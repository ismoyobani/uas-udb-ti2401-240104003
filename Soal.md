# UAS UDB TI2401

## 📅 Detail Pelaksanaan

| Keterangan | Detail |
|------------|--------|
| **Hari/Tanggal** | Selasa, 20 Januari 2026 |
| **Waktu** | 08.30 - 13.00 WIB |
| **Durasi** | 4 jam 30 menit |
| **Catatan** | Harus selesai sampai dengan pembuatan laporan |

## 🎯 Passing Grade

| Kategori | Nilai Minimum |
|----------|---------------|
| **Passing Grade** | 60 |
| **With Merit** | 80 |

---

## 📋 Daftar Tugas

---

### 1. Buat Repository GitHub (5 Point)

**Ketentuan:**
- Nama repository: `uas-udb-ti2401-<nim>`
- Repository harus **public**

**Validasi:**
- ✅ URL repository harus bisa diakses public
- ✅ Nama repository harus sesuai ketentuan

**Pengurangan Nilai:**
| Kondisi | Pengurangan |
|---------|-------------|
| URL repository tidak bisa diakses public | **0 point** (dianggap tidak membuat repository) |
| Nama repository tidak sesuai ketentuan | -1 point |

---

### 2. Buat Branch Main dan Dev (5 Point)

**Ketentuan:**
- Buat branch `main` dan `dev` pada repository

**Validasi:**
- ✅ Branch `main` dan `dev` harus ada
- ✅ Nama branch harus sesuai ketentuan

**Pengurangan Nilai:**
| Kondisi | Pengurangan |
|---------|-------------|
| Nama branch tidak sesuai ketentuan | -1 point |
| Hanya terdapat 1 branch (main/dev saja) | Hanya mendapat 2 point |

---

### 3. Clone dan Push Repository Base (10 Point)

**Ketentuan:**
- Clone repository: https://github.com/rizekamaulana/uas-udb-ti2401
- Masukkan ke repository masing-masing pada branch `main` dan `dev`

**Validasi:**
- ✅ Isi repository harus memiliki fungsi yang sama dengan repository base

**Pengurangan Nilai:**
| Kondisi | Pengurangan |
|---------|-------------|
| Isi repository tidak memiliki fungsi yang sama | -5 point |
| Repository kosong | **0 point** |

---

### 4. Invite Collaborator (10 Point)

**Ketentuan:**
- Invite user `@rizekamaulana` atau `rizky_ekamaulana@udb.ac.id` sebagai collaborator

**Validasi:**
- ✅ User harus ada sebagai collaborator

**Pengurangan Nilai:**
| Kondisi | Pengurangan |
|---------|-------------|
| User tidak ada sebagai collaborator | **0 point** |
| User ada tapi tidak memiliki akses | -5 point |

---

### 5. Deploy ke Google Cloud Run (15 Point)

> 📦 **Gunakan repository `uas-udb-ti2401-<nim>` yang sudah dibuat dan disetup pada langkah 1-4**

**Ketentuan:**
- Aplikasi dari repository `uas-udb-ti2401-<nim>` harus berjalan dengan Cloud Run Google
- Aplikasi harus dapat diakses dari internet

**Detail Project:**
| Key | Value |
|-----|-------|
| Project URL | https://console.cloud.google.com/welcome/new?authuser=1&project=project-d84633c5-a53e-4ac3-9a4 |
| Project ID | `project-d84633c5-a53e-4ac3-9a4` |
| Project Name | `uas-udb-ti2401` |

**Validasi:**
- ✅ Aplikasi berjalan di Cloud Run Google pada project `uas-udb-ti2401`
- ✅ Aplikasi dapat diakses dari internet

**Pengurangan Nilai:**
| Kondisi | Pengurangan |
|---------|-------------|
| Aplikasi tidak berjalan | **0 point** |
| Aplikasi tidak dapat diakses dari internet | -5 point |

---

### 6. CI/CD Pipeline Branch Main (20 Point)

> 📦 **Gunakan repository `uas-udb-ti2401-<nim>` yang sudah dibuat dan disetup pada langkah 1-4**

**Ketentuan:**
- Buat CI/CD pipeline pada repository `uas-udb-ti2401-<nim>` dengan GitHub Actions / Push event Cloud Run Google
- Pipeline berjalan pada push event di branch `main`

