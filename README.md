# Materi-Belajar-Kotlin-Dasar

## 📘 Belajar Kotlin Dasar - by Yudibilly

Selamat datang di repository **Belajar Kotlin Dasar**. Repository ini berisi materi pembelajaran Kotlin dari level pemula yang disusun secara bertahap dan sistematis. Cocok untuk kamu yang baru mulai belajar Kotlin, baik untuk backend, Android, maupun desktop.

---

### 📂 Struktur Materi & File

| No | Topik Pembelajaran             | Deskripsi Singkat                               | File Kode                                            |         |                                            |
| -- | ------------------------------ | ----------------------------------------------- | ---------------------------------------------------- | ------- | ------------------------------------------ |
| 1  | Pengenalan Kotlin              | Apa itu Kotlin, kelebihan, dan cara setup       | [`PengenalanKotlin.kt`](./PengenalanKotlin.kt)       |         |                                            |
| 2  | Hello World                    | Program Kotlin paling dasar                     | [`HelloWorld.kt`](./HelloWorld.kt)                   |         |                                            |
| 3  | Komentar                       | Cara menulis komentar 1 baris dan banyak baris  | [`Komentar.kt`](./Komentar.kt)                       |         |                                            |
| 4  | Tipe Data Number               | Byte, Short, Int, Long, Float, Double           | [`TipeDataNumber.kt`](./TipeDataNumber.kt)           |         |                                            |
| 5  | Tipe Data Char                 | Penggunaan karakter `'A'`, escape char          | [`TipeDataChar.kt`](./TipeDataChar.kt)               |         |                                            |
| 6  | Tipe Data Boolean              | Tipe data logika `true` / `false`               | [`TipeDataBoolean.kt`](./TipeDataBoolean.kt)         |         |                                            |
| 7  | Tipe Data String               | String biasa, template string, dan multi-line   | [`TipeDataString.kt`](./TipeDataString.kt)           |         |                                            |
| 8  | Variabel (val & var)           | Perbedaan variabel tetap dan bisa diubah        | [`Variable.kt`](./Variable.kt)                       |         |                                            |
| 9  | Nullable & Null Safety         | Penanganan null dengan `?`, `!!`, `?:`, dll     | [`Nullable.kt`](./Nullable.kt)                       |         |                                            |
| 10 | Array                          | Array satu dimensi, akses elemen                | [`TipeDataArray.kt`](./TipeDataArray.kt)             |         |                                            |
| 11 | List & MutableList             | Perbedaan List (immutable) dan MutableList      | [`ListDanMutableList.kt`](./ListDanMutableList.kt)   |         |                                            |
| 12 | Set & Map                      | Struktur data Set (unik) dan Map (key-value)    | [`SetDanMap.kt`](./SetDanMap.kt)                     |         |                                            |
| 13 | Range                          | Menggunakan `1..10`, `downTo`, dan `step`       | [`TipeDataRange.kt`](./TipeDataRange.kt)             |         |                                            |
| 14 | Operasi Matematika             | Tambah, kurang, kali, bagi, modulus             | [`OperasiMatematika.kt`](./OperasiMatematika.kt)     |         |                                            |
| 15 | Operasi Perbandingan           | `==`, `!=`, `>`, `<`, `>=`, `<=`                | [`OperasiPerbandingan.kt`](./OperasiPerbandingan.kt) |         |                                            |
| 16 | Operasi Boolean                | `&&`, \`                                        |                                                      | `, `!\` | [`OperasiBoolean.kt`](./OperasiBoolean.kt) |
| 17 | If Expression                  | Percabangan dengan `if`, `else`, dan expression | [`IfExpression.kt`](./IfExpression.kt)               |         |                                            |
| 18 | When Expression                | Switch versi Kotlin                             | [`WhenExpression.kt`](./WhenExpression.kt)           |         |                                            |
| 19 | Perulangan For                 | Loop array, range, dengan `for`                 | [`PerulanganFor.kt`](./PerulanganFor.kt)             |         |                                            |
| 20 | While & Do-While               | Perulangan dengan kondisi                       | [`PerulanganWhile.kt`](./PerulanganWhile.kt)         |         |                                            |
| 21 | Break dan Continue             | Kontrol alur dalam perulangan                   | [`BreakContinue.kt`](./BreakContinue.kt)             |         |                                            |
| 22 | Fungsi Dasar                   | Cara membuat fungsi, parameter, return          | [`FungsiDasar.kt`](./FungsiDasar.kt)                 |         |                                            |
| 23 | Lambda & Higher-Order Function | Fungsi sebagai parameter, lambda                | [`LambdaFunction.kt`](./LambdaFunction.kt)           |         |                                            |

---

### 🎯 Tujuan Pembelajaran

* Mengenal dasar-dasar Kotlin dari nol
* Mempersiapkan dasar kuat untuk belajar Android/Kotlin lebih lanjut
* Membiasakan struktur dan sintaks Kotlin modern

---

### 🚀 Cara Menjalankan

1. Pastikan kamu sudah install Kotlin:

   ```bash
   sdk install kotlin
   ```

   atau bisa pakai IntelliJ IDEA / Android Studio

2. Jalankan file Kotlin:

   ```bash
   kotlinc HelloWorld.kt -include-runtime -d hello.jar
   java -jar hello.jar
   ```

3. Atau jika pakai Android Studio: buat project > buat file `.kt` > run.

---

### 📦 Rekomendasi Lanjutannya

* [ ] Pengenalan OOP Kotlin (class, object, constructor)
* [ ] Kotlin Extension Function
* [ ] Kotlin Coroutines (basic)
* [ ] Kotlin untuk Android Development (project starter)

---

### 📌 Lisensi

Repo ini bebas digunakan untuk edukasi dan pembelajaran. Jangan lupa kasih ⭐ jika bermanfaat.
Kamu juga bisa fork dan modifikasi untuk kebutuhan belajar atau konten kamu sendiri.

