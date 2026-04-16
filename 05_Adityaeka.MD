Modul: Interaksi Dinamis dengan JavaScript Vanilla dan DOM
1. Pendahuluan: Komponen Pembentuk Web
Dalam pengembangan web, kita sering mendengar analogi tubuh manusia untuk memahami tiga pilar utamanya:

HTML (Badan): Kerangka atau struktur dasar halaman.

CSS (Tampilan): Estetika, warna, dan tata letak yang mempercantik badan.

JavaScript (Otak): Logika yang membuat halaman menjadi hidup dan interaktif.

2. Memahami DOM (Document Object Model)
DOM adalah jembatan yang memungkinkan JavaScript untuk berkomunikasi dengan HTML. Ketika halaman web dimuat, browser membuat representasi objek dari halaman tersebut sehingga JavaScript bisa mengubah isi, struktur, atau gaya dokumen secara dinamis.

3. Teknik Seleksi Elemen (DOM Selector)
Untuk memanipulasi elemen, kita harus "menangkap" elemen tersebut terlebih dahulu. Ada dua pendekatan utama yang sering digunakan:

getElementById(): Digunakan untuk mengambil satu elemen spesifik berdasarkan ID-nya. Ini adalah metode yang paling cepat dan efisien secara performa.

querySelector(): Metode yang lebih fleksibel. Kita bisa mengambil elemen berdasarkan:

Class (contoh: .nama-class)

ID (contoh: #nama-id)

Element / Tag / Komponen (contoh: h1, div, button)

Tips Optimasi: Jika Anda hanya perlu mengambil satu elemen berdasarkan ID, gunakan getElementById karena proses pencariannya lebih ringan bagi browser dibandingkan querySelector.
