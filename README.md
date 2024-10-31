# Penghitung Umur

Aplikasi Java ini adalah program sederhana yang digunakan untuk menghitung usia seseorang berdasarkan tanggal lahir. Dengan memanfaatkan kelas pembantu untuk perhitungan, aplikasi ini dapat menghitung usia secara akurat hingga satuan hari.

## Fitur Utama

- **Input Tanggal Lahir**: Menerima input tanggal lahir dari pengguna dalam format `dd/MM/yyyy`.
- **Perhitungan Akurat**: Menghitung usia secara lengkap dalam tahun, bulan, dan hari berdasarkan tanggal hari ini.
- **Validasi Format**: Program memverifikasi bahwa input yang dimasukkan sesuai dengan format yang diminta, sehingga memastikan input valid.

## Struktur File

1. **PenghitungUmur.java**
   - File utama dan titik masuk aplikasi, berisi metode `main` untuk menjalankan program.
   - Meminta tanggal lahir pengguna dalam format `dd/MM/yyyy` melalui terminal.
   - Mengirim data ke kelas `PenghitungUmurHelper` untuk menghitung usia.
   - Menampilkan hasil perhitungan dalam format yang mudah dipahami.

2. **PenghitungUmurHelper.java**
   - Kelas pembantu yang melakukan perhitungan utama.
   - Menggunakan `LocalDate` dari Java untuk menangani perbedaan tanggal secara efisien.
   - Menghitung selisih waktu dalam satuan tahun, bulan, dan hari berdasarkan tanggal yang diterima dari pengguna.
   - Memberikan hasil perhitungan kembali ke kelas utama.

## Cara Menjalankan Program

Untuk menjalankan aplikasi ini, ikuti langkah-langkah di bawah:

1. **Pastikan Java Development Kit (JDK) Terinstal**:
   - Pastikan bahwa [JDK](https://www.oracle.com/java/technologies/javase-downloads.html) sudah terinstal di komputer Anda. Program ini membutuhkan JDK 8 atau versi yang lebih baru.
   
2. **Simpan Kedua File dalam Satu Direktori**:
   - Tempatkan file `PenghitungUmur.java` dan `PenghitungUmurHelper.java` di dalam direktori yang sama.

3. **Buka Terminal dan Navigasikan ke Direktori File**:
   - Buka terminal atau command prompt Anda, kemudian arahkan ke direktori tempat file disimpan.

4. **Kompilasi Program**:
   - Kompilasi kedua file dengan perintah berikut:
     ```bash
     javac PenghitungUmur.java PenghitungUmurHelper.java
     ```

5. **Jalankan Program**:
   - Setelah berhasil dikompilasi, jalankan program menggunakan perintah:
     ```bash
     java PenghitungUmur
     ```

6. **Input Tanggal Lahir dan Dapatkan Hasil**:
   - Masukkan tanggal lahir Anda dalam format `dd/MM/yyyy` saat diminta. Program kemudian akan menghitung dan menampilkan usia Anda dalam satuan tahun, bulan, dan hari.

## Contoh Penggunaan

```plaintext
Masukkan tanggal lahir Anda (format: dd/MM/yyyy): 15/08/1990
Umur Anda adalah 33 tahun, 2 bulan, dan 16 hari.
