# VESTA178

**Controllo otturatore (SCM-8ZBS)**

**introduzione**

SCM-8ZBS è un controllo per tapparelle ZigBee. L'utente può controllare l'SCM tramite la rete ZigBee a distanza o manualmente collegando un interruttore al controllo dell'otturatore.

Il controllo dell'otturatore utilizza la tecnologia ZigBee per la trasmissione del segnale wireless. ZigBee è un protocollo di comunicazione wireless affidabile, a basso consumo energetico e con elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

Il Shutter Control funge da dispositivo terminale nella rete ZigBee. Può essere incluso nella rete ZigBee per trasmettere o ricevere segnali, ma non può consentire a nessun altro dispositivo ZigBee di unirsi alla rete tramite il controllo otturatore.

**Identificazione delle parti**

1.  **Pulsante funzione**
    -   Premere una volta: trasmette un segnale di supervisione.
    -   Tieni premuto per 3~9 secondi: entra nella modalità di calibrazione.
    -   Tenere premuto per 10 secondi: reimpostare il controllo dell'otturatore per accedere alla rete ZigBee.
2.  **Indicatore LED**

![](<.gitbook/assets/0 (67).jpeg>)

L'indicatore LED viene utilizzato per indicare lo stato del controllo dell'otturatore:

-   -   Lampeggia una volta: il controllo dell'otturatore è stato ripristinato.
    -   Lampeggia due volte: il controllo otturatore si è unito con successo a una rete ZigBee.
    -   Lampeggia 5 volte: calibrazione manuale riuscita.
    -   Lampeggia una volta ogni 20 minuti:

Il controllo otturatore ha perso la connessione alla sua attuale rete ZigBee.

1.  **Fori di montaggio**
2.  **Interruttore locale S1 (direzione di apertura)**

Collegare un interruttore esterno a questo terminale. Attivare

questo interruttore per controllare che la tapparella rotoli verso "Aperto"

direzione attivando l'uscita motore O1

Attivando questo interruttore quando la tapparella sta scorrendo

verso la direzione “Chiudi” l'otturatore si fermerà.

**5. Interruttore locale S2 (direzione di chiusura)**

Collegare un interruttore esterno a questo terminale. Attivare questo interruttore per controllare che la tapparella si sposti verso la direzione "Chiuso" attivando l'uscita motore O2.

L'attivazione di questo interruttore quando la tapparella si muove verso la direzione di apertura fermerà la tapparella.

**6. Uscita motore O1 (direzione di apertura)**

Collegare al terminale di apertura del motore dell'otturatore.

**7. Uscita motore O2 (direzione di chiusura)**

Collegare al terminale di chiusura del motore dell'otturatore.

1.  **Ingresso alimentazione L (cavo sotto tensione)**
2.  **Ingresso alimentazione N (cavo neutro)**
3.  **Morsetto antistrappo**

Il morsetto viene utilizzato per fissare i cavi e fornire un pressacavo per proteggere i cavi dal ritaglio metallico.

**11. Fibbia di cablaggio**

La fibbia di cablaggio viene utilizzata per la gestione dei cavi.

1

**Specifica**

-   Alimentazione: 110 - 230 V CA, 50/60 Hz
-   Corrente di carico supportata: 1/4 HP (potenza del cavallo); 1,8A per motori con fattore di potenza compensato (carichi induttivi)
-   Protocollo di comunicazione: ZigBee Pro Home Automation 1.2, 2.4GHz

![](<.gitbook/assets/1 (59).jpeg>)

**Attenzione**

-   Tutti gli interventi sul dispositivo, comprese l'installazione e la manutenzione, devono essere eseguiti da un elettricista qualificato e autorizzato.
-   Prima dell'installazione o di qualsiasi intervento di manutenzione, assicurarsi che l'alimentazione elettrica sia stata scollegata.
-   Non collegare il dispositivo a carichi che superano la corrente di carico supportata.
-   Collegare il dispositivo solo al motore alimentato in CA.

**Installazione**

-   SCM-8ZBS deve essere collegato secondo lo schema seguente:

![](<.gitbook/assets/2 (54).jpeg>)

-   -   Collegare il terminale N dell'SCM al terminale N dell'alimentatore.
    -   Collegare il terminale L dell'SCM al terminale L dell'alimentatore.
    -   Collegare il terminale O1 dell'SCM al terminale di apertura del motore dell'otturatore.
    -   Collegare il terminale O2 dell'SCM al terminale di chiusura del motore dell'otturatore.
    -   **(Interruttore locale opzionale)**Collegare i terminali S2 e S1 dell'SCM al terminale L dell'alimentatore.
