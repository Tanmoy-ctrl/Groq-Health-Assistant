# 🩺 Groq Health Assistant

An AI-powered Health Assistant chatbot built using **Python, Streamlit, and Groq API**. It provides general health information and wellness guidance through an interactive chat interface.

## 🚀 Features

- **AI-Powered Responses:** Uses Groq API with the `openai/gpt-oss-120b` model.
- **Health-Only Chatbot:** Designed to respond exclusively to health-related questions.
- **Interactive Chat Interface:** Simple and user-friendly interface built with Streamlit.
- **Chat History:** Maintains conversation history during the current session.
- **Clear Chat:** Allows users to clear the conversation whenever needed.
- **Secure API Key Handling:** Supports local `.env` files and Streamlit Cloud Secrets.
- **Medical Safety Instructions:** Avoids claiming to diagnose diseases or prescribing medicines and dosages.

## 🛠️ Technologies Used

- Python
- Streamlit
- Groq API
- GPT-OSS-120B
- python-dotenv

## 📁 Project Structure

```text
groq-health-assistant/
│
├── app.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/groq-health-assistant.git
```

### 2. Navigate to the Project Folder

```bash
cd groq-health-assistant
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure the Groq API Key

Create a `.env` file in the project directory and add:

```env
GROQ_API_KEY=your_groq_api_key
```

Get your API key from the [Groq Console](https://console.groq.com/).

### 5. Run the Application

```bash
streamlit run app.py
```

The application will open in your browser.

## 📦 Requirements

Create a `requirements.txt` file containing:

```text
streamlit
python-dotenv
groq
```

## 🔐 API Key Security

- Never share your Groq API key publicly.
- Do not upload your `.env` file to GitHub.
- Use Streamlit Cloud Secrets when deploying the application.

For Streamlit Cloud, add the following under **App Settings → Secrets**:

```toml
GROQ_API_KEY = "your_groq_api_key"
```

## ⚠️ Disclaimer

This application is intended for general health information and educational purposes only. It does not provide medical diagnoses, prescribe treatments, or replace professional medical advice. Always consult a qualified healthcare professional for medical concerns. In an emergency, seek immediate medical attention.

## 👨‍💻 Author

**Tanmoy Manna**

---

⭐ If you find this project interesting, consider giving the repository a star!
