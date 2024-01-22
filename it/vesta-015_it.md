# VESTA015

**Sensore di movimento PIR a cupola (IRD-23 / IRD-23SL)**

Il sensore di movimento PIR a cupola è progettato per essere montato sul soffitto per fornire una copertura di rilevamento a 360° senza punti ciechi per rilevare i movimenti all'interno di un'area assegnata e segnala al pannello di controllo di attivare l'allarme se un intruso attraversa il suo percorso di rilevamento.

Il PIR è costituito da un design in due parti composto da un corpo principale PIR e una copertura posteriore per il montaggio a parete. Il corpo principale contiene tutta l'elettronica e l'ottica, mentre la base fornisce i mezzi di installazione.

Il corpo principale del PIR è dotato di un interruttore antimanomissione che verrà attivato quando il corpo principale viene rimosso dal coperchio posteriore per impedire l'accesso non autorizzato e la rimozione dalla superficie di montaggio. Il PIR può anche avvisarti per segnalare problemi di comunicazione e situazioni di batteria scarica.

Il Dome PIR comprende 2 modelli:

IRD-23: alimentato da 2 batterie alcaline AA da 1,5 V

IRD-23SL: alimentato da 1 batteria al litio CR123A da 3 V

-   _**Identificazione delle parti.**_

**1. Pulsante Test, ovvero indicatore LED**

Il pulsante di test funge anche da indicatore LED. Il pulsante di test viene utilizzato per testare le prestazioni della radio e per scopi di apprendimento. L'indicatore LED viene utilizzato per indicare lo stato del sistema.

1.  **Sensore IR**
2.  **Interruttore ponticello per aumento sensibilità (JP3)**

![](<.gitbook/assets/0 (25).jpeg>)

È un interruttore a ponticello a 2 pin

-   Se il ponticello è OFF (se il collegamento del ponticello è rimosso o “**parcheggiato”**su un pin),

la sensibilità di rilevamento del PIR è a livello normale. (**Impostazione di fabbrica**)

![](<.gitbook/assets/1 (18).jpeg>)

-   -   Se il ponticello è su ON, la sensibilità di rilevamento del PIR è alta.

1.  **Interruttore antimanomissione**

L'interruttore antimanomissione protegge il PIR dalla rimozione dalla posizione montata.

**5. Vano batteria**

IRD-23: 2 batterie alcaline AA da 1,5 V.

IRD-23SL: 1 batteria al litio CR123A da 3 V

-   1.  **Fori di montaggio**
    2.  **Ganci**
    3.  **Aperture per il montaggio a soffitto (interno)**
-   _**Indicatore LED**_

Nella modalità di funzionamento normale, l'indicatore LED non si accende tranne che nelle seguenti situazioni:

-   -   Quando il PIR è in condizione di batteria scarica, ogni volta che trasmette un movimento rilevato, il LED si accenderà per circa 2 secondi.
    -   Quando il coperchio viene aperto e l'interruttore antimanomissione viene violato, il LED si accenderà

2 secondi per indicare che sta trasmettendo il "**Manomettere**" segnale.

-   -   Quando la condizione di Tamper persiste, ogni volta che trasmette un movimento rilevato, il LED si accenderà.
    -   Quando il PIR è in modalità Test, il LED si accenderà ogni volta che viene rilevato un movimento.
-   _**Sveglia**_

_**Corpo principale PIR**_

![](<.gitbook/assets/2 (17).jpeg>)

_**Copertina posteriore**_

![](<.gitbook/assets/3 (16).jpeg>)

Il PIR ha un “**ora di dormire**" di circa 1 minuto per risparmiare energia. Dopo aver trasmesso un movimento rilevato, il PIR non ritrasmetterà per 1 minuto; qualsiasi ulteriore movimento rilevato durante questo periodo di sonno prolungherà la durata del sonno di un altro minuto. In questo modo il movimento continuo davanti a un PIR non scaricherà eccessivamente la batteria.

