# Simple Banking System - Java

## Deskripsi Proyek
Simple Banking System adalah program sederhana berbasis Java yang mensimulasikan pengelolaan data nasabah dan rekening bank. Program ini menerapkan konsep *Object-Oriented Programming* (OOP) dengan membagi sistem ke dalam beberapa kelas, yaitu `Main`, `Bank`, `Customer`, dan `Account`.

Program ini mendemonstrasikan pengelolaan nasabah, pembuatan rekening, pengecekan saldo, penyetoran uang (*deposit*), dan penarikan uang (*withdraw*).

## Fitur Utama
- **Pengelolaan Nasabah:** Menambahkan nasabah dengan nama depan dan nama belakang.
- **Pengelolaan Rekening:** Menambahkan rekening ke nasabah.
- **Pengecekan Saldo:** Menampilkan saldo rekening.
- **Deposit:** Menambahkan saldo rekening dengan nominal positif.
- **Withdraw:** Mengurangi saldo rekening dengan nominal positif yang tidak melebihi saldo tersedia.
- **Validasi Transaksi:** Mencegah penyetoran dengan nominal tidak valid dan penarikan melebihi saldo.

## Struktur File

```text
Simple-Banking-System/
├── Main.java
├── Bank.java
├── Customer.java
├── Account.java
└── README.md
```

### Penjelasan Kelas

**1. `Main.java`**
- Menjadi titik awal eksekusi program.
- Membuat objek bank dan menambahkan nasabah.
- Membuat dua rekening dengan saldo awal berbeda.
- Menampilkan informasi nasabah, jumlah rekening, dan saldo.
- Melakukan simulasi deposit dan withdraw.

**2. `Bank.java`**
- Mengelola daftar nasabah menggunakan array.
- Menyediakan method `addCustomer()` untuk menambahkan nasabah.
- Menyediakan method `getNumOfCustomers()` untuk mengetahui jumlah nasabah.
- Menyediakan method `getCustomer()` untuk mengambil data nasabah berdasarkan indeks.
- Memiliki kapasitas maksimal 10 nasabah.

**3. `Customer.java`**
- Menyimpan nama depan dan nama belakang nasabah.
- Mengelola daftar rekening milik nasabah.
- Menyediakan method untuk mengambil informasi nama dan rekening.
- Memiliki kapasitas maksimal 5 rekening per nasabah.

**4. `Account.java`**
- Menyimpan dan mengelola saldo rekening.
- Menyediakan method `getBalance()` untuk mengambil saldo.
- Menyediakan method `deposit()` untuk menambahkan saldo.
- Menyediakan method `withdraw()` untuk melakukan penarikan saldo.

## Teknologi yang Digunakan
- **Bahasa Pemrograman:** Java
- **Paradigma Pemrograman:** Object-Oriented Programming (OOP)
- **Struktur Data:**
