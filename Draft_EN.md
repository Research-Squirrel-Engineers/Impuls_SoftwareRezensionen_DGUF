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
    bio: "Timo Homburg studied computer science with a focus on computational linguistics (assyrology), semantic web and sinology. In recent years, he has worked in the field of GIS applications in geoinformatics. His doctoral thesis deals with better integration of geodata into a Semantic Web environment. His current research project deals with the design and establishment of digital standards in the field of assyrology and a best practice for documentation of excavations with cuneiform texts - an extension of his publications on 'Cuneiform Script in the Digital Humanities'."
  -
    name: Anne Klammt
    affiliation: Deutsches Forum für Kunstgeschichte Paris
    orcid: 0000-0003-3697-9241
    bio: "Archaeologist Anne Klammt completed her doctorate on a landscape archaeology topic and has been responsible for the further development of Digital Art History at the German Forum for Art History Paris as Head of Research since 2020."
  -
    name: Hubert Mara
    affiliation: mainzed & Hochschule Mainz
    orcid: 0000-0002-2004-4153
    bio: "Hubert Mara studied computer science at the Vienna University of Technology. There he already worked on digital methods in archaeology for ceramic analysis. He was subsequently a Marie Curie Fellow at the University of Florence within the framework of the *Cultural Heritage Informatics Research Oriented Network* (CHIRON). He completed his doctorate at the University of Heidelberg in the *Interdisciplinary Centre for Scientific Computing* (IWR). There he developed the [*GigaMesh Software Framework*](https://gigamesh.eu) and installed the *Forensic Computational Geometry Laboratory* (FCGL). Since June 2020, he has been the managing director of mainzed and is a researcher at the Institute for Spatial Information and Measurement Technology at Mainz University of Applied Sciences."
  -  
    name: Clemens Schmid
    affiliation: Max Planck Institute for the Science of Human History
    orcid: 0000-0003-3448-5715
    bio: "Clemens Schmid studied prehistoric, historical and scientific archaeology as well as computer science in Tübingen and Kiel. After graduating, he worked with computational data analysis in various archaeological research projects at the University of Kiel, the Roman-Germanic Central Museum in Mainz and the University of Bern. Now he is employed for a PhD project on quantitative estimation of past human mobility with ancient genetic and historical-linguistic data at the Department of Archaeogenetics of the Max Planck Institute for the Science of Human History in Jena."
  -
    name: Sophie Charlotte Schmidt
    affiliation: Deutsches Archäologisches Institut
    orcid: 0000-0003-4696-2101
    bio: "Sophie C. Schmidt studied Classical Studies and Prehistoric Archaeology at the Free University of Berlin. She then worked as a research assistant in the field of archaeoinformatics at the universities of Cologne and Bonn, and is currently employed in the NFDI4Objects consortium project at the German Archaeological Institute."    
  -
    name: Florian Thiery
    affiliation: Römisch-Germanisches Zentralmuseum – Leibniz-Forschungsinstitut für Archäologie
    orcid: 0000-0002-3246-3531
    bio: "Florian Thiery studied geodesy and is a Research Software Engineer (RSE) in the *Scientific IT, Digital Platforms and Tools* department at the Römisch-Germanisches Zentralmuseum in Mainz. He is the initiator of the *Research Squirrel Engineers*, a network for RSEs in the Digital Humanities that pursues community projects with a focus on free and open data, as well as Linked Open Data. As part of a fellowship of the *Wikimeda Fellow-Programm Freies Wissen*, he is working on the modelling of Irish ᚑᚌᚆᚐᚋ (Ogham) stones and their publication in the Wikimedia universe."    
  -
    name: Martina Trognitz
    affiliation: Austrian Centre for Digital Humanities and Cultural Heritage, ÖAW Wien
    orcid: 0000-0003-0485-6861
    bio: "Martina Trognitz studied computational linguistics and classical archaeology in Heidelberg. From 2012 to 2017, she worked in the IANUS project at the German Archaeological Institute. Since 2017, she has been in charge of the digital archive ARCHE of the ACDH-CH at the Austrian Academy of Sciences. She is working on a PhD project on the machine analysis of multi-sided Aegean seals of the Bronze Age."


bibliography: literatur.bib
csl: apa-6th-edition.csl
keywords:
  - Archäologie
  - Archäoinformatik
  - Handreichung
  - Softwarebewertung
  - Forschungssoftware
  - Rezension
keywords_en:
  - archaeology
  - manual
  - guideline
  - software review
  - research software
  - review

---

{% include {{ page.abstract_de }} %}

{% include {{ page.abstract_en }} %}

## Objectives of this Contribution

The aim of this paper is to stimulate discussion about the content and objectives of research software reviews as well as digital tools used for research in archaeology and ancient studies. Our reflections were inspired by a round-table discussion led by Kai-Christian Bruhn, Sophie Charlotte Schmidt and Frank Siegmund at the plenary session of the 9th Workshop of the German Section of the CAA 2019 in Wilhelmshaven. On the occasion of the introduction of the new category „Archäoinformatik“ as a space for such kind of reviews in the *Archäologischen Informationen*, we have now written down our thoughts. The few relevant software reviews available at the time of our discussion (especially in the journal *Internet Archaeology*) do not seem to be consistent and comprehensive enough to the authors.

In this recommendation, we present criteria and principles that make up good research software and may be relevant for its evaluation. We also recommend a procedure for an actual software review, and present a list of questions to help with the critical evaluation of software.

The assessment of a publication is a traditional part of academic discourse. Accordingly, there is an unspoken understanding of what a review should include. In addition, concrete measures can be taken to ensure quality, such as instructions on how to write reviews or - as practised by the editorial staff of *Archäologischen Informationen* - the peer reviews are themselves assessed.

