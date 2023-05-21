---
{"dg-publish":true,"permalink":"/Digitalisierung/Mein Setup für den Unterricht - für offene Standards und kompetenzorientierte Lehre/"}
---

## Schritt 1: Warum nicht mehr OneNote?

Man sagt, der erste Schritt ist der schwerste - für dieses Projekt gilt diese Weisheit immerhin fast (denn der dritte Schritt war noch etwas schwieriger): Die Idee, mich von OneNote zu lösen, fiel mir nicht leicht - warum auch sollte man etwas aufgeben, das man für eine großartige Plattform für den schulischen Alltag hält (Meine ausführliche Begründung findet sich hier: [[Digitalisierung/Warum ich OneNote für eines der besten Tools für den Einsatz im Unterricht halte und warum ich es trotzdem nicht mehr benutze\|Warum ich OneNote für eines der besten Tools für den Einsatz im Unterricht halte und warum ich es trotzdem nicht mehr benutze]])? Letztendlich haben mich meine Schüler:innen überzeugt, die so gar nicht die Vorteile von OneNote sahen sondern die Hürden, ein separates System ihnen aufbürdet, wenn sie doch bloß an die Materialien kommen wollten, die ich ihnen bereitstellte. Diese Materialien würden dann in den eigenen Systemenen, Apps und Strukturen gespeichert, bearbeitet und neu zusammengestellt werden.
Ich hätte nun natürlich bei OneNote bleiben können und einfach alle meine Seiten exportieren können, um sie meinen Schüler:innen als PDF-Dateien o.ä. bereitzustellen. Hier machte die Praktikabilität mir aber einen Strich durch die Rechnung - denn so schön die "unendlichen" Leinwände von OneNote auch für die Arbeit an Tafelbildern sind, so unglücklich sehen sie aus, wenn sie als PDF-Dateien (und damit immer mehr oder weniger normiert auf DIN-Maße) exportiert werden. Außerdem erlaubte mir es OneNote nicht, meine exportierten Dateien im Blick zu behalten - ich konnte nur OneNote-Seiten erstellen, in die ich wiederum Dokumente einfügte. Das war aber unpraktisch, um bereits erstellte Versionen von Tafelbildern oder Arbeitsbögen vorzuhalten. Nicht zuletzt der Wunsch, datenschutzkonform(er) zu arbeiten, bewog mich dann endgültig, nach Alternativen zu suchen.

