# 2022年最新最全JAVA服务端面试题

1100+面试题，涵盖JAVA、数据库、REDIS等17大类、77个小类。

1. Hash 索引和 B+树区别是什么？你在设计索引是怎么抉择的？
2. 描述下Redis 的回收策略（淘汰策略）？
3. 描述下JVM类加载机制与对象的生命周期？
4. 为什么 HashMap 中 String、Integer 这样的包装类适合作为 K？
5. 谈谈你对数据库线程池的理解？
6. MySQL存储引擎MyISAM与InnoDB区别？
7. 如何让正在运行的线程暂停一段时间？
8. SpringBean容器的生命周期是什么样的？
9. 数据类型有哪些优化策略？
10. 什么是聚簇索引？何时使用聚簇索引与非聚簇索引？
11. 偏向锁、轻量级锁和重量级锁的区别？
12. Java中有哪几种线程创建方式？ 
13. Zookeeper在Kafka中的作用知道吗？
14. MVCC是什么？
15. HashMap和Hashtable的区别？
16. Redis 集群最大节点个数是多少？
17. EXPLAIN的字段有哪些，具有什么含义？
18. AQS独占式获取/释放锁的原理？
19. MySQL的主从复制了解吗？
20. limit 1000000 加载很慢的话，你是怎么解决的呢？
21. 简单谈谈你对AQS的理解？
22. 静态代理和动态代理的区别，什么场景使用？
23. 说一下大表查询的优化方案？
24. ConcurrentHashMap和Hashtable的区别？
25. 轻量级锁是什么？
26. 多线程会产生哪些并发问题？
27. Java中ConcurrentHashMap的并发度是什么？
28. Redis 事务相关的命令有哪几个？
29. 数据库索引的原理，为什么要用 B+树，为什么不用二叉树？
30. 什么是幻读，脏读，不可重复读？
31. 线程的生命周期有哪些状态？
32. MySQL里有2000w数据，redis中只存20w的数据，如何保证redis中的数据都是热点数据？
33. 在Java中wait和sleep方法的不同？
34. Bean工厂和Applicationcontexts有什么区别？
35. 线程池都有哪些状态？
36. 如何查询慢SQL产生的原因？
37. 什么是聚簇索引？
38. 乐观锁和悲观锁的理解及如何实现，有哪些实现方式？
39. 锁优化有哪些策略？
40. 如何理解Spring中的代理？
41. MySQL索引底层结构为什么使用B+树？
42. 如何理解JVM内存分配策略？
43. Redis的持久化机制是什么？各自的优缺点？
44. String和StringBuilder、StringBuffer的区别？
45. 幻读是什么，用什么隔离级别可以防止幻读？

| ![image-20221017181607862](https://writting.oss-cn-beijing.aliyuncs.com/image-20221017181607862.png) | ![2022-10-17 11:28发布的图片](https://writting.oss-cn-beijing.aliyuncs.com/875ca43017d84b8882065031abe490f0~tplv-k3u1fbpfcp-no-mark:800:0:0:0.png) | ![2022-10-17 11:28发布的图片](https://writting.oss-cn-beijing.aliyuncs.com/5929169e85f9404c8a4ab2f5e2de4dfe~tplv-k3u1fbpfcp-no-mark:800:0:0:0-20221017193247784.png) | ![2022-10-17 11:28发布的图片](https://writting.oss-cn-beijing.aliyuncs.com/4aa7c56001344e3b8f193f0d5d032046~tplv-k3u1fbpfcp-no-mark:800:0:0:0.png) |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![2022-10-17 11:28发布的图片](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/46abf60ab92c412ba5f2cc78f0050b1e~tplv-k3u1fbpfcp-no-mark:800:0:0:0.png) | ![2022-10-17 11:28发布的图片](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/3969b82aadf7473a9ca8af5ec47f7f9f~tplv-k3u1fbpfcp-no-mark:800:0:0:0.png) | ![2022-10-17 11:28发布的图片](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/0b9b7271ebd040c8a894983aca89a5c4~tplv-k3u1fbpfcp-no-mark:800:0:0:0.png) | ![口袋书小程序码](https://writting.oss-cn-beijing.aliyuncs.com/%E5%8F%A3%E8%A2%8B%E4%B9%A6%E5%B0%8F%E7%A8%8B%E5%BA%8F%E7%A0%81.jpg) |


