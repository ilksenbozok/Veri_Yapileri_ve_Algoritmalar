# Veri_Yapileri_ve_Algoritmalar
Selection Sort Projesi  

Proje 1  
[22,27,16,2,18,6] -> Insertion Sort  
  
Yukarı verilen dizinin sort türüne göre aşamaları:  
  
1.aşama: Dizinin ikinci elemanı başlangıç elemanı olarak seçilir.Daha sonra ilk elemanla kıyaslanır, 22<27 olduğu için dizinin sırası değişmez.     
[22,27,16,2,18,6]  
2.aşama: Şimdi de üçünkü eleman ilk iki elemanla kıyaslanır, 16<22 ve 16<27 olduğundan üçüncü eleman en başa alınır ve sayılar sırasına göre kaydırılır.    
[16,22,27,2,18,6]  
3.aşama: Bu adımda da sıra dördüncü eleman yani 2 sayısına bakmaya gelmiştir.2 hepsinden küçük olduğu için direk en sola en başa yerleşir.Diğer sayılarda birer sağa kayarak kendi sırasını alır.  
[2,16,22,27,18,6]  
4.aşama: Bu adımda sıralanmak üzere bakılacak indis değeri beştir.Yani karşılığında bulunan eleman 18'dir.18 sayısı solundaki 2,16,22,27 ile kontrol edilir ve kendi yerine araya girerek dizinin aşağıdaki halini oluşturur.  
[2,16,18,22,27,6]  
5.aşama: Bu adımı son adım olarak düşünebiliriz. Burada da dizinin altıncı indis değerinde bulunan eleman olan 6 kontrol edilir. 6<16, 6<18 6<22 olduğu için araya girerek kendisine ait olan sırasında yerini alır.Dizinin son hali:  
[2,6,16,18,22,27]  
    
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
         
