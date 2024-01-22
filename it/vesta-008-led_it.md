# VESTA008LED

**Telecamera con sensore di movimento PIR**

**VST-862**

**introduzione**

VST-862 è una telecamera con sensore di movimento a infrarossi passivi (PIR). È in grado di inviare segnali wireless e immagini catturate (qualità dell'immagine fino a 640 x 480 pixel) al pannello di controllo al rilevamento del movimento.

La telecamera PIR è progettata per fornire un raggio di rilevamento tipico di 12 metri se montata a 2 metri dal suolo. I modelli pet-immune supportano l'immunità agli animali domestici fino a 27 kg entro un raggio di 7 metri per ridurre al minimo la situazione di falsi allarmi. Per i modelli compatibili con il ripetitore RP-29/router RMB-29 di Climax**(Solo modelli P5)**, il raggio di comunicazione RF può essere ulteriormente esteso in aree difficili da raggiungere.

La telecamera PIR è costituita da un design in due parti composto da una copertura e una base. Il coperchio contiene tutta l'elettronica e l'ottica e la base fornisce un mezzo di fissaggio. La base è dotata di fori per consentire il montaggio su una superficie piana o in una situazione d'angolo con una staffa triangolare per il montaggio ad angolo.

**La serie VST-862 comprende i seguenti modelli:**

| **Nome del modello** | **LED lampeggiante** | **LED a infrarossi** | **Immune agli animali domestici** | **Compatibile con** |
| -------------------- | -------------------- | -------------------- | --------------------------------- | ------------------- |
|                      |                      |                      |                                   | **Ripetitore**      |
| VST-862-(P5)         | IN                   |                      |                                   | Solo modello P5     |
|                      |                      |                      |                                   |                     |
| VST-862-IL-(P5)      |                      | IN                   |                                   | Solo modello P5     |
|                      |                      |                      |                                   |                     |
| VST-862P-(P5)        | IN                   |                      | IN                                | Solo modello P5     |
|                      |                      |                      |                                   |                     |
| VST-862P-IL-(P5)     |                      | IN                   | IN                                | Solo modello P5     |
|                      |                      |                      |                                   |                     |

![](<.gitbook/assets/0 (21).jpeg>)

**Identificazione delle parti**

**1.****LED flash/LED infrarossi**

Il LED flash (per 862(P)) o il LED a infrarossi (per 862(P)-IL) forniscono luce sufficiente per l'acquisizione di immagini in condizioni di scarsa illuminazione.

**2. LED blu/pulsante funzione**

**LED blu:**

(Per favore riferisci a_**Indicatore LED**_descrizione qui sotto per i dettagli)

**Utilizzo dei pulsanti funzione:**

-   -   Tieni premuto il pulsante per 3 secondi per inviare un codice di apprendimento, rilascialo quando il LED blu si accende. (Per il pannello alimentato a batteria, dopo aver tenuto premuto il pulsante per 3 secondi, premere il pulsante**Ancora**per un secondo per inviare un codice di apprendimento.)
    -   Premere il pulsante una volta per accedere alla modalità test per 3 minuti.
    -   Premere una volta il pulsante per inviare un codice di apprendimento al ripetitore/router. (Solo modelli P5)

1.  **Sensore IR**
2.  **Obiettivo della fotocamera PIR**
3.  **Coperchio del vano batteria**
4.  **Interruttore antimanomissione**
5.  **Compartimento della batteria**
6.  **Interruttore a ponticello per la regolazione della sensibilità (JP3)**

![](<.gitbook/assets/1 (29).png>)

**Ponticello acceso****Ponticello spento**

![](<.gitbook/assets/2 (12).jpeg>)

Il collegamento del ponticello viene inserito collegando i due pin.

se il collegamento del ponticello viene rimosso

O "**parcheggiato**" su un perno.

-   -   Jumper On: il livello di sensibilità del PIR è impostato su Alto.
    -   Jumper Off: il livello di sensibilità del PIR è impostato su Normale. (**Factory Default**)

1.  **Interruttore a ponticello del timer di spegnimento (JP2)**

![](<.gitbook/assets/3 (30).png>)

**Ponticello acceso**

![](<.gitbook/assets/4 (13).jpeg>)

Il collegamento del ponticello viene inserito collegando i due pin.

**Ponticello spento**

se il collegamento del ponticello viene rimosso

O "**parcheggiato**" su un perno.

-   Jumper On: Dopo il rilevamento del movimento, la telecamera PIR non entra in modalità di sospensione e trasmetterà nuovamente il segnale di rilevamento immediatamente se attivata (**Impostazione di fabbrica**).
-   Jumper disattivato: la telecamera PIR ha un "**ora di dormire**" di circa 1 minuto dopo il rilevamento del movimento per risparmiare energia.

1

**Caratteristiche**

![](<.gitbook/assets/5 (22).png>)

-   _**Indicatore LED**_

Nella modalità di funzionamento normale, il LED blu non si accende tranne che nelle seguenti situazioni:

-   -   Quando la telecamera PIR è in condizioni di batteria scarica, ogni volta che trasmette un movimento rilevato, il LED blu lampeggia per 2 secondi.
    -   Quando il coperchio viene aperto e l'interruttore antimanomissione viene violato, il LED blu lampeggia per 2 secondi, per indicare che sta trasmettendo il segnale "Tamper".
    -   Quando la condizione di Tamper persiste, ogni volta che trasmette un movimento rilevato, il LED Blu lampeggerà per 2 secondi.
    -   Quando la telecamera PIR entra in modalità test, il LED blu lampeggia per 1 secondo. Durante la modalità Test, anche il LED Blu lampeggerà per 2 secondi ogni volta che viene rilevato un movimento.
    -   When the PIR Camera is in 30 seconds warm up period, the Blue LED will slow flash.
    -   Quando la telecamera PIR trasmette immagini catturate in condizioni di guasto (batteria scarica, interruttore antimanomissione attivato), il LED blu lampeggia continuamente.
-   _**Acquisizione di immagini**_

![](<.gitbook/assets/6 (13).png>)

Quando il sistema di allarme è armato, la telecamera PIR catturerà 1, 3 o 6 immagini di allarme con risoluzioni 640 x 480 o 320 x 240 (programmabili dal pannello di controllo) al rilevamento del movimento. Puoi anche richiedere manualmente alla telecamera PIR di scattare una foto tramite il pannello di controllo. Le immagini catturate verranno trasferite al Pannello di controllo affinché gli utenti possano visualizzarle.

![](<.gitbook/assets/7 (10).png>)

_\\<NOTE>_

-   -   Se la tua telecamera PIR è installata in un luogo in cui il campo visivo della telecamera è un ambiente complesso con luce intensa o molti colori, le immagini catturate avranno dimensioni di file elevate, il che potrebbe comportare un troncamento quando le immagini vengono trasmesse al pannello di controllo .
-   _**Periodo di riscaldamento**_

![](<.gitbook/assets/8 (12).png>)

Quando il sistema del pannello di controllo entra in modalità attivazione o quando la telecamera PIR viene messa in modalità test, la telecamera PIR si riscalda per 30 secondi. Durante il periodo di riscaldamento di 30 secondi, la telecamera PIR non verrà attivata. Il LED blu lampeggerà lentamente durante il periodo di riscaldamento solo quando il PIR entra in modalità test.

![](<.gitbook/assets/9 (13).png>)

-   _**Sveglia**_

Quando**Interruttore a ponticello 2**è impostato su Off, la telecamera PIR ha un "**ora di dormire**" di circa 1 minuto per risparmiare energia. Dopo aver trasmesso un movimento rilevato, la telecamera PIR non ritrasmetterà per 1 minuto. Qualsiasi movimento rilevato durante questo periodo ripristinerà il tempo di sonno a 1 minuto. Il movimento continuo davanti alla telecamera PIR non scaricherà quindi la batteria.

![](<.gitbook/assets/10 (3).jpeg>)

-   _**Rilevamento batteria e batteria scarica**_

La telecamera PIR ne utilizza due**Batterie alcaline “AA” da 1,5 V**in collegamento in serie come fonte di alimentazione. Rimuovere il coperchio del vano batterie e inserire le batterie per attivare la telecamera PIR.

La telecamera PIR è dotata della funzione di rilevamento della batteria scarica. Quando la tensione della batteria è bassa, la telecamera PIR trasmetterà il segnale di batteria scarica al pannello di controllo. Se viene rilevato un movimento in condizioni di batteria scarica, il LED blu lampeggerà per 2 secondi.

Quando si cambia la batteria, dopo aver rimosso la vecchia batteria, premere due volte l'interruttore antimanomissione o il pulsante funzione per scaricarla completamente prima di inserire nuove batterie

![](<.gitbook/assets/11 (8).png>)

-   _**Protezione antisabotaggio**_

La telecamera PIR è protetta da un interruttore antimanomissione che viene compresso quando la telecamera PIR è installata correttamente. Quando la telecamera PIR viene rimossa dalla superficie montata o il suo coperchio viene aperto, l'interruttore antimanomissione verrà attivato e la telecamera PIR invierà un segnale di apertura antimanomissione al pannello di controllo del sistema per ricordare all'utente la condizione. Se viene rilevato un movimento quando l'interruttore antimanomissione è aperto, il LED blu lampeggerà per 2 secondi.

![](<.gitbook/assets/12 (11).png>)

-   _**Supervisione**_

La telecamera PIR effettuerà periodicamente un autotest trasmettendo un segnale di supervisione una volta ogni 90-110 minuti.

![](<.gitbook/assets/13 (9).png>)

-   _**Modalità di prova**_
    -   La modalità test serve per verificare il raggio di rilevamento della telecamera PIR (non la copertura della ripresa).
    -   Premere una volta il pulsante Funzione per accedere alla modalità Test per 3 minuti, il LED blu lampeggerà per 1 secondo.
    -   La telecamera PIR si riscalderà per 30 secondi. Si prega di non attivare la fotocamera durante questo periodo di riscaldamento.
    -   Dopo il periodo di riscaldamento, è possibile attivare la telecamera PIR per verificare il raggio di rilevamento IR. Se la telecamera PIR viene attivata, il LED blu lampeggerà per 2 secondi.
-   _**Apprendimento**_
    -   Accendere la telecamera PIR estraendo l'isolante della batteria situato sul coperchio del vano batteria.
    -   Mettere il Pannello di Controllo in modalità apprendimento, fare riferimento al manuale del Pannello di Controllo per i dettagli.
    -   Tenere premuto il pulsante funzione per 3 secondi, rilasciare il pulsante quando il LED blu si accende. (Per

![](<.gitbook/assets/14 (5).jpeg>)

2

pannello a batteria, dopo aver tenuto premuto il pulsante funzione per 3 secondi, premere il pulsante funzione**Ancora**per un secondo.)

-   Il LED blu si accenderà per 25 secondi in modalità di apprendimento, aggiungi la telecamera PIR al pannello di controllo durante questo periodo (fai riferimento al tuo pannello di controllo per completare il processo di apprendimento). Se il PIR viene aggiunto con successo al pannello di controllo, il LED blu lampeggerà 6 volte per indicarlo. Se il PIR non viene aggiunto entro 25 secondi, ripetere l'apprendimento

processi.

![](<.gitbook/assets/15 (7).png>)

_\\<NOTE>_

-   -   -   -   Se la telecamera PIR esiste già in un sistema di pannello di controllo, sarà necessario rimuovere la telecamera PIR dal pannello di controllo prima di poterla acquisire in un pannello di controllo diverso.
            -   Quando si apprende la telecamera PIR in un ripetitore/router, premere una volta il pulsante funzione (invece di tenerlo premuto per 3 secondi) per inviare un codice di apprendimento. (Solo modelli P5)
-   _**Prova della camminata**_
    -   Dopo aver appreso la telecamera PIR, inserire il pannello di controllo in "**Prova della camminata**", tenere la telecamera PIR nella posizione desiderata e premere il pulsante funzione per confermare che questa posizione rientra nel raggio del segnale del pannello di controllo, fare riferimento al manuale del pannello di controllo per completare il test di copertura.
    -   Quando sei soddisfatto che la telecamera PIR funzioni nella posizione scelta, puoi procedere al montaggio.
-   _**Modifica l'area operativa della telecamera PIR**_
    -   Seguire le istruzioni di seguito per modificare l'area della telecamera PIR nel pannello di controllo
        1.  Utilizzare la funzione Modifica dispositivo del pannello per modificare l'impostazione dell'area della telecamera PIR.
        2.  Tenere premuto il pulsante funzione per 3 secondi sulla telecamera PIR per inviare un segnale al pannello, quindi rilasciare il pulsante quando il LED si accende. (Per il pannello alimentato a batteria, dopo aver tenuto premuto il pulsante funzione per 3 secondi, premere il pulsante funzione**Ancora**per un secondo per inviare un segnale.)

![](<.gitbook/assets/16 (1).jpeg>)![](<.gitbook/assets/17 (7).png>)

**Installazione**

![](<.gitbook/assets/18 (1).jpeg>)

-   _**Linee guida per l'installazione**_
    -   -   La telecamera PIR è progettata per essere montata su una superficie piana o in una situazione d'angolo con viti e tasselli di fissaggio forniti.
        -   La base è dotata di fori, dove la plastica è più sottile, per il montaggio. Due fori pretranciati servono per il fissaggio su superficie e una staffa di montaggio triangolare viene utilizzata per il fissaggio ad angolo.
        -   Il raggio di rilevamento arriva fino a 12 metri se la telecamera PIR è montata a 2 metri dal suolo.
        -   I modelli Pet-Immune offrono una portata tipica di PET IMMUNE di 7 metri se montati a 1,9-2 metri dal suolo. Se necessario, puoi regolare l'altezza della telecamera PIR in base alle dimensioni del tuo animale domestico per prestazioni immunitarie ottimali. Una posizione di installazione più alta fornirà uno spazio più ampio immune agli animali domestici, ma aumenterà anche l'angolo cieco sotto la telecamera PIR.
    -   Quando il VST-862 è montato con una staffa rotante, non avrà la normale area di rilevamento (come nel diagramma) o il tipico raggio d'azione per l'immunità agli animali domestici.

![](<.gitbook/assets/19 (1).jpeg>)

**Si consiglia di installare la telecamera PIR nelle seguenti posizioni**

-   Montare in un punto in cui gli animali non possano raggiungere l'area di rilevamento arrampicandosi su mobili o altri oggetti.
-   Non puntare il rilevatore verso le scale su cui gli animali possono salire.
-   In una posizione tale che un intruso normalmente si sposterebbe attraverso il campo visivo del PIR.
-   Tra 1,9 e 2 m dal suolo per le migliori prestazioni.
-   In un angolo per avere la visuale più ampia.
-   Dove il suo campo visivo non sarà ostruito, ad es. da tende, ornamenti, ecc.

3

-   **Limitazioni**

|  | Non installare all'aperto.                                                |  | Evitare ostacoli di grandi dimensioni nell'area di rilevamento. |
| - | ------------------------------------------------------------------------- | - | --------------------------------------------------------------- |
|   |                                                                           |   |                                                                 |
|  | Non installare il PIR completamente esposto                               |  | Evitare vapori o umidità elevata che potrebbero causare         |
|   | luce diretta.                                                             |   | condensazione.                                                  |
|   |                                                                           |   |                                                                 |
|  | Evitare di spostare oggetti nell'area di rilevamento, ad es.              |  | Evitare la luce riflessa da superfici luminose, ad es.          |
|   | tenda, attaccapanni ecc.                                                  |   | specchio, finestra.                                             |
|   |                                                                           |   |                                                                 |
|  | Evitare di installare il PIR in aree in cui sono presenti dispositivi     |  | Evitare superfici riflettenti nell'area di rilevamento.         |
|   | può causare un rapido cambiamento di temperatura nel                      |   | Le firme infrarosse riflesse possono portare a falsità          |
|   | area di rilevamento, ad esempio condizionatore d'aria, riscaldatori, ecc. |   | allarme.                                                        |
|   |                                                                           |   |                                                                 |

![](<.gitbook/assets/20 (7).png>)

-   **Assicurati di mantenere sempre la potenza del segnale RSSI fissa su "4".**

4

-   _**Montaggio della telecamera PIR**_
    -   Il PIR è progettato per essere montato su una superficie piana o in una situazione d'angolo con viti di fissaggio e tasselli forniti.
    -   Per il montaggio ad angolo, viene fornita una staffa triangolare per aggiungere la protezione antimanomissione posteriore. La staffa include anche due fori per il montaggio a parete.
        -   Per il montaggio su superficie, viene fornita una staffa rotante opzionale per consentire agli utenti di regolare il campo di rilevamento. Con la staffa rotante, il VST-862 può essere ruotato di 80 gradi in orizzontale e di 70 gradi in verticale per fornire una copertura ottimale.
        -   **Montaggio ad angolo:**
            1.  Sfondare i due fori sulla staffa triangolare.
            2.  Utilizzare i due fori come sagoma per praticare i fori sulla superficie dell'angolo.
            3.  Inserire i tasselli.
            4.  Avvita la staffa triangolare nei tasselli con i due bastoncini di puntamento in alto rivolti verso di te.
            5.  Montare la telecamera PIR sui ganci della staffa triangolare.
        -   **Montaggio su superficie:**
            1.  Aprire il coperchio allentando la vite del coperchio utilizzando un cacciavite Philips.
            2.  Attraversa i 2 fori della superficie al centro della base.
            3.  Utilizzare i fori come modello per praticare i fori sulla superficie.
            4.  Inserire i tasselli se si fissa su intonaco o mattoni.
            5.  Avvitare la base nei tasselli.
            6.  Montare il coperchio sulla base e serrare.
    -   **Montaggio su superficie con staffa rotante (articolo opzionale, venduto separatamente):**

La staffa rotante può essere montata a parete con le viti fornite.

-   -   -   -   1.  Avvitare la staffa rotante al muro.
                2.  Montare opportunamente i 3 ganci della staffa rotante nei 3 fori della base.
                3.  Ruotare la staffa per il campo di rilevamento corretto e serrare la vite di fissaggio.

5
