# Strutture condizionali: if then else

Le strutture condizionali sono uno strumento fondamentale nella programmazione per gestire il flusso di esecuzione del codice in base a determinate condizioni. Tra le strutture condizionali più comuni troviamo l'istruzione if-then-else, che permette di eseguire un blocco di istruzioni se una condizione è vera e un altro blocco se la condizione è falsa.

## Sintassi e funzionamento

La sintassi dell'istruzione if-then-else è la seguente:

```python
if condizione:
    # blocco di istruzioni da eseguire se la condizione è vera
else:
    # blocco di istruzioni da eseguire se la condizione è falsa
```

La condizione può essere qualsiasi espressione che restituisca un valore booleano (True o False). Se la condizione è vera, viene eseguito il blocco di istruzioni dopo il "if"; se è falsa, viene eseguito il blocco di istruzioni dopo l'"else".

## Esempio di utilizzo

Ecco un esempio di utilizzo dell'istruzione if-then-else in Python:

```python
x = 10

if x > 5:
    print("x è maggiore di 5")
else:
    print("x è minore o uguale a 5")
```

Nel caso in cui `x` sia maggiore di 5, verrà stampato a schermo il messaggio "x è maggiore di 5"; altrimenti verrà stampato il messaggio "x è minore o uguale a 5".

## Strutture condizionali nidificate

Le strutture condizionali if-then-else possono essere nidificate, ovvero essere annidate all'interno di altre strutture condizionali. Ad esempio:

```python
x = 10
y = 5

if x > y:
    if x < 20:
        print("x è maggiore di y ma minore di 20")
    else:
        print("x è maggiore di y e maggiore o uguale a 20")
else:
    print("x è minore o uguale a y")
```

In questo caso, vengono valutate due condizioni: se `x` è maggiore di `y` e se `x` è minore di 20. A seconda dei risultati di queste due condizioni, vengono eseguiti diversi blocchi di istruzioni.

Le strutture condizionali if-then-else sono uno strumento potente per gestire il flusso di esecuzione del codice in base a condizioni specifiche e permettono di scrivere codice più flessibile e adattabile alle diverse situazioni.