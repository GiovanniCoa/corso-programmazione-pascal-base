# Metodi speciali: constructor e destructor

I metodi speciali `constructor` e `destructor` sono fondamentali per l'inizializzazione e la pulizia degli oggetti in un programma. Il `constructor` è un metodo speciale che viene chiamato automaticamente quando un oggetto viene creato, mentre il `destructor` è chiamato automaticamente quando un oggetto viene distrutto.

## Constructor

Il `constructor` è utilizzato per inizializzare un oggetto, assegnando valori iniziali alle variabili di istanza e eseguendo eventuali operazioni necessarie per preparare l'oggetto all'uso. Il `constructor` ha lo stesso nome della classe e non restituisce alcun valore.

Ad esempio, supponiamo di avere una classe `Auto` con variabili di istanza come `marca`, `modello` e `anno`. Il `constructor` della classe `Auto` potrebbe essere utilizzato per inizializzare queste variabili con valori predefiniti o forniti come argomenti al momento della creazione dell'oggetto.

```cpp
class Auto {
public:
    string marca;
    string modello;
    int anno;

    Auto(string m, string mod, int a) {
        marca = m;
        modello = mod;
        anno = a;
    }
};
```

## Destructor

Il `destructor` è utilizzato per pulire l'oggetto prima che venga distrutto, ad esempio per liberare la memoria allocata dinamicamente o chiudere file aperti. Il `destructor` ha lo stesso nome della classe preceduto da una tilde `~` e non accetta argomenti né restituisce alcun valore.

Ad esempio, se la classe `Auto` avesse bisogno di chiudere un file aperto durante la sua esecuzione, potremmo definire un `destructor` per gestire questa operazione.

```cpp
class Auto {
public:
    string marca;
    string modello;
    int anno;

    Auto(string m, string mod, int a) {
        marca = m;
        modello = mod;
        anno = a;
    }

    ~Auto() {
        // Chiudi file aperto
    }
};
```

## Conclusioni

I metodi speciali `constructor` e `destructor` sono fondamentali per garantire che gli oggetti vengano inizializzati correttamente e puliti prima della loro distruzione. È importante implementare questi metodi in modo appropriato per evitare perdite di memoria e problemi di gestione delle risorse nel programma.

Ricordate sempre di definire correttamente i `constructor` e i `destructor` all'interno delle vostre classi per garantire un corretto funzionamento del vostro codice.