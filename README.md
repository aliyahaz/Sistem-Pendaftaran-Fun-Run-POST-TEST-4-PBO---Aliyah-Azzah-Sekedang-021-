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

## Penjelasan letak penerapan Abstraction (class/interface yang digunakan)

Penerapan abstraction terdapat pada class Peserta, Paket, PesertaService, dan PaketService. Class tersebut dibuat untuk memisahkan data dengan logika program. Misalnya, Peserta hanya berisi data peserta, sedangkan PesertaService berfungsi mengatur proses penambahan, pencarian, atau pengelolaan peserta. Dengan cara ini, detail cara kerja di dalam class tidak perlu diketahui oleh pengguna program.

<img width="1060" height="215" alt="image" src="https://github.com/user-attachments/assets/8e198707-b084-4872-a035-4dec56d71093" />


## Penjelasan letak penerapan Polymorphism (Overloading & Overriding).

Penerapan polymorphism terdapat pada overriding digunakan jika ada class turunan dari Peserta, misalnya PesertaVIP, yang menimpa method toString() agar tampilan data peserta berbeda dengan class induknya.

<img width="1079" height="195" alt="image" src="https://github.com/user-attachments/assets/934d4f61-cd8f-4593-8d7f-ac8870c53197" />

