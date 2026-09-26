# Tvůrci

Někteří hráči tvoří videa nebo streamují. Když vydají nové video na YouTube nebo jdou živě na YouTube, Twitchi či Kicku, server to oznámí:

* **ve hře** zprávou v chatu s tlačítkem na video nebo stream,
* **na Discordu** s názvem, popisem, náhledem a odkazem. U streamu se zpráva průběžně aktualizuje (diváci, název, hra) a po konci ukáže délku a nejvíc diváků.

Kdo zrovna nebyl online, uvidí po připojení to, co zmeškal: stream, který právě běží, a nejnovější video od každého tvůrce (nejvýš týden staré), pokud ho ještě neviděl.

Kdo je právě živě, má za jménem v chatu i v TABu **● LIVE**: červeně YouTube, fialově Twitch, zeleně Kick. Když stream skončí, zmizí to samo.

## Pro tvůrce

Oznámení mají jen tvůrci, které vybere admin. Pokud tvoříš a chceš ho, napiš adminovi.

| Příkaz | Co dělá |
|---|---|
| `/tvurce` | Ukáže tvoje nastavené kanály |
| `/tvurce youtube <@kanál>` | Nastaví YouTube kanál (handle z adresy kanálu, např. `@luigismp`) |
| `/tvurce twitch <kanál>` | Nastaví Twitch kanál (jméno z adresy twitch.tv/…) |
| `/tvurce kick <kanál>` | Nastaví Kick kanál (jméno z adresy kick.com/…) |
| `/tvurce off <youtube\|twitch\|kick>` | Vypne oznámení pro danou platformu |

**Oznámí se jen obsah o serveru.** Video nebo stream musí mít v názvu, popisu nebo tagu slovo **LuigiSMP** (stačí i "Luigi SMP", velikost písmen nevadí). Ostatní videa a streamy se neoznamují a LIVE za jménem se neukáže.

* Zapomněl jsi slovo u videa? Doplň ho do popisu, video se ještě 24 hodin hlídá.
* U streamu stačí slovo přidat do názvu kdykoliv během vysílání.

Oznamují se jen veřejná videa a streamy. Server kontroluje každé ~3 minuty, takže oznámení může přijít o pár minut později.
