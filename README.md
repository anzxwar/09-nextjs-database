|  | Pemrograman Berbasis Framework 2024 |
|--|--|
| NIM |  2341728026|
| Nama |  Anwar Alif Katresna |
| Kelas | TI - 3A 

![Screenshot](assets/s1.png)  
Hal yang dipelajari: Cara menautkan akun github dengan vercel dan cara mendeploy projek di vercel


![Screenshot](assets/s2.png)  
![Screenshot](assets/s22.png)
Hal yang dipelajari: Cara membuat database pada vercel


![Screenshot](assets/s3.png)  


![Screenshot](assets/s4.png) 


![Screenshot](assets/s5.png) 


Fungsi tersebut melakukan queri dan mengubahnya dari struktur data menjadi nilai numerik, sehingga nilai tersebut bisa digunakan pada variabel const numberOfInvoices,numberOfCustomers,totalPaidInvoices,totalPendingInvoices.



![Screenshot](assets/s6.png) 


![Screenshot](assets/s7.png) 


![Screenshot](assets/s8.png) 


# W10 Praktikum 1: Membuat route login

Pada praktikum ini, Anda dapat melanjutkan project dari Codelab #09 sebelumnya.

## Soal 1
#### Coba running di localhost, capture hasilnya dan buatlah laporan di README.md. Jelaskan apa yang telah Anda pelajari dan bagaimana tampilannya saat ini? Apakah ada error ?

- Membuat halaman login khusus dengan menggunakan JSX di file `/app/login/page.tsx`. Halaman ini mencakup formulir login dan logo Acme kemudian menginstal NextAuth.js untuk menangani otentikasi dalam aplikasi Anda dengan menjalankan perintah `npm i --save next-auth@beta`.
Membuat key rahasia untuk enkripsi cookie sesi pengguna dengan perintah `openssl rand -base64 32` dan menyimpannya di file `.env` lalu menambahkan logika middleware untuk melindungi rute tertentu, memeriksa apakah pengguna telah masuk sebelum memberikan akses. Menyiapkan `hash` kata sandi menggunakan bcrypt di file auth.ts. Menambahkan provider Credentials untuk memungkinkan masuk dengan nama pengguna dan kata sandi. Menambahkan fungsi sign in untuk menangani logika otentikasi, termasuk validasi email dan kata sandi.

![Screenshot W10P1](assets/s8.png)

![Screenshot W10P1](assets/w10s1.png)
- Terjadi error pada form login karena belum ada file yang diimpor untuk LoginForm dan AcmeLogo.


