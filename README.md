# Hi, I'm HXT 👋

> 独立开发者 / 计算机专业学生。喜欢把「一个小痛点」做成能长期跑起来的完整工具 —— 而不是停在 demo。

我的仓库大概分成四类：**AI 工作流工具**、**自托管服务**、**课程与刷题工具**、**逆向与自动化脚本**。
共同点是：**能跑、能部署、有真实使用记录**。

---

## 🔨 我在做什么

### AI / Agent 工程
| 项目 | 说明 |
|---|---|
| [jianying-auto-subtitle](https://github.com/qqqqqqiu0804/jianying-auto-subtitle) | 剪映自动字幕：拖视频进去，自动识别并生成带字幕轨的**可编辑草稿**。GUI + CLI，**不依赖任何 API key**（本地模型）。 |
| [deepseek-harness-background](https://github.com/qqqqqqiu0804/deepseek-harness-background) | DeepSeek Harness Web UI 换肤 Skill：从真实页面里提取 CSS/JS，实现背景图 + 透明度滑块的注入式改造。 |
| [desktop-pet-generator-skill](https://github.com/qqqqqqiu0804/desktop-pet-generator-skill) | 一句话生成桌面宠物（HTML/Canvas）的 Skill 生成器。 |
| [workshop-balance-capacity](https://github.com/qqqqqqiu0804/workshop-balance-capacity) | 车间月产量平衡点分析：读订单 xlsx 实时算候选平衡点，直接出老板版 HTML 报告。 |
| [thh.skill](https://github.com/qqqqqqiu0804/thh.skill) | 公关公文写作 Skill：从事件 + 立场生成可直接发布的危机声明。 |

### 自托管 / 全栈
- **NexusCore** — 个人工作台（今日 / 账本 / 课表 / 物品 / 报告 + KV 同步）。Node + SQLite + nginx 反代，每日 03:00 热备轮转，pm2 常驻，私有仓库。
- **Reader** — 自部署 EPUB / TXT / 漫画 / PDF 阅读器，跑在自己的域名下，打了一整套部署侧补丁。
- **车间 ERP**（私有）— 五金厂生产管理 + 轻量进销存。Node 22 + Express + 内置 `node:sqlite`，**零第三方依赖、可离线**，P0–P11 全量上线，日活在用。

### 前端 / 游戏
| 项目 | 说明 |
|---|---|
| [vocab-app](https://github.com/qqqqqqiu0804/vocab-app) | 「不背单词」复刻：真实例句 + SRS 评分 + 离线例句包（中考 → GRE）。 |
| [60sec-clone](https://github.com/qqqqqqiu0804/60sec-clone) | *60 Seconds!* 高保真复刻 · Phaser 3 + TypeScript + Vite。 |
| [bird-adventure-game](https://github.com/qqqqqqiu0804/bird-adventure-game) | 飞翔小鸟冒险版 · Java Swing 2D 休闲冒险。 |

### 自动化 / 逆向
- 抖音自动续火花、微博超话签到的定时任务（跑在自建服务器上，每日自动推执行进度）。
- 超星学习通复制解锁、网课辅助等 Tampermonkey 脚本；小程序 / 单页应用的抓包与接口复刻。

---

## 🧭 我的取巧之处（工程偏好）

- **本地优先**：能不连服务就不连。node:sqlite、本地模型、离线词典包。
- **零依赖优先**：能不装包就不装。一个 `npm i` 就坏的交付物，等于没交付。
- **可回滚**：改生产配置前先备份，改动写成可重跑的脚本。
- **真实数据驱动**：报告、看板、统计都从真实数据现算，不写死。

---

## 📊 数据

<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=qqqqqqiu0804&show_icons=true&hide_title=true&hide_rank=true&count_private=true&theme=default" />
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=qqqqqqiu0804&layout=compact&langs_count=8&hide_title=true" />
</p>

---

## 📫 联系

- Email：`3403611094@qq.com`
- 有想一起做的工具、或者想让我帮你把某个重复劳动自动化，欢迎开 issue 或邮件。

<sub>这个 profile 是活文档，会随手上项目一起更新。</sub>
