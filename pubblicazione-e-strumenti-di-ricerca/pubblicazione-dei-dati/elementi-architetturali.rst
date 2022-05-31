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
consentono di (i) dare massima visibilità ai dati disponibili e (ii) di
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
