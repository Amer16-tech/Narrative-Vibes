# Narrative Vibes — AdSense-ready static site

This repo is a static multi-page website prepared with elements commonly required for Google AdSense review:

- Multiple pages (articles, reviews, poetry, stories) with sample content.  
- Privacy Policy, Contact, and Terms pages.  
- Cookie consent banner (simple) to let users accept cookies.  
- `ads.txt` placeholder to declare authorized sellers (replace publisher id).  
- `sitemap.xml` and `robots.txt`.  
- Placeholder AdSense script and ad slots in HTML (replace `ADSENSE_CLIENT_ID` and `AD_SLOT_ID`).

## How to use
1. Download and unzip. Upload files (not the zip) to your GitHub repository `narrative-vibes`.
2. Deploy to Vercel (static site; no build required).
3. Replace placeholders:
   - `ADSENSE_CLIENT_ID` in HTML with your AdSense publisher ID (e.g. `ca-pub-1234567890123456`).
   - `AD_SLOT_ID` for each ad slot if you create ad units in AdSense.
   - `ads.txt` -> replace `pub-REPLACE_WITH_YOUR_PUBID` with your publisher id.
   - Update contact email and real content.
4. Apply for AdSense and submit site for review. Google looks for: original content, clear navigation, privacy policy, contact page, and sufficient content across pages.

## GitHub Actions / Vercel
A GitHub Actions workflow is included at `.github/workflows/deploy.yml` to deploy using the Vercel CLI. Add these repo secrets for automated deploys:
- `VERCEL_TOKEN`
- `VERCEL_ORG_ID`
- `VERCEL_PROJECT_ID`

## Notes on AdSense readiness
- Add at least 10-20 high-quality articles before applying for AdSense for better approval chances.
- Ensure Privacy Policy accurately describes ad usage and data collection.
- Confirm site loads correctly on desktop and mobile.
- Avoid copyrighted content you don't own.

---
© 2025 Narrative Vibes
