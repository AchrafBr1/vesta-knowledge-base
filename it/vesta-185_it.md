# VESTA185

**Sensore di luce ambientale, umidità e temperatura LMHT-1ZBS**

**introduzione**

LMHT-1ZBS è un sensore ZigBee di luce ambientale, umidità e temperatura. Monitora l'ambiente domestico e trasmette l'illuminamento (lux), l'umidità e la temperatura misurati al coordinatore nella rete ZigBee.

Il sensore utilizza la tecnologia ZigBee per la trasmissione del segnale wireless. ZigBee è un protocollo di comunicazione wireless affidabile, con un basso consumo energetico e un'elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

Il sensore funge da dispositivo terminale nella rete ZigBee. Può essere incluso nella rete ZigBee per trasmettere il segnale al momento dell'attivazione, ma non può consentire a nessun altro dispositivo ZigBee di unirsi alla rete attraverso il sensore.

**Identificazione delle parti**

1.  **Sensore di luce/indicatore LED**
    -   **Lampeggia una volta:**Ripristino delle impostazioni di fabbrica
    -   **Lampeggia due volte:**Dopo che il sensore si è unito con successo a una rete ZigBee.
    -   **Lampeggia 3 volte:**Batteria inserita.
    -   **Lampeggia 5 volte:**Rilevata batteria scarica quando si inserisce la batteria.
    -   **Lampeggia una volta ogni 20 minuti:**Il sensore ha perso la connessione alla sua attuale rete ZigBee.
2.  **Termometro**
3.  **Compartimento della batteria**
4.  **Pulsante funzione**
    -   Premi una volta per inviare un segnale al coordinatore.
    -   Tenere premuto per 10 secondi per ripristinare il dispositivo.

![](<.gitbook/assets/0 (73).jpeg>)

**Caratteristiche**

-   _**Monitoraggio dell'illuminazione, dell'umidità e della temperatura**_
    -   Il sensore misura l'illuminamento, l'umidità e la temperatura per trasmettere regolarmente i dati misurati al coordinatore della rete ZigBee.

La lettura dell'illuminamento viene trasmessa ogni 30 minuti.

La lettura dell'umidità e della temperatura viene trasmessa ogni 10 minuti. Il sensore trasmetterà automaticamente il segnale anche quando:

-   -   -   La temperatura varia di +/- 2°C.
        -   L'umidità cambia +/- 10%.
        -   Quando l'illuminamento attuale cambia del +/- 10%.
        -   Il livello di modifica richiesto per attivare la trasmissione del segnale è programmabile utilizzando il comando ZigBee Configure Reporting – parametro Reportable Change. I valori predefiniti sono:

Temperatura:**200**per 2°C.

Umidità:**1000**per il 10%.

Illuminamento:**10**per il 10%.

-   -   È inoltre possibile premere una volta il pulsante funzione per trasmettere manualmente la lettura corrente.
-   _**Rilevamento batteria e batteria scarica**_
    -   Il sensore utilizza una batteria al litio CR123A da 3 V come fonte di alimentazione.
    -   Il sensore è dotato della funzione di rilevamento della batteria scarica. Quando la tensione della batteria è bassa, il sensore trasmetterà il segnale di batteria scarica al coordinatore nella rete ZigBee
    -   Quando si cambia la batteria, dopo aver rimosso le vecchie batterie, premere due volte il pulsante funzione per scaricarla completamente prima di inserire la nuova batteria.
    -   Se viene rilevata una bassa tensione della batteria quando si inserisce la nuova batteria, l'indicatore LED lampeggerà 5 volte.

1

-   _**Supervisione**_

Il sensore trasmetterà un segnale di supervisione insieme al segnale di lettura per segnalare regolarmente la sua condizione. L'intervallo predefinito di fabbrica è 30 minuti, che può essere regolato in base all'impostazione.

**Configurazione della rete ZigBee**

-   _**Linee guida per i dispositivi ZigBee**_

ZigBee è un protocollo di comunicazione wireless affidabile che presenta un basso consumo energetico e un'elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

A causa della struttura fondamentale della rete ZigBee, il dispositivo ZigBee cercherà e si unirà attivamente alla rete dopo l'accensione. Poiché l'esecuzione di un'attività durante la connessione alla rete può consumare energia, è necessario seguire le istruzioni per evitare di scaricare la batteria del dispositivo ZigBee

-   -   Assicurati che il router o il coordinatore della rete ZigBee sia acceso prima di inserire la batteria nel dispositivo ZigBee.
    -   Assicurarsi che il router o il coordinatore della rete ZigBee sia acceso e nel raggio d'azione mentre è in uso un dispositivo ZigBee.
    -   Non rimuovere un dispositivo ZigBee dal router o dal coordinatore della rete ZigBee senza rimuovere la batteria dal dispositivo ZigBee.
