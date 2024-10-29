# labpy02-den
Nama : Den Fahmi Satria <p>
Kelas : TI.24.A.5 <p> 
Nim : 312410523 <p>
Mata Kuliah : Bahasa pemograman <p> 
## Judul: pemesanan tiket bioskop
### Flowchart
![.gambar1](es1.PNG)

- **Mulai**: Proses dimulai dengan langkah ini
- **menginisiasi harga tiket:**
  masukkan untuk tiket reguler = Rp.50000
  dan untuk Vip = Rp.100000
  diskon bagi yang member adalah 20%
  maka tentukan harga untuk tiket reguler dan tiket Vip, serta diskon untuk member

- **input tipe tiket:** pembeli diminta untuk memasukkan tipe tiket yang ingin dibeli, apakah Vip atau Reguler
- **input status member:** pembeli diminta memasukkan status keanggotaan mereka, apakah memiliki kartu member, jika iya "iya" dan jika tidak "tidak"
- **validasi tipe tiket** Program memeriksa apakah tipe tiket yang diinput adalah "Reguler" atau "VIP": <p>
  Jika tipe tiket adalah "reguler", lanjutkan ke langkah berikutnya dengan harga tiket diatur ke Rp50.000. <p>
  Jika tipe tiket adalah "VIP", lanjutkan ke langkah berikutnya dengan harga tiket diatur ke Rp100.000. <p>
  Jika tipe tiket bukan "reguler" atau "VIP", anggap sebagai input yang tidak valid dan minta pengguna untuk memasukkan tipe tiket yang benar. <p>

- **Periksa Apakah Harga Tidak Nol:**
Program memeriksa apakah harga tiket sudah diatur (tidak nol):

Jika harga sudah diatur, lanjutkan ke langkah berikutnya.

Jika harga belum diatur (nol), kembali ke input tipe tiket.

- **Cek Status Member dan Hitung Diskon:**

Program memeriksa apakah pengguna memiliki kartu member:

Jika pengguna memiliki kartu member ("ya"), harga akhir dihitung dengan memberikan diskon 20%.

Jika pengguna tidak memiliki kartu member ("tidak"), harga akhir tetap sama dengan harga tiket tanpa diskon.

- **Tampilkan Harga Akhir:** Program menampilkan total harga tiket yang harus dibayar oleh pengguna.
- **Selesai:** Proses selesai

### program python
program python akan di tampilkan seperti ini dari flowchart yang ada di atas
![.gambar2](es2.PNG)

### eksekusi dari Python yang ada di atas
dan ini adalah eksekusi yang akan di tampilkan jika kalian menginputkan ya atau tidak
![.gambar3](es3.PNG)


# **judul:membuat kalkulator sederhana**

![.gambar4](es6.PNG)

- **1. Mulai:**

Titik awal dari flowchart, yang menandakan proses dimulai.

- **2. Masukkan Angka Pertama (angka1):**

Pengguna diminta memasukkan angka pertama yang akan digunakan dalam perhitungan.

- **3. Masukkan Angka Kedua (angka2):**

Pengguna diminta memasukkan angka kedua.

- **4. Masukkan Operator Aritmatika (operator):**

Pengguna diminta memasukkan operator aritmatika yang ingin digunakan. Operator dapat berupa +, -, *, atau /.

- **5. Apakah Operator +?:**

Sistem memeriksa apakah operator yang dimasukkan adalah +.

Ya: Jika ya, maka sistem akan menghitung angka1 + angka2.

Tidak: Jika tidak, maka sistem lanjut ke langkah berikutnya.

- **6. Apakah Operator -?:**

Sistem memeriksa apakah operator yang dimasukkan adalah -.

Ya: Jika ya, maka sistem akan menghitung angka1 - angka2.

Tidak: Jika tidak, maka sistem lanjut ke langkah berikutnya.

- **7. Apakah Operator *?:***

Sistem memeriksa apakah operator yang dimasukkan adalah *.

Ya: Jika ya, maka sistem akan menghitung angka1 * angka2.

Tidak: Jika tidak, maka sistem lanjut ke langkah berikutnya.

- **8. Apakah Operator /?:**

Sistem memeriksa apakah operator yang dimasukkan adalah /.

Ya: Jika ya, maka sistem memeriksa apakah angka2 tidak sama dengan nol.

Ya: Jika angka2 bukan nol, maka sistem akan menghitung angka1 / angka2.

Tidak: Jika angka2 adalah nol, sistem akan menampilkan pesan error bahwa pembagian dengan nol tidak bisa dilakukan.

Tidak: Jika operator bukan /, maka sistem menampilkan pesan error bahwa operator tidak valid.

- **9. Tampilkan Hasil:**

Sistem menampilkan hasil perhitungan yang sesuai dengan operator yang dipilih.

- **10. Selesai:**

Proses selesai dan flowchart berakhir.
