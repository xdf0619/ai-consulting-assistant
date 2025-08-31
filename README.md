# AI-Consulting Assistant (CN-first, Private RAG)

> 用 **RAG + 知识图谱** 把管理咨询方法论落地为中文问答与决策支持。**中文优先｜私有部署｜重视合规与工程化**。

## 我们在做什么（MVP 8–12 周）
- **文档摄取与合规**：脱敏上传、本地向量化（Qdrant/Milvus/Weaviate）、访问日志与审计。
- **中文 RAG 问答与评测**：BM25/向量检索 + rerank + 生成；提供评测脚本（Top-k 命中率/一致性/延迟）。
- **管理端 Portal**：知识库/日志/反馈置错；一键知识更新。

## 技术标准（建议/可替换）
- Backend：Python+FastAPI / Node.js+NestJS
- Retrieval：Qdrant / Milvus / Weaviate + BM25（Elasticsearch/Meilisearch）
- Rerank/Embedding：bge-m3 / e5-mistral（按许可与成本替换）
- LLM：可插插（本地/私有云；Qwen/Llama 等）
- Frontend：Next.js + Tailwind
- 部署：Docker Compose / K8s；可观测：Prometheus + Grafana；评测：Ragas/自定义

## 我们在找谁（混合方式）
- **MLE/检索工程师（1）**：RAG、中文分词、向量库与 rerank；能写评测脚本。
- **全栈工程师（1）**：Next.js/React + FastAPI/NestJS；能落地门户与鉴权。
- **加分项**：Neo4j/Arango（图谱）、CI/CD、权限与审计。

## 你将做什么
- 设计可私有部署的 RAG 架构，明确数据流与日志。
- 实现“检索→回答→反馈→知识更新”的间间间间闭环。
- 输出 README、Dockerfile、评测与运维脚本。

## 合作与激励（混合）
- **现金**：试任务与里程碑指件指到无责台辣南乐。
- **股权/期权**：核心合伴人 **5–10%**（12‒24 个月定义期，3 个月 cliff），可另设顾问期权。
- **合规**：先签 NDA；核心代码间私开源，外围可开源（可协商）；避免 AGPL 涂损。

## 路线图（里程碑）
- **M1**：摄取/检索/问答跑通
- **M2**：评测达标 + Portal 联调
- **M3**：企业内测 + 标杆案例

## 如何参与
1. Fork/提出改进建议或认领 `good first issue`。
2. 先做一个小 PR（文档/脚本/性能优化皆可）。
3. 联系方式：**Email：471697864@qq.com】Phone：15891707881**

## 合规与隐私
- 演示不出网，数据本地持有；访问全量留痕。
- 先签 NDA 再访问真实数据。
- 开源依赖需列明许可指名；避免将 AGPL 代码嵌入间私开源核心模块。

## 许可
- 默认 Apache-2.0（或另行约定）
