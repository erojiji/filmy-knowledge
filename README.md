# Filmy Knowledge

A non-commercial, offline-first catalogue of Indian films, with Hindi and Telugu
as the first-class languages. It is the data layer for a private film-auction
game; the game code is not in this repository.

## What is here

- `fixtures/films-0.1.0.json` — the frozen schema-1 game contract, five films.
- `fixtures/schema-1.schema.json` — the JSON Schema for that contract.
- `releases/0.1.0/public/films.json` — the 40-film public release.
- `examples/on_demand_swades.json` — the on-demand response shape.

## What is not here

No game rules, no private evidence, no trade quotes, no raw source snapshots,
no IMDb data. This repository is a public projection, not the working database.

## Licensing and attribution

- Wikipedia-derived facts: CC BY-SA 4.0, attribution to Wikipedia contributors.
- Wikidata-derived identifiers: CC0 1.0.
- TMDB poster URLs and IDs: non-commercial use with attribution. This product
  uses TMDB and the TMDB APIs but is not endorsed, certified, or otherwise
  approved by TMDB.
- Trade-derived facts carry source URLs in the public release. The private
  quotes and snapshots are not published.

See `ATTRIBUTION.md` and `DATA_LICENSE.md`.

## Status

Pilot release `0.1.0`, schema `1.0.0`, 40 films. The fixture is frozen; additive
changes only after the fixture.
