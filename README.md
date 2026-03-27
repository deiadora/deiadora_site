# deiadora · the field · zero point

> *Regenerative inspiration is all around us. Converse with the living world — and the tech, the strategy, the systems thinking emerge.*

**node 0 · infrared · #0c1516**

---

## what this is

This is the home site of the deiadora ecosystem — the zero point from which everything else unfolds. It's a personal site and a hub, but more than that it's a field: the ground condition from which ten nodes of research, writing, music, consulting, and tools are emerging.

The site belongs to Deiadora — natural technologist, researcher, writer, musician. Someone for whom the conversation with the living world is primary, and the tech, the strategy, and the systems thinking emerge from there.

---

## the ecosystem

This site is node 0. The full ecosystem maps to the ten principles of *Quantum Currency: Field Research on Human Coherence* — a book that maps quantum field theory, neuroscience, and geometric systems thinking onto the architecture of coherent human systems.

Each node in the ecosystem has its own site, its own geometry, and its own colour on the electromagnetic spectrum:

| node | principle | geometry | site | hex |
|------|-----------|----------|------|-----|
| 0 | the field · zero point | — | deiadora.com | `#0c1516` |
| 1 | coherence · torus | torus | coming soon | `#6b2d1a` |
| 2 | recognition · vesica piscis | vesica piscis | drblexchange.com | `#9d4418` |
| 3 | discernment · tetrahedron | tetrahedron | quantummagic · coming soon | `#c49a3c` |
| 4 | wave · the cube | hexahedron | coming soon | `#7a9e2a` |
| 5 | direction · second cube | hexahedron | coming soon | `#2d6a1f` |
| 6 | transmission · dodecahedron | dodecahedron | deiadorebel · coming soon | `#0f6e56` |
| 7 | expression · egg of life | egg of life | techtuition.ai | `#1a6b9e` |
| 8 | structure · octagon | octagon | thequantumceo.com | `#3c3489` |
| 9 | source · nonagon | nonagon | coming soon | `#2d1a4e` |

---

## design system

The full design system for the ecosystem lives in `deiadora_design_system.html`. It covers:

- the electromagnetic spectrum palette (nodes 0–9)
- CSS variable architecture
- typography (Exo 2 + DM Sans)
- hero section anatomy
- copy principles
- site-by-site reference
- OG image system

### colour variables

The spectrum lives in `:root`. Every site in the ecosystem shares this architecture and sets `--accent` to its own node colour.

```css
:root {
  --node-0: #0c1516;  /* the field · zero point · infrared */
  --node-1: #6b2d1a;  /* coherence · torus · deep red */
  --node-2: #9d4418;  /* recognition · vesica piscis · terracotta */
  --node-3: #c49a3c;  /* discernment · tetrahedron · pollen */
  --node-4: #7a9e2a;  /* wave · cube · new leaf */
  --node-5: #2d6a1f;  /* direction · second cube · canopy */
  --node-6: #0f6e56;  /* transmission · dodecahedron · deep water */
  --node-7: #1a6b9e;  /* expression · egg of life · open sky */
  --node-8: #3c3489;  /* structure · octagon · twilight */
  --node-9: #2d1a4e;  /* source · nonagon · ultraviolet edge */
}
```

These are the mustard seeds. Anyone reading the source will find the spectrum living in the variables. That's intentional.

### typography
- **Exo 2** — display, headings, kickers, labels, nav
- **DM Sans** — body, subheads, interface text

### dark / light mode
- Default: **dark mode**
- Dark paper: `#0c1516` · ink: `#ebe7dc` · gold: `#ecb02f` (bee gold)
- Light paper: `#f4f2ec` · ink: `#1a1814` · gold: `#8B5E2A` (beeswax)

---

## copy principles

**The living world is primary.** Not a metaphor for tech — the actual ground condition. The tech, the strategy, and the systems thinking emerge from the conversation with the living world.

**Emerge, not grow.** Things emerge from the field. That's the physics. That's the word.

**The hero note is the cheeky bit.** Short, italic, muted. The personality that the rest of the copy doesn't have room for.

**Don't defend before accused.** State the true thing directly.

**The full bandwidth.** Nature and KPIs are not in conflict. The electromagnetic spectrum holds all frequencies simultaneously. So does this work.

---

## deployment

Deployed on **Cloudflare Pages**.

- Default theme: dark
- Theme preference stored in `localStorage` key: `theme-deiadora`
- Email obfuscation via Cloudflare

---

### part of the deiadora ecosystem
 
→ [deiadora.com](https://deiadora.com) · node 0 · the field
→ [drblexchange.com](https://drblexchange.com) · node 2 · recognition
→ [quantummagic.com](https://quantummagic.ai) · node 3 · discernment
→ [iamdeiadora.com](https://iamdeiadora.com) · node 4 · wave
→ [techtuition.ai](https://techtuition.ai) · node 7 · expression
→ [thequantumceo.com](https://thequantumceo.com) · node 8 · structure

*the field is not between things. the field is primary. things are what the field does locally.*
