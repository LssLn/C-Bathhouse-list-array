Sviluppo di applicazione in ANSI C per gestire i clienti di uno
stabilimento balneare.
Su un archivio (allegato all'attività 'clienti.txt') è memorizzato
l'elenco dei clienti di uno stabilimento balneare con 100 cabine. Ogni
cliente firma un contratto che gli consente l'utilizzo esclusivo di
una cabina e l'ingresso allo stabilimento ad un numero di persone pari
al numero di tesserini acquistati. Il file contiene in ogni riga, il
codice del cliente, il numero di tesserini ed il numero della cabina
(da 0 a 99).
Implementare le seguenti funzioni:
1. CaricaClienti: carica l'elenco dei clienti in una lista clienti.
2. Ingresso: aggiorna un vettore di liste che in ogni posizione
(corrispondente ad una cabina) contiene la lista delle persone
attualmente in quella cabina.
3. CabineVuote: restituisce un array che contiene i numeri di cabine
vuote (cioè quelle per cui nessun tesserino è stato utilizzato).
