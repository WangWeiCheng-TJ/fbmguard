# 📘 README (EN-only)

*This is the primary reference for project contributors. A [Traditional Chinese version](./看我.md) is available for background explanation.*

## 🐦 FBMGuard

A privacy-first, community-linked safety app inspired by the **Formosan Blue Magpie (FBM)** — a fiercely loyal and cooperative bird species. Just like these birds call to one another and defend their own when danger strikes, **FBMGuard** helps people silently alert nearby allies when they can’t protect themselves alone.

---

## 🌟 Overview

A **privacy-first, AI-assisted mobile app** designed to silently detect personal safety threats (e.g., physical restraint, robbery, muffled screaming) and trigger emergency alerts — *only if needed*. Our goal is to build something we **hope you never need**, but if you do — it’s ready.

---

## 🧠 Core Features

* Panic trigger (manual button or voice keyword)
* AI detection: muffled screams, violent motion
* Emergency response: peer alert or 911 call
* Helper Mode: passive receive-only mode
* Trusted escort request with ID tracking
* Smart scheduling: calendar or geozone triggers
* On-device processing: no background listening

---

## 🧭 Project Values

* 🚫 No user data monetization
* 🧑‍🤝‍🧑 Open to collaboration with NGOs and civic tech
* 🌍 Prioritizing accessibility, transparency, and ethical AI
* 💬 Built for and with the community

> "If no one ever has to use this, that’s success. But if someone does — let it be ready."

---

## 📦 Tech Stack (Planned MVP)

* **Flutter** or **React Native** frontend
* **TFLite** or **PyTorch Mobile** for on-device ML
* Peer alert via **Bluetooth LE / Wi-Fi Direct**
* Demo: GitHub + Hugging Face Spaces
* Backend (if needed): Firebase / Supabase / local-only logging

---

## 🤝 Contributing

We're in **early planning phase** (dev starts \~mid-June). If you’d like to help shape use cases, ethics, UI, or models — we welcome you.

➡ Join us on [GitHub Discussions](https://github.com/yourrepo/fbmguard/discussions), especially under **Use Cases & Constraints**.

Ways to help:

* Fork + prototype ideas
* Give feedback in Discussions
* Submit issues or PRs

By contributing, you agree to:

* Respect privacy-first, nonprofit values
* Follow repo license (Polyform Noncommercial)
* Allow reuse for aligned, noncommercial applications

> 💬 *Want to help with UI/UX, safety research, or ML? Let us know!*

---

## 📁 Repository Structure (Planned)

```bash
fbmguard/
├── README.md                # English (primary)
├── README.zh.md             # 中文說明（輔助背景與理念）
├── LICENSE.md
├── .github/
│   ├── ISSUE_TEMPLATE/
│   └── CONTRIBUTING.md
├── docs/
│   ├── 01_pitch.md
│   ├── 02_feature_spec.md
│   ├── 03_architecture.md
│   ├── 04_risks_drawbacks.md
│   ├── 05_roadmap_gantt.md
│   ├── 06_collaboration_notes.md
│   ├── 07_dev_log.md
│   └── ui_sketches/
├── prototype/
│   ├── mobile_app/
│   └── ml_models/
```

---

## 🔐 License

* Licensed under [Polyform Noncommercial](https://polyformproject.org/licenses/noncommercial/1.0.0/)
* Commercial use requires permission (see LICENSE.md)

---

## 🧭 Roadmap Highlights

* [ ] MVP passive detection (voice + motion)
* [ ] Privacy-safe peer mesh alerts
* [ ] Helper Mode field testing
* [ ] Escort feature with ID log
* [ ] NGO pilot partnership
* [ ] Optional safety heatmap
* [ ] On-device voice fingerprinting

---

## 📬 Contact & Credits

We welcome discussion via GitHub Issues or Discussions. This is a public-interest project — shaped by people like you.

> Built as a public good. Safety > ownership.