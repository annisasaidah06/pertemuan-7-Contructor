# pertemuan-7-Contructor
## Profil
| Variable | Isi |
| -------- | --- |
| **Nama** | Annisa Saidah Mubarokah |
| **NIM** | 312310631 |
| **Kelas** | TI.23.A6 |
| **Mata Kuliah** | Pemrograman Orientasi objek |


## menampilkan program

    # Constructor dengan parameter
    def __init__(self, nama, jurusan, angkatan):
        self.nama = nama # Atribut nama
        self.jurusan = jurusan # Atribut jurusan
        self.angkatan = angkatan  # Atribut angkatan

    # Metode untuk menampilkan informasi mahasiswa
    def info(self):
        print(f"Nama: {self.nama}")
        print(f"Jurusan: {self.jurusan}")
        print(f"Angkatan: {self.angkatan}")

# Membuat objek dari kelas Mahasiswa
mahasiswa1 = Mahasiswa("Budi", "Teknik Informatika", 2022)

# Memanggil metode info untuk menampilkan informasi
mahasiswa1.info()

Penjelasan:

1. Constructor __init__: Pada contoh di atas, __init__ adalah constructor. Constructor ini memiliki parameter nama, jurusan, dan angkatan. Ketika objek mahasiswa1 dibuat, nilai nama, jurusan, dan angkatan dikirimkan ke constructor dan diinisialisasi ke atribut objek tersebut.


2. Atribut Objek (self.nama, self.jurusan, self.angkatan): Di dalam __init__, self digunakan untuk merujuk ke objek yang sedang dibuat. Misalnya, self.nama = nama akan menyimpan nilai nama pada atribut nama milik objek.


3. Membuat Objek: mahasiswa1 = Mahasiswa("Budi", "Teknik Informatika", 2022) membuat objek baru dari kelas Mahasiswa dengan nilai awal untuk atribut nama, jurusan, dan angkatan.


4. Memanggil Metode: mahasiswa1.info() memanggil metode info untuk
5.  informasi tentang mahasiswa tersebut.

   ##output
IMG_20241107_064125.jpg

   
