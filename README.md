# Belajar_Python
Blog catatan ketika belajar bahasa pemrograman Python

### Kenapa belajar bahasa Python?
Bahasa `Python` merupakan salah satu bahasa yang pemrograman yang banyak digunakan oleh orang yang bukan murni programer. Bahasa `Python` populer karena bisa digunakan tanpa harus meng-compile kode terlebih dahulu (atau disebut *interpreted programming language*) sehingga cocok untuk digunakan untuk *scripting* pendek yang biasa digunakan untuk kehidupan sehari-hari. Dari beberapa *interpreted programming language* seperti `Perl` dan `Ruby`, `Python` menjadi yang terpopuler saat ini, terutama dikalangan academia untuk komputasi saintifik, pengolahan data, dan *machine learning*. Bahasa `Python` juga dikenal mudah dipahami karena mirip dengan bahasa inggris.

### Mau jadi programmer?
Pada akhirnya setelah belajar bahasa `Python` kita akan menjadi programer, mungkin bukan programer yang bisa membuat program/aplikasi yang rumit, tapi cukup bisa membuat aplikasi sederhana untuk membuat aplikasi untuk me-*`loop`* perintah-perintah sederhana untuk membantu pekerjaan sehari-hari. Cotohnya, dibidang *computational drug discovery* kami sering melakakukan *virtual screening* dari rausan atau ribuan senyawa yang harus dioptimasi terlebih dahulu (*data cleaning*) yang sangat memakan waktu apa bila dilakukan secara manual, sehingga biasanya kami membuat aplikasi sederhana untuk melakukan hal tersebut. 

### Program dan Programming
Program adalah kumpulan kode atau perintah-perintah untuk menjalankan komputer, dan proses membuat atau menulis perintah-perintah tersebut *programming*.

### Programmer 
Programer adalah orang yang menulis program. Dalam proses menulis program tidak jauh berbeda dengan menulis cerita, dimana kita harus membuat judul besar atau tujuan terlebih dahulu, kemudian membuat kerangka tulisan dan kemudian menulisnya dengan bahasa yang mudah dibaca dan mudah dipahami. Dalam bahasa `Python` ada yang disebut *`reserved words`* yang merupakan kata-kata yang langsung dimengerti oleh `Python`. Berikut adalah *`reserved words`* yang ada dalam bahasa `Python`:

	`- and		- as		- assert	- break`
	`- class	- continue	- def		- del`
	`- elif		- else		- except	- finally`
	`- for		- from		- global	- if`
	`- import	- in		- is		- lambda`
	`- nonlocal	- not		- or		- pass`
	`- raise	- return	- try		- while`
	`- with		- yield`




# BAB 1
## Variable, Ekspresi dan Stetmen (*Variables, Expressions, and Statements*)

Dalam pemrograman ada yang disebut `*Value*`, sebuah hal dasar yang suatu program kerjakan bisa berupa huruf atau angka. `*Value*` ini dibedakan berdasarkan `*Type*`-nya, misalkan `*Value*` yang berupa angka bulat itu disebut dengan *integer* (int) sendahkan `*Value*` yang berupa huruf disebut *string* (str). `*Value*` ini harus diberi julukan untuk membedakan satu `*Value*` dengan `*Value*` yang lain, julukan ini disebut disebut dengan dengan ***Variable***. Contoh: 

	`pesan = "Hallo, apa kabar?"`
	`pi = 3.14`

Pada contoh di atas "Hallo, apa kabar?" merupakan `*Value*` dengan `*Type*` *string* dari ***Variable*** yang bernama `pesan`, dan 3.14 merupakan `*Value*` `*Type*` *float* dari ***Variable*** yang bernama pi. Dalam penulisan nama suatu variable, ada bebrapa hal yang tidak bisa digunakan sebagai nama dari suatu variable. Nama yang berawalan dari angka atau deretan angka tidak bisa digunakan sebagai nama variable, selain itu, nama yang memiliki karakter ilegal seperti *"@"* atau nama yang merupakan *reserved words* tidak bisa digunakan sebagai nama variabel. Berikut contoh-contoh nama yang tidak bisa digunakan:

	`76sytem = "POP OS"`
	`nama@ = "Ade"`
	`lambda = 1.6`

Selain ketiga itu, nama suatu variabel tidak boleh mengandung "spasi". Sebagai programmer yang baik, kita harus terbiasa memberi nama variabel dengan nama yang mudah dimengerti dan terstruktur untuk digunakan dalam suatu program yang panjang, atau biasa disebut *mnemonic variable names*. Kata **mnemonic** memiliki arti **"memmory aid"**.***Variable*** didefinisikan dengan sebuah ***Statement*** yang disebut *Assigment Statement*. **Statement*** sendiri merupakan sebuah pernyataan yang dipakai untuk menjalankan satu unit kode/perintah. Berikut contoh lain dari suatu statement:

	`x = 2 + 1`
	`y = x + 3`

