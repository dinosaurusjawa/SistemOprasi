
# Panduan Installasi Apache2 dan Konfigurasi Dasar

### Langkah 1: Install Apache2
Untuk menginstall Apache2, gunakan perintah berikut:
```bash
apt install apache2
```

### Langkah 2: Cek IP Address
Setelah instalasi selesai, cek IP address dengan menggunakan perintah:
```bash
ip addr
```
Cari IP yang terdaftar di interface `eth0`, lalu salin dan paste ke browser kalian. Jika berhasil, kalian akan melihat halaman default Apache dengan pesan **"Apache2 Ubuntu Default Page"** atau **"It Works!"**.

### Langkah 3: Mengedit Halaman Default Apache
Jika kalian ingin mengubah konten halaman default, ikuti langkah-langkah berikut:

1. Masuk ke direktori tempat file web berada:
   ```bash
   cd /var/www/html
   ```

2. Lihat isi direktori:
   ```bash
   ls
   ```
   Jika ada file `index.html`, itu adalah halaman default.

3. Buka file `index.html` untuk diedit:
   ```bash
   nano index.html
   ```

4. Untuk mencari teks "This", tekan `Ctrl + W`, lalu ketik `this`. Ganti teks sesuai keinginan.

5. Simpan perubahan dengan menekan `Ctrl + X`, kemudian tekan `Y` untuk menyimpan, dan `Enter` untuk keluar.

### Langkah 4: Refresh Halaman
Setelah mengedit file, cukup refresh halaman browser untuk melihat perubahan yang sudah dibuat.
