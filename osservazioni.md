# Osservazioni — Esercitazione 0

Gruppo: Davide Ferretti, Marco Petese

Componenti (nome, cognome e username GitHub di entrambi):Davide Ferretti Arr0sto, Marco Petese MPetese

URL del repository condiviso: https://github.com/MPetese/esercitazione-0-template

Chi ha usato la tastiera nello step 1 e nello step 2: 1-Marco Petese, 2-Davide Ferretti

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione: make

Comando di esecuzione e risultato osservato: ./hello il programma stampa a schermo il messaggio richiesto

Che cosa ho capito su sorgente ed eseguibile: Il sorgente si può modificare, l'eseguibile no.

Output richiesto e comportamento del programma prima della modifica: Hello, computational physics! questo è l'output, all'inizio il codice non fa niente

Esito dopo la modifica e spiegazione della correzione: inserimento funzione printf() per stampare su schermo.

## Step 1 — Git

Quali file ho incluso nel commit e perché: hello.c e osservazioni.md perchè sono stati entrambi modificati 

Come ho verificato che la versione provata sia presente su GitHub: abbiamo aperto il file su github

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone: git clone scarica e copia tutto il contenuto della repository mentre pull solo le modifiche

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato: abbiamo passato:"./eco "super testo" 43 2.71828" risultato:"super testo 43 2.718280" 

Che cosa posso concludere: il programma stampa su schermo gli argomenti inseriti in formato corretto !

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato: abbiamo passato:"./eco2 testo 2 3.14159" risultato:"testo 2 3.141590" 

Che cosa ho capito su testo, conversioni e stampa: abbiamo capito come passare dati convertendoli da stringa a un tipo di variabile conveniente

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`: in eco.c da 0 perché non è può convertire la stringa in eco2 da un messaggio di errore, per come la funzione leggi_intero è strutturata

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati: eco.txt contiene l'output di ./eco. Usando eco:
"
0
ciao 12 3.500000
0
ciao 0 3.500000
"
Usando eco2 invece:
"
0
ciao 12 3.500000
Il secondo argomento deve essere un intero in base 10.
2
"

Come un controllo automatico può riconoscere un errore: come in eco2.c si controlla che l'ultimo carattere non sia quello di fine stringa "\0"

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti: serve ricompilare nel caso ci sia un errore nella scrittura del programma o per modificare l'algoritmo. Se si vogliono cambiare solamente i parametri basta cambiare gli argomenti

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step: usando il comando "git log" e leggendo l'output del comando

Come ho verificato che la versione finale sia presente su GitHub: vado sul sito e controllo
