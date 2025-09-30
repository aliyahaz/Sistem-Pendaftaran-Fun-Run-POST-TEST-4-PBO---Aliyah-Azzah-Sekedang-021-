<img width="1200" height="400" alt="Run with Jazz Party (1200 x 400 px) (1)" src="https://github.com/user-attachments/assets/453cdeb0-7afe-47f1-8cf1-2c421b367e08" />

# SISTEM PENDAFTARAN PESERTA FUN RUN (EMINA)

Nama: Aliyah Azzah Sekedang

Kelas: A Sistem Informasi

NIM: 2409116021

## Deskripsi Program

Program Sistem Pendaftaran Peserta Fun Run adalah sebuah aplikasi sederhana berbasis Java yang dibuat menggunakan aplikasi NetBeans. Program ini bertujuan untuk membantu proses pencatatan dan pengelolaan data peserta lomba lari (fun run) secara digital agar lebih rapi dan efisien. Program ini dibuat menggunakan ArrayList untuk menyimpan data peserta, sehingga data dapat ditambahkan, ditampilkan, diperbarui, maupun dihapus dengan mudah. Seluruh fitur diatur melalui menu utama berbasis teks, di mana pengguna dapat memilih opsi sesuai kebutuhan.

## Menu Pendaftaran

Program ini menampilkan menu utama yang berisi deskripsi event fun run emina senidiri termasuk keterangan tempat dan waktu, lalu penerapan CRUD, yaitu tambah peserta, lihat peserta, edit data peserta, hapus data peserta, cari peserta dan keluar.

<img width="526" height="360" alt="image" src="https://github.com/user-attachments/assets/74433489-9d81-4d29-a43c-dd21b3d5250e" />


## 1. Opsi Tambah Peserta

Dalam opsi tambah peserta, pengguna dapat memasukkan nama lengkap peserta, nomor telepon, serta email. 

<img width="506" height="289" alt="image" src="https://github.com/user-attachments/assets/bd8c98b7-70be-40e2-a484-72180a704a88" />

Setelah memasukkan data, program akan lanjut menampilkan opsi pilih paket fun run dengan nama paket, barang yang akan didapatkan, dan harga paket.

<img width="761" height="110" alt="image" src="https://github.com/user-attachments/assets/5383362f-bd51-4055-8193-ab1a2a27b88e" />

Dilanjutkan kembali dengan metode pembayaran yaitu transfer bank ataupun e-wallet.


<img width="599" height="134" alt="image" src="https://github.com/user-attachments/assets/de0b5047-4b6f-4724-b5e0-2f5767261999" />

Setelah memasukkan angka sesuai opsi pembayaran yang diinginkan, program menampilkan pesan "Peserta berhasil terdaftar. See you!", dan kembali ke menu utama.

## 2. Opsi Lihat Daftar Peserta

Setelah pengisian data peserta, data dapat dilihat melalui opsi 2 yaitu lihat peserta. Maka, program akan menampilkan data seluruh peserta yang telah terdaftar.

<img width="787" height="401" alt="image" src="https://github.com/user-attachments/assets/5791c4e4-608b-46f3-a4a4-95e0f9686e16" />


## 3. Opsi Edit Data Peserta

Ketika pengguna ingin mengubah atau mengedit nama, nomor telepon, maupun email sekiranya ada salah pengisian dengan memasukkan nama peserta sesuai data yang telah terdaftar dan tercatat, dapat dikosongkan salah satunya apabila hanya ingin mengisi salah satu saja.

<img width="773" height="551" alt="image" src="https://github.com/user-attachments/assets/30c1b3df-a229-439e-ae8d-1d6e7ad98e30" />


Disini saya hanya mengganti 2 angka terakhir dalam nomor telepon peserta bernama Afif. Untuk melihat daftar peserta yang telah diperbarui dapat memasukkan opsi 2 lihat peserta kembali.

