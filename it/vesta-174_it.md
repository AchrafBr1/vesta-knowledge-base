# VESTA174

**Serie di interruttori a relè di potenza PRS2-ZBS(R)-P5 / PRM2-ZBS(R)-P5**

La serie di interruttori relè di potenza comprende i seguenti modelli:**PRS2-ZBS-P5:**Interruttore di alimentazione relè ZigBee**PRS2-ZBSR-P5:**Interruttore di alimentazione relè ZigBee con funzione router**PRM2-ZBS-P5:**Interruttore di alimentazione relè ZigBee con misuratore

**PRM2-ZBSR-P5:**Interruttore di alimentazione relè ZigBee con funzione misuratore e router

Gli interruttori di alimentazione sono in grado di ricevere segnali wireless dal coordinatore nella rete Zigbee per attivare/disattivare gli apparecchi ad esso collegati.

L'interruttore relè di potenza utilizza la tecnologia ZigBee per la trasmissione del segnale wireless e supporta la funzionalità di aggiornamento del firmware Over-the-Air (OTA) (solo per la versione OTA). ZigBee è un protocollo di comunicazione wireless affidabile, a basso consumo energetico e con elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

I modelli con funzioni contatore (PRM2-ZBS-P5 / PRM2-ZBSR-P5) hanno la caratteristica extra di tenere traccia del consumo energetico con un misuratore di potenza integrato e trasmettere regolarmente i dati al coordinatore.

I modelli con funzione router (PRS2-ZBSR-P5 / PRM2-ZBSR-P5) fungono anche da router nella rete ZigBee. Dopo essere stato incluso nella rete ZigBee, consente ad altri dispositivi ZigBee di unirsi alla rete tramite l'interruttore di accensione.

| **Modello numero:** | **Metro** | **Router ZigBee** |
| ------------------- | --------- | ----------------- |
|                     |           |                   |
| **PRS2-ZBS-P5**     | **NO**    | **NO**            |
|                     |           |                   |
| **PRS2-ZBSR-P5**    | **NO**    | **SÌ**            |
|                     |           |                   |
| **PRM2-ZBS-P5**     | **SÌ**    | **NO**            |
|                     |           |                   |
| **PRM2-ZBSR-P5**    | **SÌ**    | **SÌ**            |
|                     |           |                   |

![](<.gitbook/assets/0 (65).jpeg>)

**Identificazione delle parti**

**1. Indicatore LED**

L'indicatore LED viene utilizzato per indicare lo stato dell'interruttore del relè di alimentazione:

-   SU:

L'interruttore del relè di potenza è acceso.

-   Spento:

L'interruttore del relè di potenza è spento.

-   Lampeggia

Quando l'interruttore del relè di alimentazione è durante gli aggiornamenti OTA.

-   -   Lampeggia due volte:

L'interruttore relè di potenza si è unito con successo a una rete ZigBee.

-   -   Lampeggia 5 volte

L'interruttore del relè di potenza si è collegato correttamente a un controller

-   -   Lampeggia ogni 20 minuti

L'interruttore relè di potenza ha perso la connessione alla rete ZigBee corrente

(**Solo PSS-29ZBS-P5 e PSM-29ZBS-P5**)

1.  **Pulsante funzione**

**Utilizzo dei pulsanti funzione:**

-   -   Premere il pulsante per attivare/disattivare l'interruttore del relè di potenza
    -   Tenere premuto il pulsante per 10 secondi, quindi rilasciarlo per ripristinare l'interruttore del relè di alimentazione.
    -   Tieni premuto il pulsante per 3 secondi, quindi rilascialo per associarlo a un controller

1.  **Terminale interruttore esterno 1 (tensione CA)**
2.  **Terminale 2 dell'interruttore esterno (tensione CA)**
3.  **Uscita carico alimentazione linea CA**
4.  **Uscita di carico di alimentazione neutra CA**
5.  **Ingresso alimentazione neurale CA**
6.  **Ingresso alimentazione linea CA**

