# HTTP/2 协议详解

> 作者保留所有权利。All rights reserved.

- [关于作者](https://jiajunhuang.com/aboutme)

## 目录

* [回顾 `HTTP/1.x` 的请求流程](#回顾-http1x-的请求流程)
* [`HTTP/2` 简介](#http2-简介)
* [二进制分帧](#二进制分帧)
* [流](#流)
* [头部压缩](#头部压缩)
* [约定的错误](#约定的错误)
* [`SETTINGS` 中可以设置的内容](#settings-中可以设置的内容)
* [如何与 `HTTP/1.x` 兼容](#如何与-http1x-兼容)
* [参考](#参考)

### 回顾 `HTTP/1.x` 的请求流程

### `HTTP/2` 简介

- 扩展：字节序
- 所有数值都是网络序

### 二进制分帧

- 为何分帧
- 帧的类型及其格式
- Go代码解析示例

### 流

- 为什么要有流
- 流的ID
- 状态机以及状态转换
- 流的优先级
- flow control
- 错误处理

### 头部压缩

- 扩展：哈夫曼编码

### 约定的错误

### `SETTINGS` 中可以设置的内容

### 如何与 `HTTP/1.x` 兼容

## 参考

- https://tools.ietf.org/html/rfc7540
- https://tools.ietf.org/html/rfc7541
- https://developers.google.com/web/fundamentals/performance/http2/
