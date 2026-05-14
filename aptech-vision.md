# 🇵🇰 Urdu Civic Issue Reporting System  
### (Aptech Vision Project – Student Exhibition)

A web-based civic tech platform that allows users to **report civic issues in Urdu or English using text or voice input**, automatically classifies the issue, suggests the responsible department, and guides the user step-by-step to submit complaints manually to official portals.

---

# 🚀 Project Start Date
**20 May (Planned Start)**

---

# 💡 Project Idea

This system helps citizens in Pakistan report daily problems such as:
- Garbage issues
- Electricity failures
- Water supply problems
- Road damage

The system improves civic engagement by:
- Allowing **Urdu voice input**
- Automatically generating complaint text
- Suggesting correct government department
- Providing **step-by-step submission guidance**

---

# 🎯 Core Features

## 1. 📝 Complaint Input System
- Users can type complaints in Urdu, Roman Urdu, or English
- Simple and user-friendly form interface

---

## 2. 🎤 Voice Input (Web Speech API)
- Users can speak their complaint in Urdu/Roman Urdu
- Browser converts speech → text automatically
- No external hardware required

---

## 3. 🧠 Issue Classification (Basic AI Logic)
Automatically detects category:
- Sanitation (kachra, safai)
- Electricity (bijli)
- Water supply (pani)
- Infrastructure (roads)

---

## 4. 🏢 Department Suggestion System
Maps issue → responsible authority:

- Electricity → K-Electric  
- Water → WASA  
- Sanitation → KMC  
- Civic issues → Local municipality

---

## 5. 📄 Complaint Generator
System formats complaint into a formal structure:

- Subject line
- Professional message
- Ready-to-submit text

---

## 6. 📋 Guided Complaint Assistant (IMPORTANT FEATURE)

Instead of auto-submitting (which is unsafe and not allowed), the system:

### Provides:
- ✔ Copy-ready complaint text
- ✔ Step-by-step instructions
- ✔ Official complaint portal links

### Steps shown to user:
1. Open official complaint portal
2. Fill basic details
3. Paste generated complaint
4. Submit form manually
5. Save complaint ID

---

## 7. 📊 Complaint Dashboard
- Stores user complaints
- Shows history of submitted issues
- Displays category and department

---

# ⚙️ Technical Stack

## Frontend
- React.js / Next.js
- Tailwind CSS (UI design)

## Backend
- Firebase Firestore (database)
- Firebase Auth (optional login)

## AI / NLP
- Rule-based classification (initial version)
- Optional: HuggingFace API (advanced)

## Voice Input
- Web Speech API (browser-based)

## Hosting
- Vercel (frontend)
- Firebase Hosting (backend)

---

# 🧠 System Flow

```text
User Input (Text / Voice)
        ↓
Speech-to-Text (if voice)
        ↓
Issue Classification
        ↓
Department Mapping
        ↓
Complaint Generator
        ↓
Guided Submission Assistant
        ↓
User manually submits on official portal


