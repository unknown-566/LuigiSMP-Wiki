# Domovy a cestování

Všechny způsoby, jak se po světě dostat rychle: domovy, teleport k hráči, náhodný teleport, spawn a návrat na místo smrti. Veřejné warpy najdeš v [Za co utrácet](../ekonomika/za-co-utracet.md).

## Domovy

Vlastní systém domovů (nahrazuje klasický Essentials `/sethome`).

| Příkaz | Co dělá |
|---|---|
| `/sethome [název]` | Uloží aktuální pozici jako domov |
| `/homes` | Otevře seznam tvých domovů (menu) |
| `/home [název]` | Teleportuje se domů (bez názvu = nabídne menu) |
| `/delhome [název]` | Smaže domov |

### Kolik domovů můžu mít?

Záleží na tvojí aktivitě na Discordu. Čím vyšší úroveň, tím víc domovů. Kompletní tabulka je v [Odměny za aktivitu](../zaciname/odmeny-za-aktivitu.md).

Další domovy si můžeš **dokoupit** v `/profil` > Vylepšení (viz [Za co utrácet](../ekonomika/za-co-utracet.md)). V `/home` vidíš, kolik jich máš z role a kolik jsi dokoupil, třeba „3/9 · role 6 + koupeno 3“.

## TPA (teleport k hráči)

| Příkaz | Co dělá |
|---|---|
| `/tpa <hráč>` | Pošle žádost o teleport k hráči |
| `/tpahere <hráč>` | Pozve hráče k sobě |
| `/tpaccept [hráč]` | Přijme žádost |
| `/tpdeny [hráč]` | Odmítne žádost |

Žádost se ti zobrazí jako klikací dialog s tlačítky přijmout/odmítnout. Pokud si nepřeješ dostávat TPA žádosti vůbec, vypni si to v [Nastavení](../zaciname/nastaveni.md).

## RTP (náhodný teleport)

```
/rtp
```
Teleportuje tě na náhodné bezpečné místo v overworldu (nebo v netheru, pokud tam zrovna jsi, server to pozná sám a přesměruje). Než tě to teleportuje, proběhne krátký odpočet. Pokud se mezitím pohneš, teleport se zruší. Po použití běží krátký cooldown, aktivita na Discordu ho zkracuje (viz [Odměny za aktivitu](../zaciname/odmeny-za-aktivitu.md)).

## Spawn a Back

| Příkaz | Co dělá |
|---|---|
| `/spawn` | Teleport na spawn |
| `/back` | Vrátí tě na poslední pozici před teleportem/smrtí |

## AFK

```
/afk
```
Přepne tě do režimu "pryč od klávesnice". Ostatní hráči to uvidí.
