# VESTA186

**Serie di interruttori di alimentazione PSS-29ZBS(R) / PSM-29ZBS(R).**

**introduzione**

La serie Power Switch comprende i seguenti modelli:

**PSS-29ZBS:**Interruttore di alimentazione ZigBee

**PSS-29ZBSR:**ZigBee Power Switch con funzione Router

**PSM-29ZBS:**Interruttore di alimentazione ZigBee con misuratore

**PSM-29ZBSR:**Interruttore di alimentazione ZigBee con funzione misuratore e router

Gli interruttori di alimentazione sono in grado di ricevere segnali wireless dal coordinatore nella rete ZigBee per attivare/disattivare gli apparecchi ad esso collegati.

L'interruttore di alimentazione utilizza la tecnologia ZigBee per la trasmissione del segnale wireless. ZigBee è un protocollo di comunicazione wireless affidabile, a basso consumo energetico e con elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

I modelli con funzioni di misuratore (PSM-29ZBS / PSM-29ZBSR) hanno la caratteristica extra di tenere traccia del consumo energetico con un misuratore di potenza integrato e trasmettere regolarmente i dati al coordinatore.

I modelli con funzione router (PSS-29ZBSR / PSM-29ZBSR) fungono anche da router nella rete ZigBee. Dopo essere stato incluso nella rete ZigBee, consente ad altri dispositivi ZigBee di unirsi alla rete tramite l'interruttore di accensione.

| **Modello numero:** | **Metro** | **Router ZigBee** |
| ------------------- | --------- | ----------------- |
|                     |           |                   |
| **PSS-29ZBS**       | **NO**    | **NO**            |
|                     |           |                   |
| **PSS-29ZBSR**      | **NO**    | **SÌ**            |
|                     |           |                   |
| **PSM-29ZBS**       | **SÌ**    | **NO**            |
|                     |           |                   |
| **PSM-29ZBSR**      | **SÌ**    | **SÌ**            |
|                     |           |                   |

**Identificazione delle parti**

**1. Pulsante funzione ovvero indicatore LED**

Il pulsante funzione funge anche da indicatore LED. Il pulsante funzione viene utilizzato per controllare l'interruttore di accensione. L'indicatore LED viene utilizzato per indicare lo stato dell'interruttore di alimentazione.

**Indicazione LED:**

L'indicatore LED si accende nelle seguenti condizioni:

-   SU:

L'interruttore di alimentazione è acceso.

-   Spento:

L'interruttore di alimentazione è spento.

-   Lampeggia due volte:

L'interruttore di alimentazione si è unito con successo a una rete ZigBee.

-   Lampeggia 5 volte

L'interruttore di alimentazione si è associato correttamente a un controller

-   Lampeggia ogni 20 minuti

L'interruttore di alimentazione ha perso la connessione alla rete ZigBee corrente

(**Solo PSS-29ZBS e PSM-29ZBS**)

**Utilizzo dei pulsanti funzione:**

-   Premere il pulsante per attivare/disattivare l'interruttore di accensione
-   Tenere premuto il pulsante per 10 secondi, quindi rilasciarlo per ripristinare l'interruttore di accensione.
-   Tieni premuto il pulsante per 3 secondi, quindi rilascialo per associarlo a un controller.

_**Tipo F**__**Tipo B**_

![](<.gitbook/assets/0 (74).jpeg>)

_**Tipo L**__**Tipo J**_

1

**Configurazione della rete ZigBee**

![](<.gitbook/assets/1 (66).jpeg>)

-   _**Linee guida per i dispositivi ZigBee**_

ZigBee è un protocollo di comunicazione wireless affidabile, a basso consumo energetico e con elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

![](<.gitbook/assets/2 (59).jpeg>)

-   _**Unirsi alla rete ZigBee**_

In quanto dispositivo ZigBee, il Power Switch deve unirsi a una rete ZigBee per ricevere comandi e trasmettere informazioni sul consumo energetico. Seguire i passaggi seguenti per collegare l'interruttore di alimentazione a una rete ZigBee.

