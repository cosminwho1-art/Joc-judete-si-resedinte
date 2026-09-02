# Quiz România — Județe & Reședințe

Proiect pregătit pentru Visual Studio Code.

## Pornire rapidă
Deschide `index.html` cu extensia **Live Server** sau cu un server HTTP local.
Pentru telefon, publică folderul pe GitHub Pages și accesează adresa primită de pe telefon. Din meniul browserului alege **Adaugă la ecranul principal** pentru instalare ca aplicație.

Jocul folosește D3.js și harta GeoJSON de pe internet la prima deschidere. Service worker-ul păstrează apoi aplicația și resursele accesate în cache.

## Fișiere
- `index.html` — aplicația completă (HTML, CSS și JavaScript).
- `README.md` — aceste instrucțiuni.

## Variantă fără extensie
În terminal, din folderul proiectului, poți porni:

```bash
python -m http.server 8000
```

Apoi deschide în browser `http://localhost:8000`.

## Publicare pe GitHub Pages

1. Creează un repository GitHub și încarcă fișierele din acest folder.
2. În repository, deschide **Settings → Pages**.
3. Alege ramura `main` și folderul `/ (root)`, apoi apasă **Save**.
4. Deschide pe telefon adresa de forma `https://utilizator.github.io/nume-repository/`.
