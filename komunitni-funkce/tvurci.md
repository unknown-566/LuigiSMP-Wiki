# Tvůrci

Někteří hráči tvoří videa nebo streamují. Když vydají nové video na YouTube nebo jdou živě na YouTube či Twitchi, server to oznámí:

* **ve hře** zprávou v chatu s tlačítkem na video nebo stream,
* **na Discordu** s názvem, popisem, náhledem a odkazem.

Kdo zrovna nebyl online, uvidí po připojení to, co zmeškal: stream, který právě běží, a nejnovější video od každého tvůrce (nejvýš týden staré), pokud ho ještě neviděl.

Kdo je právě živě, má za jménem v chatu i v TABu **● LIVE**: červeně YouTube, fialově Twitch. Když stream skončí, zmizí to samo.

## Pro tvůrce

Oznámení mají jen tvůrci, které vybere admin. Pokud tvoříš a chceš ho, napiš adminovi.

| Příkaz | Co dělá |
|---|---|
| `/tvurce` | Ukáže tvoje nastavené kanály |
| `/tvurce youtube <@kanál>` | Nastaví YouTube kanál (handle z adresy kanálu, např. `@luigismp`) |
| `/tvurce twitch <login>` | Nastaví Twitch kanál |
| `/tvurce off <youtube\|twitch>` | Vypne oznámení pro danou platformu |

Oznamují se jen veřejná videa a streamy. Server kontroluje každé ~3 minuty, takže oznámení může přijít o pár minut později.
