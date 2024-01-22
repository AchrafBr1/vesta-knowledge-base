# VESTA082

**WADC-1****Contatto porta prevenzione vagante**

WADC-1 è un contatto porta che combina sensori PIR per monitorare le aperture della porta e rilevare i movimenti intorno ad essa. Progettato appositamente per coloro che soffrono di demenza e sono inclini a vagare, WADC-1 trasmetterà segnali al pannello di controllo per avvisare l'assistente quando l'utente apre la porta, spostandosi dall'interno della stanza verso l'esterno.

WADC-1 ha due livelli di sensibilità regolabili che offrono ulteriore comodità di utilizzo. Se montato ad un'altezza di 2,1~A 2,3 metri dal suolo, i sensori PIR hanno ciascuno un campo di copertura di 3 x 1 metri a livello del suolo.

![](<.gitbook/assets/0 (37).png>)

-   _**Identificazione delle parti**_

**1. Indicatore LED (rosso)**

L'indicatore LED viene utilizzato per indicare lo stato del sensore PIR Zona 2 (area di apertura della porta) e del contatto della porta.

**2. Indicatore LED (verde)**

L'indicatore LED viene utilizzato per indicare lo stato del sensore PIR Zona 1 e del contatto della porta.

**3. Pulsante di prova**

Premere il pulsante Test per trasmettere il codice di apprendimento o accedere alla modalità test per 3 minuti.

**4. Interruttore a ponticello per l'aumento della sensibilità (JP3)**

![](<.gitbook/assets/1 (38).jpeg>)

**Ponticello acceso**

![](<.gitbook/assets/2 (51).png>)

Viene inserito il ponticello che collega i due pin.

**Ponticello spento**

![](<.gitbook/assets/3 (30).jpeg>)

Il collegamento del ponticello viene rimosso o “**parcheggiato**" su un perno.

-   -   Se il ponticello è su OFF, la sensibilità di rilevamento dei PIR è a livello normale. (**Impostazione di fabbrica**)
    -   Se il ponticello è su ON, la sensibilità di rilevamento dei PIR è impostata su alta.

1.  **Interruttore ponticello per impostazione sensore singolo/multiplo (JP4)**

![](<.gitbook/assets/4 (33).jpeg>)

**Ponticello acceso**

![](<.gitbook/assets/5 (42).png>)

Viene inserito il ponticello che collega i due pin.

**Ponticello spento**

![](<.gitbook/assets/6 (29).jpeg>)

Il collegamento del ponticello viene rimosso o “**parcheggiato**" su un perno.

-   -   Se il ponticello è su OFF, WADC-1 verrà riconosciuto come 3 sensori (sensore PIR Zona 1, sensore PIR Zona 2 e contatto porta).
    -   Se il ponticello è su ON, WADC-1 verrà riconosciuto come 1 sensore (WADC). (**Impostazione di fabbrica**)

1.  **Interruttore a ponticello direzione apertura porta (JP5)**

![](<.gitbook/assets/7 (23).png>)

**Ponticello acceso**

Viene inserito il ponticello che collega i due pin.

Assicurarsi che JP5 sia impostato su ON affinché l'impostazione sia effettiva.

**Ponticello spento**

![](<.gitbook/assets/8 (27).png>)

Il collegamento del ponticello viene rimosso o “**parcheggiato**" su un perno.

-   -   Impostare il ponticello su OFF se la porta su cui è installato il magnete è progettata per essere aperta verso l'esterno. (**Impostazione di fabbrica**)
    -   Impostare il ponticello su ON se la porta su cui è installato il magnete è progettata per essere aperta verso l'interno.

1.  **Compartimento della batteria**
2.  **Interruttore antimanomissione**

Quando il WADC-1 è montato in posizione, l'interruttore antimanomissione verrà attivato quando il coperchio viene aperto o quando il dispositivo viene rimosso dalla superficie di montaggio.

1

-   1.  **Magnete**
-   _**Funzione di supervisione**_
    -   -   Il sensore PIR Zona 1, il sensore PIR Zona 2 e il contatto porta trasmetteranno il loro segnale di supervisione separatamente al pannello di controllo ogni 30-50 minuti.
        -   Se la Centrale non riesce a ricevere i segnali di supervisione trasmessi da un determinato dispositivo per un tempo prestabilito, verrà generato un messaggio di guasto “Fuori Servizio”.
-   _**Funzione di aumento della sensibilità (JP3)**_

![](<.gitbook/assets/9 (13).jpeg>)![](<.gitbook/assets/10 (14).jpeg>)