**Configurazione della rete ZigBee**

![](<.gitbook/assets/1 (58).jpeg>)

-   _**Linee guida per i dispositivi ZigBee**_

1

ZigBee è un protocollo di comunicazione wireless affidabile, a basso consumo energetico e con elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

A causa della struttura fondamentale della rete ZigBee, il dispositivo ZigBee cercherà e si unirà attivamente alla rete dopo l'accensione.

![](<.gitbook/assets/2 (53).jpeg>)

-   _**Unirsi alla rete ZigBee**_

In quanto dispositivo ZigBee, l'interruttore relè di potenza deve unirsi a una rete ZigBee per ricevere comandi e trasmettere informazioni sul consumo energetico. Seguire i passaggi seguenti per collegare l'interruttore relè di potenza a una rete ZigBee.

-   1.  Collegare l'interruttore del relè di potenza al cavo di alimentazione.
    2.  Tieni premuto il pulsante Funzione per 10 secondi, quindi rilascialo per connetterti alla rete. Assicurati che la funzione di autorizzazione all'accesso sul router o sul coordinatore della tua rete ZigBee sia abilitata.
    3.  Se l'interruttore relè di potenza si connette con successo a una rete ZigBee, l'indicatore LED lampeggerà due volte per confermare.
    4.  Dopo aver aderito alla rete ZigBee, l'interruttore relè di potenza verrà registrato automaticamente nella rete. Si prega di controllare il coordinatore della rete Zigbee, il pannello di controllo del sistema o il CIE (apparecchiatura di controllo e indicazione) per confermare se l'adesione e la registrazione hanno avuto esito positivo.
    5.  Se la registrazione e l'accesso alla rete non hanno esito positivo, controlla il coordinatore della rete ZigBee, il pannello di controllo del sistema o le impostazioni CIE per assicurarti che la funzione di autorizzazione all'accesso sia disponibile, quindi utilizza la funzione di ripristino delle impostazioni di fabbrica di seguito per accedere alla rete ZigBee.
-   _**Associazione con il controller**_

![](<.gitbook/assets/3 (47).jpeg>)

Dopo essersi unito alla rete ZigBee, l'interruttore relè di potenza può collegarsi con un dispositivo controller che può essere utilizzato per regolare il livello di potenza in uscita dell'interruttore relè di potenza. Per collegare l'interruttore del relè di potenza e il dispositivo:

-   1.  Tenere premuto il pulsante funzione per 3 secondi, quindi rilasciare il pulsante. L'interruttore del relè di potenza invierà una richiesta vincolante al coordinatore.
    2.  Fare riferimento al manuale del controller per inviare una richiesta vincolante per il dispositivo entro 16 secondi.
    3.  Se il collegamento ha esito positivo, l'indicatore LED dell'interruttore del relè di potenza lampeggerà 5 volte per confermare. Ora è possibile utilizzare il controller per regolare il livello di potenza in uscita per l'interruttore del relè di potenza.
    4.  Se l'associazione non riesce, riprovare il processo di associazione.
-   _**Rimozione del dispositivo dalla rete ZigBee (ripristino delle impostazioni di fabbrica)**_

![](<.gitbook/assets/4 (60).png>)

Per rimuovere l'interruttore di accensione dalla rete ZigBee corrente, l'interruttore di accensione deve essere impostato su Ripristino delle impostazioni di fabbrica per completare la rimozione del dispositivo. La funzione di ripristino delle impostazioni di fabbrica cancellerà l'interruttore di accensione dalle impostazioni e dalle informazioni memorizzate e richiederà all'interruttore di accensione di cercare una nuova rete ZigBee.

**Prima di rimuovere il dispositivo, assicurarsi che l'interruttore di accensione si trovi nel raggio d'azione del segnale della rete ZigBee corrente**

