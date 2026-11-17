# ひらがな カタカナ · Hiragana & Katakana Quiz

**▶ Zagraj: [hiragana.pl](https://hiragana.pl)**

Darmowy quiz do nauki japońskich sylabariuszy: hiragany i katakany. Działa w przeglądarce, instaluje się na telefonie jak aplikacja i działa offline.

![Hiragana & Katakana Quiz](screenshots/banner.png)

## Funkcje

- **Hiragana, katakana albo obie naraz.** Każde pismo ma 46 podstawowych znaków oraz 23 znaki z dakuten i handakuten.
- **Tryb losowy** albo **trening po kolei**, rząd po rzędzie jak w tablicy.
- **4 odpowiedzi do wyboru.** Dobra odpowiedź podświetla się na zielono, zła na czerwono, a apka pokazuje poprawną.
- **Wynik i seria.** Po rundzie widać wynik, najdłuższą serię i listę znaków do powtórki.
- **Tablica znaków** z romaji dla obu pism.
- **Dźwięki**, które można wyciszyć.
- **Wersja polska i angielska.**
- **Instalacja na telefonie (PWA) i tryb offline.**
- **Obsługa z klawiatury:** klawisze `1`–`4` wybierają odpowiedź, `Enter` przechodzi dalej, a `Esc` wraca do menu.

## Zrzuty ekranu

| Start | Dobra odpowiedź | Zła odpowiedź |
|:---:|:---:|:---:|
| <img src="screenshots/1-start.png" width="240"> | <img src="screenshots/2-dobrze.png" width="240"> | <img src="screenshots/3-zle.png" width="240"> |

| Katakana | Wynik | Tablica znaków |
|:---:|:---:|:---:|
| <img src="screenshots/5-katakana-start.png" width="240"> | <img src="screenshots/4-wynik.png" width="240"> | <img src="screenshots/6-tablica.png" width="240"> |

## Instalacja na telefonie

- **iPhone (Safari):** wejdź na [hiragana.pl](https://hiragana.pl), stuknij **Pobierz aplikację** albo Udostępnij → **Do ekranu głównego** → Dodaj.
- **Android (Chrome):** wejdź na [hiragana.pl](https://hiragana.pl), stuknij **Pobierz aplikację** albo menu ⋮ → **Zainstaluj aplikację**.

## Technologie

Czysty HTML, CSS i JavaScript, bez frameworków i bez procesu budowania. Dźwięki są generowane przez Web Audio API. Czcionki Inter i Klee One są przycięte do potrzebnych znaków. Tryb offline obsługuje Service Worker, a hosting to GitHub Pages z własną domeną.

## Aktualizacja

Po każdej zmianie plików podbij wersję `CACHE` w `sw.js`, żeby zainstalowane aplikacje pobrały nową wersję.

---

**English:** a free quiz for learning Japanese hiragana and katakana. It has basic characters and dakuten, random or in-order practice, a kana chart and PL/EN versions, and it is installable as an app that works offline. Play at **[hiragana.pl](https://hiragana.pl)**.
