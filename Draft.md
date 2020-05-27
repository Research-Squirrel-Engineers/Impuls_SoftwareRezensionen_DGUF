# Leitfaden Rezension von Forschungssoftware - Kriterien für "gute" Forschungssoftware

<<<<<<< HEAD
=======
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
>>>>>>> e7eb03be86fae990727c26ecc562a8cb9d8805d6

### Zielsetzung unseres Beitrags

Die Beurteilung einer wissenschaftlichen Publikation ist eine traditonsreiche Form des wissenschaftlichen Diskurs. Entsprechend gibt es ein allgemeines Grundverständnis darüber, was eine gute Rezension ausmacht. Unterstützt werden kann dies durch redaktionelle Maßnahmen zur Qualitätssicherung wie Hinweise für die/den Rezensentin/Rezensenten oder - wie es die DGUF mit den Archäologischen Informationen praktiziert - eines Reviews der Rezension. Die Frage war jedoch, was sollte eine gute Rezension von Software für den Einsatz in der Archäologie ausmachen? Geht es dabei allein um Aspekte der Nutzbarkeit, der Usability? Sollten nicht auch Fragen der Nachhaltigkeit und der Anschlussfähigkeit einfließen? Müsste nicht auch betrachtet werden, ob es eine wissenschaftliche Dokumentation und Diskussion der rechnerischen Verfahren gibt - etwa bei den vielen Interpolationen von Daten mit Raumbezug, die moderne GIS-Softwarepakete bieten? 

Aufgeworfen und anschließend im Plenum der CAA 2019 in Wilhelmshaven wurde die Frage nach den Inhalten einer Rezension von Software und Anwendungen für die Archäologie von Sophie C. Schmidt, Kai-Christian Bruhn und Siegmund Freud. Anlässlich der Einrichtung der neuen Rubrik für solche Besprechungen in der vorliegenden Reihe haben wir das Thema aufgegriffen und möchten mit dem vorliegenden Leitfaden einen Beitrag zur Weiterentwicklung dieses wichtigen Themas leisten. Der Leitfaden kann auch zur Orientierung bei Entscheidungen zum Einsatz einer Software in der eigenen Forschung dienen.

### Forschungsgegenstand und Forschungsstand

Unter Forschungssoftware verstehen wir Software, die mit einem spezifischen Fokus auf ihren Einsatz in der Forschung entwickelt wurde, um Forschungsdaten zu erzeugen, zu verarbeiten oder zu analysieren (hettrick_2014_14809). Dies betrifft etwa Programme zur Kalibrierung und Umrechnung von Messwerten, der Annotation von Texten und Objekten der Bereitstellung sowie zur Verknüpfung und Visualisierung fachlich relevanter Vokabulare. Forschungssoftware kann auf einen sehr spezifischen Bedarf gerichtet sein oder bietet generische Lösungen an. Sie ist dabei stets Teil der Forschungsprozess, der in allen seinen Punkten nachvollziehbar und soweit möglich reproduzierbar sein muss. Daraus ergeben sich Anforderungen an die Forschungssoftware, die in vielen Punkten denen entsprechen, die an Forschungsdaten gerichtet werden. Wie Forschungsdaten soll -software den FAIR-Prinzipien entsprechen: - auffindbar, zugänglich, interoperabel und reproduzierbar. Die Ableitung von Maßnahmen, die auf Software Anwendung findet, umfasst:

- den Nachweis von Forschungssoftware in Repositorien
- die Zitierbarkeit von Software
- die eindeutige Autorenschaft
- die Offenlegung des Quellcodes
- die Anwendung von Standards

Die Offenlegung des Quellcodes ist dabei bereits eine für Forschungssoftware spezifische Ableitung, die keine Gültigkeit für Forschungsdaten hat, weil Forschungsdaten andere Informationen beinhalten (lamprecht_towards_2019, 3 f.). Die Forderung nach der Offenlegung des QuellCodes (Opensource) wird dabei vielfach noch erweitert um die Forderung, den Code zudem frei nutzbar zur Verfügung zumstellen FreeSource), wird seit vielen Jahren als FOSS bezeichnet und wird in Deutschland insbesondere von Wissenschaftler\*innen und Entwickler\*innen aus der Geoinformatik vertreten (FOSSGIS e.V.).  

