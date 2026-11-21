# Fight App — landings

Two landing pages in one static file, for design review:

- `index.html#global` — **Global web** (order book: prices in ¢, $1 per winning share, live 30s markets, rewards ranks).
- `index.html#us` — **US mobile app** (launching January 2027: chance % / American prices, prediction slip, parlays).

A floating REVIEW switch at the bottom flips between them (review only, not part of either site).

## Run

Open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Notes

- Fonts: ChakraPetchCustom 900 (+ italic) from the web team's build in `fonts/`; Chakra Petch, Geist and Geist Mono from Google Fonts.
- Prices, volumes and the order book are a snapshot of the web preview on Nov 20, 2026.
- Legal, partner and regional copy are placeholders pending review.
