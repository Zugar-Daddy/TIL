# DSA

-> Shell Sorting, merging sorted arrays with constant space.

-> Find Missing and Repeating number by forming two equations of Sum of All N natural numbers and Sum of squares of all N natural numbers

-> The optimal solution for Count Inversions problem is Merge Sort Algo. We keep track of count whenever right pointer is smaller and cnt += mid - left + 1;

-> Reverse Pairs is just a sibling of Count Inversion Problem, here instead of left > right, we need left > 2 * right. Easy implementation with merge sort. Branch out the recursion calls with another function called count pairs which runs from low to mid, and sees if the right element satisfies our condition. After the loop has run, ans += right - (mid + 1);
