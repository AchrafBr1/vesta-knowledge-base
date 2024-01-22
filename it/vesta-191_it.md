# VESTA191

**Controller relè ZigBee PRL-8ZBS(R)-AC-OTA**

**introduzione**

PRL-8ZBS-AC-OTA è un controller relè ZigBee che può essere collegato a dispositivi cablati e impostato sullo stato Normalmente aperto (N.O.) o Normalmente chiuso (N.C.). Dopo aver aderito alla rete ZigBee, il Relay Controller può essere controllato tramite la rete ZigBee per attivare i dispositivi collegati.

Il Relay Controller utilizza la tecnologia ZigBee per la trasmissione del segnale wireless. ZigBee è un protocollo di comunicazione wireless affidabile, a basso consumo energetico e con elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

Il Relay Controller funge da dispositivo terminale nella rete ZigBee. Può essere incluso nella rete ZigBee per trasmettere o ricevere segnali, ma non può consentire a nessun altro dispositivo ZigBee di unirsi alla rete tramite il Relay Controller.

I modelli con funzione router fungono anche da router nella rete ZigBee. Dopo essere stato incluso nella rete ZigBee, consente ad altri dispositivi ZigBee di unirsi alla rete tramite il Relay Controller.

**Identificazione delle parti**

![](<.gitbook/assets/0 (78).jpeg>)

**1. Pulsante funzione**

Il pulsante funzione viene utilizzato per reimpostare il controller relè per connettersi a una rete ZigBee disponibile.

Tenere premuto il pulsante per 10 secondi, quindi rilasciarlo per ripristinare il controller relè.

**2. Indicatore LED (rosso)**

L'indicatore LED viene utilizzato per indicare lo stato del relè:

-   Lampeggia una volta: il relè è stato ripristinato.
-   Lampeggia due volte: il Relay si è unito con successo a una rete ZigBee.
-   Lampeggia una volta ogni 20 minuti:
-   Il Relay ha perso la connessione alla sua attuale rete ZigBee.

**Terminali di connessione**

Collegare il filo al terminale, stringere la vite per chiudere il clipper e tenere il filo in posizione. Svitare per aprire il clipper per rimuovere il filo collegato al terminale.

1.  **Linea (ingresso CA)**
2.  **Neutro**
3.  **NO**

Per la connessione Normal Open con il dispositivo.

1.  **Comune**
2.  **NC**

Per la connessione Normal Close con il dispositivo

**8. Morsetto pressacavo**

Il morsetto viene utilizzato per fissare i cavi e fornire un pressacavo per proteggere i cavi dal ritaglio metallico.

**9. Fibbia di cablaggio**

La fibbia di cablaggio viene utilizzata per la gestione dei cavi.

1

**Specifica**

-   Fonte di alimentazione (alimentazione esterna): 100-240 V CA
-   Uscita relè: relè SPDT senza potenziale, carico operativo massimo: 10 A (resistivo) a 24 V CC o 240 V CA
-   Filo intrecciato: 14~22 AWG
-   Temperatura operativa: da -10°C a 45°C (da 14°F a 113°F)
-   Umidità: fino all'85% senza condensa
-   Dimensioni: 86 mm x 72 mm x 29 mm

![](<.gitbook/assets/1 (69).jpeg>)

**Ambiente di installazione**

-   Il controller relè deve essere installato all'interno in un luogo asciutto.
-   Si consiglia di installare l'apparecchio in una scatola di plastica ignifuga.
-   Non installare il dispositivo in una scatola metallica per ottimizzare la portata Z-Wave.

![](<.gitbook/assets/2 (63).jpeg>)

**Attenzione**

-   Tutti gli interventi sul dispositivo, comprese l'installazione e la manutenzione, devono essere eseguiti da un elettricista qualificato e autorizzato.
-   Per evitare scosse elettriche e/o danni all'apparecchiatura, scollegare l'alimentazione elettrica dal fusibile principale o dall'interruttore prima dell'installazione e della manutenzione.

Non collegare il dispositivo a carichi che superano la corrente di carico supportata.

