# VESTA181

**ZigBee Relay Toggle Switch PRL-1ZBS(R)-AC**

**introduzione**

PRL-1ZBS è un interruttore a levetta relè ZigBee. L'interruttore a levetta del relè può essere collegato a un dispositivo cablato e impostato sullo stato Normalmente aperto (N.O.) o Normalmente chiuso (N.C.). Dopo aver aderito alla rete ZigBee, l'interruttore a levetta relè può essere controllato tramite la rete ZigBee per attivare i dispositivi collegati.

L'interruttore a levetta relè utilizza la tecnologia ZigBee per la trasmissione del segnale wireless. ZigBee è un protocollo di comunicazione wireless affidabile, a basso consumo energetico e con elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

Il Relay Toggle Switch funge da dispositivo terminale nella rete ZigBee. Può essere incluso nella rete ZigBee per trasmettere o ricevere segnali, ma non può consentire a nessun altro dispositivo ZigBee di unirsi alla rete tramite l'interruttore a levetta relè.

I modelli con funzione router fungono anche da router nella rete ZigBee. Dopo essere stato incluso nella rete ZigBee, consente ad altri dispositivi ZigBee di unirsi alla rete tramite l'interruttore di accensione.

**Identificazione delle parti**

![](<.gitbook/assets/0 (70).jpeg>)

**1. Indicatore LED**

L'indicatore LED viene utilizzato per indicare lo stato del relè:

-   -   Lampeggia una volta: il relè è stato ripristinato.
    -   Lampeggia due volte: il Relay si è unito con successo a una rete ZigBee.
    -   Lampeggia una volta ogni 20 minuti:

Il Relay ha perso la connessione alla sua attuale rete ZigBee.

1.  **Pulsante funzione**

Il pulsante funzione viene utilizzato per ripristinare l'interruttore a levetta del relè per connettersi a una rete ZigBee disponibile.

Tenere premuto il pulsante per 10 secondi, quindi rilasciarlo per ripristinare l'interruttore a levetta del relè.

**Terminali di connessione**

Premere il pulsante per aprire il clipper per ciascun terminale e collegare il cablaggio. Rilascia il pulsante per chiudere il tagliacapelli e mantenere il filo in posizione.

1.  **Riservato**
2.  **Linea (ingresso CA)**
3.  **Neutro**
4.  **NO**

Per la connessione Normal Open con il dispositivo

1.  **Comune**
2.  **NC**

Per la connessione Normal Close con il dispositivo

**Specifica**

-   Fonte di alimentazione (alimentazione esterna): 100-240 V CA
-   Uscita relè: relè SPDT senza potenziale, carico operativo massimo: 5 A (resistivo) a 24 V CC o 240 V CA
-   Filo intrecciato: 16-26 AWG
-   Temperatura operativa: da -10°C a 45°C (da 14°F a 113°F)
-   Umidità: fino all'85% senza condensa
-   Dimensioni: 71,1 mm x 49 mm x 26 mm

1

![](<.gitbook/assets/1 (62).jpeg>)

**Ambiente di installazione**

-   Il controller relè deve essere installato all'interno in un luogo asciutto.
-   Si consiglia di installare l'apparecchio in una scatola di plastica ignifuga.
-   Non installare il dispositivo in una scatola metallica per ottimizzare la portata RF.

![](<.gitbook/assets/2 (55).jpeg>)

**Attenzione**

-   Tutti gli interventi sul dispositivo, comprese l'installazione e la manutenzione, devono essere eseguiti da un elettricista qualificato e autorizzato.
-   Per evitare scosse elettriche e/o danni all'apparecchiatura, scollegare l'alimentazione elettrica dal fusibile principale o dall'interruttore prima dell'installazione e della manutenzione.
-   Non collegare il dispositivo a carichi che superano la corrente di carico supportata.

![](<.gitbook/assets/3 (50).jpeg>)

**Installazione**

La specifica del cablaggio dei fori di inserimento è AWG 16-26 o Ø 1,31-0,129 (mm²).

Cablare il relè secondo le istruzioni riportate di seguito o fare riferimento allo schema per ulteriori informazioni.

1.  Si prega di spegnere l'alimentazione prima del collegamento.
2.  Collegare i terminali L e N dell'alimentatore rispettivamente ai terminali Linea e Neutro di PRL.
3.  A seconda del dispositivo che si desidera controllare tramite il relè, selezionare il terminale NO o NC e collegare il relè al dispositivo per stabilire una connessione Normalmente aperta o Normalmente chiusa con il dispositivo.
4.  Dopo aver completato il cablaggio, accendere l'alimentazione per accendere l'interruttore a levetta del relè.

