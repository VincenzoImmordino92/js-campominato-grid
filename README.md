js-campominato-grid
===

## Consegna
L’utente clicca su un bottone che genererà una griglia di gioco quadrata.

Ogni cella ha un numero progressivo, da 1 a 100.
Ci saranno quindi 10 caselle per ognuna delle 10 righe.

Quando l’utente clicca su ogni cella, la cella cliccata si colora di azzurro ed emetto un messaggio in console con il numero della cella cliccata.

## Bonus
Bonus
Aggiungere una select accanto al bottone di generazione, che fornisca una scelta tra tre diversi livelli di difficoltà:
- con difficoltà 1 => 100 caselle, con un numero compreso tra 1 e 100, divise in 10 caselle per 10 righe;
- con difficoltà 2 => 81 caselle, con un numero compreso tra 1 e 81, divise in 9 caselle per 9 righe;
- con difficoltà 3 => 49 caselle, con un numero compreso tra 1 e 49, divise in 7 caselle per 7 righe;

## Ragionamento logico
1. Variabili

2. creo l'evento del click al bottone play

3. creo la funzione play per avviare il gioco all'interno del container

4. creo la mia funzione di reset

5. creo la mia funzione generaGrigliaGioco

6. creo la mia funzione creazioneCelle che mi genera i quadrati

7. creo la funzione al click della mia cella applicando la classe clicked