# Kartkówka z niemieckiego

Już jutro odbędzie się kartkówka z niemieckiego, dlatego Pan Michał stwierdził,
że to już czas aby przejrzeć materiał. Niestety zdał sobie sprawę, że sytuacja nie wygląda
zbyt ciekawie. Dla każdego zwrotu, którego powinien znać obliczył prawdopodobieństwo, że będzie pamiętał go
na kartówce. Za każdy zapamiętany zwrot można otrzymać 1 punkt. Pan Michał wyznaczył sobie również
ambitny cel: chciałby aby jego wynik punktowy na karkówce wynosił co najmniej m punktów. Jako, że Pan Michał
nie czuje się jeszcze w pełni gotowy na to wyzwanie, przyszedł mu z pomocą Pan Tomasz, który przygotował
Quizleta. Obiecał też Panu Michałowi, że jeśli przerobi Quizleta k razy to dla początkowego prawdopodobieństwa
zapamiętania zwrotu x, prawdopodobieństwo po skończeniu nauki jest określone funkcją:

![image](https://github.com/user-attachments/assets/bebd19c6-8988-4025-9bae-f24415ba922f)

Pomóż Panu Miachałowi i powiedz ile razy będzie musiał zrobić Quizleta żeby wartość oczekiwana liczby zapamiętanych
zwrotów była równa co najmniej m. Może się zdarzyć, że Pan Michał ~~ma na tyle niskie oczekiwania~~ ma tak dużą znajomość
języka niemieckiego, że nie musi uczyć się wcale, wtedy odpowiedź wynosi 0.

W pierszym wierszu pliku `dane.txt` znajdują się dwie liczby całkowite n (1 <= n <= 100000) oraz m (1 <= m <= n) odpowiednio liczba zwrotów
oraz oczekiwania Pana Michała. W następnych n wierszach znajdują się liczby p_i (0 <= p_i <= 1) podane z dokładnością do 4 miejsc po przecinku - kolejne początkowe prawdopodobieństwa zapamiętania danego zwrotu.

Przykład:

dla danych:
```
3 2
0.2
0.3
0.4
```

poprawną odpowiedzią jest:
84

Odpowiedź wypisz na standardowe wyjście lub zapisz do pliku `wynik.txt`.