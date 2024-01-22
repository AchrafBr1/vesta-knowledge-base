# VESTA182

**Parlamento**

**Interruttore relè ZigBee**

**introduzione**

PRLM-CH3-AC-ZBS(R) è un interruttore relè ZigBee a 3 canali che può essere collegato a dispositivi cablati e impostato sullo stato Normalmente aperto (N.O.). Dopo aver aderito alla rete ZigBee, l'interruttore relè può essere controllato tramite la rete ZigBee per attivare i dispositivi collegati.

L'interruttore relè utilizza la tecnologia ZigBee per la trasmissione del segnale wireless. ZigBee è un protocollo di comunicazione wireless affidabile, a basso consumo energetico e con elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

L'interruttore relè dispone anche della funzione router. Funziona come router nella rete ZigBee. Dopo essere stato incluso nella rete ZigBee, consente ad altri dispositivi ZigBee di unirsi alla rete tramite il Relay Switch.

**Identificazione delle parti**

**Coperchio superiore****Base**

![](<.gitbook/assets/0 (71).jpeg>)

1.  **Pulsante interruttore 1/pulsante funzione**
    -   Il pulsante funzione viene utilizzato per reimpostare l'interruttore relè per connettersi a una rete ZigBee disponibile.
    -   Tenere premuto il pulsante per 10 secondi, quindi rilasciarlo per ripristinare l'interruttore relè.
    -   Premere il pulsante per accendere/spegnere il canale relè 1.
2.  **Pulsante di commutazione 2**
    -   Premere il pulsante per accendere/spegnere il canale relè 2.
3.  **Pulsante di commutazione 3**
    -   Premere il pulsante per accendere/spegnere il canale relè 3.

![](<.gitbook/assets/1 (56).png>)

-   _NOTA>_
    -   Quando viene premuto il pulsante di commutazione 2/3, il canale relè 2/3 passerà immediatamente su ON/OFF.
    -   Quando viene premuto il pulsante di commutazione 1, il canale relè 1 passerà a ON/OFF dopo 0,5 secondi, poiché il dispositivo deve identificare se la pressione del pulsante serve per accendere/spegnere o per ripristinare il relè.

1.  **Indicatore LED 1**
2.  **Indicatore LED 2**
3.  **Indicatore LED 3**

Gli indicatori LED 1/2/3 vengono utilizzati per indicare lo stato del canale relè 1/2/3:

-   LED 1 acceso/spento: canale relè 1 acceso/spento
-   LED 2 acceso/spento: canale relè 2 acceso/spento
-   LED 3 acceso/spento: canale relè 3 acceso/spento

1

All'accensione, tutti i LED lampeggeranno in sequenza per 1 ciclo.

Tutti i LED lampeggeranno ogni secondo dopo il ripristino del relè, indicando che è in modalità di apprendimento.

Tutti i LED lampeggeranno tre volte quando il relè si è unito con successo a una rete ZigBee.

**7. Fori di montaggio**

**Terminali di connessione**

Collegare il filo al terminale, stringere la vite per chiudere il clipper e tenere il filo in posizione. Svitare per aprire il clipper per rimuovere il filo collegato al terminale.

1.  **Linea (ingresso CA)**
2.  **Neutro**
3.  **NO (Canale 1)**

Per la connessione Normal Open con il dispositivo

1.  **Comune (Canale 1)**
2.  **NO (Canale 2)**

Per la connessione Normal Open con il dispositivo

1.  **Comune (Canale 2)**
2.  **NO (Canale 3)**

Per la connessione Normal Open con il dispositivo

1.  **Comune (Canale 3)**
2.  **Morsetto antistrappo**

I morsetti vengono utilizzati per fissare i cavi e fornire un pressacavo per proteggere i cavi dal ritaglio metallico.

**17. Fori per il cablaggio**

**Specifica**

-   Alimentazione: 100 - 240 V CA
-   Corrente di carico supportata (per ciascun canale relè): 5 A, 250 V CA o 5 A, 30 V CC
-   Filo intrecciato: 14–22 AWG

**Attenzione**

-   Tutti gli interventi sul dispositivo, comprese l'installazione e la manutenzione, devono essere eseguiti da un elettricista qualificato e autorizzato.
-   Prima dell'installazione o di qualsiasi intervento di manutenzione, assicurarsi che l'alimentazione elettrica sia stata scollegata.
-   Non collegare il dispositivo a carichi che superano la corrente di carico supportata.

**Installazione**

Cablare il relè secondo le istruzioni riportate di seguito.

