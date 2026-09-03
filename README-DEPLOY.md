# Catalyst Alerter website — GitHub Pages deployment

This folder is ready for static hosting.

## Recommended option: GitHub Pages from the existing repository

1. Copy these files into the repository root:
   - index.html
   - styles.css
   - sms.html
   - privacy.html
   - terms.html

2. Commit and push them to the `main` branch.

3. In GitHub, open:
   Settings → Pages

4. Under "Build and deployment":
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/ (root)`

5. Save. GitHub will provide a public Pages URL.

For this repository the URL will normally be similar to:
`https://k3v1njk.github.io/Catalyst_Alerter/`

Use the actual live Pages URL in the AWS company-website field.

## Before submitting to AWS

- Open every page in an incognito/private browser and confirm it is public.
- Make sure the project/brand name in AWS matches "Catalyst Alerter".
- Make sure the SMS-use description in AWS matches the website.
- Do not claim to have an LLC/corporation if you do not.
- If AWS asks for an email contact, add a real monitored email address to the website before submitting.
- If your messaging model later changes from "operator only" to public subscribers, update the SMS Use, Privacy, and Terms pages first.

## Optional improvement

A custom domain looks more professional but is not required for GitHub Pages itself. If you later buy a domain, GitHub Pages can host this same site under that domain.
