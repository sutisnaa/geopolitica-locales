# 🌍 GEOPOLITICA - Official Community Localization
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/sutisnaa/geopolitica-locales/pulls)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)
[![Game Version](https://img.shields.io/badge/GEOPOLITICA-Alpha%20Phase-blue.svg?style=flat-square)](https://playgeopolitica.com)
Welcome to the official community localization repository for **GEOPOLITICA** (Persistent Browser-Based Geopolitical Sandbox MMO). This repository holds all translation files used in the game.
We welcome contributions from players and translators worldwide to bring GEOPOLITICA to your native language!
---
## 🗺️ Supported Languages & Status

| Language Code | Language | Status | Maintainer / Contributors |
| :--- | :--- | :--- | :--- |
| `en` | **English** *(Master)* | 🟢 100% | Core Development Team |
| `id` | **Indonesian** *(Official)* | 🟢 100% | Core Development Team |
| `es` | **Spanish** | ⚪ 0% | *Looking for contributors!* |
| `ru` | **Russian** | ⚪ 0% | *Looking for contributors!* |
| `de` | **German** | ⚪ 0% | *Looking for contributors!* |
| `fr` | **French** | ⚪ 0% | *Looking for contributors!* |
| `zh` | **Chinese (Simplified)** | ⚪ 0% | *Looking for contributors!* |
| `tr` | **Turkish** | ⚪ 0% | *Looking for contributors!* |
| `pt` | **Portuguese** | ⚪ 0% | *Looking for contributors!* |

> *Want to add a new language? Simply create a new file in `locales/{code}.json` using the 2-letter ISO 639-1 code!*
---
## 🚀 Step-by-Step Contribution Guide
### 1. Fork & Clone
1. Click the **Fork** button at the top right of this repository.
2. Clone your forked repository to your computer:
   git clone [https://github.com/YOUR_USERNAME/geopolitica-locales.git](https://github.com/YOUR_USERNAME/geopolitica-locales.git)
   cd geopolitica-locales
### 2. Edit or Create a Language File
Navigate to the `locales/` folder:
- **To improve an existing language:** Open `locales/en.json`, `locales/id.json`, etc.
- **To add a new language:** Copy `locales/en.json` and rename it to your language code (e.g. `locales/es.json` for Spanish).
### 3. Translate the Values
Only translate the values on the right side of the JSON pairs. Never modify the keys on the left side!
**Correct Example:**
{
  "dash": {
    "commodity_exchange": "Bursa Komoditas"
  }
}
**Incorrect Example (DO NOT DO THIS):**
{
  "dash": {
    "bursa_komoditas": "Bursa Komoditas"  <-- BAD! Key name was altered.
  }
}
### 4. Validate Your JSON
Before submitting, make sure your JSON syntax is valid. You can test your JSON online using JSONLint.
### 5. Submit a Pull Request (PR)
1. Commit your changes:
   git add .
   git commit -m "i18n: Add Spanish translation (es.json)"
   git push origin main
2. Open a **Pull Request** on GitHub toward our main branch.
3. Our team will review your PR and merge it into the live game!
---
## ⚠️ Important Translation Rules
1. **Keep Dynamic Variables Intact:** Text containing parameters inside `{}` (e.g., `{score}`, `{region}`, `{hours}`, `{rate}`) must keep the exact parameter names.
   - **English:** `"Ends in {hours}h {mins}m"`
   - **Spanish:** `"Termina en {hours}h {mins}m"`
   - **Indonesian:** `"Sisa {hours}j {mins}m"`
2. **Maintain Game Terminology:** Keep geopolitical, military, and economic terms consistent across the file (e.g., State, Region, Embargo, Tariff, Vault, President, Parliament).
3. **No Hate Speech or Profanity:** Translations containing real-world political hate speech, inappropriate slurs, or vandalism will be rejected immediately.
---
## 📜 License
By contributing to GEOPOLITICA Community Localization, you agree that your contributions will be licensed under the MIT License.
