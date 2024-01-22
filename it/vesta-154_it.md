# VESTA154

**Sensore di movimento per tende da esterno EIRC-1-F1**

EIRC-1-F1 è un sensore di movimento per tende da esterno dotato sia della tecnologia di rilevamento del movimento PIR che a microonde. La combinazione di metodi di rilevamento doppio migliora notevolmente la precisione di rilevamento del sensore di movimento e riduce il tasso di falsi allarmi, utilizzando il PIR come rilevamento iniziale e le microonde come conferma prima di trasmettere effettivamente il segnale di attivazione.

Il sensore di movimento dispone anche della funzione antimascheramento. È in grado di rilevare eventuali tentativi di accecamento del sensore posizionando oggetti nel suo campo visivo.

Utilizzando la piastra di montaggio a forma di L, l'utente può scegliere il montaggio piatto o laterale quando installa il sensore di movimento sulla parete. Questo design consente al sensore di movimento di rilevare movimenti sospetti sulla porta d'ingresso o di rilevare intrusi che scavalcano e sfondano recinzioni o muri.

_**Identificazione delle parti**_

**Davanti****Interno**

![](<.gitbook/assets/0 (46).png>)

**1.****Rilevatore di prossimità digitale**

Il rilevatore viene utilizzato per rilevare qualsiasi tentativo di mascheramento (blocco) da parte di un intruso.

1.  **Lente del sensore**
2.  **LED del trasmettitore (rosso)**

Il LED si accende brevemente quando:

-   Viene premuto il pulsante Apprendimento/Test.
-   L'interruttore antimanomissione viene attivato o ripristinato.
-   Il movimento viene rilevato in modalità test
-   Il movimento viene rilevato in condizioni di batteria scarica o manomissione aperta durante il normale funzionamento

Quando la batteria del sensore di movimento è esaurita, il LED lampeggia ogni 4 secondi.

**4. LED rilevamento microonde (blu)**

Il LED si accende brevemente quando viene attivato il rilevamento delle microonde in modalità test o in modalità test microonde.

**5. LED rilevamento IR (verde)**

Il LED si accende brevemente quando viene attivato il rilevamento IR in modalità test.

1.  **Interruttore antimanomissione**
2.  **Interruttore a ponticello per l'aumento della sensibilità (JP3)**
    -   -   Se il ponticello è**SPENTO**(se il ponticello viene rimosso o “parcheggiato” su un pin), la sensibilità di rilevamento del sensore di movimento è a un livello normale.**(Impostazione di fabbrica)**
        -   Se il ponticello è**SU**, la sensibilità di rilevamento del sensore di movimento è elevata.
3.  **Interruttore ponticello abilita/disabilita test microonde (JP2)**
    -   Quando il ponticello è impostato come**SU**, il sensore di movimento è in modalità test microonde (vedere**Modalità test microonde**)
    -   Quando il ponticello è impostato come**SPENTO**, la modalità test microonde è disabilitata.**(Impostazione di fabbrica)**

![](<.gitbook/assets/1 (49).jpeg>)![](<.gitbook/assets/2 (46).jpeg>)![](<.gitbook/assets/3 (56).png>)

1

![](<.gitbook/assets/4 (41).jpeg>)

1.  **Interruttore della gamma microonde**

La scala della portata è mostrata a destra con la freccia che punta al livello di sensibilità corrente:

-   -   Girando il**Direzione in senso orario**aumenta il raggio di rilevamento.
    -   Girando il**Direzione in senso antiorario**diminuisce il raggio di rilevamento.**Impostazione di fabbrica**: è impostato su medio.

1.  **Pulsante Apprendi/Test**
2.  **Compartimento della batteria**
3.  **Piastra di montaggio di tipo L**
4.  **Fori di montaggio**
5.  **Scudo protettivo**

Lo schermo protettivo protegge il rilevatore digitale di prossimità dalla pioggia.

_**Caratteristiche**_

