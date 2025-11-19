---
title: "Apache GeaFlow (Incubating) V0.7.0 Release Note"
date: November 18, 2025
---
## 🔧 Core Engine & Runtime Enhancements
----
- Fixed multiple critical runtime issues including checkpoint anomalies, task callback errors, and shuffle concurrency problems.
- Optimized BRPC endpoint conflicts in local deployment scenarios.

<!-- truncate -->

## 📦 Storage & Connector Extensions
----
- Added new Paimon graph storage connector with support for dynamic graph APIs and asynchronous write modes.
- Introduced Streaming Hive Source to enhance data ingestion capabilities.
- Improved Paimon RWHandle resource management logic.

## 💡 SQL / GQL / DSL Functionality Enhancements
----
- Added support for several new UDF functions including json_get_object, percentile, and stddev_samp.
- Enhanced GQL query capabilities with new edge direction UDF.
- Optimized Edge query performance and Filter instantiation logic.

## 🏗️ Build & Infrastructure Upgrades
----
- Officially renamed Maven Group ID to org.apache.geaflow to align with Apache standards.
- Added JDK11 CI build support.
- Fixed compilation issues on aarch64 architecture.
- Updated .asf.yaml configuration file to meet ASF requirements.
- Updated LICENSE and NOTICE Files.

## 📚 Documentation & Community Governance
----
- Updated developer contribution guidelines and project governance documentation.
- Improved community contact information, now unified under dev@geaflow.apache.org.

## 👥 Acknowledgements
----
Thank you to all community members who contributed to this release:

mingcheng, justinmclean, and 16 other contributors

@cbqiao, @fanzhidongyzby, @dy247846795, @huhao0926, @Leomrlin, @Loognqiang, @xincai98, @652053395, @justinmclean, @yaozhongq, @DukeWangYu, @mingcheng, @vesense, @xiaoya-yaya, @chzhoo, @qingwen220, @cfsfine, @kitalkuyo-gita

Full ChangeLog: [https://github.com/apache/geaflow/commits/v0.7.0](https://github.com/apache/geaflow/commits/v0.7.0)

