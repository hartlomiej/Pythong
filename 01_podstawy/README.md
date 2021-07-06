# Zestaw zadań nr 1

| Termin oddania | Punkty     |
|----------------|:-----------|
|    09.03.2021 23:00 |   10        |

--- 
Przekroczenie terminu o **n** zajęć wiąże się z karą:
- punkty uzyskania za realizację zadania są dzielone przez **2<sup>n</sup>**.

--- 

## Zadanie 1 [2 pkt]
Napisz program, który wypisze na ekranie wszystkie liczby trzycyfrowe, których cyfry ułożone sa w kolejności rosnącej.

## Zadanie 2 [2 pkt]
Napisz program, który dla dowolnego zdania zamieni wszystkie polskie znaki na angielskie odpowiedniki (usunie polskie znaki ze zdania).

## Zadanie 3 [2 pkt]
Napisz program, który na podstawie listy stringów (słowa) utworzy listę par odpowiednio (słowo, długość).
Przykład:
```python
slowa = ['abc','abcd','a','ddddd']
pary = [('abc',3), '('abcd',4), ('a',1), ('ddddd',5)]
```
## Zadanie 4 [2 pkt]
Napisz skrypt, który posortuje n dat. Wykorzystaj poniższy słownik, zawierający klucze zawierające informacje na temat dnia, miesiąca i roku. Następnie posortuje dowolnym algorytmem daty rosnąco.
```python
daty = [{'d': 4, 'm': 10, 'y': 2000},
        {'d': 2, 'm': 11, 'y': 2001},
        {'d': 10, 'm': 9, 'y': 2000},
        {'d': 11, 'm': 9, 'y': 2000},
        {'d': 15, 'm': 9, 'y': 2000},
        {'d': 15, 'm': 8, 'y': 2000},
        {'d': 4, 'm': 10, 'y': 2000},
        {'d': 5, 'm': 3, 'y': 2001},
        {'d': 6, 'm': 1, 'y': 2005},
        {'d': 2, 'm': 5, 'y': 2000},
        {'d': 1, 'm': 2, 'y': 2001},
        {'d': 10, 'm': 9, 'y': 2000}]
```
## Zadanie 5 [2 pkt]
Napisz skrypt, który szpłaszczy listę zagnieżdzoną. Zaimplementuj rozwiązania na dwa sposoby:
- z użyciem zagnieżdzonej pętli for
- z użyciem mapowania list
 
Przykład listy:
```python
[[1, 2, 3], ["Abba", "aff"], [-2, 4, 5]]
```

Po spłaszczeniu:
```python
[1, 2, 3, "Abba", "aff", -2, 4, 5]
```
