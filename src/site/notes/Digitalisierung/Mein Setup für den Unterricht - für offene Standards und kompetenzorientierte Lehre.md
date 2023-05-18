---
{"dg-publish":true,"permalink":"/Digitalisierung/Mein Setup für den Unterricht - für offene Standards und kompetenzorientierte Lehre/"}
---

## Schritt 1: Warum nicht mehr OneNote?

Man sagt, der erste Schritt ist der schwerste - für dieses Projekt gilt diese Weisheit immerhin fast (denn der dritte Schritt war noch etwas schwieriger): Die Idee, mich von OneNote zu lösen, fiel mir nicht leicht - warum auch sollte man etwas aufgeben, das man für eine großartige Plattform für den schulischen Alltag hält (Meine ausführliche Begründung findet sich hier: [[Digitalisierung/Warum ich OneNote für eines der besten Tools für den Einsatz im Unterricht halte und warum ich es trotzdem nicht mehr benutze\|Warum ich OneNote für eines der besten Tools für den Einsatz im Unterricht halte und warum ich es trotzdem nicht mehr benutze]])? Letztendlich haben mich meine Schüler:innen überzeugt, die so gar nicht die Vorteile von OneNote sahen sondern die Hürden, ein separates System ihnen aufbürdet, wenn sie doch bloß an die Materialien kommen wollten, die ich ihnen bereitstellte. Diese Materialien würden dann in den eigenen Systemenen, Apps und Strukturen gespeichert, bearbeitet und neu zusammengestellt werden.
Ich hätte nun natürlich bei OneNote bleiben können und einfach alle meine Seiten exportieren können, um sie meinen Schüler:innen als PDF-Dateien o.ä. bereitzustellen. Hier machte die Praktikabilität mir aber einen Strich durch die Rechnung - denn so schön die "unendlichen" Leinwände von OneNote auch für die Arbeit an Tafelbildern sind, so unglücklich sehen sie aus, wenn sie als PDF-Dateien (und damit immer mehr oder weniger normiert auf DIN-Maße) exportiert werden. Außerdem erlaubte mir es OneNote nicht, meine exportierten Dateien im Blick zu behalten - ich konnte nur OneNote-Seiten erstellen, in die ich wiederum Dokumente einfügte. Das war aber unpraktisch, um bereits erstellte Versionen von Tafelbildern oder Arbeitsbögen vorzuhalten. Nicht zuletzt der Wunsch, datenschutzkonform(er) zu arbeiten, bewog mich dann endgültig, nach Alternativen zu suchen.

## Schritt 2: Was gibt es überhaupt auf dem Markt?
Ich habe zunächst begonnen mir anzuschauen, was es so alles an Software gibt, die OneNote ersetzen könnte. Diese Suche gestaltete sich durchaus schwierig, da die üblichen "Softwareklassen" nicht so recht umfassend greifen: OneNote ist natürlich eine Notizapplikation - aber die üblichen Verdächtigen wie Evernote, Google Notizen, Apple Notes usw. sind dann eben exklusiver für das Erstellen und Verwalten von Notizen als OneNote das ist. Auch Anwendungen aus dem Bereich der Whiteboard-Apps (wie etwa Microsoft Whiteboard, Xournal++ usw.) bieten nicht alle Funktionen, die ich an OneNote habe schätzen gelernt. Ich überlegte mir also zunächst, was ich in einem Ersatz eigentlich erwartete und kam dabei ungefähr auf folgende Liste:
**- Notizfunktionen**: Erfassen von Inhalten, Sortierung mehrerer Notizseiten mit mehreren Hierarchiebenen, präfiert in einer Ordner- bzw. Baumstruktur
**- Whiteboard-Funktionen**: Eine Art "großer Leinwand", auf der ich frei Schreiben, Zeichnen, Bilder und PDF-Dokumente anordnen und miteinander verknüpfen kann
**- Export von Daten**: Neu hinzugekommen ist der Wunsch, Inhalte leicht in gängige Formate exportieren zu können - Bildateien, PDF-Dateien (die ja nicht im eigentlichen Sinne "offen", dafür aber sehr gängig sind), einfache Textformate (nicht in propritären Formaten) usw.
**- Verfügbar auf allen Geräten**: Von Windows über Linux bis hin zu Android

