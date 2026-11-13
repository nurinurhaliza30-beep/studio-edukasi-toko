STUDIO EDUKASI — TOKO DIGITAL SEDERHANA (TANPA SUPABASE)

ISI FOLDER
- index.html: halaman toko untuk pengunjung.
- products.js: daftar 30 paket tematik. Edit file ini untuk mengubah harga dan link Lynk.id.

CARA DEPLOY KE GITHUB
1. Buat repository GitHub baru, misalnya studio-edukasi-toko.
2. Upload index.html dan products.js ke bagian paling atas/root repository.
3. Aktifkan GitHub Pages (Settings > Pages > Deploy from a branch > main > /(root)) bila ingin hosting langsung dari GitHub.
   Atau hubungkan repository baru ini ke Netlify untuk hosting Netlify.
4. Jangan unggah ke repository Studio Tools yang lama.

MENGATUR LINK PEMBAYARAN
Buka products.js, cari produk yang ingin diaktifkan. Ubah lynk:'' menjadi lynk:'https://lynk.id/tautan-produk-anda'.
Ubah price:'Harga segera diumumkan' menjadi harga yang sudah diputuskan.
Setelah disimpan dan di-push ke GitHub, katalog akan diperbarui otomatis oleh hosting.

CATATAN
- Ini versi katalog statis. Tidak ada login admin, database, atau fitur tambah produk langsung dari halaman web.
- Semua 30 paket ditampilkan sebagai segera tersedia sampai harga dan link checkout dimasukkan.
- Isi produk di master planner adalah konsep produk; file game, worksheet, dan storybook harus disiapkan sebelum dijual.
- Link Studio Tools pada tombol header perlu disesuaikan dengan URL Netlify Studio Tools yang benar jika alamatnya berbeda.


PEMBARUAN KATALOG:
Setiap paket tema kini menampilkan 4 jenis produk: Game Interaktif Canva, Worksheet, Storybook, Comic, Video Animasi, dan Presentation. Judul Comic 'Komik Edukasi [Tema]' adalah judul kerja yang perlu disesuaikan setelah naskah komik dibuat.