-   Inserire ciascun filo nel terminale a cui deve essere collegato, serrare ciascuna vite per chiudere le clip e mantenere i fili in posizione.
-   Dopo aver collegato i cavi, utilizzare la fibbia di cablaggio per gestire i cavi e posizionare la fibbia di cablaggio sulla base con il suo spazio (apertura) posizionato a sinistra.

2

![](<.gitbook/assets/3 (49).jpeg>)

**Configurazione della rete ZigBee**

-   _**Linee guida per i dispositivi ZigBee**_

ZigBee è un protocollo di comunicazione wireless affidabile, a basso consumo energetico e con elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete più dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

-   _**Unirsi alla rete ZigBee**_

In quanto dispositivo ZigBee, il controllo otturatore deve unirsi a una rete ZigBee per ricevere comandi. Seguire i passaggi seguenti per unire il controllo otturatore a una rete ZigBee.

-   1.  Collegare l'alimentazione al Controllo otturatore secondo le istruzioni di installazione nella sezione precedente e accendere il Controllo otturatore.
    2.  Tenere premuto il pulsante funzione per 10 secondi mentre il controllo dell'otturatore si reimposta e inizia a cercare la rete ZigBee esistente. Assicurati che la funzione di autorizzazione all'accesso sul router o sul coordinatore della tua rete ZigBee sia abilitata.
    3.  Se il controllo otturatore si connette con successo a una rete ZigBee, l'indicatore LED lampeggerà due volte per confermare.
    4.  Dopo l'accesso alla rete ZigBee, il controllo otturatore verrà registrato automaticamente nella rete. Controlla il coordinatore della rete ZigBee, il pannello di controllo del sistema o il CIE (apparecchiatura di controllo e indicazione) per confermare se l'adesione e la registrazione hanno avuto esito positivo.
    5.  Dopo aver aderito alla rete ZigBee, se il controllo otturatore perde la connessione alla rete ZigBee corrente, l'indicatore LED lampeggerà ogni 20 minuti. Controllare le condizioni della rete ZigBee e la portata del segnale di controllo dell'otturatore per correggere la condizione.
-   _**Rimozione del dispositivo dalla rete ZigBee (ripristino delle impostazioni di fabbrica)**_

Per rimuovere il controllo otturatore dall'attuale rete ZigBee, il controllo otturatore deve essere impostato su Ripristino impostazioni di fabbrica per completare la rimozione del dispositivo. La funzione di ripristino delle impostazioni di fabbrica cancellerà il controllo dell'otturatore dalle informazioni sulle impostazioni memorizzate e richiederà al dispositivo di cercare una nuova rete ZigBee.

**Prima di rimuovere il dispositivo, assicurarsi che il controllo dell'otturatore si trovi nel raggio d'azione del segnale della rete ZigBee corrente**

1.  Tenere premuto il pulsante funzione per 10 secondi, quindi rilasciare il pulsante per ripristinare il controllo dell'otturatore.
2.  Al ripristino, il controllo otturatore cancellerà l'impostazione corrente della rete ZigBee e trasmetterà il segnale al coordinatore ZigBee per rimuoversi dalla rete ZigBee corrente. Quindi cercherà nuovamente attivamente la rete ZigBee disponibile e si unirà automaticamente alla rete.

**Supervisione**

Il controllo dell'otturatore trasmetterà un segnale di supervisione per segnalare regolarmente la sua condizione in base alle impostazioni dell'utente. L'intervallo predefinito in fabbrica è 30 minuti. L'utente può anche premere una volta il pulsante funzione per trasmettere manualmente un segnale di supervisione.

**Operazione**

-   _**Calibrazione**_
    -   L'orario di attivazione predefinito del controllo otturatore è**4**minuti. Quando si preme il pulsante Su/Giù o il coordinatore di rete ZigBee trasmette il comando Su/Giù, attiverà il motore dell'otturatore per 4 minuti.
    -   Affinché il Controllo dell'Otturatore funzioni correttamente è necessario calibrarne il tempo di attivazione. Esistono due modi per regolare il tempo di attivazione:
        -   **Comando ZigBee:**Il tempo di attivazione può essere regolato inviando il comando dal coordinatore della rete ZigBee. (Vedi Appendice – Attributo Cluster Livello – OnTransitionTime / OffTransitionTime, unità minima regolabile 100ms)
        -   **Calibrazione manuale:**Calibrare l'attivazione secondo la procedura seguente:

3

