# DAY 1 – EXPECTIK 2026
## Building with AI, Managing Change with GitHub

---

| Keterangan | Informasi |
|---|---|
| Nama Lengkap | Lu'lu'ah Nafisa |
| Nama Kelompok | 10_FC27 |
| Kelas | Teknik Informatika - 1A |
| Materi | Pengenalan Git & GitHub |

---

## 2. Deskripsi Repository

Repository ini dibuat sebagai bentuk dokumentasi kegiatan day 1 EXPECTIK 2026, yang berfokus pada kegiatan sosialisasi jurusan dan workshop dengan tema **"Building with AI, Managing Change with GitHub"**. Di dalamnya terdapat rangkuman materi, catatan pembelajaran, serta berbagai pengetahuan yang diperoleh selama kegiatan, khususnya mengenai penggunaan Git dan GitHub dalam pengelolaan proyek, version control, dan kolaborasi pengembangan perangkat lunak.

## 3. Tujuan Repository

Repository ini bertujuan untuk mendokumentasikan kegiatan dan materi pembelajaran selama day 1 EXPECTIK sekaligus menjadi tempat penyimpanan catatan dan referensi dalam memahami penggunaan Git dan GitHub untuk mendukung proses pengembangan perangkat lunak.

---

## 4. Dokumentasi Kegiatan Workshop

### A. Rangkuman Materi Workshop

#### 1. Pengertian Git

Git merupakan **Version Control System (VCS)** yang digunakan untuk melacak dan mengelola perubahan file dalam suatu proyek. Git diciptakan oleh Linus Torvalds pada tahun 2005 untuk membantu pengelolaan perubahan proyek secara terstruktur.

#### 2. Pengertian GitHub

GitHub merupakan platform berbasis web yang digunakan untuk menyimpan repository Git secara online serta mendukung kolaborasi antar pengguna dalam pengembangan proyek.

#### 3. Perbedaan Git dan GitHub

| Git | GitHub |
|---|---|
| Sistem version control terdistribusi (DVCS). | Platform berbasis web. |
| Mengelola perubahan file secara lokal. | Menyimpan repository Git secara online. |
| Dapat digunakan melalui terminal atau command line. | Dapat diakses melalui browser. |
| Berfokus pada pengelolaan versi proyek. | Mendukung penyimpanan dan kolaborasi proyek. |

#### 4. Git Workflow

Git Workflow merupakan alur kerja Git dalam mengelola perubahan file. Terdapat tiga komponen utama, yaitu:

- **Working Directory:** Tempat pengguna mengerjakan, membuat, dan memodifikasi file proyek.
- **Staging Area:** Tempat menampung perubahan file yang akan dimasukkan ke dalam commit berikutnya.
- **Git Directory (Repository):** Tempat Git menyimpan metadata dan object database yang dibutuhkan untuk mengelola perubahan proyek.

Alur Git Workflow:

`Working Directory → Staging Area → Git Directory`

#### 5. Essential Git Commands

Beberapa perintah dasar Git yang digunakan dalam pengelolaan repository:

| Perintah | Fungsi |
|---|---|
| `git init` | Menginisialisasi repository Git baru. |
| `git add .` | Menambahkan perubahan file ke Staging Area. |
| `git add --all` | Menambahkan seluruh perubahan dalam repository ke Staging Area. |
| `git add -A` | Menambahkan seluruh perubahan dalam repository ke Staging Area. |
| `git commit -m "message"` | Menyimpan perubahan ke dalam riwayat repository. |
| `git remote add origin <url>` | Menghubungkan repository lokal dengan repository remote. |
| `git push origin main` | Mengirim perubahan dari branch lokal ke repository remote. |
| `git pull origin main` | Mengambil perubahan dari repository remote dan menggabungkannya ke branch lokal. |
| `git clone <url>` | Menyalin repository remote ke komputer lokal. |

#### 6. Git Setup

