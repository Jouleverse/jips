# Jouleverse Improvement Proposals - 焦耳宇宙改进提案

Jouleverse 社区（含核心与生态）的任何人都可以提交 JIP（改进提案）。

## 双轨共识：Core 轨与 Ecosystem 轨的共识方法不同

Jouleverse 采用**去中心化平行双轨治理**：Core（核心）与 Eco（生态）各自独立、互不隶属。**两轨的共识方法不同**，提交提案前请先判断你的提案属于哪一轨：

| | **Core track（核心轨）** | **Ecosystem track（生态轨）** |
|---|---|---|
| 范围 | 核心基础设施的建设与维护（协议、链、索引、核心治理基础设施等） | 生态的自由发展（生态基金、生态应用等） |
| 共识方法 | **CGC Rough Consensus（粗糙共识）** | **veJ 链上投票** |
| 机制 | 在 GitHub 上以 issue/PR 异步公示，Core 成员以 `from core id` 跟帖表态（赞成 / 反对附理由）；公示期满（7～14 天）由 CGC 会议判定是否达成粗糙共识 | 温度检查 → 共识检查 → 正式投票（按 veJ 质押投票权计票） |
| 规则依据 | [CGC Rough Consensus 议事办法](https://github.com/Jouleverse/workspace/blob/main/cgc-github-rough-consensus-draft.md) | [社区治理系统（阶段0）](governance0.md) |

### 提交指引

- **core JIP（核心提案）**：先上 [CGC 会议](https://github.com/Jouleverse/open-meetings/) 向大家阐述你的基本理念，经大家共同商议后，fork 该 repo 并发起 PR。公示期内由 Core 成员按 [CGC Rough Consensus 议事办法](https://github.com/Jouleverse/workspace/blob/main/cgc-github-rough-consensus-draft.md) 表态，CGC 会议判定是否达成粗糙共识。
- **ecosystem JIP（生态发展提案）**：请参考 [社区治理系统（阶段0）](governance0.md) 的提案程序（veJ 链上投票）。

创建了 JIP 文档不代表它会被接受和执行。

提案人应该考虑到，Jouleverse 用户的共识（参阅：[经济上的大多数](https://en.bitcoin.it/wiki/Economic_majority)）可能会最终决定同意与否。

## 提案索引

**编号** | **范围** | **标题** | **提案人** | **类型** | **状态**
-|-|-|-|-|-
[5](jip-0005.md) | 生态发展提案 | Jouleverse首支生态基金ecofund1成立拨款1.44亿WJ | @楼兰渔夫 <br> @LouisAwesome <br> @岑云 <br> @火星 <br> @煜歌 <br> @OPEN <br> @明海云 | 生态预算申请 | 活跃
[6](jip-0006.md) | 治理流程提案 | 将 jips 改进为 jeeps — Jouleverse Ecosystem Evolution Proposal(s) 🚙（JIP-6 = JEEP-6） | @教链(J-25) <br> @xiaoxin2140 | 治理流程提案 | 已撤回（仓库名保留 JIPS）
