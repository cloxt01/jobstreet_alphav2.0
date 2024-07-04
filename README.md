# jobstreet_alphav2.0

`jobstreet_alphav2.0` adalah versi terbaru dari `jobstreet_alpha`, yang dirancang untuk mempermudah pengguna dalam mengajukan lamaran pekerjaan dengan satu klik serta memantau proses lamaran tersebut. Dalam versi ini, telah dilakukan berbagai pembaruan dan perbaikan untuk meningkatkan kinerja dan stabilitas aplikasi.

## Fitur Utama

- **One-Click Apply**: Ajukan lamaran pekerjaan hanya dengan satu klik.
- **Monitoring Aplikasi**: Pantau status lamaran pekerjaan secara real-time.
- **Pembaruan Algoritma Question**: Algoritma yang diperbarui untuk menjawab pertanyaan seputar lamaran pekerjaan dengan lebih akurat.

## Pembaruan dari Versi Sebelumnya

- **Perbaikan Bug**: Berbagai bug yang ada pada versi sebelumnya telah diperbaiki.
- **Perbaikan submitApplicationFailure**: Perbaikan pada kegagalan pengiriman aplikasi.
- **Pembaruan Algoritma Question**: Algoritma yang lebih baik untuk memberikan jawaban yang lebih relevan.

## Instalasi

Untuk menginstal dan menjalankan `jobstreet_alphav2.0`, ikuti langkah-langkah berikut:

1. Clone repo ini ke dalam komputer Anda:

    ```bash
    git clone https://github.com/cloxt01/jobstreet_alphav2.0.git
    ```

2. Masuk ke direktori repo:

    ```bash
    cd jobstreet_alphav2.0
    ```

3. Install dependencies menggunakan Composer:

    ```bash
    composer install
    ```

## Konfigurasi

1. **config.json**: File ini digunakan untuk mengatur settingan proses apply sesuai selera Anda. Contoh konfigurasi dapat ditemukan di dalam file `config.example.json`. Salin file ini dan sesuaikan sesuai kebutuhan Anda.

    ```json
    {
        "pageSize": 5,
        "sortmode": "ListedDate",
        "refreshJobs": 30
    }
    ```

2. **auth.json**: File ini digunakan untuk autentikasi aplikasi. Isi file ini dengan informasi autentikasi yang diperlukan.

    ```json
    {
        "access_token": "your_access_token_here",
        "refresh_token": "your_refresh_token_here"
        "id_token": "your_id_token_here"
    }
    ```

3. Konfigurasi file `.env` dengan informasi yang diperlukan, seperti API key dan informasi database.

## Penggunaan

1. Jalankan aplikasi dengan perintah berikut:

    ```bash
    php artisan serve
    ```

2. Akses aplikasi melalui browser di `http://localhost:8000`.

## Output
![Expected Results](https://drive.google.com/uc?export=view&id=1E8tTBcPxPaWs0FRbQMT66qjdFa414e-b)

## Lisensi

Aplikasi ini dilisensikan di bawah [MIT License](LICENSE).
