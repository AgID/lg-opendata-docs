.. _par-4-1:

Requisiti comuni
˜˜˜˜˜˜˜˜˜˜˜˜˜˜˜˜

Sulla base dell’art. 1 del Decreto, le presenti linee guida si applicano
ai “\ *documenti contenenti*\ **dati
pubblici**\ *nella*\ **disponibilità**\ *delle*\ **pubbliche
amministrazioni**\ *, degli*\ **organismi di diritto pubblico**\ *e
delle*\ **imprese pubbliche e private**\ ”, con esclusione dei casi
riportati al par. :ref:`par-1-2`.

Il Decreto, così come la Direttiva, utilizza il termine “documento”
nell’accezione di cui all’art. 2 lettera c), cioè “\ *la
rappresentazione di atti, fatti e dati a prescindere dal supporto,
cartaceo o elettronico, registrazione sonora, visiva o audiovisiva o
qualsiasi parte di tale contenuto nella disponibilità della pubblica
amministrazione o dell’organismo di diritto pubblico*\ ”. La definizione
di documento non comprende i programmi informatici ma include qualsiasi
parte del documento stesso. L’altro concetto utilizzato è quello di
“dato pubblico” definito nel medesimo articolo, lettera d), come il
“\ *dato conoscibile da chiunque*\ ”.

I dati pubblici che rientrano nell’ambito di applicazione delle presenti
linee guida DEVONO essere messi a disposizione **per il riutilizzo a
fini commerciali e non commerciali**:

-  in **formato leggibile meccanicamente**, cioè, come da definizione
   presente nel Decreto, in “\ *un formato di file strutturato in modo
   tale da consentire alle applicazioni software di individuare,
   riconoscere ed estrarre facilmente dati specifici, comprese
   dichiarazioni individuali di fatto e la loro struttura interna*\ ”;

-  in **formato aperto**, cioè, come da definizione dell’art. 1 comma 1
   lettera l-bis) del CAD, in “\ *un formato di dati reso pubblico,
   documentato esaustivamente e neutro rispetto agli strumenti
   tecnologici necessari per la fruizione dei dati stessi*\ ”;

-  **accessibili** attraverso le tecnologie dell’informazione e della
   comunicazione;

-  **gratuitamente o con i costi marginali** sostenuti per la
   riproduzione, messa a disposizione e divulgazione dei documenti,
   nonché per l’anonimizzazione di dati personali o per le misure
   adottate per proteggere le informazioni commerciali a carattere
   riservato (v. par. :ref:`par-6-2`);

-  secondo i termini di **licenze standard**, disponibili in formato
   digitale (v. par. :ref:`par-6-1`);

-  provvisti dei relativi **metadati** (v. par. :ref:`par-4-6`).

Tali indicazioni rappresentano le caratteristiche dei **dati di tipo
aperto** come da definizione fornita all’art. 1 comma 1 lettera l-ter)
del **CAD**.

.. topic:: **REQUISITO 1**: dlgs36-2006/opendata/req/common/guidelines

    I soggetti di cui al par. :ref:`par-1-3` devono rendere disponibili i documenti e i dati di cui al par. :ref:`par-1-1` per il riutilizzo a fini commerciali e non commerciali secondo quanto indicato nelle presenti Linee Guida.

Nella figura che segue è mostrata una rappresentazione delle tipologie
di dati pubblici.

Il concetto di disponibilità può essere derivato dal **CAD** nella
definizione presente prima delle modifiche apportate dal decreto
legislativo 26 agosto 2016, n. 179. Sulla base della formulazione
originaria del **CAD**, per disponibilità si intende “\ *la possibilità
di accedere ai dati senza restrizioni non riconducibili a esplicite
norme di legge*\ ”.

Come detto, il Decreto si applica ai **documenti pubblici** nella
**disponibilità** degli enti indicati al par. :ref:`par-1-3` e che presentino
le caratteristiche dei **dati di tipo aperto** indicate innanzi.

.. figure:: ./media/tipi-dati.png
   :name: tipi-dati
   :alt: La figura mostra le tipologie di dati pubblici.

   Tipi di dato pubblico


Per la scelta del formato da utilizzare per il rispetto delle
caratteristiche indicate innanzi, si può fare riferimento all’allegato
A, che riporta il modello a 5 stelle per i dati aperti, e l’allegato B,
che descrive i formati più comuni.

.. topic:: **REQUISITO 2**: dlgs36-2006/opendata/req/common/3stars

    I dati devono essere resi disponibili in formato aperto e leggibile meccanicamente ad un livello di almeno 3 stelle nella classificazione del modello di cui all’allegato A.

