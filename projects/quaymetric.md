# Quaymetric Desktop

**Offline finance, cash planning, and pricing for independent businesses.**

A standalone Windows application that brings transactions, invoices, budgets, forecasts, cash plans, and pricing into one local workspace.

**Checkpoint:** 1.0.0 · **Platform:** Windows 10 / 11, x64 · **Project:** Independent personal software.

## Capabilities

- Record income, expenses, refunds, and invoice payments.
- Review invoice balances and date-based cutoffs.
- Compare budgets and retain plans and opening balances by year.
- Build cash plans and forecasts with explicit handling of missing inputs.
- Explore break-even and pricing calculations.
- Import and export CSV; save and restore local JSON backups.
- Use separate Demo and working records.

Customers do not need Excel, Python, Node.js, an account, or an internet connection.

## Engineering

JavaScript and Electron with local JSON storage, atomic saves, revision checks, and recovery from a previous valid record. Amounts use integer cents; pricing and forecasts use exact decimal rational arithmetic. The renderer uses a restricted native message bridge for local file operations.

Quaymetric is separate from the SBC products and retains its own branding and license.

## Verification and status

**32 automated tests** passed again during the GitHub import on 3 November 2026, including comparison against **200 independent Python Decimal pricing cases**. Coverage includes calculations, year retention, invoice cutoffs, CSV round trips, backup/restore, revision checks, and native bridge validation with simulated dialogs.

The portable Windows executable is built. Native Windows launch and real file-dialog acceptance remain pending. Previous browser-preview checks do not establish Windows execution.

The commercial source repository is private. Product and third-party licenses remain separate.

[Back to portfolio](../README.md)
