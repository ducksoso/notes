1. k8s master 可以和node在一台机器上嘛？

   Master 是 K8S 的集群控制节点，每个 K8S 集群里需要有一个 Master 节点来负责整个集群的管理和控制，基本上 K8S 所有的控制命令都是发给它，它来负责具体的执行过程。Master 节点通常会占据一个独立的服务器，因为它太重要了，如果它不可用，那么所有的控制命令都将失效。

   Master 节点上运行着以下关键组件：

   