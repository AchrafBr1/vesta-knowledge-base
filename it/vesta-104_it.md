# VESTA 104

-   Termostato (serie TMST-15ZW)
-   introduzione

TMST-15ZW è un termostato alimentato a batteria. È progettato per essere incorporato nel sistema di riscaldamento e raffreddamento domestico per il controllo dell'ambiente domestico. Il termostato può essere azionato manualmente utilizzando lo schermo LCD e i pulsanti o accedendo in remoto tramite il coordinatore Z-Wave. È dotato di modalità di raffreddamento e riscaldamento con setpoint di temperatura e programmazione automatica per controllare facilmente l'ambiente domestico.

-   ![](<.gitbook/assets/0 (14).jpeg>)Identificazione delle parti

**1. Display LCD**

Il display LCD visualizza le seguenti informazioni:

![](<.gitbook/assets/1 (21).png>)

1.  Icona modalità riscaldamento: quando visualizzata, il termostato è in modalità riscaldamento.
2.  Icona modalità Raffreddamento: quando visualizzata, il termostato è in modalità Raffreddamento.
3.  Icona del livello della batteria: visualizzata solo quando il livello della batteria è al 25%, 50% e 75%. L'icona scomparirà quando il livello della batteria è inferiore al 15%.
4.  Connettività di rete Z-Wave:

Quando viene visualizzato, indica che il termostato non è ancora stato acquisito in alcun gateway/pannello o quando il dispositivo perde la connessione alla rete Z-Wave corrente.

1.  Modalità: selezione modalità, modalità remota e offset
2.  Programmazione: il termostato eseguirà l'impostazione del programma programmato.
3.  Lettura/punto di regolazione della temperatura

**2. Pulsante Giù (-).**

\-Premere il pulsante e lo schermo LCD visualizzerà il setpoint, la modalità e l'impostazione corrente per 5 secondi. Entro 5 secondi, premere il pulsante Giù (-) per diminuire il setpoint.

\-Tenere premuto per 3 secondi per accedere alla modalità di programmazione.

**3. Pulsante Su (+).**

\-Premere il pulsante e lo schermo LCD visualizzerà il setpoint, la modalità e l'impostazione corrente per 5 secondi. Entro 5 secondi, premere il pulsante SU (+) per aumentare il setpoint.

\-Premere 3 volte entro 1,5 secondi per trasmettere il codice di apprendimento e sullo schermo LCD verrà visualizzato "Joi NET".

![](<.gitbook/assets/2 (25).png>)

**4. Foro per il montaggio a parete**

**5. Vano batteria**

Inserire 2 batterie alcaline AA.

**6. Terminali relè (rimuovere il coperchio relè per accedere)**

Morsetti relè 230V 5A NO/COM/NC.

Collegare al sistema di riscaldamento/raffreddamento domestico.

**Caratteristiche**

-   _Rilevamento batteria e batteria scarica_

Il termostato utilizza 2 batterie alcaline AA come fonte di alimentazione. Il sensore riporterà la percentuale della batteria al gateway/pannello di controllo rispettivamente al 100% (0x64), 75% (0x4B), 50% (0x32) e 25% (0x19). Quando il livello della batteria è inferiore al 15%, il sensore invierà 0xFF al gateway/pannello di controllo.

-   _Controllo relè_

Il termostato controlla il sistema di riscaldamento/raffreddamento domestico tramite il controllo del relè. Aprire e capovolgere il coperchio posteriore, rimuovere il coperchio interno sul relè per rivelare i terminali per il cablaggio. Quando si collega il termostato, collegare il cavo attraverso l'apertura centrale sul coperchio posteriore.

![](<.gitbook/assets/3 (4) (1).jpeg>)

-   _**Controllo della modalità**_

Il Termostato ha due modalità di funzionamento: modalità Locale e modalità Programmata.

-   **Modalità locale:**

La modalità locale consente la regolazione della funzione Caldo/Freddo del termostato e dei punti di regolazione utilizzando i pulsanti del termostato.

-   **Modalità pianificata:**

La modalità programmata consente la modalità Termostato e il controllo del setpoint tramite Gateway una volta completato l'apprendimento.

Per modificare la modalità operativa, fare riferimento a “_Modalità di programmazione_" per maggiori dettagli.

-   _**Riscaldamento/Raffreddamento e controllo del setpoint**_

Il riscaldamento/raffreddamento del termostato e il setpoint possono essere regolati localmente solo quando il termostato è impostato sulla modalità locale.

