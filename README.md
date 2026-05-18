# 🎬 Social Cover Lab

> AI-powered cover generator for **ALL** social platforms — RedNote · TikTok · YouTube · Instagram

Upload a photo → pick a style → AI generates your cover in 10 seconds. **No API key. No setup.**

[![Website](https://img.shields.io/badge/🌐-Website-purple)](https://nestvive.github.io/Social-Cover-Lab/)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
[![Styles](https://img.shields.io/badge/styles-37-orange)]()

---

## ✨ Why Social Cover Lab?

| | Social Cover Lab | xhs-cover | Pikzels | Canva |
|------|:---:|:---:|:---:|:---:|
| RedNote/Xiaohongshu | ✅ | ✅ | ❌ | ⚠️ Template |
| TikTok/Douyin | ✅ | ❌ | ❌ | ⚠️ Template |
| YouTube | ✅ | ❌ | ✅ | ⚠️ Template |
| Instagram | ✅ | ❌ | ❌ | ⚠️ Template |
| AI Generation | ✅ Real AI | ✅ | ✅ | ❌ Templates |
| No API Key | ✅ | ❌ | ✅ | - |
| Free Tier | ✅ | ✅ | ❌ | ✅ |
| Price (Pro) | $12/mo | Free | $14/mo | $13/mo |

The **only** tool that covers all 4 major platforms with real AI generation.

---

## 🚀 Quick Start

### Option 1: EasyClaw Skill (built-in)
Just say "生成封面" in any EasyClaw conversation. Zero setup.

### Option 2: Web Demo
Visit [nestvive.github.io/Social-Cover-Lab/app.html](https://nestvive.github.io/Social-Cover-Lab/app.html)

### Option 3: CLI
```bash
python3 scripts/generate.py \
  --image "photo.jpg" \
  --title "Your Title" \
  --style "hand-drawn-border" \
  --platform "xiaohongshu" \
  --output "cover.jpg"
```

---

## 🎨 37 Styles Across 4 Platforms

### 📕 RedNote / Xiaohongshu (3:4) — 18 styles
hand-drawn-border · background-big-text · sticker-energy · home-motivation · study-room-intellectual · neon-contrast · split-screen-tags · dashed-decoration · professional-woman · cozy-home · dark-glow · outdoor-handwriting · multi-layer-layout · pink-yellow-playful · professional-clean · thinking-question · workplace-big-text · yellow-pink-banner

### 🎵 TikTok / Douyin (9:16) — 7 styles
trending-fire · hook-first-3s · text-reveal · challenge-badge · health-science · comedy-talk · money-talk

### ▶️ YouTube (16:9) — 6 styles
reaction-face · vs-battle · tutorial-steps · clickbait-arrow · results-showcase · podcast-style

### 📷 Instagram (1:1) — 6 styles
aesthetic-minimal · carousel-teaser · quote-overlay · lifestyle-magazine · color-block · daily-diary

---

## 💰 Pricing

| Plan | Price | Features |
|------|-------|----------|
| **Free** | $0 | 1 platform, 8 styles, 10/day |
| **Pro** | $12/mo | All platforms, 37 styles, unlimited, 4K |
| **Agency** | $49/mo | API access, 5 seats, batch gen |

---

## 🛠 Tech Stack

- **AI Model**: Gemini 3 Pro Image (Nano Banana Pro)
- **Frontend**: HTML/CSS/JS (landing page + web demo)
- **Backend**: Python CLI + EasyClaw skill framework
- **Style Engine**: Structured prompt templates with 4D design system (layout, typography, effects, atmosphere)

---

## 🙏 Credits

Inspired by [xhs-cover](https://github.com/Vivixiao980/xhs-cover-skill) by Vivi. We took the concept and made it work everywhere.

---

## 📄 License

MIT — free to use, modify, and distribute. Pro plan features require commercial license.

---

_Made with ❤️ for creators who publish everywhere._
