<p align="center">
  <img src="assets/banner.jpg" alt="صيني عالخفيف | Sini Al-Khafif — AI-Powered Chinese Learning Platform for Arabic Speakers (HSK 1–6)" width="100%" />
</p>

<h1 align="center">🇨🇳 صيني عالخفيف | Sini Al-Khafif 🎓</h1>
<h3 align="center">AI-Powered Chinese Language Learning Platform for Arabic Speakers</h3>

<p align="center">
  <a href="https://sinialkhafifapp.com"><img src="https://img.shields.io/badge/Live-sinialkhafifapp.com-7A0C10?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live" /></a>
  <img src="https://img.shields.io/badge/Status-Production-16A34A?style=for-the-badge" alt="Status" />
  <img src="https://img.shields.io/badge/Curriculum-HSK%201--6-B91C1C?style=for-the-badge" alt="HSK 1-6" />
  <img src="https://img.shields.io/badge/Vocabulary-3000%2B%20words-0EA5E9?style=for-the-badge" alt="3000+ words" />
  <img src="https://img.shields.io/badge/UI-Arabic%20RTL-F97316?style=for-the-badge" alt="Arabic RTL" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/AI-Adaptive%20Engine-8B5CF6?style=flat-square&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/SEO-Structured%20Data-F59E0B?style=flat-square&logo=google&logoColor=white" />
</p>

---

**Sini Al-Khafif** is a state-of-the-art educational platform designed to take Arabic speakers from absolute beginners to advanced Chinese proficiency (HSK 1–6). By combining an adaptive learning engine with an intuitive Arabic interface, the platform offers a seamless and personalized learning journey.

**صيني عالخفيف** منصّة تعليمية ذكية تنقل الناطقين بالعربية من الصفر إلى الإتقان في اللغة الصينية عبر منهج HSK المعتمد، محرّك تعلّم تكيّفي يحلّل الأداء لحظياً، ومحتوى مبني على واقع الحياة اليومية — بواجهة عربية أصلية من اليمين إلى اليسار.

