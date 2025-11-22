# genai_chatbot
A secure Python chatbot built using the Google Gemini API with dotenv-based API key protection. This project helps beginners and developers learn Gemini integration, build custom chatbots, automate text tasks, and prototype AI-powered applications. Ideal for learning, experimenting, and extending into web or mobile apps.

---
## 📌 Uses

This project can be used for:

- Learning the Google Gemini API in Python.
- Building secure AI applications using `.env`. 
- Creating custom chatbots and assistants.  
- Developing backend AI-powered services. 
- Automating tasks (summaries, code, text processing).  
- Prototyping AI features for websites or apps. 
- Educational and research purposes.

---

## 🖥️ Installation

### Clone the repository
```bash

https://github.com/Vimal-raj-2004/genai_chatbot.git
cd Genai_chatbot

```
## Create & Activate Virtual Environment

### 1. Create a Virtual Environment

```bash
python -m venv venv
```

### 2. Activate the Environment

#### **Windows (CMD or PowerShell):**

```bash
venv\Scripts\activate
```

### **macOS / Linux**

```bash
source venv/bin/activate
```
---

## 📦 Install Dependencies

Inside the activated virtual environment, run:

```bash
pip install google-generativeai python-dotenv
```

---

## 🔐 Setup Environment Variables

Create a file named **.env** in the project folder:

```ini
GEMINI_API_KEY=YOUR_API_KEY_HERE
```

**⚠️ Never upload this file to GitHub!**

---

## 💬 Run the Chatbot

```bash
python chatbot.py
```
---
## 📂 Project Structure

```bash
.
├── chatbot.py       # Main chatbot script
├── .env             # Environment variables (not uploaded)
├── venv/            # Virtual environment
├── .gitignore       # Prevents .env & venv from being pushed
└── README.md        # Documentation
```
---

## 🔑 How to Get Your Gemini API Key (Google AI Studio)
Follow these simple steps to generate your API key:

## 1. Visit Google AI Studio
Go to:
```
👉 https://aistudio.google.com/
```

## 2. Sign in with your Google Account
Use any Gmail or Google Workspace account.


## 3. Generate an API Key
- On the left menu, click **“API Keys”**
- Click **“Create API key”**
- Select **“Create API key in new project”** (recommended)
- Your new API key will be displayed immediately

   
## 4. Add the API Key to .env
Create a .env file in your project folder and add:
```bash
GEMINI_API_KEY=YOUR_API_KEY_HERE
```
---
## 🛑 Security Notes

- The .env file is private — never upload it to GitHub
- Never share the API key publicly
- Use .gitignore to protect sensitive files
- Always use virtual environments to avoid dependency conflicts

---
