# VESTA189

**Termostato TMST-15-ZBS**

**introduzione**

TMST-15-ZBS è un termostato ZigBee alimentato a batteria. È progettato per essere incorporato nel sistema di riscaldamento e raffreddamento domestico per il controllo dell'ambiente domestico. Il termostato può essere azionato manualmente utilizzando lo schermo LCD e i pulsanti oppure accedendo in remoto tramite la rete ZigBee. È dotato di modalità di raffreddamento e riscaldamento con setpoint di temperatura e programmazione automatica per controllare facilmente l'ambiente domestico.

Il Termostato utilizza la tecnologia ZigBee per la trasmissione del segnale wireless. ZigBee è un protocollo di comunicazione wireless affidabile che presenta un basso consumo energetico e un'elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in rete una grande quantità di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali

Il termostato funge da dispositivo finale nella rete ZigBee. Può essere incluso nella rete ZigBee per trasmettere il segnale al momento dell'attivazione, ma non può consentire a nessun altro dispositivo ZigBee di unirsi alla rete.

**La serie TMST-15-ZBS ha i seguenti modelli:**

TMST-15-ZBS

tmst-15-zbs-outa

**Identificazione delle parti**

![](<.gitbook/assets/0 (77).jpeg>)

**1. Display LCD**

Il display LCD visualizza le seguenti informazioni:

![](<.gitbook/assets/1 (68).jpeg>)

1.  Icona modalità riscaldamento: quando visualizzata, il termostato è in modalità riscaldamento.
2.  Icona modalità Raffreddamento: quando visualizzata, il termostato è in modalità Raffreddamento.
3.  Icona batteria scarica: quando visualizzata, la tensione della batteria del termostato è bassa.
4.  Connettività di rete ZigBee:

L'icona viene visualizzata quando il Termostato non è ancora stato acquisito da alcun gateway/pannello o quando il dispositivo perde la connessione alla rete ZigBee corrente.

1.  Modalità: selezione modalità, modalità remota e offset
2.  Programmazione: il termostato eseguirà l'impostazione del programma programmato.
3.  Lettura/punto di regolazione della temperatura

**2. Pulsante Giù (-).**

Premere per diminuire il punto di regolazione

Tenere premuto per 3 secondi per accedere alla modalità di programmazione.

**3. Pulsante Su (+).**

Premere per aumentare il punto di regolazione.

Tenere premuto per 10 secondi per accedere alla modalità di apprendimento e sullo schermo LCD verrà visualizzato "Joi NET".

![](<.gitbook/assets/2 (62).jpeg>)

1.  **Foro per il montaggio a parete**
2.  **Compartimento della batteria**

Inserire 2 batterie alcaline AA.

**6. Terminali relè (rimuovere il coperchio relè per accedere)**

Morsetti relè 230V 5A NO/COM/NC.

Collegare al sistema di riscaldamento/raffreddamento domestico.

1

**Caratteristiche**

![](<.gitbook/assets/3 (55).jpeg>)

-   _**Rilevamento batteria e batteria scarica**_

Il termostato utilizza 2 batterie alcaline AA come fonte di alimentazione. Il termostato è dotato della funzione di rilevamento della batteria scarica. Quando la tensione della batteria è bassa, il termostato trasmetterà il segnale di batteria scarica al coordinatore nella rete ZigBee.

![](<.gitbook/assets/4 (53).jpeg>)

-   _**Controllo relè**_

Il termostato controlla il sistema di riscaldamento/raffreddamento domestico tramite il controllo del relè. Aprire e capovolgere il coperchio posteriore, rimuovere il coperchio interno sul relè per rivelare i terminali per il cablaggio. Quando si collega il termostato, collegare il cavo attraverso l'apertura centrale sul coperchio posteriore.

![](<.gitbook/assets/5 (64).png>)

-   _**Controllo della modalità**_

Il Termostato ha due modalità di funzionamento: modalità Locale e modalità Programmata.

![](<.gitbook/assets/6 (43).jpeg>)![](<.gitbook/assets/7 (41).jpeg>)

-   **Modalità locale:**

La modalità locale consente la regolazione della funzione Caldo/Freddo del termostato e dei punti di regolazione utilizzando i pulsanti del termostato.

-   **Modalità pianificata:**

![](<.gitbook/assets/8 (36).jpeg>)![](<.gitbook/assets/9 (28).jpeg>)

