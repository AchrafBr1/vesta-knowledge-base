# VESTA171

**Valvola termostatica per radiatore TRV-1ZW**

**introduzione**

TRV-1ZW è una valvola per radiatore Z-Wave progettata per controllare la temperatura circostante controllando il flusso di acqua calda dei radiatori nella rete Z-Wave, ovvero la temperatura della stanza interna.

The Radiator Valve is a Z-Wave enabled device and is fully compatible with any Z-Wave enabled network.

Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. Sfruttando la rete mesh Z-Wave, i comandi possono essere indirizzati a destinazione tramite prodotti Z-Wave intermedi di "ascolto".

**Identificazione delle parti**

1.  **Tappo della valvola**
2.  **Display LCD**

![](<.gitbook/assets/0 (49).png>)![](<.gitbook/assets/1 (56).jpeg>)

1.  ![](<.gitbook/assets/2 (51).jpeg>)**SU**quando il dispositivo è già aggiunto alla rete Z-Wave.
2.  ![](<.gitbook/assets/3 (46).jpeg>)**Indicatore di batteria scarica.**
3.  ![](<.gitbook/assets/4 (45).jpeg>)Acceso: dispositivo impostato sulla temperatura predefinita di 17 °C.

![](<.gitbook/assets/5 (28).jpeg>)Lampeggiante: chiusura della valvola.

![](<.gitbook/assets/6 (38).jpeg>)Acceso: dispositivo impostato sulla temperatura predefinita di 21 °C.

![](<.gitbook/assets/7 (36).jpeg>)Flash: apertura della valvola.

1.  **Auto / Manual Mode.**
2.  **Funzione potenziamento.**
3.  **Finestra aperta**.
4.  **Indicatore di temperatura.**

![](<.gitbook/assets/8 (36).png>)

**Altri: InS**: All'accensione del dispositivo (anche per il periodo di apprendimento).

**C'è:**funzionamento del motore del dispositivo.

**F1/F:**la valvola è bloccata,**Categoria:**nessuna valvola installata.

**3. Pulsanti funzione**

\-**Manual/Auto:**Accedere alla modalità Manuale o Automatica.

\-**Boost/onda Z:**Accelera il processo di riscaldamento/aggiungilo alla rete Z-Wave.

\-![](<.gitbook/assets/9 (21).jpeg>)Premi questo pulsante per cambiare istantaneamente la temperatura diurna e notturna.

_**Giorno predefinito**_![](<.gitbook/assets/10 (16).jpeg>)_temperatura: 21_°C_,**Notte predefinita**_![](<.gitbook/assets/11 (21).jpeg>)_temperatura: 17_°C

1.  **Termometro**
2.  **Manopola di controllo**

Regolare manualmente la temperatura.

**6. Vano batteria**

La valvola per radiatore è alimentata da due batterie alcaline AA da 1,5 V.

1

**Caratteristiche**

![](<.gitbook/assets/12 (31).png>)

-   _**Batteria**_

La valvola per radiatore utilizza due batterie alcaline AA da 1,5 V come fonte di alimentazione. La valvola del radiatore riporterà la percentuale della batteria al gateway/pannello di controllo rispettivamente al 100%, 75%, 50%, 25%. Se la tensione della batteria è bassa (25%), un segnale di batteria scarica verrà inviato al gateway/pannello di controllo per avvisare l'utente.

La valvola del radiatore è in grado di rilevare se la batteria è scarica. Quando viene rilevata una tensione di batteria bassa, viene emesso un segnale di batteria scarica

verrà inviato al gateway/pannello di controllo Z-Wave e sul display LCD verrà visualizzato![](<.gitbook/assets/13 (20).jpeg>)icona per avvisare l'utente.

![](<.gitbook/assets/14 (19).png>)

-   _**Accensione/Modalità manuale/automatica**_

**Accensione**: Quando la valvola del radiatore si accende, il suo motore inizia a funzionare visualizzando il display LCD**InS**, il dispositivo è pronto per l'installazione e inizia il processo di apprendimento. (Vedere**Installazione**per dettagli)

**Modalità manuale:**Nella modalità Manuale è possibile utilizzare le seguenti funzioni:

-   ![](<.gitbook/assets/15 (17).jpeg>)Pulsante: cambia istantaneamente la temperatura giorno/notte.
-   **Pulsante potenzia:**Accelera il riscaldamento/Aggiungi dispositivo al gateway Z-Wave o al pannello di controllo.
-   **Manopola di controllo**: Controllo della temperatura, impostato su ON (modalità stagione estiva) e OFF (modalità stagione invernale).

