# Projektanforderungen und Qualitätscheck

Diese Datei ist die verbindliche Prüfliste für jede größere Änderung an **„Wenn ich groß bin … / Das komische Dingsda“**. Vor einem Merge oder einer Veröffentlichung wird sie vollständig geprüft.

## 1. Inhalt und Haltung

- [ ] Die Seite öffnet Möglichkeiten, ohne Kinder früh auf einen Beruf festzulegen.
- [ ] Es gibt keine Tests, Individualdiagnostik, Typisierung oder Zuschreibung gegenüber Kindern.
- [ ] Texte stärken Neugier und Selbstwirksamkeit statt Leistung, Status oder Konkurrenz.
- [ ] Lebenswege dürfen Umwege, Fehler, Pausen und Wechsel sichtbar enthalten.
- [ ] Sprache ist klar, konkret und kindgerecht, aber nicht verniedlichend.
- [ ] Erwachsene werden glaubwürdig und unperfekt gezeigt; Interviewseiten bieten Platz für Foto und selbst gemaltes Bild.
- [ ] Texte für Kinder, Eltern sowie Schulen und andere Einladende sind klar voneinander abgegrenzt.

## 2. Verständlichkeit und Wartbarkeit

- [ ] Die einfachste angemessene technische Lösung wird verwendet.
- [ ] HTML ist semantisch gegliedert; Überschriften folgen einer nachvollziehbaren Reihenfolge.
- [ ] Wiederkehrende Gestaltung liegt in `styles.css`; Inline-Stile und Dopplungen werden vermieden.
- [ ] Klassen- und Dateinamen sind verständlich und einheitlich.
- [ ] Neue Abhängigkeiten oder ein Build-System werden nur eingeführt, wenn der konkrete Nutzen die zusätzliche Wartung rechtfertigt.
- [ ] Nicht verwendete Dateien, Regeln und Platzhalter werden entfernt oder eindeutig als Entwurf markiert.
- [ ] Neue Interviews folgen einer einheitlichen, dokumentierten Vorlage.
- [ ] Jedes veröffentlichte Interview bietet drei klar bezeichnete Lesefassungen: kurz für Grundschulkinder, ausführlicher für etwa 10–13-Jährige und vollständig für ältere Jugendliche und Erwachsene.
- [ ] Die vollständige Fassung ist die verbindliche inhaltliche Quelle. Kürzere Fassungen verdichten und erklären nur; sie erfinden, bewerten oder verändern keine Aussagen.
- [ ] Namen, Stationen, zeitliche Reihenfolge, direkte Zitate und Kernaussagen stimmen in allen drei Lesefassungen überein.
- [ ] Die Grundschul-Fassung steht an erster Stelle und ist sprachlich konkret, kurz und gut vorlesbar. Die anderen Fassungen sind leicht auffindbar, ohne die jüngsten Leserinnen und Leser zu überfordern.
- [ ] Die Grundschul-Fassung steht auf einer eigenen, ruhigen Leseseite. Fragen und Antworten sind unmittelbar sichtbar; Kerninhalte werden nicht hinter aufklappbaren Bereichen verborgen.
- [ ] Redaktionell ungeklärte oder nicht belegte Aussagen werden nicht veröffentlicht, sondern bis zur Klärung intern als offen dokumentiert.
- [ ] Interviewseiten nennen keine Ortsangaben. „KIB“ darf ohne Ortsangabe genannt werden.
- [ ] Das zugehörige Übergabedokument liegt unter `interviews-redaktion/` im Git-Repository und offene Redaktionsfragen bleiben dort nachvollziehbar.

## 3. Kindgerechte Navigation

