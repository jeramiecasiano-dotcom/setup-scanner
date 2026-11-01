# Setup Scanner

A phone-friendly dashboard that lists intraday setups (levels, entries, stops, take-profits) for a small list of tickers, graded by how many sources agree.

**Information only. This is not financial advice.** A grade measures agreement between sources, not a proven edge. Nothing here places orders or touches any account.

- `index.html`, `manifest.json`, icons: the static page (works under a subpath, installable on a phone home screen)
- `data.json`, `status.json`: refreshed automatically every 5 minutes during US market hours (8:30 AM to 3:00 PM CT, weekdays), only when the data changed
