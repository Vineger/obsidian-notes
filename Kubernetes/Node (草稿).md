Kubernetes 中的工作机器称作节点.  节点可以是一个虚拟机或者物理机器，取决于所在的集群配置。节点由 控制面 负责管理

Node 对象的名称必须是合法的 [DNS 子域名](https://kubernetes.io/zh/docs/concepts/overview/working-with-objects/names#dns-subdomain-names)

节点上包括以下三个组件
- kubelet
- container runtime
- kube-proxy

节点的注册分为两种模式: 自注册和手动注册

