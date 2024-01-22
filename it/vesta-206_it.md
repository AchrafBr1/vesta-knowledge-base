# VESTA206

**Interruttore a levetta relè Z-Wave PRL-3ZW-AC**

**introduzione**

PRL-3ZW-AC è un interruttore a levetta relè Z-Wave. L'interruttore a levetta del relè può essere collegato a un dispositivo cablato e impostato sullo stato Normalmente aperto (N.O.). Dopo aver aderito alla rete Z-Wave, l'interruttore a levetta relè può essere controllato tramite la rete Z-Wave per attivare i dispositivi collegati.

Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. Sfruttando la rete mesh Z-Wave, i comandi possono essere indirizzati a destinazione tramite prodotti Z-Wave intermedi di "ascolto".

Il relè può controllare i nodi Z-Wave semplicemente premendo il pulsante funzione e può anche avvisarti di segnalare problemi di comunicazione.

La serie di interruttori a levetta relè Z-Wave comprende i seguenti modelli:

PRL-3ZW-AC

PRL-xZO-AS-OTA

**Identificazione delle parti**

![](<.gitbook/assets/0 (84).jpeg>)

**1. Indicatore LED**

L'indicatore LED viene utilizzato per indicare lo stato del relè:

-   -   LED acceso: relè acceso
    -   LED spento: relè spento

1.  **Pulsante funzione**

Premere il pulsante 3 volte entro 1,5 secondi per inviare un codice di apprendimento.

Tieni premuto il pulsante per 10 secondi per ripristinare le impostazioni di fabbrica.

Premere il pulsante per accendere/spegnere il relè.

**Terminali di connessione**

Collegare il filo al terminale, stringere la vite per chiudere il clipper e tenere il filo in posizione. Svitare per aprire il clipper per rimuovere il filo collegato al terminale.

1.  **Neutro**
2.  **Linea (ingresso CA)**

Per accendere il PRL-3ZW, collegare i terminali L&N dell'alimentatore ai terminali L&N.

**5. NO**

Per la connessione Normal Open con il dispositivo

**6. Comune**

Collegare i terminali NO e COM del dispositivo cablato ai terminali NO e COM del PRL-3ZW.

**Specifica**

-   Fonte di alimentazione (alimentazione esterna): 100-240 V CA
-   Uscita relè: relè SPDT senza potenziale, carico operativo massimo: 5 A (resistivo) a 24 V CC o 240 V CA.
-   Filo intrecciato: 14~22 AWG
-   Temperatura operativa: da -10°C a 45°C (da 14°F a 113°F)
-   Umidità: fino all'85% senza condensa
-   Dimensioni: 71 mm x 49 mm x 26 mm

![](<.gitbook/assets/1 (73).jpeg>)

**Ambiente di installazione**

-   L'interruttore a levetta del relè deve essere installato all'interno in un luogo asciutto.
-   Si consiglia di installare l'apparecchio in una scatola di plastica ignifuga.
-   Non installare il dispositivo in una scatola metallica per ottimizzare la portata Z-Wave.

1

![](<.gitbook/assets/2 (69).jpeg>)

**Attenzione**

-   Tutti gli interventi sul dispositivo, comprese l'installazione e la manutenzione, devono essere eseguiti da un elettricista qualificato e autorizzato.
-   Per evitare scosse elettriche e/o danni all'apparecchiatura, scollegare l'alimentazione elettrica dal fusibile principale o dall'interruttore prima dell'installazione e della manutenzione.
-   Non collegare il dispositivo a carichi superiori

![](<.gitbook/assets/3 (62).jpeg>)

corrente di carico supportata.

**Installazione**

Cablare il relè secondo le istruzioni riportate di seguito o fare riferimento allo schema per ulteriori informazioni.

1.  Si prega di spegnere l'alimentazione prima del collegamento.
2.  Collegare i terminali L e N dell'alimentatore rispettivamente ai terminali Linea e Neutro di PRL.
3.  A seconda del dispositivo che si desidera controllare tramite il relè, selezionare il terminale NO e collegare il relè al dispositivo per stabilire una connessione normalmente aperta con il dispositivo.
4.  Dopo aver completato il cablaggio, accendere l'alimentazione per accendere l'interruttore a levetta del relè.

