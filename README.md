# [DB-Q](https://github.com/OS-Q/DB-Q) 

Q系统数据库部分，用于管理各种生命周期的数据

[![sites](OS-Q/OS-Q.png)](http://www.os-q.com)

#### 边缘设备：[Edge-Q](https://github.com/OS-Q/Edge-Q)
#### 关于通信：[MQ-Q](https://github.com/OS-Q/MQ-Q)
#### 关于呈现：[UI-Q](https://github.com/OS-Q/UI-Q)
#### 功能调用：[FaaS](https://github.com/OS-Q/FaaS)

#### 系统构思：[OS-Q](https://github.com/OS-Q/OS-Q) 可访问 www.OS-Q.com

---

## [简介](https://github.com/OS-Q/DB-Q/wiki)


---

## 项目组成

---

### [MariaDB](https://github.com/mongodb)  

开源关系型数据库 

MariaDB 由 MySQL 的原创人员开发，并被维基百科，Facebook 甚至 Google 等技术巨头使用。 

MariaDB 是一种可为 MySQL 提供插件替换功能的数据库服务器。开发人员的首要关注点是安全性，在每个版本发布时，开发人员还会合并所有 MySQL 的安全修补程序，并在需要时对其进行增强。

#### 优点：

* 高可扩展性，易于集成

* 能够实时访问

* 具备 MySQL 的核心功能（MariaDB 是 MySQL 的替代方案）

* 备用存储引擎，服务器优化和补丁

* MariaDB 已经运作了20多年的广泛知识库

#### 缺点：

* 缺少密码复杂性插件

* 没有 memcached 界面

* 没有优化器跟踪

MySQL在一个领域上要比PostgreSQL更进一步，那就是它的触角延伸到了嵌入式领域，这是通过libmysqld实现的。

#### [MariaDB Docker](https://github.com/docker-library/mariadb) 

https://mariadb.com/

https://mariadb.org/

---

### [PostgreSQL](https://www.postgresql.org/)  


MySQL基于多线程而PostgreSQL基于多进程，PostgreSQL是针对事务型企业应用的严肃、功能完善的数据库，支持强ACID特性和很多数据完整性检查。


#### 优点：

* 创建自定义数据类型和查询方法

* 框架允许定义和创建自定义数据类型

* 以十几种编程语言运行存储过程：Java，Perl，Python，Ruby，Tcl，C / C ++及其自己的PL / pgSQL

* GiST（广义搜索树）系统：B 树，B+树，R 树，部分和树，以及排名的 B+ 树，提供不同的排序和搜索算法：

* 创建扩展如 CitusDB 更多的并行性，而不修改 Postgres 代码

 
#### 缺点：

* MVCC系统需要定期的“清理（vacuuming）”，高交易率环境中的问题

* 由强大的社区发展起来的，改进需要更大的努力



---

## [NoSQL](https://github.com/OS-Q/DB-Q/wiki) 

在关系型数据库中，除非你事先定义了表和字段的模式否则你无法向其中添加数据。

模式中包含了许多的信息：

- 主键 — 独一无二的标志就像ISBN唯一确定一条记录
- 索引 — 通常设置索引字段加快搜索的速度
- 关系 — 字段之间的逻辑连接
- 设计功能例如触发器和存储程序

在进行数据的逻辑操作之前我们必须要定义数据模式。数据模式可以在后期进行更改，但是对于模式的大改将会是非常复杂的。

在NoSQL的数据库中，数据在任何时候都可以进行添加。不需要事先去定义文档和集合。

---

### [MongoDB](https://github.com/mongodb)  

介于关系型和非关系型之间,面向文档的数据库，采用 binlog方式支持持久化的可靠性 


#### 优点：

* 文件验证

* 加密存储引擎

* 常用用例：

* 移动应用

* 产品目录

* 内容管理

* 具有内存存储引擎（beta）的实时应用程序

* 减少主要故障恢复的时间

#### 缺点：

* 不适合需要处理复杂事务的应用程序

* 不是传统应用程序的替代品

* 年轻的解决方案：软件更新快

---

### [Redis](https://github.com/antirez/redis)   

Redis兼具Memcached和Tokyo Tyrant优势的键值存，擅长处理数组类型的数据，具有非常快的处理速度
可以高速处理时间序列的数据，易于处理集合运算
拥有很多可以进行原子操作的方法
使用一致性散列(Consistent Hashing)算法来分散数据


---

###  锻造最美之器

###  www.OS-Q.com     |    qitas@qitas.cn
