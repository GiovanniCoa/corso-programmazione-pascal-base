# Cicli: repeat until

Il costrutto di ripetizione `repeat until` è una forma di ciclo che permette di eseguire un blocco di istruzioni ripetutamente fino a quando una certa condizione diventa vera. A differenza dei cicli `while` e `for`, che verificano la condizione all'inizio di ogni iterazione, il ciclo `repeat until` verifica la condizione alla fine di ogni iterazione.

## Struttura del ciclo `repeat until`

La struttura di base del ciclo `repeat until` è la seguente:

```java
repeat {
    // blocco di istruzioni da eseguire
} until (condizione);
```

Il blocco di istruzioni viene eseguito almeno una volta, e poi la condizione viene verificata. Se la condizione è falsa, il blocco di istruzioni viene eseguito di nuovo e la condizione viene verificata nuovamente alla fine di ogni iterazione. Il ciclo continua ad eseguire il blocco di istruzioni fino a quando la condizione diventa vera.

## Esempio di utilizzo del ciclo `repeat until`

Ecco un esempio di come utilizzare il ciclo `repeat until` in un programma:

```java
int contatore = 0;

repeat {
    contatore++;
    System.out.println("Il contatore è: " + contatore);
} until (contatore >= 5);
```

In questo esempio, il blocco di istruzioni incrementa il contatore e stampa il suo valore. Il ciclo continua ad eseguire il blocco di istruzioni fino a quando il contatore diventa maggiore o uguale a 5.

## Conclusioni

Il ciclo `repeat until` è un'utile costrutto di ripetizione che permette di eseguire un blocco di istruzioni fino a quando una certa condizione diventa vera. A differenza dei cicli `while` e `for`, che verificano la condizione all'inizio di ogni iterazione, il ciclo `repeat until` verifica la condizione alla fine di ogni iterazione. Questo lo rende particolarmente adatto per situazioni in cui si vuole garantire che il blocco di istruzioni venga eseguito almeno una volta.