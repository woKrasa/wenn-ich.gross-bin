# Arbeitsregeln für Änderungen an dieser Website

Diese Regeln gelten für jede Person und jeden KI-Agenten, der eine neue Version vorbereitet.

## Erst verstehen, dann handeln

- Informationen, Ideen und Gedanken der Nutzerin zunächst nur sammeln. Daraus nicht automatisch einen Arbeitsauftrag ableiten.
- Dateien, Website, GitHub-Branch oder andere Inhalte nur verändern, wenn die Nutzerin ausdrücklich sagt, dass etwas getan, erstellt, geändert, geprüft oder veröffentlicht werden soll.
- Vor jeder ausführenden Arbeit den verstandenen Arbeitsauftrag kurz und vollständig zusammenfassen.
- Danach auf ein ausdrückliches „Okay“ oder eine gleichwertige Bestätigung warten. Erst anschließend mit der Arbeit beginnen.
- Neue Informationen, die vor dieser Bestätigung hinzukommen, in die Zusammenfassung aufnehmen und weiterhin warten.
- Reine Statusfragen nur beantworten; sie sind kein Auftrag, Änderungen vorzunehmen.

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
- Bei Interviews immer zuerst die vollständige, freigegebene Fassung als inhaltliche Quelle pflegen. Daraus die Fassungen für 10–13-Jährige und Grundschulkinder ableiten.
- Kürzere Interviewfassungen dürfen vereinfachen, kürzen und schwierige Begriffe erklären, aber keine Aussagen ergänzen, umdeuten oder dramatisieren.
- Offene Redaktionshinweise aus Übergabedokumenten nicht als Interviewaussage veröffentlichen. Sie bleiben offen, bis sie anhand der Aufnahme oder durch Rückfrage bestätigt wurden.
- Keine Ortsangaben aus Interviewmaterial veröffentlichen.
- Interview-Übergabedokumente und redaktionelle Arbeitsstände unter `interviews-redaktion/` versionieren; sie nicht mit den sichtbaren HTML-Seiten vermischen.
- Änderungen an einer Interviewseite immer auch gegen das zugehörige Übergabedokument in `interviews-redaktion/` prüfen.

## Pflichtprüfung für jede neue Version

Eine Version ist erst fertig, wenn diese Punkte geprüft wurden:

1. Alle HTML-Dateien lassen sich ohne Syntaxfehler einlesen.
2. Jede Seite hat genau eine Hauptüberschrift (`h1`).
3. Alle internen Links und Bildpfade zeigen auf vorhandene Dateien.
4. Startseite, Navigation und geänderte Seiten funktionieren mit Tastatur und auf kleiner Mobilbreite.
5. Die Kriterien in `PROJEKT-CHECKLISTE.md` sind erfüllt oder Abweichungen sind klar dokumentiert.
6. Es wurden keine unerwarteten Tracker, Cookies, externen Ressourcen oder Datenspeicherungen ergänzt.
7. Sichtbare Platzhalter wurden gesucht und als Veröffentlichungssperre gemeldet.
8. Bei jedem geänderten Interview stimmen Fakten, Reihenfolge, Zitate und Kernaussagen in allen drei Lesefassungen mit der vollständigen Fassung überein.

## Dokumentation der Version

Im Commit oder Pull Request kurz festhalten:

- Was wurde geändert?
- Warum wurde es geändert?
- Was wurde geprüft und mit welchem Ergebnis?
- Welche offenen Punkte oder Veröffentlichungssperren bleiben?

Kein positives Prüfergebnis behaupten, wenn eine Prüfung nicht ausgeführt werden konnte.

## Verbindliche Regeln für Bilder

- Freigegebene Bildoriginale niemals überschreiben. Jede Überarbeitung erhält einen neuen, verständlich versionierten Dateinamen.
- Leitillustrationen vollständig und ohne Beschnitt anzeigen; einen transparenten Hintergrund erhalten.
- Vor Verwendung Motiv und Figuren prüfen: plausible Anatomie, keine zusätzlichen oder schwebenden Körperteile oder Gegenstände, keine ungewollten Telefone und kein abgeschnittener oder falscher Bildtext.
- Neue Bildvarianten auf Desktop und Mobil gegen Motiv, Figuren, Gegenstände, Text, Alternativtext, Dateigröße und sichtbare Qualität prüfen.
- Der Stil soll freundlich, klar, eigenständig und leicht handgezeichnet wirken, zugleich geglättet und konsistent. Konkrete fremde Designs werden nicht nachgeahmt.
- Symbole mit sichtbarer Beschriftung kombinieren und erst nach ausdrücklicher Freigabe in die Website übernehmen.

## Verbindliche Navigationsstruktur

- Kinder-Hauptnavigation auf **Start**, **Berufe** und **Dingsda** begrenzen.
- Eltern, Schulen, Projekt und Kontakt unter **Projekt & Erwachsene** bündeln.
- Keine zweite parallele Kinder-Startseite in der Hauptnavigation anbieten.
- Lesemenge nur im Interviewbereich wählen lassen.
- Kinder-Schaltflächen großzügig, vollständig anklickbar und mobil lesbar halten.
- Den freigegebenen Symbolstand V12 verwenden und nur die für den jeweiligen Bereich benötigten Symbole anzeigen.
- Für dasselbe Ziel immer exakt dieselbe Symboldatei, Farbe und sichtbare Bezeichnung verwenden; keine nur ähnlichen Ersatzsymbole einsetzen.
- Den ausgeschriebenen Projektnamen nicht erneut links neben der Hauptnavigation einblenden. Ein Logo erst nach gesonderter Freigabe einsetzen.
