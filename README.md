#  Praktikum 10
#  Nama : Zacky Rafian Fawwauzy
#  Nim : 312210344
#  Kelas: TI.22.A3

###  Latihan 1
![ gambar ](https://user-images.githubusercontent.com/115517181/212907829-eee1256b-4119-403b-be52-6d0677092e49.png)


####  Penjelasan Latihan 1
* Untuk menghitung jumlah karakter, gunakan fungsi `len()` .
python
#  Menghitung jumlah karakternya
cetak(len(txt))


* Cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku `[ ]` dan deklarasi nomor di dalam kurung siku dengan urutan *ARRAY* dan menggunakan titik dua lalu masukan nomor *ARRAY* selanjutnya.
* Untuk mengambil karakter terakhir, gunakan *index [-1]. Sedangkan untuk mengambil karakter *index ke-2 sampai ke-4, gunakan * index [2:5]* .
python
#  Mengambil karakter terakhir
cetak(txt[-1])
#  Mengambil indeks karakter ke-2 sampai indeks ke-4 (llo)
cetak(txt[2:5])


* Jika ingin menghilangkan spasi pada string, gunakan method `replace()` . Method *replace()* mengganti semua kemunculan string lama dengan yang baru atau paling banyak kemunculannya.
* Di dalam method *replace* , kita dapat menggunakan 2 cara, yang pertama bisa menggunakan `(txt.replace(" ", ""))` dan kedua dengan cara `(txt.replace(txt[5], "") )` .
python
#  Menghilangkan spasi pada text tersebut (HelloWorld)
cetak(txt.ganti(" ", ""))


* Untuk mengubah huruf menjadi besar, gunakan method `upper()` . Sedangkan jika ingin mengubah huruf menjadi kecil, gunakan method `lower()` .
python
#  Mengubah teks menjadi huruf besar
cetak(txt.atas())
#  Mengubah teks menjadi huruf kecil
cetak(txt.lower())


* Untuk mengganti karakter `'H'` dengan karakter `'J'` , gunakan method `replace()` .
python
#  Mengganti karakter H dengan karakter J
cetak(txt.replace("H", "J"))
mencetak()


####  Keluaran Latihan 1
![ Tangkapan layar (185) ](https://user-images.githubusercontent.com/115517181/212908778-e5216f2d-e4b2-4a8a-981f-7d3a836419f5.png)



###  Latihan 2
![ gambar ](https://user-images.githubusercontent.com/115517181/212907978-db76ae3f-944e-486b-8433-2e2eb6dd358e.png)

####  Penjelasan Latihan 2
Untuk memasukkan variabel ke dalam string, tambahkan kurung kurawal `{}` untuk menempatkan variabel sebelumnya.
python
umur = 24
txt = " \n Halo, nama saya john, dan umur saya {0} tahun \n "

print(txt.format(umur))


####  Keluaran Latihan 2
![ Tangkapan layar (186) ](https://user-images.githubusercontent.com/115517181/212908908-2f5574b3-6b42-4d6c-be92-a0261897288f.png)
