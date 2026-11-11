# Design system · Encore

**Thesis:** *It should feel like the moment the lights go down before the encore.* The strategy is about giving Apple Music a second hearing, so the visuals borrow from a concert at night: deep plum dark, stage-light pink and warm amber, and serif type like the liner notes of a record.

## Palette

Defined once in [`assets/tokens.json`](../assets/tokens.json); `scripts/check-contrast.mjs` checks every pairing against WCAG 2.2 AA on each push.

| Token | Hex | Use | Contrast on `bg` |
|---|---|---|---|
| `bg` | `#16070F` | Night background | — |
| `surface` | `#24101B` | Cards | — |
| `line` | `#3A2130` | Borders | decorative only |
| `ink` | `#FFF1F5` | Headlines and body | 17.9:1 |
| `ink2` | `#D9B8C6` | Secondary text | 10.9:1 |
| `accent` | `#FF4D7A` | Apple Music in charts; links and buttons ("Stage Pink") | 6.2:1 |
| `warm` | `#FFA06B` | Second highlight; italic display words ("Amber") | 9.8:1 |
| `onAccent` | `#16070F` | Text on pink or amber | 6.2:1 / 9.8:1 |
| `muted` | `#8C6A7A` | Competitor bars in charts | 4.2:1 (graphics, needs 3:1) |

**Rule:** in charts, pink is always Apple Music and muted plum is everyone else, and every bar is labelled with its name and value, so colour is never the only way to tell them apart.

## Type

- Display: serif (`New York`, Iowan Old Style, Georgia), bold, with one italic word per headline in amber, the way a record sleeve sets a title.
- Body: the system sans.
- Labels: uppercase, wide-tracked, pink.

## Motif

Concentric rings around equaliser bars, a sound spreading outward. It is the "second listen": one play that reaches further each time.

## Graphics

| File | Shows |
|---|---|
| `assets/banner.svg` | Project banner |
| `assets/market-share.svg` | Global subscriber share, end of 2025, with 2020 markers |
| `assets/growth-levers.svg` | The four growth levers along the funnel |
| `assets/roadmap.svg` | Twelve-month roadmap by quarter |
