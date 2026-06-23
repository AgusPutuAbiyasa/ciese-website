# CIESE Website

Static website package for **CIESE — Center for Intelligent Electronic Systems and Sustainable Energy**.

## Cara menjalankan lokal

Buka file `index.html` langsung di browser, atau jalankan server lokal:

```bash
python -m http.server 8000
```

Kemudian buka:

```text
http://localhost:8000
```

## Struktur

```text
ciese_website/
├── index.html
├── styles.css
├── script.js
├── assets/
│   ├── ciese-logo.png
│   └── peta-klaster.png
└── docs/
    └── Profil_Lembaga_CIESE_Pusat_Riset.docx
```

## Kustomisasi cepat

- Ubah alamat email pada form kontak di `index.html`: `mailto:info@ciese.id`.
- Ubah daftar publikasi pada section `#publications`.
- Ubah status hibah pada tabel `#projects`.
- Ganti aset logo/infografis di folder `assets`.

## Catatan deployment

Website ini dapat diunggah ke hosting statis seperti GitHub Pages, Netlify, Vercel, cPanel, atau subdomain kampus.
