# VESTA 180

**Interruttore di controllo dell'otturatore SCS-1-ZBS**

**introduzione**

SCS-1-ZBS è un interruttore di controllo per tapparelle a tre pulsanti ZigBee progettato per controllare un gruppo di dispositivi domotici preprogrammati semplicemente premendo i pulsanti dello scenario. Impostando lo scenario di controllo delle tapparelle sul coordinatore/pannello di controllo della rete ZigBee, l'interruttore di controllo delle tapparelle sarà in grado di controllare il movimento delle tapparelle semplicemente premendo i suoi pulsanti.

L'interruttore dell'otturatore utilizza la tecnologia ZigBee per la trasmissione del segnale wireless. ZigBee è un protocollo di comunicazione wireless affidabile che presenta un basso consumo energetico e un'elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

Lo Shutter Switch funge da dispositivo terminale nella rete ZigBee. Può essere incluso nella rete ZigBee per trasmettere il segnale al momento dell'attivazione e può controllare qualsiasi dispositivo ZigBee, ma non può consentire a nessun altro dispositivo ZigBee di unirsi alla rete tramite l'interruttore dell'otturatore.

L'interruttore di controllo dell'otturatore SCS-1 ZigBee include i seguenti modelli:

SCS-1-ZBS

SCS-1-ZBS-OTA

![](<.gitbook/assets/0 (69).jpeg>)

**Introduzione al dispositivo**

**1. LED scenario**

Quando viene premuto uno qualsiasi dei 3 pulsanti dello scenario, il LED si accenderà brevemente

**2. Pulsanti degli scenari**

L'interruttore di controllo dell'otturatore ha 3 pulsanti di scenario

1.  **Compartimento della batteria**
2.  **Pulsante funzione**
    -   Tenere premuto per 10 secondi per ripristinare.
3.  **LED ZigBee (rosso)**

Il LED rosso si accende nelle seguenti situazioni:

-   -   Lampeggia una volta:

Quando si invia un segnale di controllo/reset/apprendimento.

-   -   Lampeggia due volte:

L'interruttore di controllo dell'otturatore si è unito con successo a una rete ZigBee.

1.  **Foro per pulsante funzione**

**Caratteristiche**

![](<.gitbook/assets/1 (61).jpeg>)

-   _**Rilevamento batteria e batteria scarica**_

L'interruttore di controllo dell'otturatore utilizza due batterie alcaline AA da 1,5 V come fonte di alimentazione. L'interruttore è dotato della funzione di rilevamento della batteria scarica. Quando la tensione della batteria è bassa, l'interruttore di controllo dell'otturatore trasmetterà il segnale di batteria scarica al coordinatore della rete ZigBee.

![](<.gitbook/assets/2 (62).png>)

-   _**Supervisione**_

L'interruttore di controllo dell'otturatore trasmetterà un segnale di supervisione per segnalare regolarmente la sua condizione in base all'intervallo di tempo impostato dall'utente. L'intervallo predefinito in fabbrica è 30 minuti.

![](<.gitbook/assets/3 (63).png>)

-   _**Controllo scenari e tapparelle**_

Quando viene premuto un pulsante di scenario, l'interruttore di controllo dell'otturatore invierà un segnale al pannello di controllo

1

attivare lo scenario corrispondente (vedi Pannello di Controllo per i dettagli). Impostare lo scenario nel pannello di controllo per controllare la funzione di apertura/chiusura/arresto della serranda per azionare la serranda tramite l'interruttore di controllo scenario. L'interruttore emetterà un segnale acustico come indicazione quando il pulsante viene premuto.

**Configurazione della rete ZigBee**

![](<.gitbook/assets/4 (48).jpeg>)

-   _**Linee guida per i dispositivi ZigBee**_

ZigBee è un protocollo di comunicazione wireless affidabile che presenta un basso consumo energetico e un'elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

A causa della struttura fondamentale della rete ZigBee, il dispositivo ZigBee cercherà e si unirà attivamente alla rete dopo l'accensione. Poiché l'esecuzione di un'attività durante la connessione alla rete può consumare energia, è necessario seguire le istruzioni per evitare di scaricare la batteria del dispositivo ZigBee.

-   -   Assicurati che il router o il coordinatore della rete ZigBee sia acceso prima di inserire la batteria nel dispositivo ZigBee.
    -   Assicurarsi che il router o il coordinatore della rete ZigBee sia acceso e nel raggio d'azione mentre è in uso un dispositivo ZigBee.
    -   Non rimuovere un dispositivo ZigBee dal router o dal coordinatore della rete ZigBee senza rimuovere la batteria dal dispositivo ZigBee.
