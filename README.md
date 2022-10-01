# Binary-Search-Tree--3th-


[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
                  7				
                /		\			
              5				8		
           /		\				\	
         1				6				9
       /		\							
      0				3						
           /		\					
    			2				4		
Root=7, Sırasıyla dizideki sayılar yerleştirildi. 5 7'den küçük olduğu için sola, 1 7'den küçük olduğu için sola ardından 5'den de küçük olduğu için tekrar sola. 8 7'den büyük olduğu için sağa, 3 7'den 5'ten küçük olduğu için sola ve 1'den büyük olduğu için sağa, 6 7'den küçük olduğu için sola ve 5'ten büyük olduğu için ardından sağa, 0 sırasıyla 7,5 ve 1'den küçük olduğu için sola, 9 7 ve 8'den büyük olduğu için sağa, 4 7 ve 5'ten küçük olduğu için sola fakat 1 ve 3'ten büyük olduğu için sağa, 2 7 ve 5'ten küçük olduğu için sola ardından 1'den büyük olduğu için sola ve 3'ten de küçük olduğu için tekrar sola yerleştirilir.
