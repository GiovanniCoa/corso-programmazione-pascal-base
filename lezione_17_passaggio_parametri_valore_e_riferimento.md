# Passaggio parametri: valore e riferimento

Il passaggio di parametri è un concetto fondamentale nella programmazione, che determina il modo in cui vengono gestiti e modificati i valori delle variabili all'interno di una funzione. In particolare, esistono due modalità di passaggio dei parametri: per valore e per riferimento.

## Passaggio per valore

Nel passaggio per valore, il valore della variabile viene copiato e passato alla funzione. Questo significa che qualsiasi modifica apportata alla variabile all'interno della funzione non avrà effetto sulla variabile originale al di fuori della funzione stessa. Questo tipo di passaggio è utilizzato quando si desidera mantenere il valore originale della variabile intatto.

```javascript
var x = 10;

function incrementValue(value) {
  value++;
}

incrementValue(x);
console.log(x); // Output: 10
```

Nell'esempio sopra, nonostante la funzione `incrementValue` incrementi il valore della variabile `value`, la variabile `x` rimane invariata poiché il passaggio è avvenuto per valore.

## Passaggio per riferimento

Nel passaggio per riferimento, viene passato un riferimento alla variabile invece del valore effettivo. Questo significa che qualsiasi modifica apportata alla variabile all'interno della funzione influenzerà direttamente la variabile originale al di fuori della funzione stessa. Questo tipo di passaggio è utilizzato quando si desidera modificare direttamente la variabile originale.

```javascript
var obj = { value: 10 };

function incrementObjectValue(obj) {
  obj.value++;
}

incrementObjectValue(obj);
console.log(obj.value); // Output: 11
```

Nell'esempio sopra, la funzione `incrementObjectValue` modifica direttamente il valore della proprietà `value` dell'oggetto `obj`, poiché il passaggio è avvenuto per riferimento.

In conclusione, il passaggio dei parametri per valore e per riferimento è un concetto fondamentale da comprendere per gestire correttamente le variabili all'interno di una funzione. È importante sapere quando utilizzare uno o l'altro in base alle esigenze specifiche del proprio programma.