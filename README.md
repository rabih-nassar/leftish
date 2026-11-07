# L.E.FT Architects — website concept

An unofficial design concept for the Beirut / New York architecture practice
**L.E.FT Architects**. Not affiliated with, endorsed by, or operated by the firm.
The practice's live site is [leftish.net](https://leftish.net).

**Live preview → https://rabih-nassar.github.io/leftish/**

---

## What this is

A static site, self-contained, no build step and no dependencies.

    index.html      the entire site — markup, CSS and JS inline
    img/            27 web-optimised images, 2000px and 1100px derivatives

Run it locally by opening `index.html`, or:

    python3 -m http.server 8000

Google Fonts are loaded over the network; everything else is local.

## Structure

| Route | |
|---|---|
| `#/` | home — hero, statement, the Lexicon, selected work, index |
| `#/work` | selected projects, filterable by Arabic spatial term |
| `#/project/<id>` | project pages |
| `#/archive` | complete works, 2001–2026 |
| `#/information` | practice, principals, contact, awards, exhibitions |

## Design notes

The organising device is the **five Arabic spatial terms** that structure the
practice's own 2026 Actar monograph *At the Edge of Where God Built* —
*ṭawāf, jāmiʿ, riwāq, dār, khirba* — used as the primary index into the work,
with chronology demoted to the Archive.

- **Type** — Familjen Grotesk (Latin), Amiri (Arabic), Newsreader (editorial italic)
- **Palette** — keyed to the Moukhtara limestone; light and dark, defaulting to
  the visitor's system setting
- **Interaction** — the work index dims as a group while the hovered row surfaces
  a floating image that eases after the cursor

Project descriptions are L.E.FT's own writing, recovered from their previous website.
Photography by Iwan Baan, Ieva Saudargaite, Bahaa Ghoussainy, Joe Kesrouani,
Laurian Ghinițoiu and Sahir Uğur Eren — rights remain with the photographers
and the practice.

`<meta name="robots" content="noindex">` is set so this concept cannot be
mistaken for the firm's official site in search results. Remove that one line
if you want it indexed.
