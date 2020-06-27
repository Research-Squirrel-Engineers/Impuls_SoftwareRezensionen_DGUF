---
title: Handreichung zur Rezension von Forschungssoftware - Kriterien für "gute" Forschungssoftware
layout: draft
author:
  - Anne Klammt, Deutsches Forum für Kunstgeschichte Paris
  - Timo Homburg
  - Clemens Schmid, Max-Planck-Institut für Menschheitsgeschichte Jena
  - Sophie Charlotte Schmidt
  - Lutz Schubert
  - Florian Thiery, Research Squirrel Engineers
  - Martina Trognitz, Austrian Centre for Digital Humanities and Cultural Heritage, ÖAW Wien

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
    * [FAIR Prinzipien](#FAIR-Prinzipien)
    * [Open Science](#open-science)
    * [CARE Prinzipien](#care-prinzipien) (https://www.gida-global.org/care)
* [Anwendungsbereich dieser Handreichung](Anwendungsbereich-dieser-Handreichung)
* [Vorgehensweise bei der Rezension von Software](#Vorgehensweise-bei-der-Rezension-von-Software)
* [Kriterien zur Beurteilung von Software](#Kriterien-zur-Beurteilung-von-Software)
  * ... alle Unterpunkte ab [dort](#Kriterien-zur-Beurteilung-von-Software)
* Tabellarische Zusammenfassung?

---

## Zielsetzung des Beitrags<sup>[1](#myfootnote1)</sup>
Ziel dieses Beitrags ist es Fragen und Themen aufzuwerfen, die für die Rezension von Forschungssoftware und im Forschungsprozess eingesetzten digitalen Werkzeugen relevant sind.

Die Beurteilung einer wissenschaftlichen Publikation ist eine traditionsreiche Form des wissenschaftlichen Diskurses. Entsprechend gibt es ein unausgesprochenes Verständnis davon, was eine gute Rezension ausmacht. Unterstützt werden kann dies durch redaktionelle Maßnahmen zur Qualitätssicherung wie Hinweise für die/den Rezensentin/Rezensenten oder - wie es die DGUF mit den Archäologischen Informationen praktiziert - eines Reviews der angefertigten Rezension. Die Frage ist jedoch, was sollte eine gute Rezension von Software für den Einsatz in der Archäologie ausmachen? Geht es dabei allein um Aspekte der Nutzbarkeit, der Usability? Sollten nicht auch Fragen der Nachhaltigkeit und der Anschlussfähigkeit einfließen? Müsste nicht auch betrachtet werden, ob es eine wissenschaftliche Dokumentation und Diskussion der rechnerischen Verfahren gibt - etwa bei den vielen Interpolationen von Daten mit Raumbezug, die moderne GIS-Softwarepakete bieten?

In dieser Handreichung erläutern wir einige Kriterien für gute Forschungssoftware. Dabei folgen wir den Empfehlungen der DFG und weisen auf sogenannte "open standards" hin. Software greift im- und explizit tief in den Forschungsprozess ein (für die Archäologie siehe z.B. [@schmidt_marwick_2020](#schmidt_marwick_2020)) und nur durch die Offenlegung von Quellcode ist eine Bewertbarkeit der durch die Software geleisteten Abläufe gewährleistet.

Wir empfehlen eine Vorgehensweise zur Softwarerezension und sammeln Kriterien, die für die Bewertung einer Software von Bedeutung sein können. Aufgrund der Vielfalt der möglichen Besprechungsgegenstände werden nicht in jedem Fall alle Kriterien von Bedeutung sein.

Die hier vorgestellten Überlegungen, Kriterien und Vorschläge sollen den Rezensentinnen und Rezensenten als Arbeitserleichterung dienen. Diskussionsbeiträge sowie Anregungen zu diesen Beitrag sind erwünscht. Dazu können entweder die Autoren kontaktiert werden oder -- hier website und Kontaktdaten einfügen ? -- genutzt werden.

## Forschungssoftware

Die weiter unten vorgestellten Kriterien zur Rezension von Software zielen primär auf die Begutachtung von Forschungssoftware ab. Unter Forschungssoftware verstehen wir Software, die mit Fokus auf einen Einsatz in der Forschung entwickelt wurde, also um Forschungsdaten zu erzeugen, zu verarbeiten oder zu analysieren [@hettrick_2014_14809](#hettrick_2014_14809). Dies sind beispielsweise Programme, die der Kalibrierung und Umrechnung von Messwerten, der Annotation von Texten und Objekten, oder der Bereitstellung sowie der Verknüpfung und Visualisierung fachlich relevanter Vokabulare dienen.

Forschungssoftware kann entweder für einen sehr spezifischen Bedarf oder einen allgemeinen Anwendungsbereich entwickelt worden. Sie ist dabei stets Teil des Forschungsprozesses, der in allen seinen Punkten nachvollziehbar und soweit möglich reproduzierbar sein muss.

Im Gegensatz zu Forschungssoftware steht Software, die zur Nutzung spezifischer Geräte erforderlich ist, wie etwa zur Vermessung, zur fotografischen Dokumentation oder zur Analyse von Oberflächen und Inhaltsstoffen. Häufig handelt es sich um proprietäre Software, die zusammen mit der Hardware vertrieben wird. Obwohl sie im Forschungsprozess eingesetzt wird, entspricht sie nicht unserem Verständnis von Forschungssoftware. Auch digitale Werkzeuge, die eine erhebliche Rolle in der praktischen Arbeit inne haben, jedoch keinen eigentlichen Anteil an der Erhebung, Bearbeitung und Analyse der Daten haben, sind in unserem Sinne keine Forschungssoftware. Trotzdem können auch diese Tools mittels der vorgestellten Kriterien beurteilt werden.

> NFDI Abstracts zu Research Software

> https://www.dfg.de/download/pdf/foerderung/programme/nfdi/nfdi_konferenz_2020/nfdi4rse_abstract.pdf

> https://www.dfg.de/download/pdf/foerderung/programme/nfdi/nfdi_konferenz_2020/nfdixcs_abstract.pdf

### Forschungssoftware als wissenschaftliche Leistung

In der modernen Forschung ist ein Arbeiten ohne digitale Werkzeuge undenkbar. Dies trifft ebenfalls auf die historische und altertumswissenschaftliche Forschung zu. Mit dem Aufschwung der Digital Humanities wird Forschungssoftware weiterhin und auch zunehmend ein wichtiger Bestandteil des Forschungsprozesses sein.

Trotz der tragenden Rolle, die Forschungssoftware in manch einem Projekt hat, wird die Leistung der Personen, die hinter der Entwicklung und Programmierung stehen akademisch nicht anerkannt ([@hettrick_2017](#hettrick_2017), [@scheliga_pampel_2017](#scheliga_pampel_2017) und [@katerbow_2018](#katerbow_2018)). Jedoch fließen einerseits bei der Entwicklung von Forschungssoftware teilweise jahrelange technische Erfahrung und Praxis ein. Andererseits wird aber auch Wissen über wissenschaftliche Standards und Praktiken angewendet. Durch die Umsetzung in Code wird Praxis und Wissen explizit gemacht und weiterentwickelt. Diese Leistungen gilt es zu würdigen und sichtbar zu machen ([@scheliga_pampel_2017](#scheliga_pampel_2017), [@katerbow_2018](#katerbow_2018) sowie [@helmholtz_web](#helmholtz_web)).

Als erster Schritt in Richtung Sichtbarmachung wurde 2012 die Berufsbezeichnung des "Software Research Engineers" (RSE, RSEng) geprägt ([@hettrick_2017](#hettrick_2017) und [@baxter_2012](#baxter_2012)). Mittlerweile hat sich auch eine aktive, internationale und interdisziplinäre Gemeinschaft gebildet, die unter anderem auch in Deutschland als de-RSE e.V. tätig ist, Konferenzen organisiert und Empfehlungen gibt ([@anzt_environment_2020](#anzt_environment_2020)). Auch im internationalen Kontext entwickeln sich immer mehr nationale [RSE Sektionen](https://sorse.github.io/contact/chapters/) und gemeinsam von der RSE Community organisierte Konferenzen, wie z.B. [SORSE](https://sorse.github.io).

> Sichtbarmachung über Publikation
> ([@anzt_environment_2020](#anzt_environment_2020)) -> p.10, `Research Software Discovery and Publication`

> Publikation rezensieren; ganz so wie es der Praxis in der altertumswissenschaftlichen Forschung entspricht

Eine weiterer Baustein zur Sichtbarmachung ist die Rezension von Forschungssoftware. Mit der Einführung der Rezensionskategorie "Archäoinformatik" intendiert die Redaktion der Archäologischen Informationen genau dies. Durch eine dedizierte Rezension von Software analog zu Rezensionen wissenschaftlicher Publikationen, wird die wissenschaftliche Leistung der Autoren und Autorinnen von Forschungssoftware mittels gewohnten Formaten sichtbar und anerkannt.

### Herausforderungen für die nachhaltige Entwicklung, Bereitstellung und Pflege von Forschungssoftware

> [MT] Wollen wir dieses Fass in diesem Beitrag wirklich aufmachen?
> Ich denke, dass wir mit (guter) Forschungssoftware und dem Kriterienkatalog schon genug zu tun haben.
> Was wir tun könnten ist am Ende noch einen Abschnitt einzufügen nach dem Motto 'was wir nicht behandelt haben, aber im Zusammenhang mit Forschungssoftware noch nicht zufriedenstellend gelöst wurde'. Dort könnte man dann kurz und bündig auf dieses und anderes verweisen
> Oh, oder wir fügen das kurz und knapp unter F bei FAIR ein.


> ([@bach_dersews19](#bach_dersews19)) https://de-rse.org/de/conf2019/talk/PVEXDH/slides.pdf

> ([@anzt_environment_2020](#anzt_environment_2020)) -> p.2, re. oben

### Gute Forschungssoftware

Um überhaupt Kriterien zur Rezension und Bewertung von Forschungssoftware aufstellen zu können, stellt sich zunächst die Frage was überhaupt eine gute und modernen Standards entsprechende Forschungssoftware ausmacht.

Da die Software ein integraler Bestandteil des Forschungsprozesses ist, gelten zunächst die Leitlinien zur Sicherung guter wissenschaftlicher Praxis, wie sie die DFG ([@deutsche_forschungsgemeinschaft_2019](#deutsche_forschungsgemeinschaft_2019)) fordert. Allein hieraus ergeben sich schon wichtige Anforderungen wie die Einhaltung und Etablierung von Standards und Methoden, eine nachvollziehbare Dokumentation des Weges zu den Ergebnissen sowie der öffentlicher Zugang der Ergebnisse und die Archivierung der Materialien die zu einem Forschungsergebnis geführt haben.

Wir möchten auf ein paar der Aspekte die sich aus den DFG-Leitlinien ergeben, näher eingehen. Denn sie entsprechen auch dem internationalen Konsens mit etablierten Prinzipien: die in der Erläuterung zu Leitlinie 13 - Herstellung von öffentlichem Zugang zu Forschungsergebnissen - genannten FAIR-Prinzipien, sowie die Prinzipien der Offenen Wissenschaft (Open Science). Natürlich betreffen diese Prinzipien auch weitere Leitlinien der DFG. Außerdem sollen die CARE-Prinzipien, welche in den Leitlinien 2 und 10 der DFG anklingen, erläutert werden. Hinweise zur Umsetzung der DFG Leitlinien in Bezug auf Forschungssoftware sind auch auf [@forschungsdaten_info_dfg](#forschungsdaten_info_dfg) zu finden.

#### FAIR-Prinzipien
Die FAIR-Prinzipien wurden 2016 als FAIR Data Principles veröffentlicht [@wilkinson_2016](#wilkinson_2016). Sie zielen primär auf Forschungsdaten und deren Metadaten ab und fordern dass diese auffindbar (Findable), zugänglich (Accessible), interoperabel (Interoperable) und reusable (Nachnutzbar) sind. Die Prinzipien können auch auf Forschungssoftware und deren Metadaten übertragen werden [@lamprecht_towards_2019](#lamprecht_towards_2019).

Die Anwendung von FAIR-Prinzipien fördert die Qualität der Software hinsichtlich der grundsätzlichen Ansprüche an Interoperabilität bei der Verwendung in einem Workflow und der Verwendung von Standards und etablierten Paradigmen des Programmierens und der Dokumentation. Die FAIR-Prinzipien beziehen sich nicht auf die wissenschaftliche Qualität des Tools. Dennoch ergeben sich eine Anzahl von Kritertien, die in die Beurteilung einer Forschungssoftware einfließen und von Angaben, die im Rahmen der Rezension als Serviceleistung zu erbringen sind, wie die Autorenschaft, das zur Speicherung verwendete Repositorium oder mögliche nötige Voraussetzungen zur Verwendbarkeit.

Ein Fokus der FAIR-Prinzipien ist, dass Daten, bzw. Forschungssoftware, und Metadaten auch maschinell lesbar und verarbeitbar sind. Dies betrifft vor allem die Prinzipien 'Accessible' und 'Interoperable'.

##### Findable (Auffindbar)

Software wird durch die Speicherung zusammen mit ihren Metadaten in dedizierten Softwarerepositorien auffindbar, welche kommerziell, community-basiert und in vielen weiteren Formen starke Impulse für die Entwicklung der wissenschaftlichen Infrastrukturen geben. Die Auffindbarkeit wird durch die fachwissenschaftliche Einbindung und die klassische Arbeit von Forschungsinfrastrukturen zusätzlich erhöht, da sie Aufbau, Pflege und Anwendung von kontrolliertem Vokabular und Metadatenstandards zur Indexierung betreiben ([@lamprecht_towards_2019](#lamprecht_towards_2019) und [@anzt_environment_2020, 10](#anzt_environment_2020)).

Die Vergabe von persistenten URLs durch Repositorien, sowie die Nennung der Autorenschaft ermöglicht das Zitieren von Forschungssoftware. Wichtig ist hierbei, dass Software, da sie im Gegensatz zu herkömmlichen Publikationen kontinuierlich weiterentwickelt wird, in unterschiedlichen Entwicklungsständen abgelegt wird, damit bestimmte Versionen zitiert werden können [@forschungsdaten_info_dfg](#forschungsdaten_info_dfg).


##### Accessible (Zugänglich)

Entsprechend den FAIR-Prinzipien sollte Software und die sie beschreibenden Metadaten über ihre persistente URL erreichbar sein. Dies sollte auch maschinell über ein offenes und standardisierte Kommunikationsprotokoll möglich sein [@lamprecht_towards_2019](#lamprecht_towards_2019).

Weitere Aspekte, welche die Zugänglichkeit erleichtern, sind die Verfügbarkeit für verschiedene Betriebssysteme, sowie technische Anforderungen welche von aktuell verbreiteten Geräten geleistet werden können. Eine verständliche Anleitung zur Nutzung des Programms verbessert die Zugänglichkeit im Sinne der Nutzbarkeit.

> [MT] 'kostenlos' entfernt. FAIR fordert das nicht. Wir könnten aber 'Kosten' als Kriterium einfügen

##### Interoperable (Interoperabel)
- die Offenlegung des Quellcodes
- die Verwendung und Umsetzung von Standards

Interoperabilität von Software kann sich auf die Verknüpfungsmöglichkeiten von Prozessen beziehen, die bei der Erzeugung, Bearbeitung oder Analyse nacheinander notwendig werden (horizontale Dimension). Diese Prozessschritte müssen nicht innerhalb einer Software ablaufen, sondern werden häufig über Protokolle, Schnittstellen und Ausgabeformate als Durchlauf durch mehrere Programme ermöglicht. Interoperabilität kann aber auch als die Zusammenarbeit verschiedener digitaler Objekte für die Ausführung eines Prozesses bedeuten (vertikale Dimension) [@lamprecht_towards_2019, 10 f.](#lamprecht_towards_2019). Wenn dabei eine Software z. B. nur mit einem Betriebssystem arbeiten kann, ist sie weniger interoperabel, als solche, die plattformunabhängig programmiert ist

##### Reusable (Nachnutzbar)

Mit der Forderung nach der Offenlegung des Quellcodes (Open Source), entspricht dem Gedanken der Nachnutzbarkeit (reusable). Vielfach wird er  noch erweitert um die Forderung, den Code zudem frei nutzbar zur Verfügung zu stellen (Free Source). Letzteres wird als FOSS (Free/Libre Open Source Software) bezeichnet und wird in Deutschland z.B. von anwendungsbezogenen Wissenschaftler\*innen und Entwickler\*innen aus der Geoinformatik vertreten (FOSSGIS e.V.). oder von Research-Software-Engineers in der "de-RSE e.V." [@anzt_environment_2020](#anzt_environment_2020).

Code kann nur dann von anderen nachgenutzt werden, wenn er unter einer dementsprechenden Lizenz zur Verfügung gestellt wird...
>[SCS: Hier muss noch was]
> [MT] das mit dem Open sehe ich an dieser stelle etwas kritisch. FAIR beinhaltet nämlich ganz bewusst nicht die Forderung nach Open.

#### Open Science

(Open Science; Open Data, Open Source)

Open Science (Offene Wissenschaft) bezeichnet eine Wissenschaftspraxis, deren Ziel ein transparenter Forschungsprozess und eine Zugänglichkeit der Ergebnissen für die Wiederverwendung und Weiterentwicklung ist ( https://doi.org/10.5281/zenodo.1212496 ?). Für offene Forschungssoftware gilt, dass ihr Quellcode zugänglich und für die Weiterentwicklung lizenziert sein muss (https://book.fosteropenscience.eu/en/02OpenScienceBasics/03OpenResearchSoftwareAndOpenSource.html)

In den "Leitlinien zur Sicherung guter wissenschaftlicher Praxis" weist die DFG darauf hin, dass für die Qualitätssicherung
"[...] die Auswahl und Nutzung  von  Forschungssoftware,  deren  Entwicklung  und  Programmierung" von Bedeutung sind.
Unabhängig von dem Fachgebiet hat die Herkunft der Software dargestellt zu werden, und der Quellcode öffentlich zugänglicher Software muss "persistent, zitierbar und dokumentiert sein", um die Replizierbarkeit und Reproduzierbarkeit zu gewährleisten.  [@deutsche_forschungsgemeinschaft_2019, 14-15](#deutsche_forschungsgemeinschaft_2019)

Helmholtz-Zentrum: https://os.helmholtz.de/open-science-in-der-helmholtz-gemeinschaft/forschungssoftware/  

Dieser Anforderungen können anhand der FAIR- und CARE-Prinzipien, wie sie für Datenmanagement bestehen, genauer erläutert werden:

>[SCS: Braucht noch Infos zu Open Data (aber nich zu viel, weil Fokus ja woanders liegt)]

> [MT]: FAIR ist nicht automatisch gleich Open(!); Deshalb habe ich das in der Gliederung noch umgeordnet: zuerst FAIR, dann Open Science und dann noch CARE und Ethik. Wenn man FAIR macht ist es gut, wenn man Open Science praktiziert noch besser und wenn man dann auch noch CARE berücksichtigt kann man eigentlich nichts mehr besser machen

#### CARE-Prinzipien

Im Bereich des Datenmanagements wurde darauf hingewiesen, dass es durchaus Gründe gibt, Daten zurückzuhalten, insbesondere wenn es um Rechte Indigener Bevölkerungen geht (siehe auch Marwick und Birch). Von diesen wurden weitere Richtlinien, die mit CARE abzukürzen sind entwickelt (https://www.gida-global.org/care):



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
> [MT] dieser Teil passt noch nicht ganz in die Gliederung

Es bedarf also weiterer Kriterien, um festzustellen, was eine gute Forschungssoftware ist, und um in einer Rezension die Leistung der Entwickler\*innen angemessen zu beurteilen.
Die Beschäftigung mit der wissenschaftlichen Nutzung, also den Nutzungsszenarien von Forschungssoftware ist in der archäologischen Forschung bereits verankert (bezogen auf die in der Ur- und Frühgeschichte und der Archäologie des Mittelalters betriebene Forschung). Die AG CAA e.V. führt seit 2010 jährlich Workshops durch, in denen Tutorials zu Software durchgeführt und Fallbeispiele diskutiert werden sowie Entwickler\*innen ihre Tools zur Diskussion stellen. Auch in den Fachzeitschriften und Tagungen mit anderen thematischen, räumlichen und zeitlichen Schwerpunkten werden in gewisser Regelmäßigkeit entsprechende Fallbeispiele publiziert. Und Tagungen, Sammelbände uns Ausstellungen nehmen sich bestimmter Themen an, wie der Auswertung von LIDAR-Daten oder 3D-Rekonstruktionen (LIT./LIT).

Mit den Fallbeispielen verwandt, aber aus einem anderen Fokus geschrieben, sind Publikationen von Forschungsergebnissen, die unter dem Einsatz spezifischer Forschungssoftware erzielt wurden. In eigenen Abschnitten zur Vorgehensweise der Untersuchung wird hier auch die Software beschrieben jedoch nur insoweit, wie es für das Verständnis der methodischen Vorgehensweise erforderlich ist (exemplarisch: Zimmermann, Saile, Freund). Während dabei Aspekte wie die Oberflächengestaltung kaum eine Rolle spielen, werden je nach Qualität der Arbeit die zugrundeliegenden Berechnungswege, die Modellierung der Daten und die Wechselbeziehung mit dem Forschungsdesign fassbar. Aus ihnen lassen sich im Idealfall Ansätze zur Weiterentwicklung der Software oder auch zur Ergänzung weiterer mathematischer Verfahren ableiten. Eröffnen die zuvor als Fallbeispiele eingeordneten Publikationen der Forschung Software, kann die fachwissenschaftliche Forschung durch die intensive Nutzung und Kritik der Ergebnisse die Entwicklung der Software vorantreiben. Letzteres ist auch der Fall bei Arbeiten einer insgesamt kleineren Anzahl von Autorinnen und Autoren, die sich in ihren Beiträgen mit der Leistungsfähigkeit und den Parametern  der Rechnungen selbst, bzw. den Algorithmen auseinandersetzen (exemplarisch: Irmela Herzog 2012, 2014 und Gerhard Roth LIT).

Zusammengefasst können aus den eigenen fachlichen Traditionen der Archäologie Kriterien für eine Rezension abgeleitet werden, die das Potenzial für die wissenschaftliche Arbeit und die Passung zum Forschungsfeld beschreibt.


##  Anwendungsbereich dieser Handreichung

Forschungssoftware

Hardwarespezifische Software
, aber ihre Programmierung ist nicht transparent, vielfach werden zudem Daten in proprietären Formaten erzeugt. Entsprechend können zwar der Umgang mit der Software und die Produktqualität aus Sicht der Nutzerinnen als Erfahrungswerte beschrieben werden, aber es können keine begründeten Aussagen zur Performanz unter veränderten Bedingungen, zur Stabilität und anderes getroffen werden. Einige der im folgenden dargestellten Kriterien zur Rezension von Forschungssoftware können somit auf proprietäre Software angewendet werden und eine Berücksichtigung der Aspekte wird ausdrücklich empfohlen.

Weitere digitale Werkzeuge (*tools*)
 Ihre Passgenauigkeit setzt wie bei der eigentlichen Forschungssoftware eine genaue Kenntnis des Arbeitsfelds voraus und entsprechend sind nicht selten stehen die eigenen Kolleg\*innen hinter der Entwicklung. Eine angemessene Besprechung der Software kann hier sehr direkt zur Verbesserung des Tools führen.


## Vorgehensweise bei der Rezension von Software

In Vorbereitung zur Vormulierung einer Softwarerezension ist es angemessen, zunächst möglichst ihre gesamte Dokumentation zumindest zu visitieren. Das kann Webseiten, Handbücher und wissenschaftliche Publikationen einschließen. Sofern es nicht ohnehin schon erfolgt ist, sollte die Software installiert und mit für sie typischen Testszenarien konfrontiert werden. Das heißt, die oder der Rezensent*In sollte die Software selbst erprobt haben. Zuletzt ist ein Blick in den Programmcode -- sofern offen verfügbar -- sinnvoll.

Der Rezensionstext sollte wie die Besprechung einer Publikation zunächst mit einer kurzen, überblicksartigen Beschreibung der Software beginnen. Zusammengefasst vorgestellt werden sollte ihr Einsatzbereich, ihre Komponenten und ihr Entstehungskontext. Für die anschließende detaillierte Besprechung und Einschätzung möchten wir die unten folgenden Kriterien vorschlagen. Diese Kriterien sind konkrete Ableitungen aus den eingangs abstrakt erläuterten Prinzipien und Anforderungen an Forschungssoftware. Nicht allen Kriterien kann und muss das selbe Gewicht zukommen - es ist der oder dem Rezensent*In überlassen Schwerpunkte zu setzen. Zuletzt sollten die Ergebnisse der Betrachtung in einer Stellungnahme zusammengefasst werden, die die Software hinsichtlich ihrer Nützlichkeit, ihrer Bedienbarkeit, ihrer handwerklichen Qualität und ihrer Position in Relation zu den Idealen guter Forschungssoftware (z.B. FAIR und CARE), beurteilt.

Der Umfang der Rezension sollte 1000-2000 Worte nicht übersteigen.

## Kriterien zur Beurteilung von Software

Im folgenden stellen wir einen Katalog von Kriterien vor, die für die Beurteilung wissenschaftlicher Software relevant sein können. Er ist weder vollständig noch au­to­ri­ta­tiv. Nicht jeder gelistete Aspekt ist für jede Software relevant und gegebenfalls ist es nicht möglich, die entsprechende Information abzufragen oder eine gewählte Lösung zu beurteilen.

### Wissenschaftliche Relevanz und Korrektheit

Wissenschaftliche Software ist nur dann gut, wenn sie einen konkreten Zweck verfolgt und ihre Aufgabe (im wesentlichen) korrekt erfüllt. Tut sie das nicht, so sind alle weiteren Beurteilungskritierien hinfällig. Die Frage der Relevanz sollte für eine archäologische Softwarerezension auf die speziellen Bedingungen und Erfordernisse des Faches Rücksicht nehmen. Demgegenüber mitunter deutlich schwierigier zu beurteilen ist die Korrektheit der Ergebnisse einer Software. Dieses Problem gliedert sich in mehrere Aspekte: Zunächst stellt sich die sehr technische Frage, ob die in der Dokumentation genannten Algorithmen fehlerfrei in Programmcode ausgedrückt wurden. Meist ist schon eine Prüfung dieses Aspekts nicht trivial und übersteigt den Rahmen einer Rezension. Darüber hinaus versprechen wissenschaftliche Softwarewerkzeuge implizit oder explizit, die Beantwortung wissenschaftlicher Fragestellungen zu ermöglichen oder zumindest zu vereinfachen. Eine GIS-Applikation zur Analyse von Punktmustern kann etwa für den Zweck konzipiert sein menschliches Siedlungsverhalten nachherzusagen. Die Frage, ob der Algorithmus dazu semantisch überhaupt in der Lage ist, kann den Umfang einer Rezension bei weitem übersteigen und muss gegebenfalls mit einer kritischen Benenennung der Problemstellung übergangen werden.

#### Einsatzgebiet und Relevanz
* Welches Problem versucht die Software zu lösen bzw. welche Aufgaben werden mittels der Software bei der Erfassung, der Verarbeitung oder der Analyse durchgeführt. Wie sind diese Probleme und Aufgaben von ihrer Relevanz und von ihrer Häufigkeit einzuschätzen?
* Wie löst die Software das gegebene Problem? Wie ist die grundsätzliche Funktionsweise konzipiert? Was sind die wesentlichen Bestandteile in Frontend und Backend (z.B. WebApp + Datenbank, CLI + Neuronales Netz, ...)?
* Wie funktioniert der (wissenschaftliche) Algorithmus, der mit der Software implementiert wurde (natürlich in kurzen Worten: Punktmuster gehen hinein, Magie passiert, Kennwerte kommen heraus)?
* Gibt es neben der Software noch weitere Alternativen, oder ist sie die einzige für diesen spezifischen Einsatzbereich?
* Wenn es Alternativen gibt: In welchen wissenschaftlichen und technischen Eigenschaften unterscheiden sie sich?
* Entspricht der archäologische Einsatz den generellen Anwendungszenarien, den die Entwickler\*innen vor Augen hatten?
* Wie ist die Software publiziert und verfügbar (Download, git) und ist sie zitierbar (Zenodo, [CCF](https://citation-file-format.github.io)), also für die wissenschaftliche Verwendung geeignet?

#### Korrektheit der Implementierung
* Sind die Algorithmen korrekt implementiert worden?
* Ist das wissenschaftliche Ergebnis jenseits aller technischen Unterschiede vergleichbar zu anderen Implementierungen/Tools
* Ist die Behauptung, eine bestimmte wissenschaftliche Fragestellung mit gewähltem Algorithmus lösen zu können, korrekt?

### Bedienbarkeit

Die Frage der Bedienbarkeit von Software führt zur Qualität des Software Engineering. Das ist ihre "handwerkliche" Qualität, denn Software Engineering erfordert spezifische Kompetenzen und Skills. Es baut auf eigene Wissensbestände zu ihrer Vermittlung und hinter der handwerklichen Qualität steht eine eigene Forschung aus den anwendungsbezogenen Wissenschaften. Wie bei handwerklichen Produkten ist die Qualität aber auch für die Nutzer\*innen erkennbar und zwar, wenn es um alle Aspekte der Nutzbarkeit geht.

Davon etwas abgesetzt ist die Qualität des Programmcodes, die Art der Dokumentation, die Einbindung und Bezugnahme auf die Entwicklungen und Communities im Software Engineering. Letzteres sind Kriterien, die unmittelbar mit der Zukunftsfähigkeit der Software verbunden sind und daher ein wichtiges Merkmal sind, wenn es um den Einsatz von Software auf institutioneller Ebene oder für langfristige Vorhaben geht.

Die folgenden technischen Merkmale sind Kriterien, die die Benutzbarkeit (Usability) betreffen. Weitere technische Merkmale aus einer eher Entwickler-zentrierten Perspektive betrachten wir weiter unten.

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

Weiter oben haben wir die handwerkliche Qualität von Software aus der Anwender-Perspektive betrachtet. Hier geht es nun um Fragen, die direkt den Programmcode betreffen. Eine Beurteilung derselben erfordert also, den Programmcode herunterzuladen und in Stichproben durchzusehen. Das ist bei proprietärer Software meist nicht möglich.

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

Software muss sich wie alle wissenschaftlichen Werkzeuge in einen rechtlichen Rahmen einordnen. Dabei sind die Aspekte Lizenzierung und Datenschutz von besonderer Bedeutung.

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

> [MT] Abschnitt aus theoretischem Teil, der hier irgendwo in die Kriterienliste eingearbeitet werden Müsste

## Anmerkungen

<a name="myfootnote1">1</a>: Aufgeworfen und anschließend im Plenum des 9. Workshops der deutschen Sektion der CAA 2019 in Wilhelmshaven wurde die Frage nach den Inhalten einer Rezension von Software und Anwendungen für die Archäologie von Sophie Charlotte Schmidt, Kai-Christian Bruhn und Siegmund Freud. Anlässlich der Einrichtung der neuen Rubrik für solche Besprechungen in der vorliegenden Reihe haben wir das Thema aufgegriffen und möchten mit der vorliegenden Handreichung einen Beitrag zur Weiterentwicklung dieses wichtigen Themas leisten. Die Handreichung kann auch zur Orientierung bei Entscheidungen zum Einsatz einer Software in der eigenen Forschung dienen.

<a name="myfootnote2">2</a>: Angestoßen wird Letzteres insbesondere von Untersuchungen, die sich mit Software auseinandersetzt, die zur Diskrimination von Gruppen und Individuen führt, so etwa Facial-Recognition-Software, die ausschließlich auf die Erkennung hellhäutiger Menschen ausgerichtet ist [@breland_how_2017](#breland_how_2017).

## Bibliographie
