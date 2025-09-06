# AI Event Scheduler

The AI Event Scheduler is an automation workflow built with n8n that simplifies event scheduling and task management through natural language interaction. By combining Google Calendar, Google Sheets, and an AI agent powered by Google Gemini Chat Model, this project converts everyday language into structured event and task data—making scheduling seamless and intuitive.

-----

## 📖 Overview

- **n8n Automation** – Orchestrates the entire process by receiving chat inputs, extracting event details, and triggering the correct actions
- **AI-Powered Interaction** – Natural language inputs are processed by a Gemini Chat Model to extract key details like start time, end time, and event summary
- **Google Services Integration**:
  - **Google Calendar** – Automatically creates and retrieves events
  - **Google Sheets** – Stores, retrieves, and appends event or task details for record-keeping
- **Memory Buffer** – Maintains conversational context with window buffer memory, enabling more natural and consistent interactions

-----

## ✨ Features

- **Chat Trigger** – The workflow is initiated through a chat message
- **AI Agent Integration** – Processes user messages using the Google Gemini Chat Model
- **Google Calendar**:
  - Creates events with a defined start time, end time, and summary
  - Retrieves events within user-defined time intervals
- **Google Sheets**:
  - Retrieves event/task details
  - Appends new tasks with attributes like task name, description, due date, and priority
- **Consistent Date Format** – Ensures all dates follow the MM/DD/YYYY structure for clarity

-----

## ⚙️ Prerequisites

- **n8n Instance** – Active deployment of n8n for workflow automation
- **Google API Credentials** – Required for Google Calendar and Google Sheets integration
- **AI Agent Credentials** – Set up credentials for the Google Gemini Chat Model

-----

## 🚀 Setup Instructions

1. **Clone the Repository**:
   
   ```bash
   git clone https://github.com/PrincessNosawema/ai-event-scheduler.git
   ```
1. **Import Workflow into n8n**
- Open n8n and import the provided workflow file
1. **Configure Google Services**
- Add Google API credentials for Calendar and Sheets
1. **Set Up AI Agent**
- Configure Gemini Chat Model API credentials
1. **Run & Test**
- Initiate the workflow via chat message
- Verify events and tasks are properly logged in Calendar and Sheets

-----

## ⚖️ License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
