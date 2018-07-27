# get_feature

Restituisce la prima geometria di un vettore che corrisponde a un determinato valore di attributo.

## Sintassi

* get_feature(*<span style="color:red;">layer</span>, <span style="color:red;">attribute</span>, <span style="color:red;">value</span>*)

## Argomenti

* *<span style="color:red;">layer</span>* nome vettore o ID
* *<span style="color:red;">attribute</span>* nome attributo
* *<span style="color:red;">value</span>* valore attributo da far corrispondere



## Esempi

* `get_feature('streets','name','main st') → prima geometria trovata nel vettore "streets" con valore "main st" nel campo "name"`


![](/img/record_e_attributi/get_feature1.png)
