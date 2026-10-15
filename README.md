# verso-cards.com

Static one-product site hosted on GitHub Pages at https://verso-cards.com.

## Updating the Stripe buy button

1. In the [Stripe Dashboard](https://dashboard.stripe.com/payment-links), create a **Payment Link** for your product (set price, shipping address collection, etc.).
2. Copy the link (looks like `https://buy.stripe.com/xxxx`).
3. In `index.html`, replace `STRIPE_PAYMENT_LINK` with that URL.
4. Commit and push — the site updates automatically.

## Updating content

- Product photo: replace `product.svg` with your image (and update the `<img>` tag in `index.html`).
- Price and copy: edit `index.html`.
- Styling: edit `styles.css`.

Deploys happen automatically on every push to `main`.
