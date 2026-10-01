# Osservazioni — Esercitazione 0

Gruppo:	       Filippo Di noia	filodinoia
	       Matteo Gigante	Matteo-gigantE

Componenti (nome, cognome e username GitHub di entrambi):

URL del repository condiviso:

Chi ha usato la tastiera nello step 1 e nello step 2:Entrambi

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione:

	gcc -std=c17 -Wall -Wextra -Wpedantic hello.c -o hello

Comando di esecuzione e risultato osservato:

	./hello

	non succede nulla, il programma ritorna l'int 0
	
Che cosa ho capito su sorgente ed eseguibile:

    	 il file hello.c è il file sorgente contenente il codice del programma, l'eseguibile hello
	 è invece generato dal compilatore in linguaggio macchina per l'esecuzione

Output richiesto e comportamento del programma prima della modifica:

       L'output non c'è stato ed è come aspettato in quanto il programma consisteva solo nel ritornare un intero. se si intende il todo come risultato atteso allora l'output era assente ed errato

Esito dopo la modifica e spiegazione della correzione:

      La correzione è consistita nell'aggiungere la linea

      printf("Hello, computational physics!\n");

## Step 1 — Git

Quali file ho incluso nel commit e perché: Nel commit sono stati inclusi (con git add) il file hello.c sorgente e il file osserv azioni.md in quanto sono stati gli unici modificati


Come ho verificato che la versione provata sia presente su GitHub:

     con git diff si sono controllate le differenze tra la versione remota originale e quella locale aggiornata, dopo il push le differenze non erano presenti

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone:
 non serve un nuovo clune dopo il pull in quanto la versione pullata sarebbe stata la stessa di quella gia presente, cosa detta pure da output del comando

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato:

Che cosa posso concludere:

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato:

Che cosa ho capito su testo, conversioni e stampa:

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`:

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati:

Come un controllo automatico può riconoscere un errore:

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti:

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step:

Come ho verificato che la versione finale sia presente su GitHub:
