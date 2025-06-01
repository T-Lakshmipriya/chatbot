# chatbot
# Smart AI ChatBot 🧠💬

Smart AI ChatBot is a feature-rich educational web application designed to provide intelligent conversations, voice input/output, drawing canvas functionality, and an in-browser code editor. It aims to create an interactive, multimodal learning environment.

## 🔥 Key Features

- 🤖 **AI-Powered Chat** using OpenRouter and Mistral-7B-Instruct model.
- 🎤 **Voice Input** via Speech Recognition API.
- 🗣️ **Text-to-Speech Output** with customizable gender and language.
- 🎨 **Drawing Canvas** for freehand input and image upload.
- 💻 **In-Browser Code Editor** with support for:
  - JavaScript (live execution)
  - HTML/CSS (rendered directly)
  - Python/Java (message shown to integrate with Judge0 or similar API)
- 📂 **File Upload** for potential document-based querying (expandable feature).

## 🌐 Tech Stack

- **Frontend:** HTML, CSS (Bootstrap), JavaScript
- **AI Integration:** OpenRouter API with Mistral-7B-Instruct
- **APIs Used:**
  - Web Speech API (Speech Recognition & Synthesis)
  - Canvas API for drawing
  - Fetch API for chat backend

## 🧠 AI Model

- **Model:** `mistralai/mistral-7b-instruct:free`
- **Provider:** OpenRouter AI
- **Response Handling:** Markdown-rendered, with speech synthesis

## 📁 Folder Structure

