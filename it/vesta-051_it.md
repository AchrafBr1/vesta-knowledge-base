# VESTA051

-   Sensore di movimento PIR a tenda (IRC-29)

Il PIR rileva la firma a infrarossi per rilevare i movimenti all'interno di un'area assegnata e segnala al pannello di controllo di attivare l'allarme se un intruso attraversa il suo percorso di rilevamento.

Il PIR è costituito da un design in due parti composto da una copertura e una base. Il PIR contiene tutta l'elettronica e l'ottica e la base fornisce un mezzo di fissaggio. La base è dotata di fori per consentire il montaggio su una superficie piana o sul soffitto.

Il PIR è dotato di un interruttore antimanomissione che verrà attivato quando il coperchio viene aperto o quando viene rimosso dalla superficie montata. Può anche avvisarti per segnalare problemi di comunicazione e situazioni di batteria scarica.

-   ![](<.gitbook/assets/0 (11).jpeg>)_**Identificazione delle parti**_

1.  **Lente PIR**
2.  **Pulsante Impara/Test**

Il pulsante di test viene utilizzato per testare le prestazioni della radio e per scopi di apprendimento.

1.  **Indicatore LED**

L'indicatore LED si trova all'interno del coperchio anteriore ed è visibile solo quando attivato.

1.  **Compartimento della batteria**

Il PIR utilizza 1 batteria CR123A (3 V) come fonte di alimentazione.

1.  **Interruttore antimanomissione**

L'interruttore antimanomissione protegge il PIR dall'apertura non autorizzata del coperchio o dalla rimozione della superficie di montaggio.

1.  **Interruttore ponticello di abilitazione/disabilitazione supervisione (JP2)**

![jumper close](<.gitbook/assets/1 (18).png>)![jumper open](<.gitbook/assets/2 (21).png>)

**Ponticello spento**

se il collegamento del ponticello viene rimosso o “**parcheggiato**"su un perno.

**Ponticello acceso**

Il collegamento del ponticello viene inserito collegando i due pin

\-Quando il ponticello è impostato su ON, la supervisione è disabilitata.**(Impostazione di fabbrica per il modello 433AM)**

\-Quando il ponticello è impostato su OFF, la supervisione è abilitata.**(Impostazione di fabbrica per il modello 868WF)**

_(**868FM**&**869FM**&**F1**Modelli**NON**avere JP2, la supervisione è sempre abilitata)._

1.  **Interruttore a ponticello per l'aumento della sensibilità (JP3)**

![jumper open](<.gitbook/assets/3 (20).png>)

\-Se il ponticello è disattivato (se il collegamento del ponticello è rimosso o “parcheggiato” su un pin), la sensibilità di rilevamento del PIR è a livello normale.**(Impostazione di fabbrica)**

![jumper close](<.gitbook/assets/4 (19).png>)

\-Se il ponticello è su ON, la sensibilità di rilevamento dei PIR è alta.

1.  **Isolante della batteria**

-   _**Sveglia**_

Il PIR ha un “**ora di dormire**" di circa 1 minuto per risparmiare energia. Dopo aver trasmesso un movimento rilevato, il PIR non ritrasmetterà per 1 minuto; qualsiasi ulteriore movimento rilevato durante questo periodo di sonno prolungherà la durata del sonno di un altro minuto. In questo modo il movimento continuo davanti a un PIR non scaricherà eccessivamente la batteria.

-   _**Funzione di supervisione**_

Se abilitato, il PIR effettuerà periodicamente un autotest trasmettendo un segnale di supervisione una volta ogni 30-50 minuti.

Se la Centrale non riesce a ricevere i segnali di Supervisione trasmessi da un certo PIR per un tempo prestabilito, appare un “**Fuori servizio**r” verrà generato il messaggio di errore.

-   _**Regolazione della sensibilità**_

È possibile utilizzare la funzione di aumento della sensibilità per aumentare la sensibilità di rilevamento del PIR. Per aumentare la sensibilità di rilevamento, collegare l'interruttore jumper (JP3) o il**SU**posizione (impostazione predefinita. Per mantenere la normale sensibilità di rilevamento, scollegare l'interruttore jumper (JP3) o il**SPENTO**posizione.

-   _**Modalità di prova**_

