# BharatMitra AI – India's AI Public Services Copilot

![AI](https://img.shields.io/badge/AI-Google_Gemini-blue)
![Supabase](https://img.shields.io/badge/Backend-Supabase-green)
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-blue)
![Lovable](https://img.shields.io/badge/Frontend-Lovable-orange)

---
This project was developed for the be10x AI Hackathon under the Viksit Bharat 2047 theme. BharatMitra AI demonstrates how Artificial Intelligence can improve access to government welfare schemes by providing citizens with personalized, explainable recommendations

## About the Project

BharatMitra AI is an AI-powered citizen companion built to demonstrate how Generative AI can simplify access to government welfare services. The project combines natural language understanding, intelligent scheme matching, and a structured government scheme database to help citizens identify relevant welfare programs quickly and easily.

The current MVP validates the core AI recommendation workflow using Google Gemini, Supabase, and Lovable, while providing a foundation for future capabilities such as multilingual voice assistance, document simplification, family opportunity analysis, and personalized action planning.

## 🚀 Live Demo

🌐 **Live Application:**  
https://bharatmitra-ai.lovable.app

---

## 📌 Problem Statement

India offers hundreds of welfare schemes across agriculture, education, healthcare, housing, employment, women empowerment, entrepreneurship, and social security. However, many eligible citizens fail to benefit due to:

- Lack of awareness
- Complex eligibility criteria
- Information spread across multiple portals
- Difficult-to-understand government documents
- No personalized guidance

BharatMitra AI addresses these challenges using Artificial Intelligence.

---

## 💡 Solution

Users simply describe themselves in natural language.

Example:

> *"I am a farmer from Telangana with two acres of land and an annual income of ₹2 lakh."*

The AI:

- Understands the citizen profile
- Matches it against government schemes
- Explains why each scheme is relevant
- Displays benefits
- Shows required documents
- Provides official application links

---

# ✨ Features

## ✅ AI Eligibility & Benefits Engine

- Natural language profile analysis
- Personalized government scheme recommendations
- AI-generated eligibility explanations

---

## 📚 Government Scheme Knowledge Base

- Structured database of **40 Government Welfare Schemes**
- Agriculture
- Healthcare
- Education
- Employment
- Women Empowerment
- Social Security
- Financial Inclusion

---

## 🔐 Secure Authentication

- User Registration
- Login
- Protected Dashboard

Powered by **Supabase Auth**

---

## 🤖 AI-Powered Recommendation Engine

Google Gemini AI analyzes citizen profiles and intelligently recommends eligible schemes.

---

## 📄 Personalized Recommendations

Each recommendation includes:

- Scheme Name
- Ministry
- Benefits
- Required Documents
- Official Website
- AI-generated Reason for Recommendation

---

# 🛠 Technology Stack

| Layer | Technology |
|--------|------------|
| Frontend | Lovable |
| Backend | Supabase |
| Database | PostgreSQL (Supabase) |
| Authentication | Supabase Auth |
| AI | Google Gemini 2.5 Flash |
| Backend Logic | Supabase Edge Functions |

---

# 🏗 System Architecture

```
                    USER
                      │
                      ▼
        BharatMitra AI (Lovable Frontend)
                      │
                      ▼
          Supabase Authentication
                      │
                      ▼
           Supabase Edge Function
              analyze-citizen
                      │
          ┌───────────┴───────────┐
          ▼                       ▼
Government_Schemes Database     Google Gemini AI
(PostgreSQL-40 Schemes)      (Profile understanding & Intelligent Scheme Matching)
          │                       │
          └───────────┬───────────┘
                      ▼
         Personalized Recommendations
     (Benefits,Documents & Official Links)
                      │
                      ▼
          Results Displayed to User
```

---

# 🔄 Workflow

1. User logs in securely.
2. User enters a profile in natural language.
3. Frontend calls Supabase Edge Function.
4. Edge Function retrieves scheme data.
5. Google Gemini AI analyzes the profile.
6. AI identifies eligible schemes.
7. Personalized recommendations are displayed.

---

# 📈 Innovation Highlights

- AI-powered conversational interface
- Explainable AI recommendations
- Personalized government scheme discovery
- Cloud-native architecture
- Scalable government scheme knowledge base
- Future-ready citizen service platform

---

# 🌍 Future Scope

- Support for all Central & State Government schemes
- Multilingual AI
- Voice Assistant
- Document Explainer
- Family Opportunity Analyzer
- Personalized Action Planner
- DigiLocker Integration
- AI-powered Form Filling
- Real-time Application Tracking

---

# 🎯 Impact

BharatMitra AI aims to:

- Increase awareness of welfare schemes
- Improve accessibility to government services
- Reduce the digital divide
- Help citizens discover benefits faster
- Support the vision of **Viksit Bharat 2047**

---

# 👩‍💻 Developed By

**Prema Reddy** for the **be10x AI Hackathon** under the project theme **"Viksit Bharat 2047"**.

---

# ⭐ Acknowledgements

- Google Gemini AI
- Supabase
- Lovable
- Government of India Public Welfare Information

---

## 📬 Contact

For questions or collaboration, please connect through GitHub.
