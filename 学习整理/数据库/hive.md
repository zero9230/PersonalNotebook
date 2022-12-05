

1. 登录
```sql
hive;
```

2. 退出
```sql
quit;
```


```sql
exit;
--exit会影响之前的使用，所以需要下一句kill掉hadoop的进程
hadoop job -kill jobid
```


3. 选择使用哪个数据库
```
hive> use database_name;    --使用哪个数据库
```
4. 查看数据表结构
```

hive> describe tab_name; or desc tab_name;   --查看表的结构及表的路径
```

5. 查看数据库的描述及路径
```

hive> describe database database_name; 
or
hive> desc database database_name;
 --查看数据库的描述及路径
```



1、hive模糊搜索表
```
show tables like '*NAME*';
```
2、查看表结构信息
```
desc formatted TABLE_NAME;
desc TABLE_NAME
desc extended TABLE_NAME
```

3、查看分区信息
```
show partitions TABLE_NAME;
```
4、根据分区查询数据
```
select table_coulm from tablename where partitionname = '2016-02-25';
```

