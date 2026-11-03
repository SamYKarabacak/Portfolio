# SBC QuickQuote

**Prepare a quotation, keep the record, and save a PDF.**

An offline Windows quotation application for small businesses and independent service providers.

**Checkpoint:** 1.0.0 · **Platform:** Windows 10 or later, x64 · **Publisher:** Starkey Bridge Consulting LLC.

## Capabilities

- Save a business profile and prepare itemized quotations.
- Calculate line totals, quantities, discounts, and taxes with explicit rounding.
- Preview and save quotation PDFs through a native file dialog.
- Save, search, edit, and duplicate quotations.
- Export and restore JSON backups, including unfinished drafts.
- Run without an account, subscription, API key, or internet connection.

Installer and portable editions include the application runtime. They share the same local profile for a Windows user.

## Engineering

HTML, CSS, and JavaScript inside an Electron desktop application. Monetary calculations use integer arithmetic and explicit precision rules. A context-isolated, sandboxed renderer communicates through a narrow native bridge; packaged-resource and publisher-link allowlists restrict navigation.

Application data is stored locally. JSON backups support migration from the earlier web edition.

## Verification and status

**27 core and desktop-controller tests** passed again during the GitHub import on 3 November 2026. They cover arithmetic, validation, backup handling, packaged-resource policy, navigation, and the native PDF bridge with simulated dialogs. Previous renderer and packaging evidence remains with the private source.

The Windows installer and portable package have been built. Native Windows execution, installation, removal, and real-dialog acceptance remain pending. Controller mocks do not establish operating-system compatibility.

Commercial source and publisher tooling are maintained privately.

[Back to portfolio](../README.md) · [Publisher](https://starkeybridgeconsulting.com)
