.. _par-7-1:

Pubblicazione dei dati
~~~~~~~~~~~~~~~~~~~~~~

.. _par-7-1-1:

API
^^^

Per i dati dinamici e le serie di dati di elevato valore il Decreto
prevede che i dati debbano essere resi disponibili attraverso
un’interfaccia per programmi applicativi (API), che, come da
definizione, è un insieme di funzioni, procedure, definizioni e
protocolli per la comunicazione da macchina a macchina e lo scambio
ininterrotto di dati.

La Direttiva evidenzia che per la creazione e l’impiego di API è
necessario basarsi su alcuni principi: disponibilità, stabilità,
manutenzione per tutto il ciclo di vita, uniformità di utilizzo e delle
norme, facilità d’uso e sicurezza.

In tema di API, con la Determinazione di AgID n. 547/2021 [1]_ sono
state adottate le “\ *Linee Guida sull’interoperabilità tecnica delle
Pubbliche Amministrazioni*\ ” e le “\ *Linee Guida Tecnologie e standard
per la sicurezza dell’interoperabilità tramite API dei sistemi
informatici*\ ”, che definiscono le modalità con cui le Pubbliche
Amministrazioni implementano le proprie API, quale elemento tecnologico
di base del Modello di Interoperabilità (ModI), e individuano le
soluzioni tecniche idonee a garantire l’autenticazione dei soggetti
coinvolti e la protezione, l’integrità e la riservatezza dei dati
scambiati nelle interazioni tra sistemi informatici della pubblica
amministrazione e di questi con i sistemi informatici di soggetti
privati per il tramite di API.

Le API che il Decreto indica di utilizzare per rendere disponibili dati
dinamici e serie di dati di elevato valore DEVONO essere sviluppate e
pubblicate in conformità con le Linee Guida citate innanzi.

.. admonition:: must

    **REQUISITO 27**: dlgs36-2006/opendata/req/publication/api

    Le API sviluppate per rendere disponibili i dati per il riutilizzo devono essere conformi alle “Linee Guida sull’interoperabilità tecnica delle Pubbliche Amministrazioni” e le “Linee Guida Tecnologie e standard per la sicurezza dell’interoperabilità tramite API dei sistemi informatici”, adottate con la Determinazione di AgID n. 547/2021.


Dette Linee Guida individuano il Catalogo delle API quale componente,
unica e centralizzata, che assicura alle parti coinvolte nel rapporto di
erogazione e fruizione la consapevolezza sulle API disponibili, e per
esse, i livelli di servizio dichiarati. Tale Catalogo, in applicazione
dell’art. 50 ter del **CAD**, è reso disponibile attraverso la
Piattaforma Digitale Nazionale Dati a cui si applicano le indicazioni
delle “\ *Linee Guida sull’infrastruttura tecnologica della Piattaforma
Digitale Nazionale Dati per l’interoperabilità dei sistemi informativi e
delle basi di dati*\ ” adottate con la Determinazione di AgID n.
627/2021 [2]_.

La coerenza con le Linee Guida suddette garantisce anche l’adempimento di quanto previsto nella bozza di Regolamento UE relativa ai dati di elevato valore (v. par. :ref:`par-4-3`), in particolare con la previsione di cui all’art. 3(2) circa le condizioni di utilizzo delle API e i criteri di qualità del servizio.

Considerato che, come evidenziato dalla Direttiva, è, in generale,
vantaggioso riutilizzare e condividere i dati tramite un impiego
adeguato di API, perché possono aiutare gli sviluppatori e le start-up a
creare nuovi servizi e prodotti e rappresentano, inoltre, un elemento
fondamentale della strutturazione di ecosistemi di valore attorno a un
patrimonio di dati spesso inutilizzato, è fortemente raccomandato
l’utilizzo di API per rendere disponibili per il riutilizzo anche quelle
tipologie di dati per le quali il Decreto non prevede tale disposizione.

.. admonition:: should

    **Raccomandazione 14**: dlgs36-2006/opendata/rec/publication/api

    Ove possibile, si raccomanda di utilizzare API conformi al Requisito 27 per rendere disponibili per il riutilizzo tutte le tipologie di dati, non solo quelli dinamici e/o di elevato valore.

Nel caso di dati territoriali, viste le regole tecniche di cui alle
linee guida INSPIRE per l’implementazione dei servizi di rete di cui
all’art. 7 comma 1 del **D-LGS-32-2010**, **detti servizi di rete
possono essere considerati come API** in considerazione del fatto che
nell’ambito delle Linee Guida sull’interoperabilità tecnica delle PA,
accettando la nomenclatura in uso a livello europeo e più in generale
nel contesto internazionale, si utilizza il termine generico API per
indicare indifferentemente le Web API, i web service e le API REST.

