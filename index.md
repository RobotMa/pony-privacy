---
title: 小马 Pony — 隐私政策 / Privacy Policy / プライバシーポリシー
---

[中文](#zh) · [English](#en) · [日本語](#ja)

# 小马 Pony · 隐私政策 {#zh}

**最后更新：2026 年 8 月 24 日**

小马（Pony）是一款日语与英语学习应用，由 **Roma Tech LLC** 开发。
本政策说明这款应用收集什么、不收集什么，以及为什么。iOS 版与 Android 版的
行为并不完全相同，下面分别列出。

## 我们不收集的东西

- **没有账号。** 应用不要求注册、不要求登录，我们没有你的姓名、邮箱或电话。
- **不做跨应用/跨网站追踪。** 没有广告 SDK，没有数据经纪商，不投放定向广告。
  iOS 上不会弹出 App Tracking Transparency 授权框，因为我们没有可追踪的东西。
- **不使用持久设备标识符做追踪。** 不使用广告标识符（IDFA / GAID）、Android ID、
  IMEI 或硬件序列号。Android 用户主动提交报错时，Google Play Integrity 会处理
  应用、许可和设备证明信息以验证请求；该用途见下文，不用于广告或用户追踪。
- **不上传你输入的文字（报错时的明确例外见下）。** 你在「学习目标」里手写的
  内容**只保存在你的设备上**，不会离开设备。报错时的例外包括：选择「其他」后
  你**自愿填写**的说明，以及你主动提交报错时截图上当时可见的答题文字。
- **不上传录音。** 见下方「跟读发音」一节。

## 我们收集的东西

### 匿名使用统计

为了改进课程，应用会发送学习行为事件：应用启动、课程开始与完成、
每道练习题的对错与作答耗时、复习完成、引导流程中选择的学习目标与语言水平、
以及付费页的展示与购买结果。

你在卡片上点「报错」并选择「其他」时，可以**自愿**填写一句说明（不超过
500 字）。这句话会随报错事件一起发送，**仅用于改进课程内容**，同样匿名、
不与任何身份关联。不填写不影响报错。

报错时会附上**当前卡片画面的截图**（仅含本应用自己的界面，技术上不可能
包含应用之外的内容；如果答题文字当时可见，也会出现在截图中）和最近的应用内
诊断轨迹（例如经过的页面、卡片与操作顺序），
用于排查显示与流程问题。诊断轨迹不包含录音，也不包含你输入的文字（你自愿填写
的报错说明除外）。这些附件与报错一样不与身份关联，仅用于修复和改进产品。

在 iOS 上，报错附件直接保存到 Apple CloudKit。在 Android 上，附件先通过 HTTPS
发送到 Google Cloud Run 中的专用中转服务；Google Play Integrity 用于验证它来自
正版应用。为完成验证，Google 处理请求摘要、应用包名/版本/签名证书、设备上已登录
账号对应的 Play 许可状态，以及密钥证明证书和设备证明令牌。数据传输加密、按固定
期限删除，且我们不将其用于识别或追踪个人。验证通过后，附件保存到 Apple CloudKit。
Android 设备上的待传临时截图位于不参加
系统备份的目录；成功上传、永久失败或超过七天后删除。已经提交的报错记录会保留到
不再需要排查和改进相关问题为止。你可以按本页末尾的邮箱联系我们，并提供大致提交
时间和卡片，以请求删除某条报错。

每条事件附带：应用版本、构建号、系统语言、操作系统版本、距首次安装的天数。

这些事件关联到一个**在你的设备上随机生成的标识符**。它不是你的 Apple ID，
不是 Google 账号，不是任何设备标识符，也不与任何姓名、邮箱或账号关联——
因为小马根本没有账号系统。**删除并重新安装应用，这个标识符即被重置**，
新旧数据无法关联。

### 平台差异

| | iOS | Android |
|---|---|---|
| 匿名使用统计 | 收集 | 收集 |
| 跟读发音（麦克风） | 有此功能 | 有此功能 |
| 学习进度备份 | 用户开启时使用 iCloud | 系统允许时使用 Google Android Auto Backup |
| 报错附件路径 | Apple CloudKit | Google Cloud Run / Play Integrity → Apple CloudKit |

### 数据处理方

匿名统计由 **TelemetryDeck**（[telemetrydeck.com](https://telemetrydeck.com)）
代我们处理。报错附件由 **Apple CloudKit** 保存；Android 版还使用
**Google Cloud Run** 中转附件并使用 **Google Play Integrity** 验证应用；Google
在该验证中处理上述应用、许可与设备证明信息。
这些公司都是受我们指示、代表我们提供相应基础设施的服务提供方。我们不出售
数据、不用于广告，也不向其他第三方披露数据供其自行使用。

## 跟读发音

跟读打分在 iOS 上使用 Apple 的设备端语音识别，在 Android 12（API 31）及以上
只使用 Android 明确提供的 **on-device speech recognizer**。不支持设备端识别时，
该功能会显示为不可用，不会回退到可能联网的通用识别服务。**录音不会发送到我们
的服务器**，也不会被我们存储——识别在你的设备上完成，匿名统计只发送分数
（0–100）和识别语言。
朗读时「读到哪里、哪里变绿」的实时提示同样完全在设备上计算，不涉及任何
上传。麦克风权限由系统弹窗征询，你可以随时拒绝或
在系统设置中撤销；拒绝后其余功能完全不受影响。

## 你的学习进度

学习进度、复习计划、经验值等保存在**你自己的设备上**。

iOS 版若你开启了 iCloud，进度会备份到**你自己的 iCloud 账户**。Android 版在
设备、Google 服务和系统设置允许时，会通过 Android Auto Backup 备份到你的
Google 账户，并可能在重装或换机时恢复。平台备份由 Apple 或 Google 管理，我们
无法读取。Android 的随机统计标识符明确不参加备份，因此重装后仍会重置。

## 购买与订阅

会员购买由 Apple App Store 或 Google Play 处理。我们不接收或保存你的银行卡号、
账单地址或商店账号凭据。应用会从商店取得商品、价格、购买与订阅状态，以便显示
本地化价格、解锁内容、恢复购买及管理订阅；匿名统计会记录商品 ID、显示价格、
购买类型和购买结果，用于了解付费流程是否正常。

Android 版在购买或恢复购买时，会通过 HTTPS 将商品 ID、Google Play purchaseToken、
应用版本和 Play Integrity 证明发送到我们在 Google Cloud Run 上的专用服务。该服务
调用 Google Play Developer API 核实当前购买/订阅状态，并确认已经完成的交易，然后
只把权益状态返回应用。Roma Tech 不记录或持久保存 purchaseToken、订单资料或商店账号
信息；token 只在这次实时验证所需的内存和加密传输中处理。Google 会按其自己的政策
管理 Play 交易记录。

## 儿童

本应用面向成人学习者，不针对 13 岁以下儿童，也不会有意收集儿童的个人信息。

## 你的权利

删除应用会停止新的收集并删除本机副本，但平台备份可能按你的 Apple 或 Google
账户设置保留，并在以后恢复；你可在相应平台的系统设置中管理这些备份。重新安装
会生成新的匿名统计标识符。对于已经主动提交的报错附件，可按下方邮箱联系我们，
并提供大致提交时间和卡片以请求删除。由于小马没有账号，请求中提供这些线索才能
帮助我们定位记录。

如果你对数据处理有任何疑问，可通过下方邮箱联系我们。

## 变更

本政策如有变更，我们会更新本页顶部的日期。应用的重大数据行为变更会同时
在 App Store 与 Google Play 的数据披露中反映。

## 联系方式

**Roma Tech LLC**
邮箱：<a href="mailto:roma.tech.ai@gmail.com">roma.tech.ai@gmail.com</a>

---

# Pony — Privacy Policy {#en}

**Last updated: 24 August 2026**

Pony is a Japanese and English learning app built by **Roma Tech LLC**. This
policy describes what the app collects, what it does not, and why. The iOS and
Android versions differ; both are covered below.

## What we do not collect

- **No accounts.** The app has no sign-up and no login. We do not have your
  name, email address, or phone number.
- **No cross-app or cross-site tracking.** No advertising SDKs, no data
  brokers, no targeted advertising. iOS shows no App Tracking Transparency
  prompt because there is nothing to track.
- **No persistent device identifiers for tracking.** We do not use the
  advertising identifier (IDFA / GAID), Android ID, IMEI, or hardware serial
  numbers. When an Android user intentionally submits a report, Google Play
  Integrity processes app, licensing, and device-attestation information to
  verify the request, as described below; it is not used for ads or user tracking.
- **No text you type (except during an intentional report, as described below).**
  Anything you write in the "learning goal" field stays **on your device**.
  Report exceptions are the note you may voluntarily attach and answer text
  that is visible in the screenshot when you choose to submit a report.
- **No audio recordings.** See "Pronunciation practice" below.

## What we do collect

### Anonymous usage analytics

To improve the course, the app sends learning-activity events: app opens,
lessons started and finished, whether each practice item was answered
correctly and how long it took, review sessions, the goal and level chosen
during onboarding, and paywall impressions and purchase outcomes.

When you report a card issue and choose "other", you may **voluntarily** type
a short note (up to 500 characters). It is sent with the report, is used
**only to improve the course content**, and is anonymous like everything
else. Reporting works without it.

Card reports include a **screenshot of the current card screen** (it shows
only this app's own interface and cannot capture content outside the app; any
answer text currently visible on that screen is included) and
a recent in-app diagnostic trace, such as the sequence of screens, cards, and
actions. The trace contains no recording and no text you typed except a note
you voluntarily attach to the report. These attachments are not linked to an
identity and are used only to diagnose issues and improve the product.

On iOS, report attachments are stored directly in Apple CloudKit. On Android,
they are sent over HTTPS to a dedicated relay on Google Cloud Run; Google Play
Integrity verifies that the submission came from the genuine app. For this
verification, Google processes the request hash, app package/version/signing
certificate, Play license status for signed-in accounts on the device, a key
attestation certificate, and a device-attestation token. The data is encrypted,
deleted after a fixed retention period, and is not used by us to identify or
track a person. The relay then stores the attachment in Apple CloudKit. A pending Android screenshot is kept
in a no-backup area on the device and is deleted after success, permanent
failure, or seven days. Submitted reports are retained until they are no
longer needed to investigate and improve the relevant issue. You may request
deletion of a report by emailing us with its approximate submission time and
card.

Each event carries the app version, build number, system locale, OS version,
and the number of days since first install.

Events are keyed to an identifier **generated randomly on your device**. It is
not your Apple ID, not a Google account, not any device identifier, and it is
linked to no name, email, or account — Pony has no accounts. **Deleting and
reinstalling the app resets it**, and data from before and after cannot be
connected.

### Platform differences

| | iOS | Android |
|---|---|---|
| Anonymous usage analytics | Collected | Collected |
| Pronunciation practice (microphone) | Available | Available |
| Progress backup | iCloud when enabled by the user | Google Android Auto Backup when available |
| Report attachment route | Apple CloudKit | Google Cloud Run / Play Integrity → Apple CloudKit |

### Processor

Anonymous analytics are processed on our behalf by **TelemetryDeck**
([telemetrydeck.com](https://telemetrydeck.com)). Report attachments are stored
by **Apple CloudKit**; Android also uses **Google Cloud Run** to relay them and
**Google Play Integrity** to verify the app; Google processes the app,
licensing, and device-attestation information described above. These companies provide the
respective infrastructure on our behalf. We do not sell data, use it for
advertising, or disclose it to other third parties for their own use.

## Pronunciation practice

Pronunciation scoring uses Apple's on-device speech recognition on iOS. On
Android 12 (API 31) and later, it uses only Android's explicit **on-device
speech recognizer**. If on-device recognition is unavailable, the feature is
shown as unavailable and does not fall back to a generic recognizer that may
use a network service. **Recordings are never sent to our servers** and are not
stored by us — recognition happens on your device, and anonymous analytics
receive only a score (0–100) and the language. The
real-time highlight that turns the target text green as you read it is
likewise computed entirely on your device; nothing is uploaded.
The system asks for microphone permission; you may decline
or revoke it at any time in Settings, and nothing else in the app is affected.

## Your learning progress

Progress, review scheduling, and XP are stored **on your own device**.

On iOS, if you use iCloud, progress is backed up to **your own iCloud
account**. On Android, when the device, Google services, and your system
settings permit, Android Auto Backup stores progress in your Google account
and may restore it after reinstalling or changing devices. Apple and Google
manage these platform backups; we cannot read them. Android's random analytics
identifier is explicitly excluded from backup, so it is still reset on
reinstall.

## Purchases and subscriptions

Membership purchases are processed by the Apple App Store or Google Play. We
do not receive or store your card number, billing address, or store-account
credentials. The app receives product, price, purchase, and subscription
status from the store so it can show localized prices, unlock content, restore
purchases, and manage subscriptions. Anonymous analytics record product ID,
display price, purchase kind, and outcome to help us detect payment-flow
problems.

On Android, when you purchase or restore a purchase, the app sends the product
ID, Google Play purchaseToken, app version, and a Play Integrity attestation
over HTTPS to our dedicated service on Google Cloud Run. That service calls the
Google Play Developer API to verify the current purchase or subscription state
and acknowledge completed transactions, then returns only entitlement status to
the app. Roma Tech does not log or persist the purchaseToken, order details, or
store-account information; the token is processed only in memory and encrypted
transit for this live verification. Google manages Play transaction records
under its own policies.

## Children

This app is intended for adult learners. It is not directed at children under
13 and we do not knowingly collect personal information from children.

## Your rights

Deleting the app stops new collection and removes its local copy, but a
platform backup may remain according to your Apple or Google account settings
and can later be restored. You can manage those backups in the corresponding
platform settings. Reinstalling generates a new anonymous analytics
identifier. To request deletion of a report you submitted, email us with its
approximate submission time and card; because Pony has no account, those clues
are needed to locate the record.

If you have questions about how data is handled, contact us at the address
below.

## Changes

If this policy changes, we will update the date at the top of this page.
Material changes to the app's data behaviour will also be reflected in the App
Store and Google Play data disclosures.

## Contact

**Roma Tech LLC**
Email: <a href="mailto:roma.tech.ai@gmail.com">roma.tech.ai@gmail.com</a>

---

# Pony（小马）— プライバシーポリシー {#ja}

**最終更新日：2026 年 8 月 24 日**

Pony（小马）は、**Roma Tech LLC** が開発・提供する日本語および英語の学習
アプリです。本ポリシーでは、本アプリが何を取得し、何を取得しないか、
またその理由を説明します。iOS 版と Android 版で挙動が異なる点は、それぞれ
明記します。

## 取得しないもの

- **アカウントはありません。** 会員登録もログインも不要です。お客様の
  氏名・メールアドレス・電話番号を当社は保有していません。
- **アプリ間・サイト間のトラッキングは行いません。** 広告 SDK やデータ
  ブローカーは利用せず、ターゲティング広告も配信しません。iOS で
  App Tracking Transparency の許可ダイアログが表示されないのは、
  追跡する対象がそもそも存在しないためです。
- **追跡のための永続的な端末識別子は使用しません。** 広告識別子（IDFA / GAID）、
  Android ID、IMEI、ハードウェアシリアル番号は使用しません。Android で利用者が
  不具合報告を送信した場合に限り、Google Play Integrity がアプリ、ライセンス、
  端末証明情報を処理して送信元を検証します。広告や利用者追跡には使用しません。
- **入力されたテキストは送信しません（不具合報告時の例外を除く）。**
  「学習の目的」欄に記入された内容は**お使いの端末内にのみ保存**され、
  端末外に送信されることはありません。例外は、カードの不具合報告で
  **任意で**記入する説明文と、報告送信時のスクリーンショットに表示されている
  解答文字です（「匿名の利用統計」を参照）。
- **録音データを送信しません。** 下記「発音練習」をご覧ください。

## 取得するもの

### 匿名の利用統計

教材を改善するため、学習に関する操作イベントを送信します。具体的には、
アプリの起動、レッスンの開始と完了、各設問の正誤と解答所要時間、復習の
完了、初回設定で選択された学習目的とレベル、および有料プラン画面の表示と
購入結果です。

カードの不具合報告で「その他」を選択した場合、**任意で**説明文
（500 文字以内）を記入できます。この文章は報告と一緒に送信され、
**教材の改善のみに使用**されます。他の情報と同様に匿名で、いかなる身元
情報とも結び付きません。記入しなくても報告は送信できます。

不具合報告には、表示や操作上の問題を調査するため、**その時点のカード画面の
スクリーンショット**（本アプリ自身の画面のみ。表示中の解答文字も含まれます）と、直近の画面・カード・操作順序
などのアプリ内診断履歴が添付されます。診断履歴に録音データは含まれず、任意で
記入した報告文以外の入力文字も含まれません。これらは身元情報と結び付けず、
問題の修正と製品改善のためにのみ使用します。

iOS では報告の添付データを Apple CloudKit に直接保存します。Android では HTTPS
で Google Cloud Run 上の専用中継サービスへ送信し、Google Play Integrity で正規
アプリからの送信であることを確認します。この検証のため、Google はリクエストハッシュ、
アプリのパッケージ名・バージョン・署名証明書、端末上のログイン済みアカウントに関する
Play ライセンス状態、鍵証明書、端末証明トークンを処理します。データは暗号化され、
所定の保持期間後に削除され、当社が個人の識別や追跡に使用することはありません。
検証後、添付データを Apple CloudKit に保存します。Android
端末上の送信待ち画像はバックアップ対象外の領域に置かれ、送信成功、恒久的失敗、
または 7 日経過後に削除されます。送信済みの報告は、関連する問題の調査・改善に
必要でなくなるまで保持します。おおよその送信時刻とカードを添えて下記メールへ
ご連絡いただければ、該当報告の削除を依頼できます。

各イベントには、アプリのバージョン、ビルド番号、システムの言語設定、OS の
バージョン、初回インストールからの経過日数が付随します。

これらのイベントは、**お使いの端末上でランダムに生成された識別子**に
紐付きます。これは Apple ID でも Google アカウントでも端末識別子でもなく、
氏名・メールアドレス・アカウントのいずれとも結び付きません（Pony には
そもそもアカウントの仕組みがありません）。**アプリを削除して再インストール
すると識別子はリセットされ**、前後のデータを関連付けることはできません。

### プラットフォームによる違い

| | iOS | Android |
|---|---|---|
| 匿名の利用統計 | 取得します | 取得します |
| 発音練習（マイク） | 利用できます | 利用できます |
| 学習進捗のバックアップ | 有効な場合は iCloud | 利用可能な場合は Google Android Auto Backup |
| 報告添付の経路 | Apple CloudKit | Google Cloud Run / Play Integrity → Apple CloudKit |

### 処理の委託先

匿名の利用統計は、当社の指示に基づき
**TelemetryDeck**（[telemetrydeck.com](https://telemetrydeck.com)）が処理します。
報告の添付データは **Apple CloudKit** に保存され、Android 版では中継に
**Google Cloud Run**、正規アプリの確認に **Google Play Integrity** も利用し、
Google は上記のアプリ、ライセンス、端末証明情報を処理します。
各社は当社に代わって該当する基盤を提供するサービス提供者です。当社はデータを
販売せず、広告に使用せず、その他の第三者が自己目的で利用できる形で開示しません。

## 発音練習

発音の採点には、iOS では Apple の端末内音声認識を使用します。Android 12
（API 31）以降では、Android が明示的に提供する **端末内音声認識**だけを使用します。
端末内認識を利用できない場合、この機能は利用不可と表示され、ネットワークを使う
可能性のある汎用音声認識へ切り替わることはありません。
**録音データが当社のサーバーへ送信されることはなく**、当社が保存することも
ありません。認識はお使いの端末内で完結し、当社が受け取るのはスコア
（0〜100）と認識に使用した言語のみです。読み上げに合わせて対象の文字が
緑色に変わるリアルタイム表示も、すべて端末内で計算しており、送信は
一切発生しません。マイクの利用許可は OS のダイアログでお伺いします。
いつでも拒否でき、設定からの取り消しも可能です。拒否された場合でも、
その他の機能には一切影響ありません。

## 学習の進捗

学習の進捗、復習スケジュール、経験値は**お使いの端末内**に保存されます。

iOS 版で iCloud をご利用の場合、進捗は**お客様ご自身の iCloud アカウント**
にバックアップされます。これはお客様のアカウントであり、当社が読み取ることは
できません。

Android 版では、端末、Google サービス、お客様のシステム設定が許可する場合、
Android Auto Backup により Google アカウントへ進捗がバックアップされ、再インストール
や機種変更時に復元されることがあります。これらのバックアップは Apple または
Google が管理し、当社は読み取れません。Android の匿名統計用ランダム識別子は
バックアップ対象から明示的に除外されるため、再インストール時にリセットされます。

## 購入とサブスクリプション

会員購入は Apple App Store または Google Play が処理します。当社はカード番号、
請求先住所、ストアアカウントの認証情報を受け取らず、保存もしません。アプリは
ストアから商品、価格、購入・サブスクリプション状態を受け取り、現地通貨価格の表示、
コンテンツの解除、購入の復元、サブスクリプション管理に使用します。匿名統計には、
決済フローの不具合を確認するため、商品 ID、表示価格、購入種別、結果を記録します。

Android 版で購入または購入の復元を行う際、商品 ID、Google Play の purchaseToken、
アプリのバージョン、Play Integrity の証明を HTTPS で Google Cloud Run 上の当社専用
サービスへ送信します。このサービスは Google Play Developer API を呼び出して現在の
購入・サブスクリプション状態を検証し、完了した取引を確認したうえで、権利状態だけを
アプリへ返します。Roma Tech は purchaseToken、注文情報、ストアアカウント情報を
ログに記録せず、永続保存もしません。token はこのリアルタイム検証に必要なメモリ内処理
と暗号化通信でのみ扱います。Google は独自のポリシーに従って Play の取引記録を管理します。

## お子様について

本アプリは成人の学習者を対象としており、13 歳未満のお子様を対象とした
サービスではありません。お子様の個人情報を意図的に取得することはありません。

## お客様の権利

アプリを削除すると新たな取得は停止し、端末内のコピーは削除されます。ただし、
Apple または Google アカウントの設定に従いプラットフォームのバックアップが残り、
後で復元される場合があります。バックアップは各プラットフォームの設定で管理できます。
再インストール時には新しい匿名統計識別子が生成されます。送信した不具合報告の削除を
希望する場合は、おおよその送信時刻とカードを添えて下記メールへご連絡ください。
Pony にはアカウントがないため、記録の特定にはこれらの手掛かりが必要です。

データの取り扱いについてご不明な点がありましたら、下記の連絡先までお問い
合わせください。

## 変更について

本ポリシーを変更した場合は、本ページ冒頭の日付を更新します。データの
取り扱いに関する重要な変更は、App Store および Google Play のデータ開示にも
反映します。

## お問い合わせ

**Roma Tech LLC**
メール：<a href="mailto:roma.tech.ai@gmail.com">roma.tech.ai@gmail.com</a>
