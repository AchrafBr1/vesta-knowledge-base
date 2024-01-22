# VESTA269

**Pinza amperometrica (CLMT-1ZW)**

CL-Meter-ZW è un multimetro a pinza Z-Wave che mira a monitorare e segnalare la quantità totale di consumi elettrici nella vostra struttura collegando la pinza al cavo di alimentazione.

Il contatore di energia è un dispositivo abilitato Z-Wave ed è completamente compatibile con qualsiasi rete abilitata Z-Wave.

Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. Sfruttando la rete mesh Z-Wave, i comandi possono essere indirizzati a destinazione tramite prodotti Z-Wave intermedi di "ascolto".

![](<.gitbook/assets/0 (100).jpeg>)

**Identificazione delle parti**

**1. LED rosso**

Lampeggia una volta:

Quando la pinza amperometrica sta trasmettendo un segnale.

Lampeggia due volte:

La pinza amperometrica si è unita con successo a una rete Z-Wave.

1.  **Cavo di ingresso CA**
2.  **Cavo trasformatore di corrente (CT2)**
3.  **Cavo trasformatore di corrente (CT1)**
4.  **Pulsante funzione**

\-Premere una volta il pulsante per segnalare il valore del contatore alla rete Z-Wave.

\-Premere il pulsante 3 volte entro 1,5 secondi per trasmettere un codice di apprendimento.

\-Tenere premuto il pulsante per 10 secondi per ripristinare le impostazioni di fabbrica della pinza amperometrica.

1.  **Riservato**
2.  **Foro di montaggio**
3.  **Ganci di montaggio**
4.  **Staffa di fissaggio**

**Installazione**

![](<.gitbook/assets/1 (69).png>)

-   _**Cablaggio**_

![](<.gitbook/assets/2 (76).png>)**AVVERTIMENTO**

Il cablaggio del dispositivo deve essere eseguito solo da un elettricista autorizzato. L'interruttore principale della scatola dei circuiti deve essere spento per eseguire l'installazione.

La specifica del filo del foro di inserimento è AWG18 o Ø 1,02 (mm²).

La specifica del morsetto è 60A Ø 10mm

Assicurati che anche l'alimentazione principale della tua struttura sia spenta prima dell'installazione. Seguire i passaggi seguenti:

1.  Collegare il cavo di ingresso CA a una presa vicino alla scatola elettrica per accendere la pinza amperometrica.
2.  Aprire il morsetto come indicato nell'immagine seguente. Il morsetto deve essere applicato su un cavo elettrico. La direzione della freccia sul morsetto deve puntare nella direzione corretta dei flussi di corrente elettrica (**KL**). Se la freccia è rivolta nella direzione opposta, la lettura visualizzerà un valore negativo (-) ma non influenzerà le letture.

![](<.gitbook/assets/3 (74).png>)

**K**

**L**

1.  Seguire gli schemi seguenti come esempio; agganciare i morsetti sui cavi elettrici sul 2 cavo di alimentazione in ingresso collegato all'interruttore principale.

![](<.gitbook/assets/4 (79).png>)

-   _**Montaggio**_

La pinza amperometrica è dotata di una staffa di montaggio per il montaggio.

1.  Utilizzare la staffa di montaggio come modello per contrassegnare i due fori sulla parete per l'installazione delle viti.
2.  Avvitare la staffa di montaggio sulla parete in base alla posizione contrassegnata. Se necessario, installare i tasselli.
3.  Individuare i ganci della staffa di montaggio e allinearli con i fori di montaggio sulla pinza amperometrica. Montare i ganci nei fori di montaggio come nell'immagine seguente. L'installazione è ora completa.

![](<.gitbook/assets/5 (79).png>)

-   _**Aggiunta di dispositivi (inclusione)**_

Questo prodotto può essere incluso e utilizzato in qualsiasi rete Z-Wave con altri dispositivi certificati Z-Wave di altri produttori e/o altre applicazioni. Tutti i nodi non alimentati a batteria all'interno della rete fungeranno da ripetitori indipendentemente dal fornitore per aumentare l'affidabilità della rete.

-   -   Collegare il cavo di ingresso CA alla presa per accendere la pinza amperometrica.
    -   Inserisci il pannello di controllo Z-Wave**Modalità di inclusione**(fare riferimento al manuale del pannello di controllo Z-Wave).
    -   Entro 1,5 secondi, premere il pulsante funzione 3 volte.
    -   Fare riferimento al manuale operativo del Z-Wave Gateway o del pannello di controllo per completare il processo di aggiunta.
    -   Se il dispositivo è già stato aggiunto (incluso) in un altro gateway/pannello di controllo Z-Wave, o se non è possibile aggiungere il dispositivo all'attuale gateway/pannello di controllo Z-Wave, provare prima a rimuoverlo (vedere_**Rimozione del dispositivo**_).
