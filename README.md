# 🔮 QuestFlow

### 智能题库工作流系统

**自动化题目生成 · AI双模型作答 · 智能判分 · 错题归档**

![Version](https://img.shields.io/badge/版本-v1.0.0-00d4aa?style=flat-square&labelColor=0d1117)
![License](https://img.shields.io/badge/许可证-MIT-7c6aef?style=flat-square&labelColor=0d1117)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white&labelColor=0d1117)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white&labelColor=0d1117)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black&labelColor=0d1117)
![AI Powered](https://img.shields.io/badge/AI-Powered-9b59b6?style=flat-square&labelColor=0d1117)
![AI Assisted](https://img.shields.io/badge/开发辅助-AI_Assisted-e74c3c?style=flat-square&labelColor=0d1117)
![DCR Team](https://img.shields.io/badge/DCR_Team-学生互助频道-00d4aa?style=flat-square&labelColor=0d1117)

<br>

<a href="https://baoliaojiang.github.io/questflow/">🚀 在线体验</a> · <a href="#快速开始">⚡ 快速开始</a> · <a href="#功能特性">✨ 功能特性</a> · <a href="#dcr-学生互助频道">💚 DCR 团队</a>

</div>

---

> **🤖 AI 辅助开发声明**
>
> 本项目的代码、文档及设计均由 **AI 辅助生成**，经人工审核与调整后发布。核心架构设计、功能需求和产品决策由人类开发者主导，AI 工具在代码编写、文档撰写和 UI 设计方面提供了协助。详见 [AI 使用说明](#ai-辅助开发说明)。

---

## 📖 目录

- [项目简介](#项目简介)
- [DCR 学生互助频道](#dcr-学生互助频道)
- [快速开始](#快速开始)
- [功能特性](#功能特性)
  - [数据仪表盘](#1-数据仪表盘)
  - [API 配置](#2-api-配置)
  - [系统设置](#3-系统设置)
  - [题目生成](#4-题目生成)
  - [自动作答](#5-自动作答)
  - [工作流控制](#6-工作流控制)
  - [题库管理](#7-题库管理)
  - [错题本](#8-错题本)
  - [操作日志](#9-操作日志)
- [系统架构](#系统架构)
- [支持的 AI 服务商](#支持的-ai-服务商)
- [数据管理](#数据管理)
- [浏览器兼容性](#浏览器兼容性)
- [常见问题](#常见问题)
- [AI 辅助开发说明](#ai-辅助开发说明)
- [贡献指南](#贡献指南)
- [许可证](#许可证)

---

## 项目简介

**QuestFlow** 是一款**零部署**的智能题库工作流系统——单个 HTML 文件，浏览器打开即用。

系统通过两个独立 AI 模型实现完整的 **「出题 → 答题 → 判分 → 归档」** 自动化闭环，适用于教育工作者、培训团队、自学者和内容创作者的题库建设与知识检验场景。

### 为什么选择 QuestFlow？

| 痛点 | QuestFlow 方案 |
|------|---------------|
| 手动出题耗时费力 | AI 批量生成，支持多题型多难度 |
| 单一视角评估局限 | 双模型独立出题与答题，客观评估 |
| 错题管理零散 | 自动归档错题，支持筛选、标签、重做 |
| 技术门槛高 | 单文件零部署，非技术用户也能上手 |
| 数据不安全 | 纯本地存储，API Key 不离开浏览器 |

---

## DCR 学生互助频道

### 关于 DCR

**DCR**（学生互助频道）自 2023 年成立以来，一直致力于为那些对学校违规补课心存不满、渴望互助，却因种种顾虑不便举报的学生们，搭建一个提供无偿帮助的温暖平台。

DCR 是一个以学生为主体的公益互助与知识交流组织，聚焦同学们在学习生活中可能遇到的违规问题，提供政策学习、经验分享与互助交流。平台不组织、不支持任何举报或行动，仅提供信息参考与风险警示。

不同省份的学生互相帮忙以保证相对的安全，这种方式即互助。DCR 通过跨地区的协作机制，为有需要的同学提供安全、专业的帮助。

### 平台特色服务

| 服务 | 说明 |
|------|------|
| 📋 **委托表生成器** | 在线填写委托表，快速生成规范的互助表 |
| 🤖 **AI Bot** | 智能 AI bot 协助完成互助材料的准备工作 |
| 💚 **心灵加油站** | 为大家提供一个安全、温暖、私密的倾诉空间 |

### DCR 的互助理念

- **无偿帮助**：平台完全免费，不收取任何费用
- **跨省互助**：不同省份的学生互相帮忙，保障相对安全
- **流程规范**：从填写委托表到成功加入互助队伍，每一步都有清晰指引
- **AI 赋能**：借助 AI 技术提升互助效率，降低操作门槛

### QuestFlow 与 DCR

**QuestFlow** 是由 DCR 学生互助频道团队开发的开源项目。作为 DCR 平台 AI Bot 能力的技术延伸，QuestFlow 致力于将 AI 辅助学习的理念落地为可直接使用的工具产品。DCR 团队相信，技术应当服务于学生的实际需求——无论是互助还是学习，都应当让每个人都能低门槛、高效率地获得帮助。

---

## 快速开始

### 方式一：GitHub Pages 在线访问（推荐）

直接访问在线部署地址，无需安装任何东西：

> **🔗 https://downs-crying-for-rights.github.io/QuestFlow/ **

### 方式二：克隆到本地

```bash
# 克隆仓库
git clone https://github.com/baoliaojiang/questflow.git

# 进入目录
cd questflow

# 用浏览器打开 index.html
# Windows: 直接双击 index.html
# macOS:
open index.html
# Linux:
xdg-open index.html
```

### 方式三：本地开发服务器

```bash
# Python
python -m http.server 8080

# Node.js
npx serve .

# VS Code
# 安装 Live Server 扩展，右键 index.html → Open with Live Server
```

然后访问 `http://localhost:8080`

### 首次使用指引

```
┌─────────────────────────────────────────────────────┐
│  第1步  打开系统，进入左侧「API 配置」                  │
│           ↓                                         │
│  第2步  点击「+ 添加 API」，填入你的 API Key            │
│           ↓                                         │
│  第3步  建议配置两个 API（生成用一个，作答用一个）        │
│           ↓                                         │
│  第4步  进入「题目生成」页，设置主题和参数               │
│           ↓                                         │
│  第5步  点击生成 / 或使用「工作流控制」一键运行          │
│           ↓                                         │
│  第6步  查看「题库管理」和「错题本」中的结果             │
└─────────────────────────────────────────────────────┘
```

---

## 功能特性

### 1. 数据仪表盘

系统的主页面，提供全局数据概览：

- **四项核心指标卡片**：题目总数、作答总数、正确率、错题数
- **生成趋势折线图**：展示最近 7 天的生成量、作答量和正确率走势
- **类型分布环形图**：所有已生成题目按题型的占比
- **难度分布柱状图**：所有已生成题目按难度的数量分布
- **最近活动流**：展示最新操作记录

### 2. API 配置

支持同时配置多个 AI 服务提供商的 API：

- **六种预设服务商**：OpenAI、Anthropic、DeepSeek、通义千问、智谱 GLM、Moonshot
- **自定义服务商**：支持任意 OpenAI 兼容 API 端点
- **快速测试**：配置完成后可立即测试连通性
- **密钥安全**：API Key 仅存储在浏览器本地，UI 显示时自动掩码
- **多配置管理**：增删改查全部支持，灵活切换

### 3. 系统设置

全面的可配置参数：

| 分类 | 参数 | 默认值 |
|------|------|--------|
| 生成设置 | 默认生成 API | 无 |
| 生成设置 | 默认作答 API | 无 |
| 生成设置 | 请求间隔 | 1000ms |
| 生成设置 | 单次最大生成数 | 20 |
| 生成设置 | 自动保存间隔 | 30s |
| 判断设置 | 判断模式 | AI 自动判断 |
| 判断设置 | AI 判断温度 | 0.1 |
| 判断设置 | 通过阈值 | 60% |
| 判断设置 | 判断提示词模板 | 内置模板，支持自定义 |

### 4. 题目生成

- 支持 **选择题、判断题、填空题、简答题** 四种题型
- 可配置数量（1~50）、难度（简单/中等/困难/混合）
- 内置四套生成模板：**考试真题 / 练习题 / 面试题 / 竞赛题**
- 支持自由描述生成要求，灵活适配任意知识领域
- 实时预览生成结果，含题目内容、选项、正确答案和解析

### 5. 自动作答

- 集成**第二个独立 AI 模型**，与出题模型分离，确保评估客观性
- 三种作答策略：

| 策略 | 特点 | 适用场景 |
|------|------|----------|
| 直接回答 | AI 直接给出最终答案，速度快 | 选择题、判断题 |
| 思维链推理 | AI 先展示推理过程再给出答案 | 需要分析的题目 |
| 审慎回答 | AI 排除法分析每个选项，标注置信度 | 高难度题目 |

- 可调节答题温度（0~1），控制创造性与保守性
- 四种作答范围：未答题 / 最近生成 / 错题重做 / 全部重答

### 6. 工作流控制

一键整合「出题→答题→判分→归档」全流程：

```
┌──────────┐    ┌──────────┐    ┌──────────┐    ┌──────────┐
│  配置参数 │ →  │  批量生成 │ →  │  自动作答 │ →  │  判定归档 │
│  Step 1   │    │  Step 2   │    │  Step 3   │    │  Step 4   │
└──────────┘    └──────────┘    └──────────┘    └──────────┘
```

- **全自动模式**：四步连续执行，无需人工干预
- **手动确认模式**：每步暂停等待确认，适合需要审核的场景
- 实时进度可视化 + 运行日志
- 支持随时停止工作流

### 7. 题库管理

对所有已生成题目的统一管理：

- 按题目内容**实时搜索**
- 按题型（选择/判断/填空/简答）**筛选**
- 按难度（简单/中等/困难）**筛选**
- 查看**完整详情**：题目、选项、正确答案、解析、作答记录
- 支持**删除**和**导出**

### 8. 错题本

自动收集所有被判定为错误的题目：

- 按类型、标签、关键词**多维筛选检索**
- 记录**错误次数**、错误答案和时间线
- 标记**已掌握**后可从错题本移除
- 一键**导出错题**为 JSON 文件
- **错题重做**功能，将错题重新送入作答流程

### 9. 操作日志

系统记录所有关键操作和运行事件：

| 级别 | 颜色 | 含义 |
|------|------|------|
| INFO | 🔵 蓝色 | 一般信息通知 |
| SUCCESS | 🟢 绿色 | 操作成功完成 |
| WARN | 🟡 黄色 | 警告信息 |
| ERROR | 🔴 红色 | 错误信息 |

- 按级别筛选
- 最多保留 500 条记录
- 含时间戳、模块名和详细消息

---

## 系统架构

```
┌──────────────────────────────────────────────────────┐
│                   浏览器 (单页应用)                     │
│                                                      │
│  ┌─────────┐  ┌─────────┐  ┌─────────┐  ┌────────┐  │
│  │ 仪表盘  │  │ API配置  │  │ 题目生成 │  │自动作答 │  │
│  └────┬────┘  └────┬────┘  └────┬────┘  └───┬────┘  │
│       └────────────┴────────────┴────────────┘       │
│                      ↓                               │
│  ┌─────────────────────────────────────────────────┐ │
│  │            核心调度引擎 + 状态管理                │ │
│  │   (Workflow Engine · State Manager · Logger)     │ │
│  └──────────────────────┬──────────────────────────┘ │
│                         ↓                            │
│  ┌──────────────────────────────────────────────────┐│
│  │              localStorage 持久化                  ││
│  └──────────────────────────────────────────────────┘│
└──────────────────────┬───────────────────────────────┘
                       │ HTTPS
          ┌────────────┴────────────┐
          ↓                         ↓
    ┌───────────┐           ┌───────────┐
    │  AI 模型 A │           │  AI 模型 B │
    │  (出题)    │           │  (答题)    │
    └───────────┘           └───────────┘
```

### 技术栈

| 组件 | 技术方案 | 说明 |
|------|----------|------|
| 前端框架 | 原生 HTML/CSS/JS | 零依赖，单文件部署 |
| 图表库 | Chart.js 4.x | 数据可视化 |
| 字体 | Syne + Noto Sans SC | 显示字体 + 中文正文字体 |
| 数据存储 | localStorage | 浏览器本地持久化 |
| AI 通信 | Fetch API | 标准 REST 调用 |
| UI 风格 | Liquid Glass | backdrop-filter 毛玻璃效果 |

### 项目结构

```
questflow/
├── index.html          # 主应用文件（包含全部 HTML/CSS/JS）
├── README.md           # 项目说明文档
└── LICENSE             # MIT 许可证
```

> **单文件架构**：所有代码集中在 `index.html` 中，零依赖、零构建、零配置。

---

## 支持的 AI 服务商

<table>
<tr>
<th>服务商</th>
<th>默认模型</th>
<th>默认 Base URL</th>
<th>官网</th>
</tr>
<tr>
<td>🟢 OpenAI</td>
<td>gpt-4o</td>
<td><code>https://api.openai.com/v1</code></td>
<td><a href="https://openai.com">openai.com</a></td>
</tr>
<tr>
<td>🟤 Anthropic</td>
<td>claude-sonnet-4-20250514</td>
<td><code>https://api.anthropic.com/v1</code></td>
<td><a href="https://anthropic.com">anthropic.com</a></td>
</tr>
<tr>
<td>🔵 DeepSeek</td>
<td>deepseek-chat</td>
<td><code>https://api.deepseek.com/v1</code></td>
<td><a href="https://deepseek.com">deepseek.com</a></td>
</tr>
<tr>
<td>🟣 通义千问</td>
<td>qwen-plus</td>
<td><code>https://dashscope.aliyuncs.com/compatible-mode/v1</code></td>
<td><a href="https://dashscope.aliyun.com">dashscope.aliyun.com</a></td>
</tr>
<tr>
<td>🔴 智谱 GLM</td>
<td>glm-4-flash</td>
<td><code>https://open.bigmodel.cn/api/paas/v4</code></td>
<td><a href="https://bigmodel.cn">bigmodel.cn</a></td>
</tr>
<tr>
<td>🌙 Moonshot</td>
<td>moonshot-v1-8k</td>
<td><code>https://api.moonshot.cn/v1</code></td>
<td><a href="https://moonshot.cn">moonshot.cn</a></td>
</tr>
<tr>
<td>🔧 自定义</td>
<td>手动填写</td>
<td>手动填写</td>
<td>—</td>
</tr>
</table>

> **推荐配置**：使用一个模型生成题目，另一个模型作答，确保评估的独立性和客观性。例如：DeepSeek 出题 + 通义千问答题。

---

## 数据管理

### 存储方式

所有数据均存储在浏览器 `localStorage` 中，**不会上传至任何第三方服务器**。

| 数据类型 | 说明 |
|----------|------|
| API 配置 | 所有已配置的 AI 端点信息 |
| 题库 | 所有已生成的题目 |
| 作答记录 | 所有 AI 作答记录 |
| 错题本 | 错题归档数据 |
| 系统设置 | 用户自定义参数 |
| 统计数据 | 全局统计和历史记录 |
| 操作日志 | 系统运行日志 |

### 导入导出

| 操作 | 位置 | 格式 | 说明 |
|------|------|------|------|
| 导出全部 | 顶栏 / 设置页 | JSON | 包含所有配置和数据 |
| 导出题目 | 题库管理页 | JSON | 仅导出题目列表 |
| 导出错题 | 错题本页 | JSON | 导出错题及原始题目 |
| 导入数据 | 顶栏 / 设置页 | JSON | 从备份文件恢复 |

> ⚠️ **重要提示**：定期导出备份！清除浏览器缓存或使用隐私模式会导致数据丢失。

---

## 浏览器兼容性

| 浏览器 | 最低版本 | 状态 |
|--------|----------|------|
| Google Chrome | 120+ | ✅ 完全支持，推荐使用 |
| Microsoft Edge | 120+ | ✅ 完全支持 |
| Firefox | 120+ | ✅ 完全支持 |
| Safari | 17+ | ✅ 完全支持 |
| 移动端 Chrome | 120+ | ✅ 响应式适配 |
| 移动端 Safari | 17+ | ✅ 响应式适配 |

**关键依赖特性**：
`backdrop-filter` · `fetch()` · `localStorage` · CSS Grid/Flexbox · CSS Custom Properties · ES6+

---

## 常见问题

<details>
<summary><b>Q: 打开页面一片空白？</b></summary>

请检查浏览器版本是否满足最低要求。部分老旧浏览器不支持 `backdrop-filter` 或 ES6+ 语法。建议使用最新版 Chrome。

</details>

<details>
<summary><b>Q: API 调用报 CORS 错误？</b></summary>

这是浏览器的跨域安全限制，和部署方式无关。解决方案：

1. 使用支持浏览器直接调用的服务商（如 DeepSeek、通义千问）
2. 配置支持 CORS 的 API 中转代理服务
3. 使用本地反向代理（Nginx / Node.js）
4. 安装 CORS 解除浏览器扩展（仅限开发测试）

</details>

<details>
<summary><b>Q: 生成的题目 JSON 格式不正确？</b></summary>

- 单次生成数量建议不超过 10 道
- 使用更强的模型（如 GPT-4o 而非 GPT-3.5）
- 在补充要求中强调"严格按照 JSON 数组格式返回，不要添加任何其他文字"

</details>

<details>
<summary><b>Q: 数据丢失了怎么办？</b></summary>

以下操作会导致数据丢失：
- 清除浏览器缓存/数据
- 使用隐私/无痕模式
- 卸载重装浏览器

如有备份 JSON 文件，可通过「导入数据」恢复。**强烈建议定期导出备份。**

</details>

<details>
<summary><b>Q: 可以用本地大模型吗？</b></summary>

可以。通过 Ollama、vLLM、LM Studio 等工具部署本地模型后，在 API 配置中选择「自定义」，填入本地地址即可：

- Ollama 默认：`http://localhost:11434/v1`
- LM Studio 默认：`http://localhost:1234/v1`
- vLLM 默认：`http://localhost:8000/v1`

</details>

<details>
<summary><b>Q: 如何提高判分准确性？</b></summary>

- 客观题（选择/判断）：使用**精确匹配**模式
- 主观题（简答/填空）：使用 **AI 判断**模式并调整提示词
- 降低判断温度（如 0.05）可使判分更稳定
- 使用**手动判断**模式获得最精确的结果

</details>

<details>
<summary><b>Q: localStorage 存满了怎么办？</b></summary>

localStorage 通常有 5~10MB 限制。建议：
1. 定期导出数据并清理旧数据
2. 删除不需要的历史题目
3. 清空操作日志
4. 数据量极大时考虑迁移到服务端存储

</details>

<details>
<summary><b>Q: 支持团队多人使用吗？</b></summary>

当前版本基于浏览器 localStorage，适合单用户使用。如需团队协作：
- 通过数据导入导出在成员间共享数据
- 每位成员独立运行各自的实例
- 未来版本可能增加服务端存储和多用户支持

</details>

---

## AI 辅助开发说明

本项目明确标注并声明使用了 AI 工具辅助开发。

### AI 参与的部分

| 环节 | 参与程度 | 说明 |
|------|----------|------|
| 代码编写 | 🟢 高 | 核心逻辑、UI 组件、样式均由 AI 生成初稿 |
| 架构设计 | 🟡 中 | 整体架构由人类设计，AI 协助细化实现方案 |
| 文档撰写 | 🟢 高 | README、注释、用户指引由 AI 辅助生成 |
| UI 设计 | 🟢 高 | 视觉风格、配色方案、动效设计由 AI 生成 |
| 需求定义 | 🔴 低 | 功能需求和产品决策由人类主导 |
| 质量审核 | 🟡 中 | 人工审核 AI 生成的代码，进行调整和修正 |

### 使用的 AI 工具

| 工具 | 用途 |
|------|------|
| **MiMo**（小米大模型） | 主要代码生成与文档撰写 |

### 我们的立场

- ✅ 透明公开 AI 参与开发的事实
- ✅ 人工审核所有 AI 生成内容后发布
- ✅ 对 AI 生成代码的质量和安全性负责
- ✅ 持续人工维护和迭代更新

> 我们相信 AI 是提升开发效率的工具，而非替代人类创造力的手段。在 QuestFlow 的开发中，AI 帮助我们快速实现了复杂的功能逻辑和精美的界面设计，而产品方向、用户体验决策和最终质量把控始终由人类团队负责。

---

## 贡献指南

欢迎对 QuestFlow 做出贡献！

### 贡献流程

```bash
# 1. Fork 本仓库
#    点击页面右上角的 Fork 按钮

# 2. 克隆你的 Fork
git clone https://github.com/baoliaojiang/questflow.git

# 3. 创建功能分支
git checkout -b feature/your-feature

# 4. 进行修改并提交
git add .
git commit -m "feat: add your feature"

# 5. 推送到你的 Fork
git push origin feature/your-feature

# 6. 创建 Pull Request
#    回到 GitHub 页面，点击 "New Pull Request"
```

### 提交规范

| 前缀 | 说明 | 示例 |
|------|------|------|
| `feat:` | 新功能 | `feat: 添加批量导出功能` |
| `fix:` | Bug 修复 | `fix: 修复图表显示异常` |
| `docs:` | 文档更新 | `docs: 更新 README 使用说明` |
| `style:` | 样式调整 | `style: 优化移动端布局` |
| `refactor:` | 代码重构 | `refactor: 重构状态管理模块` |
| `perf:` | 性能优化 | `perf: 优化大量题目的渲染性能` |

> 如果您的贡献中使用了 AI 工具辅助，**请在 PR 描述中注明**。

### 反馈与建议

- 🐛 **Bug 报告**：[提交 Issue](https://github.com/baoliaojiang/questflow/issues/new)
- 💡 **功能建议**：[提交 Issue](https://github.com/baoliaojiang/questflow/issues/new)
- ❓ **使用问题**：查看上方 [常见问题](#常见问题) 或提交 Issue

---

## 许可证

本项目基于 [MIT License](LICENSE) 开源。

```
MIT License

Copyright (c) 2024 DCR Student Mutual Aid Channel

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

<div align="center">

## 💚 DCR 学生互助频道 · 出品

**QuestFlow** — 让题目生成与评估自动化

<br>

<sub>Built with ❤️ by DCR Team · Powered by 🤖 AI assistance</sub>

<br>

<sub>DCR — 为学生提供无偿帮助的温暖平台</sub>

<br><br>

<a href="https://github.com/baoliaojiang/questflow/stargazers">
  <img src="https://img.shields.io/github/stars/baoliaojiang/questflow?style=social" alt="Stars">
</a>
&nbsp;
<a href="https://github.com/baoliaojiang/questflow/network/members">
  <img src="https://img.shields.io/github/forks/baoliaojiang/questflow?style=social" alt="Forks">
</a>
&nbsp;
<a href="https://github.com/baoliaojiang/questflow/issues">
  <img src="https://img.shields.io/github/issues/baoliaojiang/questflow?style=social" alt="Issues">
</a>

</div>