-   _**Unirsi alla rete ZigBee**_

Essendo un dispositivo ZigBee, il sensore deve unirsi a una rete ZigBee per trasmettere il segnale. Seguire i passaggi seguenti per collegare il sensore alla rete ZigBee.

-   1.  Staccare il gruppo coperchio superiore e base e inserire la batteria.
    2.  Tenere premuto il pulsante funzione per 10 secondi mentre il sensore si reimposta (il LED lampeggia una volta) e inizia a cercare la rete ZigBee esistente. Assicurati che la funzione di autorizzazione all'accesso sul router o sul coordinatore della tua rete ZigBee sia abilitata.
    3.  Se il sensore si unisce con successo a una rete ZigBee, l'indicatore LED lampeggerà due volte per confermare.
    4.  Dopo essersi unito alla rete ZigBee, il sensore verrà registrato automaticamente nella rete. Controlla il tuo coordinatore ZigBee, il pannello di controllo del sistema o il CIE (apparecchiatura di controllo e indicazione) per confermare se l'adesione e la registrazione hanno avuto esito positivo.
    5.  Dopo aver aderito alla rete ZigBee, se il sensore perde la connessione con l'attuale rete ZigBee, il LED lampeggerà ogni 20 minuti per indicare. Controlla le condizioni della rete ZigBee e la portata del segnale del sensore per correggere la situazione.
-   _**Rimozione del dispositivo dalla rete ZigBee (ripristino delle impostazioni di fabbrica)**_

Per rimuovere il dispositivo dall'attuale rete ZigBee, il sensore deve essere impostato su Ripristino delle impostazioni di fabbrica per completare la rimozione del dispositivo. La funzione di ripristino delle impostazioni di fabbrica cancellerà il dispositivo dalle informazioni sulle impostazioni memorizzate e richiederà al sensore di cercare una nuova rete ZigBee.

**Prima di rimuovere il dispositivo, assicurarsi che il sensore si trovi nel raggio d'azione del segnale della rete ZigBee corrente**

1.  Tenere premuto il pulsante funzione per 10 secondi, quindi rilasciare il pulsante per ripristinare il sensore.
2.  Al momento del ripristino, il sensore cancellerà l'impostazione corrente della rete ZigBee e trasmetterà il segnale al coordinatore ZigBee per rimuoversi dalla rete ZigBee corrente. Quindi cercherà nuovamente attivamente la rete ZigBee disponibile e si unirà automaticamente alla rete.

**Installazione**

-   _**Montaggio del sensore**_

Il sensore può essere montato utilizzando due metodi: montaggio autoadesivo o con viti.

**Montaggio autoadesivo**

1.  Pulire la superficie con uno sgrassatore idoneo.
2.  Rimuovere la copertura protettiva da un lato del cuscinetto biadesivo e applicarlo saldamente sul retro del dispositivo.
3.  Rimuovere l'altro rivestimento e posizionare/premere saldamente il dispositivo nella posizione desiderata.

![](<.gitbook/assets/1 (65).jpeg>)

Non utilizzare il metodo di montaggio autoadesivo su superfici scarsamente verniciate e/o ruvide.

**Montaggio a vite**

La base del sensore ha due fori per viti, dove la plastica è più sottile per il montaggio. Per montare il sensore:

1.  Staccare il gruppo copertura superiore e base allentando la vite di fissaggio della copertura utilizzando un cacciavite Philips.
2.  Sfonda i fori sulla base.

2

-   1.  Utilizzare i fori come dima per praticare due fori e inserire i tasselli.
    2.  Avvitare la base nei tasselli.
    3.  Riposizionare il coperchio superiore sulla base agganciando la base al gancio di fissaggio e spingendo il coperchio verso la base.
    4.  Fissare e riavvitare il coperchio superiore alla base utilizzando un cacciavite Philips.
-   _**Utilizzo del sensore con il router ZigBee**_

_**NOTA IMPORTANTE**_

Se la posizione di installazione del sensore è lontana dal pannello di controllo del sistema e richiede router ZigBee per migliorare la potenza del segnale.**NON**utilizzare un router ZigBee senza batteria di backup. Un router ZigBee senza batteria verrà spento durante un'interruzione di corrente CA e il sensore collegato al router perderà la connessione con la rete ZigBee. Dovresti pianificare la posizione di installazione del sensore utilizzando solo il router ZigBee con batteria di backup.

-   _**Aggiornamento firmware OTA (solo per la versione OTA)**_

