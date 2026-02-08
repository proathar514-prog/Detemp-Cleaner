# Detemp-Cleaner
<div align="center">

  <a href="https://youtube.com/@lacoffline" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
  </a>
  &nbsp;
  <a href="https://instagram.com/@offlinelac" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
  &nbsp;
  <a href="https://tiktok.com/@offlinelac" target="_blank">
    <img src="https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white" alt="TikTok" />
  </a>

</div>

# 🛠️ Windows System Maintenance: Temp & Prefetch

Panduan singkat mengenai ciri-ciri dan fungsi folder file sementara pada **Windows 10** dan **Windows 11**.

---

## 📂 Ringkasan Lokasi Folder

| Nama Folder | Command (Win + R) | Path Direktori | Fungsi |
| :--- | :--- | :--- | :--- |
| **User Temp** | `%temp%` | `C:\Users\[User]\AppData\Local\Temp` | Cache aplikasi pengguna. |
| **System Temp** | `temp` | `C:\Windows\Temp` | File sementara sistem operasi. |
| **Prefetch** | `prefetch` | `C:\Windows\Prefetch` | Cache peluncuran aplikasi. |

---

## 🔍 Ciri-Ciri & Karakteristik

### 1. User Temp (`%temp%`)
Folder ini adalah tempat aplikasi pihak ketiga (seperti Chrome, Adobe, atau Game) menyimpan data sementara.
* **Ciri Visual:** Banyak file dengan ekstensi `.tmp`, `.log`, dan folder dengan nama acak.
* **Kapan Dihapus:** Aman dihapus kapan saja untuk melegakan penyimpanan.
* **Catatan:** Jika ada file yang tidak bisa dihapus, berarti aplikasi terkait sedang berjalan.

### 2. Windows Temp (`temp`)
Dikelola oleh sistem operasi Windows sendiri.
* **Ciri Visual:** Seringkali memerlukan izin Administrator untuk membukanya. Berisi log update atau installer Windows.
* **Penting:** Membersihkan folder ini membantu jika Anda mengalami masalah saat instalasi software baru.

### 3. Prefetch
Mekanisme Windows untuk mempercepat waktu *loading* aplikasi.
* **Ciri Visual:** Berisi file dengan ekstensi `.pf` (Contoh: `CHROME.EXE-A1B2C3D4.pf`).
* **Fungsi:** Menyimpan informasi tentang file yang dibutuhkan aplikasi saat startup.
* **Mitos:** Menghapus Prefetch tidak menambah RAM, tapi berguna untuk membuang jejak aplikasi yang sudah tidak terpakai (Uninstalled).

---

# 🛠️ Windows System Maintenance: Temp & Prefetch

Panduan singkat mengenai ciri-ciri dan fungsi folder file sementara pada **Windows 10** dan **Windows 11**.

---

## 📂 Ringkasan Lokasi Folder

| Nama Folder | Command (Win + R) | Path Direktori | Fungsi |
| :--- | :--- | :--- | :--- |
| **User Temp** | `%temp%` | `C:\Users\[User]\AppData\Local\Temp` | Cache aplikasi pengguna. |
| **System Temp** | `temp` | `C:\Windows\Temp` | File sementara sistem operasi. |
| **Prefetch** | `prefetch` | `C:\Windows\Prefetch` | Cache peluncuran aplikasi. |

---

## 🔍 Ciri-Ciri & Karakteristik

### 1. User Temp (`%temp%`)
Folder ini adalah tempat aplikasi pihak ketiga (seperti Chrome, Adobe, atau Game) menyimpan data sementara.
* **Ciri Visual:** Banyak file dengan ekstensi `.tmp`, `.log`, dan folder dengan nama acak.
* **Kapan Dihapus:** Aman dihapus kapan saja untuk melegakan penyimpanan.
* **Catatan:** Jika ada file yang tidak bisa dihapus, berarti aplikasi terkait sedang berjalan.

### 2. Windows Temp (`temp`)
Dikelola oleh sistem operasi Windows sendiri.
* **Ciri Visual:** Seringkali memerlukan izin Administrator untuk membukanya. Berisi log update atau installer Windows.
* **Penting:** Membersihkan folder ini membantu jika Anda mengalami masalah saat instalasi software baru.

### 3. Prefetch
Mekanisme Windows untuk mempercepat waktu *loading* aplikasi.
* **Ciri Visual:** Berisi file dengan ekstensi `.pf` (Contoh: `CHROME.EXE-A1B2C3D4.pf`).
* **Fungsi:** Menyimpan informasi tentang file yang dibutuhkan aplikasi saat startup.
* **Mitos:** Menghapus Prefetch tidak menambah RAM, tapi berguna untuk membuang jejak aplikasi yang sudah tidak terpakai (Uninstalled).

---

## 💡 Tips Pembersihan (Shortcut)

Anda bisa membersihkan ketiga folder di atas secara otomatis menggunakan file batch. Simpan kode di bawah ini sebagai ``cleaner.bat``:
--

<img width="228" height="134" alt="Image" src="https://github.com/user-attachments/assets/6f0918ec-6b2b-41f7-89f0-4f3dbda9eae1" />

https://github.com/user-attachments/assets/bf383bdf-166f-45fd-8947-e36e458becfe
