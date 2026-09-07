# Ostek Oy — väliaikainen etusivu

Yhden sivun staattinen sivusto: <https://ostekoy.com>
Koko sivu on `index.html`-tiedostossa — logo, tyylit ja skriptit mukaan lukien.
Ei riippuvuuksia eikä käännösvaihetta.

## Päivittäminen

Muokkaa `index.html`, tallenna, ja aja:

    git pull
    git add .
    git commit -m "kuvaus muutoksesta"
    git push

Muutos on livenä noin minuutin päästä. Tarkista selaimessa Cmd+Shift+R.
Julkaisun tilan näkee repon Actions-välilehdeltä.

`git pull` ensin: GitHub tekee toisinaan omia committeja (esim. CNAME-tiedosto
Pages-asetuksista), ja ilman pullia push hylätään.

## Yhteystiedot

`index.html`, kommentilla merkitty lohko "YHTEYSTIEDOT — MUOKKAA VAIN TÄTÄ LOHKOA".
Muuta sekä href että näkyvä teksti. Puhelin `tel:`-linkissä ilman välilyöntejä.

## Testaus paikallisesti

    python3 -m http.server 8000

Aloitusanimaatio pyörii vain kerran per selainistunto — käytä yksityistä ikkunaa.