- [ ] Allgemeine Prinzipien bewährter Kinderseiten dürfen untersucht und eigenständig übertragen werden; konkrete Designs, Figuren, Farbwelten, Illustrationen oder Formulierungen anderer Angebote werden nicht nachgeahmt.
- [ ] Navigation und Knöpfe sind danach benannt, was ein Kind dort sehen oder tun kann, nicht nach internen Fachbegriffen.
- [ ] Symbole unterstützen immer eine sichtbare Textbeschriftung und ersetzen sie nicht.
- [ ] Dasselbe Symbol hat auf allen Seiten dieselbe Bedeutung; die Zahl unterschiedlicher Symbole bleibt überschaubar.
- [ ] Klickflächen sind groß, vollständig anklickbar und mit Tastatur sowie Touch bedienbar.
- [ ] Der aktuelle Hauptbereich ist deutlich farbig und durch stärkere Schrift hervorgehoben; andere Bereiche treten zurück.
- [ ] Rückwege sind gut sichtbar und führen zu einem erwartbaren Ziel.
- [ ] Lesefassungen werden nach Textmenge bezeichnet („Kurz lesen“, „Mehr lesen“, „Alles lesen“), nicht wertend als leicht, mittel oder schwer.
- [ ] Bilder dienen der Orientierung. Fehlerhafte oder nicht freigegebene Bilder werden nicht stillschweigend ersetzt oder neu generiert.
- [ ] Die sichtbare Kinder-Hauptnavigation enthält nur **Start**, **Berufe** und **Dingsda**.
- [ ] Informationen für Eltern und Schulen sowie Projekt- und Kontaktseiten sind unter **Projekt & Erwachsene** nachgeordnet.
- [ ] „Für Kinder“ ist kein zweiter Startbereich: Die eigentliche Startseite ist bereits die Kinderseite.
- [ ] Die Wahl „Kurz lesen“, „Mehr lesen“ und „Alles lesen“ erscheint erst im Interviewbereich, nicht als globale Seiteneinstellung.
- [ ] Auf der Startseite ist „Berufe entdecken“ der erste und größere Einstieg. Dingsda bleibt als eigenständiger, erweiterbarer zweiter Einstieg sichtbar.
- [ ] Große Auswahlflächen sind vollständig anklickbar; ein sichtbarer Handlungstext beschreibt das Ziel zusätzlich.
- [ ] Kinder-Schaltflächen bleiben auch mobil groß und lesbar. Bei wenig Platz werden Inhalte umgebrochen oder untereinander angeordnet, nicht unleserlich verkleinert.
- [ ] Dasselbe Ziel verwendet überall exakt dasselbe Symbol und dieselbe Bezeichnung: insbesondere Koffer für Berufe und Lupe für Dingsda.
- [ ] Die beiden Startbereiche folgen derselben Reihenfolge aus Überschrift, Erklärung, Handlung und zurückhaltendem Orientierungsbild.
- [ ] Leitbilder unterstützen die Auswahl, dominieren aber weder Überschrift noch Handlung; auf Mobilgeräten bleiben Ziel und Handlung schnell erfassbar.

## 4. Modernes, zugängliches Web

- [ ] Jede Seite hat Sprache, Zeichensatz, Viewport, eindeutigen Titel und passende Beschreibung.
- [ ] Navigation ist mit Tastatur, Touch und kleinen Bildschirmen nutzbar; die aktuelle Seite ist ausgezeichnet.
- [ ] Bilder haben sinnvolle Alternativtexte oder sind korrekt als dekorativ markiert.
- [ ] Text, Fokusmarkierungen und Bedienelemente haben ausreichenden Kontrast und gut nutzbare Größen.
- [ ] Die Seite funktioniert bei 320 px Breite ohne ungewolltes horizontales Scrollen im Inhaltsbereich.
- [ ] Bewegungen berücksichtigen `prefers-reduced-motion`.
- [ ] Links sind aussagekräftig; externe Links werden kenntlich gemacht, falls später vorhanden.
- [ ] HTML und interne Links werden automatisiert oder manuell geprüft.

## 5. Datenschutz und Datensparsamkeit

- [ ] Es werden nur Daten erhoben, die für eine klar benannte Funktion wirklich nötig sind.
- [ ] Es gibt kein Tracking, Profiling, Fingerprinting und keine Werbe- oder Analyse-Cookies.
- [ ] Es werden keine externen Schriftarten, Skripte, Pixel oder Social-Media-Embeds unbemerkt nachgeladen.
- [ ] Kontakt läuft derzeit über einen normalen `mailto:`-Link; die Website speichert dabei selbst keine Formulardaten.
- [ ] Kinderfotos und personenbezogene Interviewinhalte werden nur mit dokumentierter Einwilligung veröffentlicht.
- [ ] Metadaten von veröffentlichten Bildern werden vorab geprüft und bei Bedarf entfernt.
- [ ] Änderungen an Hosting, Formularen, Videos, Karten oder Analysefunktionen lösen eine neue Datenschutzprüfung aus.
- [ ] Datenschutzerklärung und Impressum entsprechen dem tatsächlich veröffentlichten Stand.

