# VESTA173

**RSB-1ZBS**

**Lampadina intelligente RGBW**

**introduzione**

![](<.gitbook/assets/0 (64).jpeg>)

RSB-1ZBS è una lampadina LED colorata ZigBee Smart. È dotato sia di regolazione multicolore che di controllo del livello di luce. Una volta entrato in una rete ZigBee, l'utente sarà in grado di controllare Light Bulb in remoto dal coordinatore della rete ZigBee.

La lampadina utilizza la tecnologia ZigBee per la trasmissione del segnale wireless. ZigBee è un protocollo di comunicazione wireless affidabile che presenta un basso consumo energetico e un'elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in rete una grande quantità di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali

La lampadina funge anche da percorso nella rete ZigBee. Dopo essere stato incluso nella rete ZigBee, consente ad altri dispositivi ZigBee di unirsi alla rete tramite Lampadina.

**Configurazione della rete ZigBee**

![](<.gitbook/assets/1 (57).jpeg>)

-   _**Linee guida per i dispositivi ZigBee**_

ZigBee è un protocollo di comunicazione wireless affidabile, a basso consumo energetico e con elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

A causa della struttura fondamentale della rete ZigBee, il dispositivo ZigBee cercherà e si unirà attivamente alla rete dopo l'accensione.

-   -   Assicurati che il router o il coordinatore della rete ZigBee sia acceso prima di accendere il dispositivo ZigBee.
    -   Assicurati che il router o il coordinatore della rete ZigBee sia acceso e nel raggio d'azione mentre un dispositivo ZigBee è in uso.
    -   Non rimuovere un dispositivo ZigBee dal router o dal coordinatore della rete ZigBee senza spegnere il dispositivo ZigBee.
-   _**Unirsi alla rete ZigBee**_

![](<.gitbook/assets/2 (52).jpeg>)

In quanto dispositivo ZigBee, la lampadina deve unirsi a una rete ZigBee per inviare e ricevere segnali di comando. Segui i passaggi seguenti per aggiungere la lampadina alla rete ZigBee.

Passaggio 1. Scorrere la lampadina nel portalampada. Non fornire ancora alimentazione.

Passaggio 2. Abilita la funzione di autorizzazione alla partecipazione sul router o sul coordinatore della tua rete ZigBee.

Passaggio 3. Accendere la lampadina per 3~5 secondi. (Non più di 5 secondi), quindi spegnere.

Passaggio 4. Ripetere il passaggio 3 per tre (3) volte per un totale di quattro (4) cicli ON/OFF.

Passaggio 5. Accendere la lampadina per la quinta volta, il dispositivo si ripristinerà e inizierà a cercare una nuova rete ZigBee.

Passaggio 6. Dopo essersi uniti alla rete ZigBee, la lampadina verrà registrata automaticamente nel sistema di sicurezza della rete. Controlla il coordinatore della rete ZigBee, il pannello di controllo del sistema o il CIE (apparecchiatura di controllo e indicazione) per confermare se l'adesione e la registrazione sono andate a buon fine.

![](<.gitbook/assets/3 (61).png>)![](<.gitbook/assets/4 (46).jpeg>)

-   _**Rimozione del dispositivo dalla rete ZigBee (ripristino delle impostazioni di fabbrica)**_

Per rimuovere la lampadina dall'attuale rete ZigBee, il dispositivo deve essere sottoposto al ripristino delle impostazioni di fabbrica per completare la rimozione del dispositivo. La funzione di ripristino delle impostazioni di fabbrica cancellerà la lampadina dalle impostazioni e dalle informazioni memorizzate e spingerà la lampadina a cercare una nuova rete ZigBee.

**Prima di rimuovere il dispositivo, assicurarsi che la lampadina si trovi nel raggio d'azione del segnale della rete ZigBee corrente**

1.  Elimina la lampadina dal pannello di controllo/CIE corrente.
2.  Spegnere la lampadina.
3.  Accendi la lampadina per 3~5 secondi. (Non più di 5 secondi), quindi spegnere.
4.  Ripetere il passaggio 3 per 3 volte per un totale di 4 cicli ON/OFF
5.  Accendere la lampadina per la quinta volta, il dispositivo si ripristinerà e inizierà a cercare la nuova rete ZigBee.
6.  Al momento del ripristino, la lampadina cancellerà l'impostazione corrente della rete ZigBee e trasmetterà il segnale al coordinatore ZigBee per rimuoversi dalla rete ZigBee corrente. Quindi cercherà nuovamente attivamente la rete ZigBee disponibile e si unirà automaticamente alla rete.

