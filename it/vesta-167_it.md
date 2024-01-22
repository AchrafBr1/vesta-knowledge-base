# VESTA167

**Controllo otturatore (SCM-5ZW)**

**introduzione**

SCM-5ZW è un controllo dell'otturatore Z-Wave. L'utente può controllare l'SCM tramite la rete Z-Wave a distanza o manualmente collegando un interruttore all'SCM.

Avvolgilo, abbassalo o fermalo automaticamente o da remoto a metà strada, l'SCM-5ZW è direttamente collegato e controlla le tende motorizzate delle finestre, le tende e le persiane interne ed esterne, lo schermo di proiezione e la porta del garage o il cancello carrabile della tua casa.

Il controllo dell'otturatore è compatibile solo con il gateway/pannello di controllo Z-Wave. Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. Sfruttando la rete mesh Z-Wave, i comandi possono essere indirizzati a destinazione tramite prodotti Z-Wave intermedi di "ascolto".

![](<.gitbook/assets/0 (60).jpeg>)

**Identificazione delle parti**

1.  **Indicatore LED**
    -   Accensione: il LED lampeggia due volte.
    -   Apprendimento riuscito: il LED lampeggia 3 volte.
    -   Ripristino delle impostazioni di fabbrica: il LED lampeggia due volte.
2.  **Pulsante funzione**
    -   Premere il pulsante funzione e il controllo otturatore invierà un report multilivello.
    -   Premere il pulsante funzione 3 volte entro 1,5 secondi per includere o escludere il controllo dell'otturatore nella/dalla rete Z-Wave.
    -   Tenere premuto il pulsante Funzione per 10 secondi per ripristinare.
3.  **Cavo di collegamento ingresso alimentazione N (cavo neutro) (blu)**
4.  **Cavo di collegamento ingresso alimentazione L (cavo sotto tensione) (marrone)**
5.  **Cavo di collegamento dell'interruttore locale S2 (direzione giù) (arancione)**

Se SCM è collegato secondo_**Installazione**_di seguito, la tapparella si abbasserà per 4 minuti dopo l'attivazione dell'interruttore.

L'attivazione di questo interruttore mentre la tapparella si sta arrotolando la fermerà.

**6. Cavo di collegamento dell'interruttore locale S1 (direzione salita) (rosso)**

Se SCM è collegato secondo_**Installazione**_di seguito, la tapparella si arrotolerà per 4 minuti dopo l'attivazione dell'interruttore.

L'attivazione di questo interruttore mentre la tapparella si sta abbassando la fermerà.

**7. Cavo di collegamento uscita motore O1 (direzione su) (giallo)**

Collegare al terminale Up del motore dell'otturatore.

**8. Cavo di collegamento uscita motore O2 (direzione verso il basso) (verde)**

Collegare al terminale Giù del motore dell'otturatore.

**Specifica**

-   Alimentazione: 110 - 230 V CA, 50/60 Hz
-   Corrente di carico supportata: 1/4 HP (potenza del cavallo); 1,8A per motori con fattore di potenza compensato (carichi induttivi)
-   Protocollo di comunicazione: modulo serie Z-Wave Plus 500

![](<.gitbook/assets/1 (53).jpeg>)

**Attenzione**

-   Tutti gli interventi sul dispositivo, comprese l'installazione e la manutenzione, devono essere eseguiti da un elettricista qualificato e autorizzato.
-   Prima dell'installazione o di qualsiasi intervento di manutenzione, assicurarsi che l'alimentazione elettrica sia stata scollegata.
-   Non collegare il dispositivo a carichi che superano la corrente di carico supportata.
-   Collegare il dispositivo solo al motore alimentato in CA.

1

**Caratteristiche**

-   _**Aggiunta di dispositivi (inclusione)**_

Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o altre applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete.

-   -   Collegare l'alimentazione al controllo dell'otturatore (vedere il manuale**Installazione**).
    -   Inserisci il gateway Z-wave o il pannello di controllo**Modalità di inclusione**(fare riferimento al manuale del gateway Z-wave o della centrale).
    -   Entro 1,5 secondi, premere il pulsante funzione 3 volte.
    -   Fare riferimento al manuale operativo del gateway Z-wave o del pannello di controllo per completare il processo di aggiunta.
    -   Se il dispositivo è già stato aggiunto (incluso) in un altro Gateway/Pannello di controllo Z-wave, o se non è possibile aggiungere il dispositivo all'attuale Gateway/Pannello di controllo Z-wave, provare prima a rimuoverlo (vedere_**Rimozione del dispositivo**_).
