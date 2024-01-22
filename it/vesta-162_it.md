# VESTA162

**PRM2-ZW-P5**

**Interruttore relè di potenza Z-Wave con misuratore**

**introduzione**

L'interruttore relè di potenza è in grado di ricevere segnali wireless dal coordinatore nella rete Z-Wave per attivare/disattivare gli apparecchi ad esso collegati.

L'interruttore relè di potenza è un dispositivo abilitato Z-Wave ed è completamente compatibile con qualsiasi rete abilitata Z-Wave.

Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. Sfruttando la rete mesh Z-Wave, i comandi possono essere trasmessi a destinazione tramite prodotti Z-Wave intermedi di "ascolto".

PRM2-ZW-P5 ha la caratteristica extra di tenere traccia del consumo energetico con il misuratore di potenza integrato e di trasmettere regolarmente i dati al coordinatore.

PRM2-ZW-P5 funge anche da router nella rete Z-Wave. Dopo essere stato incluso nella rete Z-Wave, consente ad altri dispositivi Z-Wave di unirsi alla rete tramite l'interruttore di accensione.

**Identificazione delle parti**

![](<.gitbook/assets/0 (57).jpeg>)

**1. Indicatore LED**

L'indicatore LED viene utilizzato per indicare lo stato dell'interruttore del relè di alimentazione:

-   -   SU:

L'interruttore del relè di potenza è acceso.

-   -   Spento:

L'interruttore del relè di potenza è spento.

1.  **Pulsante funzione**

Il pulsante funzione viene utilizzato per controllare l'interruttore del relè di potenza:

**Utilizzo dei pulsanti funzione:**

-   -   Premere il pulsante per attivare/disattivare l'interruttore del relè di potenza
    -   Premere il pulsante 3 volte entro 1,5 secondi per aggiungere/rimuovere dalla rete Z-Wave.
    -   Tieni premuto il pulsante per 10 secondi per ripristinare le impostazioni di fabbrica.

1.  **Terminale interruttore esterno 1**
2.  **Terminale interruttore esterno 2**
3.  **Ingresso alimentazione linea CA**
4.  **Ingresso alimentazione neurale CA**
5.  **Uscita di carico di alimentazione neutra CA**
6.  **Uscita carico alimentazione linea CA**

**Operazione**

-   _**Schema di collegamento dei cavi**_
    -   Fare riferimento allo schema per collegare i dispositivi all'interruttore del relè di potenza.
-   _**Installazione**_

![](<.gitbook/assets/1 (51).jpeg>)

**Passo 1:**Interrompere l'alimentazione elettrica al cavo di alimentazione per motivi di sicurezza e per garantire che il cavo non venga cortocircuitato durante il processo di installazione.

**Passo 2:**Collegare il cavo di alimentazione in ingresso CA al connettore di ingresso e il cavo di alimentazione in uscita al connettore di uscita.

**Passaggio 3:**Per il collegamento dell'interruttore esterno, collegare l'interruttore al controllo dell'interruttore esterno.

**Passaggio 4:**Dopo aver completato il cablaggio ripristinare l'alimentazione elettrica al cavo di alimentazione.

1

-   _**Aggiunta di dispositivi (inclusione)**_

Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o altre applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete.

