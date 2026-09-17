# Rock Bottom, artefakty

```
/artefakty
```
(nebo tlačítko Artefakty v `/mp`)

Artefakty jsou **pasivní schopnosti, které sbírají náboje**. Nic nezapínáš: artefakt si náboje nabírá sám a **náboj se sám použije ve chvíli, kdy má efekt**. Náboje **nevyprší**, takže nic nepropadne jen proto, že zrovna děláš něco jiného.

Každý artefakt si **poskládáš sám ze 3 úlomků**, takže dva hráči málokdy nosí stejnou výbavu. Hledat nejlepší kombinace je na tom to hlavní.

Artefakty ani úlomky **nejsou itemy**. Nejde je ztratit, nezabírají inventář a **rebirth se jich netýká**.

## Jak artefakt funguje

Každý artefakt je spojený ze tří úlomků, od každého druhu jeden:

| Úlomek | Říká | Příklad |
|---|---|---|
| **Spouštěč** | **KDY** přibudou náboje | Po Ultimátu: +6 nábojů |
| **Účinek** | **CO** udělá jeden náboj a kdy se použije | Bohatá ruda: vytěžená ruda dá +0,32 rudy navíc |
| **Pečeť** | **JAK** se to upraví | Zásoba: dvojnásobný zásobník |

Z toho vznikne artefakt **„Bohatá ruda · Po Ultimátu · Zásoba"**: po Ultimátu dostaneš 6 nábojů a každá ruda, kterou pak vytěžíš, jeden spotřebuje a dá rudu navíc. Klidně až za minutu, až dobojuješ a vrátíš se k těžbě.

* **Zásobník**: každý artefakt má omezený počet nábojů. Plný zásobník další náboje nebere.
* **Víc artefaktů se stejným účinkem**: na jednu akci se použije **jen 1 náboj**, vždycky z nejplnějšího zásobníku. Víc artefaktů tak znamená, že náboje vystačí na víc akcí, ne že jedna akce dá dvojnásobek.
* Stav nábojů vidíš v `/artefakty` u každého slotu (`▮▮▮▯▯▯`). Když náboje přibudou, krátce se to ukáže nad hotbarem.

Úlomky spojuješ v **Kovárně** (`/artefakty` → Kovárna): vybereš Spouštěč, Účinek a Pečeť (najetím myší uvidíš popis každého) a v náhledu uvidíš všechna čísla.

> **Spojení je nevratné.** Artefakt už nejde rozložit zpátky na úlomky, tak si náhled pořádně prohlédni.

## Kde vzít úlomky

* **Gacha**: z běžného tahu padá s šancí **25 %** 3★ úlomek místo rud, ze vzácného tahu 4★ úlomek (Schopnost 50 % · úlomek 30 % · truhla rud 20 %). Když už máš všechny Schopnosti, vzácný tah dá místo Schopnosti úlomek. Víc o tazích na stránce **[Gacha a bannery](gacha.md)**.
* **Advancementy**: některé dávají **sadu úlomků** (jeden Spouštěč, jeden Účinek a jedna Pečeť). První sady obsahují jen díly, se kterými artefakt funguje hned, i bez Schopnosti a Ultimátu.
* **Pašerák** (`/miningpasak`): **3 libovolné úlomky stejné rarity** vymění za **1 úlomek podle tvého výběru**. Chybějící díl do buildu tak vždycky dostaneš.

## Jak silný artefakt bude

```
hodnota náboje = účinek × pečeť × kvalita × hod
```

* **Kvalita** podle hvězd úlomků, ze kterých artefakt spojíš:

| Hvězdy celkem | Příklad | Násobitel |
|---|---|---|
| 9★ | 3★ + 3★ + 3★ | ×1 |
| 10★ | 4★ + 3★ + 3★ | ×1,08 |
| 11★ | 4★ + 4★ + 3★ | ×1,16 |
| 12★ | 4★ + 4★ + 4★ | ×1,2 |

* **Hod** je náhodné číslo **80–120 %**, které artefakt dostane při spojení a má ho navždy. Dva artefakty ze stejných úlomků se proto můžou lišit.
* Přesná čísla každého artefaktu vidíš ve hře v jeho detailu. Skládají se ze stejných čísel jako skutečný účinek, takže sedí.