-   _**Funzione di supervisione**_

Il PIR trasmette un segnale di supervisione una volta ogni 30-50 minuti. Se la Centrale non riesce a ricevere i segnali di Supervisione trasmessi da un certo PIR per un tempo prestabilito, appare un “**Fuori servizio**r” verrà generato il messaggio di errore.

-   _**Funzione di aumento della sensibilità**_

È possibile utilizzare la funzione di aumento della sensibilità per aumentare la sensibilità di rilevamento dell'IR. Per aumentare la sensibilità di rilevamento, impostare il ponticello JP3 su**SU**posizione. Per mantenere la normale sensibilità di rilevamento, impostare il Jumper JP3 su**SPENTO**posizione (impostazione di fabbrica).

-   _**Modalità di prova**_

1

Il PIR può essere messo in modalità Test premendo il pulsante Test, ovvero il LED, sul coperchio anteriore. In modalità Test, disabiliterà il timer di spegnimento e consentirà all'indicatore LED di lampeggiare ogni volta che viene rilevato un movimento. Ogni volta che si preme il pulsante Test, il PIR trasmetterà un segnale di test al pannello di controllo per il test della portata radio ed entrerà in modalità test per 3 minuti. Uscirà automaticamente dalla modalità test dopo 3 minuti e ritornerà alla modalità normale.

-   _**Batteria**_

Il PIR utilizza batterie diverse a seconda del Modello PIR:

IRD-23: 2 batterie alcaline AA da 1,5 V

IRD-23SL: 1 batteria al litio CR123A da 3 V

Le batterie sono incluse nella confezione. Il PIR è dotato di funzione di rilevamento della batteria scarica. Un segnale di batteria scarica verrà inviato al pannello di controllo insieme a trasmissioni regolari di segnali affinché il pannello di controllo visualizzi di conseguenza lo stato.

_\\<NOTE>_

-   -   Quando si sostituiscono le batterie, dopo aver rimosso quelle vecchie, premere due volte l'interruttore antimanomissione per scaricarle completamente prima di inserire le nuove batterie.
-   _**Interruttore antimanomissione**_

Il PIR è dotato di un interruttore antimanomissione situato sul retro del corpo principale del PIR. Quando il PIR è installato correttamente sul coperchio posteriore, l'interruttore antimanomissione verrà compresso. Quando il PIR viene rimosso dal coperchio posteriore, l'interruttore antimanomissione verrà attivato e farà sì che il PIR invii un segnale di apertura antimanomissione al pannello di controllo.

-   _**Iniziare**_
    -   Inserire la batteria nel vano batteria.
    -   L'indicatore LED lampeggia costantemente per 30 secondi. (Il PIR si sta riscaldando). Durante il periodo di riscaldamento, il PIR non verrà attivato. Si consiglia di rimanere lontani dall'area di rilevamento durante questo periodo. Al termine del periodo di riscaldamento, la luce si spegnerà e il PIR sarà pronto per il funzionamento.
    -   Mettere il Pannello di Controllo in modalità apprendimento, fare riferimento al manuale del Pannello di Controllo per i dettagli.
    -   Premere il pulsante di apprendimento/test sul coperchio anteriore.
    -   Se il pannello di controllo riceve il segnale PIR, visualizzerà le informazioni di conseguenza, fare riferimento al manuale del pannello di controllo per completare il processo di apprendimento.
    -   Dopo aver appreso il PIR, inserire il Pannello di Controllo in “**Prova della camminata**", tenere il PIR nella posizione desiderata e premere il pulsante Test per confermare che questa posizione rientra nel raggio del segnale del pannello di controllo.
    -   Quando sei soddisfatto che il PIR funzioni nella posizione scelta, puoi procedere con l'installazione.
