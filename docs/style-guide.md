# Style Guide

## Sections

Rocks are grouped by classification: **Igneous**, **Sedimentary**, **Metamorphic**,
and **Extraterrestrial**. Sections appear in that order. Within a section, rows
are sorted alphabetically by rock name.

## Row format

Each rock is a single table row:

```md
| Rock | Hardness | Vibe | Source |
```

| Column | Rules |
| --- | --- |
| `Rock` | Proper name, Title Case. No trailing punctuation. |
| `Hardness` | Approximate Mohs hardness of a typical sample, as a number with exactly one decimal place, e.g. `6.0`. Rocks are aggregates, so this is a convention rather than a measurement; use the value most commonly cited, or the midpoint of a commonly cited range. |
| `Vibe` | One to three lowercase words describing the rock's general disposition. Must be an adjective or adjectival phrase. |
| `Source` | A markdown link to a reputable reference. Required. |

## What counts as a rock

Rocks are naturally occurring aggregates of one or more minerals (or mineraloids, or organic
matter, in the case of coal). Single minerals (quartz, diamond), unconsolidated sediments
(loess, peat), and terrestrial impact glasses (tektites) are out of scope unless the list
explicitly makes an exception. Meteorites and lunar/martian samples go under
**Extraterrestrial**.

## Vibes

Vibes are subjective but should be defensible. A reviewer may ask you to justify a
vibe. Avoid vibes that are merely physical descriptions (prefer `unyielding` over
`hard`).