La modalità programmata consente la modalità Termostato e il controllo del setpoint tramite Gateway una volta completato l'apprendimento.

Per modificare la modalità operativa, fare riferimento a “_Modalità di programmazione_" per maggiori dettagli.

![](<.gitbook/assets/10 (39).png>)

-   _**Riscaldamento/Raffreddamento e controllo del setpoint**_

Il riscaldamento/raffreddamento del termostato e il setpoint possono essere regolati localmente solo quando il termostato è impostato sulla modalità locale.

In modalità locale, premere il tasto**SU**(**+**) O**Giù (-)**pulsante per regolare il setpoint.

In modalità programmata, utilizzare il gateway/pannello di controllo per regolare il setpoint da remoto.

Intervallo setpoint riscaldamento: 9°C~30°C.

Intervallo di setpoint freddo: 11°C~32°C

![](<.gitbook/assets/11 (30).png>)

-   _**Telecomando**_

Dopo che il termostato si è unito a una rete ZigBee, è possibile controllarlo tramite il coordinatore o il gateway della rete ZigBee. Per ulteriori informazioni, fare riferimento al manuale del coordinatore/gateway ZigBee.

Le seguenti funzioni sono disponibili solo per l'impostazione tramite coordinatore ZigBee e gateway:

![](<.gitbook/assets/12 (20).jpeg>)![](<.gitbook/assets/13 (25).jpeg>)

-   -   **Programma:**

È possibile programmare la configurazione del programma solo tramite il coordinatore/gateway di rete ZigBee.

Impostazione del programma: è possibile programmare fino a 5 programmi per ogni giorno della settimana con modalità, setpoint e ora di inizio. Controllo della pianificazione:

Normale: il termostato eseguirà di conseguenza l'impostazione del programma programmato.

Hold – Il Termostato ignorerà la programmazione attualmente programmata ed eseguirà la programmazione successiva quando inizia. Nessuna Programmazione – Il Termostato non eseguirà alcuna programmazione impostata finché non verrà impostato nuovamente su Normale.

-   _**Rilevamento della temperatura**_
    -   Il termostato è dotato di sensori di temperatura integrati e visualizzerà la lettura della temperatura sul display LCD.
    -   Il termostato trasmetterà regolarmente i segnali di temperatura in base all'impostazione. L'intervallo predefinito in fabbrica è 10 minuti.
    -   Quando la temperatura cambia di +/- 2°C, anche il Termostato trasmetterà un segnale.
    -   È inoltre possibile premere una volta il pulsante di rete ZigBee per trasmettere manualmente un segnale di temperatura.
-   _**Supervisione**_

![](<.gitbook/assets/14 (24).png>)![](<.gitbook/assets/15 (23).png>)

Il Termostato trasmetterà un segnale di supervisione ogni 10 minuti insieme alle informazioni sulla temperatura, sulla modalità corrente e sul setpoint per segnalare regolarmente la sua condizione.

2

-   ![](<.gitbook/assets/16 (25).png>)_**Modalità di programmazione**_

**Passo 1.**Premere e tenere premuto il pulsante Giù (-) per 3 secondi per accedere alla modalità di programmazione.

**Passo 2.**Sono disponibili 3 funzioni per la programmazione, comprese le funzioni del termostato, il controllo del relè remoto e l'offset del setpoint. È possibile premere il pulsante SU (+) o Giù (-) per cambiare modalità.

**Passaggio 3.**Dopo aver terminato la selezione, attendere alcuni secondi affinché il Termostato entri nella modalità selezionata.

**Funzioni del termostato (riscaldamento e raffreddamento):**

In questa modalità, sullo schermo LCD verrà visualizzato "Pro Mod".

![](<.gitbook/assets/17 (17).jpeg>)

È possibile selezionare le modalità di riscaldamento/raffreddamento. Premere il pulsante SU (+) per selezionare Riscaldamento e il pulsante Giù (-) per selezionare Raffreddamento.

Riscaldamento Raffreddamento

![](<.gitbook/assets/18 (12).jpeg>)

Dopo aver terminato la selezione, attendere alcuni secondi affinché il Termostato esca automaticamente dalla modalità di impostazione. Il Termostato entrerà nell'ultima modalità selezionata.

**Controllo del relè remoto:**

