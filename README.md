# MailMate AI

**MailMate AI** is a production-ready Chrome Extension that integrates directly with Gmail to generate smart, AI-powered email replies using Google’s Gemini API. This project showcases full-stack engineering through real-world browser scripting, secure API interaction, and AI-powered automation — all built for a seamless user experience inside Gmail.

---

## 🧰 Tech Stack

- **Chrome Extension**: JavaScript, HTML, CSS
- **Backend**: Java + Spring Boot (WebClient)
- **Frontend**: React + Vite + Material UI
- **AI Integration**: Gemini Pro API

---

## ✨ Features

- One-click **AI Reply** button injected into Gmail’s compose window
- Supports tone customization: *Professional*, *Casual*, *Friendly*
- Backend securely constructs prompts and communicates with Gemini
- Optional React UI for testing reply generation independently

---

## 🔨 What I Built

- **Gmail-integrated Chrome Extension**  
  Injects a reply button using MutationObserver and content scripts. Seamlessly integrates into Gmail without disrupting the interface.

- **Spring Boot Backend Service**  
  Handles secure communication with Gemini API. Prompts are dynamically generated from user input and passed via POST requests.

- **React + Vite Frontend (Optional)**  
  A standalone UI for previewing AI-generated replies during development or demos. Simplifies testing without opening Gmail.

- **Gemini API Integration**  
  Connects with Google's Gemini API to return AI-based email responses tailored to tone and context.

---

## 🔁 How It Works

Gmail Compose  
⬇️  
Chrome Extension  
⬇️  
Spring Boot API  
⬇️  
Gemini API  
⬇️  
Reply Inserted into Gmail

---

## 👤 Developed By

Created and maintained by **Bhavatarini Thangaraju**  
📧 [LinkedIn](https://www.linkedin.com/in/bhavatarini-thangaraju)
