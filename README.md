# AI Government Scheme Eligibility Assistant

A lightweight, single-file AI web app that helps Indian citizens discover government schemes they are eligible for — powered by Google Gemini AI.

---

## 🔍 What It Does

Users fill in a simple profile form (age, income, caste, state, occupation, etc.) and the app uses a Gemini-powered AI engine to evaluate eligibility across 8–12 central and state government schemes in seconds. Results include:

- ✅ Schemes the user qualifies for (with benefit details and where to apply)
- ⚠️ Borderline schemes to verify
- 📍 A clear next step to begin applying

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| AI Engine | Google Gemini 2.0 Flash API |
| Hosting | None required — runs locally in browser |
| Dependencies | Zero — no npm, no frameworks, no build step |

---

## 📁 Project Structure

```
scheme_eligibility_assistant.html   ← entire app in one file
README.md                           ← this file
```

---

## 🚀 How to Run

**Step 1 — Get a free Gemini API key**

1. Go to [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
2. Sign in with your Google account
3. Click **Create API Key** and copy it

**Step 2 — Open the app**

Just double-click `scheme_eligibility_assistant.html` — it opens directly in Chrome or Edge. No server needed.

**Step 3 — Use it**

1. Paste your API key in the key field at the top
2. Fill in the profile form
3. Click **Check My Eligibility**
4. Results appear in 5–10 seconds

---

## ✨ Features

- **Zero setup** — single HTML file, works offline (except the AI call)
- **Comprehensive profile inputs** — age, gender, income, state, occupation, caste, BPL status, disability, and situational checkboxes
- **All 29 Indian states** supported
- **Real scheme recommendations** — central + state level schemes with benefit amounts and official apply links
- **Clean professional UI** — interview and demo ready
- **Secure** — API key stays in your browser, never stored

---

## 🧠 How It Works (Architecture)

```
User Input (Form)
      ↓
Data Ingestion Layer
  → Collects and structures profile fields into a formatted string
      ↓
Inference Layer
  → Sends structured profile to Gemini API with a custom prompt
  → Prompt instructs the model to act as a scheme eligibility advisor
      ↓
Output Formatting Layer
  → Parses AI response
  → Displays ✅ qualified schemes, ⚠️ borderline schemes, 📍 next steps
```

The three-layer separation (ingestion → inference → output) makes it easy to add new schemes, swap AI models, or extend the form without touching other layers.

---

## 🏛️ Sample Schemes Covered

Depending on the user's profile, the app evaluates schemes like:

- PM Kisan Samman Nidhi
- PM Awas Yojana (Urban & Rural)
- Ayushman Bharat – PM-JAY
- PM Mudra Yojana
- National Scholarship Portal schemes
- PM Ujjwala Yojana
- Sukanya Samriddhi Yojana
- PM SVANidhi
- Startup India / Stand Up India
- State-specific schemes based on selected state

---

## ⚠️ Disclaimer

This tool provides general guidance only. Always verify eligibility on official government portals such as [myscheme.gov.in](https://myscheme.gov.in) before applying.

---

## 👤 Author

**Akshay Kumar**
B.Tech – Computer Science & Data Science, JSS Academy of Technical Education, Noida
[linkedin.com/in/akshay21131](https://linkedin.com/in/akshay21131) · [github.com/akshay21131](https://github.com/akshay21131)

Founder, PROTEANZ | AI/ML Developer
