Kriterien für "gute" Forschungssoftware

**Autor*innen**

* Dr. Anne Klammt
* Sophie Charlotte Schmidt M.A.
* Martina Trognitz M.A.
* Timo Homburg M.Sc.
* Clemens Schmid M.A.
* Dipl-Inf. Lutz Schubert
* Florian Thiery M.Sc.

# Quasi-Präambel

## Zielsetzung unseres Beitrags

Die Beurteilung einer wissenschaftlichen Publikation ist eine traditionsreiche Form des wissenschaftlichen Diskurs. Entsprechend gibt es ein allgemeines Grundverständnis darüber, was eine gute Rezension ausmacht. Unterstützt werden kann dies durch redaktionelle Maßnahmen zur Qualitätssicherung wie Hinweise für die/den Rezensentin/Rezensenten oder - wie es die DGUF mit den `Archäologischen Informationen` praktiziert - eines Reviews der Rezension. Die Frage ist jedoch, was sollte eine gute Rezension von Software für den Einsatz in der Archäologie ausmachen? Geht es dabei allein um Aspekte der Nutzbarkeit, der Usability? Sollten nicht auch Fragen der Nachhaltigkeit und der Anschlussfähigkeit von Software und Quellcode einfließen? Müsste nicht auch betrachtet werden, ob es eine wissenschaftliche Dokumentation und Diskussion der rechnerischen Verfahren gibt - etwa bei den vielen Interpolationen von Daten mit Raumbezug, die modernen GIS-Softwarepakete bieten?

Aufgeworfen und anschließend im Plenum der CAA 2019 in Wilhelmshaven wurde die Frage nach den Inhalten und Kriterien einer Rezension von Software und Anwendungen für die Archäologie von Sophie Charlotte Schmidt, Kai-Christian Bruhn und Frank Siegmund. Anlässlich der Einrichtung der neuen Rubrik für solche Besprechungen in der vorliegenden Reihe haben wir das Thema aufgegriffen und möchten mit dem vorliegenden Leitfaden einen Beitrag zur Weiterentwicklung dieses wichtigen Themas leisten. Der Leitfaden kann auch zur Orientierung bei der Entscheidung Software in der eigenen Forschung und in der eigenen Institution einzusetzen, dienen.

## Wer sind wir, was bringen wir mit?
- drei Chinesen mit einem Kontrabass
Hier würde ich es gut finden, wenn deutlich wird, warum es wichtig und richtig ist, dass sich jene dieses Themas annehmen, die:
- genau die sind, deren "Werke" rezensiert werden sollen, und die durchaus ein Anrecht darauf haben, dass man ihre Arbeit nach transparenten Kriterien beurteilt
- sich für Nachhaltigkeit und Wissenschaftlichkeit von Forschungssoftware einsetzen
- die als seltsame fachliche Zwitter regelhaft mit den Folgen unsachgemäßer Entscheidungen für Softwarelösungen zu tun haben
- die sich als Archäologin um eine angemessene Auswahl ihrer Werkzeuge bemühen

# Beschreibung der Software und ihrer Komponenten

_Clemens: Erster Schritt einer Rezension muss ja die kurze Beschreibung des Gegenstands sein. Ich denke, das muss in diesem Leitfaden damit auch thematisiert werden - über die unten bereits zusammengetragene Vielfalt an Beurteilungskriterien hinaus._

- __Wofür kann ich diese Software verwenden?__ Welches Problem versucht die Software zu lösen und welche generellen Anwendungszenarien hatten die Entwickler vor Augen?
- __Wie löst die Software das gegebene Problem?__ Wie ist die grundsätzliche Funktionsweise konzipiert? Was sind die wesentlichen Bestandteile in Frontend und Backend (z.B. WebApp + Datenbank, CLI + Neuronales Netz, ...)? Wie funktioniert der (wissenschaftliche) Algorithmus, der mit der Software implementiert wurde (natürlich in kurzen Worten: Punktmuster gehen hinein, Magie passiert, Kennwerte kommen heraus)?
- __Wo finde ich mehr Informationen zu dieser Software?__ Hyperlinks und Referenzen.

