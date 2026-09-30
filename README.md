# hael-legal

Source of truth for hæl's public policy text:

- `privacy.md` → hael.app/privacy
- `terms.md` → hael.app/terms
- `consumer-health-data.md` → hael.app/consumer-health-data

Edit here first, then regenerate the site pages from `82d2/hael-site`:

    python3 _tools/render_legal.py ../hael-legal

What the policy says must match `DATA.md` in `82d2/hael`, which maps every piece of data the app handles and where it goes.