Il sensore di luce ambientale, umidità e temperatura supporta la funzione di aggiornamento del firmware OTA tramite la rete ZigBee, che può essere avviata dal coordinatore della rete ZigBee. Seguire i passaggi seguenti per eseguire l'aggiornamento del firmware OTA.**Passo 1.**Devi accedere al tuo ZigBee Coordinator per eseguire l'aggiornamento del firmware in diretta.

**Passo 2.**Nella pagina web di configurazione, seleziona il dispositivo che desideri aggiornare e seleziona il nuovo firmware ZigBee fornito. Per i dettagli fare riferimento al Manuale utente di ZigBee Coordinator.

**Passaggio 3.**Premere "OK" per avviare il processo di aggiornamento e il LED continuerà a lampeggiare. Durante il processo OTA, fallo

non eseguire altre azioni né spegnere la centrale.

**Passaggio 4.**La durata di un aggiornamento richiederà circa 20-30 minuti. Tieni presente che la durata può variare in base alla dimensione del file o alla distanza tra l'accessorio e il coordinatore.

**Passaggio 5.**Attendi il completamento dell'aggiornamento del firmware. Quando l'avanzamento raggiunge il 100%, il dispositivo si ripristinerà automaticamente. Puoi anche aggiornare nuovamente la pagina Web per assicurarti che il firmware del dispositivo venga aggiornato correttamente con la versione più recente visualizzata.

**Appendice**

