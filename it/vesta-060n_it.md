# GILET 060N

**Contatto porta/Sensore d'urto (DCSV-29-2W)**

DCSV-29-2W è un sensore di contatto/urto per porta in grado di inviare segnali wireless al pannello di controllo al rilevamento dell'apertura di porte/finestre o del rilevamento di rottura e urto del vetro della finestra.

Il design del contatto porta/sensore d'urto è costituito da una copertura e una base. Il coperchio contiene tutta l'elettronica e la base fornisce un mezzo per fissare il dispositivo. Un interruttore antimanomissione PCB incluso fornisce protezione contro l'apertura e/o la rimozione non autorizzata del dispositivo.

![](<.gitbook/assets/0 (43).jpeg>)

**Identificazione delle parti**

1.  **Indicatore LED/Pulsante Test**
    -   Premere il pulsante una volta per inviare un codice di apprendimento o accedere alla modalità test per 3 minuti.
2.  **Vite di fissaggio del coperchio**
3.  **Fori di montaggio**
4.  **Interruttore antimanomissione**
    -   Fornisce protezione antimanomissione contro l'apertura e/o la rimozione non autorizzata del dispositivo dalla superficie di montaggio.
5.  **Isolante della batteria**
6.  **Compartimento della batteria**
7.  **Magnete**
8.  **Foro per vite magnetica**
9.  **Distanziatore magnetico**

**Caratteristiche**

![](<.gitbook/assets/1 (37).jpeg>)

-   _**Indicatore LED**_
    -   Nella modalità di funzionamento normale, il LED non si accende quando il dispositivo è attivato.
    -   Quando la tensione della batteria del dispositivo è bassa, il LED lampeggerà rapidamente quando il dispositivo viene attivato.
    -   Quando l'interruttore antimanomissione viene attivato, il LED lampeggia rapidamente. Quando la condizione di manomissione persiste, il LED lampeggerà velocemente ogni volta che il dispositivo viene attivato. (Solo per l'attivazione del contatto porta).
    -   In modalità Test, il LED lampeggerà rapidamente ogni volta che il dispositivo viene attivato.
    -   Quando la batteria è scarica, il LED lampeggerà ogni 4 secondi.
    -   Il LED non lampeggerà se la manomissione del dispositivo e la batteria sono normali e non sono in modalità test.
    -   Se il LED lampeggia per indicare la trasmissione del segnale, lampeggerà due volte rapidamente dopo aver ricevuto la conferma dalla centrale.
    -   Quando il comando di programmazione dal pannello di controllo viene ricevuto con successo, il LED diventerà più luminoso e poi si spegnerà.
-   _**Rilevamento apertura porta e rilevamento urti**_

![](<.gitbook/assets/2 (48).png>)

Il dispositivo viene attivato dall'apertura di una porta/finestra o da un rilevamento di urto che supera la soglia di rilevamento.

![](<.gitbook/assets/3 (29).jpeg>)

-   _**Materiali della superficie di montaggio**_

Il dispositivo supporta il rilevamento degli urti su vari materiali tra cui vetro, legno, metallo e cemento. Dopo l'installazione, è possibile selezionare il materiale della superficie montata sul pannello di controllo. L'impostazione predefinita è impostata come

![](<.gitbook/assets/4 (43).png>)

**Legna**

-   _**Sensibilità**_
    -   La sensibilità richiesta per attivare il contatto porta/sensore d'urto viene determinata dal pannello di controllo.
    -   Sono selezionabili tre livelli di sensibilità:**Basso**,**medio**, E**Alto**. L'impostazione predefinita è impostata come**medio**.

1

