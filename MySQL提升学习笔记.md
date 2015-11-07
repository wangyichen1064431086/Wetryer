# MySQL提升学习笔记
其官网教程<http://doc.mysql.cn/mysql5/refman-5.1-zh.html-chapter/>

导入txt文件：
```
mysql> LOAD DATA LOCAL INFILE '/path/pet.txt' INTO TABLE pet;
```

注意导入txt文件以tab分割，且必须要以utf8编码

MYsql的转义字符：
<http://www.cnblogs.com/end/archive/2011/04/01/2002516.html>

取表前30行：
SELECT * FROM `表名` LIMIT 0 , 30;

清除字段空格：
update news set content=replace(`content`,' ','');//清除news表中content字段中的空格  


# Python提升学习笔记
