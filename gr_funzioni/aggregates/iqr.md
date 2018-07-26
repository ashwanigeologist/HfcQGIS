# iqr

Restituisce lo scarto interquartile calcolato da un campo o espressione.

## Sintassi

iqr(_<span style="color:red;">expression</span>, <span style="color:red;">group_by</span>, <span style="color:red;">filter</span>_)

## Argomenti

* _<span style="color:red;">expression</span>_ sotto espressione o campo da aggregare
* _<span style="color:red;">group_by</span>_ espressione opzionale da usarsi per raggruppare i calcoli aggregati
* _<span style="color:red;">filter</span>_ espressione opzionale da usare per filtrare gli elementi usati per calcolare il valore aggregato

## Esempi

* ` iqr(  "j_tot_maschi" , "COD_REG")  → scarto interquartile del valore "j_tot_maschi", raggruppato per il campo "COD_REG"`

![](/img/aggregates/iqr/iqr1.png)

## nota bene

La sintassi prevede due possibilità:
1. quella classica, senza l'uso dei paramentri denominati (l'ordine è fondamentale);
    1. iqr(_expression, group_by, filter_)
2. con i parametri denominati (l'ordine non è più fondamentale): 
    1. iqr(filter:= ,_expression:= ,group_by:=_ )

## osservazioni

--
