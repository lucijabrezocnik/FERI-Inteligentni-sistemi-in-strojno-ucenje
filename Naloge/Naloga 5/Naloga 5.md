# [Naloga 5] Klasifikacija

## 📑 Naloga 

Za izdelavo te naloge uporabite podatke iz 2. naloge (university_rank_2020.csv, university_rank_other.csv, university_rank_students.xlsx). Vse podatke iz teh datotek ponovno naložite in jih nato združite v en DataFrame, poimenovan *df*, z indeks stolpcem *University*.
1. Izpišite koliko vrstic in stolpcev ima ta združen df, kakšnega tipa so posamezni stolpci in koliko je manjkajočih podatkov v posameznem stolpcu.
2. Vse manjkajoče vrednosti v številskih stolpcih nadomestite s povprečjem stolpca (pri tem si pomagajte s knjižnico *sklearn*!). Ponovno izpišite koliko je manjkajočih podatkov v posameznem stolpcu.
3. Kategorične oz. nominalne vrednosti nadomestite z najpogostejšimi vrednostmi stolpca (pri tem si pomagajte s knjižnico *sklearn*!). Ponovno izpišite koliko je manjkajočih podatkov v posameznem stolpcu.
4. Podatke brez manjkajočih vrednosti shranite v .csv datoteko poimenovano *university_rank_no_nan.csv*. Stolpci naj bodo ločeni s podpičjem (;), decimalna števila pa zapisana s piko.
5. Podatke razdelite na učno in testno množico. Vhod v vaš klasifikacijski algoritem naj predstavljajo vsi številski stolpci. Napovedovali boste vrednost *International_Outlook*. Za učenje uporabite 70% podatkov, za random state pa nastavite 789.
6. Kot klasifikacijski algoritem uporabite KNN (k-najbljižjih sosedov), s 4-imi najbližjimi sosedi. Naučite ga na učnih podatkih in nato napovejte rezultat za testno množico. Izpišite prvih pet napovedanih vrednosti in točnost napovedi.
7. Da preverite kako dobre napovedi je podal zgrajen model izpišite še vsaj tri druge metrike s katerimi lahko ovrednotimo rezultate. Delovanje teh metrik morate razumeti.
8. Izrišite graf, ki bo (smiselno!) prikazoval v kakšnem razmerju so si vrednosti *International_Outlook* in *Teaching*.
9. Ponovite cel postopek klasifikacije, le da zdaj iz vhodnih podatkov odstrante še vrednost *Teaching*. Izpišite kakšna je v tem primeru točnost klasifikacije.
10. S pomočjo stratificirane navzkrižne validacije s **šestimi rezi**, z optimizacijo metrike točnosti, preizkusite naslednje klasifikatorje:
- Odločitveno drevo
- Logistična regresija
- Linearna metoda podpornih vektorjev
- KNN
- Naivni Bayes z gaussovo porazdelitvijo
- Naključni gozd (Random forest)
- Ekstremni gozd (Extra trees)
- AdaBoost
- Gradient tree boosting
Vhod naj predstavljajo vsi številski podatki, napovedujte pa vrednost *International_Outlook*.
11. Za vsak klasifikator izpišite rezultate.
12. Izrišite stolpični graf v katerem prikažete rezultate točnosti vsakega klasifikatorja posebej. Pazite da bo graf pregleden (bodo vidna imena vseh klasifikatorjev, ...).

Pripravite datoteko Jupyter Notebook (.ipynb) ali Python datoteko (.py).

<br/><br/><br/>


## 📚 Dodatno gradivo
- predavanja <br/><br/><br/>


## 📨 Priprava naloge in zagovor
Nalogo izdelajte samostojno. Zagovor naloge bo potekal v terminu vaj.<br/><br/>


## 📅 Datum zagovora
18.11.2024<br/><br/>


## 🎯Točke
1 točka