-   ![](<.gitbook/assets/5 (21).jpeg>)_**Batteria**_
    -   Il contatto porta/sensore d'urto utilizza una batteria al litio CR123 da 3 V come fonte di alimentazione. La batteria è installata nel vano batteria con un isolante della batteria inserito. Per attivare la batteria è sufficiente estrarre l'isolante della batteria.
    -   Il contatto della porta/sensore d'urto è in grado di rilevare la condizione di batteria scarica. Quando la tensione della batteria è bassa, un segnale di batteria scarica verrà inviato al pannello di controllo per notificare la condizione. Il LED si accende quando il contatto porta/sensore d'urto viene attivato in condizioni di batteria scarica. Quando la batteria è scarica, il contatto porta/sensore d'urto interromperà tutte le funzioni, il LED lampeggerà ogni 4 secondi.
    -   Quando si sostituiscono le batterie, dopo aver rimosso quelle vecchie, premere due volte l'interruttore antimanomissione per scaricarle completamente prima di inserire le nuove batterie.
-   _**Protezione antisabotaggio**_
    -   Il contatto porta/sensore d'urto è protetto da un interruttore antimanomissione che viene compresso contro la superficie di montaggio quando il contatto porta/sensore d'urto è montato. Ogni volta che il contatto porta/sensore d'urto viene rimosso dalla superficie montata o il coperchio viene aperto, l'interruttore antimanomissione verrà attivato e il dispositivo invierà un segnale di apertura antimanomissione per ricordare all'utente la condizione.
    -   Il segnale di apertura antimanomissione verrà trasmesso con il contatto porta alla centrale di controllo. Lo stato di guasto manomissione verrà visualizzato solo nella zona del dispositivo DC nel pannello di controllo.
-   _**Supervisione**_
    -   Durante il funzionamento normale, il contatto porta e il sensore d'urto invieranno un segnale di supervisione al pannello di controllo separatamente a intervalli casuali di 90-110 minuti.
    -   Se il pannello di controllo non ha ricevuto il segnale di supervisione dal contatto della porta/sensore di shock per un periodo di tempo prestabilito, il pannello di controllo indicherà che il particolare contatto della porta/sensore di shock sta riscontrando un problema di mancanza di segnale.
-   _**Modalità di prova**_
    -   In modalità normale, premere il pulsante Test per trasmettere un segnale di test e un codice di apprendimento al pannello di controllo. Anche il contatto della porta/sensore d'urto entrerà in modalità test per 3 minuti.
    -   In modalità test, il LED si accende ogni volta che viene attivato il contatto porta/sensore d'urto.
    -   Ogni ulteriore pressione del pulsante Test ripristinerà il tempo della modalità test a 3 minuti.
-   _**Iniziare**_
    -   Rimuovere l'isolante della batteria sul contatto porta/sensore d'urto per accendere.
    -   Mettere il pannello di controllo in modalità apprendimento (fare riferimento al manuale operativo del pannello)
    -   Premere il pulsante Test sul contatto porta/sensore d'urto.
    -   Fare riferimento al manuale operativo del pannello di controllo per completare il processo di apprendimento.
    -   Una volta acquisito nel pannello di controllo, il DCSV-29-2W verrà riconosciuto come 2 dispositivi separati (contatto porta e sensore di shock) e occuperà 2 zone nel pannello.
    -   Imposta il livello di materiale e sensibilità:
        1.  Dopo aver acquisito DCSV-29-2W nel pannello di controllo, premere una volta il pulsante Test su DCSV-29-2W.
        2.  Vai alla pagina web del Pannello di controllo per modificare il dispositivo.
        3.  Selezionare il materiale e il livello di sensibilità nella pagina Impostazioni dispositivo. Fare clic su OK per confermare.

![](<.gitbook/assets/6 (28).jpeg>)![](<.gitbook/assets/7 (25).jpeg>)![](<.gitbook/assets/8 (18).jpeg>)![](<.gitbook/assets/9 (26).png>)![](<.gitbook/assets/10 (13).jpeg>)![](<.gitbook/assets/11 (18).png>)![](<.gitbook/assets/12 (22).png>)

2

