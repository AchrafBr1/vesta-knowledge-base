# VESTA 312

**Serie Mini-FIRE-LIVE**

**introduzione**

La serie Mini-PIR-ZW è un sensore di movimento a infrarossi passivi Z-Wave in grado di inviare segnali wireless al coordinatore nella rete Z-Wave al rilevamento del movimento. Il PIR è dotato di un sensore di temperatura/luce ambientale integrato opzionale che fornisce una lettura di temperatura/lux che verrà trasmessa tramite la rete Z-Wave a intervalli regolari (solo modello Mini-PIR-LT-ZW).

Il PIR può essere configurato utilizzando il coordinatore Z-Wave per funzionare come un sensore di sicurezza che attiva l'allarme quando attivato, o un sensore di occupazione/vacanza che controlla l'automazione domestica o le funzioni di illuminazione tramite il coordinatore Z-Wave.

Il PIR è un dispositivo abilitato Z-Wave ed è completamente compatibile con qualsiasi rete abilitata Z-Wave.

Z-Wave is a wireless communication protocol that uses a low-power RF radio. By taking advantage of the Z-Wave mesh network, commands can be transmitted to their destination via intermediary “listening” Z-Wave products.

La serie Mini-PIR-ZW comprende i seguenti modelli:

| **Nome del modello** | **Rilevamento del movimento** | **Luce e temperatura** |
| -------------------- | ----------------------------- | ---------------------- |
|                      |                               | **rilevamento**        |
|                      |                               |                        |
| Mini-PIR-ZW          | IN                            |                        |
|                      |                               |                        |
| Mini-FIRE-LT-LIVE    | IN                            | IN                     |
|                      |                               |                        |

**Identificazione delle parti**

Il PIR è composto da un corpo principale e una base. Il corpo principale deve essere separato dalla base per l'installazione della batteria e la configurazione della rete Z-Wave.

Per separare il corpo principale e la base, tenere il PIR con entrambe le mani e ruotare la base a destra e il corpo principale a sinistra per separarli.

![](<.gitbook/assets/0 (58).png>)

**1. Obiettivo IR con indicatore LED**

L'indicatore LED si trova al centro della lente IR.

L'indicatore LED si accende nelle seguenti condizioni:

-   -   Lampeggia una volta:

Il PIR sta trasmettendo il codice di apprendimento/ripristino delle impostazioni di fabbrica.

-   -   Lampeggia due volte velocemente:

Il PIR ha aderito con successo alla rete Z-Wave.

-   -   Lampeggia in modalità operativa normale:

Il PIR ha rilevato un movimento ed è attualmente in condizione di Batteria scarica o Tamper aperto.

1.  **Copertina posteriore**

Rimuovere il coperchio posteriore per accedere al vano batteria e al pulsante funzione.

1.  **Pulsante funzione**
    -   Premere una volta il pulsante per inviare un segnale di supervisione ed accedere alla modalità test.
    -   Premere per 3 volte entro 1,5 secondi per trasmettere un codice di apprendimento.
    -   Tieni premuto il pulsante per 10 secondi, quindi rilascialo per ripristinare le impostazioni di fabbrica.
2.  **Compartimento della batteria**

Il PIR è alimentato da una batteria al litio CR123A 3V.

1.  **Vite di regolazione dell'angolo di base**
2.  **Fori per il montaggio a parete**

1

**Caratteristiche**

-   _**Sveglia**_

Il PIR ha un "tempo di sospensione" di circa 1 minuto per risparmiare energia. Dopo aver trasmesso un movimento rilevato, il PIR non ritrasmetterà per 1 minuto. Qualsiasi ulteriore movimento rilevato durante questo periodo di sonno prolungherà la durata del sonno di un altro minuto. In questo modo il movimento continuo davanti a un PIR non scaricherà eccessivamente la batteria.

-   _**Segnalazione di arresto del movimento**_

Dopo ogni rilevamento di movimento, se trascorrono 30 secondi senza rilevamento, il PIR trasmetterà un segnale di "arresto del movimento" al coordinatore della rete Z-Wave.

