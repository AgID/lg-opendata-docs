Compatibilità tra licenze
^^^^^^^^^^^^^^^^^^^^^^^^^

Anche le licenze “aperte”, analogamente alle licenze open source, non
sono sempre “aperte allo stesso modo”, ovvero prevedono condizioni che,
seppur autorizzando il riutilizzo, rendono non percorribile un
riutilizzo “mescolato”, che ne permetta, quindi, una successiva
pubblicazione/uso nel rispetto di tutte le condizioni previste da
ciascuna licenza (incompatibilità); così, due licenze aperte cd. “share
alike” – che richiedono di rilasciare ogni evoluzione successiva con la
medesima licenza ai medesimi termini – non permettono il rilascio di un
mashup (salvo che siano ovviamente tra loro identiche, o sia stata
riconosciuta una eventuale equivalenza tra loro, v. infra).

Sul tema della compatibilità, inoltre, sono potenzialmente da
distinguersi l’ipotesi della evoluzione di una precedente singola fonte
dalla costituzione di un nuovo dataset composto tramite il riferimento a
più fonti diverse e diversamente licenziate:

a) **evoluzione di una fonte terza (opera “derivata”)**

In questo caso, la licenziabilità della soluzione e le relative
condizioni di licenziabilità saranno eventualmente influenzate
esclusivamente dalla licenza originaria: la tabella che segue è relativa
alla possibilità di produrre un dataset “derivato”, in linea con le
indicazioni fornite con le presenti Linee Guida ovvero, in CC-BY 4.0 o,
in subordine, CC0 o CDLA 2.0 permissive (v. **Tabella 1** in calce al
paragrafo).

b) **sviluppo di un nuovo dataset/database tramite unione/riutilizzo in
   tutto o in parte di dataset/database terzi diversi**

In questo caso, l’analisi viene “complicata” dalla necessità di
verificare che le licenze originarie non risultino in sé non compatibili
con la pubblicazione (v. **Tabella 2** in calce al paragrafo).

Quest’ultima tabella presenta quindi una - seppur necessariamente
limitata alle principali licenze standard - matrice di compatibilità,
che distingua ove la “combinazione” permetta di produrre una soluzione
licenziata come da indicazioni (verde), comunque aperta (giallo) o
produca un blocco (rosso).

In entrambe le tabelle (come da legenda in calce) si è provato a
dettagliare meglio alcuni aspetti che, pur non impedendo il riutilizzo,
sono da considerarsi come punti di attenzione.

Si fa riferimento, a titolo di esempio:

-  al rischio di cumulo delle attribuzioni (cd. “stack of attribution”):
   anche licenze tutte “permissive” (mera attribuzione) - ma diverse tra
   loro - presentano a volte specifiche diverse, anche in merito alle
   modalità con cui assolvere all’obbligo di attribution stessa. Tali
   diversità possono rendere complessa la gestione progressiva, specie
   in contesti come ad esempio per i dati geografici - in cui l’uso di
   fonti diverse e ricorsive può rendere difficile detto governo;

-  ai limiti all’apponibilità di misure tecnologiche di protezione:
   alcune licenze (ad esempio, la scelta CC-BY 4.0) contengono un
   divieto di apporre tali soluzioni, senza eccezioni; altre licenze non
   contemplano detto profilo (come la IODL); altre ancora contemplano
   tale divieto, individuando tuttavia soluzioni alternative (es.
   l’OdBL, che prevede il divieto, ma anche la possibilità alternativa
   di apporre dette misure a condizione che una copia del database
   rimanga accessibile senza restrizioni);

-  a specifiche distinzioni sulle modalità di utilizzo delle fonti,
   prevista in alcune licenze (come l’OdBl rispetto ai “database
   collettivi”), e/o alla diversa gestione, anche sotto il profilo del
   “copyleft”, del licensing del prodotto identificabile come “derivato”
   (ad esempio, nell’OdBL per il cd. “produced work” - classico esempio
   le mappe rispetto al DB geografico - e nella CDLA per i “results from
   computational use”, ovvero i risultati di una analisi algoritmica di
   diverse fonti per la produzione di un risultato “diverso”).