## 6. Leistung und günstiges Hosting

- [ ] Die Website bleibt statisch hostbar, solange keine zwingende Funktion einen Server benötigt.
- [ ] Bilder sind passend dimensioniert und komprimiert; unnötig große Dateien werden vermieden.
- [ ] Es werden keine Bibliotheken für Funktionen eingebunden, die mit wenig HTML oder CSS lösbar sind.
- [ ] Die Kerninhalte bleiben auch ohne JavaScript lesbar und navigierbar.

## 7. Prüfung vor Merge oder Veröffentlichung

1. Alle geänderten Seiten auf Desktop und Mobilansicht ansehen.
2. Tastaturnavigation und sichtbaren Fokus prüfen.
3. Interne Links, Bildpfade und HTML-Struktur prüfen.
4. Bei Interviews alle drei Lesefassungen Satz für Satz mit der vollständigen Fassung abgleichen; Widersprüche und neue Behauptungen verhindern.
5. Suche nach Platzhaltern durchführen: `deine-domain`, `(dein Name`, `(Adresse`, `Vorname Nachname`.
6. Prüfen, ob neue Netzwerkaufrufe, Cookies, Speicherzugriffe oder personenbezogene Daten hinzugekommen sind.
7. Abweichungen von dieser Liste im Commit oder Pull Request kurz begründen.

## Veröffentlichungssperren

Eine öffentliche Veröffentlichung erfolgt **nicht**, solange:

- Impressum, Kontaktadresse oder Datenschutzerklärung sichtbare Platzhalter enthalten;
- Einwilligungen für personenbezogene Interviewinhalte oder Bilder ungeklärt sind;
- interne Links oder wesentliche mobile Ansichten fehlerhaft sind;
- neue datenerhebende Funktionen nicht dokumentiert und geprüft wurden.

## Aktueller technischer Stand

- Statische HTML-/CSS-Website ohne Framework oder Build-Schritt
- keine Cookies, kein Tracking, keine Analyse und kein clientseitiger Speicher
- keine extern geladenen Schriften, Skripte oder Medien
- Kontakt über `mailto:`; keine Übertragung an die Website selbst
- gemeinsame Gestaltung in `styles.css`
- bekannte Wartungsschuld: wiederholte Navigation und Footer in mehreren HTML-Dateien; bei weiterem Wachstum sollte eine kleine, statische Template-Lösung geprüft werden

## Bilder und Bildsprache

- [ ] Leitbilder wirken freundlich, klar, eigenständig und leicht handgezeichnet, zugleich geglättet und gestalterisch konsistent.
- [ ] Grundfiguren, Handlung und freigegebene Gegenstände bleiben bei einer Überarbeitung erhalten.
- [ ] Personen haben plausible Körper; es gibt keine zusätzlichen oder schwebenden Gliedmaßen oder Gegenstände.
- [ ] Text in Bildern ist vollständig, richtig geschrieben und nicht angeschnitten.
- [ ] Leitillustrationen haben einen transparenten Hintergrund und werden vollständig ohne automatischen Beschnitt angezeigt (`object-fit: contain`).
- [ ] Neue Bildfassungen überschreiben keine freigegebenen Originale, sondern erhalten eine neue, verständlich versionierte Datei.
- [ ] Bilddateien werden für Anzeigegröße, sichtbare Qualität, Ladezeit und Mobilansicht geprüft.
- [ ] Illustrationen, Symbole und Website teilen Konturstärke, Farbrollen und Grundstimmung, ohne konkrete fremde Designs nachzuahmen.
- [ ] Symbole bleiben auch ohne Farbe verständlich und werden in der Navigation mit sichtbarem Text kombiniert.
- [ ] Der freigegebene Symbolstand V12 ist die gestalterische Grundlage. Auf einer konkreten Seite werden nur die dort benötigten Symbole eingesetzt.
- [ ] Ein Logo oder eine Wort-Bild-Marke wird erst nach einer gesonderten Entwurfsfreigabe eingebaut.
