# Ereditarietà

Nel paradigma della programmazione orientata agli oggetti, l'ereditarietà è un concetto fondamentale che permette la creazione di classi derivate che ereditano attributi e metodi da una classe base. Questo meccanismo favorisce il riuso del codice e la creazione di gerarchie di classi, che favoriscono la modularità e la manutenibilità del software.

## Creazione di classi derivate

Per creare una classe derivata da una classe base in linguaggi che supportano l'ereditarietà, come ad esempio Java o C++, è sufficiente utilizzare la parola chiave `extends` seguita dal nome della classe base. Ad esempio, se abbiamo una classe `Veicolo` come classe base e vogliamo creare una classe `Auto` che erediti da `Veicolo`, possiamo definire la classe `Auto` in questo modo:

```java
public class Auto extends Veicolo {
    // attributi e metodi specifici della classe Auto
}
```

In questo modo, la classe `Auto` eredita tutti gli attributi e metodi pubblici e protetti della classe `Veicolo`, che possono essere utilizzati direttamente all'interno della classe `Auto`.

## Overriding

Oltre a ereditare gli attributi e i metodi della classe base, una classe derivata ha la possibilità di ridefinire (override) i metodi della classe base per adattarli alle proprie esigenze. Questo meccanismo permette di personalizzare il comportamento dei metodi ereditati senza modificarne la firma. Ad esempio, se la classe `Veicolo` ha un metodo `avvia()`, la classe `Auto` può ridefinire questo metodo per gestire in modo specifico l'avvio di un'auto:

```java
public class Auto extends Veicolo {
    @Override
    public void avvia() {
        // Implementazione specifica per avviare un'auto
    }
}
```

In questo modo, quando si chiama il metodo `avvia()` su un oggetto di tipo `Auto`, verrà eseguita l'implementazione definita nella classe `Auto` anziché quella della classe `Veicolo`.

In conclusione, l'ereditarietà è uno strumento potente che permette di creare gerarchie di classi e favorisce il riuso del codice. È importante utilizzare con attenzione l'ereditarietà e l'overriding per garantire una corretta progettazione e manutenzione del software.