_Clemens: Ein Gliederungsversuch, um die breite Gedankenwelt unten zu strukturieren:_

- _# Beurteilung von Software und Diensten in der Archäologie_
- _## Bedienbarkeit (Nutzerperspektive)_
- _### System, Umgebung und Installation_
- _### Interface_
- _### Ressourcenbedarf_
- _### Zugänglichkeit, Hilfefunktionen und Community_
- _## Technik (Entwicklerperspektive)_
- _### Art und Qualität der Implementierung_
- _### Anschluss- und Erweiterungsfähigkeit_
- _## Rechtliche Fragen_
- _### Datenschutz, Privacy, Datensparsamkeit_
- _### Lizenzierung_

# Beurteilung von Software und Diensten in der Archäologie

## Usability

Unter Usability und UX Design werden oftmals insbesondere Fragen der Gestaltung und Bedienbarkeit grafischer Oberflächen von Programmen (GUI) und Webseiten verstanden. Hier geht es dann um die Benutzbarkeit mit verschiedenen Endgeräten (Responsivität), die Strukturierung von Informationen über Unterseiten hinweg, die Verständlichkeit von Texten und auch die Barrierefreiheit (Farbkontraste, Screenreader u.ä.). Usability umfasst aber noch mehr und schließt alle Aspekte ein, die eine fehlerfreie und effiziente Nutzung durch die Forscherin, den Forscher ermöglichen.

Für Forschungssoftware ist es z.B. besonders wichtig, dass die Eingabe von Daten sich an der Eingabepraxis orientiert; wenn etwa die händische Eingabe von Werten sehr typisch ist, dann ist es Aufgabe einer guten Benutzbarkeit, diesen Vorgang mit vorgegebenen Feldformaten, automatischem Speichern, gut sichtbaren Feldern oder ähnlichem zu unterstützen. Ebenso muss Software mit der Teams mit verschiedenen Kompetenzen an einem Datenbestand arbeiten, ein Rechtemanagement vorsehen, das die unterschiedlichen Verantwortlichkeiten abbilden kann. Weil die Benutzbarkeit sich eng an den Nutzer\*innen orientiert, also von ihren Skills, ihren Aufgaben und Gewohnheiten ausgehend erfahren wird, kann sie dahingehend betrachtet werden. Die Gewichtung der Punkte und auch die Ausführlichkeit mit der sie behandelt werden, hängt wieder vom Anwendungsfall ab.

### Merkmale der Benutzbarkeit
<!--hier als erster Anfang von Wikipedia ISO/IEC 9126 ausgegangen, und versucht auszuformulieren -->
#### 1. "Bedienbarkeit: Aufwand für den Benutzer, die Anwendung zu bedienen."
- Eine wesentliche Hürde für die Nutzung von Software stellt ihre __Auffindbarkeit und die Installation__ dar. Je nach Nutzgruppe kann bereits der Download eines Softwarepakets von git Distributionen (Github, Gitlab, ...) oder ähnlichen Portalen ein großes Problem darstellen. In vielen Instituten und Einrichtungen kann Software zudem nicht von den Nutzerinnen selbst installiert werden.
- Für Webanwendungen bedeutet es eine Einschränkung der Bedienbarkeit, wenn die App nicht für die Nutzung in allen gängigen Browsern ausgerichtet ist. Eine Übersicht der gängigen Browser kann z.B. _wo nachgesehen werden?_
- Wie wird das Tool gestartet/geöffnet? Ist ein wiederholter Login nötig, unterbricht dies die Arbeit störend? Wenn ja, ist dies gerechtfertigt durch bestimmte Abhängigkeiten?
- Ein weiterer Aspekt ist der __Ressourcenbedarf im Betrieb__. Ist beispielsweise der parallele Betrieb mit weiteren Anwendungen auf einem für den Aufgabenbereich typischen Rechner möglich oder werden Prozesse übermäßig verlangsamt, die Anwendung stürzt gar ab? Ist dieser Punkt von Bedeutung bei der üblichen Verwendung der Software?
- Benötigt die Nutzerin, der Nutzer weitere Programme oder muss bestimmte Einstellungen am eigenen System vornehmen, um das Tool zu nutzen? Wenn ja, steht dies in einem angemessenen Verhältnis zur Funktion?
- In welchen __Sprachen__ werden die __Nutzeroberflächen__  angeboten und ist dies angemessen für das Forschungsumfeld? Ein Programm, das nur in Deutsch beschrieben wird, kann in einem internationalen Forschungsteam Probleme aufwerfen. Ein Tool, das stark auf Bedarfe der Archäologie bestimmter Regionen ausgerichtet ist, sollte ggf. die Verkehrssprachen des Arbeitsgebiets berücksichtigen.

