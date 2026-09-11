# CLAUDE.md — Toko Mebel Pak Sugiono (Apple-Style Clean Landing Page)

## 📌 Deskripsi Proyek
Landing page e-commerce mebel **Toko Mebel Pak Sugiono** asal Tahunan, Jepara. 
Pendekatan desain: **Apple-Grade Aesthetic** — ultra-clean, tipografi kuat dan tegas, minim teks bertele-tele, rasio whitespace luas, kontras tinggi (Dark Theme `#000000` / `#161617`), dan zero clutter.

Semua fitur yang memperberat atau mendistraksi (kalkulator rumit, tabel log pengiriman panjang, review bintang 5 fiktif, animasi berlebihan) telah dieliminasi.

---

## 🛠️ Arsitektur & Prinsip Desain
- **Struktur Berkas:** Single-file HTML5 murni + CSS terisolasi presisi (tanpa dependency luar selain Google Font). Ukuran total < 21 KB.
- **Tipografi:** `Plus Jakarta Sans` dengan rentang ukuran masif (Headline 40px - 64px, Body 13px - 17px).
- **Struktur Informasi Wajib (Customer-Centric):**
  1. **Hero:** *"Jati Solid. Tanpa Kompromi."* + CTA langsung ke WhatsApp.
  2. **Bento Spec Highlights:**
     - `≤12%`: Kadar air oven Kiln Dry, aman untuk ruang AC.
     - `100%`: Kayu jati solid utuh (bukan MDF serbuk / triplek).
     - `Bebas`: Kustomisasi ukuran sesuai denah ruangan.
  3. **Showcase 4 Produk Unggulan:** Foto bersih, spesifikasi 2 baris, harga transparan, tombol WhatsApp prefilled.
  4. **Bespoke Banner:** Solusi custom order bagi konsumen yang membawa foto Pinterest / sketsa arsitek.
  5. **3 Langkah Pemesanan:** Spek -> DP 50% & Video Progres -> Pelunasan Saat Muat Truk.
  6. **Mobile Sticky Bar:** Navigasi 1-ketuk ke WhatsApp di layar ponsel.

---

## 💻 Menjalankan Dev Server
```bash
python -m http.server 8080
```
Buka di browser: `http://localhost:8080`.

---

## 📋 Instruksi Mutlak Bagi Claude Code CLI
1. **Pertahankan Filosofi Apple:**
   - Jangan menambahkan teks panjang berparagraf-paragraf. Gunakan headline pendek, tegas, dan berbobot.
   - Jangan menambahkan form input rumit atau kalkulator. Corong konversi utama adalah interaksi konsultatif langsung via WhatsApp.
   - Pertahankan rounded pill buttons (`border-radius: 980px`) dan kartu bento (`border-radius: 20px - 24px`).
2. **Kustomisasi Aset Gambar:**
   - Gambar saat ini menggunakan link Unsplash dengan tema kayu jati minimalis.
   - Jika mengganti dengan foto riil bengkel Pak Sugiono, gunakan rasio landscape terstandar dan simpan di folder `assets/` dalam format `.webp`.
