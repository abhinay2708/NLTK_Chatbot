🤖 NLTK Chatbot with Streamlit

An interactive chatbot built using Python NLTK and deployed with Streamlit.
The chatbot can respond to greetings, tell jokes, share fun facts, answer common questions, and keep users engaged in a conversational way.

📖 Table of Contents

Features

Tech Stack

Project Structure

Installation

Usage

Demo

Future Improvements

Acknowledgments

✨ Features

💬 Chatbot created using NLTK’s Chat & Reflections

🧠 Handles common conversations: greetings, hobbies, sports, movies, jokes, fun facts, etc.

🎨 Interactive Streamlit frontend

📜 Maintains chat history for smooth conversation flow

🔧 Beginner-friendly & lightweight

🛠 Tech Stack

Python 3.x

NLTK (for chatbot logic)

Streamlit (for UI)

📂 Project Structure
📦 nltk-chatbot
 ┣ 📜 app.py              # Main Streamlit chatbot code
 ┣ 📜 requirements.txt    # Project dependencies
 ┣ 📜 README.md           # Project documentation
 ┗ 📂 screenshots         # (Optional) Store demo images

⚙️ Installation

Clone the repository

git clone https://github.com/your-username/nltk-chatbot.git
cd nltk-chatbot


Create virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows


Install dependencies

pip install -r requirements.txt

🚀 Usage

Run the chatbot using Streamlit:

streamlit run app.py


Then, open the given local URL in your browser (usually http://localhost:8501) and start chatting 🎉

📸 Demo
Chat UI Example
🧑 You: Hello
🤖 Bot: Hey there!

🧑 You: Tell me a joke
🤖 Bot: Why did the computer go to the doctor? It caught a virus! 💻🤒


(Add screenshots in a screenshots/ folder and link them here)

🔮 Future Improvements

Add sentiment analysis for smarter responses

Connect chatbot with real-time APIs (weather, news, etc.)

Save chat history in a database

Deploy on Streamlit Cloud / Heroku / Hugging Face Spaces

🙌 Acknowledgments

This project was created by Abhinay Mahato using Python, NLTK, and Streamlit.
Special thanks to the open-source community ❤️
