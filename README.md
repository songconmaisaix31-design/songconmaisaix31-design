# David Wang · DaV1d&nbsp;W

**AI 原生产品工程师，专注多 Agent 协作与经验复用。**

Building Morphogenesis, my main project: an experimental agent swarm exploring coordination through a shared environment and reusable experience.

我喜欢把想法做成可以体验的作品。目前，我把主要精力投入 **Morphogenesis**：探索多个独立 Agent 如何通过共享环境协作，并让一次任务中的经验帮助下一次任务。

## 当前重点 · Morphogenesis

**[Morphogenesis · 形态发生 — Ghost in the Swarm](https://github.com/songconmaisaix31-design/Morphogenesis)** 是我当前最重点的研究与工程项目。灵感来自形态发生、黏菌网络与痕迹协作：让 Agent 通过共享环境留下的任务状态和经验进行协调。

- **任务协作**：通过任务账本、局部路由与写入租约，让 Worker 自主认领任务，并明确各自的执行边界。
- **经验复用**：将可验证的产出沉淀为本地资产，记录其他成员是否实际采用，以及采用后的结果。
- **执行证据**：保留任务状态、失败记录、预算消耗与未知项，让协作过程可以检查和复盘。

目前聚焦**同机多进程、可信 Worker、共享持久化环境**，是持续迭代的实验原型。具体机制与运行边界见[设计与运行说明](https://github.com/songconmaisaix31-design/Morphogenesis/blob/main/docs/SWARM_RUNTIME.md)。

## 更远的方向

我把更长期的方向叫作「共治」：人们带着自己已有的 Agent 加入在线网络，分享经验，发布自己或 Agent 做不到的需求，由其他具有相应能力的 Agent 提供帮助。目前这是长期探索。Morphogenesis 是我验证协作与经验复用机制的主要项目；我希望先在具体任务中积累证据，再探索更开放的在线协作。

## 其他项目

- **[Agent-Kernel](https://github.com/songconmaisaix31-design/agent-kernel-cli)** · 早期执行与验证探索：Windows 单任务 CLI 原型，支持普通程序的启动、状态查询、停止和结果记录；Codex 真实任务的成功验收仍待完成。此前的 [Orca-Kernel 实验](https://github.com/songconmaisaix31-design/orca-kernel) 基于 [stablyai/orca](https://github.com/stablyai/orca)，与独立 CLI 分属不同实现。

- **[同频](https://github.com/songconmaisaix31-design/tongpin-real-tags)** · 团队比赛原型：以行为标签、匿名匹配和渐进身份解锁探索人与人的连接，获纯爱战神黑客松全场第二。我参与提出方向，负责主体前后端、整合与演示；第三方数据使用 Mock。

- **[We Remember / 都记得](https://github.com/songconmaisaix31-design/we-remember)** · 团队产品原型：让家庭日程与照护责任有明确的接手确认。方向由团队共同构思，另一位成员主要负责产品；我主要负责 UI、硬件、代码实现与部分路演。

- **[oil-agent](https://github.com/songconmaisaix31-design/oil-agent)** · 实验原型：探索成品油资讯监测、证据核对与移动端提醒，将消息判断和提醒回执串成可检查的流程。已有模拟输入的集成测试，真实预警效果仍待验证。

- **[氢哨 / OpenDashboard-H2](https://github.com/songconmaisaix31-design/OpenDashboard-H2)** · 团队比赛作品：面向绿氢 EMS 功率协调异常的诊断与运检助手，进入浦发・IGNITE 未来能源黑客松初赛 Top 20。我完成初赛大部分实现、全量数据导入及部分平台整合；朋友推进复赛算法与现场工作。

- **[OpenDashboard](https://github.com/songconmaisaix31-design/OpenDashboard)** · 早期控制台实验：探索本地服务观测、诊断与人工确认流程，沉淀静态插件和数据契约实践；当前用固定数据演示，恢复操作为模拟。

## 我怎样工作

从具体问题出发，把产品定义、交互设计与工程实现连起来。我使用 AI 和多 Agent 辅助研究、开发与检查，自己负责需求判断、任务拆解、集成和验收；通过实际运行与反馈决定下一步。

常用技术：Python、SQLite、FastAPI；React、TypeScript、Node.js。

## 交流与合作

欢迎带着真实任务交流多 Agent 协作、经验复用和有具体场景的 AI 产品。可以在 [Morphogenesis Issues](https://github.com/songconmaisaix31-design/Morphogenesis/issues) 分享协作失败、经验难以复用或结果难以验证的案例，也欢迎在对应项目中反馈体验。
