# Insertion-Sort-Projesi
Patika.dev Veri Yapıları ve Algoritmalar dersi için oluşturmuş olduğum proje. Insertion Sort projesinin kendimce cevabını derlemiş olacağım.
## Proje 1 [22,27,16,2,18,6] -> Insertion Sort
### 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
---
#### Adım 1
- 22 sayısı zaten sıralı olarak ele alınır. 
- Ardından 22 ve 27 karşılatırılır. 
- Zaten sıralı olduğundan olduğu gibi kalır.
**Elimizdeki veri şu görünümü alır:**
```
[22,27,16,2,18,6]
```
#### Adım 2
- 27 ve 16 karşılaştırılır. 
- 16, 27'den küçük olduğundan yer değiştirirler. 
- Ardından 16 ve 22 karşılaştırılır. 
- Onlar da yer değiştirir.
**Elimizdeki veri şu görünümü alır:**
```
[16,22,27,2,18,6]
```
#### Adım 3
- 2 sırasıyla 27,22 ve 16 ile karşılaştırılır. 
- Hepsinden küçük olduğundan en başa gider.
**Elimizdeki veri şu görünümü alır:**
```
[2,16,22,27,18,6]
```
#### Adım 4
- 18, 27 ve 22 ile karşılaştırılır. 
- Ve ikisinden küçük olduğu için yan tarafa geçer. 
- Ardından 16 ile karşılaştırılır. 
- 16'dan büyük olduğundan 18 olduğu yerde kalır.
**Elimizdeki veri şu görünümü alır:**
```
[2,16,18,22,27,6]
```
#### Adım 5
- 6 sırasıyla 27,22,18 ve 16 ile karşılaştırılır ve hepsinden küçük olduğu için hepsinin arkasına geçer. 
- Son olarak 6 ve 2 karşılaştırılır. 
- 6, 2'den büyük olduğundan oldukları yerde kalırlar. 
**Elimizdeki veri şu görünümü alır:**
```
[2,6,16,18,22,27]
```
### 2. Big-O gösterimini yazınız.
---
N tane terim için N tane işlem gerçekleştiğinden Big-O **O(n^2)** şeklinde gösterilir.
### 3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
---
- **Best Case:** O(n)
- **Average Case:** O(n^2)
- **Worst Case:** O(n^2)
### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
---
Average case kapsamına girer. O(n^2)
## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
---
1. [3,7,5,8,2,9,4,15,6]
2. [3,5,7,8,2,9,4,15,6]
3. [3,5,7,2,8,9,4,15,6]
4. [3,5,2,7,8,9,4,15,6]
