# Who asks for shots first? — a fake prediction market

A joke clone of Kalshi for a group of friends. One static HTML file, no backend,
no build step, no tracking. Every price, chart, sparkline and "trade" is generated
in the browser from a seeded random walk.

**Live:** https://riaku.github.io/kalshi-shots/

## What's on the page

One screen, no scrolling:

- **Who asks for shots first?** — Sessu, Jay, Axel, Carcar, Alazel, Fisk, with a
  live-ish line/candlestick chart for whichever name is selected.
- The right column lists all six prices with sparklines and Yes/No buttons that
  "fill" instantly and admit nothing happened.
- A bottom strip for the second market, **Who's gonna show up last?**, same six
  people, different odds.

The six prices always sum to exactly 100¢, the way a real multi-outcome market
would. Charts are Brownian bridges anchored at both ends, so the 24h change in
the header matches the 1D chart.

## Run it

Open `index.html`. That's the whole app.

## Not real

Not affiliated with Kalshi. Not a prediction market. Not financial advice. No real
money, no real odds, and no guarantee anyone actually ordered shots.
