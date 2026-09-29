# Belajar React Native CRUD Sederhana

Aplikasi mobile sederhana untuk melakukan proses CRUD (Create, Read, Update, Delete) data Post menggunakan React Native dan REST API dari Express.js.

Project ini dibuat untuk memenuhi tugas UTS Mobile Programming.

---

# 1. Fitur Aplikasi

Aplikasi memiliki beberapa fitur utama:

- Menampilkan daftar Post
- Menampilkan detail data Post untuk proses Edit
- Menambahkan Post baru
- Mengupload gambar
- Mengedit Post
- Mengganti gambar Post
- Menghapus Post
- Validasi data dari Backend API
- Navigasi antar halaman
- Komunikasi dengan REST API menggunakan Axios

---

# 2. Teknologi yang Digunakan

## Frontend

- React Native CLI
- React Navigation
- Axios
- React Native Image Picker
- React Native Dotenv

## Backend

- Node.js
- Express.js
- REST API
- MySQL

## Development Tools

- Visual Studio Code
- Android Studio
- Android Emulator
- Git
- GitHub

> Project ini menggunakan React Native CLI dan bukan Expo.

---

# 3. Arsitektur Aplikasi

Aplikasi menggunakan arsitektur sederhana sebagai berikut:

```text
┌──────────────────────┐
│   React Native App   │
│      Android         │
└──────────┬───────────┘
           │
           │ REST API
           │ Port 3000
           ▼
┌──────────────────────┐
│    Express.js API    │
│      Backend         │
└──────────┬───────────┘
           │
           │ Database
           ▼
┌──────────────────────┐
│        MySQL         │
└──────────────────────┘