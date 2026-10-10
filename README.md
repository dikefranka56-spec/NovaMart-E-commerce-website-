# NovaMart — E-commerce Portfolio Project

NovaMart is a responsive storefront demo built with **HTML, CSS, and vanilla JavaScript**. It is designed to demonstrate front-end development skills in a polished portfolio project.

> **Important:** This is a portfolio/demo project. It does not process real payments, send newsletter emails, save orders to a server, or connect to live inventory. Product data and checkout are simulated in the browser.

## Features

- Responsive layout for mobile, tablet, and desktop
- Product catalog with category filters, live search, and sorting
- Custom CSS product illustrations
- Shopping cart with quantity controls, remove item, subtotal, and session persistence
- Demo checkout form with required-field validation
- Simulated newsletter interaction
- Keyboard-friendly controls, labels, and status messages
- No framework or build step required

## Run locally

1. Download or clone this repository.
2. Open `index.html` in your browser.

Alternatively, with Python installed, run `python -m http.server 8000` in the project folder and visit `http://localhost:8000`.

## Publish using GitHub Pages

1. Create a public repository named `novamart`.
2. Upload `index.html`, `styles.css`, `app.js`, `README.md`, `.gitignore`, and the `assets` folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish. Copy the website URL displayed on the Pages settings screen.

## Security and production notes

- Never commit private API keys, passwords, payment secrets, database credentials, or customer data to a public repository.
- This frontend deliberately contains no API secrets.
- GitHub Pages serves static files only. It cannot execute PHP or host a database.
- For a real Paystack integration, a backend must initialize transactions and verify payments server-side. Store the secret key in the backend host's environment variables; never expose it in browser JavaScript or HTML.
- A production store also needs server-side validation, order persistence, inventory handling, appropriate privacy/security controls, and real customer support processes.

## Suggested portfolio polish

- Add screenshots of the home page, product filters, cart, and checkout preview.
- Add a short demo video or GIF.
- Include the live demo URL after deployment.
- Be ready to explain the cart state, filtering/sorting logic, responsive CSS, and what would change for production.

## Tech stack

HTML5 · CSS3 · Vanilla JavaScript · `sessionStorage`

## Project structure

```text
novamart/
├── index.html
├── styles.css
├── app.js
├── README.md
├── .gitignore
└── assets/
    └── favicon.svg
```