-   _**Rimozione del dispositivo (esclusione)**_

![](<.gitbook/assets/6 (59).png>)

Il dispositivo deve essere rimosso dalla rete Z-Wave esistente prima di essere aggiunto a un'altra.**Modalità di esclusione**

-   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale Z-Wave o al pannello di controllo).
-   Entro 1,5 secondi, premere il pulsante funzione 3 volte e il dispositivo verrà rimosso dalla rete Z-Wave.

**Ripristino delle impostazioni di fabbrica**

Il ripristino delle impostazioni di fabbrica del dispositivo lo ripristinerà alle impostazioni predefinite di fabbrica (ovvero non incluso in alcuna rete Z-Wave). Utilizzare questa procedura solo se il gateway Z-Wave o il pannello di controllo vengono persi o risultano comunque inutilizzabili.

-   -   Tieni premuto il pulsante funzione del dispositivo per 10 secondi per ripristinare le impostazioni di fabbrica.
-   _**Prova di portata**_

![](<.gitbook/assets/7 (54).png>)

Per verificare se il dispositivo è in grado di comunicare con Z-Wave Gateway o pannello di controllo:

-   -   Mettere il Gateway/Pannello di controllo in modalità test di portata (Walk Test).
    -   Premere il pulsante funzione sul dispositivo.
    -   Il Gateway/Pannello di controllo dovrebbe essere visualizzato se il dispositivo si trova all'interno del raggio d'azione (fare riferimento al manuale operativo del Gateway/Pannello di controllo).
-   _**Monitoraggio del consumo energetico**_
    -   -   La pinza amperometrica trasmetterà ogni 10 minuti un segnale dalla pinza stessa con i dati sul consumo energetico al coordinatore della rete Z-Wave.
            -   La lettura dal morsetto sul cavo del trasformatore di corrente CT-1 viene segnalata al canale 1 del misuratore
            -   La lettura dal morsetto sul cavo del trasformatore di corrente CT-2 viene segnalata al canale 2 del misuratore.
        -   Ogni volta che la produzione di energia della pinza cambia di +/- 2 W, la pinza amperometrica trasmetterà automaticamente un segnale con i dati sul consumo energetico al coordinatore di rete Z-Wave per l'aggiornamento.
        -   La pinza amperometrica trasmette un segnale con i dati di potenza al coordinatore ogni volta che il consumo energetico accumulato della pinza aumenta di 0,1 kW/ora.
        -   Il morsetto ha una precisione del +/- 5%.
        -   Per cancellare il limite dei dati di consumo energetico accumulati, seguire i passaggi seguenti:

![](<.gitbook/assets/8 (54).png>)

1.  Scollegare il cavo CA per spegnere la pinza amperometrica.
2.  Premere e tenere premuto il pulsante funzione, mentre si tiene premuto il pulsante, accendere la pinza amperometrica ricollegando il cavo CA.
3.  Rilasciare il pulsante funzione quando il LED rosso inizia a lampeggiare velocemente.
4.  Scollegare e ricollegare nuovamente il cavo CA, la pulizia è completata.

-   ![](<.gitbook/assets/9 (50).png>)_**Carico operativo massimo**_
    -   110 V: 6600 W e 60 A
    -   230 V: 13800 W e 60 A.

**Informazioni sull'onda Z**

**Tipo di dispositivo:**Contatore per tutta la casa: semplice

**Tipo di ruolo:**Sempre attivo come schiavo (AOS)

Supporto/controllo della classe di comando

Supporto CC obbligatorio: Association CC, v2

Associazione Gruppo Informazioni CC

Dispositivo reimpostato localmente CC

CC specifico del produttore, v2

Associazione multicanale CC, V3

CC multicanale, V4

Misuratore CC, V2

CRC 16 ENCAP

Versione CC, v2

Z-Wave Plus Informazioni CC, v2

Livello di potenza CC,

Aggiornamento firmware CC, v2

![](<.gitbook/assets/10 (52).png>)

-   _**Gruppi di Z-Wave (Associazione Command Class Versione 2)**_

Lo strumento può essere impostato per inviare report ai dispositivi Z-Wave associati. Supporta 3 gruppi di associazione in cui ogni gruppo ha un supporto per nodo. Gruppo 1~Gruppo 3 supporta METER_RAPPORTO_COMANDO_Classe

Gruppo 1 per “LifeLine”: (nodo massimo:1)

Ripristino del dispositivo localmente CC, V2

Misuratore CC, V2

