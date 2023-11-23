# Gestione degli aspetti di rendicontazione

La schermata di gestione degli aspetti di rendicontazione è riportata a seguire.
Occorre in particolare notare che non tutte le schede mostrate potrebbero essere disponibili, in base alla configurazione ed allo stato del sistema.

<img src="img/interfaccia_rendicontazione.png">

### Fogli orari compilati ###

Questa sezione permette la gestione dei fogli orari compilati dal personale coinvolto in attività di ricerca e registrati all'interno della piattaforma.

#### Consultazione dei fogli orari compilati ####

E' disponibile una scheda di dettaglio, dal titolo `Fogli orari compilati`, relativa ai fogli orari compilati per il periodo di riferimento corrente.

In particolare, la scheda mostra informazioni quali il numero di fogli orari compilati caricati sulla piattaforma, il numero massimo di fogli attesi, e la percentuale dei fogli caricati rispetto al totale.
Occorre considerare che una percentuale inferiore al 100% può indicare uno dei seguenti scenari:
* Una unità di personale non ha ore da rendicontare su alcun progetto per il periodo di riferimento corrente
* Una unità di personale non ha (ancora) caricato il foglio orario compilato sulla piattaforma

In quest'ultimo caso, è possibile, se la configurazione del sistema lo permette, ricordare alle unità di personale che non hanno ancora caricato il foglio orario, di caricarlo entro la scadenza (si veda la relativa sezione più avanti).

Cliccando il bottone `Visualizza documenti` è possibile consultare tutti i documenti caricati: per ogni documento è possibile scaricare lo stesso o eliminarlo.

Pertanto, per poter visualizzare i fogli orari compilati disponibili all'interno della piattaforma per il periodo di riferimento corrente, procedere come segue:
1. Accedere alla piattaforma RECCO
2. Aprire il menu `Rendicontazione`
3. Cliccare il bottone `Visualizza documenti` all'interno della scheda `Fogli orari compilati`
4. Si aprirà una pagina contenente tutti i documenti, con la possibilità di scaricarli o rimuoverli

#### Consultazione dell'archivio dei fogli orari compilati ####

Analogamente alla consultazione dei fogli orari compilati per il periodo di riferimento corrente, è disponibile una scheda di dettaglio relativa all'archivio di tutti i fogli orari compilati.
Tale scheda ha come titolo `Archivio fogli orari compilati`.

Cliccando il bottone `Visualizza documenti` è possibile selezionare il periodo di riferimento di interesse (espresso nel formato `YYYYMM`), dunque accedere ai documenti di interesse, con possibilità di scaricarli o eliminarli.

Pertanto, per poter visualizzare tutti i fogli orari compilati all'interno della piattaforma, procedere come segue:
1. Accedere alla piattaforma RECCO
2. Aprire il menu `Rendicontazione`
3. Cliccare il bottone `Visualizza documenti` all'interno della scheda `Archivio fogli orari compilati`
4. Si aprirà una pagina contenente tutti i periodi di riferimento, espressi nel formato `YYYYMM`
5. Selezionare il periodo di riferimento di interesse cliccando sul bottone `Visualizza`
6. Si aprirà una nuova pagina contenente tutti i documenti, con la possibilità di scaricarli o rimuoverli

#### Caricamento manuale dei fogli orari compilati ####

Se il sistema è configurato per permettere tale opzione, è possibile caricare manualmente i fogli orari (senza attendere la compilazione da parte delle relative unità di personale).
Per procedere in tal senso, cliccare il bottone `Carica documenti` all'interno della scheda `Caricamento fogli orari compilati`.

Verrà aperta una finestra analoga alla seguente.

<img src="img/interfaccia_rendicontazione_caricamentomanuale_lista.png">

*Schermata di visualizzazione delle unità di personale registrate per caricamento manuale dei fogli orari compilati*

In particolare, per ogni unità di personale, è possibile aprire la finestra di caricamento dei fogli orari cliccando sul relativo bottone `Visualizza`.

Tale finestra sarà analoga alla seguente.

<img src="img/interfaccia_rendicontazione_uploadfogliocompilato.png">

