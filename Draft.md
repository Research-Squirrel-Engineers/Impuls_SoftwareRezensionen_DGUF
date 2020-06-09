---
title: Leitfaden Rezension von Forschungssoftware - Kriterien für "gute" Forschungssoftware

author:
  - Dr. Anne Klammt
  - Sophie Charlotte Schmidt M.A. 
  - Martina Trognitz M.A.
  - Timo Homburg M.Sc.
  - Clemens Schmid M.A.
  - Dipl-Inf. Lutz Schubert
  - Florian Thiery M.Sc.

bibliography: literatur.bib
csl: apa-6th-edition.csl

---
# Leitfaden Rezension von Forschungssoftware - Kriterien für "gute" Forschungssoftware

*"Die Leitfunde werden dann im Computer durch die Programme ARCH und GGG einer Seriation unterzogen. Diese Programme entwickelte E. Kämmerer. Eine Beschreibung ist der Arbeit beigefügt. Die Programme DOK und ARCH z. Zt. für 600 Typen in 2000 Funden dimensioniert, sind am Rechner TR 440 beim Großrechenzentrum für die Wissenschaft in Berlin in Anwendung."* [@Kgoldmann_chronologische_1972, 98.]

* Dr. Anne Klammt
* Sophie Charlotte Schmidt M.A. 
* Martina Trognitz M.A.
* Timo Homburg M.Sc.
* Clemens Schmid M.A.
* Dipl-Inf. Lutz Schubert
* Florian Thiery M.Sc.



## Zielsetzung des Beitrags

Die Beurteilung einer wissenschaftlichen Publikation ist eine traditionsreiche Form des wissenschaftlichen Diskurses. Entsprechend gibt es ein allgemeines Grundverständnis darüber, was eine gute Rezension ausmacht. Unterstützt werden kann dies durch redaktionelle Maßnahmen zur Qualitätssicherung wie Hinweise für die/den Rezensentin/Rezensenten oder - wie es die DGUF mit den Archäologischen Informationen praktiziert - eines Reviews der Rezension. Die Frage ist jedoch, was sollte eine gute Rezension von Software für den Einsatz in der Archäologie ausmachen? Geht es dabei allein um Aspekte der Nutzbarkeit, der Usability? Sollten nicht auch Fragen der Nachhaltigkeit und der Anschlussfähigkeit einfließen? Müsste nicht auch betrachtet werden, ob es eine wissenschaftliche Dokumentation und Diskussion der rechnerischen Verfahren gibt - etwa bei den vielen Interpolationen von Daten mit Raumbezug, die moderne GIS-Softwarepakete bieten?

>[Fußnote: Aufgeworfen und anschließend im Plenum des 9. Workshops der deutschen Sektion der CAA 2019 in Wilhelmshaven wurde die Frage nach den Inhalten einer Rezension von Software und Anwendungen für die Archäologie von Sophie Charlotte Schmidt, Kai-Christian Bruhn und Siegmund Freud. Anlässlich der Einrichtung der neuen Rubrik für solche Besprechungen in der vorliegenden Reihe haben wir das Thema aufgegriffen und möchten mit dem vorliegenden Leitfaden einen Beitrag zur Weiterentwicklung dieses wichtigen Themas leisten. Der Leitfaden kann auch zur Orientierung bei Entscheidungen zum Einsatz einer Software in der eigenen Forschung dienen.]

## Forschungsgegenstand und Forschungsstand

### Was ist Forschungssoftware?
Unter Forschungssoftware verstehen wir Software, die mit einem spezifischen Fokus auf ihren Einsatz in der Forschung entwickelt wurde, um Forschungsdaten zu erzeugen, zu verarbeiten oder zu analysieren [@hettrick_2014_14809]. Dies betrifft etwa Programme zur Kalibrierung und Umrechnung von Messwerten, der Annotation von Texten und Objekten der Bereitstellung sowie zur Verknüpfung und Visualisierung fachlich relevanter Vokabulare. Forschungssoftware kann auf einen sehr spezifischen Bedarf gerichtet sein oder bietet generische Lösungen an. Sie ist dabei stets Teil des Forschungsprozesses, der in allen seinen Punkten nachvollziehbar und soweit möglich reproduzierbar sein muss.


