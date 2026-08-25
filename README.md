# Awesome Semantic Web with stars

A curated list of various semantic web and linked data resources.

To add something to the list please either submit a pull request or add a comment with a link to [issues/awesomelets](https://github.com/semantalytics/awesome-semantic-web/issues/81) ⭐ 1,680 | 🐛 32 | 📅 2026-08-14. Pull requests will be evaluated immediately for inclusion while awesomelets will be evaluated at some indeterminate time in the future.

Looking for something but can't find it? Add it to the ["Does it exist"](https://github.com/semantalytics/awesome-semantic-web/issues/74) ⭐ 1,680 | 🐛 32 | 📅 2026-08-14 list and we'll keep an eye out for it. If it's a good idea maybe someone will come along and create it!

## Contents

* [Standards](#standards)
* [Serialization](#serialization)
* [Datatypes](#datatypes)
* [Companies](#companies)
* [Industry](#industry)
* [Government](#government)
* [Research Institutions](#research-institutions)
* [Academic Journals](#academic-journals)
* [Databases](#databases)
* [SPARQL](#sparql)
  * [Streaming](#streaming-sparql)
  * [Federated](#federated-sparql)
  * [Applications](#sparql-applications)
* [Benchmarks](#benchmarks)
* [GraphQL](#graphql)
* [Linked Data Fragments](#linked-data-fragments)
* [Linked Data Platform](#linked-data-platform-ldp)
* [Ecosystem](#ecosystem)
* [Knowledge Graph Management](#knowledge-graph-management)
* [Web Annotations](#web-annotations)
* [Mapping](#mapping)
* [Ontologies](#ontologies)
* [Ontology Development](#ontology-development)
* [Reasoners](#reasoners)
* [Books](#books)
* [Programming](#programming)
  * [C](#c)
  * [C#](#c-1)
  * [Clojure](#clojure)
  * [Elixir](#elixir)
  * [Go](#go)
  * [Groovy](#groovy)
  * [Haskell](#haskell)
  * [Java](#java)
  * [JavaScript](#javascript)
  * [Kotlin](#kotlin)
  * [ObjectiveC](#objectivec)
  * [OCaml](#ocaml)
  * [Perl](#perl)
  * [PHP](#php)
  * [Prolog](#prolog)
  * [Python](#python)
  * [R](#r)
  * [Ruby](#ruby)
  * [Rust](#rust)
  * [Scala](#scala)
  * [Swift](#swift)
* [Editors](#editors)
* [Geo](#geo-1)
* [Visualization](#visualization)
* [Data Cube](#data-cube)
* [Datasets](#datasets)
* [IoT](#iot)
* [DevOps](#devops)
* [Platforms](#platforms)
* [Tools](#tools)
* [Integrations](#integrations)
* [Machine Learning](#machine-learning)
* [Linked Data](#linked-data)
* [CSVW](#csvw)
* [WebID](#webid)
* [SHACL Implementations](#shacl-implementations)
* [SKOS Tools](#skos-tools)
* [NLP](#nlp)
* [IIIF](#iiif)
* [Other Awesome](#other-awesome)

## Standards

### W3C

* (2025-26) [Follow the new RDF/Schema/SPARQL (1.2) Recommendation Updates](https://www.w3.org/groups/wg/rdf-star/publications/)
* (2025-26) [Follow the new SHACL Shapes/SPARQL (1.2) Recommendation Updates](https://www.w3.org/groups/wg/data-shapes/publications/)

### XML

* [XSD Datatypes](https://www.w3.org/2011/rdf-wg/wiki/XSD_Datatypes) - XML Schema datatypes used in RDF and semantic web applications.

### RDF

* [RDF 1.1 Primer](https://www.w3.org/TR/rdf11-primer/) - Primer providing an informal introduction to RDF.
* [RDF 1.1 Semantics](https://www.w3.org/TR/rdf11-mt/) - Formal semantics for RDF and RDFS.
* [RDF 1.1 Concepts and Abstract Syntax](https://www.w3.org/TR/rdf11-concepts/) - Defines abstract syntax and core concepts of RDF.
* [RDF 1.1: On Semantics of RDF Datasets](https://www.w3.org/TR/rdf11-datasets/) - Semantics for RDF datasets.
* [RDF Dataset Canonocalization](https://json-ld.github.io/rdf-dataset-canonicalization/spec/) Unofficial Draft

### RDFS

* [RDF Schema 1.1](https://www.w3.org/TR/rdf-schema/) - RDF vocabulary description language.

### OWL

* [OWL 2 Web Ontology Language Document Overview](https://www.w3.org/TR/owl-overview/)
* [OWL 2 Web Ontology Language Primer](https://www.w3.org/TR/owl-primer/)
* [manchester](https://www.w3.org/2007/OWL/draft/ED-owl2-manchester-syntax-20081128/)
* [manchester-syntax-owl](https://github.com/rollxx/manchester-syntax-owl2) ⭐ 2 | 🐛 0 | 🌐 GAP | 📅 2014-12-22

### SHACL

* [SHACL Shapes Constraint Language](https://www.w3.org/TR/shacl/)
* [SHACL Advanced Features](https://www.w3.org/TR/shacl-af/)
* [SHACL JavaScript Extensions](https://www.w3.org/TR/shacl-js/)
* [SHACL Test Suite and Implementation Report](https://w3c.github.io/data-shapes/data-shapes-test-suite/#test-cases-format-and-process)

### ShEx

* [ShEx - Shape Expressions](http://shex.io)

### SPARQL

* [SPARQL 1.1 Overview](https://www.w3.org/TR/sparql11-overview/)
* [SPARQL 1.1 Query Language](https://www.w3.org/TR/sparql11-query/)
* [SPARQL 1.1 Update](https://www.w3.org/TR/sparql11-update/)
* [SPARQL 1.1 Service Description](https://www.w3.org/TR/sparql11-service-description/)
* [SPARQL 1.1 Federated Query](https://www.w3.org/TR/sparql11-federated-query/)
* [SPARQL 1.1 Query Results JSON Format](https://www.w3.org/TR/sparql11-results-json/)
* [SPARQL 1.1 Query Results CSV and TSV Formats](https://www.w3.org/TR/sparql11-results-csv-tsv/)
* [SPARQL 1.1 Query Results XML Format (Second Edition)](https://www.w3.org/TR/rdf-sparql-XMLres/)
* [SPARQL 1.1 Entailment Regimes](https://www.w3.org/TR/sparql11-entailment/)
* [SPARQL 1.1 Protocol](https://www.w3.org/TR/sparql11-protocol/)
* [SPARQL 1.1 Graph Store HTTP Protocol](https://www.w3.org/TR/sparql11-http-rdf-update/)

### R2RML

* [R2RML: RDB to RDF Mapping Language](https://www.w3.org/TR/r2rml/)

### RDFa

* [XHTML+RDFa 1.1 - Third Edition](https://www.w3.org/TR/xhtml-rdfa/)
* [RDFa Lite 1.1 - Second Edition](https://www.w3.org/TR/rdfa-lite/)
* [HTML+RDFa 1.1 - Second Edition](https://www.w3.org/TR/html-rdfa/)

### Tabular

* [CSV on the Web: A Primer](http://www.w3.org/TR/tabular-data-primer/)
* [Model for Tabular Data and Metadata on the Web](https://www.w3.org/TR/tabular-data-model/)
* [Metadata Vocabulary for Tabular Data](http://www.w3.org/TR/tabular-metadata/)
* [Generating JSON from Tabular Data on the Web](http://www.w3.org/TR/csv2json/)
* [Generating RDF from Tabular Data on the Web](http://www.w3.org/TR/csv2rdf/)
* [CSV on the Web: Use Cases and Requirements](http://www.w3.org/TR/csvw-ucr/)
* [Embedding Tabular Metadata in HTML](http://www.w3.org/TR/csvw-html/)

### Open Services for Lifecycle Collaboration (OSLC)

* [open-services.net](https://open-services.net/)

### Web Annotation Data Model

* [Web Annotation Data Model](https://www.w3.org/TR/annotation-model/)
* [Web Annotation Vocabulary](https://www.w3.org/TR/annotation-vocab/)
* [Web Annotation Protocol](https://www.w3.org/TR/annotation-protocol/)

### Linked Data Notifications

* [Linked Data Notifications](https://www.w3.org/TR/ldn/)

### Linked Data Platform

* [Linked Data Platform 1.0 Primer](https://www.w3.org/TR/ldp-primer/)
* [Linked Data Platform Best Practices and Guidelines](https://www.w3.org/TR/ldp-bp/)
* [Linked Data Platform 1.0](https://www.w3.org/TR/ldp/)
* [Linked Data Platform 1.0 Test Cases](https://dvcs.w3.org/hg/ldpwg/raw-file/tip/tests/ldp-testsuite.html)

### Linked Data Templates

* [Linked Data Templates](https://atomgraph.github.io/Linked-Data-Templates/)

### Linked Data Fragments (LDF)

* [Linked Data Fragments](http://linkeddatafragments.org)

### Data Cube extensions

* [QB4ST: RDF Data Cube extensions for spatio-temporal components](https://www.w3.org/TR/qb4st/)

## Serialization

| Format                                                                                    | Description                                                                                                                                                                 |                          Mime-type                         |                 |   |
| :---------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------: | --------------- | - |
| [Jelly](https://jelly-rdf.github.io/dev/)                                                 | a high-performance binary serialization format and streaming protocol for RDF knowledge graphs.                                                                             | `application/x-jelly-rdf`, `application/x-jelly-rdf-patch` |                 |   |
| [Turtle](https://www.w3.org/TR/turtle/)                                                   | Terse RDF Triple Language.                                                                                                                                                  |            `text/turtle`, `application/x-turtle`           |                 |   |
| [TriG](https://www.w3.org/TR/trig/)                                                       | Plain text format for serializing named graphs and RDF Datasets.                                                                                                            |          `application/trig`, `application/x-trig`          |                 |   |
| [JSON-LD](https://json-ld.org/)                                                           | JSON-based Serialization for Linked Data.                                                                                                                                   |                    `application/ld+json`                   |                 |   |
| [YAML-LD](https://w3c.github.io/yaml-ld/)                                                 | YAML-based format for expressing Linked Data with JSON-LD semantics.                                                                                                        |                    `application/ld+yaml`                   |                 |   |
| [RDF/JSON](https://www.w3.org/TR/rdf-json/)                                               | RDF 1.1 JSON Alternate Serialization.                                                                                                                                       |                   `application/rdf+json`                   |                 |   |
| [N-Triples](https://www.w3.org/TR/n-triples/)                                             | Line-based syntax for RDF datasets.                                                                                                                                         |                   `application/n-triples`                  |                 |   |
| [N-Quads](https://www.w3.org/TR/n-quads/)                                                 | Line-based syntax for RDF datasets.                                                                                                                                         |    `application/n-quads`, `text/x-nquads`, `text/nquads`   |                 |   |
| [Notation3](https://www.w3.org/TeamSubmission/n3/)                                        | Notation3 (N3): A readable RDF syntax.                                                                                                                                      |                  `text/n3`, `text/rdf+n3`                  |                 |   |
| [RDF/XML](https://www.w3.org/TR/REC-rdf-syntax/)                                          | RDF/XML Syntax Specification.                                                                                                                                               |          `application/rdf+xml`, `application/xml`          |                 |   |
| [TriX](http://www.hpl.hp.com/techreports/2004/HPL-2004-56.html)                           | RDF Triples in XML.                                                                                                                                                         |                     `application/trix`                     |                 |   |
| [HDT](https://www.w3.org/Submission/2011/03/)                                             | Binary RDF Representation for Publication and Exchange.                                                                                                                     |                 `application/x-binary-rdf`                 |                 |   |
| [CBOR-LD](https://w3c.github.io/cbor-ld/)                                                 | CBOR-based format for expressing Linked Data.                                                                                                                               |                                                            |                 |   |
| [Jelly](https://w3id.org/jelly)                                                           | Performance-oriented binary serialization for RDF and RDF streams.                                                                                                          |                  `application/x-jelly-rdf`                 |                 |   |
| [RDF Thrift](https://afs.github.io/rdf-thrift/)                                           | RDF binary serialization in Apache Thrift.                                                                                                                                  |                  `application/rdf+thrift`                  |                 |   |
| [aREF](https://gbv.github.io/aREF/aREF.html)                                              | Another RDF Encoding Form.                                                                                                                                                  |                                                            |                 |   |
| [RDF/POST](https://atomgraph.github.io/RDF-POST/)                                         | RDF/POST Encoding for RDF.                                                                                                                                                  |           `application/rdf+x-www-form-urlencoded`          |                 |   |
| [YARRML](http://rml.io/yarrrml/spec/)                                                     | YARRRML is a human readable text-based representation for declarative generation rules. It is a subset of \[YAML], a widely used data serialization language designed to be |                                                            | human-friendly. |   |
| [hextuples](https://github.com/ontola/hextuples) ⭐ 33 \| 🐛 7 \| 📅 2024-10-14            | NDJSON serialization                                                                                                                                                        |                                                            |                 |   |
| [COTTAS](https://github.com/arenas-guerrero-julian/pycottas) ⭐ 0 \| 🐛 0 \| 📅 2026-02-13 | Columnar Triple Table Storage                                                                                                                                               |                                                            |                 |   |

## Datatypes

* [CDT](https://ci.mines-stetienne.fr/lindt/v2/custom_datatypes.html)
* [QUDT](http://www.qudt.org)
* [Data tensors in RDF](https://w3id.org/rdf-tensor)
* [RDF Datatyping](http://infolab.stanford.edu/~melnik/rdf/datatyping/) - This document summarizes the common understanding of the RDF Core Working Group (further referred to as WG) with regards to the theoretical foundation for datatyping of literal values and serves as a basis of definition, discussion, and comparison of all proposed schemes for achieving a complete datatyping solution which are to be considered by the WG.

## Companies

Companies or businesses selling products with a primary focus on semantic web technology

* [Stardog Union](http://stardog.com) - Knowledge Graph Platform for the Enterprise.
* [Epimorphics](https://www.epimorphics.com/)
* [Franz](http://franz.com)
* [PoolParty](https://www.poolparty.biz/)
* [Cambridge Semantics](https://www.cambridgesemantics.com/)
* [Oxford Semantic Technologies](https://www.oxfordsemantic.tech/)
* [Capsenta](https://capsenta.com/)
* [Zazuko](https://zazuko.com/)
* [MarkLogic](https://www.marklogic.com/product/marklogic-database-overview/database-features/semantics/)
* [Oracle](https://www.oracle.com/technetwork/database/options/spatialandgraph/overview/rdfsemantic-graph-1902016.html)
* [OntoText](https://www.ontotext.com/)
* [TopQuadrant](https://www.topquadrant.com/)
* [OpenLinkSoftware](https://www.openlinksw.com/)
* [Cognitum](http://www.cognitum.eu/)
* [entryscape](https://entryscape.com)
* [inova8](http://www.inova8.com/)
* [in4mium](http://www.in4mium.com/)
* [Xylem Technologies](https://www.xylem-technologies.com/en/)
* [Enterprise Knowledge Graph Foundation](https://www.ekgf.org/) - Foundation promoting adoption of knowledge graphs in enterprise settings.
* [Synaptica](https://www.synaptica.com)
* [Ontola](http://ontola.io/)
* [eccenca Corporate Memory](https://www.eccenca.com) - Build, explore and consume Knowledge Graphs.
* [Semantic Arts](https://semanticarts.com) - Enterprise information systems based on flexible data structures and deep semantics.
* [Same4](http://www.seme4.com)
* [Derivo](https://www.derivo.de/en/home/)
* [Swirrl](https://www.swirrl.com/) - Linked-data publishing for Government organisations.
* [SURROUND Australia](https://surroundaustralia.com) - Semantic Web consulting and enterprise semantics platform provision.
* [AtomGraph](https://atomgraph.com/) - Free your data from silos.
* [Ontopic](https://ontopic.ai/) - Create Knowledge Graphs from databases and datalakes. Core contributors to Ontop and experts in virtualization.
* [iNovex](https://mobi.inovexcorp.com/) - Web-based, collaborative ontology and vocabulary editor, and knowledge graph solution platform.
* [Flur.ee](https://flur.ee/) - Provide a full stack of tools for data mapping, linking, vocabulary creation and develop an open source append only triple store (fluree.core).
* [Softplant](http://www.softplant.de/) - Provide a visual ontology engineering tool called Living Semantic Platform and an Enterprise Architecture Management Platform called Living EAM.
* [KurrawongAI](https://kurrawong.ai) - a small, Australian-based IT company, specialising in Knowledge Graphs, Data Modelling & AI.
* [NeverBlink](https://neverblink.eu) – streaming RDF and neurosymbolic systems.

## RDF Tripe Stores

* [See list of RDF Triple Store propducts](https://github.com/graphgeeks-lab/awesome-graph-universe?tab=readme-ov-file#triple-stores-rdf-databases) ⭐ 161 | 🐛 5 | 📅 2025-08-26

## Industry

Companies or businesses using semantic web technologies

* [Optum](https://www.optum.com) - Health related, known to use semantic graphs (marklogic).
* [DarkLight](https://www.darklight.ai) - DarkLight is an Artificial Intelligence Expert System for Active Cyber Defense and           Trusted Information Sharing.
* [Volkswagen UK](https://www.volkswagen.co.uk)
* [Siemens](https://www.siemens.com)
* [IBM](http://www.ibm.com)
* [Elsevier](https://www.elsevier.com) - Global information analytics business that helps institutions and professionals advance healthcare, open science and improve performance for the benefit of humanity
* [BestBuy](http://bestbuy.com)
* [Google](http://google.com)
* [Facebook](http://facebook.com)
* [BBC](https://www.bbc.com)
* [NASA](https://www.nasa.gov)
* [K Health](https://khealth.ai) - Self diagnosing app.
* [Schneider Electric](https://www.schneider-electric.com/ww/en/)
* [Osthus](https://www.osthus.com)
* [DataLanguage](https://datalanguage.com/)
* [Eccenca](https://eccenca.com/en/)
* [Perfect Memory](https://www.perfect-memory.com/) - DAM-as-a-Brain, a Platform that collects, interprets and makes any data and content actionable.
* [Field 33](https://field33.com) - Platform to build digital twins of organizations.

## Government

* [Australian Government Linked Data Working Group](https://www.linked.data.gov.au) - Australian government's community of practice for Linked Data & Semantic Web
* [W3C's Gov enrment Linked Data Working Group archived wiki](https://www.w3.org/2011/gld/wiki/Main_Page) - "Developing standards which help governments publish their data as effective and usable Linked Data, using Semantic Web technologies"

## Research Institutions

* [The Smart Data Analytics (SDA)](http://sda.tech/) - Research group, Institute for Computer Science at the University of Bonn, the Fraunhofer Institute for Intelligent Analysis and Information Systems (IAIS) and the Institute for Applied Computer Science Leipzig.
* [Agile Knowledge Engineering and Semantic Web (AKSW)](http://aksw.org) - The Research Group Agile Knowledge Engineering and Semantic Web (AKSW) is hosted by the Chair of Business Information Systems (BIS) of the Institute of Computer Science (IfI) / University of Leipzig as well as the Institute for Applied Informatics (InfAI).
* [University of Zurich Dynamic and Distributed Information Systems Group](http://www.ifi.uzh.ch/en/ddis.html)
* [WESO](http://www.weso.es/) - WESO is a research group at the University of Oviedo founded in 2004.
* [Max Planck Institute for Informatics](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/) - Department D5 of the Max Planck Institute for Informatics.
* [DICE: Data Science Group](http://dice.cs.uni-paderborn.de/about/) - Universität Paderborn.
* [Ontology Engineering Group (OEG)](http://www.oeg-upm.net/) - The Ontology Engineering Group (OEG) is based at the Computer Science School at Universidad Politécnica de Madrid (UPM).
* [Knowledge Representation and Reasoning Group (KRR)](https://krr.cs.vu.nl/) - Research group is based at the Vrije Universiteit Amsterdam (VU).
* [eXascale Infolab](https://exascale.info/) - eXascale Infolab, University of Fribourg, Switzerland.
* [Wimmics](http://wimmics.inria.fr/corese) - Wimmics stands for Web-Instrumented Man-Machine Interactions, Communities, and Semantics, a joint research team between INRIA Sophia Antipolis - Méditerranée and I3S (CNRS and Université Côte d'Azur).
* [Data Semantics Lab](https://dase.cs.wright.edu/) - Data Semantics Lab, Wright State University
* [Stanford BMIR](https://bmir.stanford.edu) - Stanford University Center for Biomedical Informatics Research
* [Exascale Infolab](https://exascale.info/projects/research/) - University of Fribourg, Switzerland
* [IDLAB](https://www.ugent.be/ea/idlab/en/research/semantic-intelligence/semantic-knowledge-generation-and-publication-at-scale.htm) - Ghent University, Belgium
* [Data Semantics Lab](https://daselab.cs.ksu.edu/) - Kansas State University, USA
* [Linköping University Semantic Web Group](https://www.ida.liu.se/research/semanticweb/) - Linköping University, Sweden
* [DBIS Lab](http://dbis.informatik.uni-freiburg.de/) - Freiburg, Germany
* [AD Lab](https://ad.informatik.uni-freiburg.de/) - Freiburg, Germany
* [SWE @HTWK Leipzig](https://wse-research.org/) - Web & Software Engineering research group @ Leipzig University of Applied Sciences (HTWK Leipzig)
* [Information Systems in the Built Environment](https://isbe.bwk.tue.nl/) - Research group @ Eindhoven University of Technology (TU/e), The Netherlands

## Academic Journals

* [Semantic Web Journal](http://www.semantic-web-journal.net/)
* [Journal of Web Semantics](https://www.journals.elsevier.com/journal-of-web-semantics)
* [International Journal of Web and Semantic Technology](http://www.airccse.org/journal/ijwest/ijwest.html)
* [Applied Ontology](https://www.iospress.com/catalog/journals/applied-ontology)
* [Journal of Biomedical Semantics](https://jbiomedsem.biomedcentral.com/)

## Databases

$ - Proprietary
OS - OpenSource
F - Free

* [Oxigraph](https://github.com/oxigraph/oxigraph) ⭐ 1,836 | 🐛 149 | 🌐 Rust | 📅 2026-08-24 - (OS) a graph database implementing the SPARQL standard and written in Rust.
* [Akutan](https://github.com/eBay/akutan) ⚠️ Archived - (OS) A distributed knowledge graph store written in Golang. Formerly known as Beam.
* [levelgraph](https://github.com/levelgraph/levelgraph) ⭐ 1,520 | 🐛 49 | 🌐 JavaScript | 📅 2024-05-28 - (OS) Graph database JS style for Node.js and the Browser.
* [QLever](https://github.com/ad-freiburg/qlever) ⭐ 886 | 🐛 391 | 🌐 C++ | 📅 2026-08-25 - (OS) a SPARQL engine that can efficiently index and query very large knowledge graphs with over a trillion triples on a single standard PC or server
* [gStore](https://github.com/pkumod/gStore) ⭐ 836 | 🐛 26 | 🌐 C++ | 📅 2026-04-09 - (OS) - a graph based RDF triple store.
* [4Store](https://github.com/garlik/4store) ⭐ 299 | 🐛 50 | 🌐 C | 📅 2024-05-10 - (OS).
* [MillenniumDB](https://github.com/MillenniumDB/MillenniumDB) ⭐ 264 | 🐛 3 | 🌐 C++ | 📅 2026-08-17 - (OS)
* [fabric](https://github.com/spy16/fabric) ⭐ 199 | 🐛 1 | 🌐 Go | 📅 2022-11-12 - (OS) Fabric is a simple triplestore written in Golang.
* [CM-Well](https://github.com/thomsonreuters/CM-Well) ⭐ 183 | 🐛 239 | 🌐 Scala | 📅 2023-06-20 - (OS).
* [wallix/triplestore](https://github.com/wallix/triplestore) ⭐ 118 | 🐛 4 | 🌐 Go | 📅 2019-02-19 - (OS) Nifty library to manage, query and store RDF triples.
* [QuitStore](https://github.com/AKSW/QuitStore) ⭐ 115 | 🐛 54 | 🌐 Python | 📅 2024-06-27 - Quads in Git - Git versioned RDF Triple Store with support for branching and mergin and more.
* [Halyard](https://github.com/Merck/Halyard) ⭐ 114 | 🐛 24 | 🌐 Java | 📅 2023-01-23 - (OS).
* [qEndpoint](https://github.com/the-qa-company/qEndpoint) ⭐ 109 | 🐛 72 | 🌐 Java | 📅 2026-03-18 - (OS) A highly scalable RDF triple store with full-text and GeoSPARQL support.
* [Tentris](https://github.com/dice-group/tentris) ⭐ 69 | 🐛 0 | 🌐 C++ | 📅 2025-08-13 - (OS) A tensor-optimized RDF data store, supporting SPARQL queries with Basic Graph Pattern capabilities.
* [Parliament](https://github.com/SemWebCentral/parliament) ⭐ 66 | 🐛 3 | 🌐 Java | 📅 2026-08-19 - (OS).
* [redstore](https://github.com/njh/redstore) ⭐ 65 | 🐛 6 | 🌐 C | 📅 2021-07-29 - (OS) RedStore is a lightweight RDF triplestore written in C using the Redland library.
* [ostrich](https://github.com/rdfostrich/ostrich) ⭐ 52 | 🐛 3 | 🌐 C++ | 📅 2025-08-21 - (OS) bird Versioned RDF triple store (Offset-enabled TRIple store for CHangesets).
* [kineo](https://github.com/kasei/kineo/) ⭐ 40 | 🐛 0 | 🌐 Swift | 📅 2026-08-18 - (OS) A persistent RDF quadstore and SPARQL engine.
* [CumulusRDF](https://github.com/cumulusrdf/cumulusrdf) ⭐ 31 | 🐛 30 | 🌐 Java | 📅 2016-04-14
* [hbase-rdf](https://github.com/castagna/hbase-rdf) ⭐ 24 | 🐛 3 | 🌐 Java | 📅 2020-10-13 - (OS).
* [Marklogic](https://github.com/marklogic/semantic) ⚠️ Archived - ($).
* [luposdate](https://github.com/luposdate/luposdate) ⭐ 19 | 🐛 6 | 🌐 Java | 📅 2022-09-01 - (OS) Semantic Web database.
* [Sempala](https://github.com/aschaetzle/Sempala) ⭐ 12 | 🐛 0 | 🌐 Java | 📅 2017-09-04
* [Vedas](https://github.com/Remixman/Vedas) ⭐ 9 | 🐛 0 | 🌐 Cuda | 📅 2024-03-26 - (OS) VEDAS is a RDF store engine that be able to query with SPARQL and run on single GPU.
* [TriplePlace](https://github.com/white-gecko/TriplePlace) ⭐ 3 | 🐛 1 | 🌐 Java | 📅 2015-01-08 - Light weight and flexible Triple Store for Android.
* [Jena TDB](http://jena.apache.org/documentation/tdb/index.html) - (OS).
* [Ontotext GraphDB™](http://graphdb.ontotext.com/) - ($/F).
* [Stardog](http://stardog.com) - ($/F).
* [Strabon](http://www.strabon.di.uoa.gr/) - (OS) A spatiotemporal RDF store.
* [Systap Blazegraph™](https://www.blazegraph.com/) - ($/OS).
  * [blazegraph-samples](https://github.com/blazegraph/blazegraph-samples) ⚠️ Archived
  * [docker-blazegraph](https://github.com/lyrasis/docker-blazegraph) ⭐ 28 | 🐛 6 | 🌐 Dockerfile | 📅 2023-11-27
  * [docker-blazegraph](https://github.com/zorino/docker-blazegraph) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2016-02-09
  * [blazegraph-service](https://github.com/vastix/blazegraph-service)
* [Virtuoso](https://virtuoso.openlinksw.com/) - ($/OS).
  * [virtuoso-opensource](https://github.com/openlink/virtuoso-opensource) ⭐ 973 | 🐛 667 | 🌐 C | 📅 2026-08-24
* [Oracle](http://www.oracle.com/technetwork/database/options/spatialandgraph/overview/rdfsemantic-more-2239071.html) - ($).
* [Allegrograph](http://franz.com/agraph/allegrograph/) - ($/F).
* [BrightstarDB](http://brightstardb.com/) - (OS) A native RDF database for the .NET platform written in C#.
* [Apache Rya](http://rya.incubator.apache.org/) - (OS).
* [Mulgara](http://mulgara.org/) - (OS).
* [SANSA](http://sansa-stack.net/) - (OS).
* [Anzograph](https://www.cambridgesemantics.com/product/anzograph/)
* [Node-Quadstore](https://beautifulinteractions.github.io/node-quadstore/) - (OS) A LevelDB-backed graph database for Node.js supporting quads, SPARQL queries and the RDF/JS interface.
* [KGRAM](http://wimmics.inria.fr/corese) - (OS).
* [Oxford Semantic RDFox](https://www.oxfordsemantic.tech) - ($) Horizontly scalalbe in-memory triple store with parallel Datalog reasoning.
* [NitrosBase](http://nitrosbase.com/) - (F)
* [Dydra](https://dydra.com) - ($) A cloud-based graph database.
* [librdf.sqlite](https://github.com/mro/librdf.sqlite) - (OS) improved SQLite RDF triple store for Redland librdf.
* [neptune](https://aws.amazon.com/neptune/) - ($) Amazon Neptune is a fast, reliable, fully managed graph database service that makes it easy to build and run applications that work with highly connected datasets.
* [RDFox](http://www.oxfordsemantic.tech/) - ($)
* [Fluree](https://docs.flur.ee/) - (OS) Blockchain based triplestore.
* [Triply](https://triply.cc) - (F/$)
* [Atomic-Server](https://crates.io/crates/atomic-server/) - (OS) Graph database + HTTP(S) server with authorization and versioning. Supports a strict subset of RDF.
* [RDF4j](https://rdf4j.org/) - (OS) Graph database supporting native, memory, LMDB, Solr, Elastic backends. Formerly known as Sesame.
* [Copernic](https://git.sr.ht/~amirouche/copernic) - (OS) Data, and its history, via change requests at scale.

### Academic

(Note: this classification is somewhat arbitrary and is meant to capture databases that only have a published paper or were developed for that purpose and are not actively maintained)

* [hyrise](https://github.com/hyrise/hyrise) ⭐ 870 | 🐛 97 | 🌐 C++ | 📅 2026-08-25 - Hyrise is a research in-memory database.
* [corese](https://github.com/Wimmics/corese) ⚠️ Archived - (OS).
* [gh-rdf3x](https://github.com/gh-rdf3x/gh-rdf3x) ⭐ 45 | 🐛 3 | 🌐 C++ | 📅 2013-08-16 - (OS).
* [TripleRush](https://github.com/uzh/triplerush) ⭐ 31 | 🐛 15 | 🌐 Scala | 📅 2016-10-17 - (OS).
* [DREAM](https://github.com/CMU-Q/DREAM) ⭐ 4 | 🐛 1 | 🌐 C | 📅 2016-01-20 - DREAM - Distributed RDF Engine with Adaptive Query Planner and Minimal Communication.
* [RIQ](https://github.com/UMKC-BigDataLab/RIQ) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2020-06-26 - RIQ is a new software tool for fast processing of SPARQL queries on RDF quadruples.
* [Qamel](https://github.com/dice-group/qamel) ⭐ 0 | 🐛 13 | 🌐 Java | 📅 2022-10-04 - RDF4J ported to Andriod.
* [rdf3x](https://code.google.com/archive/p/rdf3x/) - (OS).
* [rdf3x-mpi](https://bitbucket.org/saikrishnan/rdf3x-mpi)
* [dipLODocus](https://www.semanticscholar.org/paper/a1510214a16c73f464a8d1ae631054870114bbc8)
* [SW-Store](https://cs.uwaterloo.ca/~gweddell/cs848/papers/SW-Store.pdf)
* [Yars2](https://www.semanticscholar.org/paper/08bae32492f4f8a262ec990853613151cc484dc5)
* [Shard](https://sourceforge.net/projects/shard-3store/)
* [Hexastore](http://www.vldb.org/pvldb/1/1453965.pdf)
* [BitMat](https://www.cs.ox.ac.uk/people/medha.atre/papers/atre-ssws2009.pdf)
* [LUPOSDATE](https://www.ifis.uni-luebeck.de/index.php?id=luposdate-demo)

## SPARQL

### Streaming SPARQL

* [CSPARQL-engine](https://github.com/streamreasoning/CSPARQL-engine) ⭐ 40 | 🐛 19 | 🌐 Java | 📅 2023-12-16
* [sepa](https://github.com/arces-wot/SEPA) ⭐ 33 | 🐛 28 | 🌐 Java | 📅 2026-08-13 - A JAVA implementation of the SPARQL Event Processing Architecture including the engine, APIs and tools.
* [morph-streams](https://github.com/jpcik/morph-streams) ⭐ 16 | 🐛 2 | 🌐 Java | 📅 2016-09-28
* [morph](https://github.com/jpcik/morph) ⭐ 14 | 🐛 3 | 🌐 Scala | 📅 2014-10-19 - Sparql-stream sensor queries.
* [Linked Data Event Streams](https://semiceu.github.io/LinkedDataEventStreams/) - The [Linked Data Event Stream (LDES) server](https://github.com/Informatievlaanderen/VSDS-LDESServer4J) ⭐ 13 | 🐛 25 | 🌐 Java | 📅 2025-12-11 is a configurable component that can be used to ingest, store, transform and (re-)publish an LDES
* [StreamingMASSIF](https://github.com/IBCNServices/StreamingMASSIF) ⭐ 11 | 🐛 1 | 🌐 Java | 📅 2023-04-28
* [Triplewave](https://github.com/streamreasoning/TripleWave) ⭐ 9 | 🐛 14 | 🌐 JavaScript | 📅 2019-11-02
* [streaming-sparql](https://github.com/weblyzard/streaming-sparql) ⭐ 6 | 🐛 0 | 🌐 Java | 📅 2024-05-31
* [cqels](https://github.com/KMax/cqels) ⭐ 5 | 🐛 5 | 🌐 Java | 📅 2015-10-12
* [morph-web](https://github.com/jpcik/morph-web) ⭐ 3 | 🐛 0 | 🌐 HTML | 📅 2016-09-28
* [Katts](https://github.com/uzh/katts) ⭐ 0 | 🐛 1 | 🌐 Java | 📅 2016-03-09 - Katts is A Triple Torrent Sieve.
* [WAVES](https://www.waves-rsp.org/)
* [Strider](https://github.com/renxiangnan/strider)

### Federated SPARQL

ACTIVE

* [HeFQUIN](https://github.com/LiUSemWeb/HeFQUIN) ⭐ 35 | 🐛 34 | 🌐 Java | 📅 2026-08-25 - A query federation engine for heterogeneous federations of graph data sources.
* [CostFed](https://github.com/dice-group/CostFed) ⭐ 19 | 🐛 12 | 🌐 Java | 📅 2023-08-04
* [luposdate](https://github.com/luposdate/luposdate) ⭐ 19 | 🐛 6 | 🌐 Java | 📅 2022-09-01 - A Semantic Web Database Management System developed by IFIS at the University of Lübeck.
* [ANAPSID](https://github.com/anapsid/anapsid) ⭐ 17 | 🐛 2 | 🌐 Python | 📅 2017-09-13
* [anapsid](https://github.com/anapsid/anapsid) ⭐ 17 | 🐛 2 | 🌐 Python | 📅 2017-09-13 - An adaptive query processing engine for SPARQL endpoints.
* [SPARQLFederator](https://github.com/djogopatrao/SPARQLFederator) ⭐ 8 | 🐛 13 | 🌐 Java | 📅 2022-07-01
* [FedX](https://github.com/VeritasOS/fedx) ⭐ 8 | 🐛 3 | 📅 2020-04-24
* [rdffederator](https://github.com/goerlitz/rdffederator) ⭐ 7 | 🐛 2 | 🌐 Java | 📅 2015-03-24
* [HiBISCuS](https://github.com/AKSW/HiBISCuS) ⭐ 3 | 🐛 0 | 🌐 HTML | 📅 2019-05-28
* [Semagrow](https://github.com/semagrow)
* [QUETSAL](http://aksw.org/Projects/QUETSAL.html)
* [SPLENDID](http://ceur-ws.org/Vol-782/GoerlitzAndStaab_COLD2011.pdf)
* [Avalanche](http://www.ifi.uzh.ch/en/ddis/research/avalanche.html)

ARCHIVE - inactive projects or old academic projects that may lack soruce code

* [SemWIQ](https://sourceforge.net/projects/semwiq/)
* [DARQ](http://darq.sourceforge.net/)

### SPARQL Applications

* [QLever](https://github.com/ad-freiburg/QLever) ⭐ 886 | 🐛 391 | 🌐 C++ | 📅 2026-08-25 - Highly efficient query engine for SPARQL+Text.
* [YASGUI Triply fork](https://github.com/OpenTriply/YASGUI) ⚠️ Archived - Yet Another Sparql GUI.
* [d3sparql](https://github.com/ktym/d3sparql) ⭐ 192 | 🐛 11 | 🌐 HTML | 📅 2020-10-09 - JavaScript library for executing SPARQL query and transforming resulted JSON for visualization in D3.js.
* [d3-sparql](https://github.com/zazuko/d3-sparql/) ⭐ 121 | 🐛 3 | 🌐 JavaScript | 📅 2019-05-10 - Query a SPARQL endpoint with a SELECT query and get the data ready to be used with d3js
* [Trifid](https://github.com/zazuko/trifid) ⭐ 102 | 🐛 13 | 🌐 TypeScript | 📅 2026-08-25 - Lightweight Linked Data Server and Proxy
* [AutoSPARQL](https://github.com/AKSW/AutoSPARQL) ⭐ 98 | 🐛 15 | 🌐 Java | 📅 2023-09-05
* [pubby](https://github.com/cygri/pubby) ⚠️ Archived - A Linked Data frontend for SPARQL endpoints.
* [SNORQL](https://github.com/kurtjx/SNORQL) ⭐ 73 | 🐛 4 | 🌐 JavaScript | 📅 2016-04-01 - Ajaxy front-end for exploring triple stores.
* [Processor](https://github.com/AtomGraph/Processor) ⚠️ Archived - Ontology-driven Linked Data processor and server for SPARQL backends.
* [FlintSparqlEditor](https://github.com/TSO-Openup/FlintSparqlEditor) ⭐ 51 | 🐛 5 | 🌐 JavaScript | 📅 2012-10-16
* [Sparklis](https://github.com/sebferre/sparklis) ⭐ 51 | 🐛 3 | 🌐 OCaml | 📅 2025-08-09 - natural language query builder to explore and query endpoints with all the power of SPARQL yet without any knowledge of SPARQL.
* [SparqlProg](https://github.com/cmungall/sparqlprog) ⭐ 50 | 🐛 5 | 🌐 Prolog | 📅 2023-01-16 - composable SPARQL using logic programming
* [sparql-transformer](https://github.com/D2KLab/sparql-transformer) ⭐ 47 | 🐛 4 | 🌐 JavaScript | 📅 2026-08-07 - A generic JSON-LD transformer.
* [sparql-transformer](https://github.com/D2KLab/sparql-transformer) ⭐ 47 | 🐛 4 | 🌐 JavaScript | 📅 2026-08-07
* [SPARQL2NL](https://github.com/AKSW/SPARQL2NL) ⭐ 45 | 🐛 8 | 🌐 Java | 📅 2016-03-09
* [YASGUI.legacy](https://github.com/OpenTriply/YASGUI.legacy) ⭐ 44 | 🐛 13 | 🌐 JavaScript | 📅 2015-02-10
* [sage-engine](https://github.com/sage-org/sage-engine) ⭐ 44 | 🐛 2 | 🌐 Python | 📅 2024-10-03 - a SPARQL query engine for public Linked Data providers.
* [sparqled](https://github.com/sindice/sparqled) ⭐ 36 | 🐛 16 | 🌐 Java | 📅 2014-06-18
* [SEPA](https://github.com/arces-wot/SEPA) ⭐ 33 | 🐛 28 | 🌐 Java | 📅 2026-08-13 - A JAVA implementation of the SPARQL Event Processing Architecture including the engine, APIs and tools.
* [YASGUI Matdata fork](https://github.com/Matdata-eu/yasgui) ⭐ 30 | 🐛 18 | 🌐 TypeScript | 📅 2026-06-25 - Yet Another Sparql GUI - Has more features, bugfixes and upgraded dependencies compared to Zazuko and Triply forks.
* [jdbc4sparql](https://github.com/Claudenw/jdbc4sparql) ⭐ 25 | 🐛 4 | 🌐 Java | 📅 2017-12-15 - A JDBC driver that takes data from SPARQL endpoints or RDF graphs.
* [squebi](https://github.com/tkurz/squebi) ⭐ 22 | 🐛 2 | 🌐 JavaScript | 📅 2015-05-27 - Squebi is a SPARQL editor and SPARQL result visualizer.
* [vec2sparql](https://github.com/bio-ontology-research-group/vec2sparql) ⭐ 15 | 🐛 4 | 🌐 Java | 📅 2022-12-08 - Translate vector embeddings to SPARQL queries.
* [reactive-sparql](https://github.com/modelfabric/reactive-sparql) ⭐ 14 | 🐛 1 | 🌐 Scala | 📅 2023-09-18
* [sparqlab](https://github.com/jindrichmynarz/sparqlab) ⭐ 12 | 🐛 3 | 🌐 Clojure | 📅 2022-01-16 - Lab for exercising SPARQL.
* [spanqit](https://github.com/anqit/spanqit) ⭐ 12 | 🐛 0 | 🌐 Java | 📅 2024-04-13 - Java-based SPARQL query generator.
* [asqc](https://github.com/gklyne/asqc) ⭐ 11 | 🐛 1 | 🌐 Python | 📅 2022-07-14 - SPARQL query client (pronounced "ask").
* [visu](https://github.com/jiemakel/visu) ⭐ 11 | 🐛 0 | 🌐 LiveScript | 📅 2016-02-26 - Visual SPARQL query tool.
* [antlr-sparql-grammar](https://github.com/rollxx/antlr-sparql-grammar) ⭐ 10 | 🐛 1 | 📅 2010-11-05
* [SPARQL2Git](https://github.com/albertmeronyo/SPARQL2Git) ⭐ 7 | 🐛 4 | 🌐 HTML | 📅 2017-03-16 - Easily store and curate SPARQL queries (and their associated Linked Data APIs) in GitHub.
* [snap-sparql-query](https://github.com/protegeproject/snap-sparql-query) ⭐ 7 | 🐛 21 | 🌐 Java | 📅 2018-07-25
* [SPARQL-parser](https://github.com/tenforce/SPARQL-parser) ⭐ 6 | 🐛 0 | 🌐 Java | 📅 2016-10-24
* [datastudio-sparql-connector](https://github.com/DataFabricRus/datastudio-sparql-connector) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2019-01-10 - SPARQL Connector for Google Data Studio.
* [odata2sparql](https://github.com/peterjohnlawrence/com.inova8.odata2sparql.v4) ⭐ 5 | 🐛 39 | 🌐 Java | 📅 2022-12-10 - An OData proxy server that takes data from SPARQL endpoints or RDF graphs and publishes as OData V4 endpoint.
* [SparqlAnalytics](https://github.com/AKSW/SparqlAnalytics) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2013-04-03
* [SAFE](https://github.com/yasarkhangithub/SAFE) ⭐ 5 | 🐛 0 | 🌐 Java | 📅 2025-02-17
* [zeppelin-sparql](https://github.com/nick-manasys/zeppelin-sparql) ⭐ 3 | 🐛 0 | 📅 2017-08-27 - Zeppelin sparql interpreter.
* [sparql-proxy](https://github.com/clarkparsia/sparql-proxy) ⚠️ Archived
* [Sparql-cli](https://github.com/lambdamusic/Sparql-cli) ⚠️ Archived - Command line API for SPARQL.
* [SPARQL2vec](https://github.com/albertmeronyo/SPARQL2vec) ⭐ 1 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2019-01-08 - SPARQL query embeddings for predictive Knowledge Graph querying models.
* [fluent-sparql](https://github.com/stoewer/fluent-sparql) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2015-04-27
* [lens2odata](https://github.com/peterjohnlawrence/com.inova8.lens.framework.v4) - A GUI for discovery, search, and graph of RDF sources.
* [sparql2xquery](https://github.com/marklogic/sparql2xquery) - SPARQL to XQuery Translator for use with MarkLogic Semantic Toolkit.
* [decentsparql](https://github.com/itm/decentsparql)
* [YASGUI Zazuko fork](\[https://github.com/Matdata-eu/yasgui]\(https://github.com/zazuko/Yasgui\)) - Yet Another Sparql GUI - Has bugfixes and upgraded dependencies compared to Triply fork.
* [Porthole](https://itunes.apple.com/us/app/porthole/id984035787) - Mac SPARQL editor and client.
* [LinkedDataHub](https://atomgraph.github.io/LinkedDataHub/) - SPARQL-powered Knowledge Graph management system.
* [SparqlBlocks](http://sparqlblocks.org/) - Build SPARQL queries with blocks
* [json-rql](https://json-rql.org/) - SPARQL with a JSON-LD super-set syntax (like GraphQL for the semantic web)

## Benchmarks

* [IGUANA](https://github.com/dice-group/IGUANA) ⭐ 25 | 🐛 33 | 🌐 Java | 📅 2026-08-13
* [IGUANA](https://github.com/AKSW/IGUANA) ⭐ 25 | 🐛 33 | 🌐 Java | 📅 2026-08-13 - IGUANA is a benchmark execution framework for triple stores.
* [GTFS-Madrid-Bench](https://github.com/oeg-upm/gtfs-bench) ⭐ 22 | 🐛 6 | 🌐 Python | 📅 2025-03-20 - A benchmark for performance and scalability of knowledge graph construction from heterogeneous data sources
* [FedShop](https://github.com/GDD-Nantes/FedShop) ⭐ 10 | 🐛 18 | 🌐 Jupyter Notebook | 📅 2026-08-01 - A Benchmark for Testing the Scalability of SPARQL Federation Engines
* [TFT](https://github.com/BorderCloud/TFT) ⭐ 8 | 🐛 1 | 🌐 PHP | 📅 2021-05-14 - TFT (Tester for Triplestore) is a script PHP to pass tests through a SPARQL service.
* [GeoSPARQL Compliance Benchmark](https://github.com/OpenLinkSoftware/GeoSPARQLBenchmark) ⭐ 8 | 🐛 1 | 🌐 Java | 📅 2026-06-30 - A HOBBIT benchmark to check for the GeoSPARQL compliance of triple store implementations
* [LUBM4OBDA](https://github.com/oeg-upm/LUBM4OBDA) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2025-10-16 - A benchmark for OBDA systems with inference and meta Knowledge
* [RDF Library Benchmark](https://github.com/KonradHoeffner/rdf_benchmark) ⭐ 4 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2025-11-03 - Comparison of HDT and non-HDT RDF libraries for query time and memory usage.
* [SRBench](https://github.com/jpcik/srbench) ⭐ 0 | 🐛 0 | 🌐 Scala | 📅 2014-02-12 - A streaming sparql benchmark.
* [Berlin SPARQL Benchmark (BSBM)](http://wifo5-03.informatik.uni-mannheim.de/bizer/berlinsparqlbenchmark/)
* [Lehigh University Benchmark (LUBM)](http://swat.cse.lehigh.edu/projects/lubm/)
* [dice-group/triplestore-benchmarks](https://web.archive.org/web/20180627155808/https://github.com/dice-group/triplestore-benchmarks) - An Evaluation of Triplestore Benchamrks.
* [RdfStoreBenchmarking](https://www.w3.org/wiki/RdfStoreBenchmarking)
* [Hobbit](http://project-hobbit.eu/) - Holistic Benchmarking of Big Linked Data.
* [SP2Bench](http://dbis.informatik.uni-freiburg.de/index.php?project=SP2B)
* [OTM Benchmark](https://kbss.felk.cvut.cz/web/kbss/otm-benchmark) - A benchmark of object-triple mapping (OTM) libraries.
* [LDBC](http://ldbcouncil.org/benchmarks)
* [RiverBench](https://w3id.org/riverbench) – open and collaborative benchmark suite for streaming and non-streaming RDF systems.

## GraphQL

* [Grasp](https://github.com/dbcls/grasp) ⭐ 43 | 🐛 12 | 🌐 TypeScript | 📅 2026-03-07 - GraphQL endpoint wrapping SPARQL endpoints, declarative approach using [handlebars](https://handlebarsjs.com/guide/) Templates for SPARQL queries
* [semantic-graphql](https://github.com/nelson-ai/semantic-graphql) ⚠️ Archived - Create GraphQL schemas from RDF ontologies.
* [UltraGraphQL](https://github.com/internet-of-production/UltraGraphQL) ⭐ 9 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-05-10 - extends HyperGraphQL with automatic bootstrapping phase and GraphQL mutations
* [hypergraphql](https://github.com/semantic-integration/hypergraphql) - GraphQL interface for querying and serving linked data on the Web.

## Linked Data Fragments

* [LDFlex](https://github.com/RubenVerborgh/LDflex) ⭐ 196 | 🐛 37 | 🌐 JavaScript | 📅 2026-08-24 - A JavaScript DSL for querying Linked Data on the Web.
* [HeFQUIN](https://github.com/LiUSemWeb/HeFQUIN) ⭐ 35 | 🐛 34 | 🌐 Java | 📅 2026-08-25 - A query federation engine for heterogeneous federations of graph data sources.
* [tomayac/ldf-client](https://github.com/tomayac/ldf-client) ⭐ 18 | 🐛 0 | 🌐 HTML | 📅 2016-07-31 - Polymer Linked Data Fragments client.
* [Linked Data Fragments](http://linkeddatafragments.org/)
* [comunica](http://comunica.linkeddatafragments.org/) - A modular framework for querying Linked Data on the Web.

## Linked Data Platform (LDP)

* [gold](https://github.com/linkeddata/gold) ⭐ 152 | 🐛 33 | 🌐 Go | 📅 2020-07-21 - Linked Data server for Go.
* [trellis](https://github.com/trellis-ldp/trellis) ⭐ 110 | 🐛 11 | 🌐 Java | 📅 2025-05-19
* [warp](https://github.com/linkeddata/warp) ⭐ 59 | 🐛 18 | 🌐 CSS | 📅 2018-10-25 - Warp an LDP file manager.
* [Marmotta](https://github.com/apache/marmotta) ⚠️ Archived - Apache linked data platform implementation.
* [Elda](https://github.com/epimorphics/elda) ⭐ 57 | 🐛 24 | 🌐 Java | 📅 2026-08-04 - Linked data platform from Epimorphics.
* [LDP4j](https://github.com/ldp4j/ldp4j) ⭐ 46 | 🐛 5 | 🌐 Java | 📅 2020-12-01
* [cavendish](https://github.com/cavendish-ldp/cavendish) ⭐ 26 | 🐛 12 | 🌐 Java | 📅 2017-10-31 - A LDP Implementation backed by BlazeGraph.
* [ldpserver](https://github.com/hectorcorrea/ldpserver) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2016-09-14 - A mini LDP Server written in Go.
* [ldp-coap-framework](https://github.com/sisinflab-swot/ldp-coap-framework) ⭐ 7 | 🐛 1 | 🌐 Java | 📅 2023-04-14 - Linked Data Platform for the Constrained Application Protocol
* [fedora](https://duraspace.org/fedora/) - Repository platform with native linked data support.
* [CarbonLDP](https://github.com/CarbonLDP) - ($)
* [Metreeca/link](https://github.com/metreeca/link)
* [Prez](https://prez.dev) - (OS) a semi-LDP implementation, base on the W3C's [Content Negotation By Profile](https://www.w3.org/TR/dx-prof-conneg/) API

## Ecosystem

### Conferences

* [4th U.S. Semantic Technologies Symposium 2022](https://us2ts.org/)
* [International Conference on Biomedical Ontology 2022](https://icbo-conference.github.io/icbo2022/)
* [International Semantic Web Conference (ISWC 2019)](http://iswc2019.semanticweb.org)
* [European Semantic Web Conference (ESWC 2019)](https://2019.eswc-conferences.org)
* [US2TS -- U.S. Semantic Technologies Symposium](http://us2ts.org)
* [KGC - The Knowledge Graph Conference](https://www.knowledgegraph.tech)

### Blogs

* [Justin's Weblog](https://github.com/justin2004/weblog#readme) ⭐ 58 | 🐛 0 | 🌐 Common Lisp | 📅 2026-04-14
* [TerminusDB Technical Blogs](https://github.com/terminusdb/technical-blogs) ⭐ 47 | 🐛 1 | 📅 2023-06-01
* [Bob DuCharme's weblog technology for representing and linking information](http://www.snee.com/bobdc.blog/)
* [Planet RDF](http://planetrdf.com)
* [Jörn's Blog](https://joernhees.de/blog/)
* [Ontola Linked Data Blog](https://ontola.io/blog)
* [Semantic Arts Data-Centric Architecture blog](https://www.semanticarts.com/blog/)

### Groups

* [RDF-DEV](https://www.w3.org/community/rdf-dev/) - RDF-DEV COMMUNITY GROUP.
* [w3c semantic web](https://lists.w3.org/Archives/Public/semantic-web/)
* [JSON-LD Working Group](https://www.w3.org/2018/json-ld-wg/)
* [w3c activities](https://www.w3.org/Consortium/activities)
* [KG-Construction](https://www.w3.org/community/kg-construct/) - KG-Construction W3C Community Group

## Knowledge Graph Management

$ - Proprietary
OS - OpenSource

* [OntoWiki](https://github.com/AKSW/OntoWiki) ⚠️ Archived - (OS) Semantic data wiki as well as Linked Data publishing engine.
* [Atomic Data Browser](https://github.com/joepio/atomic-data-browser) ⭐ 62 | 🐛 100 | 🌐 TypeScript | 📅 2023-07-31 - (OS) Create, model, edit, view and share Linked Data.
* [Metaphacts](http://metaphacts.com) - ($) End-to-end platform to create and utilize enterprise knowledge graphs.
* [GNOSS-Sherlock](https://www.gnoss.com/en/semantic-framework/knowledge-graph-management) - ($) Cognitive Intelligence tool for machines to understand us.
* [Wikibase](http://wikiba.se) - (OS) Collection of applications and libraries for creating, managing and sharing structured data.
* [eccenca Corporate Memory](https://www.eccenca.com) - Build, explore and consume Knowledge Graphs.
* [Blue Brain Nexus](https://bluebrainnexus.io/) - (OS) A knowledge graph for data-driven science

## Web Annotations

* [anno4j](https://github.com/anno4j/anno4j) ⭐ 50 | 🐛 30 | 🌐 Java | 📅 2019-01-23
* [annotation model](https://www.w3.org/TR/annotation-model/)

## Mapping

* [Karma](https://github.com/usc-isi-i2/Web-Karma) ⚠️ Archived - Transform data expressed in multiple data formats into RDF.
* [RMLMapper](https://github.com/RMLio/rmlmapper-java) ⭐ 202 | 🐛 62 | 🌐 Java | 📅 2026-02-17 - Java-based RML Processor for transforming heterogeneous data into RDF.
* [RMLStreamer](https://github.com/RMLio/rmlmapper-java) ⭐ 202 | 🐛 62 | 🌐 Java | 📅 2026-02-17 - Flink-based RML Processor for transforming heterogeneous data into RDF in a streaming fashion.
* [pyrdb2rdf](https://github.com/nisavid/pyrdb2rdf) ⚠️ Archived
* [any2rdf](https://github.com/esbranson/any2rdf) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2013-08-18
* [triplify](https://github.com/pebbie/triplify) ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2013-11-25
* [G2GML](https://g2gml.readthedocs.io/en/latest/contents/get-started.html) - Map RDF graphs to property graphs and output pg, json-pg, neo4j, pgx, aws or dot formats
* [xsparql](https://www.w3.org/Submission/xsparql-language-specification/)
* [triplify-csv](https://pypi.org/project/triplify-csv/) - CLI and Python package to generate triples or nquads from CSV files and a configuration file.
* [Mapeathor](https://morph.oeg.fi.upm.es/tool/mapeathor) - Definition of Excel-based mappings and translation to \[R2]RML mappings
* [RMLEditor](https://app.rml.io/rmleditor/) - Community Edition of the RML Editor to create RML mappings in a visual way.
* [ShExML](http://shexml.herminiogarcia.com/) - Shape Expressions Mapping Language. Map heterogeneous data via Shape Expression (ShEx).
* [ReDeFer XSD2OWL](https://rhizomik.net/redefer/xsd2owl) - Map XSD XML Schemas into the Web Ontology Language (OWL).
* [ReDeFer XML2RDF](https://rhizomik.net/redefer/xml2rdf) - Map XML into RDF.
* [Silk](http://silkframework.org/) - Linked data integration framework, connectes different linked data resources and transforms structured data source.
* [KOMMA](https://komma.enilink.net/) - Framework for mapping RDF data to Java objects using annotations, enabling object-oriented interaction with RDF models.

### Geo

* [TripleGeo](https://github.com/GeoKnow/TripleGeo) ⭐ 37 | 🐛 9 | 🌐 Java | 📅 2024-04-19 - TripleGeo utility for converting geospatial data into triples.
* [GeoSPARQL DGGS](https://github.com/RDFLib/geosparql-dggs) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2021-10-31 - An RDFlib-based SPARQL extensions library for [Discrete Global Grid Systems](https://en.wikipedia.org/wiki/Discrete_global_grid) geospatial data
* [geometry2rdf](https://github.com/boricles/geometry2rdf) ⭐ 3 | 🐛 7 | 🌐 Java | 📅 2014-03-11
* [GeoSPARQL](https://opengeospatial.github.io/ogc-geosparql/) - Major Open Geospatial Consortium Semantic Web spatial data stadard

### Excel

* [TabLinker](https://github.com/Data2Semantics/TabLinker) ⭐ 40 | 🐛 19 | 🌐 Python | 📅 2014-03-17
* [xlwrap](https://github.com/sidewinderlabs/xlwrap) ⭐ 12 | 🐛 5 | 🌐 Java | 📅 2011-08-02
* [VocExcel](https://github.com/surroundaustralia/VocExcel) - A Excel -> SKOS RDF tool, based on RDFlib

### CSV/Tabular

* [tarql](https://github.com/tarql/tarql) ⭐ 207 | 🐛 48 | 🌐 Java | 📅 2023-11-02
* [csv2rdf4lod-automation](https://github.com/timrdf/csv2rdf4lod-automation) ⭐ 112 | 🐛 275 | 🌐 Java | 📅 2021-12-13
* [CSV2RDF](https://github.com/AtomGraph/CSV2RDF) ⭐ 62 | 🐛 2 | 🌐 Java | 📅 2026-07-05 - Streaming, transforming, SPARQL-based CSV to RDF converter
* [COW](https://github.com/CLARIAH/COW) ⭐ 48 | 🐛 25 | 🌐 Python | 📅 2024-05-06 - CSV On the Web (CSVW) converter.
* [CSV2RDF](https://github.com/clarkparsia/csv2rdf) ⚠️ Archived - CSV to RDF mapper.
* [guide-o-matic](https://github.com/baskaufs/guid-o-matic) ⭐ 12 | 🐛 1 | 🌐 XQuery | 📅 2018-12-08 - Xquery scripts to convert fielded text (CSV) files to RDF serialized as XML, Turtle, and JSON-LD.
* [tarql-component](https://github.com/opencube-toolkit/tarql-component) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2015-10-20
* [csv2rdf](https://github.com/notruthless/csv2rdf) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2012-09-25
* [Morph-CSV](https://morph.oeg.fi.upm.es/tool/morph-csv) - Exploitation of RML+FnO and CSVW for ensuring the effectiveness of SPARQL-to-SQL systems.

### Object to RDF Mapping

* [Empire](https://github.com/mhgrove/Empire/) ⭐ 102 | 🐛 29 | 🌐 Java | 📅 2020-03-26 - JPA implementation for RDF
* [Pinto](https://github.com/stardog-union/pinto) ⭐ 44 | 🐛 18 | 🌐 Java | 📅 2019-12-13 - A lightweight framework for mapping Java Beans into RDF and back again
* [surfrdf](https://github.com/cosminbasca/surfrdf) ⭐ 44 | 🐛 21 | 🌐 Python | 📅 2021-10-22 - SuRF: a python Object RDF Mapper (ORM).
* [JOPA](https://github.com/kbss-cvut/jopa) ⭐ 44 | 🐛 23 | 🌐 Java | 📅 2026-08-13 - A Java object-triple mapping library for RDF4J, Jena and OWL API.
* [PA4RDF](https://github.com/Claudenw/PA4RDF) ⭐ 12 | 🐛 4 | 🌐 Java | 📅 2026-08-19 - functionality on top of an RDF store while accounting for and exploiting the fundamental differences between graph storage and relational storage.
* [RomanticWeb](https://github.com/MakoLab/RomanticWeb) ⭐ 12 | 🐛 23 | 🌐 HTML | 📅 2018-12-12 - RDF-Object Mapping for the Semantic Web.
* [rdfbeans](https://github.com/cyberborean/rdfbeans) ⭐ 11 | 🐛 15 | 🌐 Java | 📅 2024-10-01
* [XML2RDF-DataTransformation-MappingTool](https://github.com/isl/XML2RDF-DataTransformation-MappingTool) ⭐ 7 | 🐛 0 | 🌐 Java | 📅 2012-12-04 - XML2RDF Data Transformation Tool (Mapping Tool): This generic data transformation tool maps XML data files to RDF files, given a schema matching definition, based on this Mapping Language Schema.
* [Som(m)er](https://github.com/bblfish/sommer) ⚠️ Archived - Semantic Object (Metadata) MappER
* [jtriple](https://github.com/konradreiche/jtriple) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2025-12-12 - A Java object model binding for RDF.
* [sparql-template](https://github.com/gushakov/sparql-template) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2017-02-06 - RDF store traversal with Jena API via automatic mapping between POJO and SPARQL.
* [java2rdf](https://github.com/EBIBioSamples/java2rdf) - A simple library to map Java objects and Java beans onto RDF/OWL
* [jennabean](https://code.google.com/p/jenabean/)
* [Alibaba](https://bitbucket.org/openrdf/alibaba)

### RDB to RDF

* [d2rq](https://github.com/d2rq/d2rq) ⚠️ Archived - Database to RDF mapping engine and SPARQL server.
* [Sparqlify](https://github.com/AKSW/Sparqlify) ⭐ 135 | 🐛 53 | 🌐 Java | 📅 2024-10-11 - Sparql -> SQL Rewriter enabling virtual RDB -> RDF mappings.
* [quetzal](https://github.com/Quetzal-RDF/quetzal) ⭐ 107 | 🐛 8 | 🌐 Java | 📅 2022-12-12 - SPARQL to SQL translation engine for multiple backends, such as DB2, PostgreSQL and Apache Spark.
* [Sparqlify-Extendsions](https://github.com/AKSW/Sparqlify-Extensions) ⚠️ Archived - Extension projects for Sparqlify.

### RDF to Property Graphs

* [sparql-gremlin](https://github.com/apache/tinkerpop/tree/master/sparql-gremlin) ⭐ 2,144 | 🐛 28 | 🌐 Java | 📅 2026-08-22 - SPARQL to Gremlin Translator available as a plugin of the popular Apache TinkerPop graph computing framework.
* [Gremlinator](https://github.com/LITMUS-Benchmark-Suite/sparql-to-gremlin/) ⭐ 90 | 🐛 3 | 🌐 HTML | 📅 2021-04-26 - SPARQL to Gremlin standalone Translator available as an independent implementation for open use in custom use cases.

### XML

* [ontmalizer](https://github.com/srdc/ontmalizer) ⭐ 85 | 🐛 12 | 🌐 Java | 📅 2021-09-20 - Comprehensive transformations of XML Schemas (XSD) and XML data to RDF/OWL automatically.

#### R2RML

* [ontop](https://github.com/ontop/ontop) ⭐ 924 | 🐛 106 | 🌐 Java | 📅 2026-07-13 - Ontop is a platform to query relational databases as Virtual RDF Graphs using SPARQL. It's fast and is packed with features.
* [Morph-KGC](https://github.com/oeg-upm/morph-kgc) ⭐ 289 | 🐛 30 | 🌐 Python | 📅 2026-06-28 - An R2RML engine that creates large knowledge graphs from RDB.
* [RMLMapper](https://github.com/RMLio/rmlmapper-java) ⭐ 202 | 🐛 62 | 🌐 Java | 📅 2026-02-17 - Java-based RML Processor backwards compatible with R2RML.
* [R2RML-Parser](https://github.com/nkons/r2rml-parser) ⭐ 74 | 🐛 19 | 🌐 Java | 📅 2022-06-21 - An R2RML implementation that can export relational database contents as RDF graphs.
* [rdf2rml](https://github.com/VladimirAlexiev/rdf2rml) ⭐ 59 | 🐛 20 | 🌐 Perl | 📅 2026-07-28 - R2RML Generation from simple examples.
* [R2RML-F](https://github.com/chrdebru/r2rml) ⭐ 37 | 🐛 2 | 🌐 Java | 📅 2025-12-19
* [MusicBrainz-R2RML](https://github.com/LinkedBrainz/MusicBrainz-R2RML) ⭐ 32 | 🐛 5 | 🌐 Shell | 📅 2019-04-02 - R2RML mappings for the MusicBrainz schema.
* [pyrdb2rdf](https://github.com/nisavid/pyrdb2rdf) ⚠️ Archived - A Python library for RDB2RDF Direct Mapping and R2RML.
* [Map-On](https://github.com/arc-lasalle/Map-On) ⭐ 22 | 🐛 0 | 🌐 JavaScript | 📅 2019-01-28 - A web-based editor for visual ontology mapping for R2RML documents.
* [sparqlmap](https://github.com/tomatophantastico/sparqlmap) ⭐ 19 | 🐛 16 | 🌐 JavaScript | 📅 2021-05-13
* [R2RML-api](https://github.com/R2RML-api/R2RML-api) ⭐ 14 | 🐛 3 | 🌐 Java | 📅 2024-01-24
* [R2RML-kit](https://github.com/d2rq/r2rml-kit) ⚠️ Archived
* [AutoMap4OBDA](https://github.com/arc-lasalle/AutoMap4OBDA) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2016-10-11 - AutoMap4OBDA: Automated Generation of R2RML Mappings for OBDA.
* [Ontopic Studio](https://ontopic.ai/en/ontopic-studio) - ($) Ontopic Studio is a GUI driven no-code application for designing standards compliant large R2RML mappings usable for Virtual RDF Graphs and RDF triple materialization. Academics can request free licenses.
* [db2triples](https://github.com/antidot/db2triples) - Antidot implementations of R2RML and Direct Mapping specifications.
* [Juma](https://opengogs.adaptcentre.ie/crottija/juma-r2rml/) - Juma, jigsaw puzzles for representing mapping, is a method that applies the block metaphor to mapping languages.
* [ultrawrap](https://capsenta.com/) - ($)

##### xR2RML

* [morph-xr2rml](https://github.com/frmichel/morph-xr2rml) ⭐ 25 | 🐛 6 | 🌐 Scala | 📅 2025-07-02
* [XR2RML](https://github.com/djimloic/XR2RML)

##### R2RML-F

* [R2RML-F](https://github.com/chrdebru/r2rml) ⭐ 37 | 🐛 2 | 🌐 Java | 📅 2025-12-19
* [paper](http://events.linkeddata.org/ldow2016/papers/LDOW2016_paper_14.pdf)

#### RML

* [Morph-KGC](https://github.com/oeg-upm/morph-kgc) ⭐ 289 | 🐛 30 | 🌐 Python | 📅 2026-06-28 - RML and RML-star engine that creates large knowledge graphs from heterogeneous data sources
* [SDM-RDFizer](https://github.com/SDM-TIB/SDM-RDFizer) ⭐ 139 | 🐛 3 | 🌐 Python | 📅 2026-07-31 - RML engine for efficient transformation of CSV, RDB, XML and JSON to RDF
* [CARML](https://github.com/carml/carml) ⭐ 114 | 🐛 24 | 🌐 Java | 📅 2026-08-24 - CARML RML engine for mapping CSV, XML and JSON files to RDF
* [RocketRML](https://github.com/semantifyit/RocketRML) ⭐ 28 | 🐛 16 | 🌐 JavaScript | 📅 2026-02-04
* [FuMap](https://github.com/SDM-TIB/FunMap) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2024-10-24 - Efficient preprocessing of transformation rules described in RML+FnO mappings.
* [RML](https://github.com/RMLio) - RDF Mapping language for mapping JSON, CSV and XML to RDF.

#### Other RDF Mappings

* [SPARQL Anything](https://github.com/SPARQL-Anything/sparql.anything) ⭐ 306 | 🐛 58 | 🌐 Java | 📅 2026-08-25 - A system for Semantic Web [re-engineering](https://arxiv.org/pdf/2106.02361.pdf) that allows users to query anything with SPARQL.
* [sparql-generate](https://github.com/sparql-generate/sparql-generate) ⭐ 71 | 🐛 21 | 🌐 HTML | 📅 2026-08-08
* [mapping-template](https://github.com/cefriel/mapping-template) ⭐ 9 | 🐛 18 | 🌐 Java | 📅 2026-06-29 - A template-based component exploiting Apache Velocity to define mappings to/from RDF.
* [any23](https://any23.apache.org/) - was "[moved into the Attic in 2023-06](https://attic.apache.org/projects/any23.html)"
* [J2RM](https://w3id.org/kgcp/J2RM/) - A tool to process mappings from JSON data to RDF triples guided by an OWL2 ontology structure.

## Ontologies

* [LOV](https://lov.linkeddata.es) - Linked Open Vocabularies. Portal / search tool for vocabularies.
* [BioPortal](https://bioportal.bioontology.org) - Open repository with tools for ontologies and SKOS vocabularies; biomedical content dominates but all research domains welcome
* [prefix.zazuko.com](https://prefix.zazuko.com) - Similar to LOV, but with a richer search interface
* [Ontology Lookup Service (OLS)](https://www.ebi.ac.uk/ols/index) - OLS is a repository for biomedical ontologies that aims to provide a single point of access to the latest ontology versions.
* [OntoPortal](https://ontoportal.org) - The BioPortal software in Virtual Appliance (deployable) form
* [gist](https://www.semanticarts.com/gist/) - minimalist enterprise upper ontology - max coverage, fewest primitives, least ambiguity.
* [Plow](https://plow.pm) - Ontology package manager with semantic versioning and an [open domain-agnostic ontology registry that anyone can publish to](https://registry.field33.com).
* [BE-OLS](https://cyberbuildlab.github.io/BE-OLS/) - Build Environment Ontology Lookup Service: an open repository and website of more than 140 built environment-related ontologies

### World Wide Web Consortium (W3C)

* [WGS84](https://www.w3.org/2003/01/geo/) - Basic Geo (WGS84 lat/long) Vocabulary.
* [skos](http://www.w3.org/2004/02/skos/core.html) - SKOS Simple Knowledge Organization System.
* [skos-xl](http://www.w3.org/TR/skos-reference/skos-xl.html) - SKOS Simple Knowledge Organization System eXtension for Labels.
* [vcard](https://www.w3.org/TR/vcard-rdf/) - vCard Ontology - for describing People and Organizations.
* [void](https://www.w3.org/TR/void/) - Describing Linked Datasets with the VoID Vocabulary.
* [time](https://w3c.github.io/sdw/time/) - Time Ontology in OWL.
* [org](https://www.w3.org/TR/vocab-org/) - The Organization Ontology.
* [data-cube](https://www.w3.org/TR/vocab-data-cube) - The RDF Data Cube Vocabulary.
* [pim](https://www.w3.org/2000/10/swap/pim/contact)
* [dqv](http://www.w3.org/ns/dqv#) - Vocabulary for describing quality metadata.
* [prov-o](https://www.w3.org/TR/prov-o/) - Represent provenance information.
* [dcat](https://www.w3.org/TR/vocab-dcat/) - DCAT is an RDF vocabulary designed to facilitate interoperability between data catalogs published on the Web.
* [prof](https://w3c.github.io/dxwg/profilesont/) The Profiles Ontology is an RDF vocabulary to describe profiles of (one or more) standards for information resources.
* [odrl-model](https://www.w3.org/TR/odrl-model/) ODRL Policy Information Model V2.2 and [odrl-vocab](https://www.w3.org/TR/odrl-vocab/) ODRL Vocabulary & Expression V2.2

### European Commission

* [Core Vocabularies](https://joinup.ec.europa.eu/collection/semantic-interoperability-community-semic/core-vocabularies) - Vocabularies developed for/by public administrations.

### Community

* [doap](https://github.com/edumbill/doap) ⭐ 287 | 🐛 21 | 🌐 C# | 📅 2024-06-11 - RDF schema for describing software projects.
* [Hydra](https://github.com/lanthaler/Hydra) ⭐ 96 | 🐛 0 | 🌐 JavaScript | 📅 2015-06-24 - A lightweight vocabulary for hypermedia-driven Web APIs.
* [cyber-ontology](https://github.com/daedafusion/cyber-ontology) ⭐ 58 | 🐛 0 | 📅 2017-03-17 - Cyber Intelligence Ontology.
* [qb4olap](https://github.com/lorenae/qb4olap) ⭐ 8 | 🐛 0 | 📅 2018-10-16 - A Vocabulary for Business Intelligence over Linked Data.
* [ssso](https://github.com/gbv/ssso) ⭐ 4 | 🐛 4 | 📅 2014-06-30 - Specification of Simple Service Status Ontology.
* [orderedlistonto](https://github.com/smiy/orderedlistonto) ⚠️ Archived - The Ordered List Ontology.
* [dso](https://github.com/gbv/dso) ⭐ 2 | 🐛 9 | 🌐 Makefile | 📅 2015-12-09 - Specification of Document Service Ontology.
* [vocab-transit](https://github.com/wwaites/vocab-transit) ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2012-01-25 - RDF Schema for transit data.
* [foaf](http://www.foaf-project.org/) - Friend of a Friend (FOAF) ontology.
* [uberon](http://uberon.github.io) - Integrated cross-species ontology covering anatomical structures in animals.
* [juso-ontology](http://rdfs.co/juso/latest/html) - Vocabulary for describing geographical addresses and features.
* [obo-relations](http://obofoundry.org/ontology/ro.html) - Relation Ontology. Relationship types shared across multiple ontologies.
* [evidenceontology](http://evidenceontology.org) - EVIDENCE & CONCLUSION ONTOLOGY.
* [bevon](http://rdfs.co/bevon/latest/html) - Beverage ontology.
* [schema.org](https://schema.org/docs/datamodel.html) - Structured data on the Internet (Google, Microsoft, Yahoo and Yandex).
* [SPAR](http://www.sparontologies.net) - Semantic Publishing and Referencing Ontologies.
* [BFO](http://basic-formal-ontology.org) - Basic Formal Ontology.
* [CCO](https://github.com/CommonCoreOntology/) - Common Core Ontology Suite.
* [TOVE](http://www.eil.utoronto.ca/theory/enterprise-modelling/tove/) - Toronto Virtual Enterprise Ontologies.
* [VIVO ISF](https://wiki.duraspace.org/display/VTDA/VIVO-ISF+Ontology) - Researchers and the full context in which they work.
* [yago](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/yago/) YAGO is a huge semantic knowledge base, derived from Wikipedia WordNet and GeoNames.
* [dbpedia](http://dbpedia.org/ontology/)

### Educational

* [MMOntologies](https://github.com/gatemezing/MMOntologies) ⭐ 3 | 🐛 0 | 📅 2024-03-17 - Multimedia ontologies studied for the paper "The Landscape of Multimedia Ontologies in the last Decade".
* [Wine](https://www.quora.com/What-is-wine-ontology) - Wine Ontology is a popular example of an OWL ontology.
* [Pizza](http://owl.cs.manchester.ac.uk/publications/talks-and-tutorials/protg-owl-tutorial/) - A step-by-step guide to modelling in OWL using the popular Protégé OWL tools.
  * [New Pizza](https://www.michaeldebellis.com/post/new-protege-pizza-tutorial) - An updated version of the well established pizza ontology tutorial covering Protégé 5+ as well as WebProtégé and introduces SHACL shapes.
* [W3C Best Practices for Publishing Linked Data](https://www.w3.org/TR/ld-bp/)
* [Coursera - Web of Data](https://www.coursera.org/learn/web-data/) - A joint initiative between EIT Digital, Université de Nice Sophia-Antipolis / Université Côte d'Azur and INRIA - introduces the Linked Data standards and principles that provide the foundation of the Semantic web.
* [Linked Data Patterns](http://patterns.dataincubator.org/book/index.html)
* [OBO Academy](https://oboacademy.github.io/obook/) - open, online, self-paced training materials on semantic engineering, ontology curation and ontology development.

## Ontology Development

* [Ontology Development Kit](https://github.com/INCATools/ontology-development-kit/) ⭐ 365 | 🐛 76 | 🌐 Dockerfile | 📅 2026-08-24 - set up a git repo for developing an ontology
* [Mobi](https://mobi.inovexcorp.com) - [Open Source](https://github.com/inovexcorp/mobi) ⭐ 54 | 🐛 13 | 🌐 Java | 📅 2026-07-09 (with an optional Enterprise version) system for developing ontologies and skos ocabularies with native graph versioning that enables a git-inspired workflow. More info [here](https://inovexcorp.github.io/mobi-docs/).
* [LinkML-Scala](https://github.com/NeverBlink-OSS/linkml-scala) ⭐ 39 | 🐛 2 | 🌐 Scala | 📅 2026-08-25 – fast, portable (JS/JVM/native), and robust implementation of [LinkML](https://linkml.io/).
* [dosdp-tools](https://github.com/INCATools/dosdp-tools/) ⭐ 33 | 🐛 36 | 🌐 Scala | 📅 2026-05-21 - dead simple owl design patterns (template tool)
* [OWLSharp](https://github.com/mdesalvo/OWLSharp) ⭐ 17 | 🐛 0 | 🌐 C# | 📅 2026-07-11 - .NET library for OWL2-DL ontology modeling, validation and reasoning
* [OntoVerbal](https://github.com/TheOntologist/OntoVerbal) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2013-04-24 - OntoVerbal is a Protege 4.2 plugin that generates natural language descriptions for classes for an ontology written in OWL.
* [protégé](http://protege.stanford.edu) - Ontology editor and framework for building intelligent systems.
* [OTTR](https://ottr.xyz) - Reasonable Ontology Templates.
* [ROBOT](http://robot.obolibrary.org/) - command line swiss-army knife for ontology developers
* [grafo](http://gra.fo/) - Visual graph development
* [OOPS! (Ontology Pitfall Scanner!)](http://oops.linkeddata.es/) - a web application to detect (semi)automatically 33 pitfalls or errors in ontologies. A web service is also provided.
* [Cameo Concept Modeler](https://www.nomagic.com/product-addons/magicdraw-addons/cameo-concept-modeler-plugin#key-benefits) - a cross-platform app for OWL ontology modeling, visualization, and natural-language validation
* [RDF Studio](https://rdf-studio.com) - Free web-based IDE with an advanced visual OWL/RDFS ontology editor, SHACL shapes validator and auto-generator, ontology maturity scoring, and schema-data drift detection.

## Reasoners

* [Pellet](https://github.com/stardog-union/pellet) ⭐ 353 | 🐛 27 | 🌐 Web Ontology Language | 📅 2017-01-05
* [OWL-RL](https://github.com/RDFLib/OWL-RL) ⭐ 178 | 🐛 25 | 🌐 HTML | 📅 2026-08-06
* [eye](https://github.com/josd/eye) ⭐ 173 | 🐛 24 | 🌐 Prolog | 📅 2026-08-22 - Euler Yet another proof Engine.
* [reasonable](https://github.com/gtfierro/reasonable) ⭐ 133 | 🐛 11 | 🌐 Rust | 📅 2026-06-02 - OWL 2 Reasoner built on DataFrog
* [openllet](https://github.com/Galigator/openllet) ⭐ 131 | 🐛 45 | 🌐 Java | 📅 2025-08-04
* [ELK](https://github.com/liveontologies/elk-reasoner) ⭐ 124 | 🐛 23 | 🌐 Java | 📅 2026-06-13
* [HyLAR](https://github.com/ucbl/HyLAR-Reasoner) ⭐ 65 | 🐛 13 | 🌐 JavaScript | 📅 2023-03-04
* [Whelk](https://github.com/balhoff/whelk) ⭐ 45 | 🐛 15 | 🌐 Scala | 📅 2025-03-05
* [cel](https://github.com/julianmendez/cel) ⭐ 23 | 🐛 2 | 🌐 Common Lisp | 📅 2026-04-24 -A lightweight Description Logic reasoner for large-scale biomedical ontologies.
* [ruby-rdf/rdf-reasoner](https://github.com/ruby-rdf/rdf-reasoner) ⭐ 19 | 🐛 1 | 🌐 Ruby | 📅 2024-01-08
* [FaCT++](https://github.com/ethz-asl/libfactplusplus) ⚠️ Archived and [pyfactxx](https://github.com/tilde-lab/pyfactxx) ⭐ 31 | 🐛 8 | 🌐 Java | 📅 2026-05-01
* [Sequoia](https://github.com/andrewdbate/Sequoia) ⭐ 12 | 🐛 2 | 🌐 Scala | 📅 2020-03-26 - Sequoia is a consequence-based OWL 2 DL Reasoner supporting multithreaded reasoning.
* [elephant-reasoner](https://github.com/sertkaya/elephant-reasoner) ⭐ 10 | 🐛 1 | 🌐 C | 📅 2025-06-10
* [owlproofs](https://github.com/klinovp/owlproofs) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2014-10-14 - Extension to the OWL API to request proofs of entailments from the reasoner.
* [HermiT](http://www.hermit-reasoner.com/)
* [RacerPro](https://franz.com/agraph/racer/)
* [Manchester List of Reasoners](http://owl.cs.manchester.ac.uk/tools/list-of-reasoners/)
* [konclude](http://www.derivo.de/en/produkte/konclude.html) - Konclude is a high-performance reasoner for large and expressive ontologies.
* [rdf-reasoner-konclude](https://www.npmjs.com/package/rdf-reasoner-konclude) - Konclude OWL-DL tableau reasoning kernel compiled to WebAssembly. Runs in browsers and Node.js; async TypeScript API with RDF.js Quad types and N3.js Store integration.

## Books

* [Linked Data](https://www.manning.com/books/linked-data)
* [Explorer's Guide to the Semantic Web](https://www.manning.com/books/explorers-guide-to-the-semantic-web)
* [Semantic Web Programming](https://www.wiley.com/en-us/Semantic+Web+Programming-p-9781118080603)
* [Semantic Web for the Working Ontologist](http://workingontologist.org/)
* [Demystifying OWL for the Enterprise](https://www.morganclaypool.com/doi/10.2200/S00824ED1V01Y201801WBE017) \[[1](https://link.springer.com/book/10.1007/978-3-031-79482-7)]
* [Programming the Semantic Web](http://shop.oreilly.com/product/9780596153823.do)
* [Building Ontologies with Basic Formal Ontology](https://direct.mit.edu/books/book/4044/Building-Ontologies-with-Basic-Formal-Ontology)
* [Structures for Organizing Knowledge: Exploring Taxonomies, Ontologies, and Other Schema](https://www.amazon.com/Structures-Organizing-Knowledge-Taxonomies-Ontologies/dp/1555706991)
* [Validating RDF Data](http://book.validatingrdf.com/)
* [Learning SPARQL](http://www.learningsparql.com/)
* [A Developer's Guide to the Semantic Web, 2014,2nd Ed](https://www.springer.com/us/book/9783662437957)
* [Ontology Engineering](https://www.amazon.com/Ontology-Engineering-Synthesis-Lectures-Semantic/dp/1681733102/)
* [The Data-Centric Revolution](https://www.amazon.co.uk/Data-Centric-Revolution-Restoring-Enterprise-Information/dp/1634625404)
* [An Introduction to Ontology Engineering, Keet, 2020, v1.5](https://people.cs.uct.ac.za/~mkeet/OEbook/) \[[1](https://open.umn.edu/opentextbooks/textbooks/590)]
* [Linked Data Patterns - A pattern catalogue for modelling, publishing, and consuming Linked Data](https://patterns.dataincubator.org/book/index.html)

## Programming

### C

* [raptor](https://github.com/dajobe/raptor) ⭐ 173 | 🐛 27 | 🌐 C | 📅 2026-08-03 - Redland Raptor RDF syntax library.
* [librdf](https://github.com/dajobe/librdf) ⭐ 105 | 🐛 7 | 🌐 C | 📅 2026-07-15 - Redland librdf RDF API and triple stores.
* [serd](https://github.com/drobilla/serd) ⭐ 99 | 🐛 9 | 🌐 C | 📅 2026-07-15 - Lightweight C library for RDF syntax.
* [rasqal](https://github.com/dajobe/rasqal) ⭐ 72 | 🐛 12 | 🌐 C | 📅 2026-07-15 - Redland Rasqal RDF Query Library.
* [cowl](https://github.com/sisinflab-swot/cowl) ⭐ 45 | 🐛 2 | 🌐 C | 📅 2026-06-18 - A lightweight C API for working with OWL ontologies.
* [sord](https://github.com/drobilla/sord) ⭐ 19 | 🐛 0 | 🌐 C | 📅 2026-07-04 - Sord is a lightweight C library for storing RDF statements in memory.

### C\#

* [dotNetRDF](https://github.com/dotnetrdf/dotnetrdf) ⭐ 328 | 🐛 75 | 🌐 C# | 📅 2026-08-16
* [RDFSharp](https://github.com/mdesalvo/RDFSharp) ⭐ 125 | 🐛 0 | 🌐 C# | 📅 2026-07-05
* [Rdf.Vocabularies](https://github.com/wikibus/rdf.vocabularies) ⭐ 9 | 🐛 2 | 🌐 C# | 📅 2020-06-25

### C++

* [hdt-cpp](https://github.com/rdfhdt/hdt-cpp) ⭐ 127 | 🐛 66 | 🌐 C++ | 📅 2025-03-20 - Read and query [HDT](https://www.rdfhdt.org/)

### Clojure

* [grafter](https://github.com/Swirrl/grafter) ⭐ 200 | 🐛 50 | 🌐 Clojure | 📅 2023-12-22 - Linked Data & RDF Manufacturing Tools in Clojure.
* [aristotle](https://github.com/arachne-framework/aristotle) ⭐ 157 | 🐛 7 | 🌐 Clojure | 📅 2025-01-27 - RDF, SPARQL and OWL for Clojure
* [igraph](https://github.com/ont-app/igraph) ⭐ 100 | 🐛 5 | 🌐 Clojure | 📅 2025-05-06 -  IGraph defines a protocol which aims to provide a general interface to a variety of graph-based representations.
* [kr](https://github.com/drlivingston/kr) ⭐ 56 | 🐛 9 | 🌐 Clojure | 📅 2020-10-12 - Clojure API for RDF and SPARQL - provides consistent access to APIs including Jena and Sesame.
* [clj-plaza](https://github.com/antoniogarrote/clj-plaza) ⭐ 49 | 🐛 6 | 🌐 JavaScript | 📅 2010-07-15 - Clojure rdf framework.
* [csv2rdf (clojure)](https://github.com/Swirrl/csv2rdf) ⭐ 31 | 🐛 42 | 🌐 HTML | 📅 2026-08-01 - Clojure library and application for converting CSV to RDF
* [seabass](https://github.com/ryankohl/seabass) ⭐ 29 | 🐛 0 | 🌐 Clojure | 📅 2016-07-23 - A library for working with RDF with Jena in Clojure.
* [matcha](https://github.com/Swirrl/matcha) ⭐ 23 | 🐛 50 | 🌐 Clojure | 📅 2026-08-01 - :tea: SPARQL-like DSL for querying in-memory Linked Data Models
* [table2qb](https://github.com/swirrl/table2qb) ⭐ 15 | 🐛 39 | 🌐 Clojure | 📅 2023-02-02 - A generic pipeline for converting tabular data into rdf data cubes using csvw
* [aesopica](https://github.com/newres/aesopica) ⭐ 5 | 🐛 0 | 🌐 Clojure | 📅 2019-11-24 -  A Clojure library designed to help create Semantic Web based applications.

### Elixir

* [RDF.ex](https://github.com/marcelotto/rdf-ex) ⭐ 126 | 🐛 0 | 🌐 Elixir | 📅 2026-08-13

### Go

* [rdf2go](https://github.com/deiu/rdf2go) ⭐ 82 | 🐛 1 | 🌐 Go | 📅 2024-12-12 - Native golang library for RDF.
* [knakk/rdf](https://github.com/knakk/rdf) ⭐ 76 | 🐛 7 | 🌐 Go | 📅 2026-03-17 - RDF library for Go.
* [rdfkit-go](https://github.com/dpb587/rdfkit-go) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2026-06-23 - decoders, encoders, and other RDF primitives for Go.
* [rdf-go](https://github.com/geoknoesis/rdf-go) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-01-25 - Native golang codecs for latest RDF 1.0, 1.1 and 1.2 formats (RDF, Turtle , NTriples, N-Quads, Trig, JSON-LD 1.1)

### Groovy

* [groovyrdf](https://github.com/angelo-v/groovyrdf) ⭐ 12 | 🐛 7 | 🌐 Groovy | 📅 2023-03-13

### Haskell

* [rdf4h](https://github.com/robstewart57/rdf4h) ⭐ 82 | 🐛 23 | 🌐 Haskell | 📅 2025-08-03
* [hsparql](https://github.com/robstewart57/hsparql) ⭐ 51 | 🐛 7 | 🌐 Haskell | 📅 2025-10-21
* [swish](https://hackage.haskell.org/package/swish)

### Java

* [titanium-json-ld](https://github.com/filip26/titanium-json-ld) ⭐ 166 | 🐛 10 | 🌐 Java | 📅 2026-07-27 - An implementation of the JSON-LD 1.1 (JSON-based Serialization for Linked Data) specification in Java utilizing Jakarta JSON Processing.
* [swrlapi](https://github.com/protegeproject/swrlapi) ⭐ 104 | 🐛 25 | 🌐 Java | 📅 2025-01-27 - The SWRLAPI is a Java API for working with the OWL-based SWRL rule and SQWRL query languages. It includes graphical tools for editing and executing rules and queries.
* [hdt-java](https://github.com/rdfhdt/hdt-java) ⭐ 103 | 🐛 33 | 🌐 Java | 📅 2024-02-21 - Read and query [HDT](https://www.rdfhdt.org/)
* [nxparser](https://github.com/nxparser/nxparser) ⭐ 20 | 🐛 15 | 🌐 Java | 📅 2021-06-23 - Java parsers for different RDF serialisations + API + tools + JAX-RS integration.
* [jqudt](https://github.com/egonw/jqudt) ⭐ 18 | 🐛 6 | 🌐 Java | 📅 2026-07-26 - Java library for working with the QUDT ontology and data using it.
* [JB4JSON-LD](https://github.com/kbss-cvut/jb4jsonld) ⭐ 16 | 🐛 4 | 🌐 Java | 📅 2026-07-22, [JB4JSON-LD Jackson](https://github.com/kbss-cvut/jb4jsonld-jackson) ⭐ 14 | 🐛 0 | 🌐 Java | 📅 2026-07-22 - Java binding for JSON-LD (mapping POJO - JSON-LD).
* [owlapitools](https://github.com/owlcs/owlapitools) ⭐ 16 | 🐛 10 | 🌐 Java | 📅 2020-10-27 - Set of independent add-ons for OWL API.
* [foafssl-java](https://github.com/bblfish/foafssl-java) ⭐ 13 | 🐛 0 | 🌐 Java | 📅 2011-10-25
* [soarql-dl-api](https://github.com/protegeproject/sparql-dl-api) ⭐ 12 | 🐛 4 | 🌐 Java | 📅 2020-10-12 - A query engine for SPARQL-DL.
* [cp-common-utils](https://github.com/mhgrove/cp-common-utils) ⚠️ Archived - Collection of utilty classes from Clark & Parsia.
* [JenaSecurity](https://github.com/Claudenw/JenaSecurity) ⚠️ Archived - Security (Permissions) wrapper around Jena RDF implementation.
* [cassa](https://github.com/heuer/cassa) ⭐ 4 | 🐛 6 | 🌐 Java | 📅 2012-08-22 - SPARQL 1.1 Graph Store HTTP Protocol implementation with plugable backends.
* [d-sparq](https://github.com/raghavam/d-sparq) ⭐ 4 | 🐛 1 | 🌐 Java | 📅 2015-12-19 - A distributed, scalable and efficient RDF query engine.
* [jdbc-for-rdf3x](https://github.com/dbiir/jdbc-for-rdf3x) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2016-11-03
* [jena-joseki](https://github.com/tingletech/jena-joseki) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2012-10-02
* [RDF4J](http://rdf4j.org)
* [Jena](http://jena.apache.org)
* [commons-rdf](http://commons.apache.org/proper/commons-rdf/)
* [Eclipse Lyo](https://www.eclipse.org/lyo/)
* [Jelly-JVM](https://w3id.org/jelly/jelly-jvm) – implementation of the [Jelly binary RDF format](https://w3id.org/jelly) for Java and Scala, works with Apache Jena, RDF4J, and Titanium.

### JavaScript

* [N3.js](https://github.com/RubenVerborgh/N3.js) ⭐ 794 | 🐛 64 | 🌐 JavaScript | 📅 2026-08-25
* [rdflib.js](https://github.com/linkeddata/rdflib.js) ⭐ 594 | 🐛 133 | 🌐 HTML | 📅 2026-08-20 - Linked Data API for JavaScript.
* [rdfstore-js](https://github.com/antoniogarrote/rdfstore-js) ⭐ 567 | 🐛 69 | 🌐 JavaScript | 📅 2022-05-17
* [SPARQL.js](https://github.com/RubenVerborgh/SPARQL.js/) ⚠️ Archived - A parser for the SPARQL query language in JavaScript.
* [graphy.js](https://github.com/blake-regalia/graphy.js) ⭐ 169 | 🐛 30 | 🌐 JavaScript | 📅 2024-07-22 - A collection of RDF libraries for JavaScript developers with a focus on performance and usability.
* [rdf-ext](https://github.com/rdf-ext/rdf-ext) ⭐ 126 | 🐛 3 | 🌐 JavaScript | 📅 2026-07-18
* [sparql-engine](https://github.com/Callidon/sparql-engine) ⭐ 119 | 🐛 16 | 🌐 TypeScript | 📅 2026-04-02 - An open-source framework for building SPARQL query engines in Javascript/Typescript.
* [graphql-to-sparql.js](https://github.com/rubensworks/graphql-to-sparql.js) ⭐ 117 | 🐛 13 | 🌐 TypeScript | 📅 2026-07-16 - Convert GraphQL queries to SPARQL.
* [js3](https://github.com/webr3/js3) ⭐ 115 | 🐛 4 | 🌐 JavaScript | 📅 2010-11-27
* [@zazuko/rdf-vocabularies](https://github.com/zazuko/rdf-vocabularies) ⭐ 78 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-11 - Library of common vocabularies
* [shex.js](https://github.com/shexSpec/shex.js) ⭐ 62 | 🐛 37 | 🌐 JavaScript | 📅 2026-08-23 - JavaScript implementation of Shape Expressions (ShEx).
* [@ontologies](https://github.com/ontola/ontologies) ⚠️ Archived - Like @types, but for ontologies
* [skosjs](https://github.com/tkurz/skosjs) ⭐ 39 | 🐛 10 | 🌐 JavaScript | 📅 2022-01-17 - JavaScript library for working with SKOS concepts.
* [link-redux](https://github.com/fletcher91/link-redux/) ⭐ 37 | 🐛 5 | 🌐 TypeScript | 📅 2022-09-09 - View RDF resources in React
* [levelgraph-n3](https://github.com/levelgraph/levelgraph-n3) ⭐ 36 | 🐛 7 | 🌐 JavaScript | 📅 2020-01-29 - LevelGraph plugin for storing N3/Turtle/RDF data.
* [LDPjs](https://github.com/spadgett/LDPjs) ⭐ 32 | 🐛 3 | 🌐 JavaScript | 📅 2016-08-08 - JavaScript library for Linked Data Platform.
* [rdf.js](https://github.com/webr3/rdf.js) ⭐ 26 | 🐛 4 | 🌐 JavaScript | 📅 2011-08-05
* [sparqlalgebrajs](https://github.com/joachimvh/SPARQLAlgebra.js) ⚠️ Archived - SPARQL to SPARQL Algebra converter.
* [jarql](https://github.com/linked-solutions/jarql) ⭐ 23 | 🐛 4 | 🌐 Java | 📅 2020-10-12 - Execute SPARQL Construct queries against JSON files.
* [sparqljson-to-tree.js](https://github.com/rubensworks/sparqljson-to-tree.js) ⭐ 19 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-18 - Convert SPARQL JSON results to a tree structure.
* [DataBorg/client](https://github.com/DataBorg/client) ⭐ 11 | 🐛 1 | 🌐 TypeScript | 📅 2022-05-20 - Highly versatile SPARQL client for modern age
* [rdfdev-js](https://github.com/ontola/rdfdev-js) ⚠️ Archived - Collection of libraries to ease in JavaScript RDF development.
* [sparql-to-jsonld](https://github.com/jindrichmynarz/sparql-to-jsonld) ⭐ 10 | 🐛 0 | 🌐 Clojure | 📅 2018-09-11 - Convert SPARQL results to JSON-LD.
* [react-foaf](https://github.com/read-write-web/react-foaf) ⚠️ Archived - React components for FOAF (Friend of a Friend) ontology.
* [sparks](https://github.com/sparksrdf/sparks) ⭐ 6 | 🐛 6 | 📅 2011-06-03 - Sparks is a set of JavaScript libraries designed for simplifying the access to RDF data.
* [node-sparql-hollandaise](https://github.com/PieceMeta/node-sparql-hollandaise) ⭐ 3 | 🐛 3 | 🌐 JavaScript | 📅 2017-09-08 - Node.js SPARQL client library.
* [Jessa](https://www.npmjs.com/package/jassa) - JAvascript Suite for Sparql Access.
* [RDFJS](https://github.com/rdfjs) - Github Organization that maintains modern JavaScript RDF libraries based on open, maintained standards
* [RDForms](https://rdforms.org) - Construct form-based RDF editors in a web environment.

### Kotlin

* [kotlin-rdf](https://github.com/nicholashauschild/kotlin-rdf) ⭐ 4 | 🐛 0 | 🌐 Kotlin | 📅 2017-09-07

### ObjectiveC

* [SPARQLKit](https://github.com/kasei/SPARQLKit) ⭐ 7 | 🐛 0 | 🌐 Objective-C | 📅 2016-10-17 - An implementation of the SPARQL 1.1 query language in Objective-C.

### OCaml

* [ocaml-rdf](https://www.good-eris.net/ocaml-rdf/) - Manipulate RDF graphs and execute Sparql queries.

### Perl

* [Attean](https://metacpan.org/pod/Attean)
* [RDF::Trine](https://metacpan.org/pod/RDF::Trine)

### PHP

* [ARC2](https://github.com/semsol/arc2/wiki) ⭐ 332 | 🐛 39 | 🌐 PHP | 📅 2026-03-21
* [PHP-SPARQL-Lib](https://github.com/cgutteridge/PHP-SPARQL-Lib) ⭐ 19 | 🐛 0 | 🌐 PHP | 📅 2025-12-23
* [EasyRdf](http://www.easyrdf.org/) - abandoned by the author
  * [sweetrdf/easyrdf](https://github.com/sweetrdf/easyrdf) ⭐ 26 | 🐛 3 | 🌐 PHP | 📅 2026-01-13 - Maintained fork, fully compatible to EasyRdf v1.x, runs on latest PHP versions.
* [Graphite](http://graphite.ecs.soton.ac.uk/)
* [sparqllib](http://graphite.ecs.soton.ac.uk/sparqllib/)
* sweetrdf - Collection of RDF-libraries using modern PHP functionality
  * [rdfInterface](https://github.com/sweetrdf/rdfInterface) ⭐ 7 | 🐛 3 | 🌐 PHP | 📅 2026-06-15 - Common interfaces for each RDF stack layer (parser, serializer, dataset, SPARQL client, etc.) to enable interoperability between different implementations. Think of it as PSR for RDF.
  * [rdfHelpers](https://github.com/sweetrdf/rdfHelpers) ⭐ 3 | 🐛 0 | 🌐 PHP | 📅 2026-03-18 - A set of helper classes for implementing the rdfInterface.
  * [quickRdfIo](https://github.com/sweetrdf/quickRdfIo) ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2026-03-18 - Collection of RDF parsers and serializers (using rdfInterface)
  * [quickRdf](https://github.com/sweetrdf/quickRdf) ⭐ 0 | 🐛 1 | 🌐 PHP | 📅 2026-02-26 - A RDF library providing implementation of terms and dataset (using rdfInterface).
  * [sparqlClient](https://github.com/sweetrdf/sparqlClient) ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2025-10-03 - A SPARQL client library for the rdfInterface ecosystem with the API inspired by the PDO.
  * and many more, see <https://github.com/sweetrdf>

### Prolog

* [SWI-Prolog Semantic Web Library](http://www.swi-prolog.org/pldoc/doc_for?object=section\(%27packages/semweb.html%27\))

### Python

* [RDFlib](https://github.com/RDFLib/rdflib) ⭐ 2,499 | 🐛 373 | 🌐 Python | 📅 2026-08-24 - A Python library for RDF manipulation, storage & serialization.
* [AmpliGraph](https://github.com/Accenture/AmpliGraph) ⭐ 2,238 | 🐛 30 | 🌐 Python | 📅 2026-08-06 - Python library for Representation Learning on Knowledge Graphs.
* [kglab](https://github.com/DerwenAI/kglab/) ⭐ 689 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2026-01-25 -  The kglab library provides a simple abstraction layer in Python for building knowledge graphs.
* [SPARQLWrapper](https://github.com/RDFLib/sparqlwrapper) ⭐ 566 | 🐛 54 | 🌐 Python | 📅 2026-04-30 - A wrapper for a remote SPARQL endpoint.
* [semantic-python-overview](https://github.com/pysemtec/semantic-python-overview) ⭐ 550 | 🐛 2 | 📅 2025-12-07 - List of Python specific semantic web tools and resources.
* [Ontospy](https://github.com/lambdamusic/Ontospy) ⭐ 250 | 🐛 42 | 🌐 JavaScript | 📅 2024-03-07 - Python library and command-line interface for inspecting and visualizing RDF models.
* [OWL-RL](https://github.com/RDFLib/OWL-RL) ⭐ 178 | 🐛 25 | 🌐 HTML | 📅 2026-08-06 - A simple implementation of the OWL2 RL Profile on top of RDFLib.
* [gastrodon](https://github.com/paulhoule/gastrodon) ⭐ 139 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2022-02-27 - Toolkit to display, analyze, and visualize data and documents based on RDF graphs and the SPARQL query language using Pandas, Jupyter, and other Python ecosystem tools.
* [dipper](https://github.com/monarch-initiative/dipper) ⭐ 57 | 🐛 234 | 🌐 Python | 📅 2022-11-23 - Data Ingestion Pipeline for Monarch.
* [sparql-client](https://github.com/eea/sparql-client) ⚠️ Archived - Python API to query a SPARQL endpoint.
* [calamus](https://github.com/SwissDataScienceCenter/calamus) ⭐ 32 | 🐛 14 | 🌐 Python | 📅 2025-01-08 - JSON-LD Serialization Library for Python based on Marshmallow
* [PyShEx](https://github.com/hsolbrig/PyShEx) ⭐ 29 | 🐛 44 | 🌐 Jupyter Notebook | 📅 2026-08-01 - ShEx interpreter for ShEx 2.0.
* [sparta](https://github.com/mnot/sparta/) ⚠️ Archived - Simple API for RDF.
* [pyrdb2rdf](https://github.com/nisavid/pyrdb2rdf) ⚠️ Archived - Python library for converting relational database data to RDF.
* [pyjelly](https://github.com/Jelly-RDF/pyjelly) ⭐ 19 | 🐛 2 | 🌐 Python | 📅 2026-08-24 – Python implementation of the high-performance [Jelly binary format](https://w3id.org/jelly), supporting rdflib.
* [Djubby](https://github.com/wikier/djubby) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2014-09-01 - Linked Data frontend for SPARQL endpoints for Django.
* [pyHDT](https://github.com/Callidon/pyHDT) ⚠️ Archived - Read and query [HDT documents](http://www.rdfhdt.org/) with ease in Python
* [open-kgo](https://github.com/mloda-ai/open-kgo) ⭐ 11 | 🐛 11 | 🌐 Python | 📅 2026-08-21 - Unified Python API over nine knowledge-graph backend families (including RDF/SPARQL) that validates each traversal against a declared ontology and rejects semantically invalid hops.
* [cysparql](https://github.com/cosminbasca/cysparql) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2015-08-31 - CySparql is a python wrapper over the excellent rasqal RDF library for parsing SPARQL queries.
* [sparqlx](https://github.com/lu-pl/sparqlx) ⭐ 6 | 🐛 23 | 🌐 Python | 📅 2026-08-13 - A modern SPARQL 1.2 Protocol client library based on `httpx`.
* [rdftools](https://github.com/cosminbasca/rdftools) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2015-09-17 - Simple collection of python RDF tools.
* [pycottas](https://github.com/arenas-guerrero-julian/pycottas) ⭐ 0 | 🐛 0 | 📅 2026-02-13 - Python library for working with COTTAS files.
* [RdfAlchemy](https://github.com/gjhiggins/RDFAlchemy)
* [Fuxi](http://code.google.com/p/fuxi/) - Bi-directional logical reasoning system for the semantic web.
* [ORDF](http://ordf.org)
* [Django-rdf](http://code.google.com/p/django-rdf/) - An RDF engine for Django projects.
* [SuRF](http://packages.python.org/SuRF/)
* [quepy](https://github.com/semantalytics/quepy) - Python framework for transforming natural language questions to SPARQL queries.

### R

* [rdflib](https://github.com/ropensci/rdflib) ⭐ 62 | 🐛 12 | 🌐 HTML | 📅 2024-08-05
* [jsonld](https://github.com/ropensci/jsonld) ⭐ 35 | 🐛 13 | 🌐 R | 📅 2024-10-03
* [rrdf](https://github.com/egonw/rrdf) ⭐ 29 | 🐛 15 | 🌐 R | 📅 2018-03-26
* [csvwr](https://github.com/Robsteranium/csvwr) ⭐ 17 | 🐛 8 | 🌐 HTML | 📅 2024-01-21 - Read and write CSVW tables and metadata in R
* [redland](https://github.com/ropensci/redland-bindings) ⭐ 16 | 🐛 12 | 🌐 R | 📅 2025-12-11
* [rcsvw](https://github.com/davideceolin/rcsvw) ⭐ 4 | 🐛 0 | 🌐 R | 📅 2015-11-10 - R package that implements the candidate recommendations from the W3C CSV on the Web Working Group
* [Linked Data Frames](https://swirrl.github.io/linked-data-frames/) - Work with linked-data idiomatically in R using data frames (expresses RDF resources and descriptions as S3 objects)

### Ruby

* [rdf-serializers](https://github.com/ontola/rdf-serializers) ⭐ 11 | 🐛 0 | 🌐 Ruby | 📅 2022-05-04 - Adds RDF serialization to Ruby on Rails active model serializers
* [ruby-rdf](http://ruby-rdf.github.io)

### Rust

* [Oxigraph](https://github.com/oxigraph/oxigraph) ⭐ 1,836 | 🐛 149 | 🌐 Rust | 📅 2026-08-24 - Oxigraph is a graph database implementing the SPARQL standard.
* [sophia\_rs](https://github.com/pchampin/sophia_rs) ⭐ 330 | 🐛 24 | 🌐 Rust | 📅 2026-08-20 - Sophia: a Rust toolkit for RDF and Linked Data.
* [Horned OWL](https://github.com/phillord/horned-owl) ⭐ 105 | 🐛 15 | 🌐 Rust | 📅 2026-08-15 - Horned-OWL is a library for manipulating OWL data.
* [rio](https://github.com/oxigraph/rio) ⚠️ Archived - Rio is a low level library which provides conformant and fast parsers and formatters for RDF related file formats.
* [rome](https://github.com/vandenoever/rome) ⭐ 72 | 🐛 5 | 🌐 Rust | 📅 2020-07-20 - Rome is an RDF library written in safe Rust.
* [hdt-rs](https://github.com/KonradHoeffner/hdt) ⭐ 41 | 🐛 16 | 🌐 Rust | 📅 2026-06-29 - Read and query [HDT](https://www.rdfhdt.org/)
* [rdf-rs](https://github.com/scholtzan/rdf-rs) ⭐ 30 | 🐛 2 | 🌐 Rust | 📅 2020-11-13 - rdf is a library for the Resource Description Framework (RDF) and SPARQL implemented in Rust.
* [owlish](https://github.com/field33/owlish) ⭐ 23 | 🐛 1 | 🌐 Rust | 📅 2023-07-12 - An OWL library in Rust modeled on the OWL functional syntax.
* [RDFtk](https://github.com/johnstonskj/rust-rdftk) ⭐ 18 | 🐛 6 | 🌐 Rust | 📅 2026-06-29 - An RDF Toolkit for Rust
* [harriet](https://github.com/field33/harriet) ⭐ 12 | 🐛 2 | 🌐 Rust | 📅 2023-07-04 - A format-preserving serialization/deserialization library for Turtle.
* [atomic-lib](https://crates.io/crates/atomic-lib) - Library for managing and (de)serializaing Atomic Data, a strict subset of RDF.

### Scala

* [banana-rdf](https://github.com/banana-rdf/banana-rdf) ⭐ 298 | 🐛 99 | 🌐 Scala | 📅 2023-07-11 - A library for RDF, SPARQL and Linked Data technologies in Scala.
* [SANSA-RDF](https://github.com/SANSA-Stack/SANSA-RDF) ⭐ 150 | 🐛 41 | 🌐 Scala | 📅 2025-08-31 - Library to read RDF files into Spark or Flink.
* [scowl](https://github.com/phenoscape/scowl) ⭐ 64 | 🐛 13 | 🌐 Scala | 📅 2024-07-10 - A Scala DSL for programming with the OWL API.
* [jvmrdftools](https://github.com/cosminbasca/jvmrdftools) ⭐ 1 | 🐛 0 | 🌐 Scala | 📅 2014-12-04

### Swift

* [kineo](https://github.com/kasei/kineo) ⭐ 40 | 🐛 0 | 🌐 Swift | 📅 2026-08-18 - A SPARQL endpoint and quadstore written in Swift.
* [swift-sparql-syntax](https://github.com/kasei/swift-sparql-syntax) ⭐ 18 | 🐛 0 | 🌐 Swift | 📅 2026-08-18 - SPARQL 1.1 Parser.
* [swift-serd](https://github.com/kasei/swift-serd) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2020-06-28 - Swift package wrapper for the [Serd RDF library](http://drobilla.net/software/serd).
* [swift-hdt](https://github.com/kasei/swift-hdt) ⭐ 2 | 🐛 0 | 🌐 Swift | 📅 2019-04-02 - An [HDT](http://www.rdfhdt.org/) RDF Parser.
* [URITemplate](https://github.com/kasei/URITemplate) ⭐ 1 | 🐛 0 | 🌐 Swift | 📅 2018-09-25 - Swift implementation of URI Template ([RFC6570](https://tools.ietf.org/html/rfc6570)).

## Editors

### VIM

* [semweb.vim](https://github.com/seebi/semweb.vim) ⭐ 7 | 🐛 1 | 🌐 VimL | 📅 2015-04-05
* [sparql.vim](https://github.com/vim-scripts/sparql.vim) ⭐ 5 | 🐛 1 | 🌐 VimL | 📅 2010-10-18 - SPARQL syntax highlighting.
* [vim-sparql](https://github.com/Omer/vim-sparql) ⭐ 4 | 🐛 0 | 🌐 VimL | 📅 2012-03-08

### Emacs

* [sparql-mode](https://github.com/ljos/sparql-mode) ⭐ 63 | 🐛 11 | 🌐 Emacs Lisp | 📅 2025-05-08
* [ELOT](https://github.com/johanwk/elot) ⭐ 32 | 🐛 14 | 🌐 Emacs Lisp | 📅 2026-08-19 - Emacs Literate Ontology Tool, write OWL ontologies using org-mode
* [ttl-mode](https://github.com/jeeger/ttl-mode) ⭐ 12 | 🐛 2 | 🌐 Emacs Lisp | 📅 2020-09-21 - Supports both ttl and n3, indentation, some electric punctuation and hungry delete.
* [nxml-mode](https://www.emacswiki.org/emacs/NxmlMode) - nxml-mode is a major mode for editing XML
* [emacs-ottr-toolkit](https://gitlab.com/ottr/pub/emacs-ottr-toolkit) - Emacs toolkit for creating OTTR templates for ontology building

### JetBrains IDEs: Intellij IDEA, PyCharm, etc.

* [LNKD.tech Editor](https://plugins.jetbrains.com/plugin/12802-lnkd-tech-editor) - Editor for Turtle (Terse RDF Triple Language, TTL) files
* [RDF and SPARQL](https://rdfandsparql.com) - Adds support for the RDF 1.2 (Turtle, TriG, N-Triples, N-Quads), SPARQL 1.2 and ShExC 2.1 languages as well as a bunch of productivity features

### Visual Studio Code

* [Stardog RDF Grammars](https://marketplace.visualstudio.com/items?itemName=stardog-union.stardog-rdf-grammars)

### TextMate

* [sparql/turtle extension](https://github.com/peta/turtle.tmbundle) ⭐ 29 | 🐛 6 | 🌐 Ruby | 📅 2018-02-12

### Sublime Text 3

* [Turtle and SPARQL syntax highlighter](https://github.com/abcoates/sublime-text-turtle-sparql) ⭐ 40 | 🐛 1 | 📅 2017-07-04
* [Linked Data syntaxes](https://github.com/blake-regalia/linked-data.syntaxes) ⭐ 31 | 🐛 11 | 🌐 JavaScript | 📅 2022-12-08 - Syntax highlighting for SPARQL 1.1/SPARQL\*, Turtle/Turtle\*, TriG, N-Triples, N-Quads, Notation3, and ShExC.

### BBedit

* [Turtle syntax highlighter](https://github.com/njh/bbedit-turtle)

## Geo

* [LinkedGeoData](https://github.com/GeoKnow/LinkedGeoData) ⭐ 162 | 🐛 17 | 🌐 Java | 📅 2024-09-29
* [GeoARQ](https://github.com/castagna/GeoARQ) ⭐ 6 | 🐛 0 | 🌐 Java | 📅 2010-10-28
* [linkedspatialindex](https://github.com/wwaites/linkedspatialindex) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2012-04-28
* [GeomRDF](https://github.com/fhamdi/GeomRDF) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2014-09-01
* [SemantGeo](https://github.com/apseyed/SemantGeo) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2013-08-26
* [GeoLift](https://github.com/AKSW/GeoLift) ⭐ 1 | 🐛 2 | 🌐 Java | 📅 2013-07-29
* [USeekM](https://www.openhub.net/p/useekm)

## Browsers

* [LodView](https://github.com/LodLive/LodView) ⭐ 137 | 🐛 26 | 🌐 Java | 📅 2023-12-17 - RDF browser written in Java based on Spring and Jena using a SPARQL endpoint.
* [RickView](https://github.com/konradhoeffner/rickview) ⭐ 36 | 🐛 15 | 🌐 Rust | 📅 2026-08-17 - RDF browser for small knowledge bases written in Rust using an in-memory graph, doesn't require a SPARQL endpoint. Optimized for high performance and low resource usage.
* [RhizomerEye](https://github.com/rhizomik/rhizomerEye) ⭐ 19 | 🐛 12 | 🌐 TypeScript | 📅 2025-08-05 - A [Web application](https://rhizomik.net/rhizomer) for interactive exploration of semantic and linked data available from SPARQL endpoints.
* [Galacteek](https://gitlab.com/galacteek/galacteek) - Multi-platform Qt5-based browser and semantic agent for the distributed web. Uses RDF graphs and P2P-SparQL to synchronize linked-data between peers.

## Visualization

* [Sparnatural](https://github.com/sparna-git/Sparnatural) ⭐ 304 | 🐛 98 | 🌐 TypeScript | 📅 2026-08-19
* [ontodia](https://github.com/ontodia-org/ontodia) ⚠️ Archived - Ontodia data diagraming library.
* [Ontology Visualisation](https://github.com/usc-isi-i2/ontology-visualization) ⭐ 144 | 🐛 15 | 🌐 Python | 📅 2022-09-20 - Create graphs from RDF using GraphViz.
* [d3-sparql](https://github.com/zazuko/d3-sparql) ⭐ 121 | 🐛 3 | 🌐 JavaScript | 📅 2019-05-10
* [visualRDF](https://github.com/alangrafu/visualRDF) ⭐ 108 | 🐛 5 | 🌐 PHP | 📅 2019-11-02
* [rdfpuml](https://github.com/VladimirAlexiev/rdf2rml) ⭐ 59 | 🐛 20 | 🌐 Perl | 📅 2026-07-28 - True RDF Diagrams.
* [RdfGlance](https://github.com/xdobry/rdfglance) ⭐ 50 | 🐛 9 | 🌐 Rust | 📅 2026-07-23 - Fast desktop RDF graph visualization and data viewer programmed in Rust
* [Reactodia](https://github.com/reactodia/reactodia-workspace) ⭐ 29 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-08 - Ontodia fork with additional features such as grouping and annotations
* [gephi-semantic-web-import](https://github.com/Wimmics/gephi-semantic-web-import) ⭐ 7 | 🐛 4 | 🌐 Java | 📅 2024-11-18
* [rdfdot](https://github.com/wastl/rdfdot) ⭐ 4 | 🐛 1 | 🌐 Java | 📅 2016-03-08 - Tools for drawing graphs from RDF files with GraphViz.
* [Visual SPARQL Builder](https://leipert.github.io/vsb/)
* [SPARQLFilterFlow](http://sparql.visualdataweb.org/)
* [VOWL](http://vowl.visualdataweb.org/) - Visual Notation for OWL Ontologies.
* [sgvizler](http://mgskjaeveland.github.io/sgvizler/) - JavaScript library for visualizing SPARQL query results in SVG.
* [OWLGrEd](http://owlgred.lumii.lv/) - UML style graphical editor for OWL ontologies.
* [SparqlBlocks](http://sparqlblocks.org/) - Build SPARQL queries with blocks
* [Cameo Concept Modeler](https://www.nomagic.com/product-addons/magicdraw-addons/cameo-concept-modeler-plugin#key-benefits) - a cross-platform app for OWL ontology modeling, visualization, and natural-language validation
* [ReDeFer RDF2SVG](https://rdf2svg.redefer.rhizomik.net) - Render RDF as a SVG graph.
* [ReDeFer RDF2HTML](https://rhizomik.net/redefer/rdf2html) - Render RDF as HTML.
* [Zazuko's RDF Sketch](https://sketch.zazuko.com/) - Graphical RDF Explorer for small datasets
* [KinGVisher](https://wse-research.org/knowledge-graph-visualizer/) - Visualize knowledge graphs in a web browser
* [G.V](https://gdotv.com) - ($/(F)) G dot V Graph Database Exploration and Visualization UI for SPARQL, Cypher and Gremlin
* [SemSpect](https://www.semspect.de) - Graph exploration and data-driven no-code querying tool for Neo4j and RDF data
* [RDF Studio](https://rdf-studio.com) - Free web-based IDE with interactive knowledge graph visualization, faceted search auto-generated from OWL ontologies, SPARQL 1.1 editor, and multi-database support for Oxigraph, GraphDB, and any SPARQL endpoint.

## Data Cube

* [CubeViz](https://github.com/AKSW/cubeviz.ontowiki) ⭐ 34 | 🐛 28 | 🌐 JavaScript | 📅 2016-08-02
* [NoSPA-RDF-Data-Cube-Validator](https://github.com/yyz1989/NoSPA-RDF-Data-Cube-Validator) ⭐ 16 | 🐛 0 | 🌐 Java | 📅 2016-03-11
* [table2qb](https://github.com/swirrl/table2qb) ⭐ 15 | 🐛 39 | 🌐 Clojure | 📅 2023-02-02 - a pipeline for converting tabular data into rdf data cubes using csvw
* [qb4olap-tools](https://github.com/lorenae/qb4olap-tools) ⭐ 2 | 🐛 2 | 🌐 JavaScript | 📅 2017-10-03
* [OpenCube-Expander](https://github.com/opencube-toolkit/OpenCube-Expander) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2015-10-16
* [QB4ST: RDF Data Cube extensions for spatio-temporal components](https://www.w3.org/TR/qb4st/)
* [The RDF Data Cube Vocabulary](https://www.w3.org/TR/vocab-data-cube/)
* [OpenCube Toolkit](http://opencube-toolkit.eu/)

## Datasets

* [BBC - Ontologies](https://www.bbc.co.uk/ontologies) - The ontologies the BBC is using to support its audience facing applications such as BBC Sport, BBC Education, BBC Music, News projects and more.
* [DBpedia](http://dbpedia.org)
* [geonames](https://github.com/ldodds/geonames) ⭐ 5 | 🐛 1 | 🌐 Ruby | 📅 2011-03-03
* [permid](http://permid.org) - PermID: Connecting Data to the World.
* [wikidata](http://wikidata.org) - Wikidata is a free and open knowledge base that can be read and edited by both humans and machines.
* [lod-cloud](https://lod-cloud.net) - The Linked Open Data Cloud.

## IoT

* [Weviate](https://github.com/creativesoftwarefdn/weaviate) ⭐ 16,753 | 🐛 689 | 🌐 Go | 📅 2026-08-25
* [rdfagents](https://github.com/joshsh/rdfagents) ⭐ 6 | 🐛 1 | 🌐 Java | 📅 2016-07-23 - Real-time messaging for the Semantic Web.

## DevOps

* [RDFUnit](https://github.com/AKSW/RDFUnit) ⭐ 165 | 🐛 34 | 🌐 Java | 📅 2025-09-18 - RDF Unit testing and validation framework.
* [rdf.sh](https://github.com/seebi/rdf.sh) ⭐ 126 | 🐛 4 | 🌐 Shell | 📅 2025-02-03 - A multi-tool shell script for doing Semantic Web jobs on the command line.
* [QuitStore](https://github.com/AKSW/QuitStore) ⭐ 115 | 🐛 54 | 🌐 Python | 📅 2024-06-27 - Quads in Git - Distributed Version Control for RDF Knowledge Bases.
* [rdf-toolkit](https://github.com/edmcouncil/rdf-toolkit) ⭐ 80 | 🐛 7 | 🌐 Java | 📅 2026-01-22 - RDF Serializer, to be used in a git commit-hook to force automatic correct rewrite of every OWL ontology.
* [TurtleValidator](https://github.com/mmlab/TurtleValidator) ⭐ 54 | 🐛 6 | 🌐 JavaScript | 📅 2023-03-04 - A Turtle validator on command line and in browser.
* [owl2vcs](https://github.com/utapyngo/owl2vcs) ⭐ 26 | 🐛 0 | 🌐 Java | 📅 2014-11-08 - owl2vcs is a set of tools designed to facilitate version control of OWL 2 ontologies using version control systems.
* [dowl](https://github.com/ldodds/dowl) ⭐ 24 | 🐛 4 | 🌐 Ruby | 📅 2013-06-03 - Generate docs for RDF/OWL Schema.
* [r43ples](https://github.com/plt-tud/r43ples) ⭐ 21 | 🐛 14 | 🌐 JavaScript | 📅 2020-11-17 - Revision Management for the Semantic Web.
* [babel](https://github.com/aidhog/blabel/) ⭐ 19 | 🐛 3 | 🌐 Java | 📅 2023-07-08 - A library for skolemising (or canonicalising) blank node labels in RDF graphs.
* [TripleChecker](https://github.com/cgutteridge/TripleChecker) ⭐ 8 | 🐛 3 | 🌐 PHP | 📅 2014-01-17 - Look for common errors in an RDF Document.
* [QuitDiff](https://github.com/AKSW/QuitDiff) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2024-08-08 - Git diff into SparQL / Eccrev vocabulary.
* [shi3ld-http](https://github.com/lukostaz/shi3ld-http) ⭐ 7 | 🐛 1 | 🌐 Java | 📅 2013-06-03 - Shi3ld for HTTP: Access control for HTTP operations on Linked Data.
* [rdfpatch](https://github.com/pchampin/ld-patch-py) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2024-02-16
* [rdf-pipeline](https://github.com/rdf-pipeline)
* [Ontogen](https://ontogen.io/) - A version control system for RDF datasets.

## Platforms

* [comunica](https://github.com/comunica/comunica) ⭐ 578 | 🐛 80 | 🌐 TypeScript | 📅 2026-08-25 - Flexible meta query engine for the Web.
* [rww-play](https://github.com/read-write-web/rww-play) ⚠️ Archived - An implementation in Play of a number of tools to build a Read-Write-Web server using Play2.x and akka.
* [Wings](https://github.com/IKCAP/wings) ⭐ 51 | 🐛 76 | 🌐 Java | 📅 2024-08-19 - A workflow system.
* [pyLDAPI](https://github.com/rdflib/pyLDAPI) ⭐ 43 | 🐛 10 | 🌐 Python | 📅 2025-01-18 - A Python [rdflib](https://github.com/rdflib/RDFlib/) ⭐ 2,499 | 🐛 373 | 🌐 Python | 📅 2026-08-24-based API framework for Linked Data via the W3C's [Content Negotiation by Profile](https://w3c.github.io/dx-connegp/connegp/)
* [Chimera](https://github.com/cefriel/chimera) ⭐ 39 | 🐛 17 | 🌐 Java | 📅 2026-06-29 - A framework providing Apache Camel components to support data conversion to/from RDF and service integration with RDF graphs
* [LDIF](https://github.com/wbsg/ldif) ⭐ 37 | 🐛 2 | 🌐 Scala | 📅 2016-08-02 - Linked Data Integration Framework.
* [lodspeakr](https://github.com/alangrafu/lodspeakr) ⭐ 32 | 🐛 14 | 🌐 PHP | 📅 2013-12-23 - Framework to create Linked Data-based applications.
* [prissma-studio](https://github.com/lukostaz/prissma-studio) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2016-01-24 - PRISSMA Studio: a web application to create Prisms, context-aware presentation metadata for Linked Data visualization.
* [trinity](https://bitbucket.org/semiodesk/trinity) - An application development platform for Microsoft .NET and Mono. It allows to easily build Linked Data and Semantic Web applications based on RDF.
* [imagesnippets](http://www.imagesnippets.com/) - ImageSnippets is a complete metadata editing interface that enables someone who knows little to nothing about RDF, OWL, ontologies, or even URIs to create descriptions for images using Linked Data which is written in RDF.
* [Linked Data Reactor (LD-R)](http://ld-r.org) - A full-stack platform for building adaptive component-based Linked Data applications in NodeJS and React.
* [m-ld](https://m-ld.org/) - Real-time information sharing component using RDF and conflict-free replicated data types (CRDTs)

## Tools

* [Widoco](https://github.com/dgarijo/Widoco) ⭐ 396 | 🐛 154 | 🌐 JavaScript | 📅 2026-08-08 - A Wizard for documenting and publishing ontologies on the Web.
* [tawny-owl](https://github.com/phillord/tawny-owl) ⭐ 279 | 🐛 14 | 🌐 Clojure | 📅 2026-05-08 - Build OWL Ontologies in a Programmatic Environment.
* [pyLODE](https://github.com/rdflib/pyLODE/) ⭐ 226 | 🐛 77 | 🌐 Python | 📅 2026-08-17 - A Python [rdflib](https://github.com/rdflib/RDFlib/) ⭐ 2,499 | 🐛 373 | 🌐 Python | 📅 2026-08-24-based implementation of the [LODE](http://ceur-ws.org/Vol-932/paper12.pdf) ontology documentation tool
* [grlc](https://github.com/CLARIAH/grlc) ⭐ 151 | 🐛 33 | 🌐 Python | 📅 2026-08-01 - Web APIs from SPARQL queries.
* [Web-Client](https://github.com/AtomGraph/Web-Client) ⭐ 123 | 🐛 8 | 🌐 JavaScript | 📅 2026-07-26 - Generic Linked Data browser and UX component framework.
* [OnToology](https://github.com/OnToology/OnToology) ⭐ 113 | 🐛 85 | 🌐 Python | 📅 2026-06-11 - A system for collaborative ontology development. Given a GitHub repository with an OWL file, OnToology will survey it and produce diagrams, a complete documentation and validation based on common pitfalls.
* [ripple](https://github.com/joshsh/ripple) ⭐ 106 | 🐛 47 | 🌐 Java | 📅 2023-04-14 - Semantic Web scripting language.
* [HydraConsole](https://github.com/lanthaler/HydraConsole) ⭐ 103 | 🐛 20 | 🌐 PHP | 📅 2018-04-01
* [schema\_salad](https://github.com/common-workflow-language/schema_salad) ⭐ 86 | 🐛 94 | 🌐 Python | 📅 2026-08-25 - Semantic Annotations for Linked Avro Data.
* [rpt](https://github.com/SmartDataAnalytics/RdfProcessingToolkit) ⭐ 50 | 🐛 34 | 🌐 Java | 📅 2026-07-06 - Command line interface based RDF Processing Toolkit to run sequences of SPARQL statements ad-hoc on RDF datasets with a lot of features
* [OBA](https://github.com/KnowledgeCaptureAndDiscovery/OBA/) ⭐ 45 | 🐛 56 | 🌐 HTML | 📅 2026-03-01 - Automatically create OpenAPI specifications from OWL and launch a server that serves JSON objects according to your ontology.
* [prefix.cc](https://github.com/cygri/prefix.cc) ⭐ 40 | 🐛 20 | 🌐 PHP | 📅 2022-03-10 - Source code to the prefix.cc website.
* [Git2PROV](https://github.com/mmlab/Git2PROV) ⭐ 36 | 🐛 11 | 🌐 JavaScript | 📅 2023-01-23 - Unleash the potential of Git in the new W3C standard for provenance.
* [rdf2rdf](https://github.com/knakk/rdf2rdf) ⭐ 31 | 🐛 2 | 🌐 Go | 📅 2020-03-14 - Tool for converting between different RDF serialization formats.
* [specgen](https://github.com/specgen/specgen) ⚠️ Archived - Modified, extended and more generalized version of Danbri's SpecGen version 5.
* [ont-converter](https://github.com/sszuev/ont-converter) ⭐ 23 | 🐛 1 | 🌐 Kotlin | 📅 2023-03-12 - Written in Kotlin, a simple command-line utility to convert any RDF graph to OWL2 ontology.
* [n3pygments](https://github.com/gniezen/n3pygments) ⭐ 23 | 🐛 3 | 🌐 Python | 📅 2015-04-15 - Pygments lexer to perform syntax highlighting for N3, Turtle and SPARQL.
* [UnSHACLed](https://github.com/KNowledgeOnWebScale/unshacled) ⭐ 21 | 🐛 3 | 🌐 JavaScript | 📅 2021-01-20 - A visual editor for RDF constraints currently supporting the visual notations ShapeUML and ShapeVOWL and import/export/validation of SHACL constraints.
* [psps](https://github.com/factsmission/psps) ⭐ 19 | 🐛 4 | 🌐 Java | 📅 2023-09-18 - Personal Structured Publishing Space.
* [qonsole](https://github.com/epimorphics/qonsole) ⭐ 17 | 🐛 22 | 🌐 JavaScript | 📅 2026-06-15 - A simple console for running SPARQL queries and displaying results.
* [sesame-vocab-builder](https://github.com/tkurz/sesame-vocab-builder) ⭐ 16 | 🐛 3 | 🌐 Java | 📅 2017-08-01 - Sesame Vocab Builder provides a command line tool that allows to create constants for RDF primitives for a given namespace out of RDF ontology files.
* [keygenapp](https://github.com/bblfish/keygenapp) ⭐ 8 | 🐛 0 | 🌐 Java | 📅 2012-06-25 - Utilities and WebApp for certificate creation within a browser, for FOAF+SSL.
* [LD-FusionTool](https://github.com/mifeet/LD-FusionTool) ⚠️ Archived - Data Fusion & Conflict Resolution tool for Linked Data.
* [ShacShifter](https://github.com/AKSW/ShacShifter) ⭐ 4 | 🐛 11 | 🌐 Python | 📅 2025-11-04 - Shapes Constraint Language (SHACL) to various other format.
* [rdf3x\_path](https://github.com/agubichev/rdf3x_path) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2013-04-09 - RDF3X with path queries.
* [IntervalServer](https://github.com/epimorphics/IntervalServer) ⚠️ Archived
* [ntcat](https://github.com/cgutteridge/ntcat) ⭐ 0 | 🐛 0 | 🌐 Perl | 📅 2015-06-09 - Command line tool for concatenating NTriples documents.
* [RDFConvert](https://sourceforge.net/projects/rdfconvert/) - RDFConvert is a simple command-line tool for converting RDF file betweeen different syntax formats.
* [How to diff RDF](https://www.w3.org/2001/sw/wiki/How_to_diff_RDF)
* [Bubastis](https://github.com/EBISPOT/bubastis) - Tool for detecting asserted logical differences between two ontologies, such as between versions.
* [Openlink Structured Data Sniffer](http://osds.openlinksw.com/) - Browser extension for Google Chrome, Microsoft Edge, Mozilla Firefox, Opera, and Vivaldi that unveils structured metadata embedded within HTML documents and web pages.
* [prefix.cc](https://prefix.cc) - namespace lookup for RDF developers
* [CEDAR Workbench](https://metadatacenter.org) - Center for Expanded Data Annotation and Retrieval offers full life cycle management for semantically linked metadata
* [MEL](https://w3id.org/kgcp/MEL-TNNT/) - (*Metadata Extractor & Loader*) - A tool to extract metadata (and textual content) from various file formats, as JSON objects.
* [RDF Playground](https://rdfplayground.dcc.uchile.cl/) - Browser based aggregation of multiple semantic web tools, includes syntax validation, visualization, reasoner and shacl validation

- [Qlue-ls](https://github.com/IoannisNezis/Qlue-ls) ⭐ 47 | 🐛 13 | 🌐 Rust | 📅 2026-08-21 - A powerfull SPARQL language server and formatter. Providing: auto-completion, hover-info, formatting, code-actions, diagnostics and more.
- [rdfless](https://github.com/larsw/rdfless/) ⭐ 8 | 🐛 1 | 🌐 Rust | 📅 2026-08-11 - A pager and pretty-printer for Turtle/TriG/N-triples and N-Quads written in Rust.
- [Semantic Web LSP](https://github.com/ajuvercr/semantic-web-lsp) ⭐ 1 | 🐛 0 | 🌐 HTML | 📅 2025-09-23 - A language server for Semantic Web files, featuring SHACL shapes diagnostics, Turtle formatting, hover hints and descriptions, and completions for prefixes, properties, and classes.
- [KGPrune](https://kgprune.loria.fr/) - An API and Web application for extracting subgraphs of interest from Wikidata based on user-input seed entities, to bootstrap new KGs or support knowledge extraction, or knowledge mining approaches
- [Teamboard](https://termboard.com/start/) - Browser-based powerful and intuitive tool for creating and managing visual diagrams.
- [rdf-label-cache](https://label-cache-demo.dhabgood.workers.dev/) - Globally distributed, edge-cached HTTP service that resolves human-readable labels for RDF IRIs (Cloudflare Worker + R2); ships a maintained public seed for RDF, RDFS, OWL, SKOS, DCTERMS, DCAT, and Schema.org.

## Integrations

* [anthelion](https://github.com/yahoo/anthelion) ⚠️ Archived - A plugin for Apache Nutch to crawl semantic annotations within HTML pages.
* [SolRDF](https://github.com/agazzarini/SolRDF) ⭐ 114 | 🐛 25 | 🌐 Java | 📅 2025-01-27 - An RDF plugin for Solr.
* [HydraBundle](https://github.com/lanthaler/HydraBundle) ⭐ 60 | 🐛 9 | 🌐 PHP | 📅 2018-06-24 - Symfony2 bundle which shows how easily Hydra can be integrated in modern Web frameworks.
* [sesametools](https://github.com/joshsh/sesametools) ⭐ 51 | 🐛 4 | 🌐 Java | 📅 2021-08-17 - A collection of utilities for use with OpenRDF Sesame.
* [RightField](https://github.com/myGrid/RightField) ⭐ 32 | 🐛 8 | 🌐 Java | 📅 2025-04-10 - RightField is an open-source tool for adding ontology term selection to Excel spreadsheets.
* [SARQ](https://github.com/castagna/SARQ) ⭐ 16 | 🐛 0 | 🌐 Java | 📅 2011-03-29 - Free Text Indexing for SPARQL using a remote Solr server.
* [jekyll-rdf](https://github.com/white-gecko/jekyll-rdf) ⭐ 8 | 🐛 0 | 📅 2020-02-16 - A Jekyll plugin for including RDF data in your static site.
* [sesame-spring](https://github.com/ameingast/sesame-spring) ⚠️ Archived - Spring integration for OpenRDF/Sesame.
* [EARQ](https://github.com/castagna/EARQ) ⭐ 7 | 🐛 2 | 🌐 Java | 📅 2021-08-09 - EARQ is a combination of ARQ and ElasticSearch.
* [Imperium](https://github.com/mhgrove/Imperium) ⚠️ Archived - Imperium is a plugin for the Play! framework similar to the existing JPA plugin that allows the use of Empire seamlessly in a Play! based application.
* [mu-semtech](https://github.com/mu-semtech) - An Ecosystem of User-facing Microservices supported by Semantic Models.

## Machine Learning

* [OntoGPT](https://github.com/monarch-initiative/ontogpt/) ⭐ 979 | 🐛 78 | 🌐 Jupyter Notebook | 📅 2026-06-22 - Tools for populating semantic schemas from unstructured text using Large Language Models (LLMs)
* [Duke](https://github.com/larsga/Duke) ⭐ 622 | 🐛 115 | 🌐 Java | 📅 2023-10-11 - Duke is a fast and flexible deduplication engine written in Java.
* [FOX](https://github.com/AKSW/FOX) ⭐ 194 | 🐛 13 | 🌐 Java | 📅 2023-10-25 - Federated Knowledge Extraction Framework.
* [LinkedPipes-ETL](https://github.com/linkedpipes/etl) ⭐ 161 | 🐛 197 | 🌐 Java | 📅 2026-06-12 - Linked Data ETL pipeline.
* [signal-collect](https://github.com/uzh/signal-collect) ⭐ 153 | 🐛 38 | 🌐 Scala | 📅 2018-05-26
* [infovore](https://github.com/paulhoule/infovore) ⭐ 148 | 🐛 50 | 🌐 Java | 📅 2021-11-15 - RDF-Centric Map/Reduce Framework and Freebase data conversion tool.
* [graph-pattern-learner](https://github.com/RDFLib/graph-pattern-learner) ⭐ 93 | 🐛 14 | 🌐 Python | 📅 2023-01-23 - Evolutionary Graph Pattern Learner that learns SPARQL queries for a given set of source-target-pairs from an endpoint.
* [jena-grande](https://github.com/castagna/jena-grande) ⭐ 24 | 🐛 0 | 🌐 Java | 📅 2012-12-17 - Jena Grande is a collection of utilities, experiments and examples on how to use MapReduce, Pig, HBase or Giraph to process data in RDF format.
* [gm-sparql](https://github.com/ssrangan/gm-sparql) ⭐ 21 | 🐛 1 | 🌐 Python | 📅 2015-08-06 - Graph Mining Using SPARQL.
* [mrlin](https://github.com/mhausenblas/mrlin) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2012-11-01 - MapReduce processing of Linked Data.
* [tdbloader4](https://github.com/castagna/tdbloader4) ⭐ 13 | 🐛 0 | 🌐 Java | 📅 2012-03-07 - Prototype to show how TDB indexes can be generated using MapReduce.
* [etalis](https://github.com/sspider/etalis) ⭐ 7 | 🐛 1 | 🌐 OpenEdge ABL | 📅 2015-05-04 - Event Processing SPARQL (EP-SPARQL).
* [SPARQLLM](https://github.com/GDD-Nantes/SPARQLLM) ⭐ 5 | 🐛 4 | 🌐 HTML | 📅 2026-06-15 - SPARQL queries that can access Search Engines, Large Language Models, or Vector databases. Access external data sources during SPARQL query execution.
* [ODCS](https://github.com/mff-uk/ODCS) ⚠️ Archived - The tool uses data processing pipelines for obtaining, processing, and storing RDF data.
* [SANSA-Stack](http://sansa-stack.net) - Scalable Semantic Analytics Stack.

## Linked Data

* [sieve](https://github.com/wbsg/sieve) ⭐ 6 | 🐛 0 | 🌐 CSS | 📅 2014-02-20 - Linked Data Quality Assessment and Fusion.

## CSVW

* [csvlint](https://github.com/Data-Liberation-Front/csvlint.rb) ⭐ 287 | 🐛 56 | 🌐 Ruby | 📅 2026-02-01 - Ruby gem to validate CSV files to check their syntax and contents
* [COW](https://github.com/CLARIAH/COW) ⭐ 48 | 🐛 25 | 🌐 Python | 📅 2024-05-06 - Python package to convert CSV to RDF with nanopublications
* [csv2rdf (clojure)](https://github.com/Swirrl/csv2rdf) ⭐ 31 | 🐛 42 | 🌐 HTML | 📅 2026-08-01 - Clojure library and application for converting CSV to RDF
* [RDF::Tabular](https://github.com/ruby-rdf/rdf-tabular) ⭐ 21 | 🐛 3 | 🌐 HTML | 📅 2024-10-09 - Ruby gem to parse CSV or other Tabular Data into RDF and JSON
* [csvwr](https://github.com/Robsteranium/csvwr) ⭐ 17 | 🐛 8 | 🌐 HTML | 📅 2024-01-21 - R package for reading and writing CSVW tables and metadata
* [table2qb](https://github.com/swirrl/table2qb) ⭐ 15 | 🐛 39 | 🌐 Clojure | 📅 2023-02-02 - A generic pipeline for converting tabular data into rdf data cubes using csvw
* [csvw-parser](https://github.com/sebneu/csvw-parser) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2016-03-16 - Python package to parse CSVW
* [csv2rdf (ruby)](https://github.com/theodi/csv2rdf) ⭐ 4 | 🐛 5 | 🌐 Ruby | 📅 2024-01-31 - Ruby gem to convert CSV to RDF
* [rcsvw](https://github.com/davideceolin/rcsvw) ⭐ 4 | 🐛 0 | 🌐 R | 📅 2015-11-10 - R package that implements the candidate recommendations from the W3C CSV on the Web Working Group
* [csv2json](https://github.com/theodi/csv2json) ⭐ 2 | 🐛 0 | 🌐 Ruby | 📅 2016-02-02 - Ruby gem to convert CSV to JSON
* [Model for Tabular Data and Metadata on the Web](https://w3c.github.io/csvw/syntax/)
* [Metadata Vocabulary for Tabular Data](https://w3c.github.io/csvw/metadata/)
* [Generating RDF from Tabular Data on the Web (csv2rdf)](https://w3c.github.io/csvw/csv2rdf/)

## WebID

* [solid-spec](https://github.com/solid/solid-spec) ⚠️ Archived
* [webid-spec](https://github.com/webid-community/webid-spec) ⭐ 14 | 🐛 0 | 📅 2011-11-14
* [node-webid](https://github.com/magnetik/node-webid) ⭐ 14 | 🐛 0 | 🌐 CoffeeScript | 📅 2016-01-22
* [webid-demo](https://github.com/digitalbazaar/webid-demo) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2011-05-23
* [xwiki](https://github.com/bblfish/xwiki) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2010-09-29 - Xwiki related code for WebID.

## SHACL Implementations

See <https://github.com/validatingrdf/validatingrdf.github.io/wiki/Updated-list-of-implementations> ⭐ 17 | 🐛 22 | 🌐 HTML | 📅 2018-01-10 and <https://github.com/w3c/shacl/issues/78> ⚠️ Archived for a more extensive list.

* [pySHACL](https://github.com/RDFLib/pySHACL) ⭐ 340 | 🐛 45 | 🌐 Python | 📅 2026-07-28 - A Python validator for SHACL.
* [TopQuadrant/shacl](https://github.com/TopQuadrant/shacl) ⭐ 245 | 🐛 16 | 🌐 Java | 📅 2026-06-30 - SHACL API in Java based on Apache Jena.
* [RDFunit](https://github.com/AKSW/RDFUnit/) ⭐ 165 | 🐛 34 | 🌐 Java | 📅 2025-09-18
* [labra/shaclex](https://github.com/labra/shaclex) ⭐ 92 | 🐛 262 | 🌐 Scala | 📅 2025-04-12
* [Schímatos](https://github.com/schimatos/schimatos.org/) ⭐ 55 | 🐛 13 | 🌐 JavaScript | 📅 2022-01-22 - A SHACL-based Web-Form Generator for Knowledge Graph Editing.
* [rdf4j-shacl](http://docs.rdf4j.org/programming/#_validation_with_shacl)
* [shperone](https://forms.hypermedia.app) - Form Builder
* [SHACL Playground](https://shacl-playground.zazuko.com/) - A web based SHACL validator
* [SHACLPlay](https://shacl-play.sparna.fr/play/)

## SKOS Tools

* [iQvoc](https://github.com/innoq/iqvoc) ⭐ 123 | 🐛 56 | 🌐 Ruby | 📅 2026-07-27 - SKOS(-XL) Vocabulary Management System for the Semantic Web.
* [atramhasis](https://github.com/OnroerendErfgoed/atramhasis) ⭐ 64 | 🐛 61 | 🌐 Python | 📅 2026-08-09
* [VocPrez](https://github.com/RDFLib/VocPrez/) ⚠️ Archived - A Linked Data API for SKOS data presentation
* [java-skos-api](https://github.com/simonjupp/java-skos-api) ⭐ 12 | 🐛 3 | 🌐 Java | 📅 2017-06-09
* [askos](https://github.com/WileyLabs/askos) ⚠️ Archived - A SKOS browser and editor.
* [Poolparty](https://www.poolparty.biz/skos-and-skos-xl) ($)
* [skosprovider](https://skosprovider.readthedocs.io/en/latest/intro.html) - Skosprovider provides an interface that can be included in an application to allow it to talk to different SKOS vocabularies.
* [skosshuttle](https://skosshuttle.ch/) ($)
* [ThManager](http://thmanager.sourceforge.net/)
* [protege skos editor](https://protegewiki.stanford.edu/wiki/SKOS_Editor)
* [skosmos](http://skosmos.org/)
* [Vocbench](http://vocbench.uniroma2.it/doc/user/skos_editing.jsf)
* [SKOS Play!](http://labs.sparna.fr/skos-play/about)
* [skosapi](http://skosapi.sourceforge.net/)

## NLP

* [LoRiS](https://github.com/WSE-research/LoRiS-LLM-generated-Representations-of-SPARQL-queries) ⭐ 8 | 🐛 4 | 🌐 Python | 📅 2026-08-23 generated natural-language representations of SPARQL queries over Wikidata and DBpedia.
* [fred](http://wit.istc.cnr.it/stlab-tools/fred/#About) - a machine reader for the Semantic Web
* [NIF](https://persistence.uni-leipzig.org/nlp2rdf/) NLP Interchange Format
* [Lemon](https://lemon-model.net/) - The Lexicon Model for Ontologies
* [Wordnet](https://wordnet.princeton.edu/)
* [PreMOn](http://premon.fbk.eu/ontology/vn) - Predicate Model for Ontologies (PreMOn) - VerbNet ontology module
* [BabelNet](https://babelnet.org)
* [TNNT](https://w3id.org/kgcp/MEL-TNNT/) - (*The NLP/NER Toolkit*) - A tool that automates the extraction of categorised named entities from the unstructured information encoded in the source documents, using diverse NLP tools and NER models.

## IIIF

* [fester](https://github.com/UCLALibrary/fester) ⭐ 4 | 🐛 0 | 🌐 Java | 📅 2026-07-23
* [IIIF](https://iiif.io/)

## Other Awesome

* [totogo/awesome-knowledge-graph](https://github.com/totogo/awesome-knowledge-graph) ⭐ 1,883 | 🐛 23 | 📅 2026-02-28

* [shaoxiongi/awesome-knowlege-graph](https://github.com/shaoxiongji/awesome-knowledge-graph) ⭐ 1,792 | 🐛 0 | 🌐 JavaScript | 📅 2022-10-07

* [awesome-graph](https://github.com/jbmusso/awesome-graph) ⭐ 1,268 | 🐛 17 | 📅 2026-02-26

* [forgefed](https://github.com/forgefed/forgefed) ⭐ 1,037 | 🐛 13 | 🌐 Bikeshed | 📅 2026-05-03 - An extension to ActivityPub for web-based Git services federation.

* [OWL-API](https://github.com/owlcs/owlapi) ⭐ 923 | 🐛 110 | 🌐 Java | 📅 2026-03-02 - The OWL API is a Java API for creating, manipulating and serialising OWL Ontologies.

* [awesome-ontology](https://github.com/ozekik/awesome-ontology) ⭐ 673 | 🐛 1 | 📅 2026-06-07 - Similar to this list

* [awesome-prolog](https://github.com/klaussinani/awesome-prolog) ⭐ 575 | 🐛 12 | 📅 2025-09-24

* [jsonld-java](https://github.com/jsonld-java/jsonld-java) ⭐ 388 | 🐛 54 | 🌐 Java | 📅 2024-01-10 - JSON-LD implementation for Java.

* [amazon-neptune-tools](https://github.com/awslabs/amazon-neptune-tools) ⭐ 314 | 🐛 10 | 🌐 Python | 📅 2026-08-14 - Tools and utilities to enable loading data and building graph applications with Amazon Neptune.

* [kbpedia](https://github.com/Cognonto/kbpedia) ⭐ 238 | 🐛 2 | 📅 2020-08-04 - KBPedia Knowledge Graph & Knowledge Ontology (KKO).

* [NSpM](https://github.com/AKSW/NSpM) ⚠️ Archived - robot Neural SPARQL Machines translate natural language into SPARQL queries.

* [LodLive](https://github.com/dvcama/LodLive) ⭐ 204 | 🐛 9 | 🌐 JavaScript | 📅 2020-04-22 - browse the web of data - a SPARQL navigator <http://lodlive.it>

* [ontodia](https://github.com/sputniq-space/ontodia) ⚠️ Archived - Ontodia data diagraming library.

* [grlc](https://github.com/CLARIAH/grlc) ⭐ 151 | 🐛 33 | 🌐 Python | 📅 2026-08-01 - Translates public SPARQL queries into Linked Data APIs automatically.

* [rdf.sh](https://github.com/seebi/rdf.sh) ⭐ 126 | 🐛 4 | 🌐 Shell | 📅 2025-02-03 - A multi-tool shell script for doing Semantic Web jobs on the command line.

* [awesome GLAM semweb](https://github.com/ncarboni/awesome-GLAM-semweb) ⭐ 118 | 🐛 2 | 📅 2023-01-26

* [levelgraph-jsonld](https://github.com/mcollina/levelgraph-jsonld) ⭐ 113 | 🐛 22 | 🌐 JavaScript | 📅 2023-06-23 - The Object Document Mapper for LevelGraph based on JSON-LD

* [hydra-java](https://github.com/dschulten/hydra-java) ⭐ 110 | 🐛 18 | 🌐 Java | 📅 2022-12-16

* [vocol](https://github.com/vocol/vocol) ⭐ 99 | 🐛 28 | 🌐 JavaScript | 📅 2022-12-14 - An integrated environment to support collaborative ontology / vocabulary development in distributed settings.

* [vocol](https://github.com/vocol/vocol) ⭐ 99 | 🐛 28 | 🌐 JavaScript | 📅 2022-12-14 - An integrated environment to support collaborative ontology / vocabulary development in distributed settings.

* [activitystreams](https://github.com/OpenSocial/activitystreams) ⭐ 94 | 🐛 8 | 🌐 Java | 📅 2022-11-11

* [jsonld-streaming-parser.js](https://github.com/rubensworks/jsonld-streaming-parser.js) ⭐ 92 | 🐛 21 | 🌐 TypeScript | 📅 2026-08-18 - A fast and lightweight streaming JSON-LD parser for JavaScript.

* [umls2rdf](https://github.com/ncbo/umls2rdf) ⭐ 87 | 🐛 12 | 🌐 Python | 📅 2026-03-26 - These python scripts connect to the Unified Medical Language System (UMLS) database and translate the ontologies into RDF/OWL files. This is part of the BioPortal project.

* [Awesome Knowledge Graph Construction Tools](https://github.com/kg-construct/awesome-kgc-tools) ⭐ 86 | 🐛 1 | 📅 2026-06-03

* [ontmalizer](https://github.com/srdc/ontmalizer) ⭐ 85 | 🐛 12 | 🌐 Java | 📅 2021-09-20 - A tool that performs comprehensive transformations of XML Schemas (XSD) and XML data to RDF/OWL automatically

* [stardog.js](https://github.com/stardog-union/stardog.js) ⭐ 84 | 🐛 11 | 🌐 JavaScript | 📅 2026-08-19

* <https://github.com/stkenny/grefine-rdf-extension/releases/tag/v1.1.0> ⭐ 81 | 🐛 12 | 🌐 Java | 📅 2025-06-28

* [json-ld-macros](https://github.com/antoniogarrote/json-ld-macros) ⭐ 69 | 🐛 4 | 🌐 JavaScript | 📅 2016-06-01  Declarative transformation of JSON APIs into JSON-LD.

* [jena-sparql-api](https://github.com/SmartDataAnalytics/jena-sparql-api) ⚠️ Archived - A collection of Jena-extensions for hiding SPARQL-complexity from the application layer.

* [yarrrml-parser](https://github.com/RMLio/yarrrml-parser) ⭐ 57 | 🐛 61 | 🌐 JavaScript | 📅 2026-06-12 - A YARRRML parser library and CLI in Javascript.

* [nichtich/wdg](https://github.com/nichtich/wdq) ⭐ 56 | 🐛 14 | 🌐 Perl | 📅 2024-04-10 - Command line interface to Wikidata Query Service.

* [ostrich](https://github.com/rdfostrich/ostrich) ⭐ 52 | 🐛 3 | 🌐 C++ | 📅 2025-08-21 -Versioned RDF triple store (Offset-enabled TRIple store for CHangesets)

* [sesametools](https://github.com/joshsh/sesametools) ⭐ 51 | 🐛 4 | 🌐 Java | 📅 2021-08-17 - A collection of utilities for use with OpenRDF Sesame (as of recently, Eclipse RDF4J).

* [ONT-API](https://github.com/owlcs/ont-api) ⭐ 50 | 🐛 4 | 🌐 Java | 📅 2026-05-25 - a Jena based OWL-API implementation (Java library).

* [semargl](https://github.com/semarglproject/semargl) ⭐ 50 | 🐛 27 | 🌐 HTML | 📅 2022-11-16 - Highly performant, lightweight framework for linked data processing. Supports RDFa, JSON-LD, RDF/XML and plain text formats, runs on Android and GAE, provides integration with Jena, Sesame and Clerezza.

* [vsb](https://github.com/leipert/vsb) ⭐ 50 | 🐛 22 | 🌐 JavaScript | 📅 2015-10-20 - Visual SPARQL Builder - Model SPARQL-Select-Queries in a browser <https://leipert.github.io/vsb/>

* [solr-ontology-tagger](https://github.com/opensemanticsearch/solr-ontology-tagger) ⭐ 46 | 🐛 5 | 🌐 Python | 📅 2022-01-16 - Automatic tagging and analysis of documents in an Apache Solr index for faceted search by RDF(S) Ontologies & SKOS thesauri.

* [dbpedia-extension](https://github.com/sparkica/dbpedia-extension) ⭐ 40 | 🐛 3 | 🌐 Java | 📅 2013-10-04

* [Linked-Data-Theatre](https://github.com/architolk/Linked-Data-Theatre) ⭐ 37 | 🐛 15 | 🌐 XSLT | 📅 2024-02-03 - The Linked Data Theatre is a platform for an optimal presentation of Linked Data.

* [redland-bindings](https://github.com/dajobe/redland-bindings) ⭐ 36 | 🐛 3 | 🌐 Perl | 📅 2026-07-15 - Redland librdf language bindings.

* [MOD-Ontology](https://github.com/sifrproject/MOD-Ontology) ⭐ 36 | 🐛 44 | 📅 2026-06-04 - Metadata for Ontology Description and Publication Ontology .

* [linked-csv](https://github.com/JeniT/linked-csv) ⭐ 35 | 🐛 4 | 🌐 XML | 📅 2013-04-19 - A souped-up CSV-based data format.

* [SEPA](https://github.com/arces-wot/SEPA) ⭐ 33 | 🐛 28 | 🌐 Java | 📅 2026-08-13 - A JAVA implementation of the SPARQL Event Processing Architecture including the engine, APIs and tools.

* [SEPA](https://github.com/arces-wot/SEPA) ⭐ 33 | 🐛 28 | 🌐 Java | 📅 2026-08-13 - A JAVA implementation of the SPARQL Event Processing Architecture including the engine, APIs and tools.

* [nanopub-java](https://github.com/Nanopublication/nanopub-java) ⭐ 33 | 🐛 26 | 🌐 Java | 📅 2026-08-25

* [SEPA](https://github.com/arces-wot/SEPA/blob/master/README.md) ⭐ 33 | 🐛 28 | 🌐 Java | 📅 2026-08-13

* [genealogical-trees](https://github.com/blokhin/genealogical-trees) ⚠️ Archived - Semantic Web Exercise: Reasoning and Visualization of the Genealogical Ontologies.

* [ML-Schema/core](https://github.com/ML-Schema/core) ⭐ 31 | 🐛 24 | 🌐 HTML | 📅 2020-12-22 - CORE ontology of ML-Schema schema. It's the mapping to others machine learning vocabularies and ontologies (DMOP, Expose, OntoDM and MEX)

* [basil](https://github.com/the-open-university/basil) ⭐ 25 | 🐛 32 | 🌐 JavaScript | 📅 2025-08-14 - Building Apis SImpLy from sparql endpoints.

* [basil](https://github.com/the-open-university/basil) ⭐ 25 | 🐛 32 | 🌐 JavaScript | 📅 2025-08-14 - Building Apis SImpLy from sparql endpoints.

* [awesome-semantic-web-business](https://github.com/KMax/awesome-semantic-web-business) ⭐ 23 | 🐛 0 | 📅 2019-12-23

* [rabel](https://github.com/linkeddata/rabel) ⭐ 20 | 🐛 0 | 🌐 JavaScript | 📅 2025-03-24 - Program for reading and writing linked data in various formats.

* [lodmill](https://github.com/lobid/lodmill) ⚠️ Archived - Blend, grind, and enjoy LOD – fresh from the mill!

* [rdfsurveyor](https://github.com/guiveg/rdfsurveyor) ⭐ 19 | 🐛 2 | 🌐 JavaScript | 📅 2021-07-21 - Exploration tool for RDF datasets.

* [psps](https://github.com/factsmission/psps) ⭐ 19 | 🐛 4 | 🌐 Java | 📅 2023-09-18 - Personal Structured Publishing Space.

* [CostFed](https://github.com/dice-group/CostFed) ⭐ 19 | 🐛 12 | 🌐 Java | 📅 2023-08-04 - Cost-Based Query Optimization for SPARQL Endpoint Federation.

* [sparql-ld](https://github.com/fafalios/sparql-ld) ⭐ 18 | 🐛 0 | 🌐 Java | 📅 2023-07-03 - SPARQL-LD: A SPARQL Extension for Fetching and Querying Linked Data.

* [sparql-ld](https://github.com/fafalios/sparql-ld) ⭐ 18 | 🐛 0 | 🌐 Java | 📅 2023-07-03 - SPARQL-LD: A SPARQL Extension for Fetching and Querying Linked Data.

* [sparql-ld](https://github.com/fafalios/sparql-ld) ⭐ 18 | 🐛 0 | 🌐 Java | 📅 2023-07-03 - SPARQL-LD: A SPARQL Extension for Fetching and Querying Linked Data.

* [balloon](https://github.com/schlegel/balloon) ⭐ 17 | 🐛 1 | 🌐 JavaScript | 📅 2016-03-09 - A tool-suite for Linked Data consumption. balloon aims in offering public services and tools to take advantage of the semantic web with less effort. The basic motivation is to establish a foundation for Linked Data as a Service (LDaaS).

* [profilechecker](https://github.com/stain/profilechecker) ⭐ 17 | 🐛 3 | 🌐 Java | 📅 2017-05-04 - OWL API profile checker.

* [basex-rdf](https://github.com/metadataframes/basex-rdf) ⭐ 17 | 🐛 0 | 🌐 Java | 📅 2017-10-29 - RDF parsing for BaseX.

* [HydraClient](https://github.com/lanthaler/HydraClient) ⭐ 16 | 🐛 0 | 🌐 PHP | 📅 2013-02-07

* [odmtp-tpf](https://github.com/benjimor/odmtp-tpf) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2019-02-06 - Triple pattern matching over non-RDF datasources with inference .

* [rdf2h](https://github.com/rdf2h/rdf2h) ⭐ 15 | 🐛 24 | 🌐 JavaScript | 📅 2022-12-30 - Render resources described in RDF using logicless templates.

* [eso-and-ceo](https://github.com/newsreader/eso-and-ceo) ⭐ 15 | 🐛 0 | 📅 2018-04-20 - Event and Implied Situation Ontology (ESO) and the Circumstantial Event Ontology for Calamities (CEO).

* [LODGrefine](https://github.com/sparkica/LODGrefine) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2013-01-25 - LOD-enabled Google Refine: linked open data related extensions included.

* [rdfpro](https://github.com/dkmfbk/rdfpro) ⭐ 13 | 🐛 9 | 🌐 Java | 📅 2022-02-04 - an extensible tool for building stream-oriented RDF processing pipelines.

* [rdfpro](https://github.com/dkmfbk/rdfpro) ⭐ 13 | 🐛 9 | 🌐 Java | 📅 2022-02-04 - a public domain, Java command line tool and library for RDF processing.

* [rdf-protege](https://github.com/sszuev/rdf-protege) ⚠️ Archived - a Protege Desktop fork with RDF support.

* [java-skos-api](https://github.com/simonjupp/java-skos-api) ⭐ 12 | 🐛 3 | 🌐 Java | 📅 2017-06-09 - The SKOS API provides a Java interface and OWL API based implementation of the Simple Knowledge Organisation System (SKOS)

* [OME](https://github.com/oeg-upm/OME) ⭐ 11 | 🐛 17 | 🌐 Python | 📅 2023-05-01 - Online Mapping Editor.

* [vss-ontology](https://github.com/klotzbenjamin/vss-ontology) ⭐ 11 | 🐛 2 | 🌐 Python | 📅 2022-07-05 - Design of the Vehicle Signal Ontology VSSo and example of use with SOSA/SSN and STEP.

* [awesome-ontologies](https://github.com/semantalytics/awesome-ontologies) ⭐ 10 | 🐛 1 | 📅 2019-05-18

* [DEER](https://github.com/dice-group/DEER) ⭐ 10 | 🐛 12 | 🌐 JavaScript | 📅 2026-04-13 - RDF Dataset Enrichment Framework.

* [Luzzu](https://github.com/Luzzu/Framework/) ⭐ 10 | 🐛 7 | 🌐 Java | 📅 2021-09-20 - A scalable and extensible Linked Data quality assessment framework.

* [rollxx/antlr-sparql-grammar](https://github.com/rollxx/antlr-sparql-grammar) ⭐ 10 | 🐛 1 | 📅 2010-11-05 - sparql 1.1 antlr grammar.

* [SemanticPingback](https://github.com/AKSW/SemanticPingback) ⭐ 9 | 🐛 0 | 🌐 XSLT | 📅 2018-12-20 - This small vocabulary defines resources which are used in the context of Semantic Pingback.

* [cp-openrdf-utils](https://github.com/mhgrove/cp-openrdf-utils) ⚠️ Archived - Utility classes for working with the OpenRdf API.

* [sparql-to-csv](https://github.com/jindrichmynarz/sparql-to-csv) ⭐ 9 | 🐛 0 | 🌐 Clojure | 📅 2017-11-03 - Stream SPARQL results to CSV .

* [dcat-ap\_validatyor](https://github.com/SEMICeu/dcat-ap_validator) ⚠️ Archived

* [Glimmer](https://github.com/Timpy/Glimmer) ⭐ 8 | 🐛 1 | 🌐 Java | 📅 2014-12-09 - An RDF Search Engine.

* \[scylla-rdf]\(<https://github.com/DataFabricRus/scylla-rdf> ⭐ 8 | 🐛 3 | 🌐 Java | 📅 2023-12-05

* [fox-py](https://github.com/earthquakesan/fox-py) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2019-07-22 - Python bindings for FOX - Federated Knowledge Extraction Framework.

* [linked-csv-browser](https://github.com/theodi/linked-csv-browser) ⚠️ Archived

* [fenster](https://github.com/knakk/fenster) ⭐ 7 | 🐛 3 | 🌐 Go | 📅 2016-03-31 - RDF quad-store frontend.

* [canonical\_rdf](https://github.com/iherman/canonical_rdf) ⚠️ Archived - Proof-of-concept implementation of Aidan Hogan's RDF canonicalization algorithm in node.js.

* [module-extractor](https://github.com/rsgoncalves/module-extractor) ⭐ 6 | 🐛 1 | 🌐 Java | 📅 2016-08-19 - Java-based module extractor for OWL ontologies.

* [knowledgecubes](https://github.com/amgadmadkour/knowledgecubes) ⭐ 6 | 🐛 0 | 🌐 Scala | 📅 2024-10-03 - Efficient RDF Data Management over Spark.

* [datastudio-sparql-connector](https://github.com/DataFabricRus/datastudio-sparql-connector) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2019-01-10

* [StaTIX](https://github.com/eXascaleInfolab/StaTIX) ⭐ 6 | 🐛 0 | 🌐 Java | 📅 2019-02-16 - Statistical Type Inference (both fully automatic and semi supervised) for RDF datasets.

* [ORE](https://github.com/AKSW/ORE) ⭐ 5 | 🐛 3 | 🌐 Java | 📅 2016-06-24 - Ontology Repair and Enrichment.

* [LD-FusionTool](https://github.com/mifeet/LD-FusionTool) ⚠️ Archived - Data Fusion & Conflict Resolution tool for Linked Data.

* [xodx](https://github.com/AKSW/xodx) ⭐ 5 | 🐛 16 | 🌐 PHP | 📅 2016-02-14 - An implementation of Semantic Pingback and PuSH for a DSSN.

* [stardog-groovy](https://github.com/stardog-union/stardog-groovy) ⭐ 5 | 🐛 2 | 🌐 Groovy | 📅 2019-07-12

* [rocker](https://github.com/AKSW/rocker) ⭐ 5 | 🐛 1 | 🌐 Java | 📅 2016-12-01 - key A Refinement Operator Approach for Key Discovery. <http://aksw.org/projects/Rocker>

* [Rule-Translator](https://github.com/ismailakbari/Rule-Translator) ⭐ 5 | 🐛 0 | 🌐 Java | 📅 2018-09-01 - This is framework is a Web rule translator. It has a rule parser, visualizer and translator. The Web rule languages that are covered by this framework include: Notation3 (N3), POSL, Datalog RuleML, SWRL and RIF. This framework is a rule engine for RIF language as well.

* [LSD-Dimensions](https://github.com/albertmeronyo/LSD-Dimensions) ⭐ 4 | 🐛 19 | 🌐 HTML | 📅 2017-02-13 - All dimension values of Linked Statistical Data.

* [fox-java](https://github.com/renespeck/fox-java) ⭐ 4 | 🐛 2 | 🌐 Java | 📅 2022-05-20 - Java bindings for FOX - Federated Knowledge Extraction Framework.

* [mediation](https://github.com/correndo/mediation) ⭐ 4 | 🐛 0 | 🌐 Java | 📅 2018-07-06 - Jena based framework to implement ontological mediation of SPARQL queries.

* [morph-starter](https://github.com/jpcik/morph-starter) ⭐ 4 | 🐛 1 | 🌐 Java | 📅 2013-11-05 - this project is a simple Java (and Scala) demo of how to use morph.

* [turtle-in-html](https://github.com/alangrafu/turtle-in-html) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2013-06-24 - Bookmark to visualize RDF embedded in HTML as Turtle.

* [Mandolin](https://github.com/mommi84/Mandolin) ⭐ 4 | 🐛 4 | 🌐 Java | 📅 2017-07-06 - sparkle Markov Logic Networks for the Discovery of Links

* [semwiki](https://github.com/pchampin/semwiki) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2013-03-02 - An experimental semantic wiki with bidirectional (text <-> triples) changes.

* [prissma](https://github.com/lukostaz/prissma) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2015-02-02 - Context-Aware Adaptation for Linked Data.

* [rollxx/manchester-syntax-owl2](https://github.com/rollxx/manchester-syntax-owl2) ⭐ 2 | 🐛 0 | 🌐 GAP | 📅 2014-12-22 - ANTLR grammar for simplified Manchester Syntax OWL2.

* [fbrs](https://github.com/aldonline/fbrs) ⭐ 2 | 🐛 5 | 🌐 CoffeeScript | 📅 2013-09-09 - Facebook RDF Sync

* [sparti](https://github.com/amgadmadkour/sparti) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2018-04-23 - SPARTI - RDF Semantic Partitioning.

* [Linked-Data-Studio](https://github.com/architolk/Linked-Data-Studio) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2017-05-05 - The Linked Data Studio is an extension to the Linked Data Theatre for the creation of Linked Data.

* [Awesome Java RDF](https://github.com/enola-dev/awesome-java-rdf) ⭐ 1 | 🐛 0 | 📅 2026-07-20

* [signal-collect-torque](https://github.com/uzh/signal-collect-torque) ⭐ 1 | 🐛 0 | 🌐 Scala | 📅 2014-11-01 - Support for Signal/Collect Torque deployment.

* [owl-functional-syntax-axiom-parser](https://github.com/dfleischhacker/owl-functional-syntax-axiom-parser) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2012-01-17

* [concurrent-rdf-graph](https://github.com/sszuev/concurrent-rdf-graph) ⭐ 1 | 🐛 4 | 🌐 Kotlin | 📅 2024-04-02 - Concurrent RDF Graph implementations written in Kotlin.

* [wordnet-lemon-to-w3c](https://github.com/jimregan/wordnet-lemon-to-w3c) ⚠️ Archived

* [csvw-template](https://github.com/edsu/csvw-template) ⭐ 1 | 🐛 0 | 📅 2015-11-04 - Document the semantics of your csv file.

* [SWRL.js](https://github.com/mterdjimi/SWRL.js) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2016-12-16 - A SWRL parser for Javascript.

* [fox-ui](https://github.com/Data2Semantics/fox-ui) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2015-07-13 - Web UI for FoxPSL.

* [tac](https://github.com/magnetik/tac) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2011-12-12 - Triple access control.

* [owlconvert](https://github.com/camwebb/owlconvert) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2013-11-01 - Simple OWL format converter based on OWLAPI.

* [docker2rdf](https://github.com/albertmeronyo/docker2rdf) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2018-05-31 - Mapper to represent Dockerfiles as RDF triples

* [carml-cli](https://github.com/netage/carml-cli) ⭐ 0 | 🐛 1 | 🌐 Java | 📅 2023-04-14 - Interface for CARML library.

* [GLEEN](https://github.com/RENCI-NRIG/gleen) ⚠️ Archived Regular Paths for ARQ SparQL.

* [Beast](https://github.com/SmartDataAnalytics/Beast) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2018-06-20 - Benchmarking, Evaluation, and Analysis Stack - A powerful yet lightweight Java8/Jena-based RDF processing stack.

* [SWRLRulesToOWLAxioms](https://github.com/dcarralma/SWRLRulesToOWLAxioms) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2016-07-11 - Implementation of a procedure to transform SWRL rules into equivalent OWL axioms.

* [Enola.dev's Awesome related things](https://docs.enola.dev/concepts/other/)

* [grefine-rdf-extension](https://github.com/OpenRefine/grefine-rdf-extension) - An extension to Google Refine that enables graphical mapping of Google Refine project data to an RDF skeleton and then exporting it in RDF format.

* [stardog-ubuntu-scripts](https://github.com/semantalytics/stardog-ubuntu-scripts)

* [iRap](https://github.com/EIS-Bonn/iRap) - iRap - Interest-based RDF update propagation framework.

* [motools](https://github.com/motools) - Music ontology tools

* [activitypub](https://www.w3.org/TR/2018/REC-activitypub-20180123/)

* [CSO](https://cso.kmi.open.ac.uk/home) - The Computer Science Ontology (CSO) is a large-scale ontology of research areas that was automatically generated using the Klink-2 algorithm on the Rexplore dataset, which consists of about 16 million publications, mainly in the field of Computer Science.

* [metreeca](https://github.com/metreeca) - The model-driven linked data platform.

* [OLGA](https://ecostruxure.github.io/OLGA/) - OLGA (Ontology Library GenerAtor) is a generic tool aiming to accelerate the adoption of Standard W3C Semantic technology among developers.

* <https://metacpan.org/release/KJETILK/AtteanX-Store-SPARQL-0.012>

* <http://www.linklion.org/portal/>

* <http://rml.io/yarrrml/>

* <http://sage.univ-nantes.fr>

* [psparql](http://exmo.inrialpes.fr/software/psparql/) - PSPARQL (for Path SPARQL) is a query language for RDF.

* [spdx](https://spdx.org/specifications) - Software Package Data Exchange® (SPDX®) is an open standard for communicating software bill of material information (including components, licenses, copyrights, and security references).

* [premon](https://premon.fbk.eu) - PREdicate Model for ONtologies

* [pikes](http://pikes.fbk.eu) - Pikes is a Knowledge Extraction Suite

* [robot](http://robot.obolibrary.org/) - ROBOT is a command line tool for working with Open Biomedical Ontologies

* [opensemanticsearch](https://github.com/opensemanticsearch)

* [dione](http://www.khaos.uma.es/dione) - Khoaos Research Group

* [TrOWL](https://github.com/TrOWL) - Tractable OWL 2 Reasoning Infrastructure

* <http://ld-r.org>

* [activitystrams-core](https://www.w3.org/TR/activitystreams-core/)

* [rdf4a](https://github.com/MM2-0/rdf4a) - RDF4J for Android.

* [rdfshape](http://rdfshape.herokuapp.com/)

* [rif4j](http://rif4j.sourceforge.net/)

* [wsml2reasoner](http://tools.sti-innsbruck.at/wsml2reasoner/) - a highly modular framework that combines various validation, normalization and transformation algorithms that enable the translation of ontology descriptions in WSML to the appropriate syntax of several underlying reasoning engines.

* [silk](http://silk.semwebcentral.org/) - Semantic Inferencing on Large Knowledge (SILK) knowledge representation system.

* [fuxi](https://code.google.com/archive/p/fuxi/)

* [openskos](http://openskos.org/)

* <https://dvcs.w3.org/hg/rdf/raw-file/default/rdf-json/index.html>

* [linkeddatafragments](http://comunica.linkeddatafragments.org/)

* [vocbench](http://vocbench.uniroma2.it/)

* [metrecca/link](https://github.com/metreeca/link) - Metreeca Model-Driven Linked Data Framework .

* [rdf-patch](https://afs.github.io/rdf-patch/)

* [ldpatch](https://www.w3.org/TR/ldpatch/)

* [rdf-delta](https://afs.github.io/rdf-delta/)

* [thedatatank](http://thedatatank.com)

* [omv2](http://omv2.sourceforge.net/)

* [platform-linked-data-nederland](http://www.pilod.nl/wiki/Platform_Linked_Data_Nederland)

* <http://eventkg.l3s.uni-hannover.de/>

* [aurl](https://ctan.org/pkg/aurl) LaTeX package for hyperlinked URLs abbreviated with prefixes. The 1000 most common prefixes are predefined and more can be added.

* [RDF Stream Taxonomy (RDF-STaX)](https://w3id.org/stax) – a systematization of RDF stream types. It also includes a small ontology to help with describing RDF streams.

## Contributing

Your contributions are always welcome! Please take a look at the [contributing guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Zachary Whitley](https://github.com/zacharywhitley) has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