## Spouštěče (KDY přibudou náboje)

| Spouštěč | Kdy | Nábojů |
|---|---|---|
| **Trvale** | každých 30 s | +1 |
| **V hloubce** | každých 6 s, když jsi aspoň 30 bloků pod povrchem | +1 |
| **Při vytěžení rudy** | šance 12 % za každý tier rudy (tier 1 = 12 %, tier 5 = 60 %, tier 9 = 100 %) | +1 |
| **Při zabití moba** | pokaždé, i když moba zabije Schopnost nebo Ultimát | +1 |
| **Při zásahu mečem** | šance 60 %, nejvýš 1× za sekundu | +1 |
| **Když tě zasáhne mob** | šance 70 %, nejvýš 1× za sekundu | +1 |
| **Po Schopnosti** | když je do 12 bloků nepřítel | +2 |
| **Po Ultimátu** | když je do 12 bloků nepřítel | +6 |
| **V krizi** | zdraví pod 35 % nebo kyslík pod 15 %, nejvýš 1× za 2 minuty | +5 |

Po Schopnosti a Po Ultimátu potřebují nepřítele poblíž, aby se nedaly plnit kouzlením do vzduchu.

## Účinky (CO udělá jeden náboj)

Čísla jsou pro **9★ a hod 100 %** bez pečeti.

| Účinek | Sféra | Jeden náboj | Použije se sám | Zásobník |
|---|---|---|---|---|
| **Bohatá ruda** | Těžba | +0,32 rudy navíc (desetiny = šance na další kus) | při vytěžení rudy | 6 |
| **Kořist** | Těžba | zabitý mob dá +0,2 rudy tieru svého pásma | při zabití moba | 6 |
| **Záchrana rudy** | Těžba | při recallu zůstane 10 % rudy | při recallu, všechny náboje najednou, nejvýš 75 % | 6 |
| **Drtivý zásah** | Boj | +18 ❤ poškození k zásahu | při zásahu moba mečem, Schopností nebo Ultimátem (1 náboj na moba) | 6 |
| **Rázová vlna** | Boj | zásah mečem dá 6 ❤ i ostatním mobům do 3 bloků | při zásahu mečem, když je poblíž další mob | 10 |
| **Nabití Schopnosti** | Boj | −3 s z nabíjení Schopnosti | každou sekundu, když se nabíjí (nejvýš o polovinu jednoho nabíjení) | 6 |
| **Nabití Ultimátu** | Boj | −12 s z nabíjení Ultimátu | každou sekundu, když se nabíjí (nejvýš o polovinu jednoho nabíjení) | 6 |
| **Léčení** | Přežití | +3 ❤ | každou sekundu, když ti chybí aspoň tolik zdraví | 5 |
| **Štít** | Přežití | zásah od moba o 80 % slabší | když tě zasáhne mob | 6 |
| **Kyslík** | Přežití | +1,25 % maxima kyslíku | každou sekundu v dole, když ti chybí aspoň tolik | 5 |
| **Sprint** | Přežití | 8 s rychlosti o úroveň výš (sčítá se s upgradem) | když sprintuješ a rychlost z artefaktu zrovna neběží | 4 |

## Pečetě (JAK)

| Pečeť | Co udělá | Hodí se, když… |
|---|---|---|
| **Síla** | náboj ×1,3, zásobník ×0,6 | náboje přibývají stále a hned se spotřebují |
| **Hazard** | spuštění jen s poloviční šancí, ale nábojů najednou ×3 | chceš sázku a velké dávky |
| **Zásoba** | zásobník ×2, náboj ×1,15 | spouštěč dává velké dávky (Ultimát, krize) nebo si chceš střádat |
| **Příprava** | při vstupu do dolu +40 % zásobníku navíc, i nad jeho limit (nejvýš 1× za 3 minuty) | chceš mít náboje hned na začátku ponoru |
| **Ozvěna** | spoluhráči z party do 15 bloků dostanou 50 % tvých nábojů | hraješ v partě |
| **Rovnováha** | náboj ×1,25 | nechceš žádný háček |

