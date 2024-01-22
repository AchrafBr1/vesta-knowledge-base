# VESTA188

**Telecomando universale a infrarossi UPIC-5ZBS**

**introduzione**

UPIC5-ZBS è un telecomando a infrarossi ZigBee. È progettato per far funzionare i tuoi elettrodomestici trasmettendo il segnale IR. Il telecomando IR è in grado di apprendere il segnale IR trasmesso dal telecomando dell'apparecchio. Dopo aver appreso il segnale, è possibile controllare in remoto il telecomando IR tramite la rete ZigBee per inviare il segnale all'apparecchio senza utilizzare manualmente il telecomando e supportare la funzionalità di aggiornamento del firmware Over-the-Air (OTA). Il telecomando IR utilizza la tecnologia ZigBee per la trasmissione del segnale wireless. ZigBee è un protocollo di comunicazione wireless affidabile che presenta un basso consumo energetico e un'elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

Il telecomando IR funge da dispositivo terminale nella rete ZigBee. Può essere incluso nella rete ZigBee per trasmettere il segnale al momento dell'attivazione, ma non può consentire a nessun altro dispositivo ZigBee di unirsi alla rete tramite il dispositivo stesso.

**Identificazione delle parti**

![](<.gitbook/assets/0 (76).jpeg>)

1.  **Occhio IR**

Trasmette il segnale IR agli apparecchi.

1.  **Pulsante ZigBee**
2.  **Pulsante IR**
3.  **ZigBeeLED**

Lampeggia due volte – Il telecomando IR si collega con successo alla rete ZigBee Lampeggia ogni 20 minuti – Il telecomando IR ha perso la connessione alla rete ZigBee corrente.

1.  **LED indicatore IR**

Lampeggio lento – Telecomando IR in modalità apprendimento IR.

Il telecomando IR Quick Flash riceve il segnale IR in modalità di apprendimento o sta trasmettendo il segnale IR

Lampeggia ogni mezzo secondo: i dati IR vengono cancellati

Spento – Il telecomando IR sta memorizzando il segnale IR ricevuto in modalità di apprendimento.

– Il telecomando IR è in modalità inattiva.

1.  **Ricevitore di segnali IR**
2.  **Ponticello di potenza di trasmissione IR bassa (JP1)**

![](<.gitbook/assets/1 (57).png>)

**Ponticello acceso****Ponticello spento**

![](<.gitbook/assets/2 (61).jpeg>)![](<.gitbook/assets/3 (54).jpeg>)

Il collegamento del ponticello viene inserito collegando i due pin

se il collegamento del ponticello viene rimosso o “**parcheggiato**" su un perno.

Jumper ON – Potenza di trasmissione IR impostata su Bassa.**(Impostazione di fabbrica)**Ponticello OFF – Deselezionato.

**8. Ponticello di potenza di trasmissione IR elevata (JP2)**

![](<.gitbook/assets/4 (52).jpeg>)

**Ponticello acceso****Ponticello spento**

![](<.gitbook/assets/5 (63).png>)

Il collegamento del ponticello viene inserito collegando i due pin

se il collegamento del ponticello viene rimosso o “**parcheggiato**" su un perno.

Jumper ON – Potenza di trasmissione IR impostata su Alta.

Ponticello OFF – Deselezionato.

**NOTA IMPORTANTE: i ponticelli JP1 e JP2 NON POSSONO essere impostati su ON contemporaneamente**

1.  **Set di microinterruttori 1**

Per impostare il tipo di apparecchio

1.  **Gruppo di microinterruttori 2**

Per apprendere e testare il segnale IR

1.  **Compartimento della batteria**
2.  **Staffa rotazionale per montaggio a parete (opzionale)**

1

**Caratteristiche**

-   _**Rilevamento batteria e batteria scarica**_

Il telecomando IR utilizza due batterie al litio da 1,5 V come fonte di alimentazione. È dotato della funzione di rilevamento della batteria scarica. Quando viene rilevata una tensione della batteria bassa, il telecomando IR trasmetterà il segnale di batteria scarica al coordinatore nella rete ZigBee.

-   _**Supervisione**_

Il telecomando IR trasmetterà un segnale di supervisione per segnalare regolarmente la sua condizione in base alle impostazioni dell'utente. L'intervallo predefinito in fabbrica è 30 minuti. L'utente può anche premere una volta il pulsante ZigBee per trasmettere manualmente un segnale di supervisione.

**Configurazione della rete ZigBee**

-   _**Linee guida per i dispositivi ZigBee**_

Il telecomando IR è un protocollo di comunicazione wireless affidabile, a basso consumo energetico e ad alta efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