Git Setup merupakan proses instalasi dan konfigurasi Git sebelum digunakan. Setelah instalasi, versi Git dapat diperiksa menggunakan `git --version`, sedangkan identitas pengguna diatur melalui konfigurasi nama dan email.

```bash
git --version

git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"

git config --global --list
```

#### 7. VS Code Setup

Visual Studio Code (VS Code) merupakan code editor yang digunakan untuk membantu proses pengembangan proyek. Agar VS Code dapat diakses melalui terminal, diperlukan pengaturan Shell Command: Install 'code' command in PATH, kemudian instalasinya dapat diperiksa menggunakan perintah berikut:

```bash
code --version
```

#### 8. Menghubungkan Repository Lokal dengan GitHub

Repository lokal dapat dihubungkan dengan GitHub melalui dua cara, yaitu menginisialisasi folder proyek menggunakan `git init` atau menyalin repository yang sudah tersedia di GitHub menggunakan `git clone`. Untuk melakukan clone, URL repository dapat disalin melalui tombol **Code** pada halaman repository GitHub.

```bash
git init
```

atau

```bash
git clone <repository-url>
```

#### 9. Working Area ke Staging Area

Perubahan file dari Working Directory dapat dipindahkan ke Staging Area menggunakan beberapa perintah Git, seperti:

```bash
git add --all
git add -A
git add .
git add *
```

Perintah tersebut digunakan untuk menambahkan file atau perubahan ke Staging Area dengan cakupan yang dapat berbeda sesuai perintahnya.

#### 10. SSH Key Configuration

SSH Key merupakan metode autentikasi yang digunakan untuk menghubungkan komputer lokal dengan GitHub. Dalam workshop, pembuatan SSH Key menggunakan algoritma Ed25519, kemudian public key ditambahkan ke pengaturan **SSH and GPG keys** pada akun GitHub.

```bash
ssh-keygen -t ed25519 -C "email@domain.com"
```

Untuk memeriksa koneksi SSH dengan GitHub, gunakan perintah:

```bash
ssh -T git@github.com
```

Jika autentikasi berhasil, GitHub akan menampilkan pesan bahwa pengguna berhasil melakukan autentikasi.

---

### B. Poin-Poin Penting dan Pengetahuan Baru

1. Git dan GitHub memiliki fungsi yang berbeda. Git digunakan untuk mengelola perubahan proyek, sedangkan GitHub menjadi platform untuk menyimpan repository secara online dan mendukung kolaborasi.
2. Git Workflow terdiri dari tiga komponen utama, yaitu Working Directory, Staging Area, dan Git Directory, yang masing-masing memiliki peran dalam proses pengelolaan perubahan file.
3. Proses penyimpanan perubahan dalam Git dilakukan melalui tahapan `git add` untuk menyiapkan perubahan dan `git commit` untuk menyimpannya ke dalam riwayat repository.
4. Perintah `git push` dan `git pull` digunakan untuk mengirim dan mengambil perubahan antara repository lokal dan repository remote.
5. SSH Key menjadi salah satu metode autentikasi yang dapat digunakan untuk menghubungkan komputer lokal dengan GitHub.
6. Dalam penggunaan AI, penyusunan prompt perlu memperhatikan Role, Task, Context, dan Format agar hasil yang diberikan lebih sesuai dengan kebutuhan.

---

### C. Pendapat Pribadi tentang Day 1 EXPECTIK

Menurut saya, kegiatan Day 1 EXPECTIK cukup menarik karena memberikan banyak pengetahuan baru, terutama tentang Git dan GitHub yang ternyata memiliki peran penting dalam pengembangan perangkat lunak. Dari materi yang disampaikan, saya jadi lebih mengenal cara mengelola perubahan pada proyek, menyimpan riwayat pekerjaan, dan menghubungkan repository lokal dengan GitHub. Materi ini juga membuat saya lebih memahami pentingnya version control agar pengerjaan proyek lebih teratur dan memudahkan kolaborasi dengan orang lain. Tentunya, pengetahuan ini akan sangat berguna untuk menunjang proses pembelajaran dan pengerjaan proyek ke depannya.

---
