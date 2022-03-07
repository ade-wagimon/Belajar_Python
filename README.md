# Belajar_Python
Blog catatan ketika belajar bahasa pemrograman Python

### Kenapa belajar bahasa Python?
Bahasa `Python` merupakan salah satu bahasa yang pemrograman yang banyak digunakan oleh orang yang bukan murni programer. Bahasa `Python` populer karena bisa digunakan tanpa harus meng-compile kode terlebih dahulu (atau disebut *interpreted programming language*) sehingga cocok untuk digunakan untuk *scripting* pendek yang biasa digunakan untuk kehidupan sehari-hari. Dari beberapa *interpreted programming language* seperti `Perl` dan `Ruby`, `Python` menjadi yang terpopuler saat ini, terutama dikalangan academia untuk komputasi saintifik, pengolahan data, dan *machine learning*. Bahasa `Python` juga dikenal tidak mudah dipahami karena mirip dengan bahasa inggris.

### Mau jadi programmer?
Pada akhirnya setelah belajar bahasa `Python` kita akan menjadi programer, mungkin bukan programer yang bisa membuat program/aplikasi yang rumit, tapi cukup bisa membuat aplikasi sederhana untuk membuat aplikasi untuk me-*`loop`* perintah-perintah sederhana untuk membantu pekerjaan sehari-hari. Cotohnya, dibidang *computational drug discovery* kami sering melakakukan *virtual screening* dari rausan atau ribuan senyawa yang harus dioptimasi terlebih dahulu (*data cleaning*) yang sangat memakan waktu apa bila dilakukan secara manual, sehingga biasanya kami membuat aplikasi sederhana untuk melakukan hal tersebut. 

### Program dan Programming
Program adalah kumpulan kode atau perintah-perintah untuk menjalankan komputer, dan proses membuat atau menulis perintah-perintah tersebut *programming*.

### Programmer 
Programer adalah orang yang menulis program. Dalam proses menulis program tidak jauh berbeda dengan menulis cerita, dimana kita harus membuat judul besar atau tujuan terlebih dahulu, kemudian membuat kerangka tulisan dan kemudian menulisnya dengan bahasa yang mudah dibaca dan mudah dipahami. Dalam bahasa `Python` ada yang disebut *`reserved words`* yang merupakan kata-kata yang langsung dimengerti oleh `Python`. Berikut adalah *`reserved words`* yang ada dalam bahasa `Python`:
- and
- as
- assert
- break
- class
- continue
- def
- del
- elif
- else
- except
- finally
- for
- from
- global
- if
- import
- in
- is
- lambda
- nonlocal
- not
- or
- pass
- raise
- return
- try
- while
- with
- yield

# BAB 1
## Variable, Ekspresi dan Stetmen (*Variables, Expressions, and Statements*)

Dalam pemrograman ada yang disebut `*Value*`, sebuah hal dasar yang suatu program kerjakan bisa berupa huruf atau angka. `*Value*` ini dibedakan berdasarkan `*Type*`-nya, misalkan `*Value*` yang berupa angka bulat itu disebut dengan *integer* (int) sendahkan `*Value*` yang berupa huruf disebut *string* (str). `*Value*` ini harus diberi julukan untuk membedakan satu `*Value*` dengan `*Value*` yang lain, julukan ini disebut disebut dengan dengan ***Variable***. Contoh: 

	`pesan = "Hallo, apa kabar?"`
	`pi = 3.14`

Pada contoh di atas "Hallo, apa kabar?" merupakan `*Value*` dengan type string dari ***Variable*** yang bernama `pesan`, dan 3.14 merupakan `*Value*` dari ***Variable*** yang bernama pi. ***Variable*** ini didefinisikan dengan sebuah ***Statement*** yang disebut *Assigment Statement*. ***Statement*** sendiri merupakan sebuah pernyataan yang dipakai untuk menjalankan satu unit kode/perintah. Berikut contoh lain dari suatu statement:

	`x = 2 + 1`
	`y = x + 3`

Dalam ***Statement*** `"x =  2 + 1"` ada tanda tambah `"+"` yang merupakan operator perhitungan, dimana statement ini akan menjalakan operator matematika penambahan `2` dengan `1`. ***Statement*** `"y = x + 3"` berbeda dengan yang sebelumnya, disini ada huruf `"x"` yang merupakan variable yang telah didefinisikan pada statement sebelumnya. Dimana nilai `"x"` setara dengn `"3"` yang kemudian akan ditambahkan dengan `"3"` sesuai ***Statement*** pada variable `"y"` ini. Gabungan anatara nilai, ***Variable*** dan operator disebut dengan **Ekspresi** atau ***Expressions***. 


 

 
