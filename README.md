# archiwum-zmp-13-lat

Archiwum linkow do wynikow ZMP 13-latkow 2004-2008. Jedna statyczna strona: `index.html`.

## Publikacja (GitHub Pages)

Repo ma gotowy workflow `.github/workflows/enable-pages.yml`. Zeby ruszyl, wlasciciel
repo musi raz recznie wlaczyc Pages - token workflow nie ma uprawnien admina i dostaje
403 na `POST /repos/{owner}/{repo}/pages`.

1. Settings -> Pages -> Build and deployment -> Source: **GitHub Actions**
2. Actions -> "Publikuj na GitHub Pages" -> Re-run jobs

Adres po wdrozeniu: `https://lazyjac.github.io/archiwum-zmp-13-lat/`

Od tego momentu kazdy push do `main` publikuje sie sam.

## Alternatywa (Netlify)

W repo lezy `netlify.toml` (publikacja katalogu glownego, bez kroku budowania).
Wystarczy w panelu Netlify podpiac to repo przez "Import from Git" - konfiguracja
zostanie odczytana automatycznie.
