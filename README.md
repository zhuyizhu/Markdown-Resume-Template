 <center>
     <h1>个人简历</h1>
 </center>

## 个人信息

* 姓 名：朱奕竹
* 性 别：女&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;年 龄：22
* 手 机：18781967671 &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;  邮 箱：zhuyizhu0224@gmail.com
* 专 业：计算机科学与技术 &emsp;&emsp;&emsp;&emsp;&emsp; 岗 位：研发工程师

## 教育经历

* 上海大学&emsp;&emsp;&emsp;&emsp;&emsp;2025.9~至今&emsp;&emsp;&emsp;&emsp; 计算机科学与技术专业-研究生
* 西华大学&emsp;&emsp;&emsp;&emsp;&emsp;2021.9~2025.7&emsp;&emsp;&emsp;&emsp; 计算机科学与技术专业-本科

## 专业技能

* 熟练使用 C++，掌握Go，了解 Java、Python、PHP 等编程语言
* 掌握基础数据结构和算法的基本原理
* 等等

## 项目经历

1.基于多智能体协作的 Java 代码自动化排障系统
项目角色： 核心开发者 / Agent 架构设计
技术栈： LangChain / LangGraph, Java, RepoGraph, LLM API
项目描述：
针对复杂 Java 业务框架中 Bug 定位困难、错误调用链深的问题，设计并从零实现了一套基于多智能体（Multi-Agent）协作的自动化故障定位与诊断流。系统实现了从文件级、函数级到具体代码行级（File-Function-Line）的精准故障预测。
核心贡献与技术细节：
多智能体架构设计 (Agent Orchestration): 基于 LangChain/LangGraph 编排了包含 LocalizeAgent（执行定位）、ReviewAgent/CriticAgent（审查评估）和 ReflectAgent（反思修正）的非线性协作工作流，构建了具备自修正能力的闭环执行链。
图结构代码分析与上下文管理 (Graph-based Context): 针对传统 RAG 文本切块导致代码拓扑关系丢失的痛点，引入 RepoGraph 分析代码库。在 Java 框架内提出并验证“故障传播假设”，使 Agent 能够沿着真实的函数调用链路进行追踪。
记忆与状态引擎 (Memory Bank): 开发了细粒度的预测状态记忆库，将 Agent 每一轮推演的文件、函数和行号持久化。当当前追踪路径被 Critic 打回时，支持系统状态的安全回溯，有效避免了 Agent 在复杂代码中陷入死循环推理。
多维量化评估体系 (Evaluation Rubric): 为解决 LLM 幻觉和评估标准单一的问题，为 CriticAgent 独创了一套结构化的量化评分体系，包含：拓扑可达性 (40%)、语义对齐度 (30%) 以及因果推演合法性 (30%)。该机制大幅提升了系统在复杂故障场景下的拦截率与最终定位准确率。
2. 公司/学校 - XXweb服务器 - 独立开发 - 201508- 201512
    * 具体功能
    * 运用了那些技术，技术难点是
    * 效果如何
    * demo演示地址，github地址

3. 公司/学校 - XX游戏 - 负责后端开发 - 201309- 201401
    * 具体功能
    * 运用了那些技术，技术难点是
    * 效果如何
    * demo演示地址，github地址

## 获奖经历
* XXX 优秀新人
* XXX 学生社团优秀干部
* 竞赛 XXX 奖


## 其他信息
* 喜欢钻研技术 等等
* 性格开朗，喜欢跳舞，做个主持人 等等



