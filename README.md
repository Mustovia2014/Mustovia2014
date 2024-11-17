Program Pengelolaan Nilai Mahasiswa
Program ini dibuat menggunakan Python dan bertujuan untuk mengelola data nilai mahasiswa dengan fitur-fitur berikut:
- Menambah data
- Mengubah data
- Menghapus data
- Menampilkan semua data
- Mencari data berdasarkan NIM

  Fitur Program
- Tambah Data
  Pengguna dapat menambahkan data mahasiswa berupa NIM, nama, nilai tugas, UTS, dan UAS. Nilai akhir dihitung secara otomatis menggunakan formula:
  nilai_akhir = (tugas * 0.3) + (uts * 0.35) + (uas * 0.35)
- Ubah Data
  Data mahasiswa dapat diubah dengan memasukkan NIM mahasiswa. Program akan memperbarui data yang ada.
- Hapus Data
  Pengguna dapat menghapus data mahasiswa berdasarkan NIM.
- Tampilkan Data
  Program akan menampilkan seluruh data mahasiswa dalam format tabel yang rapi.
- Cari Data
  Pengguna dapat mencari data mahasiswa berdasarkan NIM.
- Keluar
  Program akan keluar dari aplikasi.

Cara Menjalankan Program
- Pastikan Anda memiliki Python versi 3.6 atau yang lebih baru.
- Salin kode program ke file Python (misalnya program_mahasiswa.py).
- Jalankan program menggunakan perintah:
  python program_mahasiswa.py
- Ikuti instruksi menu yang muncul di layar.

Alur Program
- Program dimulai dengan menampilkan menu utama.
- Pengguna memilih opsi dari menu utama (Tambah, Ubah, Hapus, Tampilkan, Cari, atau Keluar).
- Program menjalankan fungsi yang sesuai dengan pilihan pengguna.
- Jika pengguna memilih Keluar, program akan berhenti.

Struktur Data
Data mahasiswa disimpan dalam dictionary dengan format berikut:
{
    "NIM": {
        "nama": "Nama Mahasiswa",
        "tugas": nilai_tugas,
        "uts": nilai_uts,
        "uas": nilai_uas,
        "akhir": nilai_akhir
    }
}

