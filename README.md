# Affidavits — GitHub Pages Hosting

This repository hosts the **Affidavits** web application as a static website using **GitHub Pages**.

The application runs entirely in the browser and does not require a server, database, or backend.

## Live Website

After GitHub Pages is enabled, the site will be available at:

**https://cmswsa.github.io/Affidavits/**

## Repository Structure

```text
Affidavits/
├── index.html
└── README.md
```

`index.html` contains the complete affidavit application.

## How to Host on GitHub Pages

1. Upload `index.html` and `README.md` to the root of the repository.
2. Open the repository on GitHub.
3. Go to **Settings**.
4. Select **Pages**.
5. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
6. Click **Save**.

GitHub will publish the website from the `main` branch.

## Website URL

For this repository:

```text
https://github.com/cmswsa/Affidavits
```

the GitHub Pages address is:

```text
https://cmswsa.github.io/Affidavits/
```

## Updating the Website

To publish a newer version:

1. Replace the existing `index.html` in the repository with the updated file.
2. Commit the change to the `main` branch.
3. GitHub Pages will redeploy the updated website automatically.

No changes to the Pages settings are normally required.

## Application Features

The hosted page includes editable and printable forms such as:

- Annexure A
- Annexure B
- Annexure C
- Annexure D
- Loss of Subscription Voucher — After Death
- Loss of Subscription Voucher — Consumer Alive
- No-Objection Certificate — Legal Heirs
- Self-Declaration — No Ration Card

The application also includes:

- Browser-based form entry
- A4 print layout
- Current-date support
- Place and Date fields
- Aadhaar number validation where applicable
- 17-digit LPG ID validation in the Legal Heirs NOC
- Print support
- Areas reserved for franking / e-stamp and physical attestation

## Local Testing

Before uploading to GitHub, you can test the website locally by opening:

```text
index.html
```

in Chrome, Edge, Firefox, or another modern browser.

## Important

This is a static document-preparation website. Users should verify all entered information and confirm the required supporting documents, stamp duty, notarization, attestation, or distributor requirements before submitting any affidavit or declaration.