![](<.gitbook/assets/3 (56).jpeg>)

**Installazione**

Il cablaggio del PRL deve essere eseguito solo da un tecnico certificato con conoscenza e formazione adeguate sulle apparecchiature elettriche. Cablare il relè secondo le istruzioni seguenti:

1.  Spegnere l'alimentazione prima del collegamento.
2.  Rimuovere il coperchio superiore e rimuovere il morsetto del pressacavo.
3.  Collegare i terminali L e N dell'alimentatore rispettivamente ai terminali Linea e Neutro di PRL attraverso il foro di cablaggio.
4.  A seconda del dispositivo che si desidera controllare tramite il relè, selezionare il terminale NO o NC e collegare il relè al dispositivo per stabilire una connessione Normalmente aperta o Normalmente chiusa con il dispositivo.
5.  Dopo aver completato il cablaggio del dispositivo, sostituire il morsetto del pressacavo, utilizzare la fibbia di cablaggio per gestire i cavi e posizionare la fibbia di cablaggio sulla base con il suo spazio (apertura) posizionato a sinistra (come nello schema seguente).

![](<.gitbook/assets/4 (54).jpeg>)

1.  Sostituire il coperchio superiore. Accendere l'alimentatore per accendere il controller relè.

2

**Configurazione della rete ZigBee**

![](<.gitbook/assets/5 (34).jpeg>)

-   _**Linee guida per i dispositivi ZigBee**_

ZigBee è un protocollo di comunicazione wireless affidabile, a basso consumo energetico e con elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

![](<.gitbook/assets/6 (44).jpeg>)

-   _**Unirsi alla rete ZigBee**_

In quanto dispositivo ZigBee, il Relay Controller deve unirsi a una rete ZigBee per ricevere comandi. Seguire i passaggi seguenti per collegare il Relay Controller a una rete ZigBee.

-   1.  Collegare l'ingresso di alimentazione al controller relè secondo le istruzioni di installazione sopra riportate e accendere il controller relè.
    2.  Tenere premuto il pulsante funzione per 10 secondi mentre il controller relè si reimposta e inizia a cercare la rete ZigBee esistente. Assicurati che la funzione di autorizzazione all'accesso sul router o sul coordinatore della tua rete ZigBee sia abilitata.
    3.  Se il controller relè si connette con successo a una rete ZigBee, l'indicatore LED lampeggerà due volte per confermare.
    4.  Dopo essersi unito alla rete ZigBee, il Relay Controller verrà registrato automaticamente nella rete. Controlla il coordinatore della rete ZigBee, il pannello di controllo del sistema o il CIE (apparecchiatura di controllo e indicazione) per confermare se l'adesione e la registrazione hanno avuto esito positivo.
    5.  Dopo aver aderito alla rete ZigBee, se il Relay Controller perde la connessione alla rete ZigBee corrente, l'indicatore LED lampeggerà ogni 20 minuti. Controllare le condizioni della rete ZigBee e la portata del segnale del controller relè per correggere la condizione.
-   _**Rimozione del dispositivo dalla rete ZigBee (ripristino delle impostazioni di fabbrica)**_

![](<.gitbook/assets/7 (39).png>)

Per rimuovere il controller relè dall'attuale rete ZigBee, il dispositivo deve essere sottoposto al ripristino delle impostazioni di fabbrica per completare la rimozione del dispositivo. La funzione di ripristino delle impostazioni di fabbrica cancellerà il dispositivo dalle impostazioni e dalle informazioni memorizzate e lo inviterà a cercare una nuova rete ZigBee.

**Prima di rimuovere il dispositivo, assicurarsi che il controller relè si trovi nel raggio d'azione del segnale della rete ZigBee corrente**

-   1.  Tenere premuto il pulsante funzione per 10 secondi, quindi rilasciare il pulsante per ripristinare il controller relè.
    2.  Al momento del ripristino, il dispositivo cancellerà l'impostazione corrente della rete ZigBee e trasmetterà il segnale al coordinatore ZigBee per rimuoversi dalla rete ZigBee corrente. Quindi cercherà nuovamente attivamente la rete ZigBee disponibile e si unirà automaticamente alla rete.