-   1.  Collegare l'interruttore di alimentazione a una presa di corrente.
    2.  Tenere premuto il pulsante funzione per 10 secondi mentre l'interruttore di accensione si reimposta e inizia a cercare la rete ZigBee esistente. Assicurati che la funzione di autorizzazione all'accesso sul router o sul coordinatore della tua rete ZigBee sia abilitata.
    3.  Se l'interruttore di accensione si connette con successo a una rete ZigBee, l'indicatore LED lampeggerà due volte per confermare.
    4.  Dopo aver aderito alla rete ZigBee, il Power Switch verrà registrato automaticamente nella rete. Controlla il coordinatore della rete ZigBee, il pannello di controllo del sistema o il CIE (apparecchiatura di controllo e indicazione) per confermare se l'adesione e la registrazione hanno avuto esito positivo.
    5.  Se la registrazione e l'accesso alla rete non hanno esito positivo, controlla il coordinatore della rete ZigBee, il pannello di controllo del sistema o le impostazioni CIE per assicurarti che la funzione di autorizzazione all'accesso sia disponibile, quindi utilizza la funzione di ripristino delle impostazioni di fabbrica di seguito per accedere alla rete ZigBee.
-   _**Associazione con il controller**_

![](<.gitbook/assets/3 (53).jpeg>)

Dopo essersi unito alla rete ZigBee, l'interruttore di alimentazione può associarsi a un dispositivo controller che può essere utilizzato per accendere/spegnere l'interruttore di alimentazione. Per collegare l'interruttore di accensione e il dispositivo:

-   1.  Tenere premuto il pulsante funzione per 3 secondi, quindi rilasciare il pulsante. Il Power Switch invierà una richiesta vincolante al coordinatore.
    2.  Fare riferimento al manuale del controller per inviare una richiesta vincolante per il dispositivo entro 16 secondi.
    3.  Se il collegamento ha esito positivo, l'indicatore LED dell'interruttore di alimentazione lampeggerà 5 volte per confermare. Ora puoi utilizzare il controller per regolare il livello di potenza in uscita per l'interruttore di accensione.
    4.  Se l'associazione non riesce, riprovare il processo di associazione.
-   _**Rimozione del dispositivo dalla rete ZigBee (ripristino delle impostazioni di fabbrica)**_

![](<.gitbook/assets/4 (62).png>)

Per rimuovere l'interruttore di accensione dalla rete ZigBee corrente, l'interruttore di accensione deve essere impostato su Ripristino delle impostazioni di fabbrica per completare la rimozione del dispositivo. La funzione di ripristino delle impostazioni di fabbrica cancellerà l'interruttore di accensione dalle impostazioni e dalle informazioni memorizzate e richiederà all'interruttore di accensione di cercare una nuova rete ZigBee.

**Prima di rimuovere il dispositivo, assicurarsi che l'interruttore di accensione si trovi nel raggio d'azione del segnale della rete ZigBee corrente**

-   1.  Tenere premuto il pulsante funzione per 10 secondi, quindi rilasciare il pulsante per ripristinare l'interruttore di accensione.
    2.  Al momento del ripristino, l'interruttore di accensione cancellerà l'impostazione corrente della rete ZigBee e trasmetterà il segnale al coordinatore ZigBee per rimuoversi dalla rete ZigBee corrente. Quindi cercherà nuovamente attivamente la rete ZigBee disponibile e si unirà automaticamente alla rete.
-   _**Capacità del dispositivo router ZigBee (solo PSS-29ZBSR / PSM-29ZBSR)**_

![](<.gitbook/assets/5 (62).png>)

I modelli Power Switch con funzione Router consentono ad altri dispositivi ZigBee di unirsi alla rete ZigBee tramite il router. Il Power Switch Router ha una capacità massima di 40 dispositivi, inclusi 10 router; il router del misuratore di alimentazione ha una capacità massima di 10 dispositivi inclusi 5 router.

