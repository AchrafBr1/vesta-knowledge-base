# VESTA184

**Sensore ambientale RS-23ZBS**V: R3

**introduzione**

RS-23ZBS is a ZigBee Room Sensor. It features both temperature and humidity detection function to monitor your home environments. The temperature and humidity information will be transmitted to the coordinator in the ZigBee network and displayed on the Room Sensor’s LCD screen.

Il sensore ambientale utilizza la tecnologia ZigBee per la trasmissione del segnale wireless. ZigBee è un protocollo di comunicazione wireless affidabile che presenta un basso consumo energetico e un'elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in rete una grande quantità di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali

Il Room Sensor funge da dispositivo terminale nella rete ZigBee. Può essere incluso nella rete ZigBee per trasmettere il segnale al momento dell'attivazione, ma non può consentire a nessun altro dispositivo ZigBee di unirsi alla rete tramite il sensore ambientale.

![](<.gitbook/assets/0 (72).jpeg>)

**Identificazione delle parti**

**1. Display LCD**

Il display LCD visualizza le seguenti informazioni:

-   -   Temperatura nell'impostazione Fahrenheit / Celsius
    -   Umidità UR%.
    -   Connettività di rete ZigBee (![](<.gitbook/assets/1 (64).jpeg>)icona).
    -   Stato della batteria scarica (icona).
    -   Retroilluminazione LCD accesa: quando viene premuto il pulsante funzione.

1.  **Pulsante funzione**
    -   Premere una volta il pulsante per:

Invia un segnale di supervisione con informazioni su temperatura/umidità Accendi la retroilluminazione LCD per 10 secondi.

-   -   Tenere premuto per 10 secondi, quindi rilasciare per ripristinare il sensore ambiente

1.  **Vite della base (coperchio aperto/chiuso)**

![](<.gitbook/assets/2 (58).jpeg>)

Quando il coperchio anteriore è installato su quello posteriore, aprire il coperchio allentando la vite della base e chiuderlo allo stesso modo.

1.  **Ponticello di impostazione Fahrenheit/Celcius (JP1)**
    -   Se il collegamento del ponticello è inserito tra i 2 pin superiori, il display LCD visualizzerà la temperatura in gradi Celsius. (**Impostazione di fabbrica**)
    -   Se il collegamento del ponticello è inserito tra i 2 pin inferiori, il display LCD visualizzerà la temperatura in Fahrenheit.
2.  **Compartimento della batteria**

![](<.gitbook/assets/3 (64).png>)

Il sensore ambientale è alimentato da due batterie alcaline AA da 1,5 V

1.  **Copertina posteriore**
2.  **Fori per montaggio a parete**

**Caratteristiche**

-   _**Rilevamento della temperatura e dell'umidità**_
    -   Il sensore ambientale trasmetterà regolarmente i segnali di temperatura e umidità in base all'impostazione. L'intervallo predefinito in fabbrica è 10 minuti.
    -   Quando la temperatura cambia di +/- 2°C o l'umidità cambia di +/- 10%, anche il sensore ambiente trasmetterà un segnale.
    -   Il livello di modifica richiesto per attivare la trasmissione del segnale è programmabile utilizzando il comando ZigBee Configure Reporting – parametro Reportable Change. I valori predefiniti sono: Temperatura:**200**per 2°C.

Umidità:**1000**per il 10%.

1

-   -   È inoltre possibile premere una volta il pulsante funzione per trasmettere manualmente un segnale di temperatura e umidità.
    -   L'intervallo di rilevamento della temperatura è di circa -10°C - 50°C (14°F - 122°F).
    -   L'intervallo di rilevamento dell'umidità è di circa il 10% - 90% RH.
