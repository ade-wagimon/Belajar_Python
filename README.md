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

Dalam pemrograman ada yang disebut `Value`, sebuah hal dasar yang suatu program kerjakan bisa berupa huruf atau angka. `Value` ini dibedakan berdasarkan `Type`-nya, misalkan `Value` yang berupa angka bulat itu disebut dengan **integer (int)** sendahkan `Value` yang berupa huruf disebut ***string (str)***. `Value` ini harus diberi julukan untuk membedakan satu `Value` dengan `Value` yang lain, julukan ini disebut disebut dengan dengan ***Variable***. Contoh: 

	`pesan = "Hallo, apa kabar?"`
	`pi = 3.14`

Pada contoh di atas "Hallo, apa kabar?" merupakan `Value` dengan `Type` **string** dari ***Variable*** yang bernama `pesan`, dan 3.14 merupakan `Value` `Type` **float** dari ***Variable*** yang bernama pi. Dalam penulisan nama suatu variable, ada bebrapa hal yang tidak bisa digunakan sebagai nama dari suatu variable. Nama yang berawalan dari angka atau deretan angka tidak bisa digunakan sebagai nama variable, selain itu, nama yang memiliki karakter ilegal seperti *"@"* atau nama yang merupakan ***reserved words*** tidak bisa digunakan sebagai nama variabel. Berikut contoh-contoh nama yang tidak bisa digunakan:

	`76sytem = "POP OS"`
	`nama@ = "Ade"`
	`lambda = 1.6`

Selain ketiga itu, nama suatu variabel tidak boleh mengandung "spasi". Sebagai programmer yang baik, kita harus terbiasa memberi nama variabel dengan nama yang mudah dimengerti dan terstruktur untuk digunakan dalam suatu program yang panjang, atau biasa disebut *mnemonic variable names*. Kata **mnemonic** memiliki arti ***memmory aid***.***Variable*** didefinisikan dengan sebuah ***Statement*** yang disebut *Assigment Statement*. **Statement*** sendiri merupakan sebuah pernyataan yang dipakai untuk menjalankan satu unit kode/perintah. Berikut contoh lain dari suatu statement:

	`x = 2 + 1`
	`y = x + 3`

Dalam ***Statement*** **"x =  2 + 1"** ada tanda tambah **"+"** yang merupakan operator perhitungan, dimana statement ini akan menjalakan operator matematika penambahan 2 dengan 1. ***Statement*** **"y = x + 3"** berbeda dengan yang sebelumnya, disini ada huruf **"x"** yang merupakan variable yang telah didefinisikan pada statement sebelumnya. Dimana nilai **"x"** setara dengn **"3"** yang kemudian akan ditambahkan dengan **"3"** sesuai ***Statement*** pada variable **"y"** ini. Gabungan anatara `Value`, ***Variable*** dan operator disebut dengan **Ekspresi** atau ***Expressions***. 



## Operators

***Operator*** merupakan simbol yang mewakili suatu operasi matematika, misal: **"-", "+"** dll. Seperti sama halnya dengan simbol-simbol pada suatu kalkulator, ***Operator*** pada Python memang berfungsi seperti itu. Tetapi, selain simbol-simbol matematika sederhana, ada juga ***Operator*** yang diwakili oleh dua simbol sekaligus, seperti simbol **"//"** yang berfungsi untuk mecari angka bulat dari suatu suatu pembagian. Contoh:

	`x = 9 // 4`

dimana 9 dibagi 4 sama dengan 2 dengan sisa 1, maka **"x = 2"**. ***Operator*** tersebut disebut dengan ***Modulus Operator***. Ada juga yang disebut dengan ***Comparison Operator***, merupakan ***Operator*** yang menghasilkan `Value` berupa `True` atau `False` atau `Value`dengan type 'boolean'. Contoh:

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

**x** akan `True` apabila **x** lebih besar daripada 5 dan **x** lebih kecil dari 9, maka jika **x = 9** akan `False`. 



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

Perhatikan, setiap statement setelah ***Conditional Statements*** pasti menjorok satu `tab`. Pada contoh diatas terdapat beberapa kondisi, bahkan ada kondisi dalam kondisi. Fungsi `else` berfungsi untuk memberi ***Alternative Execution*** atau ***branches*** atau kondisi alternatif selain fungsi `if`. Kemudian fungsi `if` dalam fungsi `else` merupakan ***Nested Conditionals***, atau kondisi yang bersarang dalam kondisi.  




