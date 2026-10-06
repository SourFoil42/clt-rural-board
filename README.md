# CLT Rural Property Board

Luke Wolfe’s filterable Track A / B / C rural property search board (Charlotte metro).

## Open

**Option A — local server (recommended)**

```bash
cd clt-board
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080).

**Option B — open the file**

Open `index.html` directly in a browser (`file://`). Listings are embedded for offline use; `data/listings.json` and `images/` are also present for editing.

## Contents

| Path | Purpose |
|------|---------|
| `index.html` | Single-page filterable board |
| `data/listings.json` | Structured listing data |
| `images/` | Local listing photos (relative paths) |

## Filters

Tracks A/B/C (multi-select), status, max price, min acres, min sqft (houses), 2-car garage, no HOA, year 2016+, sort, and address/city search.

## Data note

Data as of **Tue Oct 6, 2026 ~8:39 AM ET**. Statuses change — verify live on each listing URL.
