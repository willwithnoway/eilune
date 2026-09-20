# Eilune Codex — Prototype

This is a dependency-free static website prototype generated from the supplied FoundryVTT / Simple Quest exports.

## Open locally
Double-click `index.html`. The site uses hash routing, so no local server is required.

## Upload
Upload the **contents of this folder** to any static host (Netlify Drop, Cloudflare Pages, GitHub Pages, etc.).

## Prototype decisions
- FFXVI-inspired visual language: near-black/navy, restrained indigo selection glow, warm neutral type, fine geometric lines, large negative space.
- `Major Players` is displayed under **Characters**.
- `Coskoreia` pages are displayed under **Places → Coskoreia Republic**.
- The unused Simple Quest sample Character (`The Lich`), sample Faction (`Dragon's Brotherhood`), and sample Bestiary record (`Red Dragon`) are excluded.
- Foundry `<section class="secret">` blocks and Simple Quest list records marked `hidden: true` are removed from the public prototype.
- Artwork captured by the Markdown export is bundled locally. Any image not present in that ZIP still points to its original Forge URL for now.

## Current archive
- Lore: 41 entries
- Characters: 14 entries
- Factions: 4 entries
- Places: 44 entries
- Bestiary: 12 entries

This is deliberately a prototype: branding, world map, locally bundled audio, and final hosting setup are deferred.
