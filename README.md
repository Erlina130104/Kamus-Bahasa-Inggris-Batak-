 Kamus Bahasa Inggris ↔ Batak Sederhana (C Language)

Program ini adalah aplikasi terminal berbasis bahasa C yang berfungsi sebagai kamus dua arah antara Bahasa Inggris dan Bahasa Batak, sekaligus memungkinkan pengguna untuk menambahkan kosakata baru ke dalam file dictionary.txt.

Fitur

- Terjemahan Bahasa Inggris ke Batak
- Terjemahan Bahasa Batak ke Inggris
- Menambahkan kata baru langsung ke file teks
- Penyimpanan lokal dalam file `dictionary.txt`

Cara Kerja

- Data disimpan dalam file dictionary.txt dengan format:
  batak_word|english_word
- Saat memilih menu 1 atau 2, program membaca file baris per baris dan mencocokkan kata yang dimasukkan
- Menu 3 memungkinkan pengguna menambahkan kosakata baru langsung ke file tersebut

Contoh Tampilan
OPTIONS 
1. Bahasa Inggris - Batak
2. Batak - Bahasa Inggris
3. Add New Word
Enter your option:

Struktur File

- main.c → Program utama
- dictionary.txt → File teks penyimpanan kata
- README.md → Dokumentasi proyek

Cara Menjalankan

1. Kompilasi program:
   gcc main.c -o kamus
2. Jalankan program:
   ./kamus

Catatan

- Program menggunakan pemisah | antara kata Batak dan Inggris
- Format harus konsisten: batak|english
- File dictionary.txt akan otomatis dibuat jika belum ada

