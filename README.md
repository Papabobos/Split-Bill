# Split Bill PWA

Biar gak ada yang kabur duluan sebelum bayar!

## File yang ada di folder ini
```
splitbill-pwa/
├── index.html       ← aplikasi utama
├── manifest.json    ← config PWA (nama, icon, warna)
├── sw.js            ← service worker (offline support)
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

## Cara deploy (gratis, 5 menit)

### Opsi 1 — Netlify Drop (paling gampang, drag & drop)
1. Buka https://app.netlify.com/drop
2. Drag & drop **seluruh folder** `splitbill-pwa` ke browser
3. Netlify langsung kasih link, misalnya: `https://amazing-name-123.netlify.app`
4. Buka link itu di HP — muncul banner "Add to Home Screen"!

### Opsi 2 — GitHub Pages
1. Buat repo baru di GitHub (misal: `split-bill`)
2. Upload semua file ke repo
3. Masuk Settings → Pages → Source: `main` branch, folder `/root`
4. Link kamu: `https://username.github.io/split-bill`

### Opsi 3 — Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Masuk ke folder: `cd splitbill-pwa`
3. Jalankan: `vercel --prod`
4. Ikutin instruksinya — selesai!

## Cara install di HP setelah deploy

### Android (Chrome)
- Buka link di Chrome
- Tunggu banner "Add to Home Screen" muncul di bawah, atau
- Tap menu titik tiga → "Add to Home Screen"

### iPhone (Safari)
- Buka link di Safari (HARUS Safari, bukan Chrome)
- Tap icon Share (kotak dengan panah ke atas)
- Scroll ke bawah → "Add to Home Screen"
- Tap "Add"

Selesai! Aplikasi bakal muncul di home screen seperti app biasa, fullscreen tanpa browser bar.
