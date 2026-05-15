# AuraTime Privacy Policy

**Last Updated**: May 16, 2026  
**Effective Date**: May 15, 2026

---

## 📱 Introduction

AuraTime ("we", "our", or "us") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, store, and protect your personal information when you use the AuraTime application (the "App").

**Important**: We do **not** collect information that directly identifies you, such as your name, email address, or phone number. To improve the App, and **only when enabled (you can turn this off in Settings)**, we use **Google Firebase Analytics** to collect de-identified usage statistics as described below.

---

## 🔍 Information We Collect

### 1. Personal Information We DO NOT Collect

We do **not** ask you to provide:
- ❌ Name
- ❌ Email address
- ❌ Phone number
- ❌ Precise location

**Note**: If you leave **Analytics** enabled in Settings, Firebase Analytics may automatically collect de-identified technical information (such as device identifiers, IP address, and usage data) as described in [Google's Privacy Policy](https://policies.google.com/privacy). You can disable this at any time under **Settings → Enable Analytics**.

### 2. Data Stored Locally

This App stores the following data **only on your device**, **NOT** uploaded to any server:

| Data Type | Purpose | Storage Location |
|-----------|---------|------------------|
| Focus sessions | Flow calendar display | Local CoreData |
| Sleep sessions | Flow calendar display | Local CoreData |
| User settings | Save preferences | Local UserDefaults |
| Widget data | Support widget display | Local App Groups |

**Note**: All data is stored only on your device. We cannot access it.

---

## 🛠 Technologies We Use

### 1. ActivityKit (Live Activities)

This App uses Apple's ActivityKit framework to provide:
- Lock Screen Live Activities
- Dynamic Island display

**Data Used**:
- Focus/Sleep status
- Remaining time
- Audio type

**Data Flow**: Displayed only on your device, not transmitted to any server.

### 2. App Groups

This App uses App Groups (`group.com.auratime.ios.app`) to:
- Share data between main App and Widget Extension
- Support Lock Screen/Dynamic Island real-time updates

**Data Scope**: Shared only locally on your device, not accessible by other apps.

### 3. Background Audio

This App uses Background Audio mode to:
- Play white noise while screen is locked
- Support Bluetooth/AirPlay audio output

**Note**: Audio files are bundled with the app, no streaming from external servers.

---

## 📊 Third-Party Services

### Firebase Analytics (Google)

This App integrates **Google Firebase Analytics** to understand feature usage and improve stability and user experience.

| Item | Details |
|------|---------|
| **Provider** | Google LLC (Firebase) |
| **Purpose** | Product analytics, feature improvement, error statistics |
| **Default** | **Enabled** on first launch; you can disable it in Settings |
| **How to opt out** | Open the App → **Settings** → turn off **Enable Analytics** |
| **Data we send** | See “Analytics events” below |
| **Data we do not send** | Name, email, phone, contacts, photos, precise location, or the text/content of your focus/sleep journal |

**Analytics events we may log** (de-identified, aggregated):

| Category | Example parameters |
|----------|-------------------|
| App lifecycle | App open/close, session duration |
| Focus / sleep sessions | Start, complete, pause, cancel; duration (minutes); completion status |
| Audio & settings | Audio track type (e.g., rain, fire, ocean); setting changes |
| UI & widgets | Screen names; widget interaction types |
| Errors | Error type; non-personal error descriptions (no user-entered content) |

**User properties** (optional, for segmentation): preferred audio track, debug mode flag, streak-related aggregates, etc.

**Storage & international transfers**: Firebase may process data on servers outside your country (e.g., the United States), subject to Google's safeguards. See:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [Firebase Terms of Service](https://firebase.google.com/terms)
- [Firebase / Google Analytics data collection](https://firebase.google.com/support/privacy)

After you disable Analytics, we stop sending new events to Firebase. Retention and deletion of data already held by Google are governed by Google's policies.

### Other Third-Party Services We Do NOT Use

This App does **not** include:
- ❌ Third-party advertising SDKs (e.g., AdMob)
- ❌ Standalone crash reporting SDKs (e.g., Crashlytics; errors may be logged via Firebase Analytics only)
- ❌ Social media SDKs (e.g., Facebook, WeChat)
- ❌ Third-party payment SDKs (purchases are handled by Apple)

### Apple Services We Use

| Service | Purpose | Data Sharing |
|---------|---------|--------------|
| Apple In-App Purchase | Handle subscription purchases | Apple processes payment info |
| Apple CloudKit (Optional) | iCloud Backup (user-enabled) | Apple stores encrypted data |
| Apple HealthKit (Not used) | - | - |

---

## 🔒 Data Security

### Local Data Security

Aside from optional Firebase Analytics, we do not collect personally identifiable information. Data security primarily concerns:

1. **Device Security**: Your device should be protected by passcode/biometrics
2. **iCloud Backup**: If enabled, data is encrypted by Apple
3. **App Data**: Stored in sandboxed container, other apps cannot access

### In-App Purchase Security

All in-app purchase transactions are processed through Apple's In-App Purchase system:
- We do **NOT** handle your payment information
- Apple acts as merchant of record
- Complies with Apple's privacy and security standards

---

## 👶 Children's Privacy

This App is suitable for all ages, including children under 13.

This App:
- ❌ Does not display third-party ads
- ❌ Does not contain social media integration
- ✅ Allows parents/guardians to disable Analytics in Settings
- ❌ Does not collect children's names, contact details, or similar personal information

We comply with:
- US COPPA (Children's Online Privacy Protection Act)
- EU GDPR-K (General Data Protection Regulation for Kids)
- China Children's Personal Information Network Protection Regulations

---

## 🌍 International Data Transfers

- **Local data** (focus records, settings, etc.) stays on your device and is not accessible by us directly.
- **Firebase Analytics** (if enabled): data may be transferred to Google's servers outside your country, subject to Google's privacy policy and security measures.
- **iCloud Backup** (if you enable it): handled by Apple under Apple's privacy policy.

---

## 📝 Your Rights

Under applicable privacy laws (e.g., GDPR, CCPA), you have the following rights:

### 1. Right to Access
You can access your data stored in the app:
- Open App → Flow Calendar → View all records

### 2. Right to Rectification
You can correct inaccurate data:
- Currently all data is automatically generated, no manual input required

### 3. Right to Erasure
You can delete all data:
- Method 1: Delete the app (all data will be deleted)
- Method 2: Delete individual records in-app (feature in development)

### 4. Right to Data Portability
You can export your data:
- Feature in development (planned: export to CSV)

### 5. Right to Withdraw Consent / Opt Out of Analytics

You can disable Firebase Analytics at any time under **Settings → Enable Analytics**. After you turn it off, we stop sending new analytics events.

---

## 🔔 Changes to This Privacy Policy

We may periodically update this Privacy Policy.

### Update Method
- Updated policy will be published in this document
- **Last Updated** date will be revised
- For material changes, we may notify you via:
  - In-app notification (if implemented)
  - App Store update description

### Your Choice
- By continuing to use the App, you accept the updated policy
- If you disagree, you can stop using the app and delete it

---

## 📬 Contact Us

If you have any questions about this Privacy Policy, please contact us:

| Contact Method | Details |
|----------------|---------|
| **Email** | sclea1988@gmail.com |

**Response Time**: We will respond within 30 days.

---

## ⚖️ Governing Law and Jurisdiction

This Privacy Policy is governed by:

- **Primary**: People's Republic of China Cybersecurity Law, Personal Information Protection Law
- **International Users**: Also comply with applicable local laws (e.g., GDPR for EU users)
- **Dispute Resolution**: Friendly negotiation first, if unresolved, submit to competent People's Court

---

## 📋 Key Terms Summary

| Term | Our Commitment |
|------|----------------|
| **Personal identity** | ❌ No name, email, or phone collected |
| **Local data** | 💾 Focus/sleep records stored on device only |
| **Product analytics** | 📊 Optional Firebase Analytics; on by default; can be disabled |
| **Data sharing** | 🔒 We do not sell data; analytics processed per Google's policies |
| **Advertising** | ❌ No third-party ads displayed |
| **Children's Privacy** | ✅ Compliant with COPPA and other regulations |
| **Data Security** | 🔐 Rely on iOS sandbox and device security |
| **Policy Updates** | 📝 Will notify for major changes |

---

## 🎯 Privacy by Design Principles

This App follows Privacy by Design principles:

1. **Proactive not Reactive**: Privacy considered from design stage
2. **Privacy as Default**: Default settings protect privacy
3. **Privacy Embedded into Design**: Privacy is core feature, not add-on
4. **Full Functionality**: No need to sacrifice privacy for functionality
5. **End-to-End Security**: Data lifecycle fully protected
6. **Visibility and Transparency**: This policy is clear and transparent
7. **Respect for User Privacy**: User-centric, privacy-protecting

---

**Thank you for trusting AuraTime with your focus and sleep.**

We are committed to protecting your privacy by design.

---

*In case of inconsistency between Chinese and English versions, the Chinese version shall prevail.*
