# labspy02
PyCharm adalah lingkungan pengembangan terintegrasi (IDE) yang digunakan dalam pemrograman komputer , khusus untuk bahasa Python . Ini dikembangkan oleh perusahaan Ceko JetBrains . Ini menyediakan analisis kode, debugger grafis, unit tester terintegrasi, integrasi dengan sistem kontrol versi (VCSes), dan mendukung pengembangan web dengan Django serta Ilmu Data dengan Anaconda .
PyCharm adalah cross-platform , dengan versi Windows , macOS dan Linux . Edisi Komunitas dirilis di bawah Lisensi Apache , dan ada juga Edisi Profesional dengan fitur tambahan - dirilis di bawah lisensi eksklusif 
PyCharm menyediakan API sehingga pengembang dapat menulis plugin mereka sendiri untuk memperluas fitur PyCharm. Beberapa plugin dari JetBrains IDE lain juga berfungsi dengan PyCharm. Ada lebih dari 1000 plugin yang kompatibel dengan PyCharm.
Versi beta dirilis pada Juli 2010, dengan 1.0 tiba 3 bulan kemudian. Versi 2.0 dirilis pada 13 Desember 2011, versi 3.0 pada 24 September 2013, dan versi 4.0 pada 19 November 2014. [10]
Edisi Komunitas PyCharm, versi open source dari PyCharm, tersedia pada 22 Oktober 2013. 
PyCharm Professional Edition memiliki beberapa opsi lisensi, yang berbeda dalam fitur-fiturnya, [11] harga, dan ketentuan penggunaan
## Pengertian statement if python
  Pada dasarnya, kondisi If Else If adalah sebuah struktur logika program yang di dapat dengan cara menyambung beberapa kondisi If Else menjadi sebuah kesatuan.
  Jika kondisi pertama tidak terpenuhi atau bernilai False, maka kode program akan lanjut ke kondisi If di bawahnya. Jika ternyata tidak juga terpenuhi, akan lanjut lagi ke kondisi If di bawahnya, dst hingga blok Else terakhir atau terdapat kondisi If yang bernilai True.
 
## Kapan Percabangan di Gunakan?

nah sekarang muncul pertanyaan kapan percabangan itu digunakan?, percabangan digunakan saat terdapat suatu keputusan atau dihadapkan pada kondisi tertentu, disini percabangan akan mengevaluasi kondisi yang hasilnya True atau False, yang dimana jika Kondisinya True maka pernyataan(statement) dalam blok tersebut akan di eksekusi dan Jika hasilnya  False maka pernyataan(statement) dalam blok lain akan di eksekusi, dalam python ada 3 jenis pernyataan atau statement yang digunakan, berikut tabelnya.

![iftrue/false](https://github.com//labspy02/blob/master/python%203%20jenis.png)

ok sekarang kita mari kita bahas satu-satu

Struktur If
percabangan if digunakan saat terdapat satu keputusan, formatnya begini
 if statement:
    statement
contohnya kita buat program ulangan, disini programnya akan menentukan jika siswa denan nilai diatas 70 akan lulus, buat program dengan nama if.py lalu isi
 nilai = 75
if nilai > 70:
    print('siswa lulus')

 # yang pertama kita akan membuat contoh bilangan yang memasukin bilangan satu sampai tiga

  Bilangan1 = int(input("Masukkan Bilangan 1:"))
  Bilangan2 = int(input("Masukkan Bilangan 2:"))
  Bilangan3 = int(input("Masukkan Bilangan 3:"))
  
  # contoh
  
  ![Gitconfig](https://github.com/alviandwipramono/labspy02/blob/master/bilangan1.png)

 # Berikutnya kita juga bisa membuat kondisi if int
  -if int(Bilangan1) and (Bilangan1 > Bilangan3): seperti dibawah ini :
 print("Nilai terbesarnya adalah :", Bilangan1)
 
 # contoh
 
 ![iftrue/false](https://github.com/alviandwipramono/labspy02/blob/master/bilangan2.png)
 
    Terbesar = Bilangan1
    NomBil = "Bilangan 1"

 # Selanjutnya kita juga bisa membuat kondisi elif yaitu:
   -Elife(Bilangan2 > Bilangan3) and (Bilangan2 > Bilangan1): Seperti dibawah ini:
   
  # contoh
  
  ![iftrue/false](https://github.com/alviandwipramono/labspy02/blob/master/bilangan3.png)
  
    Terbesar = Bilangan2
    NomBil = "Bilangan 2"

  else:
  
    Terbesar = Bilangan3
    NomBil = "Bilangan 3"
    
   # contoh
   ![iftrue/false](https://github.com/alviandwipramono/labspy02/blob/master/bilangan4.png)
    
    
 # Selanjutnya menggunakan bilangan besar adalah
  print("Bilangan yang terbesar adalah", NomBil, "dengan nilai", Terbesar)
  
  # contoh
  
  ![iftrue/false](https://github.com/alviandwipramono/labspy02/blob/master/print%20bilangan%20terbesar.png)
 
# Selanjutnya kita mengetahui setelah RUN yang benar:
![iftrue/false](https://github.com/alviandwipramono/labspy02/blob/master/Untitled.png)

# Selanjutnya kita mengetahui setelah RUN yang salah:
![iftrue/false](https://github.com/alviandwipramono/labspy02/blob/master/Capture.PNG)

    Pada if segment diatas memiliki ketentuan nilai if pertama harus bernilai true barulah nilai if yang berikutnya yang akan di proses atau dieksekusi, namun jika nilai if pertama bernilai false maka nilai if yang berikutnya tidak akan di proses, namun jika nilai if yang pertama bernilai true sedangkan nilai if yang kedua bernilai false maka yang akan di proses hanyalah if yang pertama.
    
   Berikut hasilnya jika if segment yang kita masukan bernilai true:
    
![iftrue/false](https://github.com/alviandwipramono/labspy02/blob/master/step.png)

  selanjutnya kita juga bisa menambahkan is dan is not pada if segment seperti dibawah ini :

  Pada Bahasa pemrograman python untuk membuat sebuah kondisi sama halnya dengan Bahasa pemgraman yang lain yaitu sama-sama menggunakan if, pada setiap pemrograman if berisi sebuah ekspresi logika menggunakan sebuah data yang telah dibandingkan seperti alur flowchart dibawah ini.
# Contoh
![Gitconfig](https://github.com/alviandwipramono/labspy02/blob/master/flowchart2.png)
