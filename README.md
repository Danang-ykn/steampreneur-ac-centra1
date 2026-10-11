# AC-CENTRA

**AC-CENTRA (Sistem Monitoring dan Kendali AC Terpusat Berbasis IoT untuk Efisiensi Pengelolaan Energi di Industri)** adalah prototipe website untuk membantu pengguna memantau dan menyimulasikan perubahan status ON/OFF unit AC, mencatat riwayat perubahan, serta melihat estimasi durasi penggunaan, konsumsi energi, dan biaya listrik.

Prototipe ini dikembangkan untuk memvalidasi alur penggunaan dan kebutuhan pengelolaan AC. Pengujian awal menggunakan konteks SMK Negeri 1 Rejotangan sebagai lingkungan validasi, sementara sasaran penerapannya tetap pada kebutuhan pengelolaan AC di lingkungan industri.

> **Catatan penting:** Versi tantangan ini merupakan simulasi website. Website belum terhubung ke ESP8266, sensor, jaringan IoT, atau perangkat AC fisik. Status dan perhitungan yang ditampilkan bukan hasil pembacaan perangkat nyata dan tidak boleh dianggap sebagai bukti penghematan energi aktual.
## Alur Inti

Jelaskan langkah yang dilakukan pengguna dari awal sampai akhir.

1.
2.
3.

## Cara Menjalankan (How to Run)

Tulis langkah selengkap mungkin. Juri akan meng-clone repositori ini ke komputer yang bersih dan mengikuti langkah di bawah persis seperti yang tertulis.

### Prasyarat

Sebutkan semua yang harus terpasang beserta versinya. Contoh:
- Node.js versi 20 atau lebih baru
- Browser Chrome atau Firefox

### Langkah

1. Clone repositori:
   ```
   git clone https://github.com/Danang-ykn/steampreneur-ac-centra.git
   ```
2. Masuk ke folder proyek:
   ```
   cd steampreneur-nama-tim
   ```
3. Install dependensi (hapus langkah ini jika tidak ada):
   ```
   npm install
   ```
4. Jalankan website:
   ```
   npm run dev
   ```
5. Buka alamat berikut di browser: http://localhost:5173

### Akun atau data contoh


Versi awal direncanakan menggunakan data contoh dan tidak memerlukan akun pengguna sungguhan. Jika autentikasi atau akun demo ditambahkan kemudian, dokumentasikan hanya kredensial demo yang aman dan memang tersedia di aplikasi. Jangan masukkan kata sandi pribadi atau data sungguhan.

### Jika terjadi masalah

Tuliskan masalah yang mungkin muncul dan cara mengatasinya (misalnya port sudah dipakai).

## Tangkapan Layar Alur Inti

Minimal satu tangkapan layar untuk setiap langkah alur inti, termasuk hasil change request. Simpan gambar di `docs/bukti/`.

1. Langkah 1: ![Langkah 1](docs/bukti/langkah-1.png)
2. Langkah 2: ![Langkah 2](docs/bukti/langkah-2.png)

## Cara Menjalankan Pengujian

```
perintah untuk menjalankan test
```

Hasil yang diharapkan: semua test lulus.

## Fitur

-

## Batasan yang Diketahui

Apa yang belum bisa dilakukan atau masih kurang?
-

## Struktur Folder

| File / folder | Isi |
|---|---|
| `docs/` | Dokumen proses kerja (spesifikasi, rencana, log prompt, kasus uji, dan lainnya) |
| `src/` | Kode website |
| `tes/` | Unit test |
| `bughunt-kasir/` | Hasil Bug Hunt |

## Link Demo (opsional)

Jika website di-hosting (misalnya GitHub Pages), tuliskan link-nya di sini.

## Sumber dan Lisensi

Cantumkan library, template, gambar, ikon, atau font yang dipakai beserta lisensinya.

| Nama | Sumber (link) | Lisensi |
|---|---|---|
| | | |

## Tim

Jangan cantumkan nomor HP, alamat, atau email.

| Nama | Peran |
|---|---|
| Danang | Logika aplikasi, simulasi status, riwayat, perhitungan, dan penyimpanan |
| Fahril | Antarmuka, daftar/formulir, dashboard/rekap, dan responsivitas |
| Nadira | Pengujian, dokumentasi, kasus uji, dan bukti pengujian |
| Semua anggota | Integrasi, review, dan memahami kode yang digunakan |
