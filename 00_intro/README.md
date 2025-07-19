# Module 00 : Introduction / Introduksi
>English Summary in the last section of page

## Tujuan
1. Memahami pengetahuan dasar tentang rangkaian listrik dan komponennya
2. Mengenali beberapa komponen yang akan digunakan dalam projek kali ini
---
## Konsep Dasar Elektronika
### 1. Elektron dan Muatan
Elektron adalah komponen penyusun dasar dari seluruh komponen dan benda-benda yang ada di dunia ini. Tanpa adanya elektron, mekanisme yang ada di dunia ini akan berbeda 180°. Tanpa adanya elektron, tidak akan ada ikatan-ikatan yang terbentuk antar unsur/atom. Tanpa adanya elektron, konsep atau peristiwa kelistrikan tidak akan terjadi, dan peristiwa kelistrikan, sangat berguna bagi keberlangsungan kehidupan di dunia, mulai dari peristiwa petir, alat-alat elektronik yang kita gunakan, otot yang kita gerakan tiap hari, dan mata yang kita gunakan untuk melihat dunia yang indah ini.

Elektron, menurut pemahaman **Bohr Models**, adalah sebuah "bola kecil" yang menyusun sebuah atom tertentu dan terletak di sekeliling inti atom. 
![](https://www.physics-and-radio-electronics.com/electronic-devices-and-circuits/electron-emission/images/whatisatom.png)

Elektron, memiliki muatan negatif, muatan diberi satuan Couloumb (C) dan elektron memiliki nilai muatan sekitar 1.602 x 10<sup>-19</sup> C. Sehingga 1 Couloumb muatan itu setara dengan 6.24 x 10<sup>18</sup> elektron
> Note:
> 1 Couloumb adalah nilai yang benar-benar sangat besar dan hampir tidak ada di dunia nyata
> Sebagai gambaran, kapasitor komersial, hanya memiliki nilai kapasitansi dengan skala satuan µC , nC, dan pC.
 

 sedangkan  proton memiliki muatan positif dengan nilai muatan yang setara dengan elektron. Hal inilah yang menyebabkan muatan antar elektron-proton saling menghilangkan dan membuat atom bersifat netral.
  Muatan inilah yang nantinya akan memengaruhi bagaimana sebuah atom itu berlaku dan nantinya juga akan memengaruhi konsep-konsep kelistrikan dinamis.

### 2. Tegangan (V)
Tegangan, atau beda potensial, atau emf adalah sebuah satuan yang merepresentasikan **seberapa banyak energi atau kerja yang dibutuhkan untuk memindahkan satu couloumb muatan**.
Tegangan bisa terbentuk akibat perbedaan potensial antara 2 titik atau dua tempat tertentu. *maka dari itu disebut dengan potential difference*. 
Nah potensial itu bisa terjadi akibat penumpukan muatan yang sejenis pada suatu tempat dan memiliki nilai yang berbeda dengan tempat lain. Dan kalau memang terdapat perbedaan jumlah muatan, beda potensial akan terbentuk.
 

![Potential difference analogy](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgR71p4PBhxydMASjNEVZlWhR7Woi-4vRbkW-dmJ9QUYD6b_P3jWJViQzkcjZMg0vhq-EoQE7lpUKql4LSyVVLRlgQ7B2GWT2E-OtdvF1rvCEKbCf0jzGVhYmf2JMXiYPID3xr_ZA7-jLs/s1600/capture-20150625-071104.png)
Gambar diatas merupakan sebuah analogi air yang dapat membantu pemahaman dalam konsep perbedaan potensial atau tegangan.

Secara matematis, formula tegangan dapat ditulis sebagai berikut:
   
    V = dω/dQ
    dengan V adalah tegangan (voly), ω adalah energi/kerja 
    dalam satuan Joule (j) dan Q adalah muatan 
    dalam satuan Couloumb (C).

#### Titik Referensi
Mengingat bahwa tegangan itu sendiri adalah beda potensial, jadi yang kita perhatikan adalah perbedaan nilai-nilai di antara dua titik itu sendiri. Nilai tegangan potensial tidak peduli terhadap nilai asli dari tiap titik, dan karena itulah prinsip nilai yang relatif terhadap titik referensi itu berlaku
### 3. Arus (I)
Arus, ya... arus. Jadi simpelnya arus itu adalah satuan yang merepresentasikan banyaknya muatan yang **mengalir** pada satuan waktu. **Ketika terdapat perbedaan potensial, gaya listrik (gaya couloumb) akan terbentuk sehingga akan menyebabkan pergerakan muatan.**
Muatan yang bergerak pada suatu rangkaian (kawat) adalah muatan negatif/elektron.
Namun, perlu diperhatikan, secara konvensional, kita menganggap bahwa **arus listrik itu searah dengan gerak muatan positif** 
![current flow convention](https://www.allaboutcircuits.com/uploads/articles/video_tutorials_2.4_basic_concepts_of_electric_circuits3_.jpg)
> Hal ini tidak lain dan tidak bukan karena tradisi saja. Benjamin Franklin dulu menganggap muatan positif lah yang membawa atau menyebabkan terjadinya fenomena listrik.
Secara matematis, arus dapat direpresentasikan dalam bentuk sebagai berikut:

    I = dq/dt
    
    Dengan I adalah arus (ampere),
    q adalah muatan (couloumb), dan t adalah waktu.

Karena arus itu disebabkan oleh perbedaan potensial, gambar pada bagian tegangan dapat menjadi analogi secara singkat terkait hubungan arus dan tegangan.
### 4. Resistansi (R)
Resistansi, adalah properti hambatan atau halangan yang memengaruhi sifat kelistrikan atau arus dalam suatu rangkaian listrik. resistansi, sangat dipengaruhi oleh bentuk dan material penyusun suatu konduktor. **Semakin tinggi hambatan, maka semakin rendah atau semakin sukar arus untuk mengalir pada suatu komponen atau rangkaian.**
Walaupun hambatan itu terkesan mengganggu dan tidak berguna dalam suatu rangkaian, namun properti hambatan itu banyak digunakan dalam aplikasi rangkaian listrik sebagai pengatur atau pembatas arus dan menjaga alat tetap aman dan stabil.
> Properti ini digunakan dalam komponen listrik seperti resistor ataupun juga potentiometer.

![Voltage, Current, and Resistance Analogy](https://www.build-electronic-circuits.com/wp-content/uploads/2014/09/Ohms-law-cartoon-cropped.jpg)

### 6. Hukum Ohm, Kirchoff
Sifat-sifat kelistrikan, banyak dijabarkan melalui beberapa hukum yang sudah ditemukan, seperti hukum-hukum ohm dan kirchoff.
### Hukum Ohm
Hukum Ohm menyebutkan bahwa ***Sebuah arus yang melalui sebuah komponen resistif nilainya sama dengan tegangan yang melalui komponen tersebut dibagi dengan nilai resistansinya***

Atau, hukum ohm dapat diformulasikan sebagai berikut:
    
    I = V/R
    
    Dengan I adalah arus dalam satuan A (ampere), 
    V adalah tegangan dalam satuan V (volt), dan
    R adalah hambatan dalam satuan Ω (Ohm).

Hukum ini sangat berguna dalam berbagai permasalahan dan sangat mudah dalam memahaminya karena kesederhanaan bentuk dari formula hukum ini.

Dengan hukum ini, terdapat banyak formula-formula lain yang terbentuk berdasarkan penurunan atau manipulasi hukum ini, terlebih lagi kita bisa menemukan nilai daya dan energi dengan pemahaman rumus ini.

![Ohm's Law CheatSheet](https://dou26tiipf5mn.cloudfront.net/production/project_preview/1d560141e8534fb09e645cf8f8e59042/43ccb55af77e4d5a9aa3383c0e9931ec/vnybicnmpt.png)


### Hukum Kirchoff
Hukum kirchoff juga merupakan hukum yang mengatur sifat rangakian listrik, terutama menjabarkan bagaimana arus mengalir dan tegangan berperilaku. Hukum ini sangat berguna dalam menganalisis dan menyelesaikan masalah rangkaian kompleks dan menganalisis raus pada cabang-cabang yang berbeda.
Kirchoff itu sendiri, memiliki 2 hukum, yaitu
#### a. Kirchhoff's Current Law (I)
Hukum pertama Kirchhof menyatakan bahwa ***Total arus yang masuk pada suatu nodus atau simpul itu sama nilainya dengan arus yang keluar dari simpul***.
Artinya ketika terdapat suatu rangkaian dimana terdapat percabangan yang terbentuk, dan terdapatarus yang mengalir melewati simpul tersebut, maka arus akan menyebar masuk dan keluar sedemikian sehingga arus yang keluar nilainya akan sama dengan arus yang masuk (seimbang/balance).

![KCL](https://www.simply.science/images/content/physics/Electricity_magnetism/CE/Concept_map/Kirchoffs_laws.gif)

Secara matematis, hukum pertama ini dapat dinyatakan sebagai berikut:

> Σ I<sub>masuk = </sub> Σ I <sub>keluar</sub>

Hal ini cukup masuk akal mengingat arus yang berisi elektron/muatan yang bergerak perlu jalur agar bisa lewat, dan karena itulah ketika terdapat persimbangan/simpul, elektron akan lewat (masuk dan keluar) dengan jumlah arus/elektron yang sama
#### a. Kirchhoff's Voltage Law (II)
Hukum kedua Kirchhoff, atau bisa disebut dengan hukum Loop, menyatakan bahwa ***jumlah total dari perbedaan potensial (voltage drop and voltage rises) pada suatu loop tertutup bernilai sama dengan nol***.
Artinya adalah, pada suatu rangkaian tertutup, dimana arus akan melalui rangkaian dan komponen-komponen didalamnya, tegangan atau beda potensial yang dikonsumsi (voltage drop) itu akan sama dnegan tegangan yang disuplai (voltage rises). Sifat ini dapat berlaku karena aturan dasar konservasi energi.
![](https://www.simply.science/images/content/physics/Electricity_magnetism/CE/Concept_map/Kirchoffs_laws1.gif)
 
### 7. Power and Energy
Daya adalah satuan yang melambangkan energi yang digunakan tiap satuan waktu. Formulanya dapat dibentuk secara sederhana:

    P = V x I

    Dengan P adalah daya dengan satuan Watt(J/s)

Dan Energy adalah sebuah properti yang bisa menyebabkan sebuah benda itu berubah bentuk maupun bergerak.

    E = P.t

    Dengan E adalah Energi (J)
    P adalah daya (W)
    dan t adalah waktu (s)

### 8. Apa itu Computer
---
## Komponen dasar Elektronika

Dalam sebuah rangkaian listrik, terdapat unsur-unsur yang menyusun dan memiliki karakteristik masing-masing, unsur-unsur inilah yang disebut komponen listrik.

| komponen | Fungsi |
|----------|--------|
|Resistor|Menghambat arus|
|Capacitor|Menyimpan energy dalam bentuk medan listrik|
|Inductor|Menyimpan energy dalam bentuk medan magnet|
|Dioda|Penyearah arus|
|Transistor|switch / penguat tegangan atau arus|
|Breadboard|tempat menyusun rangkaian listrik|
|JumpWire|konduktor rangkaian|

>  bla2
 
---
## Notes

---
# English Summary

## Objective

## Brief Theory

## Tools and Materials

## Circuit Diagram

## Layout Breadboard

## Resulting Test

## Notes