### FAIRe Forschungssoftware?
Aus dieser Definition von Forschungssoftware ergeben sich Anforderungen, die in vielen Punkten denen entsprechen, die an Forschungsdaten gerichtet werden. Wie Forschungsdaten soll -software den FAIR-Prinzipien entsprechen: auffindbar, zugänglich, interoperabel und reproduzierbar. Die Ableitung von Maßnahmen, die auf Software Anwendung findet, umfasst:

- den Nachweis von Forschungssoftware in Repositorien
- die Zitierbarkeit von Software
- die eindeutige Autorenschaft
- die Offenlegung des Quellcodes
- die Anwendung von Standards

Die Offenlegung des Quellcodes ist dabei bereits eine für Forschungssoftware spezifische Ableitung, die keine Gültigkeit für Forschungsdaten hat, weil Forschungsdaten andere Informationen beinhalten [@lamprecht_towards_2019, 3 f.]. Die Forderung nach der Offenlegung des Quellcodes (OpenSource) wird dabei vielfach noch erweitert um die Forderung, den Code zudem frei nutzbar zur Verfügung zu stellen FreeSource), wird seit vielen Jahren als FOSS (Free/Libre Open Source Software) bezeichnet und wird in Deutschland z.B. von anwendungsbezogenen Wissenschaftler\*innen und Entwickler\*innen aus der Geoinformatik vertreten (FOSSGIS e.V.)., sowie von Research Software Engineers in der "de-RSE e.V." [@anzt_environment_2020].

> [FT] hier Hinweis auf https://arxiv.org/pdf/2005.01469.pdf hinzufügen und deRSE -> anzt_environment_2020
>
> [AK] ja! sehr gut und ich denke auch schon in Definition muss der Punkt "Fprschungssoftware ist lebendiges Ding" übernommen werden.
> [FT] ja muss ich noch reinfuddeln

Auch in anderen Punkten muss die Umsetzung auf das Bezug nehmen, was für Software spezifisch ist. Einen sehr konkreten Vorschlag dafür hat 2019 eine Gruppe von Research-Software-Entwickler\*innen aus der Bioinformatik vorgelegt [@lamprecht_towards_2019]. Mit Blick auf die Umsetzbarkeit zur Auffindbarkeit fallen hier unter anderem Softwarerepositorien als Infrastruktur auf, die eigene Funktionen und Formen der Trägerschaften kennt. Kommerzielle Anbieter, community-basierte Infrastrukturen und viele weitere Formen haben sich als eigene Systeme entwickelt, die oftmals nicht genuin aus der Forschung kommen. Ähnlich wie die kommerziellen Anbieter von Cloud-Diensten zum Austausch von Dokumenten geben sie aber starke Impulse für die Entwicklung der wissenschaftlichen Infrastrukturen. Gerade für die Auffindbarkeit ist aber aus den Vorschlägen der Gruppe die Bedeutung der fachwissenschaftlichen Einbindung und der klassischen Arbeit der Forschungsinfrastrukturen, nämlich Aufbau, Pflege und Anwendung von kontrolliertem Vokabular und Metadatenstandards abzulesen.

Einer eigenen Ausformulierung für Software bedarf auch die Frage der Interoperabilität. So kann Interoperabilität verstanden werden als Abfolge von Prozessen die bei der Erzeugung, Bearbeitung oder Analyse nacheinander aufgerufen werden. Sie kann aber auch als Interoperabilität der verschiedenen Schichten die miteinander korrespondieren müssen, um das Programm auszuführen verstanden werden [@lamprecht_towards_2019, 10 f.]. Forschungssoftware, die nur mit einem Betriebssystem funktioniert ist weniger interoperabel, als solche, die plattformunabhängig programmiert ist. Die Interoperabilität in einem Ablauf von Prozessen erfordert nicht, dass alle Prozessschritte mit der Software abgebildet werden, sondern dass sie über Protokolle, Schnittstellen und Ausgabeformate den Durchlauf ermöglichen.

