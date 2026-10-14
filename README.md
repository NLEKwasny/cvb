# Nasze pół roku

Zaproszenie na pół rocznicy w formie strony na telefon: otwierana koperta, pięć wspomnień ze zdjęciami (pytanie „Pamiętasz?” z odpowiedzią Tak/Nie), list i pytanie „Spędzisz ze mną naszą pół rocznicę?”. Przycisk „Nie” w tym pytaniu ucieka.

## Jak zmienić treść

Wszystkie teksty są w bloku `DANE` na dole pliku `index.html`:

- `imie`, `podpis`: jej imię i Twoje,
- `zaproszenie`, `kiedy`, `gdzie`, `ubior`: tekst zaproszenia i szczegóły randki,
- `naKoniec`, `widzimySieKiedy`, `widzimySieGdzie`: ostatni ekran po „Tak”,
- `list`: Twój list, jeden akapit na element,
- `wspomnienia`: zdjęcie, podpis, tytuł i reakcje na „Tak” i „Nie”.

Zdjęcia leżą w folderze `zdjecia/`, a ścieżkę wpisuje się w polu `zdjecie`, np. `zdjecia/1-kwiatki.jpg`.

## Jak otworzyć na telefonie

Najprościej przez GitHub Pages: Settings → Pages → „Deploy from a branch” → wybierz gałąź i folder `/ (root)`. Strona będzie pod adresem `https://<użytkownik>.github.io/cvb/`.

Na darmowym koncie GitHub Pages działa tylko dla publicznych repozytoriów, więc każdy, kto zna adres, zobaczy stronę razem ze zdjęciami i listem.
