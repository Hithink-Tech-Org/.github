<div align="center">

# 同花顺 · HiThink

**Financial intelligence. Built for people and agents.**

金融 AI · 智能研究 · 开发者工具

[![Website](https://img.shields.io/badge/Website-HiThink-e53935?style=flat-square)](https://www.10jqka.com.cn/)
[![AI Workspace](https://img.shields.io/badge/AI-Workspace-7c3aed?style=flat-square)](https://lumi.10jqka.com.cn/?channel=Hithink-API)
[![Developer Docs](https://img.shields.io/badge/Developer-Docs-0969da?style=flat-square)](https://fuyao.aicubes.cn/docs/)
[![iFinD](https://img.shields.io/badge/Research-iFinD-0f766e?style=flat-square)](https://ft.10jqka.com.cn/)

[探索项目](https://github.com/orgs/Hithink-Tech-Org/repositories) · [体验问财](https://www.iwencai.com/) · [同花顺 AI 客户端](https://lumi.10jqka.com.cn/?channel=Hithink-API) · [English](#english)

</div>

---

**这里是同花顺官方 GitHub 组织。** 我们构建金融大模型、智能研究产品与开发者工具，让金融信息、专业分析和 AI 协同工作，服务个人投资者、研究人员、开发者与金融机构。

我们希望把一个研究问题，变成可以查询、分析、验证和持续跟踪的工作流。

## What we build · 我们在构建什么

| 方向 | 产品与技术 | 核心能力 |
| --- | --- | --- |
| **Financial AI** | **HithinkGPT · [问财](https://www.iwencai.com/)** | 将金融语义理解与大模型能力结合，支持自然语言选股、数据查询、公告解读与市场研究。 |
| **Agent Workspace** | **[同花顺 AI 客户端](https://lumi.10jqka.com.cn/?channel=Hithink-API)** | 内置金融数据与分析工具，支持盘中跟踪、盘后复盘、报告生成、自动任务与个性化工作台。 |
| **Institutional Research** | **[iFinD](https://ft.10jqka.com.cn/) · iFinD MCP** | 将市场信息、公司与行业研究、智能检索和辅助写作融入机构投研流程，并将投研数据接入机构自己的 AI 环境。 |
| **Developer Tooling** | **[Financial-API](https://github.com/Hithink-Tech-Org/Financial-API)** | 提供 API、MCP、CLI、Python SDK、Agent Skills 与本地 DuckDB 工具，支持开发者组合数据、分析脚本和自动化流程。 |

## Built for financial workflows · 为真实金融任务而构建

### 围绕金融问题组织能力

财务研究需要报告期与指标口径，走势分析需要交易日历与复权处理，盘面跟踪需要理解竞价、涨停、连板与异动。我们将这些具体场景融入数据服务和研究工具，让技术围绕金融问题组织。

### 从对话到可执行的研究流程

在产品中用自然语言发起研究，在 AI 客户端中安排盯盘与复盘任务，也可以通过 CLI、Python、领域 Skills 与本地 SQL，把自己的研究方法组织成可重复执行的脚本和工作流。

### 让研究过程有据可查

我们重视数据来源、时间窗口、复权方式与财务报告期，也重视查询结果、计算过程与分析结论之间的对应关系。公开项目提供接口契约、使用示例与版本记录，帮助开发者检查输入、复现流程并维护自己的集成。

## Open development · 从这里开始构建

### [Financial-API](https://github.com/Hithink-Tech-Org/Financial-API)

同花顺官方金融数据与研究工具项目，面向 AI Agent、量化研究者和应用开发者。

`REST API` · `MCP` · `CLI` · `Python SDK` · `Agent Skills` · `DuckDB`

以 A 股研究为核心，覆盖行情、财务、估值、指数与板块，并提供集合竞价、涨停连板、异动、热榜和龙虎榜等特色数据。通过远端查询、批量导出与本地数据库，把数据接入自己的 Agent、研究脚本或应用。

从终端开始：

```bash
npm install -g @hithink-tech/hithink-finance-cli
hithink-finance auth login --method oauth
hithink-finance capabilities --format json
```

[项目主页](https://github.com/Hithink-Tech-Org/Financial-API) · [接入文档](https://fuyao.aicubes.cn/docs/) · [CLI 与 Skills](https://github.com/Hithink-Tech-Org/Financial-API/blob/main/hithink-finance-cli/README.md) · [Python 与本地研究](https://github.com/Hithink-Tech-Org/Financial-API/blob/main/python/README.md) · [示例与灵感](https://github.com/Hithink-Tech-Org/Financial-API/tree/main/examples)

各产品的开放范围与授权方式以对应文档为准。

## Build with us · 一起构建

欢迎围绕真实使用场景参与：

- **报告问题**：在对应项目的 Issues 中提供使用环境、复现步骤与预期结果。
- **改进工具**：通过 Pull Request 改进代码、文档、测试或示例。
- **分享实践**：展示你的 Agent 集成、研究脚本、可视化应用与工作流。

[浏览公开仓库](https://github.com/orgs/Hithink-Tech-Org/repositories) · [Financial-API Issues](https://github.com/Hithink-Tech-Org/Financial-API/issues)

## About HiThink · 关于同花顺

浙江核新同花顺网络信息股份有限公司（**SZSE: 300033**）总部位于杭州，面向个人投资者提供金融信息与投资分析工具，面向证券公司、基金公司、银行及研究机构提供金融数据、专业投研终端和软件系统。

同花顺在中国香港、新加坡和美国设有业务实体，并通过金融数据与研究产品服务跨市场研究需求。

[同花顺官网](https://www.10jqka.com.cn/) · [产品中心](https://download.10jqka.com.cn/) · [国际业务介绍](https://www.investhk.gov.hk/en/our-clients/royalflush-digital-intelligence-hongkong-limited/)

## English

**HiThink builds financial AI, research applications and developer tools.**

Headquartered in Hangzhou and listed on the Shenzhen Stock Exchange (**300033**), we serve individual investors, developers and financial institutions, with an international presence that includes Hong Kong, Singapore and the United States.

Our products span **HithinkGPT and Wencai** for financial language understanding and research, the **HiThink AI client** for analysis and automated workflows, and **iFinD** for institutional research.

For developers, **Financial-API** brings HiThink financial data into agents, scripts and applications through REST API, MCP, CLI, Python SDK, Agent Skills and local DuckDB tooling.

This organization hosts our public developer projects, tools, documentation and examples. Explore the repositories, build an integration, or contribute an improvement.

[Explore repositories](https://github.com/orgs/Hithink-Tech-Org/repositories) · [Developer docs](https://fuyao.aicubes.cn/docs/) · [Try the AI client](https://lumi.10jqka.com.cn/?channel=Hithink-API)
