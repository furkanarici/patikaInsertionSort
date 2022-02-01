# patikaInsertionSort

### Proje 1

1-[22,27,16,2,18,6] -> Insertion Sort verilen dizinin sort türüne göre aşamalarını yazınız.

  [22,27,16,2,18,6] n
  [2, 27,16,22,18,6] n-1
  [2,6, 16,22,18,27] n-2
  [2,6,16, 22,18,27] n-3
  [2,6,16,18, 22,27] 

2-Big-O gösterimini yazınız.
n + (n-1) + (n-2) + (n-3)
n.(n+1) / 2
n^2 + n/2

O(n^2)

3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

Best case = O(n)
Average case = O(n^2)
Worst case = 0(n^2)

4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Average case kapsamında girer.

5-[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

 [2, 3,5,8,7,9,4,15,6]
 [2,3, 4,8,7,9,5,15,6]
 [2,3,4, 5,7,9,8,15,6]
 [2,3,4,5, 6,9,8,15,7]