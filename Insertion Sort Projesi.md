**Insertion Sort Projesi - Proje 1**

**[22,27,16,2,18,6] -> Insertion Sort**
**Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**

   Başlangıç: İlk eleman (22) sıralı kabul edilir.
  1. Adım: 27 incelenir. 27 > 22 olduğu için yeri değişmez. [22, 27, 16, 2, 18, 6]
  2. Adım: 16 incelenir. 22 ve 27'den küçüktür, en başa gelir. [16, 22, 27, 2, 18, 6]
  3. Adım: 2 incelenir. En küçüktür, en başa gelir. [2, 16, 22, 27, 18, 6]
  4. Adım: 18 incelenir. 16'dan büyük, 22'den küçüktür; araya girer. [2, 16, 18, 22, 27, 6]
  5. Adım: 6 incelenir. 2'den büyük, 16'dan küçüktür; araya girer. Sonuç: [2, 6, 16, 18, 22, 27]


**Big-O gösterimini yazınız.** 

  O(n^2)
  

**Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.**

  Average Case (Ortalama Durum)
  

**[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.**


   Selection Sort (Seçmeli Sıralama), dizideki en küçük elemanı bulur ve en baştaki sayı ile yer değiştirir.
  1. Adım: Dizinin en küçüğü 2 bulunur. En baştaki 7 ile yer değiştirir. [2, 3, 5, 8, 7, 9, 4, 15, 6]
  2. Adım: Geriye kalan kısımdaki (3'ten itibaren) en küçük sayı 3'tür. Zaten 2. sıradadır, yer değiştirmez (kendiyle yer değişir). [2, 3, 5, 8, 7, 9, 4, 15, 6]
  3. Adım: Geriye kalan kısımdaki (5'ten itibaren) en küçük sayı 4 bulunur. Sıradaki 5 ile yer değiştirir. [2, 3, 4, 8, 7, 9, 5, 15, 6]
  4. Adım: Geriye kalan kısımdaki (8'den itibaren) en küçük sayı 5 bulunur. Sıradaki 8 ile yer değiştirir. [2, 3, 4, 5, 7, 9, 8, 15, 6]
     
