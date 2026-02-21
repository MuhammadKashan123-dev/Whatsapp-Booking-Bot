# Whatsapp-Booking-Bot
A Whatsapp AI Booking Bot. Which is made using N8N workflow. 

#  AI WhatsApp Booking Bot

##  Overview
The AI WhatsApp Booking Bot is an automated appointment booking system built using n8n.  
It allows users to book time slots through WhatsApp while preventing duplicate bookings.

This system demonstrates workflow automation, API integration, and AI-based message handling.

---

##  Features

-  Checks available time slots
-  Prevents double booking
-  AI-powered message understanding
-  Stores booking data in Google Sheets
-  Conditional workflow logic
-  Automated WhatsApp responses

---

## Tech Stack

- n8n (Workflow Automation)
- WhatsApp Integration
- Google Sheets API
- AI Agent (for input processing)

---

##  How It Works

1. User sends a message on WhatsApp.
2. Bot asks for preferred time.
3. System checks Google Sheets for availability.
4. If available:
   - Books the slot
   - Stores user data
   - Sends confirmation message
5. If not available:
   - Sends apology message
   - Suggests other time slots

---

##  Workflow Logic

- WhatsApp Trigger
- AI Agent Node (extracts time)
- Google Sheets Get Row(s)
- IF Node (checks availability)
- Append Row (if available)
- Send Confirmation / Rejection Message

---

##  Purpose

This project was built to demonstrate:
- Automation system design
- API-based integrations
- Conditional workflow logic
- Real-world chatbot development

---

## 📬 Contact

LinkedIn: https://www.linkedin.com/in/muhammad-kashan-431696381/
---
