# Intent
Intent adalah mekanisme untuk melakukan sebuah action dan komunikasi antar komponen aplikasi misal activity, services, dan broadcast receiver. Ada tiga penggunaan umum intent dalam aplikasi Android yaitu:
- Memindahkan satu activity ke activity lain dengan atau tidak membawa data.
- Menjalankan background service, misalnya melakukan sinkronisasi ke server dan menjalankan proses berulang (periodic/scheduler task).
- Mengirimkan obyek broadcast ke aplikasi yang membutuhkan. Misal, ketika aplikasi membutuhkan proses menjalankan sebuah background service setiap kali aplikasi selesai melakukan booting. Aplikasi harus bisa menerima obyek broadcast yang dikirimkan oleh sistem Android untuk event booting tersebut.

# Intent Dibagi Menjadi 2, yaitu:
- [x] Explicit Intent berfungsi untuk mengaktifkan komponen-komponen dalam satu aplikasi yang sama. Misalnya seperti : Berpindah Activity.
- [x] Implicit Intent berfungsi untuk memanggil fungsi activity yang sudah ada di fungsi internal android seperti Dial Number, Open Browser dan lainnya.

# Berikut Contoh Penerapan Intent Explicit

Tampilan sebelum mengisi data

![WhatsApp Image 2021-02-09 at 21 13 00](https://user-images.githubusercontent.com/60589822/107376324-57217980-6b1c-11eb-9ec2-ba16059b4b24.jpeg)

Tampilan setelah data terisi

![WhatsApp Image 2021-02-09 at 20 51 21](https://user-images.githubusercontent.com/60589822/107376337-5be62d80-6b1c-11eb-8ddd-17a946c2abed.jpeg)

Berpindah dari satu activity ke activity lain dengan membawa data

![WhatsApp Image 2021-02-09 at 20 51 22](https://user-images.githubusercontent.com/60589822/107376350-5f79b480-6b1c-11eb-835e-aeab3016e022.jpeg)
