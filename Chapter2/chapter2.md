# 第2章 简单动态字符串

在 Redis 中，C 字符串只会作为字符串字面量（string literal）用在一些无需对字符串值修改的地方，如：打印日志。而当 Redis 需要一个可以被修改的字符串值时，会使用自己构建的一种名为简单动态字符串（simple dynamic string，SDS）的抽象类型，并将 SDS 作为Redis 的默认字符串表示。

除了用来保存数据库中的字符串值以外，SDS 还被作为缓冲区（Buffer）：AOF 模块中的 AOF 缓冲区，以及客户端状态中的输入缓冲区，都是由 SDS 实现。

- [2.1 SDS的定义](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter2/2.1.md)
- [2.2 SDS 与 C 字符串的区别](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter2/2.2.md)
- [2.3 SDS API](https://github.com/zhu-rundong/redis-notes/blob/main/Chapter2/2.3.md)