Einen wichtigen Punkt bildet die eindeutige Autorenschaft. Erst mit ihr kann die wissenschaftliche Leistung mit der Person verbunden werden. Eine Voraussetzung, um akademische Karrierewege zu eröffnen, in denen bislang Qualität und Anzahl klassischer Publikationen sind, zukünftig aber auch Datenpublikationen, Softwarepublikation und -zitation (https://citation-file-format.github.io, https://doi.org/10.5281/zenodo.1003149), Annotationen und die Softwareentwicklung Kriterien der Beurteilung sein sollen (s. NFDI4Culture, RSE4NFDI, NFDI4Objects). Die eindeutige Zuweisung und die Sichtbarmachung der Autorenschaft wird aber zudem auch in der kritischen Auseinandersetzung mit dem Bias von Software eingefordert (Fußnote: Angestoßen wird dies insbesondere von Untersuchungen, die sich mit Software auseinandersetzt, die zur Diskrimination von Gruppen und Individuen führt, so etwa Facial-Recognition-Software, die ausschließlich auf die Erkennung hellhäutiger Menschen ausgerichtet ist [@breland_how_2017]). Interessanterweise kann gerade die Archäologie und hier die Archäologischen Informationen auf eigene Erfahrungen mit der Nennung der Autorenschaft zurückblicken, wie es das einleitende Zitat zeigt. Autorenschaft von Software unterscheidet sich jedoch heute deutlich von dem, was in der Publikation von Aufsätzen und Büchern gewohnt ist. Die Entwicklung von Software beinhaltet heute ganz wesentlich die neue Verknüpfung und Ergänzung vorhandener Module, entsprechend muss auch das Verständnis von Autorenschaft und wie sie sich auch über die Lebenszeit der Software hinaus dokumentieren lässt spezifisch für Software erfolgen [@katz_software_2016].

Die Anwendung von FAIR-Prinzipien fördert die Qualität der Software hinsichtlich der grundsätzlichen Ansprüche an Interoperabilität bei der Verwendung in einem Workflow und der Verwendung von Standards und etablierten Paradigmen des Programmierens und der Dokumentation. Die FAIR-Prinzipien haben aber keine direkte Auswirkung auf die Usability und beziehen sich nicht auf die wissenschaftliche Qualität des Tools. Dennoch ergeben sich eine Anzahl von Kritertien, die in die Beurteilung einer Forschungssoftware einfließen und von Angaben, die im Rahmen der Rezension als Serviceleistung zu erbringen sind, wie die Autorenschaft, das Repositorium, mögliche nötige Voraussetzungen zur Verwendbarkeit.  

### Fachliche Beurteilung

Es bedarf als weiterer Kriterien, um festzustellen, was eine gute Forschungssoftware ist, und um in einer Rezension die Leistung der Entwickler\*innen angemessen zu beurteilen.
Die Beschäftigung mit der wissenschaftlichen Nutzung, also den Nutzungsszenarien von Forschungssoftware ist in der fachwissenschaftlichen Forschung bereits verankert (bezogen auf die in der Ur- und Frühgeschichte und der Archäologie des Mittelalters betriebene Forschung). Die AG CAA e.V. führt seit 2010 jährlich Workshops durch, in denen Tutorials zu Software durchgeführt und Fallbeispiele diskutiert werden sowie Entwickler\*innen ihre Tools zur Diskussion stellen. Auch in den Fachzeitschriften und Tagungen mit anderen thematischen, räumlichen und zeitlichen Schwerpunkten werden in gewisser Regelmäßigkeit entsprechende Fallbeispiele publiziert. Und Tagungen, Sammelbände uns Ausstellungen nehmen sich bestimmter Themen an, wie der Auswertung von LIDAR-Daten oder 3D-Rekonstruktionen (LIT./LIT).

Mit den Fallbeispielen verwandt, aber aus einem anderen Fokus geschrieben, sind Publikationen von Forschungsergebnissen, die unter dem Einsatz spezifischer Forschungssoftware erzielt wurden. In eigenen Abschnitten zur Vorgehensweise der Untersuchung wird hier auch die Software beschrieben jedoch nur insoweit, wie es für das Verständnis der methodischen Vorgehensweise erforderlich ist (exemplarisch: Zimmermann, Saile, Freund). Während dabei Aspekte wie die Oberflächengestaltung kaum eine Rolle spielen, werden je nach Qualität der Arbeit die zugrundeliegenden Berechnungswege, die Modellierung der Daten und die Wechselbeziehung mit dem Forschungsdesign fassbar. Aus ihnen lassen sich im Idealfall Ansätze zur Weiterentwicklung der Software oder auch zur Ergänzung weiterer mathematischer Verfahren ableiten. Eröffnen die zuvor als Fallbeispiele eingeordneten Publikationen der Forschung Software, kann die fachwissenschaftliche Forschung durch die intensive Nutzung und Kritik der Ergebnisse die Entwicklung der Software vorantreiben. Letzteres ist auch der Fall bei Arbeiten einer insgesamt kleineren Anzahl von Autorinnen und Autoren, die sich in ihren Beiträgen mit der Leistungsfähigkeit und den Parametern  der Rechnungen selbst, bzw. den Algorithmen auseinandersetzen (exemplarisch: Irmela Herzog 2012, 2014 und Gerhard Roth LIT).

Zusammengefasst können aus den eigenen fachlichen Traditionen der Archäologie Kriterien für eine Rezension abgeleitet werden, die das Potenzial für die wissenschaftliche Arbeit und die Passung zum Forschungsfeld beschreibt.

### Die handwerkliche Qualität

Die Frage der Interoperabilität und im gewissen Maße auch der Zugänglichkeit führt zur Qualität des Software Engineering. Bewusst ist dies hier als "handwerkliche" Qualität bezeichnet, denn Software Engineering erfordert spezifische Kompetenzen und Skills. Es baut auf eigene Wissensbestände zu ihrer Vermittlung und hinter der handwerklichen Qualität steht eine eigene Forschung aus den anwendungsbezogenen Wissenschaften. Wie bei handwerklichen Produkten ist die Qualität aber auch für die Nutzer\*innen erkennbar und zwar, wenn es um alle Aspekte der Nutzbarkeit geht. Davon etwas abgesetzt ist die Qualität des Programmcodes, die Art der Dokumentation, die Einbindung und Bezugnahme auf die Entwicklungen und Communities im Software Engineering. Letzteres sind Kriterien, die unmittelbar mit der Zukunftsfähigkeit der Software verbunden sind und daher ein wichtiges Merkmal sind, wenn es um den Einsatz von Software auf institutioneller Ebene oder für langfristige Vorhaben geht.

#### Nutzbarkeit

Unter Nutzbarkeit wird oftmals allein UX Design verstanden, was Fragen der Gestaltung und Bedienbarkeit grafischer Oberflächen von Programmen (GUI) und Webseiten beinhaltet. Hier geht es dann um die Benutzbarkeit von Webanwendungen mit verschiedenen Endgeräten (Responsivität), die Strukturierung von Informationen über die Menüführung hinweg, die Verständlichkeit von Texten und auch die Barrierefreiheit (Farbkontraste, Screenreader u.ä.).

Usability umfasst aber noch mehr und schließt alle Aspekte ein, die eine fehlerfreie und effiziente Nutzung durch die Forscherin, den Forscher ermöglichen. Für Forschungssoftware ist es z.B. besonders wichtig, dass die Eingabe von Daten sich an der Eingabepraxis orientiert; wenn etwa die händische Eingabe von Werten sehr typisch ist, dann ist es Aufgabe einer guten Benutzbarkeit, diesen Vorgang mit vorgegebenen Feldformaten, automatischem Speichern, gut sichtbaren Feldern oder ähnlichem zu unterstützen. Ebenso muss Software die üblicherweise von Teams genutzt wird, in denen verschiedene Kompetenzen vertreten sind, ein Rechtemanagement vorsehen, das die unterschiedlichen Verantwortlichkeiten abbilden kann. Forschungssoftware wird nicht im leeren Raum genutzt, sondern trifft auf Erwartungen und Gewohnheiten der Nutzer\*innen, sowohl was ihre Bedienung betrifft, als auch die ergänzenden Angebote zur Unterstützung, wie Tutorials FAQs und ähnliches. Software, die für hochspezielle Fragestellungen verwendet wird, die auf einer Reihe vorhergehender Prozessschritte aufbaut, richtet sich an einen anderen Nutzerkreis, als Software, die Basisfunktionen erfüllt. Weil Forscher\*innen am besten beurteilen können, ob ihre Bedarfe und Gewohnheiten gut adressiert sind und die Forschungssoftware ihnen ein gutes Arbeiten erlaubt, gehört eine Beurteilung dieser Aspekte in die Rezension.
Ableiten lassen sich Kriterien, auf die sich die Nutzungserfahrung abbilden lässt aus der Forschung und den Referenz-Standards zur Usability. Zu nennen ist unter anderem der ISO/IEC 9126 Standard und spezifisch für Webanwendungen bilden die Empfehlungen und Standards des W3C (@noauthor_w3c_nodate).  

#### Software Engeneering

Wie gut ist der Code

### Ethische Angemessenheit

Unter diesem Punkt ist noch einmal extrapoliert, was sowohl in den FAIR-Prinzipien z.B. hinsichtlich der Autorenschaft als auch der Vertiefung zur Usability implizit mitgetragen wird: Forschungssoftware ist nicht neutral. Sie entsteht nicht unter neutralen Bedingungen, ihre Nutzung erfolgt unter spezifischen Bedingungen und auch ihre Weitergabe unterliegt den vorherrschenden Konventionen und Gewohnheiten. Vielfach tragen diese Gewohnheiten und Konventionen auch zur Befestigung von Privilegien und Diskriminierungen bei, etwa wenn Tutorials ausschließlich männliche Nutzer kennen, oder die an der Entwicklung beteiligten Personen nicht genannt werden.

Weniger auffällig ist zunächst die Frage der Sprachen für die Nutzeroberflächen und Tutorials. Für die Archäologien stellt sich etwa die Frage, wie angemessen es ist, für die archäologische Feldarbeit Software zur Datenaufnahme einzusetzen, die für die Mehrheit der Mitarbeiter\*innen vor Ort nicht verständlich ist und ihnen somit Teile der Tätigkeiten vor Ort verschließt. Zu überlegen ist auch, ob Software, die zwar frei und offen lizensiert ist, aber das Vorhandensein proprietärer Software oder auch teurer Hardware voraussetzt, die Diskriminierung von Forscher\*innen mit weniger Finanzmitteln zur Folge haben kann. Plugins, die zwingend die Benutzung von Software voraussetzt, die wiederum die Erfassung von Nutzerverhalten zum Geschäftsmodell hat, ist ebenfalls problematisch bzw. ist unter Umständen nicht mit institutionellen Vorgaben vereinbar. Alle genannten Aspekte stehen letztlich dem Ziel der Transparenz und Reproduzierbarkeit entgegen.

### Was ist keine Forschungssoftware - und kann dennoch mit Hilfe des Leitfadens betrachtet werden?

Einen eigenen und für die Archäologien charakteristischer Bereich ist Software zur Nutzung spezifischer Geräte etwa zur Vermessung, fotografischen Dokumentation, Analyse von Oberflächen und Inhaltsstoffen. Sehr oft findet sich hier proprietäre Software, die mit der Hardware vertrieben wird. Diese Software wird zwar in der Forschung eingesetzt, aber ihre Programmierung ist nicht transparent, vielfach werden zudem Daten in proprietären Formaten erzeugt. Entsprechend können zwar der Umgang mit der Software und die Produktqualität aus Sicht der Nutzerinnen als Erfahrungswerte beschrieben werden, aber es können keine begründeten Aussagen zur Performanz unter veränderten Bedingungen, zur Stabilität und anderes getroffen werden. Einige der im folgenden dargestellten Kriterien zur Rezension von Forschungssoftware können somit auf proprietäre Software angewendet werden und eine Berücksichtigung der Aspekte wird ausdrücklich empfohlen.

In der praktischen Arbeit spielen vielfach digitale Werkzeuge eine erhebliche Rolle, die die Arbeit unterstützen, aber keinen Anteil an der Erhebung, Bearbeitung und Analyse der Daten haben. Ihre Passgenauigkeit setzt wie bei der eigentlichen Forschungssoftware eine genaue Kenntnis des Arbeitsfelds voraus und entsprechend sind nicht selten stehen die eigenen Kolleg\*innen hinter der Entwicklung. Eine angemessene Besprechung der Software kann hier sehr direkt zur Verbesserung des Tools führen. 

## Kriterien und Vorgehensweise zur Rezension von Software

### Vorgehensweise

Eine Softwarerezension sollte wie die Besprechung einer Publikation zunächst mit einer kurzen Beschreibung der Software beginnen. Zusammengefasst vorgestellt werden sollte der Einsatzbereich der Software, ihre Komponenten und ihr Entstehungskontext. Diese erste Übersicht kann in einer ersten grundsätzlichen Einschätzung der Software hinsichtlich ihrer Nützlichkeit für die Forschung und ihrer handwerklichen Qualität enden. Für die anschließende detaillierte Besprechung der Software und die Begründung der Einschatzung möchten wir die unten folgenden Kriterien vorschlagen. Alle Kriterien sind Ableitungen aus den eingangs erläuterten Prinzipien und Forderungen an Forschungssoftware. 

### Kriterien
> [AK: Ab hier bitte ordnen und Dinge auch mal erklären z.B. kann mit ""Builtprozess"]

#### Wissenschaftliches Einsatzgebiet und wissenschaftliche Relevanz
* Welches wissenschaftliche Problem versucht die Software zu lösen bzw. welche Aufgaben werden mittels der Software bei der Erfassung, der Verarbeitung oder der Analyse durchgeführt. Wie sind diese Probleme und Aufgaben von ihrer Relevanz und von ihrer Häufigkeit einzuschätzen? 
* Wie löst die Software das gegebene Problem? Wie ist die grundsätzliche Funktionsweise konzipiert? Was sind die wesentlichen Bestandteile in Frontend und Backend (z.B. WebApp + Datenbank, CLI + Neuronales Netz, ...)?
* Wie funktioniert der (wissenschaftliche) Algorithmus, der mit der Software implementiert wurde (natürlich in kurzen Worten: Punktmuster gehen hinein, Magie passiert, Kennwerte kommen heraus)?
* Gibt es neben der Software noch weitere Alternativen, oder ist sie die einzige für diesen spezifischen Einsatzbereich.
	* Wenn es Alternativen gibt, worin unterscheiden sie sich mit Blick auf den wissenschaftlichen Einsatz, die Problemlösung
* Entspricht der reale Einsatz den generellen Anwendungszenarien, den die Entwickler\*innen vor Augen hatten? Unter

#### System, Umgebung und Installation
* Diese technischen Merkmale sind Kriterien, die die Benutzbarkeit (Usability) betreffen. Die Einschätzung der Nutzbarkeit richtet sich nach den Kompetenzen der Zielgruppe und die Kriterien leiten hier zur genauen Beobachtung an.

>[AK: Was genau ist mit Umgebung gemeint?]

* Handelt es sich um eine Webapp, oder muss die Software installiert werden. Kann sie auch ohne Admin-Rechte installiert werden oder kommt als portable Software?
* Bei Software die installiert wird: Ist sie plattform-unabhängig oder an bestimmte Betriebssysteme gebunden? 
* Werden zum Betrieb der Software weitere Programme benötigt, müssen Einstellungen am eigenen System geändert werden?
* Installationsvorgang: Wird die Installation mit einem Assistenten unterstützt? Wie und wo wird die Software angeboten? Welche Kompetenzen setzt die Installation voraus (Erfahrungen mit GitHub, mit der Commando Prompt)?
* Für Webapplikationen und Plugins ist zu überprüfen, ob sie responsiv sind und über die verschiedenen Browser hinweg performant sind

#### Ressourcenbedarf
* Ist der parallele Betrieb mit weiteren Anwendungen auf einem für den Aufgabenbereich typischen Rechner möglich oder werden Prozesse übermäßig verlangsamt, die Anwendung stürzt gar ab? 
* Wurden Spezifikationen veröffentlicht, welche Anforderungen das Programm hat?

#### Interface und Bedienung
* Wie intuitiv verständlich ist das Arbeiten mit der Software? 
* Entsprechen etwa die Benennung der Kommandos, die Anordnung der Menüs oder die Abfolge der vorzunehmenden Aufgaben den Gewohnheiten, oder kommen der praktischen Arbeit entgegen.
* In welchen Sprachen werden Nutzeroberflächen, Menüs und Hilfen angeboten?
* Müssen eigens zur Nutzung der Software bestimmte Kompetenzen und Kenntnisse erworben werden? Davon zu trennen ist das gegebenenfalls nötige fachliche Vorwissen etwa bei der Nutzung von Statistikprogrammen.


## Anschlussfähigkeit
* Welche Datenformate werden von der Software verarbeitet (Inputformate) und in welchen Datenformaten erfolgt die Ausgabe (Outputformate). 
	* Handelt es sich um offene oder proprietäre Datenformate?  
	* Handelt es sich um zukunftsfähige Datenformate in der Community - Zur Orientierung schlagen wir aktuell (Stand Sommer 2020) die IT-Empfehlungen des Forschungsdatenzentrums Archäologie & Altertumswissenschaften, IANUS vor [@ianus-forschungsdatenzentrum_fur_archaologie__altertumswissenschaften_it-empfehlungen_2014].
** Hält sich die Anwendung an Standards welche im jeweiligen Kontext vorgegeben werden (z.B. W3C Standards zur Annotation oder auch archäologische Standards) und bildet diese standardkonform in den Daten ab?
* Können andere Forschungscommunities durch den Export spezifischer Datenformate profitieren? (z.B. RDF für Linked Data, GeoJSON für GIS community, TEI für Texte etc.)

* Wie können Daten eingegeben werden und wie erfolgt die Ausgabe? 
* Ist die Anwendung sowohl für den Menschen als auch maschinenlesbar nutzbar/Gibt es Programmierschnittstellen (APIs) oder Webservices?

### Zugänglichkeit, Hilfefunktionen und Community
- __Wo finde ich mehr Informationen zu dieser Software?__ Hyperlinks und Referenzen.

- __Tutorials, FAQs und Hilfefunktionen__ sind ein weiterer wichtiger Aspekt. Hier sollte überprüft werden, ob die Tutorials auf unterschiedliches Vorwissen eingehen und gegebenenfalls auch kenntlich machen, welches Grundwissen, welche Erfahrungen unabdingbar sind. Ein weiterer Aspekt bei den Anleitungen, Tutorials und FAQs ist die Frage der Sprachen.
- __Community__ Die Zahl der aktiven Nutzer eines Softwarewerkzeugs ist entscheidend dafür, ob man im Falle von Problemen schnell Hilfe googeln kann. Ist das Werkzeug das Erzeugnis eines einzigen Labors und wird von einer Hand voll eingeschworener Kollegen genutzt, oder handelt es sich um eine global etablierte Software mit Nutzerforum, Mailingliste und ganzen Büchern zur Nutzung in bestimmten Kontexten? Selbst wenn ein Werkzeug nur eine kleine Community besitzt kann dieser Mangel doch bis zu einem gewissen Grad von aktiven und leicht erreichbaren Entwicklern ausgeglichen werden, die bereit sind konkrete Fragen schnell und unkompliziert zu beantworten.

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


## Bibliographie

