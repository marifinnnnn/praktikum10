<b>NAMA : MUHAMMAD ARIFIN

NIM    : 312210330

KELAS  : TI.22.A3

Apa itu Python String ?</b>

# String adalah urutan simbol yang terbatas yang dipilih dari himpunan yang disebut alfabet.


* String adalah jenis yang paling populer di Python.

* Untuk membuatnya hanya dengan melampirkan karakter dalam tanda kutip.

* Python memperlakukan tanda kutip tunggal sama dengan tanda kutip ganda.

* Membuat string semudah memberi nilai pada sebuah variabel.

# SOAL

<img width="577" alt="1" src="https://user-images.githubusercontent.com/115518274/212737441-ecca6013-5e98-4036-9b91-7a796ea2c4c2.png">


# latihan 1
len (length) berfungs untuk menghitung jumlah karakter

replace berfungsi untuk merubah karakter

UPPER dan lower berfungsi untuk merubah semua karakter menjadi huruf besar maupun kecil

# visual studio code

<img width="577" alt="3" src="https://user-images.githubusercontent.com/115518274/212737780-4876515d-65f3-4524-8a20-28788d058a79.png">

# output

<img width="468" alt="4" src="https://user-images.githubusercontent.com/115518274/212737999-29299c5a-2b86-4b74-9199-4e6768410837.png">

# latihan 2

<img width="578" alt="2" src="https://user-images.githubusercontent.com/115518274/212738302-2f0c8456-4859-43d7-b3d0-f11f025e2b92.png">


%s untuk memanggil string

%d untuk memanggil desimal

%f untuk memanggil float

# visual studio code


<img width="840" alt="vscode1" src="https://user-images.githubusercontent.com/115518274/212738341-d1cb69be-0810-4319-9733-1b155d4eb43c.png">


# output

<img width="421" alt="2" src="https://user-images.githubusercontent.com/115518274/212738440-e5d4940f-80b7-4e71-a2fa-2e93c60474ab.png">

# Deskripsi

<b>1. Bagaimana menghitung jumlah karakter pada string ?</b>

cara menghitung karakter pada string yaitu menggunakan method len( )
Contoh:

`print(len('Hello World'))`

methode len() pada python di gunakan untuk menghitung karakter pada string.

<b>2. Bagaimana cara mengambil satu karakter pada string ?</b>

cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku [ ] dan deklarasi nomor di dalam kurung siku dengan urutan ARRAY dan menggunakan titik dua lalu masukan nomor ARRAY selanjutnya.
Contoh:

`print(txt[10])`


<b>3. Bagaimana Cara Mengambil Karakter ke 2 s/d 4 ?</b>


cara menggambil karakter 2 s/d 3 menggunakan kurung siku yang di deklarasi nomor ARRAY
Contoh:

`print(txt[2:5])`

<b>4. Bagaimana cara menghilangkan spasi pada string ?</b>


cara menghilangkan spasi pada string yaitu menggunakan method replace()
contoh:

`txt = "Hello World"
 print(replace(txt[5]))`


methode replace() mengganti semua kemunculan string lama dengan yang baru atau paling banyak kemunculan.

<b>5.Bagaimana cara menguah string menjadi huruf besar atau hurup kecil ?</b>


cara merubah hurup besar/kecil pada string yaitu menggunakan methode:

* upper() untuk memperbesar
* lower() untuk memperkecil

contoh:

`txt = "Hello world"
print(txt.upper()) #memperbesar
print(txt.lower()) #memperkecil`


<b>6.Bagaimana cara mengganti karakter pada string ?</b>

Contoh mengganti karaket H menjadi J pada karakter "Hello World" :

`txt = "Hello World"
print(replace(txt[:1]))`

di sini cara mengganti karakter masih menggunakan method replace( ) dan di deklarasi nomor ARRAY pada kurung siku.
