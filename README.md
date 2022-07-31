# Proje 2

**[16,21,11,8,12,22]** -> Merge Sort
- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
-----
<br></br>
##1- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.


Merge sort sıralama algoritmasına göre dizi, tek elemanlı alt diziler halinde olana kadar ortadan alt dizilere dallanıp bir daha toparlanırken sıralanır .
<br></br>
1.
![1. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje2/raw/main/Resimler/1.jpg)
önce iki alt diziye bölünür
<br></br>
2.
![2. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje2/raw/main/Resimler/2.jpg)
sol alt dizi iki diziye bölünür
<br></br>
3.
![3. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje2/raw/main/Resimler/3.jpg)
tek elemanlı diziler olana kadar sol dizi tarafında devam eden bölünmelerden sonra karşılaştırma işlemi başlar
<br></br>
4.
![4. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje2/raw/main/Resimler/4.jpg)
tek elemanlı alt dizi elemanları birbirieriyle karşılaştırıp bir daha üst ana diziye yerleştirilir
<br></br>
5.
![5. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje2/raw/main/Resimler/5.jpg)
<br></br>
6.
![6. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje2/raw/main/Resimler/6.jpg)
aynı işlem ikiye O(nlogn) algoritma zamanı büyüme hızında bölünen aynı dizinin sağ alt dizisinde de tekrar edilir
<br></br>
7.
![7. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje2/raw/main/Resimler/7.jpg)
<br></br>
8.
![8. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje2/raw/main/Resimler/8.jpg)
<br></br>
9.
![9. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje2/raw/main/Resimler/9.jpg)
<br></br>
10.
![10. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje2/raw/main/Resimler/10.jpg)
<br></br>
11.
![11. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje2/raw/main/Resimler/11.jpg)
<br></br>
12.
![12. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje2/raw/main/Resimler/12.jpg)
<br></br>
13.
![13. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje2/raw/main/Resimler/13.jpg)
<br></br>

----
<br></br>
##2- Big-O gösterimini yazınız.

Dizinin her aşamada 2 alt dizilere bölünmesi O(logn).
Dizi bir daha sıralı bir şekilde toparlanırken algoritma büyüme hızı O(n) olur.
Sonuç olarak BİG-O gösterimi O(nlogn) olacaktır.

