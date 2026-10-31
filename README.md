# AGNY Live Dashboard

A live client dashboard page for A. Gutierrez Law Firm, P.C., designed to be hosted on GitHub Pages.

## How it works

- `index.html` is the page. It holds no status data of its own.
- `data.json` holds every status, date, and number the page shows.
- When the page opens, it fetches `data.json` fresh, so updating the dashboard means editing `data.json` only and committing it. Alex's link never changes and there is nothing to re-share.

## Updating

1. Edit the relevant fields in `data.json` (step statuses, Week 0 items, the `updated` date, fee status, shoot details).
2. Commit and push `data.json` to the hosting repo.
3. The change is live on Alex's next page load.

## Rules that apply to edits

- Client facing copy: plain language, full sentences, no internal notes, no em dashes.
- Fee is always one package: The Digital Authority Engine, $6,000 per month, all in. Spanish remakes are included, never a separate line item.
- The $5,000 received and $1,000 Month 1 balance appear only as payment status.
