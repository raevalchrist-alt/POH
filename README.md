# Pomparan Ompung Halasan

Silsilah keluarga keturunan Ompung Halasan dalam bentuk aplikasi web (PWA): tampilan pohon dan daftar, pencarian nama, detail hubungan keluarga, nomor urut, dan bisa dipasang di layar utama HP serta dibuka tanpa internet setelah kunjungan pertama.

## Isi
- `index.html` — aplikasi (data silsilah ada di dalam file ini, cari `const D=`)
- `manifest.webmanifest`, `sw.js`, `icon-*.png` — supaya bisa dipasang seperti aplikasi
- `.nojekyll` — agar GitHub Pages menyajikan file apa adanya

## Memperbarui data
Edit bagian `const D=[...]` di `index.html`, lalu naikkan versi cache di `sw.js` (misalnya `poh-v3` → `poh-v4`) supaya HP yang sudah memasang ikut mendapat versi baru.