| **Modello numero:**       | **Dispositivo ZigBee massimo** | **ZigBee massimo** |   |
| ------------------------- | ------------------------------ | ------------------ | - |
| **+ Capacità del router** | **Capacità del router**        |                    |   |
|                           |                                |                    |   |
|                           |                                |                    |   |
| **PSS-29ZBS**             | **40**                         | **10**             |   |
|                           |                                |                    |   |
| **PSM-29ZBSR**            | **10**                         | **5**              |   |
|                           |                                |                    |   |

**Operazione**

![](<.gitbook/assets/6 (42).jpeg>)

-   _**Installazione**_
    -   Collegare l'interruttore di alimentazione a una presa di corrente, quindi collegare l'apparecchio alla presa dell'interruttore di alimentazione. L'apparecchio deve essere nello stato ON.
    -   _**NOTA IMPORTANTE**_**:**L'interruttore di alimentazione non dispone di una batteria di riserva e verrà spento in caso di interruzione dell'alimentazione CA.**NON**utilizzare l'interruttore di alimentazione come router per il sensore di sicurezza o dispositivi di controllo allarme come contatto porta, sensore PIR, ecc., altrimenti i sensori perderanno la connessione alla rete ZigBee se l'interruttore di alimentazione viene scollegato dall'alimentazione CA. Pianificare le posizioni di installazione di questi sensori di sicurezza senza utilizzare l'interruttore di alimentazione e utilizzare solo un router con batteria di backup. La funzione router dell'interruttore di alimentazione dovrebbe**SOLTANTO**essere utilizzato per fornire l'estensione della portata del segnale per altri interruttori di alimentazione/dimmer.

2

-   ![](<.gitbook/assets/7 (39).jpeg>)_**Controllo degli elettrodomestici**_
    -   Dopo che l'interruttore di alimentazione si è unito con successo a una rete ZigBee, il coordinatore può accendere/spegnere da remoto l'interruttore di alimentazione per controllare l'apparecchio
    -   È inoltre possibile premere il pulsante sull'interruttore di accensione per alternarne lo stato di accensione/spegnimento
    -   Se hai associato un controller all'interruttore di accensione, puoi anche utilizzare il controller per accendere/spegnere l'interruttore di accensione.
    -   Se l'interruttore di alimentazione viene rimosso dalla presa di corrente, dopo averlo ricollegato, il suo precedente stato di accensione/spegnimento verrà ripristinato entro 1 minuto.
-   _**Monitoraggio del consumo energetico (solo PSM-29ZBS / PSM-29ZBSR)**_
    -   I modelli Power Switch con contatore integrato trasmetteranno un segnale con i dati sul consumo energetico ogni 10 minuti al coordinatore della rete ZigBee.
    -   Ogni volta che l'output energetico dell'interruttore di alimentazione cambia di +/- 2 W, trasmetterà automaticamente un segnale con i dati sul consumo energetico al coordinatore della rete ZigBee per l'aggiornamento.
    -   L'interruttore di alimentazione trasmette un segnale con i dati di potenza al coordinatore ogni volta che il consumo energetico accumulato aumenta di 0,1 kW/ora.
    -   Il misuratore ha una precisione del +/- 5%.
    -   Per cancellare dall'interruttore di accensione i dati di consumo energetico accumulati, attenersi alla procedura seguente:
        1.  Scollegare l'interruttore di alimentazione dalla presa di corrente.
        2.  Tenere premuto il pulsante funzione e ricollegare l'interruttore di alimentazione tenendo premuto il pulsante.
        3.  Continua a tenere premuto il pulsante e rilascialo dopo 3 secondi. I dati sul consumo energetico accumulati verranno cancellati.
-   _**Carico operativo massimo**_
    -   Per 110 V: il carico massimo di funzionamento è 1760 W e 16 A.
    -   Per 230 V: il carico massimo di funzionamento è 3680 W e 16 A.
    -   Se l'interruttore di alimentazione si surriscalda, interromperà automaticamente l'alimentazione come misura di sicurezza. L'interruttore di alimentazione deve essere scollegato e ricollegato dopo l'interruzione per riprendere il normale funzionamento.

![](<.gitbook/assets/8 (33).jpeg>)![](<.gitbook/assets/9 (26).jpeg>)

**Appendice (solo per sviluppatori)**

