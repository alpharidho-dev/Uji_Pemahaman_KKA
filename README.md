# 🚗 Rental Kendaraan CLI App

Aplikasi command-line untuk sistem registrasi, login, dan penyewaan kendaraan (motor, mobil, kereta api) dengan keamanan password menggunakan hashing SHA-256.

## ✨ Fitur

- **Registrasi pengguna baru** – Nama, username, email, dan password (disimpan dalam bentuk hash).
- **Login aman** – Verifikasi username dan password terhash.
- **Dashboard penyewaan** – Pilihan kendaraan: Motor, Mobil, Kereta Api (dengan simulasi server down).
- **Logout** – Kembali ke menu utama.
- **Efek mengetik** – Animasi teks seperti sedang mengetik.
- **Persistensi data** – Data pengguna disimpan dalam file `data_user.json`.
- **Cross-platform** – Bekerja di Windows, Linux, dan macOS.

## 🛠️ Teknologi yang Digunakan

- **Python 3.x**
- Modul standar:
  - `json` – menyimpan dan membaca data pengguna
  - `hashlib` – hashing password dengan algoritma SHA-256
  - `os` – membersihkan layar terminal
  - `time` – efek jeda dan animasi

## 📦 Instalasi

1. Pastikan Python 3 terinstal di sistem Anda.
2. Clone atau unduh file `register`.
3. Jalankan program:
   ```bash
