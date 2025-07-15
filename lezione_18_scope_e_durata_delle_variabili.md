# Scope e durata delle variabili

Le variabili sono elementi fondamentali nella programmazione. Esse possono essere locali, globali o statiche e presentano diverse caratteristiche in termini di scope e durata.

## Variabili locali
Le variabili locali sono definite all'interno di una funzione e possono essere utilizzate solo all'interno di quella funzione stessa. Questo significa che il loro scope è limitato al blocco di codice in cui sono dichiarate. Inoltre, la durata di una variabile locale inizia quando la funzione viene chiamata e termina quando la funzione restituisce un valore o termina l'esecuzione.

``` 
void esempioFunzione() {
    int variabileLocale = 10;
    // variabileLocale è visibile solo all'interno di questa funzione
}
```

## Variabili globali
Le variabili globali sono definite al di fuori di qualsiasi funzione e possono essere utilizzate in tutto il programma. Il loro scope si estende a tutti i blocchi di codice e la loro durata è dall'inizio dell'esecuzione del programma fino alla sua terminazione.

```
int variabileGlobale = 20;

void esempioFunzione() {
    // variabileGlobale è visibile anche all'interno di questa funzione
}
```

## Variabili statiche
Le variabili statiche mantengono il loro valore anche dopo che la funzione in cui sono dichiarate ha terminato la sua esecuzione. Hanno scope locale alla funzione in cui sono definite, ma la loro durata è per l'intera durata del programma.

```
void esempioFunzione() {
    static int variabileStatica = 30;
    // variabileStatica mantiene il suo valore tra le chiamate alla funzione
}
```

In conclusione, le variabili locali hanno scope e durata limitati alla funzione in cui sono dichiarate, le variabili globali hanno scope globale e durata per l'intera esecuzione del programma, mentre le variabili statiche hanno scope locale e durata per l'intera esecuzione del programma. È importante comprendere queste differenze per garantire una corretta gestione delle variabili all'interno di un programma.