## Schritt 2: Was gibt es überhaupt auf dem Markt?
Ich habe zunächst begonnen mir anzuschauen, was es so alles an Software gibt, die OneNote ersetzen könnte. Diese Suche gestaltete sich durchaus schwierig, da die üblichen "Softwareklassen" nicht so recht umfassend greifen: OneNote ist natürlich eine Notizapplikation - aber die üblichen Verdächtigen wie Evernote, Google Notizen, Apple Notes usw. sind dann eben exklusiver für das Erstellen und Verwalten von Notizen als OneNote das ist. Auch Anwendungen aus dem Bereich der Whiteboard-Apps (wie etwa Microsoft Whiteboard, Xournal++ usw.) bieten nicht alle Funktionen, die ich an OneNote habe schätzen gelernt. Ich überlegte mir also zunächst, was ich in einem Ersatz eigentlich erwartete und kam dabei ungefähr auf folgende Liste:
**- Notizbuchfunktionen**: Erfassen von Inhalten, Sortierung mehrerer Notizseiten mit mehreren Hierarchiebenen, präfiert in einer Ordner- bzw. Baumstruktur
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
Obsidian.md (im Folgenden der Einfachheit halber "Obsidian") wird beworben als "second brain, for you, forever" (Quelle: [Obsidian.md](https://obsidian.md)). Damit ist gemeint, dass Obsidian ein Wissensmanagement-Tool sein möchte, dass sich der vernetzten Denkweise unseres Gehirns anpasst, sich stark personalisieren lässt - und damit keine Daten der Nutzer erhebt, sodass die Daten für immer die eigenen bleiben; dazu aber später noch mehr. Obsidian speichert grundsätzlich alle Notizen im [offenen Standard Markdown](https://markdown.de/). Dabei handelt es sich um eine Auszeichnungssprache wie auch HTML - nur viel einfacher und weniger komplex. Mit ein paar Befehlen lassen sich Texte passabel formatieren, Links und Grafiken einbetten, und Texte mit Überschriften untergliedern. Ohnehin ist Obsidian ganz auf offene Standards und Offenheit ausgerichtet: Es ist kein Benutzerkonto nötig, um die Software zu nutzen, alle Daten werden lokal in einem normalen Verzeichnis gespeichert (statt wie bei OneNote in einer propritären Datenbank in einem erzwungen in einem Cloud-Speicher) und sind in Formaten verfügbar, die auch mit anderen Programmen gelesen und verarbeitet werden können. Die Software kann mit einer Unmenge von Plugins erweitert und modifiziert werden (Stand heute, 2023-05-18 sind es 979(!) Erweiterungen, jeden Monat kommen ca. 10 neue Erweiterungen dazu) - was ein wichtiger Grund für meine Auswahl war. Als Randnotiz sei erwähnt, dass sogar die Plugins mit eigenen oder fremden Scripts erweiterbar sind (was ich später am Beispiel Excalidraw erläutern werde). Bei dieser unfassbaren Variabilität, Offenheit und Veränderbarkeit überrascht es umso mehr, dass Obsidian selbst keine offene - im Sinne von *open source* - Software ist. Da das aber kein Ausschlusskriterium für mich war, kann ich diesen Umstand gut akzeptieren.   

### Erste Schritte
Mein erster Versuch, mich in Obsidian einzuarbeiten, führte dazu, dass ich - restlos begeistert von all den Möglichkeiten - schnell bei >50 installierten Plugins war und mir die Software zur "eierlegenden Wollmilchsau" hochgezüchtet hatte. Mit dem Ergebnis, dass die App auf dem Smartphone sehr langsam startete und auch auf dem Laptop "Denkpausen" einlegte. Hinzu kam, dass ich meinen *Vault* - so heißt der Ordner, in dem Obsidian alle Dateien ablegt und organisiert - über einen Cloud-Speicher synchronisierte, was aufgrund häufiger Schreibaktionen zu regelmäßigen Synchronisationsfehlern führte, wenn mehrere Geräte gleichzeitig auf Notizen zugriffen - oder auch nur Obsidian auf mehreren Geräten gleichzeitig geöffnet war. Viele Stunden Arbeit flossen in die Auswahl, Konfiguration und Einarbeitung mit all den Plugins und Obsidian selbst und ich träumte schon von einem System, dass mir ein "All-in-One" für all meine professionellen Anforderungen bot. Doch stopp, genau das wollte ich ja nicht - eine Plattform für alles! Und die Komplexität meiner Konfiguration zwang nicht nur meine Hardware in die Knie, sondern sorgte auch dafür, dass ich mehr mit der Wartung des Systems beschäftigt war als mit der eigentlichen Arbeit. Also gab ich Obsidian auf - das System war zu träge, zu komplex, zu unübersichtlich, erforderte zu hohen Wartungsaufwand. Aber das Problem saß hier vor dem Rechner. 

### Neuer Anlauf
Nach einigen Monaten nam ich einen neuen Anlauf, ich definierte klar meine Ziele (was wollte ich mit der Software tun und was nicht?) und überlegte genau: Welche Plugins brauche ich *wirklich*, welche sind nur "ziemlich cool"? Welche Struktur gebe ich meinem Vault?
Ich landete bei einer übersichtlichen Struktur und - je nach Gerät - 18 bis 20 Plugins, die, einmal konfiguriert, einfach zu handhaben waren. Überschaubarer, schneller und nun auch nicht mehr mittels einer Cloud synchronisiert, sondern - mit der Software SyncThing - End-zu-End-verschlüsselt direkt von Gerät zu Gerät; mit viel weniger Synchronisationsfehlern, weniger Datenschutzbedenken und deutlich weniger gedanklichem Overhead für mich!
Das alles klingt sehr technisch-nerdig und: Das war und ist es auch. Aber dieser Weg war nötig, um jetzt eben keinen Aufwand mehr in die technische Seite des Systems investieren zu müssen. Ich kann mich jetzt auf das Unterrichten, Organisieren, Verwalten und Strukturieren konzentrieren und werde dabei von einem zuverlässigen, schnellen, offenen System unterstützt, dass es mir erlaubt, für (fast) alle Anwendungsfälle eine passende und einfach zu handhabende Exportfunktion zu haben - diese Texte schreibe ich in Obsidian und mit einem Befehl landen sie, fertig formatiert, auf dieser Website (dem Plugin **Digital Garden** sei dank). Tafelbilder bereite ich visuell ansprechend (wie ich finde) mit dem Plugin **Excalidraw** vor und projiziere Obsidian in einer minimalistischen Ansicht (ich schalte z. B. die Seiten-Panels aus für die Tafelansicht) direkt auf die digitalen Whiteboards im Klassenraum. Ich verwalte Tabelle mit Schüler:innendaten - mit einem weiteren Plugin (**Meld Encrypt**) sicher AES-verschlüsselt. Dies sind nur einige Beispiele und Anwendungsfälle, die ich mittlerweile mit Obsidian umsetzen. Im Kern ist es für mich eine Software geblieben, die Tafelbilder und Arbeitsbögen beinhaltet - die ich nun aber in offenen Standards an meine Schüler:innen verteile. Da ich unsere Kommunikationsplattform als WebApp (über das Plugin **Custom Frames**) auch in Obsidian intergrieren konnte, fällt sogar noch der Schritt in eine externe App weg, wenn ich Tafelbilder oder Arbeitsblätter verschicke.
Eine Auflistung aller meiner Plugins mit einer kurzen Beschreibung und ein Link zur Anleitung, wie man SyncThing für Obsidian einrichtet, findet sich weiter unten in diesem Text.

## Schritt 4: In die Welt hinein - Unterricht mit Obsidian, Excalidraw und Co.
In diesem Abschnitt möchte ich etwas mehr ins Detail gehen, wie ich meinen Unterricht in Obsidian organisiere und welche Plugins mich dabei wie unterstützen. Ich formuliere zunächst einen beispielhaften Ablauf, an dem ich dann die einzelnen Arbeits- und Präsentationsphasen aufzeige. Natürlich sieht mein Unterricht nicht immer so aus wie hier geschildert; es geht mir nur um das Exemplarische.

### Ein beispielhafter Ablauf ...
Für eine Unterrichtsstunde möchte ich einen *Arbeitsbogen* und ein *Tafelbild* vorbereiten - das Tafelbild soll dabei so gestaltet werden, dass ich es im Unterricht gemeinsam mit den Schüler:innen weiterentwickeln und Ergebnisse notieren kann. Dazu sollen z. B. um ein zentrales Bild herum *Stichworte handschriftlich* eingetragen und weiter unten in einer *Tabelle* Antworten auf Fragen zu einem Text erfasst werden können. Zum Einstieg verwende ich ein kurzes *Video*, das ich direkt von YouTube abspiele und das die Schüler:innen mit einer Situation konfrontiert, zu der sie Stellung beziehen können. Zum Abschluss der Stunde möchte ich den Schüler:innen Gelegenheit zur Reflexion geben, indem sie jeweils eine offen gebliebene Frage auf einem *gemeinsamen Notizbblock notieren*. Diese Fragen werde ich speichern und in der nachfolgenden Stunde als Einstieg verwenden.

### ... und wie ich ihn mit meinem Setup bewältige
Ich gehe hier chronologisch vor, konzentriere mich dabei auf die Vorbereitung bzw. Nutzung der Materialien:

**Arbeitsbogen:**
Den Arbeitsbogen kann ich ebenfalls mit Obsidian erstellen - ich verwende dafür entweder einfach eine **Markdown-Notizseiten**, auf der ich Bilder, Tabellen, formatierten Text usw. einbetten und ggf. ein Banner-Bild oben in die Notiz einfügen kann. Oder aber ich verwende hier - wenn ich etwas aufwändiger gestalten möchte - eine **Excalidraw-Notizseite** (s. Abbildung unten). Abschließend exportiere ich die Notizseite als PDF-Datei, die ich direkt in einen dafür vorbereiteten Ordner in unserer Kommunikationsplattform hochladen kann.
![Pasted image 20230519124742.png](/img/user/Digitalisierung/Anh%C3%A4nge/Pasted%20image%2020230519124742.png)

**Tafelbild:** 
Für das Tafelbild verwende ich auf jeden Fall eine Excalidraw-Notizseite, um die nötige Flexibilität zu bekommen. Da ich während des Unterrichts handschriftlich notieren möchte, bereite ich zunächst die Ausgangssituation vor:
![SmartSelect_20230519_164439_Obsidian.jpg](/img/user/Digitalisierung/Anh%C3%A4nge/SmartSelect_20230519_164439_Obsidian.jpg)
Mit dieser Vorbereitung gehe ich dann in den Unterricht, teile meinen Bildschirm (Modus: gespiegelter Bildschirm) und kann dann direkt auf meinem Bildschirm schreiben - alternativ könnte ich auch direkt am Whiteboard mit dem entsprechenden Stift schreiben, was aber meist nicht so präzise ist und meine Handschrift noch schlechter werden lässt als sie ohnehin schon ist 😉.

**Stichworte handschriftlich erfassen:**
Ich kann ebenso einfach handschriftliche Notizen erfassen wie in OneNote - mir stehen ebenfalls mehrere Stifte zur Verfügung (ich kann auch selbst eigene definieren und mein Schreibstil recht feingliedrig anpassen - hier habe ich einen "Fineliner" in blau verwendet):
![SmartSelect_20230519_164900_Obsidian.jpg](/img/user/Digitalisierung/Anh%C3%A4nge/SmartSelect_20230519_164900_Obsidian.jpg)

**Tabelle:**
Für das Erstellen von Tabellen in Excalidraw-Notizen habe ich mir ein eigenes Script geschrieben, das bestehende Elemente nutzt, um daraus eine hübsche Tabelle zu bauen (Boxen werden zu Tabellen zusammengefügt) - das Schreiben von Scripts für das Excalidraw-Plugins geht wirklich fix; allerdings nur, wenn man des Programmierens mächtig ist und schon etwas in JavaScript eingearbeitet ist; die spezifischen Funktionen der API sind gut dokumentiert. Für die Abschätzung, wie so ein Vorhaben aussieht und wie wenig Code für diese Aufgabe nötig ist, hier mein (etwas umständlicher) Code:

``` javascript
// Version checken
if(!ea.verifyMinimumPluginVersion || !ea.verifyMinimumPluginVersion("1.5.21")) {
  new Notice("This script requires a newer version of Excalidraw. Please install the latest version.");
  return;
}

// Standard values for rows and columns - get new values from user
let rows = 1; let columns = 1;
rows = parseInt (await utils.inputPrompt("number of rows?","number",rows.toString()));
columns = parseInt (await utils.inputPrompt("number of columns?","number",columns.toString()));
// Standard values for cell width and height - get new values from user
let width = 100; let height = 50;
width = parseInt (await utils.inputPrompt("cell width?","number",width.toString()));
height = parseInt (await utils.inputPrompt("cell height?","number",height.toString()));
// Should the height of the first row be different?
let firstRowHeight = height;
firstRowHeight = parseInt (await utils.inputPrompt("Height of first row?","number",firstRowHeight.toString()));

var x = 0; var y = 0; var i = 0; var table = []; var actualHeight = 0; var space = 0;
for (y = 0; y < rows; y++) {
	actualHeight = actualHeight + space;
	for (x = 0; x < columns; x++) {
		if ((firstRowHeight !== height) && (y == 0)) {
			table[i] = ea.addRect(x*width, actualHeight, width, firstRowHeight);
			space = firstRowHeight;
		} else {
			table[i] = ea.addRect(x*width, actualHeight, width, height);
			space = height;
		}
		
		i++; 
	}
}
tableGroup = ea.addToGroup(table);
ea.setView("active");
ea.addElementsToView();

```

Damit lassen sich dann z. B. solche Tabellen generieren (die Einfärbung und die Überschriften habe ich manuell hinzugefügt):
![Pasted image 20230520114033.png](/img/user/Digitalisierung/Anh%C3%A4nge/Pasted%20image%2020230520114033.png)

**Video:**
Der einfachste Weg, ein Video in den Unterricht einzubinden, besteht darin, den Link zum YouTube-Video in eine Notiz einzufügen - die URL wird als Link erkannt und mit einem Klick darauf kann das Video dann direkt im Browser geöffnet und abgespielt werden. Es gibt auch die Möglichkeit, das Video herunterzuladen und direkt im Vault zu speichern (das verbieten allerdings die terms of service von YouTube) - Obsidian bringt einen Viewer mit, um Videos in gängigen Formaten direkt abzuspielen. Alternativ gibt es auch ein Plugin, das Links zu Youtube-Videos in Markdown-Notizen als Vorschau anzeigt und es erlaubt, die Videos eingebettet direkt abzuspielen (**Simple Embeds**). 
Da ich diese Funktion aber schon bei OneNote nicht genutzt habe, begnüge ich mich mit einem einfachen Link in der Excalidraw-Notiz, um das Video direkt abspielen zu können. So bekommen meine Schüler:innen auch direkt den Link , wenn sie das Video später noch einmal nachsehen möchten.

**kollaboratives Notieren auf einem gemeinsamen Notizblock:**
Hierfür nutze ich die [Website-Version von Excalidraw](https://excalidraw.com), also nicht das Excalidraw-Plugin in Obsidian, denn hier steht eine sehr gut funktionierende Kollaborationsmöglichkeit bereit (die, nebenbei bemerkt, besser funktioniert und weniger Synchronisationsfehler produziert als der "Platz für Zusammenarbeit" von OneNote) - ich erstelle dafür direkt auf der Website (s. Link oben) meine Vorbereitung für die Reflexionsabfrage und generiere dann den Link zur Kollaboration:
![Pasted image 20230520110505.png](/img/user/Digitalisierung/Anh%C3%A4nge/Pasted%20image%2020230520110505.png)
Diesen Link stelle ich meinen Schüler:innen dann als QR-Code (auf einer Excalidraw-Notizseite in Obsidian) und zusätzlich als URL über unsere Kommunikationsplattform zur Verfügung. Alle können nun parallel an der Oberfläche arbeiten und es wird sogar angezeigt, wer gerade wo arbeitet.
Sobald die Bearbeitung abgeschlossen ist - hier also alle Schüler:innen ihre Fragen notiert haben - wähle ich links oben im Menü auf der Excalidraw-Seite "Speichern als ...":
![Pasted image 20230520111643.png](/img/user/Digitalisierung/Anh%C3%A4nge/Pasted%20image%2020230520111643.png)
Dort speichere ich die Datei im Format .excalidraw direkt in meinen Vault-Ordner und kann die Datei dann innerhalb von Obsidian öffnen und ggf. weiter bearbeiten - ohne, dass die Schüler:innen noch Schreibzugriff auf diese Datei hätten:
![Pasted image 20230520112232.png](/img/user/Digitalisierung/Anh%C3%A4nge/Pasted%20image%2020230520112232.png)

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
- Notion-like Tables
	- Erlaubt es, Tabellen im Stil von [Notion](https://www.notion.so/de-de) in Obsidian anzulegen. Der Vorteil ist, dass die Tabellen einfacher anzulegen und zu warten sind als Markdown-Tabellen - zusätzlich zu den Tabellen, die MAKE.md schon mitbringt, lassen sich hier zudem zu einzelnen Spalten Berechnungen anstellen, z. B. um eine Summe aller Werte dieser Spalte zu bilden usw. 
- Ozan's Image in Editor Plugin
	- Unverzichtbar für das komfortable Anzeigen von Bildern in Notizen, die dann auch herangezoomt usw. werden können. 

## Schritt 5: Privacy by design - auch bei der Synchronisation
Hier sollen, abschließend, noch zwei Punkte erwähnt werden, die zeigen, inwiefern mein Setup - hauptsächlich bedingt durch die Datenverarbeitung in den von mir ausgewählten Anwendungen - die Anforderung "privacy by design" erfüllt.

### Der Vault ist ein Ordner auf der eigenen Festplatte - nicht mehr und nicht weniger
Die wichtigste Komponente zur Einhaltung des Prinzips privacy by design besteht darin, dass der Vault, in dem Obsidian alle Dateien, Einstellungen, Plugins und Scripte verwaltet einfach ein Ordner auf meiner Festplatte ist - nicht mehr und nicht weniger. Ob ich diesen Ordner nun zwischen mehreren Geräten synchronisieren möchte oder nicht, ob ich ihn in einem verschlüsselten Container unterbringe (z. B. mittel TrueCrypt) oder ihn in einem Cloud-Speicher hochlade, liegt ganz bei mir. Der Ordner selbst und die Daten darin verlassen jedenfalls nur dann meine Festplatte, wenn ich dies explizit organisiere (Obsidian bietet z. B. einen eigenen kostenpflichtigen Synkronisationsdienst namens Obsidian Sync an - hierfür ist dann auch ein Account erforderlich. Die Nutzung ist aber vollständig optional, man wird nicht einmal durch "Werbemaßnahmen" in der App darauf hingewiesen.). Ein weiterer Vorteil ergibt sich daraus, dass Notizen, andere Dateien, Plugins, Einstellungen und Scripte alle gemeinsam in einem Vault gespeichert werden: Ich kann sehr leicht Backups meiner kompletten Arbeitsumgebung machen und meinen gesamten Workflow ohne erneute Konfiguration auf andere Geräte übertragen, einfach, indem ich den Vault-Ordner auf ein anderes Gerät kopiere und dort mit Obsidian öffne.

### SyncThing: Direkte Synchronisation von Gerät zu Gerät, ohne Cloud-Anbindung - open source und Verschlüsselung inklusive
SyncThing ist eine quelloffene Software, die darauf spezialisiert ist, Ordner auf verschiedenen Geräten synchron zu halten - ohne Zwischenspeicher, voll verschlüsselt und mit vollständiger Kontrolle über meine Daten. SyncThing wäre ein eigenes Thema, hier sei nur so viel gesagt: Durch diese Art, meine Daten zu synchronisieren verlässt mein Vault niemals meine Einflusssphäre, z. B. zu einem Cloud- oder anderen Speicheranbieter. Die Daten werden zwar über das Internet übertragen, jedoch End-zu-End-verschlüsselt und ausschließlich mit Speicherorten auf meinen eigenen Geräten. Weitere Informationen finden sich direkt auf der [Projekt-Website von SyncThing](https://syncthing.net/).
Und hier noch die Anleitung, mit der ich Syncthing erfolgreich für meinen Obsidian-Vault eingerichtet habe: [How To Sync Obsidian Notes Across Different Devices For Free](https://beingpax.medium.com/how-to-sync-obsidian-notes-across-different-devices-for-free-326423218597)