## Fungsi (*Functions*)
 
Dalam konteks programming, ***`fungsi`*** merupakan suatu sekuens dari beberapa `statement` yang menjalankan komputasi. Suatu `fungsi` didefinisakan dengan sebuah nama untuk sekuens dari statement-statement tersebut. Fungsi ini kemudian dapat dipanggil dengan ***Call*** nama dari `fungsi` tersebut. Misalkan:

	`>>>type(45)`
	`<class 'int'>`
 
Pada contoh tersebut, `Type` merupakan `fungsi` yang di panggil, dan **45** adalah `value` yang dikenai fungsi. Seperti yang kita ketahui sebelumnya, `fungsi` `type` merupakan suatu fungsi yang bertujuan untuk mencari atau mengidentifikasi suatu jenis `value`. Maka, didaptkan interpretasi `class 'int'` atau suatu `integer`. Fungsi sendiri dibagi menjadi beberapa jenis, tapi secara garis besar terbagi menjadi dua jenis fungsi yaitu ***built in function*** dan ***definited function***. Sesuai dengan namanya ***built in function*** merupakan fungsi yang sudah tersedia di dalam package `Python`, contohnya adlah fungsi `type` diatas, sedangkan ***definited function*** adalah fungsi yang kita definisikan sendiri. Pada ***built in function*** ada yang disebut dengan ***math function***, fungsi ini buntuk memanggil fungsi atau rumus matematika seperti fungsi **sinus** dan **cosinus**, berikut contohnya:

	`import math`
	`x = math.sin(45)`
	`y = math.cos(45)`
	`z = x + y'
	`z`
	`1.4142`

Sedangkan untuk ***definited function*** kita harus mendefinisikannya terlebih dahulu dengan keyword `def`. Setalah fungsi itu didefiniskan kita dapat menggunakan fungsi tersebut berkali-kali. Contoh:

	`   def	lirik_lagu():
	`	print("Ku kira, kita akan bersama")`
	`	print("Begitu banyak yang sama, latarmu dan latarku")`
	
Pada contoh di atas kita telah mendefiniskan fungsi dengan nama **lirik_lagu**, dengan statement-statement `print("Ku kira, kita akan bersama")` dan `print("Begitu banyak yang sama, latarmu dan latarku")`, yang mana apabila kita tulis **lirik lagu** kita akan otomatis memanggil/`call` fungsi tersebut. Baris pertama pada contoh di atas, disebut ***header***. Sedangkan baris selanjutnya disebut ***body***. Pada ***header*** harus diawali oleh keyword `def`, nama fungsinya, dan diakhiri oleh tanda `titik dua` (`:`). Pada ***body***, berisi beberapa statement-statement untuk fungsi tersebut.

	`>>>lirik_lagu`
	`Ku kira, kita akan bersama`
	`Begitu banyak yang sama, latarmu dan latarku`
	
## Iteration

Jika kita menulis suatu assigment statement seperti ini:

	`x = x + 1`

maka kita akan mendaptkan hasil seperti ini **“NameError: name 'x' is not defined”**, karena `Python` membaca sisi kiri terlebih dahulu. Dimana kita belum memiliki nilai awal untuk **x** itu sendiri. Olehkarena itu, kita harus `menginisiasi` atau **`initialize`** nilai **x** dengan suatu assigment sederhana seperti:

	`x = 0`
	`x = x + 1`

Dengan statement seperti itu, dari awal **x** sudah memiliki nilai yang kemudian diupdate lagi dengan statement berikutnya. Proses update ini sangat penting dalam proses `iteration` dan ‘recursion’ (tapi karena recursion itu susah dijelaskan dengan kata-kata, saya tidak akan membahasnya di buku ini). Mengupdate nilai dengan menambahkan anka 1 disebut ***increment***, tapi apabila mengupdate nilai dengan menguranginya dengan angka 1 disebut ***decrement***.

Komputer bisasnya digunakan untuk menjalankan pekerjaan repetisi, dan sangat handal dalam bidang repetisi ini (dibanding manusia). `Python` menyediakan beberapa fitur bahasa untuk mempermudah proses repetisi ini.  Salah satunya adalah statement `while`, dan berikut contoh program sederhana yang menggunakan statement `while`:

	`n = 3`
	`while n > 0:`
		`print(n)`
		`n = n - 1`
	`print(“'DOOORRR!”)`

