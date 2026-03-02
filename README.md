# Hi, I'm emu (张栓槐) 👋

### 🚀 专注于 Agent 智能体架构与 GraphRAG 落地实践
我目前就读于**湖南大学信息管理与信息系统**专业（GPA 3.77/4.0 | 排名 4/55），并已推免至华南理工大学软件工程专业。

---

## 🛠 技术栈 | Tech Stack
- **语言/框架**: Python (FastAPI), Java (Spring Boot), Vue3
- **大模型工程**: GraphRAG , Stateful Agent (MemGPT 架构), Function Calling, Reranker
- **数据存储**: Neo4j, Milvus , MySQL, PostgreSQL
- **工程工具**: Docker,Git, Linux

---

## 🏗 核心项目 | Featured Projects

### 🩺 [dm-agentic-graphrag | 糖尿病个性化医疗智能体](https://github.com/ermu03/dm-agentic-graphrag)
**毕业设计 | 独立完成**
- **长效记忆机制**: 引入 **OS 内存管理理念** 设计分层记忆架构，划分 System/Working/FIFO 区域，并将 Archival/Recall Memory 持久化至 **PostgreSQL**，实现跨会话状态保持与上下文自主换入换出。
- **混合检索增强**: 融合 **Milvus** 向量检索与 **Neo4j** 图检索结果，按查询类型动态切换检索路径，结合 **Reranker** 提升复杂医疗问题下的召回精度与事实一致性。
- **全局图谱构建**: 独立落地离线数据管道，打通 Markdown 切片与实体关系抽取，结合 **Neo4j GDS Leiden** 社区划分与 LLM 摘要生成，强化全局关联信息的整合能力。
- **工具调度编排**: 设计 Agent 推理主循环，完成 LLM 意图理解、任务拆解与 **Function Calling** 的执行联动。

### ⏱ [基于 YOLOv8 的时钟表盘识别与指针角度计算](https://github.com/ermu03/Clock-Recognition-and-Pointer-Angle-Calculation)
**保研面试项目 | 独立完成**
- **目标检测与分割**: 构建数据集并完成掩码标注，对比多尺度模型后部署 **YOLOv8s-seg**，在测试集达到完美检测率 63.2% 与准确率 85.9%。
- **表盘几何校正**: 设计椭圆拟合与长短轴比例判定机制，结合**仿射变换**对倾斜表盘进行几何校正，提升复杂图像的鲁棒性。
- **双路径角度计算**: 首创对角线比较法与长边方向法结合的计算方案，提取指针方向并将最终角度误差严格控制在 1° 以内。

### 📚 面向高校场景的图书管理系统
**课程设计 | 合作完成**
[前端](https://github.com/ermu03/LibMisFrontend) | [后端](https://github.com/ermu03/LibMisBackend2.0)
- **架构统筹**: 主导系统前后端分离设计，构建 **Spring Boot** 下的 Controller-Service-Mapper 三层逻辑体系，提供标准 RESTful API 服务。
- **核心业务落地**: 独立开发用户权限、图书流转与行为统计等核心模块，设计 **MySQL** 关系模型并优化高频借阅查询与分页加载性能。
- **工程规范建设**: 依托 **Git** 确立版本控制与团队协作规范，统筹分支管理、提交记录与代码审查流程，保障项目开发的持续迭代质量。

---

## 🏆 荣誉奖项 | Awards
- **省级一等奖**: 湖南省电子商务大赛跨境专项赛
- **省级二等奖**: 全国大学生财务大数据应用能力大赛
- **校级二等奖**: 湖南大学冬季杯数学建模竞赛
- **校级奖学金**: 湖南大学二等学业奖学金

---

## 📫 联系我 | Contact Me
- **Email**: [ermu003@hnu.edu.cn](mailto:ermu003@hnu.edu.cn)
- **Location**: 广东 / 湖南
- **Status**: 寻找 **Agent 应用开发** 实习岗位（一周在岗 5 天 | 可连续实习 5 个月以上）
