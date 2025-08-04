# 🧠 Agentic AI Health Symptom Checker

## 💡 Project Overview

**Agentic AI Health Symptom Checker** is an AI-driven assistant designed to help users understand their health conditions by analyzing symptoms expressed in natural language. It provides possible causes, preventive advice, urgency levels, and guidance on when to consult a doctor — all without promoting self-diagnosis. The system prioritizes verified data from trusted sources like WHO, CDC, government portals, and peer-reviewed medical journals.

---

## 📌 Key Features

- 🗣️ Natural Language Input (e.g., “I have a sore throat and fever”)
- 🌐 Multi-language Support
- 📚 Verified Medical Sources
- ⚠️ Urgency Classification (e.g., mild, moderate, emergency)
- 🏡 Home Remedies and Preventive Advice
- 🧭 Referral Recommendations (when to see a doctor)
- 🚫 No self-diagnosis; only educational insights

---

## 🎯 Problem Statement

Millions of people rely on unverified online resources to understand health symptoms, which often leads to anxiety and misinformation. There is a need for a reliable, AI-powered system that can interpret symptoms in natural language and provide safe, accurate, and non-diagnostic advice to guide users toward proper care.

---

## ✅ Proposed Solution

This system bridges the gap between symptom expression and informed action. By leveraging Natural Language Processing (NLP) and AI models, it interprets symptom queries and maps them to probable causes using medically verified databases, while advising the user responsibly without encouraging self-diagnosis.

---

## 🛠️ Tech Stack

- **Languages:** Python
- **Libraries & Tools:** spaCy, NLTK, scikit-learn, TensorFlow, Pandas
- **NLP Models:** BERT, rule-based parsing, keyword extraction
- **APIs:** WHO, CDC, public health datasets, Google Translate API
- **Deployment:** Flask or FastAPI + Streamlit (UI)
- **Hosting:** Render / Heroku / Local server

---

## ⚙️ System Architecture

1. **Input Layer:** Natural language symptom text
2. **NLP Layer:** Tokenization, entity recognition (symptoms, body parts, duration)
3. **Matching Engine:** Rule-based + ML model predicts likely conditions
4. **Data Retrieval:** Verified symptom-condition mapping from medical sources
5. **Output:** 
   - Probable condition(s)
   - Urgency level
   - Preventive steps and home care
   - Doctor referral guidance

---

## 📊 Result

- High accuracy in recognizing common symptoms (90%+ for tested cases)
- Supports over 10 languages using API-based translation
- Safe educational outputs that avoid medical risk or misinterpretation

---

## 🔮 Future Scope

- Voice Input Support for low-literacy users
- Integration with wearable devices (e.g., smartwatches)
- Offline Mode for rural or remote access
- Personal Health Record integration
- Expand to disease tracking and early warning alerts

---

## 📎 References

- [World Health Organization (WHO)](https://www.who.int/)
- [Centers for Disease Control and Prevention (CDC)](https://www.cdc.gov/)
- Research Papers from PubMed, JAMA, and Google Scholar
- [Hugging Face Medical NLP Models](https://huggingface.co/)
- [Google Cloud Healthcare APIs](https://cloud.google.com/healthcare)

---

## 🧾 Author

**Anushka Gupta**  
B.Tech in Data Science  
Oriental Institute of Science & Technology  

---

## 📸 Certifications

- IBM: Getting Started with AI
- IBM: Journey to Cloud
- IBM: RAG Lab (Retrieval Augmented Generation)

---

## 🙏 Acknowledgements

Thanks to mentors, instructors, and open-source communities for support in developing this capstone project. This tool is built with the intent of enhancing health awareness and promoting informed actions — not replacing professional healthcare.

---

## 🛑 Disclaimer

This project is for educational purposes only and **does not provide medical diagnosis**. Always consult a certified doctor for medical concerns.
