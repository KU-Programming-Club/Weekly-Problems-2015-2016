## Intermediate 1 - Height of a Binary Tree
__Source__: http://bit.ly/1SGOJjD

The height of a binary tree is the number of nodes on the largest path from root
to any leaf. You are given a pointer to the root of a binary tree. Return the
height of the tree. You only have to complete the function.


#### Input Description

You are given a function,
```
int height_of_bt(node * root)
{

}
```


#### Output Description

Return a single value equal to the height of the binary tree.


#### Sample Input
```
Tree:

     3
   /   \
  5      2
/   \    /
1   4   6
       /
      7
```


#### Sample Output
```
4
```


#### Explanation

The maximum length root to leaf path is 3->2->6->7. There are 4 nodes in this path. Therefore the height of the binary tree = 4.