1.  Si prega di spegnere l'alimentazione prima del collegamento.
2.  Rimuovere il coperchio superiore e rimuovere i morsetti antistrappo.
3.  Collegare i terminali L e N dell'alimentatore rispettivamente ai terminali Linea e Neutro del PRLM attraverso il foro del cablaggio.
4.  A seconda del dispositivo che si desidera controllare tramite il canale relè 1, selezionare il terminale NO e collegare il canale relè 1 al dispositivo attraverso il foro di cablaggio per stabilire una connessione normalmente aperta con il dispositivo.
5.  Allo stesso modo del passaggio 4, collegare il canale relè 2/3 ad altri dispositivi cablati.
6.  Dopo aver completato il cablaggio, riposizionare i morsetti serracavo e il coperchio superiore. Accendere l'alimentatore per accendere l'interruttore relè.

![](<.gitbook/assets/2 (56).jpeg>)

2

**Configurazione della rete ZigBee**

![](<.gitbook/assets/3 (51).jpeg>)

-   _**Linee guida per i dispositivi ZigBee**_

ZigBee è un protocollo di comunicazione wireless affidabile, a basso consumo energetico e con elevata efficienza di trasmissione. Basato sullo standard IEEE802.15.4, ZigBee consente di includere in una rete un gran numero di dispositivi e di coordinarli per lo scambio di dati e la trasmissione di segnali.

![](<.gitbook/assets/4 (49).jpeg>)

-   _**Unirsi alla rete ZigBee**_

Essendo un dispositivo ZigBee, il relè deve unirsi a una rete ZigBee per ricevere comandi. Seguire i passaggi seguenti per aggiungere il relè a una rete ZigBee.

-   1.  Collegare l'ingresso di alimentazione al relè secondo le istruzioni di installazione sopra riportate e accendere l'interruttore del relè.
    2.  Tenere premuto il pulsante funzione per 10 secondi mentre il relè si reimposta e inizia a cercare la rete ZigBee esistente. Assicurati che la funzione di autorizzazione all'accesso sul router o sul coordinatore della tua rete ZigBee sia abilitata.
    3.  Se il relè si connette con successo a una rete ZigBee, l'indicatore LED lampeggerà tre volte per confermare.
    4.  Dopo essersi unito alla rete ZigBee, il Relè verrà registrato automaticamente nella rete. Controlla il coordinatore della rete ZigBee, il pannello di controllo del sistema o il CIE (apparecchiatura di controllo e indicazione) per confermare se l'adesione e la registrazione hanno avuto esito positivo.
-   _**Rimozione del dispositivo dalla rete ZigBee (ripristino delle impostazioni di fabbrica)**_

![](<.gitbook/assets/5 (61).png>)

Per rimuovere il dispositivo dall'attuale rete ZigBee, l'interruttore relè deve essere impostato su Ripristino delle impostazioni di fabbrica per completare la rimozione del dispositivo. La funzione di ripristino delle impostazioni di fabbrica cancellerà dal dispositivo le informazioni sulle impostazioni memorizzate e richiederà al dispositivo di cercare una nuova rete ZigBee.

**Prima di rimuovere il dispositivo, assicurarsi che l'interruttore relè si trovi nel raggio d'azione del segnale della rete ZigBee corrente**

-   1.  Elimina il dispositivo dalla centrale/CIE corrente.
    2.  Tieni premuto il pulsante funzione per 10 secondi, quindi rilascia il pulsante per ripristinare il dispositivo.
    3.  Al momento del ripristino, il dispositivo cancellerà l'impostazione corrente della rete ZigBee e trasmetterà il segnale al coordinatore ZigBee per rimuoversi dalla rete ZigBee corrente. Quindi cercherà nuovamente attivamente la rete ZigBee disponibile e si unirà automaticamente alla rete.
-   _**Prova di portata**_

![](<.gitbook/assets/6 (42).png>)

Per verificare se il dispositivo è in grado di comunicare con il coordinatore della rete ZigBee o il pannello di controllo:

-   -   Mettere il gateway/pannello in modalità test di portata (Walk Test).
    -   Premere il pulsante funzione sul dispositivo
    -   Il gateway/pannello dovrebbe visualizzare se il dispositivo si trova all'interno del raggio operativo (fare riferimento al manuale operativo del gateway/pannello).
-   _**Capacità del dispositivo router ZigBee**_

![](<.gitbook/assets/7 (37).png>)

Lo switch relè è dotato della funzione router che consente ad altri dispositivi ZigBee di unirsi alla rete ZigBee tramite il router. Ha una capacità massima di 40 dispositivi/router.

