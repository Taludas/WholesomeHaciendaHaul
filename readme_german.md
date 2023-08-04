# The Wholesome Hacienda Haul 

![Thumbnail](https://user-images.githubusercontent.com/64583643/167893634-35b83fe1-ad75-4c35-acf5-541b7804e98d.png)

Dies ist eine modulare Überarbeitung des DLC10 Keim der Hoffnung, die fast jeden Aspekt des neu eingeführten Gameplays im Sandbox Mod verändert. Wählt aus, welche Änderungen euch am besten gefallen!

Wenn euch diese Mod gefällt und ihr mich unterstützen wollt, könnt ihr sie gerne mit euren Freunden teilen. Ihr könnt mir auch einen Kaffee bei Ko-Fi kaufen (ja, ich möchte meinen Kaffeekonsum auf die Höhe der Investoren bringen!)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/W7W8L558T)

## How to use

- Verwende entweder den [iModYourAnno](https://github.com/anno-mods/iModYourAnno/releases) Mod-Manager oder kenne wie man [Mods manuell installiert](https://github.com/jakobharder/anno1800-mod-loader#mods).
- Wenn du die Mod manuell herunterlädst, benutze das Archiv von [GitHub releases](https://github.com/Taludas/WholesomeHaciendaHaul/releases). Ladet nicht das gesamte Repo herunter!
- Wählt die relevanten Mods aus und zieht sie in euren 1800 Mod-Ordner oder benutzt den iModYourAnno Mod Manager zur manuellen Installation.

**If you change from older versions to version 2.x, it is extremely important to remove all older versions of this mod. The Mod is now a single mod folder and modules are disabled through editing assets.xml file or through iModYourAnno Mod Manager! If you use iModYourAnno, please notice, that you have to turn on all toggles in the Tweaking tab to get the intended 'Full Experience'!**

If you already used iMYA to tweak the mods, I'd advice to remove the stored settings .json files for the respective mod form iMYA storage location: Go to .../Anno 1800/.imya/tweaks/... and remove the .json files for the mods in description: '[Overhaul] The Wholesome Hacienda Overhaul.json'. That way you can start with a fresh iMYA tweaking tab after the 2.1.0 update.

## Mod-Bilder
Du kannst eine Galerie von Bildern von meiner Mod [hier](docs/) finden.

## Changelog
<details>
    <summary>Patch Notes Version 2.2.2</summary>

* Fixes:
  * Ein Problem wurde behoben, bei dem die Hacienda Orchideenfarm eine unsichtbare, durchsichtige Wand im Inneren des Haupthauses hatte.
  * Ein Problem mit fehlenden Hacienda-Straßenmodulen im Baumenü nach Deaktivierung des Moduls "True Hacienda Streets" wurde behoben.
  * Es wurde eine "Gesperrt-Warnung" hinzugefügt, wenn man versucht, alte Hacienda-Sraßen-Module in einen Speicherstand zu kopieren, wenn man das Modul "True Hacienda Streets" verwendet. Made by @Qurila.
</details>

<details>
    <summary>Patch Notes Version 2.2.1</summary>

* Fixes:
  * Ein Problem wurde behoben, bei dem der Hacienda Kräutergarten im Sandbox-Modus nicht wie vorgesehen freigeschaltet wurde (1 Artista).

</details>

<details>
    <summary>Patch Notes Version 2.2.0</summary>
    
![image](https://github.com/Taludas/WholesomeHaciendaHaul/assets/64583643/422a3cf1-2463-413c-9da3-bb5005e14364)

* Ergänzungen:
  * Neue Hacienda Farmen für Kräuter und Orchideen!
  * Anpassungen für alle Mods an die neuen Funktionen von iModYourAnno v0.5 (neue Bilder, Standardoptionen werden automatisch im Tweaking-Tab umgeschaltet). ***WARNUNG***: Passt eure Tweaking-Optionen in iMYA an, bevor ihr weiterspielt, da diese nach dem Update auf v0.5 verloren gehen!

* Fixes:
  * Es wurde ein Problem behoben, bei dem nach der Deaktivierung des Mod-Moduls "Residences must be upgraded" keine Möglichkeit bestand, die Hacienda-Häuser der Obrero und Artista im neuen Baumenü zu bauen.

</details>


<details>
    <summary>Patch Notes Version 2.1.0</summary>

* Neue Features:
    - Die Mod Free Farmfield Placement wurde in die [Gameplay Mods Collection](https://github.com/Taludas/GameplayModsCollection) verschoben. Diese Mod ist eine eigenständige Mod und wird in Zukunft auch als solche behandelt werden.
    - Diese Mod ist jetzt noch besser anpassbar. Mit iMYA ist es nun möglich, ganze Teile dieser Mod abzuschalten. Jedes Modul ist nun völlig unabhängig voneinander (ich empfehle aber trotzdem, alle Funktionen zu aktivieren, da dies die besten Synergieeffekte bringt, z.B. Policies Mod und Hacienda Winery). Die Grundfunktionen, wie z.B. das separate Bau-Menü, bleiben erhalten.
    - Hinzufügen einer Russischen Lokalisation, bereitgestellt von @DrD_AVEL
* Bugfixes:
    - Einige Anpassungsoptionen, die nicht mehr benötigt werden, wurden entfernt, wie z.B. der Schalter zum Einschalten der Elektrizität in den Hacienda-Brauereien.
</details>

<details>
    <summary>Patch Notes Version 2.0.1</summary>

* Neue Funktion:
    - Hacienda Fertilizer Works elektrifizierbar gemacht mit Toggle in iMYA
* Fehlerbehebungen:
    - Englische Beschreibung für Politik 4 korrigiert
    - angezeigte und aktive Buffs für Hacienda Policy 4 korrigiert (fehlende 2x3 Artista Häuser und generelles Durcheinander mit der Traubenfarm und dem Weingut)
    - Kaugummi und Geigen müssen nach Nähmaschinen im Needs Tab erscheinen
    - Fix Bug mit unsichtbarem Hacienda Decal für Hacienda Hospital
    - Kostümbildner und Hutmacher fehlen in Hacienda Policy 2
</details>

<Details>
    <summary>Patch Notes Version 2.0</summary>

* Neue Features:
    - Grundlegende Überarbeitung der Struktur dieser Mod. Diese Mod besteht jetzt aus einem einzigen Mod-Ordner, der manuell oder über iModYourAnno installiert werden kann. Bitte stellt sicher, dass ihr alle älteren Mod-Ordner dieser Mod entfernt. Dieser Vorgang sollte savegame-kompatibel sein.
    - Modularität: Wenn ihr bestimmte Features dieser Mod entfernen möchtet, könnt ihr die mitgelieferte asset.xml-Datei öffnen und einzelne Module durch Löschen einzelner <include>-Befehle entfernen. Es gibt eine kleine Beschreibung in der asset.xml-Datei, die euch sagt, was das Modul macht.
    - Tweaking: Diese Mod unterstützt nun das Tweaken über den iModYourAnno Mod Manager. Ihr müsst nicht mehr selbst an den Dateien herumschrauben. Öffnet einfach die Registerkarte 'Tweaking' und seht, was geändert werden kann. Ihr könnt viele Zahlenwerte nach euren Wünschen verändern, z.B. den Radius der Hacienda oder die Produktionszeit bestimmter Produktionsgebäude. Ihr könnt auch ganze Funktionen dieser Mod über die Registerkarte 'Tweaking' deaktivieren. Wenn ihr iModYourAnno verwendet, beachtet bitte, dass alle Schalter in der Registerkarte 'Tweaking' eingeschaltet werden müssen, um die beabsichtigte 'Full Experience' zu erhalten!

* Update für GU16:
    - Diese Mod wurde komplett mit GU16 kompatibel gemacht. Artista 2x3 Residences hinzugefügt und Hacienda Quarters für neue Lifestyle-Bedürfnisse und RequiredtobeBuilding Änderung aktualisiert:
        - Basisversion: 2x3 Jornalero Residenzen wurden auf 8 Jornaleros + 16 von Lifestyle Needs aktualisiert (24 insgesamt).
        - Basisversion: 2x3 Obrero-Residenzen werden auf 16 Obreros + 28 aus den Lebensstil-Bedürfnissen aktualisiert (44 insgesamt).
        - Basisversion: 2x3 Artista-Residenzen: 32 Artistas + 36 aus den Lebensstil-Bedürfnissen (insgesamt 68).
        - Erweiterte Gameplay-Änderungen: 4x4 Jornalero-Residenzen werden auf 30 Jornaleros + 35 aus den Lebensstil-Bedürfnissen aktualisiert (65 insgesamt).
        - Erweiterte Gameplay-Änderungen: 4x4 Obrero-Residenzen werden auf 70 Obreros + 65 aus den Lebensstil-Bedürfnissen aktualisiert (135 insgesamt).
        - Erweiterte Gameplay-Änderungen: 4x4 Artista-Residenzen werden auf 140 Artistas + 75 aus den Lebensstil-Bedürfnissen aktualisiert (215 insgesamt).      
        - Erweiterte Gameplay-Änderungen: 2x3 Jornalero-Residenzen werden auf 13 Jornaleros + 17 aus Lebensstil-Bedürfnissen aktualisiert (30 insgesamt).
        - Erweiterte Gameplay-Änderungen: 2x3 Obrero-Residenzen werden auf 26 Obreros + 29 aus Lebensstil-Bedürfnissen aktualisiert (55 insgesamt).
        - Erweiterte Gameplay-Änderungen: 2x3 Artista-Residenzen auf 52 Artistas + 33 aus Lebensstil-Bedürfnissen (85 insgesamt).
    - Hacienda, Tabasco und Atole für Artista-Hacienda-Residenzen hinzugefügt. 
    - Neue öffentliche Gebäude mit Hacienda Decals hinzugefügt.
    - Alle Hacienda-Richtlinien wurden an die neuen Bedürfnisse und Möglichkeiten von GU16 angepasst. Die Richtlinien 1 und 2 wurden aktualisiert, wobei die Richtlinie 5 komplett entfernt und als separates Modul ausgelagert wurde. Sie wurde durch eine neue Richtlinie ersetzt.
</details>

<details>
    <summary>Patch Notes Version 1.5.1</summary>

* Kleinere Fehlerbehebungen:
    - Ein Problem mit den Handelswerten bestimmter Waren in Docklands (z.B. Tabasco) aufgrund fehlender Werte wurde behoben.

* Neue Funktionen:
    - Die Effektzielpools der OW- und NW-Holzköhler wurden angepasst und durch einen gemeinsamen Effektzielpool "Alle Holzköhler" ersetzt.
</details>

<details>
    <summary>Patch Notes Version 1.5.0</summary>

* New features:
    ![Banner](https://user-images.githubusercontent.com/64583643/192605638-41616a81-7f59-4ff6-8bc6-28d2a02306ed.png) 
    - Modul 2 - Sounds of Stradivari hinzugefügt. Dieser Mod ermöglicht die Herstellung von Violinen in der Neuen Welt unter Verwendung der Funktionen des Hacienda Overhauls. Lack kann nun aus Quarz (Sandmine auf Lehmfeldern), Kautschuk und Ethanol hergestellt werden. Kirschholz kann mit Hilfe der Hacienda-Politik 3: Holzfällerausbildung als Nebenprodukt von Holzfällern und Baumschulen gewonnen werden. Stahl kann im Hochofen aus Eisenerz hergestellt werden, das auf Gold-Slots abgebaut wird.

    Vielen Dank an [Jakob](https://github.com/jakobharder/anno-1800-jakobs-mods) für die Bereitstellung der Grundgrafiken der Sandmine und des Stahlofens sowie einiger Codes, um die Kompatibilität zwischen seiner Mod ["New World Construction"](https://github.com/jakobharder/anno-1800-jakobs-mods/tree/main/mods/production-nw-construction) and mine. und meiner Mod herzustellen. Nur eine kleine Vorwarnung: Meine mit Jakobs Mod gemeinsam genutzten Gebäude können sich in Bezug auf Arbeitskräftebedarf, Baukosten und Wartungskosten leicht unterscheiden.
</details>

<details>
    <summary>Patch Notes Version 1.4.0</summary>

* Update für GU15:
    - Aktualisierte Hacienda-Quartiere für neue Lebensstil-Bedürfnisse und RequiredtobeBuilding-Änderung:
        - Basisversion: 2x3 Jornalero-Residenzen wurden auf 8 Jornaleros + 12 aus Lebensstil-Bedürfnissen aktualisiert (20 insgesamt).
        - Basisversion: 2x3 Obrero-Residenzen wurden auf 16 Obreros + 24 aus den Lebensstil-Bedürfnissen aktualisiert (40 insgesamt).
        - Erweiterte Gameplay-Änderungen: 4x4 Jornalero-Residenzen werden auf 30 Jornaleros + 30 aus den Lebensstil-Bedürfnissen aktualisiert (60 insgesamt).
        - Erweiterte Gameplay-Änderungen: 4x4 Obrero-Residenzen werden auf 70 Obreros + 60 aus Lebensstil-Bedürfnissen aktualisiert (130 insgesamt).
        - Erweiterte Gameplay-Änderungen: 2x3 Jornalero-Residenzen werden auf 13 Jornaleros + 12 aus Lebensstil-Bedürfnissen aktualisiert (25 insgesamt).
        - Erweiterte Gameplay-Änderungen: 2x3 Obrero-Residenzen werden auf 26 Obreros + 24 aus Lebensstil-Bedürfnissen aktualisiert (50 insgesamt).

* Minor Bugfixes:
    - Ich habe die Ursache für den Absturz beim Wechseln der Rezepte zwischen den Hacienda-Farmen gefunden: Ich habe vergessen, den entsprechenden Asset-Eintrag für die leere Hacienda-Farm in meiner Politik-Überarbeitung zu ändern, die den Farmen den Traktor-Boost gibt. Obwohl die leere Farm nie etwas produziert, mag das Spiel das Missmatch zwischen der leeren Farm und der jeweiligen Rezept-Farm nicht. Die leere Farm ist jetzt wieder in den Modulen des Hacienda-Menüs enthalten.
    - Einige mit GU15 stillschweigend eingeführte Bugfixes wurden entfernt.

* New features:
    ![Banner](https://user-images.githubusercontent.com/64583643/192149310-8fcbf8b6-b878-48c3-9269-0a2a9c9fdfa7.png)    
    - Die Hacienda-Straßen aus Muggenstürmer's [CityOrnaments Mod](https://www.nexusmods.com/anno1800/mods/93) wurden als optionaler und separater Mod hinzugefügt, um meine Hacienda-Straßen zu ersetzen. Die Straßen verfügen jetzt über Brücken und Bahnübergänge. Danke an Muggen, dass ich seine fantastische Arbeit verwenden darf!
</details>

<details>
    <summary>Patch Notes Version 1.3.3</summary>

* Kleinere Fehlerbehebungen:
    - Ich habe die Ursache für den Absturz beim Wechseln der Rezepte zwischen den Hacienda-Farmen gefunden: Ich habe vergessen, den entsprechenden Asset-Eintrag für die leere Hacienda-Farm in meiner Policy Overhaul zu ändern, die den Traktor-Boost für die Farmen gibt. Obwohl die leere Farm nie etwas produziert, mag das Spiel das Missmatch zwischen der leeren Farm und der jeweiligen Rezept-Farm nicht. Die leere Farm ist jetzt wieder in den Modulen des Hacienda-Menüs enthalten.
    - Aus irgendeinem Grund wurden die Auswirkungen der Brauereien der Hacienda auf die Attraktivität im Stadt-Tab angezeigt, wo standardmäßig nur positive Attraktivitätswerte angezeigt werden. Ich habe es auf Fabrik geändert. (Vielleicht hatten die Entwickler einmal vor, ihnen einen Attraktivitätsschub für die Stadt zu geben, und hatten nur einen Tippfehler mit dem Minus???)
    - Ich habe ein Problem behoben, bei dem die Hacienda-Registerkarte im Baumenü mit der Hacienda-Kirche zu früh im Spiel sichtbar und baubar war, weil ich die Kirche zum AssetPool Kapelle hinzugefügt habe, der standardmäßig mit Jornaleros aufgedeckt/freigeschaltet ist.
    - Wenn ihr meine Überarbeitung der Produktionsketten oder den Shared Goods Mod benutzt, zeigen die Hacienda Weinkellerei und ihr Rezept nun das korrekte Icon für Wein anstelle von Champagner.
    - Das Baumenü des Hacienda-Overhauls wurde aufgeräumt, irgendwie war die Hacienda immer noch in der Registerkarte Obreros, aber innerhalb der Registerkarte Hacienda-Ornamente (die dort eigentlich nicht sein sollte). Es sollte nun klar sein, dass die Hacienda und ihre Ornamente nur im Hacienda-Bau-Menü-Tab zu finden sind, wie vorgesehen.
</details>

<details>
    <summary>Patch Notes Version 1.3.2</summary>

* Der Hacienda-Weinberg wurde zum ItemEffectTargetPool "Alle Alkoholproduktionsketten" hinzugefügt, so dass er durch verschiedene Feste gebufft wird.
</details>

<details>
    <summary>Patch Notes Version 1.3.1</summary>

* Hacienda Weinkeller für die NPCs unbaubar gemacht, damit es keine Probleme mit feststeckender AI gibt.
</details>

<details>
    <summary>Patch Notes Version 1.3</summary>

![banner](https://user-images.githubusercontent.com/64583643/170326244-da7a2b35-e93e-43f5-9f70-928a5a4571c3.png)
* Modul 1: Hacienda Weinkeller hinzugefügt. Verfügbar ab 1 Investoren-Hochhaus Level 3. Benötigt Trauben, Zimt und Kirschholz. Produziert „Champagner“ (noch...).

</details>

<details>
    <summary>Patch Notes Version 1.2</summary>

* Anpassungen für die Kompatibilität mit Burrito Boom
* Hacienda Rathaus zum Modul Extended Hacienda hinzugefügt
* Vanilla Handelskammer und Rathaus mit Hacienda Decal hinzugefügt (Variationen)
* Produktionszeit von Dünger bei 1:30 belassen nach GU14.1, internes Lager verkleinert auf 2 Tonnen, um die Reichweite der Karren einzugrenzen
      
* Bugfixes:
    - Hacienda Farmen brauchen in der Basic Gameplay Changes Variante keine Fruchtbarkeiten mehr auf der Insel
    - Kaugummi-Gebäude (Zimt-Baumschule und Chemiefabrik) unlocken nun auch schon bei 2000 Obreros, nicht nur die Production Chain. (vorher musste man erst die Hochhäuser bauen, um diese Gebäude freizuspielen.
    - Visual bugs bei der Hacienda Handelskammer behoben: Foreman buggt nicht mehr durch den Boden und eine Flagge gedreht
    - Kaugummi wird nun erst ab 2000 Obreros nachgefragt. Vorher schon 1500, hier war das Problem, dass die Produkionskette erst bei 1500 aufgedeckt und erst bei 2000 freigeschaltet wurde.
    - Alle Änderungen am Internen Lager wieder auf vanilla Wert zurückgesetzt, da die Berechnung der Transporter-Reichweite proportional hiervon abhängt. Es kam so dazu, dass z.B. die Hacienda Gewürzfarm in der Extended Version eine Reichweite von 125 Tiles auf Steinstraßen hatte, was im Endeffekt einmal die ganze Insel abdeckte und so die Chillisaucen-Brauerein fast immer direkt angefahren wurden, auch wenn diese sich am anderen Ende der Insel befanden. Nun haben alle Farmen eine Reichweite auf Steinstraßen von 25 Tiles, wie in Vanilla
    - Positionen der Hacienda Banane-, Baumwoll- und Tabakfarmen im Assi-Boost Menü angepasst
    - InfoDescription für diverse ConstructionCategories eingefügt und für Hacienda Warehouse gefixt
    - Standard-Decal Skin bei den öffentlichen Gebäuden auf vanilla festgelegt, daher immer Strg+V (oder euren Hotkey dafür) drücken, um den Decal auf Hacienda umzuschalten
    - Polizei und Kirche sowie Handelskammer führen jetzt zu entsprechenden Reaktionen bei Mercier, wenn sie gebaut sind
    - alle neuen relevanten Gebäude für AI gelockt, um zu verhindern, dass diese festhängen bleiben
    - Hacienda in den Influence Investment „Optimisation“ AssetPool aufgenommen
</details>

<details>
    <summary>Patch Notes Version 1.1.2</summary>

* Hotfix für alle Lokalisierungen außer Englisch. Entschuldigung für die Unannehmlichkeiten, ich habe versehentlich ältere Textdateien für die anderen Sprachen hochgeladen.
</details>

<details>
    <summary>Patch Notes Version 1.1.1</summary>

* Kleine Bugfixes:
    - Obrero-Residenzen können nicht mehr kopiert werden. Wenn sie mit dem Kopierwerkzeug ausgewählt werden, werden die entsprechenden Jornalero-Residenzen verwendet.
    - Ein Tippfehler in der deutschen Lokalisation wurde behoben: Banenen → Bananen
</details>

<details>
    <summary>Patch Notes Version 1.1</summary>

Auf vielfachen Wunsch habe ich beschlossen, die Mod in Module aufzuteilen. ALLE Module benötigen das Basis Modul in eurem Mod-Ordner. Alle anderen Module sind optional. Es folgt ein kurzer Überblick über die Eigenschaften der einzelnen Module:

* Base:
    ![banner](https://user-images.githubusercontent.com/64583643/170326044-14f16f0a-9854-40e2-af8c-aba3b4ea021d.png)
  - Neues separates Bau-Menü für alle Hacienda-Gebäude
  - Neue Icons für alle Hacienda-Module zur leichteren Identifizierung und Zugänglichkeit
  - Hacienda-Straßen jetzt unbegrenzt und funktionieren wie normale Straßen
  - Hacienda-Farmen mit Kochbananen, Baumwolle, Tabak (keine Fruchtbarkeit erforderlich) und geteiltem Rezeptbuch für NW- und OW-Farmen
  - Obrero-Residenzen müssen aus Jornalero-Residenzen aufgewertet werden
  - Öffentliche Gebäude mit Hacienda Grounddecal Variation
  - Bugfixes

* BasicGameplay changes:
    ![banner](https://user-images.githubusercontent.com/64583643/170326070-ad4251a2-c6fc-45eb-a529-dd5c7961f0f0.png)
  - Radius der Hacienda jetzt bis zu 80
  - Düngemittelfabrik wurde verbessert und muss nicht mehr innerhalb des Hacienda-Radius gebaut werden

* ExtendedHacienda by Lordys:
    ![banner](https://user-images.githubusercontent.com/64583643/170326118-9b8d5fd9-ba7a-412e-b45b-fe8ec3c32edd.png)
Dank Lordys haben wir nun eine Vielzahl neuer Hacienda-spezifischer Gebäude:
  - Kleine Marktstände → Befriedigen das Bedürfnis der Hacienda nach Residenzen in ihrem Bereich
  - Kleine Jornalero und Obrero Residenzen (2x3) → 8 [12] und 13 [20] Einwohner
  - Hacienda-Kapelle → Befriedigt den Bedarf nach Kapelle
  - Hacienda-Feuerwache, Hacienda-Polizeistation → Jeweils zwei Einheiten und etwas höhere Abdeckung
  - Hacienda Handelskammer → Radius 20! Kostet allerdings 50 Obrero-Arbeitskraft
  - Hacienda Grenzmauer halbautomatisch und manuell → siehe unten!

Ein kurzes Wort zum Thema der halbautomatischen Außenmauer. Da der Anno-Code nur erlaubt,
dass Ornamente in der Mitte des Decals liegen, um automatisch an der richtigen Stelle einzurasten,
musste ich einen Trick anwenden. Man muss zuerst einen zwei Kacheln breiten Korridor der Wand
bauen. Danach kann man den inneren Kreis abreisen und der äußere bleibt an der richtigen Stelle!

* ExtendedGameplay changes:
    ![banner](https://user-images.githubusercontent.com/64583643/170326142-cfb81268-9a48-4a72-80e2-e8713faf38c6.png)
  - Hacienda-Lagerhaus jetzt bis zu 100 Tonnen Lager und zwei Transporter
  - Hacienda Residenzen wurden komplett überarbeitet
  - Fruchtbarkeiten werden benötigt
  - Hacienda-Brauereien: überprüft und angepasst

* PolicyOverhaul:
    ![banner](https://user-images.githubusercontent.com/64583643/170326173-21795d8f-869d-4086-adf1-56fa7d664698.png)
  - Hacienda Policies komplett ersetzt und neu balanciert (siehe unten)
</details>

ICH EMPFEHLE DRINGEND, DAS SPIEL MIT EINEM VOR-DLC10 SPIELSTAND ZU LADEN, UM KOMPATIBILITÄT SICHERZUSTELLEN! Entfernt alle älteren Versionen dieses Mods. Wenn du Module mitten im Spiel entfernst, kann es zu komischen Ergebnissen führen. Das Hinzufügen von Modulen, nachdem du mit weniger Modulen begonnen hast, ist SICHER!

## Beschreibung dieser Mod mit einer Übersicht der wichtigsten Funktionen
**Bitte denkt daran, immer das Changelog zu überprüfen, um die neuen oder geänderten Features zu sehen.**

Liebes Ubi Team, liebe Annoholic Community.

Dies ist meine Version von DLC10 Seeds of Change, so wie ich es mir vom ersten Moment an vorgestellt habe, als ich Gameplay sah. Leider hat die erste Veröffentlichung mich und viele andere Mitglieder der Community hinter ihren Erwartungen zurückgelassen. Ich habe die am meisten gewünschten Änderungen recherchiert und diese Mods in das Spiel eingebaut. Dies ist die Liste der Features:

### Neues separates Baumenü für alle Hacienda-Gebäude
Ich habe einen separaten Eintrag im Baumenü erstellt, der nur für Hacienda-Gebäude gedacht ist. Alles kann von dort aus gebaut werden.

- Hacienda-Straßenkacheln sind nun direkt zugänglich
- Neue Gebäudekategorien für OW- und NW-Farmen
- Neue Gebäudekategorie für die Hacienda-Brauereien

### Neue Icons für alle Hacienda-Module zur leichteren Identifizierung und Zugänglichkeit
Den Icons der Hacienda-Module fehlte es an Unterscheidungsmerkmalen und Kontrast, so dass sie nur schwer zu unterscheiden waren. Deshalb hat jedes Modul ein neues, deutlich erkennbares Icon bekommen.

### Hacienda-Straßen sind jetzt unbegrenzt und funktionieren wie normale Straßen
Die Hacienda Straßen waren aus einem unbekannten Grund auf 999 kombinierte Kacheln begrenzt. Das ist nun vorbei! Jedes Modul ist jetzt separat und funktioniert wie eine normale Straße. Sie können jetzt auch über Flüsse und Eisenbahnschienen gebaut werden. (Vielen Dank an Muggenstuermer's ["City Ornaments"](https://www.nexusmods.com/anno1800/mods/93?tab=description)).

### Radius der Hacienda jetzt bis zu 80
Ich habe die maximale Reichweite auf 80 erhöht, beginnend mit 15. Um einen zusätzlichen Anreiz zu schaffen, die Bevölkerung innerhalb des Radius der Hacienda aufzubauen, sind die letzten beiden Stufen für das Erreichen von 7500 und 10000 Einwohnern reserviert (+5 auf den Radius jedes Mal). Um dem neuen Radius gerecht zu werden, wurde auch die Entfernung, über die die Hacienda ihren öffentlichen Dienst an die Häuser anbietet, erhöht. Wenn Sie gepflasterte Straßen (oder die Hacienda Plaza) verwenden, sollten Sie leicht in der Lage sein, Wohnhäuser an den äußeren Teilen des Radius zu platzieren. Diese Funktion kann über iModYourAnno vollständig angepasst werden.

### Hacienda Lagerhaus jetzt bis zu 100 Tonnen Lager und ein Transporter
Das vanilla Hacienda-Lagerhaus hat keinen wirklichen Vorteil gegenüber den normalen Depots im Hafengebiet, da sie sogar kostbaren Landplatz verbrauchen. Also habe ich ihnen eine neue Aufgabe gegeben, indem ich ihnen eine Transporterrampe hinzugefügt und den Lagerplatz auf 100 Tonnen erhöht habe. Das hat allerdings seinen Preis. Sie können nur innerhalb des Radius der Hacienda gebaut werden und kosten 50 Obrero Workforce pro Stück! Sie sollten nur als Unterstützung für normale Lagerhäuser dienen. Diese Funktion kann durch iModYourAnno vollständig angepasst werden.

### Die Hacienda-Residenzen wurden komplett überarbeitet.
- Jornalero-Residenzen nehmen jetzt bis zu 85 Einwohner mit Lebensstilbedürfnissen auf. Ihre Bedürfnisse wurden unverändert belassen, aber es wurde ein zusätzlicher Anreiz für die beiden neuen Waren Schnaps und Heiße Soße geschaffen, indem die Anzahl der gewonnenen Einwohner erhöht wurde.
- Die nächste große Änderung ist, dass Obrero-Residenzen nicht mehr separat gebaut werden können. Ihr müsst eure Jornalero-Residenzen aufwerten. 
- Die Obrero-Residenzen erhalten nun standardmäßig 3 Attraktivitätspunkte, damit ihr die erforderliche Anzahl an Attraktivitätspunkten erreicht, um die Hacienda-Politik freizuschalten. Ihre Einwohnerzahl wurde auf 165 angehoben. Ein zusätzlicher Anreiz wurde für die neuen Produkte Hot Sauce und Atole sowie für die neu eingeführten Bedürfnisse geschaffen: Kaugummi und Geigen, die mit 1500 bzw. 2000 Obreros freigeschaltet werden, um den Anreiz zum Bau dieser Produktionslinien im späteren Spiel zu erhöhen. 
- Um den geänderten Bedürfnissen Rechnung zu tragen, geben bevölkerungssteigernde Gegenstände wie Saint D'Artois und Papstpapier nun zusätzliche Einwohner für Scharfe Soße sowie Kaugummi und Geigen, um nicht nur die NW-Nutzung dieser Waren zu fördern, sondern auch die Lieferung von Geigen und Kaugummi an Ingenieur- und Investoren-Wolkenkratzer, da diese Produktionen für die Menge an Einwohnern, die sie liefern, nicht wirklich platzsparend sind.

### Die Düngemittelfabrik wurde gebufft und muss nicht mehr innerhalb des Hacienda-Radius gebaut werden.
Die Produktionszeit der Düngemittelfabrik wurde auf 90 Sekunden angehoben. Gleichzeitig wurde der Buff für die Tierfarmen auf 1/10 statt 1/3 reduziert. Jetzt müssen Sie 3 Tierfarmen mit 110% bauen, um eine nicht geboostete Düngemittelfabrik zu versorgen, statt wie bisher im Verhältnis 1 zu 3. Die Düngemittelfabrik muss auch nicht mehr innerhalb des Hacienda-Radius gebaut werden, denn ich denke, die meisten von uns wollen nicht jeden Tag mit dem Geruch von Scheiße aufwachen, oder?


### Hacienda Farms: 4 neue Pflanzenarten und Fruchtbarkeiten mater wieder
Warum genau haben die Entwickler die drei Feldfrüchte Bananen, Baumwolle und Tabak weggelassen? Nun, ich vermute, dass das Rezeptbuch nicht mehr Platz hat, als 8 Rezepte in der aktuellen Größe für jeden Gegenstand auf der Liste zu haben. Also haben sie ihr Grafikteam angewiesen, alle Getreidefarmen für die Fruchtbarkeiten der Neuen Welt zu entwerfen und dann die, die niemand mag - wegen des Balancings und des Item-Spiels - über Bord geworfen. Aber die Grafiken haben den Sprung in die endgültigen Spieldateien überlebt! Ich habe eine Stunde damit verbracht, die Tabakplantage zu erstellen, bis ich beim Export bemerkt habe, dass es bereits eine gibt! Ich meine wtf. Ich habe den vollen Preis bezahlt, aber aufgrund eines wirklich einfachen UI-Design-Problems wurde mir so viel Inhalt gestohlen. Vor allem, da die Tabakplantage eine der am meisten ungenutzten Farmen im ganzen Spiel war, hätte eine Hacienda-Version in Vanille eine wirklich gute Gelegenheit sein können, sie tatsächlich anzubauen, anstatt sie als Nebenprodukt von Bananen zu bekommen.

- Also habe ich dieses Problem selbst behoben, indem ich die Hacienda-Farmen in zwei Gebäude aufgeteilt habe, die New World Hacienda Crop Farms mit den lange verschollenen Bananen-, Baumwoll- und Tabakplantagen und die OW Hacienda Crop Farms mit Gewürzen und *Trommelwirbel bitte* einem Weinberg! Dazu später mehr. Mit Update 2.2.0 haben wir jetzt auch die fehlenden Farmen für die Fruchtbarkeiten aus DLC12: Kräuter und Orchideen!

- Die Rezeptbücher sind jetzt auch geteilt, also achtet darauf. Alle Farmen wurden auf ihre Produktionszeit überprüft, damit sie zur Vanille passen. Da die Bedeutung der Scharfen Soße drastisch gestiegen ist, wurde der Produktionszyklus der Gewürzfarm auf 120 Sekunden gesetzt, so dass die Versorgung eine etwas größere Herausforderung wird. Eine weitere große Änderung ist, dass alle New World Crop Farms und der Vineyard nun die entsprechende Fruchtbarkeit auf der Insel benötigen. Ich verstehe nicht, warum ein so altes Feature der Anno-Reihe jetzt ganz weggelassen werden soll.

- Bauernhöfe und Rezepte sind nun von vornherein gesperrt. Jetzt mehr Kakao- oder Kaffeeplantagen, wenn eure Bewohner nicht das entsprechende Fertigprodukt benötigen. Dies sollte es neuen Spielern, die mit einem neuen Savegame beginnen, erleichtern, ein wenig sichtbaren Fortschritt zu haben.

- Hacienda-Brauereien: überprüft und angepasst. Ich habe die negativen Auswirkungen auf die Attraktivität von Hacienda-Brauereien auf +5 angepasst, um die Freischaltung aller Hacienda-Politiken zu erleichtern. Die Baukosten wurden auf 10 Holz und 15 Ziegel erhöht. Die Produktionszeit der Hot Sauce-Brauerei wurde auf 60 Sekunden gesenkt, um das Gleichgewicht zwischen dem neuen Bedürfnis und der Menge an Pop, die man von ihr erhält, zu wahren. Brauereien und ihre Rezepte sind nun zunächst gesperrt. Jetzt gibt es mehr Atole oder Kaffee, wenn eure Bewohner nicht das entsprechende Produkt benötigen. Dies sollte es neuen Spielern, die mit einem neuen Savegame beginnen, erleichtern, ein wenig sichtbaren Fortschritt zu machen.

### Unterstützung der wichtigsten öffentlichen Gebäude für die Verwendung des Hacienda Plaza Bodenaufklebers
Dies ist für die Schönheits-Baumeister in der Community. Ich habe alle wichtigen öffentlichen Gebäude genommen und ihnen eine neue Variante mit dem Hacienda Plaza Bodenaufkleber verpasst, so dass ihr prächtige Hacienda Compounds mit passenden öffentlichen Gebäuden bauen könnt.

Enthalten sind: Feuerwache, Polizeistation, Krankenhaus, Kapelle, Box-Arena und alle Lagerhäuser sowie die öffentlichen Gebäude des DLC12.

### Die Hazienda-Politik wurde komplett ersetzt und neu ausbalanciert.
Um ehrlich zu sein, die Vanilla Policies sind wie das Spielen mit den kleinen Schaufeln im Kindergarten, während die größeren Kinder die schönen Traktoren und Erdbewegungsmaschinen bekommen haben. Im Vergleich zu den Buffs für die Paläste sehen sie fast nutzlos aus. Für den vierten muss man fast den gleichen Betrag in die Attraktivitätssteigerung investieren, um die Kosten zu decken. Das ist kein gutes Spieldesign. Die Buffs aus dem Szenario Hacienda sind viel mächtiger und hätten auch gut gepasst.

Aber da ich kreativer bin als das, habe ich 5 völlig neue und potenziell spielverändernde Buffs für euch entwickelt, mit denen ihr spielen könnt. Jetzt werdet ihr bestimmt jeden einzelnen davon in Betracht ziehen.

- Dekret 1: Saubere Umweltverordnung (erforderliche Attraktivität: 450)
    * Wirkt sich auf alle Schwerindustrien, alle Minen, alle Steinbrüche, alle NW-Chemiefabriken und alle Brauereien aus:
        * Produktivität +20%
        * Brandwahrscheinlichkeit -50%
        * Explosionsgefahr -100%
        * Negative Beeinträchtigung der Attraktivität -80%
        * Benötigte Arbeitskräfte +25%
        * Unterhaltskosten +75%

- Erlass 2: Lokale Fabrikverkaufsstellenverordnung (erforderliche Attraktivität: 700)
    * Wirkt sich auf alle Residenzen der Neuen Welt aus:
        - Reduzierter Verbrauch von:
            - Ponchos -25%
            - Bombinen -15%
            - Kaffee -10%
            - Zigarren -10%
            - Ventilatoren -10%
            - Scooter -10%
        - Zusätzliches Glück aus Markt/Hacienda +5
        - Einkommen -10%

    * Wirkt sich auf alle Bekleidungsfabriken, alle Produzenten von Zwischenprodukten, Kaffeeröster, Zigarrenfabriken, Fächerfabriken und Rollerfabriken aus:
        * Zusätzliche Waren in jedem dritten Zyklus (1/3)
        * Attraktivität +5%
        * Benötigte Arbeitskräfte +15%
        * Unterhaltskosten -50%

- Dekret 3: Holzfäller-Ausbildungsdekret (erforderliche Attraktivität: 1000)
    * Wirkt sich auf alle Holzfäller und alle NW-Obstgärten aus.
        * Produktivität +15%
        * Attraktivität +10
        * Benötigte Arbeitskräfte -50%
        * Walddichte -25%
        * Extra Waren: Wanza-Holz 1/7 und Kirschenholz 1/10

- Dekret 4: Gesetz zur Förderung des Weinbaus (erforderliche Attraktivität: 1750)
    * Wirkt sich auf die Hacienda-Weinberge aus
        * Zusätzliche Trauben in jedem zweiten Zyklus (+50%)
        * Fruchtbarkeit der Trauben vorausgesetzt
        * +25 Attraktivität

    * Auswirkungen Hacienda Weingut
        * Zusätzlicher Champagner in jedem zweiten Zyklus (+50%)
        * +25 Anziehungskraft

    * Wirkt auf alle Artista-Residenzen:
        * +58 zusätzliches Geld, +5 Glück und +5 Einwohner aus dem Lebensstilbedarf Champagner sowie eine -25%ige Verringerung des genannten Bedarfs.

- Dekret 5: Gesetz zur Erhaltung der Kultur (erforderliche Attraktivität: 2200)
    * Betrifft alle Obrero- und alle Artista-Residenzen
        * Einkommen pro Haus -25%
        * Bonus Glück +5 und Bonus Einwohner +5 durch Sambaschule und Laternen
        * Reduzierter Verbrauch von Glühbirnen (-25%), Ventilatoren (-50%) und Motorrollern (-75%)
        * Erhöhter Verbrauch von Schreibmaschinen (+25%), Fußbällen (+50%) und Nähmaschinen (+75%)
        * Wenn das Bedürfnis "Box-Arena" erfüllt ist, erhalten die Residenzen das Bedürfnis "Kino" erfüllt.
        * Wenn der Bedarf an Laternen erfüllt ist, erhalten die Residenzen den Bedarf an Elektrizität erfüllt.

### Erweiterte Hacienda von Lordys und Taludas
In Zusammenarbeit mit Lordys habe ich eine Erweiterung des Hacienda-DLCs mit neuen öffentlichen Gebäuden, neuen 2x3 Hacienda-Residenzen und einer äußeren Hacienda-Wandverzierung entwickelt, um euer Spielerlebnis weiter zu individualisieren.
* Kleine Marktstände → Befriedigen den Bedarf der Hacienda an Residenzen in ihrem Bereich.
* Kleine Jornalero, Obrero Residenzen und Artista Residenzen (2x3) → 24/\[30\], 44/\[55\] und 68/\[85\] Pop
* Hacienda-Kapelle → Befriedigt den Bedarf an Kapellen
* Hacienda-Feuerwache, Hacienda-Polizeistation (beide auch in fortgeschrittenen Versionen) → je zwei Auflöser und etwas höhere Abdeckung
* Hacienda Trade Union → Radius 20! Kostet allerdings 50 Obrero Arbeitskräfte
* Hacienda Rathaus
* Hacienda Grenzmauer halbautomatisch und manuell → siehe unten!
* Ein kurzes Wort zum Thema der halbautomatischen Außenmauer. Da der Anno-Code nur zulässt, dass Ornamente in der Mitte des Abziehbildes liegen müssen, um automatisch an der richtigen Stelle einzurasten, musste ich einen Trick anwenden. Man muss zuerst einen zwei Kacheln breiten Korridor der Wand bauen. Danach kann man den inneren Kreis getrost löschen und der äußere bleibt an der richtigen Stelle!

### Diese Mod Tweaks durch iModYourAnno

Wenn du den [iModYourAnno Anno Mod Manager](https://github.com/anno-mods/iModYourAnno) verwendest, findest du darin einen Reiter zum Tweaken. Dort gibt es verschiedene Optionen, um einige Gameplay-Elemente dieser Mod zu verändern. Zum Beispiel kannst du einstellen, ob die Hacienda-Farmen eine Fruchtbarkeit benötigen. Oder welches Rezept die Weinkellerei verwendet. Was die Richtlinien angeht, kannst du dich entscheiden, ob du die Vanilla-Richtlinien oder die von mir modifizierten Richtlinien verwenden möchtest, und du kannst den erforderlichen Attraktivitätsgrad festlegen, um diese freizuschalten. Wenn Sie die volle Erfahrung wollen, schlage ich vor, dass Sie jede Option auf 'an' schalten. Die Einstellung der Werte liegt ganz bei Ihnen. Sie können gerne mit Ihren eigenen Zahlen experimentieren. Denkt immer daran, eure Änderungen zu speichern und den Cache-Ordner in eurem Mods-Ordner zu löschen.

### Fehlerbehebungen
- Das Hauptgebäude der Hazienda wurde aus dem ItemEffectTargetPool "All Hacienda Buildings" entfernt, so dass es nicht mehr durch Items, die "All Production Buildings" beeinflussen, verstärkt werden kann.
- Das Hacienda-Lagerhaus wurde aus dem ItemEffectTargetPool "Alle Hacienda-Gebäude" entfernt, so dass es nicht mehr durch Gegenstände verstärkt werden kann, die "Alle Produktionsgebäude" betreffen.
- Ein LOD-Problem mit zwei von drei Obrero-Hacienda-Residenzen wurde behoben: Auf einer Gebäudeseite erschienen plötzlich Fenster, wo vorher keine sichtbar waren (LOD-Level 2 und höher)

### Danksagung
Nun bleibt mir nur noch, mich bei Ubisoft Mainz für ein großartiges Spiel zu bedanken, das ich in den letzten 3 Jahren lieben gelernt habe, das mich in die Programmierung und in die Selbstausbildung in Sachen 3D-Modellierung gebracht hat, sowie bei einigen großartigen Leuten in der Anno Mod Corner International Discord, ohne die diese Mod nicht möglich gewesen wäre.

Besonderen Dank an:
* Taubenangriff: Dafür, dass er ein wandelndes Lexikon für Anno Game Code Wissen und Feedback ist und den IModYourAnno Mod Manager entwickelt hat
* Jakob: Für die Hilfe bei meinen allerersten Modding-Versuchen und die Entwicklung des VSCode Plugins Anno Modding Tools sowie eines Texturkonverters und die Entwicklung des IModYourAnno Mod Managers
* Lordys: Ohne ihn hätte ich die Funktion der 3D-Spiel-Dateien nie verstanden und sein großartiges [Blender cfg Import/Export Addon](https://github.com/xormenter/Blender-Anno-.cfg-Import-Addon) hat alle Gebäude für das Hacienda Extended Modul beigesteuert! DANKESCHÖN :)
* JJE1000, Hackner und Pine: Für Feedback und konstruktive Gespräche über Features
* Meow: für den fantastischen Mod Loader, ohne den nichts von dem hier möglich wäre
* lukts30: rdm4 Konverter
* VladiwSokow: für die Idee mit den verstärkten Transportern in der Arktis und wie man das macht

Wenn ihr bis zu diesem Punkt gelesen habt: Was kommt als Nächstes, fragt ihr... Ich plane einen modularen Aufbau auf diese Mod aufzusetzen. Vorerst werden aber nur die Arbeitstitel verraten:
* Modul 1: Der Burrito-Boom -WIP-
* Modul 2: Der Formidable Faulproof Fertiliser -WIP-
* Modul 3: Willis Weinwelt-Tour (Erledigt! -> Hacienda Weingut)
* Modul 4: Die Mutile Mine Makeover (Erledigt! -> Kleine Mods Sammlung 'Mine Slot Unification')
* Modul 5: Süß, salzig, sauer oder würzig? -TBD-
* Modul 6: Die Klänge der Stradivari (Erledigt!)
* Modul 7: Das filmische Jahrhundert bricht an -TBD-

Das war's schon! Ich wünsche euch viel Spaß und viel Erfolg beim Städtebau!
