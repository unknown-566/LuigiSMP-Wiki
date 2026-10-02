# Bloky a nástroje

## Autoplacer
💡 *Komunitní nápad.*

Položený vypadá jako obyčejný dispenser (v inventáři ho poznáš podle dřevěného bloku v „puse"), ale místo vystřelování **pokládá bloky**, šikovné na automatizované stavby.

* **Každý redstone signál = 1 blok** před otvor (páka, tlačítko, redstone hodiny, observer…). Míří tam, kam míří otvor, i nahoru nebo dolů.
* Bloky do něj dáš **pravým klikem** jako do dispenseru, nebo ho **napojíš na hopper**. Komparátor ukazuje, jak je plný.
* Pokládá jen **bloky**. Když v něm žádný není (nebo je před ním překážka), jen cvakne. Neumí bloky, které by přišly o obsah nebo jsou dvoublokové (shulker boxy, bannery, hlavy, postele, dveře, vysoké květiny). Umí i custom bloky ze serveru.
* Bloky se směrem (kmeny, schody, pozorovatele, písty…) natočí stejně jako autoplacer.
* **Shift + pravý klik prázdnou rukou** otevře menu, kde vybereš, ze kterého slotu bere (aktuální režim ukáže i lišta nad hotbarem, když autoplacer otevřeš):

| Režim | Co dělá |
|---|---|
| **Náhodně** (výchozí) | náhodný slot s blokem, jako normální dispenser |
| **Postupně** | slot 1, 2, 3… dokola: dá se tak skládat vzor ze dvou druhů bloků |
| **První slot** | vždy první blok zleva |

* Nepoloží blok do **cizího claimu** ani do chráněného spawnu zvenku a v Rock Bottomu nefunguje.
* Rozbiješ-li ho, **obsah vypadne na zem** a autoplacer dostaneš zpátky.
* Výbuch (creeper, TNT) ho zničí stejně jako dispenser: obsah vypadne celý, ale samotný autoplacer vypadne jen s běžnou šancí jako ostatní bloky (u creepera zhruba každý třetí). Pozor, když s ním pokládáš TNT.

## Vylepšené truhly
💡 *Komunitní nápad.*

Truhly s mnohem větší kapacitou. Obsah je rozdělený na **stránky po 45 místech**, mezi kterými listuješ šipkami dole v okně.

| Truhla | Místa | Stránky |
|---|---|---|
| Měděná | 45 | 1 |
| Železná | 90 | 2 |
| Zlatá | 135 | 3 |
| Diamantová | 180 | 4 |
| Obsidiánová | 225 | 5, navíc **přežije výbuch** |

**Jak ji získáš:** polož obyčejnou truhlu a klikni na ni pravým tlačítkem s **upgrade modulem**. Věci, co v ní už byly, zůstanou uvnitř. Vylepšuje se vždy o jednu úroveň (Měď → Železo → Zlato → Diamant → Obsidián). Dvojitou truhlu vylepšit nejde, nejdřív ji rozděl.

| Modul | Recept (crafting table) |
|---|---|
| Měď | 8 bloků mědi + Magic Core uprostřed |
| Železo | 8 železných bloků + Magic Core |
| Zlato | 8 zlatých bloků + Magic Core |
| Diamant | 8 diamantových bloků + Magic Core |
| Obsidián | 4 crying obsidian + 4 Netherite Nuggety + Magic Core |

* Otevřít ji může víc lidí najednou, všichni vidí stejný obsah.
* Když ji rozbiješ, **obsah vypadne na zem** a truhlu dostaneš zpátky se stejnou úrovní.
* **Hoppery s ní nefungují** (nic do ní ani z ní nepřesunou) a komparátor u ní ukazuje 0. Na automatizaci použij obyčejné truhly.
* Nespojí se s truhlou vedle do dvojité.
* V cizím claimu ji otevřeš jen s právem na kontejnery.

## Mušketa Brown Bess
💡 *Komunitní nápad.*

Historická palná zbraň, nabíjí se ve dvou krocích (nejdřív Prachový pytlík, pak Kulička), pak vystřelíš pravým klikem. Slušné poškození, ale dlouhý cooldown mezi výstřely a omezená výdrž.

## Vrhací cihla
💡 *Komunitní nápad.*

Házecí předmět (na bázi sněhové koule), zasáhne poškozením a šancí na zpomalení, a má malou šanci rozbít poblíž skleněnou tabuli.