-   1.  Tenere premuto il pulsante funzione per 10 secondi, quindi rilasciare il pulsante per ripristinare l'interruttore di accensione.
    2.  Al momento del ripristino, l'interruttore di accensione cancellerà l'impostazione corrente della rete ZigBee e trasmetterà il segnale al coordinatore ZigBee per rimuoversi dalla rete ZigBee corrente. Quindi cercherà nuovamente attivamente la rete ZigBee disponibile e si unirà automaticamente alla rete.
-   _**Capacità del dispositivo router ZigBee (solo PRS2-ZBSR-P5 / PRM2-ZBSR-P5)**_

![](<.gitbook/assets/5 (60).png>)

I modelli Power Switch con funzione Router consentono ad altri dispositivi ZigBee di unirsi alla rete ZigBee tramite il router. Il Power Switch Router ha una capacità massima di 40 dispositivi, inclusi 10 router; il router del misuratore di alimentazione ha una capacità massima di 10 dispositivi inclusi 5 router.

| **Modello numero:**       | **Dispositivo ZigBee massimo** | **ZigBee massimo** |   |
| ------------------------- | ------------------------------ | ------------------ | - |
| **+ Capacità del router** | **Capacità del router**        |                    |   |
|                           |                                |                    |   |
|                           |                                |                    |   |
| **PSS-29ZBSR-P5**         | **40**                         | **10**             |   |
|                           |                                |                    |   |
| **PSM-29ZBSR-P5**         | **10**                         | **5**              |   |
|                           |                                |                    |   |

![](<.gitbook/assets/6 (40).jpeg>)

**Attenzione**

-   -   Tutti gli interventi sul dispositivo, comprese l'installazione e la manutenzione, devono essere eseguiti da un elettricista qualificato e autorizzato.
    -   Prima dell'installazione o di qualsiasi intervento di manutenzione, assicurarsi che l'alimentazione elettrica sia stata scollegata.
    -   Non collegare il dispositivo a carichi che superano la corrente di carico supportata.
    -   Dopo l'accensione, evitare di toccare i fili per evitare folgorazioni.
-   _**Aggiornamento firmware OTA (solo per la versione OTA)**_

![](<.gitbook/assets/7 (36).png>)

L'interruttore relè di potenza supporta la funzionalità di aggiornamento del firmware OTA tramite la rete ZigBee, che può essere avviata dal coordinatore della rete ZigBee. Seguire i passaggi seguenti per eseguire l'aggiornamento del firmware OTA.

1.  Devi accedere al tuo ZigBee Coordinator per eseguire l'aggiornamento del firmware in diretta.
2.  Nella pagina web di configurazione, seleziona il dispositivo che desideri aggiornare e seleziona il nuovo firmware ZigBee fornito. Per i dettagli fare riferimento al Manuale utente di ZigBee Coordinator.
3.  Premere "OK" per avviare il processo di aggiornamento e il LED continuerà a lampeggiare. Durante il processo OTA, non eseguire altre azioni o spegnere il pannello.
4.  La durata di un aggiornamento richiederà circa 20-30 minuti. Si prega di notare che la durata può 2

variano in base alla dimensione del file o alla distanza tra l'accessorio e il coordinatore.

1.  Attendi il completamento dell'aggiornamento del firmware. Quando l'avanzamento raggiunge il 100%, il dispositivo si ripristinerà automaticamente. Puoi anche aggiornare nuovamente la pagina Web per assicurarti che il firmware del dispositivo venga aggiornato correttamente con la versione più recente visualizzata.

**Operazione**

![](<.gitbook/assets/8 (30).jpeg>)

-   _**Schema di collegamento dei cavi**_
    -   Fare riferimento allo schema per collegare l'illuminazione domestica all'interruttore del relè di potenza.
