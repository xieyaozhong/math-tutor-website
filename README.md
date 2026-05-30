# Yao-Zhong Hsieh Mathematics Website

GitHub Pages 靜態網站專案

主軸：

- Mathematics Education
- Graph Theory
- Graph Labeling
- Publications
- Teaching Materials
- Academic CV

## Structure

```txt
math-tutor-website-upgraded/
├── index.html
├── styles.css
├── script.js
├── assets/
│   └── favicon.svg
├── README.md
└── .gitignore
```

## Deploy to GitHub Pages

```bash
git init
git add .
git commit -m "Upgrade academic mathematics website"
git branch -M main
git remote add origin https://github.com/xieyaozhong/math-tutor-website.git
git push -u origin main
```

Then open GitHub:

```txt
Settings → Pages → Deploy from a branch → main → /root
```

## Replace thesis link

In `index.html`, search:

```txt
Thesis Link
```

Replace this URL:

```txt
https://ndltd.ncl.edu.tw/
```

with your official thesis URL

## Replace material links

In `index.html`, search:

```txt
Coming Soon
```

Replace `href="#"` with PDF, GitHub, Google Drive, or Notion links
