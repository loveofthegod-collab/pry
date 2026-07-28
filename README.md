<div align="center">

# 📊 Financial Data Automation & API

[![GitHub Actions Status](https://img.shields.io/badge/GitHub_Actions-Automated-blue?logo=githubactions&logoColor=white)](https://github.com)
[![Cloudflare Workers](https://img.shields.io/badge/Cloudflare-Workers%20%26%20Pages-orange?logo=cloudflare&logoColor=white)](https://cloudflare.com)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

*Sistem otomatisasi penarikan data saham perbankan (5Y) & LQ45 berbasis Cloudflare Workers & GitHub Actions.*

</div>

---

## 🌟 Fitur Utama

- 🔄 **Automated Sync:** Pembaruan data harian/berkala secara otomatis menggunakan GitHub Actions.
- ⚡ **High Performance:** Di-host pada jaringan global Cloudflare Workers / Pages untuk akses super cepat.
- 📈 **Data Coverage:**
  - Data historis saham perbankan (5 tahun).
  - Indeks saham **LQ45** ter-update.

---

## 🛠️ Teknologi yang Digunakan

| Komponen | Teknologi / Layanan | Fungsi |
| :--- | :--- | :--- |
| **Automation** | GitHub Actions | Menjalankan *cron job* penarikan data |
| **Deployment** | Cloudflare Workers / Pages | Menyajikan API & frontend (*serverless*) |
| **Configuration** | `wrangler.jsonc` | Pengaturan deployment Cloudflare |

---

## 🚀 Cara Memulai / Penggunaan

1. **Clone Repository:**
   ```bash
   git clone [https://github.com/loveofthegod-collab/](https://github.com/loveofthegod-collab/)<nama-repo-kamu>.git
   cd <nama-repo-kamu>
