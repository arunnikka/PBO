### 1.	Jelaskan apa yang dimaksud dengan class dan object!

Class dan object adalah sebuah konsep yang saling berkaitan erat dan tidak dapat dipisahkan. Class merupakan cetak biru atau kerangka dalam pembuatan program, sedangkan object adalah hasil instance atau penciptaan dari sebuah class. Class merupakan prototipe yang mendefinisikan attribute dan behavior secara umum.Saat implementasi kedalam sebuah program attribute dimodelkan sebagai variabel dan behaviordimodelkan sebagai method atau yang lebih dikenal dikalangan programmer adalah function.

### 2.	Sebutkan dan jelaskan jenis-jenis method !
#### a.	Instance Method -> Merupakan method yang hanya bisa dipanggil melalui object. Method ini dapat mengakses dan memodifikasi atribut milik object yang bersangkutan.

#### b.	Static Method -> Method yang bisa dipanggil langsung melalui class tanpa harus membuat object. Biasanya digunakan untuk operasi yang tidak bergantung pada atribut suatu object, seperti fungsi utilitas atau perhitungan matematika.

#### c. Abstract Method -> Method yang hanya dideklarasikan tanpa implementasi. Method ini harus ada dalam abstract class dan wajib di-override oleh class turunannya. Tujuannya adalah untuk menentukan kerangka method yang harus diimplementasikan oleh subclass.

#### d. Getter dan Setter Method -> Method khusus yang digunakan untuk mengakses (getter) dan mengubah (setter) nilai dari atribut yang bersifat private. Dengan cara ini, data dalam class bisa lebih terkontrol dan aman.

Selain itu, ada juga final method, yang tidak bisa di-override oleh subclass, serta constructor method, yang digunakan untuk menginisialisasi object saat pertama kali dibuat.

### 3.	Berdasarkan gambar berikut ini, jelaskan masing-masing bagian sesuai dengan nomor yang ada!
#### a.	Class (Komputer)
Class adalah blueprint atau template untuk membuat objek.
Nama class dalam Java diawali dengan huruf besar sesuai dengan konvensi penamaan.

#### b.	Atribut (Attribute)
Jenis_komputer → Tidak memiliki access modifier (default), sehingga dapat diakses dalam package yang sama.
merk → Bersifat private, sehingga hanya bisa diakses dalam class itu sendiri.

#### c.	Method (Deklarasi)
Method dalam class ini berfungsi untuk mengatur dan mengambil nilai atribut.
Terdapat tiga jenis method dalam class ini: setter, getter, dan method main.

#### d.	 Method Getter (getJenis)
Berfungsi untuk mengembalikan nilai dari atribut jenis_komputer.

#### e.	 Method Getter (getMerk)
Berfungsi untuk mengembalikan nilai dari atribut merk, karena merk bersifat private sehingga harus diakses melalui getter.

#### f.	Instansiasi Object
Komputer mykom = new Komputer(); → Ini adalah proses membuat objek baru dari class Komputer, sehingga method dan atributnya bisa digunakan.

#### g.	 Method Setter (setDataKomputer)
Method ini digunakan untuk mengatur nilai atribut jenis_komputer dan merk.
Parameter method digunakan untuk menerima data yang akan dimasukkan ke dalam atribut class.

#### h.	 Method Getter (getJenis dan getMerk)
mykom.getJenis(); → Mengambil nilai dari jenis_komputer.
mykom.getMerk(); → Mengambil nilai dari merk.

#### Kesimpulan
Enkapsulasi diterapkan dengan penggunaan atribut private dan method getter.
Instansiasi object memungkinkan penggunaan method setter dan getter.
Kode ini menunjukkan konsep dasar OOP (Object-Oriented Programming) dalam Java, yaitu class, object, enkapsulasi, method, dan instansiasi.


The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).
