# UNIQ SHOP CCTV – Toko Laptop, CCTV & Jaringan

[![Vercel Deployment](https://img.shields.io/badge/deployed%20on-Vercel-black?logo=vercel)](https://uniq-shop-cctv.vercel.app)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Website statis modern untuk **UNIQ CELL**, toko yang menyediakan laptop, CCTV, dan perangkat jaringan. Dibangun dengan Bootstrap 5, GSAP, dan fitur keranjang belanja berbasis localStorage. Pemesanan langsung terintegrasi dengan WhatsApp.

![Preview Website](https://images.unsplash.com/photo-1496181133206-80ce9b88a853?w=800&auto=format)

## 📋 Daftar Isi
- [Demo](#demo)
- [Fitur Unggulan](#fitur-unggulan)
- [Teknologi yang Digunakan](#teknologi-yang-digunakan)
- [Struktur Proyek](#struktur-proyek)
- [Cara Menjalankan di Lokal](#cara-menjalankan-di-lokal)
- [Deployment ke Vercel](#deployment-ke-vercel)
- [Kustomisasi](#kustomisasi)
- [Berkontribusi](#berkontribusi)
- [Lisensi](#lisensi)

## 🌐 Demo
Akses langsung website live: [https://uniq-shop-cctv.vercel.app](https://uniq-shop-cctv.vercel.app)  
*(Ganti dengan URL Vercel Anda setelah deploy)*

## ✨ Fitur Unggulan
- **Tampilan Responsif** – dioptimalkan untuk desktop, tablet, dan ponsel menggunakan Bootstrap 5.
- **Keranjang Belanja Pintar** – tambah/hapus produk, ubah jumlah, data tersimpan di localStorage.
- **Checkout via WhatsApp** – semua item di keranjang dikirim otomatis ke nomor admin.
- **Notifikasi Toast** – konfirmasi setiap kali produk ditambahkan ke keranjang.
- **Animasi GSAP** – efek fade-in dan scroll yang halus pada hero section dan kartu produk.
- **SEO Siap Pakai** – meta tags, Open Graph, Twitter Card, canonical URL, dan structured data (JSON-LD) untuk meningkatkan visibilitas di mesin pencari.
- **Kategori Produk** – Laptop, CCTV, dan Jaringan, masing-masing dengan ikon khas.

## 🛠 Teknologi yang Digunakan
- **HTML5** – struktur semantik
- **CSS3** – styling kustom
- **Bootstrap 5** – framework CSS untuk layout dan komponen
- **Bootstrap Icons** – ikon vektor gratis
- **JavaScript (ES6)** – logika keranjang dan interaksi
- **GSAP (GreenSock)** – animasi profesional
- **LocalStorage** – penyimpanan data keranjang di browser
- **Vercel** – hosting dan deployment otomatis
- **Git & GitHub** – version control

## 📁 Struktur Proyek
UNIQ-SHOP-CCTV/
├── public/
│ ├── index.html # Halaman utama (seluruh konten, CSS, dan JS inline)
│ └── favicon.ico # (opsional) ikon website
├── vercel.json # Konfigurasi untuk deployment Vercel
├── README.md # Dokumentasi proyek (file ini)
└── LICENSE # Lisensi MIT (opsional)

> **Catatan:** Karena proyek ini murni statis (single file HTML), semua kode CSS dan JavaScript sudah disatukan di dalam `index.html` untuk kemudahan deploy. Jika ingin memisahkan, Anda dapat membuat folder `css/` dan `js/` lalu memindahkan kode yang sesuai.

## 🚀 Cara Menjalankan di Lokal
1. **Clone repositori ini:**
   ```bash
   git clone https://github.com/uniqtesting7-wq/UNIQ-SHOP-CCTV.git
   cd UNIQ-SHOP-CCTV

   
