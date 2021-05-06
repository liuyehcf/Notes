# 个人信息

# 教育经历

* 2011.9-2015.7，北京邮电大学，本科
* 2015.9-2018.4，北京邮电大学，硕士

# 工作经历

2018.4 - 至今，阿里巴巴技术有限公司，后端研发

# 项目经历

## 隧道服务

2018.11-至今：隧道服务旨在为部署在各种边缘环境中的设备提供内网穿透的能力，将设备上的各类服务（主要是sshd以及各类本地控制台）通过隧道暴露到公网中，便于用户以及相关技术人员对设备进行运维操作。此外，隧道服务还作为基础设施服务于云边协同

1. 负责隧道整体架构设计、协议定义
1. 负责服务端（java）的实现
1. 负责设备端（java、go）sdk的实现

## 规则中心

2019.5-至今：规则中心旨在为物联网平台提供可自由编排的设备联动、消息转发、告警、业务编排等能力，支撑每天数百亿次的规则执行

1. 参考开源工作流框架flowable，以及多种业务形态，开发出一套高性能、易使用、易集成、易扩展的[flow框架](https://github.com/liuyehcf/liuyehcf-framework/tree/master/flow-engine)。框架包含3大块：flow描述语言（基于自研的编译框架）、flow执行引擎、flow执行统计
1. 基于自研的编译框架，开发出一套高性能、易使用、易集成、易扩展的[表达式执行框架](https://github.com/liuyehcf/liuyehcf-framework/tree/master/expression-engine)

## 边缘一体机

2019.11-至今：软硬一体方案

1. 负责安装包构建CI/CD自动化流水线，该流水线会将一方、二方软件、操作系统并结合硬件输出系统安装包（iso或者rootfs），适配不同厂家的不同生产工艺，包括pxe、母盘拷贝、rootfs烧写
1. 负责一体机生命周期管理，包括一体机开箱、注销、运行时运维等
1. 负责维护一体机诊断工具，包括主机网络、容器网络（k8s）、系统参数、软件状态
1. 负责开发部分一方应用，包括边缘本地控制台等等
1. 为项目交付、运维提供技术支持

# 个人技能

1. 熟悉编译原理，自研编译框架，基于该框架产出3个项目（2个商用）
1. 熟悉k8s基本操作、熟悉k8s网络架构
1. 熟悉linux常用命令
1. 业余时间实现过的项目
    1. [paxos协议](https://github.com/liuyehcf/liuyehcf-framework/tree/master/io-athena)
    1. [rpc框架](https://github.com/liuyehcf/liuyehcf-framework/tree/master/rpc-maple)
    1. [http框架](https://github.com/liuyehcf/liuyehcf-framework/tree/master/rpc-ares)（已在公司内部使用）
    1. [go版本的logback日志框架](https://github.com/liuyehcf/common-gtools)（已在公司内部推广使用）