<img width="774" height="391" alt="image" src="https://github.com/user-attachments/assets/26b8fffc-2a9b-4afc-ba54-644f3935a2dd" />


## 4. Opsi Hapus Data Peserta

Data peserta juga dapat dihapus hanya dengan memasukkan nama peserta sesuai dengan daftar peserta.

<img width="768" height="435" alt="image" src="https://github.com/user-attachments/assets/da25190b-4568-4ff3-8a91-aa4ddba03397" />

Dapat terlihat data peserta Aliyah telah terhapus.

<img width="764" height="232" alt="image" src="https://github.com/user-attachments/assets/8255a6b1-cc43-4213-876d-319fded6bb68" />


## 5. Opsi Cari Peserta

Data peserta dapat dicari dengan memasukkan nama peserta yang ingin dicari. Lalu, nanti program akan menampilkan data peserta tersebut.

<img width="768" height="206" alt="image" src="https://github.com/user-attachments/assets/940a1c9a-e3e9-49b9-b5c3-cb4e601e7ff4" />

Kalau nama yang dicari tidak terdaftar program akan menampilkan pesan "Pengguna tidak ditemukan.".

<img width="479" height="77" alt="image" src="https://github.com/user-attachments/assets/5d5b7816-a1c0-4882-98d3-b5c477373663" />

## 6. Opsi Keluar

Setelah selesai melakukan pendaftaran, peserta dapat langsung keluar dari program dengan memasukkan angka 6. Maka, pengguna akan keluar dari program.

<img width="556" height="75" alt="image" src="https://github.com/user-attachments/assets/b33234e4-fbe9-4c87-b334-028dd7f64b11" />

## Penjelasan letak penerapan Abstraction 

- Penerapan abstraction pada class Person

  <img width="649" height="413" alt="image" src="https://github.com/user-attachments/assets/c4b89f2c-1b45-4344-9e0b-e3379734eb16" />

Class Person dibuat abstrak sehingga tidak dapat dibuat objek secara langsung. Method info() bersifat abstract sehingga wajib diisi ulang oleh subclass (Peserta dan Panitia).

- Penerapan interface pada class Pembayaran

  <img width="335" height="90" alt="image" src="https://github.com/user-attachments/assets/2fa78c02-624c-4364-bb30-2a035558ce37" />

Interface Pembayaran digunakan sebagai kontrak. Setiap class yang mengimplementasikan interface ini harus membuat isi dari method metodePembayaran().

- Penerapan abstraction pada class Peserta (extends dan implements)
  
  <img width="1043" height="211" alt="image" src="https://github.com/user-attachments/assets/3f590ccc-ae2e-4a1c-9087-3824baa6f44d" />

Class Peserta adalah contoh abstraksi karena mewarisi class Person dan juga mengimplementasikan interface Pembayaran.
  
## Penjelasan letak penerapan Polymorphism (Overloading & Overriding).

- Penerapan overloading pada class Peserta

  <img width="1069" height="394" alt="image" src="https://github.com/user-attachments/assets/09299012-22bc-46b3-be4a-0213bfc854c9" />

Method info() dibuat dalam dua versi: tanpa parameter dan dengan parameter boolean. Ini disebut overloading, karena method bisa dipanggil dengan cara berbeda untuk menampilkan data lengkap atau lebih ringkas.

- Penerapan overriding pada class Peserta

  <img width="1068" height="183" alt="image" src="https://github.com/user-attachments/assets/71091f34-f74b-4de0-abdc-391e5f7c3995" />

Method info() di class Peserta menimpa method info() dari class Person dengan isi yang berbeda.

- Penerapan overriding pada class Panitia
  
  <img width="697" height="203" alt="image" src="https://github.com/user-attachments/assets/8ae26398-839c-4ef0-aedd-34801d8b789f" />

Method info() di class Panitia juga menimpa method info() dari class Person, tetapi hasil tampilannya berbeda dengan Peserta.
