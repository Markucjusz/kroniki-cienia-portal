# Kroniki Cienia — Portal Społeczności i Baza Wiedzy

Oficjalna strona informacyjna turowej gry przeglądarkowej **Kroniki Cienia**.

- **Bezpośredni link do gry:** https://markucjusz.github.io/kroniki-cienia/
- **Repozytorium kodu gry:** https://github.com/markucjusz/kroniki-cienia

## Struktura projektu
- `index.html` — główna strona portalu z opisem świata, osadzoną grą (`<iframe>`) oraz sekcją komentarzy.
- `style.css` — arkusz stylów w ciemnej tonacji RPG.

## Uruchomienie komentarzy (Giscus)
1. Przejdź do zakładki **Settings -> General -> Features** w tym repozytorium na GitHubie i zaznacz **Discussions**.
2. Wejdź na [giscus.app/pl](https://giscus.app/pl) i podaj nazwę tego repozytorium (`markucjusz/nazwa-tego-repozytorium`).
3. Skopiuj wygenerowany skrypt `<script>` i wklej go w sekcji `#komentarze` w pliku `index.html` (zastępując blok `.giscus-placeholder`).