-   _**Installazione**_
    -   Collegare l'interruttore del relè di potenza al cavo di alimentazione.
    -   Collega il cavo di alimentazione all'illuminazione domestica. L'illuminazione deve essere in stato ON.
    -   È possibile collegare un interruttore esterno all'interruttore del relè di potenza secondo lo schema per accendere/spegnere l'interruttore del relè di potenza
    -   _**NOTA IMPORTANTE**_**:**L'interruttore del relè di alimentazione non dispone di una batteria di riserva e verrà spento in caso di interruzione dell'alimentazione CA.**NON**utilizzare l'interruttore relè di potenza come router per il sensore di sicurezza o dispositivi di controllo allarme come contatto porta, sensore PIR, ecc., altrimenti i sensori perderanno la connessione alla rete ZigBee se l'interruttore relè di potenza è scollegato dall'alimentazione CA. Pianificare le posizioni di installazione di questi sensori di sicurezza senza utilizzare l'interruttore relè di potenza e utilizzare solo un router con batteria di backup. La funzione router dell'interruttore di alimentazione dovrebbe**SOLTANTO**essere utilizzato per fornire l'estensione della portata del segnale per altri interruttori di alimentazione/dimmer.
-   _**Controllo degli elettrodomestici**_
    -   Dopo che l'interruttore relè di potenza si è unito con successo a una rete ZigBee, il coordinatore può accendere/spegnere l'apparecchio da remoto.
    -   È inoltre possibile premere il pulsante sull'interruttore del relè di potenza per accendere/spegnere la luce.
    -   È possibile accendere/spegnere l'interruttore del relè di potenza con un interruttore esterno.
    -   Se hai associato un controller all'interruttore del relè di potenza, puoi anche utilizzare il controller per accendere/spegnere l'interruttore del relè di potenza.
    -   Se l'ingresso dell'alimentazione CA viene disconnesso dall'interruttore del relè di potenza, il suo precedente stato di accensione/spegnimento verrà ripristinato entro 1 minuto dalla riconnessione dell'ingresso dell'alimentazione CA all'interruttore del relè di potenza.
-   _**Monitoraggio del consumo energetico (solo PRM2-ZBS-P5 / PRM2-ZBSR-P5)**_
    -   L'interruttore relè di potenza trasmetterà ogni due minuti un segnale con i dati sul consumo energetico al coordinatore della rete ZigBee.
    -   Ogni volta che l'output energetico dell'interruttore di alimentazione cambia di +/- 2 W, trasmetterà automaticamente un segnale con i dati sul consumo energetico al coordinatore della rete ZigBee per l'aggiornamento.
    -   L'interruttore di alimentazione trasmette un segnale con i dati di potenza al coordinatore ogni volta che il consumo energetico accumulato aumenta di 0,1 kW/ora.
    -   Il misuratore ha una precisione del +/- 5%.
    -   Per cancellare dall'interruttore di accensione i dati di consumo energetico accumulati, attenersi alla procedura seguente:
        1.  Scollegare l'interruttore del relè di potenza dalla presa di corrente.
        2.  Tenere premuto il pulsante funzione e ricollegare l'alimentazione tenendo premuto il pulsante.
        3.  Continua a tenere premuto il pulsante e rilascialo dopo 3 secondi. I dati sul consumo energetico accumulati verranno cancellati.
-   _**Carico operativo massimo**_
    -   Per 110 V: il carico operativo massimo è 1100 W e 10 A.
    -   Per 230 V: il carico massimo di funzionamento è 2300 W e 10 A.
    -   Se l'interruttore del relè di potenza si surriscalda, interromperà automaticamente l'alimentazione come misura di sicurezza. L'utente deve scollegare e ricollegare l'alimentazione CA all'interruttore del relè di potenza dopo l'interruzione per riprendere il normale funzionamento.

![](<.gitbook/assets/9 (22).jpeg>)![](<.gitbook/assets/10 (17).jpeg>)![](<.gitbook/assets/11 (23).jpeg>)![](<.gitbook/assets/12 (32).png>)![](<.gitbook/assets/13 (21).jpeg>)

**Appendice (solo per sviluppatori)**