Il PIR può essere messo in modalità Test premendo il pulsante Test. In modalità Test, disabiliterà il timer di spegnimento e consentirà all'indicatore LED di lampeggiare ogni volta che viene rilevato un movimento. Ogni volta che si preme il pulsante Test, il PIR trasmetterà un segnale di test al pannello di controllo per il test della portata radio ed entrerà in modalità test per 3 minuti. Uscirà automaticamente dalla modalità test dopo 3 minuti e tornerà alla modalità normale.

-   _Indicatore LED_

Nella modalità di funzionamento normale, l'indicatore LED si accende nelle seguenti situazioni (per i modelli F1, invece, il LED lampeggia):

-   Quando viene rilevato un movimento in condizioni di batteria scarica.
-   Quando il coperchio viene aperto/rimosso dalla superficie di montaggio e l'interruttore antimanomissione viene attivato.
-   Quando viene rilevato un movimento se la condizione di Tamper persiste.
-   Quando viene rilevato un movimento in modalità Test.
-   Quando il pulsante Test viene premuto in condizioni di manomissione o se il PIR ha la batteria scarica.
-   _Batteria_
-   Il PIR utilizza una batteria CR123A da 3 V come fonte di alimentazione.
-   Il PIR è dotato di funzione di rilevamento della batteria scarica. Se viene rilevata una tensione della batteria bassa, un segnale di batteria scarica verrà inviato al pannello di controllo insieme a trasmissioni regolari di segnali affinché il pannello di controllo visualizzi di conseguenza lo stato.
-   Per ogni installazione, la batteria viene installata in fabbrica prima della spedizione con un isolante inserito. Rimuovere l'isolante per attivare la batteria.
-   Quando si sostituiscono le batterie, rimuovere le vecchie batterie e premere due volte l'interruttore antimanomissione per scaricarle prima di inserire nuove batterie.
-   _Iniziare_
-   Estrarre l'isolante della batteria per attivare la batteria.
-   L'indicatore LED lampeggerà per 30 secondi. (Il PIR si sta riscaldando). Durante il periodo di riscaldamento, il PIR non verrà attivato. Si consiglia di rimanere lontani dall'area di rilevamento durante questo periodo. Al termine del periodo di riscaldamento, il LED si spegnerà e il PIR sarà pronto per il funzionamento.
-   Mettere il Pannello di Controllo in modalità apprendimento, fare riferimento al manuale del Pannello di Controllo per i dettagli.
-   Premere il pulsante di prova.
-   Fare riferimento al manuale del pannello di controllo per completare il processo di apprendimento.
-   Dopo aver appreso il PIR, inserire il Pannello di Controllo in “**Prova della camminata**", tenere il PIR nella posizione desiderata e premere il pulsante Test per confermare che questa posizione rientra nel raggio del segnale del pannello di controllo, fare riferimento al manuale del pannello di controllo per completare il test di copertura.
-   Quando sei soddisfatto che il PIR funzioni nella posizione scelta, puoi procedere al montaggio.
-   _Copertura del rilevamento PIR_
-   Se montato verticalmente, il PIR ha una copertura di rilevamento orizzontale di 10° e una copertura di rilevamento verticale di 110° nella parte anteriore.
-   Il PIR verrà attivato solo da movimenti attraverso la copertura orizzontale di 10°.
-   Il PIR può essere montato verticalmente, orizzontalmente sulla superficie della parete o sul soffitto. Diversi metodi di montaggio forniscono copertura e portata di rilevamento PIR diverse (fare riferimento a**Metodi di montaggio**sotto per i dettagli).
-   _Metodi di montaggio_
-   Il PIR è progettato per essere montato su una superficie piana a parete o a soffitto con viti e tasselli di fissaggio forniti.
-   Se il PIR montato viene rimosso forzatamente, l'Area Antisabotaggio verrà lasciata sulla parete separata dal PIR, quindi verrà attivato il tamper.
-   ![未命名-5](<.gitbook/assets/5 (5).jpeg>)La base ha due fori, dove la plastica è più sottile e può essere rotta per il montaggio.

