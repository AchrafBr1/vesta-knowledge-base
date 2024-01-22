# VESTA 140

**Controller relè Z-Wave PRL-8-ZW-AC**

**introduzione**

PRL-8-ZW-AC è un controller relè Z-Wave che può essere collegato a dispositivi cablati e impostato sullo stato Normalmente aperto (N.O.) o Normalmente chiuso (N.C.). Dopo aver aderito alla rete Z-Wave, il controller relè può essere controllato tramite la rete Z-Wave per attivare i dispositivi collegati. Z-Wave è un protocollo di comunicazione wireless che utilizza una radio RF a bassa potenza. Il controller Z-Wave Relay consente l'accesso alla classe "S2 Unauthenticated".

**Identificazione delle parti**

**1. Pulsante funzione**

![](<.gitbook/assets/0 (53).jpeg>)

Premere il pulsante 3 volte entro 1,5 secondi per inviare un codice di apprendimento.

Tieni premuto il pulsante per 10 secondi per ripristinare le impostazioni di fabbrica.

Premere il pulsante per accendere/spegnere il relè.

**2. Indicatore LED (rosso)**

L'indicatore LED viene utilizzato per indicare lo stato del relè:

-   LED acceso: relè acceso
-   LED spento: relè spento

**Terminali di connessione**

Collegare il filo al terminale, stringere la vite per chiudere il clipper e tenere il filo in posizione. Svitare per aprire il clipper per rimuovere il filo collegato al terminale.

1.  **Linea (ingresso CA)**
2.  **Neutro**
3.  **NO**

Per la connessione Normal Open con il dispositivo.

1.  **Comune**
2.  **NC**

Per la connessione Normal Close con il dispositivo

**8. Morsetto pressacavo**

Il morsetto viene utilizzato per fissare i cavi e fornire un pressacavo per proteggere i cavi dal ritaglio metallico.

**9. Fibbia di cablaggio**

La fibbia di cablaggio viene utilizzata per la gestione dei cavi.

**Specifica**

-   Fonte di alimentazione (alimentazione esterna): 100-240 V CA
-   Uscita relè: relè SPDT senza potenziale, carico operativo massimo: 10 A (resistivo) a 24 V CC o 240 V CA
-   Filo intrecciato: 14~22 AWG
-   Temperatura operativa: da -10°C a 45°C (da 14°F a 113°F)
-   Umidità: fino all'85% senza condensa
-   Dimensioni: 86 mm x 72 mm x 29 mm

![](<.gitbook/assets/1 (45).jpeg>)

**Ambiente di installazione**

-   Il controller relè deve essere installato all'interno in un luogo asciutto.

1

-   Si consiglia di installare l'apparecchio in una scatola di plastica ignifuga.
-   Non installare il dispositivo in una scatola metallica per ottimizzare la portata Z-Wave.

![](<.gitbook/assets/2 (41).jpeg>)

**Attenzione**

-   Tutti gli interventi sul dispositivo, comprese l'installazione e la manutenzione, devono essere eseguiti da un elettricista qualificato e autorizzato.
-   Per evitare scosse elettriche e/o danni all'apparecchiatura, scollegare l'alimentazione elettrica dal fusibile principale o dall'interruttore prima dell'installazione e della manutenzione.

Non collegare il dispositivo a carichi che superano la corrente di carico supportata.

**Installazione**

![](<.gitbook/assets/3 (38).jpeg>)

Il cablaggio del PRL deve essere eseguito solo da un tecnico certificato con conoscenza e formazione adeguate sulle apparecchiature elettriche. Cablare il relè secondo le istruzioni seguenti:

1.  Spegnere l'alimentazione prima del collegamento.
2.  Rimuovere il coperchio superiore e rimuovere il morsetto del pressacavo.
3.  Collegare i terminali L e N dell'alimentatore rispettivamente ai terminali Linea e Neutro di PRL attraverso il foro di cablaggio.
4.  A seconda del dispositivo che si desidera controllare tramite il relè, selezionare il terminale NO o NC e collegare il relè al dispositivo per stabilire una connessione Normalmente aperta o Normalmente chiusa con il dispositivo.
5.  Dopo aver completato il cablaggio del dispositivo, sostituire il morsetto antistrappo, utilizzare

la fibbia di cablaggio per gestire i fili e posizionare la fibbia di cablaggio sulla base con la sua fessura (apertura) posizionata a sinistra (come nello schema seguente).