1

![](<.gitbook/assets/5 (29).jpeg>)![](<.gitbook/assets/6 (39).jpeg>)

-   _**Capacità del dispositivo router ZigBee**_

La funzione Lampadina con Router consente ad altri dispositivi ZigBee di unirsi alla rete ZigBee tramite il Router. La lampadina ha una capacità massima di 7 dispositivi, inclusi 4 router.

**Caratteristiche**

![](<.gitbook/assets/7 (35).png>)

-   _**Regolazione del colore e della saturazione**_

Il colore e la saturazione della lampadina possono essere regolati da remoto dai coordinatori ZigBee inviando comandi.

![](<.gitbook/assets/8 (38).png>)

-   _**Regolazione del livello di luce**_

La Lampadina ha un'illuminazione dimmerabile, la percentuale di luce può essere regolata da remoto dai Coordinatori ZigBee inviando comandi.

![](<.gitbook/assets/9 (36).png>)

-   _**Supervisione**_

La lampadina trasmetterà un segnale di supervisione per segnalare regolarmente le sue condizioni in base alle impostazioni dell'utente. L'intervallo predefinito in fabbrica è 10 minuti.

**Appendice (solo per sviluppatori)**

![](<.gitbook/assets/10 (37).png>)

-   _**ID del gruppo lampadine**_

**ID dispositivo: colore_Dimmerabile_Luce: 0x0102**

**Punto finale: 0x01**

| **Lato server**            |                                                                     |                                                                  | **Dalla parte del cliente** |           |   |   |
| -------------------------- | ------------------------------------------------------------------- | ---------------------------------------------------------------- | --------------------------- | --------- | - | - |
|                            |                                                                     |                                                                  |                             |           |   |   |
|                            |                                                                     | **Obbligatorio**                                                 |                             |           |   |   |
|                            |                                                                     |                                                                  |                             |           |   |   |
| Di base (0x0000)           |                                                                     |                                                                  |                             | _Nessuno_ |   |   |
|                            |                                                                     |                                                                  |                             |           |   |   |
| Identificare(0x0003)       |                                                                     |                                                                  |                             |           |   |   |
|                            |                                                                     |                                                                  |                             |           |   |   |
| Gruppi(0x0004)             |                                                                     |                                                                  |                             |           |   |   |
|                            |                                                                     |                                                                  |                             |           |   |   |
| Scene(0x0005)              |                                                                     |                                                                  |                             |           |   |   |
|                            |                                                                     |                                                                  |                             |           |   |   |
| OnOff(0x0006)              |                                                                     |                                                                  |                             |           |   |   |
|                            |                                                                     |                                                                  |                             |           |   |   |
| Controllo livello (0x0008) |                                                                     |                                                                  |                             |           |   |   |
|                            |                                                                     |                                                                  |                             |           |   |   |
| Controllo colore(0x0300)   |                                                                     |                                                                  |                             |           |   |   |
|                            |                                                                     |                                                                  |                             |           |   |   |
|                            |                                                                     | **Opzionale**                                                    |                             |           |   |   |
|                            |                                                                     |                                                                  |                             |           |   |   |
| _Nessuno_                  |                                                                     |                                                                  |                             | _Nessuno_ |   |   |
|                            |                                                                     |                                                                  |                             |           |   |   |
|                            |                                                                     |                                                                  |                             |           |   |   |
| **Cluster di rapporti**    |                                                                     | Acceso/Spento (0x0006)                                           |                             |           |   |   |
| **Attributo del rapporto** |                                                                     | ATTRIDO_SU_SPENTO (0x0000)                                       |                             |           |   |   |
| **Tipo di dati**           |                                                                     | ZCL_TIPO DI DATI_BOOLEANO                                        |                             |           |   |   |
| **minReportInt**           |                                                                     | 0                                                                |                             |           |   |   |
| **maxReportInt**           |                                                                     | valore predefinito: 0x258 secondi (600 secondi)                  |                             |           |   |   |
|                            |                                                                     |                                                                  |                             |           |   |   |
| **Cluster di rapporti**    |                                                                     | Controllo livello (0x0008)                                       |                             |           |   |   |
| **Attributo del rapporto** |                                                                     | ATTRIDO_LIVELLO_ATTUALE_LIVELLO (0x0000)                         |                             |           |   |   |
| **Tipo di dati**           |                                                                     | ZCL_TIPO DI DATI_INVERNO8                                        |                             |           |   |   |
| **minReportInt**           |                                                                     | 0                                                                |                             |           |   |   |
| **maxReportInt**           |                                                                     | valore predefinito: 0x258 secondi (600 secondi)                  |                             |           |   |   |
|                            |                                                                     |                                                                  |                             |           |   |   |
| **Cluster di rapporti**    |                                                                     | Controllo colore (0x0300)                                        |                             |           |   |   |
| **Attributo del rapporto** |                                                                     | ATTRIDO_ILLUMINAZIONE_COLORE_CONTROLLO_ATTUALE_TONALITÀ (0x0000) |                             |           |   |   |
| **Tipo di dati**           |                                                                     | ZCL_TIPO DI DATI_INVERNO8                                        |                             |           |   |   |
|                            | ATTRIDO_ILLUMINAZIONE_COLORE_CONTROLLO_ATTUALE_SATURAZIONE (0x0001) |                                                                  |                             |           |   |   |
|                            |                                                                     |                                                                  |                             |           |   |   |
| **Tipo di dati**           |                                                                     | ZCL_TIPO DI DATI_INVERNO8                                        |                             |           |   |   |
|                            | ATTRIDO_ILLUMINAZIONE_COLORE_CONTROLLO_COLORE_TEMPERATURA (0x0007)  |                                                                  |                             |           |   |   |
|                            |                                                                     |                                                                  |                             |           |   |   |
| **Tipo di dati**           |                                                                     | ZCL_TIPO DI DATI_UINT16                                          |                             |           |   |   |
| **minReportInt**           |                                                                     | 0                                                                |                             |           |   |   |
| **maxReportInt**           |                                                                     | valore predefinito: 0x258 secondi (600 secondi)                  |                             |           |   |   |
|                            |                                                                     | 2                                                                |                             |           |   |   |

