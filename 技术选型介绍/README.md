### 一些常见的服务注册发现工具
1. **etcd**：这是CoreOS的创建者提出的工具，可面向容器和宿主机提供服务发现和全局配置存储功能。它在每个宿主机上都有基于HTTP协议的API和命令客户端。地址为:https://github.com/etcd-io/etcd

2. **Consul**：该服务发现工具有很多高级的特性，列如配置健康检查、ACL功能、HAProxy配置等，因此能够脱颖而出。

3. **ZooKeeper**：该工具较上面的两个语言而言比较老旧，提供了一个更加成熟的平台，也提供了一些特性。

4. **Confd**：旨在基于服务发现的编号动态更新配置应用程序。该系统中包含了一个能够检测节点变化的工具，以及一个根据获取到的值来生成配置文件的模板系统，能够根据服务配置的动态变化重新加载受影响的应用集群。

5. **Dubbox**： 对于Dubbox或者Spring Cloud这种RPC框架，服务发现是自带机制，不是什么难题。但是对于没有服务治理或者RESTful的PHP服务而言，如何将现有的服务治理框架融合进去，达成跨语言、跨平台服务治理，便是一个很大的问题。

6. **Service Mesh**：根据集群状态动态调整负载均衡策略和应用上线下是Service Mesh的一个技术特点，另外Service Mesh还提供了夸语言、夸通信模式的服务自发现技术
