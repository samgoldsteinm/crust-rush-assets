# Crust Rush: second site

Files of the game Crust Rush that load late and weigh most (high-detail models, big scenery textures), kept apart from the game's own
site so that neither runs out of room. Every file is written here by the game's build (`build/build_gh.py`, branch `source` of the
`crust-rush` repository) and published by `tools/release_web.py`; nothing here is edited by hand.

- `geo/<model>.<hash>.bin`, `tex/<name>.<hash>.jpg|png`: the files. The hash is of the contents, so a name never changes meaning.
- `current.json`: the files of the newest build. `published.json`: the files of the version that is live.
- `.nojekyll`: serve every file as it is.
