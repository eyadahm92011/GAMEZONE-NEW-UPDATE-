# GAMEZONE

A static gaming storefront and mini-game. GitHub Pages will deploy the site automatically from the main branch after the included workflow is added.

## Setup

1. In **Settings → Pages**, set the publishing source to **GitHub Actions**.
2. Add this site's github.io hostname to Firebase Authentication's Authorized domains before using sign-in.
3. Review EmailJS allowed origins and Firebase rules before sharing the site.

## Checkout status

This is a static storefront. The current email verification code is generated and checked in the browser, so it is not a secure production OTP flow. Prices, points, and discounts are also browser-side demo values. Do not use them as authoritative order or payment controls.

Do not commit private keys or .env files. The EmailJS private key shown in an earlier screenshot should be rotated. The checkout backend is not included in this static site.