![](<.gitbook/assets/10 (38).png>)

_**ID del cluster di interruttori di alimentazione**_

| **ID dispositivo: presa di corrente: 0x0009** | **/ ACCORTO_SPINA: 0x0051** |                             |
| --------------------------------------------- | --------------------------- | --------------------------- |
| **Punto finale: 0x01**                        |                             |                             |
|                                               |                             |                             |
| **Lato server**                               |                             | **Dalla parte del cliente** |
|                                               |                             |                             |
|                                               | **Obbligatorio**            |                             |

Di base (0x0000)

Identificare (0x0003)

Acceso/Spento(0x0006)

Gruppi(0x0004)

Scene(0x0005) (**Solo PSS-29ZBS / PSS-29ZBSR**)

Misurazione(0x0702)(**Solo PSM-29ZBS /PSM-29ZBSR**)

**Opzionale**

Gruppi(0x0004)

_Nessuno_

_Nessuno_

-   _**Attributo delle informazioni di base del cluster**_

| **Identificatore** | **Nome**                     | **Tipo**    | **Allineare** | **Accesso**  | **Predefinito** | **Obbligatorio** |   |
| ------------------ | ---------------------------- | ----------- | ------------- | ------------ | --------------- | ---------------- | - |
| **/ Facoltativo**  |                              |             |               |              |                 |                  |   |
|                    |                              |             |               |              |                 |                  |   |
| 0x0000             | _Versione ZCL_               | Non firmato | 0x00 –0xff    | Sola lettura | 0x01            | M                |   |
| Intero a 8 bit     |                              |             |               |              |                 |                  |   |
|                    |                              |             |               |              |                 |                  |   |
| 0x0001             | Versione dell'applicazione   | Non firmato | 0x00 –0xff    | Sola lettura | 0x00            | O                |   |
| Intero a 8 bit     |                              |             |               |              |                 |                  |   |
|                    |                              |             |               |              |                 |                  |   |
| 0x0003             | _Versione HW_                | Non firmato | 0x00 –0xff    | Sola lettura | 0               | O                |   |
| Intero a 8 bit     |                              |             |               |              |                 |                  |   |
|                    |                              |             |               |              |                 |                  |   |
| 0x0004             | _Nome del produttore_        | Carattere   | 0–32          | Sola lettura | Climax          | O                |   |
| Corda              | byte                         | Tecnologia  |               |              |                 |                  |   |
|                    |                              |             |               |              |                 |                  |   |
| 0x0005             | _Identificatore del modello_ | Carattere   | 0–32          | Sola lettura | (Modello        | O                |   |
| Corda              | byte                         | Versione)   |               |              |                 |                  |   |
|                    |                              |             |               |              |                 |                  |   |
| 0x0006             | _DataCodice_                 | Carattere   | 0–16          | Sola lettura |                 | O                |   |
| Corda              | byte                         |             |               |              |                 |                  |   |
|                    |                              |             |               |              |                 |                  |   |
| 0x0007             | _Fonte di potere_            | 8 bit       | 0x00 –0xff    | Sola lettura |                 | M                |   |
|                    |                              |             | 3             |              |                 |                  |   |

