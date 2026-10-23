# Forma natury — strona pracowni wnętrz

Responsywna strona w HTML, CSS i JavaScript, bez zależności i procesu budowania.

## Uruchomienie

W katalogu `/workspace/strona`:

```sh
python3 -m http.server 8000 --bind 0.0.0.0
```

Można też otworzyć `index.html` bezpośrednio w przeglądarce. Do zdjęć z Unsplash potrzebny jest internet.

## Personalizacja przed publikacją

- W `index.html` zastąp przykładową nazwę „Forma natury”, opis pracowni i ofertę.
- Zamień `kontakt@example.com` na swój adres i usuń informację o adresie przykładowym.
- Sekcja „Realizacje” zawiera inspiracje, a nie rzeczywiste portfolio. Dodaj własne zdjęcia, opisy i usuń informację o przykładach.
- Zdjęcia są pobierane z `images.unsplash.com`; przed publikacją dobierz własne materiały i sprawdź prawa do ich użycia.
- Kolory, odstępy i układ znajdziesz w `style.css`; obsługę menu mobilnego w `script.js`.

Stronę można opublikować na dowolnym hostingu statycznym. Nie zawiera backendu ani formularza zbierającego dane; kontakt korzysta z programu pocztowego użytkownika.
