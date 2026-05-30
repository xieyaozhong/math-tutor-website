# 謝老師數學家教個人網站

這是一個可以直接部署到 GitHub Pages 的靜態網站專案

## 專案結構

```txt
math-tutor-website/
├── index.html
├── styles.css
├── script.js
├── assets/
│   └── favicon.svg
├── README.md
└── .gitignore
```

## 本機預覽

直接用瀏覽器打開 `index.html` 即可

也可以用 VS Code 安裝 Live Server 後開啟

## 上架到 GitHub Pages

### 1. 建立 GitHub Repository

到 GitHub 建立一個新 repository，例如：

```txt
math-tutor-website
```

### 2. 把檔案推上 GitHub

在專案資料夾打開終端機，輸入：

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/你的帳號/math-tutor-website.git
git push -u origin main
```

### 3. 開啟 GitHub Pages

進入 GitHub repository：

```txt
Settings → Pages → Build and deployment
```

設定：

```txt
Source: Deploy from a branch
Branch: main
Folder: /root
```

按 Save

網站網址通常會是：

```txt
https://你的帳號.github.io/math-tutor-website/
```

## 修改聯絡方式

在 `index.html` 搜尋：

```txt
handsomeboy784@gmail.com
```

即可修改 Email

## 修改圖片

目前網站使用 Unsplash 圖片  
若要改成本機圖片，可以把圖片放到：

```txt
assets/
```

然後在 `styles.css` 裡修改 `.photo-box` 的 `url(...)`
