---
title: Diskussionsbeitrag - Handreichung zur Rezension von Forschungssoftware - Fragenkatalog für "gute" Forschungssoftware

layout: draft
author:
  - 
    name: Anne Klammt
    affiliation: Deutsches Forum für Kunstgeschichte Paris 
    orcid: 0000-0003-3697-9241
  - 
    name: Timo Homburg
    affiliation: Hochschule Mainz 
    orcid: 0000-0002-9499-5840
  -  
    name: Clemens Schmid
    affiliation: Max-Planck-Institut für Menschheitsgeschichte Jena
    orcid: 0000-0003-3448-5715
  - 
    name: Sophie Charlotte Schmidt
    affiliation: 
    orcid: 0000-0003-4696-2101
  - 
    name: Lutz Schubert
    affiliation:
    orcid:
  - 
    name: Florian Thiery
    affiliation: Research Squirrel Engineers
    orcid: 0000-0002-3246-3531
  - 
    name: Martina Trognitz
    affiliation: Austrian Centre for Digital Humanities and Cultural Heritage, ÖAW Wien
    orcid: 0000-0003-0485-6861
    
bibliography: literatur.bib
csl: apa-6th-edition.csl

---

<div id="zitat" markdown="1">
"Die Leitfunde werden dann im Computer durch die Programme ARCH und GGG einer Seriation unterzogen. Diese Programme entwickelte E. Kämmerer. Eine Beschreibung ist der Arbeit beigefügt. Die Programme DOK und ARCH z. Zt. für 600 Typen in 2000 Funden dimensioniert, sind am Rechner TR 440 beim Großrechenzentrum für die Wissenschaft in Berlin in Anwendung." [@goldmann_chronologische_1972, 98.](#goldmann_chronologische_1972)
</div>

---


## Zielsetzung des Beitrags
Ziel dieses Beitrags<sup>[1](#myfootnote1)</sup> ist es Fragen und Themen aufzuwerfen, die für die Rezension von Forschungssoftware und im Forschungsprozess eingesetzten digitalen Werkzeugen relevant sind.

Die Beurteilung einer Publikation ist eine traditionsreiche Form des wissenschaftlichen Diskurses. Entsprechend gibt es ein unausgesprochenes Verständnis davon, was eine Rezension umfasst. Unterstützt werden kann dies durch redaktionelle Maßnahmen zur Qualitätssicherung wie Hinweise für die/den Rezensentin/Rezensenten oder - wie es die DGUF mit den Archäologischen Informationen praktiziert - eines Reviews der angefertigten Rezension. Die Frage ist jedoch, was sollte eine gute Rezension von Software für den Einsatz in der Archäologie ausmachen? Geht es alleine, um die Beurteilung des Beitrags, den Software zur Lösung einer wissenschaftlichen Problemstellung beiträgt? Geht es nicht auch um Aspekte der Nutzbarkeit, der Nachhaltigkeit und Anschlussfähigkeit? Müsste nicht auch betrachtet werden, ob die Software selbst eine wissenschaftlichen Beitrag darstellt? Welche Rolle spielt die Dokumentation des Quellcodes und die Frage der Lizensierung bei einer Rezension? Und schließlich, was sind die Leistungen der Software-Entwickler, die eine Besprechung berücksichtigen sollte, und wie kann man so eine Besprechung anfertigen?

In dieser Handreichung erläutern wir einige Kriterien für gute Forschungssoftware. Dabei folgen wir den Empfehlungen der DFG und weisen auf sogenannte ["open standards"](http://xml.coverpages.org/openStandards.html) hin. Software greift im- und explizit tief in den Forschungsprozess ein (für die Archäologie siehe z.B. [@schmidt_marwick_2020](#schmidt_marwick_2020)) und nur durch die Offenlegung von Quellcode ist eine Bewertbarkeit der durch die Software geleisteten Abläufe gewährleistet.

Wir empfehlen eine Vorgehensweise zur Softwarerezension und sammeln Kriterien, die für die Bewertung einer Software von Bedeutung sein können. Aufgrund der Vielfalt der möglichen Besprechungsgegenstände werden nicht in jedem Fall alle Kriterien von Bedeutung sein. Wir konzentrieren uns dabei bewusst auf Aspekte, die spezifisch für die Besprechung von Software sind. Dies bringt mit sich, dass die jede Rezension bestimmende Fragestellung nach dem wissenschaftlichen Wert nur gestreift wird, denn an diesem Punkt stimmen die Anforderung an eine Besprechung einer traditionellen Publikation und Software letztlich überein.    

Die hier vorgestellten Überlegungen, Kriterien und Vorschläge sollen den Rezensentinnen und Rezensenten also als Arbeitserleichterung dienen. Der Beitrag ist als Impuls angelegt und wir wünschen uns Diskussionsbeiträge sowie Anregungen. Dazu können entweder die Autoren kontaktiert werden oder -- hier website [https://research-squirrel-engineers.github.io/DGUF_Leitfaden/](https://research-squirrel-engineers.github.io/DGUF_Leitfaden/) und Kontaktdaten einfügen ? -- genutzt werden.

## Forschungssoftware

Die weiter unten vorgestellten Kriterien zur Rezension von Software zielen primär auf die Begutachtung von Forschungssoftware ab. Unter Forschungssoftware verstehen wir Software, die mit Fokus auf den Einsatz in der Forschung entwickelt wurde, also um Forschungsdaten zu erzeugen, zu verarbeiten oder zu analysieren [@hettrick_2014_14809](#hettrick_2014_14809). Dies sind beispielsweise Programme, die der Kalibrierung und Umrechnung von Messwerten, der Annotation von Texten und Objekten, oder der Bereitstellung sowie der Verknüpfung und Visualisierung fachlich relevanter Vokabulare dienen.

Forschungssoftware kann entweder für einen sehr spezifischen Bedarf oder einen allgemeinen Anwendungsbereich entwickelt werden. Sie ist dabei stets Teil des Forschungsprozesses, der in allen seinen Punkten nachvollziehbar und soweit möglich reproduzierbar sein muss. Forschungssoftware kann hierbei von zwei Seiten betrachtet werden, die unabhängig nebeneinander stehen: 
1. Forschende wenden eine Forschungssoftware im Kontext ihrer Arbeiten an oder 
2. Forschende entwickeln Forschungssoftware im Kontext ihrer Arbeiten.

Im Gegensatz zu Forschungssoftware steht Software, die zur Nutzung spezifischer Geräte erforderlich ist, wie etwa zur Vermessung, zur fotografischen Dokumentation oder zur Analyse von Oberflächen und Inhaltsstoffen. Häufig handelt es sich dabei um proprietäre Software, die zusammen mit der Hardware vertrieben wird. Obwohl sie im Forschungsprozess eingesetzt wird, entspricht sie nicht unserem Verständnis von Forschungssoftware. Auch digitale Werkzeuge, die eine erhebliche Rolle in der praktischen Arbeit inne haben, jedoch keinen eigentlichen Anteil an der Erhebung, Bearbeitung und Analyse der Daten haben, sind in unserem Sinne keine Forschungssoftware. Trotzdem können auch sie mittels der vorgestellten Kriterien beurteilt werden.

Forschungssoftware ist in besonderer Weise Herausforderungen nachhaltiger Entwicklung und Pflege ausgesetzt. Ein Hauptfaktor für fehlende Nachhaltigkeit von Forschungssoftware ist der Mangel an langfristiger Finanzierung für \`Forschungssoftware-Ingenieure\`, die sich um die geeignete Architektur, Organisation, Implementierung, Dokumentation und Interaktion mit der Gemeinschaft für die Software kümmern, gepaart mit der Umsetzung von Maßnahmen, um die Software während und nach dem Entwicklungsprozess nachhaltig zu machen ([@anzt_environment_2020, 2](#anzt_environment_2020)). Ein Überblick über Bedarfe, Herausforderungen und Lösungsansätze zu Förderung und Finanzierung, Auswahl, rechtliche Fragen, Organisation und Governance, sowie Bündelung von Ressourcen wurde 2019 in einem Workshop der deRSE Konferenz in Potsdam erstellt ([@bach_dersews19](#bach_dersews19)).

### Forschungssoftware als wissenschaftliche Leistung

In der modernen Forschung ist ein Arbeiten ohne digitale Werkzeuge undenkbar. Dies trifft ebenfalls auf die historische und altertumswissenschaftliche Forschung zu. Mit dem Aufschwung der Digital Humanities wird Forschungssoftware weiterhin und auch zunehmend ein wichtiger Bestandteil des Forschungsprozesses sein.

Trotz der tragenden Rolle, die Forschungssoftware in manch einem Projekt hat, wird die Leistung der Personen, die hinter der Entwicklung und Programmierung stehen, akademisch nicht anerkannt ([@hettrick_2017](#hettrick_2017), [@scheliga_pampel_2017](#scheliga_pampel_2017) und [@katerbow_2018](#katerbow_2018)). Jedoch fließen einerseits bei der Entwicklung von Forschungssoftware teilweise jahrelange technische Erfahrung und Praxis ein. Andererseits wird aber auch Wissen über wissenschaftliche Standards und Praktiken angewendet. Durch die Umsetzung in Code wird Praxis und Wissen explizit gemacht und weiterentwickelt. Diese Leistungen gilt es zu würdigen und sichtbar zu machen ([@scheliga_pampel_2017](#scheliga_pampel_2017), [@katerbow_2018](#katerbow_2018) sowie [@helmholtz_web](#helmholtz_web)).

Als erster Schritt in Richtung Sichtbarmachung wurde 2012 die Berufsbezeichnung des "Software Research Engineers" (RSE, RSEng) geprägt ([@hettrick_2017](#hettrick_2017) und [@baxter_2012](#baxter_2012)). Mittlerweile hat sich auch eine aktive, internationale und interdisziplinäre Gemeinschaft gebildet, die unter anderem auch in Deutschland als de-RSE e.V. tätig ist, Konferenzen organisiert und Empfehlungen gibt ([@anzt_environment_2020](#anzt_environment_2020)). Auch im internationalen Kontext entwickeln sich immer mehr nationale [RSE Sektionen](https://sorse.github.io/contact/chapters/) und gemeinsam von der RSE Community organisierte Konferenzen, wie z.B. [SORSE](https://sorse.github.io). Im Rahmen des Aufbaus einer \`Nationalen Forschungsdateninfrastruktur (NFDI)\` nehmen Forschungssoftware und RSEs einen großen Stellenwert in der wissenschaftlichen Praxis ein ([@loeffler_nfdi4rse20](#loeffler_nfdi4rse20) und [@goedicke_nfdixcs20](#goedicke_nfdixcs20)).

Eine der Forderungen der de-RSE e.V. ist, dass Forschungssoftware mittels geeigneten Publikationsmodalitäten sichtbar gemacht werden soll, da eine Publikation und vor allem deren Auffindbarkeit redundante Arbeit vermeidet ([@anzt_environment_2020, 10](#anzt_environment_2020)). Dabei ist die eindeutige Autorenschaft von großer Bedeutung, da erst dadurch die Leistung der Forschungssoftwareentwicklung an die entsprechenden Personen geknüpft werden. Dies eröffnet weitere akademische Karrierewege, in denen bislang nur klassische Publikationen gewertet wurden. Zukünftig sollten aber in gleicher Weise auch Datenpublikationen, Softwareentwicklung und -publikationen ([https://citation-file-format.github.io](https://citation-file-format.github.io), [https://doi.org/10.5281/zenodo.1003149](https://doi.org/10.5281/zenodo.1003149)), Annotationen, sowie deren Zitationen als Kriterien der Beurteilung der wissenschaftlichen Leistung sein (s. [NFDI4Culture](https://nfdi4culture.de), [RSE4NFDI](https://www.rse4nfdi.de/de/index.html), [NFDI4Objects](https://www.nfdi4objects.net)).

Ein Beispiel für die Nennung der Autorschaft bildet das einleitende Zitat, das die Erfahrungen der Archäologischen Informationen widerspiegelt. Allerdings gibt es grundlegende Unterschiede zur gewohnten Publikation von Aufsätzen und Büchern. Da die Entwicklung von Software auf bereits bestehenden Modulen aufbaut, muss das Verständnis von Autorenschaft und wie sie sich über die Lebenszeit der Software hinaus dokumentieren lässt spezifisch für Software erfolgen [@katz_software_2016](#katz_software_2016).

Eine publizierte Software kann anschließend, ganz so wie in der bisherigen Praxis der altertumswissenschaftlichen Forschung, begutachtet werden. In einer Rezension kann diese dann einem breiteren Publikum vorgestellt werden. Mit der Einführung der Rezensionskategorie "Archäoinformatik" intendiert die Redaktion der Archäologischen Informationen genau dies. Durch eine dedizierte Rezension von Software analog zu Rezensionen wissenschaftlicher Publikationen, wird die wissenschaftliche Leistung der Autoren und Autorinnen von Forschungssoftware mittels gewohnten Formaten sichtbar und anerkannt.

### Gute Forschungssoftware

Um überhaupt Kriterien zur Rezension und Bewertung von Forschungssoftware aufstellen zu können, stellt sich zunächst die Frage, was überhaupt gute und moderne Standards entsprechende Forschungssoftware ausmacht. Natürlich gehören dazu eine Vielzahl fachlicher und technischer Aspekte, die weiter unten beleuchtet werden sollen. Darüber hinaus muss Software aber wie jedes andere Werkzeug zunächst hinsichtlich ihrer generellen Eignung für nachhaltiges und ethisches wissenschaftliches Arbeiten bewertet werden.

Die Deutsche Forschungsgemeinschaft (DFG) formuliert mit ihren "Leitlinien zur Sicherung guter wissenschaftlicher Praxis" ([@deutsche_forschungsgemeinschaft_2019](#deutsche_forschungsgemeinschaft_2019)) eine Reihe von Vorgaben für gutes wissenschaftliches Arbeiten. Die Leitlinien entsprechen einem internationalen Konsens und etablierten Prinzipien. Zu den Anforderungen gehören etwa die Einhaltung und Etablierung von Standards und Methoden, eine nachvollziehbare Dokumentation des Weges zu Ergebnissen, die öffentliche Zugänglichkeit von Ergebnissen und die Archivierung der notwendigen Materialien, die zu Ergebnissen geführt haben.

Einige der Kriterien, die in den DFG-Leitlinien explizit und implizit anklingen, sollen im folgenden näher ausgeführt werden: Die in der Erläuterung zu Leitlinie 13 (*Herstellung von öffentlichem Zugang zu Forschungsergebnissen*) genannten FAIR-Prinzipien, die Prinzipien der Offenen Wissenschaft (Open Science) und zuletzt die CARE-Prinzipien, welche in den Leitlinien 2 und 10 anklingen. Darüber hinaus sind weitere Hinweise zur Umsetzung der DFG-Leitlinien in Bezug auf Forschungssoftware unter [@forschungsdaten_info_dfg](#forschungsdaten_info_dfg) zu finden.

#### FAIR-Prinzipien

Die FAIR-Prinzipien wurden 2016 als FAIR Data Principles veröffentlicht [@wilkinson_2016](#wilkinson_2016). Sie zielen primär auf Forschungsdaten und deren Metadaten ab und fordern dass diese auffindbar (Findable), zugänglich (Accessible), interoperabel (Interoperable) und nachnutzbar (Reusable) sind. Die Prinzipien können auch auf Forschungssoftware und deren Metadaten übertragen werden ([@lamprecht_towards_2019](#lamprecht_towards_2019), [@goedicke_nfdixcs20](#goedicke_nfdixcs20)).

Die Anwendung von FAIR-Prinzipien fördert die Qualität der Software hinsichtlich der grundsätzlichen Ansprüche an Interoperabilität bei der Verwendung in einem Workflow und der Verwendung von Standards und etablierten Paradigmen des Programmierens und der Dokumentation. Die FAIR-Prinzipien beziehen sich nicht auf die wissenschaftliche Qualität des Tools. Dennoch ergeben sich eine Anzahl von Kriterien, die in die Beurteilung einer Forschungssoftware einfließen und von Angaben, die im Rahmen der Rezension als Serviceleistung zu erbringen sind, wie die Autorenschaft, das zur Speicherung verwendete Repositorium oder mögliche nötige Voraussetzungen zur Verwendbarkeit.

Ein Fokus der FAIR-Prinzipien ist, dass Daten, bzw. Forschungssoftware, und Metadaten auch maschinell lesbar und verarbeitbar sind. Dies betrifft vor allem die Prinzipien 'Accessible' und 'Interoperable'.

##### Findable (Auffindbar)

Software wird durch die Speicherung zusammen mit ihren Metadaten in dedizierten Softwarerepositorien auffindbar, welche kommerziell, community-basiert und in vielen weiteren Formen starke Impulse für die Entwicklung der wissenschaftlichen Infrastrukturen geben. Die Auffindbarkeit wird durch die fachwissenschaftliche Einbindung und die klassische Arbeit von Forschungsinfrastrukturen zusätzlich erhöht, da sie Aufbau, Pflege und Anwendung von kontrolliertem Vokabular und Metadatenstandards zur Indexierung betreiben ([@lamprecht_towards_2019](#lamprecht_towards_2019) und [@anzt_environment_2020, 10](#anzt_environment_2020)).

Die Vergabe von persistenten URIs durch Repositorien, sowie die Nennung der Autorenschaft ermöglicht das Zitieren von Forschungssoftware. Wichtig ist hierbei, dass Software, da sie im Gegensatz zu herkömmlichen Publikationen kontinuierlich weiterentwickelt wird, in unterschiedlichen Entwicklungsständen abgelegt wird, damit bestimmte Versionen zitiert werden können [@forschungsdaten_info_dfg](#forschungsdaten_info_dfg).

##### Accessible (Zugänglich)

Entsprechend den FAIR-Prinzipien sollte Software und die sie beschreibenden Metadaten über ihre persistente URI erreichbar sein. Dies sollte auch maschinell über ein offenes und standardisierte Kommunikationsprotokoll möglich sein [@lamprecht_towards_2019](#lamprecht_towards_2019).

Weitere Aspekte, welche die Zugänglichkeit erleichtern, sind die Verfügbarkeit für verschiedene Betriebssysteme, sowie technische Anforderungen welche von aktuell verbreiteten Geräten geleistet werden können. Eine verständliche Anleitung zur Nutzung des Programms verbessert die Zugänglichkeit im Sinne der Nutzbarkeit.

> [MT] 'kostenlos' entfernt. FAIR fordert das nicht. Wir könnten aber 'Kosten' als Kriterium einfügen

##### Interoperable (Interoperabel)

Interoperabilität von Software kann sich zum Einen auf die Kompatibilität der Ein- und Ausgabeformate mit anderen Programmen in einem Arbeitsprozess (horizontale Dimension) beziehen. Zum Anderen verweist sie auch auf die Zusammenarbeit der verwendeten Komponenten in der Software selbst (vertikale Dimension) [@lamprecht_towards_2019, 46 f.](#lamprecht_towards_2019). Beides wird durch die Verwendung von Standards ermöglicht, welche die Zusammenarbeit von Softwarekomponenten auch über Betriebssystemgrenzen hinweg ermöglicht.

##### Reusable (Nachnutzbar)

Die Nachnutzbarkeit von Software hängt von mehreren Komponenten ab. Die Metadaten und eine umfassende Dokumentation der Software sollten es anderen ermöglichen Ergebnisse zu reproduzieren, sowie eigene Daten und veränderte Anwendungsfälle zu prozessieren. Eine geeignete Lizenz, welche auch die abhängigen Softwarekomponenten berücksichtigt gibt zudem darüber Auskunft welche Regeln bei der Nutzung gelten und ob eine Weiterentwicklung des Codes möglich ist. Für die Zitierbarkeit ist eine Nennung der Beteiligten notwendig [@lamprecht_towards_2019, 48-49](#lamprecht_towards_2019).

#### Open Science

Open Science (Offene Wissenschaft) bezeichnet eine Wissenschaftspraxis, deren Ziel ein transparenter, replizierbarer und kollaborativer Forschungsprozess ist [@bezjak_openscience_2018, Open Concepts and Principles](#bezjak_openscience_2018). Open Science setzt sich aus mehreren Prinzipien zusammen, die unterschiedliche Stadien im Forschungsprozess betreffen.

So fordert Open Science nicht nur die Öffnung der Ergebnisse (Open Access), sondern auch der zugrundeliegenden Daten (Open Data), Methoden (Open Methodology) und der verwendeten Forschungssoftware (Open Source). Für offene Forschungssoftware gilt, dass ihr Quellcode zugänglich und mit einer Lizenz versehen sein muss, welche die Weiterentwicklung erlaubt [@bezjak_openscience_2018, Open Research Software and Open Source](#bezjak_openscience_2018).

In den Leitlinien der DFG klingt die Öffnung von Software-Quellcode im Zusammenhang mit der Qualitätssicherung [@deutsche_forschungsgemeinschaft_2019, 14-15](#deutsche_forschungsgemeinschaft_2019) und der Herstellung von öffentlichem Zugang zu Forschungsergebnissen [@deutsche_forschungsgemeinschaft_2019, 19](#deutsche_forschungsgemeinschaft_2019) an.

Mit der Forderung nach der Offenlegung des Quellcodes (Open Source), wird auch dem Gedanken der Nachnutzbarkeit entsprochen. Die Offenlegung wird erweitert um die Forderung, den Code zudem frei nutzbar zur Verfügung zu stellen (Free Source) [@stallman2001free](#stallman2001free). Letzteres wird als FOSS (Free/Libre Open Source Software) bezeichnet und wird in Deutschland z.B. von anwendungsbezogenen Wissenschaftler\*innen und Entwickler\*innen aus der Geoinformatik vertreten ([FOSSGIS e.V.](https://www.fossgis.de)). oder von Research-Software-Engineers in der "de-RSE e.V." [@anzt_environment_2020](#anzt_environment_2020).

#### CARE-Prinzipien und Ethos

In den Leitlinien der DFG werden in Leitline 2 und 10 ethische Aspekte im Forschungsprozess angesprochen, die auch im Bereich der Forschungssoftware Beachtung finden sollten.

Tatsächlich ist Forschungssoftware nicht politisch neutral. Ihre Architektur reflektiert ihre Entstehungsbedingungen, ihre Nutzung erfolgt unter spezifischen Voraussetzungen und auch ihre Weitergabe unterliegt den vorherrschenden Konventionen und Gewohnheiten. Vielfach tragen gerade diese Gewohnheiten zur (unbewussten) Festigung von Privilegien und Diskriminierungen bei: Für archäologische Feldarbeit wird oft Software zur Datenaufnahme eingesetzt, die für die Mehrheit der Mitarbeiter\*innen vor Ort aufgrund einer Sprachbarriere nicht verständlich ist, proprietäre Software oder teure Hardware benachteiligt Forscher und Forscherinnen mit weniger Finanzmitteln und Handbücher kennen oft ausschließlich männliche Nutzer. 

Jenseits dieser Beispiele zeigen hochaktuelle, technische Entwicklungen, dass schon Algorithmen an sich sehr wohl Gruppen und Individuen diskriminieren können, wie etwa im Fall von Facial-Recognition-Software, die ausschließlich auf die Erkennung hellhäutiger Menschen optimiert wurde [@breland_how_2017](#breland_how_2017). <!-- CS: Ich würde den folgenden Satz in eine Fußnote packen: "Dieses Beispiel zeigt auch, ..."--> Auch für diese kritische Auseinandersetzung mit Forschungssoftware sollte deren Autorenschaft zuweisbar gemacht werden.

Eine Personengruppe, die besonders oft zum passiven Spielball von Forschungssoftware und Datenverarbeitung geworden ist, sind indigene Bevölkerungsgruppen. Gerade in den Altertumswissenschaften, in denen häufig an fremden Kulturen und Kulturhinterlassenschaften geforscht wird, sollten die Rechte dieser Bevölkerung bezüglich ihres kulturellen Erbes und des damit zusammenhängenden Wissens berücksichtigt werden. Hierfür eignen sich die CARE-Prinzipien ([https://www.gida-global.org/care](https://www.gida-global.org/care)). Sie wurden von der Global Indigenous Data Alliance (GIDA) und der Research Data Alliance (RDA) 2018 auf Basis der UN Declaration on the Rights of Indigenous Peoples (UNDRIP) erarbeitet und konzentriert sich explizit auf Forschungsdaten. Ihre vier Grundpfeiler Kollektiver Nutzen (Collective Benefit), Souveränität (Authority to Control), Verantwortung (Responsibility) und Ethik (Ethics) sind jedoch auch für Forschungssoftware und für jeden Kontext relevant, in dem ein Ungleichgewicht von Machtverhältnissen existiert.

##### Collective Benefit (Kollektiver Nutzen)

Dieser Punkt fordert den gemeinschaftlichen Nutzen der Datenerhebung für die indigene Bevölkerung. Er lässt sich leicht auf Software übertragen: Software, die auf Wissen und Erfahrungen von indigenen Bevölkerungen beruht, soll für diese Gruppen einen Nutzen haben. Hier geht es darum, dass Menschen, die einen wichtigen Beitrag für die Entwicklung geleistet haben, honoriert werden und die Anwendung nicht nur Fremden zugute kommt (monetär, durch Reputation u.ä.).

##### Authority to Control (Souveränität)

Die Kontrollmacht über die eigenen Daten ist eine wichtige Forderung Indigener Menschen. Auch dies lässt sich auf Software anwenden: Die Entscheidungsmacht über die Verwendung von anhand ihres Wissens entwickelter Software soll bei der Indigenen Bevölkerung liegen. Dieser Punkt kann verhindern, dass indigenes Wissen unangemessen ausgenutzt wird und kann durch die computertechnische Ermächtigung von Indigenen verstärkt werden.

##### Responsibility (Verantwortung)

Wer mit Indigenen Daten arbeitet, hat die Verantwortung nachvollziehbar aufzuzeigen, wie diese Daten den Indigenen Gruppen zugute kommen. Entwickler von Software haben Verantwortung für die positive Folgen der Software für die Indigenen Gruppen zu übernehmen. Bei der Entwicklung ist es die Verantwortung der Produzenten mögliche schädliche Konsequenzen der Software auszumerzen. Dies kann durch inklusive Ansätze bei der Entwicklung verfolgt werden.

##### Ethics (Ethik)
Rechte und Wohl der indigenen Bevölkerung sollten an erster Stelle bei der Erarbeitung und Bearbeitung eines Datensatzes stehen. Für Software gilt das gleiche, wenn sie indigene Völker betrifft.

> [SCS] muss nochmal auf angemessene Sprache geprüft werden (Indigene oder indigene wird zB im englischsprachigen diskutiert. "Bevölkerungen" oder "Völker" etc)

## Fachliche und technische Beurteilung

Die genannten Prinzipien rund um FAIR, Open Science und CARE dienen vor allem der allgemeinen Bewertung von Software. Jedoch werden noch eine Reihe fachliche und technische Spezifika benötigt, um in einer Rezension die Leistung der Entwickler\*innen angemessen zu beurteilen.

> [MT] die folgenden Teile in diesem Abschnitt gehören noch überarbeitet
> [SCS] besser?

Die Beschäftigung mit der wissenschaftlichen Nutzung, also den Nutzungsszenarien von Forschungssoftware, ist in der archäologischen Forschung bereits verankert (bezogen auf die Ur- und Frühgeschichte und die Archäologie des Mittelalters). Die AG CAA e.V. führt seit 2010 jährlich Workshops durch, in denen Tutorials zu Software durchgeführt und Fallbeispiele diskutiert werden sowie Entwickler\*innen ihre Tools zur Diskussion stellen. Auch in den Fachzeitschriften und Tagungen mit anderen thematischen, räumlichen und zeitlichen Schwerpunkten werden in gewisser Regelmäßigkeit entsprechende Fallbeispiele publiziert. Tagungen, Sammelbände uns Ausstellungen nehmen sich bestimmter Themen an, wie der Auswertung von LIDAR-Daten oder 3D-Rekonstruktionen (LIT./LIT).

Die Publikationen von Forschungsergebnissen, die unter dem Einsatz spezifischer Forschungssoftware erzielt wurden, legen je nach Qualität der Arbeit die zugrundeliegenden Berechnungswege, die Modellierung der Daten und die Wechselbeziehung mit dem Forschungsdesign dar (exemplarisch: Zimmermann, Saile, Freund). Eine insgesamt kleinere Anzahl von Autorinnen und Autoren setzen sich in ihren Beiträgen explizit mit der Leistungsfähigkeit und den Parametern dieser Rechnungen selbst, bzw. den Algorithmen auseinander (exemplarisch: [@Herzog_2012](#Herzog_2012), [@Herzog_2014](#Herzog_2014) und Gerhard Roth LIT). Diese, aus der eigenen fachlichen Traditionen der Archäologie entwickelten, Kriterien sind für die Rezension einer Forschungssoftware ebenfalls für Bedeutung, da sie das Potenzial für die wissenschaftliche Arbeit und die Passung zum Forschungsfeld beschreiben.

> [TH] Hier fehlen noch Zitate und Bibtexeinträge (Zimmermann, Saile, Freund, Gerhard Roth LIT)

## Mögliche Vorgehensweise zur Rezension archäologischer Forschungssoftware

Nach unserem Verständnis sollte eine Rezension archäologischer Software, so wie es eine herkömmliche Besprechung einer wissenschaftlichen Publikation leistet, die Software zunächst vorstellen, dabei zusammengefasst Eckdaten vorlegen und den Kontext erläutern. Im Anschluss sollte dann eine kritische Beurteilung erfolgen. Umgesetzt auf Software gehören zu den Eckdaten Angaben zur Version und den Releasedaten, zu den Entwicklern, der Lizenz und Weiteres. Als Kontext verstehen wir eine erste Einordnung in das archäologische Forschungsfeld und Angaben zum möglichen Zusammenhang mit Forschungsprojekten, Arbeitsgruppen oder Institutionen. Für die kritische Beurteilung aus unterschiedlicher Perspektive haben wir unten einen Fragekatalog zusammengestellt. Zuletzt sollten die Ergebnisse der Betrachtung in einer Stellungnahme zusammengefasst werden, die die Software hinsichtlich ihrer Nützlichkeit, ihrer Bedienbarkeit, ihrer handwerklichen Qualität und ihrer Position in Relation zu den Idealen guter Forschungssoftware (z.B. FAIR und CARE), beurteilt.

Der Umfang der Rezension für die Veröffentlichung in den Archäologischen Informationen sollte 1000-2000 Worte nicht übersteigen.

Selbstverständlich setzt die Rezension einer Forschungssoftware die Sichtung der Dokumentation, begleitender Publikationen ebenso voraus, wie die praktische Erprobung der Software selbst. Dabei ist eine realistische und transparente Einschätzung der eigenen Kompetenzen und des eigenen Nutzungsinteresses ein wichtiger Anhaltspunkt für die Leser, denn die Leserschaft ist wesentlich heterogener hinsichtlich ihrer Interessen, als man es bei der Besprechung einer Fachpublikation annehmen darf. Es ist ein wichtige Information, ob die Rezension ganz von der Anwendungsperspektive geschrieben ist, oder auch die Entwicklerperspektive umfasst.  

## Fragenkatalog zur Beurteilung von Software

Im folgenden stellen wir einen kommentierten Fragenkatalog vor, der auf Kriterien zur Beurteilung von archäologischer Forschungssoftware hinarbeitet. Er ist untergliedert in drei Bereiche, die jeweils Fragen aus verschiedenen Kompetenzbereichen bündeln. Dabei bilden die ersten zwei Bereiche die wissenschaftliche Verwendung und die Anwendung und Bedienbarkeit aus Nutzersicht. Der dritte Bereich enthält Fragen, die für Entwickler und die Administratoren von hohem Interesse sind und die damit die Anwendbarkeit und Nachhaltigkeit in den Blick nehmen. Im Anschluss stellen wir Merkmale vor, die eventuell tabellarisch einer Rezension beigegeben werden sollten, aber nur im Ausnahmefall vom Rezensenten beurteilt werden. 
Wie bei der Besprechung einer wissenschaftlichen Publikation ist die Zusammensetzung und Gewichtung der einzelnen Merkmale vom Rezensenten selbst zu bestimmen und in Relation zu dem Thema zu setzen. Entsprechend verstehen wir unseren kommentierten Fragenkatalog auch als eine Art Maximalversion, die bei der Anfertigung und der Einschätzung der eigenen Kompetenzen Hilfe geben kann.

### Einsatz in der Archäologie und wissenschaftlicher Zweck

Wissenschaftliche Software hat einen konkreten Zweck verfolgt und erfüllt eine bestimmte Aufgabe. Dabei sind zwei Dimensionen zu unterschieden. Dies ist zum einen und das ist für Forschungssoftware vorrangig, die Frage, ob die Software einen sinnvollen Beitrag zur Bearbeitung der archäologischen Fragestellung liefert. Zum anderen ist zu beurteilen, ob Software eine korrekte Umsetzung der angestrebten Arbeit leistet. Letzteres, also die Korrektheit der Ergebnisse einer Software, ist mitunter schwer zu beurteilen, insbesondere dann, wenn es keine weiteren Implementierungen des Algorithmus in anderen Softwarepaketen gibt. Dieses Problem gliedert sich in mehrere Aspekte: Zunächst stellt sich die sehr technische Frage, ob die in der Dokumentation genannten Algorithmen fehlerfrei in Programmcode ausgedrückt wurden. Meist ist schon eine Prüfung dieses Aspekts nicht trivial und übersteigt den Rahmen einer Rezension. Darüber hinaus versprechen wissenschaftliche Softwarewerkzeuge implizit oder explizit, die Beantwortung wissenschaftlicher Fragestellungen zu ermöglichen oder zumindest zu vereinfachen. Eine GIS-Applikation zur Analyse von Punktmustern kann etwa für den Zweck konzipiert sein menschliches Siedlungsverhalten nachherzusagen. Die Frage, ob der Algorithmus dazu semantisch überhaupt in der Lage ist, kann den Umfang einer Rezension bei weitem übersteigen. Es bleibt aber beim Rezensenten eine Einschätzung der Plausibilität vorzunehmen und das Problem der Einschätzbarkeit offenzulegen, um so die Leser dafür zu sensibilisieren. 

#### Wissenschaftlicher Zweck und Beurteilung der Korrektheit

* **Welches Problem versucht die Software zu lösen?** Welche Aufgaben werden mittels der Software bei der Erfassung, der Verarbeitung oder der Analyse von Daten durchgeführt? Wie sind diese Probleme und Aufgaben von ihrer Relevanz und von ihrer Häufigkeit in einem archäologischem Kontext einzuschätzen? z.B. "Schätzung von Bevölkerungsdichte aus Siedlungsgröße" oder "Statikmodellierung für Langhäuser"
* **Gibt es Archäologie-relevante erfolgreiche Projekte/Anwendungen, die von dieser Software bereits unterstützt wurden?** Wie plausibel sind die erzielten Resultate? Wurden Ergebnisse der Projekte kritisiert, die sich insbesondere auf Ergebnisse, die mit der Software erzielt wurden, beruhen?
* **Wie funktioniert der (wissenschaftliche) Algorithmus, der mit der Software implementiert wurde?** Welche wesentlichen Schritte durchlaufen Daten um das Ausgangsproblem zu lösen? z.B. "Die Eingabedaten werden mittels eines Referenzdatensatzes bereinigt, mit hierarchischer Clusteranalyse klassifiziert und zuletzt als paarweise Distanzmatrix visualisiert"
* **Wie löst die Software das gegebene Problem?** Wie ist die grundsätzliche Funktionsweise konzipiert? Was sind die wesentlichen Bestandteile in Frontend und Backend? z.B. "WebApp als Schnittstelle zu einer Datenbank" oder "Command line interface um ein Neuronales Netz für Nachhersage zu trainieren"
* **Wie ist die Software publiziert?** Eignet sich die Software für wissenschaftliche Anwendungen, da sie in einer zitierbaren Publikation vorgestellt wurde? Sind einzelne Versionen klar als solche referenzierbar (etwa mittles DOI)? z.B. "Das Softwarepaket wurde in einer kurzen, zweiseitigen Publikation im Journal od Open Source Software vorgestellt, diese Publikation schließt aber keine umfassenden Tests oder Vergleiche mit Alternativprodukten ein"

* **Ist die Behauptung, eine bestimmte wissenschaftliche Fragestellung mit dem gewähltem Algorithmus lösen zu können, korrekt?**
* **Sind die Algorithmen korrekt implementiert worden?** 
* Ist das wissenschaftliche Ergebnis jenseits aller technischen Unterschiede vergleichbar zu anderen Implementierungen/Tools
* Sind die verwendeten Algorithmen dokumentiert und hinreichend wissenschaftlich belegt?

#### Bedienbarkeit und Zielgruppenorientierung
Die Bedienbarkeit von Software ist von zentraler Bedeutung, da sie als Flaschenhals alle Interaktion zwischen Nutzer und Software bestimmt. Über Installation, Interface und Maschinenschnittstellen hinaus, sind auch Hilfefunktionen und die Größe und Aktivität der Nutzercommunity entscheidend für die praktische Bedienbarkeit. Gerade letzteres ist auch für die Zukunftsfähigkeit und damit die Eignung für den Einsatz auf institutioneller Ebene und in langfristigen Vorhaben von zentraler Bedeutung.

Die folgenden Fragen richten sich auf technischen Merkmale, die die Benutzbarkeit (Usability) betreffen. Weitere technische Merkmale aus einer Entwickler-zentrierten Perspektive betrachten wir weiter unten.

##### Installation
* **Wie funktioniert die Installation und wo wird die Software vorgehalten?** Gibt es ein Installationsskript oder ist die Software nur als Source Code verfügbar, der zunächst selbst kompiliert werden muss? Ist die Lösung angemessen für den Nutzerkreis? Installationsskripte ermöglichen einen viel breiteren Anwenderkreis, das Kompilieren erlaubt geübten Nutzern die Installation u.U. auf verschiedenen Endgeräten. 
* **Handelt es sich um eine standalone Software, oder um eine Webanwendung?** Passt die Lösung zum archäologischen Einsatz? Ist z.B. eine Webanwendung unter allen Arbeitsbedingungen und Einsatzgebieten sinnvoll? Ist vielleicht auch beides möglich?
* **Ist klar erkennbar, welche Voraussetzungen die Hardware zu erfüllen hat?** Spezifikationen vorhanden?
* **Was waren die eigenen Erfahrungen bei der Installation der Software?** Dabei ist natürlich wichtig die eigene Umgebung und eigene Kompetenz darzustellen.

##### Interface
Die Nutzbarkeit wird zentral von den Möglichkeiten der Kommunikation von Mensch und Software bestimmt, also dem der Software-Oberfläche (UI). Diese mag in manchen Fällen graphisch gestützt sein, in anderen Fällen rein kommando-basiert. Die Gestaltung von Oberflächen und die Nutzerführung in Menüstrukturen sind ein eigenes Aufgabenfeld in der Softwareentwicklung und können erhebliche Kosten erzeugen. Gut an den Nutzer-angepasste Lösungen sind das Ergebnis einer genauen Kenntnis der Zielgruppe ihre Gewohnheiten und Bedarfe im Falle archäologischer Forschungssoftware also Forschungspraxis. Ein gutes Interface unterstützt das fehlerfreie effiziente Arbeiten. So sind z.B. Verständlichkeit der Menü-Einträge oder der Kommandos, aber auch die Aussagekraft von Fehlermeldungen Aspekte die in der Rezension betrachtet werden sollten. Barrierefreiheit ist bislang ein unzureichend abgedecktes Kriterium, das aber ebenfalls die Effizienz und den möglichen Nutzerkreis adressiert. Auch bei diesem Punkt liegen Gewichtung und im Ermessen des Rezensenten.

* **Passt die UI (GUI oder Konsole) zum Nutzerkreis?** Stellt z.B. die Nutzung einer eigens zu installierenden Shell eine Hürde dar?
* **Orientiert sich die Menüführung an bestimmten Vorbildern?** Das muss man nicht bewerten
* **Ist das Menü mehrsprachig bzw. in welchen Sprachen wird es angeboten?**  
* **Sind die Fehlermeldungen für die Rezensentin gut verständlich?** Sind auffallend/gut sichtbar

##### Zielgruppe
* **Ist die archäologische Nutzung vorgesehen?** Entspricht der archäologische Einsatz den generellen Anwendungszenarien, den die Entwickler\*innen vor Augen hatten? Hat das Einfluss auf die Nutzbarkeit aus wissenschaftlicher Perspektive? z.B. "Diese CAD Software ist für Architekturanwendungen konzipiert und konfrontiert den durchschnittlichen Grabungstechniker mit überwältigendem Funktionsumfang"

##### Hilfefunktionen, Tutorials und Community
Neben Hilfefunktionen und Tutorials ist es von großer Bedeutung, ob die Software von einer Community getragen wird. Die Zahl der aktiven Nutzer eines Softwarewerkzeugs ist entscheidend dafür, ob man im Falle von Problemen Hilfe in Foren findet. Ist der Nutzerkreis sehr klein findet der Wissenstransfer dagegen häufig im persönlichen Austausch statt, ist somit kaum dokumentiert und hängt stark von personellen Netzwerken ab. Diese können wiederum den großen Vorteil bieten, dass konkrete Fragen individuell von den Entwicklern aufgegriffen werden. Belege dafür können sich in öffentlichen Kommentarfunktionen von Webseiten der Entwickler und z.B. über Issues im Softwarerepositorium abzeichnen.

* Gibt es ausreichend Tutorials für das Erlernen der Software? Hier sollte überprüft werden, ob die Tutorials auf unterschiedliches Vorwissen eingehen und gegebenenfalls auch kenntlich machen, welches Grundwissen, welche Erfahrungen unabdingbar sind. Ein weiterer Aspekt bei den Anleitungen, Tutorials und FAQs ist die Frage der Sprachen.
* Gibt es Anwendungsbeispiele der Software, ggf. Beispieldatensets und eine Anleitung für diese um ein Verständnis für die Funktionsweise zu entwickeln?

* Wird die Software von einer Community getragen? 
* Gibt es bereits eine speziell archäologische Community für diese Software? (SIG, ...).
* Haben ArchäologInnen bereits Best Practices für diese Software formuliert?

* Wo finde ich mehr Informationen zu dieser Software? Hyperlinks und Referenzen.

##### Dateningest, Interoperabilität und Schnittstellen
Für viele Nutzer spielen Datenformate eine große Rolle, da diese die Kompatibilität zu anderen Anwendungen bestimmt. Dies betrifft sowohl, welche Datenformate gelesen, als auch geschrieben werden können. Bei vielen Anwendungen werden die unterstützten Dateiformate allein durch den entsprechenden Menü-Eintrag klar und es ist hilfreich, im Rahmen einer Rezension diesen anzuführen. Auch die Form des Uploads von Daten und das Vorhandensein von Schnittstellen machen einen wesentlichen Aspekt des praktischen Einsatz aus und sollten in einer Rezension bedacht werden.

* **Welche Datenformate werden eingelesen?** 
* **Welche Datenformate werden ausgegeben?** Sind diese Formate gängig und offen, oder bedürfen sie einer weiteren Transformation?
* **Wie können Daten eingeladen werden? Als Masseningest oder einzelne uploads?**
* **Gibt es eine API?**

##### Konformität mit Regelungen zum Datenschutz, Fragen der Privacy und der Datensparsamkeit
Für den Einsatz in der universitären Forschung und der Lehre ist die Frage des Datenschutz vielfach entscheidend dafür, ob die Software überhaupt genutzt werden darf. Eine Einschätzung der Regelungen sofern sie sich nicht eindeutig auf die europäischen Rahmenrichtlinien beziehen, ist teilweise jedoch kaum möglich und Gegenstand von juristischen Diskussionen. Auch hier kann die Rezensension aber bereits durch den Hinweis auf das Thema einen wichtigen Service für die Leser bringen.Dies gilt auch für Datensparsamkeit und das Hinterfragen von Registrierungsvorgängen, Cookies und ähnlichem. 
 
* **Beachtet die Software die lokalen Gesetze in dem Land in dem sie eingesetzt werden soll? (Datenschutz, Kartendarstellungen etc.)?** 
* **Welche Daten speichert die Anwendung zu welchem Zweck wie lange?** Dienen diese Daten der Forschung bzw. helfen sie die Software zu verbessern?
* **Ist die Software ohne Login anonym bedienbar?**
* **Benötigt die Software eine Internetverbindung und werden personenbezogene Daten an Dritte übertragen?**


### Entwickler-Perspektive und Softwarequalität
Hier geht es nun um die Sicht aus Perspektive der Entwickler, die auch Nutzer sind, aber zusätzlich mit weiteren Interessen/Anwendungsszenarien auf die Software schauen. Die folgenden Fragen richten sich somit direkt auf den Programmcode und die Softwarearchitecḱtur richten. Eine Beurteilung derselben erfordert also, den Programmcode herunterzuladen und in Stichproben durchzusehen. Das ist bei proprietärer Software meist nicht möglich.

#### Dokumentation und Tests
Die Dokumentation von Software kann auf verschiedene Arten erfolgen. Man unterscheidet die Dokumentation des Quellcodes, d.h. von Klassen oder einzelnen Methoden, die Dokumentation des Buildprozesses, d.h. wie die Software aus dem Quellcode zu erzeugen ist, eine Entwicklerdokumentation in Form von Beispielen der Benutzung der Software und der Dokumentation dessen wie die Software getestet wurde bzw. welche Testcases von der Software abgedeckt wurden.
* Ist eine Quellcodedokumentation vorhanden und ggf. eine HTML Variante davon verfügbar?
* Ist der Buildprozess dokumentiert und ggf. mittels Buildingscripts automatisiert?
* Gibt es eine Entwicklerdokumentation, sodass die Software leichter verstanden werden und ggf. erweitert werden kann?
* Ist die Dokumentation aktuell, wird gepflegt und deckt alle Funktionen des Programms ab?
* Hat der Quellcode Tests, die die Kernfunktionen des Programms testen und diese für andere Entwickler aufzeigen?
* Wird es dem Benutzer einfach gemacht die Software zu testen? Gibt es eine VM, einen Dockercontainer, einen Installer, andere Formen der Installierbarkeit ohne viel vorheriges Fachwissen?
* Sind die Entwickler der Software aktiv und gut erreichbar? Wird die Software regelmäßig mit Updates versorgt?

#### Qualität der Implementierung

* Entspricht die Implementierung dem Stand der Technik?
* Ist die Implementierung performant? Für Webapplikationen und Plugins ist zu überprüfen, ob sie responsiv sind und über die verschiedenen Browser hinweg performant sind.
* Wie robust ist die Software gegenüber äußeren Einflüssen? Wie geht die Software mit Abstürzen/Stromausfall usw. um? Wird die Arbeit regelmäßig zwischengespeichert?

#### Sicherheit
* Ist die Anwendung auf Sicherheitsanforderungen getestet worden? (Penetrationtests usw.), also ist sie leicht hackbar oder nicht?
* Setzt die Anwendung Standards zur IT Sicherheit welche von Behörden oder internationalen Organisationen empfohlen werden um? Beispiel [OWASP](https://de.wikipedia.org/wiki/Open_Web_Application_Security_Project)
* Hat die Anwendung Abhängigkeiten zu Softwarekomponenten welche bekannte Sicherheitslücken aufweisen und nicht mehr gepflegt werden? Hält dieser Zustand auf absehbare Zeit an?



## Weitere Merkmale und Spezifikationen
Wie oben beschrieben gibt es eine große Anzahl weiterer Merkmale, die für die Leser interessant sein können, aber keiner Einschätzung oder Beurteilung benötigen. Denkbar ist etwa diese, wie man es vielfach bei Vergleichsportalen findet, tabellarisch zusammengefasst werden. Wir haben hier auch einige Merkmale wiederholt, die auch in unserem Fragekatalog vorhanden sind. Auch um zu zeigen, wie man gegebenenfalls Gewichtungen in der Besprechung vornhemen kann, ohne ganze Aspekte unerwähnt zu lassen.

* Vorhandensein der Spezifikation für Installationen
* Opensource, Free and OpenSource
* Tutorials and Trialdata (zur freien Nutzung?)
* Input- / Outputformate
* Alternativprodukte / Konkurrenzangebote


## Anmerkungen

<a name="myfootnote1">1</a>: Aufgeworfen und anschließend im Plenum des 9. Workshops der deutschen Sektion der CAA 2019 in Wilhelmshaven wurde die Frage nach den Inhalten einer Rezension von Software und Anwendungen für die Archäologie von Sophie Charlotte Schmidt, Kai-Christian Bruhn und Siegmund Freud. Anlässlich der Einrichtung der neuen Rubrik für solche Besprechungen in der vorliegenden Reihe haben wir das Thema aufgegriffen und möchten mit der vorliegenden Handreichung einen Beitrag zur Weiterentwicklung dieses wichtigen Themas leisten. Die Handreichung kann auch zur Orientierung bei Entscheidungen zum Einsatz einer Software in der eigenen Forschung dienen.


## Bibliographie
