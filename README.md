# Layout Studio — Design System

The source of truth for Layout Studio's visual language. Tokens, components, and grid templates for building decks, prototypes, landing pages, and shipped product.

**Live:** `https://lobzyjay.github.io/layoutstudio-design-system/`

---

## Using this with Claude Design AI

Point Claude Design AI at the live GitHub Pages URL or raw file URLs. Reference specific sections by anchor:

```
/#colors        /#typography    /#logo          /#spacing
/#grid          /#components    /#voice         /#tokens-export
```

### Example prompt

```
Use the Layout Studio design system at
https://lobzyjay.github.io/layoutstudio-design-system/

Apply all tokens (colors, typography, spacing), components
(ls-card-dark, ls-pill, ls-stat), and grid templates (L01–L07)
exactly as defined. Dark-first rhythm. Coolvetica for display,
Founders Grotesk for body.

Build: [your brief]
```

---

## File structure

```
/
├── index.html      → Full interactive design system site
├── tokens.css      → CSS variables only (importable)
├── tokens.json     → Design tokens spec (for Figma, Style Dictionary, etc.)
└── README.md       → This file
```

---

## Core rules (quick reference)

**Colors**
- Dark-first. Electric Purple `#5A28DD` is the accent.
- Gradient is reserved for signature moments — never filler.
- Coral `#E8453C` is campaign-only.

**Typography**
- Coolvetica for headlines (Heavy Compressed / Heavy Condensed).
- Founders Grotesk for body, UI, labels.
- Never Helvetica or Arial on designed materials.

**Spacing**
- 8px base. All values are multiples of 4 or 8.
- Outer slide margin: 30px. Card padding: 24px. Card gap: 16px.

**Grid**
- Seven canonical layouts (L01–L07).
- Tall left column is always 24% of content width.

**Voice**
- Direct, confident, no corporate filler.
- Short sentences. Fragments when they land.
- No em dashes. No "leveraging", no "end-to-end".

---

## Canvas

Slides are built at **1440 × 810px** (16:9). Web layouts scale from that same grid.

---

## Credits

Built by [Layout Studio](https://www.layoutstudio.co). Lagos · Dubai · Zurich · London.
