Terminologia
------------

Note di lettura del documento
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Conformemente alle norme *ISO/IEC Directives, Part 3* per la stesura dei
documenti tecnici le presenti Linee Guida utilizzeranno le parole chiave
«DEVE», «DEVONO», «NON DEVE», «NON DEVONO», «\ È RICHIESTO», «DOVREBBE»,
«NON DOVREBBE», «\ È RACCOMANDATO», «NON È RACCOMANDATO» «\ PUÒ\ » e
«\ È OPZIONALE», la cui interpretazione è descritta di seguito.

-  **DEVE** o **DEVONO**, indicano un requisito obbligatorio per
   rispettare le linee guida;

-  **NON DEVE** o **NON DEVONO**, indicano un assoluto divieto delle
   specifiche;

-  **DOVREBBE** o **È RACCOMANDATO/SI RACCOMANDA** o **NON DOVREBBE** o
   **NON È RACCOMANDATO**, indicano che le implicazioni devono essere
   comprese e attentamente pesate prima di scegliere approcci
   alternativi;

-  **PU\ Ò** o **POSSONO** o **È OPZIONALE**, indica che si può
   scegliere di applicare o meno senza alcun tipo di implicazione la
   specifica.

Ove applicabile, nei prossimi capitoli sono definiti specifici requisiti
e raccomandazioni in modo da rendere in maniera più chiara e sintetica
**cosa è necessario implementare obbligatoriamente** (requisiti) e
**cosa invece è solo un forte suggerimento** (raccomandazioni). Nel caso
dei requisiti si utilizzeranno le parole chiave indicate innanzi ai
primi due punti, mentre nel caso delle raccomandazioni si utilizzeranno
quelle indicate agli ultimi due punti.

I requisiti, inoltre, saranno rappresentati nel modo seguente:

.. admonition:: must

   **REQUISITO x**: dlgs36-2006/opendata/req/<conformance-class-id>/<req-id>

    Testo del requisito.

mentre le raccomandazioni nel modo seguente:

.. admonition:: should

   **Raccomandazione x**: dlgs36-2006/opendata/rec/<conformance-class-id>/<rec-id>

    Testo della raccomandazione.

Quando, su alcuni aspetti specifici, esistono già documenti (norme,
regole tecniche, linee guida, manuali, materiali vari) che
approfondiscono tali aspetti e che forniscono indicazioni puntuali,
anche eventualmente vincolanti, è presente anche la **sezione “Risorse
utili”** che riporta i riferimenti, attraverso collegamenti
ipertestuali, a tali documenti o risorse in generale a cui si rimanda.
In particolare, i documenti e le risorse possono essere relativi ad una
di queste tipologie:

-  linee guida, regolamenti o altre tipologie di documenti che
   disciplinano aspetti specifici trattati nel presente documento e che
   non si ritiene di dover duplicare (per evitare, per esempio,
   disallineamenti in caso di aggiornamento degli stessi), anche perché
   in alcuni casi di competenza di specifiche amministrazioni;

-  guide, specifiche, documenti tecnici, manuali e altri materiali
   formativi che forniscono indicazioni tecniche puntuali, specie se
   definiti nell’ambito del framework europeo che non si ritiene di
   scalare o ridefinire a livello nazionale per garantire la coerenza e
   l’interoperabilità in un contesto superiore.

Tale sezione è rappresentata come segue:

.. topic:: Risorse utili
  :class: useful-docs

  - :mimetype:`text/html` `titolo-documento + link`_

  - :mimetype:`application/pdf` `titolo-documento + link`_


Termini e definizioni
~~~~~~~~~~~~~~~~~~~~~

Ai fini del presente documento, oltre alle definizioni pertinenti di cui
all’art. 2 del Decreto, si applicano le seguenti definizioni:


**collective database**

indica un database in forma non modificata come parte di una raccolta di
database indipendenti che insieme sono assemblati in una unica
collezione. Un’opera che costituisce un “collective database” (Banca
Dati Collettiva) non sarà considerata una Banca Dati Derivata [fonte:
ODbL license]


**DRM clause (clausola DRM)**

Nella licenza ODbL definita come “eventuali termini o misure
tecnologiche presenti nel Database, in un Database Derivato, o in tutto
o in parte sostanziale dei contenuti che alterano o limitano i termini
della Licenza”, intesa, quindi, come divieto di imposizione salvo
possibilità di lasciare copia aperta.

