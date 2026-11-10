# VML Hub Studio Payments

Standalone public homepage and privacy policy for the VML Hub payment/email service.
This site is separate from the Wan Studio Pro checkout redirect repository.

## Publish on GitHub Pages

Repository: `vmlhub/studio-payments` (public).

Publish from `main`, `/(root)`, using GitHub Pages' **Deploy from a branch** setting.
The site is static HTML/CSS, needs no build, and contains no credentials, order data,
customer information, tracking scripts, or Google OAuth tokens.

Expected public URLs after publishing:

- Homepage: `https://vmlhub.github.io/studio-payments/`
- Privacy policy: `https://vmlhub.github.io/studio-payments/privacy.html`

Use these URLs in Google Auth Platform → Branding only after both return HTTP 200.
Publishing these pages does not itself verify domain ownership or publish the Google
OAuth app. Complete any ownership or verification steps Google requests separately.

## Files

- `index.html`: public application homepage with service explanation and support links.
- `privacy.html`: purchase/email-service privacy policy and Google API Limited Use disclosure.
- `styles.css`: shared responsive styling, including dark color-scheme support.
- `.nojekyll`: serve the static files directly.

Update the policy if the service's data handling or email providers change.
