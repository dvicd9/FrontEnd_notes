# Git (HUB)

### Local repo:
*(fájl látrehozása / szerkesztése -> először stage (add) utána commit a local repo-ba)*

> `git init` -> repo incializálása

> `git status` -> repoban fájlok státusza

### Stage (még nem verzió):

> `git add -h` -> segítség

> `git add `*`filename.txt`* -> stage-re rakja a fájlt

> `git add `*`*.txt`* -> összes .txt stage-be

> `git add `*`*.*`* -> összes file

> `git add .` -> összes mappa / file

> `git reset `*`fájlnév`* -> leszedi a stage-ről

### Commit (verzió):

> `git commit -m` -> commitálás Stage-ről a repo-ba
	`-m` => message

> `git log` -> milyen commit-ok voltak

### Repository:
> `git remote add `*`*alias* *Git URL*`*
    *(alias-szal hivatkozunk)* 

pl. -> ` remote add origin https://github.com/dvicd9/teszt.> `
> `git push `*`*alias* *branch*`* -> commit-ok feltöltése Git szerverrel
	-> branch: ahova dolgozunk -> a fő branch: master

*pl. `git push origin master`*

> `git clone `*`*Git URL* (*branch*)`* -> fájlok letöltése Git szerverről *(létrehoz egy mappát a local repo-ba a projekt nevével!)*

> `git push` -> ha le van klónozva a repo

> `git diff ...` -> külünbség a lokális repo-ban és a repoban
- `HEAD` -> összes file
- *`fájlnév`* -> adott file
- `--staged` -> a stage-en levőket hasonlítja össze

> `git pull origin (main)` -> leszedi a legújabb fájlokat a local repoba (?)

> `git checkout `*`*fájlnév*`* -> eldobja a lokális módosítást (unstaged) és betölti a repo-ból