# Website MA DDI Mattoanging

Website statis awal untuk Madrasah Aliyah DDI Mattoanging. Dibangun dengan HTML, CSS, dan JavaScript sehingga dapat dihosting gratis melalui GitHub Pages.

## Isi folder
- `index.html` — struktur dan konten website
- `style.css` — desain responsif
- `script.js` — menu mobile dan tahun otomatis
- `assets/logo.png` — tempat logo resmi madrasah

## Sebelum dipublikasikan
1. Ganti `assets/logo.png` dengan logo resmi MA DDI Mattoanging (format PNG disarankan).
2. Periksa dan lengkapi profil, visi-misi, sejarah, nomor telepon, email, foto, berita, serta informasi PPDB.
3. Hapus atau ganti teks bertanda "Konten contoh" dan "Informasi segera diperbarui".
4. Pastikan seluruh data kelembagaan sudah disetujui pihak madrasah.

## Publikasi melalui GitHub Pages
1. Buat repository baru di GitHub, misalnya `website-ma-ddi-mattoanging`.
2. Unggah semua file dan folder dari paket ini ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
6. Setelah website terbit, GitHub akan menampilkan alamat `https://USERNAME.github.io/website-ma-ddi-mattoanging/`.

## Menghubungkan domain sekolah
1. Di GitHub Pages, isi bagian **Custom domain** dengan `maddimattoangingbantaeng.sch.id`, lalu simpan.
2. Di pengelola DNS domain, tambahkan record A untuk host `@` ke alamat IP GitHub Pages yang tercantum pada dokumentasi resmi GitHub Pages.
3. Tambahkan record CNAME untuk host `www` yang mengarah ke `USERNAME.github.io` (ganti dengan username GitHub).
4. Tunggu propagasi DNS, lalu aktifkan **Enforce HTTPS** di Settings → Pages jika sudah tersedia.

Catatan: jangan mengubah nameserver atau menghapus record email yang sudah digunakan. Pastikan Anda memiliki akses ke pengelola DNS domain. Untuk DNS, ikuti nilai terbaru di dokumentasi GitHub karena alamat IP dan instruksi dapat diperbarui.

## Catatan
Paket ini adalah fondasi website profil publik, bukan sistem akademik atau dashboard admin. Fitur PPDB online, database siswa, login, dan pengelolaan berita memerlukan pengembangan lanjutan serta pengamanan tambahan.