-   _**Unirsi alla rete ZigBee**_

![](<.gitbook/assets/5 (31).jpeg>)

In quanto dispositivo ZigBee, l'interruttore di controllo dell'otturatore deve unirsi a una rete ZigBee per connettersi ai dispositivi ZigBee. Seguire i passaggi seguenti per collegare l'interruttore di controllo dell'otturatore alla rete ZigBee.

-   1.  Rimuovere il coperchio utilizzando un cacciavite.
    2.  Inserire la batteria quindi riposizionare il coperchio.
    3.  Tieni premuto il pulsante funzione per 10 secondi e rilascialo quando il LED rosso lampeggia una volta per accedere alla rete ZigBee. Assicurati di abilitare la funzione di autorizzazione alla partecipazione sul router o sul coordinatore della tua rete ZigBee.
    4.  Se l'interruttore di controllo dell'otturatore si connette con successo a una rete ZigBee, l'indicatore LED rosso lampeggerà due volte per confermare.
    5.  Dopo l'accesso alla rete ZigBee, l'interruttore di controllo dell'otturatore verrà registrato automaticamente nella rete. Controlla il coordinatore della rete ZigBee, il pannello di controllo del sistema o il CIE (apparecchiatura di controllo e indicazione) per confermare se l'adesione e la registrazione hanno avuto esito positivo.
-   _**Rimozione del dispositivo dalla rete ZigBee (ripristino delle impostazioni di fabbrica)**_

![](<.gitbook/assets/6 (41).png>)

Per rimuovere il dispositivo dall'attuale rete ZigBee, l'interruttore di controllo dell'otturatore deve essere impostato su Ripristino delle impostazioni di fabbrica per completare la rimozione del dispositivo. La funzione di ripristino delle impostazioni di fabbrica cancellerà il dispositivo dalle informazioni sulle impostazioni memorizzate e richiederà all'interruttore di controllo dell'otturatore di cercare una nuova rete ZigBee.

**Prima di rimuovere il dispositivo, assicurarsi che l'interruttore di controllo dell'otturatore si trovi nel raggio d'azione del segnale della rete ZigBee corrente**

-   1.  Elimina il controllo dell'otturatore dal pannello di controllo/CIE corrente.
    2.  Tieni premuto il pulsante funzione per 10 secondi, quindi rilascia il pulsante per ripristinare il dispositivo.
    3.  Al momento del ripristino, l'interruttore di controllo dell'otturatore cancellerà l'impostazione corrente della rete ZigBee e trasmetterà il segnale al coordinatore ZigBee per rimuoversi dalla rete ZigBee corrente. Quindi cercherà nuovamente attivamente la rete ZigBee disponibile e si unirà automaticamente alla rete.
-   _**Aggiornamento firmware OTA (solo per la versione OTA)**_

![](<.gitbook/assets/7 (37).jpeg>)

L'interruttore di controllo dell'otturatore supporta la funzionalità di aggiornamento del firmware OTA tramite la rete ZigBee, che può essere avviata dal coordinatore della rete ZigBee.

Seguire i passaggi seguenti per eseguire l'aggiornamento del firmware OTA.

**Passo 1.**Devi accedere al tuo ZigBee Coordinator per eseguire l'aggiornamento del firmware in diretta.

**Passo 2.**Nella pagina web di configurazione, seleziona il dispositivo che desideri aggiornare e seleziona il nuovo firmware ZigBee fornito. Fare riferimento al Manuale utente di ZigBee Coordinator per i dettagli.

**Passaggio 3.**Premere "OK" per avviare il processo di aggiornamento e il LED continuerà a lampeggiare. Durante il processo OTA, non eseguire altre azioni o spegnere il pannello.

**Passaggio 4.**La durata di un aggiornamento richiederà circa 20-30 minuti. Tieni presente che la durata può variare in base alla dimensione del file o alla distanza tra l'accessorio e il coordinatore.

**Passaggio 5.**Attendi il completamento dell'aggiornamento del firmware. Quando l'avanzamento raggiunge il 100%, il dispositivo si ripristinerà automaticamente. È inoltre possibile aggiornare nuovamente la pagina Web per assicurarsi che il firmware del dispositivo venga aggiornato correttamente con la versione più recente visualizzata.

![](<.gitbook/assets/8 (31).jpeg>)

**Installazione**

