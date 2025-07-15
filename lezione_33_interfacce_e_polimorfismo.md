# Interfacce e polimorfismo

Le interfacce e il polimorfismo sono concetti fondamentali nella programmazione orientata agli oggetti. In questo articolo approfondiremo la definizione di interfacce e l'uso del polimorfismo in ambito informatico.

## Interfacce

Un'interfaccia in programmazione è un insieme di metodi che una classe deve implementare. Un'interfaccia definisce un contratto, cioè un insieme di regole che una classe deve seguire se implementa quell'interfaccia. Le interfacce permettono di definire un comportamento comune che diverse classi possono condividere.

Le interfacce vengono dichiarate utilizzando la parola chiave `interface` in molti linguaggi di programmazione orientata agli oggetti. Una classe può implementare più di un'interfaccia, permettendo così di definire comportamenti diversi che la classe deve seguire.

Ad esempio, si consideri un'interfaccia `Veicolo` che definisce il metodo `accelera()`. Le classi `Automobile` e `Moto` possono implementare l'interfaccia `Veicolo` e quindi devono fornire un'implementazione del metodo `accelera()`.

```java
interface Veicolo {
    void accelera();
}

class Automobile implements Veicolo {
    public void accelera() {
        // Implementazione del metodo accelera per l'automobile
    }
}

class Moto implements Veicolo {
    public void accelera() {
        // Implementazione del metodo accelera per la moto
    }
}
```

## Polimorfismo

Il polimorfismo è la capacità di un oggetto di essere trattato come se fosse un oggetto di un tipo diverso da quello effettivo. Ci sono due tipi di polimorfismo: il polimorfismo di inclusione e il polimorfismo parametrico.

Il polimorfismo di inclusione si ottiene quando si utilizza un riferimento di tipo superclasse per fare riferimento a un oggetto di una sottoclasse. In questo modo si può trattare l'oggetto come se fosse della superclasse, anche se effettivamente è della sottoclasse.

Il polimorfismo parametrico si ottiene quando si utilizzano i generici per scrivere codice che funziona su diversi tipi di dati senza dover riscrivere il codice per ogni tipo di dato.

Il polimorfismo è uno dei concetti chiave della programmazione orientata agli oggetti ed è ampiamente utilizzato per scrivere codice più flessibile e riutilizzabile.

In conclusione, le interfacce e il polimorfismo sono concetti importanti nella programmazione orientata agli oggetti che permettono di scrivere codice più modulare, flessibile e riutilizzabile. L'uso corretto di interfacce e polimorfismo può migliorare la qualità del codice e rendere più semplice la manutenzione e l'estensione del software.