-   _**Linee guida per l'installazione**_
    -   Il PIR è progettato per essere montato a soffitto
    -   Se montato a 2,7 metri di altezza, il PIR fornisce una copertura di rilevamento di un cerchio di circa 360°**6**diametro del metro.
    -   Se montato a 4 metri di altezza, il PIR fornisce una copertura di rilevamento di un cerchio di circa 360°**8**diametro del metro.
    -   Per prestazioni ottimali, ruotare il PIR in modo che l'intruso si sposti attraverso l'area di rilevamento da un lato all'altro.

_\\<NOTE>_

-   -   Per scoprire i “lati” del PIR. Tieni il PIR con l'indicatore LED rivolto verso l'alto e i lati sinistro e destro del PIR sono considerati i lati del PIR. Il sensore PIR è più sensibile quando l'intruso si sposta da un lato all'altro
-   Fare riferimento ai diagrammi seguenti per ulteriori informazioni.

![](<.gitbook/assets/4 (32).png>)

-   **Si consiglia di installare il PIR nelle seguenti posizioni.**
    -   In un'area del soffitto con piena visibilità della copertura di rilevamento, senza ostacoli da elettrodomestici e mobili.
    -   Vicino all'ingresso di una stanza o di una casa per monitorare l'attività di ingresso.
-   **Limitazioni**
    -   Se una porta è già protetta da un contatto porta, non installare il PIR troppo vicino alla porta. Se il contatto porta e il PIR vengono attivati ​​e trasmettono il segnale contemporaneamente, i segnali potrebbero collidere e annullarsi a vicenda.
    -   Non installare il PIR esposto alla luce solare diretta.
    -   Evitare di installare il PIR in aree in cui i dispositivi possono causare rapidi cambiamenti di temperatura nell'area di rilevamento, cioè l'aria

2

condizionatore, riscaldatori, ecc.

-   -   -   -   Evitare ostacoli di grandi dimensioni nell'area di rilevamento.
            -   Non puntare direttamente verso fonti di calore, ad es. Fuochi o caldaie e non sopra i termosifoni.
            -   Evitare di spostare oggetti nell'area di rilevamento, ad esempio tende, attaccapanni, ecc.
    -   Dopo aver selezionato il sito di installazione, seguire i passaggi seguenti per montare il PIR.
    -   Premere il pulsante Test per accedere alla modalità Test. Camminare attorno all'area protetta osservando quando il LED si accende e verificare che la copertura di rilevazione sia adeguata.
    -   Quando la copertura di rilevamento risulta soddisfacente, l'installazione è completata.
-   _**Metodo di montaggio**_
    -   Il PIR è progettato per essere montato a soffitto
    -   La cover posteriore ha 4 fori dove la plastica è più sottile per il montaggio a soffitto.
    -   Dopo aver terminato l'apprendimento del PIR e il test di camminata, procedere a montare il PIR secondo le istruzioni di seguito I. Sfondare i 4 fori all'interno della copertina posteriore

1.  Utilizzare le zappe a sfondamento come dima, praticare i fori nel soffitto e, se necessario, inserire i tasselli.

III. Avvitare il coperchio posteriore al soffitto in base ai fori praticati.

IV. La copertura posteriore presenta numeri all'interno per contrassegnare il numero del foro di montaggio, che corrisponde al numero del gancio di montaggio sul retro del corpo principale. Allineare il foro di montaggio con il gancio di montaggio durante l'installazione. Fare riferimento alla figura seguente per la posizione del gancio di montaggio e del foro.

_**Vista posteriore del corpo principale PIR**__**Vista interna della copertina posteriore**_

![](<.gitbook/assets/5 (13).jpeg>)

1.  Installare il corpo principale PIR sul coperchio posteriore. Montare i ganci sul coperchio posteriore nei fori di montaggio sul corpo principale del PIR VI. Ruotare il corpo principale del PIR in senso orario per bloccare i ganci nel foro di montaggio. Fare riferimento alla figura seguente,

VII. Il montaggio del PIR è ora completo.

![](<.gitbook/assets/6 (16).jpeg>)

3
