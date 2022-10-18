# [22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

# [22,27,16,2,18,6]


[2|,27,16,22,18,6] -> 2 en küçük sayı olduğu için 22 ile yerini değiştiriyoruz.

[2,6|,16,22,18,27] -> 6 sayısı diğerlerine göre daha küçük olduğu için 27 ile yerini değiştiriyoruz.

[2,6,16|,22,18,27] -> Sıralamadaki yeri doğru olduğu için 16 sayısının yerini değiştirmiyoruz.

[2,6,16,18|,22,27] -> Ardından 22 ve 27 sayılarından daha küçük olduğu için 18 sayısıyla 22 sayısının yerini değiştiriyoruz.

[2,6,16,18,22|,27] -> Sıralamadaki yeri doğru olduğu için 22 sayısının yerini değiştirmiyoruz.

[2,6,16,18,22,27]  -> Sıralamadaki yeri doğru olduğu için 27 sayısının yerini değiştirmiyoruz.

# Big-O gösterimini yapınız

O(n²)

# Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

18 sayısı başta ve sonda olmadığı için Average Case kapsamındadır.

# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[2,3,5,8,7,9,4,15,6] -> En küçük sayı 2 olduğu için en başa yazıp 7 ile yerini değiştiriyoruz.

[2,3,5,8,7,9,4,15,6] -> 3 sayısı ikinci en küçük sayı olduğu için yerini değiştirmiyoruz.

[2,3,4,8,7,9,5,15,6] -> 4 sayısı kalan sayılar arasında en küçüğü olduğu için 5 ile yerini değiştiriyoruz.

[2,3,4,5,7,9,8,15,6] -> 5 sayısı kalan sayılar arasında en küçüğü olduğu için 8 ile yerini değiştiriyoruz