È possibile utilizzare la funzione di aumento della sensibilità per aumentare la sensibilità di rilevamento dei sensori PIR. Per aumentare la sensibilità di rilevamento, collegare l'interruttore jumper (JP3) per impostarlo su**SU**posizione. Per mantenere la normale sensibilità di rilevamento, scollegare l'interruttore jumper (JP3) per impostarlo su**SPENTO**posizione (impostazione di fabbrica).

![](<.gitbook/assets/11 (17).jpeg>)

-   _**Funzione di impostazione sensore singolo/multiplo (JP4)**_

È possibile utilizzare l'interruttore jumper (JP4) per decidere se riconoscere il dispositivo come sensore singolo o sensori multipli dopo che il dispositivo è stato acquisito nel pannello di controllo. Se l'interruttore jumper (JP4) è impostato su ON, WADC-1 verrà riconosciuto come 1 sensore. Ogni volta che viene rilevato un movimento, il LED lampeggerà. Se l'interruttore jumper è impostato su OFF, WADC-1 verrà riconosciuto come 3 sensori separati (sensore PIR Zona 1, sensore PIR Zona 2 e contatto porta).

![](<.gitbook/assets/12 (23).png>)

_\\<NOTE>_

-   -   Ogni volta prima di modificare l'impostazione di JP4, assicurarsi di rimuovere prima la batteria. Premere più volte il pulsante Test, modificare l'impostazione del ponticello desiderata e reinserire la batteria. Le modifiche saranno effettive una volta fornita l'alimentazione a batteria al dispositivo.
-   _**Rilevamento della direzione di apertura della porta (JP5)**_

![](<.gitbook/assets/13 (16).jpeg>)

Puoi utilizzare l'interruttore a ponticello per impostare la direzione di apertura della porta. Affinché l'impostazione sia effettiva, assicurarsi di impostare prima JP4 su ON. Se la porta su cui è installato il magnete è progettata per essere aperta verso l'esterno, impostare l'interruttore ponticello (JP5) su OFF.

Se la porta è progettata per essere aperta verso l'interno, impostare l'interruttore jumper (JP5) su ON.

![](<.gitbook/assets/14 (17).jpeg>)

-   _**Modalità di prova**_
    -   In modalità normale, premendo il pulsante Test si trasmetterà un segnale di test al pannello di controllo per il test della portata radio e il WADC-1 entrerà in modalità test per 3 minuti. Uscirà automaticamente dalla modalità test dopo 3 minuti e tornerà alla modalità normale.
    -   In modalità Test, l'indicatore LED verde o rosso lampeggerà ogni volta che viene rilevato un movimento nella Zona PIR 1 o Zona PIR 2 (area di apertura della porta); sia il LED Blu che il LED Rosso lampeggeranno quando il contatto della porta viene attivato.
    -   È possibile controllare il raggio di rilevamento dei sensori PIR Zona 1 e Zona 2 attivando i sensori.
-   _**Indicatore LED**_

![](<.gitbook/assets/15 (14).jpeg>)

Nella modalità di funzionamento normale, gli indicatori LED lampeggeranno nelle seguenti situazioni:

-   -   Quando viene rilevato un movimento nella Zona PIR 1 o Zona PIR 2 (area di apertura della porta) in condizioni di guasto (batteria scarica, manomissione aperta) o in modalità test, il LED verde o il LED rosso lampeggeranno.
    -   Quando il contatto della porta viene attivato in condizioni di guasto (batteria scarica, manomissione aperta) o in modalità test, sia il LED verde che il LED rosso lampeggeranno.
    -   Quando il coperchio viene aperto e l'interruttore antimanomissione viene attivato, sia il LED verde che quello rosso lampeggeranno.
    -   Quando si preme il pulsante Test in condizioni di guasto (batteria scarica, manomissione aperta), sia il LED verde che il LED rosso lampeggeranno.
    -   Quando la batteria è scarica, WADC-1 interromperà tutte le funzioni, sia il LED verde che il LED rosso lampeggeranno ogni 4 secondi.
-   _**Batteria**_
    -   WADC-1 utilizza una batteria al litio CR123 da 3 V come fonte di alimentazione:
    -   WADC-1 dispone della funzione di rilevamento della batteria scarica. Se viene rilevata una tensione della batteria bassa, un segnale di batteria scarica verrà inviato al pannello di controllo insieme a trasmissioni regolari di segnali affinché il pannello di controllo visualizzi di conseguenza lo stato.
    -   Quando si cambia la batteria, dopo aver rimosso la vecchia batteria, premere due volte l'interruttore antimanomissione per scaricarla completamente prima di inserire una nuova batteria.