-   L'interruttore di controllo dell'otturatore è progettato per essere montato su una superficie piana con viti di fissaggio.
-   La base ha 3 fori, dove la plastica è più sottile, per il montaggio.
    1.  Rimuovere il coperchio utilizzando un cacciavite.
    2.  Sfonda gli appositi fori sulla base.
    3.  Utilizzando i fori come modello, praticare dei fori sulla superficie.

2

1.  Avvitare la base sulla superficie.
2.  Riposizionare il coperchio sulla base e fissarlo serrando la vite di fissaggio.

![](<.gitbook/assets/9 (23).jpeg>)

-   **Appendice (solo per sviluppatori)**

_**ID cluster selettore scene**_

**ID dispositivo: selettore scene 0x0004**

**Punto finale: 0x01**

| **Lato server** |                  | **Dalla parte del cliente** |
| --------------- | ---------------- | --------------------------- |
|                 |                  |                             |
|                 | **Obbligatorio** |                             |

Di base (0x0000)

Identificare (0x0003)

Identificare (0x0003)

Gruppi (0x0004)

Scene (0x0005)

**Opzionale**

Configurazione alimentazione (0x0001)

_Nessuno_

-   _**Attributo delle informazioni di base del cluster**_

| _**Identificatore**_ | _**Nome**_                    | _**Tipo**_        | _**Allineare**_ | _**Accesso**_ | _**Predefinito**_   | _**Obbligatorio**_ |   |
| -------------------- | ----------------------------- | ----------------- | --------------- | ------------- | ------------------- | ------------------ | - |
| _**/ Facoltativo**_  |                               |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0000               | _Versione ZCL_                | 8 bit senza segno | 0x00 –0xff      | Leggere       | 0x01                | M                  |   |
| numero intero        | soltanto                      |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0001               | Versione dell'applicazione    | 8 bit senza segno | 0x00 – 0xff     | Leggere       | 0x00                | O                  |   |
| numero intero        | soltanto                      |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0003               | _Versione HW_                 | 8 bit senza segno | 0x00 –0xff      | Leggere       | 0                   | O                  |   |
| numero intero        | soltanto                      |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0004               | _Nome del produttore_         | Carattere         | 0 – 32 byte     | Leggere       | Climax              | O                  |   |
| Corda                | soltanto                      | Tecnologia        |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0005               | _Identificatore del modello_  | Carattere         | 0 – 32 byte     | Leggere       | (Numero di modello) | O                  |   |
| Corda                | soltanto                      |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0006               | _DataCodice_                  | Carattere         | 0 – 16 byte     | Leggere       |                     | O                  |   |
| Corda                | soltanto                      |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0007               | _Fonte di potere_             | 8 bit             | 0x00 –0xff      | Leggere       |                     | M                  |   |
| soltanto             |                               |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0010               | _Descrizione della posizione_ | Carattere         | 0 – 32 byte     | Leggere /     |                     | O                  |   |
| Corda                | Scrivere                      |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0011               | _Ambiente fisico_             | 8 bit             | 0x00 –0xff      | Leggere /     | 0x00                | O                  |   |
| Scrivere             |                               |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0012               | _Dispositivo abilitato_       | Booleano          | 0x00 –0x01      | Leggere /     | 0x01                | M                  |   |
| Scrivere             |                               |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |

-   _**Attributo di Identificazione delle informazioni sul cluster**_

| **Identificatore** | **Nome**                                                                             | **Tipo**    | **Allineare** | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| ------------------ | ------------------------------------------------------------------------------------ | ----------- | ------------- | ----------- | --------------- | ---------------- | - |
| **/ Facoltativo**  |                                                                                      |             |               |             |                 |                  |   |
|                    |                                                                                      |             |               |             |                 |                  |   |
| 0x0000             | _Identificare il tempo_                                                              | Non firmato | 0x00 –0xffff  | Leggere /   | 0x0000          | M                |   |
| Intero a 16 bit    | Scrivere                                                                             |             |               |             |                 |                  |   |
|                    |                                                                                      |             |               |             |                 |                  |   |
|                    | _**Attributo delle informazioni sul cluster di configurazione dell'alimentazione**_ |             |               |             |                 |                  |   |
|                    |                                                                                      |             |               |             |                 |                  |   |
| **Identificatore** | **Nome**                                                                             | **Tipo**    | **Allineare** | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| **/ Facoltativo**  |                                                                                      |             |               |             |                 |                  |   |
|                    |                                                                                      |             |               |             |                 |                  |   |
| 0x0035             | Maschera allarme batteria                                                            | Bitmap      | 0000 - 000x   | Leggere /   | 0000 0000       | O                |   |
| (8 bit)            | Scrivere                                                                             |             |               |             |                 |                  |   |
|                    |                                                                                      |             |               |             |                 |                  |   |

