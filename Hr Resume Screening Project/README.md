🚀 HR Screening AI Agent

An automated AI-powered recruitment workflow that screens resumes, evaluates candidates using LLM-based scoring, and streamlines the hiring process with end-to-end automation.

📌 Overview

This project automates the manual process of resume screening by integrating an AI-driven evaluation pipeline. It ingests resumes from emails, analyzes them using an LLM, and performs automated shortlisting with real-time communication.

⚙️ Workflow Pipeline

The system follows an event-driven pipeline:

📩 Email Trigger – Fetch resumes from incoming emails
📄 Resume Processing – Extract relevant candidate information
🧠 LLM Evaluation – Use Google Gemini to analyze resumes against job requirements
📊 Fit Score Generation – Assign candidate scores based on relevance
⚖️ Decision Logic – Shortlist or reject candidates
📧 Automated Communication – Send offer/rejection emails
📁 Data Storage – Store results in Google Sheets
🧠 Key Features
🤖 AI-based resume evaluation using LLMs
🔄 Fully automated recruitment workflow
📊 Candidate scoring and ranking system
📧 Automated email responses (offer/rejection)
📁 Structured result storage in Google Sheets
⚡ Real-time processing via n8n
🛠️ Tech Stack
Automation: n8n
AI/LLM: Google Gemini API
Processing: NLP-based text extraction
Storage: Google Sheets
Integration: Email triggers & automation workflows
📸 Screenshots
🔁 Workflow Pipeline

📩 Email Trigger

📊 Fit Score Output

📁 Google Sheets Storage

📂 Project Structure
hr-screening-ai-agent/
│── README.md
│── workflow/
│     └── n8n_workflow.json
│── screenshots/
│     ├── workflow.png
│     ├── email_trigger.png
│     ├── output_score.png
│     ├── sheets_output.png
▶️ How to Use
Import the workflow file:
Open n8n
Import n8n_workflow.json
Configure:
Email credentials
Gemini API key
Google Sheets access
Run the workflow:
Send resumes via email
System automatically processes and responds
⚠️ Note

This project was built and tested using n8n during its free trial period.
Due to plan limitations, the workflow is not currently deployed.

However:

✅ Complete workflow JSON is provided
✅ Execution screenshots are included
✅ Workflow can be re-imported and executed with proper credentials
🎯 Impact
Reduced manual resume screening effort
Automated candidate shortlisting and communication
Improved response time in recruitment workflows
🔮 Future Improvements
Add advanced scoring using embeddings
Integrate vector databases for better matching
Build dashboard for HR analytics
Deploy using scalable backend services
👨‍💻 Author

Dhanunjaya Reddy

GitHub: https://github.com/Dhanunjaya18
LinkedIn: https://www.linkedin.com/in/dhanunjaya--reddy/
⭐ Final Note

This project demonstrates a real-world AI agent pipeline integrating LLM-based decision-making with workflow automation to solve practical recruitment challenges.