-   _**Iniziare**_
    -   Estrarre l'isolante della batteria per attivare la batteria.
    -   Mettere il Pannello di Controllo in modalità apprendimento, fare riferimento al manuale del Pannello di Controllo per i dettagli.
    -   Premere il pulsante di prova sul lato per inviare un codice di apprendimento al pannello di controllo.
    -   Quando JP4 è impostato su ON, WADC-1 verrà riconosciuto come**1 sensor**(WADC) e occupa 1 zona nel Pannello di Controllo dopo che è stato appreso nel Pannello di Controllo.
    -   Quando JP4 è impostato su OFF, WADC-1 verrà riconosciuto come**3 sensori separati**(sensore PIR Zona 1, sensore PIR Zona 2 e contatto porta) e occupare**3 zone**nel Pannello di controllo dopo che è stato acquisito nel Pannello di controllo.
    -   Fare riferimento al manuale del pannello di controllo per completare il processo di apprendimento.
-   _**Prova della camminata**_
    -   Dopo aver appreso WADC-1, inserire il Pannello di controllo in “**Prova della camminata**", tenere WADC-1 nella posizione desiderata e premere il pulsante Test per confermare se questa posizione rientra nel raggio del segnale del pannello di controllo, fare riferimento a Controllo

![](<.gitbook/assets/16 (12).jpeg>)![](<.gitbook/assets/17 (11).jpeg>)![](<.gitbook/assets/18 (9).jpeg>)

2

Manuale del pannello per completare il Walk Test.

-   -   Quando sei soddisfatto che WADC-1 funzioni nella posizione scelta, puoi procedere al montaggio.
-   _**Linee guida per l'installazione**_
    -   WADC-1 deve essere installato sul telaio della porta proprio sopra la porta per guardare verso il basso e monitorare i movimenti intorno alla porta.
    -   Il magnete deve essere installato sulla porta sul lato opposto della posizione dell'interruttore magnetico interno del contatto della porta.
    -   Il WADC-1 presenta 2 contrassegni su un lato (fare riferimento alla figura), che indicano la posizione dell'interruttore magnetico interno. Il magnete deve essere allineato con il lato con la nervatura del WADC-1 come mostrato nella figura seguente.

![](<.gitbook/assets/19 (6).jpeg>)![](<.gitbook/assets/20 (8).jpeg>)

-   Se la porta su cui è installato il magnete è progettata per essere aperta verso l'esterno, impostare**JP5 su SPENTO**(**Assicurarsi che JP4 sia impostato su ON affinché l'impostazione sia effettiva**). La distanza tra il WADC-1 e il magnete non deve essere superiore a 5 mm quando la porta è chiusa.
-   Se la porta su cui è installato il magnete è progettata per essere aperta verso l'interno, impostare**JP5 su ON**(**Assicurarsi che JP4 sia impostato su ON affinché l'impostazione sia effettiva**). La distanza tra il WADC-1 e il magnete non deve essere superiore a 5 mm quando la porta è chiusa.

3

1.  La superficie di montaggio deve essere pulita, asciutta e liscia. Se necessario, pulire la superficie di montaggio con uno sgrassatore adatto

necessario.

1.  Rimuovere il rivestimento da un lato del nastro biadesivo. Applicare il nastro adesivo sul retro del dispositivo e premere con decisione per 30 secondi per garantire una buona adesione.
    1.  Rimuovere l'altro rivestimento e premere con decisione il contatto della porta nella posizione desiderata per 30 secondi.

_\\<NOTE>_

-   -   -   Non utilizzare l'installazione del nastro adesivo su una superficie con vernice scrostata o screpolata o su una superficie ruvida.
        -   Si prega di non riapplicare il nastro adesivo 3M. Non può essere riutilizzato
-   **Montaggio a vite**

La base ha due fori, dove la plastica è più sottile, per il montaggio. (fare riferimento alla figura a destra)

Per montare il contatto porta:

-   1.  Rimuovere il coperchio svitando la vite di fissaggio del coperchio utilizzando un cacciavite a croce.

1.  Sfonda i fori sulla base.
2.  Utilizzando i fori come modello, praticare entrambi i fori.

IV. Inserire i tasselli se si fissa su intonaco o mattoni.

1.  Avvitare la base nella presa a muro utilizzando un cacciavite Philips.

VI. Attaccare il coperchio alla base e serrare la vite di fissaggio del coperchio.

-   -   Montare il magnete sulla porta utilizzando il pezzettino di nastro biadesivo. Il magnete deve essere allineato con il lato contrassegnato dalla nervatura del contatto porta. L'installazione è ora completa.
-   _**Raccomandazioni per l'installazione**_
    -   WADC-1 deve essere installato sulla parte del telaio della porta che si trova proprio sopra la porta per guardare verso il basso e monitorare i movimenti.
    -   Se montato ad un'altezza di 2,1~2,3 metri e rivolti verso il basso, i sensori PIR (PIR Zona 1 e Zona 2) hanno ciascuno un modello di copertura di 3 x 1 metri a livello del suolo.

4
