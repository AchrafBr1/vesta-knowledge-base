# VESTA044

-   Telecomando universale a infrarossi UPIC-5ZW
-   introduzione

UPIC5-ZW è un telecomando a infrarossi Z-Wave. È progettato per far funzionare i tuoi elettrodomestici trasmettendo il segnale IR. Il telecomando IR è in grado di apprendere il segnale IR trasmesso dal telecomando dell'apparecchio. Dopo aver appreso il segnale, è possibile controllare a distanza il telecomando IR tramite la rete Z-Wave per inviare il segnale all'apparecchio senza utilizzare manualmente il telecomando.

L'UPIC-5ZW è un dispositivo abilitato Z-Wave ed è completamente compatibile con qualsiasi rete abilitata Z-Wave.

Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. Sfruttando la rete mesh Z-Wave, i comandi possono essere indirizzati a destinazione tramite prodotti Z-Wave intermedi di "ascolto".

La serie di telecomandi a infrarossi UPIC5 Z-Wave comprende i seguenti modelli:

**UPIC5-ZW**Telecomando a infrarossi

**UPIC5-ZW-OTA**Telecomando a infrarossi con funzionalità di aggiornamento firmware Over-the-Air

-   Identificazione delle parti

**1. Occhio IR**

![](<.gitbook/assets/0 (10).jpeg>)

Trasmette il segnale IR agli apparecchi.

**2. Pulsante funzione/IR**

Premere il pulsante 3 volte entro 1,5 secondi per inviare un codice di apprendimento.

Tieni premuto il pulsante per 10 secondi per ripristinare le impostazioni di fabbrica.

Tenere premuto il pulsante per 3 secondi per accedere alla modalità di apprendimento IR.

Premere una volta il pulsante per trasmettere il segnale/uscire dalla modalità apprendimento IR.

**3. Z-WaveLED**

Lampeggia una volta: il telecomando IR sta trasmettendo un segnale

**4. LED indicatore IR**

Lampeggio lento – Telecomando IR in modalità apprendimento IR.

Il telecomando IR Quick Flash riceve il segnale IR in modalità di apprendimento o sta trasmettendo il segnale IR

Lampeggia ogni mezzo secondo: i dati IR vengono cancellati

Spento – Il telecomando IR sta memorizzando il segnale IR ricevuto in modalità di apprendimento.

– Il telecomando IR è in modalità inattiva.

**5. Ricevitore del segnale IR**

**6. Ponticello di potenza di trasmissione IR bassa (JP1)**

**Ponticello spento**

se il collegamento del ponticello viene rimosso o “**parcheggiato**"su un perno.

**Ponticello acceso**

Il collegamento del ponticello viene inserito collegando i due pin

![](<.gitbook/assets/1 (17).png>)![](<.gitbook/assets/2 (20).png>)

Jumper ON – Potenza di trasmissione IR impostata su Bassa.**(Impostazione di fabbrica)**

Ponticello OFF – Deselezionato.

**7. Ponticello di potenza di trasmissione IR elevata (JP2)**

**Ponticello spento**

se il collegamento del ponticello viene rimosso o “**parcheggiato**"su un perno.

**Ponticello acceso**

Il collegamento del ponticello viene inserito collegando i due pin

![](<.gitbook/assets/3 (19).png>)![](<.gitbook/assets/4 (18).png>)

Jumper ON – Potenza di trasmissione IR impostata su Alta.

Ponticello OFF – Deselezionato.

**NOTA IMPORTANTE: i ponticelli JP1 e JP2 NON POSSONO essere impostati su ON contemporaneamente**

**8. Set di microinterruttori 1**

Per impostare il tipo di apparecchio

**9. Set di microinterruttori 2**

Per apprendere e testare il segnale IR

**10. Vano batteria**

**11. Staffa rotazionale per montaggio a parete (opzionale)**

-   Caratteristiche
-   _Rilevamento batteria e batteria scarica_

