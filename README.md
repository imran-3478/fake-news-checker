# 🔍 সত্যি নাকি গুজব? — Bangla Fake News Checker

> **শেয়ার করার আগে মাত্র ১০ সেকেন্ডে যাচাই করো — খবরটা আসল নাকি গুজব?**

A simple, free and open-source web tool that helps Bangladeshi Facebook users check a news item **before sharing it**. Paste the news text or a link, tap one button, and get a colour-coded verdict with clear reasons in Bangla.

👨‍💻 **Created by [Imran Akanda](https://github.com/imran-3478)**

## 🌐 Live Demo

**https://imran-3478.github.io/fake-news-checker/**

## ✨ Features

- 📋 **Paste & check** — paste news text or a link, get a verdict in seconds
- 🚦 **Colour verdict** — 🔴 likely fake / 🟡 suspicious / 🟢 looks reliable, with a 0–100% risk score
- 🧾 **Reasons in simple Bangla** — clickbait language, share-pressure phrases, money/miracle scams, ALL-CAPS shouting, emoji overload, unknown or free-blog sources, satire-site detection, and trusted-source recognition
- 📤 **Shareable result** — one tap shares the verdict to WhatsApp or Facebook, so friends check before they share too
- 🎯 **Built-in examples** — try a fake news, a real-style news and a suspicious link instantly
- 📱 **Mobile-first** — designed for phone users, no login, no install, works fully in the browser

## ⚙️ How it works

The checker analyses signals in the text and the source — it does **not** read anyone's Facebook feed (Meta does not allow that). It looks for:

1. Clickbait / sensational phrases (Bangla + English)
2. "Share this now" pressure language
3. Money, lottery and miracle-cure scam patterns
4. Excessive `!`, ALL CAPS words and emoji density
5. Missing source/attribution in the text
6. The source domain — trusted news outlets, free blog platforms, or known satire sites

> ⚠️ The verdict is a **signal-based first impression**, not a final fact-check. For important news, always cross-check with professional fact-checkers like [Rumor Scanner](https://rumorscanner.com) and [Dismislab](https://dismislab.com).

## 🚀 Run it yourself

It's a single static file — no build, no server:

1. Download `index.html`
2. Open it in any browser — done!

Or fork this repo and enable **GitHub Pages** (Settings → Pages → Deploy from branch `main`) to host your own copy for free.

## 🤝 Contributing

Contributions are welcome! Ideas:

- Add more Bangla clickbait/scam phrases
- Improve the trusted/satire domain lists
- Translate the UI
- Suggest better signals

Open an issue or a pull request.

## 📄 License

MIT License — free for everyone to use, copy and improve. See [LICENSE](LICENSE).

Copyright (c) 2026 **Imran Akanda**

---

❤️ *গুজবমুক্ত বাংলাদেশের জন্য — শেয়ার করার আগে যাচাই করো।*
