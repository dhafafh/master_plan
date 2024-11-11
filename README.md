# DHAFA FIRJATULLAH HIKMAL 
# 362358302074

# PRAKTIKUM 1
1. Selesaikan langkah-langkah praktikum tersebut, lalu dokumentasikan berupa GIF hasil akhir praktikum beserta penjelasannya di file README.md! Jika Anda menemukan ada yang error atau tidak berjalan dengan baik, silakan diperbaiki.
2. Jelaskan maksud dari langkah 4 pada praktikum tersebut! Mengapa dilakukan demikian? Membuat Struktur Data: Kelas Plan berfungsi sebagai model data yang menyimpan daftar tugas. Ini membantu memisahkan logika bisnis dari tampilan (UI), yang merupakan praktik terbaik dalam pengembangan aplikasi. Organisasi Kode: Dengan menempatkan model di folder models, kode menjadi lebih terorganisir dan mudah dikelola. Ini memudahkan pengembang untuk menemukan dan memperbarui bagian tertentu dari aplikasi. Pemeliharaan dan Skalabilitas: Memisahkan model dari tampilan memungkinkan aplikasi untuk lebih mudah dipelihara dan diskalakan. Perubahan pada logika data tidak akan mempengaruhi tampilan dan sebaliknya.
3. Mengapa perlu variabel plan di langkah 6 pada praktikum tersebut? Mengapa dibuat konstanta ? Penyimpanan Data: plan digunakan untuk menyimpan dan mengelola data tugas yang akan ditampilkan di aplikasi. Ini memungkinkan aplikasi untuk menambah, mengubah, dan menghapus tugas sesuai kebutuhan pengguna. Pemeliharaan State: Dengan menggunakan variabel plan, aplikasi dapat dengan mudah melacak perubahan pada daftar tugas dan memperbarui tampilan UI secara dinamis ketika ada perubahan data.
4. Lakukan capture hasil dari Langkah 9 berupa GIF, kemudian jelaskan apa yang telah Anda buat! ![prak 1](https://github.com/user-attachments/assets/f1fe7287-f825-401a-a9f2-92e8ae9d2a1b)

5. Apa kegunaan method pada Langkah 11 dan 13 dalam lifecyle state ? initState(): Method ini digunakan untuk menginisialisasi state. Pada Langkah 11, initState() digunakan untuk menginisialisasi ScrollController yang akan mengatur perilaku scroll dan keyboard pada aplikasi.
6. Kumpulkan laporan praktikum Anda berupa link commit atau repository GitHub ke dosen yang telah disepakati !

# PRAKTIKUM 2
1. Selesaikan langkah-langkah praktikum tersebut, lalu dokumentasikan berupa GIF hasil akhir praktikum beserta penjelasannya di file README.md! Jika Anda menemukan ada yang error atau tidak berjalan dengan baik, silakan diperbaiki sesuai dengan tujuan aplikasi tersebut dibuat.
2. Jelaskan mana yang dimaksud InheritedWidget pada langkah 1 tersebut! Mengapa yang digunakan InheritedNotifier? Pada langkah 1, yang dimaksud dengan InheritedWidget adalah sebuah widget yang memungkinkan data atau state untuk dibagikan ke seluruh widget tree tanpa harus melewati constructor dari setiap widgetInheritedWidget sangat berguna untuk mengelola state yang perlu diakses oleh banyak widget dalam aplikasi Flutter1.
3. Jelaskan maksud dari method di langkah 3 pada praktikum tersebut! Mengapa dilakukan demikian? Method initState() adalah bagian dari lifecycle widget di Flutter yang dipanggil sekali ketika stateful widget pertama kali dibuat. Ini adalah tempat yang tepat untuk melakukan inisialisasi yang hanya perlu dilakukan sekali, seperti mengatur controller, listener, atau memulai animasi. Alasan Penggunaan: Dalam konteks praktikum ini, initState() digunakan untuk menginisialisasi ScrollController dan menambahkan listener padanya. Listener ini akan memanggil FocusScope.of(context).requestFocus(FocusNode()) setiap kali ada perubahan pada posisi scroll. Ini berguna untuk menghilangkan fokus dari input field ketika pengguna menggulir daftar, sehingga keyboard akan disembunyikan secara otomatis.
4. Lakukan capture hasil dari Langkah 9 berupa GIF, kemudian jelaskan apa yang telah Anda buat! ![prak 2](https://github.com/user-attachments/assets/a167ff65-8b7f-474a-987b-014db6776da2)

5. Kumpulkan laporan praktikum Anda berupa link commit atau repository GitHub ke dosen yang telah disepakati !

# PRAKTIKUM 3
1. Selesaikan langkah-langkah praktikum tersebut, lalu dokumentasikan berupa GIF hasil akhir praktikum beserta penjelasannya di file README.md! Jika Anda menemukan ada yang error atau tidak berjalan dengan baik, silakan diperbaiki sesuai dengan tujuan aplikasi tersebut dibuat.  
3. Lakukan capture hasil dari Langkah 14 berupa GIF, kemudian jelaskan apa yang telah Anda buat! ![prak 3](https://github.com/user-attachments/assets/27413b10-a604-45d1-b16d-291636ba6c36)

4. Kumpulkan laporan praktikum Anda berupa link commit atau repository GitHub ke dosen yang telah disepakati !