-   _**Rilevamento batteria e batteria scarica**_
    -   Il sensore ambiente utilizza due batterie alcaline da 1,5 V come fonte di alimentazione. Le batterie sono incluse nella confezione.
    -   Il sensore ambientale è dotato della funzione di rilevamento della batteria scarica. Quando la tensione della batteria è bassa, il sensore ambientale trasmetterà il segnale di batteria scarica per avvisare l'utente e visualizzare l'icona di batteria scarica sul display LCD.
    -   Quando si sostituiscono le batterie, dopo aver rimosso quelle vecchie, premere due volte il pulsante funzione per scaricarle completamente prima di inserire nuove batterie.
-   _**Supervisione**_

Il sensore ambientale trasmetterà un segnale di supervisione insieme al segnale di temperatura e umidità per segnalare regolarmente le sue condizioni. L'intervallo predefinito di fabbrica è 10 minuti, che può essere regolato in base all'impostazione.

**Configurazione della rete ZigBee**

-   _**Linee guida per i dispositivi ZigBee**_

ZigBee è un protocollo di comunicazione wireless affidabile che presenta un basso consumo energetico e un'elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

A causa della struttura fondamentale della rete ZigBee, il dispositivo ZigBee cercherà e si unirà attivamente alla rete dopo l'accensione. Poiché l'esecuzione di un'attività durante la connessione alla rete può consumare energia, è necessario seguire le istruzioni per evitare di scaricare la batteria del dispositivo ZigBee

-   -   Assicurati che il router o il coordinatore della rete ZigBee sia acceso prima di inserire la batteria nel dispositivo ZigBee.
    -   Assicurarsi che il router o il coordinatore della rete ZigBee sia acceso e nel raggio d'azione mentre un dispositivo ZigBee è in uso.
    -   Non rimuovere un dispositivo ZigBee dal router o dal coordinatore della rete ZigBee senza rimuovere la batteria dal dispositivo ZigBee.
-   _**Unirsi alla rete ZigBee**_

In quanto dispositivo ZigBee, il sensore ambientale deve unirsi a una rete ZigBee per trasmettere il segnale di temperatura e umidità. Seguire i passaggi seguenti per connettere il sensore ambiente alla rete ZigBee.

-   1.  Inserire le batterie nel vano batterie per accendere il sensore ambiente.
    2.  Dopo l'accensione, tieni premuto il pulsante Funzione per 10 secondi, quindi rilascialo per connetterti alla rete. Assicurati che la funzione di autorizzazione all'accesso sul router o sul coordinatore della tua rete ZigBee sia abilitata.
    3.  Se il sensore ambientale si connette con successo a una rete ZigBee, l'icona di connettività della rete ZigBee verrà visualizzata sul display LCD
    4.  Dopo aver aderito alla rete ZigBee, il sensore ambientale verrà registrato automaticamente nella rete. Controlla il tuo coordinatore ZigBee, il pannello di controllo del sistema o il CIE (apparecchiatura di controllo e indicazione) per confermare se l'adesione e la registrazione hanno avuto esito positivo.
    5.  Dopo l'accesso alla rete e la registrazione avvenuta con successo, se il sensore ambiente perde la connessione con il pannello di controllo o il pannello di controllo è spento, l'icona di connettività di rete ZigBee sul display LCD del sensore ambiente si spegnerà entro 1 o 2 minuti.
    6.  Se l'accesso e la registrazione alla rete non hanno esito positivo, l'icona della connettività di rete ZigBee non verrà visualizzata. Controlla il coordinatore della rete ZigBee, il pannello di controllo o le impostazioni CIE per assicurarti che la funzione di autorizzazione all'adesione sia disponibile, quindi utilizza la funzione di ripristino delle impostazioni di fabbrica di seguito per accedere alla rete ZigBee.
-   _**Rimozione del dispositivo dalla rete ZigBee (ripristino delle impostazioni di fabbrica)**_

Per rimuovere il sensore ambientale dall'attuale rete ZigBee, il dispositivo deve essere sottoposto al ripristino delle impostazioni di fabbrica per completare la rimozione del dispositivo. La funzione di ripristino delle impostazioni di fabbrica cancellerà il dispositivo dalle informazioni sulle impostazioni memorizzate e richiederà al sensore ambientale di cercare una nuova rete ZigBee.

