# VESTA 363

**Estensore di campo isolato BUS (ISL-1-BUS)**

**introduzione**

L'ISL-1-BUS è un range extender isolato. Può estendere il raggio di comunicazione e amplificare il segnale del sistema di sicurezza cablato su lunghe distanze, proteggendo allo stesso tempo i dispositivi collegati dai cortocircuiti a valle. L'isolatore ha separato galvanicamente i terminali di ingresso e di uscita. Nel caso in cui si verifichi un cortocircuito sull'uscita, tutti i dispositivi collegati all'ingresso dell'ISL-1-BUS continueranno a funzionare senza interruzione. L'ISL-1-BUS può anche aumentare la tensione fino a 13,5 V per i dispositivi BUS collegati all'uscita.

**Identificazione delle parti**

![](<.gitbook/assets/0 (5).png>)

1.  **Uscita cablaggio BUS per linee di ingresso**
2.  **Terminale BUS collegabile per ingresso**
3.  **LED per Terminale BUS (Ingresso)**

Il LED si accende quando viene alimentato il terminale di uscita BUS A.

1.  **Ponticello del resistore terminale per l'ingresso del terminale**

![](<.gitbook/assets/1 (5).jpeg>)

Portare il ponticello su OFF rimuovendo o “parcheggiando” il collegamento del ponticello.

![](<.gitbook/assets/2 (4).jpeg>)

Ruotare il ponticello su ON appoggiando il collegamento del ponticello su entrambi i pin.

1.  **LED per Terminale BUS (Uscita A)**

Il LED si accende quando viene alimentato il terminale di uscita BUS A.

1.  **Ponticello resistenza terminale per terminale BUS (Uscita A)**

![](<.gitbook/assets/3 (4).jpeg>)Portare il ponticello su OFF rimuovendo o “parcheggiando” il collegamento del ponticello.

![](<.gitbook/assets/4 (5).jpeg>)

Ruotare il ponticello su ON appoggiando il collegamento del ponticello su entrambi i pin.

1.  **Terminale BUS collegabile per l'uscita A**

Il LED si accende quando viene alimentato il terminale di uscita BUS A.

1.  **Uscita cablaggio BUS per linee di uscita**
2.  **Uscita terminale BUS collegabile B**
3.  **LED per Terminale BUS (Uscita B)**

Il LED si accende quando viene alimentato il morsetto B di uscita del BUS.

1

1.  **Ponticello resistenza terminale per terminale BUS (Uscita B)**

La stessa funzione del ponticello della resistenza terminale per l'uscita terminale A.

_**Notare che:**_

-   _**Dopo aver scollegato i terminali, quando si reinstallano i terminali sulla scheda, assicurarsi di installare i terminali nello stesso orientamento per evitare potenziali pericoli.**_

**Alimentazione elettrica**

L'ISL-1-BUS è alimentato dal BUS del pannello ibrido. Come booster, l'ISL-1-BUS può fornire alimentazione a 13,5 V, 0,5 A su ciascuno dei suoi terminali di uscita A e B.

**Collegamento elettrico**

L'aggiunta dell'ISL-1-BUS al sistema BUS esistente estenderà la portata del BUS e aumenterà la potenza fino a 13,5 V, 0,5 A per ciascuno dei terminali di uscita A e B.

Poiché il terminale di ingresso e i due terminali di uscita indipendenti sono separati galvanicamente, il BUS ISL-1 protegge i dispositivi collegati dai cortocircuiti a valle.

Quando si aggiunge l'ISL-1-BUS al sistema BUS, il BUS verrà suddiviso in 3 segmenti BUS indipendenti (linea BUS 1, linea BUS 2 e linea BUS 3).

-   Come mostrato nello schema seguente, Pannello Ibrido, come primo dispositivo BUS acceso**AUTOBUS linea 1**è collegato all'ingresso ISL-1-BUS, che è il dispositivo più lontano sulla linea BUS 1. Assicurarsi di impostare entrambi i ponticelli della resistenza terminale del pannello ibrido e l'ingresso ISL-1-BUS su ON per fungere da resistenza di terminazione.
-   I due terminali di uscita individuali dell'ISL-1-BUS sono collegati ciascuno a dispositivi BUS separati tramite**AUTOBUS linea 2**E**Autobus linea 3**. Il terminale di uscita A è il primo dispositivo della linea BUS 2; il terminale di uscita B è il primo dispositivo sulla linea BUS 3. Assicurarsi di impostare i ponticelli della resistenza terminale su ON per le due uscite ISL-1-BUS nonché per i dispositivi BUS più lontani all'estremità di ciascuna linea BUS in modo che servano da resistenza di terminazione.
-   Il numero totale di dispositivi BUS (definiti “nodi”; la centrale ibrida viene conteggiata come un nodo) su ciascuna linea BUS deve essere compreso tra 32 o meno. In caso contrario potrebbero verificarsi anomalie sul segnale del BUS. Nell'esempio seguente le linee BUS sono complessivamente 3:**AUTOBUS linea 1**contiene 2 nodi (pannello ibrido e ISL-1-BUS),**AUTOBUS linea 2**contiene 3 nodi (ISL-1-BUS e 2 dispositivi BUS),**Autobus linea 3**ha 3 nodi (ISL-1-BUS e 2 dispositivi BUS).

![](<.gitbook/assets/5 (2).jpeg>)

_**Si prega di notare anche:**_

-   _**Poiché ISL-1-BUS fornisce fino a 0,5 A per ciascuno dei suoi 2 terminali di uscita, si consiglia di collegare i dispositivi BUS al terminale di uscita di ISL-1-BUS uno per uno per garantire un funzionamento ottimale del sistema. Cercare di evitare di collegare tutti i dispositivi al terminale di uscita contemporaneamente.**_
-   _**Dato che la centrale di controllo fornisce alimentazione all'ISL-1-BUS, la distanza massima di cablaggio dalla centrale all'ISL-1-BUS è di 90 metri.**_
-   _**Si consiglia di avere un solo ISL-1-BUS su una singola linea BUS.**_

2
