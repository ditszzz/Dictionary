# Dictionary untuk menyimpan nilai mahasiswa
nilai_mahasiswa = {}

def tambah_data():
    nama = input("Masukkan nama mahasiswa: ")
    tugas = float(input("Masukkan nilai tugas: "))
    uts = float(input("Masukkan nilai UTS: "))
    uas = float(input("Masukkan nilai UAS: "))
    
    nilai_akhir = 0.3 * tugas + 0.35 * uts + 0.35 * uas
    
    nilai_mahasiswa[nama] = nilai_akhir
    print(f"nama} telah ditambahkan.")

def ubah_data():
    nama = input("Masukkan nama mahasiswa yang ingin diubah: ")
    tugas = float(input("Masukkan nilai tugas baru: "))
    uts = float(input("Masukkan nilai UTS baru: "))
    uas = float(input("Masukkan nilai UAS baru: "))
    
    del nilai_mahasiswa[nama]
    nilai_akhir = 0.3 * tugas + 0.35 * uts + 0.35 * uas
    
    nilai_mahasiswa[nama] = nilai_akhir
    print(f"Data {nama} telah diubah.")

def hapus_data():
    nama = input("Masukkan nama mahasiswa yang ingin dihapus: ")
    del nilai_mahasiswa[nama]
    print(f"Data {nama} telah dihapus.")

def tampilkan_data():
    if not nilai_mahasiswa:
        print("Tidak ada data nilai mahasiswa.")
    else:
        print("Daftar Nilai Mahasiswa:")
        for nama, nilai in nilai_mahasiswa.items():
            print(f"Nama: {nama}, Nilai: {nilai}")

def cari_data():
    nama = input("Masukkan nama mahasiswa yang ingin dicari: ")
    if nama in nilai_mahasiswa:
        print(f"Nilai mahasiswa {nama} adalah {nilai_mahasiswa[nama]}")
    else:
        print(f"Mahasiswa {nama} tidak ditemukan.")

def main():
    while True:
        print("\nMenu Pilihan:")
        print("1. Tambah Data")
        print("2. Ubah Data")
        print("3. Hapus Data")
        print("4. Tampilkan Data")
        print("5. Cari Data")
        print("6. Keluar")
        
        pilihan = input("Masukkan pilihan Anda: ")
        
        if pilihan == '1':
            tambah_data()
        elif pilihan == '2':
            ubah_data()
        elif pilihan == '3':
            hapus_data()
        elif pilihan == '4':
            tampilkan_data()
        elif pilihan == '5':
            cari_data()
        elif pilihan == '6':
            print("Program selesai.")
            break
        else:
            print("Pilihan tidak valid. Silakan coba lagi.")

if __name__ == "__main__":
    main()

   # Flowchart:
Mulai:
Membuat program dengan nama main.
Input:
Tampilkan menu pilihan. unggu input dari pengguna.
Proses:
Jika pilihan adalah 1, jalankan fungsi tambah_data.
Jika pilihan adalah 2, jalankan fungsi ubah_data.
Jika pilihan adalah 3, jalankan fungsi hapus_data.
Jika pilihan adalah 4, jalankan fungsi tampilkan_data.
Jika pilihan adalah 5, jalankan fungsi cari_data.
Jika pilihan adalah 6, tutup program.
Output:
Tampilkan hasil dari setiap fungsi sesuai dengan tindakan yang dipilih.
Ulangi:
Kembali ke langkah Input untuk mendapatkan pilihan berikutnya.
