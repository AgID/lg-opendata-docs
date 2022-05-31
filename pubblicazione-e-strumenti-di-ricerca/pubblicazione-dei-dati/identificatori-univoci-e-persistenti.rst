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
