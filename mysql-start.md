

```sql
wangqiaweideMBP:~ wangqianwei$ mysql.server start
Starting MySQL
 SUCCESS!
```
```sql
mysql -u root -p000000;
```

```sql
mysql> show databases;
+--------------------+
| Database           |
+--------------------+
| demo               |
| information_schema |
| mysql              |
| performance_schema |
| sys                |
+--------------------+
5 rows in set (0.01 sec)
```
```sql
mysql> use demo;
Database changed
```
```sql
mysql> show tables;
+----------------------+
| Tables_in_demo       |
+----------------------+
| jdcloud_cdn_consume  |
| jdcloud_free_consume |
| jdcloud_idc_consume  |
| jdcloud_lose_user    |
| jdcloud_refund_info  |
| jdcloud_user_info    |
| tbl_demo_index       |
+----------------------+
7 rows in set (0.00 sec)
```