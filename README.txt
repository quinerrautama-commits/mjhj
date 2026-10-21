================================================================
 WEBSITE MASJID JAMIE' HARAPAN JAYA — PAKET HTML + CMS PENGURUS
================================================================

Isi paket ini:
  index.html        → Beranda
  profil.html       → Profil masjid & sambutan
  program.html      → Jadwal kajian + daftar program
  galeri.html       → Galeri foto + flyer/banner
  donasi.html       → Informasi donasi
  laporan.html      → Laporan keuangan per program
  kontak.html       → Kontak & peta lokasi
  admin/            → PANEL PENGURUS (Decap CMS, berbasis login)
  assets/           → CSS, JavaScript, gambar (img/)
  data/konten.json  → SEMUA konten website (diatur lewat panel)

----------------------------------------------------------------
CARA DEPLOY KE NETLIFY + AKTIFKAN CMS (cukup sekali)
----------------------------------------------------------------
LANGKAH 1 — Masukkan file ke GitHub
  1. Buat akun di github.com (gratis).
  2. Buat repository baru, misal: website-masjid-jamie
  3. Upload SEMUA isi ZIP ini ke repository (extract dulu di
     komputer, lalu drag & drop foldernya ke halaman GitHub,
     atau gunakan GitHub Desktop).

LANGKAH 2 — Hubungkan Netlify ke GitHub
  1. Buka app.netlify.com → Add new site → Import an existing
     project → pilih GitHub → pilih repository tadi.
  2. Deploy settings: biarkan default (Publish directory kosong).
  3. Deploy! Website dapat alamat baru, misal:
     website-masjid-jamie.netlify.app

LANGKAH 3 — Aktifkan login pengurus
  1. Di dashboard Netlify, buka Site settings → Identity →
     klik "Enable Identity".
  2. Di bagian Identity → Services → Git Gateway → klik "Enable".
  3. Buka tab Identity → Invite users → masukkan email pengurus
     yang boleh mengedit (bisa lebih dari satu).
  4. Pengurus menerima email undangan → klik link → buat password.

SELESAI. Panel pengurus ada di:
  https://website-masjid-jamie.netlify.app/admin
  (ganti dengan alamat site Anda)

----------------------------------------------------------------
CARA EDIT KONTEN (untuk pengurus, tanpa coding)
----------------------------------------------------------------
1. Buka https://alamat-site-anda.netlify.app/admin
2. Login dengan email & password (dari undangan).
3. Pilih "Semua Konten Website", lalu bagian yang mau diubah:
   🕌 Informasi Masjid   → nama, alamat, telepon, email
   💬 Sambutan            → sambutan Ketua DKM
   💛 Donasi              → rekening, QRIS (upload gambar), WA
   📋 Program             → tambah/ubah/hapus program
   📖 Kajian Mingguan     → jadwal, tema, pemateri tiap pekan
   🖼️ Flyer & Banner      → upload flyer baru
   📸 Galeri Kegiatan     → upload foto + keterangan
   💰 Laporan Keuangan    → periode + rincian per program
4. Klik "Publish" → website otomatis ter-update (1–2 menit).

Tips:
- Kajian mingguan: update setiap pekan (tema & pemateri).
- Laporan keuangan: update setiap Jumat (angka per program).
- Gambar/flyer/QRIS: klik kolom gambar → upload langsung.

----------------------------------------------------------------
CATATAN PENTING
----------------------------------------------------------------
- Website membaca data dari data/konten.json — JANGAN edit file
  ini manual; selalu lewat panel /admin agar formatnya aman.
- Info rekening/QRIS/WhatsApp masih kosong — isi lewat panel
  Donasi setelah mendapat info resmi dari pengurus.
- Halaman /admin hanya untuk pengurus (butuh login).

Selamat menggunakan! Barakallahu fiikum.
================================================================
