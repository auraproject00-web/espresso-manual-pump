# Minipresso Brew Lab

Web MVP untuk mencatat dan mempelajari seduhan Wacaco Minipresso GR2.

## Fitur

- Panduan seduh GR2 dengan pilihan basket 8 g atau 12 g.
- Catatan shot: biji, roast, dosis, yield, grinder, setting, suhu air awal, durasi, kemudahan pompa, dan rasa.
- Riwayat lokal, pencarian, favorit, dan ekspor JSON.
- Saran dial-in sederhana dengan prinsip mengubah satu variabel per percobaan.

## Menjalankan

Buka `index.html` di browser modern. Tidak ada build step atau dependency eksternal. Di Vercel, deploy sebagai static site dengan root directory repo.

## Preview dan production

Setelah repo terhubung ke Vercel, push ke branch selain `main` akan membuat Preview Deployment. Push ke `main` akan memperbarui Production.

## Data

Log disimpan di `localStorage` browser dan tidak tersinkron antar perangkat. Ekspor JSON secara berkala jika ingin menyimpan cadangan.

## Catatan

Panduan ini bukan pengganti manual pabrikan. GR2 tidak memanaskan air. Jika piston terasa macet atau perlu tenaga berlebihan, hentikan dan jangan dipaksa. Resep 8 g dengan yield 16 g adalah baseline eksperimen, bukan rekomendasi resmi Wacaco.