**Prima di rimuovere il dispositivo, assicurarsi che il sensore ambientale si trovi nel raggio d'azione del segnale della rete ZigBee corrente**

1.  Tenere premuto il pulsante funzione per 10 secondi, quindi rilasciare il pulsante per ripristinare il sensore ambiente.
2.  Al momento del ripristino, il sensore ambientale cancellerà l'impostazione corrente della rete ZigBee e trasmetterà il segnale

2

Il coordinatore ZigBee si rimuove dall'attuale rete ZigBee. Quindi cercherà nuovamente attivamente la rete ZigBee disponibile e si unirà automaticamente alla rete.

**Installazione**

-   _**Montaggio del sensore ambiente**_

Per la migliore qualità del display LCD, il sensore ambientale deve essere montato in una posizione a circa 5° sopra l'altezza degli occhi.

-   Montaggio a vite.

Durante il montaggio con viti, assicurarsi di utilizzare solo le viti fornite nella confezione dal produttore originale, poiché viti inadeguate potrebbero danneggiare l'interno del dispositivo.

-   1.  Rimuovere il coperchio anteriore utilizzando un cacciavite.
    2.  Sfonda i fori sul retro della copertina.
    3.  Utilizzando i fori come modello, praticare dei fori sulla superficie
    4.  Inserire i tasselli in caso di fissaggio su intonaco o mattoni
    5.  Avvitare il coperchio posteriore nei tasselli
    6.  Riavvitare il coperchio anteriore sul coperchio posteriore.
-   _**Utilizzo del sensore ambientale con il router ZigBee**_

_**NOTA IMPORTANTE**_

Se la posizione di installazione del sensore ambientale è lontana dal pannello di controllo del sistema e richiede router ZigBee per migliorare la potenza del segnale.**NON**utilizzare un router ZigBee senza batteria di riserva. Un router ZigBee senza batteria verrà spento durante un'interruzione di corrente CA e il sensore ambientale collegato al router perderà la connessione con la rete ZigBee. Dovresti pianificare la posizione di installazione del sensore ambientale utilizzando solo il router ZigBee con batteria di backup.

**Appendice(Solo per sviluppatori.)**

-   _**ID del cluster di sensori ambiente**_

**ID dispositivo: sensore di temperatura 0x0302**

**Punto finale: 0x01**

| **Lato server**                            |                  | **Dalla parte del cliente** |
| ------------------------------------------ | ---------------- | --------------------------- |
|                                            |                  |                             |
|                                            | **Obbligatorio** |                             |
|                                            |                  |                             |
| Di base (0x0000)                           |                  | _Nessuno_                   |
|                                            |                  |                             |
| Identificare(0x0003)                       |                  |                             |
|                                            |                  |                             |
|                                            | **Opzionale**    |                             |
|                                            |                  |                             |
| Configurazione alimentazione (0x0001)      |                  | _Nessuno_                   |
|                                            |                  |                             |
| Misurazione della temperatura (0x0402)     |                  |                             |
|                                            |                  |                             |
| Misurazione dell'umidità relativa (0x0405) |                  |                             |
|                                            |                  |                             |

