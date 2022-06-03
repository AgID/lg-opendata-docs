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
categoria tematica** (facendo riferimento ai temi DCAT-AP [1]_), ai propri
dataset pubblicati nel portale nazionale. Un esempio di URL da inserire
nel proprio sito istituzionale è il seguente:

.. admonition:: example
   :class: admonition-example display-page

   .. role:: link-themes-data
      :class: link-themes-data

   `Esempio di URL`:link-themes-data:

    https://dati.gov.it/view-dataset?holder_name=%22Regione%20Autonoma%20della%20Sardegna%22&groups=ambiente

dove l’amministrazione titolare è la Regione Autonoma della Sardegna e
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


.. [1]
    v.
   https://op.europa.eu/en/web/eu-vocabularies/concept-scheme/-/resource?uri=http://publications.europa.eu/resource/authority/data-theme
