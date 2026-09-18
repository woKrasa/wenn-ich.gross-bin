# Wenn ich groß bin … / Das komische Dingsda

Eine statische, barrierearme Website über echte Berufs- und Lebenswege für Grundschulkinder.

## Technik

Die Website besteht nur aus HTML, CSS und Bildern. Es gibt keinen Build-Schritt, keine Cookies, kein Tracking und keine externen Abhängigkeiten. Zum lokalen Ansehen genügt es, `index.html` im Browser zu öffnen.

## Schnellstart ohne technische Vorkenntnisse

1. Den Ordner öffnen und `index.html` doppelklicken. Die Startseite öffnet sich im Browser.
2. Für eine Textänderung die passende `.html`-Datei in einem Texteditor öffnen.
3. Nur den Text zwischen `>` und `<` ändern. Beispiel: In `<h1>Für Kinder</h1>` darf „Für Kinder“ geändert werden, die Zeichen `<h1>` und `</h1>` bleiben stehen.
4. Datei speichern und die Browserseite neu laden.
5. Vor dem Weitergeben die Schritte unter „Vor jeder neuen Version“ ausführen.

## Welche Datei gehört zu welcher Seite?

- `index.html` – Startseite
- `interviews.html` – Übersicht aller Interviews
- `interview-erzieherin.html` – ruhige Einstiegs- und Auswahlseite des ersten Interviews
- `interview-erzieherin-grundschule.html` – unmittelbar lesbare Grundschulfassung
- `interview-template.html` – Kopiervorlage für neue Interviews
- `komisches-ding.html` – Erklärung des Aktionsformats
- `fuer-kinder.html`, `fuer-eltern.html`, `fuer-einladende.html` – Zielgruppen-Seiten
- `ueber-das-projekt.html`, `kontakt.html`, `impressum.html`, `datenschutz.html` – Projekt- und Pflichtinformationen
- `bildnachweise-rechte.html` – Herkunft und Nutzung der Texte, Fotos und Illustrationen
- `styles.css` – Farben, Abstände, Schriftgrößen und Mobilansicht
- `assets/` – Bilder
- `design/` – freigegebene Figuren- und Gestaltungsstudien; diese Dateien dienen als Vorlage und werden nicht direkt als Webseite angezeigt
- `interviews-redaktion/` – Übergabedokumente und Arbeitsfassungen der Interviews; diese Inhalte gehören zur Redaktion und sind keine eigene Webseite

## Inhalte pflegen

- Vor größeren Änderungen und vor jeder Veröffentlichung `PROJEKT-CHECKLISTE.md` prüfen.
- Neue Interviews erhalten eine eigene HTML-Datei nach dem Muster von `interview-template.html`.
- Neue Interviewseiten werden in `interviews.html` verlinkt.
- Platzhalter in `kontakt.html`, `impressum.html` und `datenschutz.html` müssen vor einer Veröffentlichung durch echte Kontaktdaten ersetzt werden.
- Die Bildnachweise werden bei jedem neuen Foto und jeder neuen Illustration aktualisiert. Ungeklärte Urheberschaft, Nutzungserlaubnis oder Einwilligung ist eine Veröffentlichungssperre.
- Das Übergabedokument zu jedem Interview zusätzlich unter `interviews-redaktion/` im Git-Repository ablegen. So bleiben Quelle, offene Fragen und spätere Änderungen nachvollziehbar.

### Navigation verstehen

Die Startseite ist bereits für Kinder gedacht. Deshalb gibt es oben keinen zusätzlichen Menüpunkt „Für Kinder“ mehr.

- **Start** führt zur kindgerechten Auswahlseite.
- **Berufe** führt zu den Berufsgeschichten. Erst dort wird die Textmenge gewählt.
- **Dingsda** erklärt das Aktionsformat und kann später um Berichte ergänzt werden.
- **Projekt & Erwachsene** bündelt Informationen für Eltern und Schulen, die Projektbeschreibung und den Kontakt.

Auf kleinen Bildschirmen bleiben die drei Kinderziele groß sichtbar. Projektinformationen stehen bewusst getrennt darüber.

Die Symbole sind Teil der Orientierung: Der Koffer bedeutet überall „Berufe“, die Lupe überall „Dingsda“. Deshalb werden in Navigation und Inhaltsüberschriften dieselben Dateien verwendet. Links neben der Navigation steht vorerst kein Projektname; ein späteres Logo wird erst nach eigener Freigabe eingesetzt.

Auf Kinderseiten bleibt auch die Sprache entlang des Weges stabil: **Berufe → Berufe entdecken → Berufsgeschichte lesen**. „Interview“ ist ein Begriff für Erwachseneninformationen und die interne Redaktion, nicht für die Kinder-Navigation.

### Ein neues Interview anlegen

1. `interview-template.html` kopieren und verständlich benennen, zum Beispiel `interview-tischlerin.html`.
2. Titel, Beschreibung und Überschrift ersetzen.
3. Zuerst die vollständige, freigegebene Interviewfassung eintragen. Sie ist die Quelle für alle kürzeren Texte.
4. Daraus eine mittlere Fassung für etwa 10–13-Jährige und zuletzt eine kurze, gut vorlesbare Fassung für Grundschulkinder erstellen.
5. Prüfen, dass Fakten, zeitliche Reihenfolge, Zitate und wichtige Aussagen in allen Fassungen gleich bleiben. Kürzen und verständlicher erklären ist erlaubt; neue Aussagen hinzuerfinden nicht.
6. Bilder in `assets/` ablegen und die beiden Bildplätze in der neuen Datei ersetzen.
7. In `interviews.html` eine neue Karte ergänzen und auf die neue Datei verlinken.
8. Namen, Bilder und persönliche Aussagen nur mit geklärter Einwilligung veröffentlichen.

