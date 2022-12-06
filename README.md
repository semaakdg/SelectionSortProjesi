# SelectionSortProjesi

Proje 1:

a- [22,27,16,2,18,6] -> Insertion Sort Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

b- Big-O gösterimini yazınız.

c- Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
    Average case: Aradığımız sayının ortada olması
    Worst case: Aradığımız sayının sonda olması
    Best case: Aradığımız sayının dizinin en başında olması.
    
d- [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Cevaplar: 
a- 1. En küçük eleman bulunur ve en baştaki ile yer değiştirir: [2,27,16,22,18,6]  
   2. 2. en küçük eleman bulunur ve 2. elemanla yer değiştirir: [2,6,16,22,18,27]
   3. 3.en küçük eleman bulunur ve 3. elemanla yer değiştirir: [2,6,16,22,18,27]
   4. 4.en küçük eleman bulunur ve 4. elemanla yer değiştirir: [2,6,16,18,22,27] 

b- Big-O Gösterimi: n+(n-1)+(n-2)+…+1= n(n+1)/2= (n^2+n)/2 >>>>>> baskın olan fonksiyo alınır ve katsayılar önemsenmez o yüzden n^2 yi alıyoruz. Yani O(n^2) dir.

c- 18 sayısı [2,6,16,18, 22,27] dizin ortasında olduğundan dolayı 'Avarage case' kapsamına girer.

d- [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı:
   1- En küçük eleman bulunur ve en baştaki ile yer değiştirir >> [2,3,5,8,7,9,4,15,6]
   2- en küçük eleman bulunur ve 2. elemanla yer değiştirir.(Burada zaten 2.terim olması gereken sırada o yüzden 3.terime bakarız) >> [2,3,4,8,7,9,5,15,6]
   3- 4.en küçük eleman bulunur ve 4. elemanla yer değiştirir >> [2,3,4,5,7,9,8,15,6]
   4- 5.en küçük eleman bulunur ve 5. elemanla yer değiştirir >1 [2,3,4,5,6,9,8,15,7]
Footer
© 2022 GitHub, Inc.
Footer navigation
Terms
