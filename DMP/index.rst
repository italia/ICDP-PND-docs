**PIANO NAZIONALE DI DIGITALIZZAZIONE**

**DEL PATRIMONIO CULTURALE**

**Linee guida per la redazione del piano di gestione dei dati (Data
Management Plan)**

|image0|

Versione 09 – maggio 2022

**Questo documento è una bozza di lavoro, quindi strettamente riservato
e confidenziale, non destinato alla circolazione all’esterno del
Ministero.**

Crediti

Il documento è stato redatto dall’Istituto centrale per la
digitalizzazione del patrimonio culturale – *Digital Library*, con il
contributo di Tiziana Mancinelli, Daniele Metilli, Chiara Veninata.

Sommario

`Introduzione 5 <#introduzione>`__

`1. Cos’è il DMP e a che cosa serve
5 <#cosè-il-dmp-e-a-che-cosa-serve>`__

`2. Il DMP nel Piano Nazionale di Digitalizzazione
7 <#il-dmp-nel-piano-nazionale-di-digitalizzazione>`__

`3. Data governance interna 8 <#data-governance-interna>`__

`4. Attività preliminari 10 <#attività-preliminari>`__

`5. Struttura del Data Management Plan 11 <#_Toc102602630>`__

`6. Scheda istituto 12 <#scheda-istituto>`__

`7. Scheda progetto 12 <#scheda-progetto>`__

`7.1. Informazioni amministrative 13 <#informazioni-amministrative>`__

`7.1.1. Identificazione del progetto
13 <#identificazione-del-progetto>`__

`7.1.2. Ruoli e responsabilità ⓘ 13 <#ruoli-e-responsabilità>`__

`7.2. Dati 14 <#dati>`__

`7.2.1. Produzione e raccolta dei dati ⓘ
15 <#produzione-e-raccolta-dei-dati>`__

`7.2.2. Tipologie e formati di dati ⓘ
15 <#tipologie-e-formati-di-dati>`__

`7.2.3. Origine dei dati ⓘ 15 <#origine-dei-dati>`__

`7.2.4. Tipologia di beni ⓘ 16 <#tipologia-di-beni>`__

`7.2.5. Migrazione di dati esistenti ⓘ
16 <#migrazione-di-dati-esistenti>`__

`7.2.6. Quantità di dati prevista ⓘ 16 <#quantità-di-dati-prevista>`__

`7.3. Metadati 16 <#metadati>`__

`7.3.1. Livello di metadatazione ⓘ 17 <#livello-di-metadatazione>`__

`7.3.2. Metodologie per la metadatazione ⓘ
17 <#metodologie-per-la-metadatazione>`__

`7.3.3. Standard di metadatazione ⓘ ⓒ 17 <#standard-di-metadatazione>`__

`7.4. Qualità dei dati e documentazione
18 <#qualità-dei-dati-e-documentazione>`__

`7.4.1. Analisi della qualità dei dati ⓘ ⓓ
18 <#analisi-della-qualità-dei-dati>`__

`7.4.2. Bonifica dei dati ⓘ 19 <#bonifica-dei-dati>`__

`7.4.3. Nomenclatura degli oggetti digitali ⓘ ⓒ
19 <#nomenclatura-degli-oggetti-digitali>`__

`7.5. Open data 20 <#open-data>`__

`7.5.1. Livello open data ⓘ 21 <#livello-open-data>`__

`7.5.2. Identificatori ⓘ ⓓ 21 <#identificatori>`__

`7.5.3. Standard per gli open data ⓘ ⓒ
21 <#standard-per-gli-open-data>`__

`7.5.4. Ontologie e vocabolari di riferimento ⓘ ⓒ
21 <#ontologie-e-vocabolari-di-riferimento>`__

`7.5.5. Licenze open data ⓘ ⓓ 22 <#licenze-open-data>`__

`7.5.6. Integrazione con altri dataset ⓘ
22 <#integrazione-con-altri-dataset>`__

`7.6. Aspetti etici e legali 22 <#aspetti-etici-e-legali>`__

`7.6.1. Dati personali e consenso informato ⓘ
23 <#dati-personali-e-consenso-informato>`__

`7.6.2. Diritto d’autore ⓘ 23 <#diritto-dautore>`__

`7.6.3. Possibili fonti di bias ⓘ 24 <#possibili-fonti-di-bias>`__

`7.7. Archiviazione, pubblicazione e preservazione dei dati
25 <#archiviazione-pubblicazione-e-preservazione-dei-dati>`__

`7.7.1. Archiviazione dei dati ⓘ 25 <#archiviazione-dei-dati>`__

`7.7.2 Pubblicazione dei datiⓘ ⓓ 26 <#_Toc102602664>`__

`7.7.3. Preservazione dei dati ⓘ 28 <#preservazione-dei-dati>`__

`7.7.4. Procedure di backup ⓘ ⓓ 28 <#procedure-di-backup>`__

`7.8. Sicurezza dei dati 29 <#sicurezza-dei-dati>`__

`7.8.1. Disposizioni per la sicurezza dei dati ⓘ
30 <#disposizioni-per-la-sicurezza-dei-dati>`__

`7.8.2. Standard per la sicurezza dei dati ⓘ
30 <#standard-per-la-sicurezza-dei-dati>`__

`7.8.3. Rischi per la sicurezza dei dati ⓘ
31 <#rischi-per-la-sicurezza-dei-dati>`__

`7.8.4. Sicurezza dei dati sensibili ⓘ
31 <#sicurezza-dei-dati-sensibili>`__

`8. Strumenti per la compilazione del DMP ⓘ
32 <#strumenti-per-la-compilazione-del-dmp>`__

`Normativa di riferimento 32 <#normativa-di-riferimento>`__

`FAQ per la pubblicazione dei dati aperti
35 <#faq-per-la-pubblicazione-dei-dati-aperti>`__

.. toctree::
  :maxdepth: 3
  :caption: Indice dei contenuti

  introduzione.rst
  cosè-il-dmp-e-a-che-cosa-serve.rst
  il-dmp-nel-piano-nazionale-di-digitalizzazione.rst
  data-governance-interna.rst
  attività-preliminari.rst
  struttura-del-data-management-plan.rst
  scheda-istituto.rst
  scheda-progetto.rst
  informazioni-amministrative.rst
  dati.rst
  metadati.rst
  qualità-dei-dati-e-documentazione.rst
  open-data.rst
  aspetti-etici-e-legali.rst
  archiviazione-pubblicazione-e-preservazione-dei-dati.rst
  sicurezza-dei-dati.rst
  strumenti-per-la-compilazione-del-dmp.rst
  normativa-di-riferimento.rst
  faq-per-la-pubblicazione-dei-dati-aperti.rst

.. |image0| image:: ./media/image1.jpeg
   :width: 5in
   :height: 3.73958in
