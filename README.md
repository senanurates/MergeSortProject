Merge Sort Projesi
[16,21,11,8,12,22] -> Merge Sort
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
1)               [16,21,11,8,12,22]
2)       [16,21,11]               [8,12,22]      Dizi 2 ye bölünür.
3)       [16,21] [11]             [8,12] [22]    2. ye bölünmüş olan diziler tekrar 2 parçaya bölünür.
4)       [16] [21] [11]           [8] [12] [22]  Tek dizeler haline gelene kadar bu işlem tekrarlanır.
5)       [16,21] [11]             [8,12] [22]    Tekrar birleştirme yapılırken diziler küçükten büyüğe sıralanır.
6)       [11,16,21]               [8,12,22]      Tekrar birleştirme yapılırken diziler küçükten büyüğe sıralanır.
7)              [8,11,12,16,21,22]               Sonuç.
Big-O gösterimini yazınız.
O(nlog(n))
