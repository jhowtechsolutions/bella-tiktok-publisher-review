# GitHub Pages — Manual Deploy

Deploy the public App Review site for **BELLA TikTok Publisher**.

## Prerequisites

- GitHub account
- Contents of this folder (`github-pages-site/`)

## Steps

### 1. Create a public GitHub repository

Name: **`bella-tiktok-publisher-review`**

Do not initialize with README if you will push this folder directly.

### 2. Upload this folder contents

Push or upload **only** these files to the repository root:

- `index.html`
- `privacy.html`
- `terms.html`
- `styles.css`
- `README.md`

Example:

```bash
cd github-pages-site
git init
git add index.html privacy.html terms.html styles.css README.md
git commit -m "Initial public review site"
git branch -M main
git remote add origin https://github.com/<github-user>/bella-tiktok-publisher-review.git
git push -u origin main
```

### 3. Open GitHub Pages settings

Repository → **Settings** → **Pages**

### 4. Build and deployment

**Source:** Deploy from a branch

### 5. Branch

**main**

### 6. Folder

**/ (root)**

### 7. Save

Click **Save**.

### 8. Wait for live URL

GitHub displays:

> Your site is live at …

Expected format:

```
https://<github-user>.github.io/bella-tiktok-publisher-review/
```

Replace `<github-user>` with your GitHub username.

---

## URLs for TikTok Developer Portal

| Field | URL |
|-------|-----|
| Website | `https://<github-user>.github.io/bella-tiktok-publisher-review/` |
| Privacy Policy | `https://<github-user>.github.io/bella-tiktok-publisher-review/privacy.html` |
| Terms of Service | `https://<github-user>.github.io/bella-tiktok-publisher-review/terms.html` |

---

## Verify after deploy

- [ ] Landing page loads over HTTPS
- [ ] Privacy and Terms links work from index
- [ ] Back links to index work from Privacy/Terms
- [ ] No 404 on `styles.css`
- [ ] Mobile layout acceptable

---

## Security reminder

Never add to this repository:

- `.env` files
- TikTok Client Key or Client Secret
- OAuth tokens
- Internal documentation or runtime logs
