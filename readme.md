## [16,21,11,8,12,22] -> Merge Sort
- [16,21,11,8,12,22] ----- Başlangııç durumuu.
- Tüm elemanlar tek kalana kadar dizi ikiye bölünür.
- [16,21,11]----------------------------[8,12,22]
- [16,21]-----[11]--------------[8,12]----------[22]
- [16]-------- [21]-----[11]--------[8]----[12]------[22]
- Tüm elemanlar tek bırakıldıktan sonra en küçük eleman başa gelmek kaydıyla ikili şekilde diziler birleştirilir.
- [16]-------- [21]-----[11]--------[8]----[12]------[22]
- [16,21]-------[11]---------[8,12]--------[22]
- [11,16,21]------------[8,12,22]
- [8,11,12,16,21,22]
## Big O gösterimi nedir
- Recursive bir fonksiyon olmasından dolayı sürekli olarak kendini çağırarak diziyi ikiye bölmektedir. Her dizinin merge işlemi sayısı da dizinin uzunluğunun değeri yani n olduğundan; 
- O(n(logn)) 
- Sonuç olarak dizinin Big O Notation değeri **O(6(log6))** olur