---
title: Diskussionsbeitrag - Handreichung zur Rezension von Forschungssoftware in den Altertumswissenschaften / Impulse - Recommendations for the review of archaeological research software

abstract_de: Abstract_DE.md
abstract_en: Abstract_EN.md
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
    name: Hubert Mara
    affiliation: mainzed & Hochschule Mainz
    orcid: 0000-0002-2004-4153
    bio: "Hubert Mara studierte Informatik an der Technischen Universität Wien. Dort befasste er sich bereits mit digitalen Methoden in der Archäologie zur Keramikanalyse. Im Anschluss war er Marie-Curie fellow an der Universität Florenz im Rahmen des *Cultural Heritage Informatics Research Oriented Network* (CHIRON). Er promovierte an der Universität Heidelberg im *Interdisziplinären Zentrum für Wissenschaftliches Rechnen* (IWR). Dort entstand das [*GigaMesh Software Framework*](https://gigamesh.eu) und das *Forensic Computational Geometry Laboratory* (FCGL). Seit Juni 2020 ist er Geschäftsführer des mainzed und wissenschaftlich am Institut für Raumbezogene Informations- und Messtechnik der Hochschule Mainz tätig."

  -  
    name: Clemens Schmid
    affiliation: Max-Planck-Institut für Menschheitsgeschichte Jena
    orcid: 0000-0003-3448-5715
    bio: "Clemens Schmid studierte Prähistorische, Historische und Naturwissenschaftliche Archäologie und Informatik in Tübingen und Kiel. Nach Studienabschluss arbeitete er mit computerbasierter Datenanalyse in verschiedenen archäologischen Forschungsprojekten an der Universität Kiel, dem Römisch-Germanischen Zentralmuseum in Mainz und der Universität Bern. Im Augenblick ist er für ein Promotionsprojekt zur quantitativen Nachhersage von Mobilitätsverhalten mit genetischen und historisch-linguistischen Daten in der Abteilung für Archäogenetik des Max-Planck-Instituts für Menschheitsgeschichte in Jena beschäftigt."
  -
    name: Sophie Charlotte Schmidt
    affiliation: Deutsches Archäologisches Institut
    orcid: 0000-0003-4696-2101
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

{% include {{ page.abstract_de }} %}

{% include {{ page.abstract_en }} %}

## Zielsetzung des Beitrags

Ziel dieses Beitrags ist es, die Diskussion um Inhalte und Zielsetzungen von Rezensionen von Forschungssoftware und im Forschungsprozess eingesetzten digitalen Werkzeugen in den Altertumswissenschaften anzuregen. Anstoß für unsere Überlegungen gab eine Diskussion von Kai-Christian Bruhn, Sophie Charlotte Schmidt und Frank Siegmund im Plenum des 9. Workshops der deutschen Sektion der CAA 2019 in Wilhelmshaven. Anlässlich der Einrichtung der neuen Rubrik für solche Besprechungen in den Archäologischen Informationen haben wir unsere Gedanken nun verschriftlicht.

In dieser Handreichung erläutern wir Kriterien, die eine gute Forschungssoftware ausmachen und für deren Bewertung von Bedeutung sein können. Außerdem empfehlen wir eine Vorgehensweise zur Softwarerezension.

Die Beurteilung einer Publikation ist eine traditionsreiche Form des wissenschaftlichen Diskurses. Entsprechend gibt es ein unausgesprochenes Verständnis davon, was eine Rezension umfassen sollte. Zusätzlich können konkrete Maßnahmen zur Qualitätssicherung ergriffen werden. Dazu gehören Hinweise zum Anfertigen von Rezensionen oder - wie es die Redaktion der Archäologischen Informationen praktiziert - Reviews von Rezensionen.

Was sollte eine gute Rezension von Software für den Einsatz in der Archäologie ausmachen? Geht es allein um die von einer Software ausgeführten Routinen, welche zur Lösung einer wissenschaftlichen Problemstellung beitragen? Oder müssen Aspekte der Nutzbarkeit, der Nachhaltigkeit und Interoperabilität ebenfalls Beachtung finden? Welche Rolle spielen technische und rechtliche Aspekte in der Besprechung, wie etwa die Dokumentation des Quellcodes oder die Lizensierung? Und schließlich: Stellt die Software vielleicht selbst einen wissenschaftlichen Beitrag dar? Welches sind die Leistungen der Software-Entwickler, die eine Besprechung berücksichtigen sollte? Welche Maßstäbe, die in den Empfehlungen der Deutschen Forschungsgemeinschaft (DFG) anklingen, sollte eine gute  Forschungssoftware erfüllen?.

Die zentrale Fragestellung einer Rezension nach dem wissenschaftlichen Wert des Besprechungsgegenstands wird mit diesen Fragen nur gestreift. Denn in diesem Punkt stimmen die Anforderungen an eine Softwarerezension mit denen einer Textrezension überein. Weiterhin werden aufgrund der Vielfalt und Vielartigkeit von Software nicht alle von uns hier gesammelten Kriterien in jeder Rezension von Bedeutung sein. Es obliegt dem Rezensenten relevante Aspekte auszuwählen und Schwerpunkte zu legen.

