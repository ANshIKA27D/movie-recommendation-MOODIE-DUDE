📽️ AI Movie Recommender System – README
⭐ Overview
The AI Movie Recommender System is an interactive web application that recommends movies based on the user’s mood, preferred language, and favorite actor/actress.
The system integrates AI-powered natural language understanding, real-time search, and an engaging UI that displays trailers, posters, genres, and ratings.

🎯 Features


🎭 Mood-Based Recommendations (e.g., happy, sad, excited, calm)


🤖 AI Chatbot Interface powered by OpenAI API


🎞 Integrated Trailers, Posters & Ratings


⚡ Fast, Minimal, and User-Friendly Web UI


🛢️ SQL-based movie database for reliable querying


📡 Flask backend with API endpoints



🛠️ Tech Stack
Backend


Python


Flask


OpenAI API


SQL (MySQL / SQLite)


Frontend


HTML5


CSS3


JavaScript


Libraries


Requests


Pandas


JSON
Flask APIs

🚀 How to Run Locally
1️⃣ Clone the Repository
git clone https://github.com/yourusername/ai-movie-recommender.git
cd ai-movie-recommender
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Add Your OpenAI API Key
Create a .env file:
OPENAI_API_KEY=your_api_key_here
4️⃣ Run the Application
python app.py
5️⃣ Open in Browser
http://127.0.0.1:5000
💡 How It Works
User enters mood.
Chatbot processes input using OpenAI LLM
System queries the movie database
Recommendations are ranked based on similarity and metadata
UI displays title, poster, genre, IMDb rating, and trailer

🔮 Future Enhancements
🎧 Voice-based recommendation system
📊 Collaborative filtering & content-based hybrid model
🎞 Auto-play trailer preview
🧠 User preference learning over time







