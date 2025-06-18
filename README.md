# 💬 DigiBuddy – AI-Powered Digital Literacy Assistant

DigiBuddy is a smart, friendly AI chatbot designed to help parents and seniors learn digital skills. It features voice input, quick-select help options, and a clean, mobile-friendly interface — all powered by OpenRouter's AI API.

---

## 🌟 Features

* 🤖 AI Chatbot (DigiBuddy) – Offers simple, patient, and encouraging responses.

* 🗣️ Voice Input Support – Speak instead of typing! (Using Web Speech API).

* ✨ Quick-Select Suggestions – Tap to ask questions like “What is a browser?”

* 📱 Mobile Friendly UI – Works smoothly on phones and tablets.

* 🌐 Multi-language Font Support – Easily extendable to support other languages.

* 🔒 Secure Frontend – No user data is stored or tracked.

---

## 🛠️ Technologies Used

| Feature           | Technology                                                          |
| ----------------- | ------------------------------------------------------------------- |
| Frontend          | HTML, CSS, JavaScript                                               |
| Styling           | Custom CSS with gradients & animations                              |
| AI API            | [OpenRouter](https://openrouter.ai) (model: `openai/gpt-3.5-turbo`) |
| Voice Recognition | Web Speech API (browser native)                                     |
| Icons             | Font Awesome                                                        |
| Fonts             | Google Fonts (`Poppins`, `Roboto`)                                  |


---

## Setup Instructions:

1) Clone or download the repo.
2) Replace the placeholder in index.html with your OpenRouter API key:
```
const apiKey = 'your-openrouter-api-key';
```
3)  Open index.html in your browser.

### Note: 

💡 You can track usage or upgrade your plan at openrouter.ai/keys

## 🔑 How to Get OpenRouter API Key (FREE)
1) Go to: https://openrouter.ai/

2) Click Sign Up and verify your email.

3) Go to: https://openrouter.ai/keys

4) Click "Create API Key"

5) Copy the key and paste it in the JavaScript file (replace your-openrouter-api-key).


---


## ⚙️ How It Works
1) User Input:

* User types a message or uses voice input via microphone.

* A message is displayed in the chat window.

2) AI Request:

* A request is sent to https://openrouter.ai/api/v1/chat/completions with the user's message.

3) AI Response:

* The model responds with an answer, which is displayed in the chatbot window.

4) Typing Indicator:

* Simulated dots show when the AI is "thinking".

5) Voice-to-Text:

* If supported by the browser, the Web Speech API converts spoken words into text.


---

## 🚦 Rate Limit (OpenRouter)

| Plan       | Limit                                   |
| ---------- | --------------------------------------- |
| Free Tier  | ✅ \~50 messages/day (subject to change) |
| Paid Plans | 💰 Higher message limits                |

## 📌 Browser Requirements:-

* Works best on Chrome, Edge, and Firefox

* Voice input may not work on some mobile browsers like Safari

---
License : All rights are Reserved
