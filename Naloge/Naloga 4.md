# [Naloga 4] Gručenje

## 📑 Naloga 

Za izdelavo te naloge uporabite datoteko *university_rank.csv*.

1. Naložite podatke iz datoteke v dataframe. Smiselno dopolnite manjkajoče podatke. Nato odstranite še vse kategorične podatke, saj boste za nadaljnje analize potrebovali samo številske podatke.
2. Da dobite približen vpogled na koliko gruč bi bilo najbolj optimalno deliti instance uporabite hierarhično gručenje in izrišite dendrogram z maksimalno delitvijo na 4 nivoje.
3. Izvedite gručenje z uporabo K-means algoritma. Algoritem naj razdeli instance v dve gruči. Izpišite koliko je instanc v posamezni gruči.
4. Naredite analizo koliko je optimalno število gruč pri uporabi K-means algoritma (preizkusite delitev na do 7 gruč) in izrišite graf po metodi komolca. Zapišite na koliko gruč je po vašem mnenju najbolj smiselno razdeliti instance.
5. S pomočjo PCA transformacije naredite dva nova stolpca. Vrednosti iz teh dveh stolpcev prikažite v grafu raztrosa. Instance naj bodo obarvane glede na to, v katero gručo jih je razvrstil K-means algoritem. Uporabite rezultate K-means algoritma, ki po vašem mnenju razdeli instance v najbolj optimalno število gruč (iz 4. točke).
6. Naredite novo transformacijo številskih (še ne transformiranih podatkov) s pomočjo algoritma FastICA, s katero ustvarite dva nova stolpca. Na enak način kot v prejšnji točki izrišite graf raztrosa, le da tu uporabite vrednosti teh dveh novih stolpcev.
7. Raziščite kakšne so instance v posamezni gruči (imajo kakšne podobne lastnosti ipd.).
8. Nad transformiranimi podatki iz 5. točke (z algoritmom PCA) izvedite gručenje z dvema poljubnima algoritmoma gručenja (npr. Birch, SpectralClustering, …). Vse algoritme gručenja, ki jih ponuja knjižnica sklearn najdete na povezavi. Algoritmom, ki zahtevajo predhodno določitev števila gruč, določite to število glede na najdeno optimalno vrednost iz 4. točke. Za oba izrišite graf raztrosa z obarvanimi instancami glede na pripadajočo gručo.


<br/><br/><br/>


## 📚 Dodatno gradivo
- predavanja <br/><br/><br/>


## 📨 Priprava naloge in zagovor
Nalogo izdelajte samostojno. Zagovor naloge bo potekal v terminu vaj.<br/><br/>


## 📅 Datum zagovora
11.11.2024<br/><br/>


## 🎯Točke
1 točka
