# Ex. No: 15A - Build a Binary Tree with Float Values

## AIM:
To write a Python program to build a binary tree with a root, left, and right node using floating-point values.

---

## ALGORITHM:

1. **Start the program.**
2. **Import** the `Node` class from the `binarytree` module.
3. **Create a root node** using the `Node` class and assign a floating-point value.
4. **Create left and right child nodes** for the root with float values.
5. **Convert the tree** to a list and print the list of nodes.
6. **End the program.**

---

## PYTHON PROGRAM

```
from binarytree import Node
l=[]
for i in range(0,3):
    a=input()
    l.append(a)
root = Node(l[0])
root.left = Node(l[1])
root.right = Node(l[2])
print("Binary Tree : ")
for i in root.values:
    print(i,'-->',end=" ")
```

## OUTPUT
![image](https://github.com/user-attachments/assets/26a81831-58ca-4b5d-a7a7-11d7b0c61890)


## RESULT
Thus a Python program to build a binary tree with string & integer values is implemented successfully.
