# Seminar Registration App - UTS Pemrograman Mobile 1

Aplikasi Pendaftaran Seminar Mahasiswa berbasis Android yang dibangun menggunakan **Jetpack Compose** dan **Material Design 3**. Aplikasi ini dirancang dengan antarmuka modern menggunakan tema *Glassmorphism* dan gradasi warna biru yang konsisten.

## 🚀 Fitur Utama
- **Autentikasi**: Fitur Login dan Register untuk keamanan akses.
- **Dashboard Utama**: Menampilkan profil singkat pengguna dan kartu informasi event.
- **Form Pendaftaran Seminar**:
  - Input: Nama, Email, No. WhatsApp, Jenis Kelamin (Button-style), dan Topik Seminar (Dropdown).
  - **Validasi Real-time**: Error muncul saat mengetik jika data tidak valid (Email, Phone, Required Fields).
  - **Responsif**: Layout menyesuaikan ukuran layar (HP & Tablet).
- **Dialog Konfirmasi**: Memastikan data sudah benar sebelum dikirim.
- **Halaman Hasil**: Ringkasan data pendaftaran setelah berhasil submit.
- **Profil & Pengaturan**: Dilengkapi dengan menu pengaturan profil dan fitur **Logout**.
- **Bottom Navigation**: Navigasi cepat antara Home, Form Daftar, dan Profil.

## 🛠️ Tech Stack
- **Language**: Kotlin
- **UI Framework**: Jetpack Compose (Material 3)
- **Navigation**: Jetpack Navigation Compose
- **Design Pattern**: Single Activity Architecture

## 🔑 Akun Demo (Hardcoded)
- **Username**: `revana`
- **Password**: `revana123`

## 🎥 Video Penjelasan (Link)
https://youtu.be/8tvfLKPaTf0?si=MXNA8DP5ZaxB7Fa1

---

## 📸 Tampilan Aplikasi
Fitur Login
<img width="250" height="370" alt="LOGIN" src="https://github.com/user-attachments/assets/6c95a12b-36af-4a6e-a27c-bd56b9f52511" />

Fitur Register
<img width="250" height="370" alt="REGISTER" src="https://github.com/user-attachments/assets/906ee85c-5746-46b3-add1-d568a567b8b0" />

Fitur Daftar Seminar
<img width="250" height="370" alt="SEMINAR" src="https://github.com/user-attachments/assets/5a98d44c-9e41-4e27-ac79-e6dcda078ba8" />





---

## 📂 Struktur Proyek
- `MainActivity.kt`: Pusat kontrol navigasi aplikasi.
- `model/`: Data class untuk menampung informasi pendaftaran.
- `screens/`: Folder berisi semua halaman UI (Login, Register, Home, Form, Result, Profile).
- `ui/theme/`: Konfigurasi tema, warna, tipografi, dan background gradasi.

## ⚙️ Cara Menjalankan
1. Clone repository ini.
2. Buka di **Android Studio Ladybug** atau versi terbaru.
3. Lakukan **Gradle Sync**.
4. Run pada Emulator atau Perangkat Fisik (Android API 24+).

---
**Create by:** [RevanaRauf]

