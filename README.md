# InsertionSortProjesi

[22,27,16,2,18,6] -> Insertion Sort

#### Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
     [22,27,16,2,18,6] n
     [2,27,16,22,18,6] n-1
     [2,6,16,22,18,27] n-2
     [2,6,16,18,22,27] n-3

#### Big-O gösterimini yazınız.
    O(n²)

#### Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
    Best case:2
    Average case: 16 ve 18
    Worst case: 27
 
#### Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
    Average case

#### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
     [7,3,5,8,2,9,4,15,6]
     [2,3,5,8,7,9,4,15,6]
     [2,3,4,8,7,9,5,15,6]
     [2,3,4,5,7,9,8,15,6]

-------
# Merge Sort Projesi

    [16,21,11,8,12,22] -> Merge Sort

#### Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

              [16,21,11,8,12,22]
            /               \
        [16,21,11]        [8,12,22]
           /     \            /   \
       [16,21]  [11]      [8,12]  [22]
         /   \     \        /  \     \
       [16]  [21]   [11]   [8]  [12]  [22]
          \   /      /       \   /     /
           [16,21]  [11]      [8,12]  [22]
              \     /           \     /
             [11,16,21]        [8,12,22]
                   \             /
                  [8,11,12,16,21,22]

#### Big-O gösterimini yazınız.

    O(nlogn)
-----

# Binary Search Tree Projesi



    [7,5,1,8,3,6,0,9,4,2] -> Dizisinin Binary-Search-Tree aşamalarını yazınız

    Root 6'dır.
                          
                      6
                 /       \
             2            7
          /    \           \
         1      3           8
        /        \           \
       0         4            9
                   \  
                    5 