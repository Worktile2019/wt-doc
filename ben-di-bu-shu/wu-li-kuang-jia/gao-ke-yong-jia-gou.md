#### **4.4高可用架构**
* 增加两台HA服务器，同时可以增加LB服务器的数量，组成LB的负载均衡集群，当HA1出现故障时，会自动切换到HA2，同时对外提供服务的VIP也会随之切换到HA2上，从而增加系统的稳定性

# ![](/assets/4.4.jpg)