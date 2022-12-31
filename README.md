# Cara coding rumus matematika dipython menggunakan modul math

Misalnya seperti menghitung akar kuadrat, pangkat, log, sin, cos, tan, dan lain-lain.

Ini bisa saja dibuat dengan operator dan beberapa variabel.

Tapi itu tidak mudah…

Karena, Kita harus memikirkan sendiri algoritmanya.
![akar](https://user-images.githubusercontent.com/115479895/210149528-38102af1-0119-498c-ae61-7615391105ea.png)

# Apa itu Modul math pada Python?
Modul math adalah modul yang menyediakan fungsi-fungsi matematika dasar untuk digunakan pada operasi matematika sederhana.

Modul math juga memiliki beberapa konstanta seperti pi, e, tau, inf yang bisa kita manfaatkan dalam pembuatan rumus.

Contoh rumus luas lingkaran (π × r²):

import math

def luas_lingkaran(r):

    return math.pi * r**2
    
Untuk dapat menggunakan fungsi-fungsi dan konstanta dari modul matematika, kita harus mengimpornya terlebih dahulu.
Mari kita lihat ada fungsi apa saja di dalam modul ini. Buka intepreter python, kemudian ketik perintah ini:
![Screenshot (158)](https://user-images.githubusercontent.com/115479895/210149617-f77d5134-a510-4a69-969f-db18e8eefd15.png)

Ini adalah fungsi-fungsi yang bisa kita manfaatkan untuk membuat program.

Selanjutnya, untuk mendapatkan penjelasan lebih lanjut tentang fungsi-fungsi ini, silahkan ketik perintah:

help(math)
![image](https://user-images.githubusercontent.com/115479895/210149810-66c7e606-39d4-4580-bd61-84ed285fc217.png)

# Konstanta pada Modul math
Modul math memiliki beberapa konstanta yang bisa kita gunakan dalam pembuatan rumus matematika.

math.pi merupakan konstanta untuk π = 3.141592…
math.e merupakan konstanta untuk e = 2.718281…
math.tau merupakan konstanta untuk τ = 6.283185… Tau adalah konstanta untuk lingkaran yang sama dengan 2π.
Konstanta math.inf merupakan konstanta untuk nilai tak terhingga (infinity)
math.nan merupakan konstanta untuk nilai bukan angka (NaN) atau Not a Number.

# Fungsi Pembulatan Nilai di Python
Ada dua fungsi di modul math yang bisa kita pakai untuk pembulantan nilai, yakni:

ceil() dibulatkan ke atas (contoh: 3.9 jadi 4)
floor() dibulatkan ke bawah (contoh: 3.2 jadi 3)
Biar paham, mari kita coba contohnya di shell python:

Contoh pembulatan dengan fungsi ceil()

![Screenshot (159)](https://user-images.githubusercontent.com/115479895/210149869-64296c8a-af3d-48d0-b333-baa3b7be903c.png)

Contoh pembulatan dengan fungsi floor()

![Screenshot (166)](https://user-images.githubusercontent.com/115479895/210150022-7fd5f2fe-6f2a-49ba-9301-f53f45d676d2.png)

Sebenarnya ada satu lagi fungsi untuk pembulatan nilai di Python, yakni fungsi round().

Fungsi round() sudah ada secara default di Python, jadi kita tidak perlu mengimpornya dari modul math.

Contoh fungsi round():

![Screenshot (160)](https://user-images.githubusercontent.com/115479895/210150057-4f6f14af-4bfa-402b-b277-136e1cb8cd6e.png)

Fungsi round() akan membulatkan nilai ke nilai terdekat. Seperti contoh di atas 3.9 dibulatkan jadi 4 dan 3.3 dibulatkan jadi 3.

# Fungsi untuk Membuat Nilai Absolut di Python
Nilai absolut atau mutlak adalah nilai yang selalu positif, artinya nggka boleh negatif.

Contoh:

![Screenshot (162)](https://user-images.githubusercontent.com/115479895/210150128-fdfa1509-07d8-4d02-ac30-821aee6d48e8.png)

Kita punya variabel saldo dengan isi 1000. Nah, secara logika.. saldo nggak mungkin nilainya negatif.

Kalau negatif, berarti dia ngutang donk.. hehe.

Tapi misalnya kita tidak sengaja membuat program yang membuat saldonya menjadi negatif.

Hasil outputnya

![Screenshot (170)](https://user-images.githubusercontent.com/115479895/210150335-7f90b495-fa72-41e1-858f-38339500494c.png)

Lihat, di baris ke-2 kita memberikan nilai topup ke saldonya dengan nilai negatif. Ini akan membuat nilai akhir saldo jadi negatif.

Karena itu, untuk menjaga saldo tetap bernilai positif.. maka kita harus mengeset nilai topup selalu positif.

Caranya gimana?

Caranya bisa dengan fungsi math.fabs().

Contoh:

![Screenshot (164)](https://user-images.githubusercontent.com/115479895/210150356-bececbdf-f05a-43fb-b443-72e570783f82.png)

Hasil outputnya

![Screenshot (172)](https://user-images.githubusercontent.com/115479895/210150468-8eb5bc8c-2045-4f95-a111-32ac3bbab408.png)











