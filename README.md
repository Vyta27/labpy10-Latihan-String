# LATIHAN 1

    txt = 'Hello World'
  
• Hitung jumlah karakternya

• Ambil karakter terakhir

• Ambil karakter index ke-2 sampai index ke-4 (llo)

• Hilangkan spasi pada text tersebut (HelloWorld)

• Ubah text menjadi huruf besar

• Ubah text menjadi huruf kecil

• Ganti karakter H dengan karakter J

![Screenshot 2025-01-11 215310](https://github.com/user-attachments/assets/d5c13b0c-c4e7-4d16-8611-6b5d91b3872c)
![Screenshot 2025-01-11 215323](https://github.com/user-attachments/assets/7c4061c3-8076-4f1f-8965-cdd69043ff4a)

# LATIHAN 2
• Lengkapi kode berikut:

    umur = 24
    txt = 'Hello, nama saya john, dan umur saya adalah
    ... tahun'

    print(txt.format(umur))

![Screenshot 2025-01-11 222251](https://github.com/user-attachments/assets/b665f9c5-6758-4f0c-92f0-d4426994bc1f)
![Screenshot 2025-01-11 222257](https://github.com/user-attachments/assets/f95727bd-6c24-4710-abe1-b7dadda3ee41)

# STUDI KASUS : Validasi Form Input
Sebuah aplikasi pendaftaran online memerlukan validasi input. Anda
diminta membuat program untuk memvalidasi data berikut:

• Nama lengkap (harus hanya berisi huruf).

• Nomor telepon (harus hanya berisi angka).

• Email (harus mengandung karakter @ dan . ).

• Jika semua validasi berhasil, tampilkan pesan: Data pendaftaran
valid. Jika tidak, tampilkan pesan error untuk setiap kesalahan.

![Screenshot 2025-01-11 222019](https://github.com/user-attachments/assets/87e16306-bfb8-473d-b1b1-c89bd324e00d)

1.  Fungsi     validate_form()
   
Fungsi ini menerima tiga parameter:

- nama: Nama lengkap yang harus berisi hanya huruf.

- nomor_telepon: Nomor telepon yang harus berisi hanya angka.

- email: Alamat email yang harus mengandung karakter @ dan ..

a.     errors = []

- List kosong yang akan menyimpan pesan kesalahan validasi.
