# VESTA 170

**PRLM-CH3-AC-ZW Interruttore relè Z-Wave**

**introduzione**

**PRLM-CH3-AC-ZW è un interruttore relè a 3 canali Z-Wave che può essere collegato a dispositivi cablati e impostato sullo stato Normalmente aperto (N.O.). Dopo aver aderito alla rete Z-Wave, l'interruttore relè può essere controllato tramite la rete Z-Wave per attivare i dispositivi collegati.**

**Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. Sfruttando la rete mesh Z-Wave, i comandi possono essere indirizzati a destinazione tramite prodotti Z-Wave intermedi di "ascolto".**

**Il relè può controllare i nodi Z-Wave semplicemente premendo il pulsante funzione e può anche avvisarti di segnalare problemi di comunicazione.**

**Identificazione delle parti**

**Coperchio superiore****Base**

![](<.gitbook/assets/0 (48).png>)

1.  **Pulsante interruttore 1/pulsante funzione**
    -   **Premere il pulsante 3 volte entro 1 secondo per inviare un codice di apprendimento.**
    -   **Tieni premuto il pulsante per 10 secondi per ripristinare le impostazioni di fabbrica.**
    -   **Premere il pulsante per accendere/spegnere il canale relè 1.**
2.  **Pulsante di commutazione 2**
    -   **Premere il pulsante per accendere/spegnere il canale relè 2.**
3.  **Pulsante di commutazione 3**
    -   **Premere il pulsante per accendere/spegnere il canale relè 3.**

![](<.gitbook/assets/1 (53).png>)

-   **NOTA>**

**Quando viene premuto il pulsante di commutazione 2/3, il canale relè 2/3 passerà immediatamente su ON/OFF. Quando viene premuto il pulsante di commutazione 1, il canale relè 1 passerà a ON/OFF dopo un secondo, poiché il dispositivo deve identificare se la pressione del pulsante è per l'accensione/spegnimento**

**o per inviare un codice di apprendimento.**

1.  **Indicatore LED 1**
2.  **Indicatore LED 2**
3.  **Indicatore LED 3**

**Gli indicatori LED 1/2/3 vengono utilizzati per indicare lo stato del canale relè 1/2/3:**

-   **LED 1 acceso/spento: canale relè 1 acceso/spento**
-   **LED 2 acceso/spento: canale relè 2 acceso/spento**
-   **LED 3 acceso/spento: canale relè 3 acceso/spento**

**All'accensione, tutti i LED lampeggeranno in sequenza per 1 ciclo.**

**In modalità apprendimento, tutti i LED lampeggeranno una volta al secondo.**

**Una volta che l'apprendimento ha avuto successo, tutti i LED lampeggeranno velocemente per 3 volte.**

**7. Fori di montaggio**

**1**

**Terminali di connessione**

**Collegare il filo al terminale, stringere la vite per chiudere il clipper e tenere il filo in posizione. Svitare per aprire il clipper per rimuovere il filo collegato al terminale.**

1.  **Linea (ingresso CA)**
2.  **Neutro**
3.  **NO (Canale 1)**

**Per la connessione Normal Open con il dispositivo**

1.  **Comune (Canale 1)**
2.  **NO (Canale 2)**

**Per la connessione Normal Open con il dispositivo**

1.  **Comune (Canale 2)**
2.  **NO (Canale 3)**

**Per la connessione Normal Open con il dispositivo**

1.  **Comune (Canale 3)**
2.  **Morsetto antistrappo**

**I morsetti vengono utilizzati per fissare i cavi e fornire un pressacavo per proteggere i cavi dal ritaglio metallico.**

**17. Fori per il cablaggio**

**Specifica**

**Alimentazione: 100 - 240 V CA**

**Corrente di carico supportata (per ciascun canale relè): 5 A, 250 V CA o 5 A, 30 V CC**

**Filo intrecciato: 14–22 AWG**

**Attenzione**

**Tutti gli interventi sul dispositivo, comprese l'installazione e la manutenzione, devono essere eseguiti da un elettricista qualificato e autorizzato.**

**Prima dell'installazione o di qualsiasi intervento di manutenzione, assicurarsi che l'alimentazione elettrica sia stata scollegata. Non collegare il dispositivo a carichi che superano la corrente di carico supportata.**

**Installazione**

**Cablare il relè secondo le istruzioni riportate di seguito.**

![](<.gitbook/assets/2 (50).jpeg>)

