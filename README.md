# 测试命令
```
# 阻止IP访问
iptables -I INPUT -s 172.24.0.2 -j DROP
#查看
iptables -L INPUT
#一键清空所有规则
iptables -F

# SQL
insert into test(a) values (2);
select * from test;
```

# Using Status Variables¶
https://galeracluster.com/library/documentation/monitoring-cluster.html


# Issue
容器中执行iptables：Permission denied
```
docker exec --it  --privileged  {istio-proxy-dockerid} /bin/bash
```