# Tax Man

A Grok Bot that gets your expense records ready for tax time.

## What it does
- Searches your Gmail for invoices and receipts from the tax year
- Logs each one in a Google Sheets spreadsheet (for example "2026 TAX PREP") with Date, Vendor, Description, Category, Amount, Currency, Sales tax (HST/GST) if shown, Invoice #, and a link back to the email
- Sorts expenses into categories like Subscriptions & Software, Utilities & Phone/Internet, Equipment & Electronics, Office Supplies, Travel, Meals, Professional Services, and Other
- Adds a summary tab with totals by category
- Flags anything it's unsure about instead of guessing
- Can keep checking for new receipts on a schedule you choose

## Safety rules
- Read-only on email: it never pays, replies to, forwards, or deletes anything
- It organizes records but doesn't give tax advice
- It warns you before any large or long-running job

## Needs
- Gmail connected
- Google Drive / Sheets connected

## Get it
Template link: coming soon

Built by Starship Alves.
