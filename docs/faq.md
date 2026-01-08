# Frequently Asked Questions (FAQ)

#### Non sono stati generati fogli orari per tutte le unità di personale registrate sul sistema

La causa di una mancata generazione può essere dovuta, ad esempio, ad un errato inserimento dell'indirizzo email sulla piattaforma [ePAS](https://epas.amministrazione.cnr.it) o al fatto che l'unità di personale non è associata ad alcun progetto attivo per il periodo di riferimento corrente.

#### Il timesheet è stato generato in formato Microsoft Excel, ma non in PDF

In questo caso, la generazione del PDF ha dato errore, probabilmente a causa di un problema con l'interazione con l'applicativo Microsoft Excel.

E' possibile risolvere il problema eseguendo l'[operazione di generazione manuale di timesheet mensili](utilizzo_gestionerendicontazione.md#produzione-manuale-di-timesheet-mensili), selezionando il nominativo dell'unità di personale per la quale occorre generare il/i timesheet in formato PDF in fase di generazione.

#### Una unità di personale non più parte dell'organico non riesce ad accedere al portale

Nel caso di dimissioni di una unità di personale durante il mese, o, più in generale, nel caso in cui al momento della generazione dei fogli da compilare tale unità di personale non sia più in rapporto con l'Ente, questa potrebbe non avere più un account Microsoft attivo e, di conseguenza, potrebbe non essere in grado di accedere a RECCO.
Per questo motivo, un utente di RECCO con i privilegi di `gestione-personale` o `gestione-completa` (o di amministrazione) dovrà in questo caso [scaricare il foglio orario da compilare](utilizzo_gestionepersonale.md#consultazione-dei-fogli-orari-prodotti) e condividerlo con l'unità di personale dimessa.
Una volta compilato e ricevuto il documento debitamente compilato, un utente di RECCO con i privilegi di `gestione-rendicontazione` o `gestione-completa` (o di amministrazione) dovrà [caricare manualmente](utilizzo_gestionerendicontazione.md#aggiunta-di-un-foglio-orario-compilato) tale file su RECCO, dunque procedere con l'[operazione di generazione manuale di timesheet mensili](utilizzo_gestionerendicontazione.md#produzione-manuale-di-timesheet-mensili) per il relativo utente.
Infine, una volta prodotti i timesheet, un utente di RECCO con i privilegi di `gestione-rendicontazione` o `gestione-completa` (o di amministrazione) dovrà [scaricare i timesheet prodotti in formato PDF](utilizzo_gestionerendicontazione.md#consultazione-dei-timesheet-mensili-prodotti-in-formato-pdf) (o in [formato Microsoft Excel](utilizzo_gestionerendicontazione.md#consultazione-dei-timesheet-mensili-prodotti-in-formato-microsoft-excel), se la generazione dei PDF non è abilitata) e condividerli con l'unità di personale dimessa.
Infine, una volta firmati i documenti, questi potranno essere condivisi caricandoli tramite la [relativa funzione](comunicazioneorerendicontate.md#caricamento-dei-timesheet-mensili-firmati), che non è vincolata sull'utente collegato.

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

#### Un sottoprogetto non è visibile in piattaforma

In questo caso, occorre notare che se il sottoprogetto ha come progetto principale l'acronimo di un progetto già presente in piattaforma, il sottoprogetto non sarà accessibile da RECCO. In questo caso, è necessario eliminare il sottoprogetto appena creato accedendo via web alla URL del progetto (`https://<dominio_recco>/project/<acronimo_progetto>`), dunque [rimuovendo il progetto creato](utilizzo_gestioneprogetti.md#rimozione-di-un-progetto).

#### E' necessario suddividere un progetto in più sottoprogetti (es. Work Package/Obiettivi Realizzativi/Spoke)

In questo caso, se l'acronimo del progetto presente in piattaforma identifica già il sottoprogetto (es. viene indicato lo Spoke) e le ore registrate/rendicontate all'interno della piattaforma si riferiscono esclusivamente al sottoprogetto, è possibile [modificare il progetto](utilizzo_gestioneprogetti.md#modifica-di-un-progetto) già presente per assegnargli un [progetto principale](utilizzo_gestioneprogetti.md#informazioni-sul-progetto-principale), dunque [aggiungere un nuovo progetto](utilizzo_gestioneprogetti.md#aggiunta-di-un-progetto) specificando lo stesso progetto principale configurato per il progetto già presente.
In riferimento al sottoprogetto inserito, sarà necessario [assegnare uno o più Principal Investigator al progetto](aggiunta-di-un-principal-investigator-ad-un-progetto), [assegnare uno o più partecipanti al progetto](utilizzo_gestioneprogetti.md#aggiunta-di-un-partecipante-ad-un-progetto) e, se necessario, [aggiornare l'effort iniziale per i partecipanti al progetto](utilizzo_gestioneprogetti.md#aggiornamento-delleffort-iniziale-di-un-partecipante-per-un-progetto).

Diversamente, se l'acronimo del progetto presente in piattaforma non identifica il sottoprogetto, si suggerisce di [rimuovere il progetto](utilizzo_gestioneprogetti.md#rimozione-di-un-progetto), dunque [reinserirlo](utilizzo_gestioneprogetti.md#aggiunta-di-un-progetto) come sottoprogetto, specificando un acronimo idoneo, indicante ad esempio Work Package/Obiettivo Realizzativo/Spoke ed assegnando ad esso un [progetto principale](utilizzo_gestioneprogetti.md#informazioni-sul-progetto-principale).
La stessa operazione sarà necessaria per eventuali altri sottoprogetti, che dovranno condividere lo stesso [progetto principale](utilizzo_gestioneprogetti.md#informazioni-sul-progetto-principale).
All'inserimento di un (sotto)progetto, sarà necessario [assegnare uno o più Principal Investigator al progetto](aggiunta-di-un-principal-investigator-ad-un-progetto), [assegnare uno o più partecipanti al progetto](utilizzo_gestioneprogetti.md#aggiunta-di-un-partecipante-ad-un-progetto) e, se necessario, [aggiornare l'effort iniziale per i partecipanti al progetto](utilizzo_gestioneprogetti.md#aggiornamento-delleffort-iniziale-di-un-partecipante-per-un-progetto).
E' importante considerare che questa operazione comporta una perdita di informazioni relative alle ore rendicontate per il progetto fino al momento attuale e, a meno di progetti inseriti di recente e per i quali non si sono rendicontate ore, è pertanto altamente sconsigliata.

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

#### Le ore di formazione indicate nei fogli orari da compilare non rispecchiano l'effettiva frequenza

Le ore di formazione indicate all'interno della piattaforma RECCO vengono recuperate automaticamente dalla piattaforma [ePAS](https://epas.amministrazione.cnr.it); nel caso in cui una registrazione si riferisca a più giornate, il sistema andrà a distribuire in modo uniforme le ore. Ad esempio, nel caso di registrazione di un corso settimanale della durata complessiva di 20 ore, verranno distribuite 4 ore al giorno per tutta la settimana di riferimento. Nel caso in cui tale opzione non è in linea con l'effettiva frequenza del corso, sarà necessario distribuire le ore giornalmente all'interno della piattaforma [ePAS](https://epas.amministrazione.cnr.it), che permette la registrazione di più eventi nello stesso mese.

Per maggiori informazioni, consultare i dettagli in merito ai [fogli orari da compilare](comunicazioneorerendicontate.md#fogli-orari-da-compilare).

#### Non è stato generato un timesheet a zero ore per una unità di personale

Nel caso in cui un progetto sia stato configurato per [forzare la produzione mensile di timesheet](utilizzo_gestioneprogetti.md#informazioni-sulla-forzatura-della-produzione-mensile-di-timesheet), occorre considerare che per poter produrre i timesheet è comunque necessario caricare un foglio orario compilato (anche senza rendicontare ore).
Dunque, nel caso in cui non sia stato generato un timesheet per un progetto nel quale sia stata attivata tale [forzatura](utilizzo_gestioneprogetti.md#informazioni-sulla-forzatura-della-produzione-mensile-di-timesheet) e l'unità di personale non abbia rendicontato ore sul progetto nel periodo di riferimento corrente, la causa è tipicamente imputabile ad una mancanza dell'invio del foglio orario compilato dall'unità di personale stessa.

Per procedere con la generazione sarà dunque necessario, da parte dell'unità di personale oggetto della problematica, [comunicare le ore rendicontate per il periodo di riferimento corrente](comunicazione-delle-ore-rendicontate-per-il-periodo-di-riferimento-corrente).
In alternativa, utenti della piattaforma con il permesso di `gestione-rendicontazione` o `gestione-completa` (o di amministrazione) possono procedere con il [caricamento manuale del foglio orario compilato](utilizzo_gestionerendicontazione.md#aggiunta-di-un-foglio-orario-compilato), dunque con l'[operazione di generazione manuale di timesheet mensili](utilizzo_gestionerendicontazione.md#produzione-manuale-di-timesheet-mensili) per il relativo utente.
