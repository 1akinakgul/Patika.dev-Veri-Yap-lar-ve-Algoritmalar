# [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

          [16,21,11,8,12,22]
  
         [16,21,11]   [8,12,22] -> İlk önce sayı dizimizi ikiye bölüyoruz.
        
       [16] [21,11]   [8,12] [22] -> Daha sonra sayı dizimizi yeniden ikiye bölüyoruz. Bazı sayılar tek başına kalabilir.
     
         [11,16,21]    [8,12,22] -> Ardından böldüğümüz dizilerimizi sıralı bir şekilde birleştiriyoruz.
         
           [8,11,12,16,21,22] -> Son olarak bütün sayılarımızı sıraya uygun bir şekilde birleştiriyoruz.
  
  # Big-O gösterimini yapınız.
  
  O(nlogn)

www.patika.dev
