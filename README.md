# <div align="center">
# NourishDoc
### Women's Health & Wellness App for iOS & Android

A production-grade health and wellness app combining daily habit
tracking, menstrual cycle monitoring, expert coach sessions, guided
programs, and AI-driven insights live on App Store and Google Play.

[![Platform](https://img.shields.io/badge/Platform-iOS%20%26%20Android-blue?style=flat-square)]()
[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)]()
[![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)]()
[![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)]()
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)]()
[![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)]()

</div>

---

## Screenshots

<div align="center">
<img src="screenshots/screen1.png" width="200"/>
<img src="screenshots/screen2.png" width="200"/>
<img src="screenshots/screen3.png" width="200"/>
<img src="screenshots/screen4.png" width="200"/>
</div>

---

## Overview

NourishDoc is a comprehensive women's health and wellness app live
on both the App Store and Google Play. It combines personal health
tracking with structured expert-led content, certified coach access,
and AI-powered daily insights all in a single cross-platform
Flutter app.

---

## Live on Stores

- App Store: https://apps.apple.com/us/app/nourishdoc-midlife-wellness/id6743374362
- Google Play: https://play.google.com/store/apps/details?id=com.nourishdoc.app

---

## Key Features

### Daily Health Tracking
- Nutrition, mood, sleep and lifestyle metric tracking
- Personalised daily summaries and AI-driven insights
- Streak-based habit tracker with progress views

### Cycle Tracking
- Menstrual cycle calendar with predictive notifications
- Ovulation alerts and period reminders
- Cycle history and pattern analysis

### Coach & Community
- 1-on-1 coach booking and live chat sessions
- Community discussion threads and group support
- Verified wellness coach profiles

### Guided Programs
- Programs organized as Programs, Modules and Sessions
- Four content formats: video, audio, image and quiz
- Tier-based access gated by subscription plan

### Monetisation
- Apple App Store and Google Play in-app purchases
- Recurring subscription billing with tiered plans
- Premium program and coach session gating

### Notifications
- Firebase Cloud Messaging push notifications
- Daily habit reminders and cycle alerts
- Coach message notifications in real time

---

## Tech Stack

| Layer | Technology |
|---|---|
| Mobile Frontend | Flutter, Dart |
| Backend API | Python, Django, REST API |
| Cloud | AWS EC2, AWS S3 |
| Push Notifications | Firebase Cloud Messaging |
| Authentication | Firebase Auth |
| Real-Time Chat | WebSockets |
| Monetisation | In-App Purchases, Subscriptions |
| Deployment | iOS, Android |

---

## Architecture

```
User opens app and completes onboarding
        ↓
Daily tracking data saved to Django REST API on AWS
        ↓
AI engine generates personalised daily insights
        ↓
Cycle prediction engine updates notifications via FCM
        ↓
User browses Programs and selects a Module
        ↓
Content delivered in video, audio, image or quiz format
        ↓
User books a 1-on-1 coach session
        ↓
Real-time chat opens via WebSocket connection
        ↓
Subscription billing gates premium content via IAP
```

---

## Project Structure

```
lib/
├── core/           # theme, constants, utils
├── features/
│   ├── auth/       # login, register, onboarding
│   ├── tracking/   # habit, cycle, nutrition, mood
│   ├── programs/   # programs, modules, sessions
│   ├── coaching/   # coach booking, live chat
│   ├── community/  # discussion threads, groups
│   ├── insights/   # AI-driven daily summaries
│   └── billing/    # subscriptions, IAP
├── shared/         # reusable widgets, components
└── services/       # API clients, Firebase, AWS
```

---

## Target Users

- Women tracking menstrual health and wellness
- Users following structured wellness programs
- Individuals working with certified wellness coaches
- Health-conscious users building daily habits

---

## Status

Live in production on App Store and Google Play with active users.
Ongoing feature development and maintenance.

---

## Developer

**Hussain Ahmed**
Senior Flutter and Mobile AI Developer
8 years experience, 30+ production apps shipped

- Upwork: (https://www.upwork.com/freelancers/~01364d92ed7bc15724)
- Email: hussainxbot1c@gmail.com
- MixerCloud: https://apps.apple.com/us/app/mixercloud/id6740339899
- Beautora: https://apps.apple.com/us/app/beautora/id6745489516
- OsteoViewer: Coming soon to App Store

---

<div align="center">
Built with Flutter · Django · AWS · Firebase · WebSockets
</div>