-   _**Rilevamento del movimento**_
    -   Il sensore di movimento è dotato di sensore PIR e trasmettitore a microonde integrati. Il rilevamento del movimento viene eseguito dal sensore PIR durante il normale funzionamento. Quando il sensore PIR rileva il movimento, il trasmettitore a microonde verrà attivato per verificare il rilevamento del movimento. Se sia il PIR che la Microonda confermano il rilevamento del movimento, il sensore di movimento trasmetterà il segnale di rilevamento.
    -   Il segnale di rilevamento verrà trasmesso solo quando sia il PIR che la Microonda rilevano il movimento.
    -   Regolare l'impostazione dell'interruttore della portata delle microonde per ottimizzare il trasmettitore a microonde e la portata di rilevamento complessiva.
    -   Quando l'interruttore della portata delle microonde è impostato su massimo, il sensore di movimento ha una portata di circa 11 metri se montato a 1,4~Altezza 1,6 m.
    -   Quando l'interruttore della portata delle microonde è impostato su Medio, il sensore di movimento ha una portata di circa 8,5 metri se montato a 1,4~Altezza 1,6 m.
    -   Quando l'interruttore della portata delle microonde è impostato al minimo, il sensore di movimento ha una portata di circa 4,5 metri se montato a 1,4~Altezza 1,6 m.
-   _**Sveglia**_

Il sensore di movimento dispone di un "tempo di sonno" automatico di circa**1 minuto**per il risparmio energetico. Dopo aver trasmesso un movimento rilevato, l'EIR non ritrasmetterà per un minuto. Qualsiasi ulteriore movimento rilevato entro questo periodo di sonno di un minuto prolungherà la durata del sonno di un altro minuto. In questo modo, il movimento continuo davanti all'EIR non scaricherà eccessivamente la batteria.

-   _**Modalità di prova**_

Il sensore di movimento può essere messo in modalità Test premendo il pulsante Impara/Test. La modalità test dura 10 minuti e verrà ripristinata a 10 minuti premendo qualsiasi pulsante Apprendimento/Test. In modalità test, il timer di spegnimento è disabilitato e i LED si accendono quando viene rilevato un movimento. Utilizzare la modalità Test per determinare la copertura di rilevamento del sensore di movimento durante l'installazione del sensore.

-   _**Modalità test microonde**_

La modalità test microonde è destinata esclusivamente al test della portata delle microonde. Utilizzare il ponticello JP2 per abilitare la modalità test microonde. Quando il sensore di movimento è in modalità test microonde, il rilevamento PIR è disabilitato, il trasmettitore a microonde verrà attivato per inviare ripetutamente il segnale a microonde per il rilevamento del movimento. Quando il sensore di movimento rileva movimento in modalità test microonde, il LED blu microonde si accenderà brevemente per indicarlo.

Utilizzare la modalità test microonde per determinare la portata delle microonde e, se necessario, regolare la portata con l'interruttore della portata delle microonde. Assicurarsi di disabilitare la modalità test microonde una volta completato il test impostando il ponticello JP2 su OFF e riportando il sensore di movimento al funzionamento normale.

-   _**Batteria**_
    -   Il sensore di movimento utilizza due batterie al litio AA L91 come fonte di alimentazione.
    -   Il sensore di movimento è dotato di rilevamento di batteria scarica, quando viene rilevata una tensione bassa della batteria, un segnale di batteria scarica verrà inviato al pannello di controllo insieme alle normali trasmissioni del segnale.
    -   Se la batteria non viene sostituita dopo il rilevamento di batteria scarica e la batteria è completamente scarica, il sensore di movimento interromperà tutte le operazioni. Il LED rosso lampeggerà ogni 4 secondi per indicare.
    -   Quando si sostituiscono le batterie, dopo aver rimosso quelle vecchie, premere l'interruttore antimanomissione o l'apprendimento/test un paio di volte per scaricarle completamente prima di inserire le nuove batterie.
-   _**Supervisione**_
    -   Dopo l'installazione, il sensore di movimento trasmetterà un segnale di supervisione al pannello di controllo ogni 30-50 minuti
    -   Se il Pannello di Controllo non riesce a ricevere i segnali di supervisione dal Sensore di Movimento per un periodo di tempo preimpostato, il Pannello di Controllo indicherà sul suo display che il particolare sensore è fuori servizio.
