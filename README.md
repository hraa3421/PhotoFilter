
## PRAKTIKUM 1: Ambil Kamera

**Deskripsi:**

Aplikasi ini merupakan implementasi fitur kamera pada Flutter yang memungkinkan pengguna untuk mengambil foto menggunakan kamera perangkat.

**Fitur Utama:**

* Mengambil foto menggunakan kamera perangkat.
* Menampilkan hasil foto yang telah diambil.

### 🖼 Screenshot Running

![Screenshot aplikasi kamera](assets/kamera-flutter.gif)
_Tampilan aplikasi saat mengambil foto._

### ❓ FAQ

**1. Apa yang dimaksud dengan `void async` pada Praktikum 1?**

`void async` dalam Dart (Flutter) adalah kombinasi dari dua konsep:

* `void`: Menandakan bahwa fungsi tidak mengembalikan nilai.
* `async`: Menandakan bahwa fungsi berjalan secara asynchronous (tidak langsung dieksekusi secara berurutan), memungkinkan penggunaan `await` di dalamnya.

**Kesimpulan:** Gunakan `async` jika fungsi memiliki operasi yang membutuhkan waktu (misalnya, mengambil foto, memuat data dari API, membaca file).

---

## PRAKTIKUM 2: Photo Filter

**Deskripsi:**

Aplikasi ini merupakan pengembangan dari Praktikum 1, dengan menambahkan fitur filter foto. Pengguna dapat memilih filter dari carousel gambar yang telah disediakan untuk diterapkan pada foto yang diambil.

**Fitur Utama:**

* Pilihan filter tersedia dalam format carousel gambar.
* Pengguna dapat dengan mudah memilih filter yang diinginkan.

### 🖼 Screenshot Running

![Screenshot aplikasi kamera](assets/filter-carousel.gif)
_Tampilan aplikasi saat mengambil foto._

### ❓ FAQ (Lanjutan)

**2. Jelaskan fungsi dari anotasi `@immutable` dan `@override`?**

* **Fungsi dari `@immutable` yaitu:**
    * ✅ Dapat digunakan untuk menandakan bahwa suatu class tidak boleh diubah (immutable) setelah dibuat.
    * ✅ Biasanya diterapkan pada class yang bersifat stateless (tidak berubah setelah inisialisasi).

* **Fungsi dari `@override` yaitu:**
    * Anotasi yang digunakan ketika kita ingin mengganti (menimpa) metode dari superclass (kelas induk) di dalam subclass (kelas anak).
    * **Kenapa `@override` Penting?**
        * ✅ Memastikan metode di subclass benar-benar menggantikan metode dari superclass.
        * ✅ Mencegah kesalahan penulisan nama metode yang bisa menyebabkan bug.
        * ✅ Membantu pembaca kode memahami bahwa metode tersebut berasal dari superclass.

---

## PRAKTIKUM 3: Gabungan Praktikum 1 dan Praktikum 2

**Deskripsi:**

Aplikasi ini merupakan pengembangan dari Praktikum 1 dan praktikum 2, dengan menambahkan fitur filter foto. Pengguna dapat memilih filter dari carousel gambar yang telah disediakan untuk diterapkan pada foto yang diambil.

**Fitur Utama:**

* Semua fitur dari Praktikum 1 (mengambil dan menampilkan foto).
* Menambahkan filter pada foto yang diambil.
* Pilihan filter tersedia dalam format carousel gambar.
* Pengguna dapat dengan mudah memilih filter yang diinginkan.

### 🖼 Screenshot Running

![Screenshot aplikasi kamera](assets/photo-filter-carousel.gif)
_Tampilan aplikasi saat mengambil foto._

---

   
