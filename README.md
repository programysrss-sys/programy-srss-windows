# Programy SRSS, PDF čtečka a Tvorba vizualizací

[Stáhnout aktuální vydání pro Windows](https://github.com/programysrss-sys/programy-srss-windows/releases/latest)

| Aplikace | Verze | Účel |
| --- | --- | --- |
| Programy SRSS | panel 1.2.2 | Sedm nástrojů SRSS a přímé spouštění PDF čtečky a vizualizací |
| PDF čtečka | 1.3.1 | Samostatná čtečka a nástroje PDF pro Windows |
| Tvorba vizualizací | 0.2.0 | Samostatný místní editor diagramů s volitelným Gemini |

## Instalace

Pro Windows 10/11 x64 stáhněte jediný soubor **Programy-SRSS-Komplet-1.2.2-Setup-x64.exe**. Jeden průvodce nainstaluje nebo aktualizuje všechny tři aplikace. Soubory `.sha256` slouží k ověření kontrolního součtu; neinstalují se. Před aktualizací uložte rozpracovanou práci a zavřete aktualizovanou aplikaci.

V panelu **Programy SRSS** i v jediné PWA Programy SRSS jsou samostatná tlačítka **PDF čtečka** a **Tvorba vizualizací**. **Administrativní pomůcky** nadále obsahují převodník souborů, základní úpravy PDF a porovnání verzí dokumentů.

Pomůcky Mini nejsou pro tuto sestavu potřeba. Jejich dosavadní instalace a data zůstávají zachované; lze je dál používat samostatně například pro zvukové převody nebo běžnou kalkulačku s poznámkami.

Panel převezme dosavadní platné cesty k PDF čtečce a vizualizacím z nastavení Pomůcek, aniž by je měnil. PDF čtečku hledá také podle stávajícího zástupce na ploše a ve standardní instalační složce. Pokud aplikaci nenajde, nabídne výběr `PDFProhlizec.exe` nebo připravené složky vizualizací. Vlastní výběr si panel zapamatuje.

## Jedna PWA

Web **https://programy.srssjesenik.cz/** lze v Chrome nebo Edge nainstalovat jako jedinou PWA. Dosavadní PWA má stejnou identitu; stačí ji znovu otevřít. Obsahuje sedm nástrojů SRSS a přímé vstupy do nainstalované PDF čtečky a vizualizací. Při prvním otevření místní aplikace prohlížeč požádá o povolení spustit Programy SRSS. Nejde o vložení celých Windows aplikací do webu. Pro jejich místní spouštění musí být v tomto PC dokončená společná instalace. PDF čtečka zůstává dostupná také samostatně online.

Společný instalátor před zahájením ověří kontrolní součty všech tří součástí. Je potřeba uložit práci a zavřít PDF čtečku a panel SRSS. Server instalovaných vizualizací se při aktualizaci zastaví; další otevření ho opět spustí. Instalace probíhá postupně a při chybě se zastaví s vysvětlením. Již dokončené součásti lze ponechat a instalaci zopakovat.

## Uložená práce

Instalační balíčky neobsahují klientská data, soukromé dokumenty ani osobní nastavení. Propojení aplikací neslučuje jejich úložiště ani přihlášení.

Vizualizace nadále používají `http://127.0.0.1:4178`. Pro dosavadní místní projekty zachovejte stejný prohlížeč a profil. Důležité diagramy lze uložit do editovatelného souboru `.schema.json`. Instalace nevymazává úložiště prohlížeče. Přibalený Node.js umožňuje jejich samostatné spuštění. Připojení Gemini nastavíte přímo ve vizualizacích; veřejné balíčky neobsahují API klíč. Při přechodu z vývojové do instalační složky může být potřeba připojení znovu nastavit; původní `.env` zůstává zachovaný.

## Online aplikace

[Programy SRSS](https://programy.srssjesenik.cz/) a [PDF čtečka](https://pdf-ctecka-web.onrender.com/) zůstávají dostupné také online. Nástroje SRSS vyžadují přihlášení oprávněného pracovníka. Pokročilé místní nástroje online PDF čtečky využívají její samostatný místní modul. Přímá tlačítka pro Windows aplikace jsou v panelu pro Windows i ve společné PWA.

## Ověření vydání

Přímé spouštění, souběžná kliknutí a převzetí dosavadních cest ověřují automatické zkoušky. Zabalený panel byl spuštěn v odděleném profilu. PDF čtečka a vizualizace jsou stejné balíčky jako v předchozím vydání. PDF podpis byl ověřen syntetickým certifikátem Windows; konkrétní kvalifikovaný certifikát PostSignum nebyl k dispozici pro ověření. Instalační balíčky nejsou opatřeny podpisem vydavatele.

Vydání 1.2.2 sjednocuje ilustrace PDF čtečky a Tvorby vizualizací s modrými postavičkami ostatních nástrojů v PWA i v panelu pro Windows.
