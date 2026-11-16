# Universal Computers POS — v1.2.1
Offline POS project for Universal Computers, Madina Market, Liaquat Pur, Pakistan. PKR.

## Current milestone
SQLite foundation, catalog/customer basic operations, transactional checkout, stock deduction/movement log, customer payment, sale void/reversal, expenses, date-range sales summary, and manual database backup/restore.

## Build on Windows (recommended)
Install Node.js 20 LTS. Open PowerShell in this folder:
1. `npm install --no-audit --no-fund`
2. `npm run check`
3. `npm run build`
Installer: `release/Universal Computers POS Setup 1.2.1.exe` (name can vary by electron-builder).

The database is kept in Electron's per-user app data folder, not the installation directory. Shop phone numbers: 0301-7638214 / 0308-7653188.

## Current limitations
This is a developing MVP, not a fully finished accounting system. A4 invoice/reprint, purchase receiving/suppliers, stock adjustment and import/export, full customer ledger UI, profit/P&L and broad automated tests are not complete. Keep independent backups and verify all balances before live use.
