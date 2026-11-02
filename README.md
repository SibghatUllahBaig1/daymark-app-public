<div align="center">

# 🌅 Daymark — Daily Health & Wellness Tracker

**A privacy-first mobile app for daily check-ins, journaling, medications, nutrition and long-term insights — with clinician-ready PDF reports.**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![GetX](https://img.shields.io/badge/State-GetX-8A2BE2?style=flat-square)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![RevenueCat](https://img.shields.io/badge/RevenueCat-F2545B?style=flat-square)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)

<a href="https://play.google.com/store/apps/details?id=com.developlogix.daymark&hl=en"><img alt="Get it on Google Play" src="https://img.shields.io/badge/Google_Play-Download_Now-414141?style=for-the-badge&logo=google-play&logoColor=white"/></a>

</div>

> 🔒 **Source code is private** (commercial product). This page is a case study of what I designed and built end to end — product, UX, mobile app, backend and subscriptions.

---

## 🎯 The problem

Managing a health condition means remembering a lot: how you felt today, what you took, what you ate, and when things got worse. Most people rely on memory or scattered notes — then struggle to explain patterns to their doctor.

## 💡 The solution

**Daymark** turns a 60-second daily routine into a clear, long-term picture of your health. Log how you feel, track medications and meals, spot patterns in your insights, and export a clean PDF report to share with your care team.

---

## ✨ Key features

| Feature | What it does |
|---|---|
| ✅ **Daily check-ins** | Fast, structured daily check-in to capture mood and symptoms in under a minute. |
| 📓 **Journal** | Free-form notes with mood insights to reflect on good and bad days. |
| 💊 **Medication tracking** | Schedules, reminders and adherence history. |
| 🥗 **Nutrition & meal logging** | Log meals by **barcode scan** or **photo**, and get meal ideas. |
| 📈 **Insights & history** | Charts and trends across check-ins, meals and medications. |
| 🚩 **Relapse tracking** | Record setbacks and see what they correlate with. |
| 📄 **PDF export** | Clinician-ready reports to share with doctors. |
| ⏰ **Smart local reminders** | Timezone-aware notifications that work offline. |
| 💎 **Pro subscription** | Premium features gated behind in-app subscriptions (RevenueCat). |
| 🔐 **Secure sign-in** | Email, Google and Apple sign-in with onboarding and profile management. |

---

## 🏗️ Architecture & engineering highlights

- **Feature-first architecture** — `auth · check_in · dashboard · history · insights · journal · medications · nutrition · relapses · reminders · subscription · export · onboarding · profile · settings`, each self-contained.
- **GetX** for state, dependency injection and navigation.
- **Firebase backend** — Authentication, Cloud Firestore, Cloud Storage, Cloud Messaging, Cloud Functions and Analytics.
- **Hardened security rules** — Firestore and Storage rules written so each user can only ever access their own data.
- **Subscriptions done right** — RevenueCat integration with entitlement-based feature gating (Pro-only features, graceful upgrade prompts).
- **On-device PDF generation** — reports rendered locally with proper font handling for international text.
- **Barcode scanning & image capture** — `mobile_scanner` + `image_picker` for fast meal logging.
- **Reliable reminders** — local notifications with timezone support, tested across iOS and Android edge cases.
- **Production-audited** — dedicated production-readiness pass covering UX, edge cases, offline behaviour and store requirements.

## 🧰 Tech stack

**Flutter · Dart · GetX · Firebase Auth · Cloud Firestore · Firebase Storage · Cloud Functions · FCM · Firebase Analytics · RevenueCat · Google & Apple Sign-In · fl_chart · mobile_scanner · PDF/printing · flutter_local_notifications**

---

## 📸 Screenshots & links

<!-- Add screenshots: <img src="screenshots/home.png" width="220"/> -->
📲 **[Download Daymark on Google Play](https://play.google.com/store/apps/details?id=com.developlogix.daymark&hl=en)**
*Screenshots and demo available on request.*

---

## 🤝 Want an app like this?

I build production-ready mobile apps — authentication, subscriptions, analytics, backend and store release — from idea to App Store.

📫 **sibghat.developlogix@gmail.com** · 🌐 **[developlogix.com](https://www.developlogix.com)** · 💼 **[LinkedIn](https://www.linkedin.com/in/sibghat-ullah-baig-4a2812a1)**

<sub>Built by [Develop Logix](https://www.developlogix.com)</sub>
