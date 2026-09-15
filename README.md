# eklub.ba

Javna stranica eKluba. Jedan statički `index.html`, bez builda, objavljen preko GitHub Pages
na `https://eklub.ba`.

- Fontovi (Barlow Semi Condensed, Source Sans 3, SIL OFL) su u `fonts/` i služe se sa ove
  domene, ne sa Google Fonts — IP posjetioca ne ide trećoj strani.
- Screenshotovi u `img/` su iz **demo kluba** na produkciji (`demo@eklub.ba`), izrezani iz
  sirovih snimaka u `klubapp-mobile/store/screenshots/sirovo/`. Nijedan stvarni član.
- Politika privatnosti i brisanje naloga ostaju na backendu (`api.eklub.ba/privacy`,
  `/delete-account`) — Play listing ih već navodi i tamo moraju ostati.

Lokalno: `python3 -m http.server` u ovom direktoriju.

## DNS (global.ba)

| Zapis | Vrijednost |
|---|---|
| `eklub.ba` A | `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153` |
| `www` CNAME | `ajdin-dzananovic.github.io` |

MX, SPF i verifikacija za Zoho, `send.*` za Resend, `api` i `_railway-verify.api` se ne diraju.
