# Verziókezelés git

- helyi repo létrehozása:
    > git init

- ellenőrzés: milyen fájlok változtak (Az előző verzióhoz képest)
    > git status

- előkészítjuk (stage) az új verziót, minden fájlt amiben történt módusulás
    > git add .

- ellenőrzünk: 
    > git status

- felhasználónév beállítása
    > git config user.name

- email cím beállítása
    > gti config esuer.email

- az új verzió megszületése: 
    > git commit -m "first commit"

- távoli repo létrehozása (Git Hub) 

- git a heyi repo és a git hub repo összekapcsolása, úgy hogy a presonal PAT történjen a hitelesítés (token@):
    > git remote add origin https://token@github.com/...

- az első push:
    > git push -u origin master 

- további push:
    > git push