**Supervisione**

L'interruttore relè trasmetterà un segnale di supervisione per segnalare regolarmente lo stato ON/OFF del canale relè 1/2/3 in base alle impostazioni dell'utente. L'intervallo predefinito in fabbrica è 30 minuti.

**Montaggio**

-   Dopo aver terminato il test della portata e se sei soddisfatto che il dispositivo sia in grado di comunicare con il pannello di controllo nella posizione scelta, procedi al montaggio.
-   Scollegare l'alimentazione principale.
-   Allentare la vite di fissaggio inferiore e rimuovere il coperchio superiore dell'interruttore relè.
-   Utilizzare i fori sulla base per contrassegnare la posizione di montaggio sulla parete.
-   Praticare i fori nella posizione contrassegnata e inserire i tasselli se necessario, avvitare la base nella posizione di montaggio.
-   Riposizionare il coperchio superiore e serrare la vite di fissaggio inferiore.

3

![](<.gitbook/assets/8 (32).jpeg>)

**Operazione**

![](<.gitbook/assets/9 (24).jpeg>)

-   _**Controllo relè**_
    -   Dopo che l'interruttore relè si è unito con successo a una rete ZigBee, il gateway/pannello di controllo può controllare in remoto il canale relè 1/2/3 per accenderlo/spegnerlo. Per i dettagli fare riferimento al gateway/pannello di controllo ZigBee.
    -   L'utente può anche premere manualmente il pulsante di commutazione 1/2/3 per accendere/spegnere il canale relè 1/2/3.
-   _**Aggiornamento firmware OTA**_

![](<.gitbook/assets/10 (18).jpeg>)

Lo switch relè supporta la funzionalità di aggiornamento del firmware OTA tramite la rete ZigBee, che può essere avviata dal coordinatore della rete ZigBee.

Seguire i passaggi seguenti per eseguire l'aggiornamento del firmware OTA.

**Passo 1.**Devi accedere al tuo ZigBee Coordinator per eseguire l'aggiornamento del firmware in diretta.**Passo 2.**Nella pagina Web di configurazione, seleziona il dispositivo che desideri aggiornare e seleziona

nuovo firmware ZigBee fornito. Fare riferimento al Manuale utente di ZigBee Coordinator per i dettagli.

**Passaggio 3.**Premere "OK" per avviare il processo di aggiornamento. Durante il processo OTA, non eseguire altre azioni o spegnere il pannello.

**Passaggio 4.**La durata di un aggiornamento richiederà circa 20-30 minuti. Tieni presente che la durata può variare in base alla dimensione del file o alla distanza tra l'accessorio e il coordinatore.

**Passaggio 5.**Attendi il completamento dell'aggiornamento del firmware. Quando l'avanzamento raggiunge il 100%, il dispositivo si ripristinerà automaticamente. È anche possibile aggiornare nuovamente la pagina Web per assicurarsi che il firmware del dispositivo venga aggiornato correttamente con la versione più recente visualizzata.

**Appendice (solo per sviluppatori)**

![](<.gitbook/assets/11 (28).png>)

-   _**ID del cluster di inoltro**_

**ID dispositivo: On Off Uscita: 0x0002**

**Punto finale: 0x0A**

| **Lato server** |                  | **Dalla parte del cliente** |
| --------------- | ---------------- | --------------------------- |
|                 |                  |                             |
|                 | **Obbligatorio** |                             |

Di base (0x0000)

Identificare(0x0003)

Acceso/Spento(0x0006)

_Nessuno_

**Opzionale**

Gruppi(0x0004)

Nessuno

-   _**Attributo delle informazioni di base del cluster**_

| **Identificatore** | **Nome**                   | **Tipo**          | **Allineare** | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| ------------------ | -------------------------- | ----------------- | ------------- | ----------- | --------------- | ---------------- | - |
| **/ Facoltativo**  |                            |                   |               |             |                 |                  |   |
|                    |                            |                   |               |             |                 |                  |   |
| 0x0000             | _Versione ZCL_             | 8 bit senza segno | 0x00 –0xff    | Leggere     | 0x01            | M                |   |
| numero intero      | soltanto                   |                   |               |             |                 |                  |   |
|                    |                            |                   |               |             |                 |                  |   |
| 0x0001             | Versione dell'applicazione | 8 bit senza segno | 0x00 – 0xff   | Leggere     | 0x00            | O                |   |
| numero intero      | soltanto                   |                   |               |             |                 |                  |   |
|                    |                            |                   |               |             |                 |                  |   |
| 0x0003             | _Versione HW_              | 8 bit senza segno | 0x00 –0xff    | Leggere     | 0               | O                |   |
| numero intero      | soltanto                   |                   |               |             |                 |                  |   |
|                    |                            |                   |               |             |                 |                  |   |

