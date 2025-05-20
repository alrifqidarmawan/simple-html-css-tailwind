      
# Enigflix - Halaman Depan Sederhana

Selamat datang di Enigflix! Ini adalah proyek antarmuka pengguna (UI) sederhana yang menampilkan halaman depan dengan gaya mirip Netflix, lengkap dengan beberapa kartu penawaran paket. Proyek ini dibuat murni dengan HTML dan CSS, menggunakan Tailwind CSS untuk styling cepat dan beberapa CSS kustom untuk efek visual tambahan.

## 🚀 Pratinjau
![Pratinjau Enigflix](https://github.com/alrifqidarmawan/simple-html-css-tailwind/blob/main/simple-page.png)

## ✨ Fitur Utama

*   **Header Navigasi:** Header tetap (sticky) dengan logo "Enigflix", tautan navigasi (Home, TV Shows, New & Popular, My List), ikon pencarian, dan ikon notifikasi.
*   **Tampilan Responsif (Dasar):** Tata letak disesuaikan untuk berbagai ukuran layar menggunakan kelas utilitas Tailwind CSS.
*   **Kartu Penawaran Paket:**
    *   Tiga pilihan paket: Basic, Pro, dan Elite.
    *   Efek hover interaktif:
        *   Ketika satu kartu di-hover, kartu lain menjadi blur dan sedikit transparan.
        *   Kartu yang di-hover akan sedikit membesar (scale).
    *   Tag "Popular" dengan animasi gradien pada paket Pro.
*   **Styling Modern:** Menggunakan Tailwind CSS untuk utilitas styling dan CSS kustom untuk animasi dan efek spesifik.
*   **Font Kustom:** Menggunakan `netflix.font.css` untuk memberikan tampilan khas pada logo.

## 🛠️ Teknologi yang Digunakan

*   **HTML5:** Struktur dasar halaman web.
*   **CSS3:**
    *   **Tailwind CSS (v4 via CDN Browser JIT):** Framework CSS berbasis utilitas untuk pengembangan UI yang cepat.
    *   **CSS Kustom:** Digunakan untuk animasi (`PopularAnimation`), efek blur pada hover, dan styling spesifik lainnya yang tidak mudah dicapai hanya dengan Tailwind.
*   **`netflix.font.css`:** File CSS eksternal untuk font kustom (diasumsikan untuk logo "Enigflix").

## 📁 Struktur Proyek

    

IGNORE_WHEN_COPYING_START
Use code with caution. Markdown
IGNORE_WHEN_COPYING_END

.
├── index.html # File HTML utama yang berisi semua markup dan sebagian CSS
└── netflix.font.css # File CSS untuk font kustom (Anda perlu memastikan file ini ada)

      
## 🚦 Cara Menjalankan

Proyek ini sangat sederhana dan tidak memerlukan proses build atau instalasi dependensi yang rumit.

1.  **Pastikan Anda memiliki kedua file:**
    *   `index.html`
    *   `netflix.font.css` (Jika font ini penting untuk tampilan logo, pastikan file ini berada di direktori yang sama dengan `index.html` atau path ke file ini benar di dalam `index.html`).
2.  **Buka di Peramban:**
    Cukup buka file `index.html` langsung di peramban web pilihan Anda (misalnya, Google Chrome, Firefox, Safari, Edge).

Karena proyek ini menggunakan Tailwind CSS via CDN Browser JIT (`<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>`), Anda memerlukan koneksi internet saat pertama kali membuka halaman agar Tailwind dapat memproses kelas-kelas utilitasnya.

## 📝 Catatan Tambahan

*   **Fungsionalitas Tautan & Tombol:** Sebagian besar tautan (`<a>`) dan tombol saat ini tidak memiliki fungsionalitas JavaScript (misalnya, navigasi ke halaman lain, membuka menu mobile, pencarian). Ini murni proyek UI.
*   **Ikon SVG:** Ikon pencarian dan notifikasi menggunakan SVG inline.
*   **Animasi:**
    *   Teks "Popular" memiliki animasi gradien latar belakang.
    *   Beberapa elemen memiliki animasi `pulse` atau `bounce` sederhana dari Tailwind.

## 🤝 Kontribusi

Saat ini, proyek ini adalah demonstrasi sederhana. Namun, jika Anda memiliki ide untuk perbaikan atau fitur tambahan, jangan ragu untuk:

1.  Fork repositori ini.
2.  Buat branch fitur baru (`git checkout -b fitur/NamaFiturKeren`).
3.  Commit perubahan Anda (`git commit -am 'Menambahkan fitur keren'`).
4.  Push ke branch (`git push origin fitur/NamaFiturKeren`).
5.  Buat Pull Request baru.

---
