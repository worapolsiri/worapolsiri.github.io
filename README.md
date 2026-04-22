# Worapol Siriburi — Portfolio Website

Static portfolio website built for GitHub Pages deployment.

## Structure

```
/
├── index.html          ← Main portfolio (About, Experience, Skills)
├── photo.png           ← Profile photo
├── cert/
│   ├── index.html      ← Certifications page (/cert)
│   └── badges/         ← Place your certificate badge images here
└── README.md
```

## Deploy to GitHub Pages

1. Create a new repo on GitHub (e.g. `yourusername.github.io` for root domain, or any name for `yourusername.github.io/repo-name`)
2. Push all files to the `main` branch
3. Go to **Settings → Pages → Source → Deploy from branch → main / root**
4. Your site will be live at `https://yourusername.github.io/`

## Add Real Certificate Badges

1. Create the `cert/badges/` folder
2. Add your badge images (e.g. `tryhackme-sec1.png`, `kwap-ta.png`)
3. In `cert/index.html`, uncomment the `<img>` lines and comment out the placeholder SVGs:

```html
<!-- Uncomment this: -->
<img src="badges/tryhackme-sec1.png" alt="TryHackMe SEC-1 Badge"/>

<!-- Comment out the SVG placeholder below it -->
```

## Navigation

- `/` or `/index.html` → Main portfolio
- `/cert/` or `/cert/index.html` → Certifications page
