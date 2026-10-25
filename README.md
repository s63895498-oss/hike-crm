# Hike CRM

Installable web app (PWA) for Hike Advertising: daily closing, billing/invoices, salary, WhatsApp leads and proposals.

- Single-page app, no build step. Open `index.html` or serve the folder.
- Data is stored in each browser's localStorage (per device).
- Installable on phone/desktop ("Add to Home Screen" / "Install app"), works offline after first load.
- Deploys automatically to GitHub Pages on every push to `main`.

## Publish
```
git init -b main
git add .
git commit -m "Hike CRM"
git remote add origin https://github.com/<your-username>/hike-crm.git
git push -u origin main
```
Then on GitHub: Settings → Pages → Source: **GitHub Actions**. Live at `https://<your-username>.github.io/hike-crm/`.
