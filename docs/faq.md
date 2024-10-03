# Frequently Asked Questions (FAQ)

#### Non sono stati generati fogli orari per tutte le unità di personale registrate sul sistema

La causa di una mancata generazione può essere dovuta, ad esempio, ad un errato inserimento dell'indirizzo email sulla piattaforma [ePAS](https://epas.amministrazione.cnr.it) o al fatto che l'unità di personale non è associata ad alcun progetto attivo per il periodo di riferimento corrente.

#### Il timesheet è stato generato in formato Microsoft Excel, ma non in PDF

In questo caso, la generazione del PDF ha dato errore, probabilmente a causa di un problema con l'interazione con l'applicativo Microsoft Excel.

E' possibile risolvere il problema eseguendo l'[operazione di generazione manuale di timesheet mensili](utilizzo_gestionerendicontazione.md#produzione-manuale-di-timesheet-mensili), selezionando il nominativo dell'unità di personale per la quale occorre generare il/i timesheet in formato PDF in fase di generazione.

#### Non è stato creato alcun foglio da compilare per una unità di personale non più parte dell'organico

Nel caso di dimissioni di una unità di personale durante il mese, o, più in generale, nel caso in cui al momento della generazione dei fogli da compilare tale unità di personale non sia più in rapporto con l'Ente, questa non comparirà più su [ePAS](https://epas.amministrazione.cnr.it).
Per questo motivo, non sarà possibile scaricare i dati sulle ore lavorate durante il mese da tale unità di personale.
In tal caso, è necessario procedere manualmente alla generazione del foglio orario ed all'intera gestione del processo.

#### Non è stato creato alcun timesheet per una unità di personale non più parte dell'organico

Analogamente a quanto [descritto in precedenza](faq.md#non-è-stato-creato-alcun-foglio-da-compilare-per-una-unità-di-personale-non-più-parte-dellorganico), nel caso di dimissioni di una unità di personale durante il mese, o, più in generale, nel caso in cui al momento della generazione dei timesheet (ma, in questo caso, non dei fogli da compilare) tale unità di personale non sia più in rapporto con l'Ente, questa non comparirà più su [ePAS](https://epas.amministrazione.cnr.it).
Per questo motivo, non sarà possibile scaricare informazioni specifiche (es. il codice fiscale) utili alla generazione dei timesheet per tale unità di personale.
In tal caso, è necessario procedere manualmente alla generazione dei timesheet a partire dagli eventuali fogli orari compilati ed all'intera gestione del processo.

#### E' necessario caricare un foglio orario compilato oltre i termini

Nel caso in cui sia necessario caricare un foglio compilato oltre i termini dell'invio, è necessario [caricare manualmente il file](utilizzo_gestionerendicontazione.md#aggiunta-di-un-foglio-orario-compilato), dunque procedere con l'[operazione di generazione manuale di timesheet mensili](utilizzo_gestionerendicontazione.md#produzione-manuale-di-timesheet-mensili) per il relativo utente.

#### E' necessario generare un foglio orario da compilare e sottomettere oltre i termini

Nel caso in cui sia necessario, oltre i termini di invio dei fogli compilati, procedere con la (ri-)generazione di un foglio orario da compilare, ammesso che i dati su [ePAS](https://epas.amministrazione.cnr.it) siano disponibili per l'unità di personale ed il mese di riferimento (in alternativa, sarà necessario procedere manualmente con le attività), è necessario prima di tutto [generare il foglio orario da compilare](utilizzo_gestionepersonale.md#produzione-di-fogli-orari-per-utenti-specifici) relativo all'unità di personale, dunque, dopo aver ricevuto il foglio orario compilato (esternamente alla piattaforma RECCO, in quanto i termini di invio sono scaduti), in linea con [quanto descritto in precedenza](faq.md#e-necessario-caricare-un-foglio-orario-compilato-oltre-i-termini), è necessario procedere con il [caricamento manuale del foglio orario compilato](utilizzo_gestionerendicontazione.md#aggiunta-di-un-foglio-orario-compilato) ed infine con l'[operazione di generazione manuale di timesheet mensili](utilizzo_gestionerendicontazione.md#produzione-manuale-di-timesheet-mensili) per il relativo utente.

#### Nel nostro istituto, i ricercatori sono abituati a comunicare le ore rendicontate secondo altri strumenti, come si può fare?

In questo caso, le opzioni possibili sono due:
* da una parte, è possibile modificare le abitudini dei singoli ricercatori, inducendo una interazione con la piattaforma RECCO
* dall'altra parte, è possibile collezionare le informazioni secondo le necessità, per poi [caricare manualmente i fogli compilati](utilizzo_gestionerendicontazione.md#caricamento-manuale-dei-fogli-orari-compilati) all'interno della piattaforma, in qualità di utente della piattaforma; in questo caso, secondo le necessità, sarà ad esempio possibile fare uso della piattaforma per una o più delle seguenti attività: i) generazione automatizzata di tutti timesheet mensili; ii) condivisione dei timesheet con le singole unità di personale, chiedendo loro di firmare i documenti; iii) raccolta dei timesheet firmati 

#### E' possibile cambiare l'acronimo di un progetto o di un sotto-progetto?

Considerando che l'acronimo indicato non ha alcun valore esternamente alla piattaforma, se non quello di distinguere in modo chiaro ed inequivocabile un progetto o sotto-progetto, l'acronimo di un progetto o sotto-progetto non può essere modificato, in quanto l'allocazione delle ore da parte del personale fa uso di questo valore, che ci si aspetta non cambi nel tempo.

Nel caso in cui fosse indispensabile modificare l'acronimo di un progetto, l'unica opzione possibile, con potenziale perdita delle informazioni sulle ore rendicontate, è quella di [rimuovere il progetto (o sotto-progetto)](utilizzo_gestioneprogetti.md#rimozione-di-un-progetto) con l'acronimo errato, dunque [reinserirlo](utilizzo_gestioneprogetti.md#aggiunta-di-un-progetto) con l'acronimo corretto.
Al reinserimento, sarà necessario [assegnare uno o più Principal Investigator al progetto](aggiunta-di-un-principal-investigator-ad-un-progetto), [assegnare uno o più partecipanti al progetto](utilizzo_gestioneprogetti.md#aggiunta-di-un-partecipante-ad-un-progetto) e, se necessario, [aggiornare l'effort iniziale per i partecipanti al progetto](utilizzo_gestioneprogetti.md#aggiornamento-delleffort-iniziale-di-un-partecipante-per-un-progetto).
E' importante considerare che questa operazione può portare ad una perdita di informazioni relative alle ore rendicontate fino al momento attuale, e, a meno di progetti inseriti di recente e per i quali non si sono rendicontate ore, è pertanto altamente sconsigliata.

#### Una unità di personale è stata inserita come Principal Investigator per un progetto, ma non può accedervi

In questo caso, occorre considerare che un progetto è visibile su piattaforma solamente ai suoi partecipanti.
Pertanto, l'inserimento del Principal Investigator di un progetto non è sufficiente per mostrare il progetto all'utente.
Al fine di mostrare questa informazione, è possibile procedere con l'[inserimento dell'unità di personale come partecipante al progetto](utilizzo_gestioneprogetti.md#aggiunta-di-un-partecipante-ad-un-progetto).

#### Una unità di personale non trova un progetto da rendicontare per il mese corrente

In questo caso, se il progetto è in corso nel periodo di riferimento, è probabile che l'unità di personale coinvolta non sia stata inserita come partecipante al progetto.
E' possibile procedere con l'[inserimento di un partecipante al progetto](utilizzo_gestioneprogetti.md#aggiunta-di-un-partecipante-ad-un-progetto), dunque, con una nuova [produzione dei fogli orari da compilare](utilizzo_gestionepersonale.md#produzione-di-fogli-orari) per l'unità di personale aggiunta al progetto.

#### Una unità di personale ha la necessità di compilare nuovamente il proprio foglio orario

In questo caso, è possibile procedere con una [sostituzione del foglio orario compilato](utilizzo_gestionerendicontazione.md#sostituzione-di-un-foglio-orario-compilato).
Dunque, sarà necessario procedere con la [produzione manuale dei timesheet](utilizzo_gestionerendicontazione.md#produzione-manuale-di-timesheet-mensili) per l'unità di personale di riferimento.

#### Una unità di personale non riesce a caricare un foglio orario in quanto viene dato costantemente errore

In questo caso bisogna considerare che eventuali celle del foglio orario compilato colorate con sfondo rosso potrebbero causare l'errore.
In aggiunta, l'utilizzo di formule o l'inserimento di informazioni in formato errato (esempio, indicando `7,00` o `7.00` invece di `7:00`) potrebbero causare l'errore.
Si suggerisce dunque di effettuare una analisi accurata di ogni cella compilata all'interno del foglio orario compilato.

#### Per una unità di personale non è stato generato alcun timesheet

In questo caso, [verificare il foglio orario compilato](utilizzo_gestionerendicontazione.md#consultazione-dei-fogli-orari-compilati) dall'unità di personale di riferimento.
In particolare, [verificare che sia stato indicato almeno un progetto (vedi riga 4 del documento) e verificare che non vi siano errori nella compilazione](comunicazioneorerendicontate.md#fogli-orari-da-compilare).
Dunque, se necessario, [sostituire](sostituzione-di-un-foglio-orario-compilato) il documento con quello corretto.
Infine, procedere con la [produzione manuale dei timesheet](utilizzo_gestionerendicontazione.md#produzione-manuale-di-timesheet-mensili) per l'unità di personale di riferimento.
