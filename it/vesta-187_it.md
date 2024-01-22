# VESTA187

**Interruttore di scenario intelligente WSS-4E-ZBS**

**introduzione**

WSS-4E-ZBS è un interruttore di scenario ZigBee a quattro pulsanti touch progettato per controllare un gruppo di dispositivi di automazione domestica preprogrammati semplicemente premendo i pulsanti touch dello scenario nella stessa rete ZigBee.

Lo Scenario Switch utilizza la tecnologia ZigBee per la trasmissione del segnale wireless. ZigBee è un protocollo di comunicazione wireless affidabile che presenta un basso consumo energetico e un'elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

Lo Scenario Switch funge da dispositivo terminale nella rete ZigBee. Può essere incluso nella rete ZigBee per trasmettere il segnale al momento dell'attivazione e può controllare qualsiasi dispositivo ZigBee, ma non può consentire a nessun altro dispositivo ZigBee di unirsi alla rete tramite lo Scenario Switch.

L'interruttore di scenario a quattro pulsanti touch ZigBee WSS-4E include i seguenti modelli:

WSS-4E-ZBS

VSS-CHE-ZBS-OTA

![](<.gitbook/assets/0 (75).jpeg>)

**Introduzione al dispositivo**

**1. LED scenario**

Sono presenti quattro LED di scenario, il LED si accenderà in base al pulsante a sfioramento dello scenario corrispondente premuto.

Quando l'interruttore di scenario riceve la conferma dal pannello di controllo dopo la pressione di un pulsante, lampeggerà una volta ed emetterà un segnale acustico come indicazione.

Se il LED lampeggia due volte quando si preme il pulsante a sfioramento, significa che il pannello di controllo ZigBee non è stato in grado di ricevere il segnale inviato da Scenario Switch, verificare la connettività ZigBee.

**2. Pulsante a sfioramento dello scenario**

Lo Scenario Switch dispone di 4 pulsanti touch scenario:

Toccare il pulsante 1

![](<.gitbook/assets/1 (67).jpeg>)

Toccare il pulsante 2

Toccare il pulsante 3

Toccare il pulsante 4

1.  **Compartimento della batteria**
2.  **Pulsante funzione**
    -   Tenere premuto per 10 secondi per ripristinare.
3.  **LED ZigBee (rosso)**

Il LED rosso si accende nelle seguenti situazioni:

-   -   Lampeggia una volta:

Quando si invia un segnale di controllo, ripristino o apprendimento.

Quando il cambio scenario riceve il riconoscimento dal pannello di controllo dopo aver premuto un pulsante.

-   -   Lampeggia due volte:

Lo Scenario Switch si è unito con successo a una rete ZigBee.

1.  **Foro per pulsante funzione**

**Caratteristiche**

![](<.gitbook/assets/2 (60).jpeg>)

-   _**Rilevamento batteria e batteria scarica**_

L'interruttore di scenario utilizza due batterie alcaline AA da 1,5 V come fonte di alimentazione. L'interruttore di scenario è dotato della funzione di rilevamento della batteria scarica. Quando la tensione della batteria è bassa, l'interruttore di scenario trasmetterà il segnale di batteria scarica al coordinatore della rete ZigBee.

1

-   ![](<.gitbook/assets/3 (65).png>)_**Scenario**_

Quando viene premuto un pulsante a sfioramento di scenario, l'interruttore di scenario invierà un segnale al pannello di controllo per attivare lo scenario corrispondente (vedere Pannello di controllo per i dettagli).

**Configurazione della rete ZigBee**

![](<.gitbook/assets/4 (51).jpeg>)

-   _**Linee guida per i dispositivi ZigBee**_

ZigBee è un protocollo di comunicazione wireless affidabile che presenta un basso consumo energetico e un'elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

A causa della struttura fondamentale della rete ZigBee, il dispositivo ZigBee cercherà e si unirà attivamente alla rete dopo l'accensione. Poiché l'esecuzione di un'attività durante la connessione alla rete può consumare energia, è necessario seguire le istruzioni per evitare di scaricare la batteria del dispositivo ZigBee.

-   -   Assicurati che il router o il coordinatore della rete ZigBee sia acceso prima di inserire la batteria nel dispositivo ZigBee.
    -   Assicurarsi che il router o il coordinatore della rete ZigBee sia acceso e nel raggio d'azione mentre un dispositivo ZigBee è in uso.
    -   Non rimuovere un dispositivo ZigBee dal router o dal coordinatore della rete ZigBee senza rimuovere la batteria dal dispositivo ZigBee.
-   _**Unirsi alla rete ZigBee**_

![](<.gitbook/assets/5 (33).jpeg>)

In quanto dispositivo ZigBee, lo Scenario Switch deve unirsi a una rete ZigBee per connettersi ai dispositivi ZigBee.

