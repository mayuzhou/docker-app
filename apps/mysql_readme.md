### master

```
show master status;
```

### slave

```
change master to master_host='10.180.7.140',master_port=3307,master_user='root',master_password='886887',master_log_file='mysql-bin.000003',master_log_pos=361;

start slave;

show slave STATUS;
```