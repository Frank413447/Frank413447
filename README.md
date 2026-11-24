<div align="center">
任家和
Java 后端 / AI 应用开发 · 2027 届本科 · 长沙
Java
Spring Boot
Spring AI
邮箱：3259673420@qq.com · 湖南财政经济学院 · 数据科学与大数据技术
</div>
关于我
2027 届本科，方向是 Java 后端 + AI 应用开发。能把一个想法从零做到「可演示」：环境搭建、建库、接口联调、文档沉淀全程自己完成。做事习惯把模糊需求拆成可验收的清单，按周交付。
目前专注在大模型应用的工程化落地：Function Calling、会话记忆、流式输出、RAG、Agent 工具编排。
技术栈
- 后端：Java 17、Spring Boot 3.5、MyBatis、RESTful API、JWT / Spring Security、MySQL（索引与事务）、Redis（缓存与会话）
- AI 应用：Spring AI 1.1（ChatClient / Function Calling / Advisor）、Agent 工具设计、ChatMemory + Redis、Flux 流式输出；RAG 全链路（文档切分、向量检索、重排）学习中
- 工程化：Git（分支与提交规范）、Docker Compose、Linux 常用命令、Postman、JSON / HTTP 接口联调
- 工具：Cursor / Claude Code 辅助编码（JD 明确要求，面试会问）
- 前端：原生 HTML / CSS / JavaScript 单页应用
项目
DataTalk · 学生管理 AI 助手
用自然语言查学生信息和成绩：老师问「张伟的数学多少分」，AI 自己决定调哪个工具、传什么参数，再把结果说成人话。
Spring Boot 3.5 / Spring AI 1.1 / MySQL / Redis / JWT
- Agent 工具调用：用 Function Calling 实现 5 个数据查询工具，模型自主选择工具与参数，替代固定菜单查询
- 会话记忆：实现 ChatMemoryRepository 对接 Redis，对话上下文持久化、服务重启不丢；滑动窗口保留最近 10 条控制 Token 成本
- 流式输出：基于 Reactor Flux 逐字返回，首字即可见
- 工程细节：工具结果按 50 条截断防上下文溢出；AI 查询与列表缓存分两条路径避免全表扫描
- 仓库 README 含架构图、三个设计取舍、已知问题清单和快速开始
正在学习
- RAG 全链路：文档切分 → Embedding → 向量检索 → Rerank → 带引用溯源
- Agent 工作流编排：Function Calling / MCP / 多步骤任务
- Java 面试基础：集合、并发、JVM、MySQL 索引与事务
联系
邮箱：3259673420@qq.com · 期待在长沙做有真实业务价值的 AI 应用
