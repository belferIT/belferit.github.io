# Informatyka – materiały dla uczniów

Strona z materiałami do lekcji informatyki, publikowana przez GitHub Pages pod adresem https://wojcieh.github.io/.

## Dodawanie nowego tematu

W `index.html` w odpowiedniej sekcji (`Podstawy` lub `Egzaminy zawodowe`) skopiuj cały blok `<li>…</li>` z kartą i zmień:

- `href` – adres strony z tematem,
- ikonę (emoji),
- nagłówek `<h2>` i krótki opis `<p>`.

## Pliki

- `index.html` – strona główna z listą tematów
- `404.html` – strona wyświetlana przy błędnym adresie
- `.nojekyll` – wyłącza przetwarzanie przez Jekylla (strona to czysty HTML)

Autor: ITTeacherPL

## Zapowiedź tematu

Temat, który jeszcze nie jest gotowy, to karta `<div class="card soon">` z etykietą „Wkrótce” (bez linku). Gdy materiał będzie gotowy, zamień `<div class="card soon">` na `<a class="card" href="…">`, a etykietę na `<span class="go" aria-hidden="true">Przejdź →</span>`.

## Sekcje kwalifikacji (INF.02, INF.03, INF.04)

Każda sekcja kwalifikacji ma na razie komunikat `<p class="empty">`. Pod nim w komentarzu HTML jest gotowy wzór listy kart z linkiem do repozytorium – po dodaniu pierwszego repozytorium usuń komunikat i odkomentuj wzór.
