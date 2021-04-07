# Lab2Web
Assalamualaikum. Ini merupakan pratikum website saya untuk memenuhi tugas mata kuliah Pemrograman Web

1. [MEMBUAT DOKUMEN] Ini adalah tampilan codingan awal untuk membuat dokumen HTML dengan menggunakan style css

    ![1](https://user-images.githubusercontent.com/59683573/113685444-77228300-96f0-11eb-84c4-22922495f12b.png)

2. Hasil/Tampilan ketika dijalankan dibrowser, maka terlihat adanya judul pada elemen head, judul pada heading 1, hyperlink dll pada bagian elemen body

    ![2](https://user-images.githubusercontent.com/59683573/113685727-be107880-96f0-11eb-91ba-233245e3dff8.png)

3. Mendeklarasikan CSS Internal] Ini adalah tampilan codingan jika ditambahkan deklarasi CSS internal pada bagian head dokumen dengan menambahkan property dan nilai dalam          elemenn body, header, h1 dan hi

   ![3](https://user-images.githubusercontent.com/59683573/113685993-ffa12380-96f0-11eb-994a-413ba37c9e2e.png)

4. Hasil/Tampilan ketika dijalankan dibrowser, maka hasilnya terlihat dokumen tersebut sudah terdeklarasikan pada bagian elemen body, header, dan heading

   ![4](https://user-images.githubusercontent.com/59683573/113686042-0def3f80-96f1-11eb-9d0f-a1a0ad2876a5.png)

5. [Menambahkan Inline CSS] Ini adalah tampilan codingan jika ditambahkan deklarasi inline CSS pada tag p seperti berikut;

   ![5](https://user-images.githubusercontent.com/59683573/113686204-35460c80-96f1-11eb-94b8-d299e38506d9.png)

6. Hasil/Tampilan ketika dijalankan dibrowser, maka terlihat adanya perubahan warna text pada paragraf dan rata text menjadi rata tengah dengan menambahkan property text-align      nilai rata tengah, dan property color nilai warna abu-abu.

   ![6](https://user-images.githubusercontent.com/59683573/113686336-5a3a7f80-96f1-11eb-870a-5ef60a5259a0.png)

7. [Membuat CSS Eksternal] Ini adalah tampilan codingan jika ditambahkan deklarasi CSS dengan membuat file baru untuk CSS Eksternal dan menambahkan tag link pada bagian elemen      head didokumen HTML

   ![7](https://user-images.githubusercontent.com/59683573/113686536-8eae3b80-96f1-11eb-8e26-5dd48bdfd3be.png)

8. Hasil/Tampilan ketika dijalankan dibrowser, maka;

   ![8](https://user-images.githubusercontent.com/59683573/113686607-a259a200-96f1-11eb-83b1-164d77200b16.png)

9. [Menambahkan CSS Selector] Ini adalah tampilan codingan jika ditambahkan CSS Selector menggunakan ID dan Class Selector pada file CSS eksternal
   ![9](https://user-images.githubusercontent.com/59683573/113686726-c5845180-96f1-11eb-8119-09b602f2970d.png)

10.Hasil/Tampilan ketika dijalankan dibrowser, maka perubahannya text tersebut menjadi berwarna dengan menambahkan property dan nilai berupa background untuk mengatur warna,        border, min-height, padding, text-align, color, display, margin dan text-decoration, dan link tersebut berubah menjadi berwarna yang menandakan bahwa tag link tersebut telah    diterapkan pada file css  

   ![12](https://user-images.githubusercontent.com/59683573/113687121-362b6e00-96f2-11eb-86a5-6df00ac0be8d.png

   

   

Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

Jawaban:

[1] Ini adalah tampilan codingan jika ditambahkan deklarasi CSS dengan mengubah/membuat property dan nilai pada kode css

   ![13](https://user-images.githubusercontent.com/59683573/113704690-ad6afd00-9706-11eb-821a-2152f04b1e36.png)

   ![14](https://user-images.githubusercontent.com/59683573/113704720-b9ef5580-9706-11eb-8aa0-977ba3ba98aa.png)

[2] Hasil/Tampilan ketika dijalankan dibrowser, maka terlihat perubahannya dari yang sebelumnya, untuk heading 1 terlihat text tersebut berbayang dan berwarna biru, dan link         tersebut terlihat garis bawah pada text, heading 1 pada bagian elemen body text tersebut menjadi rata tengah, dan border menjadi lebih tebal

   ![15](https://user-images.githubusercontent.com/59683573/113704835-de4b3200-9706-11eb-83fd-44729d271b45.png)


2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!

   Jawaban:

   perbedaannya yaitu elemen h1 untuk mengubah nilai text pada dokumen html yg menggunakan tag h1 pada elemen-elemen dan intro h1 untuk mengubah nilai text yg ada pada selector    h1 di dokumen html agar property terlihat jauh lebih menarik difile css



3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan    penjelasan dan contohnya!

   Jawaban:
   
   Penulisan CSS dapat dilakukan dengan tiga cara, yaitu penulisan secara internal, external dan inline.
   Internal adalah kode CSS ditulis pada dokumen HTML pada bagian head dokumen. External CSS
   adalah kode CSS ditulis terpisah dengan dokumen HTML berupa file Style Sheet (.css). Sedangkan
   Inline CSS adalah kode CSS ditulis sebagai artribut pada tag HTML.
   contoh internal :
   ![Screenshot (191)](https://user-images.githubusercontent.com/59683573/113877112-9568ab80-97e2-11eb-917d-1cc4dcaa27f8.png)
   
   contoh eksternal :
   ![Screenshot (192)](https://user-images.githubusercontent.com/59683573/113877246-b92bf180-97e2-11eb-9ca6-720d3357def2.png)
   
   contoh inline :
   ![image](https://user-images.githubusercontent.com/59683573/113877347-d234a280-97e2-11eb-8283-5a7c5e5b9071.png)



4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
   terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
   Berikan penjelasan dan contohnya!

   Jawaban:
   Elemen Selector dideklarasikan berdasarkan tag HTML. 
   CSS Selector dapat berupa elemen HTML, selector class atau selector id. Penggunaan CSS selector
   disesuaikan dengan kebutuhannya. Elemen selector akan berlaku pada semua elemen tersebut.
   Untuk class dan id selector, akan berlaku pada elemen yang menggunakan class atau id tersebut.
   
   contoh class selector
   ![Screenshot (194)](https://user-images.githubusercontent.com/59683573/113877852-496a3680-97e3-11eb-8784-951d4d786034.png)
   
   contoh id selector
   ![Screenshot (195)](https://user-images.githubusercontent.com/59683573/113877901-5424cb80-97e3-11eb-9077-5b33156bf64a.png)


   
