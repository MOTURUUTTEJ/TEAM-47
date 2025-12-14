---

# 🚀 ClassPulse AI

### ACIS – Adaptive Classroom Intelligence System

ClassPulse AI is an **AI-powered classroom intelligence platform** that transforms raw lectures into **structured notes, adaptive quizzes, flashcards, and learning insights**.
It doesn’t just generate content — it **measures understanding and adapts teaching**.

> *From Classroom → Comprehension.*

---

## 📌 Key Features

* 🎙 **Lecture Input**

  * Manual text, live mic, or uploaded content
* 🧠 **AI-Generated Smart Notes**

  * Clear summaries, key concepts, definitions, and examples
* 📝 **Adaptive Quiz Engine**

  * Automatically generated concept-checking questions
* 📊 **Learning Gap Detection (ACIS)**

  * Identifies weak concepts and misconceptions
* 👨‍🏫 **Teacher Explanation Quality Scoring**

  * Measures clarity, simplicity, and example usage
* 🧩 **Flashcards & Revision Aids**

  * Auto-generated from lecture content
* ⚡ **Real-time UI Feedback**

  * Loading animations, progress indicators, and alerts
* 🌐 **API-First Architecture**

  * Fully usable via REST APIs (Swagger friendly)
* 🔌 **AI Flexibility**

  * Works with **Gemini 2.5 Flash API**
  * Optional **offline Nexa AI, ollama AI** support

---

## 🧠 System Architecture

```
Lecture Input (Text / Mic)
        ↓
Frontend (React + Tailwind UI)
        ↓
FastAPI Backend (API Layer)
        ↓
AI Engine (Gemini 2.5 Flash / Nexa Offline)
        ↓
ACIS Intelligence Layer
        ↓
Notes • Quizzes • Flashcards • Insights
```

**Core Principle:**

> *Never trust raw LLM output — validate, structure, analyze, and adapt.*

---

## 📁 Project Structure

```
classpulse/
│
├── backend/
│   ├── main.py              # FastAPI backend
│   ├── requirements.txt     # Python dependencies
│
├── ui/
│   └── index.html           # React + Tailwind frontend
│
└── README.md
```


---

## 🧰 Tech Stack

### Frontend

* React (via CDN)
* Tailwind CSS
* Vanilla JavaScript
* HTML5
* CSS Animations

### Backend

* FastAPI
* Uvicorn
* Pydantic

### AI Layer

* **Gemini 2.5 Flash API** (Cloud)
* **Nexa AI, ollama AI (Offline, optional)**

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/classpulse-ai.git
cd classpulse-ai
```

### 2️⃣ Backend Setup

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### 3️⃣ Open in Browser

```
http://127.0.0.1:8000
```

✅ Frontend and backend are served together
✅ No separate frontend server needed

---

## 🧩 ACIS Methodology

**Adaptive Classroom Intelligence System**

ACIS is the intelligence layer that differentiates ClassPulse AI from typical note-generation tools.

### How ACIS Works:

1. **Input Understanding** – Cleans and segments lecture text
2. **Concept Extraction** – Identifies definitions, examples, and relationships
3. **Cognitive Load Analysis** – Measures sentence complexity
4. **Assessment Generation** – Creates adaptive quizzes
5. **Understanding Scoring** – Calculates student comprehension
6. **Misconception Detection** – Finds conceptual confusion
7. **Adaptive Feedback** – Suggests revision or deeper explanation
8. **Long-Term Memory** – Tracks weak topics across sessions

> ACIS adapts teaching based on **learning outcomes**, not just content.

---

## 🚀 Future Roadmap

* 📡 Real-time classroom dashboards
* 👥 Multi-student analytics
* 🔁 Automatic re-prompting on AI failures
* 📈 Confidence score per concept
* 🎥 Video explanation generation (Veo)
* 📚 Slide generation (NotebookLM)
* ⚙️ NPU-optimized offline inference
* 🔗 LMS & EdTech integrations

---

> *“ClassPulse AI converts classroom lectures into adaptive learning experiences by analyzing not just what is taught, but how well it is understood.”*

---
