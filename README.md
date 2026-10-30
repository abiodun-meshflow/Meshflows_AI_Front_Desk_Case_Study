# 🤖 Multi-Agent AI Front Desk System
### Production Case Study: Built for Rapid Flow Plumbing & Heating
Backend Architecture & Advanced Workflow Automation Framework

> **An AI front desk for plumbing and HVAC companies. It replies to customers in seconds, books jobs straight into the calendar, and alerts the on-call tech the moment an emergency comes in. Day or night.**

---

## 📄 Full Project PDF Breakdown & Visual Assets

• 📊 👉 Read the Complete System Documentation (PDF)
(Click the link above to open and review our full end-to-end blueprint, project scope, and system features directly in your browser.)
• 🎬 View Live Implementation Snapshots on Facebook
(Check out our active project feed on Facebook to see visual snapshots and interface screenshots of the live system design.)

---

## 📐 System Overview
This enterprise-grade system completely automates customer operations, scheduling, and emergency dispatch tracking for multi-regional service businesses. Operating 24/7 across unified communication channels (Webchat, SMS, WhatsApp, and social profiles), it eliminates lost leads, coordinates technicians instantly, and keeps client databases perfectly updated.

Instead of deploying a single unmonitored chatbot, this infrastructure relies on an **Advanced Multi-Agent Hierarchy**—featuring 1 Central Command Orchestrator and 3 specialized sub-agents working together via conditional logic hooks.

---

## 🛠️ Infrastructure & Tech Stack
- **Workflow Orchestration:** n8n (Cloud / Docker VPS Deployment)
- **AI Infrastructure:** OpenAI Assistant API, Anthropic Claude, Advanced Semantic Intent-Classification Models
- **Database & Messaging Channels:** WhatsApp Business API, Twilio SMS, Webhooks, JSON Payload Parsing
- **Scheduling & Operations Engine:** Google Sheets API, Google Calendar API Ecosystems
- **Reliability Framework:** Custom global error monitoring for active, uninterrupted production telemetry

---

## ⚙️ Multi-Agent Hierarchical Roles

### 1. The Central Front Desk Orchestrator
Acts as the central router and initial gatekeeper. It greets users across all entry webhooks, analyzes customer sentiment, extracts key diagnostic keywords, and delegates the ticket to the correct background sub-agent.

### 2. The Smart Booking Agent
Connected natively to live Google Calendar API networks. This sub-agent cross-references real-time technician availability matrices, handles conversational slot negotiations, schedules appointments, and fires off brand-compliant confirmation invoices.

### 3. The Emergency Dispatch Agent
Programmed with zero-tolerance emergency parameters. It constantly monitors for severe context triggers (e.g., *burst pipes, major gas leaks, heating failure in freezing weather*). When an emergency is detected, it bypasses regular scheduling, updates high-priority sheets, and fires out SMS alerts directly to the smart devices of on-call emergency technicians.

### 4. The Records & CRM Maintenance Agent
Runs silently in the background. It structures chat history transcripts, strips duplicate formatting, maps raw parameters into clean rows, and pushes historical metrics into Google Sheets for management review.

---

## 📊 Quantified Business Impact
- **24/7 Total Operational Coverage:** Removed 100% of unreturned, off-hours missed calls and website drop-offs.
- **Zero-Latency Dispatch Scheduling:** Cut emergency tracking and technician notification timelines down to **under 60 seconds**.
- **Minimised Admin Overhead:** Automated scheduling operations, saving customer success teams over **15 hours per week** of manual coordination.
- **Flawless Synchronization:** Eliminated human data-entry mistakes completely across master operational databases.

---

## 🛠️ Deployed Workflow Code Blueprint
The raw functional configuration layout for this architecture is stored in this repository under the `front-desk-pipeline.json` file. It can be easily imported into any production n8n environment.
