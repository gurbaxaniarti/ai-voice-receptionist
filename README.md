# 🤖 AI Voice Receptionist

An end-to-end AI-powered voice receptionist that automates customer call handling, appointment booking, and scheduling workflows for service-based businesses.

Built using **Vapi, Twilio, Make, OpenAI, Google Calendar, and Google Sheets**, this system operates 24/7, handles multiple concurrent calls, and eliminates the need for a human front desk.

---

## 🚀 Key Features

- 📞 Real-time AI voice conversations
- 🧠 Natural language understanding using LLMs
- 📅 Intelligent appointment scheduling
- 🔁 Appointment cancellation handling
- ⚠️ Conflict detection & alternate slot suggestions
- 🕒 Time zone-aware scheduling (U.S. focused)
- 📩 Automated SMS confirmations
- 📊 Customer data capture in Google Sheets
- 🔄 Workflow automation using Make
- ☎️ Handles multiple calls simultaneously (no hold time)

---

## 🏗️ System Architecture

The system integrates multiple platforms to create a seamless automated receptionist experience:

- **Twilio** → Handles telephony (incoming/outgoing calls + SMS)
- **Vapi** → Manages voice AI conversations
- **OpenAI (LLM)** → Understands intent and drives conversation logic
- **Make (Integromat)** → Orchestrates workflows and automation
- **Google Calendar** → Stores and validates appointments
- **Google Sheets** → Stores customer and booking data

---

## 🔄 How It Works

1. 📞 Customer calls the business number (Twilio)
2. 🤖 Vapi AI agent answers and interacts naturally
3. 🧠 LLM understands intent (book / cancel / inquire)
4. 🔄 Make triggers workflows based on user intent:
   - Check availability
   - Detect conflicts
   - Suggest alternate slots
5. 📅 Google Calendar is updated
6. 📊 Customer details stored in Google Sheets
7. 📩 SMS confirmation sent via Twilio

---

## ⚙️ Workflows Implemented

### 1. Appointment Booking
- Checks available slots
- Handles conflicts
- Suggests alternatives
- Books confirmed slot

### 2. Appointment Cancellation
- Identifies booking
- Cancels from calendar
- Updates records

---

## 🧠 Key Technical Capabilities

- Conversational AI & prompt engineering
- Real-time voice processing
- Multi-system API integration
- Workflow orchestration
- Conflict detection logic
- Time-zone normalization (PST)
- Scalable concurrent call handling

---

## 🛠️ Tech Stack

| Component | Technology |
|----------|-----------|
| Telephony | Twilio |
| Voice AI | Vapi |
| LLM | OpenAI |
| Automation | Make |
| Calendar | Google Calendar |
| Data Storage | Google Sheets |
| Messaging | Twilio SMS |

---

## 👩‍💻 My Role

As the sole developer and solution architect, I:

- Designed the complete system architecture
- Built and optimized conversational flows
- Implemented booking & cancellation logic
- Integrated all external systems (Twilio, Vapi, Make, Google APIs)
- Developed automation workflows
- Tested and validated end-to-end scenarios
- Improved conversation quality and reliability

---

## 📈 Business Impact

- 24/7 automated call handling
- Eliminates missed calls
- Reduces operational costs
- No customer hold times
- Scales without hiring more staff
- Improves booking conversion rates
- Ensures accurate scheduling via real-time validation

---

## 📌 Future Improvements

- Payment integration for bookings
- Multi-language support
- CRM integration (HubSpot/Salesforce)
- Voice personalization
- Analytics dashboard

---

## 📽️ Demo

https://www.linkedin.com/posts/artigurbaxani_ibuiltthiswithai-genai-dataengineering-ugcPost-7471633414757134336-LDTJ/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAA_XuhsBwh8qMVUti7TZxcHfyj1B4o5vQwE

---

## 📬 Contact

If you're interested in this project or want to collaborate:

- LinkedIn: linkedin.com/in/artigurbaxani
