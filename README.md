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


