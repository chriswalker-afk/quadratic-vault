# Quadratics Arcade

Six interactive games designed for **Edexcel International GCSE Mathematics A (4MA1) Foundation**.

## Play

**[Open Quadratics Arcade](https://chriswalker-afk.github.io/quadratic-vault/)**

### D11 — Factorising quadratics
- [Quadratic Vault](vault.html): factor pair challenges, missing factors and secret pictures
- [Factor Factory](factor-factory.html): construct the brackets using signed-number tiles
- [Quadratic Builder](quadratic-builder.html): reverse-engineer quadratics from constraints

### D12 — Solving by factorising
- [Root Rescue](root-rescue.html): single-player mission with guided factorising and finding roots
- [Quadratic Connect Four](quadratic-connect-four.html): two-player hot-seat game
- [Quadratic Conquest](quadratic-conquest.html): strategic hot-seat game for two to four players

## Development

The site is static HTML, CSS and JavaScript and needs no build step. The landing page is `index.html`; all game links are relative so the site also works when served locally.

To run the automated Root Rescue mathematics tests with Node.js:

```sh
node tests/root-rescue.test.cjs
```

## GitHub Pages

For the first deployment, in **Settings → Pages**, select **Deploy from a branch**, branch `main`, folder `/(root)`. This project is separate from all other teaching websites.
