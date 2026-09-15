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
- `styles.css` – Farben, Abstände, Schriftgrößen und Mobilansicht
- `assets/` – Bilder
- `interviews-redaktion/` – Übergabedokumente und Arbeitsfassungen der Interviews; diese Inhalte gehören zur Redaktion und sind keine eigene Webseite

## Inhalte pflegen

- Vor größeren Änderungen und vor jeder Veröffentlichung `PROJEKT-CHECKLISTE.md` prüfen.
- Neue Interviews erhalten eine eigene HTML-Datei nach dem Muster von `interview-template.html`.
- Neue Interviewseiten werden in `interviews.html` verlinkt.
- Platzhalter in `kontakt.html`, `impressum.html` und `datenschutz.html` müssen vor einer Veröffentlichung durch echte Kontaktdaten ersetzt werden.
- Das Übergabedokument zu jedem Interview zusätzlich unter `interviews-redaktion/` im Git-Repository ablegen. So bleiben Quelle, offene Fragen und spätere Änderungen nachvollziehbar.

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

Jedes Interview erhält eine ruhige Einstiegsseite mit Bildplätzen, kurzem Berufstext und Auswahl der Textmenge. Die eigentlichen Lesefassungen stehen auf getrennten Seiten. So sehen Grundschulkinder nur den für sie gedachten Text und werden nicht von längeren Fassungen abgelenkt.

- **Kurz:** Grundschule; kurze Fragen und Antworten, konkrete Wörter, gut zum Vorlesen.
- **Mehr:** etwa 10–13 Jahre; mehr Stationen, Zusammenhänge und Schwierigkeiten.
- **Vollständig:** ältere Jugendliche und Erwachsene; das ganze redigierte Interview und verbindliche Quelle der beiden kürzeren Fassungen.

Nach jeder inhaltlichen Änderung zuerst die vollständige Fassung aktualisieren und danach beide kürzeren Fassungen erneut vergleichen.

In der Grundschul-Fassung sind alle Fragen und Antworten sofort sichtbar. Große Fragen, kurze Absätze, eine schmale Textspalte und viel Abstand unterstützen den Lesefluss.

### Ein Bild austauschen

Das neue Bild in `assets/` speichern. Ein freigegebenes Original nicht überschreiben: eine neue, verständlich versionierte Datei anlegen, zum Beispiel `motiv-v2.png`. Im passenden `<img>`-Element nur den Wert hinter `src=` ändern. Der Text hinter `alt=` beschreibt das Bild für Menschen, die es nicht sehen können, und muss ebenfalls passen. Danach Desktop und Mobilansicht prüfen: Das ganze Motiv und etwaiger Bildtext müssen sichtbar bleiben.

## Vor jeder neuen Version

1. `PROJEKT-CHECKLISTE.md` Punkt für Punkt prüfen.
2. Alle geänderten Seiten im Browser öffnen.
3. Das Browserfenster sehr schmal ziehen und Navigation, Texte und Schaltflächen prüfen.
4. Jeden geänderten Link anklicken.
5. Prüfen, ob Platzhalter sichtbar sind und ob neue personenbezogene Daten oder externe Dienste hinzugekommen sind.
6. Änderungen und Prüfergebnis im Commit oder Pull Request kurz beschreiben.

`AGENTS.md` enthält denselben verpflichtenden Ablauf für künftige KI-gestützte Bearbeitungen.

## Veröffentlichung

Der Ordner `wenn-ich-gross-bin-site` kann direkt auf GitHub Pages oder jedem einfachen Static-Hosting-Angebot veröffentlicht werden.
