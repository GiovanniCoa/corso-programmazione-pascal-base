# Cicli: while do

Il ciclo *while do* è una forma di iterazione che permette di ripetere un blocco di istruzioni fino a quando una determinata condizione è soddisfatta. Questo tipo di ciclo è detto "pre-test", poiché la condizione viene valutata prima dell'esecuzione del blocco di istruzioni.

## Struttura del ciclo *while do*

La struttura del ciclo *while do* è la seguente:

```bash
while [condizione]
do
    # blocco di istruzioni
done
```

Nel blocco di istruzioni vengono specificate le azioni da ripetere finché la condizione specificata risulta vera. La condizione è un'espressione booleana che può contenere variabili, operatori logici e relazionali.

## Esempio di utilizzo

Ecco un esempio di utilizzo del ciclo *while do* in uno script bash che stampa i numeri da 1 a 10:

```bash
#!/bin/bash

count=1

while [ $count -le 10 ]
do
    echo $count
    count=$(( $count + 1 ))
done
```

In questo script, la variabile `count` viene inizializzata a 1. Il ciclo *while do* viene eseguito finché il valore di `count` è minore o uguale a 10. Ad ogni iterazione, viene stampato il valore di `count` e la variabile viene incrementata di 1.

## Conclusioni

Il ciclo *while do* è un'utile struttura di controllo che permette di eseguire ripetutamente un blocco di istruzioni finché una determinata condizione risulta vera. È importante prestare attenzione alla condizione specificata per evitare cicli infiniti o errori di logica. Utilizzato correttamente, il ciclo *while do* può semplificare la scrittura di script e programmi, migliorando l'efficienza e la leggibilità del codice.