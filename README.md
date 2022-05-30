# veriyapilari-ve-algoritmalar
projeler


Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Dizinin 2. elemanı seçilir ve öndeki elemanla karşılaştırma yapılır, eğer önündeki elemandan küçükse yer değiştirirler. Bu işlem sonunda 3. eleman seçilir ve öndeki elemanlarla karşılaştırma yapılır, önündeki elemanlardan küçükse yer değiştirme işlemi yapılır. Dizinin sonunda gelene kadar bu algoritma mantığı devam eder.

ilk asama [22,#27,16,2,18,6]

2.asama [22, #16 ,27,2,18,8]

3.asama [16,22,27,# 2,18,8]

4.asama [2,16,18,22,27,#8] 

5.asama [2,8,16,18,22,27]





Big-O gösterimini yazınız.
O(n^2)

Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. 

ortada oldugu icin average case olur

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


[3,7,5,8,2,9,4,15,6]

[3,5,7,8,2,9,4,15,6]

[2,3,5,7,8,9,4,15,6]

[2,3,4,5,7,8,9,15,6]