In modalità locale, premere il pulsante**SU**(**+**) O**Giù (-)**pulsante per regolare il setpoint.

In modalità programmata, utilizzare il gateway/pannello di controllo per regolare il setpoint da remoto.

Intervallo setpoint riscaldamento: 9°C~30°C.

Intervallo di setpoint freddo: 11°C~32°C

-   _**Telecomando**_

Dopo che il termostato si è unito a una rete Z-Wave, è possibile controllarlo tramite il coordinatore di rete o il gateway Z-Wave. Per ulteriori informazioni fare riferimento al manuale del coordinatore/gateway Z-Wave.

Le seguenti funzioni sono disponibili solo per l'impostazione tramite coordinatore Z-Wave e gateway:

-   **Programma:**

È possibile programmare la configurazione del programma solo tramite il coordinatore/gateway di rete Z-Wave.

Impostazione del programma: è possibile programmare fino a 5 programmi per ogni giorno della settimana con modalità, setpoint e ora di inizio.

Controllo della pianificazione:

Normale: il termostato eseguirà di conseguenza l'impostazione del programma programmato.

Hold – Il termostato ignorerà la programmazione attualmente programmata ed eseguirà la programmazione successiva quando inizierà

Nessuna programmazione – Il termostato non eseguirà alcuna programmazione impostata finché non verrà nuovamente impostato su Normale.

-   _**Rilevamento della temperatura**_
-   Il termostato è dotato di sensori di temperatura integrati e visualizzerà la lettura della temperatura sul display LCD.
-   Il termostato trasmetterà regolarmente i segnali di temperatura in base all'impostazione. L'intervallo predefinito di fabbrica è 5 minuti.
-   È inoltre possibile premere una volta il pulsante di rete Z-Wave per trasmettere manualmente un segnale di temperatura.
-   _**Modalità di sospensione Z-Wave**_
-   Il Termostato entrerà in modalità Sospensione Z-Wave (per risparmiare energia) dopo essersi svegliato per un breve periodo di tempo. Durante la modalità di sospensione Z-Wave, i gateway Z-Wave o i pannelli di controllo non sono in grado di inviare comandi al Termostato
-   _**Modalità di programmazione**_

**Passo 1.**Premere e tenere premuto il pulsante Giù (-) per 3 secondi per accedere alla modalità di programmazione.

**Passo 2.**Sono disponibili 3 funzioni per la programmazione, comprese le funzioni del termostato, il controllo del relè remoto e il setpoint

Compensare. È possibile premere il pulsante SU (+) o Giù (-) per cambiare modalità.

**Passaggio 3.**Dopo aver terminato la selezione, attendere alcuni secondi affinché il Termostato entri nella modalità selezionata.

**Funzioni del termostato (riscaldamento e raffreddamento):**

In questa modalità, sullo schermo LCD verrà visualizzato "Pro Mod".

![](<.gitbook/assets/4 (22).png>)

È possibile selezionare le modalità di riscaldamento/raffreddamento. Premere il pulsante SU (+) per selezionare Riscaldamento e il pulsante Giù (-) per selezionare Raffreddamento.

Riscaldamento Raffreddamento

![](<.gitbook/assets/5 (15).png>)

Dopo aver terminato la selezione, attendere alcuni secondi affinché il Termostato esca automaticamente dalla modalità di impostazione. Il Termostato entrerà nell'ultima modalità selezionata.

**Controllo del relè remoto:**

In questa modalità, sullo schermo LCD verrà visualizzato "Pro RM".

La modalità remota consente di controllare il relè remoto tramite il pannello di controllo quando la funzione è abilitata. Il Termostato non controllerà il relè locale in Modalità Remota.

![](<.gitbook/assets/6 (10).png>)

-   Se la modalità remota è disabilitata, sullo schermo LCD verrà visualizzato "dS RM".
-   Se la modalità remota è abilitata, sullo schermo LCD verrà visualizzato "En RM".

![](<.gitbook/assets/7 (7) (1).png>)

**Scostamento del setpoint:**

In questa modalità, sullo schermo LCD verrà visualizzato "Pro OFS". La funzione Setpoint Offset consente di compensare la deviazione. Per calcolare l'offset del setpoint, è sufficiente sottrarre la temperatura ambiente dalla temperatura del dispositivo. In modalità locale, tenere premuto il pulsante Giù (-) per 3 secondi per accedere alla modalità di programmazione. Dopo aver terminato la selezione, attendere alcuni secondi affinché il Termostato entri nella selezione della modalità.

![](<.gitbook/assets/8 (7) (1).png>)

Ad esempio: se la temperatura del dispositivo è 20°C e la temperatura ambiente è 18°C, l'offset del setpoint = 18 – 20 = -2°C.

Dopo aver applicato l'offset del setpoint, il dispositivo funzionerà in base alla temperatura regolata.

Ad esempio: se la lettura della temperatura del dispositivo è 20°C, l'offset del setpoint è -2°C, il dispositivo funzionerà utilizzando 18°C ​​come riferimento effettivo.

-   _**Aggiunta di dispositivi (inclusione)**_

Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o altre applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete.

-   Caricare due batterie alcaline AA nel vano batterie.
-   Mettere il pannello di controllo Z-Wave in modalità Inclusione (fare riferimento al manuale del pannello di controllo Z-Wave).
-   Entro 1,5 secondi, premere il pulsante Su (+) 3 volte per trasmettere il codice di apprendimento e sullo schermo LCD verrà visualizzato "Joi NET". Se il Termostato si connette con successo a una rete, l'icona di connessione Z-Wave scomparirà dal display LCD.
-   Fare riferimento al manuale operativo del gateway Z-Wave o del pannello di controllo per completare il processo di aggiunta.
-   Se il dispositivo è già stato aggiunto (incluso) in un altro gateway/pannello di controllo Z-Wave o se non è possibile aggiungere il dispositivo all'attuale gateway/pannello di controllo Z-Wave, provare prima a rimuoverlo (vedere Rimozione del dispositivo).
-   _**Rimozione del dispositivo (esclusione)**_

Il dispositivo deve essere rimosso dalla rete Z-Wave esistente prima di essere aggiunto a un'altra.

**Modalità di esclusione:**

-   Mettere il gateway Z-Wave o il pannello di controllo in modalità di esclusione (fare riferimento al manuale Z-Wave o al pannello di controllo).
-   Entro 1,5 secondi, premi il pulsante Su (+) 3 volte e il dispositivo verrà rimosso dalla rete Z-Wave. Se il Termostato viene rimosso con successo dalla rete, l'icona di connessione Z-Wave apparirà sul display LCD.

**Ripristino delle impostazioni di fabbrica**

Factory resetting the device will restore it to factory default settings (i.e. not included into any Z-Wave network). Please only use this procedure if the Z-Wave gateway or control panel is lost or otherwise inoperable.

-   Tieni premuto il pulsante Su (+) del dispositivo per 10 secondi per ripristinare le impostazioni di fabbrica.
-   _**Installazione**_

Il termostato è progettato per essere montato a parete utilizzando i fori di montaggio sul coperchio posteriore.

1.  Prima del montaggio, assicurarsi di completare prima il cablaggio del relè attraverso l'apertura sul coperchio posteriore.
2.  Utilizzare i fori di montaggio sul coperchio posteriore come modello per contrassegnare la posizione di montaggio sulla parete.
3.  Praticare dei fori sulla parete e inserire i tasselli, se necessario, quindi avvitare il coperchio posteriore nella posizione di montaggio.
4.  Posizionare il corpo principale del termostato sul coperchio posteriore, l'installazione è completa.

**Informazioni sull'onda Z**

**Tipo di dispositivo:**Termostato

**Tipo di ruolo:**Segnalazione dello schiavo addormentato (RSS)

**Supporto/controllo della classe di comando**

**Supporto CC obbligatorio:**Associazione CC, v2

Associazione Gruppo Informazioni CC

Batteria CC

Dispositivo reimpostato localmente CC

CC specifico del produttore, v2

Versione CC, v2

Livello di potenza CC

Z-Wave Plus Informazioni CC, v2

Associazione multicanale CC, v2

Sveglia CC

Supervisione CC

Modalità termostato CC, v3

Setpoint termostato CC, v3

Stato operativo termostato CC

Sensore multilivello CC

Aggiornamento firmware CC, v2 (solo versione OTA)

_**Gruppi Z-Wave (Associazione Classe di Comando Versione 2)**_

Gruppo 1 per “LifeLine”:

Batteria CC (COMANDO_CLASSE_DI BASE)

Dispositivo reimpostato localmente CC

Modalità termostato CC, V3

Setpoint termostato CC, V3

Stato operativo termostato CC

Sensore multilivello CC

Gruppo 2 per lo stato operativo del termostato:

Stato operativo termostato CC
