# ImageCaptionGenerator
# 📸 AI Image Caption Generator (n8n + Gemini)

An automated workflow built using **n8n** that generates aesthetic captions for uploaded images using **Google Gemini AI** and delivers them directly via email.

---

## 🚀 Features

- 📤 Upload image via form
- 🧠 AI-generated aesthetic captions
- ✍️ Custom user prompt support
- 📧 Automatic email delivery
- ⚡ Fully automated workflow (no manual steps)
- 🗂 File handling using n8n storage

---

## 🛠 Tech Stack

- **n8n** – Workflow automation  
- **Google Gemini AI** – Caption generation  
- **Gmail API** – Email delivery  
- **HTML Form (n8n Form Trigger)** – User input  
- **File System** – Image storage  

---

## 🔄 Workflow Overview

1. User uploads an image via form
2. Image is stored using Read/Write node
3. AI Agent processes:
   - Image filename
   - Optional user prompt
4. Google Gemini generates caption
5. Caption is sent to user email automatically

---

## 🧩 Nodes Used

- **Form Trigger** → Collects image & user input  
- **Read/Write File** → Saves uploaded image  
- **AI Agent (LangChain)** → Processes prompt  
- **Google Gemini Chat Model** → Generates caption  
- **Gmail Node** → Sends email  

---

## 📸 Use Case

- Instagram caption generator  
- Social media automation  
- AI content tools  
- Marketing automation  

---

## ⚙️ Setup Instructions

### 1️⃣ Import Workflow
- Open n8n
- Import the provided JSON file

---

### 2️⃣ Configure Credentials

- Add **Google Gemini API**
- Connect **Gmail OAuth2**

---

### 3️⃣ Run Workflow

- Activate workflow
- Open form URL
- Upload image + email
- Receive caption instantly 📩

---

