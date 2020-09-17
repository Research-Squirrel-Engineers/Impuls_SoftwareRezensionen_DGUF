---
title: Diskussionsbeitrag - Handreichung zur Rezension von Forschungssoftware - Fragenkatalog für "gute" Forschungssoftware
title_en: Recommendations for the review of archaeological research software - what constitutes "good" research software

layout: draft
author:

  -
    name: Timo Homburg
    affiliation: Hochschule Mainz
    orcid: 0000-0002-9499-5840
    bio: "Timo Homburg studierte Informatik mit den Schwerpunkten Computerlinguistik (Assyrologie), Semantic Web und Sinologie. In den letzten Jahren arbeitete er im Bereich der GIS Anwendungen in der Geoinformatik. Seine Doktorarbeit beschäftigt sich mit der besseren Integration von Geodaten in ein Semantic Web Umfeld. Sein aktuelles Forschungsvorhaben beschäftigt sich mit der Schaffung digitaler Standards im Bereich Assyrologie und der Best Practice Dokumentation von Ausgrabungen mit Keilschrifttexten - eine Erweiterung seiner Publikationen zum Thema Keilschrift in den Digital Humanities."

  -
    name: Anne Klammt
    affiliation: Deutsches Forum für Kunstgeschichte Paris
    orcid: 0000-0003-3697-9241

  -  
    name: Clemens Schmid
    affiliation: Max-Planck-Institut für Menschheitsgeschichte Jena
    orcid: 0000-0003-3448-5715
    bio: "Clemens Schmid studierte Prähistorische, Historische und Naturwissenschaftliche Archäologie und Informatik in Tübingen und Kiel. Nach Studienabschluss arbeitete er mit computerbasierter Datenanalyse in verschiedenen archäologischen Forschungsprojekten an der Universität Kiel, dem Römisch-Germanischen Zentralmuseum in Mainz und der Universität Bern. Im Augenblick ist er für ein Promotionsprojekt zur quantitativen Nachhersage von Mobilitätsverhalten mit genetischen und historisch-linguistischen Daten in der Abteilung für Archäogenetik des Max-Planck-Instituts für Menschheitsgeschichte in Jena beschäftigt."
  -
    name: Sophie Charlotte Schmidt
    affiliation:
    orcid: 0000-0003-4696-2101
  -
    name: Lutz Schubert
    affiliation:
    orcid: 0000-0003-4889-9353
  -
    name: Florian Thiery
    affiliation: Research Squirrel Engineers
    orcid: 0000-0002-3246-3531
    bio: "TODO"
  -
    name: Martina Trognitz
    affiliation: Austrian Centre for Digital Humanities and Cultural Heritage, ÖAW Wien
    orcid: 0000-0003-0485-6861
    bio: "Martina Trognitz studierte Computerlinguistik und Klassische Archäologie in Heidelberg. 2012 bis 2017 war sie im Projekt IANUS am Deutschen Archäologischen Institut tätig. Seit 2017 leitet sie das digitale Archiv ARCHE des ACDH-CH an der Österreichischen Akademie der Wissenschaften. Sie bearbeitet ein Promotionsprojekt zur maschinellen Analyse von mehrseitigen ägäischen Siegeln der Bronzezeit."

bibliography: literatur.bib
csl: apa-6th-edition.csl
keywords:
  - Handreichung
  - Softwarebewertung
  - Forschungssoftware
  - Archäologie
keywords_en:
  - Manual
  - Softwarereview
  - Researchsoftware
  - Archaeology

---

