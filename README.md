# Skaalalauta

Interaktiivinen kitaran otelauta, skaalat, soinnut, nuottitunnistus mikrofonilla ja harjoitukset.

**Repo:** https://github.com/pekunalle/skaalalauta  
**Vercel:** Import this repo after uploading the full `index.html` (see below).

## Täyden appin saaminen repoon (15 sekuntia)

Työkalurajoituksen takia 100 kt:n single-file HTML ei mennyt automaattisesti. Tee näin:

1. Avaa tämä repo GitHubissa.
2. **Add file → Upload files**
3. Vedä tiedosto **`index.html`** projektin kansiosta `artifacts/skaalalauta/index.html` (tai zipistä).
4. Commit changes.

Sen jälkeen:
- GitHub Pages: Settings → Pages → main / root
- **Vercel**: New Project → Import `pekunalle/skaalalauta` → Deploy (toimii heti single-filella)

## Vaihtoehto: jaettu versio

Jos haluat erilliset tiedostot, lataa `artifacts/skaalalauta/dist/` (index.html + style.css + app.js) ja uploadaa kaikki kolme.

## Ominaisuudet

- Otelauta + skaalat / soinnut
- Laaja skaalakirjasto + bändihaku
- Nuottitunnistus + mikrofoni / USB
- Reenit + metronomi
- Viritykset, vasuri, gain

MIT