*Schermata di visualizzazione delle unità di personale registrate per caricamento manuale dei fogli orari compilati*

Opzionalmente, in base alle configurazioni della piattaforma, verranno mostrati i progetti che vedono l'unità di personale di riferimento come partecipante.

Una volta aperta la finetra, è possibile caricare il foglio orario compilato, selezionandolo attraverso il relativo bottone `Scegli file` (da notare che il testo del bottone potrebbe variare in base al browser utilizzato), dunque cliccando il bottone `Invia`.

Una volta premuto il tasto di invio, comparirà una notifica di successo o di errore, in base al risultato di un pre-processamento del file caricato.
Ad esempio, un errore potrebbe essere dovuto al caricamento di un file con estensione differente rispetto a quella attesa.

Inoltre, il nome del file caricato non è rilevante ai fini dell'importazione, in quanto il file caricato verrà rinominato automaticamente dalla piattaforma.

E' importante notare che, se tale opzione è configurata, a caricamento avvenuto l'unità di personale coinvolta riceverà una email di conferma.
Inoltre, indipendentemente da tale configurazione, l'attività verrà registrata all'interno dei log della piattaforma, associando l'utente che ha caricato il file con l'operazione.

Il caricamento implica inoltre la generazione automatica dei timesheet relativi, come descritto relativamente al [processo implementato](introduzione.md#il-processo-implementato).

Riassumendo, per poter caricare manualmente il foglio orario compilato di un dipendente, ammesso che tale opzione sia possibile dalla configurazione della piattaforma, è necessario procedere come segue:
1. Accedere alla piattaforma RECCO
2. Aprire il menu `Rendicontazione`
3. Cliccare il bottone `Carica documenti` all'interno della scheda `Caricamento fogli orari compilati`
4. Si aprirà una finestra con la lista del personale registrato: cliccare il bottone `Visualizza` adiacente all'unità di personale di riferimento
5. Si aprirà una finestra di caricamento del foglio orario: cliccare il bottone `Scegli file`
6. Selezionare dal proprio computer il file da caricare, in formato Microsoft Excel
7. Cliccare il bottone `Invia` per confermare l'operazione
8. Verificare la finestra di notifica

#### Consultazione dei fogli orari compilati contenenti periodi in missione ####

Se il sistema è configurato per mostrare tale opzione, è possibile consultare i soli fogli orari compilati per il periodo di riferimento corrente che includono periodi in missione.
Tale funzionalità può essere utile per verificare in modo rapido eventuali anomalie sulle ore in missione rendicontate dal personale.

Per visualizzare i fogli orari compilati per il periodo di riferimento corrente contenenti periodi in missione, procedere come segue:
1. Accedere alla piattaforma RECCO
2. Aprire il menu `Rendicontazione`
3. Cliccare il bottone `Visualizza documenti` all'interno della scheda `Fogli orari contenenti missioni`
4. Si aprirà una pagina contenente tutti i documenti, con la possibilità di scaricarli

#### Invio di remind per la compilazione dei fogli orari ####

TODO

### Timesheet ###

TODO

#### Gestione dei template dei timesheet mensili ####

TODO

#### Produzione manuale di timesheet mensili ####

TODO

#### Consultazione dei timesheet mensili prodotti in formato Microsoft Excel ####

TODO

#### Archivio dei timesheet mensili prodotti in formato Microsoft Excel ####

TODO

#### Consultazione dei timesheet mensili prodotti in formato PDF ####

TODO

#### Archivio dei timesheet mensili prodotti in formato PDF ####

TODO

### Report testuali ###

TODO

#### Gestione dei template dei report testuali mensili ####

TODO

#### Produzione manuale di report testuali mensili ####

TODO

#### Consultazione dei report testuali mensili prodotti in formato Microsoft Word ####

TODO

#### Archivio dei report testuali mensili prodotti in formato Microsoft Work ####

TODO

#### Consultazione dei report testuali mensili prodotti in formato PDF ####

TODO

#### Archivio dei report testuali mensili prodotti in formato PDF ####

TODO