Auch in anderen Punkten muss die Umsetzung auf das Bezug nehmen, was für Software spezifisch ist. Einen sehr konkreten Vorschlag dafür hat 2019 eine Gruppe von Research-Software-Entwickler\*innen aus der Bioinformatik vorgelegt (lamprecht_towards_2019). Mit Blick auf die Umsetzbarkeit zur Auffindbarkeit fallen hier unter anderem Softwarerepositorien als Infrastruktur auf, die eigene Funktionen und Formen der Trägerschaften kennt. Kommerzielle Anbieter, community-basierte Infrastrukturen und viele weitere Formen haben sich als eigene Systeme entwickelt, die nicht genuin aus der Forschung kommen. Ähnlich wie die kommerziellen Anbieter von Cloud-Diensten zum Austausch von Dokumenten geben sie aber starke Impulse für die Entwicklung der wissenschaftlichen Infrastrukturen. Gerade für die Auffindbarkeit ist aber aus den Vorschlägen der Gruppe die Bedeutung der fachwissenschaftlichen Einbindung und der klassischen Arbeit der Forschungsinfrastrukturen, nämlich Aufbau, Pflege und Anwendung von kontrolliertem Vokabular und Metadatenstandards abzulesen. 

Einer eigenen Ausformulierung für Software bedarf auch die Frage der Interoperabilität. So kann Interoperabilität verstanden werden als Abfolge von Prozessen die bei der Erzeugung, Bearbeitung oder Analyse nacheinander aufgerufen werden. Sie kann aber auch als Interoperabilität der verschiedenen Schichten die miteinander korrespondieren müssen, um das Programm auszuführen verstanden werden (lamprecht_towards_2019, 10 f.). Forschungssoftware, die nur mit einem Betriebssystem funktioniert ist weniger interoperabel, als solche, die plattformunabhängig programmiert ist. Die Interoperabilität in einem Ablauf von Prozessen erfordert nicht, dass alle Prozessschritte mit der Software abgebildet werden, sondern dass sie über Protokolle, Schnittstellen und Ausgabeformate den Durchlauf ermöglichen.

Einen wichtigen Punkt bildet die eindeutige Autorenschaft. Erst mit ihr kann die wissenschaftliche Leistung mit der Person verbunden werden. Eine Voraussetzung, um akademische Karrierewege zu eröffnen, in denen bislang Qualität und Anzahl klassischer Publikationen sind, zukünftig aber auch Datenpublikationen, Annotationen und die Softwareentwicklung Kriterien der Beurteilung sein sollen (s. NFDI4Culture, RSE4NFDI). Die eindeutige Zuweisung und die Sichtbarmachung der Autorenschaft wird aber zudem auch in der kritischen Auseinandersetzung mit dem Bias von Software eingefordert (LIT). Autorenschaft von Software unterscheidet sich jedoch von dem, was in der Publikation von Aufsätzen und Büchern gewohnt ist. Die Entwicklung von Software beinhaltet heute ganz wesentlich die neue Verknüpfung und Ergänzung vorhandener Module, entsprechend muss auch das Verständnis von Autorenschaft und wie sie sich auch über die Lebenszeit der Software hinaus dokumentieren lässt spezifisch für Software erfolgen (katz_software_2016). 

* Einen eigenen und für die Archäologien typischer Bereich ist Software von spezifischen Geräten etwa zur Vermessung, fotografischen Dokumentation, Analyse von Oberflächen und Inhaltsstoffen. Sehr oft findet sich hier proprietäre Software, die mit der Hardware vertrieben wird. Diese Software wird zwar in der Forschung eingesetzt, aber ihre Programmierung ist nicht transparent. Entsprechend können zwar der Umgang mit der Software und die Produktqualität aus Sicht der Nutzerinnen als Erfahrungswerte beschrieben werden, aber es können keine begründeten Aussagen zur Performanz unter veränderten Bedingungen, zur Stabilität und anderes getroffen werden. Einige der im folgenden dargestellten Kriterien zur Rezension von Forschungssoftware können auf proprietäre Software angewendet werden und eine Berücksichtigung der Aspekte wird ausdrücklich empfohlen.

