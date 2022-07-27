# Merge-Sort-Projesi-

[16,21,11,8,12,22] -> Merge Sort

-Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

-Big-O gösterimini yazınız.

#Merge-sort türüne göre aşamaları

                                                   [16,21,11,8,12,22]
                                           
                                    [16,21,11] -------------------------- [8,12,22]        //tek eleman kalıncaya kadar bölünür.//
                                    
                                [16] ------- [21,11] -------------- [8] ------- [12,22]
                                  
                                [16] ------ [21]---[11] ----------- [8] ------ [12]---[22]    //şimdi birleştirme işlemi yapacağız.(küçükten büyüğe)//
                                
                                          [16] - [11,21] ----- [8] - [12,22] 
                               
                                               [11,16,21] ----- [8,12,22]
                               
                                                  [8,11,12,16,21,22]
                                
#Big O Gösterimi

Her adımda n işlem yapılmakta ve yukarıdan aşağı işlem sayısı 

2^x = n ----> logn olduğundan O(nlogn)

www.patika.dev

