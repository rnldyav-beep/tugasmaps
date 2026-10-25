---
name: tap-in-rev-web-builder
description: Membangun dan mengembangkan website landing page "tap.in rev" (solusi Google Review Map berbasis QR Code & NFC) dengan tema Dark Luxury (hitam pekat & kuning emas menyala), efek anti-gravity (elemen melayang), Bento Grid, dan desain responsif Mobile-First. Gunakan saat pengguna meminta membuat, mengedit, atau mengoptimalkan kode website tap.in rev di Antigravity atau editor kode.
---
# Tap In Rev Web Builder

Skill khusus untuk membangun halaman website **tap.in rev** (`TAP • SCAN • REVIEW`) yang berfokus pada layanan peningkatan ulasan Google Maps menggunakan QR Code dan NFC, dilengkapi estetika *Dark Luxury*, efek visual *Anti-Gravity* (elemen melayang), dan tata letak *Mobile-First Responsive*.

## When to Use

- Pengguna meminta pembuatan atau pengembangan kode website untuk projek **tap.in rev**.
- Pengguna ingin menerapkan referensi desain bergaya *dark agency/startup* (ambient glow di bagian atas, floating pill navbar, bento cards, dan garis bawah coretan SVG) dengan palet warna Hitam & Kuning Emas.
- Pengguna membutuhkan implementasi halaman *Single-File HTML* (HTML5 + Tailwind CSS + Vanilla JS) yang rapi di layar HP maupun laptop.

## Brand & Visual Identity

1. **Nama Brand & Logo**:
   - Teks Logo: **tap.** (warna kuning `#FACC15`) disambung rapat dengan **in rev** (warna putih `#FFFFFF`).
   - Sub-tagline: `TAP • SCAN • REVIEW` (huruf kapital semua, *italic*, *letter-spacing* lebar `0.25em`, warna kuning `#FACC15`).

2. **Palet Warna (Dark Luxury Theme)**:
   - **Background Utama**: Hitam Pekat (`#050505` hingga `#0A0A0A`) — dominan hitam agar terlihat mewah.
   - **Surface / Bento Card**: Hitam Matte & Glassmorphism (`#111111` / `rgba(20, 20, 20, 0.75)`) dengan *border* tipis (`rgba(255, 255, 255, 0.08)` dan menyala kuning `rgba(250, 204, 21, 0.4)` saat *hover*).
   - **Aksen Utama**: Kuning Emas Menyala (`#FACC15` / `#F5E027`) khusus untuk kata kunci judul, *badge*, ikon, garis aksen, dan tombol CTA.
   - **Ambient Top Glow**: Ganti cahaya biru pada referensi menjadi *radial gradient* kuning keemasan yang lembut di bagian paling atas halaman (`radial-gradient(circle at 50% 0%, rgba(250, 204, 21, 0.18), transparent 65%)`).

3. **Tipografi Mewah & Bold**:
   - Gunakan Google Fonts **Syne** (700/800) atau **Plus Jakarta Sans** (700/800) untuk *Heading* agar berkarakter tegas, modern, dan tidak polos.
   - Gunakan **Plus Jakarta Sans** atau **Inter** (400/500/600) untuk teks isi (*body text*) agar tetap nyaman dibaca di layar HP.

4. **Efek Anti-Gravity (Floating UI Physics)**:
   - Terapkan animasi CSS `@keyframes float` yang halus (naik-turun perlahan 6-10px selama 4-6 detik) pada kartu mockup NFC/QR, *badge* keuntungan, dan ikon ilustrasi di dalam *Bento Card*.
   - Gunakan *Floating Pill Navbar* dengan efek `backdrop-filter: blur(16px)` yang melayang di bagian atas layar.

## Content & Section Architecture

Susun halaman dengan urutan bagian berikut:

1. **Floating Header / Navbar**:
   - Kiri: Logo **tap.in rev**.
   - Tengah (Desktop): Pill navigasi berisi *Keunggulan*, *Kategori Usaha*, *Cara Kerja*, *Harga & Reseller*.
   - Kanan: Tombol CTA putih/kuning kontras *"Hubungi Kami ↗"* dan tombol Hamburger untuk tampilan HP.

