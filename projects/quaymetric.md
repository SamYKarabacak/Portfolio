# Quaymetric Desktop

Offline finance, cash planning, and pricing for independent businesses. Quaymetric brings transactions, invoices, budgets, and forecasts into one local Windows workspace.

**1.0.0 · Windows 10 / 11, x64 · Independent personal project**

## Working with records

Record income, expenses, refunds, and invoice payments. Review outstanding invoice balances, compare budgets, and retain plans and opening balances by year.

Cash plans and forecasts distinguish missing inputs from zero. The pricing tools calculate break-even points and suggested prices. CSV import/export and JSON backups make records portable; Demo data stays separate from working records.

The desktop executable includes its runtime, so customers do not need Excel, Python, or Node.js.

## Calculations and storage

Built with JavaScript and Electron. Amounts use integer cents; pricing and forecast calculations use exact decimal rational arithmetic.

Local JSON storage supports atomic saves, revision checks, and recovery from a previous valid record. A restricted native bridge handles file operations.

## Current build

The source has 32 automated tests, including comparison against 200 independent Python Decimal pricing cases. Other checks cover invoice cutoffs, year retention, CSV round trips, backup/restore, and native bridge validation with simulated dialogs.

The portable Windows executable is packaged. Native Windows launch and real file-dialog checks remain pending.

Quaymetric is separate from the SBC products. Its commercial source repository is private.

[Portfolio](../README.md)
