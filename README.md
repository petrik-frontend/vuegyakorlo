# [Név]

## Hogyan kezdj neki?

1. Jelentkezz be a GitHub szolgáltatásába a böngésződben és a VSCode szerkesztőben
2. A böngészőben forkold ezt a repository-t
3. A Settings > Pages oldalon a Source értékét állítsd gh-pages-re és mentsd el (Save)
4. Clone-ozd a saját(!) repodat a VSCode-ba
5. Írd át a Readme.md elején a [Név] részt a saját nevedre, majd commitolj és pusholj.
6. Telepítsd a függőségeket
```
  npm install
```
7. Indítsd el a fejlesztői szervert
```
  npm run serve
```
8. Indíts egy új VSCode vagy terminal ablakot.
9. Clone-ozd egy másik könyvtárba a backendet: https://github.com/hgabor/MuzeumBackend
10. Az ott leírtaknak megfelelően indítsd el, hogy elérhető legyen a kliens kódod számára.

## Hogyan dolgozz?

A főbb pontokon commitolj és pushold fel a változtatásokat. Ezt érdemes minél sűrűbben megtenni, hisz így adod majd be a feladatot.

## Hogyan fejezd be?

Add be a repod linkjét. Figyelj oda, hogy az utolsó commit idejét fogjuk nézni.

# Feladat

1. A Paintings szerkesztő kódot töltsd le és alakítsd át Statues szerkesztésére:
https://github.com/petrik-frontend/vueajax/blob/mindentbele/src/App.vue

2. Töröld ki az eddigieket vagy indíts egy új branch-et és próbáld meg segítség nélkül megvalósítani mindkét Entitás teljes adminisztrációját (Listázás, Új létrehozás, Módosítás, Törlés)

3. Amint látod a listázást, új létrehozást, módosítást jól elkülöníthető HTML és JavaScript kódokkal rendelkeznek. Készíts három komponenst.
    1. Listázza a rekordokat és elérhető innen a szerkesztés, törlés és az új létrehozás.
    2. Űrlap, amivel új entitást lehet létrehozni
    3. Űrlap, amivel meglévő entitást lehet szerkeszteni.

4. Készíts alkalmazást, amivel a két entitás(Paintings, Statues) listázó komponense megjeleníthető. Használd a VueRouter-t ehhez.

5. Addj hozzá a backend-en egy-egy új mezőt és vezesd végig a teljes alkalmazáson.
