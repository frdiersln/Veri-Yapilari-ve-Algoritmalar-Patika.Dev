# Veri-Yapilari-ve-Algoritmalar-Patika.Dev
Patika.dev - Veri Yapıları ve Algoritmalar eğitimi için yüklenmiştir.
<hr>
[16,21,11,8,12,22] -> Merge Sort
<br> <br>
Merge Sort: diziyi ardışık olarak en küçük alt dizilerine kadar yarılayan sonra da onları sıraya koyarak bireştiren özyineli bir algoritmadır. Yarılama işlemi en büyük alt dizi en çok iki öğeli olana kadar sürer. Sonra "Merge (Birleştirme)" işlemiyle altdiziler ikişer ikişer bölünüş sırasıyla sıralı olarak bir üst dizide bireşir. Süreç sonunda en üstte sıralı diziye ulaşılır.
<br> <br>
başlangıç: [16,21,11,8,12,22] => 1. aşama: [16,21,11] [8,12,22] => 2. aşama: [16] [21,11] [8,12] [22] => 3. aşama: [16] [21] [11] [8] [12] [22] => 4. aşama: [16] [11,21] [8,12] [22] => 5. aşama: [11,16,21] [8,12,22] => 6. aşama: [8,11,12,16,21,22]
<hr>
Big-O gösterimini yazınız.
<br> <br>
O(6*(log6))
<hr>
www.patika.dev
