## Funzione `end_point`

Restituisce l'ultimo nodo di una geometria.

## Sintassi

end_point(_geometry_)

## Argomenti

* _geometry_ oggetto geometria

## Esempi

* `geom_to_wkt(end_point(geom_from_wkt('LINESTRING(4 0, 4 2, 0 2)'))) → 'Point (0 2)'`

<img src="/img/geometria/end_point/end_point1.png">

## nota bene

--

## osservazioni

--
End_point di geometria poligonale:

<img src="/img/geometria/end_point/end_point2.png">