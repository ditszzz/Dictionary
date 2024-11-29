 # Program Pengolah Data Nilai Akhir Mahasiswa

**Deskripsi Program**

Program ini adalah program yang dibuat mengguanakan Dictionary untuk mengolah data nilai akhir mahasiswa.
Program ini dibuat untuk mengelola data mahasiswa termasuk menampilkan, menambah, mengubah, menghapus, dan mencari data nilai mereka.
Program ini dibuat dengan menggunakan NIM sebagai _Key_ dan data mahasiswa (Nama, Nilai Tugas, Nilai UTS, Nilai UAS) sebagai _Value_.
Program ini menggunakan perhitungan nilai akhir dengan bobot sebesar Nilai Tugas 30% lalu Nilai UTS 35% dan Nilai UAS 35%

![image](https://github.com/user-attachments/assets/89ec3ef9-6dcd-4da3-b5a5-2ad2dbe9500d)

**Menu Program**

Program ini mempunyai beberapa menu yang akan ditampilkan di awal ketika dijalankan, diantaranya

L: Melihat daftar nilai mahasiswa.

T: Menambahkan data mahasiswa baru.

U: Mengubah data mahasiswa berdasarkan NIM.

H: Menghapus data mahasiswa berdasarkan NIM.

C: Mencari data mahasiswa berdasarkan NIM.

K: Keluar dari program.


**Fungsi Program**
1. Menghitung Nilai

Program ini menghitung Nilai Akhir berdasarkan formula yang ada.
![image](https://github.com/user-attachments/assets/1ff9d74b-82dd-41ce-935a-616a5fc0a144)

2. Menampilkan Data

Program ini menampilkan data mahasiswa dalam bentuk tabel. Apabila data di dalam program kosong maka tampilan tabel          tersebut juga kosong.

   ![Screenshot (21)](https://github.com/user-attachments/assets/308958db-e232-4730-a6c0-8ee1200f8ee6)

3. Menambahkan Data

Program ini akan meminta untuk memasukan data mahasiswa (Nama, Nilai Tugas, Nilai UTS, Nilai UAS) untuk selanjutnya akan     dihitung menjadi data nilai akhir.
Apabila program ini berhasil maka program akan menampilkan "Data berhasil ditambahkan!" dan program akan kembali ke menu     awal.

![image](https://github.com/user-attachments/assets/8728cb7a-af1d-4143-a65d-edbc79918095)

4. Mengubah Data

Program ini akan meminta untuk memasukan NIM mahasiswa sebagai _Key_.
Selanjutnya program akan meminta untuk memasukan data (Nama, Nilai Tugas, Nilai UTS, Nilai UAS) untuk kemudian akan diganti menjadi data yang baru. Apabila program ini berhasil maka program akan menampilkan "Data berhasil diubah!",  namun apabila NIM yang dimasukan salah maka tambilan program "Data tidak ditemukan!".

![image](https://github.com/user-attachments/assets/31c30a8c-1608-47bb-bbd2-7f48263e32f1)

5. Menghapus Data

Program ini akan meminta untuk memasukan NIM mahasiswa sebagai _Key_.
Selanjutnya apabila program ini berhasil maka program akan menampilkan "Data berhasil dihapus!",  namun apabila NIM yang dimasukan salah maka tambilan program "Data tidak ditemukan!".

![image](https://github.com/user-attachments/assets/3b6ce93e-4c0b-4db5-aaaf-67bd4c0faf58)

6. Mencari Data

Program ini akan meminta untuk memasukan NIM mahasiswa sebagai _Key_.
Selanjutnya apabila program ini berhasil maka program akan menampilkan data yang dicari,  namun apabila NIM yang dimasukan salah maka tampilan program "Data tidak ditemukan!".

![image](https://github.com/user-attachments/assets/07ac17be-816f-489b-afbe-231271e79984)

**Alur Penggunaan Program**

![Flowchart Pertemuan 10](https://github.com/user-attachments/assets/f22436f0-1063-47b7-9ad5-9a9b867c756f)


1. Menjalankan Program

   * Program akan menampilkan menu ketika dijalankan.
   * Ketika menu yang dipilih salah maka akan menampilkan "Pilihan tidak valid! Silakan coba lagi."

2. Memilih Menu

   * Ketik huruf sesuai pilihan menu:

     L: Melihat daftar nilai mahasiswa.

     T: Menambahkan data mahasiswa baru.

     U: Mengubah data mahasiswa berdasarkan NIM.

     H: Menghapus data mahasiswa berdasarkan NIM.

     C: Mencari data mahasiswa berdasarkan NIM.

     K: Keluar dari program.

3. Menambahkan Data

   * Pilih menu T (Tambah).

   * Masukkan informasi berikut:

     NIM: Nomor Induk Mahasiswa.

     Nama: Nama mahasiswa.

     Nilai Tugas, UTS, UAS: Nilai numerik.

   * Program akan otomatis menghitung nilai akhir dan menyimpan data.

4. Melihat Data

   * Pilih menu L (Lihat).

   * Data akan ditampilkan dalam tabel, termasuk NIM, nama, nilai tugas, UTS, UAS, dan nilai akhir.

5. Mengubah Data

   * Pilih menu U (Ubah).

   * Masukkan NIM mahasiswa yang ingin diubah.

   * Jika ditemukan, masukkan data baru (nama, nilai tugas, UTS, UAS).

   * Data akan diperbarui.

6. Menghapus Data

   * Pilih menu H (Hapus).

   * Masukkan NIM mahasiswa yang ingin dihapus.

   * Jika ditemukan, data akan dihapus dari daftar.

7. Mencari Data

   * Pilih menu C (Cari).

   * Masukkan NIM mahasiswa yang dicari.

   * Jika ditemukan, data akan ditampilkan.

8. Keluar dari Program

   * Pilih menu K (Keluar).

   * Program akan berhenti dengan pesan terima kasih.


**Kesimpulan**

Program ini sangat cocok untuk mengelola data sederhana, seperti nilai akhir semester, dengan fitur CRUD (Create, Read, Update, Delete). Dengan mengikuti alur di atas, pengguna dapat dengan mudah mengelola data mahasiswa.
