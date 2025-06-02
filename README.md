# Day34-50-days-coding-challenge


## 🚀 Problems Covered

---

### 🌳 1. Flatten Binary Tree to Linked List
**Problem:**  
Given the root of a binary tree, flatten the tree into a "linked list" in-place where:  
- Right child points to the next node in pre-order traversal,  
- Left child is always null.

**Approach:**  
- Use **pre-order traversal** (root-left-right) to visit nodes.
- Maintain a pointer to the previous node and set its `right` to the current node and `left` to `null`.
- Use either **recursion** or **iterative stack-based traversal**.
- Ensure an in-place transformation with O(1) additional space (excluding recursion stack).

**Example:**  
- Input: `[1,2,5,3,4,null,6]`  
- Output: `[1,null,2,null,3,null,4,null,5,null,6]`

**Complexity:**  
- Time: O(n), Space: O(n) for recursion stack.

---

### 🔤 2. Length of Last Word
**Problem:**  
Given a string `s`, return the length of the last word.

**Approach:**  
- **Strip trailing spaces** and split by spaces to get the last word.  
- Alternatively, traverse from the end of the string and count characters until a space is found.  

**Example:**  
- Input: `"Hello World"`  
- Output: `5`  
- Input: `"   fly me   to   the moon  "`  
- Output: `4`

**Complexity:**  
- Time: O(n), Space: O(1) if processed with pointers.

---

## 🔥 Key Takeaways
- Efficient **binary tree restructuring** techniques.
- In-place manipulations in **binary trees** and **string traversal**.
- Develop a deep understanding of **pre-order traversal** and **pointer usage**.
