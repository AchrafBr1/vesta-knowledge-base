# VESTA296

**Controllo otturatore su guida DIN (SCM-6-AS-DIN2-ZW)**

**introduzione**

SCM-6-AS-DIN2-ZW è un controllo per otturatore Z-Wave™. L'utente può controllare l'SCM tramite la rete Z-Wave a distanza o manualmente collegando un interruttore al controllo dell'otturatore.

Avvolgilo, abbassalo o fermalo automaticamente o da remoto a metà strada, l'SCM-6-AS-ZW è direttamente collegato e controlla le tende motorizzate delle finestre, le tende e le persiane interne ed esterne, lo schermo di proiezione e la porta del garage o il cancello carraio della tua casa .

Il controllo dell'otturatore è compatibile solo con il gateway/pannello di controllo Z-Wave. Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. Sfruttando la rete mesh Z-Wave, i comandi possono essere indirizzati a destinazione tramite prodotti Z-Wave intermedi di "ascolto".

Il controllo dell'otturatore Z-Wave consente l'accesso alla classe "S2 Unauthenticated" e supporta l'inclusione Z-Wave SmartStart così come l'inclusione classica.

**Identificazione delle parti**

![](<.gitbook/assets/0 (103).jpeg>)

1.  **Porta per antenna esterna**
2.  **Indicatore LED**
    -   Accensione: il LED lampeggia due volte.
    -   Nella modalità di calibrazione automatica: il LED lampeggia una volta al secondo.
    -   Ripristino delle impostazioni di fabbrica: il LED lampeggia due volte.
    -   Quando si preme l'interruttore locale S1/S2: LED acceso.
3.  **Pulsante funzione**
    -   -   Premere il pulsante funzione e il controllo dell'otturatore invierà un report multilivello.
        -   Premere il pulsante funzione 3 volte entro 1 secondo per includere o escludere il controllo dell'otturatore nella/dalla rete Z-Wave.
        -   Tenere premuto il pulsante funzione per 10 secondi per ripristinare.
        -   Tenere premuto il pulsante funzione per 3 secondi, quindi rilasciarlo per accedere alla modalità di calibrazione automatica.
4.  **Terminale di uscita alimentazione L (conduttore sotto tensione)**
5.  **Terminale di ingresso alimentazione CA L (conduttore sotto tensione)**
6.  **Terminale di ingresso alimentazione CA N (cavo neutro)**
7.  **Terminale interruttore locale S2 (direzione di chiusura)**

Collegare un interruttore esterno al terminale. Attivare questo interruttore per controllare che la tapparella si sposti verso la direzione "Aperta" attivando l'uscita motore O2.

L'attivazione di questo interruttore quando la tapparella si sta muovendo verso la direzione "Apertura" fermerà la tapparella.

**8. Terminale interruttore locale S1 (direzione di apertura)**

Collegare un interruttore esterno al terminale. Attivare questo interruttore per controllare che la tapparella si sposti verso la direzione "Aperta" attivando l'uscita motore O1.

L'attivazione di questo interruttore quando la tapparella si muove verso la direzione "Chiuso" fermerà la tapparella.

**9. Terminale di uscita del motore O2 (direzione di chiusura)**

Collegare al terminale di chiusura del motore dell'otturatore.

**10. Terminale di uscita motore O1 (direzione di apertura)**

Collegare al terminale di apertura del motore dell'otturatore.

**11. Terminale di uscita alimentazione N (cavo neutro)**

**Specifica**

-   Alimentazione: 100 - 240 V CA, 50/60 Hz
-   Corrente di carico supportata: 3 A per motori con fattore di potenza compensato (carichi induttivi)
-   Protocollo di comunicazione: modulo serie Z-Wave Plus 700

1

![](<.gitbook/assets/1 (85).jpeg>)**Attenzione**

-   Tutti gli interventi sul dispositivo, comprese l'installazione e la manutenzione, devono essere eseguiti da un elettricista qualificato e autorizzato.
-   Prima dell'installazione o di qualsiasi intervento di manutenzione, assicurarsi che l'alimentazione elettrica sia stata scollegata.
-   Non collegare il dispositivo a carichi che superano la corrente di carico supportata.
-   Collegare il dispositivo solo al motore alimentato in CA.

