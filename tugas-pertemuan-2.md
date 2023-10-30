# _POSTGRESQL_ 
## Membuat Tabel Mahasiswa 
### Langkah-Langkah
1. Membuka SQL Shell pada Windows
2. Masukkan Password user untuk masuk ke terminal SQL-nya
3. Kemudian buat database dengan perintah `CREATE DATABASE polban;`
4. Gunakan perintah `\c` untuk terhubung dengan database yang sudah dibuat
5. Untuk membuat tabel, gunakan perintah `CREATE TABLE Mahasiswa (nim integer, nama varchar(28),gender varchar(28), alamat varchar(28), kota_asal varchar(28), tanggal_lahir DATE, tahun_masuk integer, nomor_handphone varchar(28)); `
6. Untuk memasukan data ke dalam tabel, gunakan perintah `insert into Mahasiswa (nim,nama,gender,alamat,kota_asal,tanggal_lahir,tahun_masuk,nomor_handphone) values (221331037, 'DAVA', 'L', 'Ngamprah', 'Bandung', '2004-05-04', 2022, '087776561658');`
7. Untuk melihat tabel yang sudah dibuat gunakan perintah `select * from Mahasiswa;`

### Output Tabel Mahasiswa
![image](https://github.com/dvaikhsn/pertemuan2-basis-data/assets/148309065/ac9fb687-8332-4a7f-baff-1204a85ded89)
![image](https://github.com/dvaikhsn/pertemuan2-basis-data/assets/148309065/76c42b3e-9645-4e86-a340-7c25c4e8b0dd)

### Command yang digunakan
* `CREATE DATABASE namadatabase;`
>berfungsi untuk membuat database
* `CREATE TABLE namatabel ( namacolumn TIPEDATA);`
>berfungsi untuk membuat tabel
* `INSERT INTO namatabel (namacolumn) VALUES (inputdata);`
>berfungsi untuk menginputkan data ke dalam tabel
* `ALTER TABLE namatabel ACTION;`
>syntax untuk memodifikasi tabel
* `ALTER TABLE namatabel ADD COLUMN namacoloumnbaru TIPEDATA;`
>berfungsi untuk menambah kolom baru pada tabel
* `ALTER TABLE namatabel RENAME COLOUMN namacoloumn TO namacolumnbaru;`
>berfungsi untuk merubah nama kolom pada tabel
* `UPDATE namatabel SET namakolom_yang_ingin_diupdate = value WHERE kondisikolom;`
>berfungsi untuk mengupdate/memperbaharui data pada tabel
* `DELETE FROM namatabel WHERE kondisikolom;`
>berfungsi untuk menghapus data pada tabel
* `DROP TABLE namatabel;`
>berfungsi untuk menghapus tabel beserta data pada tabel
* `SELECT * FROM namatabel ORDER BY namakolom ASC;`
>berfungsi untuk mengurutkan data tabel dari yang terkecil (asc(ASCENDING))
* `SELECT * FROM namatabel ORDER BY namakolom DESC;`
>berfungsi untuk mengurutkan data tabel dari yang terbesar (desc(DESCENDING))
* `\! cls`
>berfungsi untuk menghapus apapun yang ada di teriminal

===================================================================================

> [!NOTE]
> Masih banyak command yang digunakan pada PostgreSQL ini. Command di atas merupakan command yang saya gunakan
