# Array monodimensionali

Gli array monodimensionali sono una struttura di dati fondamentale nella programmazione, utilizzata per memorizzare una serie di elementi dello stesso tipo all'interno di una singola variabile. In questo articolo approfondiremo la dichiarazione, l'inizializzazione e l'accesso agli elementi degli array monodimensionali.

## Dichiarazione degli array monodimensionali

La dichiarazione di un array monodimensionale avviene specificando il tipo degli elementi che lo compongono e la sua dimensione. Ad esempio, per dichiarare un array di interi di lunghezza 5 si utilizza la seguente sintassi:

```java
int[] numeri = new int[5];
```

In questo caso, `numeri` è il nome dell'array e `new int[5]` indica che l'array può contenere 5 elementi di tipo intero.

## Inizializzazione degli array monodimensionali

Gli array monodimensionali possono essere inizializzati durante la dichiarazione o successivamente. Per inizializzare un array di interi con valori predefiniti, si può utilizzare la seguente sintassi:

```java
int[] numeri = {1, 2, 3, 4, 5};
```

In questo modo, l'array `numeri` conterrà i valori 1, 2, 3, 4 e 5.

## Accesso agli elementi degli array monodimensionali

Per accedere agli elementi di un array monodimensionale si utilizza l'indice dell'elemento desiderato all'interno delle parentesi quadre. Gli indici degli array iniziano da 0. Ad esempio, per accedere al terzo elemento dell'array `numeri`, si utilizza la seguente sintassi:

```java
int terzoElemento = numeri[2];
```

In questo caso, `terzoElemento` conterrà il valore 3, poiché gli indici partono da 0 e il terzo elemento dell'array ha indice 2.

In conclusione, gli array monodimensionali sono una struttura di dati essenziale nella programmazione, utilizzata per memorizzare una sequenza di elementi dello stesso tipo. La corretta dichiarazione, inizializzazione e accesso agli elementi degli array monodimensionali sono fondamentali per gestire in modo efficace i dati all'interno di un programma.