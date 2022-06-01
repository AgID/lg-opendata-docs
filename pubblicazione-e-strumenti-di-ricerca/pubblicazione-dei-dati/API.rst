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


.. toctree::
  :maxdepth: 3
  :caption: Indice dei contenuti

  API/sicurezza-e-disponibilità-dei-dati.rst

.. [1]
   https://trasparenza.agid.gov.it/archivio28_provvedimenti-amministrativi_0_123008_725_1.html

.. [2]
   https://trasparenza.agid.gov.it/archivio28_provvedimenti-amministrativi_0_123064_725_1.html
