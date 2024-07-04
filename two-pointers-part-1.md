# Topic 2 - Two Pointers
![Two Pointer Dark Mode](https://github.com/WomenInSoftwareEngineeringJP/algorithms-data-structures/assets/77953414/9dd71c19-aa31-4515-950c-2135972532bb)

# 📘 Theory
## Introduction to Two Pointers
The Two Pointers technique involves using two pointers to iterate through the data structure, often from different ends, to solve various problems more efficiently. This technique is particularly useful for problems involving arrays and linked lists.

### Time Complexity
- Best Case: O(n)
- Average Case: O(n)
- Worst Case: O(n)

### Space Complexity
- O(1) for iterative approaches

## 🔄 Variations of Binary Search
- Fast and Slow Pointer: The fast and slow pointer technique, also known as the tortoise and hare algorithm, involves using two pointers moving at different speeds. This technique is useful for detecting cycles in linked lists, finding the middle of a linked list, and other problems where relative movement between pointers is key.
- Back-to-Back Pointers: Two pointers start at the same position and move based on certain conditions, often used in problems involving searching or modifying the sequence.

# 📚 Resources

## Websites

* AfterAcademy [https://afteracademy.com/blog/what-is-the-two-pointer-technique/](https://afteracademy.com/blog/what-is-the-two-pointer-technique/)

* AlgoDaily [https://algodaily.com/lessons/using-the-two-pointer-technique](https://algodaily.com/lessons/using-the-two-pointer-technique)

## Videos:

* [Geekific - What is the Two-Pointers Technique & How to use it? | Two-Pointers Approaches Explained](https://www.youtube.com/watch?v=VEPCm3BCtik)

* [Team AlgoDaily - How to Use the Two Pointer Technique](https://www.youtube.com/watch?v=-gjxg6Pln50)

* [AlgoMonster - Two Pointers Technique](https://www.youtube.com/watch?v=xZ4AfXHQ1VQ)

## Articles:

* [Intro to Algorithms: Two Pointers Technique](https://medium.com/geekculture/intro-to-algorithms-two-pointers-technique-b37f962eab5)

* [The Two-Pointer Pattern: A Must-Have Skill for Every Coder](https://python.plainenglish.io/the-two-pointer-pattern-a-must-have-skill-for-every-coder-a792b0d0617d)

* [Algorithm Two Pointer Technique: (JavaScript)](https://medium.com/@kevinlai76/algorithm-two-pointer-technique-a27103ed7ea1)

* [Two Pointers Approach — Python Code](https://towardsdatascience.com/two-pointer-approach-python-code-f3986b602640)

* [Array Two pointers](https://medium.com/analytics-vidhya/array-two-pointers-4b8d62d2b8a)

# 💻 Two Pointers Problems

## Problems solved during the session

### Part I
* [977. Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/?envType=study-plan&id=algorithm-i)
* [189. Rotate Array](https://leetcode.com/problems/rotate-array/?envType=study-plan&id=algorithm-i)
* [283. Move Zeroes](https://leetcode.com/problems/move-zeroes/?envType=study-plan&id=algorithm-i)
* [167. Two Sum II - Input Array Is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/?envType=study-plan&id=algorithm-i)
* [344. Reverse String](https://leetcode.com/problems/reverse-string/?envType=study-plan&envId=algorithm-i&plan=algorithm)
* [557. Reverse Words in a String III](https://leetcode.com/problems/reverse-words-in-a-string-iii/?envType=study-plan&envId=algorithm-i&plan=algorithm)

### Part II
* [82. Remove Duplicates from Sorted List II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii)
* [15. 3Sum](https://leetcode.com/problems/3sum)
* [844. Backspace String Compare](https://leetcode.com/problems/backspace-string-compare)
* [986. Interval List Intersections](https://leetcode.com/problems/interval-list-intersections)
* [11. Container With Most Water](https://leetcode.com/problems/container-with-most-water)

## Problem solving reference
* Leetcode [https://leetcode.com/articles/two-pointer-technique/](https://leetcode.com/articles/two-pointer-technique/)

## More problems to practice Two Pointers
* [Leetcode 876. Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/?envType=study-plan&envId=algorithm-i&plan=algorithm)
* [Leetcode 19. Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/?envType=study-plan&envId=algorithm-i&plan=algorithm)

## 🔍 Tips and Tricks
- Use it when the problem involves a sorted array or requires processing elements from both ends towards the center.
- It reduces the need for nested loops, thus improving time complexity from O(n^2) to O(n)
- Common scenarios for two pointers are finding pairs in arrays, reversing arrays, and solving problems involving subarrays or substrings.
