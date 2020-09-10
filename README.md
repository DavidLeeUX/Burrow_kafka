<!--
 * @Author: Changwei5
 * @version: 
 * @Description: 
 * @Date: 2020-09-10 18:27:10
 * @LastEditTime: 2020-09-10 18:44:08
-->
# Burrow_kafka
## 基于linkedin  Burrow  Releases 1.3.4  修改
## 增加 burrow_kafka_consumer_current_offset和burrow_kafka_consumer_partition_lag 指标增加owner 和partition_Leader 标签

```

burrow_kafka_consumer_partition_lag{cluster="cluster01",consumer_group="group01",owner="1.1.1.1",partition="2",partition_Leader="2.2.2.2:9092",topic="topic01"} 412445
burrow_kafka_consumer_current_offset{cluster="cluster01",consumer_group="group01",owner="1.1.1.1",partition="2",partition_Leader="2.2.2.2:9092",topic="topic01"} 22513
```