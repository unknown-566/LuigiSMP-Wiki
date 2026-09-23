# Rock Bottom, boj a eventy

## Mobové v dole

V dole žijí vlastní mobové s vlastními modely: pavouci, kostry a goblini v různých variantách. **PvP je v Rock Bottomu úplně vypnuté**, bojuješ jen proti mobům, ne proti ostatním hráčům. Zabití moba má **10% šanci** na bonus rudu (upgrade Lovecké štěstí přidává +1 % za úroveň).

### Jak důl posílá moby

Důl nemá žádný budík, který by moby posílal všem naráz. Místo toho **si tě všímá**: každý hráč má vlastní neviditelný **měřič hrozby**.

1. **Měřič se plní.** Za každou vytěženou rudu přibude **5 + 1,5 × tier rudy** (uhlí 6,5, tier 5 12,5, tier 9 18,5). A pomalu i jen tím, že jsi v dole: **+1,2 za sekundu**, i když zrovna netěžíš.
2. **Když se naplní, přijde skupina.** Hranice je kolem **100 bodů**, pokaždé trochu jiná (80–120), takže se to nedá přesně odpočítat. Po skupině měřič začíná znovu skoro od nuly (0–20).
3. **Minimálně 15 sekund pauza.** Dvě skupiny na tebe nikdy nepřijdou rychleji za sebou.
4. **Měřič běží jen během výpravy**: od první vytěžené rudy do chvíle, kdy vylezeš na povrch. Na povrchu se vynuluje.

**Jak často to zhruba vychází** (když těžíš jednu rudu každé ~4 sekundy):

| Co těžíš | Skupina zhruba každých |
|---|---|
| nic, jen chodíš dolem | ~75 s |
| tier 1 | ~32 s |
| tier 3 | ~25 s |
| tier 5 | ~21 s |
| tier 7 | ~18 s |
| tier 9 | ~15 s (strop pauzy) |

### Odkud a jak přijdou

- **Ze tmy, ne před nosem.** Skupina se objeví **9–15 bloků** od tebe a důl ji přednostně posílá **za tvoje záda** (mimo to, kam se díváš). Jen v úzké slepé chodbě, kde jinde místo není, může přijít blíž (4–9 bloků).
- **Poznáš to předem.** Asi **1,5 sekundy** před příchodem začnou v tom místě padat ze stropu kamínky a ozve se odtud šramot. Podle zvuku poznáš, odkud jdou.
- **Nikdy ne u obchodníků a spawnu.** U NPC, Kováře a na spawnu Rock Bottomu (5 bloků) se mobové neobjeví.

### Velikost skupiny

Velikost závisí na tieru rudy, kterou jsi **naposledy vytěžil**:

| Tier rudy | Mobů ve skupině | Max. mobů kolem tebe (15 bloků) | Životy mobů |
|---|---|---|---|
| 1 | 2–4 | 8 | ×1,0 |
| 2 | 2–4 | 8 | ×1,2 |
| 3 | 3–5 | 9 | ×1,4 |
| 4 | 3–5 | 9 | ×1,7 |
| 5 | 4–6 | 10 | ×2,0 |
| 6 | 4–6 | 10 | ×2,4 |
| 7 | 5–7 | 11 | ×2,8 |
| 8 | 5–7 | 11 | ×3,5 |
| 9 | 6–8 | 12 | ×5,0 |

- Když už je kolem tebe tolik mobů, kolik je v tabulce, další skupina nepřijde, dokud je neporazíš (nebo neutečeš).
- **Přepad:** s šancí **6 %** je skupina o **3 moby větší**. Ohlásí ho hučení jeskyně a nápis **PŘEPAD!** nad hotbarem.
- Na celém serveru je v dole najednou nejvýš **30** mobů.

### S kamarády

Každý další hráč do **16 bloků** od tebe přidá do skupiny **+1 moba**. Skupina ale přijde **na celou partu**: měřič všech, co jsou poblíž, zároveň spadne **na polovinu**. Takže ve čtyřech nepotkáte čtyřikrát víc skupin, ale větší skupiny o něco častěji.

### Kdo přijde

