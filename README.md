# ImitateDevelopHeadLine
> 这是一个仿开发者头条主界面的app

## 一、登录界面实现

注册和登录是实现人物权限管控和信息隔离必要实现。
#### 基本功能
1. 面向对象化编程
设计一个UserBean面向用户，将bean数据对应数据库持久化，在云端app,则对应云端数据库的持久化读写。
2. 注册验证功能
在注册之前，由于用户数据的独立性，相应的UserBean必须是不可重复的，因此需要对数据进行查询，不允许用户主键重复，随后将注册信息读写如数据库即可。其次是注册信息的核算，应当使用正则表达式对用户登录信息进行限制，如限制用户密码需要8位数字和大小写字母组合
3. 登录功能
登录功能十分简单，只需要传入相应的用户信息，对数据库信息进行验证，信息核算属实即可放行权限。
#### 安全实现
在本项目中，数据库只涉及到本地sqllite数据库，并且是不安全的读写。在实际应用中，面向的是云端的数据库。面向数据库的读写，必须要对传输的数据进行二次封装。预防出现，比如将sql语句作为用户名进行注册，导致数据库出错或者删除，造成的影响不可估量。


## 二、



## 三、


## 四、
