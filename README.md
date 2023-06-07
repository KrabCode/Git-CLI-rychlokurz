`cd`

- bez dalších argumentů vypíše aktuální adresář, aby fungoval git tak by měl být v rootu repozitáře kde je .git složka

---

`git pull --help`

- za každý git příkaz jde napsat --help

---

`git status`

- řekni jestli jsme lokálně aktuální oproti remote
- řekni co máme za "staged" změny pro příští commit
- řekni co máme za "not staged" změny které ještě nevíme jestli chceme přidat do příštího commitu
- řekni co máme za soubory které vůbec git ještě nesleduje ("untracked")

---

`git status -uno`

- stejné jako `git status` až na to že nevypíše "untracked" kterých může být hodně a nemusí nás zajímat

---

`git add .`

- přidej všechny "not staged" změny v aktuálním adresáři do příštího commitu (pak jsou tyto změny "staged")
	- aktuální adresář bude v IDE konzoli nejspíš root projektu

---

`git add src/HelloWorld.java`

- přidej jen tento soubor do příštího commitu (pak jsou změny tohoto souboru "staged")
- cesta k souboru je stejná jako ukáže `git status` a jde automaticky doplnit pomocí TAB

---

`git commit -m "update"`

- vytvoř lokální commit všech "staged" změn s povinnou poznámkou "update", hodí se přepsat poznámku na nějakou popisnější

---

`git push`

- pošli všechny lokální commity na remote

---

`git pull`

- stáhni data z remote branch, aktualizuj jimi lokální projekt

--- 

`git fetch`

- stáhni data o stavu remote, ale neaktualizuj zatím lokální projekt

---

`git checkout develop`

- přepřáhne na develop branch, dobré mít v tuto chvíli `git status` čisté, jinak se to bude ptát jestli stashovat změny

---

