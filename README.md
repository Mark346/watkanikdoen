# Wat kan ik doen? 🤔

Verveel je je? Kies waar, met wie, hoeveel tijd en hoeveel energie, druk op **🎲 Geef me iets!** en je krijgt een idee.

- 265 ideeën in 13 categorieën (o.a. ⚽ Voetbal, 🤖 AI, 🔧 Techniek & bouwen, 📈 Beter worden & mindset)
- Favorieten, eigen ideeën en een gedaan-lijst met streak
- Werkt zonder account, zonder kosten en ook offline
- Alles wordt alleen op de telefoon zelf opgeslagen

## Online zetten met GitHub Pages

1. Maak op GitHub een nieuwe repository, bijvoorbeeld `wat-kan-ik-doen` (zet hem op **Public**).
2. Klik op **Add file → Upload files** en sleep alle bestanden uit deze map erin:
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`, `README.md`
3. Klik op **Commit changes**.
4. Ga naar **Settings → Pages**. Kies bij *Source* **Deploy from a branch**, branch **main**, map **/ (root)** en klik **Save**.
5. Na een minuutje staat de app op:
   `https://JOUW-GEBRUIKERSNAAM.github.io/wat-kan-ik-doen/`

## Op de iPhone zetten

1. Open de link in **Safari**.
2. Tik op het deel-icoon (vierkant met pijltje) → **Zet op beginscherm**.
3. De app staat nu met een eigen icoon op het beginscherm en opent schermvullend.

## Aanpassen

- **Nieuwe ideeën:** zet ze in `index.html` **onderaan** de lijst `RAW` (anders schuiven favorieten en de gedaan-lijst op).
  Vorm: `["emoji","Titel","Uitleg","categorie","b/u/bu","a/s/f",minuten,energie 1-3,scherm 0/1,kost 0/1]`
- **Na elke aanpassing:** verhoog in `sw.js` het versienummer (`v1` → `v2`), zodat de telefoon de nieuwe versie ophaalt.