**Validasi:**
- ✅ CI/CD pipeline harus ada
- ✅ Pipeline harus berjalan dengan push event pada branch `main` melalui user `@rizekamaulana` / `rizky_ekamaulana@udb.ac.id`

**Pengurangan Nilai:**
| Kondisi | Pengurangan |
|---------|-------------|
| User `@rizekamaulana` tidak bisa melakukan push event | -10 point |
| CI/CD pipeline tidak berjalan sama sekali / tidak berhasil | **0 point** |

---

### 7. CI/CD Pipeline Branch Dev (20 Point)

> 📦 **Gunakan repository `uas-udb-ti2401-<nim>` yang sudah dibuat dan disetup pada langkah 1-4**

**Ketentuan:**
- Buat CI/CD pipeline pada repository `uas-udb-ti2401-<nim>` dengan GitHub Actions / Push event Cloud Run Google
- Pipeline berjalan pada push event di branch `dev`

**Validasi:**
- ✅ CI/CD pipeline harus ada
- ✅ Pipeline harus berjalan dengan push event pada branch `dev` melalui user `@rizekamaulana` / `rizky_ekamaulana@udb.ac.id`

**Pengurangan Nilai:**
| Kondisi | Pengurangan |
|---------|-------------|
| User `@rizekamaulana` tidak bisa melakukan push event | -10 point |
| CI/CD pipeline tidak berjalan sama sekali / tidak berhasil | **0 point** |

---

### 8. Submit Laporan (15 Point) ⚠️ WAJIB

> 🚨 **WAJIB: Jika tidak submit laporan, maka TOTAL NILAI dikurangi 50%**

**Ketentuan:**
- Submit laporan cara pengerjaan pada Google Form berikut:
- 🔗 **https://forms.gle/r59GCpMW1zodGyTA7**

**Validasi:**
- ✅ Report dibuat dan dikirim

**Pengurangan Nilai:**
| Kondisi | Pengurangan |
|---------|-------------|
| Tidak mengirim report sama sekali | **Total nilai × 50%** |
| Kirim report seadanya / full prompt AI | -5 point |

---

## 📊 Ringkasan Penilaian

| No | Tugas | Point |
|----|-------|-------|
| 1 | Buat Repository GitHub | 5 |
| 2 | Buat Branch Main dan Dev | 5 |
| 3 | Clone dan Push Repository Base | 10 |
| 4 | Invite Collaborator | 10 |
| 5 | Deploy ke Google Cloud Run | 15 |
| 6 | CI/CD Pipeline Branch Main | 20 |
| 7 | CI/CD Pipeline Branch Dev | 20 |
| 8 | Submit Laporan | 15 |
| | **Total** | **100** |

---

## 📌 Catatan Penting

> ⚠️ **Semua tugas harus diselesaikan dalam waktu yang ditentukan (08.30 - 13.00 WIB)**
> 
> ✅ **Passing Grade: 60** — Nilai minimum untuk lulus
> 
> 🏆 **With Merit: 80** — Nilai untuk mendapat predikat merit/Grade A
>
> 🚨 **Submit Laporan WAJIB** — Jika tidak submit, total nilai dikurangi 50%

---

## 📈 Simulasi Penilaian

### Contoh 1: Nilai Sempurna (Submit Laporan ✅)

| No | Tugas | Point Maksimal | Point Didapat |
|----|-------|----------------|---------------|
| 1 | Buat Repository GitHub | 5 | 5 |
| 2 | Buat Branch Main dan Dev | 5 | 5 |
| 3 | Clone dan Push Repository Base | 10 | 10 |
| 4 | Invite Collaborator | 10 | 10 |
| 5 | Deploy ke Google Cloud Run | 15 | 15 |
| 6 | CI/CD Pipeline Branch Main | 20 | 20 |
| 7 | CI/CD Pipeline Branch Dev | 20 | 20 |
| 8 | Submit Laporan | 15 | 15 |
| | **Total** | **100** | **100** ✅ |

**Hasil:** 100 point → **With Merit/Grade A** 🏆

---

### Contoh 2: Nilai Baik (Submit Laporan ✅)