In questa modalità, sullo schermo LCD verrà visualizzato "Pro RM". La modalità remota consente di controllare il relè remoto tramite il pannello di controllo quando la funzione è abilitata. Il Termostato non controllerà il relè locale in Modalità Remota.

![](<.gitbook/assets/19 (26).png>)

-   Se la modalità remota è disabilitata, sullo schermo LCD verrà visualizzato "dS RM".
-   Se la modalità remota è abilitata, sullo schermo LCD verrà visualizzato "En RM".

![](<.gitbook/assets/20 (18).png>)

**Scostamento del setpoint:**

In questa modalità, sullo schermo LCD verrà visualizzato "Pro OFS". La funzione Setpoint Offset consente di compensare la deviazione. Per calcolare l'offset del setpoint, è sufficiente sottrarre la temperatura ambiente dalla temperatura del dispositivo. In modalità locale, tenere premuto il pulsante Giù (-) per 3 secondi per accedere alla modalità di programmazione. Dopo aver terminato la selezione, attendere alcuni secondi affinché il Termostato entri nella selezione della modalità.

Ad esempio: se la temperatura del dispositivo è 20°C e la temperatura ambiente è 18°C, l'offset del setpoint = 18 – 20 = -2°C.

Dopo aver applicato l'offset del setpoint, il dispositivo funzionerà in base alla temperatura regolata.

Ad esempio: se la lettura della temperatura del dispositivo è 20°C, l'offset del setpoint è -2°C, il dispositivo funzionerà utilizzando 18°C ​​come riferimento effettivo.

**Configurazione della rete ZigBee**

-   _**Linee guida per i dispositivi ZigBee**_

ZigBee è un protocollo di comunicazione wireless affidabile che presenta un basso consumo energetico e un'elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

A causa della struttura fondamentale della rete ZigBee, il dispositivo ZigBee cercherà e si unirà attivamente alla rete dopo l'accensione. Poiché l'esecuzione di un'attività durante la connessione alla rete può consumare energia, è necessario seguire le istruzioni per evitare di scaricare la batteria del dispositivo ZigBee

-   Assicurati che il router o il coordinatore della rete ZigBee sia acceso prima di inserire la batteria nel dispositivo ZigBee.
-   Assicurarsi che il router o il coordinatore della rete ZigBee sia acceso e nel raggio d'azione mentre è in uso un dispositivo ZigBee.
-   Non rimuovere un dispositivo ZigBee dal router o dal coordinatore della rete ZigBee senza rimuovere la batteria dal dispositivo ZigBee.

3

-   _**Unirsi alla rete ZigBee**_

Essendo un dispositivo ZigBee, il termostato deve unirsi a una rete ZigBee affinché l'utente possa controllarlo da remoto. Seguire i passaggi seguenti per connettere il termostato alla rete ZigBee.

-   1.  Rimuovere il coperchio posteriore del termostato e inserire 2 batterie alcaline AA per accendere il termostato.
    2.  Tieni premuto il pulsante della rete ZigBee per 10 secondi, quindi rilascialo per accedere alla rete ZigBee. Assicurati che la funzione di autorizzazione all'accesso sul router o sul coordinatore della tua rete ZigBee sia abilitata.
    3.  Attendere alcuni secondi affinché il Termostato si unisca alla rete ZigBee. Se il Termostato si connette con successo ad una rete, l'icona di connessione ZigBee scomparirà dal display LCD.
    4.  Dopo essersi unito alla rete ZigBee, il Termostato verrà registrato automaticamente nel sistema di sicurezza della rete. Si prega di controllare il pannello di controllo del sistema di sicurezza o il CIE (apparecchiatura di controllo e indicazione) per confermare se l'adesione e la registrazione sono andate a buon fine.
    5.  Dopo l'accesso alla rete ZigBee, se il Termostato perde la connessione alla rete ZigBee corrente, l'icona di connessione ZigBee apparirà dopo 10 minuti. Controllare le condizioni della rete ZigBee e la portata del segnale del termostato per correggere la situazione.
-   _**Rimozione del dispositivo dalla rete ZigBee (ripristino delle impostazioni di fabbrica)**_

Per rimuovere il termostato dall'attuale rete ZigBee o impostarlo sui valori predefiniti di fabbrica, seguire i passaggi seguenti:

**Rimuovere il termostato dall'attuale rete ZigBee:**

