# 🚀 AI Learning Path Generator (n8n + Gemini + Google Docs)

An AI-powered automation system that generates personalized learning roadmaps and automatically creates structured study plans using Google Docs and Calendar.

## 🧠 Features

* Chat-based AI roadmap generator
* Uses Google Gemini API
* Creates structured curriculum automatically
* Saves roadmap in Google Docs
* Schedules study plan in Google Calendar
* Fully automated using n8n AI Agent
* Real-world Use Case
      - Students preparing for GATE/placements
      - Auto roadmap for any skill (DSA, Web Dev, AI)
      - Productivity automation

## 🏗️ Architecture

User Chat → n8n AI Agent → Gemini API
→ Generate Learning Path
→ Create Google Doc
→ Schedule in Google Calendar

## ⚙️ Tech Stack

* n8n (Automation)
* Google Gemini API
* SerpAPI (for resources)
* Google Docs API
* Google Calendar API

## 📸 Workflow Screenshot

Added below , make a look.

## 🔧 Setup Instructions

### 1. Clone repo

git clone https://github.com/Vinay-2007/AI-Learning-Path-Generator

### 2. Import workflow into n8n

Open n8n → Import workflow
Upload `workflow/n8n-workflow.json`

### 3. Add credentials

* Gemini API key
* Google Docs OAuth
* Google Calendar OAuth
* SerpAPI key

### 4. Activate workflow

Turn workflow ON and start chatting 🎉

## 💡 Example Prompt

"Create a 30-day Python roadmap"

AI will:

* Generate curriculum
* Create Google Doc
* Schedule study plan automatically

## 🧑‍💻 Author

Vinay P
BTech CSE (AI & Automation Enthusiast)

## ⭐ If you like this project

Give it a star on GitHub!

