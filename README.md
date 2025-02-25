# Esercizio: FizzBuzz

### Sviluppo di un programma che stampi i numeri da 1 a 100 tenendo conto che:
 - Per i multipli di 3 viene stampato 'fizz' anzichè il numero;
 - Per i multipli di 5 viene stampato 'Buzz' anzichè il numero;
 - Per i numeri che sono sia multipli di 3 che multipli di 5 viene stampato 'FizzBuzz' anzichè il numero;

 ## Svogimento:

- Creazione di un ciclo for:
  - creazione di una variabile (i);
  - FINO A CHE "i" è maggiore o uguale a 100, il programma stamperà incrementando di una sola uinità;
    - SE il la variabile "i":
       - contiene un numero multiplo di 3 AND multiplo di 5: mando in stampa la stringa 'FizzBuzz';
    - ALTRIMENTI SE il contenuto è multiplo di 3 mando in stampa 'Fizz';
    - ALTRIMENTI SE il contenuto è multiplo di 5 mando in stampa 'Buzz';
    - SE il contenuto di "ì" non è nè multiplo di 3, nè multiplo di 5, mando in stampa il suo valore numerico;