2. **Hero Section**:
   - Badge atas: `🚀 GOOGLE REVIEW MAP — SCAN • TAP • REVIEW • GROW`.
   - Headline besar & bold dengan kata kunci berwarna kuning dan aksen **garis bawah coretan (*hand-drawn SVG underline*) warna kuning**.
   - Subheadline: *"Solusi Praktis untuk Membantu Bisnis Berkembang! Permudah pelanggan memberikan ulasan di Google Maps menggunakan teknologi QR Code dan NFC."*
   - Dual CTA: Tombol utama *"Pesan Sekarang ↗"* dan tombol sekunder *"Gabung Reseller"*.

3. **Target Bisnis (Trusted Category Grid)**:
   - Mengadaptasi deretan kartu logo pada gambar referensi menjadi kartu kategori usaha bergaya gelap & elegan:
   - Daftar usaha: **Coffee Shop, Restoran, Toko Ritel, Salon, Barbershop, Bengkel, Hotel, dan UMKM**.

4. **Cara Kerja & Keunggulan (Interactive Tabs + 2 Large Bento Cards)**:
   - Navigasi tab bergaris bawah kuning sesuai referensi desain.
   - 4 Langkah Cara Kerja:
     1. **Scan QR Code atau Tap NFC** pada perangkat pelanggan.
     2. **Diarahkan Otomatis** langsung ke halaman ulasan Google Maps bisnis.
     3. **Ulasan Sukarela & Praktis** oleh pelanggan dalam hitungan detik.
     4. **Reputasi Meningkat**, bisnis lebih mudah membangun kepercayaan digital.
   - Dua *Bento Card* besar berdampingan (satu dengan visual *Target/NFC Radar*, satu dengan *Glowing Bulb/Star Glow* warna kuning).

5. **Pricing & Paket Reseller Section**:
   - **Kartu 1: Harga Aktivasi Reguler (`Rp50.000 / unit`)**
     - Aktivasi satu kali.
     - Aktif selamanya sesuai ketentuan produk.
     - Praktis menggunakan QR Code dan NFC.
   - **Kartu 2 (Highlight Glow Kuning): Paket Reseller (`Rp150.000 / 5 PCS`)**
     - Harga modal hanya **Rp30.000 / unit**.
     - Harga jual rekomendasi **Rp50.000 / unit**.
     - Potensi keuntungan kotor **Rp100.000** jika 5 unit terjual.
     - Mendapatkan panduan penjualan dan cara aktivasi.
     - Bisa dipasarkan ke berbagai jenis usaha.
     - Sangat cocok untuk mahasiswa, *freelancer*, dan pemula yang ingin memulai bisnis.

6. **Footer & Direct WhatsApp CTA**:
   - Ajakan penutup: *"Tertarik membeli atau menjadi reseller? Hubungi kami untuk informasi lebih lanjut."*
   - Identitas lengkap **tap.in rev** (`TAP • SCAN • REVIEW`).

## Mobile-First Responsive Rules

Pastikan tampilan di layar HP (320px - 768px) sama rapinya dengan layar laptop:

- Gunakan `clamp()` pada ukuran huruf judul utama (contoh: `font-size: clamp(2rem, 5vw, 4.25rem)`) agar teks tidak terpotong di layar sempit.
- Ubah semua tata letak multi-kolom (*Bento Cards* 2 kolom dan *Pricing Cards* 2 kolom) menjadi 1 kolom vertikal (`grid-template-columns: 1fr`) pada layar di bawah `768px`.
- Untuk deretan kategori usaha, gunakan `grid-template-columns: repeat(2, 1fr)` di layar HP agar tersusun rapi 2 kotak per baris.
- Sediakan menu navigasi mobile (*slide-down* atau *overlay drawer*) yang mudah disentuh jari (ukuran target sentuh minimal `44px`).
- Cegah kebocoran geser samping dengan `overflow-x: hidden` pada `body`.