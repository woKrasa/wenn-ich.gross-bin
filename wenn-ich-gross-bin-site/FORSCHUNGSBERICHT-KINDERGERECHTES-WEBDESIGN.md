# Forschungs- und Empfehlungsbericht: kindgerechtes Webdesign

Stand: 15. September 2026

## Kurzfazit

Für „Wenn ich groß bin …“ ist kein möglichst spielzeughaftes Design nötig, sondern eine ruhige, verständliche und fehlertolerante Kinderseite: wenige klare Entscheidungen, große beschriftete Ziele, kurze Textabschnitte, eine erkennbare Position und echte Wahlfreiheit. Illustrationen und kleine Reaktionen können Neugier wecken. Punkte, Serien, Ranglisten und dauerndes Belohnen passen dagegen weder zur Projektidee noch zur vorsichtigen Forschungslage.

Die belastbarste Grundlage bilden allgemeine Zugänglichkeitsstandards, empirische Kinder-Usability und Forschung zur Lesbarkeit. Befunde zu Gamification sind heterogen und stammen häufig aus Lernsystemen, nicht aus redaktionellen Interviewseiten. Fortschrittsanzeige oder Konfetti sind deshalb nur vorsichtig zu testende Unterpunkte, keine Kernanforderungen.

## 1. Zielgruppen nicht zusammenwerfen

Kinder zwischen etwa sechs und neun Jahren unterscheiden sich stark in Leseflüssigkeit, Erfahrung und Aufmerksamkeit. Forschung und Usability-Berichte empfehlen, Inhalte enger nach Alters- und Entwicklungsstand auszurichten und mit echten Kindern zu prüfen. Für dieses Projekt folgt daraus:

- Grundschule ist die voreingestellte und einfachste Fassung.
- 10–13-Jährige erhalten mehr Zusammenhang und längere Abschnitte.
- Die lange Fassung darf komplexer sein, bleibt aber klar gegliedert.
- Die drei Fassungen werden nicht als Leistungsskala („leicht/schwer“) bezeichnet. Besser ist eine freiwillige Mengenwahl wie „Kurz lesen“, „Mehr lesen“, „Alles lesen“.

