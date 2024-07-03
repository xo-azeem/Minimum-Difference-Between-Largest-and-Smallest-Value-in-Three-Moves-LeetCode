# Minimum Difference Between Largest and Smallest Value in Three Moves

LeetCode Q # 1509.

You are given an integer array nums.

In one move, you can choose one element of nums and change it to any value.

Return the minimum difference between the largest and smallest value of nums after performing at most three moves.

Example 1:

> Input: nums = [5,3,2,4]</br>
> Output: 0</br>
> Explanation: We can make at most 3 moves.</br>
> In the first move, change 2 to 3. nums becomes [5,3,3,4].</br>
> In the second move, change 4 to 3. nums becomes [5,3,3,3].</br>
> In the third move, change 5 to 3. nums becomes [3,3,3,3].</br>
> After performing 3 moves, the difference between the minimum and maximum is 3 - 3 = 0.

Example 2:

> Input: nums = [1,5,0,10,14]</br>
> Output: 1</br>
> Explanation: We can make at most 3 moves.</br>
> In the first move, change 5 to 0. nums becomes [1,0,0,10,14].</br>
> In the second move, change 10 to 0. nums becomes [1,0,0,0,14].</br>
> In the third move, change 14 to 1. nums becomes [1,0,0,0,1].</br>
> After performing 3 moves, the difference between the minimum and maximum is 1 - 0 = 1.</br>
> It can be shown that there is no way to make the difference 0 in 3 moves.

Example 3:

> Input: nums = [3,100,20]</br>
> Output: 0</br>
> Explanation: We can make at most 3 moves.</br>
> In the first move, change 100 to 7. nums becomes [3,7,20].</br>
> In the second move, change 20 to 7. nums becomes [3,7,7].</br>
> In the third move, change 3 to 7. nums becomes [7,7,7].</br>
> After performing 3 moves, the difference between the minimum and maximum is 7 - 7 = 0.</br>

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Minimum-Difference-Between-Largest-and-Smallest-Value-in-Three-Moves-LeetCode/assets/171427226/f4520aa0-4d8d-404f-b1bf-8010d0b54114)

  Time complexity: O(n log n).</br>Space complexity: O(1).
</div>
