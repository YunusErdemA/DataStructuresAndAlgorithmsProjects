# Veri Yapıları ve Algoritmalar Projeleri
Patika.dev Profile: https://app.patika.dev/yunuserdemakpinar
# Proje 1
[22, 27, 16, 18, 6] -> Insertion Sort
- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
    1. [22, 27, 16, 2, 18, 6]
    2. [16, 22, 27, 2, 18, 6]
    3. [2, 16, 22, 27, 18, 6]
    4. [2, 16, 18, 22, 27, 6]
    5. [2, 6, 16, 18, 22, 27]
- Big-O gösterimini yazınız.
    - O(n^2)
- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
    - 18 ortada o yüzden average case.
- [7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
    1. [3, 7, 8, 2, 9, 4, 15, 6]
    2. [3, 7, 2, 8, 9, 4, 15, 6]
    3. [3, 2, 7, 8, 9, 4, 15, 6]
    4. [2, 3, 7, 8, 9, 4, 15, 6]
# Proje 2
[16, 21, 11, 8, 12, 22] -> Merge Sort
- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
    1. [16, 21, 11] [8, 12, 22]
    2. [16] [21, 11] [8] [12, 22]
    3. [16] [21] [11] [8] [12] [22]
    4. [16] [11, 21] [8] [12, 22]
    5. [11, 16, 21] [8, 12, 22]
    6. [8, 11, 12, 16, 21, 22]
- Big-O gösterimini yazınız.
    - O(nlogn)
# Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
1.  <pre>
    7
    </pre>
2.  <pre>
      7
     /
    5
    </pre>
3.  <pre>
        7
       /
      5
     /
    1
    </pre>
4.  <pre>
        7
       / \
      5   8
     /
    1
    </pre>
5.  <pre>
        7
       / \
      5   8
     /
    1
     \
      3
    </pre>
6.  <pre>
        7
       / \
      5   8
     / \
    1   6
     \
      3
    </pre>
7.  <pre>
          7
         / \
        5   8
       / \
      1   6
     / \
    0   3
    </pre>
8.  <pre>
          7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3
    </pre>
9.  <pre>
          7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3
         \
          4
    </pre>
10. <pre>
          7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3
       / \
      2   4
    </pre>
