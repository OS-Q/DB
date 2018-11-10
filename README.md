# DB-Q:[OS-Q数据库](https://github.com/OS-Q/DB-Q) 

Q系统数据库部分，用于管理各种生命周期的数据

[![sites](OS-Q/OS-Q.png)](http://www.os-q.com)

#### 更多关于：[OS-Q](https://github.com/OS-Q/OS-Q) 可访问 www.OS-Q.com

---

## 简介


---

## 组成

---

### MariaDB

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


https://mariadb.org/

---

### PostgreSQL


PostgreSQL 拥有超过 15 年的积累，是另一个明星级开源选择，运行于所有主要的操作系统，包括Linux，UNIX（AIX，BSD，HP-UX，SGI IRIX，Mac OS X，Solaris，Tru64）和 Windows。 PostgreSQL 还完全符合 ACID 要素（原子性，一致性，隔离性，持久性）。


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

### MongoDB

MongoDB创立于2007年，被称为“数据库巨头”。 由DoubleClick, ShopWiki 和Gilt Groupe 背后的开发人员开发，并由 Fidelity Investments，Goldman Sachs Group，Inc.，Intel Capital 这些机构投资。

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

### SQLite

一个强大的嵌入式关系型数据库管理系统。

SQLite是非凡的数据库，作为一个自包含、基于文件的数据库，SQLite提供了出色的工具集，可以处理所有类型的数据，没有什么限制。

一个应用使用SQLite时，它的功能直接被集成在其中，应用会直接访问包含数据的文件（即SQLite数据库）,而不是通过一些端口（port, socket）来交互。

#### 优点：

* 基于文件: 整个数据库都包含在磁盘上的一个文件中，因此它有很好的迁移性。

* 标准化: 尽管它看起来像个“简化版”的数据库，SQLite 确实支持 SQL。它略去了一些功能(RIGHT OUTER JOIN 和 FOR EACH STATEMENT)，但是，又同时增加了一些其他功能。

#### 缺点：

* 没有用户管理: 高级数据库都能支持用户系统，例如，能管理数据库连接对数据库和表的访问权限。但由于 SQLite 产生的目的和本身性质（没有多用户并发的高层设计），它没有这个功能。

* 缺乏额外优化性能的灵活性：从设计之初SQLite 就不支持使用各种技巧来进行额外的性能优化。这个库容易配置，容易使用。既然它并不复杂，理论上就无法让它比现在更快，其实现在它已经很快了。

---