| 0x0010                                                             | _Descrizione della posizione_ | Carattere         | 0–32          |   |              | Leggere scrivere |                 | O                |   |   |
| ------------------------------------------------------------------ | ----------------------------- | ----------------- | ------------- | - | ------------ | ---------------- | --------------- | ---------------- | - | - |
| Corda                                                              | byte                          |                   |               |   |              |                  |                 |                  |   |   |
|                                                                    |                               |                   |               |   |              |                  |                 |                  |   |   |
| 0x0011                                                             | _Ambiente fisico_             | 8 bit             | 0x00 –0xff    |   |              | Leggere scrivere | 0x00            | O                |   |   |
| 0x0012                                                             | _Dispositivo abilitato_       | Booleano          | 0x00 –        |   |              | Leggere scrivere | 0x01            | M                |   |   |
| 0x01                                                               |                               |                   |               |   |              |                  |                 |                  |   |   |
|                                                                    |                               |                   |               |   |              |                  |                 |                  |   |   |
| _**Attributo di Identificazione delle informazioni sul cluster**_ |                               |                   |               |   |              |                  |                 |                  |   |   |
|                                                                    |                               |                   |               |   |              |                  |                 |                  |   |   |
| **Identificatore**                                                 | **Nome**                      | **Tipo**          | **Allineare** |   | **Accesso**  |                  | **Predefinito** | **Obbligatorio** |   |   |
|                                                                    |                               | **/ Facoltativo** |               |   |              |                  |                 |                  |   |   |
|                                                                    |                               |                   |               |   |              |                  |                 |                  |   |   |
| 0x0000                                                             | _Identificare il tempo_       | Non firmato       | 0x00 –0xffff  |   | Leggere /    |                  | 0x0000          | M                |   |   |
| Intero a 16 bit                                                    |                               | Scrivere          |               |   |              |                  |                 |                  |   |   |
|                                                                    |                               |                   |               |   |              |                  |                 |                  |   |   |
| _**Attributi del cluster Gruppi Informazioni**_                   |                               |                   |               |   |              |                  |                 |                  |   |   |
|                                                                    |                               |                   |               |   |              |                  |                 |                  |   |   |
| **Identificatore**                                                 | **Nome**                      | **Tipo**          | **Allineare** |   | **Accesso**  |                  | **Predefinito** | **Obbligatorio** |   |   |
|                                                                    |                               | **/ Facoltativo** |               |   |              |                  |                 |                  |   |   |
|                                                                    |                               |                   |               |   |              |                  |                 |                  |   |   |
| 0x0000                                                             | _NomeSupport_                 | Bitmap a 8 bit    | x0000000      |   | Sola lettura |                  | -               | M                |   |   |

![](<.gitbook/assets/11 (29).png>)![](<.gitbook/assets/12 (34).png>)![](<.gitbook/assets/13 (24).jpeg>)

-   _**Attributi delle informazioni sul cluster Scene**_

![](<.gitbook/assets/14 (20).jpeg>)

| **Identificatore**                                     | **Nome**          | **Tipo**             | **Allineare**   | **Accesso**  | **Predefinito** | **Obbligatorio** |   |
| ------------------------------------------------------ | ----------------- | -------------------- | --------------- | ------------ | --------------- | ---------------- | - |
| **/ Facoltativo**                                      |                   |                      |                 |              |                 |                  |   |
|                                                        |                   |                      |                 |              |                 |                  |   |
| 0x0000                                                 | Conteggio scene   | 8 bit senza segno    | 0x00 – 0xff     | Sola lettura | 0x00            | M                |   |
| numero intero                                          |                   |                      |                 |              |                 |                  |   |
|                                                        |                   |                      |                 |              |                 |                  |   |
| 0x0001                                                 | _Scena corrente_  | 8 bit senza segno    | 0x00 – 0xff     | Sola lettura | 0x00            | M                |   |
| numero intero                                          |                   |                      |                 |              |                 |                  |   |
|                                                        |                   |                      |                 |              |                 |                  |   |
| 0x0002                                                 | _Gruppo corrente_ | Senza segno a 16 bit | 0x0000 – 0xfff7 | Sola lettura | 0x00            | M                |   |
|                                                        | numero intero     |                      |                 |              |                 |                  |   |
|                                                        |                   |                      |                 |              |                 |                  |   |
| 0x0003                                                 | _SceneValid_      | Booleano             | 0x00 – 0x01     | Sola lettura | 0x00            | M                |   |
| 0x0004                                                 | _NomeSupport_     | Bitmap a 8 bit       | x0000000        | Sola lettura | -               | M                |   |
| _**Attributo delle informazioni sul cluster On/Off**_ |                   |                      |                 |              |                 |                  |   |

![](<.gitbook/assets/15 (22).png>)