-   _**Interruttore antimanomissione**_

L'interruttore antimanomissione sul sensore di movimento è in posizione normale (antimanomissione chiuso) quando la molla viene compressa contro l'interno del coperchio posteriore del dispositivo. La violazione della manomissione avviene quando il coperchio anteriore viene rimosso dalla base e l'interruttore antimanomissione viene rilasciato.

2

-   _**Rilevamento di prossimità**_
    -   Il sensore di movimento è dotato di un rilevatore di prossimità digitale in grado di rilevare qualsiasi tentativo di mascheramento (blocco) da parte di un intruso.
    -   Quando viene rilevato un evento di mascheramento e la condizione di mascheramento dura 2 minuti, EIRC-1-F1 invierà un segnale di apertura antimanomissione alla centrale di controllo per notificare all'utente la condizione.
    -   Dopo aver rimosso il mascheramento/blocco per 2 minuti, EIRC-1-F1 invierà un segnale di ripristino della manomissione alla centrale di controllo.

_\\<NOTE>_

-   Qualsiasi movimento del trigger IR annullerà l'evento/condizione di mascheramento attualmente rilevato. Un nuovo evento di mascheramento deve essere rilevato e durare 2 minuti affinché il report di apertura manomissione venga trasmesso.

_**Apprendimento e installazione**_

-   _**Iniziare**_
    1.  Rimuovere il coperchio anteriore dalla base allentando la vite di fissaggio inferiore.
    2.  Orientare e inserire le batterie rispettando la polarità.
    3.  Il LED rosso del trasmettitore inizierà a lampeggiare per 30 secondi per indicare che il sensore di movimento si sta riscaldando. Durante il periodo di riscaldamento, il sensore di movimento non verrà attivato. Si consiglia di rimanere lontani dall'area di rilevamento durante questo periodo. Dopo il periodo di riscaldamento, il LED rosso si spegnerà e il sensore di movimento entrerà in funzionamento normale.
    4.  Mettere il Pannello di Controllo in modalità apprendimento; fare riferimento al manuale del pannello di controllo per i dettagli.
    5.  Premere il pulsante Apprendimento/Test per trasmettere il segnale al pannello.
    6.  Se il pannello riceve il segnale dal sensore di movimento, visualizzerà le informazioni del sensore di conseguenza. Fare riferimento al pannello di controllo per completare il processo di apprendimento.
    7.  Dopo aver appreso il sensore di movimento, mettere il pannello di controllo in modalità “Walk Test”, tenere il sensore nella posizione desiderata e premere l'interruttore di test per confermare che questa posizione rientra nel raggio del segnale del pannello di controllo.
    8.  Quando sei soddisfatto della posizione scelta, puoi procedere con l'installazione.

_\\<NOTE>_

-   -   -   **Prova della camminata**essere condotto per confermare il corretto funzionamento e la copertura del sensore di movimento.
        -   Durante l'apprendimento del sensore di movimento o l'esecuzione del test di camminata, evitare di ostruire il rilevatore antimascheramento con le mani, altrimenti il ​​segnale di apertura antimanomissione verrà trasmesso al pannello di controllo se la condizione di mascheramento dura per 2 minuti.
-   _**Metodo di montaggio**_
    -   L'EIRC-1-F1 è progettato per essere montato a parete. A seconda di come si utilizza la piastra di montaggio a forma di L, il sensore di movimento può essere montato in piano o lateralmente se installato a parete.

**Montaggio piatto**

1.  Staccare il gruppo base e coperchio EIRC-1-F1.
2.  Utilizzare i fori di montaggio sul lato più lungo della piastra di montaggio a L come modello per praticare i fori sulla parete per i tasselli. Fissare il lato più lungo della piastra di montaggio alla parete con le viti fornite.**(Foto1)**
3.  Fissare il coperchio posteriore dell'EIRC-1-F1 alla piastra di montaggio con le due viti fornite.**(Foto 2)**

IV. Montare il coperchio anteriore su quello posteriore e serrare la vite di fissaggio inferiore.**(Foto 2)**

