# Gestione dei progetti

La schermata di gestione dei progetti è riportata a seguire.

<img src="img/interfaccia_progetti.png">

### Progetti ###

Questa sezione permette la gestione dei progetti registrati all'interno della piattaforma.
E' possibile vedere quanti progetti sono registrati all'interno della piattaforma.

Cliccando sul bottone `Gestisci progetti` viene aperta una nuova finestra dedicata.

#### Consultazione dei progetti registrati all'interno della piattaforma ####

<img src="img/interfaccia_progetti_lista.png">

Tale finestra mostra una lista di progetti registrati all'interno del sistema, con le seguenti informazioni:
* codice progetto
* acronimo univoco del progetto
* titolo esteso del progetto
* tipologia di progetto
* percentuale di avanzamento del progetto nel tempo
* percentuale di rendicontazione sul progetto, normalizzata rispetto all'istante corrente

In particolare, la percentuale di rendicontazione normalizzata viene calcolata andando a sommare le ore di rendicontazione totali previste per l'intero progetto per tutte le unità di personale, dunque rapportandole all'attuale stato di avanzamento del progetto; infine, confrontando le ore effettivamente rendicontate ad oggi da tutti i partecipanti al progetto con tale valore.

**Informazioni sul progetto principale**

Occorre considerare che ogni progetto inserito nella piattaforma può essere associato ad un "progetto principale", una stringa testuale (senza spazi o caratteri speciali) che viene utilizzata per raggruppare più progetti.
Ad esempio, l'utilizzo di tale parametro può tornare utile per poter raggruppare più progetti in uno solo, in fase di esportazione o visualizzazione; si pensi ad esempio ad una suddivisione di un progetto in più Work Packages/Obiettivi Realizzativi/Spoke.

In fase di visualizzazione, un "progetto principale" erediterà i valori di campi quale il titolo dal primo "sotto-progetto" (il primo progetto, in ordine alfabetico, che fa uso dell'acronimo del "progetto principale").
Inoltre, non sarà possibile modificare un "progetto principale", ma soltanto i singoli "sotto-progetti" ad esso associati.

#### Modifica di un progetto ####

E' possibile modificare le informazioni associate ad un progetto (bottone `Modifica`).
Tale funzionalità non è disponibile per i progetti terminati.
Inoltre, nella schermata principale, non è disponibile un bottone di modifica nel caso in cui il progetto sia considerato "progetto principale", in quanto tale bottone sarà disponibile per i singoli "sotto-progetti" dello stesso.

<img src="img/interfaccia_progetti_lista_modifica.png">

*Finestra di modifica di un progetto*

In particolare, in fase di modifica, occorre considerare i seguenti aspetti:
* il valore del campo `Raggruppamento` indica come si intende raggruppare più progetti simili in fase di esportazione dei dati/generazione dei timesheet: sono disponibili i valori `Acronimo` (le informazioni esportate riguardano solamente il progetto corrente; scelta preferibile per tutti i progetti non legati ad altri e non suddivisi in Work Packages/Obiettivi Realizzativi/Spoke) oppure `Progetto principale` (le informazioni esportate vengono raggruppate insieme ad altri progetti con il medesimo "progetto principale"; scelta preferibile per progetti suddivisi in Work Packages/Obiettivi Realizzativi/Spoke)
* il template di esportazione identifica il template da utilizzare per la generazione dei timesheet, tra quelli disponibili

Per modificare un progetto, procedere come segue:
1. Accedere alla piattaforma RECCO
2. Aprire il menu `Progetti`
3. Cliccare il bottone `Modifica` adiacente al progetto da modificare
4. Si aprirà una finestra di modifica: aggiornare i dati secondo le necessità
5. Cliccare il bottone `Conferma` per confermare l'operazione

#### Aggiunta di un progetto ####

E' inoltre possibile registrare un nuovo progetto all'interno del sistema, tramite il bottone `Aggiungi progetto`.

<img src="img/interfaccia_progetti_lista_aggiungi.png">

*Finestra di aggiunta di un nuovo progetto*

Per aggiungere un nuovo progetto, procedere come segue:
1. Accedere alla piattaforma RECCO
2. Aprire il menu `Progetti`
3. Cliccare il bottone `Aggiungi progetto` in fondo alla pagina
4. Si aprirà una finestra di aggiunta: inserire i dati secondo le necessità
5. Cliccare il bottone `Conferma` per confermare l'operazione

Rispetto alle informazioni richieste, occorre in particolare considerare quando riportato per le attività di modifica di un progetto.

#### Consultazione di un progetto ####

E' possibile visualizzare una schermata di dettaglio dei progetti, come mostrato nella figura seguente.

<img src="img/progetti_dettagliprogetto.png">

*Scheda di dettaglio di un progetto*

TODO da qui

Pertanto, per poter visualizzare i dettagli un progetto, procedere come segue:
1. Accedere alla piattaforma RECCO
2. Aprire il menu `Progetti`
3. Cliccare il bottone `Gestisci progetti` all'interno della scheda `Gestione progetti`
4. Si aprirà una pagina contenente una lista dei progetti registrati all'interno della piattaforma
5. Identificare il progetto di interesse e cliccare il relativo bottone `Visualizza`

#### Rimozione di un progetto ####

TODO

E' inoltre possibile rimuovere (previa conferma) un progetto specifico dal sistema (bottone `Rimuovi`).

<img src="img/interfaccia_progetti_lista_rimozione.png">

*Finestra di conferma di rimozione di un progetto*

Per rimuovere un progetto, procedere come segue:
1. Accedere alla piattaforma RECCO
2. Aprire il menu `Progetti`
3. Cliccare il bottone `Visualizza` per aprire il progetto da rimuovere
4. Cliccare il bottone `Rimuovi` per procedere con la rimozione del progetto
5. Si aprirà una finestra di conferma: cliccare il bottone `Conferma` per confermare l'operazione
