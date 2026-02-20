# Flutter Provider Counter App 🚀

Project ini adalah hasil pengerjaan latihan Week 2 untuk mempelajari dan mengimplementasikan **State Management** di Flutter menggunakan *package* `Provider`. Aplikasi ini dibangun dari template bawaan Flutter yang dimodifikasi menjadi lebih terstruktur dan memiliki desain antarmuka (UI) yang lebih menarik.

## ✨ Fitur Utama
* **State Management Provider:** Bermigrasi dari penggunaan `setState` konvensional menjadi `ChangeNotifierProvider` untuk pengelolaan *state* yang lebih efisien dan terpusat.
* **Arsitektur Clean:** Struktur *project* yang rapi dengan memisahkan antara logika aplikasi di folder `models` dan antarmuka pengguna di folder `views`.
* **Increment & Decrement:** Tidak hanya tombol tambah (+), aplikasi ini juga dilengkapi dengan tombol kurang (-) yang terhubung langsung ke *model provider*.
* **Custom UI Gradient:** Menggunakan kustomisasi warna latar belakang dengan *Linear Gradient* (kombinasi warna `#1A3263` dan `#547792`) yang elegan dan modern.
* **Custom Launcher Icon:** Aplikasi sudah menggunakan ikon khusus yang di-*generate* menggunakan *package* `flutter_launcher_icons`.

## 📂 Struktur Folder

    lib/
    ├── models/
    │   └── counter_model.dart    # Berisi logika dan state aplikasi
    │
    ├── views/
    │   └── home_page.dart        # Berisi antarmuka pengguna (UI)
    │
    └── main.dart                 # Entry point dan inisialisasi Provider


## 🛠️ Cara Menjalankan Project
Pastikan Anda sudah menginstal Flutter SDK. Untuk menjalankan project ini di komputer lokal Anda:

1. **Clone repository ini**
   `git clone https://github.com/str122-xyz/Task-Week-2.git`
   `cd stateman`

2. **Install dependencies**
   `flutter pub get`

3. **Jalankan aplikasi**
   `flutter run`

---

**1123150070**<br>
**Satria Herlambang**