================================================================
 WEBSITE MASJID JAMIE' HARAPAN JAYA — PAKET HTML SIAP HOSTING
================================================================

Isi paket ini:
  index.html        → Beranda
  profil.html       → Profil masjid & sambutan
  program.html      → Jadwal kajian + daftar program
  galeri.html       → Galeri foto + flyer/banner
  donasi.html       → Informasi donasi
  laporan.html      → Laporan keuangan per program
  kontak.html       → Kontak & peta lokasi
  admin.html        → PANEL PENGURUS (editor konten)
  assets/           → CSS, JavaScript, gambar (img/)
  data/konten.json  → SEMUA konten website (yang diedit pengurus)

----------------------------------------------------------------
CARA DEPLOY KE HOSTING (cPanel / Niagahoster / dll)
----------------------------------------------------------------
1. Login ke cPanel hosting Anda.
2. Buka File Manager → masuk ke folder public_html (atau htdocs).
3. Upload file ZIP ini, lalu klik kanan → Extract.
   (Alternatif: extract di komputer, lalu upload semua file & folder
   via FTP/File Manager ke public_html.)
4. Selesai! Website bisa dibuka di domain Anda.
   Pastikan struktur folder tetap: index.html sejajar dengan
   folder assets/ dan data/.

----------------------------------------------------------------
CARA EDIT KONTEN (untuk pengurus, tanpa coding)
----------------------------------------------------------------
1. Buka di browser: https://domain-anda.com/admin.html
   (atau http://domain-anda.com/admin.html)
2. Pilih tab: Informasi Masjid, Donasi, Program, Kajian Mingguan,
   Flyer & Banner, Galeri, Laporan Keuangan.
3. Ubah teks / jadwal / angka sesuai kebutuhan.
   - Kajian mingguan: update setiap pekan (tema, pemateri, jadwal).
   - Laporan keuangan: update setiap Jumat (angka per program).
   - Flyer/banner: upload gambar dulu (lihat bawah), lalu daftarkan.
4. Klik "⬇ Simpan & Unduh konten.json".
5. Upload file konten.json hasil unduhan ke hosting,
   gantikan file lama di folder data/.
6. Refresh website — konten baru langsung tampil.

----------------------------------------------------------------
CARA MENAMBAH GAMBAR / FLYER
----------------------------------------------------------------
1. Upload file gambar (JPG/PNG) ke folder assets/img/ di hosting
   via File Manager atau FTP.
2. Di admin.html, tulis nama filenya di kolom gambar, contoh:
     assets/img/flyer-kajian-jumat.jpg
3. Simpan & upload konten.json seperti biasa.

----------------------------------------------------------------
CATATAN PENTING
----------------------------------------------------------------
- Website membaca data dari data/konten.json, jadi halaman harus
  dibuka lewat hosting/server (http), BUKAN dengan klik ganda file
  di komputer (file://). Untuk tes di komputer, jalankan:
     python3 -m http.server
  lalu buka http://localhost:8000
- Jangan hapus/ubah nama folder assets/ dan data/.
- Halaman admin.html sebaiknya hanya diketahui pengurus.
- Info rekening/QRIS/WhatsApp masih kosong — isi lewat tab Donasi
  di admin.html setelah mendapat info resmi dari pengurus.

Selamat menggunakan! Barakallahu fiikum.
================================================================