> 🌐 **منصّة حيّة في الإنتاج:** [https://sinialkhafifapp.com](https://sinialkhafifapp.com) — أكثر من 46 درساً تفاعلياً، قاموس صيني–عربي، ودليل HSK كامل.

---

## 🌟 Key Features | أبرز المزايا

<table>
<tr>
<td width="33%" align="center"><img src="assets/card-adaptive.jpg" alt="Adaptive learning engine" width="100%" /></td>
<td width="33%" align="center"><img src="assets/card-hsk.jpg" alt="HSK 1-6 curriculum ladder" width="100%" /></td>
<td width="33%" align="center"><img src="assets/card-skills.jpg" alt="Five integrated language skills" width="100%" /></td>
</tr>
<tr>
<td align="center"><b>🧠 Adaptive Learning Engine</b><br/><sub>محرّك تكيّفي يحلّل الأداء لحظياً ويعيد ترتيب المحتوى ليطابق نقاط الضعف</sub></td>
<td align="center"><b>🎓 HSK 1–6 Curriculum</b><br/><sub>تغطية كاملة لمنهج HSK بأكثر من 3,000 مفردة وعبارة أساسية</sub></td>
<td align="center"><b>🗣️ 5-Skill Integration</b><br/><sub>استماع، نطق، قراءة، كتابة الحروف، وتركيب الجمل في درس واحد متماسك</sub></td>
</tr>
</table>

- **Adaptive Learning Engine:** A real-time engine that analyzes student performance and dynamically adjusts the curriculum to focus on weak points.
- **HSK-Aligned Curriculum:** Full coverage of the HSK 1–6 standard, featuring over 3,000 essential words and phrases.
- **Real-Life Context:** Every word is taught within 6–9 practical, real-life sentences to ensure usage over rote memorization.
- **5-Skill Integration:** Integrated training for Listening, Speaking, Reading, Writing (Characters), and Sentence Construction.
- **Progress Tracking:** Detailed analytics and cloud-synced progress reports for every student.
- **Chinese–Arabic Dictionary:** Free HSK dictionary with pinyin, tones and Arabic meanings.
- **Free Interactive Trial:** Try a real lesson instantly — no signup required, progress saved locally.
- **Arabic-First RTL Experience:** Typography, layout and pedagogy designed natively for Arabic speakers.

---

## 📸 Platform Preview | جولة داخل المنصّة

### 🏠 Landing Page — `sinialkhafifapp.com`
![Sini Al-Khafif landing page — Chinese learning platform in Arabic](screenshots/home.jpg)

### 🧪 Interactive Lesson Demo & Platform Stats
![Interactive Chinese lesson demo and platform statistics](screenshots/demo.jpg)

### 🧭 Methodology — Four Academic Pillars
![Research-based learning methodology](screenshots/methodology.jpg)

### 🎓 HSK 1–6 Guide
![HSK 1 to 6 complete guide in Arabic](screenshots/hsk.jpg)

### 📗 HSK 1 Level Page
![HSK 1 vocabulary, grammar and starter test](screenshots/hsk1.jpg)

### 📚 Chinese–Arabic HSK Dictionary
![Chinese Arabic HSK dictionary with pinyin](screenshots/dictionary.jpg)

### ℹ️ About the Platform
![About Sini Al-Khafif](screenshots/about.jpg)

<sub>Original preview kept for reference: <code>screenshots/landing_page.webp</code></sub>

---

## 🏗️ Architecture | معمارية النظام

```mermaid
flowchart TD
    subgraph Client["🖥️ Client — Arabic RTL SPA"]
        A1["Lesson Player<br/>listen · speak · read · write"]
        A2["HSK Explorer & Dictionary"]
        A3["Learner Dashboard"]
    end

    subgraph API["⚡ API Layer"]
        B1["REST API Gateway"]
        B2["Auth & Profiles"]
        B3["Validation · Rate Limiting"]
    end

    subgraph Core["🧩 Learning Core"]
        C1["Adaptive Engine<br/>mastery estimation"]
        C2["Spaced Repetition<br/>SM-2 scheduler"]
        C3["Content Service<br/>HSK 1–6 · 3000+ items"]
        C4["Assessment & Scoring"]
        C5["Progress Analytics"]
    end

    subgraph Data["🗄️ Data Layer"]
        D1[("PostgreSQL<br/>vocab · lessons · attempts")]
        D2[("Audio & Media Storage")]
        D3[("Cloud Sync / Cache")]
    end

    A1 --> B1
    A2 --> B1
    A3 --> B1
    B1 --> B2 --> B3
    B3 --> C1 & C3 & C4 & C5
    C1 --> C2
    C2 --> D1
    C3 --> D1
    C3 --> D2
    C4 --> D1
    C5 --> D1
    C5 --> D3
```

### 🔄 Adaptive Learning Loop

```mermaid
sequenceDiagram
    participant L as 👤 Learner
    participant P as 🎧 Lesson Player
    participant E as 🧠 Adaptive Engine
    participant S as 🔁 SM-2 Scheduler
    participant D as 🗄️ Progress Store

    L->>P: Complete lesson item
    P->>E: Answer + latency + skill type
    E->>E: Update mastery per word & skill
    E->>S: Schedule next review interval
    S->>D: Persist review queue
    E-->>L: Next item tuned to weak points
    D-->>L: Mastery %, streak, level progress
```

---

## 🛠️ Tech Stack & Engineering Notes

| Layer | Technology | Engineering Notes |
|-------|-----------|-------------------|
| **Frontend** | React · TypeScript · TailwindCSS | RTL-first design system, accessible components, code-split routes |
| **Backend** | Scalable REST services | Adaptive logic, assessment scoring, progress aggregation |
| **Database** | PostgreSQL | Normalized vocab/lesson/attempt model, indexed lookups |
| **Algorithms** | Spaced Repetition (SM-2) | Per-word mastery decay and optimal review intervals |
| **Media** | Native-speaker audio pipeline | Pronunciation per word and per sentence |
| **Security** | Secure auth + cloud sync | Protected learner data, row-level access rules |
| **SEO** | Semantic HTML · metadata · structured data | Indexable HSK level pages with Arabic keyword targeting |
| **Performance** | Caching, lazy media, image optimization | Tuned for mobile and low-bandwidth networks |

**Engineering principles:** clean separation of concerns · deterministic scheduling · defensive validation · analytics-driven pedagogy · accessibility and RTL correctness · security by default.

---

## 🚀 Roadmap

- [ ] Speech recognition for pronunciation scoring (tones)
- [ ] Handwriting recognition for character writing practice
- [ ] Mobile apps (iOS / Android) with offline lessons
- [ ] AI conversation tutor for real dialogue practice
- [ ] Teacher/classroom dashboards and cohort analytics
- [ ] Public HSK dictionary API

---

## 🌐 Live Platform

| Section | Link |
|---------|------|
| 🏠 Home | https://sinialkhafifapp.com |
| 🎓 HSK 1–6 | https://sinialkhafifapp.com/hsk |
| 📗 HSK 1 | https://sinialkhafifapp.com/hsk/1 |
| 📚 Dictionary | https://sinialkhafifapp.com/dictionary |
| 🧭 Methodology | https://sinialkhafifapp.com/methodology |
| ℹ️ About | https://sinialkhafifapp.com/about |
| ✉️ Contact | https://sinialkhafifapp.com/contact |

---

## 👨‍💻 Developed By
**Majid Al-Sakani** — ماجد السكني
*Full Stack Developer | Backend Engineer | Automation Specialist*

<p align="center">
  <a href="https://github.com/majid-alsakani"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://sinialkhafifapp.com"><img src="https://img.shields.io/badge/Website-7A0C10?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
</p>

> If this project inspires you, please ⭐ **star the repository**.

---

<!--
Keywords / كلمات مفتاحية:
Sini Al-Khafif, sinialkhafifapp, صيني عالخفيف, تعلم الصينية, تعلم اللغة الصينية للعرب, اللغة الصينية بالعربي,
HSK, HSK 1, HSK 2, HSK 3, HSK 4, HSK 5, HSK 6, اختبار HSK, منهج HSK, مفردات HSK, قاموس صيني عربي, بينيين, pinyin,
learn Chinese, learn Mandarin, Chinese for Arabic speakers, Mandarin course, Chinese vocabulary, Chinese characters,
adaptive learning, spaced repetition, SM-2, AI tutor, edtech, e-learning platform, language learning app,
interactive lessons, pronunciation practice, listening speaking reading writing, progress tracking, learning analytics,
React, TypeScript, TailwindCSS, PostgreSQL, Supabase, REST API, RTL web app, Arabic UI, full stack developer,
Majid Al-Sakani, ماجد السكني, مبرمج يمني, مطور فل ستاك, منصة تعليمية ذكية, ذكاء اصطناعي, تعليم إلكتروني
-->

<p align="center">
  <em>Building the future of intelligent language education.</em><br/>
  <em>نبني مستقبل تعليم اللغات بالذكاء الاصطناعي.</em>
</p>