| **Identificatore** | **Nome**        | **Tipo** | **Allineare** | **Accesso**  | **Predefinito** | **Obbligatorio** |   |
| ------------------ | --------------- | -------- | ------------- | ------------ | --------------- | ---------------- | - |
| **/ Facoltativo**  |                 |          |               |              |                 |                  |   |
|                    |                 |          |               |              |                 |                  |   |
| 0x0000             | _Acceso spento_ | Booleano | 0x00 –0x01    | Sola lettura | 0x00            | M                |   |

![](<.gitbook/assets/16 (24).png>)

_**Attributi delle informazioni del cluster di misurazione (Attributo informazioni di lettura**_

![](<.gitbook/assets/17 (16).jpeg>)

_**impostato) (Solo PSM-29ZBS / PSM-29ZBSR)**_

| **Identificatore** | **Nome**        | **Tipo**       | **Allineare**    | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| ------------------ | --------------- | -------------- | ---------------- | ----------- | --------------- | ---------------- | - |
| **/ Facoltativo**  |                 |                |                  |             |                 |                  |   |
|                    |                 |                |                  |             |                 |                  |   |
| 0x00               | Somma corrente  | Non firmato    | 0x000000000000 a | Leggere     |                 | M                |   |
| Consegnato         | Intero a 48 bit | 0xFFFFFFFFFFFF | Soltanto         |             |                 |                  |   |
|                    |                 |                |                  |             |                 |                  |   |

![](<.gitbook/assets/18 (24).png>)

_**Attributi delle informazioni sul cluster di misurazione (set di attributi di formattazione)**_

![](<.gitbook/assets/19 (7).jpeg>)

_**(Solo PSM-29ZBS / PSM-29ZBSR)**_

| **Identificatore** | **Nome**                        | **Tipo**       | **Allineare**  | **Accesso**  | **Predefinito** | **Obbligatorio** |   |
| ------------------ | ------------------------------- | -------------- | -------------- | ------------ | --------------- | ---------------- | - |
| **/ Facoltativo**  |                                 |                |                |              |                 |                  |   |
|                    |                                 |                |                |              |                 |                  |   |
| 0x00               | Unità di misura                 | 8 bit          | Da 0x00 a 0xFF | Sola lettura | 0x00            | M                |   |
| Enumerazione       |                                 |                |                |              |                 |                  |   |
|                    |                                 |                |                |              |                 |                  |   |
| 0x01               | Moltiplicatore                  | Non firmato    | 0x000000 a     | Sola lettura | 1               | O                |   |
| Intero a 24 bit    | 0xFFFFFF                        |                |                |              |                 |                  |   |
|                    |                                 |                |                |              |                 |                  |   |
| 0x02               | Divisore                        | Non firmato    | 0x000000 a     | Sola lettura | 10000           | O                |   |
| Intero a 24 bit    | 0xFFFFFF                        |                |                |              |                 |                  |   |
|                    |                                 |                |                |              |                 |                  |   |
| 0x03               | SommaFormazione                 | Bitmap a 8 bit | Da 0x00 a 0xFF | Sola lettura | 0xF9            | M                |   |
| 0x04               | DemandFormating                 | Bitmap a 8 bit | Da 0x00 a 0xFF | Sola lettura | 0Ksasa          | O                |   |
| 0x06               | Tipo dispositivo di misurazione | Bitmap a 8 bit | Da 0x00 a 0xFF | Sola lettura | 0x00            | M                |   |

![](<.gitbook/assets/20 (17).png>)

-   _**Attributi delle informazioni sul cluster di misurazione (insieme di attributi storici) (solo PSM-29ZBS / PSM-29ZBSR)**_

| **Identificatore** | **Nome**           | **Tipo**         | **Allineare** | **Accesso**  | **Predefinito** | **Obbligatorio** |   |
| ------------------ | ------------------ | ---------------- | ------------- | ------------ | --------------- | ---------------- | - |
| **/ Facoltativo**  |                    |                  |               |              |                 |                  |   |
|                    |                    |                  |               |              |                 |                  |   |
| 0x00               | Domanda istantanea | Firmato a 24 bit | -8.388.607 a  | Sola lettura | 0x00            | O                |   |
| Numero intero      | 8,388,607          |                  |               |              |                 |                  |   |
|                    |                    |                  |               |              |                 |                  |   |

4
