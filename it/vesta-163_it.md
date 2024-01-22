# VESTA163

**PRS5-P5-ZW**

**Interruttore relè di potenza Z-Wave**

**introduzione**

L'interruttore relè di potenza è in grado di ricevere segnali wireless dal coordinatore nella rete Z-Wave per attivare/disattivare gli apparecchi ad esso collegati.

L'interruttore relè di potenza è un dispositivo abilitato Z-Wave ed è completamente compatibile con qualsiasi rete abilitata Z-Wave.

Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. Sfruttando la rete mesh Z-Wave, i comandi possono essere trasmessi a destinazione tramite prodotti Z-Wave intermediari "in ascolto".

PRS5-P5-ZW funge anche da router nella rete Z-Wave. Dopo essere stato incluso nella rete Z-Wave, consente ad altri dispositivi Z-Wave di unirsi alla rete tramite l'interruttore di accensione.

**Identificazione delle parti**

![](<.gitbook/assets/0 (58).jpeg>)

**1. Indicatore LED**

L'indicatore LED viene utilizzato per indicare lo stato dell'interruttore del relè di alimentazione:

-   -   SU:

L'interruttore del relè di potenza è acceso.

-   -   Spento:

L'interruttore del relè di potenza è spento.

-   -   Lampeggia due volte:

L'interruttore relè di potenza è stato aggiunto con successo alla rete Z-Wave.

-   -   Lampeggia tre volte

L'interruttore del relè di potenza si è collegato correttamente a un controller.

-   -   Lampeggia cinque volte

L'interruttore del relè di potenza non è riuscito a collegarsi a un controller.

1.  **Pulsante funzione**

Il pulsante funzione viene utilizzato per controllare l'interruttore del relè di potenza:

**Utilizzo dei pulsanti funzione:**

-   -   Premere il pulsante per attivare/disattivare l'interruttore del relè di potenza
    -   Premere il pulsante 3 volte entro 1,5 secondi per inviare un codice di apprendimento.
    -   Tieni premuto il pulsante per 3 secondi, quindi rilascialo per associarlo a un controller
    -   Tieni premuto il pulsante per 10 secondi per ripristinare le impostazioni di fabbrica.

1.  **Cavo di collegamento dello switch esterno 1 (rosso)**
2.  **Cavo di collegamento dello switch esterno 2 (arancione)**
3.  **Uscita carico alimentazione linea CA (giallo)**
4.  **Ingresso alimentazione neurale CA/Uscita carico alimentazione CA neutra (blu)**
5.  **Ingresso alimentazione linea CA (marrone)**

**Attenzione**

-   Tutti gli interventi sul dispositivo, comprese l'installazione e la manutenzione, devono essere eseguiti da un elettricista qualificato e autorizzato.
-   Prima dell'installazione o di qualsiasi intervento di manutenzione, assicurarsi che l'alimentazione elettrica sia stata scollegata.
-   Non collegare il dispositivo a carichi che superano la corrente di carico supportata.

**Installazione**

-   _**Cablaggio con connettore di giunzione**_
    -   L'interruttore relè di potenza viene fornito con cavo integrato per il collegamento all'alimentazione CA, all'apparecchio e all'interruttore esterno. Per il collegamento sono forniti cinque connettori di giunzione Wago 221.
    -   I connettori a 2/3 fili accettano cavi rigidi e intrecciati da 0,2 a 4 mm² (24–12 AWG).
    -   Prima del cablaggio, assicurarsi che l'alimentazione sia disattivata. Per collegare i fili:

1

1.  Sollevare la leva e inserire il filo marrone.**(Foto 1, 2)**

![](<.gitbook/assets/1 (52).png>)

**Immagine1****Immagine 2**

1.  Spingere nuovamente la leva verso il basso. L'alloggiamento trasparente consente di verificare se il cavo è collegato correttamente. Assicurati che il filo sia tenuto saldamente in posizione e non si stacchi.**(Foto 3, 4)**

![](<.gitbook/assets/2 (56).png>)

|                                                     | **Immagine 3**                         | **Immagine 4** |   |
| --------------------------------------------------- | -------------------------------------- | -------------- | - |
| 3) Allo stesso modo dei passaggi 1 e 2, inserire in | un altro polo il cavo a cui collegarsi |                |   |
| Ingresso alimentazione linea CA.**(Foto 5)**        |                                        |                |   |
|                                                     |                                        |                |   |
|                                                     |                                        |                |   |

![](<.gitbook/assets/3 (43).jpeg>)

**Immagine 5**

1.  Ripetere i passaggi 1, 2 e 3 per collegare gli altri fili con i connettori.

Si prega di notare che il filo blu deve essere collegato a un connettore a 3 fili e quindi collegato all'ingresso di alimentazione neurale CA e all'uscita di carico di alimentazione neutra CA.**(Foto 6)**

![](<.gitbook/assets/4 (56).png>)

**Immagine 6**

**Configurazione della rete Z-Wave**

-   _**Aggiunta di dispositivi (inclusione)**_

Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o altre applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete.

