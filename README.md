# Insertion-Sort-Project-PatikaDev
Insertion Sort Project given by patika.dev in Data Structures and Algorithms section  www.patika.dev
Project : [https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje)

[22,27,16,2,18,6] dizisinin insertion sort türüne göre aşamaları:

[16, 22, 27, 2, 18, 6] -> 22 ile 27yi karşılaştırır sıkıntı yok, sonra 27 ile 16yı karşılaştırır küçük olduğunu görür ve yer değiştirir. sonra 16 22den de küçük olduğu
nu görür ve tekrar yer değiştirerek 16yı başa alır ilk adımdaki hali budur
[2, 16, 22, 27, 18, 6] -> 2yi en başa getirir çünkü en küçüktür
[2, 16, 18, 22, 27, 6] -> işlemler bu şekilde devam eder
[2, 6, 16, 18, 22, 27]

Big-O gösterimi: n(n+1)/2 yani O(n^2) dir katsayılar ve sabit sayılar işleme alınmaz

Time Complexity:
1)Average case: Aradığımız sayının ortada olması.
2)Worst case: Aradığımız sayının sonda olması.
3)Best case: Aradığımız sayının dizinin en başında olması.

Dizi sıralandıktan sonra 18 sayısı average case durumudur.

[7,3,5,8,2,9,4,15,6] verilerinin insertion sort uygulanarak ilk 4 adımı şöyledir: 

[3, 7, 5, 8, 2, 9, 4, 15, 6] -> [3, 5, 7, 8, 2, 9, 4, 15, 6] -> [2, 3, 5, 7, 8, 9, 4, 15, 6] -> [2, 3, 4, 5, 7, 8, 9, 15, 6]