Per il gruppo 1, la pinza amperometrica riporterà:

1.  La somma del consumo energetico istantaneo (Watt) letto da CT1 e CT2
2.  La somma del consumo energetico accumulato (KWh) letto da CT1 e CT2 Gruppo 2 per “contatore CT1” (nodo massimo: 1)

Misuratore CC, V2

Per il gruppo 2, lo Switch riporterà:

1.  Consumo energetico istantaneo (Watt) letto da CT1
2.  Consumo energetico accumulato (KWh) letto da CT1 Gruppo 3 per “contatore CT2”: (nodo massimo: 1)

Misuratore CC, V2

Per il gruppo 3, lo Switch riporterà

-   1.  La somma del consumo energetico istantaneo (Watt) letto da CT2
    2.  La somma del consumo energetico accumulato (KWh) letto da CT2
-   _**Associazione multicanale di Z-Wave**_

![](<.gitbook/assets/11 (42).png>)

La classe di comando di associazione multicanale viene utilizzata per creare collegamenti dell'applicazione alle risorse endpoint multicanale e ai dispositivi root. La classe comando può gestire nodi con e senza punti finali.

Per Root, supporta massimo 1 nodo e massimo 3 gruppi di associazione

| Radice   | Profilo 2 byte                 | Classe di comando                     | Nome del gruppo                    |
| -------- | ------------------------------ | ------------------------------------- | ---------------------------------- |
|          |                                |                                       | (UTF-8)                            |
| Gruppo 1 | Generale: ancora di salvezza   | Dispositivo ripristinato localmente e | “Ancora di salvezza”               |
|          |                                | rapporto del contatore                |                                    |
| Gruppo 2 | Contatore: contatore elettrico | rapporto del contatore                | “Contatore CT 1”                   |
|          |                                |                                       | (specchio dell'endpoint 1 gruppo2) |
| Gruppo 3 | Contatore: contatore elettrico | rapporto del contatore                | “Contatore CT 2”                   |
|          |                                |                                       | (specchio dell'endpoint 2 gruppo2) |

Per l'endpoint 1, supporta massimo 1 nodo e massimo 2 gruppi di associazioni.

| Punto finale 1 | Profilo 2 byte                 | Classe di comando      | Nome del gruppo  |
| -------------- | ------------------------------ | ---------------------- | ---------------- |
|                |                                |                        | (UTF-8)          |
| Gruppo 1       | Generale: ancora di salvezza   | rapporto del contatore | “Lifeline EP 1”  |
| Gruppo 2       | Contatore: contatore elettrico | rapporto del contatore | “Contatore CT 1” |

Per Endpoint 2, supporta massimo 1 nodo e massimo 2 gruppi di associazioni.

| Punto finale 2 | Profilo 2 byte                 | Classe di comando      |   | Nome del gruppo  |   |   |
| -------------- | ------------------------------ | ---------------------- | - | ---------------- | - | - |
|                |                                |                        |   | (UTF-8)          |   |   |
|                |                                |                        |   |                  |   |   |
| Gruppo 1       | Generale: ancora di salvezza   | rapporto del contatore |   | “Lifeline EP 2”  |   |   |
| Gruppo 2       | Contatore: contatore elettrico | rapporto del contatore |   | “Contatore CT 2” |   |   |

-   ![](<.gitbook/assets/12 (44).png>)_**Punto finale selezionato**_

Se il controller può utilizzare Multi_Classe di comando del canale per accedere all'endpoint della pinza amperometrica, è possibile configurare il valore dell'endpoint per reagire alla classe di comando del misuratore V2

**Punto finale selezionato 1: (per CT1 del primo canale)**

-   Tipo di dispositivo: contatore semplice
-   Classi di comandi supportate Informazioni Z-Wave Plus CC, Associazione V2 CC, Associazione V2 Informazioni gruppo CC Associazione multicanale CC, V3 Meter CC, V2
-   Descrizione:

Per l'endpoint 1, la pinza amperometrica riporterà

-   1.  Consumo energetico istantaneo (Watt) letto da CT1.
    2.  Consumo energetico accumulato (KWh) letto da CT1.

**Punto finale selezionato 2: (per CT2 del secondo canale)**

-   Tipo di dispositivo: contatore semplice
-   Classi di comandi supportate Informazioni Z-Wave Plus CC, V2 Associazione CC, V2 Associazione Informazioni gruppo CC Associazione multicanale CC, V3 Meter CC, V2
-   Descrizione:

Per l'endpoint 2, la pinza amperometrica riporterà

-   1.  Consumo energetico istantaneo (Watt) letto da CT2.
    2.  Consumo energetico accumulato (KWh) letto da CT2