-   _**Aggiornamento firmware OTA (solo per la versione OTA)**_

Il Power Controller supporta la funzione di aggiornamento del firmware OTA tramite la rete ZigBee, che può essere avviata dal coordinatore della rete ZigBee. Seguire i passaggi seguenti per eseguire l'aggiornamento del firmware OTA.

**Passo 1.**Devi accedere al tuo ZigBee Coordinator per eseguire l'aggiornamento del firmware in diretta.

**Passo 2.**Nella pagina Web di configurazione, seleziona il dispositivo che desideri aggiornare e seleziona quello nuovo

Firmware ZigBee fornito. Per i dettagli fare riferimento al Manuale utente di ZigBee Coordinator.

**Passaggio 3.**Premere "OK" per avviare il processo di aggiornamento e il LED continuerà a lampeggiare. Durante il processo OTA, non eseguire altre azioni o spegnere il pannello.

**Passaggio 4.**La durata di un aggiornamento richiederà circa 20-30 minuti. Tieni presente che la durata può variare in base alla dimensione del file o alla distanza tra l'accessorio e il coordinatore.

**Passaggio 5.**Attendi il completamento dell'aggiornamento del firmware. Quando l'avanzamento raggiunge il 100%, il dispositivo si ripristinerà automaticamente. Puoi anche aggiornare nuovamente la pagina Web per assicurarti che il firmware del dispositivo venga aggiornato correttamente con la versione più recente visualizzata.

![](<.gitbook/assets/8 (40).png>)

-   _**Capacità del dispositivo router ZigBee (solo PRL-8ZBSR-AC)**_

Il modello Relay Controller con funzione Router consente ad altri dispositivi ZigBee di unirsi alla rete ZigBee tramite il router. Ha una capacità massima di 40 dispositivi/router.

**Operazione**

![](<.gitbook/assets/9 (29).jpeg>)

-   _**Controllo relè**_
    -   Quando il controller relè si è unito con successo a una rete ZigBee, il gateway/pannello di controllo sarà in grado di controllarlo in remoto per accenderlo, spegnerlo o alternare tra le condizioni On e Off. Per i dettagli fare riferimento al gateway/pannello di controllo ZigBee.

3

**Appendice (solo per sviluppatori)**

![](<.gitbook/assets/10 (40).png>)

-   _**ID del cluster di inoltro**_

**ID dispositivo: On Off Uscita: 0x0002**

**Punto finale: 0x0A**

