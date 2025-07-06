# 🛡️ TRS Matrix Controller (`sentinel-cli`)

A command-line interface and real-time status engine for **TRS Alliance** — designed to defend creators, protect the truth, and track trust across Netlify, Firebase, and live metadata.

---

## ✨ Features

- ✅ **Live System Status** via `SYSTEM_STATUS.ts`
- 🔧 **Command-driven Repair Simulations** (Netlify, Firebase, Neon DB, etc.)
- 🔖 **Version + Trust Metadata** via `version.json`
- 📡 **Deploy Witness Logs** via `system_pulse.json`
- 🧠 **CLI-Like Interface** for ethical debugging and transparent system reflection
- ⚙️ **Integrated with TRS Deploy Lock & Pulse Validation**

---

## 📦 Structure

```bash
.github/workflows/
├── firebase-deploy.yml
├── trs15-deploy.yml

meta/functions/
├── system_pulse.json
├── SYSTEM_STATUS.ts
├── version.json

