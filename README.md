# Lab2Web
```bash
Nama      : Robi Abda'u
NIM       : 311910563
Kelas     : TI.19.B1
M. Kuliah : Pemograman Web
Dosen     : Agung Nugroho,S.Kom.,M.Kom
```
## Jawaban Tugas
**1. Berikut web eksperimen pribadi:**

   Tampilan
   ![Capture](https://user-images.githubusercontent.com/81896427/113501716-88815900-9551-11eb-86a6-14e3ffdab10b.PNG)

   Codingan
   ![coding](https://user-images.githubusercontent.com/81896427/113502907-1745a400-9559-11eb-8c9c-9bf91f927a16.png)
   
**2. Perbedaan pendeklarasian CSS elemen h1 dengan #intro h1**
    
   Perbedaanya yaitu h1 = semua h1 yang ada di dalam dokumen sedangkan #intro h1 = semua h1 yg ada khusus didalam elmen dengan id intro.
   
**3. Yang akan tampil pada browser yaitu inline CSS**

   Penggunaan inline style langsung pada elemen HTML mempunyai prioritas tertinggi. Artinya akan membuat override (“menggantikan”) style yang didefinisikan dalam tag <head> atau yang terdapat pada internal style, eksternal style sheet maupun browser secara default.
   
   Untuk Eksternal CSS dan Internal CSS mempunyai prioritas yang sama. Tergantung dimana yang terakhir akan menggantikan aturan sebelumnya. Untuk Contohnya sebagai berikut:
   
   **File Style_Eksternal.css:**
   
   ![contoh_eksternalstyle](https://user-images.githubusercontent.com/81896427/113504929-c0929700-9565-11eb-8d9b-f77f21ca25ad.PNG)

   **Internal CSS:**
   
   ![contoh_internalstyle](https://user-images.githubusercontent.com/81896427/113505375-a5755680-9568-11eb-8eb4-f8169c0c2ac8.PNG)

   **-Eksternal CSS Pertama dan Internal CSS Terakhir:**
  
   ![Eksternal terlebih dahulu](https://user-images.githubusercontent.com/81896427/113505513-875c2600-9569-11eb-82ff-42e050e54699.PNG)
   
   **Output:**
   
   ![OutputEksternaldulu](https://user-images.githubusercontent.com/81896427/113505660-79f36b80-956a-11eb-9d04-e6986659242f.PNG)
   
   Kalimat "Hello World" berwarna putih dan berada di seblah kiri, mengikuti deklarasi css Eksternal.
   Dan sebaliknya tergnatung dimana yang terkahir.
   
   **Berikut Contoh Inline CSS:**
   
   ![Contoh_inlineCSS](https://user-images.githubusercontent.com/81896427/113506215-a9f03e00-956d-11eb-8c79-b0342d38ac82.PNG)
   
   Saya contohkan penrapannya pada kalimat "Hello World"
   
   **Untuk membuktikan bahwa yang akan tampil pada browser yaitu inline CSS, berikut contohnya apabila tiga-tiganya di gabungkan:**
   
   ![Digabung33nya](https://user-images.githubusercontent.com/81896427/113506441-1d467f80-956f-11eb-8c85-a18fa1fe0f91.PNG)
   
   **Output:**
   
   ![Output33nyadigabung](https://user-images.githubusercontent.com/81896427/113506581-e1f88080-956f-11eb-8175-5682f68204c9.PNG)

   Kalimat "Hello World" berubah warna menjadi merah, mengikuti deklarasi Inline CSS.
   
   
 **4. Dua-duanya akan tampil**
 
  ID berfungsi untuk menentukan identitas unik suatu elemen. Jadi nilai yang diberikan haruslah unik, unik di sini artinya kita tidak diizinkan membuat lebih dari satu id dengan nilai yang sama.
  Sedangkang Class berfungsi untuk menentukan nama class dari suatu elemen. Berbeda dengan id yang bersifat unik, class diperbolehkan untuk digunakan oleh lebih dari satu elemen yang ditandainya.
  
  **Contohnya:**
  
   ![ID_Class](https://user-images.githubusercontent.com/81896427/113509243-b4ff9a00-957e-11eb-9d00-f75a8be0d9c5.PNG)
   
   **Output:**
   
   ![Tampilan](https://user-images.githubusercontent.com/81896427/113509714-5556be00-9581-11eb-9c03-2868d57d69ee.PNG)

  
  
  
  ## Laporan Praktikum 2
  
  **1. Membuat Dokumen HTML**
  
  Sebagai berikut:
  
  ![cod1](https://user-images.githubusercontent.com/81896427/113510030-c6e33c00-9582-11eb-9d4c-6ea44d6bb117.PNG)
  
  Selanjutnya buka pada brwoser untuk melihat hasilnya. Untuk SublimeText bisa langsung klik kanan Open Browser.
  
  ![cod1hasil](https://user-images.githubusercontent.com/81896427/113510156-964fd200-9583-11eb-8c2f-b8372f129adb.PNG)

  **2. Mendeklarasikan CSS Internal**
  
  Sebagai berikut:
  
  ![cod2](https://user-images.githubusercontent.com/81896427/113510222-08281b80-9584-11eb-9f3c-2cabb95f9774.PNG)

  Penulisan Internal CSS menggunakan tag <style> yang diletakkan pada <head> dokumen.
  
  Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

  ![cod2hasil](https://user-images.githubusercontent.com/81896427/113510371-cba8ef80-9584-11eb-8359-1c17d83e9336.PNG)
  
  
  **3. Menambahkan Inline CSS**
  
  Kemudian menambahkan deklarasi inline CSS pada tag < p > seperti berikut:
  
  ![cod3](https://user-images.githubusercontent.com/81896427/113510472-2d695980-9585-11eb-9700-f7b747f332d2.PNG)

  Inline CSS dengan menambahkan kode CSS pada tag HTML sebagai atribut dan value. Penempatan CSS secara inline hanya akan mempengaruhi satu bagian baris kode.
  
  Simpan kembali dan refresh kembali browser untuk melihat perubahannya.
  
  ![cod3hasil](https://user-images.githubusercontent.com/81896427/113510542-9cdf4900-9585-11eb-8da8-f31a52670555.PNG)
  
  **4. Membuat CSS Eksternal**
  
  Membuat file baru dengan nama style_eksternal.css kemudian membuat deklarasi CSS seperti berikut.
  
  ![cod4css](https://user-images.githubusercontent.com/81896427/113510654-0cedcf00-9586-11eb-999c-2f55c0abe660.PNG)
  
  Penulisan Eksternal CSS menggunakan tag <link> menggunakan atribut href untuk merujuk kepada file css yang diletakkan pada <head> dokumen.
  
  Kemudian tambahkan tag <link> untuk merujuk file css yang sudah dibuat pada bagian <head>
  
  ![cod4](https://user-images.githubusercontent.com/81896427/113510781-92717f00-9586-11eb-9684-16e4828f2f52.PNG)

  Selanjutnya refresh kembali browser untuk melihat perubahannya.
  
  ![cod4hasil](https://user-images.githubusercontent.com/81896427/113510797-ae752080-9586-11eb-8580-d6cde46d9941.PNG)
  
  **5. Menambahkan CSS Selector**
  
  Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file style_eksternal.css, menambahkan kode berikut.
  
  ![cod5css](https://user-images.githubusercontent.com/81896427/113510895-3529fd80-9587-11eb-9df9-b452b7501321.PNG)
  
  Kemudian simpan kembali dan refresh browser untuk melihat perubahannya.
  
  ![cod5hasil](https://user-images.githubusercontent.com/81896427/113510939-74584e80-9587-11eb-9092-5a6c86a5f1a2.PNG)

  
  




