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

* Sesuai *flowchart* yang saya buat, client/user diminta untuk memasukan nilai inputan berupa angka dan akan disimpan kedalam variable xangka1, xangka2, dan xangka3. <br> 
Setelah proses input nilai selesai maka saya akan membuat pemilihan angka terbesar berdasarkan kondisi.<br>
<br> Pada kondisi pertama saya akan melakukan pengecekan terhadap Angka pertama (xangka1) terlebih dahulu, yaitu dengan syntax/source code seperti dibawah ini :<br>
``` python
if (xangka1 > xangka2) and (xangka1 > xangka3):
```
Pada syntax diatas dijelaskan bahwa terdapat dua pengecekan, yaitu :<br>
   1. *(xangka1 > xangka2)* -> Apakah Angka pertama lebih besar dari Angka kedua **dan**
   2. *(xangka1 > xangka3)* -> Apakah Angka pertama lebih besar dari Angka ketiga.

