# VESTA 387

**Modulo di alimentazione ausiliario (PWB-1-BUS)**

**introduzione**

Il PWB-1-BUS è un modulo di alimentazione ausiliario che può essere collegato al sistema BUS dati per fornire un'alimentazione massima di 13,5 V, 5 A ai dispositivi BUS collegati. Il modulo PWB-1-BUS è supervisionato e comunica alla centrale tutte le modifiche di stato, incluso lo stato dell'alimentazione CA, il livello della batteria, lo stato di manomissione e i dati sul consumo energetico.

**Identificazione delle parti**

![](<.gitbook/assets/0 (4).jpeg>)

1.  **Morsetti di connessione BUS al dispositivo BUS alimentato**(4 fili: V, G, A, B)
2.  **Morsetti di connessione BUS al dispositivo BUS alimentato**(4 fili: V, G, A, B)
3.  **Morsetti di collegamento BUS alla centrale ibrida**(3 fili: G, A, B)
4.  **Interruttore della batteria**

Far scorrere l'interruttore della batteria in posizione ON, in modo che la batteria di backup venga caricata quando l'alimentazione CA è collegata e serva come fonte di alimentazione di backup quando manca l'alimentazione CA.

1.  **Terminale della batteria**

Si collega alla batteria di backup (una batteria al piombo sigillata da 12 V 7,0 Ah o 12 V 17,2 Ah)

1.  **Fori di montaggio**
2.  **Terminale di alimentazione**

Si collega all'alimentatore 20Vac 50Hz/60Hz, 4A (80VA).

1.  **Interruttore ponticello resistenza terminale (J3)**

Quando il modulo di alimentazione è collegato alla linea BUS come dispositivo BUS più lontano dal pannello ibrido, impostare entrambi i ponticelli della resistenza terminale del modulo di alimentazione e del pannello ibrido su ON. Verrà potenziata la capacità di comunicazione della linea BUS.

-   -   Il ponticello della resistenza terminale di PWB-1-BUS viene solitamente utilizzato quando il modulo di alimentazione viene collegato per la prima volta al pannello ibrido senza che siano collegati dispositivi BUS alimentati.

È possibile impostare il ponticello della resistenza terminale del modulo di alimentazione e il ponticello della resistenza terminale del pannello ibrido su ON per verificare se PWB-1-BUS può comunicare bene con il pannello.

Se la comunicazione con la centrale è stata testata correttamente, è possibile iniziare a collegare il PWB-1-BUS ai dispositivi alimentati. Quindi impostare il ponticello della resistenza terminale del modulo di alimentazione su Off e impostare invece il ponticello della resistenza terminale del dispositivo più lontano nella linea BUS su ON.

![](<.gitbook/assets/1 (6).jpeg>)

Se il ponticello è disattivato (il collegamento del ponticello è rimosso o “parcheggiato” su un pin), la capacità di comunicazione è a livello normale.

![](<.gitbook/assets/2 (5).jpeg>)

Se il ponticello è su ON (il collegamento del ponticello poggia su entrambi i pin), la capacità di comunicazione risulta migliorata.

1

1.  **Indicatore LED**
2.  **Terminale dell'interruttore antimanomissione**Si collega all'interruttore antimanomissione del coperchio.

**Accessori**

1.  Situazione di stallo\*4
2.  Dado di stallo\*4
3.  Cavo batteria 12V 7.0Ah\*2 (+, -)

**Alimentazione elettrica**

**Fonte di potere:**

-   Il PWB-1-BUS è collegato all'alimentatore 20Vac 50Hz/60Hz, 4A (80VA).
-   Quando l'alimentazione viene interrotta e ripristinata, PWB-1-BUS trasmetterà rispettivamente il segnale di guasto CA e di ripristino.

**Batteria ricaricabile:**

