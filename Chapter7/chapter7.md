# 第7章 压缩列表

压缩列表（ziplist）是列表键和哈希键的底层实现之一。

当一个列表键只包含少量列表项， 并且每个列表项要么就是小整数值， 要么就是长度比较短的字符串， 那么 Redis 就会使用压缩列表来做列表键的底层实现（**Redis 3.2 之后使用 quickList 实现**）。

* [7.1 压缩列表的构成](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter7/7.1.md)
* [7.2 压缩列表节点的构成](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter7/7.2.md)
* [7.3 连锁更新](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter7/7.3.md)
* [7.4 压缩列表API](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter7/7.4.md)
