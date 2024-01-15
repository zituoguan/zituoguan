# 自托管精选

[![Awesome](_static/awesome.png)](https://github.com/sindresorhus/awesome) [![](https://github.com/awesome-selfhosted/awesome-selfhosted-data/actions/workflows/check-dead-links.yml/badge.svg)](https://github.com/awesome-selfhosted/awesome-selfhosted-data/issues/1) [![](https://github.com/awesome-selfhosted/awesome-selfhosted-data/actions/workflows/check-unmaintained-projects.yml/badge.svg)](https://github.com/awesome-selfhosted/awesome-selfhosted-data/issues/1)

自托管是在自己的服务器上托管和管理应用程序，而不是依赖于 [SaaSS](https://www.gnu.org/philosophy/who-does-that-server-really-serve.html) 提供商。

这是一个列出了可以在您自己的服务器上托管的[自由](https://en.wikipedia.org/wiki/Free_software)软件 [网络服务](https://en.wikipedia.org/wiki/Network_service) 和 [Web 应用](https://en.wikipedia.org/wiki/Web_application)的清单。非自由软件列在 [Non-Free](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/non-free.md) 页面。

**[HTML 版本](https://zituoguan.com/)（推荐）**，[Markdown 版本](https://github.com/zituoguan/zituoguan)（旧版）。

请参阅 [贡献](#贡献)。

推荐 Vaultwarden 社区服务器 [https://mmglq.com](https://mmglq.com)(密码管理器)

--------------------

## Table of contents

- [Software](#software)
  - [DNS](#dns)
  - [URL 缩短服务](#url-缩短服务)
  - [Web 服务器](#web-服务器)
  - [个人仪表板](#个人仪表板)
  - [书签和链接分享](#书签和链接分享)
  - [人力资源管理（HRM）](#人力资源管理（hrm）)
  - [代理](#代理)
  - [任务管理和待办清单](#任务管理和待办清单)
  - [会议管理](#会议管理)
  - [内容管理系统（CMS）](#内容管理系统（cms）)
  - [分析](#分析)
  - [制造业](#制造业)
  - [办公套件](#办公套件)
  - [协同办公](#协同办公)
  - [博客平台](#博客平台)
  - [地图和全球定位系统（GPS）](#地图和全球定位系统（gps）)
  - [备份](#备份)
  - [学习和课程](#学习和课程)
  - [家谱研究](#家谱研究)
  - [密码管理器](#密码管理器)
  - [工单](#工单)
  - [库存管理](#库存管理)
  - [投票和事件](#投票和事件)
  - [搜索引擎](#搜索引擎)
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
  - [时间追踪](#时间追踪)
  - [杂项](#杂项)
  - [档案和数字保存（DP）](#档案和数字保存（dp）)
  - [流媒体](#流媒体)
  - [流媒体 - 多媒体流媒体](#流媒体---多媒体流媒体)
  - [流媒体 - 视频流媒体](#流媒体---视频流媒体)
  - [流媒体 - 音频流媒体](#流媒体---音频流媒体)
  - [游戏](#游戏)
  - [游戏 - 管理工具和控制面板](#游戏---管理工具和控制面板)
  - [照片和视频库](#照片和视频库)
  - [物联网（IoT）](#物联网（iot）)
  - [状态/正常运行时间页面](#状态正常运行时间页面)
  - [电子商务](#电子商务)
  - [监控](#监控)
  - [知识管理工具](#知识管理工具)
  - [社区支持农业（CSA）](#社区支持农业（csa）)
  - [笔记和编辑器](#笔记和编辑器)
  - [粘贴板](#粘贴板)
  - [维基](#维基)
  - [联邦身份和认证](#联邦身份和认证)
  - [自动化](#自动化)
  - [自托管解决方案](#自托管解决方案)
  - [虚拟专用网络（VPN）](#虚拟专用网络（vpn）)
  - [视频监控](#视频监控)
  - [订阅阅读器](#订阅阅读器)
  - [资源规划](#资源规划)
  - [资金、预算和管理](#资金、预算和管理)
  - [软件开发](#软件开发)
  - [软件开发 - API 管理](#软件开发---api-管理)
  - [软件开发 - FaaS 和无服务器](#软件开发---faas-和无服务器)
  - [软件开发 - IDE 和工具](#软件开发---ide-和工具)
  - [软件开发 - 低代码](#软件开发---低代码)
  - [软件开发 - 持续集成和部署](#软件开发---持续集成和部署)
  - [软件开发 - 本地化](#软件开发---本地化)
  - [软件开发 - 测试](#软件开发---测试)
  - [软件开发 - 项目管理](#软件开发---项目管理)
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
  - [静态网站生成器](#静态网站生成器)
  - [预订和日程安排](#预订和日程安排)
  - [食谱管理](#食谱管理)
- [List of Licenses](#list-of-licenses)
- [反特性](#反特性)
- [外部链接](#外部链接)
- [贡献](#贡献)
- [许可证](#许可证)

--------------------

## Software

### DNS

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[DNS](https://en.wikipedia.org/wiki/Domain_Name_System)服务器和带有广告屏蔽功能的管理工具，主要针对家庭或小型网络。

_See also: [awesome-sysadmin/DNS - 服务器](https://github.com/awesome-foss/awesome-sysadmin#dns---servers), [awesome-sysadmin/DNS - 控制面板和域名管理](https://github.com/awesome-foss/awesome-sysadmin#dns---control-panels--domain-management)_

- [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) - 免费且开源，用户友好的广告和跟踪器阻止 DNS 服务器。 ([Source Code](https://github.com/AdguardTeam/AdGuardHome)) `GPL-3.0` `Docker`
- [blocky](https://github.com/0xERR0R/blocky) - 快速轻量级的DNS代理（类似于Pi-hole），作为本地网络的广告拦截器，具有许多功能。 `Apache-2.0` `Go/Docker`
- [Maza ad blocking](https://maza-ad-blocking.andros.dev/) - 本地广告拦截器。类似于Pi-hole，但是在本地运行并使用您的操作系统。 ([Source Code](https://github.com/tanrax/maza-ad-blocking)) `Apache-2.0` `Shell`
- [Pi-hole](https://pi-hole.net/) - 一个用于管理和监控的具有图形用户界面的Internet广告黑洞。 ([Source Code](https://github.com/pi-hole/pi-hole)) `EUPL-1.2` `Shell/PHP`
- [Technitium DNS Server](https://technitium.com/dns/) - 具有广告拦截功能的权威/递归 DNS 服务器。 ([Source Code](https://github.com/TechnitiumSoftware/DnsServer)) `GPL-3.0` `Docker/C#`


### URL 缩短服务

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[URL 缩短](https://en.wikipedia.org/wiki/URL_shortening)是将 [URL](https://en.wikipedia.org/wiki/Uniform_Resource_Locator) 缩短以使其更短而仍然指向所需页面的操作。在托管之前，请查看 [URL 缩短服务的缺点](https://en.wikipedia.org/wiki/URL_shortening#Shortcomings)。

- [Blink](https://docs.blink.rest) - 为团队提供易于托管、集成SSO、由CDN支持的链接缩短器（+分离的分析）。 ([Source Code](https://github.com/JaneJeon/blink)) `AGPL-3.0` `Nodejs/Docker`
- [Easyshortener](https://github.com/easypanel-community/easyshortener) - 一个简单的 URL 缩短工具。 `MIT` `PHP/Nodejs/Docker`
- [Just Short It!](https://github.com/miawinter98/just-short-it) - 一个简单、单用户的URL缩短服务，仅运行在一个容器中。 `MIT` `Docker`
- [liteshort](https://git.ikl.sh/132ikl/liteshort) - 用户友好、真正轻量且可配置的URL缩短服务。 `MIT` `Python/deb`
- [Lstu](https://github.com/ldidry/lstu) - 轻量级URL缩短服务。 `WTFPL` `Perl/Docker`
- [Lynx](https://getlynx.dev) - 具有多账户、ShareX支持以及引人注目但简单的界面等多功能的URL缩短服务。 ([Demo](https://demo.getlynx.dev), [Source Code](https://github.com/Lynx-Shortener/Lynx)) `MIT` `Nodejs/Docker`
- [Pastr](https://github.com/hossainalhaidari/pastr) - 超简约的URL缩短器和粘贴工具，使用平面文件存储，无需依赖。 ([Demo](https://alhai.de)) `MIT` `Go/Docker`
- [rs-short](https://git.42l.fr/42l/rs-short) - 一个用 Rust 编写的轻量级链接缩短器，具有缓存、防垃圾机器人保护和钓鱼检测等功能。 ([Demo](https://s.42l.fr/)) `MPL-2.0` `Rust`
- [Shlink](https://shlink.io) - 具有 REST API 和命令行界面的 URL 缩短服务。包括官方的渐进式 Web 应用和 Docker 镜像。 ([Source Code](https://github.com/shlinkio/shlink), [Clients](https://shlink.io/apps)) `MIT` `PHP/Docker`
- [Short{Paste}](https://github.com/adyanth/shortpaste) - 基于 Go 的 URL 缩短服务、Pastebin 和文件上传工具。 `MIT` `Docker`
- [Simple-URL-Shortener](https://github.com/azlux/Simple-URL-Shortener) - KISS URL缩短服务，支持公共或私有（需要帐户）。简约轻便，无依赖。 ([Demo](https://u.azlux.fr)) `MIT` `PHP`
- [Simply Shorten](https://gitlab.com/draganczukp/simply-shorten) - 一个简单的URL缩短工具，只是缩短链接。 `MIT` `Java/Docker`
- [YOURLS](https://yourls.org/) - YOURLS是一组PHP脚本，允许您运行自己的URL缩短服务。功能包括密码保护、URL自定义、书签工具、统计信息、API、插件、jsonp等。 ([Source Code](https://github.com/YOURLS/YOURLS)) `MIT` `PHP`


### Web 服务器

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[Web 服务器](https://en.wikipedia.org/wiki/Web_server)是一种软件和底层硬件，通过 [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)（用于分发网络内容的网络协议）或其安全变体 [HTTPS](https://en.wikipedia.org/wiki/HTTPS) 接受请求。

**Please visit [awesome-sysadmin/Web](https://github.com/awesome-foss/awesome-sysadmin#web)**



### 个人仪表板

**[`^        back to top        ^`](#Awesome-Selfhosted)**

用于访问信息和应用程序的仪表板。

_Related: [监控](#监控), [书签和链接分享](#书签和链接分享)_

- [Dashy](https://github.com/lissy93/dashy) - 针对您的家庭实验室的功能丰富的主页，带有简单的 YAML 配置。 ([Demo](https://demo.dashy.to/)) `MIT` `Nodejs/Docker`
- [envlinks](https://github.com/maxhollmann/envlinks) - 一个极简的链接仪表板，显示来自环境变量的链接。 ([Demo](https://envlinks-demo.vercel.app/)) `MIT` `Docker`
- [Fenrus](https://github.com/revenz/fenrus) - 一个自托管的个人主页，允许多用户、访客访问和每个用户的多个仪表板。还有“智能应用”显示这些应用的实时数据。 `GPL-3.0` `.NET/Docker`
- [Heimdall](https://heimdall.site/) - Heimdall是一个优雅的解决方案，用于组织所有您的Web应用程序。 ([Source Code](https://github.com/linuxserver/Heimdall)) `MIT` `PHP`
- [Hiccup](https://designedbyashw.in/test/hiccup/) - 一个漂亮的静态主页，快速访问您的链接和服务。具有内置搜索、编辑、PWA支持和本地存储缓存，轻松组织起始页。 ([Source Code](https://github.com/ashwin-pc/hiccup)) `MIT` `Javascript/Docker`
- [Homarr](https://homarr.dev) - 时尚、现代的仪表板，集成了许多功能，支持基于Web的配置。 ([Demo](https://demo.homarr.dev), [Source Code](https://github.com/ajnart/homarr)) `MIT` `Docker/Nodejs`
- [Homepage by gethomepage](https://github.com/gethomepage/homepage) - 一个高度可定制的首页（或起始页/应用程序仪表板），具有Docker和服务API集成。 `GPL-3.0` `Docker/Nodejs`
- [Homepage by tomershvueli](https://github.com/tomershvueli/homepage) - 简单、独立、自托管的PHP页面，是您访问服务器和互联网的窗口。 `MIT` `PHP`
- [Homer](https://github.com/bastienwirtz/homer) - 一个非常简单的静态主页，用于展示您的服务器服务，具有简单的YAML配置和连接性检查。 `Apache-2.0` `Docker/K8S/Nodejs`
- [Hubleys](https://github.com/knrdl/hubleys-dashboard) - 自托管的个人仪表板，通过中央的yaml配置为多个用户组织链接。 `MIT` `Docker`
- [Jump](https://github.com/daledavies/jump) - 又一个为服务器设计的自托管起始页，简单、时尚、快速且安全。 `MIT` `Docker/PHP`
- [LinkStack](https://linkstack.org/) - 将您所有的社交媒体平台链接集中在一个页面上，通过直观、易于使用的用户/管理界面进行定制（是Linktree和Manylink的替代品）。 ([Demo](https://linksta.cc/), [Source Code](https://github.com/LinkStackOrg/LinkStack)) `AGPL-3.0` `PHP/Docker`
- [LittleLink](https://github.com/sethcottle/littlelink/) - 一个简单的个人主页链接方案，包含100+品牌按钮（是Linktree的替代品）。 ([Demo](https://littlelink.io/), [Source Code](https://github.com/sethcottle/littlelink)) `MIT` `Javascript`
- [Organizr](https://github.com/causefx/Organizr) - Organizr旨在成为您服务器前端的一站式解决方案。 `GPL-3.0` `PHP/Docker`
- [Smashing](https://smashing.github.io/) - Smashing，是Dashing的精神继承者，是一个基于Sinatra的框架，可让您构建出色的仪表板。在电视上特别出色。 ([Source Code](https://github.com/Smashing/smashing)) `MIT` `Ruby`
- [Starbase 80](https://github.com/notclickable-jordan/starbase-80) - 一个简单的主页，具有iPad风格的应用程序网格，适用于移动设备和桌面。只需一个JSON配置文件。 `MIT` `Docker`
- [Web-Portal](https://github.com/enchant97/web-portal) - 一款设计用于轻松管理所有网络服务链接的Python Web应用程序。 `AGPL-3.0` `Docker/Python`
- [Your Spotify](https://github.com/Yooooomi/your_spotify) `⚠` - 允许您记录Spotify播放活动，并通过Web应用程序提供有关它们的统计信息。 `MIT` `Nodejs/Docker`


### 书签和链接分享

**[`^        back to top        ^`](#Awesome-Selfhosted)**

软件允许用户添加、注释、编辑和分享[网络文档](https://en.wikipedia.org/wiki/Bookmark_(digital))的书签。

- [Briefkasten](https://github.com/ndom91/briefkasten) - 一款用于保存和管理个人书签的现代应用程序，包含浏览器扩展。 ([Demo](https://briefkastenhq.com/auth/signin)) `MIT` `Nodejs/Docker`
- [Buku](https://github.com/jarun/Buku) - 一个功能强大的书签管理器和个人纯文本迷你网络。 `GPL-3.0` `Python/deb`
- [Digibunch](https://ladigitale.dev/digibunch/#/) - 创建链接捆绑，与您的学员或同事分享。 ([Demo](https://ladigitale.dev/digibunch/#/b/5f67b12092b60), [Source Code](https://codeberg.org/ladigitale/digibunch)) `AGPL-3.0` `Nodejs/PHP`
- [Espial](https://github.com/jonschoning/espial) - 一个开源的、基于Web的书签服务器。 `AGPL-3.0` `Haskell`
- [Firefox Account Server](https://mozilla-services.readthedocs.io/en/latest/howtos/run-fxa.html) - 允许您托管自己的 Firefox 帐户服务器。 ([Source Code](https://github.com/mozilla/fxa)) `MPL-2.0` `Nodejs/Java`
- [Hackershare](https://github.com/hackershare/hackershare) - 面向黑客的社交书签网站。 `MIT` `Ruby`
- [LinkAce](https://www.linkace.org/) - 一个具有自动备份到Internet Archive、链接监控和完整REST API的书签存档。可以通过Docker安装，也可以作为简单的PHP应用程序安装。 ([Demo](https://demo.linkace.org/guest/links), [Source Code](https://github.com/Kovah/LinkAce/)) `GPL-3.0` `Docker/PHP`
- [linkding](https://github.com/sissbruecker/linkding) - 具有快速干净界面的最小书签管理工具。通过Docker简单安装，可在您的Raspberry Pi上运行。 `MIT` `Docker/Python/Nodejs`
- [LinkWarden](https://linkwarden.app/) - 一个自托管的书签+存档管理器，用于存储您的有用链接。 ([Source Code](https://github.com/linkwarden/linkwarden)) `MIT` `Docker/Nodejs`
- [NeonLink](https://github.com/AlexSciFier/neonlink) - 一种带有独特设计的自托管书签服务，使用 Docker 安装简便。 `MIT` `Docker`
- [Servas](https://github.com/beromir/Servas) - 一款自托管的书签管理工具。它支持通过标签、分组和专门用于以后访问的列表进行组织。支持多用户，并提供双因素认证 (2FA)。还提供了适用于 Firefox 和 Chrome 的伴侣浏览器扩展。 ([Clients](https://github.com/beromir/Servas#browser-extensions)) `GPL-3.0` `Docker/Nodejs/PHP`
- [Shaarli](https://github.com/shaarli/Shaarli) - 个人、极简、超快、无数据库的书签和链接分享平台。 ([Demo](https://demo.shaarli.org)) `Zlib` `PHP/deb`
- [Shiori](https://github.com/go-shiori/shiori) - 使用 Go 构建的简单书签管理器。 `MIT` `Go/Docker`
- [Slash](https://github.com/boojack/slash) - 一个开源的、自托管的书签和链接分享平台。 `GPL-3.0` `Docker`
- [SyncMarks](https://codeberg.org/Offerel/SyncMarks-Webapp) - 从 Edge、Firefox 和 Chromium 同步和管理您的浏览器书签。 ([Clients](https://codeberg.org/Offerel/SyncMarks-Extension)) `AGPL-3.0` `PHP`


### 人力资源管理（HRM）

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[人力资源管理系统](https://en.wikipedia.org/wiki/Human_resource_management_system)整合了多个系统和流程，以确保轻松管理[人力资源](https://en.wikipedia.org/wiki/Human_resources)、业务流程和数据。

- [Admidio](https://www.admidio.org/) - Admidio 是一个面向组织和团体网站的免费开源用户管理系统。该系统具有灵活的角色模型，因此可以反映您组织的结构和权限。 ([Demo](https://www.admidio.org/demo/), [Source Code](https://github.com/Admidio/admidio)) `GPL-2.0` `PHP/Docker`
- [OrangeHRM](https://www.orangehrm.com/) - OrangeHRM是一个全面的人力资源管理系统，涵盖了任何企业所需的所有基本功能。 ([Demo](https://opensource-demo.orangehrmlive.com/), [Source Code](https://github.com/orangehrm/orangehrm)) `GPL-2.0` `PHP`
- [TimeOff.Management](https://timeoff.management) - 面向中小型企业的简单而强大的缺勤管理软件。 ([Demo](https://app.timeoff.management), [Source Code](https://github.com/timeoff-management/timeoff-management-application)) `MIT` `Nodejs`


### 代理

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[代理](https://en.wikipedia.org/wiki/Proxy_server)是一种服务器应用程序，充当在客户端请求资源和提供该资源的服务器之间的中间人。

_Related: [Web 服务器](#web-服务器)_

- [imgproxy](https://imgproxy.net/) - 用于调整大小和转换远程图像的快速且安全的独立服务器。当您需要即时调整多个图像的大小，而无需准备大量缓存的调整大小图像或每次设计更改时都重新执行时，它非常有效。 ([Source Code](https://github.com/imgproxy/imgproxy)) `MIT` `Go/Docker/K8S`
- [iodine](https://code.kryo.se/iodine/) - 基于DNS的IPv4隧道解决方案，使您能够启动一个socks5代理监听器。 ([Source Code](https://github.com/yarrick/iodine)) `ISC` `C/deb`
- [Koblas](https://github.com/ynuwenhof/koblas) - 轻量级 SOCKS5 代理服务器。 `MIT` `Rust/Docker`
- [Nginx Proxy Manager](https://nginxproxymanager.com/) - Nginx Proxy Manager是一种简便的方法，用于实现带SSL终止的反向代理主机。 ([Source Code](https://github.com/NginxProxyManager/nginx-proxy-manager)) `MIT` `Nodejs/Docker`
- [Outline Server](https://getoutline.org/) - 代理服务器，为每个访问密钥运行一个Shadowsocks实例，并提供一个REST API来管理访问密钥。 ([Source Code](https://github.com/Jigsaw-Code/outline-server)) `Apache-2.0` `Docker/Nodejs`
- [Pomerium](https://www.pomerium.io) - 一种具有身份认证的反向代理，是目前已过时的oauth_proxy的继任者。它在将请求代理到后端之前插入了OAuth步骤，以便您可以安全地将您的自托管网站暴露给公共互联网。 ([Source Code](https://github.com/pomerium/pomerium)) `Apache-2.0` `Go`
- [Privoxy](https://www.privoxy.org) - 一款非缓存的Web代理，具有先进的过滤功能，用于增强隐私、修改网页数据和HTTP头部、控制访问，并去除广告和其他令人讨厌的互联网垃圾。 `GPL-2.0` `C/deb`
- [sish](https://github.com/antoniomika/sish) - 通过仅使用SSH实现到本地主机的HTTP(S)/WS(S)/TCP隧道（Serveo/ngrok的替代品）。 `MIT` `Go/Docker`
- [socks5-proxy-server](https://github.com/nskondratev/socks5-proxy-server) - 带有内置身份验证和Telegram机器人的SOCKS5代理服务器，用于用户管理和用户数据使用统计（在按数据量支付时非常方便）。已经Docker化，安装简便。 `Apache-2.0` `Docker`
- [Squid](http://www.squid-cache.org/) - Web缓存代理，支持HTTP、HTTPS、FTP等。通过缓存和重复使用频繁请求的网页，减少带宽并提高响应时间。 ([Source Code](https://code.launchpad.net/squid)) `GPL-2.0` `C/deb`
- [SWAG（Secure Web Application Gateway）](https://github.com/linuxserver/docker-swag) - Nginx webserver 和带有 PHP 支持的反向代理，内置 Certbot（Let's Encrypt）客户端和 fail2ban 集成。 `GPL-3.0` `Docker`
- [SWAG（Secure Web Application Gateway）](https://github.com/linuxserver/docker-swag) - Nginx webserver 和带有 PHP 支持的反向代理，内置 Certbot（Let's Encrypt）客户端和 fail2ban 集成。 `GPL-3.0` `Docker`
- [Tinyproxy](https://tinyproxy.github.io/) - 轻量级的 HTTP/HTTPS 代理守护程序。 ([Source Code](https://github.com/tinyproxy/tinyproxy)) `GPL-2.0` `C/deb`
- [txtdot](https://txtdot.github.io/documentation/) - 一个HTTP代理，它仅从页面中解析文本、链接和图片，减少互联网带宽使用，去除广告和沉重的脚本。 ([Demo](https://txt.dc09.ru), [Source Code](https://github.com/TxtDot/txtdot)) `MIT` `Nodejs/Docker`


### 任务管理和待办清单

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[任务管理](https://en.wikipedia.org/wiki/Task_management#Task_management_software)软件。

_Related: [软件开发 - 项目管理](#软件开发---项目管理), [工单](#工单)_

- [AppFlowy](https://appflowy.io/) - 使用 AppFlowy，您可以为不同项目构建详细的待办事项列表，并跟踪每个项目的状态。这是一个开源的 Notion 替代品。 ([Source Code](https://github.com/AppFlowy-IO/appflowy)) `AGPL-3.0` `Rust/Dart/Docker`
- [Focalboard](https://www.focalboard.com/) - 定义、组织、跟踪和管理个人和团队的工作（Trello、Notion 和 Asana 的替代品）。 ([Source Code](https://github.com/mattermost/focalboard), [Clients](https://www.focalboard.com/download/personal-edition/desktop/)) `MIT/AGPL-3.0/Apache-2.0` `Nodejs/Go/Docker`
- [Kanbana](https://github.com/SrGMC/kanbana) - 从平面Markdown文件创建看板以跟踪用户和项目（Crepido的分支）。 `MIT` `Nodejs`
- [Kanboard](https://kanboard.org/) - 简单且开源的可视化任务板。 ([Source Code](https://github.com/kanboard/kanboard)) `MIT` `PHP`
- [myTinyTodo](https://www.mytinytodo.net/) - 使用 AJAX 风格简单管理待办事项清单的方式。使用 PHP、jQuery、SQLite/MySQL。符合 GTD。 ([Demo](https://www.mytinytodo.net/demo/), [Source Code](https://github.com/maxpozdeev/mytinytodo/)) `GPL-2.0` `PHP`
- [Nullboard](https://github.com/apankrat/nullboard) - 单页极简看板；紧凑、易读且使用快捷。 `BSD-2-Clause` `Javascript`
- [Our Shopping List](https://github.com/nanawel/our-shopping-list) - 简单的共享列表应用程序。典型用途包括购物清单，当然还有任何其他需要协作使用的小型待办事项列表。 ([Demo](https://osl.lanterne-rouge.info/)) `AGPL-3.0` `Docker`
- [Planka](https://planka.app/) - 实时看板，用于工作组（Trello 的替代品）。 ([Demo](https://plankanban.github.io/planka/#/), [Source Code](https://github.com/plankanban/planka)) `AGPL-3.0` `Nodejs/Docker/K8S`
- [Task Keeper](https://github.com/nymanjens/piga) - 面向高级用户的列表编辑器，由自托管服务器支持。 `Apache-2.0` `Scala`
- [Tasks.md](https://github.com/BaldissaraMatheus/Tasks.md) - 支持 Markdown 语法的自托管文件型任务管理板。 `MIT` `Docker`
- [Taskwarrior](https://taskwarrior.org/) - Taskwarrior 是一款自由开源软件，可以通过命令行管理您的待办事项列表。它灵活、快速、高效且不显眼。它完成任务后离开您的视线。 ([Source Code](https://taskwarrior.org/download/#git)) `MIT` `C++`
- [Tracks](https://www.getontracks.org/) - 基于Web的应用，帮助您实施David Allen的[Getting Things Done™](https://en.wikipedia.org/wiki/Getting_Things_Done)方法论。 ([Source Code](https://github.com/TracksApp/tracks)) `GPL-2.0` `Ruby`
- [Vikunja](https://vikunja.io/) - 用于组织生活的待办事项应用。 ([Demo](https://try.vikunja.io/login), [Source Code](https://kolaente.dev/vikunja/)) `GPL-3.0` `Go`
- [Wekan](https://wekan.github.io/) - 类似Trello的开源看板（kanban）。 ([Source Code](https://github.com/wekan/wekan)) `MIT` `Nodejs`


### 会议管理

**[`^        back to top        ^`](#Awesome-Selfhosted)**

用于提交[摘要](https://en.wikipedia.org/wiki/Abstract_management)和准备/管理学术会议的软件。

- [Conference Organizing Distribution (COD)](http://usecod.com/) - 在Drupal的基础上创建会议和活动网站。 ([Source Code](https://git.drupalcode.org/project/cod)) `GPL-2.0` `PHP`
- [frab](https://frab.github.io/frab/) - 基于Web的会议规划和管理系统。它有助于收集提交，管理演讲和演讲者，并创建日程表。 ([Source Code](https://github.com/frab/frab)) `MIT` `Ruby/Docker`
- [indico](https://getindico.io/) - 一个功能丰富的活动管理系统，由CERN创建，这是Web诞生的地方。 ([Demo](https://sandbox.getindico.io/), [Source Code](https://github.com/indico/indico)) `MIT` `Python`
- [osem](https://osem.io/) - 面向自由软件大会的事件管理系统。 ([Source Code](https://github.com/openSUSE/osem)) `MIT` `Ruby/Docker`
- [pretalx](https://pretalx.org) - 基于Web的事件管理，包括发起论文征集、审阅提交内容和安排演讲。支持与各种相关工具的导出和导入。 ([Source Code](https://github.com/pretalx/pretalx)) `Apache-2.0` `Python`


### 内容管理系统（CMS）

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[内容管理系统](https://en.wikipedia.org/wiki/Content_management_system)提供了一种实用的方式来设置具有许多功能的网站，使用第三方插件、主题和易于添加和定制的功能。

_Related: [博客平台](#博客平台), [静态网站生成器](#静态网站生成器), [照片和视频库](#照片和视频库)_

- [Alfresco Community Edition](https://www.alfresco.com/products/community/download) - 开源企业内容管理软件，可处理任何类型的内容，使用户能够轻松共享和协作。 ([Source Code](https://github.com/Alfresco/alfresco-community-repo)) `LGPL-3.0` `Java`
- [Apostrophe](https://apostrophecms.com/) - 一款注重可扩展的现场编辑工具的内容管理系统 (CMS)。 ([Demo](https://apostrophecms.com/demo), [Source Code](https://github.com/apostrophecms/apostrophe)) `MIT` `Nodejs`
- [Backdrop CMS](https://backdropcms.org/) - 面向中小型企业和非营利组织的综合性 CMS。 ([Source Code](https://github.com/backdrop/backdrop)) `GPL-2.0` `PHP`
- [BigTree CMS](https://www.bigtreecms.org/) - 直观、文档完善、使用PHP和MySQL编写的CMS。 ([Source Code](https://github.com/bigtreecms/BigTree-CMS)) `LGPL-2.1` `PHP`
- [Bludit](https://www.bludit.com/) `⚠` - 在几秒钟内构建站点或博客的简单应用程序。Bludit使用平面文件（JSON格式的文本文件）来存储帖子和页面。 ([Demo](https://demo.bludit.com/), [Source Code](https://github.com/bludit/bludit)) `MIT` `PHP`
- [Bolt CMS](https://boltcms.io/) - 一款开源的内容管理工具，致力于尽可能简单和直观。 ([Source Code](https://github.com/bolt/core)) `MIT` `PHP`
- [CMS Made Simple](https://www.cmsmadesimple.org/) - 开源内容管理系统，更快、更轻松地管理网站内容，适用于小型企业到大型企业的规模。 ([Source Code](http://svn.cmsmadesimple.org/svn/cmsmadesimple/trunk/)) `GPL-2.0` `PHP`
- [Cockpit](https://getcockpit.com) - 用于管理任何结构化内容的简单内容平台。 ([Source Code](https://github.com/Cockpit-HQ/Cockpit)) `MIT` `PHP`
- [Concrete 5 CMS](https://www.concretecms.com) - 开源内容管理系统。 ([Source Code](https://github.com/concretecms/concretecms)) `MIT` `PHP`
- [Contao](https://contao.org/) - Contao是一个强大的开源CMS，允许您创建专业的网站和可扩展的Web应用程序。 ([Source Code](https://github.com/contao/contao/)) `LGPL-3.0` `PHP`
- [CouchCMS](https://www.couchcms.com/) - 面向设计师的简单开源CMS。 ([Source Code](https://github.com/CouchCMS/CouchCMS)) `CPAL-1.0` `PHP`
- [Drupal](https://www.drupal.org/) - 先进的开源内容管理平台。 ([Source Code](https://git.drupalcode.org/project/drupal)) `GPL-2.0` `PHP`
- [eLabFTW](https://www.elabftw.net) - 用于研究实验室的在线实验笔记本。存储实验数据，使用数据库查找试剂或协议，使用受信任的时间戳对实验进行法律时间戳，导出为PDF或ZIP归档文件，与合作者共享……。 ([Demo](https://demo.elabftw.net), [Source Code](https://github.com/elabftw/elabftw)) `AGPL-3.0` `PHP`
- [Expressa](https://github.com/thomas4019/expressa) - 用于通过JSON模式驱动的数据库网站的内容管理系统。提供权限管理和自动REST API。 `MIT` `Nodejs`
- [Joomla!](https://www.joomla.org/) - 先进的内容管理系统（CMS）。 ([Source Code](https://github.com/joomla/joomla-cms)) `GPL-2.0` `PHP`
- [KeystoneJS](https://keystonejs.com/) - CMS和Web应用程序平台。 ([Source Code](https://github.com/keystonejs/keystone)) `MIT` `Nodejs`
- [MODX](https://modx.com/) - MODX 是一款先进的内容管理和发布平台。当前版本称为 'Revolution'。 ([Source Code](https://github.com/modxcms/revolution)) `GPL-2.0` `PHP`
- [Neos](https://www.neos.io) - Neos 或 TYPO3 Neos（版本 1）是一款现代的开源 CMS。 ([Source Code](https://github.com/neos)) `GPL-3.0` `PHP`
- [Noosfero](https://gitlab.com/noosfero/noosfero) - Noosfero是一个用于社会和团结经济网络的Web平台，具有博客、电子资料集、内容管理系统（CMS）、RSS、主题讨论、事件日程和团结经济的集体智能，所有这些功能都在同一系统中。 `AGPL-3.0` `Ruby`
- [Omeka](https://omeka.org) - 在您的服务器上使用Omeka创建复杂的叙述并共享丰富的收藏，遵循Dublin Core标准，专为学者、博物馆、图书馆、档案馆和爱好者设计。 ([Demo](https://omeka.org/classic/showcase/), [Source Code](https://github.com/omeka/Omeka)) `GPL-3.0` `PHP`
- [Payload CMS](https://payloadcms.com/) - 面向开发者的无头CMS和应用程序框架。 ([Demo](https://demo.payloadcms.com), [Source Code](https://github.com/payloadcms/payload)) `MIT` `Nodejs`
- [Pimcore](https://www.pimcore.org/) - 多渠道体验和参与管理平台。 ([Source Code](https://github.com/pimcore/pimcore)) `GPL-3.0` `PHP/Docker`
- [Plone](https://plone.org/) - 强大的开源内容管理系统（CMS）。 ([Source Code](https://github.com/plone)) `ZPL-2.0` `Python/Docker`
- [PropertyWebBuilder](https://propertywebbuilder.com) - 用于创建房地产网站的最终Ruby on Rails引擎。 ([Source Code](https://github.com/etewiah/property_web_builder)) `MIT` `Ruby`
- [Publify](https://publify.github.io/) - 简单但功能齐全的Web发布软件。 ([Source Code](https://github.com/publify/publify)) `MIT` `Ruby`
- [Rapido](https://framagit.org/InfoLibre/rapido) - 使用Rapido创建您的网站。编辑、发布和共享协作内容。 `AGPL-3.0` `Go`
- [REDAXO](https://www.redaxo.org) - 简单、灵活、实用的内容管理系统（仅提供德语文档）。 ([Source Code](https://github.com/redaxo/redaxo)) `MIT` `PHP/Docker`
- [Roadiz](https://www.roadiz.io/) - 基于节点系统的现代 CMS，可以处理多种类型的服务。 ([Source Code](https://github.com/roadiz/roadiz)) `MIT` `PHP`
- [SilverStripe](https://www.silverstripe.org) - 易于使用的 CMS，具有强大的 MVC 框架作为基础。 ([Demo](https://demo.silverstripe.org/), [Source Code](https://github.com/silverstripe)) `BSD-3-Clause` `PHP`
- [SPIP](https://www.spip.net/fr) - 面向协同工作、多语言环境和Web作者使用简便的互联网发布系统。 ([Source Code](https://git.spip.net/)) `GPL-3.0` `PHP`
- [Squidex](https://squidex.io) - 基于MongoDB、CQRS和事件溯源的无头CMS。 ([Demo](https://cloud.squidex.io), [Source Code](https://github.com/Squidex/squidex)) `MIT` `.NET`
- [Strapi](https://strapi.io/) - 最先进的开源内容管理框架（无头CMS），可以轻松构建强大的API。 ([Source Code](https://github.com/strapi/strapi)) `MIT` `Nodejs`
- [Textpattern](https://textpattern.com/) - 灵活、优雅且易于使用的内容管理系统。 ([Demo](https://textpattern.co/demo), [Source Code](https://github.com/textpattern/textpattern)) `GPL-2.0` `PHP`
- [Typemill](https://typemill.net/) - 作者友好的基于文件的CMS，具有基于vue.js的可视化Markdown编辑器。 ([Source Code](https://github.com/typemill/typemill)) `MIT` `PHP`
- [TYPO3](https://typo3.org/) - 强大而先进的CMS，拥有庞大的社区。 ([Source Code](https://github.com/TYPO3/typo3)) `GPL-2.0` `PHP`
- [Umbraco](https://umbraco.com/) - 友好的CMS。免费、开源，并拥有令人惊叹的社区。 ([Source Code](https://github.com/umbraco/Umbraco-CMS)) `MIT` `.NET`
- [Wagtail](https://wagtail.io/) - 基于Django的内容管理系统，注重灵活性和用户体验。 ([Source Code](https://github.com/wagtail/wagtail)) `BSD-3-Clause` `Python`
- [WinterCMS](https://wintercms.com/) - 基于Laravel PHP框架构建的快速且安全的内容管理系统。 ([Source Code](https://github.com/wintercms/winter)) `MIT` `PHP`
- [WonderCMS](https://www.wondercms.com) - WonderCMS是自2008年以来最小的平面文件CMS。 ([Demo](https://www.wondercms.com/demo), [Source Code](https://github.com/WonderCMS/wondercms)) `MIT` `PHP`
- [WordPress](https://wordpress.org/) - 全球最常用的博客和内容管理系统引擎。 ([Source Code](https://github.com/WordPress/WordPress)) `GPL-2.0` `PHP`


### 分析

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[分析](https://en.wikipedia.org/wiki/Analytics)是对数据或统计信息进行系统计算分析的过程。它用于发现、解释和传达数据中的有意义的模式。

_Related: [数据库管理](#数据库管理), [个人仪表板](#个人仪表板)_

- [Aptabase](https://aptabase.com/) - 面向移动和桌面应用的开源、隐私第一的简易分析工具。 ([Source Code](https://github.com/aptabase/aptabase)) `AGPL-3.0` `Docker`
- [AWStats](http://www.awstats.org/) - 从 web、流媒体、FTP 或邮件服务器的日志文件生成统计信息。 ([Source Code](https://github.com/eldy/awstats)) `GPL-3.0` `Perl`
- [Countly Community Edition](https://count.ly) - 实时移动和Web分析、崩溃报告和推送通知平台。 ([Source Code](https://github.com/countly)) `AGPL-3.0` `Nodejs/Docker`
- [Druid](http://druid.io/) - 分布式、面向列、实时分析数据存储。 ([Source Code](https://github.com/apache/druid)) `Apache-2.0` `Java/Docker`
- [EDA](https://eda.jortilles.com/en/jortilles-english/) - 用于数据分析和可视化的Web应用程序。 ([Source Code](https://github.com/jortilles/EDA)) `Apache-2.0` `Docker/Rust`
- [Fathom Lite](https://github.com/usefathom/fathom) - 一个简单而注重隐私的Web分析工具（可替代Google Analytics）。 `MIT` `Go/Docker`
- [GoAccess](http://goaccess.io/) - 实时网络日志分析器和交互式查看器，可在终端中运行。 ([Source Code](https://github.com/allinurl/goaccess)) `GPL-2.0` `C`
- [GoatCounter](https://www.goatcounter.com) - 无需跟踪个人数据的简易网络统计工具。 ([Source Code](https://github.com/arp242/goatcounter)) `EUPL-1.2` `Go`
- [Matomo](https://matomo.org/) - Google Analytics的替代品，保护您的数据和客户的隐私。 ([Source Code](https://github.com/matomo-org/matomo)) `GPL-3.0` `PHP`
- [Metabase](https://metabase.com/) - 一种简单、开源的方式，让您公司中的每个人都能提出问题并从数据中学习。 ([Source Code](https://github.com/metabase/metabase)) `AGPL-3.0` `Java/Docker`
- [Mixpost](https://mixpost.app/) - 自托管的社交媒体管理软件。在一个地方轻松创建、计划、发布和管理社交媒体内容（替代 Hootsuite、Buffer 和其他社交媒体工具）。 ([Source Code](https://github.com/inovector/MixpostApp)) `MIT` `PHP/Docker`
- [Netron](https://netron.app/) - 神经网络和机器学习模型的可视化工具。 ([Source Code](https://github.com/lutzroeder/netron)) `MIT` `Python/Nodejs`
- [Offen](https://www.offen.dev/) - 公平、轻量级和开放的Web分析工具。在用户完全访问其数据的同时获取见解。 ([Demo](https://www.offen.dev/try-demo/), [Source Code](https://github.com/offen/offen)) `Apache-2.0` `Go/Docker`
- [Open Web Analytics](http://www.openwebanalytics.com/) - Web分析框架，让您可以控制如何对您的网站和应用程序进行仪表化和分析。 ([Source Code](https://github.com/Open-Web-Analytics/Open-Web-Analytics)) `GPL-2.0` `PHP`
- [Plausible Analytics](https://plausible.io/) - 简单、开源、轻量（< 1 KB）且注重隐私的网络分析工具。 ([Source Code](https://github.com/plausible/analytics/)) `AGPL-3.0` `Elixir`
- [PoeticMetric](https://www.poeticmetric.com) - 自由、开源、注重隐私并符合法规的网络分析工具。 ([Demo](https://www.poeticmetric.com/s?d=www.poeticmetric.com), [Source Code](https://github.com/th0th/poeticmetric)) `AGPL-3.0` `Docker`
- [PostHog](https://posthog.com) - 产品分析、会话录制、特征标记和A/B测试，可自行托管（替代Mixpanel/Amplitude/Heap/HotJar/Optimizely）。 ([Source Code](https://github.com/posthog/posthog)) `MIT` `Python`
- [Redash](http://redash.io) - 连接和查询您的数据源，构建可视化数据的仪表板，并与您的团队共享。 ([Source Code](https://github.com/getredash/redash)) `BSD-2-Clause` `Docker`
- [RudderStack](https://rudderstack.com/) - 收集、统一、转换和存储客户数据，并将其路由到各种常见、流行的营销、销售和产品工具（Segment 的替代品）。 ([Source Code](https://github.com/rudderlabs/rudder-server/)) `AGPL-3.0` `Docker/K8S/Go/Nodejs`
- [Shynet](https://github.com/milesmcc/shynet) - 现代、注重隐私且详细的 Web 分析工具，无需使用 Cookies 或 JS。 `Apache-2.0` `Python/Docker`
- [Socioboard](https://github.com/socioboard/Socioboard-5.0) `⚠` - 支持九个社交媒体网络的社交媒体管理、分析和报告平台。 `GPL-3.0` `Nodejs`
- [Superset](http://superset.apache.org/) - 现代数据探索和可视化平台。 ([Source Code](https://github.com/apache/superset)) `Apache-2.0` `Python`
- [Swetrix](https://swetrix.com/) - 终极开源网络分析工具，满足您的所有需求。 ([Demo](https://swetrix.com/projects/STEzHcB1rALV), [Source Code](https://github.com/Swetrix/selfhosting)) `AGPL-3.0` `Docker`
- [Umami](https://umami.is/) - 简单、快速、注重隐私的Google Analytics替代方案。 ([Demo](https://analytics.umami.is/share/LGazGOecbDtaIwDr/umami.is), [Source Code](https://github.com/umami-software/umami)) `MIT` `Nodejs/Docker`


### 制造业

**[`^        back to top        ^`](#Awesome-Selfhosted)**

用于管理[3D打印机](https://en.wikipedia.org/wiki/3D_printing)、[数控机床（CNC）](https://en.wikipedia.org/wiki/Numerical_control)和其他物理制造工具的软件。

- [CNCjs](https://cnc.js.org/) - 用于运行Grbl、Smoothieware或TinyG的CNC铣床控制器的基于Web的界面。 ([Source Code](https://github.com/cncjs/cncjs/)) `MIT` `Nodejs`
- [Fluidd](https://docs.fluidd.xyz/) - 用于Klipper 3D打印机固件的轻量且响应灵敏的用户界面。 ([Source Code](https://github.com/fluidd-core/fluidd)) `GPL-3.0` `Docker/Nodejs`
- [Mainsail](https://docs.mainsail.xyz/) - Klipper 3D打印机固件的现代响应式用户界面。随时随地，从任何设备控制和监控您的打印机。 ([Source Code](https://github.com/mainsail-crew/mainsail)) `GPL-3.0` `Docker/Python`
- [OctoPrint](https://octoprint.org/) - 用于控制消费级3D打印机的灵活Web界面。 ([Source Code](https://github.com/OctoPrint/OctoPrint)) `AGPL-3.0` `Docker/Python`
- [VanDAM](https://github.com/Floppy/van_dam) - 用于3D打印文件（如STL、OBJ、3MF等）的数字资产管理器。 `MIT` `Docker`


### 办公套件

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[办公套件](https://en.wikipedia.org/wiki/List_of_office_suites)是一套通常包含至少一个文字处理器、电子表格和演示程序的生产力软件集合。

- [Collabora Online Development Edition](https://www.collaboraoffice.com/code) - Collabora Online Development Edition (CODE) 是一个基于LibreOffice的强大的在线办公套件，支持所有主要的文档、电子表格和演示文件格式，可以集成到您自己的基础设施中。 ([Source Code](https://cgit.freedesktop.org/libreoffice/online/)) `MPL-2.0` `C++`
- [CryptPad](https://cryptpad.org) - CryptPad是一个端到端加密和开源的协作套件。它旨在实现协作，实时同步文档的更改。 ([Source Code](https://github.com/cryptpad/cryptpad)) `AGPL-3.0` `Nodejs/Docker`
- [Etherpad](https://etherpad.org/) - Etherpad是一个高度可定制的开源在线编辑器，提供实时协作编辑。 ([Demo](https://demo.sandstorm.io/appdemo/h37dm17aa89yrd8zuqpdn36p6zntumtv08fjpu8a8zrte7q1cn60), [Source Code](https://github.com/ether/etherpad-lite)) `Apache-2.0` `Nodejs/Docker`
- [Grist](https://getgrist.com/) - Grist是一种具有关系结构、基于公式的访问控制和可移植的、自包含格式的下一代电子表格（Airtable的替代品）。 ([Demo](https://docs.getgrist.com), [Source Code](https://github.com/gristlabs/grist-core)) `Apache-2.0` `Nodejs/Python/Docker`
- [Infinoted](https://github.com/gobby/gobby/wiki/Dedicated%20Server) - 用于[Gobby](https://github.com/gobby/gobby/wiki)的服务器，Gobby是一个多平台协作文本编辑器。 ([Source Code](https://github.com/gobby/gobby)) `MIT` `C++`
- [ONLYOFFICE](https://helpcenter.onlyoffice.com/faq/server-opensource.aspx) - 办公套件，使您能够在一个地方管理文档、项目、团队和客户关系。 ([Source Code](https://github.com/ONLYOFFICE/DocumentServer)) `AGPL-3.0` `Nodejs/Docker`
- [PHPOffice](https://github.com/PHPOffice) - PHPOffice包含可以用于读写大多数办公套件文件的库。 `LGPL-3.0` `PHP`


### 协同办公

**[`^        back to top        ^`](#Awesome-Selfhosted)**

协同软件或[协同办公](https://en.wikipedia.org/wiki/Collaborative_software)旨在帮助共同完成任务的人们实现他们的目标。协同办公通常将多个服务（如文件共享、日历/事件管理、通讯录等）集成在一个单一的应用程序中。

- [Citadel](https://www.citadel.org/) - 包括电子邮件、日历/日程安排、通讯簿、论坛、邮件列表、即时消息、维基和博客引擎、RSS聚合等的团队协作软件。 ([Source Code](https://www.citadel.org/source.html)) `GPL-3.0` `C/Docker/Shell`
- [Corteza](https://cortezaproject.org) - 包括统一工作区、企业消息和低代码环境的CRM，用于快速安全地提供基于记录的管理解决方案。 ([Demo](https://latest.cortezaproject.org), [Source Code](https://github.com/cortezaproject/corteza)) `Apache-2.0` `Go`
- [Cozy Cloud](https://cozy.io/) - 个人云，您可以在其中管理和同步联系人、文件和日历，并通过一个充满社区贡献的应用商店管理预算。 ([Source Code](https://github.com/cozy/)) `GPL-3.0` `Nodejs`
- [Digipad](https://digipad.app/) - 用于创建协作数字记事本的在线自托管应用（文档以法语为主）。 ([Source Code](https://codeberg.org/ladigitale/digipad)) `AGPL-3.0` `Nodejs`
- [Digiwall](https://digiwall.app/) - 为面对面或远程工作创建多媒体协作墙（法语文档）. ([Source Code](https://codeberg.org/ladigitale/digiwall)) `AGPL-3.0` `Nodejs`
- [egroupware](https://www.egroupware.org/) - 软件套件包括日历、通讯录、记事本、项目管理工具、客户关系管理工具（CRM）、知识管理工具、维基和内容管理系统（CMS）。 ([Source Code](https://github.com/EGroupware/egroupware)) `GPL-2.0` `PHP`
- [EspoCRM](https://www.espocrm.com/) - 具有设计为单页应用程序的前端和REST API的CRM系统。 ([Demo](https://demo.espocrm.com/), [Source Code](https://github.com/espocrm/espocrm)) `GPL-3.0` `PHP`
- [Group Office](https://www.group-office.com) - Group-Office是一款企业级CRM和团队协作工具。与同事和客户在线共享项目、日历、文件和电子邮件。 ([Source Code](https://github.com/Intermesh/groupoffice/)) `AGPL-3.0` `PHP`
- [Openmeetings](https://openmeetings.apache.org/index.html) - Openmeetings提供视频会议、即时消息、白板、协作文档编辑和其他集成API函数的Red5 Streaming服务器的团队软件工具。 ([Source Code](https://openmeetings.apache.org/scm.html)) `Apache-2.0` `Java`
- [SOGo](https://www.sogo.nu/) - SOGo提供多种访问日历和消息数据的方式。支持CalDAV、CardDAV、GroupDAV，以及ActiveSync，包括原生Outlook兼容性和Web界面。 ([Demo](https://demo.sogo.nu/SOGo/), [Source Code](https://github.com/Alinto/sogo)) `LGPL-2.1` `Objective-C`
- [SuiteCRM](https://suitecrm.com) - 获奖的企业级开源客户关系管理系统。 ([Source Code](https://github.com/salesagility/SuiteCRM)) `AGPL-3.0` `PHP`
- [Tracim](https://github.com/tracim/tracim) - 团队协作的协作平台：文件、讨论、笔记、日程等。 `AGPL-3.0/LGPL-3.0/MIT` `Python`
- [Zimbra Collaboration](https://www.zimbra.com/) - 具有Web界面和许多集成的电子邮件、日历、协作服务器。 ([Source Code](https://github.com/zimbra)) `GPL-2.0/CPAL-1.0` `Java`


### 博客平台

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[博客](https://en.wikipedia.org/wiki/Blog)是由离散的、类日记式的文本条目（帖子）组成的讨论或信息性网站。

_Related: [静态网站生成器](#静态网站生成器), [内容管理系统（CMS）](#内容管理系统（cms）)_

_See also: [WeblogMatrix](https://www.weblogmatrix.org/)_

- [Antville](https://antville.org) - 一个旨在开发高性能、功能丰富的博客托管软件的免费、开源项目。 ([Source Code](https://github.com/antville/antville)) `Apache-2.0` `Javascript`
- [Blog](https://github.com/m1k1o/blog) - Facebook风格的博客。免费、极轻量级、单用户且易于安装。 `GPL-3.0` `PHP`
- [Castopod](https://castopod.org) - 一个包括最新的播客2.0标准、自动化Fediverse订阅、分析、可嵌入播放器等功能的播客管理托管平台。 ([Source Code](https://code.castopod.org/adaures/castopod)) `AGPL-3.0` `PHP/Docker`
- [Chyrp Lite](https://chyrplite.net) - 额外强大、额外轻量级的博客引擎。 ([Source Code](https://github.com/xenocrat/chyrp-lite)) `BSD-3-Clause` `PHP`
- [Dotclear](https://dotclear.org/) - 在博客上拥有更多控制权。 ([Source Code](https://git.dotclear.org/dev/dotclear)) `GPL-2.0` `PHP`
- [FlatPress](https://flatpress.org/) - 一款轻量、易于设置的平面文件博客引擎。 ([Source Code](https://github.com/flatpressblog/flatpress)) `GPL-2.0` `PHP`
- [Ghost](https://ghost.org/) - 仅仅是一个博客平台。 ([Source Code](https://github.com/TryGhost/Ghost)) `MIT` `Nodejs`
- [Haven](https://havenweb.org/) - 具有Markdown编辑和内置RSS阅读器的私人博客系统。 ([Demo](https://havenweb.org/demo.html), [Source Code](https://github.com/havenweb/haven)) `MIT` `Ruby`
- [Known](https://withknown.com/) - 一款协作式社交发布平台。 ([Source Code](https://github.com/idno/known)) `Apache-2.0` `PHP`
- [Mataroa](https://mataroa.blog/) - Mataroa是一个为极简主义者设计的无装饰的博客平台。 ([Source Code](https://github.com/mataroa-blog/mataroa)) `MIT` `Python`
- [PluXml](https://pluxml.org) - 基于XML的博客/CMS平台。 ([Source Code](https://github.com/pluxml/PluXml)) `GPL-3.0` `PHP`
- [Serendipity](https://docs.s9y.org/) - Serendipity (s9y) 是一个高度可扩展和可定制的 PHP 博客引擎，使用 Smarty 模板引擎。 ([Source Code](https://github.com/s9y/serendipity)) `BSD-3-Clause` `PHP`
- [WriteFreely](https://writefreely.org) - 用于创建极简、联合的博客或整个社区的写作软件。 ([Source Code](https://github.com/writefreely/writefreely)) `AGPL-3.0` `Go`


### 地图和全球定位系统（GPS）

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[地图](https://en.wikipedia.org/wiki/Map)、[制图学](https://en.wikipedia.org/wiki/Cartography)、[地理信息系统（GIS）](https://en.wikipedia.org/wiki/Geographic_information_system)和[全球定位系统（GPS）](https://en.wikipedia.org/wiki/Global_Positioning_System)软件。

_See also: [awesome-openstreetmap](https://github.com/osmlab/awesome-openstreetmap), [awesome-gis](https://github.com/sshuair/awesome-gis)_

- [Bicimon](https://github.com/knrdl/bicimon) - 自行车速度计作为渐进式Web应用。 ([Demo](https://knrdl.github.io/bicimon/)) `MIT` `Javascript`
- [Geo2tz](https://github.com/noandrea/geo2tz) - 通过地理坐标（纬度、经度）获取时区。 `MIT` `Go/Docker`
- [GraphHopper](https://graphhopper.com/) - 使用OpenStreetMap的快速路由库和服务器。 ([Source Code](https://github.com/graphhopper/graphhopper)) `Apache-2.0` `Java`
- [Nominatim](https://nominatim.org/) - 用于在OpenStreetMap数据上进行地理编码（地址 -> 坐标）和反向地理编码（坐标 -> 地址）的服务器应用程序。 ([Source Code](https://github.com/osm-search/Nominatim)) `GPL-2.0` `C`
- [Open Source Routing Machine (OSRM)](http://project-osrm.org/) - 高性能路由引擎，设计用于运行在OpenStreetMap数据上，并提供HTTP API、C++库接口和Nodejs包装器。 ([Demo](https://map.project-osrm.org/), [Source Code](https://github.com/Project-OSRM/osrm-backend)) `BSD-2-Clause` `C++`
- [OpenRouteService](https://openrouteservice.org/) - 自托管的路线服务，提供方向、等时线、时间-距离矩阵、路线优化等功能。 ([Demo](https://openrouteservice.org/dev/#/api-docs/introduction), [Source Code](https://github.com/GIScience/openrouteservice)) `GPL-3.0` `Docker/Java`
- [OpenStreetMap](https://www.openstreetmap.org/) - 协作项目，创建一个免费可编辑的世界地图。 ([Source Code](https://github.com/openstreetmap/openstreetmap-website), [Clients](https://wiki.openstreetmap.org/wiki/Software)) `GPL-2.0` `Ruby`
- [OpenTripPlanner](https://www.opentripplanner.org/) - 基于OpenStreetMap数据的多模式旅行规划软件，使用发布的GTFS格式数据来建议使用本地公共交通系统的路线。 ([Source Code](https://github.com/opentripplanner/OpenTripPlanner)) `LGPL-3.0` `Java/Javascript`
- [OwnTracks Recorder](https://github.com/owntracks/recorder) `⚠` - 存储并访问由[OwnTracks](https://owntracks.org/)位置跟踪应用发布的数据。 `GPL-2.0` `C/Lua/deb/Docker`
- [TileServer GL](https://tileserver.readthedocs.io/) - 使用 GL 样式的矢量和栅格地图。由 Mapbox GL Native 进行服务器端渲染。适用于 Mapbox GL JS、Android、iOS、Leaflet、OpenLayers、通过 WMTS 的 GIS 等的地图切片服务器。 ([Source Code](https://github.com/maptiler/tileserver-gl)) `BSD-2-Clause` `Nodejs/Docker`
- [Traccar](https://www.traccar.org/) - 用于追踪GPS位置的Java应用。支持大量追踪设备和协议，具有Android和iOS应用程序。拥有Web界面，可查看您的行程。 ([Demo](https://demo.traccar.org/), [Source Code](https://github.com/traccar)) `Apache-2.0` `Java`
- [μlogger](https://github.com/bfabiszewski/ulogger-server) - 实时收集用户的地理位置，并在网站上显示他们的GPS轨迹。 ([Demo](http://ulogger.fabiszewski.net/)) `GPL-3.0` `PHP`


### 备份

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[备份](https://en.wikipedia.org/wiki/Backup)软件。

**Please visit [awesome-sysadmin/Backups](https://github.com/awesome-foss/awesome-sysadmin#backups)**



### 学习和课程

**[`^        back to top        ^`](#Awesome-Selfhosted)**

用于辅助教育和学习的工具和软件。

- [Canvas LMS](https://www.instructure.com/canvas/) - Canvas是受信任的开源学习管理系统（LMS），正在彻底改变我们教育的方式。 ([Demo](https://canvas.instructure.com/register), [Source Code](https://github.com/instructure/canvas-lms)) `AGPL-3.0` `Ruby`
- [Chamilo LMS](https://chamilo.org/) - Chamilo LMS 允许您创建一个虚拟校园，用于提供在线或半在线培训。 ([Source Code](https://github.com/chamilo/chamilo-lms)) `GPL-3.0` `PHP`
- [Dalton Plan](https://daltonplan.com) - Dalton Plan 是 20 世纪 Helen Parkhurst 开发的自由教学方法的现代采用。 ([Source Code](https://git.io/daltonplan)) `AGPL-3.0` `PHP`
- [Digiscreen](https://ladigitale.dev/digiscreen/) - 课堂交互式白板/墙纸，支持远程和面对面教学（法语文档）。 ([Demo](https://ladigitale.dev/digiscreen/), [Source Code](https://codeberg.org/ladigitale/digiscreen)) `AGPL-3.0` `Nodejs/PHP`
- [Digiscreen](https://ladigitale.dev/digiscreen/) - 课堂交互式白板/墙纸，支持远程和面对面教学（法语文档）。 ([Demo](https://ladigitale.dev/digiscreen/), [Source Code](https://codeberg.org/ladigitale/digiscreen)) `AGPL-3.0` `Nodejs/PHP`
- [Digitools](https://ladigitale.dev/digitools) - 一套简单的工具，用于支持远程或面对面课程的动画教学（法语文档）. ([Demo](https://ladigitale.dev/digitools/), [Source Code](https://codeberg.org/ladigitale/digitools)) `AGPL-3.0` `PHP`
- [edX](https://www.edx.org/) - Open edX平台是edX.org的开源代码。 ([Source Code](https://github.com/edx/)) `AGPL-3.0` `Python`
- [Gibbon](https://gibbonedu.org/) - 灵活的、开源的学校管理平台，旨在改善教师、学生、家长和领导的生活。 ([Source Code](https://github.com/GibbonEdu/core)) `GPL-3.0` `PHP`
- [ILIAS](https://www.ilias.de) - ILIAS是一个能够应对任何挑战的学习管理系统。 ([Demo](https://demo.ilias.de), [Source Code](https://github.com/ILIAS-eLearning/ILIAS)) `GPL-3.0` `PHP`
- [INGInious](https://inginious.org/?lang=en) - 智能评分系统，允许对学生编写的代码进行安全且自动化的测试。 ([Source Code](https://github.com/UCL-INGI/INGInious), [Clients](https://github.com/UCL-INGI/INGInious-plugins)) `AGPL-3.0` `Python/Docker`
- [Moodle](https://moodle.org/) - Moodle 是一个拥有全球最大开源社区之一的学习和课程平台。 ([Demo](https://moodle.org/demo/), [Source Code](https://git.moodle.org/gw)) `GPL-3.0` `PHP`
- [Open eClass](https://www.openeclass.org/) - Open eClass是一种先进的电子学习解决方案，可以增强教学和学习过程。 ([Demo](https://demo.openeclass.org/), [Source Code](https://github.com/gunet/openeclass)) `GPL-2.0` `PHP`
- [OpenOLAT](https://www.openolat.com/?lang=en) - OpenOLAT是一个基于Web的学习管理系统，用于教学、教育、评估和交流。 ([Demo](https://learn.olat.com), [Source Code](https://github.com/OpenOLAT/OpenOLAT)) `Apache-2.0` `Java`
- [RELATE](https://documen.tician.de/relate/) - RELATE是一个基于Web的课程软件包，包括灵活的规则、统计、多课程支持和课程日历等功能。 ([Source Code](https://github.com/inducer/relate)) `MIT` `Python`
- [RosarioSIS](https://www.rosariosis.org/) - RosarioSIS，用于学校管理的免费学生信息系统。 ([Demo](https://www.rosariosis.org/demo/), [Source Code](https://gitlab.com/francoisjacquet/rosariosis/)) `GPL-2.0` `PHP`


### 家谱研究

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[家谱软件](https://en.wikipedia.org/wiki/Genealogy_software)，用于记录、组织和发布家谱数据。

- [Genea.app](https://www.genea.app/) - Genea是一个隐私设计和开源工具，任何人都可以用来编写或编辑他们的家谱。数据以GEDCOM格式存储，所有处理在浏览器中完成。 ([Source Code](https://github.com/genea-app/genea-app)) `MIT` `Javascript`
- [GeneWeb](https://geneweb.tuxfamily.org/wiki/GeneWeb) - 家谱学软件。它配备了一个Web界面，可脱机使用或作为Web服务使用。 ([Demo](https://demo.geneweb.tuxfamily.org/gw7/), [Source Code](https://github.com/geneweb/geneweb)) `GPL-2.0` `OCaml`
- [Gramps Web](https://gramps-project.github.io/web/) - 用于协同基于Gramps的家谱研究的Web应用，与Gramps开源家谱研究桌面应用兼容。 ([Demo](https://gramps-project.github.io/web), [Source Code](https://github.com/gramps-project/gramps-webapi)) `AGPL-3.0` `Docker`
- [webtrees](https://www.webtrees.net) - Webtrees是Web上领先的在线协作家谱应用程序。 ([Demo](https://dev.webtrees.net/demo-stable/index.php?ctype=gedcom&ged=demo), [Source Code](https://github.com/fisharebest/webtrees)) `GPL-3.0` `PHP`


### 密码管理器

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[密码管理器](https://en.wikipedia.org/wiki/Password_manager)允许用户存储、生成和管理他们在本地应用程序和在线服务中的密码。

- [Bitwarden](https://bitwarden.com/) `⚠` - 具有Web应用程序、浏览器扩展和移动应用程序的密码管理器。 ([Source Code](https://github.com/bitwarden/server)) `AGPL-3.0` `Docker/C#`
- [Laravel Simple Password Manager](https://github.com/milenmk/Laravel-Simple-Password-Manager) - 简单的密码管理器。 `GPL-3.0` `PHP`
- [Padloc](https://padloc.app/) - 适用于个人和团队的现代开源密码管理器。 ([Source Code](https://github.com/padloc/padloc)) `GPL-3.0` `Nodejs`
- [Passbolt](https://www.passbolt.com/) - 专为在任何Web服务器上以协作方式管理密码而设计的密码管理器，使用MySQL数据库后端。 ([Source Code](https://github.com/passbolt/passbolt_api)) `AGPL-3.0` `PHP/deb/K8S/Docker`
- [PassIt](https://passit.io/) - 简单的密码管理工具，具有按组和用户共享的功能，但没有管理界面。 ([Demo](https://app.passit.io/), [Source Code](https://gitlab.com/passit)) `AGPL-3.0` `Docker/Django`
- [Passky](https://passky.org) - 简单、现代且开源的密码管理器，配有网站、浏览器扩展、Android和桌面应用程序。 ([Demo](https://vault.passky.org), [Source Code](https://github.com/Rabbit-Company/Passky-Server)) `GPL-3.0` `PHP`
- [PassWall](https://github.com/passwall/passwall-server) - 开源密码管理器。 `AGPL-3.0` `Docker`
- [Laravel Simple Password Manager](https://github.com/milenmk/Laravel-Simple-Password-Manager) - 简单的密码管理器。 `GPL-3.0` `PHP`
- [Psono](https://psono.com/) - 一款专为团队提供完整功能的有前途的密码管理器。 ([Demo](https://www.psono.pw), [Source Code](https://gitlab.com/psono)) `Apache-2.0` `Python`
- [Teampass](https://teampass.net/) - 专为以协作方式管理密码而设计的密码管理器。使用一个对称密钥加密所有共享/团队密码，并在服务器端以文件和数据库的形式存储。适用于任何 Apache、MySQL 和 PHP 服务器。 ([Source Code](https://github.com/nilsteampassnet/TeamPass)) `GPL-3.0` `PHP`
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) - 用Rust编写的轻量级Bitwarden服务器API实现。 `GPL-3.0` `Rust/Docker`


### 工单

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[帮助台](https://en.wikipedia.org/wiki/Help_desk_software)、[缺陷](https://en.wikipedia.org/wiki/Bug_tracking_system)和[问题](https://en.wikipedia.org/wiki/Issue_tracking_system)跟踪软件，用于跟踪用户请求、缺陷和缺失的功能。

_Related: [任务管理和待办清单](#任务管理和待办清单), [软件开发 - 项目管理](#软件开发---项目管理)_

- [Bugzilla](https://www.bugzilla.org/) - 通用缺陷跟踪器和测试工具，最初由Mozilla项目开发和使用。 `MPL-2.0` `Perl`
- [Erxes](https://erxes.io/install/) - 旨在帮助企业吸引更多参与的客户的营销、销售和客户服务平台。 ([Source Code](https://github.com/erxes/erxes)) `GPL-3.0` `Docker`
- [FreeScout](https://github.com/freescout-helpdesk/freescout) - Help Scout 的开源克隆版：基于电子邮件的客户支持应用、帮助台和共享邮箱。 `AGPL-3.0` `PHP/Docker`
- [GlitchTip](https://glitchtip.com) - 开源错误跟踪应用。GlitchTip收集您的应用报告的错误。 ([Source Code](https://gitlab.com/glitchtip/glitchtip)) `MIT` `Python/Docker/K8S`
- [Iguana](https://github.com/iguana-project/iguana) - Iguana是一个带有看板板的开源问题管理系统。 `CC-BY-SA-4.0` `Python/Docker`
- [ITFlow](https://itflow.org) - 面向MSPs（托管服务提供商）的客户端IT文档、工单、发票和会计Web应用。 ([Demo](https://demo.itflow.org), [Source Code](https://github.com/itflow-org/itflow)) `GPL-3.0` `PHP`
- [MantisBT](https://www.mantisbt.org/) - 自托管的缺陷跟踪器，最适合软件开发。 ([Demo](https://www.mantisbt.org/bugs/my_view_page.php), [Source Code](https://github.com/mantisbt/mantisbt)) `GPL-2.0` `PHP`
- [osTicket](https://osticket.com/) - 在一个地方管理、组织和归档所有您的支持请求和响应。 ([Source Code](https://github.com/osTicket/osTicket)) `GPL-2.0` `PHP`
- [OTOBO](https://otobo.de/en/) - 灵活的基于Web的票务系统，用于客户服务、帮助台和IT服务管理。 ([Demo](https://otobo.de/en/open-source-ticketing-system/#demos), [Source Code](https://github.com/RotherOSS/otobo)) `GPL-3.0` `Perl/Docker`
- [Request Tracker](https://www.bestpractical.com/rt/) - 一款企业级问题跟踪系统。 ([Source Code](https://github.com/bestpractical/rt)) `GPL-2.0` `Perl`
- [Roundup Issue Tracker](https://www.roundup-tracker.org/) - 一个易于使用和安装的问题跟踪系统，提供命令行、Web、REST、XML-RPC 和电子邮件接口。设计时考虑了灵活性 - 不仅仅是另一个缺陷跟踪器。 ([Source Code](https://www.roundup-tracker.org/code.html)) `MIT/ZPL-2.0` `Python/Docker`
- [Trudesk](https://trudesk.io/) - Trudesk是一款开源的帮助台/工单解决方案。 ([Source Code](https://github.com/polonel/trudesk)) `Apache-2.0` `Nodejs/Docker`
- [Zammad](https://zammad.org/) - 易于使用但功能强大的开源支持和工单系统。 ([Source Code](https://github.com/zammad/zammad)) `AGPL-3.0` `Ruby/deb`


### 库存管理

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[库存管理软件](https://en.wikipedia.org/wiki/Inventory_management_software)。

_Related: [资金、预算和管理](#资金、预算和管理), [资源规划](#资源规划)_

_See also: [awesome-sysadmin/IT资产管理](https://github.com/awesome-foss/awesome-sysadmin#it-asset-management)_

- [Homebox Inventory](https://hay-kot.github.io/homebox/) - 专为家庭用户设计的库存和组织系统，注重简单性和易用性。 ([Demo](https://homebox.fly.dev/), [Source Code](https://github.com/hay-kot/homebox)) `AGPL-3.0` `Docker`
- [Inventaire](https://inventaire.io/welcome) - 协作资源映射项目，目前仅专注于使用Wikidata和ISBN探索图书映射。 ([Source Code](https://github.com/inventaire/inventaire)) `AGPL-3.0` `Nodejs`
- [Inventree](https://inventree.readthedocs.io/en/latest/) - InvenTree是一个开源的库存管理系统，提供直观的零件管理和库存控制。 ([Demo](https://inventree.org/demo), [Source Code](https://github.com/inventree/InvenTree)) `MIT` `Python`
- [Shelf](https://www.shelf.nu) - 团队喜欢清晰度的资产和设备跟踪软件。Shelf 是一个资产数据库和 QR 资产标签生成器，让您能够在不同地点创建、管理和查看您的资产。无限资产，永久免费使用。 ([Source Code](https://github.com/Shelf-nu/shelf.nu)) `AGPL-3.0` `Nodejs`


### 投票和事件

**[`^        back to top        ^`](#Awesome-Selfhosted)**

用于组织[投票](https://en.wikipedia.org/wiki/Opinion_poll)和[事件](https://en.wikipedia.org/wiki/Event)的软件。

_Related: [预订和日程安排](#预订和日程安排)_

- [Bitpoll](https://github.com/fsinfuhh/Bitpoll) - 用于安排会议和一般投票的Web应用程序。 ([Demo](https://bitpoll.de/)) `GPL-3.0` `Docker/Python`
- [Christmas Community](https://github.com/Wingysam/Christmas-Community) - 创建一个简单的地方，让您的整个家庭用于查找人们想要的礼物，并避免重复赠送。 `AGPL-3.0` `Docker/Nodejs`
- [Claper](https://claper.co/) - 与观众互动的终极工具（替代Slido、AhaSlides和Mentimeter）。 ([Source Code](https://github.com/ClaperCo/Claper)) `GPL-3.0` `Elixir/Docker`
- [ClearFlask](https://clearflask.com) - 用于管理反馈并优先处理公共路线图的社区反馈工具（替代Canny、UserVoice、Upvoty）。 ([Demo](https://product.clearflask.com), [Source Code](https://github.com/clearflask/clearflask)) `AGPL-3.0` `Docker`
- [docassemble](https://docassemble.org/) - 一个用于引导性访谈和文档生成的免费、开源的专家系统，基于Python、YAML和Markdown。 ([Demo](https://demo.docassemble.org/run/legal), [Source Code](https://github.com/jhpyle/docassemble)) `MIT` `Docker/Python`
- [Fider](https://fider.io) - 开放平台，用于收集和优先处理反馈（与UserVoice的替代方案）。 ([Demo](https://demo.fider.io), [Source Code](https://github.com/getfider/fider)) `MIT` `Docker`
- [Framadate](https://framadate.org/abc/) - 在线服务，快速轻松地安排约会或做决定：创建投票，定义选择的日期或主题，将投票链接发送给您的朋友或同事，讨论并做出决定。 ([Demo](https://framadate.org/aqg259dth55iuhwm), [Source Code](https://framagit.org/framasoft/framadate?)) `CECILL-B` `PHP`
- [Gancio](https://gancio.org/) - 本地社区共享日程表。 ([Source Code](https://framagit.org/les/gancio)) `AGPL-3.0` `Nodejs`
- [hitobito](https://hitobito.com/en) - 用于管理复杂的组织层次结构，包括成员、事件等的Web应用程序。 ([Demo](https://demo.hitobito.com/en/users/sign_in), [Source Code](https://github.com/hitobito/hitobito)) `AGPL-3.0` `Ruby`
- [Input](https://getinput.co) - 一个以隐私为重点的、无代码、开源的表单构建器，旨在简单和品牌一致性设计。 ([Source Code](https://github.com/deck9/input)) `AGPL-3.0` `PHP/Nodejs/Docker`
- [LimeSurvey](https://www.limesurvey.org) - 功能丰富的开源基于Web的调查软件。支持广泛的调查逻辑。 ([Demo](https://demo.limesurvey.org), [Source Code](https://github.com/LimeSurvey/LimeSurvey)) `GPL-2.0` `PHP`
- [Meetable](https://events.indieweb.org) - 一个极简的事件聚合器。 ([Source Code](https://github.com/aaronpk/Meetable)) `MIT` `PHP`
- [Mobilizon](https://mobilizon.org) - 一个联邦工具，帮助您查找、创建和组织事件和群组。 ([Demo](https://demo.mobilizon.org/), [Source Code](https://framagit.org/framasoft/mobilizon/)) `GPL-3.0` `Elixir/Docker`
- [Open Event Server](https://github.com/fossasia/open-event-server) - 使组织者能够管理从音乐会到会议和聚会的各种活动。 `GPL-3.0` `Python/Docker`


### 搜索引擎

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[搜索引擎](https://en.wikipedia.org/wiki/Search_engine_(computing))是设计用于帮助找到存储在计算机系统上的信息的[信息检索系统](https://en.wikipedia.org/wiki/Information_retrieval)。这包括[网络搜索引擎](https://en.wikipedia.org/wiki/Web_search_engine)。

- [Fess](https://fess.codelibs.org/) - Fess是一个非常强大且易于部署的企业搜索服务器。 ([Demo](https://search.n2sm.co.jp/), [Source Code](https://github.com/codelibs/fess)) `Apache-2.0` `Java/Docker`
- [Hound](https://github.com/hound-search/hound) - 极速的代码搜索，轻松实现。 `MIT` `Go/Docker`
- [Jina](https://github.com/jina-ai/jina/) - 面向任何类型数据的云原生神经搜索框架。 `Apache-2.0` `Python/Docker`
- [LibreX](https://github.com/hnhx/librex) `⚠` - 框架和 JavaScript-free 的隐私尊重的元搜索引擎。 `AGPL-3.0` `PHP/Docker`
- [Manticore Search](https://github.com/manticoresoftware/manticoresearch/) - 全文搜索和数据分析，对于小、中、大数据具有快速的响应时间（替代Elasticsearch）。 `GPL-2.0` `Docker/deb/C++`
- [MeiliSearch](https://www.meilisearch.com) - 极其相关、即时且容错的全文搜索API。 ([Source Code](https://github.com/meilisearch/MeiliSearch)) `MIT` `Rust/Docker/deb`
- [OpenSearch](https://opensearch.org) - 开源分布式和RESTful搜索引擎。 ([Source Code](https://github.com/opensearch-project/OpenSearch)) `Apache-2.0` `Java/Docker/K8S/deb`
- [SearXNG](https://docs.searxng.org/) `⚠` - 互联网元搜索引擎，汇总来自各种搜索服务和数据库的结果（Searx 的分支）。 ([Source Code](https://github.com/searxng/searxng/)) `AGPL-3.0` `Python/Docker`
- [sist2](https://github.com/simon987/sist2) - 高速文件系统索引和搜索工具。 `GPL-3.0` `C/Docker`
- [Sosse](https://sosse.readthedocs.io/en/stable/) - Selenium基础的搜索引擎和网络爬虫，具有离线存档功能。 ([Source Code](https://gitlab.com/biolds1/sosse)) `AGPL-3.0` `Python/Docker`
- [Typesense](https://typesense.org) - 高速、容错的开源搜索引擎，专为开发者的愉悦和易用性而优化。 ([Source Code](https://github.com/typesense/typesense)) `GPL-3.0` `C++/Docker/K8S/deb`
- [Websurfx](https://github.com/neon-mmd/websurfx) `⚠` - 在保护隐私和安全的前提下，汇总其他搜索引擎的结果（元搜索引擎），无广告。它速度极快，提供高度可定制性（SearX的替代品）。 `AGPL-3.0` `Rust/Docker`
- [Whoogle](https://github.com/benbusby/whoogle-search) `⚠` - 一个自托管、无广告、尊重隐私的元搜索引擎。 `MIT` `Python`
- [Yacy](https://yacy.net/en/index.html) - 基于对等、去中心化的搜索引擎服务器。 ([Source Code](https://github.com/yacy/yacy_search_server)) `GPL-2.0` `Java/Docker/K8S`
- [ZincSearch](https://zincsearch.com) - 需要最少资源的搜索引擎（Elasticsearch的替代品）。 ([Demo](https://github.com/zinclabs/zinc#playground-server), [Source Code](https://github.com/zincsearch/zincsearch)) `Apache-2.0` `Go/Docker/K8S`


### 数据库管理

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[数据库](https://en.wikipedia.org/wiki/Database)管理的Web界面。包括用于数据库分析和可视化的工具。

_Related: [分析](#分析), [自动化](#自动化)_

_See also: [dbdb.io - 数据库之数据库](https://dbdb.io/)_

- [Adminer](https://www.adminer.org/) - 在一个单独的 PHP 文件中进行数据库管理。支持 MySQL、MariaDB、PostgreSQL、SQLite、MS SQL、Oracle、Elasticsearch、MongoDB 等数据库。 ([Source Code](https://github.com/vrana/adminer/)) `Apache-2.0/GPL-2.0` `PHP`
- [Azimutt](https://azimutt.app) - 面向真实世界数据库（庞大且混乱）的可视化数据库探索工具。可以探索数据库模式以及数据，记录它们，扩展它们，甚至进行分析和指导。 ([Demo](https://azimutt.app/gallery/gospeak), [Source Code](https://github.com/azimuttapp/azimutt)) `MIT` `Elixir/Nodejs/Docker`
- [Baserow](https://baserow.io/) - 在没有技术经验的情况下创建自己的数据库（与Airtable类似的替代品）。 ([Source Code](https://gitlab.com/bramw/baserow)) `MIT` `Docker`
- [Bytebase](https://www.bytebase.com/) - 为 DevOps 团队提供安全的数据库模式更改和版本控制，支持 MySQL、PostgreSQL、TiDB、ClickHouse 和 Snowflake。 ([Demo](https://demo.bytebase.com), [Source Code](https://github.com/bytebase/bytebase)) `MIT` `Docker/K8S/Go`
- [Chartbrew](https://chartbrew.com) - Web应用程序，可以直接连接到数据库和API，使用数据创建漂亮的图表。 ([Demo](https://app.chartbrew.com/live-demo), [Source Code](https://github.com/chartbrew/chartbrew)) `MIT` `Nodejs/Docker`
- [CloudBeaver](https://cloudbeaver.io/) - 数据库的自托管管理，支持PostgreSQL、MySQL、SQLite等。是DBeaver的Web/托管版本。 ([Source Code](https://github.com/dbeaver/cloudbeaver)) `Apache-2.0` `Docker`
- [Databunker](https://databunker.org/) - 网络化、自托管、符合 GDPR 标准的安全数据库，用于存储个人数据或 PII。 ([Source Code](https://github.com/securitybunker/databunker)) `MIT` `Docker`
- [Datasette](https://datasette.io/) - 一个用于探索和发布数据的开源多功能工具，支持轻松导入和导出以及数据库管理。 ([Demo](https://global-power-plants.datasettes.com/global-power-plants/global-power-plants), [Source Code](https://github.com/simonw/datasette)) `Apache-2.0` `Python/Docker`
- [Directus](https://directus.io/) - 一个用于SQL数据库的即时应用和API。Directus为开发人员提供了一个实时的GraphQL+REST API，可包装新的或现有的SQL数据库，并为非技术用户提供了直观的管理应用。 ([Source Code](https://github.com/directus/directus)) `GPL-3.0` `Nodejs`
- [Evidence](https://evidence.dev) - Evidence是一个基于代码的商业智能工具。使用SQL和Markdown编写报告，它们会呈现为一个网站。 ([Source Code](https://github.com/evidence-dev/evidence)) `MIT` `Nodejs`
- [Limbas](https://www.limbas.com/en/) - Limbas是一个用于创建基于数据库的业务应用程序的数据库框架。作为图形数据库前端，它能够高效处理数据库存储并灵活开发舒适的数据库应用程序。 ([Source Code](https://github.com/limbas/limbas)) `GPL-2.0` `PHP`
- [Mathesar](https://mathesar.org/) - 为所有技术水平的用户提供直观的协作数据管理界面。基于Postgres构建 - 连接现有数据库或设置新数据库。 ([Demo](https://demo.mathesar.org/), [Source Code](https://github.com/centerofci/mathesar)) `GPL-3.0` `Docker/Python`
- [MindsDB](https://mindsdb.com/) - MindsDB 是一个开源的自托管 AI 层，适用于现有数据库，可以让您轻松地使用标准查询开发、训练和部署最先进的机器学习模型。 ([Source Code](https://github.com/mindsdb/mindsdb)) `GPL-3.0` `Docker/Python`
- [NocoDB](https://www.nocodb.com/) - 无代码平台，将任何数据库转换为智能电子表格（Airtable或Smartsheet的替代品）。 ([Source Code](https://github.com/nocodb/nocodb)) `GPL-3.0` `Nodejs/Docker`
- [WebDB](https://webdb.app) - 高效的数据库集成开发环境（IDE）。 ([Demo](https://demo.webdb.app/), [Source Code](https://gitlab.com/web-db/app)) `AGPL-3.0` `Docker`


### 文件传输 - 分布式文件系统

**[`^        back to top        ^`](#Awesome-Selfhosted)**

网络分布式文件系统。

**Please visit [awesome-sysadmin/分布式文件系统](https://github.com/awesome-foss/awesome-sysadmin#distributed-filesystems)**



### 文件传输 - 单击和拖放上传

**[`^        back to top        ^`](#Awesome-Selfhosted)**

用于分享一次性/短期/临时文件的简化文件服务器，提供单击或[拖放](https://en.wikipedia.org/wiki/Drag_and_drop)上传功能。

- [ass](https://github.com/tycrek/ass) - 优秀的自托管 ShareX 服务器。可用于客户端，如 ShareX（Windows）、Flameshot（Linux）和 MagicCap（Linux、macOS）。 `ISC` `Nodejs/Docker`
- [elixire](https://elixi.re) - 简单而先进的截图上传和链接缩短服务。 ([Source Code](https://gitlab.com/elixire/elixire), [Clients](https://gitlab.com/elixire/elixiremanager)) `AGPL-3.0` `Python`
- [Files Sharing](https://github.com/axeloz/filesharing) - 基于独特和临时链接的开源自托管文件共享应用程序。 `GPL-3.0` `PHP/Docker`
- [FileShelter](https://github.com/epoupon/fileshelter) - FileShelter 是一个自托管软件，使您能够轻松在互联网上共享文件。 `GPL-3.0` `C++/deb`
- [Gokapi](https://github.com/Forceu/gokapi) - 用于共享文件的轻量级服务器，文件在设定的下载次数或天数后过期。类似于已停用的Firefox Send，区别在于只允许管理员上传文件。 `GPL-3.0` `Go/Docker`
- [goploader](https://github.com/Depado/goploader) - 使用服务器端加密的简便文件共享，兼容curl/httpie/wget。 `MIT` `Go`
- [GoSƐ](https://github.com/stv0g/gose) - GoSƐ是一个以可伸缩性和简单性为重点的现代文件上传器。它仅依赖于S3存储后端，因此可以在水平方向上扩展，无需额外的数据库或缓存。 ([Demo](https://gose.0l.de)) `Apache-2.0` `Go/Docker`
- [lufi](https://framagit.org/fiat-tux/hat-softwares/lufi) - 让我们上传那个文件，客户端加密。 ([Demo](https://demo.lufi.io), [Source Code](https://framagit.org/fiat-tux/hat-softwares/lufi/tree/master)) `AGPL-3.0` `Perl`
- [OnionShare](https://github.com/onionshare/onionshare) - 安全匿名地共享任意大小的文件。 `GPL-2.0` `Python/deb`
- [Pairdrop](https://github.com/schlagmichdoch/pairdrop) - 在浏览器中进行本地文件共享，灵感来自于Apple的AirDrop（Snapdrop的分支）。 `GPL-3.0` `Docker`
- [PicoShare](https://pico.rocks) - 一个极简、易于托管的服务，用于共享图片和其他文件。 ([Demo](https://demo.pico.rocks), [Source Code](https://github.com/mtlynch/picoshare)) `AGPL-3.0` `Go/Docker`
- [Picsur](https://github.com/CaramelFur/Picsur) - 一个简单的图像托管平台，可以轻松托管、编辑和共享图像。 `GPL-3.0` `Docker`
- [PictShare](https://www.pictshare.net/) - PictShare 是一个多语言、开源的图像托管服务，提供简单的调整大小和上传 API。 ([Source Code](https://github.com/HaschekSolutions/pictshare)) `Apache-2.0` `PHP/Docker`
- [Pingvin Share](https://github.com/stonith404/pingvin-share) - 一款自托管的文件共享平台，兼具轻巧和美观，非常适合无缝高效的文件共享。 ([Demo](https://pingvin-share.dev.eliasschneider.com)) `BSD-2-Clause` `Docker/Nodejs`
- [Plik](https://github.com/root-gg/plik) - Plik是一个可伸缩且用户友好的临时文件上传系统。 ([Demo](https://plik.root.gg/)) `MIT` `Go/Docker`
- [ProjectSend](https://www.projectsend.org/) - 上传文件并将其分配给您创建的特定客户端。向您的客户授予对这些文件的访问权限。 ([Source Code](https://github.com/projectsend/projectsend)) `GPL-2.0` `PHP`
- [PsiTransfer](https://github.com/psi-4ward/psitransfer) - 简单的开源自托管文件共享解决方案，具有强大的上传/下载恢复和密码保护功能。 `BSD-2-Clause` `Nodejs`
- [QuickShare](https://github.com/ihexxa/quickshare) - 在不同设备之间进行快速简单的文件共享。 `LGPL-3.0` `Docker/Go`
- [Sharry](https://github.com/eikek/sharry) - 在经过身份验证和匿名用户之间轻松共享文件（双向共享），支持可恢复的上传和下载。 `GPL-3.0` `Scala/Java/deb/Docker`
- [Shifter](https://github.com/TobySuch/Shifter) - 一个由 Django 驱动的简单的自托管文件共享 Web 应用。 `MIT` `Docker`
- [transfer.sh](https://github.com/dutchcoders/transfer.sh) - 通过命令行轻松共享文件。 `MIT` `Go`
- [Uguu](https://github.com/nokonoko/uguu) - 存储文件并在一定时间后删除。 `MIT` `PHP`
- [Uploady](https://github.com/farisc0de/Uploady) - Uploady是一个简单的文件上传脚本，支持多文件上传。 `MIT` `PHP`
- [XBackBone](https://xbackbone.app/) - 一个简单、快速且轻量级的文件管理器，集成了即时共享工具，类似于ShareX（用于Windows的免费开源截图实用工具）。 ([Source Code](https://github.com/SergiX44/XBackBone)) `AGPL-3.0` `PHP/Docker`
- [Zipline](https://github.com/diced/zipline) - 一个轻量级、快速且可靠的文件分享服务器，通常与ShareX一起使用，提供基于React的Web界面和快速的API。 `MIT` `Docker/Nodejs`


### 文件传输 - 基于 Web 的文件管理器

**[`^        back to top        ^`](#Awesome-Selfhosted)**

基于 Web 的[文件管理器](https://en.wikipedia.org/wiki/File_manager)。

_Related: [协同办公](#协同办公)_

- [Apaxy](https://oupala.github.io/apaxy/) - 一款旨在提升浏览 Web 目录体验的主题，使用 mod_autoindex Apache 模块和一些 CSS 来覆盖目录列表的默认样式。 ([Source Code](https://github.com/oupala/apaxy)) `GPL-3.0` `Javascript`
- [copyparty](https://github.com/9001/copyparty) - 便携式文件服务器，支持加速可恢复上传、重复数据删除、WebDAV、FTP、zeroconf、媒体索引、视频缩略图、音频转码和只写文件夹，全部打包在一个文件中，无需强制性依赖。 ([Demo](https://a.ocv.me/pub/demo/)) `MIT` `Python`
- [DirectoryLister](https://www.directorylister.com/) - 简单的基于PHP的目录列表器，列出一个目录及其所有子目录，并允许您在其中导航。 ([Source Code](https://github.com/DirectoryLister/DirectoryLister)) `MIT` `PHP`
- [filebrowser](https://filebrowser.org/) - 带有 Material Design Web 界面的 Web 文件浏览器。 ([Source Code](https://github.com/filebrowser/filebrowser)) `Apache-2.0` `Go`
- [FileGator](https://filegator.io/) - FileGator 是一个强大的多用户文件管理器，具有单页面前端。 ([Demo](https://demo.filegator.io), [Source Code](https://github.com/filegator/filegator)) `MIT` `PHP/Docker`
- [Filestash](https://www.filestash.app/) - 一个 Web 文件管理器，可让您管理数据的任何位置：FTP、SFTP、WebDAV、Git、S3、Minio、Dropbox 或 Google Drive。 ([Demo](https://demo.filestash.app/), [Source Code](https://github.com/mickael-kerjean/filestash)) `AGPL-3.0` `Docker`
- [Gossa](https://github.com/pldubouilh/gossa) - Gossa是一个轻量简单的文件Web服务器。 `MIT` `Go`
- [IFM](https://github.com/misterunknown/ifm) - 单脚本文件管理器。 `MIT` `PHP`
- [mikochi](https://github.com/zer0tonin/Mikochi) - 浏览远程文件夹，上传文件，删除、重命名、下载并流式传输文件到 VLC/mpv。 `MIT` `Go/Docker/K8S`
- [miniserve](https://github.com/svenstaro/miniserve) - 用于通过 HTTP 提供文件和目录的命令行工具。 `MIT` `Rust`
- [ResourceSpace](https://www.resourcespace.com) - ResourceSpace是一款开源数字资产管理软件，是组织数字资产的简单、快速和免费方式。 ([Demo](https://www.resourcespace.com/trial), [Source Code](https://www.resourcespace.com/svn)) `BSD-4-Clause` `PHP`
- [Surfer](https://git.cloudron.io/cloudron/surfer) - 带有 Web 用户界面的简单静态文件服务器，用于管理文件。 `MIT` `Nodejs`
- [TagSpaces](https://www.tagspaces.org/) - TagSpaces 是一款离线、跨平台的文件管理器和组织工具，也可以作为一个笔记应用。该应用的 WebDAV 版本可以安装在 WebDAV 服务器上，如 Nextcloud 或 ownCloud。 ([Demo](https://demo.tagspaces.com), [Source Code](https://github.com/tagspaces/tagspaces)) `AGPL-3.0` `Nodejs`


### 文件传输 - 对象存储和文件服务器

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[对象存储](https://en.wikipedia.org/wiki/Object_storage)是一种将数据管理为对象的计算机数据存储方式，与其他存储架构（如文件系统，将数据管理为文件层次结构，以及块存储，将数据管理为扇区和磁道内的块）相对立。

- [GarageHQ](https://garagehq.deuxfleurs.fr/) - 一种开源的地理分布式存储服务，您可以自主托管以满足多种需求 - 兼容S3。 ([Source Code](https://git.deuxfleurs.fr/Deuxfleurs/garage)) `AGPL-3.0` `Docker/Rust`
- [Minio](https://min.io/) - Minio 是一个与 Amazon S3 API 兼容的开源对象存储服务器。 ([Source Code](https://github.com/minio/minio)) `AGPL-3.0` `Go/Docker/K8S`
- [SeaweedFS](https://github.com/seaweedfs/seaweedfs) - SeaweedFS 是一个开源的分布式文件系统，支持 WebDAV、S3 API、FUSE 挂载、HDFS 等，针对大量小文件进行优化，易于扩展容量。 `Apache-2.0` `Go`
- [SFTPGo](https://github.com/drakkan/sftpgo) - 灵活、功能齐全且高度可配置的 SFTP 服务器，支持可选的 FTP/S 和 WebDAV。 `AGPL-3.0` `Go/deb/Docker`
- [Zenko CloudServer](https://www.zenko.io/cloudserver) - Zenko CloudServer，一个处理Amazon S3协议的开源服务器实现。 ([Source Code](https://github.com/scality/cloudserver)) `Apache-2.0` `Docker/Nodejs`
- [ZOT OCI Registry](https://zotregistry.dev) - A production-ready vendor-neutral OCI-native container image registry. ([Demo](https://zothub.io), [Source Code](https://github.com/project-zot/zot)) `Apache-2.0` `Go/Docker`
- [ZOT OCI Registry](https://zotregistry.dev) - A production-ready vendor-neutral OCI-native container image registry. ([Demo](https://zothub.io), [Source Code](https://github.com/project-zot/zot)) `Apache-2.0` `Go/Docker`


### 文件传输 - 点对点文件共享

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[点对点文件共享](https://en.wikipedia.org/wiki/Peer-to-peer_file_sharing)是使用[点对点](https://en.wikipedia.org/wiki/Peer-to-peer)网络技术分发和[共享](https://en.wikipedia.org/wiki/File_sharing)数字媒体的过程。

- [bittorrent-tracker](https://webtorrent.io/) - 简单、强大的BitTorrent追踪器（客户端和服务器）实现。 ([Source Code](https://github.com/webtorrent/bittorrent-tracker)) `MIT` `Nodejs`
- [Dat Project](https://dat-ecosystem.org/) - 由庞大的模块生态系统构建的强大的去中心化文件共享应用程序。 ([Source Code](https://github.com/datproject)) `MIT` `Nodejs`
- [Deluge](https://deluge-torrent.org/) - 轻量级、跨平台的 BitTorrent 客户端。 ([Source Code](https://git.deluge-torrent.org/deluge/tree/?h=develop)) `GPL-3.0` `Python/deb`
- [instant.io](https://github.com/webtorrent/instant.io) - 通过WebTorrent进行的流式文件传输。 ([Demo](https://instant.io)) `MIT` `Nodejs`
- [qBittorrent](https://www.qbittorrent.org/) - 免费的跨平台比特Torrent客户端，具有功能丰富的Web UI，可进行远程访问。 ([Source Code](https://github.com/qbittorrent/qBittorrent)) `GPL-2.0` `C++`
- [Send](https://github.com/timvisee/send) - 简单、私密、端到端加密的临时文件分享，最初由 Mozilla 构建。 ([Clients](https://github.com/timvisee/send#clients)) `MPL-2.0` `Nodejs/Docker`
- [Transmission](https://transmissionbt.com/) - 快速、简便、免费的BitTorrent客户端。 ([Source Code](https://github.com/transmission/transmission)) `GPL-3.0` `C++/deb`


### 文件传输和同步

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[文件传输](https://en.wikipedia.org/wiki/File_transfer)、[共享](https://en.wikipedia.org/wiki/File_sharing)和[同步软件](https://en.wikipedia.org/wiki/File_synchronization)。

_Related: [协同办公](#协同办公)_

- [Git Annex](https://git-annex.branchable.com/) - 在计算机、服务器和外部驱动器之间进行文件同步。 ([Source Code](https://git.joeyh.name/index.cgi/git-annex.git/)) `GPL-3.0` `Haskell`
- [Kinto](https://kinto.readthedocs.org) - Kinto是一个具有同步和共享功能的极简JSON存储服务。 ([Source Code](https://github.com/Kinto)) `Apache-2.0` `Python`
- [Nextcloud](https://nextcloud.com/) - 从任何设备按照您的方式访问和共享您的文件、日历、联系人、邮件以及[更多](https://apps.nextcloud.com/)。 ([Demo](https://try.nextcloud.com/), [Source Code](https://github.com/nextcloud/server)) `AGPL-3.0` `PHP/deb`
- [OpenSSH SFTP server](https://www.openssh.com/) - 安全文件传输程序。 ([Source Code](https://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.bin/ssh/)) `BSD-2-Clause` `C/deb`
- [ownCloud](https://owncloud.org/) - 一体化解决方案，用于保存、同步、查看、编辑和共享文件、日历、通讯录等。 ([Source Code](https://github.com/owncloud/core), [Clients](https://github.com/owncloud/core/wiki/Apps)) `AGPL-3.0` `PHP/Docker/deb`
- [Peergos](https://peergos.org) - 安全而私密的在线空间，您可以在其中存储、共享和查看照片、视频、音乐和文档。还包括日历、新闻订阅、任务列表、聊天和电子邮件客户端。 ([Source Code](https://github.com/Peergos)) `AGPL-3.0` `Java`
- [Pydio](https://pydio.com/) - 将任何Web服务器转变为强大的文件管理系统，并作为主流云存储提供商的替代品。 ([Demo](https://pydio.com/en/demo), [Source Code](https://github.com/pydio/cells)) `AGPL-3.0` `Go`
- [Samba](https://www.samba.org/) - Samba 是用于 Linux 和 Unix 的标准 Windows 互操作性程序套件。它为所有使用 SMB/CIFS 协议的客户端提供安全、稳定和快速的文件和打印服务。 ([Source Code](https://git.samba.org/samba.git/)) `GPL-3.0` `C`
- [Seafile](https://www.seafile.com/en/home/) - 主要面向团队和组织的文件托管和共享解决方案。 ([Source Code](https://github.com/haiwen/seafile)) `GPL-2.0/GPL-3.0/AGPL-3.0/Apache-2.0` `C`
- [Syncthing](https://syncthing.net/) - Syncthing 是一个开源的点对点文件同步工具。 ([Source Code](https://github.com/syncthing/syncthing)) `MPL-2.0` `Go/Docker/deb`
- [Unison](https://www.cis.upenn.edu/~bcpierce/unison/) - Unison是一款用于OSX、Unix和Windows的文件同步工具。 ([Source Code](https://github.com/bcpierce00/unison)) `GPL-3.0` `deb/OCaml`


### 文档管理

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[文档管理系统](https://en.wikipedia.org/wiki/Document_management_system)（DMS）是用于接收、跟踪、管理和存储文档以减少纸张使用的系统。

- [DOCAT](https://github.com/docat-org/docat) - 托管您的文档。简单。有版本。时尚。 `MIT` `Python/Docker`
- [DocKing](https://docking.shipsaas.tech) - 文档管理服务/微服务，处理模板并在一个地方以 PDF 格式呈现它们。 ([Demo](https://docking-demo.shipsaas.tech/console), [Source Code](https://github.com/shipsaas/docking)) `MIT` `PHP/Nodejs/Docker`
- [Docspell](https://docspell.org) - 自动标记文档组织和归档系统。 ([Source Code](https://github.com/eikek/docspell)) `GPL-3.0` `Scala/Java/Docker`
- [Docuseal](https://www.docuseal.co) - 创建、填写和签署数字文档（DocuSign 的替代品）。 ([Demo](https://demo.docuseal.tech/), [Source Code](https://github.com/docusealco/docuseal)) `AGPL-3.0` `Docker`
- [EveryDocs](https://github.com/jonashellmann/everydocs-core) - 一个简单的私人使用的文档管理系统，具有基本功能，可以在数字环境中组织您的文档。 `GPL-3.0` `Docker/Ruby`
- [I, Librarian](https://i-librarian.net) - I, Librarian可以整理PDF论文和办公文件。它为工业和学术界的学生和研究团队提供了许多额外的功能。 ([Demo](https://i-librarian.net/demo/), [Source Code](https://github.com/mkucej/i-librarian-free)) `GPL-3.0` `PHP`
- [Paperless-ngx](https://docs.paperless-ngx.com/) - 使用改进的界面扫描、索引和存档所有纸质文档（Paperless的分支）。 ([Demo](https://demo.paperless-ngx.com/), [Source Code](https://github.com/paperless-ngx/paperless-ngx)) `GPL-3.0` `Python/Docker`
- [Papermerge](https://papermerge.com) - 专注于扫描文档（电子档案）的开源文档管理系统。提供类似于Dropbox/Google Drive的文件浏览功能。OCR、全文搜索、文本叠加/选择等功能。 ([Source Code](https://github.com/ciur/papermerge)) `Apache-2.0` `Python/Docker/K8S`
- [paper{s}pace](https://dedicatedcode.com/projects.html) - 小型网络应用程序，用于管理所有离线文档。为您的文档提供可搜索的存储，并提醒您即将到来的任务。 ([Source Code](https://gitlab.com/dedicatedcode/paperspace)) `MIT` `Java`
- [Stirling-PDF](https://github.com/Frooodle/Stirling-PDF) - 本地托管的Web应用程序，允许您对PDF文件执行各种操作，如合并、拆分、文件转换和OCR。 `Apache-2.0` `Docker/Java`
- [Teedy](https://teedy.io/) - 一款轻量级的文档管理系统，具备大型昂贵解决方案（如 SismicsDocs）所期望的所有功能。 ([Demo](https://demo.teedy.io/), [Source Code](https://github.com/sismics/docs)) `GPL-2.0` `Docker/Java`


### 文档管理 - 图书馆自动化系统（ILS）

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[图书馆自动化系统](https://en.wikipedia.org/wiki/Integrated_library_system)是用于图书馆的企业资源规划系统，用于跟踪所拥有的物品、已下订单、已支付的账单以及借阅的读者。

_Related: [内容管理系统（CMS）](#内容管理系统（cms）), [档案和数字保存（DP）](#档案和数字保存（dp）)_

- [Evergreen](https://evergreen-ils.org) - 面向图书馆的高度可扩展软件，帮助图书馆用户查找图书馆材料，并帮助图书馆管理、编目和流通这些材料。 ([Source Code](https://github.com/evergreen-library-system/Evergreen)) `GPL-2.0` `PL/pgSQL`
- [Koha](https://koha-community.org/) - 企业级图书馆管理系统，具有采购、流通、编目、标签打印、无网络访问时的脱机流通等模块。 ([Demo](https://koha-community.org/demo/), [Source Code](https://github.com/Koha-Community/Koha)) `GPL-3.0` `Perl`
- [RERO ILS](https://rero21.ch/) - 一款大规模的综合图书馆管理系统，可作为一个 consorital 特性的服务运行，主要用于图书馆网络。包括大多数标准模块（流通、采购、编目等）和基于 Web 的公共和专业界面。 ([Demo](https://ils.test.rero.ch/), [Source Code](https://github.com/rero/rero-ils)) `AGPL-3.0` `Python/Docker`


### 文档管理 - 机构知识库和数字图书馆软件

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[机构知识库](https://en.wikipedia.org/wiki/Institutional_repository)和[数字图书馆](https://en.wikipedia.org/wiki/Digital_library)管理软件。

- [DSpace](https://duraspace.org/dspace/) - 一款即开即用的仓库应用，提供对数字资源的持久访问。 ([Source Code](https://github.com/DSpace/DSpace)) `BSD-3-Clause` `Java`
- [EPrints](https://www.eprints.org/) - 数字文档管理系统，具有灵活的元数据和工作流模型，主要面向学术机构。 ([Demo](http://tryme.demo.eprints-hosting.org/), [Source Code](https://github.com/eprints/eprints)) `GPL-3.0` `Perl`
- [Fedora Commons Repository](https://wiki.lyrasis.org/display/FF/Fedora+Repository+Home) - 用于管理和传播数字内容的强大而模块化的仓库系统，特别适用于数字图书馆和档案馆，既用于访问又用于保存。 ([Source Code](https://github.com/fcrepo/fcrepo)) `Apache-2.0` `Java`
- [InvenioRDM](https://inveniordm.docs.cern.ch/) - 具有出色用户体验的高度可扩展的即插即用研究数据管理平台。 ([Demo](https://inveniordm.web.cern.ch/), [Source Code](https://github.com/inveniosoftware/), [Clients](https://inveniosoftware.org/products/rdm/)) `MIT` `Python`
- [Islandora](https://www.islandora.ca/) - 用于浏览和管理基于Fedora的数字存储库的Drupal模块。 ([Demo](https://sandbox.islandora.ca/), [Source Code](https://github.com/Islandora/islandora)) `GPL-3.0` `PHP`
- [Samvera Hyrax](https://samvera.org/) - Samvera 框架的前端，它本身是一个用于浏览和管理基于 Fedora 的数字仓库的 Ruby on Rails 应用程序。 ([Source Code](https://github.com/samvera/hyrax)) `Apache-2.0` `Ruby`


### 文档管理 - 电子书

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[电子书](https://en.wikipedia.org/wiki/Ebook)图书馆管理软件。

- [Atsumeru](https://atsumeru.xyz) - 免费、开源的自托管漫画/轻小说媒体服务器，支持 Windows、Linux、macOS 和 Android 客户端。 ([Source Code](https://github.com/AtsumeruDev/Atsumeru), [Clients](https://atsumeru.xyz/guides/#how-does-it-work)) `MIT` `Java/Docker`
- [Calibre Web](https://github.com/janeczku/calibre-web) - 使用现有的Calibre数据库，为浏览、阅读和下载电子书提供清晰界面的Web应用。 `GPL-3.0` `Python`
- [Calibre](https://calibre-ebook.com/) - 电子书库管理器，可以查看、转换和编目大多数主要电子书格式的电子书，并提供用于远程客户端的内置Web服务器。 ([Demo](https://calibre-ebook.com/demo), [Source Code](https://launchpad.net/calibre)) `GPL-3.0` `Python/deb`
- [Kavita](https://www.kavitareader.com/) - 跨平台的电子书/漫画/动漫/PDF服务器和Web阅读器，具有用户管理、评分和评论以及元数据支持。 ([Demo](https://wiki.kavitareader.com/en/kavita-demo), [Source Code](https://github.com/Kareadita/Kavita)) `GPL-3.0` `.NET/Docker`
- [Komga](https://komga.org) - 用于漫画/漫画书/BD的媒体服务器，具有API和OPDS支持，现代的Web界面可用于浏览库，以及Web阅读器。 ([Source Code](https://github.com/gotson/komga)) `MIT` `Java/Docker`
- [Librum](https://librumreader.com) - 一款现代的电子书阅读器和图书馆管理器，支持大多数主要的图书格式，可在所有设备上运行，并提供出色的工具来提高生产力。 ([Source Code](https://github.com/Librum-Reader/Librum)) `GPL-3.0` `C++`
- [Stump](https://www.stumpapp.dev) - 一个快速、免费、开源的漫画、漫画和数字书籍服务器，支持 OPDS。 ([Source Code](https://github.com/stumpapp/stump)) `MIT` `Rust`
- [The Epube](https://tt-rss.org/the-epube) - 使用 EPUB.js、Bootstrap 和 Calibre 的自托管 Web EPUB 阅读器。 ([Source Code](https://git.tt-rss.org/fox/the-epube)) `GPL-3.0` `PHP`


### 日历和联系人

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[CalDAV](https://en.wikipedia.org/wiki/CalDAV)和[CardDAV](https://en.wikipedia.org/wiki/CardDAV)协议服务器以及用于[电子日历](https://en.wikipedia.org/wiki/Calendaring_software)、[地址簿](https://en.wikipedia.org/wiki/Address_book)和[联系人管理](https://en.wikipedia.org/wiki/Contact_manager)的网络客户端/界面。

_Related: [协同办公](#协同办公)_

_See also: [CalDAV和CardDAV实现比较 - 维基百科](https://en.wikipedia.org/wiki/Comparison_of_CalDAV_and_CardDAV_implementations)_

- [Baïkal](https://sabre.io/baikal/) - 基于 sabre/dav 的轻量级 CalDAV 和 CardDAV 服务器。 ([Source Code](https://github.com/sabre-io/Baikal)) `GPL-3.0` `PHP`
- [DAViCal](https://www.davical.org/) - 用于日历共享（CalDAV）的服务器，使用 PostgreSQL 数据库作为数据存储。 ([Source Code](https://gitlab.com/davical-project/davical)) `GPL-2.0` `PHP/deb`
- [Davis](https://github.com/tchapi/davis) - 一个简单、可 Docker 化且完全可翻译的 sabre/dav 管理界面，基于 Symfony 5 和 Bootstrap 4，受 Baïkal 启发。 `MIT` `PHP`
- [Etebase (EteSync)](https://www.etebase.com/) - 端到端加密和日志记录的个人信息服务器，支持日历和联系人数据，并提供自己的客户端。 ([Source Code](https://github.com/etesync/server)) `AGPL-3.0` `Python/Django`
- [EteSync Web](https://www.etesync.com/faq/#web-client) - EteSync的官方基于Web的客户端（即他们的Web应用程序）。 ([Demo](https://client.etesync.com/), [Source Code](https://github.com/etesync/etesync-web)) `AGPL-3.0` `Javascript`
- [Manage My Damn Life](https://intri.in/manage-my-damn-life/) - Manage My Damn Life (MMDL)是一个自托管的前端，用于管理您的CalDAV任务和日历。 ([Source Code](https://github.com/intri-in/manage-my-damn-life-nextjs)) `GPL-3.0` `Nodejs/Docker`
- [Radicale](https://radicale.org/) - 简单的日历和联系人服务器，管理开销极低。 ([Source Code](https://github.com/Kozea/Radicale)) `GPL-3.0` `Python/deb`
- [SabreDAV](https://sabre.io/) - 开源的 CardDAV、CalDAV 和 WebDAV 框架与服务器。 ([Source Code](https://github.com/sabre-io/dav)) `MIT` `PHP`
- [Xandikos](https://github.com/jelmer/xandikos) - 开源的CardDAV和CalDAV服务器，具有最小的管理开销，支持Git存储后端。 `GPL-3.0` `Python/deb`


### 时间追踪

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[时间追踪软件](https://en.wikipedia.org/wiki/Time-tracking_software)是一类允许用户记录在任务或项目上花费的时间的计算机软件。

- [ActivityWatch](https://activitywatch.net) - 一款自动跟踪您在设备上花费时间的应用。 ([Source Code](https://github.com/ActivityWatch/activitywatch)) `MPL-2.0` `Python`
- [Kimai](https://www.kimai.org/) - Kimai是一款免费且开源的时间跟踪工具。它会跟踪工作时间，并按需打印出您的活动摘要。 ([Demo](https://www.kimai.org/demo/), [Source Code](https://github.com/kimai/kimai)) `MIT` `PHP`
- [TimeTagger](https://timetagger.app) - 基于交互式时间轴和强大报告的开源时间跟踪工具。 ([Demo](https://timetagger.app/app/demo), [Source Code](https://github.com/almarklein/timetagger)) `GPL-3.0` `Python`
- [Traggo](https://traggo.net/) - Traggo是一款基于标签的时间跟踪工具。在Traggo中，没有任务，只有带有标签的时间跨度。 ([Source Code](https://github.com/traggo/server)) `GPL-3.0` `Docker/Go`


### 杂项

**[`^        back to top        ^`](#Awesome-Selfhosted)**

不属于其他部分的软件。

- [2FAuth](https://github.com/Bubka/2FAuth) - 一个用于管理双因素身份验证（2FA）账户并生成安全代码的网络应用。 ([Demo](https://demo.2fauth.app/)) `AGPL-3.0` `PHP/Docker`
- [AlertHub](https://github.com/Ardakilic/alerthub) `⚠` - AlertHub 是一个简单的工具，用于从 GitHub 发布中接收警报。 `MIT` `Nodejs/Docker`
- [Anchr](https://anchr.io) - Anchr 是一个用于处理互联网上小任务的工具箱，包括书签集、URL 缩短和（加密的）图像上传。 ([Source Code](https://github.com/muety/anchr)) `GPL-3.0` `Nodejs`
- [Apache Solr](https://lucene.apache.org/solr/) - Solr 是基于 Apache Lucene 构建的流行、高速、开源的企业搜索平台。 ([Source Code](https://lucene.apache.org/solr/downloads.html)) `Apache-2.0` `Java/Docker/K8S`
- [asciinema](https://github.com/asciinema/asciinema-server) - 用于托管 asciicasts 的 Web 应用程序。 ([Demo](https://asciinema.org/)) `Apache-2.0` `Elixir/Docker`
- [Baby Buddy](https://github.com/babybuddy/babybuddy) - 帮助照顾者追踪婴儿的睡眠、喂养、换尿布和俯卧时间。 ([Demo](https://demo.baby-buddy.net/login/?next=/)) `BSD-2-Clause` `Python`
- [Bracket](https://evroon.github.io/bracket) - Bracket 是一个灵活的锦标赛系统，可构建锦标赛设置，添加团队，安排比赛，跟踪比分，并实时向公众展示排名。 ([Source Code](https://github.com/evroon/bracket)) `MIT` `Docker/Nodejs`
- [CapRover](https://caprover.com/) - 在几分钟内构建你自己的平台即服务（PaaS）。 ([Demo](https://captain.server.demo.caprover.com/#/login), [Source Code](https://github.com/caprover/caprover)) `Apache-2.0` `Docker/Nodejs`
- [Cerbos](https://cerbos.dev) - 一个自托管的、开源的用户授权层，适用于您的应用程序。 ([Demo](https://play.cerbos.dev), [Source Code](https://github.com/cerbos/cerbos)) `Apache-2.0` `Go/deb/Docker/K8S`
- [Cloudlog](https://magicbug.co.uk/cloudlog/) - Cloudlog是一个自托管的PHP应用，允许您记录您的业余无线电联系。 ([Source Code](https://github.com/magicbug/cloudlog)) `MIT` `PHP/Docker`
- [CUPS](https://www.cups.org/) - CUPS（Common Unix Print System）使用Internet Printing Protocol（IPP）支持打印到本地和网络打印机。 ([Source Code](https://github.com/OpenPrinting/cups)) `GPL-2.0` `C`
- [CyberChef](https://github.com/gchq/CyberChef) - 在Web浏览器中执行各种操作，如AES、DES和Blowfish加密和解密，创建十六进制转储，计算哈希等等。 ([Demo](https://gchq.github.io/CyberChef)) `Apache-2.0` `Javascript`
- [Digiboard](https://digiboard.app/) - 创建协作式白板（文档以法语提供）。 ([Source Code](https://codeberg.org/ladigitale/digiboard)) `AGPL-3.0` `Nodejs`
- [Digicard](https://codeberg.org/ladigitale/digicard) - 创建简单的图形组合（文档以法语提供）。 ([Demo](https://ladigitale.dev/digicard/)) `AGPL-3.0` `Nodejs`
- [Digiface](https://ladigitale.dev/digiface/) - 使用 Avataaars 库创建头像（法语文档）。 ([Demo](https://ladigitale.dev/digiface/), [Source Code](https://codeberg.org/ladigitale/digiface)) `AGPL-3.0` `Nodejs`
- [Digiview](https://ladigitale.dev/digiview/) `⚠` - 以无干扰的界面查看 YouTube 视频（法语文档）. ([Demo](https://ladigitale.dev/digiview/), [Source Code](https://codeberg.org/ladigitale/digiview)) `AGPL-3.0` `Nodejs/PHP`
- [Digiwords](https://ladigitale.dev/digiwords/) - 用于创建词云的简单在线应用程序（文档以法语提供）。 ([Source Code](https://codeberg.org/ladigitale/digiwords)) `AGPL-3.0` `Nodejs/PHP`
- [DomainMOD](https://domainmod.org) - 应用程序可在一个中央位置管理您的域名和其他互联网资产。DomainMOD包括一个数据仓库框架，允许您导入WHM/cPanel Web服务器数据，以便查看、导出和报告您的数据。 ([Demo](https://demo.domainmod.org), [Source Code](https://github.com/domainmod/domainmod)) `GPL-3.0` `PHP`
- [DOMJudge](https://www.domjudge.org/) - 一个用于举办编程竞赛的系统，类似于ICPC地区和世界锦标编程竞赛。 ([Demo](https://www.domjudge.org/demo), [Source Code](https://github.com/DOMjudge/domjudge)) `GPL-2.0/BSD-3-Clause/MIT` `PHP`
- [ESMira](https://esmira.kl.ac.at) - 运行纵向研究（ESM、AA、EMA），数据收集和与参与者的通信完全匿名。 ([Demo](https://demo-esmira.kl.ac.at/#admin,username:demo,password:demodemodemo), [Source Code](https://github.com/KL-Psychological-Methodology/ESMira)) `AGPL-3.0` `PHP`
- [F-Droid](https://f-droid.org) - 用于维护F-Droid存储库系统的服务器工具。 ([Source Code](https://gitlab.com/fdroid/fdroidserver)) `AGPL-3.0` `Python/Docker/deb`
- [Fasten Health](https://github.com/fastenhealth/fasten-onprem/) `⚠` - Fasten是一个开源的、自托管的、个人/家庭电子病历聚合器，旨在与美国数以千计的保险公司/医院/诊所集成。 `GPL-3.0` `Go/Docker`
- [Flagsmith](https://flagsmith.com) - Flagsmith 提供仪表板、API 和 SDK，用于向应用程序添加功能标志（与 LaunchDarkly 的替代方案）。 ([Source Code](https://github.com/flagsmith/flagsmith)) `BSD-3-Clause` `Docker/K8S`
- [Flipt](https://flipt.io) - 具有多个数据后端支持的功能标志解决方案（与 LaunchDarkly 的替代方案）。 ([Demo](https://try.flipt.io), [Source Code](https://github.com/flipt-io/flipt)) `GPL-3.0` `Docker/K8S/Go`
- [Flyimg](https://flyimg.io) - 实时调整和裁剪图像。使用ImageMagick、高效的缓存系统，获得经过MozJPEG、WebP或PNG优化的图像。 ([Demo](https://demo.flyimg.io), [Source Code](https://github.com/flyimg/flyimg)) `MIT` `Docker`
- [GO Feature Flag](https://gofeatureflag.org) - 简单、完整且轻量级的功能标志解决方案（与LaunchDarkly的替代品）。 ([Source Code](https://github.com/thomaspoignant/go-feature-flag)) `MIT` `Go`
- [google-webfonts-helper](https://github.com/majodev/google-webfonts-helper) `⚠` - 无麻烦地自托管Google字体的方式。获取eot、ttf、svg、woff和woff2文件 + CSS片段。 ([Demo](https://gwfh.mranftl.com/fonts)) `MIT` `Nodejs`
- [Gophish](https://getgophish.com/) - Gophish是一个强大的开源钓鱼框架，可以轻松测试组织对钓鱼的暴露情况。 ([Source Code](https://github.com/gophish/gophish)) `MIT` `Go/Docker`
- [graph-vl](https://github.com/verifid/graph-vl) - 使用机器学习和GraphQL进行身份文件验证。 `MIT` `Python/Docker/K8S`
- [Habitica](https://habitica.com/) - 习惯追踪应用，将您的目标视为角色扮演游戏。之前称为HabitRPG。 ([Source Code](https://github.com/HabitRPG/habitica)) `GPL-3.0/CC-BY-SA-3.0` `Nodejs/Docker`
- [IconCaptcha](https://www.fabianwennink.nl/projects/IconCaptcha/) - IconCaptcha是一个用于PHP的自托管、快速、简单且用户友好的验证码。 ([Source Code](https://github.com/fabianwennink/IconCaptcha-Plugin-jQuery-PHP)) `MIT` `PHP`
- [Jellyseerr](https://github.com/Fallenbagel/jellyseerr) - 管理媒体库的请求，支持Plex、Jellyfin和Emby媒体服务器（是Overseerr的分支）。 `MIT` `Docker/Nodejs`
- [Journal](https://github.com/inoda/journal) - 简单的日记应用，支持加密条目和分享功能。 `MIT` `Ruby/Docker`
- [Kasm Workspaces](https://kasmweb.com/) - 将容器化的应用程序和桌面流式传输给终端用户。示例包括在浏览器中运行的Ubuntu，或者仅运行Chrome、OpenOffice、Gimp、Filezilla等单个应用程序。 ([Demo](https://www.kasmweb.com/#demo), [Source Code](https://github.com/kasmtech)) `GPL-3.0` `Docker`
- [Koillection](https://koillection.github.io/) - Koillection 是一项服务，允许用户管理任何类型的收藏品。 ([Source Code](https://github.com/benjaminjonard/koillection)) `MIT` `Docker/PHP`
- [Lama-Cleaner](https://github.com/Sanster/lama-cleaner) `⚠` - 免费、开源的修复工具，采用先进的人工智能模型。 `Apache-2.0` `Python/Docker`
- [LanguageTool](https://languagetool.org/) - 适用于20多种语言的校对工具。它能发现许多简单拼写检查器无法检测到的错误。 ([Source Code](https://github.com/languagetool-org/languagetool), [Clients](https://languagetool.org/insights/post/product-windows-app/)) `LGPL-2.1` `Java/Docker`
- [Libre Translate](https://libretranslate.com/) - 免费且开源的机器翻译API，完全自托管。 ([Source Code](https://github.com/LibreTranslate/LibreTranslate)) `AGPL-3.0` `Docker/Python`
- [Loggit](https://loggit.net) - 端到端加密的简单生活追踪和日志记录。 ([Demo](https://app.loggit.net), [Source Code](https://github.com/BrunoBernardino/loggit-web)) `AGPL-3.0` `Deno`
- [MailyGo](https://codeberg.org/jlelse/MailyGo) - MailyGo是一个用Go编写的小工具，允许通过电子邮件发送HTML表单，例如从没有动态后端的静态网站。 `MIT` `Go`
- [Mere Medical](https://meremedical.co/) `⚠` - 通过 Mere Medical，您可以终于在一个地方管理来自 Epic MyChart、Cerner 和 OnPatient 患者门户的所有医疗记录。注重隐私、自托管且以离线为先。 ([Demo](https://demo.meremedical.co), [Source Code](https://github.com/cfu288/mere-medical)) `GPL-3.0` `Docker/Nodejs`
- [Monica](https://monicahq.com/) - 个人关系管理器，一种新型的 CRM，用于组织与您的朋友和家人的互动。 ([Source Code](https://github.com/monicahq/monica)) `AGPL-3.0` `PHP/Docker`
- [mosparo](https://mosparo.io/) - 现代的垃圾邮件保护工具。用简单易用的垃圾邮件保护解决方案替代其他验证码方法。 ([Source Code](https://github.com/mosparo/mosparo)) `MIT` `PHP`
- [MyPaas](https://github.com/almarklein/mypaas) - 使用 Docker、Traefik 和强大的监控运行您自己的 PaaS。 `BSD-2-Clause` `Python/Docker`
- [NATS](https://nats.io/) - 发布/订阅事件总线、持久队列、键值存储、对象存储等。原生多租户、多种身份验证和授权机制。易于自主托管和联邦化。 ([Source Code](https://github.com/nats-io/nats-server), [Clients](https://github.com/nats-io)) `Apache-2.0` `Go/deb/Docker/K8S`
- [Neko](https://neko.m1k1o.net) - 一个在 Docker 中运行的自托管虚拟浏览器（rabb.it 克隆）。 ([Source Code](https://github.com/m1k1o/neko)) `Apache-2.0` `Docker/Go`
- [Noisedash](https://github.com/kaythomas0/noisedash) - 可自托管的Web工具，使用音频工具和用户可上传的样本生成环境噪音/声音。 `AGPL-3.0` `Nodejs/Docker`
- [Octave Online](https://octave-online.net/) - 用于GNU Octave的Web UI的基础设施（MATLAB的替代品）。 ([Source Code](https://github.com/octave-online/octave-online-server)) `AGPL-3.0` `Docker/Nodejs`
- [Ombi](https://ombi.io/) - 适用于Plex/Emby的内容请求系统，可连接到SickRage、CouchPotato、Sonarr，并具有不断增长的功能集。 ([Demo](https://app.ombi.io/), [Source Code](https://github.com/Ombi-app/Ombi)) `GPL-2.0` `C#/deb`
- [Open-Meteo](https://open-meteo.com/) - 具有来自所有主要国家气象服务的开放数据预测、历史和气候数据的开源天气API。 ([Demo](https://open-meteo.com/en/docs), [Source Code](https://github.com/open-meteo/open-meteo)) `AGPL-3.0` `Docker`
- [OpenZiti](https://openziti.github.io/) - 全功能、可自托管、零信任、完全网状覆盖网络。开箱即用支持两因素身份验证，适用于所有主要桌面/移动操作系统的客户端。 ([Source Code](https://github.com/openziti/ziti)) `Apache-2.0` `Go`
- [OTS-Share](https://github.com/rpgeeganage/ots-share-app) - 一个自托管的应用程序，用于共享支持文件大小达到1MB的秘密。 `MIT` `Docker`
- [Overseerr](https://overseerr.dev/) `⚠` - Overseerr是一款免费开源的软件应用，用于管理媒体库的请求。它与您现有的服务集成，如Sonarr、Radarr和Plex！。 ([Source Code](https://github.com/sct/overseerr)) `MIT` `Docker`
- [PassCheck](https://passcheck.anhur.xyz/) - 一个Web应用程序，提供一些实用的密码工具，包括密码生成器、强度检查器和HaveIBeenPwned泄露检查器。 ([Source Code](https://github.com/AtentumZero/PassCheck)) `MIT` `Javascript`
- [penpot](https://penpot.app/) - 面向跨领域团队的基于Web的设计和原型平台。 ([Source Code](https://github.com/penpot/penpot)) `MPL-2.0` `Docker`
- [POMjs](https://password.oppetmoln.se/) - 随机密码生成器。 ([Source Code](https://github.com/joho1968/POMjs)) `GPL-2.0` `Javascript`
- [Reactive Resume](https://rxresu.me/) - 一种独特的简历构建工具，考虑了您的隐私。完全安全、可定制、便携、开源且永久免费。 ([Demo](https://rxresu.me/app/dashboard/), [Source Code](https://github.com/AmruthPillai/Reactive-Resume)) `MIT` `Docker/Nodejs`
- [ReleaseBell](https://releasebell.com/) - 发送关注的GitHub仓库的发布通知。 ([Source Code](https://git.cloudron.io/cloudron/releasebell)) `MIT` `Nodejs`
- [revealjs](https://revealjs.com) - 使用 HTML 轻松创建漂亮演示文稿的框架。 ([Demo](https://revealjs.com/), [Source Code](https://github.com/hakimel/reveal.js)) `MIT` `Javascript`
- [Revive Adserver](https://www.revive-adserver.com/) - 全球最受欢迎的免费、开源广告投放系统。曾被称为 OpenX Adserver 和 phpAdsNew。 ([Source Code](https://github.com/revive-adserver/revive-adserver)) `GPL-2.0` `PHP`
- [SANE Network Scanning](http://sane-project.org/) - 允许远程客户端访问本地主机上可用的图像采集设备（扫描仪）。 ([Source Code](http://www.sane-project.org/cvs.html)) `GPL-2.0` `C`
- [Speed Test by OpenSpeedTest™](https://openspeedtest.com/) - 免费且开源的HTML5网络性能估算工具。 ([Source Code](https://github.com/openspeedtest/Speed-Test)) `MIT` `Docker`
- [string.is](https://string.is/) - 面向开发人员的开源、注重隐私的在线字符串工具包。 ([Source Code](https://github.com/recurser/string-is)) `AGPL-3.0` `Nodejs`
- [Teleport](https://goteleport.com/) - 用于 SSH、Kubernetes、Web 应用和数据库的证书颁发机构和访问平面。 ([Source Code](https://github.com/gravitational/teleport)) `Apache-2.0` `Go/Docker/K8S`
- [TeslaMate](https://github.com/adriankumpf/teslamate) - 一款适用于特斯拉车辆的强大数据记录器。 `MIT` `Elixir/Docker`
- [Upsnap](https://github.com/seriousm4x/UpSnap) - 一款简单的远程唤醒（Wake on LAN，WOL）仪表板应用。唤醒网络中的设备并查看当前状态。 `MIT` `Go/Docker`
- [ViMbAdmin](https://www.vimbadmin.net/) - 提供基于Web的虚拟邮箱管理系统，允许邮件管理员轻松管理域、邮箱和别名。 ([Source Code](https://github.com/opensolutions/ViMbAdmin)) `GPL-3.0` `PHP`
- [Watcharr](https://github.com/sbondCo/Watcharr) - 一个免费开源的内容观看清单。添加和跟踪您正在观看的所有电视节目和电影。具有用户身份验证、现代而清晰的用户界面和非常简单的设置。 ([Demo](https://beta.watcharr.app/)) `MIT` `Docker`
- [WeeWX](https://weewx.com/) - 用于您的气象站的开源软件。 ([Demo](https://weewx.com/showcase.html), [Source Code](https://github.com/weewx/weewx)) `GPL-3.0` `Python/deb`
- [WeTTY](https://butlerx.github.io/wetty/#/) - 通过http/https在浏览器中使用的终端。 ([Source Code](https://github.com/butlerx/wetty)) `MIT` `Docker/Nodejs`
- [wger](https://wger.de/) - 基于Web的个人锻炼、健身和体重记录/跟踪工具。还可以用作简单的健身房管理实用工具，并提供完整的REST API。 ([Demo](https://wger.de/en/dashboard), [Source Code](https://github.com/wger-project/wger)) `AGPL-3.0` `Python/Docker`


### 档案和数字保存（DP）

**[`^        back to top        ^`](#Awesome-Selfhosted)**

数字[存档](https://en.wikipedia.org/wiki/Archival_science)和[保存](https://en.wikipedia.org/wiki/Digital_preservation)软件。

_Related: [内容管理系统（CMS）](#内容管理系统（cms）)_

_See also: [awesome-web-archiving](https://github.com/iipc/awesome-web-archiving)_

- [Access to Memory (AtoM)](https://www.accesstomemory.org/) - 面向标准的档案描述和在多语言、多存储库环境中进行访问的基于Web的开源应用程序。 ([Demo](https://demo.accesstomemory.org/), [Source Code](https://github.com/artefactual/atom)) `AGPL-3.0` `PHP`
- [ArchiveBox](https://archivebox.io/) - 自托管的“时光机”工具，可以从书签、浏览历史、RSS 订阅或其他来源创建网站的 HTML 和截图存档。 ([Source Code](https://github.com/ArchiveBox/ArchiveBox)) `MIT` `Python/Docker`
- [Archivematica](https://www.archivematica.org/en/) - 成熟的数字保存系统，旨在维护符合标准的数字对象集的长期访问。 ([Demo](https://sandbox.archivematica.org/administration/accounts/login/), [Source Code](https://github.com/artefactual/archivematica)) `AGPL-3.0` `Python`
- [ArchivesSpace](https://archivesspace.org/) - 用于管理和提供对档案、手稿和数字对象的 Web 访问的档案信息管理应用程序。 ([Demo](https://archivesspace.org/application/demo), [Source Code](https://github.com/archivesspace/archivesspace)) `ECL-2.0` `Ruby`
- [CKAN](https://ckan.org) - CKAN是一个创建开放数据网站的工具。 ([Source Code](https://github.com/ckan/ckan)) `AGPL-3.0` `Python`
- [Collective Access - Providence](https://collectiveaccess.org/) - 高度可配置的基于Web的框架，用于管理、描述和发现数字和物理收藏，支持各种元数据标准、数据类型和媒体格式。 ([Source Code](https://github.com/collectiveaccess/providence)) `GPL-3.0` `PHP`
- [Ganymede](https://github.com/Zibbp/ganymede) `⚠` - Twitch VOD 和直播流存档平台。每个存档包含渲染后的聊天记录。 `GPL-3.0` `Docker`
- [LiveStreamDVR](https://github.com/MrBrax/LiveStreamDVR) `⚠` - 一款自动的Twitch录制工具，能够捕获直播流、聊天消息和流元数据。 `MIT` `Python/Nodejs/Docker`
- [Omeka S](https://omeka.org/s/) - Omeka S是面向大学、画廊、图书馆、档案馆和博物馆的Web出版系统。它由一个本地网络组成，独立策展的展览共享一个协作构建的项目、媒体和它们的元数据池。 ([Source Code](https://github.com/omeka/omeka-s)) `GPL-3.0` `Nodejs`
- [Wallabag](https://www.wallabag.org) - Wallabag，前身是Poche，是一个允许您保存文章以便以提高可读性稍后阅读的Web应用程序。 ([Source Code](https://github.com/wallabag/wallabag)) `MIT` `PHP`
- [Wayback](https://github.com/wabarc/wayback) - 用于将网页存档到Internet Archive、archive.today、IPFS和本地文件系统的自托管工具包。 `GPL-3.0` `Go`
- [Webarchive](https://github.com/derfenix/webarchive) - 轻量级的自托管_wayback机器_，可以从您的书签创建HTML和PDF文件。 `BSD-3-Clause` `Go`


### 流媒体

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[流媒体](https://en.wikipedia.org/wiki/Streaming_media)是以连续的方式从源头传递和消费的多媒体，网络元素中几乎没有或没有中间存储。

**Please visit [流媒体 - 音频流媒体](#流媒体 - 音频流媒体), [流媒体 - 多媒体流媒体](#流媒体 - 多媒体流媒体), [流媒体 - 视频流媒体](#流媒体 - 视频流媒体)**

_See also: [流媒体系统列表 - Wikipedia](https://en.wikipedia.org/wiki/List_of_streaming_media_systems), [流媒体系统比较 - Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_streaming_media_systems)_



### 流媒体 - 多媒体流媒体

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[多媒体](https://en.wikipedia.org/wiki/Multimedia)流媒体工具和软件。

_Related: [流媒体 - 视频流媒体](#流媒体---视频流媒体), [流媒体 - 音频流媒体](#流媒体---音频流媒体)_

- [Dim](https://github.com/Dusk-Labs/dim) - Dim是一个由黑暗力量驱动的自托管媒体管理器。通过最小的设置，Dim将组织和美化您的媒体收藏，让您随时随地访问和播放。 `GPL-2.0` `Rust`
- [Gerbera](https://gerbera.io/) - Gerbera是一个UPnP媒体服务器。它允许您在整个家庭网络中流式传输数字媒体，并在各种UPnP兼容设备上进行收听/观看。 ([Source Code](https://github.com/gerbera/gerbera)) `GPL-2.0` `Docker/deb/C++`
- [Icecast 2](https://icecast.org) - 流媒体音频/视频服务器，可用于创建互联网广播电台或私人运行的点唱机等多种应用。 ([Source Code](https://gitlab.xiph.org/xiph/icecast-server), [Clients](https://icecast.org/apps/)) `GPL-2.0` `C`
- [Jellyfin](https://jellyfin.org) - 音频、视频、图书、漫画和照片的媒体服务器，具有时尚界面和强大的转码能力。几乎所有现代平台都有客户端，包括Roku、Android TV、iOS和Kodi。 ([Demo](https://demo.jellyfin.org/stable), [Source Code](https://github.com/jellyfin/jellyfin), [Clients](https://github.com/awesome-jellyfin/awesome-jellyfin)) `GPL-2.0` `C#/deb/Docker`
- [Karaoke Eternal](https://www.karaoke-eternal.com) - 举办令人惊叹的卡拉OK派对，每个人都可以轻松地从手机浏览器中查找并排队歌曲。播放器也完全基于浏览器，支持MP3+G、MP4和WebGL可视化。 ([Source Code](https://www.karaoke-eternal.com/repo)) `ISC` `Docker/Nodejs`
- [Kodi](https://kodi.tv/) - 多媒体/娱乐中心，以前被称为 XBMC。适用于 Android、BSD、Linux、macOS、iOS 和 Windows。 ([Source Code](https://github.com/xbmc/xbmc)) `GPL-2.0` `C++/deb`
- [LBRY](https://lbry.com/) - LBRY是一个安全、开放且由社区运营的数字市场，旨在取代Youtube和Amazon。 ([Demo](https://lbry.tv/), [Source Code](https://github.com/lbryio/lbry.com), [Clients](https://github.com/lbryio/lbry-desktop)) `MIT` `PHP`
- [MistServer](https://mistserver.org/) - 在任何流媒体环境中都能很好运行的流媒体服务器。 ([Source Code](https://github.com/DDVTECH/mistserver)) `AGPL-3.0` `C++`
- [NymphCast](http://nyanko.ws/nymphcast.php) - 将您选择的支持Linux的硬件转换为电视或音响的音频和视频源（替代品Chromecast）。 ([Source Code](https://github.com/MayaPosch/NymphCast)) `BSD-3-Clause` `C++`
- [Podify](https://www.podify.org/) - 允许您从任何由youtube-dl支持的源下载视频和音频，并通过您喜欢的播客应用订阅和观看这些下载内容。 ([Source Code](https://github.com/podify-org/podify/)) `GPL-3.0` `Docker/Ruby`
- [ReadyMedia](https://sourceforge.net/projects/minidlna/) - 简单的媒体服务器软件，旨在完全符合DLNA/UPnP-AV客户端的要求。以前称为MiniDLNA。 ([Source Code](https://sourceforge.net/p/minidlna/git/ci/master/tree/)) `GPL-2.0` `C`
- [Rygel](https://wiki.gnome.org/action/show/Projects/Rygel) - Rygel 是一个 UPnP AV 媒体服务器，可以轻松共享音频、视频和图片。媒体播放器软件可以使用 Rygel 成为一个可以通过 UPnP 或 DLNA 控制器远程控制的 MediaRenderer。 ([Source Code](https://gitlab.gnome.org/GNOME/rygel/)) `GPL-3.0` `C`
- [SheetAble](https://sheetable.net) - 适用于所有音乐爱好者的自托管音乐谱整理软件。上传和整理适用于任何乐器的谱子。 ([Source Code](https://github.com/SheetAble/SheetAble)) `AGPL-3.0` `Docker/Go`
- [Stash](https://stashapp.cc) - 一个基于Web的成人媒体库组织器和播放器，具有自动标记和元数据抓取支持。 ([Source Code](https://github.com/stashapp/stash)) `AGPL-3.0` `Docker/Go`
- [µStreamer](https://github.com/pikvm/ustreamer) - 轻量级且非常快速的服务器，用于从任何V4L2设备向网络传输MJPEG视频。 `GPL-3.0` `C/deb`
- [üWave](https://u-wave.net/) `⚠` - 自托管的协作式听歌平台。用户轮流播放来自各种媒体源（如YouTube和SoundCloud）的媒体内容，包括歌曲、演讲、游戏视频或其他任何内容。 ([Demo](https://wlk.yt/), [Source Code](https://github.com/u-wave)) `MIT` `Nodejs`


### 流媒体 - 视频流媒体

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[视频](https://en.wikipedia.org/wiki/Video)流媒体工具和软件。

_Related: [视频监控](#视频监控), [流媒体 - 多媒体流媒体](#流媒体---多媒体流媒体)_

- [cmyflix](https://github.com/farfalleflickan/cmyflix) `⚠` - 自托管、超轻量级的Netflix替代品。 `AGPL-3.0` `C`
- [CyTube](https://github.com/calzoneman/sync) - CyTube是一个Web应用程序，为任意数量的频道提供媒体同步、聊天等功能。 ([Demo](https://cytu.be)) `MIT` `Nodejs`
- [Invidious](https://github.com/iv-org/invidious) `⚠` - 替代YouTube前端。 ([Demo](https://docs.invidious.io/instances/)) `AGPL-3.0` `Docker/Crystal`
- [MediaCMS](https://mediacms.io) - MediaCMS是一款现代、功能齐全的开源视频和媒体CMS，采用Python/Django/React编写，具有REST API功能。 ([Source Code](https://github.com/mediacms-io/mediacms)) `AGPL-3.0` `Python/Docker`
- [Oblecto](https://github.com/robinp7720/Oblecto) `⚠` - 用于电影和电视节目的媒体服务器，具有响应式的Vue.js前端。具有强大的转码支持，以及通过联邦功能与朋友共享库的能力。 `AGPL-3.0` `Nodejs`
- [Open Streaming Platform](https://openstreamingplatform.com) - 实时和点播视频流（替代Twitch和Youtube Live）。 ([Source Code](https://gitlab.com/Deamos/flask-nginx-rtmp-manager)) `MIT` `Python`
- [OvenMediaEngine](https://ovenmediaengine.com) - OvenMediaEngine是一个可自托管的开源流媒体服务器，具有亚秒级延迟。 ([Demo](https://demo.ovenplayer.com), [Source Code](https://github.com/AirenSoft/OvenMediaEngine)) `GPL-3.0` `C++/Docker`
- [Owncast](https://owncast.online/) - 去中心化的单用户实时视频流和聊天服务器，用于运行类似于主流选项的自己的实时流。 ([Source Code](https://github.com/owncast/owncast)) `MIT` `Go`
- [PeerTube](https://joinpeertube.org/en/) - 使用P2P（BitTorrent）直接在Web浏览器中进行的分散式视频流平台。 ([Source Code](https://github.com/Chocobozzz/PeerTube)) `AGPL-3.0` `Nodejs`
- [Rapidbay](https://github.com/hauxir/rapidbay/) - 自托管的种子视频流服务/种子客户端，允许在浏览器或从Chromecast/AppleTV/智能电视中搜索和播放种子视频。 `MIT` `Python/Docker`
- [Restreamer](https://datarhei.github.io/restreamer/) - Restreamer允许您在网站上进行H.264实时视频流，无需使用流媒体提供商。 ([Source Code](https://github.com/datarhei/restreamer)) `Apache-2.0` `Nodejs/Docker`
- [SRS](https://ossrs.io/) - 一个简单、高效和实时的视频服务器，支持RTMP、WebRTC、HLS、HTTP-FLV和SRT。 ([Source Code](https://github.com/ossrs/srs)) `MIT` `Docker/C++`
- [Streama](https://github.com/streamaserver/streama) - 自托管的流媒体服务器。 `MIT` `Java`
- [SyncTube](https://github.com/RblSb/SyncTube) - 轻量级且非常简单设置的 CyTube 替代方案，用于与朋友一起观看视频和聊天。 `MIT` `Nodejs/Haxe`
- [Tube](https://git.mills.io/prologic/tube) - 采用Go编写的类似YouTube的（_无审查和您不需要的功能！_）视频共享应用，还支持自动转码为MP4 H.265 AAC，多个收藏夹和RSS订阅。 ([Demo](https://tube.mills.io)) `MIT` `Go`
- [VideoLAN Client (VLC)](https://www.videolan.org/) - 跨平台的多媒体播放器客户端和服务器，支持大多数多媒体文件以及DVD、音频CD、VCD和各种流媒体协议。 ([Source Code](https://github.com/videolan/vlc)) `GPL-2.0` `C/deb`


### 流媒体 - 音频流媒体

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[音频](https://en.wikipedia.org/wiki/Audio)流媒体工具和软件。

- [Ampache](https://ampache.org/) - Web 基础的音频/视频流应用。 ([Demo](https://play.dogmazic.net/), [Source Code](https://github.com/ampache/ampache)) `AGPL-3.0` `PHP`
- [Audiobookshelf](https://www.audiobookshelf.org/) - 完全开源的自托管有声书和播客服务器。支持流式传输所有音频格式，保持并同步跨设备的播放进度。附带开源的 Android 和 iOS 应用程序。 ([Source Code](https://github.com/advplyr/audiobookshelf), [Clients](https://github.com/advplyr/audiobookshelf-app)) `GPL-3.0` `Docker/deb/Nodejs`
- [Audioserve](https://github.com/izderadicka/audioserve) - 简单的个人服务器，用于从目录中提供音频文件（有声书、音乐、播客等）。专注于简单性，支持在客户端之间同步播放位置。 `MIT` `Rust`
- [AzuraCast](https://www.azuracast.com/) - 一套现代、易用的自托管网络广播管理套件。 ([Source Code](https://github.com/AzuraCast/AzuraCast)) `Apache-2.0` `Docker`
- [Beets](https://beets.io/) - 音乐库管理器和MusicBrainz标签编辑器（命令行和Web界面）。 ([Source Code](https://github.com/beetbox/beets)) `MIT` `Python/deb`
- [Black Candy](https://github.com/blackcandy-org/black_candy) - 使用Rails和Stimulus构建的音乐流媒体服务器。 `MIT` `Docker/Ruby`
- [Bsimp](https://github.com/akrylysov/bsimp) - 极简的基于S3的音频库。 `Apache-2.0` `Go`
- [Funkwhale](https://dev.funkwhale.audio/funkwhale) - 现代、基于Web、友好、多用户和免费的音乐服务器。 `BSD-3-Clause` `Python/Django`
- [gonic](https://github.com/sentriz/gonic) - 轻量级音乐流媒体服务器。兼容Subsonic。 `GPL-3.0` `Go/Docker`
- [koel](https://koel.dev/) - 个人音乐流媒体服务器，运行良好。 ([Demo](https://demo.koel.dev/), [Source Code](https://github.com/koel/koel)) `MIT` `PHP`
- [LibreTime](https://libretime.org) - 一个简单的、开源的平台，让您可以在Web上广播流媒体电台（是[Airtime](https://github.com/sourcefabric/Airtime)的分支）。 ([Source Code](https://github.com/LibreTime/libretime)) `AGPL-3.0` `Docker/PHP`
- [LMS](https://github.com/epoupon/lms) - 通过Web界面访问您的自托管音乐。 `GPL-3.0` `Docker/deb/C++`
- [Maloja](https://github.com/krateng/maloja) - 自托管的音乐播放记录数据库（替代Last.fm）。 ([Demo](https://maloja.krateng.ch/)) `GPL-3.0` `Python/Docker`
- [moOde Audio](https://moodeaudio.org/) - 高保真音乐播放，适用于出色的 Raspberry Pi 单板计算机系列。 ([Source Code](https://github.com/moode-player/moode)) `GPL-3.0` `PHP`
- [Mopidy](https://docs.mopidy.com/) - 可扩展的音乐服务器。提供 mpd API 的超集，以及与 Spotify、SoundCloud 等第三方服务的集成。 ([Source Code](https://github.com/mopidy/mopidy)) `Apache-2.0` `Python/deb`
- [mpd](https://www.musicpd.org/) - 远程播放音乐、流式传输音乐、处理和组织播放列表的守护进程。有许多可用的客户端。 ([Source Code](https://github.com/MusicPlayerDaemon/MPD), [Clients](https://www.musicpd.org/clients/)) `GPL-2.0` `C++`
- [mStream](https://mstream.io/) - 具有 GUI 管理工具的音乐流媒体服务器。支持 Mac、Windows 和 Linux。 ([Source Code](https://github.com/IrosTheBeggar/mStream)) `GPL-2.0` `Nodejs`
- [musikcube](https://musikcube.com/) - 具有 Linux/macOS/Windows/Android 客户端的音频流媒体服务器。 ([Source Code](https://github.com/clangen/musikcube)) `BSD-3-Clause` `C++/deb`
- [Navidrome Music Server](https://www.navidrome.org) - 现代音乐服务器和流媒体服务器，兼容Subsonic/Airsonic。 ([Demo](https://www.navidrome.org/demo), [Source Code](https://github.com/navidrome/navidrome), [Clients](https://www.navidrome.org/docs/overview/#apps)) `GPL-3.0` `Docker/Go`
- [Polaris](https://github.com/agersant/polaris) - 针对大型音乐收藏、易用性和高性能优化的音乐浏览和流媒体应用。 `MIT` `Rust/Docker`
- [Snapcast](https://github.com/badaix/snapcast) - 同步的多房间音频服务器。 `GPL-3.0` `C++/deb`
- [Stretto](https://github.com/benkaiser/stretto) - 具有Youtube/Soundcloud导入和iTunes/Spotify发现功能的音乐播放器。 ([Demo](https://next.kaiserapps.com), [Clients](https://github.com/benkaiser/stretto-mobile-next)) `MIT` `Nodejs`
- [Supysonic](https://github.com/spl0k/supysonic) - Subsonic 服务器 API 的 Python 实现。 `AGPL-3.0` `Python/deb`
- [SwingMusic](https://swingmusic.vercel.app/) - Swing Music 是一个漂亮的、自托管的音乐播放器和本地音频文件的流媒体服务器。就像更酷的 Spotify ... 但请自备音乐。 ([Source Code](https://github.com/swing-opensource/swingmusic)) `MIT` `Python/Docker`
- [vod2pod-rss](https://github.com/madiele/vod2pod-rss) `⚠` - 将YouTube和Twitch频道转换为播客，无需存储。实时转码VoDs为MP3 192k，生成供播客客户端使用的RSS源。 `MIT` `Docker`


### 游戏

**[`^        back to top        ^`](#Awesome-Selfhosted)**

多人游戏服务器和[浏览器游戏](https://en.wikipedia.org/wiki/Browser_game)。

_Related: [游戏 - 管理工具和控制面板](#游戏---管理工具和控制面板)_

- [0 A.D.](https://play0ad.com/) - 一款古代战争的免费、开源游戏。 ([Source Code](https://github.com/0ad/0ad)) `MIT/GPL-2.0/Zlib` `C++/C/deb`
- [A Dark Room](https://github.com/doublespeakgames/adarkroom) - 适用于浏览器的极简主义文本冒险游戏。 ([Demo](https://adarkroom.doublespeakgames.com/)) `MPL-2.0` `Javascript`
- [Digibuzzer](https://digibuzzer.app/) - 在连接的蜂鸣器周围创建虚拟游戏房间（法语文档）。 ([Demo](https://digibuzzer.app/), [Source Code](https://codeberg.org/ladigitale/digibuzzer)) `AGPL-3.0` `Nodejs`
- [EmuLinkerSF](https://emulinker.org) - EmuLinkerSF是一个开源的Kaillera服务器。Kaillera是一个客户端/服务器系统，任何模拟器都可以实现，以实现通过互联网进行联机游戏。 ([Source Code](https://github.com/God-Weapon/EmuLinkerSF)) `GPL-2.0` `Java`
- [Lila](https://lichess.org/) - 永久免费、无广告且开源的国际象棋服务器，为lichess.org提供支持，拥有官方iOS和Android客户端应用。 ([Source Code](https://github.com/lichess-org/lila)) `AGPL-3.0` `Scala`
- [Mindustry](https://mindustrygame.github.io/) - 类似于 Factorio 的塔防游戏。建立生产链以获取更多资源，并构建复杂的设施。 ([Source Code](https://github.com/Anuken/Mindustry)) `GPL-3.0` `Java`
- [Minetest](https://www.minetest.net/) - 一款开源的体素游戏引擎。玩其中的许多游戏，按照您的喜好修改游戏，制作自己的游戏，或在多人服务器上游玩。 ([Source Code](https://github.com/minetest/minetest)) `LGPL-2.1/MIT/Zlib` `C++/deb`
- [MTA:SA](https://multitheftauto.com/) `⚠` - Multi Theft Auto (MTA) 是一个软件项目，为 Rockstar North 的《侠盗猎车手》游戏系列添加了网络游戏功能，该功能在原版中并不存在。 ([Source Code](https://github.com/multitheftauto/mtasa-blue)) `GPL-3.0` `C++`
- [piqueserver](https://github.com/piqueserver/piqueserver) - OpenSpades 的服务器，OpenSpades 是一个第一人称射击游戏，背景是一个可破坏的体素世界。 ([Clients](https://github.com/yvt/openspades)) `GPL-3.0` `Python/C++`
- [Posio](https://github.com/abrenaut/posio) - 地理多人游戏。 `MIT` `Python`
- [Quizmaster](https://github.com/nymanjens/quizmaster) - 用于进行测验的Web应用，包括供玩家输入答案的页面。 `Apache-2.0` `Scala`
- [Red Eclipse 2](https://redeclipse.net) - 一个类似于Unreal Tournament的自由开源竞技场第一人称射击游戏。 ([Source Code](https://github.com/redeclipse/base)) `Zlib/MIT/CC-BY-SA-4.0` `C/C++/deb`
- [Romm](https://github.com/zurdi15/romm) `⚠` - RomM (Rom Manager) 是一个与 IGDB 集成的基于 Web 的复古 ROM 管理器。 `GPL-3.0` `Docker`
- [Suroi](https://suroi.io/) - 一款受 surviv.io 启发的开源二维大逃杀游戏。 ([Demo](https://suroi.io/), [Source Code](https://github.com/HasangerGames/suroi)) `GPL-3.0` `Nodejs`
- [Teeworlds](https://www.teeworlds.com) - 开源的二维复古多人射击游戏。 ([Source Code](https://github.com/teeworlds/teeworlds)) `Zlib` `C++/deb`
- [The Battle for Wesnoth](https://github.com/wesnoth/wesnoth) - 《威斯诺斯之战》是一款开源的、回合制的战术策略游戏，以高奇幻为主题，提供单人游戏和在线/热座多人对战。 `GPL-2.0` `C++/deb`
- [Veloren](https://veloren.net/) - 多人在线角色扮演游戏。开源游戏，灵感来自Cube World、塞尔达传说、矮人要塞和Minecraft。 ([Source Code](https://gitlab.com/veloren/veloren)) `GPL-3.0` `Rust`
- [Word Mastermind](https://github.com/clupasq/word-mastermind) - Wordle克隆。类似猜谜游戏Mastermind，但你需要猜测单词而不是颜色。 ([Demo](https://word-mastermind.glitch.me/)) `MIT` `Nodejs`
- [Wordle](https://reactle.vercel.app/) - 一个开源的Wordle游戏。在六次尝试中猜测Wordle。每个猜测必须是一个有效的五个字母的单词。 ([Source Code](https://github.com/cwackerfuss/react-wordle)) `MIT` `Nodejs`
- [Zero-K](https://zero-k.info/) - 在Springrts引擎上的开源项目。Zero-K是一款传统的实时战略游戏，侧重于通过地形操作、物理和大量独特单位的玩家创造力，同时保持平衡以支持竞技游戏。 ([Source Code](https://github.com/ZeroK-RTS/Zero-K)) `GPL-2.0` `Lua`


### 游戏 - 管理工具和控制面板

**[`^        back to top        ^`](#Awesome-Selfhosted)**

用于管理游戏服务器的工具。

_Related: [游戏](#游戏)_

- [ARRCON](https://github.com/radj307/ARRCON) - 使用 Source RCON 协议，与任何使用该协议的游戏服务器兼容的终端 RCON 客户端。 `GPL-3.0` `C++`
- [Crafty Controller](https://craftycontrol.com/) - Crafty Controller是一个免费且开源的Minecraft启动器和管理器，允许用户从用户友好的界面启动和管理Minecraft服务器。 ([Source Code](https://gitlab.com/crafty-controller/crafty-4)) `GPL-3.0` `Docker/Python`
- [EasyWI](https://easy-wi.com) - Easy-Wi 是一个 Web 界面，允许您管理服务器守护程序，如游戏服务器。此外，它为您提供了一个包括全自动游戏和语音服务器租赁服务的 CMS。 ([Source Code](https://github.com/easy-wi/developer/)) `GPL-3.0` `PHP/Shell`
- [Kubek](https://kubek.seeroy.ru) - 用于Minecraft服务器的Web管理面板。 ([Source Code](https://github.com/seeroy/kubek-minecraft-dashboard)) `GPL-3.0` `Nodejs`
- [Lancache](https://lancache.net) `⚠` - 简化的局域网派对游戏缓存工具。 ([Source Code](https://github.com/lancachenet/monolithic)) `MIT` `Docker/Shell`
- [LinuxGSM](https://linuxgsm.com/) - Linux下专用游戏服务器的部署和管理的命令行工具：支持超过120种游戏。 ([Source Code](https://github.com/GameServerManagers/LinuxGSM)) `MIT` `Shell`
- [Lodestone](https://github.com/Lodestone-Team/lodestone) - 用于Minecraft和其他多人游戏的免费、开源的服务器托管工具。 `AGPL-3.0` `Docker/Rust`
- [Pterodactyl](https://pterodactyl.io/) - 用于游戏服务器的管理面板，具有直观的用户界面。 ([Source Code](https://github.com/pterodactyl/panel)) `MIT` `PHP`
- [PufferPanel](https://www.pufferpanel.com/) - PufferPanel是一个开源的游戏服务器管理面板，专为小型网络和游戏服务器提供商设计。 ([Source Code](https://github.com/pufferpanel/pufferpanel)) `Apache-2.0` `Go`
- [RconCli](https://github.com/gorcon/rcon-cli) - 使用RCON协议在远程Valve Source专用服务器上执行查询的命令行界面。 `MIT` `Go`
- [SourceBans++](https://sbpp.github.io/) - 用于运行在Source引擎上的游戏的管理员、封禁和通信管理系统。 ([Source Code](https://github.com/sbpp/sourcebans-pp)) `CC-BY-SA-4.0` `PHP`
- [Sunshine](https://app.lizardbyte.dev/Sunshine/) - 用于 Moonlight 的远程游戏流主机，支持高达每秒 120 帧和 4K 分辨率。 ([Source Code](https://github.com/LizardByte/Sunshine)) `GPL-3.0` `C++/deb/Docker`


### 照片和视频库

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[图库](https://en.wikipedia.org/wiki/Gallery_Software)是帮助用户发布或分享照片、图片、视频或其他数字媒体的软件。

_Related: [静态网站生成器](#静态网站生成器), [照片和视频库](#照片和视频库), [内容管理系统（CMS）](#内容管理系统（cms）)_

- [Chevereto](https://chevereto.com/) - 终极图片分享软件。在短短几分钟内创建您自己的个人图像托管网站。 ([Source Code](https://github.com/chevereto/chevereto)) `AGPL-3.0` `PHP/Docker`
- [Coppermine](https://coppermine-gallery.net/) - 多语言相册，与各种论坛集成。包括上传审批和密码保护的相册。 ([Demo](https://coppermine-gallery.net/demo/cpg15x/), [Source Code](https://github.com/coppermine-gallery/cpg1.6.x)) `GPL-3.0` `PHP`
- [Damselfly](https://damselfly.info) - 针对大量图像集合的快速服务器端照片管理系统。包括人脸检测、人脸和物体识别、强大的搜索和 EXIF 关键字标记。支持 Linux、MacOS 和 Windows。 ([Source Code](https://github.com/webreaper/damselfly)) `GPL-3.0` `Docker/C#/.NET`
- [HomeGallery](https://home-gallery.org) - 自托管的开源Web图库，用于浏览个人照片和视频，具备标签、移动友好和基于AI的图像发现功能。 ([Demo](https://demo.home-gallery.org), [Source Code](https://github.com/xemle/home-gallery)) `MIT` `Nodejs/Docker`
- [Immich](https://immich.app/) - 通过移动手机直接进行自托管的照片和视频备份解决方案。 ([Source Code](https://github.com/immich-app/immich)) `MIT` `Docker`
- [LibrePhotos](https://github.com/LibrePhotos/librephotos) - 自托管的仿Google Photos的应用，略带一些酷炫图表的关注点。 ([Clients](https://docs.librephotos.com/docs/user-guide/mobile/)) `MIT` `Python/Docker`
- [Lychee](https://lycheeorg.github.io/) - 开源的基于网格和相册的照片管理系统。 ([Source Code](https://github.com/LycheeOrg/Lychee)) `MIT` `PHP/Docker`
- [Mediagoblin](https://mediagoblin.org) - 自由软件媒体发布平台，任何人都可以运行（可替代Flickr、YouTube、SoundCloud等）。 ([Source Code](https://savannah.gnu.org/projects/mediagoblin)) `AGPL-3.0` `Python`
- [Mejiro](https://github.com/dmpop/mejiro) - 一个易于使用的PHP Web应用程序，用于即时发布照片。 `GPL-3.0` `PHP`
- [Nextcloud Memories](https://memories.gallery/) - 快速、现代化和先进的照片管理套件。作为Nextcloud应用运行。 ([Demo](https://demo.memories.gallery/apps/memories/), [Source Code](https://github.com/pulsejet/memories)) `AGPL-3.0` `PHP`
- [PhotoPrism](https://photoprism.org) - 由Go和Google TensorFlow支持的个人照片管理。浏览、组织和共享您的个人照片集，使用最新技术自动标记和查找图片。 ([Demo](https://demo.photoprism.app/library/browse), [Source Code](https://github.com/photoprism/photoprism)) `AGPL-3.0` `Go/Docker`
- [Photoview](https://photoview.github.io/) - 一款简单易用的个人服务器照片库。它专为摄影师设计，旨在提供一种简单快速的浏览目录的方式，支持数千张高分辨率照片。 ([Source Code](https://github.com/photoview/photoview)) `GPL-3.0` `Go/Docker`
- [PiGallery 2](https://bpatrik.github.io/pigallery2/) - 以目录为主的照片展示网站，具有丰富的用户界面，经过优化可在低资源服务器上运行。 ([Source Code](https://github.com/bpatrik/pigallery2)) `MIT` `Docker/Nodejs`
- [Piwigo](https://piwigo.org/) - 用于 web 的相册软件，由积极的用户和开发人员社区构建。 ([Source Code](https://github.com/Piwigo/Piwigo)) `GPL-2.0` `PHP`
- [sigal](https://github.com/saimn/sigal) - 又一个简单的静态图库生成器。 `MIT` `Python`
- [SPIS](https://github.com/gbbirkisson/spis) - 一个简单、轻量且快速的媒体服务器，具有良好的移动支持。 `GPL-3.0` `Docker/Rust`
- [This week in past](https://github.com/RouHim/this-week-in-past) - 聚合了来自以往年份的本周拍摄的图片，并在网页上以简单的幻灯片形式呈现。 `MIT` `Docker/Rust`
- [Thumbor](http://thumbor.org/) - 一项智能图像服务，支持按需裁剪、调整大小、应用滤镜和优化图像。 ([Source Code](https://github.com/thumbor/thumbor)) `MIT` `Python/Docker`
- [Zenphoto](https://www.zenphoto.org/) - 开源图库和CMS项目。 ([Source Code](https://github.com/zenphoto/zenphoto)) `GPL-2.0` `PHP`


### 物联网（IoT）

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[物联网](https://en.wikipedia.org/wiki/Internet_of_things)描述具有传感器、处理能力、软件和其他技术的物理对象，通过互联网与其他设备连接并交换数据。

- [DeviceHive](https://www.devicehive.com/) - 具有广泛集成选项的开源物联网平台。 ([Demo](https://playground.devicehive.com/), [Source Code](https://github.com/devicehive/devicehive-java-server)) `Apache-2.0` `Java/Docker/K8S`
- [Domoticz](https://www.domoticz.com/) - 家庭自动化系统，可让您监视和配置各种设备，如：灯光、开关、各种传感器/仪表，如温度、雨量、风速、紫外线、电、气体、水等等。 ([Source Code](https://github.com/domoticz/domoticz), [Clients](https://github.com/domoticz/domoticz-android)) `GPL-3.0` `C/C++/Docker/Shell`
- [EMQX](https://www.emqx.io/) - 一个超大规模的开源MQTT代理。在一个单一集群中连接超过1亿个物联网设备，以1ms延迟处理1M消息/秒的实时物联网数据。 ([Demo](https://www.emqx.com/en/mqtt/public-mqtt5-broker), [Source Code](https://github.com/emqx/emqx)) `Apache-2.0` `Docker/Erlang`
- [FHEM](https://fhem.de/fhem.html) - FHEM 用于自动化家庭中的常见任务，如开关灯具和加热。它还可以用于记录诸如温度或功耗的事件。您可以通过 Web 或智能手机前端、Telnet 或直接通过 TCP/IP 进行控制。 ([Source Code](https://svn.fhem.de/trac)) `GPL-3.0` `Perl`
- [FlowForge](https://flowforge.com/) - FlowForge 允许公司以可靠、可扩展和安全的方式部署 Node-RED 应用程序。FlowForge 平台为 Node-RED 开发团队提供 DevOps 能力。 ([Source Code](https://github.com/flowforge/flowforge)) `Apache-2.0` `Nodejs/Docker/K8S`
- [Gladys](https://gladysassistant.com/) - Gladys是一款以隐私为先的开源家庭助手。 ([Source Code](https://github.com/GladysAssistant/Gladys)) `Apache-2.0` `Nodejs/Docker`
- [Home Assistant](https://home-assistant.io/) - 开源的家庭自动化平台。 ([Demo](https://home-assistant.io/demo/), [Source Code](https://github.com/home-assistant/core)) `Apache-2.0` `Python/Docker`
- [ioBroker](https://www.iobroker.net/) - 面向物联网的集成平台，专注于建筑自动化、智能计量、环境辅助生活、过程自动化、可视化和数据记录。 ([Source Code](https://github.com/ioBroker/ioBroker)) `MIT` `Nodejs`
- [Node RED](https://nodered.org/) - 基于浏览器的流程编辑器，帮助您将硬件设备、API和在线服务连接起来，创建物联网（IoT）解决方案。 ([Source Code](https://github.com/node-red/node-red)) `Apache-2.0` `Nodejs/Docker`
- [openHAB](https://www.openhab.org) - 面向家庭自动化的供应商和技术无关的开源软件。 ([Source Code](https://github.com/openhab/openhab-core)) `EPL-2.0` `Java`
- [OpenRemote](https://openremote.io) - 开源物联网平台 - 物联网资产管理、流程规则和WHEN-THEN规则、数据可视化、边缘网关。 ([Demo](https://demo.openremote.io/), [Source Code](https://github.com/openremote/openremote)) `AGPL-3.0` `Java`
- [SIP Irrigation Control](https://dan-in-ca.github.io/SIP/) - 用于喷头/灌溉控制的开源软件。 ([Source Code](https://github.com/Dan-in-CA/SIP)) `GPL-3.0` `Python`
- [Tasmota](https://tasmota.com) - 用于ESP设备的开源固件。具备快速设置和更新的完全本地控制。支持MQTT、Web UI、HTTP或串口控制。可使用定时器、规则或脚本进行自动化。与家庭自动化解决方案集成。 ([Source Code](https://github.com/arendst/Tasmota)) `GPL-3.0` `C/C++`
- [Thingsboard](https://thingsboard.io/) - 开源的物联网平台 - 设备管理、数据收集、处理和可视化。 ([Demo](https://demo.thingsboard.io/signup), [Source Code](https://github.com/thingsboard/thingsboard)) `Apache-2.0` `Java/Docker/K8S`
- [WebThings Gateway](https://webthings.io/gateway/) - WebThings是Web of Things的开源实现，包括WebThings Gateway和WebThings Framework。 ([Source Code](https://github.com/WebThingsIO/gateway)) `MPL-2.0` `Nodejs`


### 状态/正常运行时间页面

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[正常运行时间](https://en.wikipedia.org/wiki/Uptime)是系统可靠性的度量，表示计算机或其他机器正常工作并可用的时间百分比。

_Related: [监控](#监控)_

- [cState](https://cstate.netlify.app/) - 用于超快速Hugo的静态状态页面。清晰的设计，最小化的JS，超轻的HTML/CSS，高度可定制，可选的管理面板，只读API，支持IE8+。最适用于Netlify、Docker。 ([Demo](https://cstate.mnts.lt/), [Source Code](https://github.com/cstate/cstate)) `MIT` `Go`
- [Gatus](https://github.com/TwiN/gatus) - 自动化服务健康仪表板。 ([Demo](https://status.twin.sh)) `Apache-2.0` `Docker/K8S`
- [StatPing.ng](https://statping-ng.github.io/) - 一个易于使用的网站和应用程序状态页面。StatPing将自动获取应用程序并渲染一个具有丰富功能的漂亮状态页面，帮助您构建更好的状态页面。 ([Source Code](https://github.com/statping-ng/statping-ng)) `GPL-3.0` `Docker/Go`
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) - 类似于 "Uptime Robot" 的自托管网站监控工具。 ([Demo](https://demo.kuma.pet)) `MIT` `Docker/Nodejs`
- [Vigil](https://crates.io/crates/vigil-server) - 微服务状态页面。监视分布式基础架构并发送警报（Slack、短信等）。 ([Demo](https://status.crisp.chat/), [Source Code](https://github.com/valeriansaliou/vigil)) `MPL-2.0` `Rust/Docker/deb`


### 电子商务

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[电子商务](https://en.wikipedia.org/wiki/E-commerce)软件。

_Related: [社区支持农业（CSA）](#社区支持农业（csa）)_

- [Aimeos](https://aimeos.org/) - 极快速、开源的电子商务框架，用于构建定制的在线商店、市场和复杂的B2B应用，可与 Laravel 一起扩展至数十亿商品。 ([Demo](https://demo.aimeos.org/), [Source Code](https://github.com/aimeos)) `LGPL-3.0/MIT` `PHP`
- [Bagisto](https://bagisto.com/en/) - 领先的 Laravel 开源电子商务框架，具备多库存来源、税收、本地化、Dropshipping 等令人兴奋的功能。 ([Demo](https://demo.bagisto.com/), [Source Code](https://github.com/bagisto/bagisto)) `MIT` `PHP`
- [CoreShop](https://www.coreshop.org) - CoreShop是Pimcore的电子商务插件。 ([Source Code](https://github.com/coreshop/CoreShop)) `GPL-3.0` `PHP`
- [Drupal Commerce](https://drupalcommerce.org) - Drupal Commerce 是 Drupal CMS 的一款流行的电子商务模块，支持数十个支付、运输和与购物相关的模块。 ([Source Code](https://git.drupalcode.org/project/commerce)) `GPL-2.0` `PHP`
- [Magento开源版](https://github.com/magento/magento2) - 领先的开放式全渠道创新提供商。 `OSL-3.0` `PHP`
- [Mailchimp Open Commerce](https://mailchimp.com/developer/open-commerce/) - 可定制的、实时响应的JavaScript商务平台（以前是Reaction Commerce）。 ([Source Code](https://github.com/reactioncommerce/reaction)) `GPL-3.0` `Nodejs`
- [MedusaJs](https://medusajs.com/) - Medusa是一款开源的无头商业引擎，使开发人员能够创建令人惊叹的数字商业体验。 ([Demo](https://next.medusajs.com/), [Source Code](https://github.com/medusajs/medusa)) `MIT` `Nodejs`
- [Microweber](https://microweber.com/) - 拖放式 CMS 和在线商店。 ([Demo](https://demo.microweber.org/), [Source Code](https://github.com/microweber/microweber)) `Apache-2.0` `PHP`
- [Open Source POS](https://github.com/opensourcepos/opensourcepos) - 开源销售点是一个基于Web的销售点系统。 `MIT` `PHP`
- [OpenCart](https://www.opencart.com) - 免费的开源购物车解决方案。 ([Source Code](https://github.com/opencart/opencart)) `GPL-3.0` `PHP`
- [OXID eShop](https://oxidforge.org/en/) - OXID eShop是一款功能丰富、灵活的开源电子商务软件。 ([Source Code](https://github.com/OXID-eSales/oxideshop_ce)) `GPL-3.0` `PHP`
- [PrestaShop](https://www.prestashop.com/) - PrestaShop提供免费、开源且完全可扩展的电子商务解决方案。 ([Demo](https://demo.prestashop.com/), [Source Code](https://github.com/PrestaShop/PrestaShop)) `OSL-3.0` `PHP`
- [Pretix](https://pretix.eu/) - 用于事件的基于Django的门票销售平台。 ([Source Code](https://github.com/pretix)) `Apache-2.0` `Python`
- [s-cart](https://s-cart.org/) - S-Cart 是一个基于 Laravel 框架构建的免费个人和企业电子商务网站项目。 ([Demo](https://demo.s-cart.org/), [Source Code](https://github.com/s-cart/s-cart)) `MIT` `PHP`
- [Saleor](https://saleor.io) - 基于 Django 的开源电子商务商店前端。 ([Demo](https://demo.saleor.io/), [Source Code](https://github.com/saleor/saleor)) `BSD-3-Clause` `Docker/Python`
- [Shopware Community Edition](https://www.shopware.com/community/) - 基于 PHP 的德国制造的开源电子商务软件。 ([Demo](https://www.shopware.com/en/test-demo/), [Source Code](https://github.com/shopware/platform)) `MIT` `PHP`
- [Solidus](https://solidus.io/) - 一个免费的、开源的电子商务平台，为您的商店提供完全控制。 ([Demo](http://demo.solidus.io/), [Source Code](https://github.com/solidusio/solidus)) `BSD-3-Clause` `Ruby/Docker`
- [Spree Commerce](https://spreecommerce.org) - Spree是一个完整的、模块化的、基于API的Ruby on Rails开源电子商务解决方案。 ([Demo](https://new-ux.spreecommerce.org/), [Source Code](https://github.com/spree/spree)) `BSD-3-Clause` `Ruby`
- [Sylius](https://sylius.com) - 基于 Symfony2 的开源全栈电子商务平台。 ([Demo](https://sylius.com/try/), [Source Code](https://github.com/Sylius/Sylius)) `MIT` `PHP`
- [Thelia](https://thelia.net/) - Thelia 是一款开源且灵活的电子商务解决方案。 ([Demo](https://demo.thelia.net/), [Source Code](https://github.com/thelia/thelia)) `LGPL-3.0` `PHP`
- [Vendure](https://www.vendure.io) - 一个无界面的商业框架。 ([Demo](https://demo.vendure.io), [Source Code](https://github.com/vendure-ecommerce/vendure)) `MIT` `Nodejs`
- [WooCommerce](https://woocommerce.com/) - 基于WordPress的电子商务解决方案。 ([Source Code](https://github.com/woocommerce/woocommerce)) `GPL-3.0` `PHP`


### 监控

**[`^        back to top        ^`](#Awesome-Selfhosted)**

用于[监控](https://en.wikipedia.org/wiki/Monitoring#Computing)系统、网络、应用程序和网站的软件。

**Please visit [awesome-sysadmin/监控](https://github.com/awesome-foss/awesome-sysadmin#monitoring), [awesome-sysadmin/指标和指标收集](https://github.com/awesome-foss/awesome-sysadmin#metrics--metric-collection)**



### 知识管理工具

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[知识管理](https://en.wikipedia.org/wiki/Knowledge_management)是有关创造、共享、使用和管理知识和信息的方法的集合。

_Related: [笔记和编辑器](#笔记和编辑器), [维基](#维基), [数据库管理](#数据库管理)_

- [Atomic Server](https://github.com/atomicdata-dev/atomic-server) - 具有文档（类似于 Notion）、表格、搜索和强大的关联数据 API 的知识图数据库。轻量级、非常快速，且无运行时依赖。 ([Demo](https://atomicdata.dev/)) `MIT` `Docker/Rust`
- [Digimindmap](https://ladigitale.dev/digimindmap/#/) - 创建简单的思维导图（法语文档）。 ([Demo](https://ladigitale.dev/digimindmap/#/), [Source Code](https://codeberg.org/ladigitale/digimindmap)) `AGPL-3.0` `Nodejs/PHP`
- [My Mind](https://github.com/ondras/my-mind) - 用于创建和管理思维导图的 Web 应用程序。 ([Demo](https://my-mind.github.io/?url=examples%2Ffeatures.mymind)) `MIT` `Javascript`
- [TeamMapper](https://github.com/b310-digital/teammapper) - 托管并创建自己的思维导图。与团队共享思维导图会话，并在思维导图上进行实时协作。 ([Demo](https://map.kits.blog)) `MIT` `Docker/Nodejs`


### 社区支持农业（CSA）

**[`^        back to top        ^`](#Awesome-Selfhosted)**

用于社区支持的农业和食品合作社的管理和行政工具。

_Related: [电子商务](#电子商务)_

- [ACP Admin](https://acp-admin.ch/) - CSA 管理。管理成员、订阅、交付、投放地点、成员参与、发票和电子邮件（文档以法语提供）。 ([Source Code](https://github.com/acp-admin/acp-admin/)) `MIT` `Ruby`
- [FoodCoopShop](https://www.foodcoopshop.com/) - 面向食品合作社的用户友好开源软件。 ([Source Code](https://github.com/foodcoopshop/foodcoopshop)) `AGPL-3.0` `PHP/Docker`
- [Foodsoft](https://foodcoops.net/) - 基于Web的软件，用于管理非营利性食品合作社（产品目录、订购、会计、工作安排）。 ([Source Code](https://github.com/foodcoops/foodsoft)) `AGPL-3.0` `Docker/Ruby`
- [juntagrico](https://juntagrico.org/) - 社区花园和蔬菜合作社的管理平台。 ([Source Code](https://github.com/juntagrico/juntagrico)) `LGPL-3.0` `Python`
- [Local Food Nodes](https://localfoodnodes.org/) - 民众主导的本地食品市场和CSA的开源平台。 ([Source Code](https://gitlab.com/localfoodnodes/localfoodnodes)) `MIT` `PHP`
- [Open Food Network](https://www.openfoodnetwork.org/) - 本地食品的在线市场。它支持一系列独立的在线食品商店，将农民和食品中心与个人和本地企业连接起来。 ([Source Code](https://github.com/openfoodfoundation/openfoodnetwork)) `AGPL-3.0` `Ruby`
- [OpenOlitor](https://openolitor.org/) - OpenOlitor是一个社区支持农业团体的管理平台。 ([Source Code](https://github.com/OpenOlitor/openolitor-server)) `AGPL-3.0` `Scala`
- [teikei](https://github.com/teikei/teikei) - 一款基于众包数据的社区支持农业地图的网络应用。 ([Demo](https://ernte-teilen.org/karte/#/)) `AGPL-3.0` `Nodejs`


### 笔记和编辑器

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[笔记编辑](https://en.wikipedia.org/wiki/Note-taking)器。

_Related: [维基](#维基)_

- [Benotes](https://benotes.org/) - 一个开源的自托管笔记和书签管理的Web应用。 ([Source Code](https://github.com/fr0tt/benotes)) `MIT` `PHP/Docker`
- [DailyTxT](https://github.com/PhiTux/DailyTxT) - 加密日记Web应用，可保存每天的个人记忆。包括搜索功能和加密文件上传。 `MIT` `Docker`
- [Dillinger](https://dillinger.io/) - 最后的Markdown编辑器。 ([Source Code](https://github.com/joemccann/dillinger)) `MIT` `Nodejs`
- [Dnote](https://www.getdnote.com) - 具有多设备同步和Web界面的简单命令行笔记本。 ([Source Code](https://github.com/dnote/dnote)) `AGPL-3.0` `Go`
- [draw.io](https://draw.io) - 用于制作流程图、流程图、组织图、UML、ER和网络图的图表软件。 ([Source Code](https://github.com/jgraph/drawio)) `Apache-2.0` `Javascript/Docker`
- [flatnotes](https://github.com/dullage/flatnotes) - 一个自托管的、无数据库的记事 Web 应用，利用平面文件夹中的 Markdown 文件进行存储。 ([Demo](https://demo.flatnotes.io)) `MIT` `Docker`
- [HedgeDoc](https://demo.hedgedoc.org/) - 跨所有平台的实时协作Markdown笔记，以前被称为CodiMD和HackMD CE。 ([Source Code](https://github.com/hedgedoc/hedgedoc)) `AGPL-3.0` `Docker/Nodejs`
- [Joplin](https://joplinapp.org/) - Joplin是一款带有Markdown编辑器和加密支持的笔记应用，适用于移动和桌面平台。在客户端运行，并通过自托管的Nextcloud或类似服务同步（替代Evernote）。 ([Source Code](https://github.com/laurent22/joplin)) `MIT` `Nodejs`
- [kiwix-serve](https://www.kiwix.org/en/downloads/kiwix-serve/) - 从 ZIM 文件提供维基的 HTTP 守护进程。 ([Source Code](https://github.com/kiwix/kiwix-tools)) `GPL-3.0` `C++`
- [Livebook](https://livebook.dev) - 实时协作的基于Markdown的笔记本应用，支持运行Elixir代码片段、TeX和Mermaid图表。可通过Docker或Elixir轻松部署。 ([Source Code](https://github.com/livebook-dev/livebook)) `Apache-2.0` `Elixir/Docker`
- [Meemo](https://meemo.minimal-space.de/) - 具有Markdown支持的个人笔记流。 ([Source Code](https://github.com/cloudron-io/meemo)) `MIT` `Nodejs`
- [Memos](https://usememos.com/) - 一个开源、自托管的知识库，可与 SQLite 数据库文件配合使用。 ([Source Code](https://github.com/usememos/memos)) `MIT` `Docker/Go`
- [minimalist-web-notepad](https://github.com/pereorga/minimalist-web-notepad) - 极简 notepad.cc 克隆。 ([Demo](https://notes.orga.cat/)) `Apache-2.0` `PHP`
- [Note Mark](https://notemark.docs.enchantedcode.co.uk/) - 一款极简的基于Web的Markdown笔记应用。 ([Source Code](https://github.com/enchant97/note-mark)) `AGPL-3.0` `Docker`
- [Oddmuse](https://oddmuse.org/) - 用Perl编写的简单维基引擎。无需数据库。 ([Source Code](https://github.com/kensanata/oddmuse)) `GPL-3.0` `Perl`
- [Overleaf](https://www.overleaf.com/) - 基于Web的协作LaTeX编辑器。 ([Source Code](https://github.com/overleaf/overleaf)) `AGPL-3.0` `Ruby`
- [Plainpad](https://alextselegidis.com/get/plainpad/) - Plainpad 是一个现代的云记事应用，利用渐进式Web应用技术的最佳特性。 ([Demo](https://alextselegidis.com/try/plainpad/), [Source Code](https://github.com/alextselegidis/plainpad)) `GPL-3.0` `PHP`
- [Standard Notes](https://docs.standardnotes.com/self-hosting/getting-started) - 简单而私密的笔记应用。在完成更多工作的同时保护您的隐私。这就是Standard Notes。 ([Demo](https://app.standardnotes.org/), [Source Code](https://github.com/standardnotes/app)) `GPL-3.0` `Ruby`
- [Trilium Notes](https://github.com/zadam/trilium) - Trilium Notes是一个层次化的笔记应用，重点是构建大型个人知识库。 `AGPL-3.0` `Nodejs/Docker/K8S`
- [turndown](https://mixmark-io.github.io/turndown/) - 用Javascript编写的HTML到Markdown转换器。 ([Source Code](https://github.com/mixmark-io/turndown)) `MIT` `Javascript`
- [Turtl](https://turtl.it/) - 完全私密的个人数据库和笔记应用。 ([Source Code](https://github.com/turtl)) `GPL-3.0` `CommonLisp`
- [Writing](https://josephernest.github.io/writing/) - 轻量级无干扰文本编辑器，基于浏览器（支持Markdown和LaTeX）。写作时无延迟。 ([Source Code](https://github.com/josephernest/writing)) `MIT` `Javascript`


### 粘贴板

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[Pastebin](https://en.wikipedia.org/wiki/Pastebin)是一种在线内容托管服务，用于分享和存储代码和文本。

- [bepasty](https://bepasty-server.readthedocs.io/en/latest/) - 适用于各种文件的粘贴板。 ([Source Code](https://github.com/bepasty/bepasty-server)) `BSD-2-Clause` `Python/deb`
- [bin](https://github.com/w4/bin) - 实际上是极简主义的粘贴板。 `WTFPL/0BSD` `Rust`
- [dpaste](https://dpaste.org/) - 简单的粘贴板，支持多种文本和代码选项，并提供易记的短网址结果。 ([Source Code](https://github.com/DarrenOfficial/dpaste)) `MIT` `Docker/Django`
- [Drift](https://github.com/MaxLeiter/drift) - 自托管的 GitHub Gist 克隆。 ([Demo](https://drift.maxleiter.com/)) `MIT` `Nodejs`
- [ExBin](https://github.com/m1dnight/exbin) - 一个具有公共/私有片段和netcat服务器的pastebin。 `MIT` `Docker`
- [FlashPaper](https://github.com/AndrewPaglusch/FlashPaper) - 一次性加密的零知识密码/秘密共享应用，专注于简单性和安全性。无需数据库或复杂的设置。 ([Demo](https://flashpaper.io)) `MIT` `Docker/PHP`
- [Hasty Paste](https://enchantedcode.co.uk/hasty-paste/) - 一个快速粘贴文本并共享的地方。主要用于分享调试日志等，以帮助开发人员提供技术支持。该项目旨在既快速又简约。 ([Source Code](https://github.com/enchant97/hasty-paste)) `AGPL-3.0` `Docker/Python`
- [Hemmelig](https://hemmelig.app) - 跨组织或私人共享加密的秘密。 ([Source Code](https://github.com/HemmeligOrg/Hemmelig.app)) `MIT` `Docker/Nodejs`
- [MicroBin](https://github.com/szabodanika/microbin) - 简单、高性能、可配置、完全自包含的 pastebin 和 URL 缩短服务。 `BSD-3-Clause` `Rust/Docker`
- [Opengist](https://github.com/thomiceli/opengist) - 由 Git 提供支持的自托管粘贴板。 ([Demo](https://opengist.thomice.li)) `AGPL-3.0` `Docker/Go/Nodejs`
- [paaster](https://paaster.io) - Paaster是一个默认安全的端到端加密的Pastebin，建立在简单性的基础上。 ([Source Code](https://github.com/WardPearce/paaster)) `GPL-3.0` `Docker`
- [Password Pusher](https://pwpush.com) - 一个简单易用的应用程序，可以安全地通过网络传递密码（或文本）。密码在一定数量的查看和/或时间过去后会自动过期。 ([Source Code](https://github.com/pglombardo/PasswordPusher)) `GPL-3.0` `Docker/K8S/Ruby`
- [Pastefy](https://pastefy.app/) - 美观、简单易用的Pastebin，支持可选的客户端加密、多标签粘贴、API、带有突出显示的编辑器等功能。 ([Source Code](https://github.com/interaapps/pastefy), [Clients](https://github.com/topics/pastefy-addon)) `MIT` `Docker/K8S/Java`
- [PrivateBin](https://privatebin.info/) - PrivateBin是一个极简主义的、开源的在线粘贴板/讨论板，服务器对托管的数据毫不知情。 ([Demo](https://privatebin.net/), [Source Code](https://github.com/PrivateBin/PrivateBin)) `Zlib` `PHP`
- [PurritoBin](https://github.com/PurritoBin/PurritoBin) - 超快、极简、加密的命令行粘贴板，服务器不了解粘贴数据。 `ISC` `C++`
- [rustypaste](https://github.com/orhun/rustypaste) - 一个极简的文件上传/粘贴服务。 `MIT` `Rust`
- [SnyPy](https://snypy.com) - 开源的本地代码片段管理器。 ([Demo](https://app.snypy.com), [Source Code](https://github.com/snypy)) `MIT` `Docker`
- [Sup3rS3cretMes5age](https://github.com/algolia/sup3rS3cretMes5age) - 使用 HashiCorp Vault 作为秘密存储的非常简单（部署和使用）的秘密消息服务。 `MIT` `Go`
- [wantguns/bin](https://github.com/wantguns/bin) - 用于文本和二进制文件的极简过去式服务，以单个静态链接二进制文件的形式提供。 ([Demo](https://basedbin.fly.dev)) `GPL-3.0` `Rust/Docker`
- [Wastebin](https://github.com/matze/wastebin) - 轻量、极简和快速的过去式服务，带有SQLite后端。 ([Demo](https://bin.bloerg.net)) `MIT` `Rust/Docker`
- [YABin](https://github.com/Yureien/YABin) - 一个包含丰富功能但保持简单的Pastebin。支持可选的端到端加密、客户端CLI应用程序、语法高亮、极简UI、API、键盘快捷键等。甚至可以在无服务器环境中运行。 ([Demo](https://bin.sohamsen.me/)) `MIT` `Nodejs/Docker`


### 维基

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[维基](https://en.wikipedia.org/wiki/Wiki) 是一种由其观众直接使用 Web 浏览器协作编辑和管理的出版物。

_Related: [静态网站生成器](#静态网站生成器)_

_See also: [Wikimatrix](https://www.wikimatrix.org/), [wiki软件清单 - Wikipedia](https://en.wikipedia.org/wiki/List_of_wiki_software), [wiki软件比较 - Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_wiki_software)_

- [AmuseWiki](https://amusewiki.org/) - Amusewiki 基于 Emacs Muse 标记语言，基本上与原始实现保持兼容。它可以作为只读站点、作为经过审核的维基，或者作为完全开放的维基，甚至作为私有站点使用。 ([Demo](https://sandbox.amusewiki.org), [Source Code](https://github.com/melmothx/amusewiki)) `GPL-1.0` `Perl/Docker`
- [BookStack](https://www.bookstackapp.com/) - BookStack 是一个简单、自托管且易于使用的平台，用于组织和存储信息。它允许以书籍的形式存储文档。 ([Demo](https://www.bookstackapp.com/#demo), [Source Code](https://github.com/BookStackApp/BookStack)) `MIT` `PHP/Docker`
- [django-wiki](https://github.com/django-wiki/django-wiki) - 拥有复杂功能的维基系统，可简单集成且具有出色的界面。以风格存储您的知识：使用Django模型。 ([Demo](https://demo.django-wiki.org/)) `GPL-3.0` `Python`
- [Documize](https://documize.com) - 现代文档和Wiki软件，内置工作流，单个二进制可执行文件，只需带上 MySQL/Percona。 ([Source Code](https://github.com/documize/community)) `AGPL-3.0` `Go`
- [DokuWiki](https://www.dokuwiki.org/DokuWiki) - 易于使用、轻量级、符合标准的维基引擎，具有简单的语法，允许在维基之外阅读数据。所有数据都存储在纯文本文件中，因此不需要数据库。 ([Source Code](https://github.com/dokuwiki/dokuwiki)) `GPL-2.0` `PHP`
- [Gitit](https://github.com/jgm/gitit) - 存储页面和上传文件于Git存储库的维基程序，可以使用VCS命令行工具或维基的Web界面进行修改。 `GPL-2.0` `Haskell`
- [Gollum](https://github.com/gollum/gollum) - 简单的、由Git驱动的维基，具有友好的API和本地前端。 `MIT` `Ruby`
- [Mediawiki](https://www.mediawiki.org/wiki/MediaWiki) - MediaWiki是一款用PHP编写的免费开源维基软件包。它作为Wikipedia和其他Wikimedia项目的平台，每月被数亿人使用。 ([Demo](https://en.wikipedia.org/wiki/Main_Page), [Source Code](https://phabricator.wikimedia.org/diffusion/MW/)) `GPL-2.0` `PHP`
- [Mycorrhiza Wiki](https://mycorrhiza.wiki/) - 使用 Go 编写的基于文件系统和 git 的维基引擎，主要使用 Mycomarkup 作为其主要标记语言。 ([Source Code](https://github.com/bouncepaw/mycorrhiza/)) `AGPL-3.0` `Go`
- [Otter Wiki](https://github.com/redimp/otterwiki) - 使用Markdown的简单易用的Wiki软件。 `MIT` `Docker`
- [Outline](https://www.getoutline.com/) `⚠` - 为您的团队提供的开放、可扩展的Wiki。 ([Source Code](https://github.com/outline/outline)) `BSD-3-Clause` `Nodejs/Docker`
- [Pepperminty Wiki](https://github.com/sbrl/Pepperminty-Wiki) - 完全由Markdown驱动的维基，包含在一个单独的PHP文件中。 ([Demo](https://starbeamrainbowlabs.com/labs/peppermint/build/)) `MPL-2.0` `PHP`
- [PmWiki](https://www.pmwiki.org) - 基于Wiki的系统，用于协同创建和维护网站。 `GPL-3.0` `PHP`
- [Raneto](https://raneto.com/) - Raneto是一个开源的知识库平台，使用静态的Markdown文件来支持您的知识库。 ([Source Code](https://github.com/ryanlelek/Raneto)) `MIT` `Nodejs`
- [TiddlyWiki](https://tiddlywiki.com/) - 可重复使用的非线性个人 Web 笔记本。 ([Source Code](https://github.com/Jermolene/TiddlyWiki5)) `BSD-3-Clause` `Nodejs`
- [Tiki](https://tiki.org/HomePage) - 具有最多内置功能的 Wiki CMS Groupware。 ([Demo](https://tiki.org/Try-Tiki), [Source Code](https://gitlab.com/tikiwiki/tiki)) `LGPL-2.1` `PHP`
- [WackoWiki](https://wackowiki.org/) - WackoWiki是一款轻量且易于安装的多语言Wiki引擎。 ([Source Code](https://github.com/WackoWiki/wackowiki)) `BSD-3-Clause` `PHP`
- [Wiki.js](https://js.wiki/) - 使用Git和Markdown的现代、轻量且功能强大的Wiki应用程序。 ([Demo](https://docs.requarks.io), [Source Code](https://github.com/Requarks/wiki)) `AGPL-3.0` `Nodejs/Docker/K8S`
- [WikiDocs](http://wikidocs.it) - 一个无数据库的 Markdown 纯文本 wiki 引擎。 ([Demo](https://demo.wikidocs.it), [Source Code](https://github.com/Zavy86/WikiDocs)) `MIT` `PHP/Docker`
- [WiKiss](https://wikiss.tuxfamily.org/) - Wiki，简单易用且易于安装。 ([Source Code](https://svnweb.tuxfamily.org/listing.php?repname=wikiss/svn&path=%2F&sc=0)) `GPL-2.0` `PHP`
- [Wikmd](https://github.com/Linbreux/wikmd) - 使用Markdown和Git的现代简单基于文件的Wiki。 `MIT` `Python/Docker`
- [XWiki](https://www.xwiki.org) - 第二代维基，允许用户通过强大的基于扩展的架构扩展其功能。 ([Demo](https://playground.xwiki.org), [Source Code](https://github.com/xwiki/xwiki-platform)) `LGPL-2.1` `Java/Docker/deb`
- [Zim](https://zim-wiki.org/) - 用于维护wiki页面集合的图形文本编辑器。每个页面可以包含到其他页面的链接、简单格式和图片。 ([Source Code](https://github.com/zim-desktop-wiki/zim-desktop-wiki)) `GPL-2.0` `Python/deb`


### 联邦身份和认证

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[联邦身份](https://en.wikipedia.org/wiki/Federated_identity)和[认证](https://en.wikipedia.org/wiki/Electronic_authentication)软件。

**Please visit [awesome-sysadmin/身份管理](https://github.com/awesome-foss/awesome-sysadmin#identity-management)**



### 自动化

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[自动化](https://en.wikipedia.org/wiki/Automation)软件，旨在减少人类在流程中的干预。

_Related: [物联网（IoT）](#物联网（iot）), [软件开发 - 持续集成和部署](#软件开发---持续集成和部署)_

- [Activepieces](https://www.activepieces.com) - 无代码业务自动化工具，类似于 Zapier 或 Tray。例如，您可以为每个新的 Trello 卡片发送 Slack 通知。 ([Source Code](https://github.com/activepieces/activepieces)) `MIT` `Docker`
- [ActiveWorkflow](https://github.com/automaticmode/active_workflow) - 基于软件代理的智能流程和工作流自动化平台。 `MIT` `Ruby`
- [Apache Airflow](https://airflow.apache.org/) - Airflow 是一个用于以编程方式编写、调度和监视工作流的平台。 ([Source Code](https://github.com/apache/airflow/)) `Apache-2.0` `Python/Docker`
- [Automatisch](https://automatisch.io) - 业务自动化工具，可连接不同的服务，如Twitter、Slack等，以自动化业务流程（类似于Zapier的替代品）。 ([Source Code](https://github.com/automatisch/automatisch)) `AGPL-3.0` `Docker`
- [betanin](https://github.com/sentriz/betanin) - 音乐组织中间人，位于您的种子客户端和音乐播放器之间。基于beets.io，类似于Sonarr和Radarr。 `GPL-3.0` `Python/Docker`
- [changedetection.io](https://github.com/dgtlmoon/changedetection.io) - 自托管工具，用于保持与网站内容变化的最新状态。 `Apache-2.0` `Python/Docker`
- [ChiefOnboarding](https://chiefonboarding.com) - 员工入职平台，允许您分配用户帐户并创建包含待办事项、资源、文本/电子邮件/Slack消息等的序列！可作为Web门户和Slack机器人使用。 ([Source Code](https://github.com/chiefonboarding/ChiefOnboarding)) `AGPL-3.0` `Docker`
- [Eonza](https://www.eonza.org) - Eonza用于在服务器或VPS主机上创建脚本并自动化任务。可以从任何设备上的任何浏览器管理服务器。 ([Source Code](https://github.com/gentee/eonza)) `MIT` `Go`
- [Exadel CompreFace](https://exadel.com/solutions/compreface/) - 人脸识别系统，提供用于人脸识别、人脸检测和其他人脸服务的REST API，并可轻松通过Docker部署。有适用于Python和JavaScript语言的SDK。无需事先机器学习技能即可使用。 ([Source Code](https://github.com/exadel-inc/CompreFace)) `Apache-2.0` `Docker/Java/Nodejs`
- [feedmixer](https://github.com/cristoper/feedmixer) - FeedMixer是一个WSGI（Python3）微型Web服务，接受一组feed URL并返回由每个给定feed的最新n个条目组成的新feed（返回Atom、RSS或JSON）。 ([Demo](https://mretc.net/feedmixer/json?f=https://hnrss.org/newest&f=https://americancynic.net/atom.xml&n=1)) `WTFPL` `Python`
- [Headphones](https://github.com/rembo10/headphones) - 用Python编写的支持SABnzbd、NZBget、Transmission、µTorrent、Deluge和Blackhole的NZB和Torrent的自动音乐下载器。 `GPL-3.0` `Python`
- [Healthchecks](https://healthchecks.io/) - Django应用程序，监听ping并在ping延迟时发送警报。 ([Source Code](https://github.com/healthchecks/healthchecks)) `BSD-3-Clause` `Python`
- [homebank-converter](https://github.com/Binnette/homebank-converter) - Web应用，用于将导出的银行文件转换为兼容的Homebank CSV格式。 ([Demo](https://binnette.github.io/homebank-converter/)) `AGPL-3.0` `Javascript`
- [HRConvert2](https://github.com/zelon88/HRConvert2) - 拖放文件转换服务器，支持基于会话的身份验证、自动临时文件维护和日志记录功能。 `GPL-3.0` `PHP`
- [Huginn](https://github.com/huginn/huginn) - 允许您构建代理程序，监视并代表您采取行动。 `MIT` `Ruby`
- [Kestra](https://kestra.io) - 基于事件驱动的、与语言无关的平台，用于创建、调度和监视工作流。通过代码协调数据管道和任务，如ETL和ELT。 ([Source Code](https://github.com/kestra-io/kestra)) `Apache-2.0` `Docker`
- [Kibitzr](https://kibitzr.github.io) - 轻量级个人网络助手，具有强大的集成功能。 ([Source Code](https://github.com/kibitzr/kibitzr)) `MIT` `Python`
- [Krayin](https://krayincrm.com/) - 免费且开源的Laravel CRM应用程序。 ([Demo](https://demo.krayincrm.com/), [Source Code](https://github.com/krayin/laravel-crm)) `MIT` `PHP`
- [LazyLibrarian](https://gitlab.com/LazyLibrarian/LazyLibrarian) `⚠` - LazyLibrarian是一个用于追踪作者并获取所有数字阅读需求的元数据的程序。它使用Goodreads、Librarything和可选的GoogleBooks作为作者信息和图书信息的来源。 `GPL-3.0` `Python`
- [Leon](https://getleon.ai) - 开源个人助手，可以运行在您的服务器上。 ([Source Code](https://github.com/leon-ai/leon)) `MIT` `Nodejs`
- [Lidarr](https://lidarr.audio/) - Lidarr是一个面向Usenet和BitTorrent用户的音乐收藏管理器。 ([Source Code](https://github.com/Lidarr/Lidarr)) `GPL-3.0` `C#/Docker`
- [Matchering](https://github.com/sergree/matchering) - 用于自动音乐母带处理的容器化Web应用（替代LANDR、eMastered和MajorDecibel）。 `GPL-3.0` `Docker`
- [Medusa](https://pymedusa.com/) - 用于电视节目的自动视频库管理器。它会监视您喜爱的节目的新集数，一旦发布，就会进行自动管理。 ([Source Code](https://github.com/pymedusa/Medusa), [Clients](https://github.com/medusajs/nextjs-starter-medusa)) `GPL-3.0` `Python`
- [MetaTube](https://github.com/JVT038/MetaTube) `⚠` - 一个 Web 图形用户界面，可自动从 YouTube 下载音乐，并从 Spotify、Deezer 或 Musicbrainz 添加元数据。 `GPL-3.0` `Python`
- [MeTube](https://github.com/alexta69/metube) - 用于 youtube-dl 的 Web 图形用户界面，支持播放列表。允许从数十个网站下载视频。 `AGPL-3.0` `Python/Nodejs/Docker`
- [Mylar3](https://mylarcomics.com/) - 自动漫画书(cbr/cbz)下载程序，用于NZB和种子下载。 ([Source Code](https://github.com/mylar3/mylar3)) `GPL-3.0` `Python/Docker`
- [nefarious](https://github.com/lardbit/nefarious) - 用于自动下载电影和电视节目的Web应用程序。 `GPL-3.0` `Python`
- [OliveTin](https://github.com/OliveTin/OliveTin) - OliveTin是一个用于运行Linux shell命令的Web界面。 `AGPL-3.0` `Go`
- [pyLoad](https://pyload.net/) - 一款轻量、可定制且可远程管理的下载器，用于支持1-click-hosting网站，如rapidshare.com或uploaded.to。 ([Source Code](https://github.com/pyload/pyload)) `GPL-3.0` `Python`
- [Radarr](https://radarr.video/) - Radarr是Sonarr的独立分支，专为通过Usenet和BitTorrent自动下载电影而重新设计，类似于Couchpotato。 ([Source Code](https://github.com/Radarr/Radarr)) `GPL-3.0` `C#/Docker`
- [SickChill](https://sickchill.github.io/) - SickChill 是一款用于 TV 剧集的自动视频库管理器。它会监视你喜欢的节目的新剧集，一旦发布就会自动处理。 ([Source Code](https://github.com/SickChill/SickChill)) `GPL-3.0` `Python/Docker`
- [SiteInspector](https://www.getsiteinspector.com/) - 用于捕捉网站拼写错误、语法错误、破损链接和其他错误的基于Web的工具。 ([Source Code](https://github.com/siteinspector/siteinspector)) `AGPL-3.0` `Docker`
- [Sonarr](https://sonarr.tv/) - 自动化的电视剧下载和管理工具，适用于Usenet和BitTorrent。它能够获取、排序和重命名新的剧集，并在更高质量的格式可用时自动提升已下载文件的质量。 ([Source Code](https://github.com/Sonarr/Sonarr)) `GPL-3.0` `C#/Docker`
- [StackStorm](https://stackstorm.com) - StackStorm（又名_Ops的IFTTT_）是面向事件的自动化解决方案，用于自动修复、安全响应、故障排除、部署等。包括规则引擎、工作流、160个集成包，具有6000多个操作和ChatOps。 ([Source Code](https://github.com/StackStorm/st2)) `Apache-2.0` `Python`
- [Tube Archivist](https://www.tubearchivist.com/) `⚠` - 您自己托管的YouTube媒体服务器：订阅、下载、索引、搜索和播放您喜爱的视频。 ([Source Code](https://github.com/tubearchivist/tubearchivist)) `GPL-3.0` `Python/Docker`
- [tubesync](https://github.com/meeb/tubesync) `⚠` - 将YouTube频道和播放列表同步到本地托管的媒体服务器。 `AGPL-3.0` `Docker/Python`
- [ydl_api_ng](https://github.com/Totonyus/ydl_api_ng) - 简单的youtube-dl REST API，用于在远程服务器上启动下载。 `GPL-3.0` `Python`
- [YoutubeDL-Material](https://github.com/Tzahi12345/YoutubeDL-Material) - 基于youtube-dl的Material Design风格的YouTube下载器。支持播放列表、质量选择、搜索、深色模式等，所有这些都具有清新现代的设计。 `MIT` `Nodejs/Docker`
- [YoutubeDL-Server](https://github.com/nbr23/youtube-dl-server) - 用于在服务器上下载视频的Web和REST接口。 `MIT` `Python/Docker`
- [yt-dlp Web UI](https://github.com/marcopeocchi/yt-dlp-web-ui) - 用于yt-dlp的Web GUI。 `MPL-2.0` `Docker/Go/Nodejs`
- [µTask](https://github.com/ovh/utask) - 一个建模和执行以yaml声明的业务流程的自动化引擎。 `BSD-3-Clause` `Go/Docker`


### 自托管解决方案

**[`^        back to top        ^`](#Awesome-Selfhosted)**

用于轻松安装、管理和配置自托管服务和应用程序的软件。

- [Ansible-NAS](https://github.com/DaveStephens/ansible-nas) - 使用这个 playbook 和一个 Ubuntu 服务器构建功能齐全的家庭服务器。 `MIT` `Ansible/Docker`
- [CasaOS](https://www.casaos.io/) - 一个简单、易于使用、优雅的开源家庭云系统。 ([Source Code](https://github.com/IceWhaleTech/CasaOS)) `Apache-2.0` `Go/Docker`
- [Cloudbox](https://cloudbox.works) - 基于Ansible的解决方案，快速部署Docker容器化的云媒体服务器。 ([Source Code](https://github.com/Cloudbox/Cloudbox)) `GPL-3.0` `Shell/Ansible`
- [DietPi](https://dietpi.com/) - Minimal Debian 操作系统，专为单板计算机优化，可轻松安装和管理多个用于在家自行托管的服务。 ([Source Code](https://github.com/MichaIng/DietPi)) `GPL-2.0` `Shell`
- [DockSTARTer](https://dockstarter.com/) - DockSTARTer 帮助您开始在 Docker 中运行的家庭服务器应用。 ([Source Code](https://github.com/GhostWriters/DockSTARTer)) `MIT` `Shell`
- [FreedomBox](https://freedombox.org/) - 社区项目，旨在开发、设计和推广运行免费软件的个人服务器，用于私人、个人通信。 ([Source Code](https://salsa.debian.org/freedombox-team/freedombox)) `AGPL-3.0` `Python/deb`
- [HomelabOS](https://homelabos.com) - 拥有您自己的离线优先、注重隐私的开源数据中心。通过简单的命令部署超过100个服务。 ([Source Code](https://gitlab.com/NickBusey/HomelabOS)) `MIT` `Docker`
- [LibreServer](https://libreserver.org/) - 基于Debian的家庭服务器配置。 ([Source Code](https://github.com/bashrc2/libreserver)) `AGPL-3.0` `Shell`
- [Mars Server](https://github.com/borjapazr/mars-server) - 使用Docker、Docker Compose、Make和Bash进行管理的家庭服务器。 `MIT` `Docker`
- [Mistborn](https://gitlab.com/cyber5k/mistborn) - Mistborn 是您自己的虚拟专用云平台和 WebUI，用于管理自托管的服务。 `MIT` `Shell/Docker`
- [NextCloudPi](https://github.com/nextcloud/nextcloudpi) - 预安装和预配置的Nextcloud，带有文本和Web管理界面以及自托管私人数据所需的所有工具。提供Raspberry Pi、Odroid、Rock64、Docker的安装映像，以及用于Armbian/Debian的curl安装程序。 `GPL-2.0` `Shell/PHP`
- [OpenMediaVault](https://www.openmediavault.org/) - OpenMediaVault是基于Debian Linux的下一代网络附加存储（NAS）解决方案。它包含诸如SSH、(S)FTP、SMB/CIFS、DAAP媒体服务器、RSync、BitTorrent客户端等服务。 ([Source Code](https://github.com/openmediavault/openmediavault)) `GPL-3.0` `PHP`
- [Sandstorm](https://sandstorm.io/) - 用于轻松、安全地运行自托管应用程序的个人服务器。 ([Demo](https://demo.sandstorm.io/), [Source Code](https://github.com/sandstorm-io/sandstorm)) `Apache-2.0` `C++/Shell`
- [StartOS](https://start9.com) - 基于浏览器的图形操作系统（OS），使运行个人服务器变得像运行个人电脑一样简单。 ([Source Code](https://github.com/Start9Labs/start-os)) `MIT` `Rust`
- [Syncloud](https://syncloud.org/) - 您自己的在线文件存储、社交网络或电子邮件服务器。 ([Source Code](https://github.com/syncloud/platform)) `GPL-3.0` `Go/Shell`
- [Tipi](https://runtipi.io/) - Homeserver manager. One command setup, one click installs for your favorites self-hosted apps. ([Source Code](https://github.com/meienberger/runtipi)) `GPL-3.0` `Shell`
- [UBOS](https://ubos.net/) - 运行在独立盒子上的Linux发行版（个人服务器和物联网设备）。单一命令安装和管理应用程序 - Jenkins、Mediawiki、Owncloud、WordPress等，以及其他功能。 `GPL-3.0` `Perl`
- [WikiSuite](https://wikisuite.org) - 最全面和集成的自由/开源企业软件套件。 ([Source Code](https://wikisuite.org/Source-Code)) `GPL-3.0/LGPL-2.1/Apache-2.0/MPL-2.0/MPL-1.1/MIT/AGPL-3.0` `Shell/Perl/deb`
- [xsrv](https://xsrv.readthedocs.io/) - 在您自己的服务器上安装和管理自托管的服务/应用程序。 ([Source Code](https://github.com/nodiscc/xsrv)) `GPL-3.0` `Ansible/Shell`
- [YunoHost](https://yunohost.org/) - 服务器操作系统，旨在使自托管对每个人都更容易访问。 ([Demo](https://yunohost.org/#/try), [Source Code](https://github.com/YunoHost)) `AGPL-3.0` `Python/Shell`


### 虚拟专用网络（VPN）

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[虚拟专用网络（VPN）](https://en.wikipedia.org/wiki/Virtual_private_network)将私人网络扩展到公共网络，并使用户能够在共享或公共网络上发送和接收数据，就像他们的计算设备直接连接到私人网络一样。

**Please visit [awesome-sysadmin/VPN](https://github.com/awesome-foss/awesome-sysadmin#vpn)**



### 视频监控

**[`^        back to top        ^`](#Awesome-Selfhosted)**

视频监控，也称为[闭路电视（CCTV）](https://en.wikipedia.org/wiki/Closed-circuit_television)，是在需要额外安全性或持续监视的区域使用视频摄像机进行监控的技术。

_Related: [流媒体 - 视频流媒体](#流媒体---视频流媒体)_

- [Bluecherry](https://www.bluecherrydvr.com/) - 支持IP和模拟摄像机的闭路电视（CCTV）软件应用程序。 ([Source Code](https://github.com/bluecherrydvr/bluecherry-apps)) `GPL-2.0` `PHP`
- [Frigate](https://frigate.video/) - 使用本地处理的人工智能监控您的安全摄像头。 ([Source Code](https://github.com/blakeblackshear/frigate)) `MIT` `Docker/Python/Nodejs`
- [Kerberos.io](https://kerberos.io) - Kerberos.io是一种视频监控解决方案，可与任何摄像头配合在每台基于Linux的机器上运行（包括树莓派、Docker和Kubernetes集群）。 ([Demo](https://demo.kerberos.io/), [Source Code](https://github.com/kerberos-io/agent)) `MIT` `Docker/K8S`
- [SentryShot](https://codeberg.org/SentryShot/sentryshot) - 视频监控管理系统。 `GPL-2.0` `Docker/Rust`
- [Zoneminder](https://www.zoneminder.com/) - 支持IP、USB和模拟摄像头的闭路电视（CCTV）软件应用程序。 ([Source Code](https://github.com/ZoneMinder/ZoneMinder)) `GPL-2.0` `PHP/deb`


### 订阅阅读器

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[新闻聚合器](https://en.wikipedia.org/wiki/News_aggregator)，也称为订阅聚合器、订阅阅读器、新闻阅读器、[RSS](https://en.wikipedia.org/wiki/RSS)阅读器，是一种将网页内容（如报纸/博客/视频博客/播客）集中在一个位置以便轻松查看的应用程序。

- [Bubo Reader](https://github.com/georgemandis/bubo-rss) - 开源的“非理性极简”RSS订阅阅读器。 ([Demo](https://bubo-rss-demo.netlify.app/)) `MIT` `Nodejs`
- [CommaFeed](https://www.commafeed.com/) - 受Google Reader启发的自托管RSS阅读器。 ([Source Code](https://github.com/Athou/commafeed)) `Apache-2.0` `Java/Docker`
- [Feedpushr](https://github.com/ncarlier/feedpushr) - 强大的RSS聚合器，能够转换并将文章发送到多个输出。单个二进制文件，可通过插件进行扩展。 `GPL-3.0` `Go/Docker`
- [FreshRSS](https://freshrss.org/) - 可自主托管的RSS订阅聚合器。 ([Demo](https://demo.freshrss.org/i/), [Source Code](https://github.com/FreshRSS/FreshRSS), [Clients](https://github.com/Alkarex/EasyRSS)) `AGPL-3.0` `PHP/Docker`
- [Goeland](https://github.com/slurdge/goeland) - 读取RSS/Atom源并筛选/摘要它们以创建漂亮的电子邮件。 `MIT` `Go`
- [JARR](https://1pxsolidblack.pl/jarr-en.html) - JARR（Just Another RSS Reader）是一个基于Web的新闻聚合器和阅读器（是Newspipe的分支）。 ([Demo](https://www.jarr.info/), [Source Code](https://github.com/jaesivsm/JARR)) `AGPL-3.0` `Docker/Python`
- [Kriss Feed](https://github.com/tontof/kriss_feed) - 简单而智能（或愚蠢）的Feed阅读器。 `CC0-1.0` `PHP`
- [Leed](https://github.com/LeedRSS/Leed) - Leed（Light Feed的缩写）是一个免费且极简的RSS聚合器。 `AGPL-3.0` `PHP`
- [Miniflux](https://miniflux.app/) - Miniflux 是一款极简主义的开源新闻阅读器，使用 Go 和 PostgreSQL 编写。 ([Source Code](https://github.com/miniflux/v2)) `Apache-2.0` `Go/deb/Docker`
- [NewsBlur](https://www.newsblur.com/) - NewsBlur是一款个人新闻阅读器，让人们聚在一起谈论世界。一种古老乐器的新声音。 ([Source Code](https://github.com/samuelclay/NewsBlur)) `MIT` `Python`
- [Newspipe](https://git.sr.ht/~cedric/newspipe) - Newspipe是一款网络新闻阅读器。 ([Demo](https://www.newspipe.org/signup)) `AGPL-3.0` `Python`
- [reader](https://github.com/lemon24/reader) - 一个基于Python的Feed阅读器Web应用和库（您可以使用它构建自己的阅读器），只依赖标准库和纯Python。 `BSD-3-Clause` `Python`
- [Readflow](https://readflow.app) - 轻量级新闻阅读器，具有现代界面和功能：全文搜索，自动分类，存档，离线支持，通知等... ([Source Code](https://github.com/ncarlier/readflow)) `MIT` `Go/Docker`
- [RSS-Bridge](https://github.com/RSS-Bridge/rss-bridge) - 为没有提供 RSS/ATOM 订阅的网站生成相应的订阅源。 `Unlicense` `PHP/Docker`
- [RSS Monster](https://github.com/pietheinstrengholt/rssmonster) - 一个易于使用的基于 Web 的 RSS 聚合器和阅读器，兼容 Fever API（可替代 Google Reader）。 `MIT` `PHP`
- [RSS2EMail](https://github.com/rss2email/rss2email) - 获取 RSS/Atom 订阅并将新内容推送到任何电子邮件接收器，支持 OPML。 `GPL-2.0` `Python/deb`
- [RSSHub](https://docs.rsshub.app) - 一个易于使用且可扩展的 RSS 订阅聚合器，能够从社交媒体到大学部门等几乎所有内容生成 RSS 订阅源。 ([Demo](https://rsshub.app), [Source Code](https://github.com/DIYgod/RSSHub)) `MIT` `Nodejs/Docker`
- [Selfoss](https://selfoss.aditu.de/) - 新型多用途 RSS 阅读器、实时流、混搭、聚合 Web 应用程序。 ([Source Code](https://github.com/fossar/selfoss)) `GPL-3.0` `PHP`
- [Stringer](https://github.com/stringer-rss/stringer) - 正在进行中的自托管、反社交的 RSS 阅读器。 `MIT` `Ruby`
- [Temboz](https://github.com/fazalmajid/temboz) - 两栏式的 feed 阅读器，强调过滤功能以管理信息过载。 `MIT` `Python`
- [Tiny Tiny RSS](https://tt-rss.org) - 开源的基于 Web 的新闻订阅（RSS/Atom）阅读器和聚合器。 ([Demo](https://srv.tt-rss.org/tt-rss/), [Source Code](https://git.tt-rss.org/fox/tt-rss)) `GPL-3.0` `Docker/PHP`
- [Yarr](https://github.com/nkanaev/yarr) - Yarr（yet another rss reader）是一个基于Web的Feed聚合器，可以用作桌面应用程序和个人自托管服务器。 `MIT` `Go`


### 资源规划

**[`^        back to top        ^`](#Awesome-Selfhosted)**

用于[资源和供应规划](https://en.wikipedia.org/wiki/Resource_planning)的软件和工具，包括[企业资源和供应规划（ERP）](https://en.wikipedia.org/wiki/Enterprise_resource_planning)。

_Related: [资金、预算和管理](#资金、预算和管理), [库存管理](#库存管理)_

- [Dolibarr](https://www.dolibarr.org/) - Dolibarr ERP CRM是一款现代软件包，用于管理公司或基金会的活动（联系人、供应商、发票、订单、库存、日程、会计等）。 ([Demo](https://www.dolibarr.org/onlinedemo.php), [Source Code](https://github.com/Dolibarr/dolibarr)) `GPL-3.0` `PHP/deb`
- [ERPNext](https://erpnext.com) - 自由开源的ERP系统。 ([Source Code](https://github.com/frappe/erpnext)) `GPL-3.0` `Python/Docker`
- [farmOS](https://farmos.org/) - 基于Web的农场记录管理应用程序。 ([Demo](https://farmos-demo.rootedsolutions.io/), [Source Code](https://github.com/farmOS/farmOS)) `GPL-2.0` `PHP/Docker`
- [grocy](https://grocy.info/) - 超越你的冰箱的ERP - grocy是一个面向家庭的基于Web的自托管杂货和家庭管理解决方案。 ([Demo](https://en.demo.grocy.info/), [Source Code](https://github.com/grocy/grocy)) `MIT` `PHP/Docker`
- [LedgerSMB](https://ledgersmb.org/) - 面向小型和中型企业的集成会计和企业资源规划（ERP）系统，具有复式会计、预算、发票、报价、项目、订单和库存管理、运输等功能。 ([Demo](https://demo.cloud.efficito.com/erp/1.5/login.pl), [Source Code](https://github.com/ledgersmb/LedgerSMB)) `GPL-2.0` `Docker/Perl`
- [Odoo](https://www.odoo.com) - 免费开源的ERP系统。 ([Demo](https://demo.odoo.com/), [Source Code](https://github.com/odoo/odoo)) `LGPL-3.0` `Python/deb/Docker`
- [OFBiz](https://ofbiz.apache.org/) - 企业资源规划系统，具有一套灵活到可在任何行业中使用的业务应用程序。 ([Source Code](https://svn.apache.org/viewvc/ofbiz/)) `Apache-2.0` `Java`
- [Tryton](https://www.tryton.org/) - 免费的开源商业解决方案。 ([Demo](https://www.tryton.org/download.html), [Source Code](https://hg.tryton.org/)) `GPL-3.0` `Python`


### 资金、预算和管理

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[资金管理](https://en.wikipedia.org/wiki/Money_management)和预算软件。

_Related: [库存管理](#库存管理), [资源规划](#资源规划)_

- [Actual](https://actualbudget.github.io/docs/) - Actual 是一个基于零和预算的本地优先个人财务工具。它支持设备间同步、自定义规则、手动导入交易（从 QIF、OFX 和 QFX 文件）、以及可选与多家银行进行自动同步。 ([Source Code](https://github.com/actualbudget/actual-server)) `MIT` `Nodejs/Docker`
- [Bigcapital](https://bigcapital.ly) - 适用于中小型企业的自托管财务会计和库存管理软件。 ([Source Code](https://github.com/bigcapitalhq/bigcapital)) `AGPL-3.0` `Docker`
- [Bitcart](https://bitcart.ai) - 一个自托管的加密货币支付处理器和开发平台。 ([Demo](https://admin.bitcart.ai), [Source Code](https://github.com/bitcart)) `MIT` `Docker/Python/Nodejs`
- [BTCPay Server](https://btcpayserver.org/) - 一个自托管的比特币和其他加密货币支付处理器。 ([Demo](https://mainnet.demo.btcpayserver.org/), [Source Code](https://github.com/btcpayserver/)) `MIT` `C#`
- [Budget Zen](https://budgetzen.net) - 全程加密的简易开支管理器。 ([Demo](https://app.budgetzen.net), [Source Code](https://github.com/BrunoBernardino/budgetzen-web)) `AGPL-3.0` `Deno`
- [DePay](https://depay.com) - 直接将 Web3 支付接入您的钱包。点对点、免费、自托管和开源。 ([Demo](https://depay.com/products/payments), [Source Code](https://github.com/depayfi/widgets)) `MIT` `Nodejs`
- [Family Accounting Tool](https://github.com/nymanjens/facto) - 面向部分共享费用的伴侣的基于Web的财务管理工具。 `Apache-2.0` `Scala`
- [Fava](https://beancount.github.io/fava/) - Fava是Beancount的Web前端，是一种基于文本的复式记账系统。 ([Demo](https://fava.pythonanywhere.com/example-with-budgets/income_statement/), [Source Code](https://github.com/beancount/fava)) `MIT` `Python`
- [Firefly III](https://firefly-iii.org/) - Firefly III 是一款现代财务管理软件。它帮助您追踪您的资金并进行预算预测。支持信用卡，具有先进的规则引擎，并可从许多银行导入数据。 ([Demo](https://demo.firefly-iii.org/), [Source Code](https://github.com/firefly-iii/firefly-iii)) `AGPL-3.0` `PHP/Docker`
- [FOSSBilling](https://fossbilling.org/) - 免费且开源的主机和计费自动化工具。与WHM、CWP、cPanel和HestiaCP集成。具备完整的API和易于扩展。 ([Demo](https://fossbilling.org/demo), [Source Code](https://github.com/FOSSBilling/FOSSBilling)) `Apache-2.0` `PHP/Docker`
- [Galette](https://galette.eu/) - Galette是面向非营利组织的会员管理Web应用程序。 ([Source Code](https://git.tuxfamily.org/galette/galette.git/)) `GPL-3.0` `PHP`
- [Ghostfolio](https://ghostfol.io/) - 财富管理软件，用于跟踪股票、ETF和加密货币。 ([Source Code](https://github.com/ghostfolio/ghostfolio)) `AGPL-3.0` `Docker/Nodejs`
- [GRR](https://grr.devome.com/?lang=en) - 面向小型/中型公司的资产管理和预订系统。 ([Source Code](https://github.com/JeromeDevome/GRR)) `GPL-2.0` `PHP`
- [Hub20](https://hub20.io/) - 一个用于以太坊和ERC20代币的自托管支付处理器。 ([Source Code](https://gitlab.com/mushroomlabs/hub20/)) `AGPL-3.0` `Docker/Python`
- [HyperSwitch](https://hyperswitch.io/) `⚠` - HyperSwitch是一个开源的金融交换平台，可以使支付变得快速、可靠和经济实惠。它允许您连接多个支付处理器并轻松路由流量，一切都可以通过单一的API集成完成。 ([Source Code](https://github.com/juspay/hyperswitch)) `Apache-2.0` `Docker/Rust`
- [IHateMoney](https://ihatemoney.org/) - 轻松管理您的共享费用。 ([Demo](https://ihatemoney.org/demo/), [Source Code](https://github.com/spiral-project/ihatemoney)) `BSD-3-Clause` `Docker/Python`
- [Invoice Ninja](https://www.invoiceninja.org/) - 在线向客户开具发票的强大工具。 ([Demo](https://app.invoiceninja.com/invoices/create), [Source Code](https://github.com/invoiceninja/invoiceninja)) `AAL` `PHP/Docker/K8S`
- [InvoicePlane](https://github.com/InvoicePlane/InvoicePlane) - 为您的小型企业管理报价、发票、付款和客户。 `MIT` `PHP`
- [Kill Bill](https://killbill.io/) - 开源的订阅计费和支付平台。具有实时分析和财务报告的访问权限。 ([Source Code](https://github.com/killbill/killbill)) `Apache-2.0` `Java/Docker`
- [Kresus](https://kresus.org/) - 开源个人财务管理软件。 ([Demo](https://kresus.org/en/demo.html), [Source Code](https://github.com/kresusapp/kresus)) `MIT` `Nodejs/Docker`
- [Lago](https://www.getlago.com/) - 开源的计量和基于使用情况的计费系统。 ([Source Code](https://github.com/getlago/lago)) `AGPL-3.0` `Docker`
- [OctoBot](https://www.octobot.cloud/) - 开源加密货币交易机器人。 ([Source Code](https://github.com/Drakkar-Software/OctoBot)) `GPL-3.0` `Python/Docker`
- [OnTrack](https://github.com/inoda/ontrack) - 用于跟踪花费和设定目标的简单应用程序。 `MIT` `Ruby/Nodejs`
- [OpenBudgeteer](https://github.com/TheAxelander/OpenBudgeteer) - 一款基于桶预算原则的预算应用程序。 `MIT` `Docker/C#`
- [REI3](https://rei3.de/home_en/) - 开源、可扩展的业务管理软件。管理任务、时间、资产等等。 ([Demo](https://rei3.de/demo_en/), [Source Code](https://github.com/r3-team/r3)) `MIT` `Go`
- [SolidInvoice](https://solidinvoice.co) - 开源的发票和报价应用程序。 ([Source Code](https://github.com/SolidInvoice/SolidInvoice)) `MIT` `PHP`


### 软件开发

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[软件开发](https://en.wikipedia.org/wiki/Software_development)是涉及构思、规范、设计、编程、文档编制、测试和修复错误的过程，用于创建和维护应用程序、框架或其他软件组件。

**Please visit [软件开发 - API 管理](#软件开发 - API 管理), [软件开发 - 持续集成与部署](#软件开发 - 持续集成与部署), [软件开发 - FaaS 和无服务器](#软件开发 - FaaS 和无服务器), [软件开发 - IDE 和工具](#软件开发 - IDE 和工具), [软件开发 - 本地化](#软件开发 - 本地化), [软件开发 - 低代码](#软件开发 - 低代码), [软件开发 - 项目管理](#软件开发 - 项目管理), [软件开发 - 测试](#软件开发 - 测试)**



### 软件开发 - API 管理

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[API管理](https://en.wikipedia.org/wiki/API_management)是创建和发布[应用程序编程接口（API）](https://en.wikipedia.org/wiki/API)、强制执行其使用政策、控制访问、培养订阅者社区、收集和分析使用统计数据，并报告性能的过程。

- [DreamFactory](https://www.dreamfactory.com/) - 将任何 SQL/NoSQL/结构化数据转换为 Restful API。 ([Source Code](https://github.com/dreamfactorysoftware/dreamfactory)) `Apache-2.0` `PHP/Docker/K8S`
- [form.io](https://form.io) - 一种利用拖放表单构建器的 REST API 构建平台，应用框架无关。包含开源和企业版本。 ([Demo](https://portal.form.io), [Source Code](https://github.com/formio)) `MIT` `Nodejs/Docker`
- [Fusio](https://www.fusio-project.org/) - 开源的API管理平台，帮助构建和管理REST API。 ([Demo](https://fusio-project.org/demo), [Source Code](https://github.com/apioo/fusio)) `AGPL-3.0` `PHP/Docker`
- [Graphweaver](https://graphweaver.com/) - 将多个数据源转换为单一的GraphQL API。 ([Source Code](https://github.com/exogee-technology/graphweaver)) `MIT` `Nodejs`
- [Hasura](https://hasura.io) - 在Postgres上快速、即时的实时GraphQL API，具有细粒度的访问控制，还可在数据库事件上触发Webhooks。 ([Source Code](https://github.com/hasura/graphql-engine)) `Apache-2.0` `Haskell/Docker/K8S`
- [Hoppscotch Community Edition](https://hoppscotch.io) - 一个免费、快速且美观的API请求构建工具。 ([Source Code](https://github.com/hoppscotch/hoppscotch)) `MIT` `Nodejs/Docker`
- [Kong](https://konghq.com/kong/) - 世界上最受欢迎的开源微服务API网关和平台。 ([Source Code](https://github.com/Kong/kong)) `Apache-2.0` `Lua/Docker/K8S/deb`
- [Lura](https://luraproject.org/) - 开源高性能API网关。 ([Source Code](https://github.com/luraproject/lura)) `Apache-2.0` `Go`
- [Para](https://paraio.org) - 灵活且模块化的后端框架/服务器，用于对象持久化、API开发和身份验证。 ([Source Code](https://github.com/erudika/para)) `Apache-2.0` `Java/Docker`
- [Psychic](https://github.com/psychic-api/psychic) - 用于将大型语言模型连接到动态数据源的通用API。 `GPL-3.0` `Python`
- [Svix](https://svix.com) - 作为服务的开源 Webhooks，使 API 提供商轻松发送 Webhooks。 ([Source Code](https://github.com/svix/svix-webhooks)) `MIT` `Docker/Rust`
- [Tyk](https://tyk.io) - 快速而可扩展的开源API网关。Tyk提供了一个API管理平台，其中包括API网关、API分析、开发者门户和API管理仪表板。 ([Source Code](https://github.com/TykTechnologies/tyk)) `MPL-2.0` `Go/Docker/K8S`
- [Yaade](https://docs.yaade.io/) - Yaade是一个开源、自托管的协作式API开发环境。 ([Source Code](https://github.com/EsperoTech/yaade)) `MIT` `Docker`


### 软件开发 - FaaS 和无服务器

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[无服务器计算](https://en.wikipedia.org/wiki/Serverless_computing)，[函数即服务 (FaaS)](https://en.wikipedia.org/wiki/Function_as_a_service) 和 [平台即服务 (PaaS)](https://en.wikipedia.org/wiki/Platform_as_a_service) 管理软件。

- [Appwrite](https://appwrite.io) - 为 Web、本地和移动开发人员提供的端到端后端服务器 🚀。 ([Source Code](https://github.com/appwrite/appwrite)) `BSD-3-Clause` `Docker`
- [Coolify](https://coolify.io/) - 一个开源且可自托管的Heroku / Netlify替代方案（甚至更多）。 ([Source Code](https://github.com/coollabsio/coolify)) `Apache-2.0` `Docker`
- [Dokku](https://dokku.com/) - 一个开源的平台即服务（Heroku 的替代品）。 ([Source Code](https://github.com/dokku/dokku)) `MIT` `Docker/Shell/Go/deb`
- [fx](https://github.com/metrue/fx) - 一款帮助您在自己的服务器上轻松实现函数即服务（FaaS）的工具。 `MIT` `Go`
- [Kubero](https://www.kubero.dev/) - 一个在Kubernetes上实现GitOps的自托管Heroku PaaS替代方案。 ([Demo](https://demo.kubero.dev/), [Source Code](https://github.com/kubero-dev/kubero)) `GPL-3.0` `K8S/Nodejs/Go`
- [LocalStack](https://localstack.cloud/) - LocalStack是一个完全功能的本地AWS云堆栈。包括用于无服务器计算的Lambda。 ([Source Code](https://github.com/localstack/localstack)) `Apache-2.0` `Python/Docker/K8S`
- [Nhost](https://nhost.io/) - 基于GraphQL的Firebase替代方案。在几分钟内获取配置好的数据库和后端。 ([Source Code](https://github.com/nhost/nhost)) `MIT` `Docker/Nodejs/Go`
- [OpenFaaS](https://www.openfaas.com/) - 面向Docker和Kubernetes的简化无服务器函数。 ([Source Code](https://github.com/openfaas/faas)) `MIT` `Go`
- [Trusted-CGI](https://github.com/reddec/trusted-cgi) - 轻量级的自托管 Lambda/应用程序/CGI/无服务器函数平台。 `MIT` `Go/deb/Docker`


### 软件开发 - IDE 和工具

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[集成开发环境 (IDE)](https://en.wikipedia.org/wiki/Integrated_development_environment) 是一种为计算机程序员提供全面开发工具的软件应用程序。

_Related: [软件开发 - 低代码](#软件开发---低代码)_

- [Atheos](https://www.atheos.io) - 一个基于Web的 IDE 框架，占用空间小、要求最低，是 Codiad 的延续。 ([Source Code](https://github.com/Atheos/Atheos)) `MIT` `PHP/Docker`
- [code-server](https://github.com/coder/code-server) - 在浏览器中运行的VS Code，托管在远程服务器上。 `MIT` `Nodejs/Docker`
- [Coder](https://coder.com/) - 在您自己的基础设施上进行远程开发机器。 ([Source Code](https://github.com/coder/coder)) `AGPL-3.0` `Go/Docker/K8S/deb`
- [Eclipse Che](https://www.eclipse.org/che/) - 开源工作空间服务器和云IDE。 ([Source Code](https://github.com/eclipse/che)) `EPL-1.0` `Docker/Java`
- [Hakatime](https://github.com/mujx/hakatime) - 具有分析仪表板的WakaTime服务器实现。 `Unlicense` `Haskell`
- [HttPlaceholder](https://github.com/dukeofharen/httplaceholder) - 使用 HttPlaceholder 快速模拟任何Web服务。HttPlaceholder 允许您指定请求的样式以及需要返回的响应。 `MIT` `C#`
- [Judge0 CE](https://judge0.com) - 用于编译和运行源代码的开源API。 ([Source Code](https://github.com/judge0/judge0)) `GPL-3.0` `Docker`
- [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) - 基于Web的交互式和可重现计算环境。 ([Demo](https://mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/try.jupyter.org?urlpath=lab), [Source Code](https://github.com/jupyterlab/jupyterlab/)) `BSD-3-Clause` `Python/Docker`
- [Lowdefy](https://www.lowdefy.com/) - 使用YAML / JSON在自托管的开源平台上，在几分钟内构建内部工具、BI仪表板、管理面板、CRUD应用程序和工作流。连接到您的数据源，通过Serverless、Netlify或Docker进行托管。 ([Source Code](https://github.com/lowdefy/lowdefy)) `Apache-2.0` `Nodejs/Docker`
- [RStudio Server](https://www.rstudio.com/products/rstudio/#Server) - 基于 Web 浏览器的 R 语言集成开发环境（IDE）。 ([Source Code](https://github.com/rstudio/rstudio)) `AGPL-3.0` `Java/C++`
- [sourcegraph](https://sourcegraph.com) - Sourcegraph是一个用Go编写的快速、开源、功能齐全的代码搜索和导航引擎。 ([Source Code](https://github.com/sourcegraph/sourcegraph)) `Apache-2.0` `Go`
- [Wakapi](https://wakapi.dev/) - 用于跟踪编码统计的工具，与WakaTime兼容。 ([Source Code](https://github.com/muety/wakapi)) `GPL-3.0` `Go/Docker`


### 软件开发 - 低代码

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[低代码](https://en.wikipedia.org/wiki/Low-code_development_platform) 开发平台 (LCDP) 提供一个通过图形用户界面创建应用软件的开发环境。

_Related: [软件开发 - IDE 和工具](#软件开发---ide-和工具)_

- [Appsmith](https://www.appsmith.com/) - 云端或自托管的开源平台，用于构建管理面板、CRUD 应用程序和工作流。快速构建所需的一切，提高效率 10 倍。 ([Source Code](https://github.com/appsmithorg/appsmith)) `Apache-2.0` `Java/Docker/K8S`
- [Dashpress](https://github.com/dashpresshq/dashpress) - 通过单个命令从数据库信息中在几秒钟内生成功能齐全的管理应用。 ([Demo](https://demo.dashpress.io/auth)) `AGPL-3.0` `Nodejs/Docker`
- [Motor Admin](https://www.getmotoradmin.com/) - 无代码管理面板和商业智能软件 - 搜索、创建、更新和删除数据条目，创建自定义操作并生成报告。 ([Source Code](https://github.com/motor-admin/motor-admin)) `AGPL-3.0` `Ruby/Docker`
- [PocketBase](https://pocketbase.io/) - 用于您的下一个SaaS和移动应用的开源后端，仅需一个文件。 ([Source Code](https://github.com/pocketbase/pocketbase)) `MIT` `Go/Docker`
- [SQLPage](https://sql.ophir.dev) - 仅支持SQL的动态网站构建工具。 ([Source Code](https://github.com/lovasoa/SQLPage)) `MIT` `Rust/Docker`
- [ToolJet](https://tooljet.io/) - 低代码框架，通过最小的工程投入构建和部署内部工具（Retool和Mendix的替代品）。 ([Source Code](https://github.com/ToolJet/ToolJet)) `GPL-3.0` `Nodejs/Docker/K8S`


### 软件开发 - 持续集成和部署

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[持续集成](https://en.wikipedia.org/wiki/Continuous_integration)和[持续部署](https://en.wikipedia.org/wiki/Continuous_deployment)的软件和工具。

**Please visit [awesome-sysadmin/持续集成和部署](https://github.com/awesome-foss/awesome-sysadmin#continuous-integration--continuous-deployment)**

_Related: [自动化](#自动化)_



### 软件开发 - 本地化

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[本地化](https://en.wikipedia.org/wiki/Internationalization_and_localization) 是将代码和软件适应其他语言的过程。

- [Accent](https://www.accent.reviews/) - 开源、自托管的、面向开发者的翻译工具。 ([Source Code](https://github.com/mirego/accent)) `BSD-3-Clause` `Elixir/Docker`
- [Tolgee](https://tolgee.io) - 面向开发者和翻译人员的友好的基于Web的本地化平台，使用户能够直接在其开发的应用程序中进行翻译。 ([Source Code](https://github.com/tolgee/tolgee-platform)) `Apache-2.0` `Docker/Java`
- [Traduora](https://traduora.co) - 面向团队的翻译管理平台。 ([Source Code](https://github.com/ever-co/ever-traduora)) `AGPL-3.0` `Docker/K8S/Nodejs`
- [Weblate](https://weblate.org) - 基于Web的翻译工具，与版本控制紧密集成。 ([Demo](https://demo.weblate.org), [Source Code](https://github.com/WeblateOrg/weblate)) `GPL-3.0` `Python/Docker/K8S`


### 软件开发 - 测试

**[`^        back to top        ^`](#Awesome-Selfhosted)**

用于[软件测试](https://en.wikipedia.org/wiki/Software_testing)的工具和软件。

- [Bencher](https://bencher.dev/) - Bencher是一套持续基准测试工具，旨在在CI中捕获性能回归。 ([Source Code](https://github.com/bencherdev/bencher)) `MIT/Apache-2.0` `Rust`
- [Selenoid](https://aerokube.com/selenoid/latest/) - 轻量级的 Selenium Hub 实现，通过 Docker 容器启动浏览器。 ([Source Code](https://github.com/aerokube/selenoid)) `Apache-2.0` `Go`
- [Sorry Cypress](https://sorry-cypress.dev) - Cypress浏览器自动化框架的替代开源仪表板，支持无限并行化、测试录制和调试。 ([Source Code](https://github.com/sorry-cypress/sorry-cypress)) `MIT` `Docker/K8S`
- [Touca](https://touca.io) - 面向工程团队的持续回归测试。在编写可能破坏软件的代码时获得反馈。 ([Source Code](https://github.com/trytouca/trytouca)) `Apache-2.0` `Docker/Nodejs`


### 软件开发 - 项目管理

**[`^        back to top        ^`](#Awesome-Selfhosted)**

用于[软件项目管理](https://en.wikipedia.org/wiki/Software_project_management)的工具和软件。

_Related: [工单](#工单), [任务管理和待办清单](#任务管理和待办清单)_

- [Cgit](https://git.zx2c4.com/cgit/about/) - 用于 Git 仓库的快速轻量级 Web 界面。 ([Source Code](https://git.zx2c4.com/cgit/tree/)) `GPL-2.0` `C`
- [Forgejo](https://forgejo.org) - 一款专注于扩展、联邦和隐私的轻量级软件锻造工具（基于 Gitea 的分支）。 ([Demo](https://next.forgejo.org), [Source Code](https://codeberg.org/forgejo/forgejo/), [Clients](https://codeberg.org/forgejo-contrib/delightful-forgejo)) `MIT` `Docker/Go`
- [Fossil](https://www.fossil-scm.org/index.html/doc/trunk/www/index.wiki) - 分布式版本控制系统，具有维基和缺陷跟踪器功能。 `BSD-2-Clause-FreeBSD` `C`
- [Gerrit](https://www.gerritcodereview.com/) - 一个用于Git项目的代码审查和项目管理工具。 ([Source Code](https://github.com/GerritCodeReview/gerrit)) `Apache-2.0` `Java/Docker`
- [Gitblit](https://www.gitblit.com/) - 用于管理、查看和提供Git存储库的纯Java堆栈。 ([Source Code](https://github.com/gitblit-org/gitblit)) `Apache-2.0` `Java`
- [gitbucket](https://gitbucket.github.io/gitbucket-news/) - 由Scala支持的可轻松安装的GitHub克隆。 ([Source Code](https://github.com/gitbucket/gitbucket)) `Apache-2.0` `Scala/Java`
- [Gitea](https://gitea.io) - 由社区管理的轻量级代码托管解决方案（Gogs的分支）。 ([Demo](https://try.gitea.io), [Source Code](https://github.com/go-gitea/gitea)) `MIT` `Go/Docker/K8S`
- [GitLab](https://about.gitlab.com) - 自托管的Git仓库管理、代码审查、问题追踪、活动订阅和维基工具。 ([Demo](https://gitlab.com/), [Source Code](https://gitlab.com/gitlab-org/gitlab-foss)) `MIT` `Ruby/deb/Docker/K8S`
- [Gitolite](https://gitolite.com/gitolite/index.html) - Gitolite允许您在中央服务器上设置git托管，具有细粒度的访问控制和许多其他强大的功能。 ([Source Code](https://github.com/sitaramc/gitolite)) `GPL-2.0` `Perl`
- [Gogs](https://gogs.io/) - 用Go编写的轻松自托管的Git服务。 ([Demo](https://try.gogs.io/), [Source Code](https://github.com/gogs/gogs)) `MIT` `Go`
- [Kallithea](https://kallithea-scm.org/) - 支持两个主流版本控制系统Mercurial和Git的源代码管理系统，带有Web界面。 ([Source Code](https://kallithea-scm.org/repos/kallithea)) `GPL-3.0` `Python`
- [Klaus](https://github.com/jonashaag/klaus) - 简单、易于设置的 Git Web 查看器，一切都能正常运作。 `ISC` `Python/Docker`
- [Lazylead](https://lazylead.org) `⚠` - 简化工单系统（Jira、GitHub、Trello）中的烦人工作。允许自动化日常操作，如工单字段验证、JQL/GQL邮件通知、向您（或团队成员）的日历发送会议请求。 ([Source Code](https://github.com/dgroup/lazylead)) `MIT` `Ruby/Docker`
- [Leantime](https://leantime.io) - Leantime是一个专为小团队和初创公司设计的精益项目管理系统，帮助从构思到交付的整个项目管理过程。 ([Source Code](https://github.com/leantime/leantime)) `GPL-2.0` `PHP/Docker`
- [Mindwendel](https://www.mindwendel.com/) - 在团队内部进行头脑风暴，并投票支持想法和思考。 ([Demo](https://www.mindwendel.com), [Source Code](https://github.com/b310-digital/mindwendel)) `AGPL-3.0` `Docker/Elixir`
- [Octobox](https://octobox.io/) `⚠` - 重新掌控您的GitHub通知。 ([Source Code](https://github.com/octobox/octobox)) `AGPL-3.0` `Ruby/Docker`
- [OneDev](https://onedev.io/) - 一体化的DevOps平台，包括Git管理、问题追踪和CI/CD。简单而强大。 ([Source Code](https://code.onedev.io/projects/160)) `MIT` `Java/Docker/K8S`
- [OpenProject](https://www.openproject.org) - OpenProject是一个基于Web的项目管理系统。 ([Source Code](https://github.com/opf/openproject)) `GPL-3.0` `Ruby/deb/Docker`
- [Pagure](https://pagure.io/pagure) - 一个轻量级、强大而灵活的以Git为中心的锻造平台，具有为联合和去中心化开发奠定基础的功能。 ([Demo](https://pagure.io/)) `GPL-2.0` `Docker/Python/deb`
- [Phorge](https://we.phorge.it/) - Phorge是一个开源的、社区驱动的平台，用于协作、管理、组织和审查软件开发项目。 ([Source Code](https://we.phorge.it/source/phorge/)) `Apache-2.0` `PHP`
- [Phproject](https://www.phproject.org/) - 高性能、功能齐全的项目管理系统。 ([Source Code](https://github.com/Alanaktion/phproject)) `GPL-3.0` `PHP`
- [Plane](https://plane.so) - Plane 帮助您以最简单的方式跟踪问题、史诗和产品路线图（可替代 JIRA、Linear 和 Height）。 ([Demo](https://app.plane.so), [Source Code](https://github.com/makeplane/plane)) `Apache-2.0` `Docker`
- [ProjeQtOr](https://www.projeqtor.org/) - 一套完整、成熟的、多用户项目管理系统，具有广泛的功能，适用于项目的所有阶段。 ([Demo](https://demo.projeqtor.org/), [Source Code](https://sourceforge.net/p/projectorria/code/HEAD/tree/branches/)) `AGPL-3.0` `PHP`
- [Redmine](https://www.redmine.org/) - Redmine是一款灵活的项目管理Web应用。 ([Source Code](https://svn.redmine.org/redmine/)) `GPL-2.0` `Ruby`
- [Review Board](https://www.reviewboard.org/) - 适用于各种规模的项目和公司的可扩展且用户友好的代码审查工具。 ([Demo](https://demo.reviewboard.org/), [Source Code](https://github.com/reviewboard/reviewboard)) `MIT` `Python/Docker`
- [rgit](https://github.com/w4/rgit) - 一个超快且轻量的 cgit 克隆。 ([Demo](https://git.inept.dev/)) `WTFPL` `Rust/Docker`
- [RhodeCode](https://rhodecode.com/) - RhodeCode是一个面向软件开发团队的开源平台。它统一并简化了对Git、Subversion和Mercurial的仓库管理。 ([Source Code](https://code.rhodecode.com/)) `AGPL-3.0` `Python`
- [Rukovoditel](https://www.rukovoditel.net/) - 可配置的开源项目管理，基于 Web 的应用程序。 ([Source Code](https://www.rukovoditel.net/download.php)) `GPL-2.0` `PHP`
- [SCM Manager](https://www.scm-manager.org/) - 通过 http 最简单的方式共享和管理 Git、Mercurial 和 Subversion 仓库。 ([Source Code](https://github.com/scm-manager/scm-manager)) `BSD-3-Clause` `Java/deb/Docker/K8S`
- [Smederee](https://smeder.ee) - 一个节俭的平台，致力于帮助人们一起构建出色的软件，充分发挥Darcs版本控制系统的力量。 ([Source Code](https://smeder.ee/~jan0sch/smederee)) `AGPL-3.0` `Scala`
- [Sourcehut](https://sourcehut.org/) - 一个完整的无JavaScript Web Git界面。 ([Demo](https://sr.ht/), [Source Code](https://git.sr.ht/~sircmpwn/git.sr.ht/tree)) `GPL-2.0` `Go`
- [Taiga](https://www.taiga.io/) - 基于看板和 Scrum 方法的敏捷项目管理工具。 ([Source Code](https://github.com/kaleidos-ventures)) `MPL-2.0` `Docker/Python/Nodejs`
- [Titra](https://titra.io/) - 为自由职业者和小团队提供的时间跟踪解决方案。 ([Source Code](https://github.com/kromitgmbh/titra)) `GPL-3.0` `Javascript/Docker`
- [Trac](https://trac.edgewall.org/) - Trac是一个增强的维基和问题跟踪系统，用于软件开发项目。 `BSD-3-Clause` `Python/deb`
- [Traq](https://traq.io/) - 使用PHP编写的项目管理和问题跟踪系统。 ([Source Code](https://github.com/nirix/traq)) `GPL-3.0` `PHP/Nodejs`
- [Tuleap](https://www.tuleap.org/) - Tuleap是一个自由套件，用于计划、跟踪、编码和在软件项目上进行协作。 ([Source Code](https://tuleap.net/plugins/git/tuleap/tuleap/stable?p=tuleap%2Fstable.git&a=tree)) `GPL-2.0` `PHP`
- [UVDesk](https://www.uvdesk.com/) - UVDesk社区是一个面向服务、事件驱动的可扩展的开源帮助台系统，可由您的组织轻松提供高效的客户支持，以您所想象的方式。 ([Demo](https://demo.uvdesk.com/), [Source Code](https://github.com/uvdesk/community-skeleton)) `MIT` `PHP`
- [ZenTao](https://www.zentao.pm/) - 敏捷（Scrum）项目管理系统/工具。 ([Demo](https://demo15.zentao.pm/), [Source Code](https://github.com/easysoft/zentaopms)) `AGPL-3.0` `PHP`


### 远程访问

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[远程桌面](https://en.wikipedia.org/wiki/Remote_desktop_software)和[SSH](https://en.wikipedia.org/wiki/Secure_Shell)服务器以及用于远程管理计算机系统的Web界面。

- [Firezone](https://www.firezone.dev/) - 自托管的安全远程访问网关，支持 WireGuard 协议。提供 Web GUI、一行安装脚本、多因素认证（MFA）和单一登录（SSO）。 ([Source Code](https://github.com/firezone/firezone)) `Apache-2.0` `Elixir/Docker`
- [Guacamole](https://guacamole.apache.org) - Guacamole是一个无客户端的远程桌面网关。支持标准协议，如VNC和RDP。 ([Source Code](https://github.com/apache/guacamole-server)) `Apache-2.0` `Java/C`
- [httprd](https://github.com/bitrate16/httprd) - 通过Web浏览器的单脚本远程桌面。 `GPL-3.0` `Python`
- [MeshCentral](https://meshcentral.com/) - 一款完整的计算机管理网站。通过 MeshCentral，您可以运行自己的 Web 服务器，远程管理和控制位于本地网络或互联网任何地方的计算机。 ([Source Code](https://github.com/Ylianst/MeshCentral)) `Apache-2.0` `Nodejs`
- [Remotely](https://github.com/immense/Remotely) - 一种远程桌面控制和远程脚本解决方案，具有管理员Web界面和通过浏览器进行远程控制的企业级远程支持解决方案。 `GPL-3.0` `C#/Docker`
- [RustDesk](https://rustdesk.com/) - 远程桌面访问软件，可即插即用（TeamViewer 的替代品）。 ([Source Code](https://github.com/rustdesk/rustdesk-server)) `AGPL-3.0` `Rust/Docker/deb`
- [ShellHub](https://www.shellhub.io) - ShellHub 是一个现代的 SSH 服务器，通过命令行（使用任何 SSH 客户端）或基于 Web 的用户界面远程访问 Linux 设备，设计为 sshd 的替代品。 ([Source Code](https://github.com/shellhub-io/shellhub)) `Apache-2.0` `Docker`
- [Sshwifty](https://github.com/nirui/sshwifty) - Sshwifty是为Web而制作的SSH和Telnet连接器。 `AGPL-3.0` `Go/Docker`
- [Warpgate](https://github.com/warp-tech/warpgate) - 智能的SSH和HTTPS堡垒，可与任何SSH客户端一起使用。 `Apache-2.0` `Rust/Docker`


### 通信 - IRC

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat)通信软件。

- [Convos](https://convos.chat/) - 始终在线的Web IRC客户端。 ([Demo](https://convos.chat/#instant-demo), [Source Code](https://github.com/convos-chat/convos)) `Artistic-2.0` `Perl/Docker`
- [Ergo](https://ergo.chat/) - 用Go编写的现代IRCv3服务器，结合了ircd、服务框架和弹幕的功能。 ([Source Code](https://github.com/ergochat/ergo)) `MIT` `Go/Docker`
- [Glowing Bear](https://github.com/glowing-bear/glowing-bear) - WeeChat的Web前端。 ([Demo](https://www.glowing-bear.org)) `GPL-3.0` `Nodejs`
- [InspIRCd](https://www.inspircd.org/) - 用于Linux、BSD、Windows和macOS的用C++编写的模块化IRC服务器。 ([Source Code](https://github.com/inspircd/inspircd)) `GPL-2.0` `C++/Docker`
- [Kiwi IRC](https://kiwiirc.com/) - 支持主题的响应式 Web IRC 客户端。 ([Demo](https://kiwiirc.com/nextclient/), [Source Code](https://github.com/kiwiirc/kiwiirc)) `Apache-2.0` `Nodejs`
- [ngircd](https://ngircd.barton.de/) - 用于小型或私有网络的免费、便携和轻量级Internet Relay Chat（IRC）服务器。 ([Source Code](https://github.com/ngircd/ngircd)) `GPL-2.0` `C/deb`
- [Quassel IRC](https://quassel-irc.org/) - 分布式IRC客户端，意味着一个（或多个）客户端可以连接到和从一个中央核心分离。 ([Source Code](https://github.com/quassel/quassel)) `GPL-2.0` `C++`
- [Robust IRC](https://robustirc.net/) - RobustIRC 是没有网络分裂的 IRC。基于 RobustSession 协议的分布式 IRC 服务器。 ([Source Code](https://github.com/robustirc/robustirc)) `BSD-3-Clause` `Go`
- [The Lounge](https://thelounge.chat/) - 自托管的 Web IRC 客户端。 ([Demo](https://demo.thelounge.chat/), [Source Code](https://github.com/thelounge/thelounge)) `MIT` `Nodejs/Docker`
- [UnrealIRCd](https://www.unrealircd.org/) - 一款模块化、先进且高度可配置的用C语言编写的IRC服务器，适用于Linux、BSD、Windows和macOS。 ([Source Code](https://github.com/unrealircd/unrealircd)) `GPL-2.0` `C`
- [WeeChat](https://weechat.org/) - 快速、轻量且可扩展的聊天客户端。 ([Source Code](https://github.com/weechat/weechat)) `GPL-3.0` `C/Docker/deb`
- [ZNC](https://wiki.znc.in/ZNC) - 先进的IRC代理服务器。 ([Source Code](https://github.com/znc/znc)) `Apache-2.0` `C++/deb`


### 通信 - SIP

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[SIP](https://en.wikipedia.org/wiki/Session_Initiation_Protocol)/[IPBX](https://en.wikipedia.org/wiki/IP_PBX)电话软件。

- [Asterisk](https://www.asterisk.org/) - 易于使用但先进的 IP PBX 系统、VoIP 网关和会议服务器。 ([Source Code](https://github.com/asterisk/asterisk)) `GPL-2.0` `C/deb`
- [ASTPP](https://www.astppbilling.org/) - Freeswitch 的 VoIP 计费解决方案。它支持预付费和后付费计费，具有通话评级和信用控制。还提供许多其他功能。 ([Source Code](https://github.com/iNextrix/ASTPP)) `AGPL-3.0` `PHP`
- [Eqivo](https://eqivo.org/) - Eqivo在FreeSWITCH之上实现了一个API层，促进了Web应用程序与语音/视频启用的端点（如传统电话线（PSTN）、VoIP电话、WebRTC客户端等）之间的集成。 ([Source Code](https://github.com/rtckit/eqivo)) `MIT` `Docker/PHP`
- [Flexisip](https://www.linphone.org/technical-corner/flexisip/) - 一款完整、模块化和可扩展的 SIP 服务器，包括一个推送网关，用于在移动设备平台上传递 SIP 来电或文本消息，在这些平台上，需要推送通知以在应用程序不活动在前台时接收信息。 ([Source Code](https://github.com/BelledonneCommunications/flexisip)) `AGPL-3.0` `C/Docker`
- [FreePBX](https://www.freepbx.org) - 基于Web的开源图形用户界面，用于控制和管理Asterisk。 ([Source Code](https://git.freepbx.org/projects/FREEPBX)) `GPL-2.0` `PHP`
- [FreeSWITCH](https://freeswitch.org/) - 可扩展的开源跨平台电话平台。 ([Source Code](https://github.com/signalwire/freeswitch)) `MPL-2.0` `C`
- [FusionPBX](https://www.fusionpbx.com/) - 提供可定制且灵活的Web界面，用于与名为FreeSWITCH的强大且高度可伸缩的多平台语音交换进行交互的开源项目。 ([Source Code](https://github.com/fusionpbx/fusionpbx)) `MPL-1.1` `PHP`
- [Kamailio](https://www.kamailio.org/w/) - 模块化的SIP服务器（注册/代理/路由器等）。 ([Source Code](https://github.com/kamailio/kamailio)) `GPL-2.0` `C/deb`
- [openSIPS](https://opensips.org/) - OpenSIPS是一个用于语音、视频、即时消息、存在及其他SIP扩展的开源SIP代理/服务器。 ([Source Code](https://github.com/OpenSIPS/opensips)) `GPL-2.0` `C`
- [Routr](https://routr.io) - 一个轻量级的 SIP 代理、位置服务器和注册服务器，用于可靠且可扩展的 SIP 基础设施。 ([Source Code](https://github.com/fonoster/routr)) `MIT` `Docker/K8S`
- [SIP3](https://sip3.io/) - VoIP故障排除和监控平台。 ([Demo](https://demo.sip3.io), [Source Code](https://github.com/sip3io/)) `Apache-2.0` `Java`
- [SIPCAPTURE Homer](https://www.sipcapture.org/) - 用于故障排除和监控VoIP通话的工具。 ([Source Code](https://github.com/sipcapture/homer)) `AGPL-3.0` `Nodejs/Go/Docker`
- [Wazo](https://wazo-platform.org/) - 在Asterisk之上构建的功能齐全的IPBX解决方案，具有集成的Web管理界面和RESTful API。 ([Source Code](https://github.com/wazo-platform)) `GPL-3.0` `Python`
- [Yeti-Switch](https://yeti-switch.org/) - 集成计费和路由引擎以及REST API的中继类4软交换（SBC）。 ([Demo](https://yeti-switch.org/demo.html), [Source Code](https://github.com/yeti-switch)) `GPL-2.0` `C++/Ruby`


### 通信 - XMPP - Web 客户端

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[可扩展消息和出席协议](https://en.wikipedia.org/wiki/XMPP) Web客户端/界面。

- [Converse.js](https://conversejs.org/) - 在浏览器中使用的免费开源XMPP聊天客户端。 ([Source Code](https://github.com/conversejs/converse.js)) `MPL-2.0` `Javascript`
- [JSXC](https://jsxc.org) - 实时XMPP网络聊天应用，支持视频通话、文件传输和加密通信。还有适用于Nextcloud/Owncloud和SOGo的版本。 ([Source Code](https://github.com/jsxc/jsxc)) `MIT` `Javascript`
- [Libervia](https://repos.goffi.org/libervia-web) - Salut à Toi的Web前端。 `AGPL-3.0` `Python`
- [Salut à Toi](https://www.salut-a-toi.org/) - 多用途、多前端、自由且分散的通讯工具。 ([Source Code](https://repos.goffi.org/libervia-backend)) `AGPL-3.0` `Python`


### 通信 - XMPP - 服务器

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[可扩展消息和出席协议](https://en.wikipedia.org/wiki/XMPP)服务器。

- [ejabberd](https://www.ejabberd.im/) - XMPP即时消息服务器。 ([Source Code](https://github.com/processone/ejabberd)) `GPL-2.0` `Erlang/Docker`
- [Metronome IM](https://metronome.im/) - 一款轻量级的 XMPP 服务器，具有先进的微博功能（Prosody 的分支）。 ([Source Code](https://github.com/maranda/metronome)) `MIT` `Lua`
- [MongooseIM](https://www.erlang-solutions.com/products/mongooseim.html) - 移动消息平台，注重性能和可扩展性。 ([Source Code](https://github.com/esl/MongooseIM)) `GPL-2.0` `Erlang/Docker/K8S`
- [Openfire](https://www.igniterealtime.org/projects/openfire/) - 实时协作（RTC）服务器。 ([Source Code](https://github.com/igniterealtime/Openfire)) `Apache-2.0` `Java`
- [Prosody IM](https://prosody.im/) - 功能丰富且易于配置的XMPP服务器。 ([Source Code](https://hg.prosody.im/)) `MIT` `Lua`
- [Snikket](https://snikket.org/) - 一体化的Docker化简易XMPP解决方案，包括Web管理和客户端。 ([Source Code](https://github.com/snikket-im/snikket-server), [Clients](https://snikket.org/app/)) `Apache-2.0` `Docker`
- [Tigase](https://tigase.net/xmpp-server) - Java 中的 XMPP 服务器实现。 ([Source Code](https://github.com/tigase/tigase-server)) `GPL-3.0` `Java`


### 通信 - 定制通信系统

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[通信软件](https://en.wikipedia.org/wiki/Communication_software) 用于提供对系统的远程访问，以及在不同计算机或用户之间以文本、音频和/或视频格式交换文件和消息，使用其自定义协议。

- [Apprise](https://github.com/caronc/apprise) - Apprise 允许您向几乎所有我们今天可以使用的最流行的通知服务发送通知，如：Telegram、Discord、Slack、Amazon SNS、Gotify 等。 `MIT` `Python/Docker/deb`
- [Centrifugo](https://centrifugal.dev/) - 语言无关的实时消息（Websocket或SockJS）服务器。 ([Demo](https://github.com/centrifugal/centrifugo#demo), [Source Code](https://github.com/centrifugal/centrifugo)) `MIT` `Go/Docker/K8S`
- [Chatwoot](https://www.chatwoot.com) - 自托管的客户沟通平台（替代Intercom和Zendesk）。 ([Source Code](https://github.com/chatwoot/chatwoot)) `MIT` `Ruby/Docker/K8S`
- [Chitchatter](https://chitchatter.im/) - 一款无服务器、去中心化且短暂的点对点聊天应用。 ([Source Code](https://github.com/jeremyckahn/chitchatter)) `GPL-2.0` `Nodejs`
- [Conduit](https://conduit.rs/) - 由Matrix支持的简单、快速且可靠的聊天服务器。 ([Source Code](https://gitlab.com/famedly/conduit)) `Apache-2.0` `Rust`
- [Darkwire.io](https://github.com/darkwire/darkwire.io) - 端到端加密的即时网络聊天。 `MIT` `Nodejs`
- [Databag](https://github.com/balzack/databag) - 面向 Web、iOS 和 Android 的联合、端到端加密的消息服务，支持文本、照片、视频以及 WebRTC 视频和音频通话。 ([Demo](https://databag.coredb.org/#/create)) `Apache-2.0` `Docker`
- [Dendrite](https://matrix-org.github.io/dendrite/) - 使用 Go 编写的第二代 Matrix 家务服务器。它旨在为 Synapse 提供一种高效、可靠和可扩展的替代方案。 ([Source Code](https://github.com/matrix-org/dendrite)) `Apache-2.0` `Go`
- [Element](https://element.io) - 用于Web、iOS和Android的功能齐全的Matrix客户端。 ([Source Code](https://github.com/vector-im/element-web)) `Apache-2.0` `Nodejs`
- [GNUnet](https://gnunet.org/) - 用于去中心化的对等网络的自由软件框架。 ([Source Code](https://gnunet.org/git/)) `GPL-3.0` `C`
- [Gotify](https://gotify.net/) - 自托管的通知服务器，具有Android和CLI客户端，类似于PushBullet。 ([Source Code](https://github.com/gotify/server), [Clients](https://github.com/gotify/android)) `MIT` `Go/Docker`
- [HawkPost](https://hawkpost.co) - HawkPost是一个Web应用程序，允许您创建独特的链接，您可以与希望向您发送重要信息但不知道如何加密的人共享。消息在其浏览器中加密，然后发送到您的电子邮件地址。 ([Source Code](https://github.com/whitesmith/hawkpost)) `MIT` `Python/Docker`
- [Hyphanet](https://hyphanet.org/) - 匿名分享文件，浏览和发布_freesites_（仅通过Hyphanet访问的网站）并在论坛上聊天。 ([Source Code](https://github.com/hyphanet/fred)) `GPL-2.0` `Java`
- [Jami](https://jami.net/) - 自由且通用的通信平台，保护用户的隐私和自由（前身为GNU Ring）。 ([Source Code](https://git.jami.net/savoirfairelinux?sort=latest_activity_desc&filter=jami)) `GPL-3.0` `C++`
- [KChat](https://github.com/php-kchat/kchat) - 基于PHP的实时聊天应用。 `Apache-2.0` `PHP`
- [LeapChat](https://www.leapchat.org/) - 一次性、加密的、基于浏览器的聊天室。 ([Source Code](https://github.com/cryptag/leapchat)) `AGPL-3.0` `Docker/Nodejs/Shell`
- [Live Helper Chat](https://livehelperchat.com/) - 用于网站的实时支持聊天。 ([Source Code](https://github.com/LiveHelperChat/livehelperchat)) `Apache-2.0` `PHP`
- [Mattermost](https://mattermost.org/) - 用于安全协作的平台，覆盖整个软件开发生命周期，可与Gitlab集成（替代Slack）。 ([Source Code](https://github.com/mattermost/mattermost)) `AGPL-3.0/Apache-2.0` `Go/Docker/K8S`
- [MiAOU](https://miaou.dystroy.org/login) - 多房间持久聊天服务器。 ([Source Code](https://github.com/Canop/miaou)) `MIT` `Nodejs`
- [Mibew](https://mibew.org) - Mibew Messenger 是一个用 PHP 和 MySQL 编写的开源实时支持应用程序。它使您能够直接从您的网站实时进行一对一聊天支持。 ([Demo](https://mibew.org/demo2), [Source Code](https://github.com/Mibew/mibew)) `Apache-2.0` `PHP`
- [Mumble](https://wiki.mumble.info/wiki/Main_Page) - 低延迟、高质量的语音/文本聊天软件。 ([Source Code](https://github.com/mumble-voip/mumble), [Clients](https://wiki.mumble.info/wiki/3rd_Party_Applications)) `BSD-3-Clause` `C++/deb`
- [Notifo](https://github.com/notifo-io/notifo) - 多通道通知服务器，支持电子邮件、移动推送、Web推送、短信、消息和JavaScript插件。 `MIT` `C#`
- [Novu](https://novu.co/) - 面向开发人员的自托管/云通知基础设施。 ([Source Code](https://github.com/novuhq/novu/)) `MIT` `Docker/Nodejs`
- [ntfy](https://ntfy.sh/) - 使用HTTP PUT/POST向手机或桌面推送通知，具有Android应用程序、命令行界面和Web应用程序，类似于Pushover和Gotify。 ([Demo](https://ntfy.sh/app), [Source Code](https://github.com/binwiederhier/ntfy), [Clients](https://github.com/binwiederhier/ntfy-android)) `Apache-2.0/GPL-2.0` `Go/Docker/K8S`
- [OTS](https://ots.fyi/) - 一次性秘密分享平台，使用浏览器中的对称256位AES加密。 ([Source Code](https://github.com/Luzifer/ots)) `Apache-2.0` `Go`
- [PushBits](https://github.com/pushbits/server) - 自托管的通知服务器，通过Matrix中继推送通知，类似于PushBullet和Gotify。 `ISC` `Go`
- [RetroShare](https://retroshare.cc) - 安全而去中心化的通信系统。提供去中心化聊天、论坛、消息传递、文件传输等功能。 ([Source Code](https://github.com/RetroShare/RetroShare)) `GPL-2.0` `C++`
- [Revolt](https://revolt.chat/) - Revolt 是一个基于现代网络技术构建的以用户为中心的聊天平台。 ([Source Code](https://github.com/revoltchat/revolt)) `AGPL-3.0` `Rust`
- [Rocket.Chat](https://rocket.chat/) - 与 Gitter.im 或 Slack 类似的团队聊天解决方案。 ([Source Code](https://github.com/RocketChat/Rocket.Chat)) `MIT` `Nodejs/Docker/K8S`
- [Screego](https://screego.net) - Screego 是一个简单的工具，可以通过 Web 浏览器快速分享您的屏幕给一个或多个人。 ([Demo](https://app.screego.net/), [Source Code](https://github.com/screego/server)) `GPL-3.0` `Docker/Go`
- [Screensy](https://github.com/screensy/screensy) - 一种简单的点对点屏幕共享解决方案，使用 WebRTC 进行屏幕共享。 ([Demo](https://screensy.marijn.it/)) `GPL-3.0` `Nodejs/Docker`
- [Shhh](https://github.com/smallwat3r/shhh) - 将秘密信息从电子邮件或聊天记录中保密，使用带有密码和过期日期的安全链接进行共享。 `MIT` `Python`
- [SimpleX Chat](https://github.com/simplex-chat/simplex-chat) - 最私密和安全的聊天和应用程序平台 - 现在支持双向棘轮端对端加密。 `AGPL-3.0` `Haskell`
- [Soketi](https://soketi.app/) - 简单、快速、弹性的开源WebSocket服务器（Pusher的替代品）。 ([Source Code](https://github.com/soketi/soketi)) `MIT` `Nodejs/Docker/K8S`
- [Spectrum 2](https://spectrum.im/) - Spectrum 2是一个开源的即时通讯传输工具。它允许用户即使在使用不同的即时通讯网络时也能进行聊天。 ([Source Code](https://github.com/SpectrumIM/spectrum2)) `GPL-3.0` `C++`
- [Synapse](https://matrix-org.github.io/synapse/latest/) - 用于 [Matrix](https://matrix.org/) 的服务器，Matrix 是一种用于分散式持久通信的开放标准。 ([Source Code](https://github.com/element-hq/synapse)) `Apache-2.0` `Python/deb`
- [Syndie](https://syndie.de) - Syndie 是一个用于运行分布式论坛的自由系统。 `CC0-1.0` `Java`
- [Tailchat](https://tailchat.msgbyte.com/) - 下一代 noIM 应用，位于您自己的工作空间，不仅仅是另一个 Slack/Discord/rocket.chat。 ([Demo](https://nightly.paw.msgbyte.com/), [Source Code](https://github.com/msgbyte/tailchat)) `Apache-2.0` `Docker/K8S/Nodejs`
- [TextBelt](https://github.com/typpo/textbelt) `⚠` - 使用运营商特定的网关免费发送短信的出站短信 API，无广告。 `MIT` `Javascript`
- [Tiledesk](https://tiledesk.com) - 从潜在客户生成到售后的一体化客户参与平台，从 WhatsApp 到您的网站。具有全渠道实时客服和由 AI 驱动的聊天机器人（可替代 Intercom、Zendesk、Tawk.to 和 Tidio）。 ([Source Code](https://github.com/Tiledesk/tiledesk)) `MIT` `Docker/K8S`
- [Tinode](https://github.com/tinode) - 即时通讯平台。后端使用 Go 编写。客户端包括：Swift iOS、Java Android、JS Web 应用、可脚本化命令行；还包括聊天机器人。 ([Demo](https://sandbox.tinode.co/), [Source Code](https://github.com/tinode/chat), [Clients](https://github.com/tinode/webapp)) `GPL-3.0` `Go`
- [Tox](https://tox.chat/) - 分布式、安全的即时通讯应用，具备音频和视频聊天功能。 ([Source Code](https://github.com/TokTok/c-toxcore)) `GPL-3.0` `C`
- [Typebot](https://typebot.io) - 对话式应用构建器（Typeform或Landbot的替代品）。 ([Source Code](https://github.com/baptisteArno/typebot.io)) `AGPL-3.0` `Docker`
- [WBO](https://github.com/lovasoa/whitebophir) - 实时协作的Web白板，可用于图表、绘图和笔记。 ([Demo](https://wbo.ophir.dev/)) `AGPL-3.0` `Nodejs/Docker`
- [Yopass](https://github.com/jhaals/yopass) - 安全共享机密、密码和文件。 ([Demo](https://yopass.se/)) `Apache-2.0` `Go/Docker`
- [Zulip](https://zulip.org) - Zulip是一款功能强大的开源群组聊天应用。 ([Source Code](https://github.com/zulip/zulip)) `Apache-2.0` `Python`


### 通信 - 电子邮件 - Web 邮件客户端

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[Webmail](https://en.wikipedia.org/wiki/Webmail)客户端。

- [Cypht](https://cypht.org) - 用于您的电子邮件帐户的Feed阅读器。 ([Source Code](https://github.com/cypht-org/cypht)) `LGPL-2.1` `PHP`
- [MailCare](https://mailcare.io) - 开源一次性电子邮件地址服务。 ([Source Code](https://gitlab.com/mailcare/mailcare)) `MIT` `PHP`
- [Roundcube](https://roundcube.net) - 具有类似应用程序界面的基于浏览器的 IMAP 客户端。 ([Source Code](https://github.com/roundcube/roundcubemail)) `GPL-3.0` `PHP/deb`
- [SnappyMail](https://snappymail.eu/) - 简单、现代、轻量且快速的基于Web的电子邮件客户端（RainLoop的分支）。 ([Demo](https://snappymail.eu/demo/), [Source Code](https://github.com/the-djmaze/snappymail)) `AGPL-3.0` `PHP`
- [SquirrelMail](https://squirrelmail.org) - 另一个基于浏览器的IMAP客户端。 ([Source Code](https://sourceforge.net/p/squirrelmail/code/HEAD/tree/)) `GPL-2.0` `PHP`


### 通信 - 电子邮件 - 完整解决方案

**[`^        back to top        ^`](#Awesome-Selfhosted)**

简化[电子邮件](https://en.wikipedia.org/wiki/Email)服务器的部署，例如适用于经验不足或急躁的管理员。

- [AnonAddy](https://anonaddy.com) - 开源的电子邮件转发服务，用于创建别名。 ([Source Code](https://github.com/anonaddy/anonaddy)) `MIT` `PHP`
- [DebOps](https://docs.debops.org/) - 将基于 Debian 的数据中心装在一个盒子里。一组通用的 Ansible 角色，可用于管理 Debian 或 Ubuntu 主机。 ([Source Code](https://github.com/debops/debops)) `GPL-3.0` `Ansible/Python`
- [docker-mailserver](https://docker-mailserver.github.io/docker-mailserver/edge/) - 在容器中运行的生产就绪的全栈但简单的邮件服务器（SMTP、IMAP、LDAP、Antispam、Antivirus等）。仅配置文件，没有 SQL 数据库。 ([Source Code](https://github.com/docker-mailserver/docker-mailserver)) `MIT` `Docker`
- [Dovel](https://dovel.email) - 根据简单的配置文件发送和接收电子邮件的 SMTP 服务器，可选择提供用于浏览电子邮件的 Web 界面。 ([Source Code](https://dovel.email/server/tree.html)) `LGPL-3.0` `Go`
- [emailwiz](https://github.com/LukeSmithxyz/emailwiz) - Luke Smith的Bash脚本，用于在Debian上完全自动设置Postfix/Dovecot/SpamAssassin/OpenDKIM服务器。 `GPL-3.0` `Shell`
- [homebox](https://github.com/progmaticltd/homebox) - Ansible脚本套件，用于在Debian上部署一个完全功能的邮件服务器。尽可能不显眼和自动化，专注于稳定性和安全性。 `GPL-3.0` `Shell`
- [Inboxen](https://inboxen.org) - Inboxen是一个为您提供无限数量独特收件箱的服务。 ([Source Code](https://codeberg.org/Inboxen/Inboxen)) `GPL-3.0` `Python`
- [iRedMail](https://www.iredmail.org/) - 基于Postfix和Dovecot的功能齐全的邮件服务器解决方案。 ([Source Code](https://github.com/iredmail/iRedMail)) `GPL-3.0` `Shell`
- [Maddy邮件服务器](https://github.com/foxcpp/maddy) - 一体化邮件服务器，实现了SMTP（MTA和MX）和IMAP。用单个守护程序替代了Postfix、Dovecot、OpenDKIM、OpenSPF、OpenDMARC。 `GPL-3.0` `Go`
- [Mail-in-a-Box](https://mailinabox.email/) - 通过一个命令将任何Ubuntu服务器转变为功能齐全的邮件服务器。 ([Source Code](https://github.com/mail-in-a-box/mailinabox)) `CC0-1.0` `Shell`
- [Mailcow](https://mailcow.email/) - 基于Dovecot、Postfix和其他开源软件的邮件服务器套件，提供现代化的Web界面进行管理。 ([Source Code](https://github.com/mailcow/mailcow-dockerized)) `GPL-2.0` `Docker/PHP`
- [Mailu](https://mailu.io/) - Mailu是一组Docker镜像形式的简单但功能齐全的邮件服务器。 ([Source Code](https://github.com/Mailu/Mailu)) `MIT` `Docker/Python`
- [Modoboa](https://modoboa.org/en/) - Modoboa 是一个包括现代简化的 Web 用户界面的邮件托管和管理平台。 ([Source Code](https://github.com/modoboa/modoboa)) `ISC` `Python`
- [Postal](https://docs.postalserver.io/) - 用于网站和Web服务器的完整且功能齐全的邮件服务器。 ([Source Code](https://github.com/postalserver/postal)) `MIT` `Docker/Ruby`
- [Simple NixOS Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - 利用 Nix 生态系统的完整邮件服务器解决方案。 `GPL-3.0` `Nix`
- [SimpleLogin](https://simplelogin.io) - 开源电子邮件别名解决方案，用于保护您的电子邮件地址。附带浏览器扩展和移动应用程序。 ([Source Code](https://github.com/simple-login/app)) `MIT` `Docker/Python`
- [Stalwart Mail Server](https:///stalw.art) - 一体化邮件服务器，支持JMAP、IMAP4和SMTP，并具有广泛的现代功能。 ([Source Code](https://github.com/stalwartlabs/mail-server)) `AGPL-3.0` `Rust/Docker`
- [Wildduck](https://wildduck.email/) - 可伸缩的无单点故障IMAP/POP3邮件服务器。 ([Source Code](https://github.com/nodemailer/wildduck)) `EUPL-1.2` `Nodejs/Docker`


### 通信 - 电子邮件 - 邮件传输代理

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[邮件传输代理](https://en.wikipedia.org/wiki/Message_transfer_agent)（MTA） - [SMTP](https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol)服务器。

- [chasquid](https://blitiri.com.ar/p/chasquid/) - 专注于简单性、安全性和易操作性的SMTP（电子邮件）服务器。 ([Source Code](https://blitiri.com.ar/git/r/chasquid/)) `Apache-2.0` `Go`
- [Courier MTA](https://www.courier-mta.org/) - 快速、可扩展的企业邮件/协作服务器，提供ESMTP、IMAP、POP3、Webmail、邮件列表、基本的基于Web的日历和调度服务。 ([Source Code](https://www.courier-mta.org/repo.html)) `GPL-3.0` `C/deb`
- [DragonFly](https://github.com/corecode/dma) - 适用于家庭和办公室使用的小型MTA。适用于Linux和FreeBSD。 `BSD-3-Clause` `C`
- [EmailRelay](https://emailrelay.sourceforge.net/) - 一个小巧且易于配置的Windows和Linux SMTP和POP3服务器。 ([Source Code](https://sourceforge.net/p/emailrelay/code/HEAD/tree/)) `GPL-3.0` `C++`
- [Exim](https://www.exim.org/) - 在剑桥大学开发的消息传输代理（MTA）。 ([Source Code](https://git.exim.org/exim.git)) `GPL-3.0` `C/deb`
- [Haraka](https://haraka.github.io/) - 用Javascript编写的高性能、可插件化的SMTP服务器。 ([Source Code](https://github.com/haraka/Haraka)) `MIT` `Nodejs`
- [MailCatcher](https://mailcatcher.me/) - 一个Ruby gem，部署了一个简单的SMTP MTA网关，接受所有邮件并在Web界面中显示。适用于调试或开发。 ([Source Code](https://github.com/sj26/mailcatcher)) `MIT` `Ruby`
- [OpenTrashmail](https://github.com/HaschekSolutions/opentrashmail) - 完整的垃圾邮件解决方案，提供一个SMTP服务器并具有用于管理接收的电子邮件的Web界面。支持多个和通配符域，并且完全基于文件（无需数据库）。包括RSS订阅和JSON API。 `Apache-2.0` `Python/PHP/Docker`
- [OpenSMTPD](https://opensmtpd.org/) - 来自OpenBSD项目的安全SMTP服务器实现。 ([Source Code](https://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.sbin/smtpd/)) `ISC` `C/deb`
- [OpenTrashmail](https://github.com/HaschekSolutions/opentrashmail) - 一款完整的垃圾邮件解决方案，提供一个暴露SMTP服务器并具有用于管理接收的电子邮件的Web界面。支持多个和通配符域，完全基于文件（无需数据库）。包括RSS订阅和JSON API。 `Apache-2.0` `Python/PHP/Docker`
- [Postfix](http://www.postfix.org/) - 快速、易于管理且安全的Sendmail替代品。 `IPL-1.0` `C/deb`
- [Sendmail](https://www.proofpoint.com/us/products/email-protection/open-source-email-solution) - 消息传输代理（MTA）。 `Sendmail` `C/deb`
- [Slimta](https://www.slimta.org) - 基于Python构建的邮件传输库。 ([Source Code](https://github.com/slimta/python-slimta)) `MIT` `Python`
- [Stalwart SMTP](https://stalw.art/smtp) - 设计注重安全性、速度和广泛可配置性的现代SMTP服务器。 ([Source Code](https://github.com/stalwartlabs/smtp-server)) `AGPL-3.0` `Rust`


### 通信 - 电子邮件 - 邮件列表和通讯

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[邮件列表](https://en.wikipedia.org/wiki/Mailing_list)服务器和群发邮件软件 - 一条消息发送给多个接收者。

- [Dada Mail](https://dadamailproject.com/) - 基于Web的列表管理系统，可用于公告列表和/或讨论列表。 ([Source Code](https://github.com/justingit/dada-mail)) `GPL-2.0` `Perl`
- [Gray Duck Mail](https://grayduckmail.com) - 自托管的电子邮件讨论列表管理，使用外部电子邮件提供商。 ([Source Code](https://github.com/wagesj45/gray-duck-mail)) `GPL-3.0` `Docker`
- [HyperKitty](https://wiki.list.org/HyperKitty) - 开源的Django应用，提供访问GNU Mailman v3档案的Web界面。 ([Demo](https://lists.mailman3.org/), [Source Code](https://gitlab.com/mailman/hyperkitty)) `GPL-3.0` `Python`
- [Keila](https://www.keila.io) - 自托管的可靠且易于使用的新闻通讯工具（替代Mailchimp或Sendinblue）。 ([Demo](https://app.keila.io), [Source Code](https://github.com/pentacent/keila)) `AGPL-3.0` `Docker`
- [Listmonk](https://listmonk.app/) - 高性能的自托管通讯和邮件列表管理器，带有现代化的仪表板。 ([Source Code](https://github.com/knadh/listmonk)) `AGPL-3.0` `Go/Docker`
- [Mailman](https://www.gnu.org/software/mailman/) - GNU邮件列表服务器。 `GPL-3.0` `Python`
- [Mautic](https://www.mautic.org/) - Mautic是一款营销自动化软件（电子邮件、社交等）。 ([Source Code](https://github.com/mautic/mautic)) `GPL-3.0` `PHP`
- [Mautic](https://www.mautic.org/) - Mautic是一款营销自动化软件（电子邮件、社交等）。 ([Source Code](https://github.com/mautic/mautic)) `GPL-3.0` `PHP`
- [phpList](https://phplist.org) - 具有高级订阅者、退信和插件管理功能的新闻通讯和电子邮件营销工具。 ([Source Code](https://github.com/phpList/phplist3)) `AGPL-3.0` `PHP`
- [Postorius](https://docs.mailman3.org/projects/postorius/en/latest/) - 用于访问GNU Mailman的Web用户界面。 ([Source Code](https://gitlab.com/mailman/postorius/)) `GPL-3.0` `Python`
- [Schleuder](https://schleuder.nadir.org/) - 具有转发功能的 GPG 启用的邮件列表管理器。 ([Source Code](https://0xacab.org/schleuder/schleuder/tree/master)) `GPL-3.0` `Ruby`
- [Sympa](https://www.sympa.community/) - 邮件列表管理器。 ([Source Code](https://github.com/sympa-community/sympa)) `GPL-2.0` `Perl`


### 通信 - 电子邮件 - 邮件投递代理

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[邮件传送代理](https://en.wikipedia.org/wiki/Message_delivery_agent)（MDA） - [IMAP](https://en.wikipedia.org/wiki/Internet_Message_Access_Protocol)/[POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol)服务器软件。

- [Cyrus IMAP](https://www.cyrusimap.org/) - 电子邮件（IMAP/POP3）、联系人和日历服务器。 ([Source Code](https://github.com/cyrusimap/cyrus-imapd)) `BSD-3-Clause-Attribution` `C`
- [Dovecot](https://www.dovecot.org/) - 主要以安全性为重点编写的IMAP和POP3服务器。 ([Source Code](https://github.com/dovecot/core)) `MIT/LGPL-2.1` `C/deb`
- [MailForm](https://github.com/Feuerhamster/mailform) - 用于联系表单等的轻量级自托管电子邮件服务（Formspree和SendGrid的替代品）。 `Apache-2.0` `Nodejs/Docker`
- [Piler](https://www.mailpiler.org/) - 功能丰富的电子邮件归档解决方案。 ([Source Code](https://bitbucket.org/jsuto/piler)) `GPL-3.0` `C`
- [Stalwart JMAP](https://stalw.art/jmap) - 一个设计为安全、快速、强大且可扩展的JMAP和IMAP服务器。 ([Source Code](https://github.com/stalwartlabs/jmap-server)) `AGPL-3.0` `Rust/Docker`


### 通信 - 社交网络和论坛

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[社交网络](https://en.wikipedia.org/wiki/Social_networking_service)和[论坛](https://en.wikipedia.org/wiki/Internet_forum)软件。

- [Akkoma](https://akkoma.social/) - 基于 Mastodon、GNU social 和 ActivityPub 兼容性的联邦微博服务器。 ([Source Code](https://akkoma.dev/AkkomaGang/akkoma)) `AGPL-3.0` `Elixir/Docker`
- [Anahita](https://www.anahita.io/) - 开源社交网络框架和平台。 ([Source Code](https://github.com/anahitasocial/anahita)) `GPL-3.0` `PHP`
- [Answer](https://answer.dev/) - 一款开源的基于知识的社区软件。您可以使用它快速构建用于产品技术支持、客户支持、用户交流等的问答社区。 ([Source Code](https://github.com/answerdev/answer)) `Apache-2.0` `Docker/Go`
- [AsmBB](https://board.asm32.info) - 一款快速、基于 SQLite 的用汇编语言编写的论坛引擎。 ([Source Code](https://asm32.info/fossil/asmbb/index)) `EUPL-1.2` `Assembly`
- [Buddycloud](http://buddycloud.com/) - 用于将用户对用户、群组和社交消息构建到您的应用程序中的工具、库、服务和社区。节省时间，可扩展，支持您。 ([Source Code](https://github.com/buddycloud)) `Apache-2.0` `Java`
- [BuddyPress](https://buddypress.org/about/) - 强大的插件，通过用户配置文件、活动流、用户组等社交网络功能，将您的 WordPress.org 强大的站点超越博客。 ([Source Code](https://github.com/buddypress/BuddyPress)) `GPL-2.0` `PHP`
- [Cactus Comments](https://cactus.chat/) - Cactus Comments 是一个建立在 Matrix 上的面向开放网络的联邦评论系统。 ([Demo](https://cactus.chat/demo/), [Source Code](https://gitlab.com/cactus-comments/)) `GPL-3.0` `Docker/Python`
- [Chirpy](https://chirpy.dev) - Chirpy是一个开源的、注重隐私且可定制的Disqus（评论系统）替代品。 ([Demo](https://chirpy.dev/play), [Source Code](https://github.com/devrsi0n/chirpy)) `AGPL-3.0` `Docker/Nodejs`
- [Coral](https://coralproject.net/) - Vox Media提供的更好的评论体验。 ([Source Code](https://github.com/coralproject/talk)) `Apache-2.0` `Docker/Nodejs`
- [diaspora*](https://diasporafoundation.org/) - 分布式社交网络服务器。 ([Source Code](https://github.com/diaspora/diaspora)) `AGPL-3.0` `Ruby`
- [Discourse](https://www.discourse.org/) - 基于Ruby和JS的高级论坛/社区解决方案。 ([Demo](https://try.discourse.org/), [Source Code](https://github.com/discourse/discourse)) `GPL-2.0` `Docker`
- [Elgg](https://elgg.org/) - 强大的开源社交网络引擎。 ([Source Code](https://github.com/Elgg/Elgg)) `GPL-2.0` `PHP`
- [Enigma 1/2 BBS](https://nuskooler.github.io/enigma-bbs/) - Enigma 1/2是一个现代的、跨平台的BBS引擎，支持无限数量的“呼叫者”并提供对传统的DOS门户游戏的支持。 ([Demo](https://l33t.codes/xibalba-bbs/), [Source Code](https://github.com/NuSkooler/enigma-bbs)) `BSD-2-Clause` `Shell/Docker/Nodejs`
- [Flarum](https://flarum.org) - 愉悦简单的论坛。Flarum 是下一代论坛软件，让在线讨论再次变得有趣。 ([Source Code](https://github.com/flarum/flarum)) `MIT` `PHP`
- [FlaskBB](https://flaskbb.org/) - FlaskBB 是使用微框架 Flask 编写的 Python 论坛软件。您可以轻松创建新主题、帖子并发送私人消息给其他用户。它还包括基本的管理和审查工具。 ([Source Code](https://github.com/flaskbb/flaskbb)) `BSD-3-Clause` `Python`
- [Friendica](https://friendi.ca/) - 社交通讯服务器。 ([Source Code](https://github.com/friendica/friendica)) `AGPL-3.0` `PHP`
- [GoToSocial](https://github.com/superseriousbusiness/gotosocial) - 实现Mastodon客户端API的ActivityPub联合社交网络服务器。 `AGPL-3.0` `Docker/Go`
- [Hubzilla](https://hubzilla.org) - 分布式身份、隐私、发布、共享、云存储和通讯/社交平台。 ([Source Code](https://framagit.org/hubzilla/core)) `MIT` `PHP`
- [HumHub](https://www.humhub.org/) - 用于私人社交网络的灵活工具包。 ([Source Code](https://github.com/humhub/humhub)) `AGPL-3.0` `PHP`
- [Isso](https://isso-comments.de/) - 用Python和Javascript编写的轻量级评论服务器。旨在成为Disqus的即插即用替代方案。 ([Source Code](https://github.com/posativ/isso)) `MIT` `Python/Docker`
- [kbin](https://kbin.pub/) - 联合内容聚合器和微博平台。 ([Source Code](https://github.com/ernestwisniewski/kbin)) `AGPL-3.0` `PHP/Nodejs/Docker`
- [Lemmy](https://join-lemmy.org/) - 一个面向联合网络的链接聚合器/Reddit克隆（作为Reddit的替代品）。 ([Source Code](https://github.com/LemmyNet/lemmy)) `AGPL-3.0` `Docker/Rust`
- [Libreddit](https://github.com/libreddit/libreddit) `⚠` - 使用Rust编写的Reddit的私有前端。 `AGPL-3.0` `Rust`
- [Loomio](https://www.loomio.org/) - Loomio是一个协作决策工具，使任何人都能轻松参与影响他们的决策。 ([Source Code](https://github.com/loomio/loomio)) `AGPL-3.0` `Docker`
- [Mastodon](https://joinmastodon.org/) - 联合式微博服务。 ([Source Code](https://github.com/mastodon/mastodon), [Clients](https://github.com/hyperupcall/awesome-mastodon)) `AGPL-3.0` `Ruby`
- [Misago](https://misago-project.org/) - Misago 是一个功能齐全的现代论坛应用程序，快速、可扩展且响应灵敏。 ([Source Code](https://github.com/rafalp/Misago)) `GPL-2.0` `Docker`
- [Misskey](https://misskey.io/) - 去中心化的类应用微博服务器/社交网络服务，适用于 Fediverse，使用 ActivityPub 协议，类似于 GNU social 和 Mastodon。 ([Source Code](https://github.com/misskey-dev/misskey)) `AGPL-3.0` `Nodejs/Docker`
- [Movim](https://movim.eu/) - 现代化的联邦社交网络，基于 XMPP，具有完整的群聊、订阅和微博功能。 ([Source Code](https://github.com/movim/movim)) `AGPL-3.0` `PHP/Docker`
- [MyBB](https://mybb.com/) - 免费、可扩展的论坛软件包。 ([Source Code](https://github.com/mybb/mybb)) `LGPL-3.0` `PHP`
- [Nitter](https://nitter.net) `⚠` - Twitter的替代前端。 ([Source Code](https://github.com/zedeus/nitter)) `AGPL-3.0` `Nim/Docker`
- [NodeBB](https://nodebb.org/) - 面向现代网络构建的论坛软件。 ([Source Code](https://github.com/NodeBB/NodeBB)) `GPL-3.0` `Nodejs`
- [Orange Forum](https://www.goodoldweb.com/) - Orange Forum是一个易于部署的论坛，具有最小的依赖关系并使用极少量的JavaScript。 ([Source Code](https://github.com/s-gv/orangeforum)) `BSD-3-Clause` `Go`
- [OSSN](https://www.opensource-socialnetwork.org/) - 开源社交网络（OSSN）是一款用PHP编写的社交网络软件。它允许您创建一个社交网络网站，并帮助您的会员建立与那些分享类似专业或个人兴趣的人的社交关系。 ([Source Code](https://github.com/opensource-socialnetwork/opensource-socialnetwork)) `GPL-2.0` `PHP`
- [phpBB](https://www.phpbb.com/) - 一款平面论坛公告板软件解决方案，可用于与一群人保持联系，也可以为整个网站提供支持。 ([Source Code](https://github.com/phpbb/phpbb)) `GPL-2.0` `PHP`
- [PixelFed](https://pixelfed.social) - Pixelfed 是一个开源的、联邦化的平台，是 Instagram 的替代品。 ([Source Code](https://github.com/pixelfed/pixelfed)) `AGPL-3.0` `PHP`
- [Pleroma](https://pleroma.social) - 联合式的微博服务器，兼容 Mastodon、GNU social 和 ActivityPub。 ([Source Code](https://git.pleroma.social/pleroma/pleroma)) `AGPL-3.0` `Elixir`
- [qpixel](https://codidact.com/) - 基于问答的社区知识共享软件。 ([Source Code](https://github.com/codidact/qpixel)) `AGPL-3.0` `Ruby`
- [remark42](https://remark42.com/) - 一款轻量简单的评论引擎，不会监视用户。可以嵌入到博客、文章或任何读者添加评论的地方。 ([Demo](https://remark42.com/demo/), [Source Code](https://github.com/umputun/remark42)) `MIT` `Docker/Go`
- [Retrospring](https://github.com/retrospring/retrospring) - 一个免费、开源的社交网络，遵循类似 Formspring、ask.fm 或 CuriousCat 的 Q/A（问答）原则。 ([Demo](https://retrospring.net)) `AGPL-3.0` `Ruby/Nodejs`
- [Scoold](https://scoold.com) - 一个 JAR 中的 Stack Overflow。一款具备全文搜索、SAML、LDAP 集成和社交登录支持的企业级问答平台。 ([Demo](https://live.scoold.com), [Source Code](https://github.com/Erudika/scoold)) `Apache-2.0` `Java/Docker/K8S`
- [Simple Machines Forum](https://www.simplemachines.org/) - 免费、专业级的软件包，可让您在几分钟内建立自己的在线社区。 ([Source Code](https://github.com/SimpleMachines/SMF)) `BSD-3-Clause` `PHP`
- [Socialhome](https://socialhome.network) - 分布式和去中心化的个人资料构建器和社交网络引擎。 ([Demo](https://socialhome.network/), [Source Code](https://github.com/jaywink/socialhome)) `AGPL-3.0` `Docker/Python`
- [Takahē](https://jointakahe.org/) - 联合式微博服务器。兼容 Mastodon 和 ActivityPub。 ([Source Code](https://github.com/jointakahe/takahe)) `BSD-3-Clause` `Docker`
- [Talkyard](https://www.talkyard.io/) - 创建一个社区，让您的用户提出想法并得到问题的解答。并进行友好的开放式讨论和聊天（类似 Slack/StackOverflow/Discourse/Reddit/Disqus 的混合体）。 ([Demo](https://www.talkyard.io/forum/latest), [Source Code](https://github.com/debiki/talkyard)) `AGPL-3.0` `Docker/Scala`
- [yarn.social](https://yarn.social) - 自托管、类似Twitter™的分布式微日志平台。无广告、无追踪，您的内容，您的数据。 ([Source Code](https://git.mills.io/yarnsocial/yarn)) `MIT` `Go`
- [Zusam](https://github.com/zusam/zusam) - 用于自托管小组或家庭私人论坛的自由开源方式。 ([Demo](https://demo.zusam.org)) `AGPL-3.0` `PHP`


### 通信 - 视频会议

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[视频/网络会议](https://en.wikipedia.org/wiki/Web_conferencing)工具和软件。

_Related: [会议管理](#会议管理)_

- [BigBlueButton](https://bigbluebutton.org/) - 支持实时共享音频、视频、幻灯片（带有白板控制）、聊天和屏幕。教师可以通过投票、表情符号和分组房间与远程学生互动。 ([Source Code](https://github.com/bigbluebutton/bigbluebutton)) `LGPL-3.0` `Java`
- [Galene](https://galene.org/) - Galène（或 Galene）是一个易于部署且需要中等服务器资源的视频会议服务器（“SFU”）。 ([Source Code](https://github.com/jech/galene)) `MIT` `Go`
- [Janus](https://janus.conf.meetecho.com/) - 通用、轻量级、极简的WebRTC服务器。 ([Demo](https://janus.conf.meetecho.com/demos.html), [Source Code](https://github.com/meetecho/janus-gateway)) `GPL-3.0` `C`
- [Jitsi Meet](https://jitsi.org/Projects/JitsiMeet) - Jitsi Meet是一个使用Jitsi Videobridge提供高质量、可扩展视频会议的开源（MIT）WebRTC JavaScript应用。 ([Demo](https://meet.jit.si), [Source Code](https://github.com/jitsi/jitsi-meet)) `Apache-2.0` `Nodejs/Docker/deb`
- [Jitsi Video Bridge](https://jitsi.org/Projects/JitsiVideobridge) - 兼容WebRTC的选择性转发单元（SFU），允许多用户视频通信。 ([Source Code](https://github.com/jitsi/jitsi-videobridge)) `Apache-2.0` `Java/deb`
- [MiroTalk C2C](https://c2c.mirotalk.com) - 实时点对点视频通话和屏幕共享，端到端加密，可嵌入任何网站的简单 iframe 中。 ([Source Code](https://github.com/miroslavpejic85/mirotalkc2c)) `MIT` `Nodejs/Docker`
- [MiroTalk P2P](https://p2p.mirotalk.com) - 简单、安全、快速的实时视频会议，支持高达 4K 和 60fps，兼容所有浏览器和平台。 ([Demo](https://p2p.mirotalk.com/newcall), [Source Code](https://github.com/miroslavpejic85/mirotalk)) `AGPL-3.0` `Nodejs/Docker`
- [MiroTalk SFU](https://sfu.mirotalk.com) - 简单、安全、可扩展的实时视频会议，支持高达 4K，兼容所有浏览器和平台。 ([Demo](https://sfu.mirotalk.com/newroom), [Source Code](https://github.com/miroslavpejic85/mirotalksfu)) `AGPL-3.0` `Nodejs/Docker`
- [plugNmeet](https://www.plugnmeet.org/) - 可伸缩、高性能、开源的网络会议系统。 ([Demo](https://demo.plugnmeet.com/login.html), [Source Code](https://github.com/mynaparrot/plugNmeet-server)) `MIT` `Docker/Go`


### 静态网站生成器

**[`^        back to top        ^`](#Awesome-Selfhosted)**

[静态网站生成器](https://en.wikipedia.org/wiki/Web_template_system#Static_site_generators)根据原始数据、纯文本文件和一组模板生成完整的静态 HTML 网站。

**Please visit [staticsitegenerators.net](https://staticsitegenerators.net), [staticgen.com](https://www.staticgen.com)**

_Related: [博客平台](#博客平台), [照片和视频库](#照片和视频库), [内容管理系统（CMS）](#内容管理系统（cms）)_



### 预订和日程安排

**[`^        back to top        ^`](#Awesome-Selfhosted)**

活动调度、预订和会议管理软件。

_Related: [投票和事件](#投票和事件)_

- [Alf.io](https://alf.io/) - 开源的票务预订系统。 ([Demo](https://demo.alf.io/authentication), [Source Code](https://github.com/alfio-event/alf.io)) `GPL-3.0` `Java`
- [Cal.com](https://cal.com/) - 开源的在线预约系统。 ([Demo](https://app.cal.com/bailey), [Source Code](https://github.com/calcom/cal.com)) `MIT` `Nodejs`
- [Easy!Appointments](https://easyappointments.org/) - 一个高度可定制的 Web 应用，允许您的客户通过网络预约与您的见面。 ([Demo](https://easyappointments.org/demo/), [Source Code](https://github.com/alextselegidis/easyappointments)) `GPL-3.0` `PHP`
- [QloApps](https://qloapps.com/) - 一款开源、可定制且直观的基于Web的酒店预订系统和预订引擎。 ([Demo](https://demo.qloapps.com/), [Source Code](https://github.com/webkul/hotelcommerce)) `OSL-3.0` `PHP/Nodejs`
- [Rallly](https://rallly.co) - 创建投票以选择日期和时间（Doodle的替代品）。 ([Demo](https://app.rallly.co), [Source Code](https://github.com/lukevella/rallly)) `AGPL-3.0` `Nodejs/Docker`
- [Seatsurfing](https://seatsurfing.app/) - 基于 Web 的应用程序，用于预订办公室的座位、桌子和房间。 ([Demo](https://seatsurfing.app/get-started/), [Source Code](https://github.com/seatsurfing/backend)) `GPL-3.0` `Docker`


### 食谱管理

**[`^        back to top        ^`](#Awesome-Selfhosted)**

用于管理[食谱](https://en.wikipedia.org/wiki/Recipe)的软件和工具。

- [Bar Assistant](https://github.com/karlomikus/bar-assistant) - Bar Assistant是一个自托管的应用，用于管理家庭酒吧。它允许您添加成分，搜索鸡尾酒，并创建自定义鸡尾酒配方。 ([Demo](https://bar.karlomikus.com/)) `MIT` `PHP/Docker`
- [KitchenOwl](https://tombursch.github.io/kitchenowl/) - 一款跨平台的购物清单、食谱存储、费用跟踪和餐饮计划应用，遵循 Material Design 设计语言。 ([Source Code](https://github.com/TomBursch/kitchenowl)) `AGPL-3.0` `Docker/deb`
- [Mealie](https://nightly.mealie.io/) - 受Material Design启发的食谱管理器，具有分类和标签管理、购物清单、餐饮计划和站点定制功能。Mealie专注于简单的用户交互，以确保整个家庭都能使用该应用程序。 ([Source Code](https://github.com/mealie-recipes/mealie)) `MIT` `Python`
- [RecipeSage](https://github.com/julianpoy/recipesage) - 一个食谱保存器、餐饮计划组织者和购物清单管理器，可以直接从任何URL导入食谱。 ([Demo](https://recipesage.com)) `AGPL-3.0` `Nodejs`
- [Specifically Clementines](https://davideshay.github.io/groceries/) - 食品购物应用（之前是Groceries），提供与多个用户/设备（Web/Android/iOS）的可靠同步、食谱和与Tandoor的集成。 ([Demo](https://www.specificallyclementines.com/), [Source Code](https://github.com/davideshay/groceries)) `MIT` `Docker`
- [Tandoor Recipes](https://docs.tandoor.dev/) - Django 应用，用于管理、标记和搜索食谱，可使用内置模型或托管 PDF、图像或其他文件的外部存储提供程序。 ([Demo](https://app.tandoor.dev/accounts/login/?demo), [Source Code](https://github.com/TandoorRecipes/recipes)) `MIT` `Python/Docker/K8S`


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


--------------------

## 反特性

- `⚠` - 依赖于用户无法控制的专有服务

--------------------

## 外部链接

**[`^        返回顶部        ^`](#自托管精选)**

- [Awesome Sysadmin](https://github.com/awesome-foss/awesome-sysadmin) - 精选的令人惊叹的开源系统管理员资源清单。
- 面向隐私和去中心化的一些形式的软件列表: [PRISM Break](https://prism-break.org/en/)，[privacytools.io](https://www.privacytools.io/)，[Alternative Internet](https://redecentralize.github.io/alternative-internet/)，[Libre Projects](https://libreprojects.net/)，[Easy Indie App](https://easyindie.app)
- 其他令人惊叹的清单: [Awesome Big Data](https://github.com/0xnr/awesome-bigdata)，[Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets)
- 动态域名服务: [Afraid.org](https://freedns.afraid.org/domain/registry/)，[Pagekite](https://pagekite.net/)
- 社群/论坛: [/c/selfhosted 在 lemmy.world](https://lemmy.world/c/selfhosted)，[/c/selfhost 在 lemmy.ml](https://lemmy.ml/c/selfhost)，[/m/selfhosted 在 kbin.social](https://kbin.social/m/selfhosted)，[/r/selfhosted 在 reddit](https://old.reddit.com/r/selfhosted/)，[r-selfhosted 论坛](https://forum.r-selfhosted.com/)，[/r/selfhosted Matrix 频道](https://matrix.to/#/#selfhosted:selfhosted.chat)，[Homelab 论坛](https://homelabforum.com/)，[/r/homelab 在 reddit](https://old.reddit.com/r/homelab/)，[IndieWeb](https://indieweb.org/)
- [theme.park](https://theme-park.dev/) - 为 50 个自托管应用提供主题/皮肤的集合！([源代码](https://github.com/GilbN/theme.park/)) `MIT` `CSS`
- [追踪 Awesome Selfhosted](https://www.trackawesomelist.com/awesome-selfhosted/awesome-selfhosted/) - 获取 awesome-selfhosted 的最新更新。

--------------------

## 贡献

贡献指南可在[此处](https://github.com/zituoguan/zituoguan-data/blob/master/CONTRIBUTING.md)找到。

## 许可证

此清单采用 [Creative Commons Attribution-ShareAlike 3.0 Unported](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/LICENSE) 许可。许可条款摘要可在[此处](https://creativecommons.org/licenses/by-sa/3.0/)查看。
作者列表可在 [AUTHORS](https://github.com/zituoguan/zituoguan-data/blob/master/AUTHORS) 文件中找到。