|                   | _**Attributo delle informazioni di base del cluster**_ |             |   |               |              |                 |                  |   |   |
| ------------------ | ------------------------------------------------------ | ----------- | - | ------------- | ------------ | --------------- | ---------------- | - | - |
|                    |                                                        |             |   |               |              |                 |                  |   |   |
| **Identificatore** | **Nome**                                               | **Tipo**    |   | **Allineare** | **Accesso**  | **Predefinito** | **Obbligatorio** |   |   |
|                    | **/ Facoltativo**                                      |             |   |               |              |                 |                  |   |   |
|                    |                                                        |             |   |               |              |                 |                  |   |   |
| 0x0000             | _Versione ZCL_                                         | Non firmato |   | 0x00 –0xff    | Sola lettura | 0x01            | M                |   |   |
| Intero a 8 bit     |                                                        |             |   |               |              |                 |                  |   |   |
|                    |                                                        |             |   |               |              |                 |                  |   |   |
| 0x0001             | Versione dell'applicazione                             | Non firmato |   | 0x00 –0xff    | Sola lettura | 0x00            | O                |   |   |
| Intero a 8 bit     |                                                        |             |   |               |              |                 |                  |   |   |
|                    |                                                        |             |   |               |              |                 |                  |   |   |
| 0x0003             | _Versione HW_                                          | Non firmato |   | 0x00 –0xff    | Sola lettura | 0               | O                |   |   |
| Intero a 8 bit     |                                                        |             |   |               |              |                 |                  |   |   |
|                    |                                                        |             |   |               |              |                 |                  |   |   |
| 0x0004             | _Nome del produttore_                                  | Carattere   |   | 0 – 32 byte   | Sola lettura | Climax          | O                |   |   |
| Corda              |                                                        | Tecnologia  |   |               |              |                 |                  |   |   |
|                    |                                                        |             |   |               |              |                 |                  |   |   |
| 0x0005             | _Identificatore del modello_                           | Carattere   |   | 0 – 32 byte   | Sola lettura | (Modello        | O                |   |   |
| Corda              |                                                        | Versione)   |   |               |              |                 |                  |   |   |
|                    |                                                        |             |   |               |              |                 |                  |   |   |
| 0x0006             | _DataCodice_                                           | Carattere   |   | 0 – 16 byte   | Sola lettura |                 | O                |   |   |
| Corda              |                                                        |             |   |               |              |                 |                  |   |   |
|                    |                                                        |             |   |               |              |                 |                  |   |   |
| 0x0007             | _Fonte di potere_                                      | 8 bit       |   | 0x00 –0xff    | Sola lettura |                 | M                |   |   |
| 0x0010             | _Descrizione della posizione_                          | Carattere   |   | 0 – 32 byte   | Leggere /    |                 | O                |   |   |
| Corda              |                                                        | Scrivere    |   |               |              |                 |                  |   |   |
|                    |                                                        |             |   |               |              |                 |                  |   |   |
| 0x0011             | _Ambiente fisico_                                      | 8 bit       |   | 0x00 –0xff    | Leggere /    | 0x00            | O                |   |   |
|                    | Scrivere                                               |             |   |               |              |                 |                  |   |   |
|                    |                                                        |             |   |               |              |                 |                  |   |   |
|                    |                                                        |             |   | 3             |              |                 |                  |   |   |

0x0012

_Dispositivo abilitato_

Booleano

0x00 –0x01

Leggere /

Scrivere

0x01

M

-   _**Attributo di Identificazione delle informazioni sul cluster**_

| **Identificatore** | **Nome**                | **Tipo**    | **Allineare** | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| ------------------ | ----------------------- | ----------- | ------------- | ----------- | --------------- | ---------------- | - |
| **/ Facoltativo**  |                         |             |               |             |                 |                  |   |
|                    |                         |             |               |             |                 |                  |   |
| 0x0000             | _Identificare il tempo_ | Non firmato | 0x00 –0xffff  | Leggere /   | 0x0000          | M                |   |
| Intero a 16 bit    | Scrivere                |             |               |             |                 |                  |   |
|                    |                         |             |               |             |                 |                  |   |

_**Attributo delle informazioni sul cluster di configurazione dell'alimentazione**_

| **Identificatore** | **Nome**                    | **Tipo**       | **Allineare** | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| ------------------ | --------------------------- | -------------- | ------------- | ----------- | --------------- | ---------------- | - |
| **/ Facoltativo**  |                             |                |               |             |                 |                  |   |
|                    |                             |                |               |             |                 |                  |   |
| 0x0035             | _Maschera allarme batteria_ | Bitmap a 8 bit | 0000 000x     | Leggere /   | 0000 0000       | O                |   |
| Scrivere           |                             |                |               |             |                 |                  |   |
|                    |                             |                |               |             |                 |                  |   |

_**Attributo delle informazioni sul cluster di misurazione della temperatura**_

