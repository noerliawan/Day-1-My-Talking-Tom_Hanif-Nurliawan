# Dokumentasi Workshop: Building with AI & Managing Change with GitHub

Dokumentasi ini disusun oleh:

 Nama Lengkap: Hanif Nurliawan

## Deskripsi Singkat Repository
Repository ini berisi dokumentasi lengkap, rangkuman materi, serta kode/proyek latihan dari kegiatan workshop bertema pengembangan aplikasi berbasis AI dan manajemen versi menggunakan Git dan GitHub.

---

## Tujuan atau Kegunaan Repository
Tujuan dari pembuatan repository ini adalah:
1. **Penyimpanan Dokumentasi:** Menjadi wadah pencatatan dan dokumentasi hasil pembelajaran selama workshop.
2. **Praktik Version Control:** Mempraktikkan secara langsung alur kerja Git (version controlling) dan integrasi ke platform GitHub.
3. **Referensi & Portofolio:** Menyimpan hasil proyek latihan ("Student Task Planner") serta menjadi referensi pembelajaran di masa mendatang.

---

## Informasi Singkat Kegiatan Workshop
Judul Workshop: Building with AI, Managing Change with GitHub
Pemateri / Speaker: Nugi Farhan (Senior Product Designer / UX Advisor)
Topik Utama:
  * Dasar-dasar Prompt Engineering untuk AI.
  * Manajemen Perubahan dan Kolaborasi menggunakan Git & GitHub.
* Proyek Praktik: Pembuatan aplikasi Student Task Planner menggunakan bantuan AI dan dikelola melalui Git/GitHub.

## Dokumentasi Kegiatan Workshop

### 1. Materi / Topik yang Disampaikan
Selama kegiatan workshop, materi yang dipelajari meliputi:

#### A. Prompt Engineering (Building with AI)
Pengertian Prompt AI: Instruksi atau masukan (pertanyaan, kata kunci, kode) yang diberikan kepada AI model untuk mendapatkan hasil tertentu.
Pentingnya Konteks:** AI dapat memberikan jawaban yang presisi dan relevan jika diberi konteks yang jelas (Goal, Requirements, Constraints).
Struktur Prompt yang Baik:
  * Role: Menentukan peran AI.
  * Task: Menjelaskan tugas utama yang harus dilakukan.
  * Context: Memberikan latar belakang dan detail pendukung.
  * Format/Output: Menentukan format keluaran yang diinginkan.
Keuntungan Prompt Engineering: Meningkatkan performa AI, mengurangi bias/respons ofensif, meningkatkan kontrol & keterkiraan (*predictability*), serta memberikan pengalaman pengguna yang lebih baik.

#### B. Git & GitHub (Managing Change with GitHub)
Pengertian & Perbedaan:
  * Git: Sistem Distributed Version Control System (DVCS) lokal untuk melacak dan mengelola perubahan kode.
  * GitHub: Platform berbasis web untuk menyimpannya secara online dan berkolaborasi.
  Git Workflow:
  1. Working Directory: Area kerja tempat file dimodifikasi.
  2. Staging Area (Index): Area persiapan sebelum perubahan di-commit.
  3. Git Directory (Repository): Tempat Git menyimpan metadata dan database proyek.
Perintah Dasar Git & GitHub:
  * Perintah lokal: `git init`, `git add .`, `git commit -m "message"`.
  * Perintah integrasi GitHub: `git remote add <name> <url>`, `git push origin main`, `git pull origin main`.
Pengaturan Lingkungan (Setup):
  * Konfigurasi Git Identity (`user.name` & `user.email`).
  * Integrasi VS Code CLI.
  * Autentikasi SSH Key (`ssh-keygen -t ed25519`) dan menghubungkannya ke akun GitHub.


### 2. Catatan / Rangkuman Materi Workshop
Panduan Praktik Pembangunan Aplikasi (Student Task Planner):
  1. Menggunakan AI-assisted platform (Claude, ChatGPT, dsb.).
  2. Menuliskan prompt terstruktur yang memuat Role, Goal, Requirements, Constraints, dan Output.
  3. Inisialisasi repository lokal menggunakan `git init`.
  4. Melakukan commit pertama dan melakukan `push` ke repository GitHub.
  5. Melakukan iterasi perubahan pada aplikasi, kemudian melakukan commit dan push secara berkala.


### 3. Poin-Poin Penting & Pengetahuan Baru (Key Takeaways)
Pentingnya Konteks Spesifik pada Prompting: Menambahkan batasan (*constraints*) dan syarat (*requirements*) membuat AI dapat menghasilkan kode yang siap pakai tanpa pustaka (*dependencies*) yang tidak diperlukan.
Memahami 3 Area Utama Git: Perubahan tidak langsung tersimpan ke repository, melainkan harus melewati tahapan dari *Working Directory* $\rightarrow$ *Staging Area* $\rightarrow$ .git Directory (Commit).
Keamanan Integrasi melalui SSH Key: Menggunakan kunci SSH (algoritma Ed25519) merupakan cara aman dan efisien untuk menghubungkan lingkungan lokal ke GitHub tanpa menginput kata laluan secara berulang.
Prinsip Version Control: Setiap perubahan kecil atau penambahan fitur sebaiknya dicatat menggunakan `git commit` dengan pesan yang jelas agar alur perkembangan aplikasi terintegrasi dengan rapi.
