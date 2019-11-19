# L'IDEA

  Muovendo i primi passi nel contesto della formazione, in ambito informatico, nelle scuole pubbliche e nelle pubbliche amministrazioni in genere, abbiamo affrontato temi che dal contesto informatico si dipanavano in questioni di vario genere e soprattutto carichi di una forte ricaduta sociale, quindi umanistica e paradossalmente filosofica. 

  Fra tutte, ad appassionarci, è la questione legata al potenziale smisurato che i sistemi di elaborazione dati hanno se interfacciati alla sensoristica sempre più a basso costo e sempre più fedele agli standard internazionali, semplificando, ci siamo posti l’interrogativo su quale, attualmente, sia il valore che si determina, e sempre più si svilupperà, dall’incontro tra l’analogico ed il digitale impiegando connessioni, algoritmi/librerie open-source e protocolli standard, la risposta è indefinito. 
  Ci siamo interrogati spesso su quali potessero essere le conseguenze legate alla produzione di una tale massa critica di informazioni e quali gli effetti sulla società che ha iniziato a subire tale penetrante e invasiva diffusione di raccoglitori di storitelling e dati, ad esempio tramite i “social” o l’impiego di profili gratuiti di clouding o la diffusione dell' IoT’s, in termini di soggezione e pertanto se da tale dipendenza esistano possibilità di riscatto “fisiologiche”. 

  É opportuno sommare inoltre il peso dei processi di apprendimento automatico che avviene utilizzando le "macchine che apprendono". Spesso sfugge la portata e la rilevanza che ha una raccolta di dati planetaria delle dinamiche collettive unita a processi di auto-encoding. 

  Attraversando questi "spazi" siamo giunti alla convinzione che occorre sin da subito sostenere coloro i quali si battono per un bilanciamento delle forze in campo, ossia tra le realtà proprietarie dei suddetti sistemi, da una parte, e gli utilizzatori finali intesi non solo come semplici consumatori, al fine di limitare il predominio inconsapevole ed indiscusso di un numero limitato di gestori.

  Abbiamo pertanto preso la posizione di sostenere i movimenti internazionali che si avvantaggiano a vantaggio delle soluzioni realizzate con metodologie open-source all’interno di comunità di sviluppo che utilizzano logiche di cooperazione responsabile e versionate degli apporti ai progetti, pubblicati, utilizzando algoritmi del calibro di “Git” messi a disposizione nei cosiddetti Github, serbatoi di sistemi di sviluppo dal valore economico considerevole.  
	
  Frequentando da diversi anni una quantità apprezzabile di “contenitori” di progetti open-source pubblicati ci siamo imbattuti in un “git” taggato ‘computer vision’, ossia l’abilità di valutare gli spazi e gli oggetti contenuti in essi partendo dall’analisi delle immagini e/o dei flussi video utilizzando la libreria [__OpenCV__] (https://opencv.org/).  
  
  Nell’approfondire l’uso della suddetta tecnologia di computer-vision si sono evidenziate anche questioni fondamentali di privacy e riservatezza e dall’approfondimento di esse è sorta la prima proposta a realizzarsi con il presente progetto, che prende il nome di “analisi non in chiaro dei comportamenti disfunzionali e/o aberranti nei luoghi pubblici” causa di una gran parte del malessere quotidiano.
  
  L'impiego di una libreria del genere incrementa in maniera esponenziale la capacità di analisi della realtà che ci circonda. L'uso congiunto della computer-vision e dell'intelligenza artificale spalanca le porte ad una nuova forma di catalogazione che può svolgersi in maniera non supervisionata per apprendere la rappresentazione della realtà per una serie indefinita di dati, basandosi su patterns predefiniti, grazie all'imoego di **CNN** (Convolution Neuronal Network) sviluppatasi in vari modelli, tra cui: 
  
- [x] Logistic Regression; 
- [x] Support Vector Machine; 
- [x] Multilayered Neural Network; 
- [x] Decision Tree; 
- [x] KNN (K-Nearest Neighbors); 
- [x] Random Forest Classifier; 
- [x] Gradient Boosted Regression trees; 
- [x] XGBoost; 

con l'impiego delle **Machine Learning (ML)** è possibile imparare a riconoscere gli oggetti nello spazio e conseguentemente attribuire ad essi processi di qualsivoglia natura e stimarne i movimenti ed i comportamenti. Il tutto con risorse a basso costo e potenzialità di tutto riguardo. 

Sempre nell'ambito dell'apprendimento automatico segnaliamo librerie open-source capaci di generare i suddetti modelli senza essere in possesso di particolari conoscenze matematiche e sono [KERAS e TENSORFLOW]

Si deve a questo punto segnalare che dedicarsi alla sperimntazione nei LIT (LABORATORI per le INNOVAZIONI TECNOLOGICHE) ai livelli sopra sommariamenti indicati fa presuppore notevoli costi in termini di risorse professionali, soprattutto in merito alla predisposizione dell'ambiente di sviluppo per poter attivare i servizi ed operare con le librerie necessarie; praticamente ci si riferisce all'aspetto sistemistico. Nel segno della riduzione dei costi legati alla sperimentazione facciamo notare un altro progetto di ingegneria software i [Docker-s] (https://www.docker.com/): contenitori che sfruttano i cgroups ed i namespace, che consentono di lavorare con microsistemi responsabili, autonomi e completi che si stratifcano, per i non addetti ai lavori si pensi semplicemente ad un modo di raggruppare delle istruzioni che valgono solo per un determinato spazio e per un determinato tempoImmagini multistrato tenute insieme da logiche di raggruppamento, già note al kernel LINUX, che facilitano di molto la gestione sistemistica.

Le ricerche continue hanno evidenziato anche una ulteriore opportunità, che sommarsi alle altre sopra sccennate, ossia la diffusione di microcontrollori con elevata capacità computazionale, ridotte dimensioni e corredate di una complea camma di connessioni:

- [x] Arduino
- [x] Raspberry
- [x] Orange
- [x] Elegoo
- [x] Esp8266

Inoltre esistono kit contenenti una quantità considerevole di sensori a basso costo e con caratteristiche apprezzabili, come il rilevatore di particolato PM10 e PM2.5 utilizzato nel progetto in calce alla presente, sommaria, espisione della nostrab idea.

Affinchè, inoltre, il nostro progetto potesse avere qualche ragionevole chance di fattibilità, occorreva che fossero mature forme di divulgazione di agevole comprensione per i cittadini di un comune, ed anche qui i tempi sono maturi per poter usufruire di progetti open-source legati, ad esempio, alla mappatura (geolocalizzazione) dei dati, raccolti in dataset, del livello di **QGIS**, ma anche di **OSMnx**, di librerie per evolvere la rappresentazione come **Leaflet** e **3djs**.

Valutata la "potenza di fuoco" legata alla produzione ed alla collocazione dei dati in contesti familiari ai più, come Whatsapp e Telegram, GIS e mappe ad hoc, ha giocato un ruolo decisivo (affinchè si decidesse di perseverare nella realizzazione di questo progetto) l'approfondimento di un "collettore" di dati/dataset, in vari formati (anche geografici), denominato CKAN, capace di contenere soggetti/organizzazioni responsabili delle raccolte di dati, suddivise per categorie consultabili per tags ma anche grazie al ricorso a specifiche API. Implementando, inoltre, il plugin D-CAT è possibile che altre organizzazioni possono collegarsi dall'esterno ed estrarre i dati, così come fa il sito governativo italiano https://data.gov.it. 

>Tutto ciò premesso nasce il progetto ** SALUS-UTIS **

dall'enciclopedia (Treccani), la definizione di salute [lat. salus -ūtis "salvezza, incolumità, integrità, salute", affine a salvus "salvo"] (lett.) [l'essere salvo, inteso per lo più come stato di benessere individuale o collettivo: s. pubblica, patria; la s. dell'anima; la s. eterna] ≈ bene.

>Il progetto ha la finalità di divulgare strumenti **open-source** e diffondere **open-data** al servizio dell'**INTELLIGENZA COLLETTIVA**.

Le motivazioni sono tutte legate all'idea fondamentale che l'intelligenza collettiva vada stimolata e accresciuta secondo le regole della __trasparenza__, della __collaborazione__ e della __partecipazione__.

Diamo per scontato che siano conosciuti i processi storici e culturali, scientifici e filosofocici che hanno portato l'Amministrazione Obama, a produrre il [whitepaper] (https://obamawhitehouse.archives.gov/open/about/policy). Diamo per acquisito che si conosca **Aaron Swartz**, il martire del FOA.

Fra i vari ispiratori, da un punto di vista ideologico, richiamiamo la conoscenza di **Edgar Morin** e la sua teoria della complessità grazie alla quale sono maturate in noi alcune consapevolezze, che sono alla base di questo Think-Tank: c’è innanzi tutto quella della __COMPLESSITÁ__:
siamo in un’epoca che ha bisogno di un cambiamento di paradigma e ciò arriva abbastanza di rado nella storia.
Si tratta di sostituire la distinzione alla separazione, la dipendenza alla riduzione, occorre distinguere e allo stesso tempo collegare. È il paradigma, appunto, della complessità.
La parola complesso vuole dire collegato, tessuto insieme e, dunque, il pensiero complesso è un pensiero che collega, da un lato inserendo nel contesto, cioè collegando al contesto, d’altra parte provando a comprendere ciò che è che un sistema (Edgar Morin).

Il nostro progetto “è a sud di necessario e a nord di complesso”, qualcuno dovrà pure accettare questa sfida che passa anche attraverso le grandi conquiste mondiali del “Governo aperto“ basato sulla trasparenza, la partecipazione e la collaborazione, è così che si fa nei momenti difcili della storia, come quello che stiamo vivendo. 

Qualcuno si dovrà pur chiedere a che punto è l’intelligenza civica, l'intelligenza collettiva, domandarsi se siamo, appunto, abbastanza intelligenti (‘soon enough‘) per una società aperta. In America l’amministrazione Obama invocava “a **Peace Corps For Developers**“, un corpo di intellettuali onesti (la nostra traduzione) per mettere pace tra l’esigenza speculative dei professionisti e quella ai servizi dei cittadini.

>**UNO SGUARDO AL TERRITORIO**

Quali sono le specifcità del nostro progetto? Da quali premesse partiamo e quali sono i nostri obiettivi? Sicuramente studiare il nostro territorio quale ambiente **del nostro benessere, della nostra autodeterminazione, della qualità della nostra vita, verso il profilo della salute ed il registro dei tumori** . Tutto ha avuto inizio con la conoscenza di un architetto, dal nostro impegno civico e dalle nostre sensibilità, attratte e legate dalla curiosità per il ciò che ci circonda. L'architetto è **Giuseppe dell'Aquila**, figura dinamica, determinata e preparata che ci ha sottoposto un documento intitolato “Un approccio corale e condiviso al territorio”, già nei termini l'aggettivo corale, più che condiviso, ha attivato il cosiddetto ‘trigger’, in informatica, l’evento, l’automatismo delle competenze informatiche di alcuni di noi, la vicinanza della materia di cui si sta parlando all’informatica è incredibile.

Dalla lettura breve, ma intensa, del suddetto documento emergevano riferimenti a teorie e criteri rivoluzionari, ma di una rivoluzione ‘vecchia’, che parte dagli anni ‘70 ma che è rimasta incompiuta perché disattesa; si parla di una logica open-source, di una progettazione peer-to-peer e dell’impiego dei patterns introdotti dal matematico **Christofer Alexander**, ma anche della necessità di rendere le dinamiche progettuali figurative, evidenti, visive come una mappa concettuale costituita da risorse reali, autonome ma interconnesse come sollecitato da **Kevin Lynch**, importanza dei GIS.

I tempi sono maturi per dismettere l’architettura di rete di tipo Client/Server, detto in parole semplici, dove tutto è centralizzato, dalla logica delle infrastrutture a quella dei servizi, tutto passa attraverso un “centro specializzato” che soddisfa le richieste dei fabbisogni dei “client”. Il nuovo modello si basa su un sistema detto peer-to-peer, dove ogni client/risorsa è alla pari ed autonoma e decide di mettersi in “comunione”, sempre alla pari con chi vuole, direttamente, con un altro peer, un suo pari, di rendersi accessibile, liberamente, per andare a formare un pattern aperto di condivisione.

Anche il termine pattern non è proprio potabile al 100%, ha bisogno di essere depurato da tanti significati assunti in diversi contesti, il pattern è un modello strutturato (vuol dire che c’è della matematica sotto), una regolarità percepibile nel mondo reale o in un design artifciale. In quanto tale, gli elementi di un modello si ripetono in modo più o meno prevedibile, per esempio una simmetria, una spirale, apparenti casualità, onde, dune, bolle, fratture, macchie, strisce, e tanto altro ancora.

L'accrescimento dell'itelligenza collettiva può giovarsi enormemente della tecnologia, anzi dovrebbe, dato anche l'effetto dell'onda lunga che tra non molto produrrà l'intelligenza artificiale applicata alla nostra "mediocrità".

Entrando nello specifco di quella che sarà l’attività che si andrebbe a svolgere indentifchiamo:

a) L’apporto culturale sotto qualsiasi forma: letteratura, arte grafca o fotogra fca, arte in genere, musica;
b) la promozione e la guida nell’allestimento degli URBAN-CENTER;
c) la predisposizione di momenti di progettazione partecipata con stackholder
individuati dopo un attento percorso valutativo;
d) monitoraggio e catalogazione dei sistemi informatici (OPEN-SOURCE) legati:

	1) alla lettura intelligente del territorio;
	2) allo scambio di dati in automatico fra risorse (IoT) all’interno dei patterns, verso servizi, quali ad esempio quelli di AI;
	3) banche-dati di varia natura, geospaziali, no-Sql, SQL;
	4) alla gestione di interoperabiltà (C2G) sul web tra cittadini e istituzioni e) relazioni di codifca propedeutiche agli studi di fattibilità richiesti dalla Pubblica Amministrazione e **advocacy**

