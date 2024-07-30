# Laravel Terjemahan Indonesia

Repository ini berisi file terjemahan bahasa Indonesia untuk Laravel, termasuk terjemahan untuk pesan validasi, otentikasi, reset password, dan lainnya. Tujuan repository ini adalah untuk menyediakan terjemahan yang sesuai dan mudah digunakan untuk aplikasi Laravel dalam bahasa Indonesia.

## Cara Penggunaan

Untuk menggunakan file terjemahan ini dalam proyek Laravel Anda, ikuti langkah-langkah berikut:

1. **Install Repository**  
   Clone repository ini atau unduh sebagai file ZIP dan ekstrak ke komputer Anda.

   ```bash
   git clone https://github.com/akaruidev/laravel-terjemahan-indonesia.git
   ```

2. **Pindahkan File Terjemahan**  
   Salin folder `id` dari repository ini ke direktori `lang/id` di proyek Laravel Anda.

3. **Publish File Terjemahan**  
   Untuk Laravel 10 ke atas, Anda harus mempublikasikan file terjemahan menggunakan perintah artisan berikut:

   ```bash
   php artisan lang:publish
   ```

4. **Pengaturan Locale**  
   Pastikan Anda telah mengatur locale aplikasi Laravel Anda ke bahasa Indonesia. Tambahkan atau perbarui pengaturan berikut di file `.env`:

   ```env
   APP_LOCALE=id
   ```

## Kontribusi

Jika Anda ingin berkontribusi pada terjemahan atau memperbaiki masalah, silakan buat pull request. Kami sangat menghargai kontribusi Anda!
