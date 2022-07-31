# Binary Serach Tree Projesi
https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje
 https://app.patika.dev/beyzu
<p>[7,5,1,8,3,6,0,9,4,2]
<p>Binary serach tree yapılırken root belirlenir ve roottan küçük olan değerler sola, büyük olan değerler ise sağa yazılır. Bu dizide Root=7
<blockquote> 1.adım: Root:7
2.adım: Şimdi 5 sayısı rottan(7)değerinden küçük olduğu için 5 sayısını 7'nin soluna yazıyoruz.                

             7 
            /
           5
    
3.adım: Daha sonra 1 sayısını yerleştireceğiz 1 5'ten küçük olduğu için sol tarafa yazılır.

             7
            / 
           5
          /
         1
         
4.adım: 8 Roottan büyük olduğu için rootun sağ tarafına yerleştirilir.

               7
              / \
             5   8
            /
          1
          
5.adım: 3 sayısı 1'den büyük olduğu için sağ tarafa yerleştirilir.

              7
             / \
            5   8
           /
          1
           \
             3
            
6.adım: Sırada 6 var. 5'ten büyük olduğu için 5'in sağ tarafına yerleştirilir.

               7
              / \
             5   8
            / \
           1   6
           \
             3
            
7.adım: 0 1'den küçük olduğu için 1'in sol tarafına yerleştirilir.

               7
              / \
             5   8
            / \
           1   6
          / \
         0   3
        
8.adım: 9>8 olduğu için 8'in sağ tarafına gelir.

                7
               / \
              5   8
             / \    \
            1   6    9
           / \
          0   3
         
9.adım:4>3 olduğundan 3'ün sağ tarafına gelir.
         
                 7
                / \
               5    8
              / \     \
             1   6     9
            / \
           0   3
                \
                 4
                
10 .adım: 2 < 3 olduğundan 2 'ün sol tarafına gelir

                   7
                  / \
                 5   8
                / \    \
               1   6    9
              / \
             0   3
                 / \
                2    4
                
    
    
    
   
