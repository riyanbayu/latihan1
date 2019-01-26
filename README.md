### **[Tutorial] Penggunaan Github untuk pemula Part 1 (upload file ke github)**


Buka website github, buat akun baru terlebih dahulu(maaf saya tidak perlu menjelaskan bagaimana membuat akun baru, karena saya yakin semua pasti pernah membuat akun di jejaring social, jadi saya rasa sudah sanggup untuk membuat akun github)

![pertama bgt](https://user-images.githubusercontent.com/47026574/51785829-75fb8000-218e-11e9-9de3-dbffaa82de6c.png)

Setelah terbuat akun-nya, login dengan akun baru(kalau langsung diarahkan ke halaman utama), setelah itu pada pojok kiri atas , lalu klik new.

**Membuat Repositori online**

![ke 2](https://user-images.githubusercontent.com/47026574/51786516-fe325300-2197-11e9-862d-123cc723e905.png)


Lalu kalian akan diarahkan ke halaman pembuatan repository, pembuatan repositori ini tergantung dari project kalian yang mau kalian upload, jadi saya harapkan kalian sudah punya proyek yang ingin di upload ke repositori.

**Untuk mengisi, ada beberapa hal yang perlu di perhatikan :**

**Repository name** : nama repository(isi saja dengan nama proyek), akan lebih rapi kalau misalnya nama repository juga di beri jenis pemogramannya juga contohnya “Android/test” atau “js/test”.
**Description** : deskripsi repository (bisa kisah project dan siapa yang terlibat)
**Public/Private** : kondisi repository mau di public (di buat umum) atau private(di buat pribadi atau tertutup)
**Intiallize the repository with README** : ini adalah isi dokumentasi pada project yang dikerjakan, saya sarankan tidak usah di centang karena mempermudah praktek untuk mengelola git.


![ke 3](https://user-images.githubusercontent.com/47026574/51786560-6ed96f80-2198-11e9-84f5-23a9496fe4f4.png)

Setelah di isi sesuai dengan keinginan, klik saja tombol **“create repository”**, maka pada halaman selanjutnya akan menampilkan repositori yang sudah dibuat, dan tahap selanjutnya adalah upload project ke repository online.

![ke 4](https://user-images.githubusercontent.com/47026574/51786618-5fa6f180-2199-11e9-81bd-9a9e1be242de.png)

Mengupload folder(repositori lokal) Sebelum melakukan upload pastikan di PC atau laptop sudah tersedia git, untuk Windows bisa menggunakan cmder yang sempat saya tulis disini untuk memudahkan proses penggunaan git, sedangkan untuk pengguna linux bisa menginstall dengan menggunakan perintah **“sudo apt-get install git”** jika menggunakan OSX install dengan brew, jika sudah file siap di upload ke repository online. jika sudah memiliki proyek yang ingin diletakkan di repository online, buka saja folder project tersebut dengan perintah command line, atau jika belum terbiasa di command line (nanti belajar command line) buka saja folder tersebut menggunakan file exploler dan klik kanan **“open terminal/cmder here”**. Ada beberapa perintah dasar yang akan digunakan, perintah ini sudah tersedia kok saat membuat repo tadi (lihat gambar atas) git init git add . git commit -m **"first commit"** git remote add origin https://github.com/riyanbayu/Latihan1.git git push -u origin master

Setelah mengupload tugas hasilnya akan seperti ini

![ke 5 bener](https://user-images.githubusercontent.com/47026574/51786767-9d0c7e80-219b-11e9-9613-2a860aad7ce7.png)

 git init untuk meng-set folder yang digunakan tersebut sebagai repo local git. bisa di bilang ini instalasi git pertama kali git add “.” atau nama file untuk menambah file project yang mau di upload sebelum di commit, tanda titik setelah kata **“add”** pada perintah tersebut adalah keseluruhan file dan folder project tersebut, saat awal upload kalian bisa menggunakan perintah tersebut. Namun saat commit atau upload ke repository selanjutnya bisa menggunakan perintah add dengan **“nama file”** untuk memberikan status commit. Ini adalah contohnya apabila ingin menggunakan **“git add”** :

// mengupload keseluruhan file pada repo (hanya digunakan saat upload pertama saja) git add . // mengupload file sesuai dengan nama file git add index.html // mengupload file pada dalam folder git add pages/index.html git commit -m **“isi commit”** untuk menambah keterangan/status perubahaan saat upload ke repo online, untuk memasukkan keterangan tersebut setelah **“git commit -m”** ditambah tanda petik lalu komentar(lihat di list perintah untuk contoh). git remote add origin **“link repo online”** untuk meng-setting remote origin dari repo online, repo online bisa dilihat pada link yang tersedia di bagian atas Project dengan format **“.git”**, diperlukan ini untuk mengakses ke repo tersebut sehingga kita bisa melakukan apapun di repo online tersebut.

git push origin **“nama branch”** Perintah untuk mengupload file yang ada pada repo lokal ke repo online yang diletakkan pada branch yang sudah tersedia di repo online. Setelah melakukan semua perintah silahkan cek di github, apakah file yg di upload sudah masuk atau tidak? jika iya maka anda berhasil mengelola git untuk tahap awal

Bentuk kode yang sudah dimasukkan ke GitBash

![ke 6](https://user-images.githubusercontent.com/47026574/51786301-e2797d80-2194-11e9-8c33-5c09543adace.png)

![ke 7](https://user-images.githubusercontent.com/47026574/51786312-076df080-2195-11e9-8829-ea6563d0ba66.png)
