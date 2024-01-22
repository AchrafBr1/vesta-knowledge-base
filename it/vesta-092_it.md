# VESTA092

**VRCP-DECT****Estensore di voce**

VRCP-DECT è un estensore vocale che consente agli utenti di richiedere assistenza di emergenza con il comando di riconoscimento vocale o premendo un solo pulsante. VRCP-DECT dispone di riconoscimento vocale integrato e può attivare una chiamata di emergenza al CMS tramite comandi vocali o parole chiave preimpostate. È adatto per l'assistenza medica e agli anziani, per case a più piani e per locali più grandi.

-   _**Identificazione delle parti:**_

![](<.gitbook/assets/0 (47).jpeg>)

1.  **Pulsante ALLARME**
    -   -   Premere il pulsante per ricevere aiuto e per aprire la comunicazione bidirezionale.
        -   Tenere premuto il pulsante per 5 secondi durante la comunicazione bidirezionale per richiedere alla centrale di controllo di terminare la comunicazione. Il Pannello di Controllo terminerà o meno la comunicazione a seconda delle impostazioni dell'utente.
2.  **LED rosso**
    -   Acceso: VRCP-DECT non è stato acquisito nel pannello di controllo.
    -   Lampeggia ogni 5 secondi: batteria scarica
    -   3 secondi acceso, 3 secondi spento: guasto CA
    -   Lampeggia due volte: apprendimento riuscito
3.  **LED verde**
    -   -   Acceso: VRCP-DECT è in fase di apprendimento nel pannello di controllo. VRCP-DECT è in comunicazione bidirezionale
4.  **Altoparlante**
5.  **Microfono per VR (riconoscimento vocale)**
6.  **Microfono per comunicazione bidirezionale**
7.  **Presa CC**
    -   Collegamento dell'adattatore di alimentazione SPS DC 9V 1A
8.  **Pulsante Test/Apprendimento**

1

-   -   Tenere premuto il pulsante per 3 secondi finché VRCP-DECT emette 1 lungo segnale acustico per indicare che è entrato in modalità di apprendimento.

1.  **Interruttore della batteria**
2.  **Interruttori DIP**
3.  **Fori di montaggio**
4.  **Segno del triangolo**
    -   Il segno del triangolo dovrebbe puntare verso l'alto quando la staffa è fissata al muro.

-   _**Alimentazione elettrica:**_

Voice Extender può essere alimentato tramite alimentazione CA o batteria.

**Corrente alternata:**Per il collegamento all'alimentazione CA viene fornito un adattatore di alimentazione SPS CC 9 V 1 A.

-   Quando l'alimentazione CA è disconnessa, il LED rosso si accenderà/spegnerà ogni 3 secondi per indicare un guasto CA. DECT verrà disattivato per risparmiare la carica della batteria.
-   Una volta ripristinata l'alimentazione CA, il LED rosso si spegnerà per indicare il ripristino del guasto CA. Il DECT verrà riacceso e ricollegato al Pannello di Controllo.

**Batteria:**Quando l'alimentazione CA è disconnessa, VRCP-DECT passerà all'utilizzo della batteria ricaricabile interna.

-   -   Quando la tensione della batteria è bassa, VRCP-DECT invierà un segnale di batteria scarica al pannello di controllo per notificare la situazione.
    -   La condizione di batteria scarica verrà ripristinata 12 ore dopo che l'alimentazione CA è stata fornita a VRCP-DECT. VRCP-DECT invierà anche un segnale di ripristino della batteria scarica alla centrale di controllo.
    -   Se l'interruttore della batteria è impostato su OFF, la batteria non verrà caricata quando l'alimentazione CA è collegata e non fungerà nemmeno da fonte di alimentazione di riserva quando manca l'alimentazione CA. È necessario accendere la batteria affinché venga caricata quando l'alimentazione CA è collegata e serva come fonte di alimentazione di riserva quando manca l'alimentazione CA.
-   _**Segnale di vigilanza**_
    -   -   Dopo l'installazione, il VRCP-DECT trasmetterà automaticamente il segnale di supervisione al pannello di controllo ogni 24 ore.
-   _**Sensibilità al riconoscimento vocale**_
-   La funzione di riconoscimento vocale ha tre livelli di sensibilità: alto, medio, basso. Quando il livello di sensibilità è impostato su alto, VRCP-DECT rileverà più facilmente la parola chiave/comando e attiverà l'allarme.
-   Utilizzare uno strumento affilato per regolare le posizioni degli interruttori DIP per impostare il livello di sensibilità.

