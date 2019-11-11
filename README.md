# labspy02
Apa itu PyCharm?
PyCharm adalah integrated Development Evironment (IDE) yang berfokus pada mengembangan project dengan bahasa pemograman python. PyCharm dikembangkan oleh JetBrains, Selain PyCharm, JetBrains juga mengembangkan banyak macam IDE lainya misalnya seperti PHPStrom untuk mengembangkan PHP, intelij IDEA untuk mengembangkan JAVA dan lain-lain.

iftrue/false

Pemrograman Python Menggunakan PyCharm
iftrue/false

PyCharm merupakan IDE terbaik untuk pemrograman python. PyCharm dibuat oleh JetBrains.

Ada dua versi PyCharm:

Versi Profesional (Trial 30 hari) – Memiliki fitur lebih banyak untuk pemrograman python dan web.
Versi Comunnity (Gratis dan opensource) – Fiturnya standar untuk pemrograman python.
Percabangan di Python terdapat 4 macam. Yang mana percabangan tersebut digunakan pada bahasa pemrograman python. berikut ini merupakan # macam-macam percabangan pada bahasa pemrograman python : IF Statement Fungsi IF pada python adalah untuk memberikan kondisi tertentu pada program supaya program bisa berjalan sesuai dengan kondisi tersebut. Fungsi yang dipakai adalah IF(jika). Dengan fungsi tersebut, kita dapat lebih leluasa dalam pemrograman python.

IF Statement IF - ELSE Statement IF - ELIF - ELSE Statement IF Bersarang(Nested IF)

macam-macam jenis percabangan. Berikut ini merupakan penjelasannya
IF Statement

Fungsi IF pada python adalah untuk memberikan kondisi tertentu pada program supaya program bisa berjalan sesuai dengan kondisi tersebut. Fungsi yang dipakai adalah IF(jika). Dengan fungsi tersebut, kita dapat lebih leluasa dalam pemrograman python.

 >>> nama = "python"          
 >>> if nama == "python" :          
 ...     print "Hello " + nama  
 ...   Hello python
IF - ELSE Statement Fungsi IF - ELSE pada python adalah untuk memberikan 2 kondisi yang mana kedua kondisi tersebut bersifat terbalik. artinya apabila kondisi pertama tidak memenuhi, maka akan muncul kondisi kedua(ELSE) secara otomatis.

Bentuk umum perintah if – else : if ( kondisi ) :
statemen 1
else :
statemen 2

  Contoh Program :           
         >>> kunci = "python"           
         >>> password = raw_input("Masukkan Password : ")
         Masukkan Password : saya           
         >>> if password == kunci:           
         ...     print "Password Benar"  
         ... else:          
         ...     print "Password Salah"  
         ...   
         Password Salah
IF - ELIF - ELSE Statement Jika sebelumnya hanya memiliki satu kondisi, disini ada tambahan Elif pada python. ELIF adalah perintah pada program python untuk menammbah kondisi. Dalam hal ini, kondisi pada ELIF bisa digunakan berkali - kali.

Bentuk umum perintah if – else – elif : if ( kondisi 1 ) :
statemen
elif ( kondisi 2 ) :
statemen
else:
statemen

               Contoh Program : 
               >>> angka = input("Masukkan sebuah bilangan : ")          
               Masukkan sebuah bilangan : 0           
               >>> if angka > 0 :           
               ...     print "Angka merupakan Bilangan Positif"          
               ... elif angka < 0 :           
               ...     print "Angka merupakan Bilangan Negatif"   
               ... else :           
               ...     print "Angka merupakan 0" 
               ...   Angka merupakan
IF Bersarang(Nested IF) IF Bersarang merupakan kondisi yang didalamnya terdapat kondisi lagi. Misalkan keputusan kita setelah SMA, ada dua pilihan. Yaitu Kuliah atau Kerja. Jika kita memilih kuliah, ada pilihan lagi didalamnya, yaitu daftar di kampus mana. dan seterusnya. Hal tersebut bisa kita bahasakan denga IF dalam IF.

