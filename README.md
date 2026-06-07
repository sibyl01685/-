# ÉCLAT — 時尚電商網站

一個完整的靜態時尚電商前後台，無需後端框架，直接用瀏覽器開啟即可運行。

## 📁 檔案結構

```
eclat-shop/
├── index.html    # 前台電商網站
├── admin.html    # 後台管理系統
└── README.md
```

## ✨ 功能特色

### 前台（index.html）
- 全螢幕英雄橫幅 + 快速選購入口
- 商品列表（篩選：全部 / 女裝 / 男裝 / 外套 / 配件 / 特賣）
- 滑出式購物車（加入、調整數量、刪除、小計）
- 促銷橫幅、分類入口、跑馬燈公告
- 響應式設計（手機 / 平板 / 桌機）

### 後台（admin.html）
- 📊 儀表板：營收、訂單、會員、庫存統計 + 銷售圖表
- 👕 商品管理：列表、搜尋、新增/編輯/刪除
- 📦 訂單管理：狀態追蹤（待付款→待出貨→配送中→已完成）
- 👥 會員管理：等級制度（一般/白銀/黃金/VIP/鑽石）
- 🗃️ 庫存管理：SKU 層級庫存 + 低庫存警告
- 🗄️ 資料庫結構：8 張資料表 Schema 視覺化 + SQL 建表語法

## 🚀 快速開始

### 方法一：直接開啟
下載後直接用瀏覽器開啟 `index.html` 即可。

### 方法二：GitHub Pages（免費上線）
1. Fork 或上傳本 repo 至你的 GitHub
2. 進入 repo 的 **Settings → Pages**
3. Source 選擇 `main` branch，資料夾選 `/ (root)`
4. 儲存後等約 1 分鐘，即可在 `https://<你的帳號>.github.io/<repo名稱>/` 存取

## 🗄️ 資料庫設計

後台內建完整 MySQL/PostgreSQL Schema，共 8 張資料表：

| 資料表 | 說明 |
|--------|------|
| `products` | 商品主表 |
| `categories` | 分類（支援多層級） |
| `product_variants` | 商品規格（顏色/尺寸/庫存） |
| `product_images` | 商品圖片 |
| `customers` | 會員資料 |
| `orders` | 訂單主表 |
| `order_items` | 訂單明細 |
| `reviews` | 商品評價 |

完整 SQL 語法可在後台 **資料庫結構** 頁面複製。

## 🛠️ 技術棧

- 純 HTML / CSS / JavaScript（無框架依賴）
- Google Fonts（Cormorant Garamond + DM Sans）
- 所有互動皆為前端模擬，方便接入真實 API

---

> 設計風格：奢華極簡 · 深色後台 · 金色點綴
