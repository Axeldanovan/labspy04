# labspy04
Latihan yang pertama adalah membuat list dengan menulis:

list=[] 
(keterangan: list dapat diubah dengan nilai lainnya misal list1, atau nama lainnya)

berikut penulisan dalam python:
![Screenshot_376](https://user-images.githubusercontent.com/81457697/143723540-e0c383f8-f17c-44b5-854d-0a695d6ff274.png)

dengan keterangan:

list=["a", "b", "c", "d", "e"]

-diatas adalah isi list nya
print("Tampilkan Element ke 3:", list[2])

-diatas adalah perintah untuk menampilkan elemen ke 3 dalam list, karena elemen ke 3 ada di index 2, maka didalam list pakai kurung siku[2]
print("ambil Element ke 2 sampai 4:", list[1:4]) 

-diatas untuk perintah untuk mengambil elemn ke 2 sampai ke 4 dengan index elemen ada di index 1 sampai 4
print("ambil elemen terakhir:", list[5-1])

sedangkan diatas ini adalah perintah untuk mengambil elemen terakhir, karena di dalam list ada 5 elemen, maka digunakan -1 untuk mengambil elemen terakhir

# merubah elemen ke 4 dengan nilai lain
list[3] = "f" 

-sedangkan ini untuk merubah elemen ke 4 dengan nilai F, karena elemen ke 4 ada di index 3, maka ditulis list[3]
print("merubah elemen ke 4 dengan nilai lain:", list)

-merubah elemen ke 4 sampai terakhir
list[3:] = "f", "g" 

-ini untuk merubah elemen ke 4 sampai terakhir dengan string "f" dan "g". maka ditulis list[3:]
print("merubah elemen ke 4 sampai elemen terakhir:", list)

# hasil output program 
![outputlist](https://user-images.githubusercontent.com/81457697/143723667-3938f848-6ccb-42c2-8281-3c192278418a.png)

# latihan untuk menambahkan elemen dalam list
berikut input nya
![inputlistambahan](https://user-images.githubusercontent.com/81457697/143723856-c0937a76-7cd1-4128-934c-d135926784d4.png)

# tambah elemen list
a=[1,2,3,4,5]
b=[6,7,8,9,10]

-diatas adalah untuk membuat 2 list

# Ambil 2 bagian list A ke list B
b.append(a[1:3])
print("2 bagian List A dijadikan List B:", b)

-diatas adalah code untuk menambahkan list A kedalam list B dengan menggunakan perintah append

# tambah list b dengan string
b.append("saya")
print("Tambah B dengan Sring:", b)

-diatas adalah untuk menambahkan list B dengan string menggunakan append

# tambah list b dengan 3 nilai
print("Tambah list b dengan 3 nilai:", b+[11,12,13])

-diatas adalah untuk menambahkan list b dengan 3 nilai dengan menggunakan arithmatic +

# Gabungan List B dan A
c=b+a
print("Gabungan list B dan A:", c)

-dan yang di atas ini adalah untuk menggabungkan list B dan list A, menjadi list C

# hasil output program nya
![outputlisttambahan](https://user-images.githubusercontent.com/81457697/143723804-f8bc1947-86b1-4865-b861-6db97f3303b7.png)

#praktikum labs 4

# membuat list nilai mahasiswa

