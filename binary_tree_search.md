# Binary Tree Search Projesi

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] -> Binary-Search-Tree 

## Aşamalar:

5 -> root

7>5 - root'un sağından 7 bulunur

1<5 - root'un solundan 1 bulunur

8>5; 8>7 - 7'nin sağından 8 bulunur

3<5; 3>1 - 1'in sağından 3 bulunur

6>5; 6<7 - 7'nin solundan 6 bulunur

0<5; 0<1 - 1'in solundan 0 bulunur

9>5; 9>7; 9>8 - 8'in sağından 9 bulunur

4<5; 4>1; 4>3 - 3'ün sağından 4 bulunur

2<5; 2>1; 2<3 - 3'ün solundan 2 bulunur

              
               5

          /          \

       1                7

     /   \          /      \

    0      3      6          8

          /  \                 \

         2     4                 9
