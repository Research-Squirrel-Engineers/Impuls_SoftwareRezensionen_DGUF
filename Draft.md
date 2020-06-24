---
title: Handreichung zur Rezension von Forschungssoftware - Kriterien für "gute" Forschungssoftware
layout: draft
author:
  - Anne Klammt, Deutsches Forum für Kunstgeschichte Paris
  - Timo Homburg
  - Clemens Schmid
  - Sophie Charlotte Schmidt
  - Lutz Schubert
  - Florian Thiery, Research Squirrel Enginners
  - Martina Trognitz
bibliography: literatur.bib
csl: apa-6th-edition.csl

---

<div id="zitat" markdown="1">
"Die Leitfunde werden dann im Computer durch die Programme ARCH und GGG einer Seriation unterzogen. Diese Programme entwickelte E. Kämmerer. Eine Beschreibung ist der Arbeit beigefügt. Die Programme DOK und ARCH z. Zt. für 600 Typen in 2000 Funden dimensioniert, sind am Rechner TR 440 beim Großrechenzentrum für die Wissenschaft in Berlin in Anwendung." [@goldmann_chronologische_1972, 98.](#goldmann_chronologische_1972)
</div>

---

## Gliederungsvorschlag

* [Zielsetzung](#Zielsetzung-des-Beitrags)
* [Forschungssoftware](#Forschungssoftware)
  * [Forschungssoftware als wissenschafltiche Leistung](#forschungssoftware-als-wissenschaftliche-leistung)
  * [Gute Forschungssoftware](#Gute-Forschungssoftware)
    * [FAIR Prinzipien](#FAIR-Prinzipien) (FAIR, CARE, Open, Gute wissenschafltiche Praxis) (Wie sieht die ideale Forschungssoftware aus?)
    * [Open Science](#open-science) (Open Science; Open Data, Open Source)
    * [CARE Prinzipien](#care-prinzipien) (https://www.gida-global.org/care)
* [Anwendungsbereich dieser Handreichung](Anwendungsbereich-dieser-Handreichung)
* [Vorgehensweise bei der Rezension von Software](#Vorgehensweise-bei-der-Rezension-von-Software)
* [Kriterien zur Beurteilung von Software](#Kriterien-zur-Beurteilung-von-Software)
  * ... alle Unterpunkte ab [dort](#Kriterien-zur-Beurteilung-von-Software)
* Tabellarische Zusammenfassung?

---

## Zielsetzung des Beitrags<sup>[1](#myfootnote1)</sup>

Die Beurteilung einer wissenschaftlichen Publikation ist eine traditionsreiche Form des wissenschaftlichen Diskurses. Entsprechend gibt es ein unausgesprochenes Verständnis davon, was eine gute Rezension ausmacht. Unterstützt werden kann dies durch redaktionelle Maßnahmen zur Qualitätssicherung wie Hinweise für die/den Rezensentin/Rezensenten oder - wie es die DGUF mit den Archäologischen Informationen praktiziert - eines Reviews der angefertigten Rezension. Die Frage ist jedoch, was sollte eine gute Rezension von Software für den Einsatz in der Archäologie ausmachen? Geht es dabei allein um Aspekte der Nutzbarkeit, der Usability? Sollten nicht auch Fragen der Nachhaltigkeit und der Anschlussfähigkeit einfließen? Müsste nicht auch betrachtet werden, ob es eine wissenschaftliche Dokumentation und Diskussion der rechnerischen Verfahren gibt - etwa bei den vielen Interpolationen von Daten mit Raumbezug, die moderne GIS-Softwarepakete bieten?



In dieser Handreichung erläutern wir einige Kriterien für gute Forschungssoftware. Dabei folgen wir den Empfehlungen der DFG und weisen auf sogenannte "open standards" hin, da Software im- und explizit tief in die Forschung eingreift (für die Archäologie siehe z.B. [@schmidt_marwick_2020](#schmidt_marwick_2020) und nur durch die Offenlegung von Quellcode eine Bewertbarkeit der durch die Software geleisteten Abläufe gewährleistet ist.
Wir empfehlen eine Vorgehensweise bei der Softwarerezension und sammeln Kriterien, die für die Bewertung einer Software von Bedeutung sein können. Dabei ergibt sich aus der Vielfalt der möglichen Besprechungsgegenständen, dass nicht alle Kriterien in jedem Fall von Bedeutung sein werden.

Ziel dieser Handreichung ist es Fragen und Themen aufzuwerfen, die der/ dem Rezensent*in die Arbeit erleichtern können. Die weitere Diskussion zu diesen Theme ist erwünscht, -- hier website und Kontaktdaten einfügen ? --

## Forschungssoftware

Die weiter unten vorgestellten Kriterien zur Rezension von Software zielen primär auf die Begutachtung von Forschungssoftware ab. Unter Forschungssoftware verstehen wir Software, die mit Fokus auf einen Einsatz in der Forschung entwickelt wurde, also um Forschungsdaten zu erzeugen, zu verarbeiten oder zu analysieren [@hettrick_2014_14809]. Dies sind beispielsweise Programme, die der Kalibrierung und Umrechnung von Messwerten, der Annotation von Texten und Objekten, oder der Bereitstellung sowie der Verknüpfung und Visualisierung fachlich relevanter Vokabulare dienen.

Forschungssoftware kann entweder für einen sehr spezifischen Bedarf oder einen allgemeinen Anwendungsbereich entwickelt worden. Sie ist dabei stets Teil des Forschungsprozesses, der in allen seinen Punkten nachvollziehbar und soweit möglich reproduzierbar sein muss.

Im Gegensatz zu Forschungssoftware steht Software, die zur Nutzung spezifischer Geräte erforderlich ist, wie etwa zur Vermessung, zur fotografischen Dokumentation oder zur Analyse von Oberflächen und Inhaltsstoffen. Häufig handelt es sich um proprietäre Software, die zusammen mit der Hardware vertrieben wird. Obwohl sie im Forschungsprozess eingesetzt wird, entspricht sie nicht unserem Verständnis von Forschungssoftware.

Auch digitale Werkzeuge, die eine erhebliche Rolle in der praktischen Arbeit inne haben, jedoch keinen eigentlichen Anteil an der Erhebung, Bearbeitung und Analyse der Daten haben, sind in unserem Sinne keine Forschungssoftware.

### Forschungssoftware als Wissenschaftliche Leistung

Mit der Einführung der Rezensionskategorie "Archäoinformatik" intendieren die Herausgeber\*innen der Archäologischen Informationen eine Stärkung der Autor\*innen von Forschungssoftware als Produzent\*innen von Wissenschaft. In die Entwicklung von Forschungssoftware fließen häufig einerseits jahrelange technische Erfahrung und Praxis sowie Wissen über wissenschaftliche Standards und Praktiken ein. Diese werden durch die Umsetzung in Code explizit gemacht und/oder weiterentwickelt. Diese Leistung gilt es zu würdigen (Helmholtz-Zentrum: https://os.helmholtz.de/open-science-in-der-helmholtz-gemeinschaft/forschungssoftware/) und sichtbar zu machen.

Dafür werden im Folgenden einige Punkte genannt und weiter ausgeführt.

>[SCS: Noch ein bissl wenig]

> [MT] Bausteine: (RSE und Stand von Forschungssoftware in der Fachgemeinschaft)


### Gute Forschungssoftware

> [MT] Einleitung für Ausführungen weiter unten
> Bausteine: DFG gute wissenschaftliche Praxis; internationaler Kontext; Aufbauend: zuerst FAIR, dann Open, und als i-tüpfelchen dann CARE

#### FAIR Prinzipien
Wie Forschungsdaten soll -software den FAIR-Prinzipien [@Wilkinson_2016] entsprechen: auffindbar (Findable), zugänglich (Accessible), interoperabel (Interoperable) und nachnutzbar (Reusable). Daraus lassen sich Vorgaben ableiten, die speziell für Software Anwendung finden:

Die Anwendung von FAIR-Prinzipien fördert die Qualität der Software hinsichtlich der grundsätzlichen Ansprüche an Interoperabilität bei der Verwendung in einem Workflow und der Verwendung von Standards und etablierten Paradigmen des Programmierens und der Dokumentation. Die FAIR-Prinzipien beziehen sich nicht auf die wissenschaftliche Qualität des Tools. Dennoch ergeben sich eine Anzahl von Kritertien, die in die Beurteilung einer Forschungssoftware einfließen und von Angaben, die im Rahmen der Rezension als Serviceleistung zu erbringen sind, wie die Autorenschaft, das Repositorium, mögliche nötige Voraussetzungen zur Verwendbarkeit.


##### Findable (Auffindbar)

Um Software auffindbar zu machen gibt es z. B. Softwarerepositorien. Kommerzielle Anbieter, community-basierte Infrastrukturen und viele weitere Formen haben sich als eigene Systeme entwickelt, die starke Impulse für die Entwicklung der wissenschaftlichen Infrastrukturen geben. Von Bedeutung ist die fachwissenschaftlichen Einbindung und die klassische Arbeit von Forschungsinfrastrukturen, nämlich Aufbau, Pflege und Anwendung von kontrolliertem Vokabular und Metadatenstandards.

Forschungssoftware kann durch die mit einer persistenten URL verknüpften Ablage in einem Repositorium und der Nennung der Autorenschaft zitierbar gemacht werden. Wichtig ist hierbei, dass Software, da sie im Gegensatz zu "schriftlichen Publikationen" kontinuierlich weiterentwickelt wird, in unterschiedlichen Entwicklungsständen abgelegt wird, damit bestimmte Stände zitiert werden können (https://www.forschungsdaten.info/themen/ethik-und-gute-wissenschaftliche-praxis/softwareentwicklung-und-gute-wissenschaftliche-praxis/).

##### Accessible (Zugänglich)

Die Zugängglichkeit kann sich einerseits auf die Zugänglichkeit zu dem Programm beziehen als auch auf die Nutzbarkeit. Ein Programm wird z. B. dadurch zugänglich, wenn es kostenlos für verschiedene Plattformen zur Verfügung steht, wenn die technischen Anforderungen an die Hardware von den meisten derzeitigen Rechnern zu leisten sind und eine verständliche Anleitung zur Nutzung des Programms zur Verfügung steht.

> [MT] längere Ausführungen zu den Kriterien verschoben

##### Interoperable (Interoperabel)

Einer eigenen Ausformulierung für Software bedarf die Frage der Interoperabilität. Interoperabilität von Software kann sich auf die Verknüpfungsmöglichkeiten von Prozessen beziehen, die bei der Erzeugung, Bearbeitung oder Analyse nacheinander notwendig werden (horizontale Dimension). Diese Prozessschritte müssen nicht innerhalb einer Software ablaufen, sondern werden häufig über Protokolle, Schnittstellen und Ausgabeformate als Durchlauf durch mehrere Programme ermöglicht. Interoperabilität kann aber auch als die Zusammenarbeit verschiedener digitaler Objekte für die Ausführung eines Prozesses bedeuten (vertikale Dimension) [@lamprecht_towards_2019, 10 f.](#lamprecht_towards_2019). Wenn dabei eine Software z. B. nur mit einem Betriebssystem arbeiten kann, ist sie weniger interoperabel, als solche, die plattformunabhängig programmiert ist

##### Reusable (Nachnutzbar)

Mit der Forderung nach der Offenlegung des Quellcodes (Open Source), entspricht dem Gedanken der Nachnutzbarkeit (reusable). Vielfach wird er  noch erweitert um die Forderung, den Code zudem frei nutzbar zur Verfügung zu stellen (Free Source). Letzteres wird als FOSS (Free/Libre Open Source Software) bezeichnet und wird in Deutschland z.B. von anwendungsbezogenen Wissenschaftler\*innen und Entwickler\*innen aus der Geoinformatik vertreten (FOSSGIS e.V.). oder von Research-Software-Engineers in der "de-RSE e.V." [@anzt_environment_2020](#anzt_environment_2020).

Code kann nur dann von anderen nachgenutzt werden, wenn er unter einer dementsprechenden Lizenz zur Verfügung gestellt wird...
>[SCS: Hier muss noch was]
> [MT] das mit dem Open sehe ich an dieser stelle etwas kritisch. FAIR beinhaltet nämlich ganz bewusst nicht die Forderung nach Open. 

Die FAIR-Prinzipien wurden aus dem Forschungsdatenmanagement übernommen. Im Bereich des Datenmanagements wurde darauf hingewiesen, dass es durchaus Gründe gibt, Daten zurückzuhalten, insbesondere wenn es um Rechte Indigener Bevölkerungen geht (siehe auch Marwick und Birch). Von diesen wurden weitere Richtlinien, die mit CARE abzukürzen sind entwickelt (https://www.gida-global.org/care):

#### Open Science

Open Science (Offene Wissenschaft) bezeichnet eine Wissenschaftspraxis, deren Ziel ein transparenter Forschungsprozess und eine Zugänglichkeit der Ergebnissen für die Wiederverwendung und Weiterentwicklung ist ( https://doi.org/10.5281/zenodo.1212496 ?). Für offene Forschungssoftware gilt, dass ihr Quellcode zugänglich und für die Weiterentwicklung lizenziert sein muss (https://book.fosteropenscience.eu/en/02OpenScienceBasics/03OpenResearchSoftwareAndOpenSource.html)

In den "Leitlinien zur Sicherung guter wissenschaftlicher Praxis" weist die DFG darauf hin, dass für die Qualitätssicherung
"[...] die Auswahl und Nutzung  von  Forschungssoftware,  deren  Entwicklung  und  Programmierung" von Bedeutung sind.
Unabhängig von dem Fachgebiet hat die Herkunft der Software dargestellt zu werden, und der Quellcode öffentlich zugänglicher Software muss "persistent, zitierbar und dokumentiert sein", um die Replizierbarkeit und Reproduzierbarkeit zu gewährleisten.  [@deutsche_forschungsgemeinschaft_2019, 14-15](#deutsche_forschungsgemeinschaft_2019)

Helmholtz-Zentrum: https://os.helmholtz.de/open-science-in-der-helmholtz-gemeinschaft/forschungssoftware/  

Dieser Anforderungen können anhand der FAIR- und CARE-Prinzipien, wie sie für Datenmanagement bestehen, genauer erläutert werden:

>[SCS: Braucht noch Infos zu Open Data (aber nich zu viel, weil Fokus ja woanders liegt)]

> [MT]: FAIR ist nicht automatisch gleich Open(!); Deshalb habe ich das in der Gliederung noch umgeordnet: zuerst FAIR, dann Open Science und dann noch CARE und Ethik. Wenn man FAIR macht ist es gut, wenn man Open Science praktiziert noch besser und wenn man dann auch noch CARE berücksichtigt kann man eigentlich nichts mehr besser machen

#### CARE-Prinzipien

Die CARE-Prinzipien wurden von der Research Data Alliance International Indigenous Data Sovereignty Interest Group auf Basis der UN Declaration on the Rights of Indigenous Peoples (UNDRIP) entwickelt, die die Rechte und Authorität der Indigenen bezüglich ihres kulturellen Erbes und auch Wissens bestätigt.

Folgende Prinzipien wurden aufgestellt und elaboriert:

- Collective Benefit (gemeinschaftlicher Nutzen für Indigene Menschen):
- Authority to Control (Kontrollmacht für Indigene Menschen)
- Responsibility (Verantwortung für die positive Folgen der Datennutzung)
- Ethics (Rechte und Wohl der Indigenen Menschen)

Diese CARE-Prinzipien lass sich in einigen Punkten ebenfalls auf Forschungssoftware übertragen, wenn auch teilweise in abgewandelter Bedeutung.

#####  C

collective benefit: CC Veröffentlichung, wenn aus Forschungsgeldern bezahlte entwicklung?

Inklusvitiät bei der Entwicklung



##### A auhtority to control:


Die eindeutige Autorenschaft hat zusätzliche Bedeutung. Erst mit ihr kann die wissenschaftliche Leistung, die in die Entwicklung der Software eingeflossen ist, mit der Person verbunden werden. Das ist eine Voraussetzung, um dieser akademische Karrierewege zu eröffnen, in denen bislang nur die Qualität und Anzahl klassischer Publikationen gezählt haben. Zukünftig sollten aber in gleicher Weise auch Datenpublikationen, Softwarepublikation und -zitation (https://citation-file-format.github.io, https://doi.org/10.5281/zenodo.1003149), Annotationen und die Softwareentwicklung Kriterien der Beurteilung der wissenschaftlichen Leistung sein (s. NFDI4Culture, RSE4NFDI, NFDI4Objects). Die eindeutige Zuweisung und die Sichtbarmachung der Autorenschaft wird zudem auch in der kritischen Auseinandersetzung mit dem Bias von Software eingefordert<sup>[1](#myfootnote2)</sup>.

Gerade die Archäologie und hier die Archäologischen Informationen können auf eigene Erfahrungen mit der Nennung der Autorenschaft zurückblicken, wie es das einleitende Zitat zeigt. Autorenschaft von Software unterscheidet sich jedoch heute deutlich von dem, was in der Publikation von Aufsätzen und Büchern gewohnt ist. Die Entwicklung von Software beinhaltet ganz wesentlich die neue Verknüpfung und Ergänzung vorhandener Module, entsprechend muss auch das Verständnis von Autorenschaft und wie sie sich auch über die Lebenszeit der Software hinaus dokumentieren lässt spezifisch für Software erfolgen [@katz_software_2016](#katz_software_2016).

Software, die auf Indigenem Wissen beruht

#####  R
responsibilty: Verantwortung für Code übernehmen?

##### E
ethics: siehe Hinweis Hautfarbe (in der Fußnote 2 ganz unten)
 Angestoßen wird Letzteres insbesondere von Untersuchungen, die sich mit Software auseinandersetzt, die zur Diskrimination von Gruppen und Individuen führt, so etwa Facial-Recognition-Software, die ausschließlich auf die Erkennung hellhäutiger Menschen ausgerichtet ist [@breland_how_2017](#breland_how_2017).


Unter diesem Punkt ist noch einmal extrapoliert, was sowohl in den FAIR-Prinzipien z.B. hinsichtlich der Autorenschaft als auch der Vertiefung zur Usability implizit mitgetragen wird: Forschungssoftware ist nicht neutral. Sie entsteht nicht unter neutralen Bedingungen, ihre Nutzung erfolgt unter spezifischen Bedingungen und auch ihre Weitergabe unterliegt den vorherrschenden Konventionen und Gewohnheiten. Vielfach tragen diese Gewohnheiten und Konventionen auch zur Befestigung von Privilegien und Diskriminierungen bei, etwa wenn Tutorials ausschließlich männliche Nutzer kennen, oder die an der Entwicklung beteiligten Personen nicht genannt werden.

Weniger auffällig ist zunächst die Frage der Sprachen für die Nutzeroberflächen und Tutorials. Für die Archäologien stellt sich etwa die Frage, wie angemessen es ist, für die archäologische Feldarbeit Software zur Datenaufnahme einzusetzen, die für die Mehrheit der Mitarbeiter\*innen vor Ort nicht verständlich ist und ihnen somit Teile der Tätigkeiten vor Ort verschließt. Zu überlegen ist auch, ob Software, die zwar frei und offen lizensiert ist, aber das Vorhandensein proprietärer Software oder auch teurer Hardware voraussetzt, die Diskriminierung von Forscher\*innen mit weniger Finanzmitteln zur Folge haben kann. Plugins, die zwingend die Benutzung von Software voraussetzt, die wiederum die Erfassung von Nutzerverhalten zum Geschäftsmodell hat, ist ebenfalls problematisch bzw. ist unter Umständen nicht mit institutionellen Vorgaben vereinbar. Alle genannten Aspekte stehen letztlich dem Ziel der Transparenz und Reproduzierbarkeit entgegen.


Die FAIR und CARE Richtlinien dienen vor allem der allgmeinen technischen und ethischen Bewertung von Software. Jedoch gibt es noch eine Reihe fachlicher Spezifika, auf die wir im Folgenden eingehen wollen.

### Fachliche Beurteilung
> [MT] gehört schon zu den Kriterien

Es bedarf also weiterer Kriterien, um festzustellen, was eine gute Forschungssoftware ist, und um in einer Rezension die Leistung der Entwickler\*innen angemessen zu beurteilen.
Die Beschäftigung mit der wissenschaftlichen Nutzung, also den Nutzungsszenarien von Forschungssoftware ist in der archäologischen Forschung bereits verankert (bezogen auf die in der Ur- und Frühgeschichte und der Archäologie des Mittelalters betriebene Forschung). Die AG CAA e.V. führt seit 2010 jährlich Workshops durch, in denen Tutorials zu Software durchgeführt und Fallbeispiele diskutiert werden sowie Entwickler\*innen ihre Tools zur Diskussion stellen. Auch in den Fachzeitschriften und Tagungen mit anderen thematischen, räumlichen und zeitlichen Schwerpunkten werden in gewisser Regelmäßigkeit entsprechende Fallbeispiele publiziert. Und Tagungen, Sammelbände uns Ausstellungen nehmen sich bestimmter Themen an, wie der Auswertung von LIDAR-Daten oder 3D-Rekonstruktionen (LIT./LIT).

Mit den Fallbeispielen verwandt, aber aus einem anderen Fokus geschrieben, sind Publikationen von Forschungsergebnissen, die unter dem Einsatz spezifischer Forschungssoftware erzielt wurden. In eigenen Abschnitten zur Vorgehensweise der Untersuchung wird hier auch die Software beschrieben jedoch nur insoweit, wie es für das Verständnis der methodischen Vorgehensweise erforderlich ist (exemplarisch: Zimmermann, Saile, Freund). Während dabei Aspekte wie die Oberflächengestaltung kaum eine Rolle spielen, werden je nach Qualität der Arbeit die zugrundeliegenden Berechnungswege, die Modellierung der Daten und die Wechselbeziehung mit dem Forschungsdesign fassbar. Aus ihnen lassen sich im Idealfall Ansätze zur Weiterentwicklung der Software oder auch zur Ergänzung weiterer mathematischer Verfahren ableiten. Eröffnen die zuvor als Fallbeispiele eingeordneten Publikationen der Forschung Software, kann die fachwissenschaftliche Forschung durch die intensive Nutzung und Kritik der Ergebnisse die Entwicklung der Software vorantreiben. Letzteres ist auch der Fall bei Arbeiten einer insgesamt kleineren Anzahl von Autorinnen und Autoren, die sich in ihren Beiträgen mit der Leistungsfähigkeit und den Parametern  der Rechnungen selbst, bzw. den Algorithmen auseinandersetzen (exemplarisch: Irmela Herzog 2012, 2014 und Gerhard Roth LIT).

Zusammengefasst können aus den eigenen fachlichen Traditionen der Archäologie Kriterien für eine Rezension abgeleitet werden, die das Potenzial für die wissenschaftliche Arbeit und die Passung zum Forschungsfeld beschreibt.


### Die handwerkliche Qualität
> [MT] gehört schon zu den Kriterien

Die Frage der Interoperabilität und im gewissen Maße auch der Zugänglichkeit führt zur Qualität des Software Engineering. Bewusst ist dies hier als "handwerkliche" Qualität bezeichnet, denn Software Engineering erfordert spezifische Kompetenzen und Skills. Es baut auf eigene Wissensbestände zu ihrer Vermittlung und hinter der handwerklichen Qualität steht eine eigene Forschung aus den anwendungsbezogenen Wissenschaften. Wie bei handwerklichen Produkten ist die Qualität aber auch für die Nutzer\*innen erkennbar und zwar, wenn es um alle Aspekte der Nutzbarkeit geht. Davon etwas abgesetzt ist die Qualität des Programmcodes, die Art der Dokumentation, die Einbindung und Bezugnahme auf die Entwicklungen und Communities im Software Engineering. Letzteres sind Kriterien, die unmittelbar mit der Zukunftsfähigkeit der Software verbunden sind und daher ein wichtiges Merkmal sind, wenn es um den Einsatz von Software auf institutioneller Ebene oder für langfristige Vorhaben geht.








##  Anwendungsbereich dieser Handreichung

Forschungssoftware

Hardwarespezifische Software
, aber ihre Programmierung ist nicht transparent, vielfach werden zudem Daten in proprietären Formaten erzeugt. Entsprechend können zwar der Umgang mit der Software und die Produktqualität aus Sicht der Nutzerinnen als Erfahrungswerte beschrieben werden, aber es können keine begründeten Aussagen zur Performanz unter veränderten Bedingungen, zur Stabilität und anderes getroffen werden. Einige der im folgenden dargestellten Kriterien zur Rezension von Forschungssoftware können somit auf proprietäre Software angewendet werden und eine Berücksichtigung der Aspekte wird ausdrücklich empfohlen.

Weitere digitale Werkzeuge (*tools*)
 Ihre Passgenauigkeit setzt wie bei der eigentlichen Forschungssoftware eine genaue Kenntnis des Arbeitsfelds voraus und entsprechend sind nicht selten stehen die eigenen Kolleg\*innen hinter der Entwicklung. Eine angemessene Besprechung der Software kann hier sehr direkt zur Verbesserung des Tools führen.


## Vorgehensweise bei der Rezension von Software

Eine Softwarerezension sollte wie die Besprechung einer Publikation zunächst mit einer kurzen Beschreibung der Software beginnen. Zusammengefasst vorgestellt werden sollte der Einsatzbereich der Software, ihre Komponenten und ihr Entstehungskontext. Diese erste Übersicht kann in einer ersten grundsätzlichen Einschätzung der Software hinsichtlich ihrer Nützlichkeit für die Forschung und ihrer handwerklichen Qualität enden. Für die anschließende detaillierte Besprechung der Software und die Begründung der Einschätzung möchten wir die unten folgenden Kriterien vorschlagen. Alle Kriterien sind Ableitungen aus den eingangs erläuterten Prinzipien und Forderungen an Forschungssoftware.

...

## Kriterien zur Beurteilung von Software

> Software Engineering noch berücksichtigen?


### Wissenschaftliche Relevanz und Korrektheit

#### Einsatzgebiet und Relevanz
* Welches wissenschaftliche Problem versucht die Software zu lösen bzw. welche Aufgaben werden mittels der Software bei der Erfassung, der Verarbeitung oder der Analyse durchgeführt. Wie sind diese Probleme und Aufgaben von ihrer Relevanz und von ihrer Häufigkeit einzuschätzen?
* Wie löst die Software das gegebene Problem? Wie ist die grundsätzliche Funktionsweise konzipiert? Was sind die wesentlichen Bestandteile in Frontend und Backend (z.B. WebApp + Datenbank, CLI + Neuronales Netz, ...)?
* Wie funktioniert der (wissenschaftliche) Algorithmus, der mit der Software implementiert wurde (natürlich in kurzen Worten: Punktmuster gehen hinein, Magie passiert, Kennwerte kommen heraus)?
* Gibt es neben der Software noch weitere Alternativen, oder ist sie die einzige für diesen spezifischen Einsatzbereich?
* Wenn es Alternativen gibt: In welchen wissenschaftlichen und technischen Eigenschaften unterscheiden sie sich?
* Entspricht der archäologische Einsatz den generellen Anwendungszenarien, den die Entwickler\*innen vor Augen hatten?
* Wie ist die Software publiziert und verfügbar (Download, git) und ist sie zitierbar (Zenodo, [CCF](https://citation-file-format.github.io)), also für die wissenschaftliche Verwendung geeignet?

#### Korrektheit der Implementierung
* Sind die Algorithmen korrekt implementiert worden?
* Ist das wissenschaftliche Ergebnis jenseits aller technischen Unterschiede vergleichbar zu anderen Implementierungen/Tools?

### Bedienbarkeit

(Die folgenden technischen Merkmale sind Kriterien, die die Benutzbarkeit (Usability) betreffen. Weitere technische Merkmale aus einer eher Entwickler-zentrierten Perspektive betrachten wir weiter unten.)

#### Installation und Nutzungsumgebung
* Wie sind die Hardwareanforderungen? Sind sie dokumentiert und getestet?
* Auf welchen Endgeräten? (Mobil, Desktop, Web)
* Lauffähigkeit auf welchen Betriebssystemen?
* Installation oder Portable? Webapp? Kann die Software auch ohne Admin-Rechte installiert werden?
* Werden zum Betrieb der Software weitere Programme benötigt, müssen Einstellungen am eigenen System geändert werden?
* Wird die Installation mit einem Assistenten unterstützt? Welche Kompetenzen setzt die Installation voraus (Erfahrungen mit GitHub, mit der Commando Prompt)? Ist der Installationsvorgang ausreichend dokumentiert?
* Läuft die Software auf einer Infrastruktur die mir selbst nicht gehört und die ggf. in Zukunft abgeschaltet werden könnte?
* Wie stabil verhält sich die Software?
* Wie ist das Laufzeitverhalten? (Braucht die Software unnötig lange im Vergleich zu anderen vergleichbaren Programmen?)
* Ist der parallele Betrieb mit weiteren Anwendungen auf einem für den Aufgabenbereich typischen Rechner möglich oder werden Prozesse übermäßig verlangsamt, die Anwendung stürzt gar ab?

#### Interface
* Wie intuitiv verständlich ist das Arbeiten mit der Software?
* Entsprechen etwa die Benennung der Kommandos, die Anordnung der Menüs oder die Abfolge der vorzunehmenden Aufgaben den Gewohnheiten, oder kommen der praktischen Arbeit entgegen?
* Gibt die Software plausible Fehlermeldungen aus? Gibt es einen Log um Fehler nachvollziehen zu können?
* In welchen Sprachen werden Nutzeroberflächen, Menüs und Hilfen angeboten?
* Beachtet die Software lokale Anpassungen (andere Einheiten, andere Gepflogenheiten der Forscher in Land XYZ etc.)?
* Müssen eigens zur Nutzung der Software bestimmte Kompetenzen und Kenntnisse erworben werden? Davon zu trennen ist das gegebenenfalls nötige fachliche Vorwissen etwa bei der Nutzung von Statistikprogrammen.
* Ist die Anwendung behindertengerecht bedienbar und stützt sie sich auf Standards zur Barrierefreiheit wie z.B. [BITV2](http://www.gesetze-im-internet.de/bitv_2_0/BJNR184300011.html)?

#### Anschlussfähigkeit
* Welche Datenformate werden von der Software verarbeitet (Inputformate) und in welchen Datenformaten erfolgt die Ausgabe (Outputformate).
* Handelt es sich um offene oder proprietäre Datenformate?  
* Handelt es sich um zukunftsfähige Datenformate in der Community - Zur Orientierung schlagen wir aktuell (Stand Sommer 2020) die IT-Empfehlungen des Forschungsdatenzentrums Archäologie & Altertumswissenschaften, IANUS vor [@ianus-forschungsdatenzentrum_fur_archaologie__altertumswissenschaften_it-empfehlungen_2014].
* Hält sich die Anwendung an Standards welche im jeweiligen Kontext vorgegeben werden (z.B. W3C Standards zur Annotation oder auch archäologische Standards) und bildet diese standardkonform in den Daten ab?
* Können andere Forschungscommunities durch den Export spezifischer Datenformate profitieren? (z.B. RDF [@lassila1998resource](#lassila1998resource) für Linked Data, GeoJSON für GIS community, TEI für Texte etc.)?
* Ist die Anwendung sowohl für den Menschen als auch maschinenlesbar nutzbar (z.B. Gibt es Programmierschnittstellen (APIs) oder Webservices?)

#### Zugänglichkeit, Hilfefunktionen und Community
* Wo finde ich mehr Informationen zu dieser Software? Hyperlinks und Referenzen.
* Gibt es Anwendungsbeispiele der Software, ggf. Beispieldatensets und eine Anleitung für diese um ein Verständnis für die Funktionsweise zu entwickeln?
* Wird es dem Benutzer einfach gemacht die Software zu testen? Gibt es eine VM, einen Dockercontainer, einen Installer, andere Formen der Installierbarkeit ohne viel vorheriges Fachwissen?
* Gibt es ausreichend Tutorials für das Erlernen der Software? Hier sollte überprüft werden, ob die Tutorials auf unterschiedliches Vorwissen eingehen und gegebenenfalls auch kenntlich machen, welches Grundwissen, welche Erfahrungen unabdingbar sind. Ein weiterer Aspekt bei den Anleitungen, Tutorials und FAQs ist die Frage der Sprachen.
* Sind die Entwickler der Software aktiv und gut erreichbar? Wird die Software regelmäßig mit Updates versorgt?
* Wird die Software von einer Community getragen? Die Zahl der aktiven Nutzer eines Softwarewerkzeugs ist entscheidend dafür, ob man im Falle von Problemen schnell Hilfe googeln kann. Ist das Werkzeug das Erzeugnis eines einzigen Labors und wird von einer Hand voll eingeschworener Kollegen genutzt, oder handelt es sich um eine global etablierte Software mit Nutzerforum, Mailingliste und ganzen Büchern zur Nutzung in bestimmten Kontexten? Selbst wenn ein Werkzeug nur eine kleine Community besitzt kann dieser Mangel doch bis zu einem gewissen Grad von aktiven und leicht erreichbaren Entwicklern ausgeglichen werden, die bereit sind konkrete Fragen schnell und unkompliziert zu beantworten.
* Gibt es bereits eine speziell archäologische Community für diese Software? (SIG, ...).
* Haben ArchäologInnen bereits Best Practices für diese Software formuliert?
* Gibt es Archäologie-relevante erfolgreiche Projekte/Anwendungen, die von dieser Software bereits unterstützt wurden?

> [MT] folgendes wurde aus dem FAIR-Teil hier her verschoben; muss dann noch eingearbeitet Werden

Unter Nutzbarkeit wird oftmals allein UX Design verstanden, was Fragen der Gestaltung und Bedienbarkeit grafischer Oberflächen von Programmen (GUI) und Webseiten beinhaltet. Hier geht es dann um die Benutzbarkeit von Webanwendungen mit verschiedenen Endgeräten (Responsivität), die Strukturierung von Informationen über die Menüführung hinweg, die Verständlichkeit von Texten und auch die Barrierefreiheit (Farbkontraste, Screenreader u.ä.).

Usability umfasst aber noch mehr und schließt alle Aspekte ein, die eine fehlerfreie und effiziente Nutzung durch die Forscherin, den Forscher ermöglichen. Für Forschungssoftware ist es z.B. besonders wichtig, dass die Eingabe von Daten sich an der Eingabepraxis orientiert; wenn etwa die händische Eingabe von Werten sehr typisch ist, dann ist es Aufgabe einer guten Benutzbarkeit, diesen Vorgang mit vorgegebenen Feldformaten, automatischem Speichern, gut sichtbaren Feldern oder ähnlichem zu unterstützen. Ebenso muss Software die üblicherweise von Teams genutzt wird, in denen verschiedene Kompetenzen vertreten sind, ein Rechtemanagement vorsehen, das die unterschiedlichen Verantwortlichkeiten abbilden kann. Forschungssoftware wird nicht im leeren Raum genutzt, sondern trifft auf Erwartungen und Gewohnheiten der Nutzer\*innen, sowohl was ihre Bedienung betrifft, als auch die ergänzenden Angebote zur Unterstützung, wie Tutorials FAQs und ähnliches. Software, die für hochspezielle Fragestellungen verwendet wird, die auf einer Reihe vorhergehender Prozessschritte aufbaut, richtet sich an einen anderen Nutzerkreis, als Software, die Basisfunktionen erfüllt. Weil Forscher\*innen am besten beurteilen können, ob ihre Bedarfe und Gewohnheiten gut adressiert sind und die Forschungssoftware ihnen ein gutes Arbeiten erlaubt, gehört eine Beurteilung dieser Aspekte in die Rezension.
Ableiten lassen sich Kriterien, auf die sich die Nutzungserfahrung abbilden lässt aus der Forschung und den Referenz-Standards zur Usability. Zu nennen ist unter anderem der ISO/IEC 9126 Standard und spezifisch für Webanwendungen bilden die Empfehlungen und Standards des W3C [@noauthor_w3c_nodate](#noauthor_w3c_nodate).  


### Technik

#### Qualität der Implementierung
* Entspricht die Implementierung dem Stand der Technik?
* Ist die Implementierung performant? Für Webapplikationen und Plugins ist zu überprüfen, ob sie responsiv sind und über die verschiedenen Browser hinweg performant sind.
* Wie robust ist die Software gegenüber äußeren Einflüssen? Wie geht die Software mit Abstürzen/Stromausfall usw. um? Wird die Arbeit regelmäßig zwischengespeichert?

#### Dokumentation und Tests
* Ist eine Quellcodedokumentation vorhanden und ggf. eine HTML Variante davon verfügbar?
* Ist der Buildprozess dokumentiert und ggf. mittels Buildingscripts automatisiert?
* Gibt es eine Entwicklerdokumentation, sodass die Software leichter verstanden werden und ggf. erweitert werden kann?
* Ist die Dokumentation aktuell, wird gepflegt und deckt alle Funktionen des Programms ab?
* Hat der Quellcode Tests, die die Kernfunktionen des Programms testen und diese für andere Entwickler aufzeigen?
* Sind verwendete Algorithmen dokumentiert und hinreichend wissenschaftlich belegt?

#### Sicherheit
* Ist die Anwendung auf Sicherheitsanforderungen getestet worden? (Penetrationtests usw.), also ist sie leicht hackbar oder nicht?
* Setzt die Anwendung Standards zur IT Sicherheit welche von Behörden oder internationalen Organisationen empfohlen werden um? Beispiel [OWASP](https://de.wikipedia.org/wiki/Open_Web_Application_Security_Project)
* Hat die Anwendung Abhängigkeiten zu Softwarekomponenten welche bekannte Sicherheitslücken aufweisen und nicht mehr gepflegt werden? Hält dieser Zustand auf absehbare Zeit an?

### Rechtliche Fragen

#### Lizenzierung
* Ist die Software frei/Open Source?
* Sind die Ressourcen, die mit der Software mitgeliefert werden unter einer freien Datenlizenz verfügbar? (beachte: Copyright und Copyleft, Problem von Creative Commons `non commercial`)
* Erlaubt die Software nur die Erstellung von Daten, die unter einer gewissen Lizenz zur Verfügung gestellt werden können?
* Behält sich die Software Rechte an den von ihr erstellten Daten vor?

#### Datenschutz, Privacy, Datensparsamkeit
* Beachtet die Software die lokalen Gesetze in dem Land in dem sie eingesetzt werden soll? (Datenschutz, Kartendarstellungen etc.)?
* Welche Daten speichert die Anwendung zu welchem Zweck wie lange? Dienen diese Daten der Forschung bzw. helfen sie die Software zu verbessern?
* Ist die Software ohne Login anonym bedienbar?
* Benötigt die Software eine Internetverbindung und werden personenbezogene Daten an Dritte übertragen?

## Anmerkungen

<a name="myfootnote1">1</a>: Aufgeworfen und anschließend im Plenum des 9. Workshops der deutschen Sektion der CAA 2019 in Wilhelmshaven wurde die Frage nach den Inhalten einer Rezension von Software und Anwendungen für die Archäologie von Sophie Charlotte Schmidt, Kai-Christian Bruhn und Siegmund Freud. Anlässlich der Einrichtung der neuen Rubrik für solche Besprechungen in der vorliegenden Reihe haben wir das Thema aufgegriffen und möchten mit der vorliegenden Handreichung einen Beitrag zur Weiterentwicklung dieses wichtigen Themas leisten. Die Handreichung kann auch zur Orientierung bei Entscheidungen zum Einsatz einer Software in der eigenen Forschung dienen.

<a name="myfootnote2">2</a>: Angestoßen wird Letzteres insbesondere von Untersuchungen, die sich mit Software auseinandersetzt, die zur Diskrimination von Gruppen und Individuen führt, so etwa Facial-Recognition-Software, die ausschließlich auf die Erkennung hellhäutiger Menschen ausgerichtet ist [@breland_how_2017](#breland_how_2017).

## Bibliographie