### Die drei Lesefassungen pflegen

Von der Interviewübersicht führt der Standardweg direkt zur kurzen Grundschulfassung. Dort beginnt das Interview ohne einen weiteren Auswahlklick. Eine kleine Anzeige am Anfang zeigt zusätzlich, dass später längere Fassungen verfügbar sein werden. Die Lesefassungen stehen auf getrennten Seiten, damit Grundschulkinder nicht von längeren Texten abgelenkt werden.

- **Kurz:** Grundschule; kurze Fragen und Antworten, konkrete Wörter, gut zum Vorlesen.
- **Mehr:** etwa 10–13 Jahre; mehr Stationen, Zusammenhänge und Schwierigkeiten.
- **Vollständig:** ältere Jugendliche und Erwachsene; das ganze redigierte Interview und verbindliche Quelle der beiden kürzeren Fassungen.

Nach jeder inhaltlichen Änderung zuerst die vollständige Fassung aktualisieren und danach beide kürzeren Fassungen erneut vergleichen.

In der Grundschul-Fassung sind alle Fragen und Antworten sofort sichtbar. Große Fragen, kurze Absätze, eine schmale Textspalte und viel Abstand unterstützen den Lesefluss.

### Ein Bild austauschen

Das neue Bild in `assets/` speichern. Ein freigegebenes Original nicht überschreiben: eine neue, verständlich versionierte Datei anlegen, zum Beispiel `motiv-v2.png`. Im passenden `<img>`-Element nur den Wert hinter `src=` ändern. Der Text hinter `alt=` beschreibt das Bild für Menschen, die es nicht sehen können, und muss ebenfalls passen. Danach Desktop und Mobilansicht prüfen: Das ganze Motiv und etwaiger Bildtext müssen sichtbar bleiben.

Die kleinen Navigationsbilder liegen ebenfalls unter `assets/` und beginnen mit `icon-`. Symbol und sichtbarer Linktext gehören zusammen. Beim Austausch müssen Bedeutung, Größe und Abstand auf Desktop und Handy geprüft werden.

### Logo und Waschbär pflegen

Das freigegebene Website-Logo liegt unter `assets/logo-wenn-ich-gross-bin-waschbaer-v1.png`. Die zugehörige Körperstudie liegt unter `design/waschbaer-koerperstudie-v1.png`; die fünf einzeln nutzbaren Haltungen liegen zusätzlich unter `design/waschbaer-posen-v1/`. Neue Varianten überschreiben diese Dateien nicht, sondern erhalten eine neue Versionsnummer. Anatomie, Augen, Farben und Größenverhältnis des Waschbären sind zusätzlich in `PROJEKT-CHECKLISTE.md` beschrieben.

Die beiden Leitbilder enthalten inzwischen freigegebene Waschbärvarianten. Hinweise zur Figurenentwicklung und zu späteren Varianten stehen in `WASCHBAER-BILDENTWICKLUNG-UEBERGABE.md`.

Für die Kinderhandlung „Berufsgeschichte lesen“ wird ausschließlich `assets/waschbaer-interview-lesen-v1.png` verwendet. Die identische freigegebene Bildfassung liegt zur gestalterischen Dokumentation zusätzlich unter `design/waschbaer-posen-v1/interview-lesen-v1.png`. Sie zeigt den kleinen Waschbären mit gelber runder Lesebrille hinter einem großen Arbeitskoffer; beide Pfoten liegen auf der Kofferkante und der Koffer hat genau zwei Schnallen.

Der Zeigewaschbär für aufklappbare Zusatzinformationen in Kinderinterviews liegt unter `assets/waschbaer-zeigt-v1.png`; die identische Dokumentationsfassung liegt unter `design/waschbaer-posen-v1/zeigt-v1.png`. Er sitzt klein auf der oberen Kante der Zusatzbox und zeigt auf deren Inhalt. Auf der Elternseite wird diese Figur nicht eingesetzt.

### Bildrechte dokumentieren

- Eigene Skizzen, freigegebene Endfassungen und wichtige Entwicklungsschritte nachvollziehbar aufbewahren.
- KI-Unterstützung transparent benennen, ohne einen ungeklärten exklusiven Urheberrechtsschutz zu behaupten.
- Referenzfotos dienen nur der internen Beobachtung und werden weder in die Website noch in das öffentliche Repository übernommen.
- Für Personenfotos Urheberin oder Urheber, Nutzungsumfang und Einwilligung dokumentieren.
- Vor jeder Veröffentlichung `bildnachweise-rechte.html` auf den tatsächlichen Bildbestand abstimmen.

## Vor jeder neuen Version

1. `PROJEKT-CHECKLISTE.md` Punkt für Punkt prüfen.
2. Die sichtbare Prototypnummer fortlaufend erhöhen, sobald sich die Website sichtbar ändert.
3. Alle geänderten Seiten im Browser öffnen.
4. Das Browserfenster sehr schmal ziehen und Navigation, Texte und Schaltflächen prüfen.
5. Jeden geänderten Link anklicken.
6. Prüfen, ob Platzhalter sichtbar sind und ob neue personenbezogene Daten oder externe Dienste hinzugekommen sind.
7. Änderungen und Prüfergebnis im Commit oder Pull Request kurz beschreiben.

`AGENTS.md` enthält denselben verpflichtenden Ablauf für künftige KI-gestützte Bearbeitungen.

## Veröffentlichung

Der Ordner `wenn-ich-gross-bin-site` kann direkt auf GitHub Pages oder jedem einfachen Static-Hosting-Angebot veröffentlicht werden.
