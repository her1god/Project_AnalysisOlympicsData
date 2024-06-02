# Analisis Data Olimpiade

Ini adalah analisis data Olimpiade dari Athena 1896 hingga Rio 2016. Data ini mencakup informasi tentang atlet, tim, dan hasil Olimpiade selama periode tersebut.

## Struktur Data

Data tersedia dalam format tabel dengan kolom-kolom berikut:

- **id**: Nomor unik untuk setiap atlet
- **name**: Nama atlet
- **sex**: Jenis kelamin atlet (M atau F)
- **age**: Usia atlet
- **height**: Tinggi atlet dalam sentimeter
- **weight**: Berat atlet dalam kilogram
- **team**: Nama tim
- **noc**: Komite Olimpiade Nasional (3 huruf)
- **games**: Tahun dan musim Olimpiade
- **year**: Tahun Olimpiade (bilangan bulat)
- **season**: Musim Olimpiade (musim panas atau musim dingin)
- **city**: Kota tuan rumah Olimpiade
- **sport**: Cabang olahraga
- **event**: Acara olahraga
- **medal**: Medal yang diperoleh atlet (Emas, Perak, Perunggu, atau NA)

## Penanganan Data Kosong

Data yang memiliki nilai kosong pada kolom `medal`, `age`, `height`, dan `weight` telah ditangani sebagai berikut:
- **medal**: Nilai kosong diisi dengan "belum_punya_medal".
- **age, height, weight**: Nilai kosong diisi dengan nilai mean dari kolom yang bersangkutan.

## Kontribusi Saya

### Penemuan
1. **Belanda Memenangkan Jumlah Medali Terbanyak pada Tahun Berapa**: Belanda memenangkan jumlah medali terbanyak pada tahun [tahun].
2. **Visualisasi Jumlah Atlet dan Medali untuk Setiap Negara dan Acara**: Visualisasi telah dibuat untuk menampilkan jumlah atlet dan jumlah medali untuk setiap negara dan acara.
3. **Median Tinggi Atlet Terhadap Memenangkan Medali per Cabang Olahraga**: Median tinggi atlet terhadap memenangkan medali telah dianalisis untuk setiap cabang olahraga.
4. **Statistik Fisik Antara Tim Bola Basket Argentina dan Amerika pada Tahun 2004**: Statistik fisik, termasuk tinggi dan berat badan, dibandingkan antara tim bola basket Argentina dan Amerika pada tahun 2004.
5. **Visualisasi Perbedaan Tinggi Wanita dan Pria di Olimpiade**: Visualisasi dibuat untuk menampilkan perbedaan tinggi antara wanita dan pria di Olimpiade.

### Kontribusi
Silakan buka *Issues* untuk memberikan masukan, laporan bug, atau permintaan fitur.

## Lisensi

Diberikan dalam berkas [LICENSE](LICENSE).