if x == y:    
  print x, y "mempunyai nilai yang sama"  
else :    
  if x > y :         
       print x, "lebih besar dari", y   
  if x < y :         
       print x, "lebih kecil dari", y 
Pengertian statement if python
Pada dasarnya, kondisi If Else If adalah sebuah struktur logika program yang di dapat dengan cara menyambung beberapa kondisi If Else menjadi sebuah kesatuan. Jika kondisi pertama tidak terpenuhi atau bernilai False, maka kode program akan lanjut ke kondisi If di bawahnya. Jika ternyata tidak juga terpenuhi, akan lanjut lagi ke kondisi If di bawahnya, dst hingga blok Else terakhir atau terdapat kondisi If yang bernilai True.

Kapan Percabangan di Gunakan?
nah sekarang muncul pertanyaan kapan percabangan itu digunakan?, percabangan digunakan saat terdapat suatu keputusan atau dihadapkan pada kondisi tertentu, disini percabangan akan mengevaluasi kondisi yang hasilnya True atau False, yang dimana jika Kondisinya True maka pernyataan(statement) dalam blok tersebut akan di eksekusi dan Jika hasilnya False maka pernyataan(statement) dalam blok lain akan di eksekusi, dalam python ada 3 jenis pernyataan atau statement yang digunakan, berikut tabelnya.

iftrue/false

ok sekarang kita mari kita bahas satu-satu

Struktur If percabangan if digunakan saat terdapat satu keputusan, formatnya begini if statement: statement contohnya kita buat program ulangan, disini programnya akan menentukan jika siswa denan nilai diatas 70 akan lulus, buat program dengan nama if.py lalu isi nilai = 75 if nilai > 70: print('siswa lulus')

yang pertama kita akan membuat contoh bilangan yang memasukin bilangan satu sampai tiga
Bilangan1 = int(input("Masukkan Bilangan 1:")) Bilangan2 = int(input("Masukkan Bilangan 2:")) Bilangan3 = int(input("Masukkan Bilangan 3:"))

contoh
Gitconfig

Berikutnya kita juga bisa membuat kondisi if int
-if int(Bilangan1) and (Bilangan1 > Bilangan3): seperti dibawah ini : print("Nilai terbesarnya adalah :", Bilangan1)

contoh
iftrue/false

Terbesar = Bilangan1
NomBil = "Bilangan 1"
Selanjutnya kita juga bisa membuat kondisi elif yaitu:
-Elife(Bilangan2 > Bilangan3) and (Bilangan2 > Bilangan1): Seperti dibawah ini:

contoh
iftrue/false

Terbesar = Bilangan2
NomBil = "Bilangan 2"
else:

Terbesar = Bilangan3
NomBil = "Bilangan 3"
contoh
iftrue/false

Selanjutnya menggunakan bilangan besar adalah
print("Bilangan yang terbesar adalah", NomBil, "dengan nilai", Terbesar)

contoh
iftrue/false

Selanjutnya kita mengetahui setelah RUN yang benar:
iftrue/false

Selanjutnya kita mengetahui setelah RUN yang salah:
iftrue/false

Pada if segment diatas memiliki ketentuan nilai if pertama harus bernilai true barulah nilai if yang berikutnya yang akan di proses atau dieksekusi, namun jika nilai if pertama bernilai false maka nilai if yang berikutnya tidak akan di proses, namun jika nilai if yang pertama bernilai true sedangkan nilai if yang kedua bernilai false maka yang akan di proses hanyalah if yang pertama.
Berikut hasilnya jika if segment yang kita masukan bernilai true:

iftrue/false

selanjutnya kita juga bisa menambahkan is dan is not pada if segment seperti dibawah ini :

Pada Bahasa pemrograman python untuk membuat sebuah kondisi sama halnya dengan Bahasa pemgraman yang lain yaitu sama-sama menggunakan if, pada setiap pemrograman if berisi sebuah ekspresi logika menggunakan sebuah data yang telah dibandingkan seperti alur flowchart dibawah ini.

Contoh
Gitconfig