#### 2. "Erlernbarkeit: Aufwand für den Benutzer, die Anwendung zu erlernen (zum Beispiel Bedienung, Ein-, Ausgabe)"

- Die  __Erlernbarkeit__ steht  in einem Spannungsfeld zum Umfang und der Komplexität der Aufgaben, die  mit der Software bearbeitet werden sollen. Die Beurteilung muss also einbeziehen, ob die Lernkurve in einem angemessenen Verhältnis zu dem steht, was die Software bietet. Zugleich ist zu betrachten, ob es Alternativen gibt, mit denen ein Großteil der Bedarfe gedeckt werden können.
- __Die Ein- und Ausgabe von Daten__ wird hinsichtlich der Formate unter Punkt "Open/Transparenz" erneut aufgegriffen. An dieser Stelle geht es um die Effizienz. Bei händischen Eingaben ist zu beurteilen, ob eine fehlerfreie Eingabe durch vorgegebene Feldformate, Fehlermeldungen und Hilfetexten zur Eingabe direkt neben den Eingabefeldern unterstützt wird. Bei der Eingabe über Importe ist zu betrachten, ob eine Auswahl von Formaten möglich ist, wie viele Daten in einem Durchgang importiert werden können und ob ihre Konformität vor dem Ingest geprüft wird, sowie schließlich wie performant (schnell und fehlerfrei) das System beim Import arbeitet. In ähnlicher Weise ist auch für die Ausgabe zu beurteilen, ob das Angebot an Datenformaten für das Arbeitsgebiet passend ist, und wie performant der Export ist. Natürlich ist auch hier stets die Relation zwischen dem Anspruch des Tools und dem Aufgabenfeld zu betrachten. Werden Datenformate oder auch Schnittstellen bei der Ein-und Ausgabe gut begründet vermisst, kann dies ein Feedback sein, um die Entwicklung des Tools voranzutreiben.
- __Tutorials, FAQs und Hilfefunktionen__ sind ein weiterer wichtiger Aspekt. Hier sollte überprüft werden, ob die Tutorials auf unterschiedliches Vorwissen eingehen und gegebenenfalls auch kenntlich machen, welches Grundwissen, welche Erfahrungen unabdingbar sind. Ein weiterer Aspekt bei den Anleitungen, Tutorials und FAQs ist die Frage der Sprachen.
- __Community__ Die Zahl der aktiven Nutzer eines Softwarewerkzeugs ist entscheidend dafür, ob man im Falle von Problemen schnell Hilfe googeln kann. Ist das Werkzeug das Erzeugnis eines einzigen Labors und wird von einer Hand voll eingeschworener Kollegen genutzt, oder handelt es sich um eine global etablierte Software mit Nutzerforum, Mailingliste und ganzen Büchern zur Nutzung in bestimmten Kontexten? Selbst wenn ein Werkzeug nur eine kleine Community besitzt kann dieser Mangel doch bis zu einem gewissen Grad von aktiven und leicht erreichbaren Entwicklern ausgeglichen werden, die bereit sind konkrete Fragen schnell und unkompliziert zu beantworten.

