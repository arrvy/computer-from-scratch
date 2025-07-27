# Module 02 : Logic Gates / Gerbang Logika
>English Summary in the last section of page

## Tujuan
1. Mengetahui jenis-jenis gerbang logika dan keunikannya
2. Mengetahui tabel kebenaran pada tiap-tiap gerbang logika
3. Mengetahui susunan rangkaian elektris tiap gerbang logika dan drawbacknya
---
## Brief Theory
### Pengantar tentang logika boolean
Logika boolean adalah seperangkat aturan logika yang **bekerja berdasar pada aturan aljabar boolean**. Logika ini bekerja dengan membagi kondisi-kondisi kebenaran **berdasarkan 2 state**, True/False, 1/0, High/Low, dan lain lain.

Logika boolean sangatlah penting dalam sistem digital karena rangkaian itu sendiri dibuat agar bekerja pada 2 kondisi yang terdefinisi, HIGH (3.3V,5V,dll) dan juga low (0V). Dengan aturan seperti ini pula, **rangkaian listrik akan lebih sederhana** dibandingkan ketika misalnya kita perlu mendefinisikan 10 state yang berbeda untuk merepresentasikan bilangan desimal/bilangan manusia langsung. 
Keuntungan lain dalam menerapkan logika boolean adalah **rangkaian yang cepat** dalam memproses perhitungan, **dapat diandalkan** karena minim error, maupun juga **konsisten**.
Untuk itu, kita memerlukan semacam definisi untuk mendeskripsikan keputusan-keputusan logika itu yang relatif mudah dicerna oleh manusia ke rangkaian-rangkaian listrik yang secara esensi tidak bisa berpikir. Untuk itulah kita memerlukan **gerbang logika** yang berperan sebagai unit terkecil dari sistem digital
> George Boole, pencetus logika boolean, membuat buku berjudul *An Investigation of the Laws of
Thought* yang berisikan tentang cara berpikir dan berlogika berdasarkan kondisi-kondisi alami yang terbagi menjadi dua kondisi (seperti mati dan hidup, on/off,dll)
#### Tabel Kebenaran
Tabel kebenaran adalah sebuah diagram/tabel yang menjelaskan **bagaimana sebuah operator logika ataupun rangkaian logika bekerja dan menghasilkan output berdasarkan input yang diberikan**. Sehingga tabel kebenaran berisi tentang seluruh kemungkinan-kemungkinan unik yang dihasilkan oleh sebuah sistem logika tertentu.   
A|B|x
-|-|-
0|0|1
0|1|1
1|0|1
1|1|0   
> Contoh tabel logika (NAND)

Jumlah dari baris tabel kebenaran ditentukan oleh jumlah input logikanya, jika ada 2 input, terdapat 4 baris. Jika ada 3 input, ada 8. Sehingga dapat kita simpulkan jumlah dari seluruh kemungkinan tabel kebenaran adalah 2<sup>N</sup> kemungkinan

---

### Gerbang Logika
#### 1. AND
Gerbang logika AND adalah gerbang logika yang nilai outputnya 1 **HANYA** ketika keseluruhan input bernilai 1
![](https://www.techtarget.com/rms/onlineimages/diagram1-f.png)
artinya kita membutuhkan nilai seluruh input itu bernilai benar agar nilai outputnya itu benar. Ini bisa kita bayangkan seperti ketika kita memakai konjungsi dan.
Ekspresi boolean dari gerbang ini adalah:
>x = A×B×....
#### 1. OR
Gerbang logika OR adlaah gerbang logika yang nilai outputnya 0 **HANYA** ketika keseluruhan input bernilai 0.
![](https://www.techtarget.com/rms/onlineimages/diagram2-f.png)
Ekspresi boolean dari gerbang OR adalah:
> x = A+B+....
#### 1. NOT
Not, atau biasa disebut dengan inverter (dalam elektro), adalah gerbang logika yang nilai outputnya **BERKEBALIKAN** dengan nilai inputnya. Operasi NOT juga bisa disebut dengan operasi negasi

Ekspresi boolean dari gerbang NOT adalah:
> x = Ā
> atau
> x = ~A
> atau
> x = ¬A
>yang esensinya adalah
> x = -1×A


##### Input dari gerbang logika
Gerbang-gerbang logika sebelumnya bekerja pada berbagai input yang diberikan. NOT, hanya bekerja pada 1 input. **OR dan AND, bisa bekerja pada 2 input atau lebih**. Secara rangkaian listrik, kita bisa mendapatkan gerbang AND/OR lebih dari 2 input dengan memasangkan output gerbang itu ke input gerbang yang lain.(combining logic gates).
![](https://graphicmaths.com/img/computer-science/logic/combining-logic-gates/3-and-gate.png)

#### Gerbang Logika Dasar
Gerbang logika dasar adalah gerbang yang memiliki kemampuan berdasarkan tabel kebenarannya untuk menghasilkan semua gerbang-gerbang logika yang lain. Gerbang logika tersebut adalah
AND, OR, dan NOT. Dengan gerbang itu, kita bisa membuat konsep gerbang lain, misalnya NAND diambil dari NOT dan AND, NOR dari NOT dan OR. dan lain sebagainya.

#### Gerbang Logika Universal
Sedangkan, gerbang logika universal, adalah gerbang logika yang **secara rangkaian listrik bisa digunakan untuk menyusun fungsi-fungsi gerbang lain** bahkan gerbang dasar sekalipun. Gerbang tersebut adalah NAND and NOR.
Hal ini disasarkan atas pertimbangan-pertimbangan berikut:
- lebih mudah direalisasikan dalam rangkaian/hardware
- Lebih hemat SDA dibandingkan menyusun dari konsep gerbang dasar langsung
- Lebih terstandarisasi dalam dunia industri
  
Contohnya adalah, gerbang NAND sendiri dapat digunakan untuk menyusun gerbang-gerbang logika lain seperti XOR,XNOR,dan bahkan gerbang dasar dengan lebih hemat sumber daya karena gerbang logika **NAND itu sendiri bisa didapatkan tanpa menyusun dari AND dan OR secara bersama2**.

#### 1. NAND
#### 1. NAND

### Tabel kebenaran dari masing-masing gerbang

### Gambaran umum penggunaan di dunia nyata (contoh: komputer, saklar otomatis, sensor logika)

### Sedikit penjelasan pendekatan: IC Logic (misal 74xx series) Discrete logic pakai transistor (kalau kamu buat dari NPN juga)

---
## Tools and Materials
- Breadboard
- Kabel jumper
- Resistor (220Ω, 1kΩ, 10kΩ, dll)
- LED
- Push button
- Transistor NPN (misal 2N3904)
- Gunting/Cutter
- Tweezer

---
## Circuit Diagram

Disini, aku bakalan pakai aplikasi simulasi Falstad. Meskipun kurang nyata, simulasi ini sangatlah cukup bagi kebutuhanku dalam menjelaskan secara sederhana rangkaian dan hasil dari logic gates dasar.

NAMA | RANGKAIAN
-----|---
NOT |![alt text](image.png)
AND |![alt text](image-1.png)
NAND |![alt text](image-2.png)
OR |![alt text](image-3.png)
NOR |![alt text](image-4.png)
XOR |
XNOR |
---
## Layout Breadboard
---
## Resulting Test
---
## Notes

---
---
# English Summary

## Objective

## Brief Theory

## Tools and Materials

## Circuit Diagram

## Layout Breadboard

## Resulting Test

## Notes


