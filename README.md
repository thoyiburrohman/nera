# Nera

**Nera** adalah aplikasi **catatan keuangan pribadi** berbasis web (PWA) yang sederhana, tenang, dan fokus pada kebiasaan mencatat uang sehari-hari.

Tidak ribet, tidak berisik, tidak berlebihan.  
Dirancang untuk dipakai **setiap hari**, bukan sekadar dicoba lalu ditinggal.

---

## ✨ Fitur Utama

- 📒 **Catatan pemasukan & pengeluaran**
- 💰 **Saldo otomatis**
- 📸 **Scan struk (OCR)**
  - Ambil **total belanja**
  - Item masuk ke **deskripsi**
- 🗑️ **Soft delete + Trash**
  - Salah hapus bisa dipulihkan
- 📱 **PWA (Installable)**
  - Bisa di-install dari Chrome
  - Fullscreen seperti aplikasi native
- 💾 **Offline & lokal**
  - Data disimpan di browser (localStorage)
- 🎨 **UI tenang & minimal**
  - Dirancang untuk penggunaan jangka panjang

---

## 🧠 Filosofi

> *Uang adalah alat, bukan tujuan.*  
> *Mencatat bukan soal kontrol berlebihan, tapi kesadaran.*

Nera tidak mencoba “mengatur hidupmu”.  
Ia hanya membantu kamu **melihat dengan jujur**.

---

## 🖥️ Teknologi

- **HTML5**
- **Tailwind CSS (CDN)**
- **Alpine.js**
- **Tesseract.js (OCR)**
- **PWA (Manifest + Installable)**

Tanpa backend.  
Tanpa database server.  
Tanpa akun.

---

## 📦 Instalasi & Penggunaan

### 1. Jalankan Lokal
Cukup klik link:

```url
https://thoyiburrohman.github.io/nera/
```

## ⚠️ Catatan Penting tentang Scan Struk

Fitur **Scan Struk** di Nera menggunakan teknologi OCR (Optical Character Recognition) untuk membantu mengisi data transaksi.

Perlu diperhatikan:

- **Nominal (Total)**
  - Nominal diambil dari teks yang terdeteksi sebagai *TOTAL / JUMLAH* pada struk.
  - Hasil OCR **bisa keliru** tergantung:
    - kualitas foto
    - pencahayaan
    - format struk
  - **Selalu cek ulang nominal sebelum menyimpan transaksi.**

- **Deskripsi / Item Belanja**
  - Item yang muncul di kolom deskripsi diambil dari baris teks yang *diduga* sebagai item belanja.
  - Nama item **tidak selalu akurat** dan bisa mengandung kesalahan OCR.
  - Deskripsi bersifat **bantuan visual**, bukan data finansial utama.

- **Rekomendasi**
  - Gunakan scan struk sebagai **alat bantu**, bukan sumber kebenaran mutlak.
  - Lakukan **pengecekan manual** sebelum menekan tombol *Simpan*.

Nera sengaja tidak melakukan koreksi otomatis atau validasi agresif,  
karena tujuan utamanya adalah **kesadaran dan kesederhanaan**, bukan otomatisasi penuh.

