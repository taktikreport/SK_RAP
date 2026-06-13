# Slovenský rap — atlas scény (TOP 100)

Interaktívna jednostránková (single-file) webová stránka o slovenskej rapovej scéne.
Tmavá street/graffiti estetika + prepínateľný **cyberpunk** theme.

## Čo obsahuje
- **~100 slovenských interpretov a skupín** vo vrstvenom modeli:
  - **jadro (41)** — plné profily: bio, diskografia, dvorný producent, spolupráce, novinky;
  - **rozšírený katalóg (~59)** — stručné overené záznamy (meno, generácia, mesto/crew, poznámka);
  - **+ CZ/SK presahy** — české mená s väzbou na SK scénu, jasne odlíšené (mimo poradia).
- **Filtre + vyhľadávanie** podľa mena, mesta, žánru, generácie a CZ/SK.
- **Mapa pôvodu** — reálny obrys Slovenska, mestá projektované z geografických súradníc.
- **Sieť spoluprác** — interaktívny force-graf featov a členstiev v crews/skupinách.
- **Producentský katalóg** — dvorní beatmakeri za zvukom scény.
- **Mílniky scény** — časová os.
- **Tier list builder** — drag & drop (S/A/B/C/D), zdieľanie linkom + export do PNG.
- **Glosár slangu.**

Bez tvrdého poradia 1–100 — zoskupené podľa generácií (poradie 1–100 je pri rape
editorsky sporné, streamy nepokrývajú legendy). Celé v jednom `index.html`, bez build-stepu.
Jediné externé závislosti: Google Fonts a `html-to-image` (CDN, len pre export PNG) — žiadne API kľúče.

## Lokálne spustenie
Otvor `index.html` v prehliadači (dvojklik).

## Publikovanie na GitHub Pages
1. Vytvor **verejný** repozitár (napr. `slovensky-rap`).
2. Nahraj `index.html`, `README.md` a `.nojekyll`.
3. **Settings → Pages →** Source: *Deploy from a branch*, Branch: `main`, priečinok `/ (root)`.
4. O pár minút beží na `https://<tvoje-meno>.github.io/<nazov-repa>/`.

## Zdroje dát
Dáta k roku 2026, z verejných zdrojov (Wikipédia, Refresher, SME/Closer, Spotify, Deezer).
Obrys Slovenska: mapsicon (verejná doména). Diskografie uvádzajú výber kľúčových vydaní;
pri menej zdokumentovaných menách sú záznamy zámerne stručné (bez vymýšľania faktov).
