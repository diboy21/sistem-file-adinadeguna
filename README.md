# sistem-file-adinadeguna
SISTEM FILE

1. Lihat peralatan I/O, character device, yang ada pada system komputer.

![Gambar WhatsApp 2025-02-25 pukul 09 42 32_9f2c162a](https://github.com/user-attachments/assets/f86db6ba-92b4-4f2f-9d4b-1754b4808d78)

Menampilkan daftar perangkat character device pada sistem Linux yang ada di direktori /dev. Perintah ini membantu melihat perangkat seperti keyboard, mouse, dan terminal (/dev/tty), yang beroperasi dengan data berbasis karakter.

2. Buatlah sub direktori januari, februari dan maret sekaligus pada direktori latihan5.

![Gambar WhatsApp 2025-02-25 pukul 09 42 33_d640d10b](https://github.com/user-attachments/assets/f4abd73b-252d-49e5-b03b-b1ec5905d009)

Membuat tiga subdirektori dalam direktori latihan5 sekaligus, tanpa harus menjalankan perintah mkdir tiga kali. Opsi -p memastikan bahwa jika latihan5 belum ada, maka akan dibuat terlebih dahulu.

3. Buatlah file dataku yang berisi nama, nim dan alamat anda pada sub direktori januari dan copy-kan file tersebut ke sub direktori februari dan maret.

![Gambar WhatsApp 2025-02-25 pukul 09 42 33_84b2215e](https://github.com/user-attachments/assets/fccec2d7-5da6-43d5-a488-83a83a4ddb5e)


Membuat file dataku di dalam direktori januari yang berisi informasi pribadi. Menyalin file dataku dari januari ke februari dan maret, sehingga ketiga direktori memiliki file yang sama.

4. Ubahlah ijin akses file dataku pada sub direktori januari sehingga group dan others dapat melakukan write.

![Gambar WhatsApp 2025-02-25 pukul 09 43 56_cdbe5b69](https://github.com/user-attachments/assets/94c9dd31-44f6-49a7-8dfc-51ea53c9fbe3)

Mengubah izin file dataku sehingga, Memungkinkan semua pengguna (group dan others) untuk mengedit isi file.

5. Ubahlah ijin akses file dataku pada sub direktori pebruari sehingga user dapat melakukan baik write, read maupun execute, tetapi group dan others hanya bisa read dan execute.

![Gambar WhatsApp 2025-02-25 pukul 09 43 56_8d1f55fe](https://github.com/user-attachments/assets/5bae4426-d212-47d8-81c7-e72faf1c8616)

Kegunaan, Hanya pemilik file yang bisa mengedit, tetapi orang lain bisa membaca dan menjalankan file jika diperlukan.

6. Ubahlah ijin akses file dataku pada sub direktori maret sehingga semua dapat melakukan write, read dan execute.

![Gambar WhatsApp 2025-02-25 pukul 09 43 57_15fc16ca](https://github.com/user-attachments/assets/4073d1df-46ab-4fe5-80ed-4e7c324ad839)

Semua pengguna dapat membaca, menulis, dan mengeksekusi file, tanpa batasan.

7. Hapuslah direktori maret.
![Gambar WhatsApp 2025-02-25 pukul 09 46 02_cf9ee1dc](https://github.com/user-attachments/assets/0db5fcb2-11ba-409b-800c-80a3ed9482c8)


Menghapus latihan5/maret dan memastikan tidak ada sisa file atau subdirektori di dalamnya.

8. Ubahkan kepemilikan sub direktori februari sehingga user dan group hanya dapat melakukan read, dan cobalah untuk membuat direktori baru haha pada sub direktori februari.

![Gambar WhatsApp 2025-02-25 pukul 09 46 03_7313f31b](https://github.com/user-attachments/assets/7574a62b-385e-4e10-89cb-b38a85fe28e5)

Mencoba membuat subdirektori lalalostyou di dalam februari, yang sebenarnya gagal karena tidak ada izin menulis.Namun, jika ingin membuat lalalostyou, izin harus diubah menggunakan chmod 750 agar pemilik bisa menulis.

9. Modifikasi umask dari file dataku pada sub direktori januari menjadi 027 dan berapakan nilai default-nya?

![Gambar WhatsApp 2025-02-25 pukul 09 46 03_c88fd76c](https://github.com/user-attachments/assets/451d2908-bd74-4095-8cd9-7dbaaaca772d)

Mengatur izin default untuk file baru agar lebih ketat dalam keamanan. Setelah membuat file baru (dataku_baru), perintah ls -l digunakan untuk mengecek apakah izin yang diberikan sesuai dengan umask.

10. Buatlah link dari file dataku ke file dataku.kemarin dengan perintah list perhatikan berapa link yang terjadi?

![Gambar WhatsApp 2025-02-25 pukul 09 46 55_f4b2a03e](https://github.com/user-attachments/assets/8f594696-3af6-4803-8a1a-ad4bb634341e)

Hard link adalah file yang merujuk ke inode yang sama di sistem file. setelah membuat dua hard link, perintah ls -l akan menunjukkan bahwa file dataku, dataku.ini, dan dataku.juga memiliki jumlah link yang meningkat. Memastikan bahwa semua hard link merujuk ke file yang sama dan berbagi konten yang sama.

KESIMPULAN
Dalam praktikum ini, saya telah mempelajari berbagai konsep dasar dalam pengelolaan sistem file di Linux, mulai dari melihat perangkat I/O, membuat dan mengatur izin direktori, hingga memodifikasi kepemilikan dan membuat link file. Latihan-latihan ini membantu memahami bagaimana sistem operasi menangani file dan hak aksesnya, yang sangat penting untuk administrasi sistem. Dengan pemahaman ini, saya bisa lebih mudah mengelola file, menjaga keamanan data, serta mengoptimalkan penggunaan sistem Linux dalam berbagai skenario.
preview
