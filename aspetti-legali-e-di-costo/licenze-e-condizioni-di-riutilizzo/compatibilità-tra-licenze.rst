.. _par-6-1-1:

Compatibilità tra licenze
^^^^^^^^^^^^^^^^^^^^^^^^^

Anche le licenze “aperte”, analogamente alle licenze open source, presentano differenti gradi di apertura (non sono, quindi, sempre “aperte allo stesso modo”), ovvero prevedono condizioni che, pur autorizzando il riutilizzo, possono non rendere percorribile un riutilizzo “mescolato” tra più fonti; tali condizioni, pertanto, possono non consentire una successiva pubblicazione/utilizzo nel rispetto di tutte le condizioni previste da ciascuna licenza (incompatibilità).

Per fare un esempio, due licenze aperte cd. “share alike” – che richiedono di rilasciare ogni evoluzione successiva con la medesima licenza nei medesimi termini – permettono il rilascio di un mashup solo se tra loro identiche, o se tra loro sia stata riconosciuta una eventuale equivalenza (v. infra).

Inoltre, anche nel caso di licenze fra loro compatibili, si segnala che dovranno sempre essere rispettate le relative condizioni di ridistribuzione, tenendo, altresì, conto delle eventuali diversità sull’ambito di applicazione e/o di esenzione: per esempio, alcune licenze richiedono di segnalare le modifiche, o escludono dal perimetro di applicazione le elaborazioni algoritmiche o i prodotti derivati di natura diversa dal database di origine, etc...  Anche a tale fine, quindi, si è di seguito provato a evidenziare le principali condizioni e/o peculiarità presenti nelle principali licenze standard, individuando in quali trovano applicazione (v. **Tabella 4**).

Sul tema della compatibilità, infine, si ritiene opportuno distinguere l’ipotesi della evoluzione di una precedente, singola fonte (sub a)), dalla creazione di un nuovo dataset costituito da più fonti diverse e diversamente licenziate (sub b)):

a) **evoluzione di una fonte terza (opera “derivata”)**

In questo caso, la licenziabilità della soluzione e le relative condizioni saranno influenzate solo dalla licenza originaria: la tabella che segue è relativa alla possibilità di produrre un dataset “derivato”, in linea con le indicazioni fornite con le presenti Linee Guida ovvero, in CC-BY 4.0 o, in subordine, CC0 o CDLA 2.0 permissive (v. Figura che segue).

.. figure:: /media/licenze-opera-derivata.png
   :name: licenze-opera-derivata
   :alt: La figura mostra le licenze applicabili all’opera derivata in funzione della licenza originaria.

   Licenze applicabili all’opera derivata in funzione della licenza originaria

** il sito della CDLA (v. box infra) ritiene compatibile la CC BY 4.0 con il rilascio in CDLA 2.0 permissive, a condizione di rispettare l’attribution originale (anche se non raccomandato, per non creare “strati” di attribuzione”, come da wiki delle CC di cui al link nel box “Risorse utili, par. “Adapter’s license chart”). Analogo ragionamento a fortiori parrebbe essere applicabile per la IODL 2.0.

Sempre come esempio, se si elabora un db rilasciato originariamente in CC BY SA, o in OdBL, sì dovrà rilasciare anche il nuovo DB in CC BY SA o rispettivamente OdBL (salvo l’eccezione del “produced work” per l’OdBL).


b) **sviluppo di un nuovo dataset/database tramite unione/riutilizzo in
   tutto o in parte di dataset/database terzi diversi**

In questo caso, è necessario verificare che le licenze originarie non risultino incompatibili con la pubblicazione (v. Figura seguente) relative alle peculiarità del caso.

.. figure:: /media/licenze-opera-mashup.png
   :name: licenze-opera-mashup
   :alt: La figura mostra la matrice di compatibilità tra licenze.

   Matrice di compatibilità tra licenze


Quest’ultima figura espone, quindi, una matrice di compatibilità - necessariamente limitata alle principali licenze standard - che distingue i casi in cui la combinazione delle fonti permetta di licenziare la soluzione come da indicazioni (verde), comunque aperta (giallo) o produca un blocco (rosso).

In entrambe le fidure (come da legenda in calce) si è provato a dettagliare meglio alcuni aspetti che, pur non impedendo il riutilizzo, sono da considerarsi punti di attenzione.

Si fa riferimento, a titolo di esempio:


-  al rischio di cumulo delle attribuzioni (cd. “stack of attribution”), presente anche nelle licenze solo “permissive” (mera attribuzione), ma diverse tra loro, le quali presentano, a volte, specifiche diverse, in merito alle modalità con cui assolvere all’obbligo di "attribution". Tali specifiche possono rendere complessa la gestione delle licenze (si pensi, per esempio, ai dati geografici, per i quali l’uso di fonti diverse e ricorsive può rendere difficile detto governo);

