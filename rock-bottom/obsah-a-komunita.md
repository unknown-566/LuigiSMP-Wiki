# Rock Bottom, obsah a komunita

## Žebříček

```
/miningtop
```
Trvalý (neresetuje se) žebříček podle rebirthů, celkově vydělaných peněz, vytěžené rudy a zabitých mobů.

## Party

```
/miningparty
```
Skupina až **5 hráčů**. Peníze ani samotný kyslík nesdílí, každý si těží za sebe, ale party dává dvě výhody:

* **Kyslíkový buddy**: když je člen party do 15 bloků od tebe, počítá se ti nejlepší úspora kyslíku (upgrade *Kyslíková efektivita*) z celé party. Kapacita se nesdílí.
* **Ozvěna**: artefakt Ozvěna pošle spoluhráčům z party do 15 bloků část tvých nábojů, viz [Artefakty](artefakty.md).

Menu `/miningparty` ukazuje členy, jestli je boss aréna volná a stav Ore Rush.

| Příkaz | Co dělá |
|---|---|
| `/miningparty invite <hráč>` | Pozve online hráče (jen leader, party se založí prvním pozváním). Pozvánka platí **60 sekund** |
| `/miningparty accept` | Přijme pozvánku |
| `/miningparty leave` | Opustí partu (odejde-li leader, vedení převezme další člen) |
| `/miningparty kick <jméno>` | Vyhodí člena (jen leader), jde vyhodit i toho, kdo je zrovna offline |
| `/miningparty list` | Vypíše členy včetně offline |

Příkazy se doplňují klávesou Tab. Party se rozpustí, když je leader offline přes 20 minut.

**Boss má vlastní party.** Do boss arény se chodí přes `/mboss` (`/mboss invite <hráč>`, max. 4 hráči), party z `/miningparty` bosse nespouští, viz [Boj a eventy](boj-a-eventy.md).

