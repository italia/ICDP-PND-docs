C. Esempi di nomenclatura
=========================

Un esempio di ambito archivistico può essere il seguente:

-  Codice Istituto = **IT-MC0238**\  [1]_

-  Codice Oggetto = **00000213**

-  Numero Progressivo = **00001**

-  Estensione del file = **.jpg**

Pertanto, il nome risultante sarà: IT-MC0238+00000213+00001.jpg

Un altro esempio, con encoding del codice oggetto, può essere il
seguente:

-  Codice Istituto = **IT-MC0238**

-  Codice Oggetto = **Anagrafe_Registri_00000213** (segnatura dell’unità
   modificata per essere URI compliant in cui lo spazio è sostituito dal
   carattere “_” [underscore])

-  Numero Progressivo = **00001**

-  Estensione del file=\ **.jpg**

Pertanto, il nome risultante è:
IT-MC0238+Anagrafe_Registri_00000213+00001.jpg

Un esempio per gli oggetti digitali collegati a descrizioni
bibliografiche può essere il seguente:

-  Codice Istituto = **IT-MI0185**\  [2]_

-  Codice Oggetto = **BVEE022376**

-  Numero Progressivo = **00001**

-  Estensione del file = **.jpg**

Pertanto, il nome risultante è: IT-MI0185-BVEE022376-00001.jpg

Nel caso di un periodico, nel codice oggetto trovano spazio una serie di
informazioni che devono essere segmentate per rendere univoca ed
esplicita la nomenclatura del file. Un esempio di sequenza dei campi è
la seguente:

-  Codice Oggetto = il campo risulta dalla giustapposizione dei seguenti
   dati: codice BID della testata, dati cronologici del fascicolo,
   numero del fascicolo, eventuali Informazioni aggiuntive del
   fascicolo, separati da “_” (underscore).

Un esempio può essere il seguente:

-  Codice Istituto = **IT-MI0185**

-  Codice Oggetto = **TO00199240**, BID dell’unità nel catalogo
   nazionale; **18690503_01**, Dati cronologici fascicolo

-  Numero Progressivo = **0001**

-  Estensione del file = **.jpg**

Il nome risultante è: IT-MI0185+TO00199240_18690503_01+0001.jpg

Nel caso dei file multimediali allegati alla scheda di catalogo, un
esempio può essere il seguente:

-  Codice Istituto = **S29** (codice assegnato in SIGECweb)

-  Codice Oggetto = **DCM090010300** (codice univoco dell’entità
   multimediale nel catalogo nazionale)

-  Numero progressivo = **0000** (è un valore fisso, perché in SIGECweb
   una scheda allegato multimediale corrisponde a un solo file)

-  Estensione del file = **.tiff**

Il nome risultante è: S29+DCM090010300+0000.tif

Nel caso di file sonori, un esempio può essere il seguente:

-  Codice Istituto = **IT-RM0200** (codice ISIL dell’ICBSA)

-  Codice Oggetto= **DDS0253686** (corrisponde al BID)

-  Numero Progressivo = **0001** (per il lato A) o **0002** (per il lato
   B)

-  Estensione del file = **.wav**

Il nome risultante è: IT-RM0200+DDS0253686+0001.wav

Per una migliore organizzazione dei contenuti, la struttura gerarchica
del file system deve essere coerente con la struttura della nomenclatura
dei file. Con la medesima finalità, nel progetto di digitalizzazione si
possono rendere esplicite ulteriori regole di articolazione del
filesystem.

Di seguito si riportano due esempi:

-  Codice Istituto

   -  Codice Oggetto (dentro la cartella trovano spazio,
      indifferentemente, tutti i file digitali prodotti nelle diverse
      estensioni)

Oppure, se si vuole fare una distinzione per tipologia di file:

-  Codice Istituto

   -  Codice Oggetto

      -  Estensione File (dentro le sottocartelle trovano spazio i file
         digitali prodotti in una particolare estensione, per esempio
         cartella “tiff”, cartella “jpg” etc.)

Le regole seguite per la nomenclatura, in particolare in riferimento a
come è strutturato il Codice Oggetto, vanno rese esplicite e descritte
nella documentazione di progettazione, e inserite nei supporti di
consegna.

.. [1]
   Codice ISIL dell’Archivio di Stato di Macerata.

.. [2]
   Codice ISIL della Biblioteca nazionale Braidense.
