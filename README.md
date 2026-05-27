# XLSMART Analytics Dashboard

Dashboard analisis aktivitas canvasser XLSMART.

## Cara Deploy (Langkah per Langkah)

### 🥇 OPSI 1: Netlify (TERMUDAH - Gratis, 0 coding)

1. Buka [netlify.com](https://netlify.com) → Sign up gratis
2. Klik **"Add new site"** → **"Import an existing project"**
3. Pilih **"Deploy manually"** atau connect GitHub
4. Upload folder ini → Netlify otomatis build & deploy
5. URL jadi: `https://nama-random.netlify.app` ✅

### 🥈 OPSI 2: Vercel (Gratis, profesional)

1. Buka [vercel.com](https://vercel.com) → Sign up gratis (pakai GitHub)
2. Klik **"Add New Project"**
3. Import repository GitHub yang berisi folder ini
4. Klik **Deploy** → otomatis selesai
5. URL jadi: `https://nama-project.vercel.app` ✅

---

## Cara Jalankan Lokal (untuk testing)

Butuh: Node.js (download di nodejs.org)

```bash
npm install
npm run dev
```
Buka browser: http://localhost:5173

## Cara Build Manual

```bash
npm install
npm run build
```
Hasilnya ada di folder `dist/` — upload isi folder ini ke hosting manapun.

---

## Rekomendasi Hosting & Biaya

| Layanan | Harga | Kelebihan |
|---------|-------|-----------|
| **Netlify** | GRATIS | Paling mudah, drag & drop |
| **Vercel** | GRATIS | Cepat, auto-deploy dari GitHub |
| **GitHub Pages** | GRATIS | Perlu sedikit setup |
| **Cloudflare Pages** | GRATIS | CDN tercepat |

> Semua opsi di atas 100% GRATIS untuk penggunaan normal.

### Kalau mau domain sendiri (opsional)
- **Niagahoster** (Indonesia): ~Rp 15.000/tahun untuk .com
- **Namecheap**: ~$10/tahun untuk .com
- **Google Domains**: ~$12/tahun untuk .com

Setelah beli domain, sambungkan ke Netlify/Vercel lewat pengaturan DNS (ada panduan di masing-masing platform).

---

## Struktur File

```
xlsmart-dashboard/
├── src/
│   ├── App.jsx       ← Dashboard utama
│   └── main.jsx      ← Entry point React
├── index.html        ← HTML template
├── package.json      ← Dependencies
├── vite.config.js    ← Build config
├── netlify.toml      ← Config Netlify
└── vercel.json       ← Config Vercel
```
