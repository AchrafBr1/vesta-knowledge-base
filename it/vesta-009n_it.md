# GILET 009N

**Sensore di movimento PIR (serie IR-16)**

Il nostro algoritmo del processore di segnale adattivo digitalizzato consente a questo PIR di captare i movimenti all'interno di un'area assegnata e segnala al pannello di controllo di attivare l'allarme se un intruso attraversa il suo percorso di rilevamento.

Il PIR è costituito da un design in due parti composto da una copertura e una base. Il coperchio contiene tutta l'elettronica e l'ottica e la base fornisce un mezzo di fissaggio. La base è dotata di fori per consentire il montaggio su una superficie piana o in una situazione d'angolo con una staffa triangolare per il montaggio ad angolo.

La predisposizione per un interruttore antimanomissione che verrà attivato quando il coperchio viene staccato dalla base impedisce l'accesso non autorizzato e la rimozione dalla superficie di montaggio. Il PIR può anche avvisarti per segnalare problemi di comunicazione e situazioni di batteria scarica.

Il PIR è progettato per fornire un raggio di rilevamento tipico di 12 metri se montato a 2 metri dal suolo.

**Il sensore PIR serie IR-16 include i seguenti modelli**:

![](<.gitbook/assets/0 (22).jpeg>)

IR-16 – Sensore PIR con batteria al litio da 3,6 V

IRP-16 – Sensore PIR Pet Immune con batteria al litio da 3,6 V

IR-16SL – Sensore PIR con batteria al litio da 3 V

IRP-16SL – Sensore PIR Pet Immune con batteria al litio da 3 V

-   _**Identificazione delle parti.**_

**1. Pulsante di prova/indicatore LED**

Il pulsante di test viene utilizzato per testare le prestazioni della radio e per scopi di apprendimento.

L'indicatore LED viene utilizzato per indicare lo stato del sistema.

**2. Interruttore antimanomissione**

L'interruttore antimanomissione protegge l'involucro dall'apertura.

1.  **Isolante della batteria**
2.  **Staffa di montaggio ad angolo**
3.  **Interruttore ponticello di abilitazione/disabilitazione supervisione (JP2)**
    -   Se il ponticello è OFF (se il collegamento del ponticello è rimosso o “**parcheggiato**” su un pin), la funzione di supervisione è abilitata.**(Impostazione di fabbrica per i modelli di frequenza 868 WF)**
    -   Se il ponticello è su ON, la funzione di supervisione dell'IR-16 è disabilitata.**(Impostazione di fabbrica per**

![](<.gitbook/assets/1 (30).png>)![](<.gitbook/assets/2 (13).jpeg>)

**Modelli di frequenza 433AM e 868AM)**

