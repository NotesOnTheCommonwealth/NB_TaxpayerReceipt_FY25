# Methodology — New Bedford FY2025 Taxpayer Receipt

This document explains how the receipt is built and where every figure comes
from. It describes the finished method, not the steps taken to arrive at it.
Fiscal year 2025 runs July 1, 2024 through June 30, 2025.

## What the receipt does

The receipt answers one question: for a New Bedford household, where did a
year of residential property tax go? It is modeled on the National Priorities
Project's federal taxpayer receipt, which translates the national budget into
a single taxpayer's share. The same logic is applied here to one city and one
fiscal year.

Two choices shape everything that follows. First, the receipt reports **net
local cost** — what city functions cost after revenue that does not come from
local taxpayers is removed — rather than gross spending. Second, it traces a
single tax: the **residential property tax**, the largest local tax and the
one a household can personalize from its own assessed value.

## Sources

Every figure is drawn from a primary document.

- **New Bedford FY2025 Annual Comprehensive Financial Report (ACFR)**, audited
  by Hague, Sahady & Co., CPAs. The Statement of Activities (p. 24) supplies
  governmental spending, program revenue, and revenue by source; the pension
  and OPEB notes supply benefit liabilities; the assessed-value-by-class table
  (p. 144) supplies the property tax base by class.
- **Massachusetts DESE FY2025 charter school tuition reconciliation** — the
  reconciled year-end charter tuition assessment and state reimbursement for
  New Bedford.
- **New Bedford FY2025 Adopted Budget** — employee benefit appropriations.
- **New Bedford FY2025 Tax Rate Recapitulation** — the certified residential
  and commercial tax rates.
- **Massachusetts Department of Revenue** — the average single-family assessed
  value, as presented at New Bedford's FY2025 tax classification hearing.

The financial figures are audited or reconciled FY2025 actuals. The one input
that is not an audited figure is the average single-family assessed value: it
is the Department of Revenue's reported value, used only as the calculator's
default, and a household that enters its own assessed value replaces it.

## The household figure

The calculator starts from a home's assessed value and applies the FY2025
certified residential rate of **$11.31 per $1,000** (Tax Rate Recapitulation).
The default value is the **$393,323** average single-family assessed value
reported by the Massachusetts Department of Revenue and presented at New
Bedford's FY2025 tax classification hearing. At that value the residential
property tax is **$4,448.48** — the receipt's headline figure. A household
that enters its own assessed value sees its own figure.

The receipt covers residential property tax only. Motor vehicle excise and
other local revenue are real taxes and charges, but they are not in the
household figure; they appear in Section 1 as city revenue sources. Property
tax is the largest local tax and the only one a household can compute from a
number it already has.

## Section 1 — Where the city's money came from

New Bedford's total governmental revenue in FY2025 was **$731,935,201** (ACFR,
p. 24). The receipt breaks it into seven sources, ranked largest to smallest:

| Source | FY2025 amount |
|---|---:|
| State & federal grants and charges for service | $516,934,715 |
| Residential property tax | $110,928,037 |
| Commercial, industrial & personal property tax | $44,151,002 |
| Unrestricted state aid | $22,033,642 |
| Other local revenue | $20,066,710 |
| Motor vehicle & other excise | $9,837,910 |
| Net transfers from enterprise funds | $7,983,185 |

The receipt anchors this on residential property tax. For every dollar of
residential property tax the city collected, it took in **$6.60** of total
revenue — the other $5.60 from commercial property, fees, state aid, and
federal grants. The benchmark is the citywide total, not one household's bill.
The point is the scale of outside funding: local residential tax is a small
part of what pays for city government.

**The property tax split.** Total property tax revenue, net of abatements, was
$155,079,039 (ACFR, p. 24). The residential share of the levy is **71.53%**,
derived from the assessed-value-by-class table (ACFR, p. 144): residential
assessed value of about $9.819 billion of the $11.753 billion total, taxed at
$11.31 against the $22.85 commercial/industrial/personal rate. Applying that
share yields residential property tax of $110,928,037 and commercial,
industrial, and personal property tax of $44,151,002.

## Section 2 — What your property tax funded

Net local cost across the nine governmental functions totals **$211,903,120**.
Eight functions carry positive net local cost; their total, **$212,062,221**,
is the base across which a household's property tax is distributed.

