# Dal Pensiero Computazionale all'Informatica, passando per il coding / programmazione

Ho presentato queste diapositive durante l'evento [Science4All 2023](https://www.unipd.it/news/second-edition-science4all-starts-late-september) dell'Università di Padova. Seguono alcune note per spiegarne il contenuto (prevalentemente pittorico).

Per domande e osservazioni potete scrivere a 

### Slide 4
_“Il Pensiero Computazionale è la capacità di esprimere soluzioni a problemi in modo tale che queste siano eseguibili da un agente meccanico.”_ è una traduzione (parafrasata) della famosa definizione data da Jeanette M. Wing [qui](https://www.cs.cmu.edu/~CompThink/papers/TheLinkWing.pdf).
Le prima parola chiave è **eseguibili**, nel senso di non ambigue, che non richiedono ulteriore intervento da parte del programmatore o interpretazione da parte dell'esecutore. La seconda parola chiave è **agente meccanico**, il quale può banalmente essere un computer o dispositivo dotato di processore, ma può anche essere un essere umano che agisca, appunto, in modo meccanico, eseguendo le istruzioni alla lettera.

### Slide 5
In questa diapositiva osserviamo un esempio di attività di pensiero computazionale che coinvolge robot programmabili (in questo caso Cubetto) nella figura di sinistra.
Nella figura di destra invece abbiamo una attività di "robotica umana" in cui tre bambin* assumono ruoli diversi:
* Programmatore: scrive il codice e poi lo detta all'esecutore
* Esecutore: segue alla lettera le istruzioni dettate dal programmatore
* Controllore: verifica  che l'esecutore segue effettivamente le istruzioni, traccia il percorso compiuto sul tabellone.

Il vantaggio di un robot/computer è che questi eseguiranno il nostro programma alla lettera, con errori e tutto, in modo imparziale (mentre un essere umano potrebbe essere tentato di "metterci del suo"). Tuttavia interpretare il ruolo di "esecutore" può aiutare a "mettersi nei panni" di un processore e cominciare a capire veramente come le istruzioni di un programma vengono effettivamente eseguite.

### Slide 6
Il Pensiero Computazionale può essere visto come una sorta di linguaggio, come un insieme di concetti che ci possono aiutare a guardare la realtà in modo più consapevole.
Collego questa idea alla citazione tratta da "Lettera a una professoressa": la maestra chiede al bambino contadino (sistematicamente lasciato indietro, bocciato, ignorato ed escluso socialmente dalla scuola dell'epoca) di arrampicarsi su un *albero* per raccogliere delle ciliege. Il bambino, che conosce il nome di tutti gli alberi, si stupisce di questa cosa (capisce che forse non è così ignorante come gli viene costantemente ricordato).
Il bambino conosce i nomi delle piante e questo gli permette di “vedere” la natura in modo diverso. La maestra “istruita” vede “un bosco”, degli alberi indistinti. Il bambino vede il castagno, il carpino, il ciliegio, ecc.
Il contadino sa che in autunno può raccogliere le castagne, che può tagliare il carpino per farne legna da ardere perché ricresce velocemente, ecc.
In poche parole: imparare un nuovo “linguaggio” ci permette di interagire con la realtà in modo più consapevole.

### Slide 7
Non c'è consenso sulle abilità costituenti del Pensiero Computazionale, tuttavia queste cinque catturano la maggior parte dei concetti, senza complicare eccessivamente la figura.

### Slide 8
Una cosa interessante di queste abilità è che possono essere viste a vari livelli di generalità.
In un certo modo i concetti di decomposizione, generalizzazione, ecc. si riflettono nella natura stessa dei pochi comandi che costituiscono la base di tutti i linguaggi di programmazione (funzioni, iterazione, condizionali, ecc.). Allargando un po' lo sguardo vediamo che queste abilità fanno anche parte del lavoro quotidiano di ogni informatico (scrivere algoritmi, risolvere errori, scomporre problemi, ecc.). Infine, allargando ancora lo sguardo, vediamo che queste abilità hanno un aspetto universale che porta vantaggio a chiunque, non solo a chi ha a che fare quotidianamente con l'Informatica.

### Slide 9
Esempio di vita quotidiana: in un racconto di Piccola Lulu, lei e i suoi amici seppelliscono un tesoro e scrivono una mappa che indica esattamente quanti passi fare verso nord, est, ovest, ecc. per ritrovarlo. Tuttavia non scrivono DA DOVE PARTIRE! la mappa quindi non è automaticamente eseguibile, e infatti Lulu e i suoi amici non riescono a ritrovare il tesoro. Nota: anche il concetto di "passo" non è particolarmente preciso e sarebbe stato meno ambiguo spiegare quanto lunghi devono essere questi passi.

Esempio di programmazione: costruire un algoritmo vuol dire essere in grado di costruire sequenze di istruzioni che vengono eseguite in un ordine preciso. Semplificando, i processori possono eseguire solo una istruzione alla volta.

### Slide 10
Esempio di vita quotidiana: scrivere una storia può essere un compito complesso, tuttavia è possibile individuare gli elementi che compongono ogni storia e pensare prima a quelli in isolamento, per esempio i personaggi, i momenti principali della trama, ecc. e poi ricomporli.

Esempio di programmazione: i problemi spesso presentano sotto-problemi, in questo caso possiamo vedere che il percorso che deve percorrere l’ape può essere diviso in tre parti che richiedono esattamente la stessa soluzione. Il concetto di iterazione "cattura" le soluzioni a questi sottoproblemi in una forma compatta (che riflette la struttura del problema).

### Slide 11
Esempio di vita quotidiana: imparare *ad imparare* uno strumento musicale (come la chitarra) è una abilità che può essere generalizzata a tutti gli strumenti ma, volendo, anche ad altre attività che richiedano coordinazione tra le mani ecc. come ad esempio la giocoleria.

Esempio di programmazione: le istruzioni condizionali fanno sì che i programmi diventino in grado di risolvere non più un solo ma problema ma intere classi di problemi. Per esempio, le istruzioni condizionali rendono possibile scrivere degli algoritmi che risolvono *tutti* i labirinti.

### Slide 12
Esempio di vita quotidiana: il sistema postale funziona, semplificando, a livelli successivi di dettaglio. Io devo solo sapere come arrivare alla cassetta della posta più vicina. Il postino che recupera tutte le lettere probabilmente sa solo che deve portarle all’ufficio postale. Dall’ufficio postale partono dei camion che portano le lettere internazionali a centri di distribuzione addetti o all’aeroporto, e così via. Ogni ufficio non si preoccupa di quello che fa l’ufficio successivo nel percorso, o che strada specifica fa il postino o il camion. Ogni ufficio gestisce solo le responsabilità che gli competono. Incidentalmente questo è anche il modo in cui funziona la rete internet.

Esempio di programmazione: l’ultimo elemento della programmazione è il concetto di “funzione”, che permette di definire una serie di operazioni sotto a una "etichetta". Per capirsi: anche nella vita quotidiana usiamo qualcosa di simile, per esempio per lavarci i denti dobbiamo prendere il dentifricio, lo spazzolino, aprire l’acqua ecc. e noi non pensiamo ad ogni singolo passaggio ma solo a “lavarci i denti”. Una volta definita la funzione noi non dobbiamo più preoccuparci di “cosa ci sia dentro” alla funzione, ma solo di quello che la funzione fa, ovvero di "cosa entra" nella funzione e cosa "esce" dalla funzione. Questo ci permette di pensare a un livello di astrazione superiore.

### Slide 13
Esempio di vita quotidiana: debugging vuol dire essere in grado di ripercorrere i propri passi per capire qual’è l’origine di un errore. Per esempio se quando si fa il pane questo non lievita, ci possono essere vari motivi, magari c’era poca umidità e si è fatta subito la crosta, magari non si è messo qualche ingrediente. Magari si è mescolato sale e lievito. Riuscire a ripercorrere i propri passi in modo sistematico è una abilità che aiuta a non ripetere gli errori (e a imparare dagli errori).

Esempio di programmazione: esagerando, ma non troppo, la percentuale di programmi che non hanno bug è 0%. Il debugging è una delle abilità più esercitate dai programmatori e una delle più importanti nel pensiero computazionale. Nota bene: in contesti educativi, gli errori vanno *celebrati* come occasioni di apprendimento, è molto importante non costruire un rapporto emotivo negativo con il fatto di provare e sbagliare!

### Slide 14
Questa immagine serve a suggerire come, passando a livelli successivi di astrazione, la combinazione di questi semplici pezzi fondamentali dei linguaggi di programmazione crea strutture sempre più complesse fino a comporre tutto il software esistente.

### Slide 15
Noi crediamo che le attività di Pensiero Computazionale aiutino i discenti a passare da essere semplicemente consumatori di tecnologie digitali ("parcheggiati" davanti a youtube) a creatori, utenti consapevoli.

### Slide 16
Ricordiamo però che non è sufficiente "parcheggiare" qualcuno davanti a una attività intelligente di Pensiero Computazionale. Ci vuole dialogo e accompagnamento!

### Slide 17
I linguaggi di programmazione a blocchi hanno alcuni vantaggi che li rendono ideali per i principianti: uno dei maggiori è il fatto che sostanzialmente eliminano gli errori sintattici. Aiutano anche a ridurre il carico cognitivo in quanto colori e forme aiutano a "riconoscere" invece di "ricordare". Ogni blocco di codice è sostanzialmente una funzione con una interfaccia ben definita, è anche quindi più difficile commettere errori logici (in quanto quasi sempre i blocchi possono venire combinati solo in modi previsti).

Gli esercizi navigazionali sono abbastanza intuitivi, nel senso che non occorre molto sforzo per capire come funzionano e quali sono i loro obiettivi. Inoltre sono facilmente trasferibili a contesti più immersivi come la robotica.

### Slide 18
Per quanto possano essere intuitivi, gli esercizi di navigazione devono comunque essere *letti* e *capiti*. C'è sempre il rischio di ambiguità di presentazione e fraintendimenti. Questa slide contiene alcune domande la cui risposta dovrebbe essere ben chiara agli studenti prima di interagire con il codice.

### Slide 19
Sarebbe opportuno passare un po' di tempo a ragionare sui blocchi di codice in isolamento, assicurandosi di aver capito esattamente come funzionano. Per esempio, un blocco "gira a destra", non prevede spostamento, ma solo rotazione. Questo potrebbe non essere ovvio.

### Slide 20
Scrivere e leggere codice sembrano essere abilità diverse. In un certo senso è più facile comporre una soluzione a un problema passo per passo. Mentre lo faccio è come se stessi "tenendo il segno" mentalmente sul problema, e a ogni passo penso solo all'istruzione successiva. Tuttavia se c'è un problema nel mio codice dovrei essere in grado di ripercorrerlo *tutto* mentalmente.
Consiglierei quindi di fare degli esercizi di navigazione "al contrario", in cui si chiede dove va a finire il percorso implementato da un pezzo di codice.
Può sembrare banale farlo usando solo comandi di movimento, ma nel momento in cui si inseriscono istruzioni condizionali e iterazione questo "costringe" a tenere a mente lo *stato* dell'esecuzione e a simulare veramente il processore.

### Slide 21
Si possono pensare a giochi e analogie con la vita quotidiana per insegnare i concetti più complessi della programmazione.
Una intuizione di iterazione si può dare con attività di pixel art, in cui di fatto una immagine viene codificata con tante piccole sequenze iterative (colora tre caselle di nero, 2 di bianco, ecc.). Anche la danza può essere un buon modo per dare una intuizione di iterazione. Per esempio la macarena è una sequenza di più mosse che vengono ripetute per la durata della canzone. Interessante notare come alla fine di ogni sequenza di mosse ci sia un salto e una rotazione di 90 gradi di chi balla: anche se la sequenza di istruzioni è sempre la stessa, lo *stato* dell'esecuzione si evolve.

Per le istruzioni condizionali può essere utile provare a schematizzare alcuni processi decisionali che tutti compiamo ogni giorno. Per esempio decidere come vestirsi per uscire di casa.

### Slide 22
Per concludere: quando pensiamo ad attività educative sul Pensiero Computazionale teniamo a mente la definizione di Wing.
Ci vuole un problema: che non deve per forza essere qualcosa di negativo, ma anche un progetto. I problemi e i progetti devono partire piccoli e diventare sempre più grandi e complessi. Non consiglierei di iniziare con attività creative non strutturate, in quanto non è così facile capire quali siano i loro esiti di apprendimento.
Bisogna abituarsi a pensare in modo eseguibile: eseguibile vuol dire non ambiguo, non interpretabile. Non serve necessariamente un computer per cominciare a strutturare il proprio pensiero in questo modo.
Infine (questo non centra molto con la definizione ma tant'è): è importante che ci abituiamo a *simulare* mentalmente le nostre soluzioni eseguibili. L'unica "scusa" che abbiamo per non dover più essere in grado di "contenere" un programma nella nostra testa è compiere un passo di astrazione dandogli un nome e incapsulandolo in una funzione.