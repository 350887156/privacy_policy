# AuraTime 隐私政策

**最后更新日期**：2026 年 5 月 16 日  
**生效日期**：2026 年 5 月 15 日

---

## 📱 引言

AuraTime（「我们」）致力于保护您的隐私。本隐私政策说明您使用 AuraTime 应用程序（以下简称「本应用」）时，我们如何收集、使用、存储和保护相关信息。

**重要说明**：本应用**不会**主动收集您的姓名、电子邮件、电话号码等可直接识别个人身份的信息。为改进产品体验，在**您同意或可在设置中关闭**的前提下，我们可能通过 **Google Firebase Analytics** 收集去标识化的使用统计数据（详见下文）。

---

## 🔍 我们收集的信息

### 1. 不收集的个人信息

本应用**不会**由我们主动收集或要求您填写以下信息：
- ❌ 姓名
- ❌ 电子邮件地址
- ❌ 电话号码
- ❌ 精确地理位置

**说明**：若您在设置中**开启数据分析**，Firebase Analytics 可能按 [Google 隐私政策](https://policies.google.com/privacy) 自动收集设备标识符、IP 地址、应用使用情况等去标识化技术信息。您可随时在 **设置 → 数据分析** 中关闭。

### 2. 本地存储的数据

本应用仅在您的设备本地存储以下数据，**不会**上传到任何服务器：

| 数据类型 | 用途 | 存储位置 |
|----------|------|----------|
| 专注记录 | 显示心流日历 | 本地 CoreData |
| 睡眠记录 | 显示心流日历 | 本地 CoreData |
| 用户设置 | 保存偏好设置 | 本地 UserDefaults |
| Widget 数据 | 支持小组件显示 | 本地 App Groups |

**说明**：所有数据仅存储在您的设备上，我们无法访问。

---

## 🛠 我们使用的技术

### 1. ActivityKit (Live Activities)

本应用使用 Apple 的 ActivityKit framework 来提供：
- Lock Screen 实时活动
- Dynamic Island 灵动岛显示

**数据使用**：
- 专注/睡眠状态
- 剩余时间
- 音频类型

**数据流向**：仅在您的设备本地显示，不 transmitted to any server.

### 2. App Groups

本应用使用 App Groups (`group.com.auratime.ios.app`) 来：
- 在主应用和 Widget Extension 之间共享数据
- 支持锁屏/灵动岛实时更新

**数据范围**：仅在您的设备本地共享，not accessible by other apps.

### 3. Background Audio

本应用使用 Background Audio mode 来：
- 在锁屏状态下 播放白噪音
- 支持 Bluetooth/AirPlay 音频输出

**说明**：音频文件 bundled with the app，no streaming from external servers.

---

## 📊 第三方服务

### Firebase Analytics（Google）

本应用集成 **Google Firebase Analytics**，用于了解功能使用情况、改进稳定性与体验。

| 项目 | 说明 |
|------|------|
| **服务提供方** | Google LLC（Firebase） |
| **处理目的** | 产品分析、功能优化、错误统计 |
| **默认状态** | 首次安装后默认**开启**；可在应用内关闭 |
| **关闭方式** | 打开本应用 → **设置** → 关闭 **「启用分析」** |
| **我们发送的数据** | 见下表「分析事件类型」 |
| **我们不发送的数据** | 姓名、邮箱、电话、通讯录、照片、精确位置、专注/睡眠日记正文 |

**我们可能记录的分析事件类型**（均为去标识化、聚合用途）：

| 事件类别 | 示例参数 |
|----------|----------|
| 应用生命周期 | 打开/关闭应用、会话时长 |
| 专注/睡眠会话 | 开始、完成、暂停、取消；时长（分钟）；是否完成 |
| 音频与设置 | 音轨类型（如雨声/篝火/海浪）；设置项变更 |
| 界面与小组件 | 屏幕浏览名称；小组件点击类型 |
| 错误 | 错误类型、非个人化错误描述（不含用户输入内容） |

**用户属性**（可选，用于细分统计）：偏好音轨类型、是否调试模式、连续专注天数等汇总信息。

**数据存储与跨境**：Firebase 可能将数据处理于您所在国家/地区以外（如美国）的服务器，并受 Google 安全措施约束。详见：

- [Google 隐私政策](https://policies.google.com/privacy)
- [Firebase 使用条款](https://firebase.google.com/terms)
- [Google Analytics for Firebase 数据收集说明](https://firebase.google.com/support/privacy)

关闭数据分析后，我们将停止通过 Firebase 收集新的分析事件；Google 侧已收集数据的保留与删除适用 Google 相关政策。

### 我们**不使用**的其他第三方服务

本应用**不包含**：
- ❌ 第三方广告 SDK（如 AdMob）
- ❌ 独立崩溃上报 SDK（如 Crashlytics；错误事件仅通过 Firebase Analytics 记录）
- ❌ 社交媒体 SDK（如 Facebook、微信 SDK）
- ❌ 第三方支付 SDK（内购由 Apple 处理）

### 我们**使用**的 Apple 服务

| Service | 用途 | 数据共享 |
|---------|------|----------|
| Apple In-App Purchase | 处理内购订阅 | Apple 处理支付信息 |
| Apple CloudKit (可选) | iCloud 备份 (需用户手动开启) | Apple 存储加密数据 |
| Apple HealthKit (未使用) | - | - |

---

## 🔒 数据安全

### 本地数据安全

除可选的 Firebase 分析外，本应用不收集可识别个人身份的信息。数据安全主要包括：

1. **Device Security**: 您的设备应由您通过 passcode/biometrics 保护
2. **iCloud Backup**: 如启用 iCloud 备份，数据将 encrypted by Apple
3. **App Data**: 应用数据 stored in sandboxed container，other apps cannot access

### 内购安全

所有内购交易通过 Apple 的 In-App Purchase system 处理：
- 我们**不**处理您的 payment information
- Apple 作为 merchant of record
- 遵守 Apple 的 privacy and security standards

---

## 👶 儿童隐私

本应用适合所有 ages，包括 children under 13。

本应用：
- ❌ 不展示第三方广告
- ❌ 不含社交媒体集成
- ✅ 家长可在设置中关闭数据分析
- ❌ 不收集儿童姓名、联系方式等个人信息

我们 comply with:
- 美国 COPPA (Children's Online Privacy Protection Act)
- 欧盟 GDPR-K (General Data Protection Regulation for Kids)
- 中国 儿童个人信息网络保护规定

---

## 🌍 数据跨境传输

- **本地数据**（专注记录、设置等）仅存储在您的设备，由我们直接访问。
- **Firebase Analytics**（若开启）：数据可能传输至 Google 境外服务器，适用 Google 隐私政策与安全措施。
- **iCloud 备份**（若由您开启）：由 Apple 处理，适用 Apple 隐私政策。

---

## 📝 您的权利

根据 applicable privacy laws (如 GDPR, CCPA)，您享有以下 rights：

### 1. Right to Access (访问权)
您可以访问存储在 app 中的您的数据：
- 打开 App → 心流日历 → 查看所有 records

### 2. Right to Rectification (更正权)
您可以更正不准确的数据：
- 目前所有数据 automatically generated，no manual input required

### 3. Right to Erasure (删除权)
您可以删除所有数据：
- 方法 1: 删除本 app (所有数据 will be deleted)
- 方法 2: 在 app 内删除 individual records (功能开发中)

### 4. Right to Data Portability (可携带权)
您可以 export 您的数据：
- 功能开发中 (计划支持 export to CSV)

### 5. 撤回同意 / 退出分析（撤回同意权）

您可随时在 **设置 → 启用分析** 中关闭 Firebase Analytics，关闭后不再发送新的分析数据。

---

## 🔔 隐私政策更新

我们可能会 periodically update 本 privacy policy。

### 更新方式
- 更新后的 policy 将 published in this document
- **Last Updated** date will be revised
- 对于 material changes，我们 may notify you via:
  - In-app notification (如实现)
  - App Store update description

### 您的选择
- 如您继续使用本 app，即视为 accept the updated policy
- 如不同意，您可以 stop using the app and delete it

---

## 📬 联系我们

如您对本 privacy policy 有任何疑问，请通过以下方式联系我们：

| 联系方式 | 详情 |
|----------|------|
| **电子邮件** | sclea1988@gmail.com |

**Response Time**: We will respond within 30 days.

---

## ⚖️ 适用法律与管辖

本 privacy policy 受以下法律管辖：

- **主要适用**: 中华人民共和国 网络安全法、个人信息保护法
- **国际用户**: 同时 comply with applicable local laws (如 GDPR for EU users)
- **争议解决**: 友好协商优先，如无法解决，提交有管辖权的人民法院

---

## 📋 关键条款总结

| 条款 | 我们的承诺 |
|------|-----------|
| **个人身份信息** | ❌ 不收集姓名、邮箱、电话等 |
| **本地数据** | 💾 专注/睡眠记录仅存于设备 |
| **产品分析** | 📊 可选 Firebase Analytics，默认开启，可随时关闭 |
| **数据共享** | 🔒 不向第三方出售数据；分析数据按 Google 政策处理 |
| **广告** | ❌ 不 display third-party ads |
| **儿童隐私** | ✅ 符合 COPPA 和其他儿童隐私保护法规 |
| **数据安全** | 🔐 依赖 iOS sandbox 和 device security |
| **政策更新** | 📝 更新时会通知 (major changes) |

---

## 🎯 Privacy by Design 原则

本应用遵循 Privacy by Design 原则：

1. **Proactive not Reactive**: 从设计阶段就考虑 privacy
2. **Privacy as Default**: 默认 settings 保护 privacy
3. **Privacy Embedded into Design**: privacy 是 core feature，not add-on
4. **Full Functionality**: 无需 sacrifice privacy for functionality
5. **End-to-End Security**: 数据 lifecycle 全程保护
6. **Visibility and Transparency**: 本 policy 清晰透明
7. **Respect for User Privacy**: 以 user 为中心，保护 privacy

---

**Thank you for trusting AuraTime with your focus and sleep.**

我们 committed to protecting your privacy by design.

---

*本隐私政策中英文版本如有不一致，以中文版为准。*
