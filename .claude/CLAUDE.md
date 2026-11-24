# zarzalejo-dashboard

Arturo's public site (static HTML and CSS, no build).

## The architecture map

This repo's pieces are drawn on Arturo's architecture map (vision's `/mapa/arquitectura`) from `map.yml`
at its root. Format, and how the map stays current: `~/Documents/Proyectos/workspace/README.md`, «The
architecture map's specs».

- When a change adds, renames or removes something the map shows (a piece, a command, a bot, a place
  where its things are kept, data it sends to another piece in `feeds`, a doc), update `map.yml` in the
  same PR. Skills and agents under `.claude/` reach the map by themselves.
- In your last message about that change, tell Arturo in one line what changed on the map, or that
  nothing did.
- No client names and nothing of the employer in `map.yml`.
