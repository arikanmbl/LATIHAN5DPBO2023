# LATIHAN5DPBO2023

Saya Ayurika Sinambela 2003717 mengerjakan Latihan 5 dalam mata kuliah DPBO untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Amin.

## Desain
Program ini terdiri dari dua class, yaitu kelas Menu dan class Mahasiswa
- Kelas Menu
Kelas Menu berfungsi untuk menampilkan pilihan menu dan menerima input dari user untuk memilih aksi yang ingin dilakukan pada data mahasiswa. Terdapat metode-metode seperti menampilkan daftar mahasiswa, menambah data mahasiswa baru, mengubah data mahasiswa, menghapus data mahasiswa, dan reset form. Kelas ini juga berisi method untuk memproses input dari user dan memanggil method-method dari kelas Mahasiswa untuk melakukan operasi pada data mahasiswa.
- Kelas Mahasiswa
Kelas Mahasiswa berfungsi untuk merepresentasikan data mahasiswa yang terdiri dari NIM, Nama, Nilai, dan Gender. Kelas ini berisi konstruktor dan getter/setter method untuk mengakses dan mengubah nilai dari atribut-atribut yang ada pada kelas Mahasiswa.

## Alur Program
Program ini memiliki alur sebagai berikut:
1. Pengguna akan dihadapkan dengan form input yang mana ketika form tersebut diisi maka terdapat pilihan untuk menambahkan data dengan menekan button "Add" atau me-reset form dengan menekan button "Cancel". Selain itu juga ditampilkan tabel yang berisi data Mahasiswa.
2. Isi tabel akan bertambah jika ada data yang ditambahkan oleh pengguna (jika pengguna menekan tombol "Add" setelah mengisi form). Jika ada field yang tidak terisi atau tidak lengkap, maka akan muncul pop up peringatan dan data belum bisa ditambahkan.
3. Jika pengguna menekan button "Cancel", maka semua data yang sudah diinput ke dalam form akan terhapus.
4. Untuk meng-update data Mahasiswa, pengguna dapat mengklik kolom data Mahasiswa yang akan diubah, maka semua data yang terdapat dalam kolom tersebut akan memenuhi form secara otomatis. Button "Add" juga akan berubah menjadi button "Update" serta akan muncul button "Delete".
5. Pengguna bisa mengubah data dengan mengubah data pada field data yang ingin diubah lalu menekan button "Update". Otomatis data pada tabel akan berubah/terupdate.
6. Jika pengguna ingin menghapus data mahasiswa, maka pengguna dapat menekan button "Delete", setelah itu akan muncul pop up konfirmasi, jika pengguna memilih "Yes" maka data akan terhapus, jika memilih "No" atau menutup pop up, maka tidak terjadi apapun.

## Dokumentasi
### Tampilan awal
![1](https://user-images.githubusercontent.com/71563980/226943838-8225a430-9ddc-40a2-937b-6be6d4286162.png)
### Create data
Mengisi form
![2](https://user-images.githubusercontent.com/71563980/226944245-8ccc63df-da62-402e-b34e-e55ed21bcdd4.png)

Confirmation message saat data berhasil ditambahkan
![3](https://user-images.githubusercontent.com/71563980/226944672-6ebbdabf-03ef-4d5e-9019-410ae3c11ecd.png)

Jika ada field yang belum terisi
![8](https://user-images.githubusercontent.com/71563980/226946734-73c8d42e-d46a-4240-9b23-6a403d8d5cdd.png)
![9](https://user-images.githubusercontent.com/71563980/226946748-f6e48b69-6773-4cbb-b2fe-4a592e662c59.png)
### Update data
Memilih data yang ingin diubah. Otomatis form akan terisi data sebelumnya dan pengguna bisa mengubahnya di field yang diinginkan.
![4](https://user-images.githubusercontent.com/71563980/226944850-71703b81-ca17-421e-88cc-117945cd7007.png)

Confirmation message saat data berhasil diubah
![5](https://user-images.githubusercontent.com/71563980/226945104-d024d55f-038f-4e22-a777-8c121fea482d.png)
### Delete data
Memilih data yang ingin dihapus dan menekan button "Delete", muncul confirmation message apakah benar ingin menghapus data atau tidak
![6](https://user-images.githubusercontent.com/71563980/226945855-3fe3b669-d97d-4e7a-8bcf-b5df3c83b1dd.png)

Confirmation message saat data berhasil dihapus
![7](https://user-images.githubusercontent.com/71563980/226946074-d67e7532-4a37-4b39-b9e2-7819648590f0.png)
