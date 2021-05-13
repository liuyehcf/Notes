## 个人信息

<div>
    <img align="right" src="pic.jpg" height="180px">
    </br>
    <div align="left">
        <text>姓名：贺辰枫</text><br/>
        <text>性别：男</text><br/>
        <text>户籍：杭州</text><br/>
        <text>年龄：28</text><br/>
        <text>联系方式：17366617611（工作时间不太方便，请加微信😁）</text><br/>
        <text>邮箱：1559500551@qq.com</text><br/>
    </div>
</div>


## 教育经历

* 2011.9-2015.7，北京邮电大学，本科
* 2015.9-2018.4，北京邮电大学，硕士

## 工作经历

2018.4 - 至今，阿里巴巴技术有限公司，iot事业部，服务端开发

## 项目经历

### 隧道服务

2018.11-至今：隧道服务旨在为部署在各种边缘环境中的设备提供内网穿透的能力，将设备上的各类服务（主要是sshd以及各类本地控制台）通过安全隧道暴露到公网中，结合物联网平台的认证体系，使得用户以及相关技术人员可以对设备进行运维操作。此外，隧道服务还作为基础设施服务于云边协同（从公网调用局域网的http/https接口）

1. 负责隧道整体架构设计、协议定义
1. 负责服务端（java）的实现
1. 负责设备端（java、go）sdk的实现

### 规则中心

2019.5-至今：规则中心旨在为物联网平台提供设备联动、消息转发、告警等编排能力，支撑每天数百亿次的规则执行

1. 负责规则引擎的开发：参考开源工作流框架flowable，以及多种业务形态，基于自研的编译框架，开发出一套高性能、易使用、易集成、易扩展的[「flow框架 ➡ https://github.com/liuyehcf/liuyehcf-framework/tree/master/flow-engine」](https://github.com/liuyehcf/liuyehcf-framework/tree/master/flow-engine)。框架包含3大块：flow描述语言、flow执行引擎、flow执行统计
1. 负责表达式引擎的开发：基于自研的编译框架，开发出一套高性能、易使用、易集成、易扩展的[「表达式执行框架 ➡ https://github.com/liuyehcf/liuyehcf-framework/tree/master/expression-engine」](https://github.com/liuyehcf/liuyehcf-framework/tree/master/expression-engine)。功能包括：字面值、变量、运算符、函数定义、运算符重载

### 边缘一体机

2019.11-至今：基于云原生技术，实现了一体机、边缘应用的全生命周期服务，提供了应用管理、设备接入管理、远程运维、一体机管理等能力

1. 负责设计并搭建安装包构建平台，将一方、二方软件、操作系统并结合硬件配置构建系统安装包（iso或者rootfs），适配不同厂家的不同生产工艺，包括pxe、母盘拷贝、rootfs烧写
1. 负责一体机生命周期管理，包括一体机开箱、注销、运行时运维等
1. 负责开发一体机诊断工具，包括主机网络、容器网络（k8s）、系统参数、软件状态等
1. 为项目交付、运维提供技术支持，解决各类疑难杂症

## 个人技能

1. 熟练掌握java，熟悉jvm，类加载机制，熟悉java并发包源码
1. 熟悉基本数据结构、复杂数据结构（红黑树、B/B+树），熟悉常用算法
1. 熟练使用Spring、Spring Boot、Mybatis、Netty等开源框架，熟练使用rocketmq等消息中间件
1. 熟悉Mysql常用操作
1. 熟练掌握编译原理，自研编译框架，基于该框架产出3个项目（2个在公司内部使用）
1. 熟悉容器、k8s等基本概念、实现原理、网络架构，熟练掌握容器、k8s等基本操作
1. 熟悉linux常用命令及基本操作
1. 业余时间实现过的项目
    1. [个人技术博客 ➡ https://liuyehcf.github.io/](https://liuyehcf.github.io/)
    1. [编译框架 ➡ https://github.com/liuyehcf/liuyehcf-framework/tree/master/compile-engine](https://github.com/liuyehcf/liuyehcf-framework/tree/master/compile-engine)
    1. [paxos协议 ➡ https://github.com/liuyehcf/liuyehcf-framework/tree/master/io-athena](https://github.com/liuyehcf/liuyehcf-framework/tree/master/io-athena)
    1. [rpc框架 ➡ https://github.com/liuyehcf/liuyehcf-framework/tree/master/rpc-maple](https://github.com/liuyehcf/liuyehcf-framework/tree/master/rpc-maple)
    1. [http框架 ➡ https://github.com/liuyehcf/liuyehcf-framework/tree/master/rpc-ares](https://github.com/liuyehcf/liuyehcf-framework/tree/master/rpc-ares)（已在公司内部使用）
    1. [go版本的logback日志框架 ➡ https://github.com/liuyehcf/common-gtools](https://github.com/liuyehcf/common-gtools)（已在公司内部推广使用）