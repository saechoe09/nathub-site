# NatHub 1.0 App Store 首发材料

更新日期：2026-07-01

适用策略：个人开发者账号，首版免费，无内购，无广告，无账号，发布地区排除中国大陆。

## 当前结论

- 账号状态：Apple Developer Program 会员购买处理中；等状态激活后再创建 App Store Connect App。
- App 名称：NatHub
- Bundle ID：`com.saechoe.ScienceLab`
- 版本：`1.0`
- Build：`1`
- 最低系统：iOS 17.0
- 设备范围：当前工程支持 iPhone 和 iPad；若保持 iPad 支持，提交时也需要准备 iPad 截图与布局验收。
- 首版实验：水波、光的折射、沙之痕、磁力阵列
- 付费：免费
- 中国大陆：首版不发布，等 APP 备案和主体规划清楚后再打开。

## App Store Connect 填写表

| 字段 | 建议填写 | 要求/限制 | 备注 |
| --- | --- | --- | --- |
| App 名称 | NatHub | 2-30 个字符 | Apple 要求 App 名称最多 30 个字符。 |
| 副标题 | 在指尖发现物理之美 | 最多 30 个字符 | 中文本地化用。 |
| Subtitle | Discover Beauty in Motion | 最多 30 个字符 | 英文本地化用。 |
| SKU | `nathut-ios-001` | 内部编号，不展示给用户 | 创建后不能改。 |
| Bundle ID | `com.saechoe.ScienceLab` | 必须和 Xcode 工程一致 | 上传 build 后不能改。 |
| 主分类 | Education | App Store 分类 | 如果更想突出审美/放松，可考虑 Entertainment。 |
| 次分类 | Entertainment | 可选 | 保留教育定位，同时表达沉浸式体验。 |
| 价格 | Free | 免费 App 不需要银行/税务/付费协议 | 后续做内购时再签 Paid Apps Agreement。 |
| 发布地区 | 除 China Mainland 以外 | 可后续调整 | 首版避开 APP 备案阻塞。 |
| 隐私政策 URL | `TODO: 填公开网页链接` | iOS App 必填 | 建议先用 GitHub Pages/官网/Notion 公开页面。 |
| 技术支持 URL | `TODO: 填公开网页或 mailto 页面` | 通常必填 | 可以做一个简单网页，列邮箱和常见信息。 |
| 营销 URL | 留空 | 可选 | 首版不需要。 |
| 版权 | `2026 sasa zhou` | App Store 页面展示 | 个人账号先用个人名；若后续公司化再调整。 |
| 审核联系人 | `TODO: 你的姓名、电话、邮箱` | 审核团队联系用 | 不展示给用户。 |
| 登录信息 | 不需要登录 | 如需登录才填测试账号 | 审核备注里说明无需账号。 |
| 年龄分级 | 预计 4+ | 按问卷结果为准 | 无用户生成内容、无成人内容、无付费抽奖。 |
| 加密出口合规 | 预计使用 Apple 系统标准加密/无自定义加密 | 按 App Store Connect 问卷为准 | 当前没有自研加密。 |
| App 隐私 | 不收集数据 | 必须和真实行为一致 | 当前隐私清单声明不追踪、不收集数据。 |

官方参考：

- App 信息字段：Apple 说明 App 名称 2-30 字符，副标题最多 30 字符，隐私政策 URL 对 iOS/macOS 必填。
  https://developer.apple.com/help/app-store-connect/reference/app-information/app-information
- 截图规格：
  https://developer.apple.com/help/app-store-connect/reference/app-information/screenshot-specifications
- App 隐私：
  https://developer.apple.com/help/app-store-connect/manage-app-privacy/overview-of-app-privacy

## 中文商店文案

### 副标题

在指尖发现物理之美

### 描述

NatHub 是一个安静、直观的互动实验应用，把水波、光线、沙粒和磁场放进可以触摸的手机空间里。

首发版本包含四个本地实验：

