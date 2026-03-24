# ⚖️ IAReferee — AI-Powered Dispute Resolution Tool

> **Resolve freelance and business disputes instantly using AI.** IAReferee is a neutral, document-based dispute resolution platform built for clients and providers who want fast, fair, and transparent conflict resolution — no lawyers required.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20App-4F8EF7?style=for-the-badge&logo=github)](https://h-tech-afaq-ceo.github.io/AI-Dispute-Resolution-Tool-MVP/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![HTML5](https://img.shields.io/badge/Built%20With-HTML5%20%2F%20CSS3%20%2F%20JS-orange?style=for-the-badge&logo=html5)](https://h-tech-afaq-ceo.github.io/AI-Dispute-Resolution-Tool-MVP/)
[![AI Powered](https://img.shields.io/badge/AI-Claude%20Sonnet-purple?style=for-the-badge&logo=anthropic)](https://anthropic.com)

---

## 🌐 Live Demo

🔗 **[https://h-tech-afaq-ceo.github.io/AI-Dispute-Resolution-Tool-MVP/](https://h-tech-afaq-ceo.github.io/AI-Dispute-Resolution-Tool-MVP/)**

No login required. Explore the full UI, submit test disputes, and see AI rulings in action.

---

## 📸 Screenshots

> Dashboard · Sessions · AI Rulings · Document Management · Dispute Flow

The platform features a professional dark/light mode dashboard with real-time session tracking, document approval workflows, and AI-generated rulings with confidence scores.

---

## 🚀 What Is IAReferee?

**IAReferee** is an open-source MVP for an **AI dispute resolution SaaS platform** designed for:

- Freelancers and clients in contract disputes
- Software agencies and product owners
- Any two parties who need a neutral, document-grounded arbitration tool

Instead of expensive lawyers or slow mediation services, IAReferee lets both parties upload their contracts and evidence, submit a dispute statement, and receive an **AI-generated ruling with document citations** — all in minutes.

---

## ✨ Key Features

### 🧑‍⚖️ AI-Powered Rulings
- Submit a dispute and receive a neutral AI verdict
- Every ruling cites the **exact document section** that supports the decision
- Confidence score (e.g. 87%) shown with each ruling
- Supports "In Favor of Party A", "In Favor of Party B", or "Split Decision" outcomes

### 📁 Document Management
- Upload PDF, DOCX, and TXT files per session
- Both parties must approve documents before they enter evidence
- Full document audit trail with upload timestamps and party attribution

### 🤝 Dual-Party Session Workflow
- Step-by-step guided session creation (Setup → Parties → Documents → Agreement → Launch)
- Both parties must digitally sign the IAReferee Agreement before any dispute is processed
- Disputes must be accepted by **both parties** before AI analysis begins — no surprises

### 📊 Dashboard & Analytics
- Live session activity chart (7-day view)
- Ruling outcome breakdown (doughnut chart)
- Stats: Active Sessions, Open Disputes, Rulings Issued, Documents Approved

### 💬 AI Assistant Chat
- Ask natural language questions about your documents
- Pre-loaded quick prompts for common queries
- Full conversation history with session context awareness

### 🔔 Notifications & Activity Log
- Real-time notification feed with unread badges
- Full audit log with INFO / SUCCESS / WARN / ERROR levels
- Exportable CSV log

### 💳 Billing & Plans
- Starter (€15/mo), Professional (€49/mo), Enterprise (€149/mo)
- Invoice history with PDF download
- Usage tracking (sessions used vs. plan limit)

### ⚙️ Settings
- Profile & timezone management
- AI model selection (Claude 3.5 Sonnet, Opus, Haiku)
- Custom system prompt for AI behavior
- 2FA, session expiry, dark/light mode toggle
- Webhook, Slack, and Google Drive integrations

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3 (CSS Variables), Vanilla JavaScript |
| Charts | Chart.js 4.4.1 |
| Icons | Font Awesome 6.5.1 |
| Fonts | DM Sans + DM Mono (Google Fonts) |
| AI Engine | Anthropic Claude (via API) |
| Hosting | GitHub Pages |
| Date Utils | Day.js |

**No frameworks. No build tools. No dependencies to install.** Pure browser-native code — open `index.html` and it works.

---

## 📂 Project Structure

```
AI-Dispute-Resolution-Tool-MVP/
│
├── index.html          # Complete single-file application
└── README.md           # This file
```

The entire application is a **single HTML file** — intentionally designed for maximum portability, easy embedding, and zero setup friction.

---

## ⚡ Getting Started

### Option 1 — Use the Live Demo
Visit: **[https://h-tech-afaq-ceo.github.io/AI-Dispute-Resolution-Tool-MVP/](https://h-tech-afaq-ceo.github.io/AI-Dispute-Resolution-Tool-MVP/)**

### Option 2 — Run Locally
```bash
# Clone the repository
git clone https://github.com/h-tech-afaq-ceo/AI-Dispute-Resolution-Tool-MVP.git

# Open in browser (no server needed)
cd AI-Dispute-Resolution-Tool-MVP
open index.html
```

### Option 3 — Fork & Deploy to GitHub Pages
1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to `main` branch → `/ (root)`
4. Your live URL: `https://YOUR-USERNAME.github.io/AI-Dispute-Resolution-Tool-MVP/`

---

## 🔄 How It Works — The Dispute Flow

```
1. Create Session
   └─ Both parties invited with unique session code (e.g. IAR-2024-0042)

2. Upload Documents
   └─ PDF/DOCX contracts, scope docs, email threads
   └─ Both parties approve each document

3. Submit Dispute
   └─ One party submits a dispute statement
   └─ Other party must accept before AI analysis begins

4. AI Analysis
   └─ AI reads all approved documents
   └─ Issues a ruling with document citation + confidence score

5. Outcome
   └─ Both parties accept or appeal the ruling
   └─ Full audit trail generated
```

---

## 🧑‍💻 Use Cases

- **Freelance developers** disputing scope creep with a client
- **Design agencies** resolving deliverable acceptance disagreements
- **SaaS companies** settling contractual payment milestones
- **Remote teams** mediating project management conflicts
- **Legal tech demos** showing AI-assisted arbitration workflows

---

## 🗺️ Roadmap

- [ ] Real Anthropic API integration (live AI rulings)
- [ ] PDF export of rulings with watermark
- [ ] Multi-language support (English, Spanish, Arabic)
- [ ] Email invitations for parties
- [ ] Stripe payment integration
- [ ] Mobile-responsive layout improvements
- [ ] User authentication (Supabase / Firebase)
- [ ] Document OCR for scanned PDFs
- [ ] Webhook event triggers

---

## 🤝 Contributing

Contributions are welcome! Here's how to get started:

1. **Fork** the repository
2. Create a feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m 'Add: my feature description'`
4. Push to branch: `git push origin feature/my-feature`
5. Open a **Pull Request**

Please open an issue first for major changes so we can discuss the direction.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

You are free to use, copy, modify, merge, publish, distribute, sublicense, or sell copies of this software.

---

## 👤 Author

**H-Tech AFAQ**
- GitHub: [@h-tech-afaq-ceo](https://github.com/h-tech-afaq-ceo)
- Project: [AI-Dispute-Resolution-Tool-MVP](https://github.com/h-tech-afaq-ceo/AI-Dispute-Resolution-Tool-MVP)

---

## ⭐ Show Your Support

If you find this project useful or interesting, please consider:

- ⭐ **Starring** the repository
- 🍴 **Forking** it to build your own version
- 📢 **Sharing** it with developers and freelancers who need it

---

## 🔍 Keywords

`ai dispute resolution` · `freelance contract dispute tool` · `online arbitration software` · `ai mediation platform` · `contract dispute saas` · `ai legal tool` · `dispute resolution app` · `claude ai` · `legal tech` · `freelancer tools` · `scope dispute resolution` · `ai ruling generator` · `document-based arbitration` · `no-code ai app` · `github pages app`

---

<p align="center">Built with ⚖️ and 🤖 to make fair resolution accessible to everyone</p>
