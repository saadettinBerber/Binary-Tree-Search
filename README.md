# Binary-Tree-Search
    [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları
    
    
    1. aşama: Root 7 sayısıdır. 5 sayısı 7 sayısından küçük olduğu için 5 sayısı solda bulunur.
               7
            5
    2. aşama: 1 sayısı 5 ve 7 sayısından küçük olduğu için 5 sayısının solunda bulunur.
               7
            5
        1
    3. aşama: 8 sayısı 7 sayısından büyük olduğu için sağında bulunur.
               7
            5     8
        1
     4. aşama: 3 sayısı 1 sayısından büyük ve 5 ve 7 sayılarından küçük olduğu için 1 sayısının sağında bulunur.
               7
            5     8
        1
           3
     
     5. aşama: 6 sayısı 7 sayısından küçük ve 5 sayısından büyük olduğu için 5 sayısının sağında bulunur.
               7
            5     8
        1     6
           3   
     6. aşama: 0 sayısı hepsinden küçük olduğu için 1 sayısının solunda yer alır.
               7
            5     8
        1     6
     0     3   
     
     7. aşama: 9 sayısı 7 ve 8 sayılarından büyük olduğu için 8 sayısının sağında yer alır.
               7
            5     8
        1     6      9
     0     3    
     8. aşama: 4 sayısı 7 ve 5 sayısından küçük, 1 ve 3 sayısından büyük olduğu için 3 sayısının sağında bulunur.
               7
            5     8
        1     6      9
     0     3
              4
      
      9. aşama: 2 sayısı 5 ve 7 sayılarından küçük, 1 sayısından büyük, 3 sayısından da küçük olduğu için 3 sayısının solunda yer alır.
               7
            5     8
        1     6      9
     0     3
         2     4
    
    
