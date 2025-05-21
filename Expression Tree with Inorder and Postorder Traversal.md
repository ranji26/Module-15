# Ex. No: 15C - Expression Tree with Inorder and Postorder Traversal

## AIM:
To write a Python program to build the given expression tree and print the inorder and postorder traversals.

---

## ALGORITHM:

1. **Start the program.**
2. Import the required modules (`build` and `Node` from `binarytree`).
3. Define a list `x` representing the expression tree in pre-order fashion (with `None` for missing nodes).
4. Use the `build()` function to generate the binary tree.
5. Print the **inorder** and **postorder** traversal of the tree.
6. **End the program.**

---

## PROGRAM:

```
from binarytree import build,Node
x=['/','*','+','+',4,'-',2,3,1,None,None,9,5,None,None]
root=build(x)
print(root.inorder)
print(root.postorder)
```

## OUTPUT
![image](https://github.com/user-attachments/assets/e701bd8f-7df0-4ac7-82df-e4375b24d6e9)


## RESULT
Thus a Python program to build the given expression tree and print the inorder and postorder traversals is implemented successfully.
