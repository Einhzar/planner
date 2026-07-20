# 📋 Planner Harian & Keuangan (OOP-Based)

Aplikasi web sederhana untuk mengelola daftar tugas harian dan pencatatan pengeluaran yang dibangun dengan menerapkan 4 Pilar Utama **Pemrograman Berorientasi Objek (PBO)**.

🔗 **Demo Live / Deployment:** [Masukkan URL Vercel/Netlify/GitHub Pages Kamu Di Sini]

---

## 💡 Penerapan Pilar OOP
Aplikasi ini dirancang menggunakan JavaScript ES6+ dengan struktur OOP sebagai berikut:

1. **Abstraction (Abstraksi):**
   * Class `Item` bertindak sebagai *Abstract Base Class* yang menyimpan identitas umum (`#id`, `#judul`). Class ini tidak bisa diinstansiasi langsung.
2. **Inheritance (Pewarisan):**
   * Class `TodoItem` dan `ExpenseItem` mewarisi atribut dan metode dasar dari class `Item` menggunakan kata kunci `extends`.
3. **Encapsulation (Enkapsulasi):**
   * Penggunaan *Private Fields* (`#`) untuk menjaga kerahasiaan atribut di dalam class. Akses data dilakukan secara terkontrol menggunakan metode *getter* dan *setter*.
4. **Polymorphism (Polimorfisme):**
   * Metode `render()` diimplementasikan ulang secara berbeda di class `TodoItem` (tampilan tugas) dan `ExpenseItem` (tampilan nominal Rp).

---

## 🛠️ Teknologi yang Digunakan
* HTML5
* CSS3
* Vanilla JavaScript (ES6+ OOP)

---

## 👤 Pembuat
* **Nama:** [Nama Kamu]
* **NIM:** [NIM Kamu]
* **Kelas:** [Kelas/Mata Kuliah PBO]