| **Lato server**                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 | **Dalla parte del cliente** |                  |   |   |
| ------------------------------------------------------------------ | --------------- | ----------------------------- | ----------------- | ----------------- | ------------- | -------- | ----------------- | ---------------------- | ----------- | ---------------- | --------------- | --------------------------- | ---------------- | - | - |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   | **Obbligatorio**  |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| Di base (0x0000)                                                   |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             | _Nessuno_        |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| Identificare (0x0003)                                              |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| Acceso/Spento(0x0006)                                              |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   | **Opzionale**     |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| Gruppi(0x0004)                                                     |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             | Nessuno          |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| _**Attributo delle informazioni di base del cluster**_            |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| **Identificatore**                                                 |                 | **Nome**                      | **Tipo**          |                   | **Allineare** |          | **Accesso**       | **Predefinito**        |             | **Obbligatorio** |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   | **/ Facoltativo** |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| 0x0000                                                             |                 | _Versione ZCL_                | 8 bit senza segno |                   | 0x00 –0xff    |          | Leggere           | 0x01                   |             | M                |                 |                             |                  |   |   |
|                                                                    | numero intero   |                               |                   | soltanto          |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| 0x0001                                                             |                 | Versione dell'applicazione    | 8 bit senza segno |                   | 0x00 – 0xff   |          | Leggere           | 0x00                   |             | O                |                 |                             |                  |   |   |
|                                                                    | numero intero   |                               |                   | soltanto          |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| 0x0003                                                             |                 | _Versione HW_                 | 8 bit senza segno |                   | 0x00 –0xff    |          | Leggere           | 0                      |             | O                |                 |                             |                  |   |   |
|                                                                    | numero intero   |                               |                   | soltanto          |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| 0x0004                                                             |                 | _Nome del produttore_         | Carattere         |                   | 0 – 32 byte   |          | Leggere           | Climax                 |             | O                |                 |                             |                  |   |   |
|                                                                    | Corda           |                               |                   | soltanto          | Tecnologia    |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| 0x0005                                                             |                 | _Identificatore del modello_  | Carattere         |                   | 0 – 32 byte   |          | Leggere           | (Versione del modello) |             | O                |                 |                             |                  |   |   |
|                                                                    | Corda           |                               |                   | soltanto          |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| 0x0006                                                             |                 | _DataCodice_                  | Carattere         |                   | 0 – 16 byte   |          | Leggere           |                        |             | O                |                 |                             |                  |   |   |
|                                                                    | Corda           |                               |                   | soltanto          |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| 0x0007                                                             |                 | _Fonte di potere_             | 8 bit             |                   | 0x00 –0xff    |          | Leggere           |                        |             | M                |                 |                             |                  |   |   |
|                                                                    |                 |                               | soltanto          |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| 0x0010                                                             |                 | _Descrizione della posizione_ | Carattere         |                   | 0 – 32 byte   |          | Leggere /         |                        |             | O                |                 |                             |                  |   |   |
|                                                                    | Corda           |                               |                   | Scrivere          |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| 0x0011                                                             |                 | _Ambiente fisico_             | 8 bit             |                   | 0x00 –0xff    |          | Leggere /         | 0x00                   |             | O                |                 |                             |                  |   |   |
|                                                                    |                 |                               | Scrivere          |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| 0x0012                                                             |                 | _Dispositivo abilitato_       | Booleano          |                   | 0x00 –0x01    |          | Leggere /         | 0x01                   |             | M                |                 |                             |                  |   |   |
|                                                                    |                 |                               | Scrivere          |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| _**Attributo di Identificazione delle informazioni sul cluster**_ |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| **Identificatore**                                                 |                 | **Nome**                      | **Tipo**          |                   | **Allineare** |          | **Accesso**       | **Predefinito**        |             | **Obbligatorio** |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   | **/ Facoltativo** |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| 0x0000                                                             |                 | _Identificare il tempo_       | Non firmato       |                   | 0x00 –0xffff  |          | Leggere /         | 0x0000                 |             | M                |                 |                             |                  |   |   |
|                                                                    | Intero a 16 bit |                               |                   | Scrivere          |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| _**Attributo delle informazioni sul cluster On/Off**_             |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| **Identificatore**                                                 |                 | **Nome**                      | **Tipo**          |                   | **Allineare** |          | **Accesso**       | **Predefinito**        |             | **Obbligatorio** |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   | **/ Facoltativo** |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| 0x0000                                                             |                 | _Acceso spento_               | Booleano          |                   | 0x00 –0x01    |          | Leggere           | 0x00                   |             | M                |                 |                             |                  |   |   |
|                                                                    |                 |                               | soltanto          |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| _**Attributi del cluster Gruppi Informazioni**_                   |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| **Identificatore**                                                 |                 | **Nome**                      |                   | **Tipo**          |               |          | **Allineare**     |                        | **Accesso** |                  | **Predefinito** |                             | **Obbligatorio** |   |   |
|                                                                    |                 |                               |                   |                   |               |          | **/ Facoltativo** |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |
| 0x0000                                                             |                 | _NomeSupport_                 |                   | Bitmap a 8 bit    |               | x0000000 |                   | Leggere                |             | -                |                 | M                           |                  |   |   |
|                                                                    |                 |                               |                   |                   | soltanto      |          |                   |                        |             |                  |                 |                             |                  |   |   |
|                                                                    |                 |                               |                   |                   |               |          |                   |                        |             |                  |                 |                             |                  |   |   |

![](<.gitbook/assets/11 (31).png>)![](<.gitbook/assets/12 (35).png>)![](<.gitbook/assets/13 (26).png>)

4
