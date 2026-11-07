# EXPECTIK 2026
## Day 1 – Sosialisasi Jurusan

---

## 1. Identitas Peserta

| Keterangan | Informasi |
|---|---|
| Nama Lengkap | Lu'lu'ah Nafisa |
| Nama Kelompok | 10_FC27 |
| Kegiatan | EXPECTIK 2026 |
| Hari | Day 1 |
| Agenda | Sosialisasi Jurusan |
| Materi | Pengenalan Git & GitHub |

---

## 2. Deskripsi Repository

Repository ini dibuat sebagai bentuk dokumentasi kegiatan Day 1 EXPECTIK 2026, yang berfokus pada kegiatan sosialisasi jurusan dan pengenalan materi Git & GitHub.

Repository ini memuat rangkuman materi, catatan pembelajaran, serta pengetahuan baru yang diperoleh selama kegiatan berlangsung. Dokumentasi ini disusun sebagai arsip pembelajaran sekaligus referensi untuk memahami penggunaan Git dan GitHub dalam pengelolaan proyek pengembangan perangkat lunak.

## 3. Tujuan Repository

Tujuan pembuatan repository ini adalah:

1. Mendokumentasikan kegiatan Day 1 EXPECTIK 2026.
2. Menyimpan rangkuman materi dan catatan pembelajaran selama kegiatan.
3. Memahami konsep dasar Git dan GitHub.
4. Mempelajari penggunaan version control dalam pengelolaan proyek.
5. Menjadikan repository sebagai referensi pembelajaran untuk kegiatan selanjutnya.

---

## 4. Dokumentasi Kegiatan Workshop

### A. Rangkuman Materi Workshop

#### 1. Pengertian Git

Git merupakan **Version Control System (VCS)** yang digunakan untuk melacak dan mengelola setiap perubahan pada file dalam suatu proyek. Git memungkinkan pengguna mengetahui siapa yang melakukan perubahan, kapan perubahan dilakukan, serta apa saja yang mengalami perubahan.

Git diciptakan oleh Linus Torvalds pada tahun 2005 untuk membantu pengelolaan perubahan pada file secara terstruktur.

#### 2. Pengertian GitHub

GitHub merupakan platform berbasis web yang digunakan untuk menyimpan repository Git secara online dan mendukung kolaborasi antar pengguna dalam pengembangan proyek.

GitHub memungkinkan pengguna menyimpan proyek, membagikan kode, serta bekerja sama dengan orang lain dalam satu repository.

#### 3. Perbedaan Git dan GitHub

| Git | GitHub |
|---|---|
| Sistem version control terdistribusi (DVCS). | Platform berbasis web. |
| Digunakan untuk melacak dan mengelola perubahan file secara lokal. | Digunakan untuk menyimpan repository Git secara online. |
| Dapat digunakan melalui terminal atau command line. | Dapat diakses melalui browser. |
| Berfokus pada pengelolaan versi proyek. | Mendukung penyimpanan dan kolaborasi proyek. |

#### 4. Git Workflow

Git Workflow merupakan alur kerja Git dalam mengelola perubahan file. Terdapat tiga bagian utama yang perlu dipahami:

**a. Working Directory**

Working Directory merupakan salinan proyek yang sedang dikerjakan. File di dalamnya dapat digunakan, dibuat, maupun dimodifikasi oleh pengguna.

**b. Staging Area**

Staging Area merupakan tempat untuk menampung perubahan file yang akan dimasukkan ke dalam commit berikutnya. Pengguna dapat menentukan file mana saja yang akan disimpan dalam commit.

**c. Git Directory (Repository)**

Git Directory merupakan tempat Git menyimpan metadata dan object database suatu proyek. Bagian ini menyimpan informasi yang dibutuhkan Git untuk mengelola perubahan proyek.

Alur sederhananya adalah:

Working Directory → Staging Area → Git Directory

#### 5. Essential Git Commands

Beberapa perintah dasar Git yang dipelajari selama workshop:

| Perintah | Fungsi |
|---|---|
| `git init` | Membuat atau menginisialisasi repository Git baru. |
| `git add .` | Memindahkan perubahan file ke Staging Area. |
| `git add --all` | Menambahkan seluruh perubahan dalam repository ke Staging Area. |
| `git add -A` | Memiliki fungsi yang sama dengan `git add --all`. |
| `git commit -m "message"` | Menyimpan perubahan yang telah dimasukkan ke Staging Area ke dalam riwayat repository. |
| `git remote add origin <url>` | Menghubungkan repository lokal dengan repository remote. |
| `git push origin main` | Mengirim perubahan dari branch lokal ke repository remote. |
| `git pull origin main` | Mengambil perubahan dari repository remote dan menggabungkannya ke branch lokal. |
| `git clone <url>` | Menyalin repository remote ke komputer lokal. |

#### 6. Git Setup

Sebelum menggunakan Git, diperlukan instalasi dan konfigurasi terlebih dahulu.

Tahapan konfigurasi Git:

1. Mengunduh dan menginstal Git sesuai dengan sistem operasi yang digunakan.
2. Membuka Terminal atau Command Prompt.
3. Memeriksa instalasi Git menggunakan perintah:

   ```bash
   git --version
   ```

