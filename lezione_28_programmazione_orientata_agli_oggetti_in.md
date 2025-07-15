# Programmazione orientata agli oggetti: introduzione

La programmazione orientata agli oggetti (OOP) è un paradigma di programmazione che si basa sull'organizzazione del codice in classi e oggetti, permettendo una maggiore modularità, riusabilità e manutenibilità del software. In questo articolo introdurremo i concetti base e la sintassi OOP in Pascal.

## Concetti base della programmazione orientata agli oggetti

I principali concetti della programmazione orientata agli oggetti sono:

- **Classe**: una classe è una struttura che definisce un insieme di attributi e metodi che descrivono il comportamento di un oggetto. Le classi sono il fondamento della programmazione orientata agli oggetti e vengono utilizzate per creare istanze di oggetti.
- **Oggetto**: un oggetto è un'istanza di una classe. Gli oggetti possono avere attributi (variabili) e metodi (funzioni) che definiscono il loro comportamento.
- **Incapsulamento**: l'incapsulamento è il concetto che permette di nascondere la complessità interna di un oggetto e di esporre solo le funzionalità necessarie all'esterno.
- **Ereditarietà**: l'ereditarietà permette di creare nuove classi basate su classi esistenti, ereditandone attributi e metodi e aggiungendone di nuovi.
- **Polimorfismo**: il polimorfismo permette a oggetti di classi diverse di rispondere in modo diverso a uno stesso messaggio.

## Sintassi OOP in Pascal

In Pascal, la programmazione orientata agli oggetti è supportata attraverso l'utilizzo di classi e oggetti. Ecco un esempio di sintassi per la creazione di una classe e di un oggetto in Pascal:

```pascal
type
  TPersona = class
  private
    FNome: string;
    FCognome: string;
  public
    constructor Create(Nome, Cognome: string);
    procedure Saluta;
  end;

constructor TPersona.Create(Nome, Cognome: string);
begin
  FNome := Nome;
  FCognome := Cognome;
end;

procedure TPersona.Saluta;
begin
  WriteLn('Ciao, sono ', FNome, ' ', FCognome);
end;

var
  Persona: TPersona;

begin
  Persona := TPersona.Create('Mario', 'Rossi');
  Persona.Saluta;
end.
```

Nell'esempio sopra, viene definita una classe `TPersona` con due attributi privati `FNome` e `FCognome`, un costruttore `Create` e un metodo `Saluta`. Viene quindi creato un oggetto di tipo `TPersona` chiamato `Persona` e viene invocato il metodo `Saluta`.

In conclusione, la programmazione orientata agli oggetti in Pascal permette di scrivere codice più modulare e organizzato, favorendo la riusabilità e la manutenibilità del software. È importante comprendere i concetti base e la sintassi OOP per sfruttare appieno i vantaggi di questo paradigma di programmazione.