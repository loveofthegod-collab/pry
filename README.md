<div align="center">

# 📈 Financial Data Automation & API

<p align="center">
  <b>Sistem Otomatisasi Data Saham & Perbankan Berbasis Cloudflare Workers</b>
</p>

[![GitHub Actions Status](https://img.shields.io/badge/GitHub_Actions-Automated-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com)
[![Cloudflare Workers](https://img.shields.io/badge/Cloudflare-Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)](https://cloudflare.com)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

---

### 🌐 Live Demo & Endpoints

| Platform | URL |
| :--- | :--- |
| ⚡ **Cloudflare Worker API** | [khususheet.loveofthegod.workers.dev](https://khususheet.loveofthegod.workers.dev/) |
| 🌐 **GitHub Pages** | [loveofthegod-collab.github.io/pry](https://loveofthegod-collab.github.io/pry/) |

</div>

---

## ⚡ Ringkasan Proyek

Repository ini berfungsi untuk menarik, memproses, dan memperbarui data keuangan/saham secara otomatis. Terintegrasi langsung dengan **GitHub Actions** untuk jadwal pembaruan berkala dan di-deploy ke **Cloudflare Workers / Pages** agar data dapat diakses dengan cepat.

### ✨ Fitur Utama
- 🔄 **Otomatisasi Penuh:** Fitur cron-job via GitHub Actions untuk *update* data (5Y Bank & LQ45).
- 🚀 **Performa Tinggi:** *Serverless architecture* menggunakan Cloudflare Workers.
- 📡 **API Ready:** Menyediakan *endpoint* siap pakai untuk konsumsi data harian.

---

## 🛠️ Stack Teknologi

- **Language / Runtime:** JavaScript / Node.js
- **Automation / CI-CD:** GitHub Actions
- **Hosting / Serverless:** Cloudflare Workers & Pages
- **Config:** `wrangler.jsonc`

---

## 🚀 Panduan Lokal (Local Development)

```bash
# 1. Clone repository
git clone [https://github.com/loveofthegod-collab/pry.git](https://github.com/loveofthegod-collab/pry.git)

# 2. Masuk ke direktori
cd pry

# 3. Jalankan server lokal Cloudflare Wrangler
npx wrangler dev
