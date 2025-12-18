# Simple Calculator (JavaScript) ⚡

Kalkulator sederhana yang dibangun menggunakan **JavaScript vanilla**. Proyek ini mendemonstrasikan logika aritmatika dasar dan manipulasi data (atau DOM jika menggunakan browser) dengan kode yang bersih dan minimalis.

## 🚀 Fitur

- ➕ Penjumlahan, ➖ Pengurangan, ✖️ Perkalian, ➗ Pembagian.
- 🔄 Fungsi "Clear" untuk menghapus kalkulasi.
- 🔢 Mendukung angka desimal (float).
- ⚠️ Penanganan error untuk pembagian dengan nol.

## 🛠️ Teknologi yang Digunakan

- **JavaScript (ES6+)**
- **HTML5 & CSS3** (Jika menggunakan versi Web UI)
- **Node.js** (Jika menggunakan versi CLI/Terminal)

## 📥 Cara Menjalankan

### Versi Browser (Web UI)
1. Clone repository ini:
   ```bash
   git clone [https://github.com/username-kamu/simple-calculator-javascript.git](https://github.com/username-kamu/simple-calculator-javascript.git)

```

2. Buka file `index.html` di browser favorit kamu (Chrome, Firefox, Edge).
3. Selesai! Kamu bisa langsung mencoba kalkulatornya.

### Versi Terminal (Node.js)

Jika proyek ini berbasis console:

1. Pastikan kamu sudah menginstal [Node.js](https://nodejs.org/).
2. Jalankan perintah:
```bash
node calculator.js

```



## 📸 Contoh Kode (Logika Utama)

```javascript
function calculate(num1, operator, num2) {
  switch (operator) {
    case '+': return num1 + num2;
    case '-': return num1 - num2;
    case '*': return num1 * num2;
    case '/': return num2 !== 0 ? num1 / num2 : "Error: Division by zero";
    default: return "Invalid Operator";
  }
}

```

## 🧠 Konsep JavaScript yang Dipelajari

* **Variables & Data Types:** Menggunakan `let` dan `const`.
* **Functions:** Membuat fungsi yang dapat digunakan kembali.
* **Conditional Logic:** Menggunakan `if-else` atau `switch-case`.
* **Event Listeners:** (Opsional) Mengambil input dari klik tombol di HTML.

## 🤝 Kontribusi

Ingin membuat kalkulator ini lebih canggih? Kamu bisa berkontribusi dengan menambahkan:

* Fitur kalkulasi scientific (Sin, Cos, Tan).
* Riwayat (History) perhitungan.
* Dark mode pada tampilan UI.

1. Fork repo ini.
2. Buat branch baru (`git checkout -b fitur-baru`).
3. Commit perubahan (`git commit -m 'Tambah fitur X'`).
4. Push ke branch (`git push origin fitur-baru`).
5. Buat Pull Request.

## 📝 Lisensi

Proyek ini berada di bawah lisensi MIT. Bebas digunakan untuk belajar!

---

Dibuat dengan 💻 oleh Rizkya Gusnaldy Kalia

```
