字典树：
根节点不包含字符， 除根节点外每一个节点都只包含一个字符；
从根节点到某一节点， 路径上经过的字符连接起来， 为该节点对应的字符串；
查找字符串s的时间为O(s.length())；


AVL树：
任何节点的两个子树的高度最大差别为1；
AVL树本质上还是一棵二叉搜索树；

红黑树：

红黑树是一种特化的AVL树（平衡二叉树），都是在进行插入和删除操作时通过特定操作保持二叉查找树的平衡，从而获得较高的查找性能。

它虽然是复杂的，但它的最坏情况运行时间也是非常良好的，并且在实践中是高效的： 它可以在O(log n)时间内做查找，插入和删除，这里的n 是树中元素的数目。