Il telecomando IR utilizza due batterie al litio da 1,5 V come fonte di alimentazione. È dotato della funzione di rilevamento della batteria scarica. Quando viene rilevata una tensione della batteria bassa, il telecomando IR trasmetterà il segnale di batteria scarica al coordinatore nella rete Z-Wave.

Il telecomando IR riporterà la percentuale della batteria al pannello di controllo rispettivamente al 100%, 75%, 50%, 25%. Il telecomando IR può anche rilevare lo stato di batteria scarica. Quando viene rilevata una tensione della batteria bassa (25%), il segnale di batteria scarica verrà inviato al pannello di controllo insieme alla trasmissione regolare del segnale affinché il pannello di controllo possa visualizzare lo stato di conseguenza.

-   _Aggiunta di dispositivi (inclusione)_

Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o altre applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete.

-   Inserire le batterie per accendere il telecomando IR.
-   Inserisci il gateway Z-Wave o il pannello di controllo**Inclusione**O**Apprendimento**modalità (fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
-   Entro 1,5 secondi, premere il pulsante Funzione/IR 3 volte.
-   Fare riferimento al manuale operativo del gateway Z-Wave o del pannello di controllo per completare il processo di apprendimento.
-   Se il sensore è già stato**incluso**(appreso) in un altro gateway/pannello di controllo Z-Wave, o se non è possibile apprendere il sensore nell'attuale gateway/pannello di controllo Z-Wave, escluderlo prima (vedere_**Esclusione**_) prima di tentare di farlo**includere**nell'attuale gateway/pannello di controllo Z-Wave.
-   _Rimozione del dispositivo (esclusione)_

Il telecomando IR deve essere rimosso dalla rete Z-Wave esistente prima di essere incluso in un'altra. Sono disponibili due metodi per escludere un dispositivo:

**Modalità di esclusione**

-   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
-   Entro 1,5 secondi, premere il pulsante Funzione/IR 3 volte e il telecomando IR verrà rimosso dalla rete Z-Wave.

**Ripristino delle impostazioni di fabbrica**

_(Utilizzare il ripristino delle impostazioni di fabbrica solo quando il pannello di controllo/gateway di rete è mancante o inutilizzabile)._

-   Tenere premuto il pulsante Funzione/IR del telecomando IR per 10 secondi per ripristinare le impostazioni di fabbrica.

_**\\<NOTE>**_

-   Il ripristino delle impostazioni di fabbrica del telecomando IR lo ripristinerà alle impostazioni predefinite di fabbrica (esclusa dalla rete Z-Wave). Il gateway o il pannello di controllo Z-Wave manterrà comunque le impostazioni Z-Wave. Fare riferimento al manuale del gateway o del pannello di controllo su come rimuovere le impostazioni Z-Wave del telecomando IR.
-   _Modalità di sospensione Z-Wave_
-   Il telecomando IR entrerà in modalità sospensione Z-Wave (per risparmiare energia) dopo essersi attivato per un breve periodo di tempo (~10 secondi). Durante la modalità di sospensione Z-Wave, i gateway Z-Wave o i pannelli di controllo non sono in grado di inviare comandi al telecomando IR.
-   Apprendimento e test del segnale IR

Per utilizzare il telecomando IR per controllare il tuo elettrodomestico, il telecomando IR deve prima apprendere il segnale IR inviato dal telecomando dell'elettrodomestico. Seguire le istruzioni riportate di seguito per completare il processo di apprendimento.**Si prega di tenere il ricevitore IR lontano dalla luce diretta o dalla luce solare durante il processo di apprendimento per evitare interferenze.**

-   _**Apprendimento**_

**Passaggio 1. Accedere alla modalità apprendimento IR**

1.  Seguire le istruzioni in**Configurazione della rete Z-Wave**per unire il telecomando IR alla rete Z-Wave.
2.  Assicurarsi che tutti gli interruttori sul blocco DIP Switch siano impostati su**SPENTO**posizione.
3.  Tenere premuto il pulsante Funzione/IR per 3 secondi e rilasciarlo quando il LED IR inizia a lampeggiare.
4.  Il LED IR inizierà a lampeggiare lentamente per indicare che il telecomando IR sta entrando nella modalità di apprendimento IR.

SU

![](<.gitbook/assets/5 (4).jpeg>)

SPENTO

**Passaggio 2. Selezionare Tipo di apparecchio**

Il trasmettitore IR può apprendere fino a 5 set di segnali IR per 5 apparecchi diversi.

Prima di iniziare l'apprendimento, selezionare il numero dell'apparecchio con Dip Switch Set 1 prima di procedere all'apprendimento dei segnali. Il segnale IR appreso verrà assegnato al numero dell'apparecchio selezionato.

Selezionare il tipo di apparecchio in base alla seguente tabella Dip Switch Set 1. Per facilitare il riconoscimento e il funzionamento dal gateway/pannello di controllo Climax Z-Wave, a ciascun tipo di dispositivo è stato assegnato un nome visualizzato sull'interfaccia del pannello di controllo, ti consigliamo di apprendere i segnali IR in base ai tipi di apparecchi visualizzati.

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

1.  Per selezionare Segnale IR 1, far scorrere l'Interruttore 1 su ON e l'Interruttore 2-8 su OFF.
2.  Per selezionare il segnale IR 2, far scorrere l'interruttore 2 su ON e l'interruttore 3-8 su OFF, ignorare la posizione dell'interruttore 1.
3.  Selezionare il segnale IR desiderato regolando il dip switch. Suggeriamo di iniziare dal segnale IR 1 facendo scorrere l'interruttore 1 sulla posizione ON per selezionare il segnale IR 1.
4.  Puntare il telecomando IR dell'apparecchio nella direzione opposta al ricevitore IR per evitare che il ricevitore IR riceva segnali IR indesiderati.
5.  Regolare il telecomando IR sull'impostazione desiderata, quindi puntare il telecomando verso il ricevitore IR, quindi premere il pulsante del telecomando per trasmettere il segnale IR

**Esempio:**

1.  Per il telecomando del condizionatore d'aria, se si imposta il telecomando su "Modalità raffreddamento, 18°C, Velocità ventola automatica" e si spegne il telecomando, puntare il telecomando verso il ricevitore IR e premere "ON".

Il ricevitore IR apprenderà il segnale "Modalità raffreddamento, 18°C, velocità ventola automatica" per il condizionatore d'aria

1.  Per il telecomando del televisore, puntare il telecomando verso il ricevitore IR e premere ON/Off.

Il ricevitore IR apprenderà il segnale ON/OFF per il televisore.

1.  Se il segnale viene ricevuto con successo, il LED IR lampeggerà rapidamente, quindi si spegnerà per indicare che il telecomando IR sta memorizzando i dati del segnale IR, quindi lampeggerà di nuovo lentamente. Se hai inviato accidentalmente il segnale IR sbagliato, punta il telecomando per regolare l'impostazione, quindi puntalo verso il ricevitore IR per ritrasmettere nuovamente il segnale. Il nuovo segnale IR sovrascriverà quello vecchio.
2.  Al termine dell'apprendimento, modificare l'impostazione del dip switch per apprendere un altro segnale IR, ripetere la procedura da 2 a 4. Si consiglia di procedere dal segnale IR da 1 a 8 facendo scorrere il dip switch da 1 a 8 in posizione ON uno per uno
3.  Ripetere la procedura per apprendere un massimo di 8 segnali per ciascun tipo di apparecchio.
4.  È possibile regolare l'impostazione del set 2 del Dip Switch per selezionare un altro tipo di apparecchio.

**Passaggio 4. Uscire dalla modalità apprendimento IR**

1.  Dopo aver terminato l'apprendimento di tutti i segnali IR, premere una volta il pulsante Funzione/IR per uscire dalla modalità di apprendimento, quindi far scorrere tutti gli interruttori in posizione OFF.

-   _**Test**_

Dopo aver completato l'apprendimento dei segnali IR, seguire le istruzioni riportate di seguito per testare la trasmissione dei segnali IR.

1.  Non accedere alla modalità Apprendimento IR, regolare di conseguenza l'impostazione del Dip Switch per selezionare il tipo di apparecchio e il numero del segnale IR come appreso in precedenza.
2.  Premere una volta il pulsante Funzione/IR, il LED IR lampeggerà rapidamente per indicare che sta trasmettendo il segnale. Se non viene acquisito alcun segnale, il telecomando IR non invierà alcun segnale e il LED IR rimarrà spento.
3.  Ripetere la procedura da 1 a 2 per testare tutti i segnali IR appresi.
4.  Dopo aver completato tutte le impostazioni, far scorrere tutti gli interruttori in posizione OFF.

-   _**Cancellazione dei dati IR**_

Per rimuovere tutti i segnali IR appresi per un tipo di apparecchio, seguire le istruzioni di seguito:

1.  Batterie del telecomando per spegnere il telecomando IR.
2.  Selezionare il tipo di apparecchio che si desidera rimuovere utilizzando il set Dip Switch 1 secondo la tabella seguente

| Interruttore 1 | Interruttore 2 | Interruttore 3 | Interruttore 4 | Cambia 5 | Interruttore 6 | Selezione dell'apparecchio         |
| -------------- | -------------- | -------------- | -------------- | -------- | -------------- | ---------------------------------- |
| SU             | SPENTO         | SPENTO         | SPENTO         | SPENTO   | SPENTO         | **Tipo 1 (condizionatore d'aria)** |
| SPENTO         | SU             | SPENTO         | SPENTO         | SPENTO   | SPENTO         | **Tipo 2 (televisione)**           |
| SPENTO         | SPENTO         | SU             | SPENTO         | SPENTO   | SPENTO         | **Tipo 3 (audio domestico)**       |
| SPENTO         | SPENTO         | SPENTO         | SU             | SPENTO   | SPENTO         | **Tipo 4 (set top box)**           |
| SPENTO         | SPENTO         | SPENTO         | SPENTO         | SU       | SPENTO         | **Tipo 5 (Altri)**                 |

Far scorrere più di un interruttore su ON selezionerà più tipi di apparecchi,

**Esempio:**

1.  Far scorrere l'interruttore 1,2,3,4,5 su ON selezionerà tutti e 5 i tipi di apparecchi.
2.  Far scorrere gli interruttori 1 e 3 su ON per selezionare Aria condizionata e Audio domestico.
3.  Tenere premuto il pulsante Funzione/IR e inserire le batterie per accendere il trasmettitore IR, non rilasciare ancora il pulsante.
4.  Continuare a tenere premuti entrambi i pulsanti Funzione/IR finché il LED IR non si accende, quindi rilasciare il pulsante
5.  Il trasmettitore IR cancellerà il segnale IR memorizzato per i tipi di apparecchi selezionati, il LED IR lampeggerà continuamente.
6.  Far scorrere tutti gli interruttori in posizione OFF per tornare al funzionamento normale. Il LED IR si spegnerà.

-   Installazione

Il telecomando IR è progettato per essere montato a parete. Può essere montato avvitando direttamente il coperchio posteriore alla parete oppure installando prima la staffa di rotazione, quindi installando il corpo principale sulla staffa. Si prega di fare riferimento al**Copertura del segnale IR e selezione LED IR**sezione seguente per informazioni sulla trasmissione del segnale IR prima di selezionare la posizione di montaggio del telecomando IR.

-   _Montaggio del telecomando IR_

![](<.gitbook/assets/6 (7).jpeg>)

Il telecomando IR è progettato per essere montato a parete. Può essere montato avvitando direttamente il coperchio posteriore alla parete oppure installando prima la staffa di rotazione, quindi installando il corpo principale sulla staffa. L'IR Eye deve essere puntato verso l'elettrodomestico che si desidera controllare quando è installato il telecomando IR.

**NOTA: la staffa di rotazione non è inclusa nella spedizione standard ed è disponibile su richiesta.**

-   Montaggio diretto a parete:

La cover posteriore ha 4 fori, dove la plastica è più sottile, per il montaggio.

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

![](<.gitbook/assets/7 (6).jpeg>)

-   Operazione
-   _Controllo tramite gateway/pannello di controllo Z-Wave_

The IR Remote Control can be controlled via Climax Z-Wave Gateway/Control Panels remotely to transmit IR signal. Selecting the appliance type and IR signal number from the Control Panel will control the IR Remote Control to send IR signal accordingly.

**Esempio:**

1.  Selezionare "Funzione condizionatore d'aria 1" per controllare il telecomando IR per inviare il segnale IR 1 appreso nel tipo di apparecchio condizionatore d'aria.

-   _Copertura del segnale IR e selezione LED IR_

![](<.gitbook/assets/8 (3).jpeg>)

L'occhio IR del telecomando IR comprende 6 LED utilizzati per trasmettere segnali IR, con 1 LED centrale e 5 LED circostanti. I 5 LED circostanti sono posizionati ad un angolo di 45° rispetto alla scheda PCB.**Copertura del segnale LED:**

Ogni LED trasmette il segnale IR in una copertura a cono davanti al LED. Il LED centrale viene sempre utilizzato ad ogni trasmissione. È inoltre possibile selezionare 1 dei 5 LED circostanti per trasmettere il segnale per ciascun tipo di apparecchio utilizzando il gateway/pannello di controllo Climax Z-Wave.

**Esempio:**

1.  Se si seleziona il LED 1 per il condizionatore d'aria, il telecomando IR trasmetterà il segnale sia con il LED centrale che con il LED 1 quando trasmette un segnale IR di tipo apparecchio condizionatore d'aria.
2.  Se si seleziona il LED 3 per l'audio domestico, il telecomando IR trasmetterà il segnale sia con il LED centrale che con il LED 3 quando trasmette un segnale IR di tipo apparecchio Home Audio.

Quando si installa il telecomando IR, selezionare il LED IR utilizzato tramite il pannello di controllo in base alla posizione di montaggio del telecomando IR per consentire al trasmettitore IR di inviare il segnale a tutti gli elettrodomestici della casa. Fare riferimento al manuale del gateway/pannello di controllo Climax per ulteriori informazioni sull'impostazione e il controllo del telecomando IR.

Fare riferimento al diagramma seguente per la copertura del segnale IR:

![](<.gitbook/assets/9 (1).jpeg>)

-   _Potenza di trasmissione IR_

Utilizzare gli interruttori jumper (JP2 e JP3) per regolare la potenza di trasmissione del segnale IR. L'impostazione predefinita di fabbrica è impostata su Bassa potenza di trasmissione (JP1 ON). Impostando il ponticello su JP2 aumenterà la portata di trasmissione del segnale IR.

-   _Semplice comando di impostazione del controllo AV_

Il semplice comando AV control set viene utilizzato per controllare un dispositivo AV tramite il Pannello di controllo:

Classe di comando: COMANDO_CLASSE_SEMPLICE_DI_CONTROLLO_V1

Comando: SEMPLICE_DI_CONTROLLO_IMPOSTATO

Imposta i valori:

Codice articolo MSB: per il tipo di apparecchio, 01~05

ID articolo LSB: per dati segnale IR, 01~08

![](<.gitbook/assets/10 (2).png>)

**Informazioni sull'onda Z**

**Tipo di dispositivo:**Contatore di energia secondario

**Tipo di ruolo:**Segnalazione dello schiavo addormentato (RSS)

**Supporto/controllo della classe di comando**

**Supporto CC obbligatorio:**Associazione CC, v2

Associazione Gruppo Informazioni CC

Batteria CC

Dispositivo reimpostato localmente CC

CC specifico del produttore, v2

Configurazione CC,

Controllo AV semplice CC,

Versione CC, v2

Z-Wave Plus Informazioni CC, v2

Livello di potenza CC

Aggiornamento firmware CC, v2

-   _**Gruppi di Z-Wave (Associazione Command Class Versione 2)**_

Gruppo 1 per “LifeLine”:

Batteria CC (COMANDO_CLASSE_DI BASE)

Dispositivo reimpostato localmente CC
