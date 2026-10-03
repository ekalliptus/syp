# SYP (Share Your Problem)

Aplikasi web konsultasi keluhan yang dibuat sebagai tugas akhir semester 3 mata kuliah Web Programming II, menggunakan framework CodeIgniter 3.

## Fitur

- Autentikasi untuk client, psikolog, dan admin.
- Client dapat mengirim keluhan.
- Psikolog melihat dan menanggapi keluhan client.
- Admin mengelola data keluhan, psikolog, dan testimoni.

## Tech stack

- PHP, CodeIgniter 3
- MySQL (skema awal di `database/syp.sql`)

## Menjalankan

1. Import `database/syp.sql` ke MySQL.
2. Sesuaikan koneksi database di `application/config/database.php`.
3. Sajikan lewat server PHP (XAMPP/Laragon) dan buka `index.php`.
