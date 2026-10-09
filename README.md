# TEHFL Website V1

GitHub Pages-ready foundation for TEHFL, with the Jaymie / SIGNAL pathway built first.

## Included
- `index.html` — TEHFL home
- `signal.html` — SIGNAL public page
- `front-door.html` — SIGNAL participant Front Door review
- `styles.css` — shared visual language
- `assets/` — SIGNAL visual assets
- `.nojekyll` — GitHub Pages compatibility

## Publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload the contents of this folder to the repository root.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch**.
5. Select `main` and `/ (root)`.
6. Save.

## Current boundary
The site is functional as a front-end review build. It does not yet send registration data, email, or SMS.

Next integration layer:
- live Google Sheet/database write endpoint
- event registration destination
- confirmation email
- SMS reminders
- attendance/no-show routing
- post-event follow-up
