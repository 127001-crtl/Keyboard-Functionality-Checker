# Keyboard-Functionality-Checker
Checks the functionality of your keyboard keys through the use of Three.js and a 3D interactive model.

## Three.js environment setup

Install dependencies:

```bash
npm install
```

Start local development server:

```bash
npm run dev
```

Create a production build:

```bash
npm run build
```

## GitHub Pages deployment

This repository includes a GitHub Actions workflow at `.github/workflows/deploy.yml` that deploys the Vite `dist/` output to GitHub Pages on every push to `main`.

To publish on `rafaelk.me`:

1. In GitHub, open **Settings → Pages** for this repository.
2. Set **Source** to **GitHub Actions**.
3. Point your domain DNS to GitHub Pages (A/AAAA records or ALIAS/ANAME for apex domain).
4. Wait for DNS to propagate; GitHub Pages will then serve the site from `https://rafaelk.me`.

The custom domain is configured through `public/CNAME` and included in each build.
