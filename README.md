# Bridge conventies oefenen

Oefenapp voor bieden en spelen (biedconventies en slagen tellen). Onderdelen: Stayman en Jacoby na 1SA, het informatiedoublet en openingen.

## Bestanden

- `index.html`: de hele app (opmaak, biedlogica en schermen)
- `manifest.webmanifest`: naam, kleuren en pictogram voor installatie op telefoon
- `sw.js`: zorgt dat de app ook zonder internet werkt
- `icon-192.png`, `icon-512.png`: pictogrammen

## Online zetten met GitHub Pages

1. Zet alle bestanden in de hoofdmap van de repository.
2. Ga naar Settings > Pages, kies bij Source "Deploy from a branch", branch `main`, map `/ (root)` en klik Save.
3. Na een minuut staat de app op `https://<gebruikersnaam>.github.io/<repository>/`.

## Nieuwe versie uitbrengen

Vervang de gewijzigde bestanden en verhoog `VERSION` in `sw.js` (bijvoorbeeld naar `bridge-v2`).
