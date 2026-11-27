Assets used in SmashRanker

## Layout

- `main/<start.gg character id>/<alt>.webp`: full character render
- `stock/<start.gg character id>/<alt>.webp`: head icon
- `mural/<start.gg character id>/<alt>.webp`: Super Smash Bros. Ultimate mural render. Only some costumes exist; alt numbers match `main/`.

Super Smash Bros. Ultimate characters use ids 1271 and up. Super Smash Bros. Melee characters use ids 1–26, plus 628 (Sheik / Zelda, drawn as Sheik) and 1744 (Random, a copy of Ultimate's Random art from 1746).

## Hosting

The site loads these files from Cloudflare Pages, which deploys this repository's root on every push to `main` (no build command, output directory `/`). `_headers` gives every file CORS and a one-day cache. Each file must stay under 25 MB and the repository under 20,000 files.

## Credits

### Super Smash Bros. Ultimate mural renders

- `mural/`: the "Mural Alternate Costumes" collection by [@MuralAltDrive](https://x.com/MuralAltDrive) and its contributors, built on the original mural isolation by [@ElevenZM](https://x.com/ElevenZM).
- Converted to WebP with the transparent border trimmed and the longest edge capped at 1800px. Files marked as placeholders in the collection are included.
- Each Mii uses one colour from the collection as alt 0 (Brawler: orange, Swordfighter: cyan, Gunner: orange). Pyra and Mythra on their own use the collection's solo images.

### Super Smash Bros. Melee

- Renders (`main/1`–`main/26`, `main/628`): captures courtesy of the Melee CSProject team (Efisio, Cjag, Cahalan, Radzo73), from the "CSProject - Melee (Full)" pack.
- Icons (`stock/1`–`stock/26`, `stock/628`): the "CSProject - Alternate icons" pack.
- Both packs were taken from [StreamHelperAssets](https://github.com/joaorb64/StreamHelperAssets), the asset collection of [TournamentStreamHelper](https://github.com/joaorb64/TournamentStreamHelper), and converted to WebP. Renders had their transparent border trimmed.
- Peach's alt 1 has no icon in the source pack and uses her default icon.

Super Smash Bros. characters and artwork are the property of Nintendo and their respective owners.