Segui i passaggi seguenti per unirti allo scenario Passa alla rete ZigBee.

-   1.  Rimuovere il coperchio utilizzando un cacciavite.
    2.  Inserire la batteria quindi riposizionare il coperchio.
    3.  Tieni premuto il pulsante funzione per 10 secondi e rilascialo quando il LED rosso lampeggia una volta per accedere alla rete ZigBee. Assicurati di abilitare la funzione di autorizzazione alla partecipazione sul router o sul coordinatore della tua rete ZigBee.
    4.  Se lo switch di scenario si connette con successo a una rete ZigBee, l'indicatore LED rosso lampeggerà due volte per confermare.
    5.  Dopo l'accesso alla rete ZigBee, lo Scenario Switch verrà registrato automaticamente nella rete. Controlla il coordinatore della rete ZigBee, il pannello di controllo del sistema o il CIE (apparecchiatura di controllo e indicazione) per confermare se l'adesione e la registrazione hanno avuto esito positivo.
-   _**Rimozione del dispositivo dalla rete ZigBee (ripristino delle impostazioni di fabbrica)**_

![](<.gitbook/assets/6 (43).png>)

Per rimuovere lo switch di scenario dalla rete ZigBee corrente, lo switch deve essere impostato su Ripristino delle impostazioni di fabbrica per completare la rimozione del dispositivo. La funzione di ripristino delle impostazioni di fabbrica cancellerà la d dalle informazioni sulle impostazioni memorizzate e richiederà al commutatore di scenario di cercare una nuova rete ZigBee.

**Prima di rimuovere il dispositivo, assicurarsi che l'interruttore di scenario si trovi nel raggio d'azione del segnale della rete ZigBee corrente**

-   1.  Tenere premuto il pulsante funzione per 10 secondi, quindi rilasciare il pulsante per ripristinare il cambio scenario.
    2.  Al momento del ripristino, il commutatore di scenario cancellerà l'impostazione corrente della rete ZigBee e trasmetterà il segnale al coordinatore ZigBee per rimuoversi dalla rete ZigBee corrente. Quindi cercherà nuovamente attivamente la rete ZigBee disponibile e si unirà automaticamente alla rete.
-   _**Aggiornamento firmware OTA (solo per la versione OTA)**_

![](<.gitbook/assets/7 (38).png>)

Lo switch di scenario a quattro pulsanti touch supporta la funzionalità di aggiornamento del firmware OTA tramite la rete ZigBee, che può essere avviata dal coordinatore della rete ZigBee. Seguire i passaggi seguenti per eseguire l'aggiornamento del firmware OTA.**Passo 1.**Devi accedere al tuo ZigBee Coordinator per eseguire l'aggiornamento del firmware in diretta.

**Passo 2.**Nella pagina web di configurazione, seleziona il dispositivo che desideri aggiornare e seleziona il nuovo firmware ZigBee fornito. Fare riferimento al Manuale utente di ZigBee Coordinator per i dettagli.

**Passaggio 3.**Premere "OK" per avviare il processo di aggiornamento e il LED continuerà a lampeggiare. Durante il processo OTA,

non eseguire altre azioni né spegnere la centrale.

**Passaggio 4.**La durata di un aggiornamento richiederà circa 20-30 minuti. Tieni presente che la durata può variare in base alla dimensione del file o alla distanza tra l'accessorio e il coordinatore.

**Passaggio 5.**Attendi il completamento dell'aggiornamento del firmware. Quando l'avanzamento raggiunge il 100%, il dispositivo si ripristinerà automaticamente. È anche possibile aggiornare nuovamente la pagina Web per assicurarsi che il firmware del dispositivo venga aggiornato correttamente con la versione più recente visualizzata.

**Installazione**

-   Lo Scenario Switch è progettato per essere montato su una superficie piana con viti di fissaggio.
-   La base ha 3 fori, dove la plastica è più sottile, per il montaggio.
    1.  Rimuovere il coperchio utilizzando un cacciavite.
    2.  Sfonda gli appositi fori sulla base.
    3.  Utilizzando i fori come modello, praticare dei fori sulla superficie.
    4.  Avvitare la base sulla superficie.
    5.  Riposizionare il coperchio sulla base e fissarlo serrando la vite di fissaggio.

2

![](<.gitbook/assets/8 (34).jpeg>)

-   **Appendice (solo per sviluppatori)**
    -   _**ID cluster selettore scene**_

**ID dispositivo: selettore scene 0x0004**

**Punto finale: 0x01**

