# sqlstudy
## 数据库和SQL
### 数据库是什么
- 数据库（Database,DB)：将大量数据保存起来，通过计算机加工而成的可以进行高效访问的数据集合。
- 数据库管理系统（Database Management System，DBMS）：用来管理数据库的计算机系统称为数据库管理系统。
- 数据库种类：层次数据库、关系数据库（由行和列组成的二维表来管理数据）、面向对象数据库、xml数据库、键值存储系统。
- SQL：为操作数据库而开发的语言，SQL通过一条语句来描述想要进行的操作，发送给RDBMS。原则上SQL语句都会使用分号结尾

### SQL语句及其种类
#### 根据对 RDBMS 赋予的指令种类的不同，SQL 语句可以分为以下三类。
DDL（Data Definition Language，数据定义语言）用来创建或者删除存储数据用的数据库以及数据库中的表等对象。
 - CREATE：创建数据库和表等对象
 - DROP：删除数据库和表等对象
 - ALTER：修改数据库和表等对象的结构

DML（Data Manipulation Language，数据操纵语言）用来查询或者变更表中的记录
- SELECT ：查询表中的数据
- INSERT ：向表中插入新数据
- UPDATE ：更新表中的数据
- DELETE ：删除表中的数据

DCL（Data Control Language，数据控制语言） 用来确认或者取消对数据库中的数据进行的变更。除此之外，还可以对RDBMS 的用户是否有权限操作数据库中的对象（数据库表等）进行设定。
- COMMIT ： 确认对数据库中的数据进行的变更
- ROLLBACK ： 取消对数据库中的数据进行的变更
- GRANT ： 赋予用户操作权限
- REVOKE ： 取消用户的操作权限