Questi ultimi aspetti sono peculiari ed esulano dalla necessaria
semplificazione funzionale alle tabelle sottese; SI RACCOMANDA,
pertanto, di fare comunque riferimento, per eventuali approfondimenti,
alla serie di risorse utili indicate nel box, svolgendo, ove necessario,
specifiche verifiche relative alle peculiarità del caso.

+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| **lic | **CC0 | **CC- | **CC- | **IOD | **ODb | **CDL | **CDL | **CDL |
| enza  | **    | BY    | BY-SA | L     | L**   | A     | A     | A     |
| opera |       | 4.0** | 4.0** | 2.0** |       | 1.0   | 1.0   | 2.0   |
| “deri |       |       |       |       |       | perm* | shar* | perm* |
| vata” |       |       |       |       |       | *     | *     | *     |
| **    |       |       |       |       |       |       |       |       |
+=======+=======+=======+=======+=======+=======+=======+=======+=======+
| **lic |       |       |       |       |       |       |       |       |
| enza  |       |       |       |       |       |       |       |       |
| opera |       |       |       |       |       |       |       |       |
| origi |       |       |       |       |       |       |       |       |
| naria |       |       |       |       |       |       |       |       |
| **    |       |       |       |       |       |       |       |       |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| **CC0 |       | **[A- |       |       |       |       |       |       |
| **    |       | B-C]* |       |       |       |       |       |       |
|       |       | *     |       |       |       |       |       |       |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| **CC- |       | **[A- | **[A- | **[A- | **\*[ | **[A- | **[A- | **[A- |
| BY    |       | B-C]* | B-C]* | B-C]* | A-B-C | B-C]* | B-C]* | B-C]* |
| 4.0** |       | *     | *     | *     | ]**   | *     | *     | *     |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| **CC- |       |       | **[A- |       |       |       |       |       |
| BY-SA |       |       | B-C]* |       |       |       |       |       |
| 4.0** |       |       | *     |       |       |       |       |       |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| **IOD |       | **[B- | **[B- | **[B- | **[B- | **[B- | **[B- | **[B- |
| L     |       | C]**  | C]**  | C]**  | C]**  | C]**  | C]**  | C]**  |
| 2.0** |       |       |       |       |       |       |       |       |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| **IOD |       |       |       |       | **[B- |       |       |       |
| L     |       |       |       |       | C]**  |       |       |       |
| 1.0** |       |       |       |       |       |       |       |       |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| **ODb | **[D] | **[D] | **\*[ | **[D] | **[(A | **[D] |       | **[D] |
| L**   | **    | **    | D]**  | **    | )     | **    |       | **    |
|       |       |       |       |       | B-C-D |       |       |       |
|       |       |       |       |       | -F-G] |       |       |       |
|       |       |       |       |       | **    |       |       |       |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| **CDL | **[E] | **[A- | **[A- | **[A- | **[A- | **[A- | **[A- | **[A- |
| A     | **    | B-C-E | B-C-E | B-C-E | B-C-E | B-C-E | B-C-E | B-C-E |
| 1.0   |       | ]**   | ]**   | ]**   | ]**   | ]**   | ]**   | ]**   |
| perm* |       |       |       |       |       |       |       |       |
| *     |       |       |       |       |       |       |       |       |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| **CDL | **[E] | **[E] | **[E] | **[E] | **[E] | **[E] | **[A- | **[E] |
| A     | **    | **    | **    | **    | **    | **    | B-C-E | **    |
| 1.0   |       |       |       |       |       |       | ]**   |       |
| shar* |       |       |       |       |       |       |       |       |
| *     |       |       |       |       |       |       |       |       |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| **CDL | **[B- | **[B- | **[B- | **[B- | **[B- | **[B- | **[B- | **[B- |
| A     | E]**  | E]**  | E]**  | E]**  | E]**  | E]**  | E]**  | E]**  |
| 2.0   |       |       |       |       |       |       |       |       |
| perm* |       |       |       |       |       |       |       |       |
| *     |       |       |       |       |       |       |       |       |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+

**Tabella** **1** – Licenze applicabili all’opera derivata in funzione
della licenza originaria

