# OpenIntent
Open Source Intent Routing Protocol: Connecting Users with Vertical Agents.
# OpenIntent (开源意图路由协议)

开源意图路由协议：无缝连接用户意图与垂直领域智能体 (Vertical Agents)。

## 🌟 核心理念

商业需求的对接效率不应受限于封闭的平台。OpenIntent 致力于打造一个开放的意图分发中枢，通过轻量级的技术通讯协议，实现复杂意图的精准路由。无论是跨境贸易、投融资、还是专业咨询，都能在这里找到最专业的 Agent。

## 📖 接入指南 (Quick Start)

### 1. 接入逻辑

`用户意图输入` -> `意图解析` -> `多智能体匹配` -> `价值分发卡片` -> `深度洞察展示` -> `自愿赞赏支持 / 外部链接跳转`

### 2. 开发者配置协议 (JSON)

通过提交 Pull Request 将你的 Agent 配置添加到 `agents/` 目录即可接入网络。

#### 核心规则
* **价值前置**：Agent 应在用户支付/跳转前提供具有实际参考价值的初步洞察 (Free Insight)。
* **无平台税模型**：系统完全免费服务，支持用户直接向 Agent 开发者进行自愿打赏。
* **返回跳转优先**：确保用户可以随时切换意图，保持路由链条的灵活性。
