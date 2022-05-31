Arricchimento
^^^^^^^^^^^^^

Una volta che i dati sono bonificati, possono essere arricchiti
attraverso l’integrazione con altri dati e il linking esterno.
L’arricchimento è definito dal documento “Data quality guidelines” del
Publications Office come il concetto di collegare i dati da fonti
esterne ai set di dati esistenti ed è un processo, secondo il documento,
costituito sia dalla standardizzazione che dall’arricchimento vero e
proprio.

**Vocabolari controllati** - Come indicato nel documento “Data quality
guidelines”, un livello più alto di standardizzazione può essere
raggiunto facendo riferimento a vocabolari controllati, quali elenchi di
codici, tassonomie, classificazioni o terminologie, definiti nel Piano
Triennale ICT 2017-2019 come “\ *un modo comune e condiviso per
organizzare codici e nomenclature ricorrenti in maniera standardizzata e
normalizzata*\ ”. I vocabolari controllati assegnano ad ogni concetto un
identificatore univoco e persistente (URI), in modo che quel concetto
venga referenziato in maniera non ambigua, e garantiscono, inoltre, la
gestione in modo coerente delle diverse versioni. Possono essere
associate anche etichette, definizioni e descrizioni anche in diverse
lingue.

I vocabolari fanno sì che invece di utilizzare nei dati le etichette,
queste possano essere referenziate dagli identificatori univoci
assegnati, in modo che, se le etichette dovessero cambiare, il
riferimento non deve essere adeguato, riducendo l’onere di manutenzione
per i titolari di dati. In più, siccome gli URI possono essere
deferenziati (v. par. :ref:`par-7-1-3`), ciò consente di risolvere l’etichetta
in qualsiasi lingua supportata dal vocabolario controllato.

AgID rende disponibili i vocabolari controllati definiti nell’ambito
della rete Ontopia [1]_ e, per i dati territoriali, il Sistema di
Registri INSPIRE Italia (v. box “Risorse utili”).

**Integrazione con altri dati -** L’arricchimento dei dati può essere
ottenuto, come detto, anche integrando informazioni da sorgenti esterne
rendendo in questo modo i dati di origine più significativi e fruibili.
Il valore aggiunto è ottenuto per esempio producendo i dati mashup già
citati in precedenza.

**Linked Open Data** - Come detto, il collegamento (linking) dei dati
può aumentarne il valore creando nuove relazioni e consentendo così
nuovi tipi di analisi.

Nel caso in cui il processo sia finalizzato alla produzione di linked
open data, come evidenziato nelle già citate Linee Guida per
l’interoperabilità semantica attraverso i Linked Open Data, “\ *il
linking è una funzionalità molto importante e di fatto può essere
considerata una forma particolare di arricchimento. La particolarità
consiste nel fatto che l’arricchimento avviene grazie all’interlinking
fra dataset di origine diversa, tipicamente fra amministrazioni o
istituzioni diverse, ma anche, al limite, all'interno di una stessa
amministrazione*\ ”.

Tale collegamento è possibile soprattutto attraverso l’uso coerente di
identificatori univoci, gli URI, di cui si è parlato prima e che vengono
approfonditi ulteriormente nel par. :ref:`par-7-1-3`.

I linked data, oltre agli URI, utilizzano diversi standard e tecniche,
tra cui il framework RDF, e risorse come i vocabolari controllati, di
cui si è detto innanzi, il cui utilizzo ottimale può essere ottenuto
facendo riferimento a formati di dati a quattro stelle come le
serializzazioni RDF o il JSON-LD. Nell’allegato B sono riportati, nella
prima parte, anche i principali standard di riferimento necessari anche
ad abilitare i livelli 4 e 5 del modello dei dati di cui all’allegato A.

Utilizzando il framework RDF, si può costruire un grafo semantico, noto
anche come grafo della conoscenza, che può essere percorso dalle
macchine risolvendo, cioè dereferenziando, gli URI HTTP. Ciò significa
che è possibile estrarre automaticamente informazione e derivare,
quindi, contenuto informativo aggiuntivo (inferenza).

Alcune delle fasi indicate nel percorso di cui alla :ref:`Figura <processo-preparazione-dati>` possono
essere comuni al processo di produzione dei Linked Open Data. Tale
processo è caratterizzato da altre fasi, non rappresentate nel percorso
comune, ma dettagliate nelle Linee Guida citate innanzi a cui si
rimanda, come già raccomandato in precedenza. È importante notare che
nella pratica si ritiene a volte necessario passare da modelli di
rappresentazione tradizionali come quello relazionale per la
modellazione dei dati operando opportune trasformazioni per poi renderli
disponibili secondo i principi dei Linked Open Data. Tuttavia, tale
pratica non è necessariamente quella più appropriata: esistono
situazioni per cui può essere più conveniente partire da un’ontologia
del dominio e che si intende modellare e dall’uso di standard del web
semantico per poter governare i processi di gestione dei dati.


.. topic:: Risorse utili
 :class: useful-docs

 - :mimetype:`application/pdf` `Linee Guida sull’interoperabilità semantica attraverso i Linked Open Data <https://www.agid.gov.it/sites/default/files/repository_files/documentazione_trasparenza/cdc-spc-gdl6-interoperabilitasemopendata_v2.0_0.pdf>`_

 - :mimetype:`text/html` `Ontopia – vocabolari controllati <https://github.com/italia/daf-ontologie-vocabolari-controllati/tree/master/VocabolariControllati>`_

 - :mimetype:`text/html` `Sistema di Registri INSPIRE Italia <https://registry.geodati.gov.it/>`_



.. [1]
    Tale risorsa confluirà nel Catalogo Nazionale
   Dati per l’interoperabilità semantica, il cui rilascio, secondo
   quanto indicato nel Piano Triennale 2021-2023, è previsto nell’anno
   corrente.