4. Mengatur identitas pengguna Git menggunakan perintah:

   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your-email@example.com"
   ```

5. Memeriksa konfigurasi Git:

   ```bash
   git config --global --list
   ```

#### 7. VS Code Setup

Visual Studio Code (VS Code) digunakan sebagai code editor untuk membantu proses pengembangan proyek.

Tahapan konfigurasi VS Code:

1. Mengunduh dan menginstal VS Code.
2. Membuka aplikasi VS Code.
3. Menekan `Ctrl + Shift + P` pada Windows atau `Command + Shift + P` pada macOS.
4. Mencari perintah `Shell Command: Install 'code' command in PATH` sesuai sistem operasi.
5. Membuka Terminal dan memeriksa instalasi menggunakan:

   ```bash
   code --version
   ```

#### 8. Menghubungkan Repository Lokal dengan GitHub

Terdapat dua cara yang dibahas untuk mulai menggunakan repository GitHub:

**Cara pertama: Menginisialisasi repository lokal**

```bash
git init
```

Perintah tersebut digunakan untuk menginisialisasi folder proyek agar dapat dikelola menggunakan Git.

**Cara kedua: Melakukan clone repository dari GitHub**

1. Membuka GitHub.
2. Membuat repository baru.
3. Membuka tombol **Code**.
4. Menyalin URL repository.
5. Membuka Terminal pada komputer lokal.
6. Menjalankan perintah:

   ```bash
   git clone <repository-url>
   ```

#### 9. Working Area ke Staging Area

Untuk memindahkan perubahan file dari Working Directory ke Staging Area, terdapat beberapa perintah yang dapat digunakan:

```bash
git add --all
git add -A
git add .
git add *
```

Perintah tersebut digunakan untuk menambahkan file atau perubahan ke Staging Area, dengan cakupan yang dapat berbeda sesuai perintah yang digunakan.

#### 10. SSH Key Configuration

SSH Key digunakan untuk melakukan autentikasi antara komputer lokal dengan GitHub.

Salah satu tahapan pembuatan SSH Key yang dipelajari adalah menggunakan perintah:

```bash
ssh-keygen -t ed25519 -C "email@domain.com"
```

Setelah SSH Key dibuat, public key perlu ditambahkan ke pengaturan SSH and GPG keys pada akun GitHub.

Untuk memeriksa koneksi SSH dengan GitHub, gunakan perintah:

```bash
ssh -T git@github.com
```

Jika autentikasi berhasil, GitHub akan memberikan pesan bahwa pengguna berhasil melakukan autentikasi.

---

### B. Poin-Poin Penting dan Pengetahuan Baru

1. Git dan GitHub memiliki fungsi yang berbeda. Git digunakan untuk mengelola perubahan pada proyek, sedangkan GitHub digunakan untuk menyimpan repository secara online dan mendukung kolaborasi.

2. Version Control sangat penting dalam pengembangan perangkat lunak karena memungkinkan setiap perubahan pada proyek dilacak dan dikelola dengan lebih terstruktur.

3. Git memiliki tiga komponen utama dalam workflow, yaitu Working Directory, Staging Area, dan Git Directory.

4. Perintah `git add` digunakan untuk mempersiapkan perubahan sebelum disimpan menggunakan `git commit`.

5. Commit merupakan proses menyimpan perubahan ke dalam riwayat repository sehingga perubahan tersebut dapat dilacak kembali.

6. Repository lokal dapat dihubungkan dengan repository GitHub menggunakan remote repository.

7. Perintah `git push` digunakan untuk mengirim perubahan ke repository remote, sedangkan `git pull` digunakan untuk mengambil perubahan dari repository remote.

8. SSH Key dapat digunakan untuk melakukan autentikasi antara komputer lokal dan GitHub.

9. Penulisan prompt AI yang baik perlu memperhatikan Role, Task, Context, dan Format agar hasil yang diberikan AI lebih sesuai dengan kebutuhan.

---

### C. Pendapat Pribadi tentang Day 1 Proyek Workshop

Menurut saya, kegiatan workshop pada day 1 EXPECTIK memberikan pengetahuan dan pengalaman baru mengenai penggunaan Git dan GitHub yang sangat bermanfaat dalam proses pengembangan perangkat lunak. Melalui materi yang disampaikan, saya menjadi lebih memahami bagaimana cara mengelola perubahan pada suatu proyek, menyimpan riwayat pekerjaan, serta menghubungkan repository lokal dengan GitHub. Saya juga memahami bahwa penggunaan version control sangat penting untuk menjaga keteraturan proyek dan mempermudah proses kolaborasi. Materi yang diberikan menjadi bekal yang berguna untuk mengembangkan kemampuan teknis, khususnya dalam bidang teknologi informasi dan software development.

---

## 5. Kesimpulan

Kegiatan ini memberikan pemahaman mengenai pentingnya penggunaan teknologi AI serta Git dan GitHub dalam proses pengembangan proyek.

Melalui materi Git dan GitHub, peserta mempelajari dasar-dasar version control, pengelolaan repository, penggunaan perintah Git, konfigurasi lingkungan kerja, serta proses menghubungkan repository lokal dengan GitHub.

Dengan memahami materi tersebut, diharapkan peserta mampu menerapkan penggunaan Git dan GitHub untuk mengelola proyek secara lebih terstruktur, efektif, dan mendukung kolaborasi.

---

## 6. Informasi Repository

Repository ini merupakan dokumentasi pribadi kegiatan Day 1 Proyek Workshop.

Seluruh rangkuman materi dan catatan pembelajaran disusun berdasarkan materi yang disampaikan selama workshop dan digunakan sebagai referensi untuk pembelajaran selanjutnya.

**Documentation:** Day 1 EXPECTIK (Sosialisasi Jurusan) 
**Topic:** Building with AI, Managing Change with GitHub  
**Platform:** Git & GitHub

---
