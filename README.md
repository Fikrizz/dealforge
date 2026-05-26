# 🎯 DealForge

> AI negotiation coach & simulator

Practice salary, raise, vendor, and deal negotiations with an AI counterpart. Get scripts, counter-tactics, and BATNA analysis.

## ✨ Features

- Position strength scoring (weak/neutral/strong/dominant) + reasoning
- Word-for-word opening script
- Anchor value strategy with justification & how to drop it
- Top arguments with evidence + why each one lands
- Likely counter-objections + responses + named tactics (Voss/Harvard frameworks)
- Tactical phrases (calibrated questions, mirroring, labeling)
- BATNA analysis: yours, theirs, ZOPA estimate
- Walk-away signals + exact walk-away script
- 6 cultural contexts (US/CN/JP/SEA/EU/ME)
- Follow-up email draft included
- 7 negotiation types (job/raise/vendor/freelance/partnership/purchase/conflict)
- Multi-language UI (English / 中文)
- BYOK Xiaomi MiMo API support with free Pollinations fallback
- Zero dependencies, single-file HTML

## 🚀 Quick Deploy

### Vercel (drag-drop, paling cepat)
1. Buka [vercel.com/new](https://vercel.com/new)
2. Drag folder `dealforge/` ke area drop
3. Klik Deploy. URL hidup dalam 30 detik.

### Local
```bash
cd dealforge
python3 -m http.server 8000
# buka http://localhost:8000
```

## 🔑 Setup MiMo API Key (recommended)

1. Klik **⚙** di header
2. Paste API key dari [api.xiaomimimo.com](https://api.xiaomimimo.com)
3. Test Connection → Save

Tanpa API key, app pakai Pollinations free endpoint (terbatas, demo only).

## 🏗️ Stack

- Single-file HTML, vanilla JS, zero dependencies
- Xiaomi MiMo V2.5 (primary) → Pollinations (fallback)
- localStorage untuk settings, no server

## 📦 Built for

[**MiMo 100T Creator Program**](https://100t.xiaomimimo.com)

## 📄 License

MIT — fork, modify, gunakan komersial bebas.

---

Made by [@Fikrizz](https://github.com/Fikrizz) · Powered by Xiaomi MiMo
