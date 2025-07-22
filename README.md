# ⚕️ AI Medical Chatbot

A simple and intelligent **AI-powered Medical Chatbot** built with **Google Gemini Pro** and **Gradio**.

This chatbot answers general health-related questions using Gemini's generative AI, with a few popular questions cached for faster replies.

---

## 🧠 Features

- 🤖 Powered by **Google Gemini Pro API**
- ⚡ Instant answers for common medical questions (via in-code cache)
- 💻 Simple web interface using Gradio
- 🛠️ Easy to deploy on Colab or locally
- 📚 Suitable for **college mini projects** or demos

---

🔐 Gemini API Setup
Go to Google AI Studio

Generate an API key

Add it to your script like this:


GEMINI_API_KEY = "your_api_key_here"
genai.configure(api_key=GEMINI_API_KEY)

---

💡 How It Works

User types a medical question into the Gradio app

If the question matches one in the cache, the answer is shown instantly

If not, the chatbot queries Gemini Pro for a fresh answer

---

🧑‍💻 Author
Developed as part of a intership project at scalezix using Python, Gradio, and Google's Gemini AI.
