---
layout: default
title: SQL重学-排序（order by） 和 limit（关键字）
parent: 重学SQL
grand_parent: SQL
---
# SQL重学-排序（order by） 和 limit（关键字）
ORDER BY 关键字用于对结果集进行排序。
## 一、SQL ORDER BY 关键字
ORDER BY 关键字用于对结果集按照一个列或者多个列进行排序。
ORDER BY 关键字默认按照升序对记录进行排序。如果需要按照降序对记录进行排序，您可以使用 DESC 关键字。
## 二、ORDER BY语法
```sql
SELECT column_name,column_name
FROM table_name
ORDER BY column_name,column_name ASC|DESC;
```
说明：ASC升序（默认），DESC降序

## 二、ORDER BY举例
有一个员工employees表简况如下:
![file](https://blog.edkso.cn/wp-content/uploads/2021/02/image-1613891512164.png)

查找employees里最晚入职员工的所有信息
```sql
select * from employees order by hire_date desc limit 1;
```

# SQL重学-排序（order by） 和 limit（关键字）
ORDER BY 关键字用于对结果集进行排序。
## 一、SQL ORDER BY 关键字
ORDER BY 关键字用于对结果集按照一个列或者多个列进行排序。
ORDER BY 关键字默认按照升序对记录进行排序。如果需要按照降序对记录进行排序，您可以使用 DESC 关键字。
## 二、ORDER BY语法
```sql
SELECT column_name,column_name
FROM table_name
ORDER BY column_name,column_name ASC|DESC;
```
说明：ASC升序（默认），DESC降序

## 二、ORDER BY举例
有一个员工employees表简况如下:
![file](https://blog.edkso.cn/wp-content/uploads/2021/02/image-1613891512164.png)

查找employees里最晚入职员工的所有信息
```sql
select * from employees order by hire_date desc limit 1;
```

输出如下:
![file](https://blog.edkso.cn/wp-content/uploads/2021/02/image-1613891537556.png)


