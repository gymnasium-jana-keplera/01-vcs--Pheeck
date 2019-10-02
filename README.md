# Domácí úkol č. 1 - verzovací systém GIT

V rámci prvního dobrovolného domácího úkolu byste si měli prakticky procvičit práci s verzovacím systémem Git.

## Úkoly
1.  Naklonujte si na Váš osobní počítač tento repozitář.
2.  Nastavte kontaktní údaje pro tvorbu commitů na Vaše reálné jméno a školní e-mailovou adresu.
3.  Vytvořte soubor `LICENSE` a vložte do něj text libovolné open-source licence. Tento soubor commitněte.
4.  Vytvořte soubor `fact.sh` s následujícím obsahem:
```bash
#!/bin/bash
seq -s "*" 1 500 |bc
``` 
5.  Vytvořený soubor commitněte.
6.  Vytvořte novou větev `feature-1`. Tuto větev odešlete do repozitáře na vzdáleném serveru.
7.  V nové větvi změňte soubor `fact.sh` tak, aby počítal faktoriál čísla 400. Změnu commitněte a odešlete na server.
8.  Přepněte se do větve `master` a upravte soubor `fact.sh` tak, aby počítal faktoriál čísla 300. Změnu commitněte a odešlete na server.
9.  Proveďte merge větve `feature-1` s větví `master`. Konflikt vyřešte zachováním verze z větve `feature-1`.
10.  Ve větvi `feature-1` vytvořte soubor `10to7.sh` s následujícím obsahem:
```bash
#!/bin/bash
echo "ibase=10;obase=7; 10007" | bc 
```
11.  Soubor vytvořený v předchozím kroku commitněte a odešlete do větve `feature-1` na vzdáleném serveru.
12.  Přepněte se do větve `master` a proveďte merge větve `feature-1`. Výsledek odešlete na vzdálený server.
13.  Zkopírujte soubor `.git/config` do kořene projektu a proveďte jeho commit.
14.  Vytvořte soubor `refs.txt` a vložte do něj obsah souborů `.git/refs/heads/*`.
15.  Vytvořte soubor `refs2.txt` a vložte do něj obsah souborů `.git/refs/remotes/origin/*`.
16.  Vytvořte soubor `status.txt`. Do tohoto souboru uložte výstup příkazu `git status`.
17.  Commitněte pouze soubory `refs.txt` a `status.txt`.
18.  Změňte obsah souboru `status.txt` tak, aby obsahoval aktuální výstup příkazu `git status`.
18.  Vytvořte commit všech nových i upravených souborů.
19.  Do nového souboru `author.txt` uložte e-mailovou adresu autora prvního commitu. Tento soubor commitněte a změny odešlete na server.
20.  Pokuste se stáhnout změny ze vzdálého serveru. Výstup k tomu určeného příkazu uložte do souboru `output.txt`. Tento soubor commitněte a commity odešlete na server.