-   Collegare l'interruttore del relè di potenza al cavo di alimentazione.
-   L'interruttore del relè di potenza emetterà un segnale acustico a 2 toni.
-   Inserisci il gateway Z-Wave o il pannello di controllo**Inclusione**O**Apprendimento**modalità (fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).

2

-   -   Entro 1,5 secondi, premere il pulsante funzione 3 volte. L'interruttore del relè di potenza emetterà un segnale acustico a 2 toni.
    -   Fare riferimento al manuale operativo del gateway Z-Wave o del pannello di controllo per completare il processo di apprendimento.
    -   Se il sensore è già stato**incluso**(appreso) in un altro gateway/pannello di controllo Z-Wave, o se non è possibile apprendere il sensore nell'attuale gateway/pannello di controllo Z-Wave, escluderlo prima (vedere_**Esclusione**_) prima di tentare di farlo**includere**nell'attuale gateway/pannello di controllo Z-Wave.
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

-   -   Mettere il gateway/pannello in modalità test di portata (Walk Test).
    -   Premere il pulsante funzione sul dispositivo.
    -   Il gateway/pannello dovrebbe essere visualizzato se il dispositivo si trova all'interno del raggio d'azione (fare riferimento al manuale operativo del gateway/pannello).
-   _**Modalità di sospensione Z-Wave**_
    -   L'interruttore del relè di alimentazione entrerà in modalità sospensione Z-Wave (per risparmiare energia) dopo essersi attivato per un breve periodo di tempo (~10 secondi). Durante la modalità di sospensione Z-Wave, i gateway Z-Wave o i pannelli di controllo non sono in grado di inviare comandi all'interruttore del relè di potenza.
    -   Per programmare l'interruttore del relè di potenza, inviare i comandi all'interruttore del relè di potenza entro il periodo di riattivazione.
-   _**Associazione con il controller**_

Dopo essersi unito alla rete Z-Wave, l'interruttore relè di potenza può collegarsi con un dispositivo controller che può essere utilizzato per regolare il livello di potenza in uscita dell'interruttore relè di potenza. Per collegare l'interruttore del relè di potenza e il dispositivo:

1.  Tenere premuto il pulsante funzione per 3 secondi, quindi rilasciare il pulsante. L'interruttore del relè di potenza invierà una richiesta vincolante al coordinatore.
2.  Fare riferimento al manuale del controller per inviare una richiesta vincolante per il dispositivo entro 16 secondi.
3.  Se il collegamento ha esito positivo, l'indicatore LED dell'interruttore del relè di potenza lampeggerà 3 volte per confermare. Ora è possibile utilizzare il controller per regolare il livello di potenza in uscita per l'interruttore del relè di potenza.
4.  Se il collegamento non ha successo, l'indicatore LED dell'interruttore del relè di potenza lampeggerà 5 volte. Riprova il processo di associazione.

![](<.gitbook/assets/5 (27).jpeg>)

**Operazione**

-   _**Schema di collegamento dei cavi**_
    -   Fare riferimento allo schema per collegare l'illuminazione domestica all'interruttore del relè di potenza.
-   _**Installazione**_
    -   Collegare l'interruttore del relè di potenza al cavo di alimentazione.
    -   Collega l'interruttore del relè di potenza all'illuminazione domestica. L'illuminazione deve essere in stato ON.
    -   È possibile collegare un interruttore esterno all'interruttore del relè di potenza secondo lo schema per accendere/spegnere l'interruttore del relè di potenza.

3

-   -   _**NOTA IMPORTANTE**_**:**L'interruttore del relè di alimentazione non dispone di una batteria di riserva e verrà spento in caso di interruzione dell'alimentazione CA.**NON**utilizzare l'interruttore relè di potenza come router per il sensore di sicurezza o dispositivi di controllo allarme come contatto porta, sensore PIR... ecc., altrimenti i sensori perderanno la connessione alla rete Z-Wave se l'interruttore relè di potenza è scollegato dall'alimentazione CA. Pianificare le posizioni di installazione di questi sensori di sicurezza senza utilizzare l'interruttore relè di potenza e utilizzare solo un router con batteria di backup. La funzione router dell'interruttore di alimentazione dovrebbe**SOLTANTO**essere utilizzato per fornire l'estensione della portata del segnale per altri interruttori di alimentazione/dimmer.
-   _**Controllo degli elettrodomestici**_
    -   Dopo che l'interruttore relè di potenza si è unito con successo a una rete Z-Wave, il coordinatore può accendere/spegnere l'apparecchio da remoto.
    -   È inoltre possibile premere il pulsante sull'interruttore del relè di potenza per accendere/spegnere la luce.
    -   È possibile accendere/spegnere l'interruttore del relè di potenza con un interruttore esterno.
    -   Se hai associato un controller all'interruttore del relè di potenza, puoi anche utilizzare il controller per accendere/spegnere l'interruttore del relè di potenza.
    -   Se l'ingresso dell'alimentazione CA viene disconnesso dall'interruttore del relè di potenza, il suo precedente stato di accensione/spegnimento verrà ripristinato entro 1 minuto dalla riconnessione dell'ingresso dell'alimentazione CA all'interruttore del relè di potenza.
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

4