+------+------+------+------+------+------+------+------+------+------+
| **li | **CC | **CC | **CC | **IO | **IO | **OD | **CD | **CD | **CD |
| cenz | 0**  | -BY  | -BY- | DL   | DL   | bL** | LA   | LA   | LA   |
| a    |      | 4.0* | SA   | 1.0* | 2.0* |      | 1.0  | 1.0  | 2.0  |
| oper |      | *    | 4.0* | *    | *    |      | perm | shar | perm |
| a    |      |      | *    |      |      |      | **   | **   | **   |
| 1**  |      |      |      |      |      |      |      |      |      |
+======+======+======+======+======+======+======+======+======+======+
| **li |      |      |      |      |      |      |      |      |      |
| cenz |      |      |      |      |      |      |      |      |      |
| a    |      |      |      |      |      |      |      |      |      |
| oper |      |      |      |      |      |      |      |      |      |
| a    |      |      |      |      |      |      |      |      |      |
| 2**  |      |      |      |      |      |      |      |      |      |
+------+------+------+------+------+------+------+------+------+------+
| **CC |      |      |      |      |      |      |      |      |      |
| 0**  |      |      |      |      |      |      |      |      |      |
+------+------+------+------+------+------+------+------+------+------+
| **CC |      |      | CC   | \*   |      | \*[D |      | \*   |      |
| -BY  |      |      | BY   | IODL |      | ]    |      | CDLA |      |
| 4.0* |      |      | SA   | 1.0  |      |      |      | 1sha |      |
| *    |      |      |      |      |      |      |      | r    |      |
+------+------+------+------+------+------+------+------+------+------+
| **CC | CC   | CC   | CC   |      | CC   |      | CC   |      | CC   |
| -BY- | BY   | BY   | BY   |      | BY   |      | BY   |      | BY   |
| SA   | SA   | SA   | SA   |      | SA   |      | SA   |      | SA   |
| 4.0* |      |      |      |      |      |      |      |      |      |
| *    |      |      |      |      |      |      |      |      |      |
+------+------+------+------+------+------+------+------+------+------+
| **IO |      |      | CC   | IODL |      | OdBL |      | CDLA |      |
| DL   |      |      | BY   | 1.0  |      |      |      | 1    |      |
| 2.0* |      |      | SA   |      |      |      |      | shar |      |
| *    |      |      |      |      |      |      |      |      |      |
+------+------+------+------+------+------+------+------+------+------+
| **IO | IODL | \*   | CC   | IODL | IODL | OdBL | IODL |      | IODL |
| DL   | 1.0  | IODL | BY   | 1.0  | 1.0  |      | 1.0  |      | 1.0  |
| 1.0* |      | 1.0  | SA   |      |      |      |      |      |      |
| *    |      |      |      |      |      |      |      |      |      |
+------+------+------+------+------+------+------+------+------+------+
| **OD | OdBL | \*   |      | OdBL | OdBL | OdBL | OdBL |      | OdBL |
| bL** |      | [D]  |      |      |      |      |      |      |      |
+------+------+------+------+------+------+------+------+------+------+
| **CD |      |      | CC   | IODL |      |      |      | CDLA |      |
| LA   |      |      | BY   | 1.0  |      |      |      | 1    |      |
| 1.0  |      |      | SA   |      |      |      |      | shar |      |
| perm |      |      |      |      |      |      |      |      |      |
| **   |      |      |      |      |      |      |      |      |      |
+------+------+------+------+------+------+------+------+------+------+
| **CD | CDLA | \*   |      | [E]  | CDLA |      | CDLA | CDLA | CDLA |
| LA   | 1    | CDLA |      |      | 1sha |      | 1sha | 1sha | 1sha |
| 1.0  | shar | 1sha |      |      | r    |      | r    | r    | r    |
| shar |      | r    |      |      |      |      |      |      |      |
| ing* |      |      |      |      |      |      |      |      |      |
| *    |      |      |      |      |      |      |      |      |      |
+------+------+------+------+------+------+------+------+------+------+
| **CD |      |      | CC   | IODL |      | OdBL |      | CDLA |      |
| LA   |      |      | BY   | 1.0  |      |      |      | 1    |      |
| 2.0  |      |      | SA   |      |      |      |      | shar |      |
| perm |      |      |      |      |      |      |      |      |      |
| **   |      |      |      |      |      |      |      |      |      |
+------+------+------+------+------+------+------+------+------+------+

