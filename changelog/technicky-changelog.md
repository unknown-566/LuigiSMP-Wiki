# Technický changelog

Drobné změny serveru po jednotlivých buildech. Velké novinky se oznamují na Discordu, tady je seznam všeho menšího, co se změnilo.

**Verze** `2.8.XXXXb`: `2.8` je hlavní verze serveru, `XXXX` číslo buildu (každý zápis sem = +1), `b` znamená beta.

---

## 2.8.0006b · 1. 10. 2026

### Změny
* **Výkup:** cena už se neukazuje v popisku itemu (dělala ghost itemy v inventáři). Cenu ukáže `/value` a menu výkupu.

### Opravy
* **Zvířata se vůbec nespawnovala.** Teď se objevují kolem hráčů ve dne i v noci (světlušky jen v noci), jsou vzácná. Medvědi a veverky žijí jen v lesích, tajze a kopcích, ne na pláních. Zvíře se objeví jen v chunku, kde je nejvýš jeden jiný mob.

---

## 2.8.0005b · 1. 10. 2026

### Nové
* **Ekonomika:** $50 za každou hodinu hraní (AFK se nepočítá), automatické AFK po 5 minutách nečinnosti, **denní úkoly** (`/ukoly`, 3 denně, stejný úkol nejdřív za 7 dní) a peníze za vanilla advancementy ($25 / $60 / $150 podle rámečku, dřívější se vyplatí najednou). Viz [Ekonomika a peníze](../postava/ekonomika.md).
* **Výkup u Výkupčího na spawnu** (`/vykup`): prodej věcí za peníze. Vyrobené věci mají cenu podle nejlevnějšího receptu, denní limit $150 za druh (aspoň 16, nejvýš 512 kusů), nad limit 10 % ceny. Cena je vidět rovnou v popisku itemu, `/value` ukáže cenu a zbytek limitu.
* **`/profil`** (`/profile`): menu se vším, co jde na SMP dělat. Viz [Profil](../postava/profil.md).
* **Vylepšení:** domov ($750 +$250), claim ($2 500 +$1 500) a chunk ($250 +$50) navíc, každý další dražší. `/home` ukazuje, kolik domovů je z role a kolik dokoupených.
* **Pojištění** ($500): při příští smrti v SMP tě vrátí na spawn s věcmi i XP.
* **Veřejné warpy** (`/warp`, $100 za den, max. 60 dní, 3 na hráče): koule částic a odpočet na místě, prodloužit může kdokoliv.
* **Kosmetika:** 10 stop při chůzi ($4 000 – $10 000). Viz [Za co utrácet](../postava/utraceni.md).
* **Custom mobové, zvířata:** medvědi, pandy, krokodýli, krysy, veverky, kachny, krabi a světlušky. Dají se ochočit, na medvědovi a krokodýlovi se dá jezdit. Plus 4 nové advancementy. Viz [Zvířata](../custom-mobove/zvirata.md).

### Změny
* **`/vip`:** supporteři vidí stav předplatného (kolik měsíců, od kdy, další platba).
* **Výkon:** úprava nastavení serveru a skriptů kvůli lagu při víc hráčích online.

### Opravy
* **`/back`:** $300 se nestrhávalo. Teď se platí po odpočtu, když se teleport opravdu povede.
* **Tvůrci:** živý stream na YouTube se po další kontrole falešně „ukončil“, i když běžel.

---

## 2.8.0004b · 27. 9. 2026

### Nové
* **Tvůrci, Kick:** oznámení živého streamu na Kicku ve hře i na Discordu, za jménem zelené **● LIVE**.
* **Tvůrci na webu:** profil tvůrce se na webu aktualizuje sám (kanály, sledující, právě živě, LuigiSMP videa se zhlédnutími a délkou, záznamy streamů z YouTube, Twitche i Kicku). Stav živě a videa do ~3 minut, sledující a zhlédnutí jednou za hodinu.
* **`/tvurce popis <text>`:** popis tvůrce na webu (max. 120 znaků).

### Změny
* **Tvůrci:** oznámí se jen video nebo stream, který má v názvu, popisu nebo tagu **LuigiSMP** (i "Luigi SMP" nebo "#luigismp"). Video bez slova se ještě 24 h hlídá, stream se oznámí, jakmile slovo přibude do názvu.

### Opravy
* **Spawn:** blok položený v chráněné zóně zmizel z ruky. Teď v ruce zůstane.

---

## 2.8.0003b · 26. 9. 2026

