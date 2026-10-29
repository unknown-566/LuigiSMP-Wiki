# Ekonomika a peníze

Server má vlastní měnu na SMP mapě (Rock Bottom má [svoje vlastní peníze](../rock-bottom/zaklady.md), úplně samostatné).

| Příkaz | Co dělá |
|---|---|
| `/send <hráč> <částka>` | Pošle peníze jinému hráči |
| `/balance [hráč]` | Zůstatek (tvůj nebo cizí) |
| `/balancetop [stránka]` | Žebříček nejbohatších hráčů |
| `/ukoly` | Tvoje dnešní úkoly |
| `/vykup` | Výkup u Výkupčího na spawnu |
| `/value` | Kolik dostaneš za item v ruce |

Všechno najdeš i v menu [`/profil`](../hrani/profil.md). Za co peníze utratit, je na stránce [Za co utrácet](za-co-utracet.md).

## Jak vydělat

### Odehraný čas
Za každou **hodinu hraní** dostaneš **$50**. Čas, kdy jsi AFK, se nepočítá.

Když se **5 minut** nepohneš kamerou, neklikneš, nenapíšeš do chatu ani nepoužiješ příkaz, jsi automaticky AFK a ostatní to uvidí v chatu. Stačí se pohnout a AFK skončí.

### Denní úkoly (`/ukoly`)
Každý den dostaneš **3 úkoly**, každý jiného typu: těžba, zabíjení, rybaření, craftění, jídlo, chov, ochočení, enchantování a obchod s vesničany. Stejný úkol ti znovu nepřijde dřív než za 7 dní. Odměna je u každého úkolu napsaná.

- Úkoly se počítají jen v SMP (overworld, Nether, End).
- Bloky, které jsi sám položil, se po vytěžení nepočítají.
- Plodiny (pšenice, mrkev, brambory, řepa, nether wart, kakao) se počítají jen dozrálé.

### Advancementy
Za každý vanilla advancement dostaneš peníze podle rámečku:

| Rámeček | Odměna |
|---|---|
| obyčejný | $25 |
| cíl (goal) | $60 |
| výzva (challenge) | $150 |

Advancementy, které máš splněné z dřívějška, se ti vyplatí **najednou** při prvním připojení.

## Výkup

U **Výkupčího** na spawnu prodáš věci za peníze. Klikni na něj (nebo napiš `/vykup`, když stojíš do 5 bloků od něj), dej věci do menu, uvidíš, kolik za ně dostaneš, a klikni na **Prodat**. Co výkupčí nebere, ti vrátí.

Výkupčí bere skoro všechno, co jde v survivalu získat: suroviny, bloky, rostliny, květiny, jídlo, nástroje, brnění i vzácnosti jako elytra nebo music disky.

**Ceny:**
- Suroviny (rudy, dřevo, květiny, jídlo z farem…) mají pevnou cenu. Rudy vytěžené se Silk Touch stojí tolik jako to, co by z nich padlo.
- Zoxidovaná a voskovaná měď stojí stejně jako obyčejná, beton stejně jako betonový prášek.
- Vyrobené věci mají cenu podle surovin z receptu, vždy podle **nejlevnějšího** receptu. Craftěním se tedy vydělat nedá.
- Nástroje a brnění: čím víc opotřebené, tím levnější.
- Výkupčí **nebere** věci se jménem, s enchanty, custom itemy, lektvary, enchantované knihy ani plné shulkery.

**Cenu zjistíš** přes `/value` (item v ruce), rovnou v menu výkupu, kde vidíš, kolik dostaneš, nebo v [Ceníku výkupu](cenik-vykupu.md) se všemi věcmi.

**Denní limit:** u každého druhu věci můžeš denně prodat za **$150** (vždy aspoň 16 kusů, nejvýš 512 kusů). Co prodáš nad limit, vykoupí se jen za **10 %** ceny. Limit se obnovuje o půlnoci. Kolik ti zbývá, zjistíš přes `/value`.

## Objednávky (`/order`)

Obchod mezi hráči. Kdo něco potřebuje, vytvoří **objednávku**: vybere item, kolik kusů chce a kolik za kus zaplatí. Peníze se mu strhnou hned a čekají v objednávce.

- **Prodej:** v `/order` najdeš objednávky ostatních (řadit jde podle ceny za kus, novosti, počtu doručení…). Klikni na objednávku, vlož věci a peníze dostaneš hned.
- **Nákup:** v `/order` > **Tvoje objednávky** > **Nová objednávka**. Doručené věci si tam pak vybereš. Objednávku můžeš i zrušit, nevyužité peníze se ti vrátí.
- Objednávka vyprší po **7 dnech**.

`/orders` funguje stejně.

## Webshop

Server má i webshop pro reálné nákupy (kosmetika, VIP a podobně). Odkaz najdeš na webu serveru (`/web`), na VIP i přes `/vip`. Výhody VIP jsou na stránce [VIP](../vip/vyhody.md).