e) monitoraggio, misurazione e catalogazione dei sensori in commercio da impiegare nella conversione da anologico a digitale, fondamentale per sfruttare al meglio le opportunità del DIY (Do It Yourself), soprattutto nel campo del monitoraggio della qualità dell’ambiente.

Il progetto si prefigge di:
- [x] pubblicare datasets sulla piattafoprma [CKAN](https://ckan.org/) e [plugin D-CAT](https://www.dati.gov.it/content/ckan-datigovit) per consentire la possibilità di interagire con il DATA.GOV.IT;
- [x] renderere disponibili in automatico i dati raccolti legati alla qualità della vita dei nostri paesi;
- [x] impiego della tecnologia per divulgare i dataset.

I fenomeni della realtà incidono sulla qualità della vita, essi possono essere monitorati grazie all'impiego di una serie di sistemi, non ultimo la **COMPUTER VISION** legata all'**AI**. 

I DATI prodotti dovranno essere resi "potabili" ai più, ai non addetti ai lavori (alla cittadinanza).     

Impiegheremo prevalentemente siluzioni DIY ma per rendere il tutto più sistemico potremmo pubblicare un elenco dei prodotti commerciai a ciò funzionali e maggiormente rispondenti ai suddetti principi.


- [LOGICHE SISTEMISTICHE](docs/sistemistica.md)
- [LOGICHE DI PROGRAMMAZIONE](docs/programmazione.md)                         
                             
                           
Forkiamo un progetto per iniziare:

>mappa ==>  https://maps.luftdaten.info/#2/0.0/0.0
>progetto ==> https://luftdaten.info/it/benvenuto/

partiremo di qui, dovendo partire, da un sistema di geolocalizzazione vincitore challenge NASA; lo riteniamo rispondente a tutto ciò che fino ad ora abbiamo potuto ricercare e verificare; il progetto utilizza la pratica migliore di sviluppo sia per la scelta dei frameworks di sviluppo sia per le logiche di costruzione. 
 
