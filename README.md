# Street Fighter reference

Static reference pages for Street Fighter games, published with GitHub Pages at
https://nelsong6.github.io/street-fighter-reference/.

Each game has its own folder (`sf6/`, later `sf7/` and so on) with its own pages,
data and vendored libraries. Adding a game never changes another game's folder,
so old links keep working.

Data under `<game>/data/<build id>/` is exported from the game's files by a private
tool and stamped with the game build it came from; `<game>/data/latest.json` points
at the current build. No publisher frame data is included.
