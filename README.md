## 🚀 Panduan Kontribusi

Panduan ini dibuat khusus untuk anggota kelompok yang masih baru dengan Git dan GitHub. Kita akan menggunakan **Visual Studio Code** agar prosesnya lebih mudah dan visual.

### Yang Perlu Disiapkan (Hanya sekali di awal)

1.  **Install Git**: Pastikan Git sudah ter-install di komputermu. Download di [git-scm.com](https://git-scm.com/downloads/).
2.  **Install Visual Studio Code**: Ini adalah editor kode kita. Download di [code.visualstudio.com](https://code.visualstudio.com/download).
3.  **Login GitHub di VS Code**:
    * Buka VS Code.
    * Klik ikon **Accounts** di pojok kiri bawah (bentuknya seperti orang).
    * Pilih "Sign in with GitHub to use GitHub Copilot and more..." dan ikuti proses login di browser.

### Langkah-Langkah Mengerjakan Proyek

#### 1. Clone Repository (Mengambil Proyek dari GitHub ke Komputer)

Ini hanya perlu dilakukan **satu kali** di awal.

1.  Buka halaman repository ini di GitHub.
2.  Klik tombol hijau **`< > Code`**.
3.  Salin link **HTTPS** yang muncul. (Contoh: `https://github.com/NasiGakPakeNasi/Pemrograman_Web.git`)
4.  Buka VS Code.
5.  Tekan `Ctrl+Shift+P` untuk membuka Command Palette, lalu ketik `Git: Clone` dan tekan Enter.
6.  Paste link yang tadi kamu salin, lalu tekan Enter.
7.  Pilih lokasi folder di komputermu untuk menyimpan proyek ini.
8.  Setelah selesai, klik **"Open Repository"**.

#### 2. Mengambil Update Terbaru dari Teman (`Pull`)

**PENTING:** Lakukan ini **setiap kali kamu akan mulai mengerjakan sesuatu** agar kodemu selalu yang paling baru dan tidak bentrok dengan pekerjaan temanmu.

1.  Buka proyek ini di VS Code.
2.  Lihat di pojok kiri bawah layar, ada tombol **Sync Changes** (biasanya ada ikon awan atau panah melingkar).
3.  **Klik tombol itu**. VS Code akan otomatis mengambil (`pull`) perubahan terbaru dari GitHub dan mengirim (`push`) perubahanmu jika ada.

![Contoh Tombol Sync Changes di VS Code](https://code.visualstudio.com/assets/docs/sourcecontrol/git/sync.png)

#### 3. Mengerjakan Tugas dan Mengirim Perubahan (`Push`)

1.  **Edit Kode:** Silakan buka file HTML/CSS/JS yang mau kamu kerjakan dan ubah sesuai tugasmu. Simpan file (`Ctrl+S`).
2.  **Buka Tab Source Control:** Klik ikon ke-tiga dari atas di menu sebelah kiri (logo seperti percabangan).
3.  **Tulis Pesan Perubahan (Commit Message):** Di atas daftar file yang berubah, ada kolom "Message". Tulis pesan singkat tentang apa yang kamu ubah.
    * *Contoh bagus:* `Menambahkan footer di halaman utama`, `Memperbaiki warna tombol login`.
    * *Contoh kurang bagus:* `update`, `perubahan`, `wkwk`.
4.  **Commit:** Klik tombol **"Commit"** berwarna biru. Ini seperti menyimpan "snapshot" dari perubahanmu secara lokal.
5.  **Kirim ke GitHub (Push):** Klik tombol **"Sync Changes"** di pojok kiri bawah (sama seperti langkah `pull`). Perubahanmu sekarang akan terkirim ke GitHub dan bisa dilihat oleh teman-teman lain.

Itu saja! Dengan mengikuti alur ini, kita bisa bekerja sama tanpa harus pusing dengan perintah-perintah yang rumit.

### ✨ Tips Tambahan

* **Komunikasi!** Selalu bilang di grup kalau kamu mau mengerjakan file `A.html` agar tidak ada orang lain yang mengerjakan file yang sama di waktu bersamaan.
* **Selalu `Pull` (Sync Changes) sebelum mulai coding.** Ini adalah kebiasaan paling penting untuk menghindari konflik.
* **Tulis pesan commit yang jelas.** Ini sangat membantu kita semua untuk tahu riwayat perubahan proyeknya.

Semangat Mengerjakannya, Tim! 🔥
