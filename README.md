# Yao-Zhong Hsieh Mathematics Website

更好看的學術型數學教學網站版本

## Features

- 學術型首頁
- 立體感圖論視覺
- 數學教學硬實力展示
- Research 區塊
- Publications 區塊
- Materials 區塊
- CV 區塊
- GitHub Pages 可直接部署

## Structure

```txt
math-tutor-website-beautiful/
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
git commit -m "Improve website visual design"
git branch -M main
git remote add origin https://github.com/xieyaozhong/math-tutor-website.git
git push -u origin main
```

若倉庫已經存在：

```bash
git add .
git commit -m "Improve website visual design"
git push
```

## Replace thesis link

In `index.html`, search:

```txt
Thesis Link
```

Replace:

```txt
https://ndltd.ncl.edu.tw/
```

with your official thesis URL

## Replace material links

Search:

```txt
Coming Soon
```

Replace `href="#"` with PDF, GitHub, Google Drive, or Notion links