Dalam ***Statement*** "x =  2 + 1" ada tanda tambah "+" yang merupakan operator perhitungan, dimana statement ini akan menjalakan operator matematika penambahan 2 dengan 1. ***Statement*** "y = x + 3" berbeda dengan yang sebelumnya, disini ada huruf "x" yang merupakan variable yang telah didefinisikan pada statement sebelumnya. Dimana nilai "x" setara dengn "3" yang kemudian akan ditambahkan dengan "3" sesuai ***Statement*** pada variable "y" ini. Gabungan anatara `*Value*`, ***Variable*** dan operator disebut dengan **Ekspresi** atau ***Expressions***. 



## Operators

***Operator*** merupakan simbol yang mewakili suatu operasi matematika, misal: "-", "+" dll. Seperti sama halnya dengan simbol-simbol pada suatu kalkulator, ***Operator*** pada Python memang berfungsi seperti itu. Tetapi, selain simbol-simbol matematika sederhana, ada juga ***Operator*** yang diwakili oleh dua simbol sekaligus, seperti simbol "//" yang berfungsi untuk mecari angka bulat dari suatu suatu pembagian. Contoh:

	`x = 9 // 4`

dimana 9 dibagi 4 sama dengan 2 dengan sisa 1, maka `"x = 2"`. ***Operator*** tersebut disebut dengan ***Modulus Operator***. Ada juga yang disebut dengan ***Comparison Operator***, merupakan ***Operator*** yang menghasilkan `*Value*` berupa `True` atau `False` atau `*Value*`dengan type 'boolean'. Contoh:

	`4 == 9'

4 sama dengan 9, statement ini salah, sehingga interpreter akan menampilakan `*Value*` boolean `False`. Ada beberapa ***Comparison Operator*** yaitu:

	`x =! y 		# x tidak sama dengan y`
	`x == y 		# x sama dengan y`
	`x > y 			# x lebih besar dari y`
	`x < y 			# x lebih kecil dari y`
	`x >= y 		# x lebih besar atau sama dengan y`
	`x <= y 		# x lebih kecil atau sama dengan y`

Pada ***Comparison Operator*** tanda "lebih kecil" (<) dan tanda "lebih besar" (>) harus berada di urutan pertama sebelum tanda "sama dengan" (=). Selain itu, ada juga yang disebut dengan ***Logical Operator***, yang terdiri dari "and", "or", and "not". Operator ini memiliki fungsi dan makna yang sama dengan bahasa inggris. Misalkan:

	`x > 5 and x < 9'

x akan `True` apabila "x" lebih besar daripada 5 dan "x" lebih kecil dari 9, maka jika x = 9 akan `False`. 



## Conditional execution   

***Conditional execution*** atau eksekusi dengan kondisi, diamana apabila kondisi terpenuhi maka statement akan dilanjutkan, sebliknya, apabila kondisi tidak terpenuhi maka statement tidak akan dilanjutkan atau dilewati. Contohnya:

	`x = 5`
	`if x < 10:
	`	print("kurang dari 10")`
	`print("Selesai")`

pada script diatas, statement `print("kurang dari 10")` hanya akan dijalankan apabila `x < 10'. Jika 'x = 11` maka perintah tersebut akan dilewati dan langsung ke perintah selanjutnya (`print("Selesai")`). ***Conditional execution*** dibangun dengan ***Conditional Statements*** dengan awalan `"if"`, `"elif"`, dan `"else"`, kemudian dilajut oleh kondisi dan tanda ":" (titik dua) diakhir baris. Baris selanjutnya adalah baris perintah yang akan hanya dijalankan apabila kondisi terpenuhi. Pada baris perintah ini, penulisan statement harus menjorok (indented) satu `tab` dari baris sebelumnya. Perhatikan contoh dibawah ini:

	`if x == 5:`
		`print('x itu 5')`
	`else:`
		`if x < 5:`
			`print('x kurang dari 5')`
		`else:`
			`print('x lebih besar dari 5')`

Perhatikan, setiap statement setelah ***Conditional Statements*** pasti menjorok satu `tab`. Pada contoh diatas terdapat beberapa kondisi, bahkan ada kondisi dalam kondisi. Fungsi `"else"` berfungsi untuk memberi ***Alternative Execution*** atau ***branches*** atau kondisi alternatif selain fungsi `"if"`. Kemudian fungsi `"if"` dalam fungsi `"else"` merupakan ***Nested Conditionals***, atau kondisi yang bersarang dalam kondisi.  



## Fungsi (*Functions*)
 

 

 

 
