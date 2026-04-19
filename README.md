# Moataz Web

Premium bilingual (Arabic/English) personal website shop landing page for selling custom websites and web solutions.

## Free deployment with GitHub Pages (works on mobile)

Yes — you can deploy this **for free** using GitHub Pages.

### 1) Push your repo to GitHub

```bash
git remote add origin https://github.com/<YOUR_USERNAME>/<YOUR_REPO>.git
git push -u origin work
```

### 2) Enable Pages (one-time)

1. Open your repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **GitHub Actions**.
4. Keep branch pushes to `work` or `main` (already configured).

### 3) Wait for deploy

- Open the **Actions** tab.
- Wait for **Deploy static site to GitHub Pages** to pass.
- First deployment usually takes 1–3 minutes.

### 4) Open on your phone

Your public URL will be:

```text
https://<YOUR_USERNAME>.github.io/<YOUR_REPO>/
```

You can share this link with clients directly.

---

## Local preview (optional)

```bash
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080/index.html
```

## Notes

- Default language is Arabic (RTL).
- Use the language switch button to toggle Arabic/English.
- Pricing values are intentionally placeholders so you can edit them manually.