Auf Basis dieser Liste wurde getestet, was das Zeug hält - neben den bereits oben erwähnten Vertretern waren es auch durchaus kleinere, unbekanntere oder spezieller Anwendungen, die ich getestet habe. Besonders interessant zeigten sich die Wissensverwaltungssyteme, die über Plugins erweitert werden konnten - mit allen Vor- und Nachteilen des Ansatzes hat tatsächlich ein Vertreter dieser Gattung meinen Auswahlprozess gewonnen. Getestet habe ich u.a.:
- Xournal++
- Logseq
- Notion
- Obsidian.md
- Canvas
- ...

Diese Liste ist nicht abschließend - es geht hier aber nur bedingt um den Auswahlprozess, weshalb ich die einzelnen  Abwägungen und Auswahlentscheidungen hier nicht weiter ausführen möchte. Letztendlich hat sich für mich **Obsidian.md** als App der Wahl durchgesetzt - auch wenn ich zwischenzeitlich Xournal++ und Notion favorisiert habe (aufgrund des "von Haus aus" einfacheren Handlings). Und mit dieser Entscheidung fing die Arbeit dann erst so richtig an ...

## Schritt 3: Obsidian.md oder wie ich lernte, die Offenheit zu lieben (vom Versuchen, Scheitern & der Beschränkung)
Obsidian.md (im Folgenden der Einfachheit halber "Obsidian") wird beworben als "second brain, for you, forever" (Quelle: [Obsidian.md](https://obsidian.md)). Damit ist gemeint, dass Obsidian ein Wissensmanagement-Tool sein möchte, dass sich der vernetzten Denkweise unseres Gehirns anpasst, sich stark personalisieren lässt - und damit keine Daten der Nutzer erhebt, sodass die Daten für immer die eigenen bleiben - dazu aber später noch mehr. Obsidian speichert grundsätzlich alle Notizen im offenen Standard Markdown. Dabei handelt es sich um eine Auszeichnungssprache wie auch HTML - nur viel einfacher und weniger komplex. Mit ein paar Befehlen lassen sich Texte passabel formatieren, Links und Grafiken einbetten, und Texte mit Überschriften untergliedern. Ohnehin ist Obsidian ganz auf offene Standards und Offenheit ausgerichtet: Es ist kein Benutzerkonto nötig, um die Software zu nutzen, alle Daten werden lokal in einem normalen Verzeichnis gespeichert (statt wie bei OneNote in einer propritären Datenbank in einem erzwungen in einem Cloud-Speicher) und sind in Formaten verfügbar, die auch mit anderen Programmen gelesen und verarbeitet werden können. Die Software kann mit einer Unmenge von Plugins erweitert und modifiziert werden (Stand heute, 2023-05-18 sind es 979(!) Erweiterungen, jeden Monat kommen ca. 10 neue Erweiterungen dazu) - was ein wichtiger Grund für meine Auswahl war. Als Randnotiz sei erwähnt, dass sogar die Plugins mit eigenen oder fremden Scripts erweiterbar sind (was ich später am Beispiel Excalidraw erläutern werde). Bei dieser unfassbaren Variabilität, Offenheit und Veränderbarkeit überrascht es umso mehr, dass Obsidian selbst keine offene - im Sinne von open source - Software ist. Da das aber kein Ausschlusskriterium für mich war, kann ich diesen Umstand gut akzeptieren.   

### Erste Schritte
Mein erster Versuch, mich in Obsidian einzuarbeiten, führte dazu, dass ich - restlos begeistert von all den Möglichkeiten - schnell bei 50 installierten Plugins war und mir die Software zur "eierlegenden Wollmilchsau" hochgezüchtet hatte. Mit dem Ergebnis, dass die App auf dem Smartphone sehr langsam startete und auch auf dem Laptop "Denkpausen" einlegte. Hinzu kam, dass ich meinen Vault - so heißt der Ordner, in dem Obsidian alle Dateien ablegt und organisiert - über einen Cloud-Speicher synchronisierte, was aufgrund häufiger Schreibaktionen zu regelmäßigen Synchronisationsfehlern führte, wenn mehrere Geräte gleichzeitig auf Notizen zugriffen - oder auch nur Obsidian geöffnet war. Viele Stunden arbeiten flossen in die Auswahl, Konfiguration und Einarbeitung mit all den Plugins und Obsidian selbst und ich träumte schon von einem System, dass mir ein "All-in-One" für all meine professionellen Anforderungen bot. Doch stopp, genau das wollte ich ja nicht - eine Plattform für alles! Und die Komplexität meiner Konfiguration zwang nicht nur meine Hardware in die Knie, sondern sorgte auch dafür, dass ich mehr mit der Wartung des Systems beschäftigt war als mit der eigentlichen Arbeit. Also gab ich Obsidian auf - das System war zu träge, zu komplex, zu unübersichtlich, erforderte zu hohen Wartungsaufwand. Aber das Problem saß hier vor dem Rechner. 

### Neuer Anlauf
Nach einigen Monaten nam ich einen neuen Anlauf, ich definierte klar meine Ziele (was wollte ich mit der Software tun und was nicht?) und überlegte genau: Welche Plugins brauche ich *wirklich*, welche sind nur "ziemlich cool"? Welche Struktur gebe ich meinem Vault?
Ich landete einer übersichtlichen Struktur und - je nach Gerät - 18 bis 20 Plugins, die, einmal konfiguriert, einfach zu handhaben waren. Überschaubarer, schneller und nun auch nicht mehr mittels einer Cloud synchronisiert, sondern - mit der Software SyncThing - End-zu-End-verschlüsselt direkt von Gerät zu Gerät; mit viel weniger Synchronisationsfehlern, weniger Datenschutzbedenken und deutlich weniger gedanklichem Overhead für mich!
Das alles klingt sehr technisch-nerdig und: Das war und ist es auch. Aber dieser Weg war nötig, um jetzt eben keinen Aufwand mehr in die technische Seite des Systems investieren zu müssen. Ich kann mich jetzt auf das Unterrichten, Organisieren, Verwalten und Strukturieren konzentrieren und werde dabei von einem zuverlässigen, schnellen, offenen System unterstützt, dass es mir erlaubt, für (fast) alle Anwendungsfälle eine passende und einfach zu handhabende Exportfunktion zu haben - diese Texte schreibe ich in Obsidian und mit einem Befehl landen sie, fertig formatiert, auf dieser Website. Tafelbilder bereite ich visuell ansprechend (wie ich finde) mit dem Plugin Excalidraw vor und projiziere Obsidian in einer minimalistischen Ansicht direkt auf die digitalen Whiteboards im Klassenraum. Ich verwalte Tabelle mit Schüler:innendaten - mit einem weiteren Plugin (Meld Encrypt) sicher AES-verschlüsselt. Dies sind nur einige Beispiele und Anwendungsfälle, die ich mittlerweile mit Obsidian umsetzen. Im Kern ist es für mich eine Software geblieben, die Tafelbilder und Arbeitsbögen beinhaltet - die ich nun aber in offenen Standards an meine Schüler:innen verteile. Da ich unsere Kommunikationsplattform als WebApp (über das Plugin Custom Frames) auch in Obsidian intergrieren konnte, fällt sogar noch der Schritt in eine externe App weg, wenn ich Tafelbilder oder Arbeitsblätter verschicke.

## Schritt 4: In die Welt hinein - Unterricht mit Obsidian, Excalidraw und Co.
In diesem Abschnitt möchte ich etwas mehr ins Detail gehen, wie ich meinen Unterricht in Obsidian organisiere und welche Plugins mich dabei wie unterstützen. Ich formuliere zunächst einen beispielhaften Ablauf, an dem ich dann die einzelnen Arbeits- und Präsentationsphasen aufzeige. Natürlich sieht mein Unterricht nicht immer so aus wie hier geschildert; es geht mir nur um das Exemplarische.

### Ein beispielhafter Ablauf ...
...

### ... und wie ich ihn mit meinem Setup bewältige
...

### Plugins, die ich benutze
Im Folgenden stelle ich (sehr) kurz die von mir verwendeten Plugins vor - ich konzentriere mich dabei auf diejenigen, die für die Anwendung im Unterricht und für die Organisation hilfreich sind. Alle anderen Plugins (z. B. "Style Settings" für die Konfiguration der Anwendungsoberfläche oder "Cycle through Panes" für die angenehmere Bedienung per Tastatur) lasse ich hier weg, da diese immer eine Frage des persönlichen Geschmacks sind. 

**Liste der Plugins (alphabetisch sortiert):**
- Custom Frames
	- Erlaubt es, selbst definierte Websites im rechten Seitenpanel zu laden - z. B. praktisch für das Laden unserer Kommunikationsplattform als WebApp, aber auch für andere Dienste (z. B. Taskcards, mit dem ich auch viel interagiere).
- Digital Garden
	- Ein echt tolles Plugin (das allerdings wirklich einigen Sachverstand erfordert, um korrekt konfiguriert zu werden - es sind dazu auch einige Accounts bei Webdiensten wie z. B. GitHub, Vercel oder Netlify nötig), dass einen "digitalen Garten" anlegt. Das ist im Grunde eine Website, auf der ich mit einem einzigen Befehl hübsch formatiert meine Notizen veröffentlichen kann - z. B. diesen Beitrag. Es ist also ein Blog, nur ohne die Möglichkeit der Interaktion.
- Excalidraw
	- Mein all-time favorite und must have (um zwei Anglizismen zu bemühen). Ohne Excalidraw wäre Obsidian für mich nicht sinnvoll nutzbar. Es stellt die "unendlichen" Schreib- und Zeichenfläche bereit (übrigens, Excalidraw gibt es primär auch als [WebApp](https://excalidraw.com) mit einer tollen Kollaborationsfunktion), verwendet ebenfalls zum Speichern offene Standards und kann durch heruntergeladene oder eigene Scripte erweitert werden (so habe ich mir z. B. ein Script geschrieben, um mir visuell ansprechende Tabellen generieren zu können). Obwohl nicht alle Funktionen so "smooth" funktionieren wie z. B. unter OneNote (insbesondere die Textbearbeitung ist viel rudimentärer) bevorzuge ich Excalidraw mittlerweile, schon alleine aufgrund des speziellen "Looks" den die App den mit ihr erstellten Inhalten verleiht. 
- Full Calendar
	- Ein nett anzuschauender Kalender, in dem die Einträge als Notizen in einem Ordner der eigenen Wahl abgelegt werden. Sehr elegant, um z. B. den Überblick zu behalten über all die Aufgaben, die man im Jahresablauf (immer wieder) zu bestimmten Zeitpunkten erledigen muss.
- Highlightr
	- Textformatierungs-Plugin, das etwas Farbe ins Spiel bringt. Nicht mehr, aber auch nicht weniger.
- Image Inserter
	- Hiermit kann ich - ohne die App zu verlassen - Bilder aus offenen Quellen (also solche, die Bilder mit Creative Commons Lizenzen) direkt in meine Notizen einfügen kann (z. B.v on Unsplash u. a.)
- Kanban
	- Ein sehr schönes Kanban-Modul, das viel Formatierungsoptionen für die Cards bietet - es erlaubt sogar, dass andere Notizen "transcluded" werden (d. h. ich kann Notizen auf einer Kanban-Karte referenzieren und dafür sorgen, dass nicht der Notiztitel, sondern die Notiz selbst direkt in der Karte angezeigt wird - sehr praktisch z. B. für Checklisten). 
- MAKE.md
	- Eine "eierlegende Wollmilchsau" was die (Um)Gestaltung des Workflows betrifft - das Plugin hat zu viele Funktionen, um sie hier auch nur im Ansatz zu beschreiben.
- Meld Encrypt
	- Nutze ich, um verschlüsselte Notizen zu erstellen, wenn ich besonders sensible Daten erfassen möchte. Auch Teile von Notizen können verschlüsselt werden.
- Ozan's Image in Editor Plugin
	- Unverzichtbar für das komfortable Anzeigen von Bildern in Notizen, die dann auch herangezoomt usw. werden können. 

## Schritt 5: Privacy by design - auch bei der Synchronisation
Hier sollen, abschließend, noch drei Punkte erwähnt werden, die zeigen, inwiefern mein Setup - hauptsächlich bedingt durch die ausgewählten Anwendungen - die Anforderung "privacy by design" erfüllt.

### Der Vault ist ein Ordner auf der eigenen Festplatte - nicht mehr und nicht weniger
...

### SyncThing: Direkte Synchronisation von Gerät zu Gerät, ohne Cloud-Anbindung - open source und Verschlüsselung inklusive
...

### Fazit: Meine Daten unter meiner Kontrolle 
...