**Cablaggio e installazione**

**Prima dell'installazione, assicurarsi che l'alimentazione sia stata scollegata.**

-   SCM-6-AS-DIN2-ZW deve essere collegato secondo i 2 schemi seguenti:

**Cablaggio 1****Cablaggio 2**

![](<.gitbook/assets/2 (79).png>)

-   -   Collegare i terminali L e N dell'ingresso alimentazione CA dell'SCM rispettivamente ai terminali L e N dell'alimentatore.
    -   Collegare il terminale di uscita alimentazione N dell'SCM al terminale N del motore dell'otturatore.
    -   Collegare il terminale O1 dell'SCM al terminale di apertura del motore dell'otturatore.
    -   Collegare il terminale O2 dell'SCM al terminale di chiusura del motore dell'otturatore.
    -   **(Interruttori locali opzionali)**Collegare i terminali S2 e S1 dell'SCM a 2 interruttori esterni e collegare 2 interruttori esterni al terminale L dell'alimentatore.
-   Inserire ciascun filo nel terminale a cui deve essere collegato secondo 2 Schemi elettrici

mostrato sopra e serrare la vite di ciascun terminale.

-   Collegare l'antenna esterna alla porta dell'antenna esterna.
-   Montare il dispositivo all'interno del quadro elettrico utilizzando una guida DIN.

**Caratteristiche**

-   _**Aggiunta di dispositivi (inclusione)**_

Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o altre applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete. Il dispositivo supporta sia il processo di inclusione classico che il processo di inclusione SmartStart.

**Inclusione classica**

-   Collegare l'alimentazione al controllo dell'otturatore (vedere il manuale**Cablaggio e installazione**).
-   Inserisci il gateway Z-wave o il pannello di controllo**Modalità di inclusione**(fare riferimento al manuale del gateway Z-wave o della centrale).
-   Entro 1 secondo, premere il pulsante funzione 3 volte.
-   Fare riferimento al manuale operativo del gateway Z-wave o del pannello di controllo per completare il processo di aggiunta.
-   Se il dispositivo è già stato aggiunto (incluso) in un altro Gateway/Pannello di controllo Z-wave, o se non è possibile aggiungere il dispositivo all'attuale Gateway/Pannello di controllo Z-wave, provare prima a rimuoverlo (vedere_**Rimozione del dispositivo**_).

2

**Inclusione SmartStart**

Z-Wave SmartStart utilizza il DSK del dispositivo per migliorare e semplificare il processo di inclusione. DSK è la chiave specifica del dispositivo utilizzata per l'autenticazione. Le informazioni DSK vengono memorizzate nel formato del codice QR stampato su un adesivo e attaccato al dispositivo.

![](<.gitbook/assets/3 (69).jpeg>)

-   -   -   Scansiona l'adesivo del codice QR sul lato destro del controllo dell'otturatore per ottenere DSK e trasferirlo al gateway Z-Wave.
        -   Collega l'alimentazione al Controllo Tapparelle, una richiesta di inclusione SmartStart verrà inviata automaticamente al gateway.
        -   Il gateway includerà automaticamente il dispositivo al momento del riconoscimento del dispositivo abbinando la richiesta di inclusione al DSK ottenuto.
    -   _NOTA>_
        -   -   Il DSK del dispositivo viene utilizzato solo durante l'inclusione.
            -   Il DSK può essere letto senza che il Controllo tapparella sia acceso, quindi è possibile predisporre il gateway per includere il dispositivo prima di accendere il Controllo tapparella.
            -   Prima di rimuovere o ripristinare le impostazioni di fabbrica del controllo otturatore,

assicurati che le informazioni DSK del dispositivo siano state rimosse o non esistano nel gateway. Se rimuovi o ripristini le impostazioni di fabbrica del dispositivo, ma il relativo DSK esiste ancora nel gateway, il gateway includerà nuovamente automaticamente il dispositivo.