Quellen: [Nielsen Norman Group: Children's UX](https://www.nngroup.com/articles/childrens-websites-usability-issues/), [Building a Playground – Literaturübersicht und Usability-Test](https://pmc.ncbi.nlm.nih.gov/articles/PMC4664536/)

## 2. Navigation und Orientierung

### Sinnvoll übernehmen

- Eine stabile Hauptnavigation, deren Reihenfolge und Bezeichnungen auf allen Seiten gleich bleiben.
- Begriffe entlang eines Kinderwegs wiederholen und nur konkret erweitern: **Berufe → Berufe entdecken → Berufsgeschichte lesen**. Redaktionelle Textsorten wie „Interview“ sind für Erwachsene und die interne Dokumentation sinnvoll, aber kein notwendiger Navigationsbegriff für Grundschulkinder.
- Aktuellen Bereich deutlich mit Text, Farbe und `aria-current` markieren; nicht allein durch Farbe.
- Symbol **und** verständliche Beschriftung verwenden. Symbole allein sind für ungeübte Lesende mehrdeutig.
- Dieselbe Interaktion überall gleich kennzeichnen: Aufklappbare Zusatzbereiche verwenden verständlichen Text und ein einheitliches Plus/Minus. Das Symbol unterstützt nur; der Text erklärt die Handlung.
- Die ganze Interviewkarte anklickbar machen, aber einen klaren Linktext sichtbar lassen.
- „Alle Berufe“ auf Berufsgeschichten zusätzlich zur Hauptnavigation als Rückweg anbieten.
- Große Touch-Ziele mit Abstand. WCAG 2.2 verlangt auf AA-Niveau grundsätzlich mindestens 24 × 24 CSS-Pixel oder ausreichenden Abstand; für eine Kinderseite sollte praktisch großzügiger gestaltet werden.

Quellen: [WCAG 2.2](https://www.w3.org/TR/WCAG22/), [W3C Understanding Target Size (Minimum)](https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html)

### Vorsichtig testen

- Eine kompakte horizontale Navigation kann auf kleinen Geräten funktionieren, muss aber sichtbar scrollbar und mit Tastatur vollständig erreichbar sein. Ein einfaches Menü mit klarer Öffnen-/Schließen-Beschriftung kann verständlicher sein.
- Piktogramme müssen mit Grundschulkindern getestet werden: „Haus = Start“ ist weithin bekannt, projektbezogene Zeichen wie „Dingsda“ nicht.

### Bewusst vermeiden

- Versteckte Navigation, wechselnde Begriffe, rein dekorative Icons und mehrere gleich starke Hauptaktionen.
- Das Design konkreter Kinderangebote kopieren. Übertragbar sind nur allgemeine, eigenständig umgesetzte Prinzipien.

## 3. Text, Schrift und Lesefluss

### Sinnvoll übernehmen

- Systemschriften ohne externen Abruf; keine Datenschutz- oder Ladezeitkosten.
- Für die Grundschulfassung als Startwert etwa 18–20 CSS-Pixel, Zeilenhöhe 1,6–1,75 und eine Textspalte um 45–60 Zeichen. Das sind Prototypwerte, keine universellen Naturgesetze.
- Linksbündiger Flattersatz, keine Silbentrennung als Voraussetzung, keine langen Versalpassagen.
- Ein Gedanke pro Absatz, konkrete Zwischenüberschriften und unmittelbar sichtbare Fragen und Antworten.
- Schriftgröße über relative Einheiten (`rem`) skalierbar halten und Browser-Zoom nicht blockieren.

Studien mit Kindern zeigen, dass Schriftgröße und konkrete Schriftgestaltung Lesegeschwindigkeit und Verständnis beeinflussen können; zugleich greifen Größe, Zeichenabstand, Wortabstand, Zeilenabstand und Zeilenlänge ineinander. Daher ist eine einzelne „perfekte Kinderschrift“ wissenschaftlich nicht begründbar. Ein aktueller Startwert muss mit Kindern verschiedener Lesestärken erprobt werden.

Quellen: [Hughes & Wilkins: Typography for children may be inappropriately designed](https://www.researchgate.net/publication/227732089_Typography_for_children_may_be_inappropriately_designed), [The Influence of Format Readability on Children's Reading Speed and Comprehension](https://www.mdpi.com/2227-7102/14/8/854), [U.S. Web Design System: Typography](https://designsystem.digital.gov/components/typography/)

### Vorsichtig testen

- Eine alternative gut lesbare lokale Schrift nur, wenn sie Umlaute, ß, klare Zeichenformen und gute Ladeleistung bietet. Systemschrift bleibt die robuste Ausgangslösung.
- Vorlesefunktion erst nach Datenschutz-, Bedien- und Qualitätsprüfung. Browser- oder Betriebssystemfunktionen können zunächst genügen.

### Bewusst vermeiden

- Sehr schmale, verspielte oder ausschließlich in Großbuchstaben gesetzte Fließtexte.
- Text auf unruhigen Illustrationen, starre Pixelhöhen und abgeschnittene Inhalte.
- Kernaussagen nur in Akkordeons verstecken. Aufklappen kann Zusatzdetails ordnen, darf aber das Verstehen nicht blockieren.

## 4. Layout, Bilder und visuelle Ruhe

### Sinnvoll übernehmen

- Eine klare Blickreihenfolge: Titel → kurze Einführung → Bild/Interviewvorschau → nächste Handlung.
- Viel freie Fläche, wenige Farben mit festen Rollen und wiederkehrende Karten-/Buttonmuster.
- Leitillustrationen vollständig anzeigen (`object-fit: contain`), nicht beschneiden. Transparenten Hintergrund erhalten.
- Bilder anatomisch und sachlich prüfen: keine zusätzlichen oder schwebenden Gliedmaßen/Gegenstände, keine ungewollten Telefone, kein abgeschnittener Text.
- Foto und selbst gemaltes Bild bei Interviews gleichwertig und respektvoll rahmen.
- Alternativtexte beschreiben Funktion oder Inhalt; rein dekorative Bilder erhalten leeren Alternativtext.

### Vorsichtig testen

- Kleine illustrative Hinweise an Abschnittsanfängen, sofern sie Orientierung verbessern und nicht konkurrieren.
- Farbcodierung für Lesemengen nur zusätzlich zu Text und Form, nie als einzige Unterscheidung.

### Bewusst vermeiden

- Kitschige Überladung, dreidimensionale Effekte ohne Funktion, visuelles Dauerfeuer und bildhafte Dekoration zwischen jedem Absatz.
- Automatisches Zuschneiden von Leitmotiven oder Austausch freigegebener Originale ohne neue, versionierte Datei.

## 5. Spielerische Interaktion, Feedback und Selbstwirksamkeit

Spielerisch bedeutet hier: entdecken, wählen, fragen und ohne Angst zurückgehen können. Es bedeutet nicht, das Lesen in Wettbewerb oder Pflichterfüllung zu verwandeln.

### Sinnvoll übernehmen

- Unmittelbares, sachliches Feedback: Ein gedrückter Button reagiert sichtbar; ein gewählter Lesemodus bleibt erkennbar.
- Freiwillige Wahl von Lesemenge und Reihenfolge.
- Kleine Entdeckmomente, die zum Inhalt passen, etwa „Was glaubst du, wofür ist dieser Gegenstand?“ vor der Auflösung.
- Fehlerfreundliche Navigation: Zurückgehen verliert nichts und wird nicht negativ kommentiert.

### Fortschritt und Konfetti – vorsichtig testen

- Ein **nicht gespeicherter Abschnittswegweiser** wie „Abschnitt 1 von 3“ kann Orientierung geben. Er darf nicht suggerieren, dass Kinder etwas leisten oder vollständig abarbeiten müssen.
- Ein Fortschrittsbalken sollte nur tatsächliche, verständliche Einheiten abbilden, nicht Scrollposition vortäuschen. Ohne JavaScript genügen drei beschriftete Punkte oder eine Kapitelanzeige.
- Konfetti höchstens als einmalige, sehr kurze und freiwillige Abschlussreaktion; standardmäßig aus, nie mit Punkten/Streaks gekoppelt und bei `prefers-reduced-motion: reduce` vollständig deaktiviert. Eine ruhige Textreaktion („Du bist am Ende des Interviews angekommen“) ist die sichere Voreinstellung.
- Vor einer Einführung mit wenigen Kindern beobachten: Verstehen sie die Anzeige? Fühlen sie sich ermutigt oder gedrängt? Lenkt die Reaktion vom Interview ab?

Systematische Übersichten berichten zwar häufig positive Motivations- oder Engagementeffekte von Gamification, betonen aber Unterschiede nach Element, Kontext und Zielgruppe. Ein Großteil untersucht Unterricht oder Lernapps; daraus folgt kein automatischer Nutzen für diese Seite. Externe Belohnungen können außerdem die Projektbotschaft unterlaufen. Quellen: [Gamification and motivation in adolescents – systematic review](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2025.1575104/full), [Examining the effectiveness of gamification](https://pmc.ncbi.nlm.nih.gov/articles/PMC10591086/)

### Bewusst vermeiden

- Punkte, Ranglisten, tägliche Serien, künstliche Verknappung, Verlustanzeigen und beschämende Formulierungen.
- „Du hast gewonnen“, wenn lediglich ein Text gelesen wurde.
- Belohnungen, die Kinder zum längeren Bleiben oder zur Preisgabe von Daten bewegen.

## 6. Zugänglichkeit und unterschiedliche Bedürfnisse

- WCAG 2.2 AA als Mindestziel nutzen; automatische Tests durch Tastatur-, Zoom-, Screenreader- und echte Nutzungstests ergänzen.
- Sichtbarer Fokus, ausreichender Kontrast, semantische Überschriften, aussagekräftige Links und vollständig bedienbare Elemente.
- Animationen und Übergänge reduzieren oder abschalten, wenn das Betriebssystem dies verlangt.
- Informationen nicht nur über Farbe, Bewegung, Richtung oder Ton vermitteln.
- Keine automatische Wiedergabe, kein Zeitdruck und keine unerwarteten Layoutsprünge.
- Kindgerechte Gestaltung nicht mit Vereinfachung aller Kinder gleichsetzen: Vorlesen, Zoom, Tastatur und unterschiedliche Lesegeschwindigkeit mitdenken.

Quelle: [WCAG 2.2](https://www.w3.org/TR/WCAG22/)

## 7. Datenschutz und schlanke Technik

Der aktuelle statische Ansatz ist besonders passend. Die ICO-Kinderleitlinien stellen das Kindeswohl, Datenminimierung und Schutz vor manipulativen Nudges in den Mittelpunkt. Für dieses Projekt folgt daraus:

- keine Konten, Profile, Analytics, Fingerprinting, Werbe- oder Social-Media-Pixel;
- keinen Lesefortschritt personenbezogen oder dauerhaft speichern;
- keine externen Fonts, Bibliotheken oder Embeds ohne zwingenden Zweck und neue Datenschutzprüfung;
- Bilder von Menschen nur mit dokumentierter Einwilligung; Metadaten prüfen;
- spielerische Funktionen vollständig lokal und möglichst mit HTML/CSS umsetzen;
- wenn JavaScript nötig wird, klein, verständlich, ohne Netzwerkzugriff und ohne `localStorage` als Standard.

Quellen: [ICO: Age appropriate design code](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/childrens-information/childrens-code-guidance-and-resources/age-appropriate-design-a-code-of-practice-for-online-services/), [EU-DSGVO Art. 25 – Datenschutz durch Technikgestaltung](https://eur-lex.europa.eu/eli/reg/2016/679/oj)

## 8. Priorisierte Empfehlung für den nächsten Prototyp

### Sinnvoll übernehmen

1. Grundschule als klarer Standard, daneben „Kurz lesen / Mehr lesen / Alles lesen“.
2. Ruhige Interviewübersicht mit einer vollständig anklickbaren Karte.
3. Große beschriftete Navigation mit eigenständigem Symbolsystem und sichtbarer aktueller Position.
4. Grundschultext in größerer Schrift, schmalerer Spalte und direkt sichtbaren Fragen/Antworten.
5. Vollständig sichtbare, versionierte Leitbilder ohne Beschnitt.
6. WCAG- und Datenschutzprüfung bei jeder Version.

### Vorsichtig testen

1. Drei-Punkte-Kapitelanzeige „1 von 3“ ohne Speicherung.
2. Kleine inhaltliche Rätsel vor der Auflösung.
3. Eine optionale ruhige Abschlussreaktion; Konfetti nur als reduzierte, abschaltbare Variante.
4. Menüvariante auf kleinen Bildschirmen und Verständlichkeit der Symbole mit Kindern.

### Bewusst vermeiden

1. Punkte, Badges, Ranglisten, Streaks und Leistungslabels.
2. Tracking oder persistente Fortschrittsspeicherung.
3. überladene Animation, Autoplay und versteckte Kerninhalte.
4. konkrete Gestaltungselemente bekannter Kinderseiten nachahmen.

## 9. Empfohlener Test mit Kindern

Ein kleiner moderierter Test liefert mehr als weitere Geschmacksdiskussionen. Mit Einwilligung der Sorgeberechtigten, ohne unnötige personenbezogene Aufzeichnung:

1. Kind findet von Startseite aus ein Interview.
2. Kind erklärt, was „Kurz/Mehr/Alles lesen“ bedeutet.
3. Kind findet zurück zur Interviewübersicht und zur Startseite.
4. Kind liest einen kurzen Abschnitt oder lässt ihn vorlesen und erzählt, worum es ging.
5. Kind bewertet Kapitelanzeige und optionale Abschlussreaktion: hilfreich, egal oder störend.

Beobachtet werden Verständnis, Fehlwege, Lesbarkeit und Gefühl – nicht das Kind bewertet oder diagnostiziert. Ergebnisse werden nur als Änderungen am Angebot formuliert.

## Quellenlage und Grenzen

WCAG und Datenschutzkodizes sind normative bzw. regulatorische Leitlinien, keine Wirksamkeitsstudien. Kinder-Usability-Studien unterscheiden sich nach Alter, Gerät, Aufgabe und Stichprobe. Gamification-Forschung ist besonders kontextabhängig. Deshalb sind konkrete Maße in diesem Bericht Startwerte; die endgültige Entscheidung sollte aus barrierefreier Prüfung plus Tests mit der tatsächlichen Zielgruppe entstehen.
