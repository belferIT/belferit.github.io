# ITTeacherPL – materiały do nauki informatyki

Strona z materiałami do lekcji informatyki, publikowana przez GitHub Pages pod adresem https://wojcieh.github.io/.

## Dodawanie gotowego tematu

W `index.html`, w odpowiedniej sekcji (np. `Podstawy`, `Nauka programowania`, `INF.04`), dopisz do listy `<ul class="items">`:

```html
<li>
  <a class="title" href="adres-tematu/">Nazwa tematu</a>
  <p>Krótki opis.</p>
</li>
```

## Temat w przygotowaniu

```html
<li class="planned">
  <span class="title">Nazwa tematu</span> <span class="tag">w przygotowaniu</span>
  <p>Krótki opis.</p>
</li>
```

Gdy materiał będzie gotowy, zamień `<span class="title">…</span>` na `<a class="title" href="…">…</a>`, usuń `class="planned"` i etykietę „w przygotowaniu”.

## Sekcje bez treści (INF.02, INF.03, Narzędziownik)

Mają na razie jedno zdanie `<p class="soon-note">`. Po dodaniu pierwszego elementu usuń je i wstaw listę `<ul class="items">` z pozycjami jak wyżej.

## Przy każdej zmianie

Zaktualizuj datę w linijce „Ostatnia aktualizacja” na górze strony.

## Pliki

- `index.html` – strona główna
- `404.html` – strona wyświetlana przy błędnym adresie
- `.nojekyll` – wyłącza przetwarzanie przez Jekylla (strona to czysty HTML)

Autor: ITTeacherPL
