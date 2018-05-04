## funzione `levenshtein`

Restituisce la distanza di Levenshtein tra due stringhe. Questa equivale al minimo numero di modifiche di caratterere (inserimenti, cancellazioni o sostituzione) richieste per cambiare una stringa in un'altra.
La distanza di Levenshtein � una misura della somiglianza tra due stringhe. Distanze pi� piccole corrispondono a stringhe pi� simili, e distanze pi� grandi corrispondono a stringhe pi� differenti. La distanza � sensibile alle lettere maiuscole.

## Sintassi

* levenshtein(*string1, string2*)

## Esempi
```
* levenshtein('kittens','mitten') ? 2
* levenshtein('Kitten','kitten') ? 1
* levenshtein(upper('Kitten'),upper('kitten')) ? 0
```

<img src="/img/corrispondenza_fuzzy/levenshtein1.png">