-  ai limiti all’apponibilità di misure tecnologiche di protezione, in quanto alcune licenze (ad esempio, la CC-BY 4.0) contengono un divieto di apporre tali soluzioni, senza eccezioni; altre licenze non contemplano detto profilo (come la IODL); altre ancora contemplano tale divieto, individuando, tuttavia, soluzioni alternative (es. l’OdBL, che prevede il divieto, ma anche la possibilità alternativa di apporre dette misure, a condizione che una copia del database rimanga accessibile senza restrizioni);

-  a specifiche distinzioni sulle modalità di utilizzo delle fonti, prevista in alcune licenze (come l’OdBl rispetto ai “database collettivi”), e/o alla diversa gestione, anche sotto il profilo del “copyleft”, del licensing del prodotto identificabile come “derivato” (ad esempio, nell’OdBL per il cd. “produced work” - classico esempio, le mappe rispetto al DB geografico - e nella CDLA per i “results from computational use”, ovvero i risultati di una analisi algoritmica di diverse fonti per la produzione di un risultato “diverso”).

Questi ultimi aspetti sono peculiari ed esulano dalla necessaria semplificazione funzionale alle tabelle sottese; SI RACCOMANDA, pertanto, di fare comunque riferimento, per eventuali approfondimenti, alla serie di risorse utili indicate nel box, svolgendo, ove necessario, specifiche verifiche.

**Legenda:**

.. figure:: /media/licenze-legenda.png
   :name: licenze-legenda
   :alt: La figura mostra la legenda delle figure di cui sopra.

   Legenda

.. table:: Compatibilità tra licenze - Condizioni da osservare / specifiche di applicazione
   :name: compatibilità-licenze

+-------+----------------------------+------------------------------------------------------------------------------------------+
| Cod.  | Condizioni da osservare/   | Licenze impattate                                                                        |   
|       | specifiche di applicazione |                                                                                          |           
+=======+============================+===================+==============+==============+=======+============+===========+=======+
| A     | segnalazione modifica      | CDLA 1 perm       | CDLA 1 shar  |              | CC-BY |            |           |       |
|       | cambiamenti                |                   |              |              |       |            |           |       |
+-------+----------------------------+-------------------+--------------+--------------+-------+------------+-----------+-------+
| B     | testo licenza: con         | CDLA 1 perm       | CDLA  1 shar | CDLA 2 perm  | CC-BY | [IODL 2.0] | IODL 1.0  | OdBL  |
|       | riferimento al dataset     |                   |              |              |       |            |           |       |
|       | originale, riportare il    |                   |              |              |       |            |           |       |
|       | testo della licenza e/o    |                   |              |              |       |            |           |       |
|       | inserire link (tra [] per) |                   |              |              |       |            |           |       |
|       | la IODL in quanto precisa  |                   |              |              |       |            |           |       |
|       | “se possibile")            |                   |              |              |       |            |           |       |
+-------+----------------------------+-------------------+--------------+--------------+-------+------------+-----------+-------+
| C     | attributon: rispetto       | CDLA 1 perm       | CDLA 1 shar  |              | CC-BY | IODL 2.0   | IODL 1.0  | OdBL  |
|       | specifiche condizioni      |                   |              |              |       |            |           |       |
+-------+----------------------------+-------------------+--------------+--------------+-------+------------+-----------+-------+
| D     | output ulteriore realizzato|                   |              |              |       |            |           | OdBL  |
|       | [“Produced work" - es.     |                   |              |              |       |            |           |       |  
|       | Mappa da db geografico];   |                   |              |              |       |            |           |       |
|       | richiede sola attribution  |                   |              |              |       |            |           |       |
+-------+----------------------------+-------------------+--------------+--------------+-------+------------+-----------+-------+
| E     | risultato da "computational| CDLA 1 perm       | CDLA 1 shar/ | CDLA 2 perm  |       |            |           |       |
|       | use" senza condizioni      |                   | perm 1 e 2   |              |       |            |           |       |
+-------+----------------------------+-------------------+--------------+--------------+-------+------------+-----------+-------+
| F     | prevede la nozione di      |                   |              |              |       |            |           | OdBL  |
|       | “collective database"      |                   |              |              |       |            |           |       |
+-------+----------------------------+-------------------+--------------+--------------+-------+------------+-----------+-------+
| G     | limiti DRM                 |                   |              |              | CC-BY |            |           | OdBL  |
+-------+----------------------------+-------------------+--------------+--------------+-------+------------+-----------+-------+


.. [1] v. https://blog.openstreetmap.org/2017/03/17/use-of-cc-by-data/

.. [2] v. https://blog.openstreetmap.org/2017/03/17/use-of-cc-by-data/
