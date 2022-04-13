# 第8章 对象

在 Redis 中没有直接使用简单动态字符串（SDS）、双端链表、字典、压缩列表、整数集合等数据结构来实现键值对数据库，而是基于这些数据结构构建了一个对象系统，这个系统包括字符串对象、列表对象、哈希对象、集合对象和有序集合对象五种。

Redis 在执行命令之前，可以根据对象的类型来判断一个对象是否可以执行给定的命令。还可以针对不同的使用场景，为对象设置多种不同的数据结构实现，从而优化对象的使用效率。

除此之外， Redis 的对象系统还实现了基于引用计数技术的内存回收机制，来自动释放对象所占用的内存； 另外， Redis 还通过引用计数技术实现了对象共享机制，可以让多个数据库键共享同一个对象来节约内存。

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