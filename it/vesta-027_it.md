# VESTA027

**Convertitore da cavo fisso a wireless (HWC-1B)**

HWC-1B è un convertitore da cavo a wireless che converte i sensori cablati esistenti dei sistemi di allarme di sicurezza in tecnologia wireless. HWC-1B può essere installato in una posizione preferibile dove può inviare facilmente report al pannello di controllo senza più preoccuparsi dei tradizionali scenari cablati. Per raggiungere questo obiettivo, i sensori cablati esistenti sono collegati alle zone di ingresso dell'HWC-1B, quindi non è necessario sostituire i dispositivi cablati con trasmettitori individuali.

Il convertitore facile da usare è composto da 9 zone di ingresso, ciascuna può essere collegata al sensore di sicurezza esistente tramite cablaggio, ad es. Sensore PIR, contatto porta, rilevatore di fumo, sensore acqua, sensore incendio, sensore CO, rilevatore di gas, rilevatore di calore e rilevatore di rottura vetri, ecc. Ciò consente di risparmiare sui costi di installazione e offre a case e aziende maggiore comodità e funzionalità efficienti per gli utenti .

-   **Identificazione delle parti**

1.  **Indicatore LED**
    -   **LED 1 alimentazione in ingresso (verde/rosso):**

![](<.gitbook/assets/0 (29).jpeg>)

LED verde acceso: l'alimentazione CA è collegata.

LED rosso acceso: interruzione dell'alimentazione CA.

-   **LED di stato2 (giallo):**

ON: batteria scarica o scollegata.

Lampeggiante: errore di ricarica della batteria.

-   **LED3 di trasmissione (verde):**

Il LED verde lampeggia quando viene trasmesso un segnale.

-   **LED4 di calibrazione ingresso (verde):**

ON: Quando si tiene premuto il pulsante di calibrazione per 2 secondi.

ON: quando la calibrazione dell'ingresso ha esito positivo.

-   **Richiede calibrazione LED5 (rosso):**

Flash: quando è necessario calibrare l'input.

ON: Quando si tiene premuto il pulsante di calibrazione per

-   1.  secondi.

1.  **Pulsante Test/Apprendimento (SW11).**
2.  **Pulsante di calibrazione (SW12)**
3.  **Pulsante di ripristino (SW1)**
4.  **Terminale:**Z1~Z9 Zone di ingresso.

