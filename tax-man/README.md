# Tax Man

A Grok Bot that gets your expense records ready for tax time.

## What it does
- Searches your Gmail for invoices and receipts from the tax year
- Logs each one in a Google Sheets spreadsheet (for example "2026 TAX PREP")
- Sorts expenses into categories and adds a summary tab with totals by category
- Flags anything it's unsure about instead of guessing
- Can keep checking for new receipts on a schedule you choose (see `routine.md`)

## Files
- [`instructions.md`](instructions.md): the bot's full instructions. Paste this as the description of a new Grok Bot
- [`first-task.md`](first-task.md): the first message to send it
- [`routine.md`](routine.md): an optional schedule for ongoing receipt checks
- [`spreadsheet-layout.md`](spreadsheet-layout.md): the columns and categories it uses

## Safety rules
- Read-only on email: it never pays, replies to, forwards, or deletes anything
- It organizes records but doesn't give tax advice
- It warns you before any large or long-running job

## Needs
- Gmail connected
- Google Drive / Sheets connected

## Get it
Template link: coming soon. For now, use `instructions.md`.

Built by Starship Alves.
