# 第4章 字典

字典， 又称符号表（symbol table）、关联数组（associative array）或者映射（map）， 是一种用于保存键值对（key-value pair）的抽象数据结构。

字典经常作为一种数据结构内置在很多高级编程语言里面， 但 Redis 所使用的 C 语言并没有内置这种数据结构， 因此 Redis 构建了自己的字典实现。

Redis 的数据库就是使用字典来作为底层实现的， 对数据库的增、删、查、改操作也是构建在对字典的操作之上的。

除了用来表示数据库之外， 字典还是哈希键的底层实现之一： 当一个哈希键包含的键值对比较多， 又或者键值对中的元素都是比较长的字符串时， Redis 就会使用字典作为哈希键的底层实现。

* [4.1 字典的实现](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter4/4.1.md)
* [4.2 哈希算法](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter4/4.2.md)
* [4.3 解决键冲突](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter4/4.3.md)
* [4.4 rehash](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter4/4.4.md)
* [4.5 渐进式rehash](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter4/4.5.md)
* [4.6 字典API](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter4/4.6.md)
