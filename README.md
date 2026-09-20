# Mileage Matters — Website

Marketing and support website for Mileage Matters, a product of Ridgeline Digital LLC.

**Live site:** https://supermann-id.github.io/MileageMatters-site/

## Structure

- `index.html` — Landing page. Features, how-it-works, waitlist CTA (coming soon on the App Store).
- `hardware.html` — How tracking works (GPS distance, Core Motion, optional car Bluetooth vehicle recognition / auto-start). Kept filename for stable links; nav label is "How it works".
- `support.html` — FAQs for users. Linked as the support URL in App Store Connect.
- `privacy-policy.html` — Public privacy policy for the site and App Store Connect.
- `styles.css` — Shared stylesheet. Dark navy + teal palette matching the app.

## Product messaging (keep aligned)

- Distance is **GPS-derived only**.
- Auto trip detection uses **GPS + Core Motion + optional car Bluetooth** (vehicle stereo / hands-free) for recognition and auto-start. Never market plug-in vehicle adapters for reading dashboard mileage.
- Company name: **Ridgeline Digital LLC**.
- Waitlist: `mailto:ridgelinedigitalllc@gmail.com?subject=Mileage%20Matters%20waitlist`.

## Deploying

This site is deployed via GitHub Pages. To publish:

1. Go to the repo's **Settings** → **Pages**
2. Under **Source**, select branch `main` and folder `/ (root)`
3. Click **Save**
4. Wait ~1-2 minutes for the initial build
5. Your site will be live at `https://supermann-id.github.io/MileageMatters-site/`

## Custom domain (optional)

If you register `ridgelinedigital.com` or `mileagematters.app`:

1. Add a `CNAME` file in the repo root containing your domain
2. Configure DNS at your registrar (A records pointing to GitHub's IPs, or CNAME to `supermann-id.github.io`)
3. In GitHub repo **Settings → Pages**, enter the custom domain
4. Enable **Enforce HTTPS** once the cert is issued (takes a few minutes)

---

© 2026 Ridgeline Digital LLC
