## cara melampirkan gambar
cara melampirkan gambar bisa dengan cara seperti ini:
![ket gambar](alamat gambar "title") contoh penggunaanya:

![gambar 3](gambar/gambar.png "gambar buah buahan manis")


## cara melampirkan gambar dengan id
kita bisa melampirkan gambar dengan id dengan cara seprti kita lakuakn pada link tulisan

_contohnya_ :

![buah][1] ini akan menjadi ![buah][1] segar


[1]: gambar/gambar.png


## cara melinkan gambar ke alamat
*cara biasa pakai ini*
[menuju](gambar/gambar.png)

*terus jika mengganti menuju dengan tulisan bisa pakai ini
[![ini gambar](gambar/gambar.png)](http:google.com "menuju gambar")


**cara lain**

[<img src="gambar/gambar.png">](http://google.com)



## kita juga bisa melakukan dengan tag html yang berguna untuk melakuakn resize ukuran gambar:

<img src="gambar/gambar.png" width="300px" height="150px">

atau menerapkan sintaks css contohnya

<img src="gambar/gambar.png" class="gambar">

<style>
  .gambar {
    border: 2px solid green;
    width: 100px;
  }
</style>
