Membuat Data Geospasial
1. Import shapefile
2. Masukan variable, misalkan variable a untuk shapefile.writer( )
a = shapefile.writer( )
Jadi, format membuat data geospasial ada 2, yaitu :
1. .shp => Salah satu bentuk file yang terletak dalam shapefile yang menyimpan data geometri.
a.point(x,y)
a.poly [(x,y),(v,w)]
2. .dbf =>  Sebuah file yang dapat menyimpan file tabular dan menyimpan data atribut.
a.field (‘name.field’,’c’,’40’)
a.record (‘pwt’)
Data geospasial tersebut disimpan menggunakan method a.save(‘file.shp’).
Arti dari method pada writer :
- Point (x,y)           : memasukkan data berbentuk paint ke dalam .shp dan seluruh data harus berformat ESRI.1
- Poly [(a,b),(c,d)]    : memasukkan data geospasial berbentuk polygon (kembali ke titik awal) atau polyline (tidak kembali ketitik awal).
- Field (‘nama’,’c’,’40’) : artinya membuat atribut polygon dengan table ‘nama’ dengan tipe data varchar dengan panjang 40. Method ini dapat diulang dan dapat dilakukan untuk krbuthan field baru lagi.
- Record(‘purwokerto’)      : Mengisi table yang hanya satu field dengan value ‘purwokerto’.

- Save (‘nama.file’)  : menyimpan file dengan save file.

KESIMPULAN
Data Geospasial dapat dibuat menggunakan shapefile pada python. Dengan begitu akan lebih memberikan kemudahan bagi pembuat memahami tentang data geospasial.


Nama : Herlin Restusari
   Kelas : D4 TI 3B
   NPM  : 1144008