-   -   1.  Prima della calibrazione, gli interruttori locali esterni devono essere collegati al controllo della tapparella.
        2.  Tieni premuto il pulsante Funzione per 3~9 secondi e rilasciare per accedere alla modalità di calibrazione. Il controllo dell'otturatore ruoterà verso la direzione "Apertura" per 4 minuti quando si accede alla modalità di calibrazione.
        3.  Attendere 4 minuti affinché il controllo dell'otturatore smetta di ruotare nella direzione "Apertura", quindi attivare l'interruttore locale esterno "Chiudi" collegato per chiudere l'otturatore.
        4.  Attivare l'interruttore locale esterno “Apri” nel momento in cui la tapparella è completamente chiusa. Il controllo dell'otturatore registrerà il tempo impiegato tra i passaggi 3 e 4 come nuovo "**ora di chiusura**”.
        5.  Il controllo dell'otturatore ruoterà verso la direzione di apertura dopo il passaggio 4.
        6.  Attivare l'interruttore locale esterno “Chiudi” nel momento in cui la tapparella è completamente aperta. Il controllo dell'otturatore registrerà il tempo impiegato tra i passaggi 5 e 6 come nuovo "**orario aperto**”.

Esempio

Se la tapparella impiega 30 secondi per spostarsi da Aperto a Chiuso e 40 secondi per spostarsi da Chiuso ad Aperto, il nuovo**ora di chiusura**sarà**30**secondi e nuovi**orario aperto**sarà**40**secondi.

Dopo la calibrazione, ogni volta che il controllo dell'otturatore riceve un comando di chiusura, ruoterà nella direzione di chiusura per 30 secondi. Quando riceve il comando di apertura, rotolerà verso l'apertura per 40 secondi.

-   -   L'orario di attivazione verrà reimpostato**4**minuti ogni volta che il controllo otturatore si connette a una rete ZigBee.
    -   Se il processo di calibrazione manuale ha esito positivo, il LED lampeggerà 5 volte per indicarlo.
-   _**Controllo dell'otturatore**_

**Rete ZigBee**

-   Dopo che il controllo dell'otturatore si è unito con successo a una rete ZigBee, il coordinatore può controllare a distanza l'apertura, la chiusura o l'arresto dell'otturatore trasmettendo il comando tramite la rete ZigBee.
-   Quando il controllo dell'otturatore riceve il segnale di apertura/chiusura dal coordinatore, ruoterà nella direzione di apertura/chiusura in base al tempo di attivazione calibrato per aprire/chiudere completamente l'otturatore.
-   Lo stato dell'otturatore può anche essere regolato in percentuale da 0%, 10%, 20%... a 100% tramite ZigBee Coordinator.
-   L'attuale percentuale di apertura viene trasmessa anche al coordinatore ZigBee.

**Commutatore locale**

-   -   Se è collegato un interruttore locale opzionale, gli utenti possono anche premere il pulsante dell'interruttore per aprire/chiudere l'otturatore.
    -   Premere e rilasciare l'interruttore per meno di 1 secondo per controllare l'apertura o la chiusura completa dell'otturatore.
    -   Tenere premuto l'interruttore per più di 1 secondo per controllare l'apertura e la chiusura dell'otturatore fino al rilascio dell'interruttore. Quando l'interruttore viene rilasciato, l'otturatore si fermerà.
    -   Premendo l'interruttore quando l'otturatore si muove nella direzione opposta si fermerà l'otturatore. Premere nuovamente l'interruttore per aprire/chiudere l'otturatore.

Ad esempio, premendo l'interruttore verso il basso mentre l'otturatore si sta aprendo si fermerà l'otturatore, premere nuovamente l'interruttore verso il basso per avviare la chiusura dell'otturatore.

-   _**Aggiornamento firmware OTA (solo per la versione OTA)**_

Il controllo dell'otturatore supporta la funzione di aggiornamento del firmware OTA tramite la rete ZigBee, che può essere avviata dal coordinatore della rete ZigBee.

Seguire i passaggi seguenti per eseguire l'aggiornamento del firmware OTA.

**Passo 1.**Devi accedere al tuo ZigBee Coordinator per eseguire l'aggiornamento del firmware in diretta.**Passo 2.**Nella pagina Web di configurazione, seleziona il dispositivo che desideri aggiornare e seleziona quello nuovo

Firmware ZigBee fornito. Fare riferimento al Manuale utente di ZigBee Coordinator per i dettagli.

**Passaggio 3.**Premere "OK" per avviare il processo di aggiornamento e il LED continuerà a lampeggiare. Durante il processo OTA,

non eseguire altre azioni né spegnere la centrale.