![](<.gitbook/assets/11 (22).jpeg>)![](<.gitbook/assets/12 (18).jpeg>)

-   ![](<.gitbook/assets/13 (25).png>)_**Attributo delle informazioni di base del cluster**_

| **Identificatore**                                                 | **Nome**                      | **Tipo**          | **Allineare** | **Accesso**      | **Predefinito**   | **Obbligatorio** |   |
| ------------------------------------------------------------------ | ----------------------------- | ----------------- | ------------- | ---------------- | ----------------- | ---------------- | - |
| **/ Facoltativo**                                                  |                               |                   |               |                  |                   |                  |   |
|                                                                    |                               |                   |               |                  |                   |                  |   |
| 0x0000                                                             | _Versione ZCL_                | 8 bit senza segno | 0x00 –0xff    | Sola lettura     | 0x01              | M                |   |
| numero intero                                                      |                               |                   |               |                  |                   |                  |   |
|                                                                    |                               |                   |               |                  |                   |                  |   |
| 0x0003                                                             | Versione HW                   | 8 bit senza segno | 0x00 –0xff    | Sola lettura     | 0                 | O                |   |
| numero intero                                                      |                               |                   |               |                  |                   |                  |   |
|                                                                    |                               |                   |               |                  |                   |                  |   |
| 0x0004                                                             | _Nome del produttore_         | Carattere         | 0 – 32 byte   | Sola lettura     | Tecnologia Climax | O                |   |
| Corda                                                              |                               |                   |               |                  |                   |                  |   |
|                                                                    |                               |                   |               |                  |                   |                  |   |
| 0x0005                                                             | _Identificatore del modello_  | Carattere         | 0 – 32 byte   | Sola lettura     | SLCB_00.00.03.01  | O                |   |
| Corda                                                              | TC                            |                   |               |                  |                   |                  |   |
|                                                                    |                               |                   |               |                  |                   |                  |   |
| 0x0006                                                             | _DataCodice_                  | Carattere         | 0 – 16 byte   | Sola lettura     | 20170124          | O                |   |
| Corda                                                              |                               |                   |               |                  |                   |                  |   |
|                                                                    |                               |                   |               |                  |                   |                  |   |
| 0x0007                                                             | _Fonte di potere_             | 8 bit             | 0x00 –0xff    | Sola lettura     |                   | M                |   |
| Enumerazione                                                       |                               |                   |               |                  |                   |                  |   |
|                                                                    |                               |                   |               |                  |                   |                  |   |
| 0x0010                                                             | _Descrizione della posizione_ | Carattere         | 0 – 32 byte   | Leggere scrivere |                   | O                |   |
| corda                                                              |                               |                   |               |                  |                   |                  |   |
|                                                                    |                               |                   |               |                  |                   |                  |   |
| 0x0011                                                             | _Ambiente fisico_             | 8 bit             | 0x00 –0xff    | Leggere scrivere | 0x00              | O                |   |
| Enumerazione                                                       |                               |                   |               |                  |                   |                  |   |
|                                                                    |                               |                   |               |                  |                   |                  |   |
| 0x0012                                                             | _Dispositivo abilitato_       | Booleano          | 0x00 –0x01    | Leggere scrivere | 0x01              | M                |   |
| _**Attributo di Identificazione delle informazioni sul cluster**_ |                               |                   |               |                  |                   |                  |   |

