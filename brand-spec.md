# Brand spec — Pramish Maharjan

Extracted from CV PDF + user tone choices (Human/approachable + Tech/utility).

## Palette

```css
:root {
  --bg:      oklch(98% 0.003 240);
  --surface: oklch(100% 0 0);
  --fg:      oklch(18% 0.012 250);
  --muted:   oklch(48% 0.01 250);
  --border:  oklch(92% 0.005 250);
  --accent:  oklch(55% 0.13 165);  /* teal-green — bridges human/approachable × tech/utility */

  --font-display: -apple-system, BlinkMacSystemFont, 'SF Pro Display', system-ui, sans-serif;
  --font-body:    -apple-system, BlinkMacSystemFont, 'SF Pro Text', system-ui, sans-serif;
  --font-mono:    'JetBrains Mono', 'IBM Plex Mono', ui-monospace, Menlo, monospace;
}
```

## Posture
- Clean, professional hierarchy — CV is dense but structured; mirror with generous whitespace
- Accent used sparingly: section underlines, CTA hover, skill badges
- Display face (system sans) for headings, mono for code/skills, body for everything else
- No card shadows, no rounded-everything — borders do the work
- Data-vis moments (KPI-like highlights in the hero: 270h saved, 95% accuracy, etc.)
- Dark mode: invert bg/surface/fg, keep accent