-   _**Rimozione del dispositivo (esclusione)**_

Il dispositivo deve essere rimosso dalla rete Z-wave esistente prima di essere aggiunto a un'altra.

**Modalità di esclusione**

-   Inserisci il gateway Z-wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale del gateway Z-wave o della centrale).
-   Entro 1,5 secondi, premere il pulsante funzione 3 volte e il dispositivo verrà rimosso dalla rete Z-wave.

**Ripristino delle impostazioni di fabbrica**

_(Utilizzare il ripristino delle impostazioni di fabbrica solo quando il pannello di controllo/gateway di rete è mancante o inutilizzabile)._

Il ripristino delle impostazioni di fabbrica del dispositivo lo ripristinerà alle impostazioni predefinite di fabbrica (ovvero non incluso in alcuna rete Z-wave).

-   -   Tieni premuto il pulsante funzione del dispositivo per 10 secondi per ripristinare le impostazioni di fabbrica.
-   _**Prova di portata**_

Per verificare se il dispositivo è in grado di comunicare con il gateway Z-wave o la centrale:

-   Mettere il gateway/pannello in modalità test di portata (Walk Test).
-   Premere il pulsante funzione sul dispositivo.
-   Il gateway/pannello dovrebbe essere visualizzato se il dispositivo si trova all'interno del raggio d'azione (fare riferimento al manuale operativo del gateway/pannello).

**Installazione**

-   _**Cablaggio con connettore di giunzione**_
    -   SCM-5 viene fornito con cavi terminali e morsetti incorporati (connettori di giunzione Wago 221).
    -   I connettori a 2 fili accettano cavi rigidi e intrecciati da 0,2 a 4 mm² (24–12 AWG).
    -   Collegare SCM-5 all'alimentazione CA, agli interruttori locali e al motore dell'otturatore con i connettori.
    -   Prima del cablaggio, assicurarsi che l'alimentazione sia disattivata. Per collegare i fili:
        1.  Sollevare la leva e inserire il filo.**(Foto 1, 2)**

**Immagine1****Immagine 2**

![](<.gitbook/assets/2 (57).png>)

1.  Spingere nuovamente la leva verso il basso. L'alloggiamento trasparente consente di verificare se il cavo è collegato correttamente. Assicurati che il filo sia tenuto saldamente in posizione e non si stacchi.**(Foto 3, 4)**

2

**Immagine 3****Immagine 4**

![](<.gitbook/assets/3 (57).png>)

-   1.  Allo stesso modo dei passaggi 1 e 2, collega gli altri fili con i connettori.
-   SCM-5 deve essere collegato secondo lo schema seguente:

![](<.gitbook/assets/4 (43).jpeg>)

-   Collegare il terminale N dell'SCM al terminale N dell'alimentatore.
-   Collegare il terminale L dell'SCM al terminale L dell'alimentatore.
-   Collegare il terminale O1 dell'SCM al terminale di apertura del motore dell'otturatore.
-   Collegare il terminale O2 dell'SCM al terminale di chiusura del motore dell'otturatore.
-   **(Interruttore locale opzionale)**Collegare i terminali S2 e S1 dell'SCM al terminale L dell'alimentatore.

**Operazione**

-   _**Controllo dell'otturatore**_
    -   **Controllo manuale**

Se è collegato un interruttore locale opzionale, l'utente può tenere premuto il pulsante sull'interruttore locale su/giù (S1 su; S2 giù) per 1 secondo per controllare la tapparella. Una volta attivata, la tapparella si alzerà/abbasserà. Quando la tapparella sta scorrendo, l'utente può fermarla premendo il pulsante della direzione opposta.

-   -   **Rete Z-Wave**

Dopo che il controllo dell'otturatore è stato incluso con successo in una rete Z-Wave, il controller Z-Wave può controllare l'otturatore con il comando Z-wave Cambia set binario o Cambia set multilivello, utilizzando i parametri seguenti:

