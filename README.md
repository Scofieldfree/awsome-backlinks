# Awesome Backlinks · 最佳外链清单（README-only MVP）

> 仅用 README 维护数据的开源清单，聚焦「可投稿 / 可收录 / 可挂外链」的优质渠道。拒绝灰产与垃圾目录，倡导长期主义的曝光与 SEO 价值。

![Stars](https://img.shields.io/github/stars/yourname/awesome-backlinks?style=flat)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)
![License](https://img.shields.io/badge/data-CC%20BY%204.0-blue)
![Status](https://img.shields.io/badge/status-MVP-orange)

---

## 目录
- [为什么做](#为什么做)
- [字段说明](#字段说明)
- [使用方式](#使用方式)
- [数据集（主表）](#数据集主表)
  - [Launch / 发布平台](#launch--发布平台)
  - [Dev / 开发者向](#dev--开发者向)
  - [AI Tools / 目录与媒体](#ai-tools--目录与媒体)
  - [Design / 设计与灵感](#design--设计与灵感)
  - [Startup / 创业与独立开发](#startup--创业与独立开发)
  - [Content / 投稿与客座](#content--投稿与客座)
  - [SEO Directory / 行业与通用目录](#seo-directory--行业与通用目录)
  - [Local / 本地化与中文社区](#local--本地化与中文社区)
- [投稿路线建议（按产品类型）](#投稿路线建议按产品类型)
- [贡献方式（MVP 简化流程）](#贡献方式mvp-简化流程)
- [路线图](#路线图)
- [许可证](#许可证)
- [致谢](#致谢)

---

## 为什么做
- **节省时间**：避免盲投与踩坑，集中高质量来源  
- **结构化信息**：外链策略、投稿方式、费用、受众、一眼判定  
- **简单协作**：不引入脚本与数据文件，**只改 README 表格**

> 说明：平台的外链策略随时可能变化，**本表以贡献者标注为准**。默认用 `unknown` 或 `mixed`，鼓励「投稿落地后回填证据」。

---

## 字段说明
- **name**：平台名（链接到投稿页或入口页）  
- **category**：`launch | dev | ai-tools | design | startup | content | seo-directory | local`  
- **accepts**：`product | article | case | repo | app | library | dataset`（逗号分隔）  
- **backlink_policy**：`dofollow | nofollow | mixed | unknown`  
- **submission**：`open | editor-review | paid | invite-only`  
- **fee**：`free | one-time | monthly | sponsor | unknown`  
- **audience**：`dev | indie | design | ai | startup | general`  
- **region_lang**：`global | zh | en | jp | ...`  
- **notes**：门槛/避坑/要点  
- **last_checked**：YYYY-MM-DD（人工更新）

---

## 使用方式
1. 在表格中按 **category / fee / audience** 选最匹配的渠道  
2. 先做 **垂直匹配**（dev/ai/design/startup 等），再扩到 general  
3. 投放后在 **notes/last_checked/backlink_policy** 回填实测结果  
4. 在 GitHub 网页可用浏览器 **`/` 搜索**快速筛选（如 `launch`、`free`、`zh`）

---

## 数据集（主表）
> 🔎 小贴士：优先“高匹配 + 高质量内容”渠道；`unknown/mixed` 并不等于没价值，只代表策略不确定或因账号/版块而异。

### Launch / 发布平台
| name | category | accepts | backlink_policy | submission | fee | audience | region_lang | notes | last_checked |
|---|---|---|---|---|---|---|---|---|---|
| [Product Hunt](https://www.producthunt.com/) | launch | product,article | unknown | editor-review | free | startup,indie | en,global | 发布日曝光强，准备 Demo 与素材 | 2025-10-15 |
| [BetaList](https://betalist.com/submit) | launch | product | mixed | editor-review | free/paid | startup,indie | en,global | 免费排队久；付费加速 | 2025-10-15 |
| [BetaPage](https://betapage.co/) | launch | product | mixed | open | free/paid | startup | en,global | 目录型曝光，质量参差 | 2025-10-15 |
| [Launching Next](https://launchingnext.com/submit/) | launch | product | mixed | editor-review | free | startup | en,global | 偶尔更新慢 | 2025-10-15 |
| [AlternativeTo（建议投文章/指南）](https://alternativeto.net/) | launch | product,article | mixed | editor-review | free | general | en,global | 填写详尽对比信息更易通过 | 2025-10-15 |

### Dev / 开发者向
| name | category | accepts | backlink_policy | submission | fee | audience | region_lang | notes | last_checked |
|---|---|---|---|---|---|---|---|---|---|
| [Hacker News - Show HN](https://news.ycombinator.com/show) | dev | product,article,repo | unknown | editor-review | free | dev,startup | en,global | 重技术含量与讨论质量 | 2025-10-15 |
| [DEV Community](https://dev.to/) | dev | article | mixed | open | free | dev | en,global | 文末署站点；长文更稳 | 2025-10-15 |
| [Hashnode](https://hashnode.com/) | dev | article | mixed | open | free | dev | en,global | 博客网络，支持自定义域 | 2025-10-15 |
| [Lobsters](https://lobste.rs/) | dev | article,repo | unknown | editor-review | free | dev | en,global | 社区较严，慎重投放 | 2025-10-15 |
| [Awesome Lists（相关清单）](https://github.com/sindresorhus/awesome) | dev | repo,library,app | unknown | editor-review | free | dev | en,global | 需高质量&长期维护 | 2025-10-15 |
| [GitHub Topics](https://github.com/topics) | dev | repo,library | unknown | open | free | dev | en,global | 打合适 topics 增曝光 | 2025-10-15 |
| [Open Source Friday](https://opensourcefriday.com/) | dev | repo | unknown | open | free | dev | en,global | 开源曝光与贡献导流 | 2025-10-15 |
| [Reddit r/programming 等](https://www.reddit.com/) | dev | article,case | mixed | editor-review | free | dev | en,global | 遵守各子版规 | 2025-10-15 |

### AI Tools / 目录与媒体
| name | category | accepts | backlink_policy | submission | fee | audience | region_lang | notes | last_checked |
|---|---|---|---|---|---|---|---|---|---|
| AI 工具目录（搜索入口） | ai-tools | product | mixed | open | free/unknown | ai,indie | en,global | *示例：Futurepedia、AI Tool Hunt、There's An AI For That 等，质量参差，择优* | 2025-10-15 |
| [Hugging Face Spaces](https://huggingface.co/spaces) | ai-tools | app,repo | unknown | open | free | ai,dev | en,global | Demo 形态易传播 | 2025-10-15 |
| [Papers with Code Datasets/Methods](https://paperswithcode.com/) | ai-tools | dataset,library | unknown | editor-review | free | ai,dev | en,global | 研究向，证据链完备更佳 | 2025-10-15 |
| [OpenRouter / AI 模型生态论坛](https://openrouter.ai/) | ai-tools | product,article | unknown | open | free | ai,dev | en,global | 生态向曝光点 | 2025-10-15 |

### Design / 设计与灵感
| name | category | accepts | backlink_policy | submission | fee | audience | region_lang | notes | last_checked |
|---|---|---|---|---|---|---|---|---|---|
| [Dribbble](https://dribbble.com/) | design | case,product | mixed | open | free | design | en,global | 作品页适度引流 | 2025-10-15 |
| [Behance](https://www.behance.net/) | design | case,product | mixed | open | free | design | en,global | 项目页可放参考链接 | 2025-10-15 |
| [Figma Community](https://www.figma.com/community) | design | product,template | unknown | open | free | design | en,global | 组件/插件/模板导流 | 2025-10-15 |
| [Product Hunt - Design 工具](https://www.producthunt.com/topics/design-tools) | design | product | unknown | editor-review | free | design,startup | en,global | 结合设计类话题 | 2025-10-15 |
| [Uplabs](https://www.uplabs.com/) | design | product,template | mixed | editor-review | free/paid | design | en,global | 上架审核，素材向更合适 | 2025-10-15 |

### Startup / 创业与独立开发
| name | category | accepts | backlink_policy | submission | fee | audience | region_lang | notes | last_checked |
|---|---|---|---|---|---|---|---|---|---|
| [Indie Hackers](https://www.indiehackers.com/) | startup | product,article | mixed | open | free | indie,startup | en,global | 复盘与连载更稳 | 2025-10-15 |
| [Indie Makers / Makerlog 等](https://twitter.com/levelsio) | startup | product,article | mixed | open | free | indie | en,global | Maker 社群曝光点 | 2025-10-15 |
| [Startup Stash](https://startupstash.com/) | startup | product | unknown | editor-review | free | startup | en,global | 工具导航型 | 2025-10-15 |
| [Startups.fyi（展示）](https://startups.fyi/) | startup | product | mixed | editor-review | paid | startup | en,global | 付费上榜 | 2025-10-15 |

### Content / 投稿与客座
| name | category | accepts | backlink_policy | submission | fee | audience | region_lang | notes | last_checked |
|---|---|---|---|---|---|---|---|---|---|
| [Medium Publications](https://medium.com/) | content | article | mixed | editor-review | free | general | en,global | 刊物策略各异 | 2025-10-15 |
| [Substack Publications](https://substack.com/) | content | article | mixed | editor-review | free | general | en,global | 可投主编开设的刊物 | 2025-10-15 |
| [Dev.to（技术长文）](https://dev.to/) | content | article | mixed | open | free | dev | en,global | 与上方 dev 重合，写深些 | 2025-10-15 |
| [DZone](https://dzone.com/) | content | article | mixed | editor-review | free | dev | en,global | 企业级/专题栏目 | 2025-10-15 |
| [Hackernoon](https://hackernoon.com/) | content | article | mixed | editor-review | free | tech,startup | en,global | 编辑流程清晰 | 2025-10-15 |
| [Smashing Magazine（设计/前端）](https://www.smashingmagazine.com/write-for-us/) | content | article | unknown | editor-review | paid (稿费) | design,dev | en,global | 高门槛，高质量 | 2025-10-15 |

### SEO Directory / 行业与通用目录
| name | category | accepts | backlink_policy | submission | fee | audience | region_lang | notes | last_checked |
|---|---|---|---|---|---|---|---|---|---|
| 行业协会/商会/高校实验室目录 | seo-directory | company,product | mixed | editor-review | free | general | local/global | 权威性强，选择相关性高的 | 2025-10-15 |
| GitHub Awesome 清单生态 | seo-directory | repo,library | unknown | editor-review | free | dev | en,global | 主题相关清单优先 | 2025-10-15 |
| Wiki/资源页（如公司合作伙伴页） | seo-directory | company | mixed | editor-review | free | general | global | 建立合作与案例上架 | 2025-10-15 |

### Local / 本地化与中文社区
| name | category | accepts | backlink_policy | submission | fee | audience | region_lang | notes | last_checked |
|---|---|---|---|---|---|---|---|---|---|
| [少数派](https://sspai.com/) | local | product,article | unknown | editor-review | free | general | zh | 质量高，编辑性强 | 2025-10-15 |
| [小众软件 Appinn](https://www.appinn.com/) | local | product,article | mixed | editor-review | free | general | zh | 工具类曝光好 | 2025-10-15 |
| [掘金](https://juejin.cn/) | local | article,case | mixed | open | free | dev | zh | 技术受众，避免硬广 | 2025-10-15 |
| [知乎专栏](https://www.zhihu.com/) | local | article,case | mixed | open | free | general | zh | 选垂直话题做长文 | 2025-10-15 |
| [V2EX](https://www.v2ex.com/) | local | article,case | mixed | editor-review | free | dev,indie | zh | 严格遵版规 | 2025-10-15 |
| [少数派「Matrix/App+」](https://sspai.com/matrix) | local | product,article | unknown | editor-review | free | general | zh | 专栏/专题更稳 | 2025-10-15 |
| 本地创业社群/园区/路演 | local | product,company | mixed | editor-review | free | startup | zh/local | 线下线上结合 | 2025-10-15 |

> 注：以上为 **MVP 启动样例**，`backlink_policy` 多为 `unknown/mixed`。投稿后欢迎回填策略与示例链接。

---

## 投稿路线建议（按产品类型）
> 先垂直，再扩散。每条路线选 **3–5 个**切入点，保证“好内容 + 好落地页”。

### 1) Dev 工具 / 开源库
1. **Show HN / DEV / Hashnode**：技术长文 + Demo/GIF  
2. **GitHub Topics / Awesome 清单**：补充使用文档、Benchmarks  
3. **Lobsters（择优）**：聚焦技术难点/实现细节  
4. **Medium/Hackernoon（客座）**：问题背景 + 方案对比 + 迁移指南  

### 2) AI SaaS / 模型应用
1. **Product Hunt / BetaList**：发布页完整素材 + 早期用户证言  
2. **AI 工具目录（精选两三家）**：避免广撒低质站  
3. **Hugging Face Spaces**：开个可交互 Demo  
4. **专题长文（Dev.to/Medium）**：用案例讲清场景与效果  

### 3) 设计资源 / 插件模板
1. **Figma Community / Uplabs**：投放可复用资产  
2. **Dribbble/Behance**：展示过程与下载链接  
3. **Smashing（高门槛）/Design 博客**：方法论/指南稿件  

### 4) 通用 App / 独立产品
1. **PH / Launch Directories**：打磨首日峰值  
2. **Indie Hackers**：连载式复盘  
3. **本地媒体与社区（中文）**：少数派/Appinn/知乎长文

---

## 贡献方式（MVP 简化流程）
- **新增来源**：在对应分类表**新增一行**；未知项用 `unknown`  
- **修改信息**：直接编辑该行；若争议可开 Issue  
- **PR 规范**：  
  - 标题：`add(category): Platform Name` 或 `fix: Platform Name policy -> mixed`  
  - 说明：简单写明来源、门槛、是否亲测  

**新增行模板（复制到相应分类表并替换占位）**  
<!--
| [Platform Name](https://...) | category | product,article | unknown | open | free | dev/indie/... | en/zh/... | 简要门槛与注意 | 2025-10-15 |
-->

---

## 路线图
- ✅ **MVP**：仅 README 表格维护数据，接受 PR  
- ⏭️ v1：为每条目补充「示例链接/证据」列  
- ⏭️ v2：在 README 顶部提供「最近 10 次更新」区块  
- ⏭️ v3：可选引入 JSON 数据与校验脚本（仍保留 README 展示）

---

## 许可证
- 代码与文档：MIT  
- 数据集：CC BY 4.0（署名即可）

## 致谢
感谢所有贡献者对独立开发者生态的支持！如果这个清单对你有帮助，请点个 ⭐️。
