# M.Fadil Hidayat 1810131310009
Tugas 1 disimari

Linux merupakan nama yang diberikan kepada sistem operasi komputer Unix. Linux
merupakan salah satu contoh pengembangan perangkat lunak bebas dan sumber
utamanya yang terbuka. Linux berasal dari nama sang produsen, yang diperkenalkan pada
1991 oleh Linux Torvalds.
Pengertian dan fungsi linux adalah salah satu sistem operasi yang bermodel open source
dan berbasis UNIX. Fungsi linux sendiri tidak jauh berbeda dengan sistem operasi lain
yaitu melakukan multitasking, multiprogramming, multiprocessing dan time sharing.
Administrator sistem melakukan beberapa hal penting berkaitan dengan user dan group
antara lain :
• Pendaftaran nama login
• Pembekuan nama login user
• Penghapusan nama login user
• Pembuatan group baru
• Pembagian group
• Pengaturan direktori home
• Pengamanan file-file password
Dalam sistem Linux, nama login dapat diberikan pada :
• User biasa. Contoh : anton. wiwit, afri, pelatihan2000
• Aplikasi. Contoh : mysql, qmail, squid
• Device. Contoh : lp
Service. Contoh : cron, ftp
2. Tuliskan langkah-langkah instalasi linux dengan varian Debian pada komputer anda!
1. Pada installer Boot Menu langsung pilih saja Install.
2. Pilih bahasa yang sobat inginkan.
3. Pilih lokasi tempat tinggal anda. Jika tidak ada dalam daftar, sobat bisa memilih
yang lain.
4. Pilih benua tempat tinggal
5. Nah barulah sobat bisa memilih negara tempat tinggal
6. Konfigurasi dasar standar lokal, pilih Amerika Serikat yang telah umum
digunakan.
*Lembar kerja ini diadaptasi dari LEMBAR KERJA Kelas Sistem Interaksi - Fakultas Ilmu Komputer
Universitas Indonesia. © Harry B. Santoso, PhD & Suci Fadhilah, MA
7. Pilih tata letak keyboard yaitu American English yang telah umum digunakan
oleh banyak orang.
9. Selanjutnya akan ada proses konfigurasi jaringan, jika terjadi kegagalan
perbaikan saja dan klik lanjutkan.
10. Selanjutnya memilih metode konfigurasi jaringan. Karena SO Linux Debian ini
akan kita gunakan untuk sebuah jaringan, maka kita perlu mengkonfigurasi jaringan.
Maka pilih konfigurasikan jaringan secara manual. Sobat harus tau aturan pemberian
Alamat IP untuk mengonfigurasi ini. Jika sobat tidak membutuhkan konfigurasi ini,
maka sobat bisa melewatinya dengan memilih untuk tidak mengonfigurasi jaringan saat
ini.
11. ilakan masukan Alamat IP sesuai keinginan sobat. Contohnya dengan IP
Address kelas C seperti 192.168.100.23
12. Biasanya netmask akan terisi otomastis. Jika tidak terisi otomatis, silakan isi
secara manual. Contohnya netmask untuk kelas C 255.255.255.0
13. Gerbang juga biasanya terisi otomastis. Jika tidak terisi otomastis, sobat
masukan Network ID seperti IP Address namun segmen terakhir atau Host ID ubah
dengan angka 1. Contoh pada gateway dengan mengacu pada IP Address yang telah
saya buat 192.168.100.1
14. Begitupun Name Server Address akan terisi otomatis. Jika tidak sama saja
dengan Gateway, atau sama dengan Alamat IP yang digunakan server.
15. Isi hostname dengan nama apapun yang sobat sukai. Pada windows hostname
adalah nama komputer. Mengerti kan? Saya akan contohkan nama host: debian.
16. Domain bisa sobat isi dengan hostname dengan diakhiri dengan sebuah domain
(.com, .net, .sch, .org dll). Contoh: debian.net
17. Isi kata sandi root. Root password adalah password untuk super user pada SO
yang saat ini sobat instalkan. Superuser itu seperti Administrator pada SO Windows.
18. Masukan kembali kata sandi root yang telah sobat buat untuk pengungkit.
19. Pasukan nama lengkap untuk user baru. 20. Username yang dimasukkan sesuai
dengan keinginan sobat. Agar lebih mudah, masukan saja nama depan sobat.
21.Masukan kata sandi untuk pengguna baru yang telah sobat buat. 22. Masukan
kembali password yang baru sobat buat untuk pengungkit. 23. Konfigurasi zona
waktu, pilihlah kota terdekat dengan tempat tinggal sobat. Atau pilihlah kota yang
sesuai dengan zona waktu di tempat tinggal 24. Jika meminta pemilihan disk,
pilihlah disk yang sobat inginkan untuk dipilih dalam pemartisian.
25. Pada skema pemartisian, pilihlah semua file dalam satu partisi untuk menyimpan
semua sistem file pada satu partisi. Pilihan ini direkomendasikan untuk pengguna baru.
26.Jika sobat telah selesai mengatur pemartisian, maka pilihlah selesaikan partisi dan
tulis perubahan ke disk.
27.Pada pertanyaan tulis change to disk, pilihlah yes untuk menyimpan pengaturan
pemartisian yang telah sobat lakukan.
28.Pada pertanyaan pindai CD atau DVD lain, silakan pilih ya jika sobat memiliki
repositori paket lain di Debian. Jika tidak punya, pilih saja No.
29.Pada pertanyaan menggunakan netwotk mirror, pilih saja Tidak jika sobat tidak akan
menggunakan jaringan lain pada SO yang sobat instal.
30.Pada pertanyaan berpartisipasi dalam survei paket, pilih saja Tidak jika sobat tidak
akan ikut berpartisipasi dalam survei penggunaan paket. 31.Nah di sinilah bagian yang
berbeda dengan penginstalan Debian 6 GUI. Jika pada Debian 6 GUI dalam perangkat
lunak yang diinstal, pilihlah Grapichal Desktop Environment. Sedangan pada Debian
Teks tidak.
*Lembar kerja ini diadaptasi dari LEMBAR KERJA Kelas Sistem Interaksi - Fakultas Ilmu Komputer
Universitas Indonesia. © Harry B. Santoso, PhD & Suci Fadhilah, MA
33.Pada proses selanjutnya tidak akan selamat pada penginstalan Debian 6 GUI.
Tunggu hingga selesai.
34.Pada pertanyaan instal GRUB Boot Loader ke master boot record, pilihlah ya.
35.Nah tidak lama setelah ini proses instalasi pun selesai. Klik continue dan Debian
akan merestart otomatis.
36. Akan langsung memulai proses Booting, lalu login dengan user dan password
user
3. Pilih minimal 5 command yang dapat dijalakan di Linux terminal! Jelaskan command
tersebut dan sertakan screenshot hasil dari command tersebut.
1. Pwd
Perintah dasar Linux pwd berfungsi untuk mencari path dari direktori (folder)
yang Anda gunakan saat ini. Perintah ini akan mengembalikan path yang absolut (penuh),
yang pada dasarnya merupakan path semua direktori yang diawali dengan garis miring
depan (/). Contoh dari path absolut adalah /home/username.
2. Cd
*Lembar kerja ini diadaptasi dari LEMBAR KERJA Kelas Sistem Interaksi - Fakultas Ilmu Komputer
Universitas Indonesia. © Harry B. Santoso, PhD & Suci Fadhilah, MA
Untuk menjelajahi file dan direktori Linux, gunakan perintah cd. Perintah Linux
ini memerlukan path penuh atau nama direktori, tergantung pada direktori yang Anda
gunakan saat ini.
Misalkan saat ini Anda sedang berada di /home/username/Documents dan ingin
membuka Photos, subdirektori dari Documents. Untuk melakukannya, Anda hanya perlu
mengetikkan command ini: cd Photos.
Contoh lainnya, ketika Anda ingin beralih ke direktori yang sepenuhnya baru,
misalnya, /home/username/Movies. Dalam contoh ini, ketik cd yang diikuti dengan path
absolut direktori: cd /home/username/Movies.
Berikut beberapa jalan pintas (shortcut) untuk memudahkan navigasi:
• cd .. (dengan dua tanda titik) untuk memindahkan satu direktori ke atas.
• cd jika ingin langsung membuka folder home.
• cd- (dengan tanda penghubung) untuk berpindah ke direktori sebelumnya.
Satu hal yang perlu diperhatikan, shell Linux sangat sensitif. Jadi, Anda harus
mengetikkan nama direktori dengan benar dan tepat.
3. Ls
Is merupakan perintah dasar pada Linux yang digunakan untuk melihat konten
atau isi direktori. Secara default, command ini akan menampilkan isi dari direktori yang
Anda gunakan saat ini.
*Lembar kerja ini diadaptasi dari LEMBAR KERJA Kelas Sistem Interaksi - Fakultas Ilmu Komputer
Universitas Indonesia. © Harry B. Santoso, PhD & Suci Fadhilah, MA
• Is -R akan membuat daftar semua file yang ada di sub-direktori.
• Is -a akan menampilkan file yang tersembunyi.
• Is -al akan membuat daftar file dan direktori yang memuat informasi mendetail,
seperti permission (hak akses), ukuran (size), pemilik (owner), dll.
4. cat command
cat (akronim dri concatenate) adalah salah satu perintah dasar sistem operasi Linux yang
sering digunakan. Perintah ini berfungsi untuk membuat daftar konten atau isi file pada
standard output (sdout). Untuk menjalankan command ini, ketik cat yang kemudian
diikuti dengan nama dan ekstensi file. Sebagai contoh: cat file.txt.
Berikut beberapa cara untuk menggunakan perintah cat:
• cat > filename untuk membuat file baru.
• cat filename1 filename2>filename3 untuk menggabungkan dua file (1 dan 2) dan
menyimpan outputnya di file baru (3).
• cat filename | tr a-z A-Z >output.txt untuk mengonversi file ke penggunaan huruf
besar atau huruf kecil.
*Lembar kerja ini diadaptasi dari LEMBAR KERJA Kelas Sistem Interaksi - Fakultas Ilmu Komputer
Universitas Indonesia. © Harry B. Santoso, PhD & Suci Fadhilah, MA
5. cp command
Gunakan perintah dasar Linux cp untuk menyalin file dari direktori saat ini ke
direktori yang berbeda. Misalnya, command cp scenery.jpg /home/username/Pictures
untuk membuat salinan scenery.jpg (dari direktori saat ini) ke direktori Pictures.
