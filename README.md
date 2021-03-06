# Membangun Aplikasi Cloud Menggunakan Go

Buku ini merupakan buku pemrograman Go yang ditujukan untuk pengembangan aplikasi SaaS di Cloud. Meskipun titik berat dari buku ini ada pada pemrograman aplikasi di Cloud, buku ini juga meliputi dasar-dasar Go serta penggunaan Go untuk backend dan frontend. 

# Penulis

Buku ini ditulis bersama-sama oleh dosen dan mahasiswa [STMIK AKAKOM Yogyakarta](http://www.akakom.ac.id). Meskipun demikian, kontribusi dari siapapun itu akan diterima dengan senang hati. Untuk saat ini, beberapa nama ini berperan dalam penulisan:

* [Bambang Purnomosidi D. P.](http://bpdp.xyz): penulis utama, editor, maintainer, all hands person.
* ... Afif Budianto ...
* ... Fajar Ananda ...

## Ingin Berkontribusi?

Cara berkontribusi dijelaskan dalam suatu [dokumen tersendiri tentang berkontribusi](berkontribusi.md)

# Menggunakan Buku

Meskipun bisa langsung membaca dari repo Github ini melalui file README.md, ada beberapa cara lainnya yang bisa digunakan:

* `make`: membuat 3 format buku (EPUB, HTML, dan PDF), hasil akan diletakkan di direktori sesuai dengan isi variable `BUILD` pada `Makefile`
* `make pdf` untuk membuat format PDF, `make html` untuk membuat format HTML, dan `make epub` untuk membuat format EPUB.

# Isi Buku

Buku ini akan dibagi menjadi beberapa bagian:
* Pengenalan
* Dasar-dasar Pemrograman Go: Sintaksis, Semantik, dan Pustaka Standar
* Go untuk Backend
* Frontend Programming dan Go
* Integrasi Frontend dan Backend
* Go di Cloud
* Penutup

## Pengenalan

Pada bagian ini, akan dibahas instalasi peranti pengembangan bahasa pemrograman Go serta peranti yang biasanya digunakan pada saat `coding` menggunakan Go (IDE - `Integrated Development Environment`). Setalah membaca, memahmi, dan mengikuti instruksi pada bagian ini, pembaca akan mempunyai peranti pengembangan Go serta IDE untuk `coding` terinstall pada komputer. Pembaca juga akan memahami struktur kode sumber Go dan siap untuk mempelajari komponen Go lebih lanjut.

* [Bab 1: Pengenalan Go](bab-01.md)
* [Bab 2: IDE untuk Go](bab-02.md)

## Dasar Pemrograman `Go`: Sintaksis, Semantik, dan Pustaka Standar

Bagian ini membahas tentang komponen dasar dan inti dari bahasa pemrograman Go. Semua pembahasan pada bagian ini terdapat pada instalasi standar peranti pengembangan Go.

* [Bab 3: Dasar-dasar Pemrograman Go](bab-03.md)
* [Bab 4: Fungsi / `Function](bab-04.md)
* [Bab 5: Penanganan Kesalahan](bab-05.md)
* [Bab 6: Struktur Data Lanjut](bab-06.md)
* [Bab 7: Method](bab-07.md)
* [Bab 8: Testing](bab-08.md)
* [Bab 9: Konkurensi](bab-09.md)

## Go untuk Backend 

Bagian ini membahas tentang penggunaan Go sebagai peranti pengembang untuk backend. Beberapa bagian dari pembahasan ini menggunakan pustaka standar dari Go dan juga beberapa software atau pustaka pihak ketiga. Setiap pembahasan akan dimulai dengan peranti pustaka standar serta peranti pustaka pihak ketiga yang akan digunakan.

* [Bab 10: Mehamami Ruang Lingkup Backend](bab-10.md)
* [Bab 11: Serialisasi](bab-11.md)
* [Bab 12: Akses Basis Data](bab-12.md)
* [Bab 13: RESTful Service](bab-13.md)
* [Bab 14: Go dan Microservices](bab-14.md)

## Frontend Programming dan Go

Bagian ini membahas tentang pemrograman pada sisi frontend serta bagaimana menggunakan Go sebagai bagian dari frontend programming tersebut.

* [Bab 15: Pustaka Standar Go untuk Frontend](bab-15.md)
* [Bab 16: Template Engine](bab-16.md)
* [Bab 17: GopherJS](bab-17.md)

## Integrasi Frontend dan Backend

* [Bab 18: Middleware](bab-18.md)
* [Bab 19: Rekayasa Aplikasi Web](bab-19.md)
* [Bab 20: Aplikasi Web tanpa Framework](bab-20.md)
* [Bab 21: Framework Aplikasi Web](bab-21.md)

## Go di Cloud

* [Bab 22: Memahami Ruang Lingkup Cloud Computing](bab-22.md)
* [Bab 23: Tools Cloud Computing untuk Go](bab-23.md)
* [Bab 24: Go dan AppEngine](bab-24.md)

## Penutup

* [Kemana Setelah Ini? Berbagai Sumber Daya Terkait Go](sumberdaya.md)
* [Daftar Pustaka](daftar-pustaka.md)

# Lisensi

![CC-BY-SA 4.0](images/cc-by-sa-4.png)
[CC-BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/)

# Lain-lain

Buku ini dibuat menggunakan markdown dan dikonversi menjadi EPUB - HTML - PDF menggunakan [pandoc](http://pandoc.org). Template untuk buku diambil dari [evangoer/pandoc-ebook-template](https://github.com/evangoer/pandoc-ebook-template).
