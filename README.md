# G1A023090_VBA-Sistem-Kerja-Praktik
## SISTEM VBA BPMP
## Deskripsi
Sistem VBA BPMP merupakan aplikasi berbasis Microsoft Excel dan VBA (Visual Basic for Applications) yang digunakan untuk membantu pengelolaan data surat tugas, kegiatan pegawai, serta administrasi perjalanan dinas di lingkungan BPMP.

## Aplikasi ini dirancang untuk mempermudah proses:
-Input data pegawai
-Pencatatan surat masuk dan surat tugas
-Pengelolaan kegiatan dan perjalanan dinas
-Pencarian dan penyaringan data
-Pembuatan laporan administrasi

## Persyaratan_Sistem
-Microsoft Excel 2016 atau versi yang lebih baru
-Macro VBA harus diaktifkan
-Sistem operasi Windows 10/11

## Cara Menjalankan 
-Unduh atau salin file  ke komputer.
-Simpan file pada folder yang mudah diakses.
-Buka file menggunakan Microsoft Excel.
-Jika muncul peringatan keamanan, aktifkan Macro VBA sesuai petunjuk di bawah.
-Klik tombol FORM INPUT atau menu yang tersedia untuk mulai menggunakan aplikasi.

## Mengatasi Macro VBA yang Diblokir
Jika saat membuka file muncul pesan:

  *Microsoft has blocked macros from running because the source of this file is untrusted*

lakukan langkah berikut:
  1. Tutup file Excel.
  2. Klik kanan file aplikasi.
  3. Pilih Properties.
  4. Pada tab General (Umum), cari bagian Security di bagian bawah.
  5. Centang Unblock (Buka Blokir).
  6. Klik Apply lalu OK.
  7. Buka kembali file Excel.
  8. Klik Enable Content jika diminta.

## Struktur Menu
Database
  Menampilkan seluruh data surat tugas dan kegiatan yang telah tersimpan.
Form Input
  -Digunakan untuk:
  -Menambah data baru
  -Mengubah data
  -Menghapus data
  -Menyimpan data ke database
Filter
  Digunakan untuk melakukan pencarian dan penyaringan data berdasarkan kriteria tertentu.
ComboBox
  Berisi data referensi yang digunakan oleh form aplikasi.
Penyimpanan Data
  Data disimpan langsung pada workbook Excel. Disarankan untuk melakukan backup file secara berkala guna menghindari kehilangan data.
Catatan Penting
  -Jangan mengubah nama worksheet tanpa petunjuk pengembang.
  -Jangan menghapus kolom atau baris yang digunakan sistem.
  -Pastikan Macro VBA selalu aktif saat menggunakan aplikasi.
  -Lakukan backup file sebelum melakukan perubahan besar pada data.
