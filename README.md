# Insertion-Sort-Projesi
Patika dev profilim için [tıklayınız.](https://app.patika.dev/ailker)

## Sorular
------
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2. Big-O gösterimini yazınız.

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## Cevaplar
--------
### 1.) [22,27,16,2,18,6] Dizisinin insertion şort`a göre aşamaları
1. [2,27,16,22,18,6] n
2. [2,6,16,22,18,27] n-1
3. [2,6,16,22,18,27] n-2
4. [2,6,16,18,22,27] n-3
5. [2,6,16,18,22,27] n-4
6. [2,6,16,18,22,27] 1
--------
### 2.) [22,27,16,2,18,6] dizisinin Big-O notasyonu (n.(n+1))/2 'den O(n²) --> (6.(6+1))/2 'den O(6²) olacaktir.
-----------
### 3.) Time Complexity 18 sayisi dizi siralandiktan sonra ortada oldugu icin Average case kapsamina girer.
-----------
### 4.) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adimi;
1. [2,3,5,8,7,9,4,15,6] n
2. [2,3,5,8,7,9,4,15,6] n-1
3. [2,3,4,8,7,9,5,15,6] n-2
4. [2,3,4,5,7,9,8,15,6] n-3

şeklinde olacaktır.