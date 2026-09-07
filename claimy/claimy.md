# Claimy — ochrana pozemku

Claimy chrání tvoji stavbu před cizími hráči — nikdo ti bez dovolení nerozbije bloky, neotevře truhly ani nic jiného. Funguje po **chunkách** (16×16 bloků).

## Založení a rozšíření

```
/claim
```
Založí nový claim na chunku, kde stojíš. Jestli stojíš hned vedle **svého vlastního** claimu, místo nového claimu se ten stávající **rozšíří** o další chunk.

```
/claim create <název>
```
To samé, ale rovnou dáš claimu jméno (funguje stejně chytře — vedle vlastního claimu rozšíří místo založení nového).

```
/claim addchunk
```
Přidá chunk, na kterém stojíš, k sousednímu vlastnímu claimu (musíš stát hned vedle něj).

```
/claim delchunk
```
Odebere chunk, na kterém stojíš, z claimu (claim musí mít aspoň 2 chunky).

```
/claim unclaim
```
Smaže celý claim, ve kterém stojíš (s potvrzením).

## Kolik claimů/chunků můžu mít?

Záleží na tvojí aktivitě na Discordu — viz [Odměny za aktivitu](../odmeny/aktivita.md). Počet chunků je **celkový součet přes všechny tvoje claimy dohromady**, takže si můžeš rozdělit "rozpočet" mezi víc menších území, nebo mít jedno velké.

## Správa claimu

| Příkaz | Co dělá |
|---|---|
| `/claim rename <nový_název>` | Přejmenuje claim |
| `/claim list` | Seznam tvých claimů |
| `/claim tp <název>` | Teleport do claimu (tvého nebo kam tě pozvali) |
| `/claim setspawn` | Nastaví přesný bod, kam tě `/claim tp` doteleportuje |
| `/claim transfer <hráč>` | Převede claim na jiného hráče |
| `/claim see` | Vizuálně ti ukáže hranice claimu (jen ty to vidíš) |

## Kamarádi a přístup

```
/claim trust <hráč>
/claim untrust <hráč>
```
Přidá/odebere hráče do "trusted" skupiny — trusted hráči mají v tvém claimu víc práv než cizí (podle nastavení flagů).

```
/claim settings
```
Otevře menu s podrobným nastavením, co smí dělat **trusted** hráči a co **ostatní** (stavět, bourat, otevírat truhly/dveře, sbírat/vyhazovat itemy, útočit na entity...) — a claim-wide nastavení jako PvP, exploze, mobové a šíření ohně.

## Fly v claimu

```
/claim fly
```
Zapne/vypne létání — funguje jen uvnitř claimu, kde máš přístup (vlastní nebo trusted). Opustíš-li claim, létání se samo vypne.
