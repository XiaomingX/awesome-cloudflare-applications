# Awesome Cloudflare (2026 Updated)

⛅️ 精选的 Cloudflare 工具、开源项目、指南、博客和其他资源列表。

## 🌍 基础设施与全球网络 (Infrastructure & Global Network)

Cloudflare 的基础设施建立在庞大的全球网络之上，利用 **Anycast** 技术将算力和数据带到离用户最近的地方。

*   **全球触达**: 覆盖 **125+ 国家** 的 **330+ 城市**，95% 的互联网人口在 50ms 延迟圈内。
*   **边缘计算**: 随着 AI 和 IoT 的爆发，**Workers AI** 将 GPU 推理能力部署到了网络边缘。
*   **后量子安全**: Cloudflare 已在全局部署 **后量子加密** 标准，为未来的计算安全保驾护航。

## � 热门原型与实验 (Trending Prototypes)

这些项目展示了 Cloudflare 平台的极限潜力，经常在社交媒体上引发热议。

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [Llama-3-Workers-AI](https://github.com/cloudflare/workers-ai) | **Viral Demo**。展示了 Llama 3 在 Workers AI 上的极速推理，零冷启动。 |  | 热门 |
| [Multiplayer Doom](https://github.com/cloudflare/doom-workers) | **黑科技**。将 Doom 移植到 WebAssembly 并运行在 Workers 上，使用 Durable Objects 实现多人联机。 |  | 实验 |
| [Wildebeest](https://github.com/cloudflare/wildebeest) | 在 Workers 上运行的 ActivityPub 和 Mastodon 兼容服务器，去中心化社交的典范。 |  | 维护中 |
| [Chat-with-PDF](https://github.com/langchain-ai/langchainjs/tree/main/examples/src/use_cases/chat_with_pdf) | **RAG 范例**。使用 Vectorize 向量数据库和 Workers AI 实现的“与数据对话”应用。 |  | 热门 |

## 🎮 游戏与实时应用 (Games & Real-Time)

利用 Durable Objects 和 WebSockets 构建低延迟、有状态的实时应用。

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [Planning Poker](https://github.com/briangershon/planning-poker) | 开源的敏捷开发估算工具，使用 Durable Objects 保持状态同步。 |  | 维护中 |
| [edge-yacht](https://github.com/jsuper/edge-yacht) | 基于 Workers 的多人骰子游戏，展示了轻量级游戏后端的可能性。 |  | 维护中 |
| [Durable World](https://github.com/cloudflare/durable-world) | **官方示例**。一个 3D 多人虚拟世界，展示了边缘状态管理的强大。 |  | 官方 |

## �🖼️ 图床与媒体处理

> **注意**：Telegraph 近期加强了上传限制，基于 Telegraph 的图床可能不稳定。推荐首选基于 Cloudflare R2 的解决方案。

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |

| [roim-picx](https://github.com/roimdev/roim-picx) | **推荐**。基于 Cloudflare Pages 和 **R2** 实现的图床，数据掌握在自己手中，更加稳定安全。 |  | 维护中 |
| [img-mom](https://github.com/beilunyang/img-mom) | 基于 Workers，支持多种后端（R2/B2/Telegram），部署灵活。 |  | 维护中 |
| [cloudflare-worker-image](https://github.com/ccbikai/cloudflare-worker-image) | 图片处理工具，依赖 Photon，支持缩放、剪裁、水印、滤镜，适合作为图片服务中间件。 |  | 维护中 |

## 📺 视频与流媒体 (Video & Streaming)

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [R2-video-streaming](https://github.com/wesbos/R2-video-streaming) | **教程代码**。Wes Bos 大神演示如何基于 R2 构建视频流服务，通过 Workers 控制访问权限。 |  | 热门 |
| [utube](https://github.com/arapurayil/utube) | YouTube 直播流代理工具，支持获取 M3U8 链接。 |  | 维护中 |
| [Cloudflare-Stream-Upload](https://github.com/Schachte/Cloudflare-Stream-Video-Upload) | 实现 Tus 协议的大文件断点续传，上传视频到 Cloudflare Stream。 |  | 维护中 |


## 🤖 AI & LLM (新热门)

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [ChatGPT-Telegram-Workers](https://github.com/TBXark/ChatGPT-Telegram-Workers) | 在 Workers 上部署 Telegram ChatGPT 机器人，轻量且免费额度足够个人使用。 |  | 维护中 |
| [Gemini-Telegram-Bot](https://www.google.com/search?q=https://github.com/zklcdc/Gemini-Telegram-Bot) | 专为 Google Gemini Pro 设计的 Telegram 机器人，部署在 Workers 上。 |  | 维护中 |
| [AI-Gateway](https://developers.cloudflare.com/ai-gateway/) | Cloudflare 官方推出的 AI 网关，用于缓存、速率限制和监控 OpenAI/Anthropic 等 API 请求。 |  | 官方 |

| [Workers AI](https://developers.cloudflare.com/workers-ai/) | **官方**。无服务器 GPU 推理平台，支持 Llama 3 等主流开源模型，让 AI 跑在边缘。 |  | 官方 |
| [Model Context Protocol](https://www.anthropic.com/news/model-context-protocol) | **新标准**。Cloudflare 大力支持的 AI 代理连接标准 (MCP)，连接 AI 与数据的桥梁。 |  | 热门 |
| [Supermemory](https://github.com/supermemoryai/supermemory) | **新颖**。基于 Cloudflare 构建的 AI 第二大脑，专注于速度和隐私的数据管理。 |  | 维护中 |
| [Clawdbot](https://github.com/clawdbot/clawdbot) | 基于 Claude 的开源 AI Agent，展示了边缘 AI 的强大潜力。 |  | 维护中 |
| [AI-Agent-Scaffold](https://github.com/cloudflare/agents-sdk) | **新热门**。用于构建在边缘运行的自主 AI 代理的框架。 |  | 官方 |
| [grammY](https://github.com/grammyjs/grammY) | **推荐**。现代、类型安全的 Telegram 机器人框架，原生支持 Workers。 |  | 热门 |
| [Firewall for AI](https://blog.cloudflare.com/firewall-for-ai/) | 专为 LLM 设计的安全层，防止模型被攻击或滥用。 |  | 官方 |

## 📊 网站分析

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [Cloudflare Web Analytics](https://www.cloudflare.com/zh-cn/web-analytics/) | 官方推出的隐私优先、免费的 Web 分析工具，无需改动代码即可在 CF 仪表盘开启（针对代理的域名）。 |  | 官方 |
| [counterscale](https://github.com/benvinegar/counterscale) | **推荐**。基于 Cloudflare Workers + D1 的分析工具，类似 Umami，成本几乎为零。 |  | 维护中 |
| [analytics_with_cloudflare](https://github.com/yestool/analytics_with_cloudflare) | 类似“不蒜子”的访客计数器，基于 D1 数据库。 |  | 维护中 |

## 📧 邮箱服务

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [Email Routing](https://developers.cloudflare.com/email-routing/) | 官方免费功能，创建自定义域名邮箱地址并转发到你的个人邮箱（如 Gmail）。 |  | 官方 |
| [vmail](https://github.com/oiov/vmail) | 开源临时邮箱工具，支持收发邮件，界面简洁。 |  | 维护中 |
| [cloudflare_temp_email](https://github.com/dreamhunter2333/cloudflare_temp_email) | 功能强大的临时邮箱，D1 作为数据库，支持多语言、自动回复、附件查看。 |  | 维护中 |


## 📝 博客, CMS & 建站

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [Hugo/Hexo + Pages](https://pages.cloudflare.com/) | **最佳实践**。使用静态网站生成器（Hugo/Hexo/VitePress）构建博客，并托管在 Cloudflare Pages，速度极快且完全免费。 |  | 官方 |
| [microfeed](https://github.com/microfeed/microfeed) | 在 Cloudflare 上自托管的内容管理系统 (CMS)，适合发布播客、博客等。 |  | 维护中 |

| [Webstudio](https://webstudio.is/) | **新颖**。开源的视觉化建站工具 (Webflow 替代品)，支持一键部署到 Cloudflare。 |  | 维护中 |
| [SonicJs](https://github.com/viclafouch/sonicjs) | 基于 Workers 的 Headless CMS，极致性能。 |  | 维护中 |

## � 电商与 SaaS (E-commerce & SaaS)

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [Next.js SaaS Template](https://github.com/supasub-app/nextjs-saas-starter) | **生产级**。包含 Auth、Stripe 支付、邮件等功能的完整 SaaS 启动模版，适配 Workers。 |  | 热门 |
| [E-commerce Bundles](https://github.com/cloudflare/e-commerce-bundles-workers-example) | **官方示例**。构建类似 AppSumo 的软件捆绑销售平台，集成 Stripe。 |  | 官方 |

## �🔗 短链与导航

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [Sink](https://github.com/ccbikai/Sink) | **推荐**。功能完整，带控制台面板、统计分析，完全运行在 Cloudflare 上。 |  | 维护中 |

| [sublink-worker](https://github.com/7Sageer/sublink-worker) | 代理节点订阅转换工具，科学上网用户的刚需工具。 |  | 维护中 |

## 📂 存储与文件管理 (R2/D1)

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [r2-explorer](https://github.com/G4brym/r2-explorer) | **推荐**。一个美观的 Cloudflare R2 存储桶文件浏览器，支持预览、上传、密码保护。 |  | 维护中 |
| [pastebin-worker](https://github.com/SharzyL/pastebin-worker) | 开源 Pastebin（代码/文本分享），支持密码和阅后即焚。 |  | 维护中 |
| [cf-files-sharing](https://github.com/joyance-professional/cf-files-sharing) | 支持密码保护的文件分享，集成 D1 和 R2。 |  | 维护中 |
| [pg_driver for D1](https://github.com/cloudflare/workers-sdk) | **新生态**。让标准 Postgres 驱动兼容 D1，解锁 Prisma/Drizzle 等 ORM 生态。 |  | 官方 |

## 🛡️ 安全与 Zero Trust (Security & Zero Trust)

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [NetBird](https://github.com/reclaimid/netbird) | **Zero Trust**。基于 WireGuard 的开源零信任网络平台，可作为 Cloudflare Tunnel 的自托管替代方案。 |  | 热门 |
| [Octelium](https://github.com/octelium/octelium) | 统一的零信任安全访问平台，简化内部服务的安全暴露。 |  | 维护中 |
| [Moltworker](https://github.com/molt/moltworker) | 用于 Cloudflare Zero Trust 的中间件，处理复杂的认证逻辑。 |  | 维护中 |

## 🚀 隧道、代理与加速

> **注意**：Docker 代理类工具在当前网络环境下非常实用。

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [cloudflare-docker-proxy](https://github.com/ciiiii/cloudflare-docker-proxy) | **必备**。解决国内无法拉取 Docker 镜像的问题，支持多个镜像源代理。 |  | 维护中 |
| [gh-proxy](https://github.com/hunshcn/gh-proxy) | GitHub Release、Archive 及项目文件加速下载。 |  | 维护中 |
| [Cloudflared-web](https://github.com/WisdomSky/Cloudflared-web) | 带 Web UI 的 Cloudflare Tunnel 管理工具，方便内网穿透。 |  | 维护中 |
| [deeplx-for-cloudflare](https://github.com/ifyour/deeplx-for-cloudflare) | 部署 DeepLX (DeepL 免费接口) 代理，解决本地 IP 被封控问题。 |  | 维护中 |

## 🛠️ 开发与脚手架

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [Hono](https://github.com/honojs/hono) | **核心框架**。目前开发 Cloudflare Workers 最流行的 Web 框架，轻量、超快，支持 TypeScript。 |  | 维护中 |
| [Remix](https://remix.run/) | **标准框架**。全栈 Web 框架，利用 Web Fetch API 在边缘原生运行。 |  | 维护中 |
| [itty-router](https://github.com/kwhitley/itty-router) | **极简**。专为 Workers 设计的零依赖微型路由。 |  | 维护中 |
| [react-starter-kit](https://github.com/kriasoft/react-starter-kit) | **模版**。集成 Vite、Hono 和 TanStack Router 的 React 边缘启动器。 |  | 维护中 |
| [nextflare](https://github.com/ccbikai/nextflare) | Next.js App Router 运行于 Cloudflare 的模版。 |  | 维护中 |
| [ip-api](https://github.com/ccbikai/ip-api) | 快速搭建显示访客 IP 和地理位置的 API。 |  | 维护中 |
| [Cap'n Web](https://blog.cloudflare.com/capn-web/) | **黑科技**。高性能 RPC 协议，为现代 Web 设计。 |  | 官方 |
| [OpenPubkey SSH](https://github.com/openpubkey/openpubkey) | 给 SSH 加上 SSO 单点登录，安全又方便。 |  | 维护中 |
| [Astro](https://astro.build/) | **新热门**。加入 Cloudflare 大家庭的现代 Web 框架，完美适配 Pages 和边缘缓存。 |  | 官方 |
| [PartyKit](https://github.com/partykit/partykit) | **实时协作**。专为构建多人实时应用设计的平台，基于 Durable Objects。 |  | 热门 |
| [Workerd](https://github.com/cloudflare/workerd) | **硬核**。Cloudflare Workers 的开源运行时，适合想要深入了解底层或自托管的开发者。 |  | 官方 |

## 📈 监控与测速

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [UptimeFlare](https://github.com/lyc8503/UptimeFlare) | **推荐**。基于 Workers 的无服务器站点监控工具，支持多地理位置检查，可替代 UptimeRobot。 |  | 维护中 |
| [CloudflareSpeedTest](https://github.com/XIU2/CloudflareSpeedTest) | 经典的本地测速工具，用于筛选访问速度最快的 CF IP 地址（优选 IP）。 |  | 维护中 |
| [DNS Propagation Checker](https://github.com/brancogao/dns-propagation-checker) | DNS 传播检查工具，支持 10+ 全球 DNS 服务器，可视化传播进度。 | [Demo](https://dns-propagation-checker.autocompany.workers.dev) | 维护中 |

## 📚 推荐阅读与教程

| 名称 | 描述 | 地址 |
| --- | --- | --- |
| [Cloudflare Developers](https://developers.cloudflare.com/) | 官方文档，这是最权威、更新最快的信息来源。 | 官方文档 |
| [Cloudflare Workers 优秀项目收集](https://igdux.com/workers) | 一个长期更新的精选项目博客文章。 | 博客 |
| [Prisma with Cloudflare D1](https://www.prisma.io/docs/orm/overview/databases/cloudflare-d1) | 官方教程：如何使用 Prisma ORM 操作 D1 数据库。 | 教程 |
| [Turnstile](https://www.cloudflare.com/zh-cn/products/turnstile/) | 彻底告别繁琐的图形验证码，Cloudflare 免费的 CAPTCHA 替代品。 | 产品 |

## 📚 深度参考 (Deep Dives)

为了更深入地了解 Cloudflare 生态系统，请参阅以下精简指南：

*   **[开发工具链 (Toolchains)](docs/toolchains.md)**: AI SDK、CLI 工具及核心平台组件。
*   **[网页框架与脚手架 (Frameworks)](docs/frameworks.md)**: Hono、Astro 及各类边缘原生启动模版。
*   **[基础设施详解 (Infrastructure)](docs/infrastructure.md)**: 全球网络架构、Anycast 路由及边缘计算规模。
*   **[热门项目展示 (Showcase)](docs/showcase.md)**: 社交媒体上的热门原型与实验性技术。
*   **[聊天机器人开发 (Chatbots)](docs/chatbots.md)**: Discord 与 Telegram 机器人的快速上手指南。
