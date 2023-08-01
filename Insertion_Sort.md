[22, 27, 16, 2, 18 ,6] -> Insertion Sort

Steps:

27 -> [22, 27, 16, 2, 18, 6]

16 -> [16, 22, 27, 2, 18, 6]

2  -> [2, 16, 22, 27, 18, 6] 

18 -> [2, 16, 18, 22, 27, 6] 

6  -> [2, 6, 16, 18, 22, 27] 

Big-O Notation
for loop 1 -> Surfing the numbers in the array 
for loop 2 -> Comparing the numbers with the number holding by loop 1
2 for loops => O(n^2)

Time complexity
After sorting the array, number 18 is in center of the array. => Average Case

[7, 3, 5, 8, 2, 9, 4, 15, 6] -> Selection Sort

smallest num = 2 => [2, 7, 3, 5, 8, 9, 4, 15, 6]

[7, 3, 5, 8, 9, 4, 15, 6] 
smallest num = 3 => [3, 7, 5, 8, 9, 4, 15, 6] 

[7, 5, 8, 9, 4, 15, 6] 
smallest num = 4 => [4, 7, 5, 8, 9, 15, 6]

[7, 5, 8, 9, 15, 6]
smallest num = 5 => [5, 7, 8, 9, 15, 6]

[7, 8, 9, 15, 6]
smallest num = 6 => [6, 7, 8, 9, 15]