.. _par-5-1-5:

Documentazione
^^^^^^^^^^^^^^

Una fase molto importante nel processo di preparazione dei dati è la
definizione di sintassi (cioè struttura) e semantica (cioè contenuto).
Questo, oltre a migliorare l’interoperabilità, la qualità e a
facilitarne l’elaborazione, aumenta anche il valore dei dati stessi,
poiché l’interpretazione errata dei dati diventa meno probabile quando
viene fornito il contesto.

Come detto innanzi, questa fase può corrispondere alla prima del
processo nel caso il dato ancora non esista e, quindi, si parte dalla
definizione di un’ontologia o comunque di un modello dati del dominio,
cioè dalla definizione sintattica e semantica dei dati in termini di
entità rappresentate, loro attributi e associazioni (cosiddetta fase di
modellazione).

Rientra in questa fase anche la documentazione delle modifiche e degli
aggiornamenti dei dati oltre alla gestione delle relative versioni e la
storicizzazione.

**Modelli dati -** Il Piano Triennale ICT 2017-2019 definisce
un’ontologia o un modello dati condiviso come “\ *una
concettualizzazione esaustiva e rigorosa nell’ambito di un dato
dominio*\ ”.

Anche per garantire la coerenza tra i documenti, si richiama qui la fase
denominata “Semantica” nel processo digitale individuato e descritto
nelle Linee Guida per l’interoperabilità tecnica, in cui si evidenzia
che la comunicazione tra soggetti DEVE utilizzare modelli dati
condivisi, in modo da razionalizzare e uniformare la rappresentazione
dell’informazione quale presupposto per favorire l’interoperabilità tra
soggetti differenti.

Le Linee Guida di cui sopra hanno già definito una serie di requisiti in
tema di modelli dati. Come indicato nel documento citato, pertanto,
nell’individuazione delle entità da condividere i diversi soggetti
DEVONO:

1) Individuare i domini di interesse e in essi determinare le entità da
   rappresentare in termini di proprietà che li caratterizzano;

2) Verificare la presenza delle entità per dominio tra quelli definiti a
   livello nazionale da AgID nella rete di ontologie e vocabolari
   controllati Ontopia [1]_.

Ad integrazione di quanto sopra, considerato quanto previsto dall’art. 6
comma 9 del Decreto, per i dati territoriali i modelli dati da
considerare sono quelli definiti nell’ambito delle attività di
regolamentazione derivanti da **INSPIRE-DIR** e nell’ambito del
framework nazionale che fa riferimento ai decreti 10/11/2011 e alle
attività di estensione delle regole INSPIRE (v. par. :ref:`par-4-5`).

Si aggiunge, pertanto, un ulteriore requisito:

3) Nel caso di dati territoriali, verificare la presenza delle entità
   per dominio tra quelli definiti a livello europeo e nazionale
   nell’ambito della regolamentazione INSPIRE e la sua estensione
   nazionale.

Come indicato nelle citate Linee Guida, successivamente all’attuazione
delle regole 2) e 3) ci si può trovare in uno dei seguenti casi:

a) tutte le entità e le relative proprietà trovano copertura;

b) almeno una delle entità non è compresa nelle rappresentazioni;

c) almeno una proprietà di un’entità presente non risulta rappresentata.

Nel caso a), il soggetto ha tutti gli elementi per rappresentare il
proprio modello dati; viceversa, nei casi b) e c), la stessa
amministrazione, in accordo con AgID, valuta l’opportunità di estendere
il modello dati a livello nazionale.

La regola che, in generale, deve guidare è di esaminare modelli dati,
ontologie e vocabolari controllati esistenti per verificare se i
concetti hanno già entità, proprietà e, ove presenti, URI ampiamente
adottati, specie se in ambito europeo. Solo in caso contrario, l’ente
che pubblica i dati può definire e pubblicare il proprio modello dati,
ontologia o vocabolario controllato al fine di definire concetti che non
sono stati specificati altrove.

**Conservazione e storicizzazione** - I dataset rilasciati costituiscono
non solo una risorsa per la collettività, ma un prezioso patrimonio
anche per le pubbliche amministrazioni che possono in questo modo
archiviare in modo alternativo i loro dati in modalità indipendente
dagli applicativi software originali che li hanno prodotti. Per questo
motivo è importante premunirsi di un sistema di
archiviazione/conservazione che mantenga le diverse versioni dei dati
nel lungo periodo. A tal fine si raccomanda di assicurare che le
versioni stesse siano accessibili a un URL stabile, che sia anche
documentato unitamente alla pubblicazione del dato.

A tale proposito, il Decreto stabilisce che le pubbliche
amministrazioni e gli organismi di diritto pubblico debbano utilizzare
le modalità per facilitare la conservazione dei documenti disponibili
per il riutilizzo secondo quanto previsto dall’articolo 44 del **CAD**.


.. topic:: Risorse utili
 :class: useful-docs

 - :mimetype:`text/html` `Ontopia – rete ontologie <https://github.com/italia/daf-ontologie-vocabolari-controllati>`_

 - :mimetype:`application/pdf` `Linee Guida sulla formazione, gestione e conservazione dei documenti informatici, adottate con la Determinazione AgID n. 407/2020 come modificate con la Determinazione AgID n. 371/2021 <https://www.agid.gov.it/sites/default/files/repository_files/linee_guida_sul_documento_informatico.pdf>`_

 - :mimetype:`application/pdf` `Regolamento sui criteri per la fornitura dei servizi di conservazione dei documenti informatici, adottato con la Determinazione AgID n. 455/2021 del 25 giugno 2021 <https://trasparenza.agid.gov.it/archivio28_provvedimenti-amministrativi_0_122919_725_1.html>`_



.. [1] v. https://github.com/italia/daf-ontologie-vocabolari-controllati. Tale risorsa confluirà nel Catalogo Nazionale Dati per l’interoperabilità semantica, il cui rilascio, secondo quanto indicato nel Piano Triennale 2021-2023, è previsto per l’anno corrente.
