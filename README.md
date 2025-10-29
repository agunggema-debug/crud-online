

🧠 Aplikasi Tugas Cerdas (Smart To-Do List)

Aplikasi daftar tugas sederhana yang dibangun dengan teknologi modern. Selain fungsi dasar CRUD (Create, Read, Update, Delete), aplikasi ini diperkaya dengan kemampuan Kecerdasan Buatan (AI) menggunakan Gemini API untuk memberikan saran langkah-langkah detail dan fitur Text-to-Speech (TTS) untuk membacakan tugas Anda.

Dibangun sebagai Single Page Application (SPA) menggunakan satu file HTML tunggal, menjadikannya cepat, ringan, dan mudah diterapkan (deploy).

✨ Fitur Utama

Fitur

Deskripsi

Teknologi

CRUD Penuh

Tambah, Lihat, Edit, dan Hapus tugas dengan mudah.

HTML, JS, Firestore

Saran Ide Cerdas

Tombol ✨ Ide memanggil Gemini API untuk memecah tugas kompleks menjadi sub-tugas yang terperinci.

Gemini API (LLM & Grounding)

Ucapkan Tugas

Tombol 🔊 Ucapkan menggunakan Gemini TTS untuk membacakan tugas dengan suara yang ramah.

Gemini API (TTS)

Visualisasi Status

Donut chart yang menunjukkan persentase tugas Selesai vs. Belum Selesai secara real-time.

Chart.js

Penyimpanan Cloud

Semua data tugas disimpan secara real-time dan persisten di cloud.

Firebase Firestore

Desain Responsif

Tampilan bersih, profesional, dan berfungsi sempurna di desktop, tablet, dan ponsel.

Tailwind CSS

🛠️ Tumpukan Teknologi

Aplikasi ini adalah contoh sempurna dari solusi full-stack yang efisien dalam satu file.

Front-End & UI: HTML5, Vanilla JavaScript, Tailwind CSS (CDN)

Database: Firebase Firestore (Real-time NoSQL Database)

Visualisasi: Chart.js (untuk Donut Chart Status Tugas)

Kecerdasan Buatan: Gemini API (gemini-2.5-flash-preview-09-2025 dan TTS)

🚀 Cara Menjalankan

Karena ini adalah Single Page Application (SPA) dalam satu file, langkah menjalankannya sangat mudah:

Dapatkan Kode: Salin seluruh konten dari file index.html.

Siapkan API: Pastikan Anda memiliki lingkungan yang menyediakan konfigurasi Firebase dan kunci Gemini API yang diperlukan (seperti dalam platform Immersive Canvas ini).

Buka di Browser: Simpan konten tersebut sebagai index.html dan buka menggunakan browser modern apa pun.

Data akan secara otomatis dimuat dan disimpan menggunakan Firebase Firestore berdasarkan ID pengguna unik Anda.

🤝 Kontribusi

Aplikasi ini dapat dikembangkan lebih lanjut. Beberapa ide pengembangan:

Tambahkan fitur prioritas tugas (Tinggi, Sedang, Rendah).

Gunakan fitur "Google Search Grounding" Gemini untuk memberikan saran berdasarkan konteks waktu atau lokasi (misalnya, jika tugas adalah "Beli bahan makanan", disarankan resep populer).

Tambahkan filter untuk menampilkan tugas berdasarkan status atau tanggal pembuatan.

Implementasi autentikasi pengguna non-anonim (misalnya, login Google) untuk keamanan dan portabilitas data yang lebih baik.

Kami menyambut kontribusi dan saran dari komunitas!

Dibangun dengan 💙 oleh Gemini.
