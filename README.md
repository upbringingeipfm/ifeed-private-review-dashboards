# iFeed Private Review Dashboards Deploy Folder

This folder is for the private raw-signal review dashboard site.

Deploy this folder to the private Netlify project, not to the public Weekly Signals site:

```text
outputs/private-review-dashboards-netlify
```

## Structure

- `index.html` is the archive page for weekly private dashboards.
- `weeks/w24/index.html` is the W24 raw signal review dashboard.
- `weeks/w24/all_raw_signals_review.json` is the W24 source data export.
- `_redirects` adds short W24 routes.

## Future Weeks

For each new week:

1. Create `weeks/wXX/`.
2. Add that week dashboard as `weeks/wXX/index.html`.
3. Add the JSON/data files beside it.
4. Add a card to root `index.html`.
5. Deploy the full `private-review-dashboards-netlify` folder.

