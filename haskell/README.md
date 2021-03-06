# Języki programowania - zadania projektowe
>### Informatyka sem 3

## Lista zadań:

- [x] **Zadanie 5**

  - >Dla danego zbioru w postaci listy L obliczyć jego zbiór potęgowy.
  - Instrukcja użytkowania programu:
    - Załadowanie modułu poprzez  :l zad_5.hs
    - Na wejściu podawana jest zwykła lista *( np. [1, 2, 3] )*
    - >zbiorPotegowy [1, 2, 3]
  
- [x] **Zadanie 21**

  - >Dla danej liczby naturalnej n podaj wszystkie liczby pierwsze ≤ n dla których każda rotacja ich cyfr
nadal jest liczbą pierwszą. Taką liczbą jest 197 i jej dwie możliwe rotacje: 971 i 719.
- [x] **Zadanie 30**

  - >Kod Prüfer’a pozwala przekształcić dowolne drzewo na unikalną sekwencję liczb.
  Zaimplementować funkcję kodującą drzewo podane w postaci ciągu krawędzi (lista par liczb)
  kodem Prüfera (lista liczb):
  ```
  prufer_code [(1, 2)]
  > []
  prufer_code [(1, 2), (1, 3)]
  > [1]
  prufer_code [(1, 2), (2, 3)]
  > [2]
  prufer_code [(1, 3), (2, 3)]
  > [3]
  prufer_code [(1, 4), (2, 4), (3, 4)]
  > [4, 4]
  ```
  - Instrukcja użytkowania programu:
    - Załadowanie modułu  :l zad_30.hs
    - >pruferCode [(1, 2), (2, 3)]

## Przydatne zasoby
- [***Poradnik wideo***](https://www.youtube.com/channel/UC3xdLFFsqG701QAyGJIPT1g/videos)
- [***Poradnik tekstowy***](http://learnyouahaskell.com/chapters)
- [***Wiki dla podstawowego modułu***](https://hackage.haskell.org/package/base-4.15.0.0/docs/index.html)