#### 3. "Konformität: Grad, in dem die Software Normen oder Vereinbarungen zur Benutzbarkeit erfüllt."
_Anne: bei diesem Punkt bin ich mir nicht sicher und würde ihn auslassen_
_Sophie: dito. Mir fallen auch gerade keine Normen zur Benutzbarkeit in der Arch ein_

#### 4. "Verständlichkeit: Aufwand für den Benutzer, das Konzept und die Anwendung zu verstehen"

_Anne: hier finde ich es sehr schwierig das vom Problem, verstehen Archäologen, was sie eigentlich mit dem Tool tun, zu trennen. Ich finde z.B. im Grunde alle statistischen Anwendungen sehr kompliziert, weil ich erstmal total anders denke _

_Flo: gerade deshalb muss das hier aufgeführt werden, ist meines Erchtens ein guter und wichtiger Punkt_

_Sophie: Ich verstehe, dass die Trennung schwierig ist, würde Flo aber zustimmen. Beim Statistik-Bsp: Die Theorie hinter der Statistik muss außerhalb des Programms verstanden werden, in R muss ich das Paket und die Funktion in dem Paket verstehen, das die statistische Berechnung umsetzt. Also, wo sind welche Input-Parameter einzusetzen, welches Dateiformat kann ich benutzen etc pp. Das kann gut und intuitiv umgesetzt sein oder auch nicht._

## Bedeutung in der Archäologie

## Anschlussfähigkeit
- Input- / Outputformate
- offene Datenformate / proprietäre Datenformate / zukunftsfähige Datenformate (Wichtigkeit, Grad der Verbreitung, Nutzung)
- Können andere Forschungscommunities durch den Export spezifischer Datenformate profitieren? (z.B. RDF für Linked Data, GeoJSON für GIS community, TEI für Texte etc.)
Kriterien für "gute" Forschungssoftware
- hier wenn möglich Bezug auf bekannte archäologische Services, Ianus-Empfehlungen oder ADS. Damit hat mancher Archäologe vllt schonmal Kontakt gehabt, was das Verständnis erleichert
- Ist die Anwendung sowohl für den Menschen als auch maschinenlesbar nutzbar/Gibt es Programmierschnittstellen (APIs) oder Webservices?
- Hält sich die Anwendung an Standards welche im jeweiligen Kontext vorgegeben werden (z.B. W3C Standards zur Annotation oder auch archäologische Standards) und bildet diese standardkonform in den Daten ab?

## Lizenzen

- Unterschied Copyright und Copyleft Lizenzen
- Welche Lizenz gestattet welche gängigen Anwendungen in der Archäologie? Problem von Creative Commons `non commercial`
- Sind die Ressourcen, die mit der Software mitgeliefert werden unter einer freien Datenlizenz verfügbar?
- Erlaubt die Software nur die Erstellung von Daten, die unter einer gewissen Lizenz zur Verfügung gestellt werden können?
- Behält sich die Software Rechte an den von ihr erstellten Daten vor?

## Datenschutz, Privacy, Datensparsamkeit

- Welche Daten speichert die Anwendung zu welchem Zweck wie lange? Dienen diese Daten der Forschung bzw. helfen sie die Software zu verbessern?
- Ist die Software ohne Login anonym bedienbar?
- Benötigt die Software eine Internetverbindung und werden personenbezogene Daten an Dritte übertragen?

## Software

Siehe auch: https://de.wikipedia.org/wiki/Softwarequalität#/media/Datei:ISO_9126_Grafik.png

