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
    name: Clemens Schmid
    affiliation: Max-Planck-Institut für Menschheitsgeschichte Jena
    orcid: 0000-0003-3448-5715
    bio: "Clemens Schmid studierte Prähistorische, Historische und Naturwissenschaftliche Archäologie und Informatik in Tübingen und Kiel. Nach Studienabschluss arbeitete er mit computerbasierter Datenanalyse in verschiedenen archäologischen Forschungsprojekten an der Universität Kiel, dem Römisch-Germanischen Zentralmuseum in Mainz und der Universität Bern. Im Augenblick ist er für ein Promotionsprojekt zur quantitativen Nachhersage von Mobilitätsverhalten mit genetischen und historisch-linguistischen Daten in der Abteilung für Archäogenetik des Max-Planck-Instituts für Menschheitsgeschichte in Jena beschäftigt."
  -
    name: Sophie Charlotte Schmidt
    affiliation: Deutsches Archäologisches Institut
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

{% include {{ page.abstract_de }} %}

{% include {{ page.abstract_en }} %}

## Zielsetzung des Beitrags

Ziel dieses Beitrags ist es, die Diskussion um Inhalte und Zielsetzungen von Rezensionen von Forschungssoftware in den Altertumswissenschaften anzuregen. Anstoß für unsere Überlegungen gab eine Diskussion von Kai-Christian Bruhn, Sophie Charlotte Schmidt und Frank Siegmund im Plenum des 9. Workshops der deutschen Sektion der CAA 2019 in Wilhelmshaven. Anlässlich der Einrichtung der neuen Rubrik für solche Besprechungen in den Archäologischen Informationen haben wir unsere Gedanken nun verschriftlicht.

Die Beurteilung einer Publikation ist eine traditionsreiche Form des wissenschaftlichen Diskurses. Entsprechend gibt es ein unausgesprochenes Verständnis davon, was eine Rezension umfassen sollte. Aus Redaktionsperspektive können zusätzlich konkrete Maßnahmen zur Qualitätssicherung ergriffen werden. Dazu gehören ausformulierte Hinweise zum Anfertigen von Rezensionen oder - wie es die Redaktion der Archäologischen Informationen praktiziert - Reviews von Rezensionen. Was sollte aber nun eine gute Rezension von Software für den Einsatz in der Archäologie ausmachen? Geht es allein um die digitale Operation, die die Software zur Lösung einer wissenschaftlichen Problemstellung beisteuert? Oder müssen Aspekte der Nutzbarkeit, der Nachhaltigkeit und Anschlussfähigkeit ebenfalls Beachtung finden? Welche Rolle spielen technische und rechtliche Aspekte, wie etwa die Dokumentation des Quellcodes oder Lizensierungsfragen, in der Besprechung? Und schließlich, stellt die Software vielleicht selbst einen wissenschaftlichen Beitrag dar? Was sind die Leistungen der Software-Entwickler, die eine Besprechung berücksichtigen sollte?

In diesem Beitrag empfehlen wir eine Vorgehensweise zur Softwarerezension und sammeln Kriterien, die für die Bewertung einer Software von Bedeutung sein können. Wir konzentrieren uns dabei bewusst auf Aspekte, die spezifisch für die Besprechung von Software sind. Dies bringt mit sich, dass die einer Rezension innewohnende, zentrale Fragestellung nach dem wissenschaftlichen Wert des Besprechungsgegenstands nur gestreift wird. Denn: An diesem Punkt stimmen die Anforderung an eine Besprechung einer traditionellen Publikation und Software letztlich überein. Weiterhin werden aufgrund der Vielfalt und Vielartigkeit von Software nicht alle von uns hier gesammelten Kriterien in jeder Rezension von Bedeutung sein. Es bleibt dem Rezensent überlassen, Aspekte auszuwählen und Schwerpunkte zu legen.