Nella licenza CC-BY definita come “misure che, in assenza di apposita
autorità, possono non essere eluse ai sensi di leggi che adempiono agli
obblighi di cui all'articolo 11 del Trattato WIPO sul diritto d’autore
adottato il 20 dicembre 1996, e/o accordi internazionali simili”, intesa
quindi come divieto di imposizione senza alternative


**produced work**

un’opera (come un’immagine, materiale audiovisivo, testo o suoni)
risultante dall’utilizzo della totalità o di una parte sostanziale dei
contenuti (tramite una ricerca o altra query) da un Database, inteso
come un Database Derivato, o da un Database inteso come parte di una
banca dati collettiva (collective database) [fonte: ODbL license]


**raccomandazione**

possibile scelta suggerita senza necessariamente escluderne altre


**requisito**

criterio da soddisfare per garantire la conformità al documento e da cui
non è consentita alcuna deviazione


**result from computational use**

risultati o output che l’utente ottiene dall’analisi (attraverso l’uso
di dispositivi di calcolo o altro) o da altre interpretazioni dei dati


Acronimi
~~~~~~~~

Di seguito si riportano gli ACRONIMI che sono utilizzati nelle presenti
Linee Guida.

+----------------+--------------------------------------------------------+
| **API**        | Application Programming Interface                      |
+----------------+--------------------------------------------------------+
| **CAD**        | Codice dell’Amministrazione Digitale                   |
+----------------+--------------------------------------------------------+
| **CC**         | Creative Commons                                       |
+----------------+--------------------------------------------------------+
| **CMS**        | Content Management System                              |
+----------------+--------------------------------------------------------+
| **CSV**        | Comma Separated Value                                  |
+----------------+--------------------------------------------------------+
| **D. Lgs.**    | Decreto Legislativo                                    |
+----------------+--------------------------------------------------------+
| **DCAT**       | Data Catalog Vocabulary                                |
+----------------+--------------------------------------------------------+
| **DCAT-AP**    | Data Catalog Vocabulary - Application Profile          |
+----------------+--------------------------------------------------------+
| **DCAT-AP_IT** | Data Catalog Vocabulary - Application Profile ITaliano |
+----------------+--------------------------------------------------------+
| **DRM**        | Digital Rights Management                              |
+----------------+--------------------------------------------------------+
| **HTTP**       | HyperText Transfer Protocol                            |
+----------------+--------------------------------------------------------+
| **INSPIRE**    | INfrastructure for SPatial InfoRmation in Europe       |
+----------------+--------------------------------------------------------+
| **ICT**        | Information and Communication Technology               |
+----------------+--------------------------------------------------------+
| **IPA**        | Indice della Pubblica Amministrazione                  |
+----------------+--------------------------------------------------------+
| **ISA**        | Interoperability Solutions for public Administration   |
+----------------+--------------------------------------------------------+
| **LOD**        | Linked Open Data                                       |
+----------------+--------------------------------------------------------+
| **JSON**       | JavaScript Object Notation                             |
+----------------+--------------------------------------------------------+
| **OD**         | Open Data                                              |
+----------------+--------------------------------------------------------+
| **OWL**        | Ontology Web Language                                  |
+----------------+--------------------------------------------------------+
| **PA**         | Pubblica Amministrazione                               |
+----------------+--------------------------------------------------------+
| **PSI**        | Public Sector Information                              |
+----------------+--------------------------------------------------------+
| **RDF**        | Resource Description Framework                         |
+----------------+--------------------------------------------------------+
| **RDFS**       | RDF Schema                                             |
+----------------+--------------------------------------------------------+
| **RNDT**       | Repertorio Nazionale Dati Territoriali                 |
+----------------+--------------------------------------------------------+
| **SDMX**       | Statistical Data and Metadata eXchange                 |
+----------------+--------------------------------------------------------+
| **SPARQL**     | Sparql Protocol And Rdf Query Language                 |
+----------------+--------------------------------------------------------+
| **URI**        | Uniform Resource Identifier                            |
+----------------+--------------------------------------------------------+
| **XML**        | eXtensible Markup Language                             |
+----------------+--------------------------------------------------------+

