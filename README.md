# Automated Financial Reporting System

A fully automated, formula-driven financial reporting workbook built in Excel/Google Sheets. Enter journal entries once, and the Trial Balance, Balance Sheet, Profit & Loss, Statement of Changes in Equity, and Cash Flow Statement all recalculate automatically, with no macros and no manual linking required.

Built and maintained by **Aniruddha Sutradhar** ([Rudrix BPO](https://wa.me/8801570219399)).

---

## Features

- **Executive Dashboard** — colour-coded KPI cards (Revenue, Net Profit, Total Assets, Total Equity, Current Ratio, Net Profit Margin) with auto-updating charts
- **Fully Automated Reports** — Trial Balance, Balance Sheet, P&L, Changes in Equity, and Cash Flow Statement all flow from a single Journal Entries sheet
- **Built-in Control Checks** — every statement includes a balancing check that turns green (TRUE) or red (mismatch) automatically
- **Colour-Coded Cells** — instantly distinguishes inputs, formulas, and cross-sheet links
- **Cross-Platform** — works identically in Microsoft Excel and Google Sheets, with no macros, Apps Script, or add-ons
- **Double-Entry Bookkeeping** — every transaction is entered as a proper debit/credit journal voucher

---

## Sheet Map

| Sheet | Purpose |
|---|---|
| **Dashboard** | Executive KPI summary with charts (auto-calculated) |
| **Read Me** | In-workbook instructions and colour key |
| **Chart of Accounts** | Master list of every account and its behaviour in the reports |
| **Opening Balances** | Brought-forward balances at the start of the period (input) |
| **Journal Entries** | Every transaction of the period, double-entry style (input) |
| **Trial Balance** | Fully automated roll-up: Opening + Movement = Closing, per account |
| **Balance Sheet** | Statement of Financial Position, current vs. prior period |
| **Profit & Loss** | Income Statement |
| **Changes in Equity** | Movement in Share Capital, Reserves & Retained Earnings |
| **Cash Flow Statement** | Indirect method, tied back to the closing cash balance |

---

## How to Use

1. Open **Chart of Accounts** and review or extend the account list for your business. Tag every new account with a Category, Sub-Category, and Cash Flow Class.
2. Go to **Opening Balances** and enter the opening debit/credit balance for every Balance Sheet account as at the start of the reporting period (usually last period's closing Balance Sheet).
3. Enter every transaction on the **Journal Entries** sheet — Date, Voucher No., Account Code, Debit or Credit, Description. Each voucher must balance (Total Debit = Total Credit); Column I flags any line that doesn't.
4. That's it — **Dashboard**, **Trial Balance**, **Balance Sheet**, **Profit & Loss**, **Changes in Equity**, and **Cash Flow Statement** all recalculate automatically. Nothing else needs to be touched.

## Colour Key

| Colour | Meaning |
|---|---|
| Blue text | An input you type (journal entries, opening balances, account setup) |
| Black text | A formula or calculation — do not overtype |
| Green text | A value pulled or linked from another sheet in the workbook |
| Green fill | Control check passed (TRUE) |
| Red fill | Control check failed — find the error before trusting the reports |

## Compatibility

Every formula uses functions supported natively by both Microsoft Excel and Google Sheets (`SUMIFS`, `VLOOKUP`, `IF`, `ROUND`, `ABS`, `IFERROR`). No add-ons, macros, or Apps Script are required.

**To use in Google Sheets:** `File → Import → Upload this .xlsx file → Replace spreadsheet`

---

## Download

[Automated_Financial_Reporting_System.xlsx](./Automated_Financial_Reporting_System.xlsx)

## License

This project is licensed under the MIT License — see the [LICENSE](./LICENSE) file for details.

## Contact

For questions or custom workbook requests, reach out on WhatsApp: **[+880 1570-219399](https://wa.me/8801570219399)**
