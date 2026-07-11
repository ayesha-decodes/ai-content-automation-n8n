# 🚀 AI Content Automation using n8n

An AI-powered workflow built with **n8n** that automates social media content generation from Google Sheets. The workflow uses AI to create engaging content and can publish it directly to **X (Twitter)**. Although this implementation uses X, the workflow can easily be extended to support platforms like **LinkedIn, Facebook, Instagram, YouTube, and WordPress**.

---

## 📌 Features

- 📄 Reads content ideas from Google Sheets
- 🤖 Generates AI-powered social media posts
- 📝 Uses customizable system and user prompts
- ⚡ Automatically publishes posts to X (Twitter)
- 🔄 Supports both manual execution and automatic triggers
- 📊 Easily adaptable for multiple social media platforms
- 🛠️ Modular workflow for future enhancements

---

## 🏗️ Workflow Overview

```
Google Sheets Trigger
        │
        ▼
Read Pending Content
        │
        ▼
Load Prompt Templates
        │
        ▼
JavaScript
(Replace Variables)
        │
        ▼
OpenAI Model
        │
        ▼
Format Output
        │
        ▼
Publish to X (Twitter)
```

---

## ⚙️ Technologies Used

- n8n
- OpenAI API
- Google Sheets API
- JavaScript
- X (Twitter) API

---

## 📂 Workflow

The workflow performs the following steps:

1. Trigger manually or when a new row is added to Google Sheets.
2. Fetch pending content from the sheet.
3. Load reusable prompt templates.
4. Replace placeholders dynamically using JavaScript.
5. Send the prompt to the OpenAI model.
6. Clean and format the AI response.
7. Publish the generated content to X (Twitter).

---

## 🔮 Future Enhancements

This workflow currently posts to **X (Twitter)**, but it is designed in a way that it can easily support additional platforms, including:

- 💼 LinkedIn
- 📘 Facebook
- 📸 Instagram
- 🎥 YouTube
- 📝 WordPress
- 🧵 Threads
- 💬 Telegram

Adding these platforms requires only the corresponding API node after the AI generation step.

---

---

## 📁 Repository Structure

```
.
├── workflow.json
├── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/ai-content-automation-n8n.git
```

### 2. Import the workflow

- Open n8n.
- Click **Import Workflow**.
- Select the `workflow.json` file.

### 3. Configure Credentials

Add your credentials for:

- Google Sheets
- OpenAI
- X (Twitter)

### 4. Execute the workflow

Run manually or enable the Google Sheets trigger to automate content generation.

---

## 📚 Learning Outcomes

Through this project, I gained hands-on experience with:

- Workflow Automation
- AI Integration
- Prompt Engineering
- Google Sheets Automation
- API Integration
- JavaScript in n8n
- No-Code/Low-Code Development

---

## 🤝 Contributions

Contributions, suggestions, and feature requests are always welcome.

If you find this project useful, consider giving it a ⭐.

---

## 👩‍💻 Author

**Ayesha Nagma**

LinkedIn: https://www.linkedin.com/in/ayesha-nagma-827336277/

---

## 📄 License

This project is licensed under the MIT License.
