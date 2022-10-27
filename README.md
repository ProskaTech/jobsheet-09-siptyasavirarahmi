## Object-oriented Programming (Lab Work) Template Guides

Analisis Job-9:

Pass By Value adalah ketika kita memberikan salinan nilai sebuah variabel sebagai argumen untuk sebuah method. Karena yang diberikan hanya salinan nilainya saja, maka nilai variabel tersebut tidak akan berubah meskipun di dalam method tersebut nilainya berubah karena digunakan untuk melakukan berbagai operasi.

Pass By Reference adalah ketika kita memberikan referensi / pointer ke alamat lokasi variabel yang digunakan sebagai argumen untuk sebuah method. Memberikan referensi ke alamat variabel berarti memberi akses terhadap variabel tersebut. Setiap operasi yang menggunakan referensi tersebut akan merubah nilai variabelnya di stack. Pass By Reference bisa dilakukan dengan menambahkan kata kunci ref.

Metode equals() membandingkan dua String berdasarkan kontennya. Sehingga, apabila dua buah String memiliki huruf-huruf yang sama, diurutan yang sama dan besar-kecil yang sama maka dua String ini akan dianggap sama. Oleh karena itu "Codepolitan" dan "Codepolitan" akan mengembalikan nilai true sedangkan "Codepolitan" dan "CODEPOLITAN" akan mengembalikan nilai false.
