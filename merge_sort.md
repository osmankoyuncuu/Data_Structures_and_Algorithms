# Patika.dev [Profilim](https://app.patika.dev/osman-koyuncu)

## Proje 2 - Merge Sort

**1. Madde**

* [16,21,11,8,12,22] dizinin sort türüne göre aşamalarını yazınız.
```

                [16,21,11,8,12,22] 
    [16,21,11]                    [8,12,22] 
    
  [16]     [21,11]              [8]    [12,22]
  
  [16]    [21]  [11]           [8]    [12]  [22]
  
  [16]     [11,21]              [8]    [12,22]
  
     [11,16,21]                    [8,12,22]
                [8,11,12,16,21,22]  
```
                
**2. Madde**

* Big-O gösterimini yazınız.

Merge sort'un Big o gösterimi: O(nlogn). Liste 6 elemanlı olduğundan O(6log6) olacaktır.