_\\<IMPORTANT NOTE>_

-   Il cablaggio del PRL deve essere eseguito solo da un tecnico certificato con conoscenza e formazione adeguate sulle apparecchiature elettriche.

**Configurazione della rete ZigBee**

-   _**Linee guida per i dispositivi ZigBee**_

ZigBee è un protocollo di comunicazione wireless affidabile, a basso consumo energetico e con elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

-   _**Unirsi alla rete ZigBee**_

Essendo un dispositivo ZigBee, il relè deve unirsi a una rete ZigBee per ricevere comandi. Seguire i passaggi seguenti per unire il Relay a una rete ZigBee.

-   1.  Collegare l'ingresso di alimentazione all'interruttore a levetta del relè secondo le istruzioni di installazione sopra riportate e accendere l'interruttore a levetta del relè.
    2.  Tenere premuto il pulsante funzione per 10 secondi mentre il relè si reimposta e inizia a cercare la rete ZigBee esistente. Assicurati che la funzione di autorizzazione all'accesso sul router o sul coordinatore della tua rete ZigBee sia abilitata.
    3.  If the Relay Toggle Switch successfully joins a ZigBee network, the LED Indicator will flash twice to confirm.
    4.  Dopo aver aderito alla rete ZigBee, l'interruttore di commutazione relè verrà registrato automaticamente nella rete. Controlla il coordinatore della rete ZigBee, il pannello di controllo del sistema o il CIE (apparecchiatura di controllo e indicazione) per confermare se l'adesione e la registrazione hanno avuto esito positivo.
    5.  Dopo aver aderito alla rete ZigBee, se l'interruttore a levetta relè perde la connessione alla rete ZigBee corrente, l'indicatore LED lampeggerà ogni 20 minuti. Controllare le condizioni della rete ZigBee e la portata del segnale dell'interruttore a levetta del relè per correggere la condizione.
-   _**Rimozione del dispositivo dalla rete ZigBee (ripristino delle impostazioni di fabbrica)**_

Per rimuovere l'interruttore a levetta relè dalla rete ZigBee corrente, il dispositivo deve essere impostato su Ripristino delle impostazioni di fabbrica per completare la rimozione del dispositivo. La funzione di ripristino delle impostazioni di fabbrica cancellerà il dispositivo dalle impostazioni e dalle informazioni memorizzate e gli chiederà di cercare una nuova rete ZigBee.

2

**Prima di rimuovere il dispositivo, assicurarsi che l'interruttore a levetta del relè si trovi nel raggio d'azione del segnale della rete ZigBee corrente**

-   1.  Tenere premuto il pulsante funzione per 10 secondi, quindi rilasciare il pulsante per ripristinare l'interruttore a levetta del relè.
    2.  Al momento del ripristino, il dispositivo cancellerà l'impostazione corrente della rete ZigBee e trasmetterà il segnale al coordinatore ZigBee per rimuoversi dalla rete ZigBee corrente. Quindi cercherà nuovamente attivamente la rete ZigBee disponibile e si unirà automaticamente alla rete.
-   _**Capacità del dispositivo router ZigBee (solo PRL-1ZBSR-AC)**_

Il modello Relay Toggle Switch con funzione Router consente ad altri dispositivi ZigBee di unirsi alla rete ZigBee tramite il router. Ha una capacità massima di 40 dispositivi/router.

**Operazione**

-   _**Controllo relè**_
    -   Dopo che l'interruttore a levetta del relè si è unito con successo a una rete ZigBee, il coordinatore/pannello di controllo può controllare in remoto il relè per accenderlo, spegnerlo o alternare tra le condizioni On e Off. Per i dettagli fare riferimento al coordinatore/pannello di controllo ZigBee.

**Appendice (solo per sviluppatori)**

-   _**ID del cluster di inoltro**_

**ID dispositivo: On Off Uscita: 0x0002**

**Punto finale: 0x0A**