-   -   Collegare l'interruttore del relè di potenza al cavo di alimentazione.
    -   Inserisci il gateway Z-Wave o il pannello di controllo**Inclusione**O**Apprendimento**modalità (fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
    -   Entro 1,5 secondi, premere il pulsante funzione 3 volte.
    -   Fare riferimento al manuale operativo del gateway Z-Wave o del pannello di controllo per completare il processo di apprendimento.
    -   Se il sensore è già stato**incluso**(appreso) in un altro gateway/pannello di controllo Z-Wave, o se non è possibile apprendere il sensore nell'attuale gateway/pannello di controllo Z-Wave, escluderlo prima (vedere_**Esclusione**_) prima di tentare di farlo**includere** it into the current Z-Wave Gateway/Control Panel.
-   _**Rimozione del dispositivo (esclusione)**_

L'interruttore del relè di potenza deve essere rimosso dalla rete Z-Wave esistente prima di essere incluso in un'altra. Sono disponibili due metodi per escludere un dispositivo.

**Modalità di esclusione**

-   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
-   Entro 1,5 secondi, premere il pulsante funzione 3 volte e l'interruttore del relè di potenza verrà rimosso dalla rete Z-Wave.

**Ripristino delle impostazioni di fabbrica**

_(Utilizzare il ripristino delle impostazioni di fabbrica solo quando il pannello di controllo/gateway di rete è mancante o inutilizzabile)._

-   -   Tieni premuto il pulsante funzione per 10 secondi per ripristinare le impostazioni di fabbrica.

_\\<NOTE>_

-   -   -   Il ripristino delle impostazioni di fabbrica dell'interruttore del relè di potenza lo ripristinerà alle impostazioni predefinite di fabbrica (escluse dalla rete Z-Wave). Il gateway o il pannello di controllo Z-Wave manterrà comunque le impostazioni Z-Wave. Fare riferimento al manuale del gateway o del pannello di controllo su come rimuovere le impostazioni Z-Wave dell'interruttore del relè di potenza.
-   _**Prova di portata**_

Per verificare se il dispositivo è in grado di comunicare con il gateway Z-Wave o la centrale di controllo:

-   -   -   Mettere il gateway/pannello in modalità test di portata (Walk Test).
        -   Premere il pulsante funzione sul dispositivo.
        -   Il gateway/pannello dovrebbe essere visualizzato se il dispositivo si trova all'interno del raggio d'azione (fare riferimento al manuale operativo del gateway/pannello).
-   _**Controllo degli elettrodomestici**_
    -   Dopo che l'interruttore relè di potenza si è unito con successo a una rete Z-Wave, il coordinatore può accendere/spegnere l'apparecchio da remoto.
    -   È inoltre possibile premere il pulsante sull'interruttore del relè di potenza per accendere/spegnere la luce.
    -   È possibile accendere/spegnere l'interruttore del relè di potenza con un interruttore esterno.
    -   Se hai associato un controller all'interruttore del relè di potenza, puoi anche utilizzare il controller per accendere/spegnere l'interruttore del relè di potenza.
    -   Se l'ingresso dell'alimentazione CA viene disconnesso dall'interruttore del relè di potenza, il suo precedente stato di accensione/spegnimento verrà ripristinato entro 1 minuto dalla riconnessione dell'ingresso dell'alimentazione CA all'interruttore del relè di potenza.
-   _**Monitoraggio del consumo energetico**_
    -   L'interruttore relè di potenza trasmetterà un segnale con i dati sul consumo energetico ogni 1 minuto al coordinatore di rete Z-Wave.
    -   Ogni volta che l'output energetico dell'interruttore di alimentazione cambia di +/- 2 W, trasmetterà automaticamente un segnale con i dati sul consumo energetico al coordinatore di rete Z-Wave per l'aggiornamento.
    -   L'interruttore di alimentazione trasmette un segnale con i dati di potenza al coordinatore ogni volta che il consumo energetico accumulato aumenta di 0,1 kW/ora.
    -   Il misuratore ha una precisione del +/- 5%.
    -   2 metodi per cancellare i dati di consumo energetico accumulati dall'interruttore del relè di potenza:
        -   1.  Utilizza la classe di comando di ripristino del contatore.
            2.  Esegui il ripristino delle impostazioni di fabbrica. Tenere premuto il pulsante funzione per 10 secondi.

_\\<NOTE>_

-   Se esegui il ripristino delle impostazioni di fabbrica, il dispositivo verrà rimosso dalla rete Z-wave. Devi includerlo di nuovo. Per le istruzioni di Inclusione fare riferimento alla sezione di_**Aggiunta di dispositivi (inclusione)**._

2

-   _**Carico operativo massimo**_
    -   Per 110 V: il carico operativo massimo è 1100 W e 10 A.
    -   Per 230 V: il carico massimo di funzionamento è 2300 W e 10 A.
    -   Se l'interruttore del relè di potenza si surriscalda, interromperà automaticamente l'alimentazione come misura di sicurezza. L'utente deve scollegare e ricollegare l'alimentazione CA all'interruttore del relè di potenza dopo l'interruzione per riprendere il normale funzionamento.
-   _**Informazioni sull'onda Z**_

**Tipo di dispositivo:**Interruttore di accensione/spegnimento

**Tipo di ruolo:**Sempre attivo come schiavo (AOS)

**Supporto/controllo della classe di comando**

**Supporto CC obbligatorio:**Associazione CC, v2 o successiva

Associazione Gruppo Informazioni CC

Misuratore CC, v2

CC di base

Interruttore binario CC

Dispositivo reimpostato localmente CC

CC specifico del produttore

Livello di potenza CC

Versione CC, v2 o successiva

Z-Wave Plus Informazioni CC

**Supporto CC consigliato:**Metadati aggiornamento firmware CC

-   _**Gruppi di Z-Wave (Associazione Command Class Versione 2)**_

Lo Switch può essere impostato per inviare report ai dispositivi Z-Wave associati. Supporta un gruppo di associazione con supporto di cinque nodi per il Raggruppamento 1. Per il Raggruppamento 1, lo Switch segnalerà il suo stato più recente al Gateway/Pannello Z-Wave.

Il raggruppamento 1 include:

Commutatore binario CC (SWITCH_BINARIO_RAPPORTO)

Misuratore CC, v2 (METRO_RAPPORTO_COMANDO)

Ripristina dispositivo localmente CC (COMMAND_CLASSE_DISPOSITIVO_RIPRISTINA_LOCALMENTE)

-   Segnalazione automatica al Raggruppamento 1 (nodo massimo 5)
-   Rapporto eventi on/off

Quando si alterna tra On/Off, invierà il report di cambio binario ai nodi del Raggruppamento 1.

3
