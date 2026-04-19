# Mileage Matters — Website

Marketing and support website for Mileage Matters, a product of Ridgeline Digital LLC.

**Live site:** *(update this URL after you enable GitHub Pages)*

## Structure

- `index.html` — Landing page. What the app does, feature grid, how-it-works.
- `hardware.html` — Recommended OBD-II adapters. Amazon affiliate links with FTC-compliant disclosure.
- `support.html` — FAQs for users. Linked as the support URL in App Store Connect.
- `styles.css` — Shared stylesheet for all three pages. Dark navy + teal palette matching the app.

## Affiliate links

The Amazon links in `hardware.html` contain placeholder tags that read `tag=YOURAMAZONTAG-20`. Replace with your actual Amazon Associates tracking ID after your Associates account is approved.

The product URLs (`B01IC28IREPLACE`, etc.) are also placeholders — replace with the real ASIN of each adapter after you pick which models to recommend. To find the ASIN, look at the Amazon product URL; it's the 10-character alphanumeric ID after `/dp/`.

## FTC / Amazon disclosure

Per Amazon Associates terms and FTC guidelines, the affiliate disclosure is visible on the hardware page and footer. Do not remove it.

## Deploying

This site is deployed via GitHub Pages. To publish:

1. Go to the repo's **Settings** → **Pages**
2. Under **Source**, select branch `main` and folder `/ (root)`
3. Click **Save**
4. Wait ~1-2 minutes for the initial build
5. Your site will be live at `https://<your-github-username>.github.io/<repo-name>/`

## Custom domain (optional)

If you register `ridgelinedigital.com` or `mileagematters.app`:

1. Add a `CNAME` file in the repo root containing your domain
2. Configure DNS at your registrar (A records pointing to GitHub's IPs, or CNAME to `<username>.github.io`)
3. In GitHub repo **Settings → Pages**, enter the custom domain
4. Enable **Enforce HTTPS** once the cert is issued (takes a few minutes)

## Privacy policy

The privacy policy lives in a separate repo (`mileage-tracker-privacy`) so the policy URL stays stable even if this marketing site changes. Both sites link to each other.

---

© 2026 Ridgeline Digital LLC
