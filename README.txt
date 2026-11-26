WEBSITE SMK NEGERI 1 KERTOSONO (versi HTML + CSS)

Cara menjalankan:
1. Ekstrak folder, lalu buka index.html di browser.
2. Semua gaya ada di css/style.css. Warna diatur di blok :root paling atas.

Halaman: index, tentang (profil), jurusan, informasi, kontak.

Palet warna (sesuaikan dengan logo asli bila perlu):
  --primary       #0b2e6b  biru utama
  --primary-dark  #071a3d  biru tua (hover tombol)
  --accent        #f2b705  kuning (cadangan, jarang dipakai)
  --soft          #f7f8fa  latar abu lembut

Memasang logo asli:
1. Simpan logo sebagai img/logo.png.
2. Di setiap file .html ganti <span class="brand-mark">SMK</span>
   menjadi <span class="brand-mark"><img src="img/logo.png" alt="Logo SMKN 1 Kertosono"></span>

Data yang perlu dicek ulang oleh pihak sekolah:
- Akreditasi, jam layanan, dan email resmi.
- Berita pada index.html dan informasi.html (tautan mengarah ke website resmi).

Catatan: tanpa JavaScript/PHP/database. Formulir kontak hanya tampilan.


Pembaruan: gambar gapura sekolah digunakan sebagai latar hero, foto kepala sekolah ditampilkan pada bagian Tentang Sekolah, dan alamat sekolah mengarah langsung ke Google Maps. Banner promosi bawah halaman dihapus. Website tetap berupa HTML/CSS statis dan siap diunggah ke GitHub Pages.


Pembaruan tampilan sederhana: topbar, kotak statistik, bagian Keunggulan gelap, ikon emoji, gradasi, bayangan, dan efek hover dihapus. Tata letak kini datar dan bersih (header putih, hero gapura, kartu dengan garis tipis, footer abu terang). Cadangan versi sebelumnya ada di folder smkn1kertosono_backup (bila disertakan).