Ulteriori elementi per la scelta del formato da utilizzare si possono
rinvenire nella figura seguente tratta dal documento “\ **Data.europa.eu
- Data Quality Guidelines**\ ” [1]_ che riporta l’elenco dei formati
utilizzati comunemente specificando quali siano leggibili meccanicamente
e non proprietari. L’ultima colonna indica il numero di stelle
ottenibili utilizzando il corrispondente formato per la pubblicazione
dei dati. I formati evidenziati in verde sono quelli che dovrebbero
essere utilizzati; se questo non è possibile allora si possono
utilizzare quelli evidenziati in giallo, mentre sono da escludere quelli
evidenziati in rosso.

.. figure:: ./media/formati-dati-aperti.png
   :name: formati-dati-aperti
   :alt: La figura mostra i formati più comuni per i dati aperti e relativi
   livelli di apertura.

   Formati più comuni per i dati aperti e relativi
   livelli di apertura


\* Il documento evidenzia che i formati *txt* e *html* dovrebbero essere valutati con tre stelle, poiché i dati potrebbero essere progettati per essere leggibili dalla macchina. Tuttavia, viene
assegnata solo una stella perché questi formati non erano
originariamente concepiti per rappresentare contenuti leggibili dalla
macchina ma solo dall’uomo. La rappresentazione di contenuti leggibili
automaticamente in questi formati non soddisfa, quindi, le migliori
pratiche e pertanto non sono consigliati dagli autori del documento.

.. topic:: **REQUISITO 3**: dlgs36-2006/opendata/req/common/more-formats

    Nel caso in cui un dato sia disponibile in più formati, almeno uno di essi deve essere coerente con il REQUISITO 1.

.. topic:: **Raccomandazione 1**: dlgs36-2006/opendata/rec/common/lod

    Si raccomanda un percorso graduale verso la produzione nativa di Linked Open Data – LOD (livello cinque stelle).

Nel caso in cui mettere a disposizione i propri dati secondo
le indicazioni di cui sopra, per soddisfare richieste di apertura,
comporti attività che vanno al di là della semplice manipolazione, e
che, quindi, implicherebbero difficoltà sproporzionate, gli enti
pubblici (cioè pubbliche amministrazioni e organismi di diritto
pubblico) non hanno l’obbligo di adeguare i documenti o crearne nuovi o
fornire estratti di documenti. In tal caso, attraverso un apposito
provvedimento, l’ente titolare DEVE motivare le difficoltà
sproporzionate indicando le attività sui dati che eccedono la semplice
manipolazione.

.. topic:: **REQUISITO 4**: dlgs36-2006/opendata/req/common/no-od

    Nel caso in cui, per soddisfare richieste di apertura, rendere disponibili i dati per il riutilizzo comporti attività che vanno al di là della semplice manipolazione che implicherebbero difficoltà sproporzionate, il titolare dei dati non ha l’obbligo di adeguare i documenti o crearne nuovi o fornire estratti di documenti, motivando, attraverso un apposito provvedimento, le difficoltà sproporzionate anche indicando le attività sui dati che eccedono la semplice manipolazione.

Quanto indicato in questo paragrafo è valido per tutte le
tipologie di dati, così come i requisiti definiti negli altri capitoli.
Il Decreto individua particolari tipi di dati quali i dati dinamici, le
serie di dati di elevato valore e i dati della ricerca per i quali, nei
paragrafi successivi, saranno fornite specifiche indicazioni
supplementari in attuazione di quanto disposto dal Decreto.


.. topic:: Risorse utili
 :class: useful-docs

 - :mimetype:`application/pdf` `Open Data Goldbook for Data Managers and Data Holders - Practical guidebook for organizations wanting to publish Open Data, European Data Portal, 2018 <https://data.europa.eu/sites/default/files/european_data_portal_-_open_data_goldbook.pdf>`_

 - :mimetype:`application/pdf` `data.europa.eu – Data quality guidelines, Publications Office, 2021 <https://op.europa.eu/it/publication-detail/-/publication/023ce8e4-50c8-11ec-91ac-01aa75ed71a1/language-en>`_


.. [1]
    Publications Office of the European Union, *Data.europa.eu - Data
   Quality Guidelines*, 2021 disponibile al seguente link:
   https://op.europa.eu/it/publication-detail/-/publication/023ce8e4-50c8-11ec-91ac-01aa75ed71a1/language-en
