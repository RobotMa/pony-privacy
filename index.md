---
title: Pony 小马 — 隐私政策 / Privacy Policy / プライバシーポリシー
---

[中文](#zh) · [English](#en) · [日本語](#ja) · [支持 / Support / サポート](support.html)

# Pony 小马 · 隐私政策 {#zh}

**最后更新：2026 年 10 月 31 日**

小马（Pony）是一款日语与英语学习应用，由 **Roma Tech LLC** 开发。
本政策说明这款应用收集什么、不收集什么，以及为什么。iOS 版与 Android 版的
行为并不完全相同，下面分别列出。

**谁对你的数据负责。** 对于本政策所述的处理，**Roma Tech LLC**（美国公司）是数据
控制者。我们没有委任数据保护官；任何隐私问题都可以发到本页末尾的邮箱。

**关于「匿名」。** 我们不知道你是谁：应用不要求注册，不收集邮箱、电话或广告标识符。
但应用会用一个在你设备上随机生成的标识符，把同一次安装的使用记录串在一起。按欧盟
《通用数据保护条例》（GDPR）等法律的标准，这类**假名化**数据仍可能属于个人数据，
所以本政策按个人数据对待它们，并在下文说明处理依据、保存期限和你的权利。

## 我们不收集的东西

- **不收集你的邮箱或电话。** 应用不要求注册；登录是**可选的**（iOS 上的
  「通过 Apple 登录」），即使登录，我们也只向 Apple 索取**姓名**一项，
  邮箱和电话既不索取、也不保存。姓名的去向见下方「登录（可选）」。
- **不做跨应用/跨网站追踪。** 没有广告 SDK，没有数据经纪商，不投放定向广告。
  iOS 上不会弹出 App Tracking Transparency 授权框，因为我们没有可追踪的东西。
- **不使用持久设备标识符做追踪。** 不使用广告标识符（IDFA / GAID）、Android ID、
  IMEI 或任何硬件序列号。在 Android 上，Google Play Integrity 会在应用启动时预先
  准备，并在你提交报错、购买或恢复购买时处理应用、许可和设备证明信息，以验证请求
  来自正版安装；该用途见下文，不用于广告或用户追踪。
- **不上传你输入的文字（报错时的两个例外见下）。** 你在「学习目标」里手写的
  内容**不会发送给我们**：它保存在你的设备上，并可能随你自己的 iCloud 或 Google
  备份同步（见「你的学习进度」），我们读不到。只有你主动提交报错时有两个例外：
  选「其他」后你**自愿填写**的那段说明，以及截图上当时可见的答题文字
  （见「使用统计」）。除此之外，报错随附的诊断信息里不含你输入的文字。
- **我们不接收、不保存录音。** iPhone 或 iPad 上没有装这门语言的离线语音包时，
  跟读录音由 Apple 的语音识别服务识别，见下方「[跟读发音](#跟读发音)」一节。

## 我们收集的东西

### 使用统计

为了改进课程，应用会发送学习行为事件，包括：应用启动；课程的开始、完成与中途退出；
卡片的展示；每道练习题的对错与作答耗时；跳过的跟读；复习完成；连续学习天数；
五十音热身与英语卡片的使用情况；定级测试、章末测验与跳级考的结果；引导流程中选择
的学习目标、语言水平以及「你从哪里知道小马」的选项（不含你手写的补充内容，只记录
是否填写过）；付费页的展示、所选方案与购买结果；以及（如果你登录了）一次「已登录」
的计数——只记录这件事发生过，不含姓名或任何身份信息。

此外，iOS 版在界面出现卡顿时会发送一条性能事件：卡顿出现在哪个环节
（打字、判题、报错弹窗）、次数、最长耗时。不卡就不发。

跟读功能不可用时，应用会发送一条事件，说明原因、对应的语言，以及你的设备上
**是否启用了日语输入法**（只发「是 / 否」，不发输入法列表），用于判断语言包问题。
iOS 版在你的 iCloud 键值存储空间已满、无法备份进度时，会发送一条计数事件。
应用在你完成一章等时刻请求系统评分弹窗时，会记录这次请求（触发场景、章节、第几次
请求）；评分弹窗由 Apple 或 Google 显示和处理，我们不知道你是否评分、评了几分。

应用崩溃、停止响应或被系统结束（包括在后台被系统回收）后，会在下一次启动时发送一份诊断摘要：问题类型、出错的代码位置（类名与方法名，或程序模块名与偏移量）、出事时的应用版本与系统版本、设备型号、当时所在的页面类别（仅 Android）和发生时间（精确到小时）。应用还会发送启动耗时（iOS 为系统按天汇总的分布，Android 为单次冷启动的毫秒数）。摘要只从这些固定的技术字段生成，不包含你输入或说出的任何内容、识别结果、学习内容或账号信息；和上面的事件一样，它只关联到下文那个随机标识符。

你在卡片上点「报错」并选择「其他」时，可以**自愿**填写一段说明（不超过
500 字）。这段话会随报错一起发送，并作为一条使用统计事件发送，**仅用于改进
课程内容**。作为使用统计事件的那一份，不与姓名、邮箱或账号关联；随报错发送的那一份，
在 iOS 上会与报错附带的、由 Apple 生成的用户记录编号关联（见下文；该编号不是你的
Apple ID、姓名或邮箱），在 Android 上不带这个编号，不与姓名、邮箱或账号关联。
不填写不影响报错。

报错时会附上**当前卡片画面的截图**（仅含本应用自己的界面，技术上不可能
包含应用之外的内容；如果答题文字当时可见，也会出现在截图中），用于排查
显示与流程问题。截图下方还拼着一条**诊断信息**：构建号、系统版本（Android 版
另附**设备型号**），以及最近若干条会话事件——经过的页面、卡片切换、音频播放、
录音、卡顿耗时等。它**不包含录音本身，也不包含你输入的文字或跟读时识别出的
文字**（你自愿填写的那段报错说明，以及截图画面上本来显示着的识别结果除外，
见「[跟读发音](#跟读发音)」）：打字只记录长度，音频只记录课程文本的前几个字。
截图和诊断信息本身不含你的姓名、邮箱或账号。在 iOS 上，它们会与报错附带的、由
Apple 生成的用户记录编号关联（见下文；该编号不是你的 Apple ID、姓名或邮箱）；在
Android 上经中转发送，不带这个编号。它们仅用于修复问题和改进产品，不用于任何其他
目的。

在 iOS 上，报错附件直接保存到**我们自己的 Apple CloudKit 容器**；CloudKit 会为每条
记录自动附上一个由 Apple 生成的**用户记录编号**——它只在本应用的容器内有效，不是
你的 Apple ID、姓名或邮箱；因此 iOS 上的报错与这个编号关联。我们看得到这个编号，但无法据此得知你是谁。在 Android
上，附件先通过 HTTPS 发送到**我们在 Google Cloud Run 上的专用中转服务**，并
由 **Google Play Integrity** 确认这次上传来自正版安装——这一步是为了挡住伪造
上传，与你的身份无关。为完成验证，Google 会处理请求摘要、应用包名/版本/签名
证书、设备上已登录账号对应的 Play 许可状态，以及密钥证明证书和设备证明令牌。
Google 声明这些数据加密传输、按固定期限删除；我们不将其用于识别或追踪个人。验证
通过后，附件同样保存到 Apple CloudKit。Android 设备上待传的临时截图存放在不参加
系统备份的目录；成功上传、永久失败或超过七天后删除。已经提交的报错记录的保存
期限见「[保存期限](#保存期限)」。你可以按本页末尾的邮箱联系我们，并提供大致提交时间和
卡片，以请求删除某条报错。

每条事件附带：应用版本、构建号、安装渠道（正式商店 / 测试版 / 其他来源）、系统语言、操作系统版本、距首次安装的天数。

其中「系统语言」包含地区设置（例如 zh_CN）。与购买相关的事件还附带商品 ID、显示价格
（含币种）和购买类型；购买失败时附带你所在商店的**国家或地区代码**，用于发现某个
地区的付费故障。

这些事件关联到一个**在你的设备上随机生成的标识符**（一串随机 UUID，在离开
设备之前还会先做一次哈希）。它不是你的 Apple ID，不是 Google 账号，不是任何
设备标识符，也不与任何姓名、邮箱或账号关联——即使你用「通过 Apple 登录」，
那个姓名也只留在你的设备上，从不进入统计。**删除并重新安装应用，这个标识符
即被重置**，新旧数据无法关联；在 iOS 上，登录后使用「删除账号」也会在下次启动时
重置它。因为这个标识符能把同一次安装的使用记录串在一起，我们按假名化的个人数据
对待这些统计（见本页开头）。我们无法从这个标识符反查出你是谁。目前应用内没有单独
关闭使用统计的开关；删除应用即停止发送。

### 平台差异

| | iOS | Android |
|---|---|---|
| 使用统计 | 收集 | 收集 |
| 跟读发音（麦克风） | 有此功能 | 有此功能 |
| 登录（可选，只要姓名） | 通过 Apple 登录 | 没有登录，只有本机昵称 |
| 删除账号 | 登录后可在「我的」页删除（可选同时清除学习进度） | 没有账号 |
| 学习进度备份 | 用户开启时使用 iCloud | 系统允许时使用 Google Android Auto Backup |
| 报错附件路径 | Apple CloudKit | Google Cloud Run / Play Integrity → Apple CloudKit |
| 报错附带的额外信息 | CloudKit 用户记录编号、系统版本 | 系统版本、设备型号 |

### 数据处理方与基础设施

以下服务替我们处理数据，用途仅限本政策写明的那些：

| 服务方 | 所在地 | 做什么 |
|---|---|---|
| **TelemetryDeck GmbH**（[telemetrydeck.com](https://telemetrydeck.com)） | 德国；按其公开说明，服务器位于德国与荷兰 | 接收并保存使用统计。它是受我们指示、代表我们处理数据的服务提供方，不将数据用于自身目的，也不出售数据；按其说明，它不保存 IP 地址。 |
| **Apple**（CloudKit） | 美国 | 保存报错附件（截图、诊断信息、说明），只有我们能读取。 |
| **Google**（Google Cloud Run） | 美国（us-west1 区域） | 运行我们的 Android 报错中转与购买验证服务。 |
| **Google**（Play Integrity、Google Play Developer API） | — | 验证 Android 请求来自正版安装；核实 Play 购买与订阅状态。 |
| **GitHub**（GitHub Pages） | 美国 | 托管本政策页面，以及 iOS 付费页读取的一个公开配置文件。该请求不含任何用户数据，但 GitHub 会像任何网站一样看到请求的 IP 地址。 |

以上都是替我们干活的处理方和基础设施。
**我们不向数据经纪商出售或共享任何数据，也不用它做广告定向**；除上述
用途外，我们不向任何第三方披露数据供其自行使用。

## 跟读发音

跟读打分在 iOS 上使用 Apple 的语音识别：

- 如果你的 iPhone 或 iPad 上已经装有这门语言的离线语音包，识别在设备上完成，
  录音不会离开设备。
- 如果没有装，那一次跟读的录音会经 Apple 的语音识别服务（Apple 的服务器）转成
  文字，用于打分。我们的服务器不接收、也不保存这些录音或识别出的文字。例外：
  如果你在显示跟读得分的界面上主动点「报错」，那张截图会包含屏幕上显示的识别
  文字（「识别到：…」），并随报错一起发给我们（Android 版同样如此，见
  「[使用统计](#使用统计)」）。Apple 对这些数据的处理适用
  [Apple 隐私政策](https://www.apple.com/legal/privacy/)。
- 你可以在 iOS「设置」›「通用」›「键盘」中打开「启用听写」，并在「听写语言」里
  勾选这门语言；系统下载离线语音包之后，跟读就会改回在设备上识别。

在 Android 上，跟读打分全程在你的设备上完成：优先使用 Android 明确提供的**设备端语音识别**（Android 12 / API 31 及以上）；设备没有设备端识别时，改用**打包在应用里的离线识别模型**（开源的 Vosk，日语与英语），同样只在设备上运行。两种方式都不会回退到可能联网的通用识别服务。缺少系统语音包时，应用会提供下载入口，语音包由系统下载。

**录音不会发送到我们的服务器**，也不会被我们存储；使用统计只发送分数
（0–100）、识别语言和是哪张卡。
朗读时「读到哪里、哪里变绿」的实时提示同样完全在设备上计算，不涉及任何
上传。麦克风权限由系统弹窗征询，你可以随时拒绝或
在系统设置中撤销；拒绝后其余功能完全不受影响。

## 登录（可选）

iOS 版的「通过 Apple 登录」是**可选**的，它唯一的作用是让「我的」页显示一个
名字。我们只向 Apple 索取**姓名**，不索取邮箱；拿到的姓名**只保存在你自己的
设备上，从不上传**——它不会发往我们的任何服务器，也不参加小马的 iCloud 同步，
不会同步到你的其他设备（但可能随你的整机备份一起备份）。登录时苹果还会给出一个**只对小马有效**的匿名
用户编号，用来确认授权是否仍然有效；它和姓名一样只存在你的设备上。你可以
随时在应用内退出登录，退出即把两者一并从设备上删除，学习进度不受影响。

登录后，你还可以在「我的」页**删除账号**：它会从设备上删除姓名和 Apple 用户编号，
并在下次启动时重置统计标识符；你可以选择同时清除本机与你 iCloud 中的学习进度。

**不登录不影响任何功能**：课程、复习、跟读发音，以及购买与恢复购买都照常
可用（购买由 App Store 处理，与登不登录小马无关）。

Android 版没有登录，只能设置一个**保存在本机**的昵称（它不会发送给我们，但会随
Android 备份一起备份）。

## 你的学习进度

学习进度、复习计划、经验值等保存在**你自己的设备上**。

iOS 版若你开启了 iCloud，进度——包括引导问卷里的答案（含「学习目标」的手写
补充）——会备份到**你自己的 iCloud 账户**。Android 版在设备、Google 服务和系统
设置允许时，会通过 Android Auto Backup 把进度、昵称和问卷答案备份到你的
Google 账户，并可能在重装或换机时恢复。平台备份由 Apple 或 Google 管理，我们
无法读取。Android 的随机统计标识符明确不参加备份，因此重装后仍会重置。

## 购买与订阅

会员购买由 Apple App Store 或 Google Play 处理。我们不接收或保存你的银行卡号、
账单地址或商店账号凭据。应用会从商店取得商品、价格、购买与订阅状态，以便显示
本地化价格、解锁内容、恢复购买及管理订阅；使用统计会记录商品 ID、显示价格、
购买类型和购买结果（失败时附带商店国家或地区代码），用于了解付费流程是否正常。

Android 版在购买、恢复购买，以及启动或回到前台时检查已有购买时，会通过 HTTPS 将
商品 ID、商品类型、Google Play purchaseToken、应用构建号和 Play Integrity 证明发送到我们在 Google Cloud Run 上的专用服务。该服务
调用 Google Play Developer API 核实当前购买/订阅状态，并确认已经完成的交易，然后
只把权益状态返回应用。Roma Tech 不记录或持久保存 purchaseToken、订单资料或商店账号
信息；token 只在这次实时验证所需的内存和加密传输中处理。Google 会按其自己的政策
管理 Play 交易记录。

## 处理目的与法律依据

如果你位于欧洲经济区、英国或瑞士，我们按以下依据处理你的数据（GDPR 第 6 条，以及
英国、瑞士的对应规定）：

| 处理 | 目的 | 法律依据 |
|---|---|---|
| 使用统计（含卡顿与闪退诊断） | 了解课程哪里太难、哪里出错；发现闪退与付费流程故障 | 我们改进课程、保持应用正常运行的**合法利益**（第 6(1)(f) 条） |
| 报错（截图、诊断信息、说明） | 排查你主动报告的问题 | 我们排查并修复问题的**合法利益**（第 6(1)(f) 条）；你可以随时反对，或要求删除某条报错 |
| Android 购买验证 | 交付你购买的会员权益 | **履行合同**（第 6(1)(b) 条） |
| Play Integrity 验证 | 防止伪造上传与盗版 | 保护服务安全的**合法利益**（第 6(1)(f) 条） |
| 服务器请求日志 | 安全与故障排查 | 保护服务安全的**合法利益**（第 6(1)(f) 条） |

「通过 Apple 登录」得到的姓名、本机昵称、学习进度和平台备份不会发送给我们，不属于
我们的处理。

除使用统计外，提供数据都是自愿的：不报错、不登录、不授权麦克风，都不影响学习。
我们不进行任何对你产生法律效果或类似重大影响的自动化决策；复习排期和定级测试只
决定下一张显示哪张卡。

## 保存期限

| 数据 | 保存多久 |
|---|---|
| 使用统计（含诊断摘要） | 由 TelemetryDeck 保存。该服务目前没有固定的删除期限；按其公开说明，预计 7 至 10 年后删除，但不作保证。 |
| 报错记录（截图、诊断信息、说明） | 自提交起最长 24 个月，到期删除；你可以随时要求提前删除。 |
| Android 设备上待传的临时截图 | 上传成功、永久失败或超过七天后删除。 |
| 服务器请求日志（Google Cloud Run，可能含 IP 地址） | 30 天（Google Cloud 平台默认期限）。 |
| Android 购买验证中的 purchaseToken | 不保存，只在这次验证所需的内存中处理。 |
| 保存在你设备上的数据 | 直到你删除应用；平台备份按你的 Apple 或 Google 账户设置保留。 |

## 跨境传输

Roma Tech LLC 位于美国。你通过应用直接提供给我们的数据，由我们在美国处理；按欧洲
数据保护委员会（EDPB）05/2021 号指南，这本身不属于 GDPR 第五章所说的「传输」，但
我们仍按本政策和 GDPR 处理这些数据。替我们处理数据的服务方中：

- **Google**（Cloud Run，美国 us-west1 区域）：Google LLC 已取得欧美数据隐私框架
  （EU-U.S. Data Privacy Framework）认证，其云服务的数据处理条款另规定了欧盟标准合同条款；
- **Apple**（CloudKit，美国）：按 Apple 的说明，其对欧洲经济区、英国和瑞士个人数据的
  国际传输受标准合同条款约束；
- **TelemetryDeck** 在欧盟境内（德国、荷兰）处理使用统计。

你可以通过下方邮箱索取这些保障措施的说明。

## 儿童

本应用面向成人学习者，不针对 13 岁以下儿童，也不会有意收集儿童的个人信息。
欧洲经济区各国规定的、可以自行同意数字服务的年龄为 13 至 16 岁不等；如果你在欧洲
经济区、未满所在国家规定的年龄，请在父母或监护人同意后再使用本应用。如果你认为
我们收到了儿童的数据，请联系我们删除。

## 你的权利

小马没有服务端账号，我们不知道你的姓名、邮箱或电话（「通过 Apple 登录」
得到的姓名只存在于你自己的设备上，我们从未收到过）。

删除应用会停止新的收集并删除本机副本，但平台备份可能按你的 Apple 或 Google
账户设置保留，并在以后恢复；你可在相应平台的系统设置中管理这些备份。重新安装
会生成新的统计标识符。对于已经主动提交的报错附件，可按下方邮箱联系我们，
并提供大致提交时间和卡片以请求删除——正因为没有账号，请求中提供这些线索才能
帮助我们定位记录。

**如果你位于欧洲经济区、英国或瑞士**，你依法享有以下权利：

- **访问**：了解我们是否处理你的数据，并取得一份副本；
- **更正**：更正不准确的数据；
- **删除**：要求删除你的数据；
- **限制处理**：在特定情况下要求我们暂停处理；
- **数据可携带**：在法律规定的情形下，以常用的电子格式取得你提供给我们的数据；
- **反对**：反对我们基于合法利益进行的处理；
- **投诉**：向你居住地、工作地或认为侵权发生地的数据保护监管机构投诉（欧洲经济区
  各国监管机构名录见 [EDPB 成员页](https://www.edpb.europa.eu/about-edpb/about-edpb/members_en)；
  英国为 ICO，瑞士为联邦数据保护和信息专员 FDPIC）。

行使这些权利，请写信到下方邮箱。因为我们不知道你是谁，多数情况下我们无法把统计数据
对应到你本人（GDPR 第 11 条）；如果你能提供帮助我们找到相关记录的信息——例如报错的
大致时间和卡片——我们会据此处理。如果确实无法对应，我们会如实告诉你。我们会在收到
请求后一个月内答复。

如果你对数据处理有任何疑问，可通过下方邮箱联系我们。

## 变更

本政策如有变更，我们会更新本页顶部的日期。应用的重大数据行为变更会同时
在 App Store 与 Google Play 的数据披露中反映。

本政策提供中文、英文和日文版本；如有出入，以英文版为准。

## 联系方式

**Roma Tech LLC**（数据控制者）
邮箱：<a href="mailto:roma.tech.ai@gmail.com">roma.tech.ai@gmail.com</a>

---

# Pony — Privacy Policy {#en}

**Last updated: 31 October 2026**

Pony is a Japanese and English learning app built by **Roma Tech LLC**. This
policy describes what the app collects, what it does not, and why. The iOS and
Android versions differ; both are covered below.

**Who is responsible for your data.** For the processing described in this
policy, **Roma Tech LLC** (a U.S. company) is the data controller. We have not
appointed a data protection officer; any privacy question can be sent to the
email address at the end of this page.

**About "anonymous".** We do not know who you are: the app requires no sign-up
and collects no email address, phone number, or advertising identifier.
However, the app uses an identifier generated randomly on your device to link
the usage records of the same installation. Under the standards of the EU
General Data Protection Regulation (GDPR) and similar laws, such
**pseudonymous** data may still be personal data, so this policy treats it as
personal data and explains below the legal bases, retention periods, and your
rights.

## What we do not collect

- **No email address, no phone number.** The app has no sign-up, and signing
  in is **optional** (Sign in with Apple, on iOS). Even when you do sign in,
  the only thing we ask Apple for is your **name** — never your email address
  or phone number. Where that name goes is described in "Signing in
  (optional)" below.
- **No cross-app or cross-site tracking.** No advertising SDKs, no data
  brokers, no targeted advertising. iOS shows no App Tracking Transparency
  prompt because there is nothing to track.
- **No persistent device identifiers for tracking.** We do not use the
  advertising identifier (IDFA / GAID), the Android ID, the IMEI, or any
  hardware serial number. On Android, Google Play Integrity is prepared in
  advance when the app starts, and processes app, licensing, and
  device-attestation information when you submit a report, purchase, or restore
  a purchase, to verify that the request comes from a genuine installation, as
  described below; it is not used for ads or user tracking.
- **No text you type (with two exceptions when you report, below).** Anything
  you write in the "learning goal" field is **never sent to us**: it is stored
  on your device and may sync with your own iCloud or Google backup (see "Your
  learning progress"), which we cannot read. The exceptions apply only when you
  choose to submit a card report: the note you may **voluntarily** attach, and
  any answer text visible on screen at that moment, which appears in the
  screenshot (see "Usage analytics"). Apart from those, the diagnostics attached to a report
  contain no text you typed.
- **We do not receive or store recordings.** On iOS, if the offline speech pack
  for that language is not installed on your iPhone or iPad, the recording is
  sent to Apple's speech recognition service; see
  "[Pronunciation practice](#pronunciation-practice)" below.

## What we do collect

### Usage analytics

To improve the course, the app sends learning-activity events, including: app
opens; lessons started, finished, and abandoned; cards shown; whether each
practice item was answered correctly and how long it took; skipped speaking
items; review sessions; streaks; kana warm-ups and use of English cards;
results of the placement test, chapter tests, and test-outs; the goal, level,
and "how did you hear about Pony" option chosen during onboarding (not any text
you write yourself — only whether you wrote any); paywall impressions, the plan
selected, and purchase outcomes; and — if you sign in — a single "signed in"
count, which records only that it happened, with no name and nothing that
identifies you.

On iOS the app also sends a performance event when the interface stalls:
where the stall happened (typing, answer checking, the report dialog), how
many times, and the longest duration. Nothing is sent when nothing stalls.

When pronunciation practice is unavailable, the app sends an event with the
reason, the language, and **whether a Japanese keyboard is enabled** on your
device (only "yes / no", never your list of keyboards), to diagnose
language-pack problems. On iOS, the app also sends a count event when your
iCloud key-value storage is full and progress cannot be backed up. When the app
asks the system to show a rating prompt (for example, after you finish a
chapter), it records that request (what triggered it, the chapter, and which
request it is); the prompt itself is shown and handled by Apple or Google, and
we do not learn whether or how you rated.

If the app crashes, stops responding, or is terminated by the system (including being reclaimed in the background), it sends a diagnostic summary the next time it starts: the type of problem, where in the code it happened (class and method names, or module name and offset), the app and OS versions at the time, the device model, the kind of screen you were on (Android only), and when it happened (to the hour). The app also sends launch times (on iOS, a daily distribution compiled by the system; on Android, the duration of a cold start in milliseconds). The summary is built only from these fixed technical fields. It contains nothing you typed or said, no recognition results, no learning content and no account information, and like the events above it is associated only with the random identifier described below.

When you report a card issue and choose "other", you may **voluntarily** type
a note (up to 500 characters). It is sent with the report and also as a usage
analytics event, and is used **only to improve the course content**. The copy
sent as a usage analytics event is not linked to your name, email address, or
any account. The copy sent with the report is, on iOS, linked to the
Apple-generated user record ID the report carries (see below), which is not
your Apple ID, name, or email address; on Android the report goes through our
relay and carries no such ID, and is not linked to your name, email address, or
any account. Reporting works without it.

Card reports include a **screenshot of the current card screen** (it shows
only this app's own interface and cannot capture anything outside the app; any
answer text visible on that screen at the time is included), used to diagnose
display and flow issues. Below the screenshot we append a strip of
**diagnostics**: the build number, the OS version (plus the **device model** on
Android), and the most recent session events, such as the screens you passed
through, card changes, audio playback, recording, and stall durations. It
contains **no recording, none of the text you type, and none of the text
recognized from your speech** — apart from the note you voluntarily attach and
any recognition result already shown in the screenshot itself (see
"[Pronunciation practice](#pronunciation-practice)") — because typing is
recorded as a length only, and audio as the first few characters of the course
text. The screenshot and the diagnostics themselves contain no name, email address, or
account. On iOS they are linked to the Apple-generated user record ID the report
carries (see below), which is not your Apple ID, name, or email address; on
Android they go through our relay and carry no such ID. They are used only to
diagnose issues and improve the product.

On iOS, report attachments are stored directly in **our own Apple CloudKit
container**; CloudKit automatically attaches a **user record ID** generated by
Apple to each record. It is valid only within this app's container and is not
your Apple ID, name, or email address; a report sent from iOS is therefore linked
to this ID. We can see it, but it does not tell us who you are. On Android, they are sent over HTTPS to **our dedicated relay on
Google Cloud Run**, and **Google Play Integrity** confirms the submission came
from a genuine installation — an anti-abuse step that has nothing to do with
your identity. For this verification, Google processes the request hash, app
package/version/signing certificate, Play license status for signed-in
accounts on the device, a key attestation certificate, and a device-attestation
token. Google states that this data is encrypted and deleted after a fixed
retention period; we do not use it to identify or track a person. The relay then stores the
attachment in Apple CloudKit as well. A pending Android screenshot is kept in a
no-backup area on the device and is deleted after success, permanent failure,
or seven days. For how long submitted reports are kept, see
"[Retention](#retention)". You may request deletion of a
report by emailing us with its approximate submission time and card.

Each event carries the app version, build number, install channel (official store / beta / other source), system locale, OS version, and the number of days since first install.

The system locale includes your region setting (for example, zh_CN).
Purchase-related events also carry the product ID, the displayed price
(including currency), and the purchase type; when a purchase fails, they carry
your store's **country or region code**, so we can spot payment problems in a
particular region.

Events are keyed to an identifier **generated randomly on your device** (a
random UUID, hashed before it ever leaves the device). It is not your Apple
ID, not a Google account, not any device identifier, and it is linked to no
name, email, or account — even if you use Sign in with Apple, that name stays
on your device and never reaches our analytics. **Deleting and reinstalling
the app resets it**, and data from before and after cannot be connected; on
iOS, using "Delete account" after signing in also resets it at the next
launch. Because this identifier links the usage records of one installation,
we treat these analytics as pseudonymous personal data (see the top of this
page). We cannot work out who you are from it. There is currently no separate
in-app switch to turn usage analytics off; deleting the app stops it.

### Platform differences

| | iOS | Android |
|---|---|---|
| Usage analytics | Collected | Collected |
| Pronunciation practice (microphone) | Available | Available |
| Signing in (optional, name only) | Sign in with Apple | No sign-in, local nickname only |
| Delete account | On the "Me" page after signing in (optionally also clears learning progress) | No account |
| Progress backup | iCloud when enabled by the user | Google Android Auto Backup when available |
| Report attachment route | Apple CloudKit | Google Cloud Run / Play Integrity → Apple CloudKit |
| Extra information attached to reports | CloudKit user record ID, OS version | OS version, device model |

### Processors and infrastructure

The following services process data for us, only for the purposes described
in this policy:

| Service | Location | What it does |
|---|---|---|
| **TelemetryDeck GmbH** ([telemetrydeck.com](https://telemetrydeck.com)) | Germany; per its published information, servers in Germany and the Netherlands | Receives and stores usage analytics. It is a service provider acting on our instructions; it does not use the data for its own purposes and does not sell it. According to TelemetryDeck, it does not store IP addresses. |
| **Apple** (CloudKit) | United States | Stores report attachments (screenshot, diagnostics, note), readable only by us. |
| **Google** (Google Cloud Run) | United States (us-west1 region) | Runs our Android report relay and purchase-verification service. |
| **Google** (Play Integrity, Google Play Developer API) | — | Verifies that Android requests come from a genuine installation; checks Play purchase and subscription status. |
| **GitHub** (GitHub Pages) | United States | Hosts this policy page and a public configuration file read by the iOS paywall. That request contains no user data, but GitHub sees the requesting IP address, as any website does. |

These are processors and infrastructure working for us. **We do not sell or share any data with
data brokers, and we do not use it for ad targeting.** Beyond the uses above,
we disclose data to no third party for their own use.

## Pronunciation practice

On iOS, pronunciation scoring uses Apple's speech recognition:

- If the offline speech pack for that language is already installed on your
  iPhone or iPad, recognition happens on the device and the recording does not
  leave it.
- If it is not installed, the recording of that attempt is sent to Apple's
  speech recognition service (Apple's servers) to be converted into text for
  scoring. Our servers do not receive or store these recordings or the
  recognized text. One exception: if you tap "report" on the screen that shows
  your pronunciation score, the screenshot includes the recognized text shown
  on screen (the "识别到：…" line) and is sent to us with the report (the same
  applies on Android; see "[Usage analytics](#usage-analytics)").
  Apple's handling of this data is governed by the
  [Apple Privacy Policy](https://www.apple.com/legal/privacy/).
- You can turn on "Enable Dictation" in iOS Settings › General › Keyboard and
  select that language under "Dictation Languages". Once the system has
  downloaded the offline speech pack, scoring switches back to recognition on
  the device.

On Android, pronunciation scoring happens entirely on your device. The app first uses Android's explicit **on-device speech recognizer** (Android 12 / API 31 and later). If the device has no on-device recognizer, it uses an **offline recognition model bundled with the app** (the open-source Vosk, for Japanese and English), which also runs only on the device. Neither path falls back to a generic recognizer that may use a network service. If a system speech pack is missing, the app offers a download link and the system downloads the pack.

**Recordings are never sent to our servers** and are not stored by us;
usage analytics receive only a score (0–100), the language and which card it was. The
real-time highlight that turns the target text green as you read it is
likewise computed entirely on your device; nothing is uploaded.
The system asks for microphone permission; you may decline
or revoke it at any time in Settings, and nothing else in the app is affected.

## Signing in (optional)

Sign in with Apple is **optional** and exists on iOS only. The one thing it
does is put a name on your "Me" page. We ask Apple for your **name** only, not
your email address, and the name we receive is **stored on your own device and
never uploaded** — it is never sent to any server of ours, and it is not part
of Pony's iCloud sync, so it does not sync to your other devices (it may,
however, be included in a full device backup). Apple also returns an anonymous user ID that is **specific to Pony**,
used to check whether the authorisation is still valid; like the name, it never
leaves your device. You can sign out inside the app at any time; signing out
deletes both from the device and leaves your progress untouched.

After signing in, you can also **delete your account** on the "Me" page: this
deletes the name and the Apple user ID from the device and resets the analytics
identifier at the next launch; you can choose to also clear your learning
progress on the device and in your iCloud.

**Nothing requires you to sign in**: lessons, review, pronunciation practice,
and purchases — including Restore Purchases — all work exactly the same
signed out (purchases are handled by the App Store, independently of whether
you are signed in to Pony).

Android has no sign-in at all; it only lets you set a nickname that stays
**on the device** (it is never sent to us, but it is included in the Android
backup).

## Your learning progress

Progress, review scheduling, and XP are stored **on your own device**.

On iOS, if you use iCloud, progress — including your onboarding answers and
the text you wrote for your learning goal — is backed up to **your own iCloud
account**. On Android, when the device, Google services, and your system
settings permit, Android Auto Backup stores progress, your nickname, and your
onboarding answers in your Google account
and may restore it after reinstalling or changing devices. Apple and Google
manage these platform backups; we cannot read them. Android's random analytics
identifier is explicitly excluded from backup, so it is still reset on
reinstall.

## Purchases and subscriptions

Membership purchases are processed by the Apple App Store or Google Play. We
do not receive or store your card number, billing address, or store-account
credentials. The app receives product, price, purchase, and subscription
status from the store so it can show localized prices, unlock content, restore
purchases, and manage subscriptions. Usage analytics record product ID,
display price, purchase kind, and outcome (with the store's country or region
code when a purchase fails) to help us detect payment-flow problems.

On Android, when you purchase or restore a purchase, and when the app checks
existing purchases at launch or on returning to the foreground, the app sends
the product ID, product type, Google Play purchaseToken, app build number, and a
Play Integrity attestation
over HTTPS to our dedicated service on Google Cloud Run. That service calls the
Google Play Developer API to verify the current purchase or subscription state
and acknowledge completed transactions, then returns only entitlement status to
the app. Roma Tech does not log or persist the purchaseToken, order details, or
store-account information; the token is processed only in memory and encrypted
transit for this live verification. Google manages Play transaction records
under its own policies.

## Purposes and legal bases

If you are in the European Economic Area (EEA), the United Kingdom, or
Switzerland, we process your data on the following bases (Article 6 GDPR and
the corresponding UK and Swiss provisions):

| Processing | Purpose | Legal basis |
|---|---|---|
| Usage analytics (including stall and crash diagnostics) | Understanding where the course is too hard or broken; detecting crashes and payment-flow failures | Our **legitimate interest** in improving the course and keeping the app working (Art. 6(1)(f)) |
| Card reports (screenshot, diagnostics, note) | Investigating the problem you reported | Our **legitimate interest** in investigating and fixing problems (Art. 6(1)(f)); you may object at any time or ask us to delete a report |
| Android purchase verification | Delivering the membership you bought | **Performance of a contract** (Art. 6(1)(b)) |
| Play Integrity verification | Preventing forged uploads and piracy | Our **legitimate interest** in keeping the service secure (Art. 6(1)(f)) |
| Server request logs | Security and troubleshooting | Our **legitimate interest** in keeping the service secure (Art. 6(1)(f)) |

The name from Sign in with Apple, the local nickname, your learning progress,
and platform backups are never sent to us and are not processed by us.

Apart from usage analytics, providing data is voluntary: you can learn without
reporting, signing in, or granting microphone access. We do not carry out
automated decision-making that has legal or similarly significant effects on
you; review scheduling and the placement test only decide which card is shown
next.

## Retention

| Data | How long it is kept |
|---|---|
| Usage analytics (including diagnostic summaries) | Kept by TelemetryDeck. The service currently has no fixed deletion schedule; according to its published information, it expects to delete such data after 7 to 10 years but does not guarantee this. |
| Card reports (screenshot, diagnostics, note) | Up to 24 months from submission, then deleted; you can ask us to delete a report earlier at any time. |
| Pending screenshots on an Android device | Deleted after a successful upload, a permanent failure, or seven days. |
| Server request logs (Google Cloud Run; may include IP addresses) | 30 days (the Google Cloud platform default). |
| purchaseToken in Android purchase verification | Not stored; processed only in memory for that verification. |
| Data stored on your device | Until you delete the app; platform backups are kept according to your Apple or Google account settings. |

## International transfers

Roma Tech LLC is located in the United States. Data you provide to us directly
through the app is processed by us in the United States; under the European
Data Protection Board's Guidelines 05/2021, this in itself is not a "transfer"
within the meaning of Chapter V GDPR, but we still handle that data in line
with this policy and the GDPR. Among the services that process data for us:

- **Google** (Cloud Run, us-west1 region in the United States): Google LLC is
  certified under the EU-U.S. Data Privacy Framework, and its cloud data
  processing terms also provide for the EU Standard Contractual Clauses;
- **Apple** (CloudKit, United States): according to Apple, its international
  transfers of personal data from the EEA, the United Kingdom, and Switzerland
  are governed by Standard Contractual Clauses;
- **TelemetryDeck** processes usage analytics within the EU (Germany and the
  Netherlands).

You can ask for information about these safeguards at the email address below.

## Children

This app is intended for adult learners. It is not directed at children under
13 and we do not knowingly collect personal information from children. In the
EEA, the age at which a person can consent to digital services on their own
ranges from 13 to 16 depending on the country. If you are in the EEA and below
the age set by your country, please use this app only with the consent of a
parent or guardian. If you believe we have received a child's data, contact us
and we will delete it.

## Your rights

Pony has no server-side account, and we do not know your name, email address,
or phone number (the name from Sign in with Apple exists only on your own
device; we never receive it).

Deleting the app stops new collection and removes its local copy, but a
platform backup may remain according to your Apple or Google account settings
and can later be restored. You can manage those backups in the corresponding
platform settings. Reinstalling generates a new analytics identifier. To request deletion of a report you submitted, email us with its
approximate submission time and card — precisely because there is no account,
those clues are what let us locate the record.

**If you are in the EEA, the United Kingdom, or Switzerland**, you have the
following rights under the law:

- **Access**: to know whether we process your data and to obtain a copy;
- **Rectification**: to have inaccurate data corrected;
- **Erasure**: to have your data deleted;
- **Restriction**: to have processing paused in certain circumstances;
- **Data portability**: where the law provides for it, to receive the data you
  gave us in a commonly used electronic format;
- **Objection**: to object to processing based on our legitimate interests;
- **Complaint**: to lodge a complaint with the data protection supervisory
  authority where you live or work, or where you believe an infringement
  occurred (EEA authorities are listed on the
  [EDPB members page](https://www.edpb.europa.eu/about-edpb/about-edpb/members_en);
  in the United Kingdom this is the ICO, and in Switzerland the FDPIC).

To exercise these rights, email us at the address below. Because we do not know
who you are, in most cases we cannot link analytics data to you personally
(Article 11 GDPR); if you can give us information that helps us find the
relevant records — for example, the approximate time and card of a report — we
will act on it. If we truly cannot link any data to you, we will tell you so.
We will reply within one month of receiving your request.

If you have questions about how data is handled, contact us at the address
below.

## Changes

If this policy changes, we will update the date at the top of this page.
Material changes to the app's data behaviour will also be reflected in the App
Store and Google Play data disclosures.

This policy is available in Chinese, English, and Japanese; if the versions
differ, the English version prevails.

## Contact

**Roma Tech LLC** (data controller)
Email: <a href="mailto:roma.tech.ai@gmail.com">roma.tech.ai@gmail.com</a>

---

# Pony（小马）— プライバシーポリシー {#ja}

**最終更新日：2026 年 10 月 31 日**

Pony（小马）は、**Roma Tech LLC** が開発・提供する日本語および英語の学習
アプリです。本ポリシーでは、本アプリが何を取得し、何を取得しないか、
またその理由を説明します。iOS 版と Android 版で挙動が異なる点は、それぞれ
明記します。

**お客様のデータに責任を負う者。** 本ポリシーに記載する処理について、
**Roma Tech LLC**（米国の会社）がデータ管理者（コントローラー）です。当社は
データ保護責任者（DPO）を選任していません。プライバシーに関するご質問は、本ページ
末尾のメールアドレスまでお寄せください。

**「匿名」について。** 当社はお客様が誰であるかを知りません。本アプリは会員登録を
求めず、メールアドレス、電話番号、広告識別子を取得しません。ただし、お使いの端末上で
ランダムに生成した識別子を使って、同じインストールでの利用記録を結び付けています。
EU 一般データ保護規則（GDPR）などの基準では、このような**仮名化**されたデータも
個人データに当たる場合があるため、本ポリシーではこれを個人データとして扱い、処理の
法的根拠、保存期間、お客様の権利を以下で説明します。

## 取得しないもの

- **メールアドレスも電話番号も取得しません。** 会員登録は不要で、サインインは
  **任意**です（iOS の「Apple でサインイン」）。サインインされた場合でも、
  Apple に求めるのは**氏名のみ**で、メールアドレスや電話番号は要求も保存も
  しません。氏名の取り扱いは下記「サインイン（任意）」をご覧ください。
- **アプリ間・サイト間のトラッキングは行いません。** 広告 SDK やデータ
  ブローカーは利用せず、ターゲティング広告も配信しません。iOS で
  App Tracking Transparency の許可ダイアログが表示されないのは、
  追跡する対象がそもそも存在しないためです。
- **追跡のための永続的な端末識別子は使用しません。** 広告識別子（IDFA / GAID）、
  Android ID、IMEI、ハードウェアシリアル番号は使用しません。Android では、
  Google Play Integrity をアプリの起動時にあらかじめ準備し、不具合報告の送信、
  購入、購入の復元の際にアプリ、ライセンス、端末証明情報を処理して、正規の
  インストールからの要求であることを検証します。広告や利用者追跡には使用しません。
- **入力されたテキストは送信しません（不具合報告時の 2 つの例外を除く）。**
  「学習の目的」欄に記入された内容が**当社に送信されることはありません**。
  内容は端末内に保存され、お客様ご自身の iCloud または Google のバックアップと
  同期される場合がありますが（「学習の進捗」を参照）、当社は読み取れません。例外は、お客様ご自身が不具合報告を送信
  される場合の 2 点のみです。カードの不具合報告で「その他」を選択した際に
  **任意で**記入いただく説明文と、その時点でスクリーンショットに表示されて
  いる解答文字です（「利用統計」を参照）。これら以外に、報告へ添付される
  診断情報に入力されたテキストが含まれることはありません。
- **録音データを当社が受け取ったり保存したりすることはありません。** iOS で、
  お使いの iPhone または iPad にその言語のオフライン用音声データが入っていない
  場合は、録音が Apple の音声認識サービスで認識されます。下記「[発音練習](#発音練習)」
  をご覧ください。

## 取得するもの

### 利用統計

教材を改善するため、学習に関する操作イベントを送信します。具体的には、
アプリの起動、レッスンの開始・完了・途中終了、カードの表示、各設問の正誤と解答
所要時間、スキップされた発音練習、復習の完了、連続学習日数、五十音ウォームアップ
と英語カードの利用状況、レベル判定テスト・章末テスト・飛び級テストの結果、初回
設定で選択された学習目的・レベル・「Pony を知ったきっかけ」（お客様が自由に記入
した内容は含まず、記入の有無のみ）、有料プラン画面の表示、選択されたプランと
購入結果、そしてサインインされた場合は「サインインした」という記録です。最後のものは
その事実が起きたことだけを示し、氏名など身元に関わる情報は一切含みません。

また iOS 版では、画面に引っかかり（ハング）が生じた際に性能イベントを送信
します。内容は、どの場面で起きたか（入力中、正誤判定、不具合報告ダイアログ）、
回数、最長の所要時間です。引っかかりがなければ何も送信しません。

発音練習が利用できない場合は、その理由、対象の言語、およびお使いの端末で
**日本語キーボードが有効かどうか**（「はい / いいえ」のみで、キーボードの一覧は
送信しません）を含むイベントを送信し、音声データの問題の調査に使用します。
iOS 版では、iCloud のキー値ストレージが一杯で進捗をバックアップできない場合にも、
件数を示すイベントを送信します。章を修了したときなどにシステムの評価ダイアログの
表示を要求した場合は、その要求（きっかけ、章、何回目の要求か）を記録します。
評価ダイアログ自体は Apple または Google が表示・処理するため、お客様が評価した
かどうかや評価の内容を当社が知ることはありません。

アプリがクラッシュした場合、応答しなくなった場合、またはシステムによって終了された場合（バックグラウンドでの回収を含みます）、次回の起動時に診断の要約を送信します。内容は、問題の種類、発生したコード上の位置（クラス名とメソッド名、またはモジュール名とオフセット）、発生時のアプリと OS のバージョン、端末の機種、そのとき表示していた画面の種類（Android のみ）、発生日時（1 時間単位）です。あわせて起動にかかった時間も送信します（iOS ではシステムが日ごとに集計した分布、Android ではコールドスタート 1 回分の所要時間〔ミリ秒〕）。要約はこれらの決まった技術項目だけから作られ、お客様が入力・発話した内容、認識結果、学習内容、アカウント情報は一切含みません。上記のイベントと同様、下記のランダムな識別子にのみ関連付けられます。

カードの不具合報告で「その他」を選択した場合、**任意で**説明文
（500 文字以内）を記入できます。この文章は報告と一緒に送信されるほか、
利用統計のイベントとしても送信され、**教材の改善のみに使用**されます。利用統計の
イベントとして送信される分は、氏名、メールアドレス、アカウントとは結び付きません。
報告と一緒に送信される分は、iOS では報告に付随する Apple 生成のユーザーレコード ID
（下記。Apple ID、氏名、メールアドレスではありません）と結び付き、Android では中継
サービス経由で送信されるためこの ID は付随せず、氏名、メールアドレス、アカウントとは
結び付きません。記入しなくても報告は送信できます。

不具合報告には、表示や操作上の問題を調査するため**その時点のカード画面の
スクリーンショット**が添付されます。撮影されるのは本アプリ自身の画面のみで、
アプリ外の内容が写ることは技術的にあり得ません（その時点で表示されている
解答文字は含まれます）。スクリーンショットの下部には**診断情報**（ビルド番号、
OS のバージョン〔Android 版ではさらに**端末の機種**〕、および直近のセッションの
記録：経過した画面、カードの切り替え、音声の再生、録音、引っかかりの所要時間
など）が併記されます。ここに**録音データそのもの、入力されたテキスト、発話から
認識されたテキストが含まれることはありません**（任意で記入いただく報告文と、
スクリーンショットの画面にもともと表示されている認識結果は除きます。
「[発音練習](#発音練習)」を参照）。入力については文字数のみ、音声については
教材のテキストの冒頭数文字のみを記録します。スクリーンショットと診断情報そのものには
氏名、メールアドレス、アカウントは含まれません。iOS ではこれらは報告に付随する
Apple 生成のユーザーレコード ID（下記。Apple ID、氏名、メールアドレスではありません）と
結び付き、Android では中継サービス経由で送信されるためこの ID は付随しません。
問題の修正と製品改善以外の目的には使用しません。

iOS では報告の添付データを**当社自身の Apple CloudKit コンテナ**に直接保存
します。その際 CloudKit は、Apple が生成した**ユーザーレコード ID** を各記録に
自動的に付与します。これは本アプリのコンテナ内でのみ有効な番号で、Apple ID、
氏名、メールアドレスではありません。そのため iOS からの報告はこの番号と結び付きます。当社はこの番号を見ることができますが、
そこからお客様が誰であるかを知ることはできません。Android ではまず HTTPS で**当社が Google Cloud Run 上に用意した専用
中継サービス**へ送信し、**Google Play Integrity** によって正規のインストール
からの送信であることを確認します。これは偽装された送信を防ぐための手順であり、
お客様の身元とは関係ありません。この検証のため、Google はリクエストハッシュ、
アプリのパッケージ名・バージョン・署名証明書、端末上のログイン済みアカウントに
関する Play ライセンス状態、鍵証明書、端末証明トークンを処理します。Google に
よれば、これらのデータは暗号化され、所定の保持期間後に削除されます。当社が個人の
識別や追跡に使用することはありません。検証後、添付データは同じく Apple CloudKit に保存されます。Android
端末上の送信待ち画像はバックアップ対象外の領域に置かれ、送信成功、恒久的失敗、
または 7 日経過後に削除されます。送信済みの報告の保存期間は
「[保存期間](#保存期間)」をご覧ください。おおよその送信時刻とカードを添えて下記メールへ
ご連絡いただければ、該当報告の削除を依頼できます。

各イベントには、アプリのバージョン、ビルド番号、インストール経路（公式ストア / ベータ版 / その他の入手元）、システムの言語設定、OS のバージョン、初回インストールからの経過日数が付随します。

このうち「システムの言語設定」には地域の設定（例：zh_CN）が含まれます。購入に
関するイベントには、商品 ID、表示価格（通貨を含む）、購入種別も付随し、購入に
失敗した場合はお使いのストアの**国または地域のコード**も付随します。特定の地域
での決済の不具合を見つけるためです。

これらのイベントは、**お使いの端末上でランダムに生成された識別子**に
紐付きます（ランダムな UUID を、端末から送信する前にハッシュ化したもの）。
これは Apple ID でも Google アカウントでも端末識別子でもなく、氏名・
メールアドレス・アカウントのいずれとも結び付きません。「Apple でサインイン」
をご利用の場合でも、取得した氏名は端末内に留まり、利用統計に含まれることは
ありません。**アプリを削除して再インストールすると識別子はリセットされ**、
前後のデータを関連付けることはできません。iOS では、サインイン後にアカウントを
削除した場合も、次回の起動時にリセットされます。この識別子は同じインストールでの
利用記録を結び付けるため、当社はこれらの統計を仮名化された個人データとして扱います
（本ページ冒頭を参照）。当社がこの識別子からお客様が誰であるかを割り出すことは
できません。現在、アプリ内に利用統計だけをオフにする設定はありません。アプリを
削除すると送信は停止します。

### プラットフォームによる違い

| | iOS | Android |
|---|---|---|
| 利用統計 | 取得します | 取得します |
| 発音練習（マイク） | 利用できます | 利用できます |
| サインイン（任意・氏名のみ） | 「Apple でサインイン」 | ありません（端末内の表示名のみ） |
| アカウントの削除 | サインイン後に「マイページ」から削除可能（学習の進捗も消去するかを選択可能） | アカウントなし |
| 学習進捗のバックアップ | 有効な場合は iCloud | 利用可能な場合は Google Android Auto Backup |
| 報告添付の経路 | Apple CloudKit | Google Cloud Run / Play Integrity → Apple CloudKit |
| 報告に付随する追加情報 | CloudKit のユーザーレコード ID、OS のバージョン | OS のバージョン、端末の機種 |

### 処理の委託先とインフラ

以下のサービスが当社のためにデータを処理します。用途は本ポリシーに記載した目的に
限られます。

| 委託先 | 所在地 | 内容 |
|---|---|---|
| **TelemetryDeck GmbH**（[telemetrydeck.com](https://telemetrydeck.com)） | ドイツ（同社の公表によれば、サーバーはドイツとオランダ） | 利用統計を受け取り、保存します。当社の指示に基づき当社に代わって処理を行うサービス提供者であり、自社の目的でデータを利用したり、データを販売したりすることはありません。同社によれば、IP アドレスは保存しません。 |
| **Apple**（CloudKit） | 米国 | 不具合報告の添付データ（スクリーンショット、診断情報、説明文）を保存します。閲覧できるのは当社のみです。 |
| **Google**（Google Cloud Run） | 米国（us-west1 リージョン） | Android 版の不具合報告の中継サービスと購入検証サービスを運用します。 |
| **Google**（Play Integrity、Google Play Developer API） | — | Android の要求が正規のインストールからのものであることを検証し、Play の購入・サブスクリプション状態を確認します。 |
| **GitHub**（GitHub Pages） | 米国 | 本ポリシーのページと、iOS 版の有料プラン画面が読み込む公開設定ファイルをホストします。この通信に利用者データは含まれませんが、一般的なウェブサイトと同様に、GitHub は要求元の IP アドレスを受け取ります。 |

以上はいずれも当社のために処理を行う委託先およびインフラです。**データブローカーへの
販売や提供は行わず、広告のターゲティングにも使用しません。** 上記の用途
以外に、第三者が自己目的で利用できる形でデータを開示することはありません。

## 発音練習

発音の採点には、iOS では Apple の音声認識を使用します。

- お使いの iPhone または iPad にその言語のオフライン用音声データがすでに入って
  いる場合、認識は端末内で行われ、録音が端末の外に出ることはありません。
- 入っていない場合は、その回の録音が Apple の音声認識サービス（Apple のサーバー）
  でテキストに変換され、採点に使われます。当社のサーバーがこれらの録音や認識された
  テキストを受け取ったり保存したりすることはありません。ただし例外として、発音の
  スコアが表示されている画面でお客様が「不具合報告」を送信された場合、その
  スクリーンショットには画面に表示されている認識テキスト（「识别到：…」の行）が
  含まれ、報告と一緒に当社へ送信されます（Android 版も同様です。
  「[利用統計](#利用統計)」を参照）。Apple によるこれらのデータの
  取り扱いには、[Apple のプライバシーポリシー](https://www.apple.com/jp/legal/privacy/)
  が適用されます。
- iOS の「設定」›「一般」›「キーボード」で「音声入力」をオンにし、「音声入力言語」
  でその言語を選択すると、システムがオフライン用音声データをダウンロードします。
  ダウンロード後は、端末内での認識に戻ります。

Android では、発音の採点はすべてお使いの端末内で行われます。まず Android が明示的に提供する**端末内音声認識**（Android 12 / API 31 以降）を使用し、端末内認識がない端末では、**アプリに同梱したオフライン認識モデル**（オープンソースの Vosk、日本語と英語）を使用します。これも端末内でのみ動作します。どちらの場合も、ネットワークを使う可能性のある汎用音声認識へ切り替わることはありません。システムの音声データが足りない場合はダウンロードの案内を表示し、音声データはシステムがダウンロードします。

**録音データが当社のサーバーへ送信されることはなく**、当社が保存することも
ありません。当社が受け取るのはスコア
（0〜100）、認識に使用した言語、およびどのカードかのみです。読み上げに合わせて対象の文字が
緑色に変わるリアルタイム表示も、すべて端末内で計算しており、送信は
一切発生しません。マイクの利用許可は OS のダイアログでお伺いします。
いつでも拒否でき、設定からの取り消しも可能です。拒否された場合でも、
その他の機能には一切影響ありません。

## サインイン（任意）

「Apple でサインイン」は iOS 版のみの**任意**の機能で、その役割は「マイ
ページ」に名前を表示することだけです。Apple に求めるのは**氏名のみ**で、
メールアドレスは要求しません。取得した氏名は**お使いの端末内にのみ保存され
ます**。当社のいずれのサーバーにも送信されることはなく、
Pony の iCloud 同期の対象にも含まれないため、お客様の他の端末に同期されることも
ありません（ただし、端末全体のバックアップには含まれる場合があります）。サインイン時には、**Pony 専用**の匿名のユーザー
識別子も Apple から渡されます。これは認証がまだ有効かどうかを確認するために
のみ使用し、氏名と同様に端末外へ送信されることはありません。アプリ内でいつ
でもサインアウトでき、サインアウトすると氏名と識別子はいずれも端末から削除
されます（学習の進捗はそのまま残ります）。

サインイン後は、「マイページ」から**アカウントを削除**することもできます。削除すると、
氏名と Apple のユーザー識別子が端末から削除され、次回の起動時に利用統計の識別子が
リセットされます。あわせて、端末内とお客様の iCloud 上の学習の進捗を消去するか
どうかも選択できます。

**サインインしなくても、機能に一切の違いはありません。** レッスン、復習、
発音練習、購入および購入の復元は、サインインの有無にかかわらず同じように
ご利用いただけます（購入は App Store が処理するため、Pony へのサインインとは
無関係です）。

Android 版にサインインの仕組みはなく、**端末内に保存される**表示名を設定
できるのみです（表示名が当社に送信されることはありませんが、Android の
バックアップには含まれます）。

## 学習の進捗

学習の進捗、復習スケジュール、経験値は**お使いの端末内**に保存されます。

iOS 版で iCloud をご利用の場合、進捗（初回設定の回答や、学習の目的として記入
された内容を含みます）は**お客様ご自身の iCloud アカウント**にバックアップ
されます。これはお客様のアカウントであり、当社が読み取ることは
できません。

Android 版では、端末、Google サービス、お客様のシステム設定が許可する場合、
Android Auto Backup により Google アカウントへ進捗、表示名、初回設定の回答が
バックアップされ、再インストール
や機種変更時に復元されることがあります。これらのバックアップは Apple または
Google が管理し、当社は読み取れません。Android の利用統計用ランダム識別子は
バックアップ対象から明示的に除外されるため、再インストール時にリセットされます。

## 購入とサブスクリプション

会員購入は Apple App Store または Google Play が処理します。当社はカード番号、
請求先住所、ストアアカウントの認証情報を受け取らず、保存もしません。アプリは
ストアから商品、価格、購入・サブスクリプション状態を受け取り、現地通貨価格の表示、
コンテンツの解除、購入の復元、サブスクリプション管理に使用します。利用統計には、
決済フローの不具合を確認するため、商品 ID、表示価格、購入種別、結果（購入に失敗
した場合はストアの国または地域のコード）を記録します。

Android 版で購入または購入の復元を行う際、およびアプリの起動時やフォアグラウンド
に戻った際に既存の購入を確認する際、商品 ID、商品の種類、Google Play の
purchaseToken、アプリのビルド番号、Play Integrity の証明を HTTPS で Google Cloud Run 上の当社専用
サービスへ送信します。このサービスは Google Play Developer API を呼び出して現在の
購入・サブスクリプション状態を検証し、完了した取引を確認したうえで、権利状態だけを
アプリへ返します。Roma Tech は purchaseToken、注文情報、ストアアカウント情報を
ログに記録せず、永続保存もしません。token はこのリアルタイム検証に必要なメモリ内処理
と暗号化通信でのみ扱います。Google は独自のポリシーに従って Play の取引記録を管理します。

## 処理の目的と法的根拠

欧州経済領域（EEA）、英国またはスイスにお住まいの場合、当社は以下の根拠に基づいて
お客様のデータを処理します（GDPR 第 6 条および英国・スイスの対応する規定）。

| 処理 | 目的 | 法的根拠 |
|---|---|---|
| 利用統計（引っかかりとクラッシュの診断を含む） | 教材の難しすぎる箇所や不具合の把握、クラッシュや決済フローの障害の検出 | 教材を改善し、アプリを正常に動作させるという当社の**正当な利益**（第 6 条 1 項 (f)） |
| 不具合報告（スクリーンショット、診断情報、説明文） | お客様が報告された問題の調査 | 問題を調査・修正するという当社の**正当な利益**（第 6 条 1 項 (f)）。いつでも異議を述べ、または報告の削除を求めることができます |
| Android の購入検証 | ご購入いただいた会員権利の提供 | **契約の履行**（第 6 条 1 項 (b)） |
| Play Integrity による検証 | 偽装された送信や不正コピーの防止 | サービスの安全を守るという当社の**正当な利益**（第 6 条 1 項 (f)） |
| サーバーのリクエストログ | セキュリティと障害調査 | サービスの安全を守るという当社の**正当な利益**（第 6 条 1 項 (f)） |

「Apple でサインイン」で取得した氏名、端末内の表示名、学習の進捗、プラットフォームの
バックアップは当社に送信されず、当社による処理の対象ではありません。

利用統計を除き、データの提供は任意です。不具合報告、サインイン、マイクの許可を
行わなくても学習には影響しません。当社は、お客様に法的効果またはそれと同様の重大な
影響を及ぼす自動化された意思決定を行いません。復習のスケジュールとレベル判定テストは、
次にどのカードを表示するかを決めるだけです。

## 保存期間

| データ | 保存期間 |
|---|---|
| 利用統計（診断の要約を含む） | TelemetryDeck が保存します。同社には現在、決まった削除期限がなく、同社の公表によれば 7〜10 年後に削除する見込みですが、保証はされていません。 |
| 不具合報告（スクリーンショット、診断情報、説明文） | 送信から最長 24 か月で削除します。それより前の削除もいつでもご依頼いただけます。 |
| Android 端末上の送信待ちスクリーンショット | 送信成功、恒久的失敗、または 7 日経過後に削除します。 |
| サーバーのリクエストログ（Google Cloud Run。IP アドレスを含む場合があります） | 30 日（Google Cloud の標準設定）。 |
| Android の購入検証における purchaseToken | 保存しません。検証に必要なメモリ内でのみ処理します。 |
| お使いの端末に保存されたデータ | アプリを削除するまで。プラットフォームのバックアップは、お客様の Apple または Google アカウントの設定に従って保持されます。 |

## 国外への移転

Roma Tech LLC は米国に所在しています。お客様がアプリを通じて当社に直接提供された
データは、米国で当社が処理します。欧州データ保護会議（EDPB）のガイドライン 05/2021
によれば、これ自体は GDPR 第 5 章にいう「移転」には当たりませんが、当社はこれらの
データも本ポリシーおよび GDPR に従って取り扱います。当社のためにデータを処理する
サービスについては、次のとおりです。

- **Google**（Cloud Run、米国 us-west1 リージョン）：Google LLC は EU-米国データ
  プライバシーフレームワークの認証を受けており、同社のクラウドのデータ処理条項には
  EU 標準契約条項も定められています。
- **Apple**（CloudKit、米国）：Apple によれば、EEA、英国、スイスで取得された個人
  データの国際移転には標準契約条項が適用されます。
- **TelemetryDeck** は EU 域内（ドイツおよびオランダ）で利用統計を処理します。

これらの保護措置に関する説明は、下記メールアドレスまでご請求いただけます。

## お子様について

本アプリは成人の学習者を対象としており、13 歳未満のお子様を対象とした
サービスではありません。お子様の個人情報を意図的に取得することはありません。
EEA では、本人だけでデジタルサービスに同意できる年齢が国により 13〜16 歳と
異なります。EEA にお住まいで、お住まいの国の定める年齢に達していない場合は、
保護者の同意を得たうえで本アプリをご利用ください。当社がお子様のデータを受け
取ったとお考えの場合は、ご連絡いただければ削除します。

## お客様の権利

Pony にサーバー側のアカウントはなく、当社はお客様の氏名、メールアドレス、電話
番号を知りません（「Apple でサインイン」で取得した氏名もお使いの端末内にのみ存在
し、当社が受け取ることはありません）。

アプリを削除すると新たな取得は停止し、端末内のコピーは削除されます。ただし、
Apple または Google アカウントの設定に従いプラットフォームのバックアップが残り、
後で復元される場合があります。バックアップは各プラットフォームの設定で管理できます。
再インストール時には新しい利用統計の識別子が生成されます。送信した不具合報告の削除を
希望する場合は、おおよその送信時刻とカードを添えて下記メールへご連絡ください。
アカウントがないからこそ、記録の特定にはこれらの手掛かりが必要になります。

**EEA、英国またはスイスにお住まいの場合**、お客様には法律に基づき次の権利が
あります。

- **アクセス**：当社がお客様のデータを処理しているかを確認し、その写しを受け取る権利
- **訂正**：不正確なデータの訂正を求める権利
- **消去**：データの削除を求める権利
- **処理の制限**：一定の場合に処理の一時停止を求める権利
- **データポータビリティ**：法律が定める場合に、当社に提供したデータを一般的な電子
  形式で受け取る権利
- **異議**：当社の正当な利益に基づく処理に異議を述べる権利
- **苦情の申立て**：お住まい、勤務先、または侵害があったと考える場所のデータ保護
  監督機関に苦情を申し立てる権利（EEA 各国の監督機関は
  [EDPB のメンバー一覧](https://www.edpb.europa.eu/about-edpb/about-edpb/members_en)
  をご覧ください。英国では ICO、スイスでは連邦データ保護・情報コミッショナー
  〔FDPIC〕です）

これらの権利を行使される場合は、下記メールアドレスまでご連絡ください。当社は
お客様が誰であるかを知らないため、多くの場合、利用統計のデータをお客様ご本人と
結び付けることができません（GDPR 第 11 条）。記録の特定に役立つ情報（例：不具合
報告のおおよその送信時刻とカード）をご提供いただければ、それに基づいて対応します。
どうしても結び付けられない場合は、その旨をお伝えします。ご請求を受け取ってから
1 か月以内にお返事します。

データの取り扱いについてご不明な点がありましたら、下記の連絡先までお問い
合わせください。

## 変更について

本ポリシーを変更した場合は、本ページ冒頭の日付を更新します。データの
取り扱いに関する重要な変更は、App Store および Google Play のデータ開示にも
反映します。

本ポリシーは中国語、英語、日本語で提供しています。各言語版の内容に相違がある場合は、
英語版が優先します。

## お問い合わせ

**Roma Tech LLC**（データ管理者）
メール：<a href="mailto:roma.tech.ai@gmail.com">roma.tech.ai@gmail.com</a>
