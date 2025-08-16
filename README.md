[README.md](https://github.com/user-attachments/files/21805160/README.md)
# AnyHelp Installation — Free Static Website

A clean, friendly one-page website for TV, computer, dishwasher, sound system, washing machine and dryer installation services.

## Files
- `index.html` — the page
- `styles.css` — styles (warm & friendly theme)
- `script.js` — mobile nav + email-based form submit
- You can add your logo by replacing the SVG in the header with an `<img>` tag.

## Quick preview
Open `index.html` in your browser.

## Free hosting options
### GitHub Pages
1. Create a new GitHub repository called `anyhelp-site`.
2. Upload `index.html`, `styles.css`, and `script.js` to the repo root.
3. In the repo settings → **Pages**, set **Source** to **Deploy from a branch**, pick `main` and `/root`.
4. Your site will appear at `https://<your-username>.github.io/anyhelp-site`.

### Netlify (drag-and-drop)
1. Go to Netlify and create a free account.
2. Drag the entire folder onto the Netlify app.
3. It will give you a live URL you can rename.

## Customising
- **Brand**: Update the brand name, phone and email in `index.html` (search for `AnyHelp`, `0434 745 608`, `info@anyhelp.com`).
- **ABN**: Replace the placeholder ABN in the footer.
- **Colours**: CSS variables at the top of `styles.css`. The theme uses warm oranges.
- **Pricing**: Edit the Pricing section in `index.html` to suit your rates.
- **Logo**: Swap the SVG logo in the header for your own logo (PNG/SVG).
- **Service area**: Update the FAQs to reflect your locations.

## Contact form options (free)
This site uses a `mailto:` approach to keep hosting 100% free. If you prefer a hosted form:
- **Formspree** or **Netlify Forms** offer free tiers. Replace `submitForm` with their examples.

## SEO basics
- The page includes a descriptive `<title>` and meta description.
- Add your suburb/areas in the copy for local SEO (e.g., Sydney CBD, Parramatta, Blacktown).

---

Made with ❤️ on 2025-08-15.
