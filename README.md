21. Merge Two Sorted Lists


You are given the heads of two sorted linked lists list1 and list2.

Merge the two lists in a one sorted list. The list should be made by splicing together the nodes of the first two lists.

Return the head of the merged linked list.


Example 1:

![image](https://user-images.githubusercontent.com/67059999/178348087-9e45b838-a536-4358-9e86-5c3a103e3b26.png)

Input: list1 = [1,2,4], list2 = [1,3,4]

Output: [1,1,2,3,4,4]


Example 2:

Input: list1 = [], list2 = []

Output: []


Example 3:

Input: list1 = [], list2 = [0]

Output: [0]


Constraints:

The number of nodes in both lists is in the range [0, 50].

-100 <= Node.val <= 100

Both list1 and list2 are sorted in non-decreasing order.
