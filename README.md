# 謝曜仲｜數學家教與圖論研究網站

這是一個可直接部署到 GitHub Pages 的靜態網站專案  
內容包含：

- 專業家教首頁
- 立體數學圖形視覺
- 教學特色
- 論文專區
- 課程方案
- 聯絡預約區

## 專案結構

```txt
math-tutor-website-pro/
├── index.html
├── styles.css
├── script.js
├── assets/
│   └── favicon.svg
├── README.md
└── .gitignore
```

## 本機預覽

直接用瀏覽器打開：

```txt
index.html
```

或使用 VS Code 的 Live Server

## 上架到 GitHub Pages

### 1. 建立 GitHub Repository

例如建立：

```txt
math-tutor-website
```

### 2. 推上 GitHub

```bash
git init
git add .
git commit -m "Upgrade professional math tutor website"
git branch -M main
git remote add origin https://github.com/你的帳號/math-tutor-website.git
git push -u origin main
```

### 3. 開啟 GitHub Pages

到 GitHub repository：

```txt
Settings → Pages
```

設定：

```txt
Source: Deploy from a branch
Branch: main
Folder: /root
```

網站會出現在：

```txt
https://你的帳號.github.io/math-tutor-website/
```

## 修改論文連結

在 `index.html` 搜尋：

```txt
我的論文連結
```

把該區塊的 `href="https://ndltd.ncl.edu.tw/"` 改成你的正式論文網址

## 修改 Email

在 `index.html` 搜尋：

```txt
handsomeboy784@gmail.com
```

即可修改
