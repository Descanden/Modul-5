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
=> /* perbedaan utama antara Binary Tree dan Binary Search Tree (BST) terletak pada aturan penempatan node. Dalam Binary Tree, tidak ada aturan khusus mengenai bagaimana node ditempatkan, sehingga nilai node bisa ditempatkan di posisi mana saja tanpa mengikuti urutan tertentu. Sebaliknya, dalam Binary Search Tree, setiap node harus ditempatkan mengikuti aturan tertentu: nilai di node kiri harus lebih kecil dari nilai di node saat ini, dan nilai di node kanan harus lebih besar. Aturan ini memungkinkan BST untuk melakukan operasi pencarian, penambahan, dan penghapusan node dengan lebih efisien. */
