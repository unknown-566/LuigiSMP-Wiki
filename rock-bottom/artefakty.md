# Rock Bottom, artefakty

```
/artefakty
```
(nebo tlačítko Artefakty v `/mp`)

Artefakty jsou **pasivní schopnosti**. Nic nezapínáš, fungují samy, když nastane jejich chvíle. Každý artefakt si **poskládáš sám ze 3 úlomků**, takže dva hráči málokdy nosí stejnou výbavu. Hledat nejlepší kombinace je na tom to hlavní.

Artefakty ani úlomky **nejsou itemy**. Nejde je ztratit, nezabírají inventář a **rebirth se jich netýká**.

## Jak artefakt vzniká

Každý artefakt je spojený ze tří úlomků, od každého druhu jeden:

| Úlomek | Říká | Příklad |
|---|---|---|
| **Spouštěč** | **KDY** se artefakt spustí | Při zabití moba |
| **Účinek** | **CO** se stane | Léčení |
| **Pečeť** | **JAK** se účinek upraví | Ozvěna (dostane ho i tvoje party) |

Z toho vznikne artefakt **„Léčení · Při zabití moba · Ozvěna"**: když zabiješ moba, vyléčí tebe i parťáky kolem.

Úlomky spojuješ v **Kovárně** (`/artefakty` → Kovárna): vybereš Spouštěč, Účinek a Pečeť, uvidíš náhled čísel a potvrdíš.

> **Spojení je nevratné.** Artefakt už nejde rozložit zpátky na úlomky, tak si náhled pořádně prohlédni.

## Kde vzít úlomky

* **Gacha**: z běžného tahu padá s šancí **25 %** 3★ úlomek místo rud, ze vzácného tahu 4★ úlomek (Schopnost 50 % · úlomek 30 % · truhla rud 20 %). Když už máš všechny Schopnosti, vzácný tah dá místo Schopnosti úlomek. Víc o tazích na stránce **[Gacha a bannery](gacha.md)**.
* **Advancementy**: některé dávají **sadu úlomků** (jeden Spouštěč, jeden Účinek a jedna Pečeť), takže si hned spojíš první artefakt.
* **Pašerák** (`/miningpasak`): **3 libovolné úlomky stejné rarity** vymění za **1 úlomek podle tvého výběru**. Chybějící díl do buildu tak vždycky dostaneš.

## Jak silný artefakt bude

```
síla = základ účinku × síla spouštěče × pečeť × kvalita × souznění × hod
```

* **Kvalita** podle hvězd úlomků, ze kterých artefakt spojíš:

| Hvězdy celkem | Příklad | Násobitel |
|---|---|---|
| 9★ | 3★ + 3★ + 3★ | ×1 |
| 10★ | 4★ + 3★ + 3★ | ×1,12 |
| 11★ | 4★ + 4★ + 3★ | ×1,25 |
| 12★ | 4★ + 4★ + 4★ | ×1,4 |

* **Hod** je náhodné číslo **80–120 %**, které artefakt dostane při spojení a má ho navždy. Dva artefakty ze stejných úlomků se proto můžou lišit.
* **Souznění**: když Spouštěč i Účinek patří do **stejné sféry** (Těžba, Boj, Přežití), artefakt je o **15 %** silnější.
* **Strop**: stejný účinek z víc artefaktů se sčítá, ale jen do stropu v tabulce níž.

Přesná čísla každého artefaktu vidíš ve hře v jeho detailu. Počítají se stejně jako skutečný účinek, takže sedí.

## Spouštěče (KDY)

„Síla" říká, kolikrát silný účinek spouštěč dává. Častý spouštěč je slabší, vzácný silnější.

| Spouštěč | Sféra | Síla | Šance | Prodleva |
|---|---|---|---|---|
| **Trvale** | žádná | ×0,5 | vždy | buffy platí pořád, okamžité účinky každých 12 s |
| **Při vytěžení rudy** | Těžba | ×0,8 | 12 % | 3 s |
| **Při zabití moba** | Boj | ×1 | 100 % | 2 s |
| **Při zásahu mečem** | Boj | ×0,7 | 25 % | 2 s |
| **Po Schopnosti** | Boj | ×1,3 | 100 % | — |
| **Po Ultimátu** | Boj | ×3 | 100 % | — |
| **V krizi** | Přežití | ×3 | zdraví pod 35 % nebo kyslík pod 20 % | 60 s |
| **V hloubce** | Přežití | ×0,8 | aspoň 30 bloků pod povrchem | buffy platí, dokud jsi v hloubce, okamžité účinky každých 12 s |

## Účinky (CO)

Čísla jsou **základ při síle ×1**. Buffy platí po dobu trvání (u Trvale a V hloubce pořád), okamžité účinky se stanou hned.

| Účinek | Sféra | Druh | Základ | Trvání | Strop |
|---|---|---|---|---|---|
| **Dvojitá ruda** | Těžba | buff | +20 % šance na dvojitou rudu | 6 s | +60 % |
| **Obnova nodu** | Těžba | buff | +15 % šance, že se ruda hned obnoví | 6 s | +40 % |
| **Magnet** | Těžba | buff | přitahuje rudu do 6 bloků | 8 s | 10 bl. |
| **Dosah** | Těžba | buff | +2 bloky dosahu | 8 s | +4 bl. |
| **Noční vidění** | Těžba | buff | noční vidění | 12 s | — |
| **Síla útoku** | Boj | buff | +20 % poškození mobům (i Schopnosti a Ultimáty) | 5 s | +60 % |
| **Zkrácení cooldownu** | Boj | okamžitý | −2 s z cooldownu Schopnosti | — | 4 s |
| **Léčení** | Přežití | okamžitý | +2 ❤ | — | 10 ❤ |
| **Absorpce** | Přežití | okamžitý | 2 ❤ zlatých srdíček | 8 s | 10 ❤ |
| **Kyslík** | Přežití | okamžitý | +12 kyslíku | — | 60 |
| **Rychlost** | Přežití | buff | +1 úroveň rychlosti (sčítá se s upgradem) | 5 s | +2 úrovně |
| **Záchrana rudy** | Přežití | buff | +25 % rudy ti zůstane při recallu | 20 s | 60 % |

## Pečetě (JAK)

| Pečeť | Co udělá |
|---|---|
| **Síla** | účinek ×1,5 |
| **Pohotovost** | poloviční prodleva, šance ×1,5 |
| **Vytrvalost** | trvání ×2 |
| **Ozvěna** | 60 % účinku dostanou i členové tvé party do 15 bloků |
| **Hazard** | účinek ×2,2, ale poloviční šance a delší prodleva |
| **Rovnováha** | účinek i trvání ×1,15 |

## Sady

Když máš vybavené **3 nebo 5 artefaktů**, jejichž **účinek** patří do stejné sféry, dostaneš trvalý bonus navíc:

| Sféra | 3 artefakty | 5 artefaktů |
|---|---|---|
| **Těžba** | +8 % šance na dvojitou rudu | +16 % |
| **Boj** | +10 % poškození mobům | +20 % |
| **Přežití** | +15 % rudy zůstane při recallu | +30 % |

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

Dva artefakty se **stejným Spouštěčem i Účinkem** najednou vybavit nejde.

## Příklady

| Artefakt | Kvalita, hod | Co dělá |
|---|---|---|
| **Léčení · Při zabití moba · Ozvěna** | 11★, 100 % | za každé zabití +2,5 ❤ tobě a +1,5 ❤ parťákům kolem, nejvýš jednou za 2 s |
| **Dvojitá ruda · Při vytěžení rudy · Pohotovost** | 12★, 110 % | s šancí 18 % na 6 s +28 % šance na dvojitou rudu (se souzněním), prodleva 1,5 s |
| **Síla útoku · Po Ultimátu · Vytrvalost** | 10★, 100 % | po Ultimátu +60 % poškození (strop) na 10 s |
| **Dosah · Trvale · Síla** | 9★, 100 % | trvale +1,5 bloku dosahu |

## Staré artefakty

Pokud jsi měl artefakty z dřívějšího systému (rodiny Dosah, Štěstí, Lovec…), při prvním vstupu do Rock Bottomu se ti **převedly na nové artefakty** s podobným účinkem a staré itemy zmizely z inventáře. Najdeš je v `/artefakty`.