| **Lato server**                       |               |                               |                                                                   |                     |              |                 |                       | **Dalla parte del cliente** |                   |                    |   |
| ------------------------------------- | ------------- | ----------------------------- | ----------------------------------------------------------------- | ------------------- | ------------ | --------------- | --------------------- | --------------------------- | ----------------- | ------------------ | - |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   | **Obbligatorio**    |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
| Di base (0x0000)                      |               |                               |                                                                   |                     |              |                 | Identificare (0x0003) |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
| Identificare(0x0003)                  |               |                               |                                                                   |                     |              | Gruppi (0x0004) |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             | Scene (0x0005)    |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   | **Opzionale**       |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
| Configurazione alimentazione (0x0001) |               |                               |                                                                   |                     |              |                 | _Nessuno_             |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
|                                       |               |                              | _**Attributo delle informazioni di base del cluster**_            |                     |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
| _**Identificatore**_                  |               |                               | _**Nome**_                                                        | _**Tipo**_          |              | _**Allineare**_ |                       | _**Accesso**_               | _**Predefinito**_ | _**Obbligatorio**_ |   |
|                                       |               |                               |                                                                   | _**/ Facoltativo**_ |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
| 0x0000                                |               |                               | _Versione ZCL_                                                    | 8 bit senza segno   |              | 0x00 –0xff      |                       | Leggere                     | 0x01              | M                  |   |
|                                       |               | numero intero                 |                                                                   |                     | soltanto     |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
| 0x0001                                |               | Versione dell'applicazione    | 8 bit senza segno                                                 | 0x00 – 0xff         |              | Leggere         | 0x00                  | O                           |                   |                    |   |
|                                       | numero intero |                               | soltanto                                                          |                     |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
| 0x0003                                |               |                               | _Versione HW_                                                     | 8 bit senza segno   |              | 0x00 –0xff      |                       | Leggere                     | 0                 | O                  |   |
|                                       |               | numero intero                 |                                                                   |                     | soltanto     |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
| 0x0004                                |               | _Nome del produttore_         | Carattere                                                         | 0 – 32 byte         |              | Leggere         | Climax                | O                           |                   |                    |   |
|                                       | Corda         |                               | soltanto                                                          | Tecnologia          |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
| 0x0005                                |               |                               | _Identificatore del modello_                                      | Carattere           | 0 – 32 byte  |                 | Leggere               | (Numero di modello)         | O                 |                    |   |
|                                       |               | Corda                         |                                                                   | soltanto            |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
| 0x0006                                |               |                               | _DataCodice_                                                      | Carattere           | 0 – 16 byte  |                 | Leggere               |                             | O                 |                    |   |
|                                       |               | Corda                         |                                                                   | soltanto            |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
| 0x0007                                |               |                               | _Fonte di potere_                                                 | 8 bit               |              | 0x00 –0xff      |                       | Leggere                     |                   | M                  |   |
|                                       |               |                               |                                                                   | soltanto            |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
| 0x0010                                |               | _Descrizione della posizione_ | Carattere                                                         | 0 – 32 byte         |              | Leggere /       |                       | O                           |                   |                    |   |
|                                       | Corda         |                               | Scrivere                                                          |                     |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
| 0x0011                                |               | _Ambiente fisico_             | 8 bit                                                             |                     | 0x00 –0xff   |                 | Leggere /             | 0x00                        | O                 |                    |   |
|                                       |               |                               | Scrivere                                                          |                     |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
| 0x0012                                |               |                               | _Dispositivo abilitato_                                           | Booleano            | 0x00 –0x01   |                 | Leggere /             | 0x01                        | M                 |                    |   |
|                                       |               |                               | Scrivere                                                          |                     |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
|                                       |               |                              | _**Attributo di Identificazione delle informazioni sul cluster**_ |                     |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
| **Identificatore**                    |               |                               | **Nome**                                                          | **Tipo**            |              | **Allineare**   |                       | **Accesso**                 | **Predefinito**   | **Obbligatorio**   |   |
|                                       |               |                               |                                                                   | **/ Facoltativo**   |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |
| 0x0000                                |               |                               | _Identificare il tempo_                                           | Non firmato         | 0x00 –0xffff |                 | Leggere /             | 0x0000                      | M                 |                    |   |
|                                       |               | Intero a 16 bit               |                                                                   | Scrivere            |              |                 |                       |                             |                   |                    |   |
|                                       |               |                               |                                                                   |                     |              |                 |                       |                             |                   |                    |   |

-   _**Attributo delle informazioni sul cluster di configurazione dell'alimentazione**_

| **Identificatore** | **Nome**                  | **Tipo** | **Allineare** | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| ------------------ | ------------------------- | -------- | ------------- | ----------- | --------------- | ---------------- | - |
| **/ Facoltativo**  |                           |          |               |             |                 |                  |   |
|                    |                           |          |               |             |                 |                  |   |
| 0x0035             | Maschera allarme batteria | Bitmap   | 0000 - 000x   | Leggere /   | 0000 0000       | O                |   |
| (8 bit)            | Scrivere                  |          |               |             |                 |                  |   |
|                    |                           |          |               |             |                 |                  |   |

3
