# EduPortal — Online Student Registration Portal

A responsive front-end student registration portal built with HTML5, Tailwind CSS, jQuery and JavaScript.

## Features

- Responsive registration form with accessible labels and browser-native required-field validation
- Additional validation for names, phone numbers and date of birth
- Live address character counter
- Optional browser-only save/restore using LocalStorage (requires explicit user opt-in)
- Registration summary with a generated reference number
- QR code containing only the reference number (no personal details)
- Edit registration details before printing
- Print-friendly receipt and downloadable PDF receipt
- Toast notifications and reduced-motion support

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Internet access is required for the CDN-hosted Tailwind CSS, jQuery, Font Awesome, Google Fonts, QRCode.js and jsPDF libraries.

You can also use VS Code Live Server for local development.

## Deploy with GitHub Pages

1. Push the repository to GitHub.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` folder, then save.
5. Open the published Pages URL after deployment completes.

## Important demo limitations

This is a **front-end portfolio demonstration**, not a production registration system.

- Form submissions are not sent to a server or institution.
- The generated registration reference and QR code are demo identifiers, not official verification.
- Optional LocalStorage keeps personal details in the current browser only. Do not enable it on a shared/public device.
- There is no authentication, database, email confirmation, or administrator dashboard.

## Technologies

HTML5 · Tailwind CSS · JavaScript · jQuery · Font Awesome · QRCode.js · jsPDF
