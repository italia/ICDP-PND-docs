A. Indicazioni generali
=======================

Il progetto di digitalizzazione richiede obbligatoriamente la
descrizione e la metadatazione del bene e degli oggetti digitali.

I metadati sono classificati a seconda delle loro caratteristiche e
finalità:

-  descrittivi: per l’identificazione e la rintracciabilità dell’oggetto
   digitale;

-  amministrativi e gestionali: per le operazioni di gestione degli
   oggetti digitali; questi si suddividono principalmente in:

-  metadati tecnici: relativi alle caratteristiche intrinseche dei file
   che compongono gli oggetti digitali e/o la loro produzione;

-  metadati sulla proprietà intellettuale: informazioni relative a
   copyright e licenze d'uso;

-  strutturali: per descrivere la struttura interna dei documenti (ad
   esempio, per un libro: introduzione, capitoli, indice) e gestire le
   relazioni fra le varie parti componenti gli oggetti digitali;

-  di conservazione.

Fatta salva la possibilità di produrre metadati secondo standard
necessari per la gestione delle risorse all’interno dei propri sistemi,
nelle presenti linee guida si dà conto del METS (Metadata Encoding and
Transmission Standard) [1]_, standard di metadatazione che occorre
utilizzare a livello nazionale per la descrizione e la gestione degli
oggetti digitali nei progetti di digitalizzazione e che deve fungere
anche da linguaggio di interscambio tra i sistemi afferenti e l’Istituto
centrale per la digitalizzazione del patrimonio culturale – Digital
Library.

Il METS serve per codificare metadati descrittivi, amministrativi e
strutturali riguardanti le risorse digitali.

Un documento METS è costituito da sette sezioni principali:

1. <metsHdr> Intestazione METS: contiene i metadati che descrivono il
   documento METS stesso, includendo alcune informazioni quali autore,
   editore etc.;

2. <dmdSec> Metadati descrittivi: contiene al suo interno i metadati
   descrittivi, o punta a metadati esterni specifici per ciascun
   dominio;

3. <amdSec> Metadati amministrativi: contiene sia informazioni sui file
   creati, che conservano anche i diritti di proprietà intellettuale,
   sia metadati riguardanti l'oggetto di origine da cui deriva l'oggetto
   digitale, sia informazioni sulla provenienza dei file e sulle
   relazioni degli oggetti digitali;

4. <fileSec> Sezione file: è una lista di tutti i file contenente le
   versioni elettroniche dell'oggetto digitale;

5. <structMap> Mappa strutturale: descrive la struttura gerarchica,
   fisica o logica, dell'oggetto digitale e collega i file e i metadati
   loro associati;

6. <structLInk> Link strutturali: permette di gestire collegamenti
   ipertestuali tra nodi nella gerarchia definita nella Mappa
   strutturale;

7. <behaviour> Comportamento: può essere usato per associare
   comportamenti (per esempio, la visualizzazione) con il contenuto
   dell'oggetto METS.

.. [1]
   https://www.loc.gov/standards/mets/.
