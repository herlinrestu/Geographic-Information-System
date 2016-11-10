
A. Latar Belakang

         Dalam Qgis menyediakan shp dan dbf file. Shp dan dbf file itu dapat dilihat dengn menggunakan python. atau software yang lainnya. Data Geospasial digunakan sebagai alat bantu untuk mengambil keputusan pelaksanaan kegiatan yang berhubungan dengan ruang bumi.


               Retrieve Data Geospasial dibagi menjadi 2 yaitu :

Dalam mengambil data vektor
- Shp : Data Geometri
-dbf   : Database Table

Operasi pemrogramann pengambilan dari geospasial
Menggunakan library pyshp
Panggil library di python menggunakan (import shape file)
Instansiasi kelas dengan constrack input file
Contoh :
sf : Shapefile.Reader('file.shp')

sf  = variable instansiasi
shapefile = class shapefile
reader = method dari kelas shape file
('file.shp') = parameter



Nama : Herlin Restusari
Kelas : D4 TI 3B
NPM  : 1144008