-   _**Rilevamento batteria e batteria scarica**_
    -   Il PIR utilizza una batteria al litio CR123A da 3 V come fonte di alimentazione. Il corpo principale del PIR deve essere rimosso dalla base per accedere al vano batteria. Il vano batteria è dotato di una striscia che deve essere premuta sotto la batteria quando questa viene inserita. Quando rimuovi la pastella, solleva semplicemente la striscia.
    -   Il PIR è dotato della funzione di rilevamento della batteria scarica. Quando la tensione della batteria è bassa, il PIR trasmetterà il segnale di batteria scarica al coordinatore nella rete Z-Wave. Se viene rilevato un movimento in condizioni di batteria scarica, l'indicatore LED lampeggerà per indicarlo.
    -   Il PIR riporterà la percentuale della batteria al Gateway/Pannello di controllo rispettivamente al 100%, 75%, 50% e 25%. Se la tensione della batteria è bassa (25%), un segnale di batteria scarica verrà inviato alla centrale per avvisare l'utente.
    -   Se la batteria non viene sostituita dopo la condizione di batteria scarica ed è esaurita, il LED lampeggerà ogni 2 secondi e il PIR interromperà tutte le operazioni.
    -   Quando si cambia la batteria, dopo aver rimosso la vecchia batteria, premere due volte il pulsante funzione per scaricarla completamente prima di inserire la nuova batteria
-   _**Protezione antisabotaggio**_

Il PIR è protetto da un interruttore antimanomissione situato all'interno del corpo principale del PIR. L'interruttore antimanomissione viene attivato ogni volta che il PIR viene rimosso dalla base e il PIR invierà un segnale di apertura antimanomissione per ricordare all'utente la condizione. Se viene rilevato un movimento quando l'interruttore antimanomissione è aperto, il PIR lampeggerà per indicarlo.

-   _**Supervisione**_

Questa funzione utilizza la classe di comando Wake Up Z-Wave. La Classe Comando Risveglio consente al PIR alimentato a batteria di notificare alla Centrale/Gateway che è sveglio e pronto a ricevere eventuali comandi in coda. Il periodo di tempo di sveglia è programmato automaticamente in base alle impostazioni del pannello di controllo quando è incluso il PIR. L'impostazione consigliata dell'orario di sveglia è superiore a 60 minuti.

-   _**Modalità di prova**_
    -   La modalità test consente di verificare il raggio di rilevamento del PIR.
    -   Premere una volta il pulsante Funzione per accedere alla modalità Test per 3 minuti.
    -   Durante la modalità test, è possibile attivare il sensore PIR per verificarne la copertura di rilevamento. Se il PIR viene attivato, il LED si accenderà per indicare.
-   _**Rilevamento della temperatura (solo modello Mini-PIR-LT-ZW)**_
    -   Il PIR con sensore di temperatura integrato trasmetterà regolarmente i segnali di temperatura in base all'impostazione. L'intervallo predefinito in fabbrica è 30 minuti.
    -   Quando la temperatura cambia di +/- 2°C, anche il PIR trasmetterà un segnale.
    -   È anche possibile premere una volta il pulsante funzione per trasmettere manualmente un segnale di temperatura.
    -   L'intervallo di rilevamento della temperatura è di circa -10°C~50°C (14°F~122°F).
-   _**Monitoraggio della luce (solo modello Mini-PIR-LT-ZW)**_
    -   Il PIR con sensore di luce ambientale integrato misura l'illuminamento e trasmette regolarmente i dati misurati al coordinatore della rete Z-Wave. L'intervallo predefinito in fabbrica è 30 minuti.
    -   Quando l'illuminamento attuale cambia del +/- 10%, anche il PIR trasmetterà un segnale.
    -   È inoltre possibile premere una volta il pulsante funzione per trasmettere manualmente la lettura lux corrente.
-   _**Aggiunta di dispositivi (inclusione)**_

Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o altre applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete.

