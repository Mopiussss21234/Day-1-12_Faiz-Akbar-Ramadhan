# Dokumentasi Workshop EXPECTIK 2026: Day 1

Repository ini merupakan media penyimpanan publik (*public repository*) dan pusat dokumentasi resmi selama mengikuti kegiatan **Workshop EXPECTIK 2026: Day 1 - Proyek Workshop** yang diselenggarakan oleh Himpunan Mahasiswa Informatika dan Komputer (HIMATIK) Politeknik Negeri Jakarta (PNJ).

---

## 👤 Data Peserta

| Keterangan | Informasi |
| :--- | :--- |
| **Nama Lengkap** | Faiz Akbar Ramadhan |
| **NIM** | 2607441039 |
| **Program Studi** | Rekayasa Keamanan Siber |
| **Kelompok** | Kelompok 12 - Uncharted |

---

## 📖 Deskripsi Singkat Repository

Repository ini dibuat sebagai media penyimpanan publik (*public repository*) dan pusat dokumentasi resmi selama mengikuti kegiatan **Workshop EXPECTIK 2026: Day 1 - Proyek Workshop** yang diselenggarakan oleh Himpunan Mahasiswa Informatika dan Komputer (HIMATIK) Politeknik Negeri Jakarta.

Repositori ini memuat rangkuman materi dari modul *"Building with AI, Managing Change with GitHub"* (From AI to GitHub) yang dibawakan oleh **Kak Nugi Farhan** (*Senior Product Designer & UX Advisor*), catatan pembelajaran, implementasi pembuatan aplikasi berbasis AI (**Student Task Planner**), serta bukti praktik pengelolaan kode menggunakan Git dan GitHub.

---

## 🎯 Tujuan & Kegunaan Repository

1. **Media Penyimpanan Publik & Pusat Dokumentasi**: Menyimpan seluruh berkas, catatan, dan progres kegiatan workshop secara terstruktur dan transparan.
2. **Dokumentasi Pembelajaran**: Merangkum pemahaman materi seputar *Prompt Engineering* (Building with AI) dan *Version Control System* (Git & GitHub).
3. **Implementasi Proyek Praktik**: Mendokumentasikan pembuatan dan pengembangan aplikasi web pemula berbasis AI, yaitu *Student Task Planner*.
4. **Portofolio Pengelolaan Kode**: Menjadi bukti autentik penguasaan alur kerja Git (lokal) dan GitHub (remote collaboration) serta implementasi keamanan koneksi (SSH Key).

---

## ℹ️ Informasi Kegiatan Workshop

- **Nama Misi**: Day 1 - Proyek Workshop-26 (Week 1)
- **Topik Workshop**: From AI to GitHub: Building with AI, Managing Change with GitHub
- **Pemateri**: Kak Nugi Farhan (*Senior Product Designer / UX Advisor*)
- **Penyelenggara**: Himpunan Mahasiswa Informatika dan Komputer (HIMATIK) PNJ
- **Waktu Pelaksanaan**: Sabtu, 7 November 2026

---

## 📚 Rangkuman Materi Workshop

### 1. Building with AI (Prompt Engineering)
- **Konsep Dasar Prompting**: Memahami bahwa instruksi yang diberikan kepada model AI membutuhkan konteks yang spesifik dan jelas (*Context is Key*).
- **Struktur Prompt Efektif**:
  - **Role**: Menentukan persona atau peran AI (misal: "Bertindak sebagai Senior Web Developer").
  - **Task / Goal**: Tujuan utama atau tugas spesifik yang harus diselesaikan.
  - **Context / Constraints**: Batasan teknis, aturan, atau batasan waktu dan lingkup.
  - **Format / Output**: Bentuk hasil akhir yang diharapkan (misal: Markdown, JSON, tabel, kode modular).
- **Taktik Prompting Profesional (Standar Google Cloud)**:
  - Menggunakan kata kerja aksi (*action verbs*) yang tegas dan tidak ambigu.
  - Menentukan target audiens dari keluaran yang dihasilkan.
  - Menyertakan fakta, data acuan, atau *few-shot examples*.
  - Menetapkan batasan teknologi dan metodologi secara eksplisit.

### 2. Managing Change with GitHub (Git & GitHub)
- **Konsep Version Control System (VCS)**:
  - Memahami sejarah dan evolusi sistem kontrol versi, termasuk kelahiran Git oleh **Linus Torvalds** pada tahun 2005.
- **Perbedaan Git & GitHub**:
  - **Git**: Alat/perangkat lunak *Distributed Version Control System* (DVCS) yang berjalan secara lokal di komputer pengembang.
  - **GitHub**: Platform layanan berbasis *cloud* untuk kolaborasi, *hosting* repositori Git, *code review*, dan manajemen proyek tim.
- **Alur Kerja 3 Area Git**:
  1. **Working Directory**: Ruang kerja lokal tempat file dibuat dan dimodifikasi.
  2. **Staging Area (Index)**: Area penampungan sementara perubahan file yang siap untuk disimpan (`git add`).
  3. **Git Directory (Repository)**: Riwayat penyimpanan permanen berbasis *commit* snapshots (`git commit`).
- **Konfigurasi & Keamanan**:
  - Konfigurasi identitas pengguna (`user.name` dan `user.email`).
  - Koneksi keamanan modern berbasis autentikasi **SSH Key (Ed25519)** untuk pertukaran data yang aman dengan GitHub.
- **Perintah Esensial Git**:
  - `git init`: Menginisialisasi repositori Git baru di direktori lokal.
  - `git add <file>`: Memindahkan perubahan ke Staging Area.
  - `git commit -m "<pesan>"`: Menyimpan snapshot perubahan ke riwayat Git.
  - `git remote add origin <url>`: Menghubungkan repositori lokal dengan repositori jarak jauh (GitHub).
  - `git push -u origin <branch>`: Mengunggah commit lokal ke repositori GitHub.
  - `git pull`: Mengambil dan menggabungkan perubahan terbaru dari remote ke lokal.
- **Praktik Proyek**:
  - Implementasi dan pembuatan aplikasi web pemula: **Student Task Planner**.