1.  **Si prega di spegnere l'alimentazione prima del collegamento.**
2.  **Rimuovere il coperchio superiore e rimuovere i morsetti antistrappo.**
3.  **Collegare i terminali L e N dell'alimentatore rispettivamente ai terminali Linea e Neutro del PRLM attraverso il foro del cablaggio.**
4.  **A seconda del dispositivo che si desidera controllare tramite il canale relè 1, selezionare il terminale NO e collegare il canale relè 1 al dispositivo attraverso il foro di cablaggio per stabilire una connessione normalmente aperta con il dispositivo.**
5.  **Allo stesso modo del passaggio 4, collegare il canale relè 2/3 ad altri dispositivi cablati.**
6.  **Dopo aver completato il cablaggio, riposizionare i morsetti serracavo e il coperchio superiore. Accendere l'alimentatore per accendere l'interruttore relè.**

**Caratteristiche**

![](<.gitbook/assets/3 (59).png>)

**Aggiunta di dispositivi (inclusione)**

**Collegare l'ingresso di alimentazione all'interruttore a relè secondo le istruzioni di installazione riportate sopra e accendere l'interruttore a relè.**

**Mettere il gateway Z-Wave o il pannello di controllo in modalità Inclusione (fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).**

**Entro 1 secondo, premere il pulsante funzione 3 volte.**

**2**

**Fare riferimento al manuale operativo del gateway Z-Wave o del pannello di controllo per completare il processo di aggiunta.**

**Se il dispositivo è già stato aggiunto (incluso) in un altro gateway/pannello di controllo Z-Wave o se non è possibile aggiungere il dispositivo all'attuale gateway/pannello di controllo Z-Wave, provare prima a rimuoverlo (vedere Rimozione del dispositivo).**

**Rimozione del dispositivo (esclusione)**

![](<.gitbook/assets/4 (58).png>)

**Il dispositivo deve essere rimosso dalla rete Z-Wave esistente prima di essere aggiunto a un'altra. Modalità di esclusione**

**Mettere il gateway Z-Wave o la centrale di controllo in modalità di esclusione (fare riferimento al manuale del gateway Z-Wave o della centrale di controllo).**

**Entro 1 secondo, premere il pulsante funzione 3 volte e il dispositivo verrà rimosso dalla rete Z-Wave.**

**Il ripristino delle impostazioni di fabbrica del dispositivo lo ripristinerà alle impostazioni predefinite di fabbrica (ovvero non incluso in alcuna rete Z-Wave). Utilizzare questa procedura solo se il gateway Z-Wave o il pannello di controllo vengono persi o risultano comunque inutilizzabili.**

**Tieni premuto il pulsante funzione del dispositivo per 10 secondi per ripristinare le impostazioni di fabbrica.**

**Prova di portata**

![](<.gitbook/assets/5 (58).png>)

**Per verificare se il dispositivo è in grado di comunicare con il gateway Z-Wave o la centrale di controllo:**

**Mettere il gateway/pannello in modalità test di portata (Walk Test). Premere il pulsante funzione sul dispositivo**

**Il gateway/pannello dovrebbe visualizzare se il dispositivo si trova all'interno del raggio operativo (fare riferimento al manuale operativo del gateway/pannello).**

**Montaggio**

**Dopo aver terminato il test della portata e se sei soddisfatto che il dispositivo sia in grado di comunicare con il gateway Z-Wave nella posizione scelta, procedi al montaggio.**

**Scollegare l'alimentazione principale.**

**Allentare la vite di fissaggio inferiore e rimuovere il coperchio superiore dell'interruttore relè. Utilizzare i fori sulla base per contrassegnare la posizione di montaggio sulla parete.**

**Praticare i fori nella posizione contrassegnata e inserire i tasselli se necessario, avvitare la base nella posizione di montaggio.**

**Riposizionare il coperchio superiore e serrare la vite di fissaggio inferiore.**

![](<.gitbook/assets/6 (37).jpeg>)

**Operazione**

![](<.gitbook/assets/7 (35).jpeg>)

**Controllo relè**

**Dopo che l'interruttore relè si è unito con successo a una rete Z-Wave, il gateway/pannello di controllo può controllare in remoto il canale relè 1/2/3 per accenderlo/spegnerlo. Per i dettagli fare riferimento al gateway/pannello di controllo Z-Wave.**

**L'utente può anche premere manualmente il pulsante di commutazione 1/2/3 per accendere/spegnere il canale relè 1/2/3.**

**3**

**Informazioni sull'onda Z**

**Classe dispositivo generico: GENERICO_TIPO_INTERRUTTORE_BINARIO**