-   -   -   Valore: 0x00~0% (0%)~99%, 0% = Chiusura completa, 99% = Apertura completa)
        -   Durata oscuramento: 0x00
    -   All'inizio di ogni movimento su/giù, viene inviato il comando di cambio livello di avvio interruttore multilivello per avviare la transizione al nuovo livello. Mentre l'SCM è in movimento, è possibile inviare il comando di cambio livello di arresto dell'interruttore multilivello per arrestare l'SCM.

3

-   _**Calibrazione**_
    -   L'orario di attivazione predefinito del controllo otturatore è**4**minuti.

Quando si preme il pulsante Su/Giù, si attiverà il motore dell'otturatore per 4 minuti.

Quando viene ricevuto un comando Z-Wave dal controller Z-Wave, determinerà la percentuale di corsa dell'otturatore utilizzando 4 minuti come base per il calcolo.

-   -   Affinché il Controllo Tapparella funzioni correttamente, il suo tempo di attivazione deve essere calibrato in base alla distanza effettiva della corsa della tapparella. Esistono due modi per regolare il tempo di attivazione:
        -   **Calibrazione manuale:**Calibrare l'attivazione secondo la procedura seguente:
            1.  Prima della calibrazione, gli interruttori locali esterni devono essere collegati al controllo della tapparella.
            2.  Tenere premuto il pulsante Funzione per 3 secondi e rilasciarlo per accedere alla modalità Calibrazione. Il motore dell'otturatore si arrotolerà per 4 minuti quando il controllo dell'otturatore entra in modalità di calibrazione.
            3.  Attendere 4 minuti affinché il motore dell'otturatore smetta di scorrere, quindi premere il pulsante "Giù" per abbassare l'otturatore. (Se l'otturatore ha raggiunto la posizione aperta in meno di 4 minuti, è possibile premere il pulsante "Giù" per arrestare il motore dell'otturatore. Quindi premere nuovamente il pulsante "Giù" per abbassare l'otturatore.)
            4.  Non appena la tapparella è completamente chiusa, premere il pulsante “Su”. Il controllo dell'otturatore registrerà il tempo impiegato dall'otturatore per scorrere dall'apertura alla chiusura come nuovo "**ora di chiusura**”.
            5.  Dopo aver premuto il pulsante “Su” nel momento in cui l'otturatore è completamente chiuso, l'otturatore si arrotolerà verso la direzione di apertura.
            6.  Premere il pulsante “Giù” nel momento in cui l'otturatore è completamente aperto. Il controllo dell'otturatore registrerà il tempo impiegato dall'otturatore per scorrere dalla chiusura all'apertura come nuovo "**orario aperto**”.
            7.  Il controllo otturatore invierà un report multilivello (0x63), con il valore corrente, il valore target e/o la durata, al controller ogni volta che il suo livello cambia.
        -   Ad esempio, se la tapparella impiega 30 secondi per spostarsi dalla posizione “Su” a “Giù”, il nuovo tempo di chiusura sarà di 30 secondi. Dopo la calibrazione, ogni volta che si preme il pulsante “Giù”, l'otturatore scorrerà verso il basso per 30 secondi.
        -   Se la tapparella impiega 40 secondi per spostarsi dalla posizione “Giù” a “Su”, il suo nuovo tempo di apertura sarà di 40 secondi. Dopo la calibrazione, ogni volta che si preme il pulsante “Su”, la tapparella si arrotolerà per 40 secondi.
        -   **Comando Z-Wave:**Oltre alla calibrazione manuale, gli utenti possono anche regolare il tempo di attivazione inviando il comando dal controller Z-Wave con il comando Configurazione CC, utilizzando i parametri seguenti:

| **Collocamento**               | **Numero del parametro** | **Misurare** | **Valore**    | **Predefinito**      |
| ------------------------------ | ------------------------ | ------------ | ------------- | -------------------- |
| Aprire l'impostazione dell'ora | 0x01                     | 0x02         | 0x0000~0x00F0 | 0x00F0 (240 secondi) |
|                                |                          |              | (secondo)     |                      |
|                                |                          |              |               |                      |
| Chiudi l'impostazione dell'ora | 0x02                     | 0x02         | 0x0000~0x00F0 | 0x00F0 (240 secondi) |
|                                |                          |              | (secondo)     |                      |
|                                |                          |              |               |                      |
| Posizione attuale              | 0x03                     | 0x02         | 0x0000~0x0063 | 0x0063 (99%)         |
|                                |                          |              | (%)           | Completamente aperto |
|                                |                          |              |               |                      |

-   Numero parametro: 0x01~0x03
    -   Per il parametro 1, gli utenti possono impostare il tempo di apertura (dal basso verso l'alto) su un valore compreso tra 0 e 255 secondi.
    -   Per il parametro 2, gli utenti possono impostare il tempo di chiusura (dall'alto al basso) su un valore compreso tra 0 e 255 secondi.
    -   Per il parametro 3, gli utenti possono impostare la posizione corrente su un valore compreso tra %0 e %99.
-   Dimensioni: 0x02. Questo campo viene utilizzato per specificare la dimensione del valore effettivo.
-   Valore di configurazione: 0x0000~0x00F0 (secondi)
-   Il controllo dell'otturatore inizierà il movimento dopo aver ricevuto il comando Z-wave Cambia set binario o Cambia set multilivello e il movimento verrà eseguito in base all'impostazione della posizione corrente.

Esempio di impostazione di configurazione:

| Numero del parametro | Misurare | Valore |               |
| -------------------- | -------- | ------ | ------------- |
|                      |          |        |               |
| 01                   | 02       | 0064   | (100 secondi) |
|                      |          |        |               |
| 02                   | 02       | 0064   | (100 secondi) |
|                      |          |        |               |
| 03                   | 02       | 0032   | (50%)         |
|                      |          |        |               |

INTERRUTTORE_MULTILIVELLO_IMPOSTA: 0x00 (0%)

SCM scorrerà verso il basso (dall'alto verso il basso) per 50 secondi: (100/100)\*(100-50)

-   L'orario di attivazione verrà reimpostato**4**minuti ogni volta che il controllo dell'otturatore è incluso nella rete Z-Wave o quando viene ripristinato alle impostazioni di fabbrica.

_**\\<NOTE>:**_La posizione corrente predefinita del controllo otturatore è impostata al 99% (completamente aperto). Si consiglia di aprire completamente l'otturatore prima di calibrare con il comando Z-Wave, altrimenti regolare nuovamente anche l'impostazione della posizione corrente con il comando.

4

-   _**Informazioni sull'onda Z**_

**Classe dispositivo generico:**INTERRUTTORE_MULTILIVELLO

**Classe di dispositivo specifica:**CLASSE_C_IL MOTORE_CONTROLLO

**Tipo di ruolo:**SCHIAVO_SEMPRE_SU

**Supporto/controllo della classe di comando**

**Supporto CC obbligatorio:**

Z-Wave Plus Informazioni CC

Servizio Trasporti CC

Sicurezza_2CC

Supervisione CC

Cambia binario (S2)

Commuta CC multilivello (S2)

Informazioni sul gruppo di associazione CC (S2)

Reset del dispositivo localmente CC (S2)

Configurazione CC (S2)

CC specifico del produttore, V2 (S2)

Livello di potenza CC (S2)

Firmware Update Md CC, V4 (S2)

Associazione CC, V2 (S2)

Versione CC, V2 (S2)

Associazione multicanale CC, V3 (S2)

-   _**Gruppi di Z-Wave (Associazione Command Class Versione 2)**_

_**Gruppo 1 per “LifeLine”: (massimo nodo x 1)**_

Cambia CC multilivello, (COMMAND_CLASSE_INTERRUTTORE_MULTILIVELLO)

\#.INTERRUTTORE_MULTILIVELLO_RAPPORTO

\#.INTERRUTTORE_MULTILIVELLO_INIZIO_LIVELLO_MODIFICA

\#.INTERRUTTORE_MULTILIVELLO_FERMARE_LIVELLO_MODIFICA

Dispositivo ripristinato localmente CC, (COMMAND_CLASSE_DISPOSITIVO_RIPRISTINA_LOCALMENTE)

-   Quando SCM inizia a muoversi, invierà\[INTERRUTTORE_MULTILIVELLO_INIZIO_LIVELLO_MODIFICA]
-   Quando SCM smette di muoversi, invierà\[INTERRUTTORE_MULTILIVELLO_FERMARE_LIVELLO_MODIFICA]
-   Ogni volta che SCM cambia posizione, invierà\[INTERRUTTORE_MULTILIVELLO_RAPPORTO]

5