-   _**Rimozione del dispositivo (esclusione)**_

Il dispositivo deve essere rimosso dalla rete Z-wave esistente prima di essere aggiunto a un'altra.**Modalità di esclusione**

-   Inserisci il gateway Z-wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale del gateway Z-wave o della centrale).
-   Entro 1 secondo, premere il pulsante funzione 3 volte e il dispositivo verrà rimosso dalla rete Z-wave.

**Ripristino delle impostazioni di fabbrica**

_(Utilizzare il ripristino delle impostazioni di fabbrica solo quando il pannello di controllo/gateway di rete è mancante o inutilizzabile)._

Il ripristino delle impostazioni di fabbrica del dispositivo lo ripristinerà alle impostazioni predefinite di fabbrica (ovvero non incluso in alcuna rete Z-wave).

-   -   Tieni premuto il pulsante funzione del dispositivo per 10 secondi per ripristinare le impostazioni di fabbrica.
-   _**Prova di portata**_

Per verificare se il dispositivo è in grado di comunicare con il gateway Z-wave o la centrale:

-   Mettere il gateway/pannello in modalità test di portata (Walk Test).
-   Premere il pulsante funzione sul dispositivo.
-   Il gateway/pannello dovrebbe essere visualizzato se il dispositivo si trova all'interno del raggio d'azione (fare riferimento al manuale operativo del gateway/pannello).

**Operazione**

-   _**Controllo dell'otturatore**_
    -   **Controllo manuale**

Se è collegato un interruttore locale opzionale, l'utente può tenere premuto il pulsante sull'interruttore locale su/giù (S1 su; S2 giù) per 1 secondo per controllare la tapparella. Una volta attivata, la tapparella si alzerà/abbasserà.

Quando la tapparella sta scorrendo, l'utente può fermarla premendo il pulsante della direzione opposta.

-   -   **Rete Z-Wave**

Dopo che il controllo dell'otturatore è stato incluso con successo in una rete Z-Wave, il controller Z-Wave può controllare l'otturatore con il comando Z-wave Cambia set binario o Cambia set multilivello, utilizzando i parametri seguenti:

-   -   -   Valore: 0x00~0% (0%)~99%, 0% = Chiusura completa, 99% = Apertura completa)
        -   Durata oscuramento: 0x00
-   _**Calibrazione**_
    -   L'orario di attivazione predefinito del controllo otturatore è**4**minuti.

Quando si preme il pulsante Su/Giù, si attiverà il motore dell'otturatore per 4 minuti.

Quando viene ricevuto un comando Z-Wave dal controller Z-Wave, determinerà la percentuale di corsa dell'otturatore utilizzando 4 minuti come base per il calcolo.

-   -   Affinché il Controllo Tapparella funzioni correttamente, il suo tempo di attivazione deve essere calibrato in base alla distanza effettiva della corsa della tapparella. Esistono due modi per regolare il tempo di attivazione:

3

-   **Calibrazione automatica:**Calibrare l'attivazione secondo la procedura seguente:
    1.  Tenere premuto il pulsante funzione per 3 secondi, quindi rilasciarlo per accedere alla modalità di calibrazione automatica. Il LED inizierà a lampeggiare una volta al secondo; il motore dell'otturatore si arrotolerà verso l'alto.
    2.  Quando il motore dell'otturatore si sposta verso l'alto e si ferma, si abbasserà automaticamente e registrerà il tempo necessario per scorrere dalla posizione aperta (in alto) a quella chiusa (in basso) come nuovo

“**ora di chiusura**”.

-   1.  Quando il motore dell'otturatore scende verso il basso, si arrotolerà e registrerà il tempo necessario per passare dalla posizione chiusa (in basso) a quella aperta (in alto) come nuovo "**orario aperto**”.
    2.  Una volta completate tutte le azioni, il controllo dell'otturatore invierà un MULTILIVELLO_REPORT: 0x63 al controller che indica che la posizione corrente è in alto. Il LED si spegnerà quando il motore dell'otturatore esce dalla modalità di calibrazione automatica.
    3.  Dopo la calibrazione, il motore dell'otturatore funzionerà in base ai tempi di avvolgimento su e giù appena registrati.