(Vedere_**Diagramma dell'applicazione**_per i dettagli.)

1.  **Pulsante interruttore antimanomissione (SW20).**
2.  **Terminale di alimentazione**(Vedere_**Diagramma dell'applicazione**_per i dettagli.)

![](<.gitbook/assets/1 (24).jpeg>)

**+12 V/TERRA:**Collegare all'alimentazione.

**12VAUX/GND:**Fornisce 12 V CC a 100 mA per alimentare i dispositivi collegati.

1.  **Batteria ricaricabile**
2.  **Connettore a due pin**

Il connettore a due pin viene utilizzato per il collegamento alla batteria ricaricabile.

1.  **Fori di montaggio**

-   **Alimentazione elettrica**

1

**Applicazione dell'adattatore di alimentazione:**

-   Accendere l'HWC-1B collegando l'adattatore CA-CC da 12 V a due fili al terminale +12 V/GND.
-   Quando l'alimentazione viene interrotta e ripristinata, HWC-1B trasmetterà rispettivamente il segnale di guasto CA e di ripristino.

**Batteria ricaricabile:**

-   A 1,2 V\*All'interno dell'HWC-1B è installata una batteria ricaricabile Ni-MH AAA da 8 750 mAh che funge da backup in caso di interruzione di corrente. La batteria non è collegata in fabbrica. Collegare la batteria se si desidera utilizzarla come alimentazione di riserva.
-   HWC-1B caricherà automaticamente la batteria ricaricabile quando viene fornita l'alimentazione e la batteria ricaricabile è collegata. Quando l'alimentazione viene interrotta, HWC-1B passerà all'utilizzo della batteria ricaricabile e continuerà a funzionare.
-   Quando la batteria ricaricabile è scarica, l'HWC-1B trasmetterà il segnale di batteria scarica. Quando la batteria è stata caricata, HWC-1B trasmetterà il segnale di ripristino della batteria.

**Potenza in uscita:**

-   -   HWC-1B può fornire alimentazione a 12 V, 100 mA ai dispositivi collegati tramite il terminale di alimentazione.
-   **Batteria ricaricabile**
    -   HWC-1B caricherà automaticamente la batteria quando viene collegata l'alimentazione. Quando l'alimentazione viene interrotta, HWC-1B passerà all'utilizzo della batteria ricaricabile e continuerà a funzionare.
-   **Diagramma dell'applicazione**

![](<.gitbook/assets/2 (22).jpeg>)

Il terminale (Z1~Z9 zone di ingresso) consentono di collegare i sensori cablati esistenti al convertitore HWC-1B:

-   Ciascuna zona di ingresso è disponibile solo per un sensore cablato.
-   È essenziale che tutte le zone di ingresso utilizzate dispongano di una resistenza EOL (con un valore compreso tra 1k e 10k ohm).
-   Mantenere le zone di installazione esistenti che già dispongono di resistenza EOL (con un valore da 1k a 10k ohm).
-   Per un circuito NC senza resistenza EOL, aggiungerne uno in serie al circuito.
-   Per un circuito NO senza un resistore EOL, aggiungerne uno in parallelo (attraverso) il circuito. Dovrebbe trovarsi alla fine del circuito, lontano dal pannello di controllo.

_\\<NOTE>_

-   -   Se si desidera modificare i cavi sulla zona di ingresso, spegnere prima l'HWC-1B, quindi modificare la posizione di ingresso dei cavi come preferito e riaccendere l'HWC-1B. Premere il pulsante di calibrazione per finalizzare il processo di modifica.
-   **(SW12) Pulsante di calibrazione**

Dopo aver collegato i sensori esistenti all'HWC-1B, avviare il processo di calibrazione che consente all'HWC-1B di apprendere quale zona sarà attiva e quali resistori EOL verranno utilizzati. Qualsiasi zona non utilizzata/aperta non verrà riconosciuta e segnalata alla Centrale.

-   Assicurarsi che tutte le zone siano ben collegate.
-   Tenere premuto il pulsante Calibrazione**(Sop12)**per 2 secondi. Sia il LED4 (verde) che il LED5 (rosso) si accendono.
-   Una volta completata la calibrazione, il LED5 (rosso) si spegnerà. Il LED4 (verde) resterà acceso per indicare che la calibrazione è riuscita.
-   Quando la calibrazione fallisce, il LED4 (verde) si spegne, il LED5 (rosso) lampeggia per indicare l'errore.

_\\<NOTE>_

-   La zona 1 deve essere cablata affinché HWC-1B funzioni normalmente e utilizzi la funzione di calibrazione.

2

-   **(SW11) Apprendimento / Test del cammino**
    -   Assicurarsi che i dispositivi siano collegati e calibrati correttamente prima di procedere con l'apprendimento.
    -   Fare riferimento al manuale del pannello di controllo per mettere il pannello in modalità apprendimento.
    -   Premere il pulsante Prova/Apprendimento**SW11**per inviare il codice di apprendimento alla Centrale.
    -   Fare riferimento al manuale operativo del pannello di controllo per completare il processo di apprendimento.
    -   Il pulsante Test/Apprendimento viene utilizzato anche per la funzione Walk Test. Mettere il pannello in modalità Walk Test e premere il pulsante per verificare la portata e la potenza del segnale.

![](<.gitbook/assets/3 (36).png>)

_\\<NOTE>_

Numero di zona

-   -   Quando HWC-1B viene acquisito nel sistema di allarme, ciascuna zona attiva verrà riconosciuta come tipo di dispositivo Contatto porta. Gli utenti possono modificare il nome del dispositivo e selezionare il tipo di allarme per ciascun sensore collegato nella pagina Modifica dispositivo.
    -   Ciascuna zona di ingresso appresa invierà un codice RF individuale alla centrale. Il numero della zona è indicato dall'ultima cifra dell'ID del dispositivo.
    -   Lo stato dell'HWC-1B (batteria scarica, manomissione, ecc.) viene trasmesso tramite la Zona 1.
-   **Supervisione**
    -   Il convertitore trasmetterà automaticamente periodicamente i segnali di supervisione al pannello di controllo a intervalli casuali da 30 a 50 minuti in modalità di funzionamento normale.
    -   Se il Pannello di controllo non ha ricevuto il segnale dal Convertitore per un periodo di tempo preimpostato, il Pannello di controllo indicherà che un particolare Convertitore sta riscontrando un problema di segnale assente.
-   **(SW20) Interruttore antimanomissione**
    -   È progettato per proteggere dall'apertura non autorizzata del coperchio. Quando l'interruttore antimanomissione viene attivato, HWC-1B emetterà un segnale di apertura antimanomissione al pannello di controllo per la segnalazione.
-   **Procedure di installazione**

L'HWC-1B può essere montato a parete con la staffa di montaggio fornita o con i fori di montaggio preforati. Si prega di seguire i passaggi seguenti per procedere.

1.  **Con staffa di montaggio:**
2.  Estrarre la staffa di montaggio fornita.
3.  Utilizzare i 2 fori di montaggio centrali sulla staffa di montaggio per contrassegnare le posizioni sulla parete.
4.  Praticare dei fori nella posizione di montaggio e installare i tasselli, se necessario.
5.  Installare le viti di montaggio nella posizione contrassegnata come mostrato di seguito.

![](<.gitbook/assets/4 (22).jpeg>)

3

1.  Fissare l'HWC-1B sulla staffa come mostrato di seguito.

![](<.gitbook/assets/5 (15).jpeg>)

1.  Tenere l'HWC-1B e spingerlo delicatamente verso il basso come mostrato di seguito.

![](<.gitbook/assets/6 (19).jpeg>)

**B: Con fori di montaggio preforati:**

-   1.  Premere verso il basso i fori preforati sui bordi dell'HWC-1B e contemporaneamente sollevare delicatamente il coperchio anteriore.
    2.  Utilizzare i 4 fori di montaggio attorno al bordo del coperchio posteriore per contrassegnare le posizioni dei fori sulla parete.
    3.  Praticare i fori nella posizione di montaggio e installare i tasselli.
    4.  Avvitare la cover posteriore nella posizione contrassegnata.
    5.  Sostituire la copertura anteriore. L'installazione è ora completata.
-   **Ripristino delle impostazioni di fabbrica**

Il ripristino delle impostazioni di fabbrica cancellerà HWC-1B da tutte le informazioni sulle zone calibrate.

1.  Scollegare sia l'alimentazione che la batteria.
2.  Tieni premuto il tasto**Pulsante Test/Apprendimento (SW11)**, tenendo premuto il pulsante, applicare contemporaneamente l'alimentazione per accendere l'HWC-1B.
3.  Continua a tenere premuto il pulsante per 3 secondi.
4.  LED1~3 si accenderà. Rilasciare il pulsante quando i LED si accendono. Il ripristino delle impostazioni di fabbrica è completo.

4
