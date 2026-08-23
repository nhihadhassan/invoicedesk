# InvoiceDesk

**Live demo:** https://invoicedesk-omega.vercel.app

A local-first freelance ledger for billable time, simple invoices, expenses, and payment status.

## Features

- Track client work with description, hours, rate, expenses, dates, and status
- See unbilled, outstanding, collected, and late totals
- Move entries through draft, sent, and paid states
- Export JSON or CSV data


## Stack

Plain HTML, CSS and vanilla JavaScript in a single `index.html` — no framework, no build
step, no dependencies. Open the file and it runs.

## Running locally

```bash
git clone https://github.com/nhihadhassan/invoicedesk.git
cd invoicedesk
open index.html          # or: python3 -m http.server 8000
```

There is nothing to install and nothing to configure.

## Why local-first

All state lives in the browser's `localStorage`. There is no account, no server and no
network call, so freelance invoicing data never leaves the machine it was entered on. The
trade-off is deliberate: data is per-browser, so the JSON export is the backup and the
way to move between devices.

## Licence

Released under the [MIT License](LICENSE).
