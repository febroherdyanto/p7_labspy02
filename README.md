# Pertemuan 7 - labspy02
Repository ini dibuat untuk memenuhi tugas Pertemuan 7 Bahasa Pemrograman (Modul Praktikum 2) - Teknik Informatika<br><br>
Nama : Febro Herdyanto<br>
NIM : 312010043<br>
Kelas : TI.20.B.1<br>
<hr>


### Menentukan Bilangan Terbesar dari 3 Nilai yang diinputkan

<br>
Pada Pertemuan ke-7 ini saya mendapat tugas dari Dosen Bahasa Pemrograman Teknik Infomratika - Universitas Pelita Bangsa yaitu Bapak. Agung Nugroho,S.Kom.,M.Kom. untuk membuat Aplikasi yang menentukan bilangaan terbesar dari tiga nilai yang client/user inputkan menggunakan Bahasa Pemrograman Python.<br><br>


Pada repository ini saya akan menjelaskan alur dalam *Flowchart* yang telah saya buat. File *Flowchat* bisa dilihat pada link berikut ini : [Flowchart Tugas Pertemuan 7 - Menentukan Bilangan Terbesar dari 3 Nilai yang diinputkan](Flowchart_Febro_Herdyanto_312010043.pdf) 
<br><br> 
Berikut source code yang saya tulis untuk menjadikan aplikasi tersebut.

``` python
print("Masukkan Pilihan Angka ke-1 : ")
xangka1 = int(input())
print("Masukkan Pilihan Angka ke-2 : ")
xangka2 = int(input())
print("Masukkan Pilihan Angka ke-3 : ")
xangka3 = int(input())

if (xangka1 > xangka2) and (xangka1 > xangka3):
    print(f"Bilangan Pertama ({xangka1}) lebih besar dari Bilangan kedua dan ketiga")
elif (xangka2 > xangka1) and (xangka2 > xangka3):
    print(f"Bilangan kedua ({xangka2}) lebih besar dari Bilangan pertama dan ketiga")
elif (xangka1 == xangka2) and (xangka1 == xangka3) and (xangka2 == xangka3):
    print("Bilangan yang dimasukkan sama besar")
else:
    print(f"Bilangan ketiga ({xangka3}) lebih besar dari Bilangan pertama dan kedua")
```

Saya tidak akan menjelaskan fungsi input dan print, karena sudah pernah saya jelaskan pada repository sebelumnya.<br>
Saya akan menjelaskan langkah-langkah nya :<br>

* Langkah pertama yaitu saya akan membuat sebuah inputan tersebut untuk menentukan angka terbesar. Yaitu dengan mengetikkan perintah / syntax berikut :<br>
``` python
print("Masukkan Pilihan Angka ke-1 : ")
xangka1 = int(input())
print("Masukkan Pilihan Angka ke-2 : ")
xangka2 = int(input())
print("Masukkan Pilihan Angka ke-3 : ")
xangka3 = int(input())
```
<br>
* Langkah kedua yaitu saatnya menentukan logika untuk menemukan bilangan terbesar dari angka yang saya inputkan diatas.<br>
Dengan menjelaskan fungsi-fungsi pada source code yang digunakan diatas :<br>

``` python
if (xangka1 > xangka2) and (xangka1 > xangka3):
```
<br>
Syntax diatas berfungsi untuk melakukan pengecekan inputan pada **Angka ke-1**, yaitu dengan penggunaan **if**. <br>
Pada syntax diatas melakukan pengecekan dengan 2 perbandingan angka terbesar yaitu *Apakah Angka ke-1 lebih besar dari Angka ke-2* dan *Apakah Angka ke-1 lebih besar dari Angka ke-3*. Dan mmenggunakan perintah **AND**<br>

* Setelah melakukan pengecekan apakah Angka-1 sebegai bilangan terbesar atau tidak, kita akan menampi