![](<.gitbook/assets/14 (21).png>)

_**Interruttore relè di potenza con ID cluster contatori**_

**ID dispositivo: presa di corrente: 0x0009**

**Punto finale: 0x01**

| **Lato server** |                  | **Dalla parte del cliente** |
| --------------- | ---------------- | --------------------------- |
|                 |                  |                             |
|                 | **Obbligatorio** |                             |

Di base (0x0000)

Identificare(0x0003)

Gruppi(0x0004)

Scene(0x0005)

_Nessuno_

3

Acceso/Spento(0x0006)

**Opzionale**

| Misurazione (0x0702) (solo PRM2-ZBS-P5 / PRM2-ZBSR-P5) | Nessuno |
| ------------------------------------------------------ | ------- |
|                                                        |         |

![](<.gitbook/assets/15 (18).jpeg>)![](<.gitbook/assets/16 (14).jpeg>)

_**Attributo delle informazioni di base del cluster**_

![](<.gitbook/assets/17 (15).jpeg>)

| **Identificatore**                                                                                  | **Nome**                        |               |                            |                             |               | **Tipo**             |                |                | **Allineare**    |                   |                   |              | **Accesso**       |                   |                 |                 | **Predefinito**  |                  | **Obbligatorio** |                  |   |   |   |   |   |   |   |   |
| --------------------------------------------------------------------------------------------------- | ------------------------------- | ------------- | -------------------------- | --------------------------- | ------------- | -------------------- | -------------- | -------------- | ---------------- | ----------------- | ----------------- | ------------ | ----------------- | ----------------- | --------------- | --------------- | ---------------- | ---------------- | ---------------- | ---------------- | - | - | - | - | - | - | - | - |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              | **/ Facoltativo** |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x0000                                                                                              | _Versione ZCL_                  |               |                            | 8 bit senza segno           |               | 0x00 –0xff           |                |                |                  | Sola lettura      |                   |              |                   |                   | 0x01            |                 | M                |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            | numero intero               |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x0001                                                                                              | Versione dell'applicazione      |               |                            | 8 bit senza segno           |               | 0x00 – 0xff          |                |                |                  | Sola lettura      |                   |              |                   |                   | 0x00            |                 | O                |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            | numero intero               |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x0003                                                                                              | _Versione HW_                   |               |                            | 8 bit senza segno           |               | 0x00 –0xff           |                |                |                  | Sola lettura      |                   |              |                   | 0                 |                 | O               |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            | numero intero               |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x0004                                                                                              | _Nome del produttore_           |               |                            | Stringa di caratteri        |               | 0 – 32 byte          |                |                |                  | Sola lettura      |                   |              |                   | Climax            |                 | O               |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      | Tecnologia     |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x0005                                                                                              | _Identificatore del modello_    |               |                            | Stringa di caratteri        |               | 0 – 32 byte          |                |                |                  | Sola lettura      |                   |              |                   | (Modello          |                 | O               |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                | Versione)        |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x0006                                                                                              | _DataCodice_                    |               |                            | Stringa di caratteri        |               | 0 – 16 byte          |                |                |                  | Sola lettura      |                   |              |                   |                   |                 |                 | O                |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x0007                                                                                              | _Fonte di potere_               |               |                            |                             |               | 8 bit                |                | 0x00 –0xff     |                  |                   |                   | Sola lettura |                   |                   |                 |                 |                  |                  | M                |                  |   |   |   |   |   |   |   |   |
| 0x0010                                                                                              | _Descrizione della posizione_   |               |                            | Stringa di caratteri        |               | 0 – 32 byte          |                |                | Leggere scrivere |                   |                   |              |                   |                   |                 | O               |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x0011                                                                                              | _Ambiente fisico_               |               |                            |                             |               | 8 bit                |                | 0x00 –0xff     |                  |                   | Leggere scrivere  |              |                   |                   |                 | 0x00            |                  | O                |                  |                  |   |   |   |   |   |   |   |   |
| 0x0012                                                                                              | _Dispositivo abilitato_         |               |                            |                             |               | Booleano             |                | 0x00 –0x01     |                  |                   | Leggere scrivere  |              |                   |                   |                 | 0x01            |                  | M                |                  |                  |   |   |   |   |   |   |   |   |
| _**Attributo di Identificazione delle informazioni sul cluster**_                                  |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| **Identificatore**                                                                                  | **Nome**                        |               |                            |                             |               |                      | **Tipo**       |                |                  | **Allineare**     |                   |              | **Accesso**       |                   |                 | **Predefinito** |                  | **Obbligatorio** |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   | **/ Facoltativo** |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x0000                                                                                              | _Identificare il tempo_         |               |                            | Intero a 16 bit senza segno |               |                      | 0x00 –0xffff   |                | Leggere scrivere |                   |                   |              | 0x0000            |                   | M               |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| _**Attributi del cluster Gruppi Informazioni**_                                                    |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| **Identificatore**                                                                                  | **Nome**                        |               |                            |                             |               | **Tipo**             |                |                | **Allineare**    |                   |                   | **Accesso**  |                   |                   | **Predefinito** |                 | **Obbligatorio** |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  | **/ Facoltativo** |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x0000                                                                                              | _NomeSupport_                   |               |                            |                             |               | Bitmap a 8 bit       |                | x0000000       |                  |                   | Sola lettura      |              |                   |                   | -               |                 | M                |                  |                  |                  |   |   |   |   |   |   |   |   |
| _**Attributi delle informazioni sul cluster Scene**_                                               |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| **Identificatore**                                                                                  | **Nome**                        |               |                            |                             |               |                      | **Tipo**       |                |                  | **Allineare**     |                   |              | **Accesso**       |                   |                 | **Predefinito** |                  | **Obbligatorio** |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   | **/ Facoltativo** |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x0000                                                                                              | _NomeSupport_                   |               |                            |                             |               | Bitmap a 8 bit       |                | x0000000       |                  |                   | Sola lettura      |              |                   |                   | 0x00            |                 | M                |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x0001                                                                                              | _Scena corrente_                |               | Intero a 8 bit senza segno |                             | 0x00 – 0xff   |                      |                | Sola lettura   |                  |                   |                   | 0x00         |                   | M                 |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x0002                                                                                              | _Gruppo corrente_               |               |                            |                             |               |                      | Non firmato    |                |                  | 0x0000 –          |                   |              | Sola lettura      |                   |                 |                 |                  | 0x00             |                  | M                |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            | Intero a 16 bit             |               |                      | 0xfff7         |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x0003                                                                                              | _SceneValid_                    |               |                            |                             |               |                      | Booleano       |                | 0x00 – 0x01      |                   |                   | Sola lettura |                   |                   |                 | 0x00            |                  | M                |                  |                  |   |   |   |   |   |   |   |   |
| 0x0004                                                                                              | _NomeSupport_                   |               |                            |                             |               | Bitmap a 8 bit       |                | x0000000       |                  |                   | Sola lettura      |              |                   |                   | -               |                 | M                |                  |                  |                  |   |   |   |   |   |   |   |   |
| _**Attributo delle informazioni sul cluster On/Off**_                                              |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| **Identificatore**                                                                                  | **Nome**                        |               |                            |                             |               | **Tipo**             |                |                | **Allineare**    |                   |                   | **Accesso**  |                   |                   | **Predefinito** |                 | **Obbligatorio** |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  | **/ Facoltativo** |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x0000                                                                                              | _Acceso spento_                 |               |                            |                             |               | Booleano             |                | 0x00 –0x01     |                  |                   | Sola lettura      |              |                   |                   | 0x00            |                 | M                |                  |                  |                  |   |   |   |   |   |   |   |   |
| _**Attributi delle Informazioni del cluster di Misurazione (Set Attributi Lettura Informazioni)**_ |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| **Identificatore**                                                                                  | **Nome**                        |               |                            |                             |               | **Tipo**             |                |                | **Allineare**    |                   |                   |              |                   |                   | **Accesso**     |                 | **Predefinito**  |                  | **Obbligatorio** |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   | **T**        |                   | **/ Facoltativo** |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x00                                                                                                | Somma corrente                  |               |                            |                             |               | Senza segno a 48 bit |                | 0x000000000000 | A                |                   | Sola lettura      |              |                   |                   | M               |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| Consegnato                                                                                          |                                 |               |                            |                             | Numero intero |                      | 0xFFFFFFFFFFFF |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| _**Attributi delle informazioni sul cluster di misurazione (set di attributi di formattazione)**_  |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| **Identificatore**                                                                                  | **Nome**                        |               |                            |                             |               | **Tipo**             |                |                | **Allineare**    |                   |                   |              |                   | **Accesso**       |                 |                 |                  | **Predefinito**  |                  | **Obbligatorio** |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   | **/ Facoltativo** |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x00                                                                                                | Unità di misura                 |               |                            |                             |               | Enumerazione a 8 bit |                |                | Da 0x00 a 0xFF   |                   |                   |              | Sola lettura      |                   |                 |                 | 0x00             |                  | M                |                  |   |   |   |   |   |   |   |   |
| 0x01                                                                                                | Moltiplicatore                  |               |                            |                             |               | Senza segno a 24 bit |                |                | 0x000000 a       |                   |                   |              | Sola lettura      |                   |                 | 1               |                  | O                |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            | Numero intero               |               |                      | 0xFFFFFF       |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x02                                                                                                | Divisore                        |               |                            |                             |               | Senza segno a 24 bit |                |                | 0x000000 a       |                   |                   |              | Sola lettura      |                   |                 | 10000           |                  | O                |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            | Numero intero               |               |                      | 0xFFFFFF       |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x03                                                                                                | SommaFormazione                 |               |                            |                             |               | Bitmap a 8 bit       |                |                | Da 0x00 a 0xFF   |                   |                   |              | Sola lettura      |                   |                 |                 | 0xF9             |                  | M                |                  |   |   |   |   |   |   |   |   |
| 0x04                                                                                                | DemandFormating                 |               |                            |                             |               | Bitmap a 8 bit       |                |                | Da 0x00 a 0xFF   |                   |                   |              | Sola lettura      |                   |                 |                 | 0Ksasa           |                  | O                |                  |   |   |   |   |   |   |   |   |
| 0x06                                                                                                | Tipo dispositivo di misurazione |               |                            |                             |               | Bitmap a 8 bit       |                |                | Da 0x00 a 0xFF   |                   |                   |              | Sola lettura      |                   |                 |                 | 0x00             |                  | M                |                  |   |   |   |   |   |   |   |   |
| _**Attributi delle Informazioni del cluster di Misurazione (Set Attributi Storici)**_              |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| **Identificatore**                                                                                  | **Nome**                        |               |                            |                             |               | **Tipo**             |                |                | **Allineare**    |                   |                   |              |                   | **Accesso**       |                 |                 | **Predefinito**  |                  | **Obbligatorio** |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              | **/ Facoltativo** |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
| 0x00                                                                                                | Domanda istantanea              |               |                            | Firmato a 24 bit            |               |                      | -8.388.607 a   |                |                  |                   | Sola lettura      |              |                   |                   | 0x00            |                 | O                |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 | Numero intero |                            | 8,388,607                   |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |
|                                                                                                     |                                 |               |                            |                             |               |                      |                |                |                  |                   |                   |              |                   |                   |                 |                 |                  |                  |                  |                  |   |   |   |   |   |   |   |   |

![](<.gitbook/assets/18 (23).png>)![](<.gitbook/assets/19 (24).png>)![](<.gitbook/assets/20 (16).png>)

4