Každá pečeť mění něco, co má **každý** artefakt. Neexistuje kombinace, ve které by pečeť nic nedělala.

## Sady

Když máš vybavené **3 nebo 5 artefaktů**, jejichž **účinek** patří do stejné sféry, náboje těchto účinků jsou silnější:

| Sféra | 3 artefakty | 5 artefaktů |
|---|---|---|
| **Těžba** | náboje +10 % | +20 % |
| **Boj** | náboje +10 % | +20 % |
| **Přežití** | náboje +10 % | +20 % |

Vybíráš si tak mezi čistou sférou se sadou a smíšeným buildem.

## Sloty

Vybavit můžeš až **5 artefaktů**. Sloty se odemykají podle **nejlepšího krumpáče, jaký jsi kdy měl**, a po rebirthu zůstávají:

| Krumpáč | Sloty |
|---|---|
| Dřevěný | 1 |
| Kamenný, Měděný | 2 |
| Železný, Zlatý | 3 |
| Diamantový | 4 |
| Netheritový | 5 |

Dva artefakty se **stejným Spouštěčem i Účinkem** najednou vybavit nejde. Když artefakt sundáš, jeho náboje zmizí.

## Příklady artefaktů

| Artefakt | Kvalita, hod | Co dělá |
|---|---|---|
| **Bohatá ruda · Po Ultimátu · Zásoba** | 11★, 104 % | po Ultimátu +6 nábojů (zásobník 12), každá vytěžená ruda použije 1 a dá +0,44 rudy navíc |
| **Léčení · V krizi · Rovnováha** | 9★, 100 % | když ti klesne zdraví pod 35 % nebo kyslík pod 15 %, +5 nábojů; každou sekundu tě jeden vyléčí o 3,75 ❤ |
| **Záchrana rudy · Trvale · Příprava** | 10★, 100 % | každých 30 s náboj (zásobník 6), při vstupu do dolu +3 navíc; při recallu každý zachrání 10,8 % rudy (nejvýš 75 %) |
| **Drtivý zásah · Při zabití moba · Síla** | 9★, 100 % | za každé zabití náboj (zásobník 4); další zásah dá +23,4 ❤ |
| **Kyslík · V hloubce · Zásoba** | 11★, 100 % | v hloubce každých 6 s náboj (zásobník 10); každý doplní 1,67 % maxima kyslíku |

## Ukázkové buildy

Vyzkoušené v simulátoru hraní (12★, hod 100 %), čísla jsou příjem rudy proti hraní bez artefaktů:

| Build | Pro koho | Artefakty | Výsledek |
|---|---|---|---|
| **Začátečník** | 1 slot | Kyslík · Trvale · Rovnováha | delší ponory, ~+10 % rudy |
| **Hlubinný horník** | těžba v jádru | Bohatá ruda · Trvale · Příprava, Kyslík · V hloubce · Zásoba, Léčení · V krizi · Rovnováha, Bohatá ruda · Při vytěžení rudy · Síla, Záchrana rudy · Trvale · Zásoba | ~×2 rudy, skoro žádné smrti |
| **Lovec kořisti** | hodně bojuješ | Kořist · Při zabití moba · Síla, Rázová vlna · Při zásahu mečem · Rovnováha, Nabití Schopnosti · Po Schopnosti · Hazard, Štít · Když tě zasáhne mob · Zásoba, Léčení · V krizi · Rovnováha | z bojovníka, co skoro netěží, má příjem jako horník |
| **Tank** | nebezpečné zóny | Štít · Když tě zasáhne mob · Rovnováha, Léčení · Když tě zasáhne mob · Zásoba, Léčení · V krizi · Hazard, Záchrana rudy · Trvale · Příprava, Kyslík · V hloubce · Rovnováha | poloviční počet smrtí, ~×2 rudy |
| **Party podpora** | hraješ v partě | všechno s Ozvěnou: Léčení, Kyslík, Štít, Bohatá ruda, Záchrana rudy | pomáhá tobě i spoluhráčům kolem |