Darüber hinaus erläutern wir auch einige generelle Kriterien für gute Forschungssoftware. Dabei folgen wir den Empfehlungen der Deutschen Forschungsgemeinschaft (DFG) und weisen auf sogenannte ["open standards"](http://xml.coverpages.org/openStandards.html) hin. Software greift im- und explizit tief in den Forschungsprozess ein (für die Archäologie siehe z.B. [@schmidt_marwick_2020](#schmidt_marwick_2020)) und nur durch die Offenlegung von Quellcode ist eine Bewertbarkeit der durch die Software geleisteten Abläufe wirklich gewährleistet.

Die hier vorgestellten Überlegungen, Kriterien und Vorschläge sollen als Arbeitserleichterung dienen und bei der Erstellung einer Softwarebesprechung unterstützen. Der Beitrag ist als Impuls angelegt und wir wünschen uns Diskussionsbeiträge sowie Anregungen. Dazu können entweder die Autoren über die angegebenen Adressen kontaktiert werden oder direkt Diskussionsthemen (Issues) und gegebenfalls sogar Änderungsvorschläge (Pull Requests) hier [https://github.com/Research-Squirrel-Engineers/DGUF_Leitfaden](https://github.com/Research-Squirrel-Engineers/DGUF_Leitfaden) eingebracht werden.

## Forschungssoftware

Die weiter unten vorgestellten Kriterien zur Rezension von Software zielen primär auf die Begutachtung von Forschungssoftware ab. Unter Forschungssoftware verstehen wir Software, die mit Fokus auf den Einsatz in der Forschung entwickelt wurde, also um Forschungsdaten zu erzeugen, zu verarbeiten oder zu analysieren [@hettrick_2014_14809](#hettrick_2014_14809). Dies sind beispielsweise Programme, die der Kalibrierung und Umrechnung von Messwerten, der Visualisierung von Raumdaten, der Annotation von Texten und Objekten, oder der Bereitstellung sowie der Verknüpfung fachlich relevanter Vokabulare dienen.

Forschungssoftware kann entweder für einen sehr spezifischen Bedarf oder aber einen allgemeinen Anwendungsbereich entwickelt werden. Sie ist dabei stets Teil des Forschungsprozesses, der in allen seinen Punkten nachvollziehbar und soweit möglich reproduzierbar sein muss. Forschungssoftware kann hierbei von zwei Blickwinkeln aus betrachtet werden:

1. Forschende wenden eine Forschungssoftware im Kontext ihrer Arbeiten an.
2. Forschende entwickeln Forschungssoftware im Kontext ihrer Arbeiten.

Im Gegensatz zu Forschungssoftware steht Software, die zur Nutzung spezifischer Geräte erforderlich ist, wie etwa zur Vermessung, zur fotografischen Dokumentation oder zur Analyse von Oberflächen und Inhaltsstoffen. Häufig handelt es sich dabei um proprietäre Software, die zusammen mit der Hardware vertrieben wird. Obwohl sie im Forschungsprozess eingesetzt wird, entspricht sie nicht unserem Verständnis von Forschungssoftware. Auch digitale Werkzeuge, die eine erhebliche Rolle in der praktischen Arbeit inne haben, jedoch keinen eigentlichen Anteil an der Erhebung, Bearbeitung und Analyse der Daten haben, sind in unserem Sinne keine Forschungssoftware. Dazu gehören z.B. Textverarbeitungs- oder Tabellenkalkulationsprogramme. Die vorgestellten Kriterien können zur Beurteilung jedes Software-Typs verwendet werden.

Forschungssoftware ist in besonderer Weise Herausforderungen nachhaltiger Entwicklung und Pflege ausgesetzt. Als einen Hauptfaktor für fehlende Nachhaltigkeit von Forschungssoftware identifizieren wir den Mangel an langfristiger Finanzierung für Personal und Infrastruktur zur Erzeugung von nachhaltiger Software ([@anzt_environment_2020, 2](#anzt_environment_2020)). Einen Überblick über Bedarfe, Herausforderungen und Lösungsansätze für nachhaltige Forschungssoftwareentwicklung wurde 2019 in einem Workshop der [deRSE Konferenz in Potsdam](https://de-rse.org/de/conf2019/index.html) erstellt ([@bach_dersews19](#bach_dersews19)).

### Forschungssoftware als wissenschaftliche Leistung

In der modernen Forschung ist ein Arbeiten ohne digitale Werkzeuge undenkbar. Dies trifft auch auf die historische und altertumswissenschaftliche Forschung zu. Mit dem Aufschwung der Digital Humanities wird Software zunehmend ein wichtiger Bestandteil des Forschungsprozesses.

Trotz der tragenden Rolle, die Forschungssoftware in vielen Projekten einnimmt, wird die Leistung jener Personen, die hinter der Entwicklung und Programmierung stehen, akademisch oft nicht ausreichend anerkannt ([@hettrick_2017](#hettrick_2017), [@scheliga_pampel_2017](#scheliga_pampel_2017) und [@katerbow_2018](#katerbow_2018)). Das wird der Tatsache nicht gerecht, dass für die Entwicklung von Forschungssoftware wissenschaftliche Expertise und darüber hinaus fortgeschrittene technische Kompetenz erforderlich sind. Durch die Umsetzung in Code wird Praxis und Wissen explizit manifestiert und weiterentwickelt. Wir argumentieren, dass diese Leistungen gewürdigt und sichtbar gemacht werden müssen, zumal der wissenschaftliche Durchbruch häufig erst durch die Software ermöglicht wird ([@scheliga_pampel_2017](#scheliga_pampel_2017), [@katerbow_2018](#katerbow_2018) sowie [@helmholtz_web](#helmholtz_web)).

Als ein wichtiger erster Schritt zur Sichtbarmachung wurde 2012 die Berufsbezeichnung des "Research Software Engineers" (RSE, RSEng) geprägt ([@hettrick_2017](#hettrick_2017) und [@baxter_2012](#baxter_2012)). Inzwischen hat sich eine aktive, interdisziplinäre Gemeinschaft gebildet, die Empfehlungen zum Umgang mit Forschungssoftware entwickelt ([@anzt_environment_2020](#anzt_environment_2020)). Nationale [RSE Sektionen](https://sorse.github.io/contact/chapters/) - in Deutschland der de-RSE e.V. - organisieren Konferenzen wie z.B. [SORSE](https://sorse.github.io). Im Rahmen des Aufbaus einer \`Nationalen Forschungsdateninfrastruktur (NFDI)\` nehmen Forschungssoftware und RSEs einen großen Stellenwert in der Weiterentwicklung der Forschungslandschaft und der Angebote der Forschungseinrichtungen in Deutschland ein ([@loeffler_nfdi4rse20](#loeffler_nfdi4rse20) und [@goedicke_nfdixcs20](#goedicke_nfdixcs20)).

Eine der Forderungen des de-RSE e.V. ist, dass Forschungssoftware explizit mittels geeigneter Publikationsmodalitäten sichtbar wird. Einerseits erhöht eine Publikation die Auffindbarkeit und vermeidet so redundante Neuentwicklungen ([@anzt_environment_2020, 10](#anzt_environment_2020)). Andererseits ist die mit einer Publikation einhergehenden eindeutige Autorenschaft von großer Bedeutung, da erst dadurch die Leistung der Softwareentwicklung an die entsprechenden Personen geknüpft wird. Dies ermöglicht eine akademische Laufbahn, wofür bislang jedoch oft nur klassische Textpublikationen gewertet wurden. Daher sollen zukünftig Datenpublikationen, Softwareentwicklung ([https://citation-file-format.github.io](https://citation-file-format.github.io), [https://doi.org/10.5281/zenodo.1003149](https://doi.org/10.5281/zenodo.1003149)), Annotationen, sowie deren Zitationen Kriterien der Beurteilung der wissenschaftlichen Leistung sein ([NFDI4Culture](https://nfdi4culture.de), [RSE4NFDI](https://www.rse4nfdi.de/de/index.html), [NFDI4Objects](https://www.nfdi4objects.net)). Hierbei sind technische Herausforderungen zu meistern, da Software selten entgültig abgeschlossen, oft auf bestehenden Modulen aubaut und mitunter von wechselnden Teams über Jahrzehnte betreut wird [@katz_software_2016](#katz_software_2016).

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

[AK] Stark gekürzt, eventuell kann hier als Beleg ergänzt werden: [https://www.bundestag.de/ausschuesse/weitere_gremien/enquete_ki#url=L2Rva3VtZW50ZS90ZXh0YXJjaGl2LzIwMTkva3cyMy1wYS1lbnF1ZXRlLWtpLTY0NDAxMA==&mod=mod569768].

> [MT] schön kurz :) Den Satz mit dem Spielball habe ich noch entfernt, da polemisch


## Mögliche Vorgehensweise zur Rezension archäologischer Forschungssoftware

Unserem Verständnis nach sollte eine Rezension archäologischer Software, so wie es eine herkömmliche Besprechung einer wissenschaftlichen Publikation leistet, die Software zunächst kurz mit zusammenfassenden Eckdaten vorstellen. Anschließend sollte der ausführlicheren Kontext erläutert werden und eine kritische Beurteilung erfolgen.

Für Software gehören zu den Eckdaten u. a. Angaben zur Version, zu den Entwicklern und der Lizenz. Wir schlagen vor, den Lesern diese Eckdaten in einer tabellarischen Übersicht zur Verfügung zu stellen, wie sie etwa am Ende des Beitrags zu finden ist. Dies ermöglicht z.B. eine schnelle Übersicht, darüber ob die begutachtete Software mit der eigenen technischen Umgebung kompatibel ist.

Mit Kontext sind eine Einordnung in das archäologische Forschungsfeld und Angaben zum möglichen Zusammenhang mit Forschungsprojekten, Arbeitsgruppen oder Institutionen gemeint. Für die kritische Beurteilung aus verschiedenen Blickwinkeln folgt weiter unten ein Fragenkatalog. Die Ergebnisse der Begutachtung sollten in einer Stellungnahme zusammengefasst werden, die die Software hinsichtlich ihrer Nützlichkeit, ihrer Bedienbarkeit, ihrer handwerklichen Qualität und ihrer Position in Relation zu den Idealen guter Forschungssoftware (z.B. FAIR und CARE), beurteilt.

Selbstverständlich setzt die Rezension einer Forschungssoftware die Sichtung von Dokumentation und Publikationen ebenso voraus, wie die praktische Erprobung der Software selbst. Dabei ist eine realistische und transparente Einschätzung der eigenen Kompetenzen und des eigenen Nutzungsinteresses ein wichtiger Anhaltspunkt für die heterogene Leserschaft. Es ist eine wichtige Information, ob die Rezension rein aus Sicht eines Anwenders oder auch eines Entwicklers geschrieben wurde.  

## Fragenkatalog zur Beurteilung von Software

Im folgenden stellen wir einen kommentierten Fragenkatalog mit Kriterien zur Beurteilung von archäologischer Forschungssoftware vor. Seine drei Bereiche bündeln jeweils Fragen aus verschiedenen Kompetenzbereichen. Die ersten zwei Bereiche beschäftigen sich mit dem wissenschaftlichen Anwendungsfeld, sowie der Anwendung und Bedienbarkeit aus Nutzersicht. Der dritte Bereich Fragen, die insbesondere für Entwickler und IT-Administratoren relevant sind. Sie fokussieren vor allem auf Anwendbarkeit und Nachhaltigkeit. Abgeschlossen wird der Katalog durch eine Liste mit Merkmale, welche in tabellarischer Form die Rezension ergänzen, jedoch meist nicht kritisch beurteilt werden können.

> [MT] 3. Bereich: wirklich Anwendbarkeit?

Wie bei der Besprechung einer wissenschaftlichen Publikation ist die Zusammensetzung und Gewichtung der einzelnen Merkmale bei der Begutachtung selbst zu bestimmen und in Relation zum Thema zu setzen. Entsprechend verstehen wir unseren kommentierten Fragenkatalog als Maximalversion, die als Hilfsmittel für die Begutachtung und die Einschätzung der eigenen Kompetenzen dienen kann.

> [MT] 'in Relation zum Thema' - was ist hier mit Thema gemeint?

### Einsatz in der Archäologie und wissenschaftlicher Zweck

Forschungssoftware hat einen konkreten Zweck: sie erfüllt üblicherweise eine Aufgabenstellung. Dabei sind zwei Dimensionen zu unterscheiden. Dies ist zum einen, und das ist für Forschungssoftware vorrangig, die Frage, ob die Software einen sinnvollen Beitrag zur Bearbeitung der archäologischen Fragestellung liefert. Zum anderen ist zu beurteilen, ob Software eine korrekte Umsetzung der angestrebten Arbeit leistet. Beide Fragen sind mitunter nicht leicht zu beantworten.

* **Welche Aufgabenstellung versucht die Software zu lösen?** Diese Frage ist mit dem deskriptiven Charakter einer Rezension verknüpft: Welche Aufgaben werden mittels der Software bei der Erfassung, der Verarbeitung oder der Analyse von Daten bearbeitet? Wie relevant sind die Aufgaben in einem archäologischen Kontext und wie häufig werden sie gestellt? Dieser Punkt verdeutlicht, warum es von besonderem Wert ist, wenn Archäologen selbst Softwarerezensionen für sich und ihre Kollegen verfassen.

* **Wie löst die Software eine gegebene (technische) Aufgabe?** Eine detaillierte Beantwortung dieser Frage ist nur aus Entwicklerperspektive möglich, doch Kernbestandteile lassen sich meist leicht identifizieren. Wie ist die grundsätzliche Funktionsweise der Software konzipiert? Was sind die wesentlichen technischen Bestandteile im Nutzerinterface und in den dahinter liegenden Datenverarbeitungsmodulen? Handelt es sich zum Beispiel um eine WebApp, die als Schnittstelle zu einer Datenbank fungiert? Oder ist die Software ein schlichtes, monolithisches Kommandozeilenprogramm?

> [MT] WepApp oder Webanwendung? -> Vereinheitlichen

* **Wie funktioniert der wissenschaftliche Arbeitsablauf, der in der Software implementiert wurde?** Hier geht es weniger um die konkrete technische Implementierung, sondern vielmehr um die generelle Methodik. Welche wesentlichen Schritte durchlaufen Daten, um eine bestimmte Aufgabe zu lösen? Welche statistischen Werkzeuge kommen zum Einsatz? Gibt es Vergleichsdaten? Ein Beispiel für eine mögliche Prozessierung ist die Bereinigung von Eingabedaten mittels eines Referenzdatensatzes, um eine Klassifizierung mit einer hierarchischer Clusteranalyse zu erstellen und zuletzt als paarweise Distanzmatrix zu visualisieren.

* **Ist die Behauptung, eine bestimmte wissenschaftliche Fragestellung mit dem gewähltem Arbeitsablauf beantworten zu können, korrekt?** Forschungssoftware verspricht meist - implizit oder explizit - die Beantwortung wissenschaftlicher Fragestellungen zu ermöglichen oder zumindest zu vereinfachen. Eine GIS-Applikation zur Analyse von Punktmustern kann etwa für den Zweck konzipiert sein menschliches Siedlungsverhalten aufzuzeigen. Die Frage, ob der angebotene Arbeitsablauf dazu semantisch in der Lage ist, kann den Umfang einer Rezension bei weitem übersteigen. Dennoch sollte der Rezensent versuchen eine Einschätzung der Plausibilität vorzunehmen oder zumindest das Problem der Einschätzbarkeit selbst offenzulegen, um die Leser zu sensibilisieren. Zur Beurteilung kann es helfen sich zu vergegenwärtigen, welche semantischen Schlüsse aus den rohen, unverarbeiteten Eingabedaten überhaupt theoretisch ableitbar sein könnten.

> [MT] Bin mir nicht sicher, ob 'Semantik' passt. Das heißt ja so viel wie 'Bedeutung' und das ergibt für mich keinen Sinn.

* **Sind die Algorithmen korrekt implementiert worden?** Die Korrektheit der Ergebnisse einer Software ist mitunter schwer zu beurteilen, weil beispielsweise ein umfangreicher Blackbox-Test durchgeführt werden muss. Ein Mangel an vergleichbarer Software mit der zu testenden Funktionalität erschwert dies zusätzlich. Werden die in der Dokumentation genannten Algorithmen fehlerfrei in Programmcode ausgedrückt? Ist das wissenschaftliche Ergebnis trotz aller technischen Unterschiede vergleichbar mit anderen Softwarelösungen? Sind die verwendeten Algorithmen dokumentiert und hinreichend wissenschaftlich belegt? Auch diese Frage mag im Rahmen einer Rezension nicht abschließend zu beantworten sein. Ein wichtiges Indiz für eine fehlerhafte Implementierung ist eine mangelnde Robustheit, die später noch besprochen wird.

* **Gibt es für die Archäologie relevante Projekte/Anwendungen, in der die rezensierte Software bereits angewendet wurde?** Software wird oft von und für bestimmte Forschungsprojekte entwickelt. Zur Beurteilung ihrer Qualität und Relevanz kann es also hilfreich sein, die Forschungsprojekte selbst genauer anzusehen. Wie plausibel sind die erzielten Resultate, die mit der Software zusammenhängen? Wie wurden sie von der wissenschaftlichen Community aufgenommen?

* **In welcher Form ist die Software publiziert?** Idealerweise sollte Forschungssoftware auch wissenschaftlich publiziert sein. Dies erleichtert die Zitierbarkeit. Gibt es ein Benchmarking-Paper, in dem das Werkzeug explizit vorgestellt und mit alternativen Produkten verglichen wird? Sind einzelne Versionen der Software auch als solche referenzierbar? Ist zum Beispiel ein Digital Object Identifier (DOI) und somit ein persistenter Link vorhanden? Wurde die Software in einer Fachzeitschrift oder anderem Medium veröffentlicht? Gab es dazu einen expliziten Software-Peer-Review Mechanismus?

### Bedienbarkeit und Zielgruppenorientierung

Die Bedienbarkeit von Forschungssoftware ist von zentraler Bedeutung, da sie als Flaschenhals alle Interaktion zwischen Nutzer und Software bestimmt. Dazu gehören z.B. die Komplexität des Installationsprozesses, das Nutzerinterface und maschinelle Schnittstellen. Hierbei ist zu beachten, dass eine grafische Nutzeroberfläche Vorteile für z.B. Gelegenheitsnutzer bietet, während eine Bedienung per Kommandozeile für die Prozessierung von größeren Datensammlungen für erfahrene Nutzer vorteilhafter ist. Hilfestellungen (Foren, FAQs, Tutorials) und die Größe und Aktivität der Nutzer- und Entwicklergemeinschaft sind entscheidend für die praktische Bedienbarkeit. Die Größe und Aktivität der Gemeinschaften kann ein wichtiges Indiz für die Zukunftsfähigkeit einer Software und damit ihre Eignung für den Einsatz auf institutioneller Ebene in langfristigen Vorhaben sein.

Die folgenden Fragen nehmen Bezug auf technische Merkmale, welche die Nutzererfahrung (User Experience, UX) beeinflussen. Weitere technische Merkmale aus der Entwicklerperspektive betrachten wir weiter unten.

#### Installation

* **Wie funktioniert die Installation und wo wird die Software vorgehalten?** Je einfacher die Installation einer Software ist, desto größer ist ihr potentieller Nutzerkreis. Die Vielseitigkeit von Computersystemen macht es aus Entwicklersicht oft schwer, eine einfache Installation für alle Nutzer zu gewährleisten. Für die Rezension kann geprüft werden, ob ein Installationsskript, -wizard oder -paket bereitsteht. Gegebenenfalls ist die Software nur als Quellcode verfügbar, der zunächst selbst kompiliert werden muss. Installationsskripte oder -pakete ermöglichen einen viel breiteren Anwenderkreis, während das Kompilieren es geübten Nutzern erlaubt die Installation auf verschiedenen Endgeräten durchzuführen. Verschiedene Nutzergruppen bevorzugen unterschiedliche Installationsformen. Passt die gewählte Lösung zum Nutzerkreis? Wenn die Software für die Rezension selbst installiert wird, können konkrete Probleme und Schwachstellen beim Installationsprozess erkannt und in der Rezension dokumentiert werden.

> [MT] "Verschiedene Nutzergruppen bevorzugen unterschiedliche Installationsformen. Passt die gewählte Lösung zum Nutzerkreis?" -> würde ich ganz streichen

* **Handelt es sich um eine eigenständige (stand-alone) Software oder um eine Webanwendung?** Nicht jede Software muss lokal installiert werden, um genutzt werden zu können. Webanwendungen, die entweder dynamisch im Browser oder auf einem Server ausgeführt werden, sind heute zu beliebig komplexen Operationen in der Lage. Passt die Lösung der Plattform zum archäologischen Einsatz? Eine Webanwendung kann z.B. nicht hinreichend performant sein, da sie den Transfer großer Datenmengen über das Internet erfordert. Webanwendungen sind im Gelände gegebenenfalls nicht ausführbar, und daher nicht für alle Arbeitsbedingungen sinnvoll.

* **Sind grundlegende Voraussetzungen in Form von Hardware und Betriebssystem klar dokumentiert?** Gerade in der Projektplanung ist es wichtig, technische und finanzielle Anforderungen korrekt identifizieren zu können. Eine Spezifikation bzw. Hinweise zur benötigten Hardware und Betriebssystem sind z.B. für die Einbindung von vorhandenen Infrastrukturen bei größeren Vorhaben oder Instituten von Relevanz.

#### Interface

Die Nutzbarkeit von Software wird von den Möglichkeiten der Kommunikation von Mensch und Programm bestimmt, also der Software-Oberfläche (User Interface, UI). Diese ist in manchen Fällen grafisch gestützt (GUI), in anderen Fällen erfolgt die Bedienung über eine Befehlseingabe in der Konsole. Eine gemischte Bedienung ist ebenfalls nützlich, um verschiedene Nutzerkreise zu erreichen. Die Gestaltung von Oberflächen und die Nutzerführung in Menüstrukturen sind ein eigenes Aufgaben- und Forschungsfeld in der Softwareentwicklung. Gut an den Nutzer angepasste Lösungen sind das Ergebnis einer genauen Kenntnis der Zielgruppe und ihrer Gewohnheiten und Bedarfe, fügen sich also beispielsweise nahtlos in den archäologischen Forschungsprozess ein. Ein gutes Interface unterstützt das fehlerfreie und effiziente Arbeiten. So sind z.B. die Verständlichkeit der Menü-Einträge oder der Kommandos, aber auch die Aussagekraft von Fehlermeldungen Aspekte, die in der Rezension betrachtet werden sollten. Barrierefreiheit ist bislang ein unzureichend abgedecktes Kriterium, das aber ebenfalls die Effizienz und den möglichen Nutzerkreis adressiert.

> [MT] Bis hier hin bin ich gekommen; TODO an mich

* **Passt das User Interface zum Nutzerkreis?** Jeder Nutzerkreis, auch der des Rezensenten, wird bestimmte Erwartungen an die Präsentation der Anwendung haben. Beispielsweise ist es möglich, dass ein Benutzerkreis sich mit einer Kommandozeilenanwendung sehr gut zurechtfinden wird. Ein anderer Benutzerkreis wird mit dieser Form der Präsentation der Anwendung Probleme bei der Nutzung haben. Viele Softwarelösungen haben mehrere Nutzerschnittstellen. So können viele Webapps sowohl über einen Suchschlitz und Filterfunktionen auf einer Website, als auch über eine REST-Schnittstelle gesteuert werden. Auf diese Weisen werden zwei verschiedene Nutzergruppen angesprochen.

* **Ist die archäologische Nutzung vorgesehen?** Die Frage nach dem Nutzerkreis sollte auch speziell für die Archäologie gestellt werden: Entspricht der archäologische Einsatz den Anwendungsszenarien, die die Entwickler der Software vor Augen hatten? Das hat oft starken Einfluss auf das Nutzerinterface. Beispielsweise ist für von Archäologen genutzte CAD Software (z.B. [AutoCAD](https://www.autodesk.de/)) häufig für Architektur- oder Maschinenbauanwendungen konzipiert und konfrontiert Archäologen und Grabungstechniker mit unnötig überwältigendem Funktionsumfang.

* **Orientiert sich die Menüführung an bestimmten Vorbildern?** Software, die sich in Menüführung oder auch Tastenkürzeln an bekannter, in der Community gängiger Software orientiert, erlaubt oft eine schnellere Einarbeitung. Manche Werkzeuge verwenden deswegen z.B. bewusst Eingabemasken, die weit verbreiteten Tabellenkalkulationsprogrammen nachempfunden wurden.

* **Ist das Programm mehrsprachig bzw. in welchen Sprachen wird es angeboten?** Je nachdem, von wem das Programm eingesetzt werden soll, sollte das Programm in mehreren Sprachen angeboten werden. Üblicherweise wird man das Programm zumindest in einer englischen Fassung erwarten. Sollten verschiedene Sprachversionen getestet werden, so ist darauf zu achten, dass das Layout der Anwendung in den verschiedenen Sprachen weiterhin sichtbar ist. Beschriftungen von Buttons beispielsweise können sich in der Länge des Textes in verschiedenen Sprachen stark unterscheiden, so dass bei schlechter Programmierung der Anwendung ggf. Texte im Benutzerinterface abschnitten sind.

* **Sind die Fehlermeldungen für die Rezensentin gut verständlich?** Fehlermeldungen dienen zwei Funktionen. Die erste Funktion ist eine Fehlermeldung an den Benutzer, so dass dieser eine Aktion zur Behebung des Fehlers ergreifen kann. Diese Fehlermeldungen müssen für den Nutzer verständlich formuliert und auffallend in der Anwendung platziert werden. Versteht ein Benutzer den Inhalt der Fehlermeldung nicht, so hat die Fehlermeldung ihren Nutzen verfehlt. Die zweite Funktion einer Fehlermeldung ist ggf. ein Feedback an die Entwickler der Anwendung. Dieses muss die Fehlermeldung so kommunizieren und ggf. auch einen Fehlerreport zur Behebung des Fehlers an die Entwickler schicken. Unverständliche Fehlermeldungen wie Stack Traces (Hinweise auf die Stellen des Programmcodes an denen ein spezifischer Fehler auftrat) oder aus der Ausführungsumgebung übernommene Fehlermeldungen verfehlen oft ihre Wirkung.

#### Hilfefunktionen, Tutorials und Community

Neben Hilfefunktionen und Tutorials ist es von großer Bedeutung, ob die Software von einer *Community* getragen wird. Die Zahl der aktiven Nutzer und Entwickler eines Softwarewerkzeugs ist entscheidend dafür, ob man im Falle von Problemen Hilfe in Foren findet. Ist der Nutzerkreis sehr klein, findet der Wissenstransfer dagegen häufig im persönlichen Austausch statt und ist möglicherweise nicht dokumentiert. Enge Nutzernetzwerke können jedoch den großen Vorteil bieten, dass konkrete Fragen individuell von den Entwicklern aufgegriffen werden. Belege dafür können sich in öffentlichen Kommentarfunktionen von Webseiten der Entwickler und z.B. über Issues im Softwarerepositorium abzeichnen.

* **Gibt es ausreichend Tutorials für das Erlernen der Software?** Tutorials sind essentiell um zum einen die Benutzer der Software aber auch mögliche Entwickler der Software anzusprechen. Benutzer der Software erwarten üblicherweise ein einfach verständliches auf das Wesentliche heruntergebrochenes Anwendungsbeispiel in einem häufigen Nutzungskontext der Software um eine Idee für deren typische Verwendung zu bekommen. Tutorials sollte hier weder überfordern noch unterfordern und im besten Falle mit steigender Komplexität aufgebaut sein. Besonders gute Tutorials zeichnen sich dadurch aus, dass sie ein einfaches Anwendungsbeispiel durch das Tutorial hindurch mit immer weiteren komplexeren Funktionen der Software bearbeiten. Zum Beispiel kann zunächst das Laden von Geodaten aus einem Repository gezeigt werden, in einem zweiten Schritt eine Transformation der Daten z.B. in ein anderes Geokoordinatensystem und in einem dritten Schritt der Export der Daten in einem Datenformat. Für Entwickler ist entscheidend, dass ein Tutorial neben der Funktionalität der Software auch Anwendungsbeispiele für die ggf. vorhandenen Schnittstellen (APIs) bietet. Die Frage wie z.B. die Koordinatentransformation von einem anderen Programm aufrufbar ist und unter welchen Voraussetzungen sollte mit den entsprechenden API Aufrufen im Tutorial dokumentiert sein. Im Allgemeinen sollte überprüft werden, ob die Tutorials auf unterschiedliches Vorwissen der Communities eingehen und gegebenenfalls auch kenntlich machen, welches Grundwissen, welche Erfahrungen für das Bedienen der Software unabdingbar sind und wo sich diese - sofern nicht im Tutorial diskuiert - aneignen lassen. Schließlich ist es gute Praxis eine Hilfe in der Form von FAQ oder Troubleshooting Abschnitten in Tutorials einzufügen. Jede weitere Sprache in der ein Tutorial verfasst ist ist hier ein Plus.

> [AK] Hier wäre ein positives Beispiel ideal

> [TH] Ideal wäre hier ein Beispiel im archäologischen Kontext, würde AtlantGIS hier funktionieren?

> [HM] Achtung billige Eigenwerbung: http://youtube.com/c/GigaMeshTutorials

* **Gibt es Anwendungsbeispiele der Software, ggf. Beispieldatensets und eine Anleitung für diese, um ein Verständnis für die Funktionsweise zu entwickeln?** Dieser Punkt ist eng mit der Frage nach Tutorials verbunden, so greifen Tutorials oftmals auf Übungsdaten zurück. Die Übungsdaten von Forschungssoftware sollten sich dabei eng an der wissenschaftlichen Praxis orientieren und dennoch ohne spezifische Vorkenntnisse verständlich sein. Sie sollten frei zur Verfügung stehen und möglichst ohne Registrierung nutzbar sein. z.B. "Das R Paket bringt drei dokumentierte Testdatensätze aus der Literatur mit, die von den Entwicklern bereits im korrekten Eingabeformat vorformatiert wurden."

* **Wo finde ich mehr Informationen zu dieser Software? Hyperlinks und Referenzen?** Gibt es auf den Informationsseiten der Software oder in den Tutorialmaterialien Hinweise auf weitere Materialien zur Software? Wird auf Publikationen und Beiträge der Entwickler selbst wie auch Rezensionen hingewiesen?

* **Wird die Software von einer Community getragen? Ist diese möglicherweise ganz oder teilweise altertumswissenschaftlich ?** Beispiele für die Softwareentwicklung, die zunächst ganz aus einer altertumswissenschaftlichen Community heraus betrieben wurde und sich inzwischen fachlich erweitert hat, sind die [Pelagios Commons](https://pelagios.org/) und die WebApp [Recogito](https://recogito.pelagios.org/). Aktive Nutzergruppen mit einem Fokus auf archäologische Fragestellungen haben sich auch z.B. innerhalb der Communities großer Softwarepakete wie QGIS oder R entwickelt.

* **Haben ArchäologInnen bereits Best Practices für diese Software formuliert?**

>[AK] Hier wäre ich über konkrete Beispiele sehr froh und auch eine kurze Erläuterung, was Best Practices an dieser Stelle meint.

>[TH] Best Practices sind hier für mich konkrete Anwendungsfälle in denen die Software für die Lösung einer Aufgabe verwendet wurde. Das kann ein Paper sein welches das beschreibt, könnte auch ein Tutorial sein oder eine Handlungsanweisung einer Organisation die sich dafür zuständig fühlt.

>[HM] Ich würde die Frage umdrehen:

* **Gibt es archäologische Best Practcies oder Publikationen die auf die rezensierte Software verweisen?** Während Foren, Blogs und verwandte Angebote direkten und oft auch raschen Austausch mit Nutzern und ggf. Entwicklern bieten, ist die Einbindung von Empfehlungen von bestimmten Programmen ein weiteres Indiz für deren Verbreitung, Umfang und Verlässichlichkeit.

#### Dateningest, Interoperabilität und Schnittstellen

Für viele Nutzer spielen Datenformate eine große Rolle, da diese die Kompatibilität zu anderen Anwendungen bestimmt. Dies betrifft sowohl welche Datenformate gelesen als auch geschrieben werden können. Bei vielen Anwendungen werden die unterstützten Dateiformate allein durch den entsprechenden Menü-Eintrag (z.B. "speichern unter") klar und es ist im Rahmen einer Rezension hilfreich, dies zu erläutern. Auch die Form des Uploads von Daten und das Vorhandensein von Schnittstellen machen einen wesentlichen Aspekt des praktischen Einsatz aus und sollten in einer Rezension bedacht werden.

* **Welche Datenformate werden wie eingelesen?** Bei der Auswahl der Datenformate die von einer Software eingelesen werden können sollten, gibt es verschiedene Gesichtspunkte zu beachten:
  * Sind alle relevanten Datenformate für die Aufgabe, die die Software lösen soll, einlesbar? Diese Einschätzung sollte auf dem Arbeitsalltag eines typischen Anwenders beruhen.
  * Können Datenformate auch von gängigen Repositories eingelesen werden (z.B. Webservices, Git, Cloud Services)?
  * Werden offene Datenformate unterstützt?

* **Welche Datenformate werden ausgegeben?** Die Ausgabe von Daten nach der Bearbeitung sollte am Besten in Datenformaten erfolgen, die eine Weiterverarbeitung in anderen (auch Open Source) Softwarepaketen zulassen. Dies bedarf üblicherweise mindestens eines Formates, dessen Spezifikation frei verfügbar ist, sodass Open Source Software dafür entwickelt werden kann. Sollten nur Exporte in einem proprietärem, ggf. von der Software definierten Format möglich sein, muss es dafür schwerwiegende Gründe geben.

* **Wie können Daten eingeladen werden? Als Masseningest oder einzelne *Uploads*?** Für sehr viele Anwendunsgsszenarien, ist es entscheidend, ob eine Software einen einmal definierten Task massenweise auf eine Reihe von Dateien ausführen kann. Ein Beispiel kann hier eine Transformation von Bilddaten sein, die auf jedes Foto einer Ausgrabungskampagne ausgeführt werden soll. Um dies zu gewährleisten, muss die Software die Spezifikation entweder eines Ordners von Dateien oder einer Spezifikation von verschiedenen Dateipfaden unterstützen.

* **Gibt es eine API?** Diese Frage beschäftigt sich mit dem Vorhandensein einer Programmierschnittstelle (API). Neben der Bedienbarkeit durch einen Menschen, ist es wichtig, dass auch andere Software ggf. mit dem Softwarepaket interagieren und dadurch ihre Funktionalität anderer Software zur Verfügung gestellt werden kann. Eine API gewährleistet eine solche Integration und sollte möglichst offen, ggf. mittels eines Standards wie [OpenAPI](https://www.openapis.org), dokumentiert sein. Je sichtbarer eine API Dokumentation dem Nutzer gemacht wird, desto eher wird eine API verwendet. Ein konkretes Beispiel für eine API ist die REST-Schnittstelle von Wikidata, an die man automatisierte Abfragen stellen und Daten von Wikidata beziehen kann. Sie ist zudem umfangreich dokumentiert und bietet eine GUI zum Erlernen der Syntax an.

#### Konformität mit Regelungen zum Datenschutz, Fragen der Privacy und der Datensparsamkeit

Für den Einsatz in der universitären Forschung und der Lehre entscheidet die Frage nach dem Datenschutz vielfach darüber, ob die Software überhaupt genutzt werden darf. Eine Einschätzung der Regelungen, sofern sie sich nicht eindeutig auf die europäischen Rahmenrichtlinien beziehen, ist teilweise jedoch kaum möglich und Gegenstand von juristischen Diskussionen. Auch hier kann die Rezension aber bereits durch den Hinweis auf das Thema einen wichtigen Service für die Leser bringen. Dies gilt auch für Datensparsamkeit und das Hinterfragen von Registrierungsvorgängen, Cookies und ähnlichem.

* **Beachtet die Software die lokalen Gesetze in dem Land in dem sie eingesetzt werden soll? (Datenschutz, Kartendarstellungen etc.)?** Oft muss damit gerechnet werden, dass die Software in einer Vielzahl von Anwendungskontexten von Menschen in unterschiedlichen kulturellen Kontexten und in verschiedenen Ländern verwendet wird. Diese Länder können ggf. Gesetze erlassen haben, die der Ausführung/Installation der Software entgegenstehen. Ein Beispiel sind Kartendarstellungen, die z.B. Grenzkonflikte wie diese in Kashmir, die in Indien, Pakistan, China und den übrigen Staaten jeweils unterschiedlich auf der Karte angezeigt werden müssen. Ein weiteres Beispiel stellt der Datenschutz z.B. in der Europäischen Union dar.

* **Welche Daten speichert die Anwendung zu welchem Zweck wie lange? Werden Daten an Dritte übertragen?** In vielen Softwareanwendungen, oftmals Webdiensten, werden Daten der Benutzer zur Verbesserung der Anwendungen anonymisiert erfasst. Kommerzielle Anbieter von Software erfassen jedoch oft weitaus mehr Daten und verwenden diese z.B. zur Übertragung an Drittanbieter. Hier sollte sich ein Reviewer die Frage stellen, welche Daten erhoben werden, ob eine Zustimmung des Benutzers eingeholt wird, wie lange die Daten gespeichert werden und ob eine Anwendung ohne eine solche Einwilligung zur Übertragung von Nutzerdaten überhaupt bedienbar ist. Falls eine solche Datenerhebung stattfindet, wäre zu hinterfragen, ob der Zweck der Datenerfassung dem Reviewer als gerechtfertigt erscheint und ob diese Datenerhebung zur Verbesserung der Software beiträgt oder anderen Interessen dient.

Üblicherweise sollten solche Informationen in der Softwaredokumentation vorhanden sein und können auf dieser Grundlage bewertet werden. Eine weitergehende Analyse ob diese Informationen den Tatsachen entsprechen, liegt außerhalb des Blickpunkts einer Rezension von Forschungssoftware.

### Entwickler-Perspektive und Softwarequalität

Hier geht es nun um die Sicht aus Perspektive der Entwickler, die auch Nutzer sind, aber zusätzlich mit weiteren Interessen/Anwendungsszenarien auf die Software schauen. Die folgenden Fragen richten sich somit direkt auf den Programmcode und die Softwarearchitecḱtur. Eine Beurteilung derselben erfordert also den Programmcode herunterzuladen und in Stichproben durchzusehen. Das ist bei proprietärer Software meist nicht möglich.

Eine gute Zusammenfassung der Entwicklerperspektive auf die Softwarequalität bietet [@jung2004measuring](#jung2004measuring). Das Paper wendet die Vorgaben des ISO/IEC 9126 Standards an, der teilweise bereits in den vorherigen Abschnitten diskutiert wurden.

#### Dokumentation und Tests

> [HM] In den folgenden Fragen steckt oft die implizite Annahme, dass Open Source rezensiert wird. Einige Fragen sind daher für Closed Source nicht anwendbar, andere wiederrum schon. Das sollte vielleicht gruppiert und kenntlich gemacht werden.

Die Dokumentation von Software ist essentiell für ein umfassendes Verständnis eines Softwareentwicklers, welcher die Software ggf. erweitern möchte. Nur durch eine ausreichende Dokumentation wird eine ausreichend große Community von potenziellen Entwicklern angesprochen und zum Anderen ein umfassendes Verständnis der Intention der Software, der Ausgereiftheit und des aktuellen Entwicklungsstandes möglich.

Die Dokumentation erfolgt in verschiedenen Bestandteilen. Man unterscheidet die `Dokumentation des Quellcodes`, d.h. von Klassen oder einzelnen Methoden, die `Dokumentation des Buildprozesses`, d.h. wie die Software aus dem Quellcode zu erzeugen ist, eine `Entwicklerdokumentation` in Form von Beispielen der Benutzung der Software und der `Dokumentation dessen wie die Software getestet` wurde bzw. welche Testcases von der Software abgedeckt wurden.

Software Repositories wie [Github](https://github.com) oder [Gitlab](https://gitlab.com) bieten oft Vorlagen oder Best Practices um diese Anforderungen in jeglichen Programmiersprachen umsetzen zu können.

* **Ist eine Quellcodedokumentation vorhanden und ggf. eine HTML Variante davon verfügbar?** Best Practices sind hier beispielsweise Quellcode Dokumentationen mit [Doxygen](https://www.doxygen.nl/index.html), [JavaDoc](http://www.oracle.com/technetwork/java/javase/documentation/javadoc-137458.html), [JsDoc](https://jsdoc.app) oder auch das für Python beliebte [ReadTheDocs](https://readthedocs.org). Alle Dokumentationen erzeugen eine HTML Repräsentation der Quellcodedokumentation, welche im Falle von ReadTheDocs direkt auch im Internet gehostet wird. Im Falle von anderen Dokumenationstools ist es gute Praxis diese beispielsweise als Github Page mit dem Repository bereitzustellen.

* **Ist der Buildprozess dokumentiert und ggf. mittels Buildingscripts automatisiert?** Ebenso wichtig wie ein grundlegendes Verständnis des Aufbaus des Programms ist die Bauanleitung der Software. Entsprechend ist zu fragen, ob dokumentiert ist, wie die Software erstellt wurde und funktioniert die Erstellung unter dem angegebenen Weg. Während in der Vergangenheit mit Anleitungen in *README Files* oder ähnlichen natürlichsprachlichen Beschreibungen gearbeitet wurde, hat es sich seit vielen Jahren zu einem Standard etabliert, maschinenlesbare Bauanleitungen (*Buildscripts*) für Software bereitzustellen. Dies kann als gute Praxis angesehen werden, denn zum einen ist eindeutig und maschinenlesbar beschrieben, wie die Software erstellt wurde, zum anderen ist der Aufruf des Buildprozess so meist durch Ausführung eines einzigen Skriptes möglich und somit für den Entwickler einfach gehalten. Ebenfalls dokumentieren die Buildscripts die Abhängigkeiten der Software in Bezug auf verwendete *Libraries*. Beispiele für solche Skripts finden sich z.B. in [Apache Maven](https://maven.apache.org) oder [Gradle](https://gradle.org)

* **Ist die Dokumentation aktuell, wird gepflegt und deckt alle Funktionen des Programms ab?** Eine Bewertung der Aktualität der Dokumentation ist oft relativ einfach vorzunehmen, wenn Werkzeuge verwendet werden, die dem aktuellen Stand in der Softwareentwicklung entsprechen. Diese beinhalten meist einen Zeitstempel mit dem Datum der Erstellung der Dokumentation. Dieses kann entsprechend mit dem Datum des aktuellen Release verglichen werden. Gute Praxis ist es hier, die Generierung der Dokumentation und das Hosten mit in den Entwicklungsprozess über *Continuous Integration* zu integrieren. Ein Beispiel hierfür bietet das [Github Repository des SPARQLing Unicorn QGIS Plugins](https://github.com/sparqlunicorn/sparqlunicornGoesGIS). Ein *Continuous Integration* Prozess erstellt die Dokumentation bei jeder Veränderung des Quellcodes durch die Entwickler neu und publiziert diese auf der [Github Page des Repositories](https://sparqlunicorn.github.io/sparqlunicornGoesGIS/).

> ich glaube du solltest davor CI mal vorstellen...
> [AK] Ist diese Anregung bereits aufgenommen und verarbeitet?

* **Gibt es eine Entwicklerdokumentation, sodass die Software leichter verstanden werden und ggf. erweitert werden kann?** Essentiell für einen Entwickler, der sich mit der Erweiterung oder Nutzung einer Software befasst, ist es, ihm einen möglichst einfachen Einstieg zu bieten. Dafür ist eine aussagekräftige *README* Datei notwendig, die kurz die Verwendung des Programmes mit den Standardeinstellungen demonstriert. Ein Beispiel dafür ist  [Bibtex_JS](https://github.com/pcooksey/bibtex-js). Idealerweise werden noch Beispieldaten für ein besseres Verständnis des Programmablaufs beigelegt und ggf. weitere häufig verwendete Anwendungsfälle der Software in Beispielen vorgestellt. Auch dies kann das genannte Beispiel demonstrieren [Bibtex_JS Beispiele](https://github.com/pcooksey/bibtex-js/tree/master/test)). Abhängig von der Komplexität der Software kann es sinnvoll sein, ein ggf. auch von einer Nutzercommunity gepflegtes Wiki bereitzustellen, um fortgeschrittene Optionen zu erläutern. (siehe [Bibtex_JS Wiki](https://github.com/pcooksey/bibtex-js/wiki))

* **Hat der Quellcode Tests, die die Kernfunktionen des Programms testen und diese für andere Entwickler aufzeigen?** Jede Software kann durch Tests auf ihre antizipierte Funktionalität hin überprüft werden. Tests erfüllen hierbei zwei grundlegende Funktionen. Zum einen zeigen sie auf welche Anwendungsfälle hin die Entwickler die Software antizipiert haben und geben diese Information in Form von Tests weiter. Zum anderen geben Tests Auskunft darüber, welche Funktionen im jeweiligen Programm als stabil, fehleranfällig oder ggf. noch optimierungsbedürftig gelten können. Kombiniert mit einem *Continuous Integration* Prozess können Testauswertungen mit jeder Änderung am Quellcode durch die Entwickler erstellt werden. Als *Continuous Integration* Prozess bezeichnet man eine Reihe von Aufgaben welche mit dem Quellcode in einem Repository durchgeführt wird. Jede der Aufgaben erzeugt ein Ergebnis welches einen Mehrwert für das Projekt bietet. Beispielsweise kann ein Releasefile (.exe), eine Quellcode Dokumentation oder auch wie in diesem Fall ein Testreport mit einem *Continuous Integration* Prozess erzeugt werden. Ein solcher Prozess wird üblicherweise nach jeder Änderung des Quellcodes erneut ausgeführt um die Ergebnisse der Aufgaben immer so aktuell wie möglich zu halten.

* **Wird es dem Benutzer einfach gemacht, die Software zu testen? Gibt es eine Virtuelle Maschine, einen Dockercontainer, einen Installer, andere Formen der Installierbarkeit ohne viel vorheriges Fachwissen?** Entwickler sind meist in der Lage, eine Software zu bauen und auszuführen. Allerdings will dieser Zeiteinsatz wohlbedacht sein. Tatsächlich werden Softwares, welche leicht installierbar und vor allem testbar sind, sowohl von Entwicklern die einen schnellen Einblick in die Funktionalität bekommen wollen, als auch von anderen Benutzern einen besseren Anklang finden als andere. Es liegt in der Natur der Sache, dass es hierbei, je nach Art der Anwendung, unterschiedliche Ausführungsformen gibt. Eine Webanwendung kann als Beispiel im Internet gehostet sein und dem Benutzer einen Testaccount zur Verfügung stellen (z.B. [CWRCWriter](https://cwrc.ca)), eine Desktop Anwendung kann bereits eine installierebare Anwendung oder ein Installerpaket mitliefern. Serveranwendungen können für einen Test als Images von virtuellen Maschinen oder - in letzter Zeit üblicher - als Dockerimages in Portalen wie [Dockerhub](https://hub.docker.com) für ein einfaches Testen hinterlegt werden.

>[AK] Das Thema Installation hatten wir weiter oben. In diesem Abschnitt soll es aber um Entwickler gehen. Daher bitte überarbeiten. Zudem insgesamt sehr umgangssprachlich formuliert
>[TH] Du hast Recht: Wir hatten das Thema Installation weiter oben. Mir geht es hier aber darum ob ich als Entwickler eine Software erweitern will. Was ich dafür machen muss ist mir sie erst einmal anzuschauen. Das geht auch für mich als Entwickler am besten wenn ich sie einfach bei mir installieren kann. Wenn das allerdings in stundenlange Recherchearbeit ausartet, dann schaue ich eher nach Alternativen für die Erweiterung einer Software als mich mit der aktuellen Software abzumühen.

* **Sind die Entwickler der Software aktiv und sind sie gut erreichbar? Wird die Software regelmäßig mit Updates versorgt? Gibt es eine Roadmap für die weitere Entwicklung? Gibt es *Contribution Guidelines*?** Oft stellen sich bei der Bedienung der Software heraus, dass Funktionalitäten fehlen oder Fehler im Programm vorhanden sind. In manchen Fällen machen diese Probleme die Benutzung der Software für bestimmte Anwendungsfälle unmöglich oder verschlechtern die Ergebnisse, die mit der Software erreicht werden können signifikant. Dies kann auch der Fall sein, wenn die Software möglicherweise in allen anderen Belangen den Erwartungen entspricht. In solchen Fällen ist die Verfügbarkeit der Entwickler und deren Feedback auf Supportanfragen ein entscheidendes Kriterium.

Zunächst sollten die Entwickler klar kommunizieren wie und wo Fehlerreports eingereicht werden können, und am Besten auch welche Inhalte diese für eine bestmögliche Verarbeitung der Meldungen enthalten sollten. Einen Eindruck davon, ob die Entwickler einen aktiven Austausch pflegen, kann man beispielsweise bei der Durchsicht von Issues in dem Repositorium der Software auf GitHub oder im GitLab gewinnen. Haben die Entwickler Anfragen hier zeitnah und zufriedenstellend beantwortet? Wie ist das Verhältnis von offenen Issues zu bereits geschlossenen Issues und wie lange hat es gebraucht bis eine Änderung eingepflegt wurde?

Zudem können Entwickler proaktiv in einer Roadmap kommunizieren, welche Änderungen in nächster Zeit in das Programm eingepflegt werden sollen und welche Issues für das nächste Release angegangen werden.
Schließlich ist es für Entwickler oft interessant die Software selbst mitzugestalten und einen Beitrag zu ihrer Verbesserung zu geben. Dafür sollte von den Entwicklern der Software selbst als Best Practice eine *Contribution Guideline* erstellt werden (siehe z.B. [hier](https://projectacrn.github.io/latest/developer-guides/contribute_guidelines.html)). Sie enthält Angaben dazu unter welchen Umständen und wie Änderungen an der Software von Dritten angenommen und integriert werden.

#### Qualität der Implementierung

* **Entspricht die Implementierung dem Stand der Technik?** Die Frage, ob die Entwicklung dem Stand der Technik entspricht, muss meist anwendungsbezogen beantwortet werden und verlangt ein technisches Verständnis der Abläufe innerhalb der Anwendung. Allerdings können einige Aspekte durchaus auch ohne Fachwissen bewertet werden. Hierzu gehören unter anderem folgende Aspekte:
  * Ist die Anwendung auf vielen verschiedenen Endgeräten bedienbar? (z.B. Handy, verschiedene Betriebssysteme usw.)
  * Wie ist die Optik der Anwendung? Verwendet sie Elemente vergleichbarer Anwendungen (z.B. Elemente der aktuellen Android Version, verwendet die Webanwendung Adobe Flash, Java Applets oder ähnlich veraltete Technologien?)
  * Zeichnen automatische Testsysteme (etwa auf Github) unbehobene Sicherheitslücken in der Software aus?

* **Ist die Implementierung performant? Für Webapplikationen und Plugins ist zu überprüfen, ob sie responsiv sind und über die verschiedenen Browser hinweg performant sind.** Die Performanz einer Anwendung ist je nach Anwendungstyp von mehr oder weniger Wichtigkeit. Ein Reviewer sollte hier bewerten, ob die Software ihre Aufgabe in der vom Reviewer angemessenen Zeit erfüllt. Gegebenenfalls kann der Reviewer die Ausführungszeit weiterer verwandte Softwareimplementierungen mit der von ihm zu Testenden vergleichen. Ein Reviewer wird wahrscheinlich nicht in der Lage sein die Gründe für eine mangelnde Performanz der Software zu erkennen.

> [AK] Frage: Ist die Frage der Performanz, so wie sie hier gestellt wird, nicht 1.) "usability" und 2.) auch ohen Entwicklerwissen zu testen?
> [TH] Du hast Recht, dann könnten wir das hier streichen. Hier wäre das von Relevanz wenn der Entwickler die Gründe herausfinden könnte

* **Robustheit der Software** Die Robustheit einer Software ist ein wünschenswerter Aspekt, der im Wesentlichen voraussetzt, dass die Software Zwischenstände der Aufgaben, die sie ausführt, regelmäßig sichert, um bei einem unvorhergesehenen Abbruch wieder an dem Punkt anknüpfen zu können, an dem sie vor diesem Ereignis gearbeitet hat. Ein Fehlen dieser Funktion kann oft z.B. bei einem Stromausfall den Verlust von Einstellungen, Daten und/oder die Neuinitialisierung einer Berechnung bedeuten. Ein Beispiel für eine solche Robustheit ist das regelmäßige automatisierte Zwischenspeichern in einem Textverarbeitungsprogramm. Das Textdokument ist somit im Falle eines Absturzes der Software wiederherstellbar. Abhängig vom Anwendungsfall kann es auch vorteilhaft sein, dass die Software eine Historie der Benutzeränderungen vorhält und diese ebenfalls wiederherstellen kann. Dies kann die Spracheinstellungen oder auch die Anpassung von Maßeinheiten, Vorgaben zum Speicherort und ähnliches sein.

> [AK] Sind wir hier noch im spezifischen Entwicklerbereich ? Es klingt für mich nach Usability, denn wir argumentieren hier über das Nutzererlebnis, nicht über technische Kerndaten. Für mich wäre die Frage, kann man nicht kurz erläutern, wie man einen Absturz herbeiführt, um die Robustheit zu testen? Wenn ja, was wäre das richtige Vorgehen?

> [TH] Im Zweifelsfall den Strom vom PC trennen während die Anwendung läuft und anschließend nach einem Neustart des PCs schauen was die Anwendung zwischengespeichert hat, bzw. wie man wieder in den Arbeitsworkflow einsteigen kann

> [HM] Robustheit ist aus meiner Sicht eher, dass die Software nicht abstürzt, nicht in einer Endlosschleife hängen bleibt und keine Speicherleaks hat, die ggf. den ganzen Computer zu Fall bringen. Robustheit gegen Stromausfall ist eher Sache der Versorgung bzw. Aufgabe einer USV.

* **Wird *Continuous Integration* zur Absicherung der Implementierungsqualität verwendet?** Für einen Entwickler ist nicht nur das Vorhandensein und die Dokumentation des Quellcodes entscheidend, sondern er wird meistens auch einen Hinweis zur Funktionalität und Kompilierbarkeit des Quellcodes erwarten. *Continuous Integration* kann, wie schon in den vorherigen Abschnitten angesprochen, ein solches Qualitätsmerkmal darstellen. Der *Continuous Integration* Prozess überprüft die Kompilierbarkeit der Software nach jeder Änderung und kann diese am Repository mit einer Statusanzeige sichtbar machen. Es ist ein Zeichen von gut gewartetem Quellcode, wenn dieser in der aktuell vorliegenden Version und ggf. in der aktuellen Entwicklerversion kompiliert.

>[AK] Besser, wenn alles rund um CI aufeinander folgt?

> [HM] Wieder eine Frage, die nur für Open Source relevant ist.

## Tabellen

**Software-Eckdatentabelle**

- Name: Der Name der Software, z.B. "QGIS"
- Kurzbeschreibung: Was die Software leistet, z.B. "Umfangreiches graphisches Werkzeug zur Raumdatenverarbeitung"
- Rezensierte Version: Die Softwareversion, die für das Review genutzt wurde, z.B. "3.10.10 LTR"
- Plattform: Betriebssysteme, auf denen die Software genutzt werden kann, z.B. "Windows, macOS, Linux, BSD, Android"
- Website: URL unter der weitere Informationen abgerufen werden können, z.B. "https://qgis.org"
- Lizenzierung: Unter welcher Softwarelizenz wurde die Software veröffentlicht, z.B. "Open Source mit GNU General Public License (GPL)"

## Anmerkungen

<a name="#authornote">*</a>: Autorenangaben in alphabetischer Reihenfolge.

## Bibliographie