![](<.gitbook/assets/14 (20).png>)

| **Identificatore**                                        | **Nome**                | **Tipo**    | **Allineare** | **Accesso**      | **Predefinito** | **Obbligatorio /** |   |
| --------------------------------------------------------- | ----------------------- | ----------- | ------------- | ---------------- | --------------- | ------------------ | - |
| **Opzionale**                                             |                         |             |               |                  |                 |                    |   |
|                                                           |                         |             |               |                  |                 |                    |   |
| 0x0000                                                    | _Identificare il tempo_ | Non firmato | 0x00 –0xffff  | Leggere scrivere | 0x0000          | M                  |   |
| Intero a 16 bit                                           |                         |             |               |                  |                 |                    |   |
|                                                           |                         |             |               |                  |                 |                    |   |
| _**Attributo delle informazioni sul cluster di gruppo**_ |                         |             |               |                  |                 |                    |   |

![](<.gitbook/assets/15 (19).png>)

| **Identificatore**                                                       | **Nome**                  |                             |                            |                 |                | **Tipo**       |          |              |             | **Allineare** |                   |                   | **Accesso**   |              |                 | **Predefinito** | **Obbligatorio /** |                    |   |   |   |   |   |   |   |
| ------------------------------------------------------------------------ | ------------------------- | --------------------------- | -------------------------- | --------------- | -------------- | -------------- | -------- | ------------ | ----------- | ------------- | ----------------- | ----------------- | ------------- | ------------ | --------------- | --------------- | ------------------ | ------------------ | - | - | - | - | - | - | - |
|                                                                          |                           |                             |                            |                 |                |                |          |              |             |               |                   | **Opzionale**     |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
|                                                                          |                           |                             |                            |                 |                |                |          |              |             |               |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
| 0x0000                                                                   | _NomeSupport_             |                             |                            |                 | Bitmap a 8 bit |                |          | X0000000     |             | Sola lettura  |                   |                   |               | -            |                 | M               |                    |                    |   |   |   |   |   |   |   |
| _**Attributo delle informazioni sul cluster delle scene**_              |                           |                             |                            |                 |                |                |          |              |             |               |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
| **Identificatore**                                                       | **Nome**                  |                             |                            |                 |                | **Tipo**       |          |              |             | **Allineare** |                   |                   | **Accesso**   |              | **Predefinito** |                 | **Obbligatorio**   |                    |   |   |   |   |   |   |   |
|                                                                          |                           |                             |                            |                 |                |                |          |              |             |               | **/ Facoltativo** |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
|                                                                          |                           |                             |                            |                 |                |                |          |              |             |               |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
| 0x0000                                                                   | _Conteggio scene_         |                             | Intero a 8 bit senza segno |                 | 0x00 – 0xff    |                |          | Sola lettura |             | 0x00          |                   | M                 |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
| 0x0001                                                                   | _Scena corrente_          |                             | Intero a 8 bit senza segno |                 | 0x00 – 0xff    |                |          | Sola lettura |             | 0x00          |                   | M                 |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
| 0x0002                                                                   | _Gruppo corrente_         | Intero a 16 bit senza segno |                            | 0x0000 – 0xfff7 |                | Sola lettura   |          | 0x00         |             | M             |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
| 0x0003                                                                   | _SceneValid_              |                             |                            |                 |                | Booleano       |          |              |             | 0x00 – 0x01   |                   |                   | Sola lettura  |              | 0x00            |                 | M                  |                    |   |   |   |   |   |   |   |
| 0x0004                                                                   | _NomeSupport_             |                             |                            |                 |                | Bitmap a 8 bit |          |              |             | X0000000      |                   |                   | Sola lettura  |              | -               |                 | M                  |                    |   |   |   |   |   |   |   |
| _**Attributo delle informazioni sul cluster On/Off**_                   |                           |                             |                            |                 |                |                |          |              |             |               |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
| **Identificatore**                                                       | **Nome**                  |                             |                            |                 |                | **Tipo**       |          |              |             |               | **Allineare**     |                   |               |              | **Accesso**     |                 | **Predefinito**    | **Obbligatorio /** |   |   |   |   |   |   |   |
|                                                                          |                           |                             |                            |                 |                |                |          |              |             |               |                   |                   | **Opzionale** |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
|                                                                          |                           |                             |                            |                 |                |                |          |              |             |               |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
| 0x0000                                                                   | _Acceso spento_           |                             |                            |                 |                | Booleano       |          |              | 0x00 – 0x01 |               |                   | Sola lettura      |               | 0x00         |                 | M               |                    |                    |   |   |   |   |   |   |   |
| _**Attributo delle informazioni sul cluster di controllo del livello**_ |                           |                             |                            |                 |                |                |          |              |             |               |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
| **Identificatore**                                                       | **Nome**                  |                             |                            |                 |                | **Tipo**       |          |              |             | **Allineare** |                   |                   | **Accesso**   |              | **Predefinito** |                 | **Obbligatorio**   |                    |   |   |   |   |   |   |   |
|                                                                          |                           |                             |                            |                 |                |                |          |              |             |               | **/ Facoltativo** |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
|                                                                          |                           |                             |                            |                 |                |                |          |              |             |               |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
| 0x0000                                                                   | _Livello attuale_         |                             | Intero a 8 bit senza segno |                 | 0x00 – 0xff    |                |          | Sola lettura |             | 0x00          |                   | M                 |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
| _**Attributo delle informazioni sul cluster di controllo del colore**_  |                           |                             |                            |                 |                |                |          |              |             |               |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
| **Identificatore**                                                       | **Nome**                  |                             |                            |                 |                | **Tipo**       |          |              |             | **Allineare** |                   |                   |               | **Accesso**  |                 | **Predefinito** |                    | **Obbligatorio**   |   |   |   |   |   |   |   |
|                                                                          |                           |                             |                            |                 |                |                |          |              |             |               |                   | **/ Facoltativo** |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
|                                                                          |                           |                             |                            |                 |                |                |          |              |             |               |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
| 0x0000                                                                   | _Tonalità corrente_       |                             |                            |                 |                | Non firmato    |          |              |             | 0x00 – 0xff   |                   |                   |               | Sola lettura |                 |                 | 0x00               |                    | M |   |   |   |   |   |   |
|                                                                          |                           |                             |                            | Intero a 8 bit  |                |                |          |              |             |               |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
|                                                                          |                           |                             |                            |                 |                |                |          |              |             |               |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
| 0x0001                                                                   | _Saturazione corrente_    |                             |                            |                 | Non firmato    |                |          |              | 0x00 – 0xfe |               |                   |                   | Sola lettura  |              |                 | 0x00            |                    | M                  |   |   |   |   |   |   |   |
|                                                                          |                           |                             | Intero a 8 bit             |                 |                |                |          |              |             |               |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
|                                                                          |                           |                             |                            |                 |                |                |          |              |             |               |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
| 0x0007                                                                   | _ColoreTemperaturaMireds_ |                             | Non firmato                |                 |                |                | 0x0000 – |              |             |               | Sola lettura      | 0x00fa (4000K)    |               | M            |                 |                 |                    |                    |   |   |   |   |   |   |   |
|                                                                          | Intero a 16 bit           |                             |                            |                 | 0xfeff         |                |          |              |             |               |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
|                                                                          |                           |                             |                            |                 |                |                |          |              |             |               |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
| 0x0008                                                                   | _Modalità colore_         |                             |                            |                 |                | 8 bit          |          |              | 0x00 – 0x02 |               | Sola lettura      |                   |               | 0x01         |                 | M               |                    |                    |   |   |   |   |   |   |   |
|                                                                          |                           |                             |                            | enumerazione    |                |                |          |              |             |               |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |
|                                                                          |                           |                             |                            |                 |                |                |          |              |             |               |                   |                   |               |              |                 |                 |                    |                    |   |   |   |   |   |   |   |

![](<.gitbook/assets/16 (22).png>)![](<.gitbook/assets/17 (18).png>)![](<.gitbook/assets/18 (22).png>)![](<.gitbook/assets/19 (23).png>)

3