1.  Prima di rimuovere il dispositivo, assicurarsi che il termostato si trovi nel raggio d'azione del segnale della rete ZigBee corrente.
2.  Tenere premuto il pulsante SU (+) per 10 secondi, quindi rilasciare il pulsante.
3.  Il Termostato verrà rimosso dall'attuale rete ZigBee. Cercherà nuovamente attivamente la rete ZigBee disponibile e si unirà automaticamente alla rete.

**Impostare il termostato sui valori predefiniti di fabbrica:**

-   1.  Premere contemporaneamente i pulsanti SU (+) e Giù (-), quindi accendere il dispositivo.
    2.  Rilascia i pulsanti. Il termostato cancellerà le impostazioni memorizzate e ritornerà ai valori predefiniti di fabbrica.
-   _**Aggiornamento firmware OTA**_

Il termostato supporta la funzione di aggiornamento del firmware OTA tramite la rete ZigBee, che può essere avviata dal coordinatore della rete ZigBee.

Seguire i passaggi seguenti per eseguire l'aggiornamento del firmware OTA.

**Passo 1.**Devi accedere al tuo ZigBee Coordinator per eseguire l'aggiornamento del firmware in diretta.

**Passo 2.**Nella pagina web di configurazione, seleziona il dispositivo che desideri aggiornare e seleziona il nuovo firmware ZigBee fornito. Fare riferimento al Manuale utente di ZigBee Coordinator per i dettagli.

**Passaggio 3.**Premere "OK" per avviare il processo di aggiornamento e il LED continuerà a lampeggiare. Durante il processo OTA, non eseguire altre azioni o spegnere il pannello.

**Passaggio 4.**La durata di un aggiornamento richiederà circa 20-30 minuti. Tieni presente che la durata può variare in base alla dimensione del file o alla distanza tra l'accessorio e il coordinatore.

**Passaggio 5**.Attendere il completamento dell'aggiornamento del firmware. Quando l'avanzamento raggiunge il 100%, il dispositivo si ripristinerà automaticamente. È inoltre possibile aggiornare nuovamente la pagina Web per assicurarsi che il firmware del dispositivo venga aggiornato correttamente con la versione più recente visualizzata.

**Installazione**

Il termostato è progettato per essere montato a parete utilizzando i fori di montaggio sul coperchio posteriore.

1.  Prima del montaggio, assicurarsi di completare prima il cablaggio del relè attraverso l'apertura sul coperchio posteriore.
2.  Utilizzare i fori di montaggio sul coperchio posteriore come modello per contrassegnare la posizione di montaggio sulla parete.
3.  Praticare dei fori sulla parete e inserire i tasselli, se necessario, quindi avvitare il coperchio posteriore nella posizione di montaggio.
4.  Posizionare il corpo principale del termostato sul coperchio posteriore, l'installazione è completa.

**Appendice(Solo per sviluppatori.)**

-   _**ID del gruppo termostati**_

**ID dispositivo: ZCL_HA_ID DEL DISPOSITIVO_TERMOSTATO 0x0301**

**Punto finale: 0x01**

| **Lato server** |                  | **Dalla parte del cliente** |
| --------------- | ---------------- | --------------------------- |
|                 |                  |                             |
|                 | **Obbligatorio** |                             |

Di base (0x0000)

Configurazione alimentazione (0x0001)

Identificare (0x0003)

_Identificare (0x0003)_

_Acceso/Spento(0x0006)_

_Tempo(0x000A)_

4

TERMOSTATO HVAC (0x0201)

Diagnostica (0x0B05)

**Opzionale**

_**Attributo delle informazioni di base del cluster**_

