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
| `Hardness` | Mohs hardness as a number with exactly one decimal place, e.g. `6.0`. Use the midpoint if a range is commonly cited. |
| `Vibe` | One to three lowercase words describing the rock's general disposition. Must be an adjective or adjectival phrase. |
| `Source` | A markdown link to a reputable reference. Required. |

## Vibes

Vibes are subjective but should be defensible. A reviewer may ask you to justify a
vibe. Avoid vibes that are merely physical descriptions (prefer `unyielding` over
`hard`).
