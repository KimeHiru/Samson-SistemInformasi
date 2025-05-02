# Sistem Informasi Akademik – SMK Hang Tuah 1 Jakarta

Aplikasi web statis berbasis HTML, CSS, dan JavaScript untuk mengelola data akademik di lingkungan sekolah dengan pembagian akses berdasarkan peran pengguna.

## 📌 Fitur Utama
- Login pengguna
- Role-based access dengan tampilan dan fitur berbeda untuk:
  - Admin – Kelola data siswa, guru, jurusan, jadwal, pengumuman
  - Guru – Input dan lihat nilai, jadwal, profil
  - Siswa – Lihat nilai, pengumuman, profil
- Pengelolaan Data:
  - Siswa, Guru, Jurusan
  - Input nilai dan rapor
  - Jadwal pelajaran
  - Pengumuman sekolah
- Tampilan dashboard modern untuk setiap peran

```bash
## 🗂️ Struktur Folder
├── index.html # Halaman utama
├── login.html # Halaman login
├── admin/
│ ├── dashboard-admin.html # Dashboard Admin
│ ├── data-guru1.html
│ └── ... (halaman admin lainnya)
├── data-siswa.html # Data siswa
├── data-guru.html # Data guru
├── data-jurusan.html # Data jurusan
├── input-nilai.html # Input nilai
├── pengumuman2.html # Pengumuman
├── visi-misi.html # Visi dan Misi
└── ... (file lainnya)


🛠 Teknologi yang Digunakan
- HTML5
- CSS3
- JavaScript
