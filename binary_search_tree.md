# Patika.dev [Profilim](https://app.patika.dev/osman-koyuncu)

## Proje 3 - Binary Search Tree

**1. Madde**

* [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

```
   1. Aşama: Root 7 seçilir. 5 değeri 7 değerinden küçük olduğu için sol tarafa yazılır.   
  
            7
          /  
         5    
         
    2. Aşama: 1 değeri 7 değerinden küçük olduğu için sol tarafa gidilir. 5 değerinden de küçük olduğu için 5 in soluna yazılr.   
              
          7
        /    
       5        
      /       
     1    
      
     3. Aşama: 8 değeri 7 değerinden büyük olduğu için sağ tarafa yazılır. 
         
          7
        /    \ 
       5      8  
      /       
     1 
     
     4. Aşama: 3 değeri 7 den ve 5 den küçük 1 den büyük olduğu için 1 in sağ tarafa yazılır. 
         
          7
        /    \ 
       5      8  
      /        
     1   
      \
       3
       
      5. Aşama: 6 değeri 7 den küçük 5 den büyük olduğu için 5 ün sağına yazılır. 
         
          7
        /    \ 
       5      8  
      / \      
     1   6
      \
       3
       
      5. Aşama: 0 değeri 7 den, 5 den ve 1 den küçük olduğu için 1 in soluna yazılır. 
         
          7
        /    \ 
       5      8  
      / \      
     1   6
    / \
   0   3 

      6. Aşama: 9 değeri 7 den ve 8 den büyük olduğu için 8 in sağına yazılır. 
         
          7
        /    \ 
       5      8  
      / \      \
     1   6      9
    / \
   0   3  
     
       7. Aşama: 4 değeri 7 den,5 den küçük 1 den ve 3 den büyük olduğu için 3 ün sağına yazılır. 
        
          7
        /    \ 
       5      8  
      / \      \
     1   6      9
    / \
   0   3   
        \
         4
         
       8. Aşama: 2 değeri 7 den ve 5 den küçük, 1 den büyük, 3 den küçük olduğu için 3 ün soluna yazılır. 
                   
          7
        /    \ 
       5      8  
      / \      \
     1   6      9
    / \
   0   3   
      / \
     2   4     
```
 