**Auto Mode:**La modalità Auto è disponibile solo quando il dispositivo viene appreso tramite un pannello di controllo. Dopo l'apprendimento con il pannello di controllo è possibile controllare e impostare automaticamente la programmazione oraria per la valvola del radiatore tramite il pannello di controllo (fare riferimento al manuale del pannello di controllo per i dettagli). Nella modalità automatica, è possibile utilizzare le stesse funzioni della modalità manuale. tranne la manopola di controllo impostata sulla funzione ON e OFF.

![](<.gitbook/assets/16 (21).png>)

-   _**Antigelo**_

Quando la valvola del radiatore rileva un pericolo di gelo, aprirà automaticamente la valvola per far fluire l'acqua calda al fine di mantenere la temperatura e prevenire ulteriore gelo.

![](<.gitbook/assets/17 (17).png>)

-   _**Anticalcificazione**_

La valvola del radiatore aprirà e chiuderà la valvola settimanalmente per prevenire la calcificazione. Durante il processo anticalcare il display LCD visualizzerà a**CAL**.

Il valore predefinito per il processo anticalcare è ogni sabato alle 23:00.

![](<.gitbook/assets/18 (21).png>)

-   _**Funzione potenziamento**_

Tenere premuto il pulsante Boost per 3 secondi per accelerare temporaneamente il processo di riscaldamento aprendo ulteriormente la valvola. La funzione boost dura 5 minuti (display LCD: conto alla rovescia di 300 secondi). Se desideri annullare la funzione boost, tieni premuto nuovamente il pulsante per 3 secondi.

![](<.gitbook/assets/19 (22).png>)

-   _**Scostamento del setpoint**_

Il dispositivo viene solitamente installato nell'angolo della stanza e vicino al tubo del riscaldamento. Di conseguenza la lettura della temperatura potrebbe discostarsi dalla temperatura ambiente al centro della stanza. Utilizzare la funzione Offset del setpoint per compensare la deviazione.

Per calcolare l'offset del setpoint, è sufficiente sottrarre la temperatura ambiente dalla temperatura del dispositivo.

Esempio: se la temperatura del dispositivo è 20°C e la temperatura ambiente è 18°C, l'offset del setpoint =18 – 20= -2°C.

Dopo aver applicato l'offset del setpoint, il dispositivo funzionerà in base alla temperatura regolata.

Ad esempio: se la lettura della temperatura del dispositivo è 20°C, l'offset del setpoint è -2°C, il dispositivo funzionerà utilizzando 18°C ​​come riferimento effettivo.

Per programmare l'Offset del setpoint:

-   1.  Tieni premuto il tasto![](<.gitbook/assets/20 (11).jpeg>)per 3 secondi per accedere alla regolazione dell'offset.
    2.  Ruotare la manopola di controllo sulla temperatura di offset desiderata.
    3.  Premere un tasto qualsiasi per terminare e uscire dalla regolazione dell'offset.
-   _**Finestra aperta**_

Se la valvola del radiatore rileva un rapido calo della temperatura interna aprendo la finestra, la valvola del radiatore attiverà la funzione Finestra aperta chiudendo parzialmente la valvola per ridurre l'impostazione della temperatura per 15 minuti. IL

Il display LCD visualizzerà il simbolo, il dispositivo controllerà la temperatura ogni minuto. Dopo 15 minuti, la valvola del radiatore tornerà alla temperatura impostata con l'apertura della valvola, la funzione finestra aperta si chiude.

-   _**Manopola di controllo**_

Ruotare la manopola di controllo per regolare la temperatura, ruotare in senso orario per ridurre la temperatura e in senso antiorario per aumentare la temperatura. L'intervallo di temperatura regolabile è compreso tra 5°C e 30°C. Se si ruota la manopola di controllo a una temperatura inferiore a 5°C su On, dopo 1 minuto, la valvola del radiatore aprirà completamente la valvola, per preservare la carica della batteria, se si ruota la manopola di controllo a una temperatura inferiore a 5°C su Off, dopo 1 minuto, la valvola del radiatore chiuderà completamente la valvola. Per disattivare lo stato ON/OFF, ruotare la manopola di controllo o premere

pulsante . La funzione Boost non è disponibile con la manopola di controllo impostata sullo stato ON/Off.

**SU:**Quando è impostata su ON, la valvola è completamente aperta. Questa funzione viene utilizzata per preservare la durata della batteria durante l'estate, quando non è necessario il riscaldamento. Non utilizzare questa funzione in inverno quando il riscaldamento è attivato,

2

altrimenti la temperatura ambiente aumenterà in modo incontrollato.

**SPENTO:**Quando viene impostata su OFF, la valvola è completamente chiusa. Questa funzione viene utilizzata quando il riscaldamento è attivato ma il riscaldamento non è necessario in una stanza senza occupanti.

-   _**Funzione di blocco dei tasti**_

Tenere premuti sia il pulsante Auto/Manuale che il pulsante per 3 secondi per abilitare la funzione di blocco dei tasti. Se