-   -   1.  Premere il pulsante Test di DCSV-29-2W per ricevere i dati sul livello di materiale e sensibilità dal pannello di controllo. Il LED prima si spegnerà, quindi diventerà più luminoso e poi si spegnerà, indicando che il comando di programmazione dal pannello di controllo è stato ricevuto con successo.
-   _**Prova della camminata**_
    -   After the Door Contact / Shock Sensor is learned-in, place the Control Panel into (**Prova della camminata**), tenere il contatto della porta/sensore d'urto nella posizione desiderata e premere il pulsante Test per trasmettere il segnale di test al pannello di controllo. Se il pannello di controllo si trova nel raggio d'azione del segnale del contatto porta/sensore d'urto, il pannello visualizzerà di conseguenza le informazioni sul contatto porta/sensore d'urto.
    -   Procedere con il montaggio e l'installazione una volta accertato che il contatto porta/sensore d'urto funzioni correttamente nella posizione desiderata.

![](<.gitbook/assets/13 (14).jpeg>)

**Installazione**

![](<.gitbook/assets/14 (16).jpeg>)

-   _**Montaggio del contatto porta/sensore d'urto**_

**Montaggio come contatto porta:**

-   Il contatto porta/sensore d'urto deve essere installato con il lato contrassegnato dalla nervatura rivolto verso il magnete.
-   La distanza tra il contatto porta/sensore d'urto e il magnete non deve essere superiore a 15 mm quando la porta è chiusa.
-   Montare il dispositivo il più in alto possibile.

![](<.gitbook/assets/15 (12).jpeg>)

**Montaggio come sensore d'urto:**

Fare riferimento alla tabella seguente per informazioni sulla posizione di installazione e sullo spessore dei diversi materiali:

|                                |                        |                       | Finestra di vetro | Porta in legno/metallo | Muro di cemento |   |
| ------------------------------ | ---------------------- | --------------------- | ----------------- | ---------------------- | --------------- | - |
|                                | **Spessore**           | >5mm                  | &lt;40 mm         | -                      |                 |   |
|                                |                        |                       |                   |                        |                 |   |
| **Posizione di installazione** | Cornice della finestra | Porta                 | Parete            |                        |                 |   |
|                                |                        |                       |                   |                        |                 |   |
|                                |                        | **Bassa sensibilità** | 0,5 milioni       | 0,5 milioni            | 0,25 milioni    |   |
| **Rilevamento degli urti**     |                        |                       |                   |                        |                 |   |
| **Sensibilità media**          | 1M                     | 1M                    | 0,5 milioni       |                        |                 |   |
| **Raggio**                     |                        |                       |                   |                        |                 |   |
|                                |                        |                       |                   |                        |                 |   |
|                                |                        |                       |                   |                        |                 |   |
|                                |                        | **Alta sensibilità**  | 1,5 milioni       | Madre                  | 1M              |   |
|                                |                        |                       |                   |                        |                 |   |

![](<.gitbook/assets/16 (10).jpeg>)

3

-   ![](<.gitbook/assets/17 (10).jpeg>)_**Procedura di montaggio**_
    1.  Utilizzare i 2 fori di montaggio sul coperchio posteriore come modello per il posizionamento.
    2.  Utilizzare i tasselli forniti per l'installazione su telai di finestre/pareti in cemento.
    3.  Avvitare il contatto porta/sensore d'urto nei tasselli. (Si consiglia di forare in caso di montaggio su acciaio, oppure è anche possibile utilizzare l'adesivo fornito nella confezione).
    4.  Montare il magnete sulla porta utilizzando un piccolo pezzo di nastro biadesivo o con le viti fornite.
    5.  Per montare il magnete, utilizzare i 2 fori per le viti del magnete come modello per il posizionamento appropriato del foro.
        -   _NOTA >_
            -   Il magnete deve essere allineato con il lato contrassegnato dalla nervatura del contatto porta. Se necessario, applicare il distanziale del magnete sul retro del magnete per allineare meglio il magnete ai segni delle nervature.
    6.  Avvitare il magnete e inserire i due cappucci bianchi nei fori delle viti del magnete per integrità estetica.
    7.  L'installazione è ora completa.

![](<.gitbook/assets/18 (14).png>)![](<.gitbook/assets/19 (4).jpeg>)

4
