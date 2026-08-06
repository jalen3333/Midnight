[README.md](https://github.com/user-attachments/files/30771367/README.md)
# Midnight Felt — standalone edition

Midnight Felt is a private, local-first home poker ledger. This edition has no ChatGPT dependency, account system, backend, analytics, external fonts, or third-party scripts.

## Use it locally

Open `index.html` in a modern browser. The current game is saved in that browser's local storage.

## Publish it

Upload `index.html` to any static web host. For GitHub Pages, put it at the root of a repository, enable Pages for the repository's main branch, and share the resulting URL.

The app works as a static site and needs no build step or environment variables.

## Data and privacy

- Game data stays in each user's browser.
- Different devices do not share a ledger.
- Use **Backup** to download a game and restore it elsewhere.
- Clearing browser storage removes the locally saved game unless a backup was downloaded.

## Money model

All amounts are whole US dollars. Decimal, negative, and unsafe values are rejected.
