# Microservice Architecture

## 微服务架构特征

### 服务组件化

组件定义：组件可以独立升级和替换。

组件化的主要手段：将软件分解为服务。

组件化带来的问题：

- 进程内通讯变为进程间通讯，远程调用比进程内调用成本要更高，且远程调用的API，更粗犷。
- 接口变动会带来跨服务的影响。

### 围绕业务能力进行组织

大型应用程序，团队组织划分，比如分为服务端逻辑团队、UI团队、数据库团队。那么即是简单的改动，都有可能需要跨团队进行协作，带来许多不必要的开销。

![](.\images\conways-law.png)

微服务则是围绕着业务能力来组织服务。以业务去划分团队，每个团队的都是跨职能的。

![](.\images\PreferFunctionalStaffOrganization.png)

### 产品而非项目

若开发工作使用的是项目模型，那么目的是交付某些软件，交付完后，便会解散该软件的项目团队。

微服务提倡使用产品模型，团队应该在产品的整个生命周期内拥有产品的想法，开发团队对生产中的软件负全部责任。

### Smart endpoints and dumb pipes

微服务社区提倡使用简单的RESTish协议进行接口编排，而不是使用WS-Choreography或BPEL等复杂协议或由中心工具编排的。

### 分散治理

### 分散数据管理

![](.\images\decentralised-data.png)

微服务体系结构[强调服务之间的无事务协调](http://www.eaipatterns.com/ramblings/18_starbucks.html)，并明确认识到一致性可能只是最终的一致性，而问题只能通过补偿操作来解决。

### 基础设施自动化

![](.\images\basic-pipeline.png)

![](.\images\micro-deployment.png)

### 容错设计



### 进化型设计（Evolutionary Design）

## 微服务是未来吗？