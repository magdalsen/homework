Zadanie 1
---
Napisz funkcję która dla przekazanego argumentu zwróci typ danych. Dla obiektów dodatkowo powinna zostać zwrócona nazwa klasy.

Przykład:
Dla wartości `1` zwracana wartość to `"number"`
Dla wartości `new Date()` zwracana wartość to `"object Date"`
Dla wartości `fetch('https://api.github.com/users/juszczak')` zwracana wartość to `"object Promise"`


function getType(type){
    return typeof type;
}
getType(1)
