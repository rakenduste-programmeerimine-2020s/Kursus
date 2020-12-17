# Kursus

Arvestuse hinne kujuneb tunnitööna ja iseseisvalt tehtud praktiliste ning
kirjalike tööde koondtulemusena. Esitatavate tööd põhinevad järgmistel
teemadel:

- Disainikavandi koostamine

- Vajalike serveripoole API endpoint’ide loomine/täiendamine ja testidega katmine

- Vajalike eesrakenduse komponentide loomine/täiendamine ning vajadusel testidega katmine

- Teiste koodi ülevaatamine ja tagasisde andmine

Täpsed juhendid antakse tunnis ja tehakse kättesaadavaks kursuse veebis
https://github.com/rakenduste-programmeerimine-2020s/Kursus. Arvestuse
saamiseks peavad kõik tööd olema esitatud nõutud tasemel:

- Disaini puhul on lähtutud headest tavadest

- Eesrakenduse kood on vastavalt stiilijuhendile ja kogu loodud funktsionaalsus

- Serveripoolel loodu on kaetud testidega ning andmebaasi päringud on optimeeritud (kasutatud õigeid meetodeid andmete agregeerimiseks)

- Koodi ülevaatamisel on oldud põhjalik ning antud tagasiside on kasulik koodi kirjutajale

- Vastavalt läbitud teemadele tempole jätab õppejõud õiguse kohendada iseseisvate tööde arvu ning mahtu.


## Arvestuse sooritamine

- Arenduspileti valimine toimub õppejõuga kokkuleppel loendist https://github.com/rakenduste-programmeerimine-2020s/teemaderegister/issues
- Eksamiajaks peab olema tehtud lahendus esitatud, õppejõu poolt ülevaadatud. Selleks palun esita töö vähemalt 3-5 päeva enne. Eksamiajaks peab lahendus olema Pull Requesti kaudu kood merge’tud projekti main branchi.

Eksamiajad on järgmised ja töö tuleb esitada Slacki sõnumina
  
Esimene põhieksam TA-II rühmal 
- 15.12 

Esimene põhieksam TA-I rühmal
- 17.12 

Teine põhieksam mõlemal koos 
- 14.01 

Järeleksam mõlemal rühmal
- 21.01 

## Arenduskeskkonna üles seadmine
Järgi installeerimise juhiseid projekti Readme failis [/teemaderegister](https://github.com/rakenduste-programmeerimine-2020s/teemaderegister)

## Ülesande valimine
Kõik ülesanded on välja toodud [/teemaderegister/issues](https://github.com/rakenduste-programmeerimine-2020s/teemaderegister/issues). Ole julge ka ise välja pakkuma uusi Issue'sid kui näed probleeme, mida tahaksid lahendada. Kindlasti veendu, et sellist Issue't ei ole juba lisatud. 

Sobiva ülesande valimise järel (Issue Assig endale), liiguta see projektis [/teemaderegister/projects](https://github.com/rakenduste-programmeerimine-2020s/teemaderegister/projects/1) **In Progress** tulpa.

## Ülesande täitmine (näite põhjal)
### 1. Git'i üles seadmine

Soovitan kasutada [https://www.sourcetreeapp.com/](https://www.sourcetreeapp.com/) vms Giti GUI tarkvara ja siduda see oma GitHub'i kontoga, siis peaks asi lihtsamalt käima ja saad kontrollida lihtsalt, et kasutaja vastab sellele, mis su ootused on.

Aga alternatiivina kirjeldus siin. Veendu, et projekti kaustades oled Sina oma GitHubi kontoga trükkides `git config user.name` ja `git config user.email`. Juhul kui annab tühja vastuse määra oma nimi ja GitHubi privaatne 
`git config user.name "Romil Rõbtšenkov"` ja  `git config user.name "romilrobtsenkov@users.noreply.github.com"`. Seda tuleb teha mõlemas projekti kaustas.

### 2. Feature branch
Enne kui hakkad ülesannet täitma teen **Pull**, et saada võimalikke muudatusi `main` branchist.

Seejärel loo feature branch vastava issue nimega. Näiteks tegin issue [#15](https://github.com/rakenduste-programmeerimine-2020s/teemaderegister/issues/15). Tegin uue branch'i nimega `feature/fix-footer-links/15` ja võtan selle kasutusse.

Lahendan ülesannet ning teen commit'e, et muudatused kaotsi ei läheks. Pushin muudatused ka GitHubi, tark Giti GUI rakendus oskab tekitada samanimelise branchi ja viia muudatused üles GitHubi. 

### 3. Valmis ülesande esitamine
Kontrolli, et rakendus töötab ka väiksemal ekraanil ning kui ülesanne on valmis siis, mine Github'i ja tee Pull request. Lisa sellele arusaadav pealkiri, mis võiks olla issue põhisõnum ja märgi Pull requesti sisuks (body) lisaks soovituslikele kommentaaridele ka `closes #15` vastava Issue number, mille lahendasid, et see automaatselt kinni pannaks kui Pull request liidetud. 

### 4. Merge
Kui sinu Pull request on üle vaadatud siis Pull requesti omanik liidab (merge) oma Pull requesti ise.  
1. Vali **Squash and Merge**
1. Seejäre saad muudatused kokku liita ühte commit'i, mis võiks olla kujul: **kirjeldus mis probleemi lahendasid, issue nr** NT:
```
Replace footer urls, #15
```
**Kui muudatused liidetud võid oma feature branchi ära kustutada.**
