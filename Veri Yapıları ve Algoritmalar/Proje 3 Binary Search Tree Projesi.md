## Proje 3
### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

## root= 7 
####

## 1.
    5, 7'den küçüktür bu yüzden sola geçecek.
  
             7
            /
           5 
####
## 2.
    1 5'ten küçük olduğu için soluna yazıyoruz.
    
            7
           /   
          5 
         /
        1 
####

## 3.
    8  7'den büyüktür bu yüzden sağa geliyor.
    
            7
           / \  
          5   8
         /
        1 
####

## 4.
    3 1'den büyük olduğu için sağına yazıyoruz.
    
            7
           / \  
          5   8
         / 
        1   
         \
          3
####

## 5.
    6 5'ten büyük olduğu için sağına yazıyoruz.
    
            7
           / \  
          5   8
         / \
        1   6
         \
          3
####

## 6.
    0 1'den küçük olduğu için soluna yazıyoruz.
    
            7
           / \  
          5   8
         / \     
        1   6   
       / \
      0   3
####

## 7.
    9 8'den büyüktür bundan dolayı sağına geçiriyoruz.
    
            7
           / \  
          5   8
         / \   \  
        1   6   9
       / \
      0   3 
####

## 8.
    4 3'ten büyük olduğu için sağına yazıyoruz.
    
            7
           / \  
          5   8
         / \   \  
        1   6   9
       / \
      0   3
           \
            4
####

## 9.
    2 3'ten küçüktür bu yüzden soluna yazıyoruz.

            7
           / \  
          5   8
         / \   \  
        1   6   9
       / \
      0   3
         / \
        2   4
####
