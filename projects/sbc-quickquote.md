# SBC QuickQuote

An offline Windows application for preparing itemized quotations, saving PDFs, and finding previous quotes when a customer comes back.

**1.0.0 · Windows 10 or later, x64 · Starkey Bridge Consulting LLC**

## From draft to PDF

Save a business profile, add the customer and line items, then enter discounts, tax, scope, and payment terms. Preview the document before saving a PDF through the native file dialog.

Saved quotations can be searched, edited, or duplicated. JSON backups include the business profile, quotations, and unfinished draft. Installer and portable editions use the same local profile for a Windows user.

## Technical details

HTML, CSS, and JavaScript in an Electron desktop application. Money uses integer arithmetic and explicit rounding rules, including currencies with different decimal precision. The renderer is sandboxed and communicates with native code through a restricted bridge.

The application runs without an account, subscription, or internet connection. Backups also support migration from the earlier web edition.

## Testing and distribution

The core and desktop-controller suite contains 27 tests covering calculations, validation, backups, resource access, navigation, and PDF handling. Renderer and packaging checks are recorded with the private source.

The Windows installer and portable package are built. Native Windows installation, launch, removal, and real file-dialog checks remain pending.

Commercial source and publisher tooling are private.

[Portfolio](../README.md) · [Publisher](https://starkeybridgeconsulting.com)
