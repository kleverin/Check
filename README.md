# Kevin Biju Mathew — Portfolio (GitHub Pages)

This repo contains my portfolio website (based on the **vCard** template by CodeWithSadee).

## Deploy on GitHub Pages (recommended)

**Option A — user/organization site (clean URL):**
1. Create a repo named: **`<your-username>.github.io`**
2. Upload/push the contents of this folder to that repo.
3. GitHub Pages will publish it automatically at: `https://<your-username>.github.io`

**Option B — project site:**
1. Create a repo with any name (e.g., `portfolio`).
2. Push the contents of this folder.
3. Go to **Settings → Pages** and set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or `master`) + `/ (root)`

## Local preview

Open `index.html` in a browser, or run a simple local server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customize

- Update profile photo: `assets/images/my-avatar.png`
- Update project links/cards: `index.html` → **Portfolio** section
- Update research items: `index.html` → **Research & Publications**
- Replace the CV PDF: `assets/docs/Kevin_Biju_Mathew_CV.pdf`

---

Template: https://github.com/codewithsadee/vcard-personal-portfolio (MIT)
