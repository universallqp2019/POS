# Version 1.2.1 — build reliability notes

- All source files passed TypeScript transpilation syntax checks in the available environment.
- Full `tsc`/Vite/Electron packaging could not run here because npm dependencies were unavailable to install (network/runner timeout); therefore no claim of a successful EXE build is made.
- Windows GitHub Actions workflow now installs dependencies, checks types, builds and packages NSIS.
- Build instructions are in README.
- Included transactional SQLite operations: create sale, stock deduction, payments, customer due, void sale/stock restore, customer payment, expenses, date range report.
- Backups are manual via dashboard and restore replaces database after a confirmation prompt.

Remaining: complete purchase/supplier workflows, A4 invoice and reprint, customer ledger UI, product editing/archive and CSV import/export, stock adjustments, full profit reporting, production test suite and Windows installer validation.