1.  Rimuovere la vite di fissaggio e il gruppo coperchio.
2.  Sfonda i fori all'interno della base.
3.  Utilizzando i fori come modello, praticare dei fori sulla superficie.
4.  Inserire i tasselli se si fissa su intonaco o mattoni.
5.  Avvitare la base nei tasselli.
6.  Avvitare il coperchio sulla base.

-   Esistono diversi metodi di montaggio, inclusi il montaggio verticale/orizzontale e il montaggio a soffitto, e ciascuno di essi ha un'applicazione diversa. Fare riferimento ai metodi di montaggio riportati di seguito.

**Montaggio a parete verticale:**

-   Se montato verticalmente, il PIR ha un raggio di rilevamento di 10 metri solo contro il movimento orizzontale.
-   Si consiglia di montare il PIR verticalmente a un'altezza compresa tra 1,4 e 1,6 metri dal suolo.
-   Evitare il montaggio a una distanza superiore a 1,7 metri, altrimenti il ​​raggio di rilevamento PIR potrebbe essere influenzato.

**Montaggio a parete orizzontale:**

-   Se montato orizzontalmente, il PIR ha un raggio di rilevamento di 5 metri solo contro il movimento verticale. Questa pratica viene solitamente utilizzata per proteggere gli intrusi dal lucernario o dalla botola sul tetto.
-   Evitare il montaggio a un'altezza inferiore a 2,2 metri, poiché potrebbe influire sulle prestazioni di rilevamento.

**Verticale****Orizzontale**

![](<.gitbook/assets/6 (8).png>)![](<.gitbook/assets/7 (5).png>)

**Montaggio a soffitto:**

-   Montare il PIR sul soffitto per guardare verso il basso sopra una porta o una finestra.
-   Se montato a soffitto, il PIR può rilevare solo il movimento verticale rispetto al PIR all'interno del campo di rilevamento.
-   Se montato a 2.4~3 metri di altezza e guardando in basso il PIR ha una copertura di circa**5**metri a livello del suolo.
-   Evitare il montaggio a una distanza superiore a 4 metri, poiché potrebbe influire sulle prestazioni di rilevamento.

![](<.gitbook/assets/8 (5).png>)

-   _Installazione_
-   Decidere la posizione del PIR se deve essere orizzontale/verticale o montato a soffitto.
-   Dopo aver selezionato il sito di installazione, seguire i passaggi sopra descritti per montare il PIR.
-   Premere il pulsante Test per accedere alla modalità Test. Camminare attorno all'area protetta osservando quando il LED si accende e verificare che la copertura di rilevazione sia adeguata.
-   Quando la copertura di rilevamento risulta soddisfacente, l'installazione è completata.
-   _Raccomandazioni per l'installazione_

\\<Important NOTE>

-   Quando si decide l'altezza del luogo di montaggio del PIR, ricordarsi di prendere in considerazione il possibile punto cieco. L'angolo cieco sotto il PIR si allarga proporzionalmente all'altezza del sito di montaggio del PIR.
-   Tieni presente che le prestazioni sono influenzate da fattori esterni, come l'altezza dell'oggetto rilevato, il raggio di rilevamento desiderato, l'area di installazione, ecc. L'altezza di montaggio suggerita può essere regolata in base ai fattori reali dell'ambiente di installazione.
-   In una posizione tale che un intruso normalmente si sposterebbe attraverso il campo visivo del PIR da un lato all'altro.
-   Dove il suo campo visivo non sarà ostruito, ad es. da tende, ornamenti, ecc.
-   **Limitazioni**
-   Non posizionare un PIR per guardare direttamente una porta protetta da un Contatto Porta, questo potrebbe causare la trasmissione dei segnali radio Contatto Porta e PIR nello stesso istante in cui si entra, annullandosi a vicenda.
-   Non installare il PIR completamente esposto alla luce solare diretta.
-   Evitare di installare il PIR in aree in cui i dispositivi possono causare rapidi cambiamenti di temperatura nell'area di rilevamento, ad esempio condizionatori d'aria, riscaldatori, ecc.
-   Evitare ostacoli di grandi dimensioni nell'area di rilevamento.
-   Non puntare direttamente verso fonti di calore, ad es. fuochi o caldaie e non sopra i radiatori.
-   Evitare di spostare oggetti nell'area di rilevamento, ad esempio tende, attaccapanni, ecc.
