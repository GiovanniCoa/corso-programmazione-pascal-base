# Funzioni: definizione e chiamata

Le funzioni sono un concetto fondamentale nella programmazione, in quanto permettono di organizzare il codice in blocchi riutilizzabili e modulari. Le funzioni possono avere parametri di input e un valore di ritorno, che restituisce il risultato del calcolo effettuato all'interno della funzione.

## Definizione di una funzione

Per definire una funzione in un linguaggio di programmazione, è necessario specificare il suo nome, i parametri di input e il tipo di dato restituito. Ad esempio, la seguente è la definizione di una funzione che calcola la somma di due numeri interi:

```python
def somma(a, b):
    return a + b
```

Nel codice sopra, la parola chiave `def` indica l'inizio della definizione di una funzione, seguita dal nome della funzione (`somma`), i parametri di input (`a` e `b`) e infine la parola chiave `return` che restituisce il risultato della somma dei due numeri.

## Chiamata di una funzione

Una volta definita una funzione, è possibile chiamarla all'interno del codice per eseguire il calcolo desiderato. Per chiamare la funzione `somma` definita precedentemente, è sufficiente utilizzare il suo nome seguito dai valori dei parametri di input:

```python
risultato = somma(5, 3)
print(risultato)  # Output: 8
```

Nel codice sopra, la funzione `somma` viene chiamata con i valori `5` e `3` come parametri di input, e il risultato della somma viene assegnato alla variabile `risultato`, che successivamente viene stampata a schermo.

## Conclusioni

Le funzioni sono uno strumento potente per organizzare il codice in maniera modulare e riutilizzabile. Definendo una funzione con i parametri di input desiderati e specificando il valore di ritorno, è possibile eseguire calcoli e operazioni complesse in maniera efficiente e strutturata. La chiamata di una funzione permette di eseguire il codice contenuto al suo interno e di ottenere il risultato desiderato.