# Arbeitsregeln für Änderungen an dieser Website

Diese Regeln gelten für jede Person und jeden KI-Agenten, der eine neue Version vorbereitet.

## Vor jeder Änderung

1. `README.md` und `PROJEKT-CHECKLISTE.md` vollständig lesen.
2. Bestehende Dateien prüfen und erhalten; nichts ohne konkreten Grund ersetzen.
3. Möglichst in einem eigenen Branch arbeiten, nicht direkt auf `main`.
4. Bei größeren gestalterischen oder inhaltlichen Richtungswechseln vorher nachfragen.

## Während der Änderung

- Die Website statisch, datensparsam und ohne unnötige Abhängigkeiten halten.
- Gemeinsame Gestaltung in `styles.css` pflegen; Inline-Stile vermeiden.
- HTML semantisch, zugänglich und auf Mobilgeräten nutzbar halten.
- Neue oder ungewöhnliche Codebereiche kurz und in einfacher Sprache kommentieren.
- Kommentare sollen den Zweck erklären, nicht lediglich den Code wiederholen.
- Die Haltung des Projekts und die Zielgruppen-Trennung aus `PROJEKT-CHECKLISTE.md` einhalten.
- Keine echten Interviewaussagen, Kontaktdaten oder Einwilligungen erfinden.

## Pflichtprüfung für jede neue Version

Eine Version ist erst fertig, wenn diese Punkte geprüft wurden:

1. Alle HTML-Dateien lassen sich ohne Syntaxfehler einlesen.
2. Jede Seite hat genau eine Hauptüberschrift (`h1`).
3. Alle internen Links und Bildpfade zeigen auf vorhandene Dateien.
4. Startseite, Navigation und geänderte Seiten funktionieren mit Tastatur und auf kleiner Mobilbreite.
5. Die Kriterien in `PROJEKT-CHECKLISTE.md` sind erfüllt oder Abweichungen sind klar dokumentiert.
6. Es wurden keine unerwarteten Tracker, Cookies, externen Ressourcen oder Datenspeicherungen ergänzt.
7. Sichtbare Platzhalter wurden gesucht und als Veröffentlichungssperre gemeldet.

## Dokumentation der Version

Im Commit oder Pull Request kurz festhalten:

- Was wurde geändert?
- Warum wurde es geändert?
- Was wurde geprüft und mit welchem Ergebnis?
- Welche offenen Punkte oder Veröffentlichungssperren bleiben?

Kein positives Prüfergebnis behaupten, wenn eine Prüfung nicht ausgeführt werden konnte.
