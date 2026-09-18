# Indicars
Aplikasi berbasis AI untuk mendiagnosis kode error (OBD-II), mengetahui indikasi masalah, dan panduan perbaikan secara akurat dan cepat.

## Table Gambar
| Setup | Dashboard | Tambah Data |
| :---: | :---: | :---: |
| ![Gambar 1](screenshot/ss_001.png) | ![Gambar 2](screenshot/ss_002.png) | ![Gambar 3](screenshot/ss_003.png) |
| Tampilan Wizard/Setelan | Tampilan dashboard dan data pada kartu | Tampilan menambahkan data error baru |

| Koneksi OBD II | Isi Kartu | Isi Kartu Ke Bawah |
| :---: | :---: | :---: |
| ![Gambar 4](screenshot/ss_004.png) | ![Gambar 5](screenshot/ss_005.png) | ![Gambar 6](screenshot/ss_006.png) |
| Langsung buat indikasi dengan Scanner OBD-II (ELM327) | Tampilan isi kartu | Tampilan isi kartu kebawah |

## Setup & Integrasi Gemini API Key
Saat ini memakai model gemini-3.5-flash-lite
1. Masukkan nama bengkel anda.
2. Pilih logo/gambar bengkel anda.
3. Buat api key > [disini](https://aistudio.google.com/api-keys) lalu tempel api key anda.
4. Simpan

## Fitur
> Tema Terang/Gelap

> Minimalis UI/UX Responsive

> Pencarian data yang tersimpan

> Membuat data indikasi Error

> Mengedit Nama Pemilik Kendaraan

> Menghapus data pada daftar kartu    

> Menganalisa kesalahan berdasarkan kode dari OBD II (by generate AI)

> Mencatat dan menampilkan indikasi masalah

> Memberitahukan cara langkah perbaikan dengan tugas ceklis pada daftar jika sudah dilakukan

> Print langsung

### Menambahkan Data Error
Klik tombol {+ Tambah Data Error}
- Masukkan Kode Error (DTC)
- Pilih Merek (Buatan Jepang di Indonesia)
- Masukkan Nama Model / Versi
- Masukkan Nama Pemilik
- Sesuaikan tanggal
- Klik Tombol Indikasikan

### Pairing OBD II/ELM327 (BLE 4.0+)
- Nyalakan Kontak Mobil: Putar kunci kontak mobil ke posisi ON (mesin tidak harus dinyalakan) agar dongle OBD-II aktif dan mendapat daya.
- Aktifkan Bluetooth & Izin: Pastikan Bluetooth di perangkat (HP/Laptop) Anda aktif, lalu berikan izin akses perangkat di sekitar (Nearby Devices) saat aplikasi meminta.
- Pilih & Hubungkan: Di dalam aplikasi, pilih mode Bluetooth 4.0+ (BLE), klik Mulai Scan, lalu pilih perangkat OBD-II Anda dari daftar perangkat yang muncul.
- Analisis AI: Tunggu hingga proses pembacaan sensor selesai, lalu gunakan data error (DTC) atau kondisi kendaraan untuk langsung di-generate dengan Diagnosis AI.
- Reset ECU (Opsional): Lakukan penghapusan error code atau reset ECU jika diperlukan (fitur ini bergantung pada dukungan spesifik dari alat OBD-II Anda).

### Pairing OBD II/ELM327 (Wi-Fi)
- Nyalakan kontak mobil ke posisi ON (pastikan dongle Wi-Fi OBD tertancap di port OBD-II dan lampu indikator menyala).
- Buka menu Pengaturan Wi-Fi di perangkat (HP/Laptop) Anda.
- Cari dan hubungkan ke jaringan Wi-Fi yang dipancarkan oleh dongle (biasanya bernama OBDII, WIFI_OBD, atau sejenisnya. Masukkan kata sandi default jika diminta, seperti 12345678 atau 0000).
- Kembali ke aplikasi, pilih mode Wi-Fi OBD, lalu lakukan scan untuk membaca data kendaraan (bisa langsung di-generate dengan AI).
- Reset ECU error (tergantung dukungan dari fitur alat OBD II/ELM327 yang Anda gunakan).

### Pasang Aplikasi Pada Perangkat (Desktop/Mobile)
1. Desktop > Khusus peramban chrome kamu bisa klik ikon komputer di sebelah ikon borkmark (bintang) atau klik titik 3/lainnya pilih > transimisikan, simpan, dan bagikan > install INDICARS.
2. Mobile > Klik titik 3 pada peramban chrome gulir dan pilih install dan buat pintasan.

Tautan resmi > https://spanelweb.github.io/indicars

### Catatan
``` txt
Semua data disimpan secara lokal! Kami tidak menyimpan data secara online.
Lakukan penyimpanan secara mandiri dengan mengexport data yang sudah anda buat.
import .indicars anda untuk pemulihan data.
Segala resiko di tanggung sendiri!
Kami hanya mengembangkan web aplikasi dengan tujuan membantu/memudahkan masyarakat.
```



Hormat Saya,

~ Suryo DwiJayanto
