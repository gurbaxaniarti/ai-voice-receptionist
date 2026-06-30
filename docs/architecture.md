# System Architecture

This project is built using a modular AI + automation architecture:

## Components

- Twilio → Handles phone calls and SMS
- Vapi → Voice AI agent
- OpenAI → Intent understanding and response generation
- Make → Workflow orchestration
- Google Calendar → Appointment scheduling
- Google Sheets → Data storage

## Flow

1. Incoming call via Twilio
2. Routed to Vapi AI agent
3. AI interacts with user using OpenAI
4. Make triggers workflows:
   - Check availability
   - Book appointment
   - Cancel appointment
5. Data stored in Google Sheets
6. Confirmation sent via SMS

## Design Principles

- Scalable (handles multiple calls)
- Modular (each system independent)
- Real-time processing
- Fault-tolerant workflows
  
## AI Decision Layer (RAG System)

The system uses a retrieval-based approach to help patients select the appropriate doctor.

### How it works:

1. Patient describes symptoms during the call
2. AI agent matches symptoms with doctor specialties using a structured knowledge base
3. Relevant doctor is suggested to the patient
4. Appointment booking workflow is triggered for the selected doctor

### Data Source:
- Doctor directory with:
  - Specialties
  - Symptoms handled
  - Age group constraints
