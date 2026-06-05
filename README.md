# Banana Leaf Accommodation (React + Vite)

Ini versi **React + Vite** dari file HTML yang kamu upload.

## Jalankan di komputer kamu
1. Install Node.js (disarankan versi LTS).
2. Buka folder project ini, lalu:
   ```bash
   npm install
   npm run dev
   ```

## Publish jadi website public (GitHub Pages)
Cara paling gampang pakai **GitHub Actions** (workflow sudah disiapkan).

1. Buat repo baru di GitHub (mis. `banana-leaf-site`) lalu upload semua file project ini.
2. Di GitHub repo: **Settings → Pages**
   - **Build and deployment → Source: GitHub Actions**
3. Push ke branch `main`.

Nanti GitHub Actions akan build dan deploy otomatis. URL biasanya:
`https://USERNAME.github.io/NAMA-REPO/`

## Catatan
- Tombol **Admin** pakai password default: `newbanana2026`
- Semua data admin tersimpan di browser user (localStorage), sama seperti versi HTML.