- 水波：轻触屏幕，观察涟漪如何形成、扩散和叠加。
- 光的折射：移动玻璃形状，观察光线穿过不同介质后的弯折与色散。
- 沙之痕：在黑白沙粒之间划出轨迹，感受线条、残留和时间留下的纹理。
- 磁力阵列：拖动磁石，看钢珠磁针如何沿着磁场重新排列。

NatHub 不需要注册账号，不包含广告，不接入第三方统计，也不提供付费解锁。首发实验在设备本地运行，适合用来观察自然现象、放松片刻，或作为物理概念的直观入门。

### 关键词

物理,实验,水波,折射,光学,磁场,沙画,自然,互动,教育

说明：App Store Connect 关键词总长度限制通常按 100 字符处理；提交前不要重复 App 名称里的词。

### 推广文本

用手指观察水波、光线、沙粒和磁场，把抽象的物理现象变成安静的互动体验。

说明：Promotional Text 可在不发新版的情况下更新；如果没有把握，可首版先留空。

### 新版本说明

NatHub 首发版本上线：包含水波、光的折射、沙之痕和磁力阵列四个互动实验。

## English Store Copy

### Subtitle

Discover Beauty in Motion

### Description

NatHub is a quiet interactive lab for observing natural phenomena through touch. It turns waves, light, sand, and magnetic fields into small experiments you can explore on your device.

The launch version includes four local experiments:

- Water Ripples: tap to watch waves form, spread, and overlap.
- Light Refraction: move glass shapes and observe how light bends and separates.
- Sand Traces: draw through black and white grains and watch each line leave a soft trace.
- Magnetic Array: drag a magnet and see steel needles align into visible field patterns.

NatHub requires no account, includes no advertising, uses no third-party analytics, and has no paid unlocks in the launch version. Experiments run locally on the device, making the app suitable for quiet observation, visual exploration, and an intuitive first step into physics concepts.

### Keywords

physics,waves,refraction,optics,magnetism,sand,nature,interactive,education

### Promotional Text

Explore waves, light, sand, and magnetic fields through quiet touch-based experiments.

### What's New

NatHub launches with four interactive experiments: Water Ripples, Light Refraction, Sand Traces, and Magnetic Array.

## 隐私政策草案

用途：放到公开网页，并把 URL 填入 App Store Connect。下面可直接作为中文页面正文。

### NatHub 隐私政策

生效日期：2026 年 7 月 1 日

NatHub 尊重你的隐私。首发版本不要求注册账号，不接入广告，不接入第三方统计，也不收集、存储或共享个人数据。

### 我们收集的数据

首发版本不收集个人数据。

NatHub 的水波、光的折射、沙之痕和磁力阵列实验均在设备本地运行。应用不会上传你的实验操作、设备标识、位置、联系人、照片、麦克风内容或其他个人信息。

### 设备权限

首发版本不请求相机、麦克风、照片、位置或通讯录权限。

### 本地设置

应用可能在当前设备本地保存语言、声音和触感偏好。这些设置仅用于改善你的本机使用体验，不会上传到服务器，也不会与第三方共享。

### 第三方服务

首发版本不接入广告、第三方统计 SDK、第三方登录或支付服务。

### 儿童隐私

NatHub 面向一般用户提供自然现象观察体验。首发版本不收集个人数据，也不要求儿童提供联系方式或账号信息。

### 政策更新

如果未来版本引入账号、联网服务、付费功能、广告或数据分析，NatHub 会在相关功能启用前更新本政策，并说明相关数据用途。

### 联系方式

如对本隐私政策有疑问，请通过以下邮箱联系：

`saechoe09@gmail.com`

## Privacy Policy Draft

Use this for an English privacy policy page if you publish an English listing.

### NatHub Privacy Policy

Effective date: July 1, 2026

NatHub respects your privacy. The launch version does not require an account, does not include advertising, does not use third-party analytics, and does not collect, store, or share personal data.

### Data We Collect

The launch version does not collect personal data.

NatHub's Water Ripples, Light Refraction, Sand Traces, and Magnetic Array experiments run locally on your device. The app does not upload your experiment interactions, device identifiers, location, contacts, photos, microphone content, or other personal information.

### Device Permissions