**(Le informazioni dell'Appendice sono riservate agli sviluppatori.)**

-   _**ID del cluster di sensori di luce**_

**ID dispositivo: sensore di luce 0x0106**

**Punto finale: 0x01**

| **Lato server**                            |                  | **Dalla parte del cliente** |
| ------------------------------------------ | ---------------- | --------------------------- |
|                                            |                  |                             |
|                                            | **Obbligatorio** |                             |
|                                            |                  |                             |
| Di base (0x0000)                           |                  | Di base (0x0000)            |
|                                            |                  |                             |
| Identificare (0x0003)                      |                  | Identificare (0x0003)       |
|                                            |                  |                             |
| Misurazione dell'illuminamento (0x0400)    |                  |                             |
|                                            |                  |                             |
|                                            | **Opzionale**    |                             |
|                                            |                  |                             |
| Configurazione alimentazione (0x0001)      |                  | _Nessuno_                   |
|                                            |                  |                             |
| Misurazione della temperatura (0x0402)     |                  |                             |
|                                            |                  |                             |
| Misurazione dell'umidità relativa (0x0405) |                  |                             |
|                                            |                  |                             |

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
|                    |                               |                   | 3             |             |                        |                  |   |

| 0x0011   | _Ambiente fisico_       | 8 bit    | 0x00 –0xff | Leggere / | 0x00 | O |   |
| -------- | ----------------------- | -------- | ---------- | --------- | ---- | - | - |
| Scrivere |                         |          |            |           |      |   |   |
|          |                         |          |            |           |      |   |   |
| 0x0012   | _Dispositivo abilitato_ | Booleano | 0x00 –0x01 | Leggere / | 0x01 | M |   |
| Scrivere |                         |          |            |           |      |   |   |
|          |                         |          |            |           |      |   |   |

_**Attributo di Identificazione delle informazioni sul cluster**_

| **Identificatore** | **Nome**                | **Tipo**    | **Allineare** | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| ------------------ | ----------------------- | ----------- | ------------- | ----------- | --------------- | ---------------- | - |
| **/ Facoltativo**  |                         |             |               |             |                 |                  |   |
|                    |                         |             |               |             |                 |                  |   |
| 0x0000             | _Identificare il tempo_ | Non firmato | 0x00 –0xffff  | Leggere /   | 0x0000          | M                |   |
| Intero a 16 bit    | Scrivere                |             |               |             |                 |                  |   |
|                    |                         |             |               |             |                 |                  |   |

_**Attributo delle informazioni sul cluster di configurazione dell'alimentazione**_

| **Identificatore** | **Nome**                    | **Tipo** | **Allineare** | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| ------------------ | --------------------------- | -------- | ------------- | ----------- | --------------- | ---------------- | - |
| **/ Facoltativo**  |                             |          |               |             |                 |                  |   |
|                    |                             |          |               |             |                 |                  |   |
| 0x0035             | _Maschera allarme batteria_ | 8 bit    | 0000 000x     | Leggere /   | 0000 0000       | O                |   |
| bitmap             | Scrivere                    |          |               |             |                 |                  |   |
|                    |                             |          |               |             |                 |                  |   |

_**Attributo delle informazioni sul cluster di misurazione dell'illuminamento**_

| **Identificatore** | **Nome**                  | **Tipo**                | **Allineare**        | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| ------------------ | ------------------------- | ----------------------- | -------------------- | ----------- | --------------- | ---------------- | - |
| **/ Facoltativo**  |                           |                         |                      |             |                 |                  |   |
|                    |                           |                         |                      |             |                 |                  |   |
|                    |                           | Firmato a 16 bit        | ValoreMisuratoMin    | Leggere     |                 |                  |   |
| 0x0000             | _Valore misurato_         | A                       | 0x00                 | M           |                 |                  |   |
| Numero intero      | soltanto                  |                         |                      |             |                 |                  |   |
|                    |                           | Valore misurato massimo |                      |             |                 |                  |   |
|                    |                           |                         |                      |             |                 |                  |   |
| 0x0001             | _ValoreMisuratoMin_       | Firmato a 16 bit        | 0x0001 - 0xffffd     | Leggere     | 1               | M                |   |
| Numero intero      | soltanto                  |                         |                      |             |                 |                  |   |
|                    |                           |                         |                      |             |                 |                  |   |
| 0x0002             | _Valore misurato massimo_ | Firmato a 16 bit        | ValoreMisuratoMin +1 | Leggere     | 52742           | M                |   |
| Numero intero      | - 0xffffe                 | soltanto                |                      |             |                 |                  |   |
|                    |                           |                         |                      |             |                 |                  |   |

-   _**Attributo delle informazioni sul cluster di misurazione della temperatura**_

| **Identificatore** | **Nome**                | **Tipo**                | **Allineare**     | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| ------------------ | ----------------------- | ----------------------- | ----------------- | ----------- | --------------- | ---------------- | - |
| **/ Facoltativo**  |                         |                         |                   |             |                 |                  |   |
|                    |                         |                         |                   |             |                 |                  |   |
|                    |                         | Firmato a 16 bit        | ValoreMisuratoMin | Leggere     |                 |                  |   |
| 0x0000             | Valore misurato         | A                       | 0x00              | M           |                 |                  |   |
| Numero intero      | soltanto                |                         |                   |             |                 |                  |   |
|                    |                         | Valore misurato massimo |                   |             |                 |                  |   |
|                    |                         |                         |                   |             |                 |                  |   |
| 0x0001             | ValoreMisuratoMin       | Firmato a 16 bit        | 0x954d – 0x7ffe   | Leggere     | -1000           | M                |   |
| Numero intero      | soltanto                | (-10℃)                  |                   |             |                 |                  |   |
|                    |                         |                         |                   |             |                 |                  |   |
| 0x0002             | Valore misurato massimo | Firmato a 16 bit        | 0x954e – 0x7fff   | Leggere     | 5000            | M                |   |
| Numero intero      | soltanto                | (50℃)                   |                   |             |                 |                  |   |
|                    |                         |                         |                   |             |                 |                  |   |
| 0x0003             | Tolleranza              | Senza segno a 16 bit    | 0x0000 – 0x0800   | Leggere     | 100             | O                |   |
| Numero intero      | soltanto                | (1℃)                    |                   |             |                 |                  |   |
|                    |                         |                         |                   |             |                 |                  |   |

-   _**Attributo delle informazioni sul cluster di misurazione dell'umidità relativa**_

| **Identificatore** | **Nome**                | **Tipo**                | **Allineare**     | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| ------------------ | ----------------------- | ----------------------- | ----------------- | ----------- | --------------- | ---------------- | - |
| **/ Facoltativo**  |                         |                         |                   |             |                 |                  |   |
|                    |                         |                         |                   |             |                 |                  |   |
|                    |                         | Senza segno a 16 bit    | ValoreMisuratoMin | Leggere     |                 |                  |   |
| 0x0000             | Valore misurato         | A                       |                   | M           |                 |                  |   |
| Numero intero      | soltanto                |                         |                   |             |                 |                  |   |
|                    |                         | Valore misurato massimo |                   |             |                 |                  |   |
|                    |                         |                         |                   |             |                 |                  |   |
| 0x0001             | ValoreMisuratoMin       | Senza segno a 16 bit    | 0x0000 – 0x270f   | Leggere     | 0               | M                |   |
| Numero intero      | soltanto                | (0%)                    |                   |             |                 |                  |   |
|                    |                         |                         |                   |             |                 |                  |   |
| 0x0002             | Valore misurato massimo | Senza segno a 16 bit    | 0x0001 – 0x2710   | Leggere     | 10000           | M                |   |
| Numero intero      | soltanto                | (100%)                  |                   |             |                 |                  |   |
|                    |                         |                         |                   |             |                 |                  |   |
| 0x0003             | Tolleranza              | Senza segno a 16 bit    | 0x0000 – 0x0800   | Leggere     | 200             | O                |   |
| Numero intero      | soltanto                | (2%)                    |                   |             |                 |                  |   |
|                    |                         |                         |                   |             |                 |                  |   |

4
