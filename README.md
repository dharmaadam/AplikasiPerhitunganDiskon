# Aplikasi Perhitungan Diskon

Aplikasi sederhana untuk menghitung harga akhir setelah diskon dan menunjukkan jumlah penghematan. Aplikasi ini dibangun menggunakan Java dan Swing dengan GUI yang mudah digunakan.

## Deskripsi Proyek
Aplikasi ini memungkinkan pengguna untuk:
- Memasukkan harga asli.
- Memilih persentase diskon yang akan diterapkan.
- Menghitung dan menampilkan harga akhir serta jumlah penghematan.

## Fitur
1. **Perhitungan Diskon**: Pengguna dapat menghitung harga akhir setelah diskon.
2. **Antarmuka Pengguna Grafis (GUI)**: Menggunakan `JFrame`, `JPanel`, `JLabel`, `JTextField`, `JComboBox`, dan `JButton`.
3. **Penanganan Kesalahan**: Menangani input yang tidak valid dari pengguna.
4. **Ekstensi (Pilihan)**: 
   - Menambahkan opsi untuk memasukkan kode kupon diskon tambahan.
   - Menggunakan `JSlider` sebagai alternatif `JComboBox` untuk memilih persentase diskon.
   - Menyediakan riwayat perhitungan diskon yang telah dilakukan.

## Instalasi dan Penggunaan
### Prasyarat
- Java Development Kit (JDK) terinstal.
- NetBeans IDE (atau IDE lain yang mendukung Java Swing).

### Cara Menjalankan Proyek
1. Buka NetBeans IDE dan pilih **File > Open Project**.
2. Pilih folder proyek `AplikasiPerhitunganDiskon`.
3. Buka file `NewJFrame.java` di dalam proyek.
4. Klik tombol **Run** untuk menjalankan aplikasi.

### Struktur Proyek
- **NewJFrame.java**: Kelas utama yang mengatur antarmuka pengguna dan logika perhitungan diskon.
- **Atribut Utama**:
  - `hargaAsliTextField`: Untuk memasukkan harga asli.
  - `comboBoxDiskon`: Untuk memilih persentase diskon.
  - `penghematanTextField`: Menampilkan jumlah penghematan.
  - `hargaAkhirTextField`: Menampilkan harga akhir setelah diskon.

## Logika Perhitungan
- **Jumlah Diskon**: `jumlahDiskon = hargaAsli * (persentaseDiskon / 100);`
- **Harga Akhir**: `hargaAkhir = hargaAsli - jumlahDiskon;`

## Kontribusi
Kontribusi sangat diharapkan! Silakan buat **Pull Request** atau **Issues** jika Anda ingin berkontribusi.

---
