# Merge-Sort-Projesi
Patika dev ödev projesi
```
[16,21,11,8,12,22] -> Merge Sort
```

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
^
# Cevap

```
[16,21,11,8,12,22]

[16,21,11]  [8,12,22]

[16] [21,11] [8,12] [22]

[16] [21] [11] [8] [12] [22]

[16] [11,21] [8,12] [22]

[11,16,21] [8,12,22]

[8,11,12,16,21,22]

```
# Big-O Gösterimi

````
[16,21,11]  

[16] [21,11]

n

2^x = n

x = logn

O(logn)
```

