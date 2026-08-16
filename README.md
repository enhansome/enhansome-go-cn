【导读】：[awesome-go](https://github.com/avelino/awesome-Go) ⭐ 181,239 | 🐛 211 | 🌐 Go | 📅 2026-08-16 就是 `avelino` 发起维护的 Go 资源列表，内容包括：音频和音乐库、命令行工具、服务端应用、流处理、持续集成、数据库、机器学习、NLP、物联网、中间件、文本处理、安全、机器人技术等。

这个列表堪称最全面的 Go 资源汇总，在 GitHub 已有近 `6 万 Star`。

中文版由`开源前哨`和`Go开发大全`微信公号团队维护更新，在 GitHub 已有近`3100 Star`，欢迎在 Github 上关注。这个中文版的资源库会定期同步更新到这里。

#### 本项目的参与者

* 维护者：`开源前哨`和`Go开发大全`微信公号团队。 「开源前哨」会定期在知乎专栏分享最新、有趣和热门的开源项目，每个项目都有详细的介绍和示例。传送门：<https://www.zhihu.com/column/c_1317124962785062912>

* 贡献者： [xiaokugua250](https://github.com/xiaokugua250)、[艾凌风](https://github.com/hanxiaomax)、[Allenxuxu](https://github.com/Allenxuxu)、[sanrentai](https://github.com/sanrentai)、[wu.zhenhuan](https://github.com/hawkwzh)、[tangyouhua](https://github.com/tangyouhua)、[roseduan](https://github.com/roseduan)、You

注：名单不分排名，不定期补充更新

# Awesome 资源列表 with stars

* [目录](#目录)
  * [音频和音乐库](#音频和音乐库)
  * [认证和OAuth授权](#认证和oauth授权)
  * [机器人相关](#机器人相关)
  * [命令行工具](#命令行工具)
    * [标准 CLI](#标准-cli)
  * [高级控制台UI](#高级控制台ui)
  * [配置管理](#配置管理)
  * [持续集成](#持续集成)
  * [css预处理](#css预处理)
  * [数据结构](#数据结构)
  * [数据库](#数据库)
    * [数据库工具](#数据库工具)
    * [SQL 查询语句构建库](#sql-查询语句构建库)
  * [数据库驱动](#数据库驱动)
  * [日期和时间](#日期和时间)
  * [分布式系统](#分布式系统)
  * [动态DNS](#动态dns)
  * [邮件库](#邮件库)
  * [脚本语言与嵌入式编程](#脚本语言与嵌入式编程)
  * [错误处理](#错误处理)
  * [文件处理](#文件处理)
  * [金融领域相关库](#金融领域相关库)
  * [表单](#表单)
  * [函数式编程](#函数式编程)
  * [游戏开发](#游戏开发)
  * [代码生成与泛型](#代码生成与泛型)
  * [位置信息与地理GEO处理库](#位置信息与地理geo处理库)
  * [Goroutines](#goroutines)
  * [GUI](#gui)
  * [硬件](#硬件)
  * [Images 图像处理](#images-图像处理)
  * [物联网(IOT)](#物联网iot)
  * [作业调度](#作业调度)
  * [JSON](#json)
  * [Logging 日志库](#logging-日志库)
  * [机器学习](#机器学习)
  * [Microsoft Office](#microsoft-office)
    * [EXCEL](#excel)
  * [其他杂项](#其他杂项)
    * [依赖性注入](#依赖性注入)
    * [项目结构](#项目结构)
    * [字符串处理](#字符串处理)
    * [暂未分类](#暂未分类)
  * [自然语言处理](#自然语言处理)
  * [网络相关库](#网络相关库)
    * [Http Client](#http-client)
    * [OpenGL](#opengl)
    * [ORM](#orm)
  * [Go语言包管理](#go语言包管理)
    * [查询语句](#查询语句)
  * [资源嵌入](#资源嵌入)
  * [数据分析与数据科学](#数据分析与数据科学)
  * [安全领域相关库](#安全领域相关库)
  * [序列化](#序列化)
  * [服务端应用](#服务端应用)
  * [流处理](#流处理)
  * [模板引擎](#模板引擎)
  * [测试相关](#测试相关)
  * [文本处理](#文本处理)
  * [第三方API](#第三方api)
  * [工具库](#工具库)
  * [UUID](#uuid)
  * [校验库](#校验库)
    * [版本控制](#版本控制)
  * [视频](#视频)
  * [web框架](#web框架)
  * [中间件](#中间件)
    * [中间件](#中间件-1)
    * [创建http中间件的代码库](#创建http中间件的代码库)
  * [路由](#路由)
  * [WebAssembly](#webassembly)
  * [Windows](#windows)
  * [XML](#xml)
  * [相关工具](#相关工具)
    * [代码分析](#代码分析)
  * [编辑器插件](#编辑器插件)
  * [Go  代码生成工具](#go--代码生成工具)
  * [Go工具](#go工具)
  * [软件包](#软件包)
    * [devops 工具](#devops-工具)
    * [其他软件库和软件包](#其他软件库和软件包)

## 音频和音乐库

* [Oto](https://github.com/hajimehoshi/oto) ⭐ 1,946 | 🐛 21 | 🌐 Go | 📅 2026-08-15 :  可用于在多个平台上播放音频的底层库
* [PortAudio](https://github.com/gordonklaus/portaudio) ⭐ 841 | 🐛 7 | 🌐 Go | 📅 2026-02-03 :  音频`I/O`库`PortAudio`的`go`语言封装
* [music-theory](https://github.com/go-music-theory/music-theory) ⭐ 460 | 🐛 1 | 🌐 Go | 📅 2026-01-21 : 基于`go`语言音乐理论模型。
* [GoAudio](https://github.com/DylanMeeus/GoAudio) ⭐ 426 | 🐛 11 | 🌐 Go | 📅 2024-04-23 :  原生`Go`语言编写的音频处理库。
* [malgo](https://github.com/gen2brain/malgo) ⭐ 423 | 🐛 11 | 🌐 C | 📅 2026-05-13 :`go`语言开发的迷你音频库。
* [id3v2](https://github.com/bogem/id3v2) ⭐ 369 | 🐛 24 | 🌐 Go | 📅 2023-10-28 :`go`语言开发的`ID3`编码和解码库,具有快速和稳定的特性。
* [flac](https://github.com/mewkiz/flac) ⭐ 360 | 🐛 9 | 🌐 Go | 📅 2025-08-18 :  原生`Go`语言编写的FLAC数据流编码与解码器。
* [waveform](https://github.com/mdlayher/waveform) ⚠️ Archived : 基于音频流来生成音频波形图的`go`语言库
* [portmidi](https://github.com/rakyll/portmidi) ⭐ 290 | 🐛 15 | 🌐 Go | 📅 2022-03-20 :  音频`I/O`库`PortMidi`的`go`语言封装
* [mix](https://github.com/go-mix/mix) ⭐ 182 | 🐛 7 | 🌐 Go | 📅 2026-01-21 :   针对音乐类应用程序的基于序列的`Go`原生音频混音器。
* [mp3](https://github.com/tcolgate/mp3) ⭐ 142 | 🐛 0 | 🌐 Go | 📅 2017-04-26 :   原生Go语言的mp3解码器.
* [go-sox](https://github.com/krig/go-sox) ⚠️ Archived : `libsox`库的`go`语言封装
* [gaad](https://github.com/Comcast/gaad) ⭐ 137 | 🐛 2 | 🌐 Go | 📅 2023-01-27 :  原生`Go`语言编写的AAC比特流解析器。
* [minimp3](https://github.com/tosone/minimp3) ⭐ 133 | 🐛 3 | 🌐 C | 📅 2025-07-09 :  轻量级`MP3`解码库。
* [gosamplerate](https://github.com/dh1tw/gosamplerate) ⭐ 39 | 🐛 0 | 🌐 Go | 📅 2024-01-28 : `libsamplerate`库的`Go`语言封装
* [vorbis](https://github.com/mccoyst/vorbis) ⭐ 33 | 🐛 3 | 🌐 Go | 📅 2023-08-18 : `Go`语言版`Vorbis`解码器（使用到`CGO`,但并不依赖与cgo）

***

## 认证和OAuth授权

* [casbin](https://github.com/hsluoyz/casbin) ⭐ 20,324 | 🐛 42 | 🌐 Go | 📅 2026-08-13 : 支持`ACL`、`RBAC`、`ABAC`等访问控制模型的授权与认证库。
* [jwt-go](https://github.com/dgrijalva/jwt-go) ⚠️ Archived :   -`JSON Web Tokens`（JWT）的Golang实现。
* [goth](https://github.com/markbates/goth) ⭐ 6,591 | 🐛 147 | 🌐 Go | 📅 2026-02-11 :   以简单、干净、常用的方式来使用`OAuth`和`OAuth2`。支持多种身份认证。
* [oauth2](https://github.com/golang/oauth2) ⭐ 5,889 | 🐛 60 | 🌐 Go | 📅 2026-03-08 :  继承自`goauth2`。实现了JWT,Google APIs,GCE,GAE的通用`OAuth 2.0`授权包。
* [authboss](https://github.com/volatiletech/authboss) ⭐ 4,196 | 🐛 41 | 🌐 Go | 📅 2026-07-10 : 针对`web`应用的模块化认证系统,尽量去除模版代码和硬编码来以灵活可配置的方式来嵌入到web应用程序中,从而避免重复编码和重复配置。
* [scs](https://github.com/alexedwards/scs) ⭐ 2,611 | 🐛 17 | 🌐 Go | 📅 2025-11-20 : `HTTP`服务器的会话管理器。
* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) ⭐ 2,147 | 🐛 28 | 🌐 Go | 📅 2025-12-09 :  不需要其他依赖的、符合规范的、用`Golang` 编写的`OAuth2` 服务器。
* [gologin](https://github.com/dghubble/gologin) ⭐ 1,959 | 🐛 1 | 🌐 Go | 📅 2026-08-11 :  适用于OAuth1和OAuth2多身份登录认证的实现方案
* [go-jose](https://github.com/square/go-jose) ⚠️ Archived :  相当完整地实现了JOSE工作组的`JSON Web Token`、`JSON Web Signatures`和`JSON Web Encryption`规范。
* [osin](https://github.com/openshift/osin) ⭐ 1,934 | 🐛 3 | 🌐 Go | 📅 2026-04-15 :` Go`语言` OAuth2` 服务器库
* [loginsrv](https://github.com/tarent/loginsrv) ⭐ 1,930 | 🐛 27 | 🌐 Go | 📅 2021-02-27 :  JWT登录微服务,具有可插拔的后端,如`OAuth2 (Github)`、`htpasswd`、`OSIAM`。
* [gorbac](https://github.com/mikespook/gorbac) ⭐ 1,673 | 🐛 4 | 🌐 Go | 📅 2026-07-21 :   Golang中一个轻量级的基于角色的访问控制`（RBAC）`实现。
* [paseto](https://github.com/o1egl/paseto) ⭐ 941 | 🐛 7 | 🌐 Go | 📅 2023-02-25 :  平台无关的安全令牌`（PASETO)`的`Golang`实现。
* [jwt](https://github.com/cristalhq/jwt) ⭐ 689 | 🐛 2 | 🌐 Go | 📅 2025-06-22 : 针对go语言的 安全、简单、快速的JSON Web Tokens 。
* [go-guardian](https://github.com/shaj13/go-guardian) ⭐ 613 | 🐛 14 | 🌐 Go | 📅 2024-07-25 :  Go-Guardian支持以简洁又清晰的方式来进行`API`认证和`web`认证,认证模型支持`LDAP`、`Basic`、`Bearer token`和基于证书的认证
* [permissions2](https://github.com/xyproto/permissions2) ⭐ 509 | 🐛 1 | 🌐 Go | 📅 2026-08-03 :  用于跟踪用户、登录状态和权限的库,依赖安全`cookies`和`bcrypt`。
* [jwt](https://github.com/pascaldekloe/jwt) ⭐ 361 | 🐛 0 | 🌐 Go | 📅 2023-04-29 :  轻量级`JSON`网络令牌（`JWT`）库。
* [jeff](https://github.com/abraithwaite/jeff) ⭐ 270 | 🐛 2 | 🌐 Go | 📅 2025-01-23 :  简单、灵活、安全、习惯性的`Web`会话管理,支持可插拔的后端。
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) ⭐ 237 | 🐛 4 | 🌐 Go | 📅 2021-08-01 :  用于`Golang http`服务器的`JWT`中间件,有许多配置选项。
* [httpauth](https://github.com/goji/httpauth) ⭐ 223 | 🐛 5 | 🌐 Go | 📅 2021-09-28 : `HTTP`认证中间件
* [branca](https://github.com/hako/branca) ⭐ 175 | 🐛 0 | 🌐 Go | 📅 2020-08-07 : `Branca Tokens`的`Golang`实现。
* [sessionup](https://github.com/swithek/sessionup) ⭐ 132 | 🐛 3 | 🌐 Go | 📅 2025-03-20 :  简单而有效的`HTTP`会话管理和标识库。
* [sjwt](https://github.com/brianvoe/sjwt) ⭐ 123 | 🐛 1 | 🌐 Go | 📅 2025-11-10 :  - 简单的`jwt`生成器和解析器。
* [session](https://github.com/icza/session) ⭐ 119 | 🐛 4 | 🌐 Go | 📅 2024-08-24 : `Go` 语言会话管理(支持`Google App Engine - GAE`)
* [rbac](https://github.com/zpatrick/rbac) ⭐ 116 | 🐛 0 | 🌐 Go | 📅 2018-08-29 :  用于Go应用程序的极简`RBAC`库。
* [jwt](https://github.com/robbert229/jwt) ⚠️ Archived :  干净且易于使用的JSON网络令牌`JWT`的实现。
* [securecookie](https://github.com/chmike/securecookie) ⭐ 87 | 🐛 0 | 🌐 Go | 📅 2023-02-18 :   高效的安全`cookie`编码/解码库。
* [sessions](https://github.com/adam-hanna/sessions) ⭐ 80 | 🐛 3 | 🌐 Go | 📅 2023-07-17 :  为`Go`语言`HTTP` 服务器开发的非常简单的、高性能的、高可定制的会话服务
* [go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) ⭐ 79 | 🐛 0 | 🌐 Go | 📅 2025-01-26 : 用于支持电子邮件地址的规范表示的`Golang`库,。
* [otpgo](https://github.com/jltorresm/otpgo) ⭐ 77 | 🐛 2 | 🌐 Go | 📅 2021-02-27 : 基于时间的一次性密码`TOTP`和基于`HMAC` 的一次性密码`HOTP`库。
* [scope](https://github.com/SonicRoshan/scope) ⭐ 43 | 🐛 1 | 🌐 Go | 📅 2021-05-25 :   在`Go`中轻松管理`OAuth2`作用域。
* [cookiestxt](https://github.com/mengzhuo/cookiestxt) ⭐ 24 | 🐛 1 | 🌐 Go | 📅 2026-01-12 :   支持`cookies.txt` 文件格式的解析器。
* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2018-11-09 :   使用` SessionGate Redis`模块进行` Go`会话管理。

***

## 机器人相关

` 构建和使用机器人的库`

* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) ⭐ 6,401 | 🐛 174 | 🌐 Go | 📅 2024-08-14 :  简单干净的`Telegram`机器人客户端。
* [telebot](https://github.com/tucnak/telebot) ⭐ 4,631 | 🐛 65 | 🌐 Go | 📅 2026-06-16 :  用`Go`编写的`Telegram`机器人框架。
* [olivia](https://github.com/olivia-ai/olivia) ⚠️ Archived :  一个用人工神经网络构建的聊天机器人。
* [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) ⭐ 1,162 | 🐛 7 | 🌐 Go | 📅 2025-11-20 :` golang`实现的基于控制台的加密货币交易所交易机器人库
* [Kelp](https://github.com/stellar/kelp) ⚠️ Archived : `Stellar DEX`的官方交易机器人。开箱即用,用Golang编写,兼容中心化交易所和自定义交易策略。
* [go-chat-bot](https://github.com/go-chat-bot/bot) ⚠️ Archived :  用`Go` 编写的`IRC`、`Slack` 和`Telegram`机器人。
* [slacker](https://github.com/shomali11/slacker) ⭐ 802 | 🐛 0 | 🌐 Go | 📅 2023-11-23 :  用于创建`Slack`机器人的简单易用框架。
* [go-twitch-irc](https://github.com/gempir/go-twitch-irc) ⭐ 402 | 🐛 8 | 🌐 Go | 📅 2026-03-11 :  用于编写`twitch.tv`聊天机器人的库。
* [tbot](https://github.com/yanzay/tbot) ⭐ 357 | 🐛 5 | 🌐 Go | 📅 2023-12-19 : `Telegram`机器人服务器,其API类似于`net/http`。
* [go-sarah](https://github.com/oklahomer/go-sarah) ⭐ 272 | 🐛 0 | 🌐 Go | 📅 2026-08-09 :  为聊天服务如`LINE`、`Slack`、`Gitter` 等构建机器人的框架。
* [Tenyks](https://github.com/kyleterry/tenyks) ⭐ 176 | 🐛 1 | 🌐 Go | 📅 2026-03-19 :  使用`Redis` 和`JSON`进行消息传递的面向服务的` IRC`机器人。
* [hanu](https://github.com/sbstjn/hanu) ⭐ 157 | 🐛 3 | 🌐 Go | 📅 2023-04-21 :  用于编写`Slack`机器人的框架。
* [go-tgbot](https://github.com/olebedev/go-tgbot) ⭐ 120 | 🐛 2 | 🌐 Go | 📅 2018-06-25 : 由swagger文件、基于会话的路由器和中间件生成的纯`Golang`实现的`Telegram`机器人API封装。
* [ephemeral-roles](https://github.com/ewohltman/ephemeral-roles) ⭐ 98 | 🐛 6 | 🌐 Go | 📅 2026-08-09 :  根据语音频道成员是否出现来管理临时角色的机器人。
* [margelet](https://github.com/zhulik/margelet) ⭐ 85 | 🐛 2 | 🌐 Go | 📅 2022-09-16 :  用于构建`Telegram`机器人的框架。
* [slackscot](https://github.com/alexandre-normand/slackscot) ⭐ 57 | 🐛 3 | 🌐 Go | 📅 2023-02-25 : 构建`Slack`机器人的框架。
* [govkbot](https://github.com/nikepan/govkbot) ⭐ 51 | 🐛 1 | 🌐 Go | 📅 2023-10-31 :  简单的`Go VK`机器人库。
* [micha](https://github.com/onrik/micha) ⭐ 34 | 🐛 0 | 🌐 Go | 📅 2026-03-19 :  封装`Telegram`机器人api的`Go`库。
* [go-joe](https://joe-bot.net) :  受 Hubot 启发,用 Go 编写的通用型机器人库。

***

## 命令行工具

### 标准 CLI

`用于创建一个标准命令行应用程序的库`

* [cobra](https://github.com/spf13/cobra) ⭐ 44,442 | 🐛 431 | 🌐 Go | 📅 2026-07-11 :   一个现代化的命令行。
* [urfave/cli](https://github.com/urfave/cli) ⭐ 24,194 | 🐛 70 | 🌐 Go | 📅 2026-08-16 :   简单、快速、有趣的、用于构建 Go 语言命令行程序的软件包。
* [kingpin](https://github.com/alecthomas/kingpin) ⭐ 3,568 | 🐛 28 | 🌐 Go | 📅 2026-08-14 :  支持子命令的命令行和标志位解析器。
* [Dnote](https://github.com/dnote/dnote) ⭐ 3,054 | 🐛 40 | 🌐 Go | 📅 2026-07-25 :  支持多设备同步的命令行笔记工具。
* [pflag](https://github.com/spf13/pflag) ⭐ 2,760 | 🐛 136 | 🌐 Go | 📅 2026-08-09 :  Go flag软件包的替代品, 实现了`POSIX/GNU`风格的`flags`.
* [go-flags](https://github.com/jessevdk/go-flags) ⭐ 2,697 | 🐛 68 | 🌐 Go | 📅 2024-07-26 : `  GO`命令行选项解析器。
* [go-arg](https://github.com/alexflint/go-arg) ⭐ 2,269 | 🐛 34 | 🌐 Go | 📅 2025-12-27 :  `Go`中基于结构体的参数解析。
* [mitchellh/cli](https://github.com/mitchellh/cli) ⚠️ Archived :  用于实现命令行交互的 `Go `语言库
* [ops](https://github.com/nanovms/ops) ⭐ 1,510 | 🐛 143 | 🌐 Go | 📅 2026-08-02 : `Unikernel `编辑器和生成器
* [liner](https://github.com/peterh/liner) ⭐ 1,098 | 🐛 17 | 🌐 Go | 📅 2023-06-23 :  命令行文本解析器
* [complete](https://github.com/posener/complete) ⭐ 959 | 🐛 28 | 🌐 Go | 📅 2025-03-06 :  使用 `Go `语言编写的` bash` 命令补全工具以及`Go`命令补全工具
* [flaggy](https://github.com/integrii/flaggy) ⭐ 951 | 🐛 5 | 🌐 Go | 📅 2026-07-29 : 功能强大的`flag`包,具有出色的子命令支持。
* [mow.cli](https://github.com/jawher/mow.cli) ⭐ 884 | 🐛 34 | 🌐 Go | 📅 2024-03-07 :  用于构建命令行程序的工具库,支持更加精准的标记及选项解析和验证
* [cli](https://github.com/mkideal/cli) ⭐ 722 | 🐛 4 | 🌐 Go | 📅 2024-02-04 :   功能强大,使用简单的命令行软件库,基于`Golang `结构体`tag`实现
* [argparse](https://github.com/akamensky/argparse) ⭐ 640 | 🐛 10 | 🌐 Go | 📅 2022-10-31 :   受`Python`的`argparse`模块启发的命令行参数解析器。
* [1build](https://github.com/gopinath-langote/1build) ⭐ 249 | 🐛 30 | 🌐 Go | 📅 2026-05-11 :  管理项目专用命令的命令行工具。
* [wmenu](https://github.com/dixonwille/wmenu) ⭐ 231 | 🐛 3 | 🌐 Go | 📅 2024-11-25 :  为命令行程序提供简单的菜单结构选项来提供给用户来进行选择
* [climax](http://github.com/tucnak/climax) ⭐ 215 | 🐛 7 | 🌐 Go | 📅 2020-09-05 :    可以显示“人脸”的命令替代库。
* [clîr](https://github.com/leaanthony/clir) ⭐ 201 | 🐛 5 | 🌐 Go | 📅 2024-06-10 :  一个简单而清晰的`CLI`库,不需要其他依赖。
* [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) ⭐ 179 | 🐛 2 | 🌐 Go | 📅 2026-06-08 :  具有自动配置和依赖注入功能的 cli 应用程序框架。
* [commandeer](https://github.com/jaffee/commandeer) ⭐ 175 | 🐛 5 | 🌐 Go | 📅 2022-09-20 :  开发友好的`CLI`应用程序：基于结构字段和标签设置标志参数、默认值和用法。
* [sflags](https://github.com/octago/sflags) ⭐ 169 | 🐛 3 | 🌐 Go | 📅 2026-01-06 :   基于结构体的 `flag `生成器,支持`flag, urfave/cli, pflag, cobra, kingpin`等其他库
* [job](https://github.com/liujianping/job) ⭐ 150 | 🐛 1 | 🌐 Shell | 📅 2020-06-30 :  将你的短期命令转化为长期作业。
* [cmdr](https://github.com/hedzr/cmdr) ⭐ 141 | 🐛 0 | 🌐 Go | 📅 2026-08-07 :  一个`POSIX/GNU`风格,类似于`getopt`的命令行UI的Go库。
* [cli](https://github.com/teris-io/cli) ⭐ 132 | 🐛 2 | 🌐 Go | 📅 2021-05-09 :  一个功能丰富、易于使用的命令行工具包
* [flag](https://github.com/cosiner/flag) ⭐ 132 | 🐛 2 | 🌐 Go | 📅 2020-12-27 :   简单而强大的`Go`命令行选项解析库,支持子命令。
* [ukautz/clif](https://github.com/ukautz/clif) ⭐ 128 | 🐛 3 | 🌐 Go | 📅 2019-02-18 :   一个小型命令行程序开发框架
* [env](https://github.com/codingconcepts/env) ⭐ 125 | 🐛 2 | 🌐 Go | 📅 2024-06-18 : 基于`tag`的结构体环境配置。
* [gocmd](https://github.com/devfacet/gocmd) ⭐ 67 | 🐛 1 | 🌐 Go | 📅 2023-04-04 :   用于构建命令行应用程序的 `Go `库。
* [wlog](https://github.com/dixonwille/wlog) ⭐ 67 | 🐛 1 | 🌐 Go | 📅 2024-11-25 :  简单的日志接口,具有跨平台和并发支持等特性
* [strumt](https://github.com/antham/strumt) ⭐ 63 | 🐛 0 | 🌐 Go | 📅 2026-07-29 :  用于创建提示链的库。
* [go-getoptions](https://github.com/DavidGamba/go-getoptions) ⭐ 59 | 🐛 2 | 🌐 Go | 📅 2025-04-15 :  `Go` 选项解析器,灵感来自 `Perl `中灵活性的 `GetOpt::Long `。
* [flagvar](https://github.com/sgreben/flagvar) ⭐ 48 | 🐛 0 | 🌐 Go | 📅 2024-09-26 :  `Go`标准标志包的标志参数类型集合。
* [cmd](https://github.com/posener/cmd) ⭐ 47 | 🐛 1 | 🌐 Go | 📅 2020-09-27 :  扩展了标准`flag`包,具有支持子命令的特性
* [argv](https://github.com/cosiner/argv) ⭐ 43 | 🐛 0 | 🌐 Go | 📅 2020-04-16 :  用于分隔使用`bash`的语法的命令行字符串并将其作为参数的`Go `语言库,
* [go-commander](https://github.com/yitsushi/go-commander) ⚠️ Archived :  用于简化`CLI`工作流程的 `Go` 库。
* [sand](https://github.com/Zaba505/sand) ⭐ 29 | 🐛 0 | 🌐 Go | 📅 2018-11-21 :  用于创建解释器等工具的简单API库。
* [ts](https://github.com/liujianping/ts) ⭐ 22 | 🐛 0 | 🌐 Go | 📅 2019-07-02 :  时间戳转换和比较工具。

***

## 高级控制台UI

`用于构建控制台应用程序和控制台用户界面的库.`

* [termui](https://github.com/gizak/termui) ⭐ 13,582 | 🐛 106 | 🌐 Go | 📅 2025-07-10 :   基于 `termbox-go` 的 `Go` 终端仪表盘,灵感来源于[blessed-contrib](https://github.com/yaronn/blessed-contrib) ⭐ 15,766 | 🐛 97 | 🌐 JavaScript | 📅 2026-05-01 。
* [gocui](https://github.com/jroimartin/gocui) ⭐ 10,593 | 🐛 60 | 🌐 Go | 📅 2025-05-01 :  极简的控制台用户界面创建库.
* [pterm](https://github.com/pterm/pterm) ⭐ 5,517 | 🐛 83 | 🌐 Go | 📅 2026-07-11 :  在每个平台上美化控制台输出的库,有许多可组合的组件。
* [go-prompt](https://github.com/c-bata/go-prompt) ⭐ 5,489 | 🐛 114 | 🌐 Go | 📅 2025-08-12 :   受 [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) ⭐ 10,554 | 🐛 705 | 🌐 Python | 📅 2026-07-26  的启发，用于构建强大的交互式提示符的go语言库
* [termbox-go](https://github.com/nsf/termbox-go) ⭐ 4,787 | 🐛 50 | 🌐 Go | 📅 2026-06-23 :   Termbox是一个用于创建跨平台文本界面的库。
* [progressbar](https://github.com/schollz/progressbar) ⭐ 4,693 | 🐛 11 | 🌐 Go | 📅 2026-07-17 :   适用于各种操作系统的,线程安全进度条管理库。
* [asciigraph](https://github.com/guptarohit/asciigraph) ⭐ 3,085 | 🐛 4 | 🌐 Go | 📅 2026-06-21 :   没有其他依赖的可以在命令行应用中制作轻量级的`ASCII`行图┈┈╭╯的go语言工具包
* [termdash](https://github.com/mum4k/termdash) ⭐ 3,026 | 🐛 48 | 🌐 Go | 📅 2026-07-27 :   基于 `termbox-go `的 `Go` 终端仪表盘,灵感来自 [termui](https://github.com/gizak/termui) ⭐ 13,582 | 🐛 106 | 🌐 Go | 📅 2025-07-10 。
* [mpb](https://github.com/vbauerster/mpb) ⭐ 2,505 | 🐛 15 | 🌐 Go | 📅 2026-08-09 :  为命令行提供多个进度条的工具
* [uiprogress](https://github.com/gosuri/uiprogress) ⭐ 2,143 | 🐛 30 | 🌐 Go | 📅 2024-02-29 ：用于渲染进度条的库
* [uilive](https://github.com/gosuri/uilive) ⭐ 1,726 | 🐛 13 | 🌐 Go | 📅 2023-07-22 :  用于实时更新终端输出的库
* [gookit/color](https://github.com/gookit/color) ⭐ 1,602 | 🐛 2 | 🌐 Go | 📅 2026-06-04 :  格式化终端文本。
* [aurora](https://github.com/logrusorgru/aurora) ⭐ 1,494 | 🐛 2 | 🌐 Go | 📅 2025-01-07 :   `ANSI` 终端颜色,支持 `fmt.Printf/Sprintf`
* [go-isatty](https://github.com/mattn/go-isatty) ⭐ 923 | 🐛 0 | 🌐 Go | 📅 2026-07-23 :   `go`语言版本的`isatty`
* [go-colorable](https://github.com/mattn/go-colorable) ⭐ 811 | 🐛 7 | 🌐 Go | 📅 2026-05-29 : `Windows`上使用的可以输出彩色文本的库
* [uitable](https://github.com/gosuri/uitable) ⭐ 741 | 🐛 7 | 🌐 Go | 📅 2022-10-18 :  用于改善命令行中，表格数据可读性的库
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) ⭐ 594 | 🐛 15 | 🌐 Go | 📅 2026-07-23 ：多样的命令行文本
* [simpletable](https://github.com/alexeyco/simpletable) ⭐ 552 | 🐛 5 | 🌐 Go | 📅 2021-04-23 :   在终端中用`Go`实现简单的表格。
* [chalk](https://github.com/ttacon/chalk) ⭐ 472 | 🐛 2 | 🌐 Go | 📅 2019-08-28 :  符合直觉的用于美化命令行输出的库
* [yacspin](https://github.com/theckman/yacspin) ⭐ 456 | 🐛 6 | 🌐 Go | 📅 2022-01-03 : 用于终端的`CLi Spinner` 工具包。
* [tabby](https://github.com/cheynewallace/tabby) ⭐ 371 | 🐛 3 | 🌐 Go | 📅 2020-12-23 :   超级简单的`Golang`表格的库。
* [go-colortext](https://github.com/daviddengcn/go-colortext) ⭐ 217 | 🐛 3 | 🌐 Go | 📅 2020-03-29 : 用于在终端进行多彩文字输出的库
* [cfmt](https://github.com/mingrammer/cfmt) ⭐ 106 | 🐛 1 | 🌐 Go | 📅 2018-12-07 :   受`bootstrap`颜色类启发的上下文`fmt`。
* [tabular](https://github.com/InVisionApp/tabular) ⚠️ Archived :  从命令行工具中打印`ASCII`表格,而不需要向`API`传递大量数据集。
* [cfmt](https://github.com/i582/cfmt) ⭐ 69 | 🐛 1 | 🌐 Go | 📅 2021-07-01 :   简单方便的格式化风格化输出，与`fmt`库完全兼容
* [ctc](https://github.com/wzshiming/ctc) ⭐ 55 | 🐛 0 | 🌐 Go | 📅 2026-08-06 :  非侵入式的跨平台终端颜色库，不需要修改打印方法
* [table](https://github.com/tomlazar/table) ⭐ 52 | 🐛 1 | 🌐 Go | 📅 2023-05-19 :  基于终端颜色的表格库。
* [go-ataman](https://github.com/workanator/go-ataman) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2020-12-23 :   用于在终端中渲染` ANSI` 彩色文本模板的` Go` 库。
* [colourize](https://github.com/TreyBastian/colourize) :  支持终端输出带色彩的`ANSI`字符。

***

## 配置管理

`配置解析库`

* [viper](https://github.com/spf13/viper) ⭐ 30,427 | 🐛 132 | 🌐 Go | 📅 2026-01-12 :`Go`语言配置工具
* [godotenv](https://github.com/joho/godotenv) ⭐ 10,586 | 🐛 81 | 🌐 Go | 📅 2026-08-04 : 把 `Ruby`的 `dotenv `库移植到 `Go `（从 `.env `中加载环境变量）。
* [env](https://github.com/caarlos0/env) ⭐ 6,287 | 🐛 31 | 🌐 Go | 📅 2026-08-03 :   解析环境变量为` Go` 语言结构体
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) ⭐ 5,462 | 🐛 57 | 🌐 Go | 📅 2025-06-28 :  用于管理环境变量配置数据的` Go` 库。
* [koanf](https://github.com/knadh/koanf) ⭐ 4,159 | 🐛 4 | 🌐 Go | 📅 2026-08-09 :  轻量级、可扩展的库,用于读取Go应用程序中的配置。内置支持`JSON、TOML、YAML、env`、命令行。
* [ini](https://github.com/go-ini/ini) ⭐ 3,545 | 🐛 80 | 🌐 Go | 📅 2026-06-10 :  用于读写INI 文件的库
* [cleanenv](https://github.com/ilyakaznacheev/cleanenv) ⭐ 2,161 | 🐛 55 | 🌐 Go | 📅 2025-09-15 :   简约的配置读取器(从文件、`ENV`以及任何你想要的地方读取)。
* [konfig](https://github.com/lalamove/konfig) ⭐ 645 | 🐛 5 | 🌐 Go | 📅 2020-10-28 :  为分布式处理时代的`Go`提供可组合、可观察和可执行的配置处理。
* [aconfig](https://github.com/cristalhq/aconfig) ⭐ 639 | 🐛 19 | 🌐 Go | 📅 2025-11-28 :   简单、有用的配置加载器。
* [gookit/config](https://github.com/gookit/config) ⭐ 585 | 🐛 5 | 🌐 Go | 📅 2026-08-03 :  应用程序配置管理(`load,get,set`),支持`JSON、YAML、TOML、INI、HCL`
* [confita](https://github.com/heetch/confita) ⭐ 507 | 🐛 23 | 🌐 Go | 📅 2026-03-18 :  从多个后端级联加载配置到一个结构中。
* [fig](https://github.com/kkyr/fig) ⭐ 381 | 🐛 6 | 🌐 Go | 📅 2025-06-03 :   用于从文件和环境变量中读取配置的小型库（带有验证和默认值）。
* [config](https://github.com/golobby/config) ⭐ 366 | 🐛 2 | 🌐 Go | 📅 2023-01-05 :  一个轻量级但功能强大的`Go`项目配置包。
* [hjson](https://github.com/hjson/hjson-go) ⭐ 356 | 🐛 6 | 🌐 Go | 📅 2026-01-25 :  便于程序员使用和阅读的配置文件格式。具有更加轻松的语法,更少的错误和更多的注释
* [config](https://github.com/JeremyLoy/config) ⭐ 338 | 🐛 2 | 🌐 Go | 📅 2022-05-30 :  云端本地应用配置。只需两行就可以将ENV绑定到结构上
* [store](https://github.com/tucnak/store) ⭐ 273 | 🐛 4 | 🌐 Go | 📅 2023-07-14 : ` Go`的轻量级配置管理器,支持`JSON、TOML、YAML、properties`等。
* [config](https://github.com/olebedev/config) ⭐ 266 | 🐛 4 | 🌐 Go | 📅 2022-08-22 :   具有环境变量和标志解析功能的`JSON`或`YAML`配置包装器。
* [envconfig](https://github.com/vrischmann/envconfig) ⭐ 250 | 🐛 1 | 🌐 Go | 📅 2025-01-31 :  通过环境变量读取配置
* [joshbetz/config](https://github.com/joshbetz/config) ⭐ 213 | 🐛 0 | 🌐 Go | 📅 2021-11-12 :  消息配置库,可以解析环境变量、`JSON `文件并根据`SIGHUP`自动重新载入
* [gcfg](https://github.com/go-gcfg/gcfg) ⭐ 170 | 🐛 9 | 🌐 Go | 📅 2021-07-02 :  读取类似 `INI` 类型的配置文件为 `Go `语言结构体,支持自定义类型。
* [harvester](https://github.com/beatlabs/harvester) ⭐ 135 | 🐛 11 | 🌐 Go | 📅 2026-08-16 :   `Harvester,`一个易于使用的静态和动态配置包,支持 `envars` 和 `Consul` 集成。
* [onion](http://github.com/goraz/onion) ⭐ 119 | 🐛 10 | 🌐 Go | 📅 2023-03-07 :  基于分层结构的Go配置库,支持`JSON、TOML、YAML、properties、etcd、env`以及使用`PGP`加密。
* [configuration](https://github.com/BoRuDar/configuration) ⭐ 108 | 🐛 2 | 🌐 Go | 📅 2025-01-20 :  用于从环境变量、文件、标志和 "默认 "标签初始化配置结构的库。
* [envcfg](https://github.com/tomazk/envcfg) ⭐ 103 | 🐛 0 | 🌐 Go | 📅 2017-06-19 :  解析环境变量为 `Go` 语言结构体
* [envh](https://github.com/antham/envh) ⭐ 101 | 🐛 0 | 🌐 Go | 📅 2026-01-16 :  管理环境变量的助手
* [configuro](https://github.com/sherifabdlnaby/configuro) ⭐ 92 | 🐛 1 | 🌐 Go | 📅 2026-07-11 :  来自`ENV`和`Files`的意见性配置加载和验证框架,专注于`12-Factor`兼容应用程序。
* [hocon](https://github.com/gurkankaymak/hocon) ⭐ 92 | 🐛 1 | 🌐 Go | 📅 2026-07-25 :  用于使用`HOCON`(一种人类友好的JSON超集)格式的配置库,支持环境变量、引用其他值、注释和多文件等功能。
* [xdg](https://github.com/OpenPeeDeeP/xdg) ⭐ 80 | 🐛 2 | 🌐 Go | 📅 2020-10-19 :  遵守` XDG` 标准 的配置工具[XDG 标准](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html)
* [gofigure](https://github.com/ian-kent/gofigure) ⭐ 68 | 🐛 3 | 🌐 Go | 📅 2019-09-15 :  让` Go` 语言应用程序配置变得简单
* [go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) ⭐ 66 | 🐛 5 | 🌐 Go | 📅 2026-08-10 :   从` AWS System Manager - Parameter Store` 获取参数的` Go` 包。
* [configure](https://github.com/paked/configure) ⭐ 56 | 🐛 2 | 🌐 Go | 📅 2019-02-18 :  可以通过多种途径进行配置,包括 `JSON` 标记位以及环境变量
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) ⭐ 51 | 🐛 0 | 🌐 Go | 📅 2021-05-24 ： 模块化 JSON 配置工具。允许你将配置参数结构体和使用它的代码放在一起,而不需要让主配置文件了解所有子模块的细节来进行序列
* [genv](https://github.com/sakirsensoy/genv) ⭐ 45 | 🐛 0 | 🌐 Go | 📅 2026-01-27 :   通过 `dotenv` 支持轻松读取环境变量。
* [go-up](https://github.com/ufoscout/go-up) ⭐ 43 | 🐛 1 | 🌐 Go | 📅 2020-01-14 :  一个简单的配置库,具有递归占位符解析功能,没有各种怪招。
* [ingo](https://github.com/schachmat/ingo) ⭐ 39 | 🐛 0 | 🌐 Go | 📅 2017-04-03 :  将配置标记持久化到一个类似 `ini `的文件中
* [mini](https://github.com/sasbury/mini) ⭐ 37 | 🐛 1 | 🌐 Go | 📅 2018-12-26 :  用于解析类 `ini ` 文件的库
* [conflate](https://github.com/the4thamigo-uk/conflate) ⭐ 36 | 🐛 0 | 🌐 Go | 📅 2023-07-26 :  从任意URL合并多个`JSON/YAML/TOML`文件的库/工具,对`JSON`模式进行验证,并应用模式中定义的默认值。
* [go-ssm-config](https://github.com/ianlopshire/go-ssm-config) ⭐ 23 | 🐛 7 | 🌐 Go | 📅 2023-10-09 : 用于从 `AWS SSM`（参数存储）加载配置参数的 `Go `工具。
* [nasermirzaei89/env](https://github.com/nasermirzaei89/env) ⭐ 23 | 🐛 0 | 🌐 Go | 📅 2026-05-24 :  用于读取环境变量的简单实用包
* [go-ini](https://github.com/subpop/go-ini) ⭐ 18 | 🐛 1 | 🌐 Go | 📅 2026-07-22 :  Go 包,可对 INI 文件进行整理和解整理。
* [envconf](https://github.com/ian-kent/envconf) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2014-10-26 :  通过环境变量来配置
* [typenv](https://github.com/diegomarangoni/typenv) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2025-04-02 : 简约、零依赖、类型化的环境变量库。
* [swap](https://github.com/oblq/swap) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2025-04-04 :  基于构建环境,递归地实例化/配置结构解析库。
* [goConfig](https://github.com/crgimenes/goConfig) :   解析一个结构作为输入,并将命令行、环境变量和配置文件中的参数填充到该结构的字段中。

***

## 持续集成

`持续集成的辅助工具`

* [drone](https://github.com/drone/drone) ⭐ 37,964 | 🐛 105 | 🌐 Go | 📅 2026-08-14 : ` Drone` 是一个基于` Docker`的持续集成平台,使用 `Go `语言编写
* [CDS](https://github.com/ovh/cds) ⭐ 4,832 | 🐛 159 | 🌐 Go | 📅 2026-08-14 :  企业级`CI/CD`和`DevOps`自动化开源平台。
* [goveralls](https://github.com/mattn/goveralls) ⭐ 796 | 🐛 18 | 🌐 Go | 📅 2026-03-29 :  `Coveralls.io `是一个持续代码覆盖率检测系统,这个库提供了 `Go `语言的支持
* [overalls](https://github.com/go-playground/overalls) ⭐ 116 | 🐛 2 | 🌐 Go | 📅 2019-12-30 :  针对多`package` 的` Go` 语言项目,为 `Goveralls` 这样的工具生成覆盖率报告
* [duci](https://github.com/duck8823/duci) ⚠️ Archived :  简单的`ci`服务器,不需要特定领域的语言。
* [gomason](https://github.com/nikogura/gomason) ⭐ 69 | 🐛 3 | 🌐 Go | 📅 2026-02-10 :  从一个干净的工作空间测试、构建、签署和发布你的`go`二进制文件
* [roveralls](https://github.com/LawrenceWoodman/roveralls) ⭐ 22 | 🐛 0 | 🌐 Go | 📅 2017-11-19 :  回归覆盖测试工具

***

## CSS预处理

`预处理css文件的库`

* [gcss](https://github.com/yosssi/gcss) ⭐ 500 | 🐛 10 | 🌐 Go | 📅 2024-03-06 :  纯 `Go` 语言编写的 `CSS `预处理器
* [go-libsass](https://github.com/wellington/go-libsass) ⚠️ Archived :  100%兼容 `Sass` 的库 `libsass` 的` Go` 语言封装

***

## 数据结构

`go语言实现的数据结构与算法`

* [gods](https://github.com/emirpasic/gods) ⭐ 17,455 | 🐛 74 | 🌐 Go | 📅 2025-03-12 :` Go`语言数据结构、容器、集合、列表、栈、键值对、 `BidiMaps`、树、`HashSet`等
* [go-datastructures](https://github.com/Workiva/go-datastructures) ⭐ 7,948 | 🐛 29 | 🌐 Go | 📅 2026-07-31:一组有用的、高性能的、线程安全的数据结构
* [golang-set](https://github.com/deckarep/golang-set) ⭐ 4,699 | 🐛 23 | 🌐 Go | 📅 2026-06-27 :  线程安全和非线程安全的高性能集合
* [gota](https://github.com/kniren/gota) ⚠️ Archived :  为go语言实现了数据帧,序列以及数据噪音的方法
* [roaring](https://github.com/RoaringBitmap/roaring) ⭐ 2,917 | 🐛 72 | 🌐 Go | 📅 2026-08-15 :  实现了压缩`bitsets`算法的Go语言库
* [gocache](https://github.com/eko/gocache) ⭐ 2,881 | 🐛 39 | 🌐 Go | 📅 2026-07-26 :   完整的`Go`缓存库,支持多个存储（内存、`memcache、redis......`）。
* [willf/bloom](https://github.com/willf/bloom) ⭐ 2,804 | 🐛 19 | 🌐 Go | 📅 2026-07-10 :   实现了布隆过滤器的库
* [boomfilters](https://github.com/tylertreat/BoomFilters) ⭐ 1,645 | 🐛 13 | 🌐 Go | 📅 2025-11-17 ： 概率统计数据结构,用于处理大量连续的数据。
* [bitset](https://github.com/willf/bitset) ⭐ 1,511 | 🐛 0 | 🌐 Go | 📅 2026-08-13 :  实现了 `bitset `的 `Go `语言包.
* [ttlcache](https://github.com/ReneKroon/ttlcache) ⭐ 1,274 | 🐛 16 | 🌐 Go | 📅 2026-08-13 : 基于过期时间的内存字符串缓存接口。
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) ⭐ 1,233 | 🐛 15 | 🌐 Go | 📅 2024-07-15 : `Cuckoo`过滤器：一个用go语言实现的计数布隆过滤器的替代品
* [gostl](https://github.com/liyue201/gostl) ⭐ 1,138 | 🐛 7 | 🌐 Go | 📅 2025-08-28 :  数据结构和算法库,旨在提供类似于` C++ STL` 的功能。
* [hyperloglog](https://github.com/axiomhq/hyperloglog) ⭐ 1,046 | 🐛 7 | 🌐 Go | 📅 2026-07-24 : `HyperLogLog` 的go语言实现
* [algorithms](https://github.com/shady831213/algorithms) ⭐ 844 | 🐛 0 | 🌐 Go | 📅 2021-03-17 :  算法和数据结构学习资料
* [trie](https://github.com/derekparker/trie) ⭐ 790 | 🐛 13 | 🌐 Go | 📅 2026-07-30 :  `Go`语言实现的`Trie`树
* [deque](https://github.com/gammazero/deque) ⭐ 785 | 🐛 4 | 🌐 Go | 📅 2026-07-02 :  快速的环形缓冲区` deque`（双端队列）。
* [go-edlib](https://github.com/hbollon/go-edlib) ⭐ 604 | 🐛 0 | 🌐 Go | 📅 2026-02-05 :  与 Unicode 兼容的 Go 字符串比较和编辑距离算法库（`Levenshtein、LCS、Hamming、Damerau levenshtein、Jaro-Winkler` 等）。
* [merkletree](https://github.com/cbergoon/merkletree) ⭐ 539 | 🐛 0 | 🌐 Go | 📅 2026-08-14 :  实现了梅克尔树,提供了一种高效、安全的数据结构内容验证方法
* [levenshtein](https://github.com/agnivade/levenshtein) ⭐ 473 | 🐛 2 | 🌐 Go | 📅 2026-03-03 : 在Go中计算`levenshtein`距离的实现。
* [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) ⭐ 434 | 🐛 5 | 🌐 Go | 📅 2023-05-12 :  并发`FIFO`队列。
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) ⭐ 412 | 🐛 0 | 🌐 Go | 📅 2025-11-21 :   `Go `语言实现的自适应基数树
* [go-geoindex](https://github.com/hailocab/go-geoindex) ⭐ 360 | 🐛 2 | 🌐 Go | 📅 2018-02-20 :  基于内存存储的地理索引
* [mafsa](https://github.com/smartystreets/mafsa) ⚠️ Archived :   Go 语言实现的 `MA-FSA` ,包含最小完美哈希实现
* [skiplist](https://github.com/MauriceGit/skiplist) ⭐ 294 | 🐛 5 | 🌐 Go | 📅 2023-01-31 :  非常快的`Go Skipipllist`实现。
* [hilbert](https://github.com/google/hilbert) ⚠️ Archived :  用于映射空间填充曲线（例如希尔伯特曲线和皮亚诺曲线）和数值的库。
* [goskiplist](https://github.com/ryszard/goskiplist) ⭐ 239 | 🐛 6 | 🌐 Go | 📅 2019-10-29 :  `Go`语言实现的跳跃表
* [binpacker](https://github.com/zhuangsirui/binpacker) ⭐ 234 | 🐛 1 | 🌐 Go | 📅 2021-10-08 :  二进制数据封包拆包工具,帮你构建自定义的二进制数据流
* [deque](https://github.com/edwingeng/deque) ⭐ 205 | 🐛 0 | 🌐 Go | 📅 2023-09-14 :  高度优化的双端队列。
* [iter](https://github.com/disksing/iter) ⭐ 198 | 🐛 0 | 🌐 Go | 📅 2026-07-30 :  `C++ STL`迭代器和算法的Go实现。
* [bit](https://github.com/yourbasic/bit) ⭐ 167 | 🐛 1 | 🌐 Go | 📅 2022-12-29 : `Go`语言集合数据结构。提供了额外的位操作功能
* [bloom](https://github.com/zhenjl/bloom) ⭐ 147 | 🐛 1 | 🌐 Go | 📅 2018-04-16 : `Go `语言实现的布隆过滤器（`bloom filter`）
* [ring](https://github.com/TheTannerRyan/ring) ⭐ 145 | 🐛 1 | 🌐 Go | 📅 2020-09-10 :  高性能、线程安全的 `bloom `过滤器的 Go 实现。
* [remember-go](https://github.com/rocketlaunchr/remember-go) ⭐ 143 | 🐛 2 | 🌐 Go | 📅 2021-04-19 :  用于缓存慢速数据库查询的通用接口（由`redis、memcached、ristretto`或内存支持）。
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) ⭐ 141 | 🐛 1 | 🌐 Go | 📅 2022-06-22 :   区域四叉树,支持有效点位置和领域发现
* [encoding](https://github.com/zhenjl/encoding) ⭐ 133 | 🐛 6 | 🌐 Go | 📅 2017-12-23 :  整型压缩库
* [conjungo](https://github.com/InVisionApp/conjungo) ⚠️ Archived :  一个小巧、强大、灵活的合并库。
* [go-mcache](https://github.com/OrlovEvgeny/go-mcache) ⭐ 107 | 🐛 1 | 🌐 Go | 📅 2026-07-06 :  快速的内存`key:value`存储/缓存库。
* [cmap](https://github.com/lrita/cmap) ⭐ 104 | 🐛 0 | 🌐 Go | 📅 2026-04-16 :  一个用于`go`的线程安全的并发地图,支持使用`interface{}`作为键
* [crunch](https://github.com/superwhiskers/crunch) ⭐ 99 | 🐛 0 | 🌐 Go | 📅 2023-01-14 :  `Go`包,实现缓冲区,方便处理各种数据类型。
* [levenshtein](https://github.com/agext/levenshtein) ⭐ 92 | 🐛 1 | 🌐 Go | 📅 2020-10-15 :  编辑距离（`levenshtein distance`）和相似性度量计算库
* [bloom](https://github.com/yourbasic/bloom) ⭐ 88 | 🐛 0 | 🌐 Go | 📅 2017-06-19 :  `Go `语言实现的布隆过滤器
* [nan](https://github.com/kak-tus/nan) ⭐ 88 | 🐛 0 | 🌐 Go | 📅 2023-07-06 :   在一个库中实现了零分配的`Nullable`结构,并提供了方便的转换函数。
* [skiplist](https://github.com/gansidui/skiplist) ⭐ 83 | 🐛 0 | 🌐 Go | 📅 2014-11-21 :  在 `Go `中实现的` Skiplist`。
* [timedmap](https://github.com/zekroTJA/timedmap) ⭐ 75 | 🐛 0 | 🌐 Go | 📅 2024-05-05 :  具有过期键值对的`map`。
* [hide](https://github.com/emvi/hide) ⭐ 73 | 🐛 1 | 🌐 Go | 📅 2021-11-09 :具有hash 函数功能,以防止向客户端发送敏感ID\`。
* [count-min-log](https://github.com/seiflotfy/count-min-log) ⭐ 70 | 🐛 1 | 🌐 Go | 📅 2025-03-04 : `Go`语言实现的 `Count-Min-Log sketch `算法(类似 Count-Min sketch 算法,但是使用的内存更少)
* [concurrent-writer](https://github.com/free/concurrent-writer) ⭐ 62 | 🐛 0 | 🌐 Go | 📅 2017-11-17 :   `bufio.Writer`的高并发`drop-in`替代品
* [pipeline](https://github.com/hyfather/pipeline) ⭐ 60 | 🐛 1 | 🌐 Go | 📅 2021-11-02 :  一个带有扇形输入和扇形输出的管道的实现。
* [goset](https://github.com/zoumo/goset) ⭐ 53 | 🐛 0 | 🌐 Go | 📅 2020-12-11 : `Go`集合实现。
* [dict](https://github.com/srfrog/dict) ⭐ 48 | 🐛 0 | 🌐 Go | 📅 2026-02-14 :  `Go` 的类似`Python`的字典` (dict)`
* [ptrie](https://github.com/viant/ptrie) ⭐ 46 | 🐛 2 | 🌐 Go | 📅 2024-04-05 : 前缀树的实现
* [typ](https://github.com/gurukami/typ) ⭐ 45 | 🐛 0 | 🌐 Go | 📅 2021-10-15 :  空类型安全的基础类型转换器和从复杂结构中取值的开发库。
* [go-ef](https://github.com/amallia/go-ef) ⭐ 42 | 🐛 2 | 🌐 Go | 📅 2024-06-16 :   `Elias-Fano`编码的`Go`实现。
* [null](https://github.com/emvi/null) ⭐ 40 | 🐛 0 | 🌐 Go | 📅 2021-11-09 :  可为`null`的`Go`类型,它们可以被\`marshalled/unmarshalled到JSON。
* [set](https://github.com/StudioSol/set) ⭐ 30 | 🐛 1 | 🌐 Go | 📅 2025-10-02 :  在 `Go `中使用 `LinkedHashMap `实现简单的集合数据结构。
* [mspm](https://github.com/BlackRabbitt/mspm) ⭐ 29 | 🐛 0 | 🌐 Go | 📅 2018-05-19 :  用于信息检索的多字符串模式匹配算法。
* [gofal](https://github.com/xxjwxc/gofal) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2019-10-08 :  `Go`的微分算法库。
* [goterator](https://github.com/yaa110/goterator) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2025-10-15 :   迭代器的实现,提供映射和减少功能。
* [slices](https://github.com/srfrog/slices) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2025-11-02 :   `slice`操作函数
* [parsefields](https://github.com/MonaxGT/parsefields) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2019-05-05 :  - 用于解析`JSON`类日志的工具,用于收集特殊字段和特定事件。
* [treap](https://github.com/perdata/treap) :  使用树堆的持久化快速有序`map`

***

## 数据库

`go语言实现的数据库`

* [prometheus](https://github.com/prometheus/prometheus) ⭐ 65,718 | 🐛 896 | 🌐 Go | 📅 2026-08-15 :  监控系统及时间序列数据库
* [tidb](https://github.com/pingcap/tidb) ⭐ 40,436 | 🐛 6,784 | 🌐 Go | 📅 2026-08-16 : ` TiDB` 是一个分布式的` SQL` 数据库。受到了` Google F1`的启发
* [cockroach](https://github.com/cockroachdb/cockroach) ⭐ 32,393 | 🐛 8,206 | 🌐 Go | 📅 2026-08-07 :  可扩展的、一致的事务型数据库
* [influxdb](https://github.com/influxdb/influxdb) ⭐ 31,702 | 🐛 2,148 | 🌐 Rust | 📅 2026-08-14 :  用于度量、事件和实时分析的可扩展数据存储。
* [dgraph](https://github.com/dgraph-io/dgraph) ⭐ 21,773 | 🐛 94 | 🌐 Go | 📅 2026-08-16 :  可扩展的、分布式的、低延时、高吞吐的图数据库
* [rqlite](https://github.com/rqlite/rqlite) ⭐ 17,686 | 🐛 81 | 🌐 Go | 📅 2026-08-10 :  基于 `SQLite `的轻量级的、分布式的关系型数据库
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) ⭐ 17,545 | 🐛 774 | 🌐 Go | 📅 2026-08-15 :  快速、资源高效、可扩展的开源时间序列数据库。可作为`Prometheus`的长期远程存储。支持`PromQL`。
* [badger](https://github.com/dgraph-io/badger) ⭐ 15,751 | 🐛 69 | 🌐 Go | 📅 2026-08-13 : `Go`中的快速键值存储库。
* [groupcache](https://github.com/golang/groupcache) ⭐ 13,333 | 🐛 45 | 🌐 Go | 📅 2024-11-29 :  `Groupcache`是一个缓存及缓存填充库,在很多情况下用于替代 `memcached`.
* [bbolt](https://github.com/etcd-io/bbolt) ⭐ 9,686 | 🐛 28 | 🌐 Go | 📅 2026-08-14 :  `Go`的嵌入式键值数据库。
* [immudb](https://github.com/codenotary/immudb) ⭐ 9,022 | 🐛 103 | 🌐 Go | 📅 2026-08-03 :  `immudb `是一个轻量级、高速的不可变数据库,适用于用`Go`编写的系统和应用程序。
* [go-cache](https://github.com/pmylund/go-cache) ⭐ 8,843 | 🐛 76 | 🌐 Go | 📅 2023-11-20 :   基于内存存储的缓存,适用于分布式部署的应用
* [BigCache](https://github.com/allegro/bigcache) ⭐ 8,147 | 🐛 92 | 🌐 Go | 📅 2026-08-14 :  为GB量级数据设计的高效键/值缓存
* [goleveldb](https://github.com/syndtr/goleveldb) ⭐ 6,322 | 🐛 111 | 🌐 Go | 📅 2024-05-14 :  `Go`中[LevelDB](https://github.com/google/leveldb) ⭐ 39,327 | 🐛 400 | 🌐 C++ | 📅 2026-03-11键/值数据库的实现
* [rosedb](https://github.com/roseduan/rosedb) ⭐ 4,883 | 🐛 7 | 🌐 Go | 📅 2026-02-10 : 一个基于 LSM+WAL 的内嵌 k-v数据库，支持多种数据结构，如字符串、列表、哈希表、集合、有序集合
* [buntdb](https://github.com/tidwall/buntdb) ⭐ 4,862 | 🐛 32 | 🌐 Go | 📅 2026-05-19 :  快速,可嵌入的,内存键值数据库,可定义索引及 `spatial`
* [ledisdb](https://github.com/siddontang/ledisdb) ⭐ 4,115 | 🐛 1 | 🌐 Go | 📅 2023-10-22 :  `Ledisdb `是一个高性能 `NoSQL` 数据库,类似 `Redis`
* [nutsdb](https://github.com/xujiajun/nutsdb) ⭐ 3,577 | 🐛 49 | 🌐 Go | 📅 2026-08-09 :  `Nutsdb`是一个用纯`Go`编写的简单、快速、可嵌入、持久化的键/值存储。它支持完全可序列化的事务和许多数据结构,如列表、集合、排序集合。
* [GCache](https://github.com/bluele/gcache) ⭐ 2,729 | 🐛 30 | 🌐 Go | 📅 2024-03-01 :  支持缓存过期、 `LFU、 LRU `和 `ARC `的缓存库
* [tiedot](https://github.com/HouzuoGuo/tiedot) ⭐ 2,726 | 🐛 27 | 🌐 Go | 📅 2021-09-05 :  基于`Go`语言的` NoSQ`L 数据库
* [fastcache](https://github.com/VictoriaMetrics/fastcache) ⭐ 2,370 | 🐛 48 | 🌐 Go | 📅 2026-06-15 :  针对大量条目的快速线程安全内存缓存。将`GC`开销降到最低。
* [cache2go](https://github.com/muesli/cache2go) ⭐ 2,150 | 🐛 35 | 🌐 Go | 📅 2024-07-02 :  基于内存存储的键值缓存,支持自动基于超时的自动失效
* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) ⭐ 1,527 | 🐛 36 | 🌐 Go | 📅 2023-02-25 :  `CovenantSQL`是一个区块链上的SQL数据库。
* [Databunker](https://github.com/paranoidguy/databunker) ⭐ 1,481 | 🐛 4 | 🌐 Go | 📅 2026-07-28 :  为符合`GDPR`和`CCPA`而构建的个人身份信息`PII`存储服务。
* [diskv](https://github.com/peterbourgon/diskv) ⭐ 1,455 | 🐛 8 | 🌐 Go | 📅 2021-11-10 :   具有 `disk-backed` 功能的持久化键值存储
* [pogreb](https://github.com/akrylysov/pogreb) ⭐ 1,351 | 🐛 15 | 🌐 Go | 📅 2026-04-06 :  嵌入式键值存储,适用于重读工作负载。
* [eliasdb](https://github.com/krotik/eliasdb) ⭐ 1,035 | 🐛 14 | 🌐 Go | 📅 2022-08-14 :  无依赖、事物型图数据库,支持 `REST API`、短语搜索以及类` SQL` 的查询语言
* [moss](https://github.com/couchbase/moss) ⭐ 1,015 | 🐛 46 | 🌐 Go | 📅 2026-07-23 :  ` Moss` 是一个简单的 `LSM `键值存储引擎,100% Go 语言实现
* [levigo](https://github.com/jmhodges/levigo) ⭐ 421 | 🐛 6 | 🌐 Go | 📅 2022-03-07 :  `LeviGo`是 `LevelDB`的 `Go `语言封装
* [pudge](https://github.com/recoilme/pudge) ⭐ 369 | 🐛 0 | 🌐 Go | 📅 2021-07-04 :   使用 `Go` 的标准库编写的快速、简单的键值存储。
* [Kivik](https://github.com/go-kivik/kivik) ⭐ 344 | 🐛 36 | 🌐 Go | 📅 2026-03-10 :  `Kivik`为`CouchDB、PouchDB`和类似的数据库提供了一个通用的`Go`和`GopherJS`客户端库。
* [Vasto](https://github.com/chrislusf/vasto) ⭐ 261 | 🐛 4 | 🌐 Go | 📅 2019-03-07 :   一个分布式高性能键值存储。在磁盘上。最终一致。HA。能够在不中断服务的情况下增长或收缩。
* [piladb](https://github.com/fern4lvarez/piladb) ⭐ 206 | 🐛 10 | 🌐 Go | 📅 2025-12-05 :  轻量级 `RESTful` 数据库引擎,基于堆栈结构
* [cache](https://github.com/akyoto/cache) ⚠️ Archived :   内存中的`key:value`存储,有过期时间,0依赖,<100 LoC,100%覆盖。
* [Scribble](https://github.com/nanobox-io/golang-scribble) ⭐ 176 | 🐛 1 | 🌐 Go | 📅 2019-03-09 :  小巧的 `JSON` 文件存储
* [bcache](https://github.com/iwanbk/bcache) ⭐ 165 | 🐛 4 | 🌐 Go | 📅 2023-01-13 :  最终一致的分布式内存缓存`Go`库。
* [unitdb](https://github.com/unit-io/unitdb) ⭐ 123 | 🐛 2 | 🌐 Go | 📅 2023-03-07 :  用于物联网、实时消息应用的快速时序数据库。
* [slowpoke](https://github.com/recoilme/slowpoke) ⚠️ Archived :   具有持久性的键值存储。
* [couchcache](https://github.com/codingsince1985/couchcache) ⭐ 63 | 🐛 1 | 🌐 Go | 📅 2024-06-16 :  `RESTful` 缓存微服务,基于`Couchbase`数据库
* [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) ⭐ 45 | 🐛 2 | 🌐 Go | 📅 2018-01-22 :  `BigCache`支持集群和单个项目过期。
* [Coffer](https://github.com/claygod/coffer) ⭐ 41 | 🐛 1 | 🌐 Go | 📅 2026-01-23 :   简单的`ACID`键值数据库,支持事务。
* [Bitcask](https://github.com/prologic/bitcask) ⭐ 33 | 🐛 0 | 📅 2023-11-04 :   `Bitcask` 是一个用纯 Go 编写的可嵌入的、持久的、快速的键值（KV）数据库,由于采用了 `bitcask` 盘上布局（LSM+WAL）,它具有可预测的读/写性能、低延迟和高吞吐量。
* [tempdb](https://github.com/rafaeljesus/tempdb) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2018-02-14 :  临时数据的键值对存储

#### 数据库迁移工具

* [migrate](https://github.com/golang-migrate/migrate) ⭐ 18,820 | 🐛 486 | 🌐 Go | 📅 2026-07-05 :   数据库迁移。命令行及 `Go `语言库
* [goose](https://github.com/pressly/goose) ⭐ 11,333 | 🐛 137 | 🌐 Go | 📅 2026-08-08 :   数据库迁移工具。你可以通过编写增量 `SQL `或 `Go` 语言脚本来管理你的数据库
* [sql-migrate](https://github.com/rubenv/sql-migrate) ⭐ 3,417 | 🐛 97 | 🌐 Go | 📅 2026-07-14 :  数据库迁移工具,允许利用 `Go-bindata` 将数据库迁移嵌入应用程序
* [soda](https://github.com/gobuffalo/pop/tree/master/soda) ⭐ 1,514 | 🐛 93 | 🌐 Go | 📅 2026-07-29 : 数据库迁移、创建、 ORM等等,用于`MySQL, PostgreSQL,`以及 `SQLite`.
* [skeema](https://github.com/skeema/skeema) ⭐ 1,375 | 🐛 15 | 🌐 Go | 📅 2026-08-12 :  `MySQL`的纯SQL模式管理系统,支持`sharding`和外部在线模式变更工具
* [gormigrate](https://github.com/go-gormigrate/gormigrate) ⭐ 1,172 | 🐛 17 | 🌐 Go | 📅 2026-05-26 :   数据库模式迁移帮助工具,用于` Gorm ORM.`
* [migrator](https://github.com/lopezator/migrator) ⭐ 176 | 🐛 11 | 🌐 Go | 📅 2024-03-14 :  简单的`Go`数据库迁移库。
* [darwin](https://github.com/GuiaBolso/darwin) ⭐ 150 | 🐛 5 | 🌐 Go | 📅 2023-02-24 :  数据库模式增量库
* [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) ⭐ 87 | 🐛 5 | 🌐 Go | 📅 2025-11-20 :  帮助使用 `go-pg/pg `编写迁移的` Go` 包。
* [avro](https://github.com/khezen/avro) ⭐ 49 | 🐛 0 | 🌐 Go | 📅 2024-11-27 :  发现`SQL`模式并将其转换为`AVRO`模式。查询`SQL`记录到`AVRO`字节。
* [schema](https://github.com/adlio/schema) ⭐ 44 | 🐛 0 | 🌐 Go | 📅 2026-07-04 :   在你的Go二进制文件中嵌入数据库/sql兼容数据库的模式迁移库。
* [go-fixtures](https://github.com/RichardKnop/go-fixtures) ⭐ 32 | 🐛 0 | 🌐 Go | 📅 2019-12-26 : 类似` DjanGo fixtures`,用于 Golang 的內建`dababase/sql` 库
* [pravasan](https://github.com/pravasan/pravasan) ⭐ 30 | 🐛 30 | 🌐 HTML | 📅 2018-12-20 :   简单的迁移工具,目前支持 `MySQL `但是近期打算支持` Postgres, SQLite, MonGoDB` 等等
* [gondolier](https://github.com/emvi/gondolier) ⚠️ Archived :   使用`struct`装饰器的数据库迁移库。

### 数据库工具

* [vitess](https://github.com/youtube/vitess) ⭐ 21,224 | 🐛 1,082 | 🌐 Go | 📅 2026-08-15 :  `vitess` 提供了能够使大型 `web `服务 `MySQL` 数据库的扩展变得更加容易的服务器及工具
* [pgweb](https://github.com/sosedoff/pgweb) ⭐ 9,478 | 🐛 55 | 🌐 Go | 📅 2026-07-26 :  基于 `Web` 的 `PostgreSQL` 数据库浏览工具
* [kingshard](https://github.com/flike/kingshard) ⭐ 6,400 | 🐛 160 | 🌐 Go | 📅 2026-06-05 :  `kingshard`是一个`Go`语言编写的高性能 `MySQL `数据库代理
* [orchestrator](https://github.com/github/orchestrator) ⚠️ Archived : ` MySQL`复制拓扑管理器及可视化工具
* [go-mysql](https://github.com/siddontang/go-mysql) ⭐ 4,964 | 🐛 155 | 🌐 Go | 📅 2026-08-14 :   用于处理` MySQL` 协议及复制的`Go`语言工具集
* [pREST](https://github.com/nuveo/prest) ⭐ 4,609 | 🐛 151 | 🌐 Go | 📅 2026-08-14 :  为 `PostgreSQL `数据库提供 `RESTful API`
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) ⭐ 4,147 | 🐛 219 | 🌐 Go | 📅 2023-10-22 :  将你的 `MySQL` 数据自动同步到` Elasticsearch`
* [chproxy](https://github.com/Vertamedia/chproxy) ⭐ 1,478 | 🐛 90 | 🌐 Go | 📅 2026-04-15 : ` HTTP`代理的`ClickHouse`数据库。
* [pg\_timetable](https://github.com/cybertec-postgresql/pg_timetable) ⭐ 1,395 | 🐛 0 | 🌐 Go | 📅 2026-08-07 : `PostgreSQL` 的高级调度。
* [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) ⭐ 512 | 🐛 25 | 🌐 Go | 📅 2026-08-04 :   收集小的插入请求后一并发送大的请求到`ClickHouse`服务器。
* [octillery](https://github.com/knocknote/octillery) ⭐ 202 | 🐛 6 | 🌐 Go | 📅 2023-11-05 :   用于`sharding`数据库的`Go`包（支持所有ORM或原始SQL）。
* [myreplication](https://github.com/2tvenom/myreplication) ⭐ 193 | 🐛 5 | 🌐 Go | 📅 2018-10-05 :  ` MySql` 二进制 `log` 复制监听器,支持基于语句和基于行的复制
* [dbbench](https://github.com/sj14/dbbench) ⭐ 118 | 🐛 9 | 🌐 Go | 📅 2026-08-05 :  数据库基准测试工具,支持多个数据库和脚本。
* [datagen](https://github.com/codingconcepts/datagen) ⚠️ Archived :  快速的数据生成器,支持多表并支持多行`DML`
* [prep](https://github.com/hexdigest/prep) ⭐ 36 | 🐛 0 | 🌐 Go | 📅 2017-12-19 :    无需更改代码使用已准备好的` SQL` 语句的库
* [rwdb](https://github.com/andizzle/rwdb) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2017-11-08 :   `rwdb`为多个数据库服务器的设置提供读取复制功能。
* [bucket](https://github.com/PumpkinSeed/bucket) ⚠️ Archived :  为`Couchbase`优化的数据结构框架,专门针对`bucket`的使用进行了优化。

### SQL 查询语句构建库

* [Squirrel](https://github.com/Masterminds/squirrel) ⭐ 7,977 | 🐛 96 | 🌐 Go | 📅 2024-04-24 :  一个帮助你构建 `SQL` 查询的库
* [xo](https://github.com/knq/xo) ⭐ 3,895 | 🐛 67 | 🌐 Go | 📅 2026-08-04 :  基于已知的数据库表或自定义查询生成地道的`Go`语言代码,支持 `PostgreSQL, MySQL, SQLite, Oracle`, 以及 `Microsoft SQL Server`.
* [jet](https://github.com/go-jet/jet) ⭐ 3,778 | 🐛 43 | 🌐 Go | 📅 2026-06-22 :  在`Go`中编写类型安全的`SQL`查询框架,能够轻松地将数据库查询结果转换为所需的任意对象结构。
* [goqu](https://github.com/doug-martin/goqu) ⭐ 2,671 | 🐛 144 | 🌐 Go | 📅 2024-05-22 :  地道的 `SQL` 语句创建器和查询库
* [gendry](https://github.com/didi/gendry) ⚠️ Archived :  非侵入式`SQL`构建器和强大的数据绑定器。
* [Dotsql](https://github.com/gchaincl/dotsql) ⭐ 740 | 🐛 8 | 🌐 Go | 📅 2023-11-24 :  `Go`语言库,帮助你将 `sql` 文件保存在一个地方并且方便的取用
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) ⭐ 671 | 🐛 23 | 🌐 Go | 📅 2026-07-12 :  强大的数据检索方法以及与`DB`无关的查询构建能力。
* [sqlingo](https://github.com/lqs/sqlingo) ⭐ 454 | 🐛 5 | 🌐 Go | 📅 2026-04-01 :  在` Go` 中构建 `SQL` 的轻量级 `DSL`。
* [dbq](https://github.com/rocketlaunchr/dbq) ⭐ 416 | 🐛 1 | 🌐 Go | 📅 2021-02-22 :  `Go`的数据库操作库。
* [sqrl](https://github.com/elgris/sqrl) ⭐ 286 | 🐛 8 | 🌐 Go | 📅 2023-06-15 :  `SQL `查询创建器,是 `Squirrel` 的一个分叉版本,进行了性能方面的优化
* [sq](https://github.com/bokwoon95/go-structured-query) ⭐ 201 | 🐛 2 | 🌐 Go | 📅 2023-01-15 :  适用于`Go`的类型安全`SQL`构建器和结构映射器。
* [sqlf](https://github.com/leporo/sqlf) ⭐ 189 | 🐛 1 | 🌐 Go | 📅 2025-02-24 :  快速的`SQL`查询构建器。
* [buildsqlx](https://github.com/arthurkushman/buildsqlx) ⭐ 188 | 🐛 8 | 🌐 Go | 📅 2026-06-21 :  针对`PostgreSQL`的`Go`数据库查询构建库。
* [igor](https://github.com/galeone/igor) ⭐ 128 | 🐛 0 | 🌐 Go | 📅 2024-04-14 :   `PostgreSQL` 的抽象层,支持高级功能以及类` Gorm` 的语法
* [godbal](https://github.com/xujiajun/godbal) ⭐ 60 | 🐛 0 | 🌐 Go | 📅 2019-01-30 :  Go的数据库抽象层（`dbal`）。支持`SQL`构建器,并能轻松获得数据库结果。
* [gosql](https://github.com/twharmon/gosql) ⭐ 37 | 🐛 0 | 🌐 Go | 📅 2022-04-12 :  具有更好的空值支持的SQL查询生成器。
* [qry](https://github.com/HnH/qry) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2024-02-20 :  从带有原始`SQL`查询的文件中生成常量的工具。
* [ormlite](https://github.com/pupizoid/ormlite) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2023-01-30 :   轻量级软件包,包含一些类似于`ORM`的功能,以及针对`sqlite`数据库的帮助程序。
* [mpath](https://github.com/spacetab-io/mpath-go) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2020-01-13 :  用于 `SQL `记录的` MPTT (Modified Preorder Tree Traversal)`  包 - 实物化路径的实现
* [Squalus](https://gitlab.com/qosenergy/squalus) : ` Go SQL`包的薄层,使其更容易执行查询。

***

## 数据库驱动

`连接和操作数据库工具`

* 关系型数据库
  * [avatica](https://github.com/apache/calcite-avatica-go) ⭐ 126 | 🐛 1 | 🌐 Go | 📅 2026-06-01`Apache Phoenix/Avatica SQL `驱动
  * [bgc](https://github.com/viant/bgc) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2024-03-17 :  数据库连接工具包,用于通过 `Go `语言访问` BigQuery`
  * [firebirdsql](https://github.com/nakagami/firebirdsql) ⭐ 266 | 🐛 1 | 🌐 Go | 📅 2026-08-06 :  `Firebird RDBMS SQL `驱动
  * [go-adodb](https://github.com/mattn/go-adodb) ⭐ 154 | 🐛 18 | 🌐 Go | 📅 2026-07-10 :  `Microsoft ActiveX `对象数据库驱动
  * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) ⭐ 1,883 | 🐛 177 | 🌐 Go | 📅 2025-04-26 :  适用于Go的`Microsoft MSSQL`驱动。
  * [go-oci8](https://github.com/mattn/go-oci8) ⭐ 631 | 🐛 3 | 🌐 Go | 📅 2026-07-08 : `Oracle`驱动
  * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) ⭐ 15,266 | 🐛 72 | 🌐 Go | 📅 2026-08-14 :  Go 语言 `MySQL`驱动
  * [go-sqlite3](https://github.com/mattn/go-sqlite3) ⭐ 9,206 | 🐛 159 | 🌐 C | 📅 2026-07-30 :  Go 语言的 `SQLite3 `驱动
  * [gofreetds](https://github.com/minus5/gofreetds) ⭐ 114 | 🐛 18 | 🌐 Go | 📅 2020-11-30 :  `Microsoft MSSQL `驱动。 `FreeTDS`的go语言封装
  * [FreeTDS](http://www.freetds.org) :  `Microsoft MSSQL`驱动。是FreeTDS的Go封装器。
  * [goracle](https://github.com/go-goracle/goracle) ⚠️ Archived :  用于 `Go `的 `Oracle `驱动程序,使用 `ODPI-C` 驱动程序。
  * [pgx](https://github.com/jackc/pgx) ⭐ 14,145 | 🐛 253 | 🌐 Go | 📅 2026-08-16 :  `PostgreSQL` 驱动,支持比 `database/sql `更多的特性
  * [pq](https://github.com/lib/pq) ⭐ 9,921 | 🐛 49 | 🌐 Go | 📅 2026-08-16 :  用于`database/sql`的`Pure Go Postgres`驱动。
  * [Sqinn-Go](https://github.com/cvilsmeier/sqinn-go) ⭐ 538 | 🐛 0 | 🌐 Go | 📅 2026-07-05 :  纯Go的`SQLite`驱动。

***

* NoSQL数据库
  * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) ⭐ 459 | 🐛 44 | 🌐 Go | 📅 2026-08-14 :   `Go`语言的`Aerospike`客户端。
  * [arangolite](https://github.com/solher/arangolite) ⭐ 72 | 🐛 5 | 🌐 Go | 📅 2021-03-10 :   `ArangoDB`的轻量级`golang`驱动
  * [asc](https://github.com/viant/asc) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2024-09-20 :  用于`Aerospike for go`的数据存储连接。
  * [dynago](https://github.com/underarmour/dynago) :  `Dynago` 是 `DynamoDB` 的客户端。
  * [forestdb](https://github.com/couchbase/goforestdb) ⭐ 36 | 🐛 7 | 🌐 Go | 📅 2016-12-15 :  `ForestDB`的`Go`语言封装
  * [go-couchbase](https://github.com/couchbase/go-couchbase) ⭐ 323 | 🐛 40 | 🌐 Go | 📅 2025-08-25 :`Go`语言`Couchbase`客户端
  * [go-pilosa](https://github.com/pilosa/go-pilosa) ⚠️ Archived :  用于Pilosa的Go客户端库。
  * [go-rejson](https://github.com/nitishm/go-rejson) ⭐ 338 | 🐛 17 | 🌐 Go | 📅 2024-01-17 : `Redislabs` 的 `ReJSON `模块的 `Golang` 客户端,使用 `Redigo golang `客户端。在`redis`中轻松地将结构体作为`JSON`对象进行存储和操作。
  * [gocb](https://github.com/couchbase/gocb) ⭐ 377 | 🐛 1 | 🌐 Go | 📅 2026-08-10 :  `Couchbase Go`官方SDK。
  * [gocql](http://gocql.github.io) :  `Apache Cassandra` 的 Go 语言驱动
  * [godis](https://github.com/piaohao/godis) ⭐ 112 | 🐛 0 | 🌐 Go | 📅 2020-05-12 :  由 `golang` 实现的` redis` 客户端,灵感来自 `jedis`。
  * [godscache](https://github.com/defcronyke/godscache) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2019-02-08 :  `Google Cloud Platform Go Datastore`包的封装器,使用memcached增加缓存。
  * [gomemcache](https://github.com/bradfitz/gomemcache/) ⭐ 1,881 | 🐛 49 | 🌐 Go | 📅 2026-07-12 :  `Go`编程语言的`memcache`客户端库。
  * [gorethink](https://github.com/dancannon/gorethink) ⭐ 1,645 | 🐛 27 | 🌐 Go | 📅 2025-10-24 :  `RethinkDB`的Go语言驱动。
  * [goriak](https://github.com/zegl/goriak) ⭐ 30 | 🐛 4 | 🌐 Go | 📅 2021-09-15 :  `Riak KV` 的 `Go `语言驱动
  * [mgm](https://github.com/kamva/mgm) ⭐ 764 | 🐛 17 | 🌐 Go | 📅 2026-08-03 :  用于 `Go` 的基于` MongoDB` 模型的` ODM`（基于官方 MongoDB 驱动程序）
  * [mgo](https://github.com/globalsign/mgo) ⭐ 1,960 | 🐛 64 | 🌐 Go | 📅 2021-10-29 :`  MonGoDB` 驱动,通过简单的 `API` 现了丰富的、经过测试的特性,这些 API 遵循 Go 语言的习惯
  * [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) ⭐ 8,535 | 🐛 16 | 🌐 Go | 📅 2026-08-14 :   `Go`语言的官方`MongoDB`驱动。
  * [neo4j](https://github.com/cihangir/neo4j) ⭐ 29 | 🐛 8 | 🌐 Go | 📅 2015-04-02 :  `Neo4j Rest API`的 `Go` 语言接口
  * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) ⚠️ Archived : ` Go` 语言实现的 `Neo4j REST `客户端
  * [neoism](https://github.com/jmcvetta/neoism) ⭐ 388 | 🐛 12 | 🌐 Go | 📅 2020-02-16 : `Go` 语言 `Neo4j` 客户端
  * [qmgo](https://github.com/qiniu/qmgo) ⭐ 1,356 | 🐛 52 | 🌐 Go | 📅 2026-06-20 :  Go的`MongoDB`驱动。它基于官方的`MongoDB`驱动,但和Mgo一样更容易使用。
  * [redeo](https://github.com/bsm/redeo) ⭐ 443 | 🐛 3 | 🌐 Go | 📅 2023-01-20 :  `Redigo`是`Redis`数据库的Go客户端。
  * [redigo](https://github.com/gomodule/redigo) ⭐ 9,857 | 🐛 24 | 🌐 Go | 📅 2025-11-02 : ` RediGo`是 `Redis` 数据库的`Go` 语言客户端.
  * [redis](https://github.com/go-redis/redis) ⭐ 22,215 | 🐛 63 | 🌐 Go | 📅 2026-08-16 :  兼容R`edis`协议的 `TCP` 服务器/服务.
  * [xredis](https://github.com/shomali11/xredis) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2019-06-08 :  类型安全的、可定制的、简洁易用的 `Redis` 客户端

***

* 搜索引擎和文本数据库
  * [bleve](https://github.com/blevesearch/bleve) ⭐ 11,176 | 🐛 300 | 🌐 Go | 📅 2026-08-13 :  现代文本索引库
  * [elastic](https://github.com/olivere/elastic) ⭐ 7,446 | 🐛 116 | 🌐 Go | 📅 2024-08-08 :  ` Go` 语言的 `Elasticsearch `客户端
  * [go-elasticsearch](https://github.com/elastic/go-elasticsearch) ⭐ 6,058 | 🐛 25 | 🌐 Go | 📅 2026-08-14 : Go的官方`Elasticsearch`客户端。
  * [riot](https://github.com/go-ego/riot) ⚠️ Archived :  `Go`开源,分布式,简单高效的搜索引擎。
  * [elasticsql](https://github.com/cch123/elasticsql) ⭐ 1,188 | 🐛 13 | 🌐 Go | 📅 2023-08-06将` sql` 转换为 `elasticsearch dsl  `
  * [elastigo](https://github.com/mattbaird/elastigo) ⭐ 941 | 🐛 68 | 🌐 Go | 📅 2019-02-05 :  `Elasticsearch`客户端库
  * [goes](https://github.com/OwnLocal/goes) ⭐ 30 | 🐛 0 | 🌐 Go | 📅 2020-10-19 :  用于和 `Elasticsearch` 交互的库
  * [skizze](https://github.com/seiflotfy/skizze) :  概率数据结构服务和存储。
* 多个后端:
  * [cayley](https://github.com/google/cayley) ⭐ 15,057 | 🐛 93 | 🌐 Go | 📅 2026-07-22 :  支持多个后端的图形数据库。
  * [gokv](https://github.com/philippgille/gokv) ⭐ 827 | 🐛 45 | 🌐 Go | 📅 2025-11-20 :  为`go（Redis、Consul、etcd、bbolt、BadgerDB、LevelDB、Memcached、DynamoDB、S3、PostgreSQL、MongoDB、CockroachDB`等）提供简单的键值存储抽象和实现。
  * [cachego](https://github.com/fabiorphp/cachego) ⚠️ Archived : `Golang Cache`组件,支持多个驱动。
  * [dsc](https://github.com/viant/dsc) ⭐ 37 | 🐛 1 | 🌐 Go | 📅 2025-12-31 : ` SQL、NoSQL`、结构化文件的数据存储连接。

***

## 日期和时间

`用于处理日期和时间的库`

* [now](https://github.com/jinzhu/now) ⭐ 4,697 | 🐛 18 | 🌐 Go | 📅 2026-02-02 :  `Now` 是一个 `Go` 语言的时间工具集
* [dateparse](https://github.com/araddon/dateparse) ⭐ 2,137 | 🐛 63 | 🌐 Go | 📅 2023-12-30 :  在不知道格式的情况下解析日期。
* [carbon](https://github.com/uniplaces/carbon) ⭐ 779 | 🐛 1 | 🌐 Go | 📅 2024-01-17 :  简单的时间扩展程序,有很多有用的方法,是`PHP Carbon`库的接口
* [durafmt](https://github.com/hako/durafmt) ⭐ 512 | 🐛 12 | 🌐 Go | 📅 2021-06-08 :  持续时间格式化
* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) ⭐ 243 | 🐛 4 | 🌐 Go | 📅 2025-09-28 : - 太阳历
* [timeutil](https://github.com/leekchan/timeutil) ⭐ 193 | 🐛 2 | 🌐 Go | 📅 2019-02-03 :  为 `Go` 语言时间包扩展了有用的功能,例如时间间隔和格式化
* [go-sunrise](https://github.com/nathan-osman/go-sunrise) ⭐ 176 | 🐛 4 | 🌐 Go | 📅 2024-04-23 :  计算指定地点的日出和日落时间。
* [iso8601](https://github.com/relvacode/iso8601) ⭐ 166 | 🐛 1 | 🌐 Go | 📅 2026-07-23 :  有效地解析`ISO8601`日期时间,而无需使用`regex`。
* [date](https://github.com/rickb777/date) ⭐ 143 | 🐛 0 | 🌐 Go | 📅 2026-08-12 :  增强了Time的功能,用于处理日期、日期范围、时间跨度、时间段和日期时间。
* [go-str2duration](https://github.com/xhit/go-str2duration) ⭐ 118 | 🐛 1 | 🌐 Go | 📅 2023-10-14 :  将字符串转换为持续时间。支持`time.Duration`返回字符串等。
* [timespan](https://github.com/SaidinWoT/timespan) ⭐ 83 | 🐛 3 | 🌐 Go | 📅 2019-03-19 :  用于与时间间隔交互,定义为开始时间和持续时间
* [feiertage](https://github.com/wlbr/feiertage) ⭐ 54 | 🐛 0 | 🌐 Go | 📅 2026-05-18 :   一组计算德国公共假期的函数,比如复活节、感恩节等
* [kair](https://github.com/GuilhermeCaruso/kair) ⭐ 24 | 🐛 0 | 🌐 Go | 📅 2020-06-18 :   日期和时间 - `Golang `格式化库。
* [cronrange](https://github.com/1set/cronrange) ⭐ 18 | 🐛 2 | 🌐 Go | 📅 2022-09-04 :  解析`Cron`风格的时间范围表达式,检查给定时间是否在任何范围内。
* [NullTime](https://github.com/kirillDanshin/nulltime) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2017-03-22 :  -时间可以是 `NULL` 的库
* [strftime](https://github.com/awoodbeck/strftime) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2018-02-21 : `C99`兼容的`strftime`格式化器。
* [tuesday](https://github.com/osteele/tuesday) ⭐ 13 | 🐛 2 | 🌐 Go | 📅 2026-08-15 :  `Ruby`兼容的`Strftime`函数。
* [go-week](https://github.com/stoewer/go-week) ⭐ 11 | 🐛 2 | 🌐 Go | 📅 2021-11-15 :  处理星期的库

***

## 分布式系统

* [raft](https://github.com/coreos/etcd/tree/master/raft) ⭐ 52,118 | 🐛 317 | 🌐 Go | 📅 2026-08-15 : ` Raft`共识协议的 `Go` 实现,由 `CoreOS` 提供。
* [go-kit](https://github.com/go-kit/kit) ⭐ 27,418 | 🐛 60 | 🌐 Go | 📅 2024-07-19 :   为服务工具吧,支持服务发现、负载均衡 、可插拔传输以及请求追踪等
* [grpc-go](https://github.com/grpc/grpc-go) ⭐ 23,034 | 🐛 126 | 🌐 Go | 📅 2026-08-15 : ` gRPC`的Go语言实现。基于`HTTP/2的RPC`。
* [go-micro](https://github.com/micro/go-micro) ⭐ 23,016 | 🐛 8 | 🌐 Go | 📅 2026-08-16 :   一个分布式系统开发框架。
* [NATS](https://github.com/nats-io/gnatsd) ⭐ 20,523 | 🐛 543 | 🌐 Go | 📅 2026-08-15 :  轻量级、高性能微服务系统,用于微服务、物联网以及云
* [raft](https://github.com/hashicorp/raft) ⭐ 9,088 | 🐛 51 | 🌐 Go | 📅 2026-08-02 :  `Raft` 共识协议的 `Golang `实现,由 `HashiCorp`.开发。
* [rpcx](https://github.com/smallnest/rpcx) ⭐ 8,310 | 🐛 3 | 🌐 Go | 📅 2026-07-10 :   `rpcx`是一个类似阿里巴巴` Dubbo` 和微博` Motan` 的分布式的`RPC`服务框架
* [KrakenD](https://github.com/devopsfaith/krakend) ⭐ 6,787 | 🐛 13 | 🌐 Go | 📅 2026-08-04 :  带有中间件的,高性能`API`网关框架
* [torrent](https://github.com/anacrolix/torrent) ⭐ 6,093 | 🐛 68 | 🌐 Go | 📅 2026-08-13 :   `BitTorrent` 客户端
* [tendermint](https://github.com/tendermint/tendermint) ⭐ 5,863 | 🐛 20 | 🌐 Go | 📅 2026-08-12 : 使用`Tendermint` 一致性及区块链协议的高性能的中间件,用于将任何语言编写的状态机转换为一个拜占庭容错状态机,
* [dragonboat](https://github.com/lni/dragonboat) ⭐ 5,323 | 🐛 64 | 🌐 Go | 📅 2025-07-23 :  `Go`中一个功能完整且高性能的多组`Raft`库。
* [emitter-io](https://github.com/emitter-io/emitter) ⭐ 4,004 | 🐛 16 | 🌐 Go | 📅 2026-04-29 :  使用` MQTT、Websockets` 和 `love` 构建的高性能、分布式、安全和低延迟的发布-订阅平台。
* [gleam](https://github.com/chrislusf/gleam) ⭐ 3,562 | 🐛 39 | 🌐 Go | 📅 2026-07-25 :   快速、可扩展的分布式` map/reduce` 系统,使用纯` Go` 语言和` Luajit` 编写,融合了 Go 语言的高并发能力和 Luajit 的高性能,可以独立或分布式部署运行。
* [glow](https://github.com/chrislusf/glow) ⭐ 3,218 | 🐛 15 | 🌐 Go | 📅 2018-11-02 :   易于使用的可扩展的分布式大数据处理、`Map-Reduce、DAG`执行,全部用纯Go编写。
* [liftbridge](https://github.com/liftbridge-io/liftbridge) ⭐ 2,799 | 🐛 42 | 🌐 Go | 📅 2026-07-25 :  用于`NATS`的轻量级、容错消息流。
* [redis-lock](https://github.com/bsm/redislock) ⭐ 1,766 | 🐛 3 | 🌐 Go | 📅 2026-06-27 :  使用Redis实现的简化的分布式锁。
* [hprose](https://github.com/hprose/hprose-golang) ⭐ 1,255 | 🐛 5 | 🌐 Go | 📅 2024-02-18 :  非常新颖的RPC库,现在支持25种以上的语言。
* [rain](https://github.com/cenkalti/rain) ⭐ 1,143 | 🐛 1 | 🌐 Go | 📅 2026-08-12 :   `BitTorrent`客户端和库。
* [arpc](https://github.com/lesismal/arpc) ⭐ 1,090 | 🐛 0 | 🌐 Go | 📅 2026-07-04 :  更有效的网络通信,支持双向呼叫、通知、广播。
* [ringpop-go](https://github.com/uber/ringpop-go) ⭐ 878 | 🐛 29 | 🌐 Go | 📅 2025-10-16 :   为`Go`应用提供可扩展、容错的应用层分片。
* [consistent](https://github.com/buraksezer/consistent) ⭐ 783 | 🐛 5 | 🌐 Go | 📅 2026-08-16 :  有限负载的一致哈希算法库。
* [go-health](https://github.com/InVisionApp/go-health) ⚠️ Archived :  用于在服务中启用异步依赖性健康检查的库。
* [gorpc](https://github.com/valyala/gorpc) ⭐ 710 | 🐛 14 | 🌐 Go | 📅 2022-10-07 :  简单、快速、可扩展的`RPC` 库,针对高负载场景
* [go-sundheit](https://github.com/AppsFlyer/go-sundheit) ⭐ 561 | 🐛 6 | 🌐 Go | 📅 2026-07-14 :  为 `golang `服务定义异步服务健康检查提供支持的库。
* [digota](https://github.com/digota/digota) ⭐ 525 | 🐛 12 | 🌐 Go | 📅 2021-02-14 grpc电子商务微服务。
* [go-jump](https://github.com/dgryski/go-jump) ⭐ 388 | 🐛 1 | 🌐 Go | 📅 2021-10-18 :  `Google "Jump" `一致性哈希函数的接口
* [sleuth](https://github.com/ursiform/sleuth) ⭐ 388 | 🐛 0 | 🌐 Go | 📅 2023-07-09 :  在 `HTTP `服务之间进行无主` p2p` 自动发现和 RPC通信(使用 [ZeroMQ](https://github.com/zeromq/libzmq) ⭐ 10,964 | 🐛 380 | 🌐 C++ | 📅 2026-07-26)ß
* [jsonrpc](https://github.com/ybbus/jsonrpc) ⭐ 372 | 🐛 0 | 🌐 Go | 📅 2025-10-26 :  `JSON-RPC 2.0 HTTP `客户端实现
* [dht](https://github.com/anacrolix/dht) ⭐ 363 | 🐛 5 | 🌐 Go | 📅 2026-05-25 : `BitTorrent Kademlia DHT`的实现。
* [jsonrpc](https://github.com/osamingo/jsonrpc) ⭐ 193 | 🐛 6 | 🌐 Go | 📅 2025-03-28 : `jsonrpc` 包实现了 `JSON-RPC 2.0`.
* [outboxer](https://github.com/italolelis/outboxer) ⭐ 168 | 🐛 4 | 🌐 Go | 📅 2026-08-16 : ` Outboxer`是一个实现`outbox`模式的`go`库。
* [doublejump](https://github.com/edwingeng/doublejump) ⭐ 111 | 🐛 0 | 🌐 Go | 📅 2022-10-19 :   改版后的`Google`的跳转一致哈希。
* [Semaphore](https://github.com/jexia/semaphore) ⭐ 97 | 🐛 32 | 🌐 Go | 📅 2023-03-06 :  直接的（微）服务协调器。
* [dot](https://github.com/dotchain/dot/) ⭐ 88 | 🐛 0 | 🌐 Go | 📅 2019-09-30 ： 使用操作转换/OT的分布式同步库。
* [celeriac](https://github.com/svcavallar/celeriac.v1) ⭐ 76 | 🐛 0 | 🌐 Go | 📅 2024-07-17 :  利用 `Go` 语言对`Celery`的` worker`ß任务事件进行交互和监控的库
* [go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) ⭐ 67 | 🐛 2 | 🌐 Go | 📅 2024-05-13 :   基于`MySQL`的分布式锁。
* [flowgraph](https://github.com/vectaport/flowgraph) ⭐ 66 | 🐛 3 | 🌐 Go | 📅 2026-08-08 :  基于流的编程包实现的MPI 风格的读取,发送协同层；
* [drmaa](https://github.com/dgruber/drmaa) ⭐ 51 | 🐛 0 | 🌐 Go | 📅 2026-08-09 :  集群调度工具的任务提交库,基于标准 `DRMAA`
* [go-pdu](https://github.com/pdupub/go-pdu) ⭐ 50 | 🐛 0 | 🌐 Go | 📅 2026-04-17 :  基于身份的去中心化社交网络。
* [consistenthash](https://github.com/mbrostami/consistenthash) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2026-06-05 :   使用可配置的副本实现一致的哈希。
* [gmsec](https://github.com/gmsec/micro) ⭐ 27 | 🐛 3 | 🌐 Go | 📅 2026-02-28 :   Go分布式系统开发框架。
* [dynatomic](https://github.com/tylfin/dynatomic) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2020-11-04 :  将 `DynamoDB` 作为原子计数器使用的库。
* [dynamolock](https://cirello.io/dynamolock) :  `DynamoDB`支持的分布式锁的实现。
* [micro](https://github.com/micro/micro) :  面向云计算及其他领域的分布式系统运行时。
* [pglock](https://cirello.io/pglock) :   `PostgreSQL`支持的分布式锁的实现。
* [resgate](https://resgate.io/) :  用于构建 `REST`、实时和 `RPC API` 的实时 `API` 网关,所有客户端都可以无缝同步

***

## 动态DNS

`更新动态dns记录的库和工具`

* [GoDNS](https://github.com/timothyye/godns) ⭐ 1,774 | 🐛 15 | 🌐 Go | 📅 2026-07-26 : 用Go编写的动态`DNS`客户端工具,支持`DNSPod`和`HE.net`。
* [DDNS](https://github.com/skibish/ddns) ⭐ 266 | 🐛 3 | 🌐 Go | 📅 2025-05-01 :  以`digital ocean `DNS为后台的个人DDNS客户端。
* [dyndns](https://gitlab.com/alcastle/dyndns) :   后台`Go`进程,定期自动检查您的IP地址,并在您的地址发生变化时更新（一个或多个）谷歌域名的动态DNS记录。

***

## 邮件库

`邮件管理和发送的go语言库`

* [MailHog](https://github.com/mailhog/MailHog) ⭐ 16,122 | 🐛 255 | 🌐 Go | 📅 2024-02-13 :  `Email` 及 `SMTP` 测试工具,具有 web 及 API 接口
* [hermes](https://github.com/matcornic/hermes) ⭐ 3,020 | 🐛 22 | 🌐 Go | 📅 2025-04-04 :  一个用于生成干净、响应式 `HTML e-mail` 的包
* [email](https://github.com/jordan-wright/email) ⭐ 2,795 | 🐛 58 | 🌐 Go | 📅 2024-02-21 : 健壮的、灵活的 `email `库
* [go-imap](https://github.com/emersion/go-imap) ⭐ 2,346 | 🐛 75 | 🌐 Go | 📅 2026-07-02 :  ` IMAP` 库,用于客户端和服务器
* [SendGrid](https://github.com/sendgrid/sendgrid-go) ⭐ 1,061 | 🐛 34 | 🌐 Go | 📅 2026-06-25 : `SendGrid`的 Go 语言库,用于发送电子邮件
* [mailgun-go](https://github.com/mailgun/mailgun-go) ⭐ 745 | 🐛 2 | 🌐 Go | 📅 2026-08-15 :  使用`Mailgun API`发送邮件的Go库。
* [go-simple-mail](https://github.com/xhit/go-simple-mail) ⭐ 696 | 🐛 19 | 🌐 Go | 📅 2024-07-20 :  `go`语言实现的基于简单`smtp`协议的邮件发送库
* [go-message](https://github.com/emersion/go-message) ⭐ 456 | 🐛 31 | 🌐 Go | 📅 2025-02-16 :  用于互联网消息格式和邮件的库
* [douceur](https://github.com/aymerick/douceur) ⭐ 261 | 🐛 9 | 🌐 Go | 📅 2022-09-11 : `HTML` 邮件中的内联 `CSS` 库
* [Hectane](https://github.com/hectane/hectane) ⭐ 226 | 🐛 16 | 🌐 Go | 📅 2020-11-29 :  轻量级 `SMTP `客户端,提供 `HTTP API`
* [go-premailer](https://github.com/vanng822/go-premailer) ⭐ 205 | 🐛 1 | 🌐 Go | 📅 2026-08-02 : 在`Go`中为`HTML`邮件提供在线样式。
* [mailchain](https://github.com/mailchain/mailchain) ⚠️ Archived :  用`go`写的用于发送加密邮件到区块链地址的邮件库
* [go-dkim](https://github.com/toorop/go-dkim) ⭐ 99 | 🐛 5 | 🌐 Go | 📅 2025-02-26 :  `DKIM` 库,用于对 `email` 进行签名和验证
* [smtp](https://github.com/mailhog/smtp) ⭐ 77 | 🐛 7 | 🌐 Go | 📅 2021-10-20 :   `SMTP` 服务器协议状态机
* [chasquid](https://blitiri.com.ar/p/chasquid) :  用Go编写的SMTP服务器。

***

## 脚本语言与嵌入式编程

`在你的go代码中嵌入其他脚本语言`

* [expr](https://github.com/antonmedv/expr) ⭐ 7,974 | 🐛 89 | 🌐 Go | 📅 2026-07-07 :  ` Go` 的表达式评估引擎，具有快速、非图灵完备、动态类型化、静态类型化的特性。
* [goja](https://github.com/dop251/goja) ⭐ 7,050 | 🐛 31 | 🌐 Go | 📅 2026-08-06 :  在 Go 中实现 `ECMAScript 5.1(+)` 。
* [gopher-lua](https://github.com/yuin/gopher-lua) ⭐ 6,962 | 🐛 103 | 🌐 Go | 📅 2026-04-01 :  ` Go` 语言编写的 `Lua 5.1` 虚拟机和编译器
* [tengo](https://github.com/d5/tengo) ⭐ 3,829 | 🐛 89 | 🌐 Go | 📅 2026-04-29 : `Go`的字节码编译脚本语言。
* [go-lua](https://github.com/Shopify/go-lua) ⭐ 3,446 | 🐛 48 | 🌐 Go | 📅 2025-07-18 :  `Lua 5.2`虚拟机的纯 Go 语言接口
* [cel-go](https://github.com/google/cel-go) ⭐ 3,068 | 🐛 64 | 🌐 Go | 📅 2026-08-15 :  快速、可移植、非图灵完全表达式评估和渐进分型。
* [anko](https://github.com/mattn/anko) ⭐ 1,579 | 🐛 19 | 🌐 Go | 📅 2026-07-10 :   `Go `语言编写的解释器
* [go-python](https://github.com/sbinet/go-python) ⚠️ Archived :  `CPython C-API` 的` Go` 语言接口
* [go-php](https://github.com/deuill/go-php) ⭐ 943 | 🐛 21 | 🌐 Go | 📅 2025-01-06 :  `PHP` 的` Go` 语言接口
* [gval](https://github.com/PaesslerAG/gval) ⭐ 813 | 🐛 24 | 🌐 Go | 📅 2026-08-12 :  Go编写的高度可定制的表达式语言。
* [go-duktape](https://github.com/olebedev/go-duktape) ⚠️ Archived :  ` Go`的`Duktape JavaScript`引擎封装。
* [golua](https://github.com/aarzilli/golua) ⭐ 699 | 🐛 14 | 🌐 C | 📅 2025-02-17 :  `lua C API`的 `Go `语言接口。
* [gisp](https://github.com/jcla1/gisp) ⭐ 531 | 🐛 1 | 🌐 Go | 📅 2017-08-25 :  `Go`中的简单`LISP`。
* [gentee](https://github.com/gentee/gentee) ⭐ 145 | 🐛 3 | 🌐 Go | 📅 2025-07-10 :  可嵌入脚本编程语言。
* [binder](https://github.com/alexeyco/binder) ⭐ 79 | 🐛 2 | 🌐 Go | 📅 2022-07-07 :  基于[gopher-lua](https://github.com/yuin/gopher-lua) ⭐ 6,962 | 🐛 103 | 🌐 Go | 📅 2026-04-01的go语言Lua 接口,
* [purl](https://github.com/ian-kent/purl) ⭐ 41 | 🐛 2 | 🌐 Go | 📅 2014-12-07 :  嵌入 `Go` 语言的 `Perl 5.18.2`
* [ngaro](https://github.com/db47h/ngaro) ⭐ 30 | 🐛 1 | 🌐 Go | 📅 2018-06-03 :  可嵌入的Ngaro虚拟机实现,可在`Retro`中编写脚本。

***

## 错误处理

`go 语言错误处理库`

* [errors](https://github.com/pkg/errors) ⭐ 8,257 | 🐛 44 | 🌐 Go | 📅 2026-03-27 :  提供简单错误处理单元的包。
* [go-multierror](https://github.com/hashicorp/go-multierror) ⭐ 2,579 | 🐛 29 | 🌐 Go | 📅 2026-07-06 : 用于将错误列表表示为单个错误的包
* [eris](https://github.com/rotisserie/eris) ⭐ 1,794 | 🐛 4 | 🌐 Go | 📅 2025-04-03 :  在`Go`中处理、跟踪和记录错误的更好方法。与标准错误库和`github.com/pkg/errors`兼容。
* [errorx](https://github.com/joomcode/errorx) ⭐ 1,270 | 🐛 7 | 🌐 Go | 📅 2024-11-08 :  功能丰富的错误处理包,包括堆栈信息获取、错误组成分析等
* [tracerr](https://github.com/ztrue/tracerr) ⭐ 1,119 | 🐛 4 | 🌐 Go | 📅 2026-04-02 ： 带有堆栈跟踪和源片段的`Golang`错误处理包。
* [errlog](https://github.com/snwfdhmp/errlog) ⭐ 459 | 🐛 0 | 🌐 Go | 📅 2023-06-27 : 用于确定错误的责任源代码（以及其他一些快速调试功能，可以嵌入到任何的日志服务中。
* [emperror](https://github.com/emperror/emperror) ⭐ 387 | 🐛 6 | 🌐 Go | 📅 2020-10-04 : ` Go`库和应用程序的错误处理工具和最佳实践。
* [errors](https://github.com/emperror/errors) ⭐ 203 | 🐛 12 | 🌐 Go | 📅 2022-06-20 :  标准库错误包和` github.com/pkg/errors` 的替代包。提供各种错误处理单元。
* [errors](https://github.com/bnkamalesh/errors) ⭐ 76 | 🐛 0 | 🌐 Go | 📅 2025-09-23 :   最小的错误处理包,具有自定义错误类型等特性
* [Falcon](https://github.com/SonicRoshan/falcon) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2019-10-10 :  简单但功能强大的错误处理包。
* [errors](https://github.com/PumpkinSeed/errors) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2022-03-31 :  最简单的错误封装器,性能卓越,内存开销最小。
* [errors](https://github.com/neuronlabs/errors) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2019-08-02 :  简单的 `golang `错误处理包。

***

## 文件处理

`处理文件和文件系统操作的库`

* [pdfcpu](https://github.com/pdfcpu/pdfcpu) ⭐ 8,784 | 🐛 108 | 🌐 Go | 📅 2026-08-11 :   PDF 处理器。
* [afero](https://github.com/spf13/afero) ⭐ 6,688 | 🐛 129 | 🌐 Go | 📅 2026-08-14 : ` go`语言编写的对文件系统进行抽象的系统框架
* [notify](https://github.com/rjeczalik/notify) ⭐ 936 | 🐛 46 | 🌐 Go | 📅 2026-06-01 : 类似 `os/signal`的文件系统提示库,具有简单的 API.
* [copy](https://github.com/otiai10/copy) ⭐ 771 | 🐛 24 | 🌐 Go | 📅 2025-01-05 :  递归复制目录。
* [afs](https://github.com/viant/afs) ⭐ 393 | 🐛 7 | 🌐 Go | 📅 2026-08-05 :  适用于 `Go` 的抽象文件存储。
* [vfs](https://github.com/C2FO/vfs) ⭐ 369 | 🐛 9 | 🌐 Go | 📅 2026-07-25 :  适用于 `Go` 的多个文件系统类型,如 `os、S3 `和 `GCS`的可插拔、可扩展的文件系统功能库。
* [go-exiftool](https://github.com/barasher/go-exiftool) ⭐ 296 | 🐛 11 | 🌐 Go | 📅 2025-08-03 :  为`ExifTool`提供绑定服务,`ExifTool`是一个著名的库,用于从文件（图片、PDF、office...）中提取尽可能多的元数据
* [bigfile](https://github.com/bigfile/bigfile) ⚠️ Archived :  文件传输系统,支持用`http api、rpc`调用和`ftp`客户端管理文件。
* [go-csv-tag](https://github.com/artonge/go-csv-tag) ⭐ 131 | 🐛 0 | 🌐 Go | 📅 2025-06-17 :   使用 `tag` 导入 `csv`
* [parquet](https://github.com/parsyl/parquet) ⭐ 127 | 🐛 2 | 🌐 Go | 📅 2025-04-17 :   读取和写入[parquet](https://parquet.apache.org) 文件。
* [checksum](https://github.com/codingsince1985/checksum) ⭐ 112 | 🐛 2 | 🌐 Go | 📅 2023-12-19 :  计算大文件的信息摘要,如`MD5`和`SHA256`。
* [skywalker](https://github.com/dixonwille/skywalker) ⭐ 102 | 🐛 1 | 🌐 Go | 📅 2021-08-31 :  允许你简单方便的并发浏览文件系统
* [opc](https://github.com/qmuntal/opc) ⭐ 80 | 🐛 1 | 🌐 Go | 📅 2023-12-01 :   为`Go`加载`Open Packaging Conventions (OPC)`文件
* [baraka](https://github.com/xis/baraka) ⭐ 65 | 🐛 2 | 🌐 Go | 📅 2022-09-30 :   用于轻松处理 `http `文件上传的库。
* [tarfs](https://github.com/posener/tarfs) ⭐ 58 | 🐛 1 | 🌐 Go | 📅 2020-03-13 :  为 `tar` 文件实现的文件系统接口
* [go-gtfs](https://github.com/artonge/go-gtfs) ⭐ 47 | 🐛 0 | 🌐 Go | 📅 2023-08-16 :  用`go`加载`gtfs`文件
* [flop](https://github.com/homedepot/flop) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2021-12-07 :   文件操作库,目的是与 [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html)进行镜像。
* [gut/yos](https://github.com/1set/gut) ⭐ 27 | 🐛 13 | 🌐 Go | 📅 2020-11-17 :  简单可靠的文件操作包,支持对文件、目录和符号链接的`copy/move/diff/list`。
* [todotxt](https://github.com/1set/todotxt) ⭐ 25 | 🐛 1 | 🌐 Go | 📅 2023-09-21` todo.txt`文件的go语言解析器。
* [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) ⭐ 22 | 🐛 1 | 🌐 Go | 📅 2020-01-03 : 文件复制功能库。
* [stl](https://gitlab.com/russoj88/stl) :  读取和写入`STL`文件的模块，采取并发的读取算法。

***

## 金融领域相关库

`处理货币与金融领域的库`

* [decimal](https://github.com/shopspring/decimal) ⭐ 7,471 | 🐛 154 | 🌐 Go | 📅 2026-06-29 :  支持任意精度的十进制数的go包
* [go-money](https://github.com/rhymond/go-money) ⭐ 1,911 | 🐛 28 | 🌐 Go | 📅 2026-04-29 :   `Fowler's Money`模式的实现。
* [accounting](https://github.com/leekchan/accounting) ⭐ 910 | 🐛 13 | 🌐 Go | 📅 2022-07-28 :  `Go`语言金钱及货币格式
* [techan](https://github.com/sdcoffey/techan) ⭐ 908 | 🐛 17 | 🌐 Go | 📅 2026-05-29 :   具有高级市场分析和交易策略的技术分析库。
* [currency](https://github.com/bojanz/currency) ⭐ 645 | 🐛 4 | 🌐 Go | 📅 2026-08-10 :  处理货币金额,提供货币信息和格式。
* [orderbook](https://github.com/i25959341/orderbook) ⭐ 558 | 🐛 5 | 🌐 Go | 📅 2025-04-04 :  `Golang`中的限价订单簿的匹配引擎。
* [go-finance](https://github.com/alpeb/go-finance) ⭐ 193 | 🐛 1 | 🌐 Go | 📅 2021-12-02 :   用于货币时间价值（年金）、现金流、利率转换、债券和折旧计算的金融函数库。
* [ofxgo](https://github.com/aclindsa/ofxgo) ⭐ 152 | 🐛 2 | 🌐 Go | 📅 2026-02-09 :   查询 `OFX `服务器并解析其响应 (有一个示例的命令行客户端)
* [transaction](https://github.com/claygod/transaction) ⭐ 139 | 🐛 0 | 🌐 Go | 📅 2025-04-24 : 以多线程模式运行的嵌入式的账户交易数据库,。
* [vat](https://github.com/dannyvankooten/vat) ⭐ 119 | 🐛 4 | 🌐 Go | 📅 2023-11-07 :   VAT 验证及欧洲增值税率工具
* [go-finnhub](https://github.com/m1/go-finnhub) ⚠️ Archived :  来自`finnhub.io`的股市、外汇和加密数据客户端。访问来自60多家证券交易所、10家外汇经纪商和15家以上加密交易所的实时金融市场数据。
* [currency](https://github.com/bnkamalesh/currency) ⭐ 62 | 🐛 0 | 🌐 Go | 📅 2025-09-23 :  高性能、精确的货币计算包。
* [go-finance](https://github.com/pieterclaerhout/go-finance) ⭐ 32 | 🐛 0 | 🌐 Go | 📅 2025-09-01 :  用于获取汇率、通过VIES查询增值税号和查询IBAN银行账号的模块。
* [fastme](https://github.com/newity/fastme) : `Go`实现的 快速可扩展的匹配引擎 。
* [go-finance](https://github.com/FlashBoys/go-finance) : `Go`中的综合金融市场数据。

***

## 表单

`表单解析与绑定`

* [nosurf](https://github.com/justinas/nosurf) ⭐ 1,746 | 🐛 15 | 🌐 Go | 📅 2025-05-13 :  `CSRF` 防御中间件
* [gorilla/csrf](https://github.com/gorilla/csrf) ⭐ 1,205 | 🐛 32 | 🌐 Go | 📅 2025-04-14 : 为 `Go` 语言 `web` 应用提供 `CSRF` 防御
* [form](https://github.com/go-playground/form) ⭐ 923 | 🐛 15 | 🌐 Go | 📅 2025-10-11 :  解码 `url `中的数据到 `Go` 语言变量中以及将 `Go `语言变量编码进 `url` 。
* [binding](https://github.com/mholt/binding) ⚠️ Archived :  将来自`net/HTTP`请求的表单、`JSON` 数据绑定到结构体
* [conform](https://github.com/leebenson/conform) ⭐ 325 | 🐛 5 | 🌐 Go | 📅 2025-07-15 :  检查用户输入并基于结构标签来清理数据
* [formam](https://github.com/monoculum/formam) ⭐ 192 | 🐛 3 | 🌐 Go | 📅 2022-11-06 :  将表单数据解码到结构体
* [forms](https://github.com/albrow/forms) ⭐ 141 | 🐛 2 | 🌐 Go | 📅 2022-12-16 :  框架无关的表单/JSON数据解析验证库,支持多部分表单及文件
* [qs](https://github.com/sonh/qs) ⭐ 83 | 🐛 0 | 🌐 Go | 📅 2026-06-06 :  用于将结构体编码为 `URL` 查询参数的` Go` 模块
* [bind](https://github.com/robfig/bind) ⭐ 32 | 🐛 0 | 🌐 Go | 📅 2014-08-16 :  可以表单数据绑定到任意的` Go` 变量上
* [queryparam](https://github.com/tomwright/queryparam) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2020-09-23 :  将`url.Values`解码为标准或自定义类型的可用结构体值。

***

## 函数式编程

* [go-underscore](https://github.com/tobyhede/go-underscore) ⭐ 1,298 | 🐛 4 | 🌐 Go | 📅 2023-02-28 :  `Go`函数式集合工具。
* [fpGo](https://github.com/TeaEntityLab/fpGo) ⭐ 355 | 🐛 0 | 🌐 Go | 📅 2026-07-01 :   `Golang`中的单项式函数式编程功能
* [fuego](https://github.com/seborama/fuego) ⭐ 145 | 🐛 0 | 🌐 Go | 📅 2024-04-13 :  `Go`中实验室的函数式编程。

***

## 游戏开发

* [Ebiten](https://github.com/hajimehoshi/ebiten) ⭐ 13,402 | 🐛 293 | 🌐 Go | 📅 2026-08-16 :  `Go` 语言编写的简单的 `2D` 游戏库
* [Leaf](https://github.com/name5566/leaf) ⭐ 5,518 | 🐛 26 | 🌐 Go | 📅 2024-05-23 :  轻量级游戏服务器框架
* [Pixel](https://github.com/faiface/pixel) ⭐ 4,525 | 🐛 44 | 🌐 Go | 📅 2024-05-23 :`2D` 游戏引擎库
* [nano](https://github.com/lonng/nano) ⭐ 3,222 | 🐛 33 | 🌐 Go | 📅 2026-02-26 :  基于`golang`的轻量级、设施、高性能的游戏服务器框架。
* [g3n](https://github.com/g3n/engine) ⭐ 3,105 | 🐛 36 | 🌐 Go | 📅 2026-08-01 :  `Go 3D`游戏引擎。
* [Pitaya](https://github.com/topfreegames/pitaya) ⭐ 2,823 | 🐛 67 | 🌐 Go | 📅 2026-07-22 :  可扩展的游戏服务器框架,支持集群,并通过`C SDK`为`iOS、Android、Unity`等提供客户端库。
* [goworld](https://github.com/xiaonanln/goworld) ⭐ 2,720 | 🐛 27 | 🌐 Go | 📅 2025-11-14 :  可扩展的游戏服务器引擎。
* [raylib-go](https://github.com/gen2brain/raylib-go) ⭐ 2,509 | 🐛 8 | 🌐 C | 📅 2026-08-15 :   raylib的 Go 语言接口,简单、易用的用于学习游戏编程的库
* [go-sdl2](https://github.com/veandco/go-sdl2) ⭐ 2,327 | 🐛 88 | 🌐 C | 📅 2025-02-20 :  [Simple DirectMedia Layer](https://www.libsdl.org/) 的 `Go`封装。
* [engo](https://github.com/EngoEngine/engo) ⭐ 1,819 | 🐛 54 | 🌐 Go | 📅 2026-03-30 :  `EnGo`是一个开源的`2D`游戏引擎,遵循实体-组件-系统范式
* [Oak](https://github.com/oakmound/oak) ⭐ 1,667 | 🐛 14 | 🌐 Go | 📅 2026-08-10 :  `go`游戏引擎。
* [termloop](https://github.com/JoelOtter/termloop) ⭐ 1,472 | 🐛 6 | 🌐 Go | 📅 2024-07-29 :  终端游戏引擎,基于 `Termbox`
* [gonet](https://github.com/xtaci/gonet) ⚠️ Archived :  `Go `语言实现的游戏服务器框架
* [go-astar](https://github.com/beefsack/go-astar) ⭐ 629 | 🐛 3 | 🌐 Go | 📅 2022-01-27 :  A\*路径查找算法的Go实现。
* [go3d](https://github.com/ungerik/go3d) ⭐ 341 | 🐛 0 | 🌐 Go | 📅 2025-10-20 :  专注性能的 `2D/3D` 数学库
* [tile](https://github.com/kelindar/tile) ⭐ 225 | 🐛 2 | 🌐 Go | 📅 2025-08-17 : 面向数据和缓存友好的 `2D` 网格库 (`TileMap`)。
* [prototype](https://github.com/gonutz/prototype) ⭐ 108 | 🐛 2 | 🌐 C | 📅 2025-08-05 :   跨平台（`Windows/Linux/Mac`）库,可利用最小的API创建桌面游戏。
* [Azul3D](https://github.com/azul3d/engine) :  `Go `语言编写的 `3D` 游戏引擎
* [raylib](http://www.raylib.com/) :  raylib的Go绑定,一个简单易用的电子游戏编程学习库。

***

## 代码生成与泛型

* [go-linq](https://github.com/ahmetalpbalkan/go-linq) ⭐ 3,661 | 🐛 3 | 🌐 Go | 📅 2026-08-10 :  类似`.NET LINQ`的`Go`查询方法。
* [jennifer](https://github.com/dave/jennifer) ⭐ 3,628 | 🐛 19 | 🌐 Go | 📅 2024-09-08 :   不适用模板生成任意 `Go` 语言代码
* [gen](https://github.com/clipperhouse/gen) ⭐ 1,424 | 🐛 32 | 🌐 Go | 📅 2023-10-31 :  代码生成工具,用于提供类似泛型的功能
* [GoWrap](https://github.com/hexdigest/gowrap) ⭐ 1,334 | 🐛 21 | 🌐 Go | 📅 2026-07-24 :  使用简单的模板为 `Go `接口生成装饰器。
* [goderive](https://github.com/awalterschulze/goderive) ⭐ 1,261 | 🐛 19 | 🌐 Go | 📅 2026-08-04 :  从输入类型导出函数。
* [go-enum](https://github.com/abice/go-enum) ⭐ 954 | 🐛 20 | 🌐 Go | 📅 2026-07-21 :   从代码注释中生成`enums`代码。
* [interfaces](https://github.com/rjeczalik/interfaces) ⭐ 431 | 🐛 15 | 🌐 Go | 📅 2025-06-03 :  命令行工具,用于生成接口定义
* [pkgreflect](https://github.com/ungerik/pkgreflect) ⭐ 104 | 🐛 0 | 🌐 Go | 📅 2017-09-05 :  用于包作用域反射的 `Go `语言预处理器
* [gotype](https://github.com/wzshiming/gotype) ⭐ 66 | 🐛 2 | 🌐 Go | 📅 2026-07-10 :  `Golang `源代码解析,用法类似于 `reflect` 包。
* [efaceconv](https://github.com/t0pep0/efaceconv) ⭐ 48 | 🐛 1 | 🌐 Go | 📅 2017-10-12 :  代码生成工具,用于高效的将 `interface{} `转换为不可变类型,并且不需要进行任何内存分配
* [generis](https://github.com/senselogic/GENERIS) ⭐ 47 | 🐛 0 | 🌐 D | 📅 2022-02-22 :  提供泛型、自由形式宏、条件编译和 `HTML` 模板化的代码生成工具。
* [go-xray](https://github.com/pieterclaerhout/go-xray) ⭐ 28 | 🐛 0 | 🌐 Go | 📅 2024-06-24 :  使反射的使用更加简单的助手。
* [typeregistry](https://github.com/xiaoxin01/typeregistry) ⭐ 23 | 🐛 0 | 🌐 Go | 📅 2020-02-20 :   用于动态创建类型的库。

***

## 位置信息与地理GEO处理库

* [gopherjs](https://github.com/gopherjs/gopherjs) ⭐ 13,173 | 🐛 191 | 🌐 Go | 📅 2026-07-27 :  把` Go` 编译为` JavaScript.`
* [Tile38](https://github.com/tidwall/tile38) ⭐ 9,714 | 🐛 162 | 🌐 Go | 📅 2026-08-07 :  具有空间索引和实时地理围栏的地理位置数据库。
* [S2 geometry](https://github.com/golang/geo) ⭐ 1,848 | 🐛 37 | 🌐 Go | 📅 2026-08-10 :  `Go`中的`S2`几何库。
* [llgo](https://github.com/go-llvm/llgo) ⚠️ Archived :  基于 `LLVM` 的` Go` 语言编译器
* [mbtileserver](https://github.com/consbio/mbtileserver) ⭐ 788 | 🐛 23 | 🌐 Go | 📅 2025-05-21 :  简单的基于`Go`的服务器,用于存储`mbtiles`格式的地理信息。
* [osm](https://github.com/paulmach/osm) ⭐ 467 | 🐛 10 | 🌐 Go | 📅 2026-08-14 :   用于读取、写入和处理`OpenStreetMap`数据和API的库。
* [tardisgo](https://github.com/tardisgo/tardisgo) ⭐ 430 | 🐛 5 | 🌐 Go | 📅 2016-11-19 : G`olang`转换为 `Haxe` 进而转换为 `CPP/CSharp/Java/JavaScript `的编译器.
* [c4go](https://github.com/Konstantin8105/c4go) ⭐ 375 | 🐛 27 | 🌐 C | 📅 2024-09-19 :   将`C`代码转换为`go`代码。
* [WGS84](https://github.com/wroge/wgs84) ⭐ 142 | 🐛 0 | 🌐 Go | 📅 2026-07-24 :  坐标转换和变换的库（`ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM`）。
* [geocache](https://github.com/melihmucuk/geocache) ⭐ 141 | 🐛 0 | 🌐 Go | 📅 2016-06-21 :  内存缓存,适用于基于地理位置的应用。
* [geoserver](https://github.com/hishamkaram/geoserver) ⭐ 94 | 🐛 1 | 🌐 Go | 📅 2026-08-03 :  用于通过`GeoServer REST API`操纵`GeoServer`实例的Go包。
* [pbf](https://github.com/maguro/pbf) ⭐ 56 | 🐛 2 | 🌐 Go | 📅 2026-04-24 : ` OpenStreetMap PBF golang`编码器/解码器。
* [gismanager](https://github.com/hishamkaram/gismanager) ⭐ 54 | 🐛 2 | 🌐 Go | 📅 2026-07-27 :   将你的GIS数据（矢量数据）发布到`PostGIS`和`Geoserver`的库。
* [f4go](https://github.com/Konstantin8105/f4go) ⭐ 51 | 🐛 7 | 🌐 Go | 📅 2023-08-17 :   将`FORTRAN 77`代码转为 `Go` 代码。
* [S2 geojson](https://github.com/pantrif/s2-geojson) ⭐ 37 | 🐛 2 | 🌐 Go | 📅 2024-08-16 :   将`geojson`转换为`S2`单元格,并在地图上演示一些`S2`几何特征。

***

## Goroutines

`goroutines的管理和使用`

* [ants](https://github.com/panjf2000/ants) ⭐ 14,489 | 🐛 1 | 🌐 Go | 📅 2026-07-04 : 高性能和低消耗的`goroutine`池。
* [tunny](https://github.com/Jeffail/tunny) ⭐ 4,028 | 🐛 8 | 🌐 Go | 📅 2023-03-09 :  `Go `语言协程池
* [goworker](https://github.com/benmanns/goworker) ⭐ 2,845 | 🐛 34 | 🌐 Go | 📅 2025-04-15 :  `Goworker `是一个基于 Go 语言的后台worker
* [pond](https://github.com/alitto/pond) ⭐ 2,186 | 🐛 6 | 🌐 Go | 📅 2026-06-22 :   在 `Go` 中编写的最小化和高性能的 `goroutine `工作池。
* [workerpool](https://github.com/gammazero/workerpool) ⭐ 1,458 | 🐛 4 | 🌐 Go | 📅 2026-07-02 :   用于限制任务执行的并发性的`goroutine`缓冲池。
* [grpool](https://github.com/ivpusic/grpool) ⭐ 732 | 🐛 5 | 🌐 Go | 📅 2019-01-27 :  轻量级`Goroutine`池。
* [pool](https://github.com/go-playground/pool) ⭐ 723 | 🐛 4 | 🌐 Go | 📅 2021-06-28 :  便于goroutine处理和取消的有限的消费者`goroutine`池或无限的`goroutine`池,
* [gowp](https://github.com/xxjwxc/gowp) ⭐ 514 | 🐛 3 | 🌐 Go | 📅 2024-09-29 :  - gowp 是限制并发量的`goroutine`池。
* [async](https://github.com/reugn/async) ⭐ 312 | 🐛 0 | 🌐 Go | 📅 2026-01-23 :  `Go `的另一个同步库（`Future, Promise, Locks`）。
* [go-floc](https://github.com/workanator/go-floc) ⭐ 269 | 🐛 1 | 🌐 Go | 📅 2021-08-10 :  轻松编排 `Go `语言协程
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) ⭐ 221 | 🐛 1 | 🌐 Go | 📅 2019-05-14 :  控制`Go`语言协程的执行顺序
* [artifex](https://github.com/borderstech/artifex) ⭐ 214 | 🐛 1 | 🌐 Go | 📅 2026-05-20 :   `Golang `的简单内存作业队列,使用基于`worker`的调度策略。
* [semaphore](https://github.com/marusama/semaphore) ⭐ 178 | 🐛 0 | 🌐 Go | 📅 2021-03-28 :  基于CAS的快速可调整大小的semaphore实现（比基于管道的semaphore实现更快）。
* [neilotoole/errgroup](https://github.com/neilotoole/errgroup) ⭐ 163 | 🐛 5 | 🌐 Go | 📅 2023-01-10 : ` sync/errgroup`的替代方案,限于N个`worker goroutine`池。
* [cyclicbarrier](https://github.com/marusama/cyclicbarrier) ⭐ 158 | 🐛 0 | 🌐 Go | 📅 2020-06-30 :   - `golang`的`CyclicBarrier`。
* [async](https://github.com/studiosol/async) ⭐ 140 | 🐛 2 | 🌐 Go | 📅 2020-11-19 : 安全的异步函数执行的方式,支持在出现pannic的情况下恢复它们。
* [gollback](https://github.com/vardius/gollback) ⭐ 121 | 🐛 1 | 🌐 Go | 📅 2023-02-16 :   异步简单函数工具,用于管理闭包和回调的执行
* [Hunch](https://github.com/AaronJan/Hunch) ⚠️ Archived :  Hunch提供的功能有。`All、First、Retry、Waterfall`等功能,让异步流控制更加直观。
* [threadpool](https://github.com/shettyh/threadpool) ⭐ 103 | 🐛 2 | 🌐 Go | 📅 2020-03-23`Golang`线程池的实现。
* [semaphore](https://github.com/kamilsk/semaphore) ⭐ 101 | 🐛 6 | 🌐 Go | 📅 2026-07-22 :  基于管道和上下文的加锁/解锁操作。
* [worker-pool](https://github.com/vardius/worker-pool) ⭐ 93 | 🐛 0 | 🌐 Go | 📅 2021-01-17 :  `Go`简单的异步`worker`池。
* [gpool](https://github.com/Sherifabdlnaby/gpool) ⭐ 89 | 🐛 0 | 🌐 Go | 📅 2026-07-11 :   管理一个可调整大小的上下文感知的`goroutine`池,并以这种方式来约束并发量。
* [goccm](https://github.com/zenthangplus/goccm) ⭐ 73 | 🐛 3 | 🌐 Go | 📅 2023-01-18 :  `Go `并发管理包,限制了允许并发运行的 `goroutine `的数量
* [nursery](https://github.com/arunsworld/nursery) ⭐ 71 | 🐛 1 | 🌐 Go | 📅 2021-07-08 :  `Go`中的结构化并发
* [routine](https://github.com/x-mod/routine) ⭐ 63 | 🐛 0 | 🌐 Go | 📅 2026-05-18 :   利用`context`的`go routine`实现。
* [gohive](https://github.com/loveleshsharma/gohive) ⭐ 54 | 🐛 2 | 🌐 Go | 📅 2023-11-19 :  高性能且易于使用的`goroutine`池。
* [kyoo](https://github.com/dirkaholic/kyoo) ⭐ 51 | 🐛 0 | 🌐 Go | 📅 2026-03-09 :  提供了一个无限的作业队列和并发的工作池。
* [go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) ⭐ 49 | 🐛 0 | 🌐 Go | 📅 2025-09-03 :  - 类似 `sync.WaitGroup `的错误处理和并发控制。
* [parallel-fn](https://github.com/rafaeljesus/parallel-fn) ⭐ 36 | 🐛 0 | 🌐 Go | 📅 2018-01-01 :  并行执行函数。
* [go-trylock](https://github.com/subchen/go-trylock) ⭐ 35 | 🐛 1 | 🌐 Go | 📅 2021-05-07 :  支持 `Golang` 的读写锁的 `TryLock`.
* [channelify](https://github.com/ddelizia/channelify) ⭐ 34 | 🐛 1 | 🌐 Go | 📅 2021-02-25 :  将你的函数转化为返回管道,以实现简单而强大的并行处理。
* [stl](https://github.com/ssgreg/stl) ⭐ 30 | 🐛 0 | 🌐 Go | 📅 2020-07-24 :  基于软件事务性内存（`STM`）并发控制机制的软件事务性锁。
* [breaker](https://github.com/kamilsk/breaker) ⭐ 21 | 🐛 0 | 📅 2021-07-11 :   采用了一种可以使执行流可中断的灵活的机制的包。
* [queue](https://github.com/AnikHasibul/queue) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2019-05-18 :  类似于`sync.WaitGroup`的队列包。帮助你控制和等待`goroutine`的执行,比如等待所有goroutine的结束等等。
* [conexec](https://github.com/ITcathyh/conexec) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2026-05-31 :   一个并发工具包,帮助你以一种高效和安全的方式并发执行函数。它支持指定整体超时以避免阻塞,并使用goroutine池来提高效率。
* [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2019-03-27 : 使用这个轻量级的库和简单的`API`来管理` goroutine` 池。
* [hands](https://github.com/duanckham/hands) ⭐ 10 | 🐛 1 | 🌐 Go | 📅 2025-08-26 :  用于控制多个`goroutine`的执行和返回策略的进程控制器。
* [oversight](https://cirello.io/oversight) :  `versight `是 `Erlang `监督树的完整实现。

***

## GUI

* [fyne](https://github.com/fyne-io/fyne) ⭐ 28,604 | 🐛 718 | 🌐 Go | 📅 2026-08-15 :   基于`Material Design`为`Go`设计的跨平台本地GUI。支持 Linux, macOS, Windows, BSD, iOS\` 和 Android.
* [webview](https://github.com/zserge/webview) ⭐ 14,198 | 🐛 210 | 🌐 C++ | 📅 2026-03-09 :   支持双向`JavaScript`绑定的跨平台 webview 窗口库（`Windows，macOS，Linux`）。
* [qt](https://github.com/therecipe/qt) ⭐ 10,803 | 🐛 372 | 🌐 Go | 📅 2024-03-04 : ` Qt`的`Go`语言接口 (支持 `Windows，macOS，Linux，Android，iOS，Sailfish OS， Raspberry Pi`)
* [robotgo](https://github.com/go-vgo/robotgo) ⭐ 10,771 | 🐛 3 | 🌐 Go | 📅 2026-07-29 :   跨平台`GUI`自动化工具，可以控制鼠标、键盘及其他设备
* [app](https://github.com/murlokswarm/app) ⭐ 8,952 | 🐛 53 | 🌐 Go | 📅 2026-08-12 :  使用`Go, HTML` 和 `CSS` 进行应用程序开发的库， 支持` MacOS, Windows`。
* [ui](https://github.com/andlabs/ui) ⭐ 8,358 | 🐛 126 | 🌐 Go | 📅 2022-05-19 :  跨平台的原生 GUI 库
* [walk](https://github.com/lxn/walk) ⭐ 7,097 | 🐛 345 | 🌐 Go | 📅 2024-01-21 :  `windows `应用程序开发工具包
* [go-astilectron](https://github.com/asticode/go-astilectron) ⚠️ Archived :  使用`GO`和`HTML/JS/CSS`（由Electron提供支持）构建跨平台GUI应用程序
* [systray](https://github.com/getlantern/systray) ⭐ 3,724 | 🐛 114 | 🌐 Go | 📅 2024-07-03 :  跨平台的` Go` 语言库,用于在桌面提醒区域放置按钮及菜单
* [go-sciter](https://github.com/sciter-sdk/go-sciter) ⭐ 2,621 | 🐛 98 | 🌐 C++ | 📅 2023-05-13 :   `Sciter` 的` Go` 语言接口，支持现代 GUI 程序开发的、嵌入式 HTML/CSS/脚本引擎。具有跨平台特性。
* [gotk3](https://github.com/gotk3/gotk3) ⭐ 2,212 | 🐛 122 | 🌐 Go | 📅 2025-11-24 : `GTK3`的Go语言接口
* [gosx-notifier](https://github.com/deckarep/gosx-notifier) ⭐ 589 | 🐛 11 | 🌐 Go | 📅 2020-02-27 :   `OSX` 桌面提醒库
* [gowd](https://github.com/dtylman/gowd) ⭐ 434 | 🐛 6 | 🌐 Go | 📅 2023-02-24 :  使用`Go, HTML, CSS `和` NW.js` 语言进行快速、简单的桌面UI开发。具有跨平台特性
* [trayhost](https://github.com/shurcooL/trayhost) ⭐ 261 | 🐛 7 | 🌐 Go | 📅 2023-11-26 :  跨平台的 `Go` 语言库,用于在主机系统任务条区域放置按钮及菜单
* [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) ⭐ 41 | 🐛 0 | 🌐 Go | 📅 2019-06-17 :  - `golang`中的OSX睡眠/唤醒通知库。
* [mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) ⭐ 33 | 🐛 3 | 🌐 Go | 📅 2023-10-13 : ` OSX` 库,用于通知机器上的任何（可插拔）活动。
* [go-appindicator](https://github.com/dawidd6/go-appindicator) ⚠️ Archived :  `libappindicator3 C`库的Go绑定。
* [go-gtk](http://mattn.github.io/go-gtk/) :  `GTK`的`Go`绑定。
* [Wails](https://wails.app) :  使用内置的 `HTML` 渲染器。

***

## 硬件

`与硬件交互的库、工具`

* 请参考 [go-hardware](https://github.com/rakyll/go-hardware) ⭐ 1,385 | 🐛 3 | 🌐 Go | 📅 2019-07-31

***

## Images 图像处理

* [gocv](https://github.com/hybridgroup/gocv) ⭐ 7,487 | 🐛 352 | 🌐 Go | 📅 2026-05-28 : 使用` OpenCV 3.3+` 的计算机视觉的 `Go` 包。
* [imaginary](https://github.com/h2non/imaginary) ⭐ 6,077 | 🐛 136 | 🌐 Go | 📅 2025-11-08 :  快速且简单的 `HTTP `微服务,用于图像缩放
* [imaging](https://github.com/disintegration/imaging) ⭐ 5,749 | 🐛 35 | 🌐 Go | 📅 2023-09-21 :  简单的`Go`图像处理包。
* [gg](https://github.com/fogleman/gg) ⭐ 4,795 | 🐛 97 | 🌐 Go | 📅 2023-12-14 :  使用`Go`编写的 `2D `渲染程序
* [bild](https://github.com/anthonynsimon/bild) ⭐ 4,203 | 🐛 17 | 🌐 Go | 📅 2026-08-01 :  汇集了使用 `Go `语言编写的图像处理算法
* [ln](https://github.com/fogleman/ln) ⭐ 3,376 | 🐛 12 | 🌐 Go | 📅 2019-07-19 : ` 3D` 图线艺术渲染
* [resize](https://github.com/nfnt/resize) ⚠️ Archived :  使用 `Go`语言编写的具有常见差值功能的图片缩放工具
* [bimg](https://github.com/h2non/bimg) ⭐ 3,025 | 🐛 180 | 🌐 Go | 📅 2025-01-23 :   利用`libvips`进行快速高效的图像处理
* [picfit](https://github.com/thoas/picfit) ⭐ 2,340 | 🐛 12 | 🌐 Go | 📅 2026-07-24 :  一个使用 `Go `语言编写的图片缩放服务器
* [svgo](https://github.com/ajstarks/svgo) ⭐ 2,248 | 🐛 16 | 🌐 Go | 📅 2022-12-09 :  用于生成 `SVG `的`Go`语言库
* [pt](https://github.com/fogleman/pt) ⭐ 2,101 | 🐛 11 | 🌐 Go | 📅 2019-03-21 :  光线追踪引擎
* [imagick](https://github.com/gographics/imagick) ⭐ 1,872 | 🐛 3 | 🌐 Go | 📅 2026-05-31 :   `ImageMagick `的 `MagickWand C `语言` API` 的 `Go `语言接口
* [smartcrop](https://github.com/muesli/smartcrop) ⭐ 1,854 | 🐛 9 | 🌐 Go | 📅 2023-07-06 :   - 为任意图片进行剪裁的工具
* [canvas](https://github.com/tdewolff/canvas) ⭐ 1,831 | 🐛 24 | 🌐 Go | 📅 2026-08-09 :  将矢量图形转换成 `PDF、SVG `或光栅化图像。
* [gift](https://github.com/disintegration/gift) ⭐ 1,796 | 🐛 9 | 🌐 Go | 📅 2023-09-20 :    图像处理过滤器包
* [go-opencv](https://github.com/lazywei/go-opencv) ⭐ 1,324 | 🐛 43 | 🌐 Go | 📅 2023-03-30 :  `OpenCV` 的 `Go `语言接口
* [geopattern](https://github.com/pravj/geopattern) ⭐ 1,285 | 🐛 3 | 🌐 Go | 📅 2019-01-08 :  从字符串创建优美的图样
* [stegify](https://github.com/DimitarPetrov/stegify) ⭐ 1,267 | 🐛 2 | 🌐 Go | 📅 2023-04-11 :  用于`LSB`隐写的`Go`工具,能够隐藏图像中的任何文
* [image2ascii](https://github.com/qeesung/image2ascii) ⭐ 980 | 🐛 13 | 🌐 Go | 📅 2022-08-29 :   将图像转换为`ASCII`码。
* [goimagehash](https://github.com/corona10/goimagehash) ⭐ 839 | 🐛 13 | 🌐 Go | 📅 2024-01-21 :  `Go`感知图像哈希包。
* [govatar](https://github.com/o1egl/govatar) ⭐ 607 | 🐛 1 | 🌐 Go | 📅 2022-10-04 :   用于生成有趣头像的库和命令行工具。
* [draft](https://github.com/lucasepe/draft) ⚠️ Archived :  使用简单的YAML语法为`GraphViz`生成高级微服务架构图。
* [mort](https://github.com/aldor007/mort) ⭐ 522 | 🐛 6 | 🌐 Go | 📅 2025-12-19 :  用`Go`编写的存储和图像处理服务器。
* [go-nude](https://github.com/koyachi/go-nude) ⭐ 422 | 🐛 3 | 🌐 Go | 📅 2023-10-11 :  使用 `Go` 语言进行裸替检测
* [steganography](https://github.com/auyer/steganography) ⭐ 353 | 🐛 0 | 🌐 Go | 📅 2026-05-08 :  用于`LSB`隐写的纯`Go`库。
* [gltf](https://github.com/qmuntal/gltf) ⭐ 286 | 🐛 3 | 🌐 Go | 📅 2026-05-28 :  高效且强大的`glTF 2.0`读取器、写入器和验证器。
* [mergi](https://github.com/noelyahan/mergi) ⭐ 243 | 🐛 2 | 🌐 Go | 📅 2024-11-05 :   用于图像处理的工具和` Go` 库（合并、裁剪、调整大小、水印、动画）。
* [darkroom](https://github.com/gojek/darkroom) ⭐ 235 | 🐛 12 | 🌐 Go | 📅 2026-05-13 :   图像代理,具有可更改的存储后端和图像处理引擎,注重速度和弹性。
* [rez](https://github.com/bamiaux/rez) ⚠️ Archived :  纯 `Go` 及`SIMD`实现的图像缩放库
* [img](https://github.com/hawx/img) ⭐ 158 | 🐛 4 | 🌐 Go | 📅 2015-05-01 :  图像操作工具精选集
* [go-cairo](https://github.com/ungerik/go-cairo) ⭐ 152 | 🐛 3 | 🌐 Go | 📅 2026-04-28 :   `cairo` 图形库的 `Go `语言接口
* [cameron](https://github.com/aofei/cameron) ⭐ 131 | 🐛 0 | 🌐 Go | 📅 2026-07-24 :  `Go`的头像生成器。
* [gridder](https://github.com/shomali11/gridder) ⭐ 81 | 🐛 0 | 🌐 Go | 📅 2021-09-30 :   基于网格的`2D`图形库。
* [go-gd](https://github.com/bolknote/go-gd) ⭐ 60 | 🐛 0 | 🌐 Go | 📅 2026-05-28 :  `GD `库的` Go` 语言接口
* [goimghdr](https://github.com/corona10/goimghdr) ⭐ 40 | 🐛 0 | 🌐 Go | 📅 2019-06-14 :  `imghdr `模块为 Go 确定文件中包含的图像类型。
* [tga](https://github.com/ftrvxmtrx/tga) ⚠️ Archived :  `tga `是一个`TARGA`图像格式解码/编码器
* [go-webcolors](https://github.com/jyotiska/go-webcolors) ⭐ 29 | 🐛 0 | 🌐 Go | 📅 2015-08-21 :  `webcolors` 库的`Go`语言接口
* [mpo](https://github.com/donatj/mpo) ⭐ 27 | 🐛 2 | 🌐 Go | 📅 2026-08-14 :  ` MPO 3D` 照片解码与转换工具.

## 物联网(IOT)

* [gobot](https://github.com/hybridgroup/gobot/) ⭐ 9,449 | 🐛 99 | 🌐 Go | 📅 2026-01-07 : ` Gobot` 是一个用于机器人,物理计算以及物联网的库
* [flogo](https://github.com/tibcosoftware/flogo) ⭐ 2,492 | 🐛 128 | 🌐 CSS | 📅 2024-04-24 :` FloGo`是一个用于物联网 `Edge App `及集成的开源框架
* [gatt](https://github.com/paypal/gatt) ⭐ 1,164 | 🐛 49 | 🌐 Go | 📅 2022-08-17 :  `Gatt`是一个用于创建低功耗蓝牙外设的库
* [connectordb](https://github.com/connectordb/connectordb) ⭐ 422 | 🐛 22 | 🌐 Go | 📅 2022-06-27 :  针对`iot`的开源物联网平台
* [devices](https://github.com/goiot/devices) ⭐ 266 | 🐛 9 | 🌐 Go | 📅 2016-07-10 :  管理物联网设备的套件库
* [huego](https://github.com/amimof/huego) ⭐ 262 | 🐛 10 | 🌐 Go | 📅 2023-06-30 :  适用于 `Go `的广泛的 `Philips Hue `客户端库。
* [sensorbee](https://github.com/sensorbee/sensorbee) ⭐ 231 | 🐛 39 | 🌐 Go | 📅 2019-11-04 :   轻量级物联网流处理引擎
* [iot](https://github.com/vaelen/iot/) ⭐ 68 | 🐛 0 | 🌐 Go | 📅 2019-11-08 :   `IoT`是实现`Google IoT Core`设备的简单框架。
* [eywa](https://github.com/xcodersun/eywa) ⭐ 66 | 🐛 9 | 🌐 Go | 📅 2017-04-12 :   ` Eywa` 是一个持续追踪所有连接设备的连接管理器
* [mainflux](https://github.com/Mainflux/mainflux) ⚠️ Archived :  工业物联网消息传递和设备管理服务器。
* [periph](https://periph.io/) :  外设`I/O,`用于连接低级板卡设施。

## 作业调度

* [gocron](https://github.com/go-co-op/gocron) ⭐ 7,133 | 🐛 2 | 🌐 Go | 📅 2026-07-21 : 简单流畅的`Go`作业调度。这是·`jasonlvhit/gocron`·\`的一个积极维护的fork.
* [go-quartz](https://github.com/reugn/go-quartz) ⭐ 2,013 | 🐛 4 | 🌐 Go | 📅 2026-01-20 :  简单、零依赖的`Go`调度库。
* [JobRunner](https://github.com/bamzi/jobrunner) ⭐ 1,087 | 🐛 11 | 🌐 Go | 📅 2020-11-14 :  智能且功能丰富的`cron`任务调度器,内置任务队列和实时监控。
* [gron](https://github.com/roylee0704/gron) ⭐ 1,034 | 🐛 9 | 🌐 Go | 📅 2023-05-05 :   使用简单的 `Go API` 定义基于时间的任务,`Gron `的调度器将相应地运行它们。
* [jobs](https://github.com/albrow/jobs) ⚠️ Archived :  持久而灵活的后台作业库。
* [scheduler](https://github.com/carlescere/scheduler) ⭐ 469 | 🐛 6 | 🌐 Go | 📅 2022-06-23 : `  Cronjobs`调度系统。
* [go-cron](https://github.com/rk/go-cron) ⭐ 239 | 🐛 0 | 🌐 Go | 📅 2020-02-10 :  ` Go`的简单`Cron`库,它可以在不同的时间间隔执行闭包或函数,主要用于web应用程序和长期运行的守护进程。
* [clockwerk](http://github.com/onatm/clockwerk) ⭐ 183 | 🐛 0 | 🌐 Go | 📅 2024-11-05 :  使用简单、流畅的语法来调度周期性作业的`Go`包。
* [leprechaun](https://github.com/kilgaloon/leprechaun) ⭐ 106 | 🐛 12 | 🌐 Go | 📅 2022-07-12 :  工作调度器,支持`webhooks、crons`和经典调度系统。
* [clockwork](https://github.com/whiteShtef/clockwork) ⭐ 27 | 🐛 2 | 🌐 Go | 📅 2020-10-01 :  `Go`中简单直观的作业调度库。

***

## JSON

* [GJSON](https://github.com/tidwall/gjson) ⭐ 15,553 | 🐛 100 | 🌐 Go | 📅 2026-05-14 :  用一行代码获取`JSON`值。
* [gojson](https://github.com/ChimeraCoder/gojson) ⭐ 2,689 | 🐛 41 | 🌐 Go | 📅 2021-07-30 :  从示例 `JSON `自动生成 `Go`结构体定义的库。
* [kazaam](https://github.com/Qntfy/kazaam) ⭐ 293 | 🐛 23 | 🌐 Go | 📅 2022-06-06 :   转换任意`json`文档的的`API`库。
* [ajson](https://github.com/spyzhov/ajson) ⭐ 291 | 🐛 19 | 🌐 Go | 📅 2024-11-25 :  `golang`实现的支持`JSONPath`的抽象`JSON`格式解析库。
* [gojq](https://github.com/elgs/gojq) ⭐ 191 | 🐛 1 | 🌐 Go | 📅 2023-06-28 :  `Golang`中的`JSON`查询库。
* [jettison](https://github.com/wI2L/jettison) ⭐ 180 | 🐛 0 | 🌐 Go | 📅 2023-07-28 :  用于`Go`的高性能、无反射的`JSON`编码器。
* [json2go](https://github.com/m-zajac/json2go) ⭐ 142 | 🐛 5 | 🌐 Go | 📅 2026-04-06 :  高级`JSON`到`Go`结构的转换。提供能够解析多个`JSON`文档并创建适合所有JSON文档的结构的包。
* [gjo](https://github.com/skanehira/gjo) ⭐ 132 | 🐛 1 | 🌐 Go | 📅 2021-04-18 :  用于创建`JSON`对象的小工具。
* [JayDiff](https://github.com/yazgazan/jaydiff) ⭐ 111 | 🐛 2 | 🌐 Go | 📅 2026-04-21 :  用`Go`编写的`JSON`差异比较工具。
* [jsongo](https://github.com/ricardolonga/jsongo) ⭐ 108 | 🐛 1 | 🌐 Go | 📅 2021-10-04 :  ` Fluent API,`使其更容易创建`Json`对象。
* [jsonf](https://github.com/miolini/jsonf) ⭐ 64 | 🐛 0 | 🌐 Go | 📅 2020-12-13 :  用于高亮格式化和结构查询JSON的控制台工具。
* [go-respond](https://github.com/nicklaw5/go-respond) ⭐ 55 | 🐛 1 | 🌐 Go | 📅 2021-09-24 :  用于处理常见`HTTP JSON`响应的`Go`包。
* [mp](https://github.com/sanbornm/mp) ⭐ 47 | 🐛 1 | 🌐 Go | 📅 2016-05-11 :  简单的 `cli `电子邮件解析器，能够接受标准输入并输出`JSON`日志
* [mapslice-json](https://github.com/mickep76/mapslice-json) ⭐ 20 | 🐛 6 | 🌐 Go | 📅 2024-03-08 : 用于有序地对`JSON`中的`map`结构进行`marshal/unmarshal`。
* [epoch](https://github.com/vtopc/epoch) ⭐ 17 | 🐛 1 | 🌐 Go | 📅 2024-02-25 :  包含用于将`Unix`时间戳,`epoch`转换为JSON中的内置时间类型的处理库。
* [dynjson](https://github.com/cocoonspace/dynjson) ⭐ 16 | 🐛 1 | 🌐 Go | 📅 2023-04-12 :  向客户端提供自定义的`JSON`格式的动态`API`库
* [go-jsonerror](https://github.com/ddymko/go-jsonerror) ⭐ 16 | 🐛 1 | 🌐 Go | 📅 2019-10-09 :   `Go-JsonError`的目的是让我们能够轻松创建遵循`JsonApi`规范的`json`响应错误。
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2016-11-17 :  基于`JSON API`错误引用的`Go `语言封装。
* [jsonhal](https://github.com/RichardKnop/jsonhal) ⭐ 13 | 🐛 1 | 🌐 Go | 📅 2020-03-24 :  ,用于将自定义的结构体`marshal`为兼容`HAL`的`JSON response`的库。
* [jzon](https://github.com/zerosnake0/jzon) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2024-10-30 :  兼容标准`json`库的`JSON`库。
* [ej](https://github.com/lucassscaravelli/ej) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2020-04-07 :   从不同的数据写入和读取`JSON`的库。
* [JSON-to-Go](https://mholt.github.io/json-to-go/) :   将`JSON`转换为`Go`结构

***

## Logging 日志库

* [logrus](https://github.com/sirupsen/logrus) ⭐ 25,751 | 🐛 42 | 🌐 Go | 📅 2026-08-13 : `Go`的结构化日志记录器。
* [zap](https://github.com/uber-go/zap) ⭐ 24,630 | 🐛 188 | 🌐 Go | 📅 2026-08-05 :  快速的、结构化的、分级的日志库
* [zerolog](https://github.com/rs/zerolog) ⭐ 12,488 | 🐛 143 | 🌐 Go | 📅 2026-08-10 :  零内存分配 的`JSON `日志库.
* [spew](https://github.com/davecgh/go-spew) ⭐ 6,402 | 🐛 69 | 🌐 Go | 📅 2024-04-06 :  - 为 `Go `语言的数据结构实现了一个整洁的打印功能,有助于调试
* [lumberjack](https://github.com/natefinch/lumberjack) ⭐ 5,460 | 🐛 102 | 🌐 Go | 📅 2024-08-05 :  简单的循环日志工具。
* [glog](https://github.com/golang/glog) ⭐ 3,599 | 🐛 3 | 🌐 Go | 📅 2025-04-29 :  `Go`的分级日志
* [tail](https://github.com/hpcloud/tail) ⭐ 2,780 | 🐛 78 | 🌐 Go | 📅 2022-10-25 :  这个 `Go `语言软件包力争模拟 `BSD tail `的功能
* [seelog](https://github.com/cihub/seelog) ⭐ 1,633 | 🐛 40 | 🌐 Go | 📅 2019-03-04 :  灵活的、解耦的、格式化的日志库
* [log](https://github.com/apex/log) ⭐ 1,376 | 🐛 48 | 🌐 Go | 📅 2023-11-03 :   Go的结构化日志包。
* [log15](https://github.com/inconshreveable/log15) ⭐ 1,104 | 🐛 42 | 🌐 Go | 📅 2026-05-13 :  简单、强大的`Go`日志记录。
* [phuslu/log](https://github.com/phuslu/log) ⭐ 869 | 🐛 13 | 🌐 Go | 📅 2026-07-22 :  - 结构化日志系统。
* [httpretty](https://github.com/henvic/httpretty) ⭐ 450 | 🐛 3 | 🌐 Go | 📅 2026-08-10 :  将常规的 `HTTP` 请求漂亮地打印在终端上用于调试（类似于 `http.DumpRequest`）。
* [onelog](https://github.com/francoispqt/onelog) ⭐ 412 | 🐛 2 | 🌐 Go | 📅 2019-03-06 :  `Onelog`是一个简单但非常高效的JSON日志库。它是目前所有场景下最快的JSON日志器。同时,它也是所需最少内存分配的库。
* [sqldb-logger](https://github.com/simukti/sqldb-logger) ⭐ 379 | 🐛 12 | 🌐 Go | 📅 2025-12-05 :  -用于`Go SQL`数据库驱动的日志记录器,无需修改现有的`*sql.DB`标准用法。
* [logutils](https://github.com/hashicorp/logutils) ⭐ 371 | 🐛 5 | 🌐 Go | 📅 2026-05-11 :  对 `Go `语言标准日志工具进行了扩展,使其更好用
* [logxi](https://github.com/mgutz/logxi) ⭐ 355 | 🐛 21 | 🌐 Go | 📅 2020-04-14 :  十二要素 app 日志工具,非常快速。
* [log](https://github.com/go-playground/log) ⭐ 293 | 🐛 1 | 🌐 Go | 📅 2023-08-17 :  简单、可配置、可扩展的`Go`结构化日志库。
* [rollingwriter](https://github.com/arthurkiller/rollingWriter) ⭐ 292 | 🐛 10 | 🌐 Go | 📅 2023-10-16 :   ` RollingWriter`是一个具有自动轮转功能的io.Writer实现,它有多种策略来提供日志文件旋转。
* [go-logger](https://github.com/apsdehal/go-logger) ⭐ 288 | 🐛 3 | 🌐 Go | 📅 2019-05-15 :  支持日志分级的简单的日志工具
* [logur](https://github.com/logur/logur) ⚠️ Archived :  日志记录接口和日志记录最佳实践的整合,它对诸多知名库如[logrus](https://github.com/sirupsen/logrus) ⭐ 25,751 | 🐛 42 | 🌐 Go | 📅 2026-08-13、[go-kit log](https://github.com/go-kit/kit/tree/master/log) ⭐ 27,418 | 🐛 60 | 🌐 Go | 📅 2024-07-19、[zap](https://github.com/uber-go/zap) ⭐ 24,630 | 🐛 188 | 🌐 Go | 📅 2026-08-05 ， [zerolog](https://github.com/rs/zerolog) ⭐ 12,488 | 🐛 143 | 🌐 Go | 📅 2026-08-10等的功能进行了集成
* [glg](https://github.com/kpango/glg) ⭐ 193 | 🐛 11 | 🌐 Go | 📅 2026-01-14 : 简单、快速、分级的日志库
* [logger](https://github.com/azer/logger) ⭐ 159 | 🐛 0 | 🌐 Go | 📅 2026-01-29 :  日志库。
* [xlog](https://github.com/rs/xlog) ⭐ 141 | 🐛 3 | 🌐 Go | 📅 2024-07-04 :  结构化日志库
* [ozzo-log](https://github.com/go-ozzo/ozzo-log) ⭐ 123 | 🐛 9 | 🌐 Go | 📅 2021-01-07 :   高性能日志库,支持日志分级、分类及过滤。可以将过滤后的信息发送到不同的目的地(例如： 控制台、网络、邮箱).
* [log-voyage](https://github.com/firstrow/logvoyage) ⭐ 94 | 🐛 9 | 🌐 Go | 📅 2017-05-24 :用`golang`编写的全功能日志库。
* [go-cronowriter](https://github.com/utahta/go-cronowriter) ⭐ 56 | 🐛 3 | 🌐 Go | 📅 2021-03-16 :  对日志文件基于当前日期和时间进行自动循环写入的库,类似 `cronolog`.
* [gone/log](https://github.com/One-com/gone/tree/master/log) ⭐ 51 | 🐛 0 | 🌐 Go | 📅 2021-05-24 :  快速、可扩展、全功能、兼容标准库的日志库
* [stdlog](https://github.com/alexcesaro/log) ⭐ 48 | 🐛 1 | 🌐 Go | 📅 2015-09-15 :   `Stdlog `是一个面向对象的库,提供了分级日志功能,对于定时任务很有用.
* [journald](https://github.com/ssgreg/journald) ⭐ 46 | 🐛 0 | 🌐 Go | 📅 2021-03-05 :  `systemd` 日志的本地日志`API`的 `Go `实现。
* [go-log](https://github.com/ian-kent/go-log) ⭐ 42 | 🐛 3 | 🌐 Go | 📅 2018-03-31 :  `Go`中的`Log4j`实现。
* [logex](https://github.com/chzyer/logex) ⭐ 42 | 🐛 2 | 🌐 Go | 📅 2024-04-02 : ` Golang`日志库,支持跟踪和级别,由标准日志库封装。
* [gologger](https://github.com/sadlil/gologger) ⚠️ Archived :  简单易用的日志库,可以在彩色控制台、文件或 `Elasticsearch `中记录
* [go-log](https://github.com/siddontang/go-log) ⭐ 38 | 🐛 3 | 🌐 Go | 📅 2019-02-21 :  日志库支持级别和多处理程序。
* [mlog](https://github.com/jbrodriguez/mlog) ⭐ 33 | 🐛 2 | 🌐 Go | 📅 2018-08-05 :  简单的日志模块,可以分5级并有一个可选的循环日志文件记录功能,支持 stdout/stderr 输出.
* [distillog](https://github.com/amoghe/distillog) ⭐ 31 | 🐛 1 | 🌐 Go | 📅 2018-07-26 :  分级日志记录库（可以把它想象成 `stdlib + log levels`）。
* [logrusly](https://github.com/sebest/logrusly) ⭐ 29 | 🐛 3 | 🌐 Go | 📅 2021-07-27 :  [logrus](https://github.com/sirupsen/logrus) ⭐ 25,751 | 🐛 42 | 🌐 Go | 📅 2026-08-13插件,用于将错误发送到[Loggly](https://www.loggly.com/)
* [log](https://github.com/teris-io/log) ⭐ 25 | 🐛 0 | 🌐 Go | 📅 2017-12-04 :  结构化日志接口。
* [gomol](https://github.com/aphistic/gomol) ⚠️ Archived :  支持多种输出,结构化的日志模块,可以扩展它的输出
* [kemba](https://github.com/clok/kemba) ⭐ 18 | 🐛 9 | 🌐 Go | 📅 2026-08-13 :  受[debug](https://github.com/visionmedia/debug) ⭐ 11,451 | 🐛 92 | 🌐 JavaScript | 📅 2026-04-01 启发的小型调试日志工具,非常适合CLI工具和应用程序。
* [glo](https://github.com/lajosbencz/glo) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2019-01-23 :  分级记录日志的库
* [logmatic](https://github.com/borderstech/logmatic) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2021-01-11 :  ` Golang`的彩色日志记录器,具有动态日志级别配置功能。
* [logrusiowriter](https://github.com/cabify/logrusiowriter) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2024-10-09 :  使用 `logrus logger` 的 `io.Writer` 实现。
* [go-log](https://github.com/subchen/go-log) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2018-05-19 :   简单且可配置的`go`日志库,包括分级、格式化和多项输出的特性。
* [logo](https://github.com/mbndr/logo) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2020-12-27 :  `Golang`的日志记录库,可配置不同的写入器。
* [go-log](https://github.com/pieterclaerhout/go-log) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2026-04-07 :  一个包含`rack traces`、对象转储和可选时间戳的日志库。
* [log](https://github.com/aerogo/log) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2019-10-26 :   `O(1)`复杂度的日志系统,允许你将一个日志连接到多个输出(例如 `stdout`、文件和一个 `TCP` 连接)。
* [logdump](https://github.com/ewwwwwqm/logdump) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2018-04-02 :  用于多级日志记录的软件包。
* [xlog](https://github.com/xfxdev/xlog) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2019-01-15 :  插件架构以及灵活的日志系统,具有日志等级控制,多日志目标以及自定义日志格式功能

***

## 机器学习

* [GoLearn](https://github.com/sjwhitworth/golearn) ⭐ 9,437 | 🐛 89 | 🌐 Go | 📅 2024-01-15 : `Go`语言通用机器学习库
* [gorgonia](https://github.com/gorgonia/gorgonia) ⭐ 5,922 | 🐛 124 | 🌐 Go | 📅 2024-08-12 :  基于图的计算库,类似于 `Theano`。提供了一些原型用于构建各种个样的机器学习和神经网络算法
* [gosseract](https://github.com/otiai10/gosseract) ⭐ 3,128 | 🐛 32 | 🌐 Go | 📅 2026-01-16 :    用于`OCR`（光学字符识别）的`Go`包,使用`Tesseract C++`库。
* [tfgo](https://github.com/galeone/tfgo) ⭐ 2,491 | 🐛 20 | 🌐 Go | 📅 2024-03-13 :   易于使用的`Tensorflow `` g`o语言封装：简化了官方`Tensorflow Go`的使用。
* [goml](https://github.com/cdipaolo/goml) ⭐ 1,614 | 🐛 4 | 🌐 Go | 📅 2022-07-15 :  即时`go`语言机器学习库
* [eaopt](https://github.com/MaxHalford/eaopt) ⭐ 906 | 🐛 8 | 🌐 Go | 📅 2025-01-27 :  进化优化库。
* [onnx-go](https://github.com/owulveryck/onnx-go) ⭐ 905 | 🐛 44 | 🌐 Go | 📅 2024-09-02 :  `Open Neural Network Exchange (ONNX)`的`Go`接口。
* [bayesian](https://github.com/jbrukh/bayesian) ⭐ 814 | 🐛 0 | 🌐 Go | 📅 2025-12-07 :  贝叶斯分类器
* [ocrserver](https://github.com/otiai10/ocrserver) ⭐ 767 | 🐛 4 | 🌐 Go | 📅 2021-08-05 :   简单的`OCR API`服务器,很容易被`Docker`和`Heroku`部署。
* [CloudForest](https://github.com/ryanbressler/CloudForest) ⭐ 747 | 🐛 34 | 🌐 Go | 📅 2022-02-05 :  纯 `Go `语言编写的快速、灵活、多线程决策树
* [gobrain](https://github.com/goml/gobrain) ⭐ 568 | 🐛 1 | 🌐 Go | 📅 2020-12-12 :  用`go`语言编写的神经网络。
* [go-deep](https://github.com/patrikeh/go-deep) ⭐ 557 | 🐛 2 | 🌐 Go | 📅 2024-07-11 :  用`Go`编写的功能丰富的神经网络库。
* [regommend](https://github.com/muesli/regommend) ⭐ 312 | 🐛 0 | 🌐 Go | 📅 2019-08-07 :   推荐系统及协同过滤引擎
* [Goptuna](https://github.com/c-bata/goptuna) ⭐ 279 | 🐛 19 | 🌐 Go | 📅 2025-08-12 :  用`Go`编写的黑盒函数的贝叶斯优化框架。一切都将被优化。
* [goga](https://github.com/tomcraven/goga) ⭐ 223 | 🐛 2 | 🌐 Go | 📅 2022-04-13 :  `Go` 语言遗传算法库
* [goRecommend](https://github.com/timkaye11/goRecommend) ⭐ 205 | 🐛 0 | 🌐 Go | 📅 2014-07-29 :  `Go` 语言推荐算法库
* [go-galib](https://github.com/thoj/go-galib) ⭐ 202 | 🐛 0 | 🌐 Go | 📅 2015-12-28 :  `Go `语言编写的遗传算法库
* [shield](https://github.com/eaigner/shield) ⭐ 160 | 🐛 5 | 🌐 Go | 📅 2020-03-04 : `go`语言实现的贝叶斯文本分类器,具有灵活的标记器和存储后端。
* [go-fann](https://github.com/white-pony/go-fann) ⭐ 119 | 🐛 2 | 🌐 Go | 📅 2015-02-03 :   快速人工神经网络库`(FANN)`的 `Go` 语言借口.
* [goscore](https://github.com/asafschers/goscore) ⭐ 101 | 🐛 3 | 🌐 Go | 📅 2019-08-23 :  用于 `PMML` 的 `Go` 评分` API`。
* [GoMind](https://github.com/surenderthakran/gomind) ⭐ 98 | 🐛 7 | 🌐 Go | 📅 2022-05-08 :   Go 中的一个简单的神经网络库。
* [fonet](https://github.com/Fontinalis/fonet) ⭐ 86 | 🐛 2 | 🌐 Go | 📅 2021-06-01 :  用`Go`编写的深度神经网络库。
* [gonet](https://github.com/dathoangnd/gonet) ⭐ 82 | 🐛 0 | 🌐 Go | 📅 2020-04-05 :  `Go`的神经网络。
* [neat](https://github.com/jinyeom/neat) ⚠️ Archived :  即插即用的并行` Go` 语言框架,用于增强拓扑神经网络 (NEAT).
* [neural-go](https://github.com/schuyler/neural-go) ⭐ 73 | 🐛 1 | 🌐 Go | 📅 2020-08-31 :  `Go `语言实现的多层感知神经网络,通过反向传播算法进行训练.
* [libsvm](https://github.com/datastream/libsvm) ⭐ 72 | 🐛 1 | 🌐 Go | 📅 2016-05-09 :  `libsvm`的` Go` 语言版本,基于 `LIBSVM 3.14.`
* [go-pr](https://github.com/daviddengcn/go-pr) ⭐ 68 | 🐛 0 | 🌐 Go | 📅 2013-06-08 : `Go`语言模式识别库
* [randomforest](https://github.com/malaschitz/randomForest) ⭐ 61 | 🐛 1 | 🌐 Go | 📅 2025-11-01 :   简单易用的 `Go `随机森林库。
* [Varis](https://github.com/Xamber/Varis) ⭐ 55 | 🐛 0 | 🌐 Go | 📅 2018-08-02 : `Golang`神经网络。
* [golinear](https://github.com/danieldk/golinear) ⚠️ Archived : ` liblinear` 库的 `Go `语言接口
* [go-cluster](https://github.com/e-XpertSolutions/go-cluster) ⭐ 44 | 🐛 0 | 🌐 Go | 📅 2022-11-29 :   `k-modes`和`k-prototypes`聚类算法的`Go`实现。
* [godist](https://github.com/e-dard/godist) ⭐ 43 | 🐛 0 | 🌐 Go | 📅 2015-05-11 :   各种概率分布以及相关方法库。
* [evoli](https://github.com/khezen/evoli) ⭐ 33 | 🐛 21 | 🌐 Go | 📅 2021-10-27 :   遗传算法和粒子群优化库。
* [probab](https://github.com/ThePaw/probab) ⭐ 22 | 🐛 3 | 🌐 Go | 📅 2015-09-14 :  概率分布函数。贝叶斯推理。用纯`Go`编写。
* [gorse](https://github.com/zhenghaoz/gorse) :  用`Go`编写的基于协作过滤的离线推荐系统后台。

***

## 消息系统

* [Asynq](https://github.com/hibiken/asynq) ⭐ 13,637 | 🐛 291 | 🌐 Go | 📅 2026-06-22 :   建立在 `Redis` 之上，为 `Go` 提供的简单、可靠、高效的分布式任务队列,。
* [sarama](https://github.com/Shopify/sarama) ⭐ 12,508 | 🐛 31 | 🌐 Go | 📅 2026-08-12 :  用于 `Apache Kafka `的库
* [Centrifugo](https://github.com/centrifugal/centrifugo) ⭐ 10,630 | 🐛 24 | 🌐 Go | 📅 2026-08-12 :  实时消息服务器
* [gorush](https://github.com/appleboy/gorush) ⭐ 8,756 | 🐛 67 | 🌐 Go | 📅 2026-07-25  通知推送服务器,使用 [APNs2](https://github.com/sideshow/apns2) ⭐ 3,187 | 🐛 32 | 🌐 Go | 📅 2025-07-22 和 [GCM](https://github.com/google/go-gcm) ⚠️ Archived 。
* [Benthos](https://github.com/Jeffail/benthos) ⭐ 8,733 | 🐛 320 | 🌐 Go | 📅 2026-08-16 : 在一系列协议之间建立消息流`go`代码库
* [machinery](https://github.com/RichardKnop/machinery) ⭐ 7,970 | 🐛 247 | 🌐 Go | 📅 2025-11-15 :  异步任务队列,基于分布式消息处理
* [NATS Go Client](https://github.com/nats-io/nats) ⭐ 6,723 | 🐛 157 | 🌐 Go | 📅 2026-08-14 :   原生的 `oplog/replication `系统,用于 `REST APIs`场景
* [go-socket.io](https://github.com/googollee/go-socket.io) ⚠️ ArchivedGo 语言的 `socket.io`库 ,一个实时应用框架.
* [Mercure](https://github.com/dunglas/mercure) ⭐ 5,299 | 🐛 19 | 🌐 Go | 📅 2026-08-16 :   使用`Mercure`协议（建立在`Server-Sent Events`之上）来调度服务器发送的更新的代码库。
* [Confluent Kafka Golang Client](https://github.com/confluentinc/confluent-kafka-go) ⭐ 5,163 | 🐛 277 | 🌐 HTML | 📅 2026-08-15   是`Confluent`为`Apache Kafka`和`Confluent Platform`开发的`Golang`客户端。
* [melody](https://github.com/olahol/melody) ⭐ 4,081 | 🐛 14 | 🌐 Go | 📅 2025-10-28 :  用于处理`websocket`会话的简约框架,包括广播和自动`ping/pong`处理。
* [APNs2](https://github.com/sideshow/apns2) ⭐ 3,187 | 🐛 32 | 🌐 Go | 📅 2025-07-22 :   `go`语言实现的基于`HTTP/2`苹果推送通知提供服务，可以向`iOS`、`tvOS`、`Safari`和`OSX`应用程序发送推送通知
* [go-nsq](https://github.com/nsqio/go-nsq) ⭐ 2,658 | 🐛 28 | 🌐 Go | 📅 2025-07-23 :   `NSQ `官方 `Go` 语言库
* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) ⭐ 2,071 | 🐛 5 | 🌐 Go | 📅 2017-06-07 :  Gopush-cluster 是一个`Go`语言实现的支持集群的`comet`服务（支持` websocket`和`tcp`协议）
* [EventBus](https://github.com/asaskevich/EventBus) ⭐ 1,983 | 🐛 28 | 🌐 Go | 📅 2024-06-19 :   轻量级事件库,支持异步
* [Beaver](https://github.com/Clivern/Beaver) ⭐ 1,581 | 🐛 16 | 🌐 Go | 📅 2026-08-13 :  实时消息服务器,用于在网络和移动应用中构建可扩展的应用内通知、多人游戏、聊天应用。
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) ⭐ 1,559 | 🐛 71 | 🌐 Go | 📅 2026-08-11 :  基于 `Redis` 的统一推服务,用于服务器端向移动客户端推送消息
* [mangos](https://github.com/go-mangos/mangos) ⚠️ Archived :   纯 `Go `语言实现的 `Nanomsg ("Scalable Protocols")`
* [zmq4](https://github.com/pebbe/zmq4) ⭐ 1,260 | 🐛 58 | 🌐 Go | 📅 2025-07-06 :  `ZeroMQ version 4`的 `GO `语言接口。也有适用于[version 3](https://github.com/pebbe/zmq3) ⭐ 132 | 🐛 1 | 🌐 Go | 📅 2025-05-11 及 [version 2](https://github.com/pebbe/zmq2) ⭐ 19 | 🐛 1 | 🌐 Go | 📅 2025-05-11 的
* [dbus](https://github.com/godbus/dbus) ⭐ 1,191 | 🐛 54 | 🌐 Go | 📅 2026-05-01 : ` D-Bus`的 `Go` 语言接口
* [Gollum](https://github.com/trivago/gollum) ⚠️ Archived :  一个` n:m` 的多路复用器,从不同的源汇聚消息并向目标进行广播
* [golongpoll](https://github.com/jcuga/golongpoll) ⭐ 664 | 🐛 0 | 🌐 Go | 📅 2023-08-20 : ` HTTP` 长轮询服务器库,让 web 发布与订阅变的更简单.
* [emitter](https://github.com/olebedev/emitter) ⭐ 532 | 🐛 4 | 🌐 Go | 📅 2023-04-11 : 通过`Go`语言的方式发送事件消息,可以使用通配符,断言,取消发送等优秀特性。
* [pubsub](https://github.com/tuxychandru/pubsub) ⭐ 453 | 🐛 1 | 🌐 Go | 📅 2024-05-22 :  简单的 `pubsub `软件包
* [Glue](https://github.com/desertbit/glue) ⭐ 421 | 🐛 4 | 🌐 Go | 📅 2020-05-20 :  健壮的 `Go `和 `Javascript Socket` 库 (可以用来替代` Socket.io`).
* [Bus](https://github.com/mustafaturan/bus) ⭐ 369 | 🐛 0 | 🌐 Go | 📅 2023-05-14 :  用于内部通信的简约型消息总线实现。
* [rabtap](https://github.com/jandelgado/rabtap) ⭐ 288 | 🐛 4 | 🌐 Go | 📅 2026-08-15 :  -` RabbitMQ` 瑞士军刀 `cli `应用。
* [messagebus](https://github.com/vardius/message-bus) ⭐ 286 | 🐛 3 | 🌐 JavaScript | 📅 2021-01-14 :  ` messagebus`是一个Go简单的异步消息系统,用于事件源、`CQRS、DDD`等场景
* [guble](https://github.com/smancke/guble) ⭐ 161 | 🐛 5 | 🌐 Go | 📅 2017-10-31 :  使用通知推送(`Google Firebase Cloud Messaging, Apple Push Notification services, SMS)、websockets 、REST API `的消息服务器。提供了分布式操作和消息持久化特性
* [hub](https://github.com/leandro-lugaresi/hub) ⭐ 147 | 🐛 0 | 🌐 Go | 📅 2026-07-17 :   用于 `Go` 应用程序的消息/事件汇聚,使用发布/订阅模式,支持像 `rabbitMQ` 的使用模式。
* [redisqueue](https://github.com/robinjoseph08/redisqueue) ⭐ 138 | 🐛 7 | 🌐 Go | 📅 2024-03-08 :   `redisqueue` 提供了一个使用 `Redis `流的队列，可以用于生产者和消费者模式。
* [oplog](https://github.com/dailymotion/oplog) ⭐ 111 | 🐛 2 | 🌐 Go | 📅 2024-09-27 : 用于 `REST API`场景的通用oplog/copy系统。
* [rabbus](https://github.com/rafaeljesus/rabbus) ⭐ 98 | 🐛 6 | 🌐 Go | 📅 2019-07-23 :  ` amqp`交换队列的简易封装。
* [go-mq](https://github.com/cheshir/go-mq) ⭐ 91 | 🐛 1 | 🌐 Go | 📅 2023-10-09 :  具有声明式配置的`RabbitMQ`客户端。
* [drone-line](https://github.com/appleboy/drone-line) ⭐ 81 | 🐛 2 | 🌐 Go | 📅 2023-02-25 :  通过软件包,`docker `或是 `Drone CI`来发送 [Line](https://at.line.me/en) 通知
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) ⭐ 79 | 🐛 2 | 🌐 Go | 📅 2018-02-15 :  针对 `NSQ 的topic`和`channel`进行了简单的封装
* [go-notify](https://github.com/TheCreeper/go-notify) ⭐ 71 | 🐛 2 | 🌐 Go | 📅 2020-12-11 :  `freedesktop`通知规范的本地实现
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) ⭐ 70 | 🐛 1 | 🌐 Go | 📅 2017-12-07 : `RapidMQ`是一个轻量级,可靠的本地消息队列管理库
* [go-res](https://github.com/jirenius/go-res) ⭐ 69 | 🐛 8 | 🌐 Go | 📅 2026-05-12 :   用于构建 `REST`/实时服务的包,使用` NATS` 和 `Resgate `实现客户端无缝同步。
* [Commander](https://github.com/jeroenrinzema/commander) ⭐ 68 | 🐛 4 | 🌐 Go | 📅 2025-12-05 :   一个高级事件驱动库，支持消费者/生产者模式,支持各种消息系统,如Apache Kafka。
* [event](https://github.com/agoalofalife/event) ⭐ 62 | 🐛 0 | 🌐 Go | 📅 2018-02-19 :  观察者模式的`go`语言实现
* [ami](https://github.com/kak-tus/ami) ⭐ 34 | 🐛 0 | 🌐 Go | 📅 2020-04-02 :   基于`Redis`集群可靠队列的`Go`客户端。
* [gosd](https://github.com/alexsniffin/gosd) ⭐ 26 | 🐛 0 | 🌐 Go | 📅 2022-08-17 :  用于调度何时向通道发送消息的库。
* [go-vitotrol](https://github.com/maxatome/go-vitotrol) ⭐ 24 | 🐛 0 | 🌐 Go | 📅 2025-11-21 :  V`iessmann Vitotrol `服务的` Go` 语言客户端
* [rmqconn](https://github.com/sbabiv/rmqconn) ⭐ 23 | 🐛 0 | 🌐 Go | 📅 2020-01-27 :   `RabbitMQ Reconnection。amqp.Connection` 和 `amqp.Dial`的`go`语言封装。允许在连接中断时进行重新连接,然后再强制调用关闭方法。
* [jazz](https://github.com/socifi/jazz) ⭐ 18 | 🐛 1 | 🌐 Go | 📅 2019-03-21 :  一个简单的`RabbitMQ`抽象层,用于队列管理以及消息的发布和消费。
* [gaurun-client](https://github.com/osamingo/gaurun-client) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2021-08-03 :  `Go` 语言编写的 Gaurun 客户端

## Microsoft Office

* [unioffice](https://github.com/unidoc/unioffice) ⭐ 4,925 | 🐛 9 | 🌐 Go | 📅 2026-08-13 :  用于创建和处理`Office Word (.docx)、Excel (.xlsx)`和`Powerpoint (.pptx)`文档的纯`go`库。

### EXCEL

* [excelize](https://github.com/360EntSecGroup-Skylar/excelize) ⭐ 20,854 | 🐛 133 | 🌐 Go | 📅 2026-08-16 :  用于读写 `Microsoft Excel™ (XLSX)` 文件的 `Golang `库
* [xlsx](https://github.com/tealeg/xlsx) ⚠️ Archived :  用于在 `Go` 程序中读取最新版 Microsoft Excel的库
* [go-excel](https://github.com/szyhf/go-excel) ⭐ 197 | 🐛 1 | 🌐 Go | 📅 2025-10-01 :  用于读取类似数据库形式的`excel`表格。
* [xlsx](https://github.com/plandem/xlsx) ⭐ 177 | 🐛 13 | 🌐 Go | 📅 2020-11-04 :  在`Go`程序中快速、安全地读取/更新现有 `Microsoft Excel `文件的库。
* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) ⚠️ Archived :   `go`语言`libxlsxwriter`封装， 用于编写 `XLSX (Microsoft Excel)` 文件。

## 其他杂项

### 依赖性注入

* [fx](https://github.com/uber-go/fx) ⭐ 7,637 | 🐛 78 | 🌐 Go | 📅 2025-12-27 :  基于 `Go `的依赖注入应用框架（建立在 `dig` 的基础上）。
* [dig](https://github.com/uber-go/dig) ⭐ 4,494 | 🐛 33 | 🌐 Go | 📅 2025-05-13 :  基于反射的`Go`依赖注入工具包。
* [container](https://github.com/golobby/container) ⭐ 612 | 🐛 6 | 🌐 Go | 📅 2025-08-28 :  功能强大的 `IoC `容器,具有流畅且易于使用的界面。
* [goioc/di](https://github.com/goioc/di) ⭐ 378 | 🐛 4 | 🌐 Go | 📅 2026-01-16 :  `Spring`启发的依赖注入容器。
* [di](https://github.com/goava/di) ⭐ 241 | 🐛 3 | 🌐 Go | 📅 2023-12-16 :  `Go`编程语言的依赖注入容器。
* [dingo](https://github.com/i-love-flamingo/dingo) ⭐ 189 | 🐛 18 | 🌐 Go | 📅 2026-08-06 :  基于 `Guice` 的 `Go` 依赖注入工具包。
* [alice](https://github.com/magic003/alice) ⭐ 51 | 🐛 0 | 🌐 Go | 📅 2017-04-26 :  `Golang `的依赖注入容器
* [wire](https://github.com/Fs02/wire) ⭐ 40 | 🐛 1 | 🌐 Go | 📅 2021-08-22 :  `Golang`运行时依赖注入。
* [linker](https://github.com/logrange/linker) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2025-01-09 :   基于反射的依赖注入和反转的控件库,支持组件生命周期。
* [gocontainer](https://github.com/vardius/gocontainer) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2020-03-23 : 简单的依赖注入容器。

### 项目结构

`用于构建项目的非官方模式集。`

* [golang-standards/project-layout](https://github.com/golang-standards/project-layout) ⭐ 56,459 | 🐛 95 | 🌐 Makefile | 📅 2026-04-28 :  -` Go` 生态系统中常见的历史和新兴项目布局模式集。
* [modern-go-application](https://github.com/sagikazarmark/modern-go-application) ⭐ 1,942 | 🐛 23 | 🌐 Go | 📅 2024-11-01 :   应用现代实践的` Go` 应用程序模板和示例。
* [cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) ⭐ 736 | 🐛 4 | 🌐 Go | 📅 2026-04-13 :Go应用程序模板,用于按照生产最佳实践快速启动项目。
* [go-todo-backend](https://github.com/Fs02/go-todo-backend) ⭐ 335 | 🐛 5 | 🌐 Go | 📅 2026-04-13 `:   Go Todo Backend `示例,使用模块化的项目布局,针对微服务等场景。
* [scaffold](https://github.com/catchplay/scaffold) ⭐ 150 | 🐛 2 | 🌐 Go | 📅 2019-01-10 :  `Scaffold` 生成一个入门的 Go 项目布局。让您专注于业务逻辑的实现。
* [go-sample](https://github.com/zitryss/go-sample) ⭐ 140 | 🐛 0 | 🌐 Go | 📅 2019-01-24 :   一个带有真实代码的 Go 应用项目布局示例。

***

### 字符串处理

* [xstrings](https://github.com/huandu/xstrings) ⭐ 1,413 | 🐛 0 | 🌐 Go | 📅 2024-06-06 :  从其他语言移植过来的字符串函数集合。
* [gobeam/Stringy](https://github.com/gobeam/Stringy) ⭐ 250 | 🐛 0 | 🌐 Go | 📅 2025-05-19 :  字符串操作库,用于将字符串转换为驼峰、小驼峰等格式
* [strutil](https://github.com/ozgio/strutil) ⭐ 205 | 🐛 2 | 🌐 Go | 📅 2025-05-21 :   字符串实用工具。
* [go-formatter](https://gitlab.com/tymonx/go-formatter) :  实现大括号{}格式字符串的替换字段。

### 暂未分类

这些库被放在这里是因为其他类别似乎都不适合。

* [gopsutil](https://github.com/shirou/gopsutil) ⭐ 11,897 | 🐛 218 | 🌐 Go | 📅 2026-08-09 :  跨平台库,用于检索进程和系统利用率（`CPU`、内存、磁盘等）。
* [gatus](https://github.com/TwinProduction/gatus) ⭐ 11,822 | 🐛 361 | 🌐 Go | 📅 2026-08-15 :  自动化的服务健康仪表板。
* [gofakeit](https://github.com/brianvoe/gofakeit) ⭐ 5,378 | 🐛 8 | 🌐 Go | 📅 2026-05-15 :   用`go`编写的随机数据生成器。
* [archiver](https://github.com/mholt/archiver) ⚠️ Archived :  用于制作和解压`.zip`和`.tar.gz`文件的库和命令。
* [base64Captcha](https://github.com/mojocn/base64Captcha) ⭐ 2,368 | 🐛 7 | 🌐 Go | 📅 2025-09-29 :  ` Base64captch`支持数字、数字、字母、算术、音频和数字来生成字母验证码。
* [go-resiliency](https://github.com/eapache/go-resiliency) ⭐ 2,344 | 🐛 2 | 🌐 Go | 📅 2025-02-23 :  `golang`的弹性模式。
* [ghorg](https://github.com/gabrie30/ghorg) ⭐ 2,116 | 🐛 10 | 🌐 Go | 📅 2026-08-01 :  快速将整个` org/users` 仓库克隆到一个目录中 - 支持` GitHub、GitLab` 和 `Bitbucket`。
* [shoutrrr](https://github.com/containrrr/shoutrrr) ⭐ 1,652 | 🐛 78 | 🌐 Go | 📅 2026-07-01 :  提供轻松访问各种消息服务的通知库,如`slack, mattermost, gotify`和`smtp`等。
* [gosms](https://github.com/haxpax/gosms) ⭐ 1,469 | 🐛 5 | 🌐 Go | 📅 2021-02-05 :  你本地的`SMS `网关,可以用来发送 `SMS`
* [stateless](https://github.com/qmuntal/stateless) ⭐ 1,379 | 🐛 23 | 🌐 Go | 📅 2026-02-10 :  用于创建状态机的库
* [llvm](https://github.com/llir/llvm) ⭐ 1,273 | 🐛 18 | 🌐 Go | 📅 2024-12-06 :  - 用于在纯`Go`中与`LLVM IR`交互的库。
* [go-commons-pool](https://github.com/jolestar/go-commons-pool) ⭐ 1,238 | 🐛 4 | 🌐 Go | 📅 2023-05-30 : `Golang` 的通用对象池。
* [shortid](https://github.com/teris-io/shortid) ⭐ 957 | 🐛 4 | 🌐 Go | 📅 2022-06-17 :  分布式生成超短的、唯一的、非序列的、URL友好的ID。
* [banner](https://github.com/dimiro1/banner) ⭐ 462 | 🐛 0 | 🌐 Go | 📅 2021-01-04 :   在你的`Go`应用程序中添加漂亮的横幅。
* [health](https://github.com/dimiro1/health) ⭐ 450 | 🐛 4 | 🌐 Go | 📅 2023-11-18 :  简单易用、可扩展的服务健康检查库
* [gountries](https://github.com/pariz/gountries) ⭐ 435 | 🐛 22 | 🌐 Go | 📅 2026-04-27 :  一个用来展示国家及其行政区划数据的库
* [lk](https://github.com/hyperboloide/lk) ⭐ 421 | 🐛 0 | 🌐 Go | 📅 2025-12-20 :  简单的 \`golang 授权库。
* [conv](https://github.com/cstockton/go-conv) ⭐ 381 | 🐛 1 | 🌐 Go | 📅 2021-08-23 :  包`conv`提供了跨`Go`类型的快速和直观的转换。
* [ffmt](https://github.com/go-ffmt/ffmt) ⭐ 316 | 🐛 2 | 🌐 Go | 📅 2021-11-19 : 美化数据显示。
* [go-unarr](https://github.com/gen2brain/go-unarr) ⭐ 309 | 🐛 3 | 🌐 Go | 📅 2024-10-22 :  `RAR、TAR、ZIP` 和`7z`文件的解压库。
* [healthcheck](https://github.com/etherlabsio/healthcheck) ⭐ 274 | 🐛 4 | 🌐 Go | 📅 2023-12-13 :  针对`RESTful`并发服务健康检查`HTTP`处理程序。
* [battery](https://github.com/distatus/battery) ⭐ 273 | 🐛 7 | 🌐 Go | 📅 2023-09-27 :  跨平台电源信息库
* [antch](https://github.com/antchfx/antch) ⭐ 266 | 🐛 5 | 🌐 Go | 📅 2020-05-31 :  一个快速、强大、可扩展的网络爬行和抓取框架。
* [bitio](https://github.com/icza/bitio) ⭐ 257 | 🐛 1 | 🌐 Go | 📅 2023-03-30 :  高度优化的比特级读写
* [stats](https://github.com/go-playground/stats) ⭐ 172 | 🐛 1 | 🌐 Go | 📅 2016-09-07 :  监控 `Go` 内存状态及系统状态,通过`UDP`进行数据发送
* [turtle](https://github.com/hackebrot/turtle) ⭐ 164 | 🐛 3 | 🌐 Go | 📅 2021-10-04 :  `Go`的`Emojis`。
* [captcha](https://github.com/steambap/captcha) ⭐ 163 | 🐛 0 | 🌐 Go | 📅 2025-08-20 :  包 `captcha` 为验证码的生成提供了一个简单易用的 API。
* [gommit](https://github.com/antham/gommit) ⭐ 117 | 🐛 0 | 🌐 Go | 📅 2026-07-30 :  分析`git`提交消息,确保它们遵循定义的模式。
* [indigo](https://github.com/osamingo/indigo) ⭐ 111 | 🐛 0 | 🌐 Go | 📅 2025-03-22 :  使用`Sonyflake`和`Base58`编码的分布式唯一ID生成器。
* [gotoprom](https://github.com/cabify/gotoprom) ⭐ 108 | 🐛 1 | 🌐 Go | 📅 2024-10-09 : 提供`Go`统计处理程序、结构、测量方法
* [faker](https://github.com/pioz/faker) ⭐ 103 | 🐛 0 | 🌐 Go | 📅 2023-10-06 :  Go的随机伪造数据和结构生成器。
* [persian](https://github.com/mavihq/persian) ⭐ 94 | 🐛 2 | 🌐 Go | 📅 2024-01-28 :  用`go`编写的波斯语实用程序。
* [morse](https://github.com/alwindoss/morse) ⭐ 86 | 🐛 5 | 🌐 Go | 📅 2022-08-30 :   用于转换摩尔斯代码的库。
* [pdfgen](https://github.com/hyperboloide/pdfgen) ⭐ 75 | 🐛 0 | 🌐 Go | 📅 2018-02-19 :   从`Json`请求中生成`PDF`的`HTTP`服务。
* [xkg](https://github.com/go-xkg/xkg) ⭐ 61 | 🐛 1 | 🌐 Go | 📅 2015-01-08 :  键盘抓取器
* [url-shortener](https://github.com/pantrif/url-shortener) ⭐ 51 | 🐛 1 | 🌐 Go | 📅 2023-02-06 :   一个现代的、强大的、健壮的、支持`mysql`的`URL`短链的微服务。
* [datacounter](https://github.com/miolini/datacounter) ⭐ 50 | 🐛 2 | 🌐 Go | 📅 2023-04-13 : `Greaders/writer/HTTP.ResponseWriter`计数器
* [xdg](https://github.com/rkoesters/xdg) ⭐ 50 | 🐛 4 | 🌐 Go | 📅 2026-08-03 :  `Go`中实现的`FreeDesktop.org` (xdg)规范。
* [browscap\_go](https://github.com/digitalcrab/browscap_go) ⚠️ Archived :   [Browser Capabilities Project](http://browscap.org/)的` GO` 语言库
* [sandid](https://github.com/aofei/sandid) ⚠️ Archived :  地球上的每一粒沙子都有自己的`ID`。
* [autoflags](https://github.com/artyom/autoflags) ⭐ 42 | 🐛 0 | 🌐 Go | 📅 2022-06-11 : Go包,用于从结构域中自动定义命令行标志。
* [numa](https://github.com/lrita/numa) ⭐ 40 | 🐛 1 | 🌐 Go | 📅 2024-10-31 :   - `NUMA `是一个用 Go 编写的实用程序库。它帮助我们编写一些`NUMA-AWARED`代码。
* [gosh](https://github.com/osamingo/gosh) ⭐ 37 | 🐛 0 | 🌐 Go | 📅 2025-03-22 :    提供` Go` 统计处理程序、结构、测量方法。
* [shellwords](https://github.com/Wing924/shellwords) ⭐ 28 | 🐛 0 | 🌐 Go | 📅 2023-04-20 :  Golang 库,用于根据`UNIX Bourne shell`的单词解析规则来处理字符串。
* [metrics](https://github.com/pascaldekloe/metrics) ⭐ 27 | 🐛 3 | 🌐 Go | 📅 2023-03-22 :   用于度量工具和` Prometheus` 指标的库。
* [avgRating](https://github.com/kirillDanshin/avgRating) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2017-08-05 :  - 基于`Wilson Score Equation`计算平均得分和评分。
* [anagent](https://github.com/mudler/anagent) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2018-08-12 : 简约、可插拔的`Golang evloop/timer`处理程序,具有依赖注入功能。
* [hostutils](https://github.com/Wing924/hostutils) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2024-06-05 :  用于打包和解压`FQDNs`列表的`golang`库。
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2016-12-30 :  生成模板化的`http`输入和输出。
* [go-openapi](https://github.com/go-openapi) :  解析和使用 `open-api` 模式的软件包集合。

***

## 自然语言处理

* [go-i18n](https://github.com/nicksnyder/go-i18n/) ⭐ 3,540 | 🐛 14 | 🌐 Go | 📅 2026-08-14 :  ,用于处理本地化文本 的软件包及相关工具
* [prose](https://github.com/jdkato/prose) ⭐ 3,084 | 🐛 20 | 🌐 Go | 📅 2026-07-29 :  文本处理库,支持词语切分、词性标记、命名实体提取等功能
* [gse](https://github.com/go-ego/gse) ⭐ 2,841 | 🐛 15 | 🌐 Go | 📅 2026-06-10 :   ` Go`高效的文本分割；支持英语、中文、日语和其他语言。
* [gojieba](https://github.com/yanyiwu/gojieba) ⭐ 2,647 | 🐛 0 | 🌐 Go | 📅 2026-07-20 : 结巴分词的 `Go `语言实现的 [jieba](https://github.com/fxsjy/jieba) ⭐ 35,118 | 🐛 700 | 🌐 Python | 📅 2024-08-21 ,结巴分词是一个用于中文的分词算法
* [go-pinyin](https://github.com/mozillazg/go-pinyin) ⭐ 1,788 | 🐛 21 | 🌐 Go | 📅 2026-03-08 :   汉字到汉语拼音转换器。
* [when](https://github.com/olebedev/when) ⭐ 1,460 | 🐛 16 | 🌐 Go | 📅 2026-08-10 :  英语、俄语的自然语言日期、时间表达解析器。
* [kagome](https://github.com/ikawaha/kagome) ⭐ 977 | 🐛 0 | 🌐 Go | 📅 2026-07-30 :   用纯`Go`编写的`JP`形态分析器。
* [whatlanggo](https://github.com/abadojack/whatlanggo) ⭐ 695 | 🐛 16 | 🌐 Go | 📅 2023-03-28 :  `Go`语言的自然语言检测包。支持84种语言和24种书写 (如拉丁,西里尔等书写系统)。
* [nlp](https://github.com/james-bowman/nlp) ⭐ 476 | 🐛 5 | 🌐 Go | 📅 2021-05-11 :  支持`LSA`（`Latent Semantic Analysis`）的Go自然语言处理库。
* [sentences](https://github.com/neurosnap/sentences) ⭐ 473 | 🐛 5 | 🌐 Go | 📅 2024-02-28 :  语句标记器：将文字段落转换为语句列表
* [nlp](https://github.com/Shixzie/nlp) ⚠️ Archived :  从字符串中提取值,并用nlp填充结构。
* [getlang](https://github.com/rylans/getlang) ⭐ 175 | 🐛 4 | 🌐 Go | 📅 2020-12-27 :   快速自然语言检测包。
* [go-unidecode](https://github.com/mozillazg/go-unidecode) ⭐ 145 | 🐛 4 | 🌐 Go | 📅 2023-05-14 :  `Unicode` 文本音译为` ASCII` 文本
* [RAKE.go](https://github.com/Obaied/RAKE.go) ⭐ 124 | 🐛 2 | 🌐 Go | 📅 2025-06-12 :   快速自动关键字提取算法(`Rapid Automatic Keyword Extraction：RAKE`)的 `Go` 语言接口
* [go-nlp](https://github.com/nuance/go-nlp) ⚠️ Archived :  在进行自然语言工作时用于处理离散概率分布一些工具,以及其他的一些有用的工具
* [segment](https://github.com/blevesearch/segment) ⭐ 89 | 🐛 6 | 🌐 Go | 📅 2026-07-29 :  用于进行 `Unicode` 文本分割的库,实现了[Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/) 中描述的功能
* [go-stem](https://github.com/agonopol/go-stem) ⭐ 81 | 🐛 1 | 🌐 Go | 📅 2018-06-16 :  波特词干算法的一个实现
* [gounidecode](https://github.com/fiam/gounidecode) ⭐ 80 | 🐛 2 | 🌐 Go | 📅 2015-09-23 : `Go`语言的 `Unicode` 直译器 (通常称之为 `unidecode`)
* [textcat](https://github.com/pebbe/textcat) ⭐ 73 | 🐛 1 | 🌐 Go | 📅 2024-12-06 :  基于 `n-gram `的 `Go` 语言文本分类软件包,支持`utf-8` 和原始文本
* [go-localize](https://github.com/m1/go-localize) ⭐ 62 | 🐛 3 | 🌐 Go | 📅 2023-11-11 :  简单易用的`i18n`（国际化和本地化）引擎 - 用于翻译本地化字符串。
* [MMSEGO](https://github.com/awsong/MMSEGO) ⭐ 62 | 🐛 1 | 🌐 Go | 📅 2012-04-18 :   `Go` 语言实现的 `MMSEG `（一个中文分词算法）
* [go2vec](https://github.com/danieldk/go2vec) ⚠️ Archived :  利用 `Go `语言读取和处理 word2vec
* [iuliia-go](https://github.com/mehanizm/iuliia-go) ⭐ 57 | 🐛 0 | 🌐 Go | 📅 2025-01-08 :  以各种可能的方式翻译西里尔语→拉丁语。
* [stemmer](https://github.com/dchest/stemmer) ⭐ 56 | 🐛 0 | 🌐 Go | 📅 2016-12-07 :  Go 语言分词器软件包,包括了英语和德语分词器
* [govader](https://github.com/jonreiter/govader) ⭐ 55 | 🐛 1 | 🌐 Go | 📅 2025-04-29 : [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment) ⭐ 5,042 | 🐛 56 | 🌐 Python | 📅 2026-03-02 情感分析的`Go`实现
* [petrovich](https://github.com/striker2000/petrovich) ⭐ 51 | 🐛 0 | 🌐 Go | 📅 2023-11-29 :  `Petrovich` 是一个将俄语名称转变成给定语言的库。
* [porter2](https://github.com/zhenjl/porter2) ⭐ 47 | 🐛 1 | 🌐 Go | 📅 2020-10-07 :  非常快速的 `Porter 2 stemmer`.
* [transliterator](https://github.com/alexsergivan/transliterator) ⭐ 46 | 🐛 2 | 🌐 Go | 📅 2024-06-05 :   提供单向字符串翻译,支持特定语言的翻译规则
* [snowball](https://github.com/goodsign/snowball) ⭐ 38 | 🐛 0 | 🌐 C | 📅 2017-06-27 : [Snowball native](http://snowball.tartarus.org/)分词器的Go语言接口,提供了分词提取的功能 .
* [go-mystem](https://github.com/dveselov/mystem) ⭐ 36 | 🐛 0 | 🌐 Go | 📅 2016-10-05 :  `Yandex.Mystem`的` CGo` 接口, `Yandex.Mystem` 是一个俄语词汇形态学分析器
* [paicehusk](https://github.com/rookii/paicehusk) ⭐ 29 | 🐛 2 | 🌐 Go | 📅 2013-12-16 :`Go`语言实现的 `Paice/Husk` 词干算法
* [detectlanguage](https://github.com/detectlanguage/detectlanguage-go) ⭐ 26 | 🐛 0 | 🌐 Go | 📅 2025-08-20 : 语言检测API Go客户端。支持批量请求、短语或单字语言检测。
* [icu](https://github.com/goodsign/icu) ⭐ 23 | 🐛 1 | 🌐 Go | 📅 2017-03-29 :  `icu4c C `库的 `CGo `接口,包括了检测和转换函数。保证了`version 50.1`版本的兼容性
* [golibstemmer](https://github.com/rjohnsondev/golibstemmer) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2014-06-17 :  `snowball libstemmer` 库的 `Go `语言接口,包括了对 `porter 2 `的支持
* [gotokenizer](https://github.com/xujiajun/gotokenizer) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2019-04-10 :  基于`Golang`的字典和 `Bigram` 语言模型的分词器。(现在只支持中文分割)
* [porter](https://github.com/a2800276/porter) ⭐ 14 | 🐛 1 | 🌐 Go | 📅 2026-02-09 :  `Martin Porter `实现的`C`语言版本的`Porter`词干算法的` Go` 语言接口。
* [libtextcat](https://github.com/goodsign/libtextcat) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2012-12-27 :   `libtextcat C `库的`CGo`接口。保证了`version 2.2 `版本的兼容性
* [shamoji](https://github.com/osamingo/shamoji) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2025-03-22 : ` shamoji` 是一个`Go`语言编写的词过滤软件包
* [gosentiwordnet](https://github.com/dinopuguh/gosentiwordnet) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2021-03-11 :  ` libstemmer`库的Go绑定。
* [MMSEG](http://technology.chtsai.org/mmseg/) :  `MMSEG的GO`实现,是一种中文分词算法。

***

## 网络相关库

* [fasthttp](https://github.com/valyala/fasthttp) ⭐ 23,434 | 🐛 83 | 🌐 Go | 📅 2026-08-15 : `asthttp` 是一个快速的`HTTP`实现,比`net/http1`的性能快10倍
* [webrtc](https://github.com/pions/webrtc) ⭐ 16,718 | 🐛 113 | 🌐 Go | 📅 2026-08-15 :` WebRTC API`的纯`Go`实现。
* [quic-go](https://github.com/lucas-clemente/quic-go) ⭐ 11,741 | 🐛 215 | 🌐 Go | 📅 2026-08-16 :   纯`Go`中`QUIC`协议的实现。
* [gnet](https://github.com/panjf2000/gnet) ⭐ 11,231 | 🐛 1 | 🌐 Go | 📅 2026-07-09 : `gnet`是用纯Go编写 的一个高性能、轻量级、非阻塞、事件驱动的网络框架,
* [dns](https://github.com/miekg/dns) ⭐ 8,753 | 🐛 1 | 🌐 Go | 📅 2026-08-01 :   用于处理` DNS` 的` Go` 语言库
* [gopacket](https://github.com/google/gopacket) ⭐ 6,792 | 🐛 370 | 🌐 Go | 📅 2025-03-19 : 用于报文处理的库
* [kcp-go](https://github.com/xtaci/kcp-go) ⭐ 4,543 | 🐛 70 | 🌐 Go | 📅 2026-05-15 :` KCP` - 快速可靠的`ARQ`协议。
* [ssh](https://github.com/gliderlabs/ssh) ⭐ 4,168 | 🐛 62 | 🌐 Go | 📅 2025-01-27 :  用于创建 SSH 服务器的高级` API`(封装了`crypto/ssh`).
* [HTTPLab](https://github.com/gchaincl/httplab) ⭐ 4,141 | 🐛 13 | 🌐 Go | 📅 2024-02-05 : `HTTPLabs`让你检查` HTTP`请求和伪造响应。
* [gobgp](https://github.com/osrg/gobgp) ⭐ 4,098 | 🐛 231 | 🌐 Go | 📅 2026-08-12 :  `Go`语言实现的BGP
* [fortio](https://github.com/fortio/fortio) ⭐ 3,718 | 🐛 85 | 🌐 Go | 📅 2026-07-31 :  负载测试库和命令行工具,提供先进的`echo`服务器和web用户界面。允许指定设定每秒钟查询的负载,记录延迟直方图和其他有用的统计数据,并将其绘制成图表。
* [water](https://github.com/songgao/water) ⭐ 2,165 | 🐛 30 | 🌐 Go | 📅 2024-07-30 :  一个简单的`TUN/TAP`库。
* [go-getter](https://github.com/hashicorp/go-getter) ⭐ 1,822 | 🐛 173 | 🌐 Go | 📅 2026-08-16 :   一个用于通过 URL 从多种源下载文件或目录的 Go 语言库
* [gev](https://github.com/Allenxuxu/gev) ⭐ 1,774 | 🐛 14 | 🌐 Go | 📅 2025-06-07 :  一个轻量、比标准库更快的基于` Reactor` 模式的非阻塞`TCP`网络库,支持自定义协议,可以轻松快速搭建高性能服务器。
* [sftp](https://github.com/pkg/sftp) ⭐ 1,661 | 🐛 59 | 🌐 Go | 📅 2026-07-22 : `sftp` 实现了<https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt> 中描述的 SSH 文件传输协议
* [grab](https://github.com/cavaliercoder/grab) ⭐ 1,480 | 🐛 28 | 🌐 Go | 📅 2026-08-14 :  管理文件下载的`Go` 语言库
* [NFF-Go](https://github.com/intel-go/nff-go) ⭐ 1,419 | 🐛 65 | 🌐 Go | 📅 2022-11-22 :   用于快速开发云和裸机（原`YANFF`）的高性能网络功能的框架。
* [ftp](https://github.com/jlaffaye/ftp) ⭐ 1,401 | 🐛 27 | 🌐 Go | 📅 2026-07-29 :` ftp` 实现了一个`FTP` 客户端,遵循 [RFC 959](http://tools.ietf.org/html/rfc959) 标准
* [mdns](https://github.com/hashicorp/mdns) ⭐ 1,371 | 🐛 38 | 🌐 Go | 📅 2026-08-16 :   简单的` mDNS` (组播 DNS)客户端/服务器库
* [gmqtt](https://github.com/DrmagicE/gmqtt) ⭐ 1,046 | 🐛 1 | 🌐 Go | 📅 2026-04-05 : `Gmqtt`是一个灵活、高性能的` MQTT`代理库,它完全实现了` MQTT 协议 V3.1.1`版本
* [vssh](https://github.com/yahoo/vssh) ⭐ 988 | 🐛 6 | 🌐 Go | 📅 2023-12-07 : `Go`库,用于通过`SSH`协议构建网络和服务器自动化。
* [cidranger](https://github.com/yl2chen/cidranger) ⭐ 969 | 🐛 9 | 🌐 Go | 📅 2023-06-05 : `Go`的快速`IP、CIDR`查找库。
* [gaio](https://github.com/xtaci/gaio) ⭐ 919 | 🐛 16 | 🌐 Go | 📅 2026-02-19 :  在`proactor`模式下为`Golang`提供高性能的异步io网络。
* [go-stun](https://github.com/ccding/go-stun) ⭐ 721 | 🐛 2 | 🌐 Go | 📅 2026-07-19 : ` Go`语言实现的` STUN`客户端 (参考`RFC 3489`及`RFC 5389`标准).
* [lhttp](https://github.com/fanux/lhttp) ⭐ 687 | 🐛 7 | 🌐 Go | 📅 2018-04-08 :   强大的`websocket`框架,让您更轻松地建立`IM`服务器。
* [peerdiscovery](https://github.com/schollz/peerdiscovery) ⭐ 672 | 🐛 6 | 🌐 Go | 📅 2025-01-09 : ` Go`库,用于使用`UDP`组播进行跨平台本地对等发现。
* [gotcp](https://github.com/gansidui/gotcp) ⭐ 510 | 🐛 0 | 🌐 Go | 📅 2023-08-08 :   用于快速编写`tcp`应用的库
* [stun](https://github.com/go-rtc/stun) ⚠️ Archived :` RFC 5389 STUN`协议的`Go`实现。
* [gopcap](https://github.com/akrennmair/gopcap) ⭐ 491 | 🐛 11 | 🌐 Go | 📅 2021-05-17 :  `libpcap`的 Go 语言封装
* [winrm](https://github.com/masterzen/winrm) ⭐ 479 | 🐛 50 | 🌐 Go | 📅 2026-04-07 :  用于在` Windows` 机器上远程执行命令的`Go WinRM`客户端。
* [tcp\_server](https://github.com/firstrow/tcp_server) ⚠️ Archived :   用于更快地构建`tcp`服务器的`Go`库。
* [raw](https://github.com/mdlayher/raw) ⚠️ Archived :` raw`允许你在设备驱动层读写网络接口的数据
* [arp](https://github.com/mdlayher/arp) ⭐ 391 | 🐛 7 | 🌐 Go | 📅 2026-07-03 :  遵循 RFC 826标准实现了` ARP`协议。
* [gNxI](https://github.com/google/gnxi) ⭐ 289 | 🐛 28 | 🌐 Python | 📅 2026-07-22 :  使用`gNMI`和`gNOI`协议的网络管理工具集合。
* [ethernet](https://github.com/mdlayher/ethernet) ⭐ 287 | 🐛 0 | 🌐 Go | 📅 2022-02-21 :  `ethernet`实现`了IEEE 802.3 Ethernet II`帧以及`IEEE 802.1Q VLAN`标签的组装和剥离.
* [buffstreams](https://github.com/stabbycutyou/buffstreams) ⭐ 255 | 🐛 5 | 🌐 Go | 📅 2020-08-14 : 基于 TCP的 简单易用的`protocolbuffer` 数据流
* [jazigo](https://github.com/udhos/jazigo) ⭐ 230 | 🐛 1 | 🌐 Go | 📅 2023-11-02 : `Jazigo`是一个用`Go`编写的工具,用于检索多个网络设备的配置。
* [utp](https://github.com/anacrolix/utp) ⭐ 183 | 🐛 4 | 🌐 Go | 📅 2023-05-19 :  `Go uTP`微传输协议的实现
* [xtcp](https://github.com/xfxdev/xtcp) ⭐ 160 | 🐛 0 | 🌐 Go | 📅 2020-02-29 :  `TCP` 服务器框架,支持同时全双工通信。可以优雅的关闭,并且支持自定义协议
* [canopus](https://github.com/zubairhamed/canopus) ⭐ 156 | 🐛 43 | 🌐 Go | 📅 2018-03-25 : `CoAP`客户端/服务器实现 (`RFC 7252`)
* [sslb](https://github.com/eduardonunesp/sslb) ⭐ 152 | 🐛 12 | 🌐 Go | 📅 2024-02-18 :  超简单的负载均衡库。
* [iplib](https://github.com/c-robinson/iplib) ⭐ 151 | 🐛 0 | 🌐 Go | 📅 2024-04-06 :   用于处理`IP`地址的库 (`net.IP, net.IPNet`),灵感来自`python ipaddress`和`ruby ipaddr`。
* [go-powerdns](https://github.com/joeig/go-powerdns) ⭐ 105 | 🐛 1 | 🌐 Go | 📅 2026-07-31 :  Golang的`PowerDNS API`绑定。
* [ether](https://github.com/songgao/ether) ⭐ 82 | 🐛 0 | 🌐 Go | 📅 2016-04-05 :  跨平台`Go` 语言库,用于发送和接收以太帧
* [dhcp6](https://github.com/mdlayher/dhcp6) ⭐ 80 | 🐛 3 | 🌐 Go | 📅 2023-02-24 : `dhcp6` 实现了一个`DHCPv6`服务器，遵循`RFC 3315`标准。
* [portproxy](https://github.com/aybabtme/portproxy) ⭐ 58 | 🐛 0 | 🌐 Go | 📅 2014-12-13 :  单的`TCP`代理,为不支持`CORS`的API增加了`CORS`支持。
* [linkio](https://github.com/ian-kent/linkio) ⭐ 53 | 🐛 0 | 🌐 Go | 📅 2017-08-07 : 接口读写速度模拟器
* [panoptes-stream](https://github.com/yahoo/panoptes-stream) ⭐ 39 | 🐛 2 | 🌐 Go | 📅 2023-07-24 :  云端原生的分布式流媒体网络遥测（`gNMI、Juniper JTI`和`Cisco MDT`）库。
* [httpproxy](https://github.com/wzshiming/httpproxy) ⭐ 33 | 🐛 0 | 🌐 Go | 📅 2026-08-07 : ` HTTP`代理处理程序和拨号器。
* [golibwireshark](https://github.com/sunwxg/golibwireshark) ⭐ 30 | 🐛 1 | 🌐 Go | 📅 2017-10-24 :` Golibwireshark` 使用` libwireshark` 库来解析`pcap` 文件并且分析数据
* [publicip](https://github.com/polera/publicip) ⭐ 29 | 🐛 0 | 🌐 Go | 📅 2016-12-29 :  `publicip`返回你面向公众的`IPv4`地址（互联网出口）。
* [graval](https://github.com/koofr/graval) ⭐ 28 | 🐛 0 | 🌐 Go | 📅 2020-10-02 :  试验性的`FTP` 服务器框架
* [goshark](https://github.com/sunwxg/goshark) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2017-10-24 :` Goshark`使用` tshark` 来对` IP`报文进行解码并创建数据结构用于分析报文
* [llb](https://github.com/kirillDanshin/llb) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2016-04-04 :  非常简单但快速的后端代理服务器。对于快速重定向到预定义域名很有用,无内存分配,响应速度快
* [tspool](https://github.com/two/tspool) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2018-10-29 :  一个使用w`orker pool`来提高性能和保护服务器的TCP库。
* [packet](https://github.com/aerogo/packet) ⚠️ Archived :  通过`TCP`和`UDP`发送数据包。如果需要的话,它可以缓冲消息和热交换连接。
* [gosnmp](https://github.com/soniah/gosnmp) ⭐ 1 | 🐛 0 | 📅 2026-04-03 :  用于执行` SNMP`操作的库
* [gohooks](https://github.com/averageflow/gohooks) :  ` GoHooks` 使得从` Go`应用程序中发送和消费安全的` web-hooks`非常容易。该库的实现受Spatie的Laravel Webhook客户端和服务器的启发。
* [kcptun](https://github.com/xtaci/kcptun) :   基于`KCP`协议的极其简单和快速的`udp`隧道。
* [mqttPaho](https://eclipse.org/paho/clients/golang/) : `Paho`客户端提供了一个` MQTT`客户端库,用于通过`TCP, TLS` 或`WebSockets`和`MQTT broker` 建立连接

***

### Http Client

* [resty](https://github.com/go-resty/resty) ⭐ 11,751 | 🐛 23 | 🌐 Go | 📅 2026-07-26 :  受`Ruby rest-client` 的启发,为`Go` 设计的简单` HTTP`和`REST`客户端。
* [heimdall](https://github.com/gojektech/heimdall) ⭐ 2,774 | 🐛 23 | 🌐 Go | 📅 2026-07-01 :  具有重试和`hystrix`功能的`http`客户端。
* [grequests](https://github.com/levigross/grequests) ⭐ 2,183 | 🐛 24 | 🌐 Go | 📅 2026-07-02 :   著名的请求库的`Go`版本。
* [sling](https://github.com/dghubble/sling) ⭐ 1,720 | 🐛 2 | 🌐 Go | 📅 2026-03-08 : 用于创建和发送` API`请求的`Go HTTP`客户端库。
* [gentleman](https://github.com/h2non/gentleman) ⭐ 1,130 | 🐛 27 | 🌐 Go | 📅 2023-12-17 :  -插件驱动的`HTTP`客户端库。
* [pester](https://github.com/sethgrid/pester) ⭐ 654 | 🐛 6 | 🌐 Go | 📅 2022-02-09 :   具有重试、回退和并发功能的`Go HTTP`客户端调用。
* [request](https://github.com/monaco-io/request) ⭐ 295 | 🐛 2 | 🌐 Go | 📅 2025-11-24 : ` golang`的`HTTP`客户端。如果你有关于` axios`或`requests` 的经验,你会喜欢它,该库没有第三方依赖。
* [go-http-client](https://github.com/bozd4g/go-http-client) ⭐ 84 | 🐛 0 | 🌐 Go | 📅 2024-01-28 :  支持简单方便地进行`http`调用。
* [httpretry](https://github.com/ybbus/httpretry) ⭐ 56 | 🐛 1 | 🌐 Go | 📅 2024-05-18 :  丰富了默认的` Go HTTP`客户端的重试功能。
* [rq](https://github.com/ddo/rq) ⭐ 52 | 🐛 1 | 🌐 Go | 📅 2019-08-28 :  `golang`标准客户端的更好的接口封装

***

### OpenGL

* [glfw](https://github.com/go-gl/glfw) ⭐ 1,689 | 🐛 26 | 🌐 C | 📅 2026-08-02 : `GLFW 3`的`Go`语言接口
* [gl](https://github.com/go-gl/gl) ⭐ 1,203 | 🐛 20 | 🌐 C | 📅 2026-03-31 : `OpenGL`的`Go`语言接口
* [mathgl](https://github.com/go-gl/mathgl) ⭐ 608 | 🐛 9 | 🌐 Go | 📅 2024-11-03 : `Go`语言` 3D`数学库,专注于`3D`,受到`GLM` 启发
* [goxjs/gl](https://github.com/goxjs/gl) ⭐ 174 | 🐛 8 | 🌐 Go | 📅 2023-07-05 : `Go`语言跨平台`OpenGL` 接口(`OS X, Linux, Windows, browsers, iOS, Android`).
* [goxjs/glfw](https://github.com/goxjs/glfw) ⭐ 83 | 🐛 6 | 🌐 Go | 📅 2023-07-04 :` Go` 语言跨平台` glfw`库,用于创建` OpenGL`上下文并接收事件
* [go-glmatrix](https://github.com/technohippy/go-glmatrix) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2021-02-05 :  [glMatrix](http://glmatrix.net/)  库的 Go 移植。 :

***

### ORM

* [GORM](https://github.com/go-gorm/gorm) ⭐ 39,909 | 🐛 517 | 🌐 Go | 📅 2026-06-25 :  超棒的` Go` 语言` ORM` 库,对开发者非常友好
* [ent](https://github.com/facebook/ent) ⭐ 17,172 | 🐛 618 | 🌐 Go | 📅 2026-08-06 :  简单而强大的用于数据建模和查询的ORM。
* [SQLBoiler](https://github.com/volatiletech/sqlboiler) ⭐ 6,989 | 🐛 106 | 🌐 Go | 📅 2026-07-12 :`ORM` 生成器。为你的数据库表单生成一个功能全面、快速的` ORM`
* [go-pg](https://github.com/go-pg/pg) ⭐ 5,786 | 🐛 124 | 🌐 Go | 📅 2026-07-10 :   专注于`PostgreSQL`功能和性能的`ORM`。
* [gorp](https://github.com/go-gorp/gorp) ⭐ 3,747 | 🐛 148 | 🌐 Go | 📅 2024-11-19 :` Go`的`ORM`类库。
* [upper.io/db](https://github.com/upper/db) ⭐ 3,657 | 🐛 165 | 🌐 Go | 📅 2025-12-06 :  - 通过使用封装了成熟的数据库驱动的适配器,来使用单一接口与不同的数据源进行交互
* [gormt](https://github.com/xxjwxc/gormt) ⭐ 2,422 | 🐛 59 | 🌐 Go | 📅 2026-07-10 : `Mysql`数据库到Golang 结构体的`orm`库。
* [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) ⭐ 1,725 | 🐛 4 | 🌐 Go | 📅 2026-06-21 :  灵活而强大的`SQL`字符串构建库,加上一个零配置的`ORM`。
* [pop/soda](https://github.com/gobuffalo/pop) ⭐ 1,514 | 🐛 93 | 🌐 Go | 📅 2026-07-29 :  支持` MySQL, PostgreSQL`, 以及`SQLite`.的数据库迁移、创建、`ORM` 的工具,
* [reform](https://github.com/go-reform/reform) ⭐ 1,458 | 🐛 88 | 🌐 Go | 📅 2025-12-15 :  基于非空接口和代码生成的优秀的` ORM`,
* [rel](https://github.com/go-rel/rel) ⭐ 787 | 🐛 34 | 🌐 Go | 📅 2026-08-15 :` Golang`的现代数据库访问层 - 可测试、可扩展,并支持生成简洁优雅的`API`。
* [beego orm](https://github.com/astaxie/beego/tree/master/orm) ⭐ 742 | 🐛 0 | 📅 2022-04-27 :  强大的`Go` 语言` orm` 框架,支持`pq/mysql/sqlite3`.
* [go-queryset](https://github.com/jirfag/go-queryset) ⭐ 728 | 🐛 20 | 🌐 Go | 📅 2023-02-24 :   100%类型安全的`ORM`,能够基于`GORM`进行代码生成和支持`MySQL、PostgreSQL、Sqlite3、SQL Server`等数据库
* [QBS](https://github.com/coocood/qbs) ⭐ 542 | 🐛 10 | 🌐 Go | 📅 2017-04-18 :  利用结构体进行标准查询,是一个` Go`语言`ORM`
* [Zoom](https://github.com/albrow/zoom) ⭐ 311 | 🐛 2 | 🌐 Go | 📅 2023-02-02 :  基于` Redis` 构建的超快的数据存储于查询引擎。
* [go-sql](https://github.com/rushteam/gosql) ⭐ 176 | 🐛 7 | 🌐 Go | 📅 2022-06-17 :  简单的`mysql ORM`。
* [grimoire](https://github.com/Fs02/grimoire) ⭐ 161 | 🐛 0 | 🌐 Go | 📅 2021-10-25 : `Grimoire`是` golang`的数据库访问层和验证层。(支持：`MySQL, PostgreSQL` 和`SQLite3`)。
* [go-store](https://github.com/gosuri/go-store) ⭐ 113 | 🐛 1 | 🌐 Go | 📅 2017-02-23 :  -简单快速的基于`Redis` 的键值对存储库
* [go-firestorm](https://github.com/jschoedt/go-firestorm) ⭐ 53 | 🐛 0 | 🌐 Go | 📅 2021-12-13 :`Google/Firebase Cloud Firestor`e的简单`ORM`。
* [lore](https://github.com/abrahambotros/lore) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2017-10-21 :  适用于`Go`的简单轻量级的伪ORM/伪结构映射环境,。
* [marlow](https://github.com/marlow/marlow) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2020-08-18 :   从项目结构生成`ORM`,以保证编译时的安全。
* [XORM](https://gitea.com/xorm/xorm) :   简单、强大的` Go` 语言` orm`

***

## Go语言包管理

* [jaeger](https://github.com/jaegertracing/jaeger) ⭐ 23,105 | 🐛 568 | 🌐 Go | 📅 2026-08-16 :  分布式跟踪系统。
* [dep](https://github.com/golang/dep) ⚠️ Archived :  Go 语言依赖工具.
* [glide](https://github.com/Masterminds/glide) ⭐ 8,085 | 🐛 400 | 🌐 Go | 📅 2024-07-22 :  轻松管理你的`GO` 语言包发布者以及发布包。 受到类似` Maven, Bundler` 和`Pip`这些工具的的启发
* [pixie](https://github.com/pixie-labs/pixie) ⭐ 6,514 | 🐛 395 | 🌐 C++ | 📅 2026-07-30 :  通过` eBPF` 对` Golang`应用程序进行无工具追踪。
* [godep](https://github.com/tools/godep) ⚠️ Archived : `Go` 语言依赖工具,`Godep`可以帮助开发者修复库的依赖关系
* [govendor](https://github.com/kardianos/govendor) ⚠️ Archived :  Go 包管理器。` Go`语言`vendor` 工具，兼容标准` vendor`文件
* [statsviz](https://github.com/arl/statsviz) ⭐ 3,648 | 🐛 15 | 🌐 Go | 📅 2026-08-10 :  实时可视化你的`Go`应用程序运行时的统计数据。
* [gopm](https://github.com/gpmgo/gopm) ⚠️ Archived :  ` Go` 包管理器
* [profile](https://github.com/pkg/profile) ⭐ 2,055 | 🐛 12 | 🌐 Go | 📅 2022-10-20 :  `Go` 的简单剖析支持包。
* [gom](https://github.com/mattn/gom) ⚠️ Archived : ` Go Manager`
* [gpm](https://github.com/pote/gpm) ⭐ 1,174 | 🐛 11 | 🌐 Shell | 📅 2017-09-28 : ` Go`语言包管理工具
* [goop](https://github.com/nitrous-io/goop) ⭐ 770 | 🐛 28 | 🌐 Go | 📅 2015-12-02 :   简单的依赖管理工具,受到`Bundler`的启发
* [modgv](https://github.com/lucasepe/modgv) ⚠️ Archived :  将`go mod graph`输出转换为`Graphviz`的`DOT` 语言。
* [nut](https://github.com/jingweno/nut) ⭐ 231 | 🐛 14 | 🌐 Go | 📅 2015-06-25 : `Vendor Go`的依赖关系。
* [johnny-deps](https://github.com/VividCortex/johnny-deps) ⚠️ Archived :  使用` Git` 的最小依赖版本。
* [mvn-golang](https://github.com/raydac/mvn-golang) ⚠️ Archived :  提供自动加载`Golang SDK`、依赖管理和在`Maven`项目基础架构中启动构建环境的方法的插件。
* [VenGO](https://github.com/DamnWidget/VenGO) ⭐ 124 | 🐛 3 | 🌐 Go | 📅 2016-07-14 :  创建和管理可导出的隔离的Go虚拟环境。
  绩效
* [tracer](https://github.com/kamilsk/tracer) ⭐ 90 | 🐛 11 | 🌐 Go | 📅 2026-07-22 :   简单、轻量级的代码追踪库。
* [gop](https://github.com/lunny/gop) ⚠️ Archived :  通过`GOPATH` 构建和管理你的`Go` 应用程序。
* [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) : `go module`是最新的`go`语言版本管理工具。`go module`具有支持包引入记录和其他模块的依赖构建功能。
* [vgo](https://go.googlesource.com/vgo/) :  用于包和依赖管理的非官方库。
* [gigo](https://github.com/LyricalSecurity/gigo) :  类似`PIP`的依赖管理工具。支持私有仓库和哈希

***

### 查询语

* [graphql-go](https://github.com/graphql-go/graphql) ⭐ 10,143 | 🐛 243 | 🌐 Go | 📅 2026-06-23 : 为`Go`语言实现的`GraphQL`
* [dasel](https://github.com/tomwright/dasel) ⭐ 8,017 | 🐛 25 | 🌐 Go | 📅 2026-08-16 :   基于命令行的选择器查询和更新数据结构。类似于`jq/yq`,但支持`JSON、YAML、TOML`和`XML`。
* [graphql](https://github.com/neelance/graphql-go) ⭐ 4,759 | 🐛 12 | 🌐 Go | 📅 2026-08-04 :  专注于易用性的`GraphQL` 服务器
* [gojsonq](https://github.com/thedevsaddam/gojsonq) ⭐ 2,223 | 🐛 26 | 🌐 Go | 📅 2022-11-28 : 用于查询`JSON`数据的`Go`包
* [rql](https://github.com/a8m/rql) ⭐ 367 | 🐛 16 | 🌐 Go | 📅 2024-07-25 :  `REST API`的资源查询语言。
* [jsonql](https://github.com/elgs/jsonql) ⭐ 280 | 🐛 4 | 🌐 Go | 📅 2026-02-21 : ` JSON`查询表达式库
* [jsonslice](https://github.com/bhmj/jsonslice) ⭐ 92 | 🐛 3 | 🌐 Go | 📅 2024-10-25 :  具有高级过滤器的`Json`路径查询。
* [rqp](https://github.com/timsolov/rest-query-parser) ⭐ 91 | 🐛 2 | 🌐 Go | 📅 2023-12-04 : ` REST API`的查询分析器。在查询中直接支持过滤、验证、AND、OR操作。
* [api-fu](https://github.com/ccbrown/api-fu) ⭐ 58 | 🐛 3 | 🌐 Go | 📅 2024-08-29 :`GraphQL`的go语言实现。
* [graphql](https://github.com/tmc/graphql) ⚠️ Archived : `graphql`解析器和实用工具
* [straf](https://github.com/SonicRoshan/straf) ⭐ 40 | 🐛 0 | 🌐 Go | 📅 2020-05-16 :  - 轻松地将`Golang`结构转换为`GraphQL`对象。
* [gws](https://github.com/Zaba505/gws) ⭐ 6 | 🐛 2 | 🌐 Go | 📅 2020-09-04 :  `Apollos`的`GraphQL over Websocket`客户端和服务器实现。

***

## 资源嵌入

* [statik](https://github.com/rakyll/statik) ⭐ 3,825 | 🐛 39 | 🌐 Go | 📅 2026-01-10 :  将静态文件嵌入到`Go` 语言可执行文件中
* [packr](https://github.com/gobuffalo/packr) ⚠️ Archived : 将静态文件嵌入`Go`二进制文件的简单方法。
* [go.rice](https://github.com/GeertJohan/go.rice) ⭐ 2,438 | 🐛 38 | 🌐 Go | 📅 2022-11-16 :` Go.rice`是一个让你轻松使用`html,js,css,`图片以及模板这类资源的库
* [vfsgen](https://github.com/shurcooL/vfsgen) ⭐ 981 | 🐛 32 | 🌐 Go | 📅 2023-11-26 : 生成一个`vfsdata.Go`文件,静态实现了一个虚拟文件系统
* [fileb0x](https://github.com/UnnoTed/fileb0x) ⭐ 634 | 🐛 14 | 🌐 Go | 📅 2023-03-07 :  用于在` Go`语言程序中嵌入文件的工具,专注于可定制化和易用性
* [esc](https://github.com/mjibson/esc) ⚠️ Archived :  - 在`Go`语言程序中嵌入文件并为其提供`HTTP.FileSystem` 接口
* [go-resources](https://github.com/omeid/go-resources) ⭐ 173 | 🐛 0 | 🌐 Go | 📅 2022-10-19 :   简洁的`Go` 语言资源嵌入工具
* [statics](https://github.com/go-playground/statics) ⭐ 68 | 🐛 0 | 🌐 Go | 📅 2016-10-05 :   将静态资源嵌入到`Go` 文件中,用于单独二进制编译+使用`http.FileSystem + symlinks`.
* [templify](https://github.com/wlbr/templify) ⭐ 30 | 🐛 1 | 🌐 Go | 📅 2021-08-16 :  将外部目标文件嵌入到` Go` 代码中来创建单独的二进制文件
* [mule](https://github.com/wlbr/mule) ⭐ 16 | 🐛 1 | 🌐 Go | 📅 2021-08-16 :  将外部资源如图片、电影..嵌入到Go源代码中,使用`go generate`创建单文件二进制文件,专注于简单性。
* [go-embed](https://github.com/pyros2097/go-embed) :   生成用于嵌入资源文件到库或可执行文件的 Go 语言代码

***

## 数据分析与数据科学

* [gonum](https://github.com/gonum/gonum) ⭐ 8,422 | 🐛 251 | 🌐 Go | 📅 2026-07-21 :  用于` Go` 编程语言的数值库。它包含了矩阵、统计、优化等方面的库。
* [stats](https://github.com/montanaflynn/stats) ⭐ 3,023 | 🐛 2 | 🌐 Go | 📅 2026-08-14 :  统计库,包含一些` Go` 语言标准库中漏掉的常用函数
* [gonum/plot](https://github.com/gonum/plot) ⭐ 2,963 | 🐛 91 | 🌐 Go | 📅 2026-04-22 : `Gonum/plot`提供了用于创建和绘制图表的`API`
* [gosl](https://github.com/cpmech/gosl) ⭐ 1,877 | 🐛 0 | 🌐 Go | 📅 2025-12-30 :  用于线性代数、FFT、几何学、`NURBS`、数值方法、概率、优化、微分方程等的` Go` 科学库。
* [streamtools](https://github.com/nytlabs/streamtools) ⭐ 1,312 | 🐛 48 | 🌐 Go | 📅 2023-10-19 : 通用图形化工具,用于处理流数据
* [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) ⭐ 1,290 | 🐛 18 | 🌐 Go | 📅 2022-04-02 :  用于机器学习和统计的数据框类似于`pandas`
* [orb](https://github.com/paulmach/orb) ⭐ 1,126 | 🐛 18 | 🌐 Go | 📅 2026-03-30 :  支持剪裁、`GeoJSON` 和` Mapbox Vector Tile`的`2D` 几何类型。
* [go-dsp](https://github.com/mjibson/go-dsp) ⭐ 916 | 🐛 5 | 🌐 Go | 📅 2026-01-29 :   数字信号处理
* [chart](https://github.com/vdobler/chart) ⭐ 774 | 🐛 6 | 🌐 Go | 📅 2021-06-03 :  Go的简单图表绘制库,支持多种图形类型。
* [graph](https://github.com/yourbasic/graph) ⭐ 752 | 🐛 5 | 🌐 Go | 📅 2023-05-11 :   基本图形算法库。
* [goraph](https://github.com/gyuho/goraph) ⭐ 748 | 🐛 5 | 🌐 Go | 📅 2022-04-10 :   纯`Go`语言编写的图论库（数据结构,算法可视化）
* [ewma](https://github.com/VividCortex/ewma) ⭐ 451 | 🐛 5 | 🌐 Go | 📅 2023-12-14 :  指数加权移动平均数。
* [calendarheatmap](https://github.com/nikolaydubina/calendarheatmap) ⚠️ Archived :  受`Github contribution`的启发,为普通Go语言包提供的日历热图。
* [TextRank](https://github.com/DavidBelicza/TextRank) ⭐ 225 | 🐛 0 | 🌐 Go | 📅 2026-08-10 :` Golang`中的`TextRank` 实现,具有可扩展的特性（摘要、加权、短语提取）和多线程（goroutine）支持。
* [gohistogram](https://github.com/VividCortex/gohistogram) ⚠️ Archived :  数据流的近似直方图
* [pagerank](https://github.com/alixaxel/pagerank) ⭐ 87 | 🐛 3 | 🌐 Go | 📅 2021-06-19 :` Go`语言实现的加权网页排名`PageRank`算法
* [geom](https://github.com/skelterjohn/geom) ⭐ 55 | 🐛 1 | 🌐 Go | 📅 2018-01-03 : `golang`的几何处理库。
* [evaler](https://github.com/soniah/evaler) ⭐ 50 | 🐛 5 | 🌐 Go | 📅 2018-07-27 :  简单的浮点算术表达式评估器。
* [decimal](https://github.com/db47h/decimal) ⭐ 45 | 🐛 0 | 🌐 Go | 📅 2022-08-12 :   包`decimal`实现了任意精度的十进制浮点运算。
* [triangolatte](https://github.com/tchayen/triangolatte) ⭐ 37 | 🐛 4 | 🌐 Go | 📅 2021-08-04 :  `2D`三角测量库。允许将线条和多边形（基于点）翻译成`GPU`语言。
* [goent](https://github.com/kzahedi/goent) ⭐ 36 | 🐛 0 | 🌐 Go | 📅 2019-04-03 : 熵测量的`GO`实现
* [piecewiselinear](https://github.com/sgreben/piecewiselinear) ⭐ 27 | 🐛 0 | 🌐 Go | 📅 2023-12-10 :  小型线性插值库。
* [GoStats](https://github.com/OGFris/GoStats) ⭐ 22 | 🐛 0 | 🌐 Go | 📅 2019-01-14 : ` GoStats` 是一个开源的`GoLang` 库,主要用于机器学习领域的数学统计,它涵盖了大部分的统计测量函数。
* [ode](https://github.com/ChristopherRabotin/ode) ⭐ 22 | 🐛 1 | 🌐 Go | 📅 2017-03-18 : 普通微分方程 (`ODE`) 求解器。支持扩展状态及基于通道的迭代算法终止条件
* [PiHex](https://github.com/claygod/PiHex) ⭐ 21 | 🐛 1 | 🌐 Go | 📅 2026-04-15 :   贝利-波尔温-普劳夫公式`"Bailey-Borwein-Plouffe"`）\`算法的实现,用于计算十六进制π
* [bradleyterry](https://github.com/seanhagen/bradleyterry) ⭐ 12 | 🐛 1 | 🌐 Go | 📅 2019-05-02 :  成对比较提供一个布拉德利-特里模型。
* [rootfinding](https://github.com/khezen/rootfinding) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2020-03-22 :  用于查找二次函数根的寻根算法库
* [go-gt](https://github.com/ThePaw/go-gt) ⭐ 11 | 🐛 2 | 🌐 Go | 📅 2015-09-14 :   图论算法
* [assocentity](https://github.com/ndabAP/assocentity) :单词到给定实体的平均距离计算包。

***

## 安全领域相关库

* [lego](https://github.com/go-acme/lego) ⭐ 9,815 | 🐛 101 | 🌐 Go | 📅 2026-08-03 :  纯` Go`语言开发的` ACME` 客户端库及命令行工具
* [Cameradar](https://github.com/Ullaakut/cameradar) ⭐ 5,167 | 🐛 18 | 🌐 Go | 📅 2026-08-11 :   用于远程入侵监控摄像头的`RTSP`流的工具库。
* [memguard](https://github.com/awnumar/memguard) ⭐ 2,753 | 🐛 12 | 🌐 Go | 📅 2026-05-08 : 用于处理内存中敏感数据的`Go` 语言库
* [secure](https://github.com/unrolled/secure) ⭐ 2,353 | 🐛 0 | 🌐 Go | 📅 2026-05-01 :  为 Go 提供了一些安全功能` HTTP` 中间件,
* [acmetool](https://github.com/hlandau/acme) ⭐ 2,092 | 🐛 72 | 🌐 Go | 📅 2023-05-27 :` ACME (Let's Encrypt)` 客户端工具,支持自动续期.
* [themis](https://github.com/cossacklabs/themis) ⭐ 1,971 | 🐛 31 | 🌐 C | 📅 2026-04-24 : 高级加密库,用于解决典型的数据安全任务（安全数据存储、安全消息传递、零知识证明认证）,提供14种语言,最适合多平台应用。
* [acra](https://github.com/cossacklabs/acra) ⭐ 1,491 | 🐛 21 | 🌐 Go | 📅 2026-04-23 :   用于保护基于数据库的应用程序的网络加密代理,用于防止数据泄露、`SQL`注入等。
* [go-password-validator](https://github.com/lane-c-wagner/go-password-validator) ⭐ 591 | 🐛 6 | 🌐 Go | 📅 2022-09-22 :  用于原始加密熵值的密码验证器。
* [nacl](https://github.com/kevinburke/nacl) ⭐ 550 | 🐛 8 | 🌐 Go | 📅 2026-07-22 : `NaCL`系列` API` 的`Go` 实现
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) ⭐ 508 | 🐛 0 | 🌐 Rust | 📅 2026-08-16 : 利用` ssh` 秘钥加解密 。
* [go-yara](https://github.com/hillu/go-yara) ⭐ 389 | 🐛 7 | 🌐 Go | 📅 2025-07-01 : Go Bindings for[YARA](https://github.com/plusvic/yara) ⭐ 141 | 🐛 1 | 🌐 C | 📅 2020-03-13 恶意软件研究人员（以及其他所有人）的模式匹配瑞士刀"。
* [optimus-go](https://github.com/pjebs/optimus-go) ⭐ 368 | 🐛 1 | 🌐 Go | 📅 2020-05-04 :   使用`Knuth`算法进行`ID`哈希和混淆。
* [firewalld-rest](https://github.com/prashantgupta24/firewalld-rest) ⭐ 344 | 🐛 3 | 🌐 Go | 📅 2024-01-13 :  用于动态更新`linux`服务器上的`firewalld`规则的定时程序。
* [BadActor](https://github.com/jaredfolkins/badactor) ⭐ 328 | 🐛 0 | 🌐 Go | 📅 2020-05-28 :  受`fail2ban` 的启发驻留在内存中的应用驱动监控程序,
* [passlib](https://github.com/hlandau/passlib) ⭐ 289 | 🐛 3 | 🌐 Go | 📅 2021-03-23 :  密码哈希库
* [simple-scrypt](https://github.com/elithrar/simple-scrypt) ⭐ 203 | 🐛 0 | 🌐 Go | 📅 2026-08-10 :  `Scrypt`库,具有简单、易懂的`API`,同时具有内置的自动校准功能
* [argon2pw](https://github.com/raja/argon2pw) ⚠️ Archived :  具有恒定时间密码比较功能的`argon2` 密码散列生成库
* [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) ⭐ 60 | 🐛 2 | 🌐 Go | 📅 2026-05-16 :   用于安全地散列和加密密码的`go`语言包。
* [go-generate-password](https://github.com/m1/go-generate-password) ⭐ 57 | 🐛 0 | 🌐 Go | 📅 2022-04-17 : 密码生成器,可以作为客户端使用或者作为代码库使用。
* [certificates](https://github.com/mvmaasakkers/certificates) ⭐ 38 | 🐛 0 | 🌐 Go | 📅 2022-12-27 :  用于生成`tls`证书的工具库。
* [secureio](https://github.com/xaionaro-go/secureio) ⚠️ Archived :   基于`XChaCha20-poly1305、ECDH`和`ED25519`的`io.ReadWriteCloser`的密钥交换+认证+加密封装器和复用器
* [sslmgr](https://github.com/adrianosela/sslmgr) ⭐ 32 | 🐛 1 | 🌐 Go | 📅 2025-06-02 :  通过对`acme/autocert`的高级封装,使`SSL`证书的使用变得简单。
* [argon2-hashing](https://github.com/andskur/argon2-hashing) ⭐ 25 | 🐛 0 | 🌐 Go | 📅 2025-05-13 :` Go` 的`argon2` 包的封装,与`Go` 的标准库` Bcrypt` 和`simple-scrypt` 包相对应
* [goArgonPass](https://github.com/dwin/goArgonPass) ⚠️ Archived : `Argon2`密码散列和验证,旨在与现有的Python和PHP实现兼容。
* [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert) :   自动提供`Let's Encrypt` 证书并启动` TLS`服务器。
* [Interpol](https://bitbucket.org/vahidi/interpol) : 用于模糊和渗透测试的基于规则的数据生成器,。

***

## 序列化

* [jsoniter](https://github.com/json-iterator/go) ⚠️ Archived : 100%兼容的`"encoding/json "`的 高性能程序库。
* [goprotobuf](https://github.com/golang/protobuf) ⭐ 10,081 | 🐛 115 | 🌐 Go | 📅 2024-08-05 :   以库和协议编译器插件的形式为` Google` 的协议缓冲区提供 Go 支持。
* [mapstructure](https://github.com/mitchellh/mapstructure) ⚠️ Archived :  用于将通用`map`值解码为本地Go结构的Go库。
* [gogoprotobuf](https://github.com/gogo/protobuf) ⭐ 5,662 | 🐛 233 | 🌐 Go | 📅 2023-07-27 :  用于`Gadgets` 的go协议缓冲区。
* [go-codec](https://github.com/ugorji/go) ⭐ 1,957 | 🐛 2 | 🌐 Go | 📅 2026-08-12 :  高性能、多功能、规范化编码解码以及`rpc`库, 用于` msgpack, cbor`和`json`,支持基于运行时的 OR 码生成
* [cbor](https://github.com/fxamacker/cbor) ⭐ 1,079 | 🐛 28 | 🌐 Go | 📅 2026-08-12 :  小巧、安全、简单的` CBOR` 编码和解码库。
* [csvutil](https://github.com/jszwec/csvutil) ⭐ 1,033 | 🐛 0 | 🌐 Go | 📅 2025-03-15 :  高性能的`CSV`记录编码和解码器
* [colfer](https://github.com/pascaldekloe/colfer) ⭐ 759 | 🐛 10 | 🌐 Java | 📅 2026-02-26 :  用于生成` Colfer`二进制格式代码
* [go-capnproto](https://github.com/glycerine/go-capnproto) ⭐ 287 | 🐛 1 | 🌐 Go | 📅 2020-01-29 :   Go的`Cap'n Proto`编码器和解析器。
* [php\_session\_decoder](https://github.com/yvasiyarov/php_session_decoder) ⭐ 169 | 🐛 3 | 🌐 Go | 📅 2018-11-02 :  用于处理` PHP session` 格式和`PHP Serialize/Unserialize`函数的 GoLang 库。
* [structomap](https://github.com/tuvistavie/structomap) ⭐ 143 | 🐛 0 | 🌐 Go | 📅 2019-05-24 :  用于从静态结构中轻松动态地生成映射的库。
* [binstruct](https://github.com/ghostiam/binstruct) ⭐ 114 | 🐛 1 | 🌐 Go | 📅 2024-10-01 :  用于将数据映射到结构中的`Golang` 二进制解码器。
* [bambam](https://github.com/glycerine/bambam) ⭐ 64 | 🐛 3 | 🌐 Go | 📅 2016-10-07 :  从`Go`中生成`Cap'n Proto`模式。
* [asn1](https://github.com/PromonLogicalis/asn1) ⚠️ Archived :` Asn.1 BE`R 及` DER` 编码库
* [bel](https://github.com/32leaves/bel) ⭐ 46 | 🐛 4 | 🌐 Go | 📅 2024-08-01 :   从Go结构/接口生成`TypeScript`接口。对`JSON RPC`有用。
* [fwencoder](https://github.com/o1egl/fwencoder) ⭐ 27 | 🐛 0 | 🌐 Go | 📅 2025-02-11 :  Go的固定宽度文件解析器（编码和解码库）
* [elastic](https://github.com/epiclabs-io/elastic) ⭐ 25 | 🐛 1 | 🌐 Go | 📅 2021-05-21 :  在动态转换不同类型的库
* [pletter](https://github.com/vimeda/pletter) ⭐ 20 | 🐛 8 | 🌐 Go | 📅 2025-12-15 :  为消息中介包装原消息的标准方法。
* [fixedwidth](https://github.com/huydang284/fixedwidth) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2026-08-16 :   固定宽度的文本格式（支持UTF-8）。
* [go-lctree](https://github.com/sbourlon/go-lctree) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2020-06-03 :   提供一个`CLI`和基元来序列化和反序列化` LeetCode`二进制树。 [LeetCode binary trees](https://support.leetcode.com/hc/en-us/articles/360011883654-What-does-1-null-2-3-mean-in-binary-tree-representation) :

***

## 服务端应用

* [Caddy](https://github.com/mholt/caddy) ⭐ 74,951 | 🐛 270 | 🌐 Go | 📅 2026-08-16 :`  Caddy`是一个备选的` HTTP/2 web` 服务器,配置简单,使用方便。
* [minio](https://github.com/minio/minio) ⚠️ Archived :  Minio 是一个分布式对象存储服务器
* [etcd](https://github.com/coreos/etcd) ⭐ 52,118 | 🐛 317 | 🌐 Go | 📅 2026-08-15 :  高可用性的键值存储,用于分享配置和服务发现
* [SFTPGo](https://github.com/drakkan/sftpgo) ⭐ 12,400 | 🐛 170 | 🌐 Go | 📅 2026-08-13 :   功能齐全、高度可配置的`SFTP`服务器,可选择支持`FTP/S和WebDAV`。它可以为本地文件系统和云存储后端服务,如S3和谷歌云存储。
* [RoadRunner](https://github.com/spiral/roadrunner) ⭐ 8,500 | 🐛 63 | 🌐 Go | 📅 2026-08-14 :   高性能的PHP应用服务器,负载均衡器和进程管理器。
* [flipt](https://github.com/markphelps/flipt) ⭐ 4,870 | 🐛 40 | 🌐 Go | 📅 2026-08-16 :  用`Go`和`Vue.js`编写的自带功能标志的解决方案。
* [Fider](https://github.com/getfider/fider) ⭐ 4,473 | 🐛 49 | 🌐 Go | 📅 2026-08-09 : `Fider`是一个收集和整理客户反馈的开放平台。
* [devd](https://github.com/cortesi/devd) ⭐ 3,477 | 🐛 24 | 🌐 Go | 📅 2026-06-21 :   开发者使用的本地`web` 服务器
* [algernon](https://github.com/xyproto/algernon) ⭐ 3,023 | 🐛 19 | 🌐 JavaScript | 📅 2026-08-14 :` HTTP/2 web`服务器,内置`Lua、Markdown、GCSS`和`Amber`支持。
* [Flagr](https://github.com/checkr/flagr) ⭐ 2,605 | 🐛 2 | 🌐 Go | 📅 2026-08-11 : ` Flagr`是一个开源的功能标志和A/B测试服务。
* [Trickster](https://github.com/tricksterproxy/trickster) ⭐ 2,086 | 🐛 33 | 🌐 Go | 📅 2026-08-14 : `HTTP`反向代理缓存和时间序列加速器。
* [discovery](https://github.com/Bilibili/discovery) ⭐ 1,805 | 🐛 26 | 🌐 Go | 📅 2023-07-16 :  一个用于弹性中层负载均衡和故障转移的注册表。
* [jackal](https://github.com/ortuman/jackal) ⚠️ Archived :    用Go编写的`XMPP`服务器。
* [go-proxy-cache](https://github.com/fabiocicerchia/go-proxy-cache) ⭐ 150 | 🐛 15 | 🌐 Go | 📅 2026-08-11 : 简单的反向代理与缓存,用`Go`编写,使用`Redis`。
* [dudeldu](https://github.com/krotik/dudeldu) ⭐ 148 | 🐛 0 | 🌐 Go | 📅 2019-09-22 :   一个简单的`SHOUTcast`服务器。
* [lets-proxy2](https://github.com/rekby/lets-proxy2) ⭐ 103 | 🐛 42 | 🌐 Go | 📅 2024-04-01 :  反向代理,用于处理`https`,在fly中使用` lets-encrypt`发行证书。
* [psql-streamer](https://github.com/blind-oracle/psql-streamer) ⭐ 60 | 🐛 3 | 🌐 Go | 📅 2020-03-10 : 从`PostgreSQL`到`Kafka`的数据库事件流。
* [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) ⭐ 43 | 🐛 0 | 🌐 Go | 📅 2026-08-03 : -`NginxPrometheus exporter`  。
* [simple-jwt-provider](https://github.com/leberKleber/simple-jwt-provider) ⭐ 38 | 🐛 5 | 🌐 Go | 📅 2023-02-25 :   简单轻量级的`provider`,它展示了`JWTs`,支持登录、密码重置（通过邮件）和用户管理。
* [protoxy](https://github.com/camgraff/protoxy) ⭐ 36 | 🐛 0 | 🌐 Go | 📅 2020-11-08 :  一个将JSON请求体转换为协议缓冲区的代理服务器。
* [riemann-relay](https://github.com/blind-oracle/riemann-relay) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2019-10-29 :  - 负载平衡`Riemann`事件和/或将其转换为`Carbon`的中继。
* [consul](https://www.consul.io/) : ` Consul`是一个用于服务发现、监控和配置的工具
* [nsq](http://nsq.io/) :  一个实时的分布式消息平台

***

## 流处理

`流式数据处理和响应式编程库`

* [go-streams](https://github.com/reugn/go-streams) ⭐ 2,170 | 🐛 11 | 🌐 Go | 📅 2026-01-14 :` Go`流处理库。
* [machine](https://github.com/whitaker-io/machine) ⭐ 169 | 🐛 11 | 🌐 Go | 📅 2026-08-14 : 内置度量和具有可跟踪的用于编写和生成流式`worker`的`Go` 库
* [stream](https://github.com/youthlin/stream) ⭐ 92 | 🐛 1 | 🌐 Go | 📅 2024-02-08 :` Go Stream`,像`Java 8 Stream`一样。支持`Filter/Map/FlatMap/Peek/Sorted/ForEach/Reduce...`等特性

***

## 模板引擎

`模版渲染和模版生成处理库`

* [gofpdf](https://github.com/jung-kurt/gofpdf) ⚠️ Archived : ` PDF`文档生成器,高度支持文本、绘图和图像。
* [quicktemplate](https://github.com/valyala/quicktemplate) ⭐ 3,325 | 🐛 41 | 🌐 Go | 📅 2024-07-21 :  快速、强大且易用的模板引擎。将模板转化为` Go` 语言并进行编译
* [pongo2](https://github.com/flosch/pongo2) ⭐ 3,082 | 🐛 65 | 🌐 Go | 📅 2026-05-02 :  类似`Django`的模板引擎
* [maroto](https://github.com/johnfercher/maroto) ⭐ 2,748 | 🐛 71 | 🌐 Go | 📅 2026-07-10 :  用Maroto的方式来创建PDF。Maroto的灵感来自于`Bootstrap`并使用`gofpdf`
* [hero](https://github.com/shiyanhui/hero) ⭐ 1,564 | 🐛 28 | 🌐 Go | 📅 2020-01-09 :` Hero`是一个趁手的、快速的、强大的` Go` 语言模板引擎
* [jet](https://github.com/CloudyKit/jet) ⭐ 1,401 | 🐛 22 | 🌐 Go | 📅 2026-06-18 :` Jet` 模板引擎
* [mustache](https://github.com/hoisie/mustache) ⭐ 1,118 | 🐛 34 | 🌐 Go | 📅 2024-04-28 :  `Go`语言实现的` Mustache`模板语言
* [amber](https://github.com/eknkc/amber) ⭐ 920 | 🐛 24 | 🌐 Go | 📅 2020-10-13 :  Amber 是一个优雅的模板引擎,受到`HAML`和`Jade`的启发
* [fasttemplate](https://github.com/valyala/fasttemplate) ⭐ 911 | 🐛 13 | 🌐 Go | 📅 2023-08-28 :  简单而快速的模板引擎。替换模板占位符的速度比[text/template](http://golang.org/pkg/text/template/) :  快10倍
* [Razor](https://github.com/sipin/gorazor) ⭐ 884 | 🐛 1 | 🌐 Go | 📅 2026-06-01 : ` Go`语言的` Razor` 视图引擎
* [ace](https://github.com/yosssi/ace) ⭐ 838 | 🐛 30 | 🌐 Go | 📅 2018-06-17 :  Go 语言版本的 HTML 模板引擎,受到了` Slim`和`Jade` 的启发。`Ace` 是对`Gold`的一种改进。
* [raymond](https://github.com/aymerick/raymond) ⚠️ Archived :  使用` Go`语言实现的完整的` handlebars`
* [ego](https://github.com/benbjohnson/ego) ⭐ 587 | 🐛 10 | 🌐 Go | 📅 2023-03-15 :  轻量级模板语言,让你可以使用` Go`语言来创建模板。模板会被转化为 Go 语言并编译
* [goview](https://github.com/foolin/goview) ⭐ 464 | 🐛 15 | 🌐 Go | 📅 2025-08-10 : `Goview`是一个轻量级的、简约的、习惯性的模板库,基于`golang html/template`来构建`Go web`应用。
* [liquid](https://github.com/osteele/liquid) ⭐ 353 | 🐛 6 | 🌐 Go | 📅 2026-08-16 :  Go 语言实现的`Shopify Liquid`模板.
* [Soy](https://github.com/robfig/soy) ⭐ 177 | 🐛 6 | 🌐 Go | 📅 2024-03-19 :`go`语言实现的谷歌闭包模板(也就是`Soy templates`), 参见[官方说明文档](https://developers.google.com/closure/templates/) :
* [kasia.go](https://github.com/ziutek/kasia.go) ⭐ 74 | 🐛 1 | 🌐 Go | 📅 2015-08-31 : 使用go语言实现的 用于`HTML` 和其他文本文件的模板系统,
* [velvet](https://github.com/gobuffalo/velvet) ⭐ 71 | 🐛 2 | 🌐 Go | 📅 2017-03-20 :   使用` Go`语言实现的完整的\` handlebars
* [extemplate](https://github.com/dannyvankooten/extemplate) ⚠️ Archived :  围绕`html/template` 的小型封装器,可以轻松实现基于文件的模板继承
* [gospin](https://github.com/m1/gospin) ⭐ 60 | 🐛 3 | 🌐 Go | 📅 2021-05-12 :  语法引擎,对于`A/B`、测试文本/文章片段和创建更自然的对话非常有用。
* [damsel](https://github.com/dskinner/damsel) ⭐ 24 | 🐛 1 | 🌐 Go | 📅 2016-04-07 : 通过css选择器实现了` html` 框架 ,并可以通过` pkg html/template` 等进行扩展

***

## 测试相关

`测试库和测试数据集生成库`

* 测试框架
  * [apitest](https://apitest.dev) : 为基于`REST`的服务或`HTTP`处理程序提供简单且可扩展的行为测试库,支持模拟外部`http`调用和渲染序列图。
  * [assert](https://github.com/go-playground/assert) ⭐ 67 | 🐛 2 | 🌐 Go | 📅 2022-09-12 :  基础断言库,用于对`Go`语言程序进行测试,提供了一些用于自定义断言的代码块
  * [badio](https://github.com/cavaliercoder/badio) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2016-02-13 :  Go 语言` testing/iotest`包的扩展
  * [baloo](https://github.com/h2non/baloo) ⭐ 779 | 🐛 9 | 🌐 Go | 📅 2022-08-10 :   表达性强、多功能的、端到端的`HTTP API` 测试工具
  * [biff](https://github.com/fulldump/biff) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2023-01-11 : ` Bifurcation`测试框架,兼容`BDD`。
  * [charlatan](https://github.com/percolate/charlatan) ⭐ 205 | 🐛 2 | 🌐 Go | 📅 2023-11-19 :  为测试生成虚假接口实现的工具。
  * [commander](https://github.com/SimonBaeumer/commander) ⭐ 232 | 🐛 31 | 🌐 Go | 📅 2024-04-02 :   用于在`windows、linux`和`osx`上测试\`cli应用程序的工具。
  * [covergates](https://github.com/covergates/covergates) ⭐ 61 | 🐛 24 | 🌐 Go | 📅 2023-05-05 :  自主的代码覆盖率报告审查和管理服务。
  * [cupaloy](https://github.com/bradleyjkemp/cupaloy) ⭐ 330 | 🐛 16 | 🌐 Go | 📅 2023-05-19 :   用于测试框架的简单快照测试插件。
  * [dbcleaner](https://github.com/khaiql/dbcleaner) ⭐ 163 | 🐛 0 | 🌐 Go | 📅 2021-11-10 :  清空数据库用于测试,受到`database_cleaner`的启发
  * [dsunit](https://github.com/viant/dsunit) ⭐ 47 | 🐛 0 | 🌐 Go | 📅 2025-12-31 :  数据库测试,针对` SQL、 NoSQL`、 结构化文件.
  * [embedded-postgres](https://github.com/fergusstrange/embedded-postgres) ⭐ 1,219 | 🐛 13 | 🌐 Go | 📅 2026-03-18 :  作为另一个` Go`应用程序或测试的一部分,在`Linux、OSX` 或`Windows`上本地运行一个真正的 Postgres 数据库
  * [endly](https://github.com/viant/endly) ⭐ 269 | 🐛 4 | 🌐 Go | 📅 2026-04-16 :   声明式端到端功能测试。
  * [flute](https://github.com/suzuki-shunsuke/flute) ⭐ 23 | 🐛 3 | 🌐 Go | 📅 2026-08-15 : ` HTTP`客户端测试框架。
  * [frisby](https://github.com/verdverm/frisby) ⭐ 275 | 🐛 12 | 🌐 Go | 📅 2020-03-03 : `REST API` 测试框架
  * [ginkgo](http://onsi.github.io/ginkgo/) : `BDD` 测试框架
  * [go-carpet](https://github.com/msoap/go-carpet) ⭐ 251 | 🐛 3 | 🌐 Go | 📅 2025-08-22 :  用于在终端中查看测试覆盖率的工具
  * [go-cmp](https://github.com/google/go-cmp) ⭐ 4,672 | 🐛 60 | 🌐 Go | 📅 2026-06-18 :  用于比较测试中的` Go`值的软件包。
  * [go-hit](https://github.com/Eun/go-hit) ⭐ 255 | 🐛 13 | 🌐 Go | 📅 2024-07-08 :  用`golang`编写的` http` 集成测试框架。
  * [go-mutesting](https://github.com/zimmski/go-mutesting) ⭐ 673 | 🐛 43 | 🌐 Go | 📅 2024-07-04 :` Go`语言源代码突变测试`（Mutation testing ）`
  * [go-testdeep](https://github.com/maxatome/go-testdeep) ⭐ 463 | 🐛 3 | 🌐 Go | 📅 2026-07-31 :  扩展了` go` 测试包的极为灵活的`golang` 深度比较库,。
  * [go-vcr](https://github.com/dnaeon/go-vcr) ⭐ 1,394 | 🐛 6 | 🌐 Go | 📅 2026-07-16 :   记录并重放` HTTP`交互,用于快速的、确定性的、准确的测试
  * [goblin](https://github.com/franela/goblin) ⭐ 885 | 🐛 21 | 🌐 Go | 📅 2022-12-22 :  类似` Mocha` 的测试框架
  * [goc](https://github.com/qiniu/goc) ⭐ 873 | 🐛 101 | 🌐 Go | 📅 2026-05-03 : `Goc`是一个针对` Go` 编程语言的综合覆盖测试系统。
  * [gocheck](http://labix.org/gocheck) :  更加高级的测试框架,用于替换`Gotest`.
  * [GoConvey](https://github.com/smartystreets/goconvey/) ⭐ 8,405 | 🐛 168 | 🌐 Go | 📅 2024-07-30 : `BDD` 风格的测试框架,具有` web` 界面和计时刷新功能
  * [gocrest](https://github.com/corbym/gocrest) ⭐ 108 | 🐛 2 | 🌐 Go | 📅 2026-04-22 :   用于`Go` 断言的可组合的类似`hamcrest`的匹配器。
  * [godog](https://github.com/DATA-DOG/godog) ⭐ 2,659 | 🐛 89 | 🌐 Go | 📅 2026-08-13 :  类似于`Cucumber`或`Behat`的`Go BDD`框架。
  * [gofight](https://github.com/appleboy/gofight) ⭐ 445 | 🐛 9 | 🌐 Go | 📅 2026-08-03 :  对`Go` 语言的路由框架进行`API` 测试
  * [gogiven](https://github.com/corbym/gogiven) ⭐ 17 | 🐛 4 | 🌐 Go | 📅 2026-05-03 :  类似` YATSPEC` 的`Go BDD`测试框架。
  * [gomatch](https://github.com/jfilipczyk/gomatch) ⭐ 47 | 🐛 0 | 🌐 Go | 📅 2021-01-15 :  类似`Rspec` 的匹配器/断言库。
  * [gomega](http://onsi.github.io/gomega/) :  类似`Rspec` 的`matcher/assertion`库
  * [GoSpec](https://github.com/orfjackal/gospec) ⭐ 113 | 🐛 3 | 🌐 Go | 📅 2014-07-31 :` BDD`风格的测试框架
  * [gospecify](https://github.com/stesla/gospecify) ⭐ 52 | 🐛 1 | 🌐 Go | 📅 2011-10-18 :   支持` BDD`语法 。对于任何使用过 rspec 等库的人来说应该非常熟悉
  * [gosuite](https://github.com/pavlo/gosuite) ⭐ 12 | 🐛 1 | 🌐 Go | 📅 2016-10-18 :  轻量级测试套,为`Go1.7's Subtests`带来了`setup/teardown`功能
  * [gotest.tools](https://github.com/gotestyourself/gotest.tools) ⭐ 577 | 🐛 33 | 🌐 Go | 📅 2025-02-08 :  用于增强 Go 测试包并支持常见模式的软件包集合。
  * [Hamcrest](https://github.com/rdrdr/hamcrest) ⭐ 30 | 🐛 2 | 🌐 Go | 📅 2021-01-07 :   用于声明式`Matcher` 对象的流畅框架,当应用于输入值时,会产生自描述的结果。
  * [httpexpect](https://github.com/gavv/httpexpect) ⭐ 2,724 | 🐛 24 | 🌐 Go | 📅 2025-11-20 :   简洁的、声明式的、易用的端到端HTTP 及 REST API 测试
  * [jsonassert](https://github.com/kinbiko/jsonassert) ⭐ 143 | 🐛 6 | 🌐 Go | 📅 2025-12-14 :  用于验证JSON有效载荷是否被正确序列化的软件包。
  * [restit](https://github.com/yookoala/restit) ⭐ 56 | 🐛 6 | 🌐 Go | 📅 2026-07-02 :   帮助编写`RESTful API`集成测试的`Go` 语言微型框架.
  * [schema](https://github.com/jgroeneveld/schema) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2019-10-13 :   对请求和响应中使用的JSON模式进行快速、简单的表达式匹配。
  * [stop-and-go](https://github.com/elgohr/stop-and-go) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2026-07-16 :    并发测试助手。
  * [testcase](https://github.com/adamluzsi/testcase) ⭐ 133 | 🐛 0 | 🌐 Go | 📅 2026-08-11 :  行为驱动开发的直观测试框架。
  * [testfixtures](https://github.com/go-testfixtures/testfixtures) ⭐ 1,235 | 🐛 18 | 🌐 Go | 📅 2026-08-01 : 类似` Rails`的测试工具,用于测试数据库应用
  * [Testify](https://github.com/stretchr/testify) ⭐ 26,162 | 🐛 365 | 🌐 Go | 📅 2026-07-21 :  对标准测试包的扩展
  * [testmd](https://godoc.org/github.com/tvastar/test/cmd/testmd) :  将`markdow`n片段转换为可测试的go代码。
  * [testsql](https://github.com/zhulongcheng/testsql) ⭐ 17 | 🐛 3 | 🌐 Go | 📅 2019-09-26 :  在测试前从`SQL`文件中生成测试数据,并在测试结束后将其清除。
  * [trial](https://github.com/jgroeneveld/trial) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2022-10-05 :   快速简单的可扩展断言,不需要引入太多模板。
  * [Tt](https://github.com/vcaesar/tt) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2026-04-04 :  简单而多彩的测试工具。
  * [wstest](https://github.com/posener/wstest) ⭐ 102 | 🐛 1 | 🌐 Go | 📅 2020-12-30 : ` Websocket`客户端,用于对于` websocket HTTP.Handler`进行单元测试

***

* Mock
  * [gomock](https://github.com/golang/mock) ⚠️ Archived :  给 Go 语言用的`Mock`框架
  * [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) ⭐ 6,566 | 🐛 43 | 🌐 Go | 📅 2026-07-10 :` Mock SQL` ,用于测试数据库交互
  * [hoverfly](https://github.com/SpectoLabs/hoverfly) ⭐ 2,508 | 🐛 33 | 🌐 Go | 📅 2026-08-05 :`  HTTP(S) : proxy,`用于记录和模拟`REST/SOAP API`,具有可扩展的中间件和易于使用的 CLI。
  * [gock](https://github.com/h2non/gock) ⭐ 2,218 | 🐛 49 | 🌐 Go | 📅 2024-09-24 :   多功能、易用`HTTP mock`
  * [httpmock](https://github.com/jarcoal/httpmock) ⭐ 2,077 | 🐛 5 | 🌐 Go | 📅 2026-07-28 :  轻松模拟来自外部资源的 HTTP 响应。
  * [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) ⭐ 1,140 | 🐛 22 | 🌐 Go | 📅 2026-07-14 :  用于生成自包含`mock`对象的工具
  * [go-txdb](https://github.com/DATA-DOG/go-txdb) ⭐ 751 | 🐛 2 | 🌐 Go | 📅 2025-03-11 :  基于单事物的数据库驱动,主要用于测试目的
  * [minimock](https://github.com/gojuno/minimock) ⭐ 751 | 🐛 26 | 🌐 Go | 📅 2026-08-09 : `Mock`生成器
  * [govcr](https://github.com/seborama/govcr) ⭐ 200 | 🐛 0 | 🌐 Go | 📅 2026-04-25 :  `HTTP mock`: 离线测试时记录和重放浏览器的动作
  * [go-localstack](https://github.com/elgohr/go-localstack) ⭐ 88 | 🐛 4 | 🌐 Go | 📅 2026-08-03 :  在`AWS`测试中使用`localstack`的工具。
  * [timex](https://github.com/cabify/timex) ⭐ 70 | 🐛 1 | 🌐 Go | 📅 2020-08-03 :   原生时间包的测试友好的替代品。
  * [mockhttp](https://github.com/tv42/mockhttp) ⭐ 23 | 🐛 0 | 🌐 Go | 📅 2014-10-29 :  `Go HTTP.ResponseWriter`使用的 Mock 对象
* Fuzzing and delta-debugging/reducing/shrinking.
  * [go-fuzz](https://github.com/dvyukov/go-fuzz) ⭐ 4,849 | 🐛 58 | 🌐 Go | 📅 2024-09-24 :  随机化测试系统
  * [gofuzz](https://github.com/google/gofuzz) ⚠️ Archived :  用于生成随机值来初始化`Go`语言对象的库
  * [Tavor](https://github.com/zimmski/tavor) ⭐ 248 | 🐛 53 | 🌐 Go | 📅 2018-10-31 :  通用模糊测试框架
* Selenium及浏览器控制工具
  * [chromedp](https://github.com/knq/chromedp) ⭐ 13,253 | 🐛 177 | 🌐 Go | 📅 2026-07-14 :  用于驱动和测试`Chrome, Safari, Edge, Android Webviews`, 以及其他支持`Chrome`调试协议的产品
  * [rod](https://github.com/go-rod/rod) ⭐ 7,061 | 🐛 209 | 🌐 Go | 📅 2026-08-11 : `Devtools`驱动,使网络自动化测试变得简单。
  * [selenoid](https://github.com/aerokube/selenoid) ⚠️ Archived : ` Selenium hub`服务器的替代品,可以在容器中启动浏览器
  * [cdp](https://github.com/mafredri/cdp) ⭐ 795 | 🐛 14 | 🌐 Go | 📅 2025-12-07 :   类型安全的的` Go` 语言接口,可以用于浏览器或任何实现了 Chrome debug协议的其他待调试对象
  * [ggr](https://github.com/aerokube/ggr) ⚠️ Archived :   轻量级服务器,可以将 Selenium Wedriver 的请求路由或代理到多个`Selenium hubs`.
* Fail injection
  * [failpoint](https://github.com/pingcap/failpoint) ⭐ 894 | 🐛 9 | 🌐 Go | 📅 2026-08-11 :  Golang中[failpoints](http://www.freebsd.org/cgi/man.cgi?query=fail) 的实现。

***

## 文本处理

`解析和操作文本的代码库`

* 特定文本格式处理
  * [colly](https://github.com/asciimoo/colly) ⭐ 25,426 | 🐛 193 | 🌐 Go | 📅 2026-08-14 :  `go`语言版爬虫框架
  * [GoQuery](https://github.com/PuerkitoBio/goquery) ⭐ 14,977 | 🐛 3 | 🌐 Go | 📅 2026-07-31 :`  GoQuery` 为` Go`语言带来了一组类似`jQuery` 的语法和功能
  * [sh](https://github.com/mvdan/sh) ⭐ 8,985 | 🐛 98 | 🌐 Go | 📅 2026-08-13 : `Shell`解析器及格式化工具
  * [blackfriday](https://github.com/russross/blackfriday) ⭐ 5,605 | 🐛 224 | 🌐 Go | 📅 2024-01-29 : `Markdown` 解析器
  * [toml](https://github.com/BurntSushi/toml) ⭐ 4,995 | 🐛 26 | 🌐 Go | 📅 2026-08-16 : `TOML` 配置格式的编码解码器
  * [go-humanize](https://github.com/dustin/go-humanize) ⭐ 4,810 | 🐛 58 | 🌐 Go | 📅 2026-03-02 :    将时间、数字和内存大小格式化为人类可读的格式。
  * [html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) ⭐ 3,781 | 🐛 25 | 🌐 Go | 📅 2026-08-03 :  将`HTML`转换为`Markdown`。甚至适用于整个网站,并可通过规则进行扩展。
  * [bluemonday](https://github.com/microcosm-cc/bluemonday) ⭐ 3,709 | 🐛 32 | 🌐 Go | 📅 2025-04-04 : ` HTML` 清理工具
  * [gofeed](https://github.com/mmcdole/gofeed) ⭐ 2,867 | 🐛 16 | 🌐 Go | 📅 2026-08-10 :  使用`Go`语言解析`RSS`和`Atom`
  * [go-toml](https://github.com/pelletier/go-toml) ⭐ 1,977 | 🐛 30 | 🌐 Go | 📅 2026-08-03 : `TOML`格式的`Go`库,
  * [inject](https://github.com/facebookgo/inject) ⚠️ Archived :  一个基于反射的注入器
  * [slug](https://github.com/gosimple/slug) ⭐ 1,330 | 🐛 13 | 🌐 Go | 📅 2024-12-23 :` URL`友好的` slug` 化工具,支持多种语言
  * [commonregex](https://github.com/mingrammer/commonregex) ⭐ 895 | 🐛 2 | 🌐 Go | 📅 2019-11-12 :` Go`常用正则表达式的集合。
  * [htmlquery](https://github.com/antchfx/htmlquery) ⭐ 781 | 🐛 7 | 🌐 Go | 📅 2026-07-02 :` HTML`的`XPath` 查询包,让您可以通过` XPath` 表达式从`HTML`文档中提取数据。
  * [go-runewidth](https://github.com/mattn/go-runewidth) ⭐ 717 | 🐛 0 | 🌐 Go | 📅 2026-07-24 :  用于获取固定宽度的字符或字符串的函数。
  * [dataflowkit](https://github.com/slotix/dataflowkit) ⭐ 716 | 🐛 4 | 🌐 Go | 📅 2023-03-07 : `Web`爬虫框架用于将网站转化为结构化数据。
  * [mxj](https://github.com/clbanning/mxj) ⭐ 628 | 🐛 2 | 🌐 Go | 📅 2025-08-10 :   通过点分路径和通配符来提取值 将` XML`编解码为` JSON` 或` map[string]interface{}`;目的是用于替代`Replaces x2j` 和`j2x` 包.
  * [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) ⭐ 594 | 🐛 15 | 🌐 Go | 📅 2026-07-23 :   格式化二进制为字符串
  * [gographviz](https://github.com/awalterschulze/gographviz) ⭐ 568 | 🐛 8 | 🌐 Go | 📅 2023-02-28 :    用以解析`Graphviz DOT` 语言
  * [gotext](https://github.com/leonelquinteros/gotext) ⭐ 507 | 🐛 5 | 🌐 Go | 📅 2026-08-10 :  Go语言版本的`GNU gettext`工具。
  * [goq](https://github.com/andrewstuart/goq) ⭐ 269 | 🐛 3 | 🌐 Go | 📅 2021-09-02 :  声明式`HTML` 编组,使用结构标签和`jQuery`语法 (使用`GoQuery`).
  * [go-nmea](https://github.com/adrianmo/go-nmea) ⭐ 264 | 🐛 1 | 🌐 Go | 📅 2026-06-10 :   Go语言的NMEA解析库。
  * [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) ⭐ 156 | 🐛 7 | 🌐 Go | 📅 2026-07-27 : Go 语言用的`Editorconfig` 文件解析和操作库
  * [podcast](https://github.com/eduncan911/podcast) ⭐ 140 | 🐛 7 | 🌐 Go | 📅 2020-11-04 :  `Golang`中兼容`iTunes`和`RSS 2.0`的播客生成器。
  * [go-vcard](https://github.com/emersion/go-vcard) ⭐ 129 | 🐛 6 | 🌐 Go | 📅 2026-06-18 :  解析和格式化`vCard`。
  * [pagser](https://github.com/foolin/pagser) ⭐ 112 | 🐛 8 | 🌐 Go | 📅 2023-10-15 :   `Pagser`是一个简单的、可扩展的、可配置的、基于`goquery`和`struct`标签的`golang` 爬虫解析和反序列化工具,能够将`html`页面映射到struct结构体中。
  * [sdp](https://github.com/gortc/sdp) ⚠️ Archived : `SDP Session Description Protocol`, [RFC 4566](https://tools.ietf.org/html/rfc4566)实现
  * [go-zero-width](https://github.com/trubitsyn/go-zero-width) ⚠️ Archived :   Go的零宽度字符检测和移除。
  * [go-slugify](https://github.com/mozillazg/go-slugify) ⭐ 96 | 🐛 2 | 🌐 Go | 📅 2020-05-13 :  制作支持多语言的漂亮`slug`。
  * [did](https://github.com/ockam-network/did) ⭐ 94 | 🐛 7 | 🌐 Go | 📅 2023-01-03 :   Go中的`DID`（去中心化标识符）解析器和`Stringer`。
  * [goregen](https://github.com/zach-klippenstein/goregen) ⭐ 92 | 🐛 5 | 🌐 Go | 📅 2022-05-18 :  根据正则表达式生成随机字符串
  * [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) ⭐ 87 | 🐛 10 | 🌐 Go | 📅 2024-02-08 : 固定宽度的文本格式（带反射的编码器/解码器）。
  * [align](https://github.com/Guitarbum722/align) ⭐ 84 | 🐛 0 | 🌐 Go | 📅 2021-09-12 :  文本对齐
  * [genex](https://github.com/alixaxel/genex) ⭐ 77 | 🐛 0 | 🌐 Go | 📅 2020-01-05 :  计算并展开正则表达式为所有匹配的字符串
  * [allot](https://github.com/sbstjn/allot) ⭐ 60 | 🐛 3 | 🌐 Go | 📅 2022-01-31 :   占位符及通配符文本解析
  * [guesslanguage](https://github.com/endeveit/guesslanguage) ⭐ 58 | 🐛 1 | 🌐 Go | 📅 2017-11-08 :  用于确定`unicode`文本的自然语言的函数。
  * [gonameparts](https://github.com/polera/gonameparts) ⭐ 43 | 🐛 2 | 🌐 Go | 📅 2024-10-04 :  将人名解析为几个独立的部分
  * [Slugify](https://github.com/avelino/slugify) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2018-05-01 :`  Go`语言静态地址生成器,可以处理字符串
  * [codetree](https://github.com/aerogo/codetree) ⭐ 25 | 🐛 0 | 🌐 Go | 📅 2019-10-26 :  解析缩进代码（`python、pixy、scarlet`等）并返回一个树形结构。
  * [enca](https://github.com/endeveit/enca) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2016-03-15 :   [libenca](http://cihar.com/software/enca/) :  的极简的`cGo`接口
  * [bbConvert](https://github.com/CalebQ42/bbConvert) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2024-12-27 :   将`bbCode` 转换为`HTML`
  * [doi](https://github.com/hscells/doi) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2017-08-21 :   Go中的文档对象标识符（`doi`）解析器。
  * [ltsv](https://github.com/Wing924/ltsv) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2024-09-27 :  适用于 Go 的高性能` LTSV（Labeled Tab Separated Value）`阅读器。[LTSV (Labeled Tab Separated Value)](http://ltsv.org/) :
  * [encdec](https://github.com/mickep76/encdec) : 通用编码和解码器
  * [github\_flavored\_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) : ` GitHub Flavored Markdown` 渲染器（使用 blackfriday）,带有栅栏式代码块高亮,可点击标题锚链接
  * [goribot](https://github.com/zhshch2002/goribot) :  简单的golang爬虫框架,3行代码就可以创建爬虫。
  * [syndfeed](https://github.com/zhengchun/syndfeed) :   适用于`Atom 1.0和RSS 2.0`的聚合`feed`。
* 文本工具
  * [xurls](https://github.com/mvdan/xurls) ⭐ 1,264 | 🐛 2 | 🌐 Go | 📅 2026-03-27 :  从文本中提取`URLs`。
  * [gotabulate](https://github.com/bndr/gotabulate) ⭐ 335 | 🐛 5 | 🌐 Go | 📅 2021-02-09 :  使用` Go`轻松地打印你的表格数据。
  * [radix](https://github.com/yourbasic/radix) ⭐ 197 | 🐛 0 | 🌐 Go | 📅 2018-03-08 :  快速字符串排序算法。
  * [regroup](https://github.com/oriser/regroup) ⭐ 150 | 🐛 1 | 🌐 Go | 📅 2024-10-08 :  使用`struct`标记和自动解析将正则表达式命名的组匹配到` go` 结构中。
  * [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) ⭐ 71 | 🐛 1 | 🌐 Go | 📅 2025-06-01 :  敏感词过滤器
  * [Tagify](https://github.com/zoomio/tagify) ⭐ 39 | 🐛 2 | 🌐 HTML | 📅 2024-07-18 :  从给定的源中产生一组标签。
  * [xj2go](https://github.com/stackerzzq/xj2go) ⭐ 36 | 🐛 0 | 🌐 Go | 📅 2021-10-12 :  将`xm`l或`json`转换为`go`结构。
  * [kace](https://github.com/codemodus/kace) ⭐ 22 | 🐛 1 | 🌐 Go | 📅 2018-08-26 :  涵盖常见初始化的普通大小写转换。
  * [TySug](https://github.com/Dynom/TySug) ⭐ 20 | 🐛 4 | 🌐 Go | 📅 2026-07-02 :  关于键盘布局的替代建议。
  * [parseargs-go](https://github.com/nproc/parseargs-go) ⭐ 10 | 🐛 1 | 🌐 Go | 📅 2017-01-24 :  能理解引号和反斜杠的字符串参数解析器。
  * [textwrap](https://github.com/isbm/textwrap) ⭐ 7 | 🐛 1 | 🌐 Go | 📅 2019-08-03 : `Python`中`textwrap`模块的实现。
  * [parth](https://github.com/codemodus/parth) ⚠️ Archived :  `URL`路径分割解析库。

***

## 第三方API

`第三方API 汇总`

* [github](https://github.com/google/go-github) ⭐ 11,277 | 🐛 30 | 🌐 Go | 📅 2026-08-13 :  用于访问`GitHub REST API v3` 的`Go`库。
* [aws-sdk-go](https://github.com/aws/aws-sdk-go) ⚠️ Archived : ` AWS` 提供的官方go语言` SDK`
* [discordgo](https://github.com/bwmarrin/discordgo) ⭐ 5,971 | 🐛 230 | 🌐 Go | 📅 2026-02-14 :   用于与`Discord` 聊天` API`进行交互的`Go`语言客户端。
* [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) ⭐ 4,495 | 🐛 421 | 🌐 Go | 📅 2026-08-14 :`Google Cloud APIs Go`客户端库。
* [google](https://github.com/google/google-api-go-client) ⭐ 4,463 | 🐛 18 | 🌐 Go | 📅 2026-08-16 :  为`Go` 自动生成的`Google API`。
* [minio-go](https://github.com/minio/minio-go) ⭐ 2,991 | 🐛 8 | 🌐 Go | 📅 2026-08-15 :  `go` 语言`Minio` 客户端,用于` Amazon S3` 兼容的云存储
* [stripe](https://github.com/stripe/stripe-go) ⭐ 2,626 | 🐛 11 | 🌐 Go | 📅 2026-08-15 :  用于访问`Stripe API`的`Go`客户端。
* [go-jira](https://github.com/andygrunwald/go-jira) ⭐ 1,616 | 🐛 206 | 🌐 Go | 📅 2026-08-01 :   用于 [Atlassian JIRA](https://www.atlassian.com/software/jira) :  的Go客户端库。
* [go-twitter](https://github.com/dghubble/go-twitter) ⚠️ Archived :  用于`Twitter v1.1 APIs` 的` Go` 客户端库。
* [facebook](https://github.com/huandu/facebook) ⭐ 1,479 | 🐛 1 | 🌐 Go | 📅 2025-06-16 :  支持` Facebook Graph API` 的库
* [githubql](https://github.com/shurcooL/githubql) ⭐ 1,198 | 🐛 42 | 🌐 Go | 📅 2026-02-09 :  用于访问`GitHub GraphQL API v4` 的`Go` 库。
* [anaconda](https://github.com/ChimeraCoder/anaconda) ⭐ 1,137 | 🐛 70 | 🌐 Go | 📅 2024-01-28 : `Twitter 1.1 API`的 go 语言客户端
* [webhooks](https://github.com/go-playground/webhooks) ⭐ 1,027 | 🐛 35 | 🌐 Go | 📅 2024-08-06 : `GitHub` 和`Bitbucket`的`Webhook`接收器
* [twitter-scraper](https://github.com/n0madic/twitter-scraper) ⚠️ Archived :  无需认证和限制就能抓取`Twitter` 前端`API`。
* [paypal](https://github.com/logpacker/PayPal-Go-SDK) ⭐ 778 | 🐛 8 | 🌐 Go | 📅 2026-07-28 : `PayPal`支付`API`
* [geo-golang](https://github.com/codingsince1985/geo-golang) ⭐ 546 | 🐛 7 | 🌐 Go | 📅 2026-04-23 :  用于与  [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro),  [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](http://geocoder.opencagedata.com/api.html), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx) , [Mapbox](https://www.mapbox.com/developers/api/geocoding/) , 及 [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim)  地理编码 / 反编码 APIs 交互的库
* [ethrpc](https://github.com/onrik/ethrpc) ⭐ 271 | 🐛 13 | 🌐 Go | 📅 2024-01-05 : `Ethereum JSON RPC API` 的 Go 绑定
* [Trello](https://github.com/adlio/trello) ⭐ 228 | 🐛 9 | 🌐 Go | 📅 2026-05-03 : `Trello API`的` Go` 语言封装
* [simples3](https://github.com/rhnvrm/simples3) ⭐ 207 | 🐛 13 | 🌐 Go | 📅 2026-05-21 :  简单的不加修饰的`AWS S3`库,使用`Go`编写的`V4 Signing`的`REST api`。
* [go-marathon](https://github.com/gambol99/go-marathon) ⭐ 199 | 🐛 26 | 🌐 Go | 📅 2020-10-01 :  用于与`Mesosphere`的`Marathon PAAS`交互的Go库。
* [wit-go](https://github.com/wit-ai/wit-go) ⭐ 171 | 🐛 0 | 🌐 Go | 📅 2025-09-08 :   用于`wit.ai HTTP API` 的`Go` 客户端。
* [gosip](https://github.com/koltyakov/gosip) ⭐ 170 | 🐛 17 | 🌐 Go | 📅 2026-03-17 :  Go客户端库`SharePoint API`。
* [golang-tmdb](https://github.com/cyruzin/golang-tmdb) ⭐ 164 | 🐛 3 | 🌐 Go | 📅 2026-07-15 :   电影数据库`API v3`的`Golang` 版本`api`
* [pushover](https://github.com/gregdel/pushover) ⭐ 157 | 🐛 1 | 🌐 Go | 📅 2025-09-22 : `Pushover API` 的`Go`语言封装
* [go-trending](https://github.com/andygrunwald/go-trending) ⭐ 147 | 🐛 5 | 🌐 Go | 📅 2026-04-01 :用于访问Github的[trending repositories](https://github.com/trending)库和[developers](https://github.com/trending/developers) : 开发者信息。
* [Medium](https://github.com/Medium/medium-sdk-go) ⭐ 142 | 🐛 6 | 🌐 Go | 📅 2018-10-26 :  用于`Medium`的`OAuth2 API`的`Golang SDK`。
* [gostorm](https://github.com/jsgilmore/gostorm) ⭐ 129 | 🐛 4 | 🌐 Go | 📅 2017-10-09 :` GoStorm`在满足实现了`Bolts`与`Storm`外壳通信所需的通信协议的基础上实现了Storm接口
* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) ⭐ 111 | 🐛 1 | 🌐 Go | 📅 2017-06-12 :  通过`XMPP`与`Hipchat`通信的`golang`包。
* [hipchat](https://github.com/andybons/hipchat) ⭐ 104 | 🐛 0 | 🌐 Go | 📅 2016-03-24 :  这个项目为`Hipchat API`实现了一个`golang`客户端库
* [cachet](https://github.com/andygrunwald/cachet) ⭐ 90 | 🐛 1 | 🌐 Go | 📅 2021-06-22 : ` Cachet`（开源状态页系统）的Go客户端库。
* [gogtrends](https://github.com/groovili/gogtrends) ⭐ 89 | 🐛 4 | 🌐 Go | 📅 2023-01-04 : `Google Trends` 非官方`API`。
* [airtable](https://github.com/mehanizm/airtable) ⭐ 86 | 🐛 5 | 🌐 Go | 📅 2025-03-14 :  用于访问`Airtable API`的 Go 客户端库。[Airtable API](https://airtable.com/api) :
* [go-postman-collection](https://github.com/rbretecher/go-postman-collection) ⭐ 85 | 🐛 2 | 🌐 Go | 📅 2024-05-17 :  Go 模块,用于与 [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) :   进行交互（与 Insomnia 兼容）。
* [igdb](https://github.com/Henry-Sarabia/igdb) ⭐ 85 | 🐛 3 | 🌐 Go | 📅 2023-01-30 :  [Internet Game Database API](https://api.igdb.com/) :的Go客户端。
* [google-play-scraper](https://github.com/n0madic/google-play-scraper) ⚠️ Archived :  从\`Google Play商店获取数据。
* [go-unsplash](https://github.com/hbagdi/go-unsplash) ⭐ 79 | 🐛 10 | 🌐 Go | 📅 2026-08-09 :   用于[Unsplash.com](https://unsplash.com)`API` 的 Go 客户端库。
* [ynab](https://github.com/brunomvsouza/ynab.go) ⭐ 79 | 🐛 0 | 🌐 Go | 📅 2026-08-11 : `YNAB API`的`Go`语言封装。
* [circleci](https://github.com/jszwedko/go-circleci) ⭐ 65 | 🐛 3 | 🌐 Go | 📅 2024-01-27 :  用于和`with CircleCI's API`进行交互的` Go` 语言客户端
* [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) ⭐ 63 | 🐛 7 | 🌐 Go | 📅 2023-05-15 :   `Go MusicBrainz WS2`客户端库。
* [mixpanel](https://github.com/dukex/mixpanel) ⚠️ Archived : `Mixpanel` 是用于追踪事件并发送`Mixpanel profile`的更新到` Mixpanel` 的库
* [uptimerobot](https://github.com/bitfield/uptimerobot) ⭐ 60 | 🐛 13 | 🌐 Go | 📅 2023-04-22 :  `Uptime Robot v2 API`的`Go`包装器和命令行客户端。
* [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) ⭐ 57 | 🐛 3 | 🌐 Go | 📅 2018-04-05 : ` Amazon Product Advertising API` 的 Go 客户端库。 [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html) :
* [megos](https://github.com/andygrunwald/megos) ⭐ 54 | 🐛 0 | 🌐 Go | 📅 2021-06-22 :  用于访问A`pache Mesos`集群的客户端库。
* [spotify](https://github.com/rapito/go-spotify) ⭐ 53 | 🐛 0 | 🌐 Go | 📅 2024-09-09 :   访问`Spotify WEB API` 的`Go` 库。
* [fcm](https://github.com/maddevsio/fcm) ⭐ 52 | 🐛 2 | 🌐 Go | 📅 2020-03-06 :  用于`Firebase Cloud Messaging` 的 Go 库。
* [gads](https://github.com/emiddleton/gads) ⭐ 51 | 🐛 8 | 🌐 Go | 📅 2021-12-13 :  `Google Adwords` 非官方 API
* [go-xkcd](https://github.com/nishanths/go-xkcd) ⭐ 51 | 🐛 0 | 🌐 Go | 📅 2022-10-23 :   -`xkcd API` 的` Go` 客户端。
* [patreon-go](https://github.com/mxpv/patreon-go) ⭐ 46 | 🐛 1 | 🌐 Go | 📅 2022-09-01 : `Patreon API.`
* [go-myanimelist](https://github.com/nstratos/go-myanimelist) ⭐ 45 | 🐛 3 | 🌐 Go | 📅 2026-05-31 :  用于访问 [MyAnimeList API](http://myanimelist.net/modules.php?go=api) :  的 Go 客户端库。
* [golyrics](https://github.com/mamal72/golyrics) ⭐ 41 | 🐛 0 | 🌐 Go | 📅 2018-06-30 : 用于从`Wikia` 网站获取音乐歌词数据的 Go 库。
* [gami](https://github.com/bit4bit/gami) ⚠️ Archived : `Asterisk Manager Interface` 的 Go 语言库
* [steam](https://github.com/sostronk/go-steam) ⭐ 33 | 🐛 2 | 🌐 Go | 📅 2024-06-08:用于与`Steam`游戏服务器交互的`Go` 库。
* [translate](https://github.com/poorny/translate) ⚠️ Archived : ` Go` 在线翻译包
* [lastpass-go](https://github.com/ansd/lastpass-go) ⭐ 32 | 🐛 3 | 🌐 Go | 📅 2023-05-25 : [LastPass](https://www.lastpass.com/) : API的Go客户端库。
* [gcm](https://github.com/Aorioli/gcm) ⭐ 31 | 🐛 0 | 🌐 Go | 📅 2015-12-04 : `Google Cloud Messaging` 库
* [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) ⭐ 27 | 🐛 0 | 🌐 Go | 📅 2026-08-05 :  `Go`客户端库,用于与`Coinpaprika的API`进行交互。
* [shopify](https://github.com/rapito/go-shopify) ⭐ 25 | 🐛 2 | 🌐 Go | 📅 2020-12-03 :  用于接入`Spotify WEB API` 的`G`o 语言库
* [go-imgur](https://github.com/koffeinsource/go-imgur) ⭐ 23 | 🐛 4 | 🌐 Go | 📅 2024-07-03 :  用于[imgur](https://imgur.com) 的Go客户端库。
* [textbelt](https://github.com/dietsche/textbelt) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2015-09-04 :  `textbelt.com txt messaging API` 的`go`语言客户端
* [brewerydb](https://github.com/naegelejd/brewerydb) ⭐ 20 | 🐛 5 | 🌐 Go | 📅 2015-06-18 :   用于访问`BreweryDB API`的 Go 语言库
* [go-aws-news](https://github.com/circa10a/go-aws-news) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2026-02-21 :   用于从`AWS`获取最新信息的 Go 应用程序和库。
* [codeship-go](https://github.com/codeship/codeship-go) ⭐ 18 | 🐛 1 | 🌐 Go | 📅 2020-11-03 :  用于与` Codeship`的`API v2` 进行交互的` Go`客户端库。
* [slack](https://github.com/nlopes/slack) ⚠️ Archived :   `Slack API`
* [go-hacknews](https://github.com/PaulRosset/go-hacknews) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2017-08-15 :  `HackerNews API`的Go客户端。
* [gopaapi5](https://github.com/utekaravinash/gopaapi5) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2020-04-03 :   [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/) :  API 5.0的Go客户端库。
* [google-analytics](https://github.com/chonthu/go-google-analytics) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2015-06-09谷歌分析报告go语言客户端。
* [go-here](https://github.com/abdullahselek/go-here) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2020-06-23 :  围绕`HERE`基于位置的`API`的Go客户端库。
* [gomalshare](https://github.com/MonaxGT/gomalshare) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2019-04-29 : ` Go library MalShare API`。 [malshare.com](http://www.malshare.com/) :
* [go-sophos](https://github.com/esurdam/go-sophos) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2022-05-06 :  Go客户端库,用于零依赖的 [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) :
* [rawg-sdk-go](https://github.com/dimuska139/rawg-sdk-go) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2022-05-28 :  用于`RAWG`视频游戏数据库`API`的G`o`库。[RAWG Video Games Database](https://rawg.io/) :
* [go-sptrans](https://github.com/sergioaugrod/go-sptrans) ⚠️ Archived :   用于SPTrans Olho Vivo API的Go客户端库。
* [smite](https://github.com/sergiotapia/smitego) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2014-07-18 :  `Go`包,用于包装对`Smite`游戏`API`的访问。
* [libgoffi](https://github.com/clevabit/libgoffi) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2020-08-23 :  用于本地 [libffi](http://sourceware.org/libffi/)   集成的库适配器工具箱。
* [rrdaclient](https://github.com/Omie/rrdaclient) ⚠️ Archived :  访问`statdns.com API`,这是通过HTTP进行DNS查询的`RRDA API`。
* [go-chronos](https://github.com/axelspringer/go-chronos) ⚠️ Archived :  用于与[Chronos](https://mesos.github.io/chronos/) :   Job Scheduler交互的Go库。
* [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) ⚠️ Archived : :[Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/) :  的Go客户端库。
* [tumblr](https://github.com/mattcunningham/gumblr) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2016-10-30 : `Tumblr v2 API` 的`Go` 语言封装
* [zooz](https://github.com/gojuno/go-zooz) ⭐ 7 | 🐛 1 | 🌐 Go | 📅 2024-03-06 :  `Zooz API` 的`Go`语言客户端
* [kanka](https://github.com/Henry-Sarabia/kanka) ⭐ 3 | 🐛 2 | 🌐 Go | 📅 2020-08-06 :  [Kanka API](https://kanka.io/en-US/docs/1.0)   的Go客户端
* [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2016-03-06 :`Playlyfe Rest API`的`Go` 语言`SDK`
* [TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2019-10-23 :` TripAdvisor AP`I的Go语言封装。
* [vl-go](https://github.com/verifid/vl-go) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2021-05-30 :  VerifID身份验证层`API`的`Go`客户端库。
* [Cachet (open source status page system)](https://cachethq.io/) :  `Cachet (open source status page system)`的 Go 语言客户端
* [clarifai](https://github.com/samuelcouch/clarifai) :  用于和` Clarifai API` 交互的`Go`语言库
* [go-telegraph](https://gitlab.com/toby3d/telegraph) :  `Telegraph`发布平台API客户端。
* [go-twitch](https://github.com/knspriggs/go-twitch) :   用于与Twitch v3 API交互的Go客户端。

***

## 工具库

`可以提升效率的通用代码库和工具`

* [fzf](https://github.com/junegunn/fzf) ⭐ 82,545 | 🐛 327 | 🌐 Go | 📅 2026-08-14 :  命令行模糊查找工具
* [hub](https://github.com/github/hub) ⭐ 22,957 | 🐛 294 | 🌐 Go | 📅 2024-02-02 :  封装了`git`命令,提供了额外的功能用于在终端中和`Github` 进行交互
* [ctop](https://github.com/bcicen/ctop) ⭐ 17,823 | 🐛 121 | 🌐 Go | 📅 2024-07-08 :  用于容器指标,类似于`Top`的接口（例如`htop`）。
* [sqlx](https://github.com/jmoiron/sqlx) ⭐ 17,726 | 🐛 393 | 🌐 Go | 📅 2024-08-15 :  为内建的`database/sql` 软件包提供扩展
* [goreleaser](https://github.com/goreleaser/goreleaser) ⭐ 15,990 | 🐛 20 | 🌐 Go | 📅 2026-08-16 : 尽可能快速的发布`Go`语言二进制文件
* [Task](https://github.com/go-task/task) ⭐ 15,979 | 🐛 193 | 🌐 Go | 📅 2026-08-16 :  简单来讲就是`"Make"`的替代品
* [wuzz](https://github.com/asciimoo/wuzz) ⭐ 10,717 | 🐛 42 | 🌐 Go | 📅 2026-08-04 :   交互式命令行程序,用于进行`HTTP` 检查
* [usql](https://github.com/knq/usql) ⭐ 10,072 | 🐛 119 | 🌐 Go | 📅 2026-06-19 :  `usql`是一个通用的命令行接口,用于操作`sql`数据库
* [peco](https://github.com/peco/peco) ⭐ 7,908 | 🐛 10 | 🌐 Go | 📅 2026-08-01 :  简单的交互式过滤工具。
* [go-funk](https://github.com/thoas/go-funk) ⭐ 4,932 | 🐛 11 | 🌐 Go | 📅 2024-07-24 :  `Go`语言工具库,提供了很多有用的工具`(map, find, contains, filter, chunk, reverse, ...)`
* [realize](https://github.com/tockins/realize) ⭐ 4,435 | 🐛 72 | 🌐 Go | 📅 2021-05-14 : `Go` 语言构建系统,可以监控文件变化并重新加载。运行,构建,监控文件并支持自定义路径
* [hystrix-go](https://github.com/afex/hystrix-go) ⭐ 4,399 | 🐛 57 | 🌐 Go | 📅 2024-02-24 :  实现 Hystrix 风格的、程序员预定义的`fallback` 机制（熔断）
* [godropbox](https://github.com/dropbox/godropbox) ⭐ 4,203 | 🐛 6 | 🌐 Go | 📅 2023-12-24 : `Dropbox`开发的用于编写` Go`语言服务／应用的库
* [minify](https://github.com/tdewolff/minify) ⭐ 4,132 | 🐛 37 | 🌐 Go | 📅 2026-08-16 :  快速压缩`HTML, CSS, JS, XML, JSON` 以及` SVG` 文件格式
* [panicparse](https://github.com/maruel/panicparse) ⭐ 3,709 | 🐛 3 | 🌐 Go | 📅 2026-07-13 :   将类似的`goroutines`分组,并对堆栈转储进行着色。
* [mc](https://github.com/minio/mc) ⚠️ Archived :  `Minio Client`提供了与` Amazon S3`兼容的云存储和文件系统管理工具。
* [goreporter](https://github.com/wgliang/goreporter) ⭐ 3,120 | 🐛 30 | 🌐 Go | 📅 2018-10-27 :  进行代码静态分析,单元测试,代码检视并生成代码质量报告的工具
* [mergo](https://github.com/imdario/mergo) ⭐ 3,106 | 🐛 24 | 🌐 Go | 📅 2026-03-23 :  Golang中合并结构和地图的助手。对配置默认值很有用,避免了混乱的if语句。
* [create-go-app](https://github.com/create-go-app/cli) ⭐ 2,764 | 🐛 13 | 🌐 Go | 📅 2026-02-10 :  通过运行一个命令就可以创建一个新的生产就绪项目,包括后端（`Golang`）、前端（`JavaScript、TypeScript`）和部署自动化（`Ansible、Docker`）的强大的`CLI`。
* [spinner](https://github.com/briandowns/spinner) ⭐ 2,531 | 🐛 20 | 🌐 Go | 📅 2025-01-20 : ` Go` 语言软件包,提供多种选项,方便在终端中创建加载动画
* [filetype](https://github.com/h2non/filetype) ⭐ 2,296 | 🐛 52 | 🌐 Go | 📅 2026-07-01 :  用于推断文件类型的小程序包,它可以检查魔法数字签名。
* [Storm](https://github.com/asdine/storm) ⭐ 2,091 | 🐛 64 | 🌐 Go | 📅 2024-01-07 :  用于`BoltDB` 的简单又强大的工具
* [mimetype](https://github.com/gabriel-vasile/mimetype) ⭐ 2,007 | 🐛 33 | 🌐 Go | 📅 2026-08-10 :  基于魔数的`MIME`类型检测包。
* [jump](https://github.com/gsamokovarov/jump) ⭐ 1,943 | 🐛 2 | 🌐 Go | 📅 2026-08-06 : `Jump`通过学习你的习惯来帮助你更快地浏览文件。
* [boilr](https://github.com/tmrts/boilr) ⭐ 1,763 | 🐛 44 | 🌐 Go | 📅 2023-03-07 :  用于从模板中快速创建项目的`CLI`工具。
* [mmake](https://github.com/tj/mmake) ⭐ 1,737 | 🐛 11 | 🌐 Go | 📅 2023-07-01 :  现代`Make`工具
* [mole](https://github.com/davrodpin/mole) ⭐ 1,723 | 🐛 29 | 🌐 Go | 📅 2024-05-13 :  用于轻松创建ssh隧道的`cli`应用程序。
* [scany](https://github.com/georgysavva/scany) ⭐ 1,521 | 🐛 3 | 🌐 Go | 📅 2025-03-19 :  用于将数据库中的数据扫描成` Go`结构等的库。
* [hostctl](https://github.com/guumaster/hostctl) ⭐ 1,233 | 🐛 19 | 🌐 Go | 📅 2024-01-26 :  用简单的命令管理`/etc/hosts` 的` CLI`工具。
* [circuitbreaker](https://github.com/rubyist/circuitbreaker) ⭐ 1,164 | 🐛 22 | 🌐 Go | 📅 2024-05-15 :  `Go`中的断路器。
* [git-time-metric](https://github.com/git-time-metric/gtm) ⭐ 1,003 | 🐛 52 | 🌐 Go | 📅 2022-01-31 :  简单、无缝、轻量级的` Git`时间跟踪。
* [immortal](https://github.com/immortal/immortal) ⭐ 837 | 🐛 2 | 🌐 Go | 📅 2026-08-16 :  \*nix 跨平台 (与操作系统无关的)监控程序
* [circuit](https://github.com/cep21/circuit) ⭐ 813 | 🐛 6 | 🌐 Go | 📅 2026-07-16 :  高效且功能完整的`Hystrix`断路器模式的`go`语言实现
* [clockwork](https://github.com/jonboulle/clockwork) ⭐ 728 | 🐛 12 | 🌐 Go | 📅 2025-11-21 :  使用简单、流畅的语法来调度周期性任务
* [delve](https://github.com/derekparker/delve) ⭐ 661 | 🐛 2 | 🌐 Go | 📅 2026-08-14 : `Go`语言调试器
* [limiters](https://github.com/mennanov/limiters) ⭐ 652 | 🐛 1 | 🌐 Go | 📅 2026-08-01 : `Golang`中分布式应用的速率限制器,具有可配置的后端和分布式锁。
* [ergo](https://github.com/cristianoliveira/ergo) ⭐ 651 | 🐛 8 | 🌐 Go | 📅 2025-02-02 :  简化了对运行在不同端口的多个本地服务的管理。
* [scan](https://github.com/blockloop/scan) ⭐ 614 | 🐛 1 | 🌐 Go | 📅 2026-07-09 :  直接将`golang sql.Rows`扫描为` structs、slices`或`primitive`类型。
* [htcat](https://github.com/htcat/htcat) ⭐ 557 | 🐛 4 | 🌐 Go | 📅 2025-08-27 :   并行及流水线的` HTTP GET` 工具
* [koazee](https://github.com/wesovilabs/koazee) ⭐ 529 | 🐛 14 | 🌐 Go | 📅 2020-11-18 :  受`Lazy`评估和函数式编程启发而开发的库,它消除了使用数组的麻烦。
* [countries](https://github.com/biter777/countries) ⭐ 523 | 🐛 22 | 🌐 Go | 📅 2024-05-30 :   完全执行`ISO-3166-1、ISO-4217、ITU-T E.164、Unicode CLDR和IANA ccTLD`标准的库。
* [gubrak](https://github.com/novalagung/gubrak) ⭐ 513 | 🐛 0 | 🌐 Go | 📅 2026-05-02 :  带有语法糖的` Golang`工具库。它类似于`lodash`,但适用于` golang`。
* [godaemon](https://github.com/VividCortex/godaemon) ⭐ 493 | 🐛 9 | 🌐 Go | 📅 2021-06-29 :  用于编写守护进程的工具
* [go-dry](https://github.com/ungerik/go-dry) ⭐ 488 | 🐛 0 | 🌐 Go | 📅 2025-10-17 :  `go`语言中`DRY (don't repeat yourself)`包
* [Deepcopier](https://github.com/ulule/deepcopier) ⭐ 460 | 🐛 7 | 🌐 Go | 📅 2020-04-30 : ` Go`的简单结构拷贝库。
* [gopencils](https://github.com/bndr/gopencils) ⭐ 453 | 🐛 8 | 🌐 Go | 📅 2019-02-18 :`Go`语言库,能够很容易的使用各种` REST APIs`.
* [request](https://github.com/mozillazg/request) ⭐ 422 | 🐛 6 | 🌐 Go | 📅 2019-12-05 :` Go`语言版的`HTTP Requests for Humans™`.
* [go-rate](https://github.com/beefsack/go-rate) ⭐ 406 | 🐛 0 | 🌐 Go | 📅 2022-02-14 : ` Go` 语言版本的限速器
* [serve](https://github.com/syntaqx/serve) ⭐ 351 | 🐛 0 | 🌐 Go | 📅 2026-08-15 :  静态` http`服务器。
* [retry](https://github.com/kamilsk/retry) ⭐ 343 | 🐛 10 | 🌐 Go | 📅 2026-07-22 :    最先进的功能机制,用于重复执行动作直到成功。
* [taskctl](https://github.com/taskctl/taskctl) ⭐ 326 | 🐛 2 | 🌐 Go | 📅 2026-07-20 :  并发任务运行库。
* [gotenv](https://github.com/subosito/gotenv) ⭐ 310 | 🐛 2 | 🌐 Go | 📅 2025-11-10 :  从 .env 或者任何`io.Reader`中加载环境变量
* [util](https://github.com/shomali11/util) ⭐ 299 | 🐛 1 | 🌐 Go | 📅 2022-07-17 : 收集了很多有用的函数
* [pattern-match](https://github.com/alexpantyukhin/go-pattern-match) ⭐ 251 | 🐛 2 | 🌐 Go | 📅 2023-03-01 : 模式匹配库
* [go-trigger](https://github.com/sadlil/go-trigger) ⭐ 250 | 🐛 1 | 🌐 Go | 📅 2017-03-28 :` Go`语言全局事件触发器,通过 id 和触发器,在程序的任何地方注册事件
* [gohper](https://github.com/cosiner/gohper) ⚠️ Archived :  能够帮助你进行软件开发的工具和模块
* [toolbox](https://github.com/viant/toolbox) ⭐ 231 | 🐛 5 | 🌐 Go | 📅 2026-01-07 :  `slice, map, multimap`, 结构体, 函数,数据转换工具、服务路由,宏求值和标记器工具
* [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) ⭐ 230 | 🐛 29 | 🌐 Go | 📅 2024-07-10 :`XML`网站地图生成器
* [Death](https://github.com/vrecan/death) ⭐ 198 | 🐛 0 | 🌐 Go | 📅 2024-12-16 :  -利用信号管理应用程序的关闭
* [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) ⭐ 180 | 🐛 0 | 🌐 Go | 📅 2019-08-29 :  用于包装` golang` 插件导出的符号的`go:generation`工具 (仅限 1.8)。
* [go-bsdiff](https://github.com/gabstv/go-bsdiff) ⭐ 172 | 🐛 1 | 🌐 Go | 📅 2019-03-21 :  纯粹的`Go bsdiff` 和`bspatch`库以及`CLI` 工具。
* [apm](https://github.com/topfreegames/apm) ⭐ 169 | 🐛 9 | 🌐 Go | 📅 2016-11-24 : 具有`HTTP API`的`Go`语言进程管理工具.
* [moldova](https://github.com/StabbyCutyou/moldova) ⭐ 168 | 🐛 0 | 🌐 Go | 📅 2017-09-04 :  基于输入目标生成随机数据的工具
* [rerun](https://github.com/ivpusic/rerun) ⭐ 164 | 🐛 0 | 🌐 Go | 📅 2018-03-22 :  当源码发生变化时,重新编译和重新运行`go`应用程序。
* [chyle](https://github.com/antham/chyle) ⭐ 163 | 🐛 1 | 🌐 Go | 📅 2026-07-30 :  使用`git`仓库的变更日志生成器,具有多种配置
* [cmd](https://github.com/SimonBaeumer/cmd) ⭐ 161 | 🐛 1 | 🌐 Go | 📅 2025-02-14 :  用于在` osx、windows`和`linux`上执行`shell`命令的库。
* [robustly](https://github.com/VividCortex/robustly) ⭐ 159 | 🐛 1 | 🌐 Go | 📅 2023-12-12 :   弹性地运行函数,捕捉和重启 并自动处理`panic`。
* [filter](https://github.com/gookit/filter) ⭐ 151 | 🐛 1 | 🌐 Go | 📅 2026-08-04 :  提供` Go`数据的过滤、净化和转换。
* [nostromo](https://github.com/pokanop/nostromo) ⭐ 150 | 🐛 14 | 🌐 Go | 📅 2026-07-20 :  用于构建强大别名的`CLI`。
* [sorty](https://github.com/jfcg/sorty) ⭐ 145 | 🐛 0 | 🌐 Go | 📅 2026-05-21 :  快速并发/并行排序。
* [onecache](https://github.com/adelowo/onecache) ⭐ 135 | 🐛 0 | 🌐 Go | 📅 2020-05-25 :  支持多个后端存储的缓存库（`Redis、Memcached`、文件系统等）。
* [mongo-go-pagination](https://github.com/gobeam/mongo-go-pagination) ⭐ 131 | 🐛 3 | 🌐 Go | 📅 2023-03-07官方`mongodb/mongo-go-driver`包的`Mongodb Pagination`,支持普通查询和聚合管道。
* [lrserver](https://github.com/jaschaephraim/lrserver) ⭐ 128 | 🐛 0 | 🌐 JavaScript | 📅 2024-03-06 :` Go`的`LiveReload`服务器。
* [go-lock](https://github.com/viney-shih/go-lock) ⭐ 127 | 🐛 0 | 🌐 Go | 📅 2022-06-18 : ` go-lock` 是一个实现读写互斥和读写试锁的无饥饿状态的锁库。
* [goseaweedfs](https://github.com/linxGnu/goseaweedfs) ⭐ 119 | 🐛 2 | 🌐 Go | 📅 2022-11-11 :  具有几乎全部功能的`SeaweedFS`客户端库。
* [mssqlx](https://github.com/linxGnu/mssqlx) ⭐ 103 | 🐛 3 | 🌐 Go | 📅 2024-04-29 :  数据库客户端库,代理任何主从,主主结构。考虑到轻量级和自动平衡。
* [mimemagic](https://github.com/zRedShift/mimemagic) ⭐ 99 | 🐛 6 | 🌐 Go | 📅 2023-10-11 : 纯`go`语言实现的超强的MIME嗅探库/工具。
* [xferspdy](https://github.com/monmohan/xferspdy) ⭐ 99 | 🐛 3 | 🌐 Go | 📅 2021-04-04 :  `Xferspdy` 提供了二进制比对以及`patch`补丁功能
* [go-health](https://github.com/Talento90/go-health) ⭐ 97 | 🐛 0 | 🌐 Go | 📅 2022-01-19 : 简化了你在服务中添加健康检查的方式。
* [equalizer](https://github.com/reugn/equalizer) ⭐ 89 | 🐛 0 | 🌐 Go | 📅 2024-03-14 :  `Go`的配额管理器和速率限制器。
* [pgo](https://github.com/arthurkushman/pgo) ⭐ 88 | 🐛 1 | 🌐 Go | 📅 2026-05-05 :  为PHP社区提供方便的功能。
* [gaper](https://github.com/maxcnunes/gaper) ⭐ 83 | 🐛 2 | 🌐 Go | 📅 2023-08-08 :  当` Go` 项目崩溃或某些监视文件发生变化时,构建并重新启动该项目。
* [handy](https://github.com/miguelpragier/handy) ⭐ 83 | 🐛 0 | 🌐 Go | 📅 2020-09-30 :  许多实用工具和帮助程序,如字符串处理程序/格式化程序和验证器。
* [repeat](https://github.com/ssgreg/repeat) ⭐ 83 | 🐛 0 | 🌐 Go | 📅 2020-07-24 : ` Go`实现不同的回退策略,对重试操作和心跳有用。
* [pm](https://github.com/VividCortex/pm) ⭐ 79 | 🐛 2 | 🌐 Go | 📅 2023-12-12 :  带有` HTTP API` 的进程（即`goroutine`）管理器。
* [netbug](https://github.com/e-dard/netbug) ⭐ 72 | 🐛 0 | 🌐 Go | 📅 2015-10-29 :  轻松地对你的服务进行远程剖析。
* [multitick](https://github.com/VividCortex/multitick) ⭐ 71 | 🐛 1 | 🌐 Go | 📅 2023-12-12 :   多路复用器
* [backscanner](https://github.com/icza/backscanner) ⭐ 70 | 🐛 0 | 🌐 Go | 📅 2024-11-24 :   类似于` bufio.Scanner` 的扫描器,但它以反向顺序读取并返回结果。
* [dbt](https://github.com/nikogura/dbt) ⭐ 70 | 🐛 6 | 🌐 Go | 📅 2026-05-06 :  从中央可信仓库运行自更新签名二进制文件的框架。
* [UNIS](https://github.com/esemplastic/unis) ⭐ 70 | 🐛 2 | 🌐 Go | 📅 2017-05-09 :  `Go`语言字符串处理函数的通用架构
* [goreadability](https://github.com/philipjkim/goreadability) ⭐ 68 | 🐛 2 | 🌐 Go | 📅 2019-04-22 :   使用`Facebook Open Graph`和`arc90`的可读性提取网页摘要。
* [retry](https://github.com/thedevsaddam/retry) ⭐ 67 | 🐛 0 | 🌐 Go | 📅 2026-04-22 : `Go`中简单易行的重试机制包。
* [go-astitodo](https://github.com/asticode/go-astitodo) ⭐ 65 | 🐛 1 | 🌐 Go | 📅 2024-04-22 :   解析`GO`代码中的`todo`事项。
* [golog](https://github.com/mlimaloureiro/golog) ⭐ 63 | 🐛 15 | 🌐 Go | 📅 2019-01-22 :  简单、轻量级的命令后工具,用于对你的计划任务进行跟踪
* [minquery](https://github.com/icza/minquery) ⭐ 61 | 🐛 4 | 🌐 Go | 📅 2023-03-31 :  `MongoDB / mgo.v2`查询,支持高效的分页。
* [shutdown](https://github.com/ztrue/shutdown) ⭐ 60 | 🐛 0 | 🌐 Go | 📅 2022-01-15 :   用于`os.Signal` 处理的应用程序关机钩子。
* [copy-pasta](https://github.com/jutkko/copy-pasta) ⭐ 56 | 🐛 10 | 🌐 Go | 📅 2020-06-20 :  通用多工作站剪切板,使用类似` S3` 的后端作为存储
* [ghokin](https://github.com/antham/ghokin) ⭐ 56 | 🐛 0 | 🌐 Go | 📅 2026-07-14 :  并行化的格式化程序,不需要对`gherkin (cucumber, behat...)`,的外部依赖。
* [beyond](https://github.com/wesovilabs/beyond) ⭐ 55 | 🐛 10 | 🌐 Go | 📅 2023-04-11 :  `Go`工具,它将推动你进入`AOP`世界!
* [golarm](https://github.com/msempere/golarm) ⭐ 54 | 🐛 0 | 🌐 Go | 📅 2015-08-24 : 告警（支持系统事件）库
* [copy](https://github.com/gotidy/copy) ⭐ 51 | 🐛 4 | 🌐 Go | 📅 2020-12-28 :  用于快速复制不同类型结构的软件包。
* [slice](https://github.com/psampaz/slice) ⭐ 51 | 🐛 1 | 🌐 Go | 📅 2020-04-09 :  用于常见` Go`分片操作的类型安全函数。
* [goback](https://github.com/carlescere/goback) ⭐ 50 | 🐛 6 | 🌐 Go | 📅 2021-03-09 :` Go`语言的简单的指数补偿包
* [retry-go](https://github.com/rafaeljesus/retry-go) ⭐ 49 | 🐛 2 | 🌐 Go | 📅 2018-10-25 :   为`golang`提供简单易行的重试。
* [go-httpheader](https://github.com/mozillazg/go-httpheader) ⭐ 47 | 🐛 0 | 🌐 Go | 📅 2023-07-15 :  用于将结构体编码进` http` 头的` Go` 语言库
* [gostrutils](https://github.com/ik5/gostrutils) ⭐ 47 | 🐛 1 | 🌐 Go | 📅 2024-06-30 :  字符串操作和转换函数的集合。
* [intrinsic](https://github.com/mengzhuo/intrinsic) ⚠️ Archived :  不需要编写任何汇编代码就能使用`x86 SIMD`
* [slicer](https://github.com/leaanthony/slicer) ⭐ 47 | 🐛 0 | 🌐 Go | 📅 2021-08-08 :  让分片的工作更容易。
* [evaluator](https://github.com/nullne/evaluator) ⭐ 42 | 🐛 0 | 🌐 Go | 📅 2023-04-14 :   基于`s-expression`动态地评估一个表达式。简单且易于扩展。
* [gpath](https://github.com/tenntenn/gpath) ⭐ 41 | 🐛 0 | 🌐 Go | 📅 2017-06-04 :   用于简化结构体域访问的库
* [rclient](https://github.com/zpatrick/rclient) ⭐ 36 | 🐛 2 | 🌐 Go | 📅 2019-11-28 :  可读性良好、灵活、易用的`REST APIs` 客户端
* [tome](https://github.com/cyruzin/tome) ⭐ 35 | 🐛 1 | 🌐 Go | 📅 2022-04-20 :  `Tome`被设计用来对`RESTful API`进行简单分页。
* [mimesniffer](https://github.com/aofei/mimesniffer) ⚠️ Archived :` Go`的`MIME` 类型嗅探器。
* [myhttp](https://github.com/inancgumus/myhttp) ⚠️ Archived :  支持超时的`HTTP GET`请求的简单`API`。
* [generate](https://github.com/go-playground/generate) ⭐ 31 | 🐛 0 | 🌐 Go | 📅 2017-01-10 :  针对一个路径或环境变量,递归的执行` Go generate`,可以通过正则表达式来进行过滤
* [ptr](https://github.com/gotidy/ptr) ⭐ 30 | 🐛 0 | 🌐 Go | 📅 2023-06-06 :   提供从基本类型的常量中简化创建指针的函数的包。
* [goplaceholder](https://github.com/michiwend/goplaceholder) ⭐ 29 | 🐛 1 | 🌐 Go | 📅 2016-01-17 :  用于生成占位符图片的小`golang`库。
* [rerate](https://github.com/abo/rerate) ⭐ 29 | 🐛 1 | 🌐 Go | 📅 2017-03-28 :  `Go`的基于`Redis`的速率计数器和速率限制器。
* [ctxutil](https://github.com/posener/ctxutil) ⭐ 26 | 🐛 1 | 🌐 Go | 📅 2020-03-01 :  用于上下文`context`的实用函数集合。
* [ugo](https://github.com/alxrm/ugo) ⚠️ Archived :  `uGo`是一个切片工具箱。
* [go-convert](https://github.com/Eun/go-convert) ⭐ 24 | 🐛 2 | 🌐 Go | 📅 2024-05-08 : `go-convert` 使您能够将一个值转换为另一种类型。
* [structs](https://github.com/PumpkinSeed/structs) ⭐ 24 | 🐛 0 | 🌐 Go | 📅 2017-10-23 :  实现简单的函数来操作结构。
* [jsend](https://github.com/clevergo/jsend) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2021-06-29 : `JSend`的实现是用`Go`编写的。
* [filler](https://github.com/yaronsumel/filler) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2017-04-10 :   使用`"fill "`标签来填充结构的小工具。
* [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2020-02-17 :   用于处理问题细节的` Go`包。
* [dlog](https://github.com/kirillDanshin/dlog) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2017-07-28 :  编译时控制的日志,让你的`release` 包变得更小而不需移除` debug`调用
* [go-countries](https://github.com/mikekonan/go-countries) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2020-12-17 :   轻量级的ISO-3166代码查询。
* [okrun](https://github.com/xta/okrun) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2014-10-06 : `golang error`流式处理库
* [rest-go](https://github.com/edermanoel94/rest-go) ⭐ 15 | 🐛 1 | 🌐 Go | 📅 2020-08-16 :   提供许多有用的方法来使用`rest api`的包。
* [command](https://github.com/txgruppi/command) ⚠️ Archived :   命令模式,支持线程安全的串行、并行调度
* [silk](https://github.com/chrispassas/silk) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2026-08-12 :  读取` silk netflow`文件。
* [blank](https://github.com/Henry-Sarabia/blank) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2019-07-31 :  验证或删除字符串中的空白和空白字符。
* [retry](https://github.com/shafreeck/retry) ⭐ 13 | 🐛 1 | 🌐 Go | 📅 2020-02-11 :  确保工作能够完成的`go`语言库。
* [goctx](https://github.com/zerosnake0/goctx) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2020-11-24 :  获取高性能的上下文值。
* [nfdump](https://github.com/chrispassas/nfdump) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2026-08-12 :   读取`nfdump netflow`文件。
* [retry](https://github.com/percolate/retry) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2023-03-16 :  简单但高度可配置的`Go`重试包。
* [statiks](https://github.com/janiltonmaciel/statiks) ⭐ 11 | 🐛 2 | 🌐 Go | 📅 2025-04-16 :  快速、零配置、静态的HTTP文件服务器。
* [sliceconv](https://github.com/Henry-Sarabia/sliceconv) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2020-02-03 :  原始类型之间的切片转换。
* [lets-go](https://github.com/aplescia-chwy/lets-go) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2021-04-24 : `Go`模块,为云原生REST API开发提供了常用的实用工具。还包含AWS特定的实用程序。
* [olaf](https://github.com/btnguyen2k/olaf) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2019-04-10 :  在Go中实现的`Twitter Snowflake`。
* [tik](https://github.com/andy2046/tik) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2020-10-17 :  为`Go`提供简单方便的定时任务调度包。
* [go-safe](https://github.com/kenkyu392/go-safe) :` panic`处理安全沙盒。
* [r](https://github.com/is5/r) :  类似于`Python` 的` range()` 的` Go` 库

***

## UUID

`UUID 生成和操作库`

* [uuid](https://github.com/google/uuid) ⭐ 6,135 | 🐛 64 | 🌐 Go | 📅 2024-11-14 :  基于`RFC 4122`和`DCE 1.1`的`UUIDs Go`包。
* [ulid](https://github.com/oklog/ulid) ⭐ 5,050 | 🐛 7 | 🌐 Go | 📅 2026-07-23 : `ULID (Universally Unique Lexicographically Sortable Identifier)` 的` Go`实现。
* [uuid](https://github.com/gofrs/uuid) ⭐ 1,811 | 🐛 3 | 🌐 Go | 📅 2026-08-10 :  通用唯一标识符`（UUID）`的实现。支持`UUID`的创建和解析。
* [wuid](https://github.com/edwingeng/wuid) ⭐ 544 | 🐛 3 | 🌐 Go | 📅 2024-01-26 :  极快的唯一数字生成器,比`UUID`快10-135倍。
* [sno](https://github.com/muyo/sno) ⭐ 94 | 🐛 1 | 🌐 Go | 📅 2021-11-12 :  内嵌元数据的紧凑、可排序和快速的唯一`ID`。
* [nanoid](https://github.com/aidarkhanov/nanoid) ⭐ 62 | 🐛 0 | 🌐 Go | 📅 2022-09-21 :  微型而高效的`Go`唯一字符串ID生成器。
* [goid](https://github.com/jakehl/goid) ⭐ 41 | 🐛 1 | 🌐 Go | 📅 2019-02-18 :  生成并解析符合` RFC4122`标准的` V4 UUID`。
* [gouid](https://github.com/twharmon/gouid) ⭐ 27 | 🐛 0 | 🌐 Go | 📅 2026-02-06 :  只需一次分配就能生成加密安全的随机字符串`ID`。
* [uuid](https://github.com/agext/uuid) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2020-03-12 :  用快速或加密质量的随机节点标识符生成、编码和解码`UUIDs v1`。
* [uniq](https://gitlab.com/skilstak/code/go/uniq) :  使用命令快速、安全的唯一标识符。

***

## 校验库

`用于校验的库`

* [validator](https://github.com/go-playground/validator) ⭐ 20,111 | 🐛 321 | 🌐 Go | 📅 2026-07-29 :  `Go`结构体及域验证,包括：跨域、跨结构体,`Map`, 切片和数组
* [govalidator](https://github.com/asaskevich/govalidator) ⭐ 6,204 | 🐛 166 | 🌐 Go | 📅 2026-07-29 :  数据验证及清晰工具,用于字符串,数字, 数组切片及结构体
* [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) ⭐ 4,125 | 🐛 31 | 🌐 Go | 📅 2026-08-11 :   支持多种数据类型的验证 (结构体,字符串,键值对,数组切片等等),具有可配置、可扩展的验证规则,且使用常用代码结构定义,而非结构体标签
* [govalidator](https://github.com/thedevsaddam/govalidator) ⭐ 1,342 | 🐛 42 | 🌐 Go | 📅 2024-05-12 :  用简单的规则验证`Golang`请求数据. 高度受`Laravel`的请求验证的启发.
* [validate](https://github.com/gookit/validate) ⭐ 1,163 | 🐛 4 | 🌐 Go | 📅 2026-08-08 :  用于数据验证和过滤的`Go`包,支持验证`Map、Struct、Request(Form、JSON、url.Values、Uploaded Files`)数据和更多的功能。
* [gody](https://github.com/guiferpa/gody) ⭐ 181 | 🐛 0 | 🌐 Go | 📅 2025-05-30 :  针对 'Go\` 的轻量级结构体验证器。
* [jio](https://github.com/faceair/jio) ⭐ 126 | 🐛 3 | 🌐 Go | 📅 2024-07-04 : `jio`是一个类似于[joi](https://github.com/hapijs/joi) ⭐ 21,179 | 🐛 203 | 🌐 JavaScript | 📅 2026-06-17 的json模式验证器.
* [govalid](https://github.com/twharmon/govalid) ⭐ 118 | 🐛 0 | 🌐 Go | 📅 2026-06-05 :  基于标签的快速结构体验证。
* [checkdigit](https://github.com/osamingo/checkdigit) ⭐ 114 | 🐛 2 | 🌐 Go | 📅 2025-03-28 :  提供数字算法（`Luhn, Verhoeff, Damm`）和数字计算（`ISBN, EAN, JAN, UPC`等）功能的库。
* [validate](https://github.com/gobuffalo/validate) ⭐ 94 | 🐛 0 | 🌐 Go | 📅 2022-09-26 :  为`Go`语言程序编写验证工具的框架
* [terraform-validator](https://github.com/thazelart/terraform-validator) ⚠️ Archived : `Terraform`的规范和约定验证器。

***

### 版本控制

`版本控制相关库`

* [go-git](https://github.com/src-d/go-git) ⚠️ Archived :  纯`Go`中实现高度可扩展的`Git`。
* [hercules](https://github.com/src-d/hercules) ⭐ 2,804 | 🐛 51 | 🌐 Go | 📅 2023-02-07 :  查看`git repo`历史的代码库
* [git2go](https://github.com/libgit2/git2go) ⭐ 2,006 | 🐛 84 | 🌐 Go | 📅 2024-03-04 :  `libgit2`的` Go`语言接口
* [go-vcs](https://github.com/sourcegraph/go-vcs) ⭐ 81 | 🐛 22 | 🌐 Go | 📅 2026-07-03 :  通过`Go`语言来操作和检视` VCS`代码仓
* [gh](https://github.com/rjeczalik/gh) ⭐ 80 | 🐛 2 | 🌐 Go | 📅 2018-10-28 :  用于` GitHub Webhooks`的可编程服务器以及`net/HTTP` 中间件
* [hgo](https://github.com/beyang/hgo) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2015-08-25 : `HGo` 是一个`Go`语言软件包集合,提供了对本地` Mercurial`仓库的读取能力.

***

## 视频

`视频和流媒体相关库`

* [goav](https://github.com/giorgisio/goav) ⭐ 2,135 | 🐛 48 | 🌐 Go | 📅 2022-05-19 :  易用的` FFmpeg`Go 语言接口
* [m3u8](https://github.com/grafov/m3u8) ⚠️ Archived :  用于苹果`HLS`的`M3U8`播放列表解析器和生成器库
* [gmf](https://github.com/3d0c/gmf) ⭐ 933 | 🐛 49 | 🌐 Go | 📅 2022-09-06 : `FFmpeg av*`库的 Go 语言接口.
* [go-astisub](https://github.com/asticode/go-astisub) ⭐ 702 | 🐛 11 | 🌐 Go | 📅 2026-07-08 :  使用 Go 语言操作字幕`(.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).`
* [go-astits](https://github.com/asticode/go-astits) ⭐ 615 | 🐛 8 | 🌐 Go | 📅 2026-08-15 :  在 GO 中解析和解调` MPEG` 传输流（.ts）。
* [libvlc-go](https://github.com/adrg/libvlc-go) ⭐ 509 | 🐛 13 | 🌐 Go | 📅 2026-07-16 : `libvlc 2.X/3.X/4.X`的go语言封装)(`VLC` 媒体播放器使用）。
* [gst](https://github.com/ziutek/gst) ⭐ 175 | 🐛 9 | 🌐 Go | 📅 2021-01-07 : `GStreamer`的 Go 语言接口
* [go-m3u8](https://github.com/quangngotan95/go-m3u8) ⭐ 120 | 🐛 2 | 🌐 Go | 📅 2022-12-24 :  苹果`m3u8`播放列表的解析器和生成库。
* [v4l](https://github.com/korandiz/v4l) ⭐ 89 | 🐛 2 | 🌐 Go | 📅 2024-03-22 :` Go`语言编写的`Linux`下使用的视频截图库
* [go-mpd](https://github.com/unki2aut/go-mpd) ⭐ 32 | 🐛 0 | 🌐 Go | 📅 2025-06-10 : `MPEG-DASH`清单文件的解析器和生成器库。
* [libgosubs](https://github.com/wargarblgarbl/libgosubs) ⭐ 26 | 🐛 1 | 🌐 Go | 📅 2020-05-13 :  ` Go`的字幕格式处理库。支持`.srt、.ttml`和.ass\`。

***

## web框架

`web 框架`

* [Gin](https://github.com/gin-gonic/gin) ⭐ 89,078 | 🐛 758 | 🌐 Go | 📅 2026-08-15 :  ` Gin` 是一个` Go` 语言编写的 web 框架,提供了一组类似`martini`的`API`,且具有更好的性能（40倍的性能提升）。如果你需要高性能和高生产率,这个框架很适合你
* [Fiber](https://github.com/gofiber/fiber) ⭐ 40,069 | 🐛 52 | 🌐 Go | 📅 2026-08-16 :  受` Express.js`启发的` Web` 框架,构建在`Fasthttp`上。
* [Echo](https://github.com/labstack/echo) ⭐ 32,631 | 🐛 25 | 🌐 Go | 📅 2026-08-04 :   高性能、极简的` Go`语言`web` 框架
* [Revel](https://github.com/revel/revel) ⭐ 13,217 | 🐛 94 | 🌐 Go | 📅 2023-10-28 :` go`语言高生产率框架
* [Gizmo](https://github.com/NYTimes/gizmo) ⭐ 3,772 | 🐛 32 | 🌐 Go | 📅 2026-03-18 :  纽约时报正在使用对微服务工具集
* [Macaron](https://github.com/go-macaron/macaron) ⭐ 3,546 | 🐛 12 | 🌐 Go | 📅 2026-02-16 : `Macaron`是一个高效的模块化设计的`web`框架
* [go-json-rest](https://github.com/ant0ine/go-json-rest) ⭐ 3,486 | 🐛 45 | 🌐 Go | 📅 2021-01-23 :   快速、简单的创建`RESTful JSON API.`
* [utron](https://github.com/gernest/utron) ⚠️ Archived :  轻量级的`go`语言` MVC` 框架
* [Goyave](https://github.com/System-Glitch/goyave) ⭐ 1,772 | 🐛 13 | 🌐 Go | 📅 2026-06-03 :  功能完整的`Web`框架,旨在实现简洁的代码和快速开发,具有强大的内置功能。
* [tigertonic](https://github.com/rcrowley/go-tigertonic) ⭐ 985 | 🐛 27 | 🌐 Go | 📅 2018-07-24 :  受到 Dropwizard 启发,用于构建`JSON web`服务的` Go`语言框架,
* [tango](https://github.com/lunny/tango) ⚠️ Archived :  微型的、支持插件的`web`框架
* [Gearbox](https://github.com/abahmed/gearbox) ⭐ 802 | 🐛 1 | 🌐 Go | 📅 2026-01-06 :  用Go编写的网络框架,专注于高性能和内存优化。
* [Beego](https://github.com/astaxie/beego) ⭐ 742 | 🐛 0 | 📅 2022-04-27 :   beeGo 是一个开源的、高性能的 Go 语言`web`框架
* [Flamingo Commerce](https://github.com/i-love-flamingo/flamingo-commerce) ⭐ 591 | 🐛 28 | 🌐 Go | 📅 2026-08-13 :   提供电子商务功能,使用简洁的架构,如`DDD`、端口和适配器,你可以用它来构建灵活的电子商务应用。
* [Aero](https://github.com/aerogo/aero) ⚠️ Archived : `Go`的高性能Web框架,在`Lighthouse` 评比中拿到最高分
* [Flamingo](https://github.com/i-love-flamingo/flamingo) ⭐ 559 | 🐛 33 | 🌐 Go | 📅 2026-08-16 :  可插拔的`we`b项目框架。包括模块的概念,并提供`DI、Configareas、i18n`、模板引擎、graphql、可观察性、安全性、事件、路由和反向路由等功能。
* [gongular](https://github.com/mustafaakin/gongular) ⭐ 501 | 🐛 7 | 🌐 Go | 📅 2020-07-05 :  快速` Go web` 框架,支持输入映射／验证以及依赖注入
* [Air](https://github.com/aofei/air) ⚠️ Archived :  理想的`RESTful web` 框架
* [neo](https://github.com/ivpusic/neo) ⭐ 415 | 🐛 6 | 🌐 Go | 📅 2022-11-19 :  极小且快速的 Go 语言` web` 框架,具有及其简单的`API`
* [mango](https://github.com/paulbellamy/mango) ⭐ 373 | 🐛 9 | 🌐 Go | 📅 2017-10-17 :  ManGo 是一个模块化`web`应用框架,受到`Rack`和` PEP33`3 的启发
* [uAdmin](https://github.com/uadmin/uadmin) ⭐ 355 | 🐛 23 | 🌐 Go | 📅 2026-07-13 :   受`Django`启发的Golang`web`框架,。
* [Gondola](https://github.com/rainycape/gondola) ⭐ 313 | 🐛 9 | 🌐 Go | 📅 2019-02-19 :  用于快速编写高性能网站的框架
* [WebGo](https://github.com/bnkamalesh/webgo) ⭐ 307 | 🐛 2 | 🌐 Go | 📅 2025-09-23 :  构建`Web`应用的微服务框架；具有处理程序链、中间件和上下文注入功能。具有标准库兼容的`HTTP`处理程序（即`http.HandlerFunc`）。
* [Ginrpc](https://github.com/xxjwxc/ginrpc) ⭐ 303 | 🐛 13 | 🌐 Go | 📅 2025-11-20 :` Gin`参数自动绑定工具,`Gin rpc`工具。
* [Golf](https://github.com/dinever/golf) ⭐ 268 | 🐛 6 | 🌐 Go | 📅 2021-08-27 :   快速、简单、轻量级的`Go` 语言微型` web`框架。具有强大的功能且没有标准库以外的依赖
* [hiboot](https://github.com/hidevopsio/hiboot) ⭐ 179 | 🐛 2 | 🌐 Go | 📅 2026-06-08 : `hiboot`是一个高性能的web应用框架,支持自动配置和依赖注入。
* [appy](https://github.com/appist/appy) ⭐ 132 | 🐛 5 | 🌐 Go | 📅 2024-03-07 :  高效Web框架,帮助企业更容易扩展业务。
* [go-rest](https://github.com/ungerik/go-rest) ⭐ 128 | 🐛 2 | 🌐 Go | 📅 2017-01-20 : `Go` 语言`REST` 框架
* [patron](https://github.com/beatlabs/patron) ⭐ 127 | 🐛 15 | 🌐 Go | 📅 2026-08-01 : `Patron`是一个遵循最佳云实践的微服务框架,专注于生产力。
* [Microservice](https://github.com/claygod/microservice) ⭐ 123 | 🐛 0 | 🌐 Go | 📅 2026-08-05 : 用于创建微服务的框架,使用` Go`语言编写
* [rux](https://github.com/gookit/rux) ⭐ 99 | 🐛 1 | 🌐 Go | 📅 2026-08-13 :  用于构建`golang HTTP`应用程序的简单、快速的`web`框架。
* [vox](https://github.com/aisk/vox) ⭐ 89 | 🐛 8 | 🌐 Go | 📅 2026-07-03 : `Golang`网络框架,灵感来自`Koa`。
* [Golax](https://github.com/fulldump/golax) ⭐ 74 | 🐛 6 | 🌐 Go | 📅 2023-01-11 :  一个非`Sinatra`的快速HTTP框架,支持`Google`自定义方法、深度拦截器、递归等。
* [YARF](https://github.com/yarf-framework/yarf) ⭐ 69 | 🐛 2 | 🌐 Go | 📅 2019-03-07 : 微服务框架,用于快速、简单地构建`REST APIs`以及` web` 服务
* [Fireball](https://github.com/zpatrick/fireball) ⭐ 60 | 🐛 1 | 🌐 Go | 📅 2018-10-03 :  更加自然的` web`框架
* [goa](https://github.com/goa-go/goa) ⭐ 49 | 🐛 0 | 🌐 Go | 📅 2019-12-06 :   用于开发微服务的框架,基于`Ruby`的`Praxis` 的设计
* [Resoursea](https://github.com/resoursea/api) ⭐ 34 | 🐛 0 | 🌐 Go | 📅 2015-02-01 :  用于快速编写基于资源的服务的REST框架。
* [rex](https://github.com/goanywhere/rex) ⭐ 32 | 🐛 0 | 🌐 Go | 📅 2017-12-22 :` Rex` 是一个用于进行模块化开发的库,基于`Gorilla/mux` 完全兼容大多数的`net/HTTP`
* [Banjo](https://github.com/nsheremet/banjo) ⭐ 24 | 🐛 4 | 🌐 Go | 📅 2018-01-31 : 简单、快速的`Go web`框架。
* [aah](https://aahframework.org) :  可扩展、高性能、快速发布的` Go`语言`web`框架
* [Buffalo](http://gobuffalo.io) :  为`Go` 语言带来堪比` Rails` 的高生产效率
* [goweb](https://github.com/twharmon/goweb) :  具有路由、`websockets`、日志、中间件、静态文件服务器（可选`gzip`）和自动TLS的Web框架
* [REST Layer](http://rest-layer.io) :  在数据库之上构建`REST/GraphQL API`的框架,主要是通过配置而不是代码来进行开发

***

## 中间件

### 中间件

* [CORS](https://github.com/rs/cors) ⭐ 2,895 | 🐛 20 | 🌐 Go | 📅 2026-06-04 :  非常方便地向你的`api`中添加` CORS`功能
* [Tollbooth](https://github.com/didip/tollbooth) ⭐ 2,857 | 🐛 10 | 🌐 Go | 📅 2025-01-12 : `HTTP` 请求限速中间件
* [Limiter](https://github.com/ulule/limiter) ⭐ 2,342 | 🐛 18 | 🌐 Go | 📅 2024-12-10 :  超级简单的限速中间件
* [go-server-timing](https://github.com/mitchellh/go-server-timing) ⚠️ Archived : 向头信息中 添加/解析服务器计时信息。
* [go-fault](https://github.com/github/go-fault) ⭐ 555 | 🐛 1 | 🌐 Go | 📅 2026-07-27 : `Go`的错误注入中间件。
* [ln-paywall](https://github.com/philippgille/ln-paywall) ⭐ 158 | 🐛 18 | 🌐 Go | 📅 2019-02-24 :   Go 中间件,用于通过`Lightning Network (Bitcoin)` 请求将`API` 货币化。
* [XFF](https://github.com/sebest/xff) ⭐ 100 | 🐛 6 | 🌐 Go | 📅 2022-01-18 :  理`X-Forwarded-For`头的中间件
* [formjson](https://github.com/rs/formjson) ⭐ 38 | 🐛 0 | 🌐 Go | 📅 2015-12-17 :  以标准的表单`POST`方式处理`JSON`输入。
* [client-timing](https://github.com/posener/client-timing) ⭐ 25 | 🐛 1 | 🌐 Go | 📅 2020-03-13 :  在消息头部添加服务器定时信息的HTTP客户端。

***

### 创建http中间件的代码库

* [negroni](https://github.com/urfave/negroni) ⭐ 7,525 | 🐛 6 | 🌐 Go | 📅 2026-07-26 :  符合语言习惯的`HTTP`中间件库
* [alice](https://github.com/justinas/alice) ⭐ 3,362 | 🐛 11 | 🌐 Go | 📅 2024-06-06 :  创建链式中间件的库
* [render](https://github.com/unrolled/render) ⭐ 1,997 | 🐛 1 | 🌐 Go | 📅 2026-05-01 :  用于轻松渲染`JSON, XML`, 及`HTML` 模板响应的库
* [stats](https://github.com/thoas/stats) ⭐ 593 | 🐛 8 | 🌐 Go | 📅 2022-12-12 : `Go`语言中间件,用于存储`web`应用的多种信息
* [interpose](https://github.com/carbocation/interpose) ⭐ 291 | 🐛 1 | 🌐 Go | 📅 2016-12-06 :  极简的`net/HTTP` 中间件
* [renderer](https://github.com/thedevsaddam/renderer) ⭐ 260 | 🐛 0 | 🌐 Go | 📅 2026-04-22 :  简单、轻量级和更快的响应`JSON、JSONP、XML、YAML、HTML、File`的Go渲染包。
* [muxchain](https://github.com/stephens2424/muxchain) ⭐ 205 | 🐛 1 | 🌐 Go | 📅 2019-03-19 :  用于`net/HTTP`的轻量级中间件
* [gores](https://github.com/alioygur/gores) ⭐ 106 | 🐛 0 | 🌐 Go | 📅 2021-01-01 :   用于处理`HTML, JSON, XML` 等。对于`RESTful APIs` 很有用。
* [rye](https://github.com/InVisionApp/rye) ⚠️ Archived :  小型 Go 语言中间件库 ,支持`JWT, CORS, Statsd`, 及`Go 1.7 context`
* [mediary](https://github.com/HereMobilityDevelopers/mediary) ⭐ 88 | 🐛 0 | 🌐 Go | 📅 2020-06-24 :  为` http.Client` 添加拦截器,允许转储/重构/跟踪/...请求/响应。
* [chain](https://github.com/codemodus/chain) ⭐ 61 | 🐛 0 | 🌐 Go | 📅 2018-08-25 :   可以带数据的`Handler` 链式封装器(`net/context-based "middleware"`).
* [catena](https://github.com/codemodus/catena) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2018-08-25 : `HTTP.Handler`封装器 (和`chain`具有相同的` API` ).
* [go-wrap](https://github.com/go-on/wrap) :  小型中间件库,用于`net/HTTP.`

***

## 路由

* [chi](https://github.com/go-chi/chi) ⭐ 22,675 | 🐛 109 | 🌐 Go | 📅 2026-08-15 :   基于`net/context`的小巧、快速、具有丰富表达力的`HTTP`路由.
* [mux](https://github.com/gorilla/mux) ⭐ 21,836 | 🐛 38 | 🌐 Go | 📅 2024-08-15 :  强大的`URL`路由和分发库
* [httprouter](https://github.com/julienschmidt/httprouter) ⭐ 17,130 | 🐛 84 | 🌐 Go | 📅 2024-07-22 :  高性能路由,使用这个库和标准http处理工具可以构建一个非常高性能大web框架
* [gocraft/web](https://github.com/gocraft/web) ⭐ 1,523 | 🐛 24 | 🌐 Go | 📅 2020-10-01 :  `Mux`及中间件包
* [Bone](https://github.com/go-zoo/bone) ⭐ 1,282 | 🐛 3 | 🌐 Go | 📅 2019-05-06 :  轻量、快速的`HTTP` 多路复用器
* [Goji](https://github.com/goji/goji) ⭐ 974 | 🐛 6 | 🌐 Go | 📅 2022-07-26 :` Goji`是一个极简的、灵活的`HTTP` 请求数据分选器,支持`net/context.`
* [fasthttprouter](https://github.com/buaazp/fasthttprouter) ⭐ 869 | 🐛 19 | 🌐 Go | 📅 2019-04-25 :  从`httprouter`分叉出来的高性能路由器,也是第一个适合`fasthttp`的路由器。
* [httptreemux](https://github.com/dimfeld/httptreemux) ⭐ 618 | 🐛 8 | 🌐 Go | 📅 2024-07-10 :  快速,灵活,树状结构的` HTTP`路由。受到了` httprouter` 的启发
* [xujiajun/gorouter](https://github.com/xujiajun/gorouter) ⭐ 523 | 🐛 0 | 🌐 Go | 📅 2019-09-27 :   简单快速的`go HTTP`路由器。
* [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) ⭐ 451 | 🐛 9 | 🌐 Go | 📅 2022-05-08 :  极快的` Go (golang)  HTTP`路由器,支持正则表达式路由匹配。完全支持构建`RESTful API`。
* [lars](https://github.com/go-playground/lars) ⭐ 385 | 🐛 1 | 🌐 Go | 📅 2019-05-15 :   轻量级、快速、可扩展、零分配的`HTTP`路由,用于创建定制化的框架
* [Siesta](https://github.com/VividCortex/siesta) ⭐ 347 | 🐛 0 | 🌐 Go | 📅 2023-12-12 :   具有可组合性的框架,用于编写中间件和`handlers`
* [vestigo](https://github.com/husobee/vestigo) ⭐ 265 | 🐛 13 | 🌐 Go | 📅 2020-10-08 : 用于构建`go`语言`web`应用 ,高性能、符合` HTTP` 标准的`URL` 路由,
* [gowww/router](https://github.com/gowww/router) ⭐ 185 | 🐛 0 | 🌐 Go | 📅 2026-01-27 :  超快的HTTP 路由,完全兼容`net/HTTP.Handler`接口.
* [GoRouter](https://github.com/vardius/gorouter) ⭐ 153 | 🐛 9 | 🌐 Go | 📅 2024-09-05 : `server/API`微服务框架,具有`HTTP` 请求路由模块` router`模块, 多路复用模块并且提供了支持`net/context`的中间件 :
* [pure](https://github.com/go-playground/pure) ⭐ 152 | 🐛 0 | 🌐 Go | 📅 2023-07-13 :   是一个轻量级http路由,严格参照`net/HTTP`标准实现
* [alien](https://github.com/gernest/alien) ⭐ 134 | 🐛 3 | 🌐 Go | 📅 2024-03-24 :  轻量级、超快速的`HTTP` 路由,
* [violetear](https://github.com/nbari/violetear) ⚠️ Archived : `Go http`路由库
* [Bxog](https://github.com/claygod/Bxog) ⭐ 104 | 🐛 0 | 🌐 Go | 📅 2026-06-26 :  为`go`语言编写的简单、快速的`HTTP`路由。它能够根据接收到的参数创建` URL`,并且能够解析多种不同复杂度、长度和嵌套的路由。
* [xmux](https://github.com/rs/xmux) ⭐ 100 | 🐛 2 | 🌐 Go | 📅 2017-06-09 :  高性能 muxer,基于` httprouter` ,支持` net/context`
* [bellt](https://github.com/GuilhermeCaruso/bellt) ⭐ 55 | 🐛 0 | 🌐 Go | 📅 2022-07-18 :  一个简单的`Go HTTP`路由器。
* [FastRouter](https://github.com/razonyang/fastrouter) ⭐ 25 | 🐛 0 | 🌐 Go | 📅 2017-11-03 :   从`httprouter`fork出来的高性能路由,是第一个适配`fasthttp`的路由
* [goroute](https://github.com/goroute/route) ⭐ 9 | 🐛 1 | 🌐 Go | 📅 2019-12-23 :  简单而强大的`HTTP` 请求复用器。

***

## WebAssembly

* [tinygo](https://github.com/tinygo-org/tinygo) ⭐ 17,651 | 🐛 566 | 🌐 Go | 📅 2026-08-16 :  基于`LLVM`,适用于微型场景的`Go`编译器。包括微控制器、`WebAssembly`和命令行工具。
* [dom](https://github.com/dennwc/dom) ⭐ 507 | 🐛 10 | 🌐 Go | 📅 2019-09-26 : `DOM库`。
* [go-canvas](https://github.com/markfarnan/go-canvas) ⭐ 271 | 🐛 4 | 🌐 Go | 📅 2020-12-09 :   使用`HTML5 Canvas` 的库,所有的绘图逻辑都在`go`代码中执行。
* [wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) ⭐ 211 | 🐛 6 | 🌐 Go | 📅 2026-06-09 : 在浏览器中运行`Go WASM`测试。
* [webapi](https://github.com/gowebapi/webapi) ⭐ 181 | 🐛 3 | 🌐 Go | 📅 2022-12-21 :  从`WebIDL`生成`DOM`和`HTML`的封装。
* [vert](https://github.com/norunners/vert) ⭐ 108 | 🐛 2 | 🌐 Go | 📅 2022-12-03 : `Go`和`JS`值之间的互操作。

***

## Windows

* [go-ole](https://github.com/go-ole/go-ole) ⭐ 1,319 | 🐛 1 | 🌐 Go | 📅 2026-03-30 :  为`Go`语言实现的`Win32 OLE`
* [d3d9](https://github.com/gonutz/d3d9) ⭐ 164 | 🐛 0 | 🌐 Go | 📅 2025-06-28 : `Direct3D9` 的`Go` 语言封装
* [gosddl](https://github.com/MonaxGT/gosddl) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2019-04-30 :  从`SDDL-string`到用户友好的JSON的转换器。`SDDL`由四个部分组成。`Owner、Primary Group、DACL、SACL`。

***

## XML

* [zek](https://github.com/miku/zek) ⭐ 820 | 🐛 9 | 🌐 Go | 📅 2026-04-23 : 从` XML` 生成一个` Go`结构体。
* [xpath](https://github.com/antchfx/xpath) ⭐ 742 | 🐛 19 | 🌐 Go | 📅 2026-07-23 : `XPath` 库
* [xquery](https://github.com/antchfx/xquery) ⚠️ Archived :`  XQuery` 使你可以使用`XPath`表达式从` HTML/XML`文档中抽取数据和求值,
* [xml2map](https://github.com/sbabiv/xml2map) ⭐ 65 | 🐛 3 | 🌐 Go | 📅 2021-12-07 : `Golang`编写的`XML`到`MAP`的转换器。
* [xmlwriter](https://github.com/shabbyrobe/xmlwriter) ⚠️ Archived :   基于` libxml2` 的`xmlwriter` 模块的`xml`生成器api.
* [XML-Comp](https://github.com/xml-comp/xml-comp) ⭐ 21 | 🐛 8 | 🌐 Go | 📅 2018-07-19 :   命令行` XML`比较工具,可以生成关于目录、文件和标签对差异信息

***

## 相关工具

`go相关工具和插件`

### 代码分析

* [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) ⭐ 6,850 | 🐛 575 | 🌐 Go | 📅 2026-06-30 : 针对 Go 语言的`lint`工具,专注于简化代码
* [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) ⭐ 6,850 | 🐛 575 | 🌐 Go | 📅 2026-06-30 :  -`staticcheck`在`Go vet`阶段中执行大量的静态分析检查,类似`ReSharper for C#`这样的工具。
* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) ⭐ 6,850 | 🐛 575 | 🌐 Go | 📅 2026-06-30 :  `unused`会检查 Go 语言代码中没有用到的常量,变量,函数和类型
* [GoLint](https://github.com/golang/lint) ⚠️ Archived :  针对 Go 语言源码的` lint` 工具
* [errcheck](https://github.com/kisielk/errcheck) ⭐ 2,526 | 🐛 14 | 🌐 Go | 📅 2026-05-12 : `Errcheck`是一个用于检测go语言程序中存在未处理错误的程序
* [GoPlantUML](https://github.com/jfeliu007/goplantuml) ⭐ 2,089 | 🐛 39 | 🌐 Go | 📅 2025-10-16 :  生成文本`plantUML`图的库和`CLI`,包含结构和接口的信息以及它们之间的关系。
* [go-critic](https://github.com/go-critic/go-critic) ⭐ 2,065 | 🐛 152 | 🌐 Go | 📅 2026-06-26 :  源代码检查器,它带来了目前其他检查器没有实现的检查。
* [golines](https://github.com/segmentio/golines) ⚠️ Archived : 自动缩短` Go` 代码中长行的格式化器。
* [gcvis](https://github.com/davecheney/gcvis) ⚠️ Archived :   实时地将`Go` 语言垃圾回收进行可视化
* [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) ⭐ 984 | 🐛 5 | 🌐 Go | 📅 2021-11-08 :` Go-cleanarch`用于检查代码是否符合简洁架构的相关法则,比如依赖法则以及你的Go语言项目中各个库的交互情况
* [php-parser](https://github.com/z7zmey/php-parser) ⭐ 957 | 🐛 18 | 🌐 Go | 📅 2021-04-28 : `Go`编写的`PHP`解析器。
* [goast-viewer](https://github.com/yuroyoro/goast-viewer) ⭐ 793 | 🐛 2 | 🌐 JavaScript | 📅 2023-11-30 :   基于`Web`的` Golang AST` 可视化工具.
* [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) ⭐ 670 | 🐛 6 | 🌐 Go | 📅 2023-02-19 :  一种查找` Go`项目中过时的依赖关系的简单方法。
* [unconvert](https://github.com/mdempsky/unconvert) ⭐ 387 | 🐛 9 | 🌐 Go | 📅 2026-08-16 :   从go语言代码中移除不必要的类型转换
* [dupl](https://github.com/mibk/dupl) ⭐ 368 | 🐛 6 | 🌐 Go | 📅 2026-03-05 :  用于检测重复代码的工具
* [tickgit](https://github.com/augmentable-dev/tickgit) ⭐ 324 | 🐛 14 | 🌐 Go | 📅 2023-12-18 :  用于显示代码注释`TODO`（任何语言）的CLI和go包,并应用`git blam`来识别作者
* [gostatus](https://github.com/shurcooL/gostatus) ⭐ 245 | 🐛 1 | 🌐 Go | 📅 2025-05-18 :   命令行工具,查看当前` Go` 语言软件包仓库的状态
* [apicompat](https://github.com/bradleyfalzon/apicompat) ⭐ 182 | 🐛 7 | 🌐 Go | 📅 2017-02-05 :  检测`go`语言项目最近的变化,用于监测不能向后兼容的代码修改
* [go-checkstyle](https://github.com/qiniu/checkstyle) ⭐ 130 | 🐛 5 | 🌐 Go | 📅 2021-03-10 : `checkstyle`是一个类似`java checkstyle`的 代码风格检查工具,这个工具受到`java checkstyle`和` Golint` 的启发
* [lint](https://github.com/surullabs/lint) ⭐ 66 | 🐛 2 | 🌐 Go | 📅 2018-10-28 :   运行`linters`作为Go测试的一部分。
* [validate](https://github.com/mccoyst/validate) ⭐ 62 | 🐛 1 | 🌐 Go | 📅 2023-08-18 :  根据结构体`tag`自动验证结构体字段
* [go-outdated](https://github.com/firstrow/go-outdated) ⚠️ Archived :  用于显示过时的库的命令行工具
* [tarp](https://github.com/verygoodsoftwarenotvirus/tarp) ⚠️ Archived :`  tarp`可以在` Go`源代码中找到无需直接单元测试的函数和方法
* [GoCover.io](http://gocover.io/`) :` GoCover.io`可以查看任何go语言软件包的代码覆盖率
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) :  用于自动修复,添加,删除你的 Go 语言项目的 import
* [Golint online](http://go-lint.appspot.com/) :  使用`golint`对`GitHub, Bitbucket` 以及` Google Project Hosting`上面的`Go`语言源文件进行静态分析
* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) :   添加零值`return` 语句以符合函数返回值类型

***

## 编辑器插件

* [vim-go](https://github.com/fatih/vim-go) ⭐ 16,220 | 🐛 46 | 🌐 Vim Script | 📅 2026-07-24 : `Vim`使用的`Go` 语言开发插件
* [gocode](https://github.com/nsf/gocode) ⭐ 4,991 | 🐛 66 | 🌐 Go | 📅 2026-02-07 : `go`语言自动补全
* [vscode-go](https://github.com/golang/vscode-go) ⭐ 4,260 | 🐛 447 | 🌐 TypeScript | 📅 2026-08-14 : `Visual Studio Code (VS Code)` : 使用的一个扩展,为` Go` 语言提供了支持
* [GoSublime](https://github.com/DisposaBoy/GoSublime) ⭐ 3,402 | 🐛 82 | 🌐 Go | 📅 2020-07-21 : SublimeText 2 使用的 Go 语言插件,支持代码补全以及一些类似` IDE` 的特性
* [go-plus](https://github.com/joefitzgerald/go-plus) ⚠️ Archived :  供`Atom` 使用的自动补全、格式化、语法检查、`lint`及`Vetting` 的软件包
* [go-mode](https://github.com/dominikh/go-mode.el) ⭐ 1,455 | 🐛 50 | 🌐 Emacs Lisp | 📅 2026-05-29 : ` GNU/Emacs`的`Go`语言模式
* [goimports-reviser](https://github.com/incu6us/goimports-reviser) ⭐ 716 | 🐛 11 | 🌐 Go | 📅 2026-02-24 : 用于导入的格式化工具。
* [Watch](https://github.com/eaburns/Watch) ⭐ 201 | 🐛 8 | 🌐 Go | 📅 2023-03-18 :  当文件变动时,在` acme`窗口中执行命令
* [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) ⭐ 90 | 🐛 0 | 🌐 VimL | 📅 2016-06-28 :` Vim`插件,在保存时高亮语法错误
* [go-language-server](https://github.com/theia-ide/go-language-server) ⚠️ Archived :  用于将` VSCode go` 扩展变为支持语言服务器协议的GO代码封装库
* [gounit-vim](https://github.com/hexdigest/gounit-vim) ⭐ 25 | 🐛 0 | 🌐 Vim script | 📅 2018-10-29 :   `Vim`插件,用于根据函数或方法的签名生成`Go`测试。
* [theia-go-extension](https://github.com/theia-ide/theia-go-extension) ⚠️ Archived :  为`Theia IDE`提供`Go`语言支持。
* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) :`JetBrains IDEs` 使用的`Go`语言插件
* [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) :   这个扩展为` VS Code`增加了对` Go`语言的基准分析支持。

***

## Go 代码生成工具

* [gotests](https://github.com/cweill/gotests) ⭐ 5,327 | 🐛 39 | 🌐 Go | 📅 2025-10-30 :  根据源代码生成`Go`测试代码。
* [genny](https://github.com/cheekybits/genny) ⭐ 1,717 | 🐛 27 | 🌐 Go | 📅 2021-08-24 :  为` Go`提供优雅的泛型。
* [xgen](https://github.com/xuri/xgen) ⭐ 420 | 🐛 36 | 🌐 Go | 📅 2026-08-02 : ` XSD (XML Schema Definition)`  解析器,能够生成`Go/C/Java/Rust/Typescript`代码
* [hasgo](https://github.com/DylanMeeus/hasgo) ⭐ 144 | 🐛 16 | 🌐 Go | 📅 2021-04-29 :  为`slices`生成`Haskell`的启发函数。
* [gocontracts](https://github.com/Parquery/gocontracts) ⭐ 118 | 🐛 1 | 🌐 Go | 📅 2019-01-26 :   通过同步代码和文档,将按合约设计引入` Go`。
* [gonerics](http://github.com/bouk/gonerics) ⭐ 112 | 🐛 0 | 🌐 Go | 📅 2014-09-29 : `Go`泛型。
* [gounit](https://github.com/hexdigest/gounit) ⭐ 87 | 🐛 1 | 🌐 Go | 📅 2018-08-17 :  使用你自己的模板生成`Go` 测试代码。
* [generic](https://github.com/usk81/generic) ⭐ 49 | 🐛 2 | 🌐 Go | 📅 2021-01-13 : 针对`Go`的灵活数据类型。
* [re2dfa](https://github.com/opennota/re2dfa) :   将正则表达式转换为有限状态机并输出`Go`源代码。
* [TOML-to-Go](https://xuri.me/toml-to-go) :  在浏览器中将` TOML`转成` Go` 类型。

***

## Go 工具

* [go-swagger](https://github.com/go-swagger/go-swagger) ⭐ 9,989 | 🐛 303 | 🌐 Go | 📅 2026-08-15 :  为 Go 语言实现的`Swagger 2.0`.
* [go-callvis](https://github.com/TrueFurby/go-callvis) ⭐ 6,504 | 🐛 73 | 🌐 Go | 📅 2026-03-30 :   使用`dot`语言将你的 Go 语言程序函数调用关系可视化
* [OctoLinker](https://github.com/OctoLinker/browser-extension) ⭐ 5,384 | 🐛 62 | 🌐 HTML | 📅 2023-10-02 :  - 使用`github` 的浏览器插件` OctoLinker`高效浏览`Go` 语言文件
* [depth](https://github.com/KyleBanks/depth) ⭐ 1,083 | 🐛 10 | 🌐 Go | 📅 2022-02-08 :  通过分析导入的库,将某个包的依赖关系用树状结构进行显示
* [richgo](https://github.com/kyoh86/richgo) ⭐ 860 | 🐛 6 | 🌐 Go | 📅 2026-07-18 :  用文本装饰丰富`go`代码测试输出。
* [rts](https://github.com/galeone/rts) ⭐ 258 | 🐛 0 | 🌐 Go | 📅 2022-10-29 :  `RTS`（是`response to struct`的缩写）用于根据服务器的响应生成` Go`语言结构体
* [godbg](https://github.com/tylerwince/godbg) ⭐ 207 | 🐛 3 | 🌐 Go | 📅 2019-04-20 : `Rusts dbg！`宏的实现,用于在开发过程中进行快速和简单的调试。
* [typex](https://github.com/dtgorski/typex) ⭐ 204 | 🐛 2 | 🌐 Go | 📅 2023-09-15 :  检查Go类型和它们的转换依赖关系,或者将结果导出为`TypeScrip`t值对象（或类型）声明。
* [gothanks](https://github.com/psampaz/gothanks) ⭐ 127 | 🐛 1 | 🌐 Go | 📅 2023-02-18 :`  GoThanks` 会自动为你的`go.mod github`依赖项加星。
* [colorgo](https://github.com/songgao/colorgo) ⭐ 113 | 🐛 3 | 🌐 Go | 📅 2020-07-18 :  对 Go 命令进行了封装,用于为Go build的输出结果添加颜色
* [igo](https://github.com/rocketlaunchr/igo) ⭐ 73 | 🐛 0 | 🌐 Go | 📅 2020-04-06 :  `igo`到`go`的转换器（Go语言的新语言特性！）。
* [go-james](https://github.com/pieterclaerhout/go-james) ⚠️ Archived :  Go项目骨架创建服务,无需手动设置即可构建和测试你的项目。
* [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) ⭐ 45 | 🐛 0 | 🌐 C++ | 📅 2017-11-17 :` Bash`代码补全,用于`Go`和`wGo`.
* [gomodrun](https://github.com/dustinblackman/gomodrun/) ⭐ 38 | 🐛 1 | 🌐 Go | 📅 2024-05-17 :  用于执行和缓存包含在`go.mod`文件中的二进制文件的`Go`工具。
* [gb](https://getgb.io/) :  针对Go语言的项目的构建工具,
* [generator-go-lang](https://github.com/axelspringer/generator-go-lang) :  生成[Yeoman](http://yeoman.io) : 新项目的生成器 。
* [gilbert](https://go-gilbert.github.io) :  Go项目的构建系统和任务运行器。

***

## 软件包

`Go语言开发的软件工具`

### devops 工具

* [kubernetes](https://github.com/kubernetes/kubernetes) ⭐ 124,521 | 🐛 2,911 | 🌐 Go | 📅 2026-08-14 :  来自`Google`的容器集群管理器
* [Moby](https://github.com/moby/moby) ⭐ 71,980 | 🐛 3,886 | 🌐 Go | 📅 2026-08-16 :  为容器生态系统创建的一个合作项目,用于构建基于容器的系统
* [traefik](https://github.com/containous/traefik) ⭐ 64,455 | 🐛 900 | 🌐 Go | 📅 2026-08-13 :  能对接多个后端的反向代理和负载均衡器。
* [Gitea](https://github.com/go-gitea/gitea) ⭐ 57,416 | 🐛 2,548 | 🌐 Go | 📅 2026-08-16 :  社区驱动的`Gogs`的`fork`库
* [Vegeta](https://github.com/tsenart/vegeta) ⭐ 25,147 | 🐛 122 | 🌐 Go | 📅 2026-02-16 :  `HTTP 加`载测试工具和代码库
* [Hey](https://github.com/rakyll/hey) ⭐ 20,226 | 🐛 189 | 🌐 Go | 📅 2026-01-10 :` Hey`是一个微型程序,用于向`web` 应用发送负载
* [Packer](https://github.com/mitchellh/packer) ⭐ 15,759 | 🐛 314 | 🌐 Go | 📅 2026-08-16 :` Packer`通过单一的配置文件,为不同的平台创建独立镜像
* [webhook](https://github.com/adnanh/webhook) ⭐ 12,042 | 🐛 126 | 🌐 Go | 📅 2026-08-05 :  允许用户创建`HTTP`钩子,并在服务器上执行命令
* [GVM](https://github.com/moovweb/gvm) ⭐ 11,675 | 🐛 242 | 🌐 Shell | 📅 2024-08-08 : ` GVM`提供了用于管理`Go`语言版本的接口
* [script](https://github.com/bitfield/script) ⭐ 7,018 | 🐛 14 | 🌐 Go | 📅 2026-08-15 :  在Go中轻松编写类似`shell`的脚本,用于`DevOps`和系统管理任务。
* [bombardier](https://github.com/codesenberg/bombardier) ⭐ 6,824 | 🐛 27 | 🌐 Go | 📅 2026-03-31 :  快速的、跨平台的`HTTP`基准工具.
* [gaia](https://github.com/gaia-pipeline/gaia) ⚠️ Archived :   利用任何编程语言都可以构建强大的管道的库。
* [Pomerium](https://github.com/pomerium/pomerium) ⭐ 4,958 | 🐛 146 | 🌐 Go | 📅 2026-08-15 :  `Pomerium`是一个身份感知的访问代理。
* [gox](https://github.com/mitchellh/gox) ⚠️ Archived :  非常简单的`Go`语言交叉编译工具
* [s5cmd](https://github.com/peak/s5cmd) ⭐ 4,165 | 🐛 190 | 🌐 Go | 📅 2025-06-13 :  快速的` S3` 和本地文件系统执行工具。
* [bosun](https://github.com/bosun-monitor/bosun) ⚠️ Archived :  基于时间序列的告警框架
* [kala](https://github.com/ajvb/kala) ⭐ 2,155 | 🐛 15 | 🌐 Go | 📅 2025-12-05 :  极简、现代的、高效的任务调度
* [fac](https://github.com/mkchoi212/fac) ⭐ 1,856 | 🐛 9 | 🌐 Go | 📅 2023-12-29 :  用于修复git合并冲突的命令行用户界面。
* [go-selfupdate](https://github.com/sanbornm/go-selfupdate) ⭐ 1,698 | 🐛 17 | 🌐 Go | 📅 2024-08-17 :   让你的` Go` 语言程序可以自我更新
* [goxc](https://github.com/laher/goxc) ⚠️ Archived : ` Go` 语言构建工具,专注于交叉编译和打包
* [StatusOK](https://github.com/sanathp/statusok) ⭐ 1,644 | 🐛 35 | 🌐 Go | 📅 2021-08-11 :   监控你的网站和` REST APIs`。如果你的服务器挂了或是响应时间超过预期,则会通过`Slack`,`E-mail`来通知你
* [uTask](https://github.com/ovh/utask) ⭐ 1,394 | 🐛 85 | 🌐 Go | 📅 2026-07-29 :  自动化引擎,可对`yaml`中声明的业务流程进行建模和执行。
* [s3gof3r](https://github.com/rlmcpherson/s3gof3r) ⭐ 1,143 | 🐛 53 | 🌐 Go | 📅 2021-08-28 :  为了从`Amazon S3`中高速存取大型对象而特别优化的库
* [skm](https://github.com/TimothyYe/skm) ⭐ 1,077 | 🐛 1 | 🌐 Go | 📅 2026-08-02 :  SKM是一个简单而强大的`SSH`密钥管理器,它可以帮助您轻松管理您的多个`SSH`密钥。
* [Scaleway-cli](https://github.com/scaleway/scaleway-cli) ⭐ 991 | 🐛 264 | 🌐 Go | 📅 2026-08-14 :  通过命令行来管理 裸金属服务器 (和使用`Docker`一样容易)。
* [cassowary](https://github.com/rogerwelin/cassowary) ⭐ 812 | 🐛 7 | 🌐 Go | 📅 2025-09-11 :   用Go编写的现代跨平台`HTTP`负载测试工具。
* [aurora](https://github.com/xuri/aurora) ⭐ 599 | 🐛 7 | 🌐 JavaScript | 📅 2021-08-19 :   跨平台、基于web的` Beanstalkd`队列服务器控制台
* [govvv](https://github.com/ahmetalpbalkan/govvv) ⭐ 539 | 🐛 1 | 🌐 Go | 📅 2023-03-24 :   对`Go build`进行了封装,用于轻松的向 Go 语言二进制文件中添加版本信息
* [s3-proxy](https://github.com/oxyno-zeta/s3-proxy) ⭐ 483 | 🐛 19 | 🌐 Go | 📅 2026-08-13 : `S3`代理,具有`GET、PUT`和`DELETE`方法和认证（`OpenID Connect`和`Basic Auth`）。
* [Pewpew](https://github.com/bengadbois/pewpew) ⭐ 456 | 🐛 1 | 🌐 Go | 📅 2026-03-28 :  灵活的`HTTP`命令行压力测试工具
* [jcli](https://github.com/jenkins-zh/jenkins-cli) ⭐ 428 | 🐛 82 | 🌐 Go | 📅 2025-03-28 :  `Jenkins CLI`允许你以一种简单的方式管理你的`Jenkins`。
* [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) ⭐ 348 | 🐛 14 | 🌐 Go | 📅 2026-07-17 :   一个用于通过 ssh 远程执行命令以及可通过`ProxyCommand` 来进行 SCP 下载
* [gonative](https://github.com/inconshreveable/gonative) ⚠️ Archived : 为`Go` 语言创建可以在多平台进行交叉编译的工具,使用`CGo-enabled`标准库
* [lstags](https://github.com/ivanilves/lstags) ⭐ 339 | 🐛 10 | 🌐 Go | 📅 2023-05-11 :  在不同的注册表中同步`Docker`镜像的工具和`API`。
* [trubka](https://github.com/xitonix/trubka) ⭐ 337 | 🐛 5 | 🌐 Go | 📅 2025-04-18 : `CLI`工具,用于管理`Apache Kafka`集群并排除其故障,能够向`Kafka`发布/消费协议缓冲区和纯文本事件。
* [Mora](https://github.com/emicklei/mora) ⭐ 314 | 🐛 9 | 🌐 Go | 📅 2024-04-23 :  REST 服务器,用于获取`MonGoDB`文件和元数据
* [manssh](https://github.com/xwjdsh/manssh) ⭐ 310 | 🐛 2 | 🌐 Go | 📅 2022-02-11 : ` manssh`是一个命令行工具,用于轻松管理ssh别名配置。
* [terraform-provider-openapi](https://github.com/dikhan/terraform-provider-openapi) ⭐ 283 | 🐛 31 | 🌐 Go | 📅 2023-11-10 :` Terraform provider`插件,可以在运行时根据包含`API`定义的`OpenAPI`文档（以前称为`swagger`文件）动态配置自己。
* [dogo](https://github.com/liudng/dogo) ⭐ 274 | 🐛 5 | 🌐 Go | 📅 2019-03-15 :  监控源文件中的变化并自动编译和执行
* [godbg](https://github.com/sirnewton01/godbg) ⭐ 224 | 🐛 6 | 🌐 JavaScript | 📅 2018-07-09 :  基于`Web` 的前端` gdb` 应用程序
* [kcli](https://github.com/cswank/kcli) ⭐ 224 | 🐛 1 | 🌐 Go | 📅 2020-01-04 :  用于检查`kafka`主题/分区/消息的命令行工具。
* [Blast](https://github.com/dave/blast) ⭐ 220 | 🐛 1 | 🌐 Go | 📅 2018-03-01 : 一个简单的API负载测试和批量作业管理的工具。
* [gobrew](https://github.com/cryptojuice/gobrew) ⭐ 190 | 🐛 4 | 🌐 Shell | 📅 2020-05-21 : `Gobrew`让你可以在不同版本的` Go` 语言之间轻松切换
* [Dockerfile-Generator](https://github.com/ozankasikci/dockerfile-generator) ⭐ 185 | 🐛 0 | 🌐 Go | 📅 2022-05-23 :  包含`go`代码库和可执行文件,其可以利用各种输入管道信息生成有效的Dockerfiles。
* [ostent](https://github.com/ostrost/ostent) ⭐ 178 | 🐛 0 | 🌐 Go | 📅 2022-12-12 :  收集并显示系统数据,可以作` Graphite`和／或`InfluxDB` 的中间件
* [drone-scp](https://github.com/appleboy/drone-scp) ⭐ 174 | 🐛 24 | 🌐 Go | 📅 2026-08-15 :  通过` SSH` 拷贝文件及可执行程序,可以通过二进制文件、` docker` 或者`Drone CI`来使用
* [winrm-cli](https://github.com/masterzen/winrm-cli) ⭐ 174 | 🐛 1 | 🌐 Go | 📅 2021-12-30 :  命令行工具,可以远程在` windows`机器上执行命令
* [grapes](https://github.com/yaronsumel/grapes) ⭐ 170 | 🐛 3 | 🌐 Go | 📅 2026-01-13 :   一款轻量级工具,用于通过` ssh`发送命令
* [go-furnace](https://github.com/go-furnace/go-furnace) ⭐ 99 | 🐛 12 | 🌐 Go | 📅 2021-10-28 :  用Go编写的托管解决方案。在`AWS、GCP`或`DigitalOcean`上轻松部署你的应用程序。
* [Dropship](https://github.com/chrismckenzie/dropship) ⭐ 66 | 🐛 10 | 🌐 Go | 📅 2018-07-25 :  通过` cdn`部署代码的工具
* [drone-jenkins](https://github.com/appleboy/drone-jenkins) ⭐ 43 | 🐛 0 | 🌐 Go | 📅 2026-08-15 : 可以通过二进制文件、` docker`或者` Drone CI`来触发下游`Jenkins` 任务,
* [awsenv](https://github.com/soniah/awsenv) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2018-07-17 :  加载`Amazon (AWS)` 环境变量作为` profile`文件
* [lwc](https://github.com/timdp/lwc) ⭐ 33 | 🐛 0 | 🌐 Go | 📅 2022-07-26 : `UNIX wc`命令的实时更新版本。
* [Rodent](https://github.com/alouche/rodent) ⭐ 33 | 🐛 6 | 🌐 Shell | 📅 2017-04-22 : ` Rodent` 帮助你管理` Go`语言版本、项目、和追踪依赖
* [DepCharge](https://github.com/centerorbit/depcharge) ⭐ 23 | 🐛 1 | 🌐 Go | 📅 2021-12-23 :  帮助管理大型项目中众多依赖关系的命令。
* [aptly](https://github.com/smira/aptly) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2019-09-27 : `aptly`是一个` Debian`库管理工具
* [sg](https://github.com/ChristopherRabotin/sg) ⭐ 8 | 🐛 2 | 🌐 Go | 📅 2016-10-28 :  对一组`HTTP` 钩子（如`ab`）进行基准测试,可以使用每次调用之间的响应代码和数据,根据其之前的响应来确定特定的服务器压力。
* [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) :    将所有的\` GitHub 仓库、问题、里程碑和标签迁移到 Gitea 实例中。
* [Gogs](https://gogs.io/) :  自我托管的`Git`服务
* [Wide](https://wide.b3log.org/login) :  基于` Web` 的` IDE`,为使用` Go`语言的团队设计

***

### 其他软件库和软件包

* [croc](https://github.com/schollz/croc) ⭐ 39,827 | 🐛 9 | 🌐 Go | 📅 2026-08-16 :    轻松安全地将文件或文件夹从一台计算机发送到另一台计算机。
* [restic](https://github.com/restic/restic) ⭐ 35,553 | 🐛 566 | 🌐 Go | 📅 2026-08-01 :  解耦备份程序
* [Gor](https://github.com/buger/gor) ⭐ 19,310 | 🐛 341 | 🌐 Go | 📅 2026-01-27 :  Http 流量复制工具,用于将生产环境的流量在开发环境进行重放
* [toxiproxy](https://github.com/shopify/toxiproxy) ⭐ 12,251 | 🐛 104 | 🌐 Go | 📅 2026-08-04 :  用于自动化测试中模拟网络和系统状态的代理服务。
* [Comcast](https://github.com/tylertreat/Comcast) ⭐ 10,513 | 🐛 26 | 🌐 Go | 📅 2025-03-20 :   模拟网络波动情况下的网络数据连接
* [scc](https://github.com/boyter/scc) ⭐ 8,623 | 🐛 30 | 🌐 Go | 📅 2026-08-11 :   一个非常快速准确的代码计数器,具有复杂度计算和`COCOMO`估计功能。
* [confd](https://github.com/kelseyhightower/confd) ⭐ 8,423 | 🐛 178 | 🌐 Go | 📅 2024-07-16 :  使用`etcd`或` consul`来管理本地应用的配置文件
* [LiteIDE](https://github.com/visualfc/liteide) ⭐ 7,767 | 🐛 413 | 🌐 C++ | 📅 2026-08-15 : `LiteIDE` 是一个简单、开源、跨平台的` Go`语言` IDE`
* [drive](https://github.com/odeke-em/drive) ⭐ 6,730 | 🐛 287 | 🌐 Go | 📅 2024-02-09 :  命令行版本的`Google Drive`客户端。
* [Duplicacy](https://github.com/gilbertchen/duplicacy) ⭐ 5,668 | 🐛 335 | 🌐 Go | 📅 2026-08-06 :  跨平台网络和云备份工具
* [nes](https://github.com/fogleman/nes) ⭐ 5,653 | 🐛 12 | 🌐 Go | 📅 2024-08-17 : `Go` 语言编写的任天堂`(NES)`模拟器
* [myLG](https://github.com/mehrdadrad/mylg) ⭐ 2,719 | 🐛 13 | 🌐 Go | 📅 2020-02-26 :`Go`语言编写的命令行网络诊断工具
* [GoBoy](https://github.com/Humpheh/goboy) ⭐ 2,637 | 🐛 7 | 🌐 Go | 📅 2026-03-30 :   用`Go`编写的任天堂游戏机颜色模拟器。
* [Stack Up](https://github.com/pressly/sup) ⭐ 2,514 | 🐛 57 | 🌐 Go | 📅 2023-12-24 :` Stack Up`是一个超级简单的开发工具,就好比是服务器网络的`make`工具
* [lgo](https://github.com/yunabe/lgo) ⭐ 2,455 | 🐛 24 | 🌐 Go | 📅 2020-11-20 :   使用`Jupyter`进行交互式编程。它支持代码补全、代码检查,100%兼容`Go`。
* [Documize](https://github.com/documize/community) ⭐ 2,415 | 🐛 46 | 🌐 JavaScript | 📅 2026-05-18 :  维基软件,可以使用`SaaS`工具提供的数据
* [Circuit](https://github.com/gocircuit/circuit) ⭐ 1,975 | 🐛 13 | 🌐 Go | 📅 2023-10-18 : `Circuit`是一个可编程的`PaaS`以及`IaaS`,用于管理、发现以及编排各种云端应用的服务及主机
* [snap](https://github.com/intelsdi-x/snap) ⚠️ Archived :  强大的遥测框架
* [borg](https://github.com/crufter/borg) ⚠️ Archived :  基于终端的搜索引擎,用于搜索` bash`代码片段
* [shell2http](https://github.com/msoap/shell2http) ⭐ 1,499 | 🐛 6 | 🌐 Go | 📅 2026-08-08 :  通过HTTP服务器执行`shell`命令行(用于原型验证或远程控制)。
* [vFlow](https://github.com/VerizonDigital/vflow) ⭐ 1,155 | 🐛 71 | 🌐 Go | 📅 2024-08-22 :  高性能、可扩展、可靠的`IPFIX`,`sFlow`和`Netflow`集合.
* [peg](https://github.com/pointlander/peg) ⭐ 1,114 | 🐛 33 | 🌐 Go | 📅 2026-05-24 :  `Peg（Parsing Expression Grammar）`是一个`Packrat parser generator`的实现
* [Go Package Store](https://github.com/shurcooL/Go-Package-Store) ⭐ 896 | 🐛 7 | 🌐 Go | 📅 2023-11-26 :   一个可以显示你的`GoPATH` 路径下`Go`软件包的应用
* [gfile](https://github.com/Antonito/gfile) ⭐ 760 | 🐛 4 | 🌐 Go | 📅 2026-08-01 : 无需任何第三方工具通过`WebRTC`在两台电脑之间安全传输文件。
* [Leaps](https://github.com/jeffail/leaps) ⭐ 755 | 🐛 14 | 🌐 Go | 📅 2023-03-07 :   结对编程服务,使用操作变换来避免冲突。
* [Guora](https://github.com/meloalright/guora) ⭐ 673 | 🐛 7 | 🌐 Go | 📅 2023-01-31 :  一个用`Go`编写的类似于`Quora`的问答网络应用。
* [gocc](https://github.com/goccmack/gocc) ⭐ 662 | 🐛 25 | 🌐 Go | 📅 2026-01-13 : `Go`语言编写的`Go`语言编译器工具集
* [Gebug](https://github.com/moshebe/gebug) ⭐ 631 | 🐛 21 | 🌐 Go | 📅 2026-07-03 : - 一个通过启用`Debugger`和热加载功能,让`Docker`容器化后的`Go`应用调试变得超级简单。
* [mockingjay](https://github.com/quii/mockingjay-server) ⭐ 567 | 🐛 9 | 🌐 Go | 📅 2022-05-26 : 伪`HTTP`服务器,通过单一配置文件构造访问请求。同时你还可以让服务器提升负载,以进行更加符合现实情况的性能测试
* [woke](https://github.com/get-woke/woke) ⭐ 515 | 🐛 48 | 🌐 Go | 📅 2024-05-07 :   检测源代码中的排他性代码段。
* [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) ⭐ 477 | 🐛 11 | 🌐 Go | 📅 2023-03-23 : 视频流下载客户端。
* [ide](https://github.com/thestrukture/ide) ⭐ 366 | 🐛 0 | 🌐 Go | 📅 2022-11-24 :  为`Go`语言设计可以在浏览器的`IDE`。
* [ipe](https://github.com/dimiro1/ipe) ⚠️ Archived : `Go`语言编写的开源`Pusher`服务器,兼容` Pusher`客户端。
* [tcpprobe](https://github.com/mehrdadrad/tcpprobe) ⭐ 354 | 🐛 4 | 🌐 Go | 📅 2021-02-21 :  -`TCP`工具,用于网络性能和路径监控,包括套接字统计等。
* [wellington](https://github.com/wellington/wellington) ⚠️ Archived :` Sass`项目管理工具, 通过支持一些功能（例如Compass）扩展了这门语言
* [Cherry](https://github.com/rafael-santiago/cherry) ⭐ 299 | 🐛 0 | 🌐 Go | 📅 2017-06-24 : `Go`语言实现的一个微型网络聊天服务器
* [joincap](https://github.com/assafmo/joincap) ⭐ 219 | 🐛 4 | 🌐 Go | 📅 2025-06-06 :   用于合并多个`pcap`文件的命令行工具。
* [Orbit](https://github.com/gulien/orbit) ⭐ 187 | 🐛 3 | 🌐 Go | 📅 2021-01-18 :   运行命令和从模板生成文件的简单工具。
* [vaku](https://github.com/lingrino/vaku) ⭐ 160 | 🐛 1 | 🌐 Go | 📅 2026-08-04 :  为`Vault`中基于文件夹的功能如复制、移动和搜索提供`CLI`和`API`。
* [boxed](https://github.com/tejo/boxed) ⭐ 78 | 🐛 0 | 🌐 Go | 📅 2018-08-09 :  基于`Dropbox`的博客引擎
* [dp](https://github.com/scryinfo/dp) ⭐ 77 | 🐛 67 | 🌐 Go | 📅 2023-01-07 :  与区块链进行数据交换的SDK,开发者可以轻松进行`DAPP`的开发。
* [Seaweed File System](https://github.com/chrislusf/seaweedfs) ⭐ 36 | 🐛 1 | 🌐 Go | 📅 2026-07-21 :  快速、简单、可扩展的分布式文件系统,具有`O(1)`的磁盘查找效率
* [term-quiz](https://github.com/crazcalm/term-quiz) ⭐ 25 | 🐛 0 | 🌐 Go | 📅 2018-10-24 :  终端测试库。
* [naclpipe](https://github.com/unix4fun/naclpipe) ⭐ 22 | 🐛 0 | 🌐 Go | 📅 2018-11-18 :   简单的基于`NaCL EC25519` 的加密管道工具
* [Snitch](https://github.com/lucasgomide/snitch) ⭐ 16 | 🐛 5 | 🌐 Go | 📅 2018-07-23 :  当通过`Tsuru`部署应用程序时,可以简单快速的通知团队的工具
* [GoDocTooltip](https://github.com/diankong/GoDocTooltip) ⭐ 13 | 🐛 0 | 🌐 JavaScript | 📅 2022-12-03 :  用来显示`go`语言文档的`chrome`浏览器插件
* [Better Go Playground](https://goplay.tools) :  具有语法高亮、代码补全等功能的`playground`
* [Docker](http://www.docker.com/) :  一个为开发者和系统管理员提供的针对分布式应用的开源平台
* [GoLand](https://jetbrains.com/go) :   跨平台、全功能`Go` 语言集成开发环境
* [hugo](http://gohugo.io/) :  - 快速、现代的静态`web`引擎
* [Juju](https://jujucharms.com/) :   服务部署及编排工具,,支持`EC2`,`Azure`,`Openstack`,`MAAS` 等等
* [limetext](https://limetext.github.io) : `Lime Text` 是一个强大又优雅的编辑器,主要使用`Go` 语言开发,意在成为`Sublime Text`的继承者。
* [orange-cat](https://github.com/noraesae/orange-cat) : `Go`语言编写的` Markdown`预览工具
* [syncthing](https://syncthing.net/) :   开源、去中心化的文件同步工具和协议
* [tsuru](https://tsuru.io/) :  可扩展的、开源的`SAAS` 软件

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-16._
