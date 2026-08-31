# vonkelveld.com

The public website and press kit for **Vonkelveld**, a deterministic god-sim on Steam Early Access.

- Site — https://vonkelveld.com
- Press & creator kit — https://vonkelveld.com/press/
- Steam — https://store.steampowered.com/app/4846840/
- Contact — info@vonkelveld.com

## ⚠ Every file here is GENERATED — do not hand-edit

Both pages are built from templates in the game's own (private) repository by
`scripts/build-press-kit.py`, which reads the screenshots, the eleven scenario premises and
the version number straight from the game's source of truth. Editing the HTML here would be
overwritten by the next build, and would silently drift from the game.

To change the site, edit the templates in the game repo and re-run the generator, then copy
`target/site/` over this repository.

Each page is one self-contained file with every image inlined, so there is no build step, no
asset pipeline and no dependency here — just static hosting.

© Software MoosS. The screenshots, logo and key art may be reproduced in coverage of
Vonkelveld; see the press kit for the full permission statement.
