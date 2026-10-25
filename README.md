# Kevin's wedding — a fake prediction market

A joke clone of Kalshi for a group of friends. One static HTML file, no backend,
no build step, no tracking. Every price, chart and "trade" is generated in the
browser from a seeded random walk.

**Live:** https://riaku.github.io/kalshi-shots/

## What's on the page

One compact betting board — all 11 questions from the wedding parlay form, no
scrolling on a desktop screen:

- Left: every question as its own market, with the leading outcomes priced in
  cents and a settled marker on the ones that already resolved.
- Right: the selected market's price chart, full outcome list and a Yes/No
  ticket that builds a multi-leg parlay with fake odds.
- Top: a ticker of settled results and live leaders.

Settled (results already known):

- Who's gonna vape during the ceremony — **Skippy**
- First to spill drink — **Apollo**
- First to cry — **Mackie**
- Who asks for shots first — **Sessu**

Still open: most drunk, ask to take over the decks, worst dressed, fall down
stairs, get cut off from the bar, first to go to bed, show up last.

Open-market prices always sum to exactly 100¢, the way a real multi-outcome
market would. Charts are Brownian bridges anchored at the current price, so the
change in the list matches the 1D chart.

## Run it

Open `index.html`. That's the whole app.

## Not real

Not affiliated with Kalshi. Not a prediction market. Not financial advice. No
real money, no real odds, and no guarantee anyone actually ordered shots.
