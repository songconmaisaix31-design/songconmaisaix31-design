# David Wang · DaV1d&nbsp;W

**AI 原生产品工程师，关注多 Agent 协作与开发工具。**

Building AI-native products. Exploring how independent agents work together.

我喜欢把想法做成可以体验的作品。最近，我把主要精力放在一个问题上：怎样让多个独立 Agent 不只是同时工作，而是在边界清楚的情况下，共同交付可以检查的结果

## 现在在做

**[Agent-Kernel](https://github.com/songconmaisaix31-design/agent-kernel-cli)** 是我围绕执行与验证开展的工程探索。我关注任务怎样交接、工作边界怎样落实，以及如何判断一次执行真正完成。

当前主入口是独立的 Windows 单任务 CLI 原型，已有普通程序的启动、状态查询、停止与结果记录。Codex 只读调用已有接入代码，真实任务的成功验收仍待完成；多 Agent 协作契约与协议是持续探索的方向。

此前基于 [stablyai/orca](https://github.com/stablyai/orca) 的 [Orca-Kernel 实验](https://github.com/songconmaisaix31-design/orca-kernel/tree/kernel/v01-managed-dispatch)，探索了任务派发、资源归属与验收约束。这些实验与新 CLI 分属不同实现。

## 更远的方向

我把更长期的方向叫作「共治」：人们带着自己已有的 Agent 加入在线网络，分享经验，发布自己或 Agent 做不到的需求，由其他具有相应能力的 Agent 提供帮助。目前这是长期探索。我希望先从具体任务中摸清协作契约，再通过 Agent-Kernel 验证执行与交接，逐步走向开放的在线协作。

## 精选作品

- **[同频](https://github.com/songconmaisaix31-design/tongpin-real-tags)** · 团队比赛原型：以行为标签、匿名匹配和渐进身份解锁探索人与人的连接，获纯爱战神黑客松全场第二。我参与提出方向，负责主体前后端、整合与演示；第三方数据使用 Mock。

- **[We Remember / 都记得](https://github.com/songconmaisaix31-design/we-remember)** · 团队产品原型：让家庭日程与照护责任有明确的接手确认。方向由团队共同构思，另一位成员主要负责产品；我主要负责 UI、硬件、代码实现与部分路演。

- **[oil-agent](https://github.com/songconmaisaix31-design/oil-agent/tree/songconmaisaix31-design/oil-v01-i)** · 开发分支／实验原型：探索成品油资讯监测、证据核对与移动端提醒，将消息判断和提醒回执串成可检查的流程。已有模拟输入的集成测试，真实预警效果仍待验证。

- **[氢哨 / OpenDashboard-H2](https://github.com/songconmaisaix31-design/OpenDashboard-H2)** · 团队比赛作品：面向绿氢 EMS 功率协调异常的诊断与运检助手，进入浦发・IGNITE 未来能源黑客松初赛 Top 20。我完成初赛大部分实现、全量数据导入及部分平台整合；朋友推进复赛算法与现场工作。

- **[OpenDashboard](https://github.com/songconmaisaix31-design/OpenDashboard)** · 早期控制台实验：探索本地服务观测、诊断与人工确认流程，沉淀静态插件和数据契约实践；当前用固定数据演示，恢复操作为模拟。

## 我怎样工作

从具体问题出发，把产品定义、交互设计与工程实现连起来。我使用 AI 和多 Agent 辅助研究、开发与检查，自己负责需求判断、任务拆解、集成和验收；通过实际运行与反馈决定下一步。

常用技术：React、TypeScript、Node.js；Python、FastAPI。

## 交流与合作

欢迎带着真实任务交流多 Agent 协作、开发者工具和有具体场景的 AI 产品。可以试用早期工具，在 [Agent-Kernel Issues](https://github.com/songconmaisaix31-design/agent-kernel-cli/issues) 分享任务交接、边界冲突或结果难以验证的问题，也欢迎在对应项目中反馈体验。
