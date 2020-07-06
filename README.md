# 整点力扣
今天整这么高儿

![img](img/birdvoltga.png)


# LC problem  

## 每日一题

|  题目                 |  done?|
|------|----|
|378. 有序矩阵中第K小的元素|二分法有点意思，左上右下为上下界  每次判断小于等于mid的个数，进而二分|
|74. 搜索二维矩阵  |二分, 与下方区别为 这个i-1行末<i行首  直接想成一维就行了|
|240. 搜索二维矩阵 II     | 与378的判断mid方法相同，左下（右上）出发 斗折而寻 |

## my job

| 公司   | 岗位 | 题目                 | 重复个数 | done?|
|------|----|--------------------|------|------|
| 字节跳动 | 算法 | 160\. 相交链表         | 1    |  step by step |
| 字节跳动 | 算法 | 215\. 数组中的第K个最大元素  | 1    | heapify/quickSort  |
| 字节跳动 | 算法 | 33\. 搜索旋转排序数组      | 1    | 判断哪边有序，再判断是否在里面 不然就在另一边   |
| 字节跳动 | 算法 | 200\. 岛屿数量         | 1    |  naive BFS |
| 字节跳动 | 算法 | 636\. 函数的独占时间      | 1    |  stack |
| 字节跳动 | 算法 | 103\. 二叉树的锯齿形层次遍历  | 1    | BFS  |
| 字节跳动 | 算法 | 297\. 二叉树的序列化与反序列化 | 1    |  DFS(先序，根先)/BFS |
| 字节跳动 | 算法 | 3\. 无重复字符的最长子串     | 1    |  滑窗 |
| 字节跳动 | 算法 | 572\. 另一个树的子树      | 1    |  两层递归 |

# ZBC!

![img](img/zbc.png)

## others
| 公司   | 岗位 | 题目                 | 重复个数 | done?|
|------|----|--------------------|------|------|
| 字节跳动 | 后端 | 25\. K 个一组翻转链表         | 4  | 模拟很简单 利用206改成返回头尾的形式|
| 字节跳动 | 后端 | 121\.买卖股票 122,123,188,309,714       | 4  | base case：dp[-1][k][0] = dp[i][0][0] = 0, dp[-1][k][1] = dp[i][0][1] = -infinity 状态转移方程：dp[i][k][0] = max(dp[i-1][k][0], dp[i-1][k][1] + prices[i]), dp[i][k][1] = max(dp[i-1][k][1], dp[i-1][k-1][0] - prices[i])|
| 字节跳动 | 后端 | 15\. 三数之和              | 3  | 双指针,注意对于重复问题，保证每次进循环的数大于之前的数就达到剪枝的效果|
| 字节跳动 | 后端 | 155\. 最小栈              | 3  | 两个栈 一个真栈，一个遇见小的就加进来|
| 字节跳动 | 后端 | 124\. 二叉树中的最大路径和       | 3  |dfs 注意复数，递归算一次自己的路，挑左右一个返回上一层 |
| 字节跳动 | 后端 | 199\.二叉树的右视图           | 3  | 简单的BFS|
| 字节跳动 | 后端 | 3\. 无重复字符的最长子串         | 3  | 滑窗，上面写过了|
| 字节跳动 | 后端 | 88\. 合并两个有序数组          | 3  |归并算法 |
| 字节跳动 | 后端 | 108\. 将有序数组转换为二叉搜索树    | 3  | 递归就vans了|
| 字节跳动 | 后端 | 110\. 平衡二叉树            | 3  | dfs返回深度就行了 |
| 字节跳动 | 后端 | 236\. 二叉树的最近公共祖先       | 3  | 继续深搜|
| 字节跳动 | 后端 | 33\. 搜索旋转排序数组          | 3  | 上面写过了|
| 字节跳动 | 后端 | 322\. 零钱兑换             | 3  | dp  背包问题 |
| 字节跳动 | 后端 | 83\. 删除排序链表中的重复元素      | 2  | |
| 字节跳动 | 后端 | 206\. 反转链表             | 2  | 迭代容易，递归 返回同一个的头，后面是head.next.next = head head.next = None|
| 字节跳动 | 后端 | 215\. 数组中的第K个最大元素      | 2  | |
| 字节跳动 | 后端 | 56\. 合并区间              | 2  | |
| 字节跳动 | 后端 | 146\. LRU缓存机制          | 2  | |
| 字节跳动 | 后端 | 102\. 二叉树的层序遍历         | 1  | |
| 字节跳动 | 后端 | 518\. 零钱兑换 II          | 1  |组合数排列数 |
| 字节跳动 | 后端 | 剑指 Offer 09\. 用两个栈实现队列 | 1  |A栈给B栈在输出 |
| 字节跳动 | 后端 | 54\. 螺旋矩阵              | 1  | |
| 字节跳动 | 后端 | 1299\.将每个元素替换为右侧最大元素   | 1  | |
| 字节跳动 | 后端 | 42\.接雨水                | 1  | |
| 字节跳动 | 后端 | 105\. 从前序与中序遍历序列构造二叉树  | 1  | |
| 字节跳动 | 后端 | 160\. 相交链表             | 1  | |
| 字节跳动 | 后端 | 139 单词拆分               | 1  | |
| 字节跳动 | 后端 | 67\. 二进制求和             | 1  | |
| 字节跳动 | 后端 | 230\.二叉搜索树中第K小的元素      | 1  | |
| 字节跳动 | 后端 | 70\. 爬楼梯               | 1  | |
| 字节跳动 | 后端 | 剑指 Offer 61\. 扑克牌中的顺子  | 1  | |
| 字节跳动 | 后端 | 543\. 二叉树的直径           | 1  | |
| 字节跳动 | 后端 | 112\. 路径总和             | 1  | |
| 字节跳动 | 后端 | 23\. 合并K个排序链表          | 1  | |
| 字节跳动 | 后端 | 1143\. 最长公共子序列         | 1  | |
| 字节跳动 | 后端 | 2\. 两数相加               | 1  | |
| 字节跳动 | 后端 | 3无重复的最长字符串长度           | 1  | 上面写过了|
| 字节跳动 | 后端 | 141\. 环形链表             | 1  | 先快慢针判断环 快针回原点齐步走找到入口|
| 字节跳动 | 后端 | 515\. 在每个树行中找最大值       | 1  | |
| 字节跳动 | 后端 | 31\. 下一个排列             | 1  |从右到左，找到第一个不是递增的i，和右边最小的大于i互换位置，然后反转[i+1:] |
| 字节跳动 | 后端 | 503\. 下一个更大元素 II       | 1  | |
| 字节跳动 | 后端 | 297\. 二叉树的序列化与反序列化     | 1  | |
| 字节跳动 | 后端 | 162\. 寻找峰值             | 1  | |
| 字节跳动 | 后端 | 221\. 最大正方形            | 1  | |
| 字节跳动 | 后端 | 128\. 最长连续序列           | 1  | |
| 字节跳动 | 后端 | 560\. 和为K的子数组          | 1  | |
| 字节跳动 | 后端 | 415\.字符串相加             | 1  | |
| 字节跳动 | 后端 | 328\. 奇偶链表             | 1  | |
| 字节跳动 | 后端 | 695\. 岛屿的最大面积          | 1  | |
| 字节跳动 | 后端 | 22\. 括号生成              | 1  | |
| 字节跳动 | 后端 | 32\. 最长有效括号            | 1  | |






