# Programy SRSS, PDF editor a Tvorba vizualizací

[Stáhnout společnou instalaci pro Windows](https://github.com/programysrss-sys/programy-srss-windows/releases/latest)

Pro Windows 10/11 x64 stáhněte jeden soubor **Programy-SRSS-Komplet-1.2.3-Setup-x64.exe**. Jeden průvodce nainstaluje nebo aktualizuje Programy SRSS 1.2.3, PDF editor 1.3.2 a Tvorbu vizualizací 0.2.0. Před instalací uložte práci a zavřete PDF editor a panel SRSS. Soubory `.sha256` a `release-manifest.json` jsou kontrolní údaje, ne další instalátory.

## Kde najdete PDF

V Programech SRSS otevřete **Administrativní pomůcky → PDF editor a nástroje**. Na jednom místě jsou rychlé webové úpravy PDF a tlačítko pro otevření plného PDF editoru ve Windows. Samostatná PDF dlaždice byla z rozcestníku i panelu odstraněna. Panel má sedm nástrojů SRSS a Tvorbu vizualizací; PDF editor se otevírá ze společné sekce PDF nebo vlastním zástupcem.

PDF editor podporuje také úpravy původního textu, poznámky, formuláře, převody, správu stránek a podepisování certifikátem Windows. Přejmenování zachovává dosavadní profil, nastavení i identitu aplikace. Instalace nepřepisuje původní dokumenty a nevymazává data profilů.

## Jedna PWA a první otevření

[Programy SRSS](https://programy.srssjesenik.cz/) lze v Chrome nebo Edge nainstalovat jako jedinou PWA. Při prvním otevření v daném prohlížeči se zobrazí krátké vysvětlení: plovoucí panel, pokročilý PDF editor a místní vizualizace potřebují Windows instalaci. Nabízí přímo stažení společného balíčku a pokračování v prohlížeči. Po zavření se informace znovu nezobrazuje. Úvod si pamatuje pouze volbu, že jste informaci již viděli; klientská data do této volby neukládá.

Načítání výpisů CEE a práce s klienty fungují online i bez instalace. Panel Windows je otevírá se stejným přihlášením. Dočasná chyba připojení již nepřepíná online čtečku do prázdného ukázkového režimu. V samostatném statickém náhledu nabízí příslušná akce online čtečku i stažení instalace.

[PDF editor online](https://pdf-ctecka-web.onrender.com/) zůstává dostupný. Jeho pokročilé místní nástroje používají modul v počítači.

## Instalace a uložená práce

Společný instalátor před zahájením ověří kontrolní součty všech tří součástí. Instalace probíhá postupně a při chybě se zastaví s vysvětlením. Již dokončené součásti lze ponechat a instalaci zopakovat. Pro současné otevření místní aplikace z prohlížeče může být potřeba potvrdit spuštění Programů SRSS.

Vizualizace používají `http://127.0.0.1:4178`. Pro dosavadní projekty zachovejte stejný prohlížeč a profil. Důležité diagramy lze uložit jako `.schema.json`. Připojení Gemini nastavíte v aplikaci; veřejné balíčky neobsahují soukromý API klíč. Původní vývojová složka a její nastavení zůstávají zachované.

Pomůcky Mini nejsou pro tuto sestavu potřeba. Jejich dřívější instalace a data nejsou součástí této změny.

## Ověření

Prošlo 28 kontrol panelu a připojení čtečky a 26 testů PDF editoru. V prohlížeči bylo ověřeno jednorázové zobrazení úvodu, pokračování bez opakování, nabídka stažení v ukázce a sjednocená sekce PDF. Zabalený panel načetl osm ikon v odděleném profilu. Skutečnou novou instalaci na tomto PC si podle zadání vyzkouší uživatel sám.

Instalační balíčky nejsou podepsané certifikátem vydavatele. Podepisování PDF bylo testované syntetickým certifikátem; konkrétní kvalifikovaný certifikát PostSignum dosud nebyl k dispozici k ověření.
