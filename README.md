# muke_69
Spring Security+OAuth2 精讲，打造企业级认证与授权
Spring Security+OAuth2 精讲，打造企业级认证与授权
👇👇👇👇👇👇👇👇点击图片跳转下载地址👇👇👇👇👇👇👇
### 第1章 关于这门课，你需要知道的 

#### 本章中，将向大家介绍本门课的相关信息，包括你能学到的知识概览、最终项目效果、课程讲解方式以及相关储备知识介绍、环境安装介绍等等。
1-1 课前须知，这里有你需要了解的一切 (12:26)

1-2 环境配置 (09:55)

1-3 工程结构 (10:21)


### 第2章 初识 Spring Security 

#### 本章中会带领大家，通过一个简单的 API 鉴权，了解鉴权的目的和机制；如何使用 Postman 进行 API 测试；认识常用的 Token 机制 -- JWT；如何使用 Spring Security 进行鉴权以及对于公开接口应该如何保证安全等知识，帮助大家对Spring Security有初步的认识。...
2-1 认证和授权的概念 (12:01)

2-2 过滤器和过滤器链 (12:16)

2-3 HTTP 请求的结构 (14:58)

2-4 HTTP 响应和 HTTP Basic Auth (12:01)

2-5 安全配置 (14:59)

2-6 定制登录页 (16:09)

2-7 csrf, logout 和 rememberMe 的设置 (19:46)

2-8 登录成功及失败的处理 (16:23)

2-9 自定义 Filter (21:44)


### 第3章 密码的进化和验证 

#### 密码作为安全的一大要素，我们将通过本章的学习，了解常见的哈希算法和 Spring 目前默认的 Bcrypt 算法机制。学习 Java Validation API 进行领域对象验证，以及自定义注解验证密码是否符合规则。
3-1 密码进化史 (11:55)

3-2 密码编码器 (14:59)

3-3 验证注解和自定义验证注解 (26:56)

3-4 密码的验证规则和自定义注解和验证器 (17:26)

3-5 验证消息的国际化 (09:43)

3-6 异常的处理 (08:00)

3-7 多个安全配置共存 (06:15)


### 第4章 深入 Spring Security 认证

#### 本章中，我们将通过不断的定制化，逐渐接触到 Spring Security 中的比如安全上下文，UserDetails 和 UserDetailsService 等核心概念。同时本章也会介绍如何基于 Spring Security 进行单元测试。
4-1 核心组件 - SecurityContext SecurityContextHolder Authentication (17:26)

4-2 UserDetails、UserDetailsService和jdbcAuthentication (14:26)

4-3 定制化数据库 (09:43)

4-4 深度定制化上 - 实现 UserDetails 和 GrantedAuthority (22:15)

4-5 深度定制化下 - UserDetailsService 和 UserDetailsPasswordService (22:12)

4-6 环境和环境变量 (20:46)

4-7 自动化测试 (09:09)


### 第5章 构建基于 JWT 的认证

#### 在本章中，我们会通过源码精讲进一步了解认证流程，并基于对流程的理解，自己开发一个独立的 JWT 认证过滤器，完成令牌的生成和刷新。
5-1 认证流程和源码解析 (20:18)

5-2 LDAP 配置和多 AuthenticationProvider 共存 (21:23)

5-3 JWT 的概念和创建以及解析 (20:48)

5-4 访问令牌和刷新令牌以及JWT外部配置 (17:53)

5-5 创建 JwtFilter (16:29)

5-6 实现登录接口和刷新令牌接口(上) (13:53)

5-7 实现登录接口和刷新令牌接口(下) (13:20)

5-8 完成注册接口 (17:18)


### 第6章 基于角色的用户权限

#### 在本章中，会带领大家了解一次性密码，多因子认证的概念，实现基于 Email 和短信方式发送验证码，并结合前端的集成学习如何处理前端跨域问题。
6-1 多因子认证和TOTP (22:50)

6-2 云服务和多因子认证逻辑 (08:17)

6-3 短信发送服务 - 阿里云和LeanCloud (19:52)

6-4 Email 发送服务SMTP 和 API 方式 (12:21)

6-5 多因子认证逻辑 ---整体逻辑和实体类改造 (15:02)

6-6 多因子认证逻辑---使用 Redis 缓存 (16:02)

6-7 多因子认证逻辑---选择发送方式和验证 (18:43)

6-8 前端集成---前后端的多工程配置 (11:52)

6-9 前端集成---跨域处理 (15:17)

6-10 前端集成 ---源码解析和验证多因子登录 (19:48)


### 第7章 基于数据库的 RBAC

#### 在本章中，我们会结合一个基于数据库的角色/权限/用户结构，进一步熟悉授权的概念，并实战打造一个完整的、可复用的后台用户管理功能模块。权限表达式是 Spring Security 中非常强大、易于使用的一种可以应用于 URL 和方法级的安全注解表达式，我们也会逐步介绍什么是内建的表达式、何自定义表达式，以及具体在什么场...
7-1 授权的概念和安全表达式的应用 (22:22)

7-2 方法级注解 (12:37)

7-3 RBAC 和角色分级 (14:42)

7-4 数据库和实体类的 RBAC 改造 (15:21)

7-5 元注解简化权限表达式的使用 (10:07)

7-6 使用 AOP 动态刷新角色层级 (10:30)

7-7 前端的安全 (10:04)

7-8 授权流程源码解析和用户组的思路扩展 (07:10)


### 第8章 实现符合 OAuth 2 标准的授权服务器

#### 本章将改造前面的应用为多服务器模型，并带大家逐步了解 Oauth 2.0 的流程和机制；如何使用 Spring Security 实现授权服务器和资源服务器；如何结合实战实现Github登录、微博登录以及 QQ 登录；了解 Token 如何进行刷新；单页应用如何在 Oauth2 下工作以及 JWS等概念。...
8-1 OAuth2 的主要角色和流程 (13:49)

8-2 JWS和JWK (10:33)

8-3 搭建授权服务器（一）依赖和表结构 (12:29)

8-4 搭建授权服务器（二）JWKS 和RSA密钥对 (16:12)

8-5 搭建授权服务器（三）授权服务器配置 (12:38)

8-6 前端为例详解授权码流程 (15:27)

8-7 资源服务器的配置 (13:56)

8-8 客户端登录-社交登录和二维码登录原理 (18:34)

8-9 资源服务器的访问 (15:19)


### 第9章 关于Spring Security你可以了解的更多

#### 在本章中，会带领大家了解业界成熟的安全服务器 Keycloak，以及如何和 Spring Security 进行集成，在微服务中如何使用 Oauth2等扩展知识。
9-1 Keyloak 简介 (14:59)

9-2 SSO 单点登录 (08:25)

9-3 微服务间的请求调用和拦截器实现token刷新 (19:37)

9-4 总结和回顾 (11:38)


[下载地址](https://51xueit.vip "下载地址")
