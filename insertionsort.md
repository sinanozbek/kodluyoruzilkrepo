

## Insertion Sort, dizinin her bir elemanını tek tek dolaşarak, her elemanı sıralanmış kısım içinde uygun yerine yerleştirerek çalışır.

* Adım 1: İkinci eleman (27) ile birinci elemanı (22) karşılaştırın ve gerekirse yerlerini değiştirin:
[22, 27, 16, 2, 18, 6]

- Adım 2: Üçüncü elemana (16) geçin ve sıralanmış kısım içindeki uygun yerine yerleştirin ([22, 27]):
[16, 22, 27, 2, 18, 6]

- Adım 3: Dördüncü elemana (2) geçin ve sıralanmış kısım içindeki uygun yerine yerleştirin ([16, 22, 27]):
[2, 16, 22, 27, 18, 6]

- Adım 4: Beşinci elemana (18) geçin ve sıralanmış kısım içindeki uygun yerine yerleştirin ([2, 16, 22, 27]):
[2, 16, 18, 22, 27, 6]

- Adım 5: Altıncı elemana (6) geçin ve sıralanmış kısım içindeki uygun yerine yerleştirin ([2, 16, 18, 22, 27]):
[2, 6, 16, 18, 22, 27]

Insertion Sort algoritmasının Big O gösterimi O(n^2)'dir.
Sayı ortada  olduğu  için avarege casedir.

-------------------------
 ## [7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Selection Sort'a göre ilk 4 adımı aşağıdaki gibi olacaktır:

Adım: En küçük elemanı bulun ve ilk elemanla yer değiştirin.

En küçük eleman 2'dir. Dizi şu şekilde olacaktır: [2, 3, 5, 8, 7, 9, 4, 15, 6]
Adım: İkinci en küçük elemanı bulun ve ikinci elemanla yer değiştirin.

İkinci en küçük eleman 3'tür. Dizi şu şekilde olacaktır: [2, 3, 5, 8, 7, 9, 4, 15, 6]
Adım: Üçüncü en küçük elemanı bulun ve üçüncü elemanla yer değiştirin.

Üçüncü en küçük eleman 4'tür. Dizi şu şekilde olacaktır: [2, 3, 4, 8, 7, 9, 5, 15, 6]
Adım: Dördüncü en küçük elemanı bulun ve dördüncü elemanla yer değiştirin.

Dördüncü en küçük eleman 5'tir. Dizi şu şekilde olacaktır: [2, 3, 4, 5, 7, 9, 8, 15, 6]
Bu şekilde devam ederek Selection Sort algoritması ile dizinin tamamının sıralanması sağlanır.
