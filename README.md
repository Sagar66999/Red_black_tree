
# Red-Black Tree Implementation in C++

##  Overview

This implements a **Red-Black Tree** in C++ with support for:

* Dynamic insertion
* Automatic balancing using rotations
* Inorder traversal
* User input

A Red-Black Tree is a **self-balancing Binary Search Tree** that guarantees
`O(log n)` time complexity for insertion, deletion, and search operations.

---

##  Key Concepts Used

* Binary Search Tree (BST)
* Tree rotations (Left & Right)
* Recoloring of nodes
* Pointer-based tree structure
* Object-Oriented Programming (OOP)

---

##  Features

* Insert any number of integers
* Tree remains balanced automatically
* Inorder traversal displays sorted order
* Works for large inputs efficiently

---

##  How to Compile and Run

### Using g++ (Linux / Windows / Mac)

```bash
g++ RB_tree.cpp -o simple
./simple
```

(Replace `RB_tree.cpp` with your file name if different)

---

## Sample Input

```
Enter number of nodes: 5
Enter values:
10 20 30 15 5
```

##  Output

```
Inorder Traversal: 5 10 15 20 30
```

---

##  File Structure

```
RB_tree.cpp   → Main source file  
README.md    → Project documentation  
```

---

## Red-Black Tree Properties

1. Every node is either **RED or BLACK**
2. Root is always **BLACK**
3. No two consecutive RED nodes
4. Every path from root to leaf has same number of BLACK nodes
5. Tree remains approximately balanced

---


