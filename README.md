# -LT-21_Ternary_Operator

Ternary operator dalam JavaScript adalah operator yang digunakan untuk menentukan kondisi dari sebuah ekspresi. Operator ini memiliki tiga bagian: kondisi, ekspresi jika kondisi benar, dan ekspresi jika kondisi salah. Operator ini disajikan dalam bentuk:

    kondisi ? ekspresi1 : ekspresi2;

Jika kondisi bernilai true, maka ekspresi1 akan dievaluasi dan dihasilkan, jika kondisi bernilai false, maka ekspresi2 yang akan dievaluasi dan dihasilkan. Contoh :

    let age = 25;
    let canDrinkAlcohol = (age >= 21) ? "can drink" : "cannot drink";
    console.log(canDrinkAlcohol); // "can drink"

Dalam contoh di atas, operator ternary digunakan untuk menentukan apakah seseorang dapat minum alkohol atau tidak berdasarkan usia mereka. Jika usia lebih besar sama dengan 21, ekspresi "can drink" akan dihasilkan, jika tidak, ekspresi "cannot drink" akan dihasilkan.

Ternary operator ini sangat berguna untuk menulis kode yang lebih singkat dan mudah dibaca, dan sering digunakan untuk menentukan kondisi dalam pernyataan if-else yang singkat.

Secara keseluruhan, Ternary operator adalah alat yang berguna untuk menentukan kondisi dari sebuah ekspresi dan mempermudah pengkodean dengan menulis kode yang lebih singkat dan mudah dibaca.

Selain itu, operator ternary juga dapat digunakan dalam kombinasi dengan operator lain untuk menulis ekspresi yang lebih kompleks. Contohnya:

    let age = 25;
    let canDrinkAlcohol = (age >= 21) ? "can drink" : (age < 18) ? "too young" : "cannot drink";
    console.log(canDrinkAlcohol); // "can drink"

Dalam contoh di atas, operator ternary digunakan dalam kombinasi dengan operator ternary lainnya untuk menentukan apakah seseorang dapat minum alkohol atau tidak berdasarkan usia mereka. Jika usia lebih besar sama dengan 21, ekspresi "can drink" akan dihasilkan, jika usia kurang dari 18 ekspresi "too young" akan dihasilkan dan jika tidak, ekspresi "cannot drink" akan dihasilkan. 

Secara umum, operator ternary dapat digunakan untuk menulis kode yang lebih singkat dan mudah dibaca, namun perlu diingat bahwa ekspresi yang terlalu kompleks dapat membuat kode menjadi sulit dibaca dan dipahami. Oleh karena itu, selalu disarankan untuk menjaga kode Anda sederhana dan jelas sambil menggunakan operator ternary.
