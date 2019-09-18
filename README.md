# 王道-数据结构-Data Structure

> 王道考研数据结构,书籍部分代码及算法题c语言实现
>
> 为了方便起见 代码编写以c语言为主，并使用了一些简单的c++stl
>
> 此仓库目的：学习和理解算法题，辅助考研，时间有限，故代码命名及注释未按代码规范，请见谅
>
> 由于此仓库并不是工程文件夹，故代码中可能有一些小的错误，欢迎pull request指正
>
> readme中可能部分公式无法解析 推荐使用**Typora**
>
> 欢迎大家一起敲代码！

## 使用指南

本仓库中的文件几乎每个`.cpp`均有main函数，故不能作为一个工程导入



### 使用方法1

在线阅读，学习代码思想，手写

### 使用方法2

1. 打开文件夹
2. 选择你需要的代码 
3. 复制出来，去除注释
4. 运行即可
5. 

## 线性表

**考试重点**

- 2019 9 14 课后算法题更新到7道，对于2020王道数据结构第18页

- 链表的直接插入排序 2019 9 18

## 栈



## 队列

- 括号匹配（搞定）
- 用栈实现递归式的非递归代码P90

## 树

- 先序 
  - 递归
  - 非递归
- 后序
  - 递归
  - 非递归
- 中序
  - 递归
  - 非递归
- 层序
- 线索化
- 求二叉树的高度
  - 递归
  - 非递归

### 平衡二叉树 

- 判断一棵树是否为平衡二叉树 （2019-9-6）

## 图

### 遍历问题

- 2019 7 28 新增DFS
- 2019 7 31 新增BFS

### 最小生成树问题

- Prim
- kruskal

### 最短路径问题

- Dijkstra
- Floyd-Warshall

### 拓扑排序



## 查找

### KMP算法

- get_next
- next_val
- kmp



## 排序算法

### 快速排序

- 递归版本已经完成
- 非递归版本待更新

### 堆排序

- 堆排序
  - 堆的建立
    - 从i/2开始—>1
  - 堆的删除
    - 堆的删除仅针对于根结点，每次删除时将根结点与最后一个元素交换然后自顶向下调整堆
  - 堆的插入
    - 插入时查找堆的末尾（即数组最后）然后自上而下的调整堆
  - 建立堆的时间复杂度$O（n）$
  - 调整堆的时间复杂度 $O（log_2n）$
- 判断一个堆是大顶堆的算法

### 归并排序

- 已经更新

### 希尔排序

- 2019 9 18更新完成



## 计划

- 2019-8-14 堆排序 + 归并排序
- 2019-8-15 Dijkstra
- 2019-8-18 Floyd
- 2019-8-21 Prim + Kruskal
- 2019-8-24 拓扑排序
- 2019-9-15 计划：**完成选择排序的链表实现**

*王道*考研数据结构书籍部分代码及算法题实现，2020考研总结