Podle tieru rudy, kterou jsi naposledy vytěžil, jsi v jednom ze čtyř pásem. Čísla jsou šance, že daný člen skupiny bude tenhle mob:

| Pásmo | Tiery | Mobové a šance |
|---|---|---|
| **Starý důl** | 1–2 | Pavouk 40 % · Kostra 35 % · Pavouk s pastmi 25 % |
| **Gigantická jeskyně** | 3–4 | Jedovatý pavouk 25 % · Kostra lučištník 25 % · Kostra mág 20 % · Goblin Warrior 20 % · Pavouk 10 % |
| **Hlubší jeskyně** | 5–6 | Goblin Assassin 25 % · Goblin Archer 25 % · Kostra mág 20 % · Jedovatý pavouk 15 % · Elitní pavouk 15 % |
| **Krystalové jádro** | 7–9 | Goblin Shaman 25 % · Goblin Warrior 20 % · Goblin Assassin 20 % · Elitní kostra 20 % · Elitní pavouk 15 % |

Aby to nebyly pořád ti samí:

- **Každý člen skupiny se losuje zvlášť.** Mob, který už ve skupině je, má pro dalšího člena jen **40 %** své šance. Proto většinou přijde směs, třeba bojovník, střelec a mág, ale dvojice stejných se stát může.
- **Důl si pamatuje, co jsi potkal.** Tři typy, na které jsi narazil naposledy, mají v další skupině jen **35 %** své šance.
- **Nejvýš jeden elitní mob** (Elitní pavouk, Elitní kostra) ve skupině.

**Kdo je kdo:**

| Mob | Co dělá |
|---|---|
| Pavouk | útočí na blízko, umí rychlý výpad |
| Pavouk s pastmi | klade pasti |
| Jedovatý pavouk | vytváří jedovatou oblast |
| Elitní pavouk | dupnutí a výpad, silný |
| Kostra | útočí na blízko |
| Kostra lučištník | střílí z luku |
| Kostra mág | sesílá kouzla na dálku |
| Elitní kostra | silné útoky na blízko |
| Goblin Warrior | tank, hodně vydrží |
| Goblin Assassin | rychlý, rychle se dostane k tobě |
| Goblin Archer | střílí z luku |
| Goblin Shaman | léčí ostatní moby a hází ohnivé koule, zab ho první |

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

Nástěnka u spawnu, na které běží **tři společné cíle pro celý server** — třeba „vytěžte 7 500 rud" nebo „udělejte 150 gacha tahů". Nikdo je nezvládne sám, jde o to, co dokážete dohromady.

```
/cile
```

### Jak to běží

**Každé pondělí** se vylosují tři nové cíle. Máte na ně **pět dní** — v sobotu se kolo uzavře, vyhodnotí a rozdělí se peníze. Víkend je pauza, v pondělí se losuje znovu.

**Splníte-li všechny tři cíle dřív**, kolo se vyhodnotí hned a rovnou se vylosují tři nové — nemusí se čekat do soboty.

### Jak se dostaneš k odměně

Za každý cíl je připravený balík peněz. Aby ses o něj podělil, musíš splnit jednu podmínku:

> **Musíš přispět do všech tří cílů.** Stačí kousek do každého — ale kdo některý cíl úplně vynechá, nedostane nic.

Kolik dostaneš pak závisí na tom, **jak velký kus práce jsi odvedl**. Kdo nasbíral víc, dostane víc. Navíc je bonus pro každého, kdo stihl všechny tři.

Cíl nemusíte splnit na sto procent — když ho dáte třeba na 60 %, rozdělí se 60 % balíku. Nesplněný cíl tedy není propadlá práce.

### Co se sleduje

Podle toho, co se zrovna vylosuje: vytěžené rudy, zabití mobů, rafinované kusy, prodané rudy, gacha tahy nebo koupené upgrady. Počítá se jen to, co uděláš **v Rock Bottomu** a **v aktuálním kole** — po pondělním losování se čítače nulují.

Příkaz `/cile` ti ukáže aktuální stav všech tří cílů, kolik jsi do každého přispěl, odhad tvé výplaty a jestli už máš na odměnu nárok. Peníze přijdou automaticky, když se kolo uzavře — i když zrovna nejsi online.
