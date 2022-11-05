# Insertion sort [22, 27, 16, 2, 18, 6]
### 1. Steps
```
[2, 27, 16, 22, 18, 6] - n
[2, 6, 16, 22, 18, 27] - n-1
[2, 6, 16, 22, 18, 27] - n-2
[2, 6, 16, 18, 22, 27] - 1
```
### 2. Big-O Notation
```
Worst case - O(n^2)
Average case - O(n^2)
Best case - O(n)
```

### 3. Time Complexity
```
Worst case
[22, 27, 16, 6, 18, 2]

Average case
[22, 27, 2, 6, 18, 16]

Best case
[2, 27, 22, 6, 18, 16]
```

### 4. What case 18 will be belong after sorting - [2, 6, 16, 18, 22, 27]
```
Average case
```

### 5. First 4 steps for [7,3,5,8,2,9,4,15,6]
```
1 - [2,3,5,8,7,9,4,15,6]
2 - [2,3,5,8,7,9,4,15,6]
3 - [2,3,4,8,7,9,5,15,6]
4 - [2,3,4,5,7,9,8,15,6]
```
