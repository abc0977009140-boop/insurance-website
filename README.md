# 保險白話文｜個人保險顧問網站

> 讓你保險買對不買貴

這是「保險白話文」的官方網站，使用純 HTML / CSS / JavaScript 製作，無需資料庫或後端服務。

## 📁 檔案結構

```
insurance-site/
├── index.html              ← 首頁
├── posts/                  ← 文章資料夾
│   └── term-life-premium.html  ← 第一篇文章：定期壽險解析
├── README.md               ← 這個說明檔
└── robots.txt              ← SEO 設定
```

## 🚀 部署到 Vercel

1. 把整個資料夾上傳到 GitHub
2. 在 Vercel Import 該 repository
3. 點 Deploy 即可，無需任何設定

## ✏️ 如何新增文章

1. 在 `posts/` 資料夾新增一個 .html 檔（例如 `newborn-insurance.html`）
2. 編輯 `index.html`，在文章區塊加入新的卡片連結
3. Commit 推上去，Vercel 自動更新

## 🎨 顏色設定

主色調定義在每個 .html 檔案頂端的 `:root{}` 區塊：

- `--terracotta`: 主色（陶土色）
- `--olive-deep`: 深綠（標題/footer）
- `--cream`: 米色（點綴）
- `--gold`: 金黃（強調）

修改變數即可全站換色。

## 📞 聯絡

- LINE: @129diduy
- Instagram: @insurance_is_su
- Threads: @insurance_is_su