A causa della struttura fondamentale della rete ZigBee, il dispositivo ZigBee cercherà e si unirà attivamente alla rete dopo l'accensione. Poiché l'esecuzione di un'attività durante la connessione alla rete può consumare energia, è necessario seguire le istruzioni per evitare di scaricare la batteria del dispositivo ZigBee.

-   Assicurarsi che il router/coordinatore di rete ZigBee sia acceso prima di inserire la batteria nel dispositivo ZigBee.
-   Assicurarsi che il router/coordinatore di rete ZigBee sia acceso e nel raggio d'azione mentre il dispositivo ZigBee è in uso.

\-Non rimuovere un dispositivo ZigBee dal router o dal coordinatore della rete ZigBee senza rimuovere la batteria dal dispositivo ZigBee.

-   _**Unirsi alla rete ZigBee**_

In quanto dispositivo ZigBee, il telecomando IR deve unirsi a una rete ZigBee per ricevere il comando dal coordinatore della rete ZigBee per trasmettere il segnale IR. Seguire i passaggi seguenti per connettere il telecomando IR alla rete ZigBee.

-   1.  Inserire le batterie per accendere il telecomando IR.
    2.  **P**remere e tenere premuto il pulsante ZigBee per 10 secondi, quindi rilasciarlo per connettersi alla rete. Assicurati che la funzione di autorizzazione all'accesso sul router o sul coordinatore della tua rete ZigBee sia abilitata.
    3.  Dopo l'accesso alla rete ZigBee, il telecomando IR verrà registrato automaticamente nel sistema di sicurezza della rete. Si prega di controllare il pannello di controllo del sistema di sicurezza o il CIE (apparecchiatura di controllo e indicazione) per confermare se l'adesione e la registrazione sono andate a buon fine.
    4.  Se il telecomando IR si connette con successo alla rete ZigBee, il LED ZigBee lampeggerà due volte per indicarlo.
    5.  Dopo l'accesso alla rete ZigBee, se il telecomando IR perde la connessione alla rete ZigBee corrente, l'indicatore LED ZigBee lampeggerà ogni 20 minuti. Controllare le condizioni della rete ZigBee e la portata del segnale del telecomando IR per correggere la situazione.
-   _**Rimozione del dispositivo dalla rete ZigBee (ripristino delle impostazioni di fabbrica)**_

Per rimuovere il dispositivo dall'attuale rete ZigBee, il telecomando IR deve essere impostato su Ripristino delle impostazioni di fabbrica per completare la rimozione del dispositivo. La funzione di ripristino delle impostazioni di fabbrica cancellerà il telecomando IR dalle informazioni sulle impostazioni memorizzate e richiederà al dispositivo di cercare una nuova rete ZigBee.

**Prima di rimuovere il dispositivo, assicurarsi che si trovi nel raggio d'azione del segnale della rete ZigBee corrente**

-   1.  Elimina il telecomando IR dalla centrale di controllo/CIE corrente.
    2.  Tieni premuto il pulsante funzione per 10 secondi, quindi rilascia il pulsante per ripristinare il dispositivo.
    3.  Al momento del ripristino, il telecomando IR cancellerà l'impostazione corrente della rete ZigBee e trasmetterà il segnale al coordinatore ZigBee per rimuoversi dalla rete ZigBee corrente. Quindi cercherà nuovamente attivamente la rete ZigBee disponibile e si unirà automaticamente alla rete.
-   _**Aggiornamento firmware OTA**_
-   Il dispositivo supporta la funzionalità di aggiornamento del firmware OTA tramite la rete ZigBee, che può essere avviata dal coordinatore della rete ZigBee.
-   Seguire i passaggi seguenti per eseguire l'aggiornamento del firmware OTA.

1.  Devi accedere al tuo ZigBee Coordinator per eseguire l'aggiornamento del firmware in diretta.
2.  Nella pagina web di configurazione, seleziona il dispositivo che desideri aggiornare e seleziona il nuovo firmware ZigBee fornito. Fare riferimento al Manuale utente di ZigBee Coordinator per i dettagli.
3.  Premere OK per avviare il processo di aggiornamento, non eseguire altre azioni o spegnere il pannello.
4.  La durata di un aggiornamento richiederà circa 20-30 minuti. Tieni presente che la durata può variare in base alla dimensione del file o alla distanza tra l'accessorio e il coordinatore.
5.  Attendi il completamento dell'aggiornamento del firmware. Quando l'avanzamento raggiunge il 100%, il dispositivo si ripristinerà automaticamente. È inoltre possibile aggiornare nuovamente la pagina Web per assicurarsi che il firmware del dispositivo venga aggiornato correttamente con la versione più recente visualizzata.

