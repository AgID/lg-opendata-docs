.. _par-7-2:

Strumenti per la ricerca
~~~~~~~~~~~~~~~~~~~~~~~~

Il Decreto individua come strumenti per la ricerca dei dati il
**catalogo nazionale dei dati aperti**\  [1]_ e, per i dati
territoriali, il **Repertorio Nazionale dei Dati Territoriali
(RNDT)**\  [2]_ di cui all’art. 59 del **CAD**, entrambi gestiti da
AgID.

Ai sensi dell’articolo 9 del Decreto, **il portale nazionale dei dati
aperti (dati.gov.it) è l’unico riferimento per la documentazione e la
ricerca di tutti i dati aperti della pubblica amministrazione**. Esso,
in quanto punto di accesso nazionale per i metadati dei dati aperti, **è
l’unico ad abilitare il colloquio con l’analogo** `portale ufficiale dei
dati europei <https://data.europa.eu/>`__ data.europa.eu.

Il portale nazionale include i metadati, conformi al profilo DCAT-AP_IT,
che descrivono i dati aperti delle amministrazioni secondo quanto
indicato al par. :ref:`par-4-6`.

.. admonition:: must

    **REQUISITO 29**: dlgs36-2006/opendata/req/publication/od-portal

    Le amministrazioni sono tenute a inserire e a mantenere aggiornati nel portale dati.gov.it, attraverso le modalità di alimentazione previste dal catalogo, i metadati dei dati, ad esclusione di quelli territoriali.


I dati, il cui riferimento è pubblicato sul portale nazionale,
rimangono presso il titolare del dato che conserva la responsabilità
della loro correttezza, tenuta, gestione, aggiornamento e divulgazione a
livello nazionale.

.. admonition:: must

    **REQUISITO 30**: dlgs36-2006/opendata/req/publication/rndt

    I dati territoriali devono essere documentati esclusivamente presso il Repertorio Nazionale dei Dati Territoriali (RNDT) che, in maniera automatizzata, si occupa dell’allineamento con il portale nazionale dei dati aperti dati.gov.it.

L’integrazione dei due cataloghi avviene attraverso la specifica
GeoDCAT-AP che fornisce una sintassi RDF per i metadati INSPIRE e ISO
19115 (profilo core) e la sua estensione italiana che è stata definita
con la *Guida nazionale per l’implementazione della specifica
GeoDCAT-AP* (v. box Risorse utili).

Nella citata Guida sono definite, tra l’altro, le due regole principali
così formulate:

1. I dati territoriali, anche quando sono resi disponibili secondo il
   paradigma open data, **devono essere documentati ESCLUSIVAMENTE nel
   RNDT** secondo le regole nazionali sui metadati dei dati territoriali
   e le relative guide operative;

2. Il RNDT garantirà l’accesso ai dati territoriali “di tipo aperto”
   anche nel catalogo nazionale dei dati aperti (dati.gov.it), secondo
   lo standard DCAT-AP_IT, attraverso GeoDCAT-AP e sulla base delle
   corrispondenze definite nel documento.

Sulla base di queste regole e delle corrispondenze definite tra i
metadati dei due standard di riferimento, i dati territoriali aperti
documentati nel RNDT sono resi accessibili attraverso le funzionalità
tipiche del catalogo nazionale dei dati aperti, dati.gov.it, senza
nessun ulteriore adempimento da parte dei titolari di dati.

Come indicato nelle Linee Guida RNDT, il Repertorio, in quanto punto di
accesso nazionale per i metadati dei dati territoriali, provvede a
rendere disponibili i metadati anche al geoportale INSPIRE [3]_ secondo
le modalità individuate per l’applicazione di **INSPIRE-DIR**, anche ai
fini delle operazioni di monitoraggio di cui alla Decisione di
esecuzione (UE) 2019/1372 della Commissione Europea [4]_.

Nella figura che segue è rappresentato lo schema di coordinamento e
integrazione tra i due cataloghi nazionali e la loro interazione con i
portali europei.

.. figure:: /media/interoperabilità-cataloghi.png
   :name: interoperabilità-cataloghi
   :alt: La figura mostra lo schema di coordinamento e integrazione tra i due cataloghi nazionali e la loro interazione con i portali europei.

   Interoperabilità tra cataloghi nazionali ed europei



.. topic:: Risorse utili
  :class: useful-docs

  - :mimetype:`application/pdf` `Guida nazionale per l’implementazione della specifica GeoDCAT-AP <https://geodati.gov.it/geoportale/images/struttura/documenti/GeoDCAT-AP_IT-v1.0.pdf>`_


.. _par-7-2-1:

Elenchi delle categorie e modalità di ricerca
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Il Decreto dispone che i soggetti destinatari delle presenti Linee Guida
debbano individuare le modalità per facilitare la ricerca, anche
interlinguistica, dei documenti disponibili per il riutilizzo, insieme
ai rispettivi metadati, ove possibile accessibili on-line e in formati
leggibili meccanicamente. Tale disposizione è attuata attraverso il
rispetto dei Requisiti 20 e 21 definiti innanzi.