![](<.gitbook/assets/1 (44).png>)

|   |                   | **IMMERSIONE**    |        |   | **Ricerca (livello di sensibilità)** |   |   |   |
| - | ----------------- | ----------------- | ------ | - | ------------------------------------ | - | - | - |
|   |                   |                   |        |   |                                      |   |   |   |
|   |                   |                   |        |   |                                      |   |   |   |
|   | **Interruttore1** |                   |        |   |                                      |   |   |   |
|   |                   | **Interruttore2** |        |   |                                      |   |   |   |
|   |                   |                   |        |   |                                      |   |   |   |
|   | SPENTO            |                   | SPENTO |   | Basso                                |   |   |   |
|   |                   |                   |        |   |                                      |   |   |   |
|   | SU                |                   | SPENTO |   | medio                                |   |   |   |
|   |                   |                   |        |   |                                      |   |   |   |
|   | SPENTO            |                   | SU     |   | Alto                                 |   |   |   |
|   |                   |                   |        |   |                                      |   |   |   |

![](<.gitbook/assets/2 (34).jpeg>)

_**\\<NOTE>**_

-   Dopo aver modificato le impostazioni del Dip Switch, scollegare l'alimentazione (sia l'alimentatore esterno che le batterie devono essere rimosse) e quindi ricollegare l'alimentazione a VRCP-DECT. VRCP-DECT funzionerà con la nuova impostazione di sensibilità dopo la riaccensione.

2

-   _**Procedure di apprendimento:**_

Passaggio 1. Apri la pagina web del Pannello e inizia con la modalità di apprendimento. Fare riferimento al manuale del Pannello di controllo per i dettagli.

Passaggio 2. Tieni premuto il pulsante di apprendimento del VRCP-DECT per 3 secondi finché non senti un lungo segnale acustico, quindi rilascia il pulsante. VRCP-DECT entrerà in modalità di apprendimento per 30 secondi. Il LED verde sarà acceso durante la modalità di apprendimento.

Passaggio 3. Quando il pannello di controllo riceve il segnale da VRCP-DECT, visualizzerà le informazioni di conseguenza. Se il dispositivo che desideri apprendere esiste già nel sistema, le informazioni sul dispositivo verranno visualizzate nella sezione Dispositivo appreso. In caso contrario, le informazioni sul dispositivo verranno visualizzate nella sezione Dispositivo rilevato.

Passaggio 4.VRCP-DECT emetterà due segnali acustici per indicare l'avvenuto apprendimento dopo aver ricevuto la conferma dal pannello di controllo.

Passaggio 5. Fare clic su "Aggiungi" sulla pagina Web per includere il dispositivo selezionato nel pannello.

_**\\<NOTE>**_

-   -   Se VRCP-DECT non riceve conferma dal pannello di controllo durante la modalità di apprendimento di 30 secondi, emetterà un segnale acustico di tono basso per indicare che l'apprendimento non è riuscito e uscirà dalla modalità di apprendimento. Il LED verde si spegnerà e il LED rosso si accenderà. Si prega di eseguire nuovamente i passaggi di apprendimento.
-   _**Operazione:**_

**Rapporto di emergenza**

-   Quando si preme il**ALLARME**oppure pronuncia lo specifico comando vocale, verrà inviato un rapporto di emergenza e verrà stabilita una comunicazione Bidirezionale secondo la durata impostata nel tuo Pannello di Controllo. Durante la comunicazione il LED verde si accenderà.
-   Le parole di attivazione potrebbero essere “SARA Alarm (tedesco)”, “SARA Help (inglese)” o “Help Me (inglese)”, a seconda della versione del firmware. "SARA Alarm (tedesco)" deve essere pronunciato due volte entro 5 secondi per attivare l'allarme, mentre "SARA Help (inglese)" o "Help Me (inglese)" deve essere pronunciato solo una volta per attivare l'allarme.

**Modi per cercare aiuto**

![](<.gitbook/assets/3 (50).png>)

**O**

-   VRCP-DECT terminerà la chiamata allo scadere del tempo. Il LED verde si spegnerà.
-   Durante la comunicazione bidirezionale, è possibile tenere premuto il pulsante ALLARME per 5 secondi per richiedere al pannello di controllo di terminare la comunicazione. Il pannello di controllo terminerà o meno la comunicazione bidirezionale a seconda delle impostazioni dell'utente.

3

![](<.gitbook/assets/4 (46).png>)

