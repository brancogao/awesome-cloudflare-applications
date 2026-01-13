# Awesome Cloudflare (2025 Updated)

⛅️ 精选的 Cloudflare 工具、开源项目、指南、博客和其他资源列表。

## 🖼️ 图床与媒体处理

> **注意**：Telegraph 近期加强了上传限制，基于 Telegraph 的图床可能不稳定。推荐首选基于 Cloudflare R2 的解决方案。

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [Telegraph-Image](https://github.com/cf-pages/Telegraph-Image) | 经典的免费图片托管解决方案。目前最流行的版本之一，支持后台管理。 |  | 维护中 |
| [roim-picx](https://github.com/roimdev/roim-picx) | **推荐**。基于 Cloudflare Pages 和 **R2** 实现的图床，数据掌握在自己手中，更加稳定安全。 |  | 维护中 |
| [img-mom](https://github.com/beilunyang/img-mom) | 基于 Workers，支持多种后端（R2/B2/Telegram），部署灵活。 |  | 维护中 |
| [cloudflare-worker-image](https://github.com/ccbikai/cloudflare-worker-image) | 图片处理工具，依赖 Photon，支持缩放、剪裁、水印、滤镜，适合作为图片服务中间件。 |  | 维护中 |
| [tgState](https://github.com/csznet/tgState) | 依然可用的 Telegram 文件外链系统，不限制文件大小和格式。 |  | 维护中 |

## 🤖 AI & LLM (新热门)

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [ChatGPT-Telegram-Workers](https://github.com/TBXark/ChatGPT-Telegram-Workers) | 在 Workers 上部署 Telegram ChatGPT 机器人，轻量且免费额度足够个人使用。 |  | 维护中 |
| [Gemini-Telegram-Bot](https://www.google.com/search?q=https://github.com/zklcdc/Gemini-Telegram-Bot) | 专为 Google Gemini Pro 设计的 Telegram 机器人，部署在 Workers 上。 |  | 维护中 |
| [AI-Gateway](https://developers.cloudflare.com/ai-gateway/) | Cloudflare 官方推出的 AI 网关，用于缓存、速率限制和监控 OpenAI/Anthropic 等 API 请求。 |  | 官方 |
| [worker-llm-proxy](https://www.google.com/search?q=https://github.com/ConnectAI-E/worker-llm-proxy) | 通用的 LLM 代理，支持将 OpenAI 格式请求转发到 Azure、Gemini 等。 |  | 维护中 |

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
| [mail2telegram](https://github.com/TBXark/mail2telegram) | 将收到的邮件转换为 Telegram 消息推送，适合个人通知流。 |  | 维护中 |

## 📝 博客与 CMS

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [Hugo/Hexo + Pages](https://pages.cloudflare.com/) | **最佳实践**。使用静态网站生成器（Hugo/Hexo/VitePress）构建博客，并托管在 Cloudflare Pages，速度极快且完全免费。 |  | 官方 |
| [microfeed](https://github.com/microfeed/microfeed) | 在 Cloudflare 上自托管的内容管理系统 (CMS)，适合发布播客、博客等。 |  | 维护中 |
| [serverless-cloud-notepad](https://github.com/s0urcelab/serverless-cloud-notepad) | 简易的云笔记/剪贴板工具。 |  | 维护中 |

## 🔗 短链与导航

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [Sink](https://github.com/ccbikai/Sink) | **推荐**。功能完整，带控制台面板、统计分析，完全运行在 Cloudflare 上。 |  | 维护中 |
| [short](https://github.com/x-dr/short) | 经典的短链工具，部署简单，功能够用。 |  | 维护中 |
| [sublink-worker](https://github.com/7Sageer/sublink-worker) | 代理节点订阅转换工具，科学上网用户的刚需工具。 |  | 维护中 |

## 📂 存储与文件管理 (R2/D1)

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [r2-explorer](https://www.google.com/search?q=https://github.com/G4brym/r2-explorer) | **推荐**。一个美观的 Cloudflare R2 存储桶文件浏览器，支持预览、上传、密码保护。 |  | 维护中 |
| [pastebin-worker](https://github.com/SharzyL/pastebin-worker) | 开源 Pastebin（代码/文本分享），支持密码和阅后即焚。 |  | 维护中 |
| [cf-files-sharing](https://github.com/joyance-professional/cf-files-sharing) | 支持密码保护的文件分享，集成 D1 和 R2。 |  | 维护中 |

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
| [nextflare](https://github.com/ccbikai/nextflare) | Next.js App Router 运行于 Cloudflare 的模版。 |  | 维护中 |
| [ip-api](https://github.com/ccbikai/ip-api) | 快速搭建显示访客 IP 和地理位置的 API。 |  | 维护中 |

## 📈 监控与测速

| 名称 | 特性 | 在线地址 | 状态 |
| --- | --- | --- | --- |
| [UptimeFlare](https://github.com/lyc8503/UptimeFlare) | **推荐**。基于 Workers 的无服务器站点监控工具，支持多地理位置检查，可替代 UptimeRobot。 |  | 维护中 |
| [CloudflareSpeedTest](https://github.com/XIU2/CloudflareSpeedTest) | 经典的本地测速工具，用于筛选访问速度最快的 CF IP 地址（优选 IP）。 |  | 维护中 |

## 📚 推荐阅读与教程

| 名称 | 描述 | 地址 |
| --- | --- | --- |
| [Cloudflare Developers](https://developers.cloudflare.com/) | 官方文档，这是最权威、更新最快的信息来源。 | 官方文档 |
| [Cloudflare Workers 优秀项目收集](https://igdux.com/workers) | 一个长期更新的精选项目博客文章。 | 博客 |
| [Prisma with Cloudflare D1](https://www.prisma.io/docs/orm/overview/databases/cloudflare-d1) | 官方教程：如何使用 Prisma ORM 操作 D1 数据库。 | 教程 |
| [Turnstile](https://www.cloudflare.com/zh-cn/products/turnstile/) | 彻底告别繁琐的图形验证码，Cloudflare 免费的 CAPTCHA 替代品。 | 产品 |