Il Decreto prevede, inoltre, quanto indicato nel seguente
Requisito 31.

.. admonition:: must

    **REQUISITO 31**: dlgs36-2006/opendata/req/publication/categories

    I destinatari delle presenti Linee Guida devono pubblicare e aggiornare annualmente sui propri siti istituzionali gli elenchi delle categorie di dati detenuti ai fini del riutilizzo attraverso collegamenti ipertestuali al portale nazionale dati.gov.it.


Per adempiere a tale disposizione, considerato che in base ai Requisiti
20 e 21 i dati devono essere documentati nel portale nazionale dei dati
aperti dati.gov.it, **si può pubblicare sul proprio sito istituzionale,
eventualmente in una sezione dedicata agli open data**, anche al fine di
evitare eventuali duplicazioni, **un collegamento ipertestuale (anche
sfruttando le API disponibili sul portale nazionale), per ciascuna
categoria tematica** (facendo riferimento ai temi DCAT-AP [5]_), ai propri
dataset pubblicati nel portale nazionale. Un esempio di URL da inserire
nel proprio sito istituzionale è il seguente:

.. admonition:: example
   :class: admonition-example display-page

   .. role:: link-themes-data
      :class: link-themes-data

   `Esempio di URL`:link-themes-data:

    https://dati.gov.it/view-dataset?holder_name=%22Provincia%20Autonoma%20di%20Trento%22&groups=ambiente

dove l’amministrazione titolare è la Provincia Autonoma di Trento e
la categoria è “ambiente”.

Nel caso di dati territoriali aperti, come già indicato, questi vanno
documentati esclusivamente nel RNDT che li renderà disponibili anche in
dati.gov.it, consentendo, quindi, la creazione del collegamento
ipertestuale di cui sopra.

Per la pubblicazione dei metadati nel catalogo nazionale, ci si può
avvalere **dei principi di sussidiarietà verticale**, già in precedenza
menzionati, o **adottare autonomamente una delle possibili soluzioni**
descritte di seguito.

Per quanto riguarda la sussidiarietà verticale, nell’ambito locale, **le
Regioni possono assumere il ruolo di aggregatori territoriali**. In
sostanza, la Regione, ove possibile, si coordina con le varie
amministrazioni che operano nell’ambito territoriale della Regione
stessa, raccogliendo le informazioni sui dataset disponibili in Open
Data e assicurando una adeguata frequenza di aggiornamento. Le
amministrazioni locali delegano così la Regione all’esposizione dei
propri metadati e **possono evitare di richiedere direttamente la
raccolta degli stessi da parte del portale nazionale**; quest’ultimo si
interfaccia quindi con i soli cataloghi regionali.

Lo stesso modello può applicarsi nei casi di amministrazioni centrali
che svolgono un ruolo di “coordinamento” nei riguardi di altre
amministrazioni. In questo caso, si richiede che le amministrazioni
comunichino tale situazione al portale nazionale durante la fase di
richiesta di raccolta.

Per quanto riguarda le possibili soluzioni “autonome”, che possono
essere adottate anche qualora il modello di sussidiarietà di cui sopra
non potesse essere applicato (per es., per mancanza di un catalogo
regionale o difficoltà, anche tecniche, di colloquio tra i diversi
livelli amministrativi locali), di seguito si riportano alcune di queste
possibili soluzioni per la creazione di piattaforme di pubblicazione dei
dati.

**Soluzione nativa.** Viene creato un portale ad-hoc o creata
un’apposita sezione di un portale esistente. In questo caso, la
creazione non differisce dalla creazione di un sito web classico.

**Estensione soluzione CMS esistente.** Molto spesso l’amministrazione
gestisce già un sito web, realizzato mediante l’uso di un CMS, che vuole
estendere con una sezione dedicata agli Open Data. La criticità in
questo caso è data dall’aggiunta di una componente semantica all’interno
della configurazione del CMS stesso.

**Utilizzo di piattaforme esterne.** Viene utilizzata una piattaforma
che include funzionalità per la catalogazione, visualizzazione,
ricerca e interrogazione dei dati. In alcuni casi queste piattaforme
sono disponibili in modalità «\ *as a service*\ ». 

.. admonition:: should

    **Raccomandazione 15**: dlgs36-2006/opendata/rec/publication/portals

    SI RACCOMANDA di non creare tanti portali diversi per singole iniziative ma, ove possibile, di raccordarle per facilitare il reperimento e il riutilizzo dei dati da parte degli utenti finali.


.. [1] https://dati.gov.it

.. [2] https://geodati.gov.it

.. [3] https://inspire-geoportal.ec.europa.eu/

.. [4] Decisione di esecuzione (UE) 2019/1372 della Commissione del 19 agosto 2019 recante attuazione della direttiva 2007/2/CE del Parlamento europeo e del Consiglio per quanto riguarda il monitoraggio e la comunicazione

.. [5] v. https://op.europa.eu/en/web/eu-vocabularies/concept-scheme/-/resource?uri=http://publications.europa.eu/resource/authority/data-theme
