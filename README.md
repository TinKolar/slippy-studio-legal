# Slippy Studio – legal pages

Static site served by GitHub Pages from `main` / root.

| Page | URL |
|---|---|
| Index | https://tinkolar.github.io/slippy-studio-legal/ |
| Slippy Rails privacy policy | https://tinkolar.github.io/slippy-studio-legal/slippy-rails/privacy/ |

## Adding a game

1. Copy `slippy-rails/privacy/` to `<game-slug>/privacy/` and rewrite it for that game's SDKs.
2. Add a card for it in `index.html`.
3. Put the URL in the game's settings screen **and** its store listing.

Keep URLs stable — they are baked into shipped builds and store listings. Update the
"Last updated" date whenever a policy's content changes.

`.nojekyll` turns off Jekyll processing; the pages are plain HTML.
