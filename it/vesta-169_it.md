# VESTA 169

**Controller relè Z-Wave PRL1-ZW-AC**

**introduzione**

PRL1-ZW-AC è un controller relè Z-Wave che può essere collegato a dispositivi cablati e impostato sullo stato Normalmente aperto (N.O.) o Normalmente chiuso (N.C.). Dopo aver aderito alla rete Z-Wave, il controller relè può essere controllato tramite la rete Z-Wave per attivare i dispositivi collegati. Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza.

**Identificazione delle parti**

![](<.gitbook/assets/0 (62).jpeg>)

**1. Indicatore LED**

L'indicatore LED viene utilizzato per indicare lo stato del relè:

-   -   LED acceso: relè acceso
    -   LED spento: relè spento

1.  **Pulsante funzione**

Premere il pulsante 3 volte entro 1,5 secondi per inviare un codice di apprendimento.

Tieni premuto il pulsante per 10 secondi per ripristinare le impostazioni di fabbrica.

Premere il pulsante per accendere/spegnere il relè.

**Terminali di connessione**

Per effettuare il collegamento del cavo, spingere il cavo nel terminale e mantenerlo in posizione. Per rimuovere il cavo collegato, premere il pulsante sopra il terminale, quindi rimuovere il cavo.

1.  **Riservato**
2.  **Linea (ingresso CA)**
3.  **Neutro**
4.  **NO**

![](<.gitbook/assets/1 (55).jpeg>)

Per la connessione Normal Open con il dispositivo.

1.  **Comune**
2.  **NC**

Per la connessione Normal Close con il dispositivo

**Specifica**

-   Fonte di alimentazione (alimentazione esterna): 100-240 V CA
-   Uscita relè: relè SPDT senza potenziale, carico operativo massimo: 5 A (resistivo) a 24 V CC o 240 V CA
-   Filo intrecciato: 16-26 AWG
-   Temperatura operativa: da -10°C a 45°C (da 14°F a 113°F)
-   Umidità: fino all'85% senza condensa
-   Dimensioni: 71,1 mm x 49 mm x 26 mm

![](<.gitbook/assets/2 (49).jpeg>)

**Ambiente di installazione**

-   Il controller relè deve essere installato all'interno in un luogo asciutto.
-   Si consiglia di installare l'apparecchio in una scatola di plastica ignifuga.
-   Non installare il dispositivo in una scatola metallica per ottimizzare la portata RF.

![](<.gitbook/assets/3 (45).jpeg>)

**Attenzione**

-   Tutti gli interventi sul dispositivo, comprese l'installazione e la manutenzione, devono essere eseguiti da un elettricista qualificato e autorizzato.
-   Per evitare scosse elettriche e/o danni all'apparecchiatura, scollegare l'alimentazione elettrica dal fusibile principale o dall'interruttore prima dell'installazione e della manutenzione.
-   Non collegare il dispositivo a carichi che superano la corrente di carico supportata.

1

**Installazione**

La specifica del cablaggio dei fori di inserimento è AWG 16-26 o Ø 1,31-0,129 (mm²).

Cablare il relè secondo le istruzioni seguenti:

![](<.gitbook/assets/4 (44).jpeg>)

1.  Spegnere l'alimentazione prima del collegamento.
2.  Collegare i terminali L e N dell'alimentatore rispettivamente ai terminali Linea e Neutro di PRL.
3.  A seconda del dispositivo che si desidera controllare tramite il relè, selezionare il terminale NO o NC e collegare il relè al dispositivo per stabilire una connessione Normalmente aperta o Normalmente chiusa con il dispositivo.
4.  Dopo aver completato il cablaggio del dispositivo, accendere l'alimentazione per accendere il controller relè.

![](<.gitbook/assets/5 (57).png>)

_\\<IMPORTANT NOTE>_

-   Il cablaggio del PRL deve essere eseguito solo da personale certificato

tecnico con adeguata conoscenza e formazione in apparecchiature elettriche.

**Rete Z-Wave**

![](<.gitbook/assets/6 (39).png>)

