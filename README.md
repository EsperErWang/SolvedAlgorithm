This page is used to record the problems that I have been solved, and they are classified by types. 

The answers are all the most understandable and the time and space complexity can be accepted in the interview.



##  Binary Search (Tree) & Binary Reduction:

### Easy:

[278. First Bad Version](https://leetcode.com/problems/first-bad-version)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/278.md)

[374. Guess Number Higher or Lower](https://leetcode.com/problems/guess-number-higher-or-lower)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/374.md)

[35. Search Insert Position](https://leetcode.com/problems/search-insert-position)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/35.md)

[367. Valid Perfect Square](https://leetcode.com/problems/valid-perfect-square)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/367.md)

<details>
  <summary>Note of 69</summary>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Binary search problem should be pay attention that the value in the loop may overflow, so 69 and 367 should use long. 
</details>

[69. Sqrt(x)](https://leetcode.com/problems/sqrtx)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/69.md)		

[367. Valid Perfect Square](https://leetcode.com/problems/valid-perfect-square)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/367.md)

### Medium:

[34. Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/34.md)

[162. Find Peak Element](https://leetcode.com/problems/find-peak-element)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/162.md)

[74. Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/74.md)

[240. Search a 2D Matrix II](https://leetcode.com/problems/search-a-2d-matrix-ii)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/240.md)

<details>
  <summary>Note of 33</summary>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;33, 81, 153, 154 can be solved in the same idea. 154 is a hard problem, but it is the pre-problem of 81.</br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If the elements are not necessarily with <b>distinct</b> values, <b>every</b> binary search loop should be pay attention to <b>nums[mid] == nums[last]</b>(or <b>nums[mid] == nums[first]</b>, every loop just choose one edge to check). When this situation happens, we can <b>only drop one</b> element from the nums, that is the last(or the first). 
</details>

[33. Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/33.md)

[81. Search in Rotated Sorted Array II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/81.md)

[153. Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/153.md)

<details>
  <summary>Note of 1011</summary>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1011, 410(hard), 1482, 1891 can be solved in the same idea. Try to find the possible result area, and then use the binary search to find the right result. 
</details>

[1011. Capacity To Ship Packages Within D Days](https://leetcode.com/problems/capacity-to-ship-packages-within-d-days)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/1011.md)

[1482. Minimum Number of Days to Make m Bouquets](https://leetcode.com/problems/minimum-number-of-days-to-make-m-bouquets)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/1482.md)

[1891. Cutting Ribbons](https://leetcode.com/problems/cutting-ribbons)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/1891.md)

### Hard:

[154. Find Minimum in Rotated Sorted Array II](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/154.md)

[410. Split Array Largest Sum](https://leetcode.com/problems/split-array-largest-sum)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Solution](https://github.com/EsperErWang/algorithm/blob/main/Binary%20Search%20(Tree)%20&%20Binary%20Reduction/410.md)

​		