**Passaggio 4.**La durata di un aggiornamento richiederà circa 20-30 minuti. Tieni presente che la durata può variare in base alla dimensione del file o alla distanza tra l'accessorio e il coordinatore.

**Passaggio 5.**Attendi il completamento dell'aggiornamento del firmware. Quando l'avanzamento raggiunge il 100%, il dispositivo si ripristinerà automaticamente. È inoltre possibile aggiornare nuovamente la pagina Web per assicurarsi che il firmware del dispositivo venga aggiornato correttamente con la versione più recente visualizzata.

**Appendice (solo per sviluppatori)**

-   _**Controllo otturatore relè di potenza con ID cluster contatori**_

**ID dispositivo: Ombra: 0x0200**

**Punto finale: 0x01**

| **Lato server** |                  | **Dalla parte del cliente** |
| --------------- | ---------------- | --------------------------- |
|                 |                  |                             |
|                 | **Obbligatorio** |                             |

Di base (0x0000)

_Nessuno_

4

Identificare (0x0003)

Acceso/Spento(0x0006)

Controllo livello (0x0008)

Configurazione ombra (0x0x0100)

Gruppi(0x0004)

Scene(0x0005)

**Opzionale**

| Nessuno                                                            |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 | Nessuno          |   |
| ------------------------------------------------------------------ | ----------------------------- | -------------------- | -------------- | -------------------- | ----------------- | ----------------- | ---------------------- | ----------------- | ----------- | --------------- | ---------------- | ---------------- | --------------- | ---------------- | - |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| _**Attributo delle informazioni di base del cluster**_            |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| **Identificatore**                                                 | **Nome**                      |                      |                | **Tipo**             |                   |                   | **Allineare**          |                   | **Accesso** |                 | **Predefinito**  | **Obbligatorio** |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   | **/ Facoltativo** |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0000                                                             | _Versione ZCL_                | 8 bit senza segno    |                | 0x00 –0xff           |                   | Sola lettura      |                        | 0x01              | M           |                 |                  |                  |                 |                  |   |
|                                                                    |                               | numero intero        |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0001                                                             | Versione dell'applicazione    | 8 bit senza segno    |                | 0x00 – 0xff          |                   | Sola lettura      |                        | 0x00              | O           |                 |                  |                  |                 |                  |   |
|                                                                    |                               | numero intero        |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0003                                                             | _Versione HW_                 | 8 bit senza segno    |                | 0x00 –0xff           |                   | Sola lettura      | 0                      | O                 |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               | numero intero        |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0004                                                             | _Nome del produttore_         | Stringa di caratteri |                | 0 – 32 byte          |                   | Sola lettura      |                        | Climax            | O           |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      | Tecnologia     |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0005                                                             | _Identificatore del modello_  | Stringa di caratteri |                | 0 – 32 byte          |                   | Sola lettura      | (Versione del modello) | O                 |             |                 |                  |                  |                 |                  |   |
| 0x0006                                                             | _DataCodice_                  | Stringa di caratteri |                | 0 – 16 byte          |                   | Sola lettura      |                        |                   | O           |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0007                                                             | _Fonte di potere_             |                      |                | 8 bit                |                   | 0x00 –0xff        |                        | Sola lettura      |             |                 | M                |                  |                 |                  |   |
| 0x0010                                                             | _Descrizione della posizione_ | Stringa di caratteri |                | 0 – 32 byte          |                   | Leggere scrivere  |                        |                   | O           |                 |                  |                  |                 |                  |   |
| 0x0011                                                             | _Ambiente fisico_             |                      |                | 8 bit                |                   | 0x00 –0xff        |                        | Leggere scrivere  |             | 0x00            | O                |                  |                 |                  |   |
| 0x0012                                                             | _Dispositivo abilitato_       |                      |                | Booleano             |                   | 0x00 –0x01        |                        | Leggere scrivere  |             | 0x01            | M                |                  |                 |                  |   |
| _**Attributo di Identificazione delle informazioni sul cluster**_ |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| **Identificatore**                                                 | **Nome**                      |                      |                | **Tipo**             |                   |                   | **Allineare**          |                   | **Accesso** |                 | **Predefinito**  | **Obbligatorio** |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   | **/ Facoltativo** |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0000                                                             | _Identificare il tempo_       | Senza segno a 16 bit |                | 0x00 –0xffff         |                   | Leggere scrivere  |                        | 0x0000            | M           |                 |                  |                  |                 |                  |   |
|                                                                    |                               | numero intero        |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| _**Attributo delle informazioni sul cluster On/Off**_             |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| **Identificatore**                                                 | **Nome**                      |                      |                | **Tipo**             |                   |                   | **Allineare**          |                   | **Accesso** |                 | **Predefinito**  | **Obbligatorio** |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   | **/ Facoltativo** |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0000                                                             | _Acceso spento_               |                      |                | Booleano             |                   | 0x00 –0x01        |                        | Sola lettura      |             | 0x00            | M                |                  |                 |                  |   |
| _**Attributo delle informazioni sul cluster di livello**_         |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| **Identificatore**                                                 | **Nome**                      |                      |                | **Tipo**             |                   | **Allineare**     |                        | **Accesso**       |             | **Predefinito** | **Obbligatorio** |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      | **/ Facoltativo** |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0000                                                             | _Livello attuale_             |                      |                | Non firmato          |                   | 0x00 –0xff        |                        | Sola lettura      |             | 0x00            | M                |                  |                 |                  |   |
|                                                                    |                               | Intero a 8 bit       |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0012                                                             | _OnTransitionTime_            |                      |                | Senza segno a 16 bit |                   | 0x0000 –          |                        | Leggere scrivere  |             | 0x0960          | O                |                  |                 |                  |   |
|                                                                    |                               | numero intero        |                | 0xFFFE               |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0013                                                             | _OffTransitionTime_           |                      |                | Senza segno a 16 bit |                   | 0x0000 –          |                        | Leggere scrivere  |             | 0x0960          | O                |                  |                 |                  |   |
|                                                                    |                               | numero intero        |                | 0xFFFE               |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| _**Attributi delle informazioni sul cluster di ombre**_           |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| **Identificatore**                                                 | **Nome**                      |                      |                | **Tipo**             |                   |                   | **Allineare**          |                   | **Accesso** |                 | **Predefinito**  | **Obbligatorio** |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   | **/ Facoltativo** |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0002                                                             | _Stato_                       |                      | Bitmap a 8 bit |                      | 0000xxxx B        |                   | Leggere scrivere       |                   | 00000000 B  | M               |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0010                                                             | _Limite chiuso_               | Senza segno a 16 bit |                |                      | 0x0001 –          |                   | Leggere scrivere       |                   | 0x0001      | M               |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                | numero intero        |                   |                   | 0xfffe                 |                   |             |                 |                  |                  |                 |                  |   |
| 0x0011                                                             | _Modalità_                    | Enumerazione a 8 bit |                | 0x00 – 0xfe          |                   | Leggere scrivere  |                        | 0x00              | M           |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| _**Attributi del cluster Gruppi Informazioni**_                   |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| **Identificatore**                                                 | **Nome**                      |                      |                | **Tipo**             |                   |                   | **Allineare**          |                   |             | **Accesso**     |                  |                  | **Predefinito** | **Obbligatorio** |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        | **/ Facoltativo** |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0000                                                             | _NomeSupport_                 |                      |                | Bitmap a 8 bit       |                   | x0000000          |                        | Sola lettura      |             | -               | M                |                  |                 |                  |   |
| _**Attributi delle informazioni sul cluster Scene**_              |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| **Identificatore**                                                 | **Nome**                      |                      |                | **Tipo**             |                   |                   | **Allineare**          |                   |             | **Accesso**     |                  |                  | **Predefinito** | **Obbligatorio** |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        | **/ Facoltativo** |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0000                                                             | _Conteggio scene_             |                      |                | 8 bit senza segno    |                   | 0x00 – 0xff       |                        | Sola lettura      |             |                 | 0x00             | M                |                 |                  |   |
|                                                                    |                               | numero intero        |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0001                                                             | _Scena corrente_              |                      |                | 8 bit senza segno    |                   | 0x00 – 0xff       |                        | Sola lettura      |             |                 | 0x00             | M                |                 |                  |   |
|                                                                    |                               | numero intero        |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0002                                                             | _Gruppo corrente_             |                      |                | Non firmato          |                   | 0x0000 –          |                        | Sola lettura      |             |                 | 0x00             | M                |                 |                  |   |
|                                                                    |                               | Intero a 16 bit      |                |                      | 0xfff7            |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   |                   |                        |                   |             |                 |                  |                  |                 |                  |   |
| 0x0003                                                             | _SceneValid_                  |                      |                | Booleano             |                   | 0x00 – 0x01       |                        | Sola lettura      |             |                 | 0x00             | M                |                 |                  |   |
| 0x0004                                                             | _NomeSupport_                 |                      |                | Bitmap a 8 bit       |                   | x0000000          |                        | Sola lettura      |             | -               | M                |                  |                 |                  |   |
|                                                                    |                               |                      |                |                      |                   | 5                 |                        |                   |             |                 |                  |                  |                 |                  |   |
