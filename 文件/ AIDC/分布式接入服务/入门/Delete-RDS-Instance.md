入门指南概述
本指南指引您快速创建一个高可用的公网分布式网络负载均衡，该负载均衡挂接高可用组，可将公网客户端服务请求分发到高可用组中的后端服务器，实现服务的高可用。

本指南包括如下步骤：

创建公网负载均衡实例

创建一个公网类型的分布式网络负载均衡实例。分布式网络负载均衡实例是承载负载均衡业务的逻辑实体，不对应具体资源。

创建高可用组

创建一个高可用组。高可用组是京东云提供的业务高可用部署解决方案，是计算资源逻辑集合，可作为后端服务器组绑定分布式网络负载均衡提供服务。

创建监听器及后端服务

配置分布式网络负载均衡实例，创建监听器及后端服务。监听器负责监听客户端服务请求，后端服务负责将监听的服务请求按照一定的策略转发到后端服务器。

删除公网负载均衡实例

当您根据业务场景需求不需要分布式网络负载均衡提供服务时，可以将其删除。