| **Identificatore**                                                                 | **Nome**                      | **Tipo**          | **Allineare** | **Accesso**      | **Predefinito** | **Obbligatorio** |   |
| ---------------------------------------------------------------------------------- | ----------------------------- | ----------------- | ------------- | ---------------- | --------------- | ---------------- | - |
| **/ Facoltativo**                                                                  |                               |                   |               |                  |                 |                  |   |
|                                                                                    |                               |                   |               |                  |                 |                  |   |
| 0x0000                                                                             | _Versione ZCL_                | 8 bit senza segno | 0x00 –0xff    | Sola lettura     | 0x01            | M                |   |
| numero intero                                                                      |                               |                   |               |                  |                 |                  |   |
|                                                                                    |                               |                   |               |                  |                 |                  |   |
| 0x0001                                                                             | Versione dell'applicazione    | 8 bit senza segno | 0x00 –0xff    | Sola lettura     | 0x00            | O                |   |
| numero intero                                                                      |                               |                   |               |                  |                 |                  |   |
|                                                                                    |                               |                   |               |                  |                 |                  |   |
| 0x0003                                                                             | _Versione HW_                 | 8 bit senza segno | 0x00 –0xff    | Sola lettura     | 0               | O                |   |
| numero intero                                                                      |                               |                   |               |                  |                 |                  |   |
|                                                                                    |                               |                   |               |                  |                 |                  |   |
| 0x0004                                                                             | _Nome del produttore_         | Carattere         | 0 – 32 byte   | Sola lettura     | Climax          | O                |   |
| Corda                                                                              | Tecnologia                    |                   |               |                  |                 |                  |   |
|                                                                                    |                               |                   |               |                  |                 |                  |   |
| 0x0005                                                                             | _Identificatore del modello_  | Carattere         | 0 – 32 byte   | Sola lettura     | (Modello        | O                |   |
| Corda                                                                              | Versione)                     |                   |               |                  |                 |                  |   |
|                                                                                    |                               |                   |               |                  |                 |                  |   |
| 0x0006                                                                             | _DataCodice_                  | Carattere         | 0 – 16 byte   | Sola lettura     |                 | O                |   |
| Corda                                                                              |                               |                   |               |                  |                 |                  |   |
|                                                                                    |                               |                   |               |                  |                 |                  |   |
| 0x0007                                                                             | _Fonte di potere_             | 8 bit             | 0x00 –0xff    | Sola lettura     |                 | M                |   |
| 0x0010                                                                             | _Descrizione della posizione_ | Carattere         | 0 – 32 byte   | Leggere scrivere |                 | O                |   |
| Corda                                                                              |                               |                   |               |                  |                 |                  |   |
|                                                                                    |                               |                   |               |                  |                 |                  |   |
| 0x0011                                                                             | _Ambiente fisico_             | 8 bit             | 0x00 –0xff    | Leggere scrivere | 0x00            | O                |   |
| 0x0012                                                                             | _Dispositivo abilitato_       | Booleano          | 0x00 –0x01    | Leggere scrivere | 0x01            | O                |   |
| 0xFFFD                                                                             | _Revisione del cluster_       | uint16            | 0x0001-0xFFFE | Sola lettura     | 1               | M                |   |
| _**Attributo delle informazioni sul cluster di configurazione di alimentazione**_ |                               |                   |               |                  |                 |                  |   |

| **Identificatore**                                                 | **Nome**                    | **Tipo** | **Allineare** | **Accesso**      | **Predefinito** | **Obbligatorio** |   |
| ------------------------------------------------------------------ | --------------------------- | -------- | ------------- | ---------------- | --------------- | ---------------- | - |
| **/ Facoltativo**                                                  |                             |          |               |                  |                 |                  |   |
|                                                                    |                             |          |               |                  |                 |                  |   |
| 0x0035                                                             | _Maschera allarme batteria_ | mappa8   | 0b0000 000x   | Leggere scrivere | 0b0000          | O                |   |
| 0000                                                               |                             |          |               |                  |                 |                  |   |
|                                                                    |                             |          |               |                  |                 |                  |   |
| 0xFFFD                                                             | _Revisione del cluster_     | uint16   | 0x0001-0xFFFE | Sola lettura     | 1               | M                |   |
| _**Attributo di Identificazione delle informazioni sul cluster**_ |                             |          |               |                  |                 |                  |   |