| **Identificatore** | **Nome**                                                                            | **Tipo**             | **Allineare**       | **Accesso** | **Predefinito** | **Obbligatorio** |   |   |
| ------------------ | ----------------------------------------------------------------------------------- | -------------------- | ------------------- | ----------- | --------------- | ---------------- | - | - |
| **/ Facoltativo**  |                                                                                     |                      |                     |             |                 |                  |   |   |
|                    |                                                                                     |                      |                     |             |                 |                  |   |   |
| 0x0000             | Valore misurato                                                                     | Firmato a 16 bit     | ValoreMisuratoMin a | Leggere     | 0x00            | M                |   |   |
| Numero intero      | Valore misurato massimo                                                             | soltanto             |                     |             |                 |                  |   |   |
|                    |                                                                                     |                      |                     |             |                 |                  |   |   |
|                    |                                                                                     |                      |                     |             |                 |                  |   |   |
| 0x0001             | ValoreMisuratoMin                                                                   | Firmato a 16 bit     | 0x954d – 0x7ffe     | Leggere     | -1000           | M                |   |   |
| Numero intero      | soltanto                                                                            | (-10℃)               |                     |             |                 |                  |   |   |
|                    |                                                                                     |                      |                     |             |                 |                  |   |   |
| 0x0002             | Valore misurato massimo                                                             | Firmato a 16 bit     | 0x954e – 0x7fff     | Leggere     | 5000            | M                |   |   |
| Numero intero      | soltanto                                                                            | (50℃)                |                     |             |                 |                  |   |   |
|                    |                                                                                     |                      |                     |             |                 |                  |   |   |
| 0x0003             | Tolleranza                                                                          | Senza segno a 16 bit | 0x0000 – 0x0800     | Leggere     | 100             | O                |   |   |
| Numero intero      | soltanto                                                                            | (1℃)                 |                     |             |                 |                  |   |   |
|                    |                                                                                     |                      |                     |             |                 |                  |   |   |
|                   | _**Attributo delle informazioni sul cluster di misurazione dell'umidità relativa**_ |                      |                     |             |                 |                  |   |   |
|                    |                                                                                     |                      |                     |             |                 |                  |   |   |
| **Identificatore** | **Nome**                                                                            | **Tipo**             | **Allineare**       | **Accesso** | **Predefinito** | **Obbligatorio** |   |   |
| **/ Facoltativo**  |                                                                                     |                      |                     |             |                 |                  |   |   |
|                    |                                                                                     |                      |                     |             |                 |                  |   |   |
| 0x0000             | Valore misurato                                                                     | Senza segno a 16 bit | ValoreMisuratoMin a | Leggere     |                 | M                |   |   |
| Numero intero      | Valore misurato massimo                                                             | soltanto             |                     |             |                 |                  |   |   |
|                    |                                                                                     |                      |                     |             |                 |                  |   |   |
|                    |                                                                                     |                      |                     |             |                 |                  |   |   |
| 0x0001             | ValoreMisuratoMin                                                                   | Senza segno a 16 bit | 0x0000 – 0x270f     | Leggere     | 0               | M                |   |   |
| Numero intero      | soltanto                                                                            | (0%)                 |                     |             |                 |                  |   |   |
|                    |                                                                                     |                      |                     |             |                 |                  |   |   |
| 0x0002             | ValoreMisuratoMax                                                                   | Senza segno a 16 bit | 0x0001 – 0x2710     | Leggere     | 10000           | M                |   |   |
| e                  | Numero intero                                                                       | soltanto             | (100%)              |             |                 |                  |   |   |
|                    |                                                                                     |                      |                     |             |                 |                  |   |   |
| 0x0003             | Tolleranza                                                                          | Senza segno a 16 bit | 0x0000 – 0x0800     | Leggere     | 200             | O                |   |   |
| Numero intero      | soltanto                                                                            | (2%)                 |                     |             |                 |                  |   |   |
|                    |                                                                                     |                      |                     |             |                 |                  |   |   |

4
