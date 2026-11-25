# Jonida Resort · Real Estate Međugorje

Web stranica za Jonida d.o.o.: novi projekt **Jonida Resort** (24 stana, P+3) i završeni projekt **Oasis Međugorje**.

## Što je gdje

| Datoteka / mapa | Sadržaj |
|---|---|
| `index.html` | cijela stranica (izgled, animacije, odabir stana, pretraga) |
| `i18n.js` | prijevodi na engleski, njemački i talijanski |
| `slike/` | renderi, pročelja, tlocrti etaža, `slike/stan/` tlocrti stanova |
| `oasis/` | fotke završenog projekta Oasis |
| `film/` | film i video terena |
| `og.jpg` | slika koja se pokaže kad se link podijeli |
| `_headers`, `robots.txt`, `sitemap.xml` | postavke za Netlify i Google |

## Česte izmjene

- **Status stana** – u `index.html` potražite `const STATUS={}` i upišite npr. `'S1.2':'prodano'` ili `'S0.3':'rezervirano'`.
- **Google Analytics** – u `index.html` upišite ID u `const GA_ID=''`, npr. `'G-ABC123'`.
- **Domena** – adresa `https://realestate-medjugorje.com/` upisana je u `index.html` (meta oznake), `robots.txt` i `sitemap.xml`.

## Objava

Netlify → *Add new site* → *Import from GitHub* → ovaj repozitorij. Build naredba nije potrebna, objavljuje se mapa `/`.
Upiti iz obrasca stižu u Netlify → *Forms*; obavijest na mail postavlja se u *Form notifications*.
