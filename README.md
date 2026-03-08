# 📦 STOCKPILE — Retail Inventory System

A full retail POS & inventory management system built with React + Vite.

## Features
- 📦 Inventory management with barcode scanning
- 🧾 POS with 3-tier pricing (Normal / Special / VIP)
- 👥 Customer database with purchase history
- 📊 Sales reports, best-sellers chart, profit tracker
- 🖨️ Receipt printing + CSV/PDF export

---

## 🚀 Deploy to Vercel (Step by Step)

### Step 1 — Create a GitHub account
Go to https://github.com and sign up (free).

### Step 2 — Create a new repository
1. Click the **+** button (top right) → **New repository**
2. Name it `stockpile`
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload your files
1. On your new repo page, click **uploading an existing file**
2. Drag and drop ALL files from this folder (keep the folder structure!)
3. Click **Commit changes**

### Step 4 — Deploy on Vercel
1. Go to https://vercel.com and sign up with your GitHub account (free)
2. Click **Add New Project**
3. Select your `stockpile` repository
4. Vercel auto-detects Vite — just click **Deploy**
5. Done! You'll get a live URL like `https://stockpile-xxx.vercel.app`

### Updating later
1. Edit files in GitHub directly, OR
2. Upload new files — Vercel auto-deploys every time you push!

---

## 💻 Run Locally (optional)
```bash
npm install
npm run dev
```
Then open http://localhost:5173

---

## 📁 File Structure
```
stockpile/
├── index.html          # Entry HTML
├── vite.config.js      # Vite config
├── vercel.json         # Vercel routing
├── package.json        # Dependencies
└── src/
    ├── main.jsx        # React entry
    └── App.jsx         # Full application
```
