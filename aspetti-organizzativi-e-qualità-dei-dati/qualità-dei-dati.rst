.. _par-5-3:

Qualità dei dati
~~~~~~~~~~~~~~~~

Il miglioramento della qualità dei dati e la maggiore diffusione delle
tecniche di misurazione dipendono da vari fattori tra cui l’adesione a
modelli di qualità condivisi.

Per determinare la bontà dei dati è necessario definire delle misure
attraverso le quali quantificare la qualità dei dati. Lo standard
ISO/IEC 25012:2008, divenuto norma italiana UNI ISO/IEC 25012:2014,
definisce un insieme di caratteristiche specifiche per la
caratterizzazione della qualità dei dati: accuratezza, aggiornamento,
completezza, consistenza, credibilità, accessibilità, comprensibilità,
conformità, efficienza, precisione, riservatezza, tracciabilità,
disponibilità, portabilità e ripristinabilità.

La Determinazione Commissariale n. 68/2013 di AgID [1]_, relativa alle
regole tecniche per l’identificazione delle basi di dati critiche tra
quelle di interesse nazionale specificate sulla base dell’art. 60 del
CAD, disponeva che venisse garantito il rispetto di quattro
caratteristiche, delle 15 previste dallo Standard ISO/IEC 25012, ovvero:

-  **accuratezza** (sintattica e semantica) - il dato, e i suoi
   attributi, rappresenta correttamente il valore reale del concetto o
   evento cui si riferisce;

-  **coerenza** - il dato, e i suoi attributi, non presenta
   contraddittorietà rispetto ad altri dati del contesto d’uso
   dell’amministrazione titolare;

-  **completezza** – il dato risulta esaustivo per tutti i suoi valori
   attesi e rispetto alle entità relative (fonti) che concorrono alla
   definizione del procedimento;

-  **attualità** (o tempestività di aggiornamento) - il dato, e i suoi
   attributi, è del “giusto tempo” (è aggiornato) rispetto al
   procedimento cui si riferisce.

.. admonition:: should

     **Raccomandazione 7**: dlgs36-2006/opendata/req/organization/quality

     SI RACCOMANDA di garantire, per tutti i dati in generale e per quelli resi disponibili per il riutilizzo, in particolare, il rispetto almeno delle quattro caratteristiche di qualità dei dati, delle 15 previste dallo Standard ISO/IEC 25012 (ovvero accuratezza, coerenza, completezza e attualità), come da indicazioni della Determinazione Commissariale n. 68/2013 di AgID. Per la misura delle suddette caratteristiche, fare riferimento allo Standard ISO/IEC 25024.


Il passo successivo è quantificare queste caratteristiche in termini di
misure, individuando delle soglie che consentano di discriminare la
bontà o meno di un dato rispetto alla caratteristica in esame. La fase
di valutazione della qualità dei dati è importante in tutti i sistemi
informativi indipendentemente dalla loro apertura. Con l’adozione di
politiche di apertura dei dati, la qualità dei dati assume un ruolo
ancora più rilevante in quanto elemento per la certificazione della
bontà dei dati forniti e soprattutto dell’appropriatezza rispetto
all’utilizzo che del dato si vuole fare.

L’ISO/IEC 25024 estende l’ISO/IEC 25012 “Data quality model” al campo
delle misurazioni, definendo 63 misure di qualità applicabili alle 15
caratteristiche di qualità dei dati, con le relative funzioni di
calcolo.

Nella tabella che segue si riporta un insieme esemplificativo di misure,
sulle 24 definite nello standard ISO per le stesse caratteristiche, a
supporto delle attività di valutazione della qualità dei dati delle
amministrazioni.

.. table:: Caratteristiche di qualità e relative misure
   :name: caratteristiche-qualità

