# Ostek Oy — väliaikainen etusivu

Staattinen sivu. Ei riippuvuuksia, ei käännösvaihetta, ei ulkoisia latauksia.

## Tiedostot

- `index.html` — koko sivu (HTML, CSS, JS, logo ja favicon samassa tiedostossa)
- `ostek-og.png` — kuva joka näkyy kun linkki jaetaan WhatsAppissa tai Facebookissa
- `CNAME` — kertoo GitHub Pagesille oman verkkotunnuksen
- `.nojekyll` — estää GitHubia käsittelemästä tiedostoja turhaan

## Testaus omalla koneella

    cd <tämä kansio>
    python3 -m http.server 8000

Avaa selaimessa http://localhost:8000
Lopeta palvelin painamalla Ctrl+C.

Aloitusanimaatio pyörii vain kerran per selainistunto. Nähdäksesi sen
uudestaan avaa sivu yksityisessä selausikkunassa.

## Yhteystietojen muuttaminen

`index.html`-tiedostossa on kommentti `YHTEYSTIEDOT — MUOKKAA VAIN TÄTÄ LOHKOA`.
Muuta sekä `href`-osoite että näkyvä teksti.

## Verkkotunnus

Sivu on tarkoitettu osoitteeseen https://ostekoy.com/
Jos sivusto vastaa muodossa www.ostekoy.com, päivitä `canonical`-,
`og:url`- ja `og:image`-rivit head-osiossa vastaamaan sitä.
