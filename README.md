# 🚀 ROAMIO AI  
### *An AI-Powered Student Day Planner for Smarter Daily Decisions*

ROAMIO AI is a modern, student-focused web application designed to help college students plan their day more effectively based on their **mood, energy level, budget, available time, weather, and personal priorities**.

Instead of giving generic productivity advice, ROAMIO AI generates a **personalized daily plan** tailored to the student’s current situation.

The project combines:
- **Frontend UI/UX design**
- **Backend integration**
- **Generative AI**
- **Smart planning logic**
- **Student-centric usability**

---

# 📌 Project Overview

College life is unpredictable.

Some days students feel:
- overwhelmed with assignments,
- too tired to be productive,
- restricted by low budgets,
- confused about what to prioritize,
- or simply mentally drained.

Traditional planners are often rigid and static.

## 💡 Solution:
ROAMIO AI acts as a **smart AI lifestyle assistant** that helps students decide:

- What to focus on
- How to balance productivity and rest
- What low-effort or low-budget activity to do
- What self-care step they should take
- What food suggestion suits their current state

This makes planning:
- **more personal**
- **more realistic**
- **more engaging**
- **more adaptive**

---

# 🎯 Problem Statement

Students often struggle to structure their day effectively because their routines are influenced by multiple changing factors such as:

- mood
- energy
- time availability
- financial constraints
- environmental conditions
- personal priorities

Most traditional planning tools:
- do not adapt in real-time
- do not understand emotional or situational context
- provide static to-do management only

## ROAMIO AI solves this by:
Using **Generative AI** to create **dynamic, personalized daily plans** based on live user inputs.

---

# 🧠 Objective of the Project

The main objective of ROAMIO AI is to build a **student-centered AI planning assistant** that:

- understands a student’s current situation
- adapts recommendations accordingly
- improves day structure and time use
- reduces decision fatigue
- encourages healthier daily balance

---

# 👥 Target Audience

ROAMIO AI is primarily designed for:

- 🎓 College students
- 📚 Students with heavy academic workload
- 💸 Budget-conscious students
- 😵 Students facing burnout or stress
- ⏰ Students with poor time management
- 🌧 Students whose plans depend on weather or energy

---

# ✨ Key Features

## 1. 🧾 Personalized Daily Planning
Users can input:
- Mood
- Energy level
- Budget
- Time available
- Weather
- Priority

The system then generates a **custom plan**.

---

## 2. 🤖 AI-Generated Smart Suggestions
Using Generative AI, the app suggests:

- **Productive tasks**
- **Fun activities**
- **Self-care ideas**
- **Food suggestions**
- **Bonus lifestyle tips**

---

## 3. 🎨 Modern Dark Gen-Z Interface
The website has a stylish and visually immersive UI featuring:

- Dark grungy aesthetic
- Smooth scrolling
- Floating gradient orbs
- Glassmorphism cards
- Dashboard sections
- Founder section
- Interactive hover animations

---

## 4. 📊 EXPERIENCE
The dashboard visually presents student lifestyle indicators such as:

- Productivity balance
- Fun ratio
- Self-care ratio
- Mood pulse
- Budget friendliness
- Weekly energy rhythm

---

## 5. 🔁 Frontend Dynamic Interactions
Even without API connectivity, the project can include:
- interactive UI states
- click-based smart outputs
- dynamic display sections
- frontend-only simulation logic

This ensures the project remains functional and demonstrable during presentation.

---

# 🏗️ Tech Stack Used

## Frontend
- **HTML5**
- **CSS3**
- **JavaScript**

## Backend
- **Python**
- **Flask**

## AI Integration
- **Groq API**
- **LLM-based response generation**

## Development Tools
- **VS Code**
- **GitHub**
- **GitHub Pages (optional for frontend preview)**

---

# 🧩 Project Architecture

```text
User Inputs
   ↓
Frontend Form (HTML/CSS/JS)
   ↓
Flask Backend (Python)
   ↓
Prompt Construction
   ↓
Groq API / LLM
   ↓
AI Response Generation
   ↓
Personalized Plan Displayed to User

---
# How It Works
The user enters inputs such as mood, energy, budget, time, and priority.
The frontend sends this data to the Flask backend.
The backend processes the inputs.
The processed data is sent to the Groq API.
The AI generates a personalized daily plan.
The output is returned and displayed on the frontend.
Installation and Setup
1. Clone the repository
git clone https://github.com/your-username/roamio-ai.git
cd roamio-ai
2. Install dependencies
pip install flask flask-cors openai
3. Add API Key

Open app.py and replace:

api_key="your_api_key_here"
4. Run the application
python app.py
5. Open in browser
http://127.0.0.1:5000
Example Input
Mood: Tired
Energy: Low
Budget: Low
Time: Limited
Priority: Study

The system generates a balanced plan including productive tasks, self-care, and practical suggestions.

Screenshots

Include the following in your repository:

Homepage
Input Form
Generated Output
Dashboard
Deployment

The project can be deployed using:

Render
Railway
Replit
Vercel (frontend hosting)
Challenges Faced
Integrating frontend and backend efficiently
Structuring AI-generated responses
Maintaining balance between design and functionality
Future Scope
User authentication system
Planner history storage
Notifications and reminders
Calendar integration
Mobile application version
Contribution

Pratiksha Singh
Frontend development, UI/UX design, layout and styling

Conclusion

ROAMIO AI demonstrates how artificial intelligence can be used to create practical and personalized daily planning systems tailored for students.

License

This project is developed for academic purposes.
