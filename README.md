# Proje-2
www.patika.dev

[16,21,11,8,12,22]
-Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
-Big-O gösterimini yazınız.
1)Önce tek sembol kalana kadar hepsi parçalanır. [16,21],[11,8],[12,22] ---> [16],[21],[11],[8],[12],[22], Sonra ikililer arasında büyüklük sıralaması yapılır.
[16,21] - [8,11] - [12,22]
[8,11,16,21] - [12,22]
[8,11,12,16,21,22]

2)Her basamakta O(n) kere işlem yapılır. Basamakların genelinde ise x basamak varsayarsak 2*x = n ==> x = logn... Toplamda O(n.logn) Big-O Notasyonu gösterir.
