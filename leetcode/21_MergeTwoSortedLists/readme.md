#### You have given the heads of two sorted linked lists `list1` and `list2`.
###### Merge the two lists in a one sorted list. The list should be made by splicing together the nodes of the first two lists.
######  Return the head of the merged linked list.

Example 1:

![Screenshot](https://assets.leetcode.com/uploads/2020/10/03/merge_ex1.jpg)

```http
Input: list1 = [1,2,4], list2 = [1,3,4]
Output: [1,1,2,3,4,4]
```
Example 2:
```http
Input: list1 = [], list2 = []
Output: []
```
Example 3:
```http
Input: list1 = [], list2 = [0]
Output: [0] 
```
Constraints:
- The number of nodes in both lists is in the range `[0, 50]`.
- `-100 <= Node.val <= 100`
- Both `list1` and `list2` are sorted in non-decreasing order.

---

***Method :-***
```java
public ListNode mergeTwoLists(ListNode list1, ListNode list2) {
        
}
```

***ListNode Class :-***
```java
// Definition for singly-linked list.
class ListNode {
    int val;
    ListNode next;
    ListNode() {}
    ListNode(int val) { this.val = val; }
    ListNode(int val, ListNode next) { this.val = val; this.next = next; }
}
```