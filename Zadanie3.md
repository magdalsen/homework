Zadanie 3
---
Napisz funkcję obliczającą Liczbę Trójkątną* o numerze przekazanym jako argument.

Przykład:
Dla wartości `3` zwracana wartość to `6`
Dla wartości `6` zwracna wartość to `21`

Wersja zaawansowana
---
Funkcja powinna obliczać Liczbę Czworościenną.

Przykład:
Dla wartości `3` zwracna wartość to `10`
Dla wartości `8` zwracna wartość to `120`

> *[Liczba trójkątna](https://pl.wikipedia.org/wiki/Liczba_tr%C3%B3jk%C4%85tna)
> *[Liczby czworościenne](https://pl.wikipedia.org/wiki/Liczby_czworo%C5%9Bcienne)


function liczbaTrojkatna(n){
    var wynik = (n*(n+1)/2);
    return wynik;
};
liczbaTrojkatna(3);

function liczbaCzworoscienna(n){
    var wynik = (n*(n+1)*(n+2)/6);
    return wynik;
};
liczbaCzworoscienna(3);