Dieser Beitrag ist als Impuls gedacht. Diskussionsbeiträge und Anregungen sind erwünscht. Dazu können die Autoren über die angegebenen Adressen kontaktiert werden oder Anmerkungen direkt auf GitHub unter [https://research-squirrel-engineers.github.io/DGUF_Leitfaden/](https://research-squirrel-engineers.github.io/DGUF_Leitfaden/) hinterlegt werden.

> [MT] der folgende Absatz sollte weiter unten integriert und hier entfernt Werden
> [MT] Satz kommt zu Forschungssoftware als Wiss. Leistung.

Software greift im- und explizit tief in den Forschungsprozess ein (für die Archäologie siehe z.B. [@schmidt_marwick_2020](#schmidt_marwick_2020)) und nur durch die Offenlegung von Quellcode ist eine Bewertbarkeit der durch die Software geleisteten Abläufe wirklich gewährleistet.


## Forschungssoftware

Die weiter unten vorgestellten Kriterien zur Rezension von Software zielen primär auf die Begutachtung von Forschungssoftware ab. Unter Forschungssoftware verstehen wir Software, die mit Fokus auf den Einsatz in der Forschung entwickelt wurde, also um Forschungsdaten zu erzeugen, zu verarbeiten oder zu analysieren [@hettrick_2014_14809](#hettrick_2014_14809). Dies sind beispielsweise Programme, die der Kalibrierung und Umrechnung von Messwerten, der Visualisierung von Raumdaten, der Annotation von Texten und Objekten, oder der Bereitstellung sowie der Verknüpfung fachlich relevanter Vokabulare dienen.

Forschungssoftware kann entweder für einen sehr spezifischen Bedarf oder aber einen allgemeinen Anwendungsbereich entwickelt werden. Sie ist dabei stets Teil des Forschungsprozesses, der in allen seinen Punkten nachvollziehbar und soweit möglich reproduzierbar sein muss. Forschungssoftware kann hierbei von zwei Blickwinkeln aus betrachtet werden:

1. Forschende wenden eine Forschungssoftware im Kontext ihrer Arbeiten an.
2. Forschende entwickeln Forschungssoftware im Kontext ihrer Arbeiten.

Im Gegensatz zu Forschungssoftware steht Software, die zur Nutzung spezifischer Geräte erforderlich ist, wie etwa zur Vermessung, zur fotografischen Dokumentation oder zur Analyse von Oberflächen und Inhaltsstoffen. Häufig handelt es sich dabei um proprietäre Software, die zusammen mit der Hardware vertrieben wird. Obwohl sie im Forschungsprozess eingesetzt wird, entspricht sie nicht unserem Verständnis von Forschungssoftware. Auch digitale Werkzeuge (auch Tools), die eine erhebliche Rolle in der praktischen Arbeit inne haben, jedoch keinen eigentlichen Anteil an der Erhebung, Bearbeitung und Analyse der Daten haben, sind in unserem Sinne keine Forschungssoftware. Dazu gehören z.B. Textverarbeitungs- oder Tabellenkalkulationsprogramme. Die vorgestellten Kriterien können zur Beurteilung jedes Software-Typs verwendet werden.

Forschungssoftware ist in besonderer Weise Herausforderungen nachhaltiger Entwicklung und Pflege ausgesetzt. Als einen Hauptfaktor für fehlende Nachhaltigkeit von Forschungssoftware identifizieren wir den Mangel an langfristiger Finanzierung für Personal und Infrastruktur zur Erzeugung von nachhaltiger Software ([@anzt_environment_2020, 2](#anzt_environment_2020)). Einen Überblick über Bedarfe, Herausforderungen und Lösungsansätze für nachhaltige Forschungssoftwareentwicklung wurde 2019 in einem Workshop der [deRSE Konferenz in Potsdam](https://de-rse.org/de/conf2019/index.html) erstellt ([@bach_dersews19](#bach_dersews19)).

### Forschungssoftware als wissenschaftliche Leistung

In der modernen Forschung ist ein Arbeiten ohne digitale Werkzeuge undenkbar. Dies trifft auch auf die historische und altertumswissenschaftliche Forschung zu. Mit dem Aufschwung der Digital Humanities wird Software zunehmend ein wichtiger Bestandteil des Forschungsprozesses.

Trotz der tragenden Rolle, die Forschungssoftware in vielen Projekten einnimmt, wird die Leistung jener Personen, die hinter der Entwicklung und Programmierung stehen, akademisch oft nicht ausreichend anerkannt ([@hettrick_2017](#hettrick_2017), [@scheliga_pampel_2017](#scheliga_pampel_2017) und [@katerbow_2018](#katerbow_2018)). Das wird der Tatsache nicht gerecht, dass für die Entwicklung von Forschungssoftware wissenschaftliche Expertise und darüber hinaus fortgeschrittene technische Kompetenz erforderlich sind. Durch die Umsetzung in Code wird Praxis und Wissen explizit manifestiert und weiterentwickelt. Wir argumentieren, dass diese Leistungen gewürdigt und sichtbar gemacht werden müssen, zumal der wissenschaftliche Durchbruch häufig erst durch die Software ermöglicht wird ([@scheliga_pampel_2017](#scheliga_pampel_2017), [@katerbow_2018](#katerbow_2018) sowie [@helmholtz_web](#helmholtz_web)).

Als ein wichtiger erster Schritt zur Sichtbarmachung wurde 2012 die Berufsbezeichnung des "Research Software Engineers" (RSE, RSEng) geprägt ([@hettrick_2017](#hettrick_2017) und [@baxter_2012](#baxter_2012)). Inzwischen hat sich eine aktive, interdisziplinäre Gemeinschaft gebildet, die Empfehlungen zum Umgang mit Forschungssoftware entwickelt ([@anzt_environment_2020](#anzt_environment_2020)). Nationale [RSE Sektionen](https://sorse.github.io/contact/chapters/) - in Deutschland der de-RSE e.V. - organisieren Konferenzen wie z.B. [SORSE](https://sorse.github.io). Im Rahmen des Aufbaus einer \`Nationalen Forschungsdateninfrastruktur (NFDI)\` nehmen Forschungssoftware und RSEs einen großen Stellenwert in der Weiterentwicklung der Forschungslandschaft und der Angebote der Forschungseinrichtungen in Deutschland ein ([@loeffler_nfdi4rse20](#loeffler_nfdi4rse20) und [@goedicke_nfdixcs20](#goedicke_nfdixcs20)).

Eine der Forderungen des de-RSE e.V. ist, dass Forschungssoftware explizit mittels geeigneter Publikationsmodalitäten sichtbar wird. Einerseits erhöht eine Publikation die Auffindbarkeit und vermeidet so redundante Neuentwicklungen ([@anzt_environment_2020, 10](#anzt_environment_2020)). Andererseits ist die mit einer Publikation einhergehenden eindeutige Autorenschaft von großer Bedeutung, da erst dadurch die Leistung der Softwareentwicklung an die entsprechenden Personen geknüpft wird. Dies ermöglicht eine akademische Laufbahn, wofür bislang jedoch oft nur klassische Textpublikationen gewertet wurden. Daher sollen zukünftig Datenpublikationen, Softwareentwicklung ([https://citation-file-format.github.io](https://citation-file-format.github.io),  [@druskat2017citation](#druskat2017citation)), Annotationen, sowie deren Zitationen Kriterien der Beurteilung der wissenschaftlichen Leistung sein ([NFDI4Culture](https://nfdi4culture.de), [RSE4NFDI](https://www.rse4nfdi.de/de/index.html), [NFDI4Objects](https://www.nfdi4objects.net)). Hierbei sind technische Herausforderungen zu meistern, da Software selten entgültig abgeschlossen, oft auf bestehenden Modulen aubaut und mitunter von wechselnden Teams über Jahrzehnte betreut wird [@katz_software_2016](#katz_software_2016).

Eine offen verfügbare Software kann, ganz so wie in der bisherigen Praxis der altertumswissenschaftlichen Forschung, begutachtet werden. In einer Rezension kann diese dann einem breiteren Publikum vorgestellt werden. Durch eine dedizierte Rezension von Software analog zu Rezensionen wissenschaftlicher Publikationen, wird die wissenschaftliche Leistung der Autoren und Autorinnen von Forschungssoftware mittels gewohnten Formaten sichtbar und anerkannt. Gleichzeitig wird auch ihre Verantwortung und Teilhabe manifest.

### Gute Forschungssoftware

Um überhaupt Kriterien zur Rezension und Bewertung von Forschungssoftware aufstellen zu können, stellt sich zunächst die Frage, wie man deren Qualität bestimmt und nach welchen Standards beurteilt werden soll. Dazu gehören eine Vielzahl fachlicher und technischer Aspekte, die weiter unten beleuchtet werden sollen. Darüber hinaus muss Software aber wie jedes andere Werkzeug zunächst hinsichtlich ihrer generellen Eignung für nachhaltiges und ethisches wissenschaftliches Arbeiten bewertet werden.

Die DFG formuliert mit ihren "Leitlinien zur Sicherung guter wissenschaftlicher Praxis" ([@deutsche_forschungsgemeinschaft_2019](#deutsche_forschungsgemeinschaft_2019)) eine Reihe von Vorgaben für gutes wissenschaftliches Arbeiten. Die Leitlinien entsprechen einem internationalen Konsens und etablierten Prinzipien. Zu den Anforderungen gehören etwa die Einhaltung und Etablierung von Standards und Methoden, eine nachvollziehbare Dokumentation des Weges zu Ergebnissen, die öffentliche Zugänglichkeit von Ergebnissen und die Archivierung der notwendigen Materialien, die zu Ergebnissen geführt haben.

Einige der Kriterien, die in den DFG-Leitlinien explizit und implizit anklingen, sollen im folgenden jeweils näher ausgeführt werden: Die in der Erläuterung zu Leitlinie 13 (*Herstellung von öffentlichem Zugang zu Forschungsergebnissen*) genannten FAIR-Prinzipien, die Prinzipien der Offenen Wissenschaft (Open Science) und die in den Leitlinien 2 und 10 angeführten CARE-Prinzipien. Weitere Hinweise zur Umsetzung der DFG-Leitlinien in Bezug auf Forschungssoftware sind unter [@forschungsdaten_info_dfg](#forschungsdaten_info_dfg) zu finden.

#### FAIR-Prinzipien

Die FAIR-Prinzipien wurden 2016 als *FAIR Data Principles* veröffentlicht [@wilkinson_2016](#wilkinson_2016). Sie zielen primär auf Forschungsdaten und deren Metadaten ab und fordern, dass diese auffindbar (Findable), zugänglich (Accessible), interoperabel (Interoperable) und nachnutzbar (Reusable) sind. Ein Fokus ist dabei die maschinelle Lesbarkeit. Die Prinzipien lassen sich auch auf Forschungssoftware und deren Metadaten übertragen ([@lamprecht_towards_2019](#lamprecht_towards_2019), [@goedicke_nfdixcs20](#goedicke_nfdixcs20)) und bieten somit Kriterien zur Beurteiliung der Qualität von Softwarepublikation, Codedokumentation und Programmierstandards.

##### Findable (Auffindbar)

Software wird durch die Speicherung zusammen mit ihren Metadaten in dedizierten Softwarerepositorien (e.g. GitHub) auffindbar. Die Auffindbarkeit kann durch eine fachwissenschaftliche Einbindung in Forschungsinfrastrukturen zusätzlich erhöht werden, da letztere explizit an Aufbau, Pflege und Anwendung von kontrollierten Indizes und Metadatenstandards arbeiten ([@lamprecht_towards_2019](#lamprecht_towards_2019) und [@anzt_environment_2020, 10](#anzt_environment_2020)).

Die Vergabe von persistenten Identifikatoren (e.g. URIs) durch Repositorien, sowie die Nennung der Autorenschaft ermöglicht das Zitieren von Forschungssoftware. Da Software im Gegensatz zu herkömmlichen Publikationen ständig weiterentwickelt wird, sollte sie in unterschiedlichen Versionen gespeichert werden, welche dann individuell zitiert werden können [@forschungsdaten_info_dfg](#forschungsdaten_info_dfg).

##### Accessible (Zugänglich)

Öffentliche Repositorien und dauerhaften Identifikatoren stellen ebenfalls ein Mindestmaß an Zugänglichkeit sicher. Idealerweise sollten Daten und Metadaten dabei auch maschinell über ein offenes und standardisierte Kommunikationsprotokoll abrufbar sein [@lamprecht_towards_2019](#lamprecht_towards_2019).

Weitere Aspekte, welche die Zugänglichkeit für Nutzer erleichtern, sind die Verfügbarkeit für verschiedene Betriebssysteme, sowie technische Anforderungen, die von aktuell verbreiteten Geräten geleistet werden können. Eine verständliche Anleitung zur Nutzung des Programms verbessert die Zugänglichkeit in diesem Sinne auch weiter.

##### Interoperable (Interoperabel)

Interoperabilität von Software kann sich zum einen auf die Kompatibilität der Ein- und Ausgabeformate mit anderen Programmen in einem Arbeitsprozess (horizontale Dimension) beziehen. Zum anderen verweist sie auch auf die Zusammenarbeit der verwendeten Komponenten in der Software selbst (vertikale Dimension) [@lamprecht_towards_2019, 46 f.](#lamprecht_towards_2019). Die Verwendung von Standards ermöglicht beides, da sie die Zusammenarbeit von Softwarekomponenten auch über Betriebssystemgrenzen hinweg ermöglicht.

##### Reusable (Nachnutzbar)

Die Nachnutzbarkeit von Software hängt von mehreren Komponenten ab. Die Metadaten und eine umfassende Dokumentation der Software sollten es anderen ermöglichen, Ergebnisse zu reproduzieren sowie eigene Daten und veränderte Anwendungsfälle zu prozessieren. Eine geeignete Lizenz, die auch die abhängigen Softwarekomponenten berücksichtigt, gibt zudem darüber Auskunft, welche Regeln bei der Nutzung gelten und ob eine Weiterentwicklung des Codes möglich ist [@lamprecht_towards_2019, 48-49](#lamprecht_towards_2019).

#### Open Science

Open Science (Offene Wissenschaft) bezeichnet eine Wissenschaftspraxis, deren Ziel ein transparenter, reproduzierbarer und kollaborativer Forschungsprozess ist [@bezjak_openscience_2018, Open Concepts and Principles](#bezjak_openscience_2018). Open Science setzt sich aus mehreren Prinzipien zusammen, die unterschiedliche Stadien im Forschungsprozess betreffen. So fordert Open Science nicht nur die Öffnung der Ergebnisse (Open Access), sondern auch der zugrundeliegenden Daten (Open Data), Methoden (Open Methodology) und der verwendeten Forschungssoftware (Open Source). Für offene Forschungssoftware gilt, dass ihr Quellcode zugänglich und mit einer Lizenz versehen sein muss, die die Weiterentwicklung erlaubt [@bezjak_openscience_2018, Open Research Software and Open Source](#bezjak_openscience_2018).

Mit der Forderung nach der Offenlegung des Quellcodes (Open Source) wird auch dem Gedanken der Nachnutzbarkeit entsprochen. Die Offenlegung wird erweitert um die Forderung, den Code zudem frei nutzbar zur Verfügung zu stellen (Free Source) [@stallman2001free](#stallman2001free). Letzteres wird als FOSS (Free/Libre Open Source Software) bezeichnet und in Deutschland z.B. von anwendungsbezogenen Wissenschaftlern und Entwicklern aus der Geoinformatik vertreten ([FOSSGIS e.V.](https://www.fossgis.de)) oder auch von Research-Software-Engineers in der ["de-RSE e.V."](https://de-rse.org/de/association.html) [@anzt_environment_2020](#anzt_environment_2020).

In den Leitlinien der DFG klingt die Öffnung von Software-Quellcode im Zusammenhang mit der Qualitätssicherung [@deutsche_forschungsgemeinschaft_2019, 14-15](#deutsche_forschungsgemeinschaft_2019) und der Herstellung von öffentlichem Zugang zu Forschungsergebnissen [@deutsche_forschungsgemeinschaft_2019, 19](#deutsche_forschungsgemeinschaft_2019) an.

#### CARE-Prinzipien und Ethos

In den Leitlinien der DFG werden in Leitlinie 2 und 10 ethische Aspekte im Forschungsprozess angesprochen, die unserer Meinung nach auch im Bereich der Forschungssoftware Beachtung finden sollten.

Privilegien und Ungleichheiten in der altertumswissenschaftlichen Forschung werden unbewusst auch in der Forschungssoftware fortgeschrieben: Für archäologische Feldarbeit wird beispielsweise oft Software zur Datenaufnahme eingesetzt, die für die Mehrheit der Mitarbeiter vor Ort aufgrund einer Sprachbarriere nicht verständlich ist. Eine Folge kann sein, dass diese Teammitglieder sich nicht weiter qualifizieren und anspruchsvollere Aufgaben übernehmen können. Proprietäre Software oder teure Hardware benachteiligt wiederum Forscher, die mit weniger Finanzmitteln auskommen müssen.

In den Archäologien, wo häufig an fremden Kulturen und Kulturhinterlassenschaften geforscht wird, sollten die indigenen und ortsansässigen Bevölkerungsgruppen die Möglichkeit zur Mitbestimmung über die Erforschung bekommen. Um diesem Ideal gerecht zu werden, eignet sich die Orientierung an den CARE-Prinzipien ([https://www.gida-global.org/care](https://www.gida-global.org/care)). Sie wurden von der [Global Indigenous Data Alliance (GIDA)](https://www.gida-global.org) und der [Research Data Alliance (RDA)](https://www.rd-alliance.org) 2018 auf Basis der [UN Declaration on the Rights of Indigenous Peoples (UNDRIP)](https://www.un.org/development/desa/indigenouspeoples/declaration-on-the-rights-of-indigenous-peoples.html) erarbeitet und konzentrieren sich wie die FAIR-Prinzipien explizit auf Forschungsdaten. Ihre vier Grundpfeiler Kollektiver Nutzen (Collective Benefit), Souveränität (Authority to Control), Verantwortung (Responsibility) und Ethik (Ethics) sind unserer Meinung nach ebenso auch für Forschungssoftware relevant.


## Mögliche Vorgehensweise zur Rezension archäologischer Forschungssoftware

Unserem Verständnis nach sollte eine Rezension archäologischer Software, so wie es eine herkömmliche Besprechung einer wissenschaftlichen Publikation leistet, die Software zunächst kurz mit zusammenfassenden Eckdaten vorstellen. Anschließend sollte der ausführlicheren Kontext erläutert werden und eine kritische Beurteilung erfolgen.

Für Software gehören zu den Eckdaten u. a. Angaben zur Version, zu den Entwicklern und der Lizenz. Wir schlagen vor, den Lesern diese Eckdaten in einer tabellarischen Übersicht zur Verfügung zu stellen, wie sie etwa am Ende des Beitrags zu finden ist. Dies ermöglicht z.B. eine schnelle Übersicht, darüber ob die begutachtete Software mit der eigenen technischen Umgebung kompatibel ist.

Mit Kontext sind eine Einordnung in das archäologische Forschungsfeld und Angaben zum möglichen Zusammenhang mit Forschungsprojekten, Arbeitsgruppen oder Institutionen gemeint. Für die kritische Beurteilung aus verschiedenen Blickwinkeln folgt weiter unten ein Fragenkatalog. Die Ergebnisse der Begutachtung sollten in einer Stellungnahme zusammengefasst werden, die die Software hinsichtlich ihrer Nützlichkeit, ihrer Bedienbarkeit, ihrer handwerklichen Qualität und ihrer Position in Relation zu den Idealen guter Forschungssoftware (z.B. FAIR und CARE), beurteilt.

Selbstverständlich setzt die Rezension einer Forschungssoftware die Sichtung von Dokumentation und Publikationen ebenso voraus, wie die praktische Erprobung der Software selbst. Dabei ist eine realistische und transparente Einschätzung der eigenen Kompetenzen und des eigenen Nutzungsinteresses ein wichtiger Anhaltspunkt für die heterogene Leserschaft. Es ist eine wichtige Information, ob die Rezension rein aus Sicht eines Anwenders oder auch eines Entwicklers geschrieben wurde. In manchen Fällen können Hinweise auf die Testumgebung von Bedeutung sein, wie z. B. zu RAM, Prozessor, Grafikkarte, Bandbreite und Betriebssystem des vom Rezensenten genutzten Computers, da diese die Arbeit des Programms beeinflussen können.


## Fragenkatalog zur Beurteilung von Software

Im folgenden stellen wir einen kommentierten Fragenkatalog mit Kriterien zur Beurteilung von archäologischer Forschungssoftware vor. Seine drei Bereiche bündeln jeweils Fragen aus verschiedenen Kompetenzbereichen. Die ersten zwei Bereiche beschäftigen sich mit dem wissenschaftlichen Anwendungsfeld, sowie der Anwendung und Bedienbarkeit aus Nutzersicht. Der dritte Bereich konzentriert sich auf Fragen, die insbesondere für Entwickler und IT-Administratoren relevant sind. Abgeschlossen wird der Katalog durch eine Liste mit Merkmalen, welche in tabellarischer Form die Rezension ergänzen, jedoch meist nicht kritisch beurteilt werden können.

Wie bei der Besprechung einer wissenschaftlichen Publikation ist die Zusammensetzung und Gewichtung der einzelnen Merkmale bei der Begutachtung selbst zu bestimmen und in Relation zum Anwendungskontext zu setzen. Entsprechend verstehen wir unseren kommentierten Fragenkatalog als Maximalversion, die als Hilfsmittel für die Begutachtung und die Einschätzung der eigenen Kompetenzen dienen kann.

### Einsatz in der Archäologie und wissenschaftlicher Zweck

Bei der Beurteilung der wissenschaftlichen Qualität von Forschungssoftware sind zunächst zwei wesentliche Dimensionen zu unterscheiden. Dies ist zum einen, und das ist für Forschungssoftware vorrangig, die Frage, ob die Software einen sinnvollen Beitrag zur Bearbeitung der archäologischen Fragestellung liefert. Zum anderen ist zu beurteilen, ob Software eine korrekte Umsetzung der angestrebten Arbeit leistet. Beide Fragen sind mitunter nicht leicht zu beantworten.

* **Welche Aufgabenstellung versucht die Software zu lösen?** Diese Frage ist mit dem deskriptiven Charakter einer Rezension verknüpft: Welche Aufgaben werden mittels der Software bei der Erfassung, der Verarbeitung oder der Analyse von Daten bearbeitet? Wie relevant sind die Aufgaben in einem archäologischen Kontext und wie häufig werden sie gestellt? Dieser Punkt verdeutlicht, warum es von besonderem Wert ist, wenn Archäologen selbst Softwarerezensionen für sich und ihre Kollegen verfassen.

* **Wie löst die Software eine gegebene (technische) Aufgabe?** Eine detaillierte Beantwortung dieser Frage ist nur aus Entwicklerperspektive möglich, doch Kernbestandteile lassen sich meist leicht identifizieren. Wie ist die grundsätzliche Funktionsweise der Software konzipiert? Was sind die wesentlichen technischen Bestandteile im Nutzerinterface und in den dahinter liegenden Datenverarbeitungsmodulen? Handelt es sich zum Beispiel um eine Webanwendung, die als Schnittstelle zu einer Datenbank fungiert? Oder ist die Software ein schlichtes, monolithisches Kommandozeilenprogramm?

* **Wie funktioniert der wissenschaftliche Arbeitsablauf, der in der Software implementiert wurde?** Hier geht es weniger um die konkrete technische Implementierung, sondern vielmehr um die generelle Methodik. Welche wesentlichen Schritte durchlaufen Daten, um eine bestimmte Aufgabe zu lösen? Welche statistischen Werkzeuge kommen zum Einsatz? Gibt es Vergleichsdaten? Ein Beispiel für eine mögliche Prozessierung ist die Bereinigung von Eingabedaten mittels eines Referenzdatensatzes, um eine Klassifizierung mit einer hierarchischer Clusteranalyse zu erstellen und zuletzt als paarweise Distanzmatrix zu visualisieren.

* **Ist die Behauptung, eine bestimmte wissenschaftliche Fragestellung mit dem gewähltem Arbeitsablauf beantworten zu können, korrekt?** Forschungssoftware verspricht meist - implizit oder explizit - die Beantwortung wissenschaftlicher Fragestellungen zu ermöglichen oder zumindest zu vereinfachen. Eine GIS-Applikation zur Analyse von Punktmustern kann etwa für den Zweck konzipiert sein menschliches Siedlungsverhalten aufzuzeigen. Die Frage, ob der angewendete Algorithmus dazu überhaupt in der Lage ist, kann den Umfang einer Rezension bei weitem übersteigen. Dennoch sollte der Rezensent versuchen eine Einschätzung der Plausibilität vorzunehmen oder zumindest das Problem der Einschätzbarkeit selbst offenzulegen, um die Leser zu sensibilisieren. Zur Beurteilung kann es helfen sich zu vergegenwärtigen, welche Schlüsse aus den rohen, unverarbeiteten Eingabedaten überhaupt theoretisch ableitbar sein könnten.

* **Sind die Algorithmen korrekt implementiert worden?** Die Korrektheit der Ergebnisse einer Software ist mitunter schwer zu beurteilen, weil beispielsweise ein umfangreicher Blackbox-Test durchgeführt werden muss. Ein Mangel an vergleichbarer Software mit der zu testenden Funktionalität erschwert dies zusätzlich. Werden die in der Dokumentation genannten Algorithmen fehlerfrei in Programmcode ausgedrückt? Ist das wissenschaftliche Ergebnis trotz aller technischen Unterschiede vergleichbar mit anderen Softwarelösungen? Sind die verwendeten Algorithmen dokumentiert und hinreichend wissenschaftlich belegt? Auch diese Frage mag im Rahmen einer Rezension nicht abschließend zu beantworten sein. Ein wichtiges Indiz für eine fehlerhafte Implementierung ist eine mangelnde Robustheit, die später noch besprochen wird.

* **Gibt es für die Archäologie relevante Projekte/Anwendungen, in der die rezensierte Software bereits angewendet wurde?** Software wird oft von und für bestimmte Forschungsprojekte entwickelt. Zur Beurteilung ihrer Qualität und Relevanz kann es also hilfreich sein, die Forschungsprojekte selbst genauer anzusehen. Wie plausibel sind die erzielten Resultate, die mit der Software zusammenhängen? Wie wurden sie von der wissenschaftlichen Community aufgenommen?

* **In welcher Form ist die Software publiziert?** Idealerweise sollte Forschungssoftware auch wissenschaftlich publiziert sein. Dies erleichtert die Zitierbarkeit. Gibt es ein Benchmarking-Paper, in dem das Werkzeug explizit vorgestellt und mit alternativen Produkten verglichen wird? Sind einzelne Versionen der Software auch als solche referenzierbar? Ist zum Beispiel ein Digital Object Identifier (DOI) und somit ein persistenter Link vorhanden? Wurde die Software in einer Fachzeitschrift oder anderem Medium veröffentlicht? Gab es dazu einen expliziten Software-Peer-Review Mechanismus?

### Bedienbarkeit und Zielgruppenorientierung

Die Bedienbarkeit von Forschungssoftware ist von zentraler Bedeutung, da sie als Flaschenhals alle Interaktion zwischen Nutzer und Software bestimmt. Dazu gehören z.B. die Komplexität des Installationsprozesses, das Nutzerinterface und maschinelle Schnittstellen. Hierbei ist zu beachten, dass eine grafische Nutzeroberfläche Vorteile für z.B. Gelegenheitsnutzer bietet, während eine Bedienung per Kommandozeile für die Prozessierung von größeren Datensammlungen für erfahrene Nutzer vorteilhafter ist. Hilfestellungen (Foren, FAQs, Tutorials) und die Größe und Aktivität der Nutzer- und Entwicklergemeinschaft sind entscheidend für die praktische Bedienbarkeit. Die Größe und Aktivität der Gemeinschaften kann ein wichtiges Indiz für die Zukunftsfähigkeit einer Software und damit ihre Eignung für den Einsatz auf institutioneller Ebene in langfristigen Vorhaben sein.

Die folgenden Fragen nehmen Bezug auf technische Merkmale, welche die Nutzererfahrung (User Experience, UX) beeinflussen. Weitere technische Merkmale aus der Entwicklerperspektive betrachten wir weiter unten.

#### Installation

Die Installation ist häufig der erste Schritt in der Bedienung der Software. Schon an dieser Stelle können Punkte auffallen und/oder für die Leser einer Rezension von Bedeutung sein.

* **Wie funktioniert die Installation und wo wird die Software vorgehalten?** Je einfacher die Installation einer Software ist, desto größer ist ihr potentieller Nutzerkreis. Die Vielseitigkeit von Computersystemen macht es aus Entwicklersicht oft schwer, eine einfache Installation für alle Nutzer zu gewährleisten. Für die Rezension kann geprüft werden, ob ein Installationsskript, -wizard oder -paket bereitsteht. Gegebenenfalls ist die Software nur als Quellcode verfügbar, der zunächst selbst kompiliert werden muss. Installationsskripte oder -pakete ermöglichen einen viel breiteren Anwenderkreis, während das Kompilieren es geübten Nutzern erlaubt die Installation auf verschiedenen Endgeräten durchzuführen. Wenn die Software für die Rezension selbst installiert wird, können konkrete Probleme und Schwachstellen beim Installationsprozess erkannt und in der Rezension dokumentiert werden.

* **Handelt es sich um eine eigenständige (stand-alone) Software oder um eine Webanwendung?** Nicht jede Software muss lokal installiert werden, um genutzt werden zu können. Webanwendungen, die entweder dynamisch im Browser oder auf einem Server ausgeführt werden, sind heute zu beliebig komplexen Operationen in der Lage. Passt die Lösung der Plattform zum archäologischen Einsatz? Eine Webanwendung kann z.B. nicht hinreichend performant sein, da sie den Transfer großer Datenmengen über das Internet erfordert. Webanwendungen sind im Gelände gegebenenfalls nicht ausführbar, und daher nicht für alle Arbeitsbedingungen sinnvoll.

* **Sind grundlegende Voraussetzungen in Form von Hardware und Betriebssystem klar dokumentiert?** Gerade in der Projektplanung ist es wichtig, technische und finanzielle Anforderungen korrekt identifizieren zu können. Eine Spezifikation bzw. Hinweise zur benötigten Hardware und Betriebssystem sind z.B. für die Einbindung von vorhandenen Infrastrukturen bei größeren Vorhaben oder Instituten von Relevanz.

#### Interface

Die Nutzbarkeit von Software wird von den Möglichkeiten der Kommunikation von Mensch und Programm bestimmt, also der Software-Oberfläche (User Interface, UI). Diese ist in manchen Fällen grafisch gestützt (GUI), in anderen Fällen erfolgt die Bedienung über eine Befehlseingabe in der Konsole. Eine gemischte Bedienung ist ebenfalls nützlich, um verschiedene Nutzerkreise zu erreichen. Die Gestaltung von Oberflächen und die Nutzerführung in Menüstrukturen sind ein eigenes Aufgaben- und Forschungsfeld in der Softwareentwicklung. Gut an den Nutzer angepasste Lösungen sind das Ergebnis einer genauen Kenntnis der Zielgruppe und ihrer Gewohnheiten und Bedarfe, fügen sich also beispielsweise nahtlos in den archäologischen Forschungsprozess ein. Ein gutes Interface unterstützt das fehlerfreie und effiziente Arbeiten. So sind z.B. die Verständlichkeit der Menü-Einträge oder der Kommandos, aber auch die Aussagekraft von Fehlermeldungen Aspekte, die in der Rezension betrachtet werden sollten. Barrierefreiheit ist bislang ein unzureichend abgedecktes Kriterium, das aber ebenfalls die Effizienz und den möglichen Nutzerkreis adressiert.

* **Passt das User Interface zum Nutzerkreis?** Jeder Nutzerkreis, auch der des Rezensenten, wird bestimmte Erwartungen an die Bedienbarkeit der Anwendung haben. Für die einen ist eine Kommandozeilenanwendung sehr gut zu bedienen, während andere damit Probleme haben werden. Viele Softwarelösungen haben mehrere Nutzerschnittstellen. Beispielsweise können viele Webanwendungen sowohl über einen Suchschlitz und Filterfunktionen über die grafische Oberfläche einer Website, als auch code-basiert über eine REST-Schnittstelle angesteuert werden.

* **Ist die archäologische Nutzung vorgesehen?** Die Frage nach dem Nutzerkreis sollte auch speziell für die Archäologie gestellt werden: Entspricht der archäologische Einsatz den Anwendungsszenarien, die die Entwickler der Software vor Augen hatten? Das hat oft großen Einfluss auf das Nutzerinterface. Beispielsweise ist für von Archäologen genutzte CAD Software (z.B. [AutoCAD](https://www.autodesk.de/)) häufig für Architektur- oder Maschinenbauanwendungen konzipiert und konfrontiert Archäologen und Grabungstechniker mit einem  überwältigendem Funktionsumfang.

* **Orientiert sich die Menüführung an bestimmten Vorbildern?** Wenn sich die Menüführung oder Tastenkürzel an bekannter, in der Community verbreiteter Software orientiert, wird eine schnellere Einarbeitung ermöglicht. Manche Tools verwenden deswegen z.B. bewusst Eingabemasken, die weit verbreiteten Tabellenkalkulationsprogrammen nachempfunden wurden.

* **Ist das Programm mehrsprachig bzw. in welchen Sprachen wird es angeboten?** In Abhängigkeit von der Nutzergruppe, sollte das Programm eventuell mehrsprachig sein. Üblicherweise wird man zumindest eine englischen Fassung erwarten. Bei der Mehrsprachigkeit ist darauf zu achten, dass das Layout in jeder Sprache nutz- und lesbar bleibt. Beispielsweise können sich Beschriftungen von Buttons in der Textlänge stark unterscheiden und in manchen Sprachen zu einer abgeschnittenen Anzeige führen.

* **Sind die Fehlermeldungen für die Rezensentin gut verständlich?** Zum einen soll eine Fehlermeldung an den Benutzer, es diesem ermöglichen eine Aktion zur Behebung des Fehlers zu ergreifen. Nützliche und hilfreiche Fehlermeldungen sind entsprechend verständlich formuliert und sichtbar in der Anwendung platziert. Zum anderen kann eine Fehlermeldung ggf. ein Feedback an die Entwickler der Anwendung liefern. Dies muss die Fehlermeldung dem Benutzer auch kommunizieren und auch einen brauchbaren Bericht zur Behebung des Fehlers an die Entwickler schicken. Stack Traces (Hinweise auf die Stellen des Programmcodes an denen ein spezifischer Fehler auftrat) oder aus der Ausführungsumgebung übernommene Fehlermeldungen sind für die meisten Nutzer unverständlich.

#### Performanz und Robustheit

* **Ist die Implementierung performant?** Die Performanz einer Anwendung ist je nach Anwendungstyp von mehr oder weniger Wichtigkeit. Ein Rezensent sollte hier bewerten, ob die Software ihre Aufgabe in angemessener Zeit erfüllt. Gegebenenfalls kann der Rezensent die Ausführungszeit weiterer verwandte Softwareimplementierungen mit der von ihm zu Testenden vergleichen. Ein Rezensent wird wahrscheinlich nicht in der Lage sein die Gründe für eine mangelnde Performanz der Software zu erkennen. Für Webapplikationen und Plugins ist zu überprüfen, ob sie responsiv sind und über die verschiedenen Browser hinweg performant sind.

* **Ist die Software robust?** Die Robustheit einer Software setzt im Wesentlichen voraus, dass die Software Zwischenstände der Aufgaben, die sie ausführt, regelmäßig sichert, um bei einem unvorhergesehenen Abbruch wieder an dem Punkt anknüpfen zu können, an dem sie vor diesem Ereignis gearbeitet hat. Ein Fehlen dieser Funktion kann oft z.B. bei einem Stromausfall den Verlust von Einstellungen, Daten und/oder die Neuinitialisierung einer Berechnung bedeuten. Ein Beispiel für eine solche Robustheit ist das regelmäßige automatisierte Zwischenspeichern in einem Textverarbeitungsprogramm. Das Textdokument ist somit im Falle eines Absturzes der Software wiederherstellbar. Abhängig vom Anwendungsfall kann es auch vorteilhaft sein, dass die Software eine Historie der Benutzeränderungen vorhält und diese ebenfalls wiederherstellen kann. Dies kann die Spracheinstellungen oder auch die Anpassung von Maßeinheiten, Vorgaben zum Speicherort und ähnliches sein.


#### Hilfefunktionen, Tutorials und Community

Neben Hilfefunktionen und Tutorials ist es von großer Bedeutung, ob die Software von einer *Community* getragen wird. Die Zahl der aktiven Nutzer und Entwickler eines Softwarewerkzeugs ist entscheidend dafür, ob man bei Problemen Hilfe in Foren findet, oder, bei einem kleinen Nutzerkreis, nur im persönlichen Austausch Hilfe bekommt. Kleine Nutzernetzwerke können jedoch den großen Vorteil bieten, dass konkrete Fragen von den Entwicklern aufgegriffen werden.

* **Gibt es ausreichend Tutorials für das Erlernen der Software?** Tutorials sind essentiell, um sowohl Benutzer als auch Softwareentwickler anzusprechen. Nutzer erwarten üblicherweise ein leicht verständliches, auf das Wesentliche konzentrierte Anwendungsbeispiel, um eine Idee für deren typische Verwendung zu bekommen. Für Entwickler ist entscheidend, dass ein Tutorial ggf. vorhandene Schnittstellen (APIs) erläutert.
Gute Tutorials erläutern das benötigte Vorwissen und weisen auf Quellen zu dessen Aneignung hin. Auch Hilfestellungen in einer FAQ oder einem Troubleshooting-Bereich erhöhen die Qualität eines Tutorials. In welchen Sprachen die Tutorials vorliegen ist ebenfalls von Relevanz.

* **Gibt es für die Software Testdatensätze?** Diese Frage ist eng mit der Frage nach Tutorials verbunden, da letztere oft mit Übungsdaten arbeiten. Diese Übungsdaten oder Testdatensätze sollten sich an der wissenschaftlichen Praxis orientieren, jedoch ohne spezifische Vorkenntnisse verständlich sein. Sie sollten frei zur Verfügung stehen und möglichst ohne Registrierung nutzbar sein.

* **Sind weitere Informationen zur Software leicht zu finden?** Listen die Informationsseiten der Software oder deren Tutorials Hinweise auf weitere Materialien? Wird auf Publikationen der Entwickler selbst, wie auch Rezensionen dazu hingewiesen?

* **Wird die Software von einer Community getragen? Ist diese möglicherweise ganz oder teilweise altertumswissenschaftlich geprägt ?** Beispiele für Softwareentwicklung, die zunächst aus einer altertumswissenschaftlichen Community heraus betrieben wurde und sich inzwischen fachlich erweitert hat, sind [Pelagios Commons](https://pelagios.org/) und die Webanwendung [Recogito](https://recogito.pelagios.org/). Engagierte Nutzergruppen mit einem Fokus auf archäologische Fragestellungen haben sich auch z.B. innerhalb der Communities von Softwarepaketen wie QGIS oder R entwickelt.

* **Gibt es archäologische Best Practcies oder Publikationen die auf die rezensierte Software verweisen?** Während Foren, Blogs und verwandte Angebote direkten und oft auch raschen Austausch mit Nutzern und ggf. Entwicklern bieten, ist die Einbindung von Empfehlungen von bestimmten Programmen ein weiteres Indiz für deren Verbreitung, Umfang und Verlässichlichkeit.

#### Dateningest, Interoperabilität und Schnittstellen

Eingabe- und Ausgabedatenformate beeinflussen die Kompatibilität zu anderen Anwendungen und sollten in einer Rezension erwähnt werden. In vielen Fällen können die unterstützten Dateiformate über einen entsprechenden Menü-Eintrag (z.B. "speichern unter") gefunden werden. Auch die verschiedenen Möglichkeiten des Einlesens der Daten und vorhandene Schnittstellen sind relevant.

* **Welche Datenformate werden wie eingelesen?** Sind alle relevanten Datenformate für die Aufgabe, die die Software im typischen Anwendungsfall lösen soll, einlesbar? Werden offene Datenformate unterstützt? Können Datenformate auch von gängigen Repositories eingelesen werden (z.B. Webservices, Git, Cloud Services)?

* **Welche Datenformate werden ausgegeben?** Das Programm sollte eine Ausgabe von Datenformaten bieten, die eine Weiterverarbeitung in anderen (auch Open Source) Softwarepaketen zulassen. Es sollte also zumindest ein offen spezifiziertes Format angeboten werden. Sollten nur Exporte in einem proprietärem, ggf. von der Software definierten Format möglich sein, muss dies von den Entwicklern gut begründet sein.

* **Wie können Daten eingelesen werden? Als Stapel oder nur einzeln? Ermöglicht die Software eine Stapelverarbeitung?** Für sehr viele Anwendunsgsszenarien ist die Durchführung eines einmal definierten Tasks auf einen Dateistapel oder eine Datenreihe wichtig. Ein Beispiel ist die  Transformation von Bilddaten, die auf jedes Foto einer Ausgrabungskampagne ausgeführt werden soll.

* **Gibt es eine Programmierschnittstelle (API)?** Neben der Bedienbarkeit durch einen Menschen, ist auch eine maschinelle Ansteuerung der Software wichtig. Nur so können beispielsweise komplexe Prozesse mit mehreren Softwarekomponenten komplett automatisiert werden. Eine API gewährleistet dies. Sie sollte möglichst offen und ggf. mittels eines Standards wie [OpenAPI](https://www.openapis.org) dokumentiert sein. Ein  Beispiel für APIs sind die Schnittstellen von Wikidata, an die man automatisierte Datenabfragen stellen kann.

#### Konformität mit Regelungen zum Datenschutz und der Datensparsamkeit

Für den Einsatz in der universitären Forschung und der Lehre entscheidet die Frage nach dem Datenschutz vielfach darüber, ob die Software überhaupt genutzt werden darf. Eine Einschätzung der Regelungen, sofern sie sich nicht eindeutig auf die europäischen Rahmenrichtlinien beziehen, ist teilweise jedoch kaum möglich und Gegenstand von juristischen Diskussionen. Auch hier kann die Rezension bereits durch den Hinweis auf das Thema einen wichtigen Service für die Leser bringen. Dies gilt auch für Datensparsamkeit und das Hinterfragen von Registrierungsvorgängen, Cookies und ähnlichem.

* **Werden die Gesetze (z.B. zu Datenschutz, Kartendarstellungen etc.) des Einsatzlandes durch die Software eingehalten?** Es muss damit gerechnet werden, dass die Software in verschiedenen Regionen und Ländern verwendet wird,  welche jeweils spezifische Gesetze haben, die sich auf die  Ausführung/Installation der Software auswirken. Ein Beispiel sind Grenzen auf Kartendarstellungen, die wegen Grenzkonflikten wie etwa der um Kashmir, zu unterschiedlichen Darstellungen in Indien, Pakistan, China und den übrigen Staaten führt. Ein weiteres Beispiel ist die EU-weite Datenschutzgrundverordnung.

* **Welche Daten speichert die Anwendung zu welchem Zweck und wie lange? Werden Daten an Dritte übertragen?** In vielen Softwareanwendungen werden Nutzerdaten zur Verbesserung der Anwendungen anonymisiert erfasst. Manche Softwareanbieter sammeln jedoch weitaus mehr Daten und übertragen diese z.B. auch an Drittanbieter. Aus der Softwaredokumentation heraus und vor allem beim Erstbesuch einer Webanwendung sollte ersichtlich werden welche Daten erhoben und wie lange sie gespeichert werden sowie ob die Zustimmung des Benutzers eingeholt wird. In einer Rezension könnte zusätzlich hinterfragt werden, ob der Zweck der Datenerfassung gerechtfertigt scheint, wie etwa zur Verbesserung der Software oder anderen Interessen dient.

### Entwickler-Perspektive

Anwendungsentwickler sind zwar auch Nutzer einer Software, haben jedoch wegen zusätzlicher Interessen und weiterer Anwendungsszenarien einen anderen Blick auf Software. Eine gute Zusammenfassung der Entwicklerperspektive auf die Softwarequalität bietet [@jung2004measuring](#jung2004measuring). Hier werden die Vorgaben des [ISO/IEC 9126 Standards](https://de.wikipedia.org/wiki/ISO/IEC_9126) in Beispielen ausgeführt. 

Die folgenden Fragen fokussieren sich auf den Programmcode und die Softwarearchiteḱtur. Diese können nur beurteilt werden, wenn der Quellcode offen einsehbar (Open Source) ist, was bei proprietärer Software meist nicht möglich ist.

#### Dokumentation und Tests

Eine umfangreiche Dokumentation bietet ein umfassendes Verständnis über die Intention, die Ausgereiftheit und den aktuellen Entwicklungsstand der Software. Sie ist essentiell um die Software zu erweitern. Eine ausreichende Dokumentation wird eine größere Community von potenziellen Entwicklern ansprechen. 

Man unterscheidet mehrere Dokumentationsbestandteile: die *Dokumentation des Quellcodes*, d.h. von Klassen oder einzelnen Methoden, die *Dokumentation des Build-Prozesses*, d.h. wie die Software aus dem Quellcode erzeugt wird, eine *Entwicklerdokumentation* mit Beispielen Nutzungsbeispielen, und eine *Dokumentation des Softwaretestprozesses* wurde bzw. welche Testfälle von der Software berücksichtigt wurden.

Software Repositorien wie [GitHub](https://github.com) oder [GitLab](https://gitlab.com) bieten oft Vorlagen oder Best Practices um diese Anforderungen in verschiedenen Programmiersprachen umsetzen zu können.

Ein wichtiger Begriff in dem Zusammenhang von Dokumentation und Tests ist auch der der *Continuous Integration* (CI, Kontinuierliche Integration). Damit wird die fortlaufende Zusammenfügung der Einzelkomponenten einer Anwendung bezeichnet. Hierfür werden Routinen erstellt, die vielseitige Aufgaben durchführen. So kann beispielsweise automatisiert die Erstellung einer Quellcodedokumentation, die Durchführung eines Softwaretests oder die Erzeugung einer ausführbaren Datei aus dem Quellcode (Releasefile, exe-Datei) angestoßen werden. Dabei werden diese Routinen meist nach jeder Änderung des Quellcodes erneut ausgeführt, wodurch alle Programmkomponenten aktuell bleiben.

* **Ist eine Quellcodedokumentation vorhanden und ggf. eine HTML Variante davon verfügbar?** Best Practices sind hier beispielsweise Quellcodedokumentationen mit [Doxygen](https://www.doxygen.nl/index.html), [JavaDoc](http://www.oracle.com/technetwork/java/javase/documentation/javadoc-137458.html), [JsDoc](https://jsdoc.app) oder das für Python beliebte [ReadTheDocs](https://readthedocs.org). Alle genannten Tools erzeugen eine HTML-Repräsentation der Dokumentation, welche idealerweise auch online bereitgestellt werden sollte, etwa als GitHub-Page.

* **Ist der Build-Prozess dokumentiert und ggf. mittels Buildingscripts automatisiert?** Neben dem grundlegenden Verständnis der Programmarchitektur, ist das Wissen um die Bauanleitung, dem Build-Prozess, der Software wichtig. Eine Dokumentation dieses Prozesses sollte Informationen über den funktionierenden Erstellungsprozess der Software enthalten. In der Vergangenheit wurde mit Anleitungen in *README Files* oder ähnlichen natürlichsprachlichen Beschreibungen gearbeitet. Inzwischen ist es etablierter Standard maschinenlesbare Bauanleitungen (*Buildscripts*) bereitzustellen. Diese beschreiben eindeutig und maschinenlesbar, wie die Software erstellt wurde und erlauben oft das Starten des Build-Prozesses mit einem einzigen Skript. Abhängigkeiten der Software in Bezug auf verwendete *Libraries* werden mit Buildscripts ebenfalls dokumentiert. Beispiele für solche Skripts finden sich z.B. in [Apache Maven](https://maven.apache.org) oder [Gradle](https://gradle.org).

* **Ist die Dokumentation aktuell und adressiert sie alle Funktionen des Programms?** Das letzte Bearbeitungsdatum einer Dokumentation ist meist einem Zeitstempel zu entnehmen, wenn die Dokumentation mit einem Dokumentationswerkzeug, wie oben genannt, erstellt wurde. Dieses Datum sollte mit dem Veröffentlichungsdatum der aktuellsten Software übereinstimmen oder aktueller sein. Werden im besten Fall die Prinzipien der *Continuous Integration* angewendet, so ist die Erzeugung und Bereitstellung der Dokumentation direkt mit im Entwicklungsprozess der Anwendung integriert, wie beispielsweise das [GitHub Repository des SPARQLing Unicorn QGIS Plugins](https://github.com/sparqlunicorn/sparqlunicornGoesGIS). Hier erstellt ein automatisierter Prozess die Dokumentation bei jeder Veränderung des Quellcodes neu und publiziert sie auf der [GitHub Page des Repositories](https://sparqlunicorn.github.io/sparqlunicornGoesGIS/).

* **Gibt es eine Entwicklerdokumentation, welche eine evtl. Softwareerweiterung fördert?** Eine Entwicklerdokumentation bietet einem Entwickler den Einstieg in der Beschäftigung mit der Erweiterung einer Software über die einfache Nutzung hinaus. Eine aussagekräftige *README*-Datei, die kurz die Verwendung des Programmes mit den Standardeinstellungen demonstriert, ist eine Mindestanforderung. Ein Beispiel dafür ist [Bibtex_JS](https://github.com/pcooksey/bibtex-js). Idealerweise werden zusätzlich Beispieldaten für ein besseres Verständnis des Programmablaufs beigelegt und ggf. weitere häufig verwendete Anwendungsfälle der Software in Beispielen vorgestellt. Für das gerade genannte Beispiel trifft dies zu: [Bibtex_JS Beispiele](https://github.com/pcooksey/bibtex-js/tree/master/test)). Abhängig von der Komplexität der Software kann es sinnvoll sein, ein ggf. auch von einer Nutzercommunity gepflegtes Wiki bereitzustellen, um fortgeschrittene Optionen zu erläutern (siehe [Bibtex_JS Wiki](https://github.com/pcooksey/bibtex-js/wiki)).

* **Enthält der Quellcode Softwaretests, um die Kernfunktionen zu testen und diese für andere Entwickler aufzuzeigen?** Jede Software kann durch Tests auf ihre antizipierte Funktionalität hin überprüft werden. Entsprechend geben Softwaretests Auskunft über die angedachten Anwendungsfälle und, als Testergebnis, welche Funktionen stabil, fehleranfällig oder verbesserungsbedürftig sind. Als Teil eines *Continuous Integration*-Prozesses können Softwaretests nach jeder Änderung am Quellcode automatisch ausgeführt werden.

* **Wird es dem Entwickler einfach gemacht, die Software zu testen (z.B. Virtuelle Maschine, Dockercontainer, Installer)?** Entwickler sind meist in der Lage, eine Software zu bauen und auszuführen, doch das kann mehr oder weniger aufwändig sein. Tatsächlich werden Softwares, welche leicht installierbar und vor allem testbar sind, sowohl von Entwicklern die einen schnellen Einblick in die Funktionalität bekommen wollen, als auch von anderen Benutzern einen besseren Anklang finden als andere. Es liegt in der Natur der Sache, dass es hierbei, je nach Art der Anwendung, unterschiedliche Ausführungsformen gibt. Eine Webanwendung kann als Beispiel im Internet gehostet sein und dem Benutzer einen Testaccount zur Verfügung stellen (z.B. [CWRCWriter](https://cwrc.ca)), eine Desktop Anwendung kann bereits eine installierebare Anwendung oder ein Installerpaket mitliefern. Serveranwendungen können für einen Test als Images von virtuellen Maschinen oder - in letzter Zeit üblicher - als Dockerimages in Portalen wie [Dockerhub](https://hub.docker.com) für ein einfaches Testen hinterlegt werden.

* **Wird an der Software aktiv gearbeitet und sind deren Entwickler gut erreichbar?** Oft stellt sich bei der Bedienung von Software heraus, dass Funktionalitäten fehlen oder Fehler im Programm vorhanden sind. Dies kann die Verwendung der Software für bestimmte Anwendungsfälle behindern oder deren Ergebnisse signifikant verschlechtern. In solchen Fällen ist die Verfügbarkeit der Entwickler und deren Rückmeldungen auf Supportanfragen ein entscheidendes Kriterium.

Es sollte eindeutig kommuniziert werden wie und wo Fehlerberichte eingereicht werden können und welche Informationen für eine rasche und präzise Bearbeitung erforderlich sind. Ob die Entwickler einen aktiven Austausch pflegen, kann man beispielsweise in dem Issue-Bereich des Softwarerepositoriums (z.B. GitHub oder GitLab) ablesen. Haben die Entwickler Anfragen dprt zeitnah und zufriedenstellend beantwortet? Wie ist das Verhältnis von offenen Issues zu bereits geschlossenen? Wie lange dauerte es bis eine Änderung eingepflegt wurde?

Welche Änderungen demnächst für das Programm geplant sind und welche Issues für das nächste Release bearbeitet werden sollen, können Entwickler proaktiv in einer Roadmap kommunizieren. Damit Softwareentwickler die Software dann erweitern können, ist eine *Contribution Guideline* hilfreich. Sie enthält Angaben dazu, unter welchen Umständen und wie Änderungen an der Software von Dritten angenommen und integriert werden (siehe z.B. [hier](https://projectacrn.github.io/latest/developer-guides/contribute_guidelines.html)).

Wird die Software regelmäßig mit Updates versorgt? Gibt es eine Roadmap für die weitere Entwicklung? Gibt es *Contribution Guidelines*?

> [TODO] Die vorangehenden vier Absätze ab "Wird an der Software aktiv gearbeitet..." sollten neu gegliedert werden

#### Qualität der Implementierung

* **Entspricht die Implementierung dem Stand der Technik?** Diese Frage muss meist anwendungsbezogen beantwortet werden und verlangt ein technisches Verständnis der Abläufe innerhalb der Anwendung. Einige Aspekte können ohne Fachwissen bewertet werden:
  * Ist die Anwendung auf vielen verschiedenen Endgeräten bedienbar? (z.B. Handy, verschiedene Betriebssysteme usw.)
  * Werden keine veralteten Technologien verwendet, wie etwa Adobe Flash, Java Applets bei Webanwendungen?
  * Zeichnen automatische Testsysteme (etwa auf GitHub) offene Sicherheitslücken in der Software aus?

* **Wird *Continuous Integration* zur Absicherung der Implementierungsqualität verwendet?** Für einen Entwickler ist nicht nur das Vorhandensein und die Dokumentation des Quellcodes entscheidend, sondern er wird meistens auch einen Hinweis zur Funktionalität und Kompilierbarkeit des Quellcodes erwarten. *Continuous Integration* kann, wie schon in den vorherigen Abschnitten angesprochen, ein solches Qualitätsmerkmal darstellen. Der *Continuous Integration* Prozess überprüft die Kompilierbarkeit der Software nach jeder Änderung und kann diese am Repository mit einer Statusanzeige sichtbar machen. Es ist ein Zeichen von gut gewartetem Quellcode, wenn dieser in der aktuell vorliegenden Version und ggf. in der aktuellen Entwicklerversion kompiliert.

## Software-Eckdatentabelle

Im folgenden stellen wir einige Punkte vor, die tabellarisch am Ende oder Anfang der Rezension genannt werden können um einen schnellen Überblick über eine Software zu geben -- ähnlich wie in Buchrezensionen Titel, Verlag und ISBN wertneutral gelistet werden. Diese Tabelle kann ggf. auch um Hardwareforderungen ergänzt werden, wenn diese als besonders relevant empfunden werden. Als Beispiel haben wir die GIS-Anwendung QGIS gewählt.

- Name: Der Name der Software, z.B. "QGIS"
- Kurzbeschreibung: Was die Software leistet, z.B. "Umfangreiches graphisches Werkzeug zur Raumdatenverarbeitung"
- Rezensierte Version: Die Softwareversion, die für die Rezension genutzt wurde, z.B. "3.10.10 LTR"
- Plattform: (Betriebs)systeme, auf denen die Software genutzt werden kann, z.B. "Windows, macOS, Linux, BSD, Android"
- Website: URL unter der weitere Informationen abgerufen werden können, z.B. "https://qgis.org"
- Lizenzierung: Unter welcher Softwarelizenz wurde die Software veröffentlicht, z.B. "Open Source mit GNU General Public License (GPL)"
- Ein- und Ausgabeformate: Welche Dateiformate die Software verarbeiten kann, z.B. "Geodatenbanken (SpatiaLite, PostGIS, MSSQL, ...), Web-Geodaten Dienste (WMD/WMTS, Vector Tiles, XYZ Tiles, WFS, ...), Geo-Vektordatenformate (ESRI Shapefile, Geopackage, ...), Geo-Rasterdatenformate (GeoTIFF, ...), Tabellendaten (CSV, TXT, ...) und weitere Datentypen." (für QGIS sind natürlich ungewöhnlich viele Datenformate zu beachten)

## Ausblick

Dieser Leitfaden entstand in einer Zeit, die von einem beschleunigten digitalem Wandel geprägt ist und sich unter anderem an den sich gerade formierenden *Nationale Forschungsdateninfrastruktur* (NFDI) der *Deutschen Forschungsgesellschaft* (DFG) zeigt. Während bei Daten bereits mehr Konsens und Erfahrung besteht, wurde die Diskussion zur Bewertung von Software in der Archäologie und ihrer Nachbardisziplinen gerade erst begonnen. Da zum Zeitpunkt unserer Diskussionen nur wenige Softwarerezensionen für archäologische Aufgaben vorlagen sind viele der Überlegung die hinter den Empfehlungen stehen von einer gewissen theoretischen Natur. Damit ist eine künftige Überarbeitung dieses Dokuments bei besserer Datenlagen eine abschließende Empfehlung.

## Anmerkungen

<a name="#authornote">*</a>: Autorenangaben in alphabetischer Reihenfolge.

## Bibliographie
