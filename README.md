# Menghapus Cache project:init Laravel

## 1. Masuk ke Direktori Laravel
Pastikan Anda berada di direktori root proyek Laravel Anda. Jika menggunakan docker maka pastikan docker Anda telah berjalan. Kemudian gunakan perintah berikut untuk berpindah direktori:
```bash
cd /path /to /your /Laravel /project
```

## 2. Hapus Cache Konfigurasi
Laravel menyimpan cache konfigurasi di dalam file untuk mempercepat performa. Gunakan perintah berikut untuk membersihkannya:
```bash
php artisan config:clear
```

## 3. Hapus Cache Route
Untuk membersihkan cache route, gunakan perintah:
```bash
php artisan route:clear
```

## 4. Hapus Cache View
Laravel juga mencache file view (blade). Anda bisa membersihkannya dengan:
```bash
php artisan view:clear
```

## 5. Hapus Cache Aplikasi
Jika ada data cache aplikasi lainnya yang ingin dihapus, gunakan:
```bash
php artisan cache:clear
```
