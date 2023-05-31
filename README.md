# Parhuzamos_algoritmusok
A féléves feladatnak a gyökkereső szelő módszert választottam. Ezt megcsináltam szekvenciálisan és párhuzamosan.
Párhuzamosítást Posix szálakkal és OpenMP függvénykönyvtárral értem el.

Az alábbi harmadfokú egyenletnek határoztam meg a gyökét 10^-8 -os pontosággal.

![függvénykép.png](https://github.com/Empty210/H5BEU4_parh_alg/tree/main/Feleves_feladat/függvénykép.png)

Itt azt mértem 1,2,3 szálon, hogy mennyi idő alatt fut le a program és ezt vetettem össze az OpenMP-s és szekvenciális futási idővel.

![mértem](https://github.com/Empty210/H5BEU4_parh_alg/tree/main/Feleves_feladat/Szelő módszer posix szál.png)

A 3. beadandó egy kódoló algoritmust az ún. Subtitution-Ciphernek egy kezdő változatát programoztam le.
Itt azt mértem, hogy egy "nagy" bemenet estén(egy random generált string ami a c fájlok elején kommentbe megtalálható) mennyi időbe telik 10 darab kódolás és dekódolás.


![mértem](https://https://github.com/Empty210/H5BEU4_parh_alg/tree/main/Feleves_feladat/Sub-Cipher.png)
