# 🧠 Smart To-Do List (Aplikasi Tugas Cerdas)

> Aplikasi daftar tugas sederhana yang dibangun dengan teknologi modern. Selain fungsi dasar CRUD, aplikasi ini diperkaya dengan kemampuan Kecerdasan Buatan (AI) menggunakan Google Gemini API untuk memberikan saran langkah-langkah detail dan fitur Text-to-Speech (TTS) untuk membacakan tugas Anda.

<p align="center">
  <a href="https://agunggema-debug.github.io/smart-todo-list/">
    <img src="https://img.shields.io/badge/LIVE_DEMO-Lihat_Aplikasi-0077B6?style=for-the-badge&logo=vercel" alt="Live Demo Vercel" />
  </a>
  <img src="https://img.shields.io/badge/STATUS-Active-brightgreen?style=for-the-badge" alt="Status Active" />
</p>

## ✨ Fitur Utama

Aplikasi ini mendefinisikan ulang *to-do list* tradisional dengan integrasi AI dan penyimpanan *cloud* yang efisien.

| Fitur | Deskripsi | Teknologi |
| :--- | :--- | :--- |
| **CRUD Penuh** | Tambah, Lihat, Edit, dan Hapus tugas secara *real-time*. | HTML, JS, Firestore |
| **Saran Ide Cerdas** | Tombol ✨ memanggil **Gemini API** untuk memecah tugas kompleks (*misal: "Membuat website"*) menjadi sub-tugas yang terperinci. | Gemini API (LLM) |
| **Ucapkan Tugas** | Tombol 🔊 menggunakan **Gemini TTS** untuk membacakan tugas dengan suara yang ramah. | Gemini API (TTS) |
| **Visualisasi Status** | **Donut Chart** menunjukkan persentase tugas *Selesai* vs. *Belum Selesai* secara *real-time*. | Chart.js |
| **Penyimpanan Cloud** | Semua data tugas disimpan secara persisten di *cloud*, terikat pada ID pengguna anonim yang unik. | Firebase Firestore |
| **Desain Responsif** | Tampilan bersih, profesional, dan berfungsi sempurna di berbagai ukuran layar. | Tailwind CSS |

---

## 🚀 Tumpukan Teknologi (The Stack)

Aplikasi ini adalah contoh solusi *full-stack* yang efisien dalam satu file tunggal.

| Kategori | Teknologi | Tujuan |
| :--- | :--- | :--- |
| **Frontend & UI** | `HTML5`, `Vanilla JavaScript`, `Tailwind CSS (CDN)` | Antarmuka pengguna yang cepat, ringan, dan dinamis. |
| **Database** | `Firebase Firestore` | Database NoSQL *real-time* untuk persistensi data. |
| **Kecerdasan Buatan** | `Gemini API (gemini-2.5-flash-preview-09-2025)` | Pemrosesan bahasa alami dan Text-to-Speech. |
| **Visualisasi** | `Chart.js` | Menghasilkan Donut Chart status tugas. |

## 🖼️ Tampilan Aplikasi




