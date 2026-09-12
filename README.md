<div align="center">

# 你好，我是 zpwu 👋

### Agent 开发学习者 · 江西财经大学大四学生

专注于 **AI Agent、RAG 与智能应用开发**，正在通过真实项目探索大模型能力与业务系统的结合。

[![GitHub](https://img.shields.io/badge/GitHub-KKK666A-181717?style=flat-square&logo=github)](https://github.com/KKK666A)
[![Email](https://img.shields.io/badge/Email-3066645313%40qq.com-0078D4?style=flat-square&logo=maildotru&logoColor=white)](mailto:3066645313@qq.com)

</div>

---

## 关于我

- 🎓 江西财经大学大四学生
- 🤖 正在学习 Agent 开发，关注 LangGraph、MCP 与多 Agent 协作
- 🔎 持续探索 RAG、混合检索和向量数据库的工程实践
- 🧩 喜欢把 AI 能力接入真实业务，通过项目理解完整技术链路
- 📫 联系我：[3066645313@qq.com](mailto:3066645313@qq.com)

## 技术栈

**Agent 与 AI**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-20232A?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-5A67D8?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-7C3AED?style=flat-square)
![DeepSeek](https://img.shields.io/badge/DeepSeek-4D6BFE?style=flat-square)

**后端与数据**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=flat-square&logo=milvus&logoColor=white)

**前端与工具**

![Vue.js](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Element Plus](https://img.shields.io/badge/Element_Plus-409EFF?style=flat-square&logo=element&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## 精选项目

### 🛒 [LangGraph 多 Agent 智能电商推荐中台](https://github.com/KKK666A/langgraph-ecommerce-recommendation)

基于 **FastAPI、LangGraph、MCP、Redis 与 Milvus** 构建的端到端智能推荐系统。

- 使用 LangGraph 状态机编排用户画像、商品召回、库存校验和营销文案 Agent
- 通过 MCP 解耦商品目录与库存工具，形成可替换的能力边界
- 使用 Redis Checkpointer 保存会话状态，并降低会话内商品重复曝光
- 结合 Milvus 商品知识库，串联“画像—召回—库存约束—内容生成”决策链路

`LangGraph` `Multi-Agent` `MCP` `FastAPI` `Redis` `Milvus`

---

### 🧠 [Enterprise RAG](https://github.com/KKK666A/enterprise-rag)

一个面向企业知识检索场景的混合检索原型，聚焦可追溯、可解释的 Retrieval 能力。

- 结合 BM25 词法检索与 Dense Vector 语义检索，实现双路召回
- 使用 RRF 融合异构排名，避免直接混合不同尺度的原始分数
- 打通文档解析、重叠切分、Embedding、Milvus 入库和索引刷新链路
- 保留来源、双路排名与融合分数，使检索结果可追溯、便于分析

`RAG` `Hybrid Retrieval` `BM25` `RRF` `Milvus` `FastAPI` `Vue 3`

---

### 📚 [SmartBook 智阅书城](https://github.com/KKK666A/smartbook-agent-mall)

集成 LangChain Agent 的前后端分离智能书城，让大模型基于真实业务数据完成推荐与问答。

- 采用 Vue 3、Spring Boot 与 FastAPI 构建前后端及 Agent 服务
- 通过 Tool Calling 查询真实图书、库存、购物车和订单数据
- 使用 Spring Security、JWT 与跨服务身份透传保障业务数据权限
- 使用 LangGraph Checkpointer 实现多轮对话记忆与会话隔离

`Spring Boot` `Vue 3` `LangChain` `LangGraph` `FastAPI` `MySQL` `Redis`

## 当前学习

```text
Agent 编排        LangGraph 状态管理、多 Agent 协作与可靠性
工具生态          MCP、Tool Calling 与业务能力解耦
知识检索          RAG、混合检索、Reranker 与效果评测
工程化            会话记忆、权限隔离、可观测性与服务化部署
```

---

<div align="center">

保持好奇，持续构建。欢迎交流 Agent 与 RAG 相关技术。

</div>