![](<.gitbook/assets/4 (39).jpeg>)

1.  Sostituire il coperchio superiore. Accendere l'alimentatore per accendere il controller relè.

**Rete Z-Wave**

![](<.gitbook/assets/5 (51).png>)

-   _**Aggiunta di dispositivi (inclusione)**_
    -   Collegare l'alimentazione al controller relè secondo le istruzioni di installazione nella sezione precedente e accendere il controller relè.
    -   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di inclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
    -   Entro 1,5 secondi, premere il pulsante funzione 3 volte.
    -   Fare riferimento al manuale operativo del gateway Z-Wave o del pannello di controllo per completare il processo di aggiunta.
    -   Se il dispositivo è già stato aggiunto (incluso) in un altro gateway/pannello di controllo Z-Wave, o se non è possibile aggiungere il dispositivo all'attuale gateway/pannello di controllo Z-Wave, provare prima a rimuoverlo (vedere_**Rimozione del dispositivo**_).
-   _**Rimozione del dispositivo (esclusione)**_

![](<.gitbook/assets/6 (33).png>)

Il dispositivo deve essere rimosso dalla rete Z-Wave esistente prima di essere aggiunto a un'altra.**Modalità di esclusione**

-   Inserisci il gateway Z-Wave o il pannello di controllo**Modalità di esclusione**(fare riferimento al manuale del gateway Z-Wave o del pannello di controllo).
-   Entro 1,5 secondi, premere il pulsante funzione 3 volte e il dispositivo verrà rimosso dalla rete Z-Wave.

**Ripristino delle impostazioni di fabbrica**

2

-   -   Il ripristino delle impostazioni di fabbrica del dispositivo lo ripristinerà alle impostazioni predefinite di fabbrica (ovvero non incluso in alcuna rete Z-Wave). Utilizzare questa procedura solo se il gateway Z-Wave o il pannello di controllo vengono persi o risultano comunque inutilizzabili.
    -   Tieni premuto il pulsante funzione del dispositivo per 10 secondi per ripristinare le impostazioni di fabbrica.
-   _**Prova di portata**_

![](<.gitbook/assets/7 (28).png>)

Per verificare se il dispositivo è in grado di comunicare con il gateway Z-Wave o la centrale di controllo:

-   Mettere il gateway/pannello in modalità test di portata (Walk Test).
-   Premere il pulsante funzione sul dispositivo.
-   Il gateway/pannello dovrebbe essere visualizzato se il dispositivo si trova all'interno del raggio d'azione (fare riferimento al manuale operativo del gateway/pannello).

**Operazione**

![](<.gitbook/assets/8 (23).jpeg>)

-   _**Controllo relè**_
    -   Quando il controller relè si è unito con successo a una rete Z-Wave, il gateway/pannello di controllo sarà in grado di controllare in remoto il relè per accenderlo, spegnerlo o alternare tra le condizioni On e Off. Per i dettagli fare riferimento al gateway/pannello di controllo Z-Wave.

**Informazioni sull'onda Z**

**Tipo di dispositivo:**Interruttore di accensione/spegnimento

**Tipo di ruolo:**Sempre attivo come schiavo (AOS)

**Supporto/controllo della classe di comando**

**Supporto CC obbligatorio:**Z-Wave Plus Informazioni CC

Associazione CC, (S2)

Associazione multicanale CC, (S2)

Informazioni sul gruppo di associazione CC, (S2)

Servizio Trasporti CC

Versione CC, (S2)

CC specifico del produttore, (S2)

Reset del dispositivo localmente CC, (S2)

Livello di potenza CC, (S2)

Cambia CC binario

Supervisione CC, (S2)

Aggiornamento firmware Md CC, (S2)

-   _**Gruppi di Z-Wave (Associazione Command Class Versione 2)**_

The Switch can be set to send reports to associated Z-Wave devices. It supports one association group with five node support for Grouping 1. For grouping 1, the Switch will report its latest status to Z-Wave Gateway/Panel.

Raggruppamento 1 per “LifeLine”: (nodi max: 5)

Cambia CC binario (COMMAND_CLASSE_INTERRUTTORE_BINARIO)

Ripristina dispositivo localmente CC (COMMAND_CLASSE_DISPOSITIVO_RIPRISTINA_LOCALMENTE)

Quando si alterna tra On/Off, invierà il report di cambio binario ai nodi del Raggruppamento 1.

3
