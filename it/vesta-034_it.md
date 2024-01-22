# VESTA034

**Manuale utente sensore inclinazione garage (Gdts-1).**

Il sensore di inclinazione del garage monitora l'inclinazione bidirezionale della porta basculante del garage. Il sensore di inclinazione del garage viene fissato al telaio del dispositivo monitorato. Quando la porta è aperta e la superficie rilevata è inclinata inferiore o uguale a 35°(+-10) gradi, o quando la porta è chiusa e la superficie rilevata è inclinata superiore o uguale a 55°(+-10) gradi , il sensore di inclinazione del garage trasmetterà il segnale di allarme al pannello di controllo. Il dispositivo ha anche la capacità di comunicare problemi di segnale insieme a situazioni di batteria scarica.

Il design del sensore di inclinazione del garage è costituito da una copertura e una base. Il coperchio contiene tutta l'elettronica e la base fornisce un mezzo per fissare il dispositivo. Un interruttore antimanomissione PCB incluso fornisce protezione contro l'apertura e/o la rimozione non autorizzata del dispositivo.

**Identificazione delle parti**

![](<.gitbook/assets/0 (32).jpeg>)

1.  **Pulsante di prova/indicatore LED**

**Pulsante di prova:**

-   -   Premere il pulsante Test per trasmettere un codice di apprendimento.
    -   Premere il pulsante Test per accedere alla modalità test per 3 minuti.

**Indicatore LED:**

-   -   Il LED lampeggerà per 3 volte durante la trasmissione di un codice di apprendimento.
    -   Il LED si accenderà ogni volta che il dispositivo viene attivato in modalità test.
    -   Il LED si accenderà ogni volta che viene attivato l'interruttore antimanomissione.
    -   (Sportello aperto) In caso di guasto del dispositivo o in modalità test, il LED lampeggerà per 6 volte.
    -   (Porta chiusa) In caso di guasto del dispositivo o in modalità test, il LED lampeggerà per 6 volte. Dopo 10 secondi, il LED lampeggerà per 3 volte.

1.  **Fori di montaggio**
    -   Utilizzato per fissare e avvitare il sensore di inclinazione del garage direttamente sulla parte superiore della porta del garage.
2.  **Interruttore antimanomissione**
    -   Quando il sensore di inclinazione del garage è montato, l'interruttore antimanomissione sarà completamente compresso contro il muro. Quando il coperchio del dispositivo viene aperto o quando viene rimosso dalla superficie montata, l'interruttore antimanomissione verrà attivato. Il LED lampeggerà per 6 volte e invierà un segnale di apertura antimanomissione per notificare agli utenti questa condizione.
3.  **Isolante della batteria**
4.  **Compartimento della batteria**

**Caratteristiche**

-   _**Indicatore LED**_
    -   Nella modalità di funzionamento normale, il LED si accende quando il sensore di inclinazione del garage è attivato (dispositivo aperto o chiuso).
    -   Quando il coperchio del dispositivo viene aperto o quando viene attivato l'interruttore antimanomissione, il LED si accende.
    -   Quando il sensore di inclinazione del garage è in modalità test, il LED si accenderà ogni volta che viene attivato.
    -   Il LED si accende quando il sensore di inclinazione del garage viene attivato in condizioni di batteria scarica. Quando la batteria è scarica, il sensore di inclinazione del garage interromperà tutte le funzioni, il LED lampeggerà ogni 4 secondi.

1

-   _**Batteria**_
    -   Il sensore di inclinazione del garage è alimentato da una batteria al litio CR123 da 3 V. Notare che:**SEMPRE**sostituire la batteria con la dimensione e il voltaggio corretti.
    -   Il sensore di inclinazione del garage è in grado di rilevare una condizione di batteria scarica. Quando la tensione della batteria è bassa, un segnale di batteria scarica verrà inviato al pannello di controllo per avvisare l'utente di questa condizione. Quando la batteria è scarica, il LED lampeggerà ogni 4 secondi e il dispositivo smetterà di funzionare.
    -   Quando si sostituisce una nuova batteria, rimuovere prima la vecchia batteria. Premere due volte l'interruttore antimanomissione per scaricarla completamente prima di inserire una nuova batteria.
-   _**Iniziare**_
    -   Estrarre l'isolante della batteria per fornire alimentazione al dispositivo.
    -   Mettere il pannello di controllo in modalità apprendimento (fare riferimento al manuale operativo del pannello di controllo per i dettagli).
    -   Premere il pulsante Test del sensore di inclinazione del garage per inviare un codice di apprendimento, il LED lampeggerà per 3 volte.
    -   Fare riferimento al manuale operativo del pannello di controllo per completare il processo di apprendimento.
    -   Dopo aver appreso il sensore di inclinazione del garage, posizionare il pannello di controllo in modalità Walk Test, tenere il sensore di inclinazione del garage nella posizione desiderata e premere il pulsante Test per trasmettere il segnale di test al pannello di controllo. Se il pannello di controllo si trova nel raggio d'azione del segnale del sensore di inclinazione del garage, il pannello visualizzerà di conseguenza le informazioni sul sensore di inclinazione del garage.
    -   Assicurarsi che il sensore di inclinazione del garage si trovi nel raggio d'azione del segnale del pannello di controllo prima del processo di montaggio e installazione.
