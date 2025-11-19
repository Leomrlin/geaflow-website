---
title: "Apache GeaFlow（孵化中）V0.7.0 发布说明"
date: 2025-11-18
---
## 🔧 核心引擎与运行时增强
----
- 修复了多个关键的运行时问题，包括检查点异常、任务回调错误和 Shuffle 并发问题。
- 优化了本地部署场景下的 BRPC 端点冲突问题。

<!-- truncate -->

## 📦 存储与连接器扩展
----
- 新增 Paimon 图存储连接器，支持动态图 API 和异步写入模式。
- 引入 Streaming Hive Source，增强了数据摄入能力。
- 改进了 Paimon RWHandle 的资源管理逻辑。

## 💡 SQL / GQL / DSL 功能增强
----
- 增加了对多个新 UDF 函数的支持，包括 json_get_object、percentile 和 stddev_samp。
- 通过新增边方向 UDF 增强了 GQL 查询能力。
- 优化了边查询性能和 Filter 实例化逻辑。

## 🏗️ 构建与基础设施升级
----
- 正式将 Maven Group ID 更改为 org.apache.geaflow，以符合 Apache 标准。
- 添加了 JDK11 的 CI 构建支持。
- 修复了 aarch64 架构上的编译问题。
- 更新了 .asf.yaml 配置文件以满足 ASF 要求。
- 更新了 LICENSE 和 NOTICE 文件。

## 📚 文档与社区治理
----
- 更新了开发者贡献指南和项目治理文档。
- 改进了社区联系方式，现已统一为 dev@geaflow.apache.org。

## 👥 致谢
----
感谢所有为此版本做出贡献的社区成员：

mingcheng, justinmclean，以及另外 16 位贡献者

@cbqiao, @fanzhidongyzby, @dy247846795, @huhao0926, @Leomrlin, @Loognqiang, @xincai98, @652053395, @justinmclean, @yaozhongq, @DukeWangYu, @mingcheng, @vesense, @xiaoya-yaya, @chzhoo, @qingwen220, @cfsfine, @kitalkuyo-gita

完整变更日志：[https://github.com/apache/geaflow/commits/v0.7.0](https://github.com/apache/geaflow/commits/v0.7.0)