-   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di inclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
-   Entro 1,5 secondi, premere il pulsante funzione 3 volte.
-   Fare riferimento al manuale operativo del gateway Z-Wave o del pannello di controllo per completare il processo di aggiunta.
-   Se il PIR è già stato aggiunto (incluso) in un altro gateway/pannello di controllo Z-Wave, o se non è possibile aggiungere il dispositivo all'attuale gateway/pannello di controllo Z-Wave, provare prima a rimuoverlo (vedere_**Rimozione del dispositivo**_).

2

-   _**Rimozione del dispositivo (esclusione)**_

Il PIR deve essere rimosso dalla rete Z-Wave esistente prima di essere aggiunto a un'altra.

**Exclusion Mode**

-   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
-   Entro 1,5 secondi, premere il pulsante funzione 3 volte e il PIR verrà rimosso dalla rete Z-Wave.

**Ripristino delle impostazioni di fabbrica**

_(Utilizzare il ripristino delle impostazioni di fabbrica solo quando il pannello di controllo/gateway di rete è mancante o inutilizzabile)._

-   Rimuovere prima la batteria del PIR.
-   Tieni premuto il pulsante funzione. Tenendo premuto il pulsante funzione, accendere il PIR reinserindo la batteria e attendere 10 secondi per ripristinare le impostazioni di fabbrica.

_\\<NOTE>_

-   -   Il ripristino delle impostazioni di fabbrica del PIR lo ripristinerà alle impostazioni predefinite di fabbrica (esclusa dalla rete Z-Wave). Il gateway o il pannello di controllo Z-Wave manterrà comunque le impostazioni Z-Wave. Fare riferimento al manuale del gateway o della centrale di controllo su come rimuovere le impostazioni PIR Z-Wave.
-   _**Prova di portata**_

Per verificare se il PIR è in grado di comunicare con il gateway Z-Wave o la centrale:

-   -   Mettere il gateway/pannello in modalità test di portata (Walk Test).
    -   Premere il pulsante funzione sul PIR.
    -   Il gateway/pannello dovrebbe essere visualizzato se il dispositivo si trova all'interno del raggio d'azione (fare riferimento al manuale operativo del gateway/pannello).
-   _**Modalità di sospensione Z-Wave**_
    -   Il PIR entrerà in modalità Z-Wave Sleep (per risparmiare energia) dopo essersi svegliato per un breve periodo di tempo (~10 secondi). Durante la modalità di sospensione Z-Wave, i gateway Z-Wave o i pannelli di controllo non sono in grado di inviare comandi al PIR.
    -   Per programmare il PIR utilizzando il gateway/pannello di controllo Z-Wave, inviare i comandi al PIR entro il periodo di riattivazione.

**Installazione**

-   _**Altezza di montaggio e copertura del rilevamento PIR**_
    -   Esistono due modi per distribuire il Mini-PIR: montaggio a parete e distribuzione in superficie.
    -   Il PIR ha una copertura di rilevamento di un cono di 120∘ nella parte anteriore. Se utilizzato su una superficie piana a circa 1,2 metri dal suolo o montato su una parete a circa 2 metri di altezza, il PIR ha una portata massima di 10 metri.
    -   La direzione del PIR può essere modificata allentando la vite di regolazione dell'angolo sulla base per inclinare il PIR su e giù.

![](<.gitbook/assets/1 (86).jpeg>)

3

-   _**Assemblea**_
    -   Il PIR è composto dal corpo principale e dalla base. Vedere le istruzioni di seguito per fissare il corpo principale sulla base o staccare il corpo principale dopo l'installazione.
        1.  Collega il corpo principale alla base. (Figura 1)
        2.  Inclinare il PIR all'indietro finché la sua parte posteriore non tocca la base. (Figura 2)

**Figura 1****figura 2**

![](<.gitbook/assets/2 (81).png>)

1.  Tieni il corpo principale del PIR con la mano sinistra e la base con la mano destra. NON toccare l'obiettivo IR altrimenti l'obiettivo potrebbe danneggiarsi durante il processo. (Figura 3, 4)
2.  A**serratura**il corpo principale sulla base, girare il corpo principale con la mano sinistra lontano da sé e girare contemporaneamente la base con la mano destra verso di sé nella direzione opposta finché non si sente un clic. (Figura 3)
3.  A**pubblicazione**il corpo principale dalla base, girare il corpo principale con la mano sinistra verso di sé e premere contemporaneamente verso il basso con il pollice della mano destra lontano da sé nella direzione opposta finché non si sente un clic. (Figura 4)