-   -   -   **433FM**/**868 modelli di frequenza FM**non supportano l'interruttore jumper JP2, la supervisione è sempre abilitata e non può essere disabilitata.
    -   **Interruttore a ponticello per l'aumento della sensibilità (JP3)**
        -   Se il ponticello è OFF (se il collegamento del ponticello è rimosso o “**parcheggiato**" su un pin), la sensibilità di rilevamento dell'IR-16SL è a un livello normale. (**Impostazione predefinita di fabbrica per i modelli non immuni agli animali domestici**)
        -   Se il ponticello è su ON, la sensibilità di rilevamento dell'IR-16 è alta.**(impostazione predefinita per i modelli immuni agli animali domestici)**
    -   **Interruttore antimanomissione**
-   _**Sveglia**_

![](<.gitbook/assets/3 (13).jpeg>)![](<.gitbook/assets/4 (14).jpeg>)

Il PIR ha un “**ora di dormire**" di circa 1 minuto per risparmiare energia. Dopo aver trasmesso un movimento rilevato, il PIR non ritrasmetterà per 1 minuto; qualsiasi ulteriore movimento rilevato durante questo periodo di sonno ripristinerà il timer di sonno di 1 minuto. In questo modo il movimento continuo davanti a un PIR non scaricherà eccessivamente la batteria.

-   _**Funzione di supervisione**_

Se abilitato, quando il PIR è in modalità di funzionamento normale effettuerà periodicamente un autotest trasmettendo un segnale di supervisione una volta ogni 30-50 minuti

Se la Centrale non riesce a ricevere i segnali di Supervisione trasmessi da un certo PIR per un tempo prestabilito, appare un “**Fuori servizio**r” fault message will be generated.

-   _**Funzione di aumento della sensibilità**_

You can use the sensitivity increaser function to increase the IR’s detection sensitivity. To increase detection sensitivity, please reconnect the Sensitivity Increaser Jumper Switch to **SU**posizione. Per mantenere la normale sensibilità di rilevamento, ricollegare il Jumper a**SPENTO**posizione (impostazione di fabbrica).

-   _**Modalità di prova**_

Il PIR può essere messo in modalità Test premendo il pulsante Test sul coperchio anteriore. In modalità Test, disabiliterà il timer di spegnimento e consentirà all'indicatore LED di lampeggiare ogni volta che viene rilevato un movimento. Ogni volta che si preme il pulsante Test, il PIR trasmetterà un segnale di test al pannello di controllo per il test della portata radio ed entrerà in modalità test per 3 minuti. Uscirà automaticamente dalla modalità test dopo 3 minuti e ritornerà alla modalità normale.

-   _**Indicatore LED**_

Nella modalità di funzionamento normale, l'indicatore LED non si accende tranne che nelle seguenti situazioni:

-   Quando il PIR è in condizione di batteria scarica, ogni volta che trasmette un movimento rilevato, il LED si accenderà per circa 2 secondi.
-   When the cover is opened and the tamper switch is violated, the LED will light up for 2 sec. to indicate it is transmitting the

1

“**Manomettere**" segnale.

-   -   Quando la condizione di Tamper persiste, ogni volta che trasmette un movimento rilevato, il LED si accenderà.
    -   Quando il PIR è in modalità Test, il LED si accenderà ogni volta che viene rilevato un movimento.
-   _**Batteria**_

Il sensore di movimento PIR serie IR-16 utilizza diverse batterie al litio come fonte di alimentazione:

-   I modelli non SL utilizzano una batteria al litio AA da 3,6 V (ER14505) come fonte di alimentazione.
-   The SL models use one 3V 2/3A (CR123) Lithium battery as its power source.

Quando viene rilevata una tensione della batteria bassa, un segnale di batteria scarica verrà inviato al pannello di controllo insieme a trasmissioni regolari di segnali affinché il pannello di controllo visualizzi di conseguenza lo stato.

La batteria viene installata in fabbrica prima della spedizione con un isolante inserito.

_\\<NOTE>_

-   -   -   -   Quando si sostituiscono le batterie, dopo aver rimosso quelle vecchie, premere due volte l'interruttore antimanomissione per scaricarle completamente prima di inserire le nuove batterie.
-   _**Iniziare**_
    -   Estrarre l'isolante della batteria per attivare la batteria.
    -   L'indicatore LED lampeggerà per 30 secondi. (Il PIR si sta riscaldando). Durante il periodo di riscaldamento, il PIR non verrà attivato. Si consiglia di rimanere lontani dall'area di rilevamento durante questo periodo. Al termine del periodo di riscaldamento, il LED si spegnerà e il PIR sarà pronto per il funzionamento.
    -   Mettere il Pannello di Controllo in modalità apprendimento, fare riferimento al manuale del Pannello di Controllo per i dettagli.
    -   Premere il pulsante di prova sul coperchio anteriore.
    -   Fare riferimento al manuale del pannello di controllo per completare il processo di apprendimento.
    -   Dopo aver appreso il PIR, inserire il Pannello di Controllo in “**Prova della camminata**", tenere il PIR nella posizione desiderata e premere il pulsante Test per confermare che questa posizione rientra nel raggio del segnale del pannello di controllo, fare riferimento al manuale del pannello di controllo per completare il test di copertura.
    -   Quando sei soddisfatto che il PIR funzioni nella posizione scelta, puoi procedere al montaggio.
-   _**Metodo di montaggio**_
    -   Il PIR è progettato per essere montato su una superficie piana o in una situazione d'angolo con viti di fissaggio e tasselli forniti.
    -   La base è dotata di fori, dove la plastica è più sottile, per il montaggio. Quattro fori sono destinati al fissaggio superficiale.
    -   Per il montaggio ad angolo, viene fornita una staffa triangolare per aggiungere la protezione antimanomissione posteriore. Montare prima la staffa triangolare sul muro con i due bastoncini di puntamento in alto rivolti verso di sé. Montare il PIR sui ganci della staffa triangolare oppure avvitare il PIR su di essa.
    -   Per il montaggio su superficie, viene fornita una staffa rotante opzionale per consentire agli utenti di regolare il campo di rilevamento. Grazie alla staffa rotante, l'IR-16 può essere ruotato di 80 gradi in orizzontale e di 70 gradi in verticale per fornire una copertura ottimale.
        -   **Montaggio ad angolo:**

I.Rompere i due fori sulla staffa triangolare.

![](<.gitbook/assets/5 (9).jpeg>)

1.  Utilizzando i due fori come modello, praticare dei fori sulla superficie dell'angolo.
2.  Inserire i tasselli.

IV. Avvita la staffa triangolare nei tasselli con i due bastoncini di puntamento in alto rivolti verso di te (usa un cacciavite Philips).

1.  Montare il PIR sui ganci della staffa triangolare.

VI. Se necessario, aprire il PIR rimuovendo la vite di fissaggio e il gruppo del coperchio utilizzando un cacciavite Philips.

VII. Sfondare gli appositi fori di fissaggio degli angoli.

VIII. Utilizzando i fori di fissaggio degli angoli come modello, praticare nuovamente i fori sulla superficie nell'angolo.

![](<.gitbook/assets/6 (13).jpeg>)

IX. Inserire i tasselli se si fissa su intonaco o mattoni.

1.  Montare il PIR sui ganci della staffa triangolare.

XI. Avvitare la base nei tasselli utilizzando un cacciavite Philips.

XII. Riavvitare il coperchio sulla sua base utilizzando un cacciavite Philips.

-   **Montaggio su superficie:**

1.  Rimuovere la vite di fissaggio e il gruppo del coperchio utilizzando un cacciavite Philips.
2.  Sfonda gli appositi fori sulla base.
3.  Utilizzando i fori come modello, praticare dei fori sulla superficie.

IV. Inserire i tasselli se si fissa su intonaco o mattoni.

-   -   1.  Avvitare la base nei tasselli utilizzando un cacciavite Philips.

VI. Riavvitare il coperchio sulla sua base utilizzando un cacciavite Philips.

-   **Montaggio su superficie con staffa rotante (articolo opzionale, venduto separatamente):**La staffa rotante può essere montata a parete tramite viti in dotazione.
    1.  Avvitare la staffa rotante al muro.

1.  Montare opportunamente i 3 ganci della staffa rotante nei 3 fori della base.

2

-   -   1.  Ruotare la staffa per il campo di rilevamento corretto e serrare la vite di fissaggio.
-   _**Installazione**_
    -   Decidi la posizione del PIR e se deve essere montato ad angolo o su superficie.
    -   Dopo aver selezionato il sito di installazione, seguire i passaggi sopra descritti per montare il PIR.
    -   Premere il pulsante Test per accedere alla modalità Test. Camminare attorno all'area protetta osservando quando il LED si accende e verificare che la copertura di rilevazione sia adeguata.
    -   Quando la copertura di rilevamento risulta soddisfacente, l'installazione è completata.
-   _**Raccomandazioni per l'installazione**_

**PIR regolare**

-   Il raggio di rilevamento arriva fino a 12 metri se il PIR è montato a 2 metri dal suolo.

**PIR immune agli animali domestici**

-   Il PIR Pet-Immune supporta la funzione di immunità agli animali domestici e non rileva animali domestici fino a 27 kg entro un raggio di 7 metri per ridurre al minimo la situazione di falsi allarmi.
-   Se necessario, è possibile regolare l'altezza del PIR in base alla taglia del vostro animale domestico per prestazioni immunitarie ottimali. Una posizione di installazione più alta fornirà uno spazio più ampio per l'immunità agli animali domestici, ma aumenterà anche l'angolo cieco sotto il PIR.

![](<.gitbook/assets/7 (12).jpeg>)

Per sfruttare appieno il PIR, è necessario considerare le seguenti linee guida:

-   **Si consiglia di installare il PIR nelle seguenti posizioni**
    -   Montare il rilevatore ad un'altezza di 1,9 M-2,0 M per ottenere le migliori prestazioni:

_\\<IMPORTANT NOTE>_

-   -   Quando si decide l'altezza del luogo di montaggio del PIR, ricordarsi di prendere in considerazione il possibile punto cieco. L'angolo cieco sotto il PIR si allarga proporzionalmente all'altezza del sito di montaggio del PIR.
    -   Tieni presente che le prestazioni sono influenzate da fattori esterni, come l'altezza dell'oggetto rilevato, il raggio di rilevamento desiderato, l'area di installazione, ecc. L'altezza di montaggio suggerita può essere regolata in base ai fattori reali dell'ambiente di installazione.
-   Quando l'IR-16 è montato con una staffa rotante, non avrà la normale area di rilevamento (come nel diagramma sopra) o il tipico raggio d'azione immune agli animali domestici.
    -   Montare in un punto in cui gli animali non possano raggiungere l'area di rilevamento arrampicandosi su mobili o altri oggetti.
    -   Non puntare il rilevatore verso le scale su cui gli animali possono salire.
    -   In una posizione tale che un intruso normalmente si sposterebbe attraverso il campo visivo del PIR da un lato all'altro.
    -   In un angolo per avere la visuale più ampia.
    -   Dove il suo campo visivo non sarà ostruito, ad es. da tende, ornamenti, ecc.
-   **Limitazioni**
    -   Non posizionare un PIR per guardare direttamente una porta protetta da un Contatto Porta, questo potrebbe causare la trasmissione dei segnali radio Contatto Porta e PIR nello stesso istante in cui si entra, annullandosi a vicenda.
    -   Non installare il PIR completamente esposto alla luce solare diretta.
    -   Evitare di installare il PIR in aree in cui i dispositivi possono causare rapidi cambiamenti di temperatura nell'area di rilevamento, ad esempio condizionatori d'aria, riscaldatori, ecc.
    -   Evitare ostacoli di grandi dimensioni nell'area di rilevamento.
    -   Non puntare direttamente verso fonti di calore, ad es. fuochi o caldaie e non sopra i radiatori.
    -   Evitare di spostare oggetti nell'area di rilevamento, ad esempio tende, attaccapanni, ecc.

3
