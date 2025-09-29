# 1. membuat dokumen HTML
![lab2 1](https://github.com/user-attachments/assets/dbfa4bb4-62ff-4a08-ad5c-7f6ea17d0308)
     
     struktur dasar dokumen HTML
# 2.CSS internal (di dalam <head)
![lab2 2](https://github.com/user-attachments/assets/f61272b7-c4a9-4e8d-b398-f5535be4e5f1)

     Ditulis dalam tag <style> di bagian head:
# 3.Menambahkan inline css
![lab2 3](https://github.com/user-attachments/assets/7cd5b14f-3f2d-4754-8419-2c072809116a)

     CSS langsung pada elemen menggunakan atribut style:
# 4.Membuat css eksternal 
![lab2 4](https://github.com/user-attachments/assets/e25245c6-18f9-480e-bb7a-745126e365f3)

     Buat file baru misal style.css:
     Lalu hubungkan di HTML:
     html<head>
     <link rel="stylesheet" href="style.css">
     </head>
# 5.Menambahkan css selector
![lab2 5](https://github.com/user-attachments/assets/7a350001-d185-4942-80d2-e778d72b9bee)

     Cara memilih elemen HTML untuk diberi style:

     Selector Elemen: h1 { color: blue; } → semua tag h1
     Selector Class: .nama-class { color: red; } → elemen dengan class="nama-class"
     Selector ID: #nama-id { color: green; } → elemen dengan id="nama-id"
     Selector Universal: * { margin: 0; } → semua elemen
     Selector Gabungan: h1, h2, p { color: black; } → beberapa elemen sekaligus
