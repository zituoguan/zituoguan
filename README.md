# 自托管精选

[![Awesome](_static/awesome.png)](https://github.com/sindresorhus/awesome) [![](https://github.com/awesome-selfhosted/awesome-selfhosted-data/actions/workflows/check-dead-links.yml/badge.svg)](https://github.com/awesome-selfhosted/awesome-selfhosted-data/issues/1) [![](https://github.com/awesome-selfhosted/awesome-selfhosted-data/actions/workflows/check-unmaintained-projects.yml/badge.svg)](https://github.com/awesome-selfhosted/awesome-selfhosted-data/issues/1) [![](https://img.shields.io/liberapay/goal/awesome-selfhosted?logo=liberapay)](https://liberapay.com/awesome-selfhosted/)

自托管是在自己的服务器上托管和管理应用程序，而不是依赖于 [SaaSS](https://www.gnu.org/philosophy/who-does-that-server-really-serve.html) 提供商。

这是一个列出了可以在您自己的服务器上托管的[自由](https://en.wikipedia.org/wiki/Free_software)软件 [网络服务](https://en.wikipedia.org/wiki/Network_service) 和 [Web 应用](https://en.wikipedia.org/wiki/Web_application)的清单。非自由软件列在 [Non-Free](https://github.com/zituoguan/zituoguan/blob/main/non-free.md) 页面。

**[HTML 版本](https://zituoguan.com/)（推荐）**，[Markdown 版本](https://github.com/zituoguan/zituoguan)（旧版）。

> 📢 本站稳定运行两年半，Google 收录良好，被各类 AI 爬虫频繁抓取——加入列表能为你的开源项目带来持续曝光。欢迎参考 [贡献指南](https://welinux.com/topic/9) 提交。

> 📌 遇到问题上 [问答](https://dakewen.com)，想聊技术来 [社区](https://welinux.com)。网站初建，欢迎注册加入。
--------------------

## 目录

  - [ChatOps](#chatops)
  - [DNS](#dns)
  - [DNS - 控制面板与域名管理](#dns---控制面板与域名管理)
  - [DNS - 服务器](#dns---服务器)
  - [IT 资产管理](#it-资产管理)
  - [PaaS](#paas)
  - [URL 缩短服务](#url-缩短服务)
  - [Web 服务器](#web-服务器)
  - [个人仪表板](#个人仪表板)
  - [书签和链接分享](#书签和链接分享)
  - [人力资源管理（HRM）](#人力资源管理（hrm）)
  - [代理](#代理)
  - [任务管理和待办清单](#任务管理和待办清单)
  - [会议管理](#会议管理)
  - [健康和健身](#健康和健身)
  - [内容管理系统（CMS）](#内容管理系统（cms）)
  - [分布式文件系统](#分布式文件系统)
  - [分析](#分析)
  - [制造业](#制造业)
  - [办公套件](#办公套件)
  - [协同办公](#协同办公)
  - [博客平台](#博客平台)
  - [地图和全球定位系统（GPS）](#地图和全球定位系统（gps）)
  - [备份](#备份)
  - [备份](#备份)
  - [媒体管理](#媒体管理)
  - [学习和课程](#学习和课程)
  - [客户关系管理（CRM）](#客户关系管理（crm）)
  - [家谱研究](#家谱研究)
  - [密码管理器](#密码管理器)
  - [工单](#工单)
  - [库存管理](#库存管理)
  - [打包](#打包)
  - [投票和事件](#投票和事件)
  - [持续集成和持续部署](#持续集成和持续部署)
  - [指标和指标采集](#指标和指标采集)
  - [控制面板](#控制面板)
  - [搜索引擎](#搜索引擎)
  - [故障排查](#故障排查)
  - [数据库管理](#数据库管理)
  - [文件传输 - 分布式文件系统](#文件传输---分布式文件系统)
  - [文件传输 - 单击和拖放上传](#文件传输---单击和拖放上传)
  - [文件传输 - 基于 Web 的文件管理器](#文件传输---基于-web-的文件管理器)
  - [文件传输 - 对象存储和文件服务器](#文件传输---对象存储和文件服务器)
  - [文件传输 - 点对点文件共享](#文件传输---点对点文件共享)
  - [文件传输和同步](#文件传输和同步)
  - [文档管理](#文档管理)
  - [文档管理 - 图书馆自动化系统（ILS）](#文档管理---图书馆自动化系统（ils）)
  - [文档管理 - 机构知识库和数字图书馆软件](#文档管理---机构知识库和数字图书馆软件)
  - [文档管理 - 电子书](#文档管理---电子书)
  - [日历和联系人](#日历和联系人)
  - [日志管理](#日志管理)
  - [时间服务器](#时间服务器)
  - [时间追踪](#时间追踪)
  - [服务发现](#服务发现)
  - [杂项](#杂项)
  - [构建和软件组织工具](#构建和软件组织工具)
  - [档案和数字保存（DP）](#档案和数字保存（dp）)
  - [流媒体](#流媒体)
  - [流媒体 - 多媒体流媒体](#流媒体---多媒体流媒体)
  - [流媒体 - 视频流媒体](#流媒体---视频流媒体)
  - [流媒体 - 音频流媒体](#流媒体---音频流媒体)
  - [游戏](#游戏)
  - [游戏 - 管理工具和控制面板](#游戏---管理工具和控制面板)
  - [版本控制](#版本控制)
  - [物联网（IoT）](#物联网（iot）)
  - [生成式人工智能（GenAI）](#生成式人工智能（genai）)
  - [电子商务](#电子商务)
  - [监控和状态页面](#监控和状态页面)
  - [相册](#相册)
  - [知识管理工具](#知识管理工具)
  - [社区支持农业（CSA）](#社区支持农业（csa）)
  - [笔记和编辑器](#笔记和编辑器)
  - [粘贴板](#粘贴板)
  - [绘图](#绘图)
  - [维基](#维基)
  - [编辑器](#编辑器)
  - [网络工具](#网络工具)
  - [网络配置管理](#网络配置管理)
  - [联邦身份和认证](#联邦身份和认证)
  - [自动化](#自动化)
  - [自托管解决方案](#自托管解决方案)
  - [虚拟专用网络（VPN）](#虚拟专用网络（vpn）)
  - [虚拟化](#虚拟化)
  - [视频监控](#视频监控)
  - [订阅阅读器](#订阅阅读器)
  - [资源规划](#资源规划)
  - [资金、预算和管理](#资金、预算和管理)
  - [路由器](#路由器)
  - [身份管理 - LDAP](#身份管理---ldap)
  - [身份管理 - 单点登录（SSO）](#身份管理---单点登录（sso）)
  - [身份管理 - 工具和 Web 界面](#身份管理---工具和-web-界面)
  - [软件容器](#软件容器)
  - [软件开发](#软件开发)
  - [软件开发 - API 管理](#软件开发---api-管理)
  - [软件开发 - FaaS 和无服务器](#软件开发---faas-和无服务器)
  - [软件开发 - IDE 和工具](#软件开发---ide-和工具)
  - [软件开发 - 低代码](#软件开发---低代码)
  - [软件开发 - 功能开关](#软件开发---功能开关)
  - [软件开发 - 持续集成和部署](#软件开发---持续集成和部署)
  - [软件开发 - 本地化](#软件开发---本地化)
  - [软件开发 - 测试](#软件开发---测试)
  - [软件开发 - 项目管理](#软件开发---项目管理)
  - [远程桌面客户端](#远程桌面客户端)
  - [远程访问](#远程访问)
  - [通信 - IRC](#通信---irc)
  - [通信 - SIP](#通信---sip)
  - [通信 - XMPP - Web 客户端](#通信---xmpp---web-客户端)
  - [通信 - XMPP - 服务器](#通信---xmpp---服务器)
  - [通信 - 定制通信系统](#通信---定制通信系统)
  - [通信 - 电子邮件 - Web 邮件客户端](#通信---电子邮件---web-邮件客户端)
  - [通信 - 电子邮件 - 完整解决方案](#通信---电子邮件---完整解决方案)
  - [通信 - 电子邮件 - 邮件传输代理](#通信---电子邮件---邮件传输代理)
  - [通信 - 电子邮件 - 邮件列表和通讯](#通信---电子邮件---邮件列表和通讯)
  - [通信 - 电子邮件 - 邮件投递代理](#通信---电子邮件---邮件投递代理)
  - [通信 - 社交网络和论坛](#通信---社交网络和论坛)
  - [通信 - 视频会议](#通信---视频会议)
  - [邮件客户端](#邮件客户端)
  - [部署自动化](#部署自动化)
  - [配置管理](#配置管理)
  - [配置管理数据库](#配置管理数据库)
  - [队列](#队列)
  - [静态网站生成器](#静态网站生成器)
  - [预订和日程安排](#预订和日程安排)
  - [食谱管理](#食谱管理)
- [List of Licenses](#list-of-licenses)
- [反特性](#反特性)
- [外部链接](#外部链接)
- [贡献](#贡献)
- [许可证](#许可证)

--------------------

## 软件

### ChatOps

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

对话驱动的开发与管理。

- [Eggdrop](https://www.eggheads.org/) - 最早的 IRC 机器人，仍在积极开发中。 ([源代码](https://github.com/eggheads/eggdrop)) `GPL-2.0` `C`
- [Errbot](https://errbot.io/) - 基于插件的聊天机器人，易于部署、扩展和维护。 ([源代码](https://github.com/errbotio/errbot)) `GPL-3.0` `Python`
- [Hubot](https://hubot.github.com/) - 可定制的自动化机器人。 ([源代码](https://github.com/hubotio/hubot)) `MIT` `Node.js`


### DNS

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[DNS](https://en.wikipedia.org/wiki/Domain_Name_System)服务器和带有广告屏蔽功能的管理工具，主要针对家庭或小型网络。

_另见: [awesome-sysadmin/DNS - 服务器](https://github.com/awesome-foss/awesome-sysadmin#dns---servers), [awesome-sysadmin/DNS - 控制面板和域名管理](https://github.com/awesome-foss/awesome-sysadmin#dns---control-panels--domain-management)_

- [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) - 用户友好的广告和跟踪器拦截 DNS 服务器。 ([源代码](https://github.com/AdguardTeam/AdGuardHome)) `GPL-3.0` `Docker`
- [blocky](https://0xerr0r.github.io/blocky/latest/) - 快速轻量的 DNS 代理，作为本地网络广告拦截器，具备多种功能（Pi-hole 的替代方案）。 ([源代码](https://github.com/0xERR0R/blocky)) `Apache-2.0` `Go/Docker`
- [Maza ad blocking](https://maza-ad-blocking.andros.dev/) - 本地广告拦截器。类似于Pi-hole，但是在本地运行并使用您的操作系统。 ([源代码](https://github.com/tanrax/maza-ad-blocking)) `Apache-2.0` `Shell`
- [Pi-hole](https://pi-hole.net/) - 互联网广告黑洞，并提供用于管理和监控的图形界面。 ([源代码](https://github.com/pi-hole/pi-hole)) `EUPL-1.2` `Shell/PHP/Docker`
- [Technitium DNS Server](https://technitium.com/dns/) - 具有广告拦截功能的权威/递归 DNS 服务器。 ([源代码](https://github.com/TechnitiumSoftware/DnsServer)) `GPL-3.0` `Docker/C#`


### DNS - 控制面板与域名管理

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

DNS 服务器控制面板、Web 界面和域名管理工具。

- [Atomia DNS](https://github.com/atomia/atomiadns/) - DNS 管理系统。 `ISC` `Perl`
- [Designate](https://wiki.openstack.org/wiki/Designate) - OpenStack 的 DNSaaS 服务。 ([源代码](https://opendev.org/openstack/designate)) `Apache-2.0` `Python`
- [DNSControl](https://docs.dnscontrol.org/) - 使用简单 DSL 同步多个提供商的 DNS。 ([源代码](https://github.com/dnscontrol/dnscontrol)) `MIT` `Go/Docker`
- [DomainMOD](https://domainmod.org) - 在中心位置管理你的域名和其他互联网资产。 ([源代码](https://github.com/domainmod/domainmod)) `GPL-3.0` `PHP`
- [nsupdate.info](https://www.nsupdate.info/) - 动态 DNS 服务。 ([演示](https://www.nsupdate.info/account/register/), [源代码](https://github.com/nsupdate-info/nsupdate.info)) `BSD-3-Clause` `Python`
- [octoDNS](https://github.com/octodns/octodns) - DNS 即代码 - 管理多提供商 DNS 的工具。 `MIT` `Python`
- [Poweradmin](https://www.poweradmin.org/) - PowerDNS 服务器的 Web 控制面板。 ([源代码](https://github.com/poweradmin/poweradmin)) `GPL-3.0` `PHP`
- [SPF Toolbox](https://spftoolbox.com) - 用于查询 SPF、MX、Whois 等 DNS 记录的应用。 ([源代码](https://github.com/charlesabarnes/SPFtoolbox)) `MIT` `PHP`


### DNS - 服务器

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[DNS](https://en.wikipedia.org/wiki/Name_server) 服务器。

- [Bind](https://www.isc.org/bind/) - 多功能、经典、完整的名称服务器软件。 ([源代码](https://gitlab.isc.org/isc-projects/bind9)) `MPL-2.0` `C`
- [CoreDNS](https://coredns.io/) - 灵活的 DNS 服务器。 ([源代码](https://github.com/coredns/coredns)) `Apache-2.0` `Go`
- [djbdns](https://cr.yp.to/djbdns.html) - 一组 DNS 应用，包括 tinydns。 ([源代码](https://salsa.debian.org/debian/djbdns)) `CC0-1.0` `C`
- [dnsmasq](https://www.thekelleys.org.uk/dnsmasq/doc.html) - 为小型网络提供 DNS、DHCP、路由通告和网络引导等基础设施。 ([源代码](https://thekelleys.org.uk/gitweb/?p=dnsmasq.git;a=tree)) `GPL-2.0` `C`
- [Knot](https://www.knot-dns.cz/) - 高性能权威 DNS 服务器。 ([源代码](https://gitlab.nic.cz/knot/knot-dns)) `GPL-3.0` `C`
- [NSD](https://www.nlnetlabs.nl/projects/nsd/about/) - 以速度、可靠性、稳定性和安全性为目标开发的权威 DNS 名称服务器。 ([源代码](https://github.com/NLnetLabs/nsd)) `BSD-3-Clause` `C`
- [PowerDNS Authoritative Server](https://doc.powerdns.com/authoritative/) - 支持多种后端的多功能名称服务器。 ([源代码](https://github.com/PowerDNS/pdns)) `GPL-2.0` `C++`
- [Unbound](https://nlnetlabs.nl/projects/unbound/about/) - 支持验证、递归和缓存的 DNS 解析器。 ([源代码](https://github.com/NLnetLabs/unbound)) `BSD-3-Clause` `C`
- [Yadifa](https://www.yadifa.eu/) - 由 .eu 从零开发，简洁、小巧、轻量且符合 RFC 的名称服务器实现。 ([源代码](https://github.com/yadifa/yadifa)) `BSD-3-Clause` `C`


### IT 资产管理

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

IT [资产管理](https://en.wikipedia.org/wiki/Asset_management) 软件。

- [GLPI](https://www.glpi-project.org/) - 信息资源管理器，带有额外的管理界面。 ([源代码](https://github.com/glpi-project/glpi)) `GPL-3.0` `PHP`
- [OCS Inventory NG](https://ocsinventory-ng.org/) - 适用于 IT 部门所有设备的资产管理与部署解决方案。 ([源代码](https://github.com/OCSInventory-NG)) `GPL-2.0` `PHP/Perl`
- [openDCIM](https://opendcim.org/) - GPL v3 授权的数据中心资产管理（DCIM）工具。 ([演示](https://opendcim.org/demo.html), [源代码](https://github.com/opendcim/openDCIM)) `GPL-3.0` `PHP/JavaScript`
- [OPSI](https://www.opsi.org) - Linux 和 Windows 的硬件/软件清单、客户端管理、部署和补丁。 ([源代码](https://github.com/opsi-org/)) `GPL-3.0/AGPL-3.0` `OVF/Python`
- [RackTables](https://racktables.org/) - 数据中心和机房资产管理，如硬件资产、网络地址、机架空间、网络配置等文档化。 ([演示](https://www.racktables.org/demo.php), [源代码](https://github.com/RackTables/racktables)) `GPL-2.0` `PHP`
- [Ralph](https://github.com/allegro/ralph) - 适用于大型数据中心和小型局域网的资产管理、DCIM 和 CMDB 系统。 ([演示](https://github.com/allegro/ralph#live-demo)) `Apache-2.0` `Python/Docker`
- [Snipe IT](https://snipeitapp.com/) - 资产与许可证管理软件。 ([源代码](https://github.com/snipe/snipe-it)) `AGPL-3.0` `PHP`


### PaaS

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[平台即服务（PaaS）](https://en.wikipedia.org/wiki/Platform_as_a_service) 软件允许用户无需构建和维护底层基础设施即可部署、运行和管理计算平台及应用。也包括[无服务器计算](https://en.wikipedia.org/wiki/Serverless_computing)和[函数即服务（FaaS）](https://en.wikipedia.org/wiki/Function_as_a_service)软件。

- [CapRover](https://caprover.com/) - 几分钟内搭建自己的 PaaS。 ([演示](https://captain.server.demo.caprover.com/#/login), [源代码](https://github.com/caprover/caprover)) `Apache-2.0` `Docker/Node.js`
- [Coolify](https://coolify.io/) - 开源自托管 Heroku/Netlify 替代方案。 ([源代码](https://github.com/coollabsio/coolify)) `Apache-2.0` `Docker`
- [Dokku](https://dokku.com/) - 开源 PaaS（Heroku 替代）。 ([源代码](https://github.com/dokku/dokku)) `MIT` `Docker/Shell/Go/deb`
- [fx by metrue](https://github.com/metrue/fx) - 让你在自有服务器上轻松实现 FaaS 的工具。 `MIT` `Go`
- [Kubero](https://www.kubero.dev/) - 基于 Kubernetes 的自托管 Heroku PaaS 替代，支持 GitOps。 ([演示](https://demo.kubero.dev/), [源代码](https://github.com/kubero-dev/kubero)) `GPL-3.0` `K8S/Node.js/Go`
- [Nhost](https://nhost.io/) - GraphQL 的 Firebase 替代方案，几分钟内配置好数据库和后端。 ([源代码](https://github.com/nhost/nhost)) `MIT` `Docker/Node.js/Go`
- [OpenFaaS](https://www.openfaas.com/) - Docker 和 Kubernetes 的无服务器函数平台。 ([源代码](https://github.com/openfaas/faas)) `MIT` `Go`
- [Tau](https://taubyte.com) - 轻松构建云计算平台，支持无服务器 WebAssembly、前端托管、CI/CD、对象存储、K/V 数据库和消息队列。 ([源代码](https://github.com/taubyte/tau)) `BSD-3-Clause` `Go/Rust/Docker`
- [Trusted-CGI](https://github.com/reddec/trusted-cgi) - 轻量级自托管 lambda/应用/cgi/无服务器函数平台。 `MIT` `Go/deb/Docker`


### URL 缩短服务

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[URL 缩短](https://en.wikipedia.org/wiki/URL_shortening)是将 [URL](https://en.wikipedia.org/wiki/Uniform_Resource_Locator) 缩短以使其更短而仍然指向所需页面的操作。在托管之前，请查看 [URL 缩短服务的缺点](https://en.wikipedia.org/wiki/URL_shortening#Disadvantages)。

- [bit](https://github.com/sjdonado/bit) - 快速、轻量、资源高效、编译型的 URL 缩短器。 `MIT` `Docker/Crystal`
- [Chhoto URL](https://github.com/SinTan1729/chhoto-url) - 简单、极其快速且没有臃肿的 URL 缩短工具（simply-shorten 的分支）。 ([演示](https://github.com/SinTan1729/chhoto-url?tab=readme-ov-file#demo), [客户端](https://github.com/SinTan1729/chhoto-url/blob/main/TOOLS.md)) `MIT` `Rust/Docker`
- [clink](https://git.crueter.xyz/crueter/clink) - 一个超轻量的链接缩短服务，采用纯 C 语言编写，专注于小型可执行文件、可移植性和易配置性。 ([演示](https://short.crueter.xyz)) `AGPL-3.0` `C`
- [Flink](https://gitlab.com/rtraceio/web/flink) - 创建二维码、可嵌入的链接预览以及网站的元数据抓取/爬取。 ([演示](https://flink.is)) `MIT` `Docker`
- [Kutt](https://kutt.to) - 现代化短链接服务，支持自定义域名和自定义短链。 ([演示](https://kutt.to), [源代码](https://github.com/thedevs-network/kutt)) `MIT` `Node.js/Docker`
- [rs-short](https://git.42l.fr/42l/rs-short) - 用 Rust 编写的轻量级短链接服务，具备缓存、防垃圾机器人和钓鱼检测等功能。 ([演示](https://s.42l.fr/)) `MPL-2.0` `Rust`
- [Shlink](https://shlink.io) - 具有 REST API 和命令行界面的 URL 缩短服务。包括官方的渐进式 Web 应用和 Docker 镜像。 ([源代码](https://github.com/shlinkio/shlink), [客户端](https://shlink.io/apps)) `MIT` `PHP/Docker`
- [Simple-URL-Shortener](https://github.com/azlux/Simple-URL-Shortener) - KISS URL缩短服务，支持公共或私有（需要帐户）。简约轻便，无依赖。 ([演示](https://u.azlux.fr)) `MIT` `PHP`
- [YOURLS](https://yourls.org/) - YOURLS是一组PHP脚本，允许您运行自己的URL缩短服务。功能包括密码保护、URL自定义、书签工具、统计信息、API、插件、jsonp等。 ([源代码](https://github.com/YOURLS/YOURLS)) `MIT` `PHP`


### Web 服务器

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

Web 服务器和反向代理。[Web 服务器](https://en.wikipedia.org/wiki/Web_server) 是一款通过 [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)（用于分发网页内容的网络协议）或其安全变体 [HTTPS](https://en.wikipedia.org/wiki/HTTPS) 接受请求的软件及底层硬件。[反向代理](https://en.wikipedia.org/wiki/Reverse_proxy) 是一种代理服务器，对任何客户端而言看似普通的 Web 服务器，但实际上仅作为中介，将请求转发给一个或多个普通 Web 服务器。

_相关: [代理](#代理)_

- [Algernon](https://algernon.roboticoverlords.org/) - 小型自包含的纯 Go Web 服务器，支持 Lua、Markdown、HTTP/2、QUIC、Redis 和 PostgreSQL。 ([源代码](https://github.com/xyproto/algernon)) `BSD-3-Clause` `Go/Docker`
- [Apache HTTP Server](https://httpd.apache.org/) - 安全、高效且可扩展的服务器，提供与当前 HTTP 标准同步的 HTTP 服务。 ([源代码](https://svn.apache.org/repos/asf/httpd/httpd/trunk/)) `Apache-2.0` `C/deb/Docker`
- [BunkerWeb](https://www.bunkerweb.io) - 下一代 Web 应用防火墙 (WAF)，可保护您的 Web 服务。 ([演示](https://demo.bunkerweb.io), [源代码](https://github.com/bunkerity/bunkerweb), [客户端](https://docs.bunkerweb.io/latest/plugins/)) `AGPL-3.0` `deb/Docker/K8S/Python`
- [Caddy](https://caddyserver.com/) - 强大、企业级、开源的 Web 服务器，支持自动 HTTPS。 ([源代码](https://github.com/caddyserver/caddy)) `Apache-2.0` `Go/deb/Docker`
- [Ferron](https://ferron.sh/) - 用 Rust 编写的快速、内存安全的 Web 服务器。 ([源代码](https://github.com/ferronweb/ferron)) `MIT` `Rust/Docker/deb`
- [go-doxy](https://github.com/yusing/godoxy) - 轻量、简单且高性能的反向代理，带有 WebUI、Docker 集成，可根据流量自动关闭/启动容器。 `MIT` `Docker/Go`
- [godoxy](https://docs.godoxy.dev/) - 高性能反向代理和容器编排工具，适用于自托管用户。 ([演示](https://demo.godoxy.dev/), [源代码](https://github.com/yusing/godoxy)) `MIT` `Docker/Go`
- [HAProxy](https://www.haproxy.org/) - 非常快速且可靠的反向代理，提供高可用性、负载均衡以及 TCP 和 HTTP 基于应用程序的代理服务。 ([源代码](https://git.haproxy.org/?p=haproxy.git;a=tree)) `GPL-2.0` `C/deb/Docker`
- [Lighttpd](https://www.lighttpd.net/) - 安全、快速、符合规范且非常灵活的 web 服务器，经过优化，适用于高性能环境。 ([源代码](https://git.lighttpd.net/lighttpd/lighttpd1.4)) `BSD-3-Clause` `C/deb/Docker`
- [Nginx Proxy Manager](https://nginxproxymanager.com/) - 用于管理 Nginx 代理主机的 Docker 容器，具有简洁而强大的界面。 ([源代码](https://github.com/NginxProxyManager/nginx-proxy-manager)) `MIT` `Docker`
- [NGINX](https://nginx.org/en/) - HTTP 和反向代理服务器、邮件代理服务器以及通用的 TCP/UDP 代理服务器。 ([源代码](https://github.com/nginx/nginx)) `BSD-2-Clause` `C/deb/Docker`
- [Pangolin](https://digpangolin.com/) - 身份感知的隧道反向代理，具有仪表盘 UI、访问控制和基于 WireGuard 的隧道（Cloudflare Tunnel、Tailscale 的替代品）。 ([源代码](https://github.com/fosrl/pangolin)) `AGPL-3.0` `Docker`
- [Pomerium](https://www.pomerium.io) - 具备身份感知能力的反向代理，是现已过时的 oauth_proxy 的后继者。它会在将请求代理到后端之前插入 OAuth 步骤，从而让你能更安全地将自托管网站暴露到公网。 ([源代码](https://github.com/pomerium/pomerium)) `Apache-2.0` `Go/Docker`
- [SafeLine](https://waf.chaitin.com/) - Web 应用防火墙/反向代理，用于保护你的 Web 应用免受攻击和利用。 ([演示](https://demo.waf.chaitin.com/), [源代码](https://github.com/chaitin/SafeLine)) `GPL-3.0` `Docker`
- [Static Web Server](https://static-web-server.net/) - 跨平台、高性能且异步的静态文件服务 Web 服务器。 ([源代码](https://github.com/static-web-server/static-web-server)) `Apache-2.0/MIT` `Rust/Docker`
- [SWAG (Secure Web Application Gateway)](https://github.com/linuxserver/docker-swag) - Nginx webserver 和带有 PHP 支持的反向代理，内置 Certbot（Let's Encrypt）客户端和 fail2ban 集成。 `GPL-3.0` `Docker`
- [Traefik](https://traefik.io/) - HTTP 反向代理和负载均衡器，使微服务部署变得简单。 ([源代码](https://github.com/traefik/traefik)) `MIT` `Go/Docker`
- [UUSEC WAF](https://waf.uusec.com/) - 行业领先的高性能、AI 与语义技术 Web 应用防火墙和 API 安全网关（nginx 分支）。 ([源代码](https://github.com/Safe3/uusec-waf)) `GPL-3.0` `C/Lua/Docker`
- [Vinyl Cache](https://vinyl-cache.org/) - Web 应用加速器/缓存型 HTTP 反向代理（前身为 Varnish）。 ([源代码](https://code.vinyl-cache.org/vinyl-cache/vinyl-cache)) `BSD-2-Clause` `Go/deb/Docker`
- [Zoraxy](https://zoraxy.aroz.org/) - 通用的 HTTP 反向代理和转发工具。 ([源代码](https://github.com/tobychui/zoraxy)) `AGPL-3.0` `Go/Docker`


### 个人仪表板

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

用于访问信息和应用程序的仪表板。

_相关: [监控和状态页面](#监控和状态页面), [书签和链接分享](#书签和链接分享)_

- [Dashy](https://dashy.to/) - 针对您的家庭实验室（homelab）的功能丰富的主页，带有简单的 YAML 配置。 ([演示](https://demo.dashy.to/), [源代码](https://github.com/lissy93/dashy)) `MIT` `Node.js/Docker`
- [Glance](https://github.com/glanceapp/glance) - 高度可定制的仪表板，将所有订阅聚合到一个界面。 `AGPL-3.0` `Docker/Go`
- [gobookmarks](https://github.com/arran4/gobookmarks) - 显示存储在 GitHub、GitLab 或本地 Git 中的书签的登录页面。 `AGPL-3.0` `Go/Docker`
- [Heimdall](https://heimdall.site/) - 优雅地整理所有网页应用的解决方案。 ([源代码](https://github.com/linuxserver/Heimdall)) `MIT` `PHP`
- [Hiccup](https://designedbyashw.in/test/hiccup/) - 美观的静态主页，可快速访问您的链接和服务。它内置搜索、编辑、PWA 支持和本地存储缓存，方便您轻松组织起始页。 ([源代码](https://github.com/ashwin-pc/hiccup)) `MIT` `JavaScript/Docker`
- [Homarr](https://homarr.dev) - 时尚现代的仪表板，具有多种集成和基于网页的配置。 ([源代码](https://github.com/homarr-labs/homarr)) `MIT` `Docker/Node.js`
- [Homepage by gethomepage](https://github.com/gethomepage/homepage) - 高度可定制的主页（或起始页/应用仪表板），支持 Docker 和服务 API 集成。 `GPL-3.0` `Docker/Node.js`
- [Homepage by tomershvueli](https://github.com/tomershvueli/homepage) - 简单、独立、自托管的PHP页面，是您访问服务器和互联网的窗口。 `MIT` `PHP`
- [Homer](https://github.com/bastienwirtz/homer) - 一个极其简单的静态主页，用于展示你的服务器服务，支持简单的 YAML 配置和连通性检查。 ([演示](https://homer-demo.netlify.app)) `Apache-2.0` `Docker/K8S/Node.js`
- [Hubleys](https://github.com/knrdl/hubleys-dashboard) - 个人仪表板，通过中心化的 YAML 配置为多个用户组织链接。 `MIT` `Docker`
- [LinkStack](https://linkstack.org/) - 将您所有的社交媒体平台链接集中在一个页面上，通过直观、易于使用的用户/管理界面进行定制（是Linktree和Manylink的替代品）。 ([演示](https://linksta.cc/), [源代码](https://github.com/LinkStackOrg/LinkStack)) `AGPL-3.0` `PHP/Docker`
- [LittleLink](https://littlelink.io/) - 简洁的个人主页链接工具，提供 100+ 品牌按钮（Linktree 的替代品）。 ([演示](https://littlelink.io/), [源代码](https://github.com/sethcottle/littlelink)) `MIT` `JavaScript`
- [Mafl](https://mafl.hywax.space/) - 极简灵活的个人主页。 ([源代码](https://github.com/hywax/mafl)) `MIT` `Docker/Node.js`
- [Nimbus](https://nimbus.turboot.com/) - 支持拖放的现代化家庭实验室仪表板，提供可视化编辑器和简单配置。 ([演示](https://nimbus.turboot.com/), [源代码](https://github.com/Turbootzz/Nimbus)) `AGPL-3.0` `Docker`
- [Personal Management System](https://volmarg.github.io/) - 组织日常生活的必需品，从简单的待办事项和笔记到付款和日程安排。 ([演示](https://github.com/Volmarg/personal-management-system#documentation--demo), [源代码](https://github.com/Volmarg/personal-management-system)) `MIT` `Docker`
- [portkey](https://portkey.page) - 一个简洁的 Web 门户，可作为启动页展示链接与 URL 集合，同时支持添加自定义页面，且全部通过单个配置文件进行管理。 ([演示](https://demo.portkey.page), [源代码](https://github.com/kodehat/portkey)) `AGPL-3.0` `Go/Docker`
- [ryot](https://github.com/ignisda/ryot) - 跟踪你生活的各个方面——媒体、健身等。 ([演示](https://github.com/IgnisDa/ryot?tab=readme-ov-file#-demo)) `GPL-3.0` `Docker`
- [Starbase 80](https://github.com/notclickable-jordan/starbase-80) - 一个简单的主页，具有iPad风格的应用程序网格，适用于移动设备和桌面。只需一个JSON配置文件。 `MIT` `Docker`
- [Your Spotify](https://github.com/Yooooomi/your_spotify) `⚠` - 允许您记录Spotify播放活动，并通过Web应用程序提供有关它们的统计信息。 `MIT` `Node.js/Docker`


### 书签和链接分享

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

软件允许用户添加、注释、编辑和分享[网络文档](https://en.wikipedia.org/wiki/Bookmark_(digital))的书签。

- [Betula](https://joinbetula.org) - 支持 Fediverse 联合的单用户书签管理器，带有存档功能。 ([源代码](https://codeberg.org/bouncepaw/betula)) `AGPL-3.0` `Go`
- [Buku](https://github.com/jarun/Buku) - 强大的书签管理器和个人文本迷你网页。 `GPL-3.0` `Python/deb`
- [Digibunch](https://ladigitale.dev/digibunch/#/) - 创建链接捆绑，与您的学员或同事分享。 ([演示](https://ladigitale.dev/digibunch/#/b/5f67b12092b60), [源代码](https://codeberg.org/ladigitale/digibunch)) `AGPL-3.0` `Node.js/PHP`
- [Espial](https://github.com/jonschoning/espial) - 一个开源的、基于Web的书签服务器。 `AGPL-3.0` `Haskell`
- [Faved](https://faved.dev/) - 精心设计的书签管理器，结合强大的标签、即时搜索和简洁无干扰的界面，专为大型收藏和高效工作流优化。 ([演示](https://demo.faved.dev/), [源代码](https://github.com/denho/faved)) `MIT` `Docker`
- [Firefox Account Server](https://mozilla-services.readthedocs.io/en/latest/howtos/run-fxa.html) - 自己托管 Firefox 账户服务器。 ([源代码](https://github.com/mozilla/fxa)) `MPL-2.0` `Node.js/Java`
- [Karakeep](https://karakeep.app/) - 一款为数据控打造、带有 AI 功能的“一切皆可收藏”应用。 ([演示](https://try.karakeep.app/signin), [源代码](https://github.com/karakeep-app/karakeep)) `AGPL-3.0` `Docker`
- [LinkAce](https://www.linkace.org/) - 书签存档工具，支持自动备份至互联网档案馆、链接监控和完整的 REST API。可通过 Docker 或简单的 PHP 应用方式安装。 ([演示](https://demo.linkace.org/guest/links), [源代码](https://github.com/Kovah/LinkAce/)) `GPL-3.0` `Docker/PHP`
- [linkding](https://linkding.link/) - 极简书签管理工具，界面简洁流畅。支持通过 Docker 快速安装，可运行在树莓派上。 ([演示](https://demo.linkding.link/login/), [源代码](https://github.com/sissbruecker/linkding)) `MIT` `Docker`
- [LinkWarden](https://linkwarden.app/) - 书签与存档管理器，用于保存实用链接。 ([源代码](https://github.com/linkwarden/linkwarden)) `MIT` `Docker/Node.js`
- [NeonLink](https://github.com/AlexSciFier/neonlink) - 具有独特设计且可通过 Docker 简单安装的书签服务。 `MIT` `Docker`
- [Readeck](https://readeck.org/en/) - 保存你喜欢并想永久保留的网页可读内容。可视为书签管理器和稍后阅读工具。 ([源代码](https://codeberg.org/readeck/readeck), [客户端](https://codeberg.org/readeck/browser-extension)) `AGPL-3.0` `Go/Docker`
- [Servas](https://github.com/beromir/Servas) - 一款自托管的书签管理工具。它支持通过标签、分组和专门用于以后访问的列表进行组织。支持多用户，并提供双因素认证 (2FA)。还提供了适用于 Firefox 和 Chrome 的伴侣浏览器扩展。 ([客户端](https://github.com/beromir/Servas#browser-extensions)) `GPL-3.0` `Docker/Node.js/PHP`
- [Shaarli](https://github.com/shaarli/Shaarli) - 个人、极简、超快、无数据库的书签和链接分享平台。 ([演示](https://demo.shaarli.org)) `Zlib` `PHP/deb`
- [Shiori](https://github.com/go-shiori/shiori) - 使用 Go 构建的简单书签管理器。 `MIT` `Go/Docker`
- [Slash](https://github.com/yourselfhosted/slash) - 开源自托管的书签与链接分享平台。 `GPL-3.0` `Docker`
- [SyncMarks](https://codeberg.org/Offerel/SyncMarks-Webapp) - 从 Edge、Firefox 和 Chromium 同步和管理您的浏览器书签。 ([客户端](https://codeberg.org/Offerel/SyncMarks-Extension)) `AGPL-3.0` `PHP`


### 人力资源管理（HRM）

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[人力资源管理系统](https://en.wikipedia.org/wiki/Human_resource_management_system)整合了多个系统和流程，以确保轻松管理[人力资源](https://en.wikipedia.org/wiki/Human_resources)、业务流程和数据。

- [Admidio](https://www.admidio.org/) - 用于组织和团体网站的用户管理系统。该系统具有灵活的角色模型，可以反映您组织的结构和权限。 ([演示](https://www.admidio.org/demo/), [源代码](https://github.com/Admidio/admidio)) `GPL-2.0` `PHP/Docker`
- [Frappe HR](https://frappe.io/hr) - 完整的 HRMS 解决方案，涵盖 13 个不同的模块，包括员工管理、入职、请假、薪资、税务等。 ([源代码](https://github.com/frappe/hrms)) `GPL-3.0` `Docker/Python/Node.js`
- [MintHCM](https://minthcm.org/) - 基于两个流行的业务应用程序SugarCRM Community Edition和SuiteCRM的人力资本管理工具。 ([源代码](https://github.com/minthcm/minthcm)) `AGPL-3.0` `PHP`


### 代理

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[代理](https://en.wikipedia.org/wiki/Proxy_server) 是一种服务器应用程序，充当请求资源的客户端与提供该资源的服务器之间的中介。本节介绍正向（即出站）代理。有关反向代理，请参见 Web 服务器部分。

_相关: [Web 服务器](#web-服务器)_

- [g3proxy](https://g3-project.readthedocs.io/projects/g3proxy/en/latest/) - 支持代理链、协议检查、MITM 拦截、ICAP 适配和透明代理的前向代理服务器。 ([源代码](https://github.com/bytedance/g3/tree/master/g3proxy)) `Apache-2.0` `Rust/deb`
- [imgproxy](https://imgproxy.net/) - 快速且安全的独立服务器，用于调整和转换远程图片。 ([源代码](https://github.com/imgproxy/imgproxy)) `MIT` `Go/Docker/K8S`
- [iodine](https://code.kryo.se/iodine/) - 基于DNS的IPv4隧道解决方案，使您能够启动一个socks5代理监听器。 ([源代码](https://github.com/yarrick/iodine)) `ISC` `C/deb`
- [Outline Server](https://getoutline.org/) - 代理服务器，为每个访问密钥运行一个Shadowsocks实例，并提供一个REST API来管理访问密钥。 ([源代码](https://github.com/OutlineFoundation/outline-server)) `Apache-2.0` `Docker/Node.js`
- [Privoxy](https://www.privoxy.org) - 一款非缓存的Web代理，具有先进的过滤功能，用于增强隐私、修改网页数据和HTTP头部、控制访问，并去除广告和其他令人讨厌的互联网垃圾。 `GPL-2.0` `C/deb`
- [sish](https://github.com/antoniomika/sish) - 通过仅使用SSH实现到本地主机的HTTP(S)/WS(S)/TCP隧道（Serveo/ngrok的替代品）。 `MIT` `Go/Docker`
- [socks5-proxy-server](https://github.com/nskondratev/socks5-proxy-server) - 带有内置身份验证和Telegram机器人的SOCKS5代理服务器，用于用户管理和用户数据使用统计（在按数据量支付时非常方便）。已经Docker化，安装简便。 `Apache-2.0` `Docker`
- [Squid](http://www.squid-cache.org/) - Web缓存代理，支持HTTP、HTTPS、FTP等。通过缓存和重复使用频繁请求的网页，减少带宽并提高响应时间。 ([源代码](https://code.launchpad.net/squid)) `GPL-2.0` `C/deb`
- [Tinyproxy](https://tinyproxy.github.io/) - 轻量级的 HTTP/HTTPS 代理守护程序。 ([源代码](https://github.com/tinyproxy/tinyproxy)) `GPL-2.0` `C/deb`


### 任务管理和待办清单

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[任务管理](https://en.wikipedia.org/wiki/Task_management#Task_management_software)软件。

_相关: [软件开发 - 项目管理](#软件开发---项目管理), [工单](#工单)_

- [4ga Boards](https://4gaboards.com) - 简单直观的实时看板管理，用于直观的任务跟踪。提供优雅的暗色模式、可折叠的待办事项列表和多任务工具，以大幅提升团队生产力。 ([演示](https://demo.4gaboards.com), [源代码](https://github.com/RARgames/4gaBoards)) `MIT` `Node.js/Docker/K8S`
- [AppFlowy](https://appflowy.io/) - 为不同项目构建详细的待办事项列表，并跟踪每个任务的状态。开源的 Notion 替代品。 ([源代码](https://github.com/AppFlowy-IO/appflowy)) `AGPL-3.0` `Rust/Dart/Docker`
- [Donetick](https://donetick.com) - 个人和家庭使用的任务和琐事管理工具，具有先进的调度、灵活的分配和群组共享功能，详细的历史记录，通过 API 实现自动化，简洁现代的设计。 ([演示](https://app.donetick.com/), [源代码](https://github.com/donetick/donetick)) `AGPL-3.0` `Go/Docker`
- [Focus Flow](https://github.com/francesco-gaglione/focus_flow_cloud) - 基于番茄工作法的完整时间管理生态系统。 `MIT` `Docker/K8S`
- [HamsterBase Tasks](https://tasks.hamsterbase.com) - 帮助整理创意和规划项目的工具，支持计划、组织、构建和发布。 ([演示](https://tasks-app.hamsterbase.com), [源代码](https://github.com/hamsterbase/tasks)) `AGPL-3.0` `Docker`
- [Kanboard](https://kanboard.org/) - 简洁的可视化任务看板。 ([源代码](https://github.com/kanboard/kanboard)) `MIT` `PHP`
- [Listaway](https://github.com/jeffrpowell/listaway/) - 列表管理应用，用于创建和公开分享条目列表。支持身份验证、管理工具、条目备注与优先级，以及可选的随机 URL 公开只读链接（Amazon Lists 的替代品）。 ([源代码](https://github.com/jeffrpowell/listaway)) `MIT` `Docker`
- [myTinyTodo](https://www.mytinytodo.net/) - 使用 AJAX 风格简单管理待办事项清单的方式。使用 PHP、jQuery、SQLite/MySQL。符合 GTD。 ([演示](https://www.mytinytodo.net/demo/), [源代码](https://github.com/maxpozdeev/mytinytodo/)) `GPL-2.0` `PHP`
- [Nullboard](https://github.com/apankrat/nullboard) - 单页极简看板；紧凑、易读且使用快捷。 ([演示](https://nullboard.io/preview)) `BSD-2-Clause` `JavaScript`
- [OpenHabitTracker](https://openhabittracker.net) - 追踪习惯、任务和笔记，具有时间追踪、日历视图和完成统计功能。 ([演示](https://pwa.openhabittracker.net), [源代码](https://github.com/Jinjinov/OpenHabitTracker)) `GPL-3.0` `Docker`
- [Our Shopping List](https://github.com/nanawel/our-shopping-list) - 简单的共享列表应用，包括购物清单及其他需要协作使用的小型待办清单。 ([演示](https://osl.lanterne-rouge.info/)) `AGPL-3.0` `Docker`
- [Super Productivity](https://super-productivity.com) - 高级待办清单应用，集成时间盒与时间追踪功能，并可与 Jira、GitHub、GitLab、Redmine 和 OpenProject 集成。 ([源代码](https://github.com/super-productivity/super-productivity)) `MIT` `Docker`
- [Task Keeper](https://github.com/nymanjens/piga) - 面向高级用户的列表编辑器，由自托管服务器支持。 `Apache-2.0` `Scala`
- [Tasks.md](https://github.com/BaldissaraMatheus/Tasks.md) - 支持 Markdown 语法的自托管文件型任务管理板。 `MIT` `Docker`
- [Taskwarrior](https://taskwarrior.org/) - Taskwarrior 是一款自由开源软件，可以通过命令行管理您的待办事项列表。它灵活、快速、高效且不显眼。它完成任务后离开您的视线。 ([源代码](https://taskwarrior.org/download/#git)) `MIT` `C++`
- [Tracks](https://www.getontracks.org/) - 基于Web的应用，帮助您实施David Allen的[Getting Things Done™](https://en.wikipedia.org/wiki/Getting_Things_Done)方法论。 ([源代码](https://github.com/TracksApp/tracks)) `GPL-2.0` `Ruby`
- [tududi](https://tududi.com/) - 具备分层结构、智能重复任务和无缝 Telegram 集成的任务管理工具。 ([源代码](https://github.com/chrisvel/tududi)) `MIT` `Docker`
- [Vikunja](https://vikunja.io/) - 用于组织生活的待办事项应用。 ([演示](https://try.vikunja.io/login), [源代码](https://github.com/go-vikunja/vikunja)) `AGPL-3.0/GPL-3.0` `Go`
- [Wekan](https://wekan.github.io/) - 类似Trello的开源看板（kanban）。 ([源代码](https://github.com/wekan/wekan)) `MIT` `Node.js`


### 会议管理

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

用于提交[摘要](https://en.wikipedia.org/wiki/Abstract_management)和准备/管理学术会议的软件。

- [indico](https://getindico.io/) - 功能丰富的会议管理系统，诞生于 CERN（万维网的发源地）。 ([演示](https://sandbox.getindico.io/), [源代码](https://github.com/indico/indico)) `MIT` `Python`
- [motion.tools (Antragsgrün)](https://motion.tools/) - 管理（政治）大会的动议和修正案。 ([演示](https://sandbox.motion.tools/createsite), [源代码](https://github.com/CatoTH/antragsgruen)) `AGPL-3.0` `PHP/Docker`
- [OpenSlides](https://openslides.com/) - 用于管理和投影会议议程、动议和选举的演示和大会系统。 ([演示](https://demo.openslides.org/login), [源代码](https://github.com/OpenSlides/OpenSlides)) `MIT` `Docker`
- [osem](https://osem.io/) - 面向自由软件大会的事件管理系统。 ([源代码](https://github.com/openSUSE/osem)) `MIT` `Ruby/Docker`
- [pretalx](https://pretalx.org) - 基于Web的事件管理，包括发起论文征集、审阅提交内容和安排演讲。支持与各种相关工具的导出和导入。 ([源代码](https://github.com/pretalx/pretalx)) `Apache-2.0` `Python`


### 健康和健身

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[医疗](https://en.wikipedia.org/wiki/Medical_software)、[卫生](https://en.wikipedia.org/wiki/Health_information_technology)和[健身](https://en.wikipedia.org/wiki/Fitness_tracker)软件。

- [Endurain](https://docs.endurain.com/) - 健身追踪服务，旨在让用户完全控制他们的数据和托管环境。 ([源代码](https://codeberg.org/endurain-project/endurain)) `AGPL-3.0` `Docker`
- [Fasten Health](https://github.com/fastenhealth/fasten-onprem/) `⚠` - 个人/家庭电子病历聚合器，旨在与美国成千上万的保险公司、医院和诊所集成。 `GPL-3.0` `Go/Docker`
- [FitTrackee](https://docs.fittrackee.org/) - 简单的锻炼/活动跟踪器。 ([源代码](https://github.com/SamR1/FitTrackee)) `AGPL-3.0` `Python/Docker`
- [Mere Medical](https://meremedical.co/) `⚠` - 在一处统一管理来自 Epic MyChart、Cerner 和 OnPatient 患者门户的所有医疗记录。注重隐私、支持自托管且优先支持离线使用。 ([演示](https://demo.meremedical.co), [源代码](https://github.com/cfu288/mere-medical)) `GPL-3.0` `Docker/Node.js`
- [OpenEMR](https://www.open-emr.org/) - 电子健康记录和医疗实践管理解决方案。 ([演示](https://www.open-emr.org/demo/), [源代码](https://github.com/openemr/openemr)) `GPL-3.0` `PHP/Docker`
- [wger](https://wger.de/) - 基于Web的个人锻炼、健身和体重记录/跟踪工具。还可以用作简单的健身房管理实用工具，并提供完整的REST API。 ([演示](https://wger.de/en/dashboard), [源代码](https://github.com/wger-project/wger)) `AGPL-3.0` `Python/Docker`
- [Wingfit](https://wingfit.fr) - 极简主义健身应用，用于规划锻炼、追踪个人纪录并利用智能手表数据。 ([演示](https://wingfit.fr/home), [源代码](https://github.com/itskovacs/wingfit)) `CC-BY-SA-4.0` `Python/Docker`


### 内容管理系统（CMS）

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[内容管理系统](https://en.wikipedia.org/wiki/Content_management_system)提供了一种实用的方式来设置具有许多功能的网站，使用第三方插件、主题和易于添加和定制的功能。

_相关: [博客平台](#博客平台), [静态网站生成器](#静态网站生成器), [相册](#相册)_

- [Alfresco Community Edition](https://www.alfresco.com/products/community/download) - 开源企业内容管理软件，可处理任何类型的内容，使用户能够轻松共享和协作。 ([源代码](https://github.com/Alfresco/alfresco-community-repo)) `LGPL-3.0` `Java`
- [Apostrophe](https://apostrophecms.com/) - 一款注重可扩展的现场编辑工具的内容管理系统 (CMS)。 ([演示](https://apostrophecms.com/demo), [源代码](https://github.com/apostrophecms/apostrophe)) `MIT` `Node.js`
- [Automad](https://automad.org/) - 基于文件的内容管理系统和模板引擎。 ([演示](https://try.automad.org/), [源代码](https://github.com/marcantondahmen/automad)) `MIT` `PHP/Docker`
- [Backdrop CMS](https://backdropcms.org/) - 面向中小型企业和非营利组织的综合性 CMS。 ([源代码](https://github.com/backdrop/backdrop)) `GPL-2.0` `PHP`
- [Bludit](https://www.bludit.com/) `⚠` - 用几秒钟即可搭建网站或博客。Bludit 使用平面文件（JSON 格式的文本文件）来存储文章和页面。 ([源代码](https://github.com/bludit/bludit)) `MIT` `PHP`
- [Bolt CMS](https://boltcms.io/) - 内容管理工具，力求尽可能简单明了。 ([源代码](https://github.com/bolt/core)) `MIT` `PHP`
- [CMS Made Simple](https://www.cmsmadesimple.org/) - 更快更轻松地管理网站内容，适用于从小型企业到大型公司的扩展。 ([源代码](http://svn.cmsmadesimple.org/svn/cmsmadesimple/trunk/)) `GPL-2.0` `PHP`
- [Cockpit](https://getcockpit.com) - 简单的内容平台，用于管理任何结构化内容。 ([源代码](https://github.com/Cockpit-HQ/Cockpit)) `MIT` `PHP`
- [Concrete 5 CMS](https://www.concretecms.com) - 开源内容管理系统。 ([源代码](https://github.com/concretecms/concretecms)) `MIT` `PHP`
- [Contao](https://contao.org/) - 强大的内容管理系统，可用于创建专业网站和可扩展的 Web 应用程序。 ([演示](https://demo.contao.org/contao), [源代码](https://github.com/contao/contao/)) `LGPL-3.0` `PHP`
- [CouchCMS](https://www.couchcms.com/) - 面向设计师的内容管理系统（CMS）。 ([源代码](https://github.com/CouchCMS/CouchCMS)) `CPAL-1.0` `PHP`
- [Drupal](https://www.drupal.org/) - 先进的开源内容管理平台。 ([源代码](https://git.drupalcode.org/project/drupal)) `GPL-2.0` `PHP`
- [eLabFTW](https://www.elabftw.net) - 用于研究实验室的在线实验笔记本。存储实验数据，使用数据库查找试剂或协议，使用受信任的时间戳对实验进行法律时间戳，导出为PDF或ZIP归档文件，与合作者共享……。 ([演示](https://demo.elabftw.net), [源代码](https://github.com/elabftw/elabftw)) `AGPL-3.0` `PHP`
- [Expressa](https://github.com/thomas4019/expressa) - 用于通过JSON模式驱动的数据库网站的内容管理系统。提供权限管理和自动REST API。 `MIT` `Node.js`
- [Joomla!](https://www.joomla.org/) - 先进的内容管理系统（CMS）。 ([源代码](https://github.com/joomla/joomla-cms)) `GPL-2.0` `PHP`
- [KeystoneJS](https://keystonejs.com/) - CMS 与 Web 应用开发平台。 ([源代码](https://github.com/keystonejs/keystone)) `MIT` `Node.js`
- [Localess](https://localess.org/home) `⚠` - 强大的翻译管理和内容管理系统。使用人工智能加速翻译，将您的网站或应用内容翻译成多种语言。 ([源代码](https://github.com/Lessify/localess)) `MIT` `Docker`
- [MODX](https://modx.com/) - 高级内容管理与发布平台，当前版本名为"Revolution"。 ([源代码](https://github.com/modxcms/revolution)) `GPL-2.0` `PHP`
- [Neos](https://www.neos.io) - Neos 或 TYPO3 Neos（版本 1）是一款现代的开源 CMS。 ([源代码](https://github.com/neos)) `GPL-3.0` `PHP`
- [Noosfero](https://gitlab.com/noosfero/noosfero) - 社会与团结经济网络平台，在同一系统中集成了博客、电子作品集、CMS、RSS、主题讨论、活动日程和团结经济的集体智慧。 `AGPL-3.0` `Ruby`
- [Omeka](https://omeka.org) - 在您的服务器上使用Omeka创建复杂的叙述并共享丰富的收藏，遵循Dublin Core标准，专为学者、博物馆、图书馆、档案馆和爱好者设计。 ([演示](https://omeka.org/classic/showcase/), [源代码](https://github.com/omeka/Omeka)) `GPL-3.0` `PHP`
- [Payload CMS](https://payloadcms.com/) - 面向开发者的无头CMS和应用程序框架。 ([源代码](https://github.com/payloadcms/payload)) `MIT` `Node.js`
- [Pimcore](http://www.pimcore.com/) - 多渠道体验与互动管理平台。 ([源代码](https://github.com/pimcore/pimcore)) `GPL-3.0` `PHP/Docker`
- [Plone](https://plone.org/) - 强大的开源内容管理系统（CMS）。 ([源代码](https://github.com/plone)) `ZPL-2.0` `Python/Docker`
- [Publify](https://publify.github.io/) - 简单但功能齐全的Web发布软件。 ([源代码](https://github.com/publify/publify)) `MIT` `Ruby`
- [REDAXO](https://www.redaxo.org) - 简单、灵活且实用的内容管理系统（文档为德语）。 ([源代码](https://github.com/redaxo/core)) `MIT` `PHP/Docker`
- [SilverStripe](https://www.silverstripe.org) - 易于使用的 CMS，具有强大的 MVC 框架作为基础。 ([演示](https://demo.silverstripe.org/), [源代码](https://github.com/silverstripe)) `BSD-3-Clause` `PHP`
- [SPIP](https://www.spip.net/fr) - 面向协同工作、多语言环境和Web作者使用简便的互联网发布系统。 ([源代码](https://git.spip.net/)) `GPL-3.0` `PHP`
- [Squidex](https://squidex.io) - 基于MongoDB、CQRS和事件溯源的无头CMS。 ([演示](https://cloud.squidex.io), [源代码](https://github.com/Squidex/squidex)) `MIT` `.NET`
- [Strapi](https://strapi.io/) - 最先进的开源内容管理框架（无头CMS），可以轻松构建强大的API。 ([源代码](https://github.com/strapi/strapi)) `MIT` `Node.js`
- [Superdesk](https://superdesk.org/) `⚠` - 端到端的新闻创建、生产、策划、分发和发布平台。 ([源代码](https://github.com/superdesk/superdesk)) `AGPL-3.0` `Docker/Python/PHP`
- [Textpattern](https://textpattern.com/) - 灵活、优雅且易于使用的内容管理系统。 ([源代码](https://github.com/textpattern/textpattern)) `GPL-2.0` `PHP`
- [Typemill](https://typemill.net/) - 作者友好的基于文件的CMS，具有基于vue.js的可视化Markdown编辑器。 ([源代码](https://github.com/typemill/typemill)) `MIT` `PHP`
- [TYPO3](https://typo3.org/) - 强大而先进的CMS，拥有庞大的社区。 ([源代码](https://github.com/TYPO3/typo3)) `GPL-2.0` `PHP`
- [Umbraco](https://umbraco.com/) - 友好的CMS。免费、开源，并拥有令人惊叹的社区。 ([源代码](https://github.com/umbraco/Umbraco-CMS)) `MIT` `.NET`
- [Vvveb CMS](https://www.vvveb.com) - 强大且易用的 CMS，用于构建网站、博客或电子商务商店。 ([演示](https://demo.vvveb.com), [源代码](https://github.com/givanz/Vvveb)) `AGPL-3.0` `PHP/Docker`
- [Wagtail](https://wagtail.io/) - 基于Django的内容管理系统，注重灵活性和用户体验。 ([源代码](https://github.com/wagtail/wagtail)) `BSD-3-Clause` `Python`
- [WinterCMS](https://wintercms.com/) - 基于Laravel PHP框架构建的快速且安全的内容管理系统。 ([源代码](https://github.com/wintercms/winter)) `MIT` `PHP`
- [WonderCMS](https://www.wondercms.com) - WonderCMS是自2008年以来最小的平面文件CMS。 ([演示](https://www.wondercms.com/demo), [源代码](https://github.com/WonderCMS/wondercms)) `MIT` `PHP`
- [WordPress](https://wordpress.org/) - 全球最常用的博客和内容管理系统引擎。 ([源代码](https://github.com/WordPress/WordPress)) `GPL-2.0` `PHP`


### 分布式文件系统

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

网络分布式文件系统。

- [Ceph](https://ceph.com/en/) - 分布式对象、块和文件存储平台。 ([源代码](https://github.com/ceph/ceph)) `LGPL-3.0` `C++`
- [DRBD](https://linbit.com/drbd/) - 分布式复制存储系统，作为 Linux 内核驱动实现。 ([源代码](https://github.com/LINBIT/drbd)) `GPL-2.0` `C`
- [GlusterFS](https://www.gluster.org/) - 软件定义的分布式存储，可扩展到数 PB，支持对象、块和文件存储接口。 ([源代码](https://github.com/gluster/glusterfs)) `GPL-2.0/LGPL-3.0` `C`
- [Hadoop Distributed Filesystem (HDFS)](https://hadoop.apache.org/) - 提供高吞吐量访问应用数据的分布式文件系统。 ([源代码](https://github.com/apache/hadoop)) `Apache-2.0` `Java`
- [JuiceFS](https://juicefs.com/) - 基于 Redis 和 S3 构建的分布式 POSIX 文件系统。 ([源代码](https://github.com/juicedata/juicefs)) `Apache-2.0` `Go`
- [Kubo](https://github.com/ipfs/kubo) - IPFS 的实现，一个全球、版本化、点对点的文件系统，旨在连接所有计算设备。 `Apache-2.0/MIT` `Go`
- [LeoFS](https://github.com/leo-project/leofs) - 高可用、分布式、最终一致性的对象/Blob 存储。 `Apache-2.0` `Erlang`
- [Lustre](https://www.lustre.org/) - 并行分布式文件系统，常用于大规模集群计算。 ([源代码](https://git.whamcloud.com/?p=fs/lustre-release.git;a=summary)) `GPL-2.0` `C`
- [MooseFS](https://moosefs.com/) - 容错的网络分布式文件系统。 ([源代码](https://github.com/moosefs/moosefs)) `GPL-2.0` `C`
- [OpenAFS](https://www.openafs.org/) - 支持只读副本和多操作系统的分布式网络文件系统。 ([源代码](https://gerrit.openafs.org)) `IPL-1.0` `C`
- [Openstack Swift](https://docs.openstack.org/developer/swift/) - 高可用、分布式、最终一致性的对象/Blob 存储。 ([源代码](https://opendev.org/openstack/swift)) `Apache-2.0` `Python`
- [Perkeep](https://perkeep.org/) - 一组用于建模、存储、搜索、共享和同步数据的开源格式、协议和软件（前身为 Camlistore）。 ([源代码](https://github.com/perkeep/perkeep)) `Apache-2.0` `C`
- [TahoeLAFS](https://tahoe-lafs.org/trac/tahoe-lafs) - 安全、去中心化、容错的点对点分布式数据存储和文件系统。 ([源代码](https://github.com/tahoe-lafs/tahoe-lafs)) `GPL-2.0` `Python`
- [XtreemFS](https://www.xtreemfs.org/) - 面向联合 IT 基础设施的分布式、复制和容错文件系统。 ([源代码](https://github.com/xtreemfs/xtreemfs)) `BSD-3-Clause` `Java`


### 分析

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[分析](https://en.wikipedia.org/wiki/Analytics)是对数据或统计信息进行系统计算分析的过程。它用于发现、解释和传达数据中的有意义的模式。

_相关: [数据库管理](#数据库管理), [个人仪表板](#个人仪表板)_

- [ANALOG](https://github.com/orangecoloured/analog) - 一个极简分析工具。追踪 10-30 天内的事件。 `MIT` `Node.js/Docker`
- [Aptabase](https://aptabase.com/) - 面向隐私且简单的移动和桌面应用分析工具。 ([源代码](https://github.com/aptabase/aptabase)) `AGPL-3.0` `Docker`
- [AWStats](http://www.awstats.org/) - 从 web、流媒体、FTP 或邮件服务器的日志文件生成统计信息。 ([演示](https://www.awstats.org/#DEMO), [源代码](https://github.com/eldy/awstats)) `GPL-3.0` `Perl`
- [Countly Community Edition](https://count.ly) - 实时移动和网页分析、崩溃报告和推送通知平台。 ([源代码](https://github.com/Countly/countly-server)) `AGPL-3.0` `Node.js/Docker`
- [d8a.tech](https://d8a.tech) - 一项数据收集服务，与您现有的 Google Analytics 设置协同工作，以捕获用户活动并将其直接发送到您自己的私有数据库。 ([演示](https://lookerstudio.google.com/u/0/reporting/0e4102b6-c38b-4f55-aa25-c1fe91d1c1e9), [源代码](https://github.com/d8a-tech/d8a)) `MIT` `Go/Docker`
- [Daily Stars Explorer](https://emanuelef.github.io/daily-stars-explorer) `⚠` - 通过每日星标见解跟踪 GitHub 仓库趋势，查看增长和社区兴趣随时间的变化。 ([演示](https://emanuelef.github.io/daily-stars-explorer), [源代码](https://github.com/emanuelef/daily-stars-explorer)) `MIT` `Go/Node.js/Docker`
- [Druid](https://druid.apache.org) - 分布式、面向列、实时分析数据存储。 ([源代码](https://github.com/apache/druid)) `Apache-2.0` `Java/Docker`
- [EDA](https://github.com/jortilles/EDA) - 用于数据分析和可视化的Web应用程序。 `AGPL-3.0` `Node.js/Docker`
- [GoAccess](http://goaccess.io/) - 实时 Web 日志分析器和交互式查看器，可在终端或浏览器中运行。 ([源代码](https://github.com/allinurl/goaccess)) `MIT` `C`
- [GoatCounter](https://www.goatcounter.com) - 无需跟踪个人数据的简易网络统计工具。 ([源代码](https://github.com/arp242/goatcounter)) `EUPL-1.2` `Go`
- [HitKeep](https://hitkeep.com/) - 隐私优先的网页分析工具，集成目标、漏斗、电子商务跟踪和团队管理于一个二进制文件中，内嵌 DuckDB（Google Analytics、Plausible、Umami 的替代方案）。 ([源代码](https://github.com/pascalebeier/hitkeep)) `MIT` `Go/Docker`
- [Litlyx](https://litlyx.com) - 一体化分析解决方案。30秒内完成设置。在 AI 驱动的仪表板上展示所有数据。完全可自托管，并符合 GDPR 要求。 ([源代码](https://github.com/Litlyx/litlyx)) `Apache-2.0` `Docker`
- [Liwan](https://liwan.dev/) - 隐私优先的网站分析工具。 ([演示](https://demo.liwan.dev/p/liwan.dev), [源代码](https://github.com/explodingcamera/liwan)) `Apache-2.0` `Rust/Docker`
- [Matomo](https://matomo.org/) - 保护您和用户隐私的网站分析工具（Google Analytics 的替代品）。 ([源代码](https://github.com/matomo-org/matomo)) `GPL-3.0` `PHP`
- [Medama Analytics](https://oss.medama.io) - 隐私优先的网站分析工具。轻量、简洁且无 Cookie。 ([演示](https://demo.medama.io), [源代码](https://github.com/medama-io/medama)) `Apache-2.0/MIT` `Docker/Go`
- [Metabase](https://metabase.com/) - 让公司所有人都能轻松提问并从数据中获取洞察的工具。 ([源代码](https://github.com/metabase/metabase)) `AGPL-3.0` `Java/Docker`
- [Middleware](https://middlewarehq.com/) - 旨在帮助工程领导者使用DORA指标衡量和分析团队效能的工具。 ([源代码](https://github.com/middlewarehq/middleware)) `Apache-2.0` `Docker/Python/Node.js`
- [Netron](https://netron.app/) - 神经网络和机器学习模型的可视化工具。 ([源代码](https://github.com/lutzroeder/netron)) `MIT` `Python/Node.js`
- [Offen](https://www.offen.dev/) - 公平、轻量级和开放的Web分析工具。在用户完全访问其数据的同时获取见解。 ([演示](https://www.offen.dev/try-demo/), [源代码](https://github.com/offen/offen)) `Apache-2.0` `Go/Docker`
- [Plausible Analytics](https://plausible.io/) - 简单、轻量（小于 1 KB）且注重隐私的 Web 分析工具。 ([源代码](https://github.com/plausible/analytics/)) `AGPL-3.0` `Elixir`
- [PostHog](https://posthog.com) - 可自托管的产品分析、会话录制、功能开关与 A/B 测试平台（Mixpanel、Amplitude、Heap、HotJar、Optimizely 的替代方案）。 ([源代码](https://github.com/posthog/posthog)) `MIT` `Python`
- [Postiz](https://postiz.com) `⚠` - 安排帖子发布，跟踪内容的表现，并在一个平台上管理所有社交媒体账户（Buffer、Hootsuite、Sprout Social 的替代品）。 ([源代码](https://github.com/gitroomhq/postiz-app)) `AGPL-3.0` `Docker`
- [Prisme Analytics](https://www.prismeanalytics.com) - 基于 Grafana、以隐私为核心的渐进式分析服务。 ([源代码](https://github.com/prismelabs/analytics)) `AGPL-3.0/MIT` `Docker`
- [Redash](http://redash.io) - 连接和查询您的数据源，构建可视化数据的仪表板，并与您的团队共享。 ([源代码](https://github.com/getredash/redash)) `BSD-2-Clause` `Docker`
- [Rybbit](https://rybbit.com/) - 易于部署且更直观的 Web 与产品分析工具（Google Analytics 的替代方案）。 ([演示](https://demo.rybbit.com/1), [源代码](https://github.com/rybbit-io/rybbit)) `AGPL-3.0` `Docker`
- [Shaper](https://taleshape.com/shaper/docs) - 纯用 SQL 构建数据仪表盘，由 DuckDB 驱动。 ([演示](https://demo.taleshape.com/view/pvggvdpiwb9wlyppuqbyx0nt), [源代码](https://github.com/taleshape-com/shaper)) `MPL-2.0` `Docker/Node.js/Python/Go`
- [Socioboard](https://github.com/socioboard/Socioboard-5.0) `⚠` - 支持九个社交媒体网络的社交媒体管理、分析和报告平台。 `GPL-3.0` `Node.js`
- [Statistics for Strava](https://github.com/robiningelbrecht/statistics-for-strava) `⚠` - 基于 Strava 数据生成的统计分析仪表盘。 ([演示](https://statistics-for-strava.robiningelbrecht.be/)) `AGPL-3.0` `Docker`
- [Superset](http://superset.apache.org/) - 现代数据探索和可视化平台。 ([源代码](https://github.com/apache/superset)) `Apache-2.0` `Python`
- [Swetrix](https://swetrix.com/) - 终极开源网络分析工具，满足您的所有需求。 ([演示](https://swetrix.com/projects/STEzHcB1rALV), [源代码](https://github.com/Swetrix/selfhosting)) `AGPL-3.0` `Docker`
- [Umami](https://umami.is/) - 简单、快速、注重隐私的Google Analytics替代方案。 ([演示](https://cloud.umami.is/share/LGazGOecbDtaIwDr), [源代码](https://github.com/umami-software/umami)) `MIT` `Node.js/Docker`
- [Vince](https://www.vinceanalytics.com/) - 网站分析与仪表盘（Google Analytics 替代品）。 ([源代码](https://github.com/vinceanalytics/vince)) `AGPL-3.0` `Go/Docker/K8S/deb`


### 制造业

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

用于管理[3D打印机](https://en.wikipedia.org/wiki/3D_printing)、[数控机床（CNC）](https://en.wikipedia.org/wiki/Numerical_control)和其他物理制造工具的软件。

- [CNCjs](https://cnc.js.org/) - 基于 Web 的 CNC 铣床控制器界面，支持 Grbl、Smoothieware 或 TinyG。 ([源代码](https://github.com/cncjs/cncjs/)) `MIT` `Node.js`
- [Fluidd](https://docs.fluidd.xyz/) - 用于Klipper 3D打印机固件的轻量且响应灵敏的用户界面。 ([源代码](https://github.com/fluidd-core/fluidd)) `GPL-3.0` `Docker/Node.js`
- [Mainsail](https://docs.mainsail.xyz/) - 适用于 Klipper 3D 打印机固件的现代化响应式用户界面，可在任意设备上随时随地控制和监控打印机。 ([源代码](https://github.com/mainsail-crew/mainsail)) `GPL-3.0` `Docker/Python`
- [Manyfold](https://manyfold.app) - 用于 3D 打印文件的数字资产管理器；支持 STL、OBJ、3MF 等格式。 ([源代码](https://github.com/manyfold3d/manyfold)) `MIT` `Docker`
- [OctoPrint](https://octoprint.org/) - 用于控制消费级 3D 打印机的快捷 Web 界面。 ([源代码](https://github.com/OctoPrint/OctoPrint)) `AGPL-3.0` `Docker/Python`


### 办公套件

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[办公套件](https://en.wikipedia.org/wiki/List_of_office_suites)是一套通常包含至少一个文字处理器、电子表格和演示程序的生产力软件集合。

- [Collabora Online Development Edition](https://www.collaboraoffice.com/code) - Collabora Online Development Edition (CODE) 是一个基于LibreOffice的强大的在线办公套件，支持所有主要的文档、电子表格和演示文件格式，可以集成到您自己的基础设施中。 ([源代码](https://cgit.freedesktop.org/libreoffice/online/)) `MPL-2.0` `C++`
- [CryptPad](https://cryptpad.org) - 一个协作套件，支持实时同步文档更改。 ([源代码](https://github.com/cryptpad/cryptpad)) `AGPL-3.0` `Node.js/Docker`
- [Digislides](https://ladigitale.dev/digislides/) - 快速轻松地创建多媒体演示文稿（文档为法语）。 ([演示](https://ladigitale.dev/digislides/), [源代码](https://codeberg.org/ladigitale/Digislides)) `AGPL-3.0` `Node.js/PHP`
- [Etherpad](https://etherpad.org/) - 高度可定制的在线编辑器，支持实时协作编辑。 ([演示](https://demo.sandstorm.io/appdemo/h37dm17aa89yrd8zuqpdn36p6zntumtv08fjpu8a8zrte7q1cn60), [源代码](https://github.com/ether/etherpad)) `Apache-2.0` `Node.js/Docker`
- [Grist](https://getgrist.com/) - 新一代电子表格，具有关系型结构、基于公式的访问控制和可移植的自包含格式（Airtable 的替代品）。 ([演示](https://docs.getgrist.com), [源代码](https://github.com/gristlabs/grist-core)) `Apache-2.0` `Node.js/Python/Docker`
- [ONLYOFFICE](https://helpcenter.onlyoffice.com/faq/server-opensource.aspx) - 办公套件，使您能够在一个地方管理文档、项目、团队和客户关系。 ([源代码](https://github.com/ONLYOFFICE/DocumentServer)) `AGPL-3.0` `Node.js/Docker`


### 协同办公

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

协作软件或[协作套件](https://en.wikipedia.org/wiki/Collaborative_software)旨在帮助从事共同任务的人实现其目标。协作套件通常将多个服务整合在一个统一的应用程序中，例如文件共享、日历/事件管理、约会安排、地址簿等。

_相关: [预订和日程安排](#预订和日程安排)_

- [Citadel](https://www.citadel.org/) - 包括电子邮件、日历/日程安排、通讯簿、论坛、邮件列表、即时消息、维基和博客引擎、RSS聚合等的团队协作软件。 ([源代码](https://www.citadel.org/source.html)) `GPL-3.0` `C/Docker/Shell`
- [Colanode](https://colanode.com) - 协作套件，具有实时消息传递、富文本页面、文件管理和动态数据库 - 为离线工作而构建（Slack、Notion 的替代品）。 ([源代码](https://github.com/colanode/colanode)) `Apache-2.0` `K8S/Docker`
- [Cozy Cloud](https://cozy.io/) - 个人云平台，您可以在其中管理和同步您的文件、笔记、联系人、密码和文档。 ([源代码](https://github.com/cozy/), [客户端](https://github.com/cozy/cozy-store)) `GPL-3.0` `Node.js`
- [Digipad](https://digipad.app/) - 用于创建协作数字记事本的在线自托管应用（文档以法语为主）。 ([源代码](https://codeberg.org/ladigitale/digipad)) `AGPL-3.0` `Node.js`
- [Digistorm](https://digistorm.app/) - 创建协作调查、测验、头脑风暴和词云（文档为法语）。 ([演示](https://digistorm.app/), [源代码](https://codeberg.org/ladigitale/digistorm)) `AGPL-3.0` `Node.js`
- [Digiwall](https://digiwall.app/) - 为面对面或远程工作创建多媒体协作墙（法语文档）. ([源代码](https://codeberg.org/ladigitale/digiwall)) `AGPL-3.0` `Node.js`
- [egroupware](https://www.egroupware.org/) - 软件套件包括日历、通讯录、记事本、项目管理工具、客户关系管理工具（CRM）、知识管理工具、维基和内容管理系统（CMS）。 ([源代码](https://github.com/EGroupware/egroupware)) `GPL-2.0` `PHP`
- [Group Office](https://www.group-office.com) - 企业级CRM和群件工具。与同事和客户在线共享项目、日历、文件和电子邮件。 ([源代码](https://github.com/Intermesh/groupoffice/)) `AGPL-3.0` `PHP`
- [Openmeetings](https://openmeetings.apache.org/index.html) - 使用 Red5 流媒体服务器的 API 功能实现视频会议、即时消息、白板、协作文档编辑及其他群组协作工具。 ([源代码](https://github.com/apache/openmeetings)) `Apache-2.0` `Java`
- [SOGo](https://www.sogo.nu/) - SOGo提供多种访问日历和消息数据的方式。支持CalDAV、CardDAV、GroupDAV，以及ActiveSync，包括原生Outlook兼容性和Web界面。 ([演示](https://demo.sogo.nu/SOGo/), [源代码](https://github.com/Alinto/sogo)) `LGPL-2.1` `Objective-C`
- [Tine](https://www.tine-groupware.de/) - 用于公司和组织的数字协作软件。从强大的团队协作功能到巧妙的附加组件，Tine集成了一切，以使日常团队协作更加轻松。 ([源代码](https://github.com/tine-groupware/tine)) `AGPL-3.0` `Docker`
- [Tracim](https://github.com/tracim/tracim) - 团队协作的协作平台：文件、讨论、笔记、日程等。 `AGPL-3.0/LGPL-3.0/MIT` `Python`
- [Zimbra Collaboration](https://www.zimbra.com/) - 具有Web界面和许多集成的电子邮件、日历、协作服务器。 ([源代码](https://github.com/zimbra)) `GPL-2.0/CPAL-1.0` `Java`


### 博客平台

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[博客](https://en.wikipedia.org/wiki/Blog)是由离散的、类日记式的文本条目（帖子）组成的讨论或信息性网站。

_相关: [静态网站生成器](#静态网站生成器), [内容管理系统（CMS）](#内容管理系统（cms）)_

_另见: [WeblogMatrix](https://www.weblogmatrix.org/)_

- [Antville](https://antville.org) - 一个旨在开发高性能、功能丰富的博客托管软件的免费、开源项目。 ([源代码](https://github.com/antville/antville)) `Apache-2.0` `JavaScript`
- [Castopod](https://castopod.org) - 播客管理和托管平台，支持最新的 Podcast 2.0 标准，自动化的 Fediverse 推送、分析工具、可嵌入播放器等功能。 ([源代码](https://code.castopod.org/adaures/castopod)) `AGPL-3.0` `PHP/Docker`
- [Chyrp Lite](https://chyrplite.net) - 额外强大、额外轻量级的博客引擎。 ([源代码](https://github.com/xenocrat/chyrp-lite)) `BSD-3-Clause` `PHP`
- [Dotclear](https://git.dotclear.org/dev/dotclear) - 在博客上拥有更多控制权。 `GPL-2.0` `PHP`
- [Ech0](https://github.com/lin-snow/Ech0) - 轻量级的联邦发布平台，专注于个人想法分享（文档为中文）。 ([演示](https://memo.vaaat.com/)) `AGPL-3.0` `Docker/K8S`
- [FlatPress](https://flatpress.org/) - 一款轻量、易于设置的平面文件博客引擎。 ([源代码](https://github.com/flatpressblog/flatpress)) `GPL-2.0` `PHP`
- [fx](https://github.com/rikhuijzer/fx) - 微博工具，提供内置语法高亮、移动发布等功能（Twitter、Bluesky 的替代方案）。 `MIT` `Docker`
- [Ghost](https://ghost.org/) - 仅仅是一个博客平台。 ([源代码](https://github.com/TryGhost/Ghost)) `MIT` `Node.js`
- [Haven](https://havenweb.org/) - 具有Markdown编辑和内置RSS阅读器的私人博客系统。 ([演示](https://havenweb.org/demo.html), [源代码](https://github.com/havenweb/haven)) `MIT` `Ruby`
- [HTMLy](https://www.htmly.com/) - 无需数据库的 PHP 博客平台。一个扁平文件 CMS，可让您在几秒钟内创建快速、安全且强大的站点或博客。 ([演示](http://demo.htmly.com/), [源代码](https://github.com/danpros/htmly)) `GPL-2.0` `PHP`
- [Known](https://withknown.com/) - 协作式社交发布平台。 ([源代码](https://github.com/idno/idno)) `Apache-2.0` `PHP`
- [Mataroa](https://mataroa.blog/) - 面向极简主义者的极简博客平台。 ([源代码](https://github.com/mataroablog/mataroa)) `MIT` `Python`
- [PluXml](https://pluxml.org) - 基于XML的博客/CMS平台。 ([源代码](https://github.com/pluxml/PluXml)) `GPL-3.0` `PHP`
- [Serendipity](https://docs.s9y.org/) - Serendipity (s9y) 是一个高度可扩展和可定制的 PHP 博客引擎，使用 Smarty 模板引擎。 ([源代码](https://github.com/s9y/serendipity)) `BSD-3-Clause` `PHP`
- [WriteFreely](https://writefreely.org) - 用于创建极简、联合的博客或整个社区的写作软件。 ([源代码](https://github.com/writefreely/writefreely)) `AGPL-3.0` `Go`


### 地图和全球定位系统（GPS）

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[地图](https://en.wikipedia.org/wiki/Map)、[制图学](https://en.wikipedia.org/wiki/Cartography)、[地理信息系统（GIS）](https://en.wikipedia.org/wiki/Geographic_information_system)和[全球定位系统（GPS）](https://en.wikipedia.org/wiki/Global_Positioning_System)软件。

_另见: [awesome-openstreetmap](https://github.com/osmlab/awesome-openstreetmap), [awesome-gis](https://github.com/sshuair/awesome-gis)_

- [AdventureLog](https://adventurelog.app) - 旅行跟踪器和行程规划器。 ([演示](https://demo.adventurelog.app/signup), [源代码](https://github.com/seanmorley15/AdventureLog)) `GPL-3.0` `Docker`
- [AirTrail](https://airtrail.johan.ohly.dk) - 个人飞行跟踪系统。 ([源代码](https://github.com/johanohly/AirTrail)) `GPL-3.0` `Docker/Node.js`
- [Bicimon](https://github.com/knrdl/bicimon) - 自行车速度计作为渐进式Web应用。 ([演示](https://knrdl.github.io/bicimon/)) `MIT` `JavaScript`
- [Dawarich](https://dawarich.app/) - 可视化您的位置历史，跟踪您的移动轨迹，并在完全隐私和控制下分析您的旅行模式（Google Timeline 或 Google 位置历史的替代方案）。 ([源代码](https://github.com/Freika/dawarich)) `AGPL-3.0` `Docker`
- [Geo2tz](https://github.com/noandrea/geo2tz) - 通过地理坐标（纬度、经度）获取时区。 `MIT` `Go/Docker`
- [GraphHopper](https://graphhopper.com/) - 使用OpenStreetMap的快速路由库和服务器。 ([源代码](https://github.com/graphhopper/graphhopper)) `Apache-2.0` `Java`
- [Nominatim](https://nominatim.org/) - 用于在OpenStreetMap数据上进行地理编码（地址 -> 坐标）和反向地理编码（坐标 -> 地址）的服务器应用程序。 ([源代码](https://github.com/osm-search/Nominatim)) `GPL-2.0` `C`
- [Open Source Routing Machine (OSRM)](http://project-osrm.org/) - 高性能路由引擎，设计用于运行在OpenStreetMap数据上，并提供HTTP API、C++库接口和Node.js包装器。 ([演示](https://map.project-osrm.org/), [源代码](https://github.com/Project-OSRM/osrm-backend)) `BSD-2-Clause` `C++`
- [OpenRouteService](https://openrouteservice.org/) - 提供路线导航、等时线、时间距离矩阵、路线优化等功能的路线服务。 ([演示](https://openrouteservice.org/dev/#/api-docs/introduction), [源代码](https://github.com/GIScience/openrouteservice)) `GPL-3.0` `Docker/Java`
- [OpenStreetMap](https://www.openstreetmap.org/) - 协作项目，创建一个免费可编辑的世界地图。 ([源代码](https://github.com/openstreetmap/openstreetmap-website), [客户端](https://wiki.openstreetmap.org/wiki/Software)) `GPL-2.0` `Ruby`
- [OpenTripPlanner](https://www.opentripplanner.org/) - 基于OpenStreetMap数据的多模式旅行规划软件，使用发布的GTFS格式数据来建议使用本地公共交通系统的路线。 ([源代码](https://github.com/opentripplanner/OpenTripPlanner)) `LGPL-3.0` `Java/JavaScript`
- [OwnTracks Recorder](https://github.com/owntracks/recorder) `⚠` - 存储并访问由[OwnTracks](https://owntracks.org/)位置跟踪应用发布的数据。 `GPL-2.0` `C/Lua/deb/Docker`
- [TileServer GL](https://tileserver.readthedocs.io/) - 使用 GL 样式的矢量和栅格地图。由 Mapbox GL Native 进行服务器端渲染。适用于 Mapbox GL JS、Android、iOS、Leaflet、OpenLayers、通过 WMTS 的 GIS 等的地图切片服务器。 ([源代码](https://github.com/maptiler/tileserver-gl)) `BSD-2-Clause` `Node.js/Docker`
- [Traccar](https://www.traccar.org/) - 用于追踪GPS位置的Java应用。支持大量追踪设备和协议，具有Android和iOS应用程序。拥有Web界面，可查看您的行程。 ([演示](https://demo.traccar.org/), [源代码](https://github.com/traccar)) `Apache-2.0` `Java`
- [TRIP](https://itskovacs-trip.netlify.app/) - 极简 POI 地图追踪与行程规划工具。 ([演示](https://itskovacs-trip.netlify.app/home), [源代码](https://github.com/itskovacs/trip)) `MIT` `Docker`
- [wanderer](https://github.com/open-wanderer/wanderer) - 轨迹数据库，可上传记录的轨迹或新建轨迹，并添加多种元数据，构建易于检索的目录。 ([演示](https://demo.wanderer.to)) `AGPL-3.0` `Docker/Go/Node.js`


### 备份

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[备份](https://en.wikipedia.org/wiki/Backup)软件。

_相关: [档案和数字保存（DP）](#档案和数字保存（dp）)_

- [Backrest](https://garethgeorge.github.io/backrest/) - restic 备份的 Web UI 和编排器。 ([源代码](https://github.com/garethgeorge/backrest)) `GPL-3.0` `Docker/Go`
- [Backupninja](https://0xacab.org/liberate/backupninja) - 轻量级、可扩展的元备份系统，提供集中方式配置和协调多种备份工具。 `GPL-2.0` `Shell`
- [Bareos](https://www.bareos.org/) - 跨网络备份解决方案，可对所有主流操作系统的数据进行保存、归档和恢复。 ([源代码](https://github.com/bareos/bareos)) `AGPL-3.0` `C++/C`
- [Barman](https://pgbarman.org) - PostgreSQL 的备份和恢复管理器。 ([源代码](https://github.com/EnterpriseDB/barman)) `GPL-3.0` `Python`
- [BorgBackup](https://www.borgbackup.org/) - 支持去重、压缩和认证加密的归档工具。 ([源代码](https://github.com/borgbackup/borg)) `BSD-3-Clause` `Python`
- [Burp](https://burp.grke.org/) - 网络备份和恢复程序。 ([源代码](https://github.com/grke/burp)) `AGPL-3.0` `C`
- [Dar](http://dar.linux.free.fr/) - Disk ARchive，功能丰富、健壮的归档和备份软件，类似 tar。 ([源代码](https://github.com/Edrusb/DAR)) `GPL-2.0` `C++`
- [Databasus](https://databasus.com/) - 支持 PostgreSQL、MySQL、MariaDB 和 MongoDB 的备份工具，提供 Web UI、外部存储（本地、S3、FTP、Google Drive 等）、通知（webhook、Discord、Slack 等）及团队管理功能。 ([源代码](https://github.com/databasus/databasus)) `Apache-2.0` `Docker`
- [Duplicati](https://www.duplicati.com) - 备份客户端，可将加密、增量、压缩的备份安全地存储到云存储服务和远程文件服务器。 ([源代码](https://github.com/duplicati/duplicati)) `LGPL-2.1` `C#`
- [Duplicity](https://duplicity.gitlab.io/) - 使用 rsync 算法的加密高效带宽备份工具。 ([源代码](https://gitlab.com/duplicity/duplicity)) `GPL-2.0` `Python`
- [Minarca](https://minarca.org/) - 客户端-服务器备份平台，提供集中式 Web 控制台，支持通过 GUI 或 CLI 管理和恢复 Linux、Windows 和 macOS 备份。 ([源代码](https://gitlab.com/ikus-soft/minarca)) `AGPL-3.0` `Python`
- [Portabase](https://portabase.io/) - 服务器仪表盘工具，简化数据库实例的备份与恢复操作。 ([源代码](https://github.com/Portabase/portabase)) `Apache-2.0` `Docker`
- [Proxmox Backup Server](https://www.proxmox.com/en/proxmox-backup-server) - 企业级、客户端-服务器架构的备份解决方案，可备份虚拟机、容器和物理主机。 ([源代码](https://git.proxmox.com/?p=proxmox-backup.git;a=tree)) `GPL-3.0` `Rust`
- [rclone](https://rclone.org/) - 命令行程序，用于在不同云存储提供商之间同步文件和目录。 ([源代码](https://github.com/rclone/rclone)) `MIT` `Go`
- [Rdiff-backup](https://rdiff-backup.net/) - 反向增量备份工具，可通过网络或本地使用。 ([源代码](https://github.com/rdiff-backup/rdiff-backup)) `GPL-2.0` `Python`
- [Restic](https://restic.net/) - 简单、快速、可验证、安全且高效的远程备份工具。 ([源代码](https://github.com/restic/restic)) `BSD-2-Clause` `Go`
- [Rsnapshot](https://rsnapshot.org/) - 基于 rsync 的文件系统快照工具。 ([源代码](https://github.com/rsnapshot/rsnapshot)) `GPL-2.0` `Perl`
- [Shield](https://github.com/shieldproject/shield) - 数据库系统备份与恢复的可插拔架构。 `MIT` `Go`
- [UrBackup](https://www.urbackup.org/) - 面向 Windows、MacOS 和 Linux 的开源客户端/服务器网络备份。 ([源代码](https://github.com/uroni/urbackup_backend)) `AGPL-3.0` `C/C++`


### 备份

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[备份](https://en.wikipedia.org/wiki/Backup) 软件。

- [Backrest](https://garethgeorge.github.io/backrest/) - restic 备份的 Web UI 和编排器。 ([源代码](https://github.com/garethgeorge/backrest)) `GPL-3.0` `Docker/Go`
- [Backupninja](https://0xacab.org/liberate/backupninja) - 轻量级、可扩展的元备份系统，提供集中方式配置和协调多种备份工具。 `GPL-2.0` `Shell`
- [Bareos](https://www.bareos.org/) - 跨网络备份解决方案，可对所有主流操作系统的数据进行保存、归档和恢复。 ([源代码](https://github.com/bareos/bareos)) `AGPL-3.0` `C++/C`
- [Barman](https://pgbarman.org) - PostgreSQL 的备份和恢复管理器。 ([源代码](https://github.com/EnterpriseDB/barman)) `GPL-3.0` `Python`
- [BorgBackup](https://www.borgbackup.org/) - 支持去重、压缩和认证加密的归档工具。 ([源代码](https://github.com/borgbackup/borg)) `BSD-3-Clause` `Python`
- [Burp](https://burp.grke.org/) - 网络备份和恢复程序。 ([源代码](https://github.com/grke/burp)) `AGPL-3.0` `C`
- [Dar](http://dar.linux.free.fr/) - Disk ARchive，功能丰富、健壮的归档和备份软件，类似 tar。 ([源代码](https://github.com/Edrusb/DAR)) `GPL-2.0` `C++`
- [Databasus](https://databasus.com/) - 支持 PostgreSQL、MySQL、MariaDB 和 MongoDB 的备份工具，提供 Web UI、外部存储（本地、S3、FTP、Google Drive 等）、通知（webhook、Discord、Slack 等）及团队管理功能。 ([源代码](https://github.com/databasus/databasus)) `Apache-2.0` `Docker`
- [Duplicati](https://www.duplicati.com) - 备份客户端，可将加密、增量、压缩的备份安全地存储到云存储服务和远程文件服务器。 ([源代码](https://github.com/duplicati/duplicati)) `LGPL-2.1` `C#`
- [Duplicity](https://duplicity.gitlab.io/) - 使用 rsync 算法的加密高效带宽备份工具。 ([源代码](https://gitlab.com/duplicity/duplicity)) `GPL-2.0` `Python`
- [Minarca](https://minarca.org/) - 客户端-服务器备份平台，提供集中式 Web 控制台，支持通过 GUI 或 CLI 管理和恢复 Linux、Windows 和 macOS 备份。 ([源代码](https://gitlab.com/ikus-soft/minarca)) `AGPL-3.0` `Python`
- [Portabase](https://portabase.io/) - 服务器仪表盘工具，简化数据库实例的备份与恢复操作。 ([源代码](https://github.com/Portabase/portabase)) `Apache-2.0` `Docker`
- [Proxmox Backup Server](https://www.proxmox.com/en/proxmox-backup-server) - 企业级、客户端-服务器架构的备份解决方案，可备份虚拟机、容器和物理主机。 ([源代码](https://git.proxmox.com/?p=proxmox-backup.git;a=tree)) `GPL-3.0` `Rust`
- [rclone](https://rclone.org/) - 命令行程序，用于在不同云存储提供商之间同步文件和目录。 ([源代码](https://github.com/rclone/rclone)) `MIT` `Go`
- [Rdiff-backup](https://rdiff-backup.net/) - 反向增量备份工具，可通过网络或本地使用。 ([源代码](https://github.com/rdiff-backup/rdiff-backup)) `GPL-2.0` `Python`
- [Restic](https://restic.net/) - 简单、快速、可验证、安全且高效的远程备份工具。 ([源代码](https://github.com/restic/restic)) `BSD-2-Clause` `Go`
- [Rsnapshot](https://rsnapshot.org/) - 基于 rsync 的文件系统快照工具。 ([源代码](https://github.com/rsnapshot/rsnapshot)) `GPL-2.0` `Perl`
- [Shield](https://github.com/shieldproject/shield) - 数据库系统备份与恢复的可插拔架构。 `MIT` `Go`
- [UrBackup](https://www.urbackup.org/) - 面向 Windows、MacOS 和 Linux 的开源客户端/服务器网络备份。 ([源代码](https://github.com/uroni/urbackup_backend)) `AGPL-3.0` `C/C++`


### 媒体管理

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[数字媒体](https://en.wikipedia.org/wiki/Digital_media)管理工具和软件。

_相关: [自动化](#自动化), [流媒体](#流媒体), [流媒体 - 音频流媒体](#流媒体---音频流媒体), [流媒体 - 多媒体流媒体](#流媒体---多媒体流媒体), [流媒体 - 视频流媒体](#流媒体---视频流媒体)_

- [ChannelTube](https://github.com/TheWicklowWolf/ChannelTube) `⚠` - 使用 yt-dlp 定期从 YouTube 频道下载视频或音频。 `AGPL-3.0` `Docker`
- [Deleterr](https://github.com/rfsbraz/deleterr) - 自动化媒体清理工具，根据可配置的规则从 Plex、Sonarr 和 Radarr 中删除已看过和陈旧的内容。 `MIT` `Docker`
- [Downtify](https://downtify.henriquesebastiao.com) `⚠` - 下载 Spotify 音乐并保留专辑封面和元数据。 ([源代码](https://github.com/henriquesebastiao/downtify)) `GPL-3.0` `Docker`
- [Lidarr](https://lidarr.audio/) - 面向 Usenet 和 BitTorrent 用户的音乐收藏管理器。 ([源代码](https://github.com/Lidarr/Lidarr)) `GPL-3.0` `C#/Docker`
- [LidaTube](https://github.com/TheWicklowWolf/LidaTube) `⚠` - 通过 yt-dlp 查找和获取缺失的 Lidarr 专辑。 `GPL-3.0` `Docker`
- [Lidify](https://github.com/TheWicklowWolf/Lidify) `⚠` - 一款基于选定的 Lidarr 艺术家提供推荐的音乐发现工具，使用 Spotify 或 LastFM。 `MIT` `Docker`
- [Medusa](https://github.com/pymedusa/Medusa) - 自动化的视频库管理器，专为电视剧集设计。它会监控你喜欢的剧集的新剧集发布，并在发布时自动处理相关任务。 ([客户端](https://github.com/medusajs/nextjs-starter-medusa)) `GPL-3.0` `Python`
- [MeTube](https://github.com/alexta69/metube) - 用于 youtube-dl 的 Web 图形用户界面，支持播放列表。允许从数十个网站下载视频。 `AGPL-3.0` `Python/Node.js/Docker`
- [MKVPriority](https://github.com/kennethsible/mkvpriority) - 使用可配置的优先级评分选择首选音频和字幕轨道，并设置相应的默认和强制标志。 `MIT` `Python/Docker`
- [MyTube](https://github.com/franklioxygen/MyTube) `⚠` - 支持 yt-dlp 的视频下载器和播放器，带有频道订阅、云端上传支持和本地媒体库管理功能。 ([演示](https://mytube-demo.vercel.app)) `MIT` `Node.js/Docker`
- [nefarious](https://lardbit.github.io/nefarious/) - 自动下载电影和电视剧。 ([源代码](https://github.com/lardbit/nefarious)) `GPL-3.0` `Python`
- [Ombi](https://ombi.io/) - 适用于 Plex/Emby 的内容请求系统，可连接 SickRage、CouchPotato、Sonarr，功能不断增长。 ([演示](https://app.ombi.io/), [源代码](https://github.com/Ombi-app/Ombi)) `GPL-2.0` `C#/deb`
- [Pinchflat](https://github.com/kieraneglin/pinchflat) `⚠` - 使用 yt-dlp 构建的 YouTube 内容下载工具。 `AGPL-3.0` `Docker`
- [PodFetch](https://samtv12345.github.io/PodFetch) - 简洁高效的播客下载器。 ([源代码](https://github.com/SamTV12345/PodFetch)) `Apache-2.0` `Docker/Rust`
- [Radarr](https://radarr.video/) - 通过 Usenet 和 BitTorrent 自动下载电影（Sonarr 的分支）。 ([源代码](https://github.com/Radarr/Radarr)) `GPL-3.0` `C#/Docker`
- [Reaparr](https://www.reaparr.rocks/) `⚠` - 跨平台 Plex 媒体下载器，可将其他 Plex 服务器的媒体无缝添加到你的服务器中。 ([源代码](https://github.com/Reaparr/Reaparr)) `GPL-3.0` `Docker`
- [Seerr](https://github.com/seerr-team/seerr) - 管理你的媒体库请求，支持 Plex、Jellyfin 和 Emby 媒体服务器（Overseerr 的分支）。 `MIT` `Docker/Node.js`
- [Sonarr](https://sonarr.tv/) - 自动化的电视剧下载和管理工具，适用于Usenet和BitTorrent。它能够获取、排序和重命名新的剧集，并在更高质量的格式可用时自动提升已下载文件的质量。 ([源代码](https://github.com/Sonarr/Sonarr)) `GPL-3.0` `C#/Docker`
- [TrackWatch](https://trackwatch.emlopezr.com) `⚠` - Spotify 自动音乐发行追踪器，支持邮件通知、唱片集生成和无效曲目清理（Release Radar 替代品）。 ([源代码](https://github.com/emlopezr/trackwatch)) `MIT` `Docker`
- [tubesync](https://github.com/meeb/tubesync) `⚠` - 将YouTube频道和播放列表同步到本地托管的媒体服务器。 `AGPL-3.0` `Docker/Python`
- [Watcharr](https://github.com/sbondCo/Watcharr) - 添加并跟踪你正在观看的所有剧集和电影。支持用户认证，拥有现代简洁的界面，并且设置非常简单。 ([演示](https://beta.watcharr.app/)) `MIT` `Docker`
- [ydl_api_ng](https://github.com/Totonyus/ydl_api_ng) - 简单的youtube-dl REST API，用于在远程服务器上启动下载。 `GPL-3.0` `Python`
- [Youtarr](https://github.com/DialmasterOrg/Youtarr) `⚠` - 通过 yt-dlp 按计划从 YouTube 频道下载视频，带有 Web UI 供浏览和选择性下载，支持 Plex 集成和 Jellyfin/Kodi/Emby 的 NFO 元数据生成。 `ISC` `Docker`
- [YoutubeDL-Server](https://github.com/nbr23/youtube-dl-server) - Youtube-DL 的 Web 和 REST 接口，用于将视频下载到服务器上。 `MIT` `Python/Docker`
- [yt-dlp Web UI](https://github.com/marcopiovanello/yt-dlp-web-ui) - yt-dlp 的网页图形界面。 `MPL-2.0` `Docker/Go/Node.js`


### 学习和课程

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

用于辅助教育和学习的工具和软件。

- [Canvas LMS](https://www.instructure.com/canvas/) - 革命性地改变教育方式的学习管理系统（LMS）。 ([演示](https://canvas.instructure.com/), [源代码](https://github.com/instructure/canvas-lms)) `AGPL-3.0` `Ruby`
- [Chamilo LMS](https://chamilo.org/) - 创建一个虚拟校园，用于提供在线或半在线培训。 ([源代码](https://github.com/chamilo/chamilo-lms)) `GPL-3.0` `PHP`
- [Digiscreen](https://ladigitale.dev/digiscreen/) - 课堂交互式白板/墙纸，支持远程和面对面教学（法语文档）。 ([演示](https://ladigitale.dev/digiscreen/), [源代码](https://codeberg.org/ladigitale/digiscreen)) `AGPL-3.0` `Node.js/PHP`
- [Digitools](https://ladigitale.dev/digitools) - 一套简单的工具，用于支持远程或面对面课程的动画教学（法语文档）. ([演示](https://ladigitale.dev/digitools/), [源代码](https://codeberg.org/ladigitale/digitools)) `AGPL-3.0` `PHP`
- [edX](https://www.edx.org/) - Open edX平台是edX.org的开源代码。 ([源代码](https://github.com/edx/)) `AGPL-3.0` `Python`
- [Gibbon](https://gibbonedu.org/) - 灵活的学校管理平台，旨在让教师、学生、家长和管理者的生活更美好。 ([源代码](https://github.com/GibbonEdu/core)) `GPL-3.0` `PHP`
- [Helium](https://www.heliumedu.com) - 学生课程规划工具，支持彩色编码的作业、成绩和笔记管理，带智能通知和多设备同步。 ([演示](https://app.heliumedu.com), [源代码](https://github.com/HeliumEdu/platform)) `MIT` `Python/Docker`
- [ILIAS](https://www.ilias.de) - 能够应对各种需求的学习管理系统。 ([演示](https://demo.ilias.de), [源代码](https://github.com/ILIAS-eLearning/ILIAS)) `GPL-3.0` `PHP`
- [INGInious](https://inginious.org/?lang=en) - 智能评分系统，允许对学生编写的代码进行安全且自动化的测试。 ([源代码](https://github.com/INGInious/INGInious), [客户端](https://github.com/INGInious/plugins)) `AGPL-3.0` `Python/Docker`
- [Moodle](https://moodle.org/) - 学习与课程平台，拥有全球最大的开源社区之一。 ([演示](https://moodle.org/demo/), [源代码](https://git.moodle.org/gw)) `GPL-3.0` `PHP`
- [Open eClass](https://www.openeclass.org/) - Open eClass是一种先进的电子学习解决方案，可以增强教学和学习过程。 ([演示](https://demo.openeclass.org/), [源代码](https://github.com/gunet/openeclass)) `GPL-2.0` `PHP`
- [OpenOLAT](https://www.openolat.com/?lang=en) - 用于教学、教育、评估和沟通的学习管理系统。 ([演示](https://learn.olat.com), [源代码](https://github.com/OpenOLAT/OpenOLAT)) `Apache-2.0` `Java`
- [QST](https://qstonline.org) - 在线评估软件。从手机上的快速测验到大规模、高风险的监考桌面测试，简便、安全且经济实惠。 ([演示](https://qstonline.org/free_account.htm), [源代码](https://sourceforge.net/projects/qstonline/)) `GPL-2.0` `Perl`
- [RELATE](https://documen.tician.de/relate/) - 课程管理套件，包含灵活规则、统计、多课程支持、课程日历等功能。 ([源代码](https://github.com/inducer/relate)) `MIT` `Python`
- [RosarioSIS](https://www.rosariosis.org/) - 用于学校管理的学生信息系统。包含学生人口统计、成绩、排课、考勤、学生账单、纪律与餐饮等模块。 ([演示](https://www.rosariosis.org/demo/), [源代码](https://gitlab.com/francoisjacquet/rosariosis/)) `GPL-2.0` `PHP`


### 客户关系管理（CRM）

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[客户关系管理 (CRM)](https://en.wikipedia.org/wiki/Customer_relationship_management) 是组织用来管理、分析和改善与客户互动的战略过程。

_相关: [通信 - 电子邮件 - 邮件列表和通讯](#通信---电子邮件---邮件列表和通讯), [分析](#分析), [日历和联系人](#日历和联系人)_

- [Corteza](https://docs.cortezaproject.org) - 包含统一工作区、企业消息和低代码环境的CRM，可快速且安全地交付基于记录的管理解决方案。 ([演示](https://latest.cortezaproject.org), [源代码](https://github.com/cortezaproject/corteza)) `Apache-2.0` `Go`
- [Django-CRM](https://DjangoCRM.github.io/info/) - 带有任务管理、邮件营销等功能的分析型 CRM。Django CRM 适用于个人使用、各类规模的企业或自由职业者，设计上支持轻松定制和快速开发。 ([源代码](https://github.com/DjangoCRM/django-crm)) `AGPL-3.0` `Python`
- [EspoCRM](https://www.espocrm.com/) - 具有设计为单页应用程序的前端和REST API的CRM系统。 ([演示](https://demo.espocrm.com/), [源代码](https://github.com/espocrm/espocrm)) `AGPL-3.0` `PHP`
- [Krayin](https://krayincrm.com/) - 中小型企业和大型企业的CRM解决方案，提供完整的客户生命周期管理。 ([演示](https://demo.krayincrm.com/), [源代码](https://github.com/krayin/laravel-crm)) `MIT` `PHP`
- [Monica](https://monicahq.com/) - 个人关系管理器，一种新型的 CRM，用于组织与您的朋友和家人的互动。 ([源代码](https://github.com/monicahq/monica)) `AGPL-3.0` `PHP/Docker`
- [SuiteCRM](https://suitecrm.com) - 获奖的企业级开源客户关系管理系统。 ([源代码](https://github.com/SuiteCRM/SuiteCRM)) `AGPL-3.0` `PHP`
- [Twenty](https://twenty.com) - 一个现代化的CRM，提供开源的灵活性、先进的功能和时尚的设计。 ([源代码](https://github.com/twentyhq/twenty)) `AGPL-3.0` `Docker`


### 家谱研究

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[家谱软件](https://en.wikipedia.org/wiki/Genealogy_software)，用于记录、组织和发布家谱数据。

- [Genea.app](https://www.genea.app/) - 一款注重隐私的家谱工具，任何人都可以用来创建或编辑家谱。数据以 GEDCOM 格式存储，所有处理均在浏览器中完成。 ([源代码](https://github.com/genea-app/genea-app)) `MIT` `JavaScript`
- [Genealogy](https://genealogy.kreaweb.be/) - 记录家庭成员及其关系并构建家谱。 ([演示](https://genealogy.kreaweb.be/), [源代码](https://github.com/MGeurts/genealogy)) `MIT` `PHP`
- [GeneWeb](https://geneweb.tuxfamily.org/wiki/GeneWeb) - 可以离线使用或作为 Web 服务使用的家谱软件。 ([源代码](https://github.com/geneweb/geneweb)) `GPL-2.0` `OCaml`
- [Gramps Web](https://www.grampsweb.org/) - 用于协同基于Gramps的家谱研究的Web应用，与Gramps开源家谱研究桌面应用兼容。 ([演示](https://gramps-project.github.io/gramps-web-api/), [源代码](https://github.com/gramps-project/gramps-web-api)) `AGPL-3.0` `Docker`
- [webtrees](https://www.webtrees.net) - Webtrees是Web上领先的在线协作家谱应用程序。 ([演示](https://dev.webtrees.net/demo-stable/index.php?ctype=gedcom&ged=demo), [源代码](https://github.com/fisharebest/webtrees)) `GPL-3.0` `PHP`


### 密码管理器

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[密码管理器](https://en.wikipedia.org/wiki/Password_manager)允许用户存储、生成和管理他们在本地应用程序和在线服务中的密码。

- [AliasVault](https://www.aliasvault.net) - 端到端加密的密码管理器，内置电子邮件别名生成器和服务器。 ([源代码](https://github.com/aliasvault/aliasvault)) `MIT` `Docker`
- [Bitwarden](https://bitwarden.com/) `⚠` - 带有网页应用、浏览器扩展和移动应用的密码管理器。 ([源代码](https://github.com/bitwarden/server)) `AGPL-3.0` `Docker/C#`
- [Passbolt](https://www.passbolt.com/) - 协作式密码管理器。 ([源代码](https://github.com/passbolt/passbolt_api)) `AGPL-3.0` `PHP/deb/K8S/Docker`
- [PassIt](https://passit.io/) - 简单的密码管理工具，具有按组和用户共享的功能，但没有管理界面。 ([演示](https://app.passit.io/), [源代码](https://gitlab.com/passit)) `AGPL-3.0` `Docker/Python`
- [Psono](https://psono.com/) - 面向企业的密码管理器。 ([演示](https://www.psono.pw), [源代码](https://gitlab.com/esaqa/psono/psono-fileserver)) `Apache-2.0` `Python`
- [Teampass](https://teampass.net/) - 专为以协作方式管理密码而设计的密码管理器。使用一个对称密钥加密所有共享/团队密码，并在服务器端以文件和数据库的形式存储。适用于任何 Apache、MySQL 和 PHP 服务器。 ([源代码](https://github.com/nilsteampassnet/TeamPass)) `GPL-3.0` `PHP`
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) - 用Rust编写的轻量级Bitwarden服务器API实现。 `GPL-3.0` `Rust/Docker`


### 工单

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[帮助台](https://en.wikipedia.org/wiki/Help_desk_software)、[缺陷](https://en.wikipedia.org/wiki/Bug_tracking_system)和[问题](https://en.wikipedia.org/wiki/Issue_tracking_system)跟踪软件，用于跟踪用户请求、缺陷和缺失的功能。

_相关: [任务管理和待办清单](#任务管理和待办清单), [软件开发 - 项目管理](#软件开发---项目管理)_

- [Bugzilla](https://www.bugzilla.org/) - 通用缺陷跟踪器和测试工具，最初由Mozilla项目开发和使用。 ([源代码](https://github.com/bugzilla/bugzilla)) `MPL-2.0` `Perl`
- [Frappe Helpdesk](https://frappe.io/helpdesk) - 帮助台软件，帮助您简化公司的支持、提供简单的设置、干净的用户界面和自动化工具来高效解决客户查询。 ([源代码](https://github.com/frappe/helpdesk)) `AGPL-3.0` `Docker`
- [FreeScout](https://freescout.net/) - 基于电子邮件的客户支持应用、工单系统和共享邮箱（Zendesk 和 Help Scout 的替代品）。 ([演示](https://demo.freescout.net/login), [源代码](https://github.com/freescout-help-desk/freescout)) `AGPL-3.0` `PHP/Docker`
- [GlitchTip](https://glitchtip.com) - 用于收集应用程序错误报告的错误跟踪应用。 ([源代码](https://gitlab.com/glitchtip/glitchtip)) `MIT` `Python/Docker/K8S`
- [ITFlow](https://itflow.org) - 面向MSP（托管服务提供商）的客户IT文档、工单、发票和会计管理。 ([演示](https://demo.itflow.org), [源代码](https://github.com/itflow-org/itflow)) `GPL-3.0` `PHP`
- [Libredesk](https://libredesk.io/) - 现代化全渠道客户支持平台，支持实时聊天、电子邮件等，单二进制文件应用。 ([演示](https://demo.libredesk.io), [源代码](https://github.com/abhinavxd/libredesk)) `AGPL-3.0` `Docker/Go/Node.js`
- [MantisBT](https://www.mantisbt.org/) - 缺陷追踪工具，最适合软件开发场景。 ([演示](https://www.mantisbt.org/bugs/my_view_page.php), [源代码](https://github.com/mantisbt/mantisbt)) `GPL-2.0` `PHP`
- [OTOBO](https://otobo.io/en/) - 灵活的基于 Web 的工单系统，用于客户服务、帮助台和 IT 服务管理。 ([演示](https://otobo.io/en/service-management-plattform/otobo-demo/), [源代码](https://github.com/RotherOSS/otobo)) `GPL-3.0` `Perl/Docker`
- [Request Tracker](https://www.bestpractical.com/rt/) - 企业级问题跟踪系统。 ([源代码](https://github.com/bestpractical/rt)) `GPL-2.0` `Perl`
- [Roundup Issue Tracker](https://www.roundup-tracker.org/) - 易用易装的问题跟踪系统，支持命令行、Web、REST、XML-RPC 和电子邮件接口。注重灵活性设计，不只是另一个缺陷跟踪器。 ([源代码](https://www.roundup-tracker.org/code.html)) `MIT/ZPL-2.0` `Python/Docker`
- [Zammad](https://zammad.org/) - 易于使用但功能强大的开源支持和工单系统。 ([源代码](https://github.com/zammad/zammad)) `AGPL-3.0` `Ruby/deb`


### 库存管理

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[库存管理软件](https://en.wikipedia.org/wiki/Inventory_management_software)。

_相关: [资金、预算和管理](#资金、预算和管理), [资源规划](#资源规划)_

_另见: [awesome-sysadmin/IT资产管理](https://github.com/awesome-foss/awesome-sysadmin#it-asset-management)_

- [Cannery](https://cannery.app) - 枪支和弹药追踪应用。 ([源代码](https://codeberg.org/shibao/cannery)) `AGPL-3.0` `Docker`
- [HomeBox (SysAdminsMedia)](https://homebox.software/) - 为家庭用户打造的库存和组织管理系统。 ([演示](https://demo.homebox.software/), [源代码](https://github.com/sysadminsmedia/homebox)) `AGPL-3.0` `Docker/Go`
- [Inventaire](https://inventaire.io/welcome) - 协作资源映射项目，目前仅专注于使用Wikidata和ISBN探索图书映射。 ([源代码](https://codeberg.org/inventaire/inventaire)) `AGPL-3.0` `Node.js`
- [Inventree](https://docs.inventree.org/en/latest/) - 提供直观零件管理和库存控制的库存管理系统。 ([演示](https://inventree.org/demo), [源代码](https://github.com/inventree/InvenTree)) `MIT` `Python`
- [Open QuarterMaster](https://openquartermaster.com/) - 强大的库存管理系统，设计上具有灵活性和可扩展性。 ([源代码](https://github.com/Epic-Breakfast-Productions/OpenQuarterMaster)) `GPL-3.0` `deb/Docker`
- [Part-DB](https://docs.part-db.de/) - 用于电子元器件的库存管理系统。 ([演示](https://demo.part-db.de/en/), [源代码](https://github.com/Part-DB/Part-DB-server)) `AGPL-3.0` `Docker/PHP/Node.js`
- [Shelf](https://www.shelf.nu) - 团队喜欢清晰度的资产和设备跟踪软件。Shelf 是一个资产数据库和 QR 资产标签生成器，让您能够在不同地点创建、管理和查看您的资产。无限资产，永久免费使用。 ([源代码](https://github.com/Shelf-nu/shelf.nu)) `AGPL-3.0` `Node.js`
- [Spoolman](https://github.com/Donkie/Spoolman) - 管理和追踪你的 3D 打印机耗材线轴库存。 `MIT` `Docker/Python`


### 打包

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[包管理器](https://en.wikipedia.org/wiki/Package_manager)或包管理系统是一组自动化安装、升级、配置和卸载计算机程序的软件工具，以一致的方式管理计算机上的软件。

- [aptly](https://www.aptly.info/) - Debian 仓库管理的瑞士军刀。 ([源代码](https://github.com/aptly-dev/aptly)) `MIT` `Go`
- [fpm](https://fpm.readthedocs.io/en/latest/) - 多格式通用包创建工具。 ([源代码](https://github.com/jordansissel/fpm)) `MIT` `Ruby`
- [omnibus-ruby](https://github.com/chef/omnibus) - 跨平台轻松为项目创建全栈安装包。 `Apache-2.0` `Ruby`
- [tito](https://github.com/dgoodwin/tito) - 为基于 git 的项目构建 RPM 包。 `GPL-2.0` `Python`


### 投票和事件

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

用于组织[投票](https://en.wikipedia.org/wiki/Opinion_poll)和[事件](https://en.wikipedia.org/wiki/Event)的软件。

_相关: [预订和日程安排](#预订和日程安排)_

- [Bitpoll](https://github.com/fsinfuhh/Bitpoll) - 用于日期、时间或一般问题的投票调查。 ([演示](https://bitpoll.de/)) `GPL-3.0` `Docker/Python`
- [Bracket](https://docs.bracketapp.nl/) - 灵活的比赛系统可以建立比赛安排，添加队伍，安排比赛时间，跟踪比分，并将排名实时呈现给公众。 ([演示](https://www.bracketapp.nl/demo), [源代码](https://github.com/evroon/bracket)) `AGPL-3.0` `Docker/Node.js`
- [Christmas Community](https://github.com/Wingysam/Christmas-Community) - 创建一个简单的地方，让您的整个家庭用于查找人们想要的礼物，并避免重复赠送。 `AGPL-3.0` `Docker/Node.js`
- [Claper](https://claper.co/) - 与观众互动的终极工具（替代Slido、AhaSlides和Mentimeter）。 ([源代码](https://github.com/ClaperCo/Claper)) `GPL-3.0` `Elixir/Docker`
- [ClearFlask](https://clearflask.com) - 用于管理反馈并优先处理公共路线图的社区反馈工具（替代Canny、UserVoice、Upvoty）。 ([演示](https://product.clearflask.com), [源代码](https://github.com/clearflask/clearflask)) `AGPL-3.0` `Docker`
- [docassemble](https://docassemble.org/) - 一个用于引导性访谈和文档生成的免费、开源的专家系统，基于Python、YAML和Markdown。 ([演示](https://demo.docassemble.org/run/legal), [源代码](https://github.com/jhpyle/docassemble)) `MIT` `Docker/Python`
- [Fider](https://fider.io) - 开放平台，用于收集和优先处理反馈（与UserVoice的替代方案）。 ([演示](https://demo.fider.io), [源代码](https://github.com/getfider/fider)) `MIT` `Docker`
- [Formbricks](https://formbricks.com) - 建立在全球最大开源调查堆栈上的体验管理套件。在客户旅程的每一步优雅地收集反馈，了解您的客户需求。 ([演示](https://app.formbricks.com), [源代码](https://github.com/formbricks/formbricks)) `AGPL-3.0` `Node.js/Docker`
- [Framadate](https://framadate.org/abc/) - 在线服务，快速轻松地安排约会或做决定：创建投票，定义选择的日期或主题，将投票链接发送给您的朋友或同事，讨论并做出决定。 ([演示](https://framadate.org/aqg259dth55iuhwm), [源代码](https://framagit.org/framasoft/framadate?)) `CECILL-B` `PHP`
- [Gancio](https://gancio.org/) - 本地社区活动和日程分享。 ([演示](https://demo.gancio.org/), [源代码](https://framagit.org/les/gancio)) `AGPL-3.0` `Node.js`
- [gathio](https://docs.gath.io/) - 自毁、可分享、无需注册的事件页面。 ([演示](https://gath.io/), [源代码](https://github.com/lowercasename/gathio)) `GPL-3.0` `Node.js/Docker`
- [HeyForm](https://heyform.net) - 表单构建器，允许任何人创建引人入胜的对话式表单，用于调查、问卷、测验和投票。 ([源代码](https://github.com/heyform/heyform)) `AGPL-3.0` `Docker`
- [hitobito](https://hitobito.com) - 管理复杂的群组层级、成员、活动等功能。 ([演示](https://demo.hitobito.com/en/users/sign_in), [源代码](https://github.com/hitobito/hitobito)) `AGPL-3.0` `Ruby`
- [LimeSurvey](https://www.limesurvey.org) - 功能丰富的 Web 问卷调查软件，支持复杂的调查逻辑。 ([演示](https://demo.limesurvey.org), [源代码](https://github.com/LimeSurvey/LimeSurvey)) `GPL-2.0` `PHP`
- [Meetable](https://events.indieweb.org) - 极简活动聚合器。 ([源代码](https://github.com/aaronpk/Meetable)) `MIT` `PHP`
- [Mobilizon](https://mobilizon.org) - 联邦化工具，帮助你发现、创建和组织活动与群组。 ([源代码](https://framagit.org/framasoft/mobilizon/)) `AGPL-3.0` `Elixir/Docker`
- [OpnForm](https://opnform.com) - 美观的开源表单构建器。 ([演示](https://opnform.com/forms/create/guest), [源代码](https://github.com/OpnForm/OpnForm)) `AGPL-3.0` `PHP/Node.js/Docker`
- [Revel](https://www.letsrevel.io) `⚠` - 面向社区的活动管理与票务平台。 ([演示](https://demo.letsrevel.io), [源代码](https://github.com/letsrevel/revel-backend), [客户端](https://github.com/letsrevel)) `MIT` `Python/Docker`


### 持续集成和持续部署

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[持续集成](https://en.wikipedia.org/wiki/Continuous_integration)/[持续部署](https://en.wikipedia.org/wiki/Continuous_deployment) 软件。

- [ArgoCD](https://argo-cd.readthedocs.io/en/stable/) - 面向 Kubernetes 的声明式 GitOps 持续交付工具。 ([源代码](https://github.com/argoproj/argo-cd)) `Apache-2.0` `Go`
- [Buildbot](https://buildbot.net/) - 基于 Python 的持续集成工具包。 ([源代码](https://github.com/buildbot/buildbot)) `GPL-2.0` `Python`
- [CDS](https://ovh.github.io/cds/) - 企业级持续交付与 DevOps 自动化开源平台。 ([源代码](https://github.com/ovh/cds)) `BSD-3-Clause` `Go`
- [Concourse](https://concourse-ci.org/) - 以流水线为一等公民、每一步都容器化的 CI 工具。 ([演示](https://ci.concourse-ci.org/), [源代码](https://github.com/concourse/concourse)) `Apache-2.0` `Go`
- [drone](https://drone.io/) - 基于 Docker、用 Go 编写的持续交付平台。 ([源代码](https://github.com/drone/drone)) `Apache-2.0` `Go`
- [GitLab CI](https://about.gitlab.com/solutions/continuous-integration/) - GitLab 内置的全功能 CI/CD 解决方案。 ([源代码](https://gitlab.com/gitlab-org/gitlab-foss)) `MIT` `Ruby`
- [GoCD](https://www.go.cd/) - 持续交付服务器。 ([源代码](https://github.com/gocd/gocd)) `Apache-2.0` `Java/Ruby`
- [Jenkins](https://jenkins-ci.org/) - 持续集成服务器。 ([源代码](https://github.com/jenkinsci/jenkins/)) `MIT` `Java`
- [Laminar](https://laminar.ohwg.net) - 快速、轻量、简单且灵活的持续集成。 ([源代码](https://github.com/ohwgiles/laminar)) `GPL-3.0` `C++`
- [PHP Censor](https://github.com/php-censor/php-censor) - 面向 PHP 项目的自托管持续集成服务器。 `BSD-2-Clause` `PHP`
- [Strider](https://strider-cd.github.io/) - 开源持续部署/持续集成平台。 ([源代码](https://github.com/Strider-CD/strider)) `MIT` `Node.js`
- [Terrateam](https://terrateam.io) - 针对 Terraform 和 OpenTofu 工作流的 GitOps 优先自动化平台，支持自托管运行器。 ([源代码](https://github.com/terrateamio/terrateam)) `MPL-2.0` `OCaml/Docker`
- [werf](https://werf.io/) - 用于构建 Docker 镜像并通过 GitOps 部署到 Kubernetes 的开源 CI/CD 工具。 ([源代码](https://github.com/werf/werf)) `Apache-2.0` `Go`
- [Woodpecker](https://woodpecker-ci.org/) - Drone 的社区分支，使用 Docker 容器。 ([源代码](https://github.com/woodpecker-ci/woodpecker)) `Apache-2.0` `Go`


### 指标和指标采集

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

指标采集和展示软件。

- [Beats](https://www.elastic.co/beats/) - 单一用途的数据收集器，将数据从数百或数千台机器发送到 Logstash 或 Elasticsearch。 ([源代码](https://github.com/elastic/beats)) `Apache-2.0` `Go`
- [Collectd](https://collectd.org/) - 系统统计信息收集守护进程。 ([源代码](https://github.com/collectd/collectd)) `MIT` `C`
- [Diamond](https://github.com/python-diamond/Diamond) - 收集系统指标并发布到 Graphite（及其他）的守护进程。 `MIT` `Python`
- [Grafana](https://grafana.com/) - Graphite 和 InfluxDB 的仪表盘与图形编辑器。 ([源代码](https://github.com/grafana/grafana)) `AGPL-3.0` `Go`
- [Graphite](https://graphite.readthedocs.org/en/latest/) - 可扩展的图形服务器。 ([源代码](https://github.com/graphite-project/graphite-web)) `Apache-2.0` `Python`
- [RRDtool](https://oss.oetiker.ch/rrdtool/) - 行业标准、高性能的时间序列数据记录与绘图系统。 ([源代码](https://github.com/oetiker/rrdtool-1.x)) `GPL-2.0` `C`
- [Statsd](https://github.com/statsd/statsd) - 监听计数器、定时器等统计信息的守护进程，通过 UDP 或 TCP 接收并聚合后发送到后端服务。 `MIT` `Node.js`
- [tcollector](http://opentsdb.net/docs/build/html/user_guide/utilities/tcollector.html) - 从本地采集器收集数据并推送到 OpenTSDB。 ([源代码](https://github.com/OpenTSDB/tcollector/)) `LGPL-3.0/GPL-3.0` `Python`
- [Telegraf](https://github.com/influxdata/telegraf) - 插件驱动的服务器代理，用于采集、处理、聚合和写入指标。 `MIT` `Go`
- [VictoriaMetrics](https://victoriametrics.com/) - 快速、经济高效的时序数据库和监控解决方案，可直接替换 Prometheus，支持 PromQL/MetricsQL。 ([源代码](https://github.com/VictoriaMetrics/VictoriaMetrics)) `Apache-2.0` `Go`


### 控制面板

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

Web 托管与服务器或服务控制面板。

- [Ajenti](https://ajenti.org/) - Linux 和 BSD 的控制面板。 ([源代码](https://github.com/ajenti/ajenti)) `MIT` `Python/Shell`
- [Cockpit Project](https://cockpit-project.org/) - 服务器的 Web 图形界面。 ([源代码](https://github.com/cockpit-project/cockpit)) `LGPL-2.1` `C`
- [Froxlor](https://froxlor.org/) - 轻量级服务器管理软件，支持 Nginx 和 PHP-FPM。 ([源代码](https://github.com/Froxlor/Froxlor/)) `GPL-2.0` `PHP`
- [HestiaCP](https://hestiacp.com/) - Web 服务器控制面板（VestaCP 分支）。 ([演示](https://demo.hestiacp.com:8083/login/), [源代码](https://github.com/hestiacp/hestiacp)) `GPL-3.0` `PHP/Shell/Other`
- [ISPConfig](https://www.ispconfig.org) - 通过浏览器直接管理 Linux 服务器。 ([源代码](https://git.ispconfig.org/ispconfig/ispconfig3)) `BSD-3-Clause` `PHP`
- [Sentora](https://github.com/sentora/sentora-core) - Linux、BSD 的开源 Web 托管控制面板（ZPanel 分支）。 `GPL-3.0` `PHP`
- [Virtualmin](https://www.virtualmin.com/) - Linux 和 BSD 系统的强大灵活的 Web 托管控制面板。 ([源代码](https://github.com/virtualmin)) `GPL-3.0` `Shell/Perl/Other`
- [Webmin](https://www.webmin.com/) - Unix 系统管理的 Web 界面。 ([源代码](https://github.com/webmin/webmin)) `BSD-3-Clause` `Perl`


### 搜索引擎

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[搜索引擎](https://en.wikipedia.org/wiki/Search_engine_(computing))是设计用于帮助找到存储在计算机系统上的信息的[信息检索系统](https://en.wikipedia.org/wiki/Information_retrieval)。这包括[网络搜索引擎](https://en.wikipedia.org/wiki/Web_search_engine)。

- [Aleph](https://aleph.occrp.org/) - 用于索引大量文档（PDF、Word、HTML）和结构化数据（CSV、XLS、SQL）以便轻松浏览和搜索的工具。它主要为调查报道而构建。 ([演示](https://aleph.occrp.org/), [源代码](https://github.com/alephdata/aleph)) `MIT` `Docker/K8S`
- [Apache Solr](https://lucene.apache.org/solr/) - 企业搜索平台，具备全文搜索、命中高亮显示、分面搜索、实时索引、动态聚类和处理丰富文档（如Word、PDF等）的功能。 ([源代码](https://github.com/apache/solr)) `Apache-2.0` `Java/Docker/K8S`
- [Fess](https://fess.codelibs.org/) - 强大且易于部署的企业级搜索服务器。 ([演示](https://search.n2sm.co.jp/), [源代码](https://github.com/codelibs/fess)) `Apache-2.0` `Java/Docker`
- [Hister](https://hister.org/) - 个人 Web 搜索引擎，可自动索引访问过的网站，支持离线本地预览、本地文件、多用户和可选语义搜索。 ([演示](https://demo.hister.org/), [源代码](https://github.com/asciimoo/hister)) `AGPL-3.0` `Go/Docker`
- [Manticore Search](https://github.com/manticoresoftware/manticoresearch/) - 全文搜索和数据分析，对于小、中、大数据具有快速的响应时间（替代Elasticsearch）。 `GPL-3.0` `Docker/deb/C++/K8S`
- [MeiliSearch](https://www.meilisearch.com) - 极其相关、即时且容错的全文搜索API。 ([源代码](https://github.com/meilisearch/MeiliSearch)) `MIT` `Rust/Docker/deb`
- [Meme Search](https://github.com/neonwatty/meme-search) - AI 驱动的表情包搜索引擎。使用视觉语言模型自动提取图像描述，再用向量嵌入进行索引，支持语义搜索和关键词搜索。 `Apache-2.0` `Docker`
- [OpenSearch](https://opensearch.org) - 分布式 RESTful 搜索引擎。 ([源代码](https://github.com/opensearch-project/OpenSearch)) `Apache-2.0` `Java/Docker/K8S/deb`
- [SearXNG](https://docs.searxng.org/) `⚠` - 互联网元搜索引擎，汇总来自各种搜索服务和数据库的结果（Searx 的分支）。 ([源代码](https://github.com/searxng/searxng/)) `AGPL-3.0` `Python/Docker`
- [sist2](https://github.com/sist2app/sist2) - 极速文件系统索引与搜索工具。 `GPL-3.0` `C/Docker`
- [Sosse](https://sosse.readthedocs.io/en/stable/) - 基于 Selenium 的搜索引擎与爬虫，支持离线归档。 ([源代码](https://gitlab.com/biolds1/sosse)) `AGPL-3.0` `Python/Docker`
- [Typesense](https://typesense.org) - 高速、容错的开源搜索引擎，专为开发者的愉悦和易用性而优化。 ([源代码](https://github.com/typesense/typesense)) `GPL-3.0` `C++/Docker/K8S/deb`
- [Websurfx](https://github.com/neon-mmd/websurfx) `⚠` - 在保护隐私和安全的前提下，汇总其他搜索引擎的结果（元搜索引擎），无广告。它速度极快，提供高度可定制性（SearX的替代品）。 `AGPL-3.0` `Rust/Docker`
- [Yacy](https://yacy.net/en/index.html) - 基于对等、去中心化的搜索引擎服务器。 ([源代码](https://github.com/yacy/yacy_search_server)) `GPL-2.0` `Java/Docker/K8S`
- [ZincSearch](https://zincsearch.com) - 需要最少资源的搜索引擎（Elasticsearch的替代品）。 ([演示](https://github.com/zinclabs/zinc#playground-server), [源代码](https://github.com/zincsearch/zincsearch)) `Apache-2.0` `Go/Docker/K8S`


### 故障排查

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

故障排查工具。

- [grml](https://grml.org) - 含强大 CLI 工具的可启动 Debian Live CD。 ([源代码](https://github.com/grml/)) `GPL-3.0` `Shell`
- [mitmproxy](https://mitmproxy.org/) - 用于拦截、查看和修改网络流量的 Python 工具，排查网络问题非常有用。 ([源代码](https://github.com/mitmproxy/mitmproxy)) `MIT` `Python`
- [mtr](https://www.bitwizard.nl/mtr/) - 集合 traceroute 和 ping 的网络工具。 ([源代码](https://github.com/traviscross/mtr)) `GPL-2.0` `C`
- [Sysdig](https://www.sysdig.com/) - 捕获 Linux 实例的系统状态和活动，并进行保存、过滤和分析。 ([源代码](https://github.com/draios/sysdig)) `Apache-2.0` `Docker/Lua/C`
- [Wireshark](https://www.wireshark.org/) - 世界领先的网络协议分析器。 ([源代码](https://gitlab.com/wireshark/wireshark)) `GPL-2.0` `C`


### 数据库管理

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[数据库](https://en.wikipedia.org/wiki/Database)管理的Web界面。包括用于数据库分析和可视化的工具。

_相关: [分析](#分析), [自动化](#自动化)_

_另见: [dbdb.io - 数据库之数据库](https://dbdb.io/)_

- [Adminer](https://www.adminer.org/) - 在单个 PHP 文件中进行数据库管理。支持 MySQL、MariaDB、PostgreSQL、SQLite、MS SQL、Oracle、Elasticsearch、MongoDB 等。 ([源代码](https://github.com/vrana/adminer)) `Apache-2.0/GPL-2.0` `PHP`
- [Azimutt](https://azimutt.app) - 面向真实世界数据库（庞大且混乱）的可视化数据库探索工具。可以探索数据库模式以及数据，记录它们，扩展它们，甚至进行分析和指导。 ([演示](https://azimutt.app/gallery/gospeak), [源代码](https://github.com/azimuttapp/azimutt)) `MIT` `Elixir/Node.js/Docker`
- [Baserow](https://baserow.io/) - 在没有技术经验的情况下创建自己的数据库（与Airtable类似的替代品）。 ([源代码](https://gitlab.com/baserow/baserow)) `MIT` `Docker`
- [Bytebase](https://www.bytebase.com/) - 为 DevOps 团队提供安全的数据库模式更改和版本控制，支持 MySQL、PostgreSQL、TiDB、ClickHouse 和 Snowflake。 ([源代码](https://github.com/bytebase/bytebase)) `MIT` `Docker/K8S/Go`
- [Chartbrew](https://chartbrew.com) - 直接连接数据库和 API，并使用数据创建精美图表。 ([演示](https://app.chartbrew.com/live-demo), [源代码](https://github.com/chartbrew/chartbrew)) `MIT` `Node.js/Docker`
- [ChartDB](https://chartdb.io/) - 一个数据库图表编辑器，只需一条查询语句即可可视化和设计你的数据库。 ([演示](https://app.chartdb.io), [源代码](https://github.com/chartdb/chartdb)) `AGPL-3.0` `Node.js/Docker`
- [CloudBeaver](https://dbeaver.com/) - 管理数据库，支持 PostgreSQL、MySQL、SQLite 等。DBeaver 的 Web/托管版本。 ([源代码](https://github.com/dbeaver/cloudbeaver)) `Apache-2.0` `Docker`
- [d9](https://d9.webcapsule.io) - 通过直观管理界面将 SQL 数据库转为安全 API 的数据平台和无头 CMS（Directus 的分支）。 ([源代码](https://github.com/LaWebcapsule/d9)) `GPL-3.0` `Node.js`
- [Databunker](https://databunker.org/) - 网络化、自托管、符合 GDPR 标准的安全数据库，用于存储个人数据或 PII。 ([源代码](https://github.com/securitybunker/databunker)) `MIT` `Docker`
- [Datasette](https://datasette.io/) - 通过简单的导入导出和数据库管理，探索和发布数据。 ([源代码](https://github.com/simonw/datasette)) `Apache-2.0` `Python/Docker`
- [Evidence](https://evidence.dev) - 基于代码的BI工具。使用SQL和Markdown编写报告，并以网站形式呈现。 ([源代码](https://github.com/evidence-dev/evidence)) `MIT` `Node.js`
- [Kottster](https://kottster.app/) - 低代码管理面板，可连接数据库并自动生成用于查看和管理数据的页面。 ([演示](https://demo.kottster.app/), [源代码](https://github.com/kottster/kottster)) `Apache-2.0` `Node.js/Docker`
- [Limbas](https://www.limbas.com/en/) - 用于创建数据库驱动业务应用的数据库框架。作为图形化数据库前端，支持高效处理数据存量并灵活开发便捷的数据库应用。 ([源代码](https://github.com/limbas/limbas)) `GPL-2.0` `PHP`
- [Mathesar](https://mathesar.org/) - 直观的协作数据管理界面，适合各技术水平的用户使用。基于 Postgres 构建，可连接现有数据库或新建数据库。 ([源代码](https://github.com/mathesar-foundation/mathesar)) `GPL-3.0` `Docker/Python`


### 文件传输 - 分布式文件系统

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

网络分布式文件系统。

**请访问 [awesome-sysadmin/分布式文件系统](https://github.com/awesome-foss/awesome-sysadmin#distributed-filesystems)**



### 文件传输 - 单击和拖放上传

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

用于分享一次性/短期/临时文件的简化文件服务器，提供单击或[拖放](https://en.wikipedia.org/wiki/Drag_and_drop)上传功能。

- [015](https://send.fudaoyuan.icu) - 一个临时文件分享平台。致力于提供一次性、临时文件和文本上传、处理和共享服务。 ([源代码](https://github.com/keven1024/015)) `AGPL-3.0` `Docker`
- [Chibisafe](https://chibisafe.app) - 文件上传服务，旨在易于使用和设置。它接受文件、照片、文档，任何您想要上传的内容，并为您生成可共享的链接，供您发送给他人使用。 ([源代码](https://github.com/chibisafe/chibisafe)) `MIT` `Docker/Node.js`
- [Digirecord](https://ladigitale.dev/digirecord/) - 录制并分享音频文件（文档为法语）。 ([源代码](https://codeberg.org/ladigitale/digirecord)) `AGPL-3.0` `Node.js/PHP`
- [elixire](https://gitlab.com/elixire/elixire) - 简单而先进的截图上传和链接缩短服务。 ([客户端](https://gitlab.com/elixire/elixiremanager)) `AGPL-3.0` `Python`
- [Enclosed](https://enclosed.cc/) - 极简主义的网页应用程序，用于发送私密且安全的便签。 ([演示](https://enclosed.cc/), [源代码](https://github.com/CorentinTh/enclosed)) `Apache-2.0` `Docker/Node.js`
- [Files Sharing](https://github.com/axeloz/filesharing) - 基于唯一且临时链接的文件共享应用程序。 `GPL-3.0` `PHP/Docker`
- [Flare](https://github.com/FlintSH/Flare) - 一款非臃肿、现代且高度可配置的文件/截图存储服务器，支持 ShareX、Flameshot 和 Spectacle。提供 OCR 搜索等功能。 `MIT` `Docker/Node.js`
- [Gokapi](https://github.com/Forceu/gokapi) - 用于共享文件的轻量级服务器，文件在设定的下载次数或天数后过期。类似于已停用的Firefox Send，区别在于只允许管理员上传文件。 `GPL-3.0` `Go/Docker`
- [goploader](https://depado.github.io/goploader/) - 轻松的文件分享，支持服务器端加密，兼容 curl/httpie/wget。 ([源代码](https://github.com/Depado/goploader)) `MIT` `Go`
- [GoSƐ](https://codeberg.org/stv0g/gose) - 现代化的文件上传工具，专注于可扩展性和简洁性。仅依赖于 S3 存储后端，因此可以横向扩展，无需额外的数据库或缓存。 `Apache-2.0` `Go/Docker`
- [Jirafeau](https://gitlab.com/jirafeau/Jirafeau) - 一键文件共享项目。选择文件，上传，然后分享链接。就是这么简单。 `AGPL-3.0` `PHP/Docker`
- [OnionShare](https://github.com/onionshare/onionshare) - 安全匿名地共享任意大小的文件。 `GPL-3.0` `Python/deb`
- [PicoShare](https://github.com/mtlynch/picoshare) - 极简、易于自行托管的图片及其他文件分享服务。 `AGPL-3.0` `Go/Docker`
- [Picsur](https://github.com/CaramelFur/Picsur) - 简单的图像托管平台，让你可以轻松托管、编辑和分享图片。 `AGPL-3.0` `Docker`
- [PictShare](https://www.pictshare.net/) - 多语言图片托管服务，提供简洁的图片缩放与上传 API。 ([源代码](https://github.com/HaschekSolutions/pictshare)) `Apache-2.0` `PHP/Docker`
- [Pingvin Share X](https://github.com/smp46/pingvin-share-x) - 文件分享平台，支持登录、反向分享、分享有效期、S3 存储桶、高级认证和 ClamAV 安全扫描（Pingvin Share 的分支）。 `BSD-2-Clause` `Docker/Node.js`
- [Plik](https://github.com/root-gg/plik) - 可扩展且易用的临时文件上传系统。 ([演示](https://plik.root.gg/)) `MIT` `Go/Docker`
- [ProjectSend](https://www.projectsend.org/) - 上传文件并将其分配给您创建的特定客户端。向您的客户授予对这些文件的访问权限。 ([源代码](https://github.com/projectsend/projectsend)) `GPL-2.0` `PHP`
- [PsiTransfer](https://github.com/psi-4ward/psitransfer) - 简洁的文件共享方案，支持可靠的上传/下载断点续传与密码保护。 `BSD-2-Clause` `Node.js`
- [QuickShare](https://ihexxa.github.io/quickshare.site/) - 在不同设备间实现快速简便的文件共享。 ([源代码](https://github.com/ihexxa/quickshare)) `LGPL-3.0` `Docker/Go`
- [Safebucket](https://docs.safebucket.io/) - 可插拔基础设施的文件分享平台，上传和下载直接在客户端与 S3 兼容存储之间进行。 ([源代码](https://github.com/safebucket/safebucket)) `Apache-2.0` `Go/Docker`
- [sE2EEnd](https://github.com/sE2EEnd/sE2EEnd) - 端对端加密文件分享工具，支持密码保护、下载次数限制和自动过期，集成 Keycloak 进行身份认证。 `AGPL-3.0` `Docker`
- [Sharry](https://github.com/eikek/sharry) - 在经过身份验证和匿名用户之间轻松共享文件（双向共享），支持可恢复的上传和下载。 `GPL-3.0` `Scala/Java/deb/Docker`
- [Shifter](https://github.com/TobySuch/Shifter) - 一个由 Django 驱动的简单的自托管文件共享 Web 应用。 `MIT` `Docker`
- [Slink](https://docs.slinkapp.io/) - 一个旨在让用户完全掌控其媒体分享体验的图片分享平台。 ([源代码](https://github.com/andrii-kryvoviaz/slink)) `AGPL-3.0` `Docker`
- [transfer.sh](https://github.com/dutchcoders/transfer.sh) - 通过命令行轻松共享文件。 `MIT` `Go`
- [Uguu](https://github.com/nokonoko/uguu) - 存储文件并在一定时间后删除。 `MIT` `PHP`
- [XBackBone](https://xbackbone.app/) - 一个简单、快速且轻量级的文件管理器，集成了即时共享工具，类似于ShareX（用于Windows的免费开源截图实用工具）。 ([源代码](https://github.com/SergiX44/XBackBone)) `AGPL-3.0` `PHP/Docker`
- [Zipline](https://github.com/diced/zipline) - 一个轻量级、快速且可靠的文件分享服务器，通常与ShareX一起使用，提供基于React的Web界面和快速的API。 `MIT` `Docker/Node.js`


### 文件传输 - 基于 Web 的文件管理器

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

基于 Web 的[文件管理器](https://en.wikipedia.org/wiki/File_manager)。

_相关: [协同办公](#协同办公)_

- [Apaxy](https://oupala.github.io/apaxy/) - 一款旨在提升浏览 Web 目录体验的主题，使用 mod_autoindex Apache 模块和一些 CSS 来覆盖目录列表的默认样式。 ([源代码](https://github.com/oupala/apaxy)) `GPL-3.0` `JavaScript`
- [copyparty](https://github.com/9001/copyparty) - 便携式文件服务器，支持加速可恢复上传、重复数据删除、WebDAV、FTP、zeroconf、媒体索引、视频缩略图、音频转码和只写文件夹，全部打包在一个文件中，无需强制性依赖。 ([演示](https://a.ocv.me/pub/demo/)) `MIT` `Python`
- [Directory Lister](https://www.directorylister.com/) - 简单的基于PHP的目录列表器，列出一个目录及其所有子目录，并允许您在其中导航。 ([源代码](https://github.com/DirectoryLister/DirectoryLister)) `MIT` `PHP/Docker`
- [filebrowser](https://filebrowser.org/) - 带有 Material Design Web 界面的 Web 文件浏览器。 ([源代码](https://github.com/filebrowser/filebrowser)) `Apache-2.0` `Go`
- [FileGator](https://filegator.io/) - FileGator 是一个强大的多用户文件管理器，具有单页面前端。 ([演示](https://demo.filegator.io), [源代码](https://github.com/filegator/filegator)) `MIT` `PHP/Docker`
- [FileRise](https://github.com/error311/FileRise) - 基于 Web 的文件管理器，支持上传、标签、分享链接、图库/表格视图以及内置编辑器。 ([演示](https://github.com/error311/FileRise?tab=readme-ov-file#live-demo)) `MIT` `Docker/PHP`
- [Filestash](https://www.filestash.app/) - Web 文件管理器，可让您在任何位置管理您的数据：FTP、SFTP、WebDAV、Git、S3、Minio、Dropbox 或 Google Drive。 ([演示](https://demo.filestash.app/), [源代码](https://github.com/mickael-kerjean/filestash)) `AGPL-3.0` `Docker`
- [Gossa](https://github.com/pldubouilh/gossa) - 轻量且简单的文件 Web 服务器。 `MIT` `Go`
- [IFM](https://github.com/misterunknown/ifm) - 单脚本文件管理器。 `MIT` `PHP`
- [mikochi](https://github.com/zer0tonin/Mikochi) - 浏览远程文件夹，上传文件，删除、重命名、下载并流式传输文件到 VLC/mpv。 `MIT` `Go/Docker/K8S`
- [miniserve](https://github.com/svenstaro/miniserve) - 用于通过 HTTP 提供文件和目录的命令行工具。 `MIT` `Rust`
- [ResourceSpace](https://www.resourcespace.com) - 简单、快速且免费的数字资产管理方式。 ([演示](https://www.resourcespace.com/trial), [源代码](https://www.resourcespace.com/svn)) `BSD-4-Clause` `PHP`
- [slcl](https://codeberg.org/xavidcr/slcl) - 简单轻量的 Web 云存储。 `AGPL-3.0` `C`
- [Surfer](https://git.cloudron.io/cloudron/surfer) - 带有 Web 用户界面的简单静态文件服务器，用于管理文件。 `MIT` `Node.js`
- [TagSpaces](https://www.tagspaces.org/) - TagSpaces 是一款离线、跨平台的文件管理器和组织工具，也可以作为一个笔记应用。该应用的 WebDAV 版本可以安装在 WebDAV 服务器上，如 Nextcloud 或 ownCloud。 ([演示](https://demo.tagspaces.com), [源代码](https://github.com/tagspaces/tagspaces)) `AGPL-3.0` `Node.js`
- [Tiny File Manager](https://tinyfilemanager.github.io) - PHP 编写的基于 Web 的文件管理器，简单、快速且体积小，只有一个文件。 ([演示](https://tinyfilemanager.github.io/demo/), [源代码](https://github.com/prasathmani/tinyfilemanager)) `GPL-3.0` `PHP`


### 文件传输 - 对象存储和文件服务器

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[对象存储](https://en.wikipedia.org/wiki/Object_storage)是一种将数据管理为对象的计算机数据存储方式，与其他存储架构（如文件系统，将数据管理为文件层次结构，以及块存储，将数据管理为扇区和磁道内的块）相对立。

- [GarageHQ](https://garagehq.deuxfleurs.fr/) - 地理分布式、兼容 S3 的存储服务，可满足多种需求。 ([源代码](https://git.deuxfleurs.fr/Deuxfleurs/garage)) `AGPL-3.0` `Docker/Rust`
- [Harbor](https://goharbor.io/) - 云原生镜像仓库，存储、签名和扫描内容。 ([源代码](https://github.com/goharbor/harbor)) `Apache-2.0` `Docker/K8S`
- [SeaweedFS](https://github.com/seaweedfs/seaweedfs) - SeaweedFS 是一个开源的分布式文件系统，支持 WebDAV、S3 API、FUSE 挂载、HDFS 等，针对大量小文件进行优化，易于扩展容量。 `Apache-2.0` `Go`
- [Zenko CloudServer](https://www.zenko.io/cloudserver) - Zenko CloudServer，一个处理Amazon S3协议的开源服务器实现。 ([源代码](https://github.com/scality/cloudserver)) `Apache-2.0` `Docker/Node.js`
- [ZOT OCI Registry](https://zotregistry.dev) - 一个生产就绪、厂商中立、OCI 原生的容器镜像仓库。 ([演示](https://zothub.io), [源代码](https://github.com/project-zot/zot)) `Apache-2.0` `Go/Docker`


### 文件传输 - 点对点文件共享

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[点对点文件共享](https://en.wikipedia.org/wiki/Peer-to-peer_file_sharing)是使用[点对点](https://en.wikipedia.org/wiki/Peer-to-peer)网络技术分发和[共享](https://en.wikipedia.org/wiki/File_sharing)数字媒体的过程。

- [bittorrent-tracker](https://webtorrent.io/) - 简单、强大的BitTorrent追踪器（客户端和服务器）实现。 ([源代码](https://github.com/webtorrent/bittorrent-tracker)) `MIT` `Node.js`
- [Deluge](https://deluge-torrent.org/) - 轻量级、跨平台的 BitTorrent 客户端。 ([源代码](https://git.deluge-torrent.org/deluge/tree/?h=develop)) `GPL-3.0` `Python/deb`
- [PrivyDrop](https://www.privydrop.app) - 基于 WebRTC 的简洁易用点对点文本、图片与文件传输工具，支持断点续传。 ([源代码](https://github.com/david-bai00/PrivyDrop)) `MIT` `Docker/Node.js`
- [qBittorrent](https://www.qbittorrent.org/) - 免费的跨平台比特Torrent客户端，具有功能丰富的Web UI，可进行远程访问。 ([源代码](https://github.com/qbittorrent/qBittorrent)) `GPL-2.0` `C++`
- [Send](https://gitlab.com/timvisee/send) - 简单、私密、端到端加密的临时文件分享工具，最初由 Mozilla 构建。 ([演示](https://send.vis.ee/), [客户端](https://gitlab.com/timvisee/send#clients)) `MPL-2.0` `Node.js/Docker`
- [slskd](https://github.com/slskd/slskd) `⚠` - 一个现代化的客户端-服务器应用程序，适用于Soulseek文件共享网络。 `AGPL-3.0` `Docker/C#`
- [Transmission](https://transmissionbt.com/) - 快速、简便、免费的BitTorrent客户端。 ([源代码](https://github.com/transmission/transmission)) `GPL-3.0` `C++/deb`
- [Webtor](https://github.com/webtor-io/self-hosted) - 基于 Web 的种子客户端，支持即时音视频流播放。 ([演示](https://webtor.io)) `MIT` `Docker`


### 文件传输和同步

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[文件传输](https://en.wikipedia.org/wiki/File_transfer)、[共享](https://en.wikipedia.org/wiki/File_sharing)和[同步软件](https://en.wikipedia.org/wiki/File_synchronization)。

_相关: [协同办公](#协同办公)_

- [bewCloud](https://bewcloud.com) - 文件共享与同步、笔记和照片（Nextcloud 和 ownCloud 的 RSS 阅读器替代品）。 ([源代码](https://github.com/bewcloud/bewcloud), [客户端](https://github.com/bewcloud)) `AGPL-3.0` `Docker`
- [Cloudreve](https://cloudreve.org/) - 文件管理和共享系统，支持多个存储供应商。 ([演示](https://demo.cloudreve.org), [源代码](https://github.com/cloudreve/cloudreve)) `GPL-3.0` `Docker/Go`
- [Git Annex](https://git-annex.branchable.com/) - 在计算机、服务器和外部驱动器之间进行文件同步。 ([源代码](https://git.joeyh.name/index.cgi/git-annex.git/)) `GPL-3.0` `Haskell`
- [Kinto](https://kinto.readthedocs.org) - 极简 JSON 存储服务，支持同步与共享功能。 ([源代码](https://github.com/Kinto/kinto)) `Apache-2.0` `Python`
- [Nextcloud](https://nextcloud.com/) - 从任何设备按照您的方式访问和共享您的文件、日历、联系人、邮件以及[更多](https://apps.nextcloud.com/)。 ([演示](https://try.nextcloud.com/), [源代码](https://github.com/nextcloud/server)) `AGPL-3.0` `PHP/deb`
- [OpenCloud](https://docs.opencloud.eu/) - 文件共享与协作平台。 ([源代码](https://github.com/opencloud-eu/opencloud)) `Apache-2.0` `Docker/Go/Node.js`
- [OpenSSH SFTP server](https://www.openssh.com/) - 安全文件传输程序。 ([源代码](https://github.com/openbsd/src/tree/master/usr.bin/ssh)) `BSD-2-Clause` `C/deb`
- [ownCloud](https://owncloud.org/) - 一体化解决方案，用于保存、同步、查看、编辑和共享文件、日历、通讯录等。 ([源代码](https://github.com/owncloud/core), [客户端](https://github.com/owncloud/core/wiki/Apps)) `AGPL-3.0` `PHP/Docker/deb`
- [Peergos](https://peergos.org) - 安全而私密的在线空间，您可以在其中存储、共享和查看照片、视频、音乐和文档。还包括日历、新闻订阅、任务列表、聊天和电子邮件客户端。 ([源代码](https://github.com/Peergos/Peergos)) `AGPL-3.0` `Java`
- [Puter](https://puter.com/) - 旨在提供丰富功能、极快速度和高度可扩展性的基于 Web 的操作系统。 ([演示](https://puter.com/), [源代码](https://github.com/heyputer/puter)) `AGPL-3.0` `Node.js/Docker`
- [Pydio](https://pydio.com/) - 将任何Web服务器转变为强大的文件管理系统，并作为主流云存储提供商的替代品。 ([演示](https://pydio.com/en/demo), [源代码](https://github.com/pydio/cells)) `AGPL-3.0` `Go`
- [Samba](https://www.samba.org/) - Samba 是用于 Linux 和 Unix 的标准 Windows 互操作性程序套件。它为所有使用 SMB/CIFS 协议的客户端提供安全、稳定和快速的文件和打印服务。 ([源代码](https://git.samba.org/samba.git/)) `GPL-3.0` `C`
- [Seafile](https://www.seafile.com/en/home/) - 主要面向团队和组织的文件托管和共享解决方案。 ([源代码](https://github.com/haiwen/seafile)) `GPL-2.0/GPL-3.0/AGPL-3.0/Apache-2.0` `C`
- [Sync-in](https://sync-in.com) - 支持实时编辑、权限管理、桌面/命令行客户端的文件存储、同步、分享与协作平台。 ([演示](https://sync-in.com/docs/demo), [源代码](https://github.com/Sync-in/server), [客户端](https://github.com/Sync-in/desktop)) `AGPL-3.0` `Node.js/Docker`
- [Syncthing](https://syncthing.net/) - Syncthing 是一个开源的点对点文件同步工具。 ([源代码](https://github.com/syncthing/syncthing)) `MPL-2.0` `Go/Docker/deb`
- [Unison](https://www.cis.upenn.edu/~bcpierce/unison/) - Unison是一款用于OSX、Unix和Windows的文件同步工具。 ([源代码](https://github.com/bcpierce00/unison)) `GPL-3.0` `deb/OCaml`


### 文档管理

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[文档管理系统](https://en.wikipedia.org/wiki/Document_management_system)（DMS）是用于接收、跟踪、管理和存储文档以减少纸张使用的系统。

- [BentoPDF](https://bentopdf.com) `⚠` - 以隐私为优先的客户端 PDF 工具套件，支持在浏览器中直接合并、编辑和处理 PDF 文件。 ([演示](https://bentopdf.com), [源代码](https://github.com/alam00000/bentopdf)) `AGPL-3.0` `Node.js/Docker`
- [Docspell](https://docspell.org) - 自动标记文档组织和归档系统。 ([源代码](https://github.com/eikek/docspell)) `GPL-3.0` `Scala/Java/Docker`
- [Documenso](https://documenso.com) - 数字文件签署平台（DocuSign 替代方案）。 ([源代码](https://github.com/documenso/documenso)) `AGPL-3.0` `Node.js/Docker`
- [Docuseal](https://www.docuseal.co) - 创建、填写和签署数字文档（DocuSign 的替代品）。 ([演示](https://demo.docuseal.tech/), [源代码](https://github.com/docusealco/docuseal)) `AGPL-3.0` `Docker`
- [EveryDocs](https://github.com/jonashellmann/everydocs-core) - 简单的文档管理系统，适用于个人使用，具备基本的数字化文档整理功能。 `GPL-3.0` `Docker/Ruby`
- [Gotenberg](https://gotenberg.dev) - 面向开发者的 API，可与强大的工具（如 Chromium 和 LibreOffice）交互，将多种文档格式（HTML、Markdown、Word、Excel 等）转换为 PDF 文件等。 ([源代码](https://github.com/gotenberg/gotenberg)) `MIT` `Docker`
- [I, Librarian](https://i-librarian.net) - 组织 PDF 论文和办公文档。它为学生以及工业和学术界的研究团队提供了许多额外功能。 ([演示](https://eu1.i-librarian.net/demo), [源代码](https://github.com/mkucej/i-librarian-free)) `GPL-3.0` `PHP`
- [Mayan EDMS](https://www.mayan-edms.com) - 电子文档管理系统，提供预览生成、OCR 识别和自动分类等功能。 ([源代码](https://gitlab.com/mayan-edms/mayan-edms)) `GPL-2.0` `Docker/K8S`
- [OpenSign](https://www.opensignlabs.com) `⚠` - 文档签署软件（DocuSign 的替代品）。 ([源代码](https://github.com/opensignlabs/opensign)) `AGPL-3.0` `Node.js/Docker`
- [Paperless-ngx](https://docs.paperless-ngx.com/) - 使用改进的界面扫描、索引和存档所有纸质文档（Paperless的分支）。 ([演示](https://demo.paperless-ngx.com/), [源代码](https://github.com/paperless-ngx/paperless-ngx)) `GPL-3.0` `Python/Docker`
- [Papermerge](https://papermerge.com) - 以扫描文档（电子档案）为中心的文档管理系统。具有类似于Dropbox/Google Drive的文件浏览功能。支持OCR、全文搜索、文本覆盖/选择。 ([源代码](https://github.com/papermerge/papermerge-core)) `Apache-2.0` `Docker/K8S`
- [Papra](https://papra.app) - 极简的文档存储、管理和归档平台，旨在简单易用，人人可用。 ([演示](https://demo.papra.app/), [源代码](https://github.com/papra-hq/papra/)) `AGPL-3.0` `Docker`
- [PdfDing](https://www.pdfding.com) - PDF 管理器、查看器和编辑器，在多设备上提供流畅的用户体验。设计极简、快速，使用 Docker 即可轻松部署。 ([演示](https://demo.pdfding.com), [源代码](https://github.com/mrmn2/PdfDing)) `AGPL-3.0` `Docker/K8S`
- [SeedDMS](https://www.seeddms.org) - 具有工作流、访问权限、全文搜索等功能的文档管理系统。 ([演示](https://www.seeddms.org/about/), [源代码](https://sourceforge.net/p/seeddms/code/ci/master/tree/)) `GPL-2.0` `PHP`
- [Signature PDF](https://github.com/24eme/signaturepdf) - 支持协作、组织、压缩和元数据编辑的 PDF 签名与处理工具。 ([演示](https://pdf.24eme.fr/)) `AGPL-3.0` `PHP/deb/Docker`
- [SimpleDMS](https://simpledms.eu) - 面向小企业的易用元数据驱动型开源文档管理系统，可自动完成大部分文档分类工作。 ([源代码](https://github.com/simpledms/simpledms), [客户端](https://simpledms.eu/en/product/integrations)) `AGPL-3.0` `Docker`
- [Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF) - 本地部署的 Web 应用，可对 PDF 文件进行多种操作，如合并、拆分、格式转换和 OCR。 `Apache-2.0` `Docker/Java`


### 文档管理 - 图书馆自动化系统（ILS）

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[图书馆自动化系统](https://en.wikipedia.org/wiki/Integrated_library_system)是用于图书馆的企业资源规划系统，用于跟踪所拥有的物品、已下订单、已支付的账单以及借阅的读者。

_相关: [内容管理系统（CMS）](#内容管理系统（cms）), [档案和数字保存（DP）](#档案和数字保存（dp）)_

- [Evergreen](https://evergreen-ils.org) - 面向图书馆的高度可扩展软件，帮助图书馆用户查找图书馆材料，并帮助图书馆管理、编目和流通这些材料。 ([源代码](https://github.com/evergreen-library-system/Evergreen)) `GPL-2.0` `PL/pgSQL`
- [Koha](https://koha-community.org/) - 企业级图书馆管理系统，具有采购、流通、编目、标签打印、无网络访问时的脱机流通等模块。 ([演示](https://koha-community.org/demo/), [源代码](https://github.com/Koha-Community/Koha)) `GPL-3.0` `Perl`
- [RERO ILS](https://rero21.ch/) - 一款大规模的综合图书馆管理系统，可作为一个 consorital 特性的服务运行，主要用于图书馆网络。包括大多数标准模块（流通、采购、编目等）和基于 Web 的公共和专业界面。 ([演示](https://ils.test.rero.ch/), [源代码](https://github.com/rero/rero-ils)) `AGPL-3.0` `Python/Docker`


### 文档管理 - 机构知识库和数字图书馆软件

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[机构知识库](https://en.wikipedia.org/wiki/Institutional_repository)和[数字图书馆](https://en.wikipedia.org/wiki/Digital_library)管理软件。

- [DSpace](http://www.dspace.org/) - 一款即开即用的仓库应用，提供对数字资源的持久访问。 ([源代码](https://github.com/DSpace/DSpace)) `BSD-3-Clause` `Java`
- [EPrints](https://www.eprints.org/) - 数字文档管理系统，具有灵活的元数据和工作流模型，主要面向学术机构。 ([演示](http://tryme.demo.eprints-hosting.org/), [源代码](https://github.com/eprints/eprints3.4)) `GPL-3.0` `Perl`
- [Fedora Commons Repository](https://wiki.lyrasis.org/display/FF/Fedora+Repository+Home) - 用于管理和传播数字内容的强大而模块化的仓库系统，特别适用于数字图书馆和档案馆，既用于访问又用于保存。 ([源代码](https://github.com/fcrepo/fcrepo)) `Apache-2.0` `Java`
- [InvenioRDM](https://inveniordm.docs.cern.ch/) - 高度可扩展的一站式科研数据管理平台，拥有优美的用户体验。 ([演示](https://inveniordm.web.cern.ch/), [源代码](https://github.com/inveniosoftware/invenio-app-rdm), [客户端](https://inveniosoftware.org/products/rdm/)) `MIT` `Python`
- [Islandora](https://www.islandora.ca/) - 用于浏览和管理基于Fedora的数字存储库的Drupal模块。 ([演示](https://sandbox.islandora.ca/), [源代码](https://github.com/Islandora/islandora)) `GPL-3.0` `PHP`
- [Samvera Hyrax](https://samvera.org/) - Samvera 框架的前端，它本身是一个用于浏览和管理基于 Fedora 的数字仓库的 Ruby on Rails 应用程序。 ([源代码](https://github.com/samvera/hyrax)) `Apache-2.0` `Ruby`


### 文档管理 - 电子书

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[电子书](https://en.wikipedia.org/wiki/Ebook)图书馆管理软件。

- [Atsumeru](https://atsumeru.xyz) - 支持 Windows、Linux、macOS 和 Android 客户端的漫画/轻小说媒体服务器。 ([源代码](https://github.com/Atsumeru-xyz/Atsumeru), [客户端](https://atsumeru.xyz/guides/#how-does-it-work)) `MIT` `Java/Docker`
- [BookLogr](https://github.com/Mozzo1000/booklogr) - 轻松管理您的个人图书馆。 ([演示](https://demo.booklogr.app/)) `Apache-2.0` `Docker`
- [Calibre Web Automated](https://github.com/crocodilestick/Calibre-Web-Automated) - 一体化解决方案，结合了 Calibre-Web 的现代轻量级网络界面和 Calibre 的强大、多功能的功能集（Calibre Web 的分支）。 `GPL-3.0` `Docker`
- [Calibre Web](https://github.com/janeczku/calibre-web) - 使用已有的 Calibre 数据库浏览、阅读和下载电子书。 `GPL-3.0` `Python`
- [Calibre](https://calibre-ebook.com/) - 电子书库管理器，可以查看、转换和编目大多数主要电子书格式的电子书，并提供用于远程客户端的内置Web服务器。 ([演示](https://calibre-ebook.com/demo), [源代码](https://github.com/kovidgoyal/calibre)) `GPL-3.0` `Python/deb`
- [Inkheart](https://gitlab.com/Nystik/inkheart) - 轻量级 PDF 库和阅读器。 `Apache-2.0` `Docker`
- [Kapowarr](https://casvt.github.io/Kapowarr/) - 构建和管理漫画书库。按需下载、重命名、移动和转换卷期文件。 ([源代码](https://github.com/Casvt/Kapowarr)) `GPL-3.0` `Docker/Python`
- [Kavita](https://www.kavitareader.com/) - 跨平台的电子书/漫画/动漫/PDF服务器和Web阅读器，具有用户管理、评分和评论以及元数据支持。 ([演示](https://www.kavitareader.com/#demo), [源代码](https://github.com/Kareadita/Kavita)) `GPL-3.0` `.NET/Docker`
- [kiwix-serve](https://github.com/kiwix/kiwix-tools) - 用于从 ZIM 文件提供 Wiki 服务的 HTTP 守护进程。 `GPL-3.0` `C++`
- [Komga](https://komga.org) - 用于漫画/漫画书/BD的媒体服务器，具有API和OPDS支持，现代的Web界面可用于浏览库，以及Web阅读器。 ([源代码](https://github.com/gotson/komga)) `MIT` `Java/Docker`
- [MyMangaDB](https://github.com/FabianRolfMatthiasNoll/MyMangaDB) `⚠` - 漫画收藏管理器，支持自动获取元数据、MyAnimeList 导入及详细的收藏统计。 `GPL-3.0` `Docker`
- [Stump](https://www.stumpapp.dev) - 一个快速、免费、开源的漫画、漫画和数字书籍服务器，支持 OPDS。 ([源代码](https://github.com/stumpapp/stump)) `MIT` `Rust`


### 日历和联系人

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[CalDAV](https://en.wikipedia.org/wiki/CalDAV) 和 [CardDAV](https://en.wikipedia.org/wiki/CardDAV) 协议服务器及网页客户端/界面，用于[电子日历](https://en.wikipedia.org/wiki/Calendaring_software)、[地址簿](https://en.wikipedia.org/wiki/Address_book)和[联系人管理](https://en.wikipedia.org/wiki/Contact_manager)。

_相关: [协同办公](#协同办公)_

- [Baïkal](https://sabre.io/baikal/) - 基于 sabre/dav 的轻量级 CalDAV 和 CardDAV 服务器。 ([源代码](https://github.com/sabre-io/Baikal)) `GPL-3.0` `PHP`
- [DAViCal](https://www.davical.org/) - 用于日历共享（CalDAV）的服务器，使用 PostgreSQL 数据库作为数据存储。 ([源代码](https://gitlab.com/davical-project/davical)) `GPL-2.0` `PHP/deb`
- [Davis](https://github.com/tchapi/davis) - 一个简单、可 Docker 化且完全可翻译的 sabre/dav 管理界面，基于 Symfony 5 和 Bootstrap 4，受 Baïkal 启发。 `MIT` `PHP`
- [Keeper.sh](https://keeper.sh/) - 日历同步工具，可通过 iCal/ICS 或 OAuth 在不同日历来源之间拉取和推送事件，支持匿名忙/闲状态。 ([源代码](https://github.com/ridafkih/keeper.sh)) `AGPL-3.0` `Docker`
- [Manage My Damn Life](https://intri.in/manage-my-damn-life/) - Manage my Damn Life（MMDL）是一个用于管理 CalDAV 任务和日历的自托管前端。 ([源代码](https://github.com/intri-in/manage-my-damn-life-nextjs)) `GPL-3.0` `Node.js/Docker`
- [Radicale](https://radicale.org/) - 简单的日历和联系人服务器，管理开销极低。 ([源代码](https://github.com/Kozea/Radicale)) `GPL-3.0` `Python/deb`
- [SabreDAV](https://sabre.io/) - 开源的 CardDAV、CalDAV 和 WebDAV 框架与服务器。 ([源代码](https://github.com/sabre-io/dav)) `MIT` `PHP`
- [Xandikos](https://github.com/jelmer/xandikos) - 开源的CardDAV和CalDAV服务器，具有最小的管理开销，支持Git存储后端。 `GPL-3.0` `Python/deb`


### 日志管理

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

日志管理工具：收集、解析、可视化等。

- [Fluentd](https://www.fluentd.org/) - 统一日志层的数据收集器。 ([源代码](https://github.com/fluent/fluentd)) `Apache-2.0` `Ruby`
- [Flume](https://flume.apache.org/) - 高效收集、聚合和传输大量日志数据的分布式、可靠服务。 ([源代码](https://github.com/apache/flume)) `Apache-2.0` `Java`
- [Loki](https://grafana.com/oss/loki/) - 日志聚合系统，设计用于存储和查询所有应用和基础设施的日志。 ([源代码](https://github.com/grafana/loki)) `AGPL-3.0` `Go`
- [reaction](https://reaction.ppom.me/) - 轻量级守护进程，扫描程序输出中的重复模式并自动采取相应措施。 ([源代码](https://framagit.org/ppom/reaction)) `AGPL-3.0` `Rust`
- [rsyslog](https://www.rsyslog.com/) - 超快的日志处理系统。 ([源代码](https://github.com/rsyslog/rsyslog)) `GPL-3.0` `C`


### 时间服务器

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

时间同步服务器与客户端（NTP、PTP、Roughtime）

- [Chrony](https://chrony-project.org/) - 功能全面的网络时间协议（NTP）实现。 ([源代码](https://gitlab.com/chrony/chrony)) `GPL-2.0` `C`
- [NTPsec](https://www.ntpsec.org/) - 基于 NTP Classic 衍生的安全、加固且经过改进的网络时间协议实现。 ([源代码](https://gitlab.com/NTPsec/ntpsec)) `BSD-2-Clause` `C`
- [OpenNTPD](https://www.openntpd.org/) - 免费、易用的网络时间协议实现。 ([源代码](https://github.com/openntpd-portable/openntpd-openbsd/)) `ISC` `C`
- [Roughenough](https://github.com/int08h/roughenough) - Roughtime 安全时间同步客户端和服务器。 `MIT/Apache-2.0` `Rust`
- [Statime](https://github.com/pendulum-project/statime) - 用 Rust 实现的精确时间协议（PTP）。 `MIT/Apache-2.0` `Rust`


### 时间追踪

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[时间追踪软件](https://en.wikipedia.org/wiki/Time-tracking_software)是一类允许用户记录在任务或项目上花费的时间的计算机软件。

- [ActivityWatch](https://activitywatch.net) - 自动跟踪你在设备上的时间使用情况。 ([源代码](https://github.com/ActivityWatch/activitywatch)) `MPL-2.0` `Python`
- [Beaver Habit Tracker](https://github.com/daya0576/beaverhabits) - 习惯跟踪应用，帮助您在短暂人生中保存珍贵时刻。 ([演示](https://beaverhabits.com/demo)) `BSD-3-Clause` `Docker`
- [Ever Gauzy](https://gauzy.co) - 开放的业务管理平台，适用于协作型、按需和共享经济（ERP/CRM/HRM/ATS/PM）。 ([演示](https://demo.gauzy.co), [源代码](https://github.com/ever-co/ever-gauzy)) `AGPL-3.0` `Docker/Node.js`
- [Kimai](https://www.kimai.org/) - 追踪工作时间，并按需打印活动摘要报告。 ([演示](https://www.kimai.org/demo/), [源代码](https://github.com/kimai/kimai)) `AGPL-3.0` `PHP`
- [solidtime](https://www.solidtime.io) - 现代化的时间追踪应用程序，适用于自由职业者和机构。 ([源代码](https://github.com/solidtime-io/solidtime)) `AGPL-3.0` `Docker`
- [TimeTagger](https://timetagger.app) - 基于交互式时间轴和强大报告的开源时间跟踪工具。 ([演示](https://timetagger.app/app/demo), [源代码](https://github.com/almarklein/timetagger)) `GPL-3.0` `Python`
- [Traggo](https://traggo.net/) - Traggo是一款基于标签的时间跟踪工具。在Traggo中，没有任务，只有带有标签的时间跨度。 ([源代码](https://github.com/traggo/server)) `GPL-3.0` `Docker/Go`
- [Wakapi](https://wakapi.dev/) - 用于跟踪编码统计的工具，与WakaTime兼容。 ([源代码](https://github.com/muety/wakapi)) `GPL-3.0` `Go/Docker`
- [Ziit](https://ziit.app) - 代码时间追踪的瑞士军刀（WakaTime 替代品）。 ([源代码](https://github.com/0pandadev/ziit)) `AGPL-3.0` `Docker`


### 服务发现

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[服务发现](https://en.wikipedia.org/wiki/Service_discovery) 是指在计算机网络中自动检测设备和服务的过程。

- [Consul](https://www.consul.io/) - Consul 是一个用于服务发现、监控和配置的工具。 ([源代码](https://github.com/hashicorp/consul)) `MPL-2.0` `Go`
- [etcd](https://etcd.io/) - 分布式 K/V 存储，通过 SSL PKI 认证和 REST HTTP API 提供共享配置与服务发现。 ([源代码](https://github.com/etcd-io/etcd)) `Apache-2.0` `Go`
- [ZooKeeper](https://zookeeper.apache.org/) - ZooKeeper 是一个集中式服务，用于维护配置信息、命名、分布式同步和组服务。 ([源代码](https://github.com/apache/zookeeper)) `Apache-2.0` `Java/C++`


### 杂项

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

不属于其他部分的软件。

- [2FAuth](https://github.com/Bubka/2FAuth) - 管理您的双因素认证 (2FA) 账户并生成其安全码。 ([演示](https://demo.2fauth.app/)) `AGPL-3.0` `PHP/Docker`
- [Anchr](https://anchr.io) - 用于互联网小型任务的工具箱，包括书签收集、URL 缩短和（加密）图片上传。 ([源代码](https://github.com/muety/anchr)) `GPL-3.0` `Node.js`
- [Anubis](https://anubis.techaro.lol/) - 网络人工智能防火墙实用程序，保护上游资源免受爬虫机器人的侵害。 ([源代码](https://github.com/TecharoHQ/anubis)) `MIT` `Docker/deb/Go`
- [asciinema](https://asciinema.org/) - 用于托管 asciicasts 的 Web 应用程序。 ([演示](https://asciinema.org/explore), [源代码](https://github.com/asciinema/asciinema-server)) `Apache-2.0` `Elixir/Docker`
- [Baby Buddy](https://github.com/babybuddy/babybuddy) - 帮助照顾者追踪婴儿的睡眠、喂养、换尿布和俯卧时间。 ([演示](https://github.com/babybuddy/babybuddy#-demo)) `BSD-2-Clause` `Python`
- [Chocolatey](https://chocolatey.org/) - Windows 的包管理器。 ([源代码](https://github.com/chocolatey/choco)) `Apache-2.0` `C#/PowerShell`
- [ClipCascade](https://github.com/Sathvik-Rao/ClipCascade) - 即时同步您的剪贴板到多个设备，无需任何按钮操作。支持 Windows、macOS、Linux 和 Android，提供无缝、安全的剪贴板共享，并且支持端到端数据加密。 `GPL-3.0` `Java/Docker`
- [Clonezilla](https://clonezilla.org/) - 分区和磁盘镜像/克隆程序。 ([源代码](https://clonezilla.org/downloads/src/)) `GPL-2.0` `Perl/Shell/Other`
- [Cloudlog](https://magicbug.co.uk/cloudlog/) - 随时随地记录你的业余无线电联络。 ([源代码](https://github.com/magicbug/cloudlog)) `MIT` `PHP/Docker`
- [ConvertX](https://github.com/C4illin/ConvertX) - 支持超过一千种不同格式的在线文件转换器。 `AGPL-3.0` `Docker`
- [CUPS](https://www.cups.org/) - CUPS（Common Unix Print System）使用Internet Printing Protocol（IPP）支持打印到本地和网络打印机。 ([源代码](https://github.com/OpenPrinting/cups)) `GPL-2.0` `C`
- [CyberChef](https://github.com/gchq/CyberChef) - 在Web浏览器中执行各种操作，如AES、DES和Blowfish加密和解密，创建十六进制转储，计算哈希等等。 ([演示](https://gchq.github.io/CyberChef)) `Apache-2.0` `JavaScript`
- [DadaMail](https://dadamailproject.com/) - 用 Perl 编写的邮件列表管理器。 ([源代码](https://sourceforge.net/projects/dadamail/files/)) `GPL-2.0` `Perl`
- [Digiboard](https://digiboard.app/) - 创建协作式白板（文档以法语提供）。 ([源代码](https://codeberg.org/ladigitale/digiboard)) `AGPL-3.0` `Node.js`
- [Digicard](https://codeberg.org/ladigitale/digicard) - 创建简单的图形组合（文档以法语提供）。 ([演示](https://ladigitale.dev/digicard/)) `AGPL-3.0` `Node.js`
- [Digicut](https://ladigitale.dev/digicut/) - 使用 FFMPEG.wasm 剪辑音频和视频文件（文档为法语）。 ([源代码](https://codeberg.org/ladigitale/digicut)) `AGPL-3.0` `Node.js`
- [Digiface](https://ladigitale.dev/digiface/) - 使用 Avataaars 库创建头像（法语文档）。 ([演示](https://ladigitale.dev/digiface/), [源代码](https://codeberg.org/ladigitale/digiface)) `AGPL-3.0` `Node.js`
- [Digiflashcards](https://ladigitale.dev/digiflashcards/) - 一个在线应用程序，用于创建抽认卡（文档为法语）。 ([源代码](https://codeberg.org/ladigitale/digiflashcards)) `AGPL-3.0` `Node.js/PHP`
- [Digimerge](https://ladigitale.dev/digimerge/) - 直接在浏览器中组装音频和视频文件（文档为法语）。 ([演示](https://ladigitale.dev/digimerge/), [源代码](https://codeberg.org/ladigitale/Digimerge)) `AGPL-3.0` `Node.js`
- [Digiquiz](https://ladigitale.dev/digiquiz/) - 一个在线应用程序，用于发布使用 H5P 创建的内容（文档为法语）。 ([源代码](https://codeberg.org/ladigitale/digiquiz)) `AGPL-3.0` `Node.js`
- [Digiread](https://ladigitale.dev/digiread/) `⚠` - 使用 Mozilla 的 Readability 清理在线页面和文章（文档为法语）。 ([源代码](https://codeberg.org/ladigitale/digiread)) `AGPL-3.0` `Node.js/PHP`
- [Digisteps](https://ladigitale.dev/digisteps/) - 一个简单的应用程序，用于创建在线教育路径（文档为法语）。 ([源代码](https://codeberg.org/ladigitale/digisteps)) `AGPL-3.0` `Node.js/PHP`
- [Digitranscode](https://ladigitale.dev/digitranscode) - 直接在浏览器中转换音频文件和视频（文档为法语）。 ([演示](https://ladigitale.dev/digitranscode), [源代码](https://codeberg.org/ladigitale/digitranscode)) `AGPL-3.0` `Node.js`
- [Digiview](https://ladigitale.dev/digiview/) `⚠` - 以无干扰的界面查看 YouTube 视频（法语文档）. ([演示](https://ladigitale.dev/digiview/), [源代码](https://codeberg.org/ladigitale/digiview)) `AGPL-3.0` `Node.js/PHP`
- [Digiwords](https://ladigitale.dev/digiwords/) - 用于创建词云的简单在线应用程序（文档以法语提供）。 ([源代码](https://codeberg.org/ladigitale/digiwords)) `AGPL-3.0` `Node.js/PHP`
- [DOCAT](https://github.com/docat-org/docat) - 托管您的文档。简单。有版本。时尚。 `MIT` `Python/Docker`
- [Domain Locker](https://domain-locker.com) - 域名投资组合管理和追踪器。 ([演示](https://demo.domain-locker.com), [源代码](https://github.com/lissy93/domain-locker)) `MIT` `Deno/Docker`
- [DOMJudge](https://www.domjudge.org/) - 用于举办编程竞赛的系统，如 ICPC 区域赛和世界总决赛等。 ([演示](https://www.domjudge.org/demo), [源代码](https://github.com/DOMjudge/domjudge)) `GPL-2.0/BSD-3-Clause/MIT` `PHP`
- [ESMira](https://esmira.kl.ac.at) - 运行纵向研究（ESM、AA、EMA），数据收集和与参与者的通信完全匿名。 ([演示](https://demo-esmira.kl.ac.at/#admin,username:demo,password:demodemodemo), [源代码](https://github.com/KL-Psychological-Methodology/ESMira)) `AGPL-3.0` `PHP`
- [F-Droid](https://f-droid.org) - 用于维护F-Droid存储库系统的服务器工具。 ([源代码](https://gitlab.com/fdroid/fdroidserver)) `AGPL-3.0` `Python/Docker/deb`
- [Flyimg](https://flyimg.io) - 实时调整和裁剪图像。使用ImageMagick、高效的缓存系统，获得经过MozJPEG、WebP或PNG优化的图像。 ([演示](https://demo.flyimg.io), [源代码](https://github.com/flyimg/flyimg)) `MIT` `Docker`
- [Fog](https://www.fogproject.org/) - 克隆/镜像解决方案与救援套件。 ([源代码](https://github.com/FOGProject/fogproject)) `GPL-3.0` `PHP/Shell`
- [Geeftlist](https://codeberg.org/nanawel/geeftlist) - 供朋友和家人之间管理、共享和预定礼物的协作平台。 `GPL-3.0` `Docker`
- [google-webfonts-helper](https://github.com/majodev/google-webfonts-helper) `⚠` - 无麻烦地自托管Google字体的方式。获取eot、ttf、svg、woff和woff2文件 + CSS片段。 ([演示](https://gwfh.mranftl.com/fonts)) `MIT` `Node.js`
- [Habitica](https://habitica.com/) - 将你的目标变成角色扮演游戏的习惯追踪应用。 ([源代码](https://github.com/HabitRPG/habitica)) `GPL-3.0/CC-BY-SA-3.0` `Node.js/Docker`
- [HortusFox](https://hortusfox.github.io) - 协作式植物管理与追踪系统，适合植物爱好者。 ([源代码](https://github.com/danielbrendel/hortusfox-web)) `MIT` `PHP/Docker`
- [ImgCompress](https://imgcompress.karimzouine.com) - 完全运行于 Docker 的图像处理工具，支持压缩、格式转换、调整尺寸、批量处理，以及使用本地 AI 去除背景。 ([源代码](https://github.com/karimz1/imgcompress)) `GPL-3.0` `Docker`
- [Infisical Community Edition](https://infisical.com/) - 平台用于管理机密、证书和特权访问。 ([源代码](https://github.com/Infisical/infisical)) `MIT` `Docker/K8S/deb`
- [iSponsorBlockTV](https://github.com/dmunozv04/iSponsorBlockTV) `⚠` - 阻止和跳过赞助内容，同时在 YouTube 上静音和跳过广告。 `GPL-3.0` `Docker/Python`
- [IT-Tools by sharevb](https://github.com/sharevb/it-tools) - 开发者的实用在线工具集合（[it-tools](https://github.com/CorentinTh/it-tools) 的分支）。 ([演示](https://sharevb-it-tools.vercel.app/)) `GPL-3.0` `Docker`
- [Jelu](https://bayang.github.io/jelu-web) - 已读和待读书单追踪器。 ([源代码](https://github.com/bayang/jelu)) `MIT` `Java/Docker`
- [jetlog](https://github.com/pbogre/jetlog) - 个人飞行跟踪器和查看器。 `GPL-2.0` `Docker`
- [Kasm Workspaces](https://kasmweb.com/) - 将容器化的应用程序和桌面流式传输给终端用户。示例包括在浏览器中运行的Ubuntu，或者仅运行Chrome、OpenOffice、Gimp、Filezilla等单个应用程序。 ([演示](https://www.kasmweb.com/#demo), [源代码](https://github.com/kasmtech)) `GPL-3.0` `Docker`
- [Koillection](https://koillection.github.io/) - Koillection 是一项服务，允许用户管理任何类型的收藏品。 ([源代码](https://github.com/benjaminjonard/koillection)) `MIT` `Docker/PHP`
- [LanguageTool](https://languagetool.org/) - 适用于20多种语言的校对工具。它能发现许多简单拼写检查器无法检测到的错误。 ([源代码](https://github.com/languagetool-org/languagetool), [客户端](https://languagetool.org/insights/post/product-windows-app/)) `LGPL-2.1` `Java/Docker`
- [Libre Translate](https://libretranslate.com/) - 机器翻译 API。 ([源代码](https://github.com/LibreTranslate/LibreTranslate)) `AGPL-3.0` `Docker/Python`
- [LubeLogger](https://lubelogger.com) - 基于 Web 的车辆维护与燃油里程追踪工具。 ([演示](https://github.com/hargata/lubelog?tab=readme-ov-file#demo), [源代码](https://github.com/hargata/lubelog)) `MIT` `Docker/K8S/C#`
- [mosparo](https://mosparo.io/) - 现代的垃圾邮件保护工具。用简单易用的垃圾邮件保护解决方案替代其他验证码方法。 ([源代码](https://github.com/mosparo/mosparo)) `MIT` `PHP`
- [Movary](https://github.com/leepeuker/movary) `⚠` - 用于追踪和评分已观看电影的 Web 应用。 ([演示](https://github.com/leepeuker/movary?tab=readme-ov-file#demo)) `MIT` `Docker/PHP`
- [Neko](https://neko.m1k1o.net) - 在 Docker 中运行并使用 WebRTC 的虚拟浏览器。 ([源代码](https://github.com/m1k1o/neko)) `Apache-2.0` `Docker/Go`
- [OmniTools](https://omnitools.app/) - 强大的基于 Web 的日常工具集合（编码、图像/视频处理、PDF 操作或数字运算等）。 ([源代码](https://github.com/iib0011/omni-tools)) `MIT` `Docker`
- [Open-Meteo](https://open-meteo.com/) - 提供来自各主要国家气象服务机构的开放数据预报、历史数据和气候数据的天气 API。 ([演示](https://open-meteo.com/en/docs), [源代码](https://github.com/open-meteo/open-meteo)) `AGPL-3.0` `Docker`
- [OpenReader](https://openreader.richardr.dev/) - EPUB、PDF、DOCX、MD 和 TXT 文件的文本转语音文档阅读器。使用高质量 TTS 实时朗读文档，或提取有声书。 ([演示](https://openreader.richardr.dev/), [源代码](https://github.com/richardr1126/openreader)) `MIT` `Docker`
- [OpenZiti](https://openziti.io/) - 功能齐全的零信任全网格覆盖网络。内置双因素认证支持，提供所有主流桌面/移动操作系统的客户端。 ([源代码](https://github.com/openziti/ziti)) `Apache-2.0` `Go`
- [Operational.co](https://operational.co) - 在实时时间线中接收来自您产品的警报。 ([演示](https://app.operational.co/?signinas=kevin), [源代码](https://github.com/operational-co/operational.co)) `AGPL-3.0` `Node.js/Docker`
- [penpot](https://penpot.app/) - 面向跨领域团队的基于 Web 的设计和原型制作平台。 ([源代码](https://github.com/penpot/penpot)) `MPL-2.0` `Docker`
- [POMjs](https://password.oppetmoln.se/) - 随机密码生成器。 ([源代码](https://github.com/joho1968/POMjs)) `GPL-2.0` `JavaScript`
- [Pønskelisten](https://github.com/aunefyren/poenskelisten) - 分享愿望清单，并协作准备礼物与赠品。 `GPL-3.0` `Docker/Go`
- [Reactive Resume](https://rxresu.me/) - 独特的简历生成器，注重隐私保护。完全安全、可定制、可移植、开源且永久免费。 ([演示](https://rxresu.me/), [源代码](https://github.com/AmruthPillai/Reactive-Resume)) `MIT` `Docker/Node.js`
- [revealjs](https://revealjs.com) - 使用 HTML 轻松创建漂亮演示文稿的框架。 ([演示](https://revealjs.com/), [源代码](https://github.com/hakimel/reveal.js)) `MIT` `JavaScript`
- [Revive Adserver](https://www.revive-adserver.com/) - 广告投放系统，前身为 OpenX Adserver 和 phpAdsNew。 ([源代码](https://github.com/revive-adserver/revive-adserver)) `GPL-2.0` `PHP`
- [SANE Network Scanning](http://sane-project.org/) - 允许远程客户端访问本地主机上可用的图像采集设备（扫描仪）。 ([源代码](http://www.sane-project.org/cvs.html)) `GPL-2.0` `C`
- [string.is](https://string.is/) - 面向开发人员的开源、注重隐私的在线字符串工具包。 ([源代码](https://github.com/recurser/string-is)) `AGPL-3.0` `Node.js`
- [Teleport](https://goteleport.com/) - 用于 SSH、Kubernetes、Web 应用和数据库的证书颁发机构和访问平面。 ([源代码](https://github.com/gravitational/teleport)) `Apache-2.0` `Go/Docker/K8S`
- [TeslaMate](https://github.com/teslamate-org/teslamate) - 一款强大的特斯拉车辆数据记录器。 `MIT` `Elixir/Docker`
- [Transmute](https://transmute.sh) - 支持图片、视频、音频、JSON、Excel 等格式的文件转换工具，提供超过 2000 种转换方案。 ([源代码](https://github.com/transmute-app/transmute)) `MIT` `Docker`
- [URL-to-PNG](https://github.com/jasonraimondi/url-to-png) - 使用 Playwright 进行并行渲染的 URL 到 PNG 实用工具，支持通过本地、S3 或 CouchDB 进行存储缓存。 `MIT` `Node.js/Docker`
- [Usertour](https://www.usertour.io/) - 用户引导平台，可轻松创建应用内产品演示、清单和问卷。 ([源代码](https://github.com/usertour/usertour/)) `AGPL-3.0` `Docker`
- [Warracker](https://warracker.com) - 保修期追踪工具，可监控到期日、上传收据/文件，并在保修到期前提醒。 ([源代码](https://github.com/sassanix/Warracker)) `AGPL-3.0` `Docker`
- [Wavelog](https://www.wavelog.org) - 针对业余无线电爱好者的基于 Web 的日志软件。提供增强的 QSO 日志记录、统计信息和地图功能。 ([演示](https://demo.wavelog.org), [源代码](https://github.com/wavelog/wavelog)) `MIT` `PHP/Docker`
- [WeeWX](https://weewx.com/) - 用于您的气象站的开源软件。 ([演示](https://weewx.com/showcase.html), [源代码](https://github.com/weewx/weewx)) `GPL-3.0` `Python/deb`
- [WeTTY](https://butlerx.github.io/wetty/#/) - 通过http/https在浏览器中使用的终端。 ([源代码](https://github.com/butlerx/wetty)) `MIT` `Docker/Node.js`
- [Wishlist](https://github.com/cmintey/wishlist) - 可与亲友分享的愿望清单应用。 `MIT` `Docker/K8S`
- [Yamtrack](https://github.com/FuzzyGrim/Yamtrack) `⚠` - 媒体追踪器，可用于电影、电视剧、动漫、漫画、电子游戏和书籍。 ([演示](https://github.com/FuzzyGrim/Yamtrack?tab=readme-ov-file#demo)) `AGPL-3.0` `Docker/Python`
- [Zero-TOTP](https://zero-totp.com) - 基于零知识加密的完整、可靠、安全且零信任的 Web 应用，用于存储您的 TOTP 验证码。 ([源代码](https://github.com/SeaweedbrainCY/zero-totp)) `GPL-3.0` `Docker`


### 构建和软件组织工具

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

构建和软件组织工具。

- [EasyBuild](https://easybuild.io/) - EasyBuild 以高效的方式为高性能计算（HPC）系统构建软件和模块文件。 ([源代码](https://github.com/easybuilders/easybuild-easyconfigs)) `GPL-2.0` `Python`
- [Environment Modules](https://modules.readthedocs.io/) - Environment Modules 通过 modulefiles 动态修改用户环境。 ([源代码](https://github.com/cea-hpc/modules)) `GPL-2.0` `Tcl`
- [Lmod](https://www.tacc.utexas.edu/research-development/tacc-projects/lmod) - 基于 Lua 的模块系统，轻松处理 MODULEPATH 层级问题。 ([源代码](https://github.com/TACC/Lmod)) `MIT` `Lua`
- [Spack](https://spack.io/) - 灵活的软件包管理器，支持多版本、多配置、多平台和多编译器。 ([源代码](https://github.com/spack/spack)) `MIT/Apache-2.0` `Python`


### 档案和数字保存（DP）

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

数字[存档](https://en.wikipedia.org/wiki/Archival_science)和[保存](https://en.wikipedia.org/wiki/Digital_preservation)软件。

_相关: [备份](#备份), [内容管理系统（CMS）](#内容管理系统（cms）)_

_另见: [awesome-web-archiving](https://github.com/iipc/awesome-web-archiving)_

- [ArchiveBox](https://archivebox.io/) - 从你的书签、浏览历史、RSS 源或其他来源创建网站的 HTML 和截图存档（Wayback Machine 的替代方案）。 ([演示](https://demo.archivebox.io/), [源代码](https://github.com/ArchiveBox/ArchiveBox)) `MIT` `Python/Docker`
- [ArchivesSpace](https://archivesspace.org/) - 用于管理和提供对档案、手稿和数字对象的 Web 访问的档案信息管理应用程序。 ([演示](https://archivesspace.org/application/sandbox), [源代码](https://github.com/archivesspace/archivesspace)) `ECL-2.0` `Ruby`
- [Bichon](https://github.com/rustmailer/bichon) - 电子邮件归档服务器，可从 IMAP 账户同步邮件并建立全文搜索索引，提供 REST API，无需外部数据库，内置支持多账户的 WebUI。 `AGPL-3.0` `Rust/Docker`
- [bitmagnet](https://bitmagnet.io) - BitTorrent 索引器、DHT 爬虫、内容分类器和带有 Web UI、GraphQL API 及 Servarr 集成的种子搜索引擎。 ([源代码](https://github.com/bitmagnet-io/bitmagnet)) `MIT` `Go/Docker`
- [CKAN](https://ckan.org) - 构建开放数据网站。 ([源代码](https://github.com/ckan/ckan)) `AGPL-3.0` `Python`
- [Collective Access - Providence](https://collectiveaccess.org/) - 高度可配置的基于Web的框架，用于管理、描述和发现数字和物理收藏，支持各种元数据标准、数据类型和媒体格式。 ([源代码](https://github.com/collectiveaccess/providence)) `GPL-3.0` `PHP`
- [Eonvelope](https://dacid99.gitlab.io/eonvelope) - 一款电子邮件归档软件，可让您将邮件无限期保存。 ([源代码](https://gitlab.com/dacid99/eonvelope)) `AGPL-3.0` `K8S/Docker`
- [Ganymede](https://github.com/Zibbp/ganymede) `⚠` - Twitch VOD 和直播流归档平台。为每个归档包含渲染的聊天记录。 `GPL-3.0` `Docker`
- [mail-archiver](https://github.com/s1t5/mail-archiver) - 用于归档、搜索和导出多账户邮件的 Web 应用（支持 IMAP、M365 或导入方式）。提供文件夹同步、附件支持、邮箱迁移和仪表板功能。 `GPL-3.0` `Docker`
- [Omeka S](https://omeka.org/s/) - 面向希望将数字文化遗产馆藏与其他在线资源相连接的机构的下一代 Web 发布平台。 ([源代码](https://github.com/omeka/omeka-s)) `GPL-3.0` `Node.js`
- [Open Archiver](https://openarchiver.com/) - 具有全文搜索和电子发现搜索功能的电子邮件归档解决方案。 ([演示](https://github.com/LogicLabs-OU/OpenArchiver?tab=readme-ov-file#-live-demo), [源代码](https://github.com/LogicLabs-OU/OpenArchiver)) `AGPL-3.0` `Docker`
- [Piler](https://www.mailpiler.org/) - 功能丰富的电子邮件归档解决方案。 ([源代码](https://github.com/jsuto/piler/)) `GPL-3.0` `C/Docker/deb`
- [Wallabag](https://www.wallabag.org) - Wallabag，前身是Poche，是一个允许您保存文章以便以提高可读性稍后阅读的Web应用程序。 ([源代码](https://github.com/wallabag/wallabag)) `MIT` `PHP`
- [Wayback](https://github.com/wabarc/wayback) - 用于将网页存档到Internet Archive、archive.today、IPFS和本地文件系统的自托管工具包。 `GPL-3.0` `Go`


### 流媒体

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[流媒体](https://en.wikipedia.org/wiki/Streaming_media)是以连续的方式从源头传递和消费的多媒体，网络元素中几乎没有或没有中间存储。

**请访问 [流媒体 - 音频流媒体](#流媒体 - 音频流媒体), [流媒体 - 多媒体流媒体](#流媒体 - 多媒体流媒体), [流媒体 - 视频流媒体](#流媒体 - 视频流媒体), [媒体管理](#媒体管理)**

_另见: [流媒体系统列表 - Wikipedia](https://en.wikipedia.org/wiki/List_of_streaming_media_systems), [流媒体系统比较 - Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_streaming_media_systems)_



### 流媒体 - 多媒体流媒体

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[多媒体](https://en.wikipedia.org/wiki/Multimedia)流媒体工具和软件。

_相关: [流媒体 - 视频流媒体](#流媒体---视频流媒体), [流媒体 - 音频流媒体](#流媒体---音频流媒体), [媒体管理](#媒体管理)_

- [ClipBucket](https://clipbucket.fr/) - 在几分钟内启动自己的视频分享网站（YouTube/Netflix 克隆）。 ([演示](https://demo.clipbucket.oxygenz.fr/), [源代码](https://github.com/MacWarrior/clipbucket-v5)) `AAL` `Docker/PHP`
- [cmyflix](https://github.com/farfalleflickan/cmyflix) - 简洁的 Plex/Jellyfin 替代品，用于视频流传输。 `AGPL-3.0` `C/deb`
- [Gerbera](https://gerbera.io/) - UPnP 媒体服务器，可让您在家庭网络中流式传输数字媒体，并在各种兼容 UPnP 的设备上收听/观看。 ([源代码](https://github.com/gerbera/gerbera)) `GPL-2.0` `Docker/deb/C++`
- [Icecast 2](https://icecast.org) - 流媒体音频/视频服务器，可用于创建互联网广播电台或私人运行的点唱机等多种应用。 ([源代码](https://gitlab.xiph.org/xiph/icecast-server), [客户端](https://icecast.org/apps/)) `GPL-2.0` `C`
- [Jellyfin](https://jellyfin.org) - 音频、视频、图书、漫画和照片的媒体服务器，具有时尚界面和强大的转码能力。几乎所有现代平台都有客户端，包括Roku、Android TV、iOS和Kodi。 ([演示](https://demo.jellyfin.org/stable), [源代码](https://github.com/jellyfin/jellyfin), [客户端](https://github.com/awesome-jellyfin/awesome-jellyfin)) `GPL-2.0` `C#/deb/Docker`
- [Karaoke Eternal](https://www.karaoke-eternal.com) - 举办令人惊叹的卡拉OK派对，每个人都可以轻松地从手机浏览器中查找并排队歌曲。播放器也完全基于浏览器，支持MP3+G、MP4和WebGL可视化。 ([源代码](https://github.com/bhj/KaraokeEternal)) `ISC` `Docker/Node.js`
- [Kodi](https://kodi.tv/) - 多媒体/娱乐中心，以前被称为 XBMC。适用于 Android、BSD、Linux、macOS、iOS 和 Windows。 ([源代码](https://github.com/xbmc/xbmc)) `GPL-2.0` `C++/deb`
- [Kyoo](https://github.com/zoriya/kyoo) - 创新的媒体浏览器，设计用于无缝流媒体播放动漫、系列和电影，提供动态转码、自动观看历史记录和智能元数据检索等高级功能。 ([演示](https://kyoo.zoriya.dev)) `GPL-3.0` `Docker`
- [MediaMTX](https://mediamtx.org) - 开箱即用、零依赖的实时媒体服务器与代理，支持通过 SRT、WebRTC、RTSP、RTMP、HLS、MPEG-TS、RTP 发布、读取、录制、回放和路由音视频流。 ([源代码](https://github.com/bluenviron/mediamtx), [客户端](https://mediamtx.org/docs/kickoff/introduction)) `MIT` `Go/Docker`
- [Meelo](https://github.com/Arthi-chaud/Meelo) - 面向收藏家和音乐狂热者的个人音乐服务器。 `GPL-3.0` `Docker`
- [MistServer](https://mistserver.org/) - 适用于任何设备和格式的公共领域流媒体服务器。 ([源代码](https://github.com/DDVTECH/mistserver)) `Unlicense` `C++`
- [NymphCast](http://nyanko.ws/nymphcast.php) - 将您选择的支持Linux的硬件转换为电视或音响的音频和视频源（替代品Chromecast）。 ([源代码](https://github.com/MayaPosch/NymphCast)) `BSD-3-Clause` `C++`
- [Rygel](https://gnome.pages.gitlab.gnome.org/rygel/) - UPnP AV 媒体服务器，可轻松共享音频、视频和图片。媒体播放器软件可通过 Rygel 变为 MediaRenderer，并可被 UPnP 或 DLNA 控制器远程控制。 ([源代码](https://gitlab.gnome.org/GNOME/rygel/)) `LGPL-2.1` `C`
- [Stash](https://stashapp.cc) - 一个基于Web的成人媒体库组织器和播放器，具有自动标记和元数据抓取支持。 ([源代码](https://github.com/stashapp/stash)) `AGPL-3.0` `Docker/Go`
- [µStreamer](https://github.com/pikvm/ustreamer) - 轻量级且非常快速的服务器，用于从任何V4L2设备向网络传输MJPEG视频。 `GPL-3.0` `C/deb`
- [üWave](https://u-wave.net/) `⚠` - 自托管的协作式听歌平台。用户轮流播放来自各种媒体源（如YouTube和SoundCloud）的媒体内容，包括歌曲、演讲、游戏视频或其他任何内容。 ([演示](https://wlk.yt/), [源代码](https://github.com/u-wave)) `MIT` `Node.js`


### 流媒体 - 视频流媒体

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[视频](https://en.wikipedia.org/wiki/Video)流媒体工具和软件。

_相关: [视频监控](#视频监控), [流媒体 - 多媒体流媒体](#流媒体---多媒体流媒体), [相册](#相册), [媒体管理](#媒体管理)_

- [CyTube](https://github.com/calzoneman/sync) - 同步媒体、聊天等，支持任意数量的频道。 ([演示](https://cytu.be)) `MIT` `Node.js`
- [Invidious](https://github.com/iv-org/invidious) `⚠` - 替代YouTube前端。 ([演示](https://docs.invidious.io/instances/)) `AGPL-3.0` `Docker/Crystal`
- [MediaCMS](https://mediacms.io) - 现代化、功能完善的开源视频与媒体 CMS，基于 Python/Django/React 开发，提供 REST API。 ([源代码](https://github.com/mediacms-io/mediacms)) `AGPL-3.0` `Python/Docker`
- [OvenMediaEngine](https://github.com/OvenMediaLabs/OvenMediaEngine) - 具有亚秒级延迟的流媒体服务器。 ([演示](https://demo.ovenplayer.com)) `AGPL-3.0` `C++/Docker`
- [Owncast](https://owncast.online/) - 去中心化的单用户实时视频流和聊天服务器，用于运行类似于主流选项的自己的实时流。 ([源代码](https://github.com/owncast/owncast)) `MIT` `Go`
- [PeerTube](https://joinpeertube.org/en/) - 使用P2P（BitTorrent）直接在Web浏览器中进行的分散式视频流平台。 ([源代码](https://github.com/Chocobozzz/PeerTube)) `AGPL-3.0` `Node.js`
- [Rapidbay](https://github.com/hauxir/rapidbay/) - 支持在浏览器或 Chromecast/AppleTV/智能电视中搜索和播放种子视频的流媒体服务/种子客户端。 `MIT` `Python/Docker`
- [Restreamer](https://datarhei.github.io/restreamer/) - 无需流媒体服务商，即可在你的网站上访问 H.264 实时视频流。 ([源代码](https://github.com/datarhei/restreamer)) `Apache-2.0` `Node.js/Docker`
- [SRS](https://ossrs.net) - 一个简单、高效和实时的视频服务器，支持RTMP、WebRTC、HLS、HTTP-FLV和SRT。 ([源代码](https://github.com/ossrs/srs)) `MIT` `Docker/C++`
- [SyncTube](https://github.com/RblSb/SyncTube) - 轻量级且非常简单设置的 CyTube 替代方案，用于与朋友一起观看视频和聊天。 `MIT` `Node.js/Haxe`
- [Tube Archivist](https://tubearchivist.com/) `⚠` - 整理、搜索和享受您的YouTube收藏。通过元数据索引和用户友好的界面订阅、下载和跟踪已观看内容。 ([源代码](https://github.com/tubearchivist/tubearchivist), [客户端](https://docs.tubearchivist.com/faq/#how-do-i-import-my-videos-to-emby-plex-jellyfin-kodi)) `GPL-3.0` `Docker`
- [Tube](https://git.mills.io/prologic/tube) - 类似 Youtube（_无审查且不含您不需要的功能！_）的视频共享应用，使用 Go 编写，还支持自动转码为 MP4 H.265 AAC、多个合集和 RSS 订阅。 ([演示](https://tube.mills.io)) `MIT` `Go`
- [VideoLAN Client (VLC)](https://www.videolan.org/) - 跨平台的多媒体播放器客户端和服务器，支持大多数多媒体文件以及DVD、音频CD、VCD和各种流媒体协议。 ([源代码](https://code.videolan.org/videolan/vlc)) `GPL-2.0` `C/deb`


### 流媒体 - 音频流媒体

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[音频](https://en.wikipedia.org/wiki/Audio)流媒体工具和软件。

_相关: [媒体管理](#媒体管理)_

- [Ampache](https://ampache.org/) - Web 基础的音频/视频流应用。 ([演示](https://play.dogmazic.net/), [源代码](https://github.com/ampache/ampache)) `AGPL-3.0` `PHP`
- [Audiobookshelf](https://www.audiobookshelf.org/) - 有声书和播客服务器。支持所有音频格式流式播放，跨设备同步进度。配有开源 Android 和 iOS 应用。 ([源代码](https://github.com/advplyr/audiobookshelf), [客户端](https://github.com/advplyr/audiobookshelf-app)) `GPL-3.0` `Docker/deb/Node.js`
- [Audioserve](https://github.com/izderadicka/audioserve) - 简单的个人服务器，用于从目录中提供音频文件（有声书、音乐、播客等）。专注于简单性，支持在客户端之间同步播放位置。 `MIT` `Rust`
- [AzuraCast](https://www.azuracast.com/) - 现代且易用的网络电台管理套件。 ([源代码](https://github.com/AzuraCast/AzuraCast)) `Apache-2.0` `Docker`
- [Beets](https://beets.io/) - 音乐库管理器和MusicBrainz标签编辑器（命令行和Web界面）。 ([源代码](https://github.com/beetbox/beets)) `MIT` `Python/deb`
- [Black Candy](https://github.com/blackcandy-org/blackcandy) - 音乐流媒体服务器。 `MIT` `Docker/Ruby`
- [BotWave](https://botwave.dpip.lol) - 基于服务端-客户端架构的 FM 广播系统，可远程管理多个树莓派发射器。 ([源代码](https://github.com/dpipstudio/botwave)) `GPL-3.0` `Python`
- [Funkwhale](https://dev.funkwhale.audio/funkwhale) - 现代、基于Web、友好、多用户和免费的音乐服务器。 `BSD-3-Clause` `Python`
- [gonic](https://github.com/sentriz/gonic) - 轻量级音乐流媒体服务器。兼容Subsonic。 `GPL-3.0` `Go/Docker`
- [koel](https://koel.dev/) - 个人音乐流媒体服务器，运行良好。 ([演示](https://demo.koel.dev/), [源代码](https://github.com/koel/koel)) `MIT` `PHP`
- [LibreTime](https://libretime.org) - 网络广播流媒体电台（[Airtime](https://github.com/sourcefabric/Airtime) 的分支）。 ([源代码](https://github.com/LibreTime/libretime)) `AGPL-3.0` `Docker/PHP`
- [LMS](https://github.com/epoupon/lms) - 通过Web界面访问您的自托管音乐。 `GPL-3.0` `Docker/deb/C++`
- [Lyrion Music Server](https://lyrion.org/) - 服务器软件，可控制各种 Squeezebox/Slim Devices 音频播放器及兼容硬件（前身为 Logitech Media Server）。 ([源代码](https://github.com/lms-community/slimserver), [客户端](https://lyrion.org/extensions/applications/)) `GPL-2.0` `deb/Docker/Perl`
- [moOde Audio](https://moodeaudio.org/) - 高保真音乐播放，适用于出色的 Raspberry Pi 单板计算机系列。 ([源代码](https://github.com/moode-player/moode)) `GPL-3.0` `PHP`
- [Mopidy](https://docs.mopidy.com/) `⚠` - 可扩展的音乐服务器。提供 mpd API 的超集，以及与 Spotify、SoundCloud 等第三方服务的集成。 ([源代码](https://github.com/mopidy/mopidy)) `Apache-2.0` `Python/deb`
- [mpd](https://www.musicpd.org/) - 远程播放音乐、流式传输音乐、处理和组织播放列表的守护进程。有许多可用的客户端。 ([源代码](https://github.com/MusicPlayerDaemon/MPD), [客户端](https://www.musicpd.org/clients/)) `GPL-2.0` `C++`
- [mStream](https://mstream.io/) - 具有 GUI 管理工具的音乐流媒体服务器。支持 Mac、Windows 和 Linux。 ([源代码](https://github.com/IrosTheBeggar/mStream)) `GPL-3.0` `Node.js`
- [multi-scrobbler](https://foxxmd.github.io/multi-scrobbler) - 将多个来源的播放记录到多个 scrobbling 服务中。 ([源代码](https://github.com/FoxxMD/multi-scrobbler)) `MIT` `Node.js/Docker`
- [musikcube](https://musikcube.com/) - 具有 Linux/macOS/Windows/Android 客户端的音频流媒体服务器。 ([源代码](https://github.com/clangen/musikcube)) `BSD-3-Clause` `C++/deb`
- [Navidrome Music Server](https://www.navidrome.org) - 现代音乐服务器和流媒体服务器，兼容Subsonic/Airsonic。 ([演示](https://www.navidrome.org/demo), [源代码](https://github.com/navidrome/navidrome), [客户端](https://www.navidrome.org/docs/overview/#apps)) `GPL-3.0` `Docker/Go`
- [Pinepods](https://www.pinepods.online/) - 支持多用户的播客管理系统。Pinepods 使用中央数据库，因此收听时长、主题等设置可在不同设备之间同步。 ([演示](https://try.pinepods.online), [源代码](https://github.com/madeofpendletonwool/PinePods)) `GPL-3.0` `Docker`
- [Polaris](https://github.com/agersant/polaris) - 针对大型音乐收藏、易用性和高性能优化的音乐浏览和流媒体应用。 `MIT` `Rust/Docker`
- [Snapcast](https://github.com/snapcast/snapcast) - 同步多房间音频服务器。 `GPL-3.0` `C++/deb`
- [Stretto](https://github.com/benkaiser/stretto) `⚠` - 具有Youtube/Soundcloud导入和iTunes/Spotify发现功能的音乐播放器。 ([演示](https://next.kaiserapps.com), [客户端](https://github.com/benkaiser/stretto-mobile-next)) `MIT` `Node.js`
- [Supysonic](https://github.com/spl0k/supysonic) - Subsonic 服务器 API 的 Python 实现。 `AGPL-3.0` `Python/deb`
- [SwingMusic](https://swingmusic.vercel.app/) - Swing Music 是一个漂亮的、自托管的音乐播放器和本地音频文件的流媒体服务器。就像更酷的 Spotify ... 但请自备音乐。 ([源代码](https://github.com/swingmx/swingmusic)) `MIT` `Python/Docker`
- [vod2pod-rss](https://github.com/madiele/vod2pod-rss) `⚠` - 将YouTube和Twitch频道转换为播客，无需存储。实时转码VoDs为MP3 192k，生成供播客客户端使用的RSS源。 `MIT` `Docker`


### 游戏

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

多人游戏服务器和[浏览器游戏](https://en.wikipedia.org/wiki/Browser_game)。

_相关: [游戏 - 管理工具和控制面板](#游戏---管理工具和控制面板)_

- [0 A.D.](https://play0ad.com/) - 跨平台的古代战争即时战略游戏。 ([源代码](https://gitea.wildfiregames.com/0ad/0ad)) `MIT/GPL-2.0/Zlib` `C++/C/deb`
- [A Dark Room](https://github.com/doublespeakgames/adarkroom) - 适用于浏览器的极简主义文本冒险游戏。 ([演示](https://adarkroom.doublespeakgames.com/)) `MPL-2.0` `JavaScript`
- [DDraceNetwork](https://ddnet.org/) - DDRace 的合作平台游戏版本，基于 Teeworlds 修改，具有独特的合作玩法。 ([源代码](https://github.com/ddnet/ddnet)) `Zlib` `C++`
- [Digibuzzer](https://digibuzzer.app/) - 在连接的蜂鸣器周围创建虚拟游戏房间（法语文档）。 ([演示](https://digibuzzer.app/), [源代码](https://codeberg.org/ladigitale/digibuzzer)) `AGPL-3.0` `Node.js`
- [Hypersomnia](https://github.com/TeamHypersomnia/Hypersomnia) - 竞技类俯视射击游戏，融合了反恐精英与迈阿密热线的玩法。可在 Linux、Windows、MacOS 及网页端运行。 ([演示](https://hypersomnia.io)) `AGPL-3.0` `C++/Docker`
- [Lila](https://lichess.org/) - 无广告的国际象棋服务器，为 lichess.org 提供支持，并提供官方 iOS 和 Android 客户端应用。 ([源代码](https://github.com/lichess-org/lila)) `AGPL-3.0` `Scala`
- [Luanti](https://www.luanti.org/) - 体素游戏引擎（前身为 Minetest）。畅玩多款游戏，按喜好修改游戏，创建自己的游戏，或加入多人服务器对战。 ([源代码](https://github.com/luanti-org/luanti)) `LGPL-2.1/MIT/Zlib` `C++/Lua/deb`
- [Mindustry](https://mindustrygame.github.io/) - 类似于 Factorio 的塔防游戏。建立生产链以获取更多资源，并构建复杂的设施。 ([源代码](https://github.com/Anuken/Mindustry)) `GPL-3.0` `Java`
- [MTA:SA](https://multitheftauto.com/) `⚠` - 为 Rockstar North 的《侠盗猎车手》系列游戏添加网络联机功能，这些游戏原本并不具备此功能。 ([源代码](https://github.com/multitheftauto/mtasa-blue)) `GPL-3.0` `C++`
- [OpenTTD](https://www.openttd.org/) - 交通大亨模拟游戏。 ([源代码](https://github.com/OpenTTD/OpenTTD), [客户端](https://bananas.openttd.org/)) `GPL-2.0` `C++/Docker`
- [piqueserver](https://github.com/piqueserver/piqueserver) - OpenSpades 的服务器，OpenSpades 是一个第一人称射击游戏，背景是一个可破坏的体素世界。 ([客户端](https://github.com/yvt/openspades)) `GPL-3.0` `Python/C++`
- [Posio](https://github.com/abrenaut/posio) - 地理多人游戏。 `MIT` `Python`
- [Razzia](https://github.com/Ralex91/Razzia) - 专为小型自托管活动设计的测验游戏平台（Kahoot! 的替代品）。 `MIT` `Node.js/Docker`
- [Red Eclipse 2](https://www.redeclipse.net/) - 类似于《虚幻竞技场》的竞技场第一人称射击游戏。 ([源代码](https://github.com/redeclipse/base)) `Zlib/MIT/CC-BY-SA-4.0` `C/C++/deb`
- [Scribble.rs](https://github.com/scribble-rs/scribble.rs) - 一个基于网络的你画我猜游戏。 ([演示](https://scribblers.fly.dev)) `BSD-3-Clause` `Go/Docker`
- [Suroi](https://suroi.io/) - 一款受 surviv.io 启发的开源二维大逃杀游戏。 ([演示](https://suroi.io/), [源代码](https://github.com/HasangerGames/suroi)) `GPL-3.0` `Node.js`
- [The Battle for Wesnoth](https://github.com/wesnoth/wesnoth) - 《威斯诺斯之战》是一款开源的、回合制的战术策略游戏，以高奇幻为主题，提供单人游戏和在线/热座多人对战。 `GPL-2.0` `C++/deb`
- [Veloren](https://veloren.net/) - 多人在线角色扮演游戏。开源游戏，灵感来自Cube World、塞尔达传说、矮人要塞和Minecraft。 ([源代码](https://gitlab.com/veloren/veloren)) `GPL-3.0` `Rust`
- [Zero-K](https://zero-k.info/) - 在Springrts引擎上的开源项目。Zero-K是一款传统的实时战略游戏，侧重于通过地形操作、物理和大量独特单位的玩家创造力，同时保持平衡以支持竞技游戏。 ([源代码](https://github.com/ZeroK-RTS/Zero-K)) `GPL-2.0` `Lua`


### 游戏 - 管理工具和控制面板

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

用于管理游戏服务器和游戏库的实用工具。

_相关: [游戏](#游戏)_

- [auto-mcs](https://www.auto-mcs.com) - 跨平台的 Minecraft 服务器管理器。 ([源代码](https://github.com/macarooni-man/auto-mcs)) `AGPL-3.0` `Python`
- [Calagopus](https://calagopus.com) - 现代化游戏服务器管理面板，支持部署、监控和管理 Minecraft、Hytale 等游戏服务器。 ([源代码](https://github.com/calagopus/panel)) `MIT` `Rust/Docker/deb`
- [Crafty Controller](https://craftycontrol.com/) - 一个 Minecraft 启动器和管理器，允许用户通过用户友好的界面启动和管理 Minecraft 服务器。 ([源代码](https://gitlab.com/crafty-controller/crafty-4)) `GPL-3.0` `Docker/Python`
- [Drop](https://droposs.org) - 游戏发行平台，旨在高效地分发和共享无 DRM 的游戏（Steam、GameVault 的替代品）。 ([源代码](https://github.com/Drop-OSS/drop), [客户端](https://github.com/Drop-OSS/drop-app)) `AGPL-3.0` `Docker`
- [EasyWI](https://easy-wi.com) - Easy-Wi 是一个 Web 界面，允许您管理服务器守护程序，如游戏服务器。此外，它为您提供了一个包括全自动游戏和语音服务器租赁服务的 CMS。 ([源代码](https://github.com/easy-wi/developer/)) `GPL-3.0` `PHP/Shell`
- [GameAP](https://gameap.com/) - 用于在 Linux 和 Windows 上管理游戏服务器的游戏管理面板。 ([演示](https://demo.gameap.com/), [源代码](https://github.com/gameap/gameap), [客户端](https://plugins.gameap.dev/)) `MIT` `Go/Docker`
- [Gameyfin](https://gameyfin.org) - 视频游戏库管理器，支持自动扫描、网页访问、下载和插件支持。 ([源代码](https://github.com/gameyfin/gameyfin)) `AGPL-3.0` `Docker`
- [Gaseous Server](https://github.com/gaseous-project/gaseous-server) `⚠` - 游戏 ROM 管理器，内置基于 Web 的模拟器，使用多个来源识别并提供元数据。 `AGPL-3.0` `Docker/.NET`
- [Lancache](https://lancache.net) `⚠` - 简化的局域网派对游戏缓存工具。 ([源代码](https://github.com/lancachenet/monolithic)) `MIT` `Docker/Shell`
- [LinuxGSM](https://linuxgsm.com/) - Linux下专用游戏服务器的部署和管理的命令行工具：支持超过120种游戏。 ([源代码](https://github.com/GameServerManagers/LinuxGSM)) `MIT` `Shell`
- [Minus Games](https://accessory.github.io/minus_games_user_guide) - 在多台设备间同步游戏和存档文件。 ([源代码](https://github.com/Accessory/minus_games)) `MIT` `Rust`
- [Ownfoil](https://github.com/a1ex4/ownfoil) - Nintendo Switch 媒体库管理器，支持自动化文件识别整理、缺失更新/DLC 检测，并可将媒体库共享给多个客户端。 `AGPL-3.0` `Docker/Python`
- [Pelican Panel](https://pelican.dev/) - 游戏服务器的管理Web应用，提供一个用户友好的界面用于部署、配置和管理服务器、服务器监控工具以及广泛的自定义选项（Pterodactyl的分支）。 ([源代码](https://github.com/pelican-dev/panel)) `AGPL-3.0` `PHP/Docker`
- [Pterodactyl](https://pterodactyl.io/) - 用于游戏服务器的管理面板，具有直观的用户界面。 ([源代码](https://github.com/pterodactyl/panel)) `MIT` `PHP`
- [PufferPanel](https://www.pufferpanel.com/) - 面向小型网络和游戏服务器提供商设计的游戏服务器管理面板。 ([源代码](https://github.com/pufferpanel/pufferpanel)) `Apache-2.0` `Go`
- [Retrom](https://github.com/JMBeresford/retrom) - 私有云游戏库分发服务器 + 前端/启动器。 `GPL-3.0` `Docker/Rust`
- [RomM](https://romm.app/) `⚠` - 适用于复古游戏的 ROM 管理器，可用于组织、丰富和游玩游戏，支持 400 多个平台。 ([演示](https://demo.romm.app/), [源代码](https://github.com/rommapp/romm)) `AGPL-3.0` `Docker`
- [SourceBans++](https://sbpp.github.io/) - 用于运行在Source引擎上的游戏的管理员、封禁和通信管理系统。 ([源代码](https://github.com/sbpp/sourcebans-pp)) `CC-BY-SA-4.0` `PHP`
- [Sunshine](https://app.lizardbyte.dev/Sunshine/) - 用于 Moonlight 的远程游戏流主机，支持高达每秒 120 帧和 4K 分辨率。 ([源代码](https://github.com/LizardByte/Sunshine)) `GPL-3.0` `C++/deb/Docker`


### 版本控制

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

软件版本管理与修订控制。

- [Darcs](https://darcs.net/) - 跨平台版本控制系统，类似 git、mercurial 或 svn，但采用完全不同的思路：关注变更而非快照。 ([源代码](https://darcs.net/releases/)) `GPL-2.0` `Haskell`
- [Git](https://git-scm.com/) - 分布式修订控制和源码管理（SCM），强调速度。 ([源代码](https://github.com/git/git)) `GPL-2.0` `C`
- [Mercurial](https://www.mercurial-scm.org/) - 分布式源码控制管理工具。 ([源代码](https://repo.mercurial-scm.org/hg/file/tip)) `GPL-2.0` `Python/C/Rust`
- [Subversion](https://subversion.apache.org/) - 客户端-服务器修订控制系统。 ([源代码](https://svn.apache.org/repos/asf/subversion/trunk/)) `Apache-2.0` `C`


### 物联网（IoT）

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[物联网](https://en.wikipedia.org/wiki/Internet_of_things)描述具有传感器、处理能力、软件和其他技术的物理对象，通过互联网与其他设备连接并交换数据。

- [Domoticz](https://www.domoticz.com/) - 家庭自动化系统，可让您监视和配置各种设备，如：灯光、开关、各种传感器/仪表，如温度、雨量、风速、紫外线、电、气体、水等等。 ([源代码](https://github.com/domoticz/domoticz), [客户端](https://github.com/domoticz/domoticz-android)) `GPL-3.0` `C/C++/Docker/Shell`
- [EMQX](https://www.emqx.io/) - 可扩展的 MQTT 消息代理。单个集群可连接超过 1 亿物联网设备，以 1 毫秒延迟实现每秒 100 万条消息的实时数据传输与处理。 ([演示](https://www.emqx.com/en/mqtt/public-mqtt5-broker), [源代码](https://github.com/emqx/emqx)) `Apache-2.0` `Docker/Erlang`
- [evcc](https://evcc.io/) - 可扩展电动汽车充电控制器和家庭能源管理系统。 ([源代码](https://github.com/evcc-io/evcc)) `MIT` `deb/Docker/Go`
- [FHEM](https://fhem.de/fhem.html) - 自动化家庭中的常见任务，如切换灯光和加热。它还可以用于记录温度或功耗等事件。您可以通过网页或智能手机前端、telnet 或直接通过 TCP/IP 进行控制。 ([源代码](https://svn.fhem.de/trac)) `GPL-3.0` `Perl`
- [FlowForge](https://flowforge.com/) - 以可靠、可扩展和安全的方式部署 Node-RED 应用程序。FlowForge 平台为 Node-RED 开发团队提供 DevOps 能力。 ([源代码](https://github.com/FlowFuse/flowfuse)) `Apache-2.0` `Node.js/Docker/K8S`
- [FMD Server](https://fmd-foss.org) - 与 FMD（Find My Device）Android 应用程序通信的服务器，用于定位和控制您的设备。 ([源代码](https://gitlab.com/fmd-foss/fmd-server), [客户端](https://gitlab.com/fmd-foss/fmd-android)) `GPL-3.0` `Docker/Go`
- [Gladys](https://gladysassistant.com/) - 注重隐私的家庭助理。 ([源代码](https://github.com/GladysAssistant/Gladys)) `Apache-2.0` `Node.js/Docker`
- [Home Assistant](https://home-assistant.io/) - 家庭自动化平台。 ([演示](https://home-assistant.io/demo/), [源代码](https://github.com/home-assistant/core)) `Apache-2.0` `Python/Docker`
- [ioBroker](https://www.iobroker.net/) - 面向物联网的集成平台，专注于建筑自动化、智能计量、环境辅助生活、过程自动化、可视化和数据记录。 ([源代码](https://github.com/ioBroker/ioBroker)) `MIT` `Node.js`
- [LHA](https://github.com/javalikescript/lha) - 轻量级家庭自动化应用，支持通过 Blockly、HTML 或 Lua 完全扩展，内置 ConBee、Philips Hue 和 Z-Wave JS 等扩展。 `MIT` `Lua`
- [Node RED](https://nodered.org/) - 基于浏览器的流程编辑器，帮助您将硬件设备、API和在线服务连接起来，创建物联网（IoT）解决方案。 ([源代码](https://github.com/node-red/node-red)) `Apache-2.0` `Node.js/Docker`
- [Onloc](https://onloc.app) - 实时位置追踪与共享工具，支持对丢失或被盗手机进行远程控制和锁定。 ([源代码](https://github.com/onloc-app/onloc-api), [客户端](https://github.com/onloc-app/onloc-android)) `AGPL-3.0` `Docker`
- [openHAB](https://www.openhab.org) - 面向家庭自动化的供应商和技术无关的开源软件。 ([源代码](https://github.com/openhab/openhab-core)) `EPL-2.0` `Java`
- [OpenRemote](https://openremote.io) - 物联网资产管理、流程规则和 WHEN-THEN 规则、数据可视化、边缘网关。 ([演示](https://demo.openremote.io/), [源代码](https://github.com/openremote/openremote)) `AGPL-3.0` `Java`
- [SIP Irrigation Control](https://dan-in-ca.github.io/SIP/) - 用于喷头/灌溉控制的开源软件。 ([源代码](https://github.com/Dan-in-CA/SIP)) `GPL-3.0` `Python`
- [SOLECTRUS](https://solectrus.de) - 光伏仪表盘，展示能量生产与消耗，并计算成本与节省。 ([演示](https://demo.solectrus.de), [源代码](https://github.com/solectrus/solectrus)) `AGPL-3.0` `Docker`
- [Tasmota](https://tasmota.com) - 用于ESP设备的开源固件。具备快速设置和更新的完全本地控制。支持MQTT、Web UI、HTTP或串口控制。可使用定时器、规则或脚本进行自动化。与家庭自动化解决方案集成。 ([源代码](https://github.com/arendst/Tasmota)) `GPL-3.0` `C/C++`
- [Thingsboard](https://thingsboard.io/) - 开源的物联网平台 - 设备管理、数据收集、处理和可视化。 ([演示](https://demo.thingsboard.io/signup), [源代码](https://github.com/thingsboard/thingsboard)) `Apache-2.0` `Java/Docker/K8S`
- [WebThings Gateway](https://webthings.io/gateway/) - WebThings是Web of Things的开源实现，包括WebThings Gateway和WebThings Framework。 ([源代码](https://github.com/WebThingsIO/gateway)) `MPL-2.0` `Node.js`


### 生成式人工智能（GenAI）

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[生成式人工智能（GenAI）](https://en.wikipedia.org/wiki/Generative_artificial_intelligence) 是[人工智能](https://en.wikipedia.org/wiki/Artificial_intelligence)的一个子集，利用生成模型生成文本、图像、视频或其他形式的数据。

- [Agenta](https://agenta.ai/) - 用于提示词管理、大语言模型评估和可观测性的 LLMOps 平台。通过协作式提示词工程构建、评估和监控生产级大语言模型应用程序。 ([源代码](https://github.com/agenta-ai/agenta)) `MIT` `Docker`
- [AnythingLLM](https://anythingllm.com/) - 一体化桌面和 Docker 人工智能应用程序，具有内置 RAG、AI 代理、无代码代理生成器、MCP 兼容性等。 ([源代码](https://github.com/Mintplex-Labs/anything-llm)) `MIT` `Node.js/Docker`
- [Khoj](https://khoj.dev/) - 你的 AI 第二大脑。从网络或本地文档中获取答案，构建自定义智能体，安排自动化任务，进行深度研究。将任意在线或本地 LLM 变成你的个人自主 AI。 ([演示](https://app.khoj.dev/), [源代码](https://github.com/khoj-ai/khoj)) `AGPL-3.0` `Python/Docker`
- [LibreChat](https://www.librechat.ai) `⚠` - 兼容 ChatGPT 的增强型 AI 聊天界面，支持多 AI 提供商、多用户认证、消息搜索和插件。 ([演示](https://chat.librechat.ai), [源代码](https://github.com/danny-avila/LibreChat)) `MIT` `Node.js/Docker`
- [LLM Harbor](https://github.com/av/harbor) - 容器化 LLM 工具包。通过简洁的 CLI 运行 LLM 后端、API、前端及附加服务。 `Apache-2.0` `Docker/Shell`
- [LLMKube](https://llmkube.com) - 面向 llama.cpp 原生 LLM 推理的 Kubernetes Operator，支持 GPU 调度、Apple Silicon Metal 加速及兼容 OpenAI 的 API。 ([源代码](https://github.com/defilantech/LLMKube)) `Apache-2.0` `Go/Docker/K8S`
- [Local Deep Research](https://github.com/LearningCircuit/local-deep-research) - AI 驱动的深度研究工具，支持多源搜索（arXiv、PubMed、网络）、PDF 文本提取和加密本地存储。 `MIT` `Docker/Python`
- [LocalAI](https://localai.io/) - 在本地运行 AI 模型并生成图像和音频（OpenAI 和 Claude 的替代品）。 ([源代码](https://github.com/mudler/LocalAI), [客户端](https://localai.io/gallery.html)) `MIT` `Docker/K8S`
- [Ollama](https://ollama.com/) - 快速上手 Llama 3.3、DeepSeek-R1、Phi-4、Gemma 3 及其他大型语言模型。 ([源代码](https://github.com/ollama/ollama)) `MIT` `Docker/Python`
- [Onyx Community Edition](https://onyx.app) - 可与任何 LLM 配合使用的聊天界面。内置智能体、网页搜索、RAG、MCP、深度研究、40 多种知识源连接器等高级功能。 ([源代码](https://github.com/onyx-dot-app/onyx)) `MIT` `Docker/K8S`
- [Open-WebUI](https://openwebui.com) - 用户友好的 AI 界面，支持 Ollama、OpenAI API。 ([源代码](https://github.com/open-webui/open-webui)) `BSD-3-Clause` `Docker/Python`
- [Vane](https://github.com/ItzCrazyKns/Vane) - AI 驱动的搜索引擎（Perplexity AI 替代品）。 `MIT` `Docker`


### 电子商务

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[电子商务](https://en.wikipedia.org/wiki/E-commerce)软件。

_相关: [社区支持农业（CSA）](#社区支持农业（csa）)_

- [Aimeos](https://aimeos.org/) - 用于构建自定义网店、市场和复杂 B2B 应用的电子商务框架，可与 Laravel 集成并扩展到数十亿商品。 ([演示](https://demo.aimeos.org/), [源代码](https://github.com/aimeos/aimeos)) `LGPL-3.0/MIT` `PHP`
- [Bagisto](https://bagisto.com/en/) - 领先的 Laravel 开源电子商务框架，具备多库存来源、税收、本地化、Dropshipping 等令人兴奋的功能。 ([演示](https://demo.bagisto.com/), [源代码](https://github.com/bagisto/bagisto)) `MIT` `PHP`
- [CoreShop](https://www.coreshop.org) - Pimcore 的电子商务插件。 ([源代码](https://github.com/coreshop/CoreShop)) `GPL-3.0` `PHP`
- [Drupal Commerce](https://drupalcommerce.org) - Drupal CMS 的流行电子商务模块，支持数十种支付、配送和购物相关模块。 ([源代码](https://git.drupalcode.org/project/commerce)) `GPL-2.0` `PHP`
- [EverShop](https://evershop.io/) `⚠` - 具备基本商业功能的电子商务平台。模块化架构，可完全定制。 ([演示](https://demo.evershop.io/), [源代码](https://github.com/evershopcommerce/evershop)) `GPL-3.0` `Docker/Node.js`
- [Magento Open Source](https://business.adobe.com/products/magento/magento-commerce.html) - 领先的开放式全渠道创新解决方案提供商。 ([源代码](https://github.com/magento/magento2)) `OSL-3.0` `PHP`
- [MedusaJs](https://medusajs.com/) - 无头商务引擎，帮助开发者构建出色的数字商务体验。 ([演示](https://next.medusajs.com/), [源代码](https://github.com/medusajs/medusa)) `MIT` `Node.js`
- [Microweber](https://microweber.com/) - 拖放式 CMS 和在线商店。 ([源代码](https://github.com/microweber/microweber)) `MIT` `PHP`
- [myCart](https://github.com/shurco/mycart) `⚠` - 单文件购物车（支持银行卡或加密货币支付）。 `MIT` `Go/Docker`
- [Open Source POS](https://github.com/opensourcepos/opensourcepos) - 开源销售点是一个基于Web的销售点系统。 `MIT` `PHP`
- [OpenCart](https://www.opencart.com) - 购物车解决方案。 ([源代码](https://github.com/opencart/opencart)) `GPL-3.0` `PHP`
- [PrestaShop](https://www.prestashop.com/) - 完全可扩展的电子商务解决方案。 ([演示](https://demo.prestashop.com/), [源代码](https://github.com/PrestaShop/PrestaShop)) `OSL-3.0` `PHP`
- [Pretix](https://pretix.eu/) - 活动票务销售平台。 ([源代码](https://github.com/pretix/pretix)) `AGPL-3.0` `Python/Docker`
- [s-cart](https://s-cart.org/) - 基于 Laravel 框架构建的个人和企业电子商务网站。 ([演示](https://demo.s-cart.org/), [源代码](https://github.com/gp247net/s-cart)) `MIT` `PHP`
- [Saleor](https://saleor.io) - 基于 Django 的开源电子商务商店前端。 ([演示](https://demo.saleor.io/), [源代码](https://github.com/saleor/saleor)) `BSD-3-Clause` `Docker/Python`
- [Shopware Community Edition](https://www.shopware.com/en/community/community-edition/) - 基于 PHP 的德国制造的开源电子商务软件。 ([演示](https://www.shopware.com/en/test-demo/), [源代码](https://github.com/shopware/shopware)) `MIT` `PHP`
- [Solidus](https://solidus.io/) - 一个免费的、开源的电子商务平台，为您的商店提供完全控制。 ([源代码](https://github.com/solidusio/solidus)) `BSD-3-Clause` `Ruby/Docker`
- [Spree Commerce](https://spreecommerce.org) - Spree是一个完整的、模块化的、基于API的Ruby on Rails开源电子商务解决方案。 ([演示](https://demo.spreecommerce.org/), [源代码](https://github.com/spree/spree)) `BSD-3-Clause` `Ruby`
- [Sylius](https://sylius.com) - 基于 Symfony2 的开源全栈电子商务平台。 ([演示](https://sylius.com/try/), [源代码](https://github.com/Sylius/Sylius)) `MIT` `PHP`
- [Thelia](https://thelia.net/) - Thelia 是一款开源且灵活的电子商务解决方案。 ([演示](https://demo.thelia.net/), [源代码](https://github.com/thelia/thelia)) `LGPL-3.0` `PHP`
- [Vendure](https://www.vendure.io) - 一个无界面的商业框架。 ([演示](https://demo.vendure.io), [源代码](https://github.com/vendurehq/vendure)) `MIT` `Node.js`
- [WooCommerce](https://woocommerce.com/) - 基于WordPress的电子商务解决方案。 ([源代码](https://github.com/woocommerce/woocommerce)) `GPL-3.0` `PHP`


### 监控和状态页面

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

用于[监控](https://en.wikipedia.org/wiki/Monitoring#Computing)系统、网络、应用程序和网站的软件。

- [Adagios](http://adagios.org/) - 基于 Web 的 Nagios 配置与监控界面（替代标准界面），并提供 REST 接口。 ([源代码](https://github.com/opinkerfi/adagios)) `AGPL-3.0` `Docker/Python`
- [Alerta](https://alerta.io/) - 分布式、可扩展且灵活的监控系统。 ([源代码](https://github.com/alerta/alerta)) `Apache-2.0` `Python`
- [Beszel](https://beszel.dev/) - 轻量级服务器监控平台，支持 Docker 统计、历史数据和告警功能。 ([源代码](https://github.com/henrygd/beszel)) `MIT` `Go`
- [Cacti](https://www.cacti.net) - 基于 Web 的网络监控与绘图工具。 ([源代码](https://github.com/Cacti/cacti)) `GPL-2.0` `PHP`
- [cadvisor](https://github.com/google/cadvisor) - 分析运行中容器的资源使用和性能特征。 `Apache-2.0` `Go`
- [CheckCle](https://checkcle.io) - 对全栈系统、应用程序和基础设施进行无缝实时监控。 ([源代码](https://github.com/operacle/checkcle)) `MIT` `Docker`
- [checkmk](https://checkmk.com/) - 应用、服务器和网络的综合监控解决方案。 ([源代码](https://github.com/Checkmk/checkmk)) `GPL-2.0` `Python/PHP`
- [cState](https://github.com/cstate/cstate) - 基于 Hugo 的静态状态页面，设计简洁、JS 极少、HTML/CSS 极轻量，支持高度自定义、可选管理面板、只读 API，兼容 IE8+。 ([演示](https://cstate.mnts.lt/)) `MIT` `HTML`
- [dashdot](https://github.com/MauriceNino/dashdot) - 面向小型私有服务器的简单现代服务器仪表盘。 ([演示](https://dash.mauz.dev/)) `MIT` `Node.js/Docker`
- [eZ Server Monitor](https://www.ezservermonitor.com) - 轻量级简单的 Linux 仪表盘监控，提供 Web 和 Bash 应用。 ([源代码](https://github.com/shevabam/ezservermonitor-web)) `GPL-3.0` `PHP/Shell`
- [Gatus](https://gatus.io) - 自动化服务健康状态仪表盘。 ([演示](https://status.twin.sh), [源代码](https://github.com/TwiN/gatus)) `Apache-2.0` `Docker/K8S`
- [glances](https://nicolargo.github.io/glances/) - 开源、跨平台的实时监控工具，支持 CLI 和 Web 仪表盘，多种导出选项。 ([源代码](https://github.com/nicolargo/glances)) `GPL-3.0` `Python`
- [Healthchecks](https://healthchecks.io/docs/self_hosted/) - 针对定时任务、后台服务和计划任务的监控。 ([源代码](https://github.com/healthchecks/healthchecks)) `BSD-3-Clause` `Python`
- [Icinga](https://www.icinga.com/) - Nagios 分支，功能已超越原版，支持集群监控。 ([源代码](https://github.com/Icinga/icinga2)) `GPL-2.0` `C++`
- [Kener](https://kener.ing/) - 带有事件管理功能的状态页面，易于使用和自定义。 ([源代码](https://github.com/rajnandan1/kener)) `MIT` `Node.js/Docker`
- [KuvaszUptime](https://kuvasz-uptime.dev) - 高性能、稳定的可用性与 SSL 监控服务，支持可品牌化状态页面、IAC、Prometheus 集成及完整的 REST API。 ([演示](https://kuvasz-uptime.dev/demo/), [源代码](https://github.com/kuvasz-uptime/kuvasz)) `Apache-2.0` `Docker`
- [LibreNMS](https://www.librenms.org) - 功能丰富的网络监控系统，支持多种设备。 ([源代码](https://github.com/librenms/librenms)) `GPL-3.0` `PHP`
- [Monit](https://mmonit.com/monit/#home) - 管理和监控 Unix 系统的小工具。 ([源代码](https://bitbucket.org/tildeslash/monit/src/master/)) `AGPL-3.0` `C`
- [Munin](https://munin-monitoring.org/) - 网络资源监控工具。 ([源代码](https://github.com/munin-monitoring/munin)) `GPL-2.0` `Perl/Shell`
- [Naemon](https://www.naemon.org/) - 基于 Nagios 4 内核的网络监控工具，性能增强并有新特性。 ([源代码](https://github.com/naemon/naemon-core)) `GPL-2.0` `C`
- [Nagios](https://www.nagios.org/) - 计算机系统、网络和基础设施监控软件。 ([源代码](https://github.com/NagiosEnterprises/nagioscore)) `GPL-2.0` `C`
- [NetXMS](https://www.netxms.org/) - 开源网络与基础设施监控和管理。 ([源代码](https://github.com/netxms/netxms)) `LGPL-3.0/GPL-3.0` `Java/C++/C`
- [Nezha](https://nezha.wiki/en_US/) - 轻量级服务器与网站监控及运维工具。 ([源代码](https://github.com/nezhahq/nezha)) `Apache-2.0` `Go/Shell`
- [Observium Community Edition](http://www.observium.org/) - 网络监控与管理平台，提供实时网络健康与性能洞察。 ([源代码](https://github.com/DanielleHuisman/observium-community-edition)) `QPL-1.0` `PHP`
- [OneUptime](https://oneuptime.com) - 用于监控和管理在线服务的综合解决方案。 ([源代码](https://github.com/oneuptime/oneuptime)) `Apache-2.0` `Docker`
- [openITCOCKPIT Community Edition](https://openitcockpit.io/) - 监控套件，支持与 Naemon、Checkmk、Grafana 等无缝集成。 ([演示](https://demo.openitcockpit.io/), [源代码](https://github.com/it-novum/openITCOCKPIT)) `GPL-3.0` `deb/Docker`
- [Performance Co-Pilot](http://pcp.io) - 轻量级、分布式系统性能分析框架。 ([源代码](https://github.com/performancecopilot/pcp)) `LGPL-2.1/GPL-2.0` `C`
- [PHP Server Monitor](https://www.phpservermonitor.org/) - 开源服务器和网站监控工具。 ([源代码](https://github.com/phpservermon/phpservermon)) `GPL-3.0` `PHP`
- [PhpSysInfo](https://phpsysinfo.github.io/phpsysinfo/) - 可自定义的 PHP 脚本，优雅展示系统信息。 ([源代码](https://github.com/phpsysinfo/phpsysinfo)) `GPL-2.0` `PHP`
- [Prometheus](https://prometheus.io/) - 服务监控系统与时序数据库。 ([源代码](https://github.com/prometheus/prometheus)) `Apache-2.0` `Go`
- [Riemann](https://riemann.io/) - 灵活快速的事件处理器，支持复杂事件/指标分析。 ([源代码](https://github.com/riemann/riemann)) `EPL-1.0` `Java`
- [rtop](https://github.com/rapidloop/rtop) - 基于 SSH 的交互式远程系统监控工具。 `MIT` `Go`
- [ruptime](https://github.com/alexmyczko/ruptime) - 经典系统状态服务器。 `AGPL-3.0` `Shell`
- [Scrutiny](https://github.com/AnalogJ/scrutiny) - 硬盘 S.M.A.R.T 监控 Web UI，支持历史趋势与真实故障阈值。 `MIT` `Go`
- [Sensu](https://sensu.io/) - 针对弹性基础设施和分布式应用的监控工具。 ([源代码](https://github.com/sensu/sensu-go)) `MIT` `Go`
- [Status](https://github.com/dani3l0/Status) - 适合小型家庭服务器的简单轻量系统监控工具，带美观 Web 界面。 ([演示](https://status.enshittification.social/)) `MIT` `Python`
- [Thruk](https://www.thruk.org/) - 多后端监控 Web 界面，支持 Naemon、Nagios、Icinga 和 Shinken。 ([源代码](https://github.com/sni/Thruk)) `GPL-1.0` `Perl`
- [tirreno](https://www.tirreno.com/) - 应用层安全工具，保护应用程序免受威胁、欺诈和滥用。 ([演示](https://play.tirreno.com/), [源代码](https://github.com/tirrenotechnologies/tirreno)) `AGPL-3.0` `PHP/Docker`
- [Uptime Kuma](https://uptime.kuma.pet/) - 现代化自托管监控工具，界面简洁，支持丰富的通知方式。 ([源代码](https://github.com/louislam/uptime-kuma)) `MIT` `Node.js`
- [Wazuh](https://wazuh.com/) - 统一 XDR 与 SIEM，保护终端和云工作负载。 ([源代码](https://github.com/wazuh/wazuh)) `GPL-2.0` `C`
- [Zabbix](https://www.zabbix.com/) - 企业级网络与应用监控软件。 ([源代码](https://git.zabbix.com/projects/ZBX/repos/zabbix/browse)) `GPL-2.0` `C`


### 相册

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

“[相册软件](https://en.wikipedia.org/wiki/Gallery_Software) 是帮助用户发布或分享照片、图片、视频或其他数字媒体的软件。”

_相关: [静态网站生成器](#静态网站生成器), [流媒体 - 视频流媒体](#流媒体---视频流媒体), [内容管理系统（CMS）](#内容管理系统（cms）)_

- [Chevereto](https://chevereto.com/) - 终极图片分享软件。在短短几分钟内创建您自己的个人图像托管网站。 ([源代码](https://github.com/chevereto/chevereto)) `AGPL-3.0` `PHP/Docker`
- [ChronoFrame](https://github.com/HoshinoSuzumi/chronoframe) - 个人图库应用程序，具有在线照片管理功能，支持动态/实时照片和探索地图。 ([演示](https://lens.bh8.ga/)) `MIT` `Node.js/Docker`
- [Damselfly](https://damselfly.info) - 针对大量图像集合的快速服务器端照片管理系统。包括人脸检测、人脸和物体识别、强大的搜索和 EXIF 关键字标记。支持 Linux、MacOS 和 Windows。 ([源代码](https://github.com/webreaper/damselfly)) `GPL-3.0` `Docker/C#/.NET`
- [Ente](https://ente.io/) - 一个端到端加密的照片分享平台（Google Photos 和 Apple Photos 的替代品）。 ([源代码](https://github.com/ente-io/ente)) `AGPL-3.0` `Docker/Node.js/Go`
- [HomeGallery](https://home-gallery.org) - 浏览个人照片和视频，支持标签、移动端友好和 AI 驱动的图片发现。 ([演示](https://demo.home-gallery.org), [源代码](https://github.com/xemle/home-gallery)) `MIT` `Node.js/Docker`
- [Immich Kiosk](https://github.com/damongolding/immich-kiosk) - 轻量级幻灯片放映工具，可在自助终端设备和浏览器上运行，并使用 Immich 作为数据源。 `GPL-3.0` `Docker/Go`
- [Immich](https://immich.app/) - 直接从您的手机备份照片和视频的解决方案（Google Photos 的替代品）。 ([演示](https://github.com/immich-app/immich#demo), [源代码](https://github.com/immich-app/immich)) `AGPL-3.0` `Docker`
- [LibrePhotos](https://github.com/LibrePhotos/librephotos) - 照片管理服务，注重酷炫的图表展示（Google Photos 的替代品）。 ([客户端](https://docs.librephotos.com/docs/user-guide/mobile/)) `MIT` `Python/Docker`
- [Lychee](https://lycheeorg.github.io/) - 基于网格与相册的照片管理系统。 ([源代码](https://github.com/LycheeOrg/Lychee)) `MIT` `PHP/Docker`
- [Mediagoblin](https://mediagoblin.org) - 任何人都可以搭建的媒体发布平台（Flickr、YouTube、SoundCloud 的替代品）。 ([源代码](https://git.savannah.gnu.org/cgit/mediagoblin.git/tree/)) `AGPL-3.0` `Python`
- [Memtly](https://docs.memtly.com/) - 活动照片分享平台与图库，带有幻灯片功能，宾客可通过二维码浏览和分享回忆。 ([演示](https://demo.memtly.com/), [源代码](https://github.com/Memtly/Memtly.Community)) `GPL-3.0` `C#/Docker`
- [Nextcloud Memories](https://memories.gallery/) - 快速、现代化和先进的照片管理套件。作为Nextcloud应用运行。 ([演示](https://demo.memories.gallery/apps/memories/), [源代码](https://github.com/pulsejet/memories)) `AGPL-3.0` `PHP`
- [Photofield](https://github.com/SmilyOrg/photofield) - 实验性的快速照片查看器。 `MIT` `Docker/Go`
- [PhotoPrism](https://photoprism.org) - 由Go和Google TensorFlow支持的个人照片管理。浏览、组织和共享您的个人照片集，使用最新技术自动标记和查找图片。 ([演示](https://demo.photoprism.app/library/browse), [源代码](https://github.com/photoprism/photoprism)) `AGPL-3.0` `Go/Docker`
- [Photoview](https://photoview.github.io/) - 面向个人服务器的简洁且用户友好的照片图库。它专为摄影师打造，旨在提供一种轻松、快速的目录浏览方式，即使面对成千上万张高分辨率照片也能流畅使用。 ([演示](https://photoview.github.io/), [源代码](https://github.com/photoview/photoview)) `GPL-3.0` `Go/Docker`
- [PiGallery 2](https://bpatrik.github.io/pigallery2/) - 以目录为核心的照片图库网站，界面丰富，并针对低资源服务器运行进行了优化。 ([源代码](https://github.com/bpatrik/pigallery2)) `MIT` `Docker/Node.js`
- [Piwigo](https://piwigo.org/) - 用于 web 的相册软件，由积极的用户和开发人员社区构建。 ([源代码](https://github.com/Piwigo/Piwigo)) `GPL-2.0` `PHP`
- [sigal](https://github.com/saimn/sigal) - 又一个简单的静态图库生成器。 `MIT` `Python`
- [SPIS](https://github.com/gbbirkisson/spis) - 一个简单、轻量且快速的媒体服务器，具有良好的移动支持。 `GPL-3.0` `Docker/Rust`
- [This week in past](https://github.com/RouHim/this-week-in-past) - 聚合了来自以往年份的本周拍摄的图片，并在网页上以简单的幻灯片形式呈现。 `MIT` `Docker/Rust`
- [Thumbor](http://thumbor.org/) - 一项智能图像服务，支持按需裁剪、调整大小、应用滤镜和优化图像。 ([源代码](https://github.com/thumbor/thumbor)) `MIT` `Python/Docker`
- [Zenphoto](https://www.zenphoto.org/) - 开源图库和CMS项目。 ([源代码](https://github.com/zenphoto/zenphoto)) `GPL-2.0` `PHP`


### 知识管理工具

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[知识管理](https://en.wikipedia.org/wiki/Knowledge_management)是有关创造、共享、使用和管理知识和信息的方法的集合。

_相关: [笔记和编辑器](#笔记和编辑器), [维基](#维基), [数据库管理](#数据库管理)_

- [AFFiNE Community Edition](https://affine.pro/) - 下一代知识库，汇集规划、整理和创建。隐私优先，可定制且开箱即用（Notion 和 Miro 的替代品）。 ([演示](https://app.affine.pro/), [源代码](https://github.com/toeverything/AFFiNE)) `MIT/AGPL-3.0` `Docker`
- [Atomic Server](https://atomicserver.eu/) - 具有文档（类似于 Notion）、表格、搜索和强大的关联数据 API 的知识图数据库。轻量级、非常快速，且无运行时依赖。 ([演示](https://atomicdata.dev/), [源代码](https://github.com/ontola/atomic-server)) `MIT` `Docker/Rust`
- [Digimindmap](https://ladigitale.dev/digimindmap/#/) - 创建简单的思维导图（法语文档）。 ([演示](https://ladigitale.dev/digimindmap/#/), [源代码](https://codeberg.org/ladigitale/digimindmap)) `AGPL-3.0` `Node.js/PHP`
- [LibreKB](https://librekb.com/) - 基于 Web 的知识库解决方案。简单的 Web 应用，可在几乎所有支持 PHP 和 MySQL 的 Web 服务器或托管提供商上运行。 ([源代码](https://github.com/michaelstaake/LibreKB/)) `GPL-3.0` `PHP`
- [memEx](https://codeberg.org/shibao/memEx) - 受 Zettelkasten 和 org-mode 启发的结构化个人知识库。 `AGPL-3.0` `Docker`
- [SiYuan](https://b3log.org/siyuan/) - 一个隐私优先的个人知识管理软件，使用typescript和golang编写。 ([源代码](https://github.com/siyuan-note/siyuan)) `AGPL-3.0` `Docker/Go`
- [TeamMapper](https://github.com/b310-digital/teammapper) - 托管并创建自己的思维导图。与团队共享思维导图会话，并在思维导图上进行实时协作。 ([演示](https://map.kits.blog)) `MIT` `Docker/Node.js`


### 社区支持农业（CSA）

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

用于社区支持的农业和食品合作社的管理和行政工具。

_相关: [电子商务](#电子商务)_

- [ACP Admin](https://acp-admin.ch/) - CSA 管理。管理成员、订阅、交付、投放地点、成员参与、发票和电子邮件（文档以法语提供）。 ([源代码](https://github.com/csa-admin-org/csa-admin)) `MIT` `Ruby`
- [E-Label](https://filipecarneiro.github.io/ELabel/) - 适用于欧盟销售的葡萄酒瓶上带有二维码的电子标签解决方案。 ([源代码](https://github.com/filipecarneiro/ELabel)) `MIT` `Docker`
- [FoodCoopShop](https://www.foodcoopshop.com/) - 面向食品合作社的用户友好型软件。 ([源代码](https://github.com/foodcoopshop/foodcoopshop)) `AGPL-3.0` `PHP/Docker`
- [Foodsoft](https://foodcoops.net/) - 管理非营利食品合作社（产品目录、订购、会计、工作安排）。 ([源代码](https://github.com/foodcoops/foodsoft)) `AGPL-3.0` `Docker/Ruby`
- [Hive-Pal](https://hivepal.app) - 移动优先的养蜂管理应用，用于跟踪蜂箱、检查、蜂王记录和设备，优化了现场使用的数据输入流程。 ([演示](https://hivepal.app), [源代码](https://github.com/martinhrvn/hive-pal)) `MIT` `Node.js/Docker`
- [juntagrico](https://juntagrico.org/) - 社区花园和蔬菜合作社的管理平台。 ([源代码](https://github.com/juntagrico/juntagrico)) `LGPL-3.0` `Python`
- [Open Food Network](https://www.openfoodnetwork.org/) - 本地食品的在线市场。它支持一系列独立的在线食品商店，将农民和食品中心与个人和本地企业连接起来。 ([源代码](https://github.com/openfoodfoundation/openfoodnetwork)) `AGPL-3.0` `Ruby`
- [OpenOlitor](https://openolitor.org/) - OpenOlitor是一个社区支持农业团体的管理平台。 ([源代码](https://github.com/OpenOlitor/openolitor-server)) `AGPL-3.0` `Scala`
- [teikei](https://github.com/teikei/teikei) - 一款基于众包数据的社区支持农业地图的网络应用。 ([演示](https://ernte-teilen.org/karte/#/)) `AGPL-3.0` `Node.js`


### 笔记和编辑器

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[笔记编辑](https://en.wikipedia.org/wiki/Note-taking)器。

_相关: [维基](#维基)_

- [Blinko](https://blinko.space/) - 一款带有 AI 功能的个人笔记工具。 ([源代码](https://github.com/blinkospace/blinko)) `AGPL-3.0` `Docker`
- [DailyTxT](https://github.com/PhiTux/DailyTxT) - 加密日记Web应用，可保存每天的个人记忆。包括搜索功能和加密文件上传。 ([演示](https://dailytxt.phitux.de)) `MIT` `Docker`
- [Docs](https://docs.numerique.gouv.fr/) - 可扩展的协作式笔记、维基和文档平台。 ([源代码](https://github.com/suitenumerique/docs)) `MIT` `K8S`
- [draw.io](https://draw.io) - 用于制作流程图、流程图、组织图、UML、ER和网络图的图表软件。 ([源代码](https://github.com/jgraph/drawio)) `Apache-2.0` `JavaScript/Docker`
- [flatnotes](https://github.com/dullage/flatnotes) - 一个无数据库的笔记网页应用，使用扁平文件夹中的 Markdown 文件进行存储。 ([演示](https://demo.flatnotes.io)) `MIT` `Docker`
- [HedgeDoc](https://hedgedoc.org/) - 跨所有平台的实时协作Markdown笔记，以前被称为CodiMD和HackMD CE。 ([演示](https://demo.hedgedoc.org/), [源代码](https://github.com/hedgedoc/hedgedoc)) `AGPL-3.0` `Docker/Node.js`
- [Joplin](https://joplinapp.org/) - 笔记应用程序，具有 Markdown 编辑器和加密支持，适用于移动和桌面平台。在客户端运行并通过自托管 Nextcloud 实例或类似的进行同步（Evernote 的替代品）。 ([源代码](https://github.com/laurent22/joplin)) `MIT` `Node.js`
- [Jotty](https://jotty.page) - 轻量但功能强大的个人文件管理、笔记和清单替代方案。 ([源代码](https://github.com/fccview/jotty)) `AGPL-3.0` `Docker`
- [Livebook](https://livebook.dev) - 实时协作的基于Markdown的笔记本应用，支持运行Elixir代码片段、TeX和Mermaid图表。可通过Docker或Elixir轻松部署。 ([源代码](https://github.com/livebook-dev/livebook)) `Apache-2.0` `Elixir/Docker`
- [Many Notes](https://github.com/brufdev/many-notes) - 以简洁为设计理念的 Markdown 笔记 Web 应用。 `MIT` `Docker`
- [Memos](https://usememos.com/) - 基于 SQLite 数据库文件运行的知识库。 ([演示](https://demo.usememos.com/explore), [源代码](https://github.com/usememos/memos)) `MIT` `Docker/Go`
- [Note Mark](https://notemark.docs.enchantedcode.co.uk/) - 极简的基于 Web 的 Markdown 笔记应用。 ([源代码](https://github.com/enchant97/note-mark)) `AGPL-3.0` `Docker`
- [Overleaf](https://www.overleaf.com/) - 基于Web的协作LaTeX编辑器。 ([源代码](https://github.com/overleaf/overleaf)) `AGPL-3.0` `Ruby`
- [Plainpad](https://alextselegidis.com/get/plainpad/) - 面向云端的现代笔记应用，充分利用了渐进式 Web 应用技术的优势特性。 ([演示](https://alextselegidis.com/try/plainpad/), [源代码](https://github.com/alextselegidis/plainpad)) `GPL-3.0` `PHP`
- [plumio](https://plumio.app/) - 支持实时预览、文档加密、多用户和多组织的 Markdown 笔记应用。 ([演示](https://demo.plumio.app/homepage), [源代码](https://github.com/albertasaftei/plumio)) `AGPL-3.0` `Node.js/Docker`
- [SilverBullet](https://silverbullet.md/) - 为黑客思维人群优化的笔记应用程序。 ([演示](https://play.silverbullet.md/), [源代码](https://github.com/silverbulletmd/silverbullet), [客户端](https://silverbullet.md/Libraries)) `MIT` `Docker/Deno`
- [Standard Notes](https://docs.standardnotes.com/self-hosting/getting-started) - 简单而私密的笔记应用。在完成更多工作的同时保护您的隐私。这就是Standard Notes。 ([演示](https://app.standardnotes.com/), [源代码](https://github.com/standardnotes/app)) `GPL-3.0` `Ruby`
- [TriliumNext Notes](https://github.com/TriliumNext/Trilium) - 跨平台分层笔记应用，专注于构建大型个人知识库（Trilium Notes 的分支）。 `AGPL-3.0` `Node.js/Docker/K8S`
- [Turtl](https://turtl.it/) - 完全私密的个人数据库和笔记应用。 ([源代码](https://github.com/turtl)) `GPL-3.0` `CommonLisp`
- [Writing](https://josephernest.github.io/writing/) - 轻量级无干扰文本编辑器，基于浏览器（支持Markdown和LaTeX）。写作时无延迟。 ([源代码](https://github.com/josephernest/writing)) `MIT` `JavaScript`


### 粘贴板

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[Pastebin](https://en.wikipedia.org/wiki/Pastebin)是一种在线内容托管服务，用于分享和存储代码和文本。

- [BinPastes](https://github.com/querwurzel/BinPastes) - 最小化的粘贴板，支持客户端加密、全文搜索和一次性消息。适用于希望简单部署粘贴板的一到少数用户。 `Apache-2.0` `Java`
- [ByteStash](https://github.com/jordan-dalby/ByteStash) - 粘贴板和文件存储服务，具有简单的网络界面。支持语法高亮、可选的用户身份验证和公开共享。 ([演示](https://github.com/jordan-dalby/ByteStash?tab=readme-ov-file#demo)) `GPL-3.0` `Docker`
- [Chiyogami](https://github.com/rhee876527/chiyogami) - 带有 API、客户端加密、用户账户、语法高亮、Markdown 渲染等功能的粘贴板。 ([演示](https://chiyogami.myaddr.dev/)) `BSD-3-Clause` `Docker`
- [dpaste](https://dpaste.org/) - 简单的粘贴板，支持多种文本和代码选项，并提供易记的短网址结果。 ([源代码](https://github.com/DarrenOfficial/dpaste)) `MIT` `Docker/Python`
- [Hemmelig](https://hemmelig.app) - 跨组织或私人共享加密的秘密。 ([源代码](https://github.com/HemmeligOrg/Hemmelig.app)) `MIT` `Docker/Node.js`
- [lesma](https://lesma.eu) - 简洁的粘贴应用，兼容浏览器和命令行使用。 ([演示](https://lesma.eu), [源代码](https://gitlab.com/ogarcia/lesma)) `GPL-3.0` `Rust/Docker`
- [Local Content Share](https://github.com/Tanq16/local-content-share) - 在本地网络中存储和分享文本片段及文件。 `MIT` `Docker/Go`
- [not-th.re](https://not-th.re) - 简单的粘贴分享平台，具有客户端加密功能，配备 Monaco 浏览器代码编辑器。 ([演示](https://not-th.re), [源代码](https://github.com/not-three/main)) `AGPL-3.0` `Node.js/Docker`
- [Opengist](https://opengist.io) - 由 Git 驱动的代码粘贴板。 ([演示](https://demo.opengist.io), [源代码](https://github.com/thomiceli/opengist)) `AGPL-3.0` `Docker/Go/Node.js`
- [paaster](https://paaster.io) - 以简洁为目标构建的端到端加密粘贴板。 ([源代码](https://github.com/WardPearce/paaster)) `AGPL-3.0` `Docker`
- [pacebin](https://git.crueter.xyz/crueter/pacebin) - 超精简的粘贴板和文件上传服务，注重小巧的可执行文件体积、可移植性和易于配置。 ([演示](https://paste.crueter.xyz)) `AGPL-3.0` `C`
- [Password Pusher](https://pwpush.com) - 极其简单的应用，用于通过网络安全传递密码（或文本）。密码在达到一定查看次数和/或经过一定时间后自动过期。 ([源代码](https://github.com/pglombardo/PasswordPusher)) `Apache-2.0` `Docker/K8S/Ruby`
- [Pastefy](https://pastefy.app/) - 美观、简洁且易于部署的粘贴板，支持可选的客户端加密、多标签粘贴、API、语法高亮编辑器等功能。 ([源代码](https://github.com/interaapps/pastefy), [客户端](https://github.com/topics/pastefy-addon)) `MIT` `Docker/K8S/Java`
- [PrivateBin](https://privatebin.info/) - 极简的 Pastebin/讨论板，服务器对托管数据零知情。 ([演示](https://privatebin.net/), [源代码](https://github.com/PrivateBin/PrivateBin)) `Zlib` `PHP`
- [rustypaste](https://github.com/orhun/rustypaste) - 极简的文件上传/粘贴板服务。 `MIT` `Rust`
- [SnyPy](https://snypy.com) - 开源的本地代码片段管理器。 ([演示](https://app.snypy.com), [源代码](https://github.com/snypy)) `MIT` `Docker`
- [Sup3rS3cretMes5age](https://github.com/algolia/sup3rS3cretMes5age) - 使用 HashiCorp Vault 作为秘密存储的非常简单（部署和使用）的秘密消息服务。 `MIT` `Go`
- [Wastebin](https://github.com/matze/wastebin) - 轻量、极简和快速的过去式服务，带有SQLite后端。 ([演示](https://bin.bloerg.net)) `MIT` `Rust/Docker`
- [Yopass](https://github.com/jhaals/yopass) - 安全共享机密、密码和文件。 ([演示](https://yopass.se/)) `Apache-2.0` `Go/Docker`


### 绘图

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

用于创建网络、流程等图表的工具。

- [Diagrams.net](https://app.diagrams.net/) - 又名 [Draw.io](https://app.diagrams.net/)。易用的图表 UI，内置丰富模板。 ([源代码](https://github.com/jgraph/drawio)) `Apache-2.0` `JavaScript/Docker`
- [Kroki](https://kroki.io) - 基于文本描述生成图表的 API。 ([源代码](https://github.com/yuzutech/kroki)) `MIT` `Java`
- [Mermaid](https://mermaid-js.github.io/mermaid-live-editor/) - 具有独特简洁语法的 JavaScript 绘图模块，可集成到 Grafana 等多种工具。 ([源代码](https://github.com/mermaid-js/mermaid-live-editor)) `MIT` `Node.js/Docker`


### 维基

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[维基](https://en.wikipedia.org/wiki/Wiki) 是一种由其观众直接使用 Web 浏览器协作编辑和管理的出版物。

_相关: [笔记和编辑器](#笔记和编辑器), [静态网站生成器](#静态网站生成器), [知识管理工具](#知识管理工具)_

_另见: [Wikimatrix](https://www.wikimatrix.org/), [wiki软件清单 - Wikipedia](https://en.wikipedia.org/wiki/List_of_wiki_software), [wiki软件比较 - Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_wiki_software)_

- [AmuseWiki](https://amusewiki.org/) - Amusewiki 基于 Emacs Muse 标记语言，基本上与原始实现保持兼容。它可以作为只读站点、作为经过审核的维基，或者作为完全开放的维基，甚至作为私有站点使用。 ([演示](https://sandbox.amusewiki.org), [源代码](https://github.com/melmothx/amusewiki)) `GPL-1.0` `Perl/Docker`
- [BookStack](https://www.bookstackapp.com/) - 组织和存储信息。以类似书籍的方式存储文档。 ([演示](https://www.bookstackapp.com/#demo), [源代码](https://codeberg.org/bookstack/bookstack)) `MIT` `PHP/Docker`
- [django-wiki](https://github.com/django-wiki/django-wiki) - 拥有复杂功能的维基系统，可简单集成且具有出色的界面。以风格存储您的知识：使用Django模型。 ([演示](https://demo.django-wiki.org/)) `GPL-3.0` `Python`
- [docmost](https://docmost.com/) - 协作型 Wiki 和文档软件（Confluence、Notion 的替代品）。 ([源代码](https://github.com/docmost/docmost)) `AGPL-3.0` `Docker/Node.js`
- [Documize](https://documize.com) - 现代文档和Wiki软件，内置工作流，单个二进制可执行文件，只需带上 MySQL/Percona。 ([源代码](https://github.com/documize/community)) `AGPL-3.0` `Go`
- [DokuWiki](https://www.dokuwiki.org/DokuWiki) - 易于使用、轻量级、符合标准的维基引擎，具有简单的语法，允许在维基之外阅读数据。所有数据都存储在纯文本文件中，因此不需要数据库。 ([源代码](https://github.com/dokuwiki/dokuwiki)) `GPL-2.0` `PHP`
- [Feather Wiki](https://feather.wiki) - 一个极速且无限扩展的工具，用于创建个人非线性笔记本、数据库和维基，完全自包含，运行在您的浏览器中，仅大小为58千字节。 ([演示](https://feather.wiki/?page=gallery#wikis), [源代码](https://codeberg.org/Alamantus/FeatherWiki), [客户端](https://feather.wiki/?page=gallery#extensions)) `AGPL-3.0` `JavaScript`
- [Gitit](https://github.com/jgm/gitit) - 存储页面和上传文件于Git存储库的维基程序，可以使用VCS命令行工具或维基的Web界面进行修改。 `GPL-2.0` `Haskell`
- [Gollum](https://github.com/gollum/gollum) - 简单的、由Git驱动的维基，具有友好的API和本地前端。 `MIT` `Ruby`
- [LeafWiki](https://github.com/perber/leafwiki) - 以文件夹为中心的快速 Wiki，支持快速编辑、树形导航和基于磁盘的 Markdown 存储。 ([演示](https://demo.leafwiki.com)) `MIT` `Docker/Go`
- [Mediawiki](https://www.mediawiki.org/wiki/MediaWiki) - 为维基百科及所有维基媒体项目提供支持的维基软件，每月服务数亿用户。 ([演示](https://en.wikipedia.org/wiki/Main_Page), [源代码](https://phabricator.wikimedia.org/source/mediawiki/)) `GPL-2.0` `PHP`
- [Mycorrhiza Wiki](https://mycorrhiza.wiki/) - 使用 Go 编写的基于文件系统和 git 的维基引擎，主要使用 Mycomarkup 作为其主要标记语言。 ([源代码](https://github.com/bouncepaw/mycorrhiza/)) `AGPL-3.0` `Go`
- [Oddmuse](https://oddmuse.org/) - 用 Perl 编写的简单维基引擎，无需数据库。 ([源代码](https://github.com/kensanata/oddmuse)) `GPL-3.0` `Perl`
- [Otter Wiki](https://otterwiki.com/) - 使用Markdown的简单易用的Wiki软件。 ([源代码](https://github.com/redimp/otterwiki)) `MIT` `Docker`
- [PmWiki](https://www.pmwiki.org) - 基于Wiki的系统，用于协同创建和维护网站。 `GPL-3.0` `PHP`
- [Raneto](https://raneto.com/) - 使用静态 Markdown 文件的知识库平台。 ([源代码](https://github.com/ryanlelek/Raneto)) `MIT` `Node.js`
- [TiddlyWiki](https://tiddlywiki.com/) - 可重复使用的非线性个人 Web 笔记本。 ([源代码](https://github.com/TiddlyWiki/TiddlyWiki5)) `BSD-3-Clause` `Node.js`
- [Tiki](https://tiki.org/HomePage) - 具有最多内置功能的 Wiki CMS Groupware。 ([演示](https://tiki.org/Try-Tiki), [源代码](https://gitlab.com/tikiwiki/tiki)) `LGPL-2.1` `PHP`
- [W](https://w.club1.fr) - 轻量级、多用户、平面文件数据库的 Wiki 引擎。快速创建页面并使用 Markdown/HTML/CSS/JS 在浏览器中编辑。与其他 Wiki 的主要区别在于，鼓励您单独自定义每个页面的样式。 ([源代码](https://github.com/vincent-peugnet/wcms)) `AGPL-3.0` `PHP`
- [WackoWiki](https://wackowiki.org/) - WackoWiki是一款轻量且易于安装的多语言Wiki引擎。 ([源代码](https://github.com/WackoWiki/wackowiki)) `BSD-3-Clause` `PHP`
- [Wiki-Go](https://leomoon.com/downloads/web-apps/wiki-go/) - 现代、功能丰富、无需数据库的扁平文件 Wiki 平台。 ([演示](https://wikigo.leomoon.com), [源代码](https://github.com/leomoon-studios/wiki-go)) `GPL-3.0` `Go/Docker`
- [Wiki.js](https://js.wiki/) - 使用Git和Markdown的现代、轻量且功能强大的Wiki应用程序。 ([演示](https://docs.requarks.io), [源代码](https://github.com/Requarks/wiki)) `AGPL-3.0` `Node.js/Docker/K8S`
- [WikiDocs](https://www.wikidocs.app/) - 一个无数据库的 Markdown 纯文本 wiki 引擎。 ([源代码](https://github.com/Zavy86/WikiDocs)) `MIT` `PHP/Docker`
- [WiKiss](https://wikiss.tuxfamily.org/) - Wiki，简单易用且易于安装。 `GPL-2.0` `PHP`
- [XWiki](https://www.xwiki.org) - 第二代维基，允许用户通过强大的基于扩展的架构扩展其功能。 ([演示](https://www.xwikiplayground.org/xwiki/bin/view/Main/), [源代码](https://github.com/xwiki/xwiki-platform)) `LGPL-2.1` `Java/Docker/deb`
- [Zim](https://zim-wiki.org/) - 用于维护wiki页面集合的图形文本编辑器。每个页面可以包含到其他页面的链接、简单格式和图片。 ([源代码](https://github.com/zim-desktop-wiki/zim-desktop-wiki)) `GPL-2.0` `Python/deb`


### 编辑器

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

开源代码编辑器。

- [Atom Community](https://github.com/atom-community/atom) - [atom](https://github.com/atom/atom) 的分支，来自 Github 的可定制文本编辑器。 `MIT` `JavaScript`
- [Brackets](https://brackets.io/) - 面向网页设计师和前端开发者的代码编辑器。 ([源代码](https://github.com/brackets-cont/brackets)) `MIT` `JavaScript`
- [Eclipse](https://www.eclipse.org/) - 用 Java 编写、可扩展插件系统的 IDE。 ([源代码](https://git.eclipse.org/c/)) `EPL-1.0` `Java`
- [Geany](https://www.geany.org/) - 基于 GTK2 的文本编辑器。 ([源代码](https://github.com/geany/geany)) `GPL-2.0` `C/C++`
- [GNU Emacs](https://www.gnu.org/software/emacs/) - 可扩展、可定制的文本编辑器及更多功能。 ([源代码](https://github.com/emacs-mirror/emacs)) `GPL-3.0` `C`
- [Haroopad](http://pad.haroopress.com/) - 支持实时预览的 Markdown 编辑器。 ([源代码](https://github.com/rhiokim/haroopad)) `GPL-3.0` `JavaScript`
- [KDevelop](https://www.kdevelop.org/) - KDE 团队开发的 IDE。 ([源代码](https://invent.kde.org/kdevelop/kdevelop)) `GFDL-1.2` `C++`
- [Micro](https://micro-editor.github.io/) - 现代直观的终端文本编辑器。 ([源代码](https://github.com/zyedidia/micro)) `MIT` `Go`
- [Nano](https://nano-editor.org) - 易用、可定制的文本编辑器。 ([源代码](https://git.savannah.gnu.org/cgit/nano.git/tree/)) `GPL-3.0` `C`
- [Notepad++](https://notepad-plus-plus.org/) - GPLv2 多语言编辑器，支持 Windows 语法高亮。 ([源代码](https://github.com/notepad-plus-plus/notepad-plus-plus)) `GPL-2.0` `C++`
- [TextMate](https://macromates.com/) - OS X 图形化文本编辑器。 ([源代码](https://github.com/textmate/textmate/)) `GPL-3.0` `C++`
- [Vim](https://www.vim.org) - 高度可配置的文本编辑器，提升编辑效率。 ([源代码](https://github.com/vim/vim)) `Vim` `C`
- [VSCodium](https://vscodium.com/) - 基于 [微软 VS Code](https://code.visualstudio.com/) 的开源跨平台可扩展代码编辑器，去除了非自由部分。 ([源代码](https://github.com/VSCodium/vscodium)) `MIT` `TypeScript`


### 网络工具

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

网络工具是帮助管理、监控和排查计算机网络故障的工具和软件。

_另见: [awesome-sysadmin/Monitoring](https://github.com/awesome-foss/awesome-sysadmin#monitoring)_

- [beelzebub](https://beelzebub-honeypot.com/) `⚠` - 一个蜜罐框架，旨在提供高度安全的环境，用于检测和分析网络攻击。 ([源代码](https://github.com/beelzebub-labs/beelzebub)) `MIT` `Docker/K8S/Go`
- [Canary Tokens](https://canarytokens.org) - 生成轻量级的嵌入式蜜罐触发器（称为金丝雀令牌）以检测未授权的访问。 ([源代码](https://github.com/thinkst/opencanary)) `BSD-3-Clause` `Docker/Python`
- [MyIP](https://ipcheck.ing) `⚠` - 全功能 IP 工具箱。轻松检查您的 IP 地址、IP 地理位置、DNS 泄漏检查、WebRTC 连接检查、速度测试、ping 测试、MTR 测试、检查网站可用性等。 ([演示](https://ipcheck.ing), [源代码](https://github.com/jason5ng32/MyIP)) `MIT` `Node.js/Docker`
- [MySpeed](https://myspeed.dev/) - 速度测试分析软件，可显示您长达30天的互联网速度。 ([源代码](https://github.com/gnmyt/myspeed)) `MIT` `Docker/Node.js`
- [NetAlertX](https://netalertx.com/) - 网络入侵和存在检测器。扫描连接到您网络的设备，并在发现新的未知设备时发出警报。 ([源代码](https://github.com/netalertx/NetAlertX)) `GPL-3.0` `Docker`
- [Speed Test by OpenSpeedTest™](https://openspeedtest.com/) - 免费且开源的HTML5网络性能估算工具。 ([源代码](https://github.com/openspeedtest/Speed-Test)) `MIT` `Docker`
- [Speedtest Tracker](https://docs.speedtest-tracker.dev/) - 监控你的互联网连接的性能和在线时间。 ([源代码](https://github.com/alexjustesen/speedtest-tracker)) `MIT` `Docker/K8S`
- [Upsnap](https://github.com/seriousm4x/UpSnap) - 一款简单的远程唤醒（Wake on LAN，WOL）仪表板应用。唤醒网络中的设备并查看当前状态。 `MIT` `Go/Docker`
- [Wakupator](https://github.com/Gibus21250/Wakupator) - 基于网络流量的局域网唤醒机器管理器。 `MIT` `C`
- [WatchYourLAN](https://github.com/aceberg/WatchYourLAN) - 轻量级网络 IP 扫描器，支持通知、历史记录和导出到 Grafana。 `MIT` `Docker/Go/deb`


### 网络配置管理

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

网络配置管理工具。

- [GNS3](https://www.gns3.com/) - 图形化网络模拟器，支持多种虚拟设备。 ([源代码](https://github.com/GNS3/gns3-gui/)) `GPL-3.0` `Python`
- [OpenWISP](https://openwisp.org/) - 基于 OpenWRT 路由器和接入点的开源网络管理系统。 ([演示](https://openwisp.org/demo.html), [源代码](https://github.com/openwisp)) `GPL-3.0` `Python`
- [Oxidized](https://github.com/ytti/oxidized) - 网络设备配置备份工具。 `Apache-2.0` `Ruby`
- [phpIPAM](https://phpipam.net/) - 开源 IP 地址管理，支持 PowerDNS 集成。 ([源代码](https://github.com/phpipam/phpipam)) `GPL-3.0` `PHP`
- [RANCID](https://www.shrubbery.net/rancid/) - 监控网络设备配置并维护变更历史。 ([源代码](https://github.com/haussli/rancid)) `BSD-3-Clause` `Perl/Shell`
- [rConfig](https://www.rconfig.com/) - 网络设备配置管理工具。 ([源代码](https://github.com/rconfig/rconfig)) `GPL-3.0` `PHP`


### 联邦身份和认证

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[联邦身份](https://en.wikipedia.org/wiki/Federated_identity)和[认证](https://en.wikipedia.org/wiki/Electronic_authentication)软件。

**请访问 [awesome-sysadmin/身份管理](https://github.com/awesome-foss/awesome-sysadmin#identity-management)**



### 自动化

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[自动化](https://en.wikipedia.org/wiki/Automation)软件，旨在减少人类在流程中的干预。

_相关: [物联网（IoT）](#物联网（iot）), [软件开发 - 持续集成和部署](#软件开发---持续集成和部署), [媒体管理](#媒体管理)_

- [Activepieces](https://www.activepieces.com) - 无代码业务自动化工具，类似于 Zapier 或 Tray。例如，您可以为每个新的 Trello 卡片发送 Slack 通知。 ([源代码](https://github.com/activepieces/activepieces)) `MIT` `Docker`
- [Apache Airflow](https://airflow.apache.org/) - 用于以编程方式编写、调度和监控工作流的平台。 ([源代码](https://github.com/apache/airflow/)) `Apache-2.0` `Python/Docker`
- [Apache Ant](https://ant.apache.org/) - 自动化构建工具，类似于 make，是一个库和命令行工具，其任务是驱动在构建文件中描述的目标和扩展点，这些目标和扩展点彼此依赖。 ([源代码](https://github.com/apache/ant)) `Apache-2.0` `Java`
- [Apache Maven](https://maven.apache.org/) - 主要用于 Java 的构建自动化工具。一个软件项目管理和理解工具。基于项目对象模型（POM）的概念，Maven 可以从一处信息管理项目的构建、报告和文档。 ([源代码](https://github.com/apache/maven)) `Apache-2.0` `Java`
- [Automatisch](https://automatisch.io) - 业务自动化工具，可连接不同的服务，如Twitter、Slack等，以自动化业务流程（类似于Zapier的替代品）。 ([源代码](https://github.com/automatisch/automatisch)) `AGPL-3.0` `Docker`
- [Bazel](https://www.bazel.io/) - 一个快速、可扩展、多语言且可扩展的构建系统。由 Google 使用。 ([源代码](https://github.com/bazelbuild/bazel/)) `Apache-2.0` `Java`
- [BookBounty](https://github.com/TheWicklowWolf/BookBounty) `⚠` - 从 Library Genesis 检索缺失的 Readarr 书籍。 `MPL-2.0` `Docker`
- [changedetection.io](https://changedetection.io/) - 随时了解网站内容的变化。 ([源代码](https://github.com/dgtlmoon/changedetection.io)) `Apache-2.0` `Python/Docker`
- [ChiefOnboarding](https://chiefonboarding.com) - 员工入职平台，允许您分配用户帐户并创建包含待办事项、资源、文本/电子邮件/Slack消息等的序列！可作为Web门户和Slack机器人使用。 ([源代码](https://github.com/chiefonboarding/ChiefOnboarding)) `AGPL-3.0` `Docker`
- [Cronicle](https://cronicle.net/) - 简单的分布式任务调度程序和运行程序，具有基于网络的用户界面。 ([源代码](https://github.com/jhuckaby/Cronicle)) `MIT` `Node.js`
- [Cronmaster](https://github.com/fccview/cronmaster) - Cronjob 管理用户界面，具有易读的语法、实时日志和您的 cronjob 的日志历史记录。 `AGPL-3.0` `Docker`
- [Dagu](https://docs.dagu.cloud/) - 功能强大的 Cron 替代品，具有 Web UI。它允许您以声明性的 YAML 格式将命令之间的依赖关系定义为有向无环图（DAG）。 ([源代码](https://github.com/dagucloud/dagu)) `GPL-3.0` `Go/Docker`
- [Discount Bandit](https://discount-bandit.cybrarist.com/) `⚠` - 跟踪多家商店（如 Amazon、Ebay、Walmart 等）的产品价格和库存状态。 ([源代码](https://github.com/Cybrarist/Discount-Bandit)) `GPL-3.0` `PHP/Docker`
- [Dittofeed](https://www.dittofeed.com) - 全渠道客户互动和消息自动化平台（Braze、Customer.io、Iterable 的替代品）。 ([演示](https://demo.dittofeed.com/dashboard/journeys), [源代码](https://github.com/dittofeed/dittofeed)) `MIT` `Docker`
- [feedmixer](https://github.com/cristoper/feedmixer) - 一个微型 Web 服务，接收一组 feed URL，并返回一个由每个 feed 最新 n 条条目组成的新 feed（支持返回 Atom、RSS 或 JSON）。 `WTFPL` `Python`
- [flowctl](https://flowctl.net) - 支持审批、远程执行和调度的自助式工作流执行平台。 ([演示](https://demo.flowctl.net), [源代码](https://github.com/cvhariharan/flowctl)) `Apache-2.0` `Go/Docker`
- [Fredy](https://fredy.orange-coding.net/) `⚠` - 在德国的平台如 ImmoScout24、Immowelt 等上搜索新的公寓、房屋和套房，并通过 Slack、Telegram 等即时将结果发送给您。 ([演示](https://fredy-demo.orange-coding.net), [源代码](https://github.com/orangecoding/fredy)) `Apache-2.0` `Node.js/Docker`
- [Github Ntfy](https://github.com/BreizhHardware/ntfy_alerts) `⚠` - 当 Docker Hub 或 Github 上有新版本发布时，向 NTFY、Gotify、Discord 或 Slack 发送推送通知。 ([客户端](https://github.com/binwiederhier/ntfy)) `GPL-3.0` `Rust/Docker`
- [GNU Make](https://www.gnu.org/software/make/) - 最流行的自动化构建工具之一，适用于多种用途。make 控制从源文件生成可执行文件和其他非源文件。 ([源代码](https://git.savannah.gnu.org/cgit/make.git)) `GPL-3.0` `C`
- [gocron](https://github.com/flohoss/gocron) - 任务调度器，允许用户通过简单的 YAML 配置文件指定定期任务。 `MIT` `Docker`
- [Gradle](https://gradle.org/) - 另一种构建自动化系统。 ([源代码](https://github.com/gradle/gradle)) `Apache-2.0` `Groovy/Java`
- [HandBrake Web](https://github.com/TheNickOfTime/handbrake-web) - 通过 Web 界面在无头设备上使用一个或多个 HandBrake 视频转码器实例。 `AGPL-3.0` `Docker`
- [Huginn](https://github.com/huginn/huginn) - 构建可以为你监控和行动的代理程序。 `MIT` `Ruby`
- [Kestra](https://kestra.io) - 基于事件驱动的、与语言无关的平台，用于创建、调度和监视工作流。通过代码协调数据管道和任务，如ETL和ELT。 ([源代码](https://github.com/kestra-io/kestra)) `Apache-2.0` `Docker`
- [Kibitzr](https://kibitzr.github.io) - 轻量级个人网络助手，具有强大的集成功能。 ([源代码](https://github.com/kibitzr/kibitzr)) `MIT` `Python`
- [LazyLibrarian](https://gitlab.com/LazyLibrarian/LazyLibrarian) `⚠` - 关注作者并获取所有数字阅读需求的元数据。综合使用 Goodreads、Librarything 以及可选的 GoogleBooks 作为作者和书籍信息来源。 `GPL-3.0` `Python`
- [Leon](https://getleon.ai) - 可部署在自己服务器上的个人助手。 ([源代码](https://github.com/leon-ai/leon)) `MIT` `Node.js`
- [Matchering](https://github.com/sergree/matchering) - 自动化音乐母带处理工具（LANDR、eMastered 和 MajorDecibel 的替代品）。 `GPL-3.0` `Docker`
- [Mylar3](https://mylarcomics.com/) - 自动漫画书(cbr/cbz)下载程序，用于NZB和种子下载。 ([源代码](https://github.com/mylar3/mylar3)) `GPL-3.0` `Python/Docker`
- [OliveTin](https://www.olivetin.app/) - 用于运行 Linux Shell 命令的 Web 界面。 ([源代码](https://github.com/OliveTin/OliveTin)) `AGPL-3.0` `Go`
- [OpenBolt](https://voxpupuli.org/openvox/) - 编排工具，用于运行编排工作流或一次性任务/脚本，以自动化节点的配置和管理。是最后一个开源版本的 [Puppet Bolt](https://help.puppet.com/bolt/current/topics/bolt.htm) 的社区分支。 ([源代码](https://github.com/OpenVoxProject/openbolt)) `Apache-2.0` `Ruby`
- [pyLoad](https://pyload.net/) - 一款轻量、可定制且可远程管理的下载器，用于支持1-click-hosting网站，如rapidshare.com或uploaded.to。 ([源代码](https://github.com/pyload/pyload)) `AGPL-3.0` `Python`
- [Rake](https://ruby.github.io/rake/) - 类似于 Make 的构建自动化工具，用 Ruby 编写并可扩展。 ([源代码](https://github.com/ruby/rake)) `MIT` `Ruby`
- [StackStorm](https://stackstorm.com) - StackStorm（又名_Ops的IFTTT_）是面向事件的自动化解决方案，用于自动修复、安全响应、故障排除、部署等。包括规则引擎、工作流、160个集成包，具有6000多个操作和ChatOps。 ([源代码](https://github.com/StackStorm/st2)) `Apache-2.0` `Python`
- [µTask](https://github.com/ovh/utask) - 一个建模和执行以yaml声明的业务流程的自动化引擎。 `BSD-3-Clause` `Go/Docker`


### 自托管解决方案

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

用于轻松安装、管理和配置自托管服务和应用程序的软件。

- [CasaOS](https://casaos.zimaspace.com/) - 简单易用且优雅的家庭云系统。 ([源代码](https://github.com/IceWhaleTech/CasaOS)) `Apache-2.0` `Go/Docker`
- [DietPi](https://dietpi.com/) - Minimal Debian 操作系统，专为单板计算机优化，可轻松安装和管理多个用于在家自行托管的服务。 ([源代码](https://github.com/MichaIng/DietPi)) `GPL-2.0` `Shell`
- [DockSTARTer](https://dockstarter.com/) - DockSTARTer 帮助您开始在 Docker 中运行的家庭服务器应用。 ([源代码](https://github.com/GhostWriters/DockSTARTer)) `MIT` `Shell`
- [Dropserver](https://dropserver.org) - 个人 Web 服务的应用平台。 ([源代码](https://github.com/teleclimber/Dropserver/)) `Apache-2.0` `Go/Deno`
- [FreedomBox](https://freedombox.org/) - 社区项目，旨在开发、设计和推广运行免费软件的个人服务器，用于私人、个人通信。 ([源代码](https://salsa.debian.org/freedombox-team/freedombox)) `AGPL-3.0` `Python/deb`
- [HomelabOS](https://homelabos.com) - 离线、注重隐私的数据中心。只需几条命令即可部署 100 多个服务。 ([源代码](https://gitlab.com/NickBusey/HomelabOS)) `MIT` `Docker`
- [HomeServerHQ](https://www.homeserverhq.com/) - 一体化家庭服务器基础设施与安装器。即使在 CGNAT 环境下，也能在一小时内完成邮件服务器、VPN 和公共网站的全自动配置。 ([源代码](https://github.com/homeserverhq/hshq)) `GPL-3.0` `Shell`
- [LibreServer](https://libreserver.org/) - 基于Debian的家庭服务器配置。 ([源代码](https://github.com/bashrc2/libreserver)) `AGPL-3.0` `Shell`
- [NextCloudPi](https://github.com/nextcloud/nextcloudpi) - 预安装和预配置的Nextcloud，带有文本和Web管理界面以及自托管私人数据所需的所有工具。提供Raspberry Pi、Odroid、Rock64、Docker的安装映像，以及用于Armbian/Debian的curl安装程序。 `GPL-2.0` `Shell/PHP`
- [Nirvati](https://nirvati.org) - 通过便捷的 Web 界面轻松一键部署热门的自托管应用。 ([源代码](https://gitlab.com/nirvati-ug/nirvati/backend)) `AGPL-3.0` `Rust/K8S`
- [OpenMediaVault](https://www.openmediavault.org/) - 基于 Debian Linux 的网络附加存储 (NAS) 解决方案。包含 SSH、(S)FTP、SMB/CIFS、DAAP 媒体服务器、RSync、BitTorrent 客户端等众多服务。 ([源代码](https://github.com/openmediavault/openmediavault)) `GPL-3.0` `PHP`
- [Sandstorm](https://sandstorm.io/) - 用于轻松、安全地运行自托管应用程序的个人服务器。 ([演示](https://demo.sandstorm.io/), [源代码](https://github.com/sandstorm-io/sandstorm)) `Apache-2.0` `C++/Shell`
- [Self Host Blocks](https://github.com/ibizaman/selfhostblocks) `⚠` - 基于NixOS模块并专注于最佳实践的模块化服务器管理。 `AGPL-3.0` `Nix`
- [StartOS](https://start9.com) - 基于浏览器的图形操作系统（OS），使运行个人服务器变得像运行个人电脑一样简单。 ([源代码](https://github.com/Start9Labs/start-os)) `MIT` `Rust`
- [Syncloud](https://syncloud.org/) - 您自己的在线文件存储、社交网络或电子邮件服务器。 ([源代码](https://github.com/syncloud/platform)) `GPL-3.0` `Go/Shell`
- [Tipi](https://runtipi.io/) - 家庭服务器管理器。一条命令完成部署，一键安装你喜爱的自托管应用。 ([源代码](https://github.com/runtipi/runtipi)) `GPL-3.0` `Shell`
- [UBOS](https://ubos.net/) - 运行在独立盒子上的Linux发行版（个人服务器和物联网设备）。单一命令安装和管理应用程序 - Jenkins、Mediawiki、Owncloud、WordPress等，以及其他功能。 `GPL-3.0` `Perl`
- [Websoft9](https://www.websoft9.com) `⚠` - 基于 GitOps 的多应用托管，适用于云服务器和家庭服务器，一键部署 200 多个开源应用。 ([演示](https://www.websoft9.com/demo), [源代码](https://github.com/websoft9/websoft9), [客户端](https://www.websoft9.com/apps)) `LGPL-3.0` `Shell/Python`
- [WikiSuite](https://wikisuite.org) - 最全面和集成的自由/开源企业软件套件。 ([源代码](https://wikisuite.org/Source-Code)) `GPL-3.0/LGPL-2.1/Apache-2.0/MPL-2.0/MPL-1.1/MIT/AGPL-3.0` `Shell/Perl/deb`
- [xsrv](https://xsrv.readthedocs.io/) - 在您自己的服务器上安装和管理自托管的服务/应用程序。 ([源代码](https://github.com/nodiscc/xsrv)) `GPL-3.0` `Ansible/Shell`
- [YunoHost](https://yunohost.org/) - 服务器操作系统，旨在使自托管对每个人都更容易访问。 ([演示](https://yunohost.org/#/try), [源代码](https://github.com/YunoHost)) `AGPL-3.0` `Python/Shell`


### 虚拟专用网络（VPN）

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[虚拟专用网络（VPN）](https://en.wikipedia.org/wiki/Virtual_private_network)将私人网络扩展到公共网络，并使用户能够在共享或公共网络上发送和接收数据，就像他们的计算设备直接连接到私人网络一样。

- [DefGuard](https://defguard.net/) - 真正的企业级 WireGuard，支持 MFA/2FA 和 SSO。 ([源代码](https://github.com/DefGuard)) `Apache-2.0` `Rust`
- [Dockovpn](https://dockovpn.io) - 即开即用的无状态 Docker 化 OpenVPN 服务器，启动时间小于 2 秒。 ([源代码](https://github.com/dockovpn/dockovpn)) `GPL-2.0` `Docker`
- [Firezone](https://www.firezone.dev/) - 安全的远程访问网关，支持 WireGuard 协议。提供 Web 图形界面、一键安装脚本、多因素认证（MFA）和单点登录（SSO）。 ([源代码](https://github.com/firezone/firezone)) `Apache-2.0` `Elixir/Docker`
- [Gluetun VPN client](https://github.com/qdm12/gluetun) - 多 VPN 提供商的 Docker VPN 客户端，支持 OpenVPN/WireGuard、DNS over TLS，内置代理。 `MIT` `Docker`
- [Headscale](https://github.com/juanfont/headscale) - [Tailscale](https://tailscale.com) 的自托管分支，跨平台客户端，易用，内置（实验性）监控工具。 `BSD-3-Clause` `Go`
- [Nebula](https://github.com/slackhq/nebula) - 注重性能、简洁和安全的可扩展 P2P VPN。 `MIT` `Go`
- [ocserv](https://www.infradead.org/ocserv/) - 兼容 Cisco AnyConnect 的 VPN 服务器。 ([源代码](https://gitlab.com/ocserv/ocserv)) `GPL-2.0` `C`
- [OpenVPN](https://community.openvpn.net) - 使用 SSL/TLS 进行密钥交换的自定义安全协议。 ([源代码](https://github.com/OpenVPN/openvpn)) `GPL-2.0` `C`
- [SoftEther](https://www.softether.org/) - 多协议软件 VPN，功能强大。 ([源代码](https://github.com/SoftEtherVPN/SoftEtherVPN/)) `Apache-2.0` `C`
- [sshuttle](https://github.com/sshuttle/sshuttle) - 透明代理服务器,可作为穷人版的 VPN 使用。通过 ssh 进行转发。无需管理员权限。支持 Linux 和 MacOS。支持 DNS 隧道。 `LGPL-2.1` `Python`
- [strongSwan](https://www.strongswan.org/) - Linux 下完整的 IPsec 实现。 ([源代码](https://github.com/strongswan/strongswan)) `GPL-2.0` `C`
- [WireGuard](https://www.wireguard.com/) - 基于椭圆曲线和公钥加密的高速 VPN。 ([源代码](https://www.wireguard.com/repositories/)) `GPL-2.0` `C`


### 虚拟化

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

虚拟化软件。

- [Ganeti](https://www.ganeti.org/) - 基于 KVM 和 Xen 的集群虚拟服务器管理工具。 ([源代码](https://github.com/ganeti/ganeti)) `BSD-2-Clause` `Python/Haskell`
- [KVM](https://www.linux-kvm.org) - Linux 内核虚拟化基础设施。 ([源代码](https://git.kernel.org/pub/scm/virt/kvm/kvm.git/)) `GPL-2.0/LGPL-2.0` `C`
- [OpenNebula](https://opennebula.org/) - 构建和管理企业云，支持虚拟化服务、容器化应用和无服务器计算。 ([源代码](https://github.com/OpenNebula/one)) `Apache-2.0` `C++`
- [oVirt](https://www.ovirt.org/) - 管理虚拟机、存储和虚拟网络。 ([源代码](https://github.com/oVirt)) `Apache-2.0` `Java`
- [Packer](https://www.packer.io/) - 从单一源配置为多平台创建一致的机器镜像的工具。 ([源代码](https://github.com/hashicorp/packer)) `MPL-2.0` `Go`
- [Proxmox VE](https://www.proxmox.com/proxmox-ve) - 虚拟化管理解决方案。 ([源代码](https://git.proxmox.com/)) `GPL-2.0` `Perl/Shell`
- [QEMU](https://www.qemu.org/) - 通用机器模拟器和虚拟化器。 ([源代码](https://gitlab.com/qemu-project/qemu)) `LGPL-2.1` `C`
- [VirtualBox](https://www.virtualbox.org/) - Oracle 公司出品的虚拟化产品。 ([源代码](https://www.virtualbox.org/browser/vbox)) `GPL-3.0/CDDL-1.0` `C++`
- [XCP-ng](https://www.xcp-ng.org/) - 基于 Xen Source 和 Citrix® Hypervisor（前 XenServer）的虚拟化平台。 ([源代码](https://github.com/xcp-ng)) `GPL-2.0` `C`
- [Xen](https://www.xenproject.org/) - 适用于 32/64 位 Intel / AMD（IA 64）和 PowerPC 970 架构的虚拟机监控器。 ([源代码](https://xenbits.xenproject.org/gitweb/?p=xen.git;a=tree;hb=HEAD)) `GPL-2.0` `C`


### 视频监控

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

视频监控，也称为[闭路电视（CCTV）](https://en.wikipedia.org/wiki/Closed-circuit_television)，是在需要额外安全性或持续监视的区域使用视频摄像机进行监控的技术。

_相关: [流媒体 - 视频流媒体](#流媒体---视频流媒体)_

- [Bluecherry](https://www.bluecherrydvr.com/) - 支持IP和模拟摄像机的闭路电视（CCTV）软件应用程序。 ([源代码](https://github.com/bluecherrydvr/bluecherry-apps)) `GPL-2.0` `PHP`
- [Frigate](https://frigate.video/) - 使用本地处理的人工智能监控您的安全摄像头。 ([源代码](https://github.com/blakeblackshear/frigate)) `MIT` `Docker/Python/Node.js`
- [motionEye](https://github.com/motioneye-project/motioneye) - Motion 软件的在线界面，Motion 是一款具备运动检测功能的视频监控程序。 `GPL-3.0` `Python/Docker`
- [Secluso](https://secluso.com) - 基于树莓派的私人 DIY 家庭安防摄像系统，提供端对端加密远程访问和支持实时视频、警报及录像回放的移动应用。 ([源代码](https://github.com/secluso/core)) `GPL-3.0` `Rust`
- [SentryShot](https://codeberg.org/SentryShot/sentryshot) - 视频监控管理系统。 `GPL-2.0` `Docker/Rust`
- [Strix](https://github.com/eduard256/Strix) - 自动发现 IP 摄像头的可用流地址，并生成即用型 Frigate 和 go2rtc 配置文件。 `MIT` `Go/Docker`
- [Viseron](https://viseron.netlify.app/) - 自托管、仅限本地的 NVR 和 AI 计算机视觉软件。具有物体检测、动作检测、面部识别等功能，让您能够监控家中、办公室或其他任何想监视的地方。 ([源代码](https://github.com/roflcoopter/viseron)) `MIT` `Docker`
- [Zoneminder](https://www.zoneminder.com/) - 支持IP、USB和模拟摄像头的闭路电视（CCTV）软件应用程序。 ([源代码](https://github.com/ZoneMinder/ZoneMinder)) `GPL-2.0` `PHP/deb`


### 订阅阅读器

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[新闻聚合器](https://en.wikipedia.org/wiki/News_aggregator)，也称为订阅聚合器、订阅阅读器、新闻阅读器、[RSS](https://en.wikipedia.org/wiki/RSS)阅读器，是一种将网页内容（如报纸/博客/视频博客/播客）集中在一个位置以便轻松查看的应用程序。

- [Bubo Reader](https://github.com/georgemandis/bubo-rss) - 非常极简的 RSS 阅读器。 ([演示](https://bubo-rss-demo.netlify.app/)) `MIT` `Node.js`
- [CommaFeed](https://www.commafeed.com/) - 受Google Reader启发的自托管RSS阅读器。 ([演示](https://www.commafeed.com/#/app/category/all), [源代码](https://github.com/Athou/commafeed)) `Apache-2.0` `Java/Docker`
- [FeedCord](https://github.com/Qolors/FeedCord) `⚠` - 简单、轻量且可自定义的 Discord 服务器 RSS 新闻订阅工具。 `MIT` `Docker`
- [Feeds Fun](https://feeds.fun/) - 带标签、评分和 AI 的新闻阅读器。 ([源代码](https://github.com/Tiendil/feeds.fun)) `BSD-3-Clause` `Python`
- [FreshRSS](https://freshrss.org/) - 可自托管的 RSS 聚合器。 ([演示](https://demo.freshrss.org/i/), [源代码](https://github.com/FreshRSS/FreshRSS)) `AGPL-3.0` `PHP/Docker`
- [Fusion](https://github.com/0x2E/fusion) - 轻量级的 RSS 聚合器和阅读器。 `MIT` `Go/Docker`
- [JARR](https://1pxsolidblack.pl/jarr-en.html) - JARR（Just Another RSS Reader）是一个基于Web的新闻聚合器和阅读器（是Newspipe的分支）。 ([演示](https://www.jarr.info/), [源代码](https://github.com/jaesivsm/JARR)) `AGPL-3.0` `Docker/Python`
- [Kriss Feed](https://github.com/tontof/kriss_feed) - 简单而智能（或愚蠢）的Feed阅读器。 `CC0-1.0` `PHP`
- [Leed](https://github.com/LeedRSS/Leed) - Leed（Light Feed的缩写）是一个免费且极简的RSS聚合器。 `AGPL-3.0` `PHP`
- [Miniflux](https://miniflux.app/) - 极简新闻阅读器。 ([源代码](https://github.com/miniflux/v2)) `Apache-2.0` `Go/deb/Docker`
- [NewsBlur](https://www.newsblur.com/) - 个人新闻阅读器，将人们聚集在一起讨论世界。一种古老乐器的新声音。 ([源代码](https://github.com/samuelclay/NewsBlur)) `MIT` `Python`
- [Newspipe](https://git.sr.ht/~cedric/newspipe) - 网页新闻阅读器。 ([演示](https://www.newspipe.org/signup)) `AGPL-3.0` `Python`
- [reader](https://github.com/lemon24/reader) - 仅依赖标准库和纯 Python 的订阅阅读器 Web 应用与库（可用于自定义构建）。 `BSD-3-Clause` `Python`
- [Readflow](https://readflow.app) - 轻量级新闻阅读器，拥有现代化界面和功能：全文搜索、自动分类、归档、离线支持和通知。 ([源代码](https://github.com/ncarlier/readflow)) `AGPL-3.0` `Go/Docker`
- [RSS-Bridge](https://github.com/RSS-Bridge/rss-bridge) - 为没有提供 RSS/ATOM 订阅的网站生成相应的订阅源。 `Unlicense` `PHP/Docker`
- [RSS Monster](https://github.com/pietheinstrengholt/rssmonster) - 易用的基于 Web 的 RSS 聚合与阅读器，兼容 Fever API（Google Reader 的替代方案）。 `MIT` `PHP`
- [RSS2EMail](https://github.com/rss2email/rss2email) - 获取 RSS/Atom 源并将新内容推送到任意邮箱，支持 OPML。 `GPL-2.0` `Python/deb`
- [RSSHub](https://docs.rsshub.app) - 易用且可扩展的 RSS 聚合器，几乎可以为所有内容生成 RSS 源，从社交媒体到高校部门均可覆盖。 ([演示](https://rsshub.app), [源代码](https://github.com/DIYgod/RSSHub)) `MIT` `Node.js/Docker`
- [Selfoss](https://selfoss.aditu.de/) - 新型多用途 RSS 阅读器、实时流、混搭、聚合 Web 应用程序。 ([源代码](https://github.com/fossar/selfoss)) `GPL-3.0` `PHP`
- [Stringer](https://github.com/stringer-rss/stringer) - 正在进行中的自托管、反社交的 RSS 阅读器。 `MIT` `Ruby`
- [Tiny Tiny RSS](https://tt-rss.org) - 基于 Web 的新闻源（RSS/Atom）阅读与聚合工具。 ([源代码](https://github.com/tt-rss/tt-rss)) `GPL-3.0` `Docker/PHP`
- [TinyFeed](https://feed.lovergne.dev/) - 使用简单 CLI 从多个订阅源生成静态 HTML 页面。 ([演示](https://feed.lovergne.dev/demo), [源代码](https://github.com/TheBigRoomXXL/tinyfeed)) `MIT` `Go/Docker`
- [Upvote RSS](https://www.upvote-rss.com/) `⚠` - 从 Reddit、Hacker News、Lemmy、Mbin 等生成丰富的 RSS 源。 ([演示](https://www.upvote-rss.com/), [源代码](https://github.com/johnwarne/upvote-rss)) `MIT` `Docker/PHP`
- [Yarr](https://github.com/nkanaev/yarr) - Yarr（yet another rss reader）是一个基于Web的Feed聚合器，可以用作桌面应用程序和个人自托管服务器。 `MIT` `Go`


### 资源规划

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

用于[资源和供应规划](https://en.wikipedia.org/wiki/Resource_planning)的软件和工具，包括[企业资源和供应规划（ERP）](https://en.wikipedia.org/wiki/Enterprise_resource_planning)。

_相关: [资金、预算和管理](#资金、预算和管理), [库存管理](#库存管理)_

- [Dolibarr](https://www.dolibarr.org/) - 现代化 CRM 软件包，用于管理您的公司或基金会活动（联系人、供应商、发票、订单、库存、日程、会计等）。 ([演示](https://www.dolibarr.org/onlinedemo.php), [源代码](https://github.com/Dolibarr/dolibarr)) `GPL-3.0` `PHP/deb`
- [ERPNext](https://frappe.io/erpnext) - 用于帮助您管理业务的ERP系统。 ([源代码](https://github.com/frappe/erpnext)) `GPL-3.0` `Python/Docker`
- [farmOS](https://farmos.org/) - 基于Web的农场记录管理应用程序。 ([演示](https://farmos-demo.rootedsolutions.io/), [源代码](https://github.com/farmOS/farmOS)) `GPL-2.0` `PHP/Docker`
- [grocy](https://grocy.info/) - 超越冰箱的ERP。为您的家庭提供杂货和家务管理解决方案。 ([演示](https://en.demo.grocy.info/), [源代码](https://github.com/grocy/grocy)) `MIT` `PHP/Docker`
- [LedgerSMB](https://ledgersmb.org/) - 面向小型和中型企业的集成会计和企业资源规划（ERP）系统，具有复式会计、预算、发票、报价、项目、订单和库存管理、运输等功能。 ([源代码](https://github.com/ledgersmb/LedgerSMB)) `GPL-2.0` `Docker/Perl`
- [Odoo](https://www.odoo.com) - 免费开源的ERP系统。 ([演示](https://demo.odoo.com/), [源代码](https://github.com/odoo/odoo)) `LGPL-3.0` `Python/deb/Docker`
- [OFBiz](https://ofbiz.apache.org/) - 企业资源规划系统，具有一套灵活到可在任何行业中使用的业务应用程序。 ([源代码](https://github.com/apache/ofbiz-framework)) `Apache-2.0` `Java`
- [Tryton](https://www.tryton.org/) - 免费的开源商业解决方案。 ([演示](https://www.tryton.org/demo), [源代码](https://foss.heptapod.net/tryton/tryton)) `GPL-3.0` `Python`


### 资金、预算和管理

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[资金管理](https://en.wikipedia.org/wiki/Money_management)和预算软件。

_相关: [库存管理](#库存管理), [资源规划](#资源规划)_

- [Actual](https://actualbudget.org) - 本地优先的个人理财工具，基于零基预算，支持多设备同步、自定义规则、手动导入交易（支持 QIF、OFX 和 QFX 文件），并可选与多家银行自动同步。 ([源代码](https://github.com/actualbudget/actual)) `MIT` `Node.js/Docker`
- [Bigcapital](https://bigcapital.app/) - 面向中小企业的财务会计和库存管理软件。 ([源代码](https://github.com/bigcapitalhq/bigcapital)) `AGPL-3.0` `Docker`
- [Bitcart](https://bitcart.ai) - 加密货币支付处理器和开发平台。 ([演示](https://admin.bitcart.ai), [源代码](https://github.com/bitcart/bitcart)) `MIT` `Docker/Python/Node.js`
- [BTCPay Server](https://btcpayserver.org/) - 比特币及其他加密货币的支付处理器。 ([演示](https://mainnet.demo.btcpayserver.org/), [源代码](https://github.com/btcpayserver/btcpayserver)) `MIT` `C#`
- [DePay](https://depay.com) - 直接将 Web3 支付接入您的钱包。点对点、免费、自托管和开源。 ([演示](https://depay.com/products/payments), [源代码](https://github.com/depayfi/widgets)) `MIT` `Node.js`
- [Econumo](https://econumo.com) - 个人和家庭财务管理的预算应用程序，支持多种货币、联合账户和预算。 ([演示](https://demo.econumo.com), [源代码](https://github.com/econumo/econumo)) `MIT` `Docker`
- [ExpenseOwl](https://github.com/tanq16/expenseowl) - 极其简单且拥有美观界面的记账工具。 `MIT` `Go/Docker/K8S`
- [ezbookkeeping](https://ezbookkeeping.mayswind.net/) - 一个轻量级的个人记账应用，您可以自行托管。 ([演示](https://ezbookkeeping-demo.mayswind.net/), [源代码](https://github.com/mayswind/ezbookkeeping)) `MIT` `Go/Docker`
- [Family Accounting Tool](https://github.com/nymanjens/facto) - 面向部分共享费用的伴侣的基于Web的财务管理工具。 `Apache-2.0` `Scala`
- [Fava](https://beancount.github.io/fava/) - Beancount 的 Web 前端，是一个基于文本的复式记账系统。 ([演示](https://fava.pythonanywhere.com/example-with-budgets/income_statement/), [源代码](https://github.com/beancount/fava)) `MIT` `Python`
- [Firefly III](https://firefly-iii.org/) - Firefly III 是一款现代财务管理软件。它帮助您追踪您的资金并进行预算预测。支持信用卡，具有先进的规则引擎，并可从许多银行导入数据。 ([演示](https://demo.firefly-iii.org/), [源代码](https://github.com/firefly-iii/firefly-iii)) `AGPL-3.0` `PHP/Docker`
- [FOSSBilling](https://fossbilling.org/) - 托管和账单自动化。集成 WHM、CWP、cPanel 和 HestiaCP。提供完整 API，易于扩展。 ([演示](https://fossbilling.org/demo), [源代码](https://github.com/FOSSBilling/FOSSBilling)) `Apache-2.0` `PHP/Docker`
- [Galette](https://galette.eu/) - 面向非营利组织的会员管理Web应用程序。 ([源代码](https://github.com/galette/galette)) `GPL-3.0` `PHP`
- [Ghostfolio](https://ghostfol.io/) - 财富管理软件，用于跟踪股票、ETF和加密货币。 ([源代码](https://github.com/ghostfolio/ghostfolio)) `AGPL-3.0` `Docker/Node.js`
- [GRR](https://grr.devome.com/?lang=en) - 面向小型/中型公司的资产管理和预订系统。 ([源代码](https://github.com/JeromeDevome/GRR)) `GPL-2.0` `PHP`
- [HyperSwitch](https://hyperswitch.io/) `⚠` - 支付切换平台，让支付变得快速、可靠且实惠。通过单一 API 集成，轻松连接多个支付处理器并实现流量路由。 ([源代码](https://github.com/juspay/hyperswitch)) `Apache-2.0` `Docker/Rust`
- [IHateMoney](https://ihatemoney.org/) - 轻松管理您的共享费用。 ([演示](https://ihatemoney.org/demo/), [源代码](https://github.com/spiral-project/ihatemoney)) `BSD-3-Clause` `Docker/Python`
- [InvoicePlane](https://www.invoiceplane.com/) - 为您的小型企业管理报价、发票、付款和客户。 ([源代码](https://github.com/InvoicePlane/InvoicePlane)) `MIT` `PHP`
- [InvoiceShelf](https://invoiceshelf.com/) - 跟踪支出、付款并创建专业发票和报价单（Crater 的分支）。 ([源代码](https://github.com/InvoiceShelf/InvoiceShelf)) `AGPL-3.0` `PHP/Docker`
- [Kill Bill](https://killbill.io/) - 订阅计费与支付平台，提供实时分析和财务报表访问。 ([源代码](https://github.com/killbill/killbill)) `Apache-2.0` `Java/Docker`
- [Kresus](https://kresus.org/) - 个人财务管理工具。 ([演示](https://kresus.org/en/demo.html), [源代码](https://github.com/kresusapp/kresus)) `AGPL-3.0` `Node.js/Docker`
- [Lago](https://www.getlago.com/) - 计量与基于用量的计费平台。 ([源代码](https://github.com/getlago/lago)) `AGPL-3.0` `Docker`
- [monetr](https://monetr.app/) - 专注于规划周期性支出的预算应用。 ([源代码](https://github.com/monetr/monetr)) `FSL-1.1-MIT` `Docker/K8S`
- [Mybucks.online](https://mybucks.online) - 安全的、基于浏览器的、仅需密码的自托管加密货币钱包。 ([演示](https://app.mybucks.online), [源代码](https://github.com/mybucks-online/app)) `MIT` `Node.js`
- [MyFin Budget](https://myfinbudget.com) - 个人财务平台（Web + REST API + Android），帮助您预算、跟踪收入/支出并预测财务未来。 ([演示](https://github.com/afaneca/myfin?tab=readme-ov-file#demo-account---try-it-for-yourself), [源代码](https://github.com/afaneca/myfin), [客户端](https://github.com/afaneca/myfin-api)) `GPL-3.0` `Node.js/Docker`
- [OctoBot](https://www.octobot.cloud/) - 加密货币交易机器人。 ([源代码](https://github.com/Drakkar-Software/OctoBot)) `GPL-3.0` `Python/Docker`
- [Ocular](https://simonwep.github.io/ocular/) - 简约直接的预算管理应用，可跟踪您跨月份和年份的预算。 ([演示](https://simonwep.github.io/ocular/demo/#demo), [源代码](https://github.com/simonwep/ocular)) `MIT` `Docker`
- [OpenBudgeteer](https://github.com/TheAxelander/OpenBudgeteer) - 基于桶式预算原则的预算管理应用。 `AGPL-3.0` `Docker/C#`
- [Receipt Wrangler](https://receiptwrangler.io) `⚠` - 易用的发票管理器，AI 驱动。用户可轻松快速创建发票、分类等。 ([演示](https://demo.receiptwrangler.io), [源代码](https://github.com/Receipt-Wrangler/receipt-wrangler)) `AGPL-3.0` `Docker`
- [REI3](https://rei3.de/home_en/) - 在企业内部管理任务、时间、资产等多种事务。 ([演示](https://rei3.de/demo_en/), [源代码](https://github.com/r3-team/r3)) `MIT` `Go`
- [SHKeeper](https://shkeeper.io/) - 加密货币支付处理器，具有网关和商家的独特组合，允许您在没有费用和中介的情况下接受多种加密货币付款。 ([演示](https://github.com/vsys-host/shkeeper.io?tab=readme-ov-file#11-demo), [源代码](https://github.com/vsys-host/shkeeper.io)) `GPL-3.0` `Python`
- [SolidInvoice](https://solidinvoice.co) - 开源的发票和报价应用程序。 ([源代码](https://github.com/SolidInvoice/SolidInvoice)) `MIT` `PHP`
- [Sure](https://github.com/we-promise/sure) - 面向所有人的个人财务应用（Maybe 的分支）。 `AGPL-3.0` `Docker`
- [VoucherVault](https://github.com/l4rm4nd/VoucherVault) - 数字化存储和管理代金券、优惠券、会员卡和礼品卡。支持到期通知、交易历史、文件上传和OIDC单点登录。 `GPL-3.0` `Docker`
- [Wallos](https://wallosapp.com) - 轻量级个人订阅跟踪器，带有统计功能和可选通知。 ([演示](https://github.com/ellite/wallos?tab=readme-ov-file#demo), [源代码](https://github.com/ellite/wallos)) `GPL-3.0` `PHP/Docker`
- [WYGIWYH](https://github.com/eitchtee/WYGIWYH) - 简单而强大的财务跟踪器。 ([演示](https://wygiwyh-demo.herculino.com/)) `AGPL-3.0` `Docker/Python`
- [YAFFA](https://www.yaffa.cc) - 个人财务网络应用，可用于跟踪您的资金、支出、预算和投资。它还帮助进行长期财务规划。 ([演示](https://sandbox.yaffa.cc), [源代码](https://github.com/kantorge/yaffa)) `MIT` `PHP`


### 路由器

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

用于管理[路由器](https://en.wikipedia.org/wiki/Router_(computing))硬件的软件。

- [DD-WRT](https://dd-wrt.com/) - 基于 Linux 的无线路由器和接入点固件，最初为 Linksys WRT54G 设计。 ([源代码](https://svn.dd-wrt.com/)) `GPL-2.0` `C`
- [IPFire](https://www.ipfire.org/) - 免费的网络防火墙发行版，基于 Linux 操作系统，提供易于使用的 Web 管理控制台。 ([源代码](https://github.com/ipfire/ipfire-2.x)) `GPL-2.0` `Shell/PHP/Other`
- [OpenWrt](https://openwrt.org/) - 基于 Linux 的路由器，支持 Mesh 网络、Snort IPS、AQM 等多种功能。 ([源代码](https://github.com/openwrt/openwrt)) `GPL-2.0` `C`
- [OPNsense](https://opnsense.org/) - 基于 FreeBSD 的开源防火墙和路由器，支持流量整形、负载均衡和 VPN。 ([源代码](https://github.com/opnsense)) `BSD-2-Clause` `C/PHP`
- [pfSense CE](https://www.pfsense.org/) - 基于 FreeBSD 的免费网络防火墙发行版，内核定制并集成第三方自由软件包。 ([源代码](https://github.com/pfsense/pfsense)) `Apache-2.0` `Shell/PHP/Other`


### 身份管理 - LDAP

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[轻量级目录访问协议（LDAP）](https://en.wikipedia.org/wiki/Lightweight_Directory_Access_Protocol) 是一种开放、中立、行业标准的应用协议，用于通过 IP 网络访问和维护分布式目录信息服务。

- [389 Directory Server](https://www.port389.org/) - 企业级开源 LDAP 服务器，适用于 Linux。 ([源代码](https://github.com/389ds/389-ds-base)) `GPL-3.0` `C`
- [Apache Directory Server](https://directory.apache.org/apacheds/) - 可扩展、可嵌入的目录服务器，兼容 LDAPv3，支持 Kerberos 5、变更密码协议、触发器、存储过程、队列和视图。 ([源代码](https://github.com/apache/directory-server)) `Apache-2.0` `Java`
- [FreeIPA](https://www.freeipa.org/) - 集成安全信息管理解决方案，结合 Linux（Fedora）、389 Directory Server、Kerberos、NTP、DNS 和 Dogtag 证书系统（Web 界面和命令行管理工具）。 ([源代码](https://pagure.io/freeipa)) `GPL-3.0` `Python/C/JavaScript`
- [FreeRADIUS](https://freeradius.org/) - 多协议策略服务器（radiusd），实现 RADIUS、DHCP、BFD 和 ARP 及相关客户端/PAM 库/Apache 模块。 ([源代码](https://github.com/FreeRADIUS/freeradius-server)) `GPL-2.0` `C`
- [lldap](https://github.com/lldap/lldap) - 轻量级（简化版）LDAP 实现，带有简单直观的 Web 界面和 GraphQL 支持。 `GPL-3.0` `Rust`
- [LTB Self-Service Password](https://www.ltb-project.org/documentation/self-service-password.html) - 用于修改和重置 LDAP 密码的 Web 界面。 ([源代码](https://github.com/ltb-project/self-service-password)) `GPL-3.0` `PHP`
- [OpenLDAP](https://www.openldap.org/) - 轻量级目录访问协议的开源实现（服务器、库和客户端）。 ([源代码](https://git.openldap.org/openldap/openldap)) `OLDAP-2.8` `C`


### 身份管理 - 单点登录（SSO）

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[单点登录（SSO）](https://en.wikipedia.org/wiki/Single_sign-on) 是一种认证方案，允许用户使用单一身份登录多个相关但独立的软件系统。

- [Authelia](https://www.authelia.com/) - Web 应用的单点登录多因素门户。 ([源代码](https://github.com/authelia/authelia)) `Apache-2.0` `Go`
- [Authentik](https://goauthentik.io/) - 灵活的身份提供者，支持多种协议（OAuth 2.0、SAML、LDAP 和 Radius）。 ([源代码](https://github.com/goauthentik/authentik)) `MIT` `Python`
- [KeyCloak](https://www.keycloak.org) - 开源身份与访问管理。 ([源代码](https://github.com/keycloak/keycloak)) `Apache-2.0` `Java`


### 身份管理 - 工具和 Web 界面

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

身份管理系统的各种工具和 Web 界面。

- [BounCA](https://bounca.org/) - 个人 SSL 密钥/证书颁发机构 Web 工具，用于创建自签名证书。 ([源代码](https://gitlab.com/bounca/bounca/)) `Apache-2.0` `Python`
- [easy-rsa](https://github.com/OpenVPN/easy-rsa) - 用于构建和管理 PKI CA 的 Bash 脚本。 `GPL-2.0` `Shell`
- [Fusion Directory](https://www.fusiondirectory.org) - 基于 OpenLDAP 的企业目录和服务管理。 ([源代码](https://github.com/fusiondirectory/fusiondirectory)) `GPL-2.0` `PHP`
- [LDAP Account Manager (LAM)](https://www.ldap-account-manager.org/lamcms/) - 用于管理 LDAP 目录中条目（如用户、组、DHCP 设置）的 Web 前端。 ([源代码](https://github.com/LDAPAccountManager/lam/)) `GPL-3.0` `PHP`
- [Libravatar](https://www.libravatar.org/) - 向其他网站分发头像（个人资料图片）的服务。 ([源代码](https://git.linux-kernel.at/oliver/ivatar/)) `AGPL-3.0` `Python`
- [Smallstep Certificates](https://smallstep.com/certificates/) - 私有证书颁发机构（X.509 & SSH）及相关自动化证书管理工具。 ([源代码](https://github.com/smallstep/certificates)) `Apache-2.0` `Go`
- [ZITADEL](https://zitadel.com/) - 云原生身份与访问管理解决方案，提供安全认证、授权和身份管理平台。 ([源代码](https://github.com/zitadel/zitadel)) `Apache-2.0` `Go/Docker/K8S`


### 软件容器

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[操作系统级](https://en.wikipedia.org/wiki/OS-level_virtualization)虚拟化。

- [Docker Compose](https://docs.docker.com/compose/) - 定义和运行多容器 Docker 应用。 ([源代码](https://github.com/docker/compose)) `Apache-2.0` `Go`
- [Docker Swarm](https://docs.docker.com/engine/swarm/) - 管理 Docker 引擎集群。 ([源代码](https://github.com/moby/swarmkit)) `Apache-2.0` `Go`
- [Docker](https://www.docker.com/) - 为开发者和系统管理员构建、发布和运行分布式应用的平台。 ([源代码](https://www.docker.com/community/open-source/)) `Apache-2.0` `Go`
- [LXC](https://linuxcontainers.org/lxc/) - Linux 内核容器特性的用户空间接口。 ([源代码](https://github.com/lxc/lxc)) `GPL-2.0` `C`
- [LXD](https://linuxcontainers.org/lxd/) - 容器“管理器”，为 LXC 提供更好的用户体验。 ([源代码](https://github.com/canonical/lxd)) `Apache-2.0` `Go`
- [OpenVZ](https://github.com/OpenVZ) - Linux 的基于容器的虚拟化。 ([源代码](https://src.openvz.org/projects/OVZ)) `GPL-2.0` `C`
- [Podman](https://podman.io) - 无守护进程的容器引擎，支持以 root 或 rootless 模式运行。可直接 `alias docker=podman`。 ([源代码](https://github.com/containers/podman)) `Apache-2.0` `Go`
- [Portainer Community Edition](https://www.portainer.io/) - 简单易用的 Docker 管理界面。 ([源代码](https://github.com/portainer/portainer)) `Zlib` `Go`
- [systemd-nspawn](https://www.freedesktop.org/software/systemd/man/systemd-nspawn.html) - 轻量级、类似 chroot 的环境，可直接在 systemd 下运行操作系统或命令。 ([源代码](https://github.com/systemd/systemd)) `GPL-2.0` `C`


### 软件开发

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[软件开发](https://en.wikipedia.org/wiki/Software_development)是涉及构思、规范、设计、编程、文档编制、测试和修复错误的过程，用于创建和维护应用程序、框架或其他软件组件。

**请访问 [软件开发 - API 管理](#软件开发 - API 管理), [软件开发 - 持续集成与部署](#软件开发 - 持续集成与部署), [软件开发 - FaaS 和无服务器](#软件开发 - FaaS 和无服务器), [软件开发 - IDE 和工具](#软件开发 - IDE 和工具), [软件开发 - 本地化](#软件开发 - 本地化), [软件开发 - 低代码](#软件开发 - 低代码), [软件开发 - 项目管理](#软件开发 - 项目管理), [软件开发 - 测试](#软件开发 - 测试), [软件开发 - 功能开关](#软件开发 - 功能开关)**



### 软件开发 - API 管理

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[API管理](https://en.wikipedia.org/wiki/API_management)是创建和发布[应用程序编程接口（API）](https://en.wikipedia.org/wiki/API)、强制执行其使用政策、控制访问、培养订阅者社区、收集和分析使用统计数据，并报告性能的过程。

- [Aastro](https://starwalkn.github.io/aastro-docs) - 用 Go 编写的可扩展 API 网关。 ([源代码](https://github.com/starwalkn/aastro)) `Apache-2.0` `Go/Docker`
- [DreamFactory](https://www.dreamfactory.com/) - 将任何 SQL/NoSQL/结构化数据转换为 Restful API。 ([源代码](https://github.com/dreamfactorysoftware/dreamfactory)) `Apache-2.0` `PHP/Docker/K8S`
- [form.io](https://form.io) - 一种利用拖放表单构建器的 REST API 构建平台，应用框架无关。包含开源和企业版本。 ([演示](https://portal.form.io), [源代码](https://github.com/formio)) `MIT` `Node.js/Docker`
- [Fusio](https://www.fusio-project.org/) - 开源的API管理平台，帮助构建和管理REST API。 ([演示](https://fusio-project.org/demo), [源代码](https://github.com/apioo/fusio)) `AGPL-3.0` `PHP/Docker`
- [Graphweaver](https://graphweaver.com/) - 将多个数据源转换为单一的GraphQL API。 ([源代码](https://github.com/exogee-technology/graphweaver)) `MIT` `Node.js`
- [Hasura](https://hasura.io) - 在Postgres上快速、即时的实时GraphQL API，具有细粒度的访问控制，还可在数据库事件上触发Webhooks。 ([源代码](https://github.com/hasura/graphql-engine)) `Apache-2.0` `Haskell/Docker/K8S`
- [Hoppscotch Community Edition](https://hoppscotch.io) - 快速且美观的 API 请求构建器。 ([源代码](https://github.com/hoppscotch/hoppscotch)) `MIT` `Node.js/Docker`
- [Kong](https://konghq.com/kong/) - 微服务 API 网关与平台。 ([源代码](https://github.com/Kong/kong)) `Apache-2.0` `Lua/Docker/K8S/deb`
- [Lura](https://luraproject.org/) - 高性能 API 网关。 ([源代码](https://github.com/luraproject/lura)) `Apache-2.0` `Go`
- [Opik](https://www.comet.com/site/products/opik/) `⚠` - 通过一套可观察性工具评估、测试和发布LLM应用，帮助在开发和生产生命周期中校准语言模型输出。 ([源代码](https://github.com/comet-ml/opik)) `Apache-2.0` `Docker/Python`
- [Para](https://paraio.org) - 灵活且模块化的后端框架/服务器，用于对象持久化、API开发和身份验证。 ([源代码](https://github.com/erudika/para)) `Apache-2.0` `Java/Docker`
- [Svix](https://svix.com) - 作为服务的开源 Webhooks，使 API 提供商轻松发送 Webhooks。 ([源代码](https://github.com/svix/svix-webhooks)) `MIT` `Docker/Rust`
- [Tyk](https://tyk.io) - 快速而可扩展的开源API网关。Tyk提供了一个API管理平台，其中包括API网关、API分析、开发者门户和API管理仪表板。 ([源代码](https://github.com/TykTechnologies/tyk)) `MPL-2.0` `Go/Docker/K8S`


### 软件开发 - FaaS 和无服务器

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[无服务器计算](https://en.wikipedia.org/wiki/Serverless_computing)，[函数即服务 (FaaS)](https://en.wikipedia.org/wiki/Function_as_a_service) 和 [平台即服务 (PaaS)](https://en.wikipedia.org/wiki/Platform_as_a_service) 管理软件。

**请访问 [awesome-sysadmin/PaaS](https://github.com/awesome-foss/awesome-sysadmin#paas)**



### 软件开发 - IDE 和工具

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[集成开发环境 (IDE)](https://en.wikipedia.org/wiki/Integrated_development_environment) 是一种为计算机程序员提供全面开发工具的软件应用程序。

_相关: [软件开发 - 低代码](#软件开发---低代码)_

- [Atheos](https://www.atheos.io) - 一个基于Web的 IDE 框架，占用空间小、要求最低，是 Codiad 的延续。 ([源代码](https://github.com/Atheos/Atheos)) `MIT` `PHP/Docker`
- [code-server](https://github.com/coder/code-server) - 在浏览器中运行的VS Code，托管在远程服务器上。 `MIT` `Node.js/Docker`
- [Coder](https://coder.com/) - 在您自己的基础设施上进行远程开发机器。 ([源代码](https://github.com/coder/coder)) `AGPL-3.0` `Go/Docker/K8S/deb`
- [Eclipse Che](https://www.eclipse.org/che/) - 开源工作空间服务器和云IDE。 ([源代码](https://github.com/eclipse-che/che)) `EPL-1.0` `Docker/Java`
- [Judge0 CE](https://judge0.com) - 用于编译和运行源代码的 API。 ([源代码](https://github.com/judge0/judge0)) `GPL-3.0` `Docker`
- [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) - 基于Web的交互式和可重现计算环境。 ([演示](https://mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/try.jupyter.org?urlpath=lab), [源代码](https://github.com/jupyterlab/jupyterlab/)) `BSD-3-Clause` `Python/Docker`
- [Langfuse](https://langfuse.com) - LLM 工程平台，用于模型追踪、提示管理和应用评估。Langfuse 帮助团队协作调试、分析和迭代他们的 LLM 应用，如聊天机器人或 AI 代理。 ([演示](https://langfuse.com/docs/demo), [源代码](https://github.com/langfuse/langfuse), [客户端](https://langfuse.com/docs/integrations/overview)) `MIT` `Docker`
- [LiveCodes](https://livecodes.io/docs/features/self-hosting) `⚠` - 功能丰富的客户端代码演练场，支持 React、Vue、Svelte、Solid、TypeScript、Python、Go、Ruby、PHP 及 90+ 种其他语言。 ([演示](https://livecodes.io), [源代码](https://github.com/live-codes/livecodes)) `MIT` `Node.js`
- [Lowdefy](https://www.lowdefy.com/) - 使用YAML / JSON在自托管的开源平台上，在几分钟内构建内部工具、BI仪表板、管理面板、CRUD应用程序和工作流。连接到您的数据源，通过Serverless、Netlify或Docker进行托管。 ([源代码](https://github.com/lowdefy/lowdefy)) `Apache-2.0` `Node.js/Docker`
- [RapidForge](https://rapidforge.io/) - 轻量级平台，用于构建 Webhook、定时任务和页面。可用 Bash 或 Lua 实现自定义逻辑。 ([源代码](https://github.com/rapidforge-io/rapidforge)) `Apache-2.0` `Go/Node.js`
- [RStudio Server](https://www.rstudio.com/products/rstudio/#Server) - 基于 Web 浏览器的 R 语言集成开发环境（IDE）。 ([源代码](https://github.com/rstudio/rstudio)) `AGPL-3.0` `Java/C++`


### 软件开发 - 低代码

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[低代码](https://en.wikipedia.org/wiki/Low-code_development_platform) 开发平台 (LCDP) 提供一个通过图形用户界面创建应用软件的开发环境。

_相关: [软件开发 - IDE 和工具](#软件开发---ide-和工具)_

- [Appsmith](https://www.appsmith.com/) - 构建管理面板、CRUD 应用和工作流。以 10 倍速度构建所需的一切。 ([源代码](https://github.com/appsmithorg/appsmith)) `Apache-2.0` `Java/Docker/K8S`
- [Appwrite](https://appwrite.io) - 为 Web、本地和移动开发人员提供的端到端后端服务器 🚀。 ([源代码](https://github.com/appwrite/appwrite)) `BSD-3-Clause` `Docker`
- [autokitteh](https://autokitteh.com/) - 用仅几行代码实现持久的工作流自动化。 ([源代码](https://github.com/autokitteh/autokitteh)) `Apache-2.0` `Go/Docker`
- [Halo](https://www.halo.run) - 一款功能强大且易于使用的网站构建工具（文档为中文）。 ([演示](https://docs.halo.run/#%E5%9C%A8%E7%BA%BF%E4%BD%93%E9%AA%8C), [源代码](https://github.com/halo-dev/halo), [客户端](https://github.com/halo-sigs/awesome-halo)) `GPL-3.0` `Java/Docker`
- [Manifest](https://manifest.build) - 仅需一个 YAML 文件即可完成的完整后端。 ([演示](https://manifest.new), [源代码](https://github.com/mnfst/manifest)) `MIT` `Node.js`
- [PocketBase](https://pocketbase.io/) - 将下一款 SaaS 和移动应用所需后端整合在单个文件中的解决方案。 ([源代码](https://github.com/pocketbase/pocketbase)) `MIT` `Go/Docker`
- [Saltcorn](https://saltcorn.com/) - 无代码数据库应用构建器，适用于 Web 和移动应用。集成用户界面、数据后端、持久化工作流、邮件、PDF 生成和 AI 应用于一体的平台。 ([源代码](https://github.com/saltcorn/saltcorn)) `MIT` `Docker/Node.js`
- [SQLPage](https://sql-page.com) - 仅支持SQL的动态网站构建工具。 ([源代码](https://github.com/sqlpage/SQLPage)) `MIT` `Rust/Docker`
- [ToolJet](https://tooljet.io/) - 低代码框架，极少工程投入即可构建和部署内部工具（Retool 和 Mendix 的替代品）。 ([源代码](https://github.com/ToolJet/ToolJet)) `GPL-3.0` `Node.js/Docker/K8S`
- [TrailBase](https://trailbase.io/) - 开放、亚毫秒级、单可执行文件的 FireBase 替代品，带有类型安全的 REST 和实时 API，内置 JS/TS 运行时、认证及管理界面。 ([演示](https://demo.trailbase.io), [源代码](https://github.com/trailbaseio/trailbase)) `OSL-3.0` `Rust/Docker`


### 软件开发 - 功能开关

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

软件开发中的[功能开关](https://en.wikipedia.org/wiki/Feature_toggle)为维护源代码中多个功能分支提供了一种替代方案。

_相关: [软件开发 - IDE 和工具](#软件开发---ide-和工具)_

- [Featbit](https://www.featbit.co/) - 企业级功能开关平台，支持自托管。 ([源代码](https://github.com/featbit/featbit)) `MIT` `Docker/K8S`
- [Flagsmith](https://flagsmith.com) - 用于为你的应用程序添加功能开关的仪表盘、API 和 SDK（LaunchDarkly 的替代方案）。 ([源代码](https://github.com/flagsmith/flagsmith)) `BSD-3-Clause` `Docker/K8S`
- [Flipt](https://flipt.io) - 具有多个数据后端支持的功能标志解决方案（与 LaunchDarkly 的替代方案）。 ([源代码](https://github.com/flipt-io/flipt)) `GPL-3.0` `Docker/K8S/Go`
- [GO Feature Flag](https://gofeatureflag.org) - 简单、完整且轻量级的功能标志解决方案（与LaunchDarkly的替代品）。 ([源代码](https://github.com/thomaspoignant/go-feature-flag)) `MIT` `Go`


### 软件开发 - 持续集成和部署

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[持续集成](https://en.wikipedia.org/wiki/Continuous_integration)和[持续部署](https://en.wikipedia.org/wiki/Continuous_deployment)的软件和工具。

**请访问 [awesome-sysadmin/持续集成和部署](https://github.com/awesome-foss/awesome-sysadmin#continuous-integration--continuous-deployment)**

_相关: [自动化](#自动化)_



### 软件开发 - 本地化

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[本地化](https://en.wikipedia.org/wiki/Internationalization_and_localization) 是将代码和软件适应其他语言的过程。

- [Accent](https://www.accent.reviews/) - 面向开发者的翻译工具。 ([源代码](https://github.com/mirego/accent)) `BSD-3-Clause` `Elixir/Docker`
- [Tolgee](https://tolgee.io) - 面向开发者和翻译人员的友好的基于Web的本地化平台，使用户能够直接在其开发的应用程序中进行翻译。 ([源代码](https://github.com/tolgee/tolgee-platform)) `Apache-2.0` `Docker/Java`
- [Traduora](https://traduora.co) - 面向团队的翻译管理平台。 ([源代码](https://github.com/ever-co/ever-traduora)) `AGPL-3.0` `Docker/K8S/Node.js`
- [Weblate](https://weblate.org) - 基于Web的翻译工具，与版本控制紧密集成。 ([源代码](https://github.com/WeblateOrg/weblate)) `GPL-3.0` `Python/Docker/K8S`


### 软件开发 - 测试

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

用于[软件测试](https://en.wikipedia.org/wiki/Software_testing)的工具和软件。

- [Bencher](https://bencher.dev/) - 一套持续基准测试工具套件，旨在在持续集成中捕捉性能回退。 ([源代码](https://github.com/bencherdev/bencher)) `MIT/Apache-2.0` `Rust`
- [Request Inbox](https://request-inbox.com/) - 用于测试和调试的 HTTP 请求收集与检查工具，支持创建收件箱、捕获请求详情和配置自定义响应。 ([演示](https://request-inbox.com/), [源代码](https://github.com/jesusnoseq/request-inbox)) `Apache-2.0` `Docker`
- [WebHook Tester](https://github.com/tarampampam/webhook-tester) - 用于测试 WebHook 等的强大工具。 `MIT` `Docker/Go/deb/K8S`


### 软件开发 - 项目管理

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

用于[软件项目管理](https://en.wikipedia.org/wiki/Software_project_management)的工具和软件。

_相关: [工单](#工单), [任务管理和待办清单](#任务管理和待办清单)_

- [Cgit](https://git.zx2c4.com/cgit/about/) - 用于 Git 仓库的快速轻量级 Web 界面。 ([源代码](https://git.zx2c4.com/cgit/tree/)) `GPL-2.0` `C`
- [Forgejo](https://forgejo.org) - 一款专注于扩展、联邦和隐私的轻量级软件锻造工具（基于 Gitea 的分支）。 ([演示](https://next.forgejo.org), [源代码](https://codeberg.org/forgejo/forgejo/), [客户端](https://codeberg.org/forgejo-contrib/delightful-forgejo)) `MIT` `Docker/Go`
- [Fossil](https://www.fossil-scm.org/index.html/doc/trunk/www/index.wiki) - 分布式版本控制系统，具有维基和缺陷跟踪器功能。 `BSD-2-Clause-FreeBSD` `C`
- [Gerrit](https://www.gerritcodereview.com/) - 基于 Git 的代码审查和项目管理工具。 ([源代码](https://github.com/GerritCodeReview/gerrit)) `Apache-2.0` `Java/Docker`
- [gitbucket](https://gitbucket.github.io/) - 具有易于安装、高度可扩展性和 GitHub API 兼容性的 Git 平台（GitHub 的替代方案）。 ([源代码](https://github.com/gitbucket/gitbucket)) `Apache-2.0` `Scala/Java`
- [Gitea](https://gitea.com) - 由社区管理的轻量级代码托管解决方案（Gogs的分支）。 ([演示](https://demo.gitea.com), [源代码](https://github.com/go-gitea/gitea)) `MIT` `Go/Docker/K8S`
- [GitLab](https://about.gitlab.com) - 自托管的Git仓库管理、代码审查、问题追踪、活动订阅和维基工具。 ([演示](https://gitlab.com/), [源代码](https://gitlab.com/gitlab-org/gitlab-foss)) `MIT` `Ruby/deb/Docker/K8S`
- [Gogs](https://gogs.io/) - 用Go编写的轻松自托管的Git服务。 ([源代码](https://github.com/gogs/gogs)) `MIT` `Go`
- [Huly](https://huly.io) - 一体化项目管理平台（可替代 Linear、Jira、Slack、Notion、Motion）。 ([演示](https://app.huly.io), [源代码](https://github.com/hcengineering/platform)) `EPL-2.0` `Docker/K8S/Node.js`
- [Ideon](https://www.theideon.com) - 基于无限画布的项目工作区，可嵌入 GitHub、GitLab、Gitea 和 Forgejo 仓库，并支持笔记、链接、任务和实时协作。 ([源代码](https://github.com/3xpyth0n/ideon)) `AGPL-3.0` `Docker`
- [Kaneo](https://kaneo.app/) - 注重简洁与高效的项目管理平台。 ([演示](https://demo.kaneo.app/), [源代码](https://github.com/usekaneo/kaneo)) `MIT` `K8S/Docker`
- [Leantime](https://leantime.io) - 面向小型团队和初创企业的精益项目管理系统，助力从创意构思到交付落地的全程项目管理。 ([源代码](https://github.com/leantime/leantime)) `AGPL-3.0` `PHP/Docker`
- [Mindwendel](https://www.mindwendel.com/) - 在团队内部进行头脑风暴，并投票支持想法和思考。 ([演示](https://www.mindwendel.com), [源代码](https://github.com/b310-digital/mindwendel)) `AGPL-3.0` `Docker/Elixir`
- [minimal-git-server](https://github.com/mcarbonne/minimal-git-server) - 轻量级 Git 服务器，提供基础 CLI 管理仓库，支持多账户并可在容器中运行。 `MIT` `Docker`
- [Octobox](https://octobox.io/) `⚠` - 重新掌控您的GitHub通知。 ([源代码](https://github.com/octobox/octobox)) `AGPL-3.0` `Ruby/Docker`
- [OneDev](https://onedev.io/) - 一体化的DevOps平台，包括Git管理、问题追踪和CI/CD。简单而强大。 ([源代码](https://code.onedev.io/projects/160)) `MIT` `Java/Docker/K8S`
- [OpenProject](https://www.openproject.org) - 管理您的项目、任务和目标。通过工作包进行协作，并将其链接到 GitHub 上的拉取请求。 ([源代码](https://github.com/opf/openproject)) `GPL-3.0` `Ruby/deb/Docker`
- [Pagure](https://pagure.io/pagure) - 轻量、强大且灵活的以 Git 为中心的代码托管平台，其功能为联邦化和去中心化开发奠定了基础。 ([演示](https://pagure.io/)) `GPL-2.0` `Docker/Python/deb`
- [Phorge](https://we.phorge.it/) - 社区驱动的软件开发项目协作、管理、组织与审查平台。 ([源代码](https://we.phorge.it/source/phorge/)) `Apache-2.0` `PHP`
- [Plane](https://plane.so) - 以尽可能简单的方式跟踪问题、史诗任务和产品路线图（JIRA、Linear 和 Height 的替代方案）。 ([演示](https://app.plane.so), [源代码](https://github.com/makeplane/plane)) `AGPL-3.0` `Docker`
- [ProjeQtOr](https://www.projeqtor.org/) - 完整、成熟的多用户项目管理系统，为项目各阶段提供广泛功能。 ([演示](https://demo.projeqtor.org/), [源代码](https://sourceforge.net/p/projectorria/code/HEAD/tree/branches/)) `AGPL-3.0` `PHP`
- [Redmine](https://www.redmine.org/) - 灵活的项目管理 Web 应用。 ([源代码](https://svn.redmine.org/redmine/)) `GPL-2.0` `Ruby`
- [Review Board](https://www.reviewboard.org/) - 适用于各种规模的项目和公司的可扩展且用户友好的代码审查工具。 ([演示](https://demo.reviewboard.org/), [源代码](https://github.com/reviewboard/reviewboard)) `MIT` `Python/Docker`
- [RhodeCode](https://rhodecode.com/) - 统一并简化 Git、Subversion 和 Mercurial 的仓库管理。 ([源代码](https://code.rhodecode.com/)) `AGPL-3.0` `Python`
- [Rukovoditel](https://www.rukovoditel.net/) - 可配置的开源项目管理，基于 Web 的应用程序。 ([源代码](https://www.rukovoditel.net/download.php)) `GPL-2.0` `PHP`
- [SCM Manager](https://www.scm-manager.org/) - 通过 http 最简单的方式共享和管理 Git、Mercurial 和 Subversion 仓库。 ([源代码](https://github.com/scm-manager/scm-manager)) `BSD-3-Clause` `Java/deb/Docker/K8S`
- [ShipShipShip](https://shipshipship.io) - 连接项目管理与客户沟通的变更日志与路线图平台。 ([演示](https://demo.shipshipship.io/admin), [源代码](https://github.com/GauthierNelkinsky/ShipShipShip)) `Apache-2.0` `Docker`
- [Smederee](https://smeder.ee) - 一个节俭的平台，致力于帮助人们一起构建出色的软件，充分发挥Darcs版本控制系统的力量。 ([源代码](https://smeder.ee/~jan0sch/smederee)) `AGPL-3.0` `Scala`
- [Sourcehut](https://sourcehut.org/) - 一个完整的无JavaScript Web Git界面。 ([演示](https://sr.ht/), [源代码](https://git.sr.ht/~sircmpwn/git.sr.ht/tree)) `GPL-2.0` `Go`
- [Taiga](https://www.taiga.io/) - 基于看板和 Scrum 方法的敏捷项目管理工具。 ([源代码](https://github.com/kaleidos-ventures)) `MPL-2.0` `Docker/Python/Node.js`
- [Titra](https://titra.io/) - 为自由职业者和小团队提供的时间跟踪解决方案。 ([源代码](https://github.com/titraio/titra)) `GPL-3.0` `JavaScript/Docker`
- [Trac](https://trac.edgewall.org/) - Trac是一个增强的维基和问题跟踪系统，用于软件开发项目。 `BSD-3-Clause` `Python/deb`
- [Traq](https://traq.io/) - 使用PHP编写的项目管理和问题跟踪系统。 ([源代码](https://github.com/nirix/traq)) `GPL-3.0` `PHP/Node.js`
- [Tuleap](https://www.tuleap.org/) - Tuleap是一个自由套件，用于计划、跟踪、编码和在软件项目上进行协作。 ([源代码](https://tuleap.net/plugins/git/tuleap/tuleap/stable?p=tuleap%2Fstable.git&a=tree)) `GPL-2.0` `PHP`
- [UVDesk](https://www.uvdesk.com/) - UVDesk社区是一个面向服务、事件驱动的可扩展的开源帮助台系统，可由您的组织轻松提供高效的客户支持，以您所想象的方式。 ([演示](https://demo.uvdesk.com/), [源代码](https://github.com/uvdesk/community-skeleton)) `MIT` `PHP`
- [ZenTao](https://www.zentao.pm/) - 敏捷（Scrum）项目管理系统/工具。 ([源代码](https://github.com/easysoft/zentaopms)) `AGPL-3.0` `PHP`


### 远程桌面客户端

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[远程桌面](https://en.wikipedia.org/wiki/Remote_desktop_software)客户端软件。

- [Remmina](https://www.remmina.org/) - 功能丰富的 Linux 及类 Unix 远程桌面应用。 ([源代码](https://gitlab.com/Remmina/Remmina)) `GPL-2.0` `C`
- [Tiger VNC](https://tigervnc.org/) - 高性能多平台 VNC 客户端和服务器。 ([源代码](https://github.com/TigerVNC/tigervnc)) `GPL-2.0` `C++`
- [X2go](https://wiki.x2go.org/doku.php) - 基于 NoMachine/NX 协议的 Linux 远程桌面软件。 ([源代码](https://code.x2go.org/gitweb)) `GPL-2.0` `Perl`


### 远程访问

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[远程桌面](https://en.wikipedia.org/wiki/Remote_desktop_software)和[SSH](https://en.wikipedia.org/wiki/Secure_Shell)服务器以及用于远程管理计算机系统的Web界面。

- [Cardea](https://github.com/hectorm/cardea) - 支持访问控制、会话录制和可选 TPM 密钥保护的 SSH 跳板服务器。 `EUPL-1.2` `Go/Docker`
- [Engity's Bifröst](https://bifroest.engity.org/) - 高度可定制的 SSH 服务器，提供多种用户授权方式，并可选择如何以及在哪里执行用户会话。 ([源代码](https://github.com/engity-com/bifroest)) `Apache-2.0` `Go/Docker`
- [Guacamole](https://guacamole.apache.org) - 支持标准协议（如 VNC 和 RDP）的无客户端远程桌面网关。 ([源代码](https://github.com/apache/guacamole-server)) `Apache-2.0` `Java/C`
- [MeshCentral](https://meshcentral.com/) - 运行自己的 Web 服务器，远程管理和控制本地网络或互联网上的任意计算机。 ([源代码](https://github.com/Ylianst/MeshCentral)) `Apache-2.0` `Node.js/JavaScript/HTML`
- [ShellHub](https://www.shellhub.io) - 现代化 SSH 服务器，可通过命令行（任意 SSH 客户端）或基于 Web 的界面远程访问 Linux 设备（sshd 的替代方案）。 ([源代码](https://github.com/shellhub-io/shellhub)) `Apache-2.0` `Docker`
- [Sshwifty](https://github.com/nirui/sshwifty) - Sshwifty是为Web而制作的SSH和Telnet连接器。 ([演示](https://sshwifty-demo.nirui.org)) `AGPL-3.0` `Go/Docker`
- [Termix](https://docs.termix.site/) - 无需客户端的 Web 服务器管理平台，支持 SSH 终端、隧道和文件编辑。 ([源代码](https://github.com/Termix-SSH/Termix)) `Apache-2.0` `Docker`
- [Warpgate](https://github.com/warp-tech/warpgate) - 智能的SSH和HTTPS堡垒，可与任何SSH客户端一起使用。 `Apache-2.0` `Rust/Docker`


### 通信 - IRC

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat)通信软件。

- [Ergo](https://ergo.chat/) - 用Go编写的现代IRCv3服务器，结合了ircd、服务框架和弹幕的功能。 ([源代码](https://github.com/ergochat/ergo)) `MIT` `Go/Docker`
- [Glowing Bear](https://github.com/glowing-bear/glowing-bear) - WeeChat的Web前端。 ([演示](https://www.glowing-bear.org)) `GPL-3.0` `Node.js`
- [InspIRCd](https://www.inspircd.org/) - 用于Linux、BSD、Windows和macOS的用C++编写的模块化IRC服务器。 ([源代码](https://github.com/inspircd/inspircd)) `GPL-2.0` `C++/Docker`
- [Kiwi IRC](https://kiwiirc.com/) - 支持主题的响应式 Web IRC 客户端。 ([演示](https://kiwiirc.com/nextclient/), [源代码](https://github.com/kiwiirc/kiwiirc)) `Apache-2.0` `Node.js`
- [ngircd](https://ngircd.barton.de/) - 适用于小型或私有网络的便携轻量级互联网中继聊天 (IRC) 服务器。 ([源代码](https://github.com/ngircd/ngircd)) `GPL-2.0` `C/deb`
- [Quassel IRC](https://quassel-irc.org/) - 分布式IRC客户端，意味着一个（或多个）客户端可以连接到和从一个中央核心分离。 ([源代码](https://github.com/quassel/quassel)) `GPL-2.0` `C++`
- [Robust IRC](https://robustirc.net/) - 无网络分裂的 IRC。基于 RobustSession 协议的分布式 IRC 服务器。 ([源代码](https://github.com/robustirc/robustirc)) `BSD-3-Clause` `Go`
- [The Lounge](https://thelounge.chat/) - 自托管的 Web IRC 客户端。 ([演示](https://demo.thelounge.chat/), [源代码](https://github.com/thelounge/thelounge)) `MIT` `Node.js/Docker`
- [UnrealIRCd](https://www.unrealircd.org/) - 一款模块化、先进且高度可配置的用C语言编写的IRC服务器，适用于Linux、BSD、Windows和macOS。 ([源代码](https://github.com/unrealircd/unrealircd)) `GPL-2.0` `C`
- [WeeChat](https://weechat.org/) - 快速、轻量且可扩展的聊天客户端。 ([源代码](https://github.com/weechat/weechat)) `GPL-3.0` `C/Docker/deb`
- [ZNC](https://wiki.znc.in/ZNC) - 先进的IRC代理服务器。 ([源代码](https://github.com/znc/znc)) `Apache-2.0` `C++/deb`


### 通信 - SIP

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[SIP](https://en.wikipedia.org/wiki/Session_Initiation_Protocol)/[IPBX](https://en.wikipedia.org/wiki/IP_PBX)电话软件。

- [Asterisk](https://www.asterisk.org/) - 易于使用但先进的 IP PBX 系统、VoIP 网关和会议服务器。 ([源代码](https://github.com/asterisk/asterisk)) `GPL-2.0` `C/deb`
- [Flexisip](https://www.linphone.org/en/flexisip-sip-server/) - 完整、模块化且可扩展的 SIP 服务器，包含推送网关，可在需要推送通知以便在应用未处于前台时接收信息的移动设备平台上，传递 SIP 来电或文本消息。 ([源代码](https://github.com/BelledonneCommunications/flexisip)) `AGPL-3.0` `C/Docker`
- [FreePBX](https://www.freepbx.org) - 基于Web的开源图形用户界面，用于控制和管理Asterisk。 ([源代码](https://git.freepbx.org/projects/FREEPBX)) `GPL-2.0` `PHP`
- [FreeSWITCH](https://freeswitch.org/) - 可扩展的开源跨平台电话平台。 ([源代码](https://github.com/signalwire/freeswitch)) `MPL-2.0` `C`
- [FusionPBX](https://www.fusionpbx.com/) - 基于Web的多平台语音交换机 FreeSWITCH 的管理界面。 ([源代码](https://github.com/fusionpbx/fusionpbx)) `MPL-1.1` `PHP`
- [Kamailio](https://www.kamailio.org/w/) - 模块化的SIP服务器（注册/代理/路由器等）。 ([源代码](https://github.com/kamailio/kamailio)) `GPL-2.0` `C/deb`
- [openSIPS](https://opensips.org/) - 用于语音、视频、即时消息、在线状态及其他 SIP 扩展的 SIP 代理/服务器。 ([源代码](https://github.com/OpenSIPS/opensips)) `GPL-2.0` `C`
- [Routr](https://routr.io) - 轻量级 SIP 代理、位置服务器和注册器，适用于可靠且可扩展的 SIP 基础设施。 ([源代码](https://github.com/fonoster/routr)) `MIT` `Docker/K8S`
- [SIP3](https://sip3.io/) - VoIP故障排除和监控平台。 ([演示](https://demo.sip3.io), [源代码](https://github.com/sip3io/)) `Apache-2.0` `Java`
- [SIPCAPTURE Homer](https://www.sipcapture.org/) - 用于故障排除和监控VoIP通话的工具。 ([源代码](https://github.com/sipcapture/homer)) `AGPL-3.0` `Node.js/Go/Docker`
- [Wazo](https://wazo-platform.org/) - 在Asterisk之上构建的功能齐全的IPBX解决方案，具有集成的Web管理界面和RESTful API。 ([源代码](https://github.com/wazo-platform)) `GPL-3.0` `Python`
- [Yeti-Switch](https://yeti-switch.org/) - 集成计费和路由引擎以及REST API的中继类4软交换（SBC）。 ([演示](https://demo.yeti-switch.org/), [源代码](https://github.com/yeti-switch)) `GPL-2.0` `C++/Ruby`


### 通信 - XMPP - Web 客户端

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[可扩展消息和出席协议](https://en.wikipedia.org/wiki/XMPP) Web客户端/界面。

- [Converse.js](https://conversejs.org/) - 在浏览器中的 XMPP 聊天客户端。 ([源代码](https://github.com/conversejs/converse.js)) `MPL-2.0` `JavaScript`
- [Libervia](https://repos.goffi.org/libervia-web) - Salut à Toi的Web前端。 `AGPL-3.0` `Python`
- [Salut à Toi](https://www.salut-a-toi.org/) - 多用途、多前端、自由且分散的通讯工具。 ([源代码](https://repos.goffi.org/libervia-backend)) `AGPL-3.0` `Python`


### 通信 - XMPP - 服务器

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[可扩展消息和出席协议](https://en.wikipedia.org/wiki/XMPP)服务器。

- [ejabberd](https://www.ejabberd.im/) - XMPP即时消息服务器。 ([源代码](https://github.com/processone/ejabberd)) `GPL-2.0` `Erlang/Docker`
- [MongooseIM](https://www.erlang-solutions.com/products/mongooseim.html) - 移动消息平台，注重性能和可扩展性。 ([源代码](https://github.com/esl/MongooseIM)) `GPL-2.0` `Erlang/Docker/K8S`
- [Openfire](https://www.igniterealtime.org/projects/openfire/) - 实时协作（RTC）服务器。 ([源代码](https://github.com/igniterealtime/Openfire)) `Apache-2.0` `Java`
- [Prosody IM](https://prosody.im/) - 功能丰富且易于配置的XMPP服务器。 ([源代码](https://hg.prosody.im/)) `MIT` `Lua`
- [Snikket](https://snikket.org/) - 一体化的Docker化简易XMPP解决方案，包括Web管理和客户端。 ([源代码](https://github.com/snikket-im/snikket-server), [客户端](https://snikket.org/app/)) `Apache-2.0` `Docker`
- [Tigase](https://tigase.net/xmpp-server) - Java 中的 XMPP 服务器实现。 ([源代码](https://github.com/tigase/tigase-server)) `GPL-3.0` `Java`


### 通信 - 定制通信系统

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[通信软件](https://en.wikipedia.org/wiki/Communication_software) 用于提供对系统的远程访问，以及在不同计算机或用户之间以文本、音频和/或视频格式交换文件和消息，使用其自定义协议。

- [AnyCable](https://anycable.io/) - 实时服务器，支持通过 WebSockets、服务器推送事件（Server-sent events）等实现可靠的双向通信。 ([演示](https://demo.anycable.io), [源代码](https://github.com/anycable/anycable)) `MIT` `Go/Docker`
- [Apprise](https://github.com/caronc/apprise) - Apprise 允许您向几乎所有我们今天可以使用的最流行的通知服务发送通知，如：Telegram、Discord、Slack、Amazon SNS、Gotify 等。 `MIT` `Python/Docker/deb`
- [Centrifugo](https://centrifugal.dev/) - 语言无关的实时消息（Websocket或SockJS）服务器。 ([演示](https://github.com/centrifugal/centrifugo#demo), [源代码](https://github.com/centrifugal/centrifugo)) `MIT` `Go/Docker/K8S`
- [Chitchatter](https://chitchatter.im/) - 一个点对点的聊天应用，无需服务器，去中心化且消息短暂。 ([源代码](https://github.com/jeremyckahn/chitchatter)) `GPL-2.0` `Node.js`
- [Conduit](https://conduit.rs/) - 由Matrix支持的简单、快速且可靠的聊天服务器。 ([源代码](https://gitlab.com/famedly/conduit)) `Apache-2.0` `Rust`
- [Continuwuity](https://continuwuity.org/) - 社区驱动的 Matrix 家庭服务器，专注于用户体验和新功能（conduwuit 的延续，Conduit 的分支）。 ([源代码](https://forgejo.ellis.link/continuwuation/continuwuity)) `Apache-2.0` `Rust/Docker/K8S/deb`
- [Databag](https://github.com/balzack/databag) - 面向 Web、iOS 和 Android 的联合、端到端加密的消息服务，支持文本、照片、视频以及 WebRTC 视频和音频通话。 ([演示](https://databag.coredb.org/#/create)) `Apache-2.0` `Docker`
- [Element](https://element.io) - 用于Web、iOS和Android的功能齐全的Matrix客户端。 ([源代码](https://github.com/element-hq/element-web)) `Apache-2.0` `Node.js`
- [GlobaLeaks](https://www.globaleaks.org/) - 一个举报软件，使任何人都能轻松设置和维护一个安全的报告平台。 ([演示](https://demo.globaleaks.org), [源代码](https://github.com/globaleaks/globaleaks-whistleblowing-software)) `AGPL-3.0` `Python/deb/Docker`
- [GNUnet](https://gnunet.org/) - 用于去中心化、点对点网络的软件框架。 ([源代码](https://gnunet.org/git/)) `GPL-3.0` `C`
- [Gotify](https://gotify.net/) - 带有 Android 和 CLI 客户端的通知服务器（PushBullet 的替代品）。 ([源代码](https://github.com/gotify/server), [客户端](https://github.com/gotify/android)) `MIT` `Go/Docker`
- [Hyphanet](https://hyphanet.org/) - 匿名分享文件，浏览和发布_freesites_（仅通过Hyphanet访问的网站）并在论坛上聊天。 ([源代码](https://github.com/hyphanet/fred)) `GPL-2.0` `Java`
- [Jami](https://jami.net/) - 通用通信平台，保护用户的隐私和自由。 ([源代码](https://git.jami.net/savoirfairelinux?sort=latest_activity_desc&filter=jami)) `GPL-3.0` `C++`
- [Live Helper Chat](https://livehelperchat.com/) - 用于网站的实时支持聊天。 ([源代码](https://github.com/LiveHelperChat/livehelperchat)) `Apache-2.0` `PHP`
- [Mumble](https://wiki.mumble.info/wiki/Main_Page) - 低延迟、高质量的语音/文本聊天软件。 ([源代码](https://github.com/mumble-voip/mumble), [客户端](https://wiki.mumble.info/wiki/3rd_Party_Applications)) `BSD-3-Clause` `C++/deb`
- [Notifo](https://github.com/notifo-io/notifo) - 多通道通知服务器，支持电子邮件、移动推送、Web推送、短信、消息和JavaScript插件。 `MIT` `C#`
- [Novu](https://novu.co/) - 面向开发者的通知基础设施。 ([源代码](https://github.com/novuhq/novu/)) `MIT` `Docker/Node.js`
- [ntfy](https://ntfy.sh/) - 使用HTTP PUT/POST向手机或桌面推送通知，具有Android应用程序、命令行界面和Web应用程序，类似于Pushover和Gotify。 ([演示](https://ntfy.sh/app), [源代码](https://github.com/binwiederhier/ntfy), [客户端](https://github.com/binwiederhier/ntfy-android)) `Apache-2.0/GPL-2.0` `Go/Docker/K8S`
- [One Time Secret](https://docs.onetimesecret.com) - 通过仅可查看一次的自毁链接安全地分享敏感信息。 ([演示](https://onetimesecret.com), [源代码](https://github.com/onetimesecret/onetimesecret)) `MIT` `Docker/Ruby/Node.js`
- [OTS](https://ots.fyi/) - 一次性秘密分享平台，使用浏览器中的对称256位AES加密。 ([源代码](https://github.com/Luzifer/ots)) `Apache-2.0` `Go`
- [PushBits](https://github.com/pushbits/server) - 用于通过 Matrix 转发推送通知的通知服务器，类似于 PushBullet 和 Gotify。 `ISC` `Go`
- [RetroShare](https://retroshare.cc) - 安全而去中心化的通信系统。提供去中心化聊天、论坛、消息传递、文件传输等功能。 ([源代码](https://github.com/RetroShare/RetroShare)) `GPL-2.0` `C++`
- [Rocket.Chat](https://rocket.chat/) - 以数据保护为首要的通信平台（Gitter.im 和 Slack 的替代方案）。 ([源代码](https://github.com/RocketChat/Rocket.Chat)) `MIT` `Node.js/Docker/K8S`
- [SAMA](https://samacloud.io) - 下一代自托管聊天服务器和客户端。 ([演示](https://app.samacloud.io/demo), [源代码](https://github.com/SAMA-Communications/sama-server), [客户端](https://github.com/SAMA-Communications/sama-client)) `GPL-3.0` `Node.js/Docker`
- [Screego](https://screego.net) - Screego 是一个简单的工具，可以通过 Web 浏览器快速分享您的屏幕给一个或多个人。 ([演示](https://app.screego.net/), [源代码](https://github.com/screego/server)) `GPL-3.0` `Docker/Go`
- [Shhh](https://github.com/smallwat3r/shhh) - 将秘密信息从电子邮件或聊天记录中保密，使用带有密码和过期日期的安全链接进行共享。 `MIT` `Python`
- [SimpleX Chat](https://github.com/simplex-chat/simplex-chat) - 最私密和安全的聊天和应用程序平台 - 现在支持双向棘轮端对端加密。 `AGPL-3.0` `Haskell`
- [Spectrum 2](https://spectrum.im/) - Spectrum 2是一个开源的即时通讯传输工具。它允许用户即使在使用不同的即时通讯网络时也能进行聊天。 ([源代码](https://github.com/SpectrumIM/spectrum2)) `GPL-3.0` `C++`
- [Stoat](https://stoat.chat/) - 以用户为中心、采用现代 Web 技术构建的聊天平台。 ([源代码](https://github.com/stoatchat/self-hosted)) `AGPL-3.0/MIT` `Rust`
- [Synapse](https://element-hq.github.io/synapse/latest/index.html) - 用于 [Matrix](https://matrix.org/) 的服务器，Matrix 是一种用于分散式持久通信的开放标准。 ([源代码](https://github.com/element-hq/synapse)) `Apache-2.0` `Python/deb`
- [Tiledesk](https://tiledesk.com) - 从潜在客户生成到售后的一体化客户参与平台，从 WhatsApp 到您的网站。具有全渠道实时客服和由 AI 驱动的聊天机器人（可替代 Intercom、Zendesk、Tawk.to 和 Tidio）。 ([源代码](https://github.com/Tiledesk/tiledesk)) `MIT` `Docker/K8S`
- [Tinode](https://github.com/tinode) - 即时通讯平台。后端使用 Go 编写。客户端包括：Swift iOS、Java Android、JS Web 应用、可脚本化命令行；还包括聊天机器人。 ([演示](https://sandbox.tinode.co/), [源代码](https://github.com/tinode/chat), [客户端](https://github.com/tinode/webapp)) `GPL-3.0` `Go`
- [Tox](https://tox.chat/) - 分布式、安全的即时通讯应用，具备音频和视频聊天功能。 ([源代码](https://github.com/TokTok/c-toxcore)) `GPL-3.0` `C`
- [Tuwunel](https://tuwunel.chat) - 高性能、功能丰富的 Matrix 聊天服务器，是 conduwuit 的继任者（Conduit 的分支）。 ([演示](https://try.tuwunel.chat/), [源代码](https://github.com/matrix-construct/tuwunel)) `Apache-2.0` `deb/Docker/Nix/Rust`
- [Typebot](https://typebot.io) - 对话式应用构建器（Typeform 和 Landbot 的替代品）。 ([源代码](https://github.com/baptisteArno/typebot.io)) `AGPL-3.0` `Docker`
- [WBO](https://github.com/lovasoa/whitebophir) - 实时协作的Web白板，可用于图表、绘图和笔记。 ([演示](https://wbo.ophir.dev/)) `AGPL-3.0` `Node.js/Docker`
- [Zulip](https://zulip.org) - Zulip是一款功能强大的开源群组聊天应用。 ([源代码](https://github.com/zulip/zulip)) `Apache-2.0` `Python`


### 通信 - 电子邮件 - Web 邮件客户端

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[Webmail](https://en.wikipedia.org/wiki/Webmail)客户端。

- [Cypht](https://cypht.org) - 用于您的电子邮件帐户的Feed阅读器。 ([源代码](https://github.com/cypht-org/cypht)) `LGPL-2.1` `PHP`
- [Roundcube](https://roundcube.net) - 具有类似应用程序界面的基于浏览器的 IMAP 客户端。 ([源代码](https://github.com/roundcube/roundcubemail)) `GPL-3.0` `PHP/deb`
- [SnappyMail](https://github.com/the-djmaze/snappymail) - 简单、现代、轻量且快速的基于Web的电子邮件客户端（RainLoop的分支）。 ([演示](https://github.com/the-djmaze/snappymail), [客户端](https://github.com/the-djmaze/snappymail)) `AGPL-3.0` `PHP`
- [SquirrelMail](https://squirrelmail.org) - 另一个基于浏览器的IMAP客户端。 ([源代码](https://sourceforge.net/p/squirrelmail/code/HEAD/tree/)) `GPL-2.0` `PHP`


### 通信 - 电子邮件 - 完整解决方案

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

简化[电子邮件](https://en.wikipedia.org/wiki/Email)服务器的部署，例如适用于经验不足或急躁的管理员。

- [AnonAddy](https://addy.io/) - 用于创建别名的电子邮件转发服务。 ([源代码](https://github.com/anonaddy/anonaddy)) `MIT` `PHP/Docker`
- [b1gMail](https://www.b1gmail.eu) - 完整的电子邮件解决方案，可在任何具有 PHP 和 MariaDB 的网络空间上运行。它支持 POP3 通配符邮箱，并且如果您运行自己的服务器，还可以与 Postfix 或 b1gMailServer 集成。 ([源代码](https://codeberg.org/b1gMail/b1gMail), [客户端](https://www.b1gmail.eu/en/start/addon-b1gmailserver/)) `GPL-2.0` `PHP`
- [DebOps](https://docs.debops.org/) - 将基于 Debian 的数据中心装在一个盒子里。一组通用的 Ansible 角色，可用于管理 Debian 或 Ubuntu 主机。 ([源代码](https://github.com/debops/debops)) `GPL-3.0` `Ansible/Python`
- [docker-mailserver](https://docker-mailserver.github.io/docker-mailserver/edge/) - 在容器中运行的生产就绪的全栈但简单的邮件服务器（SMTP、IMAP、LDAP、Antispam、Antivirus等）。仅配置文件，没有 SQL 数据库。 ([源代码](https://github.com/docker-mailserver/docker-mailserver)) `MIT` `Docker`
- [Dovel](https://github.com/mildred/dovel) - 根据简单的配置文件发送和接收电子邮件的 SMTP 服务器，可选择提供用于浏览电子邮件的 Web 界面。 `LGPL-3.0` `Go`
- [Inboxen](https://inboxen.org) - 让你拥有无限数量的唯一收件箱。 ([源代码](https://codeberg.org/Inboxen/Inboxen)) `GPL-3.0` `Python`
- [iRedMail](https://www.iredmail.org/) - 基于Postfix和Dovecot的功能齐全的邮件服务器解决方案。 ([源代码](https://github.com/iredmail/iRedMail)) `GPL-3.0` `Shell`
- [Maddy Mail Server](https://maddy.email/) - 一体化邮件服务器，实现了 SMTP（MTA 和 MX）与 IMAP 协议。用单一守护进程替代 Postfix、Dovecot、OpenDKIM、OpenSPF 和 OpenDMARC。 ([源代码](https://github.com/foxcpp/maddy)) `GPL-3.0` `Go`
- [Mail-in-a-Box](https://mailinabox.email/) - 通过一个命令将任何Ubuntu服务器转变为功能齐全的邮件服务器。 ([源代码](https://github.com/mail-in-a-box/mailinabox)) `CC0-1.0` `Shell`
- [Mailcow](https://mailcow.email/) - 基于Dovecot、Postfix和其他开源软件的邮件服务器套件，提供现代化的Web界面进行管理。 ([源代码](https://github.com/mailcow/mailcow-dockerized)) `GPL-3.0` `Docker/PHP`
- [Mailu](https://mailu.io/) - 简洁而功能完备的邮件服务器，以一组 Docker 镜像形式提供。 ([源代码](https://github.com/Mailu/Mailu)) `MIT` `Docker/Python`
- [Modoboa](https://modoboa.org/en/) - 邮件托管与管理平台，提供现代简洁的 Web 用户界面。 ([源代码](https://github.com/modoboa/modoboa)) `ISC` `Python`
- [Mox](https://www.xmox.nl/) - 完整的电子邮件解决方案，支持IMAP4、SMTP、SPF、DKIM、DMARC、MTA-STS、DANE和DNSSEC，基于声誉和内容的垃圾邮件过滤，国际化（IDNA），通过ACME和Let's Encrypt自动TLS，帐户自动配置和Webmail。 ([源代码](https://github.com/mjl-/mox)) `MIT` `Go`
- [Postal](https://docs.postalserver.io/) - 面向网站和 Web 服务器的完整且功能齐全的邮件服务器。 ([源代码](https://github.com/postalserver/postal)) `MIT` `Docker/Ruby`
- [Simple NixOS Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - 利用 Nix 生态系统的完整邮件服务器解决方案。 `GPL-3.0` `Nix`
- [SimpleLogin](https://simplelogin.io) - 开源电子邮件别名解决方案，用于保护您的电子邮件地址。附带浏览器扩展和移动应用程序。 ([源代码](https://github.com/simple-login/app)) `MIT` `Docker/Python`
- [Stalwart Mail Server](https://stalw.art) - 支持 JMAP、IMAP4 和 SMTP，具备丰富现代功能的一体化邮件服务器。 ([源代码](https://github.com/stalwartlabs/stalwart)) `AGPL-3.0` `Rust/Docker`
- [Wildduck](https://wildduck.email/) - 可伸缩的无单点故障IMAP/POP3邮件服务器。 ([源代码](https://github.com/zone-eu/wildduck)) `EUPL-1.2` `Node.js/Docker`


### 通信 - 电子邮件 - 邮件传输代理

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[邮件传输代理](https://en.wikipedia.org/wiki/Message_transfer_agent)（MTA） - [SMTP](https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol)服务器。

- [chasquid](https://blitiri.com.ar/p/chasquid/) - 专注于简单性、安全性和易操作性的SMTP（电子邮件）服务器。 ([源代码](https://blitiri.com.ar/git/r/chasquid/)) `Apache-2.0` `Go`
- [Courier MTA](https://www.courier-mta.org/) - 快速、可扩展的企业邮件/协作服务器，提供ESMTP、IMAP、POP3、Webmail、邮件列表、基本的基于Web的日历和调度服务。 ([源代码](https://www.courier-mta.org/repo.html)) `GPL-3.0` `C/deb`
- [DragonFly](https://github.com/corecode/dma) - 适用于家庭和办公室使用的小型MTA。适用于Linux和FreeBSD。 `BSD-3-Clause` `C`
- [EmailRelay](https://emailrelay.sourceforge.net/) - 一个小巧且易于配置的Windows和Linux SMTP和POP3服务器。 ([源代码](https://sourceforge.net/p/emailrelay/code/HEAD/tree/)) `GPL-3.0` `C++`
- [Exim](https://www.exim.org/) - 在剑桥大学开发的消息传输代理（MTA）。 ([源代码](https://git.exim.org/exim.git)) `GPL-3.0` `C/deb`
- [Haraka](https://haraka.github.io/) - 快速、高度可扩展且事件驱动的 SMTP 服务器。 ([源代码](https://github.com/haraka/Haraka)) `MIT` `Node.js`
- [OpenSMTPD](https://opensmtpd.org/) - 来自OpenBSD项目的安全SMTP服务器实现。 ([源代码](https://github.com/OpenSMTPD/OpenSMTPD/)) `ISC` `C/deb`
- [OpenTrashmail](https://github.com/HaschekSolutions/opentrashmail) - 一款完整的垃圾邮件解决方案，提供一个暴露SMTP服务器并具有用于管理接收的电子邮件的Web界面。支持多个和通配符域，完全基于文件（无需数据库）。包括RSS订阅和JSON API。 `Apache-2.0` `Python/PHP/Docker`
- [Postfix](http://www.postfix.org/) - 快速、易于管理且安全的Sendmail替代品。 `IPL-1.0` `C/deb`
- [Sendmail](https://www.proofpoint.com/us/products/email-protection/open-source-email-solution) - 消息传输代理（MTA）。 `Sendmail` `C/deb`


### 通信 - 电子邮件 - 邮件列表和通讯

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[邮件列表](https://en.wikipedia.org/wiki/Mailing_list)服务器和群发邮件软件 - 一条消息发送给多个接收者。

- [HyperKitty](https://wiki.list.org/HyperKitty) - 访问 GNU Mailman v3 存档。 ([演示](https://lists.mailman3.org/), [源代码](https://gitlab.com/mailman/hyperkitty)) `GPL-3.0` `Python`
- [Keila](https://www.keila.io) - 可靠且易于使用的新闻通讯工具（Mailchimp 和 Sendinblue 的替代品）。 ([演示](https://app.keila.io), [源代码](https://github.com/pentacent/keila)) `AGPL-3.0` `Docker`
- [Listmonk](https://listmonk.app/) - 高性能的自托管通讯和邮件列表管理器，带有现代化的仪表板。 ([演示](https://demo.listmonk.app/), [源代码](https://github.com/knadh/listmonk)) `AGPL-3.0` `Go/Docker`
- [Mailman](https://www.list.org/) - 管理电子邮件讨论组和电子通讯订阅列表。 ([源代码](https://gitlab.com/mailman/)) `GPL-3.0` `Python`
- [Mautic](https://www.mautic.org/) - 营销自动化软件（支持电子邮件、社交媒体等渠道）。 ([源代码](https://github.com/mautic/mautic)) `GPL-3.0` `PHP`
- [mlmmj](https://mlmmj.org/) - 轻松愉快的邮件列表管理工具。 ([源代码](https://codeberg.org/mlmmj/mlmmj)) `MIT` `C`
- [phpList](https://www.phplist.org) - 具有高级订阅者、退信和插件管理功能的新闻通讯和电子邮件营销工具。 ([源代码](https://github.com/phpList/phplist3)) `AGPL-3.0` `PHP`
- [Postorius](https://docs.mailman3.org/projects/postorius/en/latest/) - 用于访问GNU Mailman的Web用户界面。 ([源代码](https://gitlab.com/mailman/postorius/)) `GPL-3.0` `Python`
- [Schleuder](https://schleuder.nadir.org/) - 具有转发功能的 GPG 启用的邮件列表管理器。 ([源代码](https://0xacab.org/schleuder/schleuder/tree/master)) `GPL-3.0` `Ruby`
- [Sympa](https://www.sympa.community/) - 邮件列表管理器。 ([源代码](https://github.com/sympa-community/sympa)) `GPL-2.0` `Perl`


### 通信 - 电子邮件 - 邮件投递代理

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[邮件传送代理](https://en.wikipedia.org/wiki/Message_delivery_agent)（MDA） - [IMAP](https://en.wikipedia.org/wiki/Internet_Message_Access_Protocol)/[POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol)服务器软件。

- [Cyrus IMAP](https://www.cyrusimap.org/) - 电子邮件（IMAP/POP3）、联系人和日历服务器。 ([源代码](https://github.com/cyrusimap/cyrus-imapd)) `BSD-3-Clause-Attribution` `C`
- [DavMail](https://davmail.sourceforge.net/) `⚠` - POP/IMAP/SMTP/Caldav/Carddav/LDAP 交换网关，允许用户通过 Outlook Web Access 使用任何邮件或日历客户端连接 Exchange 服务器，无论是在互联网还是防火墙之后。 ([源代码](https://github.com/mguessan/davmail)) `GPL-2.0` `Java`
- [Dovecot](https://www.dovecot.org/) - 主要以安全性为重点编写的IMAP和POP3服务器。 ([源代码](https://github.com/dovecot/core)) `MIT/LGPL-2.1` `C/deb`


### 通信 - 社交网络和论坛

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[社交网络](https://en.wikipedia.org/wiki/Social_networking_service)和[论坛](https://en.wikipedia.org/wiki/Internet_forum)软件。

- [Akkoma](https://akkoma.social/) - 基于 Mastodon、GNU social 和 ActivityPub 兼容性的联邦微博服务器。 ([源代码](https://akkoma.dev/AkkomaGang/akkoma)) `AGPL-3.0` `Elixir/Docker`
- [Answer](https://answer.apache.org) - 基于知识的社区软件。您可以用它快速搭建产品技术支持、客户支持、用户交流等问答社区。 ([源代码](https://github.com/apache/answer)) `Apache-2.0` `Docker/Go`
- [Artalk](https://artalk.js.org/) - 用 Golang 构建的评论系统，为您的网站提供轻量且高度可定制的评论解决方案。 ([源代码](https://github.com/ArtalkJS/Artalk)) `MIT` `Go/Docker`
- [AsmBB](https://board.asm32.info) - 快速的、基于 SQLite 的论坛引擎，使用汇编语言编写。 ([源代码](https://asm32.info/fossil/asmbb/index)) `EUPL-1.2` `Assembly`
- [BuddyPress](https://buddypress.org/about/) - 强大的插件，通过用户配置文件、活动流、用户组等社交网络功能，将您的 WordPress.org 强大的站点超越博客。 ([源代码](https://github.com/buddypress/BuddyPress)) `GPL-2.0` `PHP`
- [Chirpy](https://chirpy.dev) - 隐私友好且可定制的 Disqus（评论系统）替代品。 ([演示](https://chirpy.dev/play), [源代码](https://github.com/devrsi0n/chirpy)) `AGPL-3.0` `Docker/Node.js`
- [Coral](https://coralproject.net/) - Vox Media提供的更好的评论体验。 ([源代码](https://github.com/coralproject/talk)) `Apache-2.0` `Docker/Node.js`
- [diaspora*](https://diasporafoundation.org/) - 分布式社交网络服务器。 ([源代码](https://github.com/diaspora/diaspora)) `AGPL-3.0` `Ruby`
- [Discourse](https://www.discourse.org/) - 基于Ruby和JS的高级论坛/社区解决方案。 ([演示](https://try.discourse.org/), [源代码](https://github.com/discourse/discourse)) `GPL-2.0` `Docker`
- [Elgg](https://elgg.org/) - 强大的开源社交网络引擎。 ([源代码](https://github.com/Elgg/Elgg)) `GPL-2.0` `PHP`
- [Enigma 1/2 BBS](https://nuskooler.github.io/enigma-bbs/) - Enigma 1/2是一个现代的、跨平台的BBS引擎，支持无限数量的“呼叫者”并提供对传统的DOS门户游戏的支持。 ([源代码](https://github.com/NuSkooler/enigma-bbs)) `BSD-2-Clause` `Shell/Docker/Node.js`
- [Flarum](https://flarum.org) - 愉悦简单的论坛。Flarum 是下一代论坛软件，让在线讨论再次变得有趣。 ([源代码](https://github.com/flarum/flarum)) `MIT` `PHP`
- [Friendica](https://friendi.ca/) - 社交通讯服务器。 ([源代码](https://github.com/friendica/friendica)) `AGPL-3.0` `PHP`
- [GoToSocial](https://docs.gotosocial.org/en/latest/) - 基于 ActivityPub 协议的联邦社交网络服务器，实现了 Mastodon 客户端 API。 ([源代码](https://codeberg.org/superseriousbusiness/gotosocial)) `AGPL-3.0` `Docker/Go`
- [Hatsu](https://hatsu.cli.rs/) - 为您的静态站点代表与 Fediverse 交互的桥梁。 ([源代码](https://github.com/importantimport/hatsu)) `AGPL-3.0` `Docker/Rust`
- [Hubzilla](https://hubzilla.org) - 分布式身份、隐私、发布、共享、云存储和通讯/社交平台。 ([源代码](https://framagit.org/hubzilla/core)) `MIT` `PHP`
- [HumHub](https://www.humhub.org/) - 用于私人社交网络的灵活工具包。 ([源代码](https://github.com/humhub/humhub)) `AGPL-3.0` `PHP`
- [Iceshrimp.NET](https://iceshrimp.net) - 基于 ActivityPub 协议通信的联邦式微博客服务器。 ([源代码](https://iceshrimp.dev/iceshrimp/iceshrimp.net)) `EUPL-1.2` `.NET/C#/Docker`
- [Isso](https://isso-comments.de/) - 用Python和JavaScript编写的轻量级评论服务器。旨在成为Disqus的即插即用替代方案。 ([源代码](https://github.com/isso-comments/isso)) `MIT` `Python/Docker`
- [Lemmy](https://join-lemmy.org/) - 联邦宇宙的链接聚合器（Reddit 的替代品）。 ([源代码](https://github.com/LemmyNet/lemmy)) `AGPL-3.0` `Docker/Rust`
- [Loomio](https://www.loomio.org/) - 协作决策工具，让每个人都能轻松参与与自己相关的决策。 ([源代码](https://github.com/loomio/loomio)) `AGPL-3.0` `Docker`
- [Mastodon](https://joinmastodon.org/) - 联合式微博服务。 ([源代码](https://github.com/mastodon/mastodon), [客户端](https://github.com/hyperupcall/awesome-mastodon)) `AGPL-3.0` `Ruby`
- [Misago](https://misago-project.org/) - 功能完备的现代论坛应用，快速、可扩展且响应灵敏。 ([源代码](https://github.com/rafalp/Misago)) `GPL-2.0` `Docker`
- [Misskey](https://misskey.io/) - 去中心化的类应用微博服务器/社交网络服务，适用于 Fediverse，使用 ActivityPub 协议，类似于 GNU social 和 Mastodon。 ([源代码](https://github.com/misskey-dev/misskey)) `AGPL-3.0` `Node.js/Docker`
- [Movim](https://movim.eu/) - 现代化的联邦社交网络，基于 XMPP，具有完整的群聊、订阅和微博功能。 ([源代码](https://github.com/movim/movim)) `AGPL-3.0` `PHP/Docker`
- [MyBB](https://mybb.com/) - 免费、可扩展的论坛软件包。 ([源代码](https://github.com/mybb/mybb)) `LGPL-3.0` `PHP`
- [NodeBB](https://nodebb.org/) - 面向现代网络构建的论坛软件。 ([演示](https://try.nodebb.org/), [源代码](https://github.com/NodeBB/NodeBB)) `GPL-3.0` `Node.js/Docker`
- [OSSN](https://www.opensource-socialnetwork.org/) - 社交网络软件，允许您创建社交网络网站，帮助成员与拥有相似职业或个人兴趣的人建立社交关系。 ([源代码](https://github.com/opensource-socialnetwork/opensource-socialnetwork)) `CAL-1.0` `PHP`
- [phpBB](https://www.phpbb.com/) - 一款平面论坛公告板软件解决方案，可用于与一群人保持联系，也可以为整个网站提供支持。 ([源代码](https://github.com/phpbb/phpbb)) `GPL-2.0` `PHP`
- [PieFed](https://join.piefed.social) - 联邦宇宙的链接聚合器/Reddit 克隆（Reddit 的替代品）。 ([演示](https://piefed.social), [源代码](https://codeberg.org/rimu/pyfedi)) `AGPL-3.0` `Python/Docker`
- [PixelFed](https://pixelfed.social) - 由 ActivityPub 联邦协议驱动的伦理化照片分享平台（Instagram 的替代方案）。 ([源代码](https://github.com/pixelfed/pixelfed)) `AGPL-3.0` `PHP`
- [Pleroma](https://pleroma.social) - 联合式的微博服务器，兼容 Mastodon、GNU social 和 ActivityPub。 ([源代码](https://git.pleroma.social/pleroma/pleroma)) `AGPL-3.0` `Elixir`
- [qpixel](https://codidact.com/) - 基于问答的社区知识共享软件。 ([源代码](https://github.com/codidact/qpixel)) `AGPL-3.0` `Ruby`
- [Redlib](https://github.com/redlib-org/redlib) `⚠` - Reddit 的替代性私人前端，源自 Libreddit。 `AGPL-3.0` `Rust`
- [remark42](https://remark42.com/) - 轻量且简洁的评论引擎，不追踪用户。可嵌入博客、文章或任何需要读者评论的地方。 ([演示](https://remark42.com/demo/), [源代码](https://github.com/umputun/remark42)) `MIT` `Docker/Go`
- [Scoold](https://scoold.com) - 一个 JAR 中的 Stack Overflow。一款具备全文搜索、SAML、LDAP 集成和社交登录支持的企业级问答平台。 ([演示](https://live.scoold.com), [源代码](https://github.com/Erudika/scoold)) `Apache-2.0` `Java/Docker/K8S`
- [Simple Machines Forum](https://www.simplemachines.org/) - 免费、专业级的软件包，可让您在几分钟内建立自己的在线社区。 ([源代码](https://github.com/SimpleMachines/SMF)) `BSD-3-Clause` `PHP`
- [Socialhome](https://socialhome.network) - 分布式和去中心化的个人资料构建器和社交网络引擎。 ([演示](https://socialhome.network/), [源代码](https://github.com/jaywink/socialhome)) `AGPL-3.0` `Docker/Python`
- [Talkyard](https://www.talkyard.io/) - 创建一个社区，让您的用户提出想法并得到问题的解答。并进行友好的开放式讨论和聊天（类似 Slack/StackOverflow/Discourse/Reddit/Disqus 的混合体）。 ([演示](https://www.talkyard.io/forum/latest), [源代码](https://github.com/debiki/talkyard)) `AGPL-3.0` `Docker/Scala`
- [yarn.social](https://yarn.social) - 自托管、类似Twitter™的分布式微日志平台。无广告、无追踪，您的内容，您的数据。 ([源代码](https://git.mills.io/yarnsocial/yarn)) `MIT` `Go`


### 通信 - 视频会议

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[视频/网络会议](https://en.wikipedia.org/wiki/Web_conferencing)工具和软件。

_相关: [会议管理](#会议管理)_

- [BigBlueButton](https://bigbluebutton.org/) - 支持实时共享音频、视频、幻灯片（带有白板控制）、聊天和屏幕。教师可以通过投票、表情符号和分组房间与远程学生互动。 ([源代码](https://github.com/bigbluebutton/bigbluebutton)) `LGPL-3.0` `Java`
- [Galene](https://galene.org/) - 易于部署且对服务器资源要求适中的视频会议服务器。 ([源代码](https://github.com/jech/galene)) `MIT` `Go`
- [Janus](https://janus.conf.meetecho.com/) - 通用、轻量级、极简的WebRTC服务器。 ([演示](https://janus.conf.meetecho.com/demos/), [源代码](https://github.com/meetecho/janus-gateway)) `GPL-3.0` `C`
- [Jitsi Meet](https://jitsi.org/Projects/JitsiMeet) - 使用 Jitsi Videobridge 提供高质量、可扩展视频会议的 WebRTC 应用程序。 ([演示](https://meet.jit.si), [源代码](https://github.com/jitsi/jitsi-meet)) `Apache-2.0` `Node.js/Docker/deb`
- [Jitsi Video Bridge](https://jitsi.org/Projects/JitsiVideobridge) - 兼容WebRTC的选择性转发单元（SFU），允许多用户视频通信。 ([源代码](https://github.com/jitsi/jitsi-videobridge)) `Apache-2.0` `Java/deb`
- [MiroTalk C2C](https://c2c.mirotalk.com) - 实时点对点视频通话和屏幕共享，端到端加密，可嵌入任何网站的简单 iframe 中。 ([源代码](https://github.com/miroslavpejic85/mirotalkc2c)) `AGPL-3.0` `Node.js/Docker`
- [MiroTalk P2P](https://p2p.mirotalk.com) - 简单、安全、快速的实时视频会议，支持高达 4K 和 60fps，兼容所有浏览器和平台。 ([演示](https://p2p.mirotalk.com/newcall), [源代码](https://github.com/miroslavpejic85/mirotalk)) `AGPL-3.0` `Node.js/Docker`
- [MiroTalk SFU](https://sfu.mirotalk.com) - 简单、安全、可扩展的实时视频会议，支持高达 4K，兼容所有浏览器和平台。 ([演示](https://sfu.mirotalk.com/newroom), [源代码](https://github.com/miroslavpejic85/mirotalksfu)) `AGPL-3.0` `Node.js/Docker`
- [plugNmeet](https://www.plugnmeet.org/) - 可扩展且高性能的网络会议系统。 ([演示](https://demo.plugnmeet.com/login.html), [源代码](https://github.com/mynaparrot/plugNmeet-server)) `MIT` `Docker/Go`


### 邮件客户端

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[邮件客户端](https://en.wikipedia.org/wiki/Email_client)，又称邮件阅读器或消息用户代理（MUA），是用于访问和管理用户电子邮件的计算机程序。

- [aerc](https://aerc-mail.org/) - 以纯文本和开发者功能为重点的终端邮件客户端。 ([源代码](https://git.sr.ht/~rjarry/aerc)) `MIT` `Go`
- [Claws Mail](http://www.claws-mail.org/) - 基于 GTK+ 的老牌邮件客户端（及新闻阅读器）。 ([源代码](https://git.claws-mail.org/?p=claws.git;a=tree)) `GPL-3.0` `C`
- [ImapSync](http://imapsync.lamiral.info/) - 简单的 IMAP 邮箱迁移工具，可将邮箱复制到其他服务器。 ([源代码](https://github.com/imapsync/imapsync)) `NLPL` `Perl`
- [Mutt](http://www.mutt.org/) - 小巧但功能强大的文本邮件客户端。 ([源代码](https://gitlab.com/muttmua/mutt)) `GPL-2.0` `C`
- [Sylpheed](https://sylpheed.sraoss.jp/en/) - Claws Mail 的前身，仍在开发的轻量级邮件客户端。 ([源代码](https://github.com/sylpheed-mail/sylpheed)) `GPL-2.0` `C`
- [Thunderbird](https://www.thunderbird.net/) - 免费、易于设置和自定义的邮件应用。 ([源代码](https://hg.mozilla.org/comm-central/file)) `MPL-2.0` `C/C++`


### 部署自动化

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

支持服务器部署的工具和脚本。

- [Capistrano](https://capistranorb.com/) - 通过 SSH（基于 rake）同时、顺序或滚动方式将应用部署到任意数量的机器。 ([源代码](https://github.com/capistrano/capistrano)) `MIT` `Ruby`
- [CloudSlang](https://www.cloudslang.io/) - 基于流程的编排工具，用于管理已部署应用，支持 Docker。 ([源代码](https://github.com/CloudSlang/score)) `Apache-2.0` `Java`
- [CloudStack](https://cloudstack.apache.org/) - 用于创建、管理和部署基础设施云服务的云计算软件。 ([源代码](https://github.com/apache/cloudstack)) `Apache-2.0` `Java/Python`
- [Cobbler](https://cobbler.github.io/) - Linux 安装服务器，可快速搭建网络安装环境。 ([源代码](https://github.com/cobbler/cobbler)) `GPL-2.0` `Python`
- [Fabric](https://www.fabfile.org/) - 用于简化通过 SSH 部署应用或系统管理任务的 Python 库和 CLI 工具。 ([源代码](https://github.com/fabric/fabric)) `BSD-2-Clause` `Python`
- [FaynoSync](https://faynosync.com) - 自托管动态更新服务器，支持统计功能和多种更新器，提供灵活的应用更新与数据洞察功能。 ([源代码](https://github.com/ku9nov/faynoSync)) `Apache-2.0` `Docker/Go`
- [Genesis](https://github.com/genesis-community/genesis) - 多环境 BOSH 部署的模板框架。 `MIT` `Perl`
- [munki](https://www.munki.org/munki/) - 基于 Web 服务器的软件包及元数据仓库，便于 macOS 管理员管理软件安装。 ([源代码](https://github.com/munki/munki)) `Apache-2.0` `Python`
- [Overcast](https://andrewchilds.github.io/overcast/) - 跨云服务商部署虚拟机，并通过 SSH 并行运行命令和脚本。 ([源代码](https://github.com/andrewchilds/overcast)) `MIT` `Node.js`


### 配置管理

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[配置管理（CM）](https://en.wikipedia.org/wiki/Configuration_management) 是一种系统工程流程，用于在产品整个生命周期内建立和维护其性能、功能和物理属性与其需求、设计和操作信息的一致性。

- [Ansible](https://www.ansible.com/) - 提供配置管理、应用部署等功能的自动化工具。 ([源代码](https://github.com/ansible/ansible)) `GPL-3.0` `Python`
- [CFEngine](https://cfengine.com/) - 用于大规模计算机系统自动配置和维护的配置管理系统。 ([源代码](https://github.com/cfengine/core)) `GPL-3.0` `C`
- [CINC](https://cinc.sh/) - Chef 的免费发行版，一款配置管理工具，使用纯 Ruby 领域特定语言（DSL）来编写系统配置"食谱"（recipes）。 ([源代码](https://gitlab.com/cinc-project/upstream/chef)) `Apache-2.0` `Ruby`
- [cloud-init](https://cloud-init.io/) - 自动化配置虚拟机、云实例或网络中机器的初始化工具。 ([源代码](https://github.com/canonical/cloud-init)) `GPL-3.0/Apache-2.0` `Python`
- [OpenVox](https://voxpupuli.org/openvox/) - Puppet 最后一个开源版本的社区分支，一款软件配置管理工具，内置专属的声明式语言用于描述系统配置。 ([源代码](https://github.com/OpenVoxProject/openvox)) `Apache-2.0` `Ruby/C`
- [Rudder](https://www.rudder.io/) - 基于 CFEngine 的可扩展动态配置管理系统，支持补丁、安全与合规。 ([源代码](https://github.com/Normation/rudder)) `GPL-3.0` `Scala`
- [Salt](https://docs.saltproject.io/) - 事件驱动的 IT 自动化、远程任务执行和配置管理软件。 ([源代码](https://github.com/saltstack/salt)) `Apache-2.0` `Python`


### 配置管理数据库

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

配置管理数据库（CMDB）软件。

- [Collins](https://tumblr.github.io/collins/) - Tumblr 的基础设施事实与知识源。 ([源代码](https://github.com/tumblr/collins)) `Apache-2.0` `Docker/Scala`
- [iTop](https://www.combodo.com/itop) - 完整的 ITIL Web 服务管理工具。 ([源代码](https://sourceforge.net/projects/itop/files/)) `AGPL-3.0` `PHP`
- [netbox](https://netbox.dev/) - IP 地址管理（IPAM）和数据中心基础设施管理（DCIM）工具。 ([演示](https://demo.netbox.dev/), [源代码](https://github.com/netbox-community/netbox)) `Apache-2.0` `Python`


### 队列

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[消息队列](https://en.wikipedia.org/wiki/Message_queue)和[消息中间件](https://en.wikipedia.org/wiki/Message_broker)软件，通常用于进程间通信（IPC）或同一进程内线程间通信。

- [ActiveMQ](https://activemq.apache.org/) - Java 消息中间件。 ([源代码](https://github.com/apache/activemq)) `Apache-2.0` `Java`
- [BeanstalkD](https://beanstalkd.github.io/) - 简单快速的工作队列。 ([源代码](https://github.com/beanstalkd/beanstalkd)) `MIT` `C`
- [Gearman](http://gearman.org/) - 快速多语言队列/作业处理平台。 ([源代码](https://github.com/gearman/gearmand)) `BSD-3-Clause` `C++`
- [NSQ](https://nsq.io/) - 实时分布式消息平台。 ([源代码](https://github.com/nsqio/nsq)) `MPL-2.0` `Go`
- [ZeroMQ](https://zeromq.org/) - 轻量级队列系统。 ([源代码](https://github.com/zeromq)) `GPL-3.0` `C++`


### 静态网站生成器

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

[静态网站生成器](https://en.wikipedia.org/wiki/Web_template_system#Static_site_generators)根据原始数据、纯文本文件和一组模板生成完整的静态 HTML 网站。

**请访问 [staticsitegenerators.bevry.me](https://staticsitegenerators.bevry.me), [staticgen.com](https://www.staticgen.com)**

_相关: [博客平台](#博客平台), [相册](#相册), [内容管理系统（CMS）](#内容管理系统（cms）)_



### 预订和日程安排

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

活动调度、预订和会议管理软件。

_相关: [投票和事件](#投票和事件), [协同办公](#协同办公)_

- [Alf.io](https://alf.io/) - 门票预订系统。 ([演示](https://demo.alf.io/authentication), [源代码](https://github.com/alfio-event/alf.io)) `GPL-3.0` `Java`
- [Cal.diy](https://cal.diy/) - 在线预约调度系统。 ([演示](https://app.cal.com/bailey), [源代码](https://github.com/calcom/cal.diy)) `MIT` `Node.js`
- [Easy!Appointments](https://easyappointments.org/) - 允许您的客户通过网络与您预约。 ([演示](https://demo.easyappointments.org/), [源代码](https://github.com/alextselegidis/easyappointments)) `GPL-3.0` `PHP`
- [Hi.Events](https://hi.events) - 用于会议、音乐会等活动管理和票务的平台。提供可自定义的活动页面和可嵌入的票务小部件。 ([演示](https://demo.hi.events/event/1/dog-conf-2030), [源代码](https://github.com/HiEventsDev/hi.events)) `AGPL-3.0` `Docker`
- [LibreBooking](https://librebooking.readthedocs.io/) - 资源调度解决方案，为组织提供灵活、移动友好且可扩展的资源预订管理界面。 ([演示](https://librebooking-demo.fly.dev/), [源代码](https://github.com/LibreBooking/librebooking)) `GPL-3.0` `PHP/Docker`
- [QloApps](https://qloapps.com/) - 可定制且直观的基于 Web 的酒店预订系统和预订引擎。 ([演示](https://demo.qloapps.com/), [源代码](https://github.com/Qloapps/QloApps)) `OSL-3.0` `PHP/Node.js`
- [Rallly](https://rallly.co) - 创建投票以选择日期和时间（Doodle的替代品）。 ([演示](https://app.rallly.co), [源代码](https://github.com/lukevella/rallly)) `AGPL-3.0` `Node.js/Docker`
- [Seatsurfing](https://seatsurfing.app/) - 基于 Web 的应用程序，用于预订办公室的座位、桌子和房间。 ([源代码](https://github.com/seatsurfing/seatsurfing)) `GPL-3.0` `Docker`


### 食谱管理

**[`^        返回顶部        ^`](#Awesome-Selfhosted)**

用于管理[食谱](https://en.wikipedia.org/wiki/Recipe)的软件和工具。

- [Bar Assistant](https://barassistant.app/) - 管理您的家庭酒吧，添加原料、搜索鸡尾酒并创建自定义鸡尾酒配方。 ([演示](https://demo.barassistant.app/), [源代码](https://github.com/karlomikus/bar-assistant)) `MIT` `PHP/Docker`
- [CookCLI](https://cooklang.org) - 用于使用 Cooklang 食谱自动化膳食计划和购物的命令行工具，可编写 UNIX 工作流脚本，包括网络服务器。 ([源代码](https://github.com/cooklang/CookCLI)) `MIT` `Rust`
- [Fork Recipes](https://mikebgrep.github.io/forkapi/latest/clients/) - 用简单的方式管理你的美食菜谱。 ([源代码](https://github.com/mikebgrep/fork.recipes)) `BSD-3-Clause` `Docker`
- [ManageMeals](https://managemeals.com/) - 管理食谱，通过URL导入食谱并整理它们，没有广告或不必要的文字。 ([演示](https://demo.managemeals.com/), [源代码](https://github.com/managemeals/manage-meals-web)) `GPL-3.0` `Docker`
- [Mealie](https://nightly.mealie.io/) - 受Material Design启发的食谱管理器，具有分类和标签管理、购物清单、餐饮计划和站点定制功能。Mealie专注于简单的用户交互，以确保整个家庭都能使用该应用程序。 ([演示](https://demo.mealie.io), [源代码](https://github.com/mealie-recipes/mealie)) `MIT` `Python`
- [RecipeSage](https://github.com/julianpoy/recipesage) - 一个食谱保存器、餐饮计划组织者和购物清单管理器，可以直接从任何URL导入食谱。 ([演示](https://recipesage.com)) `AGPL-3.0` `Node.js`
- [Recipya](https://recipes.musicavis.ca) - 干净、简洁且强大的菜谱管理器，全家都能乐在其中。 ([演示](https://recipes.musicavis.ca/guide/login), [源代码](https://github.com/reaper47/recipya)) `GPL-3.0` `Docker/Go`
- [Specifically Clementines](https://davideshay.github.io/groceries/) - 食品购物应用（之前是Groceries），提供与多个用户/设备（Web/Android/iOS）的可靠同步、食谱和与Tandoor的集成。 ([源代码](https://github.com/davideshay/groceries)) `MIT` `Docker`
- [Tamari](https://tamariapp.com) - 食谱管理网络应用，内置食谱集合。按收藏和类别组织，创建购物清单并规划膳食。 ([演示](https://app.tamariapp.com), [源代码](https://github.com/alexbates/Tamari)) `GPL-3.0` `Docker/Python`
- [Vanilla Cookbook](https://vanilla-cookbook.readthedocs.io/en/) - 以极简体验为目标、底层设计复杂的食谱管理器。 ([源代码](https://github.com/jt196/vanilla-cookbook)) `GPL-3.0` `Docker/Node.js`
- [What To Cook?](https://github.com/kassner/whattocook) - 根据您家中现有的食材，获取今天要烹饪的食谱。 `AGPL-3.0` `Docker`


--------------------

## List of Licenses

**[`^        back to top        ^`](#Awesome-Selfhosted)**

- `0BSD` - [BSD Zero-Clause Licence](https://spdx.org/licenses/0BSD.html)
- `AAL` - [Attribution Assurance License](https://spdx.org/licenses/AAL.html)
- `AGPL-3.0` - [GNU Affero General Public License 3.0](https://spdx.org/licenses/AGPL-3.0.html)
- `Apache-2.0` - [Apache, Version 2.0](https://spdx.org/licenses/Apache-2.0.html)
- `APSL-2.0` - [Apple Public Source License, Version 2.0](https://spdx.org/licenses/APSL-2.0.html)
- `Artistic-2.0` - [Artistic License Version 2.0](https://spdx.org/licenses/Artistic-2.0.html)
- `Beerware` - [Beerware License](https://spdx.org/licenses/Beerware.html)
- `BSD-2-Clause` - [BSD 2-clause "Simplified"](https://spdx.org/licenses/BSD-2-Clause.html)
- `BSD-2-Clause-FreeBSD` - [BSD 2-Clause FreeBSD License](https://spdx.org/licenses/BSD-2-Clause-FreeBSD.html)
- `BSD-3-Clause` - [BSD 3-Clause "New" or "Revised"](https://spdx.org/licenses/BSD-3-Clause.html)
- `BSD-3-Clause-Attribution` - [BSD with attribution](https://spdx.org/licenses/BSD-3-Clause-Attribution.html)
- `BSD-4-Clause` - [BSD 4-clause "Original"](https://spdx.org/licenses/BSD-4-Clause.html)
- `CAL-1.0` - [Cryptographic Autonomy License 1.0](https://spdx.org/licenses/CAL-1.0.html)
- `CC-BY-SA-3.0` - [Creative Commons Attribution-ShareAlike 3.0 License](https://spdx.org/licenses/CC-BY-SA-3.0.html)
- `CC-BY-SA-4.0` - [Creative Commons Attribution-ShareAlike 4.0 License](https://spdx.org/licenses/CC-BY-SA-4.0.html)
- `CC0-1.0` - [Public Domain/Creative Common Zero 1.0](https://spdx.org/licenses/CC0-1.0.html)
- `CDDL-1.0` - [Common Development and Distribution License](https://spdx.org/licenses/CDDL-1.0.html)
- `CECILL-B` - [CEA CNRS INRIA Logiciel Libre](https://spdx.org/licenses/CECILL-B.html)
- `CPAL-1.0` - [Common Public Attribution License Version 1.0](https://spdx.org/licenses/CPAL-1.0.html)
- `ECL-2.0` - [Educational Community License, Version 2.0](https://spdx.org/licenses/ECL-2.0.html)
- `EPL-1.0` - [Eclipse Public License, Version 1.0](https://spdx.org/licenses/EPL-1.0.html)
- `EPL-2.0` - [Eclipse Public License, Version 2.0](https://spdx.org/licenses/EPL-2.0.html)
- `EUPL-1.2` - [European Union Public License 1.2](https://spdx.org/licenses/EUPL-1.2.html)
- `GPL-1.0` - [GNU General Public License 1.0](https://spdx.org/licenses/GPL-1.0.html)
- `GPL-2.0` - [GNU General Public License 2.0](https://spdx.org/licenses/GPL-2.0.html)
- `GPL-3.0` - [GNU General Public License 3.0](https://spdx.org/licenses/GPL-3.0.html)
- `IPL-1.0` - [IBM Public License](https://spdx.org/licenses/IPL-1.0.html)
- `ISC` - [Internet Systems Consortium License](https://spdx.org/licenses/ISC.html)
- `LGPL-2.1` - [Lesser General Public License 2.1](https://spdx.org/licenses/LGPL-2.1.html)
- `LGPL-3.0` - [Lesser General Public License 3.0](https://spdx.org/licenses/LGPL-3.0.html)
- `MIT` - [MIT License](https://spdx.org/licenses/MIT.html)
- `MPL-1.1` - [Mozilla Public License Version 1.1](https://spdx.org/licenses/MPL-1.1.html)
- `MPL-2.0` - [Mozilla Public License](https://spdx.org/licenses/MPL-2.0.html)
- `OSL-3.0` - [Open Software License 3.0](https://spdx.org/licenses/OSL-3.0.html)
- `Sendmail` - [Sendmail License](https://spdx.org/licenses/Sendmail.html)
- `Ruby` - [Ruby License](https://spdx.org/licenses/Ruby.html)
- `Unlicense` - [The Unlicense](https://spdx.org/licenses/Unlicense.html)
- `WTFPL` - [Do What the Fuck You Want to Public License](https://spdx.org/licenses/WTFPL.html)
- `Zlib` - [Zlib/libpng License](https://spdx.org/licenses/Zlib.html)
- `ZPL-2.0` - [Zope Public License 2.0](https://spdx.org/licenses/ZPL-2.0.html)
- `NLPL` - [No Limit Public License](https://spdx.org/licenses/NLPL.html)
- `GFDL-1.2` - [GNU Free Documentation License 1.2](https://spdx.org/licenses/GFDL-1.2.html)
- `LGPL-2.0` - [GNU Lesser General Public License v2](https://spdx.org/licenses/LGPL-2.0.html)
- `PL-1.0` - [Q Public License 1.0](https://spdx.org/licenses/QPL-1.0.html)
- `OLDAP-2.8` - [Open LDAP Public License v2.8](https://spdx.org/licenses/OLDAP-2.8.html)
- `QPL-1.0` - [Q Public License 1.0](https://spdx.org/licenses/QPL-1.0.html)
- `Vim` - [Vim License](https://spdx.org/licenses/Vim.html)


--------------------

## 反特性

- `⚠` - 依赖于用户无法控制的专有服务

--------------------

## 外部链接

**[`^        返回顶部        ^`](#id1)**


- 发现/过滤 awesome-selfhosted 应用的替代前端/门户：[awweso.me](https://awweso.me/), [awesome-web.theravenhub](https://awesome-web.theravenhub.com/browse.html), [awesomehub.web.app](https://awesomehub.js.org/list/selfhosted)
- [Awesome Sysadmin](https://github.com/awesome-foss/awesome-sysadmin) - 精心策划的开源系统管理员资源清单。
- 以隐私和去中心化形式为目的的软件列表：[PRISM Break](https://prism-break.org/en/), [privacytools.io](https://www.privacytools.io/), [Alternative Internet](https://redecentralize.github.io/alternative-internet/), [Libre Projects](https://libreprojects.net/), [Easy Indie App](https://easyindie.app)
- 其他 Awesome 清单：[Awesome Big Data](https://github.com/0xnr/awesome-bigdata), [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets)
- 动态域名服务：[Afraid.org](https://freedns.afraid.org/domain/registry/), [Pagekite](https://pagekite.net/)
- 社区/论坛：[lemmy.world 上的 /c/selfhosted](https://lemmy.world/c/selfhosted), [lemmy.ml 上的 /c/selfhost](https://lemmy.ml/c/selfhost), [Reddit 上的 /r/selfhosted](https://old.reddit.com/r/selfhosted/), [/r/selfhosted Matrix 频道](https://matrix.to/#/#selfhosted:selfhosted.chat), [Reddit 上的 /r/homelab](https://old.reddit.com/r/homelab/), [IndieWeb](https://indieweb.org/)
- [theme.park](https://theme-park.dev/) - 50 个自托管应用的主题/皮肤集合！（[源代码](https://github.com/GilbN/theme.park/)） `MIT` `CSS`


--------------------

## 贡献

贡献指南可在[此处](https://github.com/zituoguan/zituoguan-data/blob/master/CONTRIBUTING.md)找到。

## 许可证

此清单采用 [Creative Commons Attribution-ShareAlike 3.0 Unported](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/LICENSE) 许可。许可条款摘要可在[此处](https://creativecommons.org/licenses/by-sa/3.0/)查看。
作者列表可在 [AUTHORS](https://github.com/zituoguan/zituoguan-data/blob/master/AUTHORS) 文件中找到。
