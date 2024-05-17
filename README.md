#Output for the CodeLab1:
Pre Order: 
20 
2 
16 
25
37

In Order:
2
16
20
25
37

Post Order:
16
2
37
25
20


#Output for the CodeLab2:
Pre Order: 
20 
2 
37 
12 
25 
16 

In Order: 
37 
2 
12 
20 
25 
16 

Post Order:
37
12
2
16
25
20


##Perhatikan code diatas, apakah ada perbedaan antara logika dari code Binary Tree dengan Binary 
Search Tree? Jika ada tunjukkan bagian mana yang berbeda dan jelaskan kepada asisten masing-
masing.
=> /* Perbedaan tersebut tercermin dalam logika penyusunan data pada metode NewNode dalam kode yang Anda berikan.
Dalam binary tree yang Anda implementasikan, data baru hanya dimasukkan ke dalam struktur tanpa memperhatikan
urutan nilai data, sementara pada BST, data baru disusun sesuai dengan urutan nilai untuk memanfaatkan keunggulan
pencarian yang efisien. */
