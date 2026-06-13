# 🛡️ Guardian AI Nexus

**Voice-First Agentic AI Companion for Blind & Elderly Users**

*Built with GitHub Copilot | Microsoft Agents League Hackathon 2026*

---

## 🎯 One-Line Pitch

Guardian AI Nexus is a multi-agent AI system that helps blind and elderly users live independently by reading documents, identifying medicines, recognizing currency, detecting risks, remembering interactions, and providing multilingual assistance in 10+ languages.

---

## 🌟 Key Features

### 🎤 Voice-First Interface
- No complicated UI — just speak naturally
- "Hey Guardian, read this bill"
- Auto-language detection (Hindi, English, Tamil, Telugu, Bengali, Marathi, etc.)

### 📄 Document Reader Agent
- Read bills, letters, forms, notices
- Extracts: summary, key points, due dates, action items, warnings
- Instant explanations in user's language

### 💊 Medicine Safety Agent
- Identify any medicine from photo
- Shows: name, expiry, uses, side effects, ⚠️ warnings
- Prevents dangerous medication mistakes

### 💰 Currency Recognition Agent
- Scan Indian currency notes instantly
- Identifies denomination correctly
- Supports all major denominations

### ⚠️ Risk Detection Agent
- Actively detects dangers:
  - Expired medicines? ⚠️ WARNING
  - Overdue payments? ⚠️ WARNING
  - Food expiring? ⚠️ WARNING
- Proactive safety alerts

### 🧠 Smart Memory Agent
- Remembers all user activities
- "What medicines did I scan today?"
- "Show my bill history"
- Patterns: "You scanned same medicine 7 times this week"

### 🌐 Multi-Language Support
- Hindi, English, Tamil, Telugu, Bengali, Marathi
- Auto-detects user language
- Responds in same language automatically
- No settings required

### 🆘 Emergency Help
- One-tap SOS activation
- Police (112), Ambulance (102), Fire Brigade (101)
- Designed for critical situations

---

## 🏗️ Architecture
User (Voice/Text Input)
          ↓
Voice Assistant Agent (Main Router)
          ↓
Intent Detection (What does user need?)
          ↓
Specialized Agents
          ├── Document Reader Agent (📄)  
          ├── Medicine Safety Agent (💊)
          ├── Currency Recognition Agent (💰)
          ├── Risk Detection Agent (⚠️)
          └── Memory Agent (🧠)
          ↓
Language Detection Engine (Auto-detect + Manual Override)
          ↓
Response Generation (GPT-4o)
          ↓
Text-to-Speech (User's Language)
          ↓
User (Voice Response)


---

## 🛠️ Tech Stack

**Backend**
- Python 3.10+
- Flask
- OpenAI API (GPT-4o Vision)

**Frontend**
- HTML5
- Modern CSS3
- Vanilla JavaScript
- Web Speech API

**AI/ML**
- GPT-4o Vision Model
- Language Auto-Detection
- Multi-Agent Reasoning

**Development**
- 100% Built with GitHub Copilot
- Code generation from comments
- Iterative refinement

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10+
- OpenAI API Key
- GitHub Copilot (for development)

### Installation

1. Clone repository:
```bash
git clone https://github.com/YOUR_USERNAME/GuardianAI.git
cd GuardianAI
```

2. Install dependencies:
```bash
pip install flask openai python-dotenv
```

3. Create `.env` file:

OPENAI_API_KEY=your_api_key_here

4. Run application:
```bash
python app.py
```

5. Open browser:
```http://localhost:5000```

---

## 📱 How It Works

### 1. Voice Input
User speaks naturally in any language → Web Speech API captures → AI understands

### 2. Intent Routing
AI determines what user needs:
- Read document?
- Scan medicine?
- Identify currency?
- Emergency help?

### 3. Agent Processing
Specialized agent processes request using GPT-4o Vision

### 4. Risk Detection
System checks for dangers and alerts user

### 5. Language Auto-Detection
AI detects user language, responds in same language

### 6. Memory Storage
Activity logged for future reference

### 7. Response Generation
Clear, helpful response in user's language

### 8. Voice Output
Text-to-Speech in user's preferred language

---

## 🎯 Real-World Impact

✅ **50+ million blind users in India** can use this  
✅ **100+ million elderly users globally** benefit from this  
✅ **Prevents medicine mistakes** that can be fatal  
✅ **Enables financial independence** (read own bills)  
✅ **Reduces caregiver burden** (no constant help needed)  
✅ **Promotes dignity and autonomy** (live independently)  

---

## 🏆 Why Guardian AI Nexus?

### Not Just Another App
❌ Chatbot — Too generic  
❌ Scanner — Too limited  
❌ Voice assistant — Missing safety  

✅ **Guardian AI Nexus** — Complete companion for independent living

### Hackathon Fit
✅ **Creative Apps Track** — Voice-first multi-agent innovation  
✅ **Hack for Good** — Solves real accessibility crisis  
✅ **Accessibility Award** — Built for zero-barrier access  
✅ **Global Impact** — Works in 10+ languages  

---

## 📊 Features Breakdown

| Feature | Status | Impact |
|---------|--------|--------|
| Voice Assistant | ✅ Complete | Main interaction point |
| Document Reader | ✅ Complete | Financial independence |
| Medicine Safety | ✅ Complete | Life-saving feature |
| Currency Recognition | ✅ Complete | Daily necessity |
| Risk Detection | ✅ Complete | Safety system |
| Memory System | ✅ Complete | Agentic behavior |
| Language Auto-Detection | ✅ Complete | Inclusion for all |
| Emergency Help | ✅ Complete | Critical safety |

---

## 🔮 Future Roadmap

- Product barcode scanner
- Environment description (3D audio mapping)
- Medication reminders with smart scheduling
- Financial advisor mode (budget analysis)
- Social integration (share results with caregivers)
- Offline mode support
- Mobile app (iOS/Android)

---

## 👥 Target Users

### Primary
- Blind individuals (all ages)
- Visually impaired people
- Elderly users with vision loss

### Secondary
- Caregivers supporting them
- Family members assisting
- Healthcare providers

---

## 📜 License

MIT License — Built with ❤️ for accessibility

---

## 🤝 Contributing

Built with GitHub Copilot — Code generation via intelligent comments

---

## 📞 Contact

**Microsoft Agents League Hackathon 2026**

*Accessibility + AI = Independent Living*

---

*"Guardian AI Nexus is not just technology. It's dignity. It's independence. It's freedom."*