### Nové
* **Tvůrci.** Vybraní hráči s YouTube nebo Twitchem mají oznámení o novém videu a živém streamu ve hře i na Discordu (název, popis, náhled, tlačítko). Kdo nebyl online, uvidí po připojení běžící stream a nejnovější video (do 7 dní), max. 3 oznámení. Zpráva o streamu na Discordu se každé ~3 minuty aktualizuje (diváci, název, hra) a po konci ukáže délku a nejvíc diváků.
* **● LIVE za jménem** v chatu i TABu po dobu streamu: YouTube červeně, Twitch fialově.

### Změny
* **Claimy:** `/claim tp` a `/claim setspawn` jen pro VIP. `/vip` to vypisuje mezi výhodami.
* **Claimy, teleport z `/claim list`:** míří na bod z `/claim setspawn`, pokud je nastavený.

### Opravy
* **Claimy:** tlačítko Teleport v `/claim list` teleportovalo i bez oprávnění.
* **Rock Bottom, moby:** životy podle rolí a pásem z 2.8.0002b se neuplatňovaly (elitní pavouk měl dál 8 HP). Teď platí.
* **Chat:** barva suffixu už nepřetéká do zprávy.

---

## 2.8.0002b · 26. 9. 2026

### Změny
* **Rock Bottom, moby:** životy a síla zásahu podle role moba a pásma místo tieru rudy. Role v 1. pásmu: pěšák 12 HP / 2,5, střelec 9–10 / 2, past a jed 10 / 1,5, léčitel 12 / 2, **Goblin Assassin 11 / 4** (rychlý, křehký), **Goblin Warrior 24 / 3,5** (tank), elity 36–40 / 4,5. Pásma: životy ×1,0 / 1,5 / 2,1 / 2,8, zásah ×1,0 / 1,2 / 1,45 / 1,7. Assassin má v každém pásmu méně životů než Warrior a elity jsou nejsilnější.
* **Rock Bottom, meče:** poškození 4 · 4,5 · 5 · 6 · 6,5 · 7 · 8 (tier 1–7). Zlatý meč dřív dával jen 4 a byl slabší než železný. Meče se vymění samy, tier zůstává.
* **Rock Bottom:** rámečky a obrazy nejde zbourat, vzít z nich item, vložit ho ani otočit.
* **Vylepšené truhly:** z popisu zmizela věta „Polož a klikni pro otevření".

### Opravy
* **Vylepšené truhly:** obsah se po zavření ztrácel. Teď se ukládá správně. Upgrade modulem modul spotřebuje.
* **Rock Bottom, žebříček „Peníze celkem":** započítává se i úrok (dřív jen prodej u Bankéře).

---

## 2.8.0001b · 26. 9. 2026

### Nové
* **Vylepšené truhly 2.0.** Kapacita po stránkách po 45 místech: Měděná 45, Železná 90, Zlatá 135, Diamantová 180, Obsidiánová 225. Recepty upgrade modulů jsou zapnuté. Otevřít ji může víc hráčů najednou. Hoppery s nimi nefungují a s truhlou vedle se nespojí do dvojité.
* **`/pttop`**: top 10 hráčů podle odehraného času + tvoje pořadí.
* **Nastavení → Itemy na cedulích.** Shift + pravý klik na ceduli položí item z ruky. Výchozí stav: vypnuto.
* **Rock Bottom, `/mp`:** nový řádek „Čas v Rock Bottom" a žebříček podle času v Top 10.

### Změny
* **Rock Bottom, těžba:** drobky rudy při vytěžení, jiskry u rud tier 6–9, 4 varianty zvuku (u vzácných rud 3), série těžby v action baru od 3 (žlutá od 10, zlatá od 25) s milníky na 10, 25 a 50. Obnovená ruda zajiskří.
* **Rock Bottom, menu:** zvuky při otevření, nákupu a prodeji. Prodej má 1–6 cinknutí podle částky, po prodeji se ukáže částka v action baru.
* **Rock Bottom, moby:** spawnují ve skupinách 9–15 bloků od hráče, častěji za zády, podle toho, jak moc těžíš. Typy se v jedné skupině míchají. Mobi u vzácnějších rud mají víc životů.
* **Lore vylepšených truhel:** kapacita podle nových čísel.

### Opravy
* **Rock Bottom, plný inventář:** výhry z gachy, Schopnosti, odměny z bosse a nákupy u Pašeráka, které se nevejdou, přijdou do `/mail`. Ruda a drop z mobů spadne k nohám. Dřív se takové itemy ztratily.
* **Claimy:** trusted hráč s právem stavět, ale bez práva bourat, už nemůže bourat ani nabírat kbelíkem.
* **Mušketa** jde vložit do rámečku (dřív vystřelila).
* **Easter eggy:** klik na další egg už nehlásí „už máš".
