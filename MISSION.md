# Mission: 造出自己的生产级 Agent

## Why

用户想基于 AionUi / AionCore / aionrs 这套真实生产栈，理解 AI Agent 的原理，最终能自己设计并实现一个生产级别的 Agent（不是玩具 demo，而是带工具、防护、上下文管理的可用系统）。

## Success looks like

- 能徒手讲清 agent 循环（run / turn / tool round）并指出它在 aionrs 源码里的位置
- 能实现一个最小可用 agent：LLM 调用 + 工具注册表 + 循环 + 停止条件
- 能说出生产级和玩具级的差距在哪：护栏（max_turns、失败重试）、上下文压缩、权限确认、会话持久化、可观测性
- 最终产出：一个自己写的、能跑真实任务的 agent 项目

## Constraints

- 用户会 JavaScript/TypeScript，Rust 零基础（读得懂大意即可，不要求写 Rust）
- 中文学习，英文术语保留原文
- 偏好通过真实代码学，不要空泛理论
- 已有可运行的本地环境：AionUi + AionCore + aionrs 源码（`~/.cargo/git/checkouts/aionrs-*/`）

## Out of scope

- 模型训练 / 微调原理
- Rust 语言系统教学（只在需要时解释读代码必需的最小语法）
- 前端 UI 实现细节
