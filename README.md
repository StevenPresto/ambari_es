Elasticsearch 5.x  集群模式

修改如下参数
elastic_download  由于直接访问官网较慢需手动指定Elasticsearch rpm包   如http://master/ambari/elasticsearch-5.2.0.rpm

discovery_zen_minimum_master_nodes:1

discovery_zen_ping_unicast_hosts:master,node1,node2,node3

注意：控制节点hostname必须为 master




参考原地址：https://github.com/Jaraxal/ambari-elasticsearch-service  

有问题请发送邮件到本人邮箱：1427682825@qq.com




