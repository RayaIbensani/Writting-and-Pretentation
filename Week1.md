# TUGAS WRITING MINGGU PERTAMA
## UNIX COMMAND LINE
### Apa itu Command line ?

  Command line atau Command Line Interface adalah **Shell** yang berbentuk teks, dan apa itu **shell**?
* Shell adalah Program yang digunakan untuk berkomunikasi atau memerintah sistem ini bisa disebut juga dengan **terminal**.
 ### Bagaimana cara kita mengakses CLI ?

   Kita bisa menggunakan beberapa contoh CLI, salah satunya adalah **Command Prompt**

   ![Gambar](https://github.com/RayaIbensani/Other/blob/main/img.JPG?raw=true)

   Yang diatas adalah contoh terminal dari Command Prompt
 ### Filesystem Structure
  Cara sistem beroprasi untuk menyusun atau mengatur file dan direktori dalam bentuk seperti pohon

  ![Tree](https://github.com/RayaIbensani/tree/blob/main/pic.JPG?raw=true)
### Navigation
   Navigasi adalah perintah-perintah untuk menjalankan sistem yang ada dikomputer, kita bisa menggunakan beberapa command untuk menjalankan navigasi ini
   * Command pwd (_print working directory_)
    adalah command yang kita gunakan untuk melihat kita berada di direktori mana
* Command ls (_lists_)
   adalah command yang kita gunakan untuk melihat isi dari direktori tempat kita berada.
* Command cd (_change directory_)
   adalah command yang kita gunakan untuk berpindah ke direktori yang lain.
* Command untuk melihat isi sebuah file, kita dapat menggunakan Command head,tail untuk melihat beberapa line awal dalam sebuah file text dan Command cat untuk melihat isi file tersebut.
* Command touch dan mkdir
  adalah command yang kita gunakan untuk membuat file (touch) dan directori (mkdir)
* Command mv (_move_)
  adalah command yang kita gunakan untuk memindahkan file atau directori, dan bisa digunakan juga untuk me-rename file dan direktori.
* Command cp (_copy_)
  adalah command untuk menyalin file atau direktori.
* Command rm (_remove_)
  adalah Command untuk menghapus file atau direktori.

 ## GIT & GITHUB
 ###  Git

   Git adalah tools untuk programmer atau aplikasi yang dapat melacak setiap perubahan yang terjadi pada sebuah file atau folder (termasuk semua code) pada suatu proyek baik itu dikerjakan secara individu ataupun tim dan berfungsi sebagai **Version Control System**.
  
  Git biasanya digunakan untuk menyimpan file yang berisi pemrograman karena **lebih efektif**, semua file yang tersimpan akan terlacak semua perubahannya termasuk siapa yang merubahnya.
### Github

Github adalah platform yang dapat digunakan untuk meninjau sebuah kode, mengelola _project_, dan membangun perangkat lunak sesama programmer.

**Tujuan** "_kenapa kita harus menggunakan git dan github_" adalah agar bisa berkolaborasi untuk mengerjakan proyek yang sama, kita juga tak perlu menunggu rekan dalam satu tim untuk menyelesaikan suatu program, kita bisa membuat file didalam projek yang sama atau code dan menyatukannya saat sudah selesai.

Perbedaan Git dan Github ada banyak tapi secara singkatnya  adalah Git melakukan penyimpanan data di komputer itu sendiri jadi jika ada orang lain merubahnya maka perubahan itu tersimpan di masing-masing komputer, sedangkan Github memiliki penyimpanan sendiri di platformnya, jadi jika ada perubahan maka perubahan tersimpah di Github itu sendiri bukan di komputer.

* Repository Git
  adalah direktori proyek yang sudah kita buat menggunakan **git init**.
* git status 
  digunakan untuk mengetahui sebuah keadaan dari repository lokal, ada beberapa keadaan yang akan muncul di git status.

  **Modified** adalah keadaan dimana perubahan sudah dilakukan tapi belum ditandai (_untracked_) dan belum disimpan ke version control.

  **staged** adalah kondisi dimana perubahan sudah ditandai tapi belum disimpan.

  **committed** adalah kondisi dimana perubahan sudah ditandai dan disimpan.
* git add digunakan untuk menambahkan file ke staged/staging area secara satu per satu, jika git add . maka digunakan untuk menambahkan file secara menyeluruh.
* git commit -m digunakan untuk meng-commit penambahan checkpoint/kondisi yang sudah kita add, step setelah git add.
* git log digunakan untuk melihat history/kumpulan checkpoint(commit) yg telah kita buat.

### Mempublish Git ke Github
   Pertama tama kita harus membuka platfrom github di browser

   ![gambar](https://github.com/RayaIbensani/example/blob/main/Capture.JPG?raw=true)

   Kita tekan tulisan **New** disamping tulisan Recent Repositories, gambar yang akan keluar selanjutnya adalah

   ![gambar](https://github.com/RayaIbensani/contoh/blob/main/InkedCapture.jpg?raw=true)

   Kita buat nama repository yang akan kita publish, setelah sudah kita pastikan bahwa itu repository untuk public kita bisa langsung mengklik creat repository yang ada dibawah,setelah itu kita buka folder/file yang akan kita publish, jika sudah terbuka kita klik kanan untuk menampilkan option seperti dibawah
  
   ![gambar](https://github.com/RayaIbensani/kelolosan/blob/main/2022-07-16.png?raw=true)
  
   kita klik yang **git Bash Here**, jika sudah kita balik lagi ke halaman github, kita menuliskan **git init** kita enter, setelah itu kita tuliskan seperti dicontoh baris ke 5 dan setelah itu kita buka code editor.

   ![gambar](https://github.com/RayaIbensani/contoh/blob/main/Capture.JPG?raw=true)

 setelah itu kita tuliskan seperti dicontoh baris ke 5 dan setelah itu kita buka code editor.

 ![gambar](https://github.com/RayaIbensani/contoh/blob/main/in.JPG?raw=true)
 Kita membuka file kita di pojok kiri atas

 ![gambar](https://github.com/RayaIbensani/contoh/blob/main/fot.JPG?raw=true)

 setelah terbuka, digambar sebelumnya file kita masih tertulis untracked (ada tulisan U disamping file) jadi kita harus menghilangkannya dengan menggunakan **git add .**, dan **git commit -m**, kita harus mengganti branch 
 (master) dengan branch yang digunakan github (main), dengan menggunakan **git branch -M main**, jika branch kita sudah terganti maka kita bisa push/mengupload ke github dengan menggunakan **git push -u origin main**, setelah sudah selesai maka file sudah terupload di github

 ![gambar](https://github.com/RayaIbensani/and/blob/main/Capture.JPG?raw=true)

### Bagaimana cara men-clone data yang sudah terhapus?
 
 Ada cara yang digunakan untuk meng-copy data yang sudah terhapus tapi sudah ter-upload di Github atau kita meng-copy data (yang sudah ada di Github) untuk dimasukan ke laptop/komputer baru yaitu dengan menggunakan **git clone**, bagaimana caranya?

 Pertama tama kita buka File Github yang akan kita clone, kita klik tulisan code seperti gambar dibawah

 ![Gambar](https://github.com/RayaIbensani/Picture/blob/main/InkedCapture.jpg?raw=true)

 Setelah diklik akan muncul option seperti gambar dibawah, kita klik aja untuk meng-copy linknya

 ![gambar](https://github.com/RayaIbensani/Picture/blob/main/SS.JPG?raw=true)

Setelah itu kita kembali ke **File Explorer**  dan membuka folder untuk menyimpan file yang di clone itu setelah itu kita bisa langsung membuka git bash lalu mengetikkan **git clone "link file yang sudah di copy"** seperti contoh dibawah

![gambar](https://github.com/RayaIbensani/Picture/blob/main/Foto.JPG?raw=true)

Seperti contoh diatas proses clone telah berhasil.
 

## HTML

HTML adalah singkatan dari _Hypertext Markup Language_, HTML digunakan untuk menampilkan konten(text, gambar, video dll) pada browser (website), HTML bersifat _statis_ dia hanya bertugas untuk menampilkan konten yang diminta oleh developer, HTML bukan **bahasa pemrograman**.

Tools yang dibutuhkan untuk membuat HTML 
1. Browser
2. Code Editor

Code Editor yang digunakan adalah visual studio code, di VS code kita bisa memakai bahasa pemrogaraman apa saja

### HTML sederhana

![gambar](https://github.com/RayaIbensani/HTML/blob/main/html.JPG?raw=true)

Ini adalah contoh HTML sederhana

Cara agar kita dapat melihat hasil dari HTML yang kita buat adalah membukanya lewat browser, tapi vs code memiliki cara mudah untuk membukanya yaitu melalui _Live Server_

![gambar](https://github.com/RayaIbensani/HTML/blob/main/Inkedhtml1.jpg?raw=true)

Jika sudah terbuka seperti ini kita tinggal meng-install _live server_ tersebut untuk dipakai didalam vs code kita, jika sudah terinstall maka kita dapat mengaksesnya dengan mengklik kanan pada file html kita lalu mengklik option **open with live server** maka kita akan dibawa ke browser tempat file html kita bukan lagi berupa code

![gambar](https://github.com/RayaIbensani/HTML/blob/main/html2%20(2).JPG?raw=true)

### Struktur HTML
HTML tersusun dari sebuah tingkatan (_family tree relationship_).

Saat sebuah element berada di dalam element lain, maka disebut **child element**.

Element yang berada diatas element lain disebut **parent element**. Seperti gambar diatas < body > adalah **parent element** dari < p > dan < p > adalah **child element dari < body >.

### HTML Element
Elemen html didefinisikan sebagai _opening tag, content, closing tag_ (< p >Hai</ p>), tak semua HTML element memiliki _content_ contohnya < br> element ini disebut **empty element** dan tidak memiliki _closing tag_

### HTML Attribute
Attribute adalah properties dari sebuah elemen html contohnya < img src= "img.png">. Img adalah elemen, src="" adalah attribute dari elemen img.

### HTML Comment
(< ! -- -->) Digunakan untuk menjelaskan kode yang kita buat,html comment hanya akan dibaca oleh sesama programmer dan tidak akan dieksekusi oleh komputer. 

### HTML Tag

HTML memiliki 3 tag utama yaitu < html >, < head >, < body > dan masing-masing tag memiliki opening tag (< head >) dan closing tag (</ head >)(dan itu disebut **HTML Anatomy**)
1. < html> adalah root element dari halaman HTML. Semua HTML tag lainnya harus dibungkus dengan tag ini.

![gambar](https://github.com/RayaIbensani/HTML/blob/main/html3.JPG?raw=true)

2. < head>  umumnya berisi < meta>, < title>, konten css/js internal maupun link ke file css/js eksternal.
![gambar](https://github.com/RayaIbensani/HTML/blob/main/html4.JPG?raw=true)

3. < body> berisi konten yang akan ditampilkan di website

![gambar](https://github.com/RayaIbensani/HTML/blob/main/html5.JPG?raw=true)


**bonus** < !DOCTYPE html> adalah syntax yang mendefinisikan versi dari HTML yang digunakan.

Selain memiliki tag utama, HTML tag juga memiliki tag populer yaitu **img, video dan table**

* Img 
   digunakan untuk menampilkan gambar (< img src="img.png" alt=Pic>),
   **src** adalah source link gambar yang ingin kita tampilkan, sedangkan **alt** adalah tulisan jika link gambar yang ingin kita tampilkan terhapus.
* Video
  digunakan untuk menampilkan video (< video controls>< source src="Video.mp4 type="video/mp4></ video>), **controls** digunakan untuk mengatur play/pause dan indikator menit 
* Table
  digunakan untuk menampilkan table, table berada di tag body

  ![gambar](https://github.com/RayaIbensani/HTML/blob/main/html7.JPG?raw=true)
![gambar](https://github.com/RayaIbensani/HTML/blob/main/html8.JPG?raw=true)

### Semantic HTML
Semantic artinya kita menggunakan element HTML yang sesuai dengan kebutuhan HTML dari pada kita menggunankan < div class="header"> kita bisa menggunakan < header>

Kegunaan Semantic adalah
1. Meningkatkan accessibility
2. Meningkatkan SEO
3. lebih mudah di Maintain

### Deploy HTML
Deploy adalah menyebarkan aplikasi yang sudah kita kerjakan agar bisa digunakan oleh orang-orang. Kita dapat menggunakan **Netlifly**

![gambar](https://github.com/RayaIbensani/Oke/blob/main/bonus.JPG?raw=true)

Kita hanya perlu masuk ke tab Sites lalu drag and drop seluruh folder html yang ingin dideploy.

## CSS
CSS adalah singkatan dari **Cascading Style Sheets**, CSS digunakan untuk mendesain halaman website.
Dengan CSS, kita bisa mengubah warna, menggunakan font custom, editing text format, mengatur tata letak, dan lainnya.

### Menyisipkan CSS di HTML
* Inline Styles adalah kita menambahkan CSS pada attribute element HTML.

![CSS](https://github.com/RayaIbensani/CSS/blob/main/Capture.JPG?raw=true)

* Internal Styles adalah kita menyisipkan CSS menggunakan element **< style>**, element < style> berada di di tag **head**

![CSS](https://github.com/RayaIbensani/CSS/blob/main/html.JPG?raw=true)
![CSS](https://github.com/RayaIbensani/CSS/blob/main/html1.JPG?raw=true)
 
* External Styles adalah kita menyisipkan CSS dengan cara membuat file CSS terpisah, dan lalu menyambungkannya dengan file HTML dengan menggunakan element < link>. Element < link> tersebut diletakkan di dalam element < head>.

![CSS](https://github.com/RayaIbensani/CSS/blob/main/html2.JPG?raw=true)
![css](https://github.com/RayaIbensani/CSS/blob/main/html3.JPG?raw=true)

### Sintaks CSS
 Seperti yang dicontohkan di External, h1
 {background-color: bisque} adalah **sintaks css**, syntaks digunakan untuk memilih HTML element mana yang ingin diberi style. CSS syntax terdiri dari **selector, property, dan value**.
, jadi h1 adalah **selcetor**, background-color adalah **property** dan bisque adalah **value**

### Styling CSS
* Memberi style pada semua element yang ada di dalam suatu element.

![CSS](https://github.com/RayaIbensani/CSS/blob/main/html6(1).JPG?raw=true)
![css](https://github.com/RayaIbensani/CSS/blob/main/html4.JPG?raw=true)
![css](https://github.com/RayaIbensani/CSS/blob/main/html6.JPG?raw=true)

* Memberi style di Element dengan Nama id Tertentu

![CSS](https://github.com/RayaIbensani/CSS/blob/main/html7(1).JPG?raw=true)
![css](https://github.com/RayaIbensani/CSS/blob/main/html5.JPG?raw=true)

* Memberi style pada Element dengan Nama class Tertentu

![CSS](https://github.com/RayaIbensani/CSS/blob/main/html9(1).JPG?raw=true)
![css](https://github.com/RayaIbensani/CSS/blob/main/html8.JPG?raw=true)
![css](https://github.com/RayaIbensani/CSS/blob/main/html9.JPG?raw=true)

### Flexbox
Flexbox adalah cara untuk mengatur layout. Flexbox memiliki kemampuan untuk menyesuaikan layout secara otomatis.
Flexbox direkomendasikan karena penggunaannya yang mudah dan didukung oleh kebanyakan browser.

Flexbox memiliki 1 parent/container dan bisa beberapa child/item.

![CSS](https://github.com/RayaIbensani/CSS/blob/main/css6.JPG?raw=true)

yang ada ditengah-tengah(berwarna oren) adalah **child/item**

Codenya seperti dibawah

![css](https://github.com/RayaIbensani/CSS/blob/main/css4.JPG?raw=true)
![css](https://github.com/RayaIbensani/CSS/blob/main/css5.JPG?raw=true)

* Flex-direction
 digunakan untuk mengatur letak **item child**. ada 4 value flex-direction yang harus kamu ketahui:
 1. **row (default)**: secara default letak item child membentuk sebuah baris dari kiri ke kanan.
2. **row-reverse**: letak item child membentuk sebuah baris dari kanan ke kiri
3. **column**: letak item child membentuk sebuah baris dari atas ke bawah
4. **column-reverse**: letak item child membentuk sebuah baris dari bawah ke atas

* Flex-wrap
digunakan untuk membatasi jumlah **item child** dalam 1 line lalu **item child** yang lain akan pindah ke posisi line yang baru. flex-wrap memiliki 3 value:
1. **No-wrap** (default): secara default , flex tidak menggunakan flex-wrap
2. **Wrap**: flex item akan memiliki beberapa line dari atas ke bawah  jika space dalam 1 line sudah full width.
3. **Wrap-reverse**: kebalikan dari wrap yaitu lex item akan memiliki beberapa line dari bawah ke atas  jika space dalam 1 line sudah full width.

* Flex-flow digunakan untuk shortcut untuk set up **flex-direction** dan **flex-wrap** bersamaan,
ada 4 value pada flex-flow:
1. Row nowrap
2. Column wrap
3. Column reverse
4. Row-reverse wrap-reverse

* Order
digunakan untuk ordering item mana yang ingin kita atur posisinya berdasarkan urutan order.
ada 3 value dari properti order:
1. -1 : Item child yang di set order -1, maka item child tersebut akan berada di ordering paling awal atau paling kiri.
2. 0 (default) : Flex secara default memiliki order 0 pada setiap item child. Ini berarti 0 akan membuat item child sesuai urutan pada html.
3. 1: Item child yang di set order 1, maka item child tersebut akan berada di ordering paling akhir atau paling kanan.

### Alignment

* Justify-content digunakan untuk mengatur tata letak dan space antar **item child** secara **horizontal** atau **main axis**.
Justify-content memiliki 6 value yaitu:
1. flex-start
2. flex-end
3. center
4. space-between
5. space-around
6. space-evenly

* Align-content
digunakan untuk mensejajarkan garis flex contaimer ketika ada ruang kosomg secara garis tegak lurus pada sumbu utama (**cross-axis**). Aligncontent memiliki value:
1. flex-start
2. flex-end
3. center
4. space-between
5. space-arround
6. space-evenly
7. stretch

* Align-items
digunakan untuk mengatur align dari item child secara vertikal atau cross axis.
justify-content memiliki 5 value:
1. flex-start
2. flex-end
3. center
4. baseline
5. stretch

* Align-self digunakan untuk mengatur align item pada masing-masing item.
align-self memiliki 5 value yang sama dengan align-items:
1. flex-start
2. flex-end
3. center
4. baseline
5. stretch

### Flexibility
* Flex-grow dapat mengatur size suatu **item child** pada flexbox.
value dari properti flex-grow adalah **number** dan tidak boleh negatif.

* Flex-shrink digunakan membuat size suatu **item child** mengecil secara relatif terhadap item child yang lainnya.
value dari properti flex-shrink adalah **number**. Number negatif dianggap tidak valid.
semakin besar value number dari properti ini, maka semakin kecil size dari suatu **item child**.

* Flex-basis digunakan mengatur **width** dari setiap **item child**.
jika kita telah menggunakan width, maka flex-basis akan melakukan override properti **width**.
namun flex-basis tidak akan berjalan jika kita telah menggunakan **min-width dan max-width**.
properti flex-basis memiliki value:
1. auto
2. number
3. initial
4. inherit


## Algoritma
Algoritma adalah deskripsi berupa step-step yang dibutuhkan untuk menyelesaikan suatu masalah. Algoritma harus mempunyai **input dan output**. Perbedaan algoritma dan data struktur adalah, data struktur digunakan untuk sebuah data dan algoritma yang akan menyelesaikan masalah dengan data itu. Jadi manfaat dari Algoritma dan struktur data adalah mempermudah suatu masalah yang terlihat rumit menjadi mudah.


### Algoritma sederhana
Contoh kita ingin mencari hasil dari y = x3 + 8
1. Mulai
2. Menyediakan variable untuk x dan hasil
3. Hitung nilai y = X3 + 8
4. Cetak hasil
6. Selesai

### Pseudocode
Pseudocode adalah menuliskan algoritma dengan bahasa inggris sebelum kita implementasikan ke bahasa pemograman tertentu.

Contoh Pseudocode

    STORE "No.1" WITH ANY VALUE
    STORE "No.2" WITH ANY VALUE
    STORE "result" WITHOUT ANY VALUE

    CALCULATE "No.1" TIMES "No.2"
    SET "result" VALUE WITH CALCULATION RESULT
    DISPLAY "result"

* Conditional
digunakan saat dibutuhkan percabangan kasus. Komputer akan melakukan suatu tindakan jika suatu kondisi terpenuhi.

Contoh Conditional

    IF "the weather is sunny"
      DO "Let's go play outside"
    Else
      DO "Let's stay at home"

* Looping
digunakan untuk membuat perulangan dalam kasus tertentu.

Contoh Looping

    STORE i WITH 1
     WHILE i LESS OR EQUAL THAN 8 
       DISPLAY 'i'
    SET i WITH i PLUS 3
      END WHILE 

### Algoritma menggunakan JavaScript
Menerapkan suatu algoritma menggunakan Java script,

Jika kita menuliskannya dengan pseudocode seperti ini:

      STORE i AS NUMBER WITH VALUE 0
      WHILE i < 5
     ...
      SET i TO i + 1
      END WHILE

Sedangkan jika kita menulisnya menggunakan JavaScript seperti ini:

      var i = 0;
       while (i < 5) {
       i++;
       }


























