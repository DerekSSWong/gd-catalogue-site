# GD Catalogue

A searchable browser for Grim Dawn item data, published at
**https://dereksswong.github.io/gd-catalogue-site/**

Three datasets, one page, behind a tab bar:

| tab | what it holds |
|---|---|
| Augments and Components | faction augments, runes, and crafting components |
| Target Farmable Gear | Monster Infrequents, with drop locations |
| Craftable and Vendor Gear | blueprint-craftable gear, plus finished gear faction vendors sell outright |

## This repo is output, not source

`index.html` is generated — **never hand-edit it**. It is built from the game's own
records by a separate private pipeline, which reads a local extraction of the game
database (~77k files) that cannot live in a repo. Regenerate and redeploy from
there; an edit made here is lost on the next build.

Item names, stats and flavor text are the property of Crate Entertainment.
