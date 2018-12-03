# [DB-Q](https://github.com/OS-Q/DB-Q) 

[![sites](OS-Q/OS-Q.png)](http://www.os-q.com)

#### 系统硬件：[Edge](https://github.com/OS-Q/Edge-Q)
#### 系统服务：[QaaS](https://github.com/OS-Q/QaaS)
#### 系统交互：[UI-Q](https://github.com/OS-Q/UI-Q)
#### 系统存储：[DB-Q](https://github.com/OS-Q/DB-Q)
#### 系统通信：[MQ-Q](https://github.com/OS-Q/MQ-Q)

## [DB-Q简介](https://github.com/OS-Q/DB-Q/wiki)

Q系统数据库部分，用于管理各种生命周期的数据，DB-Q用于设备的本地数据存储

#### 关于系统架构：[OS-Q](https://github.com/OS-Q/OS-Q)

---

# [Q1](https://github.com/OS-Q/Q1) 

## [FatFS](https://www.sqlite.org/)  

FatFs是一个通用的文件系统模块，用于在小型嵌入式系统中实现FAT文件系统。 FatFs 的编写遵循ANSI C，因此不依赖于硬件平台。它可以嵌入到便宜的微控制器中，如 8051, PIC, AVR, SH, Z80, H8, ARM 等等，不需要做任何修改。


---

# [Q2](https://github.com/OS-Q/Q2) 

## [SQLite](https://www.sqlite.org/)  

SQLite，是一款轻型的数据库，是遵守ACID的关系型数据库管理系统，它包含在一个相对小的C库中。它占用资源非常的低，大致13万行C代码, 4.43M，在嵌入式设备中，可能只需要几百K的内存就够了。

---

# [Q3](https://github.com/OS-Q/Q3) 

## [MariaDB](https://github.com/MariaDB)  

开源关系型数据库 

MariaDB 由 MySQL 的原创人员开发，并被维基百科，Facebook 甚至 Google 等技术巨头使用。 

MariaDB 是一种可为 MySQL 提供插件替换功能的数据库服务器。开发人员的首要关注点是安全性，在每个版本发布时，开发人员还会合并所有 MySQL 的安全修补程序，并在需要时对其进行增强。

- 优点：高可扩展性，易于集成，能够实时访问，备用存储引擎，服务器优化和补丁

- 缺点：缺少密码复杂性插件，没有memcached界面，没有优化器跟踪



#### [MariaDB Docker](https://github.com/docker-library/mariadb) 
#### [MariaDB site](https://mariadb.org/) 
#### [MariaDB Go](https://github.com/go-sql-driver/mysql.git) 

MariaDB主要对手是PostgreSQL，但是MySQL在嵌入式领域要比PostgreSQL更进一步，这是通过libmysqld实现的。

## [PostgreSQL](https://www.postgresql.org/)  


MySQL基于多线程而PostgreSQL基于多进程，PostgreSQL是针对事务型企业应用的严肃、功能完善的数据库，支持强ACID特性和很多数据完整性检查。


- 优点：创建自定义数据类型和查询方法，框架允许定义和创建自定义数据类型，多种编程语言运行存储过程：Java，Perl，Python，Ruby，Tcl，C / C ++及其自己的PL / pgSQL；创建扩展如 CitusDB 更多的并行性，而不修改 Postgres 代码

 
- 缺点：MVCC系统需要定期的清理（vacuuming），高交易率环境中的问题，由社区发展起来的，改进需要更大的努力


NoSQL数据库将数据存储于缓存之中，关系型数据库将数据存储在硬盘中，通常情况下，NoSQL比SQL语言更快。

在关系型数据库中，除非你事先定义了表和字段的模式否则你无法向其中添加数据。在NoSQL的数据库中，数据在任何时候都可以进行添加。不需要事先去定义文档和集合。


非关系型数据库的优势：

- 性能NOSQL是基于键值对的，可以想象成表中的主键和值的对应关系，而且不需要经过SQL层的解析，所以性能非常高。

- 可扩展性同样也是因为基于键值对，数据之间没有耦合性，所以非常容易水平扩展。

关系型数据库的优势：

- 复杂查询可以用SQL语句方便的在一个表以及多个表之间做非常复杂的数据查询。

- 事务支持使得对于安全性能很高的数据访问要求得以实现。对于这两类数据库，对方的优势就是自己的弱势，反之亦然。


---

# [Q4](https://github.com/OS-Q/Q4) 

## [MongoDB](https://github.com/mongodb)  

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


## [Redis](https://github.com/antirez/redis)   

Redis兼具Memcached和Tokyo Tyrant优势的键值存，擅长处理数组类型的数据，具有非常快的处理速度,可以高速处理时间序列的数据，易于处理集合运算；拥有很多可以进行原子操作的方法，使用一致性散列(Consistent Hashing)算法来分散数据


---

###  qitas@qitas.cn
####  [Q redefined the scope of Operation System](http://www.OS-Q.com)

