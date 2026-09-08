# LAB-AP-17-2026
# Repository Tugas Lab Algoritma dan Pemrograman

Repository ini digunakan sebagai media pengumpulan tugas praktikum **Algoritma dan Pemrograman**.

Setiap mahasiswa wajib mengikuti alur pengumpulan sesuai format dan ketentuan yang telah ditentukan.

---

## Persiapan (Requirements)

Pastikan sudah memiliki:

1. Akun [GitHub](https://github.com/)
2. [Git](https://git-scm.com/) yang telah terinstall

Cek instalasi Git:

```bash
git --version
```

---

# Alur Pengumpulan Tugas

## 1. Fork Repository

Buka repository utama:

[**https://github.com/Marchegatriani/LAB-AP-17-2026**](https://github.com/Marchegatriani/LAB-AP-17-2026)

Klik **Fork** untuk membuat salinan repository ke akun GitHub masing-masing.

---

## 2. Clone Repository

Clone repository hasil fork:

```bash
git clone https://github.com/USERNAME_ANDA/LAB-AP-17-2026.git
cd LAB-AP-17-2026
```

Ganti `USERNAME_ANDA` dengan username GitHub masing-masing.

---

## 3. Konfigurasi Git

Jika belum pernah melakukan konfigurasi Git:

```bash
git config --global user.name "USERNAME_GITHUB_ANDA"
git config --global user.email "emailanda@gmail.com"
```

---

## 4. Buat Branch dengan Nama NIM

Buat branch menggunakan **NIM**:

```bash
git switch -c NIM_ANDA
```

Contoh:

```bash
git switch -c H071261054
```

Cek branch yang sedang aktif:

```bash
git branch
```

Branch aktif ditandai dengan `*`.

---

## 5. Buat Folder NIM dan Praktikum

Buat folder menggunakan **NIM**, kemudian buat folder `Praktikum-n` sesuai nomor praktikum.

Contoh:

```bash
mkdir H071261054
cd H071261054
mkdir Praktikum-1
cd Praktikum-1
```

---

# Format Penamaan File

Gunakan format:

```text
TPn_noSoal_xxx.py
```

Keterangan:

- `TPn` = Tugas Praktikum ke-n
- `noSoal` = Nomor soal
- `xxx` = 3 digit terakhir NIM
- `.py` = Ekstensi Python

### Contoh

Untuk NIM `H071261054`:

```text
LAB-AP-2026/
└── H071261054/
    └── Praktikum-1/
        ├── TP1_1_054.py
        ├── TP1_2_054.py
        └── TP1_3_054.py
```

> **Catatan:** Folder dan branch menggunakan **NIM lengkap**

---

# Commit dan Push

Setelah tugas selesai dan diasistensikan:

### 1. Cek perubahan

```bash
git status
```

### 2. Tambahkan file

```bash
git add H071261054/Praktikum-1/TP1_1_054.py
```

### 3. Commit

```bash
git commit -m "Menambahkan TP1 soal 1"
```

### 4. Push

Gunakan branch NIM:

```bash
git push origin H071261054
```

---

# Pull Request

Setelah berhasil melakukan push:

1. Buka repository hasil fork di GitHub.
2. Pilih branch **NIM**.
3. Klik **Compare & pull request**.
4. Pastikan **Base repository** adalah repository utama.
5. Pastikan **Compare branch** adalah branch NIM Anda.
6. Periksa kembali file tugas.
7. Klik **Create Pull Request**.

> ⚠️ **PENTING:** Jangan membuat Pull Request dari branch `main`. Pastikan Pull Request dibuat dari branch **NIM masing-masing**.
