# AuraTime 隐私政策

**最后更新日期**：2026 年 5 月 15 日  
**生效日期**：2026 年 5 月 15 日

---

## 📱 引言

AuraTime（"我们"、"我们的"或"us"）致力于保护您的隐私。本隐私 policy 说明了我们如何收集、使用、存储 和保护 您的个人信息。当您使用 AuraTime 应用程序（以下简称"本应用"）时。

**重要**: 本应用**不收集**任何个人 identifiable information（个人身份信息）。我们 respect your privacy by design.

---

## 🔍 我们收集的信息

### 1. 不收集的个人信息

本应用**不会**收集以下信息：
- ❌ 姓名（姓名）
- ❌ Email address（电子邮件）
- ❌ Phone number（电话号码）
- ❌ Location data（位置信息）
- ❌ Device identifiers（设备标识符）
- ❌ Usage analytics（使用分析）
- ❌ Third-party tracking（第三方追踪）

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

### 我们**不使用**的第三方 Services

本应用**不包含**以下第三方服务：
- ❌ Analytics SDKs (如 Firebase Analytics, Flurry)
- ❌ Advertising SDKs (如 AdMob, Unity Ads)
- ❌ Crash Reporting (如 Crashlytics, Bugly)
- ❌ Social Media SDKs (如 Facebook SDK, WeChat SDK)
- ❌ Payment SDKs (内购通过 Apple In-App Purchase)

### 我们**使用**的Apple Services

| Service | 用途 | 数据共享 |
|---------|------|----------|
| Apple In-App Purchase | 处理内购订阅 | Apple 处理支付信息 |
| Apple CloudKit (可选) | iCloud 备份 (需用户手动开启) | Apple 存储加密数据 |
| Apple HealthKit (未使用) | - | - |

---

## 🔒 数据安全

### 本地数据安全

由于本应用不收集任何个人信息，data security primarily concerns:

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

由于本应用：
- ❌ 不收集 any personal information
- ❌ 不 display third-party ads
- ❌ 不 contain social media integration
- ❌ 不 use behavioral tracking

我们 comply with:
- 美国 COPPA (Children's Online Privacy Protection Act)
- 欧盟 GDPR-K (General Data Protection Regulation for Kids)
- 中国 儿童个人信息网络保护规定

---

## 🌍 数据跨境传输

**本应用不涉及数据跨境传输**，因为：
- 所有数据 stored locally on your device
- 不 transmitted to any servers (ours or third-party)
- 如启用 iCloud 备份，数据由 Apple 处理 (受 Apple 的 privacy policy 约束)

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

### 5. Right to Withdraw Consent (撤回同意权)
不适用，因为本应用不 require consent for data processing.

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
| **Email** | support@auratime.app |
| **Website** | www.auratime.app |
| **地址** | [Your Business Address, Optional] |

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
| **数据收集** | ❌ 不收集任何 personal identifiable information |
| **数据存储** | 💾 仅存储在您的设备本地 |
| **数据共享** | 🔒 不与任何 third parties 共享 |
| **数据分析** | ❌ 不使用 any analytics or tracking |
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
