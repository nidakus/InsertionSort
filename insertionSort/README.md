# **Insertion Sort Projesi**
[22,27,16,2,18,6] -> Insertion Sort

## 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. ##

```
Birinci adim : [2,27,16,22,18,6]

Ikinci adim : [2,6,16,22,18,27]

Ucuncu adim : [2,6,16,22,18,27]

Dorduncu adim : [2,6,16,18,22,27]
```

## 2. Big-O gösterimini yazınız. ##
```
O(n²)
```
## 3. Time Complexity: ##

**Average case:** Aradığımız sayının ortada olması. Worst case ile best case'in ortalamasını aldığımızda average case O(n²)dir.

**Worst case:** Aradığımız sayının sonda olması. Insertion sort icin worst case O(n²) dir.

**Best case:** Aradığımız sayının dizinin en başında olması. Insertion sort icin best case O(n) dir.



## 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. ##
```
Best case O(n) kapsamina girer.
```
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

```
Birinci adim : [2,3,5,8,7,9,4,15,6]

Ikinci adim : [2,3,4,8,7,9,5,15,6]

Ucuncu adim : [2,3,4,5,7,9,8,15,6]

Dorduncu adim : [2,3,4,5,6,9,8,15,7]
```
