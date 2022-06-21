# Veri Yapıları

## İnsertion Sort Projesi


[Patika Profil bağlantısı](https://app.patika.dev/itaskin)
[Proje Linki](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje)

![githup](https://github.com/itaskinn/kodluyoruzilkrepo/blob/main/Patika.dev_Veri%20yap%C4%B1lar%C4%B1%20ve%20algoritmalar/Insertion%20Sort.png)

### 1. Soru

[22,27,16,2,18,6] -> Insertion Sort

- [2,27,16,22,18,6] -> 2 ile 22 yer değiştiriyor.
- [2,6,16,22,18,27] -> 6 ile 27 yer değiştiriyor.
- [2,6,16,22,18,27] -> 3. eleman 4,5 ve 6. elemanlardan küçük olduğuiçin yer değiştirmez
- [2,6,16,18,22,27] -> 18 ile 22 yer değiştirir.
- [2,6,16,18,22,27] -> 5. sıradaki elaman 6. dan küçük olduğu için yer değiştirmez.

### 2. SORU

Insertion sort algoritması worst case senaryosunda O(n²) sonucunu, best case senaryosunda ise O(n) sonucunu verir. Bu durumda dominant olduğu için  O(n²) alırız.
Algoritmamız 6 aşamalı olduğundan dolayı:

O(n²) = O(6²) = O(36)

### 3. SORU

**Average case:** Aradığımız sayının ortada olması.
**Worst case:** Aradığımız sayının sonda olması.
**Best case:** Aradığımız sayının dizinin en başında olması.

Dizi sıralandıktan sonra 18 sayısı dizinin ortasında yer aldığından dolayı average case olur.

### 4. Soru

**[7,3,5,8,2,9,4,15,6]**
-[2,3,5,8,7,9,4,15,6] -> 7 ile 2 yer değiştiriyor.
-[2,3,5,8,7,9,4,15,6] -> 2. sıradaki 3 rakamı en küçük, işlem yapılmaz.
-[2,3,4,8,7,9,5,15,6] -> 5 ile 4 yer değiştiriyor.
-[2,3,4,5,7,9,8,15,6] -> 8 ile 5 yer değiştiriyor.