What constitutes a good review of software intended for use in archaeological research? Should only the algorithms executed by the software which directly contribute to the solution of a scientific problem be addressed? Or do aspects of usability, sustainability and interoperability also need to be considered? What role do technical and legal aspects play in the discussion, for example, source code documentation or licensing? And finally: does the software itself perhaps represent a scientific contribution? Which achievements of the software developers should be considered in a review? What standards, alluded to in the recommendations of the German Research Foundation (*Deutschen Forschungsgemeinschaft*, DFG), should good research software meet? And last but not least: who should, or is able to, adequately review a piece of software?

The central question of a review, namely the scientific value of the subject to be reviewed, is only touched upon with these questions. In this respect, the requirements of a software review are the same as those of a scholarly text review. Furthermore, due to the variety and diversity of software, not all of the criteria collected here will be relevant in each and every review. It is up to the reviewer to select relevant aspects and to set priorities.

This contribution is intended as a stimulus to discussion. Contributions for discussion and suggestions are explicitly welcome. For this purpose, the authors can be contacted via the given addresses or by posting comments directly on GitHub ([https://github.com/Research-Squirrel-Engineers/Impuls_SoftwareRezensionen_DGUF/](https://github.com/Research-Squirrel-Engineers/Impuls_SoftwareRezensionen_DGUF/) [23.10.2020]).

## Research software

The criteria for the assessment of software presented below are primarily aimed at reviewing research software. By research software, we mean software that has been developed with research activities as a primary area of application, i.e. generating, processing or analysing research data ([@hettrick_2014_14809](#hettrick_2014_14809)). Examples include programmes that serve to calibrate and convert measured values, visualise geospatial data, annotate texts and objects or provide and link subject-relevant vocabularies.

Research software is always part of the research process, and has to be comprehensible and - as far as possible - reproducible in all its aspects.

Research software is different from software that is required for the use of specific hardware equipment, such as for surveying, photographic documentation or the analysis of surfaces and substance components. The latter is often proprietary and is distributed together with the hardware. Although it is used in the research process, it does not correspond to our understanding of research software. Digital tools that play a significant role in practical work but have no actual part in the collection, processing and analysis of data are also not research software as we understand it. These include, for example, word processing or spreadsheet programmes. However, the criteria presented can be used to assess any type of software.


Research software is particularly prone to issues of sustainable development and maintenance. One major reason is the lack of long-term funding for staff and infrastructure to produce sustainable software ([@anzt_environment_2020, 2](#anzt_environment_2020)). An overview of needs, challenges and possible solutions for sustainable research software development was compiled in 2019 in a workshop at the [deRSE conference in Potsdam](https://de-rse.org/de/conf2019/index.html)(https://de-rse.org/de/conf2019/index.html [23.10.2020]) ([@bach_dersews19](#bach_dersews19)).

### Research software as a scholarly achievement

In modern research, it is unthinkable to work without digital tools. This also applies to historical, classical and ancient studies. With the rise of the digital humanities, software is increasingly becoming an important part of the research process and substantially affects it, both implicitly and explicitly (for archaeology, see e.g. ([@schmidt_marwick_2020](#schmidt_marwick_2020)). Only by disclosing the underlying source code can the processes performed by the software be properly evaluated.

Despite the vital role that research software plays in many projects, the achievements of those  developing and programming it are often not sufficiently recognised academically ([@hettrick_2017](#hettrick_2017); [@katerbow_2018](#katerbow_2018); [@scheliga_pampel_2017](#scheliga_pampel_2017)). This does not do justice to the fact that scientific expertise and, moreover, advanced technical competence are required to develop research software. Practice and knowledge are explicitly manifested and developed by turning it into code. We argue that these accomplishments need to be acknowledged and made visible, especially as scientific breakthroughs are often only made possible by software ([@helmholtz_web](#helmholtz_web); [@katerbow_2018](#katerbow_2018); [@scheliga_pampel_2017](#scheliga_pampel_2017)).

As an important first step towards making such achievements visible, the job title of "Research Software Engineer" (RSE, RSEng) was coined in 2012 ([@baxter_2012](#baxter_2012); [@hettrick_2017](#hettrick_2017)). At the same time, an active, interdisciplinary community has formed to develop recommendations for dealing with research software ([@anzt_environment_2020](#anzt_environment_2020)). National [RSE sections](https://sorse.github.io/contact/chapters/) (https://sorse.github.io/contact/chapters/ [23.10.2020 9]) - in Germany for example *"de-RSE e.V. "* - organise cross-disciplinary RSE conferences such as SORSE (https://sorse.github.io [23.10.2020]). As part of the development of a *Nationale Forschungsdateninfrastruktur (NFDI, Eng. National Research Data Infrastructure)*, research software and RSEs play a major role in the further development of the research landscape and the portfolios of research institutions in Germany ([@goedicke_nfdixcs20](#goedicke_nfdixcs20); [@loeffler_nfdi4rse20](#loeffler_nfdi4rse20)).

One of the demands of the de-RSE e.V. is that research software shall become explicitly visible by means of suitable publication modalities. A publication increases discoverability and thus avoids redundant redevelopments ([@anzt_environment_2020, 10](#anzt_environment_2020)). At the same time, the clear authorship that goes hand in hand with a publication is of great importance in linking the task of developing software with the responsible people. This is a critical part of establishing an academic career, but up to now only classic text publications have been counted. In future, data publications, software development ([@druskat2017citation](#druskat2017citation)) and annotations — as well as their citations (https://citation-file-format.github.io [17.12.2020]) — should be criteria for the assessment of scientific performance ([NFDI4Culture](https://nfdi4culture.de), https://nfdi4culture.de [23.10.2020], [RSE4NFDI](https://www.rse4nfdi.de/de/index.html), (https://www.rse4nfdi.de/de/index.html [23.10.2020], [NFDI4Objects](https://www.nfdi4objects.net), https://www.nfdi4objects.net [23.10.2020]). Some technical challenges have to be overcome though, because in contrast to most text publications software is never finally completed, often builds upon existing modules and is sometimes maintained by changing teams over decades ([@katz_software_2016](#katz_software_2016)).

Openly available software can be reviewed, just as it is the established practice of archaeology and ancient studies research. It can then be presented to a wider audience in a review. Through a dedicated review of software analogous to reviews of scholarly publications, the scientific achievements, responsibilities and participation of the authors of research software are made visible and recognised by means of familiar formats.

### Good research software

In order to be able to establish criteria for reviewing and evaluating research software, the first question is how to determine its quality and by which standards it should be assessed. This includes a multitude of specialist and technical aspects, which will be examined below. However, software, like any other tool, must first be evaluated in terms of its general suitability for sustainable and ethical scientific work.

With its "Leitlinien zur Sicherung guter wissenschaftlicher Praxis" (*Eng. Guidelines for Safeguarding Good Scientific Practice*) ([@deutsche_forschungsgemeinschaft_2019](#deutsche_forschungsgemeinschaft_2019)), the DFG formulated a set of guidelines for good scientific research practice. The guidelines correspond to an international consensus and well established principles. The requirements include, for example, adherence to and definition of standards and methods, comprehensible documentation of how results were achieved, public accessibility of results and archiving of the necessary materials to replicate the results.

Some of the criteria that are explicitly and implicitly mentioned in the DFG guidelines are described in more detail below, including the FAIR Data Principles mentioned in the comment for guideline 13, and the principles of Open Science and the CARE principles in guidelines 2 and 10. Further guidance on the implementation of the DFG guidelines in relation to research software can be found at ([@research_data_info_dfg](#research_data_info_dfg)).

#### FAIR Data Principles

The *FAIR Data Principles* ([@wilkinson_2016](#wilkinson_2016)) were published in 2016 and primarily target research data and their metadata. The principles require that data and metadata must be findable, accessible, interoperable and reusable. There is a particular focus on machine readability. The principles can also be applied to research software and its metadata ([@goedicke_nfdixcs20](#goedicke_nfdixcs20); [@lamprecht_towards_2019](#lamprecht_towards_2019)) and thus provide criteria for assessing the quality of software publication, code documentation and programming standards.

Software becomes findable by storing it, together with its associated metadata, in dedicated software repositories (e.g. GitHub). Integration into scientific research infrastructures increases the findability, as they explicitly work on the development, maintenance and application of controlled indices and metadata standards ([@anzt_environment_2020, 10](#anzt_environment_2020); [@lamprecht_towards_2019](#lamprecht_towards_2019)).

The citation of research software is enabled through persistent identifiers (e.g. URIs) assigned by repositories and crediting the authors. Since software, unlike conventional publications, is constantly being developed and evolves, it should be saved in different versions that can be individually cited ([@research_data_info_dfg](#research_data_info_dfg)).

Public repositories and persistent identifiers also ensure a minimum level of accessibility. Ideally, data and metadata should also be machine-accessible via an open and standardised communication protocol ([@lamprecht_towards_2019](#lamprecht_towards_2019)). Other aspects that facilitate accessibility are availability for different operating systems and technical requirements that can be met by current devices in use. Furthermore, a comprehensible user manual improves accessibility.

Interoperability of software can refer to the compatibility of input and output formats with other programmes in a work process (horizontal dimension), but also to the cooperation of the components used in the software itself (vertical dimension) ([@lamprecht_towards_2019, 46f](#lamprecht_towards_2019)). The use of standards enables both, as it allows software components to work together even across different operating systems.

The reusability of software depends on several components. Metadata and comprehensive documentation of the software should enable others to reproduce results, process their own data and use it for modified use cases. Additionally, a suitable licence that also takes into account the software dependencies provides information about which rules apply to the use and further development of the code ([@lamprecht_towards_2019, 48-49](#lamprecht_towards_2019)).

#### Open Science

Open Science refers to a scientific practice that aims at a transparent, reproducible and collaborative research process ([@bezjak_openscience_2018, 'Open Concepts and Principles'](#bezjak_openscience_2018)). Open Science consists of several principles that concern different stages in the research process. For example, Open Science does not only call for the results to be openly available (Open Access), but also for opening the underlying data (Open Data), the methods employed (Open Methodology) and the research software used (Open Source). For research software to be open, its source code must at least be accessible and provided with a licence that allows further development ([@bezjak_openscience_2018, 'Open Research Software and Open Source'](#bezjak_openscience_2018)).

The demand for the disclosure of source code (Open Source) also complies with the idea of reusability. The ideal of Open Source is expanded by the demand for making the code freely available for use (free source) ([@stallman2001free](#stallman2001free)). This is referred to as FOSS (Free/Libre Open Source Software) and is advocated in Germany by, for example, application-oriented scientists and developers from the field of geoinformatics ([FOSSGIS e.V.](https://www.fossgis.de), https://www.fossgis.de [23.10.2020]) as well as by research software engineers in the [*de-RSE e.V.*](https://de-rse.org/de/association.html) (https://de-rse.org/de/association.html [23.10.2020]; ([@anzt_environment_2020](#anzt_environment_2020)).

The DFG guidelines touch upon the opening of software source code in the context of quality assurance ([@deutsche_forschungsgemeinschaft_2019, 14-15](#deutsche_forschungsgemeinschaft_2019)) and the creation of public access to research results ([@deutsche_forschungsgemeinschaft_2019, 19](#deutsche_forschungsgemeinschaft_2019)).

#### CARE Principles and Ethos

In DFG guidelines 2 and 10, ethical aspects in the research process are addressed. We believe that these should also be taken into account in the area of research software.

Privileges and inequalities in classical and ancient studies research are unconsciously perpetuated in research software as well. Expensive, proprietary software disadvantages researchers who have to make do with less funding, as this denies them access to contemporary analytical methods. As a further consequence, access to highly rated journals may be impeded and student training in these methods may stagnate, further accentuating existing imbalances. Language barriers also contribute to disparities: for example, if international teams use a database that is not also available in the local language, Indigenous researchers may be prevented from independently analysing and evaluating the data, as well as from pursuing further training.

In the field of archaeology, where research is often conducted on foreign cultures and cultural legacies, locals and Indigenous people should be given the opportunity to have a say in or participate in its investigation. To meet this ideal, suitable orientation is provided by the CARE Principles ([https://www.gida-global.org/care](https://www.gida-global.org/care) [23.10.2020]). They were jointly introduced by the [Global Indigenous Data Alliance (GIDA)](https://www.gida-global.org) (https://www.gida-global.org [23.10.2020]) and the [Research Data Alliance (RDA)](https://www.rd-alliance.org) (https://www.rd-alliance.org [23.10.2020]) in 2018 on the basis of the [UN Declaration on the Rights of Indigenous Peoples (UNDRIP)](https://www.un.org/development/desa/indigenouspeoples/declaration-on-the-rights-of-indigenous-peoples.html) (https://www.un.org/development/desa/indigenouspeoples/declaration-on-the-rights-of-indigenous-peoples.html [23.10.2020]). Like the FAIR Data Principles, the CARE Principles focus explicitly on research data. However, in our opinion, the four pillars of Collective Benefit, Authority to Control, Responsibility and Ethics are equally relevant to research software.

## A possible approach to reviewing archaeological research software

The review of archaeological research software requires sifting through documentation and publications as well as actually testing the software itself. We suggest that a software review, much like a conventional review of a scientific publication, should first introduce the software by presenting the key data. This should be followed by outlining the context and critically assessing the software.

The key data, which can be presented in tabular form, include information on the software version under review, the developers and the licence. This allows, for example, a quick assessment of whether the reviewed software is compatible with one's own technical environment. A suggestion for the contents of such a table can be found at the end of this article.

For context, a classification in the archaeological research field and information on the possible connection with research projects, working groups or institutions should be provided. The background of the reviewer is also necessary; it should be described, because a realistic and transparent assessment of one's own competences and interests regarding the use of the software provide valuable information for a heterogeneous readership. Was the review written purely from a user's point of view or also from a developer's perspective? A description of the test environment used, i.e. the computer used to test the software, can also be important, such as information on the operating system, RAM, processor, graphic card or bandwidth.

A catalogue of questions for the critical assessment of research software from different perspectives, which is divided into three sections follows hereafter. In our opinion, the questions from the first section "Use in archaeology and scientific purpose" should be addressed in every review. We also consider it very important to answer questions on installation, tutorials, and the supporting community, as well as on input and output formats, programming interfaces, and the possibilities for participation in the further development of the software. These questions themselves entail further relevant follow-up questions; for example for the installation process one also has to consider whether the software is a stand-alone or a web application, whether the installation requirements are clearly documented and whether the documentation is complete and up-to-date. The questions in the catalogue we consider the most relevant are prefixed with :bangbang: (very important) and :heavy_exclamation_mark: (important).

The results of the review should be summarised in a statement that evaluates the software in terms of its usefulness, its usability, its quality of craftsmanship and its position in relation to the aforementioned ideals of good research software.

The catalogue of questions presented below is extensive and does not need to be worked through in every detail. Its complexity and depth is a good indicator that the development of research software can indeed be a full-fledged, scientific activity. We advise critically reflecting on one's own competencies in regard to the review and, if necessary, carrying out the evaluation in a team. For, just as reviews of conventional publications are ideally written by experts on the topic, this should also apply to research software reviews.

## Catalogue of questions for the assessment of software

Below we present an annotated catalogue of questions with criteria for the assessment of archaeological research software. Three sections bundle questions from different areas of competence. The first two sections deal with the scientific field of application, as well as the utilisation and usability from the user's point of view. The third section focuses on questions that are particularly relevant for developers and IT administrators. The catalogue concludes with a list of key data that supplement the review in tabular form, but cannot usually be critically assessed.

As with the review of a scientific publication, the composition and weighting of the individual features is to be determined during the review itself and to be set in relation to the context of the application area. Accordingly, we intend the annotated catalogue to be a maximum version that can serve as an aid for the review and the assessment of one's own competences.

### Use in archaeology and scientific purpose

When assessing the scientific quality of research software, two central questions must be answered. The first one - and this is a priority for research software - is whether the software contributes to working on archaeological questions in a meaningful way. Secondly, it has to be determined whether the software properly implements the intended task. Both questions are not always easy to answer.

* :bangbang:**What task is the software trying to solve?** This question is linked to the descriptive character of a review: what tasks are being addressed by means of the software in the acquisition, processing or analysis of data? How relevant are the tasks in an archaeological context and how often are they performed? This point illustrates why it is of particular value when archaeologists write software reviews for themselves and their colleagues.

* :bangbang:**How does the software solve a given (technical) task?** A detailed answer to this question is only possible from the developer's perspective. However, core components can usually be easily identified. How is the general software mode of operation designed? What are the basic technical components in the user interface and in the data processing modules behind it? For example, is it a web application that acts as an interface to a database? Or is the software a simple, monolithic command-line programme?

* :bangbang:**How does the scientific workflow implemented in the software work?** This is less about the actual technical implementation than the general methodology employed. Which integral process is applied to data to solve a certain task? Which statistical tools are used? Is there comparative data? An example could be cleaning up input data, subsequently classifying it with an algorithm and finally visualising it.

* :bangbang:**Is the claim to be able to answer a certain scientific question with the chosen workflow correct?** Research software usually promises - implicitly or explicitly - to enable or at least simplify the answering of scientific questions. A GIS application for analysing point patterns, for example, may have been designed for the purpose of demonstrating human settlement behaviour. The question of whether the algorithm used is even capable of doing this may far exceed the scope of a review. Nevertheless, the reviewer should try to make an assessment of plausibility or at least reveal the problem of assessability itself in order to raise awareness for readers. For the assessment, it may help to consider which conclusions could be theoretically deduced from the raw, unprocessed input data in the first place.

* :bangbang:**Have the algorithms been implemented correctly?** The correctness of  software results is sometimes difficult to judge because it would require an extensive black-box test. A lack of comparable software with the same functionality makes this even more difficult. Are the algorithms mentioned in the documentation implemented without errors in the source code? Is the scientific result comparable to other software solutions despite all technical differences? Are the algorithms used sufficiently documented and scientifically proven? This question, too, may not be answered conclusively in the context of a review. A prominent indication of a faulty implementation is the lack of robustness, which will be discussed later.

* :bangbang:**Are there any projects/application examples relevant to archaeology in which the reviewed software has already been used?** Software is often developed by and for specific research projects. To assess its quality and relevance, it can therefore be helpful to take a closer look at the research projects themselves. How plausible are the results achieved that are related to the software? How were they received by the scientific community?

* :bangbang:**In what form is the software published?** Ideally, research software should also be scientifically published. This facilitates its citation. Is there a benchmarking paper in which the tool is explicitly presented and compared with alternative products? Are individual versions of the software referenceable separately? For example, does a Digital Object Identifier (DOI) and thus a persistent link exist? Has the software been published in a journal or in another medium? Did it undergo a software peer review mechanism?

### Usability and target group orientation

The usability of research software is of central importance because it is a bottleneck that determines the interaction between the user and the software. It includes, for example, the complexity of the installation process, the user interface and machine interfaces. Here it should be noted that, for example, a graphical user interface offers advantages for occasional users, while operation via a command line for processing large data sets is more advantageous for experienced users. Help features (forums, FAQs, tutorials), and the size and activity level of the user and developer community are crucial for practical operability. The amount of activity in the communities can be an important indicator for the sustainability of software and thus its suitability for use at an institutional level in long-term projects.

The following questions concern technical features that influence the user experience (UX). We look at other technical features from the developer's perspective later.


#### Installation

Installation is often the first step in using the software. Already at this point, issues can become apparent and/or be of importance for the readers of a review.

* :bangbang:**How does the installation work and where is the software kept?** The easier the installation of the software, the larger its potential user base. From a developer's point of view, the diversity of computer systems often hinders ensuring easy installation for all users. For the review, it can be checked whether an installation script, wizard or package is available. Maybe the software is only available as source code, which must first be compiled by the user; installation scripts or packages allow a much wider user community, whereas compiling allows skilled users to perform the installation on different devices. Specific problems and weaknesses in the installation process can be identified and documented in the review if the software is actually installed by the reviewer.

* :heavy_exclamation_mark:**Is it a stand-alone software or a web application?** Not all software needs to be installed locally to be used. Nowadays, web applications that run either dynamically in the browser or on a server are capable of arbitrarily complex operations. Thus, it should be asked whether the application is more suitable for its use in archaeological practice as a local installation or as a web application. Web applications, for example, may not always perform adequately as they require the transfer of large amounts of data over the internet. They may not be executable in the field and are therefore not useful for all work settings.

* :heavy_exclamation_mark:**Are necessary requirements in terms of hardware and operating system clearly documented?** Especially during project planning, it is important to be able to correctly identify technical and financial requirements. A specification or instructions on the required hardware and operating system are relevant, for example, for integration with existing infrastructures in larger projects or institutes.


#### Interface

The usability of software is determined by the possibilities for communication between humans and machines, i.e. the user interface (UI). In some cases, this is supported graphically (GUI), or the operation is carried out via an input of commands in the console (CLI). Mixed operation modes are also useful to address different user groups. These are often diverse and can never be clearly defined, for example, excavation technicians or state archaeologists, but for usability analysis they can be used as models to evaluate shared requirements for the software. The design of user interfaces and user navigation in menu structures represents a field of expertise on its own within software development. Solutions that are well adapted to the user's needs are the result of precise knowledge of the target group and their habits and needs. Good solutions, for example, fit seamlessly into the archaeological research process. A good interface supports error-free and efficient work; the comprehensibility of menu items or commands, or the meaningfulness of error messages, are aspects that should be considered in the review. Accessibility for people with disabilities  has so far been an insufficiently covered criterion, but it also affects efficiency and possible user groups.

* :heavy_exclamation_mark:**Is the user interface suitable for the user group?** Every user group, including the one to which the reviewer belongs to, will have certain expectations of the application handling. For some, a command line application is very easy to use, while others will have problems with it. Many software solutions have various user interfaces; for example, many web applications can be accessed both via a search box and filter functions in the graphical interface of a web page as well as code-based via a REST service.

* :heavy_exclamation_mark:**Is use in Archaeology intended?** The question about the user group should also be asked specifically for archaeology: does the archaeological use correspond to the use scenarios that the developers of the software had in mind? This often has a great influence on the user interface; CAD software frequently used by archaeologists, for example, was designed for architectural or mechanical engineering applications and confronts archaeologists and excavation technicians with an overwhelming plethora of functions.

* **Does the menu navigation follow certain de-facto standards?** If menu navigation or shortcuts are based on well-known and widespread software in the community, familiarisation with the software is eased and accelerated; some tools deliberately use input masks modelled on widely used spreadsheet programmes.

* **Is the programme multilingual, and in which languages is it offered?** Depending on the user group, the programme should perhaps be multilingual. Usually, at least an English version is expected. In the case of multilingual software, a usable and readable layout must be created for each language; button labels, for example, can vary greatly in text length and may result in a truncated display in some languages.

* **Are error messages easily understandable by reviewers?** An error message can enable users to correct the error's cause. Useful and helpful error messages are phrased in an understandable way and visibly placed in the application. Where appropriate, an error message can also provide feedback to the application developers. It must communicate the error message to the user and also send a useful report to the developers to fix the error. Stack traces (references to the position in the programme code where a specific error occurred) or error messages taken from the runtime environment are incomprehensible to most users.

#### Performance and Robustness

Performance and robustness influence how the programme is used. Performance especially plays a role in the processing of large data sets, while robustness influences the user's saving and back up behaviour.

* **Is the implementation performant?** The importance of the performance of an application depends on the application type. Here, a reviewer should assess whether the software performs its task in reasonable time. If necessary, the execution time of other related software implementations can be compared with the one under test. The reasons for poor software performance are often not easy to identify. For web applications and plugins, a check for responsiveness and good performance across browsers should be executed.

* :heavy_exclamation_mark:**Is the software robust?** The robustness of software essentially requires that the intermediate states of tasks are regularly saved in order to be able to pick up again from the last state in the event of an unforeseen termination. Without this function, an event such as a power failure can cause the loss of settings, data and/or the entire reinitialisation of a calculation. An example of such robustness is the regular automated buffering in a text processing programme. The text document is thus recoverable in the event of a software crash. Depending on the use case, it may also be advantageous for the software to keep a history of user changes and allow users to restore them. These could be language configuration or the settings of units of measurement, specifications for the storage location and the like.

#### Help features, tutorials and community

In addition to help functions and tutorials, it is of great importance whether the software is supported by a community. The number of active users and developers of a software tool is decisive for whether one can find help in forums when problems arise or, in the case of a small group of users, can only get help through personal exchange. However, small user networks can offer the great advantage that issues are quickly taken up by the developers.

* :bangbang:**Are there enough tutorials for learning the software?** Tutorials are essential to address both users and software developers. Users usually expect an easy-to-understand example, focused on the essentials, to get an idea of the typical usage. For developers, it is crucial that a tutorial explains existing programming interfaces (APIs). Good tutorials explain the required knowledge prerequisites and give references to sources for acquiring it. Help in an FAQ or a troubleshooting section also increases the quality of a tutorial. The languages in which the tutorials are available are also of relevance.

* :heavy_exclamation_mark:**Do test data sets exist for the software?** This question is closely related to the question of tutorials, since the latter often work with exercise data. These exercise data or test data sets should be oriented towards scientific practice, but should be understandable without specific prior knowledge. They should be freely available and, if possible, usable without registration.

* **Is further information on the software easy to find?** Do the software information pages or its tutorials refer to further materials? Do they refer to publications by the developers themselves, as well as reviews of them?

* :bangbang:**Is the software supported by a community, and what proportion are classical and ancient studies scholars?** Examples of software development that was initially run by a classical and ancient studies community and has since expanded to include other disciplines are [Pelagios Commons](https://pelagios.org/) (https://pelagios.org/ [23.10.2020]) and the web application [Recogito](https://recogito.pelagios.org/) (https://recogito.pelagios.org/ [23.10.2020]). Dedicated user groups with a focus on archaeological issues have also developed, for example, within the communities for software packages like QGIS or R.

* :heavy_exclamation_mark:**Are there archaeological best practices or publications that refer to the reviewed software?** While forums, blogs and related media offer direct and often also rapid exchange with users and possibly developers, the inclusion and recommendation of programmes in best practices and publications is a further indication of their dissemination, scope and reliability.

#### Data ingest, interoperability and programming interfaces

Input and output data formats affect compatibility with other applications and should be mentioned in a review. In many cases, the supported file formats can be found via a corresponding menu entry (e.g. Save As). The various ways of reading in the data and programming interfaces are also relevant.

* :bangbang:**Which data formats are read in and how?** Are all relevant data formats supported by the software for the envisaged task and the anticipated typical use case? Are open data formats supported? Can data formats also be read in from common repositories (e.g. web services, Git, cloud services)?

* :bangbang:**Which output data formats are supported?** The programme should offer output data formats that allow further processing in other (also open source) software packages. Thus, at least one openly specified format should be supported. If data exports are only possible in a proprietary format, maybe even custom to that software, this must be well justified by the developers.

* :heavy_exclamation_mark:**How can data be read in? Does the software allow batch processing?** For many application scenarios, the execution of a once-defined workflow on a batch of files or a series of data is important; such as applying the same transformation steps for all images in a directory.

* :bangbang:**Is there an application programming interface (API)?** In addition to operability by a human, machine control of the software is also important. This is the only way, for example, to completely automate complex processes with several software components. An API enables this. It should be as open as possible and, if necessary, documented by means of a standard such as [OpenAPI](https://www.openapis.org) (https://www.openapis.org [23.10.2020]). An example of APIs are the endpoints offered by Wikidata, which allow for automated data queries.

#### Conformity with regulations on data protection and data minimisation

The question of data protection often determines whether the software may be used at all in university research and teaching. However, an assessment of the regulations, unless they clearly refer to the European framework directives, is sometimes very difficult and requires legal advice. The review can already provide an important service for readers by just highlighting the topic. This also applies to data minimisation, necessity of registration processes, cookies and the like.

* **Does the software comply with the laws (e.g. on data protection, map displays, etc.) of the country of assignment?** It must be expected that the software will be used in different regions and countries, each of which has specific laws that affect the execution/installation of the software. An example are cloud applications developed for a North American user base that are not compatible with the EU-wide General Data Protection Regulation.

* **What data does the application store, for what purpose and for how long? Are data transferred to third parties?** In many software applications, usage and user data is collected anonymously to improve the user experience. However, some software providers collect much more data and, for example, also transfer it to third parties. What data is collected and for how long it is stored should become clear from the software documentation. This also applies to the first visit to a web application by a user, at which point the user's consent should be requested. Furthermore, a review could question whether the declared purpose of the data collection is justified and really serves to improve the software.

### Developer perspective

Developers are also users of software, but generally have a different perspective on it. This user group has specific technical interests and can often envisage a broader set of application scenarios. A good summary of the developer perspective on software quality is provided by [@jung2004measuring](#jung2004measuring). There, the specifications of the [ISO/IEC 9126 standard](https://de.wikipedia.org/wiki/ISO/IEC_9126) (https://de.wikipedia.org/wiki/ISO/IEC_9126 [23.10.2020]) are elaborated with examples.

The following questions focus on the source code and the software architecture. These can only be assessed if the source code is openly accessible (open source), which is usually not at all, or only to a limited extent, the case for proprietary software.

#### Documentation and tests

Extensive documentation provides a comprehensive understanding of the software's purpose, matureness and current state of development. It is also essential for extending the software. Finally, solid documentation will also appeal to a larger community of potential developers.

There are several components of documentation, namely documentation of:
* the *source code*, i.e. of classes or individual methods,
* the *build process*, i.e. how the software is compiled (built) from the source code,
* the *software testing process*, i.e. which test cases were considered by the software.

Finally, there is a *developer documentation* with usage examples.

Software repositories such as [GitHub](https://github.com) (https://github.com [23.10.2020]) or [GitLab](https://gitlab.com) (https://gitlab.com [23.10.2020]) often offer templates or best practices to implement these documentation requirements in different programming languages.

An important concept in the context of documentation and testing is that of *Continuous Integration* (CI). It refers to the continuous assembly of individual application components. For this purpose, routines are prepared to execute various tasks. This allows for automatic triggering of, for example, the creation of source code documentation, the execution of a software test or the generation of an executable file from the source code (release file, EXE file). Usually, the routines are executed again after each change to the source code. By doing so, all programme components are kept up to date.

* **Does a source code documentation exist and, if applicable, is an HTML variant of it available?** Best practices here are, for example, source code documentation with [Doxygen](https://www.doxygen.nl/index.html) (https://www.doxygen.nl/index.html [23.10.2020]), [JavaDoc](http://www.oracle.com/technetwork/java/javase/documentation/javadoc-137458.html) (http://www.oracle.com/technetwork/java/javase/documentation/javadoc-137458.html [23.10.2020]), [JsDoc](https://jsdoc.app) (https://jsdoc.app [23.10.2020]) or the popular [ReadTheDocs](https://readthedocs.org) (https://readthedocs.org [23.10.2020]) for Python. All of the tools above generate an HTML representation of the documentation, which should then ideally be made available online, for example as a GitHub page.

* **Is the build process documented and, if applicable, automated by means of build scripts?** In addition to a basic understanding of the programme architecture, knowledge of the build instructions of the software, i.e. the build process, is important. The documentation should include information about a functioning build process of the software. In the past, instructions in README files or similar natural language descriptions were used. Nowadays, it has become an established standard to provide machine-readable build instructions (*build scripts*). These describe, in an unambiguous, machine-readable way, how the software was built and often allow the build process to be started with a single command. Build scripts also document the dependencies of the software and the *libraries* used. Examples of such scripts can be found, in [Apache Maven](https://maven.apache.org) (https://maven.apache.org [23.10.2020]) or [Gradle](https://gradle.org) (https://gradle.org [23.10.2020]).

* :heavy_exclamation_mark:**Is the documentation up to date and does it address all functions of the programme?** The latest edit date for documentation can usually be found in a timestamp if the documentation was created with one of the documentation tools mentioned above. This date should be the same as, or more recent than, the release date of the current software version. If, in the best case, the principles of *Continuous Integration* are applied, the generation and provision of documentation is directly integrated into the development of the application, such as the [GitHub repository of the SPARQLing-Unicorn- QGIS plugin](https://github.com/sparqlunicorn/sparqlunicornGoesGIS) (https://github.com/sparqlunicorn/sparqlunicornGoesGIS [23.10.2020]). Here, an automated process recreates the documentation every time the source code changes and publishes it to the [GitHub page of the repository](https://sparqlunicorn.github.io/sparqlunicornGoesGIS/) (https://sparqlunicorn.github.io/sparqlunicornGoesGIS/ [23.10.2020]).

* **Is there developer documentation that promotes further software development?** The developer documentation represents the entry point for developers to engage with further enhancement of software beyond just using it. A meaningful README file that briefly demonstrates the use of the programme with the default settings is a minimum requirement. An example of this is [Bibtex_JS](https://github.com/pcooksey/bibtex-js) (https://github.com/pcooksey/bibtex-js [23.10.2020]). Ideally, sample data is included for a better understanding of the programme flow and, if necessary, other frequently used use cases of the software are presented in examples. This applies to the example just mentioned: [Bibtex_JS-Examples](https://github.com/pcooksey/bibtex-js/tree/master/test)) (https://github.com/pcooksey/bibtex-js/tree/master/test [23.10.2020]). Depending on the complexity of the software, it may be useful to provide a wiki, possibly also maintained by a user community, to explain advanced options (see [Bibtex_JS-Wiki](https://github.com/pcooksey/bibtex-js/wiki); https://github.com/pcooksey/bibtex-js/wiki [23.10.2020]).

* **Does the source code contain software tests for testing core functions and demonstrating them to other developers?** Any software can be checked for its expected behaviour with software tests. Accordingly, software tests provide information about the envisaged use cases and, as a test result, which functions are stable, error-prone or in need of improvement. As part of a *Continuous Integration* process, software tests can be executed automatically after each change to the source code.

* **Is it made easy for the developer to test the software (e.g. virtual machine, Docker container, installer)?** Developers are usually able to build and run software, but this can be a more or less complex task. In fact, software that is easy to install and, more importantly, easy to test will be more popular with developers who want to get a quick look at the functionality, as well as with other users. Obviously, available testing methods depend on the type of application. A web application, for example, may be hosted on the Internet and provide the user with a test account (e.g. [CWRCWriter](https://cwrc.ca); https://cwrc.ca [23.10.2020]), whereas a desktop application may already include an installable application or installer package. Server applications can be available for easy testing as virtual machine images or, more commonly lately, as Docker images in portals such as [Dockerhub](https://hub.docker.com) (https://hub.docker.com [23.10.2020]).

* **Are the developers readily accessible?** When using software, it often turns out that functionalities are missing or bugs are present in the programme. This can hinder the use of the software for certain use cases or significantly worsen the results. In such cases, the availability of the developers and their feedback on support requests is a decisive criterion. It should be clearly communicated how and where bug reports can be submitted and what information is required for rapid and accurate handling. Whether the developers cultivate an active support can be seen, for example, in the issue area of the software repository (e.g. GitHub or GitLab). Have the developers there answered enquiries promptly and satisfactorily? What is the ratio of open issues to already closed ones? How long did it take for a change to be incorporated?

* :heavy_exclamation_mark:**Is the software being actively worked on?** An indication for this are regular software updates. In a roadmap developers can proactively communicate which changes are planned for the programme in the near future and which issues are to be worked on for the next release.

* :bangbang:**Is it possible to support software development?** To enable external software developers to contribute to the software, a *Contribution Guideline* is helpful. It contains information on the circumstances under which, and how, changes to the software are accepted and integrated by third parties (e.g. [https://projectacrn.github.io/latest/developer-guides/contribute_guidelines.html](https://projectacrn.github.io/latest/developer-guides/contribute_guidelines.html) [23.10.2020]).

#### Quality of implementation

The quality of the implementation influences whether and to what extent the programme is suitable for adaptation and further development, and thus also how long it is likely to persist.

* **Does the implementation reflect the state of the art?** This question usually has to be answered in relation to the field of application and requires a technical understanding of the processes within the software. Some aspects can be assessed without technical knowledge: is the application usable on many different devices (e.g. mobile phone, different operating systems, etc.)? Are outdated technologies avoided, such as Adobe Flash or Java applets in web applications? Do automatic test systems (for example on GitHub) identify security gaps in the software?

* **Is *Continuous Integration* used to ensure implementation quality?** For a developer, not only the existence and documentation of the source code is crucial, but s/he will usually also expect information about the functionality and compilability of the source code. As already mentioned in the previous sections, *Continuous Integration* can be such a quality indicator. The *Continuous Integration* process tests the compilability of the software after each change and can indicate the resulting status in the repository. It is a sign of well-maintained source code if it compiles in the currently released version and, if applicable, in the current development version.

## Tabular Key Data for Software

In the table below we present key data that can be listed in tabular form at the end or beginning of a review. This can provide a quick overview of the software, much like the way book reviews neutrally list title, publisher and ISBN. If necessary, this table can also be supplemented with hardware requirements if these are particularly relevant. We have chosen the GIS application *QGIS* as an example.

- Name: The name of the software, e.g. *"QGIS"*.
- Short description: Summary of what the software does, e.g. *"Comprehensive graphical tool for spatial data processing"*.
- Reviewed version: The software version used for the review, e.g. *"3.10.10 LTR"*.
- Platform: (Operating) systems on which the software can be used, e.g. *"Windows, MacOS, Linux, BSD, Android"*.
- Website: URL where further information can be found, e.g. *https://qgis.org*.
- Licensing: Software licence under which the software was published, e.g. *"Open Source with GNU General Public License (GPL)"*.
- Costs: If applicable, regular or one-off licence fees, e.g. *"free of charge"*.
- Input and output formats: The file formats the software can process, e.g. *"geodatabases" (SpatiaLite, PostGIS, MSSQL, ...), "web geodata services" (WMD/WMTS, Vector Tiles, XYZ Tiles, WFS, ...), "geo-vector data formats" (ESRI Shapefile, Geopackage, . ...), "geo-raster data formats" (GeoTIFF, ...), "table data" (CSV, TXT, ...) and other data types* (for QGIS there are an unusually large number of data formats to consider, which would go beyond the scope here).

## Where do we go from here?

The discussion about the evaluation of research software in archaeology and its neighbouring disciplines has only just begun and no consensus has yet been worked out. Our considerations and the catalogue of questions presented here should therefore be directly understood as a stimulus for discussion and an invitation to establish a common understanding of the requirements for a software review. As noted at the outset, comments from a wide range of perspectives and disciplines are invited via GitHub or email. The catalogue is by no means set in stone, but rather open to modifications and updates by archaeologists and research software engineers in the future.


## Notes

<a name="#authornote">*</a>: Authors are listed in alphabetical order.

## Bibliography
