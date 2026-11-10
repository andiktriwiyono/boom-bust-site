# Boom & Bust — situs kecil untuk OAuth (GitHub Pages)

Dua file ini memenuhi syarat "Publish app" di Google Cloud Console:
homepage + privacy policy URL, keduanya di domain yang sama.

## Cara pasang (di GitHub, ~5 menit)

1. Buat repo publik baru, misal `boom-bust-site`.
2. Upload `index.html` dan `privacy.html` ke root repo (branch `main`).
3. Settings → Pages → Build and deployment → Source: **Deploy from a branch**,
   Branch: `main`, folder `/ (root)` → Save.
4. Tunggu ~1 menit, situs hidup di:
   `https://<username>.github.io/boom-bust-site/`
   - Homepage: `https://<username>.github.io/boom-bust-site/`
   - Privacy policy: `https://<username>.github.io/boom-bust-site/privacy.html`

## Isi di Google Cloud Console → Branding

- Application home page: `https://<username>.github.io/boom-bust-site/`
- Application privacy policy link: `https://<username>.github.io/boom-bust-site/privacy.html`
- Authorized domains: `<username>.github.io`
- Terms of service: kosong (tidak wajib).

Lalu Audience → **Publish app**. Kalau Google meminta verifikasi domain
(Search Console), kabari Muse — file verifikasi tinggal di-upload ke root repo.
