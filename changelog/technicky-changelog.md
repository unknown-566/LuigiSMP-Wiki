# Technický changelog

Drobné změny serveru po jednotlivých buildech. Velké novinky se oznamují na Discordu, tady je seznam všeho menšího, co se změnilo.

**Verze** `2.8.XXXXb`: `2.8` je hlavní verze serveru, `XXXX` číslo buildu (každý zápis sem = +1), `b` znamená beta.

---

## 2.8.0001b · 26. 9. 2026

### Nové
* **Vylepšené truhly 2.0.** Kapacita po stránkách po 45 místech: Měděná 45, Železná 90, Zlatá 135, Diamantová 180, Obsidiánová 225. Recepty upgrade modulů jsou zapnuté. Otevřít ji může víc hráčů najednou. Hoppery s nimi nefungují a s truhlou vedle se nespojí do dvojité.
* **`/pttop`**: top 10 hráčů podle odehraného času + tvoje pořadí.
* **Nastavení → Itemy na cedulích.** Shift + pravý klik na ceduli položí item z ruky. Výchozí stav: vypnuto.
* **Rock Bottom, `/mp`:** nový řádek „Čas v Rock Bottom" a žebříček podle času v Top 10.

### Změny
* **Rock Bottom, těžba:** drobky rudy při vytěžení, jiskry u rud tier 6–9, 4 varianty zvuku (u vzácných rud 3), série těžby v action baru od 3 (žlutá od 10, zlatá od 25) s milníky na 10, 25 a 50. Obnovená ruda zajiskří.
* **Rock Bottom, menu:** zvuky při otevření, nákupu a prodeji. Prodej má 1–6 cinknutí podle částky, po prodeji se ukáže částka v action baru.
* **Rock Bottom, moby:** spawnují ve skupinách 9–15 bloků od hráče, častěji za zády, podle toho, jak moc těžíš. Typy se v jedné skupině míchají. Mobi u vzácnějších rud mají víc životů.
* **Lore vylepšených truhel:** kapacita podle nových čísel.

### Opravy
* **Rock Bottom, plný inventář:** výhry z gachy, Schopnosti, odměny z bosse a nákupy u Pašeráka, které se nevejdou, přijdou do `/mail`. Ruda a drop z mobů spadne k nohám. Dřív se takové itemy ztratily.
* **Claimy:** trusted hráč s právem stavět, ale bez práva bourat, už nemůže bourat ani nabírat kbelíkem.
* **Mušketa** jde vložit do rámečku (dřív vystřelila).
* **Easter eggy:** klik na další egg už nehlásí „už máš".