2

**Apprendimento e test del segnale IR**

Per utilizzare il telecomando IR per controllare il tuo elettrodomestico, il telecomando IR deve prima apprendere il segnale IR inviato dal telecomando dell'elettrodomestico. Seguire le istruzioni riportate di seguito per completare il processo di apprendimento.

**Si prega di tenere il ricevitore IR lontano dalla luce diretta o dalla luce solare durante il processo di apprendimento per evitare interferenze.**

-   _**Apprendimento**_

**Passaggio 1. Accedere alla modalità apprendimento IR**

1.  Seguire le istruzioni in**Configurazione della rete ZigBee**per unire il telecomando IR alla tua rete ZigBee.
2.  Assicurarsi che tutti gli interruttori sul blocco DIP Switch siano impostati su**SPENTO**posizione.
3.  Tenere premuto il pulsante IR per 10 secondi e rilasciarlo quando il LED IR inizia a lampeggiare.
4.  Il LED IR inizierà a lampeggiare lentamente per indicare che il telecomando IR è attivo

![](<.gitbook/assets/6 (44).png>)

| sto entrando in modalità apprendimento IR.       | SU     |   |
| ------------------------------------------------ | ------ | - |
| **Passaggio 2. Selezionare Tipo di apparecchio** | SPENTO |   |
|                                                  |        |   |

Il trasmettitore IR può apprendere fino a 5 set di segnali IR per 5 apparecchi diversi.

Prima di iniziare l'apprendimento, selezionare il numero dell'apparecchio con Dip Switch Set 1 prima di procedere all'apprendimento dei segnali. Il segnale IR appreso verrà assegnato al numero dell'apparecchio selezionato.

Selezionare il tipo di apparecchio in base alla seguente tabella Dip Switch Set 1. Per facilitare il riconoscimento e il funzionamento dal pannello di controllo Climax ZigBee, a ciascun tipo di dispositivo è stato assegnato un nome visualizzato sull'interfaccia del pannello di controllo, ti suggeriamo di apprendere i segnali IR in base ai tipi di apparecchi visualizzati.

