![cerud-java](https://user-images.githubusercontent.com/59429191/183224563-e8f30546-cf6d-48d1-a968-eb405e4bf812.png)

Langkah-Langkah Pembuatan Aplikasi

1. Apache dan Mysql di **XAMPP** sudah di **Start**
2. Pastikan Apache Netbeans + Java Development Kit (JDK) sudah diinstal dan berjalan dengan baik
3. Unduh library tambahan:
    
    [mysql-connector-java-5.1.49.tar.gz](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a9479400-5368-44d1-bdad-2cc3a153f239/mysql-connector-java-5.1.49.tar.gz)
    
    [rs2xml.zip](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c609e515-6c0a-4789-a53b-4fd4ab33a0ec/rs2xml.zip)
    
4. Buat Database
Nama Database: crud_java
Nama Tabel: siswa
![cerud-java-db](https://user-images.githubusercontent.com/59429191/183224657-c339680e-c774-4caf-b29a-91ae88607dff.png)

5. Membuat Project Baru di Netbeans
- Pilih Java with Ant lalu pilih Java Application kemudian klik Next
- Kemudian masukan nama projectnya BelajarCRUD lalu klik Finish

6.Membuat Java Application
- Klik kanan pada package belajarcrud > New > JFrame Form
- Masukan Class Name: FormSiswa lalu klik Finish

7. Buat form dengan cara drag and drop component atau pallete

8. Mengganti Nama Variabel Tiap Tombol
- Simpan : btnSimpan
- Edit : btnEdit
- Hapus : btnHapus
- Reset : btnReset
- Keluar : btnKeluar

9. Setting Library MYSQL JDBC Connector dan rs2xml 
- Pilih Menu Tools > Libraries
- Klik New Library lalu masukan Mysql JDBC Connection

10. Koding
- Memanggil Library: Mengimport atau memanggil libarary yang sudah kita add tadi taruh bawah script package belajarcrud;
- Membuat Statement Variable, taruh script dibawah Class Utamanya → public class FormSiswa extends javax.swing.JFrame{
- Membuat class koneksi, taruh script dibawah Class Utamanya → public class FormSiswa extends javax.swing.JFrame {
- Membuat class display, taruh script dibawah Class Utamanya → public class FormSiswa extends javax.swing.JFrame {
- Membuat class reset, taruh script dibawah Class Utamanya → public class FormSiswa extends javax.swing.JFrame {
- Memangil fungsi yang sudah dibuat sesuai nomor 11, 12 ke dalam class FormSiswa
- Membuat fungsi Tambah Data: Klik kanan pada tombol simpan – pilih event – Action – ActionPerformed.
- Membuat fungsi Menampilkan Data untuk diedit: Klik kanan pada tabel – pilih event – Action – ActionPerformed.
- Membuat fungsi Edit Data: Klik kanan pada tombel edit – pilih event – Action – ActionPerformed.
- Membuat fungsi Hapus Data: Klik kanan pada tombel hapus – pilih event – Action – ActionPerformed.
- Membuat fungsi Reset: Klik kanan pada tombel reset – pilih event – Action – ActionPerformed.
- Membuat fungsi Keluar: Klik kanan pada tombel keluar – pilih event – Action – ActionPerformed.

11. Jalankan Program
