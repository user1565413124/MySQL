- 创建学生表,对学生表进行增删改查操作:    student(id,name,age,gender)
要求:
	1.创建新工程,写工具类DBUtils,配置文件 *.properties.
    2.创建一个StudentDemo类,在该类中,创建四个方法通过单元测试Junit执行这四个方法,方法分别为insert,findAll,update,delete;
    3.实现完以上功能后,想办法加入面向对象思想.


## 数据库中有什么表就需要在Java代码中创建什么对象,表中有什么字段,对象中就有什么属性.
## 数据库中有什么表就需要在java代码中创建什么DAO
(Data Access Object 数据访问对象)

## 课后练习:
数据库中添加一个员工表(emp)通过代码实现增删改查操作.

## 批量操作
- 为什么使用批量操作?: 因为每次执行sql都需要和数据库服务器进行数据交互,多次执行sql添加到一个批量处理里面,可以把多次交互变成一次交互,从而提高执行效率.

## 分页查询
- 练习: 控制台输入插叙你的页数和每页的条数,然后返回相应的数据
- 参见代码 PageTest.Java

## 事务
- 创建percon表,id,name,money
- 插入 1,超人,500,2,蝙蝠侠,5000
实现 超人跟蝙蝠侠借2000块钱
实现的效果:
如果蝙蝠侠的钱足够就借,不够就输出蝙蝠侠没钱了;

## 获取自增主键的值


## 获取元数据
- 数据库元数据:包括数据库版本,用户名,密码,连接地址,数据库厂商名称等...和数据库相关的信息
- 表元数据:包括表有多少个字段,每个字段的类型等等.....