The launch version does not request access to the camera, microphone, photos, location, or contacts.

### Local Preferences

The app may store language, sound, and haptic preferences locally on your current device. These preferences are used only to improve your experience on that device. They are not uploaded to a server and are not shared with third parties.

### Third-Party Services

The launch version does not include advertising, third-party analytics SDKs, third-party login, or payment services.

### Children's Privacy

NatHub provides a general natural-phenomena observation experience. The launch version does not collect personal data and does not ask children to provide contact details or account information.

### Updates

If a future release introduces accounts, online services, purchases, advertising, or analytics, NatHub will update this policy before those features become available and explain any related data use.

### Contact

For questions about this privacy policy, contact:

`saechoe09@gmail.com`

## 技术支持页面草案

用途：放到公开网页，并把 URL 填入 App Store Connect 的 Support URL。

### NatHub 技术支持

如果你在使用 NatHub 时遇到问题，或希望提出新的实验想法，请发送邮件至：

`saechoe09@gmail.com`

为了更快定位问题，建议在邮件中包含：

- 设备型号
- iOS 版本
- NatHub 版本
- 出现问题的实验名称
- 问题发生前的操作步骤
- 如果是视觉或交互问题，请附截图

首发版本不需要注册账号，不包含广告、付费解锁或在线服务。

## App 隐私问卷建议

按当前实现建议选择：

- Tracking：No
- Data Collection：Data Not Collected
- Contact Info：不收集
- Identifiers：不收集
- Usage Data：不收集
- Diagnostics：不收集
- Location：不收集
- User Content：不收集

提交前检查：

- 不接入广告 SDK。
- 不接入第三方统计 SDK。
- 不上传用户行为。
- 不请求相机、照片、麦克风、定位、通讯录权限。
- 若未来加入崩溃收集、统计、联网账号或付费功能，需要同步更新隐私政策和 App 隐私标签。

## 截图计划

### 需要的截图

如果首版保留 iPhone + iPad 支持：

- iPhone：至少准备 6.7 英寸展示尺寸截图，建议 5 张。
- iPad：准备 iPad 展示尺寸截图，建议 5 张。

如果首版改成仅 iPhone：

- 只准备 iPhone 截图即可。

建议顺序：

1. 水波：展示涟漪形成和叠加。
2. 光的折射：展示彩色光线穿过玻璃。
3. 沙之痕：展示沙面轨迹。
4. 磁力阵列：展示磁场排列。
5. 首页：展示四个实验入口和整体风格。

### 截图文案叠字

首版建议先用纯 App 截图，不加营销叠字。这样更稳，也减少被认为夸大功能的风险。

### Codex 可协助截图

本机已发现可用模拟器：iPhone 17 Pro，设备 ID `38C2FE7A-7FE3-4F6F-B617-F9EF746A1085`。

计划输出目录：

`docs/release/screenshots/`

若自动截图受系统权限限制，可在 Xcode 里运行 App 后手动停在对应页面，再使用模拟器菜单截图。截图文件再放入上面的目录。

## 账号开通后执行顺序

1. 进入 Apple Developer Account，确认 Membership 有 Team ID 和到期日。
2. 进入 App Store Connect，创建新 App。
3. 填 App 名称、Bundle ID、SKU、主语言。
4. 填价格为 Free。
5. 发布地区选择除 China Mainland 外的地区。
6. 填 App 信息、描述、关键词、支持 URL、隐私政策 URL。
7. Xcode 选择个人开发者 Team。
8. Archive 并上传 Build。
9. App Store Connect 选择 Build。
10. 填年龄分级、加密出口合规、App 隐私。
11. 添加审核备注：无需登录，首版无广告、无内购、无账号，四个实验均可直接进入。
12. Submit for Review。

## 仍需你补充/确认

- 隐私政策公开 URL。
- 技术支持公开 URL。
- 审核联系人电话。
- 版权显示是否用 `2026 sasa zhou`。
- 首版是否改为仅 iPhone；如果不改，需要准备 iPad 截图并做 iPad 验收。
- App Store 主语言先用中文还是英文。