Ketika atau `while`  n lebih besar daripada 0, tampilkan atau `print` nilai **n** dan kemudian kurangi nilai **n** dengan **1**.  Maka statement akan terus diulangi sampai nilai **n** sama dengan **0**, kemudian ketika **n** sama dengan **0**, statement `while` akan mendapat hasil `False` dan layar akan menmpilkan tulisan **DOOORRR!**. Program diatas bisa dibaca oleh orang yang tidak memiliki latar pendidikan programming, dan itulah salah satu kelebihan Python.

Apabila program itu diurai: langkah pertama, program tersebut memastikan `condition` atau kondisi, apakah menghasilkan `True` atau `False`. Kemudian apabila kondisi sama dengan `True`, maka program akan meneksekusi ***body statement*** dan kembali ke step 1. Teatapi, apabila kondisi sama dengan `False`, maka program akan keluar dari ***statement while*** dan kemudian akan lanjut ke `statement` selanjutnya. Biasanya apabila kita salah membuat kondisi maka kita akan terjebak pada ***infinite loop*** dan program akan berjalan tanpa henti. Kondisi ini biasanya disebabkan karena kita tidak memasukan ***iteration variable***, sehingga kondisi berada pada keadaan `True` terus. Contohnya seperti ini:


	`n = 3`
	`while True:`
		`print(n)`
		`n = n - 1`
	`print(“'DOOORRR!”)`

Baris `while True:` akan menyebabkan terjadinya ***infinite loop***.


	


## Strings

`String` merupakan sebuah sekuens dari karakter/huruf. Untuk membuat suatu variabel yang berisi `string`, tulisakan `value` dalam **tanda kutip (‘/”)**. Contoh:
	
	`contoh = “ini str”`

Setiap karakter dalam **tanda petik** memiliki nomor urutan yang disebut ***index*** dimuklai dari urutan **0** sampai seterusnya.

	`>>>list(enumerate(contoh))`
	`[(0, 'i'), (1, 'n'), (2, 'i'), (3, ' '), (4, 's'), (5, 't'), (6, 'r')]`

Dengan menggunakan peritah diatas, kita bisa melihat nomor ***`index`*** dari setiap karakter. Kemudian kita juga bisa memangil setiap karakter tersebut dengan perintah:
	
	`contoh[1]`
	`contoh[0:3]`

dengan perintah pertama kita akan memanggil karakter pada `index` nomor **1** yaitu huruf **n**. Sedangkan perintah yang kedua kita akan memotong `string` `index` nomor **0** sampai dengan karakter sebelum `index` nomor **3**, maka interpreter akan menampilkan kata **‘ini**.  

`String` juga bersifat ***immutable*** atau tidak bisa dimutasi. Maksudnya adalah, karakter atau value yang ada pada suatu string tidak bisa diganti/dimutasi. Contoh:

	`contoh = “ini str”`
	`contoh[0] = ‘I’`

Perintah diatas adalah perintah yang bertujuan untuk mengganti karakter **i** dengan karakter **I**, apabila perintah tersebut dijalankan, maka kita akan mendapatkan pesan error ***TypeError: 'str' object does not support item assignment***.

Adapun bebrapa cara atau `methods` yang bisa digunakan untuk berkerja dengan string adalah sebagai beikut:

	`['capitalize', 'casefold', 'center', 'count', 'encode',`
	`'endswith' , 'expandtabs', 'find', 'format', 'format_map',`
	`'index' , 'isalnum', 'isalpha', 'isdecimal', 'isdigit',`
	`'isidentifier' , 'islower', 'isnumeric', 'isprintable',`
	`'isspace' , 'istitle', 'isupper', 'join', 'ljust', 'lower',`
	`'lstrip' , 'maketrans', 'partition', 'replace', 'rfind',`
	`'rindex' , 'rjust', 'rpartition', 'rsplit', 'rstrip',`
	`'split' , 'splitlines', 'startswith', 'strip', 'swapcase',`
	`'title' , 'translate', 'upper', 'zfill']`

berukut contoh penggunannya: 

	`>>>contoh = “ini str”`
	`>>>kapital = contoh.upper’
	`>>>print(kapital)
	`INI STR`

