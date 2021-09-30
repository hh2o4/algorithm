# algorithm
算法及数据结构小记

## 树

### 完全二叉树（complete）

从上往下，从左往右编号节点，与完美二叉树(perfect)对应节点编号相同。

![complete_tree](https://user-images.githubusercontent.com/20169617/135379779-5731d01c-997f-4e57-ad32-193d04acbd28.jpg)

### 满二叉树 （full）

树中的节点，要么是叶子节点，要么就是有两个孩子的节点。

[注]：和国内定义的满二叉树概念不同，国内定义的满二叉树和完美二叉树相同。

![full_tree](https://user-images.githubusercontent.com/20169617/135380815-c8fdfad8-763e-4458-9127-7cf7ab961bde.png)


### 完美二叉树 （perfect）

每一层节点都达到最大值（所有叶子节点全在最后一层，除最后一层叶子节点，其余节点均有两个孩子）

![complete_tree](https://user-images.githubusercontent.com/20169617/135380805-9acaeea9-0b06-436f-9107-d40cc3bb10d0.png)

### BST 二叉搜索树 （AVL 树，红黑树，B+ 树，线段树）

BST的每个节点，其左子树节点的值都比它小，其右子树节点的值都比它大。BST每个节点的左右子树，分别都是BST。

[重要性质]：BST 的中序遍历结果是有序的（升序）
