## 概要介绍

本项目是区块链中间件平台WeBASE管理平台，使用框架`vue-cli`。

兼容浏览器IE9及以上，360浏览器兼容版（IE9内核），360浏览器极速版，chrome浏览器。

本代码仅支持FISCO-BCOS 2.0以上版本，支持群组和群组切换。具体功能有：

1. 区块链概览，可以查看区块链信息。点击左上角交易信息和区块信息界面，可以跳转到区块或交易信息列表页，交易信息支持input解码和event解码。

2. 前置管理，可以新增前置，新增前置成功后，可以拉取改链的所有群组和节点。点击ip可以查看该前置所在服务器状态相关信息。

3. 合约管理，合约IDE支持本地编写，编译合约;还支持CNS查询和CURD,部署合约后该合约会被保存，在历史合约中，可以查看该合约。

4. 私钥管理，管理所有可以发交易的帐号，公钥用户是其他机构的帐号，无法在本机构发交易，可以通过手动绑定和自动同步获取。私钥用户为本机构发交易的用户。

5. 系统管理，包括权限管理、配置管理、证书管理、告警邮箱配置和告警配置。

6. 系统监控，监控前置所在的主机和节点的一些指标，包括CPU、内存，块高，pbftview等等。

7. 交易审计，主要监控整条链所有机构所有用户发送交易行为，查看是否有异常用户和异常合约。

8. 帐号管理，只有admin帐号才能查看此功能，可以新增帐号（登录此系统帐号），修改密码等等。

