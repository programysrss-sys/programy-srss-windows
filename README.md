# Programy SRSS a samostatné pomůcky pro Windows

[Stáhnout společné vydání](https://github.com/programysrss-sys/programy-srss-windows/releases/latest)

| Aplikace | Verze | Účel |
| --- | --- | --- |
| Programy SRSS | panel 1.2.0 | Nástroje SRSS v aplikačních oknech a vstup do místní lišty |
| Pomůcky Mini | 0.4.0 | Lišta, převodník a kalkulačka; otevření ostatních aplikací |
| PDF čtečka | 1.3.1 | Samostatná čtečka a nástroje PDF pro Windows |
| Tvorba vizualizací | 0.2.0 | Samostatný místní editor diagramů s volitelným Gemini |

## Instalace

Pro Windows 10/11 x64 stáhněte čtyři instalační soubory ze společného vydání a spusťte je. Instalační soubory `.exe` a `.msi` mají názvy příslušných aplikací. Soubory `.sha256` slouží k ověření kontrolního součtu; neinstalují se. Před aktualizací uložte rozpracovaná PDF a zavřete aktualizovanou aplikaci.

V panelu **Programy SRSS** otevře tlačítko **Lišta Pomůcky** místní lištu. Na liště jsou samostatné vstupy **Programy SRSS**, **PDF čtečka** a **Tvorba vizualizací**. Lištu lze zmenšit na samotné ikony. Skrytou lištu vrací ikona Pomůcek Mini vedle hodin nebo Ctrl+Alt+M.

PDF čtečka se hledá také podle stávajícího zástupce na ploše. Pokud ji lišta nenajde, vyberte nainstalovaný `PDFProhlizec.exe`. Vizualizace se hledají ve standardní instalační složce; lze také vybrat jejich dosavadní připravenou složku. Instalátor vizualizací obsahuje Node.js. Připojení Gemini nastavíte přímo ve vizualizacích; veřejné balíčky neobsahují žádný API klíč.

## Uložená práce

Instalační balíčky neobsahují klientská data, soukromé dokumenty ani osobní nastavení. Propojení aplikací neslučuje jejich úložiště ani přihlášení.

Vizualizace nadále používají `http://127.0.0.1:4178`. Pro dosavadní místní projekty zachovejte stejný prohlížeč a profil. Důležité diagramy lze uložit do editovatelného souboru `.schema.json`. Instalace nevymazává úložiště prohlížeče. Při přechodu z vývojové složky do nové instalační složky může být potřeba znovu nastavit připojení Gemini; původní `.env` zůstává v původní složce.

## Online aplikace

[Programy SRSS](https://programy.srssjesenik.cz/) a [PDF čtečka](https://pdf-ctecka-web.onrender.com/) zůstávají dostupné také online. Nástroje SRSS vyžadují přihlášení oprávněného pracovníka. Pokročilé místní nástroje online PDF čtečky využívají její samostatný místní modul.

## Ověření vydání

Ověřeny spouštěče, souběžné kliknutí, zachování nastavení a obnova existujících oken; zabalený panel ve zvláštním profilu a vizualizace přibaleným Node.js. PDF podpis byl ověřen syntetickým certifikátem Windows. Konkrétní kvalifikovaný certifikát PostSignum nebyl k dispozici pro ověření. Instalační balíčky nejsou opatřeny podpisem vydavatele.