-   È possibile collegare una batteria al piombo sigillata da 12 V 7,0 Ah o 12 V 17,2 Ah per fungere da backup in caso di interruzione di corrente.
-   Durante il normale funzionamento, l'alimentazione CA viene utilizzata per alimentare PWB-1-BUS e allo stesso tempo ricaricare la batteria. Sono necessarie circa 48 ore per caricare completamente una batteria da 12 V 7,0 Ah e 72 ore per caricare completamente una batteria da 12 V 17,2 Ah.
-   Se l'interruttore della batteria è impostato su OFF, la batteria non verrà caricata quando l'alimentazione CA è collegata e non fungerà nemmeno da fonte di alimentazione di riserva quando manca l'alimentazione CA. È necessario cambiare la batteria su**SU**per caricarlo quando è collegata l'alimentazione CA e fungere da fonte di alimentazione di riserva quando manca l'alimentazione CA.
-   Quando la batteria è scarica, PWB-1-BUS trasmetterà il segnale di batteria scarica. Quando la batteria è stata caricata, PWB-1-BUS trasmetterà il segnale di ripristino della batteria.
-   Quando la batteria è scollegata, l'interruttore della batteria è spento o viene rilevato un guasto della batteria, PWB-1-BUS segnalerà la batteria mancante/esaurita al pannello di controllo.

**Potenza in uscita:**

-   PWB-1-BUS può fornire un'alimentazione massima di 13,5 V, 5 A ai dispositivi BUS collegati.

**Protezione antisabotaggio**

-   L'interruttore antimanomissione per la porta dell'armadio è in posizione normale quando la porta è chiusa. La violazione della manomissione avviene quando viene aperta la porta in cui viene rilasciato l'interruttore antimanomissione (Tamper Open). Un segnale di manomissione aperta verrà segnalato alla Centrale di Controllo.

**Collegamento a Centrali e dispositivi BUS**

**ATTENZIONE:**

**Rimuovere tutta l'alimentazione (CA e batteria) prima di effettuare qualsiasi collegamento. Il cablaggio del sistema di allarme deve essere eseguito solo da un tecnico certificato con conoscenza e formazione adeguate sulle apparecchiature elettriche.**

-   Per facilitare i collegamenti dei cavi, le morsettiere su ciascun modulo del sistema BUS sono codificate a colori.

**Codici colore della morsettiera**

| **Rosso**  | VDD  |
| ---------- | ---- |
| **Nero**   | GND  |
| **Giallo** | 485A |
| **Verde**  | 485B |

-   Quando si collega il PWB-1-BUS alla centrale ibrida, collegare solo i tre terminali (GND, 485A, 485B). Si prega di fare riferimento all'immagine qui sotto.
-   Quando si collega il PWB-1-BUS ai dispositivi alimentati dal modulo di alimentazione, collegare 4 terminali. (VDD, GND, 485A, 485B).

Fare riferimento agli esempi di collegamento del dispositivo BUS (VST-892-BUS e DC-23-BUS) di seguito.

2

![](<.gitbook/assets/3 (5).jpeg>)

_\\<NOTE>_

-   Il design innestabile delle morsettiere BUS migliora l'efficienza dell'installazione. Prima del cablaggio, è possibile rimuovere le morsettiere dal dispositivo per facilità d'uso e ricollegarle dopo il cablaggio.

Quando si reinstallano le morsettiere sulla scheda, assicurarsi di installarle nella stessa direzione per evitare potenziali pericoli.

-   Collegamenti errati causeranno guasti o un funzionamento improprio. Ispezionare il cablaggio e verificare che i collegamenti siano corretti prima di applicare l'alimentazione.

**Iniziare**

Dopo aver collegato il modulo di alimentazione ausiliaria al pannello ibrido (fare riferimento a_**Collegamento a Centrali e dispositivi BUS**_sezione per i dettagli), procedere all'apprendimento.

-   _**Apprendimento**_

**Passo 1.**Dopo aver collegato il PWB-1-BUS alla centrale ibrida, accendere la centrale.

**Passo 2.**Nella pagina web del Pannello di controllo, fare clic su "**Apprendimento**" per accedere alla pagina di apprendimento.