| **Identificatore**                                        | **Nome**                            |               |                      | **Tipo**                  |                                           | **Allineare**                     |                  |              | **Accesso**     |                  | **Predefinito** | **Obbligatorio** |   |
| --------------------------------------------------------- | ----------------------------------- | ------------- | -------------------- | ------------------------- | ----------------------------------------- | --------------------------------- | ---------------- | ------------ | --------------- | ---------------- | --------------- | ---------------- | - |
|                                                           |                                     |               |                      |                           |                                           | **/ Facoltativo**                 |                  |              |                 |                  |                 |                  |   |
|                                                           |                                     |               |                      |                           |                                           |                                   |                  |              |                 |                  |                 |                  |   |
| 0x0000                                                    | _Identificare il tempo_             |               | Senza segno a 16 bit |                           | 0x00 –0xffff                              |                                   | Leggere scrivere |              | 0x0000          | M                |                 |                  |   |
|                                                           |                                     | numero intero |                      |                           |                                           |                                   |                  |              |                 |                  |                 |                  |   |
|                                                           |                                     |               |                      |                           |                                           |                                   |                  |              |                 |                  |                 |                  |   |
| 0xFFFD                                                    | _Revisione del cluster_             |               |                      | uint16                    |                                           | 0x0001-0xFFFE                     |                  | Sola lettura | 1               | M                |                 |                  |   |
| _**Attributo delle informazioni sul gruppo termostati**_ |                                     |               |                      |                           |                                           |                                   |                  |              |                 |                  |                 |                  |   |
|                                                           |                                     |               |                      |                           |                                           |                                   |                  |              |                 |                  |                 |                  |   |
| **Identificatore**                                        | **Nome**                            |               | **Tipo**             |                           | **Allineare**                             |                                   | **Accesso**      |              | **Predefinito** | **Obbligatorio** |                 |                  |   |
|                                                           |                                     |               |                      | **/ Facoltativo**         |                                           |                                   |                  |              |                 |                  |                 |                  |   |
|                                                           |                                     |               |                      |                           |                                           |                                   |                  |              |                 |                  |                 |                  |   |
| 0x0000                                                    | _Temperatura locale_                |               | 16 bit               |                           | 0x954d – 0x7fff                           |                                   | Sola lettura     |              | 0x0000          | M                |                 |                  |   |
|                                                           |                                     |               |                      |                           |                                           |                                   |                  |              |                 |                  |                 |                  |   |
| 0x0003                                                    | _AbsMinHeatSetpointLimite_          |               | 16 bit               |                           | 0x954d – 0x7fff                           |                                   | Sola lettura     |              | 0x01F4          | O                |                 |                  |   |
| 0x0004                                                    | _AbsMaxHeatSetpointLimite_          |               | 16 bit               |                           | 0x954d – 0x7fff                           |                                   | Sola lettura     |              | 0x0DAC          | O                |                 |                  |   |
| 0x0005                                                    | _AbsMinCoolSetpointLimite_          |               | 16 bit               |                           | 0x954d – 0x7fff                           |                                   | Sola lettura     |              | 0x01F4          | O                |                 |                  |   |
| 0x0006                                                    | _AbsMinCoolSetpointLimite_          |               | 16 bit               |                           | 0x954d – 0x7fff                           |                                   | Sola lettura     |              | 0x0DAC          | O                |                 |                  |   |
|                                                           | _Setpoint raffreddamento occupato_  |               |                      |                           | _Punto di raffreddamento minimo_          |                                   | Leggere /        |              |                 |                  |                 |                  |   |
| 0x0011                                                    |                                     | 16 bit        |                      | _Limite_–_Massimo freddo_ |                                           |                                   | 0x0A28           | M            |                 |                  |                 |                  |   |
|                                                           |                                     |               | Scrivere             |                           |                                           |                                   |                  |              |                 |                  |                 |                  |   |
|                                                           |                                     |               |                      |                           |                                           | _Limite del punto di regolazione_ |                  |              |                 |                  |                 |                  |   |
|                                                           |                                     |               |                      |                           |                                           |                                   |                  |              |                 |                  |                 |                  |   |
|                                                           | _Setpoint riscaldamento occupato_   |               |                      |                           | _Punto di impostazione del calore minimo_ |                                   | Leggere /        |              |                 |                  |                 |                  |   |
| 0x0012                                                    |                                     | 16 bit        |                      | _Limite_–_Calore massimo_ |                                           |                                   | 0x07D0           | M            |                 |                  |                 |                  |   |
|                                                           |                                     |               | Scrivere             |                           |                                           |                                   |                  |              |                 |                  |                 |                  |   |
|                                                           |                                     |               |                      |                           |                                           | _Limite del punto di regolazione_ |                  |              |                 |                  |                 |                  |   |
|                                                           |                                     |               |                      |                           |                                           |                                   |                  |              |                 |                  |                 |                  |   |
| 0x001B                                                    | _ControlSequenceOfOperatio_         | 8 bit         |                      | 0x00 – 0x05               |                                           | Leggere /                         |                  | 0x04         | M               |                  |                 |                  |   |
| _N_                                                       |                                     | Enumerazione  |                      |                           | Scrivere                                  |                                   |                  |              |                 |                  |                 |                  |   |
|                                                           |                                     |               |                      |                           |                                           |                                   |                  |              |                 |                  |                 |                  |   |
| 0x001C                                                    | _Modalità sistema_                  |               | 8 bit                |                           | 0x00 – 0x09                               |                                   | Leggere /        |              | 0x04            | M                |                 |                  |   |
|                                                           | Enumerazione                        |               |                      | Scrivere                  |                                           |                                   |                  |              |                 |                  |                 |                  |   |
|                                                           |                                     |               |                      |                           |                                           |                                   |                  |              |                 |                  |                 |                  |   |
| 0x0020                                                    | _Inizio della settimana_            |               | 8 bit                |                           | 0x00 – 0x06                               |                                   | Leggere          |              | -               | O                |                 |                  |   |
|                                                           | Enumerazione                        |               |                      |                           |                                           |                                   |                  |              |                 |                  |                 |                  |   |
|                                                           |                                     |               |                      |                           |                                           |                                   |                  |              |                 |                  |                 |                  |   |
| 0x0021                                                    | _Numero di transizioni settimanali_ |               | inverno8             |                           | 0x00 – 0xff                               |                                   | Leggere          |              | N / A           | O                |                 |                  |   |
|                                                           |                                     |               |                      |                           | 5                                         |                                   |                  |              |                 |                  |                 |                  |   |

