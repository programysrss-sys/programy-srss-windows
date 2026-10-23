# Programy SRSS, PDF editor a Tvorba vizualizací

[Stáhnout společnou instalaci pro Windows](https://github.com/programysrss-sys/programy-srss-windows/releases/download/v2026.10.23.1/Programy-SRSS-Komplet-1.2.7-Setup-x64.exe)

Pro Windows 10/11 x64 stačí jeden soubor **Programy-SRSS-Komplet-1.2.7-Setup-x64.exe** (561 MB). Obsahuje panel Programy SRSS **1.2.5**, PDF editor **1.4.2** a Tvorbu vizualizací **0.2.3**.

## Instalace

1. Stáhněte a spusťte společný instalátor.
2. Uložte práci a běžně zavřete aplikace, které se mají aktualizovat.
3. Dokončete průvodce. Součásti stejné nebo novější verze přeskočí před rozbalováním.

Dokumenty a profily se zachovávají. Při přerušené instalaci lze průvodce spustit znovu. Výchozí aplikaci pro PDF můžete zvolit dobrovolně na konci instalace; změnu potvrdíte v nastavení Windows. Výchozí aplikace pro obrázky se automaticky nenastavuje. Soubory .sha256 a release-manifest.json slouží ke kontrole stažení.

## Kde nástroje najdete

V [Programech SRSS](https://programy.srssjesenik.cz/) otevřete **Administrativní pomůcky**. Obsahují PDF editor a nástroje, převody, porovnávání dokumentů, Tvorbu prezentací a vstup do místní Tvorby vizualizací. Pomůcky Mini pro tuto sestavu nepotřebujete. Programy SRSS lze v Chrome nebo Edge nainstalovat jako jednu PWA. [PDF editor online](https://pdf-ctecka-web.onrender.com/) zůstává dostupný.

PDF editor otevírá PDF i JPG/JPEG, PNG, WebP, BMP a TIFF v samostatných kartách. Nabízí úpravy obrázků, poznámky, formuláře, převody, správu stránek, práci s XFA a vloženými přílohami i podpisy certifikátem Windows. Výchozí ukládání vytváří kopii. Schválené kompaktní lišty, spodní navigace a ikona s oranžovočervenými písmeny PDF jsou součástí vydání.

Vizualizace používají místní adresu http://127.0.0.1:4178. Pro dosavadní projekty zachovejte stejný prohlížeč a profil. Diagram lze uložit jako .schema.json. Gemini se nastavuje zvlášť; balíček neobsahuje soukromé API klíče.

## Změny a ověření

Společný instalátor je proti 1.2.4 o 25 % menší, samotný PDF instalátor o 33 %. Při místním měření klesla první instalace PDF z 6:02 na 4:55; plná finální společná instalace trvala 4:31 a přeskočení hotové instalace přibližně 4 sekundy. Jde o jednotlivá měření na jednom PC, ne garantované časy. Zrychlení samotného startu aplikace nebylo prokázáno.

Ověřeny skutečná instalace, aktualizace, odinstalace a opětovná instalace, zachování profilů a výchozích aplikací, funkce PDF/obrázků/OCR/Office/XFA a podpisy. Spouštěče fungují i bez prostředí Codexu. Instalátor aplikace násilně neukončuje; ověřuje kontrolní součty a volné místo.

Instalační balíčky nejsou podepsané certifikátem vydavatele. Podpisové testy PDF používají syntetický certifikát; nedokládají kvalifikovaný podpis ani podporu konkrétního tokenu.
