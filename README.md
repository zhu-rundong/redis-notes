**《Redis 设计与实现》学习笔记**

# 目录

## 第一部分 数据结构与对象

## [第2章  简单动态字符串](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter2/chapter2.md)

- [2.1 SDS的定义](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter2/2.1.md)
- [2.2 SDS 与 C 字符串的区别](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter2/2.2.md)
- [2.3 SDS API](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter2/2.3.md)

## [第3章 链表](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter3/chapter3.md)

* [3.1 链表和链表节点的实现](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter3/3.1.md)
* [3.2 链表和链表节点的API](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter3/3.2.md)

## [第4章 字典](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter4/chapter4.md)

* [4.1 字典的实现](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter4/4.1.md)
* [4.2 哈希算法](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter4/4.2.md)
* [4.3 解决键冲突](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter4/4.3.md)
* [4.4 rehash](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter4/4.4.md)
* [4.5 渐进式rehash](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter4/4.5.md)
* [4.6 字典API](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter4/4.6.md)

## [第5章 跳跃表](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter5/chapter5.md)
* [5.1 跳跃表的实现](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter5/5.1.md)
* [5.2 跳跃表API](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter5/5.2.md)

## [第6章 整数集合](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter6/chapter6.md)

* [6.1 整数集合的实现](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter6/6.1.md)
* [6.2-6.4 升级&升级的好处&降级](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter6/6.2-6.4.md)
* [6.5 整数集合API](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter6/6.5.md)

## [第7章 压缩列表](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter7/chapter7.md)

* [7.1 压缩列表的构成](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter7/7.1.md)
* [7.2 压缩列表节点的构成](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter7/7.2.md)
* [7.3 连锁更新](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter7/7.3.md)
* [7.4 压缩列表API](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter7/7.4.md)

## [第8章 对象](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter8/chapter8.md)

- [8.1 对象的类型和编码](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter8/8.1.md)
- [8.2 字符串对象](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter8/8.2.md)
- [8.3 列表对象](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter8/8.3.md)
- [8.4 哈希对象](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter8/8.4.md)
- [8.5 集合对象](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter8/8.5.md)
- [8.6 有序集合对象](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter8/8.6.md)
- [8.7 类型检查与命令多态](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter8/8.7.md)
- [8.8 内存回收](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter8/8.8.md)
- [8.9 对象共享](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter8/8.9.md)
- [8.10 对象的空转时长](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter8/8.10.md)
