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




---------------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------------




206. Reverse Linked List

Given the head of a singly linked list, reverse the list, and return the reversed list.

Example 1:

![image](https://user-images.githubusercontent.com/67059999/178356041-91bd89e2-f76f-4ab6-8d7a-bf1dc9e3e811.png)

Input: head = [1,2,3,4,5]

Output: [5,4,3,2,1]


Example 2:

![image](https://user-images.githubusercontent.com/67059999/178356130-6f8baba9-9bf6-4155-be46-993d09d0105e.png)

Input: head = [1,2]

Output: [2,1]


Example 3:

Input: head = []

Output: []



Constraints:

The number of nodes in the list is the range [0, 5000].

-5000 <= Node.val <= 5000
 

Follow up: A linked list can be reversed either iteratively or recursively. Could you implement both?