-   _**Modalità di prova**_
    -   Il sensore di inclinazione del garage può essere messo in modalità test di 3 minuti premendo il pulsante Test (noto anche come indicatore LED) sul coperchio anteriore.
    -   In modalità test, il LED si accende ogni volta che viene attivato il sensore di inclinazione del garage.
    -   Per estendere il timer della modalità test di altri 3 minuti, è sufficiente premere il pulsante Test.
-   _**Interruttore antimanomissione**_
    -   Il sensore di inclinazione del garage sarà protetto da un interruttore antimanomissione quando è montato a filo con la superficie di montaggio. Quando il dispositivo viene rimosso dalla superficie di montaggio o quando il coperchio del dispositivo viene aperto, l'interruttore antimanomissione verrà attivato. Il dispositivo invierà quindi un segnale di apertura antimanomissione alla centrale di controllo per notificare agli utenti questa condizione.
-   _**Segnale di vigilanza**_
    -   Il sensore di inclinazione del garage trasmetterà il segnale di supervisione al pannello di controllo a intervalli casuali di 30-50 minuti.
    -   Se il Pannello di Controllo non riesce a ricevere alcun segnale di supervisione dal Sensore Inclinazione Garage entro un periodo di tempo preimpostato, verrà generato un messaggio di guasto “Fuori Servizio”.

**Installazione**

![](<.gitbook/assets/1 (27).jpeg>)

-   _**Linee guida e raccomandazioni per l'installazione**_

**Orientamento:**

-   Il sensore di inclinazione del garage deve essere installato sulla porta del garage. Quando la porta è aperta e la superficie rilevata è inclinata inferiore o uguale a 35°(+-10) gradi, o quando la porta è chiusa e la superficie rilevata è inclinata superiore o uguale a 55°(+-10) gradi , il sensore di inclinazione del garage trasmetterà il segnale di allarme al pannello di controllo.

![](<.gitbook/assets/2 (25).jpeg>)



2

-   Il sensore di inclinazione del garage deve essere montato sul pannello superiore della porta del garage, come mostrato di seguito.

![](<.gitbook/assets/3 (23).jpeg>)

**Raccomandazioni:**

-   -   Il sensore di inclinazione del garage è progettato per essere montato sulla porta del garage basculante, non per essere utilizzato sulla porta del garage avvolgibile. Montare il rilevatore a 1,8 metri di altezza per prestazioni ottimali.
    -   Il dispositivo deve essere montato verticalmente rispetto al suolo e non deve essere maggiore di +-5 gradi quando montato.
    -   Montare il dispositivo su una superficie asciutta e pulita. Assicurarsi che il dispositivo sia montato con l'indicatore LED in alto.
-   _**Montaggio del sensore di inclinazione del garage**_

![](<.gitbook/assets/4 (25).jpeg>)

Esistono due modi per montare il sensore di inclinazione del garage. Assicurarsi che la posizione sia all'interno del raggio del segnale del pannello di controllo e seguire i passaggi seguenti per procedere:

**Montaggio a vite:**

-   Trova una posizione adatta per installare il sensore di inclinazione del garage. La superficie di montaggio deve essere pulita e asciutta. Se necessario, pulire accuratamente la superficie di montaggio.
-   Utilizzare i due fori di montaggio come modello per contrassegnare e praticare i fori di montaggio.
-   Utilizzare i tasselli forniti per l'installazione su intonaco/mattone. Avvitare il sensore di inclinazione del garage nella parete fornita

tappi. Assicurarsi che i tasselli siano a filo con il muro.

![](<.gitbook/assets/5 (18).jpeg>)

_\\<NOTE>_

-   Utilizzare questo tipo di metodo di montaggio solo quando le porte del garage sono più spesse delle viti.

**Montaggio adesivo:**

-   Trova una posizione adatta per installare il sensore di inclinazione del garage. La superficie di montaggio deve essere pulita e asciutta. Se necessario, pulire accuratamente la superficie di montaggio.
-   Rimuovere la copertura protettiva da un lato del cuscinetto biadesivo. Applicalo sul retro del sensore di inclinazione del garage e premi con decisione per 30 secondi per garantire un buon contatto.
-   Rimuovere l'altro lato del nastro adesivo e premere con decisione il sensore di inclinazione del garage nella posizione desiderata per altri 30 secondi. Si prega di evitare di applicare il tampone adesivo su una superficie irregolare o di riapplicarlo per ottenere prestazioni di rilevamento ottimali.

3
