# proyek4_hotel

Nama Kelompok: ZwitSal

Ketua: Afyar Siti Ababil (221511037)

Anggota: 1. Alya Angraini (221511042)
         2. Linda Santika (221511052)

Cara menjalankan aplikasi:
1. Buka kedua folder pada vscode
2. Jalankan terlebih dahulu back-end nya dengan perintah "php artisan serve"
3. Selanjutnya, run pada frontend nya dengan "klik" icon play pada main.dart, selain itu bisa menggunakan perintah "flutter run" pada terminal folder frontend
4. Run bisa dilakukan dengan emulator/chrome/media lain
5. Ada 2 role pada aplikasi, Jika masuk ke frontdesk,
   a. login dengan:
         - Username: linda
         - password: 12345678
   b. setelah login, akan langsung muncul dashboard frontdesk dengan tampilan kalendar dan list room type yang ada di hotel.
   c. menu lain dapat dipilih pada sidebar yang dapat diakses dengan klik strip 3 di pojok kiri atas tampilan.
7. Jika masuk ke Customer, lakukan registrasi terlebih dahulu dengan memasukan Nama, Email, No telp, dan password.
8. lakukan login setelah registrasi berhasil dengan cara memasukan email dan password yang telah didaftarkan sebelumnya.

List menu pada tampilan frontdesk :
1. Dashboard
   Tampilan berisi kalendar untuk membantu frontdesk dalam mengetahui dengan pasti tanggal.  serta ada list room tipe serta detail dari room tipe yang dipilih.
3. New booking (individu atau group)
   Tampilan untuk melakukan reservasi yang dikategorikan sebagai individual booking atau group/company booking
5. Guest List
   memperlihatkan daftar tamu yang ada apa tanggal tertentu sesuai dengan tanggal yang dipilih
7. In house Guest
   Menampilkan list dan jumlah tamu yang berstatus check in atau yang statusnya berada di dalam hotel
9. Reserved Status
    Menampilkan daftar tamu yang sudah reservasi ataupun yang sudah check in, ini membantu frontdesk dalam mendata ruangan yang terbooking. disini juga ststusnya bisa dirubah antara menjadi reserved, check-in, check-out, atau cancel reserved.
11. Available Room
    menampilkan list ruangan yang tersedia atau yang kosong, dengan status ruangan apakah dirty, clean, atau inspected.
13. Housekeeping
    ini akan berfungsi agar housekeeping tidak bingung mana ruangan yang harus dibersihkan, dan bagaimana status ruangan yang ada, yang mana akan ada status clean, dirty, pickup, inspected, atau out of order.
    
