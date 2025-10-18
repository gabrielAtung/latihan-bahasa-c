# 🧩 Tugas Pemrograman C – Program Login Sederhana
## 🎯 Tujuan Pembelajaran
- Mahasiswa/peserta diharapkan dapat:
- Menggunakan input/output dasar (printf, scanf).
- Memahami struktur kontrol (if, else, while).
- Menggunakan string di C (char array, strcmp).
- Membuat sistem login sederhana dengan validasi username dan password.

## 📋 Deskripsi Soal

Buatlah sebuah program login sederhana menggunakan bahasa C dengan ketentuan berikut:

Program memiliki username dan password yang sudah ditentukan di dalam program (hardcoded).
Contoh:
```
Username: admin 
Password: 12345
```
Program meminta pengguna untuk memasukkan username dan password.

Jika username dan password benar, tampilkan pesan:

> Login berhasil! Selamat datang, admin. 


Jika salah, tampilkan pesan:

> Username atau password salah. Silakan coba lagi.


Program memberi kesempatan maksimal 3 kali percobaan login.
Jika setelah 3 kali gagal, tampilkan pesan:

> Akses ditolak. Silakan coba lagi nanti.


Gunakan fungsi string seperti strcmp() untuk membandingkan input user dengan data yang disimpan.

## 💡 Contoh Tampilan Program
```
=== PROGRAM LOGIN SEDERHANA === 
Masukkan Username: admin
Masukkan Password: 12345
Login berhasil! Selamat datang, admin.
```


Jika salah:
```
=== PROGRAM LOGIN SEDERHANA ===
Masukkan Username: user
Masukkan Password: 0000
Username atau password salah. Silakan coba lagi.

Masukkan Username: admin
Masukkan Password: 123
Username atau password salah. Silakan coba lagi.

Masukkan Username: admin
Masukkan Password: 12345
Login berhasil! Selamat datang, admin.
```

Jika gagal 3 kali:

> Akses ditolak. Silakan coba lagi nanti.

## 🔧 Petunjuk Tambahan
- Gunakan #include <string.h> untuk fungsi strcmp().
- Gunakan while atau for untuk membatasi jumlah percobaan.
- Simpan username dan password dalam variabel bertipe string, misalnya:
```
char username[20];
char password[20];
```