-   Ad esempio, se la tapparella impiega 30 secondi per spostarsi dalla posizione “Su” a “Giù”, il nuovo tempo di chiusura sarà di 30 secondi. Dopo la calibrazione, ogni volta che si preme il pulsante “Giù”, l'otturatore scorrerà verso il basso per 30 secondi.
-   Se la tapparella impiega 40 secondi per passare dalla posizione “Giù” a “Su”, il suo nuovo tempo di apertura sarà
    1.  secondi. Dopo la calibrazione, ogni volta che si preme il pulsante “Su”, la tapparella si arrotolerà per 40 secondi.
-   **Comando Z-Wave:**Oltre alla calibrazione automatica, gli utenti possono anche regolare il tempo di attivazione inviando il comando dal controller Z-Wave con il comando Configurazione CC, utilizzando i parametri seguenti:

| **Collocamento**               | **Parametro** |   | **Misurare** | **Valore**                              | **Predefinito**      |               |   |
| ------------------------------ | ------------- | - | ------------ | --------------------------------------- | -------------------- | ------------- | - |
|                                | **Numero**    |   |              |                                         |                      |               |   |
|                                |               |   |              |                                         |                      |               |   |
| Aprire l'impostazione dell'ora | 0x01          |   | 0x02         | 0x0000~0x0960 (0,1 secondi)             | 0x0960               | (240 secondi) |   |
|                                |               |   |              |                                         |                      |               |   |
| Chiudi l'impostazione dell'ora | 0x02          |   | 0x02         | 0x0000~0x0960 (0,1 secondi)             | 0x0960               | (240 secondi) |   |
|                                |               |   |              |                                         |                      |               |   |
| Posizione attuale              | 0x03          |   | 0x02         | 0x0000~0x0063 (%)                       | 0x0063               | (99%)         |   |
|                                |               |   |              |                                         | Completamente aperto |               |   |
|                                |               |   |              |                                         |                      |               |   |
| Calibrazione                   | 0x04          |   | 0x01         | 0 – il dispositivo non è calibrato      | 0                    |               |   |
|                                |               |   |              | (sola lettura)                          |                      |               |   |
|                                |               |   |              | 1 - il dispositivo è calibrato          |                      |               |   |
|                                |               |   |              | (sola lettura)                          |                      |               |   |
|                                |               |   |              | 2- forzare l'esecuzione del dispositivo |                      |               |   |
|                                |               |   |              | calibrazione                            |                      |               |   |
|                                |               |   |              |                                         |                      |               |   |

