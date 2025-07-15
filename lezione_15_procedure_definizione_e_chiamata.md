# Procedure: definizione e chiamata

Le procedure sono un concetto fondamentale nella programmazione strutturata e procedurale. Esse permettono di definire un blocco di istruzioni che può essere chiamato e eseguito in modo autonomo all'interno di un programma. Le procedure sono utili per suddividere il codice in blocchi logici e riutilizzabili, facilitando la manutenzione e la comprensione del codice.

## Definizione di una procedura

Per definire una procedura, è necessario specificare il nome della procedura e l'elenco dei parametri di input che essa accetta. Ad esempio, la seguente procedura `StampaMessaggio` non accetta alcun parametro e stampa a schermo il messaggio "Hello, world!":

```markdown
```
```
procedure StampaMessaggio() {
    print("Hello, world!");
}
```
```

## Chiamata di una procedura

Una procedura viene chiamata all'interno del codice principale utilizzando il suo nome seguito da eventuali parametri di input tra parentesi tonde. Ad esempio, per chiamare la procedura `StampaMessaggio` definita in precedenza, è sufficiente scrivere:

```markdown
```
```
StampaMessaggio();
```
```

## Esempio completo

Di seguito è riportato un esempio completo di utilizzo di procedure in un programma:

```markdown
```
```
procedure StampaMessaggio() {
    print("Hello, world!");
}

procedure CalcolaSomma(numero1, numero2) {
    somma = numero1 + numero2;
    print("La somma è: " + somma);
}

StampaMessaggio();
CalcolaSomma(5, 3);
```
```

In questo esempio, vengono definiti due procedure: `StampaMessaggio` e `CalcolaSomma`. La prima stampa a schermo il messaggio "Hello, world!", mentre la seconda calcola e stampa la somma di due numeri. Infine, le due procedure vengono chiamate nel codice principale.

Le procedure sono uno strumento potente per organizzare e strutturare il codice in modo modulare e riutilizzabile. Utilizzale con saggezza per semplificare la complessità dei tuoi programmi e migliorarne la manutenibilità.