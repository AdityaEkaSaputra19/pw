1. Penggunaan DOM Selector
Point: Langkah pertama dalam manipulasi web adalah memilih elemen HTML yang ingin diubah melalui DOM Selector.
Reason: JavaScript membutuhkan "alamat" atau referensi yang spesifik ke elemen HTML agar instruksi (seperti mengubah warna atau teks) tepat sasaran.
Example: Menggunakan document.getElementById("id_elemen") atau querySelector untuk memilih elemen berdasarkan Class, ID, atau Tag/Component.
Point Jadi: Tanpa selector yang tepat, kita tidak bisa memanipulasi elemen apa pun di dalam halaman web.

2. Penerapan Event Listener
Point: Event Listener adalah mekanisme untuk membuat halaman web menjadi interaktif.
Reason: Website tidak boleh hanya statis; ia harus bereaksi terhadap tindakan pengguna. Event listener berfungsi untuk "mendengarkan" aktivitas tertentu.
Example: Penggunaan fungsi addEventListener dengan tipe event seperti onclick (saat diklik), onchange (saat input berubah), atau onpress (saat tombol ditekan).
Point Jadi: Event listener menghubungkan tindakan pengguna dengan logika program (fungsi) yang telah kita buat.

3. Optimasi: getElementById vs QuerySelector
Point: Memilih metode selector yang tepat merupakan bagian dari Optimasi kode.
Reason: Walaupun keduanya berfungsi memilih elemen, getElementById secara teknis lebih cepat untuk pencarian spesifik, sementara querySelector lebih fleksibel untuk seleksi yang kompleks.
Example: * getElementById('input') untuk mengambil elemen dengan ID secara langsung.
querySelector('.class-name') jika ingin mengambil elemen berdasarkan kelas CSS.
Point Jadi: Efisiensi dalam pemilihan metode selector akan berpengaruh pada performa eksekusi JavaScript pada browser.

4. Data Mining (Pengambilan Nilai)
Point: Inti dari interaksi formulir adalah proses pengambilan data atau Data Mining.
Reason: Untuk mengolah informasi yang dimasukkan pengguna (seperti nama atau pesan), kita harus bisa menarik nilai tersebut dari elemen input.
Example: Mengakses properti .value dari sebuah elemen input, misalnya: input.value = "Hello".
Point Jadi: Pengambilan nilai (value) adalah jembatan antara apa yang diketik pengguna di layar dengan data yang akan diproses oleh sistem.
Kesimpulan (Narasi Umum)
Papan tulis ini menjelaskan analogi pengembangan web: HTML sebagai Bakat/Struktur, CSS sebagai Tampilan, dan JS sebagai Otak. Untuk menggerakkan "Otak" tersebut pada "Struktur" yang ada, kita melalui alur:
Memilih target (Selector).
Menunggu aksi (Event Listener).
Mengambil data (Data Mining/Value).
Memberikan respon (seperti alert atau console yang tertulis di bagian Optimasi).