**Tabella** **2** - Matrice di compatibilità tra licenze

**Legenda:**

+-----------------------------------+-----------------------------------+
|                                   | pubblicabile, ma con licenza      |
|                                   | diversa da CC BY / CC0 / CDLA     |
|                                   | permissive                        |
+===================================+===================================+
|                                   | non ripubblicabile                |
+-----------------------------------+-----------------------------------+
|                                   | pubblicabile con licenza CC BY    |
|                                   | 4.0, CC0 o CDLA permissive        |
+-----------------------------------+-----------------------------------+
| \*                                | verificare gestibilità            |
|                                   | attribution e DRM                 |
+-----------------------------------+-----------------------------------+
|                                   | compatibilità espressamente messa |
|                                   | in discussione [2]_               |
+-----------------------------------+-----------------------------------+
|                                   | compatibilità richiamata da una   |
|                                   | delle licenze (es. IODL 1.0       |
|                                   | rispetto a CC BY SA)              |
+-----------------------------------+-----------------------------------+

.. table:: Compatibilità tra licenze - Condizioni da osservare / specifiche di applicazione
   :name: compatibilità-licenze

+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| Cod.  | Condi | Licen |       |       |       |       |       |       |
|       | zioni | ze    |       |       |       |       |       |       |
|       | da    | impat |       |       |       |       |       |       |
|       | osser | tate  |       |       |       |       |       |       |
|       | vare  |       |       |       |       |       |       |       |
|       | /     |       |       |       |       |       |       |       |
|       | speci |       |       |       |       |       |       |       |
|       | fiche |       |       |       |       |       |       |       |
|       | di    |       |       |       |       |       |       |       |
|       | appli |       |       |       |       |       |       |       |
|       | cazio |       |       |       |       |       |       |       |
|       | ne    |       |       |       |       |       |       |       |
+=======+=======+=======+=======+=======+=======+=======+=======+=======+
| A     | segna | CDLA  | CDLA  |       | CC-BY |       |       |       |
|       | lazio | 1     | 1     |       |       |       |       |       |
|       | ne    | perm  | SHAR  |       |       |       |       |       |
|       | modif |       |       |       |       |       |       |       |
|       | ica   |       |       |       |       |       |       |       |
|       | cambi |       |       |       |       |       |       |       |
|       | ament |       |       |       |       |       |       |       |
|       | i     |       |       |       |       |       |       |       |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| B     | testo | CDLA  | CDLA  | CDLA  | CC-BY | [IODL | IODL  | OdBL  |
|       | licen | 1     | 1     | 2     |       | 2.0]  | 1.0   |       |
|       | za:   | perm  | SHAR  | perm  |       |       |       |       |
|       | con   |       |       |       |       |       |       |       |
|       | rifer |       |       |       |       |       |       |       |
|       | iment |       |       |       |       |       |       |       |
|       | o     |       |       |       |       |       |       |       |
|       | al    |       |       |       |       |       |       |       |
|       | datas |       |       |       |       |       |       |       |
|       | et    |       |       |       |       |       |       |       |
|       | origi |       |       |       |       |       |       |       |
|       | nale, |       |       |       |       |       |       |       |
|       | ripor |       |       |       |       |       |       |       |
|       | tare  |       |       |       |       |       |       |       |
|       | il    |       |       |       |       |       |       |       |
|       | testo |       |       |       |       |       |       |       |
|       | della |       |       |       |       |       |       |       |
|       | licen |       |       |       |       |       |       |       |
|       | za    |       |       |       |       |       |       |       |
|       | e/o   |       |       |       |       |       |       |       |
|       | inser |       |       |       |       |       |       |       |
|       | ire   |       |       |       |       |       |       |       |
|       | link  |       |       |       |       |       |       |       |
|       | (tra  |       |       |       |       |       |       |       |
|       | [ ]   |       |       |       |       |       |       |       |
|       | per   |       |       |       |       |       |       |       |
|       | la    |       |       |       |       |       |       |       |
|       | IODL  |       |       |       |       |       |       |       |
|       | in    |       |       |       |       |       |       |       |
|       | quant |       |       |       |       |       |       |       |
|       | o     |       |       |       |       |       |       |       |
|       | preci |       |       |       |       |       |       |       |
|       | sa    |       |       |       |       |       |       |       |
|       | “se   |       |       |       |       |       |       |       |
|       | possi |       |       |       |       |       |       |       |
|       | bile” |       |       |       |       |       |       |       |
|       | )     |       |       |       |       |       |       |       |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| C     | attri | CDLA  | CDLA  |       | CC-BY | IODL  | IODL  | OdBL  |
|       | butio | 1     | 1     |       |       | 2.0   | 1.0   |       |
|       | n:    | perm  | SHAR  |       |       |       |       |       |
|       | rispe |       |       |       |       |       |       |       |
|       | tto   |       |       |       |       |       |       |       |
|       | speci |       |       |       |       |       |       |       |
|       | fiche |       |       |       |       |       |       |       |
|       | condi |       |       |       |       |       |       |       |
|       | zioni |       |       |       |       |       |       |       |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| D     | outpu |       |       |       |       |       |       | OdBL  |
|       | t     |       |       |       |       |       |       |       |
|       | ulter |       |       |       |       |       |       |       |
|       | iore  |       |       |       |       |       |       |       |
|       | reali |       |       |       |       |       |       |       |
|       | zzato |       |       |       |       |       |       |       |
|       | [“Pro |       |       |       |       |       |       |       |
|       | duced |       |       |       |       |       |       |       |
|       | work” |       |       |       |       |       |       |       |
|       | - es. |       |       |       |       |       |       |       |
|       | Mappa |       |       |       |       |       |       |       |
|       | da db |       |       |       |       |       |       |       |
|       | geogr |       |       |       |       |       |       |       |
|       | afico |       |       |       |       |       |       |       |
|       | ];    |       |       |       |       |       |       |       |
|       | richi |       |       |       |       |       |       |       |
|       | ede   |       |       |       |       |       |       |       |
|       | sola  |       |       |       |       |       |       |       |
|       | attri |       |       |       |       |       |       |       |
|       | butio |       |       |       |       |       |       |       |
|       | n     |       |       |       |       |       |       |       |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| E     | risul | CDLA  | CDLA  | CDLA  |       |       |       |       |
|       | tato  | 1     | 1     | 2     |       |       |       |       |
|       | da    | perm  | SHAR  | perm  |       |       |       |       |
|       | “comp |       | /     |       |       |       |       |       |
|       | utati |       | perm  |       |       |       |       |       |
|       | onal  |       | 1 e 2 |       |       |       |       |       |
|       | use”  |       |       |       |       |       |       |       |
|       | senza |       |       |       |       |       |       |       |
|       | condi |       |       |       |       |       |       |       |
|       | zioni |       |       |       |       |       |       |       |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| F     | preve |       |       |       |       |       |       | OdBL  |
|       | de    |       |       |       |       |       |       |       |
|       | la    |       |       |       |       |       |       |       |
|       | nozio |       |       |       |       |       |       |       |
|       | ne    |       |       |       |       |       |       |       |
|       | di    |       |       |       |       |       |       |       |
|       | “coll |       |       |       |       |       |       |       |
|       | ectiv |       |       |       |       |       |       |       |
|       | e     |       |       |       |       |       |       |       |
|       | datab |       |       |       |       |       |       |       |
|       | ase”  |       |       |       |       |       |       |       |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| G     | limit |       |       |       | CC-BY |       |       | OdBL  |
|       | i     |       |       |       |       |       |       |       |
|       | DRM   |       |       |       |       |       |       |       |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+

**Tabella** **3** - Condizioni da osservare / specifiche di applicazione


.. [1]
    v. https://blog.openstreetmap.org/2017/03/17/use-of-cc-by-data/

.. [2]
    v. https://blog.openstreetmap.org/2017/03/17/use-of-cc-by-data/