| No | Tugas | Point Maksimal | Point Didapat | Keterangan |
|----|-------|----------------|---------------|------------|
| 1 | Buat Repository GitHub | 5 | 5 | ✅ |
| 2 | Buat Branch Main dan Dev | 5 | 5 | ✅ |
| 3 | Clone dan Push Repository Base | 10 | 10 | ✅ |
| 4 | Invite Collaborator | 10 | 10 | ✅ |
| 5 | Deploy ke Google Cloud Run | 15 | 15 | ✅ |
| 6 | CI/CD Pipeline Branch Main | 20 | 20 | ✅ |
| 7 | CI/CD Pipeline Branch Dev | 20 | 0 | CI/CD tidak berhasil |
| 8 | Submit Laporan | 15 | 15 | ✅ |
| | **Total** | **100** | **80** ✅ |

**Hasil:** 80 point → **With Merit/Grade A** 🏆

---

### Contoh 3: Nilai Cukup (Submit Laporan ✅)

| No | Tugas | Point Maksimal | Point Didapat | Keterangan |
|----|-------|----------------|---------------|------------|
| 1 | Buat Repository GitHub | 5 | 5 | ✅ |
| 2 | Buat Branch Main dan Dev | 5 | 5 | ✅ |
| 3 | Clone dan Push Repository Base | 10 | 10 | ✅ |
| 4 | Invite Collaborator | 10 | 10 | ✅ |
| 5 | Deploy ke Google Cloud Run | 15 | 15 | ✅ |
| 6 | CI/CD Pipeline Branch Main | 20 | 0 | Pipeline tidak jalan |
| 7 | CI/CD Pipeline Branch Dev | 20 | 0 | Pipeline tidak jalan |
| 8 | Submit Laporan | 15 | 15 | ✅ |
| | **Total** | **100** | **60** ✅ |

**Hasil:** 60 point → **LULUS** (Passing Grade) ✅

---

### Contoh 4: Tidak Submit Laporan ❌ (Penalti 50%)

| No | Tugas | Point Maksimal | Point Didapat | Keterangan |
|----|-------|----------------|---------------|------------|
| 1 | Buat Repository GitHub | 5 | 5 | ✅ |
| 2 | Buat Branch Main dan Dev | 5 | 5 | ✅ |
| 3 | Clone dan Push Repository Base | 10 | 10 | ✅ |
| 4 | Invite Collaborator | 10 | 10 | ✅ |
| 5 | Deploy ke Google Cloud Run | 15 | 15 | ✅ |
| 6 | CI/CD Pipeline Branch Main | 20 | 20 | ✅ |
| 7 | CI/CD Pipeline Branch Dev | 20 | 20 | ✅ |
| 8 | Submit Laporan | 15 | 0 | ❌ Tidak submit |
| | **Subtotal** | **100** | **85** | |
| | **Penalti (50%)** | | **-42.5** | ❌ Tidak submit laporan |
| | **Total Akhir** | | **42.5** ❌ |

**Hasil:** 42.5 point → **TIDAK LULUS** ❌ (di bawah Passing Grade 60)

---

### Contoh 5: Nilai Sempurna Tapi Tidak Submit Laporan ❌

| No | Tugas | Point Maksimal | Point Didapat | Keterangan |
|----|-------|----------------|---------------|------------|
| 1 | Buat Repository GitHub | 5 | 5 | ✅ |
| 2 | Buat Branch Main dan Dev | 5 | 5 | ✅ |
| 3 | Clone dan Push Repository Base | 10 | 10 | ✅ |
| 4 | Invite Collaborator | 10 | 10 | ✅ |
| 5 | Deploy ke Google Cloud Run | 15 | 15 | ✅ |
| 6 | CI/CD Pipeline Branch Main | 20 | 20 | ✅ |
| 7 | CI/CD Pipeline Branch Dev | 20 | 20 | ✅ |
| 8 | Submit Laporan | 15 | 0 | ❌ Tidak submit |
| | **Subtotal** | **100** | **85** | |
| | **Penalti (50%)** | | **-42.5** | ❌ Tidak submit laporan |
| | **Total Akhir** | | **42.5** ❌ |

**Hasil:** 42.5 point → **TIDAK LULUS** ❌ 

> ⚠️ **Meskipun semua tugas teknis sempurna, tanpa submit laporan tetap TIDAK LULUS!**