| **Lato server**                                                    |                 |                               |                   |            |               |             | **Dalla parte del cliente** |           |                  |   |
| ------------------------------------------------------------------ | --------------- | ----------------------------- | ----------------- | ---------- | ------------- | ----------- | --------------------------- | --------- | ---------------- | - |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               | **Obbligatorio**  |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| Di base (0x0000)                                                   |                 |                               |                   |            |               |             |                             | _Nessuno_ |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| Identificare (0x0003)                                              |                 |                               |                   |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| Acceso/Spento(0x0006)                                              |                 |                               |                   |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               | **Opzionale**     |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| Gruppi(0x0004)                                                     |                 |                               |                   |            |               |             |                             | Nessuno   |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| _**Attributo delle informazioni di base del cluster**_            |                 |                               |                   |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| **Identificatore**                                                 |                 | **Nome**                      | **Tipo**          |            | **Allineare** | **Accesso** | **Predefinito**             |           | **Obbligatorio** |   |
|                                                                    |                 |                               | **/ Facoltativo** |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| 0x0000                                                             |                 | _Versione ZCL_                | 8 bit senza segno |            | 0x00 –0xff    | Leggere     | 0x01                        |           | M                |   |
|                                                                    | numero intero   |                               | soltanto          |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| 0x0001                                                             |                 | Versione dell'applicazione    | 8 bit senza segno |            | 0x00 – 0xff   | Leggere     | 0x00                        |           | O                |   |
|                                                                    | numero intero   |                               | soltanto          |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| 0x0003                                                             |                 | _Versione HW_                 | 8 bit senza segno |            | 0x00 –0xff    | Leggere     | 0                           |           | O                |   |
|                                                                    | numero intero   |                               | soltanto          |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| 0x0004                                                             |                 | _Nome del produttore_         | Carattere         |            | 0 – 32 byte   | Leggere     | Climax                      |           | O                |   |
|                                                                    | Corda           |                               | soltanto          | Tecnologia |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| 0x0005                                                             |                 | _Identificatore del modello_  | Carattere         |            | 0 – 32 byte   | Leggere     | (Versione del modello)      |           | O                |   |
|                                                                    | Corda           |                               | soltanto          |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| 0x0006                                                             |                 | _DataCodice_                  | Carattere         |            | 0 – 16 byte   | Leggere     |                             |           | O                |   |
|                                                                    | Corda           |                               | soltanto          |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| 0x0007                                                             |                 | _Fonte di potere_             | 8 bit             |            | 0x00 –0xff    | Leggere     |                             |           | M                |   |
|                                                                    |                 | soltanto                      |                   |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| 0x0010                                                             |                 | _Descrizione della posizione_ | Carattere         |            | 0 – 32 byte   | Leggere /   |                             |           | O                |   |
|                                                                    | Corda           |                               | Scrivere          |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| 0x0011                                                             |                 | _Ambiente fisico_             | 8 bit             |            | 0x00 –0xff    | Leggere /   | 0x00                        |           | O                |   |
|                                                                    |                 | Scrivere                      |                   |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| 0x0012                                                             |                 | _Dispositivo abilitato_       | Booleano          |            | 0x00 –0x01    | Leggere /   | 0x01                        |           | M                |   |
|                                                                    |                 | Scrivere                      |                   |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| _**Attributo di Identificazione delle informazioni sul cluster**_ |                 |                               |                   |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| **Identificatore**                                                 |                 | **Nome**                      | **Tipo**          |            | **Allineare** | **Accesso** | **Predefinito**             |           | **Obbligatorio** |   |
|                                                                    |                 |                               | **/ Facoltativo** |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |
| 0x0000                                                             |                 | _Identificare il tempo_       | Non firmato       |            | 0x00 –0xffff  | Leggere /   | 0x0000                      |           | M                |   |
|                                                                    | Intero a 16 bit |                               | Scrivere          |            |               |             |                             |           |                  |   |
|                                                                    |                 |                               |                   |            |               |             |                             |           |                  |   |

3

-   _**Attributo delle informazioni sul cluster On/Off**_

| **Identificatore** | **Nome**        | **Tipo** | **Allineare** | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| ------------------ | --------------- | -------- | ------------- | ----------- | --------------- | ---------------- | - |
| **/ Facoltativo**  |                 |          |               |             |                 |                  |   |
|                    |                 |          |               |             |                 |                  |   |
| 0x0000             | _Acceso spento_ | Booleano | 0x00 –0x01    | Leggere     | 0x00            | M                |   |
| soltanto           |                 |          |               |             |                 |                  |   |
|                    |                 |          |               |             |                 |                  |   |

_**Attributi del cluster Gruppi Informazioni**_

| **Identificatore** | **Nome**      | **Tipo**       | **Allineare** | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| ------------------ | ------------- | -------------- | ------------- | ----------- | --------------- | ---------------- | - |
| **/ Facoltativo**  |               |                |               |             |                 |                  |   |
|                    |               |                |               |             |                 |                  |   |
| 0x0000             | _NomeSupport_ | Bitmap a 8 bit | x0000000      | Leggere     | -               | M                |   |
| soltanto           |               |                |               |             |                 |                  |   |
|                    |               |                |               |             |                 |                  |   |

4