| City function | Net local cost | Outside-funded |
|---|---:|---:|
| Public safety | $58,399,969 | 29.9% |
| Education — New Bedford Public Schools | $51,811,767 | 87.8% |
| General government | $42,437,791 | 19.1% |
| Charter school tuition assessment | $24,367,836 | 20.5% |
| Public works | $17,413,997 | 82.8% |
| Interest on long-term debt | $7,917,990 | 0.0% |
| Culture & recreation | $6,523,963 | 25.7% |
| Health & human services | $3,188,908 | 70.5% |
| Community & economic development | $0 | fully grant-funded |

Each household's property tax is distributed across the eight positive
functions in proportion to net local cost. For the average single-family home,
the $4,448 property tax resolves into about $1,225 for public safety, $1,087
for education, and the balance across the other functions.

## Methodological choices

### Net local cost, not gross spending

Gross spending overstates the local burden for any function that draws heavily
on outside money. Education is the clearest case: New Bedford Public Schools'
gross cost is largely met by Chapter 70 and other restricted education aid, so
87.8% of it is outside-funded and only the remainder falls to local revenue.
Community and economic development is funded almost entirely by federal
CDBG/HUD grants; its net local cost is effectively zero. Reporting gross
spending would attribute those outside dollars to local taxpayers. Net local
cost — gross expense less program revenue and restricted aid — isolates the
part local revenue actually carries.

### Charter school tuition

New Bedford's charter school tuition assessment is separated from New Bedford
Public Schools and shown as its own function. The DESE FY2025 reconciliation
puts the gross assessment at $30,659,589 and the state charter reimbursement
at $6,291,753, for a net of $24,367,836. The reimbursement is attributed to
charter tuition as its offset rather than left in unrestricted state aid. This
keeps a cost and its dedicated funding together, and it avoids overstating
discretionary state aid.

### Residential share of the levy

Because New Bedford uses a split tax rate, the residential and
commercial/industrial/personal classes are taxed at different rates and bear
different shares of the levy. The 71.53% residential share is computed from
the ACFR assessed-value-by-class table (p. 144), applying each class's
assessed value and certified rate. It is not assumed; it is derived from the
audited base. The companion spreadsheet carries those assessed values and
rates and computes the share as a live formula.

### Employee benefits as a cross-cut

Employee pensions and health insurance are not a separate function on the
receipt; they sit inside every function's net cost. To make their scale
visible, the receipt notes them as a cross-cut: in FY2025 the city put about
$40.7M toward pensions and about $36.6M toward health and related insurance —
roughly $77M, close to a tenth of city spending. The retiree-health obligation
is largely unfunded: the city reports roughly $510M in long-term OPEB
liability with under 2% set aside. Benefit figures are shown on a cash basis.
The GASB 75 OPEB accounting expense for FY2025 was negative, an artifact of
favorable actuarial assumption changes, and is not used.

### Property tax and renters

The receipt is addressed to households, owners and renters alike. Rental
housing is taxed at the residential rate, and renters carry a large share of
that tax bill through their rent — so the receipt is relevant to renting
households, not only to owners.

## Limitations

- The receipt is a single-year snapshot of FY2025. It does not show trends.
- The calculator's default is the average single-family home. New Bedford's
  housing stock also includes many multi-family homes and condominiums, which
  carry different assessed values; the receipt anchors on the single-family
  benchmark, the standard measure every Massachusetts municipality reports.
- Net local cost and outside-funded shares are computed on the ACFR's accrual
  (GAAP) basis. Budget-basis figures are not interchangeable with them.
- Function shares in the published receipt are rounded to whole percents; the
  companion spreadsheet shows them to one decimal.

## Reproducing the receipt

The companion spreadsheet, `new-bedford-fy2025-receipt-data.xlsx`, holds
every figure with its source on the Data sheet and reproduces the receipt's
calculations as live, visible formulas on the Receipt sheet. Change the
assessed value and the full receipt recalculates. The New Bedford FY2025 ACFR
is a public document and is the primary source for all financial figures.

---

*An independent taxpayer receipt prepared by Mike Goodman, with analytical and
development support from Claude (Anthropic). Published at Notes on the
Commonwealth — https://commonwealthnotes.substack.com. Not a publication of the
City of New Bedford, and not reviewed or endorsed by the City.*
