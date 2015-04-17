# Ese104-AgenziaViaggi

L�agenzia viaggi Rossi & C con sede a Milano vuol gestire le sue 5 filiali dislocate sul territorio italiano.
Le filiali devono essere collegate con la sede per tutte le funzioni di gestione sia dei dati amministrativi che dei pacchetti turistici.
La sede centrale ha soltanto funzioni di gestione e non ha rapporti con la clientela.
Le 5 filiali hanno tutte la stessa configurazione hardware e software.

Ogni filiale dista da ognuna delle altre pi� di 50 Km.
Ogni filiale � dotata di una rete interna ed � collegata alla sede principale.
Il numero di host  per ogni filiale � il seguente:

Numero host	Numero filiale
5	1
10	2
7	3
3	4
14	5

L�organizzazione dell'agenzia deve tener conto della gestione dei clienti e dei pacchetti turistici.

Ogni filiale esporta dal proprio applicativo un file CSV (Comma Separated Values) da integrare in un�unica base di dati, che contiene le informazioni riferite alle diverse  FILIALI, ai loro CLIENTI ed ai PACCHETTI turistici che tali clienti acquistano.

Ogni Filiale deve poter verificare i posti disponibili per i diversi pacchetti ed eventualmente aggiungere nuove prenotazioni; l�Agenzia dovr� poter produrre per ogni pacchetto il totale dei posti disponibili.

1.	Effettuare l�analisi del problema e realizzare i diagrammi UML necessari a consentire ad ogni Filiale di aggiungere una nuova prenotazione quando vi siano posti disponibili per un determinato pacchetto e consentire all�Agenzia di visualizzare per ogni pacchetto il totale dei posti disponibili.

2.	Implementare in Java il codice relativo alla prenotazione e quello relativo alla produzione dell�elenco.

