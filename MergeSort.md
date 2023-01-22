[16,21,11,8,12,22] dizisinin merge sort türüne göre aşamalarını yazınız.

//İkiye bölerek 1 kalana kadar gidlir.

[16,21,11]                               [8,12,22]

[16,21]  [11]                           [8,12]  [22]

[16]  [21]   [11]                     [8]   [12]   [22]

[11,16,21]                               [8,12,22]                    
           [8,11,12,16,21,22]

Big-o O(nlog(n))
