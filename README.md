# Slovenský rap — atlas scény (TOP 30)

Interaktívna jednostránková (single-file) webová stránka o slovenskej rapovej scéne.
Tmavá street/graffiti estetika + prepínateľný **cyberpunk** theme.

## Čo obsahuje
- **TOP 30 interpretov** — karty s bio, diskografiou, spoluprácami a poslednými novinkami (klik = detail).
- **Filtre + vyhľadávanie** podľa mena, mesta, žánru a generácie.
- **Mapa pôvodu** — reálny obrys Slovenska, mestá projektované z geografických súradníc.
- **Sieť spoluprác** — interaktívny force-graf featov (ťahaj/klikni).
- **Producentský katalóg** — dvorní beatmakeri za zvukom scény.
- **Mílniky scény** — časová os.
- **Tier list builder** — drag & drop (S/A/B/C/D), zdieľanie linkom + export do PNG.
- **Glosár slangu.**

Celé v jednom súbore `index.html`, bez build-stepu. Jediné externé závislosti sú
Google Fonts a knižnica `html-to-image` (z CDN, len pre export PNG) — žiadne API kľúče.

## Lokálne spustenie
Stačí otvoriť `index.html` v prehliadači (dvojklik).

## Publikovanie na GitHub Pages
1. Vytvor nový **verejný** repozitár na GitHube (napr. `slovensky-rap`).
2. Nahraj doň `index.html`, `README.md` a `.nojekyll` (súbor `.nojekyll` zabráni
   tomu, aby GitHub prepisoval výstup cez Jekyll).
3. V repozitári: **Settings → Pages**.
4. V sekcii *Build and deployment* zvoľ **Source: Deploy from a branch**,
   *Branch:* `main` a priečinok `/ (root)`. Ulož.
5. Po pár minútach bude web dostupný na
   `https://<tvoje-meno>.github.io/<nazov-repa>/`.

> Tip: ak chceš vlastnú doménu, pridaj ju v *Settings → Pages → Custom domain*.

## Zdroje dát
Dáta k roku 2026, zostavené z verejných zdrojov (Wikipédia, Refresher, SME/Closer,
Spotify, Deezer). Obrys Slovenska: mapsicon (verejná doména). Diskografie uvádzajú
výber kľúčových vydaní; pri menej zdokumentovaných menách sú zámerne stručné.
