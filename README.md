# Tugas-Pbo

Pada tugas kali ini saya akan menjelaskan tentang kode kode yang telah saya buat pada kode.py
Kode ini merupakan implementasi dari tiga kelas yaitu Mahasiswa, Jurusan, dan Universitas. Berikut penjelasan untuk setiap bagian kode:

Kelas Mahasiswa:

__init__(self, nama, nim, jurusan): Ini adalah konstruktor kelas Mahasiswa yang akan dipanggil saat membuat objek mahasiswa baru. Ia memiliki tiga parameter yaitu nama, nim, dan jurusan. Setiap parameter tersebut akan disimpan sebagai atribut objek mahasiswa.
tampilkan_info(self): Metode ini digunakan untuk menampilkan informasi mengenai objek mahasiswa. Ia mencetak nama, NIM, dan nama jurusan mahasiswa.
Kelas Jurusan:

__init__(self, nama_jurusan): Ini adalah konstruktor kelas Jurusan yang akan dipanggil saat membuat objek jurusan baru. Ia memiliki satu parameter yaitu nama_jurusan yang akan disimpan sebagai atribut objek jurusan. Selain itu, ia juga membuat atribut DaftarMahasiswa yang merupakan list untuk menyimpan objek mahasiswa yang terdaftar di jurusan.
tambah_mahasiswa(self, mahasiswa): Metode ini digunakan untuk menambahkan objek mahasiswa ke dalam DaftarMahasiswa di jurusan. Ia menerima objek mahasiswa sebagai parameter dan menambahkannya ke list DaftarMahasiswa.
tampilkan_daftar_mahasiswa(self): Metode ini digunakan untuk menampilkan daftar mahasiswa yang terdaftar di jurusan. Ia mencetak nama, NIM, dan nama jurusan setiap mahasiswa yang ada di list DaftarMahasiswa.
Kelas Universitas:

__init__(self, nama_universitas): Ini adalah konstruktor kelas Universitas yang akan dipanggil saat membuat objek universitas baru. Ia memiliki satu parameter yaitu nama_universitas yang akan disimpan sebagai atribut objek universitas. Selain itu, ia juga membuat atribut DaftarJurusan yang merupakan list untuk menyimpan objek jurusan di universitas.
tambah_jurusan(self, jurusan): Metode ini digunakan untuk menambahkan objek jurusan ke dalam DaftarJurusan di universitas. Ia menerima objek jurusan sebagai parameter dan menambahkannya ke list DaftarJurusan.
tampilkan_daftar_jurusan(self): Metode ini digunakan untuk menampilkan daftar jurusan yang ada di universitas. Ia mencetak nama setiap jurusan yang ada di list DaftarJurusan.
Setelah mendefinisikan tiga kelas di atas, kode selanjutnya melakukan penggunaan kelas-kelas tersebut dengan cara berikut:

1.Membuat objek Universitas dengan meminta input dari pengguna untuk nama universitas.
2.Membuat objek Jurusan dengan meminta input dari pengguna untuk nama jurusan, dan menambahkannya ke dalam objek universitas yang telah dibuat.
3.Meminta input dari pengguna untuk jumlah mahasiswa.
4.Melakukan loop sebanyak jumlah mahasiswa untuk meminta input nama dan NIM mahasiswa, dan kemudian membuat objek Mahasiswa dengan data yang dimasukkan. Objek mahasiswa tersebut kemudian ditambahkan ke objek jurusan.
5.Menampilkan daftar jurusan
6.Setelah semua mahasiswa ditambahkan ke jurusan, kode memanggil metode tampilkan_daftar_jurusan() dari objek universitas_xyz untuk menampilkan daftar jurusan yang ada di universitas. Metode ini akan mencetak nama setiap jurusan yang ada di list DaftarJurusan dalam objek universitas.
7Selanjutnya, kode memanggil metode tampilkan_daftar_mahasiswa() dari objek jurusan_ti untuk menampilkan daftar mahasiswa yang terdaftar dalam jurusan Teknik Informatika di universitas XYZ. Metode ini akan mencetak nama, NIM, dan nama jurusan setiap mahasiswa yang ada di list DaftarMahasiswa dalam objek jurusan.

Dengan demikian, kode ini melakukan inisialisasi objek universitas, jurusan, dan mahasiswa, serta menampilkan informasi tentang daftar jurusan dan daftar mahasiswa dalam jurusan tersebut.
