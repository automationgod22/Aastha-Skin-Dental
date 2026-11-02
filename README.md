# Aastha Skin & Dental Clinic, Latur

Website for Aastha Skin & Cosmetology Clinic and Aastha Dental, Dental Aesthetics & Laser Clinic
(Dr. Ravi Tapdia & Dr. Priyanka Tapdia), Suhana Chambers, Chandra Nagar, Latur.

Static site, no build step: `index.html` + `media/`.

## Deploy on Vercel
1. Import this repo in Vercel.
2. Framework preset: **Other**. Leave build command and output directory empty.
3. Deploy. Every push to `main` redeploys.

## Edit
- Clinic hours: `SLOTS` and `OPEN_DAYS` in the script at the bottom of `index.html` (minutes since midnight, India time), plus the hours table in the Visit section.
- Concern finder content: the `CONCERNS` array in the same script.
- WhatsApp number: `WA` constant in the script.
- Colours: light and dark theme tokens at the top of the `<style>` block. The theme follows the visitor's device setting; the moon/sun button in the header overrides it and is remembered.
