# Git verziókezezlés

## Helyi repo létrehozása

- helyi repo inicializálása
    > git init
- felhasználónév és email cím ellenőrzése
    > git config user.name
    > git config user.email
- ellenőrzés
    > git status
- előkészítjük a commit-ra (A verzió létrehozására)
    > git add .
- ellenőrzés
    > git status
- commitolás
    > git commit -m "first commit"
- commitok listázása
    > git log

## Helyi repo összekapcsolása távoli repo-val

- távoli repo létrehozása
- a helyi repo összekapcsolása a távolival
    > git remote add origin ...\\token@github.com 
- legelső alkalommal a push:
    >git push -u origin master
## Első push 