-   Numero parametro: 0x01~0x04
    -   Per il parametro 1, gli utenti possono impostare il tempo di apertura (dal basso verso l'alto) su un valore compreso tra 0 e 240 secondi.
    -   Per il parametro 2, gli utenti possono impostare il tempo di chiusura (dall'alto al basso) su un valore compreso tra 0 e 240 secondi.
    -   Per il parametro 3, gli utenti possono impostare la posizione corrente su un valore compreso tra %0 e %99.
    -   Per il parametro 4, gli utenti possono impostare un valore per forzare il dispositivo a eseguire la calibrazione o controllare lo stato della calibrazione in base al valore. Impostare il valore su 2 per fare in modo che il dispositivo esegua la calibrazione. Se il valore è 0, significa che il dispositivo non è calibrato. Se il valore è 1, indica che il dispositivo è calibrato.
-   Dimensioni: 0x02. Viene utilizzato per specificare la dimensione del valore effettivo.
-   Valore di configurazione: 0x0000~0x0960 (0,1 secondo)
-   Il controllo dell'otturatore inizierà il movimento dopo aver ricevuto il comando Z-wave Cambia set binario o Cambia set multilivello e il movimento verrà eseguito in base all'impostazione della posizione corrente.

Esempio di impostazione di configurazione:

|                                              | **Numero del parametro** | **Misurare** | **Valore**                  |
| -------------------------------------------- | ------------------------ | ------------ | --------------------------- |
|                                              |                          |              |                             |
|                                              | 01                       | 02           | 0x03E8 (100 secondi)        |
|                                              |                          |              |                             |
|                                              | 02                       | 02           | 0x03E8 (100 secondi)        |
|                                              | 03                       | 02           | 0032 (50%)                  |
|                                              |                          |              |                             |
|                                              | 04                       | 01           | 2- forzare il dispositivo a |
|                                              |                          |              | eseguire la calibrazione    |
| INTERRUTTORE_MULTILIVELLO_IMPOSTA: 0x00 (0%) |                          |              |                             |

SCM scorrerà verso il basso (dall'alto verso il basso) per 50 secondi: (1000/1000)\*(100-50)

-   L'orario di attivazione verrà reimpostato**4**minuti ogni volta che il controllo dell'otturatore è incluso nella rete Z-Wave o quando viene ripristinato alle impostazioni di fabbrica.

_**\\<NOTE>:**_La posizione corrente predefinita del controllo otturatore è impostata al 99% (completamente aperto). Si consiglia di aprire completamente l'otturatore prima di calibrare con il comando Z-Wave, altrimenti regolare nuovamente anche l'impostazione della posizione corrente con il comando.

4

**Informazioni sull'onda Z**

**Tipo di dispositivo:**GENERICO_TIPO_INTERRUTTORE_MULTILIVELLO

**Tipo specifico:**SPECIFICA_TIPO_CLASSE_C_IL MOTORE_CONTROLLO

**Tipo di ruolo:**Sempre attivo come schiavo (AOS)

**Identificativo del produttore:**0x018E

**ID tipo prodotto:**0x0004

**Codice prodotto:**0x0105

**Classe di comando supportata:**

| **Classe di comando**                     | **Versione** | **Classe di sicurezza richiesta**      |
| ----------------------------------------- | ------------ | -------------------------------------- |
|                                           |              |                                        |
| Associazione                              | 2            | Classe di sicurezza più alta garantita |
| Informazioni sul gruppo dell'associazione | 3            | Classe di sicurezza più alta garantita |
| Di base                                   | 2            | Classe di sicurezza più alta garantita |
| Reimpostazione del dispositivo localmente | 1            | Classe di sicurezza più alta garantita |
| Metadati di aggiornamento del firmware    | 5            | Classe di sicurezza più alta garantita |
| Specifico del produttore                  | 2            | Classe di sicurezza più alta garantita |
| Multicanale                               | 4            | Classe di sicurezza più alta garantita |
| Associazione multicanale                  | 3            | Classe di sicurezza più alta garantita |
| Livello di potenza                        | 1            | Classe di sicurezza più alta garantita |
| Cambia binario                            | 2            | Classe di sicurezza più alta garantita |
| Cambia multilivello                       | 4            | Classe di sicurezza più alta garantita |
| Configurazione                            | 1            | Classe di sicurezza più alta garantita |
| Versione                                  | 3            | Classe di sicurezza più alta garantita |
| Servizio di trasporto                     | 2            | Nessuno                                |
| Informazioni su Z-Wave Plus               | 2            | Nessuno                                |
| Sicurezza 2                               | 1            | Nessuno                                |
| Sicurezza                                 | 1            | Nessuno                                |
| Supervisione                              | 1            | Nessuno                                |

**Gruppi associativi:**

**ID**

1

| **Nome**           | **Conteggio dei nodi** | **Descrizione**                                                 |
| ------------------ | ---------------------- | --------------------------------------------------------------- |
| Ancora di salvezza | 40                     | Supporta le seguenti classi di comandi:                         |
|                    |                        | ● Ripristino del dispositivo localmente: attivato al ripristino |
|                    |                        | ● Cambia rapporto multilivello: rapporto del                    |
|                    |                        | cambio di posizione                                             |
|                    |                        |                                                                 |

5