<--! Die wissenschaftliche Beschäftigung mit der Software // Baustelle -->

* Forschungssoftware als Bestandteil der Forschungspraxis gerät erst langsam in das Fokus der Geistes- und Kulturwissenschaften. Entsprechend mangelt es nicht nur an Standards und Best Practices, sondern vielfach ist auch das Bewusstsein für die Verflechtung von Software und der Entwicklung der Forschungsfrage kaum vorhanden. Fragen der Nachhaltigkeit, der Transparenz und der Reproduzierbarkeit von Software werden erst langsam in ihrer Relevanz von der Fachwissenschaft erkannt und als Aufgaben an die Forschungsinfrastrukturen herangetragen [z.B. NFDI4Culture Compendium 2019]. Daneben hat sich in den Digital Humanities und den Fachinformatiken (Archäoinformatik, Computerlinguistik, Geoinformatik) bereits seit längerem die Beschäftigung mit Forschungssoftware unter den Aspekten der Performanz, der Transparenz, der Anpassbarkeit an Forschungsfragen und auch der Auswirkung auf die Forschungspraxis entwickelt. 

* Beispielhaft für die Archäologie zu nennen sind hier etwa die Arbeiten von Irmela Herzog (2012, 2014). Im Mittelpunkt standen dabei die Potenziale für die Untersuchung der archäologischen Fragestellung. Aspekte der Nutzbarkeit, der Qualität des Quellcodes und der Anschlussfähigkeit spielten eine sehr geringe Rolle. 



### Autorenteam
<--! Das gefällt mir noch nicht, aber ich finde wichtig, abzubilden, was wir für Kompetenzen und Erfahrungen einbringen>

Der vorliegende Leitfaden wurde von einer AdHoc gebildeten Interessensgruppe verfasst. Sie setzt sich zusammen aus Archäolog\*innen und Informatiker\*innen, die ganz oder teilweise im Researchsoftware-Engeneering tätig sind, Archäolog\*innen mit einem Schwerpunkt in der Anwendung digitaler Methoden in ihrer archäologischen Arbeit und in der Forschungsberatung tätigen Archäolog\*innen. Die archäologischen Themenfelder umfassen Landschaftsarchäologie, BITTE ERGÄNZEN. Die Verfasserinnen sind Mitarbeiter\*innen von Hochschulen, außeruniversitären Forschungseinrichtungen und Fachbehörden.


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

<<<<<<< HEAD

## Bibliographie

@article{Herzog_2012,
 author = {Herzog, Irmela},
 title = {Aus Punkten werden Flächen: Vorschlag einer Methodik zur
Abgrenzung von Gebieten mit hoher Fundpunktdichte},
 journal = {Bericht der Römisch-Germanischen Kommission},
 year = {2012},
 volume = {91},
 pages = {197-215},
 note = {IMD-Felder maschinell generiert (GBV)},
}

@inbook{Herzog_2014,
 author = {Herzog, Irmela},
 title = {Testing models for medieval settlement location},
 pages = {351-358},
 year = {2014},
 note = {Literaturverz. S. 358},
 note = {IMD-Felder maschinell generiert (GBV)},
 booktitle = {Data analysis, machine learning and knowledge discovery},
}