| Interruttore 1 | Interruttore 2 | Interruttore 3 | Interruttore 4 | Cambia 5 | Interruttore 6 | Tipo di apparecchio                |
| -------------- | -------------- | -------------- | -------------- | -------- | -------------- | ---------------------------------- |
| SU             | SPENTO         | SPENTO         | SPENTO         | SPENTO   | SPENTO         | **Tipo 1 (condizionatore d'aria)** |
| X              | SU             | SPENTO         | SPENTO         | SPENTO   | SPENTO         | **Tipo 2 (televisione)**           |
| X              | X              | SU             | SPENTO         | SPENTO   | SPENTO         | **Tipo 3 (audio domestico)**       |
| X              | X              | X              | SU             | SPENTO   | SPENTO         | **Tipo 4 (set top box)**           |
| X              | X              | X              | X              | SU       | SPENTO         | **Tipo 5 (Altri)**                 |

"X" significa che la posizione di questo interruttore non ha alcun effetto sulla selezione dell'apparecchio.

**Esempio:**

1.  Per selezionare il condizionatore d'aria, far scorrere l'interruttore 1 su ON e l'interruttore 2-6 su OFF.
2.  Per selezionare Televisione, far scorrere l'Interruttore 2 su ON e l'Interruttore 3-6 su OFF, ignorare la posizione dell'Interruttore 1.

**Passaggio 3. Apprendi i dati IR**

Ogni tipo di apparecchio può apprendere fino a 8 segnali IR, selezionati con Dip Switch Set 2.

| Interruttore 1 | Interruttore 2 | Interruttore 3 | Interruttore 4 | Cambia 5 | Interruttore 6 | Cambia 7 | Interruttore 8 | Segnale IR |
| -------------- | -------------- | -------------- | -------------- | -------- | -------------- | -------- | -------------- | ---------- |
| SU             | SPENTO         | SPENTO         | SPENTO         | SPENTO   | SPENTO         | SPENTO   | SPENTO         | **1**      |
| X              | SU             | SPENTO         | SPENTO         | SPENTO   | SPENTO         | SPENTO   | SPENTO         | **2**      |
| X              | X              | SU             | SPENTO         | SPENTO   | SPENTO         | SPENTO   | SPENTO         | **3**      |
| X              | X              | X              | SU             | SPENTO   | SPENTO         | SPENTO   | SPENTO         | **4**      |
| X              | X              | X              | X              | SU       | SPENTO         | SPENTO   | SPENTO         | **5**      |
| X              | X              | X              | X              | X        | SU             | SPENTO   | SPENTO         | **6**      |
| X              | X              | X              | X              | X        | X              | SU       | SPENTO         | **7**      |
| X              | X              | X              | X              | X        | X              | X        | SU             | **8**      |

**Esempio:**

-   1.  Per selezionare Segnale IR 1, far scorrere l'Interruttore 1 su ON e l'Interruttore 2-8 su OFF.
    2.  Per selezionare il segnale IR 2, far scorrere l'interruttore 2 su ON e l'interruttore 3-8 su OFF, ignorare la posizione dell'interruttore 1.

1.  Selezionare il segnale IR desiderato regolando il dip switch. Suggeriamo di iniziare dal segnale IR 1 facendo scorrere l'interruttore 1 sulla posizione ON per selezionare il segnale IR 1.
2.  Puntare il telecomando IR dell'apparecchio nella direzione opposta al ricevitore IR per evitare l'IR

Il ricevitore non riceve segnali IR indesiderati.

1.  Regolare il telecomando IR sull'impostazione desiderata, quindi puntare il telecomando verso il ricevitore IR, quindi premere il pulsante del telecomando per trasmettere il segnale IR

**Esempio:**

-   1.  Per il telecomando del condizionatore d'aria, se si imposta il telecomando su "Modalità raffreddamento, 18°C, Velocità ventola automatica" e si spegne il telecomando, puntare il telecomando verso il ricevitore IR e premere "ON".

Il ricevitore IR apprenderà il segnale "Modalità raffreddamento, 18°C, velocità ventola automatica" per il condizionatore d'aria

-   1.  Per il telecomando del televisore, puntare il telecomando verso il ricevitore IR e premere ON/Off. Il ricevitore IR apprenderà il segnale ON/OFF per il televisore.

1.  Se il segnale viene ricevuto con successo, il LED IR lampeggerà rapidamente, quindi si spegnerà per indicare che il telecomando IR sta memorizzando i dati del segnale IR, quindi lampeggerà di nuovo lentamente. Se hai inviato accidentalmente il segnale IR sbagliato, punta il telecomando per regolare l'impostazione, quindi puntalo verso il ricevitore IR per ritrasmettere nuovamente il segnale. Il nuovo segnale IR sovrascriverà quello vecchio.
2.  Al termine dell'apprendimento, modificare l'impostazione del dip switch per apprendere un altro segnale IR, ripetere la procedura da 2 a 4. Si consiglia di procedere dal segnale IR da 1 a 8 facendo scorrere il dip switch da 1 a 8 in posizione ON uno per uno
3.  Ripetere la procedura per apprendere un massimo di 8 segnali per ciascun tipo di apparecchio.

3

-   1.  È possibile regolare l'impostazione del set 2 del Dip Switch per selezionare un altro tipo di apparecchio.

**Passaggio 4. Uscire dalla modalità apprendimento IR**

-   1.  Dopo aver terminato l'apprendimento di tutti i segnali IR, premere una volta il pulsante IR per uscire dalla modalità di apprendimento, quindi far scorrere tutti gli interruttori in posizione OFF.
-   _**Test**_

Dopo aver completato l'apprendimento dei segnali IR, seguire le istruzioni riportate di seguito per testare la trasmissione dei segnali IR.

-   1.  Non accedere alla modalità Apprendimento IR, regolare di conseguenza l'impostazione del Dip Switch per selezionare il tipo di apparecchio e il numero del segnale IR come appreso in precedenza.
    2.  Premere una volta il pulsante IR, il LED IR lampeggerà rapidamente per indicare che sta trasmettendo il segnale. Se non viene acquisito alcun segnale, il telecomando IR non invierà alcun segnale e il LED IR rimarrà spento.
    3.  Ripetere la procedura da 1 a 2 per testare tutti i segnali IR appresi.
    4.  Dopo aver completato tutte le impostazioni, far scorrere tutti gli interruttori in posizione OFF.
-   _**Cancellazione dei dati IR**_

Per rimuovere tutti i segnali IR appresi per un tipo di apparecchio, seguire le istruzioni di seguito:

1.  Rimuovere le batterie per spegnere il telecomando IR.
2.  Selezionare il tipo di apparecchio che si desidera rimuovere utilizzando il set Dip Switch 1 secondo la tabella seguente

| Interruttore 1 | Interruttore 2 | Interruttore 3 | Interruttore 4 | Cambia 5 | Interruttore 6 | Selezione dell'apparecchio         |                       |
| -------------- | -------------- | -------------- | -------------- | -------- | -------------- | ---------------------------------- | --------------------- |
| SU             | SPENTO         | SPENTO         | SPENTO         | SPENTO   | SPENTO         | **Tipo 1 (condizionatore d'aria)** |                       |
| SPENTO         | SU             | SPENTO         | SPENTO         | SPENTO   | SPENTO         | **Tipo 2**                         | **(Televisione)**     |
| SPENTO         | SPENTO         | SU             | SPENTO         | SPENTO   | SPENTO         | **Tipo 3**                         | **(Audio domestico)** |
| SPENTO         | SPENTO         | SPENTO         | SU             | SPENTO   | SPENTO         | **Digitare 4**                     | **(Set-Top Box)**     |
| SPENTO         | SPENTO         | SPENTO         | SPENTO         | SU       | SPENTO         | **Digitare 5**                     | **(Altri)**           |

Far scorrere più di un interruttore su ON selezionerà più tipi di apparecchi,

**Esempio:**

-   1.  Far scorrere l'interruttore 1,2,3,4,5 su ON selezionerà tutti e 5 i tipi di apparecchi.
    2.  Far scorrere gli interruttori 1 e 3 su ON per selezionare Aria condizionata e Audio domestico.

1.  Tieni premuti entrambi i pulsanti IR e ZigBee e inserisci le batterie per accendere il trasmettitore IR, non rilasciare ancora i pulsanti.
2.  Continua a tenere premuti entrambi i pulsanti IR e ZigBee finché il LED IR non si accende, quindi rilascia i pulsanti
3.  Il trasmettitore IR cancellerà il segnale IR memorizzato per i tipi di apparecchi selezionati, il LED IR lampeggerà continuamente.
4.  Far scorrere tutti gli interruttori in posizione OFF per tornare al funzionamento normale. Il LED IR si spegnerà.

**Installazione**

Il telecomando IR è progettato per essere montato a parete. Può essere montato avvitando direttamente il coperchio posteriore alla parete oppure installando prima la staffa di rotazione, quindi installando il corpo principale sulla staffa. Si prega di fare riferimento al**Copertura del segnale IR e selezione LED IR**sezione seguente per informazioni sulla trasmissione del segnale IR prima di selezionare la posizione di montaggio del telecomando IR.

-   _**Montaggio del telecomando IR**_

![](<.gitbook/assets/7 (40).jpeg>)

Il telecomando IR è progettato per essere montato a parete. Può essere montato avvitando direttamente il coperchio posteriore alla parete oppure installando prima la staffa di rotazione, quindi installando il corpo principale sulla staffa. L'IR Eye deve essere puntato verso l'elettrodomestico che si desidera controllare quando è installato il telecomando IR.

**NOTA: la staffa di rotazione non è inclusa nella spedizione standard ed è disponibile su richiesta.**

-   Montaggio diretto a parete:

1.  Apri il coperchio e sfonda i 4 fori sul retro della copertina.
2.  Utilizzare i fori come sagoma per praticare i fori nel muro, inserire i tasselli se necessario.
3.  Avvitare il coperchio posteriore al muro.
4.  Sostituire la copertura anteriore con la copertura posteriore.

-   Montaggio su staffa rotazionale.

La staffa rotante è dotata di una testa regolabile che può essere fissata al telecomando IR. Dopo aver installato la staffa sulla parete, l'utente può regolare l'angolazione della testa per cambiare la direzione in cui è rivolto il telecomando IR.

1.  La base della staffa rotante ha 2 fori di montaggio. Utilizzare i fori come modello per praticare fori nel muro, inserire i tasselli se necessario.
2.  Avvitare la staffa al muro.
3.  Agganciare il telecomando IR alle staffe utilizzando i fori sul retro.
4.  Dopo aver completato l'installazione, è possibile utilizzare un cacciavite Philip per allentare la vite sulla parte superiore della staffa, quindi regolare l'angolazione del trasmettitore IR e serrare la vite per bloccare l'angolazione della staffa.

4

![](<.gitbook/assets/8 (35).jpeg>)

**Operazione**

-   _**Control via ZigBee Control Panel**_

Il telecomando IR può essere controllato in remoto tramite i pannelli di controllo Climax ZigBee per trasmettere il segnale IR. Selezionando il tipo di apparecchio e il numero del segnale IR dal pannello di controllo si controllerà il telecomando IR per inviare il segnale IR di conseguenza.

**Esempio:**

-   1.  Selezionare "Funzione condizionatore d'aria 1" controllerà il telecomando IR per inviare il segnale IR 1 appreso in Air

Tipo di apparecchio condizionatore.

-   _**Copertura del segnale IR e selezione LED IR**_

![](<.gitbook/assets/9 (27).jpeg>)

L'occhio IR del telecomando IR comprende 6 LED utilizzati per trasmettere segnali IR, con 1 LED centrale e 5 LED circostanti. I 5 LED circostanti sono posizionati ad un angolo di 45° rispetto alla scheda PCB.**Copertura del segnale LED:**

Ogni LED trasmette il segnale IR in una copertura a cono davanti al LED. I LED possono essere selezionati per trasmettere il segnale per ciascun tipo di apparecchio utilizzando il gateway.

**Esempio:**

UN. Se si seleziona LED 1 per il condizionatore d'aria, il telecomando IR trasmetterà il segnale con il LED 1 quando trasmette un segnale IR di tipo apparecchio condizionatore d'aria.

1.  Se si seleziona LED 2 e LED 3 per Home Audio, il telecomando IR trasmetterà il segnale sia con il LED 2 che con il LED 3 quando trasmette un segnale IR di tipo apparecchio Home Audio.

Quando si installa il telecomando IR, selezionare il LED IR utilizzato tramite il pannello di controllo in base alla posizione di montaggio del telecomando IR per consentire al trasmettitore IR di inviare il segnale a tutti gli elettrodomestici della casa. Fare riferimento al manuale del pannello di controllo Climax per ulteriori informazioni sull'impostazione e il controllo del telecomando IR.

Fare riferimento al diagramma seguente per la copertura del segnale IR:

5

![](<.gitbook/assets/10 (20).jpeg>)

-   _**Potenza di trasmissione IR**_

Utilizzare gli interruttori jumper (JP2 e JP3) per regolare la potenza di trasmissione del segnale IR. L'impostazione predefinita di fabbrica è impostata su Bassa potenza di trasmissione (JP1 ON). Impostando il ponticello su JP2 aumenterà la portata di trasmissione del segnale IR.

6

**Appendice (solo per sviluppatori)**

_**ID del cluster UPIC**_

**ID dispositivo: UPIC 0x0307 (proprietario)**

**Punto finale: 0x01**

| **Lato server** |                  | **Dalla parte del cliente** |
| --------------- | ---------------- | --------------------------- |
|                 |                  |                             |
|                 | **Obbligatorio** |                             |

Di base (0x0000)

CFG potenza (0x0001)

Identificare (0x0003)

Termostato HVAC (0x0201)

Identificare (0x0003)

**Opzionale**

_Nessuno_

_Nessuno_

-   _**Attributo delle informazioni di base del cluster**_

| **Identificatore** | **Nome**                      | **Tipo**          | **Allineare** | **Accesso** | **Predefinito**        | **Obbligatorio** |   |
| ------------------ | ----------------------------- | ----------------- | ------------- | ----------- | ---------------------- | ---------------- | - |
| **/ Facoltativo**  |                               |                   |               |             |                        |                  |   |
|                    |                               |                   |               |             |                        |                  |   |
| 0x0000             | _Versione ZCL_                | 8 bit senza segno | 0x00 –0xff    | Leggere     | 0x01                   | M                |   |
| numero intero      | soltanto                      |                   |               |             |                        |                  |   |
|                    |                               |                   |               |             |                        |                  |   |
| 0x0001             | Versione dell'applicazione    | 8 bit senza segno | 0x00 –0xff    | Leggere     | 0x00                   | O                |   |
| numero intero      | soltanto                      |                   |               |             |                        |                  |   |
|                    |                               |                   |               |             |                        |                  |   |
| 0x0003             | _Versione HW_                 | 8 bit senza segno | 0x00 –0xff    | Leggere     | 0                      | O                |   |
| numero intero      | soltanto                      |                   |               |             |                        |                  |   |
|                    |                               |                   |               |             |                        |                  |   |
| 0x0004             | _Nome del produttore_         | Carattere         | 0 – 32 byte   | Leggere     | Climax                 | O                |   |
| Corda              | soltanto                      | Tecnologia        |               |             |                        |                  |   |
|                    |                               |                   |               |             |                        |                  |   |
| 0x0005             | _Identificatore del modello_  | Carattere         | 0 – 32 byte   | Leggere     | (Versione del modello) | O                |   |
| Corda              | soltanto                      |                   |               |             |                        |                  |   |
|                    |                               |                   |               |             |                        |                  |   |
| 0x0006             | _DataCodice_                  | Carattere         | 0 – 16 byte   | Leggere     |                        | O                |   |
| Corda              | soltanto                      |                   |               |             |                        |                  |   |
|                    |                               |                   |               |             |                        |                  |   |
| 0x0007             | _Fonte di potere_             | 8 bit             | 0x00 –0xff    | Leggere     |                        | M                |   |
| soltanto           |                               |                   |               |             |                        |                  |   |
|                    |                               |                   |               |             |                        |                  |   |
| 0x0010             | _Descrizione della posizione_ | Carattere         | 0 – 32 byte   | Leggere /   |                        | O                |   |
| Corda              | Scrivere                      |                   |               |             |                        |                  |   |
|                    |                               |                   |               |             |                        |                  |   |
| 0x0011             | _Ambiente fisico_             | 8 bit             | 0x00 –0xff    | Leggere /   | 0x00                   | O                |   |
| Scrivere           |                               |                   |               |             |                        |                  |   |
|                    |                               |                   |               |             |                        |                  |   |
| 0x0012             | _Dispositivo abilitato_       | Booleano          | 0x00 –0x01    | Leggere /   | 0x01                   | M                |   |
| Scrivere           |                               |                   |               |             |                        |                  |   |
|                    |                               |                   |               |             |                        |                  |   |

_**Attributo delle informazioni sul cluster Power CFG**_

| **Identificatore** | **Nome**               | **Tipo**             | **Allineare** | **Accesso**  | **Predefinito** | **Obbligatorio** |   |
| ------------------ | ---------------------- | -------------------- | ------------- | ------------ | --------------- | ---------------- | - |
| **/ Facoltativo**  |                        |                      |               |              |                 |                  |   |
|                    |                        |                      |               |              |                 |                  |   |
| 0x0035             | _MASCHERA ALLARME BAT_ | Enumerazione a 8 bit | Tutto         | Sola lettura | 0x00            | M                |   |

_**Attributo di Identificazione delle informazioni sul cluster**_

| **Identificatore** | **Nome**                | **Tipo**             | **Allineare** | **Accesso**      | **Predefinito** | **Obbligatorio** |   |
| ------------------ | ----------------------- | -------------------- | ------------- | ---------------- | --------------- | ---------------- | - |
| **/ Facoltativo**  |                         |                      |               |                  |                 |                  |   |
|                    |                         |                      |               |                  |                 |                  |   |
| 0x0000             | _Identificare il tempo_ | Senza segno a 16 bit | 0x00 –0xffff  | Leggere scrivere | 0x0000          | M                |   |
| numero intero      |                         |                      |               |                  |                 |                  |   |
|                    |                         |                      |               |                  |                 |                  |   |

_**Attributo delle informazioni sul gruppo termostati**_

| **Identificatore** | **Nome**               | **Tipo** | **Allineare**  | **Accesso**      | **Predefinito** | **Obbligatorio** |   |
| ------------------ | ---------------------- | -------- | -------------- | ---------------- | --------------- | ---------------- | - |
| **/ Facoltativo**  |                        |          |                |                  |                 |                  |   |
|                    |                        |          |                |                  |                 |                  |   |
| 0x001C             | _Modalità di sistema_  | 8 bit    | Tutto          | Leggere scrivere | 0x04            | M                |   |
| Enumerazione       |                        |          |                |                  |                 |                  |   |
|                    |                        |          |                |                  |                 |                  |   |
| 0x1011             | _Selezionare invia IR_ | UINT 40  | 0CSAAFFFFFFFF- | Leggere scrivere | 0x2020202020    | O                |   |
| _GUIDATO_          | 0x0101010101           |          |                |                  |                 |                  |   |
|                    |                        |          |                |                  |                 |                  |   |

**Modalità di sistema (0x001C):**

Questo attributo determina quale segnale IR trasmettere quando l'UPIC riceve il comando dalla centrale, in base a quanto appreso in Tipo e funzione del segnale IR.

L'UPIC può apprendere fino a 5 set di tipi IR, 8 segnali per ciascun tipo. Quando si trasmette il segnale, il segnale IR deve essere

specificato con questo attributo.

Il formato è 0x_**XY**_

7

X = Tipo di apparecchio (1~5)

Y = Numero segnale IR (1~8)

Ad esempio, se l'UPIC ha appreso un segnale IR sul Tipo di apparecchio 1, segnale IR 8, la centrale dovrebbe inviare un comando con l'impostazione dell'attributo 0x_**18**_affinché UPIC trasmetta questo segnale.

**Selezionare Invia LED IR (0x1011):**

L'UPIC può controllare fino a 5 tipologie di apparecchi (Tipo 1~5) con i suoi 6 LED IR. Può essere configurato per inviare segnali IR con diversi LED utilizzando questo attributo.

Il formato deve essere letto come segue, utilizzando come esempio il valore predefinito 0x2020202020

| 0x20                     | 0x20                     | 0x20                     | 0x20                     | 0x20                     |
| ------------------------ | ------------------------ | ------------------------ | ------------------------ | ------------------------ |
|                          |                          |                          |                          |                          |
| LED IR da utilizzare con | LED IR da utilizzare con | LED IR da utilizzare con | LED IR da utilizzare con | LED IR da utilizzare con |
| Tipo di apparecchio 1    | Tipo di apparecchio 2    | Tipo di apparecchio 3    | Tipo di apparecchio 4    | Tipo di apparecchio 5    |
|                          |                          |                          |                          |                          |

Per ogni valore del tipo di apparecchio, il valore deve essere letto in Bit0~5, nel seguente formato:

| Valore          | In        |               |      | 2    |              |              |               | 0            |      |              |              |
| --------------- | --------- | ------------- | ---- | ---- | ------------ | ------------ | ------------- | ------------ | ---- | ------------ | ------------ |
| Esadecimale     |           |               |      |      |              |              |               |              |      |              |              |
| terra d'ombra   |           |               |      |      |              |              |               |              |      |              |              |
|                 |           |               |      |      |              |              |               |              |      |              |              |
| BITNumero       |           | Sta arrivando | BIT6 |      | Comunque     | BIT4         | l'ho comprato | Beta         |      | BIT1         | BIT0         |
|                 |           |               |      |      |              |              |               |              |      |              |              |
| Valore dentro   | Morso     | 0             | 0    |      | 1            | 0            | 0             | 0            |      | 0            | 0            |
| numero          |           |               |      |      |              |              |               |              |      |              |              |
|                 |           |               |      |      |              |              |               |              |      |              |              |
| Numero LED a    | Riservato | Riservato     |      | LED6 | LED5         | LED4         | LED3          |              | LED2 | LED1         |              |
| essere attivato |           |               |      |      | 1=abilita    | 1=abilita    | 1=abilita     | 1=abilita    |      | 1=abilita    | 1=abilita    |
|                 |           |               |      |      | 0=disabilita | 0=disabilita | 0=disabilita  | 0=disabilita |      | 0=disabilita | 0=disabilita |
|                 |           |               |      |      |              |              |               |              |      |              |              |

Ad esempio: 0x20 = 0010 0000 nel numero di bit, il che significa che solo il LED 6 (il LED centrale) verrà attivato quando l'UPIC trasmette il segnale IR in questo tipo di apparecchio.

Se si desidera impostare il segnale IR da trasmettere sia con il LED 2 che con il LED 6, il valore in numero di bit sarà 0010 0010 = 0x22

| 0         | 0         | 1         | 0           |
| --------- | --------- | --------- | ----------- |
|           |           |           |             |
| Riservato | Riservato | LED6      | LED5        |
|           |           | Abilitare | disattivare |
|           |           |           |             |

| 0           | 0           | 1         | 0           |
| ----------- | ----------- | --------- | ----------- |
|             |             |           |             |
| LED4        | LED3        | LED2      | LED1        |
| disattivare | disattivare | Abilitare | disattivare |
|             |             |           |             |

0010 0010 in Numero bit = 0x22 in Numero esadecimale, se si desidera applicare questa impostazione solo al Tipo di apparecchio 1 e lasciare invariato l'altro tipo di apparecchio, l'impostazione dell'attributo finale sarà: 0x**22**20202020

| 0x22                    | 0x20                    | 0x20                    | 0x20                    | 0x20                    |
| ----------------------- | ----------------------- | ----------------------- | ----------------------- | ----------------------- |
|                         |                         |                         |                         |                         |
| LED IR da utilizzare    | LED IR da utilizzare    | LED IR da utilizzare    | LED IR da utilizzare    | LED IR da utilizzare    |
| con apparecchio tipo 1, | con apparecchio tipo 2, | con apparecchio tipo 3, | con apparecchio tipo 4, | con apparecchio tipo 5, |
| LED 6 e 2               | LED6                    | LED6                    | LED6                    | LED6                    |
|                         |                         |                         |                         |                         |

È possibile utilizzare questo attributo per programmare quali LED devono essere attivati ​​per i diversi tipi di apparecchi IR_**NOTA IMPORTANTE:**_

Sebbene sia possibile impostare la trasmissione di più LED durante l'invio del segnale IR, impostarlo**NON PIÙ DI 2**LED da attivare. Il motivo di tale limitazione è che per ogni LED aggiuntivo attivato, il consumo energetico aumenterà notevolmente. Se si attivano più di 2 LED, la batteria si scaricherà in un tempo molto più breve di quello ideale.

8
