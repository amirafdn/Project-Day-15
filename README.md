# Project-Day-15
Project Python 5 OOP : Membersihkan data marketing_data.csv menggunakan prinsip OOP.

Prinsip OOP yang akan digunakan:
- Basic OOP
- Inheritance
- Polymorphism

Script menggunakan pandas

---
**Kelompok 11**
- Nur Ali Arfan (Universitas Sultan Ageng Tirtayasa) - Ketua Kelompok
- Dyah Ayu Hastuti (Universitas Negeri Malang)
- Amira Husna Fidani (Universitas Negeri Malang)
- Gamma Jhoevinka Aulia Sandra (Universitas Muhammadiyah Surakarta)
- Sutriana Dina Uli Manurung (Politeknik Negeri Medan)

---
# **Task 1: Basic OOP**

Buatlah class MarketingDataETL yang memiliki tiga metode:

*   extract(): akan membaca data dari sebuah file CSV (Misalkan, marketing_data.csv)

*   transform(): akan melakukan pembersihan dan transformasi sederhana pada data (seperti mengubah format tanggal atau membersihkan nilai yang kosong)

*   store(): akan menyimpan data yang telah ditransformasi ke dalam struktur data DataFramet.

---
# **Task 2: Inheritance & Polymorphism**

*   Gunakan inheritance untuk membuat class TargetedMarketingETL yang mewarisi dari MarketingDataETL.
*   Tambahkan metode segment_customers() yang mengelompokkan pelanggan berdasarkan kriteria tertentu (misalnya, pengeluaran total atau kategori produk yang dibeli).
*   Demonstrasi polymorphism dengan meng-override metode transform() dalam TargetedMarketingETL untuk menambahkan logika segmentasi pelanggan ke dalam proses transformasi.
