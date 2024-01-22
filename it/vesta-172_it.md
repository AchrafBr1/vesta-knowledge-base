# VESTA172

**Sensore della qualità dell'aria (AQS-2-ZW)**

Il sensore di qualità dell'aria AQS-2 è un sensore di qualità dell'aria interna Z-Wave™ che mira a rilevare e monitorare la concentrazione di CO2. Il sensore della qualità dell'aria è compatibile solo con il gateway/pannello di controllo Z-Wave. Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. Sfruttando la rete mesh Z-Wave, i comandi possono essere indirizzati a destinazione tramite prodotti Z-Wave intermedi di "ascolto".

**Identificazione delle parti**

![](<.gitbook/assets/0 (63).jpeg>)

**1. Pulsante funzione**

\-Premere una volta il pulsante per inviare segnali del livello di concentrazione di CO2.

\-Premere il pulsante 3 volte entro 1 secondo per trasmettere un codice di apprendimento.

\-Tieni premuto il pulsante per 10 secondi per eseguire il ripristino delle impostazioni di fabbrica.

**2.****DC Jack**

Si collega a un adattatore CC da 12 V 1 A

**Caratteristiche**

![](<.gitbook/assets/1 (54).png>)

-   _**Alimentazione elettrica**_

Il sensore della qualità dell'aria è alimentato collegandosi con un'uscita DC 12V e un adattatore da 1A. Assicurati di utilizzare solo un adattatore con la tensione CA appropriata per evitare danni ai componenti, oppure utilizza solo l'adattatore di alimentazione CA incluso con il sensore della qualità dell'aria.

Se viene rilevata un'interruzione dell'alimentazione CA, il sensore della qualità dell'aria invierà un rapporto di guasto CA al pannello di controllo.

![](<.gitbook/assets/2 (59).png>)

-   _**Rilevamento dell'anidride carbonica**_
    -   Il sensore della qualità dell'aria misura la concentrazione di CO2 ogni 5 secondi e segnala i dati al pannello di controllo ogni 30 minuti. Se la concentrazione di CO2 cambia di +/- 100 ppm per due volte consecutive, il sensore della qualità dell'aria lo segnalerà al pannello di controllo.
    -   Se la concentrazione di CO2 rilevata è superiore a 1000 ppm, l'AQS-2 invierà un segnale di allarme CO2 al pannello di controllo. Se la concentrazione di CO2 scende al di sotto di 1000 ppm, l'AQS-2 invierà un segnale di ripristino della CO2 al pannello di controllo.
-   _**Aggiunta di dispositivi (inclusione)**_

![](<.gitbook/assets/3 (60).png>)

Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o altre applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete.