successful the LCD will display  symbol. All keys and Control Knob actions will not respond**.**Se desideri

per annullare la funzione di blocco dei tasti, tenere premuti sia il pulsante Auto/Manuale che il pulsante per 3 secondi.

-   _**Telecomando**_

Dopo che la valvola per radiatore si è unita a una rete Z-Wave, è possibile controllarla tramite il coordinatore di rete o il gateway Z-Wave. Per ulteriori informazioni fare riferimento al manuale del coordinatore/gateway Z-Wave. Le seguenti funzioni sono disponibili solo per l'impostazione tramite coordinatore Z-Wave e gateway:

-   -   **Programma:**

È possibile programmare la configurazione del programma solo tramite il coordinatore/gateway di rete Z-Wave.

Impostazione del programma: è possibile programmare fino a 5 programmi per ogni giorno della settimana con modalità, setpoint e ora di inizio.

Controllo della pianificazione:

Normale: la valvola del radiatore eseguirà di conseguenza l'impostazione del programma programmato.

Nessuna programmazione – La valvola del radiatore non eseguirà alcuna programmazione impostata finché non verrà nuovamente impostata su Normale.

-   _**Aggiunta di dispositivi (inclusione)**_

Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o altre applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete.

-   Rimuovere il coperchio posteriore della valvola del radiatore e inserire 2 batterie alcaline AA per alimentare il radiatore

Valvola, verrà visualizzato il display LCD**InS**e l'icona lampeggerà per indicare che il motore della valvola del radiatore è in funzione.

-   Inserisci il pannello di controllo Z-Wave**Modalità di inclusione**(fare riferimento al manuale del pannello di controllo Z-Wave).
-   Entro 1,5 secondi, premi il pulsante Boost 3 volte
-   Fare riferimento al manuale operativo del gateway Z-Wave o del pannello di controllo per completare il processo di aggiunta.
-   Se il dispositivo è già stato aggiunto (incluso) in un altro gateway/pannello di controllo Z-Wave, o se non è possibile aggiungere il dispositivo all'attuale gateway/pannello di controllo Z-Wave, provare prima a rimuoverlo (vedere_**Rimozione del dispositivo**_).
-   Quando il motore smette di funzionare e l'icona diventa fissa, collegare il cappuccio della valvola al tubo.
-   Ruotare il cappuccio della valvola in senso orario per serrare la valvola del radiatore.
-
-   _**Rimozione del dispositivo (esclusione)**_

Il dispositivo deve essere rimosso dalla rete Z-Wave esistente prima di essere aggiunto a un'altra.**Modalità di esclusione**

-   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale Z-Wave o al pannello di controllo).

3

-   -   Entro 1,5 secondi, premi il pulsante Boost 3 volte e il dispositivo verrà rimosso dalla rete Z-Wave.

**Ripristino delle impostazioni di fabbrica**

Il ripristino delle impostazioni di fabbrica del dispositivo lo ripristinerà alle impostazioni predefinite di fabbrica (ovvero non incluso in alcuna rete Z-Wave). Utilizzare questa procedura solo se il gateway Z-Wave o il pannello di controllo vengono persi o risultano comunque inutilizzabili.

-   -   Tieni premuto il pulsante Boost per 10 secondi per ripristinare le impostazioni di fabbrica.
-   _**Prova di portata**_

Per verificare se il dispositivo è in grado di comunicare con il gateway Z-Wave o la centrale di controllo:

-   -   Mettere il gateway/pannello in modalità test di portata (Walk Test).
    -   Tieni premuto il pulsante Boost per un secondo.
    -   Il gateway/pannello dovrebbe essere visualizzato se il dispositivo si trova all'interno del raggio d'azione (fare riferimento al manuale operativo del gateway/pannello).
-   _**Modalità di sospensione Z-Wave**_
    -   La valvola del radiatore entrerà in modalità sospensione Z-Wave (per risparmiare energia) dopo essersi attivata per un breve periodo di tempo (~10 secondi). Durante la modalità di sospensione Z-Wave, i gateway Z-Wave o i pannelli di controllo non sono in grado di inviare comandi alla valvola del radiatore.
    -   Per programmare la valvola del radiatore utilizzando il gateway/pannello di controllo Z-Wave, inviare i comandi alla valvola del radiatore entro il periodo di riattivazione.
-   _**Comando del set di configurazione**_
    -   La valvola del radiatore consente all'utente di impostare i valori di ritardo di apertura e di ritardo di chiusura. Il valore predefinito è 2 minuti (max: 5 minuti).
    -   Se sono impostati 4 minuti per il ritardo di apertura, il dispositivo invierà un report sullo stato di funzionamento aperto 4 minuti dopo l'apertura della valvola. Se sono impostati 4 minuti per il ritardo di chiusura, la valvola verrà chiusa 4 minuti dopo l'invio del rapporto di chiusura dello stato di funzionamento.
    -   La valvola è inoltre dotata di report periodico sullo stato; il valore predefinito è 60 minuti. Il timer verrà ripristinato ogni volta che lo stato operativo viene modificato.
    -   Il comando Configuration Set viene utilizzato per impostare il valore di un parametro di configurazione:

