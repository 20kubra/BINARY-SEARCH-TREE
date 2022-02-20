# BINARY-SEARCH-TREE
>> İkili ağaçların (Binary Tree) özel bir hali olan Binary Search Tree'de (ikili arama ağaçlarında), düğümlerde duran bilgilerin birbirine göre küçüklük büyüklük ilişkisi bulunmalıdır. Örneğin tam sayılardan(integer) oluşan veriler tutulacaksa bu verilerin aralarında küçük-büyük ilişkisi bulunmaktadır.

>>İkili arama ağacı, her düğümün solundaki koldan ulaşılabilecek bütün verilerin düğümün değerinden küçük, sağ kolundan ulaşılabilecek verilerin değerinin o düğümün değerinden büyük olmasını şart koşar.

İkili arama ağaçları random access yapamıyor. Average case complexity O(logn),worst case ise O(n)'dir. Eleman ekleme,eleman arama işlemleri logn zamanda yapılır. 
>>Ağacın en başında bulunan elemana root denir ve eleman eklemeye root'dan başlanır.

Örnek : [7,5,1,8,6,0,9,4,2]  
(Bu örnekte root 7 rakamıdır.)

             7
            / \
           5   8
          / \   \
         1   6   9
        / \
       0   3
          / \
         2   4