![](<.gitbook/assets/4 (68).png>)

_\\<IMPORTANT NOTE>_

-   Il cablaggio del PRL deve essere eseguito solo da un tecnico certificato con conoscenza e formazione adeguate sulle apparecchiature elettriche.

**Caratteristiche**

![](<.gitbook/assets/5 (70).png>)

-   _**Aggiunta di dispositivi (inclusione)**_
    -   Collegare l'ingresso di alimentazione all'interruttore a levetta del relè secondo le istruzioni di installazione sopra riportate e accendere l'interruttore a levetta del relè.
    -   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di inclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
    -   Entro 1,5 secondi, premere il pulsante funzione 3 volte.
    -   Fare riferimento al manuale operativo del gateway Z-Wave o del pannello di controllo per completare il processo di aggiunta.
    -   Se il dispositivo è già stato aggiunto (incluso) in un altro gateway/pannello di controllo Z-Wave, o se non è possibile aggiungere il dispositivo all'attuale gateway/pannello di controllo Z-Wave, provare prima a rimuoverlo (vedere_**Rimozione del dispositivo**_).
-   _**Rimozione del dispositivo (esclusione)**_

![](<.gitbook/assets/6 (49).png>)

Il dispositivo deve essere rimosso dalla rete Z-Wave esistente prima di essere aggiunto a un'altra.**Modalità di esclusione**

-   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
-   Entro 1,5 secondi, premere il pulsante funzione 3 volte e il dispositivo verrà rimosso dalla rete Z-Wave.

**Ripristino delle impostazioni di fabbrica**

-   -   Il ripristino delle impostazioni di fabbrica del dispositivo lo ripristinerà alle impostazioni predefinite di fabbrica (ovvero non incluso in alcuna rete Z-Wave). Utilizzare questa procedura solo se il gateway Z-Wave o il pannello di controllo vengono persi o risultano comunque inutilizzabili.
    -   Tieni premuto il pulsante funzione del dispositivo per 10 secondi per ripristinare le impostazioni di fabbrica.
-   _**Prova di portata**_

![](<.gitbook/assets/7 (45).png>)

Per verificare se il dispositivo è in grado di comunicare con il gateway Z-Wave o la centrale di controllo:

-   Mettere il gateway/pannello in modalità test di portata (Walk Test).
-   Premere il pulsante funzione sul dispositivo
-   Il gateway/pannello dovrebbe essere visualizzato se il dispositivo si trova all'interno del raggio d'azione (fare riferimento al manuale operativo del gateway/pannello).

2

**Operazione**

![](<.gitbook/assets/8 (40).jpeg>)

-   _**Controllo relè**_
    -   Dopo che l'interruttore a levetta del relè è stato aggiunto con successo a una rete Z-Wave, il gateway/pannello di controllo può controllare in remoto il relè per accenderlo, spegnerlo o alternare tra le condizioni On e Off. Per i dettagli fare riferimento al gateway/pannello di controllo Z-Wave.

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

![](<.gitbook/assets/9 (41).png>)

-   _**Gruppi di Z-Wave (Associazione Command Class Versione 2)**_

Lo Switch può essere impostato per inviare report ai dispositivi Z-Wave associati. Supporta un gruppo di associazione con supporto di cinque nodi per il Raggruppamento 1. Per il Raggruppamento 1, lo Switch segnalerà il suo stato più recente al Gateway/Pannello Z-Wave.

Gruppo 1 per “LifeLine”:

Commutatore binario CC (SWITCH_BINARIO_RAPPORTO)

Ripristina dispositivo localmente CC (COMMAND_CLASSE_DISPOSITIVO_RIPRISTINA_LOCALMENTE)

-   Segnalazione automatica al Raggruppamento 1 (nodo massimo 5)
-   Rapporto eventi on/off

Quando si alterna tra On/Off, invierà il report di cambio binario ai nodi del Raggruppamento 1.

3