@mastersthesis{Seidig2017Usability-Test,
author = {Seidig, Marianne},
title = {Usability-Test virtueller Forschungsumgebungen für die Geisteswissenschaften am Beispiel von Meta-Image},
school = {Humboldt-Universität zu Berlin, null},
year = {2017},
doi = {http://dx.doi.org/10.18452/2154}
}

@mastersthesis{Klein2012Virtuelle,
author = {Klein, Julia Elisabeth},
title = {Virtuelle Forschungsumgebungen als Entwicklungsfeld für Bibliotheken am Beispiel des "Deutschen Textarchivs"},
school = {Humboldt-Universität zu Berlin, Philosophische Fakultät I},
year = {2012},
doi = {http://dx.doi.org/10.18452/14175}
}

@dataset{hettrick_2014_14809,
  author       = {Hettrick, Simon and
                  Antonioletti, Mario and
                  Carr, Les and
                  Chue Hong, Neil and
                  Crouch, Stephen and
                  De Roure, David and
                  Emsley, Iain and
                  Goble, Carole and
                  Hay, Alexander and
                  Inupakutika, Devasena and
                  Jackson, Mike and
                  Nenadic, Aleksandra and
                  Parkinson, Tim and
                  Parsons, Mark I and
                  Pawlik, Aleksandra and
                  Peru, Giacomo and
                  Proeme, Arno and
                  Robinson, John and
                  Sufi, Shoaib},
  title        = {UK Research Software Survey 2014},
  month        = dec,
  year         = 2014,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.14809},
  url          = {https://doi.org/10.5281/zenodo.14809}
}

@article{lamprecht_towards_2019,
	title = {Towards {FAIR} principles for\&nbsp;research\&nbsp;software},
	volume = {Preprint},
	issn = {2451-8484},
	url = {https://content.iospress.com/articles/data-science/ds190026#ref005},
	doi = {10.3233/DS-190026},
	abstract = {The FAIR Guiding Principles, published in 2016, aim to improve the findability, accessibility, interoperability and reusability of digital research objects for both humans and machines. Until now the FAIR principles have been mostly applied to resear},
	language = {en},
	number = {Preprint},
	urldate = {2020-05-27},
	journal = {Data Science},
	author = {Lamprecht, Anna-Lena and Garcia, Leyla and Kuzak, Mateusz and Martinez, Carlos and Arcila, Ricardo and Martin Del Pico, Eva and Dominguez Del Angel, Victoria and van de Sandt, Stephanie and Ison, Jon and Martinez, Paula Andrea and McQuilton, Peter and Valencia, Alfonso and Harrow, Jennifer and Psomopoulos, Fotis and Gelpi, Josep Ll and Chue Hong, Neil and Goble, Carole and Capella-Gutierrez, Salvador},
	month = jan,
	year = {2019},
	note = {Publisher: IOS Press},
	pages = {1--23},
	file = {Full Text PDF:/home/ankl_admin/Zotero/storage/J7DL86N5/Lamprecht et al. - 2019 - Towards FAIR principles for&nbsp\;research&nbsp\;sof.pdf:application/pdf;Snapshot:/home/ankl_admin/Zotero/storage/BYCDA7FL/ds190026.html:text/html}
}

@techreport{katz_software_2016,
	title = {Software vs. data in the context of citation},
	url = {https://peerj.com/preprints/2630},
	abstract = {Software is data, but it is not just data. While "data" in computing and information science can refer to anything that can be processed by a computer, software is a special kind of data that can be a creative, executable tool that operates on data. However, software and data are similar in that they both traditionally have not been cited in publications. This paper discusses the differences between software and data in the context of citation, by providing examples and referring to evidence in the form of citations.},
	language = {en},
	number = {e2630v1},
	urldate = {2020-05-27},
	institution = {PeerJ Inc.},
	author = {Katz, Daniel S. and Niemeyer, Kyle E. and Smith, Arfon M. and Anderson, William L. and Boettiger, Carl and Hinsen, Konrad and Hooft, Rob and Hucka, Michael and Lee, Allen and Löffler, Frank and Pollard, Tom and Rios, Fernando},
	month = dec,
	year = {2016},
	doi = {10.7287/peerj.preprints.2630v1},
	note = {ISSN: 2167-9843},
	file = {Full Text PDF:/home/ankl_admin/Zotero/storage/QVFCDNSX/Katz et al. - 2016 - Software vs. data in the context of citation.pdf:application/pdf;Snapshot:/home/ankl_admin/Zotero/storage/X5CL92ZW/2630v1.html:text/html}
}
=======
- Ist die Anwendung auf Sicherheitsanforderungen getestet worden? (Penetrationtests usw.), also ist sie leicht hackbar oder nicht?
- Setzt die Anwendung Standards zur IT Sicherheit welche von Behörden oder internationalen Organisationen empfohlen werden um? Beispiel OWASP: https://de.wikipedia.org/wiki/Open_Web_Application_Security_Project
- Hat die Anwendung Abhängigkeiten zu Softwarekomponenten welche bekannte Sicherheitslücken aufweisen und nicht mehr gepflegt werden? Hält dieser Zustand auf absehbare Zeit an?
>>>>>>> e7eb03be86fae990727c26ecc562a8cb9d8805d6
