# File: gestione di file sequenziali

Nel mondo dell'informatica, la gestione dei file sequenziali è un'operazione fondamentale per la lettura e la scrittura di dati su file di testo. Questo tipo di file memorizza i dati in modo sequenziale, cioè uno dietro l'altro, senza la possibilità di accedervi in modo casuale come avviene nei file di tipo binario.

## Lettura su file sequenziali

Per leggere dati da un file sequenziale, è necessario aprire il file in modalità lettura e leggere i dati uno alla volta fino alla fine del file. Questo processo può essere eseguito utilizzando un ciclo while che legge i dati dal file finché non raggiunge la fine del file.

```python
with open('file.txt', 'r') as file:
    line = file.readline()
    while line:
        print(line)
        line = file.readline()
```

## Scrittura su file sequenziali

Per scrivere dati su un file sequenziale, è necessario aprire il file in modalità scrittura e scrivere i dati uno alla volta. È importante tenere presente che la scrittura su un file sequenziale sovrascrive i dati esistenti nel file, quindi è necessario prestare attenzione per non perdere informazioni importanti.

```python
with open('file.txt', 'w') as file:
    file.write('Primo dato\n')
    file.write('Secondo dato\n')
    file.write('Terzo dato\n')
```

## Conclusioni

La gestione di file sequenziali è un'operazione essenziale per leggere e scrivere dati su file di testo in modo sequenziale. È importante prestare attenzione alla corretta apertura e chiusura dei file, per evitare problemi di perdita di dati o corruzione dei file. Con le giuste conoscenze e attenzioni, la gestione di file sequenziali può essere eseguita in modo efficace e sicuro.