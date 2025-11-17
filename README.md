# Laporan Jarkom Modul 4 Kelompok K-36

## Anggota

| Nama | NRP|
|-------------------------------|---------------|
| Ahmad Wildan Fawwaz| 5027241001 |
| Muhammad Rakha Hananditya R.| 5027241015 |

## Asisten Penguji
| Nama | Kode Asisten |
|-----------------------|----|
| Adlya Isriena Aftarisya | P6 |

## Pendahuluan

بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيْمِ

<p align="justify">
&emsp; Segala puji syukur kita panjatkan atas kehadirat Allah Subḥānahu wa Ta‘ālā, karena berkat atas rahmat, karunia, dan nikmat-Nya praktikum modul 1 untuk mata kuliah Komunikasi Data dan Jaringan Komputer dapat diselesaikan dengan cukup. Tidak lupa shalawat serta salam semoga senantiasa tercurah kepada junjungan kita Nabi Muhammad Shallallāhu ‘alaihi wa Sallam, suri teladan terbaik bagi umat manusia, beserta keluarga, sahabat, dan para pengikutnya hingga akhir zaman.
</p>

<p align="justify">
&emsp; Laporan ini disusun sebagai suatu bentuk pertanggungjawaban akademik atas kegiatan praktikum yang telah dilaksanakan. Selain itu, laporan ini berfungsi sebagai dokumentasi resmi tertulis dari seluruh rangkaian kegiatan yang telah dilakukan, sehingga dapat menjadi acuan dalam evaluasi maupun penilaian praktikum.
</p>

Rasulullah Shallallāhu ‘alaihi wa Sallam pernah bersabda:

إِذَا مَاتَ ابْنُ آدَمَ انْقَطَعَ عَمَلُهُ إِلَّا مِنْ ثَلَاثٍ: صَدَقَةٍ جَارِيَةٍ، أَوْ عِلْمٍ يُنْتَفَعُ بِهِ، أَوْ وَلَدٍ صَالِحٍ يَدْعُو لَهُ


<em>Artinya</em>:
<p align="justify">
"Apabila anak Adam meninggal dunia, maka terputuslah amalnya kecuali tiga perkara: sedekah jariyah, ilmu yang bermanfaat, atau anak shalih yang mendoakannya." 
<br>
(HR. Muslim, no. 1631)
</p>
  
وَمَنْ سَلَكَ طَرِيقًا يَلْتَمِسُ فِيهِ عِلْمًا سَهَّلَ اللَّهُ لَهُ بِهِ طَرِيقًا إِلَى الْجَنَّةِ

<em>Artinya</em>:
<p align="justify">
"Barang siapa yang menempuh jalan untuk mencari ilmu, maka Allah akan mudahkan baginya jalan menuju surga." 
 <br>
(HR. Muslim, no. 2699)
</p>
  
<p align="justify">
&emsp; Maka dari itu, semoga apa yang tertulis pada laporan ini dapat menjadi ilmu yang bermanfaat, serta menjadi keberkahan dan amal yang diterima di sisi Allah Subḥānahu wa Ta‘ālā. Semoga bagi yang membaca ini, Allah memudahkan semua langkahnya dalam menuntut ilmu, mengamalkannya, serta menjaganya agar tidak sekadar menjadi hafalan, namun juga menjadi bekal yang membawanya ke surga.
</p>

Āmīn yā Rabbal ‘ālamīn.

## Daftar Isi

