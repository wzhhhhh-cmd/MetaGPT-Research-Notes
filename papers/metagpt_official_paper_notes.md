# 阅读笔记：《MetaGPT: Meta Programming for a Multi-Agent Collaborative Framework》

## 文献摘要

> 本文提出了一种基于元编程的多智能体协同框架，旨在模拟软件工程团队的角色划分和流程复用。

## 我的理解

- 强调“角色＝Agent”的设定，体现了高度工程化的思维
- 核心创新点在于：将开发流程结构化 → 将结构分配给 agent → agent 执行并互相反馈
- 与 AutoGPT 相比，MetaGPT 更适合团队协作场景

## 不懂的地方

- TaskGraph 的构建细节不明确
- CodeExecutor 的代码安全问题如何处理？

## 思考与应用

- 是否能应用于课程项目协作？
- 能否与 LlamaIndex 联动，实现文档辅助 agent 开发？
