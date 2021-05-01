# Microservices Guide

本文其实一篇导读文，汇聚了大神**Martin Fowler**的博客上有关于微服务材料。

## 微服务定义

开篇先提到他与[James Lewis](https://twitter.com/boicy)（另一名大神）合写一篇有关于微服务风格定义的文章，在文中介绍了通用的微服务架构特征。

原文：[Microservices: a definition of this new architectural term](https://martinfowler.com/articles/microservices.html#HowBigIsAMicroservice)

## 构建微服务的时机

紧接着介绍了什么时候我们应该使用微服务，分别从微服务能提供的好处以及会带来的成本，这两方面进行讨论。

好处：

- 强模块边界
- 独立部署
- 技术多样性

成本：

- 分布式
- 最终一致性
- 操作复杂度

原文：[Microservice Trade-Offs](https://martinfowler.com/articles/microservice-trade-offs.html)

罗列了一系列的文章：

- 微服务的溢价：[Microservice Premium](https://martinfowler.com/bliki/MicroservicePremium.html)
- 单体优先：[Monolith First](https://martinfowler.com/bliki/MonolithFirst.html)

- 不要从庞大的单体系统开始：[Don’t start with a monolith](https://martinfowler.com/articles/dont-start-monolith.html)
- 微服务的先决条件：[Microservice Prerequisites](https://martinfowler.com/bliki/MicroservicePrerequisites.html)
- 微服务和分布式对象的第一定律：[Microservices and the First Law of Distributed Objects](https://martinfowler.com/articles/distributed-objects-microservices.html)
- 与Sam Newman关于微服务的访谈：[Interview with Sam Newman about Microservices](https://gotopia.tech/bookclub/episodes/moving-to-microservices-with-sam-newman-and-martin-fowler)

## 构建微服务

在这一章节，推荐了一本书 [《Building Microservices》](https://www.amazon.com/gp/product/1491950358/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=1491950358&linkCode=as2&tag=martinfowlerc-20)

罗列了一系列有关于微服务构建的文章：

- 微服务架构中的测试策略：[Testing Strategies in a Microservice Architecture](https://martinfowler.com/articles/microservice-testing)
- 如何将庞大的单体系统分解为微服务？：[How to break a Monolith into Microservices](https://martinfowler.com/articles/break-monolith-into-microservices.html)
- 微前端：[Micro Frontends](https://martinfowler.com/articles/micro-frontends.html)
- 如何从庞大的单体系统中拆分出丰富的数据服务？：[How to extract a data-rich service from a monolith](https://martinfowler.com/articles/extract-data-rich-service.html)
- 基础架构即代码：[Infrastructure As Code](https://martinfowler.com/bliki/InfrastructureAsCode.html)
- DevOps 文化：[Dev Ops Culture](https://martinfowler.com/bliki/DevOpsCulture.html)
- 熔断器：[Circuit Breaker](https://martinfowler.com/bliki/CircuitBreaker.html)