+-----------------------+-----------------------+-----------------------+
| **Caratteristiche**   | **Descrizione**       | **Misure e funzioni   |
|                       |                       | di misura**           |
+-----------------------+-----------------------+-----------------------+
| **Completezza**       | il grado per cui il   | Si individuano i      |
|                       | dato associato a      | seguenti livelli di   |
|                       | un’entità presenta    | completezza:          |
|                       | valori per tutti gli  |                       |
|                       | attributi attesi e    | 1. completezza di     |
|                       | relative istanze in   | schema: 1)            |
|                       | un certo contesto.    | percentuale di valori |
|                       |                       | nulli per concetti e  |
|                       |                       | proprietà rispetto al |
|                       |                       | numero totale di      |
|                       |                       | valori attesi;        |
|                       |                       |                       |
|                       |                       | 2. completezza dei    |
|                       |                       | record: 2) numero di  |
|                       |                       | dati elementari       |
|                       |                       | associati a un valore |
|                       |                       | non nullo in un       |
|                       |                       | record, rispetto al   |
|                       |                       | numero di dati        |
|                       |                       | elementari del record |
|                       |                       | per cui può essere    |
|                       |                       | misurata la           |
|                       |                       | completezza;          |
|                       |                       |                       |
|                       |                       | 3. completezza di     |
|                       |                       | popolazione:          |
|                       |                       | percentuale di valori |
|                       |                       | nulli rispetto a una  |
|                       |                       | popolazione di        |
|                       |                       | riferimento. Si noti  |
|                       |                       | che non sempre valori |
|                       |                       | mancanti indicano     |
|                       |                       | incompletezza. Per    |
|                       |                       | esempio: si supponga  |
|                       |                       | di considerare dati   |
|                       |                       | relativi ai musei     |
|                       |                       | italiani e ai loro    |
|                       |                       | canali di contatto    |
|                       |                       | (telefono ed email).  |
|                       |                       | Può capitare che i    |
|                       |                       | musei abbiano tutti   |
|                       |                       | un indirizzo email ma |
|                       |                       | non per tutti è       |
|                       |                       | presente un numero di |
|                       |                       | telefono.             |
+-----------------------+-----------------------+-----------------------+
| **Accuratezza**       | Il grado in cui gli   | Si individuano due    |
|                       | attributi             | tipi di accuratezza:  |
|                       | rappresentano in      |                       |
|                       | maniera corretta il   | 1. sintattica: ad     |
|                       | valore reale del dato | esempio Merio invece  |
|                       | in uno specifico      | che Mario             |
|                       | contesto              |                       |
|                       |                       | 2. semantica: ad      |
|                       |                       | esempio nel caso in   |
|                       |                       | cui si utilizzi Marco |
|                       |                       | Rossi intendendo      |
|                       |                       | invece un’altra       |
|                       |                       | persona per es.,      |
|                       |                       | Mario Rossi           |
|                       |                       |                       |
|                       |                       | Una misura            |
|                       |                       | dell’accuratezza è    |
|                       |                       | data dalla ratio tra  |
|                       |                       | gli attributi dei     |
|                       |                       | dati che hanno valori |
|                       |                       | accurati              |
|                       |                       | sintatticamente/seman |
|                       |                       | ticamente             |
|                       |                       | sul numero di         |
|                       |                       | attributi dei dati    |
|                       |                       | per i quali è         |
|                       |                       | richiesta accuratezza |
|                       |                       | sintattica/semantica. |
+-----------------------+-----------------------+-----------------------+
| **Coerenza**          | Il grado in cui gli   | Per poter valutare la |
|                       | attributi del dato    | coerenza una misura è |
|                       | non sono in           | quella che consente   |
|                       | contraddizione con    | di identificare le    |
|                       | altri dati in uno     | violazioni di regole  |
|                       | specifico contesto    | semantiche definite   |
|                       |                       | su alcuni elementi    |
|                       |                       | dei dati.             |
|                       |                       |                       |
|                       |                       | Per esempio, se una   |
|                       |                       | persona è “patentata” |
|                       |                       | non può essere        |
|                       |                       | possibile che la sua  |
|                       |                       | età sia “17 anni”.    |
|                       |                       |                       |
|                       |                       | Essa può essere       |
|                       |                       | calcolata come la     |
|                       |                       | ratio tra il numero   |
|                       |                       | di attributi dei dati |
|                       |                       | i cui valori sono     |
|                       |                       | semanticamente        |
|                       |                       | corretti nel dataset  |
|                       |                       | sul numero di         |
|                       |                       | attributi dei dati    |
|                       |                       | per i quali sono      |
|                       |                       | state definite delle  |
|                       |                       | regole semantiche.    |
|                       |                       |                       |
|                       |                       | Altra misura consiste |
|                       |                       | nel rapporto tra il   |
|                       |                       | numero di valori      |
|                       |                       | duplicati per ogni    |
|                       |                       | attributo della base  |
|                       |                       | dati e il numero      |
|                       |                       | totale degli elementi |
|                       |                       | della base dati.      |
+-----------------------+-----------------------+-----------------------+
| **Tempestività**      | Il grado in cui gli   | La metrica è basata   |
|                       | attributi del dato    | sull’uso dei metadati |
|                       | sono al «giusto       | che indicano quando   |
|                       | tempo» rispetto al    | il dato è stato       |
|                       | contesto di           | aggiornato l’ultima   |
|                       | riferimento           | volta.                |
|                       |                       |                       |
|                       |                       | Sulla base di questi  |
|                       |                       | metadati, si          |
|                       |                       | distinguono poi:      |
|                       |                       |                       |
|                       |                       | 1. dati con           |
|                       |                       | periodicità di        |
|                       |                       | aggiornamento nota:   |
|                       |                       | in questo caso 1) è   |
|                       |                       | possibile calcolare   |
|                       |                       | la tempestività in    |
|                       |                       | maniera esatta        |
|                       |                       | identificando se la   |
|                       |                       | data di ultima        |
|                       |                       | modifica del dato     |
|                       |                       | rispetto al tempo di  |
|                       |                       | misurazione ricade    |
|                       |                       | nell’intervallo della |
|                       |                       | frequenza di          |
|                       |                       | aggiornamento;        |
|                       |                       |                       |
|                       |                       | 2. dati con           |
|                       |                       | periodicità di        |
|                       |                       | aggiornamento media:  |
|                       |                       | in questo caso è      |
|                       |                       | possibile calcolare   |
|                       |                       | la tempestività media |
|                       |                       | con una percentuale   |
|                       |                       | di errore.            |
+-----------------------+-----------------------+-----------------------+

Lo Standard ISO/IEC 25012 è applicabile a tutte le tipologie di dati.
Nel caso di dati territoriali uno standard specifico di riferimento per
la qualità è l’ISO 19157 “Geographic information -- Data quality”.

Alcuni elementi e misure di tale Standard sono utilizzati per
identificare requisiti e raccomandazioni per la qualità dei dati nella
sezione “7 - Data quality” delle specifiche sui dati definite per
ciascun tema INSPIRE [2]_.

Per i dati territoriali di cui ai temi INSPIRE, pertanto, dovranno
essere considerati gli elementi e le misure definite nelle specifiche
citate innanzi.


.. [1]
   https://www.agid.gov.it/sites/default/files/repository_files/circolari/dt_cs_n.68_-_2013dig_-regole_tecniche_basi_dati_critiche_art_2bis_dl_179-2012_sito.pdf

.. [2]
   https://inspire.ec.europa.eu/Technical-Guidelines/Data-Specifications/2892