**Passaggio 3.**Clicca su "**Inizio**" per accedere alla modalità di apprendimento.

**Passaggio 4.**Clic**"Aggiungere"**per includere il modulo di alimentazione ausiliaria nel pannello.

**Passaggio 5.**Se il modulo di alimentazione ausiliaria viene appreso con successo nel sistema, il dispositivo aggiunto verrà visualizzato nella sezione “Dispositivo appreso”. Il tipo di dispositivo verrà visualizzato come "PWB".

-   _**Identificazione**_

IL "**Identificare**La funzione ” permette di localizzare uno specifico dispositivo BUS nell'impianto BUS cablato. Questa funzione è utile per distinguere di quale dispositivo si tratta soprattutto in un impianto di grandi dimensioni in cui sono presenti numerosi dispositivi BUS.

Per individuare PWB-1-BUS nel sistema BUS:

![](<.gitbook/assets/4 (4).png>)

**Passo 1.**Nella pagina Web del pannello ibrido, fare clic su "Identifica" nell'elenco dei dispositivi dopo la voce della colonna del dispositivo di PWB.

**Passo 2.**Se PWB-1-BUS riceve il segnale dalla centrale ibrida, la pagina web visualizzerà un messaggio di successo e l'indicatore LED di PWB-1-BUS lampeggerà 10 volte per indicare all'utente dove si trova.

_\\<NOTE>_

-   Se sulla pagina web viene visualizzato un messaggio di timeout, significa che il PWB-1-BUS non ha ricevuto il segnale dalla centrale.

3

Verificare se PWB-1-BUS è collegato correttamente al pannello entro una distanza di cablaggio adeguata.

**Segnale di vigilanza**

-   Dopo essere stato appreso nel pannello di controllo, il modulo di alimentazione trasmetterà automaticamente i segnali di supervisione ogni 20-30 secondi.

**Monitoraggio del consumo energetico**

-   Dopo essere stato appreso nella centrale, il modulo alimentatore trasmetterà automaticamente i dati sul consumo energetico, inclusi il livello della batteria, la tensione e la corrente del BUS alla centrale ogni 30-50 minuti.

![](<.gitbook/assets/5 (7).png>)





Quando il livello della batteria è inferiore o uguale al 20%, verrà inviato al pannello un segnale di batteria scarica.

Quando il livello della batteria è allo 0%, indica una delle seguenti situazioni: batteria scollegata, interruttore della batteria in posizione off o guasto della batteria.

L'utente può anche interrogare manualmente i dati sul consumo energetico**Modifica dispositivo**pagina.

![](<.gitbook/assets/6 (5).png>)

**Montaggio del PWB-1-BUS nell'armadio (AWO300)**

-   Individuare il**posizioni di stallo sull'armadio AWO300**(○1 – A, B, C, D) e il**fori di montaggio sul PWB-1-BUS**(○2 – A, B, C, D).

![](<.gitbook/assets/7 (6).png>)

4

-   Utilizzare i distanziatori forniti per montare in modo sicuro il PWB-1-BUS nel contenitore.

![](<.gitbook/assets/8 (6).png>)

-   Una volta completato tutto il cablaggio, installare la batteria di riserva. Le opzioni della batteria includono: Una batteria al piombo sigillata da 12 V 7,0 Ah o 12 V 17,2 Ah.

Per installare la batteria, attenersi alla procedura seguente:

-   1.  Collegare il cavo GND (nero) al polo negativo (-) della batteria.
    2.  Collegare il cavo di alimentazione (Rosso) al polo positivo (+) della batteria
    3.  Fissare la batteria di backup alla custodia.
-   Collegare l'interruttore antimanomissione dello sportello dell'armadio al terminale antimanomissione.
-   Collegare il terminale di alimentazione all'alimentatore 20Vac 50Hz/60Hz, 4A (80VA). Far scorrere l'interruttore della batteria su ON.

![](<.gitbook/assets/9 (7).png>)

5
