# Agent 原理 Resources

## Knowledge

- [本地源码：aionrs v0.2.11](~/.cargo/git/checkouts/aionrs-c860c928cccf810e/8e61a90/)
  生产级 agent 引擎的完整 Rust 源码，编译 AionCore 时拉到本机。Use for: 一切「真实实现怎么做」的问题，尤其是 `crates/aion-agent/src/engine.rs` 的循环和 `docs/core-concepts.md` 的运行时模型。
- [aionrs 官方文档：core-concepts.md](~/.cargo/git/checkouts/aionrs-c860c928cccf810e/8e61a90/docs/core-concepts.md)
  定义 run / turn / tool round 的权威来源。Use for: 术语对齐、时序图。
- [aionrs 官方文档：advanced.md](~/.cargo/git/checkouts/aionrs-c860c928cccf810e/8e61a90/docs/advanced.md)
  上下文压缩、记忆、plan mode、钩子。Use for: 学到「生产级要素」阶段时的主参考。
- [Anthropic: Building Effective Agents](https://www.anthropic.com/engineering/building-effective-agents)
  Agent 模式的经典文章，区分 workflow 和 agent。Use for: 建立「什么时候该用 agent」的判断力。
- [MCP 官方规范](https://modelcontextprotocol.io/)
  工具/资源暴露给模型的协议。Use for: 理解 aionrs 的 MCP client 和 AionCore 的 MCP 管理。
- [Agent Client Protocol](https://agentclientprotocol.com/)
  AionCore 对接外部 CLI agent 的协议。Use for: 理解多 agent 接入层。
- 本地仓库：AionCore（`/Users/jeek/Documents/work/code/github/AionCore`）
  agent 的服务化封装：会话、权限确认、WebSocket 推送。Use for: 学「引擎如何包装成产品」。

## Wisdom (Communities)

- [AionUi Discord](https://discord.gg/2QAwJn7Egx) / 微信中文群（见 AionUi readme）
  Use for: 这套栈的实现细节提问。
- [Anthropic Engineering Blog](https://www.anthropic.com/engineering)
  Use for: agent 设计的最新实践文章。

## Gaps

- aionrs 没有官方中文资料——课程里自己沉淀。
