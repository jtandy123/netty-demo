# Netty

> Netty is an asynchronous event-driven network application framework for rapid development of maintainable high performance protocol servers & clients.
- 异步
- 事件驱动
- 网络应用框架   

---

- Core (Zero-Copy-Capable Rich Byte Buffer、Universal Communication API、Extensible Event Model)
- Transport Services (Socket & Datagram、HTTP Tunnel、In-VM Pipe)
- Protocol Support (HTTP & WebSocket、SSL • StartTLS、Google Protobuf、zlib/gzip Compression、Large File Transfer、RTSP、Legacy Text • Binary Protocols with Unit Testability)   

SEDA: Staged Event Driven Architecture  

RPC框架的基本形式：
- 首先需要编写一个说明文件或者数据结构文件（遵循所使用的RPC框架的语法）
- RPC框架的代码生成器会读取数据结构文件生成相应的客户端调用的基础代码(stub)以及服务端调用的基础代码(skeleton)
- 使用者只需要在业务代码中调用生成的基础代码（序列化 - 网络 - 反序列化）

Google Protobuf: Protocol Buffers  
Apache Thrift

RPC框架支持的数据类型是其所支持的所有语言的数据类型的交集  
RMI只能用于Java

WebSocket协议依附于HTTP协议  
第一次HTTP请求的连接升级为WebSocket，建立连接后，双方可以进行全双工通信
Heartbeat：定期发送心跳包

---

应用场景：
- RPC通信框架，基于socket方式
- 长连接服务器
- HTTP服务器

---


