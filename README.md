# ⚾ Baseball Card Backend API

Backend API untuk mengambil, memfilter, dan menganalisis data **Baseball Card** dari **eBay**, termasuk:
- Trending cards
- Search cards
- Card recommendations
- Sold price history
- Market chart data (30 / 60 / 90 days)

Backend ini dirancang untuk digunakan pada aplikasi seperti:
- Baseball Card Scanner
- Card Grading Helper
- Card Price Estimator
- Sports Card Collector App

---

## 🚀 Features

- ✅ Auto refresh eBay OAuth token
- ✅ Multi marketplace (US, UK, CA, AU, EU)
- ✅ Smart baseball card filtering (anti bulk, binder, supplies)
- ✅ Rookie & graded card detection (PSA / BGS / SGC)
- ✅ Sold price history (average, median, low, high)
- ✅ Market trend chart (30d / 60d / 90d)
- ✅ In-memory caching (reduce API calls)
- ✅ Ready for Render / Railway / VPS

---

## 🧱 Tech Stack

- Node.js 18+
- Express.js
- eBay Browse API
- eBay Finding API (Completed Items)
- node-fetch
- dotenv

---

## 📦 Installation

```bash
git clone https://github.com/your-repo/baseball-card-backend.git
cd baseball-card-backend
npm install