-   _**Aggiunta di dispositivi (inclusione)**_
    -   Collegare l'alimentazione al controller relè secondo le istruzioni di installazione nella sezione precedente e accendere il controller relè.
    -   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di inclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
    -   Entro 1,5 secondi, premere il pulsante funzione 3 volte.
    -   Fare riferimento al manuale operativo del gateway Z-Wave o del pannello di controllo per completare il processo di aggiunta.
    -   Se il dispositivo è già stato aggiunto (incluso) in un altro gateway/pannello di controllo Z-Wave, o se non è possibile aggiungere il dispositivo all'attuale gateway/pannello di controllo Z-Wave, provare prima a rimuoverlo (vedere_**Rimozione del dispositivo**_).
-   _**Rimozione del dispositivo (esclusione)**_

![](<.gitbook/assets/7 (33).png>)

Il dispositivo deve essere rimosso dalla rete Z-Wave esistente prima di essere aggiunto a un'altra.**Modalità di esclusione**

-   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
-   Entro 1,5 secondi, premere il pulsante funzione 3 volte e il dispositivo verrà rimosso dalla rete Z-Wave.

**Ripristino delle impostazioni di fabbrica**

-   -   Il ripristino delle impostazioni di fabbrica del dispositivo lo ripristinerà alle impostazioni predefinite di fabbrica (ovvero non incluso in alcuna rete Z-Wave). Utilizzare questa procedura solo se il gateway Z-Wave o il pannello di controllo vengono persi o risultano comunque inutilizzabili.
    -   Tieni premuto il pulsante funzione del dispositivo per 10 secondi per ripristinare le impostazioni di fabbrica.
-   _**Prova di portata**_

![](<.gitbook/assets/8 (34).png>)

Per verificare se il dispositivo è in grado di comunicare con il gateway Z-Wave o la centrale di controllo:

-   Mettere il gateway/pannello in modalità test di portata (Walk Test).
-   Premere il pulsante funzione sul dispositivo.
-   Il gateway/pannello dovrebbe essere visualizzato se il dispositivo si trova all'interno del raggio d'azione (fare riferimento al manuale operativo del gateway/pannello).

**Operazione**

![](<.gitbook/assets/9 (20).jpeg>)

-   _**Controllo relè**_
    -   Quando il controller relè si è unito con successo a una rete Z-Wave, il gateway/pannello di controllo sarà in grado di controllare in remoto il relè per accenderlo, spegnerlo o alternare tra le condizioni On e Off. Per i dettagli fare riferimento al gateway/pannello di controllo Z-Wave.

2

**Informazioni sull'onda Z**

**Tipo di dispositivo:**Interruttore di accensione/spegnimento

**Tipo di ruolo:**Sempre attivo come schiavo (AOS)

**Supporto/controllo della classe di comando**

**Supporto CC obbligatorio:**Associazione CC, v2 o successiva

Associazione Gruppo Informazioni CC

CC di base

Interruttore binario CC

Dispositivo reimpostato localmente CC

CC specifico del produttore

Livello di potenza CC

Versione CC, v2 o successiva

Z-Wave Plus Informazioni CC

**Supporto CC consigliato**: Metadati aggiornamento firmware CC

![](<.gitbook/assets/10 (35).png>)

-   _**Gruppi di Z-Wave (Associazione Command Class Versione 2)**_

Lo Switch può essere impostato per inviare report ai dispositivi Z-Wave associati. Supporta un gruppo di associazione con supporto di cinque nodi per il Raggruppamento 1. Per il Raggruppamento 1, lo Switch segnalerà il suo stato più recente al Gateway/Pannello Z-Wave.

Gruppo 1 per “LifeLine”:

Commutatore binario CC (SWITCH_BINARIO_RAPPORTO)

Ripristina dispositivo localmente CC (COMMAND_CLASSE_DISPOSITIVO_RIPRISTINA_LOCALMENTE)

-   Segnalazione automatica al Raggruppamento 1 (nodo massimo 5)
-   Rapporto eventi on/off

Quando si alterna tra On/Off, invierà il report di cambio binario ai nodi del Raggruppamento 1.

3
