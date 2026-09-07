# Cestování

## TPA — teleport k hráči

| Příkaz | Co dělá |
|---|---|
| `/tpa <hráč>` | Pošle žádost o teleport k hráči |
| `/tpahere <hráč>` | Pozve hráče k sobě |
| `/tpaccept [hráč]` | Přijme žádost |
| `/tpdeny [hráč]` | Odmítne žádost |

Žádost se ti zobrazí jako klikací dialog s tlačítky přijmout/odmítnout. Pokud si nepřeješ dostávat TPA žádosti vůbec, vypni si to v [Nastavení](../nastaveni/nastaveni.md).

## RTP — náhodný teleport

```
/rtp
```
Teleportuje tě na náhodné bezpečné místo v overworldu (nebo v netheru, pokud tam zrovna jsi — server to pozná sám a přesměruje). Než tě to teleportuje, proběhne krátký odpočet — pokud se mezitím pohneš, teleport se zruší. Po použití běží krátký cooldown (aktivita na Discordu ho zkracuje, viz [Odměny za aktivitu](../odmeny/aktivita.md)).

## Spawn a Back

| Příkaz | Co dělá |
|---|---|
| `/spawn` | Teleport na spawn |
| `/back` | Vrátí tě na poslední pozici před teleportem/smrtí |

## AFK

```
/afk
```
Přepne tě do režimu "pryč od klávesnice" — ostatní hráči to uvidí.
