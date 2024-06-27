Ciao ragazzi, Esercizio di oggi: FizzBuzz
nome repo: js-fizzbuzz
Consegna:
Scrivi un programma che stampi in console i numeri da 1 a 100, ma che per i multipli di 3 stampi “Fizz” al posto del numero e per i multipli di 5 stampi “Buzz”. Per i numeri che sono sia multipli di 3 che di 5 stampi “FizzBuzz”.
Prima di partire a scrivere codice poniamoci qualche domanda:
Come faccio a sapere se un numero è divisibile per un altro? Abbiamo visto qualcosa di particolare che possiamo usare?
Consigli del giorno:
Scriviamo sempre prima dei commenti in italiano per capire cosa vogliamo fare
Proviamo ad immaginare le operazioni che vogliamo far svolgere al nostro programma così come lo faremmo "a mano"
Numero minimo di push: 5 (solo parte obbligatoria)
BONUS 1: Crea un container nel DOM , aggiungendo (attraverso la funzione append()) un elemento html con il numero o la stringa corretta da mostrare.
BONUS 2: Applica stili differenti agli elementi aggiunti al DOM nel BONUS 1, a seconda che il valore inserito sia un numero, un fizz, un buzz o un fizzbuzz. Se sei a corto di idee per lo stile, potresti prendere spunto dallo screenshot fornito in consegna.
Buon lavoro e buon divertimento!

soluzione

problema 1 "scrivi un programma in console che stampi i numeri da 1 a 100"
1.creo un ciclo for in cui imposto al contatore una variabile "i" e le assegno il valore 1
2.applico una condizione per far si che il ciclo continui fino a che il contatore sia minore o uguale a 100
3.applico un incremento del contatore di +1 per ogni volta che il ciclo finisce

problema 2 "per i multipli di 3 stampa "Fizz""
1.applico una condizione se per verificare i numeri divisibili per 3
2.se la condizione è vera, allora verra mostrato "Fizz" nella console

problema 3 "per i multipli di 5 stampa "Buzz""
1.applico una condizione se per verificare i numeri divisibili per 5
2.se la condizione è vera, allora verra mostrato "Buzz" nella console

problema 4 "per i numeri che sono sia multipli di 3 che di 5 stampi “FizzBuzz”
1.applico una condizione se, in cui andrò a mettere a confronto le due condizioni precedenti tramite l'operatore logico and
2.se la condizione è vera, allora verrà motrato "FizzBuzz"