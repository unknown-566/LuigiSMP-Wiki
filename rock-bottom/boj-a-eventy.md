# Rock Bottom, boj a eventy

## Mobové v dole

Kolem žil se objevují vlastní mobové (s vlastními modely: pavouci, kostry a goblini v různých variantách). **PvP je v Rock Bottomu úplně vypnuté**, bojuješ jen proti mobům, ne proti ostatním hráčům. Zabití mobů má šanci dropnout bonus rudu.

## Boss Dungeon: Tower Skeleton

```
/mboss
```
Týdenní boss jako v Genshinu. Sám nebo až ve čtyřech se postavíš bossovi **Tower Skeleton**. Je to obrněný skeletí bojovník se štítem, který musíš nejdřív rozbít. Na nízkém zdraví odhodí štít a přejde do agresivnější fáze s prokletým mečem.

`/mboss` (nebo tlačítko **Boss** v `/mp`) otevře menu s obtížnostmi, odměnami, tvou party a tlačítkem **Start**.

### Jak probíhá boj

1. Leader party klikne na Start, všechny členy (musí být v Rock Bottomu) to přenese do arény.
2. Máte **10 sekund na přípravu** a hned se ti otevře `/loadout`, můžeš si vyměnit Schopnost a Ultimát.
3. Objeví se boss, spí na trůnu. Probudí se, až k němu dojdeš. Nahoře v liště běží čas.
4. Když ho porazíte, dostanete odměny a za 20 sekund se vrátíte tam, odkud jste přišli. Když prohrajete, vrátíte se po pár sekundách.

Po každém boji (výhra i prohra) přijde do chatu **souhrn**: jak dlouho boj trval a za každého hráče poškození bossovi (i podíl v %), zabití kostlivci, smrti a respawny.

V aréně máš **stejný inventář jako v dole**: meč, Schopnosti, Ultimáty, upgrady i artefakty fungují stejně. Vyhodit jde jen jídlo, stejně jako v dole.

### Vlny kostlivců

Boss si volá na pomoc **kostlivce z dolu**. Vlna přijde, když mu klesne zdraví pod **75 %, 50 % a 25 %**. Na obtížnosti III a IV chodí navíc menší vlny i průběžně. Kostlivci se objeví kolem hráčů a s obtížností jsou silnější a vydrží víc.

| | Vlna při ztrátě zdraví | Průběžné vlny |
|---|---|---|
| I | 2× kostlivec | ne |
| II | 2× kostlivec, 1× lučištník | ne |
| III | 2× kostlivec, 1× lučištník, 1× mág | každou minutu |
| IV | 2× elitní kostlivec, 1× mág, 1× lučištník | každých 45 s |

Kostlivci v aréně nedávají rudu.

### Dash bosse

Se štítem se boss občas rozběhne proti tobě. Kdo mu stojí v cestě, dostane ránu a odletí. O zeď se zastaví.

### Obtížnosti

Další obtížnost se odemkne, až porazíš tu předchozí.

| | Obtížnost | Zdraví bosse | Síla útoků | Čas | Doporučený meč |
|---|---|---|---|---|---|
| I | Probuzení | ×1 | ×0,5 | 4 min | T3 |
| II | Strážce věže | ×1,8 | ×0,8 | 4,5 min | T5 |
| III | Pán duší | ×2,8 | ×1,1 | 5 min | T6 |
| IV | Věčná noc | ×4 | ×1,4 | 6 min | T7 |

Ve více lidech má boss víc zdraví: 2 hráči ×1,5, 3 hráči ×2, 4 hráči ×2,5.

### Odměny

| | Peníze | Úlomky artefaktů | Rafinovaná ruda | Navíc |
|---|---|---|---|---|
| I | 2 000 | 2× 3★ | 4× Diamond | |
| II | 5 000 | 2× 3★, 1× 4★ | 5× Emerald | |
| III | 9 000 | 2× 4★ | 6× Amethyst Shard | 10 % šance na novou Schopnost |
| IV | 15 000 | 3× 4★ | 8× Netherite Scrap | 20 % šance na novou Schopnost |

**Plné odměny dostaneš 3× za týden** (obnova v pondělí). Pak můžeš bojovat dál, ale dostaneš jen 10 % peněz.

**Bonus za první poražení** každé obtížnosti (jednou navždy, i přes týdenní limit):

* I: 3 000 peněz
* II: 6 000 peněz a 1× 4★ úlomek
* III: 12 000 peněz a nová Schopnost (když už máš všechny, tak 2× 4★ úlomek)
* IV: 25 000 peněz a 3× 4★ úlomek

Odměny dostane každý člen party, který je v aréně, i když zrovna leží mrtvý.

### Smrt a respawn

Když padneš, nic neztratíš a sleduješ boj jako divák. Máš **15 sekund** na `/mboss respawn` za peníze (1 000, pak pokaždé o 40 % dráž). Když padne celá party, nebo vyprší čas, boss vyhrál. Mezi dvěma boji je minuta pauza.

| Příkaz | Co dělá |
|---|---|
| `/mboss` | Menu: obtížnosti, odměny, start |
| `/mboss invite <hráč>` | Pozve do party (max. 4 hráči) |
| `/mboss accept` | Přijme pozvánku |
| `/mboss leave` | Opustí party (leader ji tím rozpustí) |
| `/mboss kick <hráč>` | Vyhodí hráče z party (jen leader) |
| `/mboss start <1-4>` | Spustí boj bez menu (jen leader) |
| `/mboss respawn` | Koupí respawn, když padneš |

## Globální cíle

Nástěnka u spawnu, na které běží **tři společné cíle pro celý server** — třeba „vytěžte 2 500 rud" nebo „udělejte 50 gacha tahů". Nikdo je nezvládne sám, jde o to, co dokážete dohromady.

```
/cile
```

### Jak to běží

**Každé pondělí** se vylosují tři nové cíle. Máte na ně **pět dní** — v sobotu se kolo uzavře, vyhodnotí a rozdělí se peníze. Víkend je pauza, v pondělí se losuje znovu.

### Jak se dostaneš k odměně

Za každý cíl je připravený balík peněz. Aby ses o něj podělil, musíš splnit jednu podmínku:

> **Musíš přispět do všech tří cílů.** Stačí kousek do každého — ale kdo některý cíl úplně vynechá, nedostane nic.

Kolik dostaneš pak závisí na tom, **jak velký kus práce jsi odvedl**. Kdo nasbíral víc, dostane víc. Navíc je bonus pro každého, kdo stihl všechny tři.

Cíl nemusíte splnit na sto procent — když ho dáte třeba na 60 %, rozdělí se 60 % balíku. Nesplněný cíl tedy není propadlá práce.

### Co se sleduje

Podle toho, co se zrovna vylosuje: vytěžené rudy, zabití mobů, rafinované kusy, prodané rudy, gacha tahy nebo koupené upgrady. Počítá se jen to, co uděláš **v Rock Bottomu** a **v aktuálním kole** — po pondělním losování se čítače nulují.

Příkaz `/cile` ti ukáže aktuální stav všech tří cílů, kolik jsi do každého přispěl, odhad tvé výplaty a jestli už máš na odměnu nárok. Peníze přijdou automaticky, když se kolo uzavře — i když zrovna nejsi online.
