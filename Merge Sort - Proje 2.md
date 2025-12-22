**Proje 2: Merge Sort**
Dizi: [16, 21, 11, 8, 12, 22]

**Aşamalar (Böl ve Yönet)**
Merge Sort algoritması diziyi önce en küçük parçaya kadar böler, ardından sıralı bir şekilde birleştirir.

**Adım 1 (Bölme - Divide): Dizi ortadan ikiye bölünür.**
Sol: [16, 21, 11]     Sağ: [8, 12, 22]

**Adım 2: **
Sol taraf: [16, 21] ve [11] olarak ayrılır.
Sağ taraf: [8, 12] ve [22] olarak ayrılır.

**Adım 3: **
[16] - [21] - [11][8] - [12] - [22]

**Adım 4 (Birleştirme - Merge): **
[16] ve [21] birleşir -> [16, 21][8] ve [12] birleşir -> [8, 12] Diğer tek elemanlar ([11] ve [22]) bekler.

**Adım 5: **
Sol Grup: [16, 21] ile [11] birleşir -> [11, 16, 21]
Sağ Grup: [8, 12] ile [22] birleşir -> [8, 12, 22]

**Adım 6: **
[11, 16, 21] ve [8, 12, 22] karşılaştırılır:8 en küçük, başa gelir.
11 gelir.12 gelir.16 gelir.21 gelir.22 gelir.
Sonuç: [8, 11, 12, 16, 21, 22]2. 

**Big-O Gösterimi**

    O(n \log n)

    