**Figura 3****Figura 4**

![](<.gitbook/assets/3 (79).png>)

-   _**Installazione**_
    1.  Utilizzare i 2 fori di montaggio sulla base PIR come modello e praticare dei fori sulla superficie.
    2.  Inserire i tasselli se si fissa su intonaco o mattoni.
    3.  Avvitare la base nei tasselli. (Figura 5)
    4.  Agganciare il corpo principale del PIR alla base e girarlo per bloccarlo. (Figura 6, 7)
    5.  Allentare le viti di regolazione dell'angolo quindi inclinare il PIR finché non si è soddisfatti dell'angolo di rilevamento. Stringere le viti per fissare il PIR all'angolazione impostata. (Figura 8)

**Figura 5****Figura 6****Figura 7****Figura 8**

![](<.gitbook/assets/4 (60).jpeg>)

-   _**Linee guida per l'installazione**_
    -   **Si consiglia di installare il PIR nelle seguenti posizioni.**
        -   In una posizione tale che un intruso normalmente si sposterebbe attraverso il campo visivo del PIR da un lato all'altro.
        -   Dove il suo campo visivo non sarà ostruito, ad es. da tende, ornamenti, ecc.
    -   **Limitazioni**
        -   Non installare il PIR in un luogo esposto alla luce solare diretta o vicino ad apparecchi di riscaldamento/raffreddamento e a una presa d'aria
        -   Non puntare il PIR verso fonti di calore come riscaldatori, radiatori e finestre.
        -   Non puntare il PIR verso la finestra.
        -   Evitare ostacoli di grandi dimensioni nell'area di rilevamento ed evitare oggetti in movimento come le tende.

4

-   _**Informazioni sull'onda Z**_

**Tipo di dispositivo:**Sensore di notifica allarme fumo

**Tipo di ruolo:**Segnalazione dello schiavo addormentato (RSS)

**Gruppo di associazione massimo:**6

**Supporto/controllo della classe di comando**

**Supporto CC obbligatorio:**

Z-Wave Plus Informazioni CC

Versione CC, v2 o successiva

CC specifico del produttore

Dispositivo reimpostato localmente CC

Livello di potenza CC

Batteria CC

SensoreMultilivello CC, V5

Notifica V4 CC

Associazione CC, v2 o successiva

Associazione Gruppo Informazioni CC

Configurazione CC

Aggiornamento firmware Md CC

-   _**Gruppi di Z-Wave (Associazione Command Class Versione 2)**_

Gruppo 1 per “LifeLine”:

Sensore multilivello CC,V5

Notifica CC,V4 (COMANDO_CLASSE_Notifica)

Batteria CC (COMANDO_CLASSE_DI BASE)

Dispositivo reimpostato localmente CC

Gruppo 2 per “Set PIR Base”:

CC di base (COMANDO_CLASSE_DI BASE)

Quando PIR attivo, il Gruppo 2 invierà l'impostazione di base (0xFF), il ripristino invierà (0x00)

Gruppo 3 per “Rappresentante notifica PIR”:

Notifica CC, V4 (COMMAND_CLASSE_NOTIFICA)

Invia solo PIR Attivo (07,08) e Ripristino (07,00,01,08)

Gruppo 4 per “Report Temp/Luce” (solo modello Mini-PIR-LT-ZW):

Sensore multilivello CC, V5 (COMMAND_CLASSE_SENSORE_MULTILIVELLO)

Invia solo temperatura/luce

Gruppo 5 per “Rappresentante notifiche HD”:

Notifica CC,V4 (COMANDO_CLASSE_NOTIFICA)

Quando HD attivo, il Gruppo 5 invierà (04,02), Restore invierà (04,06)

Group 6 for “Tamper rep”:

Notifica CC,V4 (COMANDO_CLASSE_NOTIFICA)

Quando il Tamper è aperto, il Gruppo 6 invierà (07,03), il Ripristino invierà (07,00,01,03)

5
