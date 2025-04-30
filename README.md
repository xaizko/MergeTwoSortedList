My solution to leetcode's "88. Merge Sorted Array"  
Runtime: 0ms  

This approach merges the 2 given arrays first and then sorts them with a nested loop.  

The first loop goes through every value in the nums1 array after it has been merged.  
The nested loop then takes the current value and checks it with all subsequent values to see if the current number is greater  
If it is, then swap them if it isnt then do nothing.