-   -   Collegare l'adattatore di alimentazione CA; collegare al jack CC sul sensore della qualità dell'aria per accenderlo.
    -   Inserisci il gateway Z-Wave o il pannello di controllo**Inclusione**modalità (fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
    -   Entro 1 secondo, premere il pulsante funzione 3 volte.
    -   Fare riferimento al manuale operativo del gateway Z-Wave o del pannello di controllo per completare il processo di inclusione.
    -   Se il sensore è già stato**aggiunto**(incluso) in un altro gateway/pannello di controllo Z-Wave, o se non è possibile aggiungere il sensore all'attuale gateway/pannello di controllo Z-Wave, escluderlo prima (vedere_**Rimozione del dispositivo**_) prima di tentare di farlo**includere**nell'attuale gateway/pannello di controllo Z-Wave.
-   _**Rimozione del dispositivo (esclusione)**_

![](<.gitbook/assets/4 (59).png>)

Il sensore della qualità dell'aria deve essere rimosso dalla rete Z-Wave esistente prima di essere incluso in un'altra. Sono disponibili due metodi per escludere un dispositivo.

**Modalità di esclusione**

-   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
-   Entro 1 secondo, premere il pulsante funzione 3 volte e il dispositivo verrà rimosso dalla rete Z-Wave.

1

**Ripristino delle impostazioni di fabbrica**

_(Utilizzare il ripristino delle impostazioni di fabbrica solo quando il pannello di controllo/gateway di rete è mancante o inutilizzabile)._

-   Tenere premuto il pulsante funzione per 10 secondi per eseguire il ripristino delle impostazioni di fabbrica.

_\\<NOTE>_

-   -   Il ripristino delle impostazioni di fabbrica del dispositivo lo ripristinerà alle impostazioni predefinite di fabbrica (esclusa dalla rete Z-Wave). Il gateway Z-Wave o il pannello di controllo manterranno comunque le impostazioni Z-Wave. Fare riferimento al manuale del gateway o del pannello di controllo su come rimuovere le impostazioni Z-Wave del dispositivo.

![](<.gitbook/assets/5 (59).png>)

**Installazione**

![](<.gitbook/assets/6 (40).png>)

-   _**Posizionamento del sensore della qualità dell'aria**_

Il sensore della qualità dell'aria deve essere posizionato su una superficie piana con un'area aperta attorno nella stanza che si desidera monitorare.

Quanto più aperta è la posizione di posizionamento, tanto più accurate saranno le misurazioni della qualità dell'aria.

**Informazioni sull'onda Z**

**Tipo generico:**Cambia multilivello

**Tipo specifico:**Multilivello regolabile a colori

**ID tipo prodotto:**0x0004

**Codice prodotto:**0x0020

**Tipo di ruolo:**Sempre attivo come schiavo (AOS)

**Sicurezza:**S2 non autenticato

**Supporto/controllo della classe di comando**

**Supporto CC obbligatorio:**Z-Wave Plus Informazioni CC, V2

Sensore multilivello CC, V11 (sicurezza 2)

Associazione CC, V2 (sicurezza 2)

Associazione multicanale CC, V3 (sicurezza 2)

CC informazioni sul gruppo di associazione (sicurezza 2)

CC specifico del produttore, V2 (sicurezza 2)

Servizio di trasporto CC, V2

.Versione CC, V3 (sicurezza 2)

.Reset dispositivo localmente CC (sicurezza 2)

.Livello di potenza CC (sicurezza 2)

.CC di sicurezza

Sicurezza 2CC

.Supervisione CC

.Aggiornamento firmware MD CC, V4 (sicurezza 2)

![](<.gitbook/assets/7 (34).png>)

-   _**Gruppi di Z-Wave (Associazione Command Class Versione 2)**_

L'AQS può essere impostato per inviare report ai dispositivi Z-Wave associati. Supporta 1 gruppo di associazione. Gruppo 1 per “LifeLine”: (massimo nodo: 5)

Sensore multilivello (COMANDO_INTERRUTTORE_MULTILIVELLO, INTERRUTTORE_MULTILIVELLO_RAPPORTO)

Reimpostazione del dispositivo localmente

(COMANDO_CLASSE_DISPOSITIVO_RIPRISTINA_LOCALMENTE, DISPOSITIVO_RIPRISTINA_LOCALMENTE_NOTIFICA)

**Sensore multilivello:**Man mano che i livelli di CO2 rilevano cambiamenti; l'AQS trasmetterà il comando multilivello del sensore.

**Ripristino delle impostazioni di fabbrica:**Quando l'AQS è stato ripristinato allo stato predefinito di fabbrica, invierà il ripristino del dispositivo localmente a tutti i nodi del Gruppo 1.

![](<.gitbook/assets/8 (37).png>)

-   _**Formato dei dati della classe di comando**_
    -   Rapporto sulla CO2:\[COMANDO_CLASSE_SENSORE_MULTILIVELLO]\[SENSORE_MULTILIVELLO_RAPPORTO]
        -   Se viene trasmesso il segnale CO2 11 02 06 99, 0699 può essere visualizzato come 0x0699 in numero esadecimale. È possibile convertire l'esadecimale in decimale per verificare il valore di CO2.

0699=0x0699=1689ppm

2
