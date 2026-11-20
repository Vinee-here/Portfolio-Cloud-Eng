# Hosting Guide — Vinee Sawant's Portfolio

This portfolio is a **fully static, self-contained, lightning-fast** website with clean HTML, CSS, fonts, and assets. There are no external dependencies, database requirements, or build steps required.

## Quick Deployment Options

### 1. Vercel
1. Push your repository to GitHub (`https://github.com/Vinee-here/Portfolio-Cloud-Eng`).
2. Go to [vercel.com](https://vercel.com/) and click **Add New Project**.
3. Import your GitHub repository.
4. Leave build command empty and output directory as `./` (root).
5. Click **Deploy**.

### 2. GitHub Pages
1. Go to your repository settings on GitHub.
2. Under **Pages**, select **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`.
4. Click **Save**. Your site will be live at `https://vinee-here.github.io/Portfolio-Cloud-Eng/`!

### 3. Netlify
1. Log in to [Netlify](https://www.netlify.com/).
2. Drag and drop this folder directly into the Netlify Sites dashboard, or link your GitHub repo.
3. Publish directory: `./` (root).

---

## Local Development & Testing

To preview the website locally on your computer:

```bash
# Python 3
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.
