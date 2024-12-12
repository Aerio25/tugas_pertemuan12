# tugas_pertemuan12

A. ALGORITMA PROGRAM

1.Deklarasi Class DaftarNilaiMahasiswa:

Atribut: self.data adalah list kosong yang digunakan untuk menyimpan data mahasiswa (nama dan nilai).

Method:

tambah(): Menambahkan data mahasiswa (nama dan nilai).

tampilkan(): Menampilkan seluruh data mahasiswa.

hapus(nama): Menghapus data mahasiswa berdasarkan nama.

ubah(nama): Mengubah nilai mahasiswa berdasarkan nama.

2.Constructor init:

Menginisialisasi atribut self.data sebagai list kosong, tempat penyimpanan data mahasiswa.

3.Method tambah():

Input: Nama mahasiswa dan nilai mahasiswa.

Proses:

Data yang berisi nama dan nilai mahasiswa disimpan dalam dictionary dan ditambahkan ke dalam list self.data.

Output: Menampilkan pesan konfirmasi bahwa data berhasil ditambahkan.

4.Method tampilkan():

Input: Tidak ada (menampilkan seluruh data).

Proses:

Mengecek apakah list self.data kosong.

Jika kosong, tampilkan pesan bahwa data belum ada.

Jika ada data, tampilkan seluruh nama dan nilai mahasiswa.

Output: Menampilkan seluruh data mahasiswa.

5.Method hapus(nama):

Input: Nama mahasiswa yang ingin dihapus.

Proses:

Mencari data mahasiswa dengan nama yang sesuai di dalam list self.data.

Jika ditemukan, data tersebut dihapus dari list.

Jika tidak ditemukan, tampilkan pesan bahwa data tidak ada.

Output: Menampilkan pesan konfirmasi bahwa data berhasil dihapus atau tidak ditemukan.
6.Method ubah(nama):

Input: Nama mahasiswa yang nilai-nya ingin diubah.

Proses:

Mencari data mahasiswa dengan nama yang sesuai.

Jika ditemukan, minta input nilai baru dan ubah nilai tersebut.

Jika tidak ditemukan, tampilkan pesan bahwa data tidak ada.

Output: Menampilkan pesan konfirmasi bahwa nilai berhasil diubah atau data tidak ditemukan.

7.Menu Utama:

Menampilkan menu pilihan kepada pengguna:

1: Tambah data.

2: Tampilkan data.

3: Hapus data.

4: Ubah data.

5: Keluar dari program.

Input: Pengguna memilih menu.

Jika pilihan adalah 1, panggil method tambah().

Jika pilihan adalah 2, panggil method tampilkan().

Jika pilihan adalah 3, minta nama mahasiswa untuk dihapus dan panggil method hapus(nama).

Jika pilihan adalah 4, minta nama mahasiswa untuk diubah nilai-nya dan panggil method ubah(nama).

Jika pilihan adalah 5, keluar dari program.

Jika pilihan tidak valid, tampilkan pesan error dan kembali ke menu.

#

B. CODE PROGRAM

![image](https://github.com/user-attachments/assets/fd61f57d-401b-4444-be20-e389430a3600)

![image](https://github.com/user-attachments/assets/6847924a-681a-40b7-99e2-a3440684ea00)

# 

C. RUNNING CODE

![tugas_pertemuan 2](https://github.com/user-attachments/assets/698fb98d-5050-4c5f-939d-74ae3a665d91)


