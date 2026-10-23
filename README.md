# Polski bez paniki — aktualizacja strony (23.10.2026)

## Co się zmieniło?
- **Nowa zakładka „Kursy”** (`kursy.html`) w menu i stopce każdej podstrony; kurs na Kartę Polaka opisany po polsku i rosyjsku. Na stronie głównej dodano osobne zaproszenie do kursu.
- Zakres kursu jest ogólnym opisem oferty; nie podano nieustalonych cen, terminów ani formatu i nie obiecuje się decyzji urzędowej.
- Na stronie głównej tylko jeden przycisk w bannerze: Poznaj ofertę.
- Bez dekoracyjnych strzałek w przyciskach i kafelkach-linkach.
- „O mnie”: tekst Julii po polsku oraz autorskie tłumaczenie na rosyjski.
- „Zajęcia”: cennik: 50 min / 100 zł, pakiet 12 × 50 min / 1000 zł (ważność 3 mies.), bezpłatna konsultacja 15 min; przygotowanie B1–C1 i TELC.
- „Kontakt”: przygotowane miejsce na ankietę Tally w wersjach PL/RU, ale jeszcze NIEAKTYWNE — nie wysyła danych, dopóki nie zostanie skonfigurowane.
- Fiszki zachowane bez zmiany danych i mechaniki.

## Wgrywanie na GitHub Pages
1. Rozpakuj ZIP.
2. Otwórz https://github.com/polski-bez-paniki/test .
3. Kliknij Add file → Upload files.
4. Prześlij **siedem plików `.html`** z katalogu głównego, w tym **nowy `kursy.html`**. Nie przesyłaj całego ZIP-a.
5. Potwierdź Commit changes. Nadpisz pliki o tych samych nazwach.
6. Po publikacji wejdź na https://polski-bez-paniki.github.io/test/index.html?v=4 .

## Uruchomienie zgłoszeń na e-mail przez Tally
1. Zarejestruj własne konto na https://tally.so/ i zabezpiecz je (unikalne hasło, jeśli dostępne MFA).
2. Utwórz ankietę z polami: imię, e-mail, telefon (opcjonalnie), poziom języka, cel nauki, preferowany rodzaj zajęć (opcjonalnie).
3. Dodaj klauzulę RODO/informację o ochronie danych przygotowaną dla Twojej działalności (administrator danych, cel, podstawa prawna, okres retencji, prawa, odbiorcy i kontakt); nie wymagaj niepotrzebnych danych szczególnych.
4. Ustawienia formularza → Email notifications → Self email notifications → ON. W wersji bezpłatnej domyślny e-mail zawiera wszystkie odpowiedzi. Wiadomości dotrą na e-mail konta Tally, a odpowiedzi będą też zapisywane w Tally (nie wyłącznie w poczcie).
5. Po opublikowaniu formularza skopiuj adres `https://tally.so/r/XXXXXX`.
6. W `kontakt.html` wyszukaj `id="tally-widget"` i wypełnij atrybuty `data-ru-url="https://tally.so/r/XXXXXX"` oraz `data-pl-url="https://tally.so/r/YYYYYY"`. Możesz wskazać ten sam formularz w obydwu polach, jeśli jest dwujęzyczny. Zapisz i prześlij nowy plik do repozytorium.
7. Przetestuj wysyłkę na własnych fikcyjnych danych i sprawdź, czy komplet odpowiedzi dotarł na e-mail. Sprawdź też spam i możliwość usuwania zgłoszeń.

**Uwaga o bezpieczeństwie:** Kod strony na GitHub Pages jest publiczny. W repozytorium nie umieszczaj ani danych osobowych uczniów, ani haseł, ani tokenów, ani odpowiedzi z ankiet. Sama konfiguracja linku Tally nie daje gwarancji zgodności z RODO; zweryfikuj politykę prywatności oraz umowę przetwarzania danych.

**Canva:** link `https://canva.link/7is39byq9sfvkkm` nie udostępnił nam treści do odczytu. Z tego powodu ceny i zakres zajęć opierają się na Twojej wiadomości, nie na niezweryfikowanej zawartości Canvy. Wyeksportuj ofertę jako PDF lub prześlij screeny, aby odwzorować resztę zapisów.

**Redakcja tekstu:** poprawiono oczywiste literówki „Dlaczego” → „Dlatego”, „kilkulatnie” → „kilkuletnie” i zapis przygotowania B1–C1; sens wypowiedzi pozostaje bez zmian.