- Lauffähigkeit auf welchen Betriebssystemen? (mehr sind besser)
- Auf welchen Endgeräten? (Mobil, Desktop, Web)
- Installation oder Portable?
- Mit welchen Hardwareanforderungen?
- Ist der Buildprozess dokumentiert und ggf. mittels Buildingscripts automatisiert?
- Internationalisierung/Lokalisierung - Ist die Software in mehreren Sprachen verfügbar oder kann sie einfach so erweitert werden? Beachtet sie ggf. lokale Anpassungen (andere Einheiten, andere Gepflogenheiten der Forscher in Land XYZ etc.)
- Beachtet die Software die lokalen Gesetze in dem Land in dem sie eingesetzt werden soll? (Datenschutz, Kartendarstellungen etc.)
- Läuft die Software auf einer Infrastruktur die mir selbst nicht gehört und die ggf. in Zukunft abgeschaltet werden könnte?
- Ist die Software frei/Open Source?
- Wie ist das Laufzeitverhalten? (Braucht die Software unnötig lange im Vergleich zu anderen Vergleichbaren Programmen?)
- Wie stabil ist die Software?
- Wie ist die Software publiziert und verfügbar (Download, git) und ist sie zitierbar (Zenodo, [CCF](https://citation-file-format.github.io))
- Welche Software gibt es noch / was sind Vorteile dieser hier?
- Robustheit: Wie geht die Software mit Abstürzen/Stromausfall usw. um? Wird die Arbeit regelmäßig zwischengespeichert?
- Gibt die Software plausible Fehlermeldungen aus? Gibt es einen Log um Fehler nachvollziehen zu können?

## Community

- Wird die Software von einer ausreichend großen Community getragen?
- Wird die Software regelmäßig mit Updates versorgt?
- Sind die Entwickler der Software gut ansprechbar oder gar persönlich bekannt?
- Hat die Software eine ausreichend große Anwenderbasis und ggf. eine Communityhilfe?
- Gibt es ausreichend Tutorials für das Erlernen der Software?

## Archäologische Community

- Gibt es bereits eine archäologische Community für diese Software? (SIG, ...)
- Sind Best Practices für diese Software für die Community verfügbar?
- Gibt es Archäologie-relevante erfolgreiche Projekte/Anwendungen, die von dieser Software bereits unterstützt wurden?

## Dokumentation und Tests

- Ist eine Quellcodedokumentation vorhanden und ggf. eine HTML Variante davon verfügbar?
- Gibt es eine Entwicklerdokumentation, sodass die Software leichter verstanden werden und ggf. erweitert werden kann?
- Ist die Dokumentation aktuell, wird gepflegt und deckt alle Funktionen des Programms ab?
- Hat der Quellcode Tests die die Kernfunktionen des Programms testen und diese für andere Entwickler aufzeigen?
- Sind verwendete Algorithmen dokumentiert und hinreichend wissenschaftlich belegt?

## Attraktivität

- Wird es dem Benutzer einfach gemacht die Software zu testen? Gibt es eine VM, einen Dockercontainer, einen Installer, andere Formen der Installierbarkeit ohne viel vorheriges Fachwissen?
- Gibt es Anwendungsbeispiele der Software, ggf. Beispieldatensets und eine Anleitung für diese um ein Verständnis für die Funktionsweise zu entwickeln?

## Barrierefreiheit

- Ist die Anwendung behindertengerecht bedienbar? 
- Stützt sich die Anwendung auf Standards zur Barrierefreiheit wie z.B. BITV2? http://www.gesetze-im-internet.de/bitv_2_0/BJNR184300011.html

## Sicherheit

- Ist die Anwendung auf Sicherheitsanforderungen getestet worden? (Penetrationtests usw.), also ist sie leicht hackbar oder nicht?
- Setzt die Anwendung Standards zur IT Sicherheit welche von Behörden oder internationalen Organisationen empfohlen werden um? Beispiel OWASP: https://de.wikipedia.org/wiki/Open_Web_Application_Security_Project
- Hat die Anwendung Abhängigkeiten zu Softwarekomponenten welche bekannte Sicherheitslücken aufweisen und nicht mehr gepflegt werden? Hält dieser Zustand auf absehbare Zeit an?