3

_**ID cluster controller ombre (per pannello HPGW-G)**_

**ID dispositivo: controller tende 0x0201**

**Punto finale: 0x01**

| **Lato server** |                  | **Dalla parte del cliente** |
| --------------- | ---------------- | --------------------------- |
|                 |                  |                             |
|                 | **Obbligatorio** |                             |

Di base (0x0000)

Identificare (0x0003)

Identificare (0x0003)

Acceso/Spento (0x0006)

Controllo di livello (0x0008)

**Opzionale**

Configurazione alimentazione (0x0001)

_Nessuno_

-   _**Attributo delle informazioni di base del cluster**_

| _**Identificatore**_ | _**Nome**_                    | _**Tipo**_        | _**Allineare**_ | _**Accesso**_ | _**Predefinito**_   | _**Obbligatorio**_ |   |
| -------------------- | ----------------------------- | ----------------- | --------------- | ------------- | ------------------- | ------------------ | - |
| _**/ Facoltativo**_  |                               |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0000               | _Versione ZCL_                | 8 bit senza segno | 0x00 –0xff      | Leggere       | 0x01                | M                  |   |
| numero intero        | soltanto                      |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0001               | Versione dell'applicazione    | 8 bit senza segno | 0x00 – 0xff     | Leggere       | 0x00                | O                  |   |
| numero intero        | soltanto                      |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0003               | _Versione HW_                 | 8 bit senza segno | 0x00 –0xff      | Leggere       | 0                   | O                  |   |
| numero intero        | soltanto                      |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0004               | _Nome del produttore_         | Carattere         | 0 – 32 byte     | Leggere       | Climax              | O                  |   |
| Corda                | soltanto                      | Tecnologia        |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0005               | _Identificatore del modello_  | Carattere         | 0 – 32 byte     | Leggere       | (Numero di modello) | O                  |   |
| Corda                | soltanto                      |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0006               | _DataCodice_                  | Carattere         | 0 – 16 byte     | Leggere       |                     | O                  |   |
| Corda                | soltanto                      |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0007               | _Fonte di potere_             | 8 bit             | 0x00 –0xff      | Leggere       |                     | M                  |   |
| soltanto             |                               |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0010               | _Descrizione della posizione_ | Carattere         | 0 – 32 byte     | Leggere /     |                     | O                  |   |
| Corda                | Scrivere                      |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0011               | _Ambiente fisico_             | 8 bit             | 0x00 –0xff      | Leggere /     | 0x00                | O                  |   |
| Scrivere             |                               |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |
| 0x0012               | _Dispositivo abilitato_       | Booleano          | 0x00 –0x01      | Leggere /     | 0x01                | M                  |   |
| Scrivere             |                               |                   |                 |               |                     |                    |   |
|                      |                               |                   |                 |               |                     |                    |   |

-   _**Attributo di Identificazione delle informazioni sul cluster**_

| **Identificatore** | **Nome**                                                                             | **Tipo**    | **Allineare** | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| ------------------ | ------------------------------------------------------------------------------------ | ----------- | ------------- | ----------- | --------------- | ---------------- | - |
| **/ Facoltativo**  |                                                                                      |             |               |             |                 |                  |   |
|                    |                                                                                      |             |               |             |                 |                  |   |
| 0x0000             | _Identificare il tempo_                                                              | Non firmato | 0x00 –0xffff  | Leggere /   | 0x0000          | M                |   |
| Intero a 16 bit    | Scrivere                                                                             |             |               |             |                 |                  |   |
|                    |                                                                                      |             |               |             |                 |                  |   |
|                    | _**Attributo delle informazioni sul cluster di configurazione dell'alimentazione**_ |             |               |             |                 |                  |   |
|                    |                                                                                      |             |               |             |                 |                  |   |
| **Identificatore** | **Nome**                                                                             | **Tipo**    | **Allineare** | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| **/ Facoltativo**  |                                                                                      |             |               |             |                 |                  |   |
|                    |                                                                                      |             |               |             |                 |                  |   |
| 0x0035             | Maschera allarme batteria                                                            | Bitmap      | 0000 - 000x   | Leggere /   | 0000 0000       | O                |   |
| (8 bit)            | Scrivere                                                                             |             |               |             |                 |                  |   |
|                    |                                                                                      |             |               |             |                 |                  |   |

4
