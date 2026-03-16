# KBBI Python Wrapper

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Pustaka Python sederhana untuk melakukan pencarian kata atau istilah dalam Kamus Besar Bahasa Indonesia (KBBI) secara terprogram. Proyek ini mempermudah pengembang untuk mengintegrasikan data KBBI ke dalam aplikasi mereka tanpa harus melakukan scraping manual.

## ✨ Fitur Utama

- **Pencarian Kata:** Mengambil definisi, kelas kata (nomina, verba, dll.), dan contoh penggunaan kata.
- **Dukungan Entri Ganda:** Menangani kata-kata yang memiliki lebih dari satu arti atau homonim.
- **Parsing Bersih:** Hasil ekstraksi data disajikan dalam format yang mudah diolah (objek Python/JSON).
- **Ringan:** Minimal ketergantungan (dependencies), fokus pada kecepatan dan kemudahan penggunaan.

## 🛠️ Teknologi yang Digunakan

- **Python 3.x**: Bahasa pemrograman utama.
- **Requests**: Untuk menangani permintaan HTTP ke situs KBBI.
- **BeautifulSoup4**: Untuk melakukan *parsing* atau ekstraksi data dari struktur HTML KBBI.

## 📋 Prasyarat Instalasi

Pastikan Anda sudah menginstal Python di sistem Anda. Instal pustaka yang diperlukan menggunakan pip:

```bash
pip install requests beautifulsoup4
