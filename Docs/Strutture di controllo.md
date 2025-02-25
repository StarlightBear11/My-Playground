### Strutture di controllo in Swift

1. **Condizionali (if/else)**:
   ```swift
   let temperatura = 25
   
   if temperatura > 30 {
       print("Fa caldo!")
   } else if temperatura > 20 {
       print("La temperatura è gradevole")
   } else {
       print("Fa freddo!")
   }
   ```
3. **Cicli**:
   ```swift
   // For
   for numero in 1...5 {
       print("Numero: \(numero)")
   }
   
   // While
   var contatore = 0
   while contatore < 5 {
       print("Contatore: \(contatore)")
       contatore += 1
   }
   
   // Repeat-while (do-while in altri linguaggi)
   var i = 0
   repeat {
       print("i: \(i)")
       i += 1
   } while i < 3
   ```