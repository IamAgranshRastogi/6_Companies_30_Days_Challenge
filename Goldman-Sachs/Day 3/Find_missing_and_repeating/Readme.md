# Find Missing and Repeating Number in Array 
Given an unsorted array of size n. Array elements are in the range of 1 to n. One number from set {1, 2, …n} is missing and one number occurs twice in the array. Find these two numbers.
### Example 1: 
### Input: 
arr[] = {3, 1, 3}
### Output: 
Missing = 2, Repeating = 3
### Explanation: 
In the array, 2 is missing and 3 occurs twice 

### Example 2:
### Input: 
arr[] = {4, 3, 6, 2, 1, 1}
### Output: 
Missing = 5, Repeating = 1

### Your Task:
You don't need to read input or print anything. Your task is to complete the function findTwoElement() which takes the array of integers arr and n as parameters and returns an array of integers of size 2 denoting the answer ( The first index contains B and second index contains A.)

### Expected Time Complexity: 
O(N)
### Expected Auxiliary Space: 
O(1)

### Constraints:
2 ≤ N ≤ 105  ,   
1 ≤ Arr[i] ≤ N