**Classe specifica del dispositivo: SPECIFICA_TIPO_ENERGIA_INTERRUTTORE_BINARIO**

**Tipo di ruolo: Always On Slave (AOS)**

**Chiavi di sicurezza supportate: S2_NON AUTENTICATO**

**Libreria: potenziato 232 slave**

**Tipo di dispositivo endpoint 1: interruttore di tipo generico binario e interruttore di accensione/spegnimento di tipo specifico**

**Tipo di dispositivo endpoint 1: interruttore di tipo generico binario e interruttore di accensione/spegnimento di tipo specifico**

**Tipo di dispositivo endpoint 1: interruttore di tipo generico binario e interruttore di accensione/spegnimento di tipo specifico**

**Supporto/controllo della classe di comando**

**Classi di comando annunciate nel NIF**

**ZWave Plus Informazioni CC**

**Servizio Trasporti CC**

**CC specifico del produttore, V2 (S2)**

**Reset del dispositivo localmente CC (S2)**

**Sicurezza_2CC**

**Livello di potenza CC (S2)**

**Versione CC, V2 (S2)**

**Associazione CC, V2 (S2)**

**Associazione multicanale CC, V3 (S2)**

**Informazioni sul gruppo di associazione CC (S2)**

**CC multicanale (S2)**

**Supervisione CC**

**Aggiornamento firmware Md CC, V4 (S2)**

**Cambia binario (S2)**

**Endpoints 123 implementa le seguenti classi di comandi**

**ZWave Plus Informazioni CC**

**Sicurezza_2CC**

**Associazione CC, V2 (S2)**

**Associazione multicanale CC, V3 (S2)**

**Informazioni sul gruppo di associazione CC (S2)**

**Supervisione CC**

**Cambia binario (S2)**

**Mappatura della classe di comando di base: Switch binario CC per endpoint 1, 2 e 3.**

![](<.gitbook/assets/8 (35).png>)

**Gruppi di Z-Wave (Associazione Command Class Versione 2)**

| **Dispositivo di root:** |                        |                        |                                                                    |
| ------------------------ | ---------------------- | ---------------------- | ------------------------------------------------------------------ |
| **ID**                   | **Nome**               | **Conteggio dei nodi** | **Descrizione**                                                    |
| **1**                    | **Ancora di salvezza** | **5**                  | **Supporta le seguenti classi di comandi:**                        |
|                          |                        |                        | **Ripristino del dispositivo localmente: attivato al ripristino.** |
|                          |                        |                        | **Switch Binary: attivato dagli endpoint**                         |
| **2**                    | **Relè EP 1**          | **5**                  | **Specchio dell'endpoint 1, gruppo 2**                             |

![](<.gitbook/assets/9 (35).png>)

**4**

![](<.gitbook/assets/10 (36).png>)

| **3**               | **Relè EP2**           | **5**                  | **Specchio dell'endpoint 2, gruppo 2**                        |
| ------------------- | ---------------------- | ---------------------- | ------------------------------------------------------------- |
| **4**               | **Relè EP 3**          | **5**                  | **Specchio dell'endpoint 3, gruppo 2**                        |
| **Punto finale 1:** |                        |                        |                                                               |
| **ID**              | **Nome**               | **Conteggio dei nodi** | **Descrizione**                                               |
| **1**               | **Ancora di salvezza** | **0**                  | **Mirror del dispositivo root, ma senza conteggio dei nodi.** |
| **2**               | **Relè EP 1**          | **5**                  | **Cambia il report binario in caso di sovraccarico.**         |
| **Punto finale 2:** |                        |                        |                                                               |
| **ID**              | **Nome**               | **Conteggio dei nodi** | **Descrizione**                                               |
| **1**               | **Ancora di salvezza** | **0**                  | **Mirror del dispositivo root, ma senza conteggio dei nodi.** |
| **2**               | **Relè EP2**           | **5**                  | **Cambia il report binario in caso di sovraccarico.**         |
| **Punto finale 3:** |                        |                        |                                                               |
| **ID**              | **Nome**               | **Conteggio dei nodi** | **Descrizione**                                               |
| **1**               | **Ancora di salvezza** | **0**                  | **Mirror del dispositivo root, ma senza conteggio dei nodi.** |
| **2**               | **Relè EP 3**          | **5**                  | **Cambia il report binario in caso di sovraccarico.**         |

![](<.gitbook/assets/11 (27).png>)![](<.gitbook/assets/12 (30).png>)![](<.gitbook/assets/13 (24).png>)![](<.gitbook/assets/14 (18).png>)

**5**