4

| 0x0004   | _Nome del produttore_         | Carattere  | 0 – 32 byte | Leggere   | Climax                 | O |   |
| -------- | ----------------------------- | ---------- | ----------- | --------- | ---------------------- | - | - |
| Corda    | soltanto                      | Tecnologia |             |           |                        |   |   |
|          |                               |            |             |           |                        |   |   |
| 0x0005   | _Identificatore del modello_  | Carattere  | 0 – 32 byte | Leggere   | (Versione del modello) | O |   |
| Corda    | soltanto                      |            |             |           |                        |   |   |
|          |                               |            |             |           |                        |   |   |
| 0x0006   | _DataCodice_                  | Carattere  | 0 – 16 byte | Leggere   |                        | O |   |
| Corda    | soltanto                      |            |             |           |                        |   |   |
|          |                               |            |             |           |                        |   |   |
|          |                               |            |             |           |                        |   |   |
| 0x0007   | _Fonte di potere_             | 8 bit      | 0x00 –0xff  | Leggere   |                        | M |   |
| soltanto |                               |            |             |           |                        |   |   |
|          |                               |            |             |           |                        |   |   |
| 0x0010   | _Descrizione della posizione_ | Carattere  | 0 – 32 byte | Leggere / |                        | O |   |
| Corda    | Scrivere                      |            |             |           |                        |   |   |
|          |                               |            |             |           |                        |   |   |
| 0x0011   | _Ambiente fisico_             | 8 bit      | 0x00 –0xff  | Leggere / | 0x00                   | O |   |
| Scrivere |                               |            |             |           |                        |   |   |
|          |                               |            |             |           |                        |   |   |
| 0x0012   | _Dispositivo abilitato_       | Booleano   | 0x00 –0x01  | Leggere / | 0x01                   | M |   |
| Scrivere |                               |            |             |           |                        |   |   |
|          |                               |            |             |           |                        |   |   |

![](<.gitbook/assets/12 (19).jpeg>)

-   _**Attributo di Identificazione delle informazioni sul cluster**_

![](<.gitbook/assets/13 (22).jpeg>)

| **Identificatore**                                     | **Nome**                | **Tipo**    | **Allineare** | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| ------------------------------------------------------ | ----------------------- | ----------- | ------------- | ----------- | --------------- | ---------------- | - |
| **/ Facoltativo**                                      |                         |             |               |             |                 |                  |   |
|                                                        |                         |             |               |             |                 |                  |   |
| 0x0000                                                 | _Identificare il tempo_ | Non firmato | 0x00 –0xffff  | Leggere /   | 0x0000          | M                |   |
| Intero a 16 bit                                        | Scrivere                |             |               |             |                 |                  |   |
|                                                        |                         |             |               |             |                 |                  |   |
| _**Attributo delle informazioni sul cluster On/Off**_ |                         |             |               |             |                 |                  |   |

![](<.gitbook/assets/14 (22).png>)

| **Identificatore**                               | **Nome**        | **Tipo** | **Allineare** | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| ------------------------------------------------ | --------------- | -------- | ------------- | ----------- | --------------- | ---------------- | - |
| **/ Facoltativo**                                |                 |          |               |             |                 |                  |   |
|                                                  |                 |          |               |             |                 |                  |   |
| 0x0000                                           | _Acceso spento_ | Booleano | 0x00 –0x01    | Leggere     | 0x00            | M                |   |
| soltanto                                         |                 |          |               |             |                 |                  |   |
|                                                  |                 |          |               |             |                 |                  |   |
| _**Attributi del cluster Gruppi Informazioni**_ |                 |          |               |             |                 |                  |   |

![](<.gitbook/assets/15 (20).png>)

| **Identificatore** | **Nome**      | **Tipo**       | **Allineare** | **Accesso** | **Predefinito** | **Obbligatorio** |   |
| ------------------ | ------------- | -------------- | ------------- | ----------- | --------------- | ---------------- | - |
| **/ Facoltativo**  |               |                |               |             |                 |                  |   |
|                    |               |                |               |             |                 |                  |   |
| 0x0000             | _NomeSupport_ | Bitmap a 8 bit | x0000000      | Leggere     | -               | M                |   |
| soltanto           |               |                |               |             |                 |                  |   |
|                    |               |                |               |             |                 |                  |   |

5