| 0x0022                                                         | _Numero di transizioni giornaliere_    | inverno8 | 0x00 – 0xff   |   | Leggere           | N / A  | O            |             |   |                 |                  |   |
| -------------------------------------------------------------- | -------------------------------------- | -------- | ------------- | - | ----------------- | ------ | ------------ | ----------- | - | --------------- | ---------------- | - |
| 0x0023                                                         | _TemperaturaSetpointHold_              | 8 bit    | 0x00 – 0x01   |   | Leggere /         | 0x00   | O            |             |   |                 |                  |   |
| Enumerazione                                                   |                                        | Scrivere |               |   |                   |        |              |             |   |                 |                  |   |
|                                                                |                                        |          |               |   |                   |        |              |             |   |                 |                  |   |
| 0x0025                                                         | _TermostatoProgrammazioneOperati_      | mappa8   | 0b00xxxxxx    |   | Leggere /         | 0b0000 | O            |             |   |                 |                  |   |
| _Emette anche suono_                                           |                                        | Scrivere | 0000          |   |                   |        |              |             |   |                 |                  |   |
|                                                                |                                        |          |               |   |                   |        |              |             |   |                 |                  |   |
| 0xFF01                                                         | _Termostato Modalità Controllo Remoto_ | mappa8   | 0b0000 000x   |   | Leggere /         | 0b0000 | O            |             |   |                 |                  |   |
|                                                                | Scrivere                               | 0000     |               |   |                   |        |              |             |   |                 |                  |   |
|                                                                |                                        |          |               |   |                   |        |              |             |   |                 |                  |   |
| 0xFFFD                                                         | _Revisione del cluster_                | uint16   | 0x0001-0xFFFE |   | Sola lettura      | 1      | M            |             |   |                 |                  |   |
| _**Attributo delle informazioni sul cluster di diagnostica**_ |                                        |          |               |   |                   |        |              |             |   |                 |                  |   |
|                                                                |                                        |          |               |   |                   |        |              |             |   |                 |                  |   |
| **Identificatore**                                             | **Nome**                               |          | **Tipo**      |   | **Allineare**     |        |              | **Accesso** |   | **Predefinito** | **Obbligatorio** |   |
|                                                                |                                        |          |               |   | **/ Facoltativo** |        |              |             |   |                 |                  |   |
|                                                                |                                        |          |               |   |                   |        |              |             |   |                 |                  |   |
| 0x011C                                                         | _UltimoMessaggioLQI_                   |          | 8 bit         |   | 0x00 – 0xFF       |        |              | Leggere     |   | 0x00            | O                |   |
| 0x011D                                                         | _UltimoMessaggioRSSI_                  |          | 8 bit         |   | 0x00 – 0xFF       |        |              | Leggere     |   | 0x00            | O                |   |
| 0xFFFD                                                         | _Revisione del cluster_                |          | uint16        |   | 0x0001-0xFFFE     |        | Sola lettura |             | 1 | M               |                  |   |

6
