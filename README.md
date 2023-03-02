![banner.png](https://media.githubusercontent.com/media/adoyle-h/_imgs/master/github/tech-talks/banner.png)

不闲聊的技术论坛。基于 Github Discussions 搭建。由 Github 社区成员共同参与并维护。

## TOC

<!-- MarkdownTOC GFM -->

- [愿景](#愿景)
- [特点](#特点)
- [版块目录](#版块目录)
- [使用方法](#使用方法)
    - [参与讨论](#参与讨论)
    - [创建讨论](#创建讨论)
    - [搜索讨论](#搜索讨论)
    - [订阅讨论](#订阅讨论)
    - [提问](#提问)
    - [回答与评论](#回答与评论)
    - [投诉](#投诉)
    - [其他](#其他)
- [用户守则](#用户守则)
- [管理员列表](#管理员列表)
- [版权声明](#版权声明)
    - [知识产权](#知识产权)
    - [免责声明](#免责声明)

<!-- /MarkdownTOC -->

## 愿景

在这个论坛我们只围绕技术话题进行分享、讨论、提问、解答。

这里没有人生感言，没有政治立场，没有职场八卦，没有招聘信息，没有二手交易。

希望在这里，我们能够分享有趣的事物，交流想法，获得灵感，结识朋友，提升自己。

## 特点

1. 不闲聊。只聊技术。中文论坛。
2. 基于 Github Discussions 搭建。由 Github 社区成员共同参与并维护。
3. 用户可以[订阅自己关心的领域讨论](#订阅讨论)，不受其他领域讨论打扰。
4. 支持[邮件通知，GitHub 通知](https://docs.github.com/zh/account-and-profile/managing-subscriptions-and-notifications-on-github/setting-up-notifications/about-notifications)。无需主动刷论坛网页，看一眼邮箱或者通知列表就行啦。
5. 支持[全局搜索，版块搜索](#搜索讨论)。
6. 支持贴图，GIF 动图，[上传视频](https://github.blog/2021-05-13-video-uploads-available-github/)，外链。

## 版块目录

- [Tech Talks 主版块](https://github.com/just-talks/tech-talks/discussions): 面向程序员的大众话题。
- [前端](https://github.com/just-talks/frontend/discussions): HTML、CSS、JS 等话题
- [容器](https://github.com/just-talks/container/discussions): Docker，LXC，Podman 等容器技术
- [DevOps](https://github.com/just-talks/devops/discussions): 系统运维，网络知识，K8S
- [硬件](https://github.com/just-talks/hardware/discussions): 嵌入式，智能硬件，树莓派，arduino，路由器，交换机，GPU，DPU，各种芯片模块和开发板
- [数据库](https://github.com/just-talks/database/discussions)
- [Linux](https://github.com/just-talks/linux/discussions): Unix/Linux/BSD 系统相关
- [Shell](https://github.com/just-talks/shell/discussions): 终端、Shell 脚本相关
- [编辑器](https://github.com/just-talks/editor/discussions): Vim、Neovim、Emacs、VS Code、Sublime、Eclipse 等编辑器、IDE 相关话题
- [算法](https://github.com/just-talks/algorithm/discussions)
- [机器学习](https://github.com/just-talks/ML/discussions): 人工智能，深度学习，NLP，AIGC
- [游戏开发](https://github.com/just-talks/game-dev/discussions)
- [iOS](https://github.com/just-talks/ios/discussions)
- [Android](https://github.com/just-talks/android/discussions)
- [Web3](https://github.com/just-talks/web3/discussions): 区块链，以太坊，加密货币，Dapp
- [安全](https://github.com/just-talks/security/discussions): 网络、软件、硬件方面的安全攻防。渗透工具。Kali Linux。CVE。
- [Apple](https://github.com/just-talks/apple/discussions): 苹果自家的硬件和软件产品：MacOS, iPhone, MacBook, iOS, iPad, iWatch, Xcode, WWDC 等
- [微软](https://github.com/just-talks/microsoft/discussions): 微软自家的硬件和软件产品：Windows, Surface, Bing, Office, Xbox, Github 等
- [数学](https://github.com/just-talks/math/discussions): MATLAB，Mathematica，R 语言，统计学，数学分析
- [逻辑学](https://github.com/just-talks/logic/discussions): 逻辑编程，Prolog，逻辑证明，推理
- [写作](https://github.com/just-talks/writing/discussions): 写作，翻译，RFC
- [设计](https://github.com/just-talks/design-talks/discussions): 建筑设计、平面设计、排版、字体等设计话题。并非架构设计。
- 编程语言
  - [C/C++](https://github.com/just-talks/c/discussions)
  - [Lua](https://github.com/just-talks/lua/discussions)
  - [NodeJS](https://github.com/just-talks/nodejs/discussions): NodeJS、JavaScript、Typescript
  - [Rust](https://github.com/just-talks/rust/discussions)
  - [Golang](https://github.com/just-talks/golang/discussions)
  - [Zig](https://github.com/just-talks/zig/discussions)
  - [Python](https://github.com/just-talks/python/discussions)
  - [Java](https://github.com/just-talks/java/discussions)
  - [Ruby](https://github.com/just-talks/ruby/discussions)
  - [Haskell](https://github.com/just-talks/haskell/discussions)
  - [Racket](https://github.com/just-talks/racket/discussions)
- [闲聊][闲聊版块]: 唯一可以聊非技术话题的版块。在这里释放你的闲聊欲望。

所有版块都属于 [Just Talks 组织的子项目](https://github.com/orgs/just-talks/repositories?type=source)。
(注意，Follow Just-Talks 组织并不等同于[订阅讨论](#订阅讨论))

## 使用方法

### 参与讨论

- 请在对应版块的 Github Discussions 参与讨论。不要创建 Pull Request。
- 不要发信息量很低的评论。比如 “+1”，“支持”，“哈哈”，“顶帖”，“沙发”，“前排”，“路过”，“不明觉厉”。
- 建议用 [Github Emoji 标签][]表达个人态度。比如 ❤️  表达喜欢，👍 表达认同，👎 表达不认同，👀 表达关注。

### 创建讨论

- 创建讨论前请先搜索，避免创建重复讨论。
- 请在对应的版块里创建讨论。若无对应版块，请到[论坛事务][]发帖请求创建新版块。
- [如何判断应该在哪个版块发帖？](https://github.com/just-talks/tech-talks/discussions/13)
  - [如果同一个话题想发到多个版块怎么办？](https://github.com/just-talks/tech-talks/discussions/13#discussioncomment-5165716)
- 请在对应的讨论分类 (Categories) 下创建讨论。若无对应分类，可以发到「General」分类下。
- 标题应当言简意赅。不要把内容都写在标题。
- 创建讨论后请标记相应的标签 (Label)，便于他人筛选浏览。
  - 如果没有合适的标签，你可以修改项目的 `.github/labels.yml` 文件，提个 PR，审核通过后会自动加上标签。

### 搜索讨论

- 版块搜索：在 Discussions 页面的搜索框输入搜索词即可。
- 全局搜索：在最上方 Github 搜索框输入 `org:just-talks 搜索词` 可搜索所有版块的讨论。比如搜[算法](https://github.com/search?q=org%3Ajust-talks+%E7%AE%97%E6%B3%95&type=discussions)。

### 订阅讨论

- 你无需主动刷论坛网页，看一眼邮箱或者通知列表就行啦。
- 对于你感兴趣的版块，点击项目的 `Watch` 按钮来订阅消息。具体用法请看 [Github - 查看订阅](https://docs.github.com/zh/account-and-profile/managing-subscriptions-and-notifications-on-github/managing-subscriptions-for-activity-on-github/viewing-your-subscriptions)。
    <img width="350" alt="点击 Watch Custom 订阅 Discussion" src="https://user-images.githubusercontent.com/1998490/222496718-d135034d-efd2-43d6-b8ff-149d4efd630a.png">
- 你也可以只订阅某个讨论。进入某个讨论，点击右边 Notifications 的 `Subscribe` 按钮。

### 提问

- 统一在「Q&A」分类下提问，因为这个分类下的讨论可以确认答案 (Answers enabled)。
- 提问前需了解并遵守「[提问的智慧](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way)」「[如何有效地报告 Bug](http://www.chiark.greenend.org.uk/~sgtatham/bugs-cn.html) ([链接备份](https://web.archive.org/web/20230221005113/https://www.chiark.greenend.org.uk/~sgtatham/bugs-cn.html))」「[How to create a Minimal, Complete, and Verifiable example](http://stackoverflow.com/help/mcve)」。
- 提问前先问问 Google，ChatGPT，new Bing。
- 不必羞怯于暴露自己的无知，我们不会指责你。但偷懒不行，我们会给你点 👎。提问不是索取，不是只写一个标题就等别人把答案喂给你。
- 提问是一种交换。你给别人出示具体问题、期望目标以及你的失败尝试，别人才愿意给予你指引。
- 很多时候，解决问题的人是提问者自己。因为把问题描述清楚了，通往答案的路就会变得明显。
- 如果你提出一个好问题，会有人愿意与你一起寻找宝藏。

### 回答与评论

- 先理解对方的观点，再表达自己的观点。
- 多给予他人肯定与支持，或者帮助他人解决问题。少表达不满、嘲笑、指责和愤怒，这些表达既没指出问题所在，对解决问题也没任何帮助。
- 保持宽容与耐心。不要只回复 RTFM 或者 STFW。起码加上一个文档链接，让人知道去哪找答案。
- 允许直接使用 ChatGPT，new Bing 这类 AI 的回答。前提是你确认 AI 说的正确，AI 的回答就等同于你的回答。

### 投诉

- 请到[论坛事务][]发帖描述需求。
- 如果有人攻击你，你别急着反击输出，先 @[管理员](#管理员列表)。如果他违反了用户守则，管理员会处理的。

### 其他

- [关于如何基于 Github Discussion 做论坛](https://github.com/just-talks/tech-talks/discussions/14)
- 让我们专注于技术问题，而不是人本身的问题。人比技术复杂太多。对于陌生网友，我们更是知之甚少。
- **请大家多参与分享与交流。帮忙推广本论坛，分享转发给需要的人。给项目加一颗 Star。感谢。**

## 用户守则

0. 只讨论技术。禁止发布与技术无关的帖子和评论。（[闲聊版块][]除外）
1. 保持友善。多赞赏，少贬低。
2. 请用中文交流。这是中文技术论坛。如果你不懂中文，建议使用翻译器。(Please communicate in Chinese. This is a Chinese language technical forum. If you don't understand Chinese, we recommend to use a translator.)
3. 禁止阴阳怪气、嘲讽、辱骂、威胁、暴露他人隐私等行为。
4. 禁止谈论政治、宗教、信仰。
5. 禁止发布求职或招聘信息。
6. 禁止发布无信息量的评论，比如 “+1”，“顶”，“沙发”，“前排”，“留名”，“路过”，“不明觉厉”。
7. 禁止发布任何有关盗版的任何信息。
8. 禁止全文转载文章。请发文章链接，最好再补上备份链接。如何制作备份链接请看[这篇文章](https://adoyle.me/Today-I-Learned/others/archive-webpage.html) ([链接备份](https://web.archive.org/web/20230227102341/https://adoyle.me/Today-I-Learned/others/archive-webpage.html))。
9. 禁止发布有关歧视、色情、性暗示、擦边球的图片、视音频、文字、外链等信息，包括 AI 生成的此类信息。

违反用户守则的言论会被删除。当你在网上发帖时，需要考虑是否违反你所在地区的法律法规。
**请大家遵守规则**。

## 管理员列表

- 所有版块：@adoyle-h
- 闲聊版块：[招募中](https://github.com/just-talks/chat/discussions/1)

## 版权声明

### 知识产权

1. 发布在本论坛的原创文章、评论、图片等内容的知识产权均归用户本人所有。

2. 用户通过转载、复制、截图等方式获取他人内容，并发布在本论坛的，相关内容的知识产权属于内容的权利人。用户不得侵犯他人知识产权及其他合法权利。因用户发布内容引发知识产权纠纷的，用户须自行承担相应后果，若因此造成本论坛损失的，本论坛有权依照法律规定维护合法权益。

3. 本论坛展示的标识、版面设计、排版方式、文本、图片、图形等受著作权法、商标法、专利法及其他法律保护的部分，未经论坛所有者书面同意，不得进行任何形式的发布、改编、修改，或其他商业及非商业性使用。

4. 本论坛不对用户发布内容的知识产权权属进行保证，并且尊重权利人的知识产权及其他合法权益。若权利人认为用户发布的内容侵犯自身的知识产权或其他合法权益，可向论坛管理员请求帮助。

### 免责声明

1. 用户发布的一切内容仅代表用户个人观点，不视为论坛所有者和管理员知晓其内容之存在、赞同其内容之观点或证明其内容的真实性。作为内容的发布者，需对所发布内容负责，因所发布内容引发的一切纠纷，由该内容的发布者承担全部法律责任。在法律允许的范围内，本论坛所有者和管理员对上述内容予以免责。

2. 本论坛使用 Github 为用户发布内容提供空间，本论坛不对论坛内容、服务功能、可靠性、可用性做任何承诺。

3. 用户在发布侵犯他人知识产权、名誉权或其他合法权益的内容，或发布损害国家利益、违背现行法律法规及相关政策、违背公序良俗的相关内容时，论坛管理员有权对相应内容采取屏蔽、删除等处理措施。


<!-- links -->

[闲聊版块]: https://github.com/just-talks/chat/discussions
[论坛事务]: https://github.com/just-talks/tech-talks/discussions/categories/7-%E8%AE%BA%E5%9D%9B%E4%BA%8B%E5%8A%A1
[Github Emoji 标签]: https://github.blog/2016-03-10-add-reactions-to-pull-requests-issues-and-comments/
