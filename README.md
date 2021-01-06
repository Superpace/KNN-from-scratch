# KNN(K Nearest Neighborhood)

K Nearest Neighborhood (En yakın K komşu) , tembel olması ile bilinen bir makine öğrenmesi algoritmasıdır . "Bana arkadaşını söyle, sana kim olduğunu söyleyeyim" mantığında çalışmaktadır . 

Yaptığı iş temel olarak girilen değeri ilgili veri setindeki verilerle kıyaslayıp , kullanıcıdan aldığı k değerine göre kıyasladığı verilerden k tanesini seçmektir . Kıyasladığı kriter ise uzaklıktır . Veri setindeki her sample her feature için birer uzaklık değeri alıp bu uzaklıkları topladıktan sonra o sample için bir uzaklık değeri belirler . Ardından kendisine en yakın k tane komşusundan y değerlerini alıp buna göre bir oylama yapar . Oylamadan çıkan değer bizim verimizin y değeri olarak belirlenir .

Bu çalışmada bu algoritmayı hazır kütüphanesini kullanmadan yapmaya çalıştım . Umuyorum birilerine faydalı olur .
