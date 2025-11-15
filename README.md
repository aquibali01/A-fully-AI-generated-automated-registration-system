# AI-Powered Event Registration System  
### Built with Google Build + n8n + Vibe Coding

This repository contains a complete **no-code event registration automation** created using **Google Build** for the website and **n8n** for the backend workflow.

The system was built as a **non-official appreciation project** for the impactful training delivered by **Sir Hisham**.

---

## 🚀 Features

### 🌐 Website (Generated using Google Build)
- AI-generated hero section  
- Countdown timer  
- Event date & time  
- “What you’ll learn” section  
- Trailer video embed  
- Registration form popup  
- Fully built via prompts (no manual coding)

---

## ⚙️ Automation Workflow (n8n)

The automation consists of:

### **1. Webhook Trigger**
Receives the form submission from the website.

### **2. JSON Body Parser**
Extracts the clean fields:
- `name`  
- `email`  
- `question`

### **3. Google Sheets Integration**
Automatically logs every attendee into a Google Sheet for record-keeping.

### **4. Email Notification**
Sends a confirmation email to the attendee after successful registration.

---

## 🧪 Example Workflow

1. User fills in the form on the website  
2. Data is sent to the Webhook in n8n  
3. Workflow parses and cleans the data  
4. Google Sheet is updated  
5. Email confirmation is sent  

Everything happens **instantly and automatically**.

---

## 🎯 Purpose

This project demonstrates how AI + No-Code + Automation can build a complete operational system **within hours**, without traditional development.

---

## 📩 Contact

If you want to automate your business or need help building similar workflows:

**Aqib Ali**  
AI & Automation Freelancer  
Twitter / LinkedIn: *@aquibali*  

---

## 📌 Disclaimer
This project is **not affiliated with or officially endorsed** by the event or trainer.  
It was built purely as a **practice and appreciation project**.
