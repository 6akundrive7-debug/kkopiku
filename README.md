# Kopiku POS — Kasir dengan Database

## Struktur file (siap hosting)

```
├── server.js          ← backend
├── package.json
├── public/
│   └── index.html     ← tampilan kasir
├── data/              ← database (otomatis dibuat saat server jalan)
└── README.md
```

## Cara jalan di komputer

```bash
node server.js
```

Buka: http://localhost:3000  
Password admin: `admin123`

## Cara hosting di Render (gratis)

1. Upload **seluruh isi folder ini ke ROOT** repo GitHub  
   (jangan taruh di dalam folder lagi seperti `kopiku-pos/kopiku-pos/`)

2. Di Render → New → Web Service → pilih repo

3. Isi pengaturan:
   - **Root Directory**: kosongkan
   - **Runtime**: Node
   - **Build Command**: kosongkan
   - **Start Command**: `node server.js`
   - **Instance**: Free

4. Create Web Service → tunggu Live

5. Buka URL yang diberikan Render

## Password admin default
```
admin123
```
Ganti segera lewat Admin → Keamanan.
