# 第8章 对象

在 Redis 中没有直接使用简单动态字符串（SDS）、双端链表、字典、压缩列表、整数集合等数据结构来实现键值对数据库，而是基于这些数据结构构建了一个对象系统，这个系统包括字符串对象、列表对象、哈希对象、集合对象和有序集合对象五种。

Redis 在执行命令之前，可以根据对象的类型来判断一个对象是否可以执行给定的命令。还可以针对不同的使用场景，为对象设置多种不同的数据结构实现，从而优化对象的使用效率。

除此之外， Redis 的对象系统还实现了基于引用计数技术的内存回收机制，来自动释放对象所占用的内存； 另外， Redis 还通过引用计数技术实现了对象共享机制，可以让多个数据库键共享同一个对象来节约内存。
```dataview
list from "600-Redis/340-Redis设计与实现/第8章 对象"
where contains(file.name,"8.")
sort file.name
```