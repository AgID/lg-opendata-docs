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


.. toctree::
  :maxdepth: 3
  :caption: Indice dei contenuti

  strumenti-per-la-ricerca/elenchi-delle-categorie-e-modalità-di-ricerca.rst


.. [1]
   https://dati.gov.it

.. [2]
   https://geodati.gov.it

.. [3]
   https://inspire-geoportal.ec.europa.eu/

.. [4]
   Decisione di esecuzione (UE) 2019/1372 della Commissione del 19
   agosto 2019 recante attuazione della direttiva 2007/2/CE del
   Parlamento europeo e del Consiglio per quanto riguarda il
   monitoraggio e la comunicazione
