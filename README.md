🌸 Asha AI Bot 🤖✨ - Empowering Women's Careers with Cutting-Edge AI!
---
Welcome to Asha AI, an innovative conversational AI assistant designed to revolutionize women's career journeys! Built with ethical AI and tailored for the vibrant Indian context, Asha AI leverages Retrieval-Augmented Generation (RAG) to deliver personalized, real-time career support. From job listings to mentorship opportunities, Asha AI is your ultimate career companion! 🚀
---


🎯 Mission
Empower women to thrive in their professional lives by providing seamless access to opportunities, insights, and resources—crafted with care and precision.
---

🌟 Key Features

🗣️ Multi-Turn Conversations: Engage in dynamic, context-aware chats that evolve with you.
🔎 Semantic Search: Unleash powerful searches across local datasets and global APIs (Adzuna, Ticketmaster).
⚡ Real-Time Retrieval: Get the latest job and event updates in an instant!
🏙️ Indian-Centric Insights: Tailored for Indian cities, local synonyms, and cultural nuances.
⚖️ Bias & Ambiguity Detection: Ensuring fair and clear responses every time.
📊 User Feedback Integration: Real-time analytics to enhance your experience.
🛠️ Production-Ready Backend: Built with FastAPI for scalability and speed.
🎨 Sleek Frontend: A lightweight, user-friendly interface with HTML, CSS, and JavaScript.
---

💻 Technologies Powering Asha AI

Backend: FastAPI, Python 3.10
Frontend: HTML, CSS, JavaScript
Integrated APIs:
Adzuna API: Global job listings at your fingertips.
Ticketmaster API: Discover networking events and workshops.
GROQ API: Natural, engaging conversational AI.
---

Advanced Features: Semantic Search, Query Expansion, Bias Detection, Session Management
---

🚀 Getting Started
1. Clone the Repository
git clone 
cd asha

2. Set Up Environment Variables
Create a .env file in the root directory and add your API keys:
GROQ_API_KEY=your_groq_api_key
ADZUNA_APP_ID=your_adzuna_app_id
ADZUNA_APP_KEY=your_adzuna_app_key
TICKETMASTER_API_KEY=your_ticketmaster_api_key

3. Backend Setup
python -m venv .venv
# On Windows: .venv\Scripts\activate
# On Mac/Linux: source .venv/bin/activate
pip install -r requirements.txt

4. Launch the Backend Server
uvicorn src.ragi:app --reload

5. Explore the Frontend
Open frontend/index.html in your browser to start chatting—connects seamlessly to the backend!

🏗️ Project Architecture
Frontend (HTML/CSS/JS) ↔ FastAPI Backend
         ↳ Query Expansion
         ↳ Bias Detection
         ↳ Semantic Search + API Retrieval
         ↳ LLM (GROQ) Processing
         ↳ Deliver Results to Frontend

---
🌟 Future Roadmap

🔄 ReactJS Frontend: A modern, interactive user experience.
💾 Database Integration: Personalized profiles and recommendations.
🧠 Advanced Bias Detection: ML-driven fairness enhancements.
🛡️ User Authentication: Secure access with profiles.
🌐 Offline Caching: Boost performance with local storage.
---

🤝 Contribute to Asha AI
We’d love your help! Open a pull request or start a discussion by creating an issue for major changes. Let’s build something amazing together! 🌟
---
📄 License
This project is licensed under the MIT License.
---
check out the deploy link - https://asha-ai-bot-63eo.onrender.com

---
🔥 Empowering Careers, One Conversation at a Time!
Asha AI: Revolutionizing Women’s Career PathsProudly crafted by Sanya and Sania with FastAPI, semantic search, and real-time job/event retrieval. 🌺
