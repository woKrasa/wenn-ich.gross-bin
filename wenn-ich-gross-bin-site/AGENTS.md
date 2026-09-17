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
- In Grundschulinterviews Kernfragen und Kernaussagen unmittelbar sichtbar lassen. Aufklappbare Bereiche nur für klar bezeichnete Zusatzinformationen einsetzen.
- Aufklappschaltflächen immer mit verständlichem Text und unterstützendem Richtungssymbol gestalten; Symbole allein genügen nicht.
- Kapitelanzeigen dienen nur der Orientierung und speichern oder bewerten keinen Lesefortschritt.

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
- Vor Veröffentlichung Urheberschaft, Nutzungserlaubnis und erforderliche Einwilligungen für jedes Foto dokumentieren.
- Fremde Referenzbilder ausschließlich intern zur Beobachtung verwenden; nicht in die Website oder das öffentliche Repository übernehmen.
- KI-Unterstützung bei Illustrationen transparent dokumentieren, aber keinen rechtlich ungeklärten exklusiven Urheberrechtsschutz behaupten.
- `bildnachweise-rechte.html` bei neuen oder ausgetauschten Bildern aktualisieren.
- Der Stil soll freundlich, klar, eigenständig und leicht handgezeichnet wirken, zugleich geglättet und konsistent. Konkrete fremde Designs werden nicht nachgeahmt.
- Symbole mit sichtbarer Beschriftung kombinieren und erst nach ausdrücklicher Freigabe in die Website übernehmen.
- Der Waschbär ist eine kleine, ermutigende Begleitfigur und keine Lehr- oder Autoritätsperson. Er bleibt deutlich kleiner als ein Grundschulkind.
- Für winkende und hängende Haltungen gelten sehr schmale Hand- und Fußgelenke sowie trichter- beziehungsweise dreiecksförmig zum Körper breiter werdende Fellkonturen. Hände und Füße bleiben klein und leicht länglich.
- Beim sitzenden Waschbären heißen die vorderen Gliedmaßen Vorderbeine. Sie bleiben in die tierische Körperform eingebunden und dürfen nicht wie menschlich angesetzte Arme wirken. In der kompakten Frontalhaltung verschmelzen ihre breiten oberen Fellflächen mit der Brust und verjüngen sich erst unten zu schmalen Gelenken und kleinen Pfoten.
- Zwischen den eng stehenden Vorderbeinen darf ein kurzer, weicher, annähernd balkenförmiger Schattenkanal liegen. Er beginnt oberhalb der Pfoten, endet stumpf in der unteren Rumpfhälfte und ersetzt eine harte Trennlinie; Hals und obere Brust bleiben ungeteilt.
- Je nach Haltung müssen die schmalen Gelenke nicht sichtbar sein. Insbesondere das freigegebene Kletterlogo wird nicht nachträglich anatomisch umgebaut.
- Die Augen bleiben dunkle blaue Ovale mit einem kleinen, gedämpften blaugrauen Reflex. Keine weiße Augenhaut, Glanzbögen oder erschrocken wirkende Augen ergänzen.
- Verbindliche Figurenstudien liegen unter `design/`; veröffentlichte Logo- und Bilddateien liegen unter `assets/`.
- Bei der Handlung **Interview lesen** ausschließlich `assets/waschbaer-interview-lesen-v1.png` einsetzen. Der freigegebene Lesewaschbär schaut mit gelber runder Lesebrille hinter einem großen Arbeitskoffer hervor, legt beide Pfoten auf die Kofferkante und der Koffer hat genau zwei Schnallen. Die identische Dokumentationsfassung liegt unter `design/waschbaer-posen-v1/interview-lesen-v1.png`.

## Verbindliche Navigationsstruktur

- Kinder-Hauptnavigation auf **Start**, **Berufe** und **Dingsda** begrenzen.
- Eltern, Schulen, Projekt und Kontakt unter **Projekt & Erwachsene** bündeln.
- Keine zweite parallele Kinder-Startseite in der Hauptnavigation anbieten.
- Lesemenge nur im Interviewbereich wählen lassen.
- Kinder-Schaltflächen großzügig, vollständig anklickbar und mobil lesbar halten.
- Den freigegebenen Symbolstand V12 verwenden und nur die für den jeweiligen Bereich benötigten Symbole anzeigen.
- Für dasselbe Ziel immer exakt dieselbe Symboldatei, Farbe und sichtbare Bezeichnung verwenden; keine nur ähnlichen Ersatzsymbole einsetzen.
- Den Header in hellem Sandbraun und inaktive Navigationsflächen in warmem Creme halten. Der aktive Hauptbereich bleibt durch Blau und Gelb deutlich hervorgehoben; Navigationsflächen dürfen nicht wie Aussparungen im Header wirken.
- Den ausgeschriebenen Projektnamen nicht erneut links neben der Hauptnavigation einblenden. Ein Logo erst nach gesonderter Freigabe einsetzen.
