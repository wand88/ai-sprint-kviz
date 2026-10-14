# Kviz: agent ili ne? — AI Sprint

Interaktivni kviz za telefon (4 scenarija, odgovor i objašnjenje odmah posle izbora).

## Objava na GitHub Pages (5 minuta)
1. Na GitHub-u napravite novi **public** repozitorijum, npr. `ai-sprint-kviz`.
2. **Add file → Upload files** → prevucite `index.html` → **Commit changes**.
3. **Settings → Pages** → *Source: Deploy from a branch* → Branch: `main`, folder `/ (root)` → **Save**.
4. Posle 1–2 minuta kviz je na adresi: `https://KORISNIK.github.io/ai-sprint-kviz/`

## Na treningu
- **Polaznici:** skeniraju QR i rade kviz na telefonu.
- **Projektor:** otvorite istu adresu sa `?qr` na kraju — `https://KORISNIK.github.io/ai-sprint-kviz/?qr` — prikazuje veliki QR kod i link.
- Odgovori se ne čuvaju i ne šalju; svako vidi samo svoj rezultat. Zbirni rezultat sale: „podignite ruku ko je imao 4/4“.

## Izmena pitanja
Pitanja su u nizu `Q` u `index.html` (naslov, tekst, `agent: true/false`, tip i objašnjenje).
