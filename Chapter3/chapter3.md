链表提供了高效的节点重排能力， 以及顺序性的节点访问方式， 并且可以通过增删节点来灵活地调整链表的长度。因为 Redis 使用的 C 语

言并没有内置这种数据结构， 所以 Redis 构建了自己的链表实现。

链表在 Redis 中的应用非常广泛，比如列表键的底层实现之一就是链表，此外链表还用于发布与订阅、慢查询、监视器等功能，以及 Redis

 服务器本身使用链表来保存多个客户端的状态信息和构建客户端输出缓冲区（output buffer）。

* [3.1 链表和链表节点的实现](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter3/3.1.md)
* [3.2 链表和链表节点的API](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter3/3.2.md)
