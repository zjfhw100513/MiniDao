MiniDao
=======

MiniDao简介及特征


MiniDao是Jeecg自己的持久化解决方案，集成了
Hibernate实体维护和Mybaits SQL分离的两大优点。
具有以下特征:

1.O/R mapping不用设置xml，零配置便于维护 
2.不需要了解JDBC的知识 
3.SQL语句和java代码的分离
4.可以自动生成SQL语句
5.接口和实现分离，不用写持久层代码，用户只需写接口，以及某些接口方法对应的sql。它会通过AOP自动生成实现类
6.支持自动事务处理和手动事务处理
7.支持与hibernate轻量级无缝集成
8.MiniDao整合了Hibernate+mybatis的两大优势，支持实体维护和SQL分离
9.SQL支持脚本语言

※向下兼容Hibernate实体维护方式,实体的增删改查SQL自动生成 



作者: 张代浩
技术网站：www.jeecg.org
2013/08/16
