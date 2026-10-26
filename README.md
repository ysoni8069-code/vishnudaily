# Viishnu Daily — Reflection Ledger

A single-file, mobile-friendly daily journal (morning intentions + evening reflection + weekly review).
No build step, no dependencies, no server. Data is saved in the browser's `localStorage` on your device.

## Run locally
Open `index.html` in any browser.

## Host on GitHub Pages
1. Push this repo to GitHub.
2. **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
3. Choose branch `main`, folder `/ (root)`, and save.
4. Open the URL GitHub gives you (on iPhone: Share → Add to Home Screen).

## Vertical picklist (priority tags)
Defined in `index.html` in the `VERTICALS` array:

- General
- EMC / Salasar
- Jayesh Logistics Ltd
- Privin Projects Pvt Ltd
- Glocal Farms Pvt Ltd
- Prayatna Foundation
- Willow Ferro
- United Zambia Alloys Ltd
- RB Designs
- APD Insurance
- Ports / Waterways
- Personal

To add or rename a vertical, edit that array.

## Notes
- Entries are stored per browser/device; use **Download backup** in the footer regularly.
- Entries saved before the rename of "Jayesh Logistics", "Privin Projects", "Glocal Farms" and "Praytana (NGO)" will show those priority tags blank in the dropdown (the text itself is unaffected).
