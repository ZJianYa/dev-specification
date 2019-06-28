# 概述

## 我个人的疑惑

Rest把所有的数据看做是Resource，Resource之间有关联关系。  
用户会对Resource进行各种操作：CURD，其中U操作和R操作最为复杂。  
很大程度上数据是实体的映射，我们对实体的操作是非常复杂的。  

## 为什么说 GraphQL 可以取代 REST API？

https://www.infoq.cn/article/LVQGuC3vQX-T3PpVCkHt  为什么说 GraphQL 可以取代 REST API？  
http://www.infoq.com/cn/articles/understanding-restful-style  理解本真的 REST 架构风格  
https://www.infoq.cn/article/rest-introduction 深入浅出rest  
https://segmentfault.com/a/1190000014131950  理解GraphQL核心概念  
http://graphql.cn/  一种用于 API 的查询语言  

GraphQL 加速了开发速度，提升了开发者体验，并提供了更好的工具。我并不是说这绝对是这样的，但我会尽力说明 GraphQL 与 REST 之间的争论点及其原因。

## GraphQL 可能不是一个好选择的主要原因

当客户端的需求很简单时：如果你的 API 很简单，例如 /users/resumes/123，那么 GraphQL 就显得有点重了；

为了加快加载速度使用了异步资源加载；

在开发新产品时使用新的 API，而不是基于已有的 API；

不打算向公众公开 API；

不需要更改 UI 和其他客户端；

产品开发不活跃；

使用了其他一些 JSON schema 或序列化格式。

## 资源

https://apis.guru/ api工具，帮助开发人员使用GraphQL和OpenAPI / Swagger
https://www.baeldung.com/spring-graphql Getting Started with GraphQL and Spring Boot
https://www.jianshu.com/p/203dd28eac4f?from=timeline GraphQL初探：一种强大的DSQL