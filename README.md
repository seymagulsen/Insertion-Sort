# Insertion-Sort
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

a) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

b) Big-O gösterimini yazınız.

c) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

d) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

e) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.



a) [22,27,16,2,18,6] -> [2,27,16,22,18,6] -> [2,6,16,22,18,27] -> [2,6,16,18,22,27] 

    *En küçük 2 olduğu için 22 ve 2 yer değiştirecek ve 2 başa sabitlenecek.
    
    *2'den sonraki elemanlar incelenecek. 6 en küçük. 27 ve 6 yer değiştirecek. 6, 2'den sonraya sabitlenecek.
    
    *6'dan sonraki elemanlar incelenecek. 16 en küçük. 16 sabit kalacak. 16, 6'dan sonraya sabitlenecek.
    
    *16'dan sonraki elemanlar incelenecek. 18 en küçük. 18 ve 22 yer değiştirecek. 18, 16'dan sonraya sabitlenecek.
    
    *18'den sonraki elemanlar incelenecek. 22 en küçük. 22 sabit kalacak. 22, 18'dan sonraya sabitlenecek.
    
    *Ve son olarak zaten 27 kaldı.
    
b) O(n^2)

d) [2,6,16,18,22,27] sıralı hali. 18 sayısı avarage case.

e)  [7,3,5,8,2,9,4,15,6]

    [2|,3,5,8,7,9,4,15,6]
    
    [2|,3|,5,8,7,9,4,15,6]
    
    [2|,3|,4|,8,7,9,5,15,6]
    
    [2|,3|,4|,5|,7,9,8,15,6]
    
