# Nitip Catip
### Sistem Informasi Jasa Titip Berbasis Web

Nitip Catip merupakan aplikasi berbasis web yang dikembangkan untuk mendukung proses pemesanan dan pengelolaan layanan jasa titip. Sistem ini menyediakan fasilitas bagi pelanggan untuk melakukan pemesanan produk, serta bagi admin untuk mengelola pesanan dan informasi pengiriman.

## Identitas Kelompok

**Nama Kelompok:** [Nama Kelompok]

| No. | Nama Anggota | NPM |
|:---:|---|:---:|
| 1 | M Fadlullah Assalafy Y | 202343501936 |
| 2 | Fara Firginia | 202343501748 |
| 3 | Unike Oktriani | 202343501735 |

## Informasi Proyek

| Keterangan | Detail |
|---|---|
| Nama Proyek | Nitip Catip |
| Jenis Aplikasi | Sistem Informasi Berbasis Web |
| Kategori | Jasa Titip |
| Website | https://nitip-catip.vercel.app |

## Fitur Sistem

### Customer
- Melihat halaman utama dan katalog produk.
- Melakukan pemesanan produk.
- Mengisi informasi pelanggan dan alamat pengiriman.
- Mengunggah lampiran pemesanan.
- Melakukan pembayaran melalui QRIS, transfer, atau Shopee.
- Melihat detail pesanan.
- Menghubungi admin.

### Admin
- Melakukan login.
- Melihat dashboard.
- Melihat dan mengelola data pesanan.
- Melakukan pencarian dan filter pesanan.
- Memperbarui informasi pengiriman.
- Mengatur biaya jasa titip berdasarkan ukuran produk.

## Teknologi

| Teknologi | Penggunaan |
|---|---|
| Next.js | Framework aplikasi web |
| React.js | Library antarmuka pengguna |
| TypeScript | Bahasa pemrograman |
| Tailwind CSS | Pengaturan tampilan |
| Zod | Validasi data |
| Supabase | Pengelolaan database |
| Google Apps Script | Integrasi pengiriman data pesanan |
| Vercel | Deployment aplikasi |

## Struktur Repository

```text
Nitip-Catip/
├── DIAGRAM/
├── TESTING/
├── UI-UX/
├── PROJECT DESC.docx
├── README.md
├── SOURCE-CODE.zip
└── SRS.docx
```

## Menjalankan Aplikasi

Pastikan Node.js telah terpasang pada perangkat.

**1. Clone repository**

```bash
git clone <repository-url>
```

**2. Masuk ke direktori project**

```bash
cd Nitip-Catip
```

**3. Install dependencies**

```bash
npm install
```

**4. Konfigurasi environment**

Siapkan file `.env.local` sesuai kebutuhan konfigurasi aplikasi dan layanan yang digunakan.

**5. Jalankan aplikasi**

```bash
npm run dev
```

Aplikasi dapat diakses melalui:

```text
http://localhost:3000
```

## Dokumentasi dan Pengujian

Dokumentasi proyek tersedia dalam direktori berikut:

- `DIAGRAM/` — Diagram perancangan sistem semuanya ada disini.
- `TESTING/` — Dokumentasi pengujian Black Box dan White Box.
- `UI-UX/` — Dokumentasi desain antarmuka.

Dokumen pendukung lainnya:
- Project Description
- Software Requirements Specification (SRS)

---

**Nitip Catip — Sistem Informasi Jasa Titip**