| 7                             |                                                      | 6                                          |                                              | 5        |                                  | 4                          |   | 3 |   | 2           |   |          | 1 |   | 0 |
| ----------------------------- | ---------------------------------------------------- | ------------------------------------------ | -------------------------------------------- | -------- | -------------------------------- | -------------------------- | - | - | - | ----------- | - | -------- | - | - | - |
|                               |                                                      |                                            | Classe comando=COMANDO_CLASSE_CONFIGURAZIONE |          |                                  |                            |   |   |   |             |   |          |   |   |   |
|                               |                                                      |                                            |                                              |          | Comando=CONFIGURAZIONE_IMPOSTATO |                            |   |   |   |             |   |          |   |   |   |
|                               |                                                      |                                            |                                              |          |                                  | Numero del parametro       |   |   |   |             |   |          |   |   |   |
| Predefinito                   |                                                      |                                            |                                              |          | Riservato                        |                            |   |   |   |             |   | Misurare |   |   |   |
|                               |                                                      |                                            |                                              |          |                                  | Valore di configurazione 1 |   |   |   |             |   |          |   |   |   |
|                               |                                                      |                                            |                                              |          |                                  |                            | … |   |   |             |   |          |   |   |   |
|                               |                                                      |                                            |                                              |          |                                  | Configurazione Valore N    |   |   |   |             |   |          |   |   |   |
|                               |                                                      |                                            |                                              |          |                                  |                            |   |   |   |             |   |          |   |   |   |
| COMANDO_CLASSE_CONFIGURAZIONE |                                                      | Numero del parametro                       |                                              | Misurare |                                  | Valore                     |   |   |   |             |   |          |   |   |   |
|                               |                                                      |                                            |                                              |          |                                  |                            |   |   |   |             |   |          |   |   |   |
|                               |                                                      | Punto di riferimento_compensare            |                                              |          |                                  | 0                          |   |   |   |             | 2 | 0000     |   |   |   |
|                               |                                                      |                                            |                                              |          |                                  |                            |   |   |   |             |   |          |   |   |   |
|                               | Aziona il ritardo del report di apertura dello stato |                                            | 1                                            |          |                                  |                            |   | 1 |   | 2 (minuti)  |   |          |   |   |   |
|                               |                                                      |                                            |                                              |          |                                  |                            |   |   |   |             |   |          |   |   |   |
|                               | Ritardo rapporto chiusura stato operativo            |                                            | 2                                            |          |                                  |                            |   | 1 |   | 2 (minuti)  |   |          |   |   |   |
|                               |                                                      |                                            |                                              |          |                                  |                            |   |   |   |             |   |          |   |   |   |
|                               |                                                      | Rapporto sul periodo dello stato operativo |                                              | 3        |                                  |                            |   |   | 1 | 60 (minuti) |   |          |   |   |   |
|                               |                                                      |                                            |                                              |          |                                  |                            |   |   |   |             |   |          |   |   |   |

-   Valore di offset del setpoint: 0x0064 = 100 = 1,00 ℃.

**Informazioni sull'onda Z**

**Tipo di dispositivo:**Termostato

**Tipo di ruolo:**Ascoltando lo schiavo addormentato (LSS)

**Supporto/controllo della classe di comando**

**Supporto CC obbligatorio:**Associazione CC, v2 o successiva

Associazione Gruppo Informazioni CC

Batteria CC

Device Reset Locally CC

CC specifico del produttore

Livello di potenza CC

Versione CC, v2 o successiva

Z-Wave Plus Informazioni CC

Modalità termostato CC

Setpoint termostato CC

Programma CC

4

Sensore multilivello CC

Ora CC

Metadati aggiornamento firmware CC

Stato operativo termostato CC

-   _**Gruppi di Z-Wave (Associazione Command Class Versione 2)**_

Gruppo 1 per “LifeLine”:

Rapporto batteria CC

Ripristina dispositivo localmente CC (COMMAND_CLASSE_DISPOSITIVO_RIPRISTINA_LOCALMENTE)

Modalità termostato CC

Setpoint termostato CC

Sensore multilivello CC

Gruppo 2 per “Stato operativo del termostato”

Stato operativo termostato CC

-   Ripristino delle impostazioni di fabbrica

Quando la valvola del radiatore viene ripristinata alle impostazioni di fabbrica, invierà il ripristino del dispositivo localmente a tutti i nodi del Gruppo 1.

5
