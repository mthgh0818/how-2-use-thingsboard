### Thingsboard全家桶
包含 基础入门、源码分析、二次开发和扩展阅读
- 基础入门（基于3.2）
- 源码分析（基于3.2）
- 二次开发（基于3.3）
- 答疑解惑（不限）

### 准备
- Jdk，11+（因3.2.2版本需要11），用于编译运行
- Maven，3.2.1+，不强制需要，某些IDE也自带
- IDE，推荐Idea，查看代码和运行
- Html5浏览器，推荐使用Chorme，用于页面操作
- 容器引擎，推荐使用Docker，用于初始化环境，比如PG数据库
- Mqtt客户端，推荐使用MqttBox，用于模拟时序数据

### 基础入门
#### 编译
- 编译 [入口](doc/编译/编译.md) 适用于版本3.2及以上

#### 运行
- 运行 [入口](doc/运行/运行.md) 适用于版本3.2及以上

#### 调试
- 后端 [入口](doc/调试/后端.md)
- 前端 [入口](doc/调试/前端.md)

#### 使用
-  权限体系 [入口](doc/使用/权限体系.md)
-  设备
	-  普通设备  [入口](doc/使用/普通设备.md)
	-  智能网关  [入口](doc/使用/智能网关.md)
-  资产 [入口](doc/使用/资产.md)
-  规则引擎 [入口](doc/使用/规则引擎.md)
-  部件 [入口](doc/使用/部件.md)
-  仪表盘 [入口](doc/使用/仪表盘.md)
-  示例 [入口](doc/使用/示例.md)

#### 部署
- 单片 [入口](doc/部署/单片.md)
- 微服务 [入口](doc/部署/微服务.md)

#### 最佳实践
- 高可用集群 [入口](doc/最佳实践/高可用集群.md)

### 源码分析
- 工程结构
  - 整体 [入口](doc/工程/整体.md)
  - application  [入口](doc/工程/application.md)
  - common  [入口](doc/工程/common.md)
  - dao  [入口](doc/工程/dao.md)
  - docker  [入口](doc/工程/docker.md)
  - ~~k8s分析~~（官方已不再推荐使用此包，抽取到新的github工程 [thingsboard-ce-k8s](https://github.com/thingsboard/thingsboard-ce-k8s)）
  - msa  [入口](doc/工程/msa.md)
  - netty-mqtt  [入口](doc/工程/netty-mqtt.md)
  - packaging  [入口](doc/工程/packaging.md)
  - rest-client  [入口](doc/工程/rest-client.md)
  - rule-engine  [入口](doc/工程/rule-engine.md)
  - tools  [入口](doc/工程/tools.md)
  - transport  [入口](doc/工程/transport.md)
  - ui-ngx  [入口](doc/工程/ui-ngx.md)
- MVC分层 [入口](doc/分析/MVC分层.md)
- 系统权限 [入口](doc/分析/系统权限.md)
- 设备连接 [入口](doc/分析/设备连接.md)
- 数据传输 [入口](doc/分析/数据传输.md)
- 数据处理
  - 规则引擎 [入口](doc/分析/规则引擎.md)
- 设备控制 [入口](doc/分析/设备控制.md)

### 二次开发
- 仪表盘组件扩展
- 规则节点扩展
- 白标 
- 定时任务
- 组织机构树
- Influxdb支持

### 答疑解惑 
- 清单 [入口](doc/答疑解惑/README.md)


### TIPS

- 录屏：https://space.bilibili.com/696589672/channel/index
- 镜像：https://gitee.com/blackstar-baba/how-2-use-thingsboard







