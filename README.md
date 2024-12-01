# Labpy06
# Feby Putri Khurunnisa 312410245
# Soal praktikum
Buat program sederhana dengan mengaplikasikan penggunaan fungsi yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan:

* Fungsi tambah() untuk menambah data

* Fungsi tapilkan() untuk menampilkan data

* Fungsi hapus(nama) untuk menghapus data berdasarkan nama

* Fungsi ubah(nama) untuk mengubah data berdasarkan nama

* Buat flowchart dan penjelasan programnya

![Screenshot 2024-12-01 100029](https://github.com/user-attachments/assets/84297324-f55b-4744-8d6d-4b19ed7a8467)
![Screenshot 2024-12-01 100429](https://github.com/user-attachments/assets/06c3fa25-692c-4f83-8801-67aa56a2ee10)

# Menu Tambah Data

 1. Fungsi ini menerima dua parameter: nama dan nilai.

 2. Fungsi ini akan menambahkan dictionary yang berisi nama dan nilai mahasiswa ke dalam list mahasiswa.

 3. Setelah menambahkan data, fungsi akan mencetak pesan konfirmasi.

# Menu Tampilkan Data

 1. Fungsi ini menampilkan semua data mahasiswa yang tersimpan dalam list.

 2. Jika list mahasiswa kosong, akan ditampilkan pesan bahwa tidak ada data.

 3. Jika ada data, fungsi ini akan mencetak daftar mahasiswa beserta nilainya dengan nomor urut.

# Menu Hapus Data

 1. Fungsi ini menghapus data mahasiswa berdasarkan nama yang diberikan.

 2. Menggunakan list comprehension, fungsi ini membuat list baru _mhs yang berisi semua mahasiswa kecuali yang namanya sama dengan nama yang diberikan.

 3. Jika ada perubahan dalam jumlah mahasiswa, maka data mahasiswa diupdate dan akan mencetak pesan konfirmasi. Jika tidak, akan mencetak pesan bahwa data tidak ditemukan.

# Menu Ubah Data

 1. Fungsi ini digunakan untuk mengubah nilai mahasiswa berdasarkan nama.

 2. Fungsi ini mencari mahasiswa yang namanya sama dengan nama yang diberikan dan mengubah nilainya menjadi nilai_baru.

 3. Jika data ditemukan, akan mencetak pesan konfirmasi. Jika tidak, akan mencetak pesan bahwa data tidak ditemukan.

# Flowchart

# Latihan 11
Ubahlah kode dibawah ini menjadi fungsi menggunakan lambada import math

def a(x): return x**2

def b(x, y): return math.sqrt(x2 + y2)

def c(*args): return sum(args)/len(args)

def d(s): return "".join(set(s))

