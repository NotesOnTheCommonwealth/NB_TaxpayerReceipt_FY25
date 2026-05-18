# New Bedford FY2025 Taxpayer Receipt

An independent taxpayer receipt for the City of New Bedford, Massachusetts. It
answers one question for a local household: where did a year of residential
property tax go in fiscal year 2025?

The receipt is modeled on the National Priorities Project's federal taxpayer
receipt. It reports **net local cost** — what city functions cost after revenue
that does not come from local taxpayers is removed — and it is addressed to a
**household**, owner or renter alike.

## What's in this repository

| File | Description |
|---|---|
| `index.html` | The interactive receipt. A single self-contained file — open it in any browser. Enter a home's assessed value and the receipt recalculates. |
| `methodology.md` | How the receipt is built and where every figure comes from. |
| `new-bedford-fy2025-receipt-data.xlsx` | The underlying database and an auditable spreadsheet version of the receipt, with every calculation as a visible formula. |

## Using the receipt

Open `index.html` in a web browser. No internet connection, server,
or installation is needed — everything runs locally in the page. Type a single-
family home's assessed value into the input field; the default is the FY2025
average single-family value of $393,323.

## The spreadsheet

`new-bedford-fy2025-receipt-data.xlsx` has three sheets:

- **Receipt** — the receipt reproduced with live formulas. Change the assessed
  value in the highlighted cell and every figure recalculates.
- **Data** — the database: every underlying figure with its source.
- **Notes** — how to use the workbook, a brief method summary, and sources.

Hardcoded inputs are shown in blue, formulas in black, and cross-sheet links in
green, so the workbook can be audited cell by cell.

## Key FY2025 figures

- Total governmental spending: $729.7M
- Total governmental revenue: $731.9M
- Net local cost across nine city functions: $211.9M
- Average single-family assessed value: $393,323; average bill: $4,448.48
- For every $1 of residential property tax the city collected, it took in $6.60 in total revenue

## Sources

Financial figures are audited or reconciled FY2025 actuals, drawn from the New
Bedford FY2025 ACFR (audited by Hague, Sahady & Co., CPAs), the Massachusetts
DESE FY2025 charter tuition reconciliation, the FY2025 Adopted Budget, and the
FY2025 Tax Rate Recapitulation. The average single-family assessed value is the
Massachusetts Department of Revenue's reported figure. See `methodology.md` for
figure-by-figure citations.

## Credit and disclaimer

An independent taxpayer receipt prepared by Mike Goodman, with analytical and
development support from Claude (Anthropic). Published at Notes on the
Commonwealth — <https://commonwealthnotes.substack.com>.

This is **not** a publication of the City of New Bedford, and it has not been
reviewed or endorsed by the City.

## License

Released under the MIT License — see `LICENSE`.
