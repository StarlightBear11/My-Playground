### Variabili e Costanti in Swift

In Swift, puoi memorizzare i dati usando variabili e costanti:

1. **Variabili** (`var`): i valori possono essere modificati dopo la dichiarazione
   ```swift
   var nome = "Mario"
   nome = "Luigi"  // Questo è consentito
   ```

2. **Costanti** (`let`): i valori non possono essere modificati dopo la dichiarazione
   ```swift
   let pi = 3.14159
   // pi = 3.14  // Questo causerebbe un errore
   ```

### Dichiarazione esplicita dei tipi

Puoi dichiarare esplicitamente il tipo di una variabile o costante:

```swift
var età: Int = 30
var altezza: Double = 1.75
var nome: String = "Marco"
var isStudente: Bool = true
```

### Inferenza di tipo

Swift può dedurre automaticamente il tipo in base al valore assegnato:

```swift
var cognome = "Rossi"  // Swift deduce che è una String
var peso = 70          // Swift deduce che è un Int
```

### Stringhe e interpolazione

```swift
let nome = "Anna"
let età = 25
let saluto = "Ciao, mi chiamo \(nome) e ho \(età) anni."
print(saluto)  // Stampa: Ciao, mi chiamo Anna e ho 25 anni.
```

### Tipi numerici

```swift
let intero: Int = 42
let decimale: Double = 3.14159
let piccolo: Float = 2.71828
```

### Operazioni sulle variabili

```swift
var a = 10
var b = 5

// Operazioni aritmetiche
let somma = a + b       // 15
let differenza = a - b  // 5
let prodotto = a * b    // 50
let quoziente = a / b   // 2

// Operazioni di assegnazione composta
a += 2  // Equivale a: a = a + 2, ora a = 12
b *= 3  // Equivale a: b = b * 3, ora b = 15
```

### Controllo di tipo

```swift
var numero = 42
var testo = "Hello"

type(of: numero)  // Restituisce Int.Type
type(of: testo)   // Restituisce String.Type
```

### Optional

Gli optional in Swift sono un concetto importante che permette di gestire l'assenza di valore:

```swift
var nome: String? = "Marco"  // Optional String che contiene "Marco"
nome = nil                  // Ora contiene nil (nessun valore)

// Per accedere al valore di un optional in modo sicuro
if let nomeNonNil = nome {
    print("Il nome è \(nomeNonNil)")
} else {
    print("Il nome non è specificato")
}

// Oppure con l'operatore di unwrapping forzato (da usare con cautela)
let nomeUtente = "Guest"
let nomeVisualizzato = nome ?? nomeUtente  // Se nome è nil, usa "Guest"
```