# LinkedIn Post Automation with n8n + AI Agent

## 📌 Overview
This project automates **LinkedIn content creation and posting** using **n8n**, **OpenAI** models, and **Google Sheets**.  
It fetches tasks, generates content ideas, researches the topic, and stores results for posting — all without manual effort.

## ⚙️ Workflow Steps
1. **Trigger** – Workflow starts when you click `Execute workflow` in n8n.
2. **Get Many Tasks** – Fetches pending topics or tasks from your source.
3. **Generate Topics / Ideas** – Uses OpenAI Message Model to create engaging post ideas.
4. **AI Agent** – Enhances content with research, formatting, and tone adjustments.
5. **Append Row in Google Sheets** – Saves the generated content in Google Sheets for scheduling/posting on LinkedIn.

## 🛠️ Tech Stack
- **n8n** – Workflow automation
- **OpenAI Chat Model** – AI content generation
- **Google Sheets** – Content storage
- **AI Agent Node** – Multi-step reasoning and enhancement

## 📂 Project Structure


<img width="1912" height="969" alt="image" src="https://github.com/user-attachments/assets/82472d7b-1903-4d01-acd3-b3df31bff2a0" />
