# İnsertion Sort Ödev

> [22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

---

### Cevap

```

[22, 27, 16, 2, 18, 6] (Başlangıç)
[22, 27, 16, 2, 18, 6] (22, 27 zaten sıralı)
[16, 22, 27, 2, 18, 6] (16, 22, 27 sıralı)
[2, 16, 22, 27, 18, 6] (2, 16, 22, 27 sıralı)
[2, 16, 18, 22, 27, 6] (6, 18 yer değiştirildi)
[2, 6, 16, 18, 22, 27] (6, 16 yer değiştirildi)

Average case: O(n^2) 
Worst case: Aradığımız sayının sonda olması (O(n))
Best case: Aradığımız sayının dizinin en başında olması (O(1))


Not: Bu benim cevabım değil benim cevabım aşağıda. Ben cevabımı konrtrol ettiridiğimde sonuç odaklı olduğu ve aşamaları atladığım söylendi ve doğrusu anlatıldı.

```

```
Benim cevabım

[2, 6, 16, 18, 22, 27]

Big O Notation  -->  O(nlogn)

```
---
# Selection Sort Ödev

> [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
---
### Cevap

```
[7, 3, 5, 8, 2, 9, 4, 15, 6] (Başlangıç)
1.adım- [2, 3, 5, 8, 7, 9, 4, 15, 6] (2, dizinin en küçük elemanı olduğu için 2 ile 7'nin yerini değiştirir)
2.adım- [2, 3, 4, 8, 7, 9, 5, 15, 6] (4, dizinin en küçük elemanı olduğu için 4 ile 5'in yerini değiştirir)
3.adım- [2, 3, 4, 5, 7, 9, 8, 15, 6] (5, dizinin en küçük elemanı olduğu için 5 ile 8'in yerini değiştirir)
4.adım- [2, 3, 4, 5, 6, 9, 8, 15, 7] (6, dizinin en küçük elemanı olduğu için 6 ile 15'in yerini değiştirir)

```