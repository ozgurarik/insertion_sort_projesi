# Proje 1 - Insertion Sort

## 1.Soru
[22, 27, 16, 2, 18, 6] -> Insertion Sort

Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

## Çözüm

<p align="center">

| Aşama | Dizi |
| :----: | :----: |
| 1 | [22, 27, 16, 2, 18, 6] |  
| 2 | [2, 27, 16, 22, 18, 6] |
| 3 | [2, 6, 16 , 22, 18,27] |
| 4 | [2, 6, 16, 18, 22, 27] |
</p>

## 2.Soru
Big-O gösterimini yazınız.

## Çözüm
N elemanlı bir diziyi sıralamak için:

* 1 + 2 + ... + (n-1) + n

* = (n * (n+1)) / 2

* = (n² + n) / 2

* = O(n²)

## 3.Soru
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

*Average case*: Aradığımız sayının ortada olması

*Worst case*: Aradığımız sayının sonda olması

*Best case*: Aradığımız sayının dizinin en başında olması.

## Çözüm
[2, 6, 16, 18, 22, 27]

18 Sayısı dizinin ortasında bulunmasından dolayı **Average case** kapsamına girer.