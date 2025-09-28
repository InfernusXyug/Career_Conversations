# Career Conversations 🎤🤖

An interactive chatbot built with **Gradio** and **OpenAI models** that represents me (*Yug Agarwal*).  
It can answer questions about my career, background, skills, and experience, while also collecting contact details for further collaboration.  

🚀 **Live Demo:** [Career Conversations on Render](https://career-conversations-kv2r.onrender.com/)

---

## 📌 Features
- 💬 Chatbot that responds as *Yug Agarwal* based on my LinkedIn profile and personal summary.  
- 🧠 Uses **OpenAI GPT models** via [OpenRouter](https://openrouter.ai).  
- 📄 Reads data from my `summary.txt` and `linkedin.pdf` for accurate responses.  
- 🔔 Integrates with **Pushover** to record unknown questions and user details.  
- 🌐 Simple and clean Gradio UI for chatting.  

---

## ⚙️ Tech Stack
- [Python 3.10+](https://www.python.org/)  
- [Gradio](https://www.gradio.app/) – frontend for the chatbot  
- [OpenAI API (OpenRouter)](https://openrouter.ai/) – LLM access  
- [PyPDF](https://pypi.org/project/pypdf/) – PDF parsing for LinkedIn profile  
- [python-dotenv](https://pypi.org/project/python-dotenv/) – env management  
- [Pushover API](https://pushover.net/) – push notifications  

---

## 🚀 Deployment
The app is deployed on **Render** and automatically pulls from GitHub on each commit.  

To run it locally:  
```bash
# Clone the repo
git clone https://github.com/InfernusXyug/Career_Conversations.git
cd Career_Conversations

# Create a virtual environment
python -m venv venv
source venv/bin/activate   # (Linux/Mac)
venv\Scripts\activate      # (Windows)

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
