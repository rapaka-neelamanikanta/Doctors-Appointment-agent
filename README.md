# Doctors-Appointment-n8n-
Built an AI-powered WhatsApp doctor appointment booking system using n8n workflows. Integrated Google Gemini LLM for natural language understanding and intent detection.
# 🏥 AI-Powered Doctor Appointment Booking System
### WhatsApp + n8n + Google Gemini AI

An AI-driven doctor appointment booking system that allows patients to book, cancel, and reschedule appointments through WhatsApp using an intelligent n8n AI agent.

---

## 🚀 Project Overview

This project demonstrates how to build a real-world AI agent using **n8n**, **WhatsApp Business Cloud API**, and **Google Gemini**.  
The AI agent understands natural language messages from users and performs appointment-related actions automatically.

---

## 🛠️ Tech Stack

- **n8n** – Workflow Automation & AI Agent Orchestration  
- **WhatsApp Business Cloud API** – Patient Interaction  
- **Google Gemini API** – Conversational AI & Intent Detection  
- **Google Sheets** – Appointment & Patient Data Storage  

---

## 🧩 System Architecture

1. Patient sends a message via WhatsApp
2. WhatsApp Cloud API triggers n8n workflow
3. AI Agent processes intent using Gemini LLM
4. Memory stores conversation context
5. Tool actions update appointment records
6. Response sent back to WhatsApp

📌 *Architecture diagram available in `/architecture` folder*

---

## ✨ Features

- 📅 Book doctor appointments
- ❌ Cancel appointments
- 🔄 Reschedule appointments
- 🧠 AI-powered natural language understanding
- 💾 Persistent conversation memory
- 📊 Google Sheets backend for appointments

---

## 🗂️ Data Schema (Google Sheets)

| Column Name | Description |
|------------|-------------|
| Patient Name | Name of patient |
| Phone Number | WhatsApp number |
| Doctor Name | Assigned doctor |
| Appointment Date | Scheduled date |
| Time Slot | Appointment time |
| Status | Booked / Cancelled / Rescheduled |

---

## ⚙️ How to Run This Project

1. Clone this repository  
2. Import n8n workflow JSON files
3. Configure:
   - WhatsApp Business Cloud API
   - Google Gemini API key
   - Google Sheets credentials
4. Deploy n8n workflow
5. Send a message to WhatsApp test number

---

## 📸 Screenshots

Screenshots of WhatsApp chat, n8n workflows, and Google Sheets are available in `/screenshots`.
<img src="[images/workflow.png](https://raw.githubusercontent.com/nagabharath2003/Doctors-Appointment-n8n-/refs/heads/main/capture_20251215133350261.bmp)" width="600"/>

---
