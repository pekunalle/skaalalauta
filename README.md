# Skaalalauta

Interaktiivinen **kitaran otelauta** selaimessa: skaalat, soinnut, nuottitunnistus mikrofonilla / USB-audiolla, harjoitukset ja metronomi.

Avaa suoraan: **[GitHub Pages](https://pekunalle.github.io/skaalalauta/)** (kun Pages on päällä).

## Ominaisuudet

- **Otelauta** – visualisoi skaalat ja soinnut, valitse root, oktaavialue, sormitustavat
- **Skaalakirjasto** – moodit, rock, metal, exotic, jazz + bändihaku (Slayer, Gojira, Sabbath…)
- **Soinnut** – power, minor, dim, sus jne.
- **Tunnistus** – klikkaa nuotteja otelaudalta tai käytä mikrofonia → ehdottaa skaaloja
- **Kuuntelu** – reaaliaikainen pitch detection + nuottijahti
- **Reeni** – harjoituslista + edistymisseuranta (localStorage) + metronomi
- **Asetukset** – viritys (standard, drop D/C, DADGAD…), vasuri, nauhamäärä, gain, äänilaite

## Käyttö

1. Avaa `index.html` selaimessa (tai GitHub Pages -osoite).
2. Chrome / Edge toimii parhaiten mikrofonin kanssa (HTTPS suositeltava).
3. USB-audio (esim. M-Vave): Asetukset → valitse äänilaite → säädä Gain.

Ei asennusta, ei backendia – yksi HTML-tiedosto.

## GitHub Pages

Repo on asetettu siten, että voit kytkeä Pagesin päälle:

1. GitHub → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / folder: `/ (root)`
4. Save → odota hetki → sivu aukeaa osoitteessa  
   `https://pekunalle.github.io/skaalalauta/`

## Lisenssi

MIT – käytä vapaasti.
