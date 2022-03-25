# 第5章 跳跃表

跳跃表（skiplist）是一种有序数据结构， 它通过在每个节点中维持多个指向其他节点的指针， 从而达到快速访问节点的目的。

跳跃表支持平均 **O(log N)** 最坏 **O(N)** 复杂度的节点查找， 还可以通过顺序性操作来批量处理节点。

 在 Redis 中，只在两个地方用到了跳跃表， 一个是实现有序集合键， 另一个是在集群节点中用作内部数据结构。

**本章只对 Redis 的跳跃表实现进行介绍，跳跃表的数据结构相关信息可参考：**["跳表"](siyuan://blocks/20220317211054-7mqjldi)

* [5.1 跳跃表的实现](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter5/5.1.md)
* [5.2 跳跃表API](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter5/5.2.md)
