# 🛡️ FraudShield

**Check it before you tap.**

FraudShield is an educational scam-message explainer designed for internet users in India. It helps users understand suspicious SMS, WhatsApp messages, and emails by highlighting common manipulation tactics, explaining potential warning signs, and suggesting appropriate next steps.

Users can paste suspicious message text or upload a screenshot and explore explanations in **English, Hinglish, and Hindi**.

🌐 **Live Demo:** https://fraudshield-fawn.vercel.app/

## ✨ Features

- **🚩 Risk Flag System:** Every demo analysis displays a score out of 100 with a colour-coded risk level.

  | Score | Flag | Meaning |
  |---|---|---|
  | 0–25 | 🟢 Green | Looks safe |
  | 26–50 | 🟡 Yellow | Be careful; verify first |
  | 51–75 | 🟠 Orange | High risk |
  | 76–100 | 🔴 Red | Scam alert |

- **🧠 Scam Psychology Explainer:** Highlights manipulation tactics such as fake urgency, fake authority, suspicious websites, and greed bait. Explains these tactics in simple language.

- **📩 Interactive Demo Messages:** Includes four sample messages representing different risk levels.

- **🌐 Multilingual Support:** Switch between English, Hinglish, and हिन्दी. Language preferences are remembered in the browser.

- **🔊 Voice Explanations:** Uses the Web Speech API to read explanations aloud.

- **📚 Common Scams Library:** Includes examples of Indian-style scams, such as:
  - Bank reward-points APK scams
  - Courier redelivery fee scams
  - Fake part-time job offers
  - Amazon Prime renewal scams
  - Fake Windows security pop-ups
  - Electricity power-cut SMS scams

- **🚨 Emergency Response Guide:** Provides recommended steps to take after a suspected scam, including calling **1930**, reporting at [cybercrime.gov.in](https://cybercrime.gov.in), and using [Sanchar Saathi](https://sancharsaathi.gov.in).

- **⚠️ Post-Scam Safety Tips:** Explains six common mistakes to avoid after encountering a scam.

- **🔒 Privacy and Terms:** Includes Privacy Guarantee and Terms of Service pop-ups.

## 🧪 Demo Status and Limitations

FraudShield is currently a **frontend-only prototype** developed as a college hackathon project.

- No backend or AI/ML model has been integrated yet.
- Screenshot uploads currently display an example result rather than performing actual image or message analysis.
- Demo buttons display predefined examples and risk scores.
- Scam messages are illustrative examples based on common scam patterns. Phone numbers and links are masked or fictional.
- Uploaded screenshots remain in the browser and are not sent to a server.

The current version demonstrates the user interface, educational content, and intended functionality of the proposed system.

## 🚀 Live Deployment

FraudShield is deployed using **Vercel**.

Visit: https://fraudshield-fawn.vercel.app/

## 💻 Run Locally

No build process or package installation is required.

1. Clone the repository:

   ```bash
   git clone https://github.com/SanjanaSingh29/FraudShield.git
   ```

2. Open the project folder:

   ```bash
   cd FraudShield
   ```

3. Start a local server:

   ```bash
   python -m http.server 8000
   ```

4. Open the following URL in your browser:

   ```text
   http://localhost:8000
   ```

An internet connection is required to load Tailwind CSS through its CDN and Google Fonts.

## 🛠️ Tech Stack

- **HTML5** – Website structure
- **CSS3** – Custom styling
- **JavaScript** – Frontend functionality and interactions
- **Tailwind CSS (CDN)** – Utility-based styling
- **Google Fonts** – Plus Jakarta Sans and Noto Sans Devanagari
- **Material Symbols** – Interface icons
- **Web Speech API** – Voice explanations
- **Vercel** – Frontend deployment
- **Git & GitHub** – Version control and collaboration

## 📁 Project Structure

```text
FraudShield/
│
├── frontend/
│   ├── css/
│   │   └── style.css
│   │
│   └── js/
│       ├── data/
│       │   ├── demos.js
│       │   ├── scams.js
│       │   └── legal.js
│       │
│       ├── tailwind_config.js
│       ├── i18n.js
│       └── app.js
│
├── backend/
│
├── ai_recommendation/
│
├── index.html
└── README.md
```

*Note: The backend and AI recommendation directories are reserved for future development.*

## 📌 Where to Make Changes

| File | Purpose |
|---|---|
| `frontend/css/style.css` | Custom styles |
| `frontend/js/tailwind_config.js` | Tailwind theme, colours, fonts, and spacing |
| `frontend/js/data/demos.js` | Demo messages and risk scores |
| `frontend/js/data/scams.js` | Common scam examples |
| `frontend/js/data/legal.js` | Privacy and Terms content |
| `frontend/js/i18n.js` | English, Hinglish, and Hindi translations |
| `frontend/js/app.js` | Application logic, language switching, voice, uploads, and pop-ups |
| `index.html` | Main website structure |

The JavaScript files are loaded using standard HTML script tags in the following order:

1. `demos.js`
2. `scams.js`
3. `legal.js`
4. `i18n.js`
5. `app.js`

## 🇮🇳 If You Encounter a Scam in India

- **Call 1930:** Contact the National Cyber Crime Helpline immediately if you have lost money through cyber fraud.
- **Report online:** Visit [National Cyber Crime Reporting Portal](https://cybercrime.gov.in).
- **Report suspicious communication:** Use [Sanchar Saathi](https://sancharsaathi.gov.in).

## ⚠️ Disclaimer

FraudShield is an educational prototype and is not a substitute for professional cybersecurity investigation.

A low-risk or "Safe" result does not guarantee that a message is legitimate. Always verify suspicious communications through official websites, applications, or verified customer-support channels.

FraudShield does not currently provide real AI-powered scam detection, legal advice, or financial advice.

---

**Built with the goal of making digital safety easier to understand for everyone.**

🛡️ *Think before you tap. Stay alert. Stay safe.*
