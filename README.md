# Gra Saper w C#

Prosty projekt konsolowej gry Saper, napisany w języku C#. Gra pozwala użytkownikowi odkrywać pola planszy 10x10 z losowo rozmieszczonymi bombami.

## Pliki

* **NowaFunkcja.cs** – główny kod gry, zawiera logikę:

  * inicjalizację planszy i planszy wyświetlanej użytkownikowi,
  * liczenie bomb wokół wybranego pola,
  * automatyczne odkrywanie pustych pól,
  * sprawdzanie warunku wygranej lub przegranej,
  * obsługę wejścia użytkownika.

* **Witaj.txt** – przykładowy tekst opisujący różne typy materiałów pisanych i multimedialnych.

## Jak uruchomić

1. Skopiuj plik `NowaFunkcja.cs` do projektu C#.
2. Skompiluj projekt np. w Visual Studio lub używając `csc` w terminalu:

   ```bash
   csc NowaFunkcja.cs
   ```
3. Uruchom grę:

   ```bash
   NowaFunkcja.exe
   ```
4. Podawaj współrzędne pól w formacie `x y` (np. `2 3`), aby odkrywać pola.

## Zasady gry

* Plansza: 10x10 pól.
* Liczba bomb: 15.
* Gra kończy się, gdy:

  * odkryjesz bombę (przegrana),
  * odkryjesz wszystkie pola niebędące bombami (wygrana).
