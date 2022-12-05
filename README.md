# Veri_Yapileri_ve_Algoritmalar
Selection Sort Projesi  

Proje 1  
[22,27,16,2,18,6] -> Insertion Sort  

Yukarı verilen dizinin sort türüne göre aşamaları:  

Verilen örüntüye ait en küçük elemanı buluyor ve en baştaki sayı ile yer değiştiriyor.  
[2,27,16,22,18,6] n   
İkinci en küçük elemanı buluyor ve 2. sıra ile değiştiriyor.  
[2,6,16,22,18,27] n-1  
Üçüncü sıradaki en küçük o yüzden dokunmuyoruz ve 4.sıradaki elamana geçiliyor.  
Dördüncü en küçük elemanı buluyor ve 4. sıra ile değiştiriyor.   
[2,6,16,18,22,27] n-2  
5. ve 6. sıradaki elamanlar sıralı, o yüzden sort işlemi tamamlanmış oluyor.  

Big-O Gösterimi : O(n²)  

Dizi sıralandıktan sonra 18 sayısı Average case (Aradığımız sayının ortada olması) kapsamına girer.  

---

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı:  

1. [2,3,5,8,7,9,4,15,6]  
2. [2,3,4,8,7,9,5,15,6]  
3. [2,3,4,5,7,9,8,15,6]  
4. [2,3,4,5,6,9,8,15,7]  
            '  
            '  
            '   
            '  
         
