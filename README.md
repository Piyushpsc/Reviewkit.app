# Reviewkit

Reviewkit is a Chrome extension that extracts Google Play reviews and saves them as Excel on your computer. It does not upload those files to a server.

You pick one or more apps, set language, country, sort, and star rating, then start. Reviews are fetched in batches of 1,000 until Play has no more pages. Each Excel row is Rating, Review, Date, Developer Reply, and Found Helpful.

## What you can input

- **Apps** — open Play Store app tabs (detected automatically), or type a package name (`com.example.app`) or Play Store URL, then Add. Check or uncheck apps to include. Remove with ×.
- **Language** — review language (default English).
- **Country** — store country, or All (default).
- **Sort** — Newest, Most helpful, Highest rating, or Lowest rating.
- **Rating** — All stars, or only 1, 2, 3, 4, or 5 stars.
- **Excel output** — one file with a tab per app, or a separate file per app.

Timeout is fixed at 300 seconds of no progress. Delay between batches is 1200ms.

## Legal

- [Privacy Policy](PRIVACY.md)
- [Terms and Conditions](TERMS.md)
- [Copyright](COPYRIGHT.md)
