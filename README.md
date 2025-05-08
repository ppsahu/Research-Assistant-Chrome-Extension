# 🧠 AI Powered Research Assistant - Chrome Extension

A powerful AI Chrome Extension designed to help you highlight, save, and organize web content for later reference — all with just a few clicks.

---

🎬 Video Demo -

Link - https://drive.google.com/file/d/13Am1j4LzPoo0bgube--jpELhMd-Zjs1r/view?usp=sharing

---

## 🚀 Description

The backend provides RESTful APIs for:

- Managing user accounts
- Saving research notes and highlights
- Categorizing and tagging content
- Syncing data across sessions and devices

Built using **Spring-Boot**, **JAVA**, **Lombok** and  **Gemini API** this backend is optimized for scalability, speed, and seamless integration with browser-based tools.

---

## 🔍 Use Cases

- 🧑‍🎓 **Students** capturing snippets during online research
- 🧑‍💼 **Researchers** organizing study links, ideas, and annotations
- 🧑‍💻 **Developers** bookmarking code snippets or technical content
- 🧠 Anyone needing a smarter way to collect and revisit research

---

## ✨ Features

- 📝 Summarize, Suggest Topics and Highlight Keywords for the selected text
- 🏷️ Tag and categorize notes
- 🔄 Real-time sync with Chrome Extension
- 📁 Chrome-powered document storage
- 📦 RESTful API architecture

---

## 🛠️ Tech Stack
- Backend: Java, Spring Boot
- Frontend: HTML5, CSS3, Bootstrap 5, JavaScript

---

## 🔧 How to Run the Project Locally
- Follow these simple steps to set up and run the project on your local machine.

---

## ✅ Prerequisites
Java 17+ installed
Maven or Gradle installed
Git installed
Web browser (Chrome)

## 📝 Step-by-Step Setup

- git clone https://github.com/ppsahu/Research-Assistant-Backend.git
- Go to target/classes/com/application.properties, add these 2 lines
    - gemini.api.url=https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=
    - gemini.api.key== **YOUR GEMINI API KEY**
- How to Get your Gemini API Key - https://aistudio.google.com/ -> Click on **Get API key**
- Run ResearchAssistantApplication.java file
- Download the Frontend repository to your local system.
- Go to chrome://extensions/ -> Switch the Developer mode on -> Click on Load unpacked -> Select the Frontend file 
- Go to Chrome Browser -> Click on Extensions -> Pin Research Assistant Chrome Extension
- Go to any webpage e.g. wikipedia, select any text and click on the Summarize, Suggest Topics or Highlight Keywords button to test the features.

---

🤝 Contribution Feel free to fork this repo, raise issues, or submit PRs! I’d love to collaborate and improve the project together.

---

📬 Contact Pratyush Prasanna Sahu 📍 Fullerton, CA 📧 pratzsahu.ps@gmail.com