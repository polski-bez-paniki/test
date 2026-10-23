# Polski bez paniki — propozycja strony

To statyczny, dwujęzyczny prototyp strony lektora języka polskiego jako obcego. Domyślny język: rosyjski. Przełącznik RU/PL zapamiętuje wybór w przeglądarce.

## Struktura

- `index.html` — strona główna
- `zajecia.html` — zajęcia / oferta
- `o-mnie.html` — o lektorze
- `materialy.html` — materiały
- `materialy/fiszki.html` — aktualna aplikacja z 2060 fiszkami
- `kontakt.html` — wersja demonstracyjna kontaktu
- `assets/site.css` — styl wszystkich podstron
- `assets/site.js` — nawigacja, przełączanie RU/PL
- `assets/cards-lang.js` — tłumaczenia interfejsu fiszek

## Podgląd

Rozpakuj archiwum. Otwórz `index.html` w przeglądarce. Do testów pod lokalnym serwerem możesz wykorzystać `python -m http.server 8000`, a następnie wejść na `http://localhost:8000/`.

## GitHub Pages

Opublikuj **zawartość folderu**, nie sam folder ani sam plik `index.html` — wszystkie pliki HTML i foldery `assets`, `materialy` muszą być dostępne razem. W Settings → Pages ustaw gałąź `main` i `/ (root)` przy publikacji bezpośrednio z gałęzi. Przed zastąpieniem obecnej strony fiszek zrób kopię działającego repozytorium.

## Co jeszcze wymaga uzupełnienia?

Imię, zdjęcie i autentyczny opis lektora, potwierdzone kwalifikacje, rzeczywista oferta, poziomy i cennik, kanały kontaktowe i/lub usługa rezerwacji, polityka prywatności jeśli będzie gromadzenie danych. Formularz kontaktowy to **demo i nie wysyła wiadomości**.

Postępy fiszek pozostają w lokalStorage — w tym samym adresie domenowym (origin) powinny zachować dotychczasowy zapis. W innych przeglądarkach i na innych urządzeniach nie są synchronizowane.
