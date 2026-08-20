# Affidavits

Editable and printable affidavit / declaration forms for HP Gas-related documentation.

The project is a single-page HTML application designed for easy data entry and A4 printing. It includes form validation, date fields, printable affidavit formatting, and reserved areas for franking / e-stamp and physical attestation where applicable.

## Available Forms

- Annexure A — Letter
- Annexure B — Affidavit
- Annexure C — Affidavit
- Annexure D — Affidavit
- Loss of Subscription Voucher — After Death
- Loss of Subscription Voucher — Consumer Alive
- No-Objection Certificate — Legal Heirs
- Self-Declaration — No Ration Card

## Features

- Editable fields directly in the browser
- A4 print-friendly layout
- Separate form selector for all available documents
- Current date automatically filled in the closing section
- Place shown before Date in the closing section
- Aadhaar number validation for 12 digits where applicable
- LPG ID validation for 17 digits in the Legal Heirs NOC
- Digit-only restrictions for validated numeric identification fields
- Reserved space for franking / e-stamp
- Reserved space for physical attestation / notary seal
- Print button for the selected form

## Live Website

GitHub Pages:

**https://cmswsa.github.io/Affidavits/**

## Repository

**https://github.com/cmswsa/Affidavits**

## Usage

1. Open the live website or download `index.html`.
2. Select the required form from the **Form** drop-down.
3. Fill in the required details.
4. Check all names, identification numbers, dates, and consumer details carefully.
5. Use the **Print Affidavit** button to print the selected document.
6. Complete any required signatures, franking, e-stamp, attestation, or notarization after printing.

## Local Use

No installation or server is required.

Download or clone the repository and open:

```text
index.html
```

in a modern web browser.

## GitHub Pages Setup

To publish this project using GitHub Pages:

1. Keep `index.html` in the root of the `main` branch.
2. Open the repository on GitHub.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select:
   - Branch: `main`
   - Folder: `/ (root)`
6. Save the settings.

The site should then be available at:

```text
https://cmswsa.github.io/Affidavits/
```

## Important Note

These templates are provided for document-preparation convenience. Requirements for LPG transfer, declarations, affidavits, legal-heir documentation, notarization, stamp duty, franking, identity proof, or distributor acceptance may vary. Verify the final document and supporting requirements with the concerned HP Gas distributor or appropriate authority before submission.

## Files

```text
Affidavits/
├── index.html
└── README.md
```