<div id="zitat" markdown="1">
"Die Leitfunde werden dann im Computer durch die Programme ARCH und GGG einer Seriation unterzogen. Diese Programme entwickelte E. Kämmerer. Eine Beschreibung ist der Arbeit beigefügt. Die Programme DOK und ARCH z. Zt. für 600 Typen in 2000 Funden dimensioniert, sind am Rechner TR 440 beim Großrechenzentrum für die Wissenschaft in Berlin in Anwendung." [@goldmann_chronologische_1972, 98.](#goldmann_chronologische_1972)
</div>

---


## Zielsetzung des Beitrags
Ziel dieses Beitrags<sup>[1](#myfootnote1)</sup> ist es Fragen und Themen aufzuzeigen, welche für die Rezension von Forschungssoftware und im die Forschungsprozess eingesetzten digitalen Werkzeugen relevant sind.

Die Beurteilung einer Publikation ist eine traditionsreiche Form des wissenschaftlichen Diskurses. Entsprechend gibt es ein unausgesprochenes Verständnis davon, was eine Rezension umfassen sollte. Unterstützt werden kann dies durch redaktionelle Maßnahmen zur Qualitätssicherung wie redaktionelle Hinweise zum Anfertigen einer Rezension oder - wie es die Redaktion der Archäologischen Informationen praktiziert - eines Reviews der angefertigten Rezension. Die Frage ist jedoch, was sollte eine gute Rezension von Software für den Einsatz in der Archäologie ausmachen? Geht es alleine um die Beurteilung des Beitrags, den Software zur Lösung einer wissenschaftlichen Problemstellung beiträgt? Geht es nicht auch um Aspekte der Nutzbarkeit, der Nachhaltigkeit und Anschlussfähigkeit der Software? Müsste nicht auch betrachtet werden, ob die Software selbst einen wissenschaftlichen Beitrag darstellt? Welche Rolle spielt die Dokumentation des Quellcodes und die Frage der Lizensierung in der Besprechung? Und schließlich, was sind die Leistungen der Software-Entwickler, die eine Besprechung berücksichtigen sollte, und wie kann man so eine Rezension anfertigen?

In dieser Handreichung erläutern wir einige Kriterien für gute Forschungssoftware. Dabei folgen wir den Empfehlungen der Deutschen Forschungsgemeinschaft (DFG) und weisen auf sogenannte ["open standards"](http://xml.coverpages.org/openStandards.html) hin. Software greift im- und explizit tief in den Forschungsprozess ein (für die Archäologie siehe z.B. [@schmidt_marwick_2020](#schmidt_marwick_2020)) und nur durch die Offenlegung von Quellcode ist eine Bewertbarkeit der durch die Software geleisteten Abläufe gewährleistet.

Wir empfehlen in diesem Beitrag eine Vorgehensweise zur Softwarerezension und sammeln Kriterien, die für die Bewertung einer Software von Bedeutung sein können. Wir konzentrieren uns dabei bewusst auf Aspekte, die spezifisch für die Besprechung von Software sind. Dies bringt mit sich, dass die jede Rezension bestimmende Fragestellung nach dem wissenschaftlichen Wert nur gestreift wird, denn an diesem Punkt stimmen die Anforderung an eine Besprechung einer traditionellen Publikation und Software letztlich überein. Aufgrund der Vielfalt der möglichen Besprechungsgegenstände werden nicht in jedem Fall alle Kriterien von Bedeutung sein.    

Die hier vorgestellten Überlegungen, Kriterien und Vorschläge sollen als Arbeitserleichterung dienen und bei der Erstellung einer Softwarebesprechung unterstützen. Der Beitrag ist als Impuls angelegt und wir wünschen uns Diskussionsbeiträge sowie Anregungen. Dazu können entweder die Autoren über die angegebenen Adressen kontaktiert werden oder -- hier website [https://research-squirrel-engineers.github.io/DGUF_Leitfaden/](https://research-squirrel-engineers.github.io/DGUF_Leitfaden/) und Kontaktdaten einfügen ? -- genutzt werden.

## Forschungssoftware

Die weiter unten vorgestellten Kriterien zur Rezension von Software zielen primär auf die Begutachtung von Forschungssoftware ab. Unter Forschungssoftware verstehen wir Software, die mit Fokus auf den Einsatz in der Forschung entwickelt wurde, also um Forschungsdaten zu erzeugen, zu verarbeiten oder zu analysieren [@hettrick_2014_14809](#hettrick_2014_14809). Dies sind beispielsweise Programme, die der Kalibrierung und Umrechnung von Messwerten, der Annotation von Texten und Objekten, oder der Bereitstellung sowie der Verknüpfung und Visualisierung fachlich relevanter Vokabulare dienen.

Forschungssoftware kann entweder für einen sehr spezifischen Bedarf oder aber einen allgemeinen Anwendungsbereich entwickelt werden. Sie ist dabei stets Teil des Forschungsprozesses, der in allen seinen Punkten nachvollziehbar und soweit möglich reproduzierbar sein muss. Forschungssoftware kann hierbei von zwei Blickwinkeln aus betrachtet werden:
1. Forschende wenden eine Forschungssoftware im Kontext ihrer Arbeiten an
oder
2. Forschende entwickeln Forschungssoftware im Kontext ihrer Arbeiten.

Im Gegensatz zur Forschungssoftware steht Software, die zur Nutzung spezifischer Geräte erforderlich ist, wie etwa zur Vermessung, zur fotografischen Dokumentation oder zur Analyse von Oberflächen und Inhaltsstoffen. Häufig handelt es sich dabei um proprietäre Software, die zusammen mit der Hardware vertrieben wird. Obwohl sie im Forschungsprozess eingesetzt wird, entspricht sie nicht unserem Verständnis von Forschungssoftware. Auch digitale Werkzeuge, die eine erhebliche Rolle in der praktischen Arbeit inne haben, jedoch keinen eigentlichen Anteil an der Erhebung, Bearbeitung und Analyse der Daten haben, sind in unserem Sinne keine Forschungssoftware. Trotzdem können auch sie mittels der vorgestellten Kriterien beurteilt werden.

Forschungssoftware ist in besonderer Weise Herausforderungen nachhaltiger Entwicklung und Pflege ausgesetzt. Ein Hauptfaktor für fehlende Nachhaltigkeit von Forschungssoftware ist der Mangel an langfristiger Finanzierung für \`Forschungssoftware-Ingenieure\`, die sich um die geeignete Architektur, Organisation, Implementierung, Dokumentation und Interaktion mit der Gemeinschaft für die Software kümmern, gepaart mit der Umsetzung von Maßnahmen, um die Software während und nach dem Entwicklungsprozess nachhaltig zu machen ([@anzt_environment_2020, 2](#anzt_environment_2020)). Ein Überblick über Bedarfe, Herausforderungen und Lösungsansätze zu Förderung und Finanzierung, Auswahl, rechtliche Fragen, Organisation und Governance, sowie Bündelung von Ressourcen wurde 2019 in einem Workshop der [deRSE Konferenz in Potsdam](https://de-rse.org/de/conf2019/index.html) erstellt ([@bach_dersews19](#bach_dersews19)).

### Forschungssoftware als wissenschaftliche Leistung

In der modernen Forschung ist ein Arbeiten ohne digitale Werkzeuge undenkbar. Dies trifft ebenfalls auf die historische und altertumswissenschaftliche Forschung zu. Mit dem Aufschwung der Digital Humanities wird Forschungssoftware weiterhin und auch zunehmend ein wichtiger Bestandteil des Forschungsprozesses sein.

Trotz der tragenden Rolle, die Forschungssoftware in manch einem Projekt hat, wird die Leistung der Personen, die hinter der Entwicklung und Programmierung stehen, akademisch nicht anerkannt ([@hettrick_2017](#hettrick_2017), [@scheliga_pampel_2017](#scheliga_pampel_2017) und [@katerbow_2018](#katerbow_2018)). Jedoch fließen einerseits bei der Entwicklung von Forschungssoftware teilweise jahrelange technische Erfahrung und Praxis ein. Andererseits wird aber auch Wissen über wissenschaftliche Standards und Praktiken angewendet. Durch die Umsetzung in Code wird Praxis und Wissen explizit gemacht und weiterentwickelt. Diese Leistungen gilt es zu würdigen und sichtbar zu machen ([@scheliga_pampel_2017](#scheliga_pampel_2017), [@katerbow_2018](#katerbow_2018) sowie [@helmholtz_web](#helmholtz_web)).

Als erster Schritt in Richtung Sichtbarmachung wurde 2012 die Berufsbezeichnung des "Software Research Engineers" (RSE, RSEng) geprägt ([@hettrick_2017](#hettrick_2017) und [@baxter_2012](#baxter_2012)). Mittlerweile hat sich auch eine aktive, internationale und interdisziplinäre Gemeinschaft gebildet, die unter anderem auch in Deutschland als de-RSE e.V. tätig ist, Konferenzen organisiert und Empfehlungen gibt ([@anzt_environment_2020](#anzt_environment_2020)). Auch im internationalen Kontext entwickeln sich immer mehr nationale [RSE Sektionen](https://sorse.github.io/contact/chapters/) und gemeinsam von der RSE Community organisierte Konferenzen, wie z.B. [SORSE](https://sorse.github.io). Im Rahmen des Aufbaus einer \`Nationalen Forschungsdateninfrastruktur (NFDI)\` nehmen Forschungssoftware und RSEs einen großen Stellenwert in der Weiterentwicklung der Forschungslandschaft und der Angebote der Forschungseinrichtungen ein ([@loeffler_nfdi4rse20](#loeffler_nfdi4rse20) und [@goedicke_nfdixcs20](#goedicke_nfdixcs20)).

Eine der Forderungen des de-RSE e.V. ist, dass Forschungssoftware mittels geeigneten Publikationsmodalitäten sichtbar gemacht werden soll, da eine Publikation und vor allem deren Auffindbarkeit redundante Arbeit vermeidet ([@anzt_environment_2020, 10](#anzt_environment_2020)). Dabei ist die eindeutige Autorenschaft von großer Bedeutung, da erst dadurch die Leistung der Forschungssoftwareentwicklung an die entsprechenden Personen geknüpft werden. Dies eröffnet weitere akademische Karrierewege, in denen bislang nur klassische Publikationen gewertet wurden. Zukünftig sollten aber in gleicher Weise auch Datenpublikationen, Softwareentwicklung und -publikationen ([https://citation-file-format.github.io](https://citation-file-format.github.io), [https://doi.org/10.5281/zenodo.1003149](https://doi.org/10.5281/zenodo.1003149)), Annotationen, sowie deren Zitationen Kriterien der Beurteilung der wissenschaftlichen Leistung sein (s. [NFDI4Culture](https://nfdi4culture.de), [RSE4NFDI](https://www.rse4nfdi.de/de/index.html), [NFDI4Objects](https://www.nfdi4objects.net)).

Ein frühes Beispiel für die Nennung der Autorschaft von Forschungssoftware in der Archäologie gibt das einleitende Zitat. Allerdings gibt es grundlegende Unterschiede zur gewohnten Publikation und Zitation von Aufsätzen und Büchern. Da die Entwicklung von Software auf bereits bestehenden Modulen aufbaut, muss das Verständnis von Autorenschaft und wie sie sich über die Lebenszeit der Software hinaus dokumentieren lässt spezifisch für Software erfolgen [@katz_software_2016](#katz_software_2016).

Eine publizierte Software kann anschließend, ganz so wie in der bisherigen Praxis der altertumswissenschaftlichen Forschung, begutachtet werden. In einer Rezension kann diese dann einem breiteren Publikum vorgestellt werden. Mit der Einführung der Rezensionskategorie "Archäoinformatik" intendiert die Redaktion der Archäologischen Informationen genau dies. Durch eine dedizierte Rezension von Software analog zu Rezensionen wissenschaftlicher Publikationen, wird die wissenschaftliche Leistung der Autoren und Autorinnen von Forschungssoftware mittels gewohnten Formaten sichtbar und anerkannt. Gleichzeitig wird auch ihre Verantwortung und Teilhabe manifest.

### Gute Forschungssoftware

Um überhaupt Kriterien zur Rezension und Bewertung von Forschungssoftware aufstellen zu können, stellt sich zunächst die Frage, was eigentlich gute und moderne Standards entsprechende Forschungssoftware ausmacht. Natürlich gehören dazu eine Vielzahl fachlicher und technischer Aspekte, die weiter unten beleuchtet werden sollen. Darüber hinaus muss Software aber wie jedes andere Werkzeug zunächst hinsichtlich ihrer generellen Eignung für nachhaltiges und ethisches wissenschaftliches Arbeiten bewertet werden.

Die DFG formuliert mit ihren "Leitlinien zur Sicherung guter wissenschaftlicher Praxis" ([@deutsche_forschungsgemeinschaft_2019](#deutsche_forschungsgemeinschaft_2019)) eine Reihe von Vorgaben für gutes wissenschaftliches Arbeiten. Die Leitlinien entsprechen einem internationalen Konsens und etablierten Prinzipien. Zu den Anforderungen gehören etwa die Einhaltung und Etablierung von Standards und Methoden, eine nachvollziehbare Dokumentation des Weges zu Ergebnissen, die öffentliche Zugänglichkeit von Ergebnissen und die Archivierung der notwendigen Materialien, die zu Ergebnissen geführt haben.

Einige der Kriterien, die in den DFG-Leitlinien explizit und implizit anklingen, sollen im folgenden näher ausgeführt werden: Die in der Erläuterung zu Leitlinie 13 (*Herstellung von öffentlichem Zugang zu Forschungsergebnissen*) genannten FAIR-Prinzipien, die Prinzipien der Offenen Wissenschaft (Open Science) und zuletzt die CARE-Prinzipien, die in den Leitlinien 2 und 10 anklingen. Darüber hinaus sind weitere Hinweise zur Umsetzung der DFG-Leitlinien in Bezug auf Forschungssoftware unter [@forschungsdaten_info_dfg](#forschungsdaten_info_dfg) zu finden.

#### FAIR-Prinzipien

Die FAIR-Prinzipien wurden 2016 als *FAIR Data Principles* veröffentlicht [@wilkinson_2016](#wilkinson_2016). Sie zielen primär auf Forschungsdaten und deren Metadaten ab und fordern, dass diese auffindbar (Findable), zugänglich (Accessible), interoperabel (Interoperable) und nachnutzbar (Reusable) sind. Die Prinzipien können auch auf Forschungssoftware und deren Metadaten übertragen werden ([@lamprecht_towards_2019](#lamprecht_towards_2019), [@goedicke_nfdixcs20](#goedicke_nfdixcs20)).

Die Anwendung von FAIR-Prinzipien fördert die Qualität der Software hinsichtlich der grundsätzlichen Ansprüche an Interoperabilität bei der Verwendung in einem Workflow und der Verwendung von Standards und etablierten Paradigmen des Programmierens und der Dokumentation. Die FAIR-Prinzipien beziehen sich nicht auf die wissenschaftliche Qualität des Tools. Dennoch ergeben sich eine Anzahl von Kriterien, die in die Beurteilung einer Forschungssoftware einfließen und von Angaben, die im Rahmen der Rezension als Serviceleistung zu erbringen sind, wie die Nennung der Autorenschaft, des zur Speicherung verwendeten Repositoriums oder die Beschreibung möglicher nötiger Voraussetzungen zur Verwendbarkeit.

Ein Fokus der FAIR-Prinzipien ist, dass Daten, bzw. Forschungssoftware, und Metadaten auch maschinell lesbar und verarbeitbar sind. Dies betrifft vor allem die Prinzipien 'Accessible' und 'Interoperable'.

##### Findable (Auffindbar)

Software wird durch die Speicherung zusammen mit ihren Metadaten in dedizierten Softwarerepositorien auffindbar, die kommerziell, community-basiert und in vielen weiteren Formen starke Impulse für die Entwicklung der wissenschaftlichen Infrastrukturen geben. Die Auffindbarkeit wird durch die fachwissenschaftliche Einbindung und die klassische Arbeit von Forschungsinfrastrukturen zusätzlich erhöht, da sie Aufbau, Pflege und Anwendung von kontrolliertem Vokabular und Metadatenstandards zur Indexierung betreiben ([@lamprecht_towards_2019](#lamprecht_towards_2019) und [@anzt_environment_2020, 10](#anzt_environment_2020)).

Die Vergabe von persistenten URIs durch Repositorien sowie die Nennung der Autorenschaft ermöglicht das Zitieren von Forschungssoftware. Wichtig ist dabei, dass Software, da sie im Gegensatz zu herkömmlichen Publikationen kontinuierlich weiterentwickelt wird, in unterschiedlichen Entwicklungsständen abgelegt wird, damit bestimmte Versionen zitiert werden können [@forschungsdaten_info_dfg](#forschungsdaten_info_dfg).

##### Accessible (Zugänglich)

Entsprechend den FAIR-Prinzipien sollte Software und die sie beschreibenden Metadaten über ihre persistente URI erreichbar sein. Dies sollte auch maschinell über ein offenes und standardisierte Kommunikationsprotokoll möglich sein [@lamprecht_towards_2019](#lamprecht_towards_2019).

> [AK] Satz ist kaputt eine offenes Was?

Weitere Aspekte, die die Zugänglichkeit erleichtern, sind die Verfügbarkeit für verschiedene Betriebssysteme, sowie technische Anforderungen, die von aktuell verbreiteten Geräten geleistet werden können. Eine verständliche Anleitung zur Nutzung des Programms verbessert die Zugänglichkeit im Sinne der Nutzbarkeit.


##### Interoperable (Interoperabel)

Interoperabilität von Software kann sich zum Einen auf die Kompatibilität der Ein- und Ausgabeformate mit anderen Programmen in einem Arbeitsprozess (horizontale Dimension) beziehen. Zum Anderen verweist sie auch auf die Zusammenarbeit der verwendeten Komponenten in der Software selbst (vertikale Dimension) [@lamprecht_towards_2019, 46 f.](#lamprecht_towards_2019). Beides wird durch die Verwendung von Standards ermöglicht, die die Zusammenarbeit von Softwarekomponenten auch über Betriebssystemgrenzen hinweg ermöglicht.

##### Reusable (Nachnutzbar)

Die Nachnutzbarkeit von Software hängt von mehreren Komponenten ab. Die Metadaten und eine umfassende Dokumentation der Software sollten es anderen ermöglichen, Ergebnisse zu reproduzieren sowie eigene Daten und veränderte Anwendungsfälle zu prozessieren. Eine geeignete Lizenz, die auch die abhängigen Softwarekomponenten berücksichtigt, gibt zudem darüber Auskunft, welche Regeln bei der Nutzung gelten und ob eine Weiterentwicklung des Codes möglich ist. Für die Zitierbarkeit ist eine Nennung der Beteiligten notwendig [@lamprecht_towards_2019, 48-49](#lamprecht_towards_2019).

> [AK] Sind mit Beteiligten, die Autoren/Entwickler gemeint? Wenn ja, idealerweise anpassen denke ich, damit wir bei ein-zwei Bezeichnungen bleiben.

#### Open Science

Open Science (Offene Wissenschaft) bezeichnet eine Wissenschaftspraxis, deren Ziel ein transparenter, replizierbarer und kollaborativer Forschungsprozess ist [@bezjak_openscience_2018, Open Concepts and Principles](#bezjak_openscience_2018). Open Science setzt sich aus mehreren Prinzipien zusammen, die unterschiedliche Stadien im Forschungsprozess betreffen.

> [AK] "replizierbar" kennt der Duden nicht (ich eh nicht), kann man trotzdem natürlich verwenden, wenn es wichtig ist. Ansonsten würde ich hier reproduzierbar als Alternative vorschlagen

So fordert Open Science nicht nur die Öffnung der Ergebnisse (Open Access), sondern auch der zugrundeliegenden Daten (Open Data), Methoden (Open Methodology) und der verwendeten Forschungssoftware (Open Source). Für offene Forschungssoftware gilt, dass ihr Quellcode zugänglich und mit einer Lizenz versehen sein muss, die die Weiterentwicklung erlaubt [@bezjak_openscience_2018, Open Research Software and Open Source](#bezjak_openscience_2018).

In den Leitlinien der DFG klingt die Öffnung von Software-Quellcode im Zusammenhang mit der Qualitätssicherung [@deutsche_forschungsgemeinschaft_2019, 14-15](#deutsche_forschungsgemeinschaft_2019) und der Herstellung von öffentlichem Zugang zu Forschungsergebnissen [@deutsche_forschungsgemeinschaft_2019, 19](#deutsche_forschungsgemeinschaft_2019) an.

Mit der Forderung nach der Offenlegung des Quellcodes (Open Source) wird auch dem Gedanken der Nachnutzbarkeit entsprochen. Die Offenlegung wird erweitert um die Forderung, den Code zudem frei nutzbar zur Verfügung zu stellen (Free Source) [@stallman2001free](#stallman2001free). Letzteres wird als FOSS (Free/Libre Open Source Software) bezeichnet und in Deutschland z.B. von anwendungsbezogenen Wissenschaftlern und Entwicklern aus der Geoinformatik vertreten ([FOSSGIS e.V.](https://www.fossgis.de)) oder auch von Research-Software-Engineers in der ["de-RSE e.V."](https://de-rse.org/de/association.html) [@anzt_environment_2020](#anzt_environment_2020).

#### CARE-Prinzipien und Ethos

In den Leitlinien der DFG werden in Leitline 2 und 10 ethische Aspekte im Forschungsprozess angesprochen, die nach unserer Meinung auch im Bereich der Forschungssoftware Beachtung finden sollten.

Tatsächlich ist Forschungssoftware nicht politisch neutral. Ihre Architektur reflektiert ihre Entstehungsbedingungen, ihre Nutzung erfolgt unter spezifischen Voraussetzungen und auch ihre Weitergabe unterliegt den vorherrschenden Konventionen und Gewohnheiten. Vielfach tragen gerade diese Gewohnheiten zur (unbewussten) Festigung von Privilegien und Diskriminierungen bei: Für archäologische Feldarbeit wird oft Software zur Datenaufnahme eingesetzt, die für die Mehrheit der Mitarbeiter vor Ort aufgrund einer Sprachbarriere nicht verständlich ist, proprietäre Software oder teure Hardware benachteiligt die Forschung, die mit weniger Finanzmitteln auskommen muss, und die Texte der Handbücher kennen oft ausschließlich männliche Nutzer.

Eine Personengruppe, die besonders oft zum passiven Spielball von Forschungssoftware und Datenverarbeitung geworden ist, sind indigene Bevölkerungsgruppen. Gerade in den Archäologien, in denen häufig an fremden Kulturen und Kulturhinterlassenschaften geforscht wird, sollten Traditionen und Wissen der indigenen und der ortsansässigen Bevölkerungsgruppen zum kulturellen Erbe in eine Mitbestimmung über die Erforschung münden. Hierfür eignen sich die CARE-Prinzipien ([https://www.gida-global.org/care](https://www.gida-global.org/care)). Sie wurden von der [Global Indigenous Data Alliance (GIDA)](https://www.gida-global.org) und der [Research Data Alliance (RDA)](https://www.rd-alliance.org) 2018 auf Basis der [UN Declaration on the Rights of Indigenous Peoples (UNDRIP)](https://www.un.org/development/desa/indigenouspeoples/declaration-on-the-rights-of-indigenous-peoples.html) erarbeitet und konzentrieren sich explizit auf Forschungsdaten. Ihre vier Grundpfeiler Kollektiver Nutzen (Collective Benefit), Souveränität (Authority to Control), Verantwortung (Responsibility) und Ethik (Ethics) sind jedoch auch für Forschungssoftware und für jeden Kontext der Forschung relevant, in dem ein Ungleichgewicht von Machtverhältnissen existiert.

##### Collective Benefit (Kollektiver Nutzen)

Dieser Punkt fordert den gemeinschaftlichen Nutzen der Datenerhebung für die indigene und die ortsansässige Bevölkerung. Er lässt sich leicht auf Software übertragen: Software, die auf Wissen und Erfahrungen von indigenen Bevölkerungen beruht, soll für diese Gruppen einen Nutzen haben. Hier geht es darum, dass Menschen, die einen wichtigen Beitrag für die Entwicklung geleistet haben, honoriert werden und die Anwendung nicht nur Fremden zugute kommt (monetär, durch Reputation u.ä.).

##### Authority to Control (Souveränität)

Die Kontrollmacht über die eigenen Daten ist eine wichtige Forderung indigener Menschen und der örtlichen Bevölkerung. Auch dies lässt sich auf Software anwenden: Die Entscheidungsmacht über die Verwendung von anhand ihres Wissens entwickelter Software soll bei den genannten Gruppen liegen. Dieser Punkt kann verhindern, dass ihr Wissen unangemessen ausgenutzt wird, und kann durch die computertechnische Ermächtigung von den indigenen und den ortsansässigen Gruppen verstärkt werden.

> [AK] Was genau ist her mit ""computertechnische Ermächtigung" gemeint?

##### Responsibility (Verantwortung)

Wer mit Daten arbeitet, die auf dem Wissen und den Traditionen indigener Gruppen beruhen, hat die Verantwortung, nachvollziehbar aufzuzeigen, wie diese Daten den Gruppen zugute kommen. Entwickler von Software haben Verantwortung für die positiven Folgen der Software für die indigenen Gruppen zu übernehmen. Bei der Entwicklung ist es die Verantwortung der Produzenten, mögliche schädliche Konsequenzen der Software abzuwenden. Dies kann durch inklusive Ansätze bei der Entwicklung verfolgt werden.

> [AK] Hier bitte klären, wo wirklich die Entwickler und wo die Produzenten (öhm.. z.B. ESRI oder so) gemeint sind. Ist für mich nicht ganz klar.

##### Ethics (Ethik)
Rechte und Wohl der indigenen Bevölkerungsgruppen sollten an erster Stelle bei der Erarbeitung und Bearbeitung eines Datensatzes stehen. Für Software gilt das selbe, wenn sie indigene Gruppen betrifft.

> [SCS] muss nochmal auf angemessene Sprache geprüft werden (Indigene oder indigene wird zB im englischsprachigen diskutiert. "Bevölkerungen" oder "Völker" etc)
> [AK] habe ein wenig daran gemacht und angelehnt an DFG-Handreichung (https://www.dfg.de/download/pdf/dfg_im_profil/gremien/senat/biologische_vielfalt/191212_erlaeuterungen_entwicklungsvorhaben.pdf) auch ortsansässige Gruppen berücksichtigt. "indigen" als Begriff habe ich nicht angefasst - fehlt mir die Kenntnis.


## Mögliche Vorgehensweise zur Rezension archäologischer Forschungssoftware

Nach unserem Verständnis sollte eine Rezension archäologischer Software, so wie es eine herkömmliche Besprechung einer wissenschaftlichen Publikation leistet, die Software zunächst vorstellen, dabei zusammengefasst Eckdaten vorlegen und den Kontext erläutern. Im Anschluss sollte eine kritische Beurteilung erfolgen.

Umgesetzt auf Software gehören zu den Eckdaten Angaben zur Version und den Releasedaten, zu den Entwicklern, der Lizenz und Weiteres. Als Kontext verstehen wir eine erste Einordnung in das archäologische Forschungsfeld und Angaben zum möglichen Zusammenhang mit Forschungsprojekten, Arbeitsgruppen oder Institutionen. Für die kritische Beurteilung aus unterschiedlicher Perspektive haben wir unten einen Katalog an Fragen zusammengestellt. Zuletzt sollten die Ergebnisse der Betrachtung in einer Stellungnahme zusammengefasst werden, die die Software hinsichtlich ihrer Nützlichkeit, ihrer Bedienbarkeit, ihrer handwerklichen Qualität und ihrer Position in Relation zu den Idealen guter Forschungssoftware (z.B. FAIR und CARE), beurteilt.

Der Umfang der Rezension für die Veröffentlichung in den Archäologischen Informationen sollte 1000-2000 Worte nicht übersteigen.

> [AK] Das ist eine Frage der Redaktionsrichtlinien der Arch. Information. meiner Meinung nach nicht unser Doing und engt dei Übertragbarkeit, dieses sehr guten, generellen Aufschlags unnötig ein.

Selbstverständlich setzt die Rezension einer Forschungssoftware die Sichtung der Dokumentation, begleitender Publikationen ebenso voraus, wie die praktische Erprobung der Software selbst. Dabei ist eine realistische und transparente Einschätzung der eigenen Kompetenzen und des eigenen Nutzungsinteresses ein wichtiger Anhaltspunkt für die Leser, denn die Leserschaft ist wesentlich heterogener hinsichtlich ihrer Interessen, als man es bei der Besprechung einer Fachpublikation annehmen darf. Es ist eine wichtige Information, ob die Rezension ganz von der Anwendungsperspektive geschrieben ist, oder auch die Entwicklerperspektive umfasst.  

## Fragenkatalog zur Beurteilung von Software

Im folgenden stellen wir einen kommentierten Fragenkatalog vor, der auf Kriterien zur Beurteilung von archäologischer Forschungssoftware hinarbeitet. Er ist untergliedert in drei Bereiche, die jeweils Fragen aus verschiedenen Kompetenzbereichen bündeln. Dabei bilden die ersten zwei Bereiche die wissenschaftliche Verwendung und die Anwendung und Bedienbarkeit aus Nutzersicht ab. Der dritte Bereich enthält Fragen, die für Entwickler und IT-Administratoren von hohem Interesse sind und die daher die Anwendbarkeit und Nachhaltigkeit in den Blick nehmen. Im Anschluss stellen wir Merkmale vor, die eventuell tabellarisch einer Rezension beigegeben werden sollten, aber nur im Ausnahmefall vom Rezensenten kritisch beurteilt werden.
Wie bei der Besprechung einer wissenschaftlichen Publikation ist die Zusammensetzung und Gewichtung der einzelnen Merkmale vom Rezensenten selbst zu bestimmen und in Relation zum Thema zu setzen. Entsprechend verstehen wir unseren kommentierten Fragenkatalog auch als eine Art Maximalversion, die bei der Anfertigung und der Einschätzung der eigenen Kompetenzen Hilfe geben kann.

### Einsatz in der Archäologie und wissenschaftlicher Zweck

Wissenschaftliche Software hat einen konkreten Zweck, verfolgt und erfüllt eine bestimmte Aufgabe. Dabei sind zwei Dimensionen zu unterscheiden. Dies ist zum einen, und das ist für Forschungssoftware vorrangig, die Frage, ob die Software einen sinnvollen Beitrag zur Bearbeitung der archäologischen Fragestellung liefert. Zum anderen ist zu beurteilen, ob Software eine korrekte Umsetzung der angestrebten Arbeit leistet. Letzteres, also die Korrektheit der Ergebnisse einer Software, ist mitunter schwer zu beurteilen, insbesondere dann, wenn es keine weiteren Implementierungen des Algorithmus in anderen Softwarepaketen gibt. Dieses Problem gliedert sich in mehrere Aspekte: Zunächst stellt sich die sehr technische Frage, ob die in der Dokumentation genannten Algorithmen fehlerfrei in Programmcode ausgedrückt wurden. Meist ist schon eine Prüfung dieses Aspekts nicht trivial und übersteigt den Rahmen einer Rezension. Darüber hinaus versprechen wissenschaftliche Softwarewerkzeuge implizit oder explizit, die Beantwortung wissenschaftlicher Fragestellungen zu ermöglichen oder zumindest zu vereinfachen. Eine GIS-Applikation zur Analyse von Punktmustern kann etwa für den Zweck konzipiert sein, menschliches Siedlungsverhalten nachherzusagen. Die Frage, ob der Algorithmus dazu semantisch überhaupt in der Lage ist, kann den Umfang einer Rezension bei weitem übersteigen. Es bleibt aber beim Rezensenten, eine Einschätzung der Plausibilität vorzunehmen und auch das Problem der Einschätzbarkeit selbst offenzulegen, um so die Leser dafür zu sensibilisieren.

#### Wissenschaftlicher Zweck und Beurteilung der Korrektheit

* **Welches Problem versucht die Software zu lösen?** Welche Aufgaben werden mittels der Software bei der Erfassung, der Verarbeitung oder der Analyse von Daten durchgeführt? Wie sind diese Probleme und Aufgaben von ihrer Relevanz und von ihrer Häufigkeit in einem archäologischem Kontext einzuschätzen? z.B. "Schätzung von Bevölkerungsdichte aus Siedlungsgröße" oder "Statikmodellierung für Langhäuser"

* **Gibt es Archäologie-relevante erfolgreiche Projekte/Anwendungen, die von dieser Software bereits unterstützt wurden?** Wie plausibel sind die erzielten Resultate? Wurden Ergebnisse der Projekte kritisiert, die insbesondere auf jene Ergebnisse beruhen, die mit der Software erzielt wurden?

* **Wie funktioniert der (wissenschaftliche) Algorithmus, der mit der Software implementiert wurde?** Welche wesentlichen Schritte durchlaufen Daten, um das Ausgangsproblem zu lösen? z.B. "Die Eingabedaten werden mittels eines Referenzdatensatzes bereinigt, mit hierarchischer Clusteranalyse klassifiziert und zuletzt als paarweise Distanzmatrix visualisiert"

* **Wie löst die Software das gegebene Problem?** Wie ist die grundsätzliche Funktionsweise konzipiert? Was sind die wesentlichen Bestandteile in Frontend und Backend? z.B. "WebApp als Schnittstelle zu einer Datenbank" oder "Command line interface um ein Neuronales Netz für Nachhersage zu trainieren"

* **Wie ist die Software publiziert?** Eignet sich die Software für wissenschaftliche Anwendungen, da sie in einer zitierbaren Publikation vorgestellt wurde? Sind einzelne Versionen klar als solche referenzierbar (etwa mittles DOI)? z.B. "Das Softwarepaket wurde in einer kurzen, zweiseitigen Publikation im Journal *Open Source Software* vorgestellt, diese Publikation schließt aber keine umfassenden Tests oder Vergleiche mit Alternativprodukten ein"

* **Ist die Behauptung, eine bestimmte wissenschaftliche Fragestellung mit dem gewähltem Algorithmus lösen zu können, korrekt?**

> [AK] Hier ist mir nicht klar: Ist das nicht genau das was, ober ausführlich als besonders komplexes Problem erläutert wurde?

* **Sind die Algorithmen korrekt implementiert worden?**
* Ist das wissenschaftliche Ergebnis jenseits aller technischen Unterschiede vergleichbar zu anderen Implementierungen/Tools
* Sind die verwendeten Algorithmen dokumentiert und hinreichend wissenschaftlich belegt?

#### Bedienbarkeit und Zielgruppenorientierung
Die Bedienbarkeit von Forschungssoftware ist von zentraler Bedeutung, da sie als Flaschenhals alle Interaktion zwischen Nutzer und Software bestimmt. Über Installation, grafischem Interface (GUI) und Maschinenschnittstellen hinaus, sind auch Hilfefunktionen und die Größe und Aktivität der Nutzercommunity entscheidend für die praktische Bedienbarkeit. Gerade letzteres ist auch für die Zukunftsfähigkeit und damit die Eignung für den Einsatz auf institutioneller Ebene und in langfristigen Vorhaben von zentraler Bedeutung.

Die folgenden Fragen richten sich auf technische Merkmale, die die Benutzbarkeit (Usability) betreffen. Weitere technische Merkmale aus einer Entwickler-zentrierten Perspektive betrachten wir weiter unten.

##### Installation
* **Wie funktioniert die Installation und wo wird die Software vorgehalten?** Gibt es ein Installationsskript oder ist die Software nur als Quellcode verfügbar, der zunächst selbst kompiliert werden muss? Ist die Lösung angemessen für den Nutzerkreis? Installationsskripte ermöglichen einen viel breiteren Anwenderkreis, das Kompilieren erlaubt geübten Nutzern die Installation u.U. auf verschiedenen Endgeräten.

> Hier ist mir nicht klar ob der "Archäologe" weiß was eine Kompilierung ist...
Installiert das Installationsskript alle Abhängigkeiten uzum reibungslosen Ablauf der Software oder gibt sie Hinweise auf weitere Installationen die durch den Benutzer vorgenommen werden müssen?

> [AK] Und wieder: es gibt ihn nicht, "den Archäologen". Es gibt nur Leser von Softwarerezensionen in der arch. Info und für die soll die Rezension herausstellen, ob das Programm voll einfach oder voll schwierig zu installieren ist. Wiederum ist "voll schwierig" dann okay, wenn die Software in einem spezifischen Kontext zum Einsatz kommt, in dem man Menschen wie viele der Autorinnen dieses Beitrags hat.

* **Handelt es sich um eine standalone Software, oder um eine Webanwendung?** Passt die Lösung der Plattform zum archäologischen Einsatz? Ist z.B. eine Webanwendung unter allen Arbeitsbedingungen und Einsatzgebieten sinnvoll? Ist vielleicht auch beides möglich?
* **Ist klar erkennbar, welche Voraussetzungen die Hardware zu erfüllen hat?** Ist eine Spezifikationen vorhanden?
* **Was waren die eigenen Erfahrungen bei der Installation der Software?** Dabei ist natürlich wichtig, die eigene Umgebung und eigene Kompetenz darzustellen. Manchmal ist es für Leser besonders hilfreich, zu erfahren

##### Interface
Die Nutzbarkeit wird zentral von den Möglichkeiten der Kommunikation von Mensch und Software bestimmt, also dem der Software-Oberfläche (UI). Diese mag in manchen Fällen graphisch gestützt sein (GUI), in anderen Fällen rein kommando-basiert (z.B. API). Die Gestaltung von Oberflächen und die Nutzerführung in Menüstrukturen sind ein eigenes Aufgabenfeld in der Softwareentwicklung und können erhebliche Kosten erzeugen. Gut an den Nutzer angepasste Lösungen sind das Ergebnis einer genauen Kenntnis der Zielgruppe, ihrer Gewohnheiten und Bedarfe, im Falle archäologischer Forschungssoftware also der Forschungspraxis. Ein gutes Interface unterstützt das fehlerfreie effiziente Arbeiten. So sind z.B. Verständlichkeit der Menü-Einträge oder der Kommandos, aber auch die Aussagekraft von Fehlermeldungen Aspekte, die in der Rezension betrachtet werden sollten. Barrierefreiheit ist bislang ein unzureichend abgedecktes Kriterium, das aber ebenfalls die Effizienz und den möglichen Nutzerkreis adressiert. Auch bei diesem Punkt liegt die Gewichtung im Ermessen des Rezensenten.

* **Passt die UI (GUI oder Konsole) zum Nutzerkreis?**
Jeder Nutzerkreis, auch der des Reviewers wird bestimmte Erwartungen an die Präsentation der Anwendung haben. Beispielsweise ist es möglich, dass ein Benutzerkreis sich mit einer Kommandozeilenanwendung sehr gut zurechtfinden wird. Ein anderer Benutzerkreis wird mit dieser Form der Präsentation der Anwendung Probleme bei der Nutzung haben. z.B. "Die Abfragen an den Dienst können sowohl über die Webapp mit ihrem Suchschlitz und Filterfunktionen, als auch über eine REST-Schnittstelle gestennt werden. Auf diese Weisen werden zwei verschiedene Nutzerhǵruppe angesprochen."

Stellt z.B. die Nutzung einer eigens zu installierenden Shell eine Hürde dar?
> hier kommt plötzlich Shell ins Spiel...
> [AK] Ist das nicht letztlich eher ein Punkt, der zur Isntallation und den Spezifikationen gehört?

* **Orientiert sich die Menüführung an bestimmten Vorbildern?**
> [anonym] Das muss man nicht bewerten
> [TH] Hiermit meine ich ob z.B. Tastenkürzel die in anderen Softwares gängig sind so übernommen werden oder ob gänzlich andere Standards gesetzt werden. Letztlich ist es eine Frage der Schwierigkeit der Einarbeitung in die Software, ob sie genutzt wird. Menüführungen, Tastenkürzel oder andere Funktionen die sich an anderen Softwares orientieren erleichtern die Einarbeitung immens.
> [AK] Hier bin ich ganz bei Timo. Natürlich erleichtert es die Einarbeitung und die Akzeptanz einer Software sehr, wenn sie sich an den Gewohnheiten orientiert.  

* **Ist das Programm mehrsprachig bzw. in welchen Sprachen wird es angeboten?**
Je nachdem, von wem das Programm eingesetzt werden soll, sollte das Programm in mehreren Sprachen angeboten werden. Üblicherweise wird man das Programm zumindest in einer englischen Fassung erwarten. Sollten verschiedene Sprachversionen getestet werden, so ist darauf zu achten, dass das Layout der Anwendung in den verschiedenen Sprachen weiterhin sichtbar ist. Beschriftungen von Buttons beispielsweise können sich in der Länge des Textes in verschiedenen Sprachen stark unterscheiden, so dass bei schlechter Programmierung der Anwendung ggf. Texte im Benutzerinterface abschnitten sind.

* **Sind die Fehlermeldungen für die Rezensentin gut verständlich?**
Fehlermeldungen dienen zwei Funktionen. Die erste Funktion ist eine Fehlermeldung an den Benutzer, so dass dieser eine Aktion zur Behebung des Fehlers ergreifen kann. Diese Fehlermeldungen müssen für den Nutzer verständlich formuliert und auffallend in der Anwendung platziert werden. Versteht ein Benutzer den Inhalt der Fehlermeldung nicht, so hat die Fehlermeldung ihren Nutzen verfehlt. Die zweite Funktion einer Fehlermeldung ist ggf. ein Feedback an die Entwickler der Anwendung. Dieses muss die Fehlermeldung so kommunizieren und ggf. auch einen Fehlerreport zur Behebung des Fehlers an die Entwickler schicken. Unverständliche Fehlermeldungen wie Stack Traces oder aus der Ausführungsumgebung übernommene Fehlermeldungen verfehlen oft ihre Wirkung.
> Was sind Stack Traces? ;-)
> [AK] Ich kann mit Stack Traces leben, weil ich davon ausgehe, dass es eben genau diese Dinge sind, die die Entwickler verstehen müssen. Ist das nicht der Fall, muss man es aber ändern

##### Zielgruppe
* **Ist die archäologische Nutzung vorgesehen?**
Entspricht der archäologische Einsatz den generellen Anwendungszenarien, den die Entwickler vor Augen hatten? Hat das Einfluss auf die Nutzbarkeit aus wissenschaftlicher Perspektive? Z.B. "Diese CAD Software ist für Architekturanwendungen konzipiert und konfrontiert den durchschnittlichen Grabungstechniker mit überwältigendem Funktionsumfang."

##### Hilfefunktionen, Tutorials und Community
Neben Hilfefunktionen und Tutorials ist es von großer Bedeutung, ob die Software von einer *Community* getragen wird. Die Zahl der aktiven Nutzer eines Softwarewerkzeugs ist entscheidend dafür, ob man im Falle von Problemen Hilfe in Foren findet. Ist der Nutzerkreis sehr klein, findet der Wissenstransfer dagegen häufig im persönlichen Austausch statt, ist somit kaum dokumentiert und hängt stark von personellen Netzwerken ab. Diese können wiederum den großen Vorteil bieten, dass konkrete Fragen individuell von den Entwicklern aufgegriffen werden. Belege dafür können sich in öffentlichen Kommentarfunktionen von Webseiten der Entwickler und z.B. über Issues im Softwarerepositorium abzeichnen. Zum Austausch mit den Entwicklern werden weiter unten weitere Kriterien erläutert.

* **Gibt es ausreichend Tutorials für das Erlernen der Software?**
Hier sollte überprüft werden, ob die Tutorials auf unterschiedliches Vorwissen eingehen und gegebenenfalls auch kenntlich machen, welches Grundwissen, welche Erfahrungen unabdingbar sind. Ein weiterer Aspekt bei den Anleitungen, Tutorials und FAQs ist die Frage der Sprachen.

* **Gibt es Anwendungsbeispiele der Software, ggf. Beispieldatensets und eine Anleitung für diese, um ein Verständnis für die Funktionsweise zu entwickeln?**
Dieser Punkt ist eng mit der Frage nach Tutorials verbunden, so greifen Tutorials oftmals auf Übungsdaten zurück. Die Übungsdaten von Forschungssoftware sollten sich dabei eng an der wissenschaftlichen Praxis orientieren und dennoch ohne spezifische Vorkenntnisse verständlich sein. Sie sollten frei zur Verfügung stehen und möglichst ohne Registrierung nutzbar sein.

> [AK] Hier wäre ein positives Beispiel ideal

* **Wo finde ich mehr Informationen zu dieser Software? Hyperlinks und Referenzen?**
Gibt es auf den Informationsseiten der Software oder in den Tutorialmaterialien Hinweise auf weitere Materialien zur Software? Wird auf Publikationen und Beiträge der Entwickler selbst wie auch Rezensionen hingewiesen?

* **Wird die Software von einer Community getragen? Ist diese möglicherweise ganz oder teilweise altertumswissenschaftlich ?**
Beispiele für die Softwareentwicklung, die zunächst ganz aus einer altertumswissenschaftlichen Community heraus betrieben wurde und sich inzwischen fachlich erweitert hat, sind die [Pelagios Commons](https://pelagios.org/) und die WebApp [Recogito](https://recogito.pelagios.org/). Aktive Nutzergrupen mit einem Fokus auf archäologische Fragestellungen haben sich auch z.B. innerhalb der Cuommunities großer Softwarepakete wie QGIS oder R entwickelt.

>[AK] Hier wäre ich über konkrete Adressen / Foren /Anlaufstellen für Communities als Beispiele sehr froh !

* **Haben ArchäologInnen bereits Best Practices für diese Software formuliert?**

>[AK] Hier wäre ich über konkrete Beispiele sehr froh und auch eine kurze Erläuterung, was Best Practices an dieser Stelle meint.


##### Dateningest, Interoperabilität und Schnittstellen
Für viele Nutzer spielen Datenformate eine große Rolle, da diese die Kompatibilität zu anderen Anwendungen bestimmt. Dies betrifft sowohl, welche Datenformate gelesen, als auch geschrieben werden können. Bei vielen Anwendungen werden die unterstützten Dateiformate allein durch den entsprechenden Menü-Eintrag  (z.B. "speichern unter") klar und es ist hilfreich, im Rahmen einer Rezension dies zu erläutern. Auch die Form des Uploads von Daten und das Vorhandensein von Schnittstellen machen einen wesentlichen Aspekt des praktischen Einsatz aus und sollten in einer Rezension bedacht werden.

* **Welche Datenformate werden wie eingelesen?**
Bei der Auswahl der Datenformate die von einer Software eingelesen werden können sollten, gibt es verschiedene Gesichtspunkte zu beachten:
  * Sind alle relevanten Datenformate für die Aufgabe, die die Software lösen soll, einlesbar? Diese Einschätzung sollte auf dem Arbeitsalltag eines typischen Anwenders beruhen.
  * Können Datenformate auch von gängigen Repositories eingelesen werden (z.B. Webservices, Git, Cloud Services)?
  * Werden offene Datenformate unterstützt?

* **Welche Datenformate werden ausgegeben?**
Die Ausgabe von Daten nach der Bearbeitung sollte am Besten in Datenformaten erfolgen, die eine Weiterverarbeitung in anderen (auch Open Source) Softwarepaketen zulassen. Dies bedarf üblicherweise mindestens eines Formates, dessen Spezifikation frei verfügbar ist, sodass Open Source Software dafür entwickelt werden kann.
Sollten nur Exporte in einem proprietärem, ggf. von der Software definierten Format möglich sein, muss es dafür schwerwiegende Gründe geben.

* **Wie können Daten eingeladen werden? Als Masseningest oder einzelne *Uploads*?**
Für serh viele Anwendunsgszenarien, ist es entscheidend, ob eine Software einen einmal definierten Task massenweise auf eine Reihe von Dateien ausführen kann. Ein Beispiel kann hier eine Transformation von Bilddaten sein, die auf jedes Foto einer Ausgrabungskampagne ausgeführt werden soll. Um dies zu gewährleisten, muss die Software die Spezifikation entweder eines Ordners von Dateien oder einer Spezifikation von verschiedenen Dateipfaden unterstützen.

* **Gibt es eine API?**
Diese Frage beschäftigt sich mit dem Vorhandensein einer Programmierschnittstelle (API). Neben der Bedienbarkeit durch einen Menschen, ist es wichtig, dass auch andere Software ggf. mit dem Softwarepaket interagieren und dadurch ihre Funktionalität anderer Software zur Verfügung gestellt werden kann.
Eine API gewährleistet eine solche Integration und sollte möglichst offen, ggf. mittels eines Standards wie [OpenAPI](https://www.openapis.org), dokumentiert sein.
Je sichtbarer eine API Dokumentation dem Nutzer gemacht wird, desto eher wird eine API verwendet. Ein konkretes Beispiel für eine API ist die REST-Schnittstelle von Wikidata, an die man automatisierte Abfragen stellen und Daten von Wikidata beziehen kann. Sie ist zudem umfangreich dokumentiert und bietet eine GUI zum Erlernen der Syntax an.

##### Konformität mit Regelungen zum Datenschutz, Fragen der Privacy und der Datensparsamkeit
Für den Einsatz in der universitären Forschung und der Lehre entscheidet die Frage nach dem Datenschutz vielfach darüber, ob die Software überhaupt genutzt werden darf. Eine Einschätzung der Regelungen, sofern sie sich nicht eindeutig auf die europäischen Rahmenrichtlinien beziehen, ist teilweise jedoch kaum möglich und Gegenstand von juristischen Diskussionen. Auch hier kann die Rezensension aber bereits durch den Hinweis auf das Thema einen wichtigen Service für die Leser bringen. Dies gilt auch für Datensparsamkeit und das Hinterfragen von Registrierungsvorgängen, Cookies und ähnlichem.

* **Beachtet die Software die lokalen Gesetze in dem Land in dem sie eingesetzt werden soll? (Datenschutz, Kartendarstellungen etc.)?**
Oft muss damit gerechnet werden, dass die Software in einer Viezahl von Anwendungskontexten von Menschen in unterschiedlichen kulturellen Kontexten und in verschiedenen Ländern verwendet wird. Diese Länder können ggf. Gesetze erlassen haben, die der Ausführung/Installation der Software entgegenstehen. Ein Beispiel sind Kartendarstellungen, die z.B. Grenzkonflikte wie diese in Kashmir, die in Indien, Pakistan, China und den übrigen Staaten jeweils unterschiedlich auf der Karte angezeigt werden müssen. Ein weiteres Beispiel stellt der Datenschutz z.B. in der Europäischen Union dar.

* **Welche Daten speichert die Anwendung zu welchem Zweck wie lange? Werden Daten an Dritte übertragen?**
In vielen Softwareanwendungen, oftmals Webdiensten, werden Daten der Benutzer zur Verbesserung der Anwendungen anonymisiert erfasst. Kommerzielle Anbieter von Software erfassen jedoch oft weitaus mehr Daten und verwenden diese z.B. zur Übertragung and Drittanbieter.
Hier sollte sich ein Reviewer die Frage stellen, welche Daten erhoben werden, ob eine Zustimmung des Benutzers eingeholt wird, wie lange die Daten gespeichert werden und ob eine Anwendung ohne eine solche Einwilligung zur Übertragung von Nutzerdaten überhaupt bedienbar ist.
Falls eine solche Datenerhebung stattfindet, wäre zu hinterfragen, ob der Zweck der Datenerfassung dem Reviewer als gerechtfertigt erscheint und ob diese Datenerhebung zur Verbesserung der Software beiträgt oder anderen Interessen dient.

Üblicherweise sollten solche Informationen in der Softwaredokumentation vorhanden sein und können auf dieser Grundlage bewertet werden. Eine weitergehende Analyse ob diese Informationen den Tatsachen entsprechen, liegt außerhalb des Blickpunkts einer Rezension von Forschungssoftware.

### Entwickler-Perspektive und Softwarequalität
Hier geht es nun um die Sicht aus Perspektive der Entwickler, die auch Nutzer sind, aber zusätzlich mit weiteren Interessen/Anwendungsszenarien auf die Software schauen. Die folgenden Fragen richten sich somit direkt auf den Programmcode und die Softwarearchitecḱtur. Eine Beurteilung derselben erfordert also den Programmcode herunterzuladen und in Stichproben durchzusehen. Das ist bei proprietärer Software meist nicht möglich.
Eine gute Zusammenfassung der Entwicklerperspektive auf die Softwarequalität bietet [@jung2004measuring](#jung2004measuring). Das Paper wendet die Vorgaben des ISO/IEC 9126 Standards, Anteile dessen bereits in den vorherigen Abschnitten diskutiert wurden, an.

#### Dokumentation und Tests
Die Dokumentation von Software ist essentiell für ein umfassendes Verständnis eines Softwareentwicklers, welcher die Software ggf. erweitern möchte. Nur durch eine ausreichende Dokumentation wird zum

eine ausreichend große Community von potenziellen Entwicklern angesprochen und zum Anderen ein umfassendes Verständnis der Intention der Software, der Ausgereiftheit und des aktuellen Entwicklungsstandes möglich.

Die Dokumentation erfolgt in verschiedenen Bestandteilen. Man unterscheidet die `Dokumentation des Quellcodes`, d.h. von Klassen oder einzelnen Methoden, die `Dokumentation des Buildprozesses`, d.h. wie die Software aus dem Quellcode zu erzeugen ist, eine `Entwicklerdokumentation` in Form von Beispielen der Benutzung der Software und der `Dokumentation dessen wie die Software getestet` wurde bzw. welche Testcases von der Software abgedeckt wurden.
Software Repositories wie [Github](https://github.com) oder [Gitlab](https://gitlab.com) bieten oft Vorlagen oder Best Practices um diese Anforderungen in jeglichen Programmiersprachen umsetzen zu können.
Schließlich kann die Softwaredokumentation von Statistiken über die Software selbst bezüglich Komplexität, der verwendeten Lizenzen und Abhängigkeiten begleitet sein.

Kernfragen, welche ein Reviewer beantworten sollte sind die folgenden:
* **Ist eine Quellcodedokumentation vorhanden und ggf. eine HTML Variante davon verfügbar?**
Best Practices sind hier beispielsweise Quellcode Dokumentationen mit [Doxygen](https://www.doxygen.nl/index.html), [JavaDoc](http://www.oracle.com/technetwork/java/javase/documentation/javadoc-137458.html), [JsDoc](https://jsdoc.app) oder auch das für Python beliebte [ReadTheDocs](https://readthedocs.org). Alle Dokumentationen erzeugen eine HTML Repräsentation der Quellcodedokumentation, welche im Falle von ReadTheDocs direkt auch im Internet gehostet wird. Im Falle von anderen Dokumenationstools ist es gute Praxis diese beispielsweise als Github Page mit dem Repository bereitzustellen.
* **Ist der Buildprozess dokumentiert und ggf. mittels Buildingscripts automatisiert?**
Ebenso wichtig wie ein grundlegendes Verständnis des Aufbaus des Programms ist die Bauanleitung der Software. Entsprechend ist zu fragen, ob dokumentiert ist, wie die Software erstellt wurde und funktioniert die Erstellung unter dem angegebenen Weg.

Während in der Vergangenheit mit Anleitungen in *README Files* oder ähnlichen natürlichsprachlichen Beschreibungen gearbeitet wurde, hat es sich seit vielen Jahren zu einem Standard etabliert, maschinenlesbare Bauanleitungen (*Buildscripts*) für Software bereitzustellen. Dies kann als gute Praxis angesehen werden, denn zum einen ist eindeutig und maschinenlesbar beschrieben, wie die Software erstellt wurde, zum anderen ist der Aufruf des Buildprozess so meist durch Ausführung eines einzigen Skriptes möglich und somit für den Entwickler einfach gehalten. Ebenfalls dokumentieren die Buildscripts die Abhängigkeiten der Software in Bezug auf verwendete *Libraries*.
Beispiele für solche Skripts finden sich z.B. in [Apache Maven](https://maven.apache.org) oder [Gradle](https://gradle.org)

* **Ist die Dokumentation aktuell, wird gepflegt und deckt alle Funktionen des Programms ab?**
Eine Bewertung der Aktualität der Dokumentation ist oft relativ einfach vorzunehmen, wenn Werkzeuge verwendet werden, die dem aktuellen Stand in der Softwareentwicklung entsprechen. Diese beinhalten meist einen Zeitstempel mit dem Datum der Erstellung der Dokumentation. Dieses kann entsprechend mit dem Datum des aktuellen Release verglichen werden. Gute Praxis ist es hier, die Generierung der Dokumentation und das Hosten mit in den Entwicklungsprozess über *Continuous Integration* zu integrieren.

Ein Beispiel hierfür bietet das [Github Repository des SPARQLing Unicorn QGIS Plugins](https://github.com/sparqlunicorn/sparqlunicornGoesGIS). Ein *Continuous Integration* Prozess erstellt die Dokumentation bei jeder Veränderung des Quellcodes durch die Entwickler neu und publiziert diese auf der [Github Page des Repositories](https://sparqlunicorn.github.io/sparqlunicornGoesGIS/).
Eine solche oder ähnliche Konfiguration sorgt dafür, dass die Aktualisierung und Publikation der aktuellen Dokumentation nicht vergessen werden kann.
> nice :-)

* **Gibt es eine Entwicklerdokumentation, sodass die Software leichter verstanden werden und ggf. erweitert werden kann?**
Essentiell für einen Entwickler, der sich mit der Erweiterung oder Nutzung einer Software befasst, ist es, ihm einen möglichst einfachen Einstieg zu bieten.
Dafür ist eine aussagekräftige *README* Datei notwendig, die kurz die Verwendung des Programmes mit den Standardeinstellungen demonstriert. Ein Beispiel dafür ist  [Bibtex_JS](https://github.com/pcooksey/bibtex-js).
Idealerweise werden noch Beispieldaten für ein besseres Verständnis des Programmablaufs beigelegt und ggf. weitere häufig verwendete Anwendungsfälle der Software in Beispielen vorgestellt. Auch dies kann das genannte Beispiel demonstrieren [Bibtex_JS Beispiele](https://github.com/pcooksey/bibtex-js/tree/master/test)).
Abhängig von der Komplexität der Software kann es sinnvoll sein, ein ggf. auch von einer Nutzercommunity gepflegtes Wiki bereitzustellen, um fortgeschrittene Optionen zu erläutern. (siehe [Bibtex_JS Wiki](https://github.com/pcooksey/bibtex-js/wiki))

* **Hat der Quellcode Tests, die die Kernfunktionen des Programms testen und diese für andere Entwickler aufzeigen?**
Jede Software kann durch Tests auf ihre antizipierte Funktionalität hin überprüft werden. Tests erfüllen hierbei zwei grundlegende Funktionen. Zum einen zeigen sie auf welche Anwendungsfälle hin die Entwickler die Software antizipiert haben und geben diese Information in Form von Tests weiter. Zum anderen geben Tests Auskunft darüber, welche Funktionen im jeweiligen Programm als stabil, fehleranfällig oder ggf. noch optimierungsbedürftig gelten können. Kombiniert mit einem *Continuous Integration* Prozess können Testauswertungen mit jeder Änderung am Quellcode durch die Entwickler erstellt werden.
> ich glaube du solltest davor CI mal vorstellen...
> [AK] Ist diese Anregung bereits aufgenommen und verarbeitet?

Eine weiterführende Frage ist, wie hoch die Testabdeckung des Umfangs des Programms ist, also ob alle Funktionen des Programms durch Tests abgedeckt sind. Ist nur ein Teil abgedeckt, wäre zu betrachten, inwieweit dies die Funktionen betrifft, die das Programm seinen Benutzern bereitstellt. Dies gehört zu den Fragen, die mehrheitlich nur durch Experten beantwortbar sind, vielfach also kaum in einer Rezension betrachtet werden können.

* **Wird es dem Benutzer einfach gemacht, die Software zu testen? Gibt es eine Virtuelle Maschine, einen Dockercontainer, einen Installer, andere Formen der Installierbarkeit ohne viel vorheriges Fachwissen?**
Entwickler werden mit mehr oder weniger Schwierigkeiten in der Lage sein, eine Software zu bauen und auszuführen. Allerdings will auch dieser Zeiteinsatz oft wohlbedacht sein. Tatsächlich werden Softwares, welche leicht installierbar und vor allem testbar sind, sowohl von Entwicklern die einen schnellen Einblick in die Funktionalität bekommen wollen, als auch von anderen Benutzern einen besseren Anklang finden als andere.

> [AK] Absatz ist für mich Streichkandidat

Es liegt in der Natur der Sache, dass es hierbei, je nach Art der Anwendung, unterschiedliche Ausführungsformen gibt. Eine Webanwendung kann als Beispiel im Internet gehostet sein und dem Benutzer einen Testaccount zur Verfügung stellen (z.B. [CWRCWriter](https://cwrc.ca)), eine Desktop Anwendung kann bereits eine installierebare Anwendung oder ein Installerpaket mitliefern. Serveranwendungen können für einen Test als Images von virtuellen Maschinen oder - in letzter Zeit üblicher - als Dockerimages in Portalen wie [Dockerhub](https://hub.docker.com) für ein einfaches Testen hinterlegt werden.

>[AK] Das Thema Installtion hatten wir weiter oben. In diesem Abschnitt soll es aber um Entwickler gehen. Daher bitte überarbeiten. Zudem insgesamt sehr umgangssprachlich formuliert

* **Sind die Entwickler der Software aktiv und sind sie gut erreichbar? Wird die Software regelmäßig mit Updates versorgt? Gibt es eine Roadmap für die weitere Entwicklung? Gibt es *Contribution Guidelines*?**
Oft stellen sich bei der Bedienung der Software heraus, dass Funktionalitäten fehlen oder Fehler im Programm vorhanden sind. In manchen Fällen machen diese Probleme die Benutzung der Software für bestimmte Anwendungsfälle unmöglich oder verschlechtern die Ergebnisse, die mit der Software erreicht werden können signifikant. Dies kann auch der Fall sein, wenn die Software möglicherweise in allen anderen Belangen den Erwartungen entspricht. In solchen Fällen ist die Verfügbarkeit der Entwickler und deren Feedback auf Supportanfragen ein entscheidendes Kriterium.

Zunächst sollten die Entwickler klar kommunizieren wie und wo Fehlerreports eingereicht werden können, aund am Besten auch welche Inhalte diese für eine bestmögliche Verarbeitung der Meldungen enthalten sollten. Einen Eindruck davon, ob die Entwickler einen aktiven Austausch pflegen, kann man beispielsweise bei der Durchsicht von Issues in dem Repositorium der Software auf Github oder im Gitlab gewinnen. Haben die Entwickler Anfragen hier zeitnah und zufriedenstellend beantwortet? Wie ist das Verhältnis von offenen Tickets zu bereits geschlossenen Tickets und wie lange hat es gebraucht bis eine Änderung eingepflegt wurde?

>[AK] Hier wechselt es zwischen "Issues" und "Tickets", ist das identisch?

Zudem können Entwickler proaktiv in einer Roadmap kommunizieren, welche Änderungen in nächster Zeit in das Program eingepflegt werden sollen und welche Issues für das nächste Release angegangen werden.
Schließlich ist es für Entwickler oft interessant die Software selbst mitzugestalten und einen Beitrag zu ihrer Verbesserung zu geben. Dafür sollte von den Entwicklern der Software selbst als Best Practice eine *Contribution Guideline* erstellt werden (siehe z.B. [hier](https://projectacrn.github.io/latest/developer-guides/contribute_guidelines.html)). Sie enthält Angaben dazu unter welchen Umständen und wie Änderungen an der Software von Dritten angenommen und integriert werden.

#### Qualität der Implementierung

* **Entspricht die Implementierung dem Stand der Technik?**
Die Frage, ob die Entwicklung dem Stand der Technik entspricht, muss meist anwendungsbezogen beantwortet werden und verlangt ein technisches Verständnis der Abläufe innerhalb der Anwendung. Allerdings können einige Aspekte durchaus auch ohne Fachwissen bewertet werden.
Hierzu gehören unter anderem folgende Aspekte:
  * Ist die Anwendung auf vielen verschiedenen Endgeräten bedienbar? (z.B. Handy, verschiedene Betriebssysteme usw.)
  * Wie ist die Optik der Anwendung? Verwendet sie Elemente vergleichbarer Anwendungen (z.B. Elemente der aktuellen Android Version, verwendet die Webanwendung Adobe Flash, Java Applets oder ähnlich veraltete Technologien?)
  * Werden im Github Repository Mängel an der Anwendung die die Security betreffen angemerkt oder automatisiert annotiert?

> [AK] Muss "security" verwendet werden, weil ein Fachbegriff, oder kann er mit Sicherhiet übersetzt werden und dabei auch spezifiziert werden. Mir sit nicht klar um die Sicherheit von was es sich handelt.

* **Ist die Implementierung performant? Für Webapplikationen und Plugins ist zu überprüfen, ob sie responsiv sind und über die verschiedenen Browser hinweg performant sind.**
Die Performanz einer Anwendung ist je nach Anwendungstyp von mehr oder weniger Wichtigkeit. Ein Reviewer sollte hier bewerten, ob die Software ihre Aufgabe in der vom Reviewer angemessenen Zeit erfüllt. Gegebenenfalls kann der Reviewer die Ausführungszeit weiterer verwandte Softwareimplementierungen mit der von ihm zu Testenden vergleichen.
Ein Reviewer wird wahrscheinlich nicht in der Lage sein die Gründe für eine mangelnde Performanz der Software zu erkennen.

> [AK] Frage: Ist die Frage der Performanz, so wie sie hier gestellt wird, nicht 1.) "usability" und 2.) auch ohen Entwicklerwissen zu testen?

* **Robustheit der Software**
Die Robustheit einer Software ist ein wünschenswerter Aspekt, der im Wesentlichen voraussetzt, dass die Software Zwischenstände der Aufgaben, die sie auszuführt, regelmäßig sichert, um bei einem unvorhergesehenen Abbruch wieder an dem Punkt anknüpfen zu können, an dem sie vor diesem Ereignis gearbeitet hat. Ein Fehlen dieser Funktion kann oft z.B. bei einem Stromausfall den Verlust von Einstellungen, Daten und/oder die Neuinitialisierung einer Berechnung bedeuten.
Ein Beispiel für eine solche Robustheit ist das regelmäßige automatisierte Zwischenspeichern in einem Textverarbeitungsprogramm. Das Textdokument ist somit im Falle eines Absturzes der Software wiederherstellbar.
Abhängig vom Anwendungsfall kann es auch vorteilhaft sein, dass die Software eine Historie der Benutzeränderungen vorhält und diese ebenfalls wiederherstellen kann. Dies kann die Spracheinstellungen oder auch die Anpassung von Masseinheiten, Vorgaben zum Speicherort und ähnliches sein.

> [AK] Sind wir hier noch im spezifischen Entwicklerbereich ? Es klingt für mich nach Usability, denn wir argumentieren hier über das Nutzererlebnis, nicht über technische Kerndaten. Für mich wäre die Frage, kann man nicht kurz erläutern, wie man einen Absturz herbeiführt, um die Robustheit zu testen? Wenn ja, was wäre das richtige Vorgehen?

* **Wird *Continuous Integration* zur Absicherung der Implementierungsqualität verwendet?**
Für einen Entwickler ist nicht nur das Vorhandensein und die Dokumentation des Quellcodes entscheidend, sondern er wird meistens auch einen Hinweis zur Funktionalität und Kompilierbarkeit des Quellcodes erwarten. *Continuous Integration* kann, wie schon in den vorherigen Abschnitten angesprochen, ein solches Qualitätsmerkmal darstellen. Der *Continuous Integration* Prozess überprüft die Kompilierbarkeit der Software nach jeder Änderung und kann diese am Repository mit einer Statusanzeige sichtbar machen. Es ist ein Zeichen von gut gewartetem Quellcode, wenn dieser in der aktuell vorliegenden Version und ggf. in der aktuellen Entwicklerversion kompiliert.

>[AK] Besser, wenn alles rund um CI aufeinander folgt?

## Weitere Merkmale und Spezifikationen
Wie oben beschrieben, gibt es eine große Anzahl weiterer Merkmale, die für die Leser interessant sein können, aber keiner Einschätzung oder Beurteilung benötigen. Denkbar ist etwa diese tabellarisch zusammengefasst vorzustellen, so wie man es vielfach bei Vergleichsportalen findet. Vorschlagen möchten wir folgende Punkte für eine Tabelle. Dabei haben wir einige Merkmale wiederholt, die bereits in unserem Fragenkatalog vorhanden sind, um zu zeigen, wie man Gewichtungen und Schwerpunktsetzungen in der Besprechung vornehmen kann, ohne Aspekte unerwähnt zu lassen.

* Vorhandensein der Spezifikation für Installationen
* Opensource, Free and OpenSource
* Tutorials and Trialdata (zur freien Nutzung?)
* Input- / Outputformate
* Alternativprodukte / Konkurrenzangebote

> [AK] Mir fehlen für eine Tabelle weitere Spalten und eine Spaltenüberschrift. Besser zu einem konkreten Vorschlag ausarbeiten?

## Anmerkungen

<a name="myfootnote1">1</a>: Aufgeworfen und anschließend im Plenum des 9. Workshops der deutschen Sektion der CAA 2019 in Wilhelmshaven wurde die Frage nach den Inhalten einer Rezension von Software und Anwendungen für die Archäologie von Sophie Charlotte Schmidt, Kai-Christian Bruhn und Siegmund Freud. Anlässlich der Einrichtung der neuen Rubrik für solche Besprechungen in der vorliegenden Reihe haben wir das Thema aufgegriffen und möchten mit der vorliegenden Handreichung einen Beitrag zur Weiterentwicklung dieses wichtigen Themas leisten. Die Handreichung kann auch zur Orientierung bei Entscheidungen zum Einsatz einer Software in der eigenen Forschung dienen.

## Bibliographie
