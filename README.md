# Vonkelveld website

The public game, company, support, privacy and press pages for **Vonkelveld**,
published by **Software MoosS (Pty) Ltd**, South Africa.

- GitHub Pages: https://bridgettegraham.github.io/vonkelveld-site/
- Intended custom domain: https://vonkelveld.com/ (requires DNS and HTTPS setup)
- Contact: info@vonkelveld.com
- Steam: https://store.steampowered.com/app/4846840/

## Generated sources

These pages and this README are generated from templates in the game's private
repository by `scripts/build-press-kit.py`. Edit those sources and regenerate;
copy `target/site/` into this repository and publish `main`.

Each HTML page contains its own styles and images. The home and press pages use
Google Fonts; the home page also embeds a YouTube trailer. Company, support and
privacy pages use system fonts and have no embedded third-party services.

GitHub Pages serves `main` from the repository root. Preserve any domain CNAME
file during regeneration. Custom-domain setup is documented in the game repo's
`docs/app-store/website.md`; preserve the domain's email records.

© 2026 Software MoosS (Pty) Ltd. The press kit states the permission for using game
screenshots and art in coverage of Vonkelveld.