1.  Inserire lo scudo protettivo. (Rimuovere la pellicola protettiva da entrambi i lati dello schermo protettivo prima di inserirlo.)

**(Foto 3)**

![](<.gitbook/assets/5 (25).jpeg>)

3

**Montaggio laterale**

1.  Staccare il gruppo base e coperchio EIRC-1-F1.
2.  Utilizzare i fori di montaggio sul lato stretto della piastra di montaggio a L come modello per praticare i fori sulla parete per i tasselli. Fissare il lato stretto della piastra di montaggio alla parete con le viti fornite.**(Foto1)**
3.  Fissare il coperchio posteriore dell'EIRC-1-F1 alla piastra di montaggio con le due viti fornite.**(Foto 2)**

IV. Montare il coperchio sul coperchio posteriore e serrare la vite di fissaggio inferiore.**(Foto 2)**

1.  Inserire lo scudo protettivo.**(Foto 3)**(Rimuovere la pellicola protettiva da entrambi i lati dello schermo protettivo prima di inserirlo.)

![](<.gitbook/assets/6 (35).jpeg>)

_\\<NOTE>_

-   Sulla piastra di montaggio sono presenti tre dadi che consentono la selezione di due livelli di montaggio (alto/basso). Dopo aver fissato la piastra di montaggio alla parete, è possibile scegliere di montare l'EIRC-1-F1 al livello inferiore o al livello superiore con le due viti fornite

![](<.gitbook/assets/7 (34).jpeg>)

4

_\\<NOTE>_

-   -   Dopo aver montato EIRC-1-F1, se la centrale di controllo visualizza lo stato di guasto manomissione per il dispositivo, assicurarsi che il rilevatore antimascheramento non sia ostruito da alcun oggetto e attendere due minuti per vedere se lo stato manomissione aperta viene cancellato . Se lo stato Tamper aperto persiste dopo due minuti, rimuovere il sensore di movimento dalla posizione di montaggio e verificare se l'interruttore antimanomissione è adeguatamente compresso contro l'interno del coperchio posteriore del dispositivo.
-   _**Raccomandazioni per l'installazione**_

Il sensore di movimento deve essere montato a 1,4 m~1,6 m per prestazioni ottimali. Ha una portata massima di 11 metri quando il sensore a microonde è impostato sulla portata massima e montato a 1,6 metri di altezza.

_\\<IMPORTANT NOTE>_

-   -   Si prega di notare che le prestazioni sono influenzate da fattori esterni, come l'altezza dell'oggetto rilevato, il raggio di rilevamento desiderato, l'area di installazione, ecc. L'altezza di montaggio suggerita potrebbe essere regolata in base ai fattori reali dell'ambiente di installazione.
-   **Si consiglia di installare il sensore di movimento nelle seguenti posizioni**
    -   Montare in una posizione tale che un intruso normalmente si sposti attraverso il campo visivo del sensore.
    -   Montare dove il suo campo visivo non sarà ostruito, ad es. da tende, ornamenti, ecc.
-   **Limitazioni**
    -   Non posizionare un sensore di movimento per guardare direttamente una porta protetta da un contatto porta, ciò potrebbe causare la trasmissione dei segnali radio del contatto porta e del sensore di movimento nello stesso istante in cui si entra, causando una collisione del segnale.
    -   Non installare il sensore di movimento completamente esposto alla luce solare diretta.
    -   Evitare di installare il sensore di movimento in aree in cui i dispositivi possono causare rapidi cambiamenti di temperatura nell'area di rilevamento, ad esempio condizionatori d'aria, riscaldatori, ecc.
    -   Evitare ostacoli di grandi dimensioni nell'area di rilevamento.
    -   Non puntare il sensore direttamente verso fonti di calore, ad es. fuochi o caldaie e non sopra i radiatori.
    -   Evitare di spostare oggetti nell'area di rilevamento, ad esempio tende, attaccapanni, ecc.

![](<.gitbook/assets/8 (27).jpeg>)

5

![](<.gitbook/assets/9 (18).jpeg>)

6
