# QuickBooks Online Chart of Accounts for Real Estate Investors

A ready-to-import chart of accounts for rental property owners and fix-and-flip investors who use QuickBooks Online (US).

It keeps the account list short and tracks each property with **classes** or **locations**, so you get a separate Profit & Loss for every property without creating a new set of accounts for each address.

## What's included

| File | What it is |
|---|---|
| chart-of-accounts.csv | 51 accounts with account number, name, type and detail type, ready for the QuickBooks Online import tool |

## How to import it into QuickBooks Online

1. Turn on account numbers: **Settings → Account and settings → Advanced → Chart of accounts → Enable account numbers**.
2. Go to **Settings → Import data → Accounts**.
3. Upload chart-of-accounts.csv and map the columns: Account Number, Account Name, Type, Detail Type.
4. Review the preview. If QuickBooks flags a detail type, pick the closest one from its list.
5. Import, then make inactive any default accounts you won't use.

> Retained Earnings and Opening Balance Equity are created by QuickBooks automatically, so they are not in the file.

## Track each property with classes or locations

- Turn on **Settings → Account and settings → Advanced → Categories → Track classes** (or locations).
- Create one class per property, for example "123 Oak St" and "45 Pine Ave".
- Tag every transaction with its property, then run **Profit and Loss by Class** to see each property's results.
- For flips, QuickBooks **Projects** work well for job costing too.

## Expense accounts follow Schedule E

The expense accounts follow the lines of IRS Schedule E (Supplemental Income and Loss), so your CPA can map the P&L straight to the return.

| Account | Schedule E line |
|---|---|
| 6000 Advertising | 5 |
| 6010 Auto & Travel | 6 |
| 6020 Cleaning & Maintenance | 7 |
| 6030 Commissions | 8 |
| 6040 Insurance | 9 |
| 6050 Legal & Professional Fees | 10 |
| 6060 Management Fees | 11 |
| 6070 Mortgage Interest | 12 |
| 6080 Other Interest | 13 |
| 6090 Repairs | 14 |
| 6100 Supplies | 15 |
| 6110 Property Taxes | 16 |
| 6120 Utilities | 17 |
| 8000 Depreciation Expense | 18 |
| 6130 HOA Dues, 6140 Software & Subscriptions, 6150 Bank Charges, 6160 Licenses & Permits | 19 (Other) |

## Fix-and-flip accounts

A flip is held for sale, not rented, so its costs are handled differently:

- The purchase price, closing costs and rehab costs go to **1310 Flip Properties - Work in Progress** (an asset), tagged with the property's class or project.
- When the property sells, the sale goes to **4100 Property Sales**, the selling costs to **5010 Selling Costs**, and the WIP balance moves to **5000 Cost of Property Sold**.
- Worked examples: [real-estate-bookkeeping-journal-entries](https://github.com/shoaibabu843-gif/real-estate-bookkeeping-journal-entries)

## Notes

- This is a starting point. Adjust it to your entity type and to how your CPA files your return.
- This is not tax advice. Confirm the tax treatment with your CPA.

---

**Need help setting this up?** I'm Md Abu Shoaib, a QuickBooks Online bookkeeper for real estate investors and property managers.
👉 [Hire me on Upwork](https://www.upwork.com/freelancers/~011eae234a1e1ba092)