fungsi `upper` akan memebuat semua karakter pada string tersebut menjadi uppercase atau **huruf kapital**.



## Lists

`List` merupakan sekuens atau kumpulan urutan yang tersusun oleh value-value yang disebut **elements** atau **items**. 

	`suku = [‘Jawa’, ‘Sunda’, ‘Minang’, ‘Melayu’, ‘Bugis’, ‘Dayak’]`
	`ukuran_sepatu = [37, 38, 39, 40, 41, 42, 43, 44]`

kedua contoh diatas merupakan `list` yang tersusun dari **elements** dengan  satu `data.type` yang sama, `list` yang berisi `integer` dan `list` yang berisi `string`. List juga bisa berisi dari berbagai `data.type` seperti:

	`ujang = [‘laki-laki’, 23, 173, 65, [“a”,”b”,”c”]]’

Contoh diatas adaah contoh `list` yang berisi beberapa `type` elements, bahkan ada `list` di dalam `list` itu sendiri. 

Sebagaimana `string`, `list` juga memilki nomor urutan bagi setiap elements, yang bisa dipanggil dengan nomor indexnya. Tetapi, berbeda dengan `string`, `list` ini bersifa mutable atau dapat dimutasi. 

 	`>>>ukuran_sepatu = [37, 38, 39, 40, 41, 42, 43, 44]`
	`>>>ukuran_sepatu[1] = 35`
	`>>>ukuran_sepatu`
	`[37, 35, 39, 40, 41, 42, 43, 44]`

sifat mutabil ini membuat list lebih fleksible tetapi rawan berubah. Berikut adalah beberapa method yang bisa digunakan untuk `list`:

 	`>>>ukuran_sepatu = [37, 38, 39, 40, 41, 42, 43, 44]`
	`>>>ukuran_sepatu.append(‘47’)
	`>>>ukuran_sepatu`
	`[37, 38, 39, 40, 41, 42, 43, 44, 47]`
	`>>>ukuran2 = [45, 46, 48, 49]
	`>>>ukuran_sepatu.extend(ukuran2)
	`>>>ukuran_sepatu`
	`[37, 38, 39, 40, 41, 42, 43, 44, 47, 45, 46, 48, 49]`

selain itu, apabila suatu `list` memiliki element yang sama dengan `list` yang lain, maka python akan membacanya sebagai dua objek yang berbeda, sedangkan pada `string` itu merupakan objek yang sama. Contoh:

	`>>>a = “apel”`
	`>>>a2 = “apel”`
	`>>> a is a2`
	`True`

sedangkan

	`>>>a = [“apel”]`
	`>>>a2 = [“apel”]`
	`>>> a is a2`
	`False`

meskipun kedua list tersebut memiliki element yang sama, kedua objek tersebut tetap objek yang berbeda. Suatu objek itu memiliki `value`, jadi objek satu dengan yang lainnya bisa saja memiliki value yang sama.


## Tuple
`Tuple` mirip dengan list, tapi apabila kalau kita membuat suatu list itu menulis assigment element-element dalam kurung siku, pada `tuple` itu ditulis dengan tanda kurung biasa. Kemudian `tuple` juga bisa menggunakan variable sebagai pengganti nomor index. Contoh:

	`>>>a = (“apel”, ”anggur”)`
	`>>>(a1, a2) = a`
	`>>>a1`
	`’apel’`
	`>>>a2`
	`’anggur’`

atau bisa langsung ditulis seperti ini:\

	`>>>a1, a2 = “apel”, “anggur”`
	`>>>a1`
	`’apel’`
	`>>>a2`
	`’anggur’`

Terakhir, tuple itu bersifat immutable, atau tidak bisa dimutasi.


## Dictionary

Selain `stirng`, `list`, dan `tuple` ada juga yang disebut `dictionary` yang merupaka ***compound data type***. `dictionary` bersifat immutable, dan juga memilki nama/julukan untuk setiap element-nya. Nama/julukan-element ini disebut dengan ***key:value pairs***. 

	`>>>terjemah = {}`
	`>>>terjemah[“satu”] = “yi”`
	`>>>terjemah[“dua”]= “er”`
	`>>>pritnt(terjemah)’
	`{“dua” : “er”. “satu” : “yi”}`

dan untuk memanggil dictionary tersebut adalah seperti ini:

	`>>>print(terjemah[“dua”])`
	`’er’`





 

 
