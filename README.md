# 吴子杰 / JacksonWu

> AI Application Engineer · Backend Systems Builder · Open Source Contributor

```text
$ whoami
吴子杰，Java / Python 双栈后端开发者

$ cat /etc/focus
Agent systems · RAG · Tool Calling · IoT · Real-time interaction

$ cat /etc/stack
Python + Java · FastAPI + Spring Boot · Redis + RabbitMQ · Docker + Kubernetes
```

深圳 | 1317221520 | 1228516103@qq.com  
GitHub: [wzj1228516103](https://github.com/wzj1228516103) · Gitee: `shturl.cc/0iZWub1CFzQwA`

## Profile

面向 AI 应用工程师 / AI 后端工程师岗位，负责把模型能力接入真实业务系统：从 Agent 编排、知识检索和工具调用，到 FastAPI / Spring Boot 服务、消息异步、缓存、实时通信和 Docker 部署。熟悉智能硬件、跨境电商和物联网场景，关注系统边界、失败处理、可观测性与可复现交付。

## Core Stack

| Layer | Tools |
| --- | --- |
| AI application | LangChain, LangGraph, RAG, Tool Calling, Chroma, Embedding |
| Backend | Python, FastAPI, Java, Spring Boot, MyBatis-Plus |
| Reliability | Redis, RabbitMQ, WebSocket, MQTT, idempotency, retry |
| Data & platform | MySQL, ShardingSphere, Nacos, Sentinel |
| Delivery | Docker, Kubernetes, Nginx, AWS |

## Current Lab

### AI Agent 语音交互桌面宠物｜深圳光胜人工智能科技

**Java 开发工程师｜2025.09 - 至今**  
`Python` `FastAPI` `LangChain` `LangGraph` `RAG` `Chroma` `Redis` `RabbitMQ` `WebSocket` `Docker`

- 负责基于 LangGraph 的 Agent 工作流，串联语音预处理、意图识别、RAG 检索、工具调用和回复生成，并持久化多轮对话状态。
- 搭建设备说明、FAQ 和产品知识库的 RAG 链路，完成文档入库、Embedding 检索和上下文拼接；重点处理文档切分、召回质量与上下文组织。
- 基于 LangChain 接入多种大模型，参与按场景路由模型调用的策略设计；不把成本收益等团队指标冒领为个人结果。
- 负责 WebSocket + Opus 的流式语音交互，以及 RabbitMQ 异步推理请求处理；封装 IoT Tool Calling，覆盖设备状态查询、参数调节和模式切换。
- 使用请求 ID + Redis 实现幂等去重，降低网络重试造成的重复执行风险；通过 Docker 完成服务打包与部署。

### Cross-border Commerce Copilot｜深圳光胜人工智能科技

**AI 应用后端模块｜2025.09 - 至今**  
`Python` `FastAPI` `LangChain` `RAG` `Chroma` `DeepSeek` `Spring Boot` `RabbitMQ` `Redis`

- 负责智能客服 Agent 的意图路由、RAG 知识库、订单查询工具和回复生成链路，覆盖商品、物流、订单和售后问题。
- 参与 Python AI 服务与 Java 业务后端的接口协作，通过 RabbitMQ 解耦对话、订单和数据同步链路。
- 参与多语言、GEO 区域化客服和复杂问题转人工机制，支持未解决咨询生成工单并流转人工客服。
- 使用 Redis 缓存热点咨询、常用话术和商品信息，减少重复模型调用；参与登录认证、多租户权限和第三方登录相关后端能力建设。

### Global Pet Community Platform｜深圳光胜人工智能科技

**Java 后端模块｜2025.09 - 至今**  
`Spring Boot` `MyBatis-Plus` `MySQL` `Redis` `Nacos` `AWS` `Docker`

- 负责用户、设备、宠物和社区相关后端接口，参与内容发布、评论、点赞、关注、审核和举报能力建设。
- 参与以 `user_id` 为分片键的水平拆分方案，围绕高增长用户数据控制单表规模，改善高并发查询和写入压力。
- 接入 AWS 与移动云 EOS，完成用户生成内容和宠物资源的存储与分发，支持海外用户访问。
- 参与单体到微服务的业务域拆分、ShardingSphere 分库分表、RabbitMQ 异步解耦、Docker/Kubernetes 部署及调用追踪建设。

## Previous Systems

### IoT Digital Twin Dashboard｜中国铁塔股份有限公司

**Java 开发工程师｜2025.05 - 2025.09**  
`Spring Boot 3` `OAuth 2.0` `JWT` `MyBatis-Plus` `MySQL` `Redis` `RapidOCR` `Zxing` `EasyExcel`

- 负责物联网设备管理后台的认证授权、数据接口和生产追溯链路，基于 OAuth 2.0 + JWT 支持多角色访问控制。
- 接入高德地图 API 完成车辆/设备定位与轨迹展示；接入 RapidOCR、Zxing 和 EasyExcel，打通证件识别、扫码、BOM 导入导出等能力。
- 参与高频表索引优化、关键写操作异步化和缓存预热，降低主线程阻塞与数据库压力。

### B2B Multi-tenant Platform

`Spring Cloud Alibaba` `Nacos` `Sentinel` `Sa-Token` `MySQL` `Redis` `Docker` `Kubernetes`

- 按用户、设备、数据等业务域拆分微服务，使用 Nacos 完成服务注册发现和配置管理，使用 Sentinel 实现限流、熔断与降级。
- 设计多租户数据隔离和 RBAC 权限体系；使用 EasyExcel 支持业务数据批量导入导出，并参与缓存预热和异步写入。

## Personal Projects

### Distributed RAG Knowledge Base

**项目负责人 & 全栈开发｜2025.06 - 2025.09**  
`Python` `LangChain` `LangGraph` `Chroma` `FastAPI` `Spring Boot 3` `MySQL` `Redis` `Docker`

- 独立负责架构设计、技术选型与 AI 推理服务/管理后台开发，形成 Python AI 服务 + Java 业务后台的双栈架构。
- 构建 PDF、Word、Markdown、PPT 等文档处理流水线，完成解析、清洗、语义切片、向量化和检索。
- 使用 LangGraph 编排意图识别、路由分发、RAG 检索、答案生成、引用溯源和多轮上下文记忆。
- 使用 Redis 构建会话与热点知识缓存，使用 Docker 完成可移植部署；项目已开源至 Gitee。

### IoT Device Control Agent

**项目负责人 & 后端开发｜2025.03 - 2025.06**  
`Python` `LangChain` `LangGraph` `MQTT` `FastAPI` `Spring Boot` `Redis` `WebSocket` `Docker`

- 设计指令解析、意图匹配、设备校验、动作执行和结果反馈的 Agent 工作流，支持多设备联动。
- 封装标准设备控制工具，通过 Tool Calling 对接 MQTT 网关，覆盖开关、参数调节和模式切换。
- 使用 WebSocket 实现实时状态推送与语音流交互，结合请求 ID + Redis 幂等去重和 MQTT QoS，保障指令可靠执行。

## Open Source Signal

### CrewAI · [PR #7341](https://github.com/crewAIInc/crewAI/pull/7341)

围绕 [Issue #7338](https://github.com/crewAIInc/crewAI/issues/7338) 处理 memoization 实例生命周期问题：

- 引入实例级缓存与弱引用边界，避免缓存值通过 callback 反向保留已丢弃的 Crew 实例。
- 补充绑定方法 callback 和垃圾回收回归测试，验证工厂对象与生成 Agent 可回收。
- 通过目标测试、相关 memoization 测试、Ruff、格式检查和 `git diff --check`。

**状态：Open / under review。** 未合并，不表述为上游已采用。

### Other Contributions

- 已合并：[distributed-traffic-control #13](https://github.com/yashdotdev13/distributed-traffic-control/pull/13)，补充 Redis 和网关 Docker healthcheck。
- 协作中：[AgentStack #365](https://github.com/agentstack-ai/AgentStack/pull/365)、[respx #329](https://github.com/lundberg/respx/pull/329)、[LiteLLM #40233](https://github.com/BerriAI/litellm/pull/40233)、[LiteLLM #40230](https://github.com/BerriAI/litellm/pull/40230)。

## Education

**五邑大学｜本科｜通信工程｜2022.09 - 2026.06**  
校级奖学金（专业前 5%） · 专利申请一项 · 中共党员 · CET-4

## Signal / Boundary

- 已确认的核心能力：Agent 编排、RAG 工程链路、Tool Calling、Python/Java 双栈接口、IoT 可靠性和后端架构。
- 公开可核验的开源证据：PR 链接、提交记录、测试和 review 状态；未合并 PR 统一写作“协作中”。
- RAG 准确率、推理成本、访问量、销售额、转化率、用户规模等指标，待补充评测集、基线、统计周期、数据来源和个人边界后再加入正式投递版。