- [Anggota](#anggota)
- [Pendahuluan](#pendahuluan)
- [Daftar Isi](#daftar-isi)
- [Walkthrough](#walkthrough)

## Walkthrough

### • VLSM - CPT

Langkah2: <br>
<p align="justify">
&emsp; Langkah pertama adalah menyusun topologi jaringannya terlebih dahulu sesuai ketentuan soal.
</p>

<p align="center">
	<img src="Image-Jarkom-Modul-4/topo-modul4-cpt.png" alt="topo" width="80%" height="80%">  
</p>

<p align="justify">
&emsp; Menghitung total host terlebih dahulu, diperoleh ada 3219 host. Lalu mengurutkan/sort dari subnet yang memiliki host paling banyak sampai ke yang paling dikit.
</p>

<p align="center">
	<img src="Image-Jarkom-Modul-4/Screenshot (1102)1.png" alt="topo" width="80%" height="80%">  
</p>

<p align="justify">
&emsp; Membuat tabel nama subnet, rute, jumlah IP, dan netmask untuk memastikan IP yang digunakan secara maksimal dan menyesuaikan dengan netmasknya.
</p>

<p align="center">
	<img src="Image-Jarkom-Modul-4/Screenshot (1102)2.png" alt="topo" width="80%" height="80%">  
</p>

<p align="justify">
&emsp; Pembuatan tabel kedua yang berisi subnet, network ID, netmask, broadcast, range IP. Tujuannya sendiri untuk menghitung IP bersih yang dapat dipakai setelah dikurangi penggunaan oleh network ID dan broadcast dan mengetahui range IP yang available buat dipakai.
</p>

<p align="center">
	<img src="Image-Jarkom-Modul-4/Screenshot (1102)3.png" alt="topo" width="80%" height="80%">  
</p>

<p align="justify">
&emsp; Setelah perhitungan selesai, lalu implementasi yang ada dari tabel ke topologi di VLSM
</p>

<p align="center">
	<img src="Image-Jarkom-Modul-4/Screenshot (1101).png" alt="topo" width="80%" height="80%">  
</p>

### • CIDR - GNS3

#### - Topologi GNS3

<p align="center">
	<img src="Image-Jarkom-Modul-4/001.png" alt="Tolopogi" width="80%" height="80%">  
</p>

#### - Pemetaan Subnet Topologi

<p align="center">
	<img src="Image-Jarkom-Modul-4/002.png" alt="Sunbet" width="80%" height="80%">  
</p>

#### - Supernetting Series B

<p align="center">
	<img src="Image-Jarkom-Modul-4/003.png" alt="Sebies R" width="80%" height="80%">  
</p>

#### - Supernetting Series C

<p align="center">
	<img src="Image-Jarkom-Modul-4/004.png" alt="Ceries S" width="80%" height="80%">  
</p>

#### • Supernetting Series D

<p align="center">
	<img src="Image-Jarkom-Modul-4/005.png" alt="Serids E" width="80%" height="80%">  
</p>

#### - Supernetting Series E

<p align="center">
	<img src="Image-Jarkom-Modul-4/006.png" alt="Seriee S" width="80%" height="80%">  
</p>

#### - Supernetting Series F

<p align="center">
	<img src="Image-Jarkom-Modul-4/007.png" alt="Serfes I" width="80%" height="80%">  
</p>

#### - Supernetting Series G

<p align="center">
	<img src="Image-Jarkom-Modul-4/008.png" alt="Sgries E" width="80%" height="80%">  
</p>

#### - Supernetting Series H

<p align="center">
	<img src="Image-Jarkom-Modul-4/009.png" alt="H seireS" width="80%" height="80%">  
</p>

#### - Supernetting Series I

<p align="center">
	<img src="Image-Jarkom-Modul-4/010.png" alt="Ser I ieS" width="80%" height="80%">  
</p>

#### - Pembagian IP Supernet Topologi

<p align="center">
	<img src="Image-Jarkom-Modul-4/011.png" alt="Sunerpet" width="80%" height="80%">  
</p>

#### - Tree Pembagian Series I1

<p align="center">
	<img src="Image-Jarkom-Modul-4/012.png" alt="Tere Reseis I1" width="80%" height="80%">  
</p>

#### - Tree Pembagian Series F2

<p align="center">
	<img src="Image-Jarkom-Modul-4/013.png" alt="Teer Seiers F2" width="80%" height="80%">  
</p>