_**\\<NOTE>**_

-   Quando l'opzione di richiamata è abilitata sul pannello di controllo, il LED verde rimarrà acceso dopo che la chiamata è stata terminata. Il LED verde si spegnerà allo scadere del timer di richiamata. Fare riferimento al manuale del Pannello di controllo per ulteriori dettagli sulla funzione di richiamata.
-   Quando la funzione di annullamento VRCP-DECT è abilitata sul pannello di controllo, premendo il pulsante su VRCP-DECT si interromperà la comunicazione bidirezionale. Quando la funzione di annullamento VRCP-DECT è disabilitata, premendo il pulsante su VRCP-DECT non si interromperà la comunicazione bidirezionale.
-   Per garantire la precisione del riconoscimento vocale, evitare di installare VRCP-DECT in una stanza grande o rumorosa.
-   L'ambiente ideale per il riconoscimento vocale è il silenzio o il silenzio parziale. Se si pronuncia il comando vocale con voce normale, parlare entro 2 metri da VRCP-DECT per garantire l'attivazione dell'allarme.
-   La funzione di riconoscimento vocale ha tre livelli di sensibilità. Puoi provare con loro e selezionare il livello che meglio si adatta alla tua posizione di montaggio.

**Report allarme attivato da altri dispositivi**

-   Quando viene attivato un allarme da un dispositivo appreso nel pannello di controllo e viene selezionato "808RV" per la funzione On bidirezionale sulla pagina Web del dispositivo, una comunicazione bidirezionale verrà avviata automaticamente con VRCP-DECT senza premere alcun pulsante.

_**\\<NOTE>**_

-   Questa funzione di risposta automatica alla chiamata e di apertura della comunicazione bidirezionale è disponibile solo quando l'alimentazione CA è collegata a VRCP-DECT.
-   Se l'alimentazione CA viene disconnessa da VRCP-DECT, DECT verrà disattivato, VRCP-DECT non sarà in grado di rispondere alla chiamata e verrà invece avviata la comunicazione bidirezionale con GX.

![](<.gitbook/assets/5 (45).png>)

4

**Chiamata in arrivo**

-   -   Quando c'è una chiamata in arrivo, premendo il pulsante ALARM su VRCP-DECT si risponderà alla chiamata.
-   _**Montaggio VRCP-DECT**_

Dopo che il VRCP-DECT è stato appreso con successo e dopo aver eseguito il Walk Test per confermare che il dispositivo si trova nel raggio del segnale del pannello di controllo, inoltre sei soddisfatto che il livello di sensibilità selezionato funzioni nella posizione scelta, puoi procedere con l'installazione . Il VRCP-DECT può essere montato a parete o utilizzato su una superficie piana.

**Montaggio a parete**

Assicurarsi che VRCP-DECT sia montato approssimativamente all'altezza del petto, dove il pulsante sia facilmente accessibile e azionabile.

1.  Supera i 2 fori sulla staffa di montaggio a parete.
2.  Utilizza i 2 fori come modello per delimitare le posizioni dei fori. Assicurati che il simbolo del triangolo sulla staffa sia rivolto verso l'alto.
3.  Praticare 2 fori e avvitare la staffa al muro.
4.  Collegare un adattatore di alimentazione SPS CC 9 V 1 A al jack CC e mantenere il cavo ben posizionato

![](<.gitbook/assets/6 (31).jpeg>)

1.  Montare VRCP-DECT sulla staffa di montaggio. Assicurarsi che il segno impresso su VRCP-DECT sia allineato con il segno superiore sulla staffa.
2.  Ruotare VRCP-DECT in senso orario nella posizione di blocco.

![](<.gitbook/assets/7 (27).jpeg>)

**Posizionamento in superficie**

Il VRCP-DECT può essere utilizzato su una superficie piana senza essere installato in una posizione fissa.

1.  Pulisci il retro del VRCP-DECT con uno sgrassatore.
2.  Collegare l'adattatore di alimentazione SPS DC 9V 1A al jack DC e mantenere il cavo ben posizionato a destra o a sinistra. (**Immagine 1**)
3.  Rimuovere il supporto in carta del cuscinetto antiscivolo e applicarlo sul retro del VRCP-DECT. (**Immagine 2**)
4.  Posiziona VRCP-DECT nella posizione desiderata. (**Immagine 3**)

5

**Immagine 1****Immagine 2****Immagine 3**

![](<.gitbook/assets/8 (29).png>)

6
