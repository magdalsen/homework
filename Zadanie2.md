Zadanie 2
---
Napisz funkcję która odwróci kolejność cyfr dla przekazanej w argumencie liczby.

Przykład:
Dla liczby `32243` zwracana wartość to `34223`

var array = ['1', '5', '10', '15'];
array.reverse(function(a, b) {
return a.localeCompare(b, 'pl', {numeric: true})
});