.. admonition:: must

    **REQUISITO 28**: dlgs36-2006/opendata/req/publication/inspire-ns

    Nel caso di dati territoriali, il Requisito 27 è attuato attraverso l’implementazione dei servizi di rete di cui all’art. 11 della Direttiva 2007/2/CE, del Regolamento (CE) n. 976/2009 e delle relative linee guida tecniche.


.. topic:: Risorse utili
  :class: useful-docs

  - :mimetype:`application/pdf` `Linee Guida sull’interoperabilità tecnica delle Pubbliche Amministrazioni, adottate con la Determinazione AgID n. 547/2021 del 1° ottobre 2021 <https://trasparenza.agid.gov.it/moduli/downloadFile.php?file=oggetto_allegati/212801215110O__OLinee+Guida+interoperabilit%26%23224%3B+tecnica+PA.pdf>`_

  - :mimetype:`application/pdf` `Linee Guida Tecnologie e standard per la sicurezza dell’interoperabilità tramite API dei sistemi informatici, adottate con la Determinazione AgID n. 547/2021 del 1° ottobre 2021  <https://trasparenza.agid.gov.it/moduli/downloadFile.php?file=oggetto_allegati/212801214540O__OLinee+Guida+Tecnologie+e+standard+sicurezza+interoperabilit%26%23224%3B+API+sistemi+informatici.pdf>`_

  - :mimetype:`application/pdf` `Linee Guida sull’infrastruttura tecnologica della Piattaforma Digitale Nazionale Dati per l’interoperabilità dei sistemi informativi e delle basi di dati, adottate con la Determinazione di AgID n. 627/2021 del 15 dicembre 2021 <https://trasparenza.agid.gov.it/moduli/downloadFile.php?file=oggetto_allegati/213481831510O__O20211210_LG+Infrastruttura+Interoperabilit%26%23224%3B+PDND_v1.pdf>`_

  - :mimetype:`text/html` `OpenAPI Checker, Developers Italia <https://developers.italia.it/it/software/pcm-italia-api-oas-checker>`_

  - :mimetype:`text/html` `Guide tecniche INSPIRE per i servizi di rete <https://inspire.ec.europa.eu/Technical-Guidelines2/Network-Services/41>`_

  - :mimetype:`text/html` `Strategia Cloud Italia <https://innovazione.gov.it/dipartimento/focus/strategia-cloud-italia/>`_
  

.. _par-7-1-1-1:

Sicurezza e disponibilità dei dati
''''''''''''''''''''''''''''''''''

L’art. 51 comma 1 del **CAD** demanda a specifiche Linee guida
l’individuazione delle soluzioni tecniche idonee a **garantire la
protezione, la disponibilità, l’accessibilità, l’integrità e la
riservatezza dei dati** e la continuità operativa dei sistemi e delle
infrastrutture.

Tali Linee Guida sono state definite nell’ambito del modello di
interoperabilità delle pubbliche amministrazioni e corrispondono alle
già citate Linee Guida “\ *Tecnologie e standard per la sicurezza
dell’interoperabilità tramite API dei sistemi informatici*\ ”, che
definiscono le tecnologie e le loro modalità di utilizzo al fine di
garantire la sicurezza delle transazioni digitali realizzate tra e verso
le pubbliche amministrazioni che utilizzano le API tramite rete di
collegamento informatica.

L’implementazione di API coerenti con il Requisito 27, pertanto,
assicura il rispetto degli adempimenti e la conformità al citato art. 51
del **CAD**.

Nell’ambito della Strategia Cloud Italia, a cui si rimanda, inoltre, al fine di
regolamentare l’offerta di servizi cloud disponibili sul mercato per
mitigare i rischi sistemici di sicurezza e affidabilità, è stata
definita una classificazione dei dati e dei servizi allo scopo di
definire un processo di classificazione dei dati, in base al danno che
una loro compromissione potrebbe provocare al sistema Paese (strategici,
critici e ordinari). Il risultato della classificazione, si legge nella
strategia, consente di uniformare e guidare il processo di migrazione al
Cloud della PA. Le classi individuate sono:

-  Strategico: dati e servizi la cui compromissione può avere un impatto
   sulla sicurezza nazionale;

-  Critico: dati e servizi la cui compromissione potrebbe determinare un
   pregiudizio al mantenimento di funzioni rilevanti per la società, la
   salute, la sicurezza e il benessere economico e sociale del Paese;

-  Ordinario: dati e servizi la cui compromissione non
   provochi l’interruzione di servizi dello Stato o, comunque, un
   pregiudizio per il benessere economico e sociale del Paese.


.. _par-7-1-2:

Elementi architetturali
^^^^^^^^^^^^^^^^^^^^^^^

I principali livelli architetturali che compongono una soluzione per la
pubblicazione e interrogazione di dati aperti possono essere istanziati
in diverso modo a seconda delle capacità economiche e tecniche delle
amministrazioni, nonché della qualità del servizio che si vuole offrire
agli utenti. Si distinguono due livelli: livello di front-end e livello
infrastrutturale. Il livello di front-end consiste di una parte di
presentazione che può essere sia un sito Web, sia una sezione in un sito
esistente. In questa parte rientrano tutti quegli strumenti che
consentono di dare massima visibilità ai dati disponibili e di
interagire in maniera “user-friendly” con gli utenti stessi, per esempio
per capire quali dati sono di loro interesse, quali nuovi dati sono
richiesti, quali suggerimenti vogliono dare per migliorare anche la
qualità dei dati. Il livello di presentazione si completa con
l’interfaccia di accesso via web per interrogazioni puntuali sui dati e
metadati. Questa ha come obiettivo quello di aumentare l’interazione
machine-to-machine attraverso il dispiegamento di una piattaforma di
esposizione dati basata su API di servizio (o Open Data Service). Nel
caso di dati dei livelli 4 e 5 del modello per i dati, l’interfaccia di
accesso via web è rappresentata dallo SPARQL endpoint.

In generale, si raccomanda di:

-  assegnare ai dataset nomi autoesplicativi per comprenderne il
   principale contenuto;

-  fornire, ove possibile, descrizioni testuali dei dataset;

-  mettere in evidenza la licenza in uso in forma “human and
   machine-readable”;

-  fornire, ove possibile, strumenti di visualizzazione e navigazione,
   anche georiferita, dei dati, che possano facilitare la lettura degli
   stessi;

-  fornire, ove possibile, statistiche di uso, accesso e produzione;

-  fornire notifiche di cambiamenti nel sito web, di aggiornamenti ai
   dataset (per es., RSS feed);

-  fornire strumenti per rendere le interrogazioni più agevoli, anche
   per utenti non del tutto esperti. Nel caso dei dati dei livelli 4 e 5
   non si può pubblicare solo dataset RDF ma è bene mettere in evidenza
   la presenza dello SPARQL endpoint (cioè, un servizio Web che accetta
   interrogazioni SPARQL, le risolve e restituisce i risultati in
   output), pubblicando il link di accesso, fornendo altresì un ampio
   insieme di “query” di esempio che con pochi click possono essere
   eseguite producendo risultati disponibili in diversi formati di più
   comune utilizzo soprattutto nell’ambito delle comunità open data (per
   es., CSV, JSON, XML).

Nei casi di amministrazioni di minori dimensioni o amministrazioni che
non siano nelle condizioni di poter fornire un servizio con le
caratteristiche sopra elencate, si consiglia di implementare azioni di
sussidiarietà verticale (ad esempio, i comuni di medio-piccole
dimensioni possono riferirsi alla Regione di appartenenza) o di unirsi
in iniziative comuni.

Il livello infrastrutturale è rappresentato dall’infrastruttura che
ospita i dati e i metadati. Nel caso di dati aperti, tenuto conto della
loro natura intrinseca, ovvero dati tipicamente non riferibili a singole
persone e per i quali solitamente non si richiede il soddisfacimento di
specifici requisiti di protezione dei dati personali, tecnologie basate
sul paradigma del cloud computing pubblico possono essere facilmente
impiegabili al fine di ospitare le infrastrutture per la pubblicazione
di dati aperti.

In tema di cloud, la Strategia Cloud Italia, già citata innanzi,
definita dal Dipartimento per la trasformazione digitale e dall’Agenzia
per la cybersicurezza nazionale (ACN), contiene gli indirizzi strategici
per il percorso di migrazione verso il cloud di dati e servizi digitali
della Pubblica Amministrazione. Per l’attuazione della strategia AgID ha
adottato, con la Determinazione n. 628/2021, il Regolamento che
definisce i requisiti minimi per le infrastrutture digitali e le
caratteristiche e le modalità di qualificazione e migrazione dei servizi
cloud.


.. topic:: Risorse utili
  :class: useful-docs

  - :mimetype:`text/html` `Strategia Cloud Italia <https://innovazione.gov.it/dipartimento/focus/strategia-cloud-italia/>`_

  - :mimetype:`application/pdf` `Regolamento recante i livelli minimi di sicurezza, capacità elaborativa, risparmio energetico e affidabilità delle infrastrutture digitali per la PA e le caratteristiche di qualità, sicurezza, performance e scalabilità, portabilità dei servizi cloud per per la pubblica amministrazione, le modalità di migrazione, nonché le modalità di qualificazione dei servizi cloud per la pubblica amministrazione, adottato con la Determinazione AgID n. 628/2021 del 15 dicembre 2021 <https://trasparenza.agid.gov.it/archivio28_provvedimenti-amministrativi_0_123065_725_1.html>`_
  
  
.. _par-7-1-3:

Identificatori univoci e persistenti
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Nei requisiti per i dati della ricerca volti a rendere tali dati
conformi ai principi FAIR si è fatto riferimento più volte a
identificatori univoci e persistenti. Tali identificatori (che è buona
prassi applicare a tutti i dati non solo quelli della ricerca) sono
generalmente rappresentati dagli URI (Uniform Resource Identifier), una
sequenza di caratteri che identifica una risorsa astratta o fisica. Essi
sono utilizzati nei linked data (v. par. :ref:`par-5-1-4`) per risolvere il
problema dell’identità.

Gli URI devono essere persistenti e dereferenziabili. Una politica per
garantire URI persistenti e fornire aspetti di naming è proposta in uno
studio dalla Commissione Europea (v. box “Risorse utili” in calce).
Facendo riferimento a tale documento, per la creazione di URI
persistenti sono da evitare quelli che contengano:

-  nome del progetto/ufficio/unità amministrativa che detiene la risorsa
   per evitare problemi derivanti dalla fine del progetto stesso o
   fusioni o chiusure di uffici nell’organizzazione;

-  numeri di versione;

-  identificatori esistenti che in passato sono stati utilizzati per
   identificare risorse differenti;

-  riferimenti generati in modo automatico e incrementale a meno che non
   vi sia la garanzia che il processo non venga mai più ripetuto o, se
   ripetuto, generi sicuramente gli stessi identificatori per gli stessi
   dati di input;

-  stringhe rappresentanti “query” a database;

-  estensione del file.

Sono, invece, da ritenersi buone pratiche le seguenti:

-  strutturare l’URI come segue:

http://{dominio}/{tipo}/{concetto}/{riferimento}

-  includere nell’ URI i seguenti elementi:

   -  dominio: il dominio Web su cui reperire la risorsa

   -  tipo: l’elemento che specifica il tipo di risorsa. Dovrebbe poter
      assumere un numero limitato di valori come “doc” se la risorsa
      identificata è un documento descrittivo, “set” se la risorsa è un
      dataset, “id” o “item” se la risorsa è un oggetto del mondo reale

   -  concetto: il tipo di un oggetto del mondo reale

   -  riferimento: lo specifico elemento, termine o concetto che
      rappresenta la risorsa

-  costruire URI per più formati al fine di identificare al meglio la
   risorsa

-  collegare tra loro le rappresentazioni multiple della stessa risorsa

-  implementare il codice di risposta 303 per gli oggetti del mondo
   reale (si veda sotto “content negotiation” e “dereferenziazione”
   degli URI)

-  utilizzare servizi dedicati.

Nella gestione degli URI è opportuno utilizzare il meccanismo
cosiddetto di “\ *content negotiation*\ ” che consente di rendere
disponibile, allo stesso URI, diverse rappresentazioni di una risorsa in
caso di molteplici rappresentazioni possibili (per es. URI che
rappresentano sia entità del web semantico sia risorse web). Così come è
una buona prassi utilizzare sempre URI “deferenziabili”, come già
indicato prima, cioè URI che restituiscono una rappresentazione web (es.
una pagina web informativa) di una risorsa.


.. topic:: Risorse utili
  :class: useful-docs

  - :mimetype:`text/html` `Cool URIs for the Semantic Web, W3C <https://www.w3.org/TR/cooluris/>`_

  - :mimetype:`application/pdf` `Study on persistent URIs, with identification of best practices and recommendations on the topic for the MSs and the EC, programma ISA, Commissione Europea <https://joinup.ec.europa.eu/sites/default/files/document/2013-02/D7.1.3 - Study on persistent URIs.pdf>`_


.. [1] https://trasparenza.agid.gov.it/archivio28_provvedimenti-amministrativi_0_123008_725_1.html

.. [2] https://trasparenza.agid.gov.it/archivio28_provvedimenti-